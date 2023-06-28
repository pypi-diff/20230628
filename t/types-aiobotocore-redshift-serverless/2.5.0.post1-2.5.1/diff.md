# Comparing `tmp/types-aiobotocore-redshift-serverless-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-redshift-serverless-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-redshift-serverless-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:11 2023, max compression
+gzip compressed data, was "types-aiobotocore-redshift-serverless-2.5.1.tar", last modified: Wed Jun 28 01:44:02 2023, max compression
```

## Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1.tar` & `types-aiobotocore-redshift-serverless-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.119537 types-aiobotocore-redshift-serverless-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18716 2023-03-11 12:27:11.119537 types-aiobotocore-redshift-serverless-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17098 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:11.119537 types-aiobotocore-redshift-serverless-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2199 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.119537 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/
--rw-r--r--   0 runner    (1001) docker     (123)     2008 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2007 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35167 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35111 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9330 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9328 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9964 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9954 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    33742 2023-03-11 12:22:18.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    33711 2023-03-11 12:22:18.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:17.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.119537 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18716 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.906199 types-aiobotocore-redshift-serverless-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18720 2023-06-28 01:44:02.906199 types-aiobotocore-redshift-serverless-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17108 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:02.906199 types-aiobotocore-redshift-serverless-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2193 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.902199 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/
+-rw-r--r--   0 runner    (1001) docker     (123)     2008 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2007 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35167 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35111 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9611 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9609 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9858 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9849 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    33830 2023-06-28 01:39:04.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33799 2023-06-28 01:39:03.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.906199 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18720 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/LICENSE` & `types-aiobotocore-redshift-serverless-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/PKG-INFO` & `types-aiobotocore-redshift-serverless-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-redshift-serverless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RedshiftServerless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RedshiftServerless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-redshift-serverless"></a>
 
 # types-aiobotocore-redshift-serverless
 
 [![PyPI - types-aiobotocore-redshift-serverless](https://img.shields.io/pypi/v/types-aiobotocore-redshift-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-serverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-redshift-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-serverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-redshift-serverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-redshift-serverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RedshiftServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless)
+[aiobotocore.RedshiftServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless)
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
 [types-aiobotocore-redshift-serverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -351,66 +351,73 @@
 `types_aiobotocore_redshift_serverless.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_redshift_serverless.type_defs import (
     ConfigParameterTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     SnapshotTypeDef,
     CreateEndpointAccessRequestRequestTypeDef,
     NamespaceTypeDef,
     CreateUsageLimitRequestRequestTypeDef,
     UsageLimitTypeDef,
     DeleteEndpointAccessRequestRequestTypeDef,
     DeleteNamespaceRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
     DeleteUsageLimitRequestRequestTypeDef,
     DeleteWorkgroupRequestRequestTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     GetCredentialsRequestRequestTypeDef,
+    GetCredentialsResponseTypeDef,
     GetEndpointAccessRequestRequestTypeDef,
     GetNamespaceRequestRequestTypeDef,
     GetRecoveryPointRequestRequestTypeDef,
     RecoveryPointTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
     ResourcePolicyTypeDef,
     GetSnapshotRequestRequestTypeDef,
     GetTableRestoreStatusRequestRequestTypeDef,
     TableRestoreStatusTypeDef,
     GetUsageLimitRequestRequestTypeDef,
     GetWorkgroupRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListEndpointAccessRequestListEndpointAccessPaginateTypeDef,
     ListEndpointAccessRequestRequestTypeDef,
+    ListNamespacesRequestListNamespacesPaginateTypeDef,
     ListNamespacesRequestRequestTypeDef,
+    ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef,
     ListRecoveryPointsRequestRequestTypeDef,
+    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
     ListSnapshotsRequestRequestTypeDef,
+    ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef,
     ListTableRestoreStatusRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsageLimitsRequestListUsageLimitsPaginateTypeDef,
     ListUsageLimitsRequestRequestTypeDef,
+    ListWorkgroupsRequestListWorkgroupsPaginateTypeDef,
     ListWorkgroupsRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreFromRecoveryPointRequestRequestTypeDef,
     RestoreFromSnapshotRequestRequestTypeDef,
     RestoreTableFromSnapshotRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateEndpointAccessRequestRequestTypeDef,
     UpdateNamespaceRequestRequestTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     UpdateUsageLimitRequestRequestTypeDef,
     UpdateWorkgroupRequestRequestTypeDef,
     ConvertRecoveryPointToSnapshotRequestRequestTypeDef,
     CreateNamespaceRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateWorkgroupRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    GetCredentialsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ConvertRecoveryPointToSnapshotResponseTypeDef,
     CreateSnapshotResponseTypeDef,
     DeleteSnapshotResponseTypeDef,
     GetSnapshotResponseTypeDef,
     ListSnapshotsResponseTypeDef,
     UpdateSnapshotResponseTypeDef,
     CreateNamespaceResponseTypeDef,
@@ -428,21 +435,14 @@
     GetRecoveryPointResponseTypeDef,
     ListRecoveryPointsResponseTypeDef,
     GetResourcePolicyResponseTypeDef,
     PutResourcePolicyResponseTypeDef,
     GetTableRestoreStatusResponseTypeDef,
     ListTableRestoreStatusResponseTypeDef,
     RestoreTableFromSnapshotResponseTypeDef,
-    ListEndpointAccessRequestListEndpointAccessPaginateTypeDef,
-    ListNamespacesRequestListNamespacesPaginateTypeDef,
-    ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef,
-    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef,
-    ListUsageLimitsRequestListUsageLimitsPaginateTypeDef,
-    ListWorkgroupsRequestListWorkgroupsPaginateTypeDef,
     VpcEndpointTypeDef,
     EndpointAccessTypeDef,
     EndpointTypeDef,
     CreateEndpointAccessResponseTypeDef,
     DeleteEndpointAccessResponseTypeDef,
     GetEndpointAccessResponseTypeDef,
     ListEndpointAccessResponseTypeDef,
@@ -463,43 +463,43 @@
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

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/README.md` & `types-aiobotocore-redshift-serverless-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-redshift-serverless"></a>
 
 # types-aiobotocore-redshift-serverless
 
 [![PyPI - types-aiobotocore-redshift-serverless](https://img.shields.io/pypi/v/types-aiobotocore-redshift-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-serverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-redshift-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-serverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-redshift-serverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-redshift-serverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RedshiftServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless)
+[aiobotocore.RedshiftServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless)
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
 [types-aiobotocore-redshift-serverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,66 +318,73 @@
 `types_aiobotocore_redshift_serverless.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_redshift_serverless.type_defs import (
     ConfigParameterTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     SnapshotTypeDef,
     CreateEndpointAccessRequestRequestTypeDef,
     NamespaceTypeDef,
     CreateUsageLimitRequestRequestTypeDef,
     UsageLimitTypeDef,
     DeleteEndpointAccessRequestRequestTypeDef,
     DeleteNamespaceRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
     DeleteUsageLimitRequestRequestTypeDef,
     DeleteWorkgroupRequestRequestTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     GetCredentialsRequestRequestTypeDef,
+    GetCredentialsResponseTypeDef,
     GetEndpointAccessRequestRequestTypeDef,
     GetNamespaceRequestRequestTypeDef,
     GetRecoveryPointRequestRequestTypeDef,
     RecoveryPointTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
     ResourcePolicyTypeDef,
     GetSnapshotRequestRequestTypeDef,
     GetTableRestoreStatusRequestRequestTypeDef,
     TableRestoreStatusTypeDef,
     GetUsageLimitRequestRequestTypeDef,
     GetWorkgroupRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListEndpointAccessRequestListEndpointAccessPaginateTypeDef,
     ListEndpointAccessRequestRequestTypeDef,
+    ListNamespacesRequestListNamespacesPaginateTypeDef,
     ListNamespacesRequestRequestTypeDef,
+    ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef,
     ListRecoveryPointsRequestRequestTypeDef,
+    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
     ListSnapshotsRequestRequestTypeDef,
+    ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef,
     ListTableRestoreStatusRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsageLimitsRequestListUsageLimitsPaginateTypeDef,
     ListUsageLimitsRequestRequestTypeDef,
+    ListWorkgroupsRequestListWorkgroupsPaginateTypeDef,
     ListWorkgroupsRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreFromRecoveryPointRequestRequestTypeDef,
     RestoreFromSnapshotRequestRequestTypeDef,
     RestoreTableFromSnapshotRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateEndpointAccessRequestRequestTypeDef,
     UpdateNamespaceRequestRequestTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     UpdateUsageLimitRequestRequestTypeDef,
     UpdateWorkgroupRequestRequestTypeDef,
     ConvertRecoveryPointToSnapshotRequestRequestTypeDef,
     CreateNamespaceRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateWorkgroupRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    GetCredentialsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ConvertRecoveryPointToSnapshotResponseTypeDef,
     CreateSnapshotResponseTypeDef,
     DeleteSnapshotResponseTypeDef,
     GetSnapshotResponseTypeDef,
     ListSnapshotsResponseTypeDef,
     UpdateSnapshotResponseTypeDef,
     CreateNamespaceResponseTypeDef,
@@ -395,21 +402,14 @@
     GetRecoveryPointResponseTypeDef,
     ListRecoveryPointsResponseTypeDef,
     GetResourcePolicyResponseTypeDef,
     PutResourcePolicyResponseTypeDef,
     GetTableRestoreStatusResponseTypeDef,
     ListTableRestoreStatusResponseTypeDef,
     RestoreTableFromSnapshotResponseTypeDef,
-    ListEndpointAccessRequestListEndpointAccessPaginateTypeDef,
-    ListNamespacesRequestListNamespacesPaginateTypeDef,
-    ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef,
-    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef,
-    ListUsageLimitsRequestListUsageLimitsPaginateTypeDef,
-    ListWorkgroupsRequestListWorkgroupsPaginateTypeDef,
     VpcEndpointTypeDef,
     EndpointAccessTypeDef,
     EndpointTypeDef,
     CreateEndpointAccessResponseTypeDef,
     DeleteEndpointAccessResponseTypeDef,
     GetEndpointAccessResponseTypeDef,
     ListEndpointAccessResponseTypeDef,
@@ -430,43 +430,43 @@
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

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/setup.py` & `types-aiobotocore-redshift-serverless-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-redshift-serverless.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-redshift-serverless",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_redshift_serverless"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RedshiftServerless 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.RedshiftServerless 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/",
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

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/__init__.py` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/__init__.pyi` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/__main__.py` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RedshiftServerless 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RedshiftServerless 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless\nOther"
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

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/client.py` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/client.pyi` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/literals.py` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -115,14 +115,15 @@
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
@@ -201,14 +202,15 @@
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
@@ -219,14 +221,15 @@
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
@@ -262,14 +265,15 @@
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
@@ -288,16 +292,19 @@
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
@@ -381,15 +388,17 @@
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
@@ -419,17 +428,21 @@
     "list_table_restore_status",
     "list_usage_limits",
     "list_workgroups",
 ]
 RegionName = Literal[
     "ap-northeast-1",
     "ap-northeast-2",
+    "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
     "eu-west-2",
+    "eu-west-3",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/literals.pyi` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -113,14 +113,15 @@
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
@@ -199,14 +200,15 @@
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
@@ -217,14 +219,15 @@
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
@@ -260,14 +263,15 @@
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
@@ -286,16 +290,19 @@
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
@@ -379,15 +386,17 @@
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
@@ -417,17 +426,21 @@
     "list_table_restore_status",
     "list_usage_limits",
     "list_workgroups",
 ]
 RegionName = Literal[
     "ap-northeast-1",
     "ap-northeast-2",
+    "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
     "eu-west-2",
+    "eu-west-3",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/paginator.py` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,17 +28,16 @@
         list_recovery_points_paginator: ListRecoveryPointsPaginator = client.get_paginator("list_recovery_points")
         list_snapshots_paginator: ListSnapshotsPaginator = client.get_paginator("list_snapshots")
         list_table_restore_status_paginator: ListTableRestoreStatusPaginator = client.get_paginator("list_table_restore_status")
         list_usage_limits_paginator: ListUsageLimitsPaginator = client.get_paginator("list_usage_limits")
         list_workgroups_paginator: ListWorkgroupsPaginator = client.get_paginator("list_workgroups")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import UsageLimitUsageTypeType
 from .type_defs import (
     ListEndpointAccessResponseTypeDef,
@@ -47,162 +46,147 @@
     ListSnapshotsResponseTypeDef,
     ListTableRestoreStatusResponseTypeDef,
     ListUsageLimitsResponseTypeDef,
     ListWorkgroupsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListEndpointAccessPaginator",
     "ListNamespacesPaginator",
     "ListRecoveryPointsPaginator",
     "ListSnapshotsPaginator",
     "ListTableRestoreStatusPaginator",
     "ListUsageLimitsPaginator",
     "ListWorkgroupsPaginator",
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
 class ListEndpointAccessPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListEndpointAccess)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listendpointaccesspaginator)
     """
 
     def paginate(
         self,
         *,
         vpcId: str = ...,
         workgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointAccessResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListEndpointAccess.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listendpointaccesspaginator)
         """
 
-
 class ListNamespacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListNamespaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listnamespacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNamespacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListNamespaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listnamespacespaginator)
         """
 
-
 class ListRecoveryPointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListRecoveryPoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listrecoverypointspaginator)
     """
 
     def paginate(
         self,
         *,
         endTime: Union[datetime, str] = ...,
         namespaceArn: str = ...,
         namespaceName: str = ...,
         startTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListRecoveryPoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listrecoverypointspaginator)
         """
 
-
 class ListSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listsnapshotspaginator)
     """
 
     def paginate(
         self,
         *,
         endTime: Union[datetime, str] = ...,
         namespaceArn: str = ...,
         namespaceName: str = ...,
         ownerAccount: str = ...,
         startTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listsnapshotspaginator)
         """
 
-
 class ListTableRestoreStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListTableRestoreStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listtablerestorestatuspaginator)
     """
 
     def paginate(
         self,
         *,
         namespaceName: str = ...,
         workgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableRestoreStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListTableRestoreStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listtablerestorestatuspaginator)
         """
 
-
 class ListUsageLimitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListUsageLimits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listusagelimitspaginator)
     """
 
     def paginate(
         self,
         *,
         resourceArn: str = ...,
         usageType: UsageLimitUsageTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsageLimitsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListUsageLimits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listusagelimitspaginator)
         """
 
-
 class ListWorkgroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListWorkgroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listworkgroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkgroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListWorkgroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listworkgroupspaginator)
         """
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/paginator.pyi` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,17 +28,16 @@
         list_recovery_points_paginator: ListRecoveryPointsPaginator = client.get_paginator("list_recovery_points")
         list_snapshots_paginator: ListSnapshotsPaginator = client.get_paginator("list_snapshots")
         list_table_restore_status_paginator: ListTableRestoreStatusPaginator = client.get_paginator("list_table_restore_status")
         list_usage_limits_paginator: ListUsageLimitsPaginator = client.get_paginator("list_usage_limits")
         list_workgroups_paginator: ListWorkgroupsPaginator = client.get_paginator("list_workgroups")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import UsageLimitUsageTypeType
 from .type_defs import (
     ListEndpointAccessResponseTypeDef,
@@ -47,152 +46,156 @@
     ListSnapshotsResponseTypeDef,
     ListTableRestoreStatusResponseTypeDef,
     ListUsageLimitsResponseTypeDef,
     ListWorkgroupsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListEndpointAccessPaginator",
     "ListNamespacesPaginator",
     "ListRecoveryPointsPaginator",
     "ListSnapshotsPaginator",
     "ListTableRestoreStatusPaginator",
     "ListUsageLimitsPaginator",
     "ListWorkgroupsPaginator",
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
 class ListEndpointAccessPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListEndpointAccess)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listendpointaccesspaginator)
     """
 
     def paginate(
         self,
         *,
         vpcId: str = ...,
         workgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointAccessResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListEndpointAccess.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listendpointaccesspaginator)
         """
 
+
 class ListNamespacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListNamespaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listnamespacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNamespacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListNamespaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listnamespacespaginator)
         """
 
+
 class ListRecoveryPointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListRecoveryPoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listrecoverypointspaginator)
     """
 
     def paginate(
         self,
         *,
         endTime: Union[datetime, str] = ...,
         namespaceArn: str = ...,
         namespaceName: str = ...,
         startTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListRecoveryPoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listrecoverypointspaginator)
         """
 
+
 class ListSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listsnapshotspaginator)
     """
 
     def paginate(
         self,
         *,
         endTime: Union[datetime, str] = ...,
         namespaceArn: str = ...,
         namespaceName: str = ...,
         ownerAccount: str = ...,
         startTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listsnapshotspaginator)
         """
 
+
 class ListTableRestoreStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListTableRestoreStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listtablerestorestatuspaginator)
     """
 
     def paginate(
         self,
         *,
         namespaceName: str = ...,
         workgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableRestoreStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListTableRestoreStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listtablerestorestatuspaginator)
         """
 
+
 class ListUsageLimitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListUsageLimits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listusagelimitspaginator)
     """
 
     def paginate(
         self,
         *,
         resourceArn: str = ...,
         usageType: UsageLimitUsageTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsageLimitsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListUsageLimits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listusagelimitspaginator)
         """
 
+
 class ListWorkgroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListWorkgroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listworkgroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkgroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless.Paginator.ListWorkgroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/paginators/#listworkgroupspaginator)
         """
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/type_defs.py` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/type_defs.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -26,70 +26,76 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ConfigParameterTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "SnapshotTypeDef",
     "CreateEndpointAccessRequestRequestTypeDef",
     "NamespaceTypeDef",
     "CreateUsageLimitRequestRequestTypeDef",
     "UsageLimitTypeDef",
     "DeleteEndpointAccessRequestRequestTypeDef",
     "DeleteNamespaceRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
     "DeleteUsageLimitRequestRequestTypeDef",
     "DeleteWorkgroupRequestRequestTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "GetCredentialsRequestRequestTypeDef",
+    "GetCredentialsResponseTypeDef",
     "GetEndpointAccessRequestRequestTypeDef",
     "GetNamespaceRequestRequestTypeDef",
     "GetRecoveryPointRequestRequestTypeDef",
     "RecoveryPointTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
     "ResourcePolicyTypeDef",
     "GetSnapshotRequestRequestTypeDef",
     "GetTableRestoreStatusRequestRequestTypeDef",
     "TableRestoreStatusTypeDef",
     "GetUsageLimitRequestRequestTypeDef",
     "GetWorkgroupRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
     "ListEndpointAccessRequestRequestTypeDef",
+    "ListNamespacesRequestListNamespacesPaginateTypeDef",
     "ListNamespacesRequestRequestTypeDef",
+    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
     "ListRecoveryPointsRequestRequestTypeDef",
+    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
     "ListSnapshotsRequestRequestTypeDef",
+    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
     "ListTableRestoreStatusRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
     "ListUsageLimitsRequestRequestTypeDef",
+    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
     "ListWorkgroupsRequestRequestTypeDef",
     "NetworkInterfaceTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreFromRecoveryPointRequestRequestTypeDef",
     "RestoreFromSnapshotRequestRequestTypeDef",
     "RestoreTableFromSnapshotRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateEndpointAccessRequestRequestTypeDef",
     "UpdateNamespaceRequestRequestTypeDef",
     "UpdateSnapshotRequestRequestTypeDef",
     "UpdateUsageLimitRequestRequestTypeDef",
     "UpdateWorkgroupRequestRequestTypeDef",
     "ConvertRecoveryPointToSnapshotRequestRequestTypeDef",
     "CreateNamespaceRequestRequestTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "CreateWorkgroupRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "GetCredentialsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ConvertRecoveryPointToSnapshotResponseTypeDef",
     "CreateSnapshotResponseTypeDef",
     "DeleteSnapshotResponseTypeDef",
     "GetSnapshotResponseTypeDef",
     "ListSnapshotsResponseTypeDef",
     "UpdateSnapshotResponseTypeDef",
     "CreateNamespaceResponseTypeDef",
@@ -107,21 +113,14 @@
     "GetRecoveryPointResponseTypeDef",
     "ListRecoveryPointsResponseTypeDef",
     "GetResourcePolicyResponseTypeDef",
     "PutResourcePolicyResponseTypeDef",
     "GetTableRestoreStatusResponseTypeDef",
     "ListTableRestoreStatusResponseTypeDef",
     "RestoreTableFromSnapshotResponseTypeDef",
-    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
-    "ListNamespacesRequestListNamespacesPaginateTypeDef",
-    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
-    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
-    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
-    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
     "VpcEndpointTypeDef",
     "EndpointAccessTypeDef",
     "EndpointTypeDef",
     "CreateEndpointAccessResponseTypeDef",
     "DeleteEndpointAccessResponseTypeDef",
     "GetEndpointAccessResponseTypeDef",
     "ListEndpointAccessResponseTypeDef",
@@ -147,25 +146,14 @@
     "TagTypeDef",
     {
         "key": str,
         "value": str,
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
 SnapshotTypeDef = TypedDict(
     "SnapshotTypeDef",
     {
         "accountsWithProvisionedRestoreAccess": List[str],
         "accountsWithRestoreAccess": List[str],
         "actualIncrementalBackupSizeInMegaBytes": float,
         "adminUsername": str,
@@ -201,22 +189,20 @@
     "_OptionalCreateEndpointAccessRequestRequestTypeDef",
     {
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class CreateEndpointAccessRequestRequestTypeDef(
     _RequiredCreateEndpointAccessRequestRequestTypeDef,
     _OptionalCreateEndpointAccessRequestRequestTypeDef,
 ):
     pass
 
-
 NamespaceTypeDef = TypedDict(
     "NamespaceTypeDef",
     {
         "adminUsername": str,
         "creationDate": datetime,
         "dbName": str,
         "defaultIamRoleArn": str,
@@ -244,21 +230,19 @@
     {
         "breachAction": UsageLimitBreachActionType,
         "period": UsageLimitPeriodType,
     },
     total=False,
 )
 
-
 class CreateUsageLimitRequestRequestTypeDef(
     _RequiredCreateUsageLimitRequestRequestTypeDef, _OptionalCreateUsageLimitRequestRequestTypeDef
 ):
     pass
 
-
 UsageLimitTypeDef = TypedDict(
     "UsageLimitTypeDef",
     {
         "amount": int,
         "breachAction": UsageLimitBreachActionType,
         "period": UsageLimitPeriodType,
         "resourceArn": str,
@@ -287,21 +271,19 @@
     {
         "finalSnapshotName": str,
         "finalSnapshotRetentionPeriod": int,
     },
     total=False,
 )
 
-
 class DeleteNamespaceRequestRequestTypeDef(
     _RequiredDeleteNamespaceRequestRequestTypeDef, _OptionalDeleteNamespaceRequestRequestTypeDef
 ):
     pass
 
-
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
@@ -346,20 +328,29 @@
     {
         "dbName": str,
         "durationSeconds": int,
     },
     total=False,
 )
 
-
 class GetCredentialsRequestRequestTypeDef(
     _RequiredGetCredentialsRequestRequestTypeDef, _OptionalGetCredentialsRequestRequestTypeDef
 ):
     pass
 
+GetCredentialsResponseTypeDef = TypedDict(
+    "GetCredentialsResponseTypeDef",
+    {
+        "dbPassword": str,
+        "dbUser": str,
+        "expiration": datetime,
+        "nextRefreshTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 GetEndpointAccessRequestRequestTypeDef = TypedDict(
     "GetEndpointAccessRequestRequestTypeDef",
     {
         "endpointName": str,
     },
 )
@@ -456,20 +447,20 @@
 GetWorkgroupRequestRequestTypeDef = TypedDict(
     "GetWorkgroupRequestRequestTypeDef",
     {
         "workgroupName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListEndpointAccessRequestListEndpointAccessPaginateTypeDef = TypedDict(
+    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "vpcId": str,
+        "workgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEndpointAccessRequestRequestTypeDef = TypedDict(
     "ListEndpointAccessRequestRequestTypeDef",
     {
@@ -477,50 +468,93 @@
         "nextToken": str,
         "vpcId": str,
         "workgroupName": str,
     },
     total=False,
 )
 
+ListNamespacesRequestListNamespacesPaginateTypeDef = TypedDict(
+    "ListNamespacesRequestListNamespacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListNamespacesRequestRequestTypeDef = TypedDict(
     "ListNamespacesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef = TypedDict(
+    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
+    {
+        "endTime": Union[datetime, str],
+        "namespaceArn": str,
+        "namespaceName": str,
+        "startTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecoveryPointsRequestRequestTypeDef = TypedDict(
     "ListRecoveryPointsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "maxResults": int,
         "namespaceArn": str,
         "namespaceName": str,
         "nextToken": str,
         "startTime": Union[datetime, str],
     },
     total=False,
 )
 
+ListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
+    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
+    {
+        "endTime": Union[datetime, str],
+        "namespaceArn": str,
+        "namespaceName": str,
+        "ownerAccount": str,
+        "startTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSnapshotsRequestRequestTypeDef = TypedDict(
     "ListSnapshotsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "maxResults": int,
         "namespaceArn": str,
         "namespaceName": str,
         "nextToken": str,
         "ownerAccount": str,
         "startTime": Union[datetime, str],
     },
     total=False,
 )
 
+ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef = TypedDict(
+    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
+    {
+        "namespaceName": str,
+        "workgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTableRestoreStatusRequestRequestTypeDef = TypedDict(
     "ListTableRestoreStatusRequestRequestTypeDef",
     {
         "maxResults": int,
         "namespaceName": str,
         "nextToken": str,
         "workgroupName": str,
@@ -531,25 +565,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListUsageLimitsRequestListUsageLimitsPaginateTypeDef = TypedDict(
+    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
+    {
+        "resourceArn": str,
+        "usageType": UsageLimitUsageTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListUsageLimitsRequestRequestTypeDef = TypedDict(
     "ListUsageLimitsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "resourceArn": str,
         "usageType": UsageLimitUsageTypeType,
     },
     total=False,
 )
 
+ListWorkgroupsRequestListWorkgroupsPaginateTypeDef = TypedDict(
+    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkgroupsRequestRequestTypeDef = TypedDict(
     "ListWorkgroupsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -562,22 +614,43 @@
         "networkInterfaceId": str,
         "privateIpAddress": str,
         "subnetId": str,
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
 PutResourcePolicyRequestRequestTypeDef = TypedDict(
     "PutResourcePolicyRequestRequestTypeDef",
     {
         "policy": str,
         "resourceArn": str,
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
 RestoreFromRecoveryPointRequestRequestTypeDef = TypedDict(
     "RestoreFromRecoveryPointRequestRequestTypeDef",
     {
         "namespaceName": str,
         "recoveryPointId": str,
         "workgroupName": str,
     },
@@ -596,22 +669,20 @@
         "ownerAccount": str,
         "snapshotArn": str,
         "snapshotName": str,
     },
     total=False,
 )
 
-
 class RestoreFromSnapshotRequestRequestTypeDef(
     _RequiredRestoreFromSnapshotRequestRequestTypeDef,
     _OptionalRestoreFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredRestoreTableFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreTableFromSnapshotRequestRequestTypeDef",
     {
         "namespaceName": str,
         "newTableName": str,
         "snapshotName": str,
         "sourceDatabaseName": str,
@@ -626,22 +697,20 @@
         "sourceSchemaName": str,
         "targetDatabaseName": str,
         "targetSchemaName": str,
     },
     total=False,
 )
 
-
 class RestoreTableFromSnapshotRequestRequestTypeDef(
     _RequiredRestoreTableFromSnapshotRequestRequestTypeDef,
     _OptionalRestoreTableFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -656,22 +725,20 @@
     "_OptionalUpdateEndpointAccessRequestRequestTypeDef",
     {
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateEndpointAccessRequestRequestTypeDef(
     _RequiredUpdateEndpointAccessRequestRequestTypeDef,
     _OptionalUpdateEndpointAccessRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateNamespaceRequestRequestTypeDef",
     {
         "namespaceName": str,
     },
 )
 _OptionalUpdateNamespaceRequestRequestTypeDef = TypedDict(
@@ -683,42 +750,38 @@
         "iamRoles": Sequence[str],
         "kmsKeyId": str,
         "logExports": Sequence[LogExportType],
     },
     total=False,
 )
 
-
 class UpdateNamespaceRequestRequestTypeDef(
     _RequiredUpdateNamespaceRequestRequestTypeDef, _OptionalUpdateNamespaceRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSnapshotRequestRequestTypeDef",
     {
         "snapshotName": str,
     },
 )
 _OptionalUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateSnapshotRequestRequestTypeDef",
     {
         "retentionPeriod": int,
     },
     total=False,
 )
 
-
 class UpdateSnapshotRequestRequestTypeDef(
     _RequiredUpdateSnapshotRequestRequestTypeDef, _OptionalUpdateSnapshotRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateUsageLimitRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUsageLimitRequestRequestTypeDef",
     {
         "usageLimitId": str,
     },
 )
 _OptionalUpdateUsageLimitRequestRequestTypeDef = TypedDict(
@@ -726,21 +789,19 @@
     {
         "amount": int,
         "breachAction": UsageLimitBreachActionType,
     },
     total=False,
 )
 
-
 class UpdateUsageLimitRequestRequestTypeDef(
     _RequiredUpdateUsageLimitRequestRequestTypeDef, _OptionalUpdateUsageLimitRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateWorkgroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkgroupRequestRequestTypeDef",
     {
         "workgroupName": str,
     },
 )
 _OptionalUpdateWorkgroupRequestRequestTypeDef = TypedDict(
@@ -753,21 +814,19 @@
         "publiclyAccessible": bool,
         "securityGroupIds": Sequence[str],
         "subnetIds": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateWorkgroupRequestRequestTypeDef(
     _RequiredUpdateWorkgroupRequestRequestTypeDef, _OptionalUpdateWorkgroupRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredConvertRecoveryPointToSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredConvertRecoveryPointToSnapshotRequestRequestTypeDef",
     {
         "recoveryPointId": str,
         "snapshotName": str,
     },
 )
@@ -776,22 +835,20 @@
     {
         "retentionPeriod": int,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class ConvertRecoveryPointToSnapshotRequestRequestTypeDef(
     _RequiredConvertRecoveryPointToSnapshotRequestRequestTypeDef,
     _OptionalConvertRecoveryPointToSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNamespaceRequestRequestTypeDef",
     {
         "namespaceName": str,
     },
 )
 _OptionalCreateNamespaceRequestRequestTypeDef = TypedDict(
@@ -805,21 +862,19 @@
         "kmsKeyId": str,
         "logExports": Sequence[LogExportType],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateNamespaceRequestRequestTypeDef(
     _RequiredCreateNamespaceRequestRequestTypeDef, _OptionalCreateNamespaceRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSnapshotRequestRequestTypeDef",
     {
         "namespaceName": str,
         "snapshotName": str,
     },
 )
@@ -828,21 +883,19 @@
     {
         "retentionPeriod": int,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateSnapshotRequestRequestTypeDef(
     _RequiredCreateSnapshotRequestRequestTypeDef, _OptionalCreateSnapshotRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateWorkgroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkgroupRequestRequestTypeDef",
     {
         "namespaceName": str,
         "workgroupName": str,
     },
 )
@@ -857,327 +910,243 @@
         "securityGroupIds": Sequence[str],
         "subnetIds": Sequence[str],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateWorkgroupRequestRequestTypeDef(
     _RequiredCreateWorkgroupRequestRequestTypeDef, _OptionalCreateWorkgroupRequestRequestTypeDef
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
 
-GetCredentialsResponseTypeDef = TypedDict(
-    "GetCredentialsResponseTypeDef",
-    {
-        "dbPassword": str,
-        "dbUser": str,
-        "expiration": datetime,
-        "nextRefreshTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ConvertRecoveryPointToSnapshotResponseTypeDef = TypedDict(
     "ConvertRecoveryPointToSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResponseTypeDef = TypedDict(
     "CreateSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSnapshotResponseTypeDef = TypedDict(
     "DeleteSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotResponseTypeDef = TypedDict(
     "GetSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSnapshotsResponseTypeDef = TypedDict(
     "ListSnapshotsResponseTypeDef",
     {
         "nextToken": str,
         "snapshots": List[SnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSnapshotResponseTypeDef = TypedDict(
     "UpdateSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNamespaceResponseTypeDef = TypedDict(
     "CreateNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNamespaceResponseTypeDef = TypedDict(
     "DeleteNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNamespaceResponseTypeDef = TypedDict(
     "GetNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNamespacesResponseTypeDef = TypedDict(
     "ListNamespacesResponseTypeDef",
     {
         "namespaces": List[NamespaceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreFromRecoveryPointResponseTypeDef = TypedDict(
     "RestoreFromRecoveryPointResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
         "recoveryPointId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreFromSnapshotResponseTypeDef = TypedDict(
     "RestoreFromSnapshotResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
         "ownerAccount": str,
         "snapshotName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNamespaceResponseTypeDef = TypedDict(
     "UpdateNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUsageLimitResponseTypeDef = TypedDict(
     "CreateUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteUsageLimitResponseTypeDef = TypedDict(
     "DeleteUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUsageLimitResponseTypeDef = TypedDict(
     "GetUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsageLimitsResponseTypeDef = TypedDict(
     "ListUsageLimitsResponseTypeDef",
     {
         "nextToken": str,
         "usageLimits": List[UsageLimitTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUsageLimitResponseTypeDef = TypedDict(
     "UpdateUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecoveryPointResponseTypeDef = TypedDict(
     "GetRecoveryPointResponseTypeDef",
     {
         "recoveryPoint": RecoveryPointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryPointsResponseTypeDef = TypedDict(
     "ListRecoveryPointsResponseTypeDef",
     {
         "nextToken": str,
         "recoveryPoints": List[RecoveryPointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcePolicyResponseTypeDef = TypedDict(
     "GetResourcePolicyResponseTypeDef",
     {
         "resourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourcePolicyResponseTypeDef = TypedDict(
     "PutResourcePolicyResponseTypeDef",
     {
         "resourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableRestoreStatusResponseTypeDef = TypedDict(
     "GetTableRestoreStatusResponseTypeDef",
     {
         "tableRestoreStatus": TableRestoreStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTableRestoreStatusResponseTypeDef = TypedDict(
     "ListTableRestoreStatusResponseTypeDef",
     {
         "nextToken": str,
         "tableRestoreStatuses": List[TableRestoreStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreTableFromSnapshotResponseTypeDef = TypedDict(
     "RestoreTableFromSnapshotResponseTypeDef",
     {
         "tableRestoreStatus": TableRestoreStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListEndpointAccessRequestListEndpointAccessPaginateTypeDef = TypedDict(
-    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
-    {
-        "vpcId": str,
-        "workgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListNamespacesRequestListNamespacesPaginateTypeDef = TypedDict(
-    "ListNamespacesRequestListNamespacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef = TypedDict(
-    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
-    {
-        "endTime": Union[datetime, str],
-        "namespaceArn": str,
-        "namespaceName": str,
-        "startTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
-    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    {
-        "endTime": Union[datetime, str],
-        "namespaceArn": str,
-        "namespaceName": str,
-        "ownerAccount": str,
-        "startTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef = TypedDict(
-    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
-    {
-        "namespaceName": str,
-        "workgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListUsageLimitsRequestListUsageLimitsPaginateTypeDef = TypedDict(
-    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
-    {
-        "resourceArn": str,
-        "usageType": UsageLimitUsageTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkgroupsRequestListWorkgroupsPaginateTypeDef = TypedDict(
-    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 VpcEndpointTypeDef = TypedDict(
     "VpcEndpointTypeDef",
     {
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "vpcEndpointId": str,
         "vpcId": str,
     },
@@ -1211,48 +1180,48 @@
     total=False,
 )
 
 CreateEndpointAccessResponseTypeDef = TypedDict(
     "CreateEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEndpointAccessResponseTypeDef = TypedDict(
     "DeleteEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEndpointAccessResponseTypeDef = TypedDict(
     "GetEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEndpointAccessResponseTypeDef = TypedDict(
     "ListEndpointAccessResponseTypeDef",
     {
         "endpoints": List[EndpointAccessTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointAccessResponseTypeDef = TypedDict(
     "UpdateEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkgroupTypeDef = TypedDict(
     "WorkgroupTypeDef",
     {
         "baseCapacity": int,
@@ -1273,43 +1242,43 @@
     total=False,
 )
 
 CreateWorkgroupResponseTypeDef = TypedDict(
     "CreateWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteWorkgroupResponseTypeDef = TypedDict(
     "DeleteWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkgroupResponseTypeDef = TypedDict(
     "GetWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkgroupsResponseTypeDef = TypedDict(
     "ListWorkgroupsResponseTypeDef",
     {
         "nextToken": str,
         "workgroups": List[WorkgroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkgroupResponseTypeDef = TypedDict(
     "UpdateWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless/type_defs.pyi` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless/type_defs.py`

 * *Files 18% similar despite different names*

```diff
@@ -26,69 +26,77 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ConfigParameterTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "SnapshotTypeDef",
     "CreateEndpointAccessRequestRequestTypeDef",
     "NamespaceTypeDef",
     "CreateUsageLimitRequestRequestTypeDef",
     "UsageLimitTypeDef",
     "DeleteEndpointAccessRequestRequestTypeDef",
     "DeleteNamespaceRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
     "DeleteUsageLimitRequestRequestTypeDef",
     "DeleteWorkgroupRequestRequestTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "GetCredentialsRequestRequestTypeDef",
+    "GetCredentialsResponseTypeDef",
     "GetEndpointAccessRequestRequestTypeDef",
     "GetNamespaceRequestRequestTypeDef",
     "GetRecoveryPointRequestRequestTypeDef",
     "RecoveryPointTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
     "ResourcePolicyTypeDef",
     "GetSnapshotRequestRequestTypeDef",
     "GetTableRestoreStatusRequestRequestTypeDef",
     "TableRestoreStatusTypeDef",
     "GetUsageLimitRequestRequestTypeDef",
     "GetWorkgroupRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
     "ListEndpointAccessRequestRequestTypeDef",
+    "ListNamespacesRequestListNamespacesPaginateTypeDef",
     "ListNamespacesRequestRequestTypeDef",
+    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
     "ListRecoveryPointsRequestRequestTypeDef",
+    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
     "ListSnapshotsRequestRequestTypeDef",
+    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
     "ListTableRestoreStatusRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
     "ListUsageLimitsRequestRequestTypeDef",
+    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
     "ListWorkgroupsRequestRequestTypeDef",
     "NetworkInterfaceTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreFromRecoveryPointRequestRequestTypeDef",
     "RestoreFromSnapshotRequestRequestTypeDef",
     "RestoreTableFromSnapshotRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateEndpointAccessRequestRequestTypeDef",
     "UpdateNamespaceRequestRequestTypeDef",
     "UpdateSnapshotRequestRequestTypeDef",
     "UpdateUsageLimitRequestRequestTypeDef",
     "UpdateWorkgroupRequestRequestTypeDef",
     "ConvertRecoveryPointToSnapshotRequestRequestTypeDef",
     "CreateNamespaceRequestRequestTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "CreateWorkgroupRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "GetCredentialsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ConvertRecoveryPointToSnapshotResponseTypeDef",
     "CreateSnapshotResponseTypeDef",
     "DeleteSnapshotResponseTypeDef",
     "GetSnapshotResponseTypeDef",
     "ListSnapshotsResponseTypeDef",
     "UpdateSnapshotResponseTypeDef",
     "CreateNamespaceResponseTypeDef",
@@ -106,21 +114,14 @@
     "GetRecoveryPointResponseTypeDef",
     "ListRecoveryPointsResponseTypeDef",
     "GetResourcePolicyResponseTypeDef",
     "PutResourcePolicyResponseTypeDef",
     "GetTableRestoreStatusResponseTypeDef",
     "ListTableRestoreStatusResponseTypeDef",
     "RestoreTableFromSnapshotResponseTypeDef",
-    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
-    "ListNamespacesRequestListNamespacesPaginateTypeDef",
-    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
-    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
-    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
-    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
     "VpcEndpointTypeDef",
     "EndpointAccessTypeDef",
     "EndpointTypeDef",
     "CreateEndpointAccessResponseTypeDef",
     "DeleteEndpointAccessResponseTypeDef",
     "GetEndpointAccessResponseTypeDef",
     "ListEndpointAccessResponseTypeDef",
@@ -146,25 +147,14 @@
     "TagTypeDef",
     {
         "key": str,
         "value": str,
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
 SnapshotTypeDef = TypedDict(
     "SnapshotTypeDef",
     {
         "accountsWithProvisionedRestoreAccess": List[str],
         "accountsWithRestoreAccess": List[str],
         "actualIncrementalBackupSizeInMegaBytes": float,
         "adminUsername": str,
@@ -200,20 +190,22 @@
     "_OptionalCreateEndpointAccessRequestRequestTypeDef",
     {
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class CreateEndpointAccessRequestRequestTypeDef(
     _RequiredCreateEndpointAccessRequestRequestTypeDef,
     _OptionalCreateEndpointAccessRequestRequestTypeDef,
 ):
     pass
 
+
 NamespaceTypeDef = TypedDict(
     "NamespaceTypeDef",
     {
         "adminUsername": str,
         "creationDate": datetime,
         "dbName": str,
         "defaultIamRoleArn": str,
@@ -241,19 +233,21 @@
     {
         "breachAction": UsageLimitBreachActionType,
         "period": UsageLimitPeriodType,
     },
     total=False,
 )
 
+
 class CreateUsageLimitRequestRequestTypeDef(
     _RequiredCreateUsageLimitRequestRequestTypeDef, _OptionalCreateUsageLimitRequestRequestTypeDef
 ):
     pass
 
+
 UsageLimitTypeDef = TypedDict(
     "UsageLimitTypeDef",
     {
         "amount": int,
         "breachAction": UsageLimitBreachActionType,
         "period": UsageLimitPeriodType,
         "resourceArn": str,
@@ -282,19 +276,21 @@
     {
         "finalSnapshotName": str,
         "finalSnapshotRetentionPeriod": int,
     },
     total=False,
 )
 
+
 class DeleteNamespaceRequestRequestTypeDef(
     _RequiredDeleteNamespaceRequestRequestTypeDef, _OptionalDeleteNamespaceRequestRequestTypeDef
 ):
     pass
 
+
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
@@ -339,19 +335,32 @@
     {
         "dbName": str,
         "durationSeconds": int,
     },
     total=False,
 )
 
+
 class GetCredentialsRequestRequestTypeDef(
     _RequiredGetCredentialsRequestRequestTypeDef, _OptionalGetCredentialsRequestRequestTypeDef
 ):
     pass
 
+
+GetCredentialsResponseTypeDef = TypedDict(
+    "GetCredentialsResponseTypeDef",
+    {
+        "dbPassword": str,
+        "dbUser": str,
+        "expiration": datetime,
+        "nextRefreshTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEndpointAccessRequestRequestTypeDef = TypedDict(
     "GetEndpointAccessRequestRequestTypeDef",
     {
         "endpointName": str,
     },
 )
 
@@ -447,20 +456,20 @@
 GetWorkgroupRequestRequestTypeDef = TypedDict(
     "GetWorkgroupRequestRequestTypeDef",
     {
         "workgroupName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListEndpointAccessRequestListEndpointAccessPaginateTypeDef = TypedDict(
+    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "vpcId": str,
+        "workgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEndpointAccessRequestRequestTypeDef = TypedDict(
     "ListEndpointAccessRequestRequestTypeDef",
     {
@@ -468,50 +477,93 @@
         "nextToken": str,
         "vpcId": str,
         "workgroupName": str,
     },
     total=False,
 )
 
+ListNamespacesRequestListNamespacesPaginateTypeDef = TypedDict(
+    "ListNamespacesRequestListNamespacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListNamespacesRequestRequestTypeDef = TypedDict(
     "ListNamespacesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef = TypedDict(
+    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
+    {
+        "endTime": Union[datetime, str],
+        "namespaceArn": str,
+        "namespaceName": str,
+        "startTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecoveryPointsRequestRequestTypeDef = TypedDict(
     "ListRecoveryPointsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "maxResults": int,
         "namespaceArn": str,
         "namespaceName": str,
         "nextToken": str,
         "startTime": Union[datetime, str],
     },
     total=False,
 )
 
+ListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
+    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
+    {
+        "endTime": Union[datetime, str],
+        "namespaceArn": str,
+        "namespaceName": str,
+        "ownerAccount": str,
+        "startTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSnapshotsRequestRequestTypeDef = TypedDict(
     "ListSnapshotsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "maxResults": int,
         "namespaceArn": str,
         "namespaceName": str,
         "nextToken": str,
         "ownerAccount": str,
         "startTime": Union[datetime, str],
     },
     total=False,
 )
 
+ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef = TypedDict(
+    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
+    {
+        "namespaceName": str,
+        "workgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTableRestoreStatusRequestRequestTypeDef = TypedDict(
     "ListTableRestoreStatusRequestRequestTypeDef",
     {
         "maxResults": int,
         "namespaceName": str,
         "nextToken": str,
         "workgroupName": str,
@@ -522,25 +574,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListUsageLimitsRequestListUsageLimitsPaginateTypeDef = TypedDict(
+    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
+    {
+        "resourceArn": str,
+        "usageType": UsageLimitUsageTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListUsageLimitsRequestRequestTypeDef = TypedDict(
     "ListUsageLimitsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "resourceArn": str,
         "usageType": UsageLimitUsageTypeType,
     },
     total=False,
 )
 
+ListWorkgroupsRequestListWorkgroupsPaginateTypeDef = TypedDict(
+    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkgroupsRequestRequestTypeDef = TypedDict(
     "ListWorkgroupsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -553,22 +623,43 @@
         "networkInterfaceId": str,
         "privateIpAddress": str,
         "subnetId": str,
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
 PutResourcePolicyRequestRequestTypeDef = TypedDict(
     "PutResourcePolicyRequestRequestTypeDef",
     {
         "policy": str,
         "resourceArn": str,
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
 RestoreFromRecoveryPointRequestRequestTypeDef = TypedDict(
     "RestoreFromRecoveryPointRequestRequestTypeDef",
     {
         "namespaceName": str,
         "recoveryPointId": str,
         "workgroupName": str,
     },
@@ -587,20 +678,22 @@
         "ownerAccount": str,
         "snapshotArn": str,
         "snapshotName": str,
     },
     total=False,
 )
 
+
 class RestoreFromSnapshotRequestRequestTypeDef(
     _RequiredRestoreFromSnapshotRequestRequestTypeDef,
     _OptionalRestoreFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredRestoreTableFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreTableFromSnapshotRequestRequestTypeDef",
     {
         "namespaceName": str,
         "newTableName": str,
         "snapshotName": str,
         "sourceDatabaseName": str,
@@ -615,20 +708,22 @@
         "sourceSchemaName": str,
         "targetDatabaseName": str,
         "targetSchemaName": str,
     },
     total=False,
 )
 
+
 class RestoreTableFromSnapshotRequestRequestTypeDef(
     _RequiredRestoreTableFromSnapshotRequestRequestTypeDef,
     _OptionalRestoreTableFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -643,20 +738,22 @@
     "_OptionalUpdateEndpointAccessRequestRequestTypeDef",
     {
         "vpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateEndpointAccessRequestRequestTypeDef(
     _RequiredUpdateEndpointAccessRequestRequestTypeDef,
     _OptionalUpdateEndpointAccessRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateNamespaceRequestRequestTypeDef",
     {
         "namespaceName": str,
     },
 )
 _OptionalUpdateNamespaceRequestRequestTypeDef = TypedDict(
@@ -668,38 +765,42 @@
         "iamRoles": Sequence[str],
         "kmsKeyId": str,
         "logExports": Sequence[LogExportType],
     },
     total=False,
 )
 
+
 class UpdateNamespaceRequestRequestTypeDef(
     _RequiredUpdateNamespaceRequestRequestTypeDef, _OptionalUpdateNamespaceRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSnapshotRequestRequestTypeDef",
     {
         "snapshotName": str,
     },
 )
 _OptionalUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateSnapshotRequestRequestTypeDef",
     {
         "retentionPeriod": int,
     },
     total=False,
 )
 
+
 class UpdateSnapshotRequestRequestTypeDef(
     _RequiredUpdateSnapshotRequestRequestTypeDef, _OptionalUpdateSnapshotRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateUsageLimitRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUsageLimitRequestRequestTypeDef",
     {
         "usageLimitId": str,
     },
 )
 _OptionalUpdateUsageLimitRequestRequestTypeDef = TypedDict(
@@ -707,19 +808,21 @@
     {
         "amount": int,
         "breachAction": UsageLimitBreachActionType,
     },
     total=False,
 )
 
+
 class UpdateUsageLimitRequestRequestTypeDef(
     _RequiredUpdateUsageLimitRequestRequestTypeDef, _OptionalUpdateUsageLimitRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateWorkgroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkgroupRequestRequestTypeDef",
     {
         "workgroupName": str,
     },
 )
 _OptionalUpdateWorkgroupRequestRequestTypeDef = TypedDict(
@@ -732,19 +835,21 @@
         "publiclyAccessible": bool,
         "securityGroupIds": Sequence[str],
         "subnetIds": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateWorkgroupRequestRequestTypeDef(
     _RequiredUpdateWorkgroupRequestRequestTypeDef, _OptionalUpdateWorkgroupRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredConvertRecoveryPointToSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredConvertRecoveryPointToSnapshotRequestRequestTypeDef",
     {
         "recoveryPointId": str,
         "snapshotName": str,
     },
 )
@@ -753,20 +858,22 @@
     {
         "retentionPeriod": int,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class ConvertRecoveryPointToSnapshotRequestRequestTypeDef(
     _RequiredConvertRecoveryPointToSnapshotRequestRequestTypeDef,
     _OptionalConvertRecoveryPointToSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNamespaceRequestRequestTypeDef",
     {
         "namespaceName": str,
     },
 )
 _OptionalCreateNamespaceRequestRequestTypeDef = TypedDict(
@@ -780,19 +887,21 @@
         "kmsKeyId": str,
         "logExports": Sequence[LogExportType],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateNamespaceRequestRequestTypeDef(
     _RequiredCreateNamespaceRequestRequestTypeDef, _OptionalCreateNamespaceRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSnapshotRequestRequestTypeDef",
     {
         "namespaceName": str,
         "snapshotName": str,
     },
 )
@@ -801,19 +910,21 @@
     {
         "retentionPeriod": int,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateSnapshotRequestRequestTypeDef(
     _RequiredCreateSnapshotRequestRequestTypeDef, _OptionalCreateSnapshotRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateWorkgroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkgroupRequestRequestTypeDef",
     {
         "namespaceName": str,
         "workgroupName": str,
     },
 )
@@ -828,323 +939,243 @@
         "securityGroupIds": Sequence[str],
         "subnetIds": Sequence[str],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateWorkgroupRequestRequestTypeDef(
     _RequiredCreateWorkgroupRequestRequestTypeDef, _OptionalCreateWorkgroupRequestRequestTypeDef
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
 
-GetCredentialsResponseTypeDef = TypedDict(
-    "GetCredentialsResponseTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "dbPassword": str,
-        "dbUser": str,
-        "expiration": datetime,
-        "nextRefreshTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 ConvertRecoveryPointToSnapshotResponseTypeDef = TypedDict(
     "ConvertRecoveryPointToSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResponseTypeDef = TypedDict(
     "CreateSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSnapshotResponseTypeDef = TypedDict(
     "DeleteSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotResponseTypeDef = TypedDict(
     "GetSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSnapshotsResponseTypeDef = TypedDict(
     "ListSnapshotsResponseTypeDef",
     {
         "nextToken": str,
         "snapshots": List[SnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSnapshotResponseTypeDef = TypedDict(
     "UpdateSnapshotResponseTypeDef",
     {
         "snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNamespaceResponseTypeDef = TypedDict(
     "CreateNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNamespaceResponseTypeDef = TypedDict(
     "DeleteNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNamespaceResponseTypeDef = TypedDict(
     "GetNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNamespacesResponseTypeDef = TypedDict(
     "ListNamespacesResponseTypeDef",
     {
         "namespaces": List[NamespaceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreFromRecoveryPointResponseTypeDef = TypedDict(
     "RestoreFromRecoveryPointResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
         "recoveryPointId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreFromSnapshotResponseTypeDef = TypedDict(
     "RestoreFromSnapshotResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
         "ownerAccount": str,
         "snapshotName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNamespaceResponseTypeDef = TypedDict(
     "UpdateNamespaceResponseTypeDef",
     {
         "namespace": NamespaceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUsageLimitResponseTypeDef = TypedDict(
     "CreateUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteUsageLimitResponseTypeDef = TypedDict(
     "DeleteUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUsageLimitResponseTypeDef = TypedDict(
     "GetUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsageLimitsResponseTypeDef = TypedDict(
     "ListUsageLimitsResponseTypeDef",
     {
         "nextToken": str,
         "usageLimits": List[UsageLimitTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUsageLimitResponseTypeDef = TypedDict(
     "UpdateUsageLimitResponseTypeDef",
     {
         "usageLimit": UsageLimitTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecoveryPointResponseTypeDef = TypedDict(
     "GetRecoveryPointResponseTypeDef",
     {
         "recoveryPoint": RecoveryPointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryPointsResponseTypeDef = TypedDict(
     "ListRecoveryPointsResponseTypeDef",
     {
         "nextToken": str,
         "recoveryPoints": List[RecoveryPointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcePolicyResponseTypeDef = TypedDict(
     "GetResourcePolicyResponseTypeDef",
     {
         "resourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourcePolicyResponseTypeDef = TypedDict(
     "PutResourcePolicyResponseTypeDef",
     {
         "resourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableRestoreStatusResponseTypeDef = TypedDict(
     "GetTableRestoreStatusResponseTypeDef",
     {
         "tableRestoreStatus": TableRestoreStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTableRestoreStatusResponseTypeDef = TypedDict(
     "ListTableRestoreStatusResponseTypeDef",
     {
         "nextToken": str,
         "tableRestoreStatuses": List[TableRestoreStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreTableFromSnapshotResponseTypeDef = TypedDict(
     "RestoreTableFromSnapshotResponseTypeDef",
     {
         "tableRestoreStatus": TableRestoreStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListEndpointAccessRequestListEndpointAccessPaginateTypeDef = TypedDict(
-    "ListEndpointAccessRequestListEndpointAccessPaginateTypeDef",
-    {
-        "vpcId": str,
-        "workgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListNamespacesRequestListNamespacesPaginateTypeDef = TypedDict(
-    "ListNamespacesRequestListNamespacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef = TypedDict(
-    "ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef",
-    {
-        "endTime": Union[datetime, str],
-        "namespaceArn": str,
-        "namespaceName": str,
-        "startTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
-    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    {
-        "endTime": Union[datetime, str],
-        "namespaceArn": str,
-        "namespaceName": str,
-        "ownerAccount": str,
-        "startTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef = TypedDict(
-    "ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef",
-    {
-        "namespaceName": str,
-        "workgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListUsageLimitsRequestListUsageLimitsPaginateTypeDef = TypedDict(
-    "ListUsageLimitsRequestListUsageLimitsPaginateTypeDef",
-    {
-        "resourceArn": str,
-        "usageType": UsageLimitUsageTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkgroupsRequestListWorkgroupsPaginateTypeDef = TypedDict(
-    "ListWorkgroupsRequestListWorkgroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 VpcEndpointTypeDef = TypedDict(
     "VpcEndpointTypeDef",
     {
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "vpcEndpointId": str,
@@ -1180,48 +1211,48 @@
     total=False,
 )
 
 CreateEndpointAccessResponseTypeDef = TypedDict(
     "CreateEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEndpointAccessResponseTypeDef = TypedDict(
     "DeleteEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEndpointAccessResponseTypeDef = TypedDict(
     "GetEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEndpointAccessResponseTypeDef = TypedDict(
     "ListEndpointAccessResponseTypeDef",
     {
         "endpoints": List[EndpointAccessTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointAccessResponseTypeDef = TypedDict(
     "UpdateEndpointAccessResponseTypeDef",
     {
         "endpoint": EndpointAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkgroupTypeDef = TypedDict(
     "WorkgroupTypeDef",
     {
         "baseCapacity": int,
@@ -1242,43 +1273,43 @@
     total=False,
 )
 
 CreateWorkgroupResponseTypeDef = TypedDict(
     "CreateWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteWorkgroupResponseTypeDef = TypedDict(
     "DeleteWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkgroupResponseTypeDef = TypedDict(
     "GetWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkgroupsResponseTypeDef = TypedDict(
     "ListWorkgroupsResponseTypeDef",
     {
         "nextToken": str,
         "workgroups": List[WorkgroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkgroupResponseTypeDef = TypedDict(
     "UpdateWorkgroupResponseTypeDef",
     {
         "workgroup": WorkgroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/PKG-INFO` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-redshift-serverless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RedshiftServerless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RedshiftServerless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-redshift-serverless"></a>
 
 # types-aiobotocore-redshift-serverless
 
 [![PyPI - types-aiobotocore-redshift-serverless](https://img.shields.io/pypi/v/types-aiobotocore-redshift-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-serverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-redshift-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-serverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-redshift-serverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-redshift-serverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RedshiftServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless)
+[aiobotocore.RedshiftServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html#RedshiftServerless)
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
 [types-aiobotocore-redshift-serverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_serverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -351,66 +351,73 @@
 `types_aiobotocore_redshift_serverless.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_redshift_serverless.type_defs import (
     ConfigParameterTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     SnapshotTypeDef,
     CreateEndpointAccessRequestRequestTypeDef,
     NamespaceTypeDef,
     CreateUsageLimitRequestRequestTypeDef,
     UsageLimitTypeDef,
     DeleteEndpointAccessRequestRequestTypeDef,
     DeleteNamespaceRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
     DeleteUsageLimitRequestRequestTypeDef,
     DeleteWorkgroupRequestRequestTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     GetCredentialsRequestRequestTypeDef,
+    GetCredentialsResponseTypeDef,
     GetEndpointAccessRequestRequestTypeDef,
     GetNamespaceRequestRequestTypeDef,
     GetRecoveryPointRequestRequestTypeDef,
     RecoveryPointTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
     ResourcePolicyTypeDef,
     GetSnapshotRequestRequestTypeDef,
     GetTableRestoreStatusRequestRequestTypeDef,
     TableRestoreStatusTypeDef,
     GetUsageLimitRequestRequestTypeDef,
     GetWorkgroupRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListEndpointAccessRequestListEndpointAccessPaginateTypeDef,
     ListEndpointAccessRequestRequestTypeDef,
+    ListNamespacesRequestListNamespacesPaginateTypeDef,
     ListNamespacesRequestRequestTypeDef,
+    ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef,
     ListRecoveryPointsRequestRequestTypeDef,
+    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
     ListSnapshotsRequestRequestTypeDef,
+    ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef,
     ListTableRestoreStatusRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsageLimitsRequestListUsageLimitsPaginateTypeDef,
     ListUsageLimitsRequestRequestTypeDef,
+    ListWorkgroupsRequestListWorkgroupsPaginateTypeDef,
     ListWorkgroupsRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreFromRecoveryPointRequestRequestTypeDef,
     RestoreFromSnapshotRequestRequestTypeDef,
     RestoreTableFromSnapshotRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateEndpointAccessRequestRequestTypeDef,
     UpdateNamespaceRequestRequestTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     UpdateUsageLimitRequestRequestTypeDef,
     UpdateWorkgroupRequestRequestTypeDef,
     ConvertRecoveryPointToSnapshotRequestRequestTypeDef,
     CreateNamespaceRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateWorkgroupRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    GetCredentialsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ConvertRecoveryPointToSnapshotResponseTypeDef,
     CreateSnapshotResponseTypeDef,
     DeleteSnapshotResponseTypeDef,
     GetSnapshotResponseTypeDef,
     ListSnapshotsResponseTypeDef,
     UpdateSnapshotResponseTypeDef,
     CreateNamespaceResponseTypeDef,
@@ -428,21 +435,14 @@
     GetRecoveryPointResponseTypeDef,
     ListRecoveryPointsResponseTypeDef,
     GetResourcePolicyResponseTypeDef,
     PutResourcePolicyResponseTypeDef,
     GetTableRestoreStatusResponseTypeDef,
     ListTableRestoreStatusResponseTypeDef,
     RestoreTableFromSnapshotResponseTypeDef,
-    ListEndpointAccessRequestListEndpointAccessPaginateTypeDef,
-    ListNamespacesRequestListNamespacesPaginateTypeDef,
-    ListRecoveryPointsRequestListRecoveryPointsPaginateTypeDef,
-    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    ListTableRestoreStatusRequestListTableRestoreStatusPaginateTypeDef,
-    ListUsageLimitsRequestListUsageLimitsPaginateTypeDef,
-    ListWorkgroupsRequestListWorkgroupsPaginateTypeDef,
     VpcEndpointTypeDef,
     EndpointAccessTypeDef,
     EndpointTypeDef,
     CreateEndpointAccessResponseTypeDef,
     DeleteEndpointAccessResponseTypeDef,
     GetEndpointAccessResponseTypeDef,
     ListEndpointAccessResponseTypeDef,
@@ -463,43 +463,43 @@
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

### Comparing `types-aiobotocore-redshift-serverless-2.5.0.post1/types_aiobotocore_redshift_serverless.egg-info/SOURCES.txt` & `types-aiobotocore-redshift-serverless-2.5.1/types_aiobotocore_redshift_serverless.egg-info/SOURCES.txt`

 * *Files identical despite different names*

