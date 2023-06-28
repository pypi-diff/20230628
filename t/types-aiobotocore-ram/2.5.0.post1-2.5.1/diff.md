# Comparing `tmp/types-aiobotocore-ram-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ram-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ram-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-ram-2.5.1.tar", last modified: Wed Jun 28 01:44:01 2023, max compression
```

## Comparing `types-aiobotocore-ram-2.5.0.post1.tar` & `types-aiobotocore-ram-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.531531 types-aiobotocore-ram-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16912 2023-03-11 12:27:10.531531 types-aiobotocore-ram-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15357 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:10.531531 types-aiobotocore-ram-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:21:50.000000 types-aiobotocore-ram-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.519531 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/
--rw-r--r--   0 runner    (1001) docker     (123)     1805 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1804 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25919 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    25879 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9849 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9847 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9107 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9098 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    30623 2023-03-11 12:21:52.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    30576 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:21:51.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.531531 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16912 2023-03-11 12:27:10.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:10.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:10.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:10.000000 types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.234196 types-aiobotocore-ram-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18032 2023-06-28 01:44:01.234196 types-aiobotocore-ram-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16483 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:01.234196 types-aiobotocore-ram-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.234196 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/
+-rw-r--r--   0 runner    (1001) docker     (123)     1805 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1804 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33623 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33574 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10639 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10637 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9037 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9029 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    41091 2023-06-28 01:38:39.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41026 2023-06-28 01:38:39.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:38:38.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.234196 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18032 2023-06-28 01:44:01.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:01.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:01.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:01.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:01.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:01.000000 types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/LICENSE` & `types-aiobotocore-ram-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ram-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ram-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ram
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RAM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RAM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ram"></a>
 
 # types-aiobotocore-ram
 
 [![PyPI - types-aiobotocore-ram](https://img.shields.io/pypi/v/types-aiobotocore-ram.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ram)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ram.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ram)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ram?color=blue)](https://pypistats.org/packages/types-aiobotocore-ram)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RAM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
+[aiobotocore.RAM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
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
 [types-aiobotocore-ram docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/).
 
 See how it helps to find and fix potential bugs:
 
@@ -316,14 +316,19 @@
 from types_aiobotocore_ram.literals import (
     GetResourcePoliciesPaginatorName,
     GetResourceShareAssociationsPaginatorName,
     GetResourceShareInvitationsPaginatorName,
     GetResourceSharesPaginatorName,
     ListPrincipalsPaginatorName,
     ListResourcesPaginatorName,
+    PermissionFeatureSetType,
+    PermissionStatusType,
+    PermissionTypeFilterType,
+    PermissionTypeType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceRegionScopeType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareFeatureSetType,
     ResourceShareInvitationStatusType,
@@ -347,75 +352,95 @@
 
 `types_aiobotocore_ram.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ram.type_defs import (
     AcceptResourceShareInvitationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AssociateResourceSharePermissionRequestRequestTypeDef,
+    AssociateResourceSharePermissionResponseTypeDef,
     AssociateResourceShareRequestRequestTypeDef,
     ResourceShareAssociationTypeDef,
+    AssociatedPermissionTypeDef,
     TagTypeDef,
+    CreatePermissionVersionRequestRequestTypeDef,
+    DeletePermissionRequestRequestTypeDef,
+    DeletePermissionResponseTypeDef,
+    DeletePermissionVersionRequestRequestTypeDef,
+    DeletePermissionVersionResponseTypeDef,
     DeleteResourceShareRequestRequestTypeDef,
+    DeleteResourceShareResponseTypeDef,
     DisassociateResourceSharePermissionRequestRequestTypeDef,
+    DisassociateResourceSharePermissionResponseTypeDef,
     DisassociateResourceShareRequestRequestTypeDef,
+    EnableSharingWithAwsOrganizationResponseTypeDef,
     GetPermissionRequestRequestTypeDef,
-    ResourceSharePermissionDetailTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
+    GetResourcePoliciesResponseTypeDef,
+    GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
     GetResourceShareAssociationsRequestRequestTypeDef,
+    GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef,
     GetResourceShareInvitationsRequestRequestTypeDef,
     TagFilterTypeDef,
     ListPendingInvitationResourcesRequestRequestTypeDef,
     ResourceTypeDef,
+    ListPermissionAssociationsRequestRequestTypeDef,
     ListPermissionVersionsRequestRequestTypeDef,
-    ResourceSharePermissionSummaryTypeDef,
     ListPermissionsRequestRequestTypeDef,
+    ListPrincipalsRequestListPrincipalsPaginateTypeDef,
     ListPrincipalsRequestRequestTypeDef,
     PrincipalTypeDef,
+    ListReplacePermissionAssociationsWorkRequestRequestTypeDef,
+    ReplacePermissionAssociationsWorkTypeDef,
     ListResourceSharePermissionsRequestRequestTypeDef,
     ListResourceTypesRequestRequestTypeDef,
     ServiceNameAndResourceTypeTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PromotePermissionCreatedFromPolicyRequestRequestTypeDef,
     PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef,
+    PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     RejectResourceShareInvitationRequestRequestTypeDef,
+    ReplacePermissionAssociationsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SetDefaultPermissionVersionRequestRequestTypeDef,
+    SetDefaultPermissionVersionResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateResourceShareRequestRequestTypeDef,
-    AssociateResourceSharePermissionResponseTypeDef,
-    DeleteResourceShareResponseTypeDef,
-    DisassociateResourceSharePermissionResponseTypeDef,
-    EnableSharingWithAwsOrganizationResponseTypeDef,
-    GetResourcePoliciesResponseTypeDef,
-    PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     AssociateResourceShareResponseTypeDef,
     DisassociateResourceShareResponseTypeDef,
     GetResourceShareAssociationsResponseTypeDef,
     ResourceShareInvitationTypeDef,
+    ListPermissionAssociationsResponseTypeDef,
+    CreatePermissionRequestRequestTypeDef,
     CreateResourceShareRequestRequestTypeDef,
+    ResourceSharePermissionDetailTypeDef,
+    ResourceSharePermissionSummaryTypeDef,
     ResourceShareTypeDef,
     TagResourceRequestRequestTypeDef,
-    GetPermissionResponseTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-    GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef,
-    ListPrincipalsRequestListPrincipalsPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
     GetResourceSharesRequestGetResourceSharesPaginateTypeDef,
     GetResourceSharesRequestRequestTypeDef,
     ListPendingInvitationResourcesResponseTypeDef,
     ListResourcesResponseTypeDef,
-    ListPermissionVersionsResponseTypeDef,
-    ListPermissionsResponseTypeDef,
-    ListResourceSharePermissionsResponseTypeDef,
     ListPrincipalsResponseTypeDef,
+    ListReplacePermissionAssociationsWorkResponseTypeDef,
+    ReplacePermissionAssociationsResponseTypeDef,
     ListResourceTypesResponseTypeDef,
     AcceptResourceShareInvitationResponseTypeDef,
     GetResourceShareInvitationsResponseTypeDef,
     RejectResourceShareInvitationResponseTypeDef,
+    CreatePermissionVersionResponseTypeDef,
+    GetPermissionResponseTypeDef,
+    CreatePermissionResponseTypeDef,
+    ListPermissionVersionsResponseTypeDef,
+    ListPermissionsResponseTypeDef,
+    ListResourceSharePermissionsResponseTypeDef,
+    PromotePermissionCreatedFromPolicyResponseTypeDef,
     CreateResourceShareResponseTypeDef,
     GetResourceSharesResponseTypeDef,
     UpdateResourceShareResponseTypeDef,
 )
 
 
 def get_structure() -> AcceptResourceShareInvitationRequestRequestTypeDef:
@@ -425,43 +450,43 @@
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/README.md` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-ram
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RAM 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore ram type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-ram"></a>
 
 # types-aiobotocore-ram
 
 [![PyPI - types-aiobotocore-ram](https://img.shields.io/pypi/v/types-aiobotocore-ram.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ram)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ram.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ram)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ram?color=blue)](https://pypistats.org/packages/types-aiobotocore-ram)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RAM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
+[aiobotocore.RAM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
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
 [types-aiobotocore-ram docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/).
 
 See how it helps to find and fix potential bugs:
 
@@ -283,14 +316,19 @@
 from types_aiobotocore_ram.literals import (
     GetResourcePoliciesPaginatorName,
     GetResourceShareAssociationsPaginatorName,
     GetResourceShareInvitationsPaginatorName,
     GetResourceSharesPaginatorName,
     ListPrincipalsPaginatorName,
     ListResourcesPaginatorName,
+    PermissionFeatureSetType,
+    PermissionStatusType,
+    PermissionTypeFilterType,
+    PermissionTypeType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceRegionScopeType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareFeatureSetType,
     ResourceShareInvitationStatusType,
@@ -314,75 +352,95 @@
 
 `types_aiobotocore_ram.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ram.type_defs import (
     AcceptResourceShareInvitationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AssociateResourceSharePermissionRequestRequestTypeDef,
+    AssociateResourceSharePermissionResponseTypeDef,
     AssociateResourceShareRequestRequestTypeDef,
     ResourceShareAssociationTypeDef,
+    AssociatedPermissionTypeDef,
     TagTypeDef,
+    CreatePermissionVersionRequestRequestTypeDef,
+    DeletePermissionRequestRequestTypeDef,
+    DeletePermissionResponseTypeDef,
+    DeletePermissionVersionRequestRequestTypeDef,
+    DeletePermissionVersionResponseTypeDef,
     DeleteResourceShareRequestRequestTypeDef,
+    DeleteResourceShareResponseTypeDef,
     DisassociateResourceSharePermissionRequestRequestTypeDef,
+    DisassociateResourceSharePermissionResponseTypeDef,
     DisassociateResourceShareRequestRequestTypeDef,
+    EnableSharingWithAwsOrganizationResponseTypeDef,
     GetPermissionRequestRequestTypeDef,
-    ResourceSharePermissionDetailTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
+    GetResourcePoliciesResponseTypeDef,
+    GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
     GetResourceShareAssociationsRequestRequestTypeDef,
+    GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef,
     GetResourceShareInvitationsRequestRequestTypeDef,
     TagFilterTypeDef,
     ListPendingInvitationResourcesRequestRequestTypeDef,
     ResourceTypeDef,
+    ListPermissionAssociationsRequestRequestTypeDef,
     ListPermissionVersionsRequestRequestTypeDef,
-    ResourceSharePermissionSummaryTypeDef,
     ListPermissionsRequestRequestTypeDef,
+    ListPrincipalsRequestListPrincipalsPaginateTypeDef,
     ListPrincipalsRequestRequestTypeDef,
     PrincipalTypeDef,
+    ListReplacePermissionAssociationsWorkRequestRequestTypeDef,
+    ReplacePermissionAssociationsWorkTypeDef,
     ListResourceSharePermissionsRequestRequestTypeDef,
     ListResourceTypesRequestRequestTypeDef,
     ServiceNameAndResourceTypeTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PromotePermissionCreatedFromPolicyRequestRequestTypeDef,
     PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef,
+    PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     RejectResourceShareInvitationRequestRequestTypeDef,
+    ReplacePermissionAssociationsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SetDefaultPermissionVersionRequestRequestTypeDef,
+    SetDefaultPermissionVersionResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateResourceShareRequestRequestTypeDef,
-    AssociateResourceSharePermissionResponseTypeDef,
-    DeleteResourceShareResponseTypeDef,
-    DisassociateResourceSharePermissionResponseTypeDef,
-    EnableSharingWithAwsOrganizationResponseTypeDef,
-    GetResourcePoliciesResponseTypeDef,
-    PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     AssociateResourceShareResponseTypeDef,
     DisassociateResourceShareResponseTypeDef,
     GetResourceShareAssociationsResponseTypeDef,
     ResourceShareInvitationTypeDef,
+    ListPermissionAssociationsResponseTypeDef,
+    CreatePermissionRequestRequestTypeDef,
     CreateResourceShareRequestRequestTypeDef,
+    ResourceSharePermissionDetailTypeDef,
+    ResourceSharePermissionSummaryTypeDef,
     ResourceShareTypeDef,
     TagResourceRequestRequestTypeDef,
-    GetPermissionResponseTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-    GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef,
-    ListPrincipalsRequestListPrincipalsPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
     GetResourceSharesRequestGetResourceSharesPaginateTypeDef,
     GetResourceSharesRequestRequestTypeDef,
     ListPendingInvitationResourcesResponseTypeDef,
     ListResourcesResponseTypeDef,
-    ListPermissionVersionsResponseTypeDef,
-    ListPermissionsResponseTypeDef,
-    ListResourceSharePermissionsResponseTypeDef,
     ListPrincipalsResponseTypeDef,
+    ListReplacePermissionAssociationsWorkResponseTypeDef,
+    ReplacePermissionAssociationsResponseTypeDef,
     ListResourceTypesResponseTypeDef,
     AcceptResourceShareInvitationResponseTypeDef,
     GetResourceShareInvitationsResponseTypeDef,
     RejectResourceShareInvitationResponseTypeDef,
+    CreatePermissionVersionResponseTypeDef,
+    GetPermissionResponseTypeDef,
+    CreatePermissionResponseTypeDef,
+    ListPermissionVersionsResponseTypeDef,
+    ListPermissionsResponseTypeDef,
+    ListResourceSharePermissionsResponseTypeDef,
+    PromotePermissionCreatedFromPolicyResponseTypeDef,
     CreateResourceShareResponseTypeDef,
     GetResourceSharesResponseTypeDef,
     UpdateResourceShareResponseTypeDef,
 )
 
 
 def get_structure() -> AcceptResourceShareInvitationRequestRequestTypeDef:
@@ -392,43 +450,43 @@
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/setup.py` & `types-aiobotocore-ram-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ram.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ram",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ram"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RAM 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.RAM 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/",
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/__init__.py` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/__init__.pyi` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/__main__.py` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RAM 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RAM 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM\nOther"
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/client.py` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/client.py`

 * *Files 11% similar despite different names*

```diff
@@ -17,14 +17,17 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    PermissionFeatureSetType,
+    PermissionTypeFilterType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareStatusType,
 )
 from .paginator import (
@@ -35,33 +38,42 @@
     ListPrincipalsPaginator,
     ListResourcesPaginator,
 )
 from .type_defs import (
     AcceptResourceShareInvitationResponseTypeDef,
     AssociateResourceSharePermissionResponseTypeDef,
     AssociateResourceShareResponseTypeDef,
+    CreatePermissionResponseTypeDef,
+    CreatePermissionVersionResponseTypeDef,
     CreateResourceShareResponseTypeDef,
+    DeletePermissionResponseTypeDef,
+    DeletePermissionVersionResponseTypeDef,
     DeleteResourceShareResponseTypeDef,
     DisassociateResourceSharePermissionResponseTypeDef,
     DisassociateResourceShareResponseTypeDef,
     EnableSharingWithAwsOrganizationResponseTypeDef,
     GetPermissionResponseTypeDef,
     GetResourcePoliciesResponseTypeDef,
     GetResourceShareAssociationsResponseTypeDef,
     GetResourceShareInvitationsResponseTypeDef,
     GetResourceSharesResponseTypeDef,
     ListPendingInvitationResourcesResponseTypeDef,
+    ListPermissionAssociationsResponseTypeDef,
     ListPermissionsResponseTypeDef,
     ListPermissionVersionsResponseTypeDef,
     ListPrincipalsResponseTypeDef,
+    ListReplacePermissionAssociationsWorkResponseTypeDef,
     ListResourceSharePermissionsResponseTypeDef,
     ListResourcesResponseTypeDef,
     ListResourceTypesResponseTypeDef,
+    PromotePermissionCreatedFromPolicyResponseTypeDef,
     PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     RejectResourceShareInvitationResponseTypeDef,
+    ReplacePermissionAssociationsResponseTypeDef,
+    SetDefaultPermissionVersionResponseTypeDef,
     TagFilterTypeDef,
     TagTypeDef,
     UpdateResourceShareResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -83,31 +95,37 @@
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     InvalidClientTokenException: Type[BotocoreClientError]
     InvalidMaxResultsException: Type[BotocoreClientError]
     InvalidNextTokenException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
+    InvalidPolicyException: Type[BotocoreClientError]
     InvalidResourceTypeException: Type[BotocoreClientError]
     InvalidStateTransitionException: Type[BotocoreClientError]
     MalformedArnException: Type[BotocoreClientError]
+    MalformedPolicyTemplateException: Type[BotocoreClientError]
     MissingRequiredParameterException: Type[BotocoreClientError]
     OperationNotPermittedException: Type[BotocoreClientError]
+    PermissionAlreadyExistsException: Type[BotocoreClientError]
+    PermissionLimitExceededException: Type[BotocoreClientError]
+    PermissionVersionsLimitExceededException: Type[BotocoreClientError]
     ResourceArnNotFoundException: Type[BotocoreClientError]
     ResourceShareInvitationAlreadyAcceptedException: Type[BotocoreClientError]
     ResourceShareInvitationAlreadyRejectedException: Type[BotocoreClientError]
     ResourceShareInvitationArnNotFoundException: Type[BotocoreClientError]
     ResourceShareInvitationExpiredException: Type[BotocoreClientError]
     ResourceShareLimitExceededException: Type[BotocoreClientError]
     ServerInternalException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     TagLimitExceededException: Type[BotocoreClientError]
     TagPolicyViolationException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     UnknownResourceException: Type[BotocoreClientError]
+    UnmatchedPolicyPermissionException: Type[BotocoreClientError]
 
 
 class RAMClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/)
     """
@@ -178,14 +196,41 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#close)
         """
 
+    async def create_permission(
+        self,
+        *,
+        name: str,
+        resourceType: str,
+        policyTemplate: str,
+        clientToken: str = ...,
+        tags: Sequence[TagTypeDef] = ...
+    ) -> CreatePermissionResponseTypeDef:
+        """
+        Creates a customer managed permission for a specified resource type that you can
+        attach to resource shares.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_permission)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#create_permission)
+        """
+
+    async def create_permission_version(
+        self, *, permissionArn: str, policyTemplate: str, clientToken: str = ...
+    ) -> CreatePermissionVersionResponseTypeDef:
+        """
+        Creates a new version of the specified customer managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_permission_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#create_permission_version)
+        """
+
     async def create_resource_share(
         self,
         *,
         name: str,
         resourceArns: Sequence[str] = ...,
         principals: Sequence[str] = ...,
         tags: Sequence[TagTypeDef] = ...,
@@ -196,14 +241,35 @@
         """
         Creates a resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_resource_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#create_resource_share)
         """
 
+    async def delete_permission(
+        self, *, permissionArn: str, clientToken: str = ...
+    ) -> DeletePermissionResponseTypeDef:
+        """
+        Deletes the specified customer managed permission in the Amazon Web Services
+        Region in which you call this operation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_permission)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#delete_permission)
+        """
+
+    async def delete_permission_version(
+        self, *, permissionArn: str, permissionVersion: int, clientToken: str = ...
+    ) -> DeletePermissionVersionResponseTypeDef:
+        """
+        Deletes one version of a customer managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_permission_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#delete_permission_version)
+        """
+
     async def delete_resource_share(
         self, *, resourceShareArn: str, clientToken: str = ...
     ) -> DeleteResourceShareResponseTypeDef:
         """
         Deletes the specified resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_resource_share)
@@ -215,26 +281,26 @@
         *,
         resourceShareArn: str,
         resourceArns: Sequence[str] = ...,
         principals: Sequence[str] = ...,
         clientToken: str = ...
     ) -> DisassociateResourceShareResponseTypeDef:
         """
-        Disassociates the specified principals or resources from the specified resource
-        share.
+        Removes the specified principals or resources from participating in the
+        specified resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.disassociate_resource_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#disassociate_resource_share)
         """
 
     async def disassociate_resource_share_permission(
         self, *, resourceShareArn: str, permissionArn: str, clientToken: str = ...
     ) -> DisassociateResourceSharePermissionResponseTypeDef:
         """
-        Disassociates an RAM permission from a resource share.
+        Removes a managed permission from a resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.disassociate_resource_share_permission)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#disassociate_resource_share_permission)
         """
 
     async def enable_sharing_with_aws_organization(
         self,
@@ -260,15 +326,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#generate_presigned_url)
         """
 
     async def get_permission(
         self, *, permissionArn: str, permissionVersion: int = ...
     ) -> GetPermissionResponseTypeDef:
         """
-        Gets the contents of an RAM permission in JSON format.
+        Retrieves the contents of a managed permission in JSON format.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_permission)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#get_permission)
         """
 
     async def get_resource_policies(
         self,
@@ -294,16 +360,16 @@
         resourceArn: str = ...,
         principal: str = ...,
         associationStatus: ResourceShareAssociationStatusType = ...,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetResourceShareAssociationsResponseTypeDef:
         """
-        Retrieves the resource and principal associations for resource shares that you
-        own.
+        Retrieves the lists of resources and principals that associated for resource
+        shares that you own.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_share_associations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#get_resource_share_associations)
         """
 
     async def get_resource_share_invitations(
         self,
@@ -326,15 +392,16 @@
         resourceOwner: ResourceOwnerType,
         resourceShareArns: Sequence[str] = ...,
         resourceShareStatus: ResourceShareStatusType = ...,
         name: str = ...,
         tagFilters: Sequence[TagFilterTypeDef] = ...,
         nextToken: str = ...,
         maxResults: int = ...,
-        permissionArn: str = ...
+        permissionArn: str = ...,
+        permissionVersion: int = ...
     ) -> GetResourceSharesResponseTypeDef:
         """
         Retrieves details about the resource shares that you own or that are shared with
         you.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_shares)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#get_resource_shares)
@@ -352,26 +419,51 @@
         Lists the resources in a resource share that is shared with you but for which
         the invitation is still `PENDING`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_pending_invitation_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_pending_invitation_resources)
         """
 
+    async def list_permission_associations(
+        self,
+        *,
+        permissionArn: str = ...,
+        permissionVersion: int = ...,
+        associationStatus: ResourceShareAssociationStatusType = ...,
+        resourceType: str = ...,
+        featureSet: PermissionFeatureSetType = ...,
+        defaultVersion: bool = ...,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListPermissionAssociationsResponseTypeDef:
+        """
+        Lists information about the managed permission and its associations to any
+        resource shares that use this managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permission_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_permission_associations)
+        """
+
     async def list_permission_versions(
         self, *, permissionArn: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListPermissionVersionsResponseTypeDef:
         """
         Lists the available versions of the specified RAM permission.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permission_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_permission_versions)
         """
 
     async def list_permissions(
-        self, *, resourceType: str = ..., nextToken: str = ..., maxResults: int = ...
+        self,
+        *,
+        resourceType: str = ...,
+        nextToken: str = ...,
+        maxResults: int = ...,
+        permissionType: PermissionTypeFilterType = ...
     ) -> ListPermissionsResponseTypeDef:
         """
         Retrieves a list of available RAM permissions that you can use for the supported
         resource types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permissions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_permissions)
@@ -392,14 +484,30 @@
         Lists the principals that you are sharing resources with or that are sharing
         resources with you.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_principals)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_principals)
         """
 
+    async def list_replace_permission_associations_work(
+        self,
+        *,
+        workIds: Sequence[str] = ...,
+        status: ReplacePermissionAssociationsWorkStatusType = ...,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListReplacePermissionAssociationsWorkResponseTypeDef:
+        """
+        Retrieves the current status of the asynchronous tasks performed by RAM when you
+        perform the  ReplacePermissionAssociationsWork operation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_replace_permission_associations_work)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_replace_permission_associations_work)
+        """
+
     async def list_resource_share_permissions(
         self, *, resourceShareArn: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListResourceSharePermissionsResponseTypeDef:
         """
         Lists the RAM permissions that are associated with a resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resource_share_permissions)
@@ -436,20 +544,35 @@
         Lists the resources that you added to a resource share or the resources that are
         shared with you.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_resources)
         """
 
+    async def promote_permission_created_from_policy(
+        self, *, permissionArn: str, name: str, clientToken: str = ...
+    ) -> PromotePermissionCreatedFromPolicyResponseTypeDef:
+        """
+        When you attach a resource-based policy to a resource, RAM automatically creates
+        a resource share of `featureSet`= `CREATED_FROM_POLICY` with a managed
+        permission that has the same IAM permissions as the original resource-based
+        policy.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.promote_permission_created_from_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#promote_permission_created_from_policy)
+        """
+
     async def promote_resource_share_created_from_policy(
         self, *, resourceShareArn: str
     ) -> PromoteResourceShareCreatedFromPolicyResponseTypeDef:
         """
-        When you attach a resource-based permission policy to a resource, it
-        automatically creates a resource share.
+        When you attach a resource-based policy to a resource, RAM automatically creates
+        a resource share of `featureSet`= `CREATED_FROM_POLICY` with a managed
+        permission that has the same IAM permissions as the original resource-based
+        policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.promote_resource_share_created_from_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#promote_resource_share_created_from_policy)
         """
 
     async def reject_resource_share_invitation(
         self, *, resourceShareInvitationArn: str, clientToken: str = ...
@@ -458,29 +581,58 @@
         Rejects an invitation to a resource share from another Amazon Web Services
         account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.reject_resource_share_invitation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#reject_resource_share_invitation)
         """
 
+    async def replace_permission_associations(
+        self,
+        *,
+        fromPermissionArn: str,
+        toPermissionArn: str,
+        fromPermissionVersion: int = ...,
+        clientToken: str = ...
+    ) -> ReplacePermissionAssociationsResponseTypeDef:
+        """
+        Updates all resource shares that use a managed permission to a different managed
+        permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.replace_permission_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#replace_permission_associations)
+        """
+
+    async def set_default_permission_version(
+        self, *, permissionArn: str, permissionVersion: int, clientToken: str = ...
+    ) -> SetDefaultPermissionVersionResponseTypeDef:
+        """
+        Designates the specified version number as the default version for the specified
+        customer managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.set_default_permission_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#set_default_permission_version)
+        """
+
     async def tag_resource(
-        self, *, resourceShareArn: str, tags: Sequence[TagTypeDef]
+        self, *, tags: Sequence[TagTypeDef], resourceShareArn: str = ..., resourceArn: str = ...
     ) -> Dict[str, Any]:
         """
-        Adds the specified tag keys and values to the specified resource share.
+        Adds the specified tag keys and values to a resource share or managed
+        permission.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#tag_resource)
         """
 
     async def untag_resource(
-        self, *, resourceShareArn: str, tagKeys: Sequence[str]
+        self, *, tagKeys: Sequence[str], resourceShareArn: str = ..., resourceArn: str = ...
     ) -> Dict[str, Any]:
         """
-        Removes the specified tag key and value pairs from the specified resource share.
+        Removes the specified tag key and value pairs from the specified resource share
+        or managed permission.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#untag_resource)
         """
 
     async def update_resource_share(
         self,
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/client.pyi` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/client.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -17,14 +17,17 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    PermissionFeatureSetType,
+    PermissionTypeFilterType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareStatusType,
 )
 from .paginator import (
@@ -35,33 +38,42 @@
     ListPrincipalsPaginator,
     ListResourcesPaginator,
 )
 from .type_defs import (
     AcceptResourceShareInvitationResponseTypeDef,
     AssociateResourceSharePermissionResponseTypeDef,
     AssociateResourceShareResponseTypeDef,
+    CreatePermissionResponseTypeDef,
+    CreatePermissionVersionResponseTypeDef,
     CreateResourceShareResponseTypeDef,
+    DeletePermissionResponseTypeDef,
+    DeletePermissionVersionResponseTypeDef,
     DeleteResourceShareResponseTypeDef,
     DisassociateResourceSharePermissionResponseTypeDef,
     DisassociateResourceShareResponseTypeDef,
     EnableSharingWithAwsOrganizationResponseTypeDef,
     GetPermissionResponseTypeDef,
     GetResourcePoliciesResponseTypeDef,
     GetResourceShareAssociationsResponseTypeDef,
     GetResourceShareInvitationsResponseTypeDef,
     GetResourceSharesResponseTypeDef,
     ListPendingInvitationResourcesResponseTypeDef,
+    ListPermissionAssociationsResponseTypeDef,
     ListPermissionsResponseTypeDef,
     ListPermissionVersionsResponseTypeDef,
     ListPrincipalsResponseTypeDef,
+    ListReplacePermissionAssociationsWorkResponseTypeDef,
     ListResourceSharePermissionsResponseTypeDef,
     ListResourcesResponseTypeDef,
     ListResourceTypesResponseTypeDef,
+    PromotePermissionCreatedFromPolicyResponseTypeDef,
     PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     RejectResourceShareInvitationResponseTypeDef,
+    ReplacePermissionAssociationsResponseTypeDef,
+    SetDefaultPermissionVersionResponseTypeDef,
     TagFilterTypeDef,
     TagTypeDef,
     UpdateResourceShareResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -80,31 +92,37 @@
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     InvalidClientTokenException: Type[BotocoreClientError]
     InvalidMaxResultsException: Type[BotocoreClientError]
     InvalidNextTokenException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
+    InvalidPolicyException: Type[BotocoreClientError]
     InvalidResourceTypeException: Type[BotocoreClientError]
     InvalidStateTransitionException: Type[BotocoreClientError]
     MalformedArnException: Type[BotocoreClientError]
+    MalformedPolicyTemplateException: Type[BotocoreClientError]
     MissingRequiredParameterException: Type[BotocoreClientError]
     OperationNotPermittedException: Type[BotocoreClientError]
+    PermissionAlreadyExistsException: Type[BotocoreClientError]
+    PermissionLimitExceededException: Type[BotocoreClientError]
+    PermissionVersionsLimitExceededException: Type[BotocoreClientError]
     ResourceArnNotFoundException: Type[BotocoreClientError]
     ResourceShareInvitationAlreadyAcceptedException: Type[BotocoreClientError]
     ResourceShareInvitationAlreadyRejectedException: Type[BotocoreClientError]
     ResourceShareInvitationArnNotFoundException: Type[BotocoreClientError]
     ResourceShareInvitationExpiredException: Type[BotocoreClientError]
     ResourceShareLimitExceededException: Type[BotocoreClientError]
     ServerInternalException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     TagLimitExceededException: Type[BotocoreClientError]
     TagPolicyViolationException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     UnknownResourceException: Type[BotocoreClientError]
+    UnmatchedPolicyPermissionException: Type[BotocoreClientError]
 
 class RAMClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/)
     """
 
@@ -168,14 +186,39 @@
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#close)
         """
+    async def create_permission(
+        self,
+        *,
+        name: str,
+        resourceType: str,
+        policyTemplate: str,
+        clientToken: str = ...,
+        tags: Sequence[TagTypeDef] = ...
+    ) -> CreatePermissionResponseTypeDef:
+        """
+        Creates a customer managed permission for a specified resource type that you can
+        attach to resource shares.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_permission)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#create_permission)
+        """
+    async def create_permission_version(
+        self, *, permissionArn: str, policyTemplate: str, clientToken: str = ...
+    ) -> CreatePermissionVersionResponseTypeDef:
+        """
+        Creates a new version of the specified customer managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_permission_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#create_permission_version)
+        """
     async def create_resource_share(
         self,
         *,
         name: str,
         resourceArns: Sequence[str] = ...,
         principals: Sequence[str] = ...,
         tags: Sequence[TagTypeDef] = ...,
@@ -185,14 +228,33 @@
     ) -> CreateResourceShareResponseTypeDef:
         """
         Creates a resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.create_resource_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#create_resource_share)
         """
+    async def delete_permission(
+        self, *, permissionArn: str, clientToken: str = ...
+    ) -> DeletePermissionResponseTypeDef:
+        """
+        Deletes the specified customer managed permission in the Amazon Web Services
+        Region in which you call this operation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_permission)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#delete_permission)
+        """
+    async def delete_permission_version(
+        self, *, permissionArn: str, permissionVersion: int, clientToken: str = ...
+    ) -> DeletePermissionVersionResponseTypeDef:
+        """
+        Deletes one version of a customer managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_permission_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#delete_permission_version)
+        """
     async def delete_resource_share(
         self, *, resourceShareArn: str, clientToken: str = ...
     ) -> DeleteResourceShareResponseTypeDef:
         """
         Deletes the specified resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.delete_resource_share)
@@ -203,25 +265,25 @@
         *,
         resourceShareArn: str,
         resourceArns: Sequence[str] = ...,
         principals: Sequence[str] = ...,
         clientToken: str = ...
     ) -> DisassociateResourceShareResponseTypeDef:
         """
-        Disassociates the specified principals or resources from the specified resource
-        share.
+        Removes the specified principals or resources from participating in the
+        specified resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.disassociate_resource_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#disassociate_resource_share)
         """
     async def disassociate_resource_share_permission(
         self, *, resourceShareArn: str, permissionArn: str, clientToken: str = ...
     ) -> DisassociateResourceSharePermissionResponseTypeDef:
         """
-        Disassociates an RAM permission from a resource share.
+        Removes a managed permission from a resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.disassociate_resource_share_permission)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#disassociate_resource_share_permission)
         """
     async def enable_sharing_with_aws_organization(
         self,
     ) -> EnableSharingWithAwsOrganizationResponseTypeDef:
@@ -244,15 +306,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#generate_presigned_url)
         """
     async def get_permission(
         self, *, permissionArn: str, permissionVersion: int = ...
     ) -> GetPermissionResponseTypeDef:
         """
-        Gets the contents of an RAM permission in JSON format.
+        Retrieves the contents of a managed permission in JSON format.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_permission)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#get_permission)
         """
     async def get_resource_policies(
         self,
         *,
@@ -276,16 +338,16 @@
         resourceArn: str = ...,
         principal: str = ...,
         associationStatus: ResourceShareAssociationStatusType = ...,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetResourceShareAssociationsResponseTypeDef:
         """
-        Retrieves the resource and principal associations for resource shares that you
-        own.
+        Retrieves the lists of resources and principals that associated for resource
+        shares that you own.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_share_associations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#get_resource_share_associations)
         """
     async def get_resource_share_invitations(
         self,
         *,
@@ -306,15 +368,16 @@
         resourceOwner: ResourceOwnerType,
         resourceShareArns: Sequence[str] = ...,
         resourceShareStatus: ResourceShareStatusType = ...,
         name: str = ...,
         tagFilters: Sequence[TagFilterTypeDef] = ...,
         nextToken: str = ...,
         maxResults: int = ...,
-        permissionArn: str = ...
+        permissionArn: str = ...,
+        permissionVersion: int = ...
     ) -> GetResourceSharesResponseTypeDef:
         """
         Retrieves details about the resource shares that you own or that are shared with
         you.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.get_resource_shares)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#get_resource_shares)
@@ -330,25 +393,49 @@
         """
         Lists the resources in a resource share that is shared with you but for which
         the invitation is still `PENDING`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_pending_invitation_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_pending_invitation_resources)
         """
+    async def list_permission_associations(
+        self,
+        *,
+        permissionArn: str = ...,
+        permissionVersion: int = ...,
+        associationStatus: ResourceShareAssociationStatusType = ...,
+        resourceType: str = ...,
+        featureSet: PermissionFeatureSetType = ...,
+        defaultVersion: bool = ...,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListPermissionAssociationsResponseTypeDef:
+        """
+        Lists information about the managed permission and its associations to any
+        resource shares that use this managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permission_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_permission_associations)
+        """
     async def list_permission_versions(
         self, *, permissionArn: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListPermissionVersionsResponseTypeDef:
         """
         Lists the available versions of the specified RAM permission.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permission_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_permission_versions)
         """
     async def list_permissions(
-        self, *, resourceType: str = ..., nextToken: str = ..., maxResults: int = ...
+        self,
+        *,
+        resourceType: str = ...,
+        nextToken: str = ...,
+        maxResults: int = ...,
+        permissionType: PermissionTypeFilterType = ...
     ) -> ListPermissionsResponseTypeDef:
         """
         Retrieves a list of available RAM permissions that you can use for the supported
         resource types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_permissions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_permissions)
@@ -367,14 +454,29 @@
         """
         Lists the principals that you are sharing resources with or that are sharing
         resources with you.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_principals)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_principals)
         """
+    async def list_replace_permission_associations_work(
+        self,
+        *,
+        workIds: Sequence[str] = ...,
+        status: ReplacePermissionAssociationsWorkStatusType = ...,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListReplacePermissionAssociationsWorkResponseTypeDef:
+        """
+        Retrieves the current status of the asynchronous tasks performed by RAM when you
+        perform the  ReplacePermissionAssociationsWork operation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_replace_permission_associations_work)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_replace_permission_associations_work)
+        """
     async def list_resource_share_permissions(
         self, *, resourceShareArn: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListResourceSharePermissionsResponseTypeDef:
         """
         Lists the RAM permissions that are associated with a resource share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resource_share_permissions)
@@ -408,48 +510,89 @@
         """
         Lists the resources that you added to a resource share or the resources that are
         shared with you.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.list_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#list_resources)
         """
+    async def promote_permission_created_from_policy(
+        self, *, permissionArn: str, name: str, clientToken: str = ...
+    ) -> PromotePermissionCreatedFromPolicyResponseTypeDef:
+        """
+        When you attach a resource-based policy to a resource, RAM automatically creates
+        a resource share of `featureSet`= `CREATED_FROM_POLICY` with a managed
+        permission that has the same IAM permissions as the original resource-based
+        policy.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.promote_permission_created_from_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#promote_permission_created_from_policy)
+        """
     async def promote_resource_share_created_from_policy(
         self, *, resourceShareArn: str
     ) -> PromoteResourceShareCreatedFromPolicyResponseTypeDef:
         """
-        When you attach a resource-based permission policy to a resource, it
-        automatically creates a resource share.
+        When you attach a resource-based policy to a resource, RAM automatically creates
+        a resource share of `featureSet`= `CREATED_FROM_POLICY` with a managed
+        permission that has the same IAM permissions as the original resource-based
+        policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.promote_resource_share_created_from_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#promote_resource_share_created_from_policy)
         """
     async def reject_resource_share_invitation(
         self, *, resourceShareInvitationArn: str, clientToken: str = ...
     ) -> RejectResourceShareInvitationResponseTypeDef:
         """
         Rejects an invitation to a resource share from another Amazon Web Services
         account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.reject_resource_share_invitation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#reject_resource_share_invitation)
         """
+    async def replace_permission_associations(
+        self,
+        *,
+        fromPermissionArn: str,
+        toPermissionArn: str,
+        fromPermissionVersion: int = ...,
+        clientToken: str = ...
+    ) -> ReplacePermissionAssociationsResponseTypeDef:
+        """
+        Updates all resource shares that use a managed permission to a different managed
+        permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.replace_permission_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#replace_permission_associations)
+        """
+    async def set_default_permission_version(
+        self, *, permissionArn: str, permissionVersion: int, clientToken: str = ...
+    ) -> SetDefaultPermissionVersionResponseTypeDef:
+        """
+        Designates the specified version number as the default version for the specified
+        customer managed permission.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.set_default_permission_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#set_default_permission_version)
+        """
     async def tag_resource(
-        self, *, resourceShareArn: str, tags: Sequence[TagTypeDef]
+        self, *, tags: Sequence[TagTypeDef], resourceShareArn: str = ..., resourceArn: str = ...
     ) -> Dict[str, Any]:
         """
-        Adds the specified tag keys and values to the specified resource share.
+        Adds the specified tag keys and values to a resource share or managed
+        permission.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#tag_resource)
         """
     async def untag_resource(
-        self, *, resourceShareArn: str, tagKeys: Sequence[str]
+        self, *, tagKeys: Sequence[str], resourceShareArn: str = ..., resourceArn: str = ...
     ) -> Dict[str, Any]:
         """
-        Removes the specified tag key and value pairs from the specified resource share.
+        Removes the specified tag key and value pairs from the specified resource share
+        or managed permission.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/client/#untag_resource)
         """
     async def update_resource_share(
         self,
         *,
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/literals.py` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -14,22 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "GetResourcePoliciesPaginatorName",
     "GetResourceShareAssociationsPaginatorName",
     "GetResourceShareInvitationsPaginatorName",
     "GetResourceSharesPaginatorName",
     "ListPrincipalsPaginatorName",
     "ListResourcesPaginatorName",
+    "PermissionFeatureSetType",
+    "PermissionStatusType",
+    "PermissionTypeFilterType",
+    "PermissionTypeType",
+    "ReplacePermissionAssociationsWorkStatusType",
     "ResourceOwnerType",
     "ResourceRegionScopeFilterType",
     "ResourceRegionScopeType",
     "ResourceShareAssociationStatusType",
     "ResourceShareAssociationTypeType",
     "ResourceShareFeatureSetType",
     "ResourceShareInvitationStatusType",
@@ -38,21 +42,25 @@
     "RAMServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 GetResourcePoliciesPaginatorName = Literal["get_resource_policies"]
 GetResourceShareAssociationsPaginatorName = Literal["get_resource_share_associations"]
 GetResourceShareInvitationsPaginatorName = Literal["get_resource_share_invitations"]
 GetResourceSharesPaginatorName = Literal["get_resource_shares"]
 ListPrincipalsPaginatorName = Literal["list_principals"]
 ListResourcesPaginatorName = Literal["list_resources"]
+PermissionFeatureSetType = Literal["CREATED_FROM_POLICY", "PROMOTING_TO_STANDARD", "STANDARD"]
+PermissionStatusType = Literal["ATTACHABLE", "DELETED", "DELETING", "UNATTACHABLE"]
+PermissionTypeFilterType = Literal["ALL", "AWS_MANAGED", "CUSTOMER_MANAGED"]
+PermissionTypeType = Literal["AWS_MANAGED", "CUSTOMER_MANAGED"]
+ReplacePermissionAssociationsWorkStatusType = Literal["COMPLETED", "FAILED", "IN_PROGRESS"]
 ResourceOwnerType = Literal["OTHER-ACCOUNTS", "SELF"]
 ResourceRegionScopeFilterType = Literal["ALL", "GLOBAL", "REGIONAL"]
 ResourceRegionScopeType = Literal["GLOBAL", "REGIONAL"]
 ResourceShareAssociationStatusType = Literal[
     "ASSOCIATED", "ASSOCIATING", "DISASSOCIATED", "DISASSOCIATING", "FAILED"
 ]
 ResourceShareAssociationTypeType = Literal["PRINCIPAL", "RESOURCE"]
@@ -121,14 +129,15 @@
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
@@ -207,14 +216,15 @@
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
@@ -225,14 +235,15 @@
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
@@ -268,14 +279,15 @@
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
@@ -294,16 +306,19 @@
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
@@ -387,15 +402,17 @@
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/literals.pyi` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/literals.py`

 * *Files 10% similar despite different names*

```diff
@@ -14,21 +14,27 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "GetResourcePoliciesPaginatorName",
     "GetResourceShareAssociationsPaginatorName",
     "GetResourceShareInvitationsPaginatorName",
     "GetResourceSharesPaginatorName",
     "ListPrincipalsPaginatorName",
     "ListResourcesPaginatorName",
+    "PermissionFeatureSetType",
+    "PermissionStatusType",
+    "PermissionTypeFilterType",
+    "PermissionTypeType",
+    "ReplacePermissionAssociationsWorkStatusType",
     "ResourceOwnerType",
     "ResourceRegionScopeFilterType",
     "ResourceRegionScopeType",
     "ResourceShareAssociationStatusType",
     "ResourceShareAssociationTypeType",
     "ResourceShareFeatureSetType",
     "ResourceShareInvitationStatusType",
@@ -37,20 +43,26 @@
     "RAMServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 GetResourcePoliciesPaginatorName = Literal["get_resource_policies"]
 GetResourceShareAssociationsPaginatorName = Literal["get_resource_share_associations"]
 GetResourceShareInvitationsPaginatorName = Literal["get_resource_share_invitations"]
 GetResourceSharesPaginatorName = Literal["get_resource_shares"]
 ListPrincipalsPaginatorName = Literal["list_principals"]
 ListResourcesPaginatorName = Literal["list_resources"]
+PermissionFeatureSetType = Literal["CREATED_FROM_POLICY", "PROMOTING_TO_STANDARD", "STANDARD"]
+PermissionStatusType = Literal["ATTACHABLE", "DELETED", "DELETING", "UNATTACHABLE"]
+PermissionTypeFilterType = Literal["ALL", "AWS_MANAGED", "CUSTOMER_MANAGED"]
+PermissionTypeType = Literal["AWS_MANAGED", "CUSTOMER_MANAGED"]
+ReplacePermissionAssociationsWorkStatusType = Literal["COMPLETED", "FAILED", "IN_PROGRESS"]
 ResourceOwnerType = Literal["OTHER-ACCOUNTS", "SELF"]
 ResourceRegionScopeFilterType = Literal["ALL", "GLOBAL", "REGIONAL"]
 ResourceRegionScopeType = Literal["GLOBAL", "REGIONAL"]
 ResourceShareAssociationStatusType = Literal[
     "ASSOCIATED", "ASSOCIATING", "DISASSOCIATED", "DISASSOCIATING", "FAILED"
 ]
 ResourceShareAssociationTypeType = Literal["PRINCIPAL", "RESOURCE"]
@@ -119,14 +131,15 @@
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
@@ -205,14 +218,15 @@
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
@@ -223,14 +237,15 @@
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
@@ -266,14 +281,15 @@
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
@@ -292,16 +308,19 @@
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
@@ -385,15 +404,17 @@
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/paginator.py` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         get_resource_share_associations_paginator: GetResourceShareAssociationsPaginator = client.get_paginator("get_resource_share_associations")
         get_resource_share_invitations_paginator: GetResourceShareInvitationsPaginator = client.get_paginator("get_resource_share_invitations")
         get_resource_shares_paginator: GetResourceSharesPaginator = client.get_paginator("get_resource_shares")
         list_principals_paginator: ListPrincipalsPaginator = client.get_paginator("list_principals")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
@@ -50,20 +49,14 @@
     GetResourceSharesResponseTypeDef,
     ListPrincipalsResponseTypeDef,
     ListResourcesResponseTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetResourcePoliciesPaginator",
     "GetResourceShareAssociationsPaginator",
     "GetResourceShareInvitationsPaginator",
     "GetResourceSharesPaginator",
     "ListPrincipalsPaginator",
     "ListResourcesPaginator",
@@ -87,15 +80,15 @@
     """
 
     def paginate(
         self,
         *,
         resourceArns: Sequence[str],
         principal: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourcepoliciespaginator)
         """
 
 
@@ -109,15 +102,15 @@
         self,
         *,
         associationType: ResourceShareAssociationTypeType,
         resourceShareArns: Sequence[str] = ...,
         resourceArn: str = ...,
         principal: str = ...,
         associationStatus: ResourceShareAssociationStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceShareAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShareAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourceshareassociationspaginator)
         """
 
 
@@ -128,15 +121,15 @@
     """
 
     def paginate(
         self,
         *,
         resourceShareInvitationArns: Sequence[str] = ...,
         resourceShareArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceShareInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShareInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourceshareinvitationspaginator)
         """
 
 
@@ -151,15 +144,16 @@
         *,
         resourceOwner: ResourceOwnerType,
         resourceShareArns: Sequence[str] = ...,
         resourceShareStatus: ResourceShareStatusType = ...,
         name: str = ...,
         tagFilters: Sequence[TagFilterTypeDef] = ...,
         permissionArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        permissionVersion: int = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceSharesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShares.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourcesharespaginator)
         """
 
 
@@ -173,15 +167,15 @@
         self,
         *,
         resourceOwner: ResourceOwnerType,
         resourceArn: str = ...,
         principals: Sequence[str] = ...,
         resourceType: str = ...,
         resourceShareArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.ListPrincipals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#listprincipalspaginator)
         """
 
 
@@ -196,13 +190,13 @@
         *,
         resourceOwner: ResourceOwnerType,
         principal: str = ...,
         resourceType: str = ...,
         resourceArns: Sequence[str] = ...,
         resourceShareArns: Sequence[str] = ...,
         resourceRegionScope: ResourceRegionScopeFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#listresourcespaginator)
         """
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/paginator.pyi` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         get_resource_share_associations_paginator: GetResourceShareAssociationsPaginator = client.get_paginator("get_resource_share_associations")
         get_resource_share_invitations_paginator: GetResourceShareInvitationsPaginator = client.get_paginator("get_resource_share_invitations")
         get_resource_shares_paginator: GetResourceSharesPaginator = client.get_paginator("get_resource_shares")
         list_principals_paginator: ListPrincipalsPaginator = client.get_paginator("list_principals")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
@@ -50,19 +49,14 @@
     GetResourceSharesResponseTypeDef,
     ListPrincipalsResponseTypeDef,
     ListResourcesResponseTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetResourcePoliciesPaginator",
     "GetResourceShareAssociationsPaginator",
     "GetResourceShareInvitationsPaginator",
     "GetResourceSharesPaginator",
     "ListPrincipalsPaginator",
     "ListResourcesPaginator",
@@ -83,15 +77,15 @@
     """
 
     def paginate(
         self,
         *,
         resourceArns: Sequence[str],
         principal: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourcepoliciespaginator)
         """
 
 class GetResourceShareAssociationsPaginator(AioPaginator):
@@ -104,15 +98,15 @@
         self,
         *,
         associationType: ResourceShareAssociationTypeType,
         resourceShareArns: Sequence[str] = ...,
         resourceArn: str = ...,
         principal: str = ...,
         associationStatus: ResourceShareAssociationStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceShareAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShareAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourceshareassociationspaginator)
         """
 
 class GetResourceShareInvitationsPaginator(AioPaginator):
@@ -122,15 +116,15 @@
     """
 
     def paginate(
         self,
         *,
         resourceShareInvitationArns: Sequence[str] = ...,
         resourceShareArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceShareInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShareInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourceshareinvitationspaginator)
         """
 
 class GetResourceSharesPaginator(AioPaginator):
@@ -144,15 +138,16 @@
         *,
         resourceOwner: ResourceOwnerType,
         resourceShareArns: Sequence[str] = ...,
         resourceShareStatus: ResourceShareStatusType = ...,
         name: str = ...,
         tagFilters: Sequence[TagFilterTypeDef] = ...,
         permissionArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        permissionVersion: int = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceSharesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.GetResourceShares.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#getresourcesharespaginator)
         """
 
 class ListPrincipalsPaginator(AioPaginator):
@@ -165,15 +160,15 @@
         self,
         *,
         resourceOwner: ResourceOwnerType,
         resourceArn: str = ...,
         principals: Sequence[str] = ...,
         resourceType: str = ...,
         resourceShareArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.ListPrincipals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#listprincipalspaginator)
         """
 
 class ListResourcesPaginator(AioPaginator):
@@ -187,13 +182,13 @@
         *,
         resourceOwner: ResourceOwnerType,
         principal: str = ...,
         resourceType: str = ...,
         resourceArns: Sequence[str] = ...,
         resourceShareArns: Sequence[str] = ...,
         resourceRegionScope: ResourceRegionScopeFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/paginators/#listresourcespaginator)
         """
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/type_defs.py` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/type_defs.py`

 * *Files 23% similar despite different names*

```diff
@@ -12,14 +12,19 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    PermissionFeatureSetType,
+    PermissionStatusType,
+    PermissionTypeFilterType,
+    PermissionTypeType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceRegionScopeType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareFeatureSetType,
     ResourceShareInvitationStatusType,
@@ -31,75 +36,95 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptResourceShareInvitationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociateResourceSharePermissionRequestRequestTypeDef",
+    "AssociateResourceSharePermissionResponseTypeDef",
     "AssociateResourceShareRequestRequestTypeDef",
     "ResourceShareAssociationTypeDef",
+    "AssociatedPermissionTypeDef",
     "TagTypeDef",
+    "CreatePermissionVersionRequestRequestTypeDef",
+    "DeletePermissionRequestRequestTypeDef",
+    "DeletePermissionResponseTypeDef",
+    "DeletePermissionVersionRequestRequestTypeDef",
+    "DeletePermissionVersionResponseTypeDef",
     "DeleteResourceShareRequestRequestTypeDef",
+    "DeleteResourceShareResponseTypeDef",
     "DisassociateResourceSharePermissionRequestRequestTypeDef",
+    "DisassociateResourceSharePermissionResponseTypeDef",
     "DisassociateResourceShareRequestRequestTypeDef",
+    "EnableSharingWithAwsOrganizationResponseTypeDef",
     "GetPermissionRequestRequestTypeDef",
-    "ResourceSharePermissionDetailTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesRequestRequestTypeDef",
+    "GetResourcePoliciesResponseTypeDef",
+    "GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
     "GetResourceShareAssociationsRequestRequestTypeDef",
+    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
     "GetResourceShareInvitationsRequestRequestTypeDef",
     "TagFilterTypeDef",
     "ListPendingInvitationResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
+    "ListPermissionAssociationsRequestRequestTypeDef",
     "ListPermissionVersionsRequestRequestTypeDef",
-    "ResourceSharePermissionSummaryTypeDef",
     "ListPermissionsRequestRequestTypeDef",
+    "ListPrincipalsRequestListPrincipalsPaginateTypeDef",
     "ListPrincipalsRequestRequestTypeDef",
     "PrincipalTypeDef",
+    "ListReplacePermissionAssociationsWorkRequestRequestTypeDef",
+    "ReplacePermissionAssociationsWorkTypeDef",
     "ListResourceSharePermissionsRequestRequestTypeDef",
     "ListResourceTypesRequestRequestTypeDef",
     "ServiceNameAndResourceTypeTypeDef",
+    "ListResourcesRequestListResourcesPaginateTypeDef",
     "ListResourcesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "PromotePermissionCreatedFromPolicyRequestRequestTypeDef",
     "PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef",
+    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
     "RejectResourceShareInvitationRequestRequestTypeDef",
+    "ReplacePermissionAssociationsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SetDefaultPermissionVersionRequestRequestTypeDef",
+    "SetDefaultPermissionVersionResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateResourceShareRequestRequestTypeDef",
-    "AssociateResourceSharePermissionResponseTypeDef",
-    "DeleteResourceShareResponseTypeDef",
-    "DisassociateResourceSharePermissionResponseTypeDef",
-    "EnableSharingWithAwsOrganizationResponseTypeDef",
-    "GetResourcePoliciesResponseTypeDef",
-    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
     "AssociateResourceShareResponseTypeDef",
     "DisassociateResourceShareResponseTypeDef",
     "GetResourceShareAssociationsResponseTypeDef",
     "ResourceShareInvitationTypeDef",
+    "ListPermissionAssociationsResponseTypeDef",
+    "CreatePermissionRequestRequestTypeDef",
     "CreateResourceShareRequestRequestTypeDef",
+    "ResourceSharePermissionDetailTypeDef",
+    "ResourceSharePermissionSummaryTypeDef",
     "ResourceShareTypeDef",
     "TagResourceRequestRequestTypeDef",
-    "GetPermissionResponseTypeDef",
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    "GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
-    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
-    "ListPrincipalsRequestListPrincipalsPaginateTypeDef",
-    "ListResourcesRequestListResourcesPaginateTypeDef",
     "GetResourceSharesRequestGetResourceSharesPaginateTypeDef",
     "GetResourceSharesRequestRequestTypeDef",
     "ListPendingInvitationResourcesResponseTypeDef",
     "ListResourcesResponseTypeDef",
-    "ListPermissionVersionsResponseTypeDef",
-    "ListPermissionsResponseTypeDef",
-    "ListResourceSharePermissionsResponseTypeDef",
     "ListPrincipalsResponseTypeDef",
+    "ListReplacePermissionAssociationsWorkResponseTypeDef",
+    "ReplacePermissionAssociationsResponseTypeDef",
     "ListResourceTypesResponseTypeDef",
     "AcceptResourceShareInvitationResponseTypeDef",
     "GetResourceShareInvitationsResponseTypeDef",
     "RejectResourceShareInvitationResponseTypeDef",
+    "CreatePermissionVersionResponseTypeDef",
+    "GetPermissionResponseTypeDef",
+    "CreatePermissionResponseTypeDef",
+    "ListPermissionVersionsResponseTypeDef",
+    "ListPermissionsResponseTypeDef",
+    "ListResourceSharePermissionsResponseTypeDef",
+    "PromotePermissionCreatedFromPolicyResponseTypeDef",
     "CreateResourceShareResponseTypeDef",
     "GetResourceSharesResponseTypeDef",
     "UpdateResourceShareResponseTypeDef",
 )
 
 _RequiredAcceptResourceShareInvitationRequestRequestTypeDef = TypedDict(
     "_RequiredAcceptResourceShareInvitationRequestRequestTypeDef",
@@ -119,25 +144,14 @@
 class AcceptResourceShareInvitationRequestRequestTypeDef(
     _RequiredAcceptResourceShareInvitationRequestRequestTypeDef,
     _OptionalAcceptResourceShareInvitationRequestRequestTypeDef,
 ):
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
 _RequiredAssociateResourceSharePermissionRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateResourceSharePermissionRequestRequestTypeDef",
     {
         "resourceShareArn": str,
         "permissionArn": str,
     },
 )
@@ -155,14 +169,23 @@
 class AssociateResourceSharePermissionRequestRequestTypeDef(
     _RequiredAssociateResourceSharePermissionRequestRequestTypeDef,
     _OptionalAssociateResourceSharePermissionRequestRequestTypeDef,
 ):
     pass
 
 
+AssociateResourceSharePermissionResponseTypeDef = TypedDict(
+    "AssociateResourceSharePermissionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateResourceShareRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalAssociateResourceShareRequestRequestTypeDef = TypedDict(
@@ -195,23 +218,125 @@
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
         "external": bool,
     },
     total=False,
 )
 
+AssociatedPermissionTypeDef = TypedDict(
+    "AssociatedPermissionTypeDef",
+    {
+        "arn": str,
+        "permissionVersion": str,
+        "defaultVersion": bool,
+        "resourceType": str,
+        "status": str,
+        "featureSet": PermissionFeatureSetType,
+        "lastUpdatedTime": datetime,
+        "resourceShareArn": str,
+    },
+    total=False,
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
     total=False,
 )
 
+_RequiredCreatePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePermissionVersionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "policyTemplate": str,
+    },
+)
+_OptionalCreatePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePermissionVersionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class CreatePermissionVersionRequestRequestTypeDef(
+    _RequiredCreatePermissionVersionRequestRequestTypeDef,
+    _OptionalCreatePermissionVersionRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredDeletePermissionRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePermissionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+    },
+)
+_OptionalDeletePermissionRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePermissionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class DeletePermissionRequestRequestTypeDef(
+    _RequiredDeletePermissionRequestRequestTypeDef, _OptionalDeletePermissionRequestRequestTypeDef
+):
+    pass
+
+
+DeletePermissionResponseTypeDef = TypedDict(
+    "DeletePermissionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "permissionStatus": PermissionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDeletePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePermissionVersionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "permissionVersion": int,
+    },
+)
+_OptionalDeletePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePermissionVersionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class DeletePermissionVersionRequestRequestTypeDef(
+    _RequiredDeletePermissionVersionRequestRequestTypeDef,
+    _OptionalDeletePermissionVersionRequestRequestTypeDef,
+):
+    pass
+
+
+DeletePermissionVersionResponseTypeDef = TypedDict(
+    "DeletePermissionVersionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "permissionStatus": PermissionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourceShareRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalDeleteResourceShareRequestRequestTypeDef = TypedDict(
@@ -226,14 +351,23 @@
 class DeleteResourceShareRequestRequestTypeDef(
     _RequiredDeleteResourceShareRequestRequestTypeDef,
     _OptionalDeleteResourceShareRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteResourceShareResponseTypeDef = TypedDict(
+    "DeleteResourceShareResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateResourceSharePermissionRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateResourceSharePermissionRequestRequestTypeDef",
     {
         "resourceShareArn": str,
         "permissionArn": str,
     },
 )
@@ -249,14 +383,23 @@
 class DisassociateResourceSharePermissionRequestRequestTypeDef(
     _RequiredDisassociateResourceSharePermissionRequestRequestTypeDef,
     _OptionalDisassociateResourceSharePermissionRequestRequestTypeDef,
 ):
     pass
 
 
+DisassociateResourceSharePermissionResponseTypeDef = TypedDict(
+    "DisassociateResourceSharePermissionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateResourceShareRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalDisassociateResourceShareRequestRequestTypeDef = TypedDict(
@@ -273,14 +416,22 @@
 class DisassociateResourceShareRequestRequestTypeDef(
     _RequiredDisassociateResourceShareRequestRequestTypeDef,
     _OptionalDisassociateResourceShareRequestRequestTypeDef,
 ):
     pass
 
 
+EnableSharingWithAwsOrganizationResponseTypeDef = TypedDict(
+    "EnableSharingWithAwsOrganizationResponseTypeDef",
+    {
+        "returnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredGetPermissionRequestRequestTypeDef",
     {
         "permissionArn": str,
     },
 )
 _OptionalGetPermissionRequestRequestTypeDef = TypedDict(
@@ -294,40 +445,37 @@
 
 class GetPermissionRequestRequestTypeDef(
     _RequiredGetPermissionRequestRequestTypeDef, _OptionalGetPermissionRequestRequestTypeDef
 ):
     pass
 
 
-ResourceSharePermissionDetailTypeDef = TypedDict(
-    "ResourceSharePermissionDetailTypeDef",
+_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     {
-        "arn": str,
-        "version": str,
-        "defaultVersion": bool,
-        "name": str,
-        "resourceType": str,
-        "permission": str,
-        "creationTime": datetime,
-        "lastUpdatedTime": datetime,
-        "isResourceTypeDefault": bool,
+        "resourceArns": Sequence[str],
     },
-    total=False,
 )
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "principal": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
+    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetResourcePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourcePoliciesRequestRequestTypeDef",
     {
         "resourceArns": Sequence[str],
     },
 )
 _OptionalGetResourcePoliciesRequestRequestTypeDef = TypedDict(
@@ -344,14 +492,49 @@
 class GetResourcePoliciesRequestRequestTypeDef(
     _RequiredGetResourcePoliciesRequestRequestTypeDef,
     _OptionalGetResourcePoliciesRequestRequestTypeDef,
 ):
     pass
 
 
+GetResourcePoliciesResponseTypeDef = TypedDict(
+    "GetResourcePoliciesResponseTypeDef",
+    {
+        "policies": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
+    {
+        "associationType": ResourceShareAssociationTypeType,
+    },
+)
+_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
+    {
+        "resourceShareArns": Sequence[str],
+        "resourceArn": str,
+        "principal": str,
+        "associationStatus": ResourceShareAssociationStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef(
+    _RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
+    _OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetResourceShareAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourceShareAssociationsRequestRequestTypeDef",
     {
         "associationType": ResourceShareAssociationTypeType,
     },
 )
 _OptionalGetResourceShareAssociationsRequestRequestTypeDef = TypedDict(
@@ -371,14 +554,24 @@
 class GetResourceShareAssociationsRequestRequestTypeDef(
     _RequiredGetResourceShareAssociationsRequestRequestTypeDef,
     _OptionalGetResourceShareAssociationsRequestRequestTypeDef,
 ):
     pass
 
 
+GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef = TypedDict(
+    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
+    {
+        "resourceShareInvitationArns": Sequence[str],
+        "resourceShareArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetResourceShareInvitationsRequestRequestTypeDef = TypedDict(
     "GetResourceShareInvitationsRequestRequestTypeDef",
     {
         "resourceShareInvitationArns": Sequence[str],
         "resourceShareArns": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -431,14 +624,29 @@
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
         "resourceRegionScope": ResourceRegionScopeType,
     },
     total=False,
 )
 
+ListPermissionAssociationsRequestRequestTypeDef = TypedDict(
+    "ListPermissionAssociationsRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "permissionVersion": int,
+        "associationStatus": ResourceShareAssociationStatusType,
+        "resourceType": str,
+        "featureSet": PermissionFeatureSetType,
+        "defaultVersion": bool,
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
 _RequiredListPermissionVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionVersionsRequestRequestTypeDef",
     {
         "permissionArn": str,
     },
 )
 _OptionalListPermissionVersionsRequestRequestTypeDef = TypedDict(
@@ -454,40 +662,51 @@
 class ListPermissionVersionsRequestRequestTypeDef(
     _RequiredListPermissionVersionsRequestRequestTypeDef,
     _OptionalListPermissionVersionsRequestRequestTypeDef,
 ):
     pass
 
 
-ResourceSharePermissionSummaryTypeDef = TypedDict(
-    "ResourceSharePermissionSummaryTypeDef",
+ListPermissionsRequestRequestTypeDef = TypedDict(
+    "ListPermissionsRequestRequestTypeDef",
     {
-        "arn": str,
-        "version": str,
-        "defaultVersion": bool,
-        "name": str,
         "resourceType": str,
-        "status": str,
-        "creationTime": datetime,
-        "lastUpdatedTime": datetime,
-        "isResourceTypeDefault": bool,
+        "nextToken": str,
+        "maxResults": int,
+        "permissionType": PermissionTypeFilterType,
     },
     total=False,
 )
 
-ListPermissionsRequestRequestTypeDef = TypedDict(
-    "ListPermissionsRequestRequestTypeDef",
+_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef",
     {
+        "resourceOwner": ResourceOwnerType,
+    },
+)
+_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef",
+    {
+        "resourceArn": str,
+        "principals": Sequence[str],
         "resourceType": str,
-        "nextToken": str,
-        "maxResults": int,
+        "resourceShareArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListPrincipalsRequestListPrincipalsPaginateTypeDef(
+    _RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef,
+    _OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPrincipalsRequestRequestTypeDef = TypedDict(
     "_RequiredListPrincipalsRequestRequestTypeDef",
     {
         "resourceOwner": ResourceOwnerType,
     },
 )
 _OptionalListPrincipalsRequestRequestTypeDef = TypedDict(
@@ -518,14 +737,41 @@
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
         "external": bool,
     },
     total=False,
 )
 
+ListReplacePermissionAssociationsWorkRequestRequestTypeDef = TypedDict(
+    "ListReplacePermissionAssociationsWorkRequestRequestTypeDef",
+    {
+        "workIds": Sequence[str],
+        "status": ReplacePermissionAssociationsWorkStatusType,
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+ReplacePermissionAssociationsWorkTypeDef = TypedDict(
+    "ReplacePermissionAssociationsWorkTypeDef",
+    {
+        "id": str,
+        "fromPermissionArn": str,
+        "fromPermissionVersion": str,
+        "toPermissionArn": str,
+        "toPermissionVersion": str,
+        "status": ReplacePermissionAssociationsWorkStatusType,
+        "statusMessage": str,
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+    },
+    total=False,
+)
+
 _RequiredListResourceSharePermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceSharePermissionsRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalListResourceSharePermissionsRequestRequestTypeDef = TypedDict(
@@ -561,14 +807,41 @@
         "resourceType": str,
         "serviceName": str,
         "resourceRegionScope": ResourceRegionScopeType,
     },
     total=False,
 )
 
+_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "resourceOwner": ResourceOwnerType,
+    },
+)
+_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "principal": str,
+        "resourceType": str,
+        "resourceArns": Sequence[str],
+        "resourceShareArns": Sequence[str],
+        "resourceRegionScope": ResourceRegionScopeFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourcesRequestListResourcesPaginateTypeDef(
+    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
+    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesRequestRequestTypeDef",
     {
         "resourceOwner": ResourceOwnerType,
     },
 )
 _OptionalListResourcesRequestRequestTypeDef = TypedDict(
@@ -588,21 +861,62 @@
 
 class ListResourcesRequestRequestTypeDef(
     _RequiredListResourcesRequestRequestTypeDef, _OptionalListResourcesRequestRequestTypeDef
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
+_RequiredPromotePermissionCreatedFromPolicyRequestRequestTypeDef = TypedDict(
+    "_RequiredPromotePermissionCreatedFromPolicyRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "name": str,
+    },
+)
+_OptionalPromotePermissionCreatedFromPolicyRequestRequestTypeDef = TypedDict(
+    "_OptionalPromotePermissionCreatedFromPolicyRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class PromotePermissionCreatedFromPolicyRequestRequestTypeDef(
+    _RequiredPromotePermissionCreatedFromPolicyRequestRequestTypeDef,
+    _OptionalPromotePermissionCreatedFromPolicyRequestRequestTypeDef,
+):
+    pass
+
+
 PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef = TypedDict(
     "PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 
+PromoteResourceShareCreatedFromPolicyResponseTypeDef = TypedDict(
+    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
+    {
+        "returnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRejectResourceShareInvitationRequestRequestTypeDef = TypedDict(
     "_RequiredRejectResourceShareInvitationRequestRequestTypeDef",
     {
         "resourceShareInvitationArn": str,
     },
 )
 _OptionalRejectResourceShareInvitationRequestRequestTypeDef = TypedDict(
@@ -617,122 +931,151 @@
 class RejectResourceShareInvitationRequestRequestTypeDef(
     _RequiredRejectResourceShareInvitationRequestRequestTypeDef,
     _OptionalRejectResourceShareInvitationRequestRequestTypeDef,
 ):
     pass
 
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceShareArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-_RequiredUpdateResourceShareRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateResourceShareRequestRequestTypeDef",
+_RequiredReplacePermissionAssociationsRequestRequestTypeDef = TypedDict(
+    "_RequiredReplacePermissionAssociationsRequestRequestTypeDef",
     {
-        "resourceShareArn": str,
+        "fromPermissionArn": str,
+        "toPermissionArn": str,
     },
 )
-_OptionalUpdateResourceShareRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateResourceShareRequestRequestTypeDef",
+_OptionalReplacePermissionAssociationsRequestRequestTypeDef = TypedDict(
+    "_OptionalReplacePermissionAssociationsRequestRequestTypeDef",
     {
-        "name": str,
-        "allowExternalPrincipals": bool,
+        "fromPermissionVersion": int,
         "clientToken": str,
     },
     total=False,
 )
 
 
-class UpdateResourceShareRequestRequestTypeDef(
-    _RequiredUpdateResourceShareRequestRequestTypeDef,
-    _OptionalUpdateResourceShareRequestRequestTypeDef,
+class ReplacePermissionAssociationsRequestRequestTypeDef(
+    _RequiredReplacePermissionAssociationsRequestRequestTypeDef,
+    _OptionalReplacePermissionAssociationsRequestRequestTypeDef,
 ):
     pass
 
 
-AssociateResourceSharePermissionResponseTypeDef = TypedDict(
-    "AssociateResourceSharePermissionResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "returnValue": bool,
-        "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-DeleteResourceShareResponseTypeDef = TypedDict(
-    "DeleteResourceShareResponseTypeDef",
+_RequiredSetDefaultPermissionVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredSetDefaultPermissionVersionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "permissionVersion": int,
+    },
+)
+_OptionalSetDefaultPermissionVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalSetDefaultPermissionVersionRequestRequestTypeDef",
     {
-        "returnValue": bool,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-DisassociateResourceSharePermissionResponseTypeDef = TypedDict(
-    "DisassociateResourceSharePermissionResponseTypeDef",
+
+class SetDefaultPermissionVersionRequestRequestTypeDef(
+    _RequiredSetDefaultPermissionVersionRequestRequestTypeDef,
+    _OptionalSetDefaultPermissionVersionRequestRequestTypeDef,
+):
+    pass
+
+
+SetDefaultPermissionVersionResponseTypeDef = TypedDict(
+    "SetDefaultPermissionVersionResponseTypeDef",
     {
         "returnValue": bool,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EnableSharingWithAwsOrganizationResponseTypeDef = TypedDict(
-    "EnableSharingWithAwsOrganizationResponseTypeDef",
+_RequiredUntagResourceRequestRequestTypeDef = TypedDict(
+    "_RequiredUntagResourceRequestRequestTypeDef",
     {
-        "returnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tagKeys": Sequence[str],
     },
 )
-
-GetResourcePoliciesResponseTypeDef = TypedDict(
-    "GetResourcePoliciesResponseTypeDef",
+_OptionalUntagResourceRequestRequestTypeDef = TypedDict(
+    "_OptionalUntagResourceRequestRequestTypeDef",
     {
-        "policies": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceShareArn": str,
+        "resourceArn": str,
     },
+    total=False,
 )
 
-PromoteResourceShareCreatedFromPolicyResponseTypeDef = TypedDict(
-    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
+
+class UntagResourceRequestRequestTypeDef(
+    _RequiredUntagResourceRequestRequestTypeDef, _OptionalUntagResourceRequestRequestTypeDef
+):
+    pass
+
+
+_RequiredUpdateResourceShareRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateResourceShareRequestRequestTypeDef",
     {
-        "returnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceShareArn": str,
+    },
+)
+_OptionalUpdateResourceShareRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateResourceShareRequestRequestTypeDef",
+    {
+        "name": str,
+        "allowExternalPrincipals": bool,
+        "clientToken": str,
     },
+    total=False,
 )
 
+
+class UpdateResourceShareRequestRequestTypeDef(
+    _RequiredUpdateResourceShareRequestRequestTypeDef,
+    _OptionalUpdateResourceShareRequestRequestTypeDef,
+):
+    pass
+
+
 AssociateResourceShareResponseTypeDef = TypedDict(
     "AssociateResourceShareResponseTypeDef",
     {
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResourceShareResponseTypeDef = TypedDict(
     "DisassociateResourceShareResponseTypeDef",
     {
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceShareAssociationsResponseTypeDef = TypedDict(
     "GetResourceShareAssociationsResponseTypeDef",
     {
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceShareInvitationTypeDef = TypedDict(
     "ResourceShareInvitationTypeDef",
     {
         "resourceShareInvitationArn": str,
@@ -744,14 +1087,47 @@
         "status": ResourceShareInvitationStatusType,
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "receiverArn": str,
     },
     total=False,
 )
 
+ListPermissionAssociationsResponseTypeDef = TypedDict(
+    "ListPermissionAssociationsResponseTypeDef",
+    {
+        "permissions": List[AssociatedPermissionTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreatePermissionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePermissionRequestRequestTypeDef",
+    {
+        "name": str,
+        "resourceType": str,
+        "policyTemplate": str,
+    },
+)
+_OptionalCreatePermissionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePermissionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreatePermissionRequestRequestTypeDef(
+    _RequiredCreatePermissionRequestRequestTypeDef, _OptionalCreatePermissionRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredCreateResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResourceShareRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateResourceShareRequestRequestTypeDef = TypedDict(
@@ -771,155 +1147,88 @@
 class CreateResourceShareRequestRequestTypeDef(
     _RequiredCreateResourceShareRequestRequestTypeDef,
     _OptionalCreateResourceShareRequestRequestTypeDef,
 ):
     pass
 
 
-ResourceShareTypeDef = TypedDict(
-    "ResourceShareTypeDef",
+ResourceSharePermissionDetailTypeDef = TypedDict(
+    "ResourceSharePermissionDetailTypeDef",
     {
-        "resourceShareArn": str,
+        "arn": str,
+        "version": str,
+        "defaultVersion": bool,
         "name": str,
-        "owningAccountId": str,
-        "allowExternalPrincipals": bool,
-        "status": ResourceShareStatusType,
-        "statusMessage": str,
-        "tags": List[TagTypeDef],
+        "resourceType": str,
+        "permission": str,
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
-        "featureSet": ResourceShareFeatureSetType,
-    },
-    total=False,
-)
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceShareArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-GetPermissionResponseTypeDef = TypedDict(
-    "GetPermissionResponseTypeDef",
-    {
-        "permission": ResourceSharePermissionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "resourceArns": Sequence[str],
-    },
-)
-_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "principal": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "isResourceTypeDefault": bool,
+        "permissionType": PermissionTypeType,
+        "featureSet": PermissionFeatureSetType,
+        "status": PermissionStatusType,
+        "tags": List[TagTypeDef],
     },
     total=False,
 )
 
-
-class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
-    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
-    {
-        "associationType": ResourceShareAssociationTypeType,
-    },
-)
-_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
+ResourceSharePermissionSummaryTypeDef = TypedDict(
+    "ResourceSharePermissionSummaryTypeDef",
     {
-        "resourceShareArns": Sequence[str],
-        "resourceArn": str,
-        "principal": str,
-        "associationStatus": ResourceShareAssociationStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "arn": str,
+        "version": str,
+        "defaultVersion": bool,
+        "name": str,
+        "resourceType": str,
+        "status": str,
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+        "isResourceTypeDefault": bool,
+        "permissionType": PermissionTypeType,
+        "featureSet": PermissionFeatureSetType,
+        "tags": List[TagTypeDef],
     },
     total=False,
 )
 
-
-class GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef(
-    _RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-    _OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-):
-    pass
-
-
-GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef = TypedDict(
-    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
+ResourceShareTypeDef = TypedDict(
+    "ResourceShareTypeDef",
     {
-        "resourceShareInvitationArns": Sequence[str],
-        "resourceShareArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "resourceShareArn": str,
+        "name": str,
+        "owningAccountId": str,
+        "allowExternalPrincipals": bool,
+        "status": ResourceShareStatusType,
+        "statusMessage": str,
+        "tags": List[TagTypeDef],
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+        "featureSet": ResourceShareFeatureSetType,
     },
     total=False,
 )
 
-_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef",
+_RequiredTagResourceRequestRequestTypeDef = TypedDict(
+    "_RequiredTagResourceRequestRequestTypeDef",
     {
-        "resourceOwner": ResourceOwnerType,
+        "tags": Sequence[TagTypeDef],
     },
 )
-_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef",
+_OptionalTagResourceRequestRequestTypeDef = TypedDict(
+    "_OptionalTagResourceRequestRequestTypeDef",
     {
+        "resourceShareArn": str,
         "resourceArn": str,
-        "principals": Sequence[str],
-        "resourceType": str,
-        "resourceShareArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPrincipalsRequestListPrincipalsPaginateTypeDef(
-    _RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef,
-    _OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "resourceOwner": ResourceOwnerType,
-    },
-)
-_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "principal": str,
-        "resourceType": str,
-        "resourceArns": Sequence[str],
-        "resourceShareArns": Sequence[str],
-        "resourceRegionScope": ResourceRegionScopeFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
 
-class ListResourcesRequestListResourcesPaginateTypeDef(
-    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
-    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+class TagResourceRequestRequestTypeDef(
+    _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
 
 _RequiredGetResourceSharesRequestGetResourceSharesPaginateTypeDef = TypedDict(
     "_RequiredGetResourceSharesRequestGetResourceSharesPaginateTypeDef",
     {
@@ -930,15 +1239,16 @@
     "_OptionalGetResourceSharesRequestGetResourceSharesPaginateTypeDef",
     {
         "resourceShareArns": Sequence[str],
         "resourceShareStatus": ResourceShareStatusType,
         "name": str,
         "tagFilters": Sequence[TagFilterTypeDef],
         "permissionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "permissionVersion": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetResourceSharesRequestGetResourceSharesPaginateTypeDef(
     _RequiredGetResourceSharesRequestGetResourceSharesPaginateTypeDef,
@@ -959,14 +1269,15 @@
         "resourceShareArns": Sequence[str],
         "resourceShareStatus": ResourceShareStatusType,
         "name": str,
         "tagFilters": Sequence[TagFilterTypeDef],
         "nextToken": str,
         "maxResults": int,
         "permissionArn": str,
+        "permissionVersion": int,
     },
     total=False,
 )
 
 
 class GetResourceSharesRequestRequestTypeDef(
     _RequiredGetResourceSharesRequestRequestTypeDef, _OptionalGetResourceSharesRequestRequestTypeDef
@@ -975,118 +1286,171 @@
 
 
 ListPendingInvitationResourcesResponseTypeDef = TypedDict(
     "ListPendingInvitationResourcesResponseTypeDef",
     {
         "resources": List[ResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResponseTypeDef = TypedDict(
     "ListResourcesResponseTypeDef",
     {
         "resources": List[ResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPermissionVersionsResponseTypeDef = TypedDict(
-    "ListPermissionVersionsResponseTypeDef",
-    {
-        "permissions": List[ResourceSharePermissionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPermissionsResponseTypeDef = TypedDict(
-    "ListPermissionsResponseTypeDef",
+ListPrincipalsResponseTypeDef = TypedDict(
+    "ListPrincipalsResponseTypeDef",
     {
-        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "principals": List[PrincipalTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListResourceSharePermissionsResponseTypeDef = TypedDict(
-    "ListResourceSharePermissionsResponseTypeDef",
+ListReplacePermissionAssociationsWorkResponseTypeDef = TypedDict(
+    "ListReplacePermissionAssociationsWorkResponseTypeDef",
     {
-        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "replacePermissionAssociationsWorks": List[ReplacePermissionAssociationsWorkTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPrincipalsResponseTypeDef = TypedDict(
-    "ListPrincipalsResponseTypeDef",
+ReplacePermissionAssociationsResponseTypeDef = TypedDict(
+    "ReplacePermissionAssociationsResponseTypeDef",
     {
-        "principals": List[PrincipalTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "replacePermissionAssociationsWork": ReplacePermissionAssociationsWorkTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceTypesResponseTypeDef = TypedDict(
     "ListResourceTypesResponseTypeDef",
     {
         "resourceTypes": List[ServiceNameAndResourceTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptResourceShareInvitationResponseTypeDef = TypedDict(
     "AcceptResourceShareInvitationResponseTypeDef",
     {
         "resourceShareInvitation": ResourceShareInvitationTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceShareInvitationsResponseTypeDef = TypedDict(
     "GetResourceShareInvitationsResponseTypeDef",
     {
         "resourceShareInvitations": List[ResourceShareInvitationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectResourceShareInvitationResponseTypeDef = TypedDict(
     "RejectResourceShareInvitationResponseTypeDef",
     {
         "resourceShareInvitation": ResourceShareInvitationTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePermissionVersionResponseTypeDef = TypedDict(
+    "CreatePermissionVersionResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionDetailTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetPermissionResponseTypeDef = TypedDict(
+    "GetPermissionResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePermissionResponseTypeDef = TypedDict(
+    "CreatePermissionResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionSummaryTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPermissionVersionsResponseTypeDef = TypedDict(
+    "ListPermissionVersionsResponseTypeDef",
+    {
+        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPermissionsResponseTypeDef = TypedDict(
+    "ListPermissionsResponseTypeDef",
+    {
+        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListResourceSharePermissionsResponseTypeDef = TypedDict(
+    "ListResourceSharePermissionsResponseTypeDef",
+    {
+        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PromotePermissionCreatedFromPolicyResponseTypeDef = TypedDict(
+    "PromotePermissionCreatedFromPolicyResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionSummaryTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResourceShareResponseTypeDef = TypedDict(
     "CreateResourceShareResponseTypeDef",
     {
         "resourceShare": ResourceShareTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceSharesResponseTypeDef = TypedDict(
     "GetResourceSharesResponseTypeDef",
     {
         "resourceShares": List[ResourceShareTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResourceShareResponseTypeDef = TypedDict(
     "UpdateResourceShareResponseTypeDef",
     {
         "resourceShare": ResourceShareTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram/type_defs.pyi` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram/type_defs.pyi`

 * *Files 22% similar despite different names*

```diff
@@ -12,14 +12,19 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    PermissionFeatureSetType,
+    PermissionStatusType,
+    PermissionTypeFilterType,
+    PermissionTypeType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceRegionScopeType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareFeatureSetType,
     ResourceShareInvitationStatusType,
@@ -30,75 +35,95 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptResourceShareInvitationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociateResourceSharePermissionRequestRequestTypeDef",
+    "AssociateResourceSharePermissionResponseTypeDef",
     "AssociateResourceShareRequestRequestTypeDef",
     "ResourceShareAssociationTypeDef",
+    "AssociatedPermissionTypeDef",
     "TagTypeDef",
+    "CreatePermissionVersionRequestRequestTypeDef",
+    "DeletePermissionRequestRequestTypeDef",
+    "DeletePermissionResponseTypeDef",
+    "DeletePermissionVersionRequestRequestTypeDef",
+    "DeletePermissionVersionResponseTypeDef",
     "DeleteResourceShareRequestRequestTypeDef",
+    "DeleteResourceShareResponseTypeDef",
     "DisassociateResourceSharePermissionRequestRequestTypeDef",
+    "DisassociateResourceSharePermissionResponseTypeDef",
     "DisassociateResourceShareRequestRequestTypeDef",
+    "EnableSharingWithAwsOrganizationResponseTypeDef",
     "GetPermissionRequestRequestTypeDef",
-    "ResourceSharePermissionDetailTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesRequestRequestTypeDef",
+    "GetResourcePoliciesResponseTypeDef",
+    "GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
     "GetResourceShareAssociationsRequestRequestTypeDef",
+    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
     "GetResourceShareInvitationsRequestRequestTypeDef",
     "TagFilterTypeDef",
     "ListPendingInvitationResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
+    "ListPermissionAssociationsRequestRequestTypeDef",
     "ListPermissionVersionsRequestRequestTypeDef",
-    "ResourceSharePermissionSummaryTypeDef",
     "ListPermissionsRequestRequestTypeDef",
+    "ListPrincipalsRequestListPrincipalsPaginateTypeDef",
     "ListPrincipalsRequestRequestTypeDef",
     "PrincipalTypeDef",
+    "ListReplacePermissionAssociationsWorkRequestRequestTypeDef",
+    "ReplacePermissionAssociationsWorkTypeDef",
     "ListResourceSharePermissionsRequestRequestTypeDef",
     "ListResourceTypesRequestRequestTypeDef",
     "ServiceNameAndResourceTypeTypeDef",
+    "ListResourcesRequestListResourcesPaginateTypeDef",
     "ListResourcesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "PromotePermissionCreatedFromPolicyRequestRequestTypeDef",
     "PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef",
+    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
     "RejectResourceShareInvitationRequestRequestTypeDef",
+    "ReplacePermissionAssociationsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SetDefaultPermissionVersionRequestRequestTypeDef",
+    "SetDefaultPermissionVersionResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateResourceShareRequestRequestTypeDef",
-    "AssociateResourceSharePermissionResponseTypeDef",
-    "DeleteResourceShareResponseTypeDef",
-    "DisassociateResourceSharePermissionResponseTypeDef",
-    "EnableSharingWithAwsOrganizationResponseTypeDef",
-    "GetResourcePoliciesResponseTypeDef",
-    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
     "AssociateResourceShareResponseTypeDef",
     "DisassociateResourceShareResponseTypeDef",
     "GetResourceShareAssociationsResponseTypeDef",
     "ResourceShareInvitationTypeDef",
+    "ListPermissionAssociationsResponseTypeDef",
+    "CreatePermissionRequestRequestTypeDef",
     "CreateResourceShareRequestRequestTypeDef",
+    "ResourceSharePermissionDetailTypeDef",
+    "ResourceSharePermissionSummaryTypeDef",
     "ResourceShareTypeDef",
     "TagResourceRequestRequestTypeDef",
-    "GetPermissionResponseTypeDef",
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    "GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
-    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
-    "ListPrincipalsRequestListPrincipalsPaginateTypeDef",
-    "ListResourcesRequestListResourcesPaginateTypeDef",
     "GetResourceSharesRequestGetResourceSharesPaginateTypeDef",
     "GetResourceSharesRequestRequestTypeDef",
     "ListPendingInvitationResourcesResponseTypeDef",
     "ListResourcesResponseTypeDef",
-    "ListPermissionVersionsResponseTypeDef",
-    "ListPermissionsResponseTypeDef",
-    "ListResourceSharePermissionsResponseTypeDef",
     "ListPrincipalsResponseTypeDef",
+    "ListReplacePermissionAssociationsWorkResponseTypeDef",
+    "ReplacePermissionAssociationsResponseTypeDef",
     "ListResourceTypesResponseTypeDef",
     "AcceptResourceShareInvitationResponseTypeDef",
     "GetResourceShareInvitationsResponseTypeDef",
     "RejectResourceShareInvitationResponseTypeDef",
+    "CreatePermissionVersionResponseTypeDef",
+    "GetPermissionResponseTypeDef",
+    "CreatePermissionResponseTypeDef",
+    "ListPermissionVersionsResponseTypeDef",
+    "ListPermissionsResponseTypeDef",
+    "ListResourceSharePermissionsResponseTypeDef",
+    "PromotePermissionCreatedFromPolicyResponseTypeDef",
     "CreateResourceShareResponseTypeDef",
     "GetResourceSharesResponseTypeDef",
     "UpdateResourceShareResponseTypeDef",
 )
 
 _RequiredAcceptResourceShareInvitationRequestRequestTypeDef = TypedDict(
     "_RequiredAcceptResourceShareInvitationRequestRequestTypeDef",
@@ -116,25 +141,14 @@
 
 class AcceptResourceShareInvitationRequestRequestTypeDef(
     _RequiredAcceptResourceShareInvitationRequestRequestTypeDef,
     _OptionalAcceptResourceShareInvitationRequestRequestTypeDef,
 ):
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
 _RequiredAssociateResourceSharePermissionRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateResourceSharePermissionRequestRequestTypeDef",
     {
         "resourceShareArn": str,
         "permissionArn": str,
     },
 )
@@ -150,14 +164,23 @@
 
 class AssociateResourceSharePermissionRequestRequestTypeDef(
     _RequiredAssociateResourceSharePermissionRequestRequestTypeDef,
     _OptionalAssociateResourceSharePermissionRequestRequestTypeDef,
 ):
     pass
 
+AssociateResourceSharePermissionResponseTypeDef = TypedDict(
+    "AssociateResourceSharePermissionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateResourceShareRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalAssociateResourceShareRequestRequestTypeDef = TypedDict(
@@ -188,23 +211,119 @@
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
         "external": bool,
     },
     total=False,
 )
 
+AssociatedPermissionTypeDef = TypedDict(
+    "AssociatedPermissionTypeDef",
+    {
+        "arn": str,
+        "permissionVersion": str,
+        "defaultVersion": bool,
+        "resourceType": str,
+        "status": str,
+        "featureSet": PermissionFeatureSetType,
+        "lastUpdatedTime": datetime,
+        "resourceShareArn": str,
+    },
+    total=False,
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
     total=False,
 )
 
+_RequiredCreatePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePermissionVersionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "policyTemplate": str,
+    },
+)
+_OptionalCreatePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePermissionVersionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class CreatePermissionVersionRequestRequestTypeDef(
+    _RequiredCreatePermissionVersionRequestRequestTypeDef,
+    _OptionalCreatePermissionVersionRequestRequestTypeDef,
+):
+    pass
+
+_RequiredDeletePermissionRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePermissionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+    },
+)
+_OptionalDeletePermissionRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePermissionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class DeletePermissionRequestRequestTypeDef(
+    _RequiredDeletePermissionRequestRequestTypeDef, _OptionalDeletePermissionRequestRequestTypeDef
+):
+    pass
+
+DeletePermissionResponseTypeDef = TypedDict(
+    "DeletePermissionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "permissionStatus": PermissionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDeletePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePermissionVersionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "permissionVersion": int,
+    },
+)
+_OptionalDeletePermissionVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePermissionVersionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class DeletePermissionVersionRequestRequestTypeDef(
+    _RequiredDeletePermissionVersionRequestRequestTypeDef,
+    _OptionalDeletePermissionVersionRequestRequestTypeDef,
+):
+    pass
+
+DeletePermissionVersionResponseTypeDef = TypedDict(
+    "DeletePermissionVersionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "permissionStatus": PermissionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourceShareRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalDeleteResourceShareRequestRequestTypeDef = TypedDict(
@@ -217,14 +336,23 @@
 
 class DeleteResourceShareRequestRequestTypeDef(
     _RequiredDeleteResourceShareRequestRequestTypeDef,
     _OptionalDeleteResourceShareRequestRequestTypeDef,
 ):
     pass
 
+DeleteResourceShareResponseTypeDef = TypedDict(
+    "DeleteResourceShareResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateResourceSharePermissionRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateResourceSharePermissionRequestRequestTypeDef",
     {
         "resourceShareArn": str,
         "permissionArn": str,
     },
 )
@@ -238,14 +366,23 @@
 
 class DisassociateResourceSharePermissionRequestRequestTypeDef(
     _RequiredDisassociateResourceSharePermissionRequestRequestTypeDef,
     _OptionalDisassociateResourceSharePermissionRequestRequestTypeDef,
 ):
     pass
 
+DisassociateResourceSharePermissionResponseTypeDef = TypedDict(
+    "DisassociateResourceSharePermissionResponseTypeDef",
+    {
+        "returnValue": bool,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateResourceShareRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalDisassociateResourceShareRequestRequestTypeDef = TypedDict(
@@ -260,14 +397,22 @@
 
 class DisassociateResourceShareRequestRequestTypeDef(
     _RequiredDisassociateResourceShareRequestRequestTypeDef,
     _OptionalDisassociateResourceShareRequestRequestTypeDef,
 ):
     pass
 
+EnableSharingWithAwsOrganizationResponseTypeDef = TypedDict(
+    "EnableSharingWithAwsOrganizationResponseTypeDef",
+    {
+        "returnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredGetPermissionRequestRequestTypeDef",
     {
         "permissionArn": str,
     },
 )
 _OptionalGetPermissionRequestRequestTypeDef = TypedDict(
@@ -279,40 +424,35 @@
 )
 
 class GetPermissionRequestRequestTypeDef(
     _RequiredGetPermissionRequestRequestTypeDef, _OptionalGetPermissionRequestRequestTypeDef
 ):
     pass
 
-ResourceSharePermissionDetailTypeDef = TypedDict(
-    "ResourceSharePermissionDetailTypeDef",
+_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     {
-        "arn": str,
-        "version": str,
-        "defaultVersion": bool,
-        "name": str,
-        "resourceType": str,
-        "permission": str,
-        "creationTime": datetime,
-        "lastUpdatedTime": datetime,
-        "isResourceTypeDefault": bool,
+        "resourceArns": Sequence[str],
     },
-    total=False,
 )
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "principal": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
+    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetResourcePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourcePoliciesRequestRequestTypeDef",
     {
         "resourceArns": Sequence[str],
     },
 )
 _OptionalGetResourcePoliciesRequestRequestTypeDef = TypedDict(
@@ -327,14 +467,47 @@
 
 class GetResourcePoliciesRequestRequestTypeDef(
     _RequiredGetResourcePoliciesRequestRequestTypeDef,
     _OptionalGetResourcePoliciesRequestRequestTypeDef,
 ):
     pass
 
+GetResourcePoliciesResponseTypeDef = TypedDict(
+    "GetResourcePoliciesResponseTypeDef",
+    {
+        "policies": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
+    {
+        "associationType": ResourceShareAssociationTypeType,
+    },
+)
+_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
+    {
+        "resourceShareArns": Sequence[str],
+        "resourceArn": str,
+        "principal": str,
+        "associationStatus": ResourceShareAssociationStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef(
+    _RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
+    _OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetResourceShareAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourceShareAssociationsRequestRequestTypeDef",
     {
         "associationType": ResourceShareAssociationTypeType,
     },
 )
 _OptionalGetResourceShareAssociationsRequestRequestTypeDef = TypedDict(
@@ -352,14 +525,24 @@
 
 class GetResourceShareAssociationsRequestRequestTypeDef(
     _RequiredGetResourceShareAssociationsRequestRequestTypeDef,
     _OptionalGetResourceShareAssociationsRequestRequestTypeDef,
 ):
     pass
 
+GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef = TypedDict(
+    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
+    {
+        "resourceShareInvitationArns": Sequence[str],
+        "resourceShareArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetResourceShareInvitationsRequestRequestTypeDef = TypedDict(
     "GetResourceShareInvitationsRequestRequestTypeDef",
     {
         "resourceShareInvitationArns": Sequence[str],
         "resourceShareArns": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -410,14 +593,29 @@
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
         "resourceRegionScope": ResourceRegionScopeType,
     },
     total=False,
 )
 
+ListPermissionAssociationsRequestRequestTypeDef = TypedDict(
+    "ListPermissionAssociationsRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "permissionVersion": int,
+        "associationStatus": ResourceShareAssociationStatusType,
+        "resourceType": str,
+        "featureSet": PermissionFeatureSetType,
+        "defaultVersion": bool,
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
 _RequiredListPermissionVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionVersionsRequestRequestTypeDef",
     {
         "permissionArn": str,
     },
 )
 _OptionalListPermissionVersionsRequestRequestTypeDef = TypedDict(
@@ -431,40 +629,49 @@
 
 class ListPermissionVersionsRequestRequestTypeDef(
     _RequiredListPermissionVersionsRequestRequestTypeDef,
     _OptionalListPermissionVersionsRequestRequestTypeDef,
 ):
     pass
 
-ResourceSharePermissionSummaryTypeDef = TypedDict(
-    "ResourceSharePermissionSummaryTypeDef",
+ListPermissionsRequestRequestTypeDef = TypedDict(
+    "ListPermissionsRequestRequestTypeDef",
     {
-        "arn": str,
-        "version": str,
-        "defaultVersion": bool,
-        "name": str,
         "resourceType": str,
-        "status": str,
-        "creationTime": datetime,
-        "lastUpdatedTime": datetime,
-        "isResourceTypeDefault": bool,
+        "nextToken": str,
+        "maxResults": int,
+        "permissionType": PermissionTypeFilterType,
     },
     total=False,
 )
 
-ListPermissionsRequestRequestTypeDef = TypedDict(
-    "ListPermissionsRequestRequestTypeDef",
+_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef",
+    {
+        "resourceOwner": ResourceOwnerType,
+    },
+)
+_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef",
     {
+        "resourceArn": str,
+        "principals": Sequence[str],
         "resourceType": str,
-        "nextToken": str,
-        "maxResults": int,
+        "resourceShareArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListPrincipalsRequestListPrincipalsPaginateTypeDef(
+    _RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef,
+    _OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPrincipalsRequestRequestTypeDef = TypedDict(
     "_RequiredListPrincipalsRequestRequestTypeDef",
     {
         "resourceOwner": ResourceOwnerType,
     },
 )
 _OptionalListPrincipalsRequestRequestTypeDef = TypedDict(
@@ -493,14 +700,41 @@
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
         "external": bool,
     },
     total=False,
 )
 
+ListReplacePermissionAssociationsWorkRequestRequestTypeDef = TypedDict(
+    "ListReplacePermissionAssociationsWorkRequestRequestTypeDef",
+    {
+        "workIds": Sequence[str],
+        "status": ReplacePermissionAssociationsWorkStatusType,
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+ReplacePermissionAssociationsWorkTypeDef = TypedDict(
+    "ReplacePermissionAssociationsWorkTypeDef",
+    {
+        "id": str,
+        "fromPermissionArn": str,
+        "fromPermissionVersion": str,
+        "toPermissionArn": str,
+        "toPermissionVersion": str,
+        "status": ReplacePermissionAssociationsWorkStatusType,
+        "statusMessage": str,
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+    },
+    total=False,
+)
+
 _RequiredListResourceSharePermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceSharePermissionsRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 _OptionalListResourceSharePermissionsRequestRequestTypeDef = TypedDict(
@@ -534,14 +768,39 @@
         "resourceType": str,
         "serviceName": str,
         "resourceRegionScope": ResourceRegionScopeType,
     },
     total=False,
 )
 
+_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "resourceOwner": ResourceOwnerType,
+    },
+)
+_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "principal": str,
+        "resourceType": str,
+        "resourceArns": Sequence[str],
+        "resourceShareArns": Sequence[str],
+        "resourceRegionScope": ResourceRegionScopeFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourcesRequestListResourcesPaginateTypeDef(
+    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
+    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesRequestRequestTypeDef",
     {
         "resourceOwner": ResourceOwnerType,
     },
 )
 _OptionalListResourcesRequestRequestTypeDef = TypedDict(
@@ -559,21 +818,60 @@
 )
 
 class ListResourcesRequestRequestTypeDef(
     _RequiredListResourcesRequestRequestTypeDef, _OptionalListResourcesRequestRequestTypeDef
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
+_RequiredPromotePermissionCreatedFromPolicyRequestRequestTypeDef = TypedDict(
+    "_RequiredPromotePermissionCreatedFromPolicyRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "name": str,
+    },
+)
+_OptionalPromotePermissionCreatedFromPolicyRequestRequestTypeDef = TypedDict(
+    "_OptionalPromotePermissionCreatedFromPolicyRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class PromotePermissionCreatedFromPolicyRequestRequestTypeDef(
+    _RequiredPromotePermissionCreatedFromPolicyRequestRequestTypeDef,
+    _OptionalPromotePermissionCreatedFromPolicyRequestRequestTypeDef,
+):
+    pass
+
 PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef = TypedDict(
     "PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef",
     {
         "resourceShareArn": str,
     },
 )
 
+PromoteResourceShareCreatedFromPolicyResponseTypeDef = TypedDict(
+    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
+    {
+        "returnValue": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRejectResourceShareInvitationRequestRequestTypeDef = TypedDict(
     "_RequiredRejectResourceShareInvitationRequestRequestTypeDef",
     {
         "resourceShareInvitationArn": str,
     },
 )
 _OptionalRejectResourceShareInvitationRequestRequestTypeDef = TypedDict(
@@ -586,120 +884,143 @@
 
 class RejectResourceShareInvitationRequestRequestTypeDef(
     _RequiredRejectResourceShareInvitationRequestRequestTypeDef,
     _OptionalRejectResourceShareInvitationRequestRequestTypeDef,
 ):
     pass
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceShareArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-_RequiredUpdateResourceShareRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateResourceShareRequestRequestTypeDef",
+_RequiredReplacePermissionAssociationsRequestRequestTypeDef = TypedDict(
+    "_RequiredReplacePermissionAssociationsRequestRequestTypeDef",
     {
-        "resourceShareArn": str,
+        "fromPermissionArn": str,
+        "toPermissionArn": str,
     },
 )
-_OptionalUpdateResourceShareRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateResourceShareRequestRequestTypeDef",
+_OptionalReplacePermissionAssociationsRequestRequestTypeDef = TypedDict(
+    "_OptionalReplacePermissionAssociationsRequestRequestTypeDef",
     {
-        "name": str,
-        "allowExternalPrincipals": bool,
+        "fromPermissionVersion": int,
         "clientToken": str,
     },
     total=False,
 )
 
-class UpdateResourceShareRequestRequestTypeDef(
-    _RequiredUpdateResourceShareRequestRequestTypeDef,
-    _OptionalUpdateResourceShareRequestRequestTypeDef,
+class ReplacePermissionAssociationsRequestRequestTypeDef(
+    _RequiredReplacePermissionAssociationsRequestRequestTypeDef,
+    _OptionalReplacePermissionAssociationsRequestRequestTypeDef,
 ):
     pass
 
-AssociateResourceSharePermissionResponseTypeDef = TypedDict(
-    "AssociateResourceSharePermissionResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "returnValue": bool,
-        "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-DeleteResourceShareResponseTypeDef = TypedDict(
-    "DeleteResourceShareResponseTypeDef",
+_RequiredSetDefaultPermissionVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredSetDefaultPermissionVersionRequestRequestTypeDef",
+    {
+        "permissionArn": str,
+        "permissionVersion": int,
+    },
+)
+_OptionalSetDefaultPermissionVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalSetDefaultPermissionVersionRequestRequestTypeDef",
     {
-        "returnValue": bool,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-DisassociateResourceSharePermissionResponseTypeDef = TypedDict(
-    "DisassociateResourceSharePermissionResponseTypeDef",
+class SetDefaultPermissionVersionRequestRequestTypeDef(
+    _RequiredSetDefaultPermissionVersionRequestRequestTypeDef,
+    _OptionalSetDefaultPermissionVersionRequestRequestTypeDef,
+):
+    pass
+
+SetDefaultPermissionVersionResponseTypeDef = TypedDict(
+    "SetDefaultPermissionVersionResponseTypeDef",
     {
         "returnValue": bool,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EnableSharingWithAwsOrganizationResponseTypeDef = TypedDict(
-    "EnableSharingWithAwsOrganizationResponseTypeDef",
+_RequiredUntagResourceRequestRequestTypeDef = TypedDict(
+    "_RequiredUntagResourceRequestRequestTypeDef",
     {
-        "returnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tagKeys": Sequence[str],
     },
 )
-
-GetResourcePoliciesResponseTypeDef = TypedDict(
-    "GetResourcePoliciesResponseTypeDef",
+_OptionalUntagResourceRequestRequestTypeDef = TypedDict(
+    "_OptionalUntagResourceRequestRequestTypeDef",
     {
-        "policies": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceShareArn": str,
+        "resourceArn": str,
     },
+    total=False,
 )
 
-PromoteResourceShareCreatedFromPolicyResponseTypeDef = TypedDict(
-    "PromoteResourceShareCreatedFromPolicyResponseTypeDef",
+class UntagResourceRequestRequestTypeDef(
+    _RequiredUntagResourceRequestRequestTypeDef, _OptionalUntagResourceRequestRequestTypeDef
+):
+    pass
+
+_RequiredUpdateResourceShareRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateResourceShareRequestRequestTypeDef",
     {
-        "returnValue": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceShareArn": str,
     },
 )
+_OptionalUpdateResourceShareRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateResourceShareRequestRequestTypeDef",
+    {
+        "name": str,
+        "allowExternalPrincipals": bool,
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class UpdateResourceShareRequestRequestTypeDef(
+    _RequiredUpdateResourceShareRequestRequestTypeDef,
+    _OptionalUpdateResourceShareRequestRequestTypeDef,
+):
+    pass
 
 AssociateResourceShareResponseTypeDef = TypedDict(
     "AssociateResourceShareResponseTypeDef",
     {
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateResourceShareResponseTypeDef = TypedDict(
     "DisassociateResourceShareResponseTypeDef",
     {
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceShareAssociationsResponseTypeDef = TypedDict(
     "GetResourceShareAssociationsResponseTypeDef",
     {
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceShareInvitationTypeDef = TypedDict(
     "ResourceShareInvitationTypeDef",
     {
         "resourceShareInvitationArn": str,
@@ -711,14 +1032,45 @@
         "status": ResourceShareInvitationStatusType,
         "resourceShareAssociations": List[ResourceShareAssociationTypeDef],
         "receiverArn": str,
     },
     total=False,
 )
 
+ListPermissionAssociationsResponseTypeDef = TypedDict(
+    "ListPermissionAssociationsResponseTypeDef",
+    {
+        "permissions": List[AssociatedPermissionTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreatePermissionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePermissionRequestRequestTypeDef",
+    {
+        "name": str,
+        "resourceType": str,
+        "policyTemplate": str,
+    },
+)
+_OptionalCreatePermissionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePermissionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreatePermissionRequestRequestTypeDef(
+    _RequiredCreatePermissionRequestRequestTypeDef, _OptionalCreatePermissionRequestRequestTypeDef
+):
+    pass
+
 _RequiredCreateResourceShareRequestRequestTypeDef = TypedDict(
     "_RequiredCreateResourceShareRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateResourceShareRequestRequestTypeDef = TypedDict(
@@ -736,148 +1088,87 @@
 
 class CreateResourceShareRequestRequestTypeDef(
     _RequiredCreateResourceShareRequestRequestTypeDef,
     _OptionalCreateResourceShareRequestRequestTypeDef,
 ):
     pass
 
-ResourceShareTypeDef = TypedDict(
-    "ResourceShareTypeDef",
+ResourceSharePermissionDetailTypeDef = TypedDict(
+    "ResourceSharePermissionDetailTypeDef",
     {
-        "resourceShareArn": str,
+        "arn": str,
+        "version": str,
+        "defaultVersion": bool,
         "name": str,
-        "owningAccountId": str,
-        "allowExternalPrincipals": bool,
-        "status": ResourceShareStatusType,
-        "statusMessage": str,
-        "tags": List[TagTypeDef],
+        "resourceType": str,
+        "permission": str,
         "creationTime": datetime,
         "lastUpdatedTime": datetime,
-        "featureSet": ResourceShareFeatureSetType,
-    },
-    total=False,
-)
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceShareArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-GetPermissionResponseTypeDef = TypedDict(
-    "GetPermissionResponseTypeDef",
-    {
-        "permission": ResourceSharePermissionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "resourceArns": Sequence[str],
-    },
-)
-_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "principal": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "isResourceTypeDefault": bool,
+        "permissionType": PermissionTypeType,
+        "featureSet": PermissionFeatureSetType,
+        "status": PermissionStatusType,
+        "tags": List[TagTypeDef],
     },
     total=False,
 )
 
-class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
-    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
-    {
-        "associationType": ResourceShareAssociationTypeType,
-    },
-)
-_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef",
+ResourceSharePermissionSummaryTypeDef = TypedDict(
+    "ResourceSharePermissionSummaryTypeDef",
     {
-        "resourceShareArns": Sequence[str],
-        "resourceArn": str,
-        "principal": str,
-        "associationStatus": ResourceShareAssociationStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "arn": str,
+        "version": str,
+        "defaultVersion": bool,
+        "name": str,
+        "resourceType": str,
+        "status": str,
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+        "isResourceTypeDefault": bool,
+        "permissionType": PermissionTypeType,
+        "featureSet": PermissionFeatureSetType,
+        "tags": List[TagTypeDef],
     },
     total=False,
 )
 
-class GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef(
-    _RequiredGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-    _OptionalGetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-):
-    pass
-
-GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef = TypedDict(
-    "GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef",
+ResourceShareTypeDef = TypedDict(
+    "ResourceShareTypeDef",
     {
-        "resourceShareInvitationArns": Sequence[str],
-        "resourceShareArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "resourceShareArn": str,
+        "name": str,
+        "owningAccountId": str,
+        "allowExternalPrincipals": bool,
+        "status": ResourceShareStatusType,
+        "statusMessage": str,
+        "tags": List[TagTypeDef],
+        "creationTime": datetime,
+        "lastUpdatedTime": datetime,
+        "featureSet": ResourceShareFeatureSetType,
     },
     total=False,
 )
 
-_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef",
+_RequiredTagResourceRequestRequestTypeDef = TypedDict(
+    "_RequiredTagResourceRequestRequestTypeDef",
     {
-        "resourceOwner": ResourceOwnerType,
+        "tags": Sequence[TagTypeDef],
     },
 )
-_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef",
+_OptionalTagResourceRequestRequestTypeDef = TypedDict(
+    "_OptionalTagResourceRequestRequestTypeDef",
     {
+        "resourceShareArn": str,
         "resourceArn": str,
-        "principals": Sequence[str],
-        "resourceType": str,
-        "resourceShareArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPrincipalsRequestListPrincipalsPaginateTypeDef(
-    _RequiredListPrincipalsRequestListPrincipalsPaginateTypeDef,
-    _OptionalListPrincipalsRequestListPrincipalsPaginateTypeDef,
-):
-    pass
-
-_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "resourceOwner": ResourceOwnerType,
-    },
-)
-_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "principal": str,
-        "resourceType": str,
-        "resourceArns": Sequence[str],
-        "resourceShareArns": Sequence[str],
-        "resourceRegionScope": ResourceRegionScopeFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-class ListResourcesRequestListResourcesPaginateTypeDef(
-    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
-    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+class TagResourceRequestRequestTypeDef(
+    _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
 _RequiredGetResourceSharesRequestGetResourceSharesPaginateTypeDef = TypedDict(
     "_RequiredGetResourceSharesRequestGetResourceSharesPaginateTypeDef",
     {
         "resourceOwner": ResourceOwnerType,
@@ -887,15 +1178,16 @@
     "_OptionalGetResourceSharesRequestGetResourceSharesPaginateTypeDef",
     {
         "resourceShareArns": Sequence[str],
         "resourceShareStatus": ResourceShareStatusType,
         "name": str,
         "tagFilters": Sequence[TagFilterTypeDef],
         "permissionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "permissionVersion": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetResourceSharesRequestGetResourceSharesPaginateTypeDef(
     _RequiredGetResourceSharesRequestGetResourceSharesPaginateTypeDef,
     _OptionalGetResourceSharesRequestGetResourceSharesPaginateTypeDef,
@@ -914,132 +1206,186 @@
         "resourceShareArns": Sequence[str],
         "resourceShareStatus": ResourceShareStatusType,
         "name": str,
         "tagFilters": Sequence[TagFilterTypeDef],
         "nextToken": str,
         "maxResults": int,
         "permissionArn": str,
+        "permissionVersion": int,
     },
     total=False,
 )
 
 class GetResourceSharesRequestRequestTypeDef(
     _RequiredGetResourceSharesRequestRequestTypeDef, _OptionalGetResourceSharesRequestRequestTypeDef
 ):
     pass
 
 ListPendingInvitationResourcesResponseTypeDef = TypedDict(
     "ListPendingInvitationResourcesResponseTypeDef",
     {
         "resources": List[ResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResponseTypeDef = TypedDict(
     "ListResourcesResponseTypeDef",
     {
         "resources": List[ResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPermissionVersionsResponseTypeDef = TypedDict(
-    "ListPermissionVersionsResponseTypeDef",
-    {
-        "permissions": List[ResourceSharePermissionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPermissionsResponseTypeDef = TypedDict(
-    "ListPermissionsResponseTypeDef",
+ListPrincipalsResponseTypeDef = TypedDict(
+    "ListPrincipalsResponseTypeDef",
     {
-        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "principals": List[PrincipalTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListResourceSharePermissionsResponseTypeDef = TypedDict(
-    "ListResourceSharePermissionsResponseTypeDef",
+ListReplacePermissionAssociationsWorkResponseTypeDef = TypedDict(
+    "ListReplacePermissionAssociationsWorkResponseTypeDef",
     {
-        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "replacePermissionAssociationsWorks": List[ReplacePermissionAssociationsWorkTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListPrincipalsResponseTypeDef = TypedDict(
-    "ListPrincipalsResponseTypeDef",
+ReplacePermissionAssociationsResponseTypeDef = TypedDict(
+    "ReplacePermissionAssociationsResponseTypeDef",
     {
-        "principals": List[PrincipalTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "replacePermissionAssociationsWork": ReplacePermissionAssociationsWorkTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceTypesResponseTypeDef = TypedDict(
     "ListResourceTypesResponseTypeDef",
     {
         "resourceTypes": List[ServiceNameAndResourceTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptResourceShareInvitationResponseTypeDef = TypedDict(
     "AcceptResourceShareInvitationResponseTypeDef",
     {
         "resourceShareInvitation": ResourceShareInvitationTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceShareInvitationsResponseTypeDef = TypedDict(
     "GetResourceShareInvitationsResponseTypeDef",
     {
         "resourceShareInvitations": List[ResourceShareInvitationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectResourceShareInvitationResponseTypeDef = TypedDict(
     "RejectResourceShareInvitationResponseTypeDef",
     {
         "resourceShareInvitation": ResourceShareInvitationTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePermissionVersionResponseTypeDef = TypedDict(
+    "CreatePermissionVersionResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionDetailTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetPermissionResponseTypeDef = TypedDict(
+    "GetPermissionResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePermissionResponseTypeDef = TypedDict(
+    "CreatePermissionResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionSummaryTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPermissionVersionsResponseTypeDef = TypedDict(
+    "ListPermissionVersionsResponseTypeDef",
+    {
+        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPermissionsResponseTypeDef = TypedDict(
+    "ListPermissionsResponseTypeDef",
+    {
+        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListResourceSharePermissionsResponseTypeDef = TypedDict(
+    "ListResourceSharePermissionsResponseTypeDef",
+    {
+        "permissions": List[ResourceSharePermissionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PromotePermissionCreatedFromPolicyResponseTypeDef = TypedDict(
+    "PromotePermissionCreatedFromPolicyResponseTypeDef",
+    {
+        "permission": ResourceSharePermissionSummaryTypeDef,
+        "clientToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResourceShareResponseTypeDef = TypedDict(
     "CreateResourceShareResponseTypeDef",
     {
         "resourceShare": ResourceShareTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceSharesResponseTypeDef = TypedDict(
     "GetResourceSharesResponseTypeDef",
     {
         "resourceShares": List[ResourceShareTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResourceShareResponseTypeDef = TypedDict(
     "UpdateResourceShareResponseTypeDef",
     {
         "resourceShare": ResourceShareTypeDef,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/PKG-INFO` & `types-aiobotocore-ram-2.5.1/README.md`

 * *Files 18% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-ram
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RAM 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore ram type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-ram"></a>
 
 # types-aiobotocore-ram
 
 [![PyPI - types-aiobotocore-ram](https://img.shields.io/pypi/v/types-aiobotocore-ram.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ram)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ram.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ram)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ram?color=blue)](https://pypistats.org/packages/types-aiobotocore-ram)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RAM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
+[aiobotocore.RAM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
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
 [types-aiobotocore-ram docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ram/).
 
 See how it helps to find and fix potential bugs:
 
@@ -316,14 +283,19 @@
 from types_aiobotocore_ram.literals import (
     GetResourcePoliciesPaginatorName,
     GetResourceShareAssociationsPaginatorName,
     GetResourceShareInvitationsPaginatorName,
     GetResourceSharesPaginatorName,
     ListPrincipalsPaginatorName,
     ListResourcesPaginatorName,
+    PermissionFeatureSetType,
+    PermissionStatusType,
+    PermissionTypeFilterType,
+    PermissionTypeType,
+    ReplacePermissionAssociationsWorkStatusType,
     ResourceOwnerType,
     ResourceRegionScopeFilterType,
     ResourceRegionScopeType,
     ResourceShareAssociationStatusType,
     ResourceShareAssociationTypeType,
     ResourceShareFeatureSetType,
     ResourceShareInvitationStatusType,
@@ -347,75 +319,95 @@
 
 `types_aiobotocore_ram.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ram.type_defs import (
     AcceptResourceShareInvitationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AssociateResourceSharePermissionRequestRequestTypeDef,
+    AssociateResourceSharePermissionResponseTypeDef,
     AssociateResourceShareRequestRequestTypeDef,
     ResourceShareAssociationTypeDef,
+    AssociatedPermissionTypeDef,
     TagTypeDef,
+    CreatePermissionVersionRequestRequestTypeDef,
+    DeletePermissionRequestRequestTypeDef,
+    DeletePermissionResponseTypeDef,
+    DeletePermissionVersionRequestRequestTypeDef,
+    DeletePermissionVersionResponseTypeDef,
     DeleteResourceShareRequestRequestTypeDef,
+    DeleteResourceShareResponseTypeDef,
     DisassociateResourceSharePermissionRequestRequestTypeDef,
+    DisassociateResourceSharePermissionResponseTypeDef,
     DisassociateResourceShareRequestRequestTypeDef,
+    EnableSharingWithAwsOrganizationResponseTypeDef,
     GetPermissionRequestRequestTypeDef,
-    ResourceSharePermissionDetailTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
+    GetResourcePoliciesResponseTypeDef,
+    GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
     GetResourceShareAssociationsRequestRequestTypeDef,
+    GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef,
     GetResourceShareInvitationsRequestRequestTypeDef,
     TagFilterTypeDef,
     ListPendingInvitationResourcesRequestRequestTypeDef,
     ResourceTypeDef,
+    ListPermissionAssociationsRequestRequestTypeDef,
     ListPermissionVersionsRequestRequestTypeDef,
-    ResourceSharePermissionSummaryTypeDef,
     ListPermissionsRequestRequestTypeDef,
+    ListPrincipalsRequestListPrincipalsPaginateTypeDef,
     ListPrincipalsRequestRequestTypeDef,
     PrincipalTypeDef,
+    ListReplacePermissionAssociationsWorkRequestRequestTypeDef,
+    ReplacePermissionAssociationsWorkTypeDef,
     ListResourceSharePermissionsRequestRequestTypeDef,
     ListResourceTypesRequestRequestTypeDef,
     ServiceNameAndResourceTypeTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PromotePermissionCreatedFromPolicyRequestRequestTypeDef,
     PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef,
+    PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     RejectResourceShareInvitationRequestRequestTypeDef,
+    ReplacePermissionAssociationsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SetDefaultPermissionVersionRequestRequestTypeDef,
+    SetDefaultPermissionVersionResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateResourceShareRequestRequestTypeDef,
-    AssociateResourceSharePermissionResponseTypeDef,
-    DeleteResourceShareResponseTypeDef,
-    DisassociateResourceSharePermissionResponseTypeDef,
-    EnableSharingWithAwsOrganizationResponseTypeDef,
-    GetResourcePoliciesResponseTypeDef,
-    PromoteResourceShareCreatedFromPolicyResponseTypeDef,
     AssociateResourceShareResponseTypeDef,
     DisassociateResourceShareResponseTypeDef,
     GetResourceShareAssociationsResponseTypeDef,
     ResourceShareInvitationTypeDef,
+    ListPermissionAssociationsResponseTypeDef,
+    CreatePermissionRequestRequestTypeDef,
     CreateResourceShareRequestRequestTypeDef,
+    ResourceSharePermissionDetailTypeDef,
+    ResourceSharePermissionSummaryTypeDef,
     ResourceShareTypeDef,
     TagResourceRequestRequestTypeDef,
-    GetPermissionResponseTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    GetResourceShareAssociationsRequestGetResourceShareAssociationsPaginateTypeDef,
-    GetResourceShareInvitationsRequestGetResourceShareInvitationsPaginateTypeDef,
-    ListPrincipalsRequestListPrincipalsPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
     GetResourceSharesRequestGetResourceSharesPaginateTypeDef,
     GetResourceSharesRequestRequestTypeDef,
     ListPendingInvitationResourcesResponseTypeDef,
     ListResourcesResponseTypeDef,
-    ListPermissionVersionsResponseTypeDef,
-    ListPermissionsResponseTypeDef,
-    ListResourceSharePermissionsResponseTypeDef,
     ListPrincipalsResponseTypeDef,
+    ListReplacePermissionAssociationsWorkResponseTypeDef,
+    ReplacePermissionAssociationsResponseTypeDef,
     ListResourceTypesResponseTypeDef,
     AcceptResourceShareInvitationResponseTypeDef,
     GetResourceShareInvitationsResponseTypeDef,
     RejectResourceShareInvitationResponseTypeDef,
+    CreatePermissionVersionResponseTypeDef,
+    GetPermissionResponseTypeDef,
+    CreatePermissionResponseTypeDef,
+    ListPermissionVersionsResponseTypeDef,
+    ListPermissionsResponseTypeDef,
+    ListResourceSharePermissionsResponseTypeDef,
+    PromotePermissionCreatedFromPolicyResponseTypeDef,
     CreateResourceShareResponseTypeDef,
     GetResourceSharesResponseTypeDef,
     UpdateResourceShareResponseTypeDef,
 )
 
 
 def get_structure() -> AcceptResourceShareInvitationRequestRequestTypeDef:
@@ -425,43 +417,43 @@
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

### Comparing `types-aiobotocore-ram-2.5.0.post1/types_aiobotocore_ram.egg-info/SOURCES.txt` & `types-aiobotocore-ram-2.5.1/types_aiobotocore_ram.egg-info/SOURCES.txt`

 * *Files identical despite different names*

