# Comparing `tmp/types-aiobotocore-grafana-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-grafana-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-grafana-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:41 2023, max compression
+gzip compressed data, was "types-aiobotocore-grafana-2.5.1.tar", last modified: Wed Jun 28 01:43:33 2023, max compression
```

## Comparing `types-aiobotocore-grafana-2.5.0.post1.tar` & `types-aiobotocore-grafana-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.655246 types-aiobotocore-grafana-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15391 2023-03-11 12:26:41.655246 types-aiobotocore-grafana-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13813 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:41.655246 types-aiobotocore-grafana-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:15:20.000000 types-aiobotocore-grafana-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.651246 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      869 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      957 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18312 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18283 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9108 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9106 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3389 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3384 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19312 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19289 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:21.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.655246 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15391 2023-03-11 12:26:41.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:26:41.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:41.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:41.000000 types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.566144 types-aiobotocore-grafana-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15383 2023-06-28 01:43:33.566144 types-aiobotocore-grafana-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13811 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:33.566144 types-aiobotocore-grafana-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.562144 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      869 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      945 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18347 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18318 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9317 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9315 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3273 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3269 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19377 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19354 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:56.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.566144 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15383 2023-06-28 01:43:33.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:43:33.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:33.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:33.000000 types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/LICENSE` & `types-aiobotocore-grafana-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/PKG-INFO` & `types-aiobotocore-grafana-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-grafana
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ManagedGrafana 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ManagedGrafana 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-grafana"></a>
 
 # types-aiobotocore-grafana
 
 [![PyPI - types-aiobotocore-grafana](https://img.shields.io/pypi/v/types-aiobotocore-grafana.svg?color=blue)](https://pypi.org/project/types-aiobotocore-grafana)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-grafana.svg?color=blue)](https://pypi.org/project/types-aiobotocore-grafana)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-grafana?color=blue)](https://pypistats.org/packages/types-aiobotocore-grafana)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ManagedGrafana 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
+[aiobotocore.ManagedGrafana 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
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
 [types-aiobotocore-grafana docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/).
 
 See how it helps to find and fix potential bugs:
 
@@ -329,46 +329,46 @@
 `types_aiobotocore_grafana.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_grafana.type_defs import (
     AssertionAttributesTypeDef,
     AssociateLicenseRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AwsSsoAuthenticationTypeDef,
     AuthenticationSummaryTypeDef,
     CreateWorkspaceApiKeyRequestRequestTypeDef,
+    CreateWorkspaceApiKeyResponseTypeDef,
     NetworkAccessConfigurationTypeDef,
     VpcConfigurationTypeDef,
     DeleteWorkspaceApiKeyRequestRequestTypeDef,
+    DeleteWorkspaceApiKeyResponseTypeDef,
     DeleteWorkspaceRequestRequestTypeDef,
     DescribeWorkspaceAuthenticationRequestRequestTypeDef,
     DescribeWorkspaceConfigurationRequestRequestTypeDef,
+    DescribeWorkspaceConfigurationResponseTypeDef,
     DescribeWorkspaceRequestRequestTypeDef,
     DisassociateLicenseRequestRequestTypeDef,
     IdpMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    ListPermissionsRequestListPermissionsPaginateTypeDef,
     ListPermissionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorkspacesRequestListWorkspacesPaginateTypeDef,
     ListWorkspacesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     UserTypeDef,
+    ResponseMetadataTypeDef,
     RoleValuesTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateWorkspaceConfigurationRequestRequestTypeDef,
-    CreateWorkspaceApiKeyResponseTypeDef,
-    DeleteWorkspaceApiKeyResponseTypeDef,
-    DescribeWorkspaceConfigurationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     WorkspaceSummaryTypeDef,
     CreateWorkspaceRequestRequestTypeDef,
     UpdateWorkspaceRequestRequestTypeDef,
     WorkspaceDescriptionTypeDef,
-    ListPermissionsRequestListPermissionsPaginateTypeDef,
-    ListWorkspacesRequestListWorkspacesPaginateTypeDef,
     PermissionEntryTypeDef,
     UpdateInstructionTypeDef,
     SamlConfigurationTypeDef,
     ListWorkspacesResponseTypeDef,
     AssociateLicenseResponseTypeDef,
     CreateWorkspaceResponseTypeDef,
     DeleteWorkspaceResponseTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/README.md` & `types-aiobotocore-grafana-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-grafana"></a>
 
 # types-aiobotocore-grafana
 
 [![PyPI - types-aiobotocore-grafana](https://img.shields.io/pypi/v/types-aiobotocore-grafana.svg?color=blue)](https://pypi.org/project/types-aiobotocore-grafana)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-grafana.svg?color=blue)](https://pypi.org/project/types-aiobotocore-grafana)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-grafana?color=blue)](https://pypistats.org/packages/types-aiobotocore-grafana)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ManagedGrafana 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
+[aiobotocore.ManagedGrafana 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
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
 [types-aiobotocore-grafana docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,46 +296,46 @@
 `types_aiobotocore_grafana.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_grafana.type_defs import (
     AssertionAttributesTypeDef,
     AssociateLicenseRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AwsSsoAuthenticationTypeDef,
     AuthenticationSummaryTypeDef,
     CreateWorkspaceApiKeyRequestRequestTypeDef,
+    CreateWorkspaceApiKeyResponseTypeDef,
     NetworkAccessConfigurationTypeDef,
     VpcConfigurationTypeDef,
     DeleteWorkspaceApiKeyRequestRequestTypeDef,
+    DeleteWorkspaceApiKeyResponseTypeDef,
     DeleteWorkspaceRequestRequestTypeDef,
     DescribeWorkspaceAuthenticationRequestRequestTypeDef,
     DescribeWorkspaceConfigurationRequestRequestTypeDef,
+    DescribeWorkspaceConfigurationResponseTypeDef,
     DescribeWorkspaceRequestRequestTypeDef,
     DisassociateLicenseRequestRequestTypeDef,
     IdpMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    ListPermissionsRequestListPermissionsPaginateTypeDef,
     ListPermissionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorkspacesRequestListWorkspacesPaginateTypeDef,
     ListWorkspacesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     UserTypeDef,
+    ResponseMetadataTypeDef,
     RoleValuesTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateWorkspaceConfigurationRequestRequestTypeDef,
-    CreateWorkspaceApiKeyResponseTypeDef,
-    DeleteWorkspaceApiKeyResponseTypeDef,
-    DescribeWorkspaceConfigurationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     WorkspaceSummaryTypeDef,
     CreateWorkspaceRequestRequestTypeDef,
     UpdateWorkspaceRequestRequestTypeDef,
     WorkspaceDescriptionTypeDef,
-    ListPermissionsRequestListPermissionsPaginateTypeDef,
-    ListWorkspacesRequestListWorkspacesPaginateTypeDef,
     PermissionEntryTypeDef,
     UpdateInstructionTypeDef,
     SamlConfigurationTypeDef,
     ListWorkspacesResponseTypeDef,
     AssociateLicenseResponseTypeDef,
     CreateWorkspaceResponseTypeDef,
     DeleteWorkspaceResponseTypeDef,
@@ -361,43 +361,43 @@
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/setup.py` & `types-aiobotocore-grafana-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-grafana.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-grafana",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_grafana"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ManagedGrafana 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ManagedGrafana 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/"
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/__init__.py` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/__init__.pyi` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/__main__.py` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ManagedGrafana 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ManagedGrafana 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana\nOther"
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/client.py` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -126,14 +126,15 @@
         self,
         *,
         accountAccessType: AccountAccessTypeType,
         authenticationProviders: Sequence[AuthenticationProviderTypesType],
         permissionType: PermissionTypeType,
         clientToken: str = ...,
         configuration: str = ...,
+        grafanaVersion: str = ...,
         networkAccessControl: NetworkAccessConfigurationTypeDef = ...,
         organizationRoleName: str = ...,
         stackSetName: str = ...,
         tags: Mapping[str, str] = ...,
         vpcConfiguration: VpcConfigurationTypeDef = ...,
         workspaceDataSources: Sequence[DataSourceTypeType] = ...,
         workspaceDescription: str = ...,
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/client.pyi` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -118,14 +118,15 @@
         self,
         *,
         accountAccessType: AccountAccessTypeType,
         authenticationProviders: Sequence[AuthenticationProviderTypesType],
         permissionType: PermissionTypeType,
         clientToken: str = ...,
         configuration: str = ...,
+        grafanaVersion: str = ...,
         networkAccessControl: NetworkAccessConfigurationTypeDef = ...,
         organizationRoleName: str = ...,
         stackSetName: str = ...,
         tags: Mapping[str, str] = ...,
         vpcConfiguration: VpcConfigurationTypeDef = ...,
         workspaceDataSources: Sequence[DataSourceTypeType] = ...,
         workspaceDescription: str = ...,
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/literals.py` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -135,14 +135,15 @@
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
@@ -221,14 +222,15 @@
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
@@ -239,14 +241,15 @@
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
@@ -282,14 +285,15 @@
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
@@ -308,16 +312,19 @@
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
@@ -401,15 +408,17 @@
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/literals.pyi` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -133,14 +133,15 @@
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
@@ -219,14 +220,15 @@
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
@@ -237,14 +239,15 @@
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
@@ -280,14 +283,15 @@
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
@@ -306,16 +310,19 @@
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
@@ -399,15 +406,17 @@
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/paginator.py` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,33 +18,26 @@
     with session.create_client("grafana") as client:
         client: ManagedGrafanaClient
 
         list_permissions_paginator: ListPermissionsPaginator = client.get_paginator("list_permissions")
         list_workspaces_paginator: ListWorkspacesPaginator = client.get_paginator("list_workspaces")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import UserTypeType
 from .type_defs import (
     ListPermissionsResponseTypeDef,
     ListWorkspacesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListPermissionsPaginator", "ListWorkspacesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -63,28 +56,28 @@
     def paginate(
         self,
         *,
         workspaceId: str,
         groupId: str = ...,
         userId: str = ...,
         userType: UserTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana.Paginator.ListPermissions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/paginators/#listpermissionspaginator)
         """
 
 
 class ListWorkspacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana.Paginator.ListWorkspaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/paginators/#listworkspacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkspacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana.Paginator.ListWorkspaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/paginators/#listworkspacespaginator)
         """
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/paginator.pyi` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -18,32 +18,26 @@
     with session.create_client("grafana") as client:
         client: ManagedGrafanaClient
 
         list_permissions_paginator: ListPermissionsPaginator = client.get_paginator("list_permissions")
         list_workspaces_paginator: ListWorkspacesPaginator = client.get_paginator("list_workspaces")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import UserTypeType
 from .type_defs import (
     ListPermissionsResponseTypeDef,
     ListWorkspacesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListPermissionsPaginator", "ListWorkspacesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -59,27 +53,27 @@
     def paginate(
         self,
         *,
         workspaceId: str,
         groupId: str = ...,
         userId: str = ...,
         userType: UserTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana.Paginator.ListPermissions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/paginators/#listpermissionspaginator)
         """
 
 class ListWorkspacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana.Paginator.ListWorkspaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/paginators/#listworkspacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkspacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana.Paginator.ListWorkspaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/paginators/#listworkspacespaginator)
         """
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/type_defs.py` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -37,46 +37,46 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssertionAttributesTypeDef",
     "AssociateLicenseRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AwsSsoAuthenticationTypeDef",
     "AuthenticationSummaryTypeDef",
     "CreateWorkspaceApiKeyRequestRequestTypeDef",
+    "CreateWorkspaceApiKeyResponseTypeDef",
     "NetworkAccessConfigurationTypeDef",
     "VpcConfigurationTypeDef",
     "DeleteWorkspaceApiKeyRequestRequestTypeDef",
+    "DeleteWorkspaceApiKeyResponseTypeDef",
     "DeleteWorkspaceRequestRequestTypeDef",
     "DescribeWorkspaceAuthenticationRequestRequestTypeDef",
     "DescribeWorkspaceConfigurationRequestRequestTypeDef",
+    "DescribeWorkspaceConfigurationResponseTypeDef",
     "DescribeWorkspaceRequestRequestTypeDef",
     "DisassociateLicenseRequestRequestTypeDef",
     "IdpMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListPermissionsRequestListPermissionsPaginateTypeDef",
     "ListPermissionsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
     "ListWorkspacesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "UserTypeDef",
+    "ResponseMetadataTypeDef",
     "RoleValuesTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateWorkspaceConfigurationRequestRequestTypeDef",
-    "CreateWorkspaceApiKeyResponseTypeDef",
-    "DeleteWorkspaceApiKeyResponseTypeDef",
-    "DescribeWorkspaceConfigurationResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "WorkspaceSummaryTypeDef",
     "CreateWorkspaceRequestRequestTypeDef",
     "UpdateWorkspaceRequestRequestTypeDef",
     "WorkspaceDescriptionTypeDef",
-    "ListPermissionsRequestListPermissionsPaginateTypeDef",
-    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
     "PermissionEntryTypeDef",
     "UpdateInstructionTypeDef",
     "SamlConfigurationTypeDef",
     "ListWorkspacesResponseTypeDef",
     "AssociateLicenseResponseTypeDef",
     "CreateWorkspaceResponseTypeDef",
     "DeleteWorkspaceResponseTypeDef",
@@ -111,25 +111,14 @@
     "AssociateLicenseRequestRequestTypeDef",
     {
         "licenseType": LicenseTypeType,
         "workspaceId": str,
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
 AwsSsoAuthenticationTypeDef = TypedDict(
     "AwsSsoAuthenticationTypeDef",
     {
         "ssoClientId": str,
     },
     total=False,
 )
@@ -161,14 +150,24 @@
         "keyName": str,
         "keyRole": str,
         "secondsToLive": int,
         "workspaceId": str,
     },
 )
 
+CreateWorkspaceApiKeyResponseTypeDef = TypedDict(
+    "CreateWorkspaceApiKeyResponseTypeDef",
+    {
+        "key": str,
+        "keyName": str,
+        "workspaceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NetworkAccessConfigurationTypeDef = TypedDict(
     "NetworkAccessConfigurationTypeDef",
     {
         "prefixListIds": List[str],
         "vpceIds": List[str],
     },
 )
@@ -185,14 +184,23 @@
     "DeleteWorkspaceApiKeyRequestRequestTypeDef",
     {
         "keyName": str,
         "workspaceId": str,
     },
 )
 
+DeleteWorkspaceApiKeyResponseTypeDef = TypedDict(
+    "DeleteWorkspaceApiKeyResponseTypeDef",
+    {
+        "keyName": str,
+        "workspaceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkspaceRequestRequestTypeDef = TypedDict(
     "DeleteWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
@@ -206,14 +214,22 @@
 DescribeWorkspaceConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeWorkspaceConfigurationRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
+DescribeWorkspaceConfigurationResponseTypeDef = TypedDict(
+    "DescribeWorkspaceConfigurationResponseTypeDef",
+    {
+        "configuration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeWorkspaceRequestRequestTypeDef = TypedDict(
     "DescribeWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
@@ -230,24 +246,39 @@
     {
         "url": str,
         "xml": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
+    "_RequiredListPermissionsRequestListPermissionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "workspaceId": str,
+    },
+)
+_OptionalListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
+    "_OptionalListPermissionsRequestListPermissionsPaginateTypeDef",
+    {
+        "groupId": str,
+        "userId": str,
+        "userType": UserTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListPermissionsRequestListPermissionsPaginateTypeDef(
+    _RequiredListPermissionsRequestListPermissionsPaginateTypeDef,
+    _OptionalListPermissionsRequestListPermissionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionsRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 _OptionalListPermissionsRequestRequestTypeDef = TypedDict(
@@ -272,31 +303,68 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkspacesRequestListWorkspacesPaginateTypeDef = TypedDict(
+    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkspacesRequestRequestTypeDef = TypedDict(
     "ListWorkspacesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
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
 UserTypeDef = TypedDict(
     "UserTypeDef",
     {
         "id": str,
         "type": UserTypeType,
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
 RoleValuesTypeDef = TypedDict(
     "RoleValuesTypeDef",
     {
         "admin": List[str],
         "editor": List[str],
     },
     total=False,
@@ -322,49 +390,14 @@
     "UpdateWorkspaceConfigurationRequestRequestTypeDef",
     {
         "configuration": str,
         "workspaceId": str,
     },
 )
 
-CreateWorkspaceApiKeyResponseTypeDef = TypedDict(
-    "CreateWorkspaceApiKeyResponseTypeDef",
-    {
-        "key": str,
-        "keyName": str,
-        "workspaceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteWorkspaceApiKeyResponseTypeDef = TypedDict(
-    "DeleteWorkspaceApiKeyResponseTypeDef",
-    {
-        "keyName": str,
-        "workspaceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWorkspaceConfigurationResponseTypeDef = TypedDict(
-    "DescribeWorkspaceConfigurationResponseTypeDef",
-    {
-        "configuration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredWorkspaceSummaryTypeDef = TypedDict(
     "_RequiredWorkspaceSummaryTypeDef",
     {
         "authentication": AuthenticationSummaryTypeDef,
         "created": datetime,
         "endpoint": str,
         "grafanaVersion": str,
@@ -398,14 +431,15 @@
     },
 )
 _OptionalCreateWorkspaceRequestRequestTypeDef = TypedDict(
     "_OptionalCreateWorkspaceRequestRequestTypeDef",
     {
         "clientToken": str,
         "configuration": str,
+        "grafanaVersion": str,
         "networkAccessControl": NetworkAccessConfigurationTypeDef,
         "organizationRoleName": str,
         "stackSetName": str,
         "tags": Mapping[str, str],
         "vpcConfiguration": VpcConfigurationTypeDef,
         "workspaceDataSources": Sequence[DataSourceTypeType],
         "workspaceDescription": str,
@@ -497,47 +531,14 @@
 
 class WorkspaceDescriptionTypeDef(
     _RequiredWorkspaceDescriptionTypeDef, _OptionalWorkspaceDescriptionTypeDef
 ):
     pass
 
 
-_RequiredListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
-    "_RequiredListPermissionsRequestListPermissionsPaginateTypeDef",
-    {
-        "workspaceId": str,
-    },
-)
-_OptionalListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
-    "_OptionalListPermissionsRequestListPermissionsPaginateTypeDef",
-    {
-        "groupId": str,
-        "userId": str,
-        "userType": UserTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPermissionsRequestListPermissionsPaginateTypeDef(
-    _RequiredListPermissionsRequestListPermissionsPaginateTypeDef,
-    _OptionalListPermissionsRequestListPermissionsPaginateTypeDef,
-):
-    pass
-
-
-ListWorkspacesRequestListWorkspacesPaginateTypeDef = TypedDict(
-    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 PermissionEntryTypeDef = TypedDict(
     "PermissionEntryTypeDef",
     {
         "role": RoleType,
         "user": UserTypeDef,
     },
 )
@@ -576,72 +577,72 @@
 
 
 ListWorkspacesResponseTypeDef = TypedDict(
     "ListWorkspacesResponseTypeDef",
     {
         "nextToken": str,
         "workspaces": List[WorkspaceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateLicenseResponseTypeDef = TypedDict(
     "AssociateLicenseResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateWorkspaceResponseTypeDef = TypedDict(
     "CreateWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteWorkspaceResponseTypeDef = TypedDict(
     "DeleteWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorkspaceResponseTypeDef = TypedDict(
     "DescribeWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateLicenseResponseTypeDef = TypedDict(
     "DisassociateLicenseResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkspaceResponseTypeDef = TypedDict(
     "UpdateWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPermissionsResponseTypeDef = TypedDict(
     "ListPermissionsResponseTypeDef",
     {
         "nextToken": str,
         "permissions": List[PermissionEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateErrorTypeDef = TypedDict(
     "UpdateErrorTypeDef",
     {
         "causedBy": UpdateInstructionTypeDef,
@@ -702,15 +703,15 @@
     pass
 
 
 UpdatePermissionsResponseTypeDef = TypedDict(
     "UpdatePermissionsResponseTypeDef",
     {
         "errors": List[UpdateErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAuthenticationDescriptionTypeDef = TypedDict(
     "_RequiredAuthenticationDescriptionTypeDef",
     {
         "providers": List[AuthenticationProviderTypesType],
@@ -732,18 +733,18 @@
     pass
 
 
 DescribeWorkspaceAuthenticationResponseTypeDef = TypedDict(
     "DescribeWorkspaceAuthenticationResponseTypeDef",
     {
         "authentication": AuthenticationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkspaceAuthenticationResponseTypeDef = TypedDict(
     "UpdateWorkspaceAuthenticationResponseTypeDef",
     {
         "authentication": AuthenticationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana/type_defs.pyi` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -36,46 +36,46 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssertionAttributesTypeDef",
     "AssociateLicenseRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AwsSsoAuthenticationTypeDef",
     "AuthenticationSummaryTypeDef",
     "CreateWorkspaceApiKeyRequestRequestTypeDef",
+    "CreateWorkspaceApiKeyResponseTypeDef",
     "NetworkAccessConfigurationTypeDef",
     "VpcConfigurationTypeDef",
     "DeleteWorkspaceApiKeyRequestRequestTypeDef",
+    "DeleteWorkspaceApiKeyResponseTypeDef",
     "DeleteWorkspaceRequestRequestTypeDef",
     "DescribeWorkspaceAuthenticationRequestRequestTypeDef",
     "DescribeWorkspaceConfigurationRequestRequestTypeDef",
+    "DescribeWorkspaceConfigurationResponseTypeDef",
     "DescribeWorkspaceRequestRequestTypeDef",
     "DisassociateLicenseRequestRequestTypeDef",
     "IdpMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListPermissionsRequestListPermissionsPaginateTypeDef",
     "ListPermissionsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
     "ListWorkspacesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "UserTypeDef",
+    "ResponseMetadataTypeDef",
     "RoleValuesTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateWorkspaceConfigurationRequestRequestTypeDef",
-    "CreateWorkspaceApiKeyResponseTypeDef",
-    "DeleteWorkspaceApiKeyResponseTypeDef",
-    "DescribeWorkspaceConfigurationResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "WorkspaceSummaryTypeDef",
     "CreateWorkspaceRequestRequestTypeDef",
     "UpdateWorkspaceRequestRequestTypeDef",
     "WorkspaceDescriptionTypeDef",
-    "ListPermissionsRequestListPermissionsPaginateTypeDef",
-    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
     "PermissionEntryTypeDef",
     "UpdateInstructionTypeDef",
     "SamlConfigurationTypeDef",
     "ListWorkspacesResponseTypeDef",
     "AssociateLicenseResponseTypeDef",
     "CreateWorkspaceResponseTypeDef",
     "DeleteWorkspaceResponseTypeDef",
@@ -110,25 +110,14 @@
     "AssociateLicenseRequestRequestTypeDef",
     {
         "licenseType": LicenseTypeType,
         "workspaceId": str,
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
 AwsSsoAuthenticationTypeDef = TypedDict(
     "AwsSsoAuthenticationTypeDef",
     {
         "ssoClientId": str,
     },
     total=False,
 )
@@ -158,14 +147,24 @@
         "keyName": str,
         "keyRole": str,
         "secondsToLive": int,
         "workspaceId": str,
     },
 )
 
+CreateWorkspaceApiKeyResponseTypeDef = TypedDict(
+    "CreateWorkspaceApiKeyResponseTypeDef",
+    {
+        "key": str,
+        "keyName": str,
+        "workspaceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NetworkAccessConfigurationTypeDef = TypedDict(
     "NetworkAccessConfigurationTypeDef",
     {
         "prefixListIds": List[str],
         "vpceIds": List[str],
     },
 )
@@ -182,14 +181,23 @@
     "DeleteWorkspaceApiKeyRequestRequestTypeDef",
     {
         "keyName": str,
         "workspaceId": str,
     },
 )
 
+DeleteWorkspaceApiKeyResponseTypeDef = TypedDict(
+    "DeleteWorkspaceApiKeyResponseTypeDef",
+    {
+        "keyName": str,
+        "workspaceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkspaceRequestRequestTypeDef = TypedDict(
     "DeleteWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
@@ -203,14 +211,22 @@
 DescribeWorkspaceConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeWorkspaceConfigurationRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
+DescribeWorkspaceConfigurationResponseTypeDef = TypedDict(
+    "DescribeWorkspaceConfigurationResponseTypeDef",
+    {
+        "configuration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeWorkspaceRequestRequestTypeDef = TypedDict(
     "DescribeWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
@@ -227,24 +243,37 @@
     {
         "url": str,
         "xml": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
+    "_RequiredListPermissionsRequestListPermissionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "workspaceId": str,
+    },
+)
+_OptionalListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
+    "_OptionalListPermissionsRequestListPermissionsPaginateTypeDef",
+    {
+        "groupId": str,
+        "userId": str,
+        "userType": UserTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListPermissionsRequestListPermissionsPaginateTypeDef(
+    _RequiredListPermissionsRequestListPermissionsPaginateTypeDef,
+    _OptionalListPermissionsRequestListPermissionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionsRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 _OptionalListPermissionsRequestRequestTypeDef = TypedDict(
@@ -267,31 +296,68 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkspacesRequestListWorkspacesPaginateTypeDef = TypedDict(
+    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkspacesRequestRequestTypeDef = TypedDict(
     "ListWorkspacesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
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
 UserTypeDef = TypedDict(
     "UserTypeDef",
     {
         "id": str,
         "type": UserTypeType,
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
 RoleValuesTypeDef = TypedDict(
     "RoleValuesTypeDef",
     {
         "admin": List[str],
         "editor": List[str],
     },
     total=False,
@@ -317,49 +383,14 @@
     "UpdateWorkspaceConfigurationRequestRequestTypeDef",
     {
         "configuration": str,
         "workspaceId": str,
     },
 )
 
-CreateWorkspaceApiKeyResponseTypeDef = TypedDict(
-    "CreateWorkspaceApiKeyResponseTypeDef",
-    {
-        "key": str,
-        "keyName": str,
-        "workspaceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteWorkspaceApiKeyResponseTypeDef = TypedDict(
-    "DeleteWorkspaceApiKeyResponseTypeDef",
-    {
-        "keyName": str,
-        "workspaceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWorkspaceConfigurationResponseTypeDef = TypedDict(
-    "DescribeWorkspaceConfigurationResponseTypeDef",
-    {
-        "configuration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredWorkspaceSummaryTypeDef = TypedDict(
     "_RequiredWorkspaceSummaryTypeDef",
     {
         "authentication": AuthenticationSummaryTypeDef,
         "created": datetime,
         "endpoint": str,
         "grafanaVersion": str,
@@ -391,14 +422,15 @@
     },
 )
 _OptionalCreateWorkspaceRequestRequestTypeDef = TypedDict(
     "_OptionalCreateWorkspaceRequestRequestTypeDef",
     {
         "clientToken": str,
         "configuration": str,
+        "grafanaVersion": str,
         "networkAccessControl": NetworkAccessConfigurationTypeDef,
         "organizationRoleName": str,
         "stackSetName": str,
         "tags": Mapping[str, str],
         "vpcConfiguration": VpcConfigurationTypeDef,
         "workspaceDataSources": Sequence[DataSourceTypeType],
         "workspaceDescription": str,
@@ -484,45 +516,14 @@
 )
 
 class WorkspaceDescriptionTypeDef(
     _RequiredWorkspaceDescriptionTypeDef, _OptionalWorkspaceDescriptionTypeDef
 ):
     pass
 
-_RequiredListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
-    "_RequiredListPermissionsRequestListPermissionsPaginateTypeDef",
-    {
-        "workspaceId": str,
-    },
-)
-_OptionalListPermissionsRequestListPermissionsPaginateTypeDef = TypedDict(
-    "_OptionalListPermissionsRequestListPermissionsPaginateTypeDef",
-    {
-        "groupId": str,
-        "userId": str,
-        "userType": UserTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPermissionsRequestListPermissionsPaginateTypeDef(
-    _RequiredListPermissionsRequestListPermissionsPaginateTypeDef,
-    _OptionalListPermissionsRequestListPermissionsPaginateTypeDef,
-):
-    pass
-
-ListWorkspacesRequestListWorkspacesPaginateTypeDef = TypedDict(
-    "ListWorkspacesRequestListWorkspacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 PermissionEntryTypeDef = TypedDict(
     "PermissionEntryTypeDef",
     {
         "role": RoleType,
         "user": UserTypeDef,
     },
 )
@@ -559,72 +560,72 @@
     pass
 
 ListWorkspacesResponseTypeDef = TypedDict(
     "ListWorkspacesResponseTypeDef",
     {
         "nextToken": str,
         "workspaces": List[WorkspaceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateLicenseResponseTypeDef = TypedDict(
     "AssociateLicenseResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateWorkspaceResponseTypeDef = TypedDict(
     "CreateWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteWorkspaceResponseTypeDef = TypedDict(
     "DeleteWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorkspaceResponseTypeDef = TypedDict(
     "DescribeWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateLicenseResponseTypeDef = TypedDict(
     "DisassociateLicenseResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkspaceResponseTypeDef = TypedDict(
     "UpdateWorkspaceResponseTypeDef",
     {
         "workspace": WorkspaceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPermissionsResponseTypeDef = TypedDict(
     "ListPermissionsResponseTypeDef",
     {
         "nextToken": str,
         "permissions": List[PermissionEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateErrorTypeDef = TypedDict(
     "UpdateErrorTypeDef",
     {
         "causedBy": UpdateInstructionTypeDef,
@@ -681,15 +682,15 @@
 ):
     pass
 
 UpdatePermissionsResponseTypeDef = TypedDict(
     "UpdatePermissionsResponseTypeDef",
     {
         "errors": List[UpdateErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAuthenticationDescriptionTypeDef = TypedDict(
     "_RequiredAuthenticationDescriptionTypeDef",
     {
         "providers": List[AuthenticationProviderTypesType],
@@ -709,18 +710,18 @@
 ):
     pass
 
 DescribeWorkspaceAuthenticationResponseTypeDef = TypedDict(
     "DescribeWorkspaceAuthenticationResponseTypeDef",
     {
         "authentication": AuthenticationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkspaceAuthenticationResponseTypeDef = TypedDict(
     "UpdateWorkspaceAuthenticationResponseTypeDef",
     {
         "authentication": AuthenticationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/PKG-INFO` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-grafana
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ManagedGrafana 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ManagedGrafana 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-grafana"></a>
 
 # types-aiobotocore-grafana
 
 [![PyPI - types-aiobotocore-grafana](https://img.shields.io/pypi/v/types-aiobotocore-grafana.svg?color=blue)](https://pypi.org/project/types-aiobotocore-grafana)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-grafana.svg?color=blue)](https://pypi.org/project/types-aiobotocore-grafana)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-grafana?color=blue)](https://pypistats.org/packages/types-aiobotocore-grafana)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ManagedGrafana 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
+[aiobotocore.ManagedGrafana 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
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
 [types-aiobotocore-grafana docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_grafana/).
 
 See how it helps to find and fix potential bugs:
 
@@ -329,46 +329,46 @@
 `types_aiobotocore_grafana.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_grafana.type_defs import (
     AssertionAttributesTypeDef,
     AssociateLicenseRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AwsSsoAuthenticationTypeDef,
     AuthenticationSummaryTypeDef,
     CreateWorkspaceApiKeyRequestRequestTypeDef,
+    CreateWorkspaceApiKeyResponseTypeDef,
     NetworkAccessConfigurationTypeDef,
     VpcConfigurationTypeDef,
     DeleteWorkspaceApiKeyRequestRequestTypeDef,
+    DeleteWorkspaceApiKeyResponseTypeDef,
     DeleteWorkspaceRequestRequestTypeDef,
     DescribeWorkspaceAuthenticationRequestRequestTypeDef,
     DescribeWorkspaceConfigurationRequestRequestTypeDef,
+    DescribeWorkspaceConfigurationResponseTypeDef,
     DescribeWorkspaceRequestRequestTypeDef,
     DisassociateLicenseRequestRequestTypeDef,
     IdpMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    ListPermissionsRequestListPermissionsPaginateTypeDef,
     ListPermissionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorkspacesRequestListWorkspacesPaginateTypeDef,
     ListWorkspacesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     UserTypeDef,
+    ResponseMetadataTypeDef,
     RoleValuesTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateWorkspaceConfigurationRequestRequestTypeDef,
-    CreateWorkspaceApiKeyResponseTypeDef,
-    DeleteWorkspaceApiKeyResponseTypeDef,
-    DescribeWorkspaceConfigurationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     WorkspaceSummaryTypeDef,
     CreateWorkspaceRequestRequestTypeDef,
     UpdateWorkspaceRequestRequestTypeDef,
     WorkspaceDescriptionTypeDef,
-    ListPermissionsRequestListPermissionsPaginateTypeDef,
-    ListWorkspacesRequestListWorkspacesPaginateTypeDef,
     PermissionEntryTypeDef,
     UpdateInstructionTypeDef,
     SamlConfigurationTypeDef,
     ListWorkspacesResponseTypeDef,
     AssociateLicenseResponseTypeDef,
     CreateWorkspaceResponseTypeDef,
     DeleteWorkspaceResponseTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-grafana-2.5.0.post1/types_aiobotocore_grafana.egg-info/SOURCES.txt` & `types-aiobotocore-grafana-2.5.1/types_aiobotocore_grafana.egg-info/SOURCES.txt`

 * *Files identical despite different names*

