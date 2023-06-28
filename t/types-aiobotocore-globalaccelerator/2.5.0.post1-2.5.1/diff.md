# Comparing `tmp/types-aiobotocore-globalaccelerator-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-globalaccelerator-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-globalaccelerator-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:41 2023, max compression
+gzip compressed data, was "types-aiobotocore-globalaccelerator-2.5.1.tar", last modified: Wed Jun 28 01:43:32 2023, max compression
```

## Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1.tar` & `types-aiobotocore-globalaccelerator-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.395244 types-aiobotocore-globalaccelerator-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20890 2023-03-11 12:26:41.391244 types-aiobotocore-globalaccelerator-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19279 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:41.395244 types-aiobotocore-globalaccelerator-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.383244 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/
--rw-r--r--   0 runner    (1001) docker     (123)     2559 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2558 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    43795 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    43729 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9857 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9855 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11218 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11207 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    44658 2023-03-11 12:15:06.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    44609 2023-03-11 12:15:05.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:04.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.391244 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20890 2023-03-11 12:26:41.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-03-11 12:26:41.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:41.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:41.000000 types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:32.826143 types-aiobotocore-globalaccelerator-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:40.000000 types-aiobotocore-globalaccelerator-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20892 2023-06-28 01:43:32.826143 types-aiobotocore-globalaccelerator-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19287 2023-06-28 01:31:40.000000 types-aiobotocore-globalaccelerator-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:32.826143 types-aiobotocore-globalaccelerator-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2204 2023-06-28 01:31:40.000000 types-aiobotocore-globalaccelerator-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:32.826143 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/
+-rw-r--r--   0 runner    (1001) docker     (123)     2559 2023-06-28 01:31:40.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2558 2023-06-28 01:31:40.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43795 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43729 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10066 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10064 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11114 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11104 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    44750 2023-06-28 01:31:42.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44701 2023-06-28 01:31:41.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:40.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:32.826143 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20892 2023-06-28 01:43:32.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:43:32.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:32.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:32.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:32.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:32.000000 types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/LICENSE` & `types-aiobotocore-globalaccelerator-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/PKG-INFO` & `types-aiobotocore-globalaccelerator-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-globalaccelerator
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GlobalAccelerator 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GlobalAccelerator 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-globalaccelerator"></a>
 
 # types-aiobotocore-globalaccelerator
 
 [![PyPI - types-aiobotocore-globalaccelerator](https://img.shields.io/pypi/v/types-aiobotocore-globalaccelerator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-globalaccelerator)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-globalaccelerator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-globalaccelerator)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-globalaccelerator?color=blue)](https://pypistats.org/packages/types-aiobotocore-globalaccelerator)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GlobalAccelerator 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator)
+[aiobotocore.GlobalAccelerator 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator)
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
 [types-aiobotocore-globalaccelerator docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/).
 
 See how it helps to find and fix potential bugs:
 
@@ -364,15 +364,14 @@
 ```python
 from types_aiobotocore_globalaccelerator.type_defs import (
     AcceleratorAttributesTypeDef,
     AcceleratorEventTypeDef,
     IpSetTypeDef,
     CustomRoutingEndpointConfigurationTypeDef,
     CustomRoutingEndpointDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     EndpointConfigurationTypeDef,
     EndpointDescriptionTypeDef,
     AdvertiseByoipCidrRequestRequestTypeDef,
     AllowCustomRoutingTrafficRequestRequestTypeDef,
     ByoipCidrEventTypeDef,
     CidrAuthorizationContextTypeDef,
     TagTypeDef,
@@ -394,40 +393,49 @@
     DescribeCustomRoutingAcceleratorAttributesRequestRequestTypeDef,
     DescribeCustomRoutingAcceleratorRequestRequestTypeDef,
     DescribeCustomRoutingEndpointGroupRequestRequestTypeDef,
     DescribeCustomRoutingListenerRequestRequestTypeDef,
     DescribeEndpointGroupRequestRequestTypeDef,
     DescribeListenerRequestRequestTypeDef,
     SocketAddressTypeDef,
+    EmptyResponseMetadataTypeDef,
     EndpointIdentifierTypeDef,
-    PaginatorConfigTypeDef,
+    ListAcceleratorsRequestListAcceleratorsPaginateTypeDef,
     ListAcceleratorsRequestRequestTypeDef,
+    ListByoipCidrsRequestListByoipCidrsPaginateTypeDef,
     ListByoipCidrsRequestRequestTypeDef,
+    ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef,
     ListCustomRoutingAcceleratorsRequestRequestTypeDef,
     ListCustomRoutingEndpointGroupsRequestRequestTypeDef,
+    ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
     ListCustomRoutingListenersRequestRequestTypeDef,
+    ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
     ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
+    ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
     ListCustomRoutingPortMappingsRequestRequestTypeDef,
+    ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
     ListEndpointGroupsRequestRequestTypeDef,
+    ListListenersRequestListListenersPaginateTypeDef,
     ListListenersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     RemoveCustomRoutingEndpointsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAcceleratorAttributesRequestRequestTypeDef,
     UpdateAcceleratorRequestRequestTypeDef,
     UpdateCustomRoutingAcceleratorAttributesRequestRequestTypeDef,
     UpdateCustomRoutingAcceleratorRequestRequestTypeDef,
     WithdrawByoipCidrRequestRequestTypeDef,
+    DescribeAcceleratorAttributesResponseTypeDef,
+    UpdateAcceleratorAttributesResponseTypeDef,
     AcceleratorTypeDef,
     CustomRoutingAcceleratorTypeDef,
     AddCustomRoutingEndpointsRequestRequestTypeDef,
     AddCustomRoutingEndpointsResponseTypeDef,
-    DescribeAcceleratorAttributesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    UpdateAcceleratorAttributesResponseTypeDef,
     AddEndpointsRequestRequestTypeDef,
     AddEndpointsResponseTypeDef,
     ByoipCidrTypeDef,
     ProvisionByoipCidrRequestRequestTypeDef,
     CreateAcceleratorRequestRequestTypeDef,
     CreateCustomRoutingAcceleratorRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -444,22 +452,14 @@
     UpdateEndpointGroupRequestRequestTypeDef,
     DescribeCustomRoutingAcceleratorAttributesResponseTypeDef,
     UpdateCustomRoutingAcceleratorAttributesResponseTypeDef,
     CustomRoutingEndpointGroupTypeDef,
     DestinationPortMappingTypeDef,
     PortMappingTypeDef,
     RemoveEndpointsRequestRequestTypeDef,
-    ListAcceleratorsRequestListAcceleratorsPaginateTypeDef,
-    ListByoipCidrsRequestListByoipCidrsPaginateTypeDef,
-    ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef,
-    ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-    ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-    ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-    ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-    ListListenersRequestListListenersPaginateTypeDef,
     CreateAcceleratorResponseTypeDef,
     DescribeAcceleratorResponseTypeDef,
     ListAcceleratorsResponseTypeDef,
     UpdateAcceleratorResponseTypeDef,
     CreateCustomRoutingAcceleratorResponseTypeDef,
     DescribeCustomRoutingAcceleratorResponseTypeDef,
     ListCustomRoutingAcceleratorsResponseTypeDef,
@@ -496,43 +496,43 @@
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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/README.md` & `types-aiobotocore-globalaccelerator-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-globalaccelerator"></a>
 
 # types-aiobotocore-globalaccelerator
 
 [![PyPI - types-aiobotocore-globalaccelerator](https://img.shields.io/pypi/v/types-aiobotocore-globalaccelerator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-globalaccelerator)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-globalaccelerator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-globalaccelerator)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-globalaccelerator?color=blue)](https://pypistats.org/packages/types-aiobotocore-globalaccelerator)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GlobalAccelerator 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator)
+[aiobotocore.GlobalAccelerator 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator)
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
 [types-aiobotocore-globalaccelerator docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,15 +331,14 @@
 ```python
 from types_aiobotocore_globalaccelerator.type_defs import (
     AcceleratorAttributesTypeDef,
     AcceleratorEventTypeDef,
     IpSetTypeDef,
     CustomRoutingEndpointConfigurationTypeDef,
     CustomRoutingEndpointDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     EndpointConfigurationTypeDef,
     EndpointDescriptionTypeDef,
     AdvertiseByoipCidrRequestRequestTypeDef,
     AllowCustomRoutingTrafficRequestRequestTypeDef,
     ByoipCidrEventTypeDef,
     CidrAuthorizationContextTypeDef,
     TagTypeDef,
@@ -361,40 +360,49 @@
     DescribeCustomRoutingAcceleratorAttributesRequestRequestTypeDef,
     DescribeCustomRoutingAcceleratorRequestRequestTypeDef,
     DescribeCustomRoutingEndpointGroupRequestRequestTypeDef,
     DescribeCustomRoutingListenerRequestRequestTypeDef,
     DescribeEndpointGroupRequestRequestTypeDef,
     DescribeListenerRequestRequestTypeDef,
     SocketAddressTypeDef,
+    EmptyResponseMetadataTypeDef,
     EndpointIdentifierTypeDef,
-    PaginatorConfigTypeDef,
+    ListAcceleratorsRequestListAcceleratorsPaginateTypeDef,
     ListAcceleratorsRequestRequestTypeDef,
+    ListByoipCidrsRequestListByoipCidrsPaginateTypeDef,
     ListByoipCidrsRequestRequestTypeDef,
+    ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef,
     ListCustomRoutingAcceleratorsRequestRequestTypeDef,
     ListCustomRoutingEndpointGroupsRequestRequestTypeDef,
+    ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
     ListCustomRoutingListenersRequestRequestTypeDef,
+    ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
     ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
+    ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
     ListCustomRoutingPortMappingsRequestRequestTypeDef,
+    ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
     ListEndpointGroupsRequestRequestTypeDef,
+    ListListenersRequestListListenersPaginateTypeDef,
     ListListenersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     RemoveCustomRoutingEndpointsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAcceleratorAttributesRequestRequestTypeDef,
     UpdateAcceleratorRequestRequestTypeDef,
     UpdateCustomRoutingAcceleratorAttributesRequestRequestTypeDef,
     UpdateCustomRoutingAcceleratorRequestRequestTypeDef,
     WithdrawByoipCidrRequestRequestTypeDef,
+    DescribeAcceleratorAttributesResponseTypeDef,
+    UpdateAcceleratorAttributesResponseTypeDef,
     AcceleratorTypeDef,
     CustomRoutingAcceleratorTypeDef,
     AddCustomRoutingEndpointsRequestRequestTypeDef,
     AddCustomRoutingEndpointsResponseTypeDef,
-    DescribeAcceleratorAttributesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    UpdateAcceleratorAttributesResponseTypeDef,
     AddEndpointsRequestRequestTypeDef,
     AddEndpointsResponseTypeDef,
     ByoipCidrTypeDef,
     ProvisionByoipCidrRequestRequestTypeDef,
     CreateAcceleratorRequestRequestTypeDef,
     CreateCustomRoutingAcceleratorRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -411,22 +419,14 @@
     UpdateEndpointGroupRequestRequestTypeDef,
     DescribeCustomRoutingAcceleratorAttributesResponseTypeDef,
     UpdateCustomRoutingAcceleratorAttributesResponseTypeDef,
     CustomRoutingEndpointGroupTypeDef,
     DestinationPortMappingTypeDef,
     PortMappingTypeDef,
     RemoveEndpointsRequestRequestTypeDef,
-    ListAcceleratorsRequestListAcceleratorsPaginateTypeDef,
-    ListByoipCidrsRequestListByoipCidrsPaginateTypeDef,
-    ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef,
-    ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-    ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-    ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-    ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-    ListListenersRequestListListenersPaginateTypeDef,
     CreateAcceleratorResponseTypeDef,
     DescribeAcceleratorResponseTypeDef,
     ListAcceleratorsResponseTypeDef,
     UpdateAcceleratorResponseTypeDef,
     CreateCustomRoutingAcceleratorResponseTypeDef,
     DescribeCustomRoutingAcceleratorResponseTypeDef,
     ListCustomRoutingAcceleratorsResponseTypeDef,
@@ -463,43 +463,43 @@
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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/setup.py` & `types-aiobotocore-globalaccelerator-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-globalaccelerator.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-globalaccelerator",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_globalaccelerator"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.GlobalAccelerator 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.GlobalAccelerator 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/"
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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/__init__.py` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/__init__.pyi` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/client.py` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/client.pyi` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/literals.py` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/literals.py`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/literals.pyi` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/literals.pyi`

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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/paginator.py` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_custom_routing_listeners_paginator: ListCustomRoutingListenersPaginator = client.get_paginator("list_custom_routing_listeners")
         list_custom_routing_port_mappings_paginator: ListCustomRoutingPortMappingsPaginator = client.get_paginator("list_custom_routing_port_mappings")
         list_custom_routing_port_mappings_by_destination_paginator: ListCustomRoutingPortMappingsByDestinationPaginator = client.get_paginator("list_custom_routing_port_mappings_by_destination")
         list_endpoint_groups_paginator: ListEndpointGroupsPaginator = client.get_paginator("list_endpoint_groups")
         list_listeners_paginator: ListListenersPaginator = client.get_paginator("list_listeners")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAcceleratorsResponseTypeDef,
     ListByoipCidrsResponseTypeDef,
@@ -48,20 +47,14 @@
     ListCustomRoutingPortMappingsByDestinationResponseTypeDef,
     ListCustomRoutingPortMappingsResponseTypeDef,
     ListEndpointGroupsResponseTypeDef,
     ListListenersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAcceleratorsPaginator",
     "ListByoipCidrsPaginator",
     "ListCustomRoutingAcceleratorsPaginator",
     "ListCustomRoutingListenersPaginator",
     "ListCustomRoutingPortMappingsPaginator",
     "ListCustomRoutingPortMappingsByDestinationPaginator",
@@ -83,60 +76,60 @@
 class ListAcceleratorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListAccelerators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listacceleratorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAcceleratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListAccelerators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listacceleratorspaginator)
         """
 
 
 class ListByoipCidrsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListByoipCidrs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listbyoipcidrspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListByoipCidrsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListByoipCidrs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listbyoipcidrspaginator)
         """
 
 
 class ListCustomRoutingAcceleratorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingAccelerators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingacceleratorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingAcceleratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingAccelerators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingacceleratorspaginator)
         """
 
 
 class ListCustomRoutingListenersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingListeners)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutinglistenerspaginator)
     """
 
     def paginate(
-        self, *, AcceleratorArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceleratorArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingListenersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingListeners.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutinglistenerspaginator)
         """
 
 
@@ -147,15 +140,15 @@
     """
 
     def paginate(
         self,
         *,
         AcceleratorArn: str,
         EndpointGroupArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingPortMappingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingPortMappings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingportmappingspaginator)
         """
 
 
@@ -166,43 +159,43 @@
     """
 
     def paginate(
         self,
         *,
         EndpointId: str,
         DestinationAddress: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingPortMappingsByDestinationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingPortMappingsByDestination.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingportmappingsbydestinationpaginator)
         """
 
 
 class ListEndpointGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListEndpointGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listendpointgroupspaginator)
     """
 
     def paginate(
-        self, *, ListenerArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ListenerArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListEndpointGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listendpointgroupspaginator)
         """
 
 
 class ListListenersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListListeners)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listlistenerspaginator)
     """
 
     def paginate(
-        self, *, AcceleratorArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceleratorArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListListenersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListListeners.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listlistenerspaginator)
         """
```

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/paginator.pyi` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_custom_routing_listeners_paginator: ListCustomRoutingListenersPaginator = client.get_paginator("list_custom_routing_listeners")
         list_custom_routing_port_mappings_paginator: ListCustomRoutingPortMappingsPaginator = client.get_paginator("list_custom_routing_port_mappings")
         list_custom_routing_port_mappings_by_destination_paginator: ListCustomRoutingPortMappingsByDestinationPaginator = client.get_paginator("list_custom_routing_port_mappings_by_destination")
         list_endpoint_groups_paginator: ListEndpointGroupsPaginator = client.get_paginator("list_endpoint_groups")
         list_listeners_paginator: ListListenersPaginator = client.get_paginator("list_listeners")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAcceleratorsResponseTypeDef,
     ListByoipCidrsResponseTypeDef,
@@ -48,19 +47,14 @@
     ListCustomRoutingPortMappingsByDestinationResponseTypeDef,
     ListCustomRoutingPortMappingsResponseTypeDef,
     ListEndpointGroupsResponseTypeDef,
     ListListenersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAcceleratorsPaginator",
     "ListByoipCidrsPaginator",
     "ListCustomRoutingAcceleratorsPaginator",
     "ListCustomRoutingListenersPaginator",
     "ListCustomRoutingPortMappingsPaginator",
     "ListCustomRoutingPortMappingsByDestinationPaginator",
@@ -79,57 +73,57 @@
 class ListAcceleratorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListAccelerators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listacceleratorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAcceleratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListAccelerators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listacceleratorspaginator)
         """
 
 class ListByoipCidrsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListByoipCidrs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listbyoipcidrspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListByoipCidrsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListByoipCidrs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listbyoipcidrspaginator)
         """
 
 class ListCustomRoutingAcceleratorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingAccelerators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingacceleratorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingAcceleratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingAccelerators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingacceleratorspaginator)
         """
 
 class ListCustomRoutingListenersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingListeners)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutinglistenerspaginator)
     """
 
     def paginate(
-        self, *, AcceleratorArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceleratorArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingListenersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingListeners.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutinglistenerspaginator)
         """
 
 class ListCustomRoutingPortMappingsPaginator(AioPaginator):
@@ -139,15 +133,15 @@
     """
 
     def paginate(
         self,
         *,
         AcceleratorArn: str,
         EndpointGroupArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingPortMappingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingPortMappings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingportmappingspaginator)
         """
 
 class ListCustomRoutingPortMappingsByDestinationPaginator(AioPaginator):
@@ -157,41 +151,41 @@
     """
 
     def paginate(
         self,
         *,
         EndpointId: str,
         DestinationAddress: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomRoutingPortMappingsByDestinationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListCustomRoutingPortMappingsByDestination.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listcustomroutingportmappingsbydestinationpaginator)
         """
 
 class ListEndpointGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListEndpointGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listendpointgroupspaginator)
     """
 
     def paginate(
-        self, *, ListenerArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ListenerArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListEndpointGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listendpointgroupspaginator)
         """
 
 class ListListenersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListListeners)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listlistenerspaginator)
     """
 
     def paginate(
-        self, *, AcceleratorArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AcceleratorArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListListenersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator.Paginator.ListListeners.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/paginators/#listlistenerspaginator)
         """
```

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/type_defs.py` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -37,15 +37,14 @@
 
 __all__ = (
     "AcceleratorAttributesTypeDef",
     "AcceleratorEventTypeDef",
     "IpSetTypeDef",
     "CustomRoutingEndpointConfigurationTypeDef",
     "CustomRoutingEndpointDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "EndpointConfigurationTypeDef",
     "EndpointDescriptionTypeDef",
     "AdvertiseByoipCidrRequestRequestTypeDef",
     "AllowCustomRoutingTrafficRequestRequestTypeDef",
     "ByoipCidrEventTypeDef",
     "CidrAuthorizationContextTypeDef",
     "TagTypeDef",
@@ -67,40 +66,49 @@
     "DescribeCustomRoutingAcceleratorAttributesRequestRequestTypeDef",
     "DescribeCustomRoutingAcceleratorRequestRequestTypeDef",
     "DescribeCustomRoutingEndpointGroupRequestRequestTypeDef",
     "DescribeCustomRoutingListenerRequestRequestTypeDef",
     "DescribeEndpointGroupRequestRequestTypeDef",
     "DescribeListenerRequestRequestTypeDef",
     "SocketAddressTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EndpointIdentifierTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
     "ListAcceleratorsRequestRequestTypeDef",
+    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
     "ListByoipCidrsRequestRequestTypeDef",
+    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
     "ListCustomRoutingAcceleratorsRequestRequestTypeDef",
     "ListCustomRoutingEndpointGroupsRequestRequestTypeDef",
+    "ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
     "ListCustomRoutingListenersRequestRequestTypeDef",
+    "ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
     "ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef",
+    "ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
     "ListCustomRoutingPortMappingsRequestRequestTypeDef",
+    "ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
     "ListEndpointGroupsRequestRequestTypeDef",
+    "ListListenersRequestListListenersPaginateTypeDef",
     "ListListenersRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveCustomRoutingEndpointsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAcceleratorAttributesRequestRequestTypeDef",
     "UpdateAcceleratorRequestRequestTypeDef",
     "UpdateCustomRoutingAcceleratorAttributesRequestRequestTypeDef",
     "UpdateCustomRoutingAcceleratorRequestRequestTypeDef",
     "WithdrawByoipCidrRequestRequestTypeDef",
+    "DescribeAcceleratorAttributesResponseTypeDef",
+    "UpdateAcceleratorAttributesResponseTypeDef",
     "AcceleratorTypeDef",
     "CustomRoutingAcceleratorTypeDef",
     "AddCustomRoutingEndpointsRequestRequestTypeDef",
     "AddCustomRoutingEndpointsResponseTypeDef",
-    "DescribeAcceleratorAttributesResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "UpdateAcceleratorAttributesResponseTypeDef",
     "AddEndpointsRequestRequestTypeDef",
     "AddEndpointsResponseTypeDef",
     "ByoipCidrTypeDef",
     "ProvisionByoipCidrRequestRequestTypeDef",
     "CreateAcceleratorRequestRequestTypeDef",
     "CreateCustomRoutingAcceleratorRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -117,22 +125,14 @@
     "UpdateEndpointGroupRequestRequestTypeDef",
     "DescribeCustomRoutingAcceleratorAttributesResponseTypeDef",
     "UpdateCustomRoutingAcceleratorAttributesResponseTypeDef",
     "CustomRoutingEndpointGroupTypeDef",
     "DestinationPortMappingTypeDef",
     "PortMappingTypeDef",
     "RemoveEndpointsRequestRequestTypeDef",
-    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
-    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
-    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
-    "ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
-    "ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
-    "ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
-    "ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
-    "ListListenersRequestListListenersPaginateTypeDef",
     "CreateAcceleratorResponseTypeDef",
     "DescribeAcceleratorResponseTypeDef",
     "ListAcceleratorsResponseTypeDef",
     "UpdateAcceleratorResponseTypeDef",
     "CreateCustomRoutingAcceleratorResponseTypeDef",
     "DescribeCustomRoutingAcceleratorResponseTypeDef",
     "ListCustomRoutingAcceleratorsResponseTypeDef",
@@ -202,25 +202,14 @@
     "CustomRoutingEndpointDescriptionTypeDef",
     {
         "EndpointId": str,
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
 EndpointConfigurationTypeDef = TypedDict(
     "EndpointConfigurationTypeDef",
     {
         "EndpointId": str,
         "Weight": int,
         "ClientIPPreservationEnabled": bool,
     },
@@ -478,14 +467,21 @@
     {
         "IpAddress": str,
         "Port": int,
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
 _RequiredEndpointIdentifierTypeDef = TypedDict(
     "_RequiredEndpointIdentifierTypeDef",
     {
         "EndpointId": str,
     },
 )
 _OptionalEndpointIdentifierTypeDef = TypedDict(
@@ -499,42 +495,56 @@
 
 class EndpointIdentifierTypeDef(
     _RequiredEndpointIdentifierTypeDef, _OptionalEndpointIdentifierTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAcceleratorsRequestListAcceleratorsPaginateTypeDef = TypedDict(
+    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAcceleratorsRequestRequestTypeDef = TypedDict(
     "ListAcceleratorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListByoipCidrsRequestListByoipCidrsPaginateTypeDef = TypedDict(
+    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListByoipCidrsRequestRequestTypeDef = TypedDict(
     "ListByoipCidrsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef = TypedDict(
+    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomRoutingAcceleratorsRequestRequestTypeDef = TypedDict(
     "ListCustomRoutingAcceleratorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -559,14 +569,36 @@
 class ListCustomRoutingEndpointGroupsRequestRequestTypeDef(
     _RequiredListCustomRoutingEndpointGroupsRequestRequestTypeDef,
     _OptionalListCustomRoutingEndpointGroupsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
+    "_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
+    {
+        "AcceleratorArn": str,
+    },
+)
+_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
+    "_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef(
+    _RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
+    _OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCustomRoutingListenersRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomRoutingListenersRequestRequestTypeDef",
     {
         "AcceleratorArn": str,
     },
 )
 _OptionalListCustomRoutingListenersRequestRequestTypeDef = TypedDict(
@@ -582,14 +614,37 @@
 class ListCustomRoutingListenersRequestRequestTypeDef(
     _RequiredListCustomRoutingListenersRequestRequestTypeDef,
     _OptionalListCustomRoutingListenersRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
+    "_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
+    {
+        "EndpointId": str,
+        "DestinationAddress": str,
+    },
+)
+_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
+    "_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef(
+    _RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
+    _OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef",
     {
         "EndpointId": str,
         "DestinationAddress": str,
     },
 )
@@ -606,14 +661,41 @@
 class ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef(
     _RequiredListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
     _OptionalListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
+        {
+            "AcceleratorArn": str,
+        },
+    )
+)
+_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
+        {
+            "EndpointGroupArn": str,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef(
+    _RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
+    _OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCustomRoutingPortMappingsRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomRoutingPortMappingsRequestRequestTypeDef",
     {
         "AcceleratorArn": str,
     },
 )
 _OptionalListCustomRoutingPortMappingsRequestRequestTypeDef = TypedDict(
@@ -630,14 +712,36 @@
 class ListCustomRoutingPortMappingsRequestRequestTypeDef(
     _RequiredListCustomRoutingPortMappingsRequestRequestTypeDef,
     _OptionalListCustomRoutingPortMappingsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
+    {
+        "ListenerArn": str,
+    },
+)
+_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef(
+    _RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
+    _OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEndpointGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListEndpointGroupsRequestRequestTypeDef",
     {
         "ListenerArn": str,
     },
 )
 _OptionalListEndpointGroupsRequestRequestTypeDef = TypedDict(
@@ -653,14 +757,36 @@
 class ListEndpointGroupsRequestRequestTypeDef(
     _RequiredListEndpointGroupsRequestRequestTypeDef,
     _OptionalListEndpointGroupsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListListenersRequestListListenersPaginateTypeDef = TypedDict(
+    "_RequiredListListenersRequestListListenersPaginateTypeDef",
+    {
+        "AcceleratorArn": str,
+    },
+)
+_OptionalListListenersRequestListListenersPaginateTypeDef = TypedDict(
+    "_OptionalListListenersRequestListListenersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListListenersRequestListListenersPaginateTypeDef(
+    _RequiredListListenersRequestListListenersPaginateTypeDef,
+    _OptionalListListenersRequestListListenersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListListenersRequestRequestTypeDef = TypedDict(
     "_RequiredListListenersRequestRequestTypeDef",
     {
         "AcceleratorArn": str,
     },
 )
 _OptionalListListenersRequestRequestTypeDef = TypedDict(
@@ -682,22 +808,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
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
 RemoveCustomRoutingEndpointsRequestRequestTypeDef = TypedDict(
     "RemoveCustomRoutingEndpointsRequestRequestTypeDef",
     {
         "EndpointIds": Sequence[str],
         "EndpointGroupArn": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -800,14 +947,30 @@
 WithdrawByoipCidrRequestRequestTypeDef = TypedDict(
     "WithdrawByoipCidrRequestRequestTypeDef",
     {
         "Cidr": str,
     },
 )
 
+DescribeAcceleratorAttributesResponseTypeDef = TypedDict(
+    "DescribeAcceleratorAttributesResponseTypeDef",
+    {
+        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateAcceleratorAttributesResponseTypeDef = TypedDict(
+    "UpdateAcceleratorAttributesResponseTypeDef",
+    {
+        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AcceleratorTypeDef = TypedDict(
     "AcceleratorTypeDef",
     {
         "AcceleratorArn": str,
         "Name": str,
         "IpAddressType": IpAddressTypeType,
         "Enabled": bool,
@@ -847,38 +1010,15 @@
 )
 
 AddCustomRoutingEndpointsResponseTypeDef = TypedDict(
     "AddCustomRoutingEndpointsResponseTypeDef",
     {
         "EndpointDescriptions": List[CustomRoutingEndpointDescriptionTypeDef],
         "EndpointGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAcceleratorAttributesResponseTypeDef = TypedDict(
-    "DescribeAcceleratorAttributesResponseTypeDef",
-    {
-        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
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
-UpdateAcceleratorAttributesResponseTypeDef = TypedDict(
-    "UpdateAcceleratorAttributesResponseTypeDef",
-    {
-        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddEndpointsRequestRequestTypeDef = TypedDict(
     "AddEndpointsRequestRequestTypeDef",
     {
         "EndpointConfigurations": Sequence[EndpointConfigurationTypeDef],
@@ -887,15 +1027,15 @@
 )
 
 AddEndpointsResponseTypeDef = TypedDict(
     "AddEndpointsResponseTypeDef",
     {
         "EndpointDescriptions": List[EndpointDescriptionTypeDef],
         "EndpointGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ByoipCidrTypeDef = TypedDict(
     "ByoipCidrTypeDef",
     {
         "Cidr": str,
@@ -964,15 +1104,15 @@
     pass
 
 
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
         "ResourceArn": str,
@@ -1151,23 +1291,23 @@
     pass
 
 
 DescribeCustomRoutingAcceleratorAttributesResponseTypeDef = TypedDict(
     "DescribeCustomRoutingAcceleratorAttributesResponseTypeDef",
     {
         "AcceleratorAttributes": CustomRoutingAcceleratorAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomRoutingAcceleratorAttributesResponseTypeDef = TypedDict(
     "UpdateCustomRoutingAcceleratorAttributesResponseTypeDef",
     {
         "AcceleratorAttributes": CustomRoutingAcceleratorAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomRoutingEndpointGroupTypeDef = TypedDict(
     "CustomRoutingEndpointGroupTypeDef",
     {
         "EndpointGroupArn": str,
@@ -1210,395 +1350,255 @@
     "RemoveEndpointsRequestRequestTypeDef",
     {
         "EndpointIdentifiers": Sequence[EndpointIdentifierTypeDef],
         "EndpointGroupArn": str,
     },
 )
 
-ListAcceleratorsRequestListAcceleratorsPaginateTypeDef = TypedDict(
-    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListByoipCidrsRequestListByoipCidrsPaginateTypeDef = TypedDict(
-    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef = TypedDict(
-    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
-    "_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
-    {
-        "AcceleratorArn": str,
-    },
-)
-_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
-    "_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef(
-    _RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-    _OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
-    "_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
-    {
-        "EndpointId": str,
-        "DestinationAddress": str,
-    },
-)
-_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
-    "_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef(
-    _RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-    _OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
-        {
-            "AcceleratorArn": str,
-        },
-    )
-)
-_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
-        {
-            "EndpointGroupArn": str,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef(
-    _RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-    _OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
-    {
-        "ListenerArn": str,
-    },
-)
-_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef(
-    _RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-    _OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListListenersRequestListListenersPaginateTypeDef = TypedDict(
-    "_RequiredListListenersRequestListListenersPaginateTypeDef",
-    {
-        "AcceleratorArn": str,
-    },
-)
-_OptionalListListenersRequestListListenersPaginateTypeDef = TypedDict(
-    "_OptionalListListenersRequestListListenersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListListenersRequestListListenersPaginateTypeDef(
-    _RequiredListListenersRequestListListenersPaginateTypeDef,
-    _OptionalListListenersRequestListListenersPaginateTypeDef,
-):
-    pass
-
-
 CreateAcceleratorResponseTypeDef = TypedDict(
     "CreateAcceleratorResponseTypeDef",
     {
         "Accelerator": AcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAcceleratorResponseTypeDef = TypedDict(
     "DescribeAcceleratorResponseTypeDef",
     {
         "Accelerator": AcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAcceleratorsResponseTypeDef = TypedDict(
     "ListAcceleratorsResponseTypeDef",
     {
         "Accelerators": List[AcceleratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAcceleratorResponseTypeDef = TypedDict(
     "UpdateAcceleratorResponseTypeDef",
     {
         "Accelerator": AcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCustomRoutingAcceleratorResponseTypeDef = TypedDict(
     "CreateCustomRoutingAcceleratorResponseTypeDef",
     {
         "Accelerator": CustomRoutingAcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomRoutingAcceleratorResponseTypeDef = TypedDict(
     "DescribeCustomRoutingAcceleratorResponseTypeDef",
     {
         "Accelerator": CustomRoutingAcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingAcceleratorsResponseTypeDef = TypedDict(
     "ListCustomRoutingAcceleratorsResponseTypeDef",
     {
         "Accelerators": List[CustomRoutingAcceleratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomRoutingAcceleratorResponseTypeDef = TypedDict(
     "UpdateCustomRoutingAcceleratorResponseTypeDef",
     {
         "Accelerator": CustomRoutingAcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdvertiseByoipCidrResponseTypeDef = TypedDict(
     "AdvertiseByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeprovisionByoipCidrResponseTypeDef = TypedDict(
     "DeprovisionByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListByoipCidrsResponseTypeDef = TypedDict(
     "ListByoipCidrsResponseTypeDef",
     {
         "ByoipCidrs": List[ByoipCidrTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisionByoipCidrResponseTypeDef = TypedDict(
     "ProvisionByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WithdrawByoipCidrResponseTypeDef = TypedDict(
     "WithdrawByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCustomRoutingListenerResponseTypeDef = TypedDict(
     "CreateCustomRoutingListenerResponseTypeDef",
     {
         "Listener": CustomRoutingListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomRoutingListenerResponseTypeDef = TypedDict(
     "DescribeCustomRoutingListenerResponseTypeDef",
     {
         "Listener": CustomRoutingListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingListenersResponseTypeDef = TypedDict(
     "ListCustomRoutingListenersResponseTypeDef",
     {
         "Listeners": List[CustomRoutingListenerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomRoutingListenerResponseTypeDef = TypedDict(
     "UpdateCustomRoutingListenerResponseTypeDef",
     {
         "Listener": CustomRoutingListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateListenerResponseTypeDef = TypedDict(
     "CreateListenerResponseTypeDef",
     {
         "Listener": ListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeListenerResponseTypeDef = TypedDict(
     "DescribeListenerResponseTypeDef",
     {
         "Listener": ListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListListenersResponseTypeDef = TypedDict(
     "ListListenersResponseTypeDef",
     {
         "Listeners": List[ListenerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateListenerResponseTypeDef = TypedDict(
     "UpdateListenerResponseTypeDef",
     {
         "Listener": ListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEndpointGroupResponseTypeDef = TypedDict(
     "CreateEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": EndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointGroupResponseTypeDef = TypedDict(
     "DescribeEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": EndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEndpointGroupsResponseTypeDef = TypedDict(
     "ListEndpointGroupsResponseTypeDef",
     {
         "EndpointGroups": List[EndpointGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointGroupResponseTypeDef = TypedDict(
     "UpdateEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": EndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCustomRoutingEndpointGroupResponseTypeDef = TypedDict(
     "CreateCustomRoutingEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": CustomRoutingEndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomRoutingEndpointGroupResponseTypeDef = TypedDict(
     "DescribeCustomRoutingEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": CustomRoutingEndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingEndpointGroupsResponseTypeDef = TypedDict(
     "ListCustomRoutingEndpointGroupsResponseTypeDef",
     {
         "EndpointGroups": List[CustomRoutingEndpointGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingPortMappingsByDestinationResponseTypeDef = TypedDict(
     "ListCustomRoutingPortMappingsByDestinationResponseTypeDef",
     {
         "DestinationPortMappings": List[DestinationPortMappingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingPortMappingsResponseTypeDef = TypedDict(
     "ListCustomRoutingPortMappingsResponseTypeDef",
     {
         "PortMappings": List[PortMappingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator/type_defs.pyi` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -36,15 +36,14 @@
 
 __all__ = (
     "AcceleratorAttributesTypeDef",
     "AcceleratorEventTypeDef",
     "IpSetTypeDef",
     "CustomRoutingEndpointConfigurationTypeDef",
     "CustomRoutingEndpointDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "EndpointConfigurationTypeDef",
     "EndpointDescriptionTypeDef",
     "AdvertiseByoipCidrRequestRequestTypeDef",
     "AllowCustomRoutingTrafficRequestRequestTypeDef",
     "ByoipCidrEventTypeDef",
     "CidrAuthorizationContextTypeDef",
     "TagTypeDef",
@@ -66,40 +65,49 @@
     "DescribeCustomRoutingAcceleratorAttributesRequestRequestTypeDef",
     "DescribeCustomRoutingAcceleratorRequestRequestTypeDef",
     "DescribeCustomRoutingEndpointGroupRequestRequestTypeDef",
     "DescribeCustomRoutingListenerRequestRequestTypeDef",
     "DescribeEndpointGroupRequestRequestTypeDef",
     "DescribeListenerRequestRequestTypeDef",
     "SocketAddressTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EndpointIdentifierTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
     "ListAcceleratorsRequestRequestTypeDef",
+    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
     "ListByoipCidrsRequestRequestTypeDef",
+    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
     "ListCustomRoutingAcceleratorsRequestRequestTypeDef",
     "ListCustomRoutingEndpointGroupsRequestRequestTypeDef",
+    "ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
     "ListCustomRoutingListenersRequestRequestTypeDef",
+    "ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
     "ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef",
+    "ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
     "ListCustomRoutingPortMappingsRequestRequestTypeDef",
+    "ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
     "ListEndpointGroupsRequestRequestTypeDef",
+    "ListListenersRequestListListenersPaginateTypeDef",
     "ListListenersRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveCustomRoutingEndpointsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAcceleratorAttributesRequestRequestTypeDef",
     "UpdateAcceleratorRequestRequestTypeDef",
     "UpdateCustomRoutingAcceleratorAttributesRequestRequestTypeDef",
     "UpdateCustomRoutingAcceleratorRequestRequestTypeDef",
     "WithdrawByoipCidrRequestRequestTypeDef",
+    "DescribeAcceleratorAttributesResponseTypeDef",
+    "UpdateAcceleratorAttributesResponseTypeDef",
     "AcceleratorTypeDef",
     "CustomRoutingAcceleratorTypeDef",
     "AddCustomRoutingEndpointsRequestRequestTypeDef",
     "AddCustomRoutingEndpointsResponseTypeDef",
-    "DescribeAcceleratorAttributesResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "UpdateAcceleratorAttributesResponseTypeDef",
     "AddEndpointsRequestRequestTypeDef",
     "AddEndpointsResponseTypeDef",
     "ByoipCidrTypeDef",
     "ProvisionByoipCidrRequestRequestTypeDef",
     "CreateAcceleratorRequestRequestTypeDef",
     "CreateCustomRoutingAcceleratorRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -116,22 +124,14 @@
     "UpdateEndpointGroupRequestRequestTypeDef",
     "DescribeCustomRoutingAcceleratorAttributesResponseTypeDef",
     "UpdateCustomRoutingAcceleratorAttributesResponseTypeDef",
     "CustomRoutingEndpointGroupTypeDef",
     "DestinationPortMappingTypeDef",
     "PortMappingTypeDef",
     "RemoveEndpointsRequestRequestTypeDef",
-    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
-    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
-    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
-    "ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
-    "ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
-    "ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
-    "ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
-    "ListListenersRequestListListenersPaginateTypeDef",
     "CreateAcceleratorResponseTypeDef",
     "DescribeAcceleratorResponseTypeDef",
     "ListAcceleratorsResponseTypeDef",
     "UpdateAcceleratorResponseTypeDef",
     "CreateCustomRoutingAcceleratorResponseTypeDef",
     "DescribeCustomRoutingAcceleratorResponseTypeDef",
     "ListCustomRoutingAcceleratorsResponseTypeDef",
@@ -201,25 +201,14 @@
     "CustomRoutingEndpointDescriptionTypeDef",
     {
         "EndpointId": str,
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
 EndpointConfigurationTypeDef = TypedDict(
     "EndpointConfigurationTypeDef",
     {
         "EndpointId": str,
         "Weight": int,
         "ClientIPPreservationEnabled": bool,
     },
@@ -473,14 +462,21 @@
     {
         "IpAddress": str,
         "Port": int,
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
 _RequiredEndpointIdentifierTypeDef = TypedDict(
     "_RequiredEndpointIdentifierTypeDef",
     {
         "EndpointId": str,
     },
 )
 _OptionalEndpointIdentifierTypeDef = TypedDict(
@@ -492,42 +488,56 @@
 )
 
 class EndpointIdentifierTypeDef(
     _RequiredEndpointIdentifierTypeDef, _OptionalEndpointIdentifierTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAcceleratorsRequestListAcceleratorsPaginateTypeDef = TypedDict(
+    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAcceleratorsRequestRequestTypeDef = TypedDict(
     "ListAcceleratorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListByoipCidrsRequestListByoipCidrsPaginateTypeDef = TypedDict(
+    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListByoipCidrsRequestRequestTypeDef = TypedDict(
     "ListByoipCidrsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef = TypedDict(
+    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomRoutingAcceleratorsRequestRequestTypeDef = TypedDict(
     "ListCustomRoutingAcceleratorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -550,14 +560,34 @@
 
 class ListCustomRoutingEndpointGroupsRequestRequestTypeDef(
     _RequiredListCustomRoutingEndpointGroupsRequestRequestTypeDef,
     _OptionalListCustomRoutingEndpointGroupsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
+    "_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
+    {
+        "AcceleratorArn": str,
+    },
+)
+_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
+    "_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef(
+    _RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
+    _OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
+):
+    pass
+
 _RequiredListCustomRoutingListenersRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomRoutingListenersRequestRequestTypeDef",
     {
         "AcceleratorArn": str,
     },
 )
 _OptionalListCustomRoutingListenersRequestRequestTypeDef = TypedDict(
@@ -571,14 +601,35 @@
 
 class ListCustomRoutingListenersRequestRequestTypeDef(
     _RequiredListCustomRoutingListenersRequestRequestTypeDef,
     _OptionalListCustomRoutingListenersRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
+    "_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
+    {
+        "EndpointId": str,
+        "DestinationAddress": str,
+    },
+)
+_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
+    "_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef(
+    _RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
+    _OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
+):
+    pass
+
 _RequiredListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef",
     {
         "EndpointId": str,
         "DestinationAddress": str,
     },
 )
@@ -593,14 +644,39 @@
 
 class ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef(
     _RequiredListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
     _OptionalListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
+        {
+            "AcceleratorArn": str,
+        },
+    )
+)
+_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
+        {
+            "EndpointGroupArn": str,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef(
+    _RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
+    _OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
+):
+    pass
+
 _RequiredListCustomRoutingPortMappingsRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomRoutingPortMappingsRequestRequestTypeDef",
     {
         "AcceleratorArn": str,
     },
 )
 _OptionalListCustomRoutingPortMappingsRequestRequestTypeDef = TypedDict(
@@ -615,14 +691,34 @@
 
 class ListCustomRoutingPortMappingsRequestRequestTypeDef(
     _RequiredListCustomRoutingPortMappingsRequestRequestTypeDef,
     _OptionalListCustomRoutingPortMappingsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
+    {
+        "ListenerArn": str,
+    },
+)
+_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef(
+    _RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
+    _OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEndpointGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListEndpointGroupsRequestRequestTypeDef",
     {
         "ListenerArn": str,
     },
 )
 _OptionalListEndpointGroupsRequestRequestTypeDef = TypedDict(
@@ -636,14 +732,34 @@
 
 class ListEndpointGroupsRequestRequestTypeDef(
     _RequiredListEndpointGroupsRequestRequestTypeDef,
     _OptionalListEndpointGroupsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListListenersRequestListListenersPaginateTypeDef = TypedDict(
+    "_RequiredListListenersRequestListListenersPaginateTypeDef",
+    {
+        "AcceleratorArn": str,
+    },
+)
+_OptionalListListenersRequestListListenersPaginateTypeDef = TypedDict(
+    "_OptionalListListenersRequestListListenersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListListenersRequestListListenersPaginateTypeDef(
+    _RequiredListListenersRequestListListenersPaginateTypeDef,
+    _OptionalListListenersRequestListListenersPaginateTypeDef,
+):
+    pass
+
 _RequiredListListenersRequestRequestTypeDef = TypedDict(
     "_RequiredListListenersRequestRequestTypeDef",
     {
         "AcceleratorArn": str,
     },
 )
 _OptionalListListenersRequestRequestTypeDef = TypedDict(
@@ -663,22 +779,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
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
 RemoveCustomRoutingEndpointsRequestRequestTypeDef = TypedDict(
     "RemoveCustomRoutingEndpointsRequestRequestTypeDef",
     {
         "EndpointIds": Sequence[str],
         "EndpointGroupArn": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -773,14 +910,30 @@
 WithdrawByoipCidrRequestRequestTypeDef = TypedDict(
     "WithdrawByoipCidrRequestRequestTypeDef",
     {
         "Cidr": str,
     },
 )
 
+DescribeAcceleratorAttributesResponseTypeDef = TypedDict(
+    "DescribeAcceleratorAttributesResponseTypeDef",
+    {
+        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateAcceleratorAttributesResponseTypeDef = TypedDict(
+    "UpdateAcceleratorAttributesResponseTypeDef",
+    {
+        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AcceleratorTypeDef = TypedDict(
     "AcceleratorTypeDef",
     {
         "AcceleratorArn": str,
         "Name": str,
         "IpAddressType": IpAddressTypeType,
         "Enabled": bool,
@@ -820,38 +973,15 @@
 )
 
 AddCustomRoutingEndpointsResponseTypeDef = TypedDict(
     "AddCustomRoutingEndpointsResponseTypeDef",
     {
         "EndpointDescriptions": List[CustomRoutingEndpointDescriptionTypeDef],
         "EndpointGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAcceleratorAttributesResponseTypeDef = TypedDict(
-    "DescribeAcceleratorAttributesResponseTypeDef",
-    {
-        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
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
-UpdateAcceleratorAttributesResponseTypeDef = TypedDict(
-    "UpdateAcceleratorAttributesResponseTypeDef",
-    {
-        "AcceleratorAttributes": AcceleratorAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddEndpointsRequestRequestTypeDef = TypedDict(
     "AddEndpointsRequestRequestTypeDef",
     {
         "EndpointConfigurations": Sequence[EndpointConfigurationTypeDef],
@@ -860,15 +990,15 @@
 )
 
 AddEndpointsResponseTypeDef = TypedDict(
     "AddEndpointsResponseTypeDef",
     {
         "EndpointDescriptions": List[EndpointDescriptionTypeDef],
         "EndpointGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ByoipCidrTypeDef = TypedDict(
     "ByoipCidrTypeDef",
     {
         "Cidr": str,
@@ -933,15 +1063,15 @@
 ):
     pass
 
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
         "ResourceArn": str,
@@ -1112,23 +1242,23 @@
 ):
     pass
 
 DescribeCustomRoutingAcceleratorAttributesResponseTypeDef = TypedDict(
     "DescribeCustomRoutingAcceleratorAttributesResponseTypeDef",
     {
         "AcceleratorAttributes": CustomRoutingAcceleratorAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomRoutingAcceleratorAttributesResponseTypeDef = TypedDict(
     "UpdateCustomRoutingAcceleratorAttributesResponseTypeDef",
     {
         "AcceleratorAttributes": CustomRoutingAcceleratorAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomRoutingEndpointGroupTypeDef = TypedDict(
     "CustomRoutingEndpointGroupTypeDef",
     {
         "EndpointGroupArn": str,
@@ -1171,385 +1301,255 @@
     "RemoveEndpointsRequestRequestTypeDef",
     {
         "EndpointIdentifiers": Sequence[EndpointIdentifierTypeDef],
         "EndpointGroupArn": str,
     },
 )
 
-ListAcceleratorsRequestListAcceleratorsPaginateTypeDef = TypedDict(
-    "ListAcceleratorsRequestListAcceleratorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListByoipCidrsRequestListByoipCidrsPaginateTypeDef = TypedDict(
-    "ListByoipCidrsRequestListByoipCidrsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef = TypedDict(
-    "ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
-    "_RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
-    {
-        "AcceleratorArn": str,
-    },
-)
-_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef = TypedDict(
-    "_OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef(
-    _RequiredListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-    _OptionalListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-):
-    pass
-
-_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
-    "_RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
-    {
-        "EndpointId": str,
-        "DestinationAddress": str,
-    },
-)
-_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef = TypedDict(
-    "_OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef(
-    _RequiredListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-    _OptionalListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-):
-    pass
-
-_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
-        {
-            "AcceleratorArn": str,
-        },
-    )
-)
-_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef",
-        {
-            "EndpointGroupArn": str,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef(
-    _RequiredListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-    _OptionalListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-):
-    pass
-
-_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
-    {
-        "ListenerArn": str,
-    },
-)
-_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef(
-    _RequiredListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-    _OptionalListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListListenersRequestListListenersPaginateTypeDef = TypedDict(
-    "_RequiredListListenersRequestListListenersPaginateTypeDef",
-    {
-        "AcceleratorArn": str,
-    },
-)
-_OptionalListListenersRequestListListenersPaginateTypeDef = TypedDict(
-    "_OptionalListListenersRequestListListenersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListListenersRequestListListenersPaginateTypeDef(
-    _RequiredListListenersRequestListListenersPaginateTypeDef,
-    _OptionalListListenersRequestListListenersPaginateTypeDef,
-):
-    pass
-
 CreateAcceleratorResponseTypeDef = TypedDict(
     "CreateAcceleratorResponseTypeDef",
     {
         "Accelerator": AcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAcceleratorResponseTypeDef = TypedDict(
     "DescribeAcceleratorResponseTypeDef",
     {
         "Accelerator": AcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAcceleratorsResponseTypeDef = TypedDict(
     "ListAcceleratorsResponseTypeDef",
     {
         "Accelerators": List[AcceleratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAcceleratorResponseTypeDef = TypedDict(
     "UpdateAcceleratorResponseTypeDef",
     {
         "Accelerator": AcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCustomRoutingAcceleratorResponseTypeDef = TypedDict(
     "CreateCustomRoutingAcceleratorResponseTypeDef",
     {
         "Accelerator": CustomRoutingAcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomRoutingAcceleratorResponseTypeDef = TypedDict(
     "DescribeCustomRoutingAcceleratorResponseTypeDef",
     {
         "Accelerator": CustomRoutingAcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingAcceleratorsResponseTypeDef = TypedDict(
     "ListCustomRoutingAcceleratorsResponseTypeDef",
     {
         "Accelerators": List[CustomRoutingAcceleratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomRoutingAcceleratorResponseTypeDef = TypedDict(
     "UpdateCustomRoutingAcceleratorResponseTypeDef",
     {
         "Accelerator": CustomRoutingAcceleratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdvertiseByoipCidrResponseTypeDef = TypedDict(
     "AdvertiseByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeprovisionByoipCidrResponseTypeDef = TypedDict(
     "DeprovisionByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListByoipCidrsResponseTypeDef = TypedDict(
     "ListByoipCidrsResponseTypeDef",
     {
         "ByoipCidrs": List[ByoipCidrTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProvisionByoipCidrResponseTypeDef = TypedDict(
     "ProvisionByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WithdrawByoipCidrResponseTypeDef = TypedDict(
     "WithdrawByoipCidrResponseTypeDef",
     {
         "ByoipCidr": ByoipCidrTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCustomRoutingListenerResponseTypeDef = TypedDict(
     "CreateCustomRoutingListenerResponseTypeDef",
     {
         "Listener": CustomRoutingListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomRoutingListenerResponseTypeDef = TypedDict(
     "DescribeCustomRoutingListenerResponseTypeDef",
     {
         "Listener": CustomRoutingListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingListenersResponseTypeDef = TypedDict(
     "ListCustomRoutingListenersResponseTypeDef",
     {
         "Listeners": List[CustomRoutingListenerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCustomRoutingListenerResponseTypeDef = TypedDict(
     "UpdateCustomRoutingListenerResponseTypeDef",
     {
         "Listener": CustomRoutingListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateListenerResponseTypeDef = TypedDict(
     "CreateListenerResponseTypeDef",
     {
         "Listener": ListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeListenerResponseTypeDef = TypedDict(
     "DescribeListenerResponseTypeDef",
     {
         "Listener": ListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListListenersResponseTypeDef = TypedDict(
     "ListListenersResponseTypeDef",
     {
         "Listeners": List[ListenerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateListenerResponseTypeDef = TypedDict(
     "UpdateListenerResponseTypeDef",
     {
         "Listener": ListenerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEndpointGroupResponseTypeDef = TypedDict(
     "CreateEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": EndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointGroupResponseTypeDef = TypedDict(
     "DescribeEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": EndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEndpointGroupsResponseTypeDef = TypedDict(
     "ListEndpointGroupsResponseTypeDef",
     {
         "EndpointGroups": List[EndpointGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointGroupResponseTypeDef = TypedDict(
     "UpdateEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": EndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCustomRoutingEndpointGroupResponseTypeDef = TypedDict(
     "CreateCustomRoutingEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": CustomRoutingEndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomRoutingEndpointGroupResponseTypeDef = TypedDict(
     "DescribeCustomRoutingEndpointGroupResponseTypeDef",
     {
         "EndpointGroup": CustomRoutingEndpointGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingEndpointGroupsResponseTypeDef = TypedDict(
     "ListCustomRoutingEndpointGroupsResponseTypeDef",
     {
         "EndpointGroups": List[CustomRoutingEndpointGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingPortMappingsByDestinationResponseTypeDef = TypedDict(
     "ListCustomRoutingPortMappingsByDestinationResponseTypeDef",
     {
         "DestinationPortMappings": List[DestinationPortMappingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomRoutingPortMappingsResponseTypeDef = TypedDict(
     "ListCustomRoutingPortMappingsResponseTypeDef",
     {
         "PortMappings": List[PortMappingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/PKG-INFO` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-globalaccelerator
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GlobalAccelerator 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GlobalAccelerator 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-globalaccelerator"></a>
 
 # types-aiobotocore-globalaccelerator
 
 [![PyPI - types-aiobotocore-globalaccelerator](https://img.shields.io/pypi/v/types-aiobotocore-globalaccelerator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-globalaccelerator)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-globalaccelerator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-globalaccelerator)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-globalaccelerator?color=blue)](https://pypistats.org/packages/types-aiobotocore-globalaccelerator)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GlobalAccelerator 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator)
+[aiobotocore.GlobalAccelerator 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/globalaccelerator.html#GlobalAccelerator)
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
 [types-aiobotocore-globalaccelerator docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_globalaccelerator/).
 
 See how it helps to find and fix potential bugs:
 
@@ -364,15 +364,14 @@
 ```python
 from types_aiobotocore_globalaccelerator.type_defs import (
     AcceleratorAttributesTypeDef,
     AcceleratorEventTypeDef,
     IpSetTypeDef,
     CustomRoutingEndpointConfigurationTypeDef,
     CustomRoutingEndpointDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     EndpointConfigurationTypeDef,
     EndpointDescriptionTypeDef,
     AdvertiseByoipCidrRequestRequestTypeDef,
     AllowCustomRoutingTrafficRequestRequestTypeDef,
     ByoipCidrEventTypeDef,
     CidrAuthorizationContextTypeDef,
     TagTypeDef,
@@ -394,40 +393,49 @@
     DescribeCustomRoutingAcceleratorAttributesRequestRequestTypeDef,
     DescribeCustomRoutingAcceleratorRequestRequestTypeDef,
     DescribeCustomRoutingEndpointGroupRequestRequestTypeDef,
     DescribeCustomRoutingListenerRequestRequestTypeDef,
     DescribeEndpointGroupRequestRequestTypeDef,
     DescribeListenerRequestRequestTypeDef,
     SocketAddressTypeDef,
+    EmptyResponseMetadataTypeDef,
     EndpointIdentifierTypeDef,
-    PaginatorConfigTypeDef,
+    ListAcceleratorsRequestListAcceleratorsPaginateTypeDef,
     ListAcceleratorsRequestRequestTypeDef,
+    ListByoipCidrsRequestListByoipCidrsPaginateTypeDef,
     ListByoipCidrsRequestRequestTypeDef,
+    ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef,
     ListCustomRoutingAcceleratorsRequestRequestTypeDef,
     ListCustomRoutingEndpointGroupsRequestRequestTypeDef,
+    ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
     ListCustomRoutingListenersRequestRequestTypeDef,
+    ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
     ListCustomRoutingPortMappingsByDestinationRequestRequestTypeDef,
+    ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
     ListCustomRoutingPortMappingsRequestRequestTypeDef,
+    ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
     ListEndpointGroupsRequestRequestTypeDef,
+    ListListenersRequestListListenersPaginateTypeDef,
     ListListenersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     RemoveCustomRoutingEndpointsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAcceleratorAttributesRequestRequestTypeDef,
     UpdateAcceleratorRequestRequestTypeDef,
     UpdateCustomRoutingAcceleratorAttributesRequestRequestTypeDef,
     UpdateCustomRoutingAcceleratorRequestRequestTypeDef,
     WithdrawByoipCidrRequestRequestTypeDef,
+    DescribeAcceleratorAttributesResponseTypeDef,
+    UpdateAcceleratorAttributesResponseTypeDef,
     AcceleratorTypeDef,
     CustomRoutingAcceleratorTypeDef,
     AddCustomRoutingEndpointsRequestRequestTypeDef,
     AddCustomRoutingEndpointsResponseTypeDef,
-    DescribeAcceleratorAttributesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    UpdateAcceleratorAttributesResponseTypeDef,
     AddEndpointsRequestRequestTypeDef,
     AddEndpointsResponseTypeDef,
     ByoipCidrTypeDef,
     ProvisionByoipCidrRequestRequestTypeDef,
     CreateAcceleratorRequestRequestTypeDef,
     CreateCustomRoutingAcceleratorRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -444,22 +452,14 @@
     UpdateEndpointGroupRequestRequestTypeDef,
     DescribeCustomRoutingAcceleratorAttributesResponseTypeDef,
     UpdateCustomRoutingAcceleratorAttributesResponseTypeDef,
     CustomRoutingEndpointGroupTypeDef,
     DestinationPortMappingTypeDef,
     PortMappingTypeDef,
     RemoveEndpointsRequestRequestTypeDef,
-    ListAcceleratorsRequestListAcceleratorsPaginateTypeDef,
-    ListByoipCidrsRequestListByoipCidrsPaginateTypeDef,
-    ListCustomRoutingAcceleratorsRequestListCustomRoutingAcceleratorsPaginateTypeDef,
-    ListCustomRoutingListenersRequestListCustomRoutingListenersPaginateTypeDef,
-    ListCustomRoutingPortMappingsByDestinationRequestListCustomRoutingPortMappingsByDestinationPaginateTypeDef,
-    ListCustomRoutingPortMappingsRequestListCustomRoutingPortMappingsPaginateTypeDef,
-    ListEndpointGroupsRequestListEndpointGroupsPaginateTypeDef,
-    ListListenersRequestListListenersPaginateTypeDef,
     CreateAcceleratorResponseTypeDef,
     DescribeAcceleratorResponseTypeDef,
     ListAcceleratorsResponseTypeDef,
     UpdateAcceleratorResponseTypeDef,
     CreateCustomRoutingAcceleratorResponseTypeDef,
     DescribeCustomRoutingAcceleratorResponseTypeDef,
     ListCustomRoutingAcceleratorsResponseTypeDef,
@@ -496,43 +496,43 @@
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

### Comparing `types-aiobotocore-globalaccelerator-2.5.0.post1/types_aiobotocore_globalaccelerator.egg-info/SOURCES.txt` & `types-aiobotocore-globalaccelerator-2.5.1/types_aiobotocore_globalaccelerator.egg-info/SOURCES.txt`

 * *Files identical despite different names*

