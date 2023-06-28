# Comparing `tmp/types-aiobotocore-route53-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-route53-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-route53-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-route53-2.5.1.tar", last modified: Wed Jun 28 01:44:04 2023, max compression
```

## Comparing `types-aiobotocore-route53-2.5.0.post1.tar` & `types-aiobotocore-route53-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.543561 types-aiobotocore-route53-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    23124 2023-03-11 12:27:13.543561 types-aiobotocore-route53-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21553 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.543561 types-aiobotocore-route53-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.539561 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/
--rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2556 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    58365 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    58277 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12808 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12806 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10339 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10328 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    61069 2023-03-11 12:22:38.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    61002 2023-03-11 12:22:38.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1626 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1625 2023-03-11 12:22:37.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.543561 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    23124 2023-03-11 12:27:13.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      886 2023-03-11 12:27:13.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:27:13.000000 types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:04.906203 types-aiobotocore-route53-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23116 2023-06-28 01:44:04.902203 types-aiobotocore-route53-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21551 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:04.906203 types-aiobotocore-route53-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:39:21.000000 types-aiobotocore-route53-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:04.902203 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/
+-rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2556 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58365 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58277 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13017 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13015 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10235 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10225 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    61209 2023-06-28 01:39:26.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    61142 2023-06-28 01:39:25.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1626 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1625 2023-06-28 01:39:22.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:04.902203 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23116 2023-06-28 01:44:04.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      886 2023-06-28 01:44:04.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:04.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:04.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:04.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:44:04.000000 types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-route53-2.5.0.post1/LICENSE` & `types-aiobotocore-route53-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-route53-2.5.0.post1/PKG-INFO` & `types-aiobotocore-route53-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53"></a>
 
 # types-aiobotocore-route53
 
 [![PyPI - types-aiobotocore-route53](https://img.shields.io/pypi/v/types-aiobotocore-route53.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53)
+[aiobotocore.Route53 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53)
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
 [types-aiobotocore-route53 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/).
 
 See how it helps to find and fix potential bugs:
 
@@ -397,19 +397,19 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53.type_defs import (
     AccountLimitTypeDef,
     ActivateKeySigningKeyRequestRequestTypeDef,
     ChangeInfoTypeDef,
-    ResponseMetadataTypeDef,
     AlarmIdentifierTypeDef,
     AliasTargetTypeDef,
     VPCTypeDef,
     CidrCollectionChangeTypeDef,
+    ChangeCidrCollectionResponseTypeDef,
     TagTypeDef,
     CidrBlockSummaryTypeDef,
     CidrCollectionTypeDef,
     CidrRoutingConfigTypeDef,
     DimensionTypeDef,
     CollectionSummaryTypeDef,
     CreateCidrCollectionRequestRequestTypeDef,
@@ -438,75 +438,83 @@
     DisableHostedZoneDNSSECRequestRequestTypeDef,
     EnableHostedZoneDNSSECRequestRequestTypeDef,
     GeoLocationDetailsTypeDef,
     GeoLocationTypeDef,
     GetAccountLimitRequestRequestTypeDef,
     GetChangeRequestRequestTypeDef,
     WaiterConfigTypeDef,
+    GetCheckerIpRangesResponseTypeDef,
     GetDNSSECRequestRequestTypeDef,
     GetGeoLocationRequestRequestTypeDef,
+    GetHealthCheckCountResponseTypeDef,
     GetHealthCheckLastFailureReasonRequestRequestTypeDef,
     GetHealthCheckRequestRequestTypeDef,
     GetHealthCheckStatusRequestRequestTypeDef,
+    GetHostedZoneCountResponseTypeDef,
     GetHostedZoneLimitRequestRequestTypeDef,
     HostedZoneLimitTypeDef,
     GetHostedZoneRequestRequestTypeDef,
     GetQueryLoggingConfigRequestRequestTypeDef,
     GetReusableDelegationSetLimitRequestRequestTypeDef,
     ReusableDelegationSetLimitTypeDef,
     GetReusableDelegationSetRequestRequestTypeDef,
+    GetTrafficPolicyInstanceCountResponseTypeDef,
     GetTrafficPolicyInstanceRequestRequestTypeDef,
     GetTrafficPolicyRequestRequestTypeDef,
     StatusReportTypeDef,
     LinkedServiceTypeDef,
     HostedZoneOwnerTypeDef,
-    PaginatorConfigTypeDef,
+    ListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
     ListCidrBlocksRequestRequestTypeDef,
+    ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef,
     ListCidrCollectionsRequestRequestTypeDef,
+    ListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
     ListCidrLocationsRequestRequestTypeDef,
     LocationSummaryTypeDef,
     ListGeoLocationsRequestRequestTypeDef,
+    ListHealthChecksRequestListHealthChecksPaginateTypeDef,
     ListHealthChecksRequestRequestTypeDef,
     ListHostedZonesByNameRequestRequestTypeDef,
     ListHostedZonesByVPCRequestRequestTypeDef,
+    ListHostedZonesRequestListHostedZonesPaginateTypeDef,
     ListHostedZonesRequestRequestTypeDef,
+    ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef,
     ListQueryLoggingConfigsRequestRequestTypeDef,
+    ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
     ListResourceRecordSetsRequestRequestTypeDef,
     ListReusableDelegationSetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListTagsForResourcesRequestRequestTypeDef,
     ListTrafficPoliciesRequestRequestTypeDef,
     TrafficPolicySummaryTypeDef,
     ListTrafficPolicyInstancesByHostedZoneRequestRequestTypeDef,
     ListTrafficPolicyInstancesByPolicyRequestRequestTypeDef,
     ListTrafficPolicyInstancesRequestRequestTypeDef,
     ListTrafficPolicyVersionsRequestRequestTypeDef,
+    ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
     ListVPCAssociationAuthorizationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ResourceRecordTypeDef,
+    ResponseMetadataTypeDef,
     TestDNSAnswerRequestRequestTypeDef,
+    TestDNSAnswerResponseTypeDef,
     UpdateHostedZoneCommentRequestRequestTypeDef,
     UpdateTrafficPolicyCommentRequestRequestTypeDef,
     UpdateTrafficPolicyInstanceRequestRequestTypeDef,
+    GetAccountLimitResponseTypeDef,
     ActivateKeySigningKeyResponseTypeDef,
     AssociateVPCWithHostedZoneResponseTypeDef,
-    ChangeCidrCollectionResponseTypeDef,
     ChangeResourceRecordSetsResponseTypeDef,
     DeactivateKeySigningKeyResponseTypeDef,
     DeleteHostedZoneResponseTypeDef,
     DeleteKeySigningKeyResponseTypeDef,
     DisableHostedZoneDNSSECResponseTypeDef,
     DisassociateVPCFromHostedZoneResponseTypeDef,
     EnableHostedZoneDNSSECResponseTypeDef,
-    GetAccountLimitResponseTypeDef,
     GetChangeResponseTypeDef,
-    GetCheckerIpRangesResponseTypeDef,
-    GetHealthCheckCountResponseTypeDef,
-    GetHostedZoneCountResponseTypeDef,
-    GetTrafficPolicyInstanceCountResponseTypeDef,
-    TestDNSAnswerResponseTypeDef,
     HealthCheckConfigTypeDef,
     UpdateHealthCheckRequestRequestTypeDef,
     AssociateVPCWithHostedZoneRequestRequestTypeDef,
     CreateVPCAssociationAuthorizationRequestRequestTypeDef,
     CreateVPCAssociationAuthorizationResponseTypeDef,
     DeleteVPCAssociationAuthorizationRequestRequestTypeDef,
     DisassociateVPCFromHostedZoneRequestRequestTypeDef,
@@ -542,22 +550,14 @@
     ListGeoLocationsResponseTypeDef,
     GetChangeRequestResourceRecordSetsChangedWaitTypeDef,
     GetHostedZoneLimitResponseTypeDef,
     GetReusableDelegationSetLimitResponseTypeDef,
     HealthCheckObservationTypeDef,
     HostedZoneTypeDef,
     HostedZoneSummaryTypeDef,
-    ListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-    ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef,
-    ListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-    ListHealthChecksRequestListHealthChecksPaginateTypeDef,
-    ListHostedZonesRequestListHostedZonesPaginateTypeDef,
-    ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef,
-    ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-    ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
     ListCidrLocationsResponseTypeDef,
     ListTrafficPoliciesResponseTypeDef,
     ResourceRecordSetTypeDef,
     CreateHealthCheckRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTagsForResourcesResponseTypeDef,
     HealthCheckTypeDef,
@@ -587,43 +587,43 @@
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/README.md` & `types-aiobotocore-route53-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-route53"></a>
 
 # types-aiobotocore-route53
 
 [![PyPI - types-aiobotocore-route53](https://img.shields.io/pypi/v/types-aiobotocore-route53.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53)
+[aiobotocore.Route53 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53)
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
 [types-aiobotocore-route53 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/).
 
 See how it helps to find and fix potential bugs:
 
@@ -364,19 +364,19 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53.type_defs import (
     AccountLimitTypeDef,
     ActivateKeySigningKeyRequestRequestTypeDef,
     ChangeInfoTypeDef,
-    ResponseMetadataTypeDef,
     AlarmIdentifierTypeDef,
     AliasTargetTypeDef,
     VPCTypeDef,
     CidrCollectionChangeTypeDef,
+    ChangeCidrCollectionResponseTypeDef,
     TagTypeDef,
     CidrBlockSummaryTypeDef,
     CidrCollectionTypeDef,
     CidrRoutingConfigTypeDef,
     DimensionTypeDef,
     CollectionSummaryTypeDef,
     CreateCidrCollectionRequestRequestTypeDef,
@@ -405,75 +405,83 @@
     DisableHostedZoneDNSSECRequestRequestTypeDef,
     EnableHostedZoneDNSSECRequestRequestTypeDef,
     GeoLocationDetailsTypeDef,
     GeoLocationTypeDef,
     GetAccountLimitRequestRequestTypeDef,
     GetChangeRequestRequestTypeDef,
     WaiterConfigTypeDef,
+    GetCheckerIpRangesResponseTypeDef,
     GetDNSSECRequestRequestTypeDef,
     GetGeoLocationRequestRequestTypeDef,
+    GetHealthCheckCountResponseTypeDef,
     GetHealthCheckLastFailureReasonRequestRequestTypeDef,
     GetHealthCheckRequestRequestTypeDef,
     GetHealthCheckStatusRequestRequestTypeDef,
+    GetHostedZoneCountResponseTypeDef,
     GetHostedZoneLimitRequestRequestTypeDef,
     HostedZoneLimitTypeDef,
     GetHostedZoneRequestRequestTypeDef,
     GetQueryLoggingConfigRequestRequestTypeDef,
     GetReusableDelegationSetLimitRequestRequestTypeDef,
     ReusableDelegationSetLimitTypeDef,
     GetReusableDelegationSetRequestRequestTypeDef,
+    GetTrafficPolicyInstanceCountResponseTypeDef,
     GetTrafficPolicyInstanceRequestRequestTypeDef,
     GetTrafficPolicyRequestRequestTypeDef,
     StatusReportTypeDef,
     LinkedServiceTypeDef,
     HostedZoneOwnerTypeDef,
-    PaginatorConfigTypeDef,
+    ListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
     ListCidrBlocksRequestRequestTypeDef,
+    ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef,
     ListCidrCollectionsRequestRequestTypeDef,
+    ListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
     ListCidrLocationsRequestRequestTypeDef,
     LocationSummaryTypeDef,
     ListGeoLocationsRequestRequestTypeDef,
+    ListHealthChecksRequestListHealthChecksPaginateTypeDef,
     ListHealthChecksRequestRequestTypeDef,
     ListHostedZonesByNameRequestRequestTypeDef,
     ListHostedZonesByVPCRequestRequestTypeDef,
+    ListHostedZonesRequestListHostedZonesPaginateTypeDef,
     ListHostedZonesRequestRequestTypeDef,
+    ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef,
     ListQueryLoggingConfigsRequestRequestTypeDef,
+    ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
     ListResourceRecordSetsRequestRequestTypeDef,
     ListReusableDelegationSetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListTagsForResourcesRequestRequestTypeDef,
     ListTrafficPoliciesRequestRequestTypeDef,
     TrafficPolicySummaryTypeDef,
     ListTrafficPolicyInstancesByHostedZoneRequestRequestTypeDef,
     ListTrafficPolicyInstancesByPolicyRequestRequestTypeDef,
     ListTrafficPolicyInstancesRequestRequestTypeDef,
     ListTrafficPolicyVersionsRequestRequestTypeDef,
+    ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
     ListVPCAssociationAuthorizationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ResourceRecordTypeDef,
+    ResponseMetadataTypeDef,
     TestDNSAnswerRequestRequestTypeDef,
+    TestDNSAnswerResponseTypeDef,
     UpdateHostedZoneCommentRequestRequestTypeDef,
     UpdateTrafficPolicyCommentRequestRequestTypeDef,
     UpdateTrafficPolicyInstanceRequestRequestTypeDef,
+    GetAccountLimitResponseTypeDef,
     ActivateKeySigningKeyResponseTypeDef,
     AssociateVPCWithHostedZoneResponseTypeDef,
-    ChangeCidrCollectionResponseTypeDef,
     ChangeResourceRecordSetsResponseTypeDef,
     DeactivateKeySigningKeyResponseTypeDef,
     DeleteHostedZoneResponseTypeDef,
     DeleteKeySigningKeyResponseTypeDef,
     DisableHostedZoneDNSSECResponseTypeDef,
     DisassociateVPCFromHostedZoneResponseTypeDef,
     EnableHostedZoneDNSSECResponseTypeDef,
-    GetAccountLimitResponseTypeDef,
     GetChangeResponseTypeDef,
-    GetCheckerIpRangesResponseTypeDef,
-    GetHealthCheckCountResponseTypeDef,
-    GetHostedZoneCountResponseTypeDef,
-    GetTrafficPolicyInstanceCountResponseTypeDef,
-    TestDNSAnswerResponseTypeDef,
     HealthCheckConfigTypeDef,
     UpdateHealthCheckRequestRequestTypeDef,
     AssociateVPCWithHostedZoneRequestRequestTypeDef,
     CreateVPCAssociationAuthorizationRequestRequestTypeDef,
     CreateVPCAssociationAuthorizationResponseTypeDef,
     DeleteVPCAssociationAuthorizationRequestRequestTypeDef,
     DisassociateVPCFromHostedZoneRequestRequestTypeDef,
@@ -509,22 +517,14 @@
     ListGeoLocationsResponseTypeDef,
     GetChangeRequestResourceRecordSetsChangedWaitTypeDef,
     GetHostedZoneLimitResponseTypeDef,
     GetReusableDelegationSetLimitResponseTypeDef,
     HealthCheckObservationTypeDef,
     HostedZoneTypeDef,
     HostedZoneSummaryTypeDef,
-    ListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-    ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef,
-    ListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-    ListHealthChecksRequestListHealthChecksPaginateTypeDef,
-    ListHostedZonesRequestListHostedZonesPaginateTypeDef,
-    ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef,
-    ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-    ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
     ListCidrLocationsResponseTypeDef,
     ListTrafficPoliciesResponseTypeDef,
     ResourceRecordSetTypeDef,
     CreateHealthCheckRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTagsForResourcesResponseTypeDef,
     HealthCheckTypeDef,
@@ -554,43 +554,43 @@
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/setup.py` & `types-aiobotocore-route53-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-route53.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-route53",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_route53"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Route53 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Route53 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/"
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/__init__.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/__init__.pyi` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/__main__.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Route53 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Route53 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53\nOther"
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/client.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/client.pyi` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/literals.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -273,14 +273,15 @@
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
@@ -359,14 +360,15 @@
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
@@ -377,14 +379,15 @@
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
@@ -420,14 +423,15 @@
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
@@ -446,16 +450,19 @@
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
@@ -539,15 +546,17 @@
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/literals.pyi` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -271,14 +271,15 @@
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
@@ -357,14 +358,15 @@
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
@@ -375,14 +377,15 @@
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
@@ -418,14 +421,15 @@
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
@@ -444,16 +448,19 @@
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
@@ -537,15 +544,17 @@
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/paginator.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_health_checks_paginator: ListHealthChecksPaginator = client.get_paginator("list_health_checks")
         list_hosted_zones_paginator: ListHostedZonesPaginator = client.get_paginator("list_hosted_zones")
         list_query_logging_configs_paginator: ListQueryLoggingConfigsPaginator = client.get_paginator("list_query_logging_configs")
         list_resource_record_sets_paginator: ListResourceRecordSetsPaginator = client.get_paginator("list_resource_record_sets")
         list_vpc_association_authorizations_paginator: ListVPCAssociationAuthorizationsPaginator = client.get_paginator("list_vpc_association_authorizations")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListCidrBlocksResponseTypeDef,
     ListCidrCollectionsResponseTypeDef,
@@ -48,161 +47,145 @@
     ListHostedZonesResponseTypeDef,
     ListQueryLoggingConfigsResponseTypeDef,
     ListResourceRecordSetsResponseTypeDef,
     ListVPCAssociationAuthorizationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListCidrBlocksPaginator",
     "ListCidrCollectionsPaginator",
     "ListCidrLocationsPaginator",
     "ListHealthChecksPaginator",
     "ListHostedZonesPaginator",
     "ListQueryLoggingConfigsPaginator",
     "ListResourceRecordSetsPaginator",
     "ListVPCAssociationAuthorizationsPaginator",
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
 class ListCidrBlocksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrBlocks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrblockspaginator)
     """
 
     def paginate(
         self,
         *,
         CollectionId: str,
         LocationName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCidrBlocksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrBlocks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrblockspaginator)
         """
 
-
 class ListCidrCollectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrCollections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrcollectionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCidrCollectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrCollections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrcollectionspaginator)
         """
 
-
 class ListCidrLocationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrLocations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrlocationspaginator)
     """
 
     def paginate(
-        self, *, CollectionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CollectionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCidrLocationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrLocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrlocationspaginator)
         """
 
-
 class ListHealthChecksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHealthChecks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhealthcheckspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHealthChecksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHealthChecks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhealthcheckspaginator)
         """
 
-
 class ListHostedZonesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHostedZones)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhostedzonespaginator)
     """
 
     def paginate(
-        self, *, DelegationSetId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DelegationSetId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHostedZonesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHostedZones.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhostedzonespaginator)
         """
 
-
 class ListQueryLoggingConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListQueryLoggingConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listqueryloggingconfigspaginator)
     """
 
     def paginate(
-        self, *, HostedZoneId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, HostedZoneId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueryLoggingConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListQueryLoggingConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listqueryloggingconfigspaginator)
         """
 
-
 class ListResourceRecordSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListResourceRecordSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listresourcerecordsetspaginator)
     """
 
     def paginate(
-        self, *, HostedZoneId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, HostedZoneId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceRecordSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListResourceRecordSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listresourcerecordsetspaginator)
         """
 
-
 class ListVPCAssociationAuthorizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListVPCAssociationAuthorizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listvpcassociationauthorizationspaginator)
     """
 
     def paginate(
         self,
         *,
         HostedZoneId: str,
         MaxResults: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVPCAssociationAuthorizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListVPCAssociationAuthorizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listvpcassociationauthorizationspaginator)
         """
```

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/paginator.pyi` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_health_checks_paginator: ListHealthChecksPaginator = client.get_paginator("list_health_checks")
         list_hosted_zones_paginator: ListHostedZonesPaginator = client.get_paginator("list_hosted_zones")
         list_query_logging_configs_paginator: ListQueryLoggingConfigsPaginator = client.get_paginator("list_query_logging_configs")
         list_resource_record_sets_paginator: ListResourceRecordSetsPaginator = client.get_paginator("list_resource_record_sets")
         list_vpc_association_authorizations_paginator: ListVPCAssociationAuthorizationsPaginator = client.get_paginator("list_vpc_association_authorizations")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListCidrBlocksResponseTypeDef,
     ListCidrCollectionsResponseTypeDef,
@@ -48,150 +47,155 @@
     ListHostedZonesResponseTypeDef,
     ListQueryLoggingConfigsResponseTypeDef,
     ListResourceRecordSetsResponseTypeDef,
     ListVPCAssociationAuthorizationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListCidrBlocksPaginator",
     "ListCidrCollectionsPaginator",
     "ListCidrLocationsPaginator",
     "ListHealthChecksPaginator",
     "ListHostedZonesPaginator",
     "ListQueryLoggingConfigsPaginator",
     "ListResourceRecordSetsPaginator",
     "ListVPCAssociationAuthorizationsPaginator",
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
 class ListCidrBlocksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrBlocks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrblockspaginator)
     """
 
     def paginate(
         self,
         *,
         CollectionId: str,
         LocationName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCidrBlocksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrBlocks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrblockspaginator)
         """
 
+
 class ListCidrCollectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrCollections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrcollectionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCidrCollectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrCollections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrcollectionspaginator)
         """
 
+
 class ListCidrLocationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrLocations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrlocationspaginator)
     """
 
     def paginate(
-        self, *, CollectionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CollectionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCidrLocationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListCidrLocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listcidrlocationspaginator)
         """
 
+
 class ListHealthChecksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHealthChecks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhealthcheckspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHealthChecksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHealthChecks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhealthcheckspaginator)
         """
 
+
 class ListHostedZonesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHostedZones)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhostedzonespaginator)
     """
 
     def paginate(
-        self, *, DelegationSetId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DelegationSetId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHostedZonesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListHostedZones.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listhostedzonespaginator)
         """
 
+
 class ListQueryLoggingConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListQueryLoggingConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listqueryloggingconfigspaginator)
     """
 
     def paginate(
-        self, *, HostedZoneId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, HostedZoneId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueryLoggingConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListQueryLoggingConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listqueryloggingconfigspaginator)
         """
 
+
 class ListResourceRecordSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListResourceRecordSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listresourcerecordsetspaginator)
     """
 
     def paginate(
-        self, *, HostedZoneId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, HostedZoneId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceRecordSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListResourceRecordSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listresourcerecordsetspaginator)
         """
 
+
 class ListVPCAssociationAuthorizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListVPCAssociationAuthorizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listvpcassociationauthorizationspaginator)
     """
 
     def paginate(
         self,
         *,
         HostedZoneId: str,
         MaxResults: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVPCAssociationAuthorizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53.Paginator.ListVPCAssociationAuthorizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/paginators/#listvpcassociationauthorizationspaginator)
         """
```

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/type_defs.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -45,19 +45,19 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountLimitTypeDef",
     "ActivateKeySigningKeyRequestRequestTypeDef",
     "ChangeInfoTypeDef",
-    "ResponseMetadataTypeDef",
     "AlarmIdentifierTypeDef",
     "AliasTargetTypeDef",
     "VPCTypeDef",
     "CidrCollectionChangeTypeDef",
+    "ChangeCidrCollectionResponseTypeDef",
     "TagTypeDef",
     "CidrBlockSummaryTypeDef",
     "CidrCollectionTypeDef",
     "CidrRoutingConfigTypeDef",
     "DimensionTypeDef",
     "CollectionSummaryTypeDef",
     "CreateCidrCollectionRequestRequestTypeDef",
@@ -86,75 +86,83 @@
     "DisableHostedZoneDNSSECRequestRequestTypeDef",
     "EnableHostedZoneDNSSECRequestRequestTypeDef",
     "GeoLocationDetailsTypeDef",
     "GeoLocationTypeDef",
     "GetAccountLimitRequestRequestTypeDef",
     "GetChangeRequestRequestTypeDef",
     "WaiterConfigTypeDef",
+    "GetCheckerIpRangesResponseTypeDef",
     "GetDNSSECRequestRequestTypeDef",
     "GetGeoLocationRequestRequestTypeDef",
+    "GetHealthCheckCountResponseTypeDef",
     "GetHealthCheckLastFailureReasonRequestRequestTypeDef",
     "GetHealthCheckRequestRequestTypeDef",
     "GetHealthCheckStatusRequestRequestTypeDef",
+    "GetHostedZoneCountResponseTypeDef",
     "GetHostedZoneLimitRequestRequestTypeDef",
     "HostedZoneLimitTypeDef",
     "GetHostedZoneRequestRequestTypeDef",
     "GetQueryLoggingConfigRequestRequestTypeDef",
     "GetReusableDelegationSetLimitRequestRequestTypeDef",
     "ReusableDelegationSetLimitTypeDef",
     "GetReusableDelegationSetRequestRequestTypeDef",
+    "GetTrafficPolicyInstanceCountResponseTypeDef",
     "GetTrafficPolicyInstanceRequestRequestTypeDef",
     "GetTrafficPolicyRequestRequestTypeDef",
     "StatusReportTypeDef",
     "LinkedServiceTypeDef",
     "HostedZoneOwnerTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
     "ListCidrBlocksRequestRequestTypeDef",
+    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
     "ListCidrCollectionsRequestRequestTypeDef",
+    "ListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
     "ListCidrLocationsRequestRequestTypeDef",
     "LocationSummaryTypeDef",
     "ListGeoLocationsRequestRequestTypeDef",
+    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
     "ListHealthChecksRequestRequestTypeDef",
     "ListHostedZonesByNameRequestRequestTypeDef",
     "ListHostedZonesByVPCRequestRequestTypeDef",
+    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
     "ListHostedZonesRequestRequestTypeDef",
+    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
     "ListQueryLoggingConfigsRequestRequestTypeDef",
+    "ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
     "ListResourceRecordSetsRequestRequestTypeDef",
     "ListReusableDelegationSetsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListTagsForResourcesRequestRequestTypeDef",
     "ListTrafficPoliciesRequestRequestTypeDef",
     "TrafficPolicySummaryTypeDef",
     "ListTrafficPolicyInstancesByHostedZoneRequestRequestTypeDef",
     "ListTrafficPolicyInstancesByPolicyRequestRequestTypeDef",
     "ListTrafficPolicyInstancesRequestRequestTypeDef",
     "ListTrafficPolicyVersionsRequestRequestTypeDef",
+    "ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
     "ListVPCAssociationAuthorizationsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourceRecordTypeDef",
+    "ResponseMetadataTypeDef",
     "TestDNSAnswerRequestRequestTypeDef",
+    "TestDNSAnswerResponseTypeDef",
     "UpdateHostedZoneCommentRequestRequestTypeDef",
     "UpdateTrafficPolicyCommentRequestRequestTypeDef",
     "UpdateTrafficPolicyInstanceRequestRequestTypeDef",
+    "GetAccountLimitResponseTypeDef",
     "ActivateKeySigningKeyResponseTypeDef",
     "AssociateVPCWithHostedZoneResponseTypeDef",
-    "ChangeCidrCollectionResponseTypeDef",
     "ChangeResourceRecordSetsResponseTypeDef",
     "DeactivateKeySigningKeyResponseTypeDef",
     "DeleteHostedZoneResponseTypeDef",
     "DeleteKeySigningKeyResponseTypeDef",
     "DisableHostedZoneDNSSECResponseTypeDef",
     "DisassociateVPCFromHostedZoneResponseTypeDef",
     "EnableHostedZoneDNSSECResponseTypeDef",
-    "GetAccountLimitResponseTypeDef",
     "GetChangeResponseTypeDef",
-    "GetCheckerIpRangesResponseTypeDef",
-    "GetHealthCheckCountResponseTypeDef",
-    "GetHostedZoneCountResponseTypeDef",
-    "GetTrafficPolicyInstanceCountResponseTypeDef",
-    "TestDNSAnswerResponseTypeDef",
     "HealthCheckConfigTypeDef",
     "UpdateHealthCheckRequestRequestTypeDef",
     "AssociateVPCWithHostedZoneRequestRequestTypeDef",
     "CreateVPCAssociationAuthorizationRequestRequestTypeDef",
     "CreateVPCAssociationAuthorizationResponseTypeDef",
     "DeleteVPCAssociationAuthorizationRequestRequestTypeDef",
     "DisassociateVPCFromHostedZoneRequestRequestTypeDef",
@@ -190,22 +198,14 @@
     "ListGeoLocationsResponseTypeDef",
     "GetChangeRequestResourceRecordSetsChangedWaitTypeDef",
     "GetHostedZoneLimitResponseTypeDef",
     "GetReusableDelegationSetLimitResponseTypeDef",
     "HealthCheckObservationTypeDef",
     "HostedZoneTypeDef",
     "HostedZoneSummaryTypeDef",
-    "ListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
-    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
-    "ListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
-    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
-    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
-    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
-    "ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
-    "ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
     "ListCidrLocationsResponseTypeDef",
     "ListTrafficPoliciesResponseTypeDef",
     "ResourceRecordSetTypeDef",
     "CreateHealthCheckRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "ListTagsForResourcesResponseTypeDef",
     "HealthCheckTypeDef",
@@ -260,25 +260,14 @@
 )
 
 
 class ChangeInfoTypeDef(_RequiredChangeInfoTypeDef, _OptionalChangeInfoTypeDef):
     pass
 
 
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
 AlarmIdentifierTypeDef = TypedDict(
     "AlarmIdentifierTypeDef",
     {
         "Region": CloudWatchRegionType,
         "Name": str,
     },
 )
@@ -306,14 +295,22 @@
     {
         "LocationName": str,
         "Action": CidrCollectionChangeActionType,
         "CidrList": Sequence[str],
     },
 )
 
+ChangeCidrCollectionResponseTypeDef = TypedDict(
+    "ChangeCidrCollectionResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
@@ -702,14 +699,22 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+GetCheckerIpRangesResponseTypeDef = TypedDict(
+    "GetCheckerIpRangesResponseTypeDef",
+    {
+        "CheckerIpRanges": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDNSSECRequestRequestTypeDef = TypedDict(
     "GetDNSSECRequestRequestTypeDef",
     {
         "HostedZoneId": str,
     },
 )
 
@@ -719,14 +724,22 @@
         "ContinentCode": str,
         "CountryCode": str,
         "SubdivisionCode": str,
     },
     total=False,
 )
 
+GetHealthCheckCountResponseTypeDef = TypedDict(
+    "GetHealthCheckCountResponseTypeDef",
+    {
+        "HealthCheckCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHealthCheckLastFailureReasonRequestRequestTypeDef = TypedDict(
     "GetHealthCheckLastFailureReasonRequestRequestTypeDef",
     {
         "HealthCheckId": str,
     },
 )
 
@@ -740,14 +753,22 @@
 GetHealthCheckStatusRequestRequestTypeDef = TypedDict(
     "GetHealthCheckStatusRequestRequestTypeDef",
     {
         "HealthCheckId": str,
     },
 )
 
+GetHostedZoneCountResponseTypeDef = TypedDict(
+    "GetHostedZoneCountResponseTypeDef",
+    {
+        "HostedZoneCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHostedZoneLimitRequestRequestTypeDef = TypedDict(
     "GetHostedZoneLimitRequestRequestTypeDef",
     {
         "Type": HostedZoneLimitTypeType,
         "HostedZoneId": str,
     },
 )
@@ -793,14 +814,22 @@
 GetReusableDelegationSetRequestRequestTypeDef = TypedDict(
     "GetReusableDelegationSetRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+GetTrafficPolicyInstanceCountResponseTypeDef = TypedDict(
+    "GetTrafficPolicyInstanceCountResponseTypeDef",
+    {
+        "TrafficPolicyInstanceCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTrafficPolicyInstanceRequestRequestTypeDef = TypedDict(
     "GetTrafficPolicyInstanceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -835,24 +864,37 @@
     {
         "OwningAccount": str,
         "OwningService": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
+    "_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CollectionId": str,
+    },
+)
+_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
+    "_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
+    {
+        "LocationName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListCidrBlocksRequestListCidrBlocksPaginateTypeDef(
+    _RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
+    _OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCidrBlocksRequestRequestTypeDef = TypedDict(
     "_RequiredListCidrBlocksRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 _OptionalListCidrBlocksRequestRequestTypeDef = TypedDict(
@@ -868,23 +910,53 @@
 
 class ListCidrBlocksRequestRequestTypeDef(
     _RequiredListCidrBlocksRequestRequestTypeDef, _OptionalListCidrBlocksRequestRequestTypeDef
 ):
     pass
 
 
+ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef = TypedDict(
+    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCidrCollectionsRequestRequestTypeDef = TypedDict(
     "ListCidrCollectionsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": str,
     },
     total=False,
 )
 
+_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
+    "_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
+    "_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCidrLocationsRequestListCidrLocationsPaginateTypeDef(
+    _RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
+    _OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCidrLocationsRequestRequestTypeDef = TypedDict(
     "_RequiredListCidrLocationsRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 _OptionalListCidrLocationsRequestRequestTypeDef = TypedDict(
@@ -918,14 +990,22 @@
         "StartCountryCode": str,
         "StartSubdivisionCode": str,
         "MaxItems": str,
     },
     total=False,
 )
 
+ListHealthChecksRequestListHealthChecksPaginateTypeDef = TypedDict(
+    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHealthChecksRequestRequestTypeDef = TypedDict(
     "ListHealthChecksRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
@@ -961,34 +1041,74 @@
 class ListHostedZonesByVPCRequestRequestTypeDef(
     _RequiredListHostedZonesByVPCRequestRequestTypeDef,
     _OptionalListHostedZonesByVPCRequestRequestTypeDef,
 ):
     pass
 
 
+ListHostedZonesRequestListHostedZonesPaginateTypeDef = TypedDict(
+    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
+    {
+        "DelegationSetId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHostedZonesRequestRequestTypeDef = TypedDict(
     "ListHostedZonesRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
         "DelegationSetId": str,
     },
     total=False,
 )
 
+ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef = TypedDict(
+    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
+    {
+        "HostedZoneId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueryLoggingConfigsRequestRequestTypeDef = TypedDict(
     "ListQueryLoggingConfigsRequestRequestTypeDef",
     {
         "HostedZoneId": str,
         "NextToken": str,
         "MaxResults": str,
     },
     total=False,
 )
 
+_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
+    "_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
+    {
+        "HostedZoneId": str,
+    },
+)
+_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
+    "_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef(
+    _RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
+    _OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourceRecordSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceRecordSetsRequestRequestTypeDef",
     {
         "HostedZoneId": str,
     },
 )
 _OptionalListResourceRecordSetsRequestRequestTypeDef = TypedDict(
@@ -1135,14 +1255,37 @@
 class ListTrafficPolicyVersionsRequestRequestTypeDef(
     _RequiredListTrafficPolicyVersionsRequestRequestTypeDef,
     _OptionalListTrafficPolicyVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
+    "_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
+    {
+        "HostedZoneId": str,
+    },
+)
+_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
+    "_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
+    {
+        "MaxResults": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef(
+    _RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
+    _OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVPCAssociationAuthorizationsRequestRequestTypeDef = TypedDict(
     "_RequiredListVPCAssociationAuthorizationsRequestRequestTypeDef",
     {
         "HostedZoneId": str,
     },
 )
 _OptionalListVPCAssociationAuthorizationsRequestRequestTypeDef = TypedDict(
@@ -1158,21 +1301,42 @@
 class ListVPCAssociationAuthorizationsRequestRequestTypeDef(
     _RequiredListVPCAssociationAuthorizationsRequestRequestTypeDef,
     _OptionalListVPCAssociationAuthorizationsRequestRequestTypeDef,
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
 ResourceRecordTypeDef = TypedDict(
     "ResourceRecordTypeDef",
     {
         "Value": str,
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
 _RequiredTestDNSAnswerRequestRequestTypeDef = TypedDict(
     "_RequiredTestDNSAnswerRequestRequestTypeDef",
     {
         "HostedZoneId": str,
         "RecordName": str,
         "RecordType": RRTypeType,
     },
@@ -1190,14 +1354,27 @@
 
 class TestDNSAnswerRequestRequestTypeDef(
     _RequiredTestDNSAnswerRequestRequestTypeDef, _OptionalTestDNSAnswerRequestRequestTypeDef
 ):
     pass
 
 
+TestDNSAnswerResponseTypeDef = TypedDict(
+    "TestDNSAnswerResponseTypeDef",
+    {
+        "Nameserver": str,
+        "RecordName": str,
+        "RecordType": RRTypeType,
+        "RecordData": List[str],
+        "ResponseCode": str,
+        "Protocol": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateHostedZoneCommentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateHostedZoneCommentRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateHostedZoneCommentRequestRequestTypeDef = TypedDict(
@@ -1231,153 +1408,100 @@
         "Id": str,
         "TTL": int,
         "TrafficPolicyId": str,
         "TrafficPolicyVersion": int,
     },
 )
 
+GetAccountLimitResponseTypeDef = TypedDict(
+    "GetAccountLimitResponseTypeDef",
+    {
+        "Limit": AccountLimitTypeDef,
+        "Count": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActivateKeySigningKeyResponseTypeDef = TypedDict(
     "ActivateKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateVPCWithHostedZoneResponseTypeDef = TypedDict(
     "AssociateVPCWithHostedZoneResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ChangeCidrCollectionResponseTypeDef = TypedDict(
-    "ChangeCidrCollectionResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeResourceRecordSetsResponseTypeDef = TypedDict(
     "ChangeResourceRecordSetsResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeactivateKeySigningKeyResponseTypeDef = TypedDict(
     "DeactivateKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteHostedZoneResponseTypeDef = TypedDict(
     "DeleteHostedZoneResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteKeySigningKeyResponseTypeDef = TypedDict(
     "DeleteKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisableHostedZoneDNSSECResponseTypeDef = TypedDict(
     "DisableHostedZoneDNSSECResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateVPCFromHostedZoneResponseTypeDef = TypedDict(
     "DisassociateVPCFromHostedZoneResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableHostedZoneDNSSECResponseTypeDef = TypedDict(
     "EnableHostedZoneDNSSECResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountLimitResponseTypeDef = TypedDict(
-    "GetAccountLimitResponseTypeDef",
-    {
-        "Limit": AccountLimitTypeDef,
-        "Count": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChangeResponseTypeDef = TypedDict(
     "GetChangeResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCheckerIpRangesResponseTypeDef = TypedDict(
-    "GetCheckerIpRangesResponseTypeDef",
-    {
-        "CheckerIpRanges": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetHealthCheckCountResponseTypeDef = TypedDict(
-    "GetHealthCheckCountResponseTypeDef",
-    {
-        "HealthCheckCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetHostedZoneCountResponseTypeDef = TypedDict(
-    "GetHostedZoneCountResponseTypeDef",
-    {
-        "HostedZoneCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTrafficPolicyInstanceCountResponseTypeDef = TypedDict(
-    "GetTrafficPolicyInstanceCountResponseTypeDef",
-    {
-        "TrafficPolicyInstanceCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestDNSAnswerResponseTypeDef = TypedDict(
-    "TestDNSAnswerResponseTypeDef",
-    {
-        "Nameserver": str,
-        "RecordName": str,
-        "RecordType": RRTypeType,
-        "RecordData": List[str],
-        "ResponseCode": str,
-        "Protocol": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHealthCheckConfigTypeDef = TypedDict(
     "_RequiredHealthCheckConfigTypeDef",
     {
         "Type": HealthCheckTypeType,
@@ -1482,15 +1606,15 @@
 )
 
 CreateVPCAssociationAuthorizationResponseTypeDef = TypedDict(
     "CreateVPCAssociationAuthorizationResponseTypeDef",
     {
         "HostedZoneId": str,
         "VPC": VPCTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVPCAssociationAuthorizationRequestRequestTypeDef = TypedDict(
     "DeleteVPCAssociationAuthorizationRequestRequestTypeDef",
     {
         "HostedZoneId": str,
@@ -1523,15 +1647,15 @@
 
 ListVPCAssociationAuthorizationsResponseTypeDef = TypedDict(
     "ListVPCAssociationAuthorizationsResponseTypeDef",
     {
         "HostedZoneId": str,
         "NextToken": str,
         "VPCs": List[VPCTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredChangeCidrCollectionRequestRequestTypeDef = TypedDict(
     "_RequiredChangeCidrCollectionRequestRequestTypeDef",
     {
         "Id": str,
@@ -1589,24 +1713,24 @@
 )
 
 ListCidrBlocksResponseTypeDef = TypedDict(
     "ListCidrBlocksResponseTypeDef",
     {
         "NextToken": str,
         "CidrBlocks": List[CidrBlockSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCidrCollectionResponseTypeDef = TypedDict(
     "CreateCidrCollectionResponseTypeDef",
     {
         "Collection": CidrCollectionTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCloudWatchAlarmConfigurationTypeDef = TypedDict(
     "_RequiredCloudWatchAlarmConfigurationTypeDef",
     {
         "EvaluationPeriods": int,
@@ -1634,15 +1758,15 @@
 
 
 ListCidrCollectionsResponseTypeDef = TypedDict(
     "ListCidrCollectionsResponseTypeDef",
     {
         "NextToken": str,
         "CidrCollections": List[CollectionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateHostedZoneRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHostedZoneRequestRequestTypeDef",
     {
         "Name": str,
@@ -1667,209 +1791,209 @@
 
 
 CreateReusableDelegationSetResponseTypeDef = TypedDict(
     "CreateReusableDelegationSetResponseTypeDef",
     {
         "DelegationSet": DelegationSetTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReusableDelegationSetResponseTypeDef = TypedDict(
     "GetReusableDelegationSetResponseTypeDef",
     {
         "DelegationSet": DelegationSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReusableDelegationSetsResponseTypeDef = TypedDict(
     "ListReusableDelegationSetsResponseTypeDef",
     {
         "DelegationSets": List[DelegationSetTypeDef],
         "Marker": str,
         "IsTruncated": bool,
         "NextMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateKeySigningKeyResponseTypeDef = TypedDict(
     "CreateKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
         "KeySigningKey": KeySigningKeyTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateQueryLoggingConfigResponseTypeDef = TypedDict(
     "CreateQueryLoggingConfigResponseTypeDef",
     {
         "QueryLoggingConfig": QueryLoggingConfigTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueryLoggingConfigResponseTypeDef = TypedDict(
     "GetQueryLoggingConfigResponseTypeDef",
     {
         "QueryLoggingConfig": QueryLoggingConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQueryLoggingConfigsResponseTypeDef = TypedDict(
     "ListQueryLoggingConfigsResponseTypeDef",
     {
         "QueryLoggingConfigs": List[QueryLoggingConfigTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTrafficPolicyInstanceResponseTypeDef = TypedDict(
     "CreateTrafficPolicyInstanceResponseTypeDef",
     {
         "TrafficPolicyInstance": TrafficPolicyInstanceTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrafficPolicyInstanceResponseTypeDef = TypedDict(
     "GetTrafficPolicyInstanceResponseTypeDef",
     {
         "TrafficPolicyInstance": TrafficPolicyInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyInstancesByHostedZoneResponseTypeDef = TypedDict(
     "ListTrafficPolicyInstancesByHostedZoneResponseTypeDef",
     {
         "TrafficPolicyInstances": List[TrafficPolicyInstanceTypeDef],
         "TrafficPolicyInstanceNameMarker": str,
         "TrafficPolicyInstanceTypeMarker": RRTypeType,
         "IsTruncated": bool,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyInstancesByPolicyResponseTypeDef = TypedDict(
     "ListTrafficPolicyInstancesByPolicyResponseTypeDef",
     {
         "TrafficPolicyInstances": List[TrafficPolicyInstanceTypeDef],
         "HostedZoneIdMarker": str,
         "TrafficPolicyInstanceNameMarker": str,
         "TrafficPolicyInstanceTypeMarker": RRTypeType,
         "IsTruncated": bool,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyInstancesResponseTypeDef = TypedDict(
     "ListTrafficPolicyInstancesResponseTypeDef",
     {
         "TrafficPolicyInstances": List[TrafficPolicyInstanceTypeDef],
         "HostedZoneIdMarker": str,
         "TrafficPolicyInstanceNameMarker": str,
         "TrafficPolicyInstanceTypeMarker": RRTypeType,
         "IsTruncated": bool,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTrafficPolicyInstanceResponseTypeDef = TypedDict(
     "UpdateTrafficPolicyInstanceResponseTypeDef",
     {
         "TrafficPolicyInstance": TrafficPolicyInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTrafficPolicyResponseTypeDef = TypedDict(
     "CreateTrafficPolicyResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTrafficPolicyVersionResponseTypeDef = TypedDict(
     "CreateTrafficPolicyVersionResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrafficPolicyResponseTypeDef = TypedDict(
     "GetTrafficPolicyResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyVersionsResponseTypeDef = TypedDict(
     "ListTrafficPolicyVersionsResponseTypeDef",
     {
         "TrafficPolicies": List[TrafficPolicyTypeDef],
         "IsTruncated": bool,
         "TrafficPolicyVersionMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTrafficPolicyCommentResponseTypeDef = TypedDict(
     "UpdateTrafficPolicyCommentResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDNSSECResponseTypeDef = TypedDict(
     "GetDNSSECResponseTypeDef",
     {
         "Status": DNSSECStatusTypeDef,
         "KeySigningKeys": List[KeySigningKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGeoLocationResponseTypeDef = TypedDict(
     "GetGeoLocationResponseTypeDef",
     {
         "GeoLocationDetails": GeoLocationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGeoLocationsResponseTypeDef = TypedDict(
     "ListGeoLocationsResponseTypeDef",
     {
         "GeoLocationDetailsList": List[GeoLocationDetailsTypeDef],
         "IsTruncated": bool,
         "NextContinentCode": str,
         "NextCountryCode": str,
         "NextSubdivisionCode": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetChangeRequestResourceRecordSetsChangedWaitTypeDef = TypedDict(
     "_RequiredGetChangeRequestResourceRecordSetsChangedWaitTypeDef",
     {
         "Id": str,
@@ -1892,24 +2016,24 @@
 
 
 GetHostedZoneLimitResponseTypeDef = TypedDict(
     "GetHostedZoneLimitResponseTypeDef",
     {
         "Limit": HostedZoneLimitTypeDef,
         "Count": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReusableDelegationSetLimitResponseTypeDef = TypedDict(
     "GetReusableDelegationSetLimitResponseTypeDef",
     {
         "Limit": ReusableDelegationSetLimitTypeDef,
         "Count": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HealthCheckObservationTypeDef = TypedDict(
     "HealthCheckObservationTypeDef",
     {
         "Region": HealthCheckRegionType,
@@ -1947,155 +2071,31 @@
     {
         "HostedZoneId": str,
         "Name": str,
         "Owner": HostedZoneOwnerTypeDef,
     },
 )
 
-_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
-    "_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
-    {
-        "CollectionId": str,
-    },
-)
-_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
-    "_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
-    {
-        "LocationName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCidrBlocksRequestListCidrBlocksPaginateTypeDef(
-    _RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-    _OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-):
-    pass
-
-
-ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef = TypedDict(
-    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
-    "_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
-    {
-        "CollectionId": str,
-    },
-)
-_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
-    "_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCidrLocationsRequestListCidrLocationsPaginateTypeDef(
-    _RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-    _OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-):
-    pass
-
-
-ListHealthChecksRequestListHealthChecksPaginateTypeDef = TypedDict(
-    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHostedZonesRequestListHostedZonesPaginateTypeDef = TypedDict(
-    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
-    {
-        "DelegationSetId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef = TypedDict(
-    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
-    {
-        "HostedZoneId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
-    "_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
-    {
-        "HostedZoneId": str,
-    },
-)
-_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
-    "_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef(
-    _RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-    _OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
-    "_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
-    {
-        "HostedZoneId": str,
-    },
-)
-_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
-    "_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
-    {
-        "MaxResults": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef(
-    _RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
-    _OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
-):
-    pass
-
-
 ListCidrLocationsResponseTypeDef = TypedDict(
     "ListCidrLocationsResponseTypeDef",
     {
         "NextToken": str,
         "CidrLocations": List[LocationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPoliciesResponseTypeDef = TypedDict(
     "ListTrafficPoliciesResponseTypeDef",
     {
         "TrafficPolicySummaries": List[TrafficPolicySummaryTypeDef],
         "IsTruncated": bool,
         "TrafficPolicyIdMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResourceRecordSetTypeDef = TypedDict(
     "_RequiredResourceRecordSetTypeDef",
     {
         "Name": str,
@@ -2136,23 +2136,23 @@
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceTagSet": ResourceTagSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourcesResponseTypeDef = TypedDict(
     "ListTagsForResourcesResponseTypeDef",
     {
         "ResourceTagSets": List[ResourceTagSetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHealthCheckTypeDef = TypedDict(
     "_RequiredHealthCheckTypeDef",
     {
         "Id": str,
@@ -2175,89 +2175,89 @@
     pass
 
 
 GetHealthCheckLastFailureReasonResponseTypeDef = TypedDict(
     "GetHealthCheckLastFailureReasonResponseTypeDef",
     {
         "HealthCheckObservations": List[HealthCheckObservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHealthCheckStatusResponseTypeDef = TypedDict(
     "GetHealthCheckStatusResponseTypeDef",
     {
         "HealthCheckObservations": List[HealthCheckObservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHostedZoneResponseTypeDef = TypedDict(
     "CreateHostedZoneResponseTypeDef",
     {
         "HostedZone": HostedZoneTypeDef,
         "ChangeInfo": ChangeInfoTypeDef,
         "DelegationSet": DelegationSetTypeDef,
         "VPC": VPCTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHostedZoneResponseTypeDef = TypedDict(
     "GetHostedZoneResponseTypeDef",
     {
         "HostedZone": HostedZoneTypeDef,
         "DelegationSet": DelegationSetTypeDef,
         "VPCs": List[VPCTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostedZonesByNameResponseTypeDef = TypedDict(
     "ListHostedZonesByNameResponseTypeDef",
     {
         "HostedZones": List[HostedZoneTypeDef],
         "DNSName": str,
         "HostedZoneId": str,
         "IsTruncated": bool,
         "NextDNSName": str,
         "NextHostedZoneId": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostedZonesResponseTypeDef = TypedDict(
     "ListHostedZonesResponseTypeDef",
     {
         "HostedZones": List[HostedZoneTypeDef],
         "Marker": str,
         "IsTruncated": bool,
         "NextMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateHostedZoneCommentResponseTypeDef = TypedDict(
     "UpdateHostedZoneCommentResponseTypeDef",
     {
         "HostedZone": HostedZoneTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostedZonesByVPCResponseTypeDef = TypedDict(
     "ListHostedZonesByVPCResponseTypeDef",
     {
         "HostedZoneSummaries": List[HostedZoneSummaryTypeDef],
         "MaxItems": str,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeTypeDef = TypedDict(
     "ChangeTypeDef",
     {
         "Action": ChangeActionType,
@@ -2270,52 +2270,52 @@
     {
         "ResourceRecordSets": List[ResourceRecordSetTypeDef],
         "IsTruncated": bool,
         "NextRecordName": str,
         "NextRecordType": RRTypeType,
         "NextRecordIdentifier": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHealthCheckResponseTypeDef = TypedDict(
     "CreateHealthCheckResponseTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHealthCheckResponseTypeDef = TypedDict(
     "GetHealthCheckResponseTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHealthChecksResponseTypeDef = TypedDict(
     "ListHealthChecksResponseTypeDef",
     {
         "HealthChecks": List[HealthCheckTypeDef],
         "Marker": str,
         "IsTruncated": bool,
         "NextMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateHealthCheckResponseTypeDef = TypedDict(
     "UpdateHealthCheckResponseTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredChangeBatchTypeDef = TypedDict(
     "_RequiredChangeBatchTypeDef",
     {
         "Changes": Sequence[ChangeTypeDef],
```

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/type_defs.pyi` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -44,19 +44,19 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountLimitTypeDef",
     "ActivateKeySigningKeyRequestRequestTypeDef",
     "ChangeInfoTypeDef",
-    "ResponseMetadataTypeDef",
     "AlarmIdentifierTypeDef",
     "AliasTargetTypeDef",
     "VPCTypeDef",
     "CidrCollectionChangeTypeDef",
+    "ChangeCidrCollectionResponseTypeDef",
     "TagTypeDef",
     "CidrBlockSummaryTypeDef",
     "CidrCollectionTypeDef",
     "CidrRoutingConfigTypeDef",
     "DimensionTypeDef",
     "CollectionSummaryTypeDef",
     "CreateCidrCollectionRequestRequestTypeDef",
@@ -85,75 +85,83 @@
     "DisableHostedZoneDNSSECRequestRequestTypeDef",
     "EnableHostedZoneDNSSECRequestRequestTypeDef",
     "GeoLocationDetailsTypeDef",
     "GeoLocationTypeDef",
     "GetAccountLimitRequestRequestTypeDef",
     "GetChangeRequestRequestTypeDef",
     "WaiterConfigTypeDef",
+    "GetCheckerIpRangesResponseTypeDef",
     "GetDNSSECRequestRequestTypeDef",
     "GetGeoLocationRequestRequestTypeDef",
+    "GetHealthCheckCountResponseTypeDef",
     "GetHealthCheckLastFailureReasonRequestRequestTypeDef",
     "GetHealthCheckRequestRequestTypeDef",
     "GetHealthCheckStatusRequestRequestTypeDef",
+    "GetHostedZoneCountResponseTypeDef",
     "GetHostedZoneLimitRequestRequestTypeDef",
     "HostedZoneLimitTypeDef",
     "GetHostedZoneRequestRequestTypeDef",
     "GetQueryLoggingConfigRequestRequestTypeDef",
     "GetReusableDelegationSetLimitRequestRequestTypeDef",
     "ReusableDelegationSetLimitTypeDef",
     "GetReusableDelegationSetRequestRequestTypeDef",
+    "GetTrafficPolicyInstanceCountResponseTypeDef",
     "GetTrafficPolicyInstanceRequestRequestTypeDef",
     "GetTrafficPolicyRequestRequestTypeDef",
     "StatusReportTypeDef",
     "LinkedServiceTypeDef",
     "HostedZoneOwnerTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
     "ListCidrBlocksRequestRequestTypeDef",
+    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
     "ListCidrCollectionsRequestRequestTypeDef",
+    "ListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
     "ListCidrLocationsRequestRequestTypeDef",
     "LocationSummaryTypeDef",
     "ListGeoLocationsRequestRequestTypeDef",
+    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
     "ListHealthChecksRequestRequestTypeDef",
     "ListHostedZonesByNameRequestRequestTypeDef",
     "ListHostedZonesByVPCRequestRequestTypeDef",
+    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
     "ListHostedZonesRequestRequestTypeDef",
+    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
     "ListQueryLoggingConfigsRequestRequestTypeDef",
+    "ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
     "ListResourceRecordSetsRequestRequestTypeDef",
     "ListReusableDelegationSetsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListTagsForResourcesRequestRequestTypeDef",
     "ListTrafficPoliciesRequestRequestTypeDef",
     "TrafficPolicySummaryTypeDef",
     "ListTrafficPolicyInstancesByHostedZoneRequestRequestTypeDef",
     "ListTrafficPolicyInstancesByPolicyRequestRequestTypeDef",
     "ListTrafficPolicyInstancesRequestRequestTypeDef",
     "ListTrafficPolicyVersionsRequestRequestTypeDef",
+    "ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
     "ListVPCAssociationAuthorizationsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourceRecordTypeDef",
+    "ResponseMetadataTypeDef",
     "TestDNSAnswerRequestRequestTypeDef",
+    "TestDNSAnswerResponseTypeDef",
     "UpdateHostedZoneCommentRequestRequestTypeDef",
     "UpdateTrafficPolicyCommentRequestRequestTypeDef",
     "UpdateTrafficPolicyInstanceRequestRequestTypeDef",
+    "GetAccountLimitResponseTypeDef",
     "ActivateKeySigningKeyResponseTypeDef",
     "AssociateVPCWithHostedZoneResponseTypeDef",
-    "ChangeCidrCollectionResponseTypeDef",
     "ChangeResourceRecordSetsResponseTypeDef",
     "DeactivateKeySigningKeyResponseTypeDef",
     "DeleteHostedZoneResponseTypeDef",
     "DeleteKeySigningKeyResponseTypeDef",
     "DisableHostedZoneDNSSECResponseTypeDef",
     "DisassociateVPCFromHostedZoneResponseTypeDef",
     "EnableHostedZoneDNSSECResponseTypeDef",
-    "GetAccountLimitResponseTypeDef",
     "GetChangeResponseTypeDef",
-    "GetCheckerIpRangesResponseTypeDef",
-    "GetHealthCheckCountResponseTypeDef",
-    "GetHostedZoneCountResponseTypeDef",
-    "GetTrafficPolicyInstanceCountResponseTypeDef",
-    "TestDNSAnswerResponseTypeDef",
     "HealthCheckConfigTypeDef",
     "UpdateHealthCheckRequestRequestTypeDef",
     "AssociateVPCWithHostedZoneRequestRequestTypeDef",
     "CreateVPCAssociationAuthorizationRequestRequestTypeDef",
     "CreateVPCAssociationAuthorizationResponseTypeDef",
     "DeleteVPCAssociationAuthorizationRequestRequestTypeDef",
     "DisassociateVPCFromHostedZoneRequestRequestTypeDef",
@@ -189,22 +197,14 @@
     "ListGeoLocationsResponseTypeDef",
     "GetChangeRequestResourceRecordSetsChangedWaitTypeDef",
     "GetHostedZoneLimitResponseTypeDef",
     "GetReusableDelegationSetLimitResponseTypeDef",
     "HealthCheckObservationTypeDef",
     "HostedZoneTypeDef",
     "HostedZoneSummaryTypeDef",
-    "ListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
-    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
-    "ListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
-    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
-    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
-    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
-    "ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
-    "ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
     "ListCidrLocationsResponseTypeDef",
     "ListTrafficPoliciesResponseTypeDef",
     "ResourceRecordSetTypeDef",
     "CreateHealthCheckRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "ListTagsForResourcesResponseTypeDef",
     "HealthCheckTypeDef",
@@ -257,25 +257,14 @@
     },
     total=False,
 )
 
 class ChangeInfoTypeDef(_RequiredChangeInfoTypeDef, _OptionalChangeInfoTypeDef):
     pass
 
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
 AlarmIdentifierTypeDef = TypedDict(
     "AlarmIdentifierTypeDef",
     {
         "Region": CloudWatchRegionType,
         "Name": str,
     },
 )
@@ -303,14 +292,22 @@
     {
         "LocationName": str,
         "Action": CidrCollectionChangeActionType,
         "CidrList": Sequence[str],
     },
 )
 
+ChangeCidrCollectionResponseTypeDef = TypedDict(
+    "ChangeCidrCollectionResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
@@ -689,14 +686,22 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+GetCheckerIpRangesResponseTypeDef = TypedDict(
+    "GetCheckerIpRangesResponseTypeDef",
+    {
+        "CheckerIpRanges": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDNSSECRequestRequestTypeDef = TypedDict(
     "GetDNSSECRequestRequestTypeDef",
     {
         "HostedZoneId": str,
     },
 )
 
@@ -706,14 +711,22 @@
         "ContinentCode": str,
         "CountryCode": str,
         "SubdivisionCode": str,
     },
     total=False,
 )
 
+GetHealthCheckCountResponseTypeDef = TypedDict(
+    "GetHealthCheckCountResponseTypeDef",
+    {
+        "HealthCheckCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHealthCheckLastFailureReasonRequestRequestTypeDef = TypedDict(
     "GetHealthCheckLastFailureReasonRequestRequestTypeDef",
     {
         "HealthCheckId": str,
     },
 )
 
@@ -727,14 +740,22 @@
 GetHealthCheckStatusRequestRequestTypeDef = TypedDict(
     "GetHealthCheckStatusRequestRequestTypeDef",
     {
         "HealthCheckId": str,
     },
 )
 
+GetHostedZoneCountResponseTypeDef = TypedDict(
+    "GetHostedZoneCountResponseTypeDef",
+    {
+        "HostedZoneCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHostedZoneLimitRequestRequestTypeDef = TypedDict(
     "GetHostedZoneLimitRequestRequestTypeDef",
     {
         "Type": HostedZoneLimitTypeType,
         "HostedZoneId": str,
     },
 )
@@ -780,14 +801,22 @@
 GetReusableDelegationSetRequestRequestTypeDef = TypedDict(
     "GetReusableDelegationSetRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+GetTrafficPolicyInstanceCountResponseTypeDef = TypedDict(
+    "GetTrafficPolicyInstanceCountResponseTypeDef",
+    {
+        "TrafficPolicyInstanceCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTrafficPolicyInstanceRequestRequestTypeDef = TypedDict(
     "GetTrafficPolicyInstanceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -822,24 +851,35 @@
     {
         "OwningAccount": str,
         "OwningService": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
+    "_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CollectionId": str,
+    },
+)
+_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
+    "_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
+    {
+        "LocationName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListCidrBlocksRequestListCidrBlocksPaginateTypeDef(
+    _RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
+    _OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
+):
+    pass
+
 _RequiredListCidrBlocksRequestRequestTypeDef = TypedDict(
     "_RequiredListCidrBlocksRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 _OptionalListCidrBlocksRequestRequestTypeDef = TypedDict(
@@ -853,23 +893,51 @@
 )
 
 class ListCidrBlocksRequestRequestTypeDef(
     _RequiredListCidrBlocksRequestRequestTypeDef, _OptionalListCidrBlocksRequestRequestTypeDef
 ):
     pass
 
+ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef = TypedDict(
+    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCidrCollectionsRequestRequestTypeDef = TypedDict(
     "ListCidrCollectionsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": str,
     },
     total=False,
 )
 
+_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
+    "_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
+    {
+        "CollectionId": str,
+    },
+)
+_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
+    "_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCidrLocationsRequestListCidrLocationsPaginateTypeDef(
+    _RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
+    _OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListCidrLocationsRequestRequestTypeDef = TypedDict(
     "_RequiredListCidrLocationsRequestRequestTypeDef",
     {
         "CollectionId": str,
     },
 )
 _OptionalListCidrLocationsRequestRequestTypeDef = TypedDict(
@@ -901,14 +969,22 @@
         "StartCountryCode": str,
         "StartSubdivisionCode": str,
         "MaxItems": str,
     },
     total=False,
 )
 
+ListHealthChecksRequestListHealthChecksPaginateTypeDef = TypedDict(
+    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHealthChecksRequestRequestTypeDef = TypedDict(
     "ListHealthChecksRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
@@ -942,34 +1018,72 @@
 
 class ListHostedZonesByVPCRequestRequestTypeDef(
     _RequiredListHostedZonesByVPCRequestRequestTypeDef,
     _OptionalListHostedZonesByVPCRequestRequestTypeDef,
 ):
     pass
 
+ListHostedZonesRequestListHostedZonesPaginateTypeDef = TypedDict(
+    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
+    {
+        "DelegationSetId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHostedZonesRequestRequestTypeDef = TypedDict(
     "ListHostedZonesRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
         "DelegationSetId": str,
     },
     total=False,
 )
 
+ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef = TypedDict(
+    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
+    {
+        "HostedZoneId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueryLoggingConfigsRequestRequestTypeDef = TypedDict(
     "ListQueryLoggingConfigsRequestRequestTypeDef",
     {
         "HostedZoneId": str,
         "NextToken": str,
         "MaxResults": str,
     },
     total=False,
 )
 
+_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
+    "_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
+    {
+        "HostedZoneId": str,
+    },
+)
+_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
+    "_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef(
+    _RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
+    _OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourceRecordSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceRecordSetsRequestRequestTypeDef",
     {
         "HostedZoneId": str,
     },
 )
 _OptionalListResourceRecordSetsRequestRequestTypeDef = TypedDict(
@@ -1108,14 +1222,35 @@
 
 class ListTrafficPolicyVersionsRequestRequestTypeDef(
     _RequiredListTrafficPolicyVersionsRequestRequestTypeDef,
     _OptionalListTrafficPolicyVersionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
+    "_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
+    {
+        "HostedZoneId": str,
+    },
+)
+_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
+    "_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
+    {
+        "MaxResults": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef(
+    _RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
+    _OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListVPCAssociationAuthorizationsRequestRequestTypeDef = TypedDict(
     "_RequiredListVPCAssociationAuthorizationsRequestRequestTypeDef",
     {
         "HostedZoneId": str,
     },
 )
 _OptionalListVPCAssociationAuthorizationsRequestRequestTypeDef = TypedDict(
@@ -1129,21 +1264,42 @@
 
 class ListVPCAssociationAuthorizationsRequestRequestTypeDef(
     _RequiredListVPCAssociationAuthorizationsRequestRequestTypeDef,
     _OptionalListVPCAssociationAuthorizationsRequestRequestTypeDef,
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
 ResourceRecordTypeDef = TypedDict(
     "ResourceRecordTypeDef",
     {
         "Value": str,
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
 _RequiredTestDNSAnswerRequestRequestTypeDef = TypedDict(
     "_RequiredTestDNSAnswerRequestRequestTypeDef",
     {
         "HostedZoneId": str,
         "RecordName": str,
         "RecordType": RRTypeType,
     },
@@ -1159,14 +1315,27 @@
 )
 
 class TestDNSAnswerRequestRequestTypeDef(
     _RequiredTestDNSAnswerRequestRequestTypeDef, _OptionalTestDNSAnswerRequestRequestTypeDef
 ):
     pass
 
+TestDNSAnswerResponseTypeDef = TypedDict(
+    "TestDNSAnswerResponseTypeDef",
+    {
+        "Nameserver": str,
+        "RecordName": str,
+        "RecordType": RRTypeType,
+        "RecordData": List[str],
+        "ResponseCode": str,
+        "Protocol": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateHostedZoneCommentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateHostedZoneCommentRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateHostedZoneCommentRequestRequestTypeDef = TypedDict(
@@ -1198,153 +1367,100 @@
         "Id": str,
         "TTL": int,
         "TrafficPolicyId": str,
         "TrafficPolicyVersion": int,
     },
 )
 
+GetAccountLimitResponseTypeDef = TypedDict(
+    "GetAccountLimitResponseTypeDef",
+    {
+        "Limit": AccountLimitTypeDef,
+        "Count": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActivateKeySigningKeyResponseTypeDef = TypedDict(
     "ActivateKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateVPCWithHostedZoneResponseTypeDef = TypedDict(
     "AssociateVPCWithHostedZoneResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ChangeCidrCollectionResponseTypeDef = TypedDict(
-    "ChangeCidrCollectionResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeResourceRecordSetsResponseTypeDef = TypedDict(
     "ChangeResourceRecordSetsResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeactivateKeySigningKeyResponseTypeDef = TypedDict(
     "DeactivateKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteHostedZoneResponseTypeDef = TypedDict(
     "DeleteHostedZoneResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteKeySigningKeyResponseTypeDef = TypedDict(
     "DeleteKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisableHostedZoneDNSSECResponseTypeDef = TypedDict(
     "DisableHostedZoneDNSSECResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateVPCFromHostedZoneResponseTypeDef = TypedDict(
     "DisassociateVPCFromHostedZoneResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableHostedZoneDNSSECResponseTypeDef = TypedDict(
     "EnableHostedZoneDNSSECResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountLimitResponseTypeDef = TypedDict(
-    "GetAccountLimitResponseTypeDef",
-    {
-        "Limit": AccountLimitTypeDef,
-        "Count": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChangeResponseTypeDef = TypedDict(
     "GetChangeResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCheckerIpRangesResponseTypeDef = TypedDict(
-    "GetCheckerIpRangesResponseTypeDef",
-    {
-        "CheckerIpRanges": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetHealthCheckCountResponseTypeDef = TypedDict(
-    "GetHealthCheckCountResponseTypeDef",
-    {
-        "HealthCheckCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetHostedZoneCountResponseTypeDef = TypedDict(
-    "GetHostedZoneCountResponseTypeDef",
-    {
-        "HostedZoneCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTrafficPolicyInstanceCountResponseTypeDef = TypedDict(
-    "GetTrafficPolicyInstanceCountResponseTypeDef",
-    {
-        "TrafficPolicyInstanceCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestDNSAnswerResponseTypeDef = TypedDict(
-    "TestDNSAnswerResponseTypeDef",
-    {
-        "Nameserver": str,
-        "RecordName": str,
-        "RecordType": RRTypeType,
-        "RecordData": List[str],
-        "ResponseCode": str,
-        "Protocol": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHealthCheckConfigTypeDef = TypedDict(
     "_RequiredHealthCheckConfigTypeDef",
     {
         "Type": HealthCheckTypeType,
@@ -1443,15 +1559,15 @@
 )
 
 CreateVPCAssociationAuthorizationResponseTypeDef = TypedDict(
     "CreateVPCAssociationAuthorizationResponseTypeDef",
     {
         "HostedZoneId": str,
         "VPC": VPCTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVPCAssociationAuthorizationRequestRequestTypeDef = TypedDict(
     "DeleteVPCAssociationAuthorizationRequestRequestTypeDef",
     {
         "HostedZoneId": str,
@@ -1482,15 +1598,15 @@
 
 ListVPCAssociationAuthorizationsResponseTypeDef = TypedDict(
     "ListVPCAssociationAuthorizationsResponseTypeDef",
     {
         "HostedZoneId": str,
         "NextToken": str,
         "VPCs": List[VPCTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredChangeCidrCollectionRequestRequestTypeDef = TypedDict(
     "_RequiredChangeCidrCollectionRequestRequestTypeDef",
     {
         "Id": str,
@@ -1544,24 +1660,24 @@
 )
 
 ListCidrBlocksResponseTypeDef = TypedDict(
     "ListCidrBlocksResponseTypeDef",
     {
         "NextToken": str,
         "CidrBlocks": List[CidrBlockSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCidrCollectionResponseTypeDef = TypedDict(
     "CreateCidrCollectionResponseTypeDef",
     {
         "Collection": CidrCollectionTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCloudWatchAlarmConfigurationTypeDef = TypedDict(
     "_RequiredCloudWatchAlarmConfigurationTypeDef",
     {
         "EvaluationPeriods": int,
@@ -1587,15 +1703,15 @@
     pass
 
 ListCidrCollectionsResponseTypeDef = TypedDict(
     "ListCidrCollectionsResponseTypeDef",
     {
         "NextToken": str,
         "CidrCollections": List[CollectionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateHostedZoneRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHostedZoneRequestRequestTypeDef",
     {
         "Name": str,
@@ -1618,209 +1734,209 @@
     pass
 
 CreateReusableDelegationSetResponseTypeDef = TypedDict(
     "CreateReusableDelegationSetResponseTypeDef",
     {
         "DelegationSet": DelegationSetTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReusableDelegationSetResponseTypeDef = TypedDict(
     "GetReusableDelegationSetResponseTypeDef",
     {
         "DelegationSet": DelegationSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReusableDelegationSetsResponseTypeDef = TypedDict(
     "ListReusableDelegationSetsResponseTypeDef",
     {
         "DelegationSets": List[DelegationSetTypeDef],
         "Marker": str,
         "IsTruncated": bool,
         "NextMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateKeySigningKeyResponseTypeDef = TypedDict(
     "CreateKeySigningKeyResponseTypeDef",
     {
         "ChangeInfo": ChangeInfoTypeDef,
         "KeySigningKey": KeySigningKeyTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateQueryLoggingConfigResponseTypeDef = TypedDict(
     "CreateQueryLoggingConfigResponseTypeDef",
     {
         "QueryLoggingConfig": QueryLoggingConfigTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueryLoggingConfigResponseTypeDef = TypedDict(
     "GetQueryLoggingConfigResponseTypeDef",
     {
         "QueryLoggingConfig": QueryLoggingConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQueryLoggingConfigsResponseTypeDef = TypedDict(
     "ListQueryLoggingConfigsResponseTypeDef",
     {
         "QueryLoggingConfigs": List[QueryLoggingConfigTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTrafficPolicyInstanceResponseTypeDef = TypedDict(
     "CreateTrafficPolicyInstanceResponseTypeDef",
     {
         "TrafficPolicyInstance": TrafficPolicyInstanceTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrafficPolicyInstanceResponseTypeDef = TypedDict(
     "GetTrafficPolicyInstanceResponseTypeDef",
     {
         "TrafficPolicyInstance": TrafficPolicyInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyInstancesByHostedZoneResponseTypeDef = TypedDict(
     "ListTrafficPolicyInstancesByHostedZoneResponseTypeDef",
     {
         "TrafficPolicyInstances": List[TrafficPolicyInstanceTypeDef],
         "TrafficPolicyInstanceNameMarker": str,
         "TrafficPolicyInstanceTypeMarker": RRTypeType,
         "IsTruncated": bool,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyInstancesByPolicyResponseTypeDef = TypedDict(
     "ListTrafficPolicyInstancesByPolicyResponseTypeDef",
     {
         "TrafficPolicyInstances": List[TrafficPolicyInstanceTypeDef],
         "HostedZoneIdMarker": str,
         "TrafficPolicyInstanceNameMarker": str,
         "TrafficPolicyInstanceTypeMarker": RRTypeType,
         "IsTruncated": bool,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyInstancesResponseTypeDef = TypedDict(
     "ListTrafficPolicyInstancesResponseTypeDef",
     {
         "TrafficPolicyInstances": List[TrafficPolicyInstanceTypeDef],
         "HostedZoneIdMarker": str,
         "TrafficPolicyInstanceNameMarker": str,
         "TrafficPolicyInstanceTypeMarker": RRTypeType,
         "IsTruncated": bool,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTrafficPolicyInstanceResponseTypeDef = TypedDict(
     "UpdateTrafficPolicyInstanceResponseTypeDef",
     {
         "TrafficPolicyInstance": TrafficPolicyInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTrafficPolicyResponseTypeDef = TypedDict(
     "CreateTrafficPolicyResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTrafficPolicyVersionResponseTypeDef = TypedDict(
     "CreateTrafficPolicyVersionResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTrafficPolicyResponseTypeDef = TypedDict(
     "GetTrafficPolicyResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPolicyVersionsResponseTypeDef = TypedDict(
     "ListTrafficPolicyVersionsResponseTypeDef",
     {
         "TrafficPolicies": List[TrafficPolicyTypeDef],
         "IsTruncated": bool,
         "TrafficPolicyVersionMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTrafficPolicyCommentResponseTypeDef = TypedDict(
     "UpdateTrafficPolicyCommentResponseTypeDef",
     {
         "TrafficPolicy": TrafficPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDNSSECResponseTypeDef = TypedDict(
     "GetDNSSECResponseTypeDef",
     {
         "Status": DNSSECStatusTypeDef,
         "KeySigningKeys": List[KeySigningKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGeoLocationResponseTypeDef = TypedDict(
     "GetGeoLocationResponseTypeDef",
     {
         "GeoLocationDetails": GeoLocationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGeoLocationsResponseTypeDef = TypedDict(
     "ListGeoLocationsResponseTypeDef",
     {
         "GeoLocationDetailsList": List[GeoLocationDetailsTypeDef],
         "IsTruncated": bool,
         "NextContinentCode": str,
         "NextCountryCode": str,
         "NextSubdivisionCode": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetChangeRequestResourceRecordSetsChangedWaitTypeDef = TypedDict(
     "_RequiredGetChangeRequestResourceRecordSetsChangedWaitTypeDef",
     {
         "Id": str,
@@ -1841,24 +1957,24 @@
     pass
 
 GetHostedZoneLimitResponseTypeDef = TypedDict(
     "GetHostedZoneLimitResponseTypeDef",
     {
         "Limit": HostedZoneLimitTypeDef,
         "Count": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReusableDelegationSetLimitResponseTypeDef = TypedDict(
     "GetReusableDelegationSetLimitResponseTypeDef",
     {
         "Limit": ReusableDelegationSetLimitTypeDef,
         "Count": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HealthCheckObservationTypeDef = TypedDict(
     "HealthCheckObservationTypeDef",
     {
         "Region": HealthCheckRegionType,
@@ -1894,147 +2010,31 @@
     {
         "HostedZoneId": str,
         "Name": str,
         "Owner": HostedZoneOwnerTypeDef,
     },
 )
 
-_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
-    "_RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
-    {
-        "CollectionId": str,
-    },
-)
-_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef = TypedDict(
-    "_OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef",
-    {
-        "LocationName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCidrBlocksRequestListCidrBlocksPaginateTypeDef(
-    _RequiredListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-    _OptionalListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-):
-    pass
-
-ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef = TypedDict(
-    "ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
-    "_RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
-    {
-        "CollectionId": str,
-    },
-)
-_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef = TypedDict(
-    "_OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCidrLocationsRequestListCidrLocationsPaginateTypeDef(
-    _RequiredListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-    _OptionalListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-):
-    pass
-
-ListHealthChecksRequestListHealthChecksPaginateTypeDef = TypedDict(
-    "ListHealthChecksRequestListHealthChecksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHostedZonesRequestListHostedZonesPaginateTypeDef = TypedDict(
-    "ListHostedZonesRequestListHostedZonesPaginateTypeDef",
-    {
-        "DelegationSetId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef = TypedDict(
-    "ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef",
-    {
-        "HostedZoneId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
-    "_RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
-    {
-        "HostedZoneId": str,
-    },
-)
-_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef = TypedDict(
-    "_OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef(
-    _RequiredListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-    _OptionalListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
-    "_RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
-    {
-        "HostedZoneId": str,
-    },
-)
-_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef = TypedDict(
-    "_OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef",
-    {
-        "MaxResults": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef(
-    _RequiredListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
-    _OptionalListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
-):
-    pass
-
 ListCidrLocationsResponseTypeDef = TypedDict(
     "ListCidrLocationsResponseTypeDef",
     {
         "NextToken": str,
         "CidrLocations": List[LocationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTrafficPoliciesResponseTypeDef = TypedDict(
     "ListTrafficPoliciesResponseTypeDef",
     {
         "TrafficPolicySummaries": List[TrafficPolicySummaryTypeDef],
         "IsTruncated": bool,
         "TrafficPolicyIdMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResourceRecordSetTypeDef = TypedDict(
     "_RequiredResourceRecordSetTypeDef",
     {
         "Name": str,
@@ -2073,23 +2073,23 @@
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceTagSet": ResourceTagSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourcesResponseTypeDef = TypedDict(
     "ListTagsForResourcesResponseTypeDef",
     {
         "ResourceTagSets": List[ResourceTagSetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHealthCheckTypeDef = TypedDict(
     "_RequiredHealthCheckTypeDef",
     {
         "Id": str,
@@ -2110,89 +2110,89 @@
 class HealthCheckTypeDef(_RequiredHealthCheckTypeDef, _OptionalHealthCheckTypeDef):
     pass
 
 GetHealthCheckLastFailureReasonResponseTypeDef = TypedDict(
     "GetHealthCheckLastFailureReasonResponseTypeDef",
     {
         "HealthCheckObservations": List[HealthCheckObservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHealthCheckStatusResponseTypeDef = TypedDict(
     "GetHealthCheckStatusResponseTypeDef",
     {
         "HealthCheckObservations": List[HealthCheckObservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHostedZoneResponseTypeDef = TypedDict(
     "CreateHostedZoneResponseTypeDef",
     {
         "HostedZone": HostedZoneTypeDef,
         "ChangeInfo": ChangeInfoTypeDef,
         "DelegationSet": DelegationSetTypeDef,
         "VPC": VPCTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHostedZoneResponseTypeDef = TypedDict(
     "GetHostedZoneResponseTypeDef",
     {
         "HostedZone": HostedZoneTypeDef,
         "DelegationSet": DelegationSetTypeDef,
         "VPCs": List[VPCTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostedZonesByNameResponseTypeDef = TypedDict(
     "ListHostedZonesByNameResponseTypeDef",
     {
         "HostedZones": List[HostedZoneTypeDef],
         "DNSName": str,
         "HostedZoneId": str,
         "IsTruncated": bool,
         "NextDNSName": str,
         "NextHostedZoneId": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostedZonesResponseTypeDef = TypedDict(
     "ListHostedZonesResponseTypeDef",
     {
         "HostedZones": List[HostedZoneTypeDef],
         "Marker": str,
         "IsTruncated": bool,
         "NextMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateHostedZoneCommentResponseTypeDef = TypedDict(
     "UpdateHostedZoneCommentResponseTypeDef",
     {
         "HostedZone": HostedZoneTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHostedZonesByVPCResponseTypeDef = TypedDict(
     "ListHostedZonesByVPCResponseTypeDef",
     {
         "HostedZoneSummaries": List[HostedZoneSummaryTypeDef],
         "MaxItems": str,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeTypeDef = TypedDict(
     "ChangeTypeDef",
     {
         "Action": ChangeActionType,
@@ -2205,52 +2205,52 @@
     {
         "ResourceRecordSets": List[ResourceRecordSetTypeDef],
         "IsTruncated": bool,
         "NextRecordName": str,
         "NextRecordType": RRTypeType,
         "NextRecordIdentifier": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHealthCheckResponseTypeDef = TypedDict(
     "CreateHealthCheckResponseTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHealthCheckResponseTypeDef = TypedDict(
     "GetHealthCheckResponseTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHealthChecksResponseTypeDef = TypedDict(
     "ListHealthChecksResponseTypeDef",
     {
         "HealthChecks": List[HealthCheckTypeDef],
         "Marker": str,
         "IsTruncated": bool,
         "NextMarker": str,
         "MaxItems": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateHealthCheckResponseTypeDef = TypedDict(
     "UpdateHealthCheckResponseTypeDef",
     {
         "HealthCheck": HealthCheckTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredChangeBatchTypeDef = TypedDict(
     "_RequiredChangeBatchTypeDef",
     {
         "Changes": Sequence[ChangeTypeDef],
```

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/waiter.py` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53/waiter.pyi` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/PKG-INFO` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53"></a>
 
 # types-aiobotocore-route53
 
 [![PyPI - types-aiobotocore-route53](https://img.shields.io/pypi/v/types-aiobotocore-route53.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53)
+[aiobotocore.Route53 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53.html#Route53)
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
 [types-aiobotocore-route53 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53/).
 
 See how it helps to find and fix potential bugs:
 
@@ -397,19 +397,19 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53.type_defs import (
     AccountLimitTypeDef,
     ActivateKeySigningKeyRequestRequestTypeDef,
     ChangeInfoTypeDef,
-    ResponseMetadataTypeDef,
     AlarmIdentifierTypeDef,
     AliasTargetTypeDef,
     VPCTypeDef,
     CidrCollectionChangeTypeDef,
+    ChangeCidrCollectionResponseTypeDef,
     TagTypeDef,
     CidrBlockSummaryTypeDef,
     CidrCollectionTypeDef,
     CidrRoutingConfigTypeDef,
     DimensionTypeDef,
     CollectionSummaryTypeDef,
     CreateCidrCollectionRequestRequestTypeDef,
@@ -438,75 +438,83 @@
     DisableHostedZoneDNSSECRequestRequestTypeDef,
     EnableHostedZoneDNSSECRequestRequestTypeDef,
     GeoLocationDetailsTypeDef,
     GeoLocationTypeDef,
     GetAccountLimitRequestRequestTypeDef,
     GetChangeRequestRequestTypeDef,
     WaiterConfigTypeDef,
+    GetCheckerIpRangesResponseTypeDef,
     GetDNSSECRequestRequestTypeDef,
     GetGeoLocationRequestRequestTypeDef,
+    GetHealthCheckCountResponseTypeDef,
     GetHealthCheckLastFailureReasonRequestRequestTypeDef,
     GetHealthCheckRequestRequestTypeDef,
     GetHealthCheckStatusRequestRequestTypeDef,
+    GetHostedZoneCountResponseTypeDef,
     GetHostedZoneLimitRequestRequestTypeDef,
     HostedZoneLimitTypeDef,
     GetHostedZoneRequestRequestTypeDef,
     GetQueryLoggingConfigRequestRequestTypeDef,
     GetReusableDelegationSetLimitRequestRequestTypeDef,
     ReusableDelegationSetLimitTypeDef,
     GetReusableDelegationSetRequestRequestTypeDef,
+    GetTrafficPolicyInstanceCountResponseTypeDef,
     GetTrafficPolicyInstanceRequestRequestTypeDef,
     GetTrafficPolicyRequestRequestTypeDef,
     StatusReportTypeDef,
     LinkedServiceTypeDef,
     HostedZoneOwnerTypeDef,
-    PaginatorConfigTypeDef,
+    ListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
     ListCidrBlocksRequestRequestTypeDef,
+    ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef,
     ListCidrCollectionsRequestRequestTypeDef,
+    ListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
     ListCidrLocationsRequestRequestTypeDef,
     LocationSummaryTypeDef,
     ListGeoLocationsRequestRequestTypeDef,
+    ListHealthChecksRequestListHealthChecksPaginateTypeDef,
     ListHealthChecksRequestRequestTypeDef,
     ListHostedZonesByNameRequestRequestTypeDef,
     ListHostedZonesByVPCRequestRequestTypeDef,
+    ListHostedZonesRequestListHostedZonesPaginateTypeDef,
     ListHostedZonesRequestRequestTypeDef,
+    ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef,
     ListQueryLoggingConfigsRequestRequestTypeDef,
+    ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
     ListResourceRecordSetsRequestRequestTypeDef,
     ListReusableDelegationSetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListTagsForResourcesRequestRequestTypeDef,
     ListTrafficPoliciesRequestRequestTypeDef,
     TrafficPolicySummaryTypeDef,
     ListTrafficPolicyInstancesByHostedZoneRequestRequestTypeDef,
     ListTrafficPolicyInstancesByPolicyRequestRequestTypeDef,
     ListTrafficPolicyInstancesRequestRequestTypeDef,
     ListTrafficPolicyVersionsRequestRequestTypeDef,
+    ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
     ListVPCAssociationAuthorizationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ResourceRecordTypeDef,
+    ResponseMetadataTypeDef,
     TestDNSAnswerRequestRequestTypeDef,
+    TestDNSAnswerResponseTypeDef,
     UpdateHostedZoneCommentRequestRequestTypeDef,
     UpdateTrafficPolicyCommentRequestRequestTypeDef,
     UpdateTrafficPolicyInstanceRequestRequestTypeDef,
+    GetAccountLimitResponseTypeDef,
     ActivateKeySigningKeyResponseTypeDef,
     AssociateVPCWithHostedZoneResponseTypeDef,
-    ChangeCidrCollectionResponseTypeDef,
     ChangeResourceRecordSetsResponseTypeDef,
     DeactivateKeySigningKeyResponseTypeDef,
     DeleteHostedZoneResponseTypeDef,
     DeleteKeySigningKeyResponseTypeDef,
     DisableHostedZoneDNSSECResponseTypeDef,
     DisassociateVPCFromHostedZoneResponseTypeDef,
     EnableHostedZoneDNSSECResponseTypeDef,
-    GetAccountLimitResponseTypeDef,
     GetChangeResponseTypeDef,
-    GetCheckerIpRangesResponseTypeDef,
-    GetHealthCheckCountResponseTypeDef,
-    GetHostedZoneCountResponseTypeDef,
-    GetTrafficPolicyInstanceCountResponseTypeDef,
-    TestDNSAnswerResponseTypeDef,
     HealthCheckConfigTypeDef,
     UpdateHealthCheckRequestRequestTypeDef,
     AssociateVPCWithHostedZoneRequestRequestTypeDef,
     CreateVPCAssociationAuthorizationRequestRequestTypeDef,
     CreateVPCAssociationAuthorizationResponseTypeDef,
     DeleteVPCAssociationAuthorizationRequestRequestTypeDef,
     DisassociateVPCFromHostedZoneRequestRequestTypeDef,
@@ -542,22 +550,14 @@
     ListGeoLocationsResponseTypeDef,
     GetChangeRequestResourceRecordSetsChangedWaitTypeDef,
     GetHostedZoneLimitResponseTypeDef,
     GetReusableDelegationSetLimitResponseTypeDef,
     HealthCheckObservationTypeDef,
     HostedZoneTypeDef,
     HostedZoneSummaryTypeDef,
-    ListCidrBlocksRequestListCidrBlocksPaginateTypeDef,
-    ListCidrCollectionsRequestListCidrCollectionsPaginateTypeDef,
-    ListCidrLocationsRequestListCidrLocationsPaginateTypeDef,
-    ListHealthChecksRequestListHealthChecksPaginateTypeDef,
-    ListHostedZonesRequestListHostedZonesPaginateTypeDef,
-    ListQueryLoggingConfigsRequestListQueryLoggingConfigsPaginateTypeDef,
-    ListResourceRecordSetsRequestListResourceRecordSetsPaginateTypeDef,
-    ListVPCAssociationAuthorizationsRequestListVPCAssociationAuthorizationsPaginateTypeDef,
     ListCidrLocationsResponseTypeDef,
     ListTrafficPoliciesResponseTypeDef,
     ResourceRecordSetTypeDef,
     CreateHealthCheckRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTagsForResourcesResponseTypeDef,
     HealthCheckTypeDef,
@@ -587,43 +587,43 @@
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

### Comparing `types-aiobotocore-route53-2.5.0.post1/types_aiobotocore_route53.egg-info/SOURCES.txt` & `types-aiobotocore-route53-2.5.1/types_aiobotocore_route53.egg-info/SOURCES.txt`

 * *Files identical despite different names*

