# Comparing `tmp/types-aiobotocore-organizations-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-organizations-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-organizations-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:05 2023, max compression
+gzip compressed data, was "types-aiobotocore-organizations-2.5.1.tar", last modified: Wed Jun 28 01:43:56 2023, max compression
```

## Comparing `types-aiobotocore-organizations-2.5.0.post1.tar` & `types-aiobotocore-organizations-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.871486 types-aiobotocore-organizations-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22366 2023-03-11 12:27:05.871486 types-aiobotocore-organizations-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20771 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:05.871486 types-aiobotocore-organizations-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:19:32.000000 types-aiobotocore-organizations-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.859486 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/
--rw-r--r--   0 runner    (1001) docker     (123)     4303 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4302 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    49680 2023-03-11 12:19:35.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    49600 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12052 2023-03-11 12:19:35.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12050 2023-03-11 12:19:35.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    20623 2023-03-11 12:19:35.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    20604 2023-03-11 12:19:35.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    44302 2023-03-11 12:19:36.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    44247 2023-03-11 12:19:36.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:33.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.871486 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22366 2023-03-11 12:27:05.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:27:05.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:05.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:27:05.000000 types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.602187 types-aiobotocore-organizations-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22364 2023-06-28 01:43:56.602187 types-aiobotocore-organizations-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20775 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:56.602187 types-aiobotocore-organizations-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.594187 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/
+-rw-r--r--   0 runner    (1001) docker     (123)     4303 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4302 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49679 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49599 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12261 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12259 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    20535 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20517 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    44414 2023-06-28 01:36:20.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44359 2023-06-28 01:36:18.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:17.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.602187 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22364 2023-06-28 01:43:56.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:56.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:56.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:56.000000 types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/LICENSE` & `types-aiobotocore-organizations-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/PKG-INFO` & `types-aiobotocore-organizations-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-organizations
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Organizations 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Organizations 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-organizations"></a>
 
 # types-aiobotocore-organizations
 
 [![PyPI - types-aiobotocore-organizations](https://img.shields.io/pypi/v/types-aiobotocore-organizations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-organizations)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-organizations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-organizations)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-organizations?color=blue)](https://pypistats.org/packages/types-aiobotocore-organizations)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Organizations 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
+[aiobotocore.Organizations 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
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
 [types-aiobotocore-organizations docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/).
 
 See how it helps to find and fix potential bugs:
 
@@ -399,15 +399,14 @@
 
 `types_aiobotocore_organizations.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_organizations.type_defs import (
     AcceptHandshakeRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AccountTypeDef,
     AttachPolicyRequestRequestTypeDef,
     CancelHandshakeRequestRequestTypeDef,
     ChildTypeDef,
     CloseAccountRequestRequestTypeDef,
     TagTypeDef,
     CreateAccountStatusTypeDef,
@@ -425,47 +424,62 @@
     EffectivePolicyTypeDef,
     DescribeHandshakeRequestRequestTypeDef,
     DescribeOrganizationalUnitRequestRequestTypeDef,
     DescribePolicyRequestRequestTypeDef,
     DetachPolicyRequestRequestTypeDef,
     DisableAWSServiceAccessRequestRequestTypeDef,
     DisablePolicyTypeRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableAWSServiceAccessRequestRequestTypeDef,
     EnablePolicyTypeRequestRequestTypeDef,
     EnabledServicePrincipalTypeDef,
     HandshakeFilterTypeDef,
     HandshakePartyTypeDef,
     HandshakeResourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef,
     ListAWSServiceAccessForOrganizationRequestRequestTypeDef,
+    ListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
     ListAccountsForParentRequestRequestTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
+    ListChildrenRequestListChildrenPaginateTypeDef,
     ListChildrenRequestRequestTypeDef,
+    ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef,
     ListCreateAccountStatusRequestRequestTypeDef,
+    ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef,
     ListDelegatedAdministratorsRequestRequestTypeDef,
+    ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
     ListDelegatedServicesForAccountRequestRequestTypeDef,
+    ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
     ListOrganizationalUnitsForParentRequestRequestTypeDef,
+    ListParentsRequestListParentsPaginateTypeDef,
     ListParentsRequestRequestTypeDef,
     ParentTypeDef,
+    ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
     ListPoliciesForTargetRequestRequestTypeDef,
     PolicySummaryTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListRootsRequestListRootsPaginateTypeDef,
     ListRootsRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListTargetsForPolicyRequestRequestTypeDef,
     PolicyTargetSummaryTypeDef,
     MoveAccountRequestRequestTypeDef,
     PolicyTypeSummaryTypeDef,
+    PaginatorConfigTypeDef,
     RegisterDelegatedAdministratorRequestRequestTypeDef,
     RemoveAccountFromOrganizationRequestRequestTypeDef,
     ResourcePolicySummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateOrganizationalUnitRequestRequestTypeDef,
     UpdatePolicyRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     DescribeAccountResponseTypeDef,
     ListAccountsForParentResponseTypeDef,
     ListAccountsResponseTypeDef,
     ListChildrenResponseTypeDef,
     CreateAccountRequestRequestTypeDef,
     CreateGovCloudAccountRequestRequestTypeDef,
     CreateOrganizationalUnitRequestRequestTypeDef,
@@ -481,34 +495,20 @@
     DescribeOrganizationalUnitResponseTypeDef,
     ListOrganizationalUnitsForParentResponseTypeDef,
     UpdateOrganizationalUnitResponseTypeDef,
     ListDelegatedAdministratorsResponseTypeDef,
     ListDelegatedServicesForAccountResponseTypeDef,
     DescribeEffectivePolicyResponseTypeDef,
     ListAWSServiceAccessForOrganizationResponseTypeDef,
+    ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef,
     ListHandshakesForAccountRequestRequestTypeDef,
+    ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef,
     ListHandshakesForOrganizationRequestRequestTypeDef,
     HandshakeTypeDef,
     InviteAccountToOrganizationRequestRequestTypeDef,
-    ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef,
-    ListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
-    ListChildrenRequestListChildrenPaginateTypeDef,
-    ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef,
-    ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef,
-    ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-    ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef,
-    ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef,
-    ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-    ListParentsRequestListParentsPaginateTypeDef,
-    ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListRootsRequestListRootsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListParentsResponseTypeDef,
     ListPoliciesForTargetResponseTypeDef,
     ListPoliciesResponseTypeDef,
     PolicyTypeDef,
     ListTargetsForPolicyResponseTypeDef,
     OrganizationTypeDef,
     RootTypeDef,
@@ -541,43 +541,43 @@
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/README.md` & `types-aiobotocore-organizations-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-organizations"></a>
 
 # types-aiobotocore-organizations
 
 [![PyPI - types-aiobotocore-organizations](https://img.shields.io/pypi/v/types-aiobotocore-organizations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-organizations)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-organizations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-organizations)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-organizations?color=blue)](https://pypistats.org/packages/types-aiobotocore-organizations)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Organizations 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
+[aiobotocore.Organizations 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
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
 [types-aiobotocore-organizations docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,15 +366,14 @@
 
 `types_aiobotocore_organizations.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_organizations.type_defs import (
     AcceptHandshakeRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AccountTypeDef,
     AttachPolicyRequestRequestTypeDef,
     CancelHandshakeRequestRequestTypeDef,
     ChildTypeDef,
     CloseAccountRequestRequestTypeDef,
     TagTypeDef,
     CreateAccountStatusTypeDef,
@@ -392,47 +391,62 @@
     EffectivePolicyTypeDef,
     DescribeHandshakeRequestRequestTypeDef,
     DescribeOrganizationalUnitRequestRequestTypeDef,
     DescribePolicyRequestRequestTypeDef,
     DetachPolicyRequestRequestTypeDef,
     DisableAWSServiceAccessRequestRequestTypeDef,
     DisablePolicyTypeRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableAWSServiceAccessRequestRequestTypeDef,
     EnablePolicyTypeRequestRequestTypeDef,
     EnabledServicePrincipalTypeDef,
     HandshakeFilterTypeDef,
     HandshakePartyTypeDef,
     HandshakeResourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef,
     ListAWSServiceAccessForOrganizationRequestRequestTypeDef,
+    ListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
     ListAccountsForParentRequestRequestTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
+    ListChildrenRequestListChildrenPaginateTypeDef,
     ListChildrenRequestRequestTypeDef,
+    ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef,
     ListCreateAccountStatusRequestRequestTypeDef,
+    ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef,
     ListDelegatedAdministratorsRequestRequestTypeDef,
+    ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
     ListDelegatedServicesForAccountRequestRequestTypeDef,
+    ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
     ListOrganizationalUnitsForParentRequestRequestTypeDef,
+    ListParentsRequestListParentsPaginateTypeDef,
     ListParentsRequestRequestTypeDef,
     ParentTypeDef,
+    ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
     ListPoliciesForTargetRequestRequestTypeDef,
     PolicySummaryTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListRootsRequestListRootsPaginateTypeDef,
     ListRootsRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListTargetsForPolicyRequestRequestTypeDef,
     PolicyTargetSummaryTypeDef,
     MoveAccountRequestRequestTypeDef,
     PolicyTypeSummaryTypeDef,
+    PaginatorConfigTypeDef,
     RegisterDelegatedAdministratorRequestRequestTypeDef,
     RemoveAccountFromOrganizationRequestRequestTypeDef,
     ResourcePolicySummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateOrganizationalUnitRequestRequestTypeDef,
     UpdatePolicyRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     DescribeAccountResponseTypeDef,
     ListAccountsForParentResponseTypeDef,
     ListAccountsResponseTypeDef,
     ListChildrenResponseTypeDef,
     CreateAccountRequestRequestTypeDef,
     CreateGovCloudAccountRequestRequestTypeDef,
     CreateOrganizationalUnitRequestRequestTypeDef,
@@ -448,34 +462,20 @@
     DescribeOrganizationalUnitResponseTypeDef,
     ListOrganizationalUnitsForParentResponseTypeDef,
     UpdateOrganizationalUnitResponseTypeDef,
     ListDelegatedAdministratorsResponseTypeDef,
     ListDelegatedServicesForAccountResponseTypeDef,
     DescribeEffectivePolicyResponseTypeDef,
     ListAWSServiceAccessForOrganizationResponseTypeDef,
+    ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef,
     ListHandshakesForAccountRequestRequestTypeDef,
+    ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef,
     ListHandshakesForOrganizationRequestRequestTypeDef,
     HandshakeTypeDef,
     InviteAccountToOrganizationRequestRequestTypeDef,
-    ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef,
-    ListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
-    ListChildrenRequestListChildrenPaginateTypeDef,
-    ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef,
-    ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef,
-    ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-    ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef,
-    ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef,
-    ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-    ListParentsRequestListParentsPaginateTypeDef,
-    ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListRootsRequestListRootsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListParentsResponseTypeDef,
     ListPoliciesForTargetResponseTypeDef,
     ListPoliciesResponseTypeDef,
     PolicyTypeDef,
     ListTargetsForPolicyResponseTypeDef,
     OrganizationTypeDef,
     RootTypeDef,
@@ -508,43 +508,43 @@
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/setup.py` & `types-aiobotocore-organizations-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-organizations.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-organizations",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_organizations"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Organizations 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Organizations 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/"
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/__init__.py` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/__init__.pyi` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/__main__.py` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Organizations 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Organizations 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations\nOther"
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/client.py` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -250,16 +250,16 @@
         Email: str,
         AccountName: str,
         RoleName: str = ...,
         IamUserAccessToBilling: IAMUserAccessToBillingType = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateGovCloudAccountResponseTypeDef:
         """
-        This action is available if all of the following are true * You're authorized to
-        create accounts in the Amazon Web Services GovCloud (US) Region.
+        This action is available if all of the following are true: * You're authorized
+        to create accounts in the Amazon Web Services GovCloud (US) Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Client.create_gov_cloud_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#create_gov_cloud_account)
         """
 
     async def create_organization(
         self, *, FeatureSet: OrganizationFeatureSetType = ...
@@ -431,15 +431,15 @@
         """
 
     async def disable_aws_service_access(
         self, *, ServicePrincipal: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Disables the integration of an Amazon Web Services service (the service that is
-        specified by `ServicePrincipal` ) with Organizations.
+        specified by `ServicePrincipal`) with Organizations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Client.disable_aws_service_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#disable_aws_service_access)
         """
 
     async def disable_policy_type(
         self, *, RootId: str, PolicyType: PolicyTypeType
@@ -460,15 +460,15 @@
         """
 
     async def enable_aws_service_access(
         self, *, ServicePrincipal: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Enables the integration of an Amazon Web Services service (the service that is
-        specified by `ServicePrincipal` ) with Organizations.
+        specified by `ServicePrincipal`) with Organizations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Client.enable_aws_service_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#enable_aws_service_access)
         """
 
     async def enable_policy_type(
         self, *, RootId: str, PolicyType: PolicyTypeType
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/client.pyi` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -238,16 +238,16 @@
         Email: str,
         AccountName: str,
         RoleName: str = ...,
         IamUserAccessToBilling: IAMUserAccessToBillingType = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateGovCloudAccountResponseTypeDef:
         """
-        This action is available if all of the following are true * You're authorized to
-        create accounts in the Amazon Web Services GovCloud (US) Region.
+        This action is available if all of the following are true: * You're authorized
+        to create accounts in the Amazon Web Services GovCloud (US) Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Client.create_gov_cloud_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#create_gov_cloud_account)
         """
     async def create_organization(
         self, *, FeatureSet: OrganizationFeatureSetType = ...
     ) -> CreateOrganizationResponseTypeDef:
@@ -400,15 +400,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#detach_policy)
         """
     async def disable_aws_service_access(
         self, *, ServicePrincipal: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Disables the integration of an Amazon Web Services service (the service that is
-        specified by `ServicePrincipal` ) with Organizations.
+        specified by `ServicePrincipal`) with Organizations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Client.disable_aws_service_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#disable_aws_service_access)
         """
     async def disable_policy_type(
         self, *, RootId: str, PolicyType: PolicyTypeType
     ) -> DisablePolicyTypeResponseTypeDef:
@@ -426,15 +426,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#enable_all_features)
         """
     async def enable_aws_service_access(
         self, *, ServicePrincipal: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Enables the integration of an Amazon Web Services service (the service that is
-        specified by `ServicePrincipal` ) with Organizations.
+        specified by `ServicePrincipal`) with Organizations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Client.enable_aws_service_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/client/#enable_aws_service_access)
         """
     async def enable_policy_type(
         self, *, RootId: str, PolicyType: PolicyTypeType
     ) -> EnablePolicyTypeResponseTypeDef:
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/literals.py` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AccountJoinedMethodType",
     "AccountStatusType",
     "ActionTypeType",
     "ChildTypeType",
     "CreateAccountFailureReasonType",
     "CreateAccountStateType",
@@ -54,15 +53,14 @@
     "TargetTypeType",
     "OrganizationsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 AccountJoinedMethodType = Literal["CREATED", "INVITED"]
 AccountStatusType = Literal["ACTIVE", "PENDING_CLOSURE", "SUSPENDED"]
 ActionTypeType = Literal[
     "ADD_ORGANIZATIONS_SERVICE_LINKED_ROLE", "APPROVE_ALL_FEATURES", "ENABLE_ALL_FEATURES", "INVITE"
 ]
 ChildTypeType = Literal["ACCOUNT", "ORGANIZATIONAL_UNIT"]
 CreateAccountFailureReasonType = Literal[
@@ -181,14 +179,15 @@
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
@@ -267,14 +266,15 @@
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
@@ -285,14 +285,15 @@
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
@@ -328,14 +329,15 @@
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
@@ -354,16 +356,19 @@
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
@@ -447,15 +452,17 @@
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/literals.pyi` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/literals.py`

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
     "AccountJoinedMethodType",
     "AccountStatusType",
     "ActionTypeType",
     "ChildTypeType",
     "CreateAccountFailureReasonType",
     "CreateAccountStateType",
@@ -53,14 +54,15 @@
     "TargetTypeType",
     "OrganizationsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 AccountJoinedMethodType = Literal["CREATED", "INVITED"]
 AccountStatusType = Literal["ACTIVE", "PENDING_CLOSURE", "SUSPENDED"]
 ActionTypeType = Literal[
     "ADD_ORGANIZATIONS_SERVICE_LINKED_ROLE", "APPROVE_ALL_FEATURES", "ENABLE_ALL_FEATURES", "INVITE"
 ]
 ChildTypeType = Literal["ACCOUNT", "ORGANIZATIONAL_UNIT"]
 CreateAccountFailureReasonType = Literal[
@@ -179,14 +181,15 @@
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
@@ -265,14 +268,15 @@
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
@@ -283,14 +287,15 @@
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
@@ -326,14 +331,15 @@
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
@@ -352,16 +358,19 @@
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
@@ -445,15 +454,17 @@
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/paginator.py` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,16 +46,15 @@
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
         list_policies_for_target_paginator: ListPoliciesForTargetPaginator = client.get_paginator("list_policies_for_target")
         list_roots_paginator: ListRootsPaginator = client.get_paginator("list_roots")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_targets_for_policy_paginator: ListTargetsForPolicyPaginator = client.get_paginator("list_targets_for_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ChildTypeType, CreateAccountStateType, PolicyTypeType
 from .type_defs import (
     HandshakeFilterTypeDef,
@@ -74,20 +73,14 @@
     ListPoliciesResponseTypeDef,
     ListRootsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTargetsForPolicyResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAWSServiceAccessForOrganizationPaginator",
     "ListAccountsPaginator",
     "ListAccountsForParentPaginator",
     "ListChildrenPaginator",
     "ListCreateAccountStatusPaginator",
     "ListDelegatedAdministratorsPaginator",
@@ -117,45 +110,45 @@
 class ListAWSServiceAccessForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAWSServiceAccessForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listawsserviceaccessfororganizationpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAWSServiceAccessForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAWSServiceAccessForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listawsserviceaccessfororganizationpaginator)
         """
 
 
 class ListAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountspaginator)
         """
 
 
 class ListAccountsForParentPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccountsForParent)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountsforparentpaginator)
     """
 
     def paginate(
-        self, *, ParentId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParentId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsForParentResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccountsForParent.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountsforparentpaginator)
         """
 
 
@@ -166,15 +159,15 @@
     """
 
     def paginate(
         self,
         *,
         ParentId: str,
         ChildType: ChildTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChildrenResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListChildren.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listchildrenpaginator)
         """
 
 
@@ -184,45 +177,45 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listcreateaccountstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         States: Sequence[CreateAccountStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCreateAccountStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListCreateAccountStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listcreateaccountstatuspaginator)
         """
 
 
 class ListDelegatedAdministratorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedAdministrators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedadministratorspaginator)
     """
 
     def paginate(
-        self, *, ServicePrincipal: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServicePrincipal: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDelegatedAdministratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedAdministrators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedadministratorspaginator)
         """
 
 
 class ListDelegatedServicesForAccountPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedServicesForAccount)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedservicesforaccountpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDelegatedServicesForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedServicesForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedservicesforaccountpaginator)
         """
 
 
@@ -232,15 +225,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesforaccountpaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: HandshakeFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHandshakesForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListHandshakesForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesforaccountpaginator)
         """
 
 
@@ -250,60 +243,60 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesfororganizationpaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: HandshakeFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHandshakesForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListHandshakesForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesfororganizationpaginator)
         """
 
 
 class ListOrganizationalUnitsForParentPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListOrganizationalUnitsForParent)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listorganizationalunitsforparentpaginator)
     """
 
     def paginate(
-        self, *, ParentId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParentId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationalUnitsForParentResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListOrganizationalUnitsForParent.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listorganizationalunitsforparentpaginator)
         """
 
 
 class ListParentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListParents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listparentspaginator)
     """
 
     def paginate(
-        self, *, ChildId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ChildId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListParentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListParents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listparentspaginator)
         """
 
 
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listpoliciespaginator)
     """
 
     def paginate(
-        self, *, Filter: PolicyTypeType, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Filter: PolicyTypeType, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listpoliciespaginator)
         """
 
 
@@ -314,58 +307,58 @@
     """
 
     def paginate(
         self,
         *,
         TargetId: str,
         Filter: PolicyTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesForTargetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPoliciesForTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listpoliciesfortargetpaginator)
         """
 
 
 class ListRootsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListRoots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listrootspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRootsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListRoots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listrootspaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtagsforresourcepaginator)
         """
 
 
 class ListTargetsForPolicyPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTargetsForPolicy)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtargetsforpolicypaginator)
     """
 
     def paginate(
-        self, *, PolicyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PolicyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsForPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTargetsForPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtargetsforpolicypaginator)
         """
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/paginator.pyi` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -46,16 +46,15 @@
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
         list_policies_for_target_paginator: ListPoliciesForTargetPaginator = client.get_paginator("list_policies_for_target")
         list_roots_paginator: ListRootsPaginator = client.get_paginator("list_roots")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_targets_for_policy_paginator: ListTargetsForPolicyPaginator = client.get_paginator("list_targets_for_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ChildTypeType, CreateAccountStateType, PolicyTypeType
 from .type_defs import (
     HandshakeFilterTypeDef,
@@ -74,19 +73,14 @@
     ListPoliciesResponseTypeDef,
     ListRootsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTargetsForPolicyResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAWSServiceAccessForOrganizationPaginator",
     "ListAccountsPaginator",
     "ListAccountsForParentPaginator",
     "ListChildrenPaginator",
     "ListCreateAccountStatusPaginator",
     "ListDelegatedAdministratorsPaginator",
@@ -113,43 +107,43 @@
 class ListAWSServiceAccessForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAWSServiceAccessForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listawsserviceaccessfororganizationpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAWSServiceAccessForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAWSServiceAccessForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listawsserviceaccessfororganizationpaginator)
         """
 
 class ListAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountspaginator)
         """
 
 class ListAccountsForParentPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccountsForParent)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountsforparentpaginator)
     """
 
     def paginate(
-        self, *, ParentId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParentId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsForParentResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListAccountsForParent.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listaccountsforparentpaginator)
         """
 
 class ListChildrenPaginator(AioPaginator):
@@ -159,15 +153,15 @@
     """
 
     def paginate(
         self,
         *,
         ParentId: str,
         ChildType: ChildTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChildrenResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListChildren.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listchildrenpaginator)
         """
 
 class ListCreateAccountStatusPaginator(AioPaginator):
@@ -176,43 +170,43 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listcreateaccountstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         States: Sequence[CreateAccountStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCreateAccountStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListCreateAccountStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listcreateaccountstatuspaginator)
         """
 
 class ListDelegatedAdministratorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedAdministrators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedadministratorspaginator)
     """
 
     def paginate(
-        self, *, ServicePrincipal: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServicePrincipal: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDelegatedAdministratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedAdministrators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedadministratorspaginator)
         """
 
 class ListDelegatedServicesForAccountPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedServicesForAccount)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedservicesforaccountpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDelegatedServicesForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListDelegatedServicesForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listdelegatedservicesforaccountpaginator)
         """
 
 class ListHandshakesForAccountPaginator(AioPaginator):
@@ -221,15 +215,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesforaccountpaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: HandshakeFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHandshakesForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListHandshakesForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesforaccountpaginator)
         """
 
 class ListHandshakesForOrganizationPaginator(AioPaginator):
@@ -238,57 +232,57 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesfororganizationpaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: HandshakeFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHandshakesForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListHandshakesForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listhandshakesfororganizationpaginator)
         """
 
 class ListOrganizationalUnitsForParentPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListOrganizationalUnitsForParent)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listorganizationalunitsforparentpaginator)
     """
 
     def paginate(
-        self, *, ParentId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParentId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationalUnitsForParentResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListOrganizationalUnitsForParent.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listorganizationalunitsforparentpaginator)
         """
 
 class ListParentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListParents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listparentspaginator)
     """
 
     def paginate(
-        self, *, ChildId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ChildId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListParentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListParents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listparentspaginator)
         """
 
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listpoliciespaginator)
     """
 
     def paginate(
-        self, *, Filter: PolicyTypeType, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Filter: PolicyTypeType, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listpoliciespaginator)
         """
 
 class ListPoliciesForTargetPaginator(AioPaginator):
@@ -298,55 +292,55 @@
     """
 
     def paginate(
         self,
         *,
         TargetId: str,
         Filter: PolicyTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesForTargetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListPoliciesForTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listpoliciesfortargetpaginator)
         """
 
 class ListRootsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListRoots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listrootspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRootsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListRoots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listrootspaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtagsforresourcepaginator)
         """
 
 class ListTargetsForPolicyPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTargetsForPolicy)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtargetsforpolicypaginator)
     """
 
     def paginate(
-        self, *, PolicyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PolicyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsForPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations.Paginator.ListTargetsForPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/paginators/#listtargetsforpolicypaginator)
         """
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/type_defs.py` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptHandshakeRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AccountTypeDef",
     "AttachPolicyRequestRequestTypeDef",
     "CancelHandshakeRequestRequestTypeDef",
     "ChildTypeDef",
     "CloseAccountRequestRequestTypeDef",
     "TagTypeDef",
     "CreateAccountStatusTypeDef",
@@ -64,47 +63,62 @@
     "EffectivePolicyTypeDef",
     "DescribeHandshakeRequestRequestTypeDef",
     "DescribeOrganizationalUnitRequestRequestTypeDef",
     "DescribePolicyRequestRequestTypeDef",
     "DetachPolicyRequestRequestTypeDef",
     "DisableAWSServiceAccessRequestRequestTypeDef",
     "DisablePolicyTypeRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableAWSServiceAccessRequestRequestTypeDef",
     "EnablePolicyTypeRequestRequestTypeDef",
     "EnabledServicePrincipalTypeDef",
     "HandshakeFilterTypeDef",
     "HandshakePartyTypeDef",
     "HandshakeResourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
     "ListAWSServiceAccessForOrganizationRequestRequestTypeDef",
+    "ListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
     "ListAccountsForParentRequestRequestTypeDef",
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountsRequestRequestTypeDef",
+    "ListChildrenRequestListChildrenPaginateTypeDef",
     "ListChildrenRequestRequestTypeDef",
+    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
     "ListCreateAccountStatusRequestRequestTypeDef",
+    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
     "ListDelegatedAdministratorsRequestRequestTypeDef",
+    "ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
     "ListDelegatedServicesForAccountRequestRequestTypeDef",
+    "ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
     "ListOrganizationalUnitsForParentRequestRequestTypeDef",
+    "ListParentsRequestListParentsPaginateTypeDef",
     "ListParentsRequestRequestTypeDef",
     "ParentTypeDef",
+    "ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
     "ListPoliciesForTargetRequestRequestTypeDef",
     "PolicySummaryTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
+    "ListRootsRequestListRootsPaginateTypeDef",
     "ListRootsRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
     "ListTargetsForPolicyRequestRequestTypeDef",
     "PolicyTargetSummaryTypeDef",
     "MoveAccountRequestRequestTypeDef",
     "PolicyTypeSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "RegisterDelegatedAdministratorRequestRequestTypeDef",
     "RemoveAccountFromOrganizationRequestRequestTypeDef",
     "ResourcePolicySummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateOrganizationalUnitRequestRequestTypeDef",
     "UpdatePolicyRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "DescribeAccountResponseTypeDef",
     "ListAccountsForParentResponseTypeDef",
     "ListAccountsResponseTypeDef",
     "ListChildrenResponseTypeDef",
     "CreateAccountRequestRequestTypeDef",
     "CreateGovCloudAccountRequestRequestTypeDef",
     "CreateOrganizationalUnitRequestRequestTypeDef",
@@ -120,34 +134,20 @@
     "DescribeOrganizationalUnitResponseTypeDef",
     "ListOrganizationalUnitsForParentResponseTypeDef",
     "UpdateOrganizationalUnitResponseTypeDef",
     "ListDelegatedAdministratorsResponseTypeDef",
     "ListDelegatedServicesForAccountResponseTypeDef",
     "DescribeEffectivePolicyResponseTypeDef",
     "ListAWSServiceAccessForOrganizationResponseTypeDef",
+    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
     "ListHandshakesForAccountRequestRequestTypeDef",
+    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
     "ListHandshakesForOrganizationRequestRequestTypeDef",
     "HandshakeTypeDef",
     "InviteAccountToOrganizationRequestRequestTypeDef",
-    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
-    "ListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    "ListChildrenRequestListChildrenPaginateTypeDef",
-    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
-    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
-    "ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
-    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
-    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
-    "ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
-    "ListParentsRequestListParentsPaginateTypeDef",
-    "ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListRootsRequestListRootsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
     "ListParentsResponseTypeDef",
     "ListPoliciesForTargetResponseTypeDef",
     "ListPoliciesResponseTypeDef",
     "PolicyTypeDef",
     "ListTargetsForPolicyResponseTypeDef",
     "OrganizationTypeDef",
     "RootTypeDef",
@@ -175,25 +175,14 @@
 AcceptHandshakeRequestRequestTypeDef = TypedDict(
     "AcceptHandshakeRequestRequestTypeDef",
     {
         "HandshakeId": str,
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
 AccountTypeDef = TypedDict(
     "AccountTypeDef",
     {
         "Id": str,
         "Arn": str,
         "Email": str,
         "Name": str,
@@ -416,14 +405,21 @@
     "DisablePolicyTypeRequestRequestTypeDef",
     {
         "RootId": str,
         "PolicyType": PolicyTypeType,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableAWSServiceAccessRequestRequestTypeDef = TypedDict(
     "EnableAWSServiceAccessRequestRequestTypeDef",
     {
         "ServicePrincipal": str,
     },
 )
 
@@ -467,33 +463,53 @@
         "Value": str,
         "Type": HandshakeResourceTypeType,
         "Resources": List[Dict[str, Any]],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef = TypedDict(
+    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAWSServiceAccessForOrganizationRequestRequestTypeDef = TypedDict(
     "ListAWSServiceAccessForOrganizationRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
+    "_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
+    {
+        "ParentId": str,
+    },
+)
+_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
+    "_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAccountsForParentRequestListAccountsForParentPaginateTypeDef(
+    _RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
+    _OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccountsForParentRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountsForParentRequestRequestTypeDef",
     {
         "ParentId": str,
     },
 )
 _OptionalListAccountsForParentRequestRequestTypeDef = TypedDict(
@@ -509,23 +525,54 @@
 class ListAccountsForParentRequestRequestTypeDef(
     _RequiredListAccountsForParentRequestRequestTypeDef,
     _OptionalListAccountsForParentRequestRequestTypeDef,
 ):
     pass
 
 
+ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "ListAccountsRequestListAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAccountsRequestRequestTypeDef = TypedDict(
     "ListAccountsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
+    "_RequiredListChildrenRequestListChildrenPaginateTypeDef",
+    {
+        "ParentId": str,
+        "ChildType": ChildTypeType,
+    },
+)
+_OptionalListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
+    "_OptionalListChildrenRequestListChildrenPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListChildrenRequestListChildrenPaginateTypeDef(
+    _RequiredListChildrenRequestListChildrenPaginateTypeDef,
+    _OptionalListChildrenRequestListChildrenPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListChildrenRequestRequestTypeDef = TypedDict(
     "_RequiredListChildrenRequestRequestTypeDef",
     {
         "ParentId": str,
         "ChildType": ChildTypeType,
     },
 )
@@ -541,34 +588,74 @@
 
 class ListChildrenRequestRequestTypeDef(
     _RequiredListChildrenRequestRequestTypeDef, _OptionalListChildrenRequestRequestTypeDef
 ):
     pass
 
 
+ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef = TypedDict(
+    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
+    {
+        "States": Sequence[CreateAccountStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCreateAccountStatusRequestRequestTypeDef = TypedDict(
     "ListCreateAccountStatusRequestRequestTypeDef",
     {
         "States": Sequence[CreateAccountStateType],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef = TypedDict(
+    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
+    {
+        "ServicePrincipal": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDelegatedAdministratorsRequestRequestTypeDef = TypedDict(
     "ListDelegatedAdministratorsRequestRequestTypeDef",
     {
         "ServicePrincipal": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
+    "_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
+    "_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef(
+    _RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
+    _OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDelegatedServicesForAccountRequestRequestTypeDef = TypedDict(
     "_RequiredListDelegatedServicesForAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListDelegatedServicesForAccountRequestRequestTypeDef = TypedDict(
@@ -584,14 +671,36 @@
 class ListDelegatedServicesForAccountRequestRequestTypeDef(
     _RequiredListDelegatedServicesForAccountRequestRequestTypeDef,
     _OptionalListDelegatedServicesForAccountRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
+    "_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
+    {
+        "ParentId": str,
+    },
+)
+_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
+    "_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef(
+    _RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
+    _OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListOrganizationalUnitsForParentRequestRequestTypeDef = TypedDict(
     "_RequiredListOrganizationalUnitsForParentRequestRequestTypeDef",
     {
         "ParentId": str,
     },
 )
 _OptionalListOrganizationalUnitsForParentRequestRequestTypeDef = TypedDict(
@@ -607,14 +716,36 @@
 class ListOrganizationalUnitsForParentRequestRequestTypeDef(
     _RequiredListOrganizationalUnitsForParentRequestRequestTypeDef,
     _OptionalListOrganizationalUnitsForParentRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListParentsRequestListParentsPaginateTypeDef = TypedDict(
+    "_RequiredListParentsRequestListParentsPaginateTypeDef",
+    {
+        "ChildId": str,
+    },
+)
+_OptionalListParentsRequestListParentsPaginateTypeDef = TypedDict(
+    "_OptionalListParentsRequestListParentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListParentsRequestListParentsPaginateTypeDef(
+    _RequiredListParentsRequestListParentsPaginateTypeDef,
+    _OptionalListParentsRequestListParentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListParentsRequestRequestTypeDef = TypedDict(
     "_RequiredListParentsRequestRequestTypeDef",
     {
         "ChildId": str,
     },
 )
 _OptionalListParentsRequestRequestTypeDef = TypedDict(
@@ -638,14 +769,37 @@
     {
         "Id": str,
         "Type": ParentTypeType,
     },
     total=False,
 )
 
+_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
+    "_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
+    {
+        "TargetId": str,
+        "Filter": PolicyTypeType,
+    },
+)
+_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
+    "_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef(
+    _RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
+    _OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPoliciesForTargetRequestRequestTypeDef = TypedDict(
     "_RequiredListPoliciesForTargetRequestRequestTypeDef",
     {
         "TargetId": str,
         "Filter": PolicyTypeType,
     },
 )
@@ -675,14 +829,36 @@
         "Description": str,
         "Type": PolicyTypeType,
         "AwsManaged": bool,
     },
     total=False,
 )
 
+_RequiredListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "Filter": PolicyTypeType,
+    },
+)
+_OptionalListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPoliciesRequestListPoliciesPaginateTypeDef(
+    _RequiredListPoliciesRequestListPoliciesPaginateTypeDef,
+    _OptionalListPoliciesRequestListPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListPoliciesRequestRequestTypeDef",
     {
         "Filter": PolicyTypeType,
     },
 )
 _OptionalListPoliciesRequestRequestTypeDef = TypedDict(
@@ -697,23 +873,53 @@
 
 class ListPoliciesRequestRequestTypeDef(
     _RequiredListPoliciesRequestRequestTypeDef, _OptionalListPoliciesRequestRequestTypeDef
 ):
     pass
 
 
+ListRootsRequestListRootsPaginateTypeDef = TypedDict(
+    "ListRootsRequestListRootsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRootsRequestRequestTypeDef = TypedDict(
     "ListRootsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceId": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceId": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -728,14 +934,36 @@
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "PolicyId": str,
+    },
+)
+_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
+    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTargetsForPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsForPolicyRequestRequestTypeDef",
     {
         "PolicyId": str,
     },
 )
 _OptionalListTargetsForPolicyRequestRequestTypeDef = TypedDict(
@@ -780,14 +1008,24 @@
     {
         "Type": PolicyTypeType,
         "Status": PolicyTypeStatusType,
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
 RegisterDelegatedAdministratorRequestRequestTypeDef = TypedDict(
     "RegisterDelegatedAdministratorRequestRequestTypeDef",
     {
         "AccountId": str,
         "ServicePrincipal": str,
     },
 )
@@ -804,14 +1042,25 @@
     {
         "Id": str,
         "Arn": str,
     },
     total=False,
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
         "ResourceId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -857,53 +1106,46 @@
 
 class UpdatePolicyRequestRequestTypeDef(
     _RequiredUpdatePolicyRequestRequestTypeDef, _OptionalUpdatePolicyRequestRequestTypeDef
 ):
     pass
 
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeAccountResponseTypeDef = TypedDict(
     "DescribeAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountsForParentResponseTypeDef = TypedDict(
     "ListAccountsForParentResponseTypeDef",
     {
         "Accounts": List[AccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountsResponseTypeDef = TypedDict(
     "ListAccountsResponseTypeDef",
     {
         "Accounts": List[AccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChildrenResponseTypeDef = TypedDict(
     "ListChildrenResponseTypeDef",
     {
         "Children": List[ChildTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAccountRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAccountRequestRequestTypeDef",
     {
         "Email": str,
@@ -1000,15 +1242,15 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "Content": str,
@@ -1037,121 +1279,139 @@
     },
 )
 
 CreateAccountResponseTypeDef = TypedDict(
     "CreateAccountResponseTypeDef",
     {
         "CreateAccountStatus": CreateAccountStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGovCloudAccountResponseTypeDef = TypedDict(
     "CreateGovCloudAccountResponseTypeDef",
     {
         "CreateAccountStatus": CreateAccountStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCreateAccountStatusResponseTypeDef = TypedDict(
     "DescribeCreateAccountStatusResponseTypeDef",
     {
         "CreateAccountStatus": CreateAccountStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCreateAccountStatusResponseTypeDef = TypedDict(
     "ListCreateAccountStatusResponseTypeDef",
     {
         "CreateAccountStatuses": List[CreateAccountStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOrganizationalUnitResponseTypeDef = TypedDict(
     "CreateOrganizationalUnitResponseTypeDef",
     {
         "OrganizationalUnit": OrganizationalUnitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationalUnitResponseTypeDef = TypedDict(
     "DescribeOrganizationalUnitResponseTypeDef",
     {
         "OrganizationalUnit": OrganizationalUnitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOrganizationalUnitsForParentResponseTypeDef = TypedDict(
     "ListOrganizationalUnitsForParentResponseTypeDef",
     {
         "OrganizationalUnits": List[OrganizationalUnitTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateOrganizationalUnitResponseTypeDef = TypedDict(
     "UpdateOrganizationalUnitResponseTypeDef",
     {
         "OrganizationalUnit": OrganizationalUnitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDelegatedAdministratorsResponseTypeDef = TypedDict(
     "ListDelegatedAdministratorsResponseTypeDef",
     {
         "DelegatedAdministrators": List[DelegatedAdministratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDelegatedServicesForAccountResponseTypeDef = TypedDict(
     "ListDelegatedServicesForAccountResponseTypeDef",
     {
         "DelegatedServices": List[DelegatedServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEffectivePolicyResponseTypeDef = TypedDict(
     "DescribeEffectivePolicyResponseTypeDef",
     {
         "EffectivePolicy": EffectivePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAWSServiceAccessForOrganizationResponseTypeDef = TypedDict(
     "ListAWSServiceAccessForOrganizationResponseTypeDef",
     {
         "EnabledServicePrincipals": List[EnabledServicePrincipalTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef = TypedDict(
+    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
+    {
+        "Filter": HandshakeFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListHandshakesForAccountRequestRequestTypeDef = TypedDict(
     "ListHandshakesForAccountRequestRequestTypeDef",
     {
         "Filter": HandshakeFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef = TypedDict(
+    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
+    {
+        "Filter": HandshakeFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHandshakesForOrganizationRequestRequestTypeDef = TypedDict(
     "ListHandshakesForOrganizationRequestRequestTypeDef",
     {
         "Filter": HandshakeFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -1192,298 +1452,38 @@
 class InviteAccountToOrganizationRequestRequestTypeDef(
     _RequiredInviteAccountToOrganizationRequestRequestTypeDef,
     _OptionalInviteAccountToOrganizationRequestRequestTypeDef,
 ):
     pass
 
 
-ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef = TypedDict(
-    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
-    "_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
-    {
-        "ParentId": str,
-    },
-)
-_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
-    "_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAccountsForParentRequestListAccountsForParentPaginateTypeDef(
-    _RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-    _OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-):
-    pass
-
-
-ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
-    "_RequiredListChildrenRequestListChildrenPaginateTypeDef",
-    {
-        "ParentId": str,
-        "ChildType": ChildTypeType,
-    },
-)
-_OptionalListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
-    "_OptionalListChildrenRequestListChildrenPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListChildrenRequestListChildrenPaginateTypeDef(
-    _RequiredListChildrenRequestListChildrenPaginateTypeDef,
-    _OptionalListChildrenRequestListChildrenPaginateTypeDef,
-):
-    pass
-
-
-ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef = TypedDict(
-    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
-    {
-        "States": Sequence[CreateAccountStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef = TypedDict(
-    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
-    {
-        "ServicePrincipal": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
-    "_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
-    "_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef(
-    _RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-    _OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-):
-    pass
-
-
-ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef = TypedDict(
-    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
-    {
-        "Filter": HandshakeFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef = TypedDict(
-    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
-    {
-        "Filter": HandshakeFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
-    "_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
-    {
-        "ParentId": str,
-    },
-)
-_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
-    "_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef(
-    _RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-    _OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListParentsRequestListParentsPaginateTypeDef = TypedDict(
-    "_RequiredListParentsRequestListParentsPaginateTypeDef",
-    {
-        "ChildId": str,
-    },
-)
-_OptionalListParentsRequestListParentsPaginateTypeDef = TypedDict(
-    "_OptionalListParentsRequestListParentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListParentsRequestListParentsPaginateTypeDef(
-    _RequiredListParentsRequestListParentsPaginateTypeDef,
-    _OptionalListParentsRequestListParentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
-    "_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
-    {
-        "TargetId": str,
-        "Filter": PolicyTypeType,
-    },
-)
-_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
-    "_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef(
-    _RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-    _OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "Filter": PolicyTypeType,
-    },
-)
-_OptionalListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPoliciesRequestListPoliciesPaginateTypeDef(
-    _RequiredListPoliciesRequestListPoliciesPaginateTypeDef,
-    _OptionalListPoliciesRequestListPoliciesPaginateTypeDef,
-):
-    pass
-
-
-ListRootsRequestListRootsPaginateTypeDef = TypedDict(
-    "ListRootsRequestListRootsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceId": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "PolicyId": str,
-    },
-)
-_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
-    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-):
-    pass
-
-
 ListParentsResponseTypeDef = TypedDict(
     "ListParentsResponseTypeDef",
     {
         "Parents": List[ParentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesForTargetResponseTypeDef = TypedDict(
     "ListPoliciesForTargetResponseTypeDef",
     {
         "Policies": List[PolicySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "Policies": List[PolicySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyTypeDef = TypedDict(
     "PolicyTypeDef",
     {
         "PolicySummary": PolicySummaryTypeDef,
@@ -1493,15 +1493,15 @@
 )
 
 ListTargetsForPolicyResponseTypeDef = TypedDict(
     "ListTargetsForPolicyResponseTypeDef",
     {
         "Targets": List[PolicyTargetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrganizationTypeDef = TypedDict(
     "OrganizationTypeDef",
     {
         "Id": str,
@@ -1535,149 +1535,149 @@
     total=False,
 )
 
 AcceptHandshakeResponseTypeDef = TypedDict(
     "AcceptHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelHandshakeResponseTypeDef = TypedDict(
     "CancelHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineHandshakeResponseTypeDef = TypedDict(
     "DeclineHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHandshakeResponseTypeDef = TypedDict(
     "DescribeHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableAllFeaturesResponseTypeDef = TypedDict(
     "EnableAllFeaturesResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteAccountToOrganizationResponseTypeDef = TypedDict(
     "InviteAccountToOrganizationResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHandshakesForAccountResponseTypeDef = TypedDict(
     "ListHandshakesForAccountResponseTypeDef",
     {
         "Handshakes": List[HandshakeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHandshakesForOrganizationResponseTypeDef = TypedDict(
     "ListHandshakesForOrganizationResponseTypeDef",
     {
         "Handshakes": List[HandshakeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePolicyResponseTypeDef = TypedDict(
     "CreatePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePolicyResponseTypeDef = TypedDict(
     "DescribePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePolicyResponseTypeDef = TypedDict(
     "UpdatePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOrganizationResponseTypeDef = TypedDict(
     "CreateOrganizationResponseTypeDef",
     {
         "Organization": OrganizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationResponseTypeDef = TypedDict(
     "DescribeOrganizationResponseTypeDef",
     {
         "Organization": OrganizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisablePolicyTypeResponseTypeDef = TypedDict(
     "DisablePolicyTypeResponseTypeDef",
     {
         "Root": RootTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnablePolicyTypeResponseTypeDef = TypedDict(
     "EnablePolicyTypeResponseTypeDef",
     {
         "Root": RootTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRootsResponseTypeDef = TypedDict(
     "ListRootsResponseTypeDef",
     {
         "Roots": List[RootTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeResourcePolicyResponseTypeDef = TypedDict(
     "DescribeResourcePolicyResponseTypeDef",
     {
         "ResourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourcePolicyResponseTypeDef = TypedDict(
     "PutResourcePolicyResponseTypeDef",
     {
         "ResourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations/type_defs.pyi` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -37,15 +37,14 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptHandshakeRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AccountTypeDef",
     "AttachPolicyRequestRequestTypeDef",
     "CancelHandshakeRequestRequestTypeDef",
     "ChildTypeDef",
     "CloseAccountRequestRequestTypeDef",
     "TagTypeDef",
     "CreateAccountStatusTypeDef",
@@ -63,47 +62,62 @@
     "EffectivePolicyTypeDef",
     "DescribeHandshakeRequestRequestTypeDef",
     "DescribeOrganizationalUnitRequestRequestTypeDef",
     "DescribePolicyRequestRequestTypeDef",
     "DetachPolicyRequestRequestTypeDef",
     "DisableAWSServiceAccessRequestRequestTypeDef",
     "DisablePolicyTypeRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableAWSServiceAccessRequestRequestTypeDef",
     "EnablePolicyTypeRequestRequestTypeDef",
     "EnabledServicePrincipalTypeDef",
     "HandshakeFilterTypeDef",
     "HandshakePartyTypeDef",
     "HandshakeResourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
     "ListAWSServiceAccessForOrganizationRequestRequestTypeDef",
+    "ListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
     "ListAccountsForParentRequestRequestTypeDef",
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountsRequestRequestTypeDef",
+    "ListChildrenRequestListChildrenPaginateTypeDef",
     "ListChildrenRequestRequestTypeDef",
+    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
     "ListCreateAccountStatusRequestRequestTypeDef",
+    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
     "ListDelegatedAdministratorsRequestRequestTypeDef",
+    "ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
     "ListDelegatedServicesForAccountRequestRequestTypeDef",
+    "ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
     "ListOrganizationalUnitsForParentRequestRequestTypeDef",
+    "ListParentsRequestListParentsPaginateTypeDef",
     "ListParentsRequestRequestTypeDef",
     "ParentTypeDef",
+    "ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
     "ListPoliciesForTargetRequestRequestTypeDef",
     "PolicySummaryTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
+    "ListRootsRequestListRootsPaginateTypeDef",
     "ListRootsRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
     "ListTargetsForPolicyRequestRequestTypeDef",
     "PolicyTargetSummaryTypeDef",
     "MoveAccountRequestRequestTypeDef",
     "PolicyTypeSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "RegisterDelegatedAdministratorRequestRequestTypeDef",
     "RemoveAccountFromOrganizationRequestRequestTypeDef",
     "ResourcePolicySummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateOrganizationalUnitRequestRequestTypeDef",
     "UpdatePolicyRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "DescribeAccountResponseTypeDef",
     "ListAccountsForParentResponseTypeDef",
     "ListAccountsResponseTypeDef",
     "ListChildrenResponseTypeDef",
     "CreateAccountRequestRequestTypeDef",
     "CreateGovCloudAccountRequestRequestTypeDef",
     "CreateOrganizationalUnitRequestRequestTypeDef",
@@ -119,34 +133,20 @@
     "DescribeOrganizationalUnitResponseTypeDef",
     "ListOrganizationalUnitsForParentResponseTypeDef",
     "UpdateOrganizationalUnitResponseTypeDef",
     "ListDelegatedAdministratorsResponseTypeDef",
     "ListDelegatedServicesForAccountResponseTypeDef",
     "DescribeEffectivePolicyResponseTypeDef",
     "ListAWSServiceAccessForOrganizationResponseTypeDef",
+    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
     "ListHandshakesForAccountRequestRequestTypeDef",
+    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
     "ListHandshakesForOrganizationRequestRequestTypeDef",
     "HandshakeTypeDef",
     "InviteAccountToOrganizationRequestRequestTypeDef",
-    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
-    "ListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    "ListChildrenRequestListChildrenPaginateTypeDef",
-    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
-    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
-    "ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
-    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
-    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
-    "ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
-    "ListParentsRequestListParentsPaginateTypeDef",
-    "ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListRootsRequestListRootsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
     "ListParentsResponseTypeDef",
     "ListPoliciesForTargetResponseTypeDef",
     "ListPoliciesResponseTypeDef",
     "PolicyTypeDef",
     "ListTargetsForPolicyResponseTypeDef",
     "OrganizationTypeDef",
     "RootTypeDef",
@@ -174,25 +174,14 @@
 AcceptHandshakeRequestRequestTypeDef = TypedDict(
     "AcceptHandshakeRequestRequestTypeDef",
     {
         "HandshakeId": str,
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
 AccountTypeDef = TypedDict(
     "AccountTypeDef",
     {
         "Id": str,
         "Arn": str,
         "Email": str,
         "Name": str,
@@ -413,14 +402,21 @@
     "DisablePolicyTypeRequestRequestTypeDef",
     {
         "RootId": str,
         "PolicyType": PolicyTypeType,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableAWSServiceAccessRequestRequestTypeDef = TypedDict(
     "EnableAWSServiceAccessRequestRequestTypeDef",
     {
         "ServicePrincipal": str,
     },
 )
 
@@ -464,33 +460,51 @@
         "Value": str,
         "Type": HandshakeResourceTypeType,
         "Resources": List[Dict[str, Any]],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef = TypedDict(
+    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAWSServiceAccessForOrganizationRequestRequestTypeDef = TypedDict(
     "ListAWSServiceAccessForOrganizationRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
+    "_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
+    {
+        "ParentId": str,
+    },
+)
+_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
+    "_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAccountsForParentRequestListAccountsForParentPaginateTypeDef(
+    _RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
+    _OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccountsForParentRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountsForParentRequestRequestTypeDef",
     {
         "ParentId": str,
     },
 )
 _OptionalListAccountsForParentRequestRequestTypeDef = TypedDict(
@@ -504,23 +518,52 @@
 
 class ListAccountsForParentRequestRequestTypeDef(
     _RequiredListAccountsForParentRequestRequestTypeDef,
     _OptionalListAccountsForParentRequestRequestTypeDef,
 ):
     pass
 
+ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "ListAccountsRequestListAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAccountsRequestRequestTypeDef = TypedDict(
     "ListAccountsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
+    "_RequiredListChildrenRequestListChildrenPaginateTypeDef",
+    {
+        "ParentId": str,
+        "ChildType": ChildTypeType,
+    },
+)
+_OptionalListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
+    "_OptionalListChildrenRequestListChildrenPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListChildrenRequestListChildrenPaginateTypeDef(
+    _RequiredListChildrenRequestListChildrenPaginateTypeDef,
+    _OptionalListChildrenRequestListChildrenPaginateTypeDef,
+):
+    pass
+
 _RequiredListChildrenRequestRequestTypeDef = TypedDict(
     "_RequiredListChildrenRequestRequestTypeDef",
     {
         "ParentId": str,
         "ChildType": ChildTypeType,
     },
 )
@@ -534,34 +577,72 @@
 )
 
 class ListChildrenRequestRequestTypeDef(
     _RequiredListChildrenRequestRequestTypeDef, _OptionalListChildrenRequestRequestTypeDef
 ):
     pass
 
+ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef = TypedDict(
+    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
+    {
+        "States": Sequence[CreateAccountStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCreateAccountStatusRequestRequestTypeDef = TypedDict(
     "ListCreateAccountStatusRequestRequestTypeDef",
     {
         "States": Sequence[CreateAccountStateType],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef = TypedDict(
+    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
+    {
+        "ServicePrincipal": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDelegatedAdministratorsRequestRequestTypeDef = TypedDict(
     "ListDelegatedAdministratorsRequestRequestTypeDef",
     {
         "ServicePrincipal": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
+    "_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
+    "_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef(
+    _RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
+    _OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
+):
+    pass
+
 _RequiredListDelegatedServicesForAccountRequestRequestTypeDef = TypedDict(
     "_RequiredListDelegatedServicesForAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListDelegatedServicesForAccountRequestRequestTypeDef = TypedDict(
@@ -575,14 +656,34 @@
 
 class ListDelegatedServicesForAccountRequestRequestTypeDef(
     _RequiredListDelegatedServicesForAccountRequestRequestTypeDef,
     _OptionalListDelegatedServicesForAccountRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
+    "_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
+    {
+        "ParentId": str,
+    },
+)
+_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
+    "_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef(
+    _RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
+    _OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
+):
+    pass
+
 _RequiredListOrganizationalUnitsForParentRequestRequestTypeDef = TypedDict(
     "_RequiredListOrganizationalUnitsForParentRequestRequestTypeDef",
     {
         "ParentId": str,
     },
 )
 _OptionalListOrganizationalUnitsForParentRequestRequestTypeDef = TypedDict(
@@ -596,14 +697,34 @@
 
 class ListOrganizationalUnitsForParentRequestRequestTypeDef(
     _RequiredListOrganizationalUnitsForParentRequestRequestTypeDef,
     _OptionalListOrganizationalUnitsForParentRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListParentsRequestListParentsPaginateTypeDef = TypedDict(
+    "_RequiredListParentsRequestListParentsPaginateTypeDef",
+    {
+        "ChildId": str,
+    },
+)
+_OptionalListParentsRequestListParentsPaginateTypeDef = TypedDict(
+    "_OptionalListParentsRequestListParentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListParentsRequestListParentsPaginateTypeDef(
+    _RequiredListParentsRequestListParentsPaginateTypeDef,
+    _OptionalListParentsRequestListParentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListParentsRequestRequestTypeDef = TypedDict(
     "_RequiredListParentsRequestRequestTypeDef",
     {
         "ChildId": str,
     },
 )
 _OptionalListParentsRequestRequestTypeDef = TypedDict(
@@ -625,14 +746,35 @@
     {
         "Id": str,
         "Type": ParentTypeType,
     },
     total=False,
 )
 
+_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
+    "_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
+    {
+        "TargetId": str,
+        "Filter": PolicyTypeType,
+    },
+)
+_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
+    "_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef(
+    _RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
+    _OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
+):
+    pass
+
 _RequiredListPoliciesForTargetRequestRequestTypeDef = TypedDict(
     "_RequiredListPoliciesForTargetRequestRequestTypeDef",
     {
         "TargetId": str,
         "Filter": PolicyTypeType,
     },
 )
@@ -660,14 +802,34 @@
         "Description": str,
         "Type": PolicyTypeType,
         "AwsManaged": bool,
     },
     total=False,
 )
 
+_RequiredListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "Filter": PolicyTypeType,
+    },
+)
+_OptionalListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPoliciesRequestListPoliciesPaginateTypeDef(
+    _RequiredListPoliciesRequestListPoliciesPaginateTypeDef,
+    _OptionalListPoliciesRequestListPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListPoliciesRequestRequestTypeDef",
     {
         "Filter": PolicyTypeType,
     },
 )
 _OptionalListPoliciesRequestRequestTypeDef = TypedDict(
@@ -680,23 +842,51 @@
 )
 
 class ListPoliciesRequestRequestTypeDef(
     _RequiredListPoliciesRequestRequestTypeDef, _OptionalListPoliciesRequestRequestTypeDef
 ):
     pass
 
+ListRootsRequestListRootsPaginateTypeDef = TypedDict(
+    "ListRootsRequestListRootsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRootsRequestRequestTypeDef = TypedDict(
     "ListRootsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceId": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceId": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -709,14 +899,34 @@
 
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "PolicyId": str,
+    },
+)
+_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
+    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+):
+    pass
+
 _RequiredListTargetsForPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsForPolicyRequestRequestTypeDef",
     {
         "PolicyId": str,
     },
 )
 _OptionalListTargetsForPolicyRequestRequestTypeDef = TypedDict(
@@ -759,14 +969,24 @@
     {
         "Type": PolicyTypeType,
         "Status": PolicyTypeStatusType,
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
 RegisterDelegatedAdministratorRequestRequestTypeDef = TypedDict(
     "RegisterDelegatedAdministratorRequestRequestTypeDef",
     {
         "AccountId": str,
         "ServicePrincipal": str,
     },
 )
@@ -783,14 +1003,25 @@
     {
         "Id": str,
         "Arn": str,
     },
     total=False,
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
         "ResourceId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -832,53 +1063,46 @@
 )
 
 class UpdatePolicyRequestRequestTypeDef(
     _RequiredUpdatePolicyRequestRequestTypeDef, _OptionalUpdatePolicyRequestRequestTypeDef
 ):
     pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeAccountResponseTypeDef = TypedDict(
     "DescribeAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountsForParentResponseTypeDef = TypedDict(
     "ListAccountsForParentResponseTypeDef",
     {
         "Accounts": List[AccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountsResponseTypeDef = TypedDict(
     "ListAccountsResponseTypeDef",
     {
         "Accounts": List[AccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChildrenResponseTypeDef = TypedDict(
     "ListChildrenResponseTypeDef",
     {
         "Children": List[ChildTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAccountRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAccountRequestRequestTypeDef",
     {
         "Email": str,
@@ -967,15 +1191,15 @@
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "Content": str,
@@ -1002,121 +1226,139 @@
     },
 )
 
 CreateAccountResponseTypeDef = TypedDict(
     "CreateAccountResponseTypeDef",
     {
         "CreateAccountStatus": CreateAccountStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGovCloudAccountResponseTypeDef = TypedDict(
     "CreateGovCloudAccountResponseTypeDef",
     {
         "CreateAccountStatus": CreateAccountStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCreateAccountStatusResponseTypeDef = TypedDict(
     "DescribeCreateAccountStatusResponseTypeDef",
     {
         "CreateAccountStatus": CreateAccountStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCreateAccountStatusResponseTypeDef = TypedDict(
     "ListCreateAccountStatusResponseTypeDef",
     {
         "CreateAccountStatuses": List[CreateAccountStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOrganizationalUnitResponseTypeDef = TypedDict(
     "CreateOrganizationalUnitResponseTypeDef",
     {
         "OrganizationalUnit": OrganizationalUnitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationalUnitResponseTypeDef = TypedDict(
     "DescribeOrganizationalUnitResponseTypeDef",
     {
         "OrganizationalUnit": OrganizationalUnitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOrganizationalUnitsForParentResponseTypeDef = TypedDict(
     "ListOrganizationalUnitsForParentResponseTypeDef",
     {
         "OrganizationalUnits": List[OrganizationalUnitTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateOrganizationalUnitResponseTypeDef = TypedDict(
     "UpdateOrganizationalUnitResponseTypeDef",
     {
         "OrganizationalUnit": OrganizationalUnitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDelegatedAdministratorsResponseTypeDef = TypedDict(
     "ListDelegatedAdministratorsResponseTypeDef",
     {
         "DelegatedAdministrators": List[DelegatedAdministratorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDelegatedServicesForAccountResponseTypeDef = TypedDict(
     "ListDelegatedServicesForAccountResponseTypeDef",
     {
         "DelegatedServices": List[DelegatedServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEffectivePolicyResponseTypeDef = TypedDict(
     "DescribeEffectivePolicyResponseTypeDef",
     {
         "EffectivePolicy": EffectivePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAWSServiceAccessForOrganizationResponseTypeDef = TypedDict(
     "ListAWSServiceAccessForOrganizationResponseTypeDef",
     {
         "EnabledServicePrincipals": List[EnabledServicePrincipalTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef = TypedDict(
+    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
+    {
+        "Filter": HandshakeFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHandshakesForAccountRequestRequestTypeDef = TypedDict(
     "ListHandshakesForAccountRequestRequestTypeDef",
     {
         "Filter": HandshakeFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef = TypedDict(
+    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
+    {
+        "Filter": HandshakeFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHandshakesForOrganizationRequestRequestTypeDef = TypedDict(
     "ListHandshakesForOrganizationRequestRequestTypeDef",
     {
         "Filter": HandshakeFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -1155,280 +1397,38 @@
 
 class InviteAccountToOrganizationRequestRequestTypeDef(
     _RequiredInviteAccountToOrganizationRequestRequestTypeDef,
     _OptionalInviteAccountToOrganizationRequestRequestTypeDef,
 ):
     pass
 
-ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef = TypedDict(
-    "ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
-    "_RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
-    {
-        "ParentId": str,
-    },
-)
-_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef = TypedDict(
-    "_OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAccountsForParentRequestListAccountsForParentPaginateTypeDef(
-    _RequiredListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-    _OptionalListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-):
-    pass
-
-ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
-    "_RequiredListChildrenRequestListChildrenPaginateTypeDef",
-    {
-        "ParentId": str,
-        "ChildType": ChildTypeType,
-    },
-)
-_OptionalListChildrenRequestListChildrenPaginateTypeDef = TypedDict(
-    "_OptionalListChildrenRequestListChildrenPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListChildrenRequestListChildrenPaginateTypeDef(
-    _RequiredListChildrenRequestListChildrenPaginateTypeDef,
-    _OptionalListChildrenRequestListChildrenPaginateTypeDef,
-):
-    pass
-
-ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef = TypedDict(
-    "ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef",
-    {
-        "States": Sequence[CreateAccountStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef = TypedDict(
-    "ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef",
-    {
-        "ServicePrincipal": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
-    "_RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef = TypedDict(
-    "_OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef(
-    _RequiredListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-    _OptionalListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-):
-    pass
-
-ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef = TypedDict(
-    "ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef",
-    {
-        "Filter": HandshakeFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef = TypedDict(
-    "ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef",
-    {
-        "Filter": HandshakeFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
-    "_RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
-    {
-        "ParentId": str,
-    },
-)
-_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef = TypedDict(
-    "_OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef(
-    _RequiredListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-    _OptionalListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-):
-    pass
-
-_RequiredListParentsRequestListParentsPaginateTypeDef = TypedDict(
-    "_RequiredListParentsRequestListParentsPaginateTypeDef",
-    {
-        "ChildId": str,
-    },
-)
-_OptionalListParentsRequestListParentsPaginateTypeDef = TypedDict(
-    "_OptionalListParentsRequestListParentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListParentsRequestListParentsPaginateTypeDef(
-    _RequiredListParentsRequestListParentsPaginateTypeDef,
-    _OptionalListParentsRequestListParentsPaginateTypeDef,
-):
-    pass
-
-_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
-    "_RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
-    {
-        "TargetId": str,
-        "Filter": PolicyTypeType,
-    },
-)
-_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef = TypedDict(
-    "_OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef(
-    _RequiredListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-    _OptionalListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-):
-    pass
-
-_RequiredListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "Filter": PolicyTypeType,
-    },
-)
-_OptionalListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPoliciesRequestListPoliciesPaginateTypeDef(
-    _RequiredListPoliciesRequestListPoliciesPaginateTypeDef,
-    _OptionalListPoliciesRequestListPoliciesPaginateTypeDef,
-):
-    pass
-
-ListRootsRequestListRootsPaginateTypeDef = TypedDict(
-    "ListRootsRequestListRootsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceId": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "PolicyId": str,
-    },
-)
-_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
-    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-):
-    pass
-
 ListParentsResponseTypeDef = TypedDict(
     "ListParentsResponseTypeDef",
     {
         "Parents": List[ParentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesForTargetResponseTypeDef = TypedDict(
     "ListPoliciesForTargetResponseTypeDef",
     {
         "Policies": List[PolicySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "Policies": List[PolicySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyTypeDef = TypedDict(
     "PolicyTypeDef",
     {
         "PolicySummary": PolicySummaryTypeDef,
@@ -1438,15 +1438,15 @@
 )
 
 ListTargetsForPolicyResponseTypeDef = TypedDict(
     "ListTargetsForPolicyResponseTypeDef",
     {
         "Targets": List[PolicyTargetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrganizationTypeDef = TypedDict(
     "OrganizationTypeDef",
     {
         "Id": str,
@@ -1480,149 +1480,149 @@
     total=False,
 )
 
 AcceptHandshakeResponseTypeDef = TypedDict(
     "AcceptHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelHandshakeResponseTypeDef = TypedDict(
     "CancelHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineHandshakeResponseTypeDef = TypedDict(
     "DeclineHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHandshakeResponseTypeDef = TypedDict(
     "DescribeHandshakeResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableAllFeaturesResponseTypeDef = TypedDict(
     "EnableAllFeaturesResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteAccountToOrganizationResponseTypeDef = TypedDict(
     "InviteAccountToOrganizationResponseTypeDef",
     {
         "Handshake": HandshakeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHandshakesForAccountResponseTypeDef = TypedDict(
     "ListHandshakesForAccountResponseTypeDef",
     {
         "Handshakes": List[HandshakeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHandshakesForOrganizationResponseTypeDef = TypedDict(
     "ListHandshakesForOrganizationResponseTypeDef",
     {
         "Handshakes": List[HandshakeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePolicyResponseTypeDef = TypedDict(
     "CreatePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePolicyResponseTypeDef = TypedDict(
     "DescribePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePolicyResponseTypeDef = TypedDict(
     "UpdatePolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOrganizationResponseTypeDef = TypedDict(
     "CreateOrganizationResponseTypeDef",
     {
         "Organization": OrganizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationResponseTypeDef = TypedDict(
     "DescribeOrganizationResponseTypeDef",
     {
         "Organization": OrganizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisablePolicyTypeResponseTypeDef = TypedDict(
     "DisablePolicyTypeResponseTypeDef",
     {
         "Root": RootTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnablePolicyTypeResponseTypeDef = TypedDict(
     "EnablePolicyTypeResponseTypeDef",
     {
         "Root": RootTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRootsResponseTypeDef = TypedDict(
     "ListRootsResponseTypeDef",
     {
         "Roots": List[RootTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeResourcePolicyResponseTypeDef = TypedDict(
     "DescribeResourcePolicyResponseTypeDef",
     {
         "ResourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourcePolicyResponseTypeDef = TypedDict(
     "PutResourcePolicyResponseTypeDef",
     {
         "ResourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/PKG-INFO` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-organizations
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Organizations 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Organizations 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-organizations"></a>
 
 # types-aiobotocore-organizations
 
 [![PyPI - types-aiobotocore-organizations](https://img.shields.io/pypi/v/types-aiobotocore-organizations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-organizations)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-organizations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-organizations)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-organizations?color=blue)](https://pypistats.org/packages/types-aiobotocore-organizations)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Organizations 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
+[aiobotocore.Organizations 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/organizations.html#Organizations)
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
 [types-aiobotocore-organizations docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/).
 
 See how it helps to find and fix potential bugs:
 
@@ -399,15 +399,14 @@
 
 `types_aiobotocore_organizations.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_organizations.type_defs import (
     AcceptHandshakeRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AccountTypeDef,
     AttachPolicyRequestRequestTypeDef,
     CancelHandshakeRequestRequestTypeDef,
     ChildTypeDef,
     CloseAccountRequestRequestTypeDef,
     TagTypeDef,
     CreateAccountStatusTypeDef,
@@ -425,47 +424,62 @@
     EffectivePolicyTypeDef,
     DescribeHandshakeRequestRequestTypeDef,
     DescribeOrganizationalUnitRequestRequestTypeDef,
     DescribePolicyRequestRequestTypeDef,
     DetachPolicyRequestRequestTypeDef,
     DisableAWSServiceAccessRequestRequestTypeDef,
     DisablePolicyTypeRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableAWSServiceAccessRequestRequestTypeDef,
     EnablePolicyTypeRequestRequestTypeDef,
     EnabledServicePrincipalTypeDef,
     HandshakeFilterTypeDef,
     HandshakePartyTypeDef,
     HandshakeResourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef,
     ListAWSServiceAccessForOrganizationRequestRequestTypeDef,
+    ListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
     ListAccountsForParentRequestRequestTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
+    ListChildrenRequestListChildrenPaginateTypeDef,
     ListChildrenRequestRequestTypeDef,
+    ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef,
     ListCreateAccountStatusRequestRequestTypeDef,
+    ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef,
     ListDelegatedAdministratorsRequestRequestTypeDef,
+    ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
     ListDelegatedServicesForAccountRequestRequestTypeDef,
+    ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
     ListOrganizationalUnitsForParentRequestRequestTypeDef,
+    ListParentsRequestListParentsPaginateTypeDef,
     ListParentsRequestRequestTypeDef,
     ParentTypeDef,
+    ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
     ListPoliciesForTargetRequestRequestTypeDef,
     PolicySummaryTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListRootsRequestListRootsPaginateTypeDef,
     ListRootsRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListTargetsForPolicyRequestRequestTypeDef,
     PolicyTargetSummaryTypeDef,
     MoveAccountRequestRequestTypeDef,
     PolicyTypeSummaryTypeDef,
+    PaginatorConfigTypeDef,
     RegisterDelegatedAdministratorRequestRequestTypeDef,
     RemoveAccountFromOrganizationRequestRequestTypeDef,
     ResourcePolicySummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateOrganizationalUnitRequestRequestTypeDef,
     UpdatePolicyRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     DescribeAccountResponseTypeDef,
     ListAccountsForParentResponseTypeDef,
     ListAccountsResponseTypeDef,
     ListChildrenResponseTypeDef,
     CreateAccountRequestRequestTypeDef,
     CreateGovCloudAccountRequestRequestTypeDef,
     CreateOrganizationalUnitRequestRequestTypeDef,
@@ -481,34 +495,20 @@
     DescribeOrganizationalUnitResponseTypeDef,
     ListOrganizationalUnitsForParentResponseTypeDef,
     UpdateOrganizationalUnitResponseTypeDef,
     ListDelegatedAdministratorsResponseTypeDef,
     ListDelegatedServicesForAccountResponseTypeDef,
     DescribeEffectivePolicyResponseTypeDef,
     ListAWSServiceAccessForOrganizationResponseTypeDef,
+    ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef,
     ListHandshakesForAccountRequestRequestTypeDef,
+    ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef,
     ListHandshakesForOrganizationRequestRequestTypeDef,
     HandshakeTypeDef,
     InviteAccountToOrganizationRequestRequestTypeDef,
-    ListAWSServiceAccessForOrganizationRequestListAWSServiceAccessForOrganizationPaginateTypeDef,
-    ListAccountsForParentRequestListAccountsForParentPaginateTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
-    ListChildrenRequestListChildrenPaginateTypeDef,
-    ListCreateAccountStatusRequestListCreateAccountStatusPaginateTypeDef,
-    ListDelegatedAdministratorsRequestListDelegatedAdministratorsPaginateTypeDef,
-    ListDelegatedServicesForAccountRequestListDelegatedServicesForAccountPaginateTypeDef,
-    ListHandshakesForAccountRequestListHandshakesForAccountPaginateTypeDef,
-    ListHandshakesForOrganizationRequestListHandshakesForOrganizationPaginateTypeDef,
-    ListOrganizationalUnitsForParentRequestListOrganizationalUnitsForParentPaginateTypeDef,
-    ListParentsRequestListParentsPaginateTypeDef,
-    ListPoliciesForTargetRequestListPoliciesForTargetPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListRootsRequestListRootsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListParentsResponseTypeDef,
     ListPoliciesForTargetResponseTypeDef,
     ListPoliciesResponseTypeDef,
     PolicyTypeDef,
     ListTargetsForPolicyResponseTypeDef,
     OrganizationTypeDef,
     RootTypeDef,
@@ -541,43 +541,43 @@
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

### Comparing `types-aiobotocore-organizations-2.5.0.post1/types_aiobotocore_organizations.egg-info/SOURCES.txt` & `types-aiobotocore-organizations-2.5.1/types_aiobotocore_organizations.egg-info/SOURCES.txt`

 * *Files identical despite different names*

