# Comparing `tmp/types-aiobotocore-appmesh-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-appmesh-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-appmesh-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-appmesh-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-appmesh-2.5.0.post1.tar` & `types-aiobotocore-appmesh-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.730948 types-aiobotocore-appmesh-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22840 2023-03-11 12:26:12.726948 types-aiobotocore-appmesh-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21269 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.730948 types-aiobotocore-appmesh-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.722948 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/
--rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    32306 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    32251 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10831 2023-03-11 12:09:41.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10829 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10067 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10056 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    80418 2023-03-11 12:09:43.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    80267 2023-03-11 12:09:41.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:40.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.726948 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22840 2023-03-11 12:26:12.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:26:12.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:12.000000 types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.534094 types-aiobotocore-appmesh-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22832 2023-06-28 01:43:06.534094 types-aiobotocore-appmesh-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21267 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.534094 types-aiobotocore-appmesh-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.534094 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32306 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32251 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11040 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11038 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10091 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10081 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    80506 2023-06-28 01:26:19.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    80355 2023-06-28 01:26:18.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:17.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.534094 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22832 2023-06-28 01:43:06.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:43:06.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:06.000000 types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/LICENSE` & `types-aiobotocore-appmesh-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/PKG-INFO` & `types-aiobotocore-appmesh-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appmesh
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppMesh 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppMesh 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appmesh"></a>
 
 # types-aiobotocore-appmesh
 
 [![PyPI - types-aiobotocore-appmesh](https://img.shields.io/pypi/v/types-aiobotocore-appmesh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appmesh)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appmesh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appmesh)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appmesh?color=blue)](https://pypistats.org/packages/types-aiobotocore-appmesh)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppMesh 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
+[aiobotocore.AppMesh 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
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
 [types-aiobotocore-appmesh docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/).
 
 See how it helps to find and fix potential bugs:
 
@@ -372,15 +372,14 @@
 
 ```python
 from types_aiobotocore_appmesh.type_defs import (
     AwsCloudMapInstanceAttributeTypeDef,
     ListenerTlsFileCertificateTypeDef,
     ListenerTlsSdsCertificateTypeDef,
     TagRefTypeDef,
-    ResponseMetadataTypeDef,
     DeleteGatewayRouteInputRequestTypeDef,
     DeleteMeshInputRequestTypeDef,
     DeleteRouteInputRequestTypeDef,
     DeleteVirtualGatewayInputRequestTypeDef,
     DeleteVirtualNodeInputRequestTypeDef,
     DeleteVirtualRouterInputRequestTypeDef,
     DeleteVirtualServiceInputRequestTypeDef,
@@ -404,35 +403,44 @@
     WeightedTargetTypeDef,
     HealthCheckPolicyTypeDef,
     HttpPathMatchTypeDef,
     HttpGatewayRoutePathRewriteTypeDef,
     HttpGatewayRoutePrefixRewriteTypeDef,
     QueryParameterMatchTypeDef,
     JsonFormatRefTypeDef,
-    PaginatorConfigTypeDef,
+    ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
     ListGatewayRoutesInputRequestTypeDef,
+    ListMeshesInputListMeshesPaginateTypeDef,
     ListMeshesInputRequestTypeDef,
     MeshRefTypeDef,
+    ListRoutesInputListRoutesPaginateTypeDef,
     ListRoutesInputRequestTypeDef,
     RouteRefTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
     ListVirtualGatewaysInputRequestTypeDef,
     VirtualGatewayRefTypeDef,
+    ListVirtualNodesInputListVirtualNodesPaginateTypeDef,
     ListVirtualNodesInputRequestTypeDef,
     VirtualNodeRefTypeDef,
+    ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
     ListVirtualRoutersInputRequestTypeDef,
     VirtualRouterRefTypeDef,
+    ListVirtualServicesInputListVirtualServicesPaginateTypeDef,
     ListVirtualServicesInputRequestTypeDef,
     VirtualServiceRefTypeDef,
     ListenerTlsAcmCertificateTypeDef,
     TlsValidationContextFileTrustTypeDef,
     TlsValidationContextSdsTrustTypeDef,
     PortMappingTypeDef,
     MeshStatusTypeDef,
     MeshServiceDiscoveryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RouteStatusTypeDef,
     SubjectAlternativeNameMatchersTypeDef,
     TcpRouteMatchTypeDef,
     TlsValidationContextAcmTrustTypeDef,
     UntagResourceInputRequestTypeDef,
     VirtualGatewayListenerTlsFileCertificateTypeDef,
     VirtualGatewayListenerTlsSdsCertificateTypeDef,
@@ -453,16 +461,16 @@
     VirtualNodeStatusTypeDef,
     VirtualNodeServiceProviderTypeDef,
     VirtualRouterStatusTypeDef,
     VirtualRouterServiceProviderTypeDef,
     VirtualServiceStatusTypeDef,
     AwsCloudMapServiceDiscoveryTypeDef,
     ClientTlsCertificateTypeDef,
-    TagResourceInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
+    TagResourceInputRequestTypeDef,
     GrpcRetryPolicyTypeDef,
     GrpcTimeoutTypeDef,
     HttpRetryPolicyTypeDef,
     HttpTimeoutTypeDef,
     OutlierDetectionTypeDef,
     TcpTimeoutTypeDef,
     GrpcGatewayRouteRewriteTypeDef,
@@ -473,22 +481,14 @@
     HeaderMatchMethodTypeDef,
     GrpcRouteActionTypeDef,
     HttpRouteActionTypeDef,
     TcpRouteActionTypeDef,
     HttpGatewayRouteRewriteTypeDef,
     HttpQueryParameterTypeDef,
     LoggingFormatTypeDef,
-    ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-    ListMeshesInputListMeshesPaginateTypeDef,
-    ListRoutesInputListRoutesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-    ListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-    ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-    ListVirtualServicesInputListVirtualServicesPaginateTypeDef,
     ListMeshesOutputTypeDef,
     ListRoutesOutputTypeDef,
     ListVirtualGatewaysOutputTypeDef,
     ListVirtualNodesOutputTypeDef,
     ListVirtualRoutersOutputTypeDef,
     ListVirtualServicesOutputTypeDef,
     ListenerTlsCertificateTypeDef,
@@ -608,43 +608,43 @@
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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/README.md` & `types-aiobotocore-appmesh-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-appmesh"></a>
 
 # types-aiobotocore-appmesh
 
 [![PyPI - types-aiobotocore-appmesh](https://img.shields.io/pypi/v/types-aiobotocore-appmesh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appmesh)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appmesh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appmesh)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appmesh?color=blue)](https://pypistats.org/packages/types-aiobotocore-appmesh)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppMesh 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
+[aiobotocore.AppMesh 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
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
 [types-aiobotocore-appmesh docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,15 +339,14 @@
 
 ```python
 from types_aiobotocore_appmesh.type_defs import (
     AwsCloudMapInstanceAttributeTypeDef,
     ListenerTlsFileCertificateTypeDef,
     ListenerTlsSdsCertificateTypeDef,
     TagRefTypeDef,
-    ResponseMetadataTypeDef,
     DeleteGatewayRouteInputRequestTypeDef,
     DeleteMeshInputRequestTypeDef,
     DeleteRouteInputRequestTypeDef,
     DeleteVirtualGatewayInputRequestTypeDef,
     DeleteVirtualNodeInputRequestTypeDef,
     DeleteVirtualRouterInputRequestTypeDef,
     DeleteVirtualServiceInputRequestTypeDef,
@@ -371,35 +370,44 @@
     WeightedTargetTypeDef,
     HealthCheckPolicyTypeDef,
     HttpPathMatchTypeDef,
     HttpGatewayRoutePathRewriteTypeDef,
     HttpGatewayRoutePrefixRewriteTypeDef,
     QueryParameterMatchTypeDef,
     JsonFormatRefTypeDef,
-    PaginatorConfigTypeDef,
+    ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
     ListGatewayRoutesInputRequestTypeDef,
+    ListMeshesInputListMeshesPaginateTypeDef,
     ListMeshesInputRequestTypeDef,
     MeshRefTypeDef,
+    ListRoutesInputListRoutesPaginateTypeDef,
     ListRoutesInputRequestTypeDef,
     RouteRefTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
     ListVirtualGatewaysInputRequestTypeDef,
     VirtualGatewayRefTypeDef,
+    ListVirtualNodesInputListVirtualNodesPaginateTypeDef,
     ListVirtualNodesInputRequestTypeDef,
     VirtualNodeRefTypeDef,
+    ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
     ListVirtualRoutersInputRequestTypeDef,
     VirtualRouterRefTypeDef,
+    ListVirtualServicesInputListVirtualServicesPaginateTypeDef,
     ListVirtualServicesInputRequestTypeDef,
     VirtualServiceRefTypeDef,
     ListenerTlsAcmCertificateTypeDef,
     TlsValidationContextFileTrustTypeDef,
     TlsValidationContextSdsTrustTypeDef,
     PortMappingTypeDef,
     MeshStatusTypeDef,
     MeshServiceDiscoveryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RouteStatusTypeDef,
     SubjectAlternativeNameMatchersTypeDef,
     TcpRouteMatchTypeDef,
     TlsValidationContextAcmTrustTypeDef,
     UntagResourceInputRequestTypeDef,
     VirtualGatewayListenerTlsFileCertificateTypeDef,
     VirtualGatewayListenerTlsSdsCertificateTypeDef,
@@ -420,16 +428,16 @@
     VirtualNodeStatusTypeDef,
     VirtualNodeServiceProviderTypeDef,
     VirtualRouterStatusTypeDef,
     VirtualRouterServiceProviderTypeDef,
     VirtualServiceStatusTypeDef,
     AwsCloudMapServiceDiscoveryTypeDef,
     ClientTlsCertificateTypeDef,
-    TagResourceInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
+    TagResourceInputRequestTypeDef,
     GrpcRetryPolicyTypeDef,
     GrpcTimeoutTypeDef,
     HttpRetryPolicyTypeDef,
     HttpTimeoutTypeDef,
     OutlierDetectionTypeDef,
     TcpTimeoutTypeDef,
     GrpcGatewayRouteRewriteTypeDef,
@@ -440,22 +448,14 @@
     HeaderMatchMethodTypeDef,
     GrpcRouteActionTypeDef,
     HttpRouteActionTypeDef,
     TcpRouteActionTypeDef,
     HttpGatewayRouteRewriteTypeDef,
     HttpQueryParameterTypeDef,
     LoggingFormatTypeDef,
-    ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-    ListMeshesInputListMeshesPaginateTypeDef,
-    ListRoutesInputListRoutesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-    ListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-    ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-    ListVirtualServicesInputListVirtualServicesPaginateTypeDef,
     ListMeshesOutputTypeDef,
     ListRoutesOutputTypeDef,
     ListVirtualGatewaysOutputTypeDef,
     ListVirtualNodesOutputTypeDef,
     ListVirtualRoutersOutputTypeDef,
     ListVirtualServicesOutputTypeDef,
     ListenerTlsCertificateTypeDef,
@@ -575,43 +575,43 @@
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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/setup.py` & `types-aiobotocore-appmesh-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-appmesh.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-appmesh",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_appmesh"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppMesh 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.AppMesh 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/"
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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/__init__.py` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/__init__.pyi` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/__main__.py` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppMesh 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppMesh 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh\nOther"
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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/client.py` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/client.pyi` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/literals.py` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -147,14 +147,15 @@
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
@@ -233,14 +234,15 @@
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
@@ -251,14 +253,15 @@
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
@@ -294,14 +297,15 @@
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
@@ -320,16 +324,19 @@
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
@@ -413,15 +420,17 @@
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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/literals.pyi` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/literals.pyi`

 * *Files 1% similar despite different names*

```diff
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
```

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/paginator.py` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_virtual_gateways_paginator: ListVirtualGatewaysPaginator = client.get_paginator("list_virtual_gateways")
         list_virtual_nodes_paginator: ListVirtualNodesPaginator = client.get_paginator("list_virtual_nodes")
         list_virtual_routers_paginator: ListVirtualRoutersPaginator = client.get_paginator("list_virtual_routers")
         list_virtual_services_paginator: ListVirtualServicesPaginator = client.get_paginator("list_virtual_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListGatewayRoutesOutputTypeDef,
     ListMeshesOutputTypeDef,
@@ -48,163 +47,163 @@
     ListVirtualGatewaysOutputTypeDef,
     ListVirtualNodesOutputTypeDef,
     ListVirtualRoutersOutputTypeDef,
     ListVirtualServicesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListGatewayRoutesPaginator",
     "ListMeshesPaginator",
     "ListRoutesPaginator",
     "ListTagsForResourcePaginator",
     "ListVirtualGatewaysPaginator",
     "ListVirtualNodesPaginator",
     "ListVirtualRoutersPaginator",
     "ListVirtualServicesPaginator",
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
 class ListGatewayRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListGatewayRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listgatewayroutespaginator)
     """
 
     def paginate(
         self,
         *,
         meshName: str,
         virtualGatewayName: str,
         meshOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGatewayRoutesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListGatewayRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listgatewayroutespaginator)
         """
 
-
 class ListMeshesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListMeshes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listmeshespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMeshesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListMeshes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listmeshespaginator)
         """
 
-
 class ListRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listroutespaginator)
     """
 
     def paginate(
         self,
         *,
         meshName: str,
         virtualRouterName: str,
         meshOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listroutespaginator)
         """
 
-
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listtagsforresourcepaginator)
         """
 
-
 class ListVirtualGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualgatewayspaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualGatewaysOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualgatewayspaginator)
         """
 
-
 class ListVirtualNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualnodespaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualNodesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualnodespaginator)
         """
 
-
 class ListVirtualRoutersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualRouters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualrouterspaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualRoutersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualRouters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualrouterspaginator)
         """
 
-
 class ListVirtualServicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualServices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualservicespaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualServicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualservicespaginator)
         """
```

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/paginator.pyi` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/paginator.py`

 * *Files 7% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_virtual_gateways_paginator: ListVirtualGatewaysPaginator = client.get_paginator("list_virtual_gateways")
         list_virtual_nodes_paginator: ListVirtualNodesPaginator = client.get_paginator("list_virtual_nodes")
         list_virtual_routers_paginator: ListVirtualRoutersPaginator = client.get_paginator("list_virtual_routers")
         list_virtual_services_paginator: ListVirtualServicesPaginator = client.get_paginator("list_virtual_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListGatewayRoutesOutputTypeDef,
     ListMeshesOutputTypeDef,
@@ -48,152 +47,173 @@
     ListVirtualGatewaysOutputTypeDef,
     ListVirtualNodesOutputTypeDef,
     ListVirtualRoutersOutputTypeDef,
     ListVirtualServicesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListGatewayRoutesPaginator",
     "ListMeshesPaginator",
     "ListRoutesPaginator",
     "ListTagsForResourcePaginator",
     "ListVirtualGatewaysPaginator",
     "ListVirtualNodesPaginator",
     "ListVirtualRoutersPaginator",
     "ListVirtualServicesPaginator",
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
 class ListGatewayRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListGatewayRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listgatewayroutespaginator)
     """
 
     def paginate(
         self,
         *,
         meshName: str,
         virtualGatewayName: str,
         meshOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGatewayRoutesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListGatewayRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listgatewayroutespaginator)
         """
 
+
 class ListMeshesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListMeshes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listmeshespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMeshesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListMeshes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listmeshespaginator)
         """
 
+
 class ListRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listroutespaginator)
     """
 
     def paginate(
         self,
         *,
         meshName: str,
         virtualRouterName: str,
         meshOwner: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listroutespaginator)
         """
 
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listtagsforresourcepaginator)
         """
 
+
 class ListVirtualGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualgatewayspaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualGatewaysOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualgatewayspaginator)
         """
 
+
 class ListVirtualNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualnodespaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualNodesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualnodespaginator)
         """
 
+
 class ListVirtualRoutersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualRouters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualrouterspaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualRoutersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualRouters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualrouterspaginator)
         """
 
+
 class ListVirtualServicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualServices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualservicespaginator)
     """
 
     def paginate(
-        self, *, meshName: str, meshOwner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        meshName: str,
+        meshOwner: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualServicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh.Paginator.ListVirtualServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/paginators/#listvirtualservicespaginator)
         """
```

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/type_defs.py` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -48,15 +48,14 @@
 
 
 __all__ = (
     "AwsCloudMapInstanceAttributeTypeDef",
     "ListenerTlsFileCertificateTypeDef",
     "ListenerTlsSdsCertificateTypeDef",
     "TagRefTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteGatewayRouteInputRequestTypeDef",
     "DeleteMeshInputRequestTypeDef",
     "DeleteRouteInputRequestTypeDef",
     "DeleteVirtualGatewayInputRequestTypeDef",
     "DeleteVirtualNodeInputRequestTypeDef",
     "DeleteVirtualRouterInputRequestTypeDef",
     "DeleteVirtualServiceInputRequestTypeDef",
@@ -80,35 +79,44 @@
     "WeightedTargetTypeDef",
     "HealthCheckPolicyTypeDef",
     "HttpPathMatchTypeDef",
     "HttpGatewayRoutePathRewriteTypeDef",
     "HttpGatewayRoutePrefixRewriteTypeDef",
     "QueryParameterMatchTypeDef",
     "JsonFormatRefTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
     "ListGatewayRoutesInputRequestTypeDef",
+    "ListMeshesInputListMeshesPaginateTypeDef",
     "ListMeshesInputRequestTypeDef",
     "MeshRefTypeDef",
+    "ListRoutesInputListRoutesPaginateTypeDef",
     "ListRoutesInputRequestTypeDef",
     "RouteRefTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
     "ListVirtualGatewaysInputRequestTypeDef",
     "VirtualGatewayRefTypeDef",
+    "ListVirtualNodesInputListVirtualNodesPaginateTypeDef",
     "ListVirtualNodesInputRequestTypeDef",
     "VirtualNodeRefTypeDef",
+    "ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
     "ListVirtualRoutersInputRequestTypeDef",
     "VirtualRouterRefTypeDef",
+    "ListVirtualServicesInputListVirtualServicesPaginateTypeDef",
     "ListVirtualServicesInputRequestTypeDef",
     "VirtualServiceRefTypeDef",
     "ListenerTlsAcmCertificateTypeDef",
     "TlsValidationContextFileTrustTypeDef",
     "TlsValidationContextSdsTrustTypeDef",
     "PortMappingTypeDef",
     "MeshStatusTypeDef",
     "MeshServiceDiscoveryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RouteStatusTypeDef",
     "SubjectAlternativeNameMatchersTypeDef",
     "TcpRouteMatchTypeDef",
     "TlsValidationContextAcmTrustTypeDef",
     "UntagResourceInputRequestTypeDef",
     "VirtualGatewayListenerTlsFileCertificateTypeDef",
     "VirtualGatewayListenerTlsSdsCertificateTypeDef",
@@ -129,16 +137,16 @@
     "VirtualNodeStatusTypeDef",
     "VirtualNodeServiceProviderTypeDef",
     "VirtualRouterStatusTypeDef",
     "VirtualRouterServiceProviderTypeDef",
     "VirtualServiceStatusTypeDef",
     "AwsCloudMapServiceDiscoveryTypeDef",
     "ClientTlsCertificateTypeDef",
-    "TagResourceInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
+    "TagResourceInputRequestTypeDef",
     "GrpcRetryPolicyTypeDef",
     "GrpcTimeoutTypeDef",
     "HttpRetryPolicyTypeDef",
     "HttpTimeoutTypeDef",
     "OutlierDetectionTypeDef",
     "TcpTimeoutTypeDef",
     "GrpcGatewayRouteRewriteTypeDef",
@@ -149,22 +157,14 @@
     "HeaderMatchMethodTypeDef",
     "GrpcRouteActionTypeDef",
     "HttpRouteActionTypeDef",
     "TcpRouteActionTypeDef",
     "HttpGatewayRouteRewriteTypeDef",
     "HttpQueryParameterTypeDef",
     "LoggingFormatTypeDef",
-    "ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
-    "ListMeshesInputListMeshesPaginateTypeDef",
-    "ListRoutesInputListRoutesPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    "ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
-    "ListVirtualNodesInputListVirtualNodesPaginateTypeDef",
-    "ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
-    "ListVirtualServicesInputListVirtualServicesPaginateTypeDef",
     "ListMeshesOutputTypeDef",
     "ListRoutesOutputTypeDef",
     "ListVirtualGatewaysOutputTypeDef",
     "ListVirtualNodesOutputTypeDef",
     "ListVirtualRoutersOutputTypeDef",
     "ListVirtualServicesOutputTypeDef",
     "ListenerTlsCertificateTypeDef",
@@ -303,25 +303,14 @@
     "TagRefTypeDef",
     {
         "key": str,
         "value": str,
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
 _RequiredDeleteGatewayRouteInputRequestTypeDef = TypedDict(
     "_RequiredDeleteGatewayRouteInputRequestTypeDef",
     {
         "gatewayRouteName": str,
         "meshName": str,
         "virtualGatewayName": str,
     },
@@ -809,24 +798,38 @@
     "JsonFormatRefTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "meshName": str,
+        "virtualGatewayName": str,
+    },
+)
+_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef(
+    _RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
+    _OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGatewayRoutesInputRequestTypeDef = TypedDict(
     "_RequiredListGatewayRoutesInputRequestTypeDef",
     {
         "meshName": str,
         "virtualGatewayName": str,
     },
 )
@@ -843,14 +846,22 @@
 
 class ListGatewayRoutesInputRequestTypeDef(
     _RequiredListGatewayRoutesInputRequestTypeDef, _OptionalListGatewayRoutesInputRequestTypeDef
 ):
     pass
 
 
+ListMeshesInputListMeshesPaginateTypeDef = TypedDict(
+    "ListMeshesInputListMeshesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMeshesInputRequestTypeDef = TypedDict(
     "ListMeshesInputRequestTypeDef",
     {
         "limit": int,
         "nextToken": str,
     },
     total=False,
@@ -865,14 +876,38 @@
         "meshName": str,
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
     },
 )
 
+_RequiredListRoutesInputListRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListRoutesInputListRoutesPaginateTypeDef",
+    {
+        "meshName": str,
+        "virtualRouterName": str,
+    },
+)
+_OptionalListRoutesInputListRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListRoutesInputListRoutesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRoutesInputListRoutesPaginateTypeDef(
+    _RequiredListRoutesInputListRoutesPaginateTypeDef,
+    _OptionalListRoutesInputListRoutesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRoutesInputRequestTypeDef = TypedDict(
     "_RequiredListRoutesInputRequestTypeDef",
     {
         "meshName": str,
         "virtualRouterName": str,
     },
 )
@@ -904,14 +939,36 @@
         "resourceOwner": str,
         "routeName": str,
         "version": int,
         "virtualRouterName": str,
     },
 )
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -926,14 +983,37 @@
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
 ):
     pass
 
 
+_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef(
+    _RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
+    _OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVirtualGatewaysInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualGatewaysInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualGatewaysInputRequestTypeDef = TypedDict(
@@ -963,14 +1043,37 @@
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
         "virtualGatewayName": str,
     },
 )
 
+_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVirtualNodesInputListVirtualNodesPaginateTypeDef(
+    _RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef,
+    _OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVirtualNodesInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualNodesInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualNodesInputRequestTypeDef = TypedDict(
@@ -1000,14 +1103,37 @@
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
         "virtualNodeName": str,
     },
 )
 
+_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef(
+    _RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
+    _OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVirtualRoutersInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualRoutersInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualRoutersInputRequestTypeDef = TypedDict(
@@ -1037,14 +1163,37 @@
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
         "virtualRouterName": str,
     },
 )
 
+_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVirtualServicesInputListVirtualServicesPaginateTypeDef(
+    _RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef,
+    _OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVirtualServicesInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualServicesInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualServicesInputRequestTypeDef = TypedDict(
@@ -1119,14 +1268,35 @@
     "MeshServiceDiscoveryTypeDef",
     {
         "ipPreference": IpPreferenceType,
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
 RouteStatusTypeDef = TypedDict(
     "RouteStatusTypeDef",
     {
         "status": RouteStatusCodeType,
     },
 )
 
@@ -1385,28 +1555,28 @@
     {
         "file": ListenerTlsFileCertificateTypeDef,
         "sds": ListenerTlsSdsCertificateTypeDef,
     },
     total=False,
 )
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagRefTypeDef],
-    },
-)
-
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "nextToken": str,
         "tags": List[TagRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tags": Sequence[TagRefTypeDef],
     },
 )
 
 _RequiredGrpcRetryPolicyTypeDef = TypedDict(
     "_RequiredGrpcRetryPolicyTypeDef",
     {
         "maxRetries": int,
@@ -1494,15 +1664,15 @@
 )
 
 ListGatewayRoutesOutputTypeDef = TypedDict(
     "ListGatewayRoutesOutputTypeDef",
     {
         "gatewayRoutes": List[GatewayRouteRefTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGatewayRouteTargetTypeDef = TypedDict(
     "_RequiredGatewayRouteTargetTypeDef",
     {
         "virtualService": GatewayRouteVirtualServiceTypeDef,
@@ -1616,235 +1786,65 @@
     {
         "json": Sequence[JsonFormatRefTypeDef],
         "text": str,
     },
     total=False,
 )
 
-_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
-    {
-        "meshName": str,
-        "virtualGatewayName": str,
-    },
-)
-_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef(
-    _RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-    _OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-):
-    pass
-
-
-ListMeshesInputListMeshesPaginateTypeDef = TypedDict(
-    "ListMeshesInputListMeshesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRoutesInputListRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListRoutesInputListRoutesPaginateTypeDef",
-    {
-        "meshName": str,
-        "virtualRouterName": str,
-    },
-)
-_OptionalListRoutesInputListRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListRoutesInputListRoutesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRoutesInputListRoutesPaginateTypeDef(
-    _RequiredListRoutesInputListRoutesPaginateTypeDef,
-    _OptionalListRoutesInputListRoutesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef(
-    _RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-    _OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVirtualNodesInputListVirtualNodesPaginateTypeDef(
-    _RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-    _OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef(
-    _RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-    _OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVirtualServicesInputListVirtualServicesPaginateTypeDef(
-    _RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef,
-    _OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef,
-):
-    pass
-
-
 ListMeshesOutputTypeDef = TypedDict(
     "ListMeshesOutputTypeDef",
     {
         "meshes": List[MeshRefTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoutesOutputTypeDef = TypedDict(
     "ListRoutesOutputTypeDef",
     {
         "nextToken": str,
         "routes": List[RouteRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualGatewaysOutputTypeDef = TypedDict(
     "ListVirtualGatewaysOutputTypeDef",
     {
         "nextToken": str,
         "virtualGateways": List[VirtualGatewayRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualNodesOutputTypeDef = TypedDict(
     "ListVirtualNodesOutputTypeDef",
     {
         "nextToken": str,
         "virtualNodes": List[VirtualNodeRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualRoutersOutputTypeDef = TypedDict(
     "ListVirtualRoutersOutputTypeDef",
     {
         "nextToken": str,
         "virtualRouters": List[VirtualRouterRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualServicesOutputTypeDef = TypedDict(
     "ListVirtualServicesOutputTypeDef",
     {
         "nextToken": str,
         "virtualServices": List[VirtualServiceRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListenerTlsCertificateTypeDef = TypedDict(
     "ListenerTlsCertificateTypeDef",
     {
         "acm": ListenerTlsAcmCertificateTypeDef,
@@ -2455,39 +2455,39 @@
     },
 )
 
 CreateMeshOutputTypeDef = TypedDict(
     "CreateMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMeshOutputTypeDef = TypedDict(
     "DeleteMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMeshOutputTypeDef = TypedDict(
     "DescribeMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMeshOutputTypeDef = TypedDict(
     "UpdateMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListenerTlsTypeDef = TypedDict(
     "_RequiredListenerTlsTypeDef",
     {
         "certificate": ListenerTlsCertificateTypeDef,
@@ -2709,39 +2709,39 @@
     total=False,
 )
 
 CreateVirtualRouterOutputTypeDef = TypedDict(
     "CreateVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualRouterOutputTypeDef = TypedDict(
     "DeleteVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualRouterOutputTypeDef = TypedDict(
     "DescribeVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualRouterOutputTypeDef = TypedDict(
     "UpdateVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListenerTypeDef = TypedDict(
     "_RequiredListenerTypeDef",
     {
         "portMapping": PortMappingTypeDef,
@@ -2803,39 +2803,39 @@
     total=False,
 )
 
 CreateVirtualServiceOutputTypeDef = TypedDict(
     "CreateVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualServiceOutputTypeDef = TypedDict(
     "DeleteVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualServiceOutputTypeDef = TypedDict(
     "DescribeVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualServiceOutputTypeDef = TypedDict(
     "UpdateVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GatewayRouteSpecTypeDef = TypedDict(
     "GatewayRouteSpecTypeDef",
     {
         "grpcRoute": GrpcGatewayRouteTypeDef,
@@ -3051,71 +3051,71 @@
     pass
 
 
 CreateGatewayRouteOutputTypeDef = TypedDict(
     "CreateGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGatewayRouteOutputTypeDef = TypedDict(
     "DeleteGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGatewayRouteOutputTypeDef = TypedDict(
     "DescribeGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGatewayRouteOutputTypeDef = TypedDict(
     "UpdateGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRouteOutputTypeDef = TypedDict(
     "CreateRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRouteOutputTypeDef = TypedDict(
     "DeleteRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRouteOutputTypeDef = TypedDict(
     "DescribeRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRouteOutputTypeDef = TypedDict(
     "UpdateRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualNodeSpecTypeDef = TypedDict(
     "VirtualNodeSpecTypeDef",
     {
         "backendDefaults": BackendDefaultsTypeDef,
@@ -3249,66 +3249,66 @@
     },
 )
 
 CreateVirtualGatewayOutputTypeDef = TypedDict(
     "CreateVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualGatewayOutputTypeDef = TypedDict(
     "DeleteVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualGatewayOutputTypeDef = TypedDict(
     "DescribeVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualGatewayOutputTypeDef = TypedDict(
     "UpdateVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVirtualNodeOutputTypeDef = TypedDict(
     "CreateVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualNodeOutputTypeDef = TypedDict(
     "DeleteVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualNodeOutputTypeDef = TypedDict(
     "DescribeVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualNodeOutputTypeDef = TypedDict(
     "UpdateVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh/type_defs.pyi` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -47,15 +47,14 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AwsCloudMapInstanceAttributeTypeDef",
     "ListenerTlsFileCertificateTypeDef",
     "ListenerTlsSdsCertificateTypeDef",
     "TagRefTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteGatewayRouteInputRequestTypeDef",
     "DeleteMeshInputRequestTypeDef",
     "DeleteRouteInputRequestTypeDef",
     "DeleteVirtualGatewayInputRequestTypeDef",
     "DeleteVirtualNodeInputRequestTypeDef",
     "DeleteVirtualRouterInputRequestTypeDef",
     "DeleteVirtualServiceInputRequestTypeDef",
@@ -79,35 +78,44 @@
     "WeightedTargetTypeDef",
     "HealthCheckPolicyTypeDef",
     "HttpPathMatchTypeDef",
     "HttpGatewayRoutePathRewriteTypeDef",
     "HttpGatewayRoutePrefixRewriteTypeDef",
     "QueryParameterMatchTypeDef",
     "JsonFormatRefTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
     "ListGatewayRoutesInputRequestTypeDef",
+    "ListMeshesInputListMeshesPaginateTypeDef",
     "ListMeshesInputRequestTypeDef",
     "MeshRefTypeDef",
+    "ListRoutesInputListRoutesPaginateTypeDef",
     "ListRoutesInputRequestTypeDef",
     "RouteRefTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
     "ListVirtualGatewaysInputRequestTypeDef",
     "VirtualGatewayRefTypeDef",
+    "ListVirtualNodesInputListVirtualNodesPaginateTypeDef",
     "ListVirtualNodesInputRequestTypeDef",
     "VirtualNodeRefTypeDef",
+    "ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
     "ListVirtualRoutersInputRequestTypeDef",
     "VirtualRouterRefTypeDef",
+    "ListVirtualServicesInputListVirtualServicesPaginateTypeDef",
     "ListVirtualServicesInputRequestTypeDef",
     "VirtualServiceRefTypeDef",
     "ListenerTlsAcmCertificateTypeDef",
     "TlsValidationContextFileTrustTypeDef",
     "TlsValidationContextSdsTrustTypeDef",
     "PortMappingTypeDef",
     "MeshStatusTypeDef",
     "MeshServiceDiscoveryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RouteStatusTypeDef",
     "SubjectAlternativeNameMatchersTypeDef",
     "TcpRouteMatchTypeDef",
     "TlsValidationContextAcmTrustTypeDef",
     "UntagResourceInputRequestTypeDef",
     "VirtualGatewayListenerTlsFileCertificateTypeDef",
     "VirtualGatewayListenerTlsSdsCertificateTypeDef",
@@ -128,16 +136,16 @@
     "VirtualNodeStatusTypeDef",
     "VirtualNodeServiceProviderTypeDef",
     "VirtualRouterStatusTypeDef",
     "VirtualRouterServiceProviderTypeDef",
     "VirtualServiceStatusTypeDef",
     "AwsCloudMapServiceDiscoveryTypeDef",
     "ClientTlsCertificateTypeDef",
-    "TagResourceInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
+    "TagResourceInputRequestTypeDef",
     "GrpcRetryPolicyTypeDef",
     "GrpcTimeoutTypeDef",
     "HttpRetryPolicyTypeDef",
     "HttpTimeoutTypeDef",
     "OutlierDetectionTypeDef",
     "TcpTimeoutTypeDef",
     "GrpcGatewayRouteRewriteTypeDef",
@@ -148,22 +156,14 @@
     "HeaderMatchMethodTypeDef",
     "GrpcRouteActionTypeDef",
     "HttpRouteActionTypeDef",
     "TcpRouteActionTypeDef",
     "HttpGatewayRouteRewriteTypeDef",
     "HttpQueryParameterTypeDef",
     "LoggingFormatTypeDef",
-    "ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
-    "ListMeshesInputListMeshesPaginateTypeDef",
-    "ListRoutesInputListRoutesPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    "ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
-    "ListVirtualNodesInputListVirtualNodesPaginateTypeDef",
-    "ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
-    "ListVirtualServicesInputListVirtualServicesPaginateTypeDef",
     "ListMeshesOutputTypeDef",
     "ListRoutesOutputTypeDef",
     "ListVirtualGatewaysOutputTypeDef",
     "ListVirtualNodesOutputTypeDef",
     "ListVirtualRoutersOutputTypeDef",
     "ListVirtualServicesOutputTypeDef",
     "ListenerTlsCertificateTypeDef",
@@ -302,25 +302,14 @@
     "TagRefTypeDef",
     {
         "key": str,
         "value": str,
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
 _RequiredDeleteGatewayRouteInputRequestTypeDef = TypedDict(
     "_RequiredDeleteGatewayRouteInputRequestTypeDef",
     {
         "gatewayRouteName": str,
         "meshName": str,
         "virtualGatewayName": str,
     },
@@ -776,24 +765,36 @@
     "JsonFormatRefTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "meshName": str,
+        "virtualGatewayName": str,
+    },
+)
+_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef(
+    _RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
+    _OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
+):
+    pass
+
 _RequiredListGatewayRoutesInputRequestTypeDef = TypedDict(
     "_RequiredListGatewayRoutesInputRequestTypeDef",
     {
         "meshName": str,
         "virtualGatewayName": str,
     },
 )
@@ -808,14 +809,22 @@
 )
 
 class ListGatewayRoutesInputRequestTypeDef(
     _RequiredListGatewayRoutesInputRequestTypeDef, _OptionalListGatewayRoutesInputRequestTypeDef
 ):
     pass
 
+ListMeshesInputListMeshesPaginateTypeDef = TypedDict(
+    "ListMeshesInputListMeshesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMeshesInputRequestTypeDef = TypedDict(
     "ListMeshesInputRequestTypeDef",
     {
         "limit": int,
         "nextToken": str,
     },
     total=False,
@@ -830,14 +839,36 @@
         "meshName": str,
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
     },
 )
 
+_RequiredListRoutesInputListRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListRoutesInputListRoutesPaginateTypeDef",
+    {
+        "meshName": str,
+        "virtualRouterName": str,
+    },
+)
+_OptionalListRoutesInputListRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListRoutesInputListRoutesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRoutesInputListRoutesPaginateTypeDef(
+    _RequiredListRoutesInputListRoutesPaginateTypeDef,
+    _OptionalListRoutesInputListRoutesPaginateTypeDef,
+):
+    pass
+
 _RequiredListRoutesInputRequestTypeDef = TypedDict(
     "_RequiredListRoutesInputRequestTypeDef",
     {
         "meshName": str,
         "virtualRouterName": str,
     },
 )
@@ -867,14 +898,34 @@
         "resourceOwner": str,
         "routeName": str,
         "version": int,
         "virtualRouterName": str,
     },
 )
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -887,14 +938,35 @@
 )
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
 ):
     pass
 
+_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef(
+    _RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
+    _OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
+):
+    pass
+
 _RequiredListVirtualGatewaysInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualGatewaysInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualGatewaysInputRequestTypeDef = TypedDict(
@@ -922,14 +994,35 @@
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
         "virtualGatewayName": str,
     },
 )
 
+_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVirtualNodesInputListVirtualNodesPaginateTypeDef(
+    _RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef,
+    _OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef,
+):
+    pass
+
 _RequiredListVirtualNodesInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualNodesInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualNodesInputRequestTypeDef = TypedDict(
@@ -957,14 +1050,35 @@
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
         "virtualNodeName": str,
     },
 )
 
+_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef(
+    _RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
+    _OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
+):
+    pass
+
 _RequiredListVirtualRoutersInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualRoutersInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualRoutersInputRequestTypeDef = TypedDict(
@@ -992,14 +1106,35 @@
         "meshOwner": str,
         "resourceOwner": str,
         "version": int,
         "virtualRouterName": str,
     },
 )
 
+_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
+    "_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef",
+    {
+        "meshName": str,
+    },
+)
+_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
+    "_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef",
+    {
+        "meshOwner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVirtualServicesInputListVirtualServicesPaginateTypeDef(
+    _RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef,
+    _OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef,
+):
+    pass
+
 _RequiredListVirtualServicesInputRequestTypeDef = TypedDict(
     "_RequiredListVirtualServicesInputRequestTypeDef",
     {
         "meshName": str,
     },
 )
 _OptionalListVirtualServicesInputRequestTypeDef = TypedDict(
@@ -1072,14 +1207,35 @@
     "MeshServiceDiscoveryTypeDef",
     {
         "ipPreference": IpPreferenceType,
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
 RouteStatusTypeDef = TypedDict(
     "RouteStatusTypeDef",
     {
         "status": RouteStatusCodeType,
     },
 )
 
@@ -1330,28 +1486,28 @@
     {
         "file": ListenerTlsFileCertificateTypeDef,
         "sds": ListenerTlsSdsCertificateTypeDef,
     },
     total=False,
 )
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagRefTypeDef],
-    },
-)
-
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "nextToken": str,
         "tags": List[TagRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tags": Sequence[TagRefTypeDef],
     },
 )
 
 _RequiredGrpcRetryPolicyTypeDef = TypedDict(
     "_RequiredGrpcRetryPolicyTypeDef",
     {
         "maxRetries": int,
@@ -1435,15 +1591,15 @@
 )
 
 ListGatewayRoutesOutputTypeDef = TypedDict(
     "ListGatewayRoutesOutputTypeDef",
     {
         "gatewayRoutes": List[GatewayRouteRefTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGatewayRouteTargetTypeDef = TypedDict(
     "_RequiredGatewayRouteTargetTypeDef",
     {
         "virtualService": GatewayRouteVirtualServiceTypeDef,
@@ -1553,221 +1709,65 @@
     {
         "json": Sequence[JsonFormatRefTypeDef],
         "text": str,
     },
     total=False,
 )
 
-_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
-    {
-        "meshName": str,
-        "virtualGatewayName": str,
-    },
-)
-_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef(
-    _RequiredListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-    _OptionalListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-):
-    pass
-
-ListMeshesInputListMeshesPaginateTypeDef = TypedDict(
-    "ListMeshesInputListMeshesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRoutesInputListRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListRoutesInputListRoutesPaginateTypeDef",
-    {
-        "meshName": str,
-        "virtualRouterName": str,
-    },
-)
-_OptionalListRoutesInputListRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListRoutesInputListRoutesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRoutesInputListRoutesPaginateTypeDef(
-    _RequiredListRoutesInputListRoutesPaginateTypeDef,
-    _OptionalListRoutesInputListRoutesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef(
-    _RequiredListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-    _OptionalListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-):
-    pass
-
-_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVirtualNodesInputListVirtualNodesPaginateTypeDef(
-    _RequiredListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-    _OptionalListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-):
-    pass
-
-_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef(
-    _RequiredListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-    _OptionalListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-):
-    pass
-
-_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
-    "_RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef",
-    {
-        "meshName": str,
-    },
-)
-_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef = TypedDict(
-    "_OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef",
-    {
-        "meshOwner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVirtualServicesInputListVirtualServicesPaginateTypeDef(
-    _RequiredListVirtualServicesInputListVirtualServicesPaginateTypeDef,
-    _OptionalListVirtualServicesInputListVirtualServicesPaginateTypeDef,
-):
-    pass
-
 ListMeshesOutputTypeDef = TypedDict(
     "ListMeshesOutputTypeDef",
     {
         "meshes": List[MeshRefTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoutesOutputTypeDef = TypedDict(
     "ListRoutesOutputTypeDef",
     {
         "nextToken": str,
         "routes": List[RouteRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualGatewaysOutputTypeDef = TypedDict(
     "ListVirtualGatewaysOutputTypeDef",
     {
         "nextToken": str,
         "virtualGateways": List[VirtualGatewayRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualNodesOutputTypeDef = TypedDict(
     "ListVirtualNodesOutputTypeDef",
     {
         "nextToken": str,
         "virtualNodes": List[VirtualNodeRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualRoutersOutputTypeDef = TypedDict(
     "ListVirtualRoutersOutputTypeDef",
     {
         "nextToken": str,
         "virtualRouters": List[VirtualRouterRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualServicesOutputTypeDef = TypedDict(
     "ListVirtualServicesOutputTypeDef",
     {
         "nextToken": str,
         "virtualServices": List[VirtualServiceRefTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListenerTlsCertificateTypeDef = TypedDict(
     "ListenerTlsCertificateTypeDef",
     {
         "acm": ListenerTlsAcmCertificateTypeDef,
@@ -2344,39 +2344,39 @@
     },
 )
 
 CreateMeshOutputTypeDef = TypedDict(
     "CreateMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMeshOutputTypeDef = TypedDict(
     "DeleteMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMeshOutputTypeDef = TypedDict(
     "DescribeMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMeshOutputTypeDef = TypedDict(
     "UpdateMeshOutputTypeDef",
     {
         "mesh": MeshDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListenerTlsTypeDef = TypedDict(
     "_RequiredListenerTlsTypeDef",
     {
         "certificate": ListenerTlsCertificateTypeDef,
@@ -2582,39 +2582,39 @@
     total=False,
 )
 
 CreateVirtualRouterOutputTypeDef = TypedDict(
     "CreateVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualRouterOutputTypeDef = TypedDict(
     "DeleteVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualRouterOutputTypeDef = TypedDict(
     "DescribeVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualRouterOutputTypeDef = TypedDict(
     "UpdateVirtualRouterOutputTypeDef",
     {
         "virtualRouter": VirtualRouterDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListenerTypeDef = TypedDict(
     "_RequiredListenerTypeDef",
     {
         "portMapping": PortMappingTypeDef,
@@ -2672,39 +2672,39 @@
     total=False,
 )
 
 CreateVirtualServiceOutputTypeDef = TypedDict(
     "CreateVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualServiceOutputTypeDef = TypedDict(
     "DeleteVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualServiceOutputTypeDef = TypedDict(
     "DescribeVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualServiceOutputTypeDef = TypedDict(
     "UpdateVirtualServiceOutputTypeDef",
     {
         "virtualService": VirtualServiceDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GatewayRouteSpecTypeDef = TypedDict(
     "GatewayRouteSpecTypeDef",
     {
         "grpcRoute": GrpcGatewayRouteTypeDef,
@@ -2908,71 +2908,71 @@
 ):
     pass
 
 CreateGatewayRouteOutputTypeDef = TypedDict(
     "CreateGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGatewayRouteOutputTypeDef = TypedDict(
     "DeleteGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGatewayRouteOutputTypeDef = TypedDict(
     "DescribeGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGatewayRouteOutputTypeDef = TypedDict(
     "UpdateGatewayRouteOutputTypeDef",
     {
         "gatewayRoute": GatewayRouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRouteOutputTypeDef = TypedDict(
     "CreateRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRouteOutputTypeDef = TypedDict(
     "DeleteRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRouteOutputTypeDef = TypedDict(
     "DescribeRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRouteOutputTypeDef = TypedDict(
     "UpdateRouteOutputTypeDef",
     {
         "route": RouteDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualNodeSpecTypeDef = TypedDict(
     "VirtualNodeSpecTypeDef",
     {
         "backendDefaults": BackendDefaultsTypeDef,
@@ -3098,66 +3098,66 @@
     },
 )
 
 CreateVirtualGatewayOutputTypeDef = TypedDict(
     "CreateVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualGatewayOutputTypeDef = TypedDict(
     "DeleteVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualGatewayOutputTypeDef = TypedDict(
     "DescribeVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualGatewayOutputTypeDef = TypedDict(
     "UpdateVirtualGatewayOutputTypeDef",
     {
         "virtualGateway": VirtualGatewayDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVirtualNodeOutputTypeDef = TypedDict(
     "CreateVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVirtualNodeOutputTypeDef = TypedDict(
     "DeleteVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVirtualNodeOutputTypeDef = TypedDict(
     "DescribeVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVirtualNodeOutputTypeDef = TypedDict(
     "UpdateVirtualNodeOutputTypeDef",
     {
         "virtualNode": VirtualNodeDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/PKG-INFO` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appmesh
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppMesh 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppMesh 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appmesh"></a>
 
 # types-aiobotocore-appmesh
 
 [![PyPI - types-aiobotocore-appmesh](https://img.shields.io/pypi/v/types-aiobotocore-appmesh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appmesh)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appmesh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appmesh)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appmesh?color=blue)](https://pypistats.org/packages/types-aiobotocore-appmesh)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppMesh 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
+[aiobotocore.AppMesh 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appmesh.html#AppMesh)
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
 [types-aiobotocore-appmesh docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appmesh/).
 
 See how it helps to find and fix potential bugs:
 
@@ -372,15 +372,14 @@
 
 ```python
 from types_aiobotocore_appmesh.type_defs import (
     AwsCloudMapInstanceAttributeTypeDef,
     ListenerTlsFileCertificateTypeDef,
     ListenerTlsSdsCertificateTypeDef,
     TagRefTypeDef,
-    ResponseMetadataTypeDef,
     DeleteGatewayRouteInputRequestTypeDef,
     DeleteMeshInputRequestTypeDef,
     DeleteRouteInputRequestTypeDef,
     DeleteVirtualGatewayInputRequestTypeDef,
     DeleteVirtualNodeInputRequestTypeDef,
     DeleteVirtualRouterInputRequestTypeDef,
     DeleteVirtualServiceInputRequestTypeDef,
@@ -404,35 +403,44 @@
     WeightedTargetTypeDef,
     HealthCheckPolicyTypeDef,
     HttpPathMatchTypeDef,
     HttpGatewayRoutePathRewriteTypeDef,
     HttpGatewayRoutePrefixRewriteTypeDef,
     QueryParameterMatchTypeDef,
     JsonFormatRefTypeDef,
-    PaginatorConfigTypeDef,
+    ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
     ListGatewayRoutesInputRequestTypeDef,
+    ListMeshesInputListMeshesPaginateTypeDef,
     ListMeshesInputRequestTypeDef,
     MeshRefTypeDef,
+    ListRoutesInputListRoutesPaginateTypeDef,
     ListRoutesInputRequestTypeDef,
     RouteRefTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
     ListVirtualGatewaysInputRequestTypeDef,
     VirtualGatewayRefTypeDef,
+    ListVirtualNodesInputListVirtualNodesPaginateTypeDef,
     ListVirtualNodesInputRequestTypeDef,
     VirtualNodeRefTypeDef,
+    ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
     ListVirtualRoutersInputRequestTypeDef,
     VirtualRouterRefTypeDef,
+    ListVirtualServicesInputListVirtualServicesPaginateTypeDef,
     ListVirtualServicesInputRequestTypeDef,
     VirtualServiceRefTypeDef,
     ListenerTlsAcmCertificateTypeDef,
     TlsValidationContextFileTrustTypeDef,
     TlsValidationContextSdsTrustTypeDef,
     PortMappingTypeDef,
     MeshStatusTypeDef,
     MeshServiceDiscoveryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RouteStatusTypeDef,
     SubjectAlternativeNameMatchersTypeDef,
     TcpRouteMatchTypeDef,
     TlsValidationContextAcmTrustTypeDef,
     UntagResourceInputRequestTypeDef,
     VirtualGatewayListenerTlsFileCertificateTypeDef,
     VirtualGatewayListenerTlsSdsCertificateTypeDef,
@@ -453,16 +461,16 @@
     VirtualNodeStatusTypeDef,
     VirtualNodeServiceProviderTypeDef,
     VirtualRouterStatusTypeDef,
     VirtualRouterServiceProviderTypeDef,
     VirtualServiceStatusTypeDef,
     AwsCloudMapServiceDiscoveryTypeDef,
     ClientTlsCertificateTypeDef,
-    TagResourceInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
+    TagResourceInputRequestTypeDef,
     GrpcRetryPolicyTypeDef,
     GrpcTimeoutTypeDef,
     HttpRetryPolicyTypeDef,
     HttpTimeoutTypeDef,
     OutlierDetectionTypeDef,
     TcpTimeoutTypeDef,
     GrpcGatewayRouteRewriteTypeDef,
@@ -473,22 +481,14 @@
     HeaderMatchMethodTypeDef,
     GrpcRouteActionTypeDef,
     HttpRouteActionTypeDef,
     TcpRouteActionTypeDef,
     HttpGatewayRouteRewriteTypeDef,
     HttpQueryParameterTypeDef,
     LoggingFormatTypeDef,
-    ListGatewayRoutesInputListGatewayRoutesPaginateTypeDef,
-    ListMeshesInputListMeshesPaginateTypeDef,
-    ListRoutesInputListRoutesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    ListVirtualGatewaysInputListVirtualGatewaysPaginateTypeDef,
-    ListVirtualNodesInputListVirtualNodesPaginateTypeDef,
-    ListVirtualRoutersInputListVirtualRoutersPaginateTypeDef,
-    ListVirtualServicesInputListVirtualServicesPaginateTypeDef,
     ListMeshesOutputTypeDef,
     ListRoutesOutputTypeDef,
     ListVirtualGatewaysOutputTypeDef,
     ListVirtualNodesOutputTypeDef,
     ListVirtualRoutersOutputTypeDef,
     ListVirtualServicesOutputTypeDef,
     ListenerTlsCertificateTypeDef,
@@ -608,43 +608,43 @@
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

### Comparing `types-aiobotocore-appmesh-2.5.0.post1/types_aiobotocore_appmesh.egg-info/SOURCES.txt` & `types-aiobotocore-appmesh-2.5.1/types_aiobotocore_appmesh.egg-info/SOURCES.txt`

 * *Files identical despite different names*

