# Comparing `tmp/types-aiobotocore-networkmanager-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-networkmanager-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-networkmanager-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-networkmanager-2.5.1.tar", last modified: Wed Jun 28 01:43:54 2023, max compression
```

## Comparing `types-aiobotocore-networkmanager-2.5.0.post1.tar` & `types-aiobotocore-networkmanager-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.583464 types-aiobotocore-networkmanager-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    28820 2023-03-11 12:27:03.583464 types-aiobotocore-networkmanager-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    27221 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.583464 types-aiobotocore-networkmanager-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.579464 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/
--rw-r--r--   0 runner    (1001) docker     (123)     5443 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5442 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    73474 2023-03-11 12:19:09.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    73359 2023-03-11 12:19:09.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14424 2023-03-11 12:19:09.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14422 2023-03-11 12:19:09.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    28644 2023-03-11 12:19:09.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    28620 2023-03-11 12:19:09.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    95684 2023-03-11 12:19:13.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    95567 2023-03-11 12:19:12.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:08.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.583464 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    28820 2023-03-11 12:27:03.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:03.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:03.000000 types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.402183 types-aiobotocore-networkmanager-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    28819 2023-06-28 01:43:54.402183 types-aiobotocore-networkmanager-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    27226 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:54.402183 types-aiobotocore-networkmanager-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.398183 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/
+-rw-r--r--   0 runner    (1001) docker     (123)     5443 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5442 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    73474 2023-06-28 01:35:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    73359 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14633 2023-06-28 01:35:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14631 2023-06-28 01:35:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    28579 2023-06-28 01:35:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28555 2023-06-28 01:35:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    95886 2023-06-28 01:35:57.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    95769 2023-06-28 01:35:55.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:53.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.402183 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    28819 2023-06-28 01:43:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:54.000000 types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/LICENSE` & `types-aiobotocore-networkmanager-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/PKG-INFO` & `types-aiobotocore-networkmanager-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-networkmanager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.NetworkManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.NetworkManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-networkmanager"></a>
 
 # types-aiobotocore-networkmanager
 
 [![PyPI - types-aiobotocore-networkmanager](https://img.shields.io/pypi/v/types-aiobotocore-networkmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-networkmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-networkmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-networkmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-networkmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-networkmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NetworkManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
+[aiobotocore.NetworkManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
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
 [types-aiobotocore-networkmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -437,15 +437,14 @@
 `types_aiobotocore_networkmanager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_networkmanager.type_defs import (
     AWSLocationTypeDef,
     AcceptAttachmentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AccountStatusTypeDef,
     AssociateConnectPeerRequestRequestTypeDef,
     ConnectPeerAssociationTypeDef,
     AssociateCustomerGatewayRequestRequestTypeDef,
     CustomerGatewayAssociationTypeDef,
     AssociateLinkRequestRequestTypeDef,
     LinkAssociationTypeDef,
@@ -474,73 +473,95 @@
     DeleteDeviceRequestRequestTypeDef,
     DeleteGlobalNetworkRequestRequestTypeDef,
     DeleteLinkRequestRequestTypeDef,
     DeletePeeringRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSiteRequestRequestTypeDef,
     DeregisterTransitGatewayRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef,
     DescribeGlobalNetworksRequestRequestTypeDef,
     DisassociateConnectPeerRequestRequestTypeDef,
     DisassociateCustomerGatewayRequestRequestTypeDef,
     DisassociateLinkRequestRequestTypeDef,
     DisassociateTransitGatewayConnectPeerRequestRequestTypeDef,
     ExecuteCoreNetworkChangeSetRequestRequestTypeDef,
     GetConnectAttachmentRequestRequestTypeDef,
+    GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
     GetConnectPeerAssociationsRequestRequestTypeDef,
     GetConnectPeerRequestRequestTypeDef,
+    GetConnectionsRequestGetConnectionsPaginateTypeDef,
     GetConnectionsRequestRequestTypeDef,
+    GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
     GetCoreNetworkChangeEventsRequestRequestTypeDef,
+    GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
     GetCoreNetworkChangeSetRequestRequestTypeDef,
     GetCoreNetworkPolicyRequestRequestTypeDef,
     GetCoreNetworkRequestRequestTypeDef,
+    GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
     GetCustomerGatewayAssociationsRequestRequestTypeDef,
+    GetDevicesRequestGetDevicesPaginateTypeDef,
     GetDevicesRequestRequestTypeDef,
+    GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
     GetLinkAssociationsRequestRequestTypeDef,
+    GetLinksRequestGetLinksPaginateTypeDef,
     GetLinksRequestRequestTypeDef,
+    GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
     GetNetworkResourceCountsRequestRequestTypeDef,
     NetworkResourceCountTypeDef,
+    GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
     GetNetworkResourceRelationshipsRequestRequestTypeDef,
     RelationshipTypeDef,
+    GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
     GetNetworkResourcesRequestRequestTypeDef,
+    GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
     GetNetworkTelemetryRequestRequestTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetRouteAnalysisRequestRequestTypeDef,
     GetSiteToSiteVpnAttachmentRequestRequestTypeDef,
+    GetSitesRequestGetSitesPaginateTypeDef,
     GetSitesRequestRequestTypeDef,
+    GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
     GetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef,
     GetTransitGatewayPeeringRequestRequestTypeDef,
+    GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
     GetTransitGatewayRegistrationsRequestRequestTypeDef,
     GetTransitGatewayRouteTableAttachmentRequestRequestTypeDef,
     GetVpcAttachmentRequestRequestTypeDef,
+    ListAttachmentsRequestListAttachmentsPaginateTypeDef,
     ListAttachmentsRequestRequestTypeDef,
+    ListConnectPeersRequestListConnectPeersPaginateTypeDef,
     ListConnectPeersRequestRequestTypeDef,
+    ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
     ListCoreNetworkPolicyVersionsRequestRequestTypeDef,
+    ListCoreNetworksRequestListCoreNetworksPaginateTypeDef,
     ListCoreNetworksRequestRequestTypeDef,
     ListOrganizationServiceAccessStatusRequestRequestTypeDef,
+    ListPeeringsRequestListPeeringsPaginateTypeDef,
     ListPeeringsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     NetworkResourceSummaryTypeDef,
     NetworkRouteDestinationTypeDef,
+    PaginatorConfigTypeDef,
     PutCoreNetworkPolicyRequestRequestTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
     RegisterTransitGatewayRequestRequestTypeDef,
     RejectAttachmentRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreCoreNetworkPolicyVersionRequestRequestTypeDef,
     RouteAnalysisCompletionTypeDef,
     RouteAnalysisEndpointOptionsSpecificationTypeDef,
     RouteAnalysisEndpointOptionsTypeDef,
     StartOrganizationServiceAccessUpdateRequestRequestTypeDef,
     TransitGatewayRegistrationStateReasonTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateConnectionRequestRequestTypeDef,
     UpdateCoreNetworkRequestRequestTypeDef,
     UpdateGlobalNetworkRequestRequestTypeDef,
     UpdateNetworkResourceMetadataRequestRequestTypeDef,
-    GetResourcePolicyResponseTypeDef,
     UpdateNetworkResourceMetadataResponseTypeDef,
     OrganizationStatusTypeDef,
     AssociateConnectPeerResponseTypeDef,
     DisassociateConnectPeerResponseTypeDef,
     GetConnectPeerAssociationsResponseTypeDef,
     AssociateCustomerGatewayResponseTypeDef,
     DisassociateCustomerGatewayResponseTypeDef,
@@ -583,35 +604,14 @@
     CreateSiteRequestRequestTypeDef,
     DeviceTypeDef,
     SiteTypeDef,
     UpdateDeviceRequestRequestTypeDef,
     UpdateSiteRequestRequestTypeDef,
     CreateVpcAttachmentRequestRequestTypeDef,
     UpdateVpcAttachmentRequestRequestTypeDef,
-    DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef,
-    GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-    GetConnectionsRequestGetConnectionsPaginateTypeDef,
-    GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-    GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-    GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-    GetDevicesRequestGetDevicesPaginateTypeDef,
-    GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-    GetLinksRequestGetLinksPaginateTypeDef,
-    GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-    GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-    GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-    GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-    GetSitesRequestGetSitesPaginateTypeDef,
-    GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-    GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-    ListAttachmentsRequestListAttachmentsPaginateTypeDef,
-    ListConnectPeersRequestListConnectPeersPaginateTypeDef,
-    ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-    ListCoreNetworksRequestListCoreNetworksPaginateTypeDef,
-    ListPeeringsRequestListPeeringsPaginateTypeDef,
     GetNetworkResourceCountsResponseTypeDef,
     GetNetworkResourceRelationshipsResponseTypeDef,
     PathComponentTypeDef,
     NetworkRouteTypeDef,
     StartRouteAnalysisRequestRequestTypeDef,
     TransitGatewayRegistrationTypeDef,
     ListOrganizationServiceAccessStatusResponseTypeDef,
@@ -696,43 +696,43 @@
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/README.md` & `types-aiobotocore-networkmanager-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-networkmanager"></a>
 
 # types-aiobotocore-networkmanager
 
 [![PyPI - types-aiobotocore-networkmanager](https://img.shields.io/pypi/v/types-aiobotocore-networkmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-networkmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-networkmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-networkmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-networkmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-networkmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NetworkManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
+[aiobotocore.NetworkManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
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
 [types-aiobotocore-networkmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -404,15 +404,14 @@
 `types_aiobotocore_networkmanager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_networkmanager.type_defs import (
     AWSLocationTypeDef,
     AcceptAttachmentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AccountStatusTypeDef,
     AssociateConnectPeerRequestRequestTypeDef,
     ConnectPeerAssociationTypeDef,
     AssociateCustomerGatewayRequestRequestTypeDef,
     CustomerGatewayAssociationTypeDef,
     AssociateLinkRequestRequestTypeDef,
     LinkAssociationTypeDef,
@@ -441,73 +440,95 @@
     DeleteDeviceRequestRequestTypeDef,
     DeleteGlobalNetworkRequestRequestTypeDef,
     DeleteLinkRequestRequestTypeDef,
     DeletePeeringRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSiteRequestRequestTypeDef,
     DeregisterTransitGatewayRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef,
     DescribeGlobalNetworksRequestRequestTypeDef,
     DisassociateConnectPeerRequestRequestTypeDef,
     DisassociateCustomerGatewayRequestRequestTypeDef,
     DisassociateLinkRequestRequestTypeDef,
     DisassociateTransitGatewayConnectPeerRequestRequestTypeDef,
     ExecuteCoreNetworkChangeSetRequestRequestTypeDef,
     GetConnectAttachmentRequestRequestTypeDef,
+    GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
     GetConnectPeerAssociationsRequestRequestTypeDef,
     GetConnectPeerRequestRequestTypeDef,
+    GetConnectionsRequestGetConnectionsPaginateTypeDef,
     GetConnectionsRequestRequestTypeDef,
+    GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
     GetCoreNetworkChangeEventsRequestRequestTypeDef,
+    GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
     GetCoreNetworkChangeSetRequestRequestTypeDef,
     GetCoreNetworkPolicyRequestRequestTypeDef,
     GetCoreNetworkRequestRequestTypeDef,
+    GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
     GetCustomerGatewayAssociationsRequestRequestTypeDef,
+    GetDevicesRequestGetDevicesPaginateTypeDef,
     GetDevicesRequestRequestTypeDef,
+    GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
     GetLinkAssociationsRequestRequestTypeDef,
+    GetLinksRequestGetLinksPaginateTypeDef,
     GetLinksRequestRequestTypeDef,
+    GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
     GetNetworkResourceCountsRequestRequestTypeDef,
     NetworkResourceCountTypeDef,
+    GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
     GetNetworkResourceRelationshipsRequestRequestTypeDef,
     RelationshipTypeDef,
+    GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
     GetNetworkResourcesRequestRequestTypeDef,
+    GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
     GetNetworkTelemetryRequestRequestTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetRouteAnalysisRequestRequestTypeDef,
     GetSiteToSiteVpnAttachmentRequestRequestTypeDef,
+    GetSitesRequestGetSitesPaginateTypeDef,
     GetSitesRequestRequestTypeDef,
+    GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
     GetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef,
     GetTransitGatewayPeeringRequestRequestTypeDef,
+    GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
     GetTransitGatewayRegistrationsRequestRequestTypeDef,
     GetTransitGatewayRouteTableAttachmentRequestRequestTypeDef,
     GetVpcAttachmentRequestRequestTypeDef,
+    ListAttachmentsRequestListAttachmentsPaginateTypeDef,
     ListAttachmentsRequestRequestTypeDef,
+    ListConnectPeersRequestListConnectPeersPaginateTypeDef,
     ListConnectPeersRequestRequestTypeDef,
+    ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
     ListCoreNetworkPolicyVersionsRequestRequestTypeDef,
+    ListCoreNetworksRequestListCoreNetworksPaginateTypeDef,
     ListCoreNetworksRequestRequestTypeDef,
     ListOrganizationServiceAccessStatusRequestRequestTypeDef,
+    ListPeeringsRequestListPeeringsPaginateTypeDef,
     ListPeeringsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     NetworkResourceSummaryTypeDef,
     NetworkRouteDestinationTypeDef,
+    PaginatorConfigTypeDef,
     PutCoreNetworkPolicyRequestRequestTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
     RegisterTransitGatewayRequestRequestTypeDef,
     RejectAttachmentRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreCoreNetworkPolicyVersionRequestRequestTypeDef,
     RouteAnalysisCompletionTypeDef,
     RouteAnalysisEndpointOptionsSpecificationTypeDef,
     RouteAnalysisEndpointOptionsTypeDef,
     StartOrganizationServiceAccessUpdateRequestRequestTypeDef,
     TransitGatewayRegistrationStateReasonTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateConnectionRequestRequestTypeDef,
     UpdateCoreNetworkRequestRequestTypeDef,
     UpdateGlobalNetworkRequestRequestTypeDef,
     UpdateNetworkResourceMetadataRequestRequestTypeDef,
-    GetResourcePolicyResponseTypeDef,
     UpdateNetworkResourceMetadataResponseTypeDef,
     OrganizationStatusTypeDef,
     AssociateConnectPeerResponseTypeDef,
     DisassociateConnectPeerResponseTypeDef,
     GetConnectPeerAssociationsResponseTypeDef,
     AssociateCustomerGatewayResponseTypeDef,
     DisassociateCustomerGatewayResponseTypeDef,
@@ -550,35 +571,14 @@
     CreateSiteRequestRequestTypeDef,
     DeviceTypeDef,
     SiteTypeDef,
     UpdateDeviceRequestRequestTypeDef,
     UpdateSiteRequestRequestTypeDef,
     CreateVpcAttachmentRequestRequestTypeDef,
     UpdateVpcAttachmentRequestRequestTypeDef,
-    DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef,
-    GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-    GetConnectionsRequestGetConnectionsPaginateTypeDef,
-    GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-    GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-    GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-    GetDevicesRequestGetDevicesPaginateTypeDef,
-    GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-    GetLinksRequestGetLinksPaginateTypeDef,
-    GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-    GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-    GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-    GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-    GetSitesRequestGetSitesPaginateTypeDef,
-    GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-    GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-    ListAttachmentsRequestListAttachmentsPaginateTypeDef,
-    ListConnectPeersRequestListConnectPeersPaginateTypeDef,
-    ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-    ListCoreNetworksRequestListCoreNetworksPaginateTypeDef,
-    ListPeeringsRequestListPeeringsPaginateTypeDef,
     GetNetworkResourceCountsResponseTypeDef,
     GetNetworkResourceRelationshipsResponseTypeDef,
     PathComponentTypeDef,
     NetworkRouteTypeDef,
     StartRouteAnalysisRequestRequestTypeDef,
     TransitGatewayRegistrationTypeDef,
     ListOrganizationServiceAccessStatusResponseTypeDef,
@@ -663,43 +663,43 @@
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/setup.py` & `types-aiobotocore-networkmanager-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-networkmanager.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-networkmanager",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_networkmanager"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.NetworkManager 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.NetworkManager 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/"
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/__init__.py` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/__init__.pyi` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/__main__.py` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.NetworkManager 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.NetworkManager 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager\nOther"
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/client.py` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/client.pyi` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/literals.py` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -233,14 +233,15 @@
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
@@ -319,14 +320,15 @@
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
@@ -337,14 +339,15 @@
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
@@ -380,14 +383,15 @@
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
@@ -406,16 +410,19 @@
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
@@ -499,15 +506,17 @@
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/literals.pyi` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -231,14 +231,15 @@
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
@@ -317,14 +318,15 @@
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
@@ -335,14 +337,15 @@
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
@@ -378,14 +381,15 @@
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
@@ -404,16 +408,19 @@
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
@@ -497,15 +504,17 @@
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/paginator.py` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -57,15 +57,15 @@
         list_connect_peers_paginator: ListConnectPeersPaginator = client.get_paginator("list_connect_peers")
         list_core_network_policy_versions_paginator: ListCoreNetworkPolicyVersionsPaginator = client.get_paginator("list_core_network_policy_versions")
         list_core_networks_paginator: ListCoreNetworksPaginator = client.get_paginator("list_core_networks")
         list_peerings_paginator: ListPeeringsPaginator = client.get_paginator("list_peerings")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AttachmentStateType, AttachmentTypeType, PeeringStateType
 from .type_defs import (
     DescribeGlobalNetworksResponseTypeDef,
@@ -88,24 +88,19 @@
     ListConnectPeersResponseTypeDef,
     ListCoreNetworkPolicyVersionsResponseTypeDef,
     ListCoreNetworksResponseTypeDef,
     ListPeeringsResponseTypeDef,
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
 
-
 __all__ = (
     "DescribeGlobalNetworksPaginator",
     "GetConnectPeerAssociationsPaginator",
     "GetConnectionsPaginator",
     "GetCoreNetworkChangeEventsPaginator",
     "GetCoreNetworkChangeSetPaginator",
     "GetCustomerGatewayAssociationsPaginator",
@@ -122,220 +117,207 @@
     "ListAttachmentsPaginator",
     "ListConnectPeersPaginator",
     "ListCoreNetworkPolicyVersionsPaginator",
     "ListCoreNetworksPaginator",
     "ListPeeringsPaginator",
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
 class DescribeGlobalNetworksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.DescribeGlobalNetworks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#describeglobalnetworkspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGlobalNetworksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.DescribeGlobalNetworks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#describeglobalnetworkspaginator)
         """
 
-
 class GetConnectPeerAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnectPeerAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectpeerassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         ConnectPeerIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectPeerAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnectPeerAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectpeerassociationspaginator)
         """
 
-
 class GetConnectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectionspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         ConnectionIds: Sequence[str] = ...,
         DeviceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectionspaginator)
         """
 
-
 class GetCoreNetworkChangeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str,
         PolicyVersionId: int,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCoreNetworkChangeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangeeventspaginator)
         """
 
-
 class GetCoreNetworkChangeSetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeSet)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangesetpaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str,
         PolicyVersionId: int,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCoreNetworkChangeSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangesetpaginator)
         """
 
-
 class GetCustomerGatewayAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCustomerGatewayAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcustomergatewayassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         CustomerGatewayArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCustomerGatewayAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCustomerGatewayAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcustomergatewayassociationspaginator)
         """
 
-
 class GetDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getdevicespaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         DeviceIds: Sequence[str] = ...,
         SiteId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getdevicespaginator)
         """
 
-
 class GetLinkAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinkAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         DeviceId: str = ...,
         LinkId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLinkAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinkAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkassociationspaginator)
         """
 
-
 class GetLinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         LinkIds: Sequence[str] = ...,
         SiteId: str = ...,
         Type: str = ...,
         Provider: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLinksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkspaginator)
         """
 
-
 class GetNetworkResourceCountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceCounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcecountspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         ResourceType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkResourceCountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceCounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcecountspaginator)
         """
 
-
 class GetNetworkResourceRelationshipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceRelationships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcerelationshipspaginator)
     """
 
     def paginate(
@@ -344,22 +326,21 @@
         GlobalNetworkId: str,
         CoreNetworkId: str = ...,
         RegisteredGatewayArn: str = ...,
         AwsRegion: str = ...,
         AccountId: str = ...,
         ResourceType: str = ...,
         ResourceArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkResourceRelationshipsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceRelationships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcerelationshipspaginator)
         """
 
-
 class GetNetworkResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcespaginator)
     """
 
     def paginate(
@@ -368,22 +349,21 @@
         GlobalNetworkId: str,
         CoreNetworkId: str = ...,
         RegisteredGatewayArn: str = ...,
         AwsRegion: str = ...,
         AccountId: str = ...,
         ResourceType: str = ...,
         ResourceArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcespaginator)
         """
 
-
 class GetNetworkTelemetryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkTelemetry)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworktelemetrypaginator)
     """
 
     def paginate(
@@ -392,161 +372,153 @@
         GlobalNetworkId: str,
         CoreNetworkId: str = ...,
         RegisteredGatewayArn: str = ...,
         AwsRegion: str = ...,
         AccountId: str = ...,
         ResourceType: str = ...,
         ResourceArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkTelemetryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkTelemetry.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworktelemetrypaginator)
         """
 
-
 class GetSitesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetSites)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getsitespaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         SiteIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSitesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetSites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getsitespaginator)
         """
 
-
 class GetTransitGatewayConnectPeerAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayConnectPeerAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayconnectpeerassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         TransitGatewayConnectPeerArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTransitGatewayConnectPeerAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayConnectPeerAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayconnectpeerassociationspaginator)
         """
 
-
 class GetTransitGatewayRegistrationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayRegistrations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayregistrationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         TransitGatewayArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTransitGatewayRegistrationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayRegistrations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayregistrationspaginator)
         """
 
-
 class ListAttachmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListAttachments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listattachmentspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str = ...,
         AttachmentType: AttachmentTypeType = ...,
         EdgeLocation: str = ...,
         State: AttachmentStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListAttachments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listattachmentspaginator)
         """
 
-
 class ListConnectPeersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListConnectPeers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listconnectpeerspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str = ...,
         ConnectAttachmentId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConnectPeersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListConnectPeers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listconnectpeerspaginator)
         """
 
-
 class ListCoreNetworkPolicyVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworkPolicyVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkpolicyversionspaginator)
     """
 
     def paginate(
-        self, *, CoreNetworkId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CoreNetworkId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCoreNetworkPolicyVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworkPolicyVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkpolicyversionspaginator)
         """
 
-
 class ListCoreNetworksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCoreNetworksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkspaginator)
         """
 
-
 class ListPeeringsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListPeerings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listpeeringspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str = ...,
         PeeringType: Literal["TRANSIT_GATEWAY"] = ...,
         EdgeLocation: str = ...,
         State: PeeringStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPeeringsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListPeerings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listpeeringspaginator)
         """
```

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/paginator.pyi` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -57,15 +57,15 @@
         list_connect_peers_paginator: ListConnectPeersPaginator = client.get_paginator("list_connect_peers")
         list_core_network_policy_versions_paginator: ListCoreNetworkPolicyVersionsPaginator = client.get_paginator("list_core_network_policy_versions")
         list_core_networks_paginator: ListCoreNetworksPaginator = client.get_paginator("list_core_networks")
         list_peerings_paginator: ListPeeringsPaginator = client.get_paginator("list_peerings")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AttachmentStateType, AttachmentTypeType, PeeringStateType
 from .type_defs import (
     DescribeGlobalNetworksResponseTypeDef,
@@ -88,23 +88,20 @@
     ListConnectPeersResponseTypeDef,
     ListCoreNetworkPolicyVersionsResponseTypeDef,
     ListCoreNetworksResponseTypeDef,
     ListPeeringsResponseTypeDef,
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
 
+
 __all__ = (
     "DescribeGlobalNetworksPaginator",
     "GetConnectPeerAssociationsPaginator",
     "GetConnectionsPaginator",
     "GetCoreNetworkChangeEventsPaginator",
     "GetCoreNetworkChangeSetPaginator",
     "GetCustomerGatewayAssociationsPaginator",
@@ -121,207 +118,220 @@
     "ListAttachmentsPaginator",
     "ListConnectPeersPaginator",
     "ListCoreNetworkPolicyVersionsPaginator",
     "ListCoreNetworksPaginator",
     "ListPeeringsPaginator",
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
 class DescribeGlobalNetworksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.DescribeGlobalNetworks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#describeglobalnetworkspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGlobalNetworksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.DescribeGlobalNetworks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#describeglobalnetworkspaginator)
         """
 
+
 class GetConnectPeerAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnectPeerAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectpeerassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         ConnectPeerIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectPeerAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnectPeerAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectpeerassociationspaginator)
         """
 
+
 class GetConnectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectionspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         ConnectionIds: Sequence[str] = ...,
         DeviceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getconnectionspaginator)
         """
 
+
 class GetCoreNetworkChangeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str,
         PolicyVersionId: int,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCoreNetworkChangeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangeeventspaginator)
         """
 
+
 class GetCoreNetworkChangeSetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeSet)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangesetpaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str,
         PolicyVersionId: int,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCoreNetworkChangeSetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCoreNetworkChangeSet.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcorenetworkchangesetpaginator)
         """
 
+
 class GetCustomerGatewayAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCustomerGatewayAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcustomergatewayassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         CustomerGatewayArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCustomerGatewayAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetCustomerGatewayAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getcustomergatewayassociationspaginator)
         """
 
+
 class GetDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getdevicespaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         DeviceIds: Sequence[str] = ...,
         SiteId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getdevicespaginator)
         """
 
+
 class GetLinkAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinkAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         DeviceId: str = ...,
         LinkId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLinkAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinkAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkassociationspaginator)
         """
 
+
 class GetLinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         LinkIds: Sequence[str] = ...,
         SiteId: str = ...,
         Type: str = ...,
         Provider: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLinksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getlinkspaginator)
         """
 
+
 class GetNetworkResourceCountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceCounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcecountspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         ResourceType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkResourceCountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceCounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcecountspaginator)
         """
 
+
 class GetNetworkResourceRelationshipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceRelationships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcerelationshipspaginator)
     """
 
     def paginate(
@@ -330,21 +340,22 @@
         GlobalNetworkId: str,
         CoreNetworkId: str = ...,
         RegisteredGatewayArn: str = ...,
         AwsRegion: str = ...,
         AccountId: str = ...,
         ResourceType: str = ...,
         ResourceArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkResourceRelationshipsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResourceRelationships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcerelationshipspaginator)
         """
 
+
 class GetNetworkResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcespaginator)
     """
 
     def paginate(
@@ -353,21 +364,22 @@
         GlobalNetworkId: str,
         CoreNetworkId: str = ...,
         RegisteredGatewayArn: str = ...,
         AwsRegion: str = ...,
         AccountId: str = ...,
         ResourceType: str = ...,
         ResourceArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworkresourcespaginator)
         """
 
+
 class GetNetworkTelemetryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkTelemetry)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworktelemetrypaginator)
     """
 
     def paginate(
@@ -376,153 +388,161 @@
         GlobalNetworkId: str,
         CoreNetworkId: str = ...,
         RegisteredGatewayArn: str = ...,
         AwsRegion: str = ...,
         AccountId: str = ...,
         ResourceType: str = ...,
         ResourceArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetNetworkTelemetryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetNetworkTelemetry.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getnetworktelemetrypaginator)
         """
 
+
 class GetSitesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetSites)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getsitespaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         SiteIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSitesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetSites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#getsitespaginator)
         """
 
+
 class GetTransitGatewayConnectPeerAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayConnectPeerAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayconnectpeerassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         TransitGatewayConnectPeerArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTransitGatewayConnectPeerAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayConnectPeerAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayconnectpeerassociationspaginator)
         """
 
+
 class GetTransitGatewayRegistrationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayRegistrations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayregistrationspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalNetworkId: str,
         TransitGatewayArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTransitGatewayRegistrationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.GetTransitGatewayRegistrations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#gettransitgatewayregistrationspaginator)
         """
 
+
 class ListAttachmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListAttachments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listattachmentspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str = ...,
         AttachmentType: AttachmentTypeType = ...,
         EdgeLocation: str = ...,
         State: AttachmentStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListAttachments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listattachmentspaginator)
         """
 
+
 class ListConnectPeersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListConnectPeers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listconnectpeerspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str = ...,
         ConnectAttachmentId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConnectPeersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListConnectPeers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listconnectpeerspaginator)
         """
 
+
 class ListCoreNetworkPolicyVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworkPolicyVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkpolicyversionspaginator)
     """
 
     def paginate(
-        self, *, CoreNetworkId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CoreNetworkId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCoreNetworkPolicyVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworkPolicyVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkpolicyversionspaginator)
         """
 
+
 class ListCoreNetworksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCoreNetworksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListCoreNetworks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listcorenetworkspaginator)
         """
 
+
 class ListPeeringsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListPeerings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listpeeringspaginator)
     """
 
     def paginate(
         self,
         *,
         CoreNetworkId: str = ...,
         PeeringType: Literal["TRANSIT_GATEWAY"] = ...,
         EdgeLocation: str = ...,
         State: PeeringStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPeeringsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager.Paginator.ListPeerings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/paginators/#listpeeringspaginator)
         """
```

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/type_defs.py` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -55,15 +55,14 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AWSLocationTypeDef",
     "AcceptAttachmentRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AccountStatusTypeDef",
     "AssociateConnectPeerRequestRequestTypeDef",
     "ConnectPeerAssociationTypeDef",
     "AssociateCustomerGatewayRequestRequestTypeDef",
     "CustomerGatewayAssociationTypeDef",
     "AssociateLinkRequestRequestTypeDef",
     "LinkAssociationTypeDef",
@@ -92,73 +91,95 @@
     "DeleteDeviceRequestRequestTypeDef",
     "DeleteGlobalNetworkRequestRequestTypeDef",
     "DeleteLinkRequestRequestTypeDef",
     "DeletePeeringRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSiteRequestRequestTypeDef",
     "DeregisterTransitGatewayRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
     "DescribeGlobalNetworksRequestRequestTypeDef",
     "DisassociateConnectPeerRequestRequestTypeDef",
     "DisassociateCustomerGatewayRequestRequestTypeDef",
     "DisassociateLinkRequestRequestTypeDef",
     "DisassociateTransitGatewayConnectPeerRequestRequestTypeDef",
     "ExecuteCoreNetworkChangeSetRequestRequestTypeDef",
     "GetConnectAttachmentRequestRequestTypeDef",
+    "GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
     "GetConnectPeerAssociationsRequestRequestTypeDef",
     "GetConnectPeerRequestRequestTypeDef",
+    "GetConnectionsRequestGetConnectionsPaginateTypeDef",
     "GetConnectionsRequestRequestTypeDef",
+    "GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
     "GetCoreNetworkChangeEventsRequestRequestTypeDef",
+    "GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
     "GetCoreNetworkChangeSetRequestRequestTypeDef",
     "GetCoreNetworkPolicyRequestRequestTypeDef",
     "GetCoreNetworkRequestRequestTypeDef",
+    "GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
     "GetCustomerGatewayAssociationsRequestRequestTypeDef",
+    "GetDevicesRequestGetDevicesPaginateTypeDef",
     "GetDevicesRequestRequestTypeDef",
+    "GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
     "GetLinkAssociationsRequestRequestTypeDef",
+    "GetLinksRequestGetLinksPaginateTypeDef",
     "GetLinksRequestRequestTypeDef",
+    "GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
     "GetNetworkResourceCountsRequestRequestTypeDef",
     "NetworkResourceCountTypeDef",
+    "GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
     "GetNetworkResourceRelationshipsRequestRequestTypeDef",
     "RelationshipTypeDef",
+    "GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
     "GetNetworkResourcesRequestRequestTypeDef",
+    "GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
     "GetNetworkTelemetryRequestRequestTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "GetRouteAnalysisRequestRequestTypeDef",
     "GetSiteToSiteVpnAttachmentRequestRequestTypeDef",
+    "GetSitesRequestGetSitesPaginateTypeDef",
     "GetSitesRequestRequestTypeDef",
+    "GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
     "GetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef",
     "GetTransitGatewayPeeringRequestRequestTypeDef",
+    "GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
     "GetTransitGatewayRegistrationsRequestRequestTypeDef",
     "GetTransitGatewayRouteTableAttachmentRequestRequestTypeDef",
     "GetVpcAttachmentRequestRequestTypeDef",
+    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
     "ListAttachmentsRequestRequestTypeDef",
+    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
     "ListConnectPeersRequestRequestTypeDef",
+    "ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
     "ListCoreNetworkPolicyVersionsRequestRequestTypeDef",
+    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
     "ListCoreNetworksRequestRequestTypeDef",
     "ListOrganizationServiceAccessStatusRequestRequestTypeDef",
+    "ListPeeringsRequestListPeeringsPaginateTypeDef",
     "ListPeeringsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "NetworkResourceSummaryTypeDef",
     "NetworkRouteDestinationTypeDef",
+    "PaginatorConfigTypeDef",
     "PutCoreNetworkPolicyRequestRequestTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
     "RegisterTransitGatewayRequestRequestTypeDef",
     "RejectAttachmentRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreCoreNetworkPolicyVersionRequestRequestTypeDef",
     "RouteAnalysisCompletionTypeDef",
     "RouteAnalysisEndpointOptionsSpecificationTypeDef",
     "RouteAnalysisEndpointOptionsTypeDef",
     "StartOrganizationServiceAccessUpdateRequestRequestTypeDef",
     "TransitGatewayRegistrationStateReasonTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateConnectionRequestRequestTypeDef",
     "UpdateCoreNetworkRequestRequestTypeDef",
     "UpdateGlobalNetworkRequestRequestTypeDef",
     "UpdateNetworkResourceMetadataRequestRequestTypeDef",
-    "GetResourcePolicyResponseTypeDef",
     "UpdateNetworkResourceMetadataResponseTypeDef",
     "OrganizationStatusTypeDef",
     "AssociateConnectPeerResponseTypeDef",
     "DisassociateConnectPeerResponseTypeDef",
     "GetConnectPeerAssociationsResponseTypeDef",
     "AssociateCustomerGatewayResponseTypeDef",
     "DisassociateCustomerGatewayResponseTypeDef",
@@ -201,35 +222,14 @@
     "CreateSiteRequestRequestTypeDef",
     "DeviceTypeDef",
     "SiteTypeDef",
     "UpdateDeviceRequestRequestTypeDef",
     "UpdateSiteRequestRequestTypeDef",
     "CreateVpcAttachmentRequestRequestTypeDef",
     "UpdateVpcAttachmentRequestRequestTypeDef",
-    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
-    "GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
-    "GetConnectionsRequestGetConnectionsPaginateTypeDef",
-    "GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
-    "GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
-    "GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
-    "GetDevicesRequestGetDevicesPaginateTypeDef",
-    "GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
-    "GetLinksRequestGetLinksPaginateTypeDef",
-    "GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
-    "GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
-    "GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
-    "GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
-    "GetSitesRequestGetSitesPaginateTypeDef",
-    "GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
-    "GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
-    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
-    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
-    "ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
-    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
-    "ListPeeringsRequestListPeeringsPaginateTypeDef",
     "GetNetworkResourceCountsResponseTypeDef",
     "GetNetworkResourceRelationshipsResponseTypeDef",
     "PathComponentTypeDef",
     "NetworkRouteTypeDef",
     "StartRouteAnalysisRequestRequestTypeDef",
     "TransitGatewayRegistrationTypeDef",
     "ListOrganizationServiceAccessStatusResponseTypeDef",
@@ -318,25 +318,14 @@
 AcceptAttachmentRequestRequestTypeDef = TypedDict(
     "AcceptAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
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
 AccountStatusTypeDef = TypedDict(
     "AccountStatusTypeDef",
     {
         "AccountId": str,
         "SLRDeploymentStatus": str,
     },
     total=False,
@@ -720,20 +709,19 @@
     "DeregisterTransitGatewayRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
         "TransitGatewayArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef = TypedDict(
+    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "GlobalNetworkIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeGlobalNetworksRequestRequestTypeDef = TypedDict(
     "DescribeGlobalNetworksRequestRequestTypeDef",
     {
@@ -788,14 +776,37 @@
 GetConnectAttachmentRequestRequestTypeDef = TypedDict(
     "GetConnectAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
     },
 )
 
+_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
+    {
+        "ConnectPeerIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef(
+    _RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
+    _OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetConnectPeerAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
@@ -819,14 +830,38 @@
 GetConnectPeerRequestRequestTypeDef = TypedDict(
     "GetConnectPeerRequestRequestTypeDef",
     {
         "ConnectPeerId": str,
     },
 )
 
+_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
+    "_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
+    "_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef",
+    {
+        "ConnectionIds": Sequence[str],
+        "DeviceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetConnectionsRequestGetConnectionsPaginateTypeDef(
+    _RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef,
+    _OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetConnectionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetConnectionsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetConnectionsRequestRequestTypeDef = TypedDict(
@@ -843,14 +878,37 @@
 
 class GetConnectionsRequestRequestTypeDef(
     _RequiredGetConnectionsRequestRequestTypeDef, _OptionalGetConnectionsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
+    "_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "PolicyVersionId": int,
+    },
+)
+_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
+    "_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef(
+    _RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
+    _OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetCoreNetworkChangeEventsRequestRequestTypeDef = TypedDict(
     "_RequiredGetCoreNetworkChangeEventsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyVersionId": int,
     },
 )
@@ -867,14 +925,37 @@
 class GetCoreNetworkChangeEventsRequestRequestTypeDef(
     _RequiredGetCoreNetworkChangeEventsRequestRequestTypeDef,
     _OptionalGetCoreNetworkChangeEventsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
+    "_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "PolicyVersionId": int,
+    },
+)
+_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
+    "_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef(
+    _RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
+    _OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetCoreNetworkChangeSetRequestRequestTypeDef = TypedDict(
     "_RequiredGetCoreNetworkChangeSetRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyVersionId": int,
     },
 )
@@ -921,14 +1002,37 @@
 GetCoreNetworkRequestRequestTypeDef = TypedDict(
     "GetCoreNetworkRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
     },
 )
 
+_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
+    {
+        "CustomerGatewayArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef(
+    _RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
+    _OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetCustomerGatewayAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetCustomerGatewayAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetCustomerGatewayAssociationsRequestRequestTypeDef = TypedDict(
@@ -945,14 +1049,38 @@
 class GetCustomerGatewayAssociationsRequestRequestTypeDef(
     _RequiredGetCustomerGatewayAssociationsRequestRequestTypeDef,
     _OptionalGetCustomerGatewayAssociationsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
+    "_RequiredGetDevicesRequestGetDevicesPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
+    "_OptionalGetDevicesRequestGetDevicesPaginateTypeDef",
+    {
+        "DeviceIds": Sequence[str],
+        "SiteId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetDevicesRequestGetDevicesPaginateTypeDef(
+    _RequiredGetDevicesRequestGetDevicesPaginateTypeDef,
+    _OptionalGetDevicesRequestGetDevicesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetDevicesRequestRequestTypeDef = TypedDict(
     "_RequiredGetDevicesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetDevicesRequestRequestTypeDef = TypedDict(
@@ -969,14 +1097,38 @@
 
 class GetDevicesRequestRequestTypeDef(
     _RequiredGetDevicesRequestRequestTypeDef, _OptionalGetDevicesRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
+    {
+        "DeviceId": str,
+        "LinkId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef(
+    _RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
+    _OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetLinkAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetLinkAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetLinkAssociationsRequestRequestTypeDef = TypedDict(
@@ -994,14 +1146,39 @@
 class GetLinkAssociationsRequestRequestTypeDef(
     _RequiredGetLinkAssociationsRequestRequestTypeDef,
     _OptionalGetLinkAssociationsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
+    "_RequiredGetLinksRequestGetLinksPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
+    "_OptionalGetLinksRequestGetLinksPaginateTypeDef",
+    {
+        "LinkIds": Sequence[str],
+        "SiteId": str,
+        "Type": str,
+        "Provider": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetLinksRequestGetLinksPaginateTypeDef(
+    _RequiredGetLinksRequestGetLinksPaginateTypeDef, _OptionalGetLinksRequestGetLinksPaginateTypeDef
+):
+    pass
+
+
 _RequiredGetLinksRequestRequestTypeDef = TypedDict(
     "_RequiredGetLinksRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetLinksRequestRequestTypeDef = TypedDict(
@@ -1020,14 +1197,37 @@
 
 class GetLinksRequestRequestTypeDef(
     _RequiredGetLinksRequestRequestTypeDef, _OptionalGetLinksRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
+    {
+        "ResourceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef(
+    _RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
+    _OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetNetworkResourceCountsRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkResourceCountsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkResourceCountsRequestRequestTypeDef = TypedDict(
@@ -1053,14 +1253,42 @@
     {
         "ResourceType": str,
         "Count": int,
     },
     total=False,
 )
 
+_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "RegisteredGatewayArn": str,
+        "AwsRegion": str,
+        "AccountId": str,
+        "ResourceType": str,
+        "ResourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef(
+    _RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
+    _OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetNetworkResourceRelationshipsRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkResourceRelationshipsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkResourceRelationshipsRequestRequestTypeDef = TypedDict(
@@ -1091,14 +1319,42 @@
     {
         "From": str,
         "To": str,
     },
     total=False,
 )
 
+_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "RegisteredGatewayArn": str,
+        "AwsRegion": str,
+        "AccountId": str,
+        "ResourceType": str,
+        "ResourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef(
+    _RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
+    _OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetNetworkResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkResourcesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkResourcesRequestRequestTypeDef = TypedDict(
@@ -1120,14 +1376,42 @@
 class GetNetworkResourcesRequestRequestTypeDef(
     _RequiredGetNetworkResourcesRequestRequestTypeDef,
     _OptionalGetNetworkResourcesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "RegisteredGatewayArn": str,
+        "AwsRegion": str,
+        "AccountId": str,
+        "ResourceType": str,
+        "ResourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef(
+    _RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
+    _OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetNetworkTelemetryRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkTelemetryRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkTelemetryRequestRequestTypeDef = TypedDict(
@@ -1156,14 +1440,22 @@
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRouteAnalysisRequestRequestTypeDef = TypedDict(
     "GetRouteAnalysisRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
         "RouteAnalysisId": str,
     },
 )
@@ -1171,14 +1463,36 @@
 GetSiteToSiteVpnAttachmentRequestRequestTypeDef = TypedDict(
     "GetSiteToSiteVpnAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
     },
 )
 
+_RequiredGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
+    "_RequiredGetSitesRequestGetSitesPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
+    "_OptionalGetSitesRequestGetSitesPaginateTypeDef",
+    {
+        "SiteIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetSitesRequestGetSitesPaginateTypeDef(
+    _RequiredGetSitesRequestGetSitesPaginateTypeDef, _OptionalGetSitesRequestGetSitesPaginateTypeDef
+):
+    pass
+
+
 _RequiredGetSitesRequestRequestTypeDef = TypedDict(
     "_RequiredGetSitesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetSitesRequestRequestTypeDef = TypedDict(
@@ -1194,14 +1508,37 @@
 
 class GetSitesRequestRequestTypeDef(
     _RequiredGetSitesRequestRequestTypeDef, _OptionalGetSitesRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
+    {
+        "TransitGatewayConnectPeerArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef(
+    _RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
+    _OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
@@ -1225,14 +1562,37 @@
 GetTransitGatewayPeeringRequestRequestTypeDef = TypedDict(
     "GetTransitGatewayPeeringRequestRequestTypeDef",
     {
         "PeeringId": str,
     },
 )
 
+_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
+    "_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
+    "_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
+    {
+        "TransitGatewayArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef(
+    _RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
+    _OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTransitGatewayRegistrationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTransitGatewayRegistrationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetTransitGatewayRegistrationsRequestRequestTypeDef = TypedDict(
@@ -1263,38 +1623,86 @@
 GetVpcAttachmentRequestRequestTypeDef = TypedDict(
     "GetVpcAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
     },
 )
 
+ListAttachmentsRequestListAttachmentsPaginateTypeDef = TypedDict(
+    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "AttachmentType": AttachmentTypeType,
+        "EdgeLocation": str,
+        "State": AttachmentStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAttachmentsRequestRequestTypeDef = TypedDict(
     "ListAttachmentsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "AttachmentType": AttachmentTypeType,
         "EdgeLocation": str,
         "State": AttachmentStateType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListConnectPeersRequestListConnectPeersPaginateTypeDef = TypedDict(
+    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "ConnectAttachmentId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConnectPeersRequestRequestTypeDef = TypedDict(
     "ListConnectPeersRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "ConnectAttachmentId": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
+        {
+            "CoreNetworkId": str,
+        },
+    )
+)
+_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef(
+    _RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
+    _OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCoreNetworkPolicyVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListCoreNetworkPolicyVersionsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
     },
 )
 _OptionalListCoreNetworkPolicyVersionsRequestRequestTypeDef = TypedDict(
@@ -1310,14 +1718,22 @@
 class ListCoreNetworkPolicyVersionsRequestRequestTypeDef(
     _RequiredListCoreNetworkPolicyVersionsRequestRequestTypeDef,
     _OptionalListCoreNetworkPolicyVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListCoreNetworksRequestListCoreNetworksPaginateTypeDef = TypedDict(
+    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCoreNetworksRequestRequestTypeDef = TypedDict(
     "ListCoreNetworksRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -1328,14 +1744,26 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListPeeringsRequestListPeeringsPaginateTypeDef = TypedDict(
+    "ListPeeringsRequestListPeeringsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "PeeringType": Literal["TRANSIT_GATEWAY"],
+        "EdgeLocation": str,
+        "State": PeeringStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPeeringsRequestRequestTypeDef = TypedDict(
     "ListPeeringsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PeeringType": Literal["TRANSIT_GATEWAY"],
         "EdgeLocation": str,
         "State": PeeringStateType,
@@ -1374,14 +1802,24 @@
         "EdgeLocation": str,
         "ResourceType": str,
         "ResourceId": str,
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
 _RequiredPutCoreNetworkPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutCoreNetworkPolicyRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyDocument": str,
     },
 )
@@ -1422,14 +1860,25 @@
 RejectAttachmentRequestRequestTypeDef = TypedDict(
     "RejectAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
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
 RestoreCoreNetworkPolicyVersionRequestRequestTypeDef = TypedDict(
     "RestoreCoreNetworkPolicyVersionRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyVersionId": int,
     },
 )
@@ -1559,28 +2008,20 @@
     {
         "GlobalNetworkId": str,
         "ResourceArn": str,
         "Metadata": Mapping[str, str],
     },
 )
 
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateNetworkResourceMetadataResponseTypeDef = TypedDict(
     "UpdateNetworkResourceMetadataResponseTypeDef",
     {
         "ResourceArn": str,
         "Metadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrganizationStatusTypeDef = TypedDict(
     "OrganizationStatusTypeDef",
     {
         "OrganizationId": str,
@@ -1591,107 +2032,107 @@
     total=False,
 )
 
 AssociateConnectPeerResponseTypeDef = TypedDict(
     "AssociateConnectPeerResponseTypeDef",
     {
         "ConnectPeerAssociation": ConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateConnectPeerResponseTypeDef = TypedDict(
     "DisassociateConnectPeerResponseTypeDef",
     {
         "ConnectPeerAssociation": ConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectPeerAssociationsResponseTypeDef = TypedDict(
     "GetConnectPeerAssociationsResponseTypeDef",
     {
         "ConnectPeerAssociations": List[ConnectPeerAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateCustomerGatewayResponseTypeDef = TypedDict(
     "AssociateCustomerGatewayResponseTypeDef",
     {
         "CustomerGatewayAssociation": CustomerGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateCustomerGatewayResponseTypeDef = TypedDict(
     "DisassociateCustomerGatewayResponseTypeDef",
     {
         "CustomerGatewayAssociation": CustomerGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCustomerGatewayAssociationsResponseTypeDef = TypedDict(
     "GetCustomerGatewayAssociationsResponseTypeDef",
     {
         "CustomerGatewayAssociations": List[CustomerGatewayAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateLinkResponseTypeDef = TypedDict(
     "AssociateLinkResponseTypeDef",
     {
         "LinkAssociation": LinkAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateLinkResponseTypeDef = TypedDict(
     "DisassociateLinkResponseTypeDef",
     {
         "LinkAssociation": LinkAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLinkAssociationsResponseTypeDef = TypedDict(
     "GetLinkAssociationsResponseTypeDef",
     {
         "LinkAssociations": List[LinkAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateTransitGatewayConnectPeerResponseTypeDef = TypedDict(
     "AssociateTransitGatewayConnectPeerResponseTypeDef",
     {
         "TransitGatewayConnectPeerAssociation": TransitGatewayConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateTransitGatewayConnectPeerResponseTypeDef = TypedDict(
     "DisassociateTransitGatewayConnectPeerResponseTypeDef",
     {
         "TransitGatewayConnectPeerAssociation": TransitGatewayConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayConnectPeerAssociationsResponseTypeDef = TypedDict(
     "GetTransitGatewayConnectPeerAssociationsResponseTypeDef",
     {
         "TransitGatewayConnectPeerAssociations": List[TransitGatewayConnectPeerAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectPeerSummaryTypeDef = TypedDict(
     "ConnectPeerSummaryTypeDef",
     {
         "CoreNetworkId": str,
@@ -1881,15 +2322,15 @@
     total=False,
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkResourceTypeDef = TypedDict(
     "NetworkResourceTypeDef",
     {
         "RegisteredGatewayArn": str,
@@ -2133,15 +2574,15 @@
 )
 
 ListCoreNetworkPolicyVersionsResponseTypeDef = TypedDict(
     "ListCoreNetworkPolicyVersionsResponseTypeDef",
     {
         "CoreNetworkPolicyVersions": List[CoreNetworkPolicyVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RouteTableIdentifierTypeDef = TypedDict(
     "RouteTableIdentifierTypeDef",
     {
         "TransitGatewayRouteTableArn": str,
@@ -2352,470 +2793,29 @@
 class UpdateVpcAttachmentRequestRequestTypeDef(
     _RequiredUpdateVpcAttachmentRequestRequestTypeDef,
     _OptionalUpdateVpcAttachmentRequestRequestTypeDef,
 ):
     pass
 
 
-DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef = TypedDict(
-    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
-    {
-        "GlobalNetworkIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
-    {
-        "ConnectPeerIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef(
-    _RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-    _OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
-    "_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
-    "_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef",
-    {
-        "ConnectionIds": Sequence[str],
-        "DeviceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetConnectionsRequestGetConnectionsPaginateTypeDef(
-    _RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef,
-    _OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
-    "_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "PolicyVersionId": int,
-    },
-)
-_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
-    "_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef(
-    _RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-    _OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
-    "_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "PolicyVersionId": int,
-    },
-)
-_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
-    "_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef(
-    _RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-    _OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
-    {
-        "CustomerGatewayArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef(
-    _RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-    _OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
-    "_RequiredGetDevicesRequestGetDevicesPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
-    "_OptionalGetDevicesRequestGetDevicesPaginateTypeDef",
-    {
-        "DeviceIds": Sequence[str],
-        "SiteId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetDevicesRequestGetDevicesPaginateTypeDef(
-    _RequiredGetDevicesRequestGetDevicesPaginateTypeDef,
-    _OptionalGetDevicesRequestGetDevicesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
-    {
-        "DeviceId": str,
-        "LinkId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef(
-    _RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-    _OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
-    "_RequiredGetLinksRequestGetLinksPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
-    "_OptionalGetLinksRequestGetLinksPaginateTypeDef",
-    {
-        "LinkIds": Sequence[str],
-        "SiteId": str,
-        "Type": str,
-        "Provider": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetLinksRequestGetLinksPaginateTypeDef(
-    _RequiredGetLinksRequestGetLinksPaginateTypeDef, _OptionalGetLinksRequestGetLinksPaginateTypeDef
-):
-    pass
-
-
-_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
-    {
-        "ResourceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef(
-    _RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-    _OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "RegisteredGatewayArn": str,
-        "AwsRegion": str,
-        "AccountId": str,
-        "ResourceType": str,
-        "ResourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef(
-    _RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-    _OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "RegisteredGatewayArn": str,
-        "AwsRegion": str,
-        "AccountId": str,
-        "ResourceType": str,
-        "ResourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef(
-    _RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-    _OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "RegisteredGatewayArn": str,
-        "AwsRegion": str,
-        "AccountId": str,
-        "ResourceType": str,
-        "ResourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef(
-    _RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-    _OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
-    "_RequiredGetSitesRequestGetSitesPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
-    "_OptionalGetSitesRequestGetSitesPaginateTypeDef",
-    {
-        "SiteIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetSitesRequestGetSitesPaginateTypeDef(
-    _RequiredGetSitesRequestGetSitesPaginateTypeDef, _OptionalGetSitesRequestGetSitesPaginateTypeDef
-):
-    pass
-
-
-_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
-    {
-        "TransitGatewayConnectPeerArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef(
-    _RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-    _OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
-    "_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
-    "_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
-    {
-        "TransitGatewayArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef(
-    _RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-    _OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-):
-    pass
-
-
-ListAttachmentsRequestListAttachmentsPaginateTypeDef = TypedDict(
-    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "AttachmentType": AttachmentTypeType,
-        "EdgeLocation": str,
-        "State": AttachmentStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListConnectPeersRequestListConnectPeersPaginateTypeDef = TypedDict(
-    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "ConnectAttachmentId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
-        {
-            "CoreNetworkId": str,
-        },
-    )
-)
-_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef(
-    _RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-    _OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListCoreNetworksRequestListCoreNetworksPaginateTypeDef = TypedDict(
-    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPeeringsRequestListPeeringsPaginateTypeDef = TypedDict(
-    "ListPeeringsRequestListPeeringsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "PeeringType": Literal["TRANSIT_GATEWAY"],
-        "EdgeLocation": str,
-        "State": PeeringStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetNetworkResourceCountsResponseTypeDef = TypedDict(
     "GetNetworkResourceCountsResponseTypeDef",
     {
         "NetworkResourceCounts": List[NetworkResourceCountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResourceRelationshipsResponseTypeDef = TypedDict(
     "GetNetworkResourceRelationshipsResponseTypeDef",
     {
         "Relationships": List[RelationshipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PathComponentTypeDef = TypedDict(
     "PathComponentTypeDef",
     {
         "Sequence": int,
@@ -2873,133 +2873,133 @@
 )
 
 ListOrganizationServiceAccessStatusResponseTypeDef = TypedDict(
     "ListOrganizationServiceAccessStatusResponseTypeDef",
     {
         "OrganizationStatus": OrganizationStatusTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartOrganizationServiceAccessUpdateResponseTypeDef = TypedDict(
     "StartOrganizationServiceAccessUpdateResponseTypeDef",
     {
         "OrganizationStatus": OrganizationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConnectPeersResponseTypeDef = TypedDict(
     "ListConnectPeersResponseTypeDef",
     {
         "ConnectPeers": List[ConnectPeerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConnectionResponseTypeDef = TypedDict(
     "CreateConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteConnectionResponseTypeDef = TypedDict(
     "DeleteConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectionsResponseTypeDef = TypedDict(
     "GetConnectionsResponseTypeDef",
     {
         "Connections": List[ConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConnectionResponseTypeDef = TypedDict(
     "UpdateConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCoreNetworksResponseTypeDef = TypedDict(
     "ListCoreNetworksResponseTypeDef",
     {
         "CoreNetworks": List[CoreNetworkSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGlobalNetworkResponseTypeDef = TypedDict(
     "CreateGlobalNetworkResponseTypeDef",
     {
         "GlobalNetwork": GlobalNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGlobalNetworkResponseTypeDef = TypedDict(
     "DeleteGlobalNetworkResponseTypeDef",
     {
         "GlobalNetwork": GlobalNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGlobalNetworksResponseTypeDef = TypedDict(
     "DescribeGlobalNetworksResponseTypeDef",
     {
         "GlobalNetworks": List[GlobalNetworkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalNetworkResponseTypeDef = TypedDict(
     "UpdateGlobalNetworkResponseTypeDef",
     {
         "GlobalNetwork": GlobalNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResourcesResponseTypeDef = TypedDict(
     "GetNetworkResourcesResponseTypeDef",
     {
         "NetworkResources": List[NetworkResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePeeringResponseTypeDef = TypedDict(
     "DeletePeeringResponseTypeDef",
     {
         "Peering": PeeringTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPeeringsResponseTypeDef = TypedDict(
     "ListPeeringsResponseTypeDef",
     {
         "Peerings": List[PeeringTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransitGatewayPeeringTypeDef = TypedDict(
     "TransitGatewayPeeringTypeDef",
     {
         "Peering": PeeringTypeDef,
@@ -3030,40 +3030,40 @@
     total=False,
 )
 
 CreateLinkResponseTypeDef = TypedDict(
     "CreateLinkResponseTypeDef",
     {
         "Link": LinkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLinkResponseTypeDef = TypedDict(
     "DeleteLinkResponseTypeDef",
     {
         "Link": LinkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLinksResponseTypeDef = TypedDict(
     "GetLinksResponseTypeDef",
     {
         "Links": List[LinkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLinkResponseTypeDef = TypedDict(
     "UpdateLinkResponseTypeDef",
     {
         "Link": LinkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectPeerTypeDef = TypedDict(
     "ConnectPeerTypeDef",
     {
         "CoreNetworkId": str,
@@ -3079,65 +3079,65 @@
 )
 
 GetNetworkTelemetryResponseTypeDef = TypedDict(
     "GetNetworkTelemetryResponseTypeDef",
     {
         "NetworkTelemetry": List[NetworkTelemetryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkChangeEventsResponseTypeDef = TypedDict(
     "GetCoreNetworkChangeEventsResponseTypeDef",
     {
         "CoreNetworkChangeEvents": List[CoreNetworkChangeEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkChangeSetResponseTypeDef = TypedDict(
     "GetCoreNetworkChangeSetResponseTypeDef",
     {
         "CoreNetworkChanges": List[CoreNetworkChangeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCoreNetworkPolicyVersionResponseTypeDef = TypedDict(
     "DeleteCoreNetworkPolicyVersionResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkPolicyResponseTypeDef = TypedDict(
     "GetCoreNetworkPolicyResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutCoreNetworkPolicyResponseTypeDef = TypedDict(
     "PutCoreNetworkPolicyResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreCoreNetworkPolicyVersionResponseTypeDef = TypedDict(
     "RestoreCoreNetworkPolicyVersionResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetNetworkRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkRoutesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
@@ -3166,105 +3166,105 @@
     pass
 
 
 CreateCoreNetworkResponseTypeDef = TypedDict(
     "CreateCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCoreNetworkResponseTypeDef = TypedDict(
     "DeleteCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkResponseTypeDef = TypedDict(
     "GetCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCoreNetworkResponseTypeDef = TypedDict(
     "UpdateCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDeviceResponseTypeDef = TypedDict(
     "CreateDeviceResponseTypeDef",
     {
         "Device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDeviceResponseTypeDef = TypedDict(
     "DeleteDeviceResponseTypeDef",
     {
         "Device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevicesResponseTypeDef = TypedDict(
     "GetDevicesResponseTypeDef",
     {
         "Devices": List[DeviceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDeviceResponseTypeDef = TypedDict(
     "UpdateDeviceResponseTypeDef",
     {
         "Device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSiteResponseTypeDef = TypedDict(
     "CreateSiteResponseTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSiteResponseTypeDef = TypedDict(
     "DeleteSiteResponseTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSitesResponseTypeDef = TypedDict(
     "GetSitesResponseTypeDef",
     {
         "Sites": List[SiteTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSiteResponseTypeDef = TypedDict(
     "UpdateSiteResponseTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RouteAnalysisPathTypeDef = TypedDict(
     "RouteAnalysisPathTypeDef",
     {
         "CompletionStatus": RouteAnalysisCompletionTypeDef,
@@ -3277,64 +3277,64 @@
     "GetNetworkRoutesResponseTypeDef",
     {
         "RouteTableArn": str,
         "CoreNetworkSegmentEdge": CoreNetworkSegmentEdgeIdentifierTypeDef,
         "RouteTableType": RouteTableTypeType,
         "RouteTableTimestamp": datetime,
         "NetworkRoutes": List[NetworkRouteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterTransitGatewayResponseTypeDef = TypedDict(
     "DeregisterTransitGatewayResponseTypeDef",
     {
         "TransitGatewayRegistration": TransitGatewayRegistrationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayRegistrationsResponseTypeDef = TypedDict(
     "GetTransitGatewayRegistrationsResponseTypeDef",
     {
         "TransitGatewayRegistrations": List[TransitGatewayRegistrationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterTransitGatewayResponseTypeDef = TypedDict(
     "RegisterTransitGatewayResponseTypeDef",
     {
         "TransitGatewayRegistration": TransitGatewayRegistrationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTransitGatewayPeeringResponseTypeDef = TypedDict(
     "CreateTransitGatewayPeeringResponseTypeDef",
     {
         "TransitGatewayPeering": TransitGatewayPeeringTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayPeeringResponseTypeDef = TypedDict(
     "GetTransitGatewayPeeringResponseTypeDef",
     {
         "TransitGatewayPeering": TransitGatewayPeeringTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptAttachmentResponseTypeDef = TypedDict(
     "AcceptAttachmentResponseTypeDef",
     {
         "Attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectAttachmentTypeDef = TypedDict(
     "ConnectAttachmentTypeDef",
     {
         "Attachment": AttachmentTypeDef,
@@ -3344,32 +3344,32 @@
     total=False,
 )
 
 DeleteAttachmentResponseTypeDef = TypedDict(
     "DeleteAttachmentResponseTypeDef",
     {
         "Attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachmentsResponseTypeDef = TypedDict(
     "ListAttachmentsResponseTypeDef",
     {
         "Attachments": List[AttachmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectAttachmentResponseTypeDef = TypedDict(
     "RejectAttachmentResponseTypeDef",
     {
         "Attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SiteToSiteVpnAttachmentTypeDef = TypedDict(
     "SiteToSiteVpnAttachmentTypeDef",
     {
         "Attachment": AttachmentTypeDef,
@@ -3398,31 +3398,31 @@
     total=False,
 )
 
 CreateConnectPeerResponseTypeDef = TypedDict(
     "CreateConnectPeerResponseTypeDef",
     {
         "ConnectPeer": ConnectPeerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteConnectPeerResponseTypeDef = TypedDict(
     "DeleteConnectPeerResponseTypeDef",
     {
         "ConnectPeer": ConnectPeerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectPeerResponseTypeDef = TypedDict(
     "GetConnectPeerResponseTypeDef",
     {
         "ConnectPeer": ConnectPeerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RouteAnalysisTypeDef = TypedDict(
     "RouteAnalysisTypeDef",
     {
         "GlobalNetworkId": str,
@@ -3440,90 +3440,90 @@
     total=False,
 )
 
 CreateConnectAttachmentResponseTypeDef = TypedDict(
     "CreateConnectAttachmentResponseTypeDef",
     {
         "ConnectAttachment": ConnectAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectAttachmentResponseTypeDef = TypedDict(
     "GetConnectAttachmentResponseTypeDef",
     {
         "ConnectAttachment": ConnectAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSiteToSiteVpnAttachmentResponseTypeDef = TypedDict(
     "CreateSiteToSiteVpnAttachmentResponseTypeDef",
     {
         "SiteToSiteVpnAttachment": SiteToSiteVpnAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSiteToSiteVpnAttachmentResponseTypeDef = TypedDict(
     "GetSiteToSiteVpnAttachmentResponseTypeDef",
     {
         "SiteToSiteVpnAttachment": SiteToSiteVpnAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTransitGatewayRouteTableAttachmentResponseTypeDef = TypedDict(
     "CreateTransitGatewayRouteTableAttachmentResponseTypeDef",
     {
         "TransitGatewayRouteTableAttachment": TransitGatewayRouteTableAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayRouteTableAttachmentResponseTypeDef = TypedDict(
     "GetTransitGatewayRouteTableAttachmentResponseTypeDef",
     {
         "TransitGatewayRouteTableAttachment": TransitGatewayRouteTableAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcAttachmentResponseTypeDef = TypedDict(
     "CreateVpcAttachmentResponseTypeDef",
     {
         "VpcAttachment": VpcAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVpcAttachmentResponseTypeDef = TypedDict(
     "GetVpcAttachmentResponseTypeDef",
     {
         "VpcAttachment": VpcAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcAttachmentResponseTypeDef = TypedDict(
     "UpdateVpcAttachmentResponseTypeDef",
     {
         "VpcAttachment": VpcAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteAnalysisResponseTypeDef = TypedDict(
     "GetRouteAnalysisResponseTypeDef",
     {
         "RouteAnalysis": RouteAnalysisTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartRouteAnalysisResponseTypeDef = TypedDict(
     "StartRouteAnalysisResponseTypeDef",
     {
         "RouteAnalysis": RouteAnalysisTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager/type_defs.pyi` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -54,15 +54,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AWSLocationTypeDef",
     "AcceptAttachmentRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AccountStatusTypeDef",
     "AssociateConnectPeerRequestRequestTypeDef",
     "ConnectPeerAssociationTypeDef",
     "AssociateCustomerGatewayRequestRequestTypeDef",
     "CustomerGatewayAssociationTypeDef",
     "AssociateLinkRequestRequestTypeDef",
     "LinkAssociationTypeDef",
@@ -91,73 +90,95 @@
     "DeleteDeviceRequestRequestTypeDef",
     "DeleteGlobalNetworkRequestRequestTypeDef",
     "DeleteLinkRequestRequestTypeDef",
     "DeletePeeringRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSiteRequestRequestTypeDef",
     "DeregisterTransitGatewayRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
     "DescribeGlobalNetworksRequestRequestTypeDef",
     "DisassociateConnectPeerRequestRequestTypeDef",
     "DisassociateCustomerGatewayRequestRequestTypeDef",
     "DisassociateLinkRequestRequestTypeDef",
     "DisassociateTransitGatewayConnectPeerRequestRequestTypeDef",
     "ExecuteCoreNetworkChangeSetRequestRequestTypeDef",
     "GetConnectAttachmentRequestRequestTypeDef",
+    "GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
     "GetConnectPeerAssociationsRequestRequestTypeDef",
     "GetConnectPeerRequestRequestTypeDef",
+    "GetConnectionsRequestGetConnectionsPaginateTypeDef",
     "GetConnectionsRequestRequestTypeDef",
+    "GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
     "GetCoreNetworkChangeEventsRequestRequestTypeDef",
+    "GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
     "GetCoreNetworkChangeSetRequestRequestTypeDef",
     "GetCoreNetworkPolicyRequestRequestTypeDef",
     "GetCoreNetworkRequestRequestTypeDef",
+    "GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
     "GetCustomerGatewayAssociationsRequestRequestTypeDef",
+    "GetDevicesRequestGetDevicesPaginateTypeDef",
     "GetDevicesRequestRequestTypeDef",
+    "GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
     "GetLinkAssociationsRequestRequestTypeDef",
+    "GetLinksRequestGetLinksPaginateTypeDef",
     "GetLinksRequestRequestTypeDef",
+    "GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
     "GetNetworkResourceCountsRequestRequestTypeDef",
     "NetworkResourceCountTypeDef",
+    "GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
     "GetNetworkResourceRelationshipsRequestRequestTypeDef",
     "RelationshipTypeDef",
+    "GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
     "GetNetworkResourcesRequestRequestTypeDef",
+    "GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
     "GetNetworkTelemetryRequestRequestTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "GetRouteAnalysisRequestRequestTypeDef",
     "GetSiteToSiteVpnAttachmentRequestRequestTypeDef",
+    "GetSitesRequestGetSitesPaginateTypeDef",
     "GetSitesRequestRequestTypeDef",
+    "GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
     "GetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef",
     "GetTransitGatewayPeeringRequestRequestTypeDef",
+    "GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
     "GetTransitGatewayRegistrationsRequestRequestTypeDef",
     "GetTransitGatewayRouteTableAttachmentRequestRequestTypeDef",
     "GetVpcAttachmentRequestRequestTypeDef",
+    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
     "ListAttachmentsRequestRequestTypeDef",
+    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
     "ListConnectPeersRequestRequestTypeDef",
+    "ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
     "ListCoreNetworkPolicyVersionsRequestRequestTypeDef",
+    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
     "ListCoreNetworksRequestRequestTypeDef",
     "ListOrganizationServiceAccessStatusRequestRequestTypeDef",
+    "ListPeeringsRequestListPeeringsPaginateTypeDef",
     "ListPeeringsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "NetworkResourceSummaryTypeDef",
     "NetworkRouteDestinationTypeDef",
+    "PaginatorConfigTypeDef",
     "PutCoreNetworkPolicyRequestRequestTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
     "RegisterTransitGatewayRequestRequestTypeDef",
     "RejectAttachmentRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreCoreNetworkPolicyVersionRequestRequestTypeDef",
     "RouteAnalysisCompletionTypeDef",
     "RouteAnalysisEndpointOptionsSpecificationTypeDef",
     "RouteAnalysisEndpointOptionsTypeDef",
     "StartOrganizationServiceAccessUpdateRequestRequestTypeDef",
     "TransitGatewayRegistrationStateReasonTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateConnectionRequestRequestTypeDef",
     "UpdateCoreNetworkRequestRequestTypeDef",
     "UpdateGlobalNetworkRequestRequestTypeDef",
     "UpdateNetworkResourceMetadataRequestRequestTypeDef",
-    "GetResourcePolicyResponseTypeDef",
     "UpdateNetworkResourceMetadataResponseTypeDef",
     "OrganizationStatusTypeDef",
     "AssociateConnectPeerResponseTypeDef",
     "DisassociateConnectPeerResponseTypeDef",
     "GetConnectPeerAssociationsResponseTypeDef",
     "AssociateCustomerGatewayResponseTypeDef",
     "DisassociateCustomerGatewayResponseTypeDef",
@@ -200,35 +221,14 @@
     "CreateSiteRequestRequestTypeDef",
     "DeviceTypeDef",
     "SiteTypeDef",
     "UpdateDeviceRequestRequestTypeDef",
     "UpdateSiteRequestRequestTypeDef",
     "CreateVpcAttachmentRequestRequestTypeDef",
     "UpdateVpcAttachmentRequestRequestTypeDef",
-    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
-    "GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
-    "GetConnectionsRequestGetConnectionsPaginateTypeDef",
-    "GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
-    "GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
-    "GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
-    "GetDevicesRequestGetDevicesPaginateTypeDef",
-    "GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
-    "GetLinksRequestGetLinksPaginateTypeDef",
-    "GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
-    "GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
-    "GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
-    "GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
-    "GetSitesRequestGetSitesPaginateTypeDef",
-    "GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
-    "GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
-    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
-    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
-    "ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
-    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
-    "ListPeeringsRequestListPeeringsPaginateTypeDef",
     "GetNetworkResourceCountsResponseTypeDef",
     "GetNetworkResourceRelationshipsResponseTypeDef",
     "PathComponentTypeDef",
     "NetworkRouteTypeDef",
     "StartRouteAnalysisRequestRequestTypeDef",
     "TransitGatewayRegistrationTypeDef",
     "ListOrganizationServiceAccessStatusResponseTypeDef",
@@ -317,25 +317,14 @@
 AcceptAttachmentRequestRequestTypeDef = TypedDict(
     "AcceptAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
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
 AccountStatusTypeDef = TypedDict(
     "AccountStatusTypeDef",
     {
         "AccountId": str,
         "SLRDeploymentStatus": str,
     },
     total=False,
@@ -711,20 +700,19 @@
     "DeregisterTransitGatewayRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
         "TransitGatewayArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef = TypedDict(
+    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "GlobalNetworkIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeGlobalNetworksRequestRequestTypeDef = TypedDict(
     "DescribeGlobalNetworksRequestRequestTypeDef",
     {
@@ -779,14 +767,35 @@
 GetConnectAttachmentRequestRequestTypeDef = TypedDict(
     "GetConnectAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
     },
 )
 
+_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
+    {
+        "ConnectPeerIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef(
+    _RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
+    _OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetConnectPeerAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
@@ -808,14 +817,36 @@
 GetConnectPeerRequestRequestTypeDef = TypedDict(
     "GetConnectPeerRequestRequestTypeDef",
     {
         "ConnectPeerId": str,
     },
 )
 
+_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
+    "_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
+    "_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef",
+    {
+        "ConnectionIds": Sequence[str],
+        "DeviceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetConnectionsRequestGetConnectionsPaginateTypeDef(
+    _RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef,
+    _OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetConnectionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetConnectionsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetConnectionsRequestRequestTypeDef = TypedDict(
@@ -830,14 +861,35 @@
 )
 
 class GetConnectionsRequestRequestTypeDef(
     _RequiredGetConnectionsRequestRequestTypeDef, _OptionalGetConnectionsRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
+    "_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "PolicyVersionId": int,
+    },
+)
+_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
+    "_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef(
+    _RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
+    _OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetCoreNetworkChangeEventsRequestRequestTypeDef = TypedDict(
     "_RequiredGetCoreNetworkChangeEventsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyVersionId": int,
     },
 )
@@ -852,14 +904,35 @@
 
 class GetCoreNetworkChangeEventsRequestRequestTypeDef(
     _RequiredGetCoreNetworkChangeEventsRequestRequestTypeDef,
     _OptionalGetCoreNetworkChangeEventsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
+    "_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "PolicyVersionId": int,
+    },
+)
+_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
+    "_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef(
+    _RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
+    _OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
+):
+    pass
+
 _RequiredGetCoreNetworkChangeSetRequestRequestTypeDef = TypedDict(
     "_RequiredGetCoreNetworkChangeSetRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyVersionId": int,
     },
 )
@@ -902,14 +975,35 @@
 GetCoreNetworkRequestRequestTypeDef = TypedDict(
     "GetCoreNetworkRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
     },
 )
 
+_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
+    {
+        "CustomerGatewayArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef(
+    _RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
+    _OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetCustomerGatewayAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetCustomerGatewayAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetCustomerGatewayAssociationsRequestRequestTypeDef = TypedDict(
@@ -924,14 +1018,36 @@
 
 class GetCustomerGatewayAssociationsRequestRequestTypeDef(
     _RequiredGetCustomerGatewayAssociationsRequestRequestTypeDef,
     _OptionalGetCustomerGatewayAssociationsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
+    "_RequiredGetDevicesRequestGetDevicesPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
+    "_OptionalGetDevicesRequestGetDevicesPaginateTypeDef",
+    {
+        "DeviceIds": Sequence[str],
+        "SiteId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetDevicesRequestGetDevicesPaginateTypeDef(
+    _RequiredGetDevicesRequestGetDevicesPaginateTypeDef,
+    _OptionalGetDevicesRequestGetDevicesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetDevicesRequestRequestTypeDef = TypedDict(
     "_RequiredGetDevicesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetDevicesRequestRequestTypeDef = TypedDict(
@@ -946,14 +1062,36 @@
 )
 
 class GetDevicesRequestRequestTypeDef(
     _RequiredGetDevicesRequestRequestTypeDef, _OptionalGetDevicesRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
+    {
+        "DeviceId": str,
+        "LinkId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef(
+    _RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
+    _OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetLinkAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetLinkAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetLinkAssociationsRequestRequestTypeDef = TypedDict(
@@ -969,14 +1107,37 @@
 
 class GetLinkAssociationsRequestRequestTypeDef(
     _RequiredGetLinkAssociationsRequestRequestTypeDef,
     _OptionalGetLinkAssociationsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
+    "_RequiredGetLinksRequestGetLinksPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
+    "_OptionalGetLinksRequestGetLinksPaginateTypeDef",
+    {
+        "LinkIds": Sequence[str],
+        "SiteId": str,
+        "Type": str,
+        "Provider": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetLinksRequestGetLinksPaginateTypeDef(
+    _RequiredGetLinksRequestGetLinksPaginateTypeDef, _OptionalGetLinksRequestGetLinksPaginateTypeDef
+):
+    pass
+
 _RequiredGetLinksRequestRequestTypeDef = TypedDict(
     "_RequiredGetLinksRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetLinksRequestRequestTypeDef = TypedDict(
@@ -993,14 +1154,35 @@
 )
 
 class GetLinksRequestRequestTypeDef(
     _RequiredGetLinksRequestRequestTypeDef, _OptionalGetLinksRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
+    {
+        "ResourceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef(
+    _RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
+    _OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetNetworkResourceCountsRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkResourceCountsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkResourceCountsRequestRequestTypeDef = TypedDict(
@@ -1024,14 +1206,40 @@
     {
         "ResourceType": str,
         "Count": int,
     },
     total=False,
 )
 
+_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "RegisteredGatewayArn": str,
+        "AwsRegion": str,
+        "AccountId": str,
+        "ResourceType": str,
+        "ResourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef(
+    _RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
+    _OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetNetworkResourceRelationshipsRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkResourceRelationshipsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkResourceRelationshipsRequestRequestTypeDef = TypedDict(
@@ -1060,14 +1268,40 @@
     {
         "From": str,
         "To": str,
     },
     total=False,
 )
 
+_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "RegisteredGatewayArn": str,
+        "AwsRegion": str,
+        "AccountId": str,
+        "ResourceType": str,
+        "ResourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef(
+    _RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
+    _OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetNetworkResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkResourcesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkResourcesRequestRequestTypeDef = TypedDict(
@@ -1087,14 +1321,40 @@
 
 class GetNetworkResourcesRequestRequestTypeDef(
     _RequiredGetNetworkResourcesRequestRequestTypeDef,
     _OptionalGetNetworkResourcesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
+    "_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
+    "_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "RegisteredGatewayArn": str,
+        "AwsRegion": str,
+        "AccountId": str,
+        "ResourceType": str,
+        "ResourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef(
+    _RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
+    _OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetNetworkTelemetryRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkTelemetryRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetNetworkTelemetryRequestRequestTypeDef = TypedDict(
@@ -1121,14 +1381,22 @@
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "PolicyDocument": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRouteAnalysisRequestRequestTypeDef = TypedDict(
     "GetRouteAnalysisRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
         "RouteAnalysisId": str,
     },
 )
@@ -1136,14 +1404,34 @@
 GetSiteToSiteVpnAttachmentRequestRequestTypeDef = TypedDict(
     "GetSiteToSiteVpnAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
     },
 )
 
+_RequiredGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
+    "_RequiredGetSitesRequestGetSitesPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
+    "_OptionalGetSitesRequestGetSitesPaginateTypeDef",
+    {
+        "SiteIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetSitesRequestGetSitesPaginateTypeDef(
+    _RequiredGetSitesRequestGetSitesPaginateTypeDef, _OptionalGetSitesRequestGetSitesPaginateTypeDef
+):
+    pass
+
 _RequiredGetSitesRequestRequestTypeDef = TypedDict(
     "_RequiredGetSitesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetSitesRequestRequestTypeDef = TypedDict(
@@ -1157,14 +1445,35 @@
 )
 
 class GetSitesRequestRequestTypeDef(
     _RequiredGetSitesRequestRequestTypeDef, _OptionalGetSitesRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
+    {
+        "TransitGatewayConnectPeerArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef(
+    _RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
+    _OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef = TypedDict(
@@ -1186,14 +1495,35 @@
 GetTransitGatewayPeeringRequestRequestTypeDef = TypedDict(
     "GetTransitGatewayPeeringRequestRequestTypeDef",
     {
         "PeeringId": str,
     },
 )
 
+_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
+    "_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
+    {
+        "GlobalNetworkId": str,
+    },
+)
+_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
+    "_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
+    {
+        "TransitGatewayArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef(
+    _RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
+    _OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetTransitGatewayRegistrationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTransitGatewayRegistrationsRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
     },
 )
 _OptionalGetTransitGatewayRegistrationsRequestRequestTypeDef = TypedDict(
@@ -1222,38 +1552,84 @@
 GetVpcAttachmentRequestRequestTypeDef = TypedDict(
     "GetVpcAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
     },
 )
 
+ListAttachmentsRequestListAttachmentsPaginateTypeDef = TypedDict(
+    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "AttachmentType": AttachmentTypeType,
+        "EdgeLocation": str,
+        "State": AttachmentStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAttachmentsRequestRequestTypeDef = TypedDict(
     "ListAttachmentsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "AttachmentType": AttachmentTypeType,
         "EdgeLocation": str,
         "State": AttachmentStateType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListConnectPeersRequestListConnectPeersPaginateTypeDef = TypedDict(
+    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "ConnectAttachmentId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConnectPeersRequestRequestTypeDef = TypedDict(
     "ListConnectPeersRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "ConnectAttachmentId": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
+        {
+            "CoreNetworkId": str,
+        },
+    )
+)
+_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef(
+    _RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
+    _OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListCoreNetworkPolicyVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListCoreNetworkPolicyVersionsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
     },
 )
 _OptionalListCoreNetworkPolicyVersionsRequestRequestTypeDef = TypedDict(
@@ -1267,14 +1643,22 @@
 
 class ListCoreNetworkPolicyVersionsRequestRequestTypeDef(
     _RequiredListCoreNetworkPolicyVersionsRequestRequestTypeDef,
     _OptionalListCoreNetworkPolicyVersionsRequestRequestTypeDef,
 ):
     pass
 
+ListCoreNetworksRequestListCoreNetworksPaginateTypeDef = TypedDict(
+    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCoreNetworksRequestRequestTypeDef = TypedDict(
     "ListCoreNetworksRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -1285,14 +1669,26 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListPeeringsRequestListPeeringsPaginateTypeDef = TypedDict(
+    "ListPeeringsRequestListPeeringsPaginateTypeDef",
+    {
+        "CoreNetworkId": str,
+        "PeeringType": Literal["TRANSIT_GATEWAY"],
+        "EdgeLocation": str,
+        "State": PeeringStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPeeringsRequestRequestTypeDef = TypedDict(
     "ListPeeringsRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PeeringType": Literal["TRANSIT_GATEWAY"],
         "EdgeLocation": str,
         "State": PeeringStateType,
@@ -1331,14 +1727,24 @@
         "EdgeLocation": str,
         "ResourceType": str,
         "ResourceId": str,
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
 _RequiredPutCoreNetworkPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutCoreNetworkPolicyRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyDocument": str,
     },
 )
@@ -1377,14 +1783,25 @@
 RejectAttachmentRequestRequestTypeDef = TypedDict(
     "RejectAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
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
 RestoreCoreNetworkPolicyVersionRequestRequestTypeDef = TypedDict(
     "RestoreCoreNetworkPolicyVersionRequestRequestTypeDef",
     {
         "CoreNetworkId": str,
         "PolicyVersionId": int,
     },
 )
@@ -1508,28 +1925,20 @@
     {
         "GlobalNetworkId": str,
         "ResourceArn": str,
         "Metadata": Mapping[str, str],
     },
 )
 
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "PolicyDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateNetworkResourceMetadataResponseTypeDef = TypedDict(
     "UpdateNetworkResourceMetadataResponseTypeDef",
     {
         "ResourceArn": str,
         "Metadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrganizationStatusTypeDef = TypedDict(
     "OrganizationStatusTypeDef",
     {
         "OrganizationId": str,
@@ -1540,107 +1949,107 @@
     total=False,
 )
 
 AssociateConnectPeerResponseTypeDef = TypedDict(
     "AssociateConnectPeerResponseTypeDef",
     {
         "ConnectPeerAssociation": ConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateConnectPeerResponseTypeDef = TypedDict(
     "DisassociateConnectPeerResponseTypeDef",
     {
         "ConnectPeerAssociation": ConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectPeerAssociationsResponseTypeDef = TypedDict(
     "GetConnectPeerAssociationsResponseTypeDef",
     {
         "ConnectPeerAssociations": List[ConnectPeerAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateCustomerGatewayResponseTypeDef = TypedDict(
     "AssociateCustomerGatewayResponseTypeDef",
     {
         "CustomerGatewayAssociation": CustomerGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateCustomerGatewayResponseTypeDef = TypedDict(
     "DisassociateCustomerGatewayResponseTypeDef",
     {
         "CustomerGatewayAssociation": CustomerGatewayAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCustomerGatewayAssociationsResponseTypeDef = TypedDict(
     "GetCustomerGatewayAssociationsResponseTypeDef",
     {
         "CustomerGatewayAssociations": List[CustomerGatewayAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateLinkResponseTypeDef = TypedDict(
     "AssociateLinkResponseTypeDef",
     {
         "LinkAssociation": LinkAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateLinkResponseTypeDef = TypedDict(
     "DisassociateLinkResponseTypeDef",
     {
         "LinkAssociation": LinkAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLinkAssociationsResponseTypeDef = TypedDict(
     "GetLinkAssociationsResponseTypeDef",
     {
         "LinkAssociations": List[LinkAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateTransitGatewayConnectPeerResponseTypeDef = TypedDict(
     "AssociateTransitGatewayConnectPeerResponseTypeDef",
     {
         "TransitGatewayConnectPeerAssociation": TransitGatewayConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateTransitGatewayConnectPeerResponseTypeDef = TypedDict(
     "DisassociateTransitGatewayConnectPeerResponseTypeDef",
     {
         "TransitGatewayConnectPeerAssociation": TransitGatewayConnectPeerAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayConnectPeerAssociationsResponseTypeDef = TypedDict(
     "GetTransitGatewayConnectPeerAssociationsResponseTypeDef",
     {
         "TransitGatewayConnectPeerAssociations": List[TransitGatewayConnectPeerAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectPeerSummaryTypeDef = TypedDict(
     "ConnectPeerSummaryTypeDef",
     {
         "CoreNetworkId": str,
@@ -1820,15 +2229,15 @@
     total=False,
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkResourceTypeDef = TypedDict(
     "NetworkResourceTypeDef",
     {
         "RegisteredGatewayArn": str,
@@ -2064,15 +2473,15 @@
 )
 
 ListCoreNetworkPolicyVersionsResponseTypeDef = TypedDict(
     "ListCoreNetworkPolicyVersionsResponseTypeDef",
     {
         "CoreNetworkPolicyVersions": List[CoreNetworkPolicyVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RouteTableIdentifierTypeDef = TypedDict(
     "RouteTableIdentifierTypeDef",
     {
         "TransitGatewayRouteTableArn": str,
@@ -2271,438 +2680,29 @@
 
 class UpdateVpcAttachmentRequestRequestTypeDef(
     _RequiredUpdateVpcAttachmentRequestRequestTypeDef,
     _OptionalUpdateVpcAttachmentRequestRequestTypeDef,
 ):
     pass
 
-DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef = TypedDict(
-    "DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef",
-    {
-        "GlobalNetworkIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef",
-    {
-        "ConnectPeerIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef(
-    _RequiredGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-    _OptionalGetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
-    "_RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
-    "_OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef",
-    {
-        "ConnectionIds": Sequence[str],
-        "DeviceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetConnectionsRequestGetConnectionsPaginateTypeDef(
-    _RequiredGetConnectionsRequestGetConnectionsPaginateTypeDef,
-    _OptionalGetConnectionsRequestGetConnectionsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
-    "_RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "PolicyVersionId": int,
-    },
-)
-_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef = TypedDict(
-    "_OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef(
-    _RequiredGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-    _OptionalGetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
-    "_RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "PolicyVersionId": int,
-    },
-)
-_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef = TypedDict(
-    "_OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef(
-    _RequiredGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-    _OptionalGetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-):
-    pass
-
-_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef",
-    {
-        "CustomerGatewayArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef(
-    _RequiredGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-    _OptionalGetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
-    "_RequiredGetDevicesRequestGetDevicesPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetDevicesRequestGetDevicesPaginateTypeDef = TypedDict(
-    "_OptionalGetDevicesRequestGetDevicesPaginateTypeDef",
-    {
-        "DeviceIds": Sequence[str],
-        "SiteId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetDevicesRequestGetDevicesPaginateTypeDef(
-    _RequiredGetDevicesRequestGetDevicesPaginateTypeDef,
-    _OptionalGetDevicesRequestGetDevicesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef",
-    {
-        "DeviceId": str,
-        "LinkId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef(
-    _RequiredGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-    _OptionalGetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
-    "_RequiredGetLinksRequestGetLinksPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetLinksRequestGetLinksPaginateTypeDef = TypedDict(
-    "_OptionalGetLinksRequestGetLinksPaginateTypeDef",
-    {
-        "LinkIds": Sequence[str],
-        "SiteId": str,
-        "Type": str,
-        "Provider": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetLinksRequestGetLinksPaginateTypeDef(
-    _RequiredGetLinksRequestGetLinksPaginateTypeDef, _OptionalGetLinksRequestGetLinksPaginateTypeDef
-):
-    pass
-
-_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef",
-    {
-        "ResourceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef(
-    _RequiredGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-    _OptionalGetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "RegisteredGatewayArn": str,
-        "AwsRegion": str,
-        "AccountId": str,
-        "ResourceType": str,
-        "ResourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef(
-    _RequiredGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-    _OptionalGetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "RegisteredGatewayArn": str,
-        "AwsRegion": str,
-        "AccountId": str,
-        "ResourceType": str,
-        "ResourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef(
-    _RequiredGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-    _OptionalGetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
-    "_RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef = TypedDict(
-    "_OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "RegisteredGatewayArn": str,
-        "AwsRegion": str,
-        "AccountId": str,
-        "ResourceType": str,
-        "ResourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef(
-    _RequiredGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-    _OptionalGetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-):
-    pass
-
-_RequiredGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
-    "_RequiredGetSitesRequestGetSitesPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetSitesRequestGetSitesPaginateTypeDef = TypedDict(
-    "_OptionalGetSitesRequestGetSitesPaginateTypeDef",
-    {
-        "SiteIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetSitesRequestGetSitesPaginateTypeDef(
-    _RequiredGetSitesRequestGetSitesPaginateTypeDef, _OptionalGetSitesRequestGetSitesPaginateTypeDef
-):
-    pass
-
-_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef",
-    {
-        "TransitGatewayConnectPeerArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef(
-    _RequiredGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-    _OptionalGetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
-    "_RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
-    {
-        "GlobalNetworkId": str,
-    },
-)
-_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef = TypedDict(
-    "_OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef",
-    {
-        "TransitGatewayArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef(
-    _RequiredGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-    _OptionalGetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-):
-    pass
-
-ListAttachmentsRequestListAttachmentsPaginateTypeDef = TypedDict(
-    "ListAttachmentsRequestListAttachmentsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "AttachmentType": AttachmentTypeType,
-        "EdgeLocation": str,
-        "State": AttachmentStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListConnectPeersRequestListConnectPeersPaginateTypeDef = TypedDict(
-    "ListConnectPeersRequestListConnectPeersPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "ConnectAttachmentId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
-        {
-            "CoreNetworkId": str,
-        },
-    )
-)
-_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef(
-    _RequiredListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-    _OptionalListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-):
-    pass
-
-ListCoreNetworksRequestListCoreNetworksPaginateTypeDef = TypedDict(
-    "ListCoreNetworksRequestListCoreNetworksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPeeringsRequestListPeeringsPaginateTypeDef = TypedDict(
-    "ListPeeringsRequestListPeeringsPaginateTypeDef",
-    {
-        "CoreNetworkId": str,
-        "PeeringType": Literal["TRANSIT_GATEWAY"],
-        "EdgeLocation": str,
-        "State": PeeringStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetNetworkResourceCountsResponseTypeDef = TypedDict(
     "GetNetworkResourceCountsResponseTypeDef",
     {
         "NetworkResourceCounts": List[NetworkResourceCountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResourceRelationshipsResponseTypeDef = TypedDict(
     "GetNetworkResourceRelationshipsResponseTypeDef",
     {
         "Relationships": List[RelationshipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PathComponentTypeDef = TypedDict(
     "PathComponentTypeDef",
     {
         "Sequence": int,
@@ -2758,133 +2758,133 @@
 )
 
 ListOrganizationServiceAccessStatusResponseTypeDef = TypedDict(
     "ListOrganizationServiceAccessStatusResponseTypeDef",
     {
         "OrganizationStatus": OrganizationStatusTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartOrganizationServiceAccessUpdateResponseTypeDef = TypedDict(
     "StartOrganizationServiceAccessUpdateResponseTypeDef",
     {
         "OrganizationStatus": OrganizationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConnectPeersResponseTypeDef = TypedDict(
     "ListConnectPeersResponseTypeDef",
     {
         "ConnectPeers": List[ConnectPeerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConnectionResponseTypeDef = TypedDict(
     "CreateConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteConnectionResponseTypeDef = TypedDict(
     "DeleteConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectionsResponseTypeDef = TypedDict(
     "GetConnectionsResponseTypeDef",
     {
         "Connections": List[ConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConnectionResponseTypeDef = TypedDict(
     "UpdateConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCoreNetworksResponseTypeDef = TypedDict(
     "ListCoreNetworksResponseTypeDef",
     {
         "CoreNetworks": List[CoreNetworkSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGlobalNetworkResponseTypeDef = TypedDict(
     "CreateGlobalNetworkResponseTypeDef",
     {
         "GlobalNetwork": GlobalNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGlobalNetworkResponseTypeDef = TypedDict(
     "DeleteGlobalNetworkResponseTypeDef",
     {
         "GlobalNetwork": GlobalNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGlobalNetworksResponseTypeDef = TypedDict(
     "DescribeGlobalNetworksResponseTypeDef",
     {
         "GlobalNetworks": List[GlobalNetworkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalNetworkResponseTypeDef = TypedDict(
     "UpdateGlobalNetworkResponseTypeDef",
     {
         "GlobalNetwork": GlobalNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResourcesResponseTypeDef = TypedDict(
     "GetNetworkResourcesResponseTypeDef",
     {
         "NetworkResources": List[NetworkResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePeeringResponseTypeDef = TypedDict(
     "DeletePeeringResponseTypeDef",
     {
         "Peering": PeeringTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPeeringsResponseTypeDef = TypedDict(
     "ListPeeringsResponseTypeDef",
     {
         "Peerings": List[PeeringTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransitGatewayPeeringTypeDef = TypedDict(
     "TransitGatewayPeeringTypeDef",
     {
         "Peering": PeeringTypeDef,
@@ -2915,40 +2915,40 @@
     total=False,
 )
 
 CreateLinkResponseTypeDef = TypedDict(
     "CreateLinkResponseTypeDef",
     {
         "Link": LinkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLinkResponseTypeDef = TypedDict(
     "DeleteLinkResponseTypeDef",
     {
         "Link": LinkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLinksResponseTypeDef = TypedDict(
     "GetLinksResponseTypeDef",
     {
         "Links": List[LinkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLinkResponseTypeDef = TypedDict(
     "UpdateLinkResponseTypeDef",
     {
         "Link": LinkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectPeerTypeDef = TypedDict(
     "ConnectPeerTypeDef",
     {
         "CoreNetworkId": str,
@@ -2964,65 +2964,65 @@
 )
 
 GetNetworkTelemetryResponseTypeDef = TypedDict(
     "GetNetworkTelemetryResponseTypeDef",
     {
         "NetworkTelemetry": List[NetworkTelemetryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkChangeEventsResponseTypeDef = TypedDict(
     "GetCoreNetworkChangeEventsResponseTypeDef",
     {
         "CoreNetworkChangeEvents": List[CoreNetworkChangeEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkChangeSetResponseTypeDef = TypedDict(
     "GetCoreNetworkChangeSetResponseTypeDef",
     {
         "CoreNetworkChanges": List[CoreNetworkChangeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCoreNetworkPolicyVersionResponseTypeDef = TypedDict(
     "DeleteCoreNetworkPolicyVersionResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkPolicyResponseTypeDef = TypedDict(
     "GetCoreNetworkPolicyResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutCoreNetworkPolicyResponseTypeDef = TypedDict(
     "PutCoreNetworkPolicyResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreCoreNetworkPolicyVersionResponseTypeDef = TypedDict(
     "RestoreCoreNetworkPolicyVersionResponseTypeDef",
     {
         "CoreNetworkPolicy": CoreNetworkPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetNetworkRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredGetNetworkRoutesRequestRequestTypeDef",
     {
         "GlobalNetworkId": str,
@@ -3049,105 +3049,105 @@
 ):
     pass
 
 CreateCoreNetworkResponseTypeDef = TypedDict(
     "CreateCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCoreNetworkResponseTypeDef = TypedDict(
     "DeleteCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCoreNetworkResponseTypeDef = TypedDict(
     "GetCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCoreNetworkResponseTypeDef = TypedDict(
     "UpdateCoreNetworkResponseTypeDef",
     {
         "CoreNetwork": CoreNetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDeviceResponseTypeDef = TypedDict(
     "CreateDeviceResponseTypeDef",
     {
         "Device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDeviceResponseTypeDef = TypedDict(
     "DeleteDeviceResponseTypeDef",
     {
         "Device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevicesResponseTypeDef = TypedDict(
     "GetDevicesResponseTypeDef",
     {
         "Devices": List[DeviceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDeviceResponseTypeDef = TypedDict(
     "UpdateDeviceResponseTypeDef",
     {
         "Device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSiteResponseTypeDef = TypedDict(
     "CreateSiteResponseTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSiteResponseTypeDef = TypedDict(
     "DeleteSiteResponseTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSitesResponseTypeDef = TypedDict(
     "GetSitesResponseTypeDef",
     {
         "Sites": List[SiteTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSiteResponseTypeDef = TypedDict(
     "UpdateSiteResponseTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RouteAnalysisPathTypeDef = TypedDict(
     "RouteAnalysisPathTypeDef",
     {
         "CompletionStatus": RouteAnalysisCompletionTypeDef,
@@ -3160,64 +3160,64 @@
     "GetNetworkRoutesResponseTypeDef",
     {
         "RouteTableArn": str,
         "CoreNetworkSegmentEdge": CoreNetworkSegmentEdgeIdentifierTypeDef,
         "RouteTableType": RouteTableTypeType,
         "RouteTableTimestamp": datetime,
         "NetworkRoutes": List[NetworkRouteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterTransitGatewayResponseTypeDef = TypedDict(
     "DeregisterTransitGatewayResponseTypeDef",
     {
         "TransitGatewayRegistration": TransitGatewayRegistrationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayRegistrationsResponseTypeDef = TypedDict(
     "GetTransitGatewayRegistrationsResponseTypeDef",
     {
         "TransitGatewayRegistrations": List[TransitGatewayRegistrationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterTransitGatewayResponseTypeDef = TypedDict(
     "RegisterTransitGatewayResponseTypeDef",
     {
         "TransitGatewayRegistration": TransitGatewayRegistrationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTransitGatewayPeeringResponseTypeDef = TypedDict(
     "CreateTransitGatewayPeeringResponseTypeDef",
     {
         "TransitGatewayPeering": TransitGatewayPeeringTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayPeeringResponseTypeDef = TypedDict(
     "GetTransitGatewayPeeringResponseTypeDef",
     {
         "TransitGatewayPeering": TransitGatewayPeeringTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptAttachmentResponseTypeDef = TypedDict(
     "AcceptAttachmentResponseTypeDef",
     {
         "Attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectAttachmentTypeDef = TypedDict(
     "ConnectAttachmentTypeDef",
     {
         "Attachment": AttachmentTypeDef,
@@ -3227,32 +3227,32 @@
     total=False,
 )
 
 DeleteAttachmentResponseTypeDef = TypedDict(
     "DeleteAttachmentResponseTypeDef",
     {
         "Attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttachmentsResponseTypeDef = TypedDict(
     "ListAttachmentsResponseTypeDef",
     {
         "Attachments": List[AttachmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectAttachmentResponseTypeDef = TypedDict(
     "RejectAttachmentResponseTypeDef",
     {
         "Attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SiteToSiteVpnAttachmentTypeDef = TypedDict(
     "SiteToSiteVpnAttachmentTypeDef",
     {
         "Attachment": AttachmentTypeDef,
@@ -3281,31 +3281,31 @@
     total=False,
 )
 
 CreateConnectPeerResponseTypeDef = TypedDict(
     "CreateConnectPeerResponseTypeDef",
     {
         "ConnectPeer": ConnectPeerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteConnectPeerResponseTypeDef = TypedDict(
     "DeleteConnectPeerResponseTypeDef",
     {
         "ConnectPeer": ConnectPeerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectPeerResponseTypeDef = TypedDict(
     "GetConnectPeerResponseTypeDef",
     {
         "ConnectPeer": ConnectPeerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RouteAnalysisTypeDef = TypedDict(
     "RouteAnalysisTypeDef",
     {
         "GlobalNetworkId": str,
@@ -3323,90 +3323,90 @@
     total=False,
 )
 
 CreateConnectAttachmentResponseTypeDef = TypedDict(
     "CreateConnectAttachmentResponseTypeDef",
     {
         "ConnectAttachment": ConnectAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectAttachmentResponseTypeDef = TypedDict(
     "GetConnectAttachmentResponseTypeDef",
     {
         "ConnectAttachment": ConnectAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSiteToSiteVpnAttachmentResponseTypeDef = TypedDict(
     "CreateSiteToSiteVpnAttachmentResponseTypeDef",
     {
         "SiteToSiteVpnAttachment": SiteToSiteVpnAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSiteToSiteVpnAttachmentResponseTypeDef = TypedDict(
     "GetSiteToSiteVpnAttachmentResponseTypeDef",
     {
         "SiteToSiteVpnAttachment": SiteToSiteVpnAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTransitGatewayRouteTableAttachmentResponseTypeDef = TypedDict(
     "CreateTransitGatewayRouteTableAttachmentResponseTypeDef",
     {
         "TransitGatewayRouteTableAttachment": TransitGatewayRouteTableAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTransitGatewayRouteTableAttachmentResponseTypeDef = TypedDict(
     "GetTransitGatewayRouteTableAttachmentResponseTypeDef",
     {
         "TransitGatewayRouteTableAttachment": TransitGatewayRouteTableAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcAttachmentResponseTypeDef = TypedDict(
     "CreateVpcAttachmentResponseTypeDef",
     {
         "VpcAttachment": VpcAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVpcAttachmentResponseTypeDef = TypedDict(
     "GetVpcAttachmentResponseTypeDef",
     {
         "VpcAttachment": VpcAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcAttachmentResponseTypeDef = TypedDict(
     "UpdateVpcAttachmentResponseTypeDef",
     {
         "VpcAttachment": VpcAttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteAnalysisResponseTypeDef = TypedDict(
     "GetRouteAnalysisResponseTypeDef",
     {
         "RouteAnalysis": RouteAnalysisTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartRouteAnalysisResponseTypeDef = TypedDict(
     "StartRouteAnalysisResponseTypeDef",
     {
         "RouteAnalysis": RouteAnalysisTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/PKG-INFO` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-networkmanager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.NetworkManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.NetworkManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-networkmanager"></a>
 
 # types-aiobotocore-networkmanager
 
 [![PyPI - types-aiobotocore-networkmanager](https://img.shields.io/pypi/v/types-aiobotocore-networkmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-networkmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-networkmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-networkmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-networkmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-networkmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NetworkManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
+[aiobotocore.NetworkManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
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
 [types-aiobotocore-networkmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_networkmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -437,15 +437,14 @@
 `types_aiobotocore_networkmanager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_networkmanager.type_defs import (
     AWSLocationTypeDef,
     AcceptAttachmentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AccountStatusTypeDef,
     AssociateConnectPeerRequestRequestTypeDef,
     ConnectPeerAssociationTypeDef,
     AssociateCustomerGatewayRequestRequestTypeDef,
     CustomerGatewayAssociationTypeDef,
     AssociateLinkRequestRequestTypeDef,
     LinkAssociationTypeDef,
@@ -474,73 +473,95 @@
     DeleteDeviceRequestRequestTypeDef,
     DeleteGlobalNetworkRequestRequestTypeDef,
     DeleteLinkRequestRequestTypeDef,
     DeletePeeringRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSiteRequestRequestTypeDef,
     DeregisterTransitGatewayRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef,
     DescribeGlobalNetworksRequestRequestTypeDef,
     DisassociateConnectPeerRequestRequestTypeDef,
     DisassociateCustomerGatewayRequestRequestTypeDef,
     DisassociateLinkRequestRequestTypeDef,
     DisassociateTransitGatewayConnectPeerRequestRequestTypeDef,
     ExecuteCoreNetworkChangeSetRequestRequestTypeDef,
     GetConnectAttachmentRequestRequestTypeDef,
+    GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
     GetConnectPeerAssociationsRequestRequestTypeDef,
     GetConnectPeerRequestRequestTypeDef,
+    GetConnectionsRequestGetConnectionsPaginateTypeDef,
     GetConnectionsRequestRequestTypeDef,
+    GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
     GetCoreNetworkChangeEventsRequestRequestTypeDef,
+    GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
     GetCoreNetworkChangeSetRequestRequestTypeDef,
     GetCoreNetworkPolicyRequestRequestTypeDef,
     GetCoreNetworkRequestRequestTypeDef,
+    GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
     GetCustomerGatewayAssociationsRequestRequestTypeDef,
+    GetDevicesRequestGetDevicesPaginateTypeDef,
     GetDevicesRequestRequestTypeDef,
+    GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
     GetLinkAssociationsRequestRequestTypeDef,
+    GetLinksRequestGetLinksPaginateTypeDef,
     GetLinksRequestRequestTypeDef,
+    GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
     GetNetworkResourceCountsRequestRequestTypeDef,
     NetworkResourceCountTypeDef,
+    GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
     GetNetworkResourceRelationshipsRequestRequestTypeDef,
     RelationshipTypeDef,
+    GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
     GetNetworkResourcesRequestRequestTypeDef,
+    GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
     GetNetworkTelemetryRequestRequestTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetRouteAnalysisRequestRequestTypeDef,
     GetSiteToSiteVpnAttachmentRequestRequestTypeDef,
+    GetSitesRequestGetSitesPaginateTypeDef,
     GetSitesRequestRequestTypeDef,
+    GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
     GetTransitGatewayConnectPeerAssociationsRequestRequestTypeDef,
     GetTransitGatewayPeeringRequestRequestTypeDef,
+    GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
     GetTransitGatewayRegistrationsRequestRequestTypeDef,
     GetTransitGatewayRouteTableAttachmentRequestRequestTypeDef,
     GetVpcAttachmentRequestRequestTypeDef,
+    ListAttachmentsRequestListAttachmentsPaginateTypeDef,
     ListAttachmentsRequestRequestTypeDef,
+    ListConnectPeersRequestListConnectPeersPaginateTypeDef,
     ListConnectPeersRequestRequestTypeDef,
+    ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
     ListCoreNetworkPolicyVersionsRequestRequestTypeDef,
+    ListCoreNetworksRequestListCoreNetworksPaginateTypeDef,
     ListCoreNetworksRequestRequestTypeDef,
     ListOrganizationServiceAccessStatusRequestRequestTypeDef,
+    ListPeeringsRequestListPeeringsPaginateTypeDef,
     ListPeeringsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     NetworkResourceSummaryTypeDef,
     NetworkRouteDestinationTypeDef,
+    PaginatorConfigTypeDef,
     PutCoreNetworkPolicyRequestRequestTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
     RegisterTransitGatewayRequestRequestTypeDef,
     RejectAttachmentRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreCoreNetworkPolicyVersionRequestRequestTypeDef,
     RouteAnalysisCompletionTypeDef,
     RouteAnalysisEndpointOptionsSpecificationTypeDef,
     RouteAnalysisEndpointOptionsTypeDef,
     StartOrganizationServiceAccessUpdateRequestRequestTypeDef,
     TransitGatewayRegistrationStateReasonTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateConnectionRequestRequestTypeDef,
     UpdateCoreNetworkRequestRequestTypeDef,
     UpdateGlobalNetworkRequestRequestTypeDef,
     UpdateNetworkResourceMetadataRequestRequestTypeDef,
-    GetResourcePolicyResponseTypeDef,
     UpdateNetworkResourceMetadataResponseTypeDef,
     OrganizationStatusTypeDef,
     AssociateConnectPeerResponseTypeDef,
     DisassociateConnectPeerResponseTypeDef,
     GetConnectPeerAssociationsResponseTypeDef,
     AssociateCustomerGatewayResponseTypeDef,
     DisassociateCustomerGatewayResponseTypeDef,
@@ -583,35 +604,14 @@
     CreateSiteRequestRequestTypeDef,
     DeviceTypeDef,
     SiteTypeDef,
     UpdateDeviceRequestRequestTypeDef,
     UpdateSiteRequestRequestTypeDef,
     CreateVpcAttachmentRequestRequestTypeDef,
     UpdateVpcAttachmentRequestRequestTypeDef,
-    DescribeGlobalNetworksRequestDescribeGlobalNetworksPaginateTypeDef,
-    GetConnectPeerAssociationsRequestGetConnectPeerAssociationsPaginateTypeDef,
-    GetConnectionsRequestGetConnectionsPaginateTypeDef,
-    GetCoreNetworkChangeEventsRequestGetCoreNetworkChangeEventsPaginateTypeDef,
-    GetCoreNetworkChangeSetRequestGetCoreNetworkChangeSetPaginateTypeDef,
-    GetCustomerGatewayAssociationsRequestGetCustomerGatewayAssociationsPaginateTypeDef,
-    GetDevicesRequestGetDevicesPaginateTypeDef,
-    GetLinkAssociationsRequestGetLinkAssociationsPaginateTypeDef,
-    GetLinksRequestGetLinksPaginateTypeDef,
-    GetNetworkResourceCountsRequestGetNetworkResourceCountsPaginateTypeDef,
-    GetNetworkResourceRelationshipsRequestGetNetworkResourceRelationshipsPaginateTypeDef,
-    GetNetworkResourcesRequestGetNetworkResourcesPaginateTypeDef,
-    GetNetworkTelemetryRequestGetNetworkTelemetryPaginateTypeDef,
-    GetSitesRequestGetSitesPaginateTypeDef,
-    GetTransitGatewayConnectPeerAssociationsRequestGetTransitGatewayConnectPeerAssociationsPaginateTypeDef,
-    GetTransitGatewayRegistrationsRequestGetTransitGatewayRegistrationsPaginateTypeDef,
-    ListAttachmentsRequestListAttachmentsPaginateTypeDef,
-    ListConnectPeersRequestListConnectPeersPaginateTypeDef,
-    ListCoreNetworkPolicyVersionsRequestListCoreNetworkPolicyVersionsPaginateTypeDef,
-    ListCoreNetworksRequestListCoreNetworksPaginateTypeDef,
-    ListPeeringsRequestListPeeringsPaginateTypeDef,
     GetNetworkResourceCountsResponseTypeDef,
     GetNetworkResourceRelationshipsResponseTypeDef,
     PathComponentTypeDef,
     NetworkRouteTypeDef,
     StartRouteAnalysisRequestRequestTypeDef,
     TransitGatewayRegistrationTypeDef,
     ListOrganizationServiceAccessStatusResponseTypeDef,
@@ -696,43 +696,43 @@
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

### Comparing `types-aiobotocore-networkmanager-2.5.0.post1/types_aiobotocore_networkmanager.egg-info/SOURCES.txt` & `types-aiobotocore-networkmanager-2.5.1/types_aiobotocore_networkmanager.egg-info/SOURCES.txt`

 * *Files identical despite different names*

