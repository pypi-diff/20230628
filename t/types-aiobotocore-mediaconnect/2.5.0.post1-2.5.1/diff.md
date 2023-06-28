# Comparing `tmp/types-aiobotocore-mediaconnect-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediaconnect-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediaconnect-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediaconnect-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-mediaconnect-2.5.0.post1.tar` & `types-aiobotocore-mediaconnect-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.579415 types-aiobotocore-mediaconnect-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19076 2023-03-11 12:26:58.579415 types-aiobotocore-mediaconnect-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17485 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.579415 types-aiobotocore-mediaconnect-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.571415 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/
--rw-r--r--   0 runner    (1001) docker     (123)     1733 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1732 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    28227 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    28181 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10424 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10422 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5423 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5416 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    40965 2023-03-11 12:18:12.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    40908 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:10.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3403 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3400 2023-03-11 12:18:11.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.575415 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19076 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:58.000000 types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.510174 types-aiobotocore-mediaconnect-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22556 2023-06-28 01:43:49.510174 types-aiobotocore-mediaconnect-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20971 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.510174 types-aiobotocore-mediaconnect-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.510174 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/
+-rw-r--r--   0 runner    (1001) docker     (123)     2311 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2310 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42802 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42733 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11819 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11817 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8639 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8630 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    65078 2023-06-28 01:34:53.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    64987 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:51.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3403 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3400 2023-06-28 01:34:52.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.510174 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22556 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:49.000000 types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/LICENSE` & `types-aiobotocore-mediaconnect-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediaconnect-2.5.1/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediaconnect
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaConnect 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaConnect 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediaconnect"></a>
 
 # types-aiobotocore-mediaconnect
 
 [![PyPI - types-aiobotocore-mediaconnect](https://img.shields.io/pypi/v/types-aiobotocore-mediaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediaconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediaconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
+[aiobotocore.MediaConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
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
 [types-aiobotocore-mediaconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,30 +274,38 @@
 all paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_mediaconnect import MediaConnectClient
 from types_aiobotocore_mediaconnect.paginator import (
+    ListBridgesPaginator,
     ListEntitlementsPaginator,
     ListFlowsPaginator,
+    ListGatewayInstancesPaginator,
+    ListGatewaysPaginator,
     ListOfferingsPaginator,
     ListReservationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("mediaconnect") as client:
     client: MediaConnectClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
+    list_bridges_paginator: ListBridgesPaginator = client.get_paginator("list_bridges")
     list_entitlements_paginator: ListEntitlementsPaginator = client.get_paginator(
         "list_entitlements"
     )
     list_flows_paginator: ListFlowsPaginator = client.get_paginator("list_flows")
+    list_gateway_instances_paginator: ListGatewayInstancesPaginator = client.get_paginator(
+        "list_gateway_instances"
+    )
+    list_gateways_paginator: ListGatewaysPaginator = client.get_paginator("list_gateways")
     list_offerings_paginator: ListOfferingsPaginator = client.get_paginator("list_offerings")
     list_reservations_paginator: ListReservationsPaginator = client.get_paginator(
         "list_reservations"
     )
 ```
 
 <a id="waiters-annotations"></a>
@@ -334,26 +342,35 @@
 
 `types_aiobotocore_mediaconnect.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mediaconnect.literals import (
     AlgorithmType,
+    BridgePlacementType,
+    BridgeStateType,
     ColorimetryType,
+    ConnectionStatusType,
+    DesiredStateType,
     DurationUnitsType,
     EncoderProfileType,
     EncodingNameType,
     EntitlementStatusType,
     FailoverModeType,
     FlowActiveWaiterName,
     FlowDeletedWaiterName,
     FlowStandbyWaiterName,
+    GatewayStateType,
+    InstanceStateType,
     KeyTypeType,
+    ListBridgesPaginatorName,
     ListEntitlementsPaginatorName,
     ListFlowsPaginatorName,
+    ListGatewayInstancesPaginatorName,
+    ListGatewaysPaginatorName,
     ListOfferingsPaginatorName,
     ListReservationsPaginatorName,
     MaintenanceDayType,
     MediaStreamTypeType,
     NetworkInterfaceTypeType,
     PriceUnitsType,
     ProtocolType,
@@ -383,169 +400,243 @@
 ### Typed dictionaries
 
 `types_aiobotocore_mediaconnect.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediaconnect.type_defs import (
-    ResponseMetadataTypeDef,
+    VpcInterfaceAttachmentTypeDef,
+    AddBridgeNetworkOutputRequestTypeDef,
+    AddBridgeNetworkSourceRequestTypeDef,
+    AddEgressGatewayBridgeRequestTypeDef,
     VpcInterfaceRequestTypeDef,
     VpcInterfaceTypeDef,
+    AddIngressGatewayBridgeRequestTypeDef,
     AddMaintenanceTypeDef,
     EncryptionTypeDef,
-    VpcInterfaceAttachmentTypeDef,
+    BridgeFlowOutputTypeDef,
+    BridgeNetworkOutputTypeDef,
+    BridgeNetworkSourceTypeDef,
+    EgressGatewayBridgeTypeDef,
+    IngressGatewayBridgeTypeDef,
+    MessageDetailTypeDef,
+    GatewayNetworkTypeDef,
+    DeleteBridgeRequestRequestTypeDef,
+    DeleteBridgeResponseTypeDef,
     DeleteFlowRequestRequestTypeDef,
+    DeleteFlowResponseTypeDef,
+    DeleteGatewayRequestRequestTypeDef,
+    DeleteGatewayResponseTypeDef,
+    DeregisterGatewayInstanceRequestRequestTypeDef,
+    DeregisterGatewayInstanceResponseTypeDef,
+    DescribeBridgeRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeFlowRequestRequestTypeDef,
     MessagesTypeDef,
+    DescribeGatewayInstanceRequestRequestTypeDef,
+    DescribeGatewayRequestRequestTypeDef,
     DescribeOfferingRequestRequestTypeDef,
     DescribeReservationRequestRequestTypeDef,
     InterfaceRequestTypeDef,
     InterfaceTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncodingParametersRequestTypeDef,
     EncodingParametersTypeDef,
     SourcePriorityTypeDef,
     MaintenanceTypeDef,
     FmtpRequestTypeDef,
     FmtpTypeDef,
-    PaginatorConfigTypeDef,
+    ListBridgesRequestListBridgesPaginateTypeDef,
+    ListBridgesRequestRequestTypeDef,
+    ListedBridgeTypeDef,
+    ListEntitlementsRequestListEntitlementsPaginateTypeDef,
     ListEntitlementsRequestRequestTypeDef,
     ListedEntitlementTypeDef,
+    ListFlowsRequestListFlowsPaginateTypeDef,
     ListFlowsRequestRequestTypeDef,
+    ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef,
+    ListGatewayInstancesRequestRequestTypeDef,
+    ListedGatewayInstanceTypeDef,
+    ListGatewaysRequestListGatewaysPaginateTypeDef,
+    ListGatewaysRequestRequestTypeDef,
+    ListedGatewayTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListReservationsRequestListReservationsPaginateTypeDef,
     ListReservationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ResourceSpecificationTypeDef,
     TransportTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
+    RemoveBridgeOutputRequestRequestTypeDef,
+    RemoveBridgeOutputResponseTypeDef,
+    RemoveBridgeSourceRequestRequestTypeDef,
+    RemoveBridgeSourceResponseTypeDef,
     RemoveFlowMediaStreamRequestRequestTypeDef,
+    RemoveFlowMediaStreamResponseTypeDef,
     RemoveFlowOutputRequestRequestTypeDef,
+    RemoveFlowOutputResponseTypeDef,
     RemoveFlowSourceRequestRequestTypeDef,
+    RemoveFlowSourceResponseTypeDef,
     RemoveFlowVpcInterfaceRequestRequestTypeDef,
+    RemoveFlowVpcInterfaceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RevokeFlowEntitlementRequestRequestTypeDef,
+    RevokeFlowEntitlementResponseTypeDef,
     StartFlowRequestRequestTypeDef,
+    StartFlowResponseTypeDef,
     StopFlowRequestRequestTypeDef,
+    StopFlowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateBridgeNetworkOutputRequestTypeDef,
+    UpdateBridgeNetworkSourceRequestTypeDef,
+    UpdateEgressGatewayBridgeRequestTypeDef,
+    UpdateIngressGatewayBridgeRequestTypeDef,
+    UpdateBridgeStateRequestRequestTypeDef,
+    UpdateBridgeStateResponseTypeDef,
     UpdateEncryptionTypeDef,
     UpdateMaintenanceTypeDef,
-    DeleteFlowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RemoveFlowMediaStreamResponseTypeDef,
-    RemoveFlowOutputResponseTypeDef,
-    RemoveFlowSourceResponseTypeDef,
-    RemoveFlowVpcInterfaceResponseTypeDef,
-    RevokeFlowEntitlementResponseTypeDef,
-    StartFlowResponseTypeDef,
-    StopFlowResponseTypeDef,
+    UpdateGatewayInstanceRequestRequestTypeDef,
+    UpdateGatewayInstanceResponseTypeDef,
+    AddBridgeFlowSourceRequestTypeDef,
+    BridgeFlowSourceTypeDef,
+    GatewayBridgeSourceTypeDef,
+    SetGatewayBridgeSourceRequestTypeDef,
+    UpdateBridgeFlowSourceRequestTypeDef,
+    UpdateGatewayBridgeSourceRequestTypeDef,
+    AddBridgeOutputRequestTypeDef,
     AddFlowVpcInterfacesRequestRequestTypeDef,
     AddFlowVpcInterfacesResponseTypeDef,
     EntitlementTypeDef,
     GrantEntitlementRequestTypeDef,
+    BridgeOutputTypeDef,
+    GatewayInstanceTypeDef,
+    CreateGatewayRequestRequestTypeDef,
+    GatewayTypeDef,
     DescribeFlowRequestFlowActiveWaitTypeDef,
     DescribeFlowRequestFlowDeletedWaitTypeDef,
     DescribeFlowRequestFlowStandbyWaitTypeDef,
     DestinationConfigurationRequestTypeDef,
     InputConfigurationRequestTypeDef,
     DestinationConfigurationTypeDef,
     InputConfigurationTypeDef,
     FailoverConfigTypeDef,
     UpdateFailoverConfigTypeDef,
     ListedFlowTypeDef,
     MediaStreamAttributesRequestTypeDef,
     MediaStreamAttributesTypeDef,
-    ListEntitlementsRequestListEntitlementsPaginateTypeDef,
-    ListFlowsRequestListFlowsPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListReservationsRequestListReservationsPaginateTypeDef,
+    ListBridgesResponseTypeDef,
     ListEntitlementsResponseTypeDef,
+    ListGatewayInstancesResponseTypeDef,
+    ListGatewaysResponseTypeDef,
     OfferingTypeDef,
     ReservationTypeDef,
+    UpdateBridgeOutputRequestRequestTypeDef,
     UpdateFlowEntitlementRequestRequestTypeDef,
+    AddBridgeSourceRequestTypeDef,
+    BridgeSourceTypeDef,
+    UpdateBridgeSourceRequestRequestTypeDef,
+    AddBridgeOutputsRequestRequestTypeDef,
     GrantFlowEntitlementsResponseTypeDef,
     UpdateFlowEntitlementResponseTypeDef,
     GrantFlowEntitlementsRequestRequestTypeDef,
+    AddBridgeOutputsResponseTypeDef,
+    UpdateBridgeOutputResponseTypeDef,
+    DescribeGatewayInstanceResponseTypeDef,
+    CreateGatewayResponseTypeDef,
+    DescribeGatewayResponseTypeDef,
     MediaStreamOutputConfigurationRequestTypeDef,
     MediaStreamSourceConfigurationRequestTypeDef,
     MediaStreamOutputConfigurationTypeDef,
     MediaStreamSourceConfigurationTypeDef,
+    UpdateBridgeRequestRequestTypeDef,
     UpdateFlowRequestRequestTypeDef,
     ListFlowsResponseTypeDef,
     AddMediaStreamRequestTypeDef,
     UpdateFlowMediaStreamRequestRequestTypeDef,
     MediaStreamTypeDef,
     DescribeOfferingResponseTypeDef,
     ListOfferingsResponseTypeDef,
     DescribeReservationResponseTypeDef,
     ListReservationsResponseTypeDef,
     PurchaseOfferingResponseTypeDef,
+    AddBridgeSourcesRequestRequestTypeDef,
+    CreateBridgeRequestRequestTypeDef,
+    AddBridgeSourcesResponseTypeDef,
+    BridgeTypeDef,
+    UpdateBridgeSourceResponseTypeDef,
     AddOutputRequestTypeDef,
     UpdateFlowOutputRequestRequestTypeDef,
     SetSourceRequestTypeDef,
     UpdateFlowSourceRequestRequestTypeDef,
     OutputTypeDef,
     SourceTypeDef,
     AddFlowMediaStreamsRequestRequestTypeDef,
     AddFlowMediaStreamsResponseTypeDef,
     UpdateFlowMediaStreamResponseTypeDef,
+    CreateBridgeResponseTypeDef,
+    DescribeBridgeResponseTypeDef,
+    UpdateBridgeResponseTypeDef,
     AddFlowOutputsRequestRequestTypeDef,
     AddFlowSourcesRequestRequestTypeDef,
     CreateFlowRequestRequestTypeDef,
     AddFlowOutputsResponseTypeDef,
     UpdateFlowOutputResponseTypeDef,
     AddFlowSourcesResponseTypeDef,
     FlowTypeDef,
     UpdateFlowSourceResponseTypeDef,
     CreateFlowResponseTypeDef,
     DescribeFlowResponseTypeDef,
     UpdateFlowResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> VpcInterfaceAttachmentTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/README.md` & `types-aiobotocore-mediaconnect-2.5.1/README.md`

 * *Files 22% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediaconnect"></a>
 
 # types-aiobotocore-mediaconnect
 
 [![PyPI - types-aiobotocore-mediaconnect](https://img.shields.io/pypi/v/types-aiobotocore-mediaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediaconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediaconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
+[aiobotocore.MediaConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
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
 [types-aiobotocore-mediaconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -241,30 +241,38 @@
 all paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_mediaconnect import MediaConnectClient
 from types_aiobotocore_mediaconnect.paginator import (
+    ListBridgesPaginator,
     ListEntitlementsPaginator,
     ListFlowsPaginator,
+    ListGatewayInstancesPaginator,
+    ListGatewaysPaginator,
     ListOfferingsPaginator,
     ListReservationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("mediaconnect") as client:
     client: MediaConnectClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
+    list_bridges_paginator: ListBridgesPaginator = client.get_paginator("list_bridges")
     list_entitlements_paginator: ListEntitlementsPaginator = client.get_paginator(
         "list_entitlements"
     )
     list_flows_paginator: ListFlowsPaginator = client.get_paginator("list_flows")
+    list_gateway_instances_paginator: ListGatewayInstancesPaginator = client.get_paginator(
+        "list_gateway_instances"
+    )
+    list_gateways_paginator: ListGatewaysPaginator = client.get_paginator("list_gateways")
     list_offerings_paginator: ListOfferingsPaginator = client.get_paginator("list_offerings")
     list_reservations_paginator: ListReservationsPaginator = client.get_paginator(
         "list_reservations"
     )
 ```
 
 <a id="waiters-annotations"></a>
@@ -301,26 +309,35 @@
 
 `types_aiobotocore_mediaconnect.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mediaconnect.literals import (
     AlgorithmType,
+    BridgePlacementType,
+    BridgeStateType,
     ColorimetryType,
+    ConnectionStatusType,
+    DesiredStateType,
     DurationUnitsType,
     EncoderProfileType,
     EncodingNameType,
     EntitlementStatusType,
     FailoverModeType,
     FlowActiveWaiterName,
     FlowDeletedWaiterName,
     FlowStandbyWaiterName,
+    GatewayStateType,
+    InstanceStateType,
     KeyTypeType,
+    ListBridgesPaginatorName,
     ListEntitlementsPaginatorName,
     ListFlowsPaginatorName,
+    ListGatewayInstancesPaginatorName,
+    ListGatewaysPaginatorName,
     ListOfferingsPaginatorName,
     ListReservationsPaginatorName,
     MaintenanceDayType,
     MediaStreamTypeType,
     NetworkInterfaceTypeType,
     PriceUnitsType,
     ProtocolType,
@@ -350,169 +367,243 @@
 ### Typed dictionaries
 
 `types_aiobotocore_mediaconnect.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediaconnect.type_defs import (
-    ResponseMetadataTypeDef,
+    VpcInterfaceAttachmentTypeDef,
+    AddBridgeNetworkOutputRequestTypeDef,
+    AddBridgeNetworkSourceRequestTypeDef,
+    AddEgressGatewayBridgeRequestTypeDef,
     VpcInterfaceRequestTypeDef,
     VpcInterfaceTypeDef,
+    AddIngressGatewayBridgeRequestTypeDef,
     AddMaintenanceTypeDef,
     EncryptionTypeDef,
-    VpcInterfaceAttachmentTypeDef,
+    BridgeFlowOutputTypeDef,
+    BridgeNetworkOutputTypeDef,
+    BridgeNetworkSourceTypeDef,
+    EgressGatewayBridgeTypeDef,
+    IngressGatewayBridgeTypeDef,
+    MessageDetailTypeDef,
+    GatewayNetworkTypeDef,
+    DeleteBridgeRequestRequestTypeDef,
+    DeleteBridgeResponseTypeDef,
     DeleteFlowRequestRequestTypeDef,
+    DeleteFlowResponseTypeDef,
+    DeleteGatewayRequestRequestTypeDef,
+    DeleteGatewayResponseTypeDef,
+    DeregisterGatewayInstanceRequestRequestTypeDef,
+    DeregisterGatewayInstanceResponseTypeDef,
+    DescribeBridgeRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeFlowRequestRequestTypeDef,
     MessagesTypeDef,
+    DescribeGatewayInstanceRequestRequestTypeDef,
+    DescribeGatewayRequestRequestTypeDef,
     DescribeOfferingRequestRequestTypeDef,
     DescribeReservationRequestRequestTypeDef,
     InterfaceRequestTypeDef,
     InterfaceTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncodingParametersRequestTypeDef,
     EncodingParametersTypeDef,
     SourcePriorityTypeDef,
     MaintenanceTypeDef,
     FmtpRequestTypeDef,
     FmtpTypeDef,
-    PaginatorConfigTypeDef,
+    ListBridgesRequestListBridgesPaginateTypeDef,
+    ListBridgesRequestRequestTypeDef,
+    ListedBridgeTypeDef,
+    ListEntitlementsRequestListEntitlementsPaginateTypeDef,
     ListEntitlementsRequestRequestTypeDef,
     ListedEntitlementTypeDef,
+    ListFlowsRequestListFlowsPaginateTypeDef,
     ListFlowsRequestRequestTypeDef,
+    ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef,
+    ListGatewayInstancesRequestRequestTypeDef,
+    ListedGatewayInstanceTypeDef,
+    ListGatewaysRequestListGatewaysPaginateTypeDef,
+    ListGatewaysRequestRequestTypeDef,
+    ListedGatewayTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListReservationsRequestListReservationsPaginateTypeDef,
     ListReservationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ResourceSpecificationTypeDef,
     TransportTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
+    RemoveBridgeOutputRequestRequestTypeDef,
+    RemoveBridgeOutputResponseTypeDef,
+    RemoveBridgeSourceRequestRequestTypeDef,
+    RemoveBridgeSourceResponseTypeDef,
     RemoveFlowMediaStreamRequestRequestTypeDef,
+    RemoveFlowMediaStreamResponseTypeDef,
     RemoveFlowOutputRequestRequestTypeDef,
+    RemoveFlowOutputResponseTypeDef,
     RemoveFlowSourceRequestRequestTypeDef,
+    RemoveFlowSourceResponseTypeDef,
     RemoveFlowVpcInterfaceRequestRequestTypeDef,
+    RemoveFlowVpcInterfaceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RevokeFlowEntitlementRequestRequestTypeDef,
+    RevokeFlowEntitlementResponseTypeDef,
     StartFlowRequestRequestTypeDef,
+    StartFlowResponseTypeDef,
     StopFlowRequestRequestTypeDef,
+    StopFlowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateBridgeNetworkOutputRequestTypeDef,
+    UpdateBridgeNetworkSourceRequestTypeDef,
+    UpdateEgressGatewayBridgeRequestTypeDef,
+    UpdateIngressGatewayBridgeRequestTypeDef,
+    UpdateBridgeStateRequestRequestTypeDef,
+    UpdateBridgeStateResponseTypeDef,
     UpdateEncryptionTypeDef,
     UpdateMaintenanceTypeDef,
-    DeleteFlowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RemoveFlowMediaStreamResponseTypeDef,
-    RemoveFlowOutputResponseTypeDef,
-    RemoveFlowSourceResponseTypeDef,
-    RemoveFlowVpcInterfaceResponseTypeDef,
-    RevokeFlowEntitlementResponseTypeDef,
-    StartFlowResponseTypeDef,
-    StopFlowResponseTypeDef,
+    UpdateGatewayInstanceRequestRequestTypeDef,
+    UpdateGatewayInstanceResponseTypeDef,
+    AddBridgeFlowSourceRequestTypeDef,
+    BridgeFlowSourceTypeDef,
+    GatewayBridgeSourceTypeDef,
+    SetGatewayBridgeSourceRequestTypeDef,
+    UpdateBridgeFlowSourceRequestTypeDef,
+    UpdateGatewayBridgeSourceRequestTypeDef,
+    AddBridgeOutputRequestTypeDef,
     AddFlowVpcInterfacesRequestRequestTypeDef,
     AddFlowVpcInterfacesResponseTypeDef,
     EntitlementTypeDef,
     GrantEntitlementRequestTypeDef,
+    BridgeOutputTypeDef,
+    GatewayInstanceTypeDef,
+    CreateGatewayRequestRequestTypeDef,
+    GatewayTypeDef,
     DescribeFlowRequestFlowActiveWaitTypeDef,
     DescribeFlowRequestFlowDeletedWaitTypeDef,
     DescribeFlowRequestFlowStandbyWaitTypeDef,
     DestinationConfigurationRequestTypeDef,
     InputConfigurationRequestTypeDef,
     DestinationConfigurationTypeDef,
     InputConfigurationTypeDef,
     FailoverConfigTypeDef,
     UpdateFailoverConfigTypeDef,
     ListedFlowTypeDef,
     MediaStreamAttributesRequestTypeDef,
     MediaStreamAttributesTypeDef,
-    ListEntitlementsRequestListEntitlementsPaginateTypeDef,
-    ListFlowsRequestListFlowsPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListReservationsRequestListReservationsPaginateTypeDef,
+    ListBridgesResponseTypeDef,
     ListEntitlementsResponseTypeDef,
+    ListGatewayInstancesResponseTypeDef,
+    ListGatewaysResponseTypeDef,
     OfferingTypeDef,
     ReservationTypeDef,
+    UpdateBridgeOutputRequestRequestTypeDef,
     UpdateFlowEntitlementRequestRequestTypeDef,
+    AddBridgeSourceRequestTypeDef,
+    BridgeSourceTypeDef,
+    UpdateBridgeSourceRequestRequestTypeDef,
+    AddBridgeOutputsRequestRequestTypeDef,
     GrantFlowEntitlementsResponseTypeDef,
     UpdateFlowEntitlementResponseTypeDef,
     GrantFlowEntitlementsRequestRequestTypeDef,
+    AddBridgeOutputsResponseTypeDef,
+    UpdateBridgeOutputResponseTypeDef,
+    DescribeGatewayInstanceResponseTypeDef,
+    CreateGatewayResponseTypeDef,
+    DescribeGatewayResponseTypeDef,
     MediaStreamOutputConfigurationRequestTypeDef,
     MediaStreamSourceConfigurationRequestTypeDef,
     MediaStreamOutputConfigurationTypeDef,
     MediaStreamSourceConfigurationTypeDef,
+    UpdateBridgeRequestRequestTypeDef,
     UpdateFlowRequestRequestTypeDef,
     ListFlowsResponseTypeDef,
     AddMediaStreamRequestTypeDef,
     UpdateFlowMediaStreamRequestRequestTypeDef,
     MediaStreamTypeDef,
     DescribeOfferingResponseTypeDef,
     ListOfferingsResponseTypeDef,
     DescribeReservationResponseTypeDef,
     ListReservationsResponseTypeDef,
     PurchaseOfferingResponseTypeDef,
+    AddBridgeSourcesRequestRequestTypeDef,
+    CreateBridgeRequestRequestTypeDef,
+    AddBridgeSourcesResponseTypeDef,
+    BridgeTypeDef,
+    UpdateBridgeSourceResponseTypeDef,
     AddOutputRequestTypeDef,
     UpdateFlowOutputRequestRequestTypeDef,
     SetSourceRequestTypeDef,
     UpdateFlowSourceRequestRequestTypeDef,
     OutputTypeDef,
     SourceTypeDef,
     AddFlowMediaStreamsRequestRequestTypeDef,
     AddFlowMediaStreamsResponseTypeDef,
     UpdateFlowMediaStreamResponseTypeDef,
+    CreateBridgeResponseTypeDef,
+    DescribeBridgeResponseTypeDef,
+    UpdateBridgeResponseTypeDef,
     AddFlowOutputsRequestRequestTypeDef,
     AddFlowSourcesRequestRequestTypeDef,
     CreateFlowRequestRequestTypeDef,
     AddFlowOutputsResponseTypeDef,
     UpdateFlowOutputResponseTypeDef,
     AddFlowSourcesResponseTypeDef,
     FlowTypeDef,
     UpdateFlowSourceResponseTypeDef,
     CreateFlowResponseTypeDef,
     DescribeFlowResponseTypeDef,
     UpdateFlowResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> VpcInterfaceAttachmentTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/setup.py` & `types-aiobotocore-mediaconnect-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediaconnect.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediaconnect",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediaconnect"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaConnect 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaConnect 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/"
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

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/__main__.py` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaConnect 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaConnect 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect\nOther"
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

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/client.py` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/client.py`

 * *Files 22% similar despite different names*

```diff
@@ -16,62 +16,102 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import EntitlementStatusType, MediaStreamTypeType, ProtocolType
+from .literals import (
+    BridgePlacementType,
+    DesiredStateType,
+    EntitlementStatusType,
+    MediaStreamTypeType,
+    ProtocolType,
+)
 from .paginator import (
+    ListBridgesPaginator,
     ListEntitlementsPaginator,
     ListFlowsPaginator,
+    ListGatewayInstancesPaginator,
+    ListGatewaysPaginator,
     ListOfferingsPaginator,
     ListReservationsPaginator,
 )
 from .type_defs import (
+    AddBridgeOutputRequestTypeDef,
+    AddBridgeOutputsResponseTypeDef,
+    AddBridgeSourceRequestTypeDef,
+    AddBridgeSourcesResponseTypeDef,
+    AddEgressGatewayBridgeRequestTypeDef,
     AddFlowMediaStreamsResponseTypeDef,
     AddFlowOutputsResponseTypeDef,
     AddFlowSourcesResponseTypeDef,
     AddFlowVpcInterfacesResponseTypeDef,
+    AddIngressGatewayBridgeRequestTypeDef,
     AddMaintenanceTypeDef,
     AddMediaStreamRequestTypeDef,
     AddOutputRequestTypeDef,
+    CreateBridgeResponseTypeDef,
     CreateFlowResponseTypeDef,
+    CreateGatewayResponseTypeDef,
+    DeleteBridgeResponseTypeDef,
     DeleteFlowResponseTypeDef,
+    DeleteGatewayResponseTypeDef,
+    DeregisterGatewayInstanceResponseTypeDef,
+    DescribeBridgeResponseTypeDef,
     DescribeFlowResponseTypeDef,
+    DescribeGatewayInstanceResponseTypeDef,
+    DescribeGatewayResponseTypeDef,
     DescribeOfferingResponseTypeDef,
     DescribeReservationResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     FailoverConfigTypeDef,
+    GatewayNetworkTypeDef,
     GrantEntitlementRequestTypeDef,
     GrantFlowEntitlementsResponseTypeDef,
+    ListBridgesResponseTypeDef,
     ListEntitlementsResponseTypeDef,
     ListFlowsResponseTypeDef,
+    ListGatewayInstancesResponseTypeDef,
+    ListGatewaysResponseTypeDef,
     ListOfferingsResponseTypeDef,
     ListReservationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     MediaStreamAttributesRequestTypeDef,
     MediaStreamOutputConfigurationRequestTypeDef,
     MediaStreamSourceConfigurationRequestTypeDef,
     PurchaseOfferingResponseTypeDef,
+    RemoveBridgeOutputResponseTypeDef,
+    RemoveBridgeSourceResponseTypeDef,
     RemoveFlowMediaStreamResponseTypeDef,
     RemoveFlowOutputResponseTypeDef,
     RemoveFlowSourceResponseTypeDef,
     RemoveFlowVpcInterfaceResponseTypeDef,
     RevokeFlowEntitlementResponseTypeDef,
     SetSourceRequestTypeDef,
     StartFlowResponseTypeDef,
     StopFlowResponseTypeDef,
+    UpdateBridgeFlowSourceRequestTypeDef,
+    UpdateBridgeNetworkOutputRequestTypeDef,
+    UpdateBridgeNetworkSourceRequestTypeDef,
+    UpdateBridgeOutputResponseTypeDef,
+    UpdateBridgeResponseTypeDef,
+    UpdateBridgeSourceResponseTypeDef,
+    UpdateBridgeStateResponseTypeDef,
+    UpdateEgressGatewayBridgeRequestTypeDef,
     UpdateEncryptionTypeDef,
     UpdateFailoverConfigTypeDef,
     UpdateFlowEntitlementResponseTypeDef,
     UpdateFlowMediaStreamResponseTypeDef,
     UpdateFlowOutputResponseTypeDef,
     UpdateFlowResponseTypeDef,
     UpdateFlowSourceResponseTypeDef,
+    UpdateGatewayBridgeSourceRequestTypeDef,
+    UpdateGatewayInstanceResponseTypeDef,
+    UpdateIngressGatewayBridgeRequestTypeDef,
     UpdateMaintenanceTypeDef,
     VpcInterfaceAttachmentTypeDef,
     VpcInterfaceRequestTypeDef,
 )
 from .waiter import FlowActiveWaiter, FlowDeletedWaiter, FlowStandbyWaiter
 
 if sys.version_info >= (3, 9):
@@ -91,15 +131,18 @@
         self.operation_name: str
 
 
 class Exceptions:
     AddFlowOutputs420Exception: Type[BotocoreClientError]
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
+    CreateBridge420Exception: Type[BotocoreClientError]
     CreateFlow420Exception: Type[BotocoreClientError]
+    CreateGateway420Exception: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
     GrantFlowEntitlements420Exception: Type[BotocoreClientError]
     InternalServerErrorException: Type[BotocoreClientError]
     NotFoundException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
 
@@ -117,14 +160,34 @@
         """
         MediaConnectClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#exceptions)
         """
 
+    async def add_bridge_outputs(
+        self, *, BridgeArn: str, Outputs: Sequence[AddBridgeOutputRequestTypeDef]
+    ) -> AddBridgeOutputsResponseTypeDef:
+        """
+        Adds outputs to an existing bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_bridge_outputs)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#add_bridge_outputs)
+        """
+
+    async def add_bridge_sources(
+        self, *, BridgeArn: str, Sources: Sequence[AddBridgeSourceRequestTypeDef]
+    ) -> AddBridgeSourcesResponseTypeDef:
+        """
+        Adds sources to an existing bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_bridge_sources)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#add_bridge_sources)
+        """
+
     async def add_flow_media_streams(
         self, *, FlowArn: str, MediaStreams: Sequence[AddMediaStreamRequestTypeDef]
     ) -> AddFlowMediaStreamsResponseTypeDef:
         """
         Adds media streams to an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_flow_media_streams)
@@ -175,14 +238,32 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#close)
         """
 
+    async def create_bridge(
+        self,
+        *,
+        Name: str,
+        PlacementArn: str,
+        Sources: Sequence[AddBridgeSourceRequestTypeDef],
+        EgressGatewayBridge: AddEgressGatewayBridgeRequestTypeDef = ...,
+        IngressGatewayBridge: AddIngressGatewayBridgeRequestTypeDef = ...,
+        Outputs: Sequence[AddBridgeOutputRequestTypeDef] = ...,
+        SourceFailoverConfig: FailoverConfigTypeDef = ...
+    ) -> CreateBridgeResponseTypeDef:
+        """
+        Creates a new bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#create_bridge)
+        """
+
     async def create_flow(
         self,
         *,
         Name: str,
         AvailabilityZone: str = ...,
         Entitlements: Sequence[GrantEntitlementRequestTypeDef] = ...,
         MediaStreams: Sequence[AddMediaStreamRequestTypeDef] = ...,
@@ -196,30 +277,96 @@
         """
         Creates a new flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#create_flow)
         """
 
+    async def create_gateway(
+        self,
+        *,
+        EgressCidrBlocks: Sequence[str],
+        Name: str,
+        Networks: Sequence[GatewayNetworkTypeDef]
+    ) -> CreateGatewayResponseTypeDef:
+        """
+        Creates a new gateway.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_gateway)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#create_gateway)
+        """
+
+    async def delete_bridge(self, *, BridgeArn: str) -> DeleteBridgeResponseTypeDef:
+        """
+        Deletes a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#delete_bridge)
+        """
+
     async def delete_flow(self, *, FlowArn: str) -> DeleteFlowResponseTypeDef:
         """
         Deletes a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#delete_flow)
         """
 
+    async def delete_gateway(self, *, GatewayArn: str) -> DeleteGatewayResponseTypeDef:
+        """
+        Deletes a gateway.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_gateway)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#delete_gateway)
+        """
+
+    async def deregister_gateway_instance(
+        self, *, GatewayInstanceArn: str, Force: bool = ...
+    ) -> DeregisterGatewayInstanceResponseTypeDef:
+        """
+        Deregisters an instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.deregister_gateway_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#deregister_gateway_instance)
+        """
+
+    async def describe_bridge(self, *, BridgeArn: str) -> DescribeBridgeResponseTypeDef:
+        """
+        Displays the details of a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_bridge)
+        """
+
     async def describe_flow(self, *, FlowArn: str) -> DescribeFlowResponseTypeDef:
         """
         Displays the details of a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_flow)
         """
 
+    async def describe_gateway(self, *, GatewayArn: str) -> DescribeGatewayResponseTypeDef:
+        """
+        Displays the details of a gateway.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_gateway)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_gateway)
+        """
+
+    async def describe_gateway_instance(
+        self, *, GatewayInstanceArn: str
+    ) -> DescribeGatewayInstanceResponseTypeDef:
+        """
+        Displays the details of an instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_gateway_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_gateway_instance)
+        """
+
     async def describe_offering(self, *, OfferingArn: str) -> DescribeOfferingResponseTypeDef:
         """
         Displays the details of an offering.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_offering)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_offering)
         """
@@ -254,14 +401,25 @@
         """
         Grants entitlements to an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.grant_flow_entitlements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#grant_flow_entitlements)
         """
 
+    async def list_bridges(
+        self, *, FilterArn: str = ..., MaxResults: int = ..., NextToken: str = ...
+    ) -> ListBridgesResponseTypeDef:
+        """
+        Displays a list of bridges that are associated with this account and an
+        optionally specified Arn.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_bridges)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_bridges)
+        """
+
     async def list_entitlements(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListEntitlementsResponseTypeDef:
         """
         Displays a list of all entitlements that have been granted to this account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_entitlements)
@@ -274,14 +432,34 @@
         """
         Displays a list of flows that are associated with this account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_flows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_flows)
         """
 
+    async def list_gateway_instances(
+        self, *, FilterArn: str = ..., MaxResults: int = ..., NextToken: str = ...
+    ) -> ListGatewayInstancesResponseTypeDef:
+        """
+        Displays a list of instances associated with the AWS account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_gateway_instances)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_gateway_instances)
+        """
+
+    async def list_gateways(
+        self, *, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListGatewaysResponseTypeDef:
+        """
+        Displays a list of gateways that are associated with this account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_gateways)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_gateways)
+        """
+
     async def list_offerings(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListOfferingsResponseTypeDef:
         """
         Displays a list of all offerings that are available to this account in the
         current AWS Region.
 
@@ -317,14 +495,34 @@
         """
         Submits a request to purchase an offering.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.purchase_offering)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#purchase_offering)
         """
 
+    async def remove_bridge_output(
+        self, *, BridgeArn: str, OutputName: str
+    ) -> RemoveBridgeOutputResponseTypeDef:
+        """
+        Removes an output from a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_bridge_output)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#remove_bridge_output)
+        """
+
+    async def remove_bridge_source(
+        self, *, BridgeArn: str, SourceName: str
+    ) -> RemoveBridgeSourceResponseTypeDef:
+        """
+        Removes a source from a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_bridge_source)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#remove_bridge_source)
+        """
+
     async def remove_flow_media_stream(
         self, *, FlowArn: str, MediaStreamName: str
     ) -> RemoveFlowMediaStreamResponseTypeDef:
         """
         Removes a media stream from a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_flow_media_stream)
@@ -403,14 +601,70 @@
         """
         Deletes specified tags from a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#untag_resource)
         """
 
+    async def update_bridge(
+        self,
+        *,
+        BridgeArn: str,
+        EgressGatewayBridge: UpdateEgressGatewayBridgeRequestTypeDef = ...,
+        IngressGatewayBridge: UpdateIngressGatewayBridgeRequestTypeDef = ...,
+        SourceFailoverConfig: UpdateFailoverConfigTypeDef = ...
+    ) -> UpdateBridgeResponseTypeDef:
+        """
+        Updates the bridge See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/UpdateBridge).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge)
+        """
+
+    async def update_bridge_output(
+        self,
+        *,
+        BridgeArn: str,
+        OutputName: str,
+        NetworkOutput: UpdateBridgeNetworkOutputRequestTypeDef = ...
+    ) -> UpdateBridgeOutputResponseTypeDef:
+        """
+        Updates an existing bridge output.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge_output)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge_output)
+        """
+
+    async def update_bridge_source(
+        self,
+        *,
+        BridgeArn: str,
+        SourceName: str,
+        FlowSource: UpdateBridgeFlowSourceRequestTypeDef = ...,
+        NetworkSource: UpdateBridgeNetworkSourceRequestTypeDef = ...
+    ) -> UpdateBridgeSourceResponseTypeDef:
+        """
+        Updates an existing bridge source.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge_source)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge_source)
+        """
+
+    async def update_bridge_state(
+        self, *, BridgeArn: str, DesiredState: DesiredStateType
+    ) -> UpdateBridgeStateResponseTypeDef:
+        """
+        Updates the bridge state See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/UpdateBridgeState).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge_state)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge_state)
+        """
+
     async def update_flow(
         self,
         *,
         FlowArn: str,
         SourceFailoverConfig: UpdateFailoverConfigTypeDef = ...,
         Maintenance: UpdateMaintenanceTypeDef = ...
     ) -> UpdateFlowResponseTypeDef:
@@ -506,23 +760,41 @@
         Protocol: ProtocolType = ...,
         SenderControlPort: int = ...,
         SenderIpAddress: str = ...,
         SourceListenerAddress: str = ...,
         SourceListenerPort: int = ...,
         StreamId: str = ...,
         VpcInterfaceName: str = ...,
-        WhitelistCidr: str = ...
+        WhitelistCidr: str = ...,
+        GatewayBridgeSource: UpdateGatewayBridgeSourceRequestTypeDef = ...
     ) -> UpdateFlowSourceResponseTypeDef:
         """
         Updates the source of a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_flow_source)
         """
 
+    async def update_gateway_instance(
+        self, *, GatewayInstanceArn: str, BridgePlacement: BridgePlacementType = ...
+    ) -> UpdateGatewayInstanceResponseTypeDef:
+        """
+        Updates the configuration of an existing Gateway Instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_gateway_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_gateway_instance)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_bridges"]) -> ListBridgesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_entitlements"]
     ) -> ListEntitlementsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
@@ -532,14 +804,30 @@
     def get_paginator(self, operation_name: Literal["list_flows"]) -> ListFlowsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_gateway_instances"]
+    ) -> ListGatewayInstancesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_gateways"]) -> ListGatewaysPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_offerings"]) -> ListOfferingsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
         """
 
     @overload
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/client.pyi` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/client.pyi`

 * *Files 22% similar despite different names*

```diff
@@ -16,62 +16,102 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import EntitlementStatusType, MediaStreamTypeType, ProtocolType
+from .literals import (
+    BridgePlacementType,
+    DesiredStateType,
+    EntitlementStatusType,
+    MediaStreamTypeType,
+    ProtocolType,
+)
 from .paginator import (
+    ListBridgesPaginator,
     ListEntitlementsPaginator,
     ListFlowsPaginator,
+    ListGatewayInstancesPaginator,
+    ListGatewaysPaginator,
     ListOfferingsPaginator,
     ListReservationsPaginator,
 )
 from .type_defs import (
+    AddBridgeOutputRequestTypeDef,
+    AddBridgeOutputsResponseTypeDef,
+    AddBridgeSourceRequestTypeDef,
+    AddBridgeSourcesResponseTypeDef,
+    AddEgressGatewayBridgeRequestTypeDef,
     AddFlowMediaStreamsResponseTypeDef,
     AddFlowOutputsResponseTypeDef,
     AddFlowSourcesResponseTypeDef,
     AddFlowVpcInterfacesResponseTypeDef,
+    AddIngressGatewayBridgeRequestTypeDef,
     AddMaintenanceTypeDef,
     AddMediaStreamRequestTypeDef,
     AddOutputRequestTypeDef,
+    CreateBridgeResponseTypeDef,
     CreateFlowResponseTypeDef,
+    CreateGatewayResponseTypeDef,
+    DeleteBridgeResponseTypeDef,
     DeleteFlowResponseTypeDef,
+    DeleteGatewayResponseTypeDef,
+    DeregisterGatewayInstanceResponseTypeDef,
+    DescribeBridgeResponseTypeDef,
     DescribeFlowResponseTypeDef,
+    DescribeGatewayInstanceResponseTypeDef,
+    DescribeGatewayResponseTypeDef,
     DescribeOfferingResponseTypeDef,
     DescribeReservationResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     FailoverConfigTypeDef,
+    GatewayNetworkTypeDef,
     GrantEntitlementRequestTypeDef,
     GrantFlowEntitlementsResponseTypeDef,
+    ListBridgesResponseTypeDef,
     ListEntitlementsResponseTypeDef,
     ListFlowsResponseTypeDef,
+    ListGatewayInstancesResponseTypeDef,
+    ListGatewaysResponseTypeDef,
     ListOfferingsResponseTypeDef,
     ListReservationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     MediaStreamAttributesRequestTypeDef,
     MediaStreamOutputConfigurationRequestTypeDef,
     MediaStreamSourceConfigurationRequestTypeDef,
     PurchaseOfferingResponseTypeDef,
+    RemoveBridgeOutputResponseTypeDef,
+    RemoveBridgeSourceResponseTypeDef,
     RemoveFlowMediaStreamResponseTypeDef,
     RemoveFlowOutputResponseTypeDef,
     RemoveFlowSourceResponseTypeDef,
     RemoveFlowVpcInterfaceResponseTypeDef,
     RevokeFlowEntitlementResponseTypeDef,
     SetSourceRequestTypeDef,
     StartFlowResponseTypeDef,
     StopFlowResponseTypeDef,
+    UpdateBridgeFlowSourceRequestTypeDef,
+    UpdateBridgeNetworkOutputRequestTypeDef,
+    UpdateBridgeNetworkSourceRequestTypeDef,
+    UpdateBridgeOutputResponseTypeDef,
+    UpdateBridgeResponseTypeDef,
+    UpdateBridgeSourceResponseTypeDef,
+    UpdateBridgeStateResponseTypeDef,
+    UpdateEgressGatewayBridgeRequestTypeDef,
     UpdateEncryptionTypeDef,
     UpdateFailoverConfigTypeDef,
     UpdateFlowEntitlementResponseTypeDef,
     UpdateFlowMediaStreamResponseTypeDef,
     UpdateFlowOutputResponseTypeDef,
     UpdateFlowResponseTypeDef,
     UpdateFlowSourceResponseTypeDef,
+    UpdateGatewayBridgeSourceRequestTypeDef,
+    UpdateGatewayInstanceResponseTypeDef,
+    UpdateIngressGatewayBridgeRequestTypeDef,
     UpdateMaintenanceTypeDef,
     VpcInterfaceAttachmentTypeDef,
     VpcInterfaceRequestTypeDef,
 )
 from .waiter import FlowActiveWaiter, FlowDeletedWaiter, FlowStandbyWaiter
 
 if sys.version_info >= (3, 9):
@@ -88,15 +128,18 @@
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
     AddFlowOutputs420Exception: Type[BotocoreClientError]
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
+    CreateBridge420Exception: Type[BotocoreClientError]
     CreateFlow420Exception: Type[BotocoreClientError]
+    CreateGateway420Exception: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
     GrantFlowEntitlements420Exception: Type[BotocoreClientError]
     InternalServerErrorException: Type[BotocoreClientError]
     NotFoundException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
 
@@ -112,14 +155,32 @@
     def exceptions(self) -> Exceptions:
         """
         MediaConnectClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#exceptions)
         """
+    async def add_bridge_outputs(
+        self, *, BridgeArn: str, Outputs: Sequence[AddBridgeOutputRequestTypeDef]
+    ) -> AddBridgeOutputsResponseTypeDef:
+        """
+        Adds outputs to an existing bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_bridge_outputs)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#add_bridge_outputs)
+        """
+    async def add_bridge_sources(
+        self, *, BridgeArn: str, Sources: Sequence[AddBridgeSourceRequestTypeDef]
+    ) -> AddBridgeSourcesResponseTypeDef:
+        """
+        Adds sources to an existing bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_bridge_sources)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#add_bridge_sources)
+        """
     async def add_flow_media_streams(
         self, *, FlowArn: str, MediaStreams: Sequence[AddMediaStreamRequestTypeDef]
     ) -> AddFlowMediaStreamsResponseTypeDef:
         """
         Adds media streams to an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.add_flow_media_streams)
@@ -164,14 +225,31 @@
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#close)
         """
+    async def create_bridge(
+        self,
+        *,
+        Name: str,
+        PlacementArn: str,
+        Sources: Sequence[AddBridgeSourceRequestTypeDef],
+        EgressGatewayBridge: AddEgressGatewayBridgeRequestTypeDef = ...,
+        IngressGatewayBridge: AddIngressGatewayBridgeRequestTypeDef = ...,
+        Outputs: Sequence[AddBridgeOutputRequestTypeDef] = ...,
+        SourceFailoverConfig: FailoverConfigTypeDef = ...
+    ) -> CreateBridgeResponseTypeDef:
+        """
+        Creates a new bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#create_bridge)
+        """
     async def create_flow(
         self,
         *,
         Name: str,
         AvailabilityZone: str = ...,
         Entitlements: Sequence[GrantEntitlementRequestTypeDef] = ...,
         MediaStreams: Sequence[AddMediaStreamRequestTypeDef] = ...,
@@ -184,28 +262,87 @@
     ) -> CreateFlowResponseTypeDef:
         """
         Creates a new flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#create_flow)
         """
+    async def create_gateway(
+        self,
+        *,
+        EgressCidrBlocks: Sequence[str],
+        Name: str,
+        Networks: Sequence[GatewayNetworkTypeDef]
+    ) -> CreateGatewayResponseTypeDef:
+        """
+        Creates a new gateway.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.create_gateway)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#create_gateway)
+        """
+    async def delete_bridge(self, *, BridgeArn: str) -> DeleteBridgeResponseTypeDef:
+        """
+        Deletes a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#delete_bridge)
+        """
     async def delete_flow(self, *, FlowArn: str) -> DeleteFlowResponseTypeDef:
         """
         Deletes a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#delete_flow)
         """
+    async def delete_gateway(self, *, GatewayArn: str) -> DeleteGatewayResponseTypeDef:
+        """
+        Deletes a gateway.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.delete_gateway)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#delete_gateway)
+        """
+    async def deregister_gateway_instance(
+        self, *, GatewayInstanceArn: str, Force: bool = ...
+    ) -> DeregisterGatewayInstanceResponseTypeDef:
+        """
+        Deregisters an instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.deregister_gateway_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#deregister_gateway_instance)
+        """
+    async def describe_bridge(self, *, BridgeArn: str) -> DescribeBridgeResponseTypeDef:
+        """
+        Displays the details of a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_bridge)
+        """
     async def describe_flow(self, *, FlowArn: str) -> DescribeFlowResponseTypeDef:
         """
         Displays the details of a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_flow)
         """
+    async def describe_gateway(self, *, GatewayArn: str) -> DescribeGatewayResponseTypeDef:
+        """
+        Displays the details of a gateway.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_gateway)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_gateway)
+        """
+    async def describe_gateway_instance(
+        self, *, GatewayInstanceArn: str
+    ) -> DescribeGatewayInstanceResponseTypeDef:
+        """
+        Displays the details of an instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_gateway_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_gateway_instance)
+        """
     async def describe_offering(self, *, OfferingArn: str) -> DescribeOfferingResponseTypeDef:
         """
         Displays the details of an offering.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.describe_offering)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#describe_offering)
         """
@@ -236,14 +373,24 @@
     ) -> GrantFlowEntitlementsResponseTypeDef:
         """
         Grants entitlements to an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.grant_flow_entitlements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#grant_flow_entitlements)
         """
+    async def list_bridges(
+        self, *, FilterArn: str = ..., MaxResults: int = ..., NextToken: str = ...
+    ) -> ListBridgesResponseTypeDef:
+        """
+        Displays a list of bridges that are associated with this account and an
+        optionally specified Arn.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_bridges)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_bridges)
+        """
     async def list_entitlements(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListEntitlementsResponseTypeDef:
         """
         Displays a list of all entitlements that have been granted to this account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_entitlements)
@@ -254,14 +401,32 @@
     ) -> ListFlowsResponseTypeDef:
         """
         Displays a list of flows that are associated with this account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_flows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_flows)
         """
+    async def list_gateway_instances(
+        self, *, FilterArn: str = ..., MaxResults: int = ..., NextToken: str = ...
+    ) -> ListGatewayInstancesResponseTypeDef:
+        """
+        Displays a list of instances associated with the AWS account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_gateway_instances)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_gateway_instances)
+        """
+    async def list_gateways(
+        self, *, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListGatewaysResponseTypeDef:
+        """
+        Displays a list of gateways that are associated with this account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.list_gateways)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#list_gateways)
+        """
     async def list_offerings(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListOfferingsResponseTypeDef:
         """
         Displays a list of all offerings that are available to this account in the
         current AWS Region.
 
@@ -293,14 +458,32 @@
     ) -> PurchaseOfferingResponseTypeDef:
         """
         Submits a request to purchase an offering.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.purchase_offering)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#purchase_offering)
         """
+    async def remove_bridge_output(
+        self, *, BridgeArn: str, OutputName: str
+    ) -> RemoveBridgeOutputResponseTypeDef:
+        """
+        Removes an output from a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_bridge_output)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#remove_bridge_output)
+        """
+    async def remove_bridge_source(
+        self, *, BridgeArn: str, SourceName: str
+    ) -> RemoveBridgeSourceResponseTypeDef:
+        """
+        Removes a source from a bridge.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_bridge_source)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#remove_bridge_source)
+        """
     async def remove_flow_media_stream(
         self, *, FlowArn: str, MediaStreamName: str
     ) -> RemoveFlowMediaStreamResponseTypeDef:
         """
         Removes a media stream from a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.remove_flow_media_stream)
@@ -370,14 +553,66 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes specified tags from a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#untag_resource)
         """
+    async def update_bridge(
+        self,
+        *,
+        BridgeArn: str,
+        EgressGatewayBridge: UpdateEgressGatewayBridgeRequestTypeDef = ...,
+        IngressGatewayBridge: UpdateIngressGatewayBridgeRequestTypeDef = ...,
+        SourceFailoverConfig: UpdateFailoverConfigTypeDef = ...
+    ) -> UpdateBridgeResponseTypeDef:
+        """
+        Updates the bridge See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/UpdateBridge).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge)
+        """
+    async def update_bridge_output(
+        self,
+        *,
+        BridgeArn: str,
+        OutputName: str,
+        NetworkOutput: UpdateBridgeNetworkOutputRequestTypeDef = ...
+    ) -> UpdateBridgeOutputResponseTypeDef:
+        """
+        Updates an existing bridge output.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge_output)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge_output)
+        """
+    async def update_bridge_source(
+        self,
+        *,
+        BridgeArn: str,
+        SourceName: str,
+        FlowSource: UpdateBridgeFlowSourceRequestTypeDef = ...,
+        NetworkSource: UpdateBridgeNetworkSourceRequestTypeDef = ...
+    ) -> UpdateBridgeSourceResponseTypeDef:
+        """
+        Updates an existing bridge source.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge_source)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge_source)
+        """
+    async def update_bridge_state(
+        self, *, BridgeArn: str, DesiredState: DesiredStateType
+    ) -> UpdateBridgeStateResponseTypeDef:
+        """
+        Updates the bridge state See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/mediaconnect-2018-11-14/UpdateBridgeState).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_bridge_state)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_bridge_state)
+        """
     async def update_flow(
         self,
         *,
         FlowArn: str,
         SourceFailoverConfig: UpdateFailoverConfigTypeDef = ...,
         Maintenance: UpdateMaintenanceTypeDef = ...
     ) -> UpdateFlowResponseTypeDef:
@@ -469,22 +704,38 @@
         Protocol: ProtocolType = ...,
         SenderControlPort: int = ...,
         SenderIpAddress: str = ...,
         SourceListenerAddress: str = ...,
         SourceListenerPort: int = ...,
         StreamId: str = ...,
         VpcInterfaceName: str = ...,
-        WhitelistCidr: str = ...
+        WhitelistCidr: str = ...,
+        GatewayBridgeSource: UpdateGatewayBridgeSourceRequestTypeDef = ...
     ) -> UpdateFlowSourceResponseTypeDef:
         """
         Updates the source of a flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_flow_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_flow_source)
         """
+    async def update_gateway_instance(
+        self, *, GatewayInstanceArn: str, BridgePlacement: BridgePlacementType = ...
+    ) -> UpdateGatewayInstanceResponseTypeDef:
+        """
+        Updates the configuration of an existing Gateway Instance.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.update_gateway_instance)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#update_gateway_instance)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_bridges"]) -> ListBridgesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_entitlements"]
     ) -> ListEntitlementsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
@@ -492,14 +743,28 @@
     @overload
     def get_paginator(self, operation_name: Literal["list_flows"]) -> ListFlowsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_gateway_instances"]
+    ) -> ListGatewayInstancesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_gateways"]) -> ListGatewaysPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_offerings"]) -> ListOfferingsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/client/#get_paginator)
         """
     @overload
     def get_paginator(
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/literals.py` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -14,29 +14,37 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AlgorithmType",
+    "BridgePlacementType",
+    "BridgeStateType",
     "ColorimetryType",
+    "ConnectionStatusType",
+    "DesiredStateType",
     "DurationUnitsType",
     "EncoderProfileType",
     "EncodingNameType",
     "EntitlementStatusType",
     "FailoverModeType",
     "FlowActiveWaiterName",
     "FlowDeletedWaiterName",
     "FlowStandbyWaiterName",
+    "GatewayStateType",
+    "InstanceStateType",
     "KeyTypeType",
+    "ListBridgesPaginatorName",
     "ListEntitlementsPaginatorName",
     "ListFlowsPaginatorName",
+    "ListGatewayInstancesPaginatorName",
+    "ListGatewaysPaginatorName",
     "ListOfferingsPaginatorName",
     "ListReservationsPaginatorName",
     "MaintenanceDayType",
     "MediaStreamTypeType",
     "NetworkInterfaceTypeType",
     "PriceUnitsType",
     "ProtocolType",
@@ -52,28 +60,56 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-
 AlgorithmType = Literal["aes128", "aes192", "aes256"]
+BridgePlacementType = Literal["AVAILABLE", "LOCKED"]
+BridgeStateType = Literal[
+    "ACTIVE",
+    "CREATING",
+    "DELETED",
+    "DELETING",
+    "DEPLOYING",
+    "STANDBY",
+    "STARTING",
+    "START_FAILED",
+    "START_PENDING",
+    "STOPPING",
+    "STOP_FAILED",
+    "UPDATING",
+]
 ColorimetryType = Literal["BT2020", "BT2100", "BT601", "BT709", "ST2065-1", "ST2065-3", "XYZ"]
+ConnectionStatusType = Literal["CONNECTED", "DISCONNECTED"]
+DesiredStateType = Literal["ACTIVE", "DELETED", "STANDBY"]
 DurationUnitsType = Literal["MONTHS"]
 EncoderProfileType = Literal["high", "main"]
 EncodingNameType = Literal["jxsv", "pcm", "raw", "smpte291"]
 EntitlementStatusType = Literal["DISABLED", "ENABLED"]
 FailoverModeType = Literal["FAILOVER", "MERGE"]
 FlowActiveWaiterName = Literal["flow_active"]
 FlowDeletedWaiterName = Literal["flow_deleted"]
 FlowStandbyWaiterName = Literal["flow_standby"]
+GatewayStateType = Literal["ACTIVE", "CREATING", "DELETED", "DELETING", "ERROR", "UPDATING"]
+InstanceStateType = Literal[
+    "ACTIVE",
+    "DEREGISTERED",
+    "DEREGISTERING",
+    "DEREGISTRATION_ERROR",
+    "REGISTERING",
+    "REGISTRATION_ERROR",
+]
 KeyTypeType = Literal["speke", "srt-password", "static-key"]
+ListBridgesPaginatorName = Literal["list_bridges"]
 ListEntitlementsPaginatorName = Literal["list_entitlements"]
 ListFlowsPaginatorName = Literal["list_flows"]
+ListGatewayInstancesPaginatorName = Literal["list_gateway_instances"]
+ListGatewaysPaginatorName = Literal["list_gateways"]
 ListOfferingsPaginatorName = Literal["list_offerings"]
 ListReservationsPaginatorName = Literal["list_reservations"]
 MaintenanceDayType = Literal[
     "Friday", "Monday", "Saturday", "Sunday", "Thursday", "Tuesday", "Wednesday"
 ]
 MediaStreamTypeType = Literal["ancillary-data", "audio", "video"]
 NetworkInterfaceTypeType = Literal["efa", "ena"]
@@ -83,14 +119,15 @@
     "fujitsu-qos",
     "rist",
     "rtp",
     "rtp-fec",
     "srt-caller",
     "srt-listener",
     "st2110-jpegxs",
+    "udp",
     "zixi-pull",
     "zixi-push",
 ]
 RangeType = Literal["FULL", "FULLPROTECT", "NARROW"]
 ReservationStateType = Literal["ACTIVE", "CANCELED", "EXPIRED", "PROCESSING"]
 ResourceTypeType = Literal["Mbps_Outbound_Bandwidth"]
 ScanModeType = Literal["interlace", "progressive", "progressive-segmented-frame"]
@@ -159,14 +196,15 @@
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
@@ -245,14 +283,15 @@
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
@@ -263,14 +302,15 @@
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
@@ -306,14 +346,15 @@
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
@@ -332,16 +373,19 @@
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
@@ -425,15 +469,17 @@
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
@@ -451,15 +497,23 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-PaginatorName = Literal["list_entitlements", "list_flows", "list_offerings", "list_reservations"]
+PaginatorName = Literal[
+    "list_bridges",
+    "list_entitlements",
+    "list_flows",
+    "list_gateway_instances",
+    "list_gateways",
+    "list_offerings",
+    "list_reservations",
+]
 WaiterName = Literal["flow_active", "flow_deleted", "flow_standby"]
 RegionName = Literal[
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/literals.pyi` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/literals.py`

 * *Files 8% similar despite different names*

```diff
@@ -14,28 +14,38 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AlgorithmType",
+    "BridgePlacementType",
+    "BridgeStateType",
     "ColorimetryType",
+    "ConnectionStatusType",
+    "DesiredStateType",
     "DurationUnitsType",
     "EncoderProfileType",
     "EncodingNameType",
     "EntitlementStatusType",
     "FailoverModeType",
     "FlowActiveWaiterName",
     "FlowDeletedWaiterName",
     "FlowStandbyWaiterName",
+    "GatewayStateType",
+    "InstanceStateType",
     "KeyTypeType",
+    "ListBridgesPaginatorName",
     "ListEntitlementsPaginatorName",
     "ListFlowsPaginatorName",
+    "ListGatewayInstancesPaginatorName",
+    "ListGatewaysPaginatorName",
     "ListOfferingsPaginatorName",
     "ListReservationsPaginatorName",
     "MaintenanceDayType",
     "MediaStreamTypeType",
     "NetworkInterfaceTypeType",
     "PriceUnitsType",
     "ProtocolType",
@@ -51,27 +61,57 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
+
 AlgorithmType = Literal["aes128", "aes192", "aes256"]
+BridgePlacementType = Literal["AVAILABLE", "LOCKED"]
+BridgeStateType = Literal[
+    "ACTIVE",
+    "CREATING",
+    "DELETED",
+    "DELETING",
+    "DEPLOYING",
+    "STANDBY",
+    "STARTING",
+    "START_FAILED",
+    "START_PENDING",
+    "STOPPING",
+    "STOP_FAILED",
+    "UPDATING",
+]
 ColorimetryType = Literal["BT2020", "BT2100", "BT601", "BT709", "ST2065-1", "ST2065-3", "XYZ"]
+ConnectionStatusType = Literal["CONNECTED", "DISCONNECTED"]
+DesiredStateType = Literal["ACTIVE", "DELETED", "STANDBY"]
 DurationUnitsType = Literal["MONTHS"]
 EncoderProfileType = Literal["high", "main"]
 EncodingNameType = Literal["jxsv", "pcm", "raw", "smpte291"]
 EntitlementStatusType = Literal["DISABLED", "ENABLED"]
 FailoverModeType = Literal["FAILOVER", "MERGE"]
 FlowActiveWaiterName = Literal["flow_active"]
 FlowDeletedWaiterName = Literal["flow_deleted"]
 FlowStandbyWaiterName = Literal["flow_standby"]
+GatewayStateType = Literal["ACTIVE", "CREATING", "DELETED", "DELETING", "ERROR", "UPDATING"]
+InstanceStateType = Literal[
+    "ACTIVE",
+    "DEREGISTERED",
+    "DEREGISTERING",
+    "DEREGISTRATION_ERROR",
+    "REGISTERING",
+    "REGISTRATION_ERROR",
+]
 KeyTypeType = Literal["speke", "srt-password", "static-key"]
+ListBridgesPaginatorName = Literal["list_bridges"]
 ListEntitlementsPaginatorName = Literal["list_entitlements"]
 ListFlowsPaginatorName = Literal["list_flows"]
+ListGatewayInstancesPaginatorName = Literal["list_gateway_instances"]
+ListGatewaysPaginatorName = Literal["list_gateways"]
 ListOfferingsPaginatorName = Literal["list_offerings"]
 ListReservationsPaginatorName = Literal["list_reservations"]
 MaintenanceDayType = Literal[
     "Friday", "Monday", "Saturday", "Sunday", "Thursday", "Tuesday", "Wednesday"
 ]
 MediaStreamTypeType = Literal["ancillary-data", "audio", "video"]
 NetworkInterfaceTypeType = Literal["efa", "ena"]
@@ -81,14 +121,15 @@
     "fujitsu-qos",
     "rist",
     "rtp",
     "rtp-fec",
     "srt-caller",
     "srt-listener",
     "st2110-jpegxs",
+    "udp",
     "zixi-pull",
     "zixi-push",
 ]
 RangeType = Literal["FULL", "FULLPROTECT", "NARROW"]
 ReservationStateType = Literal["ACTIVE", "CANCELED", "EXPIRED", "PROCESSING"]
 ResourceTypeType = Literal["Mbps_Outbound_Bandwidth"]
 ScanModeType = Literal["interlace", "progressive", "progressive-segmented-frame"]
@@ -157,14 +198,15 @@
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
@@ -243,14 +285,15 @@
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
@@ -261,14 +304,15 @@
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
@@ -304,14 +348,15 @@
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
@@ -330,16 +375,19 @@
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
@@ -423,15 +471,17 @@
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
@@ -449,15 +499,23 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-PaginatorName = Literal["list_entitlements", "list_flows", "list_offerings", "list_reservations"]
+PaginatorName = Literal[
+    "list_bridges",
+    "list_entitlements",
+    "list_flows",
+    "list_gateway_instances",
+    "list_gateways",
+    "list_offerings",
+    "list_reservations",
+]
 WaiterName = Literal["flow_active", "flow_deleted", "flow_standby"]
 RegionName = Literal[
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/type_defs.py` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/type_defs.py`

 * *Files 25% similar despite different names*

```diff
@@ -2,29 +2,35 @@
 Type annotations for mediaconnect service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_mediaconnect.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_mediaconnect.type_defs import VpcInterfaceAttachmentTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: VpcInterfaceAttachmentTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AlgorithmType,
+    BridgePlacementType,
+    BridgeStateType,
     ColorimetryType,
+    ConnectionStatusType,
+    DesiredStateType,
     EncoderProfileType,
     EncodingNameType,
     EntitlementStatusType,
     FailoverModeType,
+    GatewayStateType,
+    InstanceStateType,
     KeyTypeType,
     MaintenanceDayType,
     MediaStreamTypeType,
     NetworkInterfaceTypeType,
     ProtocolType,
     RangeType,
     ReservationStateType,
@@ -42,136 +48,237 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
+    "VpcInterfaceAttachmentTypeDef",
+    "AddBridgeNetworkOutputRequestTypeDef",
+    "AddBridgeNetworkSourceRequestTypeDef",
+    "AddEgressGatewayBridgeRequestTypeDef",
     "VpcInterfaceRequestTypeDef",
     "VpcInterfaceTypeDef",
+    "AddIngressGatewayBridgeRequestTypeDef",
     "AddMaintenanceTypeDef",
     "EncryptionTypeDef",
-    "VpcInterfaceAttachmentTypeDef",
+    "BridgeFlowOutputTypeDef",
+    "BridgeNetworkOutputTypeDef",
+    "BridgeNetworkSourceTypeDef",
+    "EgressGatewayBridgeTypeDef",
+    "IngressGatewayBridgeTypeDef",
+    "MessageDetailTypeDef",
+    "GatewayNetworkTypeDef",
+    "DeleteBridgeRequestRequestTypeDef",
+    "DeleteBridgeResponseTypeDef",
     "DeleteFlowRequestRequestTypeDef",
+    "DeleteFlowResponseTypeDef",
+    "DeleteGatewayRequestRequestTypeDef",
+    "DeleteGatewayResponseTypeDef",
+    "DeregisterGatewayInstanceRequestRequestTypeDef",
+    "DeregisterGatewayInstanceResponseTypeDef",
+    "DescribeBridgeRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeFlowRequestRequestTypeDef",
     "MessagesTypeDef",
+    "DescribeGatewayInstanceRequestRequestTypeDef",
+    "DescribeGatewayRequestRequestTypeDef",
     "DescribeOfferingRequestRequestTypeDef",
     "DescribeReservationRequestRequestTypeDef",
     "InterfaceRequestTypeDef",
     "InterfaceTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncodingParametersRequestTypeDef",
     "EncodingParametersTypeDef",
     "SourcePriorityTypeDef",
     "MaintenanceTypeDef",
     "FmtpRequestTypeDef",
     "FmtpTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListBridgesRequestListBridgesPaginateTypeDef",
+    "ListBridgesRequestRequestTypeDef",
+    "ListedBridgeTypeDef",
+    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
     "ListEntitlementsRequestRequestTypeDef",
     "ListedEntitlementTypeDef",
+    "ListFlowsRequestListFlowsPaginateTypeDef",
     "ListFlowsRequestRequestTypeDef",
+    "ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef",
+    "ListGatewayInstancesRequestRequestTypeDef",
+    "ListedGatewayInstanceTypeDef",
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
+    "ListGatewaysRequestRequestTypeDef",
+    "ListedGatewayTypeDef",
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
     "ListOfferingsRequestRequestTypeDef",
+    "ListReservationsRequestListReservationsPaginateTypeDef",
     "ListReservationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ResourceSpecificationTypeDef",
     "TransportTypeDef",
+    "PaginatorConfigTypeDef",
     "PurchaseOfferingRequestRequestTypeDef",
+    "RemoveBridgeOutputRequestRequestTypeDef",
+    "RemoveBridgeOutputResponseTypeDef",
+    "RemoveBridgeSourceRequestRequestTypeDef",
+    "RemoveBridgeSourceResponseTypeDef",
     "RemoveFlowMediaStreamRequestRequestTypeDef",
+    "RemoveFlowMediaStreamResponseTypeDef",
     "RemoveFlowOutputRequestRequestTypeDef",
+    "RemoveFlowOutputResponseTypeDef",
     "RemoveFlowSourceRequestRequestTypeDef",
+    "RemoveFlowSourceResponseTypeDef",
     "RemoveFlowVpcInterfaceRequestRequestTypeDef",
+    "RemoveFlowVpcInterfaceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeFlowEntitlementRequestRequestTypeDef",
+    "RevokeFlowEntitlementResponseTypeDef",
     "StartFlowRequestRequestTypeDef",
+    "StartFlowResponseTypeDef",
     "StopFlowRequestRequestTypeDef",
+    "StopFlowResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateBridgeNetworkOutputRequestTypeDef",
+    "UpdateBridgeNetworkSourceRequestTypeDef",
+    "UpdateEgressGatewayBridgeRequestTypeDef",
+    "UpdateIngressGatewayBridgeRequestTypeDef",
+    "UpdateBridgeStateRequestRequestTypeDef",
+    "UpdateBridgeStateResponseTypeDef",
     "UpdateEncryptionTypeDef",
     "UpdateMaintenanceTypeDef",
-    "DeleteFlowResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RemoveFlowMediaStreamResponseTypeDef",
-    "RemoveFlowOutputResponseTypeDef",
-    "RemoveFlowSourceResponseTypeDef",
-    "RemoveFlowVpcInterfaceResponseTypeDef",
-    "RevokeFlowEntitlementResponseTypeDef",
-    "StartFlowResponseTypeDef",
-    "StopFlowResponseTypeDef",
+    "UpdateGatewayInstanceRequestRequestTypeDef",
+    "UpdateGatewayInstanceResponseTypeDef",
+    "AddBridgeFlowSourceRequestTypeDef",
+    "BridgeFlowSourceTypeDef",
+    "GatewayBridgeSourceTypeDef",
+    "SetGatewayBridgeSourceRequestTypeDef",
+    "UpdateBridgeFlowSourceRequestTypeDef",
+    "UpdateGatewayBridgeSourceRequestTypeDef",
+    "AddBridgeOutputRequestTypeDef",
     "AddFlowVpcInterfacesRequestRequestTypeDef",
     "AddFlowVpcInterfacesResponseTypeDef",
     "EntitlementTypeDef",
     "GrantEntitlementRequestTypeDef",
+    "BridgeOutputTypeDef",
+    "GatewayInstanceTypeDef",
+    "CreateGatewayRequestRequestTypeDef",
+    "GatewayTypeDef",
     "DescribeFlowRequestFlowActiveWaitTypeDef",
     "DescribeFlowRequestFlowDeletedWaitTypeDef",
     "DescribeFlowRequestFlowStandbyWaitTypeDef",
     "DestinationConfigurationRequestTypeDef",
     "InputConfigurationRequestTypeDef",
     "DestinationConfigurationTypeDef",
     "InputConfigurationTypeDef",
     "FailoverConfigTypeDef",
     "UpdateFailoverConfigTypeDef",
     "ListedFlowTypeDef",
     "MediaStreamAttributesRequestTypeDef",
     "MediaStreamAttributesTypeDef",
-    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
-    "ListFlowsRequestListFlowsPaginateTypeDef",
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    "ListReservationsRequestListReservationsPaginateTypeDef",
+    "ListBridgesResponseTypeDef",
     "ListEntitlementsResponseTypeDef",
+    "ListGatewayInstancesResponseTypeDef",
+    "ListGatewaysResponseTypeDef",
     "OfferingTypeDef",
     "ReservationTypeDef",
+    "UpdateBridgeOutputRequestRequestTypeDef",
     "UpdateFlowEntitlementRequestRequestTypeDef",
+    "AddBridgeSourceRequestTypeDef",
+    "BridgeSourceTypeDef",
+    "UpdateBridgeSourceRequestRequestTypeDef",
+    "AddBridgeOutputsRequestRequestTypeDef",
     "GrantFlowEntitlementsResponseTypeDef",
     "UpdateFlowEntitlementResponseTypeDef",
     "GrantFlowEntitlementsRequestRequestTypeDef",
+    "AddBridgeOutputsResponseTypeDef",
+    "UpdateBridgeOutputResponseTypeDef",
+    "DescribeGatewayInstanceResponseTypeDef",
+    "CreateGatewayResponseTypeDef",
+    "DescribeGatewayResponseTypeDef",
     "MediaStreamOutputConfigurationRequestTypeDef",
     "MediaStreamSourceConfigurationRequestTypeDef",
     "MediaStreamOutputConfigurationTypeDef",
     "MediaStreamSourceConfigurationTypeDef",
+    "UpdateBridgeRequestRequestTypeDef",
     "UpdateFlowRequestRequestTypeDef",
     "ListFlowsResponseTypeDef",
     "AddMediaStreamRequestTypeDef",
     "UpdateFlowMediaStreamRequestRequestTypeDef",
     "MediaStreamTypeDef",
     "DescribeOfferingResponseTypeDef",
     "ListOfferingsResponseTypeDef",
     "DescribeReservationResponseTypeDef",
     "ListReservationsResponseTypeDef",
     "PurchaseOfferingResponseTypeDef",
+    "AddBridgeSourcesRequestRequestTypeDef",
+    "CreateBridgeRequestRequestTypeDef",
+    "AddBridgeSourcesResponseTypeDef",
+    "BridgeTypeDef",
+    "UpdateBridgeSourceResponseTypeDef",
     "AddOutputRequestTypeDef",
     "UpdateFlowOutputRequestRequestTypeDef",
     "SetSourceRequestTypeDef",
     "UpdateFlowSourceRequestRequestTypeDef",
     "OutputTypeDef",
     "SourceTypeDef",
     "AddFlowMediaStreamsRequestRequestTypeDef",
     "AddFlowMediaStreamsResponseTypeDef",
     "UpdateFlowMediaStreamResponseTypeDef",
+    "CreateBridgeResponseTypeDef",
+    "DescribeBridgeResponseTypeDef",
+    "UpdateBridgeResponseTypeDef",
     "AddFlowOutputsRequestRequestTypeDef",
     "AddFlowSourcesRequestRequestTypeDef",
     "CreateFlowRequestRequestTypeDef",
     "AddFlowOutputsResponseTypeDef",
     "UpdateFlowOutputResponseTypeDef",
     "AddFlowSourcesResponseTypeDef",
     "FlowTypeDef",
     "UpdateFlowSourceResponseTypeDef",
     "CreateFlowResponseTypeDef",
     "DescribeFlowResponseTypeDef",
     "UpdateFlowResponseTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+VpcInterfaceAttachmentTypeDef = TypedDict(
+    "VpcInterfaceAttachmentTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "VpcInterfaceName": str,
+    },
+    total=False,
+)
+
+AddBridgeNetworkOutputRequestTypeDef = TypedDict(
+    "AddBridgeNetworkOutputRequestTypeDef",
+    {
+        "IpAddress": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+        "Ttl": int,
+    },
+)
+
+AddBridgeNetworkSourceRequestTypeDef = TypedDict(
+    "AddBridgeNetworkSourceRequestTypeDef",
+    {
+        "MulticastIp": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+    },
+)
+
+AddEgressGatewayBridgeRequestTypeDef = TypedDict(
+    "AddEgressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
     },
 )
 
 _RequiredVpcInterfaceRequestTypeDef = TypedDict(
     "_RequiredVpcInterfaceRequestTypeDef",
     {
         "Name": str,
@@ -203,14 +310,22 @@
         "NetworkInterfaceType": NetworkInterfaceTypeType,
         "RoleArn": str,
         "SecurityGroupIds": List[str],
         "SubnetId": str,
     },
 )
 
+AddIngressGatewayBridgeRequestTypeDef = TypedDict(
+    "AddIngressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
+        "MaxOutputs": int,
+    },
+)
+
 AddMaintenanceTypeDef = TypedDict(
     "AddMaintenanceTypeDef",
     {
         "MaintenanceDay": MaintenanceDayType,
         "MaintenanceStartHour": str,
     },
 )
@@ -237,29 +352,201 @@
 )
 
 
 class EncryptionTypeDef(_RequiredEncryptionTypeDef, _OptionalEncryptionTypeDef):
     pass
 
 
-VpcInterfaceAttachmentTypeDef = TypedDict(
-    "VpcInterfaceAttachmentTypeDef",
+BridgeFlowOutputTypeDef = TypedDict(
+    "BridgeFlowOutputTypeDef",
     {
-        "VpcInterfaceName": str,
+        "FlowArn": str,
+        "FlowSourceArn": str,
+        "Name": str,
+    },
+)
+
+BridgeNetworkOutputTypeDef = TypedDict(
+    "BridgeNetworkOutputTypeDef",
+    {
+        "IpAddress": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+        "Ttl": int,
+    },
+)
+
+BridgeNetworkSourceTypeDef = TypedDict(
+    "BridgeNetworkSourceTypeDef",
+    {
+        "MulticastIp": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+    },
+)
+
+_RequiredEgressGatewayBridgeTypeDef = TypedDict(
+    "_RequiredEgressGatewayBridgeTypeDef",
+    {
+        "MaxBitrate": int,
+    },
+)
+_OptionalEgressGatewayBridgeTypeDef = TypedDict(
+    "_OptionalEgressGatewayBridgeTypeDef",
+    {
+        "InstanceId": str,
     },
     total=False,
 )
 
+
+class EgressGatewayBridgeTypeDef(
+    _RequiredEgressGatewayBridgeTypeDef, _OptionalEgressGatewayBridgeTypeDef
+):
+    pass
+
+
+_RequiredIngressGatewayBridgeTypeDef = TypedDict(
+    "_RequiredIngressGatewayBridgeTypeDef",
+    {
+        "MaxBitrate": int,
+        "MaxOutputs": int,
+    },
+)
+_OptionalIngressGatewayBridgeTypeDef = TypedDict(
+    "_OptionalIngressGatewayBridgeTypeDef",
+    {
+        "InstanceId": str,
+    },
+    total=False,
+)
+
+
+class IngressGatewayBridgeTypeDef(
+    _RequiredIngressGatewayBridgeTypeDef, _OptionalIngressGatewayBridgeTypeDef
+):
+    pass
+
+
+_RequiredMessageDetailTypeDef = TypedDict(
+    "_RequiredMessageDetailTypeDef",
+    {
+        "Code": str,
+        "Message": str,
+    },
+)
+_OptionalMessageDetailTypeDef = TypedDict(
+    "_OptionalMessageDetailTypeDef",
+    {
+        "ResourceName": str,
+    },
+    total=False,
+)
+
+
+class MessageDetailTypeDef(_RequiredMessageDetailTypeDef, _OptionalMessageDetailTypeDef):
+    pass
+
+
+GatewayNetworkTypeDef = TypedDict(
+    "GatewayNetworkTypeDef",
+    {
+        "CidrBlock": str,
+        "Name": str,
+    },
+)
+
+DeleteBridgeRequestRequestTypeDef = TypedDict(
+    "DeleteBridgeRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+    },
+)
+
+DeleteBridgeResponseTypeDef = TypedDict(
+    "DeleteBridgeResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFlowRequestRequestTypeDef = TypedDict(
     "DeleteFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 
+DeleteFlowResponseTypeDef = TypedDict(
+    "DeleteFlowResponseTypeDef",
+    {
+        "FlowArn": str,
+        "Status": StatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteGatewayRequestRequestTypeDef = TypedDict(
+    "DeleteGatewayRequestRequestTypeDef",
+    {
+        "GatewayArn": str,
+    },
+)
+
+DeleteGatewayResponseTypeDef = TypedDict(
+    "DeleteGatewayResponseTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDeregisterGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_RequiredDeregisterGatewayInstanceRequestRequestTypeDef",
+    {
+        "GatewayInstanceArn": str,
+    },
+)
+_OptionalDeregisterGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_OptionalDeregisterGatewayInstanceRequestRequestTypeDef",
+    {
+        "Force": bool,
+    },
+    total=False,
+)
+
+
+class DeregisterGatewayInstanceRequestRequestTypeDef(
+    _RequiredDeregisterGatewayInstanceRequestRequestTypeDef,
+    _OptionalDeregisterGatewayInstanceRequestRequestTypeDef,
+):
+    pass
+
+
+DeregisterGatewayInstanceResponseTypeDef = TypedDict(
+    "DeregisterGatewayInstanceResponseTypeDef",
+    {
+        "GatewayInstanceArn": str,
+        "InstanceState": InstanceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeBridgeRequestRequestTypeDef = TypedDict(
+    "DescribeBridgeRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -275,14 +562,28 @@
 MessagesTypeDef = TypedDict(
     "MessagesTypeDef",
     {
         "Errors": List[str],
     },
 )
 
+DescribeGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "DescribeGatewayInstanceRequestRequestTypeDef",
+    {
+        "GatewayInstanceArn": str,
+    },
+)
+
+DescribeGatewayRequestRequestTypeDef = TypedDict(
+    "DescribeGatewayRequestRequestTypeDef",
+    {
+        "GatewayArn": str,
+    },
+)
+
 DescribeOfferingRequestRequestTypeDef = TypedDict(
     "DescribeOfferingRequestRequestTypeDef",
     {
         "OfferingArn": str,
     },
 )
 
@@ -303,14 +604,21 @@
 InterfaceTypeDef = TypedDict(
     "InterfaceTypeDef",
     {
         "Name": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EncodingParametersRequestTypeDef = TypedDict(
     "EncodingParametersRequestTypeDef",
     {
         "CompressionFactor": float,
         "EncoderProfile": EncoderProfileType,
     },
 )
@@ -366,20 +674,48 @@
         "Range": RangeType,
         "ScanMode": ScanModeType,
         "Tcs": TcsType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListBridgesRequestListBridgesPaginateTypeDef = TypedDict(
+    "ListBridgesRequestListBridgesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FilterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListBridgesRequestRequestTypeDef = TypedDict(
+    "ListBridgesRequestRequestTypeDef",
+    {
+        "FilterArn": str,
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+ListedBridgeTypeDef = TypedDict(
+    "ListedBridgeTypeDef",
+    {
+        "BridgeArn": str,
+        "BridgeState": BridgeStateType,
+        "BridgeType": str,
+        "Name": str,
+        "PlacementArn": str,
+    },
+)
+
+ListEntitlementsRequestListEntitlementsPaginateTypeDef = TypedDict(
+    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEntitlementsRequestRequestTypeDef = TypedDict(
     "ListEntitlementsRequestRequestTypeDef",
     {
@@ -407,32 +743,124 @@
 
 class ListedEntitlementTypeDef(
     _RequiredListedEntitlementTypeDef, _OptionalListedEntitlementTypeDef
 ):
     pass
 
 
+ListFlowsRequestListFlowsPaginateTypeDef = TypedDict(
+    "ListFlowsRequestListFlowsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFlowsRequestRequestTypeDef = TypedDict(
     "ListFlowsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef = TypedDict(
+    "ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef",
+    {
+        "FilterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListGatewayInstancesRequestRequestTypeDef = TypedDict(
+    "ListGatewayInstancesRequestRequestTypeDef",
+    {
+        "FilterArn": str,
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+_RequiredListedGatewayInstanceTypeDef = TypedDict(
+    "_RequiredListedGatewayInstanceTypeDef",
+    {
+        "GatewayArn": str,
+        "GatewayInstanceArn": str,
+        "InstanceId": str,
+    },
+)
+_OptionalListedGatewayInstanceTypeDef = TypedDict(
+    "_OptionalListedGatewayInstanceTypeDef",
+    {
+        "InstanceState": InstanceStateType,
+    },
+    total=False,
+)
+
+
+class ListedGatewayInstanceTypeDef(
+    _RequiredListedGatewayInstanceTypeDef, _OptionalListedGatewayInstanceTypeDef
+):
+    pass
+
+
+ListGatewaysRequestListGatewaysPaginateTypeDef = TypedDict(
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListGatewaysRequestRequestTypeDef = TypedDict(
+    "ListGatewaysRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+ListedGatewayTypeDef = TypedDict(
+    "ListedGatewayTypeDef",
+    {
+        "GatewayArn": str,
+        "GatewayState": GatewayStateType,
+        "Name": str,
+    },
+)
+
+ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingsRequestRequestTypeDef = TypedDict(
     "ListOfferingsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
+    "ListReservationsRequestListReservationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReservationsRequestRequestTypeDef = TypedDict(
     "ListReservationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -441,14 +869,22 @@
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
 _RequiredResourceSpecificationTypeDef = TypedDict(
     "_RequiredResourceSpecificationTypeDef",
     {
         "ResourceType": Literal["Mbps_Outbound_Bandwidth"],
     },
 )
 _OptionalResourceSpecificationTypeDef = TypedDict(
@@ -492,77 +928,196 @@
 )
 
 
 class TransportTypeDef(_RequiredTransportTypeDef, _OptionalTransportTypeDef):
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
 PurchaseOfferingRequestRequestTypeDef = TypedDict(
     "PurchaseOfferingRequestRequestTypeDef",
     {
         "OfferingArn": str,
         "ReservationName": str,
         "Start": str,
     },
 )
 
+RemoveBridgeOutputRequestRequestTypeDef = TypedDict(
+    "RemoveBridgeOutputRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "OutputName": str,
+    },
+)
+
+RemoveBridgeOutputResponseTypeDef = TypedDict(
+    "RemoveBridgeOutputResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "OutputName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RemoveBridgeSourceRequestRequestTypeDef = TypedDict(
+    "RemoveBridgeSourceRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "SourceName": str,
+    },
+)
+
+RemoveBridgeSourceResponseTypeDef = TypedDict(
+    "RemoveBridgeSourceResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "SourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowMediaStreamRequestRequestTypeDef = TypedDict(
     "RemoveFlowMediaStreamRequestRequestTypeDef",
     {
         "FlowArn": str,
         "MediaStreamName": str,
     },
 )
 
+RemoveFlowMediaStreamResponseTypeDef = TypedDict(
+    "RemoveFlowMediaStreamResponseTypeDef",
+    {
+        "FlowArn": str,
+        "MediaStreamName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowOutputRequestRequestTypeDef = TypedDict(
     "RemoveFlowOutputRequestRequestTypeDef",
     {
         "FlowArn": str,
         "OutputArn": str,
     },
 )
 
+RemoveFlowOutputResponseTypeDef = TypedDict(
+    "RemoveFlowOutputResponseTypeDef",
+    {
+        "FlowArn": str,
+        "OutputArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowSourceRequestRequestTypeDef = TypedDict(
     "RemoveFlowSourceRequestRequestTypeDef",
     {
         "FlowArn": str,
         "SourceArn": str,
     },
 )
 
+RemoveFlowSourceResponseTypeDef = TypedDict(
+    "RemoveFlowSourceResponseTypeDef",
+    {
+        "FlowArn": str,
+        "SourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowVpcInterfaceRequestRequestTypeDef = TypedDict(
     "RemoveFlowVpcInterfaceRequestRequestTypeDef",
     {
         "FlowArn": str,
         "VpcInterfaceName": str,
     },
 )
 
+RemoveFlowVpcInterfaceResponseTypeDef = TypedDict(
+    "RemoveFlowVpcInterfaceResponseTypeDef",
+    {
+        "FlowArn": str,
+        "NonDeletedNetworkInterfaceIds": List[str],
+        "VpcInterfaceName": str,
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
 RevokeFlowEntitlementRequestRequestTypeDef = TypedDict(
     "RevokeFlowEntitlementRequestRequestTypeDef",
     {
         "EntitlementArn": str,
         "FlowArn": str,
     },
 )
 
+RevokeFlowEntitlementResponseTypeDef = TypedDict(
+    "RevokeFlowEntitlementResponseTypeDef",
+    {
+        "EntitlementArn": str,
+        "FlowArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartFlowRequestRequestTypeDef = TypedDict(
     "StartFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 
+StartFlowResponseTypeDef = TypedDict(
+    "StartFlowResponseTypeDef",
+    {
+        "FlowArn": str,
+        "Status": StatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopFlowRequestRequestTypeDef = TypedDict(
     "StopFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 
+StopFlowResponseTypeDef = TypedDict(
+    "StopFlowResponseTypeDef",
+    {
+        "FlowArn": str,
+        "Status": StatusType,
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
@@ -571,14 +1126,71 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateBridgeNetworkOutputRequestTypeDef = TypedDict(
+    "UpdateBridgeNetworkOutputRequestTypeDef",
+    {
+        "IpAddress": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+        "Ttl": int,
+    },
+    total=False,
+)
+
+UpdateBridgeNetworkSourceRequestTypeDef = TypedDict(
+    "UpdateBridgeNetworkSourceRequestTypeDef",
+    {
+        "MulticastIp": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+    },
+    total=False,
+)
+
+UpdateEgressGatewayBridgeRequestTypeDef = TypedDict(
+    "UpdateEgressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
+    },
+    total=False,
+)
+
+UpdateIngressGatewayBridgeRequestTypeDef = TypedDict(
+    "UpdateIngressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
+        "MaxOutputs": int,
+    },
+    total=False,
+)
+
+UpdateBridgeStateRequestRequestTypeDef = TypedDict(
+    "UpdateBridgeStateRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "DesiredState": DesiredStateType,
+    },
+)
+
+UpdateBridgeStateResponseTypeDef = TypedDict(
+    "UpdateBridgeStateResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "DesiredState": DesiredStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateEncryptionTypeDef = TypedDict(
     "UpdateEncryptionTypeDef",
     {
         "Algorithm": AlgorithmType,
         "ConstantInitializationVector": str,
         "DeviceId": str,
         "KeyType": KeyTypeType,
@@ -597,100 +1209,154 @@
         "MaintenanceDay": MaintenanceDayType,
         "MaintenanceScheduledDate": str,
         "MaintenanceStartHour": str,
     },
     total=False,
 )
 
-DeleteFlowResponseTypeDef = TypedDict(
-    "DeleteFlowResponseTypeDef",
+_RequiredUpdateGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateGatewayInstanceRequestRequestTypeDef",
     {
-        "FlowArn": str,
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GatewayInstanceArn": str,
     },
 )
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+_OptionalUpdateGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateGatewayInstanceRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgePlacement": BridgePlacementType,
     },
+    total=False,
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+
+class UpdateGatewayInstanceRequestRequestTypeDef(
+    _RequiredUpdateGatewayInstanceRequestRequestTypeDef,
+    _OptionalUpdateGatewayInstanceRequestRequestTypeDef,
+):
+    pass
+
+
+UpdateGatewayInstanceResponseTypeDef = TypedDict(
+    "UpdateGatewayInstanceResponseTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgePlacement": BridgePlacementType,
+        "GatewayInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RemoveFlowMediaStreamResponseTypeDef = TypedDict(
-    "RemoveFlowMediaStreamResponseTypeDef",
+_RequiredAddBridgeFlowSourceRequestTypeDef = TypedDict(
+    "_RequiredAddBridgeFlowSourceRequestTypeDef",
     {
         "FlowArn": str,
-        "MediaStreamName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
     },
 )
+_OptionalAddBridgeFlowSourceRequestTypeDef = TypedDict(
+    "_OptionalAddBridgeFlowSourceRequestTypeDef",
+    {
+        "FlowVpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
+    },
+    total=False,
+)
 
-RemoveFlowOutputResponseTypeDef = TypedDict(
-    "RemoveFlowOutputResponseTypeDef",
+
+class AddBridgeFlowSourceRequestTypeDef(
+    _RequiredAddBridgeFlowSourceRequestTypeDef, _OptionalAddBridgeFlowSourceRequestTypeDef
+):
+    pass
+
+
+_RequiredBridgeFlowSourceTypeDef = TypedDict(
+    "_RequiredBridgeFlowSourceTypeDef",
     {
         "FlowArn": str,
+        "Name": str,
+    },
+)
+_OptionalBridgeFlowSourceTypeDef = TypedDict(
+    "_OptionalBridgeFlowSourceTypeDef",
+    {
+        "FlowVpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
         "OutputArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-RemoveFlowSourceResponseTypeDef = TypedDict(
-    "RemoveFlowSourceResponseTypeDef",
+
+class BridgeFlowSourceTypeDef(_RequiredBridgeFlowSourceTypeDef, _OptionalBridgeFlowSourceTypeDef):
+    pass
+
+
+_RequiredGatewayBridgeSourceTypeDef = TypedDict(
+    "_RequiredGatewayBridgeSourceTypeDef",
     {
-        "FlowArn": str,
-        "SourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgeArn": str,
     },
 )
+_OptionalGatewayBridgeSourceTypeDef = TypedDict(
+    "_OptionalGatewayBridgeSourceTypeDef",
+    {
+        "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
+    },
+    total=False,
+)
 
-RemoveFlowVpcInterfaceResponseTypeDef = TypedDict(
-    "RemoveFlowVpcInterfaceResponseTypeDef",
+
+class GatewayBridgeSourceTypeDef(
+    _RequiredGatewayBridgeSourceTypeDef, _OptionalGatewayBridgeSourceTypeDef
+):
+    pass
+
+
+_RequiredSetGatewayBridgeSourceRequestTypeDef = TypedDict(
+    "_RequiredSetGatewayBridgeSourceRequestTypeDef",
     {
-        "FlowArn": str,
-        "NonDeletedNetworkInterfaceIds": List[str],
-        "VpcInterfaceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgeArn": str,
+    },
+)
+_OptionalSetGatewayBridgeSourceRequestTypeDef = TypedDict(
+    "_OptionalSetGatewayBridgeSourceRequestTypeDef",
+    {
+        "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-RevokeFlowEntitlementResponseTypeDef = TypedDict(
-    "RevokeFlowEntitlementResponseTypeDef",
+
+class SetGatewayBridgeSourceRequestTypeDef(
+    _RequiredSetGatewayBridgeSourceRequestTypeDef, _OptionalSetGatewayBridgeSourceRequestTypeDef
+):
+    pass
+
+
+UpdateBridgeFlowSourceRequestTypeDef = TypedDict(
+    "UpdateBridgeFlowSourceRequestTypeDef",
     {
-        "EntitlementArn": str,
         "FlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FlowVpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-StartFlowResponseTypeDef = TypedDict(
-    "StartFlowResponseTypeDef",
+UpdateGatewayBridgeSourceRequestTypeDef = TypedDict(
+    "UpdateGatewayBridgeSourceRequestTypeDef",
     {
-        "FlowArn": str,
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgeArn": str,
+        "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-StopFlowResponseTypeDef = TypedDict(
-    "StopFlowResponseTypeDef",
+AddBridgeOutputRequestTypeDef = TypedDict(
+    "AddBridgeOutputRequestTypeDef",
     {
-        "FlowArn": str,
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NetworkOutput": AddBridgeNetworkOutputRequestTypeDef,
     },
+    total=False,
 )
 
 AddFlowVpcInterfacesRequestRequestTypeDef = TypedDict(
     "AddFlowVpcInterfacesRequestRequestTypeDef",
     {
         "FlowArn": str,
         "VpcInterfaces": Sequence[VpcInterfaceRequestTypeDef],
@@ -698,15 +1364,15 @@
 )
 
 AddFlowVpcInterfacesResponseTypeDef = TypedDict(
     "AddFlowVpcInterfacesResponseTypeDef",
     {
         "FlowArn": str,
         "VpcInterfaces": List[VpcInterfaceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEntitlementTypeDef = TypedDict(
     "_RequiredEntitlementTypeDef",
     {
         "EntitlementArn": str,
@@ -751,14 +1417,80 @@
 
 class GrantEntitlementRequestTypeDef(
     _RequiredGrantEntitlementRequestTypeDef, _OptionalGrantEntitlementRequestTypeDef
 ):
     pass
 
 
+BridgeOutputTypeDef = TypedDict(
+    "BridgeOutputTypeDef",
+    {
+        "FlowOutput": BridgeFlowOutputTypeDef,
+        "NetworkOutput": BridgeNetworkOutputTypeDef,
+    },
+    total=False,
+)
+
+_RequiredGatewayInstanceTypeDef = TypedDict(
+    "_RequiredGatewayInstanceTypeDef",
+    {
+        "BridgePlacement": BridgePlacementType,
+        "ConnectionStatus": ConnectionStatusType,
+        "GatewayArn": str,
+        "GatewayInstanceArn": str,
+        "InstanceId": str,
+        "InstanceState": InstanceStateType,
+        "RunningBridgeCount": int,
+    },
+)
+_OptionalGatewayInstanceTypeDef = TypedDict(
+    "_OptionalGatewayInstanceTypeDef",
+    {
+        "InstanceMessages": List[MessageDetailTypeDef],
+    },
+    total=False,
+)
+
+
+class GatewayInstanceTypeDef(_RequiredGatewayInstanceTypeDef, _OptionalGatewayInstanceTypeDef):
+    pass
+
+
+CreateGatewayRequestRequestTypeDef = TypedDict(
+    "CreateGatewayRequestRequestTypeDef",
+    {
+        "EgressCidrBlocks": Sequence[str],
+        "Name": str,
+        "Networks": Sequence[GatewayNetworkTypeDef],
+    },
+)
+
+_RequiredGatewayTypeDef = TypedDict(
+    "_RequiredGatewayTypeDef",
+    {
+        "EgressCidrBlocks": List[str],
+        "GatewayArn": str,
+        "Name": str,
+        "Networks": List[GatewayNetworkTypeDef],
+    },
+)
+_OptionalGatewayTypeDef = TypedDict(
+    "_OptionalGatewayTypeDef",
+    {
+        "GatewayMessages": List[MessageDetailTypeDef],
+        "GatewayState": GatewayStateType,
+    },
+    total=False,
+)
+
+
+class GatewayTypeDef(_RequiredGatewayTypeDef, _OptionalGatewayTypeDef):
+    pass
+
+
 _RequiredDescribeFlowRequestFlowActiveWaitTypeDef = TypedDict(
     "_RequiredDescribeFlowRequestFlowActiveWaitTypeDef",
     {
         "FlowArn": str,
     },
 )
 _OptionalDescribeFlowRequestFlowActiveWaitTypeDef = TypedDict(
@@ -929,52 +1661,47 @@
 
 class MediaStreamAttributesTypeDef(
     _RequiredMediaStreamAttributesTypeDef, _OptionalMediaStreamAttributesTypeDef
 ):
     pass
 
 
-ListEntitlementsRequestListEntitlementsPaginateTypeDef = TypedDict(
-    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
+ListBridgesResponseTypeDef = TypedDict(
+    "ListBridgesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFlowsRequestListFlowsPaginateTypeDef = TypedDict(
-    "ListFlowsRequestListFlowsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Bridges": List[ListedBridgeTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+ListEntitlementsResponseTypeDef = TypedDict(
+    "ListEntitlementsResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Entitlements": List[ListedEntitlementTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
-    "ListReservationsRequestListReservationsPaginateTypeDef",
+ListGatewayInstancesResponseTypeDef = TypedDict(
+    "ListGatewayInstancesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Instances": List[ListedGatewayInstanceTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListEntitlementsResponseTypeDef = TypedDict(
-    "ListEntitlementsResponseTypeDef",
+ListGatewaysResponseTypeDef = TypedDict(
+    "ListGatewaysResponseTypeDef",
     {
-        "Entitlements": List[ListedEntitlementTypeDef],
+        "Gateways": List[ListedGatewayTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTypeDef = TypedDict(
     "OfferingTypeDef",
     {
         "CurrencyCode": str,
@@ -1003,14 +1730,37 @@
         "ReservationName": str,
         "ReservationState": ReservationStateType,
         "ResourceSpecification": ResourceSpecificationTypeDef,
         "Start": str,
     },
 )
 
+_RequiredUpdateBridgeOutputRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateBridgeOutputRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "OutputName": str,
+    },
+)
+_OptionalUpdateBridgeOutputRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateBridgeOutputRequestRequestTypeDef",
+    {
+        "NetworkOutput": UpdateBridgeNetworkOutputRequestTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateBridgeOutputRequestRequestTypeDef(
+    _RequiredUpdateBridgeOutputRequestRequestTypeDef,
+    _OptionalUpdateBridgeOutputRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredUpdateFlowEntitlementRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowEntitlementRequestRequestTypeDef",
     {
         "EntitlementArn": str,
         "FlowArn": str,
     },
 )
@@ -1029,40 +1779,132 @@
 class UpdateFlowEntitlementRequestRequestTypeDef(
     _RequiredUpdateFlowEntitlementRequestRequestTypeDef,
     _OptionalUpdateFlowEntitlementRequestRequestTypeDef,
 ):
     pass
 
 
+AddBridgeSourceRequestTypeDef = TypedDict(
+    "AddBridgeSourceRequestTypeDef",
+    {
+        "FlowSource": AddBridgeFlowSourceRequestTypeDef,
+        "NetworkSource": AddBridgeNetworkSourceRequestTypeDef,
+    },
+    total=False,
+)
+
+BridgeSourceTypeDef = TypedDict(
+    "BridgeSourceTypeDef",
+    {
+        "FlowSource": BridgeFlowSourceTypeDef,
+        "NetworkSource": BridgeNetworkSourceTypeDef,
+    },
+    total=False,
+)
+
+_RequiredUpdateBridgeSourceRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateBridgeSourceRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "SourceName": str,
+    },
+)
+_OptionalUpdateBridgeSourceRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateBridgeSourceRequestRequestTypeDef",
+    {
+        "FlowSource": UpdateBridgeFlowSourceRequestTypeDef,
+        "NetworkSource": UpdateBridgeNetworkSourceRequestTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateBridgeSourceRequestRequestTypeDef(
+    _RequiredUpdateBridgeSourceRequestRequestTypeDef,
+    _OptionalUpdateBridgeSourceRequestRequestTypeDef,
+):
+    pass
+
+
+AddBridgeOutputsRequestRequestTypeDef = TypedDict(
+    "AddBridgeOutputsRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "Outputs": Sequence[AddBridgeOutputRequestTypeDef],
+    },
+)
+
 GrantFlowEntitlementsResponseTypeDef = TypedDict(
     "GrantFlowEntitlementsResponseTypeDef",
     {
         "Entitlements": List[EntitlementTypeDef],
         "FlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowEntitlementResponseTypeDef = TypedDict(
     "UpdateFlowEntitlementResponseTypeDef",
     {
         "Entitlement": EntitlementTypeDef,
         "FlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GrantFlowEntitlementsRequestRequestTypeDef = TypedDict(
     "GrantFlowEntitlementsRequestRequestTypeDef",
     {
         "Entitlements": Sequence[GrantEntitlementRequestTypeDef],
         "FlowArn": str,
     },
 )
 
+AddBridgeOutputsResponseTypeDef = TypedDict(
+    "AddBridgeOutputsResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Outputs": List[BridgeOutputTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBridgeOutputResponseTypeDef = TypedDict(
+    "UpdateBridgeOutputResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Output": BridgeOutputTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeGatewayInstanceResponseTypeDef = TypedDict(
+    "DescribeGatewayInstanceResponseTypeDef",
+    {
+        "GatewayInstance": GatewayInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateGatewayResponseTypeDef = TypedDict(
+    "CreateGatewayResponseTypeDef",
+    {
+        "Gateway": GatewayTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeGatewayResponseTypeDef = TypedDict(
+    "DescribeGatewayResponseTypeDef",
+    {
+        "Gateway": GatewayTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMediaStreamOutputConfigurationRequestTypeDef = TypedDict(
     "_RequiredMediaStreamOutputConfigurationRequestTypeDef",
     {
         "EncodingName": EncodingNameType,
         "MediaStreamName": str,
     },
 )
@@ -1147,14 +1989,37 @@
 
 class MediaStreamSourceConfigurationTypeDef(
     _RequiredMediaStreamSourceConfigurationTypeDef, _OptionalMediaStreamSourceConfigurationTypeDef
 ):
     pass
 
 
+_RequiredUpdateBridgeRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateBridgeRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+    },
+)
+_OptionalUpdateBridgeRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateBridgeRequestRequestTypeDef",
+    {
+        "EgressGatewayBridge": UpdateEgressGatewayBridgeRequestTypeDef,
+        "IngressGatewayBridge": UpdateIngressGatewayBridgeRequestTypeDef,
+        "SourceFailoverConfig": UpdateFailoverConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateBridgeRequestRequestTypeDef(
+    _RequiredUpdateBridgeRequestRequestTypeDef, _OptionalUpdateBridgeRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredUpdateFlowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 _OptionalUpdateFlowRequestRequestTypeDef = TypedDict(
@@ -1174,15 +2039,15 @@
 
 
 ListFlowsResponseTypeDef = TypedDict(
     "ListFlowsResponseTypeDef",
     {
         "Flows": List[ListedFlowTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddMediaStreamRequestTypeDef = TypedDict(
     "_RequiredAddMediaStreamRequestTypeDef",
     {
         "MediaStreamId": int,
@@ -1260,49 +2125,128 @@
     pass
 
 
 DescribeOfferingResponseTypeDef = TypedDict(
     "DescribeOfferingResponseTypeDef",
     {
         "Offering": OfferingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingsResponseTypeDef = TypedDict(
     "ListOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "Offerings": List[OfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservationResponseTypeDef = TypedDict(
     "DescribeReservationResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReservationsResponseTypeDef = TypedDict(
     "ListReservationsResponseTypeDef",
     {
         "NextToken": str,
         "Reservations": List[ReservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseOfferingResponseTypeDef = TypedDict(
     "PurchaseOfferingResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AddBridgeSourcesRequestRequestTypeDef = TypedDict(
+    "AddBridgeSourcesRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "Sources": Sequence[AddBridgeSourceRequestTypeDef],
+    },
+)
+
+_RequiredCreateBridgeRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateBridgeRequestRequestTypeDef",
+    {
+        "Name": str,
+        "PlacementArn": str,
+        "Sources": Sequence[AddBridgeSourceRequestTypeDef],
+    },
+)
+_OptionalCreateBridgeRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateBridgeRequestRequestTypeDef",
+    {
+        "EgressGatewayBridge": AddEgressGatewayBridgeRequestTypeDef,
+        "IngressGatewayBridge": AddIngressGatewayBridgeRequestTypeDef,
+        "Outputs": Sequence[AddBridgeOutputRequestTypeDef],
+        "SourceFailoverConfig": FailoverConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateBridgeRequestRequestTypeDef(
+    _RequiredCreateBridgeRequestRequestTypeDef, _OptionalCreateBridgeRequestRequestTypeDef
+):
+    pass
+
+
+AddBridgeSourcesResponseTypeDef = TypedDict(
+    "AddBridgeSourcesResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Sources": List[BridgeSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredBridgeTypeDef = TypedDict(
+    "_RequiredBridgeTypeDef",
+    {
+        "BridgeArn": str,
+        "BridgeState": BridgeStateType,
+        "Name": str,
+        "PlacementArn": str,
+    },
+)
+_OptionalBridgeTypeDef = TypedDict(
+    "_OptionalBridgeTypeDef",
+    {
+        "BridgeMessages": List[MessageDetailTypeDef],
+        "EgressGatewayBridge": EgressGatewayBridgeTypeDef,
+        "IngressGatewayBridge": IngressGatewayBridgeTypeDef,
+        "Outputs": List[BridgeOutputTypeDef],
+        "SourceFailoverConfig": FailoverConfigTypeDef,
+        "Sources": List[BridgeSourceTypeDef],
+    },
+    total=False,
+)
+
+
+class BridgeTypeDef(_RequiredBridgeTypeDef, _OptionalBridgeTypeDef):
+    pass
+
+
+UpdateBridgeSourceResponseTypeDef = TypedDict(
+    "UpdateBridgeSourceResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Source": BridgeSourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddOutputRequestTypeDef = TypedDict(
     "_RequiredAddOutputRequestTypeDef",
     {
         "Protocol": ProtocolType,
@@ -1387,14 +2331,15 @@
         "SenderControlPort": int,
         "SenderIpAddress": str,
         "SourceListenerAddress": str,
         "SourceListenerPort": int,
         "StreamId": str,
         "VpcInterfaceName": str,
         "WhitelistCidr": str,
+        "GatewayBridgeSource": SetGatewayBridgeSourceRequestTypeDef,
     },
     total=False,
 )
 
 _RequiredUpdateFlowSourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowSourceRequestRequestTypeDef",
     {
@@ -1418,14 +2363,15 @@
         "SenderControlPort": int,
         "SenderIpAddress": str,
         "SourceListenerAddress": str,
         "SourceListenerPort": int,
         "StreamId": str,
         "VpcInterfaceName": str,
         "WhitelistCidr": str,
+        "GatewayBridgeSource": UpdateGatewayBridgeSourceRequestTypeDef,
     },
     total=False,
 )
 
 
 class UpdateFlowSourceRequestRequestTypeDef(
     _RequiredUpdateFlowSourceRequestRequestTypeDef, _OptionalUpdateFlowSourceRequestRequestTypeDef
@@ -1450,14 +2396,16 @@
         "EntitlementArn": str,
         "ListenerAddress": str,
         "MediaLiveInputArn": str,
         "MediaStreamOutputConfigurations": List[MediaStreamOutputConfigurationTypeDef],
         "Port": int,
         "Transport": TransportTypeDef,
         "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
+        "BridgeArn": str,
+        "BridgePorts": List[int],
     },
     total=False,
 )
 
 
 class OutputTypeDef(_RequiredOutputTypeDef, _OptionalOutputTypeDef):
     pass
@@ -1481,14 +2429,15 @@
         "IngestPort": int,
         "MediaStreamSourceConfigurations": List[MediaStreamSourceConfigurationTypeDef],
         "SenderControlPort": int,
         "SenderIpAddress": str,
         "Transport": TransportTypeDef,
         "VpcInterfaceName": str,
         "WhitelistCidr": str,
+        "GatewayBridgeSource": GatewayBridgeSourceTypeDef,
     },
     total=False,
 )
 
 
 class SourceTypeDef(_RequiredSourceTypeDef, _OptionalSourceTypeDef):
     pass
@@ -1503,24 +2452,48 @@
 )
 
 AddFlowMediaStreamsResponseTypeDef = TypedDict(
     "AddFlowMediaStreamsResponseTypeDef",
     {
         "FlowArn": str,
         "MediaStreams": List[MediaStreamTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowMediaStreamResponseTypeDef = TypedDict(
     "UpdateFlowMediaStreamResponseTypeDef",
     {
         "FlowArn": str,
         "MediaStream": MediaStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateBridgeResponseTypeDef = TypedDict(
+    "CreateBridgeResponseTypeDef",
+    {
+        "Bridge": BridgeTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeBridgeResponseTypeDef = TypedDict(
+    "DescribeBridgeResponseTypeDef",
+    {
+        "Bridge": BridgeTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBridgeResponseTypeDef = TypedDict(
+    "UpdateBridgeResponseTypeDef",
+    {
+        "Bridge": BridgeTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddFlowOutputsRequestRequestTypeDef = TypedDict(
     "AddFlowOutputsRequestRequestTypeDef",
     {
         "FlowArn": str,
@@ -1566,33 +2539,33 @@
 
 
 AddFlowOutputsResponseTypeDef = TypedDict(
     "AddFlowOutputsResponseTypeDef",
     {
         "FlowArn": str,
         "Outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowOutputResponseTypeDef = TypedDict(
     "UpdateFlowOutputResponseTypeDef",
     {
         "FlowArn": str,
         "Output": OutputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddFlowSourcesResponseTypeDef = TypedDict(
     "AddFlowSourcesResponseTypeDef",
     {
         "FlowArn": str,
         "Sources": List[SourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFlowTypeDef = TypedDict(
     "_RequiredFlowTypeDef",
     {
         "AvailabilityZone": str,
@@ -1624,35 +2597,35 @@
 
 
 UpdateFlowSourceResponseTypeDef = TypedDict(
     "UpdateFlowSourceResponseTypeDef",
     {
         "FlowArn": str,
         "Source": SourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFlowResponseTypeDef = TypedDict(
     "CreateFlowResponseTypeDef",
     {
         "Flow": FlowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFlowResponseTypeDef = TypedDict(
     "DescribeFlowResponseTypeDef",
     {
         "Flow": FlowTypeDef,
         "Messages": MessagesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowResponseTypeDef = TypedDict(
     "UpdateFlowResponseTypeDef",
     {
         "Flow": FlowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/type_defs.pyi` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/type_defs.pyi`

 * *Files 26% similar despite different names*

```diff
@@ -2,29 +2,35 @@
 Type annotations for mediaconnect service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_mediaconnect.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_mediaconnect.type_defs import VpcInterfaceAttachmentTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: VpcInterfaceAttachmentTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AlgorithmType,
+    BridgePlacementType,
+    BridgeStateType,
     ColorimetryType,
+    ConnectionStatusType,
+    DesiredStateType,
     EncoderProfileType,
     EncodingNameType,
     EntitlementStatusType,
     FailoverModeType,
+    GatewayStateType,
+    InstanceStateType,
     KeyTypeType,
     MaintenanceDayType,
     MediaStreamTypeType,
     NetworkInterfaceTypeType,
     ProtocolType,
     RangeType,
     ReservationStateType,
@@ -41,136 +47,237 @@
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
-    "ResponseMetadataTypeDef",
+    "VpcInterfaceAttachmentTypeDef",
+    "AddBridgeNetworkOutputRequestTypeDef",
+    "AddBridgeNetworkSourceRequestTypeDef",
+    "AddEgressGatewayBridgeRequestTypeDef",
     "VpcInterfaceRequestTypeDef",
     "VpcInterfaceTypeDef",
+    "AddIngressGatewayBridgeRequestTypeDef",
     "AddMaintenanceTypeDef",
     "EncryptionTypeDef",
-    "VpcInterfaceAttachmentTypeDef",
+    "BridgeFlowOutputTypeDef",
+    "BridgeNetworkOutputTypeDef",
+    "BridgeNetworkSourceTypeDef",
+    "EgressGatewayBridgeTypeDef",
+    "IngressGatewayBridgeTypeDef",
+    "MessageDetailTypeDef",
+    "GatewayNetworkTypeDef",
+    "DeleteBridgeRequestRequestTypeDef",
+    "DeleteBridgeResponseTypeDef",
     "DeleteFlowRequestRequestTypeDef",
+    "DeleteFlowResponseTypeDef",
+    "DeleteGatewayRequestRequestTypeDef",
+    "DeleteGatewayResponseTypeDef",
+    "DeregisterGatewayInstanceRequestRequestTypeDef",
+    "DeregisterGatewayInstanceResponseTypeDef",
+    "DescribeBridgeRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeFlowRequestRequestTypeDef",
     "MessagesTypeDef",
+    "DescribeGatewayInstanceRequestRequestTypeDef",
+    "DescribeGatewayRequestRequestTypeDef",
     "DescribeOfferingRequestRequestTypeDef",
     "DescribeReservationRequestRequestTypeDef",
     "InterfaceRequestTypeDef",
     "InterfaceTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncodingParametersRequestTypeDef",
     "EncodingParametersTypeDef",
     "SourcePriorityTypeDef",
     "MaintenanceTypeDef",
     "FmtpRequestTypeDef",
     "FmtpTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListBridgesRequestListBridgesPaginateTypeDef",
+    "ListBridgesRequestRequestTypeDef",
+    "ListedBridgeTypeDef",
+    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
     "ListEntitlementsRequestRequestTypeDef",
     "ListedEntitlementTypeDef",
+    "ListFlowsRequestListFlowsPaginateTypeDef",
     "ListFlowsRequestRequestTypeDef",
+    "ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef",
+    "ListGatewayInstancesRequestRequestTypeDef",
+    "ListedGatewayInstanceTypeDef",
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
+    "ListGatewaysRequestRequestTypeDef",
+    "ListedGatewayTypeDef",
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
     "ListOfferingsRequestRequestTypeDef",
+    "ListReservationsRequestListReservationsPaginateTypeDef",
     "ListReservationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ResourceSpecificationTypeDef",
     "TransportTypeDef",
+    "PaginatorConfigTypeDef",
     "PurchaseOfferingRequestRequestTypeDef",
+    "RemoveBridgeOutputRequestRequestTypeDef",
+    "RemoveBridgeOutputResponseTypeDef",
+    "RemoveBridgeSourceRequestRequestTypeDef",
+    "RemoveBridgeSourceResponseTypeDef",
     "RemoveFlowMediaStreamRequestRequestTypeDef",
+    "RemoveFlowMediaStreamResponseTypeDef",
     "RemoveFlowOutputRequestRequestTypeDef",
+    "RemoveFlowOutputResponseTypeDef",
     "RemoveFlowSourceRequestRequestTypeDef",
+    "RemoveFlowSourceResponseTypeDef",
     "RemoveFlowVpcInterfaceRequestRequestTypeDef",
+    "RemoveFlowVpcInterfaceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeFlowEntitlementRequestRequestTypeDef",
+    "RevokeFlowEntitlementResponseTypeDef",
     "StartFlowRequestRequestTypeDef",
+    "StartFlowResponseTypeDef",
     "StopFlowRequestRequestTypeDef",
+    "StopFlowResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateBridgeNetworkOutputRequestTypeDef",
+    "UpdateBridgeNetworkSourceRequestTypeDef",
+    "UpdateEgressGatewayBridgeRequestTypeDef",
+    "UpdateIngressGatewayBridgeRequestTypeDef",
+    "UpdateBridgeStateRequestRequestTypeDef",
+    "UpdateBridgeStateResponseTypeDef",
     "UpdateEncryptionTypeDef",
     "UpdateMaintenanceTypeDef",
-    "DeleteFlowResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RemoveFlowMediaStreamResponseTypeDef",
-    "RemoveFlowOutputResponseTypeDef",
-    "RemoveFlowSourceResponseTypeDef",
-    "RemoveFlowVpcInterfaceResponseTypeDef",
-    "RevokeFlowEntitlementResponseTypeDef",
-    "StartFlowResponseTypeDef",
-    "StopFlowResponseTypeDef",
+    "UpdateGatewayInstanceRequestRequestTypeDef",
+    "UpdateGatewayInstanceResponseTypeDef",
+    "AddBridgeFlowSourceRequestTypeDef",
+    "BridgeFlowSourceTypeDef",
+    "GatewayBridgeSourceTypeDef",
+    "SetGatewayBridgeSourceRequestTypeDef",
+    "UpdateBridgeFlowSourceRequestTypeDef",
+    "UpdateGatewayBridgeSourceRequestTypeDef",
+    "AddBridgeOutputRequestTypeDef",
     "AddFlowVpcInterfacesRequestRequestTypeDef",
     "AddFlowVpcInterfacesResponseTypeDef",
     "EntitlementTypeDef",
     "GrantEntitlementRequestTypeDef",
+    "BridgeOutputTypeDef",
+    "GatewayInstanceTypeDef",
+    "CreateGatewayRequestRequestTypeDef",
+    "GatewayTypeDef",
     "DescribeFlowRequestFlowActiveWaitTypeDef",
     "DescribeFlowRequestFlowDeletedWaitTypeDef",
     "DescribeFlowRequestFlowStandbyWaitTypeDef",
     "DestinationConfigurationRequestTypeDef",
     "InputConfigurationRequestTypeDef",
     "DestinationConfigurationTypeDef",
     "InputConfigurationTypeDef",
     "FailoverConfigTypeDef",
     "UpdateFailoverConfigTypeDef",
     "ListedFlowTypeDef",
     "MediaStreamAttributesRequestTypeDef",
     "MediaStreamAttributesTypeDef",
-    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
-    "ListFlowsRequestListFlowsPaginateTypeDef",
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    "ListReservationsRequestListReservationsPaginateTypeDef",
+    "ListBridgesResponseTypeDef",
     "ListEntitlementsResponseTypeDef",
+    "ListGatewayInstancesResponseTypeDef",
+    "ListGatewaysResponseTypeDef",
     "OfferingTypeDef",
     "ReservationTypeDef",
+    "UpdateBridgeOutputRequestRequestTypeDef",
     "UpdateFlowEntitlementRequestRequestTypeDef",
+    "AddBridgeSourceRequestTypeDef",
+    "BridgeSourceTypeDef",
+    "UpdateBridgeSourceRequestRequestTypeDef",
+    "AddBridgeOutputsRequestRequestTypeDef",
     "GrantFlowEntitlementsResponseTypeDef",
     "UpdateFlowEntitlementResponseTypeDef",
     "GrantFlowEntitlementsRequestRequestTypeDef",
+    "AddBridgeOutputsResponseTypeDef",
+    "UpdateBridgeOutputResponseTypeDef",
+    "DescribeGatewayInstanceResponseTypeDef",
+    "CreateGatewayResponseTypeDef",
+    "DescribeGatewayResponseTypeDef",
     "MediaStreamOutputConfigurationRequestTypeDef",
     "MediaStreamSourceConfigurationRequestTypeDef",
     "MediaStreamOutputConfigurationTypeDef",
     "MediaStreamSourceConfigurationTypeDef",
+    "UpdateBridgeRequestRequestTypeDef",
     "UpdateFlowRequestRequestTypeDef",
     "ListFlowsResponseTypeDef",
     "AddMediaStreamRequestTypeDef",
     "UpdateFlowMediaStreamRequestRequestTypeDef",
     "MediaStreamTypeDef",
     "DescribeOfferingResponseTypeDef",
     "ListOfferingsResponseTypeDef",
     "DescribeReservationResponseTypeDef",
     "ListReservationsResponseTypeDef",
     "PurchaseOfferingResponseTypeDef",
+    "AddBridgeSourcesRequestRequestTypeDef",
+    "CreateBridgeRequestRequestTypeDef",
+    "AddBridgeSourcesResponseTypeDef",
+    "BridgeTypeDef",
+    "UpdateBridgeSourceResponseTypeDef",
     "AddOutputRequestTypeDef",
     "UpdateFlowOutputRequestRequestTypeDef",
     "SetSourceRequestTypeDef",
     "UpdateFlowSourceRequestRequestTypeDef",
     "OutputTypeDef",
     "SourceTypeDef",
     "AddFlowMediaStreamsRequestRequestTypeDef",
     "AddFlowMediaStreamsResponseTypeDef",
     "UpdateFlowMediaStreamResponseTypeDef",
+    "CreateBridgeResponseTypeDef",
+    "DescribeBridgeResponseTypeDef",
+    "UpdateBridgeResponseTypeDef",
     "AddFlowOutputsRequestRequestTypeDef",
     "AddFlowSourcesRequestRequestTypeDef",
     "CreateFlowRequestRequestTypeDef",
     "AddFlowOutputsResponseTypeDef",
     "UpdateFlowOutputResponseTypeDef",
     "AddFlowSourcesResponseTypeDef",
     "FlowTypeDef",
     "UpdateFlowSourceResponseTypeDef",
     "CreateFlowResponseTypeDef",
     "DescribeFlowResponseTypeDef",
     "UpdateFlowResponseTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+VpcInterfaceAttachmentTypeDef = TypedDict(
+    "VpcInterfaceAttachmentTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "VpcInterfaceName": str,
+    },
+    total=False,
+)
+
+AddBridgeNetworkOutputRequestTypeDef = TypedDict(
+    "AddBridgeNetworkOutputRequestTypeDef",
+    {
+        "IpAddress": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+        "Ttl": int,
+    },
+)
+
+AddBridgeNetworkSourceRequestTypeDef = TypedDict(
+    "AddBridgeNetworkSourceRequestTypeDef",
+    {
+        "MulticastIp": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+    },
+)
+
+AddEgressGatewayBridgeRequestTypeDef = TypedDict(
+    "AddEgressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
     },
 )
 
 _RequiredVpcInterfaceRequestTypeDef = TypedDict(
     "_RequiredVpcInterfaceRequestTypeDef",
     {
         "Name": str,
@@ -200,14 +307,22 @@
         "NetworkInterfaceType": NetworkInterfaceTypeType,
         "RoleArn": str,
         "SecurityGroupIds": List[str],
         "SubnetId": str,
     },
 )
 
+AddIngressGatewayBridgeRequestTypeDef = TypedDict(
+    "AddIngressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
+        "MaxOutputs": int,
+    },
+)
+
 AddMaintenanceTypeDef = TypedDict(
     "AddMaintenanceTypeDef",
     {
         "MaintenanceDay": MaintenanceDayType,
         "MaintenanceStartHour": str,
     },
 )
@@ -232,29 +347,193 @@
     },
     total=False,
 )
 
 class EncryptionTypeDef(_RequiredEncryptionTypeDef, _OptionalEncryptionTypeDef):
     pass
 
-VpcInterfaceAttachmentTypeDef = TypedDict(
-    "VpcInterfaceAttachmentTypeDef",
+BridgeFlowOutputTypeDef = TypedDict(
+    "BridgeFlowOutputTypeDef",
     {
-        "VpcInterfaceName": str,
+        "FlowArn": str,
+        "FlowSourceArn": str,
+        "Name": str,
+    },
+)
+
+BridgeNetworkOutputTypeDef = TypedDict(
+    "BridgeNetworkOutputTypeDef",
+    {
+        "IpAddress": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+        "Ttl": int,
+    },
+)
+
+BridgeNetworkSourceTypeDef = TypedDict(
+    "BridgeNetworkSourceTypeDef",
+    {
+        "MulticastIp": str,
+        "Name": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+    },
+)
+
+_RequiredEgressGatewayBridgeTypeDef = TypedDict(
+    "_RequiredEgressGatewayBridgeTypeDef",
+    {
+        "MaxBitrate": int,
+    },
+)
+_OptionalEgressGatewayBridgeTypeDef = TypedDict(
+    "_OptionalEgressGatewayBridgeTypeDef",
+    {
+        "InstanceId": str,
     },
     total=False,
 )
 
+class EgressGatewayBridgeTypeDef(
+    _RequiredEgressGatewayBridgeTypeDef, _OptionalEgressGatewayBridgeTypeDef
+):
+    pass
+
+_RequiredIngressGatewayBridgeTypeDef = TypedDict(
+    "_RequiredIngressGatewayBridgeTypeDef",
+    {
+        "MaxBitrate": int,
+        "MaxOutputs": int,
+    },
+)
+_OptionalIngressGatewayBridgeTypeDef = TypedDict(
+    "_OptionalIngressGatewayBridgeTypeDef",
+    {
+        "InstanceId": str,
+    },
+    total=False,
+)
+
+class IngressGatewayBridgeTypeDef(
+    _RequiredIngressGatewayBridgeTypeDef, _OptionalIngressGatewayBridgeTypeDef
+):
+    pass
+
+_RequiredMessageDetailTypeDef = TypedDict(
+    "_RequiredMessageDetailTypeDef",
+    {
+        "Code": str,
+        "Message": str,
+    },
+)
+_OptionalMessageDetailTypeDef = TypedDict(
+    "_OptionalMessageDetailTypeDef",
+    {
+        "ResourceName": str,
+    },
+    total=False,
+)
+
+class MessageDetailTypeDef(_RequiredMessageDetailTypeDef, _OptionalMessageDetailTypeDef):
+    pass
+
+GatewayNetworkTypeDef = TypedDict(
+    "GatewayNetworkTypeDef",
+    {
+        "CidrBlock": str,
+        "Name": str,
+    },
+)
+
+DeleteBridgeRequestRequestTypeDef = TypedDict(
+    "DeleteBridgeRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+    },
+)
+
+DeleteBridgeResponseTypeDef = TypedDict(
+    "DeleteBridgeResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFlowRequestRequestTypeDef = TypedDict(
     "DeleteFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 
+DeleteFlowResponseTypeDef = TypedDict(
+    "DeleteFlowResponseTypeDef",
+    {
+        "FlowArn": str,
+        "Status": StatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteGatewayRequestRequestTypeDef = TypedDict(
+    "DeleteGatewayRequestRequestTypeDef",
+    {
+        "GatewayArn": str,
+    },
+)
+
+DeleteGatewayResponseTypeDef = TypedDict(
+    "DeleteGatewayResponseTypeDef",
+    {
+        "GatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDeregisterGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_RequiredDeregisterGatewayInstanceRequestRequestTypeDef",
+    {
+        "GatewayInstanceArn": str,
+    },
+)
+_OptionalDeregisterGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_OptionalDeregisterGatewayInstanceRequestRequestTypeDef",
+    {
+        "Force": bool,
+    },
+    total=False,
+)
+
+class DeregisterGatewayInstanceRequestRequestTypeDef(
+    _RequiredDeregisterGatewayInstanceRequestRequestTypeDef,
+    _OptionalDeregisterGatewayInstanceRequestRequestTypeDef,
+):
+    pass
+
+DeregisterGatewayInstanceResponseTypeDef = TypedDict(
+    "DeregisterGatewayInstanceResponseTypeDef",
+    {
+        "GatewayInstanceArn": str,
+        "InstanceState": InstanceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeBridgeRequestRequestTypeDef = TypedDict(
+    "DescribeBridgeRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -270,14 +549,28 @@
 MessagesTypeDef = TypedDict(
     "MessagesTypeDef",
     {
         "Errors": List[str],
     },
 )
 
+DescribeGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "DescribeGatewayInstanceRequestRequestTypeDef",
+    {
+        "GatewayInstanceArn": str,
+    },
+)
+
+DescribeGatewayRequestRequestTypeDef = TypedDict(
+    "DescribeGatewayRequestRequestTypeDef",
+    {
+        "GatewayArn": str,
+    },
+)
+
 DescribeOfferingRequestRequestTypeDef = TypedDict(
     "DescribeOfferingRequestRequestTypeDef",
     {
         "OfferingArn": str,
     },
 )
 
@@ -298,14 +591,21 @@
 InterfaceTypeDef = TypedDict(
     "InterfaceTypeDef",
     {
         "Name": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EncodingParametersRequestTypeDef = TypedDict(
     "EncodingParametersRequestTypeDef",
     {
         "CompressionFactor": float,
         "EncoderProfile": EncoderProfileType,
     },
 )
@@ -361,20 +661,48 @@
         "Range": RangeType,
         "ScanMode": ScanModeType,
         "Tcs": TcsType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListBridgesRequestListBridgesPaginateTypeDef = TypedDict(
+    "ListBridgesRequestListBridgesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FilterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListBridgesRequestRequestTypeDef = TypedDict(
+    "ListBridgesRequestRequestTypeDef",
+    {
+        "FilterArn": str,
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+ListedBridgeTypeDef = TypedDict(
+    "ListedBridgeTypeDef",
+    {
+        "BridgeArn": str,
+        "BridgeState": BridgeStateType,
+        "BridgeType": str,
+        "Name": str,
+        "PlacementArn": str,
+    },
+)
+
+ListEntitlementsRequestListEntitlementsPaginateTypeDef = TypedDict(
+    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEntitlementsRequestRequestTypeDef = TypedDict(
     "ListEntitlementsRequestRequestTypeDef",
     {
@@ -400,32 +728,122 @@
 )
 
 class ListedEntitlementTypeDef(
     _RequiredListedEntitlementTypeDef, _OptionalListedEntitlementTypeDef
 ):
     pass
 
+ListFlowsRequestListFlowsPaginateTypeDef = TypedDict(
+    "ListFlowsRequestListFlowsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFlowsRequestRequestTypeDef = TypedDict(
     "ListFlowsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef = TypedDict(
+    "ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef",
+    {
+        "FilterArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListGatewayInstancesRequestRequestTypeDef = TypedDict(
+    "ListGatewayInstancesRequestRequestTypeDef",
+    {
+        "FilterArn": str,
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+_RequiredListedGatewayInstanceTypeDef = TypedDict(
+    "_RequiredListedGatewayInstanceTypeDef",
+    {
+        "GatewayArn": str,
+        "GatewayInstanceArn": str,
+        "InstanceId": str,
+    },
+)
+_OptionalListedGatewayInstanceTypeDef = TypedDict(
+    "_OptionalListedGatewayInstanceTypeDef",
+    {
+        "InstanceState": InstanceStateType,
+    },
+    total=False,
+)
+
+class ListedGatewayInstanceTypeDef(
+    _RequiredListedGatewayInstanceTypeDef, _OptionalListedGatewayInstanceTypeDef
+):
+    pass
+
+ListGatewaysRequestListGatewaysPaginateTypeDef = TypedDict(
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListGatewaysRequestRequestTypeDef = TypedDict(
+    "ListGatewaysRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+ListedGatewayTypeDef = TypedDict(
+    "ListedGatewayTypeDef",
+    {
+        "GatewayArn": str,
+        "GatewayState": GatewayStateType,
+        "Name": str,
+    },
+)
+
+ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingsRequestRequestTypeDef = TypedDict(
     "ListOfferingsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
+    "ListReservationsRequestListReservationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReservationsRequestRequestTypeDef = TypedDict(
     "ListReservationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -434,14 +852,22 @@
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
 _RequiredResourceSpecificationTypeDef = TypedDict(
     "_RequiredResourceSpecificationTypeDef",
     {
         "ResourceType": Literal["Mbps_Outbound_Bandwidth"],
     },
 )
 _OptionalResourceSpecificationTypeDef = TypedDict(
@@ -481,77 +907,196 @@
     },
     total=False,
 )
 
 class TransportTypeDef(_RequiredTransportTypeDef, _OptionalTransportTypeDef):
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
 PurchaseOfferingRequestRequestTypeDef = TypedDict(
     "PurchaseOfferingRequestRequestTypeDef",
     {
         "OfferingArn": str,
         "ReservationName": str,
         "Start": str,
     },
 )
 
+RemoveBridgeOutputRequestRequestTypeDef = TypedDict(
+    "RemoveBridgeOutputRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "OutputName": str,
+    },
+)
+
+RemoveBridgeOutputResponseTypeDef = TypedDict(
+    "RemoveBridgeOutputResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "OutputName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RemoveBridgeSourceRequestRequestTypeDef = TypedDict(
+    "RemoveBridgeSourceRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "SourceName": str,
+    },
+)
+
+RemoveBridgeSourceResponseTypeDef = TypedDict(
+    "RemoveBridgeSourceResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "SourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowMediaStreamRequestRequestTypeDef = TypedDict(
     "RemoveFlowMediaStreamRequestRequestTypeDef",
     {
         "FlowArn": str,
         "MediaStreamName": str,
     },
 )
 
+RemoveFlowMediaStreamResponseTypeDef = TypedDict(
+    "RemoveFlowMediaStreamResponseTypeDef",
+    {
+        "FlowArn": str,
+        "MediaStreamName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowOutputRequestRequestTypeDef = TypedDict(
     "RemoveFlowOutputRequestRequestTypeDef",
     {
         "FlowArn": str,
         "OutputArn": str,
     },
 )
 
+RemoveFlowOutputResponseTypeDef = TypedDict(
+    "RemoveFlowOutputResponseTypeDef",
+    {
+        "FlowArn": str,
+        "OutputArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowSourceRequestRequestTypeDef = TypedDict(
     "RemoveFlowSourceRequestRequestTypeDef",
     {
         "FlowArn": str,
         "SourceArn": str,
     },
 )
 
+RemoveFlowSourceResponseTypeDef = TypedDict(
+    "RemoveFlowSourceResponseTypeDef",
+    {
+        "FlowArn": str,
+        "SourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveFlowVpcInterfaceRequestRequestTypeDef = TypedDict(
     "RemoveFlowVpcInterfaceRequestRequestTypeDef",
     {
         "FlowArn": str,
         "VpcInterfaceName": str,
     },
 )
 
+RemoveFlowVpcInterfaceResponseTypeDef = TypedDict(
+    "RemoveFlowVpcInterfaceResponseTypeDef",
+    {
+        "FlowArn": str,
+        "NonDeletedNetworkInterfaceIds": List[str],
+        "VpcInterfaceName": str,
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
 RevokeFlowEntitlementRequestRequestTypeDef = TypedDict(
     "RevokeFlowEntitlementRequestRequestTypeDef",
     {
         "EntitlementArn": str,
         "FlowArn": str,
     },
 )
 
+RevokeFlowEntitlementResponseTypeDef = TypedDict(
+    "RevokeFlowEntitlementResponseTypeDef",
+    {
+        "EntitlementArn": str,
+        "FlowArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartFlowRequestRequestTypeDef = TypedDict(
     "StartFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 
+StartFlowResponseTypeDef = TypedDict(
+    "StartFlowResponseTypeDef",
+    {
+        "FlowArn": str,
+        "Status": StatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopFlowRequestRequestTypeDef = TypedDict(
     "StopFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 
+StopFlowResponseTypeDef = TypedDict(
+    "StopFlowResponseTypeDef",
+    {
+        "FlowArn": str,
+        "Status": StatusType,
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
@@ -560,14 +1105,71 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateBridgeNetworkOutputRequestTypeDef = TypedDict(
+    "UpdateBridgeNetworkOutputRequestTypeDef",
+    {
+        "IpAddress": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+        "Ttl": int,
+    },
+    total=False,
+)
+
+UpdateBridgeNetworkSourceRequestTypeDef = TypedDict(
+    "UpdateBridgeNetworkSourceRequestTypeDef",
+    {
+        "MulticastIp": str,
+        "NetworkName": str,
+        "Port": int,
+        "Protocol": ProtocolType,
+    },
+    total=False,
+)
+
+UpdateEgressGatewayBridgeRequestTypeDef = TypedDict(
+    "UpdateEgressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
+    },
+    total=False,
+)
+
+UpdateIngressGatewayBridgeRequestTypeDef = TypedDict(
+    "UpdateIngressGatewayBridgeRequestTypeDef",
+    {
+        "MaxBitrate": int,
+        "MaxOutputs": int,
+    },
+    total=False,
+)
+
+UpdateBridgeStateRequestRequestTypeDef = TypedDict(
+    "UpdateBridgeStateRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "DesiredState": DesiredStateType,
+    },
+)
+
+UpdateBridgeStateResponseTypeDef = TypedDict(
+    "UpdateBridgeStateResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "DesiredState": DesiredStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateEncryptionTypeDef = TypedDict(
     "UpdateEncryptionTypeDef",
     {
         "Algorithm": AlgorithmType,
         "ConstantInitializationVector": str,
         "DeviceId": str,
         "KeyType": KeyTypeType,
@@ -586,100 +1188,144 @@
         "MaintenanceDay": MaintenanceDayType,
         "MaintenanceScheduledDate": str,
         "MaintenanceStartHour": str,
     },
     total=False,
 )
 
-DeleteFlowResponseTypeDef = TypedDict(
-    "DeleteFlowResponseTypeDef",
+_RequiredUpdateGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateGatewayInstanceRequestRequestTypeDef",
     {
-        "FlowArn": str,
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GatewayInstanceArn": str,
     },
 )
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+_OptionalUpdateGatewayInstanceRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateGatewayInstanceRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgePlacement": BridgePlacementType,
     },
+    total=False,
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+class UpdateGatewayInstanceRequestRequestTypeDef(
+    _RequiredUpdateGatewayInstanceRequestRequestTypeDef,
+    _OptionalUpdateGatewayInstanceRequestRequestTypeDef,
+):
+    pass
+
+UpdateGatewayInstanceResponseTypeDef = TypedDict(
+    "UpdateGatewayInstanceResponseTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgePlacement": BridgePlacementType,
+        "GatewayInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RemoveFlowMediaStreamResponseTypeDef = TypedDict(
-    "RemoveFlowMediaStreamResponseTypeDef",
+_RequiredAddBridgeFlowSourceRequestTypeDef = TypedDict(
+    "_RequiredAddBridgeFlowSourceRequestTypeDef",
     {
         "FlowArn": str,
-        "MediaStreamName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Name": str,
+    },
+)
+_OptionalAddBridgeFlowSourceRequestTypeDef = TypedDict(
+    "_OptionalAddBridgeFlowSourceRequestTypeDef",
+    {
+        "FlowVpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-RemoveFlowOutputResponseTypeDef = TypedDict(
-    "RemoveFlowOutputResponseTypeDef",
+class AddBridgeFlowSourceRequestTypeDef(
+    _RequiredAddBridgeFlowSourceRequestTypeDef, _OptionalAddBridgeFlowSourceRequestTypeDef
+):
+    pass
+
+_RequiredBridgeFlowSourceTypeDef = TypedDict(
+    "_RequiredBridgeFlowSourceTypeDef",
     {
         "FlowArn": str,
+        "Name": str,
+    },
+)
+_OptionalBridgeFlowSourceTypeDef = TypedDict(
+    "_OptionalBridgeFlowSourceTypeDef",
+    {
+        "FlowVpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
         "OutputArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-RemoveFlowSourceResponseTypeDef = TypedDict(
-    "RemoveFlowSourceResponseTypeDef",
+class BridgeFlowSourceTypeDef(_RequiredBridgeFlowSourceTypeDef, _OptionalBridgeFlowSourceTypeDef):
+    pass
+
+_RequiredGatewayBridgeSourceTypeDef = TypedDict(
+    "_RequiredGatewayBridgeSourceTypeDef",
     {
-        "FlowArn": str,
-        "SourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgeArn": str,
+    },
+)
+_OptionalGatewayBridgeSourceTypeDef = TypedDict(
+    "_OptionalGatewayBridgeSourceTypeDef",
+    {
+        "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-RemoveFlowVpcInterfaceResponseTypeDef = TypedDict(
-    "RemoveFlowVpcInterfaceResponseTypeDef",
+class GatewayBridgeSourceTypeDef(
+    _RequiredGatewayBridgeSourceTypeDef, _OptionalGatewayBridgeSourceTypeDef
+):
+    pass
+
+_RequiredSetGatewayBridgeSourceRequestTypeDef = TypedDict(
+    "_RequiredSetGatewayBridgeSourceRequestTypeDef",
     {
-        "FlowArn": str,
-        "NonDeletedNetworkInterfaceIds": List[str],
-        "VpcInterfaceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgeArn": str,
+    },
+)
+_OptionalSetGatewayBridgeSourceRequestTypeDef = TypedDict(
+    "_OptionalSetGatewayBridgeSourceRequestTypeDef",
+    {
+        "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-RevokeFlowEntitlementResponseTypeDef = TypedDict(
-    "RevokeFlowEntitlementResponseTypeDef",
+class SetGatewayBridgeSourceRequestTypeDef(
+    _RequiredSetGatewayBridgeSourceRequestTypeDef, _OptionalSetGatewayBridgeSourceRequestTypeDef
+):
+    pass
+
+UpdateBridgeFlowSourceRequestTypeDef = TypedDict(
+    "UpdateBridgeFlowSourceRequestTypeDef",
     {
-        "EntitlementArn": str,
         "FlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FlowVpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-StartFlowResponseTypeDef = TypedDict(
-    "StartFlowResponseTypeDef",
+UpdateGatewayBridgeSourceRequestTypeDef = TypedDict(
+    "UpdateGatewayBridgeSourceRequestTypeDef",
     {
-        "FlowArn": str,
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BridgeArn": str,
+        "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
     },
+    total=False,
 )
 
-StopFlowResponseTypeDef = TypedDict(
-    "StopFlowResponseTypeDef",
+AddBridgeOutputRequestTypeDef = TypedDict(
+    "AddBridgeOutputRequestTypeDef",
     {
-        "FlowArn": str,
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NetworkOutput": AddBridgeNetworkOutputRequestTypeDef,
     },
+    total=False,
 )
 
 AddFlowVpcInterfacesRequestRequestTypeDef = TypedDict(
     "AddFlowVpcInterfacesRequestRequestTypeDef",
     {
         "FlowArn": str,
         "VpcInterfaces": Sequence[VpcInterfaceRequestTypeDef],
@@ -687,15 +1333,15 @@
 )
 
 AddFlowVpcInterfacesResponseTypeDef = TypedDict(
     "AddFlowVpcInterfacesResponseTypeDef",
     {
         "FlowArn": str,
         "VpcInterfaces": List[VpcInterfaceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEntitlementTypeDef = TypedDict(
     "_RequiredEntitlementTypeDef",
     {
         "EntitlementArn": str,
@@ -736,14 +1382,76 @@
 )
 
 class GrantEntitlementRequestTypeDef(
     _RequiredGrantEntitlementRequestTypeDef, _OptionalGrantEntitlementRequestTypeDef
 ):
     pass
 
+BridgeOutputTypeDef = TypedDict(
+    "BridgeOutputTypeDef",
+    {
+        "FlowOutput": BridgeFlowOutputTypeDef,
+        "NetworkOutput": BridgeNetworkOutputTypeDef,
+    },
+    total=False,
+)
+
+_RequiredGatewayInstanceTypeDef = TypedDict(
+    "_RequiredGatewayInstanceTypeDef",
+    {
+        "BridgePlacement": BridgePlacementType,
+        "ConnectionStatus": ConnectionStatusType,
+        "GatewayArn": str,
+        "GatewayInstanceArn": str,
+        "InstanceId": str,
+        "InstanceState": InstanceStateType,
+        "RunningBridgeCount": int,
+    },
+)
+_OptionalGatewayInstanceTypeDef = TypedDict(
+    "_OptionalGatewayInstanceTypeDef",
+    {
+        "InstanceMessages": List[MessageDetailTypeDef],
+    },
+    total=False,
+)
+
+class GatewayInstanceTypeDef(_RequiredGatewayInstanceTypeDef, _OptionalGatewayInstanceTypeDef):
+    pass
+
+CreateGatewayRequestRequestTypeDef = TypedDict(
+    "CreateGatewayRequestRequestTypeDef",
+    {
+        "EgressCidrBlocks": Sequence[str],
+        "Name": str,
+        "Networks": Sequence[GatewayNetworkTypeDef],
+    },
+)
+
+_RequiredGatewayTypeDef = TypedDict(
+    "_RequiredGatewayTypeDef",
+    {
+        "EgressCidrBlocks": List[str],
+        "GatewayArn": str,
+        "Name": str,
+        "Networks": List[GatewayNetworkTypeDef],
+    },
+)
+_OptionalGatewayTypeDef = TypedDict(
+    "_OptionalGatewayTypeDef",
+    {
+        "GatewayMessages": List[MessageDetailTypeDef],
+        "GatewayState": GatewayStateType,
+    },
+    total=False,
+)
+
+class GatewayTypeDef(_RequiredGatewayTypeDef, _OptionalGatewayTypeDef):
+    pass
+
 _RequiredDescribeFlowRequestFlowActiveWaitTypeDef = TypedDict(
     "_RequiredDescribeFlowRequestFlowActiveWaitTypeDef",
     {
         "FlowArn": str,
     },
 )
 _OptionalDescribeFlowRequestFlowActiveWaitTypeDef = TypedDict(
@@ -904,52 +1612,47 @@
 )
 
 class MediaStreamAttributesTypeDef(
     _RequiredMediaStreamAttributesTypeDef, _OptionalMediaStreamAttributesTypeDef
 ):
     pass
 
-ListEntitlementsRequestListEntitlementsPaginateTypeDef = TypedDict(
-    "ListEntitlementsRequestListEntitlementsPaginateTypeDef",
+ListBridgesResponseTypeDef = TypedDict(
+    "ListBridgesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Bridges": List[ListedBridgeTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListFlowsRequestListFlowsPaginateTypeDef = TypedDict(
-    "ListFlowsRequestListFlowsPaginateTypeDef",
+ListEntitlementsResponseTypeDef = TypedDict(
+    "ListEntitlementsResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Entitlements": List[ListedEntitlementTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+ListGatewayInstancesResponseTypeDef = TypedDict(
+    "ListGatewayInstancesResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Instances": List[ListedGatewayInstanceTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
-    "ListReservationsRequestListReservationsPaginateTypeDef",
+ListGatewaysResponseTypeDef = TypedDict(
+    "ListGatewaysResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEntitlementsResponseTypeDef = TypedDict(
-    "ListEntitlementsResponseTypeDef",
-    {
-        "Entitlements": List[ListedEntitlementTypeDef],
+        "Gateways": List[ListedGatewayTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTypeDef = TypedDict(
     "OfferingTypeDef",
     {
         "CurrencyCode": str,
@@ -978,14 +1681,35 @@
         "ReservationName": str,
         "ReservationState": ReservationStateType,
         "ResourceSpecification": ResourceSpecificationTypeDef,
         "Start": str,
     },
 )
 
+_RequiredUpdateBridgeOutputRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateBridgeOutputRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "OutputName": str,
+    },
+)
+_OptionalUpdateBridgeOutputRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateBridgeOutputRequestRequestTypeDef",
+    {
+        "NetworkOutput": UpdateBridgeNetworkOutputRequestTypeDef,
+    },
+    total=False,
+)
+
+class UpdateBridgeOutputRequestRequestTypeDef(
+    _RequiredUpdateBridgeOutputRequestRequestTypeDef,
+    _OptionalUpdateBridgeOutputRequestRequestTypeDef,
+):
+    pass
+
 _RequiredUpdateFlowEntitlementRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowEntitlementRequestRequestTypeDef",
     {
         "EntitlementArn": str,
         "FlowArn": str,
     },
 )
@@ -1002,40 +1726,130 @@
 
 class UpdateFlowEntitlementRequestRequestTypeDef(
     _RequiredUpdateFlowEntitlementRequestRequestTypeDef,
     _OptionalUpdateFlowEntitlementRequestRequestTypeDef,
 ):
     pass
 
+AddBridgeSourceRequestTypeDef = TypedDict(
+    "AddBridgeSourceRequestTypeDef",
+    {
+        "FlowSource": AddBridgeFlowSourceRequestTypeDef,
+        "NetworkSource": AddBridgeNetworkSourceRequestTypeDef,
+    },
+    total=False,
+)
+
+BridgeSourceTypeDef = TypedDict(
+    "BridgeSourceTypeDef",
+    {
+        "FlowSource": BridgeFlowSourceTypeDef,
+        "NetworkSource": BridgeNetworkSourceTypeDef,
+    },
+    total=False,
+)
+
+_RequiredUpdateBridgeSourceRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateBridgeSourceRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "SourceName": str,
+    },
+)
+_OptionalUpdateBridgeSourceRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateBridgeSourceRequestRequestTypeDef",
+    {
+        "FlowSource": UpdateBridgeFlowSourceRequestTypeDef,
+        "NetworkSource": UpdateBridgeNetworkSourceRequestTypeDef,
+    },
+    total=False,
+)
+
+class UpdateBridgeSourceRequestRequestTypeDef(
+    _RequiredUpdateBridgeSourceRequestRequestTypeDef,
+    _OptionalUpdateBridgeSourceRequestRequestTypeDef,
+):
+    pass
+
+AddBridgeOutputsRequestRequestTypeDef = TypedDict(
+    "AddBridgeOutputsRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "Outputs": Sequence[AddBridgeOutputRequestTypeDef],
+    },
+)
+
 GrantFlowEntitlementsResponseTypeDef = TypedDict(
     "GrantFlowEntitlementsResponseTypeDef",
     {
         "Entitlements": List[EntitlementTypeDef],
         "FlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowEntitlementResponseTypeDef = TypedDict(
     "UpdateFlowEntitlementResponseTypeDef",
     {
         "Entitlement": EntitlementTypeDef,
         "FlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GrantFlowEntitlementsRequestRequestTypeDef = TypedDict(
     "GrantFlowEntitlementsRequestRequestTypeDef",
     {
         "Entitlements": Sequence[GrantEntitlementRequestTypeDef],
         "FlowArn": str,
     },
 )
 
+AddBridgeOutputsResponseTypeDef = TypedDict(
+    "AddBridgeOutputsResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Outputs": List[BridgeOutputTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBridgeOutputResponseTypeDef = TypedDict(
+    "UpdateBridgeOutputResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Output": BridgeOutputTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeGatewayInstanceResponseTypeDef = TypedDict(
+    "DescribeGatewayInstanceResponseTypeDef",
+    {
+        "GatewayInstance": GatewayInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateGatewayResponseTypeDef = TypedDict(
+    "CreateGatewayResponseTypeDef",
+    {
+        "Gateway": GatewayTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeGatewayResponseTypeDef = TypedDict(
+    "DescribeGatewayResponseTypeDef",
+    {
+        "Gateway": GatewayTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMediaStreamOutputConfigurationRequestTypeDef = TypedDict(
     "_RequiredMediaStreamOutputConfigurationRequestTypeDef",
     {
         "EncodingName": EncodingNameType,
         "MediaStreamName": str,
     },
 )
@@ -1112,14 +1926,35 @@
 )
 
 class MediaStreamSourceConfigurationTypeDef(
     _RequiredMediaStreamSourceConfigurationTypeDef, _OptionalMediaStreamSourceConfigurationTypeDef
 ):
     pass
 
+_RequiredUpdateBridgeRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateBridgeRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+    },
+)
+_OptionalUpdateBridgeRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateBridgeRequestRequestTypeDef",
+    {
+        "EgressGatewayBridge": UpdateEgressGatewayBridgeRequestTypeDef,
+        "IngressGatewayBridge": UpdateIngressGatewayBridgeRequestTypeDef,
+        "SourceFailoverConfig": UpdateFailoverConfigTypeDef,
+    },
+    total=False,
+)
+
+class UpdateBridgeRequestRequestTypeDef(
+    _RequiredUpdateBridgeRequestRequestTypeDef, _OptionalUpdateBridgeRequestRequestTypeDef
+):
+    pass
+
 _RequiredUpdateFlowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowRequestRequestTypeDef",
     {
         "FlowArn": str,
     },
 )
 _OptionalUpdateFlowRequestRequestTypeDef = TypedDict(
@@ -1137,15 +1972,15 @@
     pass
 
 ListFlowsResponseTypeDef = TypedDict(
     "ListFlowsResponseTypeDef",
     {
         "Flows": List[ListedFlowTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddMediaStreamRequestTypeDef = TypedDict(
     "_RequiredAddMediaStreamRequestTypeDef",
     {
         "MediaStreamId": int,
@@ -1217,49 +2052,124 @@
 class MediaStreamTypeDef(_RequiredMediaStreamTypeDef, _OptionalMediaStreamTypeDef):
     pass
 
 DescribeOfferingResponseTypeDef = TypedDict(
     "DescribeOfferingResponseTypeDef",
     {
         "Offering": OfferingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingsResponseTypeDef = TypedDict(
     "ListOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "Offerings": List[OfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservationResponseTypeDef = TypedDict(
     "DescribeReservationResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReservationsResponseTypeDef = TypedDict(
     "ListReservationsResponseTypeDef",
     {
         "NextToken": str,
         "Reservations": List[ReservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseOfferingResponseTypeDef = TypedDict(
     "PurchaseOfferingResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AddBridgeSourcesRequestRequestTypeDef = TypedDict(
+    "AddBridgeSourcesRequestRequestTypeDef",
+    {
+        "BridgeArn": str,
+        "Sources": Sequence[AddBridgeSourceRequestTypeDef],
+    },
+)
+
+_RequiredCreateBridgeRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateBridgeRequestRequestTypeDef",
+    {
+        "Name": str,
+        "PlacementArn": str,
+        "Sources": Sequence[AddBridgeSourceRequestTypeDef],
+    },
+)
+_OptionalCreateBridgeRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateBridgeRequestRequestTypeDef",
+    {
+        "EgressGatewayBridge": AddEgressGatewayBridgeRequestTypeDef,
+        "IngressGatewayBridge": AddIngressGatewayBridgeRequestTypeDef,
+        "Outputs": Sequence[AddBridgeOutputRequestTypeDef],
+        "SourceFailoverConfig": FailoverConfigTypeDef,
+    },
+    total=False,
+)
+
+class CreateBridgeRequestRequestTypeDef(
+    _RequiredCreateBridgeRequestRequestTypeDef, _OptionalCreateBridgeRequestRequestTypeDef
+):
+    pass
+
+AddBridgeSourcesResponseTypeDef = TypedDict(
+    "AddBridgeSourcesResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Sources": List[BridgeSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredBridgeTypeDef = TypedDict(
+    "_RequiredBridgeTypeDef",
+    {
+        "BridgeArn": str,
+        "BridgeState": BridgeStateType,
+        "Name": str,
+        "PlacementArn": str,
+    },
+)
+_OptionalBridgeTypeDef = TypedDict(
+    "_OptionalBridgeTypeDef",
+    {
+        "BridgeMessages": List[MessageDetailTypeDef],
+        "EgressGatewayBridge": EgressGatewayBridgeTypeDef,
+        "IngressGatewayBridge": IngressGatewayBridgeTypeDef,
+        "Outputs": List[BridgeOutputTypeDef],
+        "SourceFailoverConfig": FailoverConfigTypeDef,
+        "Sources": List[BridgeSourceTypeDef],
+    },
+    total=False,
+)
+
+class BridgeTypeDef(_RequiredBridgeTypeDef, _OptionalBridgeTypeDef):
+    pass
+
+UpdateBridgeSourceResponseTypeDef = TypedDict(
+    "UpdateBridgeSourceResponseTypeDef",
+    {
+        "BridgeArn": str,
+        "Source": BridgeSourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddOutputRequestTypeDef = TypedDict(
     "_RequiredAddOutputRequestTypeDef",
     {
         "Protocol": ProtocolType,
@@ -1340,14 +2250,15 @@
         "SenderControlPort": int,
         "SenderIpAddress": str,
         "SourceListenerAddress": str,
         "SourceListenerPort": int,
         "StreamId": str,
         "VpcInterfaceName": str,
         "WhitelistCidr": str,
+        "GatewayBridgeSource": SetGatewayBridgeSourceRequestTypeDef,
     },
     total=False,
 )
 
 _RequiredUpdateFlowSourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowSourceRequestRequestTypeDef",
     {
@@ -1371,14 +2282,15 @@
         "SenderControlPort": int,
         "SenderIpAddress": str,
         "SourceListenerAddress": str,
         "SourceListenerPort": int,
         "StreamId": str,
         "VpcInterfaceName": str,
         "WhitelistCidr": str,
+        "GatewayBridgeSource": UpdateGatewayBridgeSourceRequestTypeDef,
     },
     total=False,
 )
 
 class UpdateFlowSourceRequestRequestTypeDef(
     _RequiredUpdateFlowSourceRequestRequestTypeDef, _OptionalUpdateFlowSourceRequestRequestTypeDef
 ):
@@ -1401,14 +2313,16 @@
         "EntitlementArn": str,
         "ListenerAddress": str,
         "MediaLiveInputArn": str,
         "MediaStreamOutputConfigurations": List[MediaStreamOutputConfigurationTypeDef],
         "Port": int,
         "Transport": TransportTypeDef,
         "VpcInterfaceAttachment": VpcInterfaceAttachmentTypeDef,
+        "BridgeArn": str,
+        "BridgePorts": List[int],
     },
     total=False,
 )
 
 class OutputTypeDef(_RequiredOutputTypeDef, _OptionalOutputTypeDef):
     pass
 
@@ -1430,14 +2344,15 @@
         "IngestPort": int,
         "MediaStreamSourceConfigurations": List[MediaStreamSourceConfigurationTypeDef],
         "SenderControlPort": int,
         "SenderIpAddress": str,
         "Transport": TransportTypeDef,
         "VpcInterfaceName": str,
         "WhitelistCidr": str,
+        "GatewayBridgeSource": GatewayBridgeSourceTypeDef,
     },
     total=False,
 )
 
 class SourceTypeDef(_RequiredSourceTypeDef, _OptionalSourceTypeDef):
     pass
 
@@ -1450,24 +2365,48 @@
 )
 
 AddFlowMediaStreamsResponseTypeDef = TypedDict(
     "AddFlowMediaStreamsResponseTypeDef",
     {
         "FlowArn": str,
         "MediaStreams": List[MediaStreamTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowMediaStreamResponseTypeDef = TypedDict(
     "UpdateFlowMediaStreamResponseTypeDef",
     {
         "FlowArn": str,
         "MediaStream": MediaStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateBridgeResponseTypeDef = TypedDict(
+    "CreateBridgeResponseTypeDef",
+    {
+        "Bridge": BridgeTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeBridgeResponseTypeDef = TypedDict(
+    "DescribeBridgeResponseTypeDef",
+    {
+        "Bridge": BridgeTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBridgeResponseTypeDef = TypedDict(
+    "UpdateBridgeResponseTypeDef",
+    {
+        "Bridge": BridgeTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddFlowOutputsRequestRequestTypeDef = TypedDict(
     "AddFlowOutputsRequestRequestTypeDef",
     {
         "FlowArn": str,
@@ -1511,33 +2450,33 @@
     pass
 
 AddFlowOutputsResponseTypeDef = TypedDict(
     "AddFlowOutputsResponseTypeDef",
     {
         "FlowArn": str,
         "Outputs": List[OutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowOutputResponseTypeDef = TypedDict(
     "UpdateFlowOutputResponseTypeDef",
     {
         "FlowArn": str,
         "Output": OutputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddFlowSourcesResponseTypeDef = TypedDict(
     "AddFlowSourcesResponseTypeDef",
     {
         "FlowArn": str,
         "Sources": List[SourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFlowTypeDef = TypedDict(
     "_RequiredFlowTypeDef",
     {
         "AvailabilityZone": str,
@@ -1567,35 +2506,35 @@
     pass
 
 UpdateFlowSourceResponseTypeDef = TypedDict(
     "UpdateFlowSourceResponseTypeDef",
     {
         "FlowArn": str,
         "Source": SourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFlowResponseTypeDef = TypedDict(
     "CreateFlowResponseTypeDef",
     {
         "Flow": FlowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFlowResponseTypeDef = TypedDict(
     "DescribeFlowResponseTypeDef",
     {
         "Flow": FlowTypeDef,
         "Messages": MessagesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowResponseTypeDef = TypedDict(
     "UpdateFlowResponseTypeDef",
     {
         "Flow": FlowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/waiter.py` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect/waiter.pyi` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/PKG-INFO` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediaconnect
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaConnect 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaConnect 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediaconnect"></a>
 
 # types-aiobotocore-mediaconnect
 
 [![PyPI - types-aiobotocore-mediaconnect](https://img.shields.io/pypi/v/types-aiobotocore-mediaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconnect)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediaconnect.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediaconnect)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediaconnect?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediaconnect)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaConnect 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
+[aiobotocore.MediaConnect 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediaconnect.html#MediaConnect)
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
 [types-aiobotocore-mediaconnect docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediaconnect/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,30 +274,38 @@
 all paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_mediaconnect import MediaConnectClient
 from types_aiobotocore_mediaconnect.paginator import (
+    ListBridgesPaginator,
     ListEntitlementsPaginator,
     ListFlowsPaginator,
+    ListGatewayInstancesPaginator,
+    ListGatewaysPaginator,
     ListOfferingsPaginator,
     ListReservationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("mediaconnect") as client:
     client: MediaConnectClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
+    list_bridges_paginator: ListBridgesPaginator = client.get_paginator("list_bridges")
     list_entitlements_paginator: ListEntitlementsPaginator = client.get_paginator(
         "list_entitlements"
     )
     list_flows_paginator: ListFlowsPaginator = client.get_paginator("list_flows")
+    list_gateway_instances_paginator: ListGatewayInstancesPaginator = client.get_paginator(
+        "list_gateway_instances"
+    )
+    list_gateways_paginator: ListGatewaysPaginator = client.get_paginator("list_gateways")
     list_offerings_paginator: ListOfferingsPaginator = client.get_paginator("list_offerings")
     list_reservations_paginator: ListReservationsPaginator = client.get_paginator(
         "list_reservations"
     )
 ```
 
 <a id="waiters-annotations"></a>
@@ -334,26 +342,35 @@
 
 `types_aiobotocore_mediaconnect.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mediaconnect.literals import (
     AlgorithmType,
+    BridgePlacementType,
+    BridgeStateType,
     ColorimetryType,
+    ConnectionStatusType,
+    DesiredStateType,
     DurationUnitsType,
     EncoderProfileType,
     EncodingNameType,
     EntitlementStatusType,
     FailoverModeType,
     FlowActiveWaiterName,
     FlowDeletedWaiterName,
     FlowStandbyWaiterName,
+    GatewayStateType,
+    InstanceStateType,
     KeyTypeType,
+    ListBridgesPaginatorName,
     ListEntitlementsPaginatorName,
     ListFlowsPaginatorName,
+    ListGatewayInstancesPaginatorName,
+    ListGatewaysPaginatorName,
     ListOfferingsPaginatorName,
     ListReservationsPaginatorName,
     MaintenanceDayType,
     MediaStreamTypeType,
     NetworkInterfaceTypeType,
     PriceUnitsType,
     ProtocolType,
@@ -383,169 +400,243 @@
 ### Typed dictionaries
 
 `types_aiobotocore_mediaconnect.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediaconnect.type_defs import (
-    ResponseMetadataTypeDef,
+    VpcInterfaceAttachmentTypeDef,
+    AddBridgeNetworkOutputRequestTypeDef,
+    AddBridgeNetworkSourceRequestTypeDef,
+    AddEgressGatewayBridgeRequestTypeDef,
     VpcInterfaceRequestTypeDef,
     VpcInterfaceTypeDef,
+    AddIngressGatewayBridgeRequestTypeDef,
     AddMaintenanceTypeDef,
     EncryptionTypeDef,
-    VpcInterfaceAttachmentTypeDef,
+    BridgeFlowOutputTypeDef,
+    BridgeNetworkOutputTypeDef,
+    BridgeNetworkSourceTypeDef,
+    EgressGatewayBridgeTypeDef,
+    IngressGatewayBridgeTypeDef,
+    MessageDetailTypeDef,
+    GatewayNetworkTypeDef,
+    DeleteBridgeRequestRequestTypeDef,
+    DeleteBridgeResponseTypeDef,
     DeleteFlowRequestRequestTypeDef,
+    DeleteFlowResponseTypeDef,
+    DeleteGatewayRequestRequestTypeDef,
+    DeleteGatewayResponseTypeDef,
+    DeregisterGatewayInstanceRequestRequestTypeDef,
+    DeregisterGatewayInstanceResponseTypeDef,
+    DescribeBridgeRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeFlowRequestRequestTypeDef,
     MessagesTypeDef,
+    DescribeGatewayInstanceRequestRequestTypeDef,
+    DescribeGatewayRequestRequestTypeDef,
     DescribeOfferingRequestRequestTypeDef,
     DescribeReservationRequestRequestTypeDef,
     InterfaceRequestTypeDef,
     InterfaceTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncodingParametersRequestTypeDef,
     EncodingParametersTypeDef,
     SourcePriorityTypeDef,
     MaintenanceTypeDef,
     FmtpRequestTypeDef,
     FmtpTypeDef,
-    PaginatorConfigTypeDef,
+    ListBridgesRequestListBridgesPaginateTypeDef,
+    ListBridgesRequestRequestTypeDef,
+    ListedBridgeTypeDef,
+    ListEntitlementsRequestListEntitlementsPaginateTypeDef,
     ListEntitlementsRequestRequestTypeDef,
     ListedEntitlementTypeDef,
+    ListFlowsRequestListFlowsPaginateTypeDef,
     ListFlowsRequestRequestTypeDef,
+    ListGatewayInstancesRequestListGatewayInstancesPaginateTypeDef,
+    ListGatewayInstancesRequestRequestTypeDef,
+    ListedGatewayInstanceTypeDef,
+    ListGatewaysRequestListGatewaysPaginateTypeDef,
+    ListGatewaysRequestRequestTypeDef,
+    ListedGatewayTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListReservationsRequestListReservationsPaginateTypeDef,
     ListReservationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ResourceSpecificationTypeDef,
     TransportTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
+    RemoveBridgeOutputRequestRequestTypeDef,
+    RemoveBridgeOutputResponseTypeDef,
+    RemoveBridgeSourceRequestRequestTypeDef,
+    RemoveBridgeSourceResponseTypeDef,
     RemoveFlowMediaStreamRequestRequestTypeDef,
+    RemoveFlowMediaStreamResponseTypeDef,
     RemoveFlowOutputRequestRequestTypeDef,
+    RemoveFlowOutputResponseTypeDef,
     RemoveFlowSourceRequestRequestTypeDef,
+    RemoveFlowSourceResponseTypeDef,
     RemoveFlowVpcInterfaceRequestRequestTypeDef,
+    RemoveFlowVpcInterfaceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RevokeFlowEntitlementRequestRequestTypeDef,
+    RevokeFlowEntitlementResponseTypeDef,
     StartFlowRequestRequestTypeDef,
+    StartFlowResponseTypeDef,
     StopFlowRequestRequestTypeDef,
+    StopFlowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateBridgeNetworkOutputRequestTypeDef,
+    UpdateBridgeNetworkSourceRequestTypeDef,
+    UpdateEgressGatewayBridgeRequestTypeDef,
+    UpdateIngressGatewayBridgeRequestTypeDef,
+    UpdateBridgeStateRequestRequestTypeDef,
+    UpdateBridgeStateResponseTypeDef,
     UpdateEncryptionTypeDef,
     UpdateMaintenanceTypeDef,
-    DeleteFlowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RemoveFlowMediaStreamResponseTypeDef,
-    RemoveFlowOutputResponseTypeDef,
-    RemoveFlowSourceResponseTypeDef,
-    RemoveFlowVpcInterfaceResponseTypeDef,
-    RevokeFlowEntitlementResponseTypeDef,
-    StartFlowResponseTypeDef,
-    StopFlowResponseTypeDef,
+    UpdateGatewayInstanceRequestRequestTypeDef,
+    UpdateGatewayInstanceResponseTypeDef,
+    AddBridgeFlowSourceRequestTypeDef,
+    BridgeFlowSourceTypeDef,
+    GatewayBridgeSourceTypeDef,
+    SetGatewayBridgeSourceRequestTypeDef,
+    UpdateBridgeFlowSourceRequestTypeDef,
+    UpdateGatewayBridgeSourceRequestTypeDef,
+    AddBridgeOutputRequestTypeDef,
     AddFlowVpcInterfacesRequestRequestTypeDef,
     AddFlowVpcInterfacesResponseTypeDef,
     EntitlementTypeDef,
     GrantEntitlementRequestTypeDef,
+    BridgeOutputTypeDef,
+    GatewayInstanceTypeDef,
+    CreateGatewayRequestRequestTypeDef,
+    GatewayTypeDef,
     DescribeFlowRequestFlowActiveWaitTypeDef,
     DescribeFlowRequestFlowDeletedWaitTypeDef,
     DescribeFlowRequestFlowStandbyWaitTypeDef,
     DestinationConfigurationRequestTypeDef,
     InputConfigurationRequestTypeDef,
     DestinationConfigurationTypeDef,
     InputConfigurationTypeDef,
     FailoverConfigTypeDef,
     UpdateFailoverConfigTypeDef,
     ListedFlowTypeDef,
     MediaStreamAttributesRequestTypeDef,
     MediaStreamAttributesTypeDef,
-    ListEntitlementsRequestListEntitlementsPaginateTypeDef,
-    ListFlowsRequestListFlowsPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListReservationsRequestListReservationsPaginateTypeDef,
+    ListBridgesResponseTypeDef,
     ListEntitlementsResponseTypeDef,
+    ListGatewayInstancesResponseTypeDef,
+    ListGatewaysResponseTypeDef,
     OfferingTypeDef,
     ReservationTypeDef,
+    UpdateBridgeOutputRequestRequestTypeDef,
     UpdateFlowEntitlementRequestRequestTypeDef,
+    AddBridgeSourceRequestTypeDef,
+    BridgeSourceTypeDef,
+    UpdateBridgeSourceRequestRequestTypeDef,
+    AddBridgeOutputsRequestRequestTypeDef,
     GrantFlowEntitlementsResponseTypeDef,
     UpdateFlowEntitlementResponseTypeDef,
     GrantFlowEntitlementsRequestRequestTypeDef,
+    AddBridgeOutputsResponseTypeDef,
+    UpdateBridgeOutputResponseTypeDef,
+    DescribeGatewayInstanceResponseTypeDef,
+    CreateGatewayResponseTypeDef,
+    DescribeGatewayResponseTypeDef,
     MediaStreamOutputConfigurationRequestTypeDef,
     MediaStreamSourceConfigurationRequestTypeDef,
     MediaStreamOutputConfigurationTypeDef,
     MediaStreamSourceConfigurationTypeDef,
+    UpdateBridgeRequestRequestTypeDef,
     UpdateFlowRequestRequestTypeDef,
     ListFlowsResponseTypeDef,
     AddMediaStreamRequestTypeDef,
     UpdateFlowMediaStreamRequestRequestTypeDef,
     MediaStreamTypeDef,
     DescribeOfferingResponseTypeDef,
     ListOfferingsResponseTypeDef,
     DescribeReservationResponseTypeDef,
     ListReservationsResponseTypeDef,
     PurchaseOfferingResponseTypeDef,
+    AddBridgeSourcesRequestRequestTypeDef,
+    CreateBridgeRequestRequestTypeDef,
+    AddBridgeSourcesResponseTypeDef,
+    BridgeTypeDef,
+    UpdateBridgeSourceResponseTypeDef,
     AddOutputRequestTypeDef,
     UpdateFlowOutputRequestRequestTypeDef,
     SetSourceRequestTypeDef,
     UpdateFlowSourceRequestRequestTypeDef,
     OutputTypeDef,
     SourceTypeDef,
     AddFlowMediaStreamsRequestRequestTypeDef,
     AddFlowMediaStreamsResponseTypeDef,
     UpdateFlowMediaStreamResponseTypeDef,
+    CreateBridgeResponseTypeDef,
+    DescribeBridgeResponseTypeDef,
+    UpdateBridgeResponseTypeDef,
     AddFlowOutputsRequestRequestTypeDef,
     AddFlowSourcesRequestRequestTypeDef,
     CreateFlowRequestRequestTypeDef,
     AddFlowOutputsResponseTypeDef,
     UpdateFlowOutputResponseTypeDef,
     AddFlowSourcesResponseTypeDef,
     FlowTypeDef,
     UpdateFlowSourceResponseTypeDef,
     CreateFlowResponseTypeDef,
     DescribeFlowResponseTypeDef,
     UpdateFlowResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> VpcInterfaceAttachmentTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-mediaconnect-2.5.0.post1/types_aiobotocore_mediaconnect.egg-info/SOURCES.txt` & `types-aiobotocore-mediaconnect-2.5.1/types_aiobotocore_mediaconnect.egg-info/SOURCES.txt`

 * *Files identical despite different names*

