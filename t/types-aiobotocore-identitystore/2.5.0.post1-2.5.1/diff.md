# Comparing `tmp/types-aiobotocore-identitystore-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-identitystore-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-identitystore-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-identitystore-2.5.1.tar", last modified: Wed Jun 28 01:43:35 2023, max compression
```

## Comparing `types-aiobotocore-identitystore-2.5.0.post1.tar` & `types-aiobotocore-identitystore-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.015270 types-aiobotocore-identitystore-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15656 2023-03-11 12:26:44.015270 types-aiobotocore-identitystore-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14061 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.015270 types-aiobotocore-identitystore-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:15:45.000000 types-aiobotocore-identitystore-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.015270 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/
--rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1368 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18850 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18818 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8377 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8375 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5985 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5978 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19258 2023-03-11 12:15:48.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19229 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:46.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.015270 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15656 2023-03-11 12:26:43.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:26:43.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:43.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:43.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:43.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:43.000000 types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.658148 types-aiobotocore-identitystore-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15654 2023-06-28 01:43:35.658148 types-aiobotocore-identitystore-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14065 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:35.658148 types-aiobotocore-identitystore-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.658148 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/
+-rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1368 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18843 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18811 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8586 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8584 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5905 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5899 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19294 2023-06-28 01:32:23.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19265 2023-06-28 01:32:23.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:22.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.658148 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15654 2023-06-28 01:43:35.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:35.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:35.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:35.000000 types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/LICENSE` & `types-aiobotocore-identitystore-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/PKG-INFO` & `types-aiobotocore-identitystore-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-identitystore
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IdentityStore 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IdentityStore 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-identitystore"></a>
 
 # types-aiobotocore-identitystore
 
 [![PyPI - types-aiobotocore-identitystore](https://img.shields.io/pypi/v/types-aiobotocore-identitystore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-identitystore)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-identitystore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-identitystore)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-identitystore?color=blue)](https://pypistats.org/packages/types-aiobotocore-identitystore)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IdentityStore 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
+[aiobotocore.IdentityStore 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
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
 [types-aiobotocore-identitystore docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,55 +334,55 @@
 ```python
 from types_aiobotocore_identitystore.type_defs import (
     AddressTypeDef,
     ExternalIdTypeDef,
     UniqueAttributeTypeDef,
     AttributeOperationTypeDef,
     MemberIdTypeDef,
-    ResponseMetadataTypeDef,
+    CreateGroupMembershipResponseTypeDef,
     CreateGroupRequestRequestTypeDef,
+    CreateGroupResponseTypeDef,
     EmailTypeDef,
     NameTypeDef,
     PhoneNumberTypeDef,
+    CreateUserResponseTypeDef,
     DeleteGroupMembershipRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeGroupMembershipRequestRequestTypeDef,
     DescribeGroupRequestRequestTypeDef,
     DescribeUserRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
+    GetGroupIdResponseTypeDef,
+    GetGroupMembershipIdResponseTypeDef,
+    GetUserIdResponseTypeDef,
+    ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
     ListGroupMembershipsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeGroupResponseTypeDef,
     GroupTypeDef,
     AlternateIdentifierTypeDef,
     UpdateGroupRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     CreateGroupMembershipRequestRequestTypeDef,
+    DescribeGroupMembershipResponseTypeDef,
     GetGroupMembershipIdRequestRequestTypeDef,
     GroupMembershipExistenceResultTypeDef,
     GroupMembershipTypeDef,
     IsMemberInGroupsRequestRequestTypeDef,
+    ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
     ListGroupMembershipsForMemberRequestRequestTypeDef,
-    CreateGroupMembershipResponseTypeDef,
-    CreateGroupResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DescribeGroupMembershipResponseTypeDef,
-    DescribeGroupResponseTypeDef,
-    GetGroupIdResponseTypeDef,
-    GetGroupMembershipIdResponseTypeDef,
-    GetUserIdResponseTypeDef,
     CreateUserRequestRequestTypeDef,
     DescribeUserResponseTypeDef,
     UserTypeDef,
-    ListGroupsRequestRequestTypeDef,
-    ListUsersRequestRequestTypeDef,
-    ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-    ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
     ListGroupsRequestListGroupsPaginateTypeDef,
+    ListGroupsRequestRequestTypeDef,
     ListUsersRequestListUsersPaginateTypeDef,
+    ListUsersRequestRequestTypeDef,
     ListGroupsResponseTypeDef,
     GetGroupIdRequestRequestTypeDef,
     GetUserIdRequestRequestTypeDef,
     IsMemberInGroupsResponseTypeDef,
     ListGroupMembershipsForMemberResponseTypeDef,
     ListGroupMembershipsResponseTypeDef,
     ListUsersResponseTypeDef,
@@ -396,43 +396,43 @@
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/README.md` & `types-aiobotocore-identitystore-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-identitystore"></a>
 
 # types-aiobotocore-identitystore
 
 [![PyPI - types-aiobotocore-identitystore](https://img.shields.io/pypi/v/types-aiobotocore-identitystore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-identitystore)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-identitystore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-identitystore)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-identitystore?color=blue)](https://pypistats.org/packages/types-aiobotocore-identitystore)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IdentityStore 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
+[aiobotocore.IdentityStore 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
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
 [types-aiobotocore-identitystore docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/).
 
 See how it helps to find and fix potential bugs:
 
@@ -301,55 +301,55 @@
 ```python
 from types_aiobotocore_identitystore.type_defs import (
     AddressTypeDef,
     ExternalIdTypeDef,
     UniqueAttributeTypeDef,
     AttributeOperationTypeDef,
     MemberIdTypeDef,
-    ResponseMetadataTypeDef,
+    CreateGroupMembershipResponseTypeDef,
     CreateGroupRequestRequestTypeDef,
+    CreateGroupResponseTypeDef,
     EmailTypeDef,
     NameTypeDef,
     PhoneNumberTypeDef,
+    CreateUserResponseTypeDef,
     DeleteGroupMembershipRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeGroupMembershipRequestRequestTypeDef,
     DescribeGroupRequestRequestTypeDef,
     DescribeUserRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
+    GetGroupIdResponseTypeDef,
+    GetGroupMembershipIdResponseTypeDef,
+    GetUserIdResponseTypeDef,
+    ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
     ListGroupMembershipsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeGroupResponseTypeDef,
     GroupTypeDef,
     AlternateIdentifierTypeDef,
     UpdateGroupRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     CreateGroupMembershipRequestRequestTypeDef,
+    DescribeGroupMembershipResponseTypeDef,
     GetGroupMembershipIdRequestRequestTypeDef,
     GroupMembershipExistenceResultTypeDef,
     GroupMembershipTypeDef,
     IsMemberInGroupsRequestRequestTypeDef,
+    ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
     ListGroupMembershipsForMemberRequestRequestTypeDef,
-    CreateGroupMembershipResponseTypeDef,
-    CreateGroupResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DescribeGroupMembershipResponseTypeDef,
-    DescribeGroupResponseTypeDef,
-    GetGroupIdResponseTypeDef,
-    GetGroupMembershipIdResponseTypeDef,
-    GetUserIdResponseTypeDef,
     CreateUserRequestRequestTypeDef,
     DescribeUserResponseTypeDef,
     UserTypeDef,
-    ListGroupsRequestRequestTypeDef,
-    ListUsersRequestRequestTypeDef,
-    ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-    ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
     ListGroupsRequestListGroupsPaginateTypeDef,
+    ListGroupsRequestRequestTypeDef,
     ListUsersRequestListUsersPaginateTypeDef,
+    ListUsersRequestRequestTypeDef,
     ListGroupsResponseTypeDef,
     GetGroupIdRequestRequestTypeDef,
     GetUserIdRequestRequestTypeDef,
     IsMemberInGroupsResponseTypeDef,
     ListGroupMembershipsForMemberResponseTypeDef,
     ListGroupMembershipsResponseTypeDef,
     ListUsersResponseTypeDef,
@@ -363,43 +363,43 @@
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/setup.py` & `types-aiobotocore-identitystore-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-identitystore.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-identitystore",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_identitystore"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IdentityStore 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IdentityStore 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/"
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/__init__.py` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/__init__.pyi` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/__main__.py` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IdentityStore 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IdentityStore 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore\nOther"
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/client.py` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -147,41 +147,41 @@
         UserType: str = ...,
         Title: str = ...,
         PreferredLanguage: str = ...,
         Locale: str = ...,
         Timezone: str = ...
     ) -> CreateUserResponseTypeDef:
         """
-        Creates a new user within the specified identity store.
+        Creates a user within the specified identity store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.create_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#create_user)
         """
 
     async def delete_group(self, *, IdentityStoreId: str, GroupId: str) -> Dict[str, Any]:
         """
-        Delete a group within an identity store given `GroupId` .
+        Delete a group within an identity store given `GroupId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.delete_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#delete_group)
         """
 
     async def delete_group_membership(
         self, *, IdentityStoreId: str, MembershipId: str
     ) -> Dict[str, Any]:
         """
-        Delete a membership within a group given `MembershipId` .
+        Delete a membership within a group given `MembershipId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.delete_group_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#delete_group_membership)
         """
 
     async def delete_user(self, *, IdentityStoreId: str, UserId: str) -> Dict[str, Any]:
         """
-        Deletes a user within an identity store given `UserId` .
+        Deletes a user within an identity store given `UserId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.delete_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#delete_user)
         """
 
     async def describe_group(
         self, *, IdentityStoreId: str, GroupId: str
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/client.pyi` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -138,38 +138,38 @@
         UserType: str = ...,
         Title: str = ...,
         PreferredLanguage: str = ...,
         Locale: str = ...,
         Timezone: str = ...
     ) -> CreateUserResponseTypeDef:
         """
-        Creates a new user within the specified identity store.
+        Creates a user within the specified identity store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.create_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#create_user)
         """
     async def delete_group(self, *, IdentityStoreId: str, GroupId: str) -> Dict[str, Any]:
         """
-        Delete a group within an identity store given `GroupId` .
+        Delete a group within an identity store given `GroupId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.delete_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#delete_group)
         """
     async def delete_group_membership(
         self, *, IdentityStoreId: str, MembershipId: str
     ) -> Dict[str, Any]:
         """
-        Delete a membership within a group given `MembershipId` .
+        Delete a membership within a group given `MembershipId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.delete_group_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#delete_group_membership)
         """
     async def delete_user(self, *, IdentityStoreId: str, UserId: str) -> Dict[str, Any]:
         """
-        Deletes a user within an identity store given `UserId` .
+        Deletes a user within an identity store given `UserId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Client.delete_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/client/#delete_user)
         """
     async def describe_group(
         self, *, IdentityStoreId: str, GroupId: str
     ) -> DescribeGroupResponseTypeDef:
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/literals.py` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/literals.pyi` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -93,14 +93,15 @@
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
@@ -179,14 +180,15 @@
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
@@ -197,14 +199,15 @@
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
@@ -240,14 +243,15 @@
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
@@ -266,16 +270,19 @@
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
@@ -359,15 +366,17 @@
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/paginator.py` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -22,36 +22,29 @@
 
         list_group_memberships_paginator: ListGroupMembershipsPaginator = client.get_paginator("list_group_memberships")
         list_group_memberships_for_member_paginator: ListGroupMembershipsForMemberPaginator = client.get_paginator("list_group_memberships_for_member")
         list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListGroupMembershipsForMemberResponseTypeDef,
     ListGroupMembershipsResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListUsersResponseTypeDef,
     MemberIdTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListGroupMembershipsPaginator",
     "ListGroupMembershipsForMemberPaginator",
     "ListGroupsPaginator",
     "ListUsersPaginator",
 )
 
@@ -69,15 +62,19 @@
 class ListGroupMembershipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroupMemberships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupmembershipspaginator)
     """
 
     def paginate(
-        self, *, IdentityStoreId: str, GroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        IdentityStoreId: str,
+        GroupId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupMembershipsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroupMemberships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupmembershipspaginator)
         """
 
 
@@ -88,15 +85,15 @@
     """
 
     def paginate(
         self,
         *,
         IdentityStoreId: str,
         MemberId: MemberIdTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupMembershipsForMemberResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroupMembershipsForMember.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupmembershipsformemberpaginator)
         """
 
 
@@ -107,15 +104,15 @@
     """
 
     def paginate(
         self,
         *,
         IdentityStoreId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupspaginator)
         """
 
 
@@ -126,13 +123,13 @@
     """
 
     def paginate(
         self,
         *,
         IdentityStoreId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/paginator.pyi` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -22,35 +22,29 @@
 
         list_group_memberships_paginator: ListGroupMembershipsPaginator = client.get_paginator("list_group_memberships")
         list_group_memberships_for_member_paginator: ListGroupMembershipsForMemberPaginator = client.get_paginator("list_group_memberships_for_member")
         list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListGroupMembershipsForMemberResponseTypeDef,
     ListGroupMembershipsResponseTypeDef,
     ListGroupsResponseTypeDef,
     ListUsersResponseTypeDef,
     MemberIdTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListGroupMembershipsPaginator",
     "ListGroupMembershipsForMemberPaginator",
     "ListGroupsPaginator",
     "ListUsersPaginator",
 )
 
@@ -65,15 +59,19 @@
 class ListGroupMembershipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroupMemberships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupmembershipspaginator)
     """
 
     def paginate(
-        self, *, IdentityStoreId: str, GroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        IdentityStoreId: str,
+        GroupId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupMembershipsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroupMemberships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupmembershipspaginator)
         """
 
 class ListGroupMembershipsForMemberPaginator(AioPaginator):
@@ -83,15 +81,15 @@
     """
 
     def paginate(
         self,
         *,
         IdentityStoreId: str,
         MemberId: MemberIdTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupMembershipsForMemberResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroupMembershipsForMember.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupmembershipsformemberpaginator)
         """
 
 class ListGroupsPaginator(AioPaginator):
@@ -101,15 +99,15 @@
     """
 
     def paginate(
         self,
         *,
         IdentityStoreId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listgroupspaginator)
         """
 
 class ListUsersPaginator(AioPaginator):
@@ -119,13 +117,13 @@
     """
 
     def paginate(
         self,
         *,
         IdentityStoreId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/type_defs.py` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,55 +22,55 @@
 
 __all__ = (
     "AddressTypeDef",
     "ExternalIdTypeDef",
     "UniqueAttributeTypeDef",
     "AttributeOperationTypeDef",
     "MemberIdTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateGroupMembershipResponseTypeDef",
     "CreateGroupRequestRequestTypeDef",
+    "CreateGroupResponseTypeDef",
     "EmailTypeDef",
     "NameTypeDef",
     "PhoneNumberTypeDef",
+    "CreateUserResponseTypeDef",
     "DeleteGroupMembershipRequestRequestTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DescribeGroupMembershipRequestRequestTypeDef",
     "DescribeGroupRequestRequestTypeDef",
     "DescribeUserRequestRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetGroupIdResponseTypeDef",
+    "GetGroupMembershipIdResponseTypeDef",
+    "GetUserIdResponseTypeDef",
+    "ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
     "ListGroupMembershipsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "DescribeGroupResponseTypeDef",
     "GroupTypeDef",
     "AlternateIdentifierTypeDef",
     "UpdateGroupRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "CreateGroupMembershipRequestRequestTypeDef",
+    "DescribeGroupMembershipResponseTypeDef",
     "GetGroupMembershipIdRequestRequestTypeDef",
     "GroupMembershipExistenceResultTypeDef",
     "GroupMembershipTypeDef",
     "IsMemberInGroupsRequestRequestTypeDef",
+    "ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
     "ListGroupMembershipsForMemberRequestRequestTypeDef",
-    "CreateGroupMembershipResponseTypeDef",
-    "CreateGroupResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "DescribeGroupMembershipResponseTypeDef",
-    "DescribeGroupResponseTypeDef",
-    "GetGroupIdResponseTypeDef",
-    "GetGroupMembershipIdResponseTypeDef",
-    "GetUserIdResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
     "DescribeUserResponseTypeDef",
     "UserTypeDef",
-    "ListGroupsRequestRequestTypeDef",
-    "ListUsersRequestRequestTypeDef",
-    "ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
-    "ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
     "ListGroupsRequestListGroupsPaginateTypeDef",
+    "ListGroupsRequestRequestTypeDef",
     "ListUsersRequestListUsersPaginateTypeDef",
+    "ListUsersRequestRequestTypeDef",
     "ListGroupsResponseTypeDef",
     "GetGroupIdRequestRequestTypeDef",
     "GetUserIdRequestRequestTypeDef",
     "IsMemberInGroupsResponseTypeDef",
     "ListGroupMembershipsForMemberResponseTypeDef",
     "ListGroupMembershipsResponseTypeDef",
     "ListUsersResponseTypeDef",
@@ -132,22 +132,20 @@
     "MemberIdTypeDef",
     {
         "UserId": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateGroupMembershipResponseTypeDef = TypedDict(
+    "CreateGroupMembershipResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "MembershipId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateGroupRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
@@ -165,14 +163,23 @@
 
 class CreateGroupRequestRequestTypeDef(
     _RequiredCreateGroupRequestRequestTypeDef, _OptionalCreateGroupRequestRequestTypeDef
 ):
     pass
 
 
+CreateGroupResponseTypeDef = TypedDict(
+    "CreateGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EmailTypeDef = TypedDict(
     "EmailTypeDef",
     {
         "Value": str,
         "Type": str,
         "Primary": bool,
     },
@@ -198,14 +205,23 @@
         "Value": str,
         "Type": str,
         "Primary": bool,
     },
     total=False,
 )
 
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "UserId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteGroupMembershipRequestRequestTypeDef = TypedDict(
     "DeleteGroupMembershipRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "MembershipId": str,
     },
 )
@@ -254,24 +270,64 @@
     "FilterTypeDef",
     {
         "AttributePath": str,
         "AttributeValue": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetGroupIdResponseTypeDef = TypedDict(
+    "GetGroupIdResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "GroupId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetGroupMembershipIdResponseTypeDef = TypedDict(
+    "GetGroupMembershipIdResponseTypeDef",
+    {
+        "MembershipId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetUserIdResponseTypeDef = TypedDict(
+    "GetUserIdResponseTypeDef",
+    {
+        "UserId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
+    "_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
+    {
+        "IdentityStoreId": str,
+        "GroupId": str,
+    },
+)
+_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
+    "_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef(
+    _RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
+    _OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGroupMembershipsRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupMembershipsRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "GroupId": str,
     },
 )
@@ -288,14 +344,47 @@
 class ListGroupMembershipsRequestRequestTypeDef(
     _RequiredListGroupMembershipsRequestRequestTypeDef,
     _OptionalListGroupMembershipsRequestRequestTypeDef,
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
+DescribeGroupResponseTypeDef = TypedDict(
+    "DescribeGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "DisplayName": str,
+        "ExternalIds": List[ExternalIdTypeDef],
+        "Description": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGroupTypeDef = TypedDict(
     "_RequiredGroupTypeDef",
     {
         "GroupId": str,
         "IdentityStoreId": str,
     },
 )
@@ -346,14 +435,25 @@
     {
         "IdentityStoreId": str,
         "GroupId": str,
         "MemberId": MemberIdTypeDef,
     },
 )
 
+DescribeGroupMembershipResponseTypeDef = TypedDict(
+    "DescribeGroupMembershipResponseTypeDef",
+    {
+        "IdentityStoreId": str,
+        "MembershipId": str,
+        "GroupId": str,
+        "MemberId": MemberIdTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetGroupMembershipIdRequestRequestTypeDef = TypedDict(
     "GetGroupMembershipIdRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "GroupId": str,
         "MemberId": MemberIdTypeDef,
     },
@@ -395,14 +495,41 @@
     {
         "IdentityStoreId": str,
         "MemberId": MemberIdTypeDef,
         "GroupIds": Sequence[str],
     },
 )
 
+_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
+        {
+            "IdentityStoreId": str,
+            "MemberId": MemberIdTypeDef,
+        },
+    )
+)
+_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef(
+    _RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
+    _OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGroupMembershipsForMemberRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupMembershipsForMemberRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "MemberId": MemberIdTypeDef,
     },
 )
@@ -419,91 +546,14 @@
 class ListGroupMembershipsForMemberRequestRequestTypeDef(
     _RequiredListGroupMembershipsForMemberRequestRequestTypeDef,
     _OptionalListGroupMembershipsForMemberRequestRequestTypeDef,
 ):
     pass
 
 
-CreateGroupMembershipResponseTypeDef = TypedDict(
-    "CreateGroupMembershipResponseTypeDef",
-    {
-        "MembershipId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGroupResponseTypeDef = TypedDict(
-    "CreateGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "UserId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGroupMembershipResponseTypeDef = TypedDict(
-    "DescribeGroupMembershipResponseTypeDef",
-    {
-        "IdentityStoreId": str,
-        "MembershipId": str,
-        "GroupId": str,
-        "MemberId": MemberIdTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGroupResponseTypeDef = TypedDict(
-    "DescribeGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "DisplayName": str,
-        "ExternalIds": List[ExternalIdTypeDef],
-        "Description": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGroupIdResponseTypeDef = TypedDict(
-    "GetGroupIdResponseTypeDef",
-    {
-        "GroupId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGroupMembershipIdResponseTypeDef = TypedDict(
-    "GetGroupMembershipIdResponseTypeDef",
-    {
-        "MembershipId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUserIdResponseTypeDef = TypedDict(
-    "GetUserIdResponseTypeDef",
-    {
-        "UserId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
 _OptionalCreateUserRequestRequestTypeDef = TypedDict(
@@ -548,15 +598,15 @@
         "PhoneNumbers": List[PhoneNumberTypeDef],
         "UserType": str,
         "Title": str,
         "PreferredLanguage": str,
         "Locale": str,
         "Timezone": str,
         "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUserTypeDef = TypedDict(
     "_RequiredUserTypeDef",
     {
         "UserId": str,
@@ -585,162 +635,112 @@
 )
 
 
 class UserTypeDef(_RequiredUserTypeDef, _OptionalUserTypeDef):
     pass
 
 
-_RequiredListGroupsRequestRequestTypeDef = TypedDict(
-    "_RequiredListGroupsRequestRequestTypeDef",
+_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListGroupsRequestRequestTypeDef = TypedDict(
-    "_OptionalListGroupsRequestRequestTypeDef",
+_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
-class ListGroupsRequestRequestTypeDef(
-    _RequiredListGroupsRequestRequestTypeDef, _OptionalListGroupsRequestRequestTypeDef
+class ListGroupsRequestListGroupsPaginateTypeDef(
+    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
+    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListUsersRequestRequestTypeDef = TypedDict(
-    "_RequiredListUsersRequestRequestTypeDef",
+_RequiredListGroupsRequestRequestTypeDef = TypedDict(
+    "_RequiredListGroupsRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListUsersRequestRequestTypeDef = TypedDict(
-    "_OptionalListUsersRequestRequestTypeDef",
+_OptionalListGroupsRequestRequestTypeDef = TypedDict(
+    "_OptionalListGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
 
-class ListUsersRequestRequestTypeDef(
-    _RequiredListUsersRequestRequestTypeDef, _OptionalListUsersRequestRequestTypeDef
-):
-    pass
-
-
-_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
-        {
-            "IdentityStoreId": str,
-            "MemberId": MemberIdTypeDef,
-        },
-    )
-)
-_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef(
-    _RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-    _OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
-    "_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
-    {
-        "IdentityStoreId": str,
-        "GroupId": str,
-    },
-)
-_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
-    "_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef(
-    _RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
-    _OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
+class ListGroupsRequestRequestTypeDef(
+    _RequiredListGroupsRequestRequestTypeDef, _OptionalListGroupsRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
-class ListGroupsRequestListGroupsPaginateTypeDef(
-    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
-    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+_RequiredListUsersRequestRequestTypeDef = TypedDict(
+    "_RequiredListUsersRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+_OptionalListUsersRequestRequestTypeDef = TypedDict(
+    "_OptionalListUsersRequestRequestTypeDef",
     {
+        "MaxResults": int,
+        "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
 
-class ListUsersRequestListUsersPaginateTypeDef(
-    _RequiredListUsersRequestListUsersPaginateTypeDef,
-    _OptionalListUsersRequestListUsersPaginateTypeDef,
+class ListUsersRequestRequestTypeDef(
+    _RequiredListUsersRequestRequestTypeDef, _OptionalListUsersRequestRequestTypeDef
 ):
     pass
 
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupIdRequestRequestTypeDef = TypedDict(
     "GetGroupIdRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
@@ -756,37 +756,37 @@
     },
 )
 
 IsMemberInGroupsResponseTypeDef = TypedDict(
     "IsMemberInGroupsResponseTypeDef",
     {
         "Results": List[GroupMembershipExistenceResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupMembershipsForMemberResponseTypeDef = TypedDict(
     "ListGroupMembershipsForMemberResponseTypeDef",
     {
         "GroupMemberships": List[GroupMembershipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupMembershipsResponseTypeDef = TypedDict(
     "ListGroupMembershipsResponseTypeDef",
     {
         "GroupMemberships": List[GroupMembershipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore/type_defs.pyi` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -21,55 +21,55 @@
 
 __all__ = (
     "AddressTypeDef",
     "ExternalIdTypeDef",
     "UniqueAttributeTypeDef",
     "AttributeOperationTypeDef",
     "MemberIdTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateGroupMembershipResponseTypeDef",
     "CreateGroupRequestRequestTypeDef",
+    "CreateGroupResponseTypeDef",
     "EmailTypeDef",
     "NameTypeDef",
     "PhoneNumberTypeDef",
+    "CreateUserResponseTypeDef",
     "DeleteGroupMembershipRequestRequestTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DescribeGroupMembershipRequestRequestTypeDef",
     "DescribeGroupRequestRequestTypeDef",
     "DescribeUserRequestRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetGroupIdResponseTypeDef",
+    "GetGroupMembershipIdResponseTypeDef",
+    "GetUserIdResponseTypeDef",
+    "ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
     "ListGroupMembershipsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "DescribeGroupResponseTypeDef",
     "GroupTypeDef",
     "AlternateIdentifierTypeDef",
     "UpdateGroupRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "CreateGroupMembershipRequestRequestTypeDef",
+    "DescribeGroupMembershipResponseTypeDef",
     "GetGroupMembershipIdRequestRequestTypeDef",
     "GroupMembershipExistenceResultTypeDef",
     "GroupMembershipTypeDef",
     "IsMemberInGroupsRequestRequestTypeDef",
+    "ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
     "ListGroupMembershipsForMemberRequestRequestTypeDef",
-    "CreateGroupMembershipResponseTypeDef",
-    "CreateGroupResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "DescribeGroupMembershipResponseTypeDef",
-    "DescribeGroupResponseTypeDef",
-    "GetGroupIdResponseTypeDef",
-    "GetGroupMembershipIdResponseTypeDef",
-    "GetUserIdResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
     "DescribeUserResponseTypeDef",
     "UserTypeDef",
-    "ListGroupsRequestRequestTypeDef",
-    "ListUsersRequestRequestTypeDef",
-    "ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
-    "ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
     "ListGroupsRequestListGroupsPaginateTypeDef",
+    "ListGroupsRequestRequestTypeDef",
     "ListUsersRequestListUsersPaginateTypeDef",
+    "ListUsersRequestRequestTypeDef",
     "ListGroupsResponseTypeDef",
     "GetGroupIdRequestRequestTypeDef",
     "GetUserIdRequestRequestTypeDef",
     "IsMemberInGroupsResponseTypeDef",
     "ListGroupMembershipsForMemberResponseTypeDef",
     "ListGroupMembershipsResponseTypeDef",
     "ListUsersResponseTypeDef",
@@ -129,22 +129,20 @@
     "MemberIdTypeDef",
     {
         "UserId": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateGroupMembershipResponseTypeDef = TypedDict(
+    "CreateGroupMembershipResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "MembershipId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateGroupRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
@@ -160,14 +158,23 @@
 )
 
 class CreateGroupRequestRequestTypeDef(
     _RequiredCreateGroupRequestRequestTypeDef, _OptionalCreateGroupRequestRequestTypeDef
 ):
     pass
 
+CreateGroupResponseTypeDef = TypedDict(
+    "CreateGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EmailTypeDef = TypedDict(
     "EmailTypeDef",
     {
         "Value": str,
         "Type": str,
         "Primary": bool,
     },
@@ -193,14 +200,23 @@
         "Value": str,
         "Type": str,
         "Primary": bool,
     },
     total=False,
 )
 
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "UserId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteGroupMembershipRequestRequestTypeDef = TypedDict(
     "DeleteGroupMembershipRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "MembershipId": str,
     },
 )
@@ -249,24 +265,62 @@
     "FilterTypeDef",
     {
         "AttributePath": str,
         "AttributeValue": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetGroupIdResponseTypeDef = TypedDict(
+    "GetGroupIdResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "GroupId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetGroupMembershipIdResponseTypeDef = TypedDict(
+    "GetGroupMembershipIdResponseTypeDef",
+    {
+        "MembershipId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetUserIdResponseTypeDef = TypedDict(
+    "GetUserIdResponseTypeDef",
+    {
+        "UserId": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
+    "_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
+    {
+        "IdentityStoreId": str,
+        "GroupId": str,
+    },
+)
+_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
+    "_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef(
+    _RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
+    _OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
+):
+    pass
+
 _RequiredListGroupMembershipsRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupMembershipsRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "GroupId": str,
     },
 )
@@ -281,14 +335,47 @@
 
 class ListGroupMembershipsRequestRequestTypeDef(
     _RequiredListGroupMembershipsRequestRequestTypeDef,
     _OptionalListGroupMembershipsRequestRequestTypeDef,
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
+DescribeGroupResponseTypeDef = TypedDict(
+    "DescribeGroupResponseTypeDef",
+    {
+        "GroupId": str,
+        "DisplayName": str,
+        "ExternalIds": List[ExternalIdTypeDef],
+        "Description": str,
+        "IdentityStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGroupTypeDef = TypedDict(
     "_RequiredGroupTypeDef",
     {
         "GroupId": str,
         "IdentityStoreId": str,
     },
 )
@@ -337,14 +424,25 @@
     {
         "IdentityStoreId": str,
         "GroupId": str,
         "MemberId": MemberIdTypeDef,
     },
 )
 
+DescribeGroupMembershipResponseTypeDef = TypedDict(
+    "DescribeGroupMembershipResponseTypeDef",
+    {
+        "IdentityStoreId": str,
+        "MembershipId": str,
+        "GroupId": str,
+        "MemberId": MemberIdTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetGroupMembershipIdRequestRequestTypeDef = TypedDict(
     "GetGroupMembershipIdRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "GroupId": str,
         "MemberId": MemberIdTypeDef,
     },
@@ -384,14 +482,39 @@
     {
         "IdentityStoreId": str,
         "MemberId": MemberIdTypeDef,
         "GroupIds": Sequence[str],
     },
 )
 
+_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
+        {
+            "IdentityStoreId": str,
+            "MemberId": MemberIdTypeDef,
+        },
+    )
+)
+_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef(
+    _RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
+    _OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
+):
+    pass
+
 _RequiredListGroupMembershipsForMemberRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupMembershipsForMemberRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
         "MemberId": MemberIdTypeDef,
     },
 )
@@ -406,91 +529,14 @@
 
 class ListGroupMembershipsForMemberRequestRequestTypeDef(
     _RequiredListGroupMembershipsForMemberRequestRequestTypeDef,
     _OptionalListGroupMembershipsForMemberRequestRequestTypeDef,
 ):
     pass
 
-CreateGroupMembershipResponseTypeDef = TypedDict(
-    "CreateGroupMembershipResponseTypeDef",
-    {
-        "MembershipId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGroupResponseTypeDef = TypedDict(
-    "CreateGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "UserId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGroupMembershipResponseTypeDef = TypedDict(
-    "DescribeGroupMembershipResponseTypeDef",
-    {
-        "IdentityStoreId": str,
-        "MembershipId": str,
-        "GroupId": str,
-        "MemberId": MemberIdTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGroupResponseTypeDef = TypedDict(
-    "DescribeGroupResponseTypeDef",
-    {
-        "GroupId": str,
-        "DisplayName": str,
-        "ExternalIds": List[ExternalIdTypeDef],
-        "Description": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGroupIdResponseTypeDef = TypedDict(
-    "GetGroupIdResponseTypeDef",
-    {
-        "GroupId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGroupMembershipIdResponseTypeDef = TypedDict(
-    "GetGroupMembershipIdResponseTypeDef",
-    {
-        "MembershipId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUserIdResponseTypeDef = TypedDict(
-    "GetUserIdResponseTypeDef",
-    {
-        "UserId": str,
-        "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
 _OptionalCreateUserRequestRequestTypeDef = TypedDict(
@@ -533,15 +579,15 @@
         "PhoneNumbers": List[PhoneNumberTypeDef],
         "UserType": str,
         "Title": str,
         "PreferredLanguage": str,
         "Locale": str,
         "Timezone": str,
         "IdentityStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUserTypeDef = TypedDict(
     "_RequiredUserTypeDef",
     {
         "UserId": str,
@@ -568,150 +614,104 @@
     },
     total=False,
 )
 
 class UserTypeDef(_RequiredUserTypeDef, _OptionalUserTypeDef):
     pass
 
-_RequiredListGroupsRequestRequestTypeDef = TypedDict(
-    "_RequiredListGroupsRequestRequestTypeDef",
+_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListGroupsRequestRequestTypeDef = TypedDict(
-    "_OptionalListGroupsRequestRequestTypeDef",
+_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListGroupsRequestRequestTypeDef(
-    _RequiredListGroupsRequestRequestTypeDef, _OptionalListGroupsRequestRequestTypeDef
+class ListGroupsRequestListGroupsPaginateTypeDef(
+    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
+    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
 ):
     pass
 
-_RequiredListUsersRequestRequestTypeDef = TypedDict(
-    "_RequiredListUsersRequestRequestTypeDef",
+_RequiredListGroupsRequestRequestTypeDef = TypedDict(
+    "_RequiredListGroupsRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListUsersRequestRequestTypeDef = TypedDict(
-    "_OptionalListUsersRequestRequestTypeDef",
+_OptionalListGroupsRequestRequestTypeDef = TypedDict(
+    "_OptionalListGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-class ListUsersRequestRequestTypeDef(
-    _RequiredListUsersRequestRequestTypeDef, _OptionalListUsersRequestRequestTypeDef
-):
-    pass
-
-_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
-        {
-            "IdentityStoreId": str,
-            "MemberId": MemberIdTypeDef,
-        },
-    )
-)
-_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef(
-    _RequiredListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-    _OptionalListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-):
-    pass
-
-_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
-    "_RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
-    {
-        "IdentityStoreId": str,
-        "GroupId": str,
-    },
-)
-_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef = TypedDict(
-    "_OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef(
-    _RequiredListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
-    _OptionalListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
+class ListGroupsRequestRequestTypeDef(
+    _RequiredListGroupsRequestRequestTypeDef, _OptionalListGroupsRequestRequestTypeDef
 ):
     pass
 
-_RequiredListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListGroupsRequestListGroupsPaginateTypeDef",
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListGroupsRequestListGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListGroupsRequestListGroupsPaginateTypeDef",
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListGroupsRequestListGroupsPaginateTypeDef(
-    _RequiredListGroupsRequestListGroupsPaginateTypeDef,
-    _OptionalListGroupsRequestListGroupsPaginateTypeDef,
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
 ):
     pass
 
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+_RequiredListUsersRequestRequestTypeDef = TypedDict(
+    "_RequiredListUsersRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
     },
 )
-_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+_OptionalListUsersRequestRequestTypeDef = TypedDict(
+    "_OptionalListUsersRequestRequestTypeDef",
     {
+        "MaxResults": int,
+        "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-class ListUsersRequestListUsersPaginateTypeDef(
-    _RequiredListUsersRequestListUsersPaginateTypeDef,
-    _OptionalListUsersRequestListUsersPaginateTypeDef,
+class ListUsersRequestRequestTypeDef(
+    _RequiredListUsersRequestRequestTypeDef, _OptionalListUsersRequestRequestTypeDef
 ):
     pass
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupIdRequestRequestTypeDef = TypedDict(
     "GetGroupIdRequestRequestTypeDef",
     {
         "IdentityStoreId": str,
@@ -727,37 +727,37 @@
     },
 )
 
 IsMemberInGroupsResponseTypeDef = TypedDict(
     "IsMemberInGroupsResponseTypeDef",
     {
         "Results": List[GroupMembershipExistenceResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupMembershipsForMemberResponseTypeDef = TypedDict(
     "ListGroupMembershipsForMemberResponseTypeDef",
     {
         "GroupMemberships": List[GroupMembershipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupMembershipsResponseTypeDef = TypedDict(
     "ListGroupMembershipsResponseTypeDef",
     {
         "GroupMemberships": List[GroupMembershipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/PKG-INFO` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-identitystore
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IdentityStore 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IdentityStore 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-identitystore"></a>
 
 # types-aiobotocore-identitystore
 
 [![PyPI - types-aiobotocore-identitystore](https://img.shields.io/pypi/v/types-aiobotocore-identitystore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-identitystore)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-identitystore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-identitystore)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-identitystore?color=blue)](https://pypistats.org/packages/types-aiobotocore-identitystore)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IdentityStore 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
+[aiobotocore.IdentityStore 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/identitystore.html#IdentityStore)
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
 [types-aiobotocore-identitystore docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_identitystore/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,55 +334,55 @@
 ```python
 from types_aiobotocore_identitystore.type_defs import (
     AddressTypeDef,
     ExternalIdTypeDef,
     UniqueAttributeTypeDef,
     AttributeOperationTypeDef,
     MemberIdTypeDef,
-    ResponseMetadataTypeDef,
+    CreateGroupMembershipResponseTypeDef,
     CreateGroupRequestRequestTypeDef,
+    CreateGroupResponseTypeDef,
     EmailTypeDef,
     NameTypeDef,
     PhoneNumberTypeDef,
+    CreateUserResponseTypeDef,
     DeleteGroupMembershipRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeGroupMembershipRequestRequestTypeDef,
     DescribeGroupRequestRequestTypeDef,
     DescribeUserRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
+    GetGroupIdResponseTypeDef,
+    GetGroupMembershipIdResponseTypeDef,
+    GetUserIdResponseTypeDef,
+    ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
     ListGroupMembershipsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeGroupResponseTypeDef,
     GroupTypeDef,
     AlternateIdentifierTypeDef,
     UpdateGroupRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     CreateGroupMembershipRequestRequestTypeDef,
+    DescribeGroupMembershipResponseTypeDef,
     GetGroupMembershipIdRequestRequestTypeDef,
     GroupMembershipExistenceResultTypeDef,
     GroupMembershipTypeDef,
     IsMemberInGroupsRequestRequestTypeDef,
+    ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
     ListGroupMembershipsForMemberRequestRequestTypeDef,
-    CreateGroupMembershipResponseTypeDef,
-    CreateGroupResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DescribeGroupMembershipResponseTypeDef,
-    DescribeGroupResponseTypeDef,
-    GetGroupIdResponseTypeDef,
-    GetGroupMembershipIdResponseTypeDef,
-    GetUserIdResponseTypeDef,
     CreateUserRequestRequestTypeDef,
     DescribeUserResponseTypeDef,
     UserTypeDef,
-    ListGroupsRequestRequestTypeDef,
-    ListUsersRequestRequestTypeDef,
-    ListGroupMembershipsForMemberRequestListGroupMembershipsForMemberPaginateTypeDef,
-    ListGroupMembershipsRequestListGroupMembershipsPaginateTypeDef,
     ListGroupsRequestListGroupsPaginateTypeDef,
+    ListGroupsRequestRequestTypeDef,
     ListUsersRequestListUsersPaginateTypeDef,
+    ListUsersRequestRequestTypeDef,
     ListGroupsResponseTypeDef,
     GetGroupIdRequestRequestTypeDef,
     GetUserIdRequestRequestTypeDef,
     IsMemberInGroupsResponseTypeDef,
     ListGroupMembershipsForMemberResponseTypeDef,
     ListGroupMembershipsResponseTypeDef,
     ListUsersResponseTypeDef,
@@ -396,43 +396,43 @@
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

### Comparing `types-aiobotocore-identitystore-2.5.0.post1/types_aiobotocore_identitystore.egg-info/SOURCES.txt` & `types-aiobotocore-identitystore-2.5.1/types_aiobotocore_identitystore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

