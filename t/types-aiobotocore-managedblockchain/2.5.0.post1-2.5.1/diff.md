# Comparing `tmp/types-aiobotocore-managedblockchain-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-managedblockchain-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-managedblockchain-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-managedblockchain-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-managedblockchain-2.5.0.post1.tar` & `types-aiobotocore-managedblockchain-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.859398 types-aiobotocore-managedblockchain-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16459 2023-03-11 12:26:56.859398 types-aiobotocore-managedblockchain-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14848 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.859398 types-aiobotocore-managedblockchain-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.847398 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/
--rw-r--r--   0 runner    (1001) docker     (123)      721 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      720 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22041 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22004 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8976 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8974 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2213 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    26074 2023-03-11 12:18:06.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    26047 2023-03-11 12:18:06.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:05.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.859398 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16459 2023-03-11 12:26:56.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-03-11 12:26:56.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:56.000000 types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:48.990173 types-aiobotocore-managedblockchain-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16461 2023-06-28 01:43:48.986173 types-aiobotocore-managedblockchain-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14856 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:48.990173 types-aiobotocore-managedblockchain-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2204 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:48.978173 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/
+-rw-r--r--   0 runner    (1001) docker     (123)      721 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      720 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22333 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22296 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9185 2023-06-28 01:34:47.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9183 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2095 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2092 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    26482 2023-06-28 01:34:47.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26453 2023-06-28 01:34:47.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:46.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:48.986173 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16461 2023-06-28 01:43:48.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:43:48.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:48.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:48.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:48.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:48.000000 types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/LICENSE` & `types-aiobotocore-managedblockchain-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/PKG-INFO` & `types-aiobotocore-managedblockchain-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-managedblockchain
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ManagedBlockchain 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ManagedBlockchain 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-managedblockchain"></a>
 
 # types-aiobotocore-managedblockchain
 
 [![PyPI - types-aiobotocore-managedblockchain](https://img.shields.io/pypi/v/types-aiobotocore-managedblockchain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-managedblockchain)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-managedblockchain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-managedblockchain)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-managedblockchain?color=blue)](https://pypistats.org/packages/types-aiobotocore-managedblockchain)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ManagedBlockchain 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
+[aiobotocore.ManagedBlockchain 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
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
 [types-aiobotocore-managedblockchain docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,63 +330,63 @@
 
 ```python
 from types_aiobotocore_managedblockchain.type_defs import (
     AccessorSummaryTypeDef,
     AccessorTypeDef,
     ApprovalThresholdPolicyTypeDef,
     CreateAccessorInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessorOutputTypeDef,
+    CreateMemberOutputTypeDef,
+    CreateNetworkOutputTypeDef,
+    CreateNodeOutputTypeDef,
+    CreateProposalOutputTypeDef,
     DeleteAccessorInputRequestTypeDef,
     DeleteMemberInputRequestTypeDef,
     DeleteNodeInputRequestTypeDef,
     GetAccessorInputRequestTypeDef,
     GetMemberInputRequestTypeDef,
     GetNetworkInputRequestTypeDef,
     GetNodeInputRequestTypeDef,
     GetProposalInputRequestTypeDef,
     NetworkSummaryTypeDef,
     InviteActionTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessorsInputListAccessorsPaginateTypeDef,
     ListAccessorsInputRequestTypeDef,
     ListInvitationsInputRequestTypeDef,
     ListMembersInputRequestTypeDef,
     MemberSummaryTypeDef,
     ListNetworksInputRequestTypeDef,
     ListNodesInputRequestTypeDef,
     NodeSummaryTypeDef,
     ListProposalVotesInputRequestTypeDef,
     VoteSummaryTypeDef,
     ListProposalsInputRequestTypeDef,
     ProposalSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     LogConfigurationTypeDef,
     MemberFabricAttributesTypeDef,
     MemberFabricConfigurationTypeDef,
     NetworkEthereumAttributesTypeDef,
     NetworkFabricAttributesTypeDef,
     NetworkFabricConfigurationTypeDef,
     NodeEthereumAttributesTypeDef,
     NodeFabricAttributesTypeDef,
+    PaginatorConfigTypeDef,
     RemoveActionTypeDef,
     RejectInvitationInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     VoteOnProposalInputRequestTypeDef,
-    VotingPolicyTypeDef,
-    CreateAccessorOutputTypeDef,
-    CreateMemberOutputTypeDef,
-    CreateNetworkOutputTypeDef,
-    CreateNodeOutputTypeDef,
-    CreateProposalOutputTypeDef,
-    GetAccessorOutputTypeDef,
     ListAccessorsOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    GetAccessorOutputTypeDef,
+    VotingPolicyTypeDef,
     InvitationTypeDef,
     ListNetworksOutputTypeDef,
-    ListAccessorsInputListAccessorsPaginateTypeDef,
     ListMembersOutputTypeDef,
     ListNodesOutputTypeDef,
     ListProposalVotesOutputTypeDef,
     ListProposalsOutputTypeDef,
     LogConfigurationsTypeDef,
     MemberFrameworkAttributesTypeDef,
     MemberFrameworkConfigurationTypeDef,
@@ -425,43 +425,43 @@
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/README.md` & `types-aiobotocore-managedblockchain-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-managedblockchain"></a>
 
 # types-aiobotocore-managedblockchain
 
 [![PyPI - types-aiobotocore-managedblockchain](https://img.shields.io/pypi/v/types-aiobotocore-managedblockchain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-managedblockchain)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-managedblockchain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-managedblockchain)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-managedblockchain?color=blue)](https://pypistats.org/packages/types-aiobotocore-managedblockchain)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ManagedBlockchain 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
+[aiobotocore.ManagedBlockchain 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
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
 [types-aiobotocore-managedblockchain docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,63 +297,63 @@
 
 ```python
 from types_aiobotocore_managedblockchain.type_defs import (
     AccessorSummaryTypeDef,
     AccessorTypeDef,
     ApprovalThresholdPolicyTypeDef,
     CreateAccessorInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessorOutputTypeDef,
+    CreateMemberOutputTypeDef,
+    CreateNetworkOutputTypeDef,
+    CreateNodeOutputTypeDef,
+    CreateProposalOutputTypeDef,
     DeleteAccessorInputRequestTypeDef,
     DeleteMemberInputRequestTypeDef,
     DeleteNodeInputRequestTypeDef,
     GetAccessorInputRequestTypeDef,
     GetMemberInputRequestTypeDef,
     GetNetworkInputRequestTypeDef,
     GetNodeInputRequestTypeDef,
     GetProposalInputRequestTypeDef,
     NetworkSummaryTypeDef,
     InviteActionTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessorsInputListAccessorsPaginateTypeDef,
     ListAccessorsInputRequestTypeDef,
     ListInvitationsInputRequestTypeDef,
     ListMembersInputRequestTypeDef,
     MemberSummaryTypeDef,
     ListNetworksInputRequestTypeDef,
     ListNodesInputRequestTypeDef,
     NodeSummaryTypeDef,
     ListProposalVotesInputRequestTypeDef,
     VoteSummaryTypeDef,
     ListProposalsInputRequestTypeDef,
     ProposalSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     LogConfigurationTypeDef,
     MemberFabricAttributesTypeDef,
     MemberFabricConfigurationTypeDef,
     NetworkEthereumAttributesTypeDef,
     NetworkFabricAttributesTypeDef,
     NetworkFabricConfigurationTypeDef,
     NodeEthereumAttributesTypeDef,
     NodeFabricAttributesTypeDef,
+    PaginatorConfigTypeDef,
     RemoveActionTypeDef,
     RejectInvitationInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     VoteOnProposalInputRequestTypeDef,
-    VotingPolicyTypeDef,
-    CreateAccessorOutputTypeDef,
-    CreateMemberOutputTypeDef,
-    CreateNetworkOutputTypeDef,
-    CreateNodeOutputTypeDef,
-    CreateProposalOutputTypeDef,
-    GetAccessorOutputTypeDef,
     ListAccessorsOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    GetAccessorOutputTypeDef,
+    VotingPolicyTypeDef,
     InvitationTypeDef,
     ListNetworksOutputTypeDef,
-    ListAccessorsInputListAccessorsPaginateTypeDef,
     ListMembersOutputTypeDef,
     ListNodesOutputTypeDef,
     ListProposalVotesOutputTypeDef,
     ListProposalsOutputTypeDef,
     LogConfigurationsTypeDef,
     MemberFrameworkAttributesTypeDef,
     MemberFrameworkConfigurationTypeDef,
@@ -392,43 +392,43 @@
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/setup.py` & `types-aiobotocore-managedblockchain-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-managedblockchain.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-managedblockchain",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_managedblockchain"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ManagedBlockchain 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ManagedBlockchain 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/"
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/__init__.py` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/__init__.pyi` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/__main__.py` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ManagedBlockchain 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ManagedBlockchain 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain\nOther"
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/client.py` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -117,18 +117,22 @@
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#close)
         """
 
     async def create_accessor(
-        self, *, ClientRequestToken: str, AccessorType: Literal["BILLING_TOKEN"]
+        self,
+        *,
+        ClientRequestToken: str,
+        AccessorType: Literal["BILLING_TOKEN"],
+        Tags: Mapping[str, str] = ...
     ) -> CreateAccessorOutputTypeDef:
         """
-        .
+        Creates a new accessor for use with Managed Blockchain Ethereum nodes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.create_accessor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#create_accessor)
         """
 
     async def create_member(
         self,
@@ -197,15 +201,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.create_proposal)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#create_proposal)
         """
 
     async def delete_accessor(self, *, AccessorId: str) -> Dict[str, Any]:
         """
-        .
+        Deletes an accessor that your Amazon Web Services account owns.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.delete_accessor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#delete_accessor)
         """
 
     async def delete_member(self, *, NetworkId: str, MemberId: str) -> Dict[str, Any]:
         """
@@ -237,15 +241,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#generate_presigned_url)
         """
 
     async def get_accessor(self, *, AccessorId: str) -> GetAccessorOutputTypeDef:
         """
-        .
+        Returns detailed information about an accessor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.get_accessor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#get_accessor)
         """
 
     async def get_member(self, *, NetworkId: str, MemberId: str) -> GetMemberOutputTypeDef:
         """
@@ -281,15 +285,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#get_proposal)
         """
 
     async def list_accessors(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAccessorsOutputTypeDef:
         """
-        .
+        Returns a list of the accessors and their properties.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.list_accessors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#list_accessors)
         """
 
     async def list_invitations(
         self, *, MaxResults: int = ..., NextToken: str = ...
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/client.pyi` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -110,18 +110,22 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#close)
         """
     async def create_accessor(
-        self, *, ClientRequestToken: str, AccessorType: Literal["BILLING_TOKEN"]
+        self,
+        *,
+        ClientRequestToken: str,
+        AccessorType: Literal["BILLING_TOKEN"],
+        Tags: Mapping[str, str] = ...
     ) -> CreateAccessorOutputTypeDef:
         """
-        .
+        Creates a new accessor for use with Managed Blockchain Ethereum nodes.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.create_accessor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#create_accessor)
         """
     async def create_member(
         self,
         *,
@@ -185,15 +189,15 @@
         can vote on, for example, a proposal to add a new member to the network.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.create_proposal)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#create_proposal)
         """
     async def delete_accessor(self, *, AccessorId: str) -> Dict[str, Any]:
         """
-        .
+        Deletes an accessor that your Amazon Web Services account owns.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.delete_accessor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#delete_accessor)
         """
     async def delete_member(self, *, NetworkId: str, MemberId: str) -> Dict[str, Any]:
         """
         Deletes a member.
@@ -221,15 +225,15 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#generate_presigned_url)
         """
     async def get_accessor(self, *, AccessorId: str) -> GetAccessorOutputTypeDef:
         """
-        .
+        Returns detailed information about an accessor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.get_accessor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#get_accessor)
         """
     async def get_member(self, *, NetworkId: str, MemberId: str) -> GetMemberOutputTypeDef:
         """
         Returns detailed information about a member.
@@ -260,15 +264,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.get_proposal)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#get_proposal)
         """
     async def list_accessors(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAccessorsOutputTypeDef:
         """
-        .
+        Returns a list of the accessors and their properties.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Client.list_accessors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/client/#list_accessors)
         """
     async def list_invitations(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListInvitationsOutputTypeDef:
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/literals.py` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -131,14 +131,15 @@
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
@@ -217,14 +218,15 @@
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
@@ -235,14 +237,15 @@
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
@@ -278,14 +281,15 @@
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
@@ -304,16 +308,19 @@
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
@@ -397,15 +404,17 @@
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/literals.pyi` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -129,14 +129,15 @@
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
@@ -215,14 +216,15 @@
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
@@ -233,14 +235,15 @@
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
@@ -276,14 +279,15 @@
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
@@ -302,16 +306,19 @@
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
@@ -395,15 +402,17 @@
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/paginator.py` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("managedblockchain") as client:
         client: ManagedBlockchainClient
 
         list_accessors_paginator: ListAccessorsPaginator = client.get_paginator("list_accessors")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListAccessorsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListAccessorsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListAccessorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Paginator.ListAccessors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/paginators/#listaccessorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessorsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Paginator.ListAccessors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/paginators/#listaccessorspaginator)
         """
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/paginator.pyi` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("managedblockchain") as client:
         client: ManagedBlockchainClient
 
         list_accessors_paginator: ListAccessorsPaginator = client.get_paginator("list_accessors")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListAccessorsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListAccessorsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListAccessorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Paginator.ListAccessors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/paginators/#listaccessorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessorsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain.Paginator.ListAccessors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/paginators/#listaccessorspaginator)
         """
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/type_defs.py` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,63 +40,63 @@
 
 
 __all__ = (
     "AccessorSummaryTypeDef",
     "AccessorTypeDef",
     "ApprovalThresholdPolicyTypeDef",
     "CreateAccessorInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAccessorOutputTypeDef",
+    "CreateMemberOutputTypeDef",
+    "CreateNetworkOutputTypeDef",
+    "CreateNodeOutputTypeDef",
+    "CreateProposalOutputTypeDef",
     "DeleteAccessorInputRequestTypeDef",
     "DeleteMemberInputRequestTypeDef",
     "DeleteNodeInputRequestTypeDef",
     "GetAccessorInputRequestTypeDef",
     "GetMemberInputRequestTypeDef",
     "GetNetworkInputRequestTypeDef",
     "GetNodeInputRequestTypeDef",
     "GetProposalInputRequestTypeDef",
     "NetworkSummaryTypeDef",
     "InviteActionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessorsInputListAccessorsPaginateTypeDef",
     "ListAccessorsInputRequestTypeDef",
     "ListInvitationsInputRequestTypeDef",
     "ListMembersInputRequestTypeDef",
     "MemberSummaryTypeDef",
     "ListNetworksInputRequestTypeDef",
     "ListNodesInputRequestTypeDef",
     "NodeSummaryTypeDef",
     "ListProposalVotesInputRequestTypeDef",
     "VoteSummaryTypeDef",
     "ListProposalsInputRequestTypeDef",
     "ProposalSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "LogConfigurationTypeDef",
     "MemberFabricAttributesTypeDef",
     "MemberFabricConfigurationTypeDef",
     "NetworkEthereumAttributesTypeDef",
     "NetworkFabricAttributesTypeDef",
     "NetworkFabricConfigurationTypeDef",
     "NodeEthereumAttributesTypeDef",
     "NodeFabricAttributesTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveActionTypeDef",
     "RejectInvitationInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "VoteOnProposalInputRequestTypeDef",
-    "VotingPolicyTypeDef",
-    "CreateAccessorOutputTypeDef",
-    "CreateMemberOutputTypeDef",
-    "CreateNetworkOutputTypeDef",
-    "CreateNodeOutputTypeDef",
-    "CreateProposalOutputTypeDef",
-    "GetAccessorOutputTypeDef",
     "ListAccessorsOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "GetAccessorOutputTypeDef",
+    "VotingPolicyTypeDef",
     "InvitationTypeDef",
     "ListNetworksOutputTypeDef",
-    "ListAccessorsInputListAccessorsPaginateTypeDef",
     "ListMembersOutputTypeDef",
     "ListNodesOutputTypeDef",
     "ListProposalVotesOutputTypeDef",
     "ListProposalsOutputTypeDef",
     "LogConfigurationsTypeDef",
     "MemberFrameworkAttributesTypeDef",
     "MemberFrameworkConfigurationTypeDef",
@@ -144,44 +144,90 @@
     {
         "Id": str,
         "Type": Literal["BILLING_TOKEN"],
         "BillingToken": str,
         "Status": AccessorStatusType,
         "CreationDate": datetime,
         "Arn": str,
+        "Tags": Dict[str, str],
     },
     total=False,
 )
 
 ApprovalThresholdPolicyTypeDef = TypedDict(
     "ApprovalThresholdPolicyTypeDef",
     {
         "ThresholdPercentage": int,
         "ProposalDurationInHours": int,
         "ThresholdComparator": ThresholdComparatorType,
     },
     total=False,
 )
 
-CreateAccessorInputRequestTypeDef = TypedDict(
-    "CreateAccessorInputRequestTypeDef",
+_RequiredCreateAccessorInputRequestTypeDef = TypedDict(
+    "_RequiredCreateAccessorInputRequestTypeDef",
     {
         "ClientRequestToken": str,
         "AccessorType": Literal["BILLING_TOKEN"],
     },
 )
+_OptionalCreateAccessorInputRequestTypeDef = TypedDict(
+    "_OptionalCreateAccessorInputRequestTypeDef",
+    {
+        "Tags": Mapping[str, str],
+    },
+    total=False,
+)
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+class CreateAccessorInputRequestTypeDef(
+    _RequiredCreateAccessorInputRequestTypeDef, _OptionalCreateAccessorInputRequestTypeDef
+):
+    pass
+
+
+CreateAccessorOutputTypeDef = TypedDict(
+    "CreateAccessorOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AccessorId": str,
+        "BillingToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateMemberOutputTypeDef = TypedDict(
+    "CreateMemberOutputTypeDef",
+    {
+        "MemberId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateNetworkOutputTypeDef = TypedDict(
+    "CreateNetworkOutputTypeDef",
+    {
+        "NetworkId": str,
+        "MemberId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateNodeOutputTypeDef = TypedDict(
+    "CreateNodeOutputTypeDef",
+    {
+        "NodeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProposalOutputTypeDef = TypedDict(
+    "CreateProposalOutputTypeDef",
+    {
+        "ProposalId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAccessorInputRequestTypeDef = TypedDict(
     "DeleteAccessorInputRequestTypeDef",
     {
         "AccessorId": str,
@@ -288,20 +334,18 @@
 InviteActionTypeDef = TypedDict(
     "InviteActionTypeDef",
     {
         "Principal": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccessorsInputListAccessorsPaginateTypeDef = TypedDict(
+    "ListAccessorsInputListAccessorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccessorsInputRequestTypeDef = TypedDict(
     "ListAccessorsInputRequestTypeDef",
     {
@@ -481,14 +525,22 @@
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
 LogConfigurationTypeDef = TypedDict(
     "LogConfigurationTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
@@ -548,28 +600,49 @@
     {
         "PeerEndpoint": str,
         "PeerEventEndpoint": str,
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
 RemoveActionTypeDef = TypedDict(
     "RemoveActionTypeDef",
     {
         "MemberId": str,
     },
 )
 
 RejectInvitationInputRequestTypeDef = TypedDict(
     "RejectInvitationInputRequestTypeDef",
     {
         "InvitationId": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -588,87 +661,37 @@
         "NetworkId": str,
         "ProposalId": str,
         "VoterMemberId": str,
         "Vote": VoteValueType,
     },
 )
 
-VotingPolicyTypeDef = TypedDict(
-    "VotingPolicyTypeDef",
-    {
-        "ApprovalThresholdPolicy": ApprovalThresholdPolicyTypeDef,
-    },
-    total=False,
-)
-
-CreateAccessorOutputTypeDef = TypedDict(
-    "CreateAccessorOutputTypeDef",
-    {
-        "AccessorId": str,
-        "BillingToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMemberOutputTypeDef = TypedDict(
-    "CreateMemberOutputTypeDef",
-    {
-        "MemberId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNetworkOutputTypeDef = TypedDict(
-    "CreateNetworkOutputTypeDef",
-    {
-        "NetworkId": str,
-        "MemberId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNodeOutputTypeDef = TypedDict(
-    "CreateNodeOutputTypeDef",
-    {
-        "NodeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProposalOutputTypeDef = TypedDict(
-    "CreateProposalOutputTypeDef",
+ListAccessorsOutputTypeDef = TypedDict(
+    "ListAccessorsOutputTypeDef",
     {
-        "ProposalId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Accessors": List[AccessorSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccessorOutputTypeDef = TypedDict(
     "GetAccessorOutputTypeDef",
     {
         "Accessor": AccessorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAccessorsOutputTypeDef = TypedDict(
-    "ListAccessorsOutputTypeDef",
-    {
-        "Accessors": List[AccessorSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+VotingPolicyTypeDef = TypedDict(
+    "VotingPolicyTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApprovalThresholdPolicy": ApprovalThresholdPolicyTypeDef,
     },
+    total=False,
 )
 
 InvitationTypeDef = TypedDict(
     "InvitationTypeDef",
     {
         "InvitationId": str,
         "CreationDate": datetime,
@@ -681,59 +704,51 @@
 )
 
 ListNetworksOutputTypeDef = TypedDict(
     "ListNetworksOutputTypeDef",
     {
         "Networks": List[NetworkSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAccessorsInputListAccessorsPaginateTypeDef = TypedDict(
-    "ListAccessorsInputListAccessorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListMembersOutputTypeDef = TypedDict(
     "ListMembersOutputTypeDef",
     {
         "Members": List[MemberSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNodesOutputTypeDef = TypedDict(
     "ListNodesOutputTypeDef",
     {
         "Nodes": List[NodeSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProposalVotesOutputTypeDef = TypedDict(
     "ListProposalVotesOutputTypeDef",
     {
         "ProposalVotes": List[VoteSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProposalsOutputTypeDef = TypedDict(
     "ListProposalsOutputTypeDef",
     {
         "Proposals": List[ProposalSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LogConfigurationsTypeDef = TypedDict(
     "LogConfigurationsTypeDef",
     {
         "Cloudwatch": LogConfigurationTypeDef,
@@ -793,15 +808,15 @@
 )
 
 ListInvitationsOutputTypeDef = TypedDict(
     "ListInvitationsOutputTypeDef",
     {
         "Invitations": List[InvitationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MemberFabricLogPublishingConfigurationTypeDef = TypedDict(
     "MemberFabricLogPublishingConfigurationTypeDef",
     {
         "CaLogs": LogConfigurationsTypeDef,
@@ -899,23 +914,23 @@
     total=False,
 )
 
 GetNetworkOutputTypeDef = TypedDict(
     "GetNetworkOutputTypeDef",
     {
         "Network": NetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProposalOutputTypeDef = TypedDict(
     "GetProposalOutputTypeDef",
     {
         "Proposal": ProposalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMemberConfigurationTypeDef = TypedDict(
     "_RequiredMemberConfigurationTypeDef",
     {
         "Name": str,
@@ -1084,15 +1099,15 @@
     pass
 
 
 GetMemberOutputTypeDef = TypedDict(
     "GetMemberOutputTypeDef",
     {
         "Member": MemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateNodeInputRequestTypeDef = TypedDict(
     "_RequiredCreateNodeInputRequestTypeDef",
     {
         "ClientRequestToken": str,
@@ -1116,10 +1131,10 @@
     pass
 
 
 GetNodeOutputTypeDef = TypedDict(
     "GetNodeOutputTypeDef",
     {
         "Node": NodeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain/type_defs.pyi` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -39,63 +39,63 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccessorSummaryTypeDef",
     "AccessorTypeDef",
     "ApprovalThresholdPolicyTypeDef",
     "CreateAccessorInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAccessorOutputTypeDef",
+    "CreateMemberOutputTypeDef",
+    "CreateNetworkOutputTypeDef",
+    "CreateNodeOutputTypeDef",
+    "CreateProposalOutputTypeDef",
     "DeleteAccessorInputRequestTypeDef",
     "DeleteMemberInputRequestTypeDef",
     "DeleteNodeInputRequestTypeDef",
     "GetAccessorInputRequestTypeDef",
     "GetMemberInputRequestTypeDef",
     "GetNetworkInputRequestTypeDef",
     "GetNodeInputRequestTypeDef",
     "GetProposalInputRequestTypeDef",
     "NetworkSummaryTypeDef",
     "InviteActionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessorsInputListAccessorsPaginateTypeDef",
     "ListAccessorsInputRequestTypeDef",
     "ListInvitationsInputRequestTypeDef",
     "ListMembersInputRequestTypeDef",
     "MemberSummaryTypeDef",
     "ListNetworksInputRequestTypeDef",
     "ListNodesInputRequestTypeDef",
     "NodeSummaryTypeDef",
     "ListProposalVotesInputRequestTypeDef",
     "VoteSummaryTypeDef",
     "ListProposalsInputRequestTypeDef",
     "ProposalSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "LogConfigurationTypeDef",
     "MemberFabricAttributesTypeDef",
     "MemberFabricConfigurationTypeDef",
     "NetworkEthereumAttributesTypeDef",
     "NetworkFabricAttributesTypeDef",
     "NetworkFabricConfigurationTypeDef",
     "NodeEthereumAttributesTypeDef",
     "NodeFabricAttributesTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveActionTypeDef",
     "RejectInvitationInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "VoteOnProposalInputRequestTypeDef",
-    "VotingPolicyTypeDef",
-    "CreateAccessorOutputTypeDef",
-    "CreateMemberOutputTypeDef",
-    "CreateNetworkOutputTypeDef",
-    "CreateNodeOutputTypeDef",
-    "CreateProposalOutputTypeDef",
-    "GetAccessorOutputTypeDef",
     "ListAccessorsOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "GetAccessorOutputTypeDef",
+    "VotingPolicyTypeDef",
     "InvitationTypeDef",
     "ListNetworksOutputTypeDef",
-    "ListAccessorsInputListAccessorsPaginateTypeDef",
     "ListMembersOutputTypeDef",
     "ListNodesOutputTypeDef",
     "ListProposalVotesOutputTypeDef",
     "ListProposalsOutputTypeDef",
     "LogConfigurationsTypeDef",
     "MemberFrameworkAttributesTypeDef",
     "MemberFrameworkConfigurationTypeDef",
@@ -143,44 +143,88 @@
     {
         "Id": str,
         "Type": Literal["BILLING_TOKEN"],
         "BillingToken": str,
         "Status": AccessorStatusType,
         "CreationDate": datetime,
         "Arn": str,
+        "Tags": Dict[str, str],
     },
     total=False,
 )
 
 ApprovalThresholdPolicyTypeDef = TypedDict(
     "ApprovalThresholdPolicyTypeDef",
     {
         "ThresholdPercentage": int,
         "ProposalDurationInHours": int,
         "ThresholdComparator": ThresholdComparatorType,
     },
     total=False,
 )
 
-CreateAccessorInputRequestTypeDef = TypedDict(
-    "CreateAccessorInputRequestTypeDef",
+_RequiredCreateAccessorInputRequestTypeDef = TypedDict(
+    "_RequiredCreateAccessorInputRequestTypeDef",
     {
         "ClientRequestToken": str,
         "AccessorType": Literal["BILLING_TOKEN"],
     },
 )
+_OptionalCreateAccessorInputRequestTypeDef = TypedDict(
+    "_OptionalCreateAccessorInputRequestTypeDef",
+    {
+        "Tags": Mapping[str, str],
+    },
+    total=False,
+)
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+class CreateAccessorInputRequestTypeDef(
+    _RequiredCreateAccessorInputRequestTypeDef, _OptionalCreateAccessorInputRequestTypeDef
+):
+    pass
+
+CreateAccessorOutputTypeDef = TypedDict(
+    "CreateAccessorOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AccessorId": str,
+        "BillingToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateMemberOutputTypeDef = TypedDict(
+    "CreateMemberOutputTypeDef",
+    {
+        "MemberId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateNetworkOutputTypeDef = TypedDict(
+    "CreateNetworkOutputTypeDef",
+    {
+        "NetworkId": str,
+        "MemberId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateNodeOutputTypeDef = TypedDict(
+    "CreateNodeOutputTypeDef",
+    {
+        "NodeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProposalOutputTypeDef = TypedDict(
+    "CreateProposalOutputTypeDef",
+    {
+        "ProposalId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAccessorInputRequestTypeDef = TypedDict(
     "DeleteAccessorInputRequestTypeDef",
     {
         "AccessorId": str,
@@ -283,20 +327,18 @@
 InviteActionTypeDef = TypedDict(
     "InviteActionTypeDef",
     {
         "Principal": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccessorsInputListAccessorsPaginateTypeDef = TypedDict(
+    "ListAccessorsInputListAccessorsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccessorsInputRequestTypeDef = TypedDict(
     "ListAccessorsInputRequestTypeDef",
     {
@@ -468,14 +510,22 @@
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
 LogConfigurationTypeDef = TypedDict(
     "LogConfigurationTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
@@ -535,28 +585,49 @@
     {
         "PeerEndpoint": str,
         "PeerEventEndpoint": str,
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
 RemoveActionTypeDef = TypedDict(
     "RemoveActionTypeDef",
     {
         "MemberId": str,
     },
 )
 
 RejectInvitationInputRequestTypeDef = TypedDict(
     "RejectInvitationInputRequestTypeDef",
     {
         "InvitationId": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -575,87 +646,37 @@
         "NetworkId": str,
         "ProposalId": str,
         "VoterMemberId": str,
         "Vote": VoteValueType,
     },
 )
 
-VotingPolicyTypeDef = TypedDict(
-    "VotingPolicyTypeDef",
-    {
-        "ApprovalThresholdPolicy": ApprovalThresholdPolicyTypeDef,
-    },
-    total=False,
-)
-
-CreateAccessorOutputTypeDef = TypedDict(
-    "CreateAccessorOutputTypeDef",
-    {
-        "AccessorId": str,
-        "BillingToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMemberOutputTypeDef = TypedDict(
-    "CreateMemberOutputTypeDef",
-    {
-        "MemberId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNetworkOutputTypeDef = TypedDict(
-    "CreateNetworkOutputTypeDef",
-    {
-        "NetworkId": str,
-        "MemberId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNodeOutputTypeDef = TypedDict(
-    "CreateNodeOutputTypeDef",
-    {
-        "NodeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProposalOutputTypeDef = TypedDict(
-    "CreateProposalOutputTypeDef",
+ListAccessorsOutputTypeDef = TypedDict(
+    "ListAccessorsOutputTypeDef",
     {
-        "ProposalId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Accessors": List[AccessorSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccessorOutputTypeDef = TypedDict(
     "GetAccessorOutputTypeDef",
     {
         "Accessor": AccessorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAccessorsOutputTypeDef = TypedDict(
-    "ListAccessorsOutputTypeDef",
-    {
-        "Accessors": List[AccessorSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+VotingPolicyTypeDef = TypedDict(
+    "VotingPolicyTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApprovalThresholdPolicy": ApprovalThresholdPolicyTypeDef,
     },
+    total=False,
 )
 
 InvitationTypeDef = TypedDict(
     "InvitationTypeDef",
     {
         "InvitationId": str,
         "CreationDate": datetime,
@@ -668,59 +689,51 @@
 )
 
 ListNetworksOutputTypeDef = TypedDict(
     "ListNetworksOutputTypeDef",
     {
         "Networks": List[NetworkSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccessorsInputListAccessorsPaginateTypeDef = TypedDict(
-    "ListAccessorsInputListAccessorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListMembersOutputTypeDef = TypedDict(
     "ListMembersOutputTypeDef",
     {
         "Members": List[MemberSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNodesOutputTypeDef = TypedDict(
     "ListNodesOutputTypeDef",
     {
         "Nodes": List[NodeSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProposalVotesOutputTypeDef = TypedDict(
     "ListProposalVotesOutputTypeDef",
     {
         "ProposalVotes": List[VoteSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProposalsOutputTypeDef = TypedDict(
     "ListProposalsOutputTypeDef",
     {
         "Proposals": List[ProposalSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LogConfigurationsTypeDef = TypedDict(
     "LogConfigurationsTypeDef",
     {
         "Cloudwatch": LogConfigurationTypeDef,
@@ -780,15 +793,15 @@
 )
 
 ListInvitationsOutputTypeDef = TypedDict(
     "ListInvitationsOutputTypeDef",
     {
         "Invitations": List[InvitationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MemberFabricLogPublishingConfigurationTypeDef = TypedDict(
     "MemberFabricLogPublishingConfigurationTypeDef",
     {
         "CaLogs": LogConfigurationsTypeDef,
@@ -884,23 +897,23 @@
     total=False,
 )
 
 GetNetworkOutputTypeDef = TypedDict(
     "GetNetworkOutputTypeDef",
     {
         "Network": NetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProposalOutputTypeDef = TypedDict(
     "GetProposalOutputTypeDef",
     {
         "Proposal": ProposalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMemberConfigurationTypeDef = TypedDict(
     "_RequiredMemberConfigurationTypeDef",
     {
         "Name": str,
@@ -1059,15 +1072,15 @@
 ):
     pass
 
 GetMemberOutputTypeDef = TypedDict(
     "GetMemberOutputTypeDef",
     {
         "Member": MemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateNodeInputRequestTypeDef = TypedDict(
     "_RequiredCreateNodeInputRequestTypeDef",
     {
         "ClientRequestToken": str,
@@ -1089,10 +1102,10 @@
 ):
     pass
 
 GetNodeOutputTypeDef = TypedDict(
     "GetNodeOutputTypeDef",
     {
         "Node": NodeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/PKG-INFO` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-managedblockchain
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ManagedBlockchain 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ManagedBlockchain 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-managedblockchain"></a>
 
 # types-aiobotocore-managedblockchain
 
 [![PyPI - types-aiobotocore-managedblockchain](https://img.shields.io/pypi/v/types-aiobotocore-managedblockchain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-managedblockchain)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-managedblockchain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-managedblockchain)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-managedblockchain?color=blue)](https://pypistats.org/packages/types-aiobotocore-managedblockchain)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ManagedBlockchain 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
+[aiobotocore.ManagedBlockchain 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
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
 [types-aiobotocore-managedblockchain docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_managedblockchain/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,63 +330,63 @@
 
 ```python
 from types_aiobotocore_managedblockchain.type_defs import (
     AccessorSummaryTypeDef,
     AccessorTypeDef,
     ApprovalThresholdPolicyTypeDef,
     CreateAccessorInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessorOutputTypeDef,
+    CreateMemberOutputTypeDef,
+    CreateNetworkOutputTypeDef,
+    CreateNodeOutputTypeDef,
+    CreateProposalOutputTypeDef,
     DeleteAccessorInputRequestTypeDef,
     DeleteMemberInputRequestTypeDef,
     DeleteNodeInputRequestTypeDef,
     GetAccessorInputRequestTypeDef,
     GetMemberInputRequestTypeDef,
     GetNetworkInputRequestTypeDef,
     GetNodeInputRequestTypeDef,
     GetProposalInputRequestTypeDef,
     NetworkSummaryTypeDef,
     InviteActionTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessorsInputListAccessorsPaginateTypeDef,
     ListAccessorsInputRequestTypeDef,
     ListInvitationsInputRequestTypeDef,
     ListMembersInputRequestTypeDef,
     MemberSummaryTypeDef,
     ListNetworksInputRequestTypeDef,
     ListNodesInputRequestTypeDef,
     NodeSummaryTypeDef,
     ListProposalVotesInputRequestTypeDef,
     VoteSummaryTypeDef,
     ListProposalsInputRequestTypeDef,
     ProposalSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     LogConfigurationTypeDef,
     MemberFabricAttributesTypeDef,
     MemberFabricConfigurationTypeDef,
     NetworkEthereumAttributesTypeDef,
     NetworkFabricAttributesTypeDef,
     NetworkFabricConfigurationTypeDef,
     NodeEthereumAttributesTypeDef,
     NodeFabricAttributesTypeDef,
+    PaginatorConfigTypeDef,
     RemoveActionTypeDef,
     RejectInvitationInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     VoteOnProposalInputRequestTypeDef,
-    VotingPolicyTypeDef,
-    CreateAccessorOutputTypeDef,
-    CreateMemberOutputTypeDef,
-    CreateNetworkOutputTypeDef,
-    CreateNodeOutputTypeDef,
-    CreateProposalOutputTypeDef,
-    GetAccessorOutputTypeDef,
     ListAccessorsOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    GetAccessorOutputTypeDef,
+    VotingPolicyTypeDef,
     InvitationTypeDef,
     ListNetworksOutputTypeDef,
-    ListAccessorsInputListAccessorsPaginateTypeDef,
     ListMembersOutputTypeDef,
     ListNodesOutputTypeDef,
     ListProposalVotesOutputTypeDef,
     ListProposalsOutputTypeDef,
     LogConfigurationsTypeDef,
     MemberFrameworkAttributesTypeDef,
     MemberFrameworkConfigurationTypeDef,
@@ -425,43 +425,43 @@
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

### Comparing `types-aiobotocore-managedblockchain-2.5.0.post1/types_aiobotocore_managedblockchain.egg-info/SOURCES.txt` & `types-aiobotocore-managedblockchain-2.5.1/types_aiobotocore_managedblockchain.egg-info/SOURCES.txt`

 * *Files identical despite different names*

