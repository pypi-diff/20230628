# Comparing `tmp/types-aiobotocore-servicediscovery-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-servicediscovery-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-servicediscovery-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-servicediscovery-2.5.1.tar", last modified: Wed Jun 28 01:44:11 2023, max compression
```

## Comparing `types-aiobotocore-servicediscovery-2.5.0.post1.tar` & `types-aiobotocore-servicediscovery-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.727631 types-aiobotocore-servicediscovery-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17498 2023-03-11 12:27:20.727631 types-aiobotocore-servicediscovery-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15891 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:20.727631 types-aiobotocore-servicediscovery-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.719631 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/
--rw-r--r--   0 runner    (1001) docker     (123)     1295 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1294 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24551 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24512 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9941 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9939 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5860 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5853 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    28438 2023-03-11 12:24:06.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    28402 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:05.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.727631 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17498 2023-03-11 12:27:20.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:27:20.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:27:20.000000 types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.094215 types-aiobotocore-servicediscovery-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17499 2023-06-28 01:44:11.094215 types-aiobotocore-servicediscovery-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15898 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:11.094215 types-aiobotocore-servicediscovery-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.094215 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/
+-rw-r--r--   0 runner    (1001) docker     (123)     1295 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1294 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24549 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24510 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10172 2023-06-28 01:40:54.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10170 2023-06-28 01:40:54.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5748 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5742 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    28492 2023-06-28 01:40:54.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28456 2023-06-28 01:40:54.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:53.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.094215 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17499 2023-06-28 01:44:10.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:44:10.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:10.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:10.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:10.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:44:10.000000 types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/LICENSE` & `types-aiobotocore-servicediscovery-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/PKG-INFO` & `types-aiobotocore-servicediscovery-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-servicediscovery
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServiceDiscovery 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServiceDiscovery 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-servicediscovery"></a>
 
 # types-aiobotocore-servicediscovery
 
 [![PyPI - types-aiobotocore-servicediscovery](https://img.shields.io/pypi/v/types-aiobotocore-servicediscovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicediscovery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicediscovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicediscovery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicediscovery?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicediscovery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceDiscovery 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
+[aiobotocore.ServiceDiscovery 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
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
 [types-aiobotocore-servicediscovery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -342,71 +342,71 @@
 
 `types_aiobotocore_servicediscovery.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_servicediscovery.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateHttpNamespaceResponseTypeDef,
+    CreatePrivateDnsNamespaceResponseTypeDef,
+    CreatePublicDnsNamespaceResponseTypeDef,
     HealthCheckConfigTypeDef,
     HealthCheckCustomConfigTypeDef,
     DeleteNamespaceRequestRequestTypeDef,
+    DeleteNamespaceResponseTypeDef,
     DeleteServiceRequestRequestTypeDef,
     DeregisterInstanceRequestRequestTypeDef,
+    DeregisterInstanceResponseTypeDef,
     DiscoverInstancesRequestRequestTypeDef,
     HttpInstanceSummaryTypeDef,
     DnsRecordTypeDef,
     SOATypeDef,
+    EmptyResponseMetadataTypeDef,
     GetInstanceRequestRequestTypeDef,
     InstanceTypeDef,
     GetInstancesHealthStatusRequestRequestTypeDef,
+    GetInstancesHealthStatusResponseTypeDef,
     GetNamespaceRequestRequestTypeDef,
     GetOperationRequestRequestTypeDef,
     OperationTypeDef,
     GetServiceRequestRequestTypeDef,
     HttpNamespaceChangeTypeDef,
     HttpPropertiesTypeDef,
     InstanceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
     NamespaceFilterTypeDef,
     OperationFilterTypeDef,
     OperationSummaryTypeDef,
     ServiceFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     SOAChangeTypeDef,
     RegisterInstanceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    UpdateInstanceCustomHealthStatusRequestRequestTypeDef,
-    CreateHttpNamespaceRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateHttpNamespaceResponseTypeDef,
-    CreatePrivateDnsNamespaceResponseTypeDef,
-    CreatePublicDnsNamespaceResponseTypeDef,
-    DeleteNamespaceResponseTypeDef,
-    DeregisterInstanceResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetInstancesHealthStatusResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     RegisterInstanceResponseTypeDef,
+    ResponseMetadataTypeDef,
+    UntagResourceRequestRequestTypeDef,
     UpdateHttpNamespaceResponseTypeDef,
+    UpdateInstanceCustomHealthStatusRequestRequestTypeDef,
     UpdatePrivateDnsNamespaceResponseTypeDef,
     UpdatePublicDnsNamespaceResponseTypeDef,
     UpdateServiceResponseTypeDef,
+    CreateHttpNamespaceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     DiscoverInstancesResponseTypeDef,
     DnsConfigChangeTypeDef,
     DnsConfigTypeDef,
     DnsPropertiesTypeDef,
     PrivateDnsPropertiesMutableTypeDef,
     PublicDnsPropertiesMutableTypeDef,
     GetInstanceResponseTypeDef,
     GetOperationResponseTypeDef,
     UpdateHttpNamespaceRequestRequestTypeDef,
     ListInstancesResponseTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
     ListNamespacesRequestListNamespacesPaginateTypeDef,
     ListNamespacesRequestRequestTypeDef,
     ListOperationsRequestListOperationsPaginateTypeDef,
     ListOperationsRequestRequestTypeDef,
     ListOperationsResponseTypeDef,
     ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/README.md` & `types-aiobotocore-servicediscovery-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-servicediscovery"></a>
 
 # types-aiobotocore-servicediscovery
 
 [![PyPI - types-aiobotocore-servicediscovery](https://img.shields.io/pypi/v/types-aiobotocore-servicediscovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicediscovery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicediscovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicediscovery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicediscovery?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicediscovery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceDiscovery 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
+[aiobotocore.ServiceDiscovery 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
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
 [types-aiobotocore-servicediscovery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -309,71 +309,71 @@
 
 `types_aiobotocore_servicediscovery.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_servicediscovery.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateHttpNamespaceResponseTypeDef,
+    CreatePrivateDnsNamespaceResponseTypeDef,
+    CreatePublicDnsNamespaceResponseTypeDef,
     HealthCheckConfigTypeDef,
     HealthCheckCustomConfigTypeDef,
     DeleteNamespaceRequestRequestTypeDef,
+    DeleteNamespaceResponseTypeDef,
     DeleteServiceRequestRequestTypeDef,
     DeregisterInstanceRequestRequestTypeDef,
+    DeregisterInstanceResponseTypeDef,
     DiscoverInstancesRequestRequestTypeDef,
     HttpInstanceSummaryTypeDef,
     DnsRecordTypeDef,
     SOATypeDef,
+    EmptyResponseMetadataTypeDef,
     GetInstanceRequestRequestTypeDef,
     InstanceTypeDef,
     GetInstancesHealthStatusRequestRequestTypeDef,
+    GetInstancesHealthStatusResponseTypeDef,
     GetNamespaceRequestRequestTypeDef,
     GetOperationRequestRequestTypeDef,
     OperationTypeDef,
     GetServiceRequestRequestTypeDef,
     HttpNamespaceChangeTypeDef,
     HttpPropertiesTypeDef,
     InstanceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
     NamespaceFilterTypeDef,
     OperationFilterTypeDef,
     OperationSummaryTypeDef,
     ServiceFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     SOAChangeTypeDef,
     RegisterInstanceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    UpdateInstanceCustomHealthStatusRequestRequestTypeDef,
-    CreateHttpNamespaceRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateHttpNamespaceResponseTypeDef,
-    CreatePrivateDnsNamespaceResponseTypeDef,
-    CreatePublicDnsNamespaceResponseTypeDef,
-    DeleteNamespaceResponseTypeDef,
-    DeregisterInstanceResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetInstancesHealthStatusResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     RegisterInstanceResponseTypeDef,
+    ResponseMetadataTypeDef,
+    UntagResourceRequestRequestTypeDef,
     UpdateHttpNamespaceResponseTypeDef,
+    UpdateInstanceCustomHealthStatusRequestRequestTypeDef,
     UpdatePrivateDnsNamespaceResponseTypeDef,
     UpdatePublicDnsNamespaceResponseTypeDef,
     UpdateServiceResponseTypeDef,
+    CreateHttpNamespaceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     DiscoverInstancesResponseTypeDef,
     DnsConfigChangeTypeDef,
     DnsConfigTypeDef,
     DnsPropertiesTypeDef,
     PrivateDnsPropertiesMutableTypeDef,
     PublicDnsPropertiesMutableTypeDef,
     GetInstanceResponseTypeDef,
     GetOperationResponseTypeDef,
     UpdateHttpNamespaceRequestRequestTypeDef,
     ListInstancesResponseTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
     ListNamespacesRequestListNamespacesPaginateTypeDef,
     ListNamespacesRequestRequestTypeDef,
     ListOperationsRequestListOperationsPaginateTypeDef,
     ListOperationsRequestRequestTypeDef,
     ListOperationsResponseTypeDef,
     ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
@@ -412,43 +412,43 @@
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

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/setup.py` & `types-aiobotocore-servicediscovery-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-servicediscovery.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-servicediscovery",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_servicediscovery"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ServiceDiscovery 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ServiceDiscovery 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/"
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

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/__init__.py` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/__init__.pyi` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/__main__.py` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ServiceDiscovery 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ServiceDiscovery 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery\nOther"
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

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/client.py` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -274,16 +274,16 @@
         *,
         ServiceId: str,
         Instances: Sequence[str] = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> GetInstancesHealthStatusResponseTypeDef:
         """
-        Gets the current health status ( `Healthy` , `Unhealthy` , or `Unknown` ) of one
-        or more instances that are associated with a specified service.
+        Gets the current health status ( `Healthy`, `Unhealthy`, or `Unknown`) of one or
+        more instances that are associated with a specified service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_instances_health_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/client/#get_instances_health_status)
         """
 
     async def get_namespace(self, *, Id: str) -> GetNamespaceResponseTypeDef:
         """
@@ -448,15 +448,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/client/#update_public_dns_namespace)
         """
 
     async def update_service(
         self, *, Id: str, Service: ServiceChangeTypeDef
     ) -> UpdateServiceResponseTypeDef:
         """
-        Submits a request to perform the following operations * Update the TTL setting
+        Submits a request to perform the following operations: * Update the TTL setting
         for existing `DnsRecords` configurations * Add, update, or delete
         `HealthCheckConfig` for a specified service .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/client/#update_service)
         """
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/client.pyi` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -257,16 +257,16 @@
         *,
         ServiceId: str,
         Instances: Sequence[str] = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> GetInstancesHealthStatusResponseTypeDef:
         """
-        Gets the current health status ( `Healthy` , `Unhealthy` , or `Unknown` ) of one
-        or more instances that are associated with a specified service.
+        Gets the current health status ( `Healthy`, `Unhealthy`, or `Unknown`) of one or
+        more instances that are associated with a specified service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.get_instances_health_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/client/#get_instances_health_status)
         """
     async def get_namespace(self, *, Id: str) -> GetNamespaceResponseTypeDef:
         """
         Gets information about a namespace.
@@ -415,15 +415,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_public_dns_namespace)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/client/#update_public_dns_namespace)
         """
     async def update_service(
         self, *, Id: str, Service: ServiceChangeTypeDef
     ) -> UpdateServiceResponseTypeDef:
         """
-        Submits a request to perform the following operations * Update the TTL setting
+        Submits a request to perform the following operations: * Update the TTL setting
         for existing `DnsRecords` configurations * Add, update, or delete
         `HealthCheckConfig` for a specified service .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Client.update_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/client/#update_service)
         """
     @overload
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/literals.py` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -134,14 +134,15 @@
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
@@ -220,14 +221,15 @@
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
@@ -238,14 +240,15 @@
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
@@ -281,14 +284,15 @@
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
@@ -307,16 +311,19 @@
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
@@ -400,15 +407,17 @@
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
@@ -438,14 +447,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/literals.pyi` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -132,14 +132,15 @@
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
@@ -218,14 +219,15 @@
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
@@ -236,14 +238,15 @@
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
@@ -279,14 +282,15 @@
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
@@ -305,16 +309,19 @@
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
@@ -398,15 +405,17 @@
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
@@ -436,14 +445,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/paginator.py` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,16 +22,15 @@
 
         list_instances_paginator: ListInstancesPaginator = client.get_paginator("list_instances")
         list_namespaces_paginator: ListNamespacesPaginator = client.get_paginator("list_namespaces")
         list_operations_paginator: ListOperationsPaginator = client.get_paginator("list_operations")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListInstancesResponseTypeDef,
     ListNamespacesResponseTypeDef,
@@ -39,20 +38,14 @@
     ListServicesResponseTypeDef,
     NamespaceFilterTypeDef,
     OperationFilterTypeDef,
     PaginatorConfigTypeDef,
     ServiceFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListInstancesPaginator",
     "ListNamespacesPaginator",
     "ListOperationsPaginator",
     "ListServicesPaginator",
 )
 
@@ -70,15 +63,15 @@
 class ListInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listinstancespaginator)
     """
 
     def paginate(
-        self, *, ServiceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServiceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listinstancespaginator)
         """
 
 
@@ -88,15 +81,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listnamespacespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[NamespaceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNamespacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListNamespaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listnamespacespaginator)
         """
 
 
@@ -106,15 +99,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listoperationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[OperationFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOperationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listoperationspaginator)
         """
 
 
@@ -124,13 +117,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listservicespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ServiceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listservicespaginator)
         """
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/paginator.pyi` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/paginator.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -22,16 +22,15 @@
 
         list_instances_paginator: ListInstancesPaginator = client.get_paginator("list_instances")
         list_namespaces_paginator: ListNamespacesPaginator = client.get_paginator("list_namespaces")
         list_operations_paginator: ListOperationsPaginator = client.get_paginator("list_operations")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListInstancesResponseTypeDef,
     ListNamespacesResponseTypeDef,
@@ -39,19 +38,14 @@
     ListServicesResponseTypeDef,
     NamespaceFilterTypeDef,
     OperationFilterTypeDef,
     PaginatorConfigTypeDef,
     ServiceFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListInstancesPaginator",
     "ListNamespacesPaginator",
     "ListOperationsPaginator",
     "ListServicesPaginator",
 )
 
@@ -66,15 +60,15 @@
 class ListInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listinstancespaginator)
     """
 
     def paginate(
-        self, *, ServiceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServiceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listinstancespaginator)
         """
 
 class ListNamespacesPaginator(AioPaginator):
@@ -83,15 +77,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listnamespacespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[NamespaceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNamespacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListNamespaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listnamespacespaginator)
         """
 
 class ListOperationsPaginator(AioPaginator):
@@ -100,15 +94,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listoperationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[OperationFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOperationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listoperationspaginator)
         """
 
 class ListServicesPaginator(AioPaginator):
@@ -117,13 +111,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listservicespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ServiceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/paginators/#listservicespaginator)
         """
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/type_defs.py` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,71 +40,71 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateHttpNamespaceResponseTypeDef",
+    "CreatePrivateDnsNamespaceResponseTypeDef",
+    "CreatePublicDnsNamespaceResponseTypeDef",
     "HealthCheckConfigTypeDef",
     "HealthCheckCustomConfigTypeDef",
     "DeleteNamespaceRequestRequestTypeDef",
+    "DeleteNamespaceResponseTypeDef",
     "DeleteServiceRequestRequestTypeDef",
     "DeregisterInstanceRequestRequestTypeDef",
+    "DeregisterInstanceResponseTypeDef",
     "DiscoverInstancesRequestRequestTypeDef",
     "HttpInstanceSummaryTypeDef",
     "DnsRecordTypeDef",
     "SOATypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetInstanceRequestRequestTypeDef",
     "InstanceTypeDef",
     "GetInstancesHealthStatusRequestRequestTypeDef",
+    "GetInstancesHealthStatusResponseTypeDef",
     "GetNamespaceRequestRequestTypeDef",
     "GetOperationRequestRequestTypeDef",
     "OperationTypeDef",
     "GetServiceRequestRequestTypeDef",
     "HttpNamespaceChangeTypeDef",
     "HttpPropertiesTypeDef",
     "InstanceSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListInstancesRequestRequestTypeDef",
     "NamespaceFilterTypeDef",
     "OperationFilterTypeDef",
     "OperationSummaryTypeDef",
     "ServiceFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "SOAChangeTypeDef",
     "RegisterInstanceRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
-    "CreateHttpNamespaceRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateHttpNamespaceResponseTypeDef",
-    "CreatePrivateDnsNamespaceResponseTypeDef",
-    "CreatePublicDnsNamespaceResponseTypeDef",
-    "DeleteNamespaceResponseTypeDef",
-    "DeregisterInstanceResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetInstancesHealthStatusResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "RegisterInstanceResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "UpdateHttpNamespaceResponseTypeDef",
+    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
     "UpdatePrivateDnsNamespaceResponseTypeDef",
     "UpdatePublicDnsNamespaceResponseTypeDef",
     "UpdateServiceResponseTypeDef",
+    "CreateHttpNamespaceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "DiscoverInstancesResponseTypeDef",
     "DnsConfigChangeTypeDef",
     "DnsConfigTypeDef",
     "DnsPropertiesTypeDef",
     "PrivateDnsPropertiesMutableTypeDef",
     "PublicDnsPropertiesMutableTypeDef",
     "GetInstanceResponseTypeDef",
     "GetOperationResponseTypeDef",
     "UpdateHttpNamespaceRequestRequestTypeDef",
     "ListInstancesResponseTypeDef",
-    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListNamespacesRequestListNamespacesPaginateTypeDef",
     "ListNamespacesRequestRequestTypeDef",
     "ListOperationsRequestListOperationsPaginateTypeDef",
     "ListOperationsRequestRequestTypeDef",
     "ListOperationsResponseTypeDef",
     "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
@@ -139,22 +139,35 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateHttpNamespaceResponseTypeDef = TypedDict(
+    "CreateHttpNamespaceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePrivateDnsNamespaceResponseTypeDef = TypedDict(
+    "CreatePrivateDnsNamespaceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePublicDnsNamespaceResponseTypeDef = TypedDict(
+    "CreatePublicDnsNamespaceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHealthCheckConfigTypeDef = TypedDict(
     "_RequiredHealthCheckConfigTypeDef",
     {
         "Type": HealthCheckTypeType,
@@ -187,14 +200,22 @@
 DeleteNamespaceRequestRequestTypeDef = TypedDict(
     "DeleteNamespaceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+DeleteNamespaceResponseTypeDef = TypedDict(
+    "DeleteNamespaceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteServiceRequestRequestTypeDef = TypedDict(
     "DeleteServiceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -202,14 +223,22 @@
     "DeregisterInstanceRequestRequestTypeDef",
     {
         "ServiceId": str,
         "InstanceId": str,
     },
 )
 
+DeregisterInstanceResponseTypeDef = TypedDict(
+    "DeregisterInstanceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDiscoverInstancesRequestRequestTypeDef = TypedDict(
     "_RequiredDiscoverInstancesRequestRequestTypeDef",
     {
         "NamespaceName": str,
         "ServiceName": str,
     },
 )
@@ -254,14 +283,21 @@
 SOATypeDef = TypedDict(
     "SOATypeDef",
     {
         "TTL": int,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInstanceRequestRequestTypeDef = TypedDict(
     "GetInstanceRequestRequestTypeDef",
     {
         "ServiceId": str,
         "InstanceId": str,
     },
 )
@@ -306,14 +342,23 @@
 class GetInstancesHealthStatusRequestRequestTypeDef(
     _RequiredGetInstancesHealthStatusRequestRequestTypeDef,
     _OptionalGetInstancesHealthStatusRequestRequestTypeDef,
 ):
     pass
 
 
+GetInstancesHealthStatusResponseTypeDef = TypedDict(
+    "GetInstancesHealthStatusResponseTypeDef",
+    {
+        "Status": Dict[str, HealthStatusType],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetNamespaceRequestRequestTypeDef = TypedDict(
     "GetNamespaceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -366,24 +411,36 @@
     {
         "Id": str,
         "Attributes": Dict[str, str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "_RequiredListInstancesRequestListInstancesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServiceId": str,
+    },
+)
+_OptionalListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "_OptionalListInstancesRequestListInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListInstancesRequestListInstancesPaginateTypeDef(
+    _RequiredListInstancesRequestListInstancesPaginateTypeDef,
+    _OptionalListInstancesRequestListInstancesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListInstancesRequestRequestTypeDef = TypedDict(
     "_RequiredListInstancesRequestRequestTypeDef",
     {
         "ServiceId": str,
     },
 )
 _OptionalListInstancesRequestRequestTypeDef = TypedDict(
@@ -474,14 +531,24 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 SOAChangeTypeDef = TypedDict(
     "SOAChangeTypeDef",
     {
         "TTL": int,
     },
 )
 
@@ -504,172 +571,127 @@
 
 class RegisterInstanceRequestRequestTypeDef(
     _RequiredRegisterInstanceRequestRequestTypeDef, _OptionalRegisterInstanceRequestRequestTypeDef
 ):
     pass
 
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "TagKeys": Sequence[str],
-    },
-)
-
-UpdateInstanceCustomHealthStatusRequestRequestTypeDef = TypedDict(
-    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
+RegisterInstanceResponseTypeDef = TypedDict(
+    "RegisterInstanceResponseTypeDef",
     {
-        "ServiceId": str,
-        "InstanceId": str,
-        "Status": CustomHealthStatusType,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateHttpNamespaceRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateHttpNamespaceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "CreatorRequestId": str,
-        "Description": str,
-        "Tags": Sequence[TagTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
-
-class CreateHttpNamespaceRequestRequestTypeDef(
-    _RequiredCreateHttpNamespaceRequestRequestTypeDef,
-    _OptionalCreateHttpNamespaceRequestRequestTypeDef,
-):
-    pass
-
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
+        "TagKeys": Sequence[str],
     },
 )
 
-CreateHttpNamespaceResponseTypeDef = TypedDict(
-    "CreateHttpNamespaceResponseTypeDef",
+UpdateHttpNamespaceResponseTypeDef = TypedDict(
+    "UpdateHttpNamespaceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreatePrivateDnsNamespaceResponseTypeDef = TypedDict(
-    "CreatePrivateDnsNamespaceResponseTypeDef",
+UpdateInstanceCustomHealthStatusRequestRequestTypeDef = TypedDict(
+    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ServiceId": str,
+        "InstanceId": str,
+        "Status": CustomHealthStatusType,
     },
 )
 
-CreatePublicDnsNamespaceResponseTypeDef = TypedDict(
-    "CreatePublicDnsNamespaceResponseTypeDef",
+UpdatePrivateDnsNamespaceResponseTypeDef = TypedDict(
+    "UpdatePrivateDnsNamespaceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteNamespaceResponseTypeDef = TypedDict(
-    "DeleteNamespaceResponseTypeDef",
+UpdatePublicDnsNamespaceResponseTypeDef = TypedDict(
+    "UpdatePublicDnsNamespaceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeregisterInstanceResponseTypeDef = TypedDict(
-    "DeregisterInstanceResponseTypeDef",
+UpdateServiceResponseTypeDef = TypedDict(
+    "UpdateServiceResponseTypeDef",
     {
         "OperationId": str,
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
 
-GetInstancesHealthStatusResponseTypeDef = TypedDict(
-    "GetInstancesHealthStatusResponseTypeDef",
+_RequiredCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateHttpNamespaceRequestRequestTypeDef",
     {
-        "Status": Dict[str, HealthStatusType],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateHttpNamespaceRequestRequestTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CreatorRequestId": str,
+        "Description": str,
+        "Tags": Sequence[TagTypeDef],
     },
+    total=False,
 )
 
-RegisterInstanceResponseTypeDef = TypedDict(
-    "RegisterInstanceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateHttpNamespaceResponseTypeDef = TypedDict(
-    "UpdateHttpNamespaceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class CreateHttpNamespaceRequestRequestTypeDef(
+    _RequiredCreateHttpNamespaceRequestRequestTypeDef,
+    _OptionalCreateHttpNamespaceRequestRequestTypeDef,
+):
+    pass
 
-UpdatePrivateDnsNamespaceResponseTypeDef = TypedDict(
-    "UpdatePrivateDnsNamespaceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdatePublicDnsNamespaceResponseTypeDef = TypedDict(
-    "UpdatePublicDnsNamespaceResponseTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateServiceResponseTypeDef = TypedDict(
-    "UpdateServiceResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 DiscoverInstancesResponseTypeDef = TypedDict(
     "DiscoverInstancesResponseTypeDef",
     {
         "Instances": List[HttpInstanceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DnsConfigChangeTypeDef = TypedDict(
     "DnsConfigChangeTypeDef",
     {
         "DnsRecords": Sequence[DnsRecordTypeDef],
@@ -719,23 +741,23 @@
     },
 )
 
 GetInstanceResponseTypeDef = TypedDict(
     "GetInstanceResponseTypeDef",
     {
         "Instance": InstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationResponseTypeDef = TypedDict(
     "GetOperationResponseTypeDef",
     {
         "Operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateHttpNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateHttpNamespaceRequestRequestTypeDef",
     {
         "Id": str,
@@ -759,45 +781,23 @@
 
 
 ListInstancesResponseTypeDef = TypedDict(
     "ListInstancesResponseTypeDef",
     {
         "Instances": List[InstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "_RequiredListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "ServiceId": str,
-    },
-)
-_OptionalListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "_OptionalListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListInstancesRequestListInstancesPaginateTypeDef(
-    _RequiredListInstancesRequestListInstancesPaginateTypeDef,
-    _OptionalListInstancesRequestListInstancesPaginateTypeDef,
-):
-    pass
-
-
 ListNamespacesRequestListNamespacesPaginateTypeDef = TypedDict(
     "ListNamespacesRequestListNamespacesPaginateTypeDef",
     {
         "Filters": Sequence[NamespaceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListNamespacesRequestRequestTypeDef = TypedDict(
     "ListNamespacesRequestRequestTypeDef",
     {
@@ -808,15 +808,15 @@
     total=False,
 )
 
 ListOperationsRequestListOperationsPaginateTypeDef = TypedDict(
     "ListOperationsRequestListOperationsPaginateTypeDef",
     {
         "Filters": Sequence[OperationFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOperationsRequestRequestTypeDef = TypedDict(
     "ListOperationsRequestRequestTypeDef",
     {
@@ -828,23 +828,23 @@
 )
 
 ListOperationsResponseTypeDef = TypedDict(
     "ListOperationsResponseTypeDef",
     {
         "Operations": List[OperationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesRequestListServicesPaginateTypeDef = TypedDict(
     "ListServicesRequestListServicesPaginateTypeDef",
     {
         "Filters": Sequence[ServiceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListServicesRequestRequestTypeDef = TypedDict(
     "ListServicesRequestRequestTypeDef",
     {
@@ -989,31 +989,31 @@
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "Services": List[ServiceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceResponseTypeDef = TypedDict(
     "GetServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NamespaceSummaryTypeDef = TypedDict(
     "NamespaceSummaryTypeDef",
     {
         "Id": str,
@@ -1114,23 +1114,23 @@
 )
 
 ListNamespacesResponseTypeDef = TypedDict(
     "ListNamespacesResponseTypeDef",
     {
         "Namespaces": List[NamespaceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNamespaceResponseTypeDef = TypedDict(
     "GetNamespaceResponseTypeDef",
     {
         "Namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePrivateDnsNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePrivateDnsNamespaceRequestRequestTypeDef",
     {
         "Id": str,
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery/type_defs.pyi` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -39,71 +39,71 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateHttpNamespaceResponseTypeDef",
+    "CreatePrivateDnsNamespaceResponseTypeDef",
+    "CreatePublicDnsNamespaceResponseTypeDef",
     "HealthCheckConfigTypeDef",
     "HealthCheckCustomConfigTypeDef",
     "DeleteNamespaceRequestRequestTypeDef",
+    "DeleteNamespaceResponseTypeDef",
     "DeleteServiceRequestRequestTypeDef",
     "DeregisterInstanceRequestRequestTypeDef",
+    "DeregisterInstanceResponseTypeDef",
     "DiscoverInstancesRequestRequestTypeDef",
     "HttpInstanceSummaryTypeDef",
     "DnsRecordTypeDef",
     "SOATypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetInstanceRequestRequestTypeDef",
     "InstanceTypeDef",
     "GetInstancesHealthStatusRequestRequestTypeDef",
+    "GetInstancesHealthStatusResponseTypeDef",
     "GetNamespaceRequestRequestTypeDef",
     "GetOperationRequestRequestTypeDef",
     "OperationTypeDef",
     "GetServiceRequestRequestTypeDef",
     "HttpNamespaceChangeTypeDef",
     "HttpPropertiesTypeDef",
     "InstanceSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListInstancesRequestRequestTypeDef",
     "NamespaceFilterTypeDef",
     "OperationFilterTypeDef",
     "OperationSummaryTypeDef",
     "ServiceFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "SOAChangeTypeDef",
     "RegisterInstanceRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
-    "CreateHttpNamespaceRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateHttpNamespaceResponseTypeDef",
-    "CreatePrivateDnsNamespaceResponseTypeDef",
-    "CreatePublicDnsNamespaceResponseTypeDef",
-    "DeleteNamespaceResponseTypeDef",
-    "DeregisterInstanceResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetInstancesHealthStatusResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "RegisterInstanceResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "UpdateHttpNamespaceResponseTypeDef",
+    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
     "UpdatePrivateDnsNamespaceResponseTypeDef",
     "UpdatePublicDnsNamespaceResponseTypeDef",
     "UpdateServiceResponseTypeDef",
+    "CreateHttpNamespaceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "DiscoverInstancesResponseTypeDef",
     "DnsConfigChangeTypeDef",
     "DnsConfigTypeDef",
     "DnsPropertiesTypeDef",
     "PrivateDnsPropertiesMutableTypeDef",
     "PublicDnsPropertiesMutableTypeDef",
     "GetInstanceResponseTypeDef",
     "GetOperationResponseTypeDef",
     "UpdateHttpNamespaceRequestRequestTypeDef",
     "ListInstancesResponseTypeDef",
-    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListNamespacesRequestListNamespacesPaginateTypeDef",
     "ListNamespacesRequestRequestTypeDef",
     "ListOperationsRequestListOperationsPaginateTypeDef",
     "ListOperationsRequestRequestTypeDef",
     "ListOperationsResponseTypeDef",
     "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
@@ -138,22 +138,35 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateHttpNamespaceResponseTypeDef = TypedDict(
+    "CreateHttpNamespaceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePrivateDnsNamespaceResponseTypeDef = TypedDict(
+    "CreatePrivateDnsNamespaceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePublicDnsNamespaceResponseTypeDef = TypedDict(
+    "CreatePublicDnsNamespaceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHealthCheckConfigTypeDef = TypedDict(
     "_RequiredHealthCheckConfigTypeDef",
     {
         "Type": HealthCheckTypeType,
@@ -184,14 +197,22 @@
 DeleteNamespaceRequestRequestTypeDef = TypedDict(
     "DeleteNamespaceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+DeleteNamespaceResponseTypeDef = TypedDict(
+    "DeleteNamespaceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteServiceRequestRequestTypeDef = TypedDict(
     "DeleteServiceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -199,14 +220,22 @@
     "DeregisterInstanceRequestRequestTypeDef",
     {
         "ServiceId": str,
         "InstanceId": str,
     },
 )
 
+DeregisterInstanceResponseTypeDef = TypedDict(
+    "DeregisterInstanceResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDiscoverInstancesRequestRequestTypeDef = TypedDict(
     "_RequiredDiscoverInstancesRequestRequestTypeDef",
     {
         "NamespaceName": str,
         "ServiceName": str,
     },
 )
@@ -249,14 +278,21 @@
 SOATypeDef = TypedDict(
     "SOATypeDef",
     {
         "TTL": int,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInstanceRequestRequestTypeDef = TypedDict(
     "GetInstanceRequestRequestTypeDef",
     {
         "ServiceId": str,
         "InstanceId": str,
     },
 )
@@ -297,14 +333,23 @@
 
 class GetInstancesHealthStatusRequestRequestTypeDef(
     _RequiredGetInstancesHealthStatusRequestRequestTypeDef,
     _OptionalGetInstancesHealthStatusRequestRequestTypeDef,
 ):
     pass
 
+GetInstancesHealthStatusResponseTypeDef = TypedDict(
+    "GetInstancesHealthStatusResponseTypeDef",
+    {
+        "Status": Dict[str, HealthStatusType],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetNamespaceRequestRequestTypeDef = TypedDict(
     "GetNamespaceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -357,24 +402,34 @@
     {
         "Id": str,
         "Attributes": Dict[str, str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "_RequiredListInstancesRequestListInstancesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServiceId": str,
+    },
+)
+_OptionalListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "_OptionalListInstancesRequestListInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListInstancesRequestListInstancesPaginateTypeDef(
+    _RequiredListInstancesRequestListInstancesPaginateTypeDef,
+    _OptionalListInstancesRequestListInstancesPaginateTypeDef,
+):
+    pass
+
 _RequiredListInstancesRequestRequestTypeDef = TypedDict(
     "_RequiredListInstancesRequestRequestTypeDef",
     {
         "ServiceId": str,
     },
 )
 _OptionalListInstancesRequestRequestTypeDef = TypedDict(
@@ -457,14 +512,24 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 SOAChangeTypeDef = TypedDict(
     "SOAChangeTypeDef",
     {
         "TTL": int,
     },
 )
 
@@ -485,170 +550,125 @@
 )
 
 class RegisterInstanceRequestRequestTypeDef(
     _RequiredRegisterInstanceRequestRequestTypeDef, _OptionalRegisterInstanceRequestRequestTypeDef
 ):
     pass
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "TagKeys": Sequence[str],
-    },
-)
-
-UpdateInstanceCustomHealthStatusRequestRequestTypeDef = TypedDict(
-    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
+RegisterInstanceResponseTypeDef = TypedDict(
+    "RegisterInstanceResponseTypeDef",
     {
-        "ServiceId": str,
-        "InstanceId": str,
-        "Status": CustomHealthStatusType,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateHttpNamespaceRequestRequestTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateHttpNamespaceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "CreatorRequestId": str,
-        "Description": str,
-        "Tags": Sequence[TagTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
-class CreateHttpNamespaceRequestRequestTypeDef(
-    _RequiredCreateHttpNamespaceRequestRequestTypeDef,
-    _OptionalCreateHttpNamespaceRequestRequestTypeDef,
-):
-    pass
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
+        "TagKeys": Sequence[str],
     },
 )
 
-CreateHttpNamespaceResponseTypeDef = TypedDict(
-    "CreateHttpNamespaceResponseTypeDef",
+UpdateHttpNamespaceResponseTypeDef = TypedDict(
+    "UpdateHttpNamespaceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreatePrivateDnsNamespaceResponseTypeDef = TypedDict(
-    "CreatePrivateDnsNamespaceResponseTypeDef",
+UpdateInstanceCustomHealthStatusRequestRequestTypeDef = TypedDict(
+    "UpdateInstanceCustomHealthStatusRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ServiceId": str,
+        "InstanceId": str,
+        "Status": CustomHealthStatusType,
     },
 )
 
-CreatePublicDnsNamespaceResponseTypeDef = TypedDict(
-    "CreatePublicDnsNamespaceResponseTypeDef",
+UpdatePrivateDnsNamespaceResponseTypeDef = TypedDict(
+    "UpdatePrivateDnsNamespaceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteNamespaceResponseTypeDef = TypedDict(
-    "DeleteNamespaceResponseTypeDef",
+UpdatePublicDnsNamespaceResponseTypeDef = TypedDict(
+    "UpdatePublicDnsNamespaceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeregisterInstanceResponseTypeDef = TypedDict(
-    "DeregisterInstanceResponseTypeDef",
+UpdateServiceResponseTypeDef = TypedDict(
+    "UpdateServiceResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+_RequiredCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateHttpNamespaceRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
-
-GetInstancesHealthStatusResponseTypeDef = TypedDict(
-    "GetInstancesHealthStatusResponseTypeDef",
+_OptionalCreateHttpNamespaceRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateHttpNamespaceRequestRequestTypeDef",
     {
-        "Status": Dict[str, HealthStatusType],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CreatorRequestId": str,
+        "Description": str,
+        "Tags": Sequence[TagTypeDef],
     },
+    total=False,
 )
 
+class CreateHttpNamespaceRequestRequestTypeDef(
+    _RequiredCreateHttpNamespaceRequestRequestTypeDef,
+    _OptionalCreateHttpNamespaceRequestRequestTypeDef,
+):
+    pass
+
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterInstanceResponseTypeDef = TypedDict(
-    "RegisterInstanceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateHttpNamespaceResponseTypeDef = TypedDict(
-    "UpdateHttpNamespaceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePrivateDnsNamespaceResponseTypeDef = TypedDict(
-    "UpdatePrivateDnsNamespaceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePublicDnsNamespaceResponseTypeDef = TypedDict(
-    "UpdatePublicDnsNamespaceResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateServiceResponseTypeDef = TypedDict(
-    "UpdateServiceResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 DiscoverInstancesResponseTypeDef = TypedDict(
     "DiscoverInstancesResponseTypeDef",
     {
         "Instances": List[HttpInstanceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DnsConfigChangeTypeDef = TypedDict(
     "DnsConfigChangeTypeDef",
     {
         "DnsRecords": Sequence[DnsRecordTypeDef],
@@ -696,23 +716,23 @@
     },
 )
 
 GetInstanceResponseTypeDef = TypedDict(
     "GetInstanceResponseTypeDef",
     {
         "Instance": InstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationResponseTypeDef = TypedDict(
     "GetOperationResponseTypeDef",
     {
         "Operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateHttpNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateHttpNamespaceRequestRequestTypeDef",
     {
         "Id": str,
@@ -734,43 +754,23 @@
     pass
 
 ListInstancesResponseTypeDef = TypedDict(
     "ListInstancesResponseTypeDef",
     {
         "Instances": List[InstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "_RequiredListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "ServiceId": str,
-    },
-)
-_OptionalListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "_OptionalListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListInstancesRequestListInstancesPaginateTypeDef(
-    _RequiredListInstancesRequestListInstancesPaginateTypeDef,
-    _OptionalListInstancesRequestListInstancesPaginateTypeDef,
-):
-    pass
-
 ListNamespacesRequestListNamespacesPaginateTypeDef = TypedDict(
     "ListNamespacesRequestListNamespacesPaginateTypeDef",
     {
         "Filters": Sequence[NamespaceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListNamespacesRequestRequestTypeDef = TypedDict(
     "ListNamespacesRequestRequestTypeDef",
     {
@@ -781,15 +781,15 @@
     total=False,
 )
 
 ListOperationsRequestListOperationsPaginateTypeDef = TypedDict(
     "ListOperationsRequestListOperationsPaginateTypeDef",
     {
         "Filters": Sequence[OperationFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOperationsRequestRequestTypeDef = TypedDict(
     "ListOperationsRequestRequestTypeDef",
     {
@@ -801,23 +801,23 @@
 )
 
 ListOperationsResponseTypeDef = TypedDict(
     "ListOperationsResponseTypeDef",
     {
         "Operations": List[OperationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesRequestListServicesPaginateTypeDef = TypedDict(
     "ListServicesRequestListServicesPaginateTypeDef",
     {
         "Filters": Sequence[ServiceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListServicesRequestRequestTypeDef = TypedDict(
     "ListServicesRequestRequestTypeDef",
     {
@@ -960,31 +960,31 @@
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "Services": List[ServiceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceResponseTypeDef = TypedDict(
     "GetServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NamespaceSummaryTypeDef = TypedDict(
     "NamespaceSummaryTypeDef",
     {
         "Id": str,
@@ -1081,23 +1081,23 @@
 )
 
 ListNamespacesResponseTypeDef = TypedDict(
     "ListNamespacesResponseTypeDef",
     {
         "Namespaces": List[NamespaceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNamespaceResponseTypeDef = TypedDict(
     "GetNamespaceResponseTypeDef",
     {
         "Namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePrivateDnsNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePrivateDnsNamespaceRequestRequestTypeDef",
     {
         "Id": str,
```

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/PKG-INFO` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-servicediscovery
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServiceDiscovery 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServiceDiscovery 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-servicediscovery"></a>
 
 # types-aiobotocore-servicediscovery
 
 [![PyPI - types-aiobotocore-servicediscovery](https://img.shields.io/pypi/v/types-aiobotocore-servicediscovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicediscovery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-servicediscovery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-servicediscovery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-servicediscovery?color=blue)](https://pypistats.org/packages/types-aiobotocore-servicediscovery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServiceDiscovery 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
+[aiobotocore.ServiceDiscovery 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/servicediscovery.html#ServiceDiscovery)
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
 [types-aiobotocore-servicediscovery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_servicediscovery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -342,71 +342,71 @@
 
 `types_aiobotocore_servicediscovery.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_servicediscovery.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateHttpNamespaceResponseTypeDef,
+    CreatePrivateDnsNamespaceResponseTypeDef,
+    CreatePublicDnsNamespaceResponseTypeDef,
     HealthCheckConfigTypeDef,
     HealthCheckCustomConfigTypeDef,
     DeleteNamespaceRequestRequestTypeDef,
+    DeleteNamespaceResponseTypeDef,
     DeleteServiceRequestRequestTypeDef,
     DeregisterInstanceRequestRequestTypeDef,
+    DeregisterInstanceResponseTypeDef,
     DiscoverInstancesRequestRequestTypeDef,
     HttpInstanceSummaryTypeDef,
     DnsRecordTypeDef,
     SOATypeDef,
+    EmptyResponseMetadataTypeDef,
     GetInstanceRequestRequestTypeDef,
     InstanceTypeDef,
     GetInstancesHealthStatusRequestRequestTypeDef,
+    GetInstancesHealthStatusResponseTypeDef,
     GetNamespaceRequestRequestTypeDef,
     GetOperationRequestRequestTypeDef,
     OperationTypeDef,
     GetServiceRequestRequestTypeDef,
     HttpNamespaceChangeTypeDef,
     HttpPropertiesTypeDef,
     InstanceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
     NamespaceFilterTypeDef,
     OperationFilterTypeDef,
     OperationSummaryTypeDef,
     ServiceFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     SOAChangeTypeDef,
     RegisterInstanceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    UpdateInstanceCustomHealthStatusRequestRequestTypeDef,
-    CreateHttpNamespaceRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateHttpNamespaceResponseTypeDef,
-    CreatePrivateDnsNamespaceResponseTypeDef,
-    CreatePublicDnsNamespaceResponseTypeDef,
-    DeleteNamespaceResponseTypeDef,
-    DeregisterInstanceResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetInstancesHealthStatusResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     RegisterInstanceResponseTypeDef,
+    ResponseMetadataTypeDef,
+    UntagResourceRequestRequestTypeDef,
     UpdateHttpNamespaceResponseTypeDef,
+    UpdateInstanceCustomHealthStatusRequestRequestTypeDef,
     UpdatePrivateDnsNamespaceResponseTypeDef,
     UpdatePublicDnsNamespaceResponseTypeDef,
     UpdateServiceResponseTypeDef,
+    CreateHttpNamespaceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     DiscoverInstancesResponseTypeDef,
     DnsConfigChangeTypeDef,
     DnsConfigTypeDef,
     DnsPropertiesTypeDef,
     PrivateDnsPropertiesMutableTypeDef,
     PublicDnsPropertiesMutableTypeDef,
     GetInstanceResponseTypeDef,
     GetOperationResponseTypeDef,
     UpdateHttpNamespaceRequestRequestTypeDef,
     ListInstancesResponseTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
     ListNamespacesRequestListNamespacesPaginateTypeDef,
     ListNamespacesRequestRequestTypeDef,
     ListOperationsRequestListOperationsPaginateTypeDef,
     ListOperationsRequestRequestTypeDef,
     ListOperationsResponseTypeDef,
     ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-servicediscovery-2.5.0.post1/types_aiobotocore_servicediscovery.egg-info/SOURCES.txt` & `types-aiobotocore-servicediscovery-2.5.1/types_aiobotocore_servicediscovery.egg-info/SOURCES.txt`

 * *Files identical despite different names*

