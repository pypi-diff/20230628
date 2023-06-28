# Comparing `tmp/types-aiobotocore-es-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-es-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-es-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:36 2023, max compression
+gzip compressed data, was "types-aiobotocore-es-2.5.1.tar", last modified: Wed Jun 28 01:43:29 2023, max compression
```

## Comparing `types-aiobotocore-es-2.5.0.post1.tar` & `types-aiobotocore-es-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.955199 types-aiobotocore-es-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22666 2023-03-11 12:26:36.955199 types-aiobotocore-es-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21097 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:36.955199 types-aiobotocore-es-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2083 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.955199 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/
--rw-r--r--   0 runner    (1001) docker     (123)     2015 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2014 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      948 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    43173 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    43109 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14308 2023-03-11 12:14:24.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14306 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7674 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7666 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    63595 2023-03-11 12:14:26.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    63548 2023-03-11 12:14:25.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:23.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.955199 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22666 2023-03-11 12:26:36.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      718 2023-03-11 12:26:36.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:36.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-03-11 12:26:36.000000 types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.234136 types-aiobotocore-es-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22653 2023-06-28 01:43:29.234136 types-aiobotocore-es-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21090 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:29.234136 types-aiobotocore-es-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2077 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.234136 types-aiobotocore-es-2.5.1/types_aiobotocore_es/
+-rw-r--r--   0 runner    (1001) docker     (123)     2015 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2014 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      936 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43173 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43109 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14517 2023-06-28 01:31:00.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14515 2023-06-28 01:31:00.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7564 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7557 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    63699 2023-06-28 01:31:02.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    63652 2023-06-28 01:31:00.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:59.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.234136 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22653 2023-06-28 01:43:29.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      718 2023-06-28 01:43:29.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:29.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 01:43:29.000000 types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-es-2.5.0.post1/LICENSE` & `types-aiobotocore-es-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-es-2.5.0.post1/PKG-INFO` & `types-aiobotocore-es-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-es
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticsearchService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticsearchService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-es"></a>
 
 # types-aiobotocore-es
 
 [![PyPI - types-aiobotocore-es](https://img.shields.io/pypi/v/types-aiobotocore-es.svg?color=blue)](https://pypi.org/project/types-aiobotocore-es)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-es.svg?color=blue)](https://pypi.org/project/types-aiobotocore-es)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-es?color=blue)](https://pypistats.org/packages/types-aiobotocore-es)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticsearchService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService)
+[aiobotocore.ElasticsearchService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService)
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
 [types-aiobotocore-es docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,15 +366,14 @@
 
 `types_aiobotocore_es.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_es.type_defs import (
     AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     OptionStatusTypeDef,
     TagTypeDef,
     AdditionalLimitTypeDef,
     MasterUserOptionsTypeDef,
     AssociatePackageRequestRequestTypeDef,
     AuthorizeVpcEndpointAccessRequestRequestTypeDef,
     AuthorizedPrincipalTypeDef,
@@ -409,56 +408,62 @@
     DescribeDomainChangeProgressRequestRequestTypeDef,
     DescribeElasticsearchDomainConfigRequestRequestTypeDef,
     DescribeElasticsearchDomainRequestRequestTypeDef,
     DescribeElasticsearchDomainsRequestRequestTypeDef,
     DescribeElasticsearchInstanceTypeLimitsRequestRequestTypeDef,
     FilterTypeDef,
     DescribePackagesFilterTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef,
     DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef,
+    DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef,
     DescribeReservedElasticsearchInstancesRequestRequestTypeDef,
     DescribeVpcEndpointsRequestRequestTypeDef,
     VpcEndpointErrorTypeDef,
     DissociatePackageRequestRequestTypeDef,
     DomainInfoTypeDef,
     ErrorDetailsTypeDef,
     DryRunResultsTypeDef,
     ZoneAwarenessConfigTypeDef,
     VPCDerivedInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCompatibleElasticsearchVersionsRequestRequestTypeDef,
     GetPackageVersionHistoryRequestRequestTypeDef,
     PackageVersionHistoryTypeDef,
+    GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
     GetUpgradeHistoryRequestRequestTypeDef,
     GetUpgradeStatusRequestRequestTypeDef,
+    GetUpgradeStatusResponseTypeDef,
     InboundCrossClusterSearchConnectionStatusTypeDef,
     InstanceCountLimitsTypeDef,
     ListDomainNamesRequestRequestTypeDef,
     ListDomainsForPackageRequestRequestTypeDef,
+    ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
     ListElasticsearchInstanceTypesRequestRequestTypeDef,
+    ListElasticsearchInstanceTypesResponseTypeDef,
+    ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef,
     ListElasticsearchVersionsRequestRequestTypeDef,
+    ListElasticsearchVersionsResponseTypeDef,
     ListPackagesForDomainRequestRequestTypeDef,
     ListTagsRequestRequestTypeDef,
     ListVpcEndpointAccessRequestRequestTypeDef,
     ListVpcEndpointsForDomainRequestRequestTypeDef,
     ListVpcEndpointsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
+    PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef,
     RecurringChargeTypeDef,
     RejectInboundCrossClusterSearchConnectionRequestRequestTypeDef,
     RemoveTagsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeVpcEndpointAccessRequestRequestTypeDef,
     SAMLIdpTypeDef,
     StartElasticsearchServiceSoftwareUpdateRequestRequestTypeDef,
     StorageTypeLimitTypeDef,
     UpgradeElasticsearchDomainRequestRequestTypeDef,
     UpgradeStepItemTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetUpgradeStatusResponseTypeDef,
-    ListElasticsearchInstanceTypesResponseTypeDef,
-    ListElasticsearchVersionsResponseTypeDef,
-    PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef,
     AccessPoliciesStatusTypeDef,
     AdvancedOptionsStatusTypeDef,
     ElasticsearchVersionStatusTypeDef,
     AddTagsRequestRequestTypeDef,
     ListTagsResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
@@ -485,19 +490,14 @@
     UpdatePackageRequestRequestTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
     DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef,
     DescribeOutboundCrossClusterSearchConnectionsRequestRequestTypeDef,
     DescribePackagesRequestRequestTypeDef,
-    DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef,
-    DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef,
-    GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-    ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-    ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef,
     ListDomainNamesResponseTypeDef,
     DomainPackageDetailsTypeDef,
     PackageDetailsTypeDef,
     ElasticsearchClusterConfigTypeDef,
     VPCDerivedInfoStatusTypeDef,
     VpcEndpointTypeDef,
     GetPackageVersionHistoryResponseTypeDef,
@@ -561,43 +561,43 @@
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

### Comparing `types-aiobotocore-es-2.5.0.post1/README.md` & `types-aiobotocore-es-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-es"></a>
 
 # types-aiobotocore-es
 
 [![PyPI - types-aiobotocore-es](https://img.shields.io/pypi/v/types-aiobotocore-es.svg?color=blue)](https://pypi.org/project/types-aiobotocore-es)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-es.svg?color=blue)](https://pypi.org/project/types-aiobotocore-es)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-es?color=blue)](https://pypistats.org/packages/types-aiobotocore-es)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticsearchService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService)
+[aiobotocore.ElasticsearchService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService)
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
 [types-aiobotocore-es docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/).
 
 See how it helps to find and fix potential bugs:
 
@@ -333,15 +333,14 @@
 
 `types_aiobotocore_es.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_es.type_defs import (
     AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     OptionStatusTypeDef,
     TagTypeDef,
     AdditionalLimitTypeDef,
     MasterUserOptionsTypeDef,
     AssociatePackageRequestRequestTypeDef,
     AuthorizeVpcEndpointAccessRequestRequestTypeDef,
     AuthorizedPrincipalTypeDef,
@@ -376,56 +375,62 @@
     DescribeDomainChangeProgressRequestRequestTypeDef,
     DescribeElasticsearchDomainConfigRequestRequestTypeDef,
     DescribeElasticsearchDomainRequestRequestTypeDef,
     DescribeElasticsearchDomainsRequestRequestTypeDef,
     DescribeElasticsearchInstanceTypeLimitsRequestRequestTypeDef,
     FilterTypeDef,
     DescribePackagesFilterTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef,
     DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef,
+    DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef,
     DescribeReservedElasticsearchInstancesRequestRequestTypeDef,
     DescribeVpcEndpointsRequestRequestTypeDef,
     VpcEndpointErrorTypeDef,
     DissociatePackageRequestRequestTypeDef,
     DomainInfoTypeDef,
     ErrorDetailsTypeDef,
     DryRunResultsTypeDef,
     ZoneAwarenessConfigTypeDef,
     VPCDerivedInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCompatibleElasticsearchVersionsRequestRequestTypeDef,
     GetPackageVersionHistoryRequestRequestTypeDef,
     PackageVersionHistoryTypeDef,
+    GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
     GetUpgradeHistoryRequestRequestTypeDef,
     GetUpgradeStatusRequestRequestTypeDef,
+    GetUpgradeStatusResponseTypeDef,
     InboundCrossClusterSearchConnectionStatusTypeDef,
     InstanceCountLimitsTypeDef,
     ListDomainNamesRequestRequestTypeDef,
     ListDomainsForPackageRequestRequestTypeDef,
+    ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
     ListElasticsearchInstanceTypesRequestRequestTypeDef,
+    ListElasticsearchInstanceTypesResponseTypeDef,
+    ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef,
     ListElasticsearchVersionsRequestRequestTypeDef,
+    ListElasticsearchVersionsResponseTypeDef,
     ListPackagesForDomainRequestRequestTypeDef,
     ListTagsRequestRequestTypeDef,
     ListVpcEndpointAccessRequestRequestTypeDef,
     ListVpcEndpointsForDomainRequestRequestTypeDef,
     ListVpcEndpointsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
+    PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef,
     RecurringChargeTypeDef,
     RejectInboundCrossClusterSearchConnectionRequestRequestTypeDef,
     RemoveTagsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeVpcEndpointAccessRequestRequestTypeDef,
     SAMLIdpTypeDef,
     StartElasticsearchServiceSoftwareUpdateRequestRequestTypeDef,
     StorageTypeLimitTypeDef,
     UpgradeElasticsearchDomainRequestRequestTypeDef,
     UpgradeStepItemTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetUpgradeStatusResponseTypeDef,
-    ListElasticsearchInstanceTypesResponseTypeDef,
-    ListElasticsearchVersionsResponseTypeDef,
-    PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef,
     AccessPoliciesStatusTypeDef,
     AdvancedOptionsStatusTypeDef,
     ElasticsearchVersionStatusTypeDef,
     AddTagsRequestRequestTypeDef,
     ListTagsResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
@@ -452,19 +457,14 @@
     UpdatePackageRequestRequestTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
     DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef,
     DescribeOutboundCrossClusterSearchConnectionsRequestRequestTypeDef,
     DescribePackagesRequestRequestTypeDef,
-    DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef,
-    DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef,
-    GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-    ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-    ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef,
     ListDomainNamesResponseTypeDef,
     DomainPackageDetailsTypeDef,
     PackageDetailsTypeDef,
     ElasticsearchClusterConfigTypeDef,
     VPCDerivedInfoStatusTypeDef,
     VpcEndpointTypeDef,
     GetPackageVersionHistoryResponseTypeDef,
@@ -528,43 +528,43 @@
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

### Comparing `types-aiobotocore-es-2.5.0.post1/setup.py` & `types-aiobotocore-es-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-es.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-es",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_es"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ElasticsearchService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ElasticsearchService 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/",
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

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/__init__.py` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/__init__.pyi` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/__main__.py` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ElasticsearchService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ElasticsearchService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es//\nBoto3 docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService\nOther"
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

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/client.py` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/client.pyi` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/literals.py` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -256,14 +256,15 @@
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
@@ -342,14 +343,15 @@
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
@@ -360,14 +362,15 @@
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
@@ -403,14 +406,15 @@
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
@@ -429,16 +433,19 @@
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
@@ -522,15 +529,17 @@
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

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/literals.pyi` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -254,14 +254,15 @@
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
@@ -340,14 +341,15 @@
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
@@ -358,14 +360,15 @@
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
@@ -401,14 +404,15 @@
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
@@ -427,16 +431,19 @@
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
@@ -520,15 +527,17 @@
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

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/paginator.py` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         describe_reserved_elasticsearch_instance_offerings_paginator: DescribeReservedElasticsearchInstanceOfferingsPaginator = client.get_paginator("describe_reserved_elasticsearch_instance_offerings")
         describe_reserved_elasticsearch_instances_paginator: DescribeReservedElasticsearchInstancesPaginator = client.get_paginator("describe_reserved_elasticsearch_instances")
         get_upgrade_history_paginator: GetUpgradeHistoryPaginator = client.get_paginator("get_upgrade_history")
         list_elasticsearch_instance_types_paginator: ListElasticsearchInstanceTypesPaginator = client.get_paginator("list_elasticsearch_instance_types")
         list_elasticsearch_versions_paginator: ListElasticsearchVersionsPaginator = client.get_paginator("list_elasticsearch_versions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef,
     DescribeReservedElasticsearchInstancesResponseTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     ListElasticsearchInstanceTypesResponseTypeDef,
     ListElasticsearchVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeReservedElasticsearchInstanceOfferingsPaginator",
     "DescribeReservedElasticsearchInstancesPaginator",
     "GetUpgradeHistoryPaginator",
     "ListElasticsearchInstanceTypesPaginator",
     "ListElasticsearchVersionsPaginator",
 )
@@ -74,15 +67,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstanceofferingspaginator)
     """
 
     def paginate(
         self,
         *,
         ReservedElasticsearchInstanceOfferingId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.DescribeReservedElasticsearchInstanceOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstanceofferingspaginator)
         """
 
 
@@ -92,30 +85,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         ReservedElasticsearchInstanceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedElasticsearchInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.DescribeReservedElasticsearchInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstancespaginator)
         """
 
 
 class GetUpgradeHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.GetUpgradeHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#getupgradehistorypaginator)
     """
 
     def paginate(
-        self, *, DomainName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DomainName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetUpgradeHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.GetUpgradeHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#getupgradehistorypaginator)
         """
 
 
@@ -126,28 +119,28 @@
     """
 
     def paginate(
         self,
         *,
         ElasticsearchVersion: str,
         DomainName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListElasticsearchInstanceTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.ListElasticsearchInstanceTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#listelasticsearchinstancetypespaginator)
         """
 
 
 class ListElasticsearchVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.ListElasticsearchVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#listelasticsearchversionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListElasticsearchVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.ListElasticsearchVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#listelasticsearchversionspaginator)
         """
```

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/paginator.pyi` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         describe_reserved_elasticsearch_instance_offerings_paginator: DescribeReservedElasticsearchInstanceOfferingsPaginator = client.get_paginator("describe_reserved_elasticsearch_instance_offerings")
         describe_reserved_elasticsearch_instances_paginator: DescribeReservedElasticsearchInstancesPaginator = client.get_paginator("describe_reserved_elasticsearch_instances")
         get_upgrade_history_paginator: GetUpgradeHistoryPaginator = client.get_paginator("get_upgrade_history")
         list_elasticsearch_instance_types_paginator: ListElasticsearchInstanceTypesPaginator = client.get_paginator("list_elasticsearch_instance_types")
         list_elasticsearch_versions_paginator: ListElasticsearchVersionsPaginator = client.get_paginator("list_elasticsearch_versions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef,
     DescribeReservedElasticsearchInstancesResponseTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     ListElasticsearchInstanceTypesResponseTypeDef,
     ListElasticsearchVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeReservedElasticsearchInstanceOfferingsPaginator",
     "DescribeReservedElasticsearchInstancesPaginator",
     "GetUpgradeHistoryPaginator",
     "ListElasticsearchInstanceTypesPaginator",
     "ListElasticsearchVersionsPaginator",
 )
@@ -70,15 +64,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstanceofferingspaginator)
     """
 
     def paginate(
         self,
         *,
         ReservedElasticsearchInstanceOfferingId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.DescribeReservedElasticsearchInstanceOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstanceofferingspaginator)
         """
 
 class DescribeReservedElasticsearchInstancesPaginator(AioPaginator):
@@ -87,29 +81,29 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         ReservedElasticsearchInstanceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedElasticsearchInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.DescribeReservedElasticsearchInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#describereservedelasticsearchinstancespaginator)
         """
 
 class GetUpgradeHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.GetUpgradeHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#getupgradehistorypaginator)
     """
 
     def paginate(
-        self, *, DomainName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DomainName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetUpgradeHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.GetUpgradeHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#getupgradehistorypaginator)
         """
 
 class ListElasticsearchInstanceTypesPaginator(AioPaginator):
@@ -119,27 +113,27 @@
     """
 
     def paginate(
         self,
         *,
         ElasticsearchVersion: str,
         DomainName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListElasticsearchInstanceTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.ListElasticsearchInstanceTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#listelasticsearchinstancetypespaginator)
         """
 
 class ListElasticsearchVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.ListElasticsearchVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#listelasticsearchversionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListElasticsearchVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService.Paginator.ListElasticsearchVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/paginators/#listelasticsearchversionspaginator)
         """
```

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/type_defs.py` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -51,15 +51,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "OptionStatusTypeDef",
     "TagTypeDef",
     "AdditionalLimitTypeDef",
     "MasterUserOptionsTypeDef",
     "AssociatePackageRequestRequestTypeDef",
     "AuthorizeVpcEndpointAccessRequestRequestTypeDef",
     "AuthorizedPrincipalTypeDef",
@@ -94,56 +93,62 @@
     "DescribeDomainChangeProgressRequestRequestTypeDef",
     "DescribeElasticsearchDomainConfigRequestRequestTypeDef",
     "DescribeElasticsearchDomainRequestRequestTypeDef",
     "DescribeElasticsearchDomainsRequestRequestTypeDef",
     "DescribeElasticsearchInstanceTypeLimitsRequestRequestTypeDef",
     "FilterTypeDef",
     "DescribePackagesFilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
     "DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef",
+    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
     "DescribeReservedElasticsearchInstancesRequestRequestTypeDef",
     "DescribeVpcEndpointsRequestRequestTypeDef",
     "VpcEndpointErrorTypeDef",
     "DissociatePackageRequestRequestTypeDef",
     "DomainInfoTypeDef",
     "ErrorDetailsTypeDef",
     "DryRunResultsTypeDef",
     "ZoneAwarenessConfigTypeDef",
     "VPCDerivedInfoTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCompatibleElasticsearchVersionsRequestRequestTypeDef",
     "GetPackageVersionHistoryRequestRequestTypeDef",
     "PackageVersionHistoryTypeDef",
+    "GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
     "GetUpgradeHistoryRequestRequestTypeDef",
     "GetUpgradeStatusRequestRequestTypeDef",
+    "GetUpgradeStatusResponseTypeDef",
     "InboundCrossClusterSearchConnectionStatusTypeDef",
     "InstanceCountLimitsTypeDef",
     "ListDomainNamesRequestRequestTypeDef",
     "ListDomainsForPackageRequestRequestTypeDef",
+    "ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
     "ListElasticsearchInstanceTypesRequestRequestTypeDef",
+    "ListElasticsearchInstanceTypesResponseTypeDef",
+    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
     "ListElasticsearchVersionsRequestRequestTypeDef",
+    "ListElasticsearchVersionsResponseTypeDef",
     "ListPackagesForDomainRequestRequestTypeDef",
     "ListTagsRequestRequestTypeDef",
     "ListVpcEndpointAccessRequestRequestTypeDef",
     "ListVpcEndpointsForDomainRequestRequestTypeDef",
     "ListVpcEndpointsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef",
+    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
     "RecurringChargeTypeDef",
     "RejectInboundCrossClusterSearchConnectionRequestRequestTypeDef",
     "RemoveTagsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     "SAMLIdpTypeDef",
     "StartElasticsearchServiceSoftwareUpdateRequestRequestTypeDef",
     "StorageTypeLimitTypeDef",
     "UpgradeElasticsearchDomainRequestRequestTypeDef",
     "UpgradeStepItemTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetUpgradeStatusResponseTypeDef",
-    "ListElasticsearchInstanceTypesResponseTypeDef",
-    "ListElasticsearchVersionsResponseTypeDef",
-    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
     "AccessPoliciesStatusTypeDef",
     "AdvancedOptionsStatusTypeDef",
     "ElasticsearchVersionStatusTypeDef",
     "AddTagsRequestRequestTypeDef",
     "ListTagsResponseTypeDef",
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     "ListVpcEndpointAccessResponseTypeDef",
@@ -170,19 +175,14 @@
     "UpdatePackageRequestRequestTypeDef",
     "DeleteVpcEndpointResponseTypeDef",
     "ListVpcEndpointsForDomainResponseTypeDef",
     "ListVpcEndpointsResponseTypeDef",
     "DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef",
     "DescribeOutboundCrossClusterSearchConnectionsRequestRequestTypeDef",
     "DescribePackagesRequestRequestTypeDef",
-    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
-    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
-    "GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
-    "ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
-    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
     "ListDomainNamesResponseTypeDef",
     "DomainPackageDetailsTypeDef",
     "PackageDetailsTypeDef",
     "ElasticsearchClusterConfigTypeDef",
     "VPCDerivedInfoStatusTypeDef",
     "VpcEndpointTypeDef",
     "GetPackageVersionHistoryResponseTypeDef",
@@ -241,25 +241,14 @@
 AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef = TypedDict(
     "AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef",
     {
         "CrossClusterSearchConnectionId": str,
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
 _RequiredOptionStatusTypeDef = TypedDict(
     "_RequiredOptionStatusTypeDef",
     {
         "CreationDate": datetime,
         "UpdateDate": datetime,
         "State": OptionStateType,
     },
@@ -707,34 +696,42 @@
     {
         "Name": DescribePackagesFilterNameType,
         "Value": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ReservedElasticsearchInstanceOfferingId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef",
     {
         "ReservedElasticsearchInstanceOfferingId": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef = TypedDict(
+    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
+    {
+        "ReservedElasticsearchInstanceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedElasticsearchInstancesRequestRequestTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstancesRequestRequestTypeDef",
     {
         "ReservedElasticsearchInstanceId": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -808,14 +805,21 @@
         "SubnetIds": List[str],
         "AvailabilityZones": List[str],
         "SecurityGroupIds": List[str],
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
 GetCompatibleElasticsearchVersionsRequestRequestTypeDef = TypedDict(
     "GetCompatibleElasticsearchVersionsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
@@ -849,14 +853,36 @@
         "PackageVersion": str,
         "CommitMessage": str,
         "CreatedAt": datetime,
     },
     total=False,
 )
 
+_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef(
+    _RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
+    _OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetUpgradeHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetUpgradeHistoryRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalGetUpgradeHistoryRequestRequestTypeDef = TypedDict(
@@ -878,14 +904,24 @@
 GetUpgradeStatusRequestRequestTypeDef = TypedDict(
     "GetUpgradeStatusRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetUpgradeStatusResponseTypeDef = TypedDict(
+    "GetUpgradeStatusResponseTypeDef",
+    {
+        "UpgradeStep": UpgradeStepType,
+        "StepStatus": UpgradeStatusType,
+        "UpgradeName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InboundCrossClusterSearchConnectionStatusTypeDef = TypedDict(
     "InboundCrossClusterSearchConnectionStatusTypeDef",
     {
         "StatusCode": InboundCrossClusterSearchConnectionStatusCodeType,
         "Message": str,
     },
     total=False,
@@ -927,14 +963,37 @@
 class ListDomainsForPackageRequestRequestTypeDef(
     _RequiredListDomainsForPackageRequestRequestTypeDef,
     _OptionalListDomainsForPackageRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
+    "_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
+    {
+        "ElasticsearchVersion": str,
+    },
+)
+_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
+    "_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
+    {
+        "DomainName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef(
+    _RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
+    _OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListElasticsearchInstanceTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListElasticsearchInstanceTypesRequestRequestTypeDef",
     {
         "ElasticsearchVersion": str,
     },
 )
 _OptionalListElasticsearchInstanceTypesRequestRequestTypeDef = TypedDict(
@@ -951,23 +1010,49 @@
 class ListElasticsearchInstanceTypesRequestRequestTypeDef(
     _RequiredListElasticsearchInstanceTypesRequestRequestTypeDef,
     _OptionalListElasticsearchInstanceTypesRequestRequestTypeDef,
 ):
     pass
 
 
+ListElasticsearchInstanceTypesResponseTypeDef = TypedDict(
+    "ListElasticsearchInstanceTypesResponseTypeDef",
+    {
+        "ElasticsearchInstanceTypes": List[ESPartitionInstanceTypeType],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef = TypedDict(
+    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListElasticsearchVersionsRequestRequestTypeDef = TypedDict(
     "ListElasticsearchVersionsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListElasticsearchVersionsResponseTypeDef = TypedDict(
+    "ListElasticsearchVersionsResponseTypeDef",
+    {
+        "ElasticsearchVersions": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListPackagesForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListPackagesForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListPackagesForDomainRequestRequestTypeDef = TypedDict(
@@ -1042,14 +1127,24 @@
     "ListVpcEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
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
 _RequiredPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef",
     {
         "ReservedElasticsearchInstanceOfferingId": str,
         "ReservationName": str,
     },
 )
@@ -1065,14 +1160,23 @@
 class PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef(
     _RequiredPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
     _OptionalPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
 ):
     pass
 
 
+PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef = TypedDict(
+    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
+    {
+        "ReservedElasticsearchInstanceId": str,
+        "ReservationName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "RecurringChargeAmount": float,
         "RecurringChargeFrequency": str,
     },
     total=False,
@@ -1089,14 +1193,25 @@
     "RemoveTagsRequestRequestTypeDef",
     {
         "ARN": str,
         "TagKeys": Sequence[str],
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
 RevokeVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     {
         "DomainName": str,
         "Account": str,
     },
 )
@@ -1155,58 +1270,14 @@
         "UpgradeStepStatus": UpgradeStatusType,
         "Issues": List[str],
         "ProgressPercent": float,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUpgradeStatusResponseTypeDef = TypedDict(
-    "GetUpgradeStatusResponseTypeDef",
-    {
-        "UpgradeStep": UpgradeStepType,
-        "StepStatus": UpgradeStatusType,
-        "UpgradeName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListElasticsearchInstanceTypesResponseTypeDef = TypedDict(
-    "ListElasticsearchInstanceTypesResponseTypeDef",
-    {
-        "ElasticsearchInstanceTypes": List[ESPartitionInstanceTypeType],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListElasticsearchVersionsResponseTypeDef = TypedDict(
-    "ListElasticsearchVersionsResponseTypeDef",
-    {
-        "ElasticsearchVersions": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef = TypedDict(
-    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
-    {
-        "ReservedElasticsearchInstanceId": str,
-        "ReservationName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AccessPoliciesStatusTypeDef = TypedDict(
     "AccessPoliciesStatusTypeDef",
     {
         "Options": str,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -1235,32 +1306,32 @@
     },
 )
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthorizeVpcEndpointAccessResponseTypeDef = TypedDict(
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipal": AuthorizedPrincipalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointAccessResponseTypeDef = TypedDict(
     "ListVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipalList": List[AuthorizedPrincipalTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoTuneDetailsTypeDef = TypedDict(
     "AutoTuneDetailsTypeDef",
     {
         "ScheduledAutoTuneDetails": ScheduledAutoTuneDetailsTypeDef,
@@ -1278,34 +1349,34 @@
     total=False,
 )
 
 CancelElasticsearchServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "CancelElasticsearchServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartElasticsearchServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "StartElasticsearchServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpgradeElasticsearchDomainResponseTypeDef = TypedDict(
     "UpgradeElasticsearchDomainResponseTypeDef",
     {
         "DomainName": str,
         "TargetVersion": str,
         "PerformCheckOnly": bool,
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeProgressStatusDetailsTypeDef = TypedDict(
     "ChangeProgressStatusDetailsTypeDef",
     {
         "ChangeId": str,
@@ -1327,15 +1398,15 @@
     },
 )
 
 GetCompatibleElasticsearchVersionsResponseTypeDef = TypedDict(
     "GetCompatibleElasticsearchVersionsResponseTypeDef",
     {
         "CompatibleElasticsearchVersions": List[CompatibleVersionsMapTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainEndpointOptionsStatusTypeDef = TypedDict(
     "DomainEndpointOptionsStatusTypeDef",
     {
         "Options": DomainEndpointOptionsTypeDef,
@@ -1427,15 +1498,15 @@
     "CreateOutboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "SourceDomainInfo": DomainInformationTypeDef,
         "DestinationDomainInfo": DomainInformationTypeDef,
         "ConnectionAlias": str,
         "ConnectionStatus": OutboundCrossClusterSearchConnectionStatusTypeDef,
         "CrossClusterSearchConnectionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OutboundCrossClusterSearchConnectionTypeDef = TypedDict(
     "OutboundCrossClusterSearchConnectionTypeDef",
     {
         "SourceDomainInfo": DomainInformationTypeDef,
@@ -1493,33 +1564,33 @@
     pass
 
 
 DeleteVpcEndpointResponseTypeDef = TypedDict(
     "DeleteVpcEndpointResponseTypeDef",
     {
         "VpcEndpointSummary": VpcEndpointSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsForDomainResponseTypeDef = TypedDict(
     "ListVpcEndpointsForDomainResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsResponseTypeDef = TypedDict(
     "ListVpcEndpointsResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef = TypedDict(
     "DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
@@ -1545,90 +1616,19 @@
         "Filters": Sequence[DescribePackagesFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
-    {
-        "ReservedElasticsearchInstanceOfferingId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef = TypedDict(
-    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
-    {
-        "ReservedElasticsearchInstanceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
-    {
-        "DomainName": str,
-    },
-)
-_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef(
-    _RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-    _OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
-    "_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
-    {
-        "ElasticsearchVersion": str,
-    },
-)
-_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
-    "_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
-    {
-        "DomainName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef(
-    _RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-    _OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-):
-    pass
-
-
-ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef = TypedDict(
-    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDomainNamesResponseTypeDef = TypedDict(
     "ListDomainNamesResponseTypeDef",
     {
         "DomainNames": List[DomainInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainPackageDetailsTypeDef = TypedDict(
     "DomainPackageDetailsTypeDef",
     {
         "PackageID": str,
@@ -1701,15 +1701,15 @@
 
 GetPackageVersionHistoryResponseTypeDef = TypedDict(
     "GetPackageVersionHistoryResponseTypeDef",
     {
         "PackageID": str,
         "PackageVersionHistoryList": List[PackageVersionHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InboundCrossClusterSearchConnectionTypeDef = TypedDict(
     "InboundCrossClusterSearchConnectionTypeDef",
     {
         "SourceDomainInfo": DomainInformationTypeDef,
@@ -1838,99 +1838,99 @@
     total=False,
 )
 
 DescribeDomainChangeProgressResponseTypeDef = TypedDict(
     "DescribeDomainChangeProgressResponseTypeDef",
     {
         "ChangeProgressStatus": ChangeProgressStatusDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteOutboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "DeleteOutboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": OutboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOutboundCrossClusterSearchConnectionsResponseTypeDef = TypedDict(
     "DescribeOutboundCrossClusterSearchConnectionsResponseTypeDef",
     {
         "CrossClusterSearchConnections": List[OutboundCrossClusterSearchConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociatePackageResponseTypeDef = TypedDict(
     "AssociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DissociatePackageResponseTypeDef = TypedDict(
     "DissociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsForPackageResponseTypeDef = TypedDict(
     "ListDomainsForPackageResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesForDomainResponseTypeDef = TypedDict(
     "ListPackagesForDomainResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePackageResponseTypeDef = TypedDict(
     "CreatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageResponseTypeDef = TypedDict(
     "DeletePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackagesResponseTypeDef = TypedDict(
     "DescribePackagesResponseTypeDef",
     {
         "PackageDetailsList": List[PackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePackageResponseTypeDef = TypedDict(
     "UpdatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ElasticsearchClusterConfigStatusTypeDef = TypedDict(
     "ElasticsearchClusterConfigStatusTypeDef",
     {
         "Options": ElasticsearchClusterConfigTypeDef,
@@ -1938,85 +1938,85 @@
     },
 )
 
 CreateVpcEndpointResponseTypeDef = TypedDict(
     "CreateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcEndpointsResponseTypeDef = TypedDict(
     "DescribeVpcEndpointsResponseTypeDef",
     {
         "VpcEndpoints": List[VpcEndpointTypeDef],
         "VpcEndpointErrors": List[VpcEndpointErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcEndpointResponseTypeDef = TypedDict(
     "UpdateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptInboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "AcceptInboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": InboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "DeleteInboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": InboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundCrossClusterSearchConnectionsResponseTypeDef = TypedDict(
     "DescribeInboundCrossClusterSearchConnectionsResponseTypeDef",
     {
         "CrossClusterSearchConnections": List[InboundCrossClusterSearchConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectInboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "RejectInboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": InboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "ReservedElasticsearchInstanceOfferings": List[
             ReservedElasticsearchInstanceOfferingTypeDef
         ],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedElasticsearchInstancesResponseTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstancesResponseTypeDef",
     {
         "NextToken": str,
         "ReservedElasticsearchInstances": List[ReservedElasticsearchInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdvancedSecurityOptionsInputTypeDef = TypedDict(
     "AdvancedSecurityOptionsInputTypeDef",
     {
         "Enabled": bool,
@@ -2051,24 +2051,24 @@
 )
 
 GetUpgradeHistoryResponseTypeDef = TypedDict(
     "GetUpgradeHistoryResponseTypeDef",
     {
         "UpgradeHistories": List[UpgradeHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainAutoTunesResponseTypeDef = TypedDict(
     "DescribeDomainAutoTunesResponseTypeDef",
     {
         "AutoTunes": List[AutoTuneTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoTuneOptionsStatusTypeDef = TypedDict(
     "AutoTuneOptionsStatusTypeDef",
     {
         "Options": AutoTuneOptionsTypeDef,
@@ -2200,15 +2200,15 @@
     pass
 
 
 DescribeElasticsearchInstanceTypeLimitsResponseTypeDef = TypedDict(
     "DescribeElasticsearchInstanceTypeLimitsResponseTypeDef",
     {
         "LimitsByRole": Dict[str, LimitsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ElasticsearchDomainConfigTypeDef = TypedDict(
     "ElasticsearchDomainConfigTypeDef",
     {
         "ElasticsearchVersion": ElasticsearchVersionStatusTypeDef,
@@ -2230,51 +2230,51 @@
     total=False,
 )
 
 CreateElasticsearchDomainResponseTypeDef = TypedDict(
     "CreateElasticsearchDomainResponseTypeDef",
     {
         "DomainStatus": ElasticsearchDomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteElasticsearchDomainResponseTypeDef = TypedDict(
     "DeleteElasticsearchDomainResponseTypeDef",
     {
         "DomainStatus": ElasticsearchDomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticsearchDomainResponseTypeDef = TypedDict(
     "DescribeElasticsearchDomainResponseTypeDef",
     {
         "DomainStatus": ElasticsearchDomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticsearchDomainsResponseTypeDef = TypedDict(
     "DescribeElasticsearchDomainsResponseTypeDef",
     {
         "DomainStatusList": List[ElasticsearchDomainStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticsearchDomainConfigResponseTypeDef = TypedDict(
     "DescribeElasticsearchDomainConfigResponseTypeDef",
     {
         "DomainConfig": ElasticsearchDomainConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateElasticsearchDomainConfigResponseTypeDef = TypedDict(
     "UpdateElasticsearchDomainConfigResponseTypeDef",
     {
         "DomainConfig": ElasticsearchDomainConfigTypeDef,
         "DryRunResults": DryRunResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es/type_defs.pyi` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -50,15 +50,14 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "OptionStatusTypeDef",
     "TagTypeDef",
     "AdditionalLimitTypeDef",
     "MasterUserOptionsTypeDef",
     "AssociatePackageRequestRequestTypeDef",
     "AuthorizeVpcEndpointAccessRequestRequestTypeDef",
     "AuthorizedPrincipalTypeDef",
@@ -93,56 +92,62 @@
     "DescribeDomainChangeProgressRequestRequestTypeDef",
     "DescribeElasticsearchDomainConfigRequestRequestTypeDef",
     "DescribeElasticsearchDomainRequestRequestTypeDef",
     "DescribeElasticsearchDomainsRequestRequestTypeDef",
     "DescribeElasticsearchInstanceTypeLimitsRequestRequestTypeDef",
     "FilterTypeDef",
     "DescribePackagesFilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
     "DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef",
+    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
     "DescribeReservedElasticsearchInstancesRequestRequestTypeDef",
     "DescribeVpcEndpointsRequestRequestTypeDef",
     "VpcEndpointErrorTypeDef",
     "DissociatePackageRequestRequestTypeDef",
     "DomainInfoTypeDef",
     "ErrorDetailsTypeDef",
     "DryRunResultsTypeDef",
     "ZoneAwarenessConfigTypeDef",
     "VPCDerivedInfoTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCompatibleElasticsearchVersionsRequestRequestTypeDef",
     "GetPackageVersionHistoryRequestRequestTypeDef",
     "PackageVersionHistoryTypeDef",
+    "GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
     "GetUpgradeHistoryRequestRequestTypeDef",
     "GetUpgradeStatusRequestRequestTypeDef",
+    "GetUpgradeStatusResponseTypeDef",
     "InboundCrossClusterSearchConnectionStatusTypeDef",
     "InstanceCountLimitsTypeDef",
     "ListDomainNamesRequestRequestTypeDef",
     "ListDomainsForPackageRequestRequestTypeDef",
+    "ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
     "ListElasticsearchInstanceTypesRequestRequestTypeDef",
+    "ListElasticsearchInstanceTypesResponseTypeDef",
+    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
     "ListElasticsearchVersionsRequestRequestTypeDef",
+    "ListElasticsearchVersionsResponseTypeDef",
     "ListPackagesForDomainRequestRequestTypeDef",
     "ListTagsRequestRequestTypeDef",
     "ListVpcEndpointAccessRequestRequestTypeDef",
     "ListVpcEndpointsForDomainRequestRequestTypeDef",
     "ListVpcEndpointsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef",
+    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
     "RecurringChargeTypeDef",
     "RejectInboundCrossClusterSearchConnectionRequestRequestTypeDef",
     "RemoveTagsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     "SAMLIdpTypeDef",
     "StartElasticsearchServiceSoftwareUpdateRequestRequestTypeDef",
     "StorageTypeLimitTypeDef",
     "UpgradeElasticsearchDomainRequestRequestTypeDef",
     "UpgradeStepItemTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetUpgradeStatusResponseTypeDef",
-    "ListElasticsearchInstanceTypesResponseTypeDef",
-    "ListElasticsearchVersionsResponseTypeDef",
-    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
     "AccessPoliciesStatusTypeDef",
     "AdvancedOptionsStatusTypeDef",
     "ElasticsearchVersionStatusTypeDef",
     "AddTagsRequestRequestTypeDef",
     "ListTagsResponseTypeDef",
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     "ListVpcEndpointAccessResponseTypeDef",
@@ -169,19 +174,14 @@
     "UpdatePackageRequestRequestTypeDef",
     "DeleteVpcEndpointResponseTypeDef",
     "ListVpcEndpointsForDomainResponseTypeDef",
     "ListVpcEndpointsResponseTypeDef",
     "DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef",
     "DescribeOutboundCrossClusterSearchConnectionsRequestRequestTypeDef",
     "DescribePackagesRequestRequestTypeDef",
-    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
-    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
-    "GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
-    "ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
-    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
     "ListDomainNamesResponseTypeDef",
     "DomainPackageDetailsTypeDef",
     "PackageDetailsTypeDef",
     "ElasticsearchClusterConfigTypeDef",
     "VPCDerivedInfoStatusTypeDef",
     "VpcEndpointTypeDef",
     "GetPackageVersionHistoryResponseTypeDef",
@@ -240,25 +240,14 @@
 AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef = TypedDict(
     "AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef",
     {
         "CrossClusterSearchConnectionId": str,
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
 _RequiredOptionStatusTypeDef = TypedDict(
     "_RequiredOptionStatusTypeDef",
     {
         "CreationDate": datetime,
         "UpdateDate": datetime,
         "State": OptionStateType,
     },
@@ -694,34 +683,42 @@
     {
         "Name": DescribePackagesFilterNameType,
         "Value": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ReservedElasticsearchInstanceOfferingId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef",
     {
         "ReservedElasticsearchInstanceOfferingId": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef = TypedDict(
+    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
+    {
+        "ReservedElasticsearchInstanceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedElasticsearchInstancesRequestRequestTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstancesRequestRequestTypeDef",
     {
         "ReservedElasticsearchInstanceId": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -795,14 +792,21 @@
         "SubnetIds": List[str],
         "AvailabilityZones": List[str],
         "SecurityGroupIds": List[str],
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
 GetCompatibleElasticsearchVersionsRequestRequestTypeDef = TypedDict(
     "GetCompatibleElasticsearchVersionsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
@@ -834,14 +838,34 @@
         "PackageVersion": str,
         "CommitMessage": str,
         "CreatedAt": datetime,
     },
     total=False,
 )
 
+_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef(
+    _RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
+    _OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetUpgradeHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetUpgradeHistoryRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalGetUpgradeHistoryRequestRequestTypeDef = TypedDict(
@@ -861,14 +885,24 @@
 GetUpgradeStatusRequestRequestTypeDef = TypedDict(
     "GetUpgradeStatusRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetUpgradeStatusResponseTypeDef = TypedDict(
+    "GetUpgradeStatusResponseTypeDef",
+    {
+        "UpgradeStep": UpgradeStepType,
+        "StepStatus": UpgradeStatusType,
+        "UpgradeName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InboundCrossClusterSearchConnectionStatusTypeDef = TypedDict(
     "InboundCrossClusterSearchConnectionStatusTypeDef",
     {
         "StatusCode": InboundCrossClusterSearchConnectionStatusCodeType,
         "Message": str,
     },
     total=False,
@@ -908,14 +942,35 @@
 
 class ListDomainsForPackageRequestRequestTypeDef(
     _RequiredListDomainsForPackageRequestRequestTypeDef,
     _OptionalListDomainsForPackageRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
+    "_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
+    {
+        "ElasticsearchVersion": str,
+    },
+)
+_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
+    "_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
+    {
+        "DomainName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef(
+    _RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
+    _OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
+):
+    pass
+
 _RequiredListElasticsearchInstanceTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListElasticsearchInstanceTypesRequestRequestTypeDef",
     {
         "ElasticsearchVersion": str,
     },
 )
 _OptionalListElasticsearchInstanceTypesRequestRequestTypeDef = TypedDict(
@@ -930,23 +985,49 @@
 
 class ListElasticsearchInstanceTypesRequestRequestTypeDef(
     _RequiredListElasticsearchInstanceTypesRequestRequestTypeDef,
     _OptionalListElasticsearchInstanceTypesRequestRequestTypeDef,
 ):
     pass
 
+ListElasticsearchInstanceTypesResponseTypeDef = TypedDict(
+    "ListElasticsearchInstanceTypesResponseTypeDef",
+    {
+        "ElasticsearchInstanceTypes": List[ESPartitionInstanceTypeType],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef = TypedDict(
+    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListElasticsearchVersionsRequestRequestTypeDef = TypedDict(
     "ListElasticsearchVersionsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListElasticsearchVersionsResponseTypeDef = TypedDict(
+    "ListElasticsearchVersionsResponseTypeDef",
+    {
+        "ElasticsearchVersions": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListPackagesForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListPackagesForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListPackagesForDomainRequestRequestTypeDef = TypedDict(
@@ -1015,14 +1096,24 @@
     "ListVpcEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
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
 _RequiredPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef",
     {
         "ReservedElasticsearchInstanceOfferingId": str,
         "ReservationName": str,
     },
 )
@@ -1036,14 +1127,23 @@
 
 class PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef(
     _RequiredPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
     _OptionalPurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
 ):
     pass
 
+PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef = TypedDict(
+    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
+    {
+        "ReservedElasticsearchInstanceId": str,
+        "ReservationName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "RecurringChargeAmount": float,
         "RecurringChargeFrequency": str,
     },
     total=False,
@@ -1060,14 +1160,25 @@
     "RemoveTagsRequestRequestTypeDef",
     {
         "ARN": str,
         "TagKeys": Sequence[str],
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
 RevokeVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     {
         "DomainName": str,
         "Account": str,
     },
 )
@@ -1124,58 +1235,14 @@
         "UpgradeStepStatus": UpgradeStatusType,
         "Issues": List[str],
         "ProgressPercent": float,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUpgradeStatusResponseTypeDef = TypedDict(
-    "GetUpgradeStatusResponseTypeDef",
-    {
-        "UpgradeStep": UpgradeStepType,
-        "StepStatus": UpgradeStatusType,
-        "UpgradeName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListElasticsearchInstanceTypesResponseTypeDef = TypedDict(
-    "ListElasticsearchInstanceTypesResponseTypeDef",
-    {
-        "ElasticsearchInstanceTypes": List[ESPartitionInstanceTypeType],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListElasticsearchVersionsResponseTypeDef = TypedDict(
-    "ListElasticsearchVersionsResponseTypeDef",
-    {
-        "ElasticsearchVersions": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef = TypedDict(
-    "PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef",
-    {
-        "ReservedElasticsearchInstanceId": str,
-        "ReservationName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AccessPoliciesStatusTypeDef = TypedDict(
     "AccessPoliciesStatusTypeDef",
     {
         "Options": str,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -1204,32 +1271,32 @@
     },
 )
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthorizeVpcEndpointAccessResponseTypeDef = TypedDict(
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipal": AuthorizedPrincipalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointAccessResponseTypeDef = TypedDict(
     "ListVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipalList": List[AuthorizedPrincipalTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoTuneDetailsTypeDef = TypedDict(
     "AutoTuneDetailsTypeDef",
     {
         "ScheduledAutoTuneDetails": ScheduledAutoTuneDetailsTypeDef,
@@ -1247,34 +1314,34 @@
     total=False,
 )
 
 CancelElasticsearchServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "CancelElasticsearchServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartElasticsearchServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "StartElasticsearchServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpgradeElasticsearchDomainResponseTypeDef = TypedDict(
     "UpgradeElasticsearchDomainResponseTypeDef",
     {
         "DomainName": str,
         "TargetVersion": str,
         "PerformCheckOnly": bool,
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeProgressStatusDetailsTypeDef = TypedDict(
     "ChangeProgressStatusDetailsTypeDef",
     {
         "ChangeId": str,
@@ -1296,15 +1363,15 @@
     },
 )
 
 GetCompatibleElasticsearchVersionsResponseTypeDef = TypedDict(
     "GetCompatibleElasticsearchVersionsResponseTypeDef",
     {
         "CompatibleElasticsearchVersions": List[CompatibleVersionsMapTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainEndpointOptionsStatusTypeDef = TypedDict(
     "DomainEndpointOptionsStatusTypeDef",
     {
         "Options": DomainEndpointOptionsTypeDef,
@@ -1394,15 +1461,15 @@
     "CreateOutboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "SourceDomainInfo": DomainInformationTypeDef,
         "DestinationDomainInfo": DomainInformationTypeDef,
         "ConnectionAlias": str,
         "ConnectionStatus": OutboundCrossClusterSearchConnectionStatusTypeDef,
         "CrossClusterSearchConnectionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OutboundCrossClusterSearchConnectionTypeDef = TypedDict(
     "OutboundCrossClusterSearchConnectionTypeDef",
     {
         "SourceDomainInfo": DomainInformationTypeDef,
@@ -1456,33 +1523,33 @@
 ):
     pass
 
 DeleteVpcEndpointResponseTypeDef = TypedDict(
     "DeleteVpcEndpointResponseTypeDef",
     {
         "VpcEndpointSummary": VpcEndpointSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsForDomainResponseTypeDef = TypedDict(
     "ListVpcEndpointsForDomainResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsResponseTypeDef = TypedDict(
     "ListVpcEndpointsResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef = TypedDict(
     "DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
@@ -1508,86 +1575,19 @@
         "Filters": Sequence[DescribePackagesFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef",
-    {
-        "ReservedElasticsearchInstanceOfferingId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef = TypedDict(
-    "DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef",
-    {
-        "ReservedElasticsearchInstanceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
-    {
-        "DomainName": str,
-    },
-)
-_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef(
-    _RequiredGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-    _OptionalGetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-):
-    pass
-
-_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
-    "_RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
-    {
-        "ElasticsearchVersion": str,
-    },
-)
-_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef = TypedDict(
-    "_OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef",
-    {
-        "DomainName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef(
-    _RequiredListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-    _OptionalListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-):
-    pass
-
-ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef = TypedDict(
-    "ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDomainNamesResponseTypeDef = TypedDict(
     "ListDomainNamesResponseTypeDef",
     {
         "DomainNames": List[DomainInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainPackageDetailsTypeDef = TypedDict(
     "DomainPackageDetailsTypeDef",
     {
         "PackageID": str,
@@ -1660,15 +1660,15 @@
 
 GetPackageVersionHistoryResponseTypeDef = TypedDict(
     "GetPackageVersionHistoryResponseTypeDef",
     {
         "PackageID": str,
         "PackageVersionHistoryList": List[PackageVersionHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InboundCrossClusterSearchConnectionTypeDef = TypedDict(
     "InboundCrossClusterSearchConnectionTypeDef",
     {
         "SourceDomainInfo": DomainInformationTypeDef,
@@ -1797,99 +1797,99 @@
     total=False,
 )
 
 DescribeDomainChangeProgressResponseTypeDef = TypedDict(
     "DescribeDomainChangeProgressResponseTypeDef",
     {
         "ChangeProgressStatus": ChangeProgressStatusDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteOutboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "DeleteOutboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": OutboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOutboundCrossClusterSearchConnectionsResponseTypeDef = TypedDict(
     "DescribeOutboundCrossClusterSearchConnectionsResponseTypeDef",
     {
         "CrossClusterSearchConnections": List[OutboundCrossClusterSearchConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociatePackageResponseTypeDef = TypedDict(
     "AssociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DissociatePackageResponseTypeDef = TypedDict(
     "DissociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsForPackageResponseTypeDef = TypedDict(
     "ListDomainsForPackageResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesForDomainResponseTypeDef = TypedDict(
     "ListPackagesForDomainResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePackageResponseTypeDef = TypedDict(
     "CreatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageResponseTypeDef = TypedDict(
     "DeletePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackagesResponseTypeDef = TypedDict(
     "DescribePackagesResponseTypeDef",
     {
         "PackageDetailsList": List[PackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePackageResponseTypeDef = TypedDict(
     "UpdatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ElasticsearchClusterConfigStatusTypeDef = TypedDict(
     "ElasticsearchClusterConfigStatusTypeDef",
     {
         "Options": ElasticsearchClusterConfigTypeDef,
@@ -1897,85 +1897,85 @@
     },
 )
 
 CreateVpcEndpointResponseTypeDef = TypedDict(
     "CreateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcEndpointsResponseTypeDef = TypedDict(
     "DescribeVpcEndpointsResponseTypeDef",
     {
         "VpcEndpoints": List[VpcEndpointTypeDef],
         "VpcEndpointErrors": List[VpcEndpointErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcEndpointResponseTypeDef = TypedDict(
     "UpdateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptInboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "AcceptInboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": InboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "DeleteInboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": InboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundCrossClusterSearchConnectionsResponseTypeDef = TypedDict(
     "DescribeInboundCrossClusterSearchConnectionsResponseTypeDef",
     {
         "CrossClusterSearchConnections": List[InboundCrossClusterSearchConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectInboundCrossClusterSearchConnectionResponseTypeDef = TypedDict(
     "RejectInboundCrossClusterSearchConnectionResponseTypeDef",
     {
         "CrossClusterSearchConnection": InboundCrossClusterSearchConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstanceOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "ReservedElasticsearchInstanceOfferings": List[
             ReservedElasticsearchInstanceOfferingTypeDef
         ],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedElasticsearchInstancesResponseTypeDef = TypedDict(
     "DescribeReservedElasticsearchInstancesResponseTypeDef",
     {
         "NextToken": str,
         "ReservedElasticsearchInstances": List[ReservedElasticsearchInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdvancedSecurityOptionsInputTypeDef = TypedDict(
     "AdvancedSecurityOptionsInputTypeDef",
     {
         "Enabled": bool,
@@ -2010,24 +2010,24 @@
 )
 
 GetUpgradeHistoryResponseTypeDef = TypedDict(
     "GetUpgradeHistoryResponseTypeDef",
     {
         "UpgradeHistories": List[UpgradeHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainAutoTunesResponseTypeDef = TypedDict(
     "DescribeDomainAutoTunesResponseTypeDef",
     {
         "AutoTunes": List[AutoTuneTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoTuneOptionsStatusTypeDef = TypedDict(
     "AutoTuneOptionsStatusTypeDef",
     {
         "Options": AutoTuneOptionsTypeDef,
@@ -2153,15 +2153,15 @@
 ):
     pass
 
 DescribeElasticsearchInstanceTypeLimitsResponseTypeDef = TypedDict(
     "DescribeElasticsearchInstanceTypeLimitsResponseTypeDef",
     {
         "LimitsByRole": Dict[str, LimitsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ElasticsearchDomainConfigTypeDef = TypedDict(
     "ElasticsearchDomainConfigTypeDef",
     {
         "ElasticsearchVersion": ElasticsearchVersionStatusTypeDef,
@@ -2183,51 +2183,51 @@
     total=False,
 )
 
 CreateElasticsearchDomainResponseTypeDef = TypedDict(
     "CreateElasticsearchDomainResponseTypeDef",
     {
         "DomainStatus": ElasticsearchDomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteElasticsearchDomainResponseTypeDef = TypedDict(
     "DeleteElasticsearchDomainResponseTypeDef",
     {
         "DomainStatus": ElasticsearchDomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticsearchDomainResponseTypeDef = TypedDict(
     "DescribeElasticsearchDomainResponseTypeDef",
     {
         "DomainStatus": ElasticsearchDomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticsearchDomainsResponseTypeDef = TypedDict(
     "DescribeElasticsearchDomainsResponseTypeDef",
     {
         "DomainStatusList": List[ElasticsearchDomainStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticsearchDomainConfigResponseTypeDef = TypedDict(
     "DescribeElasticsearchDomainConfigResponseTypeDef",
     {
         "DomainConfig": ElasticsearchDomainConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateElasticsearchDomainConfigResponseTypeDef = TypedDict(
     "UpdateElasticsearchDomainConfigResponseTypeDef",
     {
         "DomainConfig": ElasticsearchDomainConfigTypeDef,
         "DryRunResults": DryRunResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/PKG-INFO` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-es
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticsearchService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticsearchService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-es"></a>
 
 # types-aiobotocore-es
 
 [![PyPI - types-aiobotocore-es](https://img.shields.io/pypi/v/types-aiobotocore-es.svg?color=blue)](https://pypi.org/project/types-aiobotocore-es)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-es.svg?color=blue)](https://pypi.org/project/types-aiobotocore-es)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-es?color=blue)](https://pypistats.org/packages/types-aiobotocore-es)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticsearchService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService)
+[aiobotocore.ElasticsearchService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/es.html#ElasticsearchService)
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
 [types-aiobotocore-es docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_es/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,15 +366,14 @@
 
 `types_aiobotocore_es.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_es.type_defs import (
     AcceptInboundCrossClusterSearchConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     OptionStatusTypeDef,
     TagTypeDef,
     AdditionalLimitTypeDef,
     MasterUserOptionsTypeDef,
     AssociatePackageRequestRequestTypeDef,
     AuthorizeVpcEndpointAccessRequestRequestTypeDef,
     AuthorizedPrincipalTypeDef,
@@ -409,56 +408,62 @@
     DescribeDomainChangeProgressRequestRequestTypeDef,
     DescribeElasticsearchDomainConfigRequestRequestTypeDef,
     DescribeElasticsearchDomainRequestRequestTypeDef,
     DescribeElasticsearchDomainsRequestRequestTypeDef,
     DescribeElasticsearchInstanceTypeLimitsRequestRequestTypeDef,
     FilterTypeDef,
     DescribePackagesFilterTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef,
     DescribeReservedElasticsearchInstanceOfferingsRequestRequestTypeDef,
+    DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef,
     DescribeReservedElasticsearchInstancesRequestRequestTypeDef,
     DescribeVpcEndpointsRequestRequestTypeDef,
     VpcEndpointErrorTypeDef,
     DissociatePackageRequestRequestTypeDef,
     DomainInfoTypeDef,
     ErrorDetailsTypeDef,
     DryRunResultsTypeDef,
     ZoneAwarenessConfigTypeDef,
     VPCDerivedInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCompatibleElasticsearchVersionsRequestRequestTypeDef,
     GetPackageVersionHistoryRequestRequestTypeDef,
     PackageVersionHistoryTypeDef,
+    GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
     GetUpgradeHistoryRequestRequestTypeDef,
     GetUpgradeStatusRequestRequestTypeDef,
+    GetUpgradeStatusResponseTypeDef,
     InboundCrossClusterSearchConnectionStatusTypeDef,
     InstanceCountLimitsTypeDef,
     ListDomainNamesRequestRequestTypeDef,
     ListDomainsForPackageRequestRequestTypeDef,
+    ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
     ListElasticsearchInstanceTypesRequestRequestTypeDef,
+    ListElasticsearchInstanceTypesResponseTypeDef,
+    ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef,
     ListElasticsearchVersionsRequestRequestTypeDef,
+    ListElasticsearchVersionsResponseTypeDef,
     ListPackagesForDomainRequestRequestTypeDef,
     ListTagsRequestRequestTypeDef,
     ListVpcEndpointAccessRequestRequestTypeDef,
     ListVpcEndpointsForDomainRequestRequestTypeDef,
     ListVpcEndpointsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseReservedElasticsearchInstanceOfferingRequestRequestTypeDef,
+    PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef,
     RecurringChargeTypeDef,
     RejectInboundCrossClusterSearchConnectionRequestRequestTypeDef,
     RemoveTagsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeVpcEndpointAccessRequestRequestTypeDef,
     SAMLIdpTypeDef,
     StartElasticsearchServiceSoftwareUpdateRequestRequestTypeDef,
     StorageTypeLimitTypeDef,
     UpgradeElasticsearchDomainRequestRequestTypeDef,
     UpgradeStepItemTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetUpgradeStatusResponseTypeDef,
-    ListElasticsearchInstanceTypesResponseTypeDef,
-    ListElasticsearchVersionsResponseTypeDef,
-    PurchaseReservedElasticsearchInstanceOfferingResponseTypeDef,
     AccessPoliciesStatusTypeDef,
     AdvancedOptionsStatusTypeDef,
     ElasticsearchVersionStatusTypeDef,
     AddTagsRequestRequestTypeDef,
     ListTagsResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
@@ -485,19 +490,14 @@
     UpdatePackageRequestRequestTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
     DescribeInboundCrossClusterSearchConnectionsRequestRequestTypeDef,
     DescribeOutboundCrossClusterSearchConnectionsRequestRequestTypeDef,
     DescribePackagesRequestRequestTypeDef,
-    DescribeReservedElasticsearchInstanceOfferingsRequestDescribeReservedElasticsearchInstanceOfferingsPaginateTypeDef,
-    DescribeReservedElasticsearchInstancesRequestDescribeReservedElasticsearchInstancesPaginateTypeDef,
-    GetUpgradeHistoryRequestGetUpgradeHistoryPaginateTypeDef,
-    ListElasticsearchInstanceTypesRequestListElasticsearchInstanceTypesPaginateTypeDef,
-    ListElasticsearchVersionsRequestListElasticsearchVersionsPaginateTypeDef,
     ListDomainNamesResponseTypeDef,
     DomainPackageDetailsTypeDef,
     PackageDetailsTypeDef,
     ElasticsearchClusterConfigTypeDef,
     VPCDerivedInfoStatusTypeDef,
     VpcEndpointTypeDef,
     GetPackageVersionHistoryResponseTypeDef,
@@ -561,43 +561,43 @@
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

### Comparing `types-aiobotocore-es-2.5.0.post1/types_aiobotocore_es.egg-info/SOURCES.txt` & `types-aiobotocore-es-2.5.1/types_aiobotocore_es.egg-info/SOURCES.txt`

 * *Files identical despite different names*

