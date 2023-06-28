# Comparing `tmp/types-aiobotocore-directconnect-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-directconnect-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-directconnect-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-directconnect-2.5.1.tar", last modified: Wed Jun 28 01:43:22 2023, max compression
```

## Comparing `types-aiobotocore-directconnect-2.5.0.post1.tar` & `types-aiobotocore-directconnect-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.799123 types-aiobotocore-directconnect-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20624 2023-03-11 12:26:29.799123 types-aiobotocore-directconnect-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19029 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:29.799123 types-aiobotocore-directconnect-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.791123 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/
--rw-r--r--   0 runner    (1001) docker     (123)     1511 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    49897 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    49822 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10614 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10612 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5483 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5477 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    54953 2023-03-11 12:12:28.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    54906 2023-03-11 12:12:28.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:27.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.799123 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20624 2023-03-11 12:26:29.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:26:29.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:29.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:29.000000 types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.666124 types-aiobotocore-directconnect-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:05.000000 types-aiobotocore-directconnect-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20622 2023-06-28 01:43:22.666124 types-aiobotocore-directconnect-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19033 2023-06-28 01:29:05.000000 types-aiobotocore-directconnect-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:22.666124 types-aiobotocore-directconnect-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:29:05.000000 types-aiobotocore-directconnect-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.666124 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/
+-rw-r--r--   0 runner    (1001) docker     (123)     1511 2023-06-28 01:29:06.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-06-28 01:29:05.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:29:06.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49897 2023-06-28 01:29:07.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49822 2023-06-28 01:29:06.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10823 2023-06-28 01:29:07.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10821 2023-06-28 01:29:07.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5369 2023-06-28 01:29:07.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5364 2023-06-28 01:29:07.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:06.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    55049 2023-06-28 01:29:08.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55002 2023-06-28 01:29:07.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:05.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.666124 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20622 2023-06-28 01:43:22.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:22.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:22.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:22.000000 types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/LICENSE` & `types-aiobotocore-directconnect-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/PKG-INFO` & `types-aiobotocore-directconnect-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-directconnect
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DirectConnect 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DirectConnect 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-directconnect"></a>
 
 # types-aiobotocore-directconnect
 
 [![PyPI - types-aiobotocore-directconnect](https://img.shields.io/pypi/v/types-aiobotocore-directconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-directconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-directconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-directconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-directconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-directconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DirectConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
+[aiobotocore.DirectConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
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
 [types-aiobotocore-directconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -345,85 +345,88 @@
 
 `types_aiobotocore_directconnect.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_directconnect.type_defs import (
     RouteFilterPrefixTypeDef,
-    ResponseMetadataTypeDef,
     AllocateConnectionOnInterconnectRequestRequestTypeDef,
     TagTypeDef,
     AssociateConnectionWithLagRequestRequestTypeDef,
     AssociateHostedConnectionRequestRequestTypeDef,
     AssociateMacSecKeyRequestRequestTypeDef,
     MacSecKeyTypeDef,
     AssociateVirtualInterfaceRequestRequestTypeDef,
     AssociatedGatewayTypeDef,
     BGPPeerTypeDef,
     ConfirmConnectionRequestRequestTypeDef,
+    ConfirmConnectionResponseTypeDef,
     ConfirmCustomerAgreementRequestRequestTypeDef,
+    ConfirmCustomerAgreementResponseTypeDef,
     ConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
+    ConfirmPrivateVirtualInterfaceResponseTypeDef,
     ConfirmPublicVirtualInterfaceRequestRequestTypeDef,
+    ConfirmPublicVirtualInterfaceResponseTypeDef,
     ConfirmTransitVirtualInterfaceRequestRequestTypeDef,
+    ConfirmTransitVirtualInterfaceResponseTypeDef,
     NewBGPPeerTypeDef,
     CreateDirectConnectGatewayRequestRequestTypeDef,
     DirectConnectGatewayTypeDef,
     CustomerAgreementTypeDef,
     DeleteBGPPeerRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
     DeleteDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     DeleteDirectConnectGatewayAssociationRequestRequestTypeDef,
     DeleteDirectConnectGatewayRequestRequestTypeDef,
     DeleteInterconnectRequestRequestTypeDef,
+    DeleteInterconnectResponseTypeDef,
     DeleteLagRequestRequestTypeDef,
     DeleteVirtualInterfaceRequestRequestTypeDef,
+    DeleteVirtualInterfaceResponseTypeDef,
     DescribeConnectionLoaRequestRequestTypeDef,
     LoaTypeDef,
     DescribeConnectionsOnInterconnectRequestRequestTypeDef,
     DescribeConnectionsRequestRequestTypeDef,
     DescribeDirectConnectGatewayAssociationProposalsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef,
     DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef,
+    DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef,
     DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef,
     DirectConnectGatewayAttachmentTypeDef,
+    DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef,
     DescribeDirectConnectGatewaysRequestRequestTypeDef,
     DescribeHostedConnectionsRequestRequestTypeDef,
     DescribeInterconnectLoaRequestRequestTypeDef,
     DescribeInterconnectsRequestRequestTypeDef,
     DescribeLagsRequestRequestTypeDef,
     DescribeLoaRequestRequestTypeDef,
     DescribeRouterConfigurationRequestRequestTypeDef,
     RouterTypeTypeDef,
     DescribeTagsRequestRequestTypeDef,
     DescribeVirtualInterfacesRequestRequestTypeDef,
     DisassociateConnectionFromLagRequestRequestTypeDef,
     DisassociateMacSecKeyRequestRequestTypeDef,
     ListVirtualInterfaceTestHistoryRequestRequestTypeDef,
     VirtualInterfaceTestHistoryTypeDef,
+    LoaResponseMetadataTypeDef,
     LocationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartBgpFailoverTestRequestRequestTypeDef,
     StopBgpFailoverTestRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateConnectionRequestRequestTypeDef,
     UpdateDirectConnectGatewayRequestRequestTypeDef,
     UpdateLagRequestRequestTypeDef,
     UpdateVirtualInterfaceAttributesRequestRequestTypeDef,
     VirtualGatewayTypeDef,
     AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     CreateDirectConnectGatewayAssociationRequestRequestTypeDef,
     UpdateDirectConnectGatewayAssociationRequestRequestTypeDef,
-    ConfirmConnectionResponseTypeDef,
-    ConfirmCustomerAgreementResponseTypeDef,
-    ConfirmPrivateVirtualInterfaceResponseTypeDef,
-    ConfirmPublicVirtualInterfaceResponseTypeDef,
-    ConfirmTransitVirtualInterfaceResponseTypeDef,
-    DeleteInterconnectResponseTypeDef,
-    DeleteVirtualInterfaceResponseTypeDef,
-    LoaResponseMetadataTypeDef,
     AllocateHostedConnectionRequestRequestTypeDef,
     CreateConnectionRequestRequestTypeDef,
     CreateInterconnectRequestRequestTypeDef,
     CreateLagRequestRequestTypeDef,
     InterconnectResponseMetadataTypeDef,
     InterconnectTypeDef,
     NewPrivateVirtualInterfaceAllocationTypeDef,
@@ -446,17 +449,14 @@
     CreateDirectConnectGatewayResultTypeDef,
     DeleteDirectConnectGatewayResultTypeDef,
     DescribeDirectConnectGatewaysResultTypeDef,
     UpdateDirectConnectGatewayResponseTypeDef,
     DescribeCustomerMetadataResponseTypeDef,
     DescribeConnectionLoaResponseTypeDef,
     DescribeInterconnectLoaResponseTypeDef,
-    DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef,
-    DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef,
-    DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef,
     DescribeDirectConnectGatewayAttachmentsResultTypeDef,
     DescribeRouterConfigurationResponseTypeDef,
     ListVirtualInterfaceTestHistoryResponseTypeDef,
     StartBgpFailoverTestResponseTypeDef,
     StopBgpFailoverTestResponseTypeDef,
     LocationsTypeDef,
     VirtualGatewaysTypeDef,
@@ -495,43 +495,43 @@
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/README.md` & `types-aiobotocore-directconnect-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-directconnect"></a>
 
 # types-aiobotocore-directconnect
 
 [![PyPI - types-aiobotocore-directconnect](https://img.shields.io/pypi/v/types-aiobotocore-directconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-directconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-directconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-directconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-directconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-directconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DirectConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
+[aiobotocore.DirectConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
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
 [types-aiobotocore-directconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,85 +312,88 @@
 
 `types_aiobotocore_directconnect.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_directconnect.type_defs import (
     RouteFilterPrefixTypeDef,
-    ResponseMetadataTypeDef,
     AllocateConnectionOnInterconnectRequestRequestTypeDef,
     TagTypeDef,
     AssociateConnectionWithLagRequestRequestTypeDef,
     AssociateHostedConnectionRequestRequestTypeDef,
     AssociateMacSecKeyRequestRequestTypeDef,
     MacSecKeyTypeDef,
     AssociateVirtualInterfaceRequestRequestTypeDef,
     AssociatedGatewayTypeDef,
     BGPPeerTypeDef,
     ConfirmConnectionRequestRequestTypeDef,
+    ConfirmConnectionResponseTypeDef,
     ConfirmCustomerAgreementRequestRequestTypeDef,
+    ConfirmCustomerAgreementResponseTypeDef,
     ConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
+    ConfirmPrivateVirtualInterfaceResponseTypeDef,
     ConfirmPublicVirtualInterfaceRequestRequestTypeDef,
+    ConfirmPublicVirtualInterfaceResponseTypeDef,
     ConfirmTransitVirtualInterfaceRequestRequestTypeDef,
+    ConfirmTransitVirtualInterfaceResponseTypeDef,
     NewBGPPeerTypeDef,
     CreateDirectConnectGatewayRequestRequestTypeDef,
     DirectConnectGatewayTypeDef,
     CustomerAgreementTypeDef,
     DeleteBGPPeerRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
     DeleteDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     DeleteDirectConnectGatewayAssociationRequestRequestTypeDef,
     DeleteDirectConnectGatewayRequestRequestTypeDef,
     DeleteInterconnectRequestRequestTypeDef,
+    DeleteInterconnectResponseTypeDef,
     DeleteLagRequestRequestTypeDef,
     DeleteVirtualInterfaceRequestRequestTypeDef,
+    DeleteVirtualInterfaceResponseTypeDef,
     DescribeConnectionLoaRequestRequestTypeDef,
     LoaTypeDef,
     DescribeConnectionsOnInterconnectRequestRequestTypeDef,
     DescribeConnectionsRequestRequestTypeDef,
     DescribeDirectConnectGatewayAssociationProposalsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef,
     DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef,
+    DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef,
     DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef,
     DirectConnectGatewayAttachmentTypeDef,
+    DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef,
     DescribeDirectConnectGatewaysRequestRequestTypeDef,
     DescribeHostedConnectionsRequestRequestTypeDef,
     DescribeInterconnectLoaRequestRequestTypeDef,
     DescribeInterconnectsRequestRequestTypeDef,
     DescribeLagsRequestRequestTypeDef,
     DescribeLoaRequestRequestTypeDef,
     DescribeRouterConfigurationRequestRequestTypeDef,
     RouterTypeTypeDef,
     DescribeTagsRequestRequestTypeDef,
     DescribeVirtualInterfacesRequestRequestTypeDef,
     DisassociateConnectionFromLagRequestRequestTypeDef,
     DisassociateMacSecKeyRequestRequestTypeDef,
     ListVirtualInterfaceTestHistoryRequestRequestTypeDef,
     VirtualInterfaceTestHistoryTypeDef,
+    LoaResponseMetadataTypeDef,
     LocationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartBgpFailoverTestRequestRequestTypeDef,
     StopBgpFailoverTestRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateConnectionRequestRequestTypeDef,
     UpdateDirectConnectGatewayRequestRequestTypeDef,
     UpdateLagRequestRequestTypeDef,
     UpdateVirtualInterfaceAttributesRequestRequestTypeDef,
     VirtualGatewayTypeDef,
     AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     CreateDirectConnectGatewayAssociationRequestRequestTypeDef,
     UpdateDirectConnectGatewayAssociationRequestRequestTypeDef,
-    ConfirmConnectionResponseTypeDef,
-    ConfirmCustomerAgreementResponseTypeDef,
-    ConfirmPrivateVirtualInterfaceResponseTypeDef,
-    ConfirmPublicVirtualInterfaceResponseTypeDef,
-    ConfirmTransitVirtualInterfaceResponseTypeDef,
-    DeleteInterconnectResponseTypeDef,
-    DeleteVirtualInterfaceResponseTypeDef,
-    LoaResponseMetadataTypeDef,
     AllocateHostedConnectionRequestRequestTypeDef,
     CreateConnectionRequestRequestTypeDef,
     CreateInterconnectRequestRequestTypeDef,
     CreateLagRequestRequestTypeDef,
     InterconnectResponseMetadataTypeDef,
     InterconnectTypeDef,
     NewPrivateVirtualInterfaceAllocationTypeDef,
@@ -413,17 +416,14 @@
     CreateDirectConnectGatewayResultTypeDef,
     DeleteDirectConnectGatewayResultTypeDef,
     DescribeDirectConnectGatewaysResultTypeDef,
     UpdateDirectConnectGatewayResponseTypeDef,
     DescribeCustomerMetadataResponseTypeDef,
     DescribeConnectionLoaResponseTypeDef,
     DescribeInterconnectLoaResponseTypeDef,
-    DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef,
-    DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef,
-    DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef,
     DescribeDirectConnectGatewayAttachmentsResultTypeDef,
     DescribeRouterConfigurationResponseTypeDef,
     ListVirtualInterfaceTestHistoryResponseTypeDef,
     StartBgpFailoverTestResponseTypeDef,
     StopBgpFailoverTestResponseTypeDef,
     LocationsTypeDef,
     VirtualGatewaysTypeDef,
@@ -462,43 +462,43 @@
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/setup.py` & `types-aiobotocore-directconnect-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-directconnect.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-directconnect",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_directconnect"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DirectConnect 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DirectConnect 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/"
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/__init__.py` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/__init__.pyi` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/__main__.py` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DirectConnect 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DirectConnect 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect\nOther"
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/client.py` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/client.pyi` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/literals.py` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -157,14 +157,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -261,14 +263,15 @@
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
@@ -304,14 +307,15 @@
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
@@ -330,16 +334,19 @@
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
@@ -423,15 +430,17 @@
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/literals.pyi` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -155,14 +155,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -259,14 +261,15 @@
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
@@ -302,14 +305,15 @@
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
@@ -328,16 +332,19 @@
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
@@ -421,15 +428,17 @@
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/paginator.py` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: DirectConnectClient
 
         describe_direct_connect_gateway_associations_paginator: DescribeDirectConnectGatewayAssociationsPaginator = client.get_paginator("describe_direct_connect_gateway_associations")
         describe_direct_connect_gateway_attachments_paginator: DescribeDirectConnectGatewayAttachmentsPaginator = client.get_paginator("describe_direct_connect_gateway_attachments")
         describe_direct_connect_gateways_paginator: DescribeDirectConnectGatewaysPaginator = client.get_paginator("describe_direct_connect_gateways")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeDirectConnectGatewayAssociationsResultTypeDef,
     DescribeDirectConnectGatewayAttachmentsResultTypeDef,
     DescribeDirectConnectGatewaysResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeDirectConnectGatewayAssociationsPaginator",
     "DescribeDirectConnectGatewayAttachmentsPaginator",
     "DescribeDirectConnectGatewaysPaginator",
 )
 
 
@@ -69,15 +62,15 @@
     def paginate(
         self,
         *,
         associationId: str = ...,
         associatedGatewayId: str = ...,
         directConnectGatewayId: str = ...,
         virtualGatewayId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectConnectGatewayAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGatewayAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayassociationspaginator)
         """
 
 
@@ -88,28 +81,28 @@
     """
 
     def paginate(
         self,
         *,
         directConnectGatewayId: str = ...,
         virtualInterfaceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectConnectGatewayAttachmentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGatewayAttachments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayattachmentspaginator)
         """
 
 
 class DescribeDirectConnectGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayspaginator)
     """
 
     def paginate(
-        self, *, directConnectGatewayId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, directConnectGatewayId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectConnectGatewaysResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayspaginator)
         """
```

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/paginator.pyi` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: DirectConnectClient
 
         describe_direct_connect_gateway_associations_paginator: DescribeDirectConnectGatewayAssociationsPaginator = client.get_paginator("describe_direct_connect_gateway_associations")
         describe_direct_connect_gateway_attachments_paginator: DescribeDirectConnectGatewayAttachmentsPaginator = client.get_paginator("describe_direct_connect_gateway_attachments")
         describe_direct_connect_gateways_paginator: DescribeDirectConnectGatewaysPaginator = client.get_paginator("describe_direct_connect_gateways")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeDirectConnectGatewayAssociationsResultTypeDef,
     DescribeDirectConnectGatewayAttachmentsResultTypeDef,
     DescribeDirectConnectGatewaysResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeDirectConnectGatewayAssociationsPaginator",
     "DescribeDirectConnectGatewayAttachmentsPaginator",
     "DescribeDirectConnectGatewaysPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -65,15 +59,15 @@
     def paginate(
         self,
         *,
         associationId: str = ...,
         associatedGatewayId: str = ...,
         directConnectGatewayId: str = ...,
         virtualGatewayId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectConnectGatewayAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGatewayAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayassociationspaginator)
         """
 
 class DescribeDirectConnectGatewayAttachmentsPaginator(AioPaginator):
@@ -83,27 +77,27 @@
     """
 
     def paginate(
         self,
         *,
         directConnectGatewayId: str = ...,
         virtualInterfaceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectConnectGatewayAttachmentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGatewayAttachments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayattachmentspaginator)
         """
 
 class DescribeDirectConnectGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayspaginator)
     """
 
     def paginate(
-        self, *, directConnectGatewayId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, directConnectGatewayId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectConnectGatewaysResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect.Paginator.DescribeDirectConnectGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/paginators/#describedirectconnectgatewayspaginator)
         """
```

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/type_defs.py` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -38,88 +38,90 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "RouteFilterPrefixTypeDef",
-    "ResponseMetadataTypeDef",
     "AllocateConnectionOnInterconnectRequestRequestTypeDef",
     "TagTypeDef",
     "AssociateConnectionWithLagRequestRequestTypeDef",
     "AssociateHostedConnectionRequestRequestTypeDef",
     "AssociateMacSecKeyRequestRequestTypeDef",
     "MacSecKeyTypeDef",
     "AssociateVirtualInterfaceRequestRequestTypeDef",
     "AssociatedGatewayTypeDef",
     "BGPPeerTypeDef",
     "ConfirmConnectionRequestRequestTypeDef",
+    "ConfirmConnectionResponseTypeDef",
     "ConfirmCustomerAgreementRequestRequestTypeDef",
+    "ConfirmCustomerAgreementResponseTypeDef",
     "ConfirmPrivateVirtualInterfaceRequestRequestTypeDef",
+    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
     "ConfirmPublicVirtualInterfaceRequestRequestTypeDef",
+    "ConfirmPublicVirtualInterfaceResponseTypeDef",
     "ConfirmTransitVirtualInterfaceRequestRequestTypeDef",
+    "ConfirmTransitVirtualInterfaceResponseTypeDef",
     "NewBGPPeerTypeDef",
     "CreateDirectConnectGatewayRequestRequestTypeDef",
     "DirectConnectGatewayTypeDef",
     "CustomerAgreementTypeDef",
     "DeleteBGPPeerRequestRequestTypeDef",
     "DeleteConnectionRequestRequestTypeDef",
     "DeleteDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     "DeleteDirectConnectGatewayAssociationRequestRequestTypeDef",
     "DeleteDirectConnectGatewayRequestRequestTypeDef",
     "DeleteInterconnectRequestRequestTypeDef",
+    "DeleteInterconnectResponseTypeDef",
     "DeleteLagRequestRequestTypeDef",
     "DeleteVirtualInterfaceRequestRequestTypeDef",
+    "DeleteVirtualInterfaceResponseTypeDef",
     "DescribeConnectionLoaRequestRequestTypeDef",
     "LoaTypeDef",
     "DescribeConnectionsOnInterconnectRequestRequestTypeDef",
     "DescribeConnectionsRequestRequestTypeDef",
     "DescribeDirectConnectGatewayAssociationProposalsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
     "DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef",
+    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
     "DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef",
     "DirectConnectGatewayAttachmentTypeDef",
+    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
     "DescribeDirectConnectGatewaysRequestRequestTypeDef",
     "DescribeHostedConnectionsRequestRequestTypeDef",
     "DescribeInterconnectLoaRequestRequestTypeDef",
     "DescribeInterconnectsRequestRequestTypeDef",
     "DescribeLagsRequestRequestTypeDef",
     "DescribeLoaRequestRequestTypeDef",
     "DescribeRouterConfigurationRequestRequestTypeDef",
     "RouterTypeTypeDef",
     "DescribeTagsRequestRequestTypeDef",
     "DescribeVirtualInterfacesRequestRequestTypeDef",
     "DisassociateConnectionFromLagRequestRequestTypeDef",
     "DisassociateMacSecKeyRequestRequestTypeDef",
     "ListVirtualInterfaceTestHistoryRequestRequestTypeDef",
     "VirtualInterfaceTestHistoryTypeDef",
+    "LoaResponseMetadataTypeDef",
     "LocationTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartBgpFailoverTestRequestRequestTypeDef",
     "StopBgpFailoverTestRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateConnectionRequestRequestTypeDef",
     "UpdateDirectConnectGatewayRequestRequestTypeDef",
     "UpdateLagRequestRequestTypeDef",
     "UpdateVirtualInterfaceAttributesRequestRequestTypeDef",
     "VirtualGatewayTypeDef",
     "AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     "CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     "CreateDirectConnectGatewayAssociationRequestRequestTypeDef",
     "UpdateDirectConnectGatewayAssociationRequestRequestTypeDef",
-    "ConfirmConnectionResponseTypeDef",
-    "ConfirmCustomerAgreementResponseTypeDef",
-    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
-    "ConfirmPublicVirtualInterfaceResponseTypeDef",
-    "ConfirmTransitVirtualInterfaceResponseTypeDef",
-    "DeleteInterconnectResponseTypeDef",
-    "DeleteVirtualInterfaceResponseTypeDef",
-    "LoaResponseMetadataTypeDef",
     "AllocateHostedConnectionRequestRequestTypeDef",
     "CreateConnectionRequestRequestTypeDef",
     "CreateInterconnectRequestRequestTypeDef",
     "CreateLagRequestRequestTypeDef",
     "InterconnectResponseMetadataTypeDef",
     "InterconnectTypeDef",
     "NewPrivateVirtualInterfaceAllocationTypeDef",
@@ -142,17 +144,14 @@
     "CreateDirectConnectGatewayResultTypeDef",
     "DeleteDirectConnectGatewayResultTypeDef",
     "DescribeDirectConnectGatewaysResultTypeDef",
     "UpdateDirectConnectGatewayResponseTypeDef",
     "DescribeCustomerMetadataResponseTypeDef",
     "DescribeConnectionLoaResponseTypeDef",
     "DescribeInterconnectLoaResponseTypeDef",
-    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
-    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
-    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
     "DescribeDirectConnectGatewayAttachmentsResultTypeDef",
     "DescribeRouterConfigurationResponseTypeDef",
     "ListVirtualInterfaceTestHistoryResponseTypeDef",
     "StartBgpFailoverTestResponseTypeDef",
     "StopBgpFailoverTestResponseTypeDef",
     "LocationsTypeDef",
     "VirtualGatewaysTypeDef",
@@ -187,25 +186,14 @@
     "RouteFilterPrefixTypeDef",
     {
         "cidr": str,
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
 AllocateConnectionOnInterconnectRequestRequestTypeDef = TypedDict(
     "AllocateConnectionOnInterconnectRequestRequestTypeDef",
     {
         "bandwidth": str,
         "connectionName": str,
         "ownerAccount": str,
         "interconnectId": str,
@@ -223,19 +211,17 @@
     "_OptionalTagTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
-
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
-
 AssociateConnectionWithLagRequestRequestTypeDef = TypedDict(
     "AssociateConnectionWithLagRequestRequestTypeDef",
     {
         "connectionId": str,
         "lagId": str,
     },
 )
@@ -260,22 +246,20 @@
         "secretARN": str,
         "ckn": str,
         "cak": str,
     },
     total=False,
 )
 
-
 class AssociateMacSecKeyRequestRequestTypeDef(
     _RequiredAssociateMacSecKeyRequestRequestTypeDef,
     _OptionalAssociateMacSecKeyRequestRequestTypeDef,
 ):
     pass
 
-
 MacSecKeyTypeDef = TypedDict(
     "MacSecKeyTypeDef",
     {
         "secretARN": str,
         "ckn": str,
         "state": str,
         "startOn": str,
@@ -322,22 +306,38 @@
 ConfirmConnectionRequestRequestTypeDef = TypedDict(
     "ConfirmConnectionRequestRequestTypeDef",
     {
         "connectionId": str,
     },
 )
 
+ConfirmConnectionResponseTypeDef = TypedDict(
+    "ConfirmConnectionResponseTypeDef",
+    {
+        "connectionState": ConnectionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfirmCustomerAgreementRequestRequestTypeDef = TypedDict(
     "ConfirmCustomerAgreementRequestRequestTypeDef",
     {
         "agreementName": str,
     },
     total=False,
 )
 
+ConfirmCustomerAgreementResponseTypeDef = TypedDict(
+    "ConfirmCustomerAgreementResponseTypeDef",
+    {
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredConfirmPrivateVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "_RequiredConfirmPrivateVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalConfirmPrivateVirtualInterfaceRequestRequestTypeDef = TypedDict(
@@ -345,37 +345,59 @@
     {
         "virtualGatewayId": str,
         "directConnectGatewayId": str,
     },
     total=False,
 )
 
-
 class ConfirmPrivateVirtualInterfaceRequestRequestTypeDef(
     _RequiredConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
     _OptionalConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
 ):
     pass
 
+ConfirmPrivateVirtualInterfaceResponseTypeDef = TypedDict(
+    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ConfirmPublicVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "ConfirmPublicVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 
+ConfirmPublicVirtualInterfaceResponseTypeDef = TypedDict(
+    "ConfirmPublicVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfirmTransitVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "ConfirmTransitVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
         "directConnectGatewayId": str,
     },
 )
 
+ConfirmTransitVirtualInterfaceResponseTypeDef = TypedDict(
+    "ConfirmTransitVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NewBGPPeerTypeDef = TypedDict(
     "NewBGPPeerTypeDef",
     {
         "asn": int,
         "authKey": str,
         "addressFamily": AddressFamilyType,
         "amazonAddress": str,
@@ -394,22 +416,20 @@
     "_OptionalCreateDirectConnectGatewayRequestRequestTypeDef",
     {
         "amazonSideAsn": int,
     },
     total=False,
 )
 
-
 class CreateDirectConnectGatewayRequestRequestTypeDef(
     _RequiredCreateDirectConnectGatewayRequestRequestTypeDef,
     _OptionalCreateDirectConnectGatewayRequestRequestTypeDef,
 ):
     pass
 
-
 DirectConnectGatewayTypeDef = TypedDict(
     "DirectConnectGatewayTypeDef",
     {
         "directConnectGatewayId": str,
         "directConnectGatewayName": str,
         "amazonSideAsn": int,
         "ownerAccount": str,
@@ -473,28 +493,44 @@
 DeleteInterconnectRequestRequestTypeDef = TypedDict(
     "DeleteInterconnectRequestRequestTypeDef",
     {
         "interconnectId": str,
     },
 )
 
+DeleteInterconnectResponseTypeDef = TypedDict(
+    "DeleteInterconnectResponseTypeDef",
+    {
+        "interconnectState": InterconnectStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLagRequestRequestTypeDef = TypedDict(
     "DeleteLagRequestRequestTypeDef",
     {
         "lagId": str,
     },
 )
 
 DeleteVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "DeleteVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 
+DeleteVirtualInterfaceResponseTypeDef = TypedDict(
+    "DeleteVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeConnectionLoaRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConnectionLoaRequestRequestTypeDef",
     {
         "connectionId": str,
     },
 )
 _OptionalDescribeConnectionLoaRequestRequestTypeDef = TypedDict(
@@ -502,22 +538,20 @@
     {
         "providerName": str,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
 )
 
-
 class DescribeConnectionLoaRequestRequestTypeDef(
     _RequiredDescribeConnectionLoaRequestRequestTypeDef,
     _OptionalDescribeConnectionLoaRequestRequestTypeDef,
 ):
     pass
 
-
 LoaTypeDef = TypedDict(
     "LoaTypeDef",
     {
         "loaContent": bytes,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
@@ -546,20 +580,22 @@
         "associatedGatewayId": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef = TypedDict(
+    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "associationId": str,
+        "associatedGatewayId": str,
+        "directConnectGatewayId": str,
+        "virtualGatewayId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef",
     {
@@ -569,14 +605,24 @@
         "maxResults": int,
         "nextToken": str,
         "virtualGatewayId": str,
     },
     total=False,
 )
 
+DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef = TypedDict(
+    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
+    {
+        "directConnectGatewayId": str,
+        "virtualInterfaceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "virtualInterfaceId": str,
         "maxResults": int,
         "nextToken": str,
@@ -594,14 +640,23 @@
         "attachmentState": DirectConnectGatewayAttachmentStateType,
         "attachmentType": DirectConnectGatewayAttachmentTypeType,
         "stateChangeError": str,
     },
     total=False,
 )
 
+DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef = TypedDict(
+    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
+    {
+        "directConnectGatewayId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDirectConnectGatewaysRequestRequestTypeDef = TypedDict(
     "DescribeDirectConnectGatewaysRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "maxResults": int,
         "nextToken": str,
     },
@@ -626,22 +681,20 @@
     {
         "providerName": str,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
 )
 
-
 class DescribeInterconnectLoaRequestRequestTypeDef(
     _RequiredDescribeInterconnectLoaRequestRequestTypeDef,
     _OptionalDescribeInterconnectLoaRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeInterconnectsRequestRequestTypeDef = TypedDict(
     "DescribeInterconnectsRequestRequestTypeDef",
     {
         "interconnectId": str,
     },
     total=False,
 )
@@ -665,43 +718,39 @@
     {
         "providerName": str,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
 )
 
-
 class DescribeLoaRequestRequestTypeDef(
     _RequiredDescribeLoaRequestRequestTypeDef, _OptionalDescribeLoaRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredDescribeRouterConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRouterConfigurationRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalDescribeRouterConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeRouterConfigurationRequestRequestTypeDef",
     {
         "routerTypeIdentifier": str,
     },
     total=False,
 )
 
-
 class DescribeRouterConfigurationRequestRequestTypeDef(
     _RequiredDescribeRouterConfigurationRequestRequestTypeDef,
     _OptionalDescribeRouterConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 RouterTypeTypeDef = TypedDict(
     "RouterTypeTypeDef",
     {
         "vendor": str,
         "platform": str,
         "software": str,
         "xsltTemplateName": str,
@@ -767,27 +816,57 @@
         "testDurationInMinutes": int,
         "startTime": datetime,
         "endTime": datetime,
     },
     total=False,
 )
 
+LoaResponseMetadataTypeDef = TypedDict(
+    "LoaResponseMetadataTypeDef",
+    {
+        "loaContent": bytes,
+        "loaContentType": Literal["application/pdf"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LocationTypeDef = TypedDict(
     "LocationTypeDef",
     {
         "locationCode": str,
         "locationName": str,
         "region": str,
         "availablePortSpeeds": List[str],
         "availableProviders": List[str],
         "availableMacSecPortSpeeds": List[str],
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
 _RequiredStartBgpFailoverTestRequestRequestTypeDef = TypedDict(
     "_RequiredStartBgpFailoverTestRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalStartBgpFailoverTestRequestRequestTypeDef = TypedDict(
@@ -795,22 +874,20 @@
     {
         "bgpPeers": Sequence[str],
         "testDurationInMinutes": int,
     },
     total=False,
 )
 
-
 class StartBgpFailoverTestRequestRequestTypeDef(
     _RequiredStartBgpFailoverTestRequestRequestTypeDef,
     _OptionalStartBgpFailoverTestRequestRequestTypeDef,
 ):
     pass
 
-
 StopBgpFailoverTestRequestRequestTypeDef = TypedDict(
     "StopBgpFailoverTestRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 
@@ -833,21 +910,19 @@
     {
         "connectionName": str,
         "encryptionMode": str,
     },
     total=False,
 )
 
-
 class UpdateConnectionRequestRequestTypeDef(
     _RequiredUpdateConnectionRequestRequestTypeDef, _OptionalUpdateConnectionRequestRequestTypeDef
 ):
     pass
 
-
 UpdateDirectConnectGatewayRequestRequestTypeDef = TypedDict(
     "UpdateDirectConnectGatewayRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "newDirectConnectGatewayName": str,
     },
 )
@@ -864,21 +939,19 @@
         "lagName": str,
         "minimumLinks": int,
         "encryptionMode": str,
     },
     total=False,
 )
 
-
 class UpdateLagRequestRequestTypeDef(
     _RequiredUpdateLagRequestRequestTypeDef, _OptionalUpdateLagRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateVirtualInterfaceAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVirtualInterfaceAttributesRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalUpdateVirtualInterfaceAttributesRequestRequestTypeDef = TypedDict(
@@ -887,22 +960,20 @@
         "mtu": int,
         "enableSiteLink": bool,
         "virtualInterfaceName": str,
     },
     total=False,
 )
 
-
 class UpdateVirtualInterfaceAttributesRequestRequestTypeDef(
     _RequiredUpdateVirtualInterfaceAttributesRequestRequestTypeDef,
     _OptionalUpdateVirtualInterfaceAttributesRequestRequestTypeDef,
 ):
     pass
 
-
 VirtualGatewayTypeDef = TypedDict(
     "VirtualGatewayTypeDef",
     {
         "virtualGatewayId": str,
         "virtualGatewayState": str,
     },
     total=False,
@@ -920,22 +991,20 @@
     "_OptionalAcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     {
         "overrideAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
     },
     total=False,
 )
 
-
 class AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef(
     _RequiredAcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     _OptionalAcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "directConnectGatewayOwnerAccount": str,
         "gatewayId": str,
     },
@@ -945,22 +1014,20 @@
     {
         "addAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
         "removeAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
     },
     total=False,
 )
 
-
 class CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef(
     _RequiredCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     _OptionalCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDirectConnectGatewayAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDirectConnectGatewayAssociationRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
     },
 )
 _OptionalCreateDirectConnectGatewayAssociationRequestRequestTypeDef = TypedDict(
@@ -969,97 +1036,30 @@
         "gatewayId": str,
         "addAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
         "virtualGatewayId": str,
     },
     total=False,
 )
 
-
 class CreateDirectConnectGatewayAssociationRequestRequestTypeDef(
     _RequiredCreateDirectConnectGatewayAssociationRequestRequestTypeDef,
     _OptionalCreateDirectConnectGatewayAssociationRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateDirectConnectGatewayAssociationRequestRequestTypeDef = TypedDict(
     "UpdateDirectConnectGatewayAssociationRequestRequestTypeDef",
     {
         "associationId": str,
         "addAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
         "removeAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
     },
     total=False,
 )
 
-ConfirmConnectionResponseTypeDef = TypedDict(
-    "ConfirmConnectionResponseTypeDef",
-    {
-        "connectionState": ConnectionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmCustomerAgreementResponseTypeDef = TypedDict(
-    "ConfirmCustomerAgreementResponseTypeDef",
-    {
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmPrivateVirtualInterfaceResponseTypeDef = TypedDict(
-    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmPublicVirtualInterfaceResponseTypeDef = TypedDict(
-    "ConfirmPublicVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmTransitVirtualInterfaceResponseTypeDef = TypedDict(
-    "ConfirmTransitVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteInterconnectResponseTypeDef = TypedDict(
-    "DeleteInterconnectResponseTypeDef",
-    {
-        "interconnectState": InterconnectStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteVirtualInterfaceResponseTypeDef = TypedDict(
-    "DeleteVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-LoaResponseMetadataTypeDef = TypedDict(
-    "LoaResponseMetadataTypeDef",
-    {
-        "loaContent": bytes,
-        "loaContentType": Literal["application/pdf"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredAllocateHostedConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredAllocateHostedConnectionRequestRequestTypeDef",
     {
         "connectionId": str,
         "ownerAccount": str,
         "bandwidth": str,
         "connectionName": str,
@@ -1070,22 +1070,20 @@
     "_OptionalAllocateHostedConnectionRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class AllocateHostedConnectionRequestRequestTypeDef(
     _RequiredAllocateHostedConnectionRequestRequestTypeDef,
     _OptionalAllocateHostedConnectionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectionRequestRequestTypeDef",
     {
         "location": str,
         "bandwidth": str,
         "connectionName": str,
     },
@@ -1097,21 +1095,19 @@
         "tags": Sequence[TagTypeDef],
         "providerName": str,
         "requestMACSec": bool,
     },
     total=False,
 )
 
-
 class CreateConnectionRequestRequestTypeDef(
     _RequiredCreateConnectionRequestRequestTypeDef, _OptionalCreateConnectionRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateInterconnectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInterconnectRequestRequestTypeDef",
     {
         "interconnectName": str,
         "bandwidth": str,
         "location": str,
     },
@@ -1122,22 +1118,20 @@
         "lagId": str,
         "tags": Sequence[TagTypeDef],
         "providerName": str,
     },
     total=False,
 )
 
-
 class CreateInterconnectRequestRequestTypeDef(
     _RequiredCreateInterconnectRequestRequestTypeDef,
     _OptionalCreateInterconnectRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateLagRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLagRequestRequestTypeDef",
     {
         "numberOfConnections": int,
         "location": str,
         "connectionsBandwidth": str,
         "lagName": str,
@@ -1151,21 +1145,19 @@
         "childConnectionTags": Sequence[TagTypeDef],
         "providerName": str,
         "requestMACSec": bool,
     },
     total=False,
 )
 
-
 class CreateLagRequestRequestTypeDef(
     _RequiredCreateLagRequestRequestTypeDef, _OptionalCreateLagRequestRequestTypeDef
 ):
     pass
 
-
 InterconnectResponseMetadataTypeDef = TypedDict(
     "InterconnectResponseMetadataTypeDef",
     {
         "interconnectId": str,
         "interconnectName": str,
         "interconnectState": InterconnectStateType,
         "region": str,
@@ -1176,15 +1168,15 @@
         "awsDevice": str,
         "jumboFrameCapable": bool,
         "awsDeviceV2": str,
         "awsLogicalDeviceId": str,
         "hasLogicalRedundancy": HasLogicalRedundancyType,
         "tags": List[TagTypeDef],
         "providerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InterconnectTypeDef = TypedDict(
     "InterconnectTypeDef",
     {
         "interconnectId": str,
@@ -1223,22 +1215,20 @@
         "addressFamily": AddressFamilyType,
         "customerAddress": str,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class NewPrivateVirtualInterfaceAllocationTypeDef(
     _RequiredNewPrivateVirtualInterfaceAllocationTypeDef,
     _OptionalNewPrivateVirtualInterfaceAllocationTypeDef,
 ):
     pass
 
-
 _RequiredNewPrivateVirtualInterfaceTypeDef = TypedDict(
     "_RequiredNewPrivateVirtualInterfaceTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
     },
@@ -1255,21 +1245,19 @@
         "directConnectGatewayId": str,
         "tags": Sequence[TagTypeDef],
         "enableSiteLink": bool,
     },
     total=False,
 )
 
-
 class NewPrivateVirtualInterfaceTypeDef(
     _RequiredNewPrivateVirtualInterfaceTypeDef, _OptionalNewPrivateVirtualInterfaceTypeDef
 ):
     pass
 
-
 _RequiredNewPublicVirtualInterfaceAllocationTypeDef = TypedDict(
     "_RequiredNewPublicVirtualInterfaceAllocationTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
     },
@@ -1283,22 +1271,20 @@
         "addressFamily": AddressFamilyType,
         "routeFilterPrefixes": Sequence[RouteFilterPrefixTypeDef],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class NewPublicVirtualInterfaceAllocationTypeDef(
     _RequiredNewPublicVirtualInterfaceAllocationTypeDef,
     _OptionalNewPublicVirtualInterfaceAllocationTypeDef,
 ):
     pass
 
-
 _RequiredNewPublicVirtualInterfaceTypeDef = TypedDict(
     "_RequiredNewPublicVirtualInterfaceTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
     },
@@ -1312,21 +1298,19 @@
         "addressFamily": AddressFamilyType,
         "routeFilterPrefixes": Sequence[RouteFilterPrefixTypeDef],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class NewPublicVirtualInterfaceTypeDef(
     _RequiredNewPublicVirtualInterfaceTypeDef, _OptionalNewPublicVirtualInterfaceTypeDef
 ):
     pass
 
-
 NewTransitVirtualInterfaceAllocationTypeDef = TypedDict(
     "NewTransitVirtualInterfaceAllocationTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
         "mtu": int,
@@ -1375,15 +1359,15 @@
 )
 
 AssociateMacSecKeyResponseTypeDef = TypedDict(
     "AssociateMacSecKeyResponseTypeDef",
     {
         "connectionId": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectionResponseMetadataTypeDef = TypedDict(
     "ConnectionResponseMetadataTypeDef",
     {
         "ownerAccount": str,
@@ -1404,15 +1388,15 @@
         "hasLogicalRedundancy": HasLogicalRedundancyType,
         "tags": List[TagTypeDef],
         "providerName": str,
         "macSecCapable": bool,
         "portEncryptionStatus": str,
         "encryptionMode": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectionTypeDef = TypedDict(
     "ConnectionTypeDef",
     {
         "ownerAccount": str,
@@ -1442,15 +1426,15 @@
 )
 
 DisassociateMacSecKeyResponseTypeDef = TypedDict(
     "DisassociateMacSecKeyResponseTypeDef",
     {
         "connectionId": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DirectConnectGatewayAssociationProposalTypeDef = TypedDict(
     "DirectConnectGatewayAssociationProposalTypeDef",
     {
         "proposalId": str,
@@ -1506,15 +1490,15 @@
         "routeFilterPrefixes": List[RouteFilterPrefixTypeDef],
         "bgpPeers": List[BGPPeerTypeDef],
         "region": str,
         "awsDeviceV2": str,
         "awsLogicalDeviceId": str,
         "tags": List[TagTypeDef],
         "siteLinkEnabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualInterfaceTypeDef = TypedDict(
     "VirtualInterfaceTypeDef",
     {
         "ownerAccount": str,
@@ -1556,165 +1540,134 @@
     total=False,
 )
 
 CreateDirectConnectGatewayResultTypeDef = TypedDict(
     "CreateDirectConnectGatewayResultTypeDef",
     {
         "directConnectGateway": DirectConnectGatewayTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDirectConnectGatewayResultTypeDef = TypedDict(
     "DeleteDirectConnectGatewayResultTypeDef",
     {
         "directConnectGateway": DirectConnectGatewayTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectConnectGatewaysResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewaysResultTypeDef",
     {
         "directConnectGateways": List[DirectConnectGatewayTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDirectConnectGatewayResponseTypeDef = TypedDict(
     "UpdateDirectConnectGatewayResponseTypeDef",
     {
         "directConnectGateway": DirectConnectGatewayTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomerMetadataResponseTypeDef = TypedDict(
     "DescribeCustomerMetadataResponseTypeDef",
     {
         "agreements": List[CustomerAgreementTypeDef],
         "nniPartnerType": NniPartnerTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectionLoaResponseTypeDef = TypedDict(
     "DescribeConnectionLoaResponseTypeDef",
     {
         "loa": LoaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInterconnectLoaResponseTypeDef = TypedDict(
     "DescribeInterconnectLoaResponseTypeDef",
     {
         "loa": LoaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef = TypedDict(
-    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
-    {
-        "associationId": str,
-        "associatedGatewayId": str,
-        "directConnectGatewayId": str,
-        "virtualGatewayId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef = TypedDict(
-    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
-    {
-        "directConnectGatewayId": str,
-        "virtualInterfaceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef = TypedDict(
-    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
-    {
-        "directConnectGatewayId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeDirectConnectGatewayAttachmentsResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAttachmentsResultTypeDef",
     {
         "directConnectGatewayAttachments": List[DirectConnectGatewayAttachmentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRouterConfigurationResponseTypeDef = TypedDict(
     "DescribeRouterConfigurationResponseTypeDef",
     {
         "customerRouterConfig": str,
         "router": RouterTypeTypeDef,
         "virtualInterfaceId": str,
         "virtualInterfaceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualInterfaceTestHistoryResponseTypeDef = TypedDict(
     "ListVirtualInterfaceTestHistoryResponseTypeDef",
     {
         "virtualInterfaceTestHistory": List[VirtualInterfaceTestHistoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartBgpFailoverTestResponseTypeDef = TypedDict(
     "StartBgpFailoverTestResponseTypeDef",
     {
         "virtualInterfaceTest": VirtualInterfaceTestHistoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopBgpFailoverTestResponseTypeDef = TypedDict(
     "StopBgpFailoverTestResponseTypeDef",
     {
         "virtualInterfaceTest": VirtualInterfaceTestHistoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LocationsTypeDef = TypedDict(
     "LocationsTypeDef",
     {
         "locations": List[LocationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualGatewaysTypeDef = TypedDict(
     "VirtualGatewaysTypeDef",
     {
         "virtualGateways": List[VirtualGatewayTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InterconnectsTypeDef = TypedDict(
     "InterconnectsTypeDef",
     {
         "interconnects": List[InterconnectTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllocatePrivateVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "AllocatePrivateVirtualInterfaceRequestRequestTypeDef",
     {
         "connectionId": str,
@@ -1765,23 +1718,23 @@
     },
 )
 
 DescribeTagsResponseTypeDef = TypedDict(
     "DescribeTagsResponseTypeDef",
     {
         "resourceTags": List[ResourceTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectionsTypeDef = TypedDict(
     "ConnectionsTypeDef",
     {
         "connections": List[ConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LagResponseMetadataTypeDef = TypedDict(
     "LagResponseMetadataTypeDef",
     {
         "connectionsBandwidth": str,
@@ -1801,15 +1754,15 @@
         "jumboFrameCapable": bool,
         "hasLogicalRedundancy": HasLogicalRedundancyType,
         "tags": List[TagTypeDef],
         "providerName": str,
         "macSecCapable": bool,
         "encryptionMode": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LagTypeDef = TypedDict(
     "LagTypeDef",
     {
         "connectionsBandwidth": str,
@@ -1837,118 +1790,118 @@
     total=False,
 )
 
 CreateDirectConnectGatewayAssociationProposalResultTypeDef = TypedDict(
     "CreateDirectConnectGatewayAssociationProposalResultTypeDef",
     {
         "directConnectGatewayAssociationProposal": DirectConnectGatewayAssociationProposalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDirectConnectGatewayAssociationProposalResultTypeDef = TypedDict(
     "DeleteDirectConnectGatewayAssociationProposalResultTypeDef",
     {
         "directConnectGatewayAssociationProposal": DirectConnectGatewayAssociationProposalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectConnectGatewayAssociationProposalsResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAssociationProposalsResultTypeDef",
     {
         "directConnectGatewayAssociationProposals": List[
             DirectConnectGatewayAssociationProposalTypeDef
         ],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptDirectConnectGatewayAssociationProposalResultTypeDef = TypedDict(
     "AcceptDirectConnectGatewayAssociationProposalResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDirectConnectGatewayAssociationResultTypeDef = TypedDict(
     "CreateDirectConnectGatewayAssociationResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDirectConnectGatewayAssociationResultTypeDef = TypedDict(
     "DeleteDirectConnectGatewayAssociationResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectConnectGatewayAssociationsResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAssociationsResultTypeDef",
     {
         "directConnectGatewayAssociations": List[DirectConnectGatewayAssociationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDirectConnectGatewayAssociationResultTypeDef = TypedDict(
     "UpdateDirectConnectGatewayAssociationResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllocateTransitVirtualInterfaceResultTypeDef = TypedDict(
     "AllocateTransitVirtualInterfaceResultTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBGPPeerResponseTypeDef = TypedDict(
     "CreateBGPPeerResponseTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTransitVirtualInterfaceResultTypeDef = TypedDict(
     "CreateTransitVirtualInterfaceResultTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBGPPeerResponseTypeDef = TypedDict(
     "DeleteBGPPeerResponseTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualInterfacesTypeDef = TypedDict(
     "VirtualInterfacesTypeDef",
     {
         "virtualInterfaces": List[VirtualInterfaceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LagsTypeDef = TypedDict(
     "LagsTypeDef",
     {
         "lags": List[LagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect/type_defs.pyi` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect/type_defs.py`

 * *Files 11% similar despite different names*

```diff
@@ -38,87 +38,91 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "RouteFilterPrefixTypeDef",
-    "ResponseMetadataTypeDef",
     "AllocateConnectionOnInterconnectRequestRequestTypeDef",
     "TagTypeDef",
     "AssociateConnectionWithLagRequestRequestTypeDef",
     "AssociateHostedConnectionRequestRequestTypeDef",
     "AssociateMacSecKeyRequestRequestTypeDef",
     "MacSecKeyTypeDef",
     "AssociateVirtualInterfaceRequestRequestTypeDef",
     "AssociatedGatewayTypeDef",
     "BGPPeerTypeDef",
     "ConfirmConnectionRequestRequestTypeDef",
+    "ConfirmConnectionResponseTypeDef",
     "ConfirmCustomerAgreementRequestRequestTypeDef",
+    "ConfirmCustomerAgreementResponseTypeDef",
     "ConfirmPrivateVirtualInterfaceRequestRequestTypeDef",
+    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
     "ConfirmPublicVirtualInterfaceRequestRequestTypeDef",
+    "ConfirmPublicVirtualInterfaceResponseTypeDef",
     "ConfirmTransitVirtualInterfaceRequestRequestTypeDef",
+    "ConfirmTransitVirtualInterfaceResponseTypeDef",
     "NewBGPPeerTypeDef",
     "CreateDirectConnectGatewayRequestRequestTypeDef",
     "DirectConnectGatewayTypeDef",
     "CustomerAgreementTypeDef",
     "DeleteBGPPeerRequestRequestTypeDef",
     "DeleteConnectionRequestRequestTypeDef",
     "DeleteDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     "DeleteDirectConnectGatewayAssociationRequestRequestTypeDef",
     "DeleteDirectConnectGatewayRequestRequestTypeDef",
     "DeleteInterconnectRequestRequestTypeDef",
+    "DeleteInterconnectResponseTypeDef",
     "DeleteLagRequestRequestTypeDef",
     "DeleteVirtualInterfaceRequestRequestTypeDef",
+    "DeleteVirtualInterfaceResponseTypeDef",
     "DescribeConnectionLoaRequestRequestTypeDef",
     "LoaTypeDef",
     "DescribeConnectionsOnInterconnectRequestRequestTypeDef",
     "DescribeConnectionsRequestRequestTypeDef",
     "DescribeDirectConnectGatewayAssociationProposalsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
     "DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef",
+    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
     "DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef",
     "DirectConnectGatewayAttachmentTypeDef",
+    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
     "DescribeDirectConnectGatewaysRequestRequestTypeDef",
     "DescribeHostedConnectionsRequestRequestTypeDef",
     "DescribeInterconnectLoaRequestRequestTypeDef",
     "DescribeInterconnectsRequestRequestTypeDef",
     "DescribeLagsRequestRequestTypeDef",
     "DescribeLoaRequestRequestTypeDef",
     "DescribeRouterConfigurationRequestRequestTypeDef",
     "RouterTypeTypeDef",
     "DescribeTagsRequestRequestTypeDef",
     "DescribeVirtualInterfacesRequestRequestTypeDef",
     "DisassociateConnectionFromLagRequestRequestTypeDef",
     "DisassociateMacSecKeyRequestRequestTypeDef",
     "ListVirtualInterfaceTestHistoryRequestRequestTypeDef",
     "VirtualInterfaceTestHistoryTypeDef",
+    "LoaResponseMetadataTypeDef",
     "LocationTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartBgpFailoverTestRequestRequestTypeDef",
     "StopBgpFailoverTestRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateConnectionRequestRequestTypeDef",
     "UpdateDirectConnectGatewayRequestRequestTypeDef",
     "UpdateLagRequestRequestTypeDef",
     "UpdateVirtualInterfaceAttributesRequestRequestTypeDef",
     "VirtualGatewayTypeDef",
     "AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     "CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     "CreateDirectConnectGatewayAssociationRequestRequestTypeDef",
     "UpdateDirectConnectGatewayAssociationRequestRequestTypeDef",
-    "ConfirmConnectionResponseTypeDef",
-    "ConfirmCustomerAgreementResponseTypeDef",
-    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
-    "ConfirmPublicVirtualInterfaceResponseTypeDef",
-    "ConfirmTransitVirtualInterfaceResponseTypeDef",
-    "DeleteInterconnectResponseTypeDef",
-    "DeleteVirtualInterfaceResponseTypeDef",
-    "LoaResponseMetadataTypeDef",
     "AllocateHostedConnectionRequestRequestTypeDef",
     "CreateConnectionRequestRequestTypeDef",
     "CreateInterconnectRequestRequestTypeDef",
     "CreateLagRequestRequestTypeDef",
     "InterconnectResponseMetadataTypeDef",
     "InterconnectTypeDef",
     "NewPrivateVirtualInterfaceAllocationTypeDef",
@@ -141,17 +145,14 @@
     "CreateDirectConnectGatewayResultTypeDef",
     "DeleteDirectConnectGatewayResultTypeDef",
     "DescribeDirectConnectGatewaysResultTypeDef",
     "UpdateDirectConnectGatewayResponseTypeDef",
     "DescribeCustomerMetadataResponseTypeDef",
     "DescribeConnectionLoaResponseTypeDef",
     "DescribeInterconnectLoaResponseTypeDef",
-    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
-    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
-    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
     "DescribeDirectConnectGatewayAttachmentsResultTypeDef",
     "DescribeRouterConfigurationResponseTypeDef",
     "ListVirtualInterfaceTestHistoryResponseTypeDef",
     "StartBgpFailoverTestResponseTypeDef",
     "StopBgpFailoverTestResponseTypeDef",
     "LocationsTypeDef",
     "VirtualGatewaysTypeDef",
@@ -186,25 +187,14 @@
     "RouteFilterPrefixTypeDef",
     {
         "cidr": str,
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
 AllocateConnectionOnInterconnectRequestRequestTypeDef = TypedDict(
     "AllocateConnectionOnInterconnectRequestRequestTypeDef",
     {
         "bandwidth": str,
         "connectionName": str,
         "ownerAccount": str,
         "interconnectId": str,
@@ -222,17 +212,19 @@
     "_OptionalTagTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
+
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
+
 AssociateConnectionWithLagRequestRequestTypeDef = TypedDict(
     "AssociateConnectionWithLagRequestRequestTypeDef",
     {
         "connectionId": str,
         "lagId": str,
     },
 )
@@ -257,20 +249,22 @@
         "secretARN": str,
         "ckn": str,
         "cak": str,
     },
     total=False,
 )
 
+
 class AssociateMacSecKeyRequestRequestTypeDef(
     _RequiredAssociateMacSecKeyRequestRequestTypeDef,
     _OptionalAssociateMacSecKeyRequestRequestTypeDef,
 ):
     pass
 
+
 MacSecKeyTypeDef = TypedDict(
     "MacSecKeyTypeDef",
     {
         "secretARN": str,
         "ckn": str,
         "state": str,
         "startOn": str,
@@ -317,22 +311,38 @@
 ConfirmConnectionRequestRequestTypeDef = TypedDict(
     "ConfirmConnectionRequestRequestTypeDef",
     {
         "connectionId": str,
     },
 )
 
+ConfirmConnectionResponseTypeDef = TypedDict(
+    "ConfirmConnectionResponseTypeDef",
+    {
+        "connectionState": ConnectionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfirmCustomerAgreementRequestRequestTypeDef = TypedDict(
     "ConfirmCustomerAgreementRequestRequestTypeDef",
     {
         "agreementName": str,
     },
     total=False,
 )
 
+ConfirmCustomerAgreementResponseTypeDef = TypedDict(
+    "ConfirmCustomerAgreementResponseTypeDef",
+    {
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredConfirmPrivateVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "_RequiredConfirmPrivateVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalConfirmPrivateVirtualInterfaceRequestRequestTypeDef = TypedDict(
@@ -340,35 +350,61 @@
     {
         "virtualGatewayId": str,
         "directConnectGatewayId": str,
     },
     total=False,
 )
 
+
 class ConfirmPrivateVirtualInterfaceRequestRequestTypeDef(
     _RequiredConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
     _OptionalConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
 ):
     pass
 
+
+ConfirmPrivateVirtualInterfaceResponseTypeDef = TypedDict(
+    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfirmPublicVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "ConfirmPublicVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 
+ConfirmPublicVirtualInterfaceResponseTypeDef = TypedDict(
+    "ConfirmPublicVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConfirmTransitVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "ConfirmTransitVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
         "directConnectGatewayId": str,
     },
 )
 
+ConfirmTransitVirtualInterfaceResponseTypeDef = TypedDict(
+    "ConfirmTransitVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NewBGPPeerTypeDef = TypedDict(
     "NewBGPPeerTypeDef",
     {
         "asn": int,
         "authKey": str,
         "addressFamily": AddressFamilyType,
         "amazonAddress": str,
@@ -387,20 +423,22 @@
     "_OptionalCreateDirectConnectGatewayRequestRequestTypeDef",
     {
         "amazonSideAsn": int,
     },
     total=False,
 )
 
+
 class CreateDirectConnectGatewayRequestRequestTypeDef(
     _RequiredCreateDirectConnectGatewayRequestRequestTypeDef,
     _OptionalCreateDirectConnectGatewayRequestRequestTypeDef,
 ):
     pass
 
+
 DirectConnectGatewayTypeDef = TypedDict(
     "DirectConnectGatewayTypeDef",
     {
         "directConnectGatewayId": str,
         "directConnectGatewayName": str,
         "amazonSideAsn": int,
         "ownerAccount": str,
@@ -464,28 +502,44 @@
 DeleteInterconnectRequestRequestTypeDef = TypedDict(
     "DeleteInterconnectRequestRequestTypeDef",
     {
         "interconnectId": str,
     },
 )
 
+DeleteInterconnectResponseTypeDef = TypedDict(
+    "DeleteInterconnectResponseTypeDef",
+    {
+        "interconnectState": InterconnectStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLagRequestRequestTypeDef = TypedDict(
     "DeleteLagRequestRequestTypeDef",
     {
         "lagId": str,
     },
 )
 
 DeleteVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "DeleteVirtualInterfaceRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 
+DeleteVirtualInterfaceResponseTypeDef = TypedDict(
+    "DeleteVirtualInterfaceResponseTypeDef",
+    {
+        "virtualInterfaceState": VirtualInterfaceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeConnectionLoaRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConnectionLoaRequestRequestTypeDef",
     {
         "connectionId": str,
     },
 )
 _OptionalDescribeConnectionLoaRequestRequestTypeDef = TypedDict(
@@ -493,20 +547,22 @@
     {
         "providerName": str,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
 )
 
+
 class DescribeConnectionLoaRequestRequestTypeDef(
     _RequiredDescribeConnectionLoaRequestRequestTypeDef,
     _OptionalDescribeConnectionLoaRequestRequestTypeDef,
 ):
     pass
 
+
 LoaTypeDef = TypedDict(
     "LoaTypeDef",
     {
         "loaContent": bytes,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
@@ -535,20 +591,22 @@
         "associatedGatewayId": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef = TypedDict(
+    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "associationId": str,
+        "associatedGatewayId": str,
+        "directConnectGatewayId": str,
+        "virtualGatewayId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef",
     {
@@ -558,14 +616,24 @@
         "maxResults": int,
         "nextToken": str,
         "virtualGatewayId": str,
     },
     total=False,
 )
 
+DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef = TypedDict(
+    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
+    {
+        "directConnectGatewayId": str,
+        "virtualInterfaceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "virtualInterfaceId": str,
         "maxResults": int,
         "nextToken": str,
@@ -583,14 +651,23 @@
         "attachmentState": DirectConnectGatewayAttachmentStateType,
         "attachmentType": DirectConnectGatewayAttachmentTypeType,
         "stateChangeError": str,
     },
     total=False,
 )
 
+DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef = TypedDict(
+    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
+    {
+        "directConnectGatewayId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDirectConnectGatewaysRequestRequestTypeDef = TypedDict(
     "DescribeDirectConnectGatewaysRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "maxResults": int,
         "nextToken": str,
     },
@@ -615,20 +692,22 @@
     {
         "providerName": str,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
 )
 
+
 class DescribeInterconnectLoaRequestRequestTypeDef(
     _RequiredDescribeInterconnectLoaRequestRequestTypeDef,
     _OptionalDescribeInterconnectLoaRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeInterconnectsRequestRequestTypeDef = TypedDict(
     "DescribeInterconnectsRequestRequestTypeDef",
     {
         "interconnectId": str,
     },
     total=False,
 )
@@ -652,39 +731,43 @@
     {
         "providerName": str,
         "loaContentType": Literal["application/pdf"],
     },
     total=False,
 )
 
+
 class DescribeLoaRequestRequestTypeDef(
     _RequiredDescribeLoaRequestRequestTypeDef, _OptionalDescribeLoaRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredDescribeRouterConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRouterConfigurationRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalDescribeRouterConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeRouterConfigurationRequestRequestTypeDef",
     {
         "routerTypeIdentifier": str,
     },
     total=False,
 )
 
+
 class DescribeRouterConfigurationRequestRequestTypeDef(
     _RequiredDescribeRouterConfigurationRequestRequestTypeDef,
     _OptionalDescribeRouterConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 RouterTypeTypeDef = TypedDict(
     "RouterTypeTypeDef",
     {
         "vendor": str,
         "platform": str,
         "software": str,
         "xsltTemplateName": str,
@@ -750,27 +833,57 @@
         "testDurationInMinutes": int,
         "startTime": datetime,
         "endTime": datetime,
     },
     total=False,
 )
 
+LoaResponseMetadataTypeDef = TypedDict(
+    "LoaResponseMetadataTypeDef",
+    {
+        "loaContent": bytes,
+        "loaContentType": Literal["application/pdf"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LocationTypeDef = TypedDict(
     "LocationTypeDef",
     {
         "locationCode": str,
         "locationName": str,
         "region": str,
         "availablePortSpeeds": List[str],
         "availableProviders": List[str],
         "availableMacSecPortSpeeds": List[str],
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
 _RequiredStartBgpFailoverTestRequestRequestTypeDef = TypedDict(
     "_RequiredStartBgpFailoverTestRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalStartBgpFailoverTestRequestRequestTypeDef = TypedDict(
@@ -778,20 +891,22 @@
     {
         "bgpPeers": Sequence[str],
         "testDurationInMinutes": int,
     },
     total=False,
 )
 
+
 class StartBgpFailoverTestRequestRequestTypeDef(
     _RequiredStartBgpFailoverTestRequestRequestTypeDef,
     _OptionalStartBgpFailoverTestRequestRequestTypeDef,
 ):
     pass
 
+
 StopBgpFailoverTestRequestRequestTypeDef = TypedDict(
     "StopBgpFailoverTestRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 
@@ -814,19 +929,21 @@
     {
         "connectionName": str,
         "encryptionMode": str,
     },
     total=False,
 )
 
+
 class UpdateConnectionRequestRequestTypeDef(
     _RequiredUpdateConnectionRequestRequestTypeDef, _OptionalUpdateConnectionRequestRequestTypeDef
 ):
     pass
 
+
 UpdateDirectConnectGatewayRequestRequestTypeDef = TypedDict(
     "UpdateDirectConnectGatewayRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "newDirectConnectGatewayName": str,
     },
 )
@@ -843,19 +960,21 @@
         "lagName": str,
         "minimumLinks": int,
         "encryptionMode": str,
     },
     total=False,
 )
 
+
 class UpdateLagRequestRequestTypeDef(
     _RequiredUpdateLagRequestRequestTypeDef, _OptionalUpdateLagRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateVirtualInterfaceAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVirtualInterfaceAttributesRequestRequestTypeDef",
     {
         "virtualInterfaceId": str,
     },
 )
 _OptionalUpdateVirtualInterfaceAttributesRequestRequestTypeDef = TypedDict(
@@ -864,20 +983,22 @@
         "mtu": int,
         "enableSiteLink": bool,
         "virtualInterfaceName": str,
     },
     total=False,
 )
 
+
 class UpdateVirtualInterfaceAttributesRequestRequestTypeDef(
     _RequiredUpdateVirtualInterfaceAttributesRequestRequestTypeDef,
     _OptionalUpdateVirtualInterfaceAttributesRequestRequestTypeDef,
 ):
     pass
 
+
 VirtualGatewayTypeDef = TypedDict(
     "VirtualGatewayTypeDef",
     {
         "virtualGatewayId": str,
         "virtualGatewayState": str,
     },
     total=False,
@@ -895,20 +1016,22 @@
     "_OptionalAcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     {
         "overrideAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
     },
     total=False,
 )
 
+
 class AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef(
     _RequiredAcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     _OptionalAcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
         "directConnectGatewayOwnerAccount": str,
         "gatewayId": str,
     },
@@ -918,20 +1041,22 @@
     {
         "addAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
         "removeAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
     },
     total=False,
 )
 
+
 class CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef(
     _RequiredCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     _OptionalCreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDirectConnectGatewayAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDirectConnectGatewayAssociationRequestRequestTypeDef",
     {
         "directConnectGatewayId": str,
     },
 )
 _OptionalCreateDirectConnectGatewayAssociationRequestRequestTypeDef = TypedDict(
@@ -940,95 +1065,32 @@
         "gatewayId": str,
         "addAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
         "virtualGatewayId": str,
     },
     total=False,
 )
 
+
 class CreateDirectConnectGatewayAssociationRequestRequestTypeDef(
     _RequiredCreateDirectConnectGatewayAssociationRequestRequestTypeDef,
     _OptionalCreateDirectConnectGatewayAssociationRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateDirectConnectGatewayAssociationRequestRequestTypeDef = TypedDict(
     "UpdateDirectConnectGatewayAssociationRequestRequestTypeDef",
     {
         "associationId": str,
         "addAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
         "removeAllowedPrefixesToDirectConnectGateway": Sequence[RouteFilterPrefixTypeDef],
     },
     total=False,
 )
 
-ConfirmConnectionResponseTypeDef = TypedDict(
-    "ConfirmConnectionResponseTypeDef",
-    {
-        "connectionState": ConnectionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmCustomerAgreementResponseTypeDef = TypedDict(
-    "ConfirmCustomerAgreementResponseTypeDef",
-    {
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmPrivateVirtualInterfaceResponseTypeDef = TypedDict(
-    "ConfirmPrivateVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmPublicVirtualInterfaceResponseTypeDef = TypedDict(
-    "ConfirmPublicVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfirmTransitVirtualInterfaceResponseTypeDef = TypedDict(
-    "ConfirmTransitVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteInterconnectResponseTypeDef = TypedDict(
-    "DeleteInterconnectResponseTypeDef",
-    {
-        "interconnectState": InterconnectStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteVirtualInterfaceResponseTypeDef = TypedDict(
-    "DeleteVirtualInterfaceResponseTypeDef",
-    {
-        "virtualInterfaceState": VirtualInterfaceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-LoaResponseMetadataTypeDef = TypedDict(
-    "LoaResponseMetadataTypeDef",
-    {
-        "loaContent": bytes,
-        "loaContentType": Literal["application/pdf"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredAllocateHostedConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredAllocateHostedConnectionRequestRequestTypeDef",
     {
         "connectionId": str,
         "ownerAccount": str,
         "bandwidth": str,
         "connectionName": str,
@@ -1039,20 +1101,22 @@
     "_OptionalAllocateHostedConnectionRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class AllocateHostedConnectionRequestRequestTypeDef(
     _RequiredAllocateHostedConnectionRequestRequestTypeDef,
     _OptionalAllocateHostedConnectionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectionRequestRequestTypeDef",
     {
         "location": str,
         "bandwidth": str,
         "connectionName": str,
     },
@@ -1064,19 +1128,21 @@
         "tags": Sequence[TagTypeDef],
         "providerName": str,
         "requestMACSec": bool,
     },
     total=False,
 )
 
+
 class CreateConnectionRequestRequestTypeDef(
     _RequiredCreateConnectionRequestRequestTypeDef, _OptionalCreateConnectionRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateInterconnectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInterconnectRequestRequestTypeDef",
     {
         "interconnectName": str,
         "bandwidth": str,
         "location": str,
     },
@@ -1087,20 +1153,22 @@
         "lagId": str,
         "tags": Sequence[TagTypeDef],
         "providerName": str,
     },
     total=False,
 )
 
+
 class CreateInterconnectRequestRequestTypeDef(
     _RequiredCreateInterconnectRequestRequestTypeDef,
     _OptionalCreateInterconnectRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateLagRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLagRequestRequestTypeDef",
     {
         "numberOfConnections": int,
         "location": str,
         "connectionsBandwidth": str,
         "lagName": str,
@@ -1114,19 +1182,21 @@
         "childConnectionTags": Sequence[TagTypeDef],
         "providerName": str,
         "requestMACSec": bool,
     },
     total=False,
 )
 
+
 class CreateLagRequestRequestTypeDef(
     _RequiredCreateLagRequestRequestTypeDef, _OptionalCreateLagRequestRequestTypeDef
 ):
     pass
 
+
 InterconnectResponseMetadataTypeDef = TypedDict(
     "InterconnectResponseMetadataTypeDef",
     {
         "interconnectId": str,
         "interconnectName": str,
         "interconnectState": InterconnectStateType,
         "region": str,
@@ -1137,15 +1207,15 @@
         "awsDevice": str,
         "jumboFrameCapable": bool,
         "awsDeviceV2": str,
         "awsLogicalDeviceId": str,
         "hasLogicalRedundancy": HasLogicalRedundancyType,
         "tags": List[TagTypeDef],
         "providerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InterconnectTypeDef = TypedDict(
     "InterconnectTypeDef",
     {
         "interconnectId": str,
@@ -1184,20 +1254,22 @@
         "addressFamily": AddressFamilyType,
         "customerAddress": str,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class NewPrivateVirtualInterfaceAllocationTypeDef(
     _RequiredNewPrivateVirtualInterfaceAllocationTypeDef,
     _OptionalNewPrivateVirtualInterfaceAllocationTypeDef,
 ):
     pass
 
+
 _RequiredNewPrivateVirtualInterfaceTypeDef = TypedDict(
     "_RequiredNewPrivateVirtualInterfaceTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
     },
@@ -1214,19 +1286,21 @@
         "directConnectGatewayId": str,
         "tags": Sequence[TagTypeDef],
         "enableSiteLink": bool,
     },
     total=False,
 )
 
+
 class NewPrivateVirtualInterfaceTypeDef(
     _RequiredNewPrivateVirtualInterfaceTypeDef, _OptionalNewPrivateVirtualInterfaceTypeDef
 ):
     pass
 
+
 _RequiredNewPublicVirtualInterfaceAllocationTypeDef = TypedDict(
     "_RequiredNewPublicVirtualInterfaceAllocationTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
     },
@@ -1240,20 +1314,22 @@
         "addressFamily": AddressFamilyType,
         "routeFilterPrefixes": Sequence[RouteFilterPrefixTypeDef],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class NewPublicVirtualInterfaceAllocationTypeDef(
     _RequiredNewPublicVirtualInterfaceAllocationTypeDef,
     _OptionalNewPublicVirtualInterfaceAllocationTypeDef,
 ):
     pass
 
+
 _RequiredNewPublicVirtualInterfaceTypeDef = TypedDict(
     "_RequiredNewPublicVirtualInterfaceTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
     },
@@ -1267,19 +1343,21 @@
         "addressFamily": AddressFamilyType,
         "routeFilterPrefixes": Sequence[RouteFilterPrefixTypeDef],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class NewPublicVirtualInterfaceTypeDef(
     _RequiredNewPublicVirtualInterfaceTypeDef, _OptionalNewPublicVirtualInterfaceTypeDef
 ):
     pass
 
+
 NewTransitVirtualInterfaceAllocationTypeDef = TypedDict(
     "NewTransitVirtualInterfaceAllocationTypeDef",
     {
         "virtualInterfaceName": str,
         "vlan": int,
         "asn": int,
         "mtu": int,
@@ -1328,15 +1406,15 @@
 )
 
 AssociateMacSecKeyResponseTypeDef = TypedDict(
     "AssociateMacSecKeyResponseTypeDef",
     {
         "connectionId": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectionResponseMetadataTypeDef = TypedDict(
     "ConnectionResponseMetadataTypeDef",
     {
         "ownerAccount": str,
@@ -1357,15 +1435,15 @@
         "hasLogicalRedundancy": HasLogicalRedundancyType,
         "tags": List[TagTypeDef],
         "providerName": str,
         "macSecCapable": bool,
         "portEncryptionStatus": str,
         "encryptionMode": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectionTypeDef = TypedDict(
     "ConnectionTypeDef",
     {
         "ownerAccount": str,
@@ -1395,15 +1473,15 @@
 )
 
 DisassociateMacSecKeyResponseTypeDef = TypedDict(
     "DisassociateMacSecKeyResponseTypeDef",
     {
         "connectionId": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DirectConnectGatewayAssociationProposalTypeDef = TypedDict(
     "DirectConnectGatewayAssociationProposalTypeDef",
     {
         "proposalId": str,
@@ -1459,15 +1537,15 @@
         "routeFilterPrefixes": List[RouteFilterPrefixTypeDef],
         "bgpPeers": List[BGPPeerTypeDef],
         "region": str,
         "awsDeviceV2": str,
         "awsLogicalDeviceId": str,
         "tags": List[TagTypeDef],
         "siteLinkEnabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualInterfaceTypeDef = TypedDict(
     "VirtualInterfaceTypeDef",
     {
         "ownerAccount": str,
@@ -1509,165 +1587,134 @@
     total=False,
 )
 
 CreateDirectConnectGatewayResultTypeDef = TypedDict(
     "CreateDirectConnectGatewayResultTypeDef",
     {
         "directConnectGateway": DirectConnectGatewayTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDirectConnectGatewayResultTypeDef = TypedDict(
     "DeleteDirectConnectGatewayResultTypeDef",
     {
         "directConnectGateway": DirectConnectGatewayTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectConnectGatewaysResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewaysResultTypeDef",
     {
         "directConnectGateways": List[DirectConnectGatewayTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDirectConnectGatewayResponseTypeDef = TypedDict(
     "UpdateDirectConnectGatewayResponseTypeDef",
     {
         "directConnectGateway": DirectConnectGatewayTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomerMetadataResponseTypeDef = TypedDict(
     "DescribeCustomerMetadataResponseTypeDef",
     {
         "agreements": List[CustomerAgreementTypeDef],
         "nniPartnerType": NniPartnerTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectionLoaResponseTypeDef = TypedDict(
     "DescribeConnectionLoaResponseTypeDef",
     {
         "loa": LoaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInterconnectLoaResponseTypeDef = TypedDict(
     "DescribeInterconnectLoaResponseTypeDef",
     {
         "loa": LoaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef = TypedDict(
-    "DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef",
-    {
-        "associationId": str,
-        "associatedGatewayId": str,
-        "directConnectGatewayId": str,
-        "virtualGatewayId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef = TypedDict(
-    "DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef",
-    {
-        "directConnectGatewayId": str,
-        "virtualInterfaceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef = TypedDict(
-    "DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef",
-    {
-        "directConnectGatewayId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeDirectConnectGatewayAttachmentsResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAttachmentsResultTypeDef",
     {
         "directConnectGatewayAttachments": List[DirectConnectGatewayAttachmentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRouterConfigurationResponseTypeDef = TypedDict(
     "DescribeRouterConfigurationResponseTypeDef",
     {
         "customerRouterConfig": str,
         "router": RouterTypeTypeDef,
         "virtualInterfaceId": str,
         "virtualInterfaceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualInterfaceTestHistoryResponseTypeDef = TypedDict(
     "ListVirtualInterfaceTestHistoryResponseTypeDef",
     {
         "virtualInterfaceTestHistory": List[VirtualInterfaceTestHistoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartBgpFailoverTestResponseTypeDef = TypedDict(
     "StartBgpFailoverTestResponseTypeDef",
     {
         "virtualInterfaceTest": VirtualInterfaceTestHistoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopBgpFailoverTestResponseTypeDef = TypedDict(
     "StopBgpFailoverTestResponseTypeDef",
     {
         "virtualInterfaceTest": VirtualInterfaceTestHistoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LocationsTypeDef = TypedDict(
     "LocationsTypeDef",
     {
         "locations": List[LocationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualGatewaysTypeDef = TypedDict(
     "VirtualGatewaysTypeDef",
     {
         "virtualGateways": List[VirtualGatewayTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InterconnectsTypeDef = TypedDict(
     "InterconnectsTypeDef",
     {
         "interconnects": List[InterconnectTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllocatePrivateVirtualInterfaceRequestRequestTypeDef = TypedDict(
     "AllocatePrivateVirtualInterfaceRequestRequestTypeDef",
     {
         "connectionId": str,
@@ -1718,23 +1765,23 @@
     },
 )
 
 DescribeTagsResponseTypeDef = TypedDict(
     "DescribeTagsResponseTypeDef",
     {
         "resourceTags": List[ResourceTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectionsTypeDef = TypedDict(
     "ConnectionsTypeDef",
     {
         "connections": List[ConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LagResponseMetadataTypeDef = TypedDict(
     "LagResponseMetadataTypeDef",
     {
         "connectionsBandwidth": str,
@@ -1754,15 +1801,15 @@
         "jumboFrameCapable": bool,
         "hasLogicalRedundancy": HasLogicalRedundancyType,
         "tags": List[TagTypeDef],
         "providerName": str,
         "macSecCapable": bool,
         "encryptionMode": str,
         "macSecKeys": List[MacSecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LagTypeDef = TypedDict(
     "LagTypeDef",
     {
         "connectionsBandwidth": str,
@@ -1790,118 +1837,118 @@
     total=False,
 )
 
 CreateDirectConnectGatewayAssociationProposalResultTypeDef = TypedDict(
     "CreateDirectConnectGatewayAssociationProposalResultTypeDef",
     {
         "directConnectGatewayAssociationProposal": DirectConnectGatewayAssociationProposalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDirectConnectGatewayAssociationProposalResultTypeDef = TypedDict(
     "DeleteDirectConnectGatewayAssociationProposalResultTypeDef",
     {
         "directConnectGatewayAssociationProposal": DirectConnectGatewayAssociationProposalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectConnectGatewayAssociationProposalsResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAssociationProposalsResultTypeDef",
     {
         "directConnectGatewayAssociationProposals": List[
             DirectConnectGatewayAssociationProposalTypeDef
         ],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptDirectConnectGatewayAssociationProposalResultTypeDef = TypedDict(
     "AcceptDirectConnectGatewayAssociationProposalResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDirectConnectGatewayAssociationResultTypeDef = TypedDict(
     "CreateDirectConnectGatewayAssociationResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDirectConnectGatewayAssociationResultTypeDef = TypedDict(
     "DeleteDirectConnectGatewayAssociationResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectConnectGatewayAssociationsResultTypeDef = TypedDict(
     "DescribeDirectConnectGatewayAssociationsResultTypeDef",
     {
         "directConnectGatewayAssociations": List[DirectConnectGatewayAssociationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDirectConnectGatewayAssociationResultTypeDef = TypedDict(
     "UpdateDirectConnectGatewayAssociationResultTypeDef",
     {
         "directConnectGatewayAssociation": DirectConnectGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllocateTransitVirtualInterfaceResultTypeDef = TypedDict(
     "AllocateTransitVirtualInterfaceResultTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBGPPeerResponseTypeDef = TypedDict(
     "CreateBGPPeerResponseTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTransitVirtualInterfaceResultTypeDef = TypedDict(
     "CreateTransitVirtualInterfaceResultTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBGPPeerResponseTypeDef = TypedDict(
     "DeleteBGPPeerResponseTypeDef",
     {
         "virtualInterface": VirtualInterfaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VirtualInterfacesTypeDef = TypedDict(
     "VirtualInterfacesTypeDef",
     {
         "virtualInterfaces": List[VirtualInterfaceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LagsTypeDef = TypedDict(
     "LagsTypeDef",
     {
         "lags": List[LagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/PKG-INFO` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-directconnect
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DirectConnect 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DirectConnect 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-directconnect"></a>
 
 # types-aiobotocore-directconnect
 
 [![PyPI - types-aiobotocore-directconnect](https://img.shields.io/pypi/v/types-aiobotocore-directconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-directconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-directconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-directconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-directconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-directconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DirectConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
+[aiobotocore.DirectConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/directconnect.html#DirectConnect)
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
 [types-aiobotocore-directconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_directconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -345,85 +345,88 @@
 
 `types_aiobotocore_directconnect.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_directconnect.type_defs import (
     RouteFilterPrefixTypeDef,
-    ResponseMetadataTypeDef,
     AllocateConnectionOnInterconnectRequestRequestTypeDef,
     TagTypeDef,
     AssociateConnectionWithLagRequestRequestTypeDef,
     AssociateHostedConnectionRequestRequestTypeDef,
     AssociateMacSecKeyRequestRequestTypeDef,
     MacSecKeyTypeDef,
     AssociateVirtualInterfaceRequestRequestTypeDef,
     AssociatedGatewayTypeDef,
     BGPPeerTypeDef,
     ConfirmConnectionRequestRequestTypeDef,
+    ConfirmConnectionResponseTypeDef,
     ConfirmCustomerAgreementRequestRequestTypeDef,
+    ConfirmCustomerAgreementResponseTypeDef,
     ConfirmPrivateVirtualInterfaceRequestRequestTypeDef,
+    ConfirmPrivateVirtualInterfaceResponseTypeDef,
     ConfirmPublicVirtualInterfaceRequestRequestTypeDef,
+    ConfirmPublicVirtualInterfaceResponseTypeDef,
     ConfirmTransitVirtualInterfaceRequestRequestTypeDef,
+    ConfirmTransitVirtualInterfaceResponseTypeDef,
     NewBGPPeerTypeDef,
     CreateDirectConnectGatewayRequestRequestTypeDef,
     DirectConnectGatewayTypeDef,
     CustomerAgreementTypeDef,
     DeleteBGPPeerRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
     DeleteDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     DeleteDirectConnectGatewayAssociationRequestRequestTypeDef,
     DeleteDirectConnectGatewayRequestRequestTypeDef,
     DeleteInterconnectRequestRequestTypeDef,
+    DeleteInterconnectResponseTypeDef,
     DeleteLagRequestRequestTypeDef,
     DeleteVirtualInterfaceRequestRequestTypeDef,
+    DeleteVirtualInterfaceResponseTypeDef,
     DescribeConnectionLoaRequestRequestTypeDef,
     LoaTypeDef,
     DescribeConnectionsOnInterconnectRequestRequestTypeDef,
     DescribeConnectionsRequestRequestTypeDef,
     DescribeDirectConnectGatewayAssociationProposalsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef,
     DescribeDirectConnectGatewayAssociationsRequestRequestTypeDef,
+    DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef,
     DescribeDirectConnectGatewayAttachmentsRequestRequestTypeDef,
     DirectConnectGatewayAttachmentTypeDef,
+    DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef,
     DescribeDirectConnectGatewaysRequestRequestTypeDef,
     DescribeHostedConnectionsRequestRequestTypeDef,
     DescribeInterconnectLoaRequestRequestTypeDef,
     DescribeInterconnectsRequestRequestTypeDef,
     DescribeLagsRequestRequestTypeDef,
     DescribeLoaRequestRequestTypeDef,
     DescribeRouterConfigurationRequestRequestTypeDef,
     RouterTypeTypeDef,
     DescribeTagsRequestRequestTypeDef,
     DescribeVirtualInterfacesRequestRequestTypeDef,
     DisassociateConnectionFromLagRequestRequestTypeDef,
     DisassociateMacSecKeyRequestRequestTypeDef,
     ListVirtualInterfaceTestHistoryRequestRequestTypeDef,
     VirtualInterfaceTestHistoryTypeDef,
+    LoaResponseMetadataTypeDef,
     LocationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartBgpFailoverTestRequestRequestTypeDef,
     StopBgpFailoverTestRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateConnectionRequestRequestTypeDef,
     UpdateDirectConnectGatewayRequestRequestTypeDef,
     UpdateLagRequestRequestTypeDef,
     UpdateVirtualInterfaceAttributesRequestRequestTypeDef,
     VirtualGatewayTypeDef,
     AcceptDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     CreateDirectConnectGatewayAssociationProposalRequestRequestTypeDef,
     CreateDirectConnectGatewayAssociationRequestRequestTypeDef,
     UpdateDirectConnectGatewayAssociationRequestRequestTypeDef,
-    ConfirmConnectionResponseTypeDef,
-    ConfirmCustomerAgreementResponseTypeDef,
-    ConfirmPrivateVirtualInterfaceResponseTypeDef,
-    ConfirmPublicVirtualInterfaceResponseTypeDef,
-    ConfirmTransitVirtualInterfaceResponseTypeDef,
-    DeleteInterconnectResponseTypeDef,
-    DeleteVirtualInterfaceResponseTypeDef,
-    LoaResponseMetadataTypeDef,
     AllocateHostedConnectionRequestRequestTypeDef,
     CreateConnectionRequestRequestTypeDef,
     CreateInterconnectRequestRequestTypeDef,
     CreateLagRequestRequestTypeDef,
     InterconnectResponseMetadataTypeDef,
     InterconnectTypeDef,
     NewPrivateVirtualInterfaceAllocationTypeDef,
@@ -446,17 +449,14 @@
     CreateDirectConnectGatewayResultTypeDef,
     DeleteDirectConnectGatewayResultTypeDef,
     DescribeDirectConnectGatewaysResultTypeDef,
     UpdateDirectConnectGatewayResponseTypeDef,
     DescribeCustomerMetadataResponseTypeDef,
     DescribeConnectionLoaResponseTypeDef,
     DescribeInterconnectLoaResponseTypeDef,
-    DescribeDirectConnectGatewayAssociationsRequestDescribeDirectConnectGatewayAssociationsPaginateTypeDef,
-    DescribeDirectConnectGatewayAttachmentsRequestDescribeDirectConnectGatewayAttachmentsPaginateTypeDef,
-    DescribeDirectConnectGatewaysRequestDescribeDirectConnectGatewaysPaginateTypeDef,
     DescribeDirectConnectGatewayAttachmentsResultTypeDef,
     DescribeRouterConfigurationResponseTypeDef,
     ListVirtualInterfaceTestHistoryResponseTypeDef,
     StartBgpFailoverTestResponseTypeDef,
     StopBgpFailoverTestResponseTypeDef,
     LocationsTypeDef,
     VirtualGatewaysTypeDef,
@@ -495,43 +495,43 @@
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

### Comparing `types-aiobotocore-directconnect-2.5.0.post1/types_aiobotocore_directconnect.egg-info/SOURCES.txt` & `types-aiobotocore-directconnect-2.5.1/types_aiobotocore_directconnect.egg-info/SOURCES.txt`

 * *Files identical despite different names*

