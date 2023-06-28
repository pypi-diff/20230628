# Comparing `tmp/types-aiobotocore-opensearchserverless-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-opensearchserverless-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-opensearchserverless-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:04 2023, max compression
+gzip compressed data, was "types-aiobotocore-opensearchserverless-2.5.1.tar", last modified: Wed Jun 28 01:43:56 2023, max compression
```

## Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1.tar` & `types-aiobotocore-opensearchserverless-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:04.287471 types-aiobotocore-opensearchserverless-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16073 2023-03-11 12:27:04.287471 types-aiobotocore-opensearchserverless-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14443 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:04.287471 types-aiobotocore-opensearchserverless-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2214 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:04.287471 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/
--rw-r--r--   0 runner    (1001) docker     (123)      581 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      580 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25666 2023-03-11 12:19:27.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    25626 2023-03-11 12:19:27.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8112 2023-03-11 12:19:27.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8110 2023-03-11 12:19:27.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    29371 2023-03-11 12:19:28.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    29332 2023-03-11 12:19:28.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:25.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:04.287471 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16073 2023-03-11 12:27:04.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:27:04.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:04.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:04.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:04.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-03-11 12:27:04.000000 types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.106186 types-aiobotocore-opensearchserverless-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16078 2023-06-28 01:43:56.106186 types-aiobotocore-opensearchserverless-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14454 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:56.106186 types-aiobotocore-opensearchserverless-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2208 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.106186 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/
+-rw-r--r--   0 runner    (1001) docker     (123)      581 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      580 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      997 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25784 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25744 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8321 2023-06-28 01:36:11.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8319 2023-06-28 01:36:11.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    29423 2023-06-28 01:36:11.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29384 2023-06-28 01:36:11.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:10.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.106186 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16078 2023-06-28 01:43:55.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:43:55.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:55.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:55.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:55.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 01:43:55.000000 types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/LICENSE` & `types-aiobotocore-opensearchserverless-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/PKG-INFO` & `types-aiobotocore-opensearchserverless-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opensearchserverless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opensearchserverless"></a>
 
 # types-aiobotocore-opensearchserverless
 
 [![PyPI - types-aiobotocore-opensearchserverless](https://img.shields.io/pypi/v/types-aiobotocore-opensearchserverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearchserverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opensearchserverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearchserverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opensearchserverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-opensearchserverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpenSearchServiceServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless)
+[aiobotocore.OpenSearchServiceServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless)
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
 [types-aiobotocore-opensearchserverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -302,15 +302,14 @@
     AccessPolicyDetailTypeDef,
     AccessPolicyStatsTypeDef,
     AccessPolicySummaryTypeDef,
     CapacityLimitsTypeDef,
     BatchGetCollectionRequestRequestTypeDef,
     CollectionDetailTypeDef,
     CollectionErrorDetailTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetVpcEndpointRequestRequestTypeDef,
     VpcEndpointDetailTypeDef,
     VpcEndpointErrorDetailTypeDef,
     CollectionFiltersTypeDef,
     CollectionSummaryTypeDef,
     CreateAccessPolicyRequestRequestTypeDef,
     CreateCollectionDetailTypeDef,
@@ -336,28 +335,29 @@
     ListSecurityConfigsRequestRequestTypeDef,
     SecurityConfigSummaryTypeDef,
     ListSecurityPoliciesRequestRequestTypeDef,
     SecurityPolicySummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     VpcEndpointFiltersTypeDef,
     VpcEndpointSummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAccessPolicyRequestRequestTypeDef,
     UpdateCollectionDetailTypeDef,
     UpdateCollectionRequestRequestTypeDef,
     UpdateSecurityPolicyRequestRequestTypeDef,
     UpdateVpcEndpointDetailTypeDef,
     UpdateVpcEndpointRequestRequestTypeDef,
-    AccountSettingsDetailTypeDef,
-    UpdateAccountSettingsRequestRequestTypeDef,
-    BatchGetCollectionResponseTypeDef,
     CreateAccessPolicyResponseTypeDef,
     GetAccessPolicyResponseTypeDef,
-    ListAccessPoliciesResponseTypeDef,
     UpdateAccessPolicyResponseTypeDef,
+    ListAccessPoliciesResponseTypeDef,
+    AccountSettingsDetailTypeDef,
+    UpdateAccountSettingsRequestRequestTypeDef,
+    BatchGetCollectionResponseTypeDef,
     BatchGetVpcEndpointResponseTypeDef,
     ListCollectionsRequestRequestTypeDef,
     ListCollectionsResponseTypeDef,
     CreateCollectionResponseTypeDef,
     CreateCollectionRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/README.md` & `types-aiobotocore-opensearchserverless-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-opensearchserverless"></a>
 
 # types-aiobotocore-opensearchserverless
 
 [![PyPI - types-aiobotocore-opensearchserverless](https://img.shields.io/pypi/v/types-aiobotocore-opensearchserverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearchserverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opensearchserverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearchserverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opensearchserverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-opensearchserverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpenSearchServiceServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless)
+[aiobotocore.OpenSearchServiceServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless)
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
 [types-aiobotocore-opensearchserverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,15 +269,14 @@
     AccessPolicyDetailTypeDef,
     AccessPolicyStatsTypeDef,
     AccessPolicySummaryTypeDef,
     CapacityLimitsTypeDef,
     BatchGetCollectionRequestRequestTypeDef,
     CollectionDetailTypeDef,
     CollectionErrorDetailTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetVpcEndpointRequestRequestTypeDef,
     VpcEndpointDetailTypeDef,
     VpcEndpointErrorDetailTypeDef,
     CollectionFiltersTypeDef,
     CollectionSummaryTypeDef,
     CreateAccessPolicyRequestRequestTypeDef,
     CreateCollectionDetailTypeDef,
@@ -303,28 +302,29 @@
     ListSecurityConfigsRequestRequestTypeDef,
     SecurityConfigSummaryTypeDef,
     ListSecurityPoliciesRequestRequestTypeDef,
     SecurityPolicySummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     VpcEndpointFiltersTypeDef,
     VpcEndpointSummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAccessPolicyRequestRequestTypeDef,
     UpdateCollectionDetailTypeDef,
     UpdateCollectionRequestRequestTypeDef,
     UpdateSecurityPolicyRequestRequestTypeDef,
     UpdateVpcEndpointDetailTypeDef,
     UpdateVpcEndpointRequestRequestTypeDef,
-    AccountSettingsDetailTypeDef,
-    UpdateAccountSettingsRequestRequestTypeDef,
-    BatchGetCollectionResponseTypeDef,
     CreateAccessPolicyResponseTypeDef,
     GetAccessPolicyResponseTypeDef,
-    ListAccessPoliciesResponseTypeDef,
     UpdateAccessPolicyResponseTypeDef,
+    ListAccessPoliciesResponseTypeDef,
+    AccountSettingsDetailTypeDef,
+    UpdateAccountSettingsRequestRequestTypeDef,
+    BatchGetCollectionResponseTypeDef,
     BatchGetVpcEndpointResponseTypeDef,
     ListCollectionsRequestRequestTypeDef,
     ListCollectionsResponseTypeDef,
     CreateCollectionResponseTypeDef,
     CreateCollectionRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -359,43 +359,43 @@
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/setup.py` & `types-aiobotocore-opensearchserverless-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-opensearchserverless.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-opensearchserverless",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_opensearchserverless"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/",
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/__init__.py` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/__init__.pyi` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/__main__.py` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless\nOther"
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/client.py` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -72,15 +72,17 @@
         self.operation_name: str
 
 
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    OcuLimitExceededException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
+    ServiceQuotaExceededException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 
 class OpenSearchServiceServerlessClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/client/)
```

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/client.pyi` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -69,15 +69,17 @@
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    OcuLimitExceededException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
+    ServiceQuotaExceededException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 class OpenSearchServiceServerlessClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/client/)
     """
```

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/literals.py` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -98,14 +98,15 @@
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
@@ -184,14 +185,15 @@
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
@@ -202,14 +204,15 @@
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
@@ -245,14 +248,15 @@
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
@@ -271,16 +275,19 @@
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
@@ -364,15 +371,17 @@
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/literals.pyi` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -96,14 +96,15 @@
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
@@ -182,14 +183,15 @@
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
@@ -200,14 +202,15 @@
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
@@ -243,14 +246,15 @@
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
@@ -269,16 +273,19 @@
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
@@ -362,15 +369,17 @@
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/type_defs.py` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -35,15 +35,14 @@
     "AccessPolicyDetailTypeDef",
     "AccessPolicyStatsTypeDef",
     "AccessPolicySummaryTypeDef",
     "CapacityLimitsTypeDef",
     "BatchGetCollectionRequestRequestTypeDef",
     "CollectionDetailTypeDef",
     "CollectionErrorDetailTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetVpcEndpointRequestRequestTypeDef",
     "VpcEndpointDetailTypeDef",
     "VpcEndpointErrorDetailTypeDef",
     "CollectionFiltersTypeDef",
     "CollectionSummaryTypeDef",
     "CreateAccessPolicyRequestRequestTypeDef",
     "CreateCollectionDetailTypeDef",
@@ -69,28 +68,29 @@
     "ListSecurityConfigsRequestRequestTypeDef",
     "SecurityConfigSummaryTypeDef",
     "ListSecurityPoliciesRequestRequestTypeDef",
     "SecurityPolicySummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "VpcEndpointFiltersTypeDef",
     "VpcEndpointSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAccessPolicyRequestRequestTypeDef",
     "UpdateCollectionDetailTypeDef",
     "UpdateCollectionRequestRequestTypeDef",
     "UpdateSecurityPolicyRequestRequestTypeDef",
     "UpdateVpcEndpointDetailTypeDef",
     "UpdateVpcEndpointRequestRequestTypeDef",
-    "AccountSettingsDetailTypeDef",
-    "UpdateAccountSettingsRequestRequestTypeDef",
-    "BatchGetCollectionResponseTypeDef",
     "CreateAccessPolicyResponseTypeDef",
     "GetAccessPolicyResponseTypeDef",
-    "ListAccessPoliciesResponseTypeDef",
     "UpdateAccessPolicyResponseTypeDef",
+    "ListAccessPoliciesResponseTypeDef",
+    "AccountSettingsDetailTypeDef",
+    "UpdateAccountSettingsRequestRequestTypeDef",
+    "BatchGetCollectionResponseTypeDef",
     "BatchGetVpcEndpointResponseTypeDef",
     "ListCollectionsRequestRequestTypeDef",
     "ListCollectionsResponseTypeDef",
     "CreateCollectionResponseTypeDef",
     "CreateCollectionRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
@@ -195,25 +195,14 @@
         "errorMessage": str,
         "id": str,
         "name": str,
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
 BatchGetVpcEndpointRequestRequestTypeDef = TypedDict(
     "BatchGetVpcEndpointRequestRequestTypeDef",
     {
         "ids": Sequence[str],
     },
 )
 
@@ -694,14 +683,25 @@
         "id": str,
         "name": str,
         "status": VpcEndpointStatusType,
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
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -829,78 +829,78 @@
 
 class UpdateVpcEndpointRequestRequestTypeDef(
     _RequiredUpdateVpcEndpointRequestRequestTypeDef, _OptionalUpdateVpcEndpointRequestRequestTypeDef
 ):
     pass
 
 
-AccountSettingsDetailTypeDef = TypedDict(
-    "AccountSettingsDetailTypeDef",
+CreateAccessPolicyResponseTypeDef = TypedDict(
+    "CreateAccessPolicyResponseTypeDef",
     {
-        "capacityLimits": CapacityLimitsTypeDef,
+        "accessPolicyDetail": AccessPolicyDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-UpdateAccountSettingsRequestRequestTypeDef = TypedDict(
-    "UpdateAccountSettingsRequestRequestTypeDef",
+GetAccessPolicyResponseTypeDef = TypedDict(
+    "GetAccessPolicyResponseTypeDef",
     {
-        "capacityLimits": CapacityLimitsTypeDef,
+        "accessPolicyDetail": AccessPolicyDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-BatchGetCollectionResponseTypeDef = TypedDict(
-    "BatchGetCollectionResponseTypeDef",
+UpdateAccessPolicyResponseTypeDef = TypedDict(
+    "UpdateAccessPolicyResponseTypeDef",
     {
-        "collectionDetails": List[CollectionDetailTypeDef],
-        "collectionErrorDetails": List[CollectionErrorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "accessPolicyDetail": AccessPolicyDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateAccessPolicyResponseTypeDef = TypedDict(
-    "CreateAccessPolicyResponseTypeDef",
+ListAccessPoliciesResponseTypeDef = TypedDict(
+    "ListAccessPoliciesResponseTypeDef",
     {
-        "accessPolicyDetail": AccessPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "accessPolicySummaries": List[AccessPolicySummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetAccessPolicyResponseTypeDef = TypedDict(
-    "GetAccessPolicyResponseTypeDef",
+AccountSettingsDetailTypeDef = TypedDict(
+    "AccountSettingsDetailTypeDef",
     {
-        "accessPolicyDetail": AccessPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "capacityLimits": CapacityLimitsTypeDef,
     },
+    total=False,
 )
 
-ListAccessPoliciesResponseTypeDef = TypedDict(
-    "ListAccessPoliciesResponseTypeDef",
+UpdateAccountSettingsRequestRequestTypeDef = TypedDict(
+    "UpdateAccountSettingsRequestRequestTypeDef",
     {
-        "accessPolicySummaries": List[AccessPolicySummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "capacityLimits": CapacityLimitsTypeDef,
     },
+    total=False,
 )
 
-UpdateAccessPolicyResponseTypeDef = TypedDict(
-    "UpdateAccessPolicyResponseTypeDef",
+BatchGetCollectionResponseTypeDef = TypedDict(
+    "BatchGetCollectionResponseTypeDef",
     {
-        "accessPolicyDetail": AccessPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "collectionDetails": List[CollectionDetailTypeDef],
+        "collectionErrorDetails": List[CollectionErrorDetailTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetVpcEndpointResponseTypeDef = TypedDict(
     "BatchGetVpcEndpointResponseTypeDef",
     {
         "vpcEndpointDetails": List[VpcEndpointDetailTypeDef],
         "vpcEndpointErrorDetails": List[VpcEndpointErrorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCollectionsRequestRequestTypeDef = TypedDict(
     "ListCollectionsRequestRequestTypeDef",
     {
         "collectionFilters": CollectionFiltersTypeDef,
@@ -911,23 +911,23 @@
 )
 
 ListCollectionsResponseTypeDef = TypedDict(
     "ListCollectionsResponseTypeDef",
     {
         "collectionSummaries": List[CollectionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCollectionResponseTypeDef = TypedDict(
     "CreateCollectionResponseTypeDef",
     {
         "createCollectionDetail": CreateCollectionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCollectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCollectionRequestRequestTypeDef",
     {
         "name": str,
@@ -951,15 +951,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1031,84 +1031,84 @@
     pass
 
 
 CreateSecurityPolicyResponseTypeDef = TypedDict(
     "CreateSecurityPolicyResponseTypeDef",
     {
         "securityPolicyDetail": SecurityPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSecurityPolicyResponseTypeDef = TypedDict(
     "GetSecurityPolicyResponseTypeDef",
     {
         "securityPolicyDetail": SecurityPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSecurityPolicyResponseTypeDef = TypedDict(
     "UpdateSecurityPolicyResponseTypeDef",
     {
         "securityPolicyDetail": SecurityPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcEndpointResponseTypeDef = TypedDict(
     "CreateVpcEndpointResponseTypeDef",
     {
         "createVpcEndpointDetail": CreateVpcEndpointDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCollectionResponseTypeDef = TypedDict(
     "DeleteCollectionResponseTypeDef",
     {
         "deleteCollectionDetail": DeleteCollectionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVpcEndpointResponseTypeDef = TypedDict(
     "DeleteVpcEndpointResponseTypeDef",
     {
         "deleteVpcEndpointDetail": DeleteVpcEndpointDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPoliciesStatsResponseTypeDef = TypedDict(
     "GetPoliciesStatsResponseTypeDef",
     {
         "AccessPolicyStats": AccessPolicyStatsTypeDef,
         "SecurityConfigStats": SecurityConfigStatsTypeDef,
         "SecurityPolicyStats": SecurityPolicyStatsTypeDef,
         "TotalPolicyCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityConfigsResponseTypeDef = TypedDict(
     "ListSecurityConfigsResponseTypeDef",
     {
         "nextToken": str,
         "securityConfigSummaries": List[SecurityConfigSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityPoliciesResponseTypeDef = TypedDict(
     "ListSecurityPoliciesResponseTypeDef",
     {
         "nextToken": str,
         "securityPolicySummaries": List[SecurityPolicySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsRequestRequestTypeDef = TypedDict(
     "ListVpcEndpointsRequestRequestTypeDef",
     {
         "maxResults": int,
@@ -1119,66 +1119,66 @@
 )
 
 ListVpcEndpointsResponseTypeDef = TypedDict(
     "ListVpcEndpointsResponseTypeDef",
     {
         "nextToken": str,
         "vpcEndpointSummaries": List[VpcEndpointSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCollectionResponseTypeDef = TypedDict(
     "UpdateCollectionResponseTypeDef",
     {
         "updateCollectionDetail": UpdateCollectionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcEndpointResponseTypeDef = TypedDict(
     "UpdateVpcEndpointResponseTypeDef",
     {
         "UpdateVpcEndpointDetail": UpdateVpcEndpointDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountSettingsResponseTypeDef = TypedDict(
     "GetAccountSettingsResponseTypeDef",
     {
         "accountSettingsDetail": AccountSettingsDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountSettingsResponseTypeDef = TypedDict(
     "UpdateAccountSettingsResponseTypeDef",
     {
         "accountSettingsDetail": AccountSettingsDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSecurityConfigResponseTypeDef = TypedDict(
     "CreateSecurityConfigResponseTypeDef",
     {
         "securityConfigDetail": SecurityConfigDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSecurityConfigResponseTypeDef = TypedDict(
     "GetSecurityConfigResponseTypeDef",
     {
         "securityConfigDetail": SecurityConfigDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSecurityConfigResponseTypeDef = TypedDict(
     "UpdateSecurityConfigResponseTypeDef",
     {
         "securityConfigDetail": SecurityConfigDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless/type_defs.pyi` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,15 +34,14 @@
     "AccessPolicyDetailTypeDef",
     "AccessPolicyStatsTypeDef",
     "AccessPolicySummaryTypeDef",
     "CapacityLimitsTypeDef",
     "BatchGetCollectionRequestRequestTypeDef",
     "CollectionDetailTypeDef",
     "CollectionErrorDetailTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetVpcEndpointRequestRequestTypeDef",
     "VpcEndpointDetailTypeDef",
     "VpcEndpointErrorDetailTypeDef",
     "CollectionFiltersTypeDef",
     "CollectionSummaryTypeDef",
     "CreateAccessPolicyRequestRequestTypeDef",
     "CreateCollectionDetailTypeDef",
@@ -68,28 +67,29 @@
     "ListSecurityConfigsRequestRequestTypeDef",
     "SecurityConfigSummaryTypeDef",
     "ListSecurityPoliciesRequestRequestTypeDef",
     "SecurityPolicySummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "VpcEndpointFiltersTypeDef",
     "VpcEndpointSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAccessPolicyRequestRequestTypeDef",
     "UpdateCollectionDetailTypeDef",
     "UpdateCollectionRequestRequestTypeDef",
     "UpdateSecurityPolicyRequestRequestTypeDef",
     "UpdateVpcEndpointDetailTypeDef",
     "UpdateVpcEndpointRequestRequestTypeDef",
-    "AccountSettingsDetailTypeDef",
-    "UpdateAccountSettingsRequestRequestTypeDef",
-    "BatchGetCollectionResponseTypeDef",
     "CreateAccessPolicyResponseTypeDef",
     "GetAccessPolicyResponseTypeDef",
-    "ListAccessPoliciesResponseTypeDef",
     "UpdateAccessPolicyResponseTypeDef",
+    "ListAccessPoliciesResponseTypeDef",
+    "AccountSettingsDetailTypeDef",
+    "UpdateAccountSettingsRequestRequestTypeDef",
+    "BatchGetCollectionResponseTypeDef",
     "BatchGetVpcEndpointResponseTypeDef",
     "ListCollectionsRequestRequestTypeDef",
     "ListCollectionsResponseTypeDef",
     "CreateCollectionResponseTypeDef",
     "CreateCollectionRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
@@ -194,25 +194,14 @@
         "errorMessage": str,
         "id": str,
         "name": str,
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
 BatchGetVpcEndpointRequestRequestTypeDef = TypedDict(
     "BatchGetVpcEndpointRequestRequestTypeDef",
     {
         "ids": Sequence[str],
     },
 )
 
@@ -669,14 +658,25 @@
         "id": str,
         "name": str,
         "status": VpcEndpointStatusType,
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
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -796,78 +796,78 @@
 )
 
 class UpdateVpcEndpointRequestRequestTypeDef(
     _RequiredUpdateVpcEndpointRequestRequestTypeDef, _OptionalUpdateVpcEndpointRequestRequestTypeDef
 ):
     pass
 
-AccountSettingsDetailTypeDef = TypedDict(
-    "AccountSettingsDetailTypeDef",
+CreateAccessPolicyResponseTypeDef = TypedDict(
+    "CreateAccessPolicyResponseTypeDef",
     {
-        "capacityLimits": CapacityLimitsTypeDef,
+        "accessPolicyDetail": AccessPolicyDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-UpdateAccountSettingsRequestRequestTypeDef = TypedDict(
-    "UpdateAccountSettingsRequestRequestTypeDef",
+GetAccessPolicyResponseTypeDef = TypedDict(
+    "GetAccessPolicyResponseTypeDef",
     {
-        "capacityLimits": CapacityLimitsTypeDef,
+        "accessPolicyDetail": AccessPolicyDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-BatchGetCollectionResponseTypeDef = TypedDict(
-    "BatchGetCollectionResponseTypeDef",
+UpdateAccessPolicyResponseTypeDef = TypedDict(
+    "UpdateAccessPolicyResponseTypeDef",
     {
-        "collectionDetails": List[CollectionDetailTypeDef],
-        "collectionErrorDetails": List[CollectionErrorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "accessPolicyDetail": AccessPolicyDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateAccessPolicyResponseTypeDef = TypedDict(
-    "CreateAccessPolicyResponseTypeDef",
+ListAccessPoliciesResponseTypeDef = TypedDict(
+    "ListAccessPoliciesResponseTypeDef",
     {
-        "accessPolicyDetail": AccessPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "accessPolicySummaries": List[AccessPolicySummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetAccessPolicyResponseTypeDef = TypedDict(
-    "GetAccessPolicyResponseTypeDef",
+AccountSettingsDetailTypeDef = TypedDict(
+    "AccountSettingsDetailTypeDef",
     {
-        "accessPolicyDetail": AccessPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "capacityLimits": CapacityLimitsTypeDef,
     },
+    total=False,
 )
 
-ListAccessPoliciesResponseTypeDef = TypedDict(
-    "ListAccessPoliciesResponseTypeDef",
+UpdateAccountSettingsRequestRequestTypeDef = TypedDict(
+    "UpdateAccountSettingsRequestRequestTypeDef",
     {
-        "accessPolicySummaries": List[AccessPolicySummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "capacityLimits": CapacityLimitsTypeDef,
     },
+    total=False,
 )
 
-UpdateAccessPolicyResponseTypeDef = TypedDict(
-    "UpdateAccessPolicyResponseTypeDef",
+BatchGetCollectionResponseTypeDef = TypedDict(
+    "BatchGetCollectionResponseTypeDef",
     {
-        "accessPolicyDetail": AccessPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "collectionDetails": List[CollectionDetailTypeDef],
+        "collectionErrorDetails": List[CollectionErrorDetailTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetVpcEndpointResponseTypeDef = TypedDict(
     "BatchGetVpcEndpointResponseTypeDef",
     {
         "vpcEndpointDetails": List[VpcEndpointDetailTypeDef],
         "vpcEndpointErrorDetails": List[VpcEndpointErrorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCollectionsRequestRequestTypeDef = TypedDict(
     "ListCollectionsRequestRequestTypeDef",
     {
         "collectionFilters": CollectionFiltersTypeDef,
@@ -878,23 +878,23 @@
 )
 
 ListCollectionsResponseTypeDef = TypedDict(
     "ListCollectionsResponseTypeDef",
     {
         "collectionSummaries": List[CollectionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCollectionResponseTypeDef = TypedDict(
     "CreateCollectionResponseTypeDef",
     {
         "createCollectionDetail": CreateCollectionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCollectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCollectionRequestRequestTypeDef",
     {
         "name": str,
@@ -916,15 +916,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -992,84 +992,84 @@
 ):
     pass
 
 CreateSecurityPolicyResponseTypeDef = TypedDict(
     "CreateSecurityPolicyResponseTypeDef",
     {
         "securityPolicyDetail": SecurityPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSecurityPolicyResponseTypeDef = TypedDict(
     "GetSecurityPolicyResponseTypeDef",
     {
         "securityPolicyDetail": SecurityPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSecurityPolicyResponseTypeDef = TypedDict(
     "UpdateSecurityPolicyResponseTypeDef",
     {
         "securityPolicyDetail": SecurityPolicyDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcEndpointResponseTypeDef = TypedDict(
     "CreateVpcEndpointResponseTypeDef",
     {
         "createVpcEndpointDetail": CreateVpcEndpointDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCollectionResponseTypeDef = TypedDict(
     "DeleteCollectionResponseTypeDef",
     {
         "deleteCollectionDetail": DeleteCollectionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVpcEndpointResponseTypeDef = TypedDict(
     "DeleteVpcEndpointResponseTypeDef",
     {
         "deleteVpcEndpointDetail": DeleteVpcEndpointDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPoliciesStatsResponseTypeDef = TypedDict(
     "GetPoliciesStatsResponseTypeDef",
     {
         "AccessPolicyStats": AccessPolicyStatsTypeDef,
         "SecurityConfigStats": SecurityConfigStatsTypeDef,
         "SecurityPolicyStats": SecurityPolicyStatsTypeDef,
         "TotalPolicyCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityConfigsResponseTypeDef = TypedDict(
     "ListSecurityConfigsResponseTypeDef",
     {
         "nextToken": str,
         "securityConfigSummaries": List[SecurityConfigSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityPoliciesResponseTypeDef = TypedDict(
     "ListSecurityPoliciesResponseTypeDef",
     {
         "nextToken": str,
         "securityPolicySummaries": List[SecurityPolicySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsRequestRequestTypeDef = TypedDict(
     "ListVpcEndpointsRequestRequestTypeDef",
     {
         "maxResults": int,
@@ -1080,66 +1080,66 @@
 )
 
 ListVpcEndpointsResponseTypeDef = TypedDict(
     "ListVpcEndpointsResponseTypeDef",
     {
         "nextToken": str,
         "vpcEndpointSummaries": List[VpcEndpointSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCollectionResponseTypeDef = TypedDict(
     "UpdateCollectionResponseTypeDef",
     {
         "updateCollectionDetail": UpdateCollectionDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcEndpointResponseTypeDef = TypedDict(
     "UpdateVpcEndpointResponseTypeDef",
     {
         "UpdateVpcEndpointDetail": UpdateVpcEndpointDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountSettingsResponseTypeDef = TypedDict(
     "GetAccountSettingsResponseTypeDef",
     {
         "accountSettingsDetail": AccountSettingsDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountSettingsResponseTypeDef = TypedDict(
     "UpdateAccountSettingsResponseTypeDef",
     {
         "accountSettingsDetail": AccountSettingsDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSecurityConfigResponseTypeDef = TypedDict(
     "CreateSecurityConfigResponseTypeDef",
     {
         "securityConfigDetail": SecurityConfigDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSecurityConfigResponseTypeDef = TypedDict(
     "GetSecurityConfigResponseTypeDef",
     {
         "securityConfigDetail": SecurityConfigDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSecurityConfigResponseTypeDef = TypedDict(
     "UpdateSecurityConfigResponseTypeDef",
     {
         "securityConfigDetail": SecurityConfigDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/PKG-INFO` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opensearchserverless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpenSearchServiceServerless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opensearchserverless"></a>
 
 # types-aiobotocore-opensearchserverless
 
 [![PyPI - types-aiobotocore-opensearchserverless](https://img.shields.io/pypi/v/types-aiobotocore-opensearchserverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearchserverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opensearchserverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearchserverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opensearchserverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-opensearchserverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpenSearchServiceServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless)
+[aiobotocore.OpenSearchServiceServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearchserverless.html#OpenSearchServiceServerless)
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
 [types-aiobotocore-opensearchserverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearchserverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -302,15 +302,14 @@
     AccessPolicyDetailTypeDef,
     AccessPolicyStatsTypeDef,
     AccessPolicySummaryTypeDef,
     CapacityLimitsTypeDef,
     BatchGetCollectionRequestRequestTypeDef,
     CollectionDetailTypeDef,
     CollectionErrorDetailTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetVpcEndpointRequestRequestTypeDef,
     VpcEndpointDetailTypeDef,
     VpcEndpointErrorDetailTypeDef,
     CollectionFiltersTypeDef,
     CollectionSummaryTypeDef,
     CreateAccessPolicyRequestRequestTypeDef,
     CreateCollectionDetailTypeDef,
@@ -336,28 +335,29 @@
     ListSecurityConfigsRequestRequestTypeDef,
     SecurityConfigSummaryTypeDef,
     ListSecurityPoliciesRequestRequestTypeDef,
     SecurityPolicySummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     VpcEndpointFiltersTypeDef,
     VpcEndpointSummaryTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAccessPolicyRequestRequestTypeDef,
     UpdateCollectionDetailTypeDef,
     UpdateCollectionRequestRequestTypeDef,
     UpdateSecurityPolicyRequestRequestTypeDef,
     UpdateVpcEndpointDetailTypeDef,
     UpdateVpcEndpointRequestRequestTypeDef,
-    AccountSettingsDetailTypeDef,
-    UpdateAccountSettingsRequestRequestTypeDef,
-    BatchGetCollectionResponseTypeDef,
     CreateAccessPolicyResponseTypeDef,
     GetAccessPolicyResponseTypeDef,
-    ListAccessPoliciesResponseTypeDef,
     UpdateAccessPolicyResponseTypeDef,
+    ListAccessPoliciesResponseTypeDef,
+    AccountSettingsDetailTypeDef,
+    UpdateAccountSettingsRequestRequestTypeDef,
+    BatchGetCollectionResponseTypeDef,
     BatchGetVpcEndpointResponseTypeDef,
     ListCollectionsRequestRequestTypeDef,
     ListCollectionsResponseTypeDef,
     CreateCollectionResponseTypeDef,
     CreateCollectionRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
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

### Comparing `types-aiobotocore-opensearchserverless-2.5.0.post1/types_aiobotocore_opensearchserverless.egg-info/SOURCES.txt` & `types-aiobotocore-opensearchserverless-2.5.1/types_aiobotocore_opensearchserverless.egg-info/SOURCES.txt`

 * *Files identical despite different names*

