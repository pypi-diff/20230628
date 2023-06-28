# Comparing `tmp/types-aiobotocore-route53domains-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-route53domains-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-route53domains-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-route53domains-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-route53domains-2.5.0.post1.tar` & `types-aiobotocore-route53domains-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.939565 types-aiobotocore-route53domains-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17582 2023-03-11 12:27:13.939565 types-aiobotocore-route53domains-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15983 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.939565 types-aiobotocore-route53domains-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.939565 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/
--rw-r--r--   0 runner    (1001) docker     (123)     1237 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1236 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    30847 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    30800 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13023 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13021 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6183 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6176 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    27532 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    27511 2023-03-11 12:22:43.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:42.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.939565 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17582 2023-03-11 12:27:13.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:13.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:13.000000 types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.466204 types-aiobotocore-route53domains-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17581 2023-06-28 01:44:05.466204 types-aiobotocore-route53domains-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15988 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.466204 types-aiobotocore-route53domains-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.466204 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/
+-rw-r--r--   0 runner    (1001) docker     (123)     1237 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1236 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30855 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30808 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13232 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13230 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6084 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6077 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    27598 2023-06-28 01:39:31.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27577 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:30.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.466204 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17581 2023-06-28 01:44:05.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:44:05.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:05.000000 types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/LICENSE` & `types-aiobotocore-route53domains-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/PKG-INFO` & `types-aiobotocore-route53domains-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53domains
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53Domains 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53Domains 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53domains"></a>
 
 # types-aiobotocore-route53domains
 
 [![PyPI - types-aiobotocore-route53domains](https://img.shields.io/pypi/v/types-aiobotocore-route53domains.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53domains)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53domains.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53domains)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53domains?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53domains)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53Domains 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
+[aiobotocore.Route53Domains 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
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
 [types-aiobotocore-route53domains docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,88 +339,88 @@
 
 `types_aiobotocore_route53domains.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53domains.type_defs import (
     AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef,
     DnssecSigningAttributesTypeDef,
+    AssociateDelegationSignerToDomainResponseTypeDef,
     BillingRecordTypeDef,
     CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef,
+    CancelDomainTransferToAnotherAwsAccountResponseTypeDef,
     CheckDomainAvailabilityRequestRequestTypeDef,
+    CheckDomainAvailabilityResponseTypeDef,
     CheckDomainTransferabilityRequestRequestTypeDef,
     DomainTransferabilityTypeDef,
     ConsentTypeDef,
     ExtraParamTypeDef,
     DeleteDomainRequestRequestTypeDef,
+    DeleteDomainResponseTypeDef,
     DeleteTagsForDomainRequestRequestTypeDef,
     DisableDomainAutoRenewRequestRequestTypeDef,
     DisableDomainTransferLockRequestRequestTypeDef,
+    DisableDomainTransferLockResponseTypeDef,
     DisassociateDelegationSignerFromDomainRequestRequestTypeDef,
+    DisassociateDelegationSignerFromDomainResponseTypeDef,
     DnssecKeyTypeDef,
     PriceWithCurrencyTypeDef,
     DomainSuggestionTypeDef,
     DomainSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableDomainAutoRenewRequestRequestTypeDef,
     EnableDomainTransferLockRequestRequestTypeDef,
+    EnableDomainTransferLockResponseTypeDef,
     FilterConditionTypeDef,
     GetContactReachabilityStatusRequestRequestTypeDef,
+    GetContactReachabilityStatusResponseTypeDef,
     GetDomainDetailRequestRequestTypeDef,
     NameserverTypeDef,
     GetDomainSuggestionsRequestRequestTypeDef,
     GetOperationDetailRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetOperationDetailResponseTypeDef,
     SortConditionTypeDef,
+    ListOperationsRequestListOperationsPaginateTypeDef,
     ListOperationsRequestRequestTypeDef,
     OperationSummaryTypeDef,
+    ListPricesRequestListPricesPaginateTypeDef,
     ListPricesRequestRequestTypeDef,
     ListTagsForDomainRequestRequestTypeDef,
     TagTypeDef,
+    PaginatorConfigTypeDef,
     PushDomainRequestRequestTypeDef,
+    RegisterDomainResponseTypeDef,
     RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef,
+    RejectDomainTransferFromAnotherAwsAccountResponseTypeDef,
     RenewDomainRequestRequestTypeDef,
+    RenewDomainResponseTypeDef,
     ResendContactReachabilityEmailRequestRequestTypeDef,
+    ResendContactReachabilityEmailResponseTypeDef,
     ResendOperationAuthorizationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RetrieveDomainAuthCodeRequestRequestTypeDef,
-    TransferDomainToAnotherAwsAccountRequestRequestTypeDef,
-    UpdateDomainContactPrivacyRequestRequestTypeDef,
-    ViewBillingRequestRequestTypeDef,
-    AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef,
-    AssociateDelegationSignerToDomainResponseTypeDef,
-    CancelDomainTransferToAnotherAwsAccountResponseTypeDef,
-    CheckDomainAvailabilityResponseTypeDef,
-    DeleteDomainResponseTypeDef,
-    DisableDomainTransferLockResponseTypeDef,
-    DisassociateDelegationSignerFromDomainResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EnableDomainTransferLockResponseTypeDef,
-    GetContactReachabilityStatusResponseTypeDef,
-    GetOperationDetailResponseTypeDef,
-    RegisterDomainResponseTypeDef,
-    RejectDomainTransferFromAnotherAwsAccountResponseTypeDef,
-    RenewDomainResponseTypeDef,
-    ResendContactReachabilityEmailResponseTypeDef,
     RetrieveDomainAuthCodeResponseTypeDef,
     TransferDomainResponseTypeDef,
+    TransferDomainToAnotherAwsAccountRequestRequestTypeDef,
     TransferDomainToAnotherAwsAccountResponseTypeDef,
+    UpdateDomainContactPrivacyRequestRequestTypeDef,
     UpdateDomainContactPrivacyResponseTypeDef,
     UpdateDomainContactResponseTypeDef,
     UpdateDomainNameserversResponseTypeDef,
+    ViewBillingRequestRequestTypeDef,
+    ViewBillingRequestViewBillingPaginateTypeDef,
     AssociateDelegationSignerToDomainRequestRequestTypeDef,
     ViewBillingResponseTypeDef,
     CheckDomainTransferabilityResponseTypeDef,
     ContactDetailTypeDef,
     DomainPriceTypeDef,
     GetDomainSuggestionsResponseTypeDef,
     ListDomainsResponseTypeDef,
     UpdateDomainNameserversRequestRequestTypeDef,
-    ListOperationsRequestListOperationsPaginateTypeDef,
-    ListPricesRequestListPricesPaginateTypeDef,
-    ViewBillingRequestViewBillingPaginateTypeDef,
     ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListOperationsResponseTypeDef,
     ListTagsForDomainResponseTypeDef,
     UpdateTagsForDomainRequestRequestTypeDef,
     GetDomainDetailResponseTypeDef,
     RegisterDomainRequestRequestTypeDef,
@@ -437,43 +437,43 @@
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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/README.md` & `types-aiobotocore-route53domains-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-route53domains"></a>
 
 # types-aiobotocore-route53domains
 
 [![PyPI - types-aiobotocore-route53domains](https://img.shields.io/pypi/v/types-aiobotocore-route53domains.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53domains)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53domains.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53domains)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53domains?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53domains)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53Domains 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
+[aiobotocore.Route53Domains 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
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
 [types-aiobotocore-route53domains docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,88 +306,88 @@
 
 `types_aiobotocore_route53domains.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53domains.type_defs import (
     AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef,
     DnssecSigningAttributesTypeDef,
+    AssociateDelegationSignerToDomainResponseTypeDef,
     BillingRecordTypeDef,
     CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef,
+    CancelDomainTransferToAnotherAwsAccountResponseTypeDef,
     CheckDomainAvailabilityRequestRequestTypeDef,
+    CheckDomainAvailabilityResponseTypeDef,
     CheckDomainTransferabilityRequestRequestTypeDef,
     DomainTransferabilityTypeDef,
     ConsentTypeDef,
     ExtraParamTypeDef,
     DeleteDomainRequestRequestTypeDef,
+    DeleteDomainResponseTypeDef,
     DeleteTagsForDomainRequestRequestTypeDef,
     DisableDomainAutoRenewRequestRequestTypeDef,
     DisableDomainTransferLockRequestRequestTypeDef,
+    DisableDomainTransferLockResponseTypeDef,
     DisassociateDelegationSignerFromDomainRequestRequestTypeDef,
+    DisassociateDelegationSignerFromDomainResponseTypeDef,
     DnssecKeyTypeDef,
     PriceWithCurrencyTypeDef,
     DomainSuggestionTypeDef,
     DomainSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableDomainAutoRenewRequestRequestTypeDef,
     EnableDomainTransferLockRequestRequestTypeDef,
+    EnableDomainTransferLockResponseTypeDef,
     FilterConditionTypeDef,
     GetContactReachabilityStatusRequestRequestTypeDef,
+    GetContactReachabilityStatusResponseTypeDef,
     GetDomainDetailRequestRequestTypeDef,
     NameserverTypeDef,
     GetDomainSuggestionsRequestRequestTypeDef,
     GetOperationDetailRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetOperationDetailResponseTypeDef,
     SortConditionTypeDef,
+    ListOperationsRequestListOperationsPaginateTypeDef,
     ListOperationsRequestRequestTypeDef,
     OperationSummaryTypeDef,
+    ListPricesRequestListPricesPaginateTypeDef,
     ListPricesRequestRequestTypeDef,
     ListTagsForDomainRequestRequestTypeDef,
     TagTypeDef,
+    PaginatorConfigTypeDef,
     PushDomainRequestRequestTypeDef,
+    RegisterDomainResponseTypeDef,
     RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef,
+    RejectDomainTransferFromAnotherAwsAccountResponseTypeDef,
     RenewDomainRequestRequestTypeDef,
+    RenewDomainResponseTypeDef,
     ResendContactReachabilityEmailRequestRequestTypeDef,
+    ResendContactReachabilityEmailResponseTypeDef,
     ResendOperationAuthorizationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RetrieveDomainAuthCodeRequestRequestTypeDef,
-    TransferDomainToAnotherAwsAccountRequestRequestTypeDef,
-    UpdateDomainContactPrivacyRequestRequestTypeDef,
-    ViewBillingRequestRequestTypeDef,
-    AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef,
-    AssociateDelegationSignerToDomainResponseTypeDef,
-    CancelDomainTransferToAnotherAwsAccountResponseTypeDef,
-    CheckDomainAvailabilityResponseTypeDef,
-    DeleteDomainResponseTypeDef,
-    DisableDomainTransferLockResponseTypeDef,
-    DisassociateDelegationSignerFromDomainResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EnableDomainTransferLockResponseTypeDef,
-    GetContactReachabilityStatusResponseTypeDef,
-    GetOperationDetailResponseTypeDef,
-    RegisterDomainResponseTypeDef,
-    RejectDomainTransferFromAnotherAwsAccountResponseTypeDef,
-    RenewDomainResponseTypeDef,
-    ResendContactReachabilityEmailResponseTypeDef,
     RetrieveDomainAuthCodeResponseTypeDef,
     TransferDomainResponseTypeDef,
+    TransferDomainToAnotherAwsAccountRequestRequestTypeDef,
     TransferDomainToAnotherAwsAccountResponseTypeDef,
+    UpdateDomainContactPrivacyRequestRequestTypeDef,
     UpdateDomainContactPrivacyResponseTypeDef,
     UpdateDomainContactResponseTypeDef,
     UpdateDomainNameserversResponseTypeDef,
+    ViewBillingRequestRequestTypeDef,
+    ViewBillingRequestViewBillingPaginateTypeDef,
     AssociateDelegationSignerToDomainRequestRequestTypeDef,
     ViewBillingResponseTypeDef,
     CheckDomainTransferabilityResponseTypeDef,
     ContactDetailTypeDef,
     DomainPriceTypeDef,
     GetDomainSuggestionsResponseTypeDef,
     ListDomainsResponseTypeDef,
     UpdateDomainNameserversRequestRequestTypeDef,
-    ListOperationsRequestListOperationsPaginateTypeDef,
-    ListPricesRequestListPricesPaginateTypeDef,
-    ViewBillingRequestViewBillingPaginateTypeDef,
     ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListOperationsResponseTypeDef,
     ListTagsForDomainResponseTypeDef,
     UpdateTagsForDomainRequestRequestTypeDef,
     GetDomainDetailResponseTypeDef,
     RegisterDomainRequestRequestTypeDef,
@@ -404,43 +404,43 @@
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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/setup.py` & `types-aiobotocore-route53domains-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-route53domains.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-route53domains",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_route53domains"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Route53Domains 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Route53Domains 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/"
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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/__init__.py` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/__init__.pyi` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/client.py` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -340,17 +340,17 @@
         """
 
     async def list_prices(
         self, *, Tld: str = ..., Marker: str = ..., MaxItems: int = ...
     ) -> ListPricesResponseTypeDef:
         """
         Lists the following prices for either all the TLDs supported by Route 53, or the
-        specified TLD * Registration * Transfer * Owner change * Domain renewal * Domain
-        restoration See also: `AWS API Documentation
-        <https://docs.aws.amazon.com/goto/WebAPI/route53domains-2014-05-1...`.
+        specified TLD: * Registration * Transfer * Owner change * Domain renewal *
+        Domain restoration See also: `AWS API Documentation
+        <https://docs.aws.amazon.com/goto/WebAPI/route53domains-2014-05-15/ListP...`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Client.list_prices)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/client/#list_prices)
         """
 
     async def list_tags_for_domain(self, *, DomainName: str) -> ListTagsForDomainResponseTypeDef:
         """
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/client.pyi` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -314,17 +314,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/client/#list_operations)
         """
     async def list_prices(
         self, *, Tld: str = ..., Marker: str = ..., MaxItems: int = ...
     ) -> ListPricesResponseTypeDef:
         """
         Lists the following prices for either all the TLDs supported by Route 53, or the
-        specified TLD * Registration * Transfer * Owner change * Domain renewal * Domain
-        restoration See also: `AWS API Documentation
-        <https://docs.aws.amazon.com/goto/WebAPI/route53domains-2014-05-1...`.
+        specified TLD: * Registration * Transfer * Owner change * Domain renewal *
+        Domain restoration See also: `AWS API Documentation
+        <https://docs.aws.amazon.com/goto/WebAPI/route53domains-2014-05-15/ListP...`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Client.list_prices)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/client/#list_prices)
         """
     async def list_tags_for_domain(self, *, DomainName: str) -> ListTagsForDomainResponseTypeDef:
         """
         This operation returns all of the tags that are associated with the specified
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/literals.py` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ContactTypeType",
     "CountryCodeType",
     "DomainAvailabilityType",
     "ExtraParamNameType",
     "ListDomainsAttributeNameType",
     "ListDomainsPaginatorName",
@@ -40,15 +39,14 @@
     "Route53DomainsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ContactTypeType = Literal["ASSOCIATION", "COMPANY", "PERSON", "PUBLIC_BODY", "RESELLER"]
 CountryCodeType = Literal[
     "AC",
     "AD",
     "AE",
     "AF",
     "AG",
@@ -446,14 +444,15 @@
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
@@ -532,14 +531,15 @@
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
@@ -550,14 +550,15 @@
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
@@ -593,14 +594,15 @@
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
@@ -619,16 +621,19 @@
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
@@ -712,15 +717,17 @@
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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/literals.pyi` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ContactTypeType",
     "CountryCodeType",
     "DomainAvailabilityType",
     "ExtraParamNameType",
     "ListDomainsAttributeNameType",
     "ListDomainsPaginatorName",
@@ -39,14 +40,15 @@
     "Route53DomainsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ContactTypeType = Literal["ASSOCIATION", "COMPANY", "PERSON", "PUBLIC_BODY", "RESELLER"]
 CountryCodeType = Literal[
     "AC",
     "AD",
     "AE",
     "AF",
     "AG",
@@ -444,14 +446,15 @@
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
@@ -530,14 +533,15 @@
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
@@ -548,14 +552,15 @@
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
@@ -591,14 +596,15 @@
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
@@ -617,16 +623,19 @@
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
@@ -710,15 +719,17 @@
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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/paginator.py` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -24,15 +24,15 @@
         list_operations_paginator: ListOperationsPaginator = client.get_paginator("list_operations")
         list_prices_paginator: ListPricesPaginator = client.get_paginator("list_prices")
         view_billing_paginator: ViewBillingPaginator = client.get_paginator("view_billing")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import OperationStatusType, OperationTypeType, SortOrderType
 from .type_defs import (
     FilterConditionTypeDef,
@@ -40,108 +40,97 @@
     ListOperationsResponseTypeDef,
     ListPricesResponseTypeDef,
     PaginatorConfigTypeDef,
     SortConditionTypeDef,
     ViewBillingResponseTypeDef,
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
     "ListDomainsPaginator",
     "ListOperationsPaginator",
     "ListPricesPaginator",
     "ViewBillingPaginator",
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
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listdomainspaginator)
     """
 
     def paginate(
         self,
         *,
         FilterConditions: Sequence[FilterConditionTypeDef] = ...,
         SortCondition: SortConditionTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listdomainspaginator)
         """
 
-
 class ListOperationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListOperations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listoperationspaginator)
     """
 
     def paginate(
         self,
         *,
         SubmittedSince: Union[datetime, str] = ...,
         Status: Sequence[OperationStatusType] = ...,
         Type: Sequence[OperationTypeType] = ...,
         SortBy: Literal["SubmittedDate"] = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOperationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listoperationspaginator)
         """
 
-
 class ListPricesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListPrices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listpricespaginator)
     """
 
     def paginate(
-        self, *, Tld: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Tld: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListPrices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listpricespaginator)
         """
 
-
 class ViewBillingPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ViewBilling)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#viewbillingpaginator)
     """
 
     def paginate(
         self,
         *,
         Start: Union[datetime, str] = ...,
         End: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ViewBillingResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ViewBilling.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#viewbillingpaginator)
         """
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/paginator.pyi` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/paginator.py`

 * *Files 11% similar despite different names*

```diff
@@ -24,15 +24,15 @@
         list_operations_paginator: ListOperationsPaginator = client.get_paginator("list_operations")
         list_prices_paginator: ListPricesPaginator = client.get_paginator("list_prices")
         view_billing_paginator: ViewBillingPaginator = client.get_paginator("view_billing")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import OperationStatusType, OperationTypeType, SortOrderType
 from .type_defs import (
     FilterConditionTypeDef,
@@ -40,101 +40,104 @@
     ListOperationsResponseTypeDef,
     ListPricesResponseTypeDef,
     PaginatorConfigTypeDef,
     SortConditionTypeDef,
     ViewBillingResponseTypeDef,
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
     "ListDomainsPaginator",
     "ListOperationsPaginator",
     "ListPricesPaginator",
     "ViewBillingPaginator",
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
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listdomainspaginator)
     """
 
     def paginate(
         self,
         *,
         FilterConditions: Sequence[FilterConditionTypeDef] = ...,
         SortCondition: SortConditionTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listdomainspaginator)
         """
 
+
 class ListOperationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListOperations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listoperationspaginator)
     """
 
     def paginate(
         self,
         *,
         SubmittedSince: Union[datetime, str] = ...,
         Status: Sequence[OperationStatusType] = ...,
         Type: Sequence[OperationTypeType] = ...,
         SortBy: Literal["SubmittedDate"] = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOperationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listoperationspaginator)
         """
 
+
 class ListPricesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListPrices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listpricespaginator)
     """
 
     def paginate(
-        self, *, Tld: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Tld: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPricesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ListPrices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#listpricespaginator)
         """
 
+
 class ViewBillingPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ViewBilling)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#viewbillingpaginator)
     """
 
     def paginate(
         self,
         *,
         Start: Union[datetime, str] = ...,
         End: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ViewBillingResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains.Paginator.ViewBilling.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/paginators/#viewbillingpaginator)
         """
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/type_defs.py` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -38,88 +38,88 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
     "DnssecSigningAttributesTypeDef",
+    "AssociateDelegationSignerToDomainResponseTypeDef",
     "BillingRecordTypeDef",
     "CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef",
+    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
     "CheckDomainAvailabilityRequestRequestTypeDef",
+    "CheckDomainAvailabilityResponseTypeDef",
     "CheckDomainTransferabilityRequestRequestTypeDef",
     "DomainTransferabilityTypeDef",
     "ConsentTypeDef",
     "ExtraParamTypeDef",
     "DeleteDomainRequestRequestTypeDef",
+    "DeleteDomainResponseTypeDef",
     "DeleteTagsForDomainRequestRequestTypeDef",
     "DisableDomainAutoRenewRequestRequestTypeDef",
     "DisableDomainTransferLockRequestRequestTypeDef",
+    "DisableDomainTransferLockResponseTypeDef",
     "DisassociateDelegationSignerFromDomainRequestRequestTypeDef",
+    "DisassociateDelegationSignerFromDomainResponseTypeDef",
     "DnssecKeyTypeDef",
     "PriceWithCurrencyTypeDef",
     "DomainSuggestionTypeDef",
     "DomainSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableDomainAutoRenewRequestRequestTypeDef",
     "EnableDomainTransferLockRequestRequestTypeDef",
+    "EnableDomainTransferLockResponseTypeDef",
     "FilterConditionTypeDef",
     "GetContactReachabilityStatusRequestRequestTypeDef",
+    "GetContactReachabilityStatusResponseTypeDef",
     "GetDomainDetailRequestRequestTypeDef",
     "NameserverTypeDef",
     "GetDomainSuggestionsRequestRequestTypeDef",
     "GetOperationDetailRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetOperationDetailResponseTypeDef",
     "SortConditionTypeDef",
+    "ListOperationsRequestListOperationsPaginateTypeDef",
     "ListOperationsRequestRequestTypeDef",
     "OperationSummaryTypeDef",
+    "ListPricesRequestListPricesPaginateTypeDef",
     "ListPricesRequestRequestTypeDef",
     "ListTagsForDomainRequestRequestTypeDef",
     "TagTypeDef",
+    "PaginatorConfigTypeDef",
     "PushDomainRequestRequestTypeDef",
+    "RegisterDomainResponseTypeDef",
     "RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
+    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
     "RenewDomainRequestRequestTypeDef",
+    "RenewDomainResponseTypeDef",
     "ResendContactReachabilityEmailRequestRequestTypeDef",
+    "ResendContactReachabilityEmailResponseTypeDef",
     "ResendOperationAuthorizationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RetrieveDomainAuthCodeRequestRequestTypeDef",
-    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
-    "UpdateDomainContactPrivacyRequestRequestTypeDef",
-    "ViewBillingRequestRequestTypeDef",
-    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
-    "AssociateDelegationSignerToDomainResponseTypeDef",
-    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
-    "CheckDomainAvailabilityResponseTypeDef",
-    "DeleteDomainResponseTypeDef",
-    "DisableDomainTransferLockResponseTypeDef",
-    "DisassociateDelegationSignerFromDomainResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EnableDomainTransferLockResponseTypeDef",
-    "GetContactReachabilityStatusResponseTypeDef",
-    "GetOperationDetailResponseTypeDef",
-    "RegisterDomainResponseTypeDef",
-    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
-    "RenewDomainResponseTypeDef",
-    "ResendContactReachabilityEmailResponseTypeDef",
     "RetrieveDomainAuthCodeResponseTypeDef",
     "TransferDomainResponseTypeDef",
+    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
     "TransferDomainToAnotherAwsAccountResponseTypeDef",
+    "UpdateDomainContactPrivacyRequestRequestTypeDef",
     "UpdateDomainContactPrivacyResponseTypeDef",
     "UpdateDomainContactResponseTypeDef",
     "UpdateDomainNameserversResponseTypeDef",
+    "ViewBillingRequestRequestTypeDef",
+    "ViewBillingRequestViewBillingPaginateTypeDef",
     "AssociateDelegationSignerToDomainRequestRequestTypeDef",
     "ViewBillingResponseTypeDef",
     "CheckDomainTransferabilityResponseTypeDef",
     "ContactDetailTypeDef",
     "DomainPriceTypeDef",
     "GetDomainSuggestionsResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "UpdateDomainNameserversRequestRequestTypeDef",
-    "ListOperationsRequestListOperationsPaginateTypeDef",
-    "ListPricesRequestListPricesPaginateTypeDef",
-    "ViewBillingRequestViewBillingPaginateTypeDef",
     "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
     "ListOperationsResponseTypeDef",
     "ListTagsForDomainResponseTypeDef",
     "UpdateTagsForDomainRequestRequestTypeDef",
     "GetDomainDetailResponseTypeDef",
     "RegisterDomainRequestRequestTypeDef",
@@ -132,35 +132,40 @@
     "AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
     {
         "DomainName": str,
         "Password": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
+    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DnssecSigningAttributesTypeDef = TypedDict(
     "DnssecSigningAttributesTypeDef",
     {
         "Algorithm": int,
         "Flags": int,
         "PublicKey": str,
     },
     total=False,
 )
 
+AssociateDelegationSignerToDomainResponseTypeDef = TypedDict(
+    "AssociateDelegationSignerToDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BillingRecordTypeDef = TypedDict(
     "BillingRecordTypeDef",
     {
         "DomainName": str,
         "Operation": OperationTypeType,
         "InvoiceId": str,
         "BillDate": datetime,
@@ -172,14 +177,22 @@
 CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef = TypedDict(
     "CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+CancelDomainTransferToAnotherAwsAccountResponseTypeDef = TypedDict(
+    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCheckDomainAvailabilityRequestRequestTypeDef = TypedDict(
     "_RequiredCheckDomainAvailabilityRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalCheckDomainAvailabilityRequestRequestTypeDef = TypedDict(
@@ -194,14 +207,22 @@
 class CheckDomainAvailabilityRequestRequestTypeDef(
     _RequiredCheckDomainAvailabilityRequestRequestTypeDef,
     _OptionalCheckDomainAvailabilityRequestRequestTypeDef,
 ):
     pass
 
 
+CheckDomainAvailabilityResponseTypeDef = TypedDict(
+    "CheckDomainAvailabilityResponseTypeDef",
+    {
+        "Availability": DomainAvailabilityType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCheckDomainTransferabilityRequestRequestTypeDef = TypedDict(
     "_RequiredCheckDomainTransferabilityRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalCheckDomainTransferabilityRequestRequestTypeDef = TypedDict(
@@ -247,14 +268,22 @@
 DeleteDomainRequestRequestTypeDef = TypedDict(
     "DeleteDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DeleteDomainResponseTypeDef = TypedDict(
+    "DeleteDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTagsForDomainRequestRequestTypeDef = TypedDict(
     "DeleteTagsForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "TagsToDelete": Sequence[str],
     },
 )
@@ -269,22 +298,38 @@
 DisableDomainTransferLockRequestRequestTypeDef = TypedDict(
     "DisableDomainTransferLockRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DisableDomainTransferLockResponseTypeDef = TypedDict(
+    "DisableDomainTransferLockResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateDelegationSignerFromDomainRequestRequestTypeDef = TypedDict(
     "DisassociateDelegationSignerFromDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "Id": str,
     },
 )
 
+DisassociateDelegationSignerFromDomainResponseTypeDef = TypedDict(
+    "DisassociateDelegationSignerFromDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DnssecKeyTypeDef = TypedDict(
     "DnssecKeyTypeDef",
     {
         "Algorithm": int,
         "Flags": int,
         "PublicKey": str,
         "DigestType": int,
@@ -319,28 +364,43 @@
         "AutoRenew": bool,
         "TransferLock": bool,
         "Expiry": datetime,
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
 EnableDomainAutoRenewRequestRequestTypeDef = TypedDict(
     "EnableDomainAutoRenewRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
 EnableDomainTransferLockRequestRequestTypeDef = TypedDict(
     "EnableDomainTransferLockRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+EnableDomainTransferLockResponseTypeDef = TypedDict(
+    "EnableDomainTransferLockResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FilterConditionTypeDef = TypedDict(
     "FilterConditionTypeDef",
     {
         "Name": ListDomainsAttributeNameType,
         "Operator": OperatorType,
         "Values": Sequence[str],
     },
@@ -350,14 +410,23 @@
     "GetContactReachabilityStatusRequestRequestTypeDef",
     {
         "domainName": str,
     },
     total=False,
 )
 
+GetContactReachabilityStatusResponseTypeDef = TypedDict(
+    "GetContactReachabilityStatusResponseTypeDef",
+    {
+        "domainName": str,
+        "status": ReachabilityStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDomainDetailRequestRequestTypeDef = TypedDict(
     "GetDomainDetailRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
@@ -392,32 +461,50 @@
 GetOperationDetailRequestRequestTypeDef = TypedDict(
     "GetOperationDetailRequestRequestTypeDef",
     {
         "OperationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetOperationDetailResponseTypeDef = TypedDict(
+    "GetOperationDetailResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "OperationId": str,
+        "Status": OperationStatusType,
+        "Message": str,
+        "DomainName": str,
+        "Type": OperationTypeType,
+        "SubmittedDate": datetime,
+        "LastUpdatedDate": datetime,
+        "StatusFlag": StatusFlagType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 SortConditionTypeDef = TypedDict(
     "SortConditionTypeDef",
     {
         "Name": ListDomainsAttributeNameType,
         "SortOrder": SortOrderType,
     },
 )
 
+ListOperationsRequestListOperationsPaginateTypeDef = TypedDict(
+    "ListOperationsRequestListOperationsPaginateTypeDef",
+    {
+        "SubmittedSince": Union[datetime, str],
+        "Status": Sequence[OperationStatusType],
+        "Type": Sequence[OperationTypeType],
+        "SortBy": Literal["SubmittedDate"],
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOperationsRequestRequestTypeDef = TypedDict(
     "ListOperationsRequestRequestTypeDef",
     {
         "SubmittedSince": Union[datetime, str],
         "Marker": str,
         "MaxItems": int,
         "Status": Sequence[OperationStatusType],
@@ -439,14 +526,23 @@
         "Message": str,
         "StatusFlag": StatusFlagType,
         "LastUpdatedDate": datetime,
     },
     total=False,
 )
 
+ListPricesRequestListPricesPaginateTypeDef = TypedDict(
+    "ListPricesRequestListPricesPaginateTypeDef",
+    {
+        "Tld": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPricesRequestRequestTypeDef = TypedDict(
     "ListPricesRequestRequestTypeDef",
     {
         "Tld": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -465,29 +561,55 @@
     {
         "Key": str,
         "Value": str,
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
 PushDomainRequestRequestTypeDef = TypedDict(
     "PushDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "Target": str,
     },
 )
 
+RegisterDomainResponseTypeDef = TypedDict(
+    "RegisterDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef = TypedDict(
     "RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+RejectDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
+    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRenewDomainRequestRequestTypeDef = TypedDict(
     "_RequiredRenewDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "CurrentExpiryYear": int,
     },
 )
@@ -502,255 +624,165 @@
 
 class RenewDomainRequestRequestTypeDef(
     _RequiredRenewDomainRequestRequestTypeDef, _OptionalRenewDomainRequestRequestTypeDef
 ):
     pass
 
 
-ResendContactReachabilityEmailRequestRequestTypeDef = TypedDict(
-    "ResendContactReachabilityEmailRequestRequestTypeDef",
-    {
-        "domainName": str,
-    },
-    total=False,
-)
-
-ResendOperationAuthorizationRequestRequestTypeDef = TypedDict(
-    "ResendOperationAuthorizationRequestRequestTypeDef",
+RenewDomainResponseTypeDef = TypedDict(
+    "RenewDomainResponseTypeDef",
     {
         "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RetrieveDomainAuthCodeRequestRequestTypeDef = TypedDict(
-    "RetrieveDomainAuthCodeRequestRequestTypeDef",
-    {
-        "DomainName": str,
-    },
-)
-
-TransferDomainToAnotherAwsAccountRequestRequestTypeDef = TypedDict(
-    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
-    {
-        "DomainName": str,
-        "AccountId": str,
-    },
-)
-
-_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef",
-    {
-        "DomainName": str,
-    },
-)
-_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef",
-    {
-        "AdminPrivacy": bool,
-        "RegistrantPrivacy": bool,
-        "TechPrivacy": bool,
-    },
-    total=False,
-)
-
-
-class UpdateDomainContactPrivacyRequestRequestTypeDef(
-    _RequiredUpdateDomainContactPrivacyRequestRequestTypeDef,
-    _OptionalUpdateDomainContactPrivacyRequestRequestTypeDef,
-):
-    pass
-
-
-ViewBillingRequestRequestTypeDef = TypedDict(
-    "ViewBillingRequestRequestTypeDef",
+ResendContactReachabilityEmailRequestRequestTypeDef = TypedDict(
+    "ResendContactReachabilityEmailRequestRequestTypeDef",
     {
-        "Start": Union[datetime, str],
-        "End": Union[datetime, str],
-        "Marker": str,
-        "MaxItems": int,
+        "domainName": str,
     },
     total=False,
 )
 
-AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
-    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateDelegationSignerToDomainResponseTypeDef = TypedDict(
-    "AssociateDelegationSignerToDomainResponseTypeDef",
+ResendContactReachabilityEmailResponseTypeDef = TypedDict(
+    "ResendContactReachabilityEmailResponseTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "domainName": str,
+        "emailAddress": str,
+        "isAlreadyVerified": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CancelDomainTransferToAnotherAwsAccountResponseTypeDef = TypedDict(
-    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
+ResendOperationAuthorizationRequestRequestTypeDef = TypedDict(
+    "ResendOperationAuthorizationRequestRequestTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-CheckDomainAvailabilityResponseTypeDef = TypedDict(
-    "CheckDomainAvailabilityResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Availability": DomainAvailabilityType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-DeleteDomainResponseTypeDef = TypedDict(
-    "DeleteDomainResponseTypeDef",
+RetrieveDomainAuthCodeRequestRequestTypeDef = TypedDict(
+    "RetrieveDomainAuthCodeRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DomainName": str,
     },
 )
 
-DisableDomainTransferLockResponseTypeDef = TypedDict(
-    "DisableDomainTransferLockResponseTypeDef",
+RetrieveDomainAuthCodeResponseTypeDef = TypedDict(
+    "RetrieveDomainAuthCodeResponseTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AuthCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DisassociateDelegationSignerFromDomainResponseTypeDef = TypedDict(
-    "DisassociateDelegationSignerFromDomainResponseTypeDef",
+TransferDomainResponseTypeDef = TypedDict(
+    "TransferDomainResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+TransferDomainToAnotherAwsAccountRequestRequestTypeDef = TypedDict(
+    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DomainName": str,
+        "AccountId": str,
     },
 )
 
-EnableDomainTransferLockResponseTypeDef = TypedDict(
-    "EnableDomainTransferLockResponseTypeDef",
+TransferDomainToAnotherAwsAccountResponseTypeDef = TypedDict(
+    "TransferDomainToAnotherAwsAccountResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContactReachabilityStatusResponseTypeDef = TypedDict(
-    "GetContactReachabilityStatusResponseTypeDef",
-    {
-        "domainName": str,
-        "status": ReachabilityStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Password": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetOperationDetailResponseTypeDef = TypedDict(
-    "GetOperationDetailResponseTypeDef",
+_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "Status": OperationStatusType,
-        "Message": str,
         "DomainName": str,
-        "Type": OperationTypeType,
-        "SubmittedDate": datetime,
-        "LastUpdatedDate": datetime,
-        "StatusFlag": StatusFlagType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-RegisterDomainResponseTypeDef = TypedDict(
-    "RegisterDomainResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RejectDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
-    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
+_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AdminPrivacy": bool,
+        "RegistrantPrivacy": bool,
+        "TechPrivacy": bool,
     },
+    total=False,
 )
 
-RenewDomainResponseTypeDef = TypedDict(
-    "RenewDomainResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ResendContactReachabilityEmailResponseTypeDef = TypedDict(
-    "ResendContactReachabilityEmailResponseTypeDef",
-    {
-        "domainName": str,
-        "emailAddress": str,
-        "isAlreadyVerified": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateDomainContactPrivacyRequestRequestTypeDef(
+    _RequiredUpdateDomainContactPrivacyRequestRequestTypeDef,
+    _OptionalUpdateDomainContactPrivacyRequestRequestTypeDef,
+):
+    pass
 
-RetrieveDomainAuthCodeResponseTypeDef = TypedDict(
-    "RetrieveDomainAuthCodeResponseTypeDef",
-    {
-        "AuthCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-TransferDomainResponseTypeDef = TypedDict(
-    "TransferDomainResponseTypeDef",
+UpdateDomainContactPrivacyResponseTypeDef = TypedDict(
+    "UpdateDomainContactPrivacyResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TransferDomainToAnotherAwsAccountResponseTypeDef = TypedDict(
-    "TransferDomainToAnotherAwsAccountResponseTypeDef",
+UpdateDomainContactResponseTypeDef = TypedDict(
+    "UpdateDomainContactResponseTypeDef",
     {
         "OperationId": str,
-        "Password": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateDomainContactPrivacyResponseTypeDef = TypedDict(
-    "UpdateDomainContactPrivacyResponseTypeDef",
+UpdateDomainNameserversResponseTypeDef = TypedDict(
+    "UpdateDomainNameserversResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateDomainContactResponseTypeDef = TypedDict(
-    "UpdateDomainContactResponseTypeDef",
+ViewBillingRequestRequestTypeDef = TypedDict(
+    "ViewBillingRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Start": Union[datetime, str],
+        "End": Union[datetime, str],
+        "Marker": str,
+        "MaxItems": int,
     },
+    total=False,
 )
 
-UpdateDomainNameserversResponseTypeDef = TypedDict(
-    "UpdateDomainNameserversResponseTypeDef",
+ViewBillingRequestViewBillingPaginateTypeDef = TypedDict(
+    "ViewBillingRequestViewBillingPaginateTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Start": Union[datetime, str],
+        "End": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 AssociateDelegationSignerToDomainRequestRequestTypeDef = TypedDict(
     "AssociateDelegationSignerToDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "SigningAttributes": DnssecSigningAttributesTypeDef,
@@ -758,23 +790,23 @@
 )
 
 ViewBillingResponseTypeDef = TypedDict(
     "ViewBillingResponseTypeDef",
     {
         "NextPageMarker": str,
         "BillingRecords": List[BillingRecordTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CheckDomainTransferabilityResponseTypeDef = TypedDict(
     "CheckDomainTransferabilityResponseTypeDef",
     {
         "Transferability": DomainTransferabilityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContactDetailTypeDef = TypedDict(
     "ContactDetailTypeDef",
     {
         "FirstName": str,
@@ -808,24 +840,24 @@
     total=False,
 )
 
 GetDomainSuggestionsResponseTypeDef = TypedDict(
     "GetDomainSuggestionsResponseTypeDef",
     {
         "SuggestionsList": List[DomainSuggestionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "Domains": List[DomainSummaryTypeDef],
         "NextPageMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDomainNameserversRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainNameserversRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -844,52 +876,20 @@
 class UpdateDomainNameserversRequestRequestTypeDef(
     _RequiredUpdateDomainNameserversRequestRequestTypeDef,
     _OptionalUpdateDomainNameserversRequestRequestTypeDef,
 ):
     pass
 
 
-ListOperationsRequestListOperationsPaginateTypeDef = TypedDict(
-    "ListOperationsRequestListOperationsPaginateTypeDef",
-    {
-        "SubmittedSince": Union[datetime, str],
-        "Status": Sequence[OperationStatusType],
-        "Type": Sequence[OperationTypeType],
-        "SortBy": Literal["SubmittedDate"],
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPricesRequestListPricesPaginateTypeDef = TypedDict(
-    "ListPricesRequestListPricesPaginateTypeDef",
-    {
-        "Tld": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ViewBillingRequestViewBillingPaginateTypeDef = TypedDict(
-    "ViewBillingRequestViewBillingPaginateTypeDef",
-    {
-        "Start": Union[datetime, str],
-        "End": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
     "ListDomainsRequestListDomainsPaginateTypeDef",
     {
         "FilterConditions": Sequence[FilterConditionTypeDef],
         "SortCondition": SortConditionTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
@@ -902,23 +902,23 @@
 )
 
 ListOperationsResponseTypeDef = TypedDict(
     "ListOperationsResponseTypeDef",
     {
         "Operations": List[OperationSummaryTypeDef],
         "NextPageMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForDomainResponseTypeDef = TypedDict(
     "ListTagsForDomainResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTagsForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTagsForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -961,15 +961,15 @@
         "CreationDate": datetime,
         "UpdatedDate": datetime,
         "ExpirationDate": datetime,
         "Reseller": str,
         "DnsSec": str,
         "StatusList": List[str],
         "DnssecKeys": List[DnssecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterDomainRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterDomainRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1055,10 +1055,10 @@
 
 
 ListPricesResponseTypeDef = TypedDict(
     "ListPricesResponseTypeDef",
     {
         "Prices": List[DomainPriceTypeDef],
         "NextPageMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains/type_defs.pyi` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -37,88 +37,88 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
     "DnssecSigningAttributesTypeDef",
+    "AssociateDelegationSignerToDomainResponseTypeDef",
     "BillingRecordTypeDef",
     "CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef",
+    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
     "CheckDomainAvailabilityRequestRequestTypeDef",
+    "CheckDomainAvailabilityResponseTypeDef",
     "CheckDomainTransferabilityRequestRequestTypeDef",
     "DomainTransferabilityTypeDef",
     "ConsentTypeDef",
     "ExtraParamTypeDef",
     "DeleteDomainRequestRequestTypeDef",
+    "DeleteDomainResponseTypeDef",
     "DeleteTagsForDomainRequestRequestTypeDef",
     "DisableDomainAutoRenewRequestRequestTypeDef",
     "DisableDomainTransferLockRequestRequestTypeDef",
+    "DisableDomainTransferLockResponseTypeDef",
     "DisassociateDelegationSignerFromDomainRequestRequestTypeDef",
+    "DisassociateDelegationSignerFromDomainResponseTypeDef",
     "DnssecKeyTypeDef",
     "PriceWithCurrencyTypeDef",
     "DomainSuggestionTypeDef",
     "DomainSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableDomainAutoRenewRequestRequestTypeDef",
     "EnableDomainTransferLockRequestRequestTypeDef",
+    "EnableDomainTransferLockResponseTypeDef",
     "FilterConditionTypeDef",
     "GetContactReachabilityStatusRequestRequestTypeDef",
+    "GetContactReachabilityStatusResponseTypeDef",
     "GetDomainDetailRequestRequestTypeDef",
     "NameserverTypeDef",
     "GetDomainSuggestionsRequestRequestTypeDef",
     "GetOperationDetailRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetOperationDetailResponseTypeDef",
     "SortConditionTypeDef",
+    "ListOperationsRequestListOperationsPaginateTypeDef",
     "ListOperationsRequestRequestTypeDef",
     "OperationSummaryTypeDef",
+    "ListPricesRequestListPricesPaginateTypeDef",
     "ListPricesRequestRequestTypeDef",
     "ListTagsForDomainRequestRequestTypeDef",
     "TagTypeDef",
+    "PaginatorConfigTypeDef",
     "PushDomainRequestRequestTypeDef",
+    "RegisterDomainResponseTypeDef",
     "RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
+    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
     "RenewDomainRequestRequestTypeDef",
+    "RenewDomainResponseTypeDef",
     "ResendContactReachabilityEmailRequestRequestTypeDef",
+    "ResendContactReachabilityEmailResponseTypeDef",
     "ResendOperationAuthorizationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RetrieveDomainAuthCodeRequestRequestTypeDef",
-    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
-    "UpdateDomainContactPrivacyRequestRequestTypeDef",
-    "ViewBillingRequestRequestTypeDef",
-    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
-    "AssociateDelegationSignerToDomainResponseTypeDef",
-    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
-    "CheckDomainAvailabilityResponseTypeDef",
-    "DeleteDomainResponseTypeDef",
-    "DisableDomainTransferLockResponseTypeDef",
-    "DisassociateDelegationSignerFromDomainResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EnableDomainTransferLockResponseTypeDef",
-    "GetContactReachabilityStatusResponseTypeDef",
-    "GetOperationDetailResponseTypeDef",
-    "RegisterDomainResponseTypeDef",
-    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
-    "RenewDomainResponseTypeDef",
-    "ResendContactReachabilityEmailResponseTypeDef",
     "RetrieveDomainAuthCodeResponseTypeDef",
     "TransferDomainResponseTypeDef",
+    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
     "TransferDomainToAnotherAwsAccountResponseTypeDef",
+    "UpdateDomainContactPrivacyRequestRequestTypeDef",
     "UpdateDomainContactPrivacyResponseTypeDef",
     "UpdateDomainContactResponseTypeDef",
     "UpdateDomainNameserversResponseTypeDef",
+    "ViewBillingRequestRequestTypeDef",
+    "ViewBillingRequestViewBillingPaginateTypeDef",
     "AssociateDelegationSignerToDomainRequestRequestTypeDef",
     "ViewBillingResponseTypeDef",
     "CheckDomainTransferabilityResponseTypeDef",
     "ContactDetailTypeDef",
     "DomainPriceTypeDef",
     "GetDomainSuggestionsResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "UpdateDomainNameserversRequestRequestTypeDef",
-    "ListOperationsRequestListOperationsPaginateTypeDef",
-    "ListPricesRequestListPricesPaginateTypeDef",
-    "ViewBillingRequestViewBillingPaginateTypeDef",
     "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
     "ListOperationsResponseTypeDef",
     "ListTagsForDomainResponseTypeDef",
     "UpdateTagsForDomainRequestRequestTypeDef",
     "GetDomainDetailResponseTypeDef",
     "RegisterDomainRequestRequestTypeDef",
@@ -131,35 +131,40 @@
     "AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
     {
         "DomainName": str,
         "Password": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
+    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DnssecSigningAttributesTypeDef = TypedDict(
     "DnssecSigningAttributesTypeDef",
     {
         "Algorithm": int,
         "Flags": int,
         "PublicKey": str,
     },
     total=False,
 )
 
+AssociateDelegationSignerToDomainResponseTypeDef = TypedDict(
+    "AssociateDelegationSignerToDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BillingRecordTypeDef = TypedDict(
     "BillingRecordTypeDef",
     {
         "DomainName": str,
         "Operation": OperationTypeType,
         "InvoiceId": str,
         "BillDate": datetime,
@@ -171,14 +176,22 @@
 CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef = TypedDict(
     "CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+CancelDomainTransferToAnotherAwsAccountResponseTypeDef = TypedDict(
+    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCheckDomainAvailabilityRequestRequestTypeDef = TypedDict(
     "_RequiredCheckDomainAvailabilityRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalCheckDomainAvailabilityRequestRequestTypeDef = TypedDict(
@@ -191,14 +204,22 @@
 
 class CheckDomainAvailabilityRequestRequestTypeDef(
     _RequiredCheckDomainAvailabilityRequestRequestTypeDef,
     _OptionalCheckDomainAvailabilityRequestRequestTypeDef,
 ):
     pass
 
+CheckDomainAvailabilityResponseTypeDef = TypedDict(
+    "CheckDomainAvailabilityResponseTypeDef",
+    {
+        "Availability": DomainAvailabilityType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCheckDomainTransferabilityRequestRequestTypeDef = TypedDict(
     "_RequiredCheckDomainTransferabilityRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalCheckDomainTransferabilityRequestRequestTypeDef = TypedDict(
@@ -242,14 +263,22 @@
 DeleteDomainRequestRequestTypeDef = TypedDict(
     "DeleteDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DeleteDomainResponseTypeDef = TypedDict(
+    "DeleteDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTagsForDomainRequestRequestTypeDef = TypedDict(
     "DeleteTagsForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "TagsToDelete": Sequence[str],
     },
 )
@@ -264,22 +293,38 @@
 DisableDomainTransferLockRequestRequestTypeDef = TypedDict(
     "DisableDomainTransferLockRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DisableDomainTransferLockResponseTypeDef = TypedDict(
+    "DisableDomainTransferLockResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateDelegationSignerFromDomainRequestRequestTypeDef = TypedDict(
     "DisassociateDelegationSignerFromDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "Id": str,
     },
 )
 
+DisassociateDelegationSignerFromDomainResponseTypeDef = TypedDict(
+    "DisassociateDelegationSignerFromDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DnssecKeyTypeDef = TypedDict(
     "DnssecKeyTypeDef",
     {
         "Algorithm": int,
         "Flags": int,
         "PublicKey": str,
         "DigestType": int,
@@ -314,28 +359,43 @@
         "AutoRenew": bool,
         "TransferLock": bool,
         "Expiry": datetime,
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
 EnableDomainAutoRenewRequestRequestTypeDef = TypedDict(
     "EnableDomainAutoRenewRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
 EnableDomainTransferLockRequestRequestTypeDef = TypedDict(
     "EnableDomainTransferLockRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+EnableDomainTransferLockResponseTypeDef = TypedDict(
+    "EnableDomainTransferLockResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FilterConditionTypeDef = TypedDict(
     "FilterConditionTypeDef",
     {
         "Name": ListDomainsAttributeNameType,
         "Operator": OperatorType,
         "Values": Sequence[str],
     },
@@ -345,14 +405,23 @@
     "GetContactReachabilityStatusRequestRequestTypeDef",
     {
         "domainName": str,
     },
     total=False,
 )
 
+GetContactReachabilityStatusResponseTypeDef = TypedDict(
+    "GetContactReachabilityStatusResponseTypeDef",
+    {
+        "domainName": str,
+        "status": ReachabilityStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDomainDetailRequestRequestTypeDef = TypedDict(
     "GetDomainDetailRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
@@ -385,32 +454,50 @@
 GetOperationDetailRequestRequestTypeDef = TypedDict(
     "GetOperationDetailRequestRequestTypeDef",
     {
         "OperationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetOperationDetailResponseTypeDef = TypedDict(
+    "GetOperationDetailResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "OperationId": str,
+        "Status": OperationStatusType,
+        "Message": str,
+        "DomainName": str,
+        "Type": OperationTypeType,
+        "SubmittedDate": datetime,
+        "LastUpdatedDate": datetime,
+        "StatusFlag": StatusFlagType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 SortConditionTypeDef = TypedDict(
     "SortConditionTypeDef",
     {
         "Name": ListDomainsAttributeNameType,
         "SortOrder": SortOrderType,
     },
 )
 
+ListOperationsRequestListOperationsPaginateTypeDef = TypedDict(
+    "ListOperationsRequestListOperationsPaginateTypeDef",
+    {
+        "SubmittedSince": Union[datetime, str],
+        "Status": Sequence[OperationStatusType],
+        "Type": Sequence[OperationTypeType],
+        "SortBy": Literal["SubmittedDate"],
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOperationsRequestRequestTypeDef = TypedDict(
     "ListOperationsRequestRequestTypeDef",
     {
         "SubmittedSince": Union[datetime, str],
         "Marker": str,
         "MaxItems": int,
         "Status": Sequence[OperationStatusType],
@@ -432,14 +519,23 @@
         "Message": str,
         "StatusFlag": StatusFlagType,
         "LastUpdatedDate": datetime,
     },
     total=False,
 )
 
+ListPricesRequestListPricesPaginateTypeDef = TypedDict(
+    "ListPricesRequestListPricesPaginateTypeDef",
+    {
+        "Tld": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPricesRequestRequestTypeDef = TypedDict(
     "ListPricesRequestRequestTypeDef",
     {
         "Tld": str,
         "Marker": str,
         "MaxItems": int,
     },
@@ -458,29 +554,55 @@
     {
         "Key": str,
         "Value": str,
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
 PushDomainRequestRequestTypeDef = TypedDict(
     "PushDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "Target": str,
     },
 )
 
+RegisterDomainResponseTypeDef = TypedDict(
+    "RegisterDomainResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef = TypedDict(
     "RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+RejectDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
+    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
+    {
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRenewDomainRequestRequestTypeDef = TypedDict(
     "_RequiredRenewDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "CurrentExpiryYear": int,
     },
 )
@@ -493,253 +615,163 @@
 )
 
 class RenewDomainRequestRequestTypeDef(
     _RequiredRenewDomainRequestRequestTypeDef, _OptionalRenewDomainRequestRequestTypeDef
 ):
     pass
 
-ResendContactReachabilityEmailRequestRequestTypeDef = TypedDict(
-    "ResendContactReachabilityEmailRequestRequestTypeDef",
-    {
-        "domainName": str,
-    },
-    total=False,
-)
-
-ResendOperationAuthorizationRequestRequestTypeDef = TypedDict(
-    "ResendOperationAuthorizationRequestRequestTypeDef",
+RenewDomainResponseTypeDef = TypedDict(
+    "RenewDomainResponseTypeDef",
     {
         "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RetrieveDomainAuthCodeRequestRequestTypeDef = TypedDict(
-    "RetrieveDomainAuthCodeRequestRequestTypeDef",
-    {
-        "DomainName": str,
-    },
-)
-
-TransferDomainToAnotherAwsAccountRequestRequestTypeDef = TypedDict(
-    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
-    {
-        "DomainName": str,
-        "AccountId": str,
-    },
-)
-
-_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef",
-    {
-        "DomainName": str,
-    },
-)
-_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef",
-    {
-        "AdminPrivacy": bool,
-        "RegistrantPrivacy": bool,
-        "TechPrivacy": bool,
-    },
-    total=False,
-)
-
-class UpdateDomainContactPrivacyRequestRequestTypeDef(
-    _RequiredUpdateDomainContactPrivacyRequestRequestTypeDef,
-    _OptionalUpdateDomainContactPrivacyRequestRequestTypeDef,
-):
-    pass
-
-ViewBillingRequestRequestTypeDef = TypedDict(
-    "ViewBillingRequestRequestTypeDef",
+ResendContactReachabilityEmailRequestRequestTypeDef = TypedDict(
+    "ResendContactReachabilityEmailRequestRequestTypeDef",
     {
-        "Start": Union[datetime, str],
-        "End": Union[datetime, str],
-        "Marker": str,
-        "MaxItems": int,
+        "domainName": str,
     },
     total=False,
 )
 
-AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
-    "AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateDelegationSignerToDomainResponseTypeDef = TypedDict(
-    "AssociateDelegationSignerToDomainResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelDomainTransferToAnotherAwsAccountResponseTypeDef = TypedDict(
-    "CancelDomainTransferToAnotherAwsAccountResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CheckDomainAvailabilityResponseTypeDef = TypedDict(
-    "CheckDomainAvailabilityResponseTypeDef",
+ResendContactReachabilityEmailResponseTypeDef = TypedDict(
+    "ResendContactReachabilityEmailResponseTypeDef",
     {
-        "Availability": DomainAvailabilityType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "domainName": str,
+        "emailAddress": str,
+        "isAlreadyVerified": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteDomainResponseTypeDef = TypedDict(
-    "DeleteDomainResponseTypeDef",
+ResendOperationAuthorizationRequestRequestTypeDef = TypedDict(
+    "ResendOperationAuthorizationRequestRequestTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-DisableDomainTransferLockResponseTypeDef = TypedDict(
-    "DisableDomainTransferLockResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-DisassociateDelegationSignerFromDomainResponseTypeDef = TypedDict(
-    "DisassociateDelegationSignerFromDomainResponseTypeDef",
+RetrieveDomainAuthCodeRequestRequestTypeDef = TypedDict(
+    "RetrieveDomainAuthCodeRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DomainName": str,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+RetrieveDomainAuthCodeResponseTypeDef = TypedDict(
+    "RetrieveDomainAuthCodeResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AuthCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EnableDomainTransferLockResponseTypeDef = TypedDict(
-    "EnableDomainTransferLockResponseTypeDef",
+TransferDomainResponseTypeDef = TypedDict(
+    "TransferDomainResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContactReachabilityStatusResponseTypeDef = TypedDict(
-    "GetContactReachabilityStatusResponseTypeDef",
-    {
-        "domainName": str,
-        "status": ReachabilityStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetOperationDetailResponseTypeDef = TypedDict(
-    "GetOperationDetailResponseTypeDef",
+TransferDomainToAnotherAwsAccountRequestRequestTypeDef = TypedDict(
+    "TransferDomainToAnotherAwsAccountRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "Status": OperationStatusType,
-        "Message": str,
         "DomainName": str,
-        "Type": OperationTypeType,
-        "SubmittedDate": datetime,
-        "LastUpdatedDate": datetime,
-        "StatusFlag": StatusFlagType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterDomainResponseTypeDef = TypedDict(
-    "RegisterDomainResponseTypeDef",
-    {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AccountId": str,
     },
 )
 
-RejectDomainTransferFromAnotherAwsAccountResponseTypeDef = TypedDict(
-    "RejectDomainTransferFromAnotherAwsAccountResponseTypeDef",
+TransferDomainToAnotherAwsAccountResponseTypeDef = TypedDict(
+    "TransferDomainToAnotherAwsAccountResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Password": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RenewDomainResponseTypeDef = TypedDict(
-    "RenewDomainResponseTypeDef",
+_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateDomainContactPrivacyRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DomainName": str,
     },
 )
-
-ResendContactReachabilityEmailResponseTypeDef = TypedDict(
-    "ResendContactReachabilityEmailResponseTypeDef",
+_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateDomainContactPrivacyRequestRequestTypeDef",
     {
-        "domainName": str,
-        "emailAddress": str,
-        "isAlreadyVerified": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AdminPrivacy": bool,
+        "RegistrantPrivacy": bool,
+        "TechPrivacy": bool,
     },
+    total=False,
 )
 
-RetrieveDomainAuthCodeResponseTypeDef = TypedDict(
-    "RetrieveDomainAuthCodeResponseTypeDef",
-    {
-        "AuthCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateDomainContactPrivacyRequestRequestTypeDef(
+    _RequiredUpdateDomainContactPrivacyRequestRequestTypeDef,
+    _OptionalUpdateDomainContactPrivacyRequestRequestTypeDef,
+):
+    pass
 
-TransferDomainResponseTypeDef = TypedDict(
-    "TransferDomainResponseTypeDef",
+UpdateDomainContactPrivacyResponseTypeDef = TypedDict(
+    "UpdateDomainContactPrivacyResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TransferDomainToAnotherAwsAccountResponseTypeDef = TypedDict(
-    "TransferDomainToAnotherAwsAccountResponseTypeDef",
+UpdateDomainContactResponseTypeDef = TypedDict(
+    "UpdateDomainContactResponseTypeDef",
     {
         "OperationId": str,
-        "Password": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateDomainContactPrivacyResponseTypeDef = TypedDict(
-    "UpdateDomainContactPrivacyResponseTypeDef",
+UpdateDomainNameserversResponseTypeDef = TypedDict(
+    "UpdateDomainNameserversResponseTypeDef",
     {
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateDomainContactResponseTypeDef = TypedDict(
-    "UpdateDomainContactResponseTypeDef",
+ViewBillingRequestRequestTypeDef = TypedDict(
+    "ViewBillingRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Start": Union[datetime, str],
+        "End": Union[datetime, str],
+        "Marker": str,
+        "MaxItems": int,
     },
+    total=False,
 )
 
-UpdateDomainNameserversResponseTypeDef = TypedDict(
-    "UpdateDomainNameserversResponseTypeDef",
+ViewBillingRequestViewBillingPaginateTypeDef = TypedDict(
+    "ViewBillingRequestViewBillingPaginateTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Start": Union[datetime, str],
+        "End": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 AssociateDelegationSignerToDomainRequestRequestTypeDef = TypedDict(
     "AssociateDelegationSignerToDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "SigningAttributes": DnssecSigningAttributesTypeDef,
@@ -747,23 +779,23 @@
 )
 
 ViewBillingResponseTypeDef = TypedDict(
     "ViewBillingResponseTypeDef",
     {
         "NextPageMarker": str,
         "BillingRecords": List[BillingRecordTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CheckDomainTransferabilityResponseTypeDef = TypedDict(
     "CheckDomainTransferabilityResponseTypeDef",
     {
         "Transferability": DomainTransferabilityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContactDetailTypeDef = TypedDict(
     "ContactDetailTypeDef",
     {
         "FirstName": str,
@@ -797,24 +829,24 @@
     total=False,
 )
 
 GetDomainSuggestionsResponseTypeDef = TypedDict(
     "GetDomainSuggestionsResponseTypeDef",
     {
         "SuggestionsList": List[DomainSuggestionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "Domains": List[DomainSummaryTypeDef],
         "NextPageMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDomainNameserversRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainNameserversRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -831,52 +863,20 @@
 
 class UpdateDomainNameserversRequestRequestTypeDef(
     _RequiredUpdateDomainNameserversRequestRequestTypeDef,
     _OptionalUpdateDomainNameserversRequestRequestTypeDef,
 ):
     pass
 
-ListOperationsRequestListOperationsPaginateTypeDef = TypedDict(
-    "ListOperationsRequestListOperationsPaginateTypeDef",
-    {
-        "SubmittedSince": Union[datetime, str],
-        "Status": Sequence[OperationStatusType],
-        "Type": Sequence[OperationTypeType],
-        "SortBy": Literal["SubmittedDate"],
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPricesRequestListPricesPaginateTypeDef = TypedDict(
-    "ListPricesRequestListPricesPaginateTypeDef",
-    {
-        "Tld": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ViewBillingRequestViewBillingPaginateTypeDef = TypedDict(
-    "ViewBillingRequestViewBillingPaginateTypeDef",
-    {
-        "Start": Union[datetime, str],
-        "End": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
     "ListDomainsRequestListDomainsPaginateTypeDef",
     {
         "FilterConditions": Sequence[FilterConditionTypeDef],
         "SortCondition": SortConditionTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
@@ -889,23 +889,23 @@
 )
 
 ListOperationsResponseTypeDef = TypedDict(
     "ListOperationsResponseTypeDef",
     {
         "Operations": List[OperationSummaryTypeDef],
         "NextPageMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForDomainResponseTypeDef = TypedDict(
     "ListTagsForDomainResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTagsForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTagsForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -946,15 +946,15 @@
         "CreationDate": datetime,
         "UpdatedDate": datetime,
         "ExpirationDate": datetime,
         "Reseller": str,
         "DnsSec": str,
         "StatusList": List[str],
         "DnssecKeys": List[DnssecKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterDomainRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterDomainRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1034,10 +1034,10 @@
     pass
 
 ListPricesResponseTypeDef = TypedDict(
     "ListPricesResponseTypeDef",
     {
         "Prices": List[DomainPriceTypeDef],
         "NextPageMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/PKG-INFO` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53domains
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53Domains 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53Domains 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53domains"></a>
 
 # types-aiobotocore-route53domains
 
 [![PyPI - types-aiobotocore-route53domains](https://img.shields.io/pypi/v/types-aiobotocore-route53domains.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53domains)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53domains.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53domains)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53domains?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53domains)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53Domains 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
+[aiobotocore.Route53Domains 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53domains.html#Route53Domains)
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
 [types-aiobotocore-route53domains docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53domains/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,88 +339,88 @@
 
 `types_aiobotocore_route53domains.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_route53domains.type_defs import (
     AcceptDomainTransferFromAnotherAwsAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef,
     DnssecSigningAttributesTypeDef,
+    AssociateDelegationSignerToDomainResponseTypeDef,
     BillingRecordTypeDef,
     CancelDomainTransferToAnotherAwsAccountRequestRequestTypeDef,
+    CancelDomainTransferToAnotherAwsAccountResponseTypeDef,
     CheckDomainAvailabilityRequestRequestTypeDef,
+    CheckDomainAvailabilityResponseTypeDef,
     CheckDomainTransferabilityRequestRequestTypeDef,
     DomainTransferabilityTypeDef,
     ConsentTypeDef,
     ExtraParamTypeDef,
     DeleteDomainRequestRequestTypeDef,
+    DeleteDomainResponseTypeDef,
     DeleteTagsForDomainRequestRequestTypeDef,
     DisableDomainAutoRenewRequestRequestTypeDef,
     DisableDomainTransferLockRequestRequestTypeDef,
+    DisableDomainTransferLockResponseTypeDef,
     DisassociateDelegationSignerFromDomainRequestRequestTypeDef,
+    DisassociateDelegationSignerFromDomainResponseTypeDef,
     DnssecKeyTypeDef,
     PriceWithCurrencyTypeDef,
     DomainSuggestionTypeDef,
     DomainSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableDomainAutoRenewRequestRequestTypeDef,
     EnableDomainTransferLockRequestRequestTypeDef,
+    EnableDomainTransferLockResponseTypeDef,
     FilterConditionTypeDef,
     GetContactReachabilityStatusRequestRequestTypeDef,
+    GetContactReachabilityStatusResponseTypeDef,
     GetDomainDetailRequestRequestTypeDef,
     NameserverTypeDef,
     GetDomainSuggestionsRequestRequestTypeDef,
     GetOperationDetailRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetOperationDetailResponseTypeDef,
     SortConditionTypeDef,
+    ListOperationsRequestListOperationsPaginateTypeDef,
     ListOperationsRequestRequestTypeDef,
     OperationSummaryTypeDef,
+    ListPricesRequestListPricesPaginateTypeDef,
     ListPricesRequestRequestTypeDef,
     ListTagsForDomainRequestRequestTypeDef,
     TagTypeDef,
+    PaginatorConfigTypeDef,
     PushDomainRequestRequestTypeDef,
+    RegisterDomainResponseTypeDef,
     RejectDomainTransferFromAnotherAwsAccountRequestRequestTypeDef,
+    RejectDomainTransferFromAnotherAwsAccountResponseTypeDef,
     RenewDomainRequestRequestTypeDef,
+    RenewDomainResponseTypeDef,
     ResendContactReachabilityEmailRequestRequestTypeDef,
+    ResendContactReachabilityEmailResponseTypeDef,
     ResendOperationAuthorizationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RetrieveDomainAuthCodeRequestRequestTypeDef,
-    TransferDomainToAnotherAwsAccountRequestRequestTypeDef,
-    UpdateDomainContactPrivacyRequestRequestTypeDef,
-    ViewBillingRequestRequestTypeDef,
-    AcceptDomainTransferFromAnotherAwsAccountResponseTypeDef,
-    AssociateDelegationSignerToDomainResponseTypeDef,
-    CancelDomainTransferToAnotherAwsAccountResponseTypeDef,
-    CheckDomainAvailabilityResponseTypeDef,
-    DeleteDomainResponseTypeDef,
-    DisableDomainTransferLockResponseTypeDef,
-    DisassociateDelegationSignerFromDomainResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EnableDomainTransferLockResponseTypeDef,
-    GetContactReachabilityStatusResponseTypeDef,
-    GetOperationDetailResponseTypeDef,
-    RegisterDomainResponseTypeDef,
-    RejectDomainTransferFromAnotherAwsAccountResponseTypeDef,
-    RenewDomainResponseTypeDef,
-    ResendContactReachabilityEmailResponseTypeDef,
     RetrieveDomainAuthCodeResponseTypeDef,
     TransferDomainResponseTypeDef,
+    TransferDomainToAnotherAwsAccountRequestRequestTypeDef,
     TransferDomainToAnotherAwsAccountResponseTypeDef,
+    UpdateDomainContactPrivacyRequestRequestTypeDef,
     UpdateDomainContactPrivacyResponseTypeDef,
     UpdateDomainContactResponseTypeDef,
     UpdateDomainNameserversResponseTypeDef,
+    ViewBillingRequestRequestTypeDef,
+    ViewBillingRequestViewBillingPaginateTypeDef,
     AssociateDelegationSignerToDomainRequestRequestTypeDef,
     ViewBillingResponseTypeDef,
     CheckDomainTransferabilityResponseTypeDef,
     ContactDetailTypeDef,
     DomainPriceTypeDef,
     GetDomainSuggestionsResponseTypeDef,
     ListDomainsResponseTypeDef,
     UpdateDomainNameserversRequestRequestTypeDef,
-    ListOperationsRequestListOperationsPaginateTypeDef,
-    ListPricesRequestListPricesPaginateTypeDef,
-    ViewBillingRequestViewBillingPaginateTypeDef,
     ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListOperationsResponseTypeDef,
     ListTagsForDomainResponseTypeDef,
     UpdateTagsForDomainRequestRequestTypeDef,
     GetDomainDetailResponseTypeDef,
     RegisterDomainRequestRequestTypeDef,
@@ -437,43 +437,43 @@
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

### Comparing `types-aiobotocore-route53domains-2.5.0.post1/types_aiobotocore_route53domains.egg-info/SOURCES.txt` & `types-aiobotocore-route53domains-2.5.1/types_aiobotocore_route53domains.egg-info/SOURCES.txt`

 * *Files identical despite different names*

