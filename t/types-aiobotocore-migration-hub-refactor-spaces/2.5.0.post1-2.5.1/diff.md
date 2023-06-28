# Comparing `tmp/types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-migration-hub-refactor-spaces-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-migration-hub-refactor-spaces-2.5.1.tar", last modified: Wed Jun 28 01:43:52 2023, max compression
```

## Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1.tar` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.175441 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17544 2023-03-11 12:27:01.171441 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15888 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.175441 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2278 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.163441 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/
--rw-r--r--   0 runner    (1001) docker     (123)     1612 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1611 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1025 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24605 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24567 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9967 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9965 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7398 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7390 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    28276 2023-03-11 12:18:50.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    28247 2023-03-11 12:18:50.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:49.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.171441 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17544 2023-03-11 12:27:00.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1231 2023-03-11 12:27:01.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:00.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       48 2023-03-11 12:27:00.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.066179 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17558 2023-06-28 01:43:52.066179 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15908 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:52.066179 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2272 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.062179 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/
+-rw-r--r--   0 runner    (1001) docker     (123)     1612 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1611 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1013 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24605 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24567 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10176 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10174 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7288 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7281 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    28428 2023-06-28 01:35:34.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28399 2023-06-28 01:35:34.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:33.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.066179 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17558 2023-06-28 01:43:51.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1231 2023-06-28 01:43:51.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-28 01:43:51.000000 types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/LICENSE` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/PKG-INFO` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migration-hub-refactor-spaces
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migration-hub-refactor-spaces"></a>
 
 # types-aiobotocore-migration-hub-refactor-spaces
 
 [![PyPI - types-aiobotocore-migration-hub-refactor-spaces](https://img.shields.io/pypi/v/types-aiobotocore-migration-hub-refactor-spaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migration-hub-refactor-spaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migration-hub-refactor-spaces?color=blue)](https://pypistats.org/packages/types-aiobotocore-migration-hub-refactor-spaces)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubRefactorSpaces 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
+[aiobotocore.MigrationHubRefactorSpaces 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
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
 [types-aiobotocore-migration-hub-refactor-spaces docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/).
 
 See how it helps to find and fix potential bugs:
 
@@ -355,73 +355,73 @@
 
 ```python
 from types_aiobotocore_migration_hub_refactor_spaces.type_defs import (
     ApiGatewayProxyConfigTypeDef,
     ApiGatewayProxyInputTypeDef,
     ApiGatewayProxySummaryTypeDef,
     ErrorResponseTypeDef,
-    ResponseMetadataTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
+    CreateEnvironmentResponseTypeDef,
     DefaultRouteInputTypeDef,
     UriPathRouteInputTypeDef,
     LambdaEndpointInputTypeDef,
     UrlEndpointInputTypeDef,
     DeleteApplicationRequestRequestTypeDef,
+    DeleteApplicationResponseTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
+    DeleteEnvironmentResponseTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteRouteRequestRequestTypeDef,
+    DeleteRouteResponseTypeDef,
     DeleteServiceRequestRequestTypeDef,
+    DeleteServiceResponseTypeDef,
     EnvironmentVpcTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetRouteRequestRequestTypeDef,
     GetServiceRequestRequestTypeDef,
     LambdaEndpointConfigTypeDef,
     UrlEndpointConfigTypeDef,
     LambdaEndpointSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
     ListEnvironmentVpcsRequestRequestTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListRoutesRequestListRoutesPaginateTypeDef,
     ListRoutesRequestRequestTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UrlEndpointSummaryTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateRouteRequestRequestTypeDef,
+    UpdateRouteResponseTypeDef,
     CreateApplicationRequestRequestTypeDef,
+    CreateApplicationResponseTypeDef,
     ApplicationSummaryTypeDef,
     EnvironmentSummaryTypeDef,
-    RouteSummaryTypeDef,
-    CreateApplicationResponseTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    DeleteApplicationResponseTypeDef,
-    DeleteEnvironmentResponseTypeDef,
-    DeleteRouteResponseTypeDef,
-    DeleteServiceResponseTypeDef,
     GetApplicationResponseTypeDef,
     GetEnvironmentResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
     GetRouteResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateRouteResponseTypeDef,
+    RouteSummaryTypeDef,
     CreateRouteRequestRequestTypeDef,
     CreateRouteResponseTypeDef,
     CreateServiceRequestRequestTypeDef,
     CreateServiceResponseTypeDef,
     ListEnvironmentVpcsResponseTypeDef,
     GetServiceResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
-    ListRoutesRequestListRoutesPaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
     ServiceSummaryTypeDef,
     ListApplicationsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     ListRoutesResponseTypeDef,
     ListServicesResponseTypeDef,
 )
 
@@ -433,43 +433,43 @@
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/README.md` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-migration-hub-refactor-spaces"></a>
 
 # types-aiobotocore-migration-hub-refactor-spaces
 
 [![PyPI - types-aiobotocore-migration-hub-refactor-spaces](https://img.shields.io/pypi/v/types-aiobotocore-migration-hub-refactor-spaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migration-hub-refactor-spaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migration-hub-refactor-spaces?color=blue)](https://pypistats.org/packages/types-aiobotocore-migration-hub-refactor-spaces)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubRefactorSpaces 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
+[aiobotocore.MigrationHubRefactorSpaces 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
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
 [types-aiobotocore-migration-hub-refactor-spaces docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/).
 
 See how it helps to find and fix potential bugs:
 
@@ -322,73 +322,73 @@
 
 ```python
 from types_aiobotocore_migration_hub_refactor_spaces.type_defs import (
     ApiGatewayProxyConfigTypeDef,
     ApiGatewayProxyInputTypeDef,
     ApiGatewayProxySummaryTypeDef,
     ErrorResponseTypeDef,
-    ResponseMetadataTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
+    CreateEnvironmentResponseTypeDef,
     DefaultRouteInputTypeDef,
     UriPathRouteInputTypeDef,
     LambdaEndpointInputTypeDef,
     UrlEndpointInputTypeDef,
     DeleteApplicationRequestRequestTypeDef,
+    DeleteApplicationResponseTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
+    DeleteEnvironmentResponseTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteRouteRequestRequestTypeDef,
+    DeleteRouteResponseTypeDef,
     DeleteServiceRequestRequestTypeDef,
+    DeleteServiceResponseTypeDef,
     EnvironmentVpcTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetRouteRequestRequestTypeDef,
     GetServiceRequestRequestTypeDef,
     LambdaEndpointConfigTypeDef,
     UrlEndpointConfigTypeDef,
     LambdaEndpointSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
     ListEnvironmentVpcsRequestRequestTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListRoutesRequestListRoutesPaginateTypeDef,
     ListRoutesRequestRequestTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UrlEndpointSummaryTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateRouteRequestRequestTypeDef,
+    UpdateRouteResponseTypeDef,
     CreateApplicationRequestRequestTypeDef,
+    CreateApplicationResponseTypeDef,
     ApplicationSummaryTypeDef,
     EnvironmentSummaryTypeDef,
-    RouteSummaryTypeDef,
-    CreateApplicationResponseTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    DeleteApplicationResponseTypeDef,
-    DeleteEnvironmentResponseTypeDef,
-    DeleteRouteResponseTypeDef,
-    DeleteServiceResponseTypeDef,
     GetApplicationResponseTypeDef,
     GetEnvironmentResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
     GetRouteResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateRouteResponseTypeDef,
+    RouteSummaryTypeDef,
     CreateRouteRequestRequestTypeDef,
     CreateRouteResponseTypeDef,
     CreateServiceRequestRequestTypeDef,
     CreateServiceResponseTypeDef,
     ListEnvironmentVpcsResponseTypeDef,
     GetServiceResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
-    ListRoutesRequestListRoutesPaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
     ServiceSummaryTypeDef,
     ListApplicationsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     ListRoutesResponseTypeDef,
     ListServicesResponseTypeDef,
 )
 
@@ -400,43 +400,43 @@
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/setup.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-migration-hub-refactor-spaces.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-migration-hub-refactor-spaces",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_migration_hub_refactor_spaces"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/",
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/__init__.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/__init__.pyi` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/__main__.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces\nOther"
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/client.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/client.pyi` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/literals.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/literals.pyi`

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
     "ApiGatewayEndpointTypeType",
     "ApplicationStateType",
     "EnvironmentStateType",
     "ErrorCodeType",
     "ErrorResourceTypeType",
     "HttpMethodType",
@@ -40,15 +39,14 @@
     "ServiceStateType",
     "MigrationHubRefactorSpacesServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 ApiGatewayEndpointTypeType = Literal["PRIVATE", "REGIONAL"]
 ApplicationStateType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "UPDATING"]
 EnvironmentStateType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED"]
 ErrorCodeType = Literal[
     "INVALID_RESOURCE_STATE",
     "NOT_AUTHORIZED",
     "REQUEST_LIMIT_EXCEEDED",
@@ -155,14 +153,15 @@
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
@@ -241,14 +240,15 @@
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
@@ -259,14 +259,15 @@
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
@@ -302,14 +303,15 @@
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
@@ -328,16 +330,19 @@
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
@@ -421,15 +426,17 @@
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/literals.pyi` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/literals.py`

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
     "ApiGatewayEndpointTypeType",
     "ApplicationStateType",
     "EnvironmentStateType",
     "ErrorCodeType",
     "ErrorResourceTypeType",
     "HttpMethodType",
@@ -39,14 +40,15 @@
     "ServiceStateType",
     "MigrationHubRefactorSpacesServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 ApiGatewayEndpointTypeType = Literal["PRIVATE", "REGIONAL"]
 ApplicationStateType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "UPDATING"]
 EnvironmentStateType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED"]
 ErrorCodeType = Literal[
     "INVALID_RESOURCE_STATE",
     "NOT_AUTHORIZED",
     "REQUEST_LIMIT_EXCEEDED",
@@ -153,14 +155,15 @@
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
@@ -239,14 +242,15 @@
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
@@ -257,14 +261,15 @@
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
@@ -300,14 +305,15 @@
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
@@ -326,16 +332,19 @@
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
@@ -419,15 +428,17 @@
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/paginator.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_environment_vpcs_paginator: ListEnvironmentVpcsPaginator = client.get_paginator("list_environment_vpcs")
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
         list_routes_paginator: ListRoutesPaginator = client.get_paginator("list_routes")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     ListEnvironmentVpcsResponseTypeDef,
     ListRoutesResponseTypeDef,
     ListServicesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationsPaginator",
     "ListEnvironmentVpcsPaginator",
     "ListEnvironmentsPaginator",
     "ListRoutesPaginator",
     "ListServicesPaginator",
 )
@@ -71,45 +64,45 @@
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, EnvironmentIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EnvironmentIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listapplicationspaginator)
         """
 
 
 class ListEnvironmentVpcsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironmentVpcs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentvpcspaginator)
     """
 
     def paginate(
-        self, *, EnvironmentIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EnvironmentIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentVpcsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironmentVpcs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentvpcspaginator)
         """
 
 
 class ListEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentspaginator)
         """
 
 
@@ -120,15 +113,15 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationIdentifier: str,
         EnvironmentIdentifier: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listroutespaginator)
         """
 
 
@@ -139,13 +132,13 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationIdentifier: str,
         EnvironmentIdentifier: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listservicespaginator)
         """
```

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/paginator.pyi` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_environment_vpcs_paginator: ListEnvironmentVpcsPaginator = client.get_paginator("list_environment_vpcs")
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
         list_routes_paginator: ListRoutesPaginator = client.get_paginator("list_routes")
         list_services_paginator: ListServicesPaginator = client.get_paginator("list_services")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     ListEnvironmentVpcsResponseTypeDef,
     ListRoutesResponseTypeDef,
     ListServicesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationsPaginator",
     "ListEnvironmentVpcsPaginator",
     "ListEnvironmentsPaginator",
     "ListRoutesPaginator",
     "ListServicesPaginator",
 )
@@ -67,43 +61,43 @@
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, EnvironmentIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EnvironmentIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listapplicationspaginator)
         """
 
 class ListEnvironmentVpcsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironmentVpcs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentvpcspaginator)
     """
 
     def paginate(
-        self, *, EnvironmentIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EnvironmentIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentVpcsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironmentVpcs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentvpcspaginator)
         """
 
 class ListEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listenvironmentspaginator)
         """
 
 class ListRoutesPaginator(AioPaginator):
@@ -113,15 +107,15 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationIdentifier: str,
         EnvironmentIdentifier: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listroutespaginator)
         """
 
 class ListServicesPaginator(AioPaginator):
@@ -131,13 +125,13 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationIdentifier: str,
         EnvironmentIdentifier: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/paginators/#listservicespaginator)
         """
```

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.py` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -35,79 +35,78 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ApiGatewayProxyConfigTypeDef",
     "ApiGatewayProxyInputTypeDef",
     "ApiGatewayProxySummaryTypeDef",
     "ErrorResponseTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateEnvironmentRequestRequestTypeDef",
+    "CreateEnvironmentResponseTypeDef",
     "DefaultRouteInputTypeDef",
     "UriPathRouteInputTypeDef",
     "LambdaEndpointInputTypeDef",
     "UrlEndpointInputTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
+    "DeleteApplicationResponseTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
+    "DeleteEnvironmentResponseTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteRouteRequestRequestTypeDef",
+    "DeleteRouteResponseTypeDef",
     "DeleteServiceRequestRequestTypeDef",
+    "DeleteServiceResponseTypeDef",
     "EnvironmentVpcTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetEnvironmentRequestRequestTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "GetRouteRequestRequestTypeDef",
     "GetServiceRequestRequestTypeDef",
     "LambdaEndpointConfigTypeDef",
     "UrlEndpointConfigTypeDef",
     "LambdaEndpointSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
     "ListEnvironmentVpcsRequestRequestTypeDef",
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
+    "ListRoutesRequestListRoutesPaginateTypeDef",
     "ListRoutesRequestRequestTypeDef",
+    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UrlEndpointSummaryTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateRouteRequestRequestTypeDef",
+    "UpdateRouteResponseTypeDef",
     "CreateApplicationRequestRequestTypeDef",
+    "CreateApplicationResponseTypeDef",
     "ApplicationSummaryTypeDef",
     "EnvironmentSummaryTypeDef",
-    "RouteSummaryTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "CreateEnvironmentResponseTypeDef",
-    "DeleteApplicationResponseTypeDef",
-    "DeleteEnvironmentResponseTypeDef",
-    "DeleteRouteResponseTypeDef",
-    "DeleteServiceResponseTypeDef",
     "GetApplicationResponseTypeDef",
     "GetEnvironmentResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
     "GetRouteResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateRouteResponseTypeDef",
+    "RouteSummaryTypeDef",
     "CreateRouteRequestRequestTypeDef",
     "CreateRouteResponseTypeDef",
     "CreateServiceRequestRequestTypeDef",
     "CreateServiceResponseTypeDef",
     "ListEnvironmentVpcsResponseTypeDef",
     "GetServiceResponseTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    "ListRoutesRequestListRoutesPaginateTypeDef",
-    "ListServicesRequestListServicesPaginateTypeDef",
     "ServiceSummaryTypeDef",
     "ListApplicationsResponseTypeDef",
     "ListEnvironmentsResponseTypeDef",
     "ListRoutesResponseTypeDef",
     "ListServicesResponseTypeDef",
 )
 
@@ -157,25 +156,14 @@
         "Message": str,
         "ResourceIdentifier": str,
         "ResourceType": ErrorResourceTypeType,
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
 _RequiredCreateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentRequestRequestTypeDef",
     {
         "Name": str,
         "NetworkFabricType": NetworkFabricTypeType,
     },
 )
@@ -185,20 +173,35 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateEnvironmentRequestRequestTypeDef(
     _RequiredCreateEnvironmentRequestRequestTypeDef, _OptionalCreateEnvironmentRequestRequestTypeDef
 ):
     pass
 
+CreateEnvironmentResponseTypeDef = TypedDict(
+    "CreateEnvironmentResponseTypeDef",
+    {
+        "Arn": str,
+        "CreatedTime": datetime,
+        "Description": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "NetworkFabricType": NetworkFabricTypeType,
+        "OwnerAccountId": str,
+        "State": EnvironmentStateType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DefaultRouteInputTypeDef = TypedDict(
     "DefaultRouteInputTypeDef",
     {
         "ActivationState": RouteActivationStateType,
     },
     total=False,
@@ -210,27 +213,26 @@
         "ActivationState": RouteActivationStateType,
         "SourcePath": str,
     },
 )
 _OptionalUriPathRouteInputTypeDef = TypedDict(
     "_OptionalUriPathRouteInputTypeDef",
     {
+        "AppendSourcePath": bool,
         "IncludeChildPaths": bool,
         "Methods": Sequence[HttpMethodType],
     },
     total=False,
 )
 
-
 class UriPathRouteInputTypeDef(
     _RequiredUriPathRouteInputTypeDef, _OptionalUriPathRouteInputTypeDef
 ):
     pass
 
-
 LambdaEndpointInputTypeDef = TypedDict(
     "LambdaEndpointInputTypeDef",
     {
         "Arn": str,
     },
 )
 
@@ -244,34 +246,57 @@
     "_OptionalUrlEndpointInputTypeDef",
     {
         "HealthUrl": str,
     },
     total=False,
 )
 
-
 class UrlEndpointInputTypeDef(_RequiredUrlEndpointInputTypeDef, _OptionalUrlEndpointInputTypeDef):
     pass
 
-
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
     },
 )
 
+DeleteApplicationResponseTypeDef = TypedDict(
+    "DeleteApplicationResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "State": ApplicationStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteEnvironmentRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
     },
 )
 
+DeleteEnvironmentResponseTypeDef = TypedDict(
+    "DeleteEnvironmentResponseTypeDef",
+    {
+        "Arn": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "State": EnvironmentStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
@@ -280,23 +305,50 @@
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "RouteIdentifier": str,
     },
 )
 
+DeleteRouteResponseTypeDef = TypedDict(
+    "DeleteRouteResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "LastUpdatedTime": datetime,
+        "RouteId": str,
+        "ServiceId": str,
+        "State": RouteStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteServiceRequestRequestTypeDef = TypedDict(
     "DeleteServiceRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "ServiceIdentifier": str,
     },
 )
 
+DeleteServiceResponseTypeDef = TypedDict(
+    "DeleteServiceResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "ServiceId": str,
+        "State": ServiceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnvironmentVpcTypeDef = TypedDict(
     "EnvironmentVpcTypeDef",
     {
         "AccountId": str,
         "CidrBlocks": List[str],
         "CreatedTime": datetime,
         "EnvironmentId": str,
@@ -325,14 +377,22 @@
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRouteRequestRequestTypeDef = TypedDict(
     "GetRouteRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "RouteIdentifier": str,
     },
@@ -368,24 +428,34 @@
     "LambdaEndpointSummaryTypeDef",
     {
         "Arn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationsRequestListApplicationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListApplicationsRequestListApplicationsPaginateTypeDef(
+    _RequiredListApplicationsRequestListApplicationsPaginateTypeDef,
+    _OptionalListApplicationsRequestListApplicationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListApplicationsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationsRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
     },
 )
 _OptionalListApplicationsRequestRequestTypeDef = TypedDict(
@@ -393,20 +463,38 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListApplicationsRequestRequestTypeDef(
     _RequiredListApplicationsRequestRequestTypeDef, _OptionalListApplicationsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
+    {
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef(
+    _RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
+    _OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
+):
+    pass
 
 _RequiredListEnvironmentVpcsRequestRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentVpcsRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
     },
 )
@@ -415,31 +503,58 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListEnvironmentVpcsRequestRequestTypeDef(
     _RequiredListEnvironmentVpcsRequestRequestTypeDef,
     _OptionalListEnvironmentVpcsRequestRequestTypeDef,
 ):
     pass
 
+ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListEnvironmentsRequestRequestTypeDef = TypedDict(
     "ListEnvironmentsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListRoutesRequestListRoutesPaginateTypeDef",
+    {
+        "ApplicationIdentifier": str,
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListRoutesRequestListRoutesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRoutesRequestListRoutesPaginateTypeDef(
+    _RequiredListRoutesRequestListRoutesPaginateTypeDef,
+    _OptionalListRoutesRequestListRoutesPaginateTypeDef,
+):
+    pass
+
 _RequiredListRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredListRoutesRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
     },
 )
@@ -448,20 +563,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListRoutesRequestRequestTypeDef(
     _RequiredListRoutesRequestRequestTypeDef, _OptionalListRoutesRequestRequestTypeDef
 ):
     pass
 
+_RequiredListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "_RequiredListServicesRequestListServicesPaginateTypeDef",
+    {
+        "ApplicationIdentifier": str,
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "_OptionalListServicesRequestListServicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServicesRequestListServicesPaginateTypeDef(
+    _RequiredListServicesRequestListServicesPaginateTypeDef,
+    _OptionalListServicesRequestListServicesPaginateTypeDef,
+):
+    pass
 
 _RequiredListServicesRequestRequestTypeDef = TypedDict(
     "_RequiredListServicesRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
     },
@@ -471,36 +605,63 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListServicesRequestRequestTypeDef(
     _RequiredListServicesRequestRequestTypeDef, _OptionalListServicesRequestRequestTypeDef
 ):
     pass
 
-
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
         "Policy": str,
         "ResourceArn": str,
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
 UrlEndpointSummaryTypeDef = TypedDict(
     "UrlEndpointSummaryTypeDef",
     {
         "HealthUrl": str,
         "Url": str,
     },
     total=False,
@@ -528,14 +689,27 @@
         "ActivationState": RouteActivationStateType,
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "RouteIdentifier": str,
     },
 )
 
+UpdateRouteResponseTypeDef = TypedDict(
+    "UpdateRouteResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "LastUpdatedTime": datetime,
+        "RouteId": str,
+        "ServiceId": str,
+        "State": RouteStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
         "Name": str,
         "ProxyType": Literal["API_GATEWAY"],
         "VpcId": str,
@@ -547,172 +721,77 @@
         "ApiGatewayProxy": ApiGatewayProxyInputTypeDef,
         "ClientToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
-
-ApplicationSummaryTypeDef = TypedDict(
-    "ApplicationSummaryTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "ApiGatewayProxy": ApiGatewayProxySummaryTypeDef,
+        "ApiGatewayProxy": ApiGatewayProxyInputTypeDef,
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
         "EnvironmentId": str,
-        "Error": ErrorResponseTypeDef,
         "LastUpdatedTime": datetime,
         "Name": str,
         "OwnerAccountId": str,
         "ProxyType": Literal["API_GATEWAY"],
         "State": ApplicationStateType,
         "Tags": Dict[str, str],
         "VpcId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-EnvironmentSummaryTypeDef = TypedDict(
-    "EnvironmentSummaryTypeDef",
-    {
-        "Arn": str,
-        "CreatedTime": datetime,
-        "Description": str,
-        "EnvironmentId": str,
-        "Error": ErrorResponseTypeDef,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "NetworkFabricType": NetworkFabricTypeType,
-        "OwnerAccountId": str,
-        "State": EnvironmentStateType,
-        "Tags": Dict[str, str],
-        "TransitGatewayId": str,
-    },
-    total=False,
-)
-
-RouteSummaryTypeDef = TypedDict(
-    "RouteSummaryTypeDef",
+ApplicationSummaryTypeDef = TypedDict(
+    "ApplicationSummaryTypeDef",
     {
+        "ApiGatewayProxy": ApiGatewayProxySummaryTypeDef,
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
         "EnvironmentId": str,
         "Error": ErrorResponseTypeDef,
-        "IncludeChildPaths": bool,
-        "LastUpdatedTime": datetime,
-        "Methods": List[HttpMethodType],
-        "OwnerAccountId": str,
-        "PathResourceToId": Dict[str, str],
-        "RouteId": str,
-        "RouteType": RouteTypeType,
-        "ServiceId": str,
-        "SourcePath": str,
-        "State": RouteStateType,
-        "Tags": Dict[str, str],
-    },
-    total=False,
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "ApiGatewayProxy": ApiGatewayProxyInputTypeDef,
-        "ApplicationId": str,
-        "Arn": str,
-        "CreatedByAccountId": str,
-        "CreatedTime": datetime,
-        "EnvironmentId": str,
         "LastUpdatedTime": datetime,
         "Name": str,
         "OwnerAccountId": str,
         "ProxyType": Literal["API_GATEWAY"],
         "State": ApplicationStateType,
         "Tags": Dict[str, str],
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-CreateEnvironmentResponseTypeDef = TypedDict(
-    "CreateEnvironmentResponseTypeDef",
+EnvironmentSummaryTypeDef = TypedDict(
+    "EnvironmentSummaryTypeDef",
     {
         "Arn": str,
         "CreatedTime": datetime,
         "Description": str,
         "EnvironmentId": str,
+        "Error": ErrorResponseTypeDef,
         "LastUpdatedTime": datetime,
         "Name": str,
         "NetworkFabricType": NetworkFabricTypeType,
         "OwnerAccountId": str,
         "State": EnvironmentStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationResponseTypeDef = TypedDict(
-    "DeleteApplicationResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "Arn": str,
-        "EnvironmentId": str,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "State": ApplicationStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEnvironmentResponseTypeDef = TypedDict(
-    "DeleteEnvironmentResponseTypeDef",
-    {
-        "Arn": str,
-        "EnvironmentId": str,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "State": EnvironmentStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRouteResponseTypeDef = TypedDict(
-    "DeleteRouteResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "Arn": str,
-        "LastUpdatedTime": datetime,
-        "RouteId": str,
-        "ServiceId": str,
-        "State": RouteStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteServiceResponseTypeDef = TypedDict(
-    "DeleteServiceResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "Arn": str,
-        "EnvironmentId": str,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "ServiceId": str,
-        "State": ServiceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TransitGatewayId": str,
     },
+    total=False,
 )
 
 GetApplicationResponseTypeDef = TypedDict(
     "GetApplicationResponseTypeDef",
     {
         "ApiGatewayProxy": ApiGatewayProxyConfigTypeDef,
         "ApplicationId": str,
@@ -724,15 +803,15 @@
         "LastUpdatedTime": datetime,
         "Name": str,
         "OwnerAccountId": str,
         "ProxyType": Literal["API_GATEWAY"],
         "State": ApplicationStateType,
         "Tags": Dict[str, str],
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentResponseTypeDef = TypedDict(
     "GetEnvironmentResponseTypeDef",
     {
         "Arn": str,
@@ -743,29 +822,22 @@
         "LastUpdatedTime": datetime,
         "Name": str,
         "NetworkFabricType": NetworkFabricTypeType,
         "OwnerAccountId": str,
         "State": EnvironmentStateType,
         "Tags": Dict[str, str],
         "TransitGatewayId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResponseTypeDef = TypedDict(
     "GetRouteResponseTypeDef",
     {
+        "AppendSourcePath": bool,
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
         "EnvironmentId": str,
         "Error": ErrorResponseTypeDef,
         "IncludeChildPaths": bool,
@@ -775,37 +847,41 @@
         "PathResourceToId": Dict[str, str],
         "RouteId": str,
         "RouteType": RouteTypeType,
         "ServiceId": str,
         "SourcePath": str,
         "State": RouteStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateRouteResponseTypeDef = TypedDict(
-    "UpdateRouteResponseTypeDef",
+RouteSummaryTypeDef = TypedDict(
+    "RouteSummaryTypeDef",
     {
+        "AppendSourcePath": bool,
         "ApplicationId": str,
         "Arn": str,
+        "CreatedByAccountId": str,
+        "CreatedTime": datetime,
+        "EnvironmentId": str,
+        "Error": ErrorResponseTypeDef,
+        "IncludeChildPaths": bool,
         "LastUpdatedTime": datetime,
+        "Methods": List[HttpMethodType],
+        "OwnerAccountId": str,
+        "PathResourceToId": Dict[str, str],
         "RouteId": str,
+        "RouteType": RouteTypeType,
         "ServiceId": str,
+        "SourcePath": str,
         "State": RouteStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Dict[str, str],
     },
+    total=False,
 )
 
 _RequiredCreateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
@@ -820,21 +896,19 @@
         "DefaultRoute": DefaultRouteInputTypeDef,
         "Tags": Mapping[str, str],
         "UriPathRoute": UriPathRouteInputTypeDef,
     },
     total=False,
 )
 
-
 class CreateRouteRequestRequestTypeDef(
     _RequiredCreateRouteRequestRequestTypeDef, _OptionalCreateRouteRequestRequestTypeDef
 ):
     pass
 
-
 CreateRouteResponseTypeDef = TypedDict(
     "CreateRouteResponseTypeDef",
     {
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
@@ -842,15 +916,15 @@
         "OwnerAccountId": str,
         "RouteId": str,
         "RouteType": RouteTypeType,
         "ServiceId": str,
         "State": RouteStateType,
         "Tags": Dict[str, str],
         "UriPathRoute": UriPathRouteInputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateServiceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateServiceRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
@@ -868,21 +942,19 @@
         "Tags": Mapping[str, str],
         "UrlEndpoint": UrlEndpointInputTypeDef,
         "VpcId": str,
     },
     total=False,
 )
 
-
 class CreateServiceRequestRequestTypeDef(
     _RequiredCreateServiceRequestRequestTypeDef, _OptionalCreateServiceRequestRequestTypeDef
 ):
     pass
 
-
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
@@ -894,24 +966,24 @@
         "Name": str,
         "OwnerAccountId": str,
         "ServiceId": str,
         "State": ServiceStateType,
         "Tags": Dict[str, str],
         "UrlEndpoint": UrlEndpointInputTypeDef,
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentVpcsResponseTypeDef = TypedDict(
     "ListEnvironmentVpcsResponseTypeDef",
     {
         "EnvironmentVpcList": List[EnvironmentVpcTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceResponseTypeDef = TypedDict(
     "GetServiceResponseTypeDef",
     {
         "ApplicationId": str,
@@ -927,116 +999,18 @@
         "Name": str,
         "OwnerAccountId": str,
         "ServiceId": str,
         "State": ServiceStateType,
         "Tags": Dict[str, str],
         "UrlEndpoint": UrlEndpointConfigTypeDef,
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApplicationsRequestListApplicationsPaginateTypeDef(
-    _RequiredListApplicationsRequestListApplicationsPaginateTypeDef,
-    _OptionalListApplicationsRequestListApplicationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
-    {
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef(
-    _RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-    _OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-):
-    pass
-
-
-ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListRoutesRequestListRoutesPaginateTypeDef",
-    {
-        "ApplicationIdentifier": str,
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListRoutesRequestListRoutesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
-
-class ListRoutesRequestListRoutesPaginateTypeDef(
-    _RequiredListRoutesRequestListRoutesPaginateTypeDef,
-    _OptionalListRoutesRequestListRoutesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "_RequiredListServicesRequestListServicesPaginateTypeDef",
-    {
-        "ApplicationIdentifier": str,
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "_OptionalListServicesRequestListServicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServicesRequestListServicesPaginateTypeDef(
-    _RequiredListServicesRequestListServicesPaginateTypeDef,
-    _OptionalListServicesRequestListServicesPaginateTypeDef,
-):
-    pass
-
-
 ServiceSummaryTypeDef = TypedDict(
     "ServiceSummaryTypeDef",
     {
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
@@ -1058,37 +1032,37 @@
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationSummaryList": List[ApplicationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentsResponseTypeDef = TypedDict(
     "ListEnvironmentsResponseTypeDef",
     {
         "EnvironmentSummaryList": List[EnvironmentSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoutesResponseTypeDef = TypedDict(
     "ListRoutesResponseTypeDef",
     {
         "NextToken": str,
         "RouteSummaryList": List[RouteSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "NextToken": str,
         "ServiceSummaryList": List[ServiceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.pyi` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -35,78 +35,79 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ApiGatewayProxyConfigTypeDef",
     "ApiGatewayProxyInputTypeDef",
     "ApiGatewayProxySummaryTypeDef",
     "ErrorResponseTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateEnvironmentRequestRequestTypeDef",
+    "CreateEnvironmentResponseTypeDef",
     "DefaultRouteInputTypeDef",
     "UriPathRouteInputTypeDef",
     "LambdaEndpointInputTypeDef",
     "UrlEndpointInputTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
+    "DeleteApplicationResponseTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
+    "DeleteEnvironmentResponseTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteRouteRequestRequestTypeDef",
+    "DeleteRouteResponseTypeDef",
     "DeleteServiceRequestRequestTypeDef",
+    "DeleteServiceResponseTypeDef",
     "EnvironmentVpcTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetEnvironmentRequestRequestTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "GetRouteRequestRequestTypeDef",
     "GetServiceRequestRequestTypeDef",
     "LambdaEndpointConfigTypeDef",
     "UrlEndpointConfigTypeDef",
     "LambdaEndpointSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
     "ListEnvironmentVpcsRequestRequestTypeDef",
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
+    "ListRoutesRequestListRoutesPaginateTypeDef",
     "ListRoutesRequestRequestTypeDef",
+    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UrlEndpointSummaryTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateRouteRequestRequestTypeDef",
+    "UpdateRouteResponseTypeDef",
     "CreateApplicationRequestRequestTypeDef",
+    "CreateApplicationResponseTypeDef",
     "ApplicationSummaryTypeDef",
     "EnvironmentSummaryTypeDef",
-    "RouteSummaryTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "CreateEnvironmentResponseTypeDef",
-    "DeleteApplicationResponseTypeDef",
-    "DeleteEnvironmentResponseTypeDef",
-    "DeleteRouteResponseTypeDef",
-    "DeleteServiceResponseTypeDef",
     "GetApplicationResponseTypeDef",
     "GetEnvironmentResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
     "GetRouteResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateRouteResponseTypeDef",
+    "RouteSummaryTypeDef",
     "CreateRouteRequestRequestTypeDef",
     "CreateRouteResponseTypeDef",
     "CreateServiceRequestRequestTypeDef",
     "CreateServiceResponseTypeDef",
     "ListEnvironmentVpcsResponseTypeDef",
     "GetServiceResponseTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    "ListRoutesRequestListRoutesPaginateTypeDef",
-    "ListServicesRequestListServicesPaginateTypeDef",
     "ServiceSummaryTypeDef",
     "ListApplicationsResponseTypeDef",
     "ListEnvironmentsResponseTypeDef",
     "ListRoutesResponseTypeDef",
     "ListServicesResponseTypeDef",
 )
 
@@ -156,25 +157,14 @@
         "Message": str,
         "ResourceIdentifier": str,
         "ResourceType": ErrorResourceTypeType,
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
 _RequiredCreateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentRequestRequestTypeDef",
     {
         "Name": str,
         "NetworkFabricType": NetworkFabricTypeType,
     },
 )
@@ -184,19 +174,38 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateEnvironmentRequestRequestTypeDef(
     _RequiredCreateEnvironmentRequestRequestTypeDef, _OptionalCreateEnvironmentRequestRequestTypeDef
 ):
     pass
 
+
+CreateEnvironmentResponseTypeDef = TypedDict(
+    "CreateEnvironmentResponseTypeDef",
+    {
+        "Arn": str,
+        "CreatedTime": datetime,
+        "Description": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "NetworkFabricType": NetworkFabricTypeType,
+        "OwnerAccountId": str,
+        "State": EnvironmentStateType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DefaultRouteInputTypeDef = TypedDict(
     "DefaultRouteInputTypeDef",
     {
         "ActivationState": RouteActivationStateType,
     },
     total=False,
 )
@@ -207,25 +216,28 @@
         "ActivationState": RouteActivationStateType,
         "SourcePath": str,
     },
 )
 _OptionalUriPathRouteInputTypeDef = TypedDict(
     "_OptionalUriPathRouteInputTypeDef",
     {
+        "AppendSourcePath": bool,
         "IncludeChildPaths": bool,
         "Methods": Sequence[HttpMethodType],
     },
     total=False,
 )
 
+
 class UriPathRouteInputTypeDef(
     _RequiredUriPathRouteInputTypeDef, _OptionalUriPathRouteInputTypeDef
 ):
     pass
 
+
 LambdaEndpointInputTypeDef = TypedDict(
     "LambdaEndpointInputTypeDef",
     {
         "Arn": str,
     },
 )
 
@@ -239,32 +251,59 @@
     "_OptionalUrlEndpointInputTypeDef",
     {
         "HealthUrl": str,
     },
     total=False,
 )
 
+
 class UrlEndpointInputTypeDef(_RequiredUrlEndpointInputTypeDef, _OptionalUrlEndpointInputTypeDef):
     pass
 
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
     },
 )
 
+DeleteApplicationResponseTypeDef = TypedDict(
+    "DeleteApplicationResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "State": ApplicationStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteEnvironmentRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
     },
 )
 
+DeleteEnvironmentResponseTypeDef = TypedDict(
+    "DeleteEnvironmentResponseTypeDef",
+    {
+        "Arn": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "State": EnvironmentStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
@@ -273,23 +312,50 @@
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "RouteIdentifier": str,
     },
 )
 
+DeleteRouteResponseTypeDef = TypedDict(
+    "DeleteRouteResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "LastUpdatedTime": datetime,
+        "RouteId": str,
+        "ServiceId": str,
+        "State": RouteStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteServiceRequestRequestTypeDef = TypedDict(
     "DeleteServiceRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "ServiceIdentifier": str,
     },
 )
 
+DeleteServiceResponseTypeDef = TypedDict(
+    "DeleteServiceResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "EnvironmentId": str,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "ServiceId": str,
+        "State": ServiceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnvironmentVpcTypeDef = TypedDict(
     "EnvironmentVpcTypeDef",
     {
         "AccountId": str,
         "CidrBlocks": List[str],
         "CreatedTime": datetime,
         "EnvironmentId": str,
@@ -318,14 +384,22 @@
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRouteRequestRequestTypeDef = TypedDict(
     "GetRouteRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "RouteIdentifier": str,
     },
@@ -361,24 +435,36 @@
     "LambdaEndpointSummaryTypeDef",
     {
         "Arn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationsRequestListApplicationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListApplicationsRequestListApplicationsPaginateTypeDef(
+    _RequiredListApplicationsRequestListApplicationsPaginateTypeDef,
+    _OptionalListApplicationsRequestListApplicationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApplicationsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationsRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
     },
 )
 _OptionalListApplicationsRequestRequestTypeDef = TypedDict(
@@ -386,19 +472,43 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListApplicationsRequestRequestTypeDef(
     _RequiredListApplicationsRequestRequestTypeDef, _OptionalListApplicationsRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
+    "_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
+    {
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
+    "_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef(
+    _RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
+    _OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEnvironmentVpcsRequestRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentVpcsRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
     },
 )
 _OptionalListEnvironmentVpcsRequestRequestTypeDef = TypedDict(
@@ -406,29 +516,62 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListEnvironmentVpcsRequestRequestTypeDef(
     _RequiredListEnvironmentVpcsRequestRequestTypeDef,
     _OptionalListEnvironmentVpcsRequestRequestTypeDef,
 ):
     pass
 
+
+ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentsRequestRequestTypeDef = TypedDict(
     "ListEnvironmentsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
+    "_RequiredListRoutesRequestListRoutesPaginateTypeDef",
+    {
+        "ApplicationIdentifier": str,
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
+    "_OptionalListRoutesRequestListRoutesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRoutesRequestListRoutesPaginateTypeDef(
+    _RequiredListRoutesRequestListRoutesPaginateTypeDef,
+    _OptionalListRoutesRequestListRoutesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredListRoutesRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
     },
 )
@@ -437,19 +580,44 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListRoutesRequestRequestTypeDef(
     _RequiredListRoutesRequestRequestTypeDef, _OptionalListRoutesRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "_RequiredListServicesRequestListServicesPaginateTypeDef",
+    {
+        "ApplicationIdentifier": str,
+        "EnvironmentIdentifier": str,
+    },
+)
+_OptionalListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "_OptionalListServicesRequestListServicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServicesRequestListServicesPaginateTypeDef(
+    _RequiredListServicesRequestListServicesPaginateTypeDef,
+    _OptionalListServicesRequestListServicesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServicesRequestRequestTypeDef = TypedDict(
     "_RequiredListServicesRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
     },
 )
@@ -458,34 +626,65 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListServicesRequestRequestTypeDef(
     _RequiredListServicesRequestRequestTypeDef, _OptionalListServicesRequestRequestTypeDef
 ):
     pass
 
+
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
         "Policy": str,
         "ResourceArn": str,
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
 UrlEndpointSummaryTypeDef = TypedDict(
     "UrlEndpointSummaryTypeDef",
     {
         "HealthUrl": str,
         "Url": str,
     },
     total=False,
@@ -513,14 +712,27 @@
         "ActivationState": RouteActivationStateType,
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
         "RouteIdentifier": str,
     },
 )
 
+UpdateRouteResponseTypeDef = TypedDict(
+    "UpdateRouteResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "Arn": str,
+        "LastUpdatedTime": datetime,
+        "RouteId": str,
+        "ServiceId": str,
+        "State": RouteStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationRequestRequestTypeDef",
     {
         "EnvironmentIdentifier": str,
         "Name": str,
         "ProxyType": Literal["API_GATEWAY"],
         "VpcId": str,
@@ -532,170 +744,79 @@
         "ApiGatewayProxy": ApiGatewayProxyInputTypeDef,
         "ClientToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
-ApplicationSummaryTypeDef = TypedDict(
-    "ApplicationSummaryTypeDef",
+
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "ApiGatewayProxy": ApiGatewayProxySummaryTypeDef,
+        "ApiGatewayProxy": ApiGatewayProxyInputTypeDef,
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
         "EnvironmentId": str,
-        "Error": ErrorResponseTypeDef,
         "LastUpdatedTime": datetime,
         "Name": str,
         "OwnerAccountId": str,
         "ProxyType": Literal["API_GATEWAY"],
         "State": ApplicationStateType,
         "Tags": Dict[str, str],
         "VpcId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-EnvironmentSummaryTypeDef = TypedDict(
-    "EnvironmentSummaryTypeDef",
-    {
-        "Arn": str,
-        "CreatedTime": datetime,
-        "Description": str,
-        "EnvironmentId": str,
-        "Error": ErrorResponseTypeDef,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "NetworkFabricType": NetworkFabricTypeType,
-        "OwnerAccountId": str,
-        "State": EnvironmentStateType,
-        "Tags": Dict[str, str],
-        "TransitGatewayId": str,
-    },
-    total=False,
 )
 
-RouteSummaryTypeDef = TypedDict(
-    "RouteSummaryTypeDef",
+ApplicationSummaryTypeDef = TypedDict(
+    "ApplicationSummaryTypeDef",
     {
+        "ApiGatewayProxy": ApiGatewayProxySummaryTypeDef,
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
         "EnvironmentId": str,
         "Error": ErrorResponseTypeDef,
-        "IncludeChildPaths": bool,
-        "LastUpdatedTime": datetime,
-        "Methods": List[HttpMethodType],
-        "OwnerAccountId": str,
-        "PathResourceToId": Dict[str, str],
-        "RouteId": str,
-        "RouteType": RouteTypeType,
-        "ServiceId": str,
-        "SourcePath": str,
-        "State": RouteStateType,
-        "Tags": Dict[str, str],
-    },
-    total=False,
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "ApiGatewayProxy": ApiGatewayProxyInputTypeDef,
-        "ApplicationId": str,
-        "Arn": str,
-        "CreatedByAccountId": str,
-        "CreatedTime": datetime,
-        "EnvironmentId": str,
         "LastUpdatedTime": datetime,
         "Name": str,
         "OwnerAccountId": str,
         "ProxyType": Literal["API_GATEWAY"],
         "State": ApplicationStateType,
         "Tags": Dict[str, str],
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-CreateEnvironmentResponseTypeDef = TypedDict(
-    "CreateEnvironmentResponseTypeDef",
+EnvironmentSummaryTypeDef = TypedDict(
+    "EnvironmentSummaryTypeDef",
     {
         "Arn": str,
         "CreatedTime": datetime,
         "Description": str,
         "EnvironmentId": str,
+        "Error": ErrorResponseTypeDef,
         "LastUpdatedTime": datetime,
         "Name": str,
         "NetworkFabricType": NetworkFabricTypeType,
         "OwnerAccountId": str,
         "State": EnvironmentStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteApplicationResponseTypeDef = TypedDict(
-    "DeleteApplicationResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "Arn": str,
-        "EnvironmentId": str,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "State": ApplicationStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEnvironmentResponseTypeDef = TypedDict(
-    "DeleteEnvironmentResponseTypeDef",
-    {
-        "Arn": str,
-        "EnvironmentId": str,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "State": EnvironmentStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRouteResponseTypeDef = TypedDict(
-    "DeleteRouteResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "Arn": str,
-        "LastUpdatedTime": datetime,
-        "RouteId": str,
-        "ServiceId": str,
-        "State": RouteStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteServiceResponseTypeDef = TypedDict(
-    "DeleteServiceResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "Arn": str,
-        "EnvironmentId": str,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "ServiceId": str,
-        "State": ServiceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TransitGatewayId": str,
     },
+    total=False,
 )
 
 GetApplicationResponseTypeDef = TypedDict(
     "GetApplicationResponseTypeDef",
     {
         "ApiGatewayProxy": ApiGatewayProxyConfigTypeDef,
         "ApplicationId": str,
@@ -707,15 +828,15 @@
         "LastUpdatedTime": datetime,
         "Name": str,
         "OwnerAccountId": str,
         "ProxyType": Literal["API_GATEWAY"],
         "State": ApplicationStateType,
         "Tags": Dict[str, str],
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnvironmentResponseTypeDef = TypedDict(
     "GetEnvironmentResponseTypeDef",
     {
         "Arn": str,
@@ -726,29 +847,22 @@
         "LastUpdatedTime": datetime,
         "Name": str,
         "NetworkFabricType": NetworkFabricTypeType,
         "OwnerAccountId": str,
         "State": EnvironmentStateType,
         "Tags": Dict[str, str],
         "TransitGatewayId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResponseTypeDef = TypedDict(
     "GetRouteResponseTypeDef",
     {
+        "AppendSourcePath": bool,
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
         "EnvironmentId": str,
         "Error": ErrorResponseTypeDef,
         "IncludeChildPaths": bool,
@@ -758,37 +872,41 @@
         "PathResourceToId": Dict[str, str],
         "RouteId": str,
         "RouteType": RouteTypeType,
         "ServiceId": str,
         "SourcePath": str,
         "State": RouteStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRouteResponseTypeDef = TypedDict(
-    "UpdateRouteResponseTypeDef",
+RouteSummaryTypeDef = TypedDict(
+    "RouteSummaryTypeDef",
     {
+        "AppendSourcePath": bool,
         "ApplicationId": str,
         "Arn": str,
+        "CreatedByAccountId": str,
+        "CreatedTime": datetime,
+        "EnvironmentId": str,
+        "Error": ErrorResponseTypeDef,
+        "IncludeChildPaths": bool,
         "LastUpdatedTime": datetime,
+        "Methods": List[HttpMethodType],
+        "OwnerAccountId": str,
+        "PathResourceToId": Dict[str, str],
         "RouteId": str,
+        "RouteType": RouteTypeType,
         "ServiceId": str,
+        "SourcePath": str,
         "State": RouteStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Dict[str, str],
     },
+    total=False,
 )
 
 _RequiredCreateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
         "EnvironmentIdentifier": str,
@@ -803,19 +921,21 @@
         "DefaultRoute": DefaultRouteInputTypeDef,
         "Tags": Mapping[str, str],
         "UriPathRoute": UriPathRouteInputTypeDef,
     },
     total=False,
 )
 
+
 class CreateRouteRequestRequestTypeDef(
     _RequiredCreateRouteRequestRequestTypeDef, _OptionalCreateRouteRequestRequestTypeDef
 ):
     pass
 
+
 CreateRouteResponseTypeDef = TypedDict(
     "CreateRouteResponseTypeDef",
     {
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
@@ -823,15 +943,15 @@
         "OwnerAccountId": str,
         "RouteId": str,
         "RouteType": RouteTypeType,
         "ServiceId": str,
         "State": RouteStateType,
         "Tags": Dict[str, str],
         "UriPathRoute": UriPathRouteInputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateServiceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateServiceRequestRequestTypeDef",
     {
         "ApplicationIdentifier": str,
@@ -849,19 +969,21 @@
         "Tags": Mapping[str, str],
         "UrlEndpoint": UrlEndpointInputTypeDef,
         "VpcId": str,
     },
     total=False,
 )
 
+
 class CreateServiceRequestRequestTypeDef(
     _RequiredCreateServiceRequestRequestTypeDef, _OptionalCreateServiceRequestRequestTypeDef
 ):
     pass
 
+
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
@@ -873,24 +995,24 @@
         "Name": str,
         "OwnerAccountId": str,
         "ServiceId": str,
         "State": ServiceStateType,
         "Tags": Dict[str, str],
         "UrlEndpoint": UrlEndpointInputTypeDef,
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentVpcsResponseTypeDef = TypedDict(
     "ListEnvironmentVpcsResponseTypeDef",
     {
         "EnvironmentVpcList": List[EnvironmentVpcTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceResponseTypeDef = TypedDict(
     "GetServiceResponseTypeDef",
     {
         "ApplicationId": str,
@@ -906,108 +1028,18 @@
         "Name": str,
         "OwnerAccountId": str,
         "ServiceId": str,
         "State": ServiceStateType,
         "Tags": Dict[str, str],
         "UrlEndpoint": UrlEndpointConfigTypeDef,
         "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApplicationsRequestListApplicationsPaginateTypeDef(
-    _RequiredListApplicationsRequestListApplicationsPaginateTypeDef,
-    _OptionalListApplicationsRequestListApplicationsPaginateTypeDef,
-):
-    pass
-
-_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
-    "_RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
-    {
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef = TypedDict(
-    "_OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef(
-    _RequiredListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-    _OptionalListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-):
-    pass
-
-ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
-    "_RequiredListRoutesRequestListRoutesPaginateTypeDef",
-    {
-        "ApplicationIdentifier": str,
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListRoutesRequestListRoutesPaginateTypeDef = TypedDict(
-    "_OptionalListRoutesRequestListRoutesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListRoutesRequestListRoutesPaginateTypeDef(
-    _RequiredListRoutesRequestListRoutesPaginateTypeDef,
-    _OptionalListRoutesRequestListRoutesPaginateTypeDef,
-):
-    pass
-
-_RequiredListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "_RequiredListServicesRequestListServicesPaginateTypeDef",
-    {
-        "ApplicationIdentifier": str,
-        "EnvironmentIdentifier": str,
-    },
-)
-_OptionalListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "_OptionalListServicesRequestListServicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServicesRequestListServicesPaginateTypeDef(
-    _RequiredListServicesRequestListServicesPaginateTypeDef,
-    _OptionalListServicesRequestListServicesPaginateTypeDef,
-):
-    pass
-
 ServiceSummaryTypeDef = TypedDict(
     "ServiceSummaryTypeDef",
     {
         "ApplicationId": str,
         "Arn": str,
         "CreatedByAccountId": str,
         "CreatedTime": datetime,
@@ -1029,37 +1061,37 @@
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationSummaryList": List[ApplicationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentsResponseTypeDef = TypedDict(
     "ListEnvironmentsResponseTypeDef",
     {
         "EnvironmentSummaryList": List[EnvironmentSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoutesResponseTypeDef = TypedDict(
     "ListRoutesResponseTypeDef",
     {
         "NextToken": str,
         "RouteSummaryList": List[RouteSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "NextToken": str,
         "ServiceSummaryList": List[ServiceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/PKG-INFO` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migration-hub-refactor-spaces
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubRefactorSpaces 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migration-hub-refactor-spaces"></a>
 
 # types-aiobotocore-migration-hub-refactor-spaces
 
 [![PyPI - types-aiobotocore-migration-hub-refactor-spaces](https://img.shields.io/pypi/v/types-aiobotocore-migration-hub-refactor-spaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migration-hub-refactor-spaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migration-hub-refactor-spaces)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migration-hub-refactor-spaces?color=blue)](https://pypistats.org/packages/types-aiobotocore-migration-hub-refactor-spaces)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubRefactorSpaces 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
+[aiobotocore.MigrationHubRefactorSpaces 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migration-hub-refactor-spaces.html#MigrationHubRefactorSpaces)
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
 [types-aiobotocore-migration-hub-refactor-spaces docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migration_hub_refactor_spaces/).
 
 See how it helps to find and fix potential bugs:
 
@@ -355,73 +355,73 @@
 
 ```python
 from types_aiobotocore_migration_hub_refactor_spaces.type_defs import (
     ApiGatewayProxyConfigTypeDef,
     ApiGatewayProxyInputTypeDef,
     ApiGatewayProxySummaryTypeDef,
     ErrorResponseTypeDef,
-    ResponseMetadataTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
+    CreateEnvironmentResponseTypeDef,
     DefaultRouteInputTypeDef,
     UriPathRouteInputTypeDef,
     LambdaEndpointInputTypeDef,
     UrlEndpointInputTypeDef,
     DeleteApplicationRequestRequestTypeDef,
+    DeleteApplicationResponseTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
+    DeleteEnvironmentResponseTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteRouteRequestRequestTypeDef,
+    DeleteRouteResponseTypeDef,
     DeleteServiceRequestRequestTypeDef,
+    DeleteServiceResponseTypeDef,
     EnvironmentVpcTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetRouteRequestRequestTypeDef,
     GetServiceRequestRequestTypeDef,
     LambdaEndpointConfigTypeDef,
     UrlEndpointConfigTypeDef,
     LambdaEndpointSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
     ListEnvironmentVpcsRequestRequestTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListRoutesRequestListRoutesPaginateTypeDef,
     ListRoutesRequestRequestTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UrlEndpointSummaryTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateRouteRequestRequestTypeDef,
+    UpdateRouteResponseTypeDef,
     CreateApplicationRequestRequestTypeDef,
+    CreateApplicationResponseTypeDef,
     ApplicationSummaryTypeDef,
     EnvironmentSummaryTypeDef,
-    RouteSummaryTypeDef,
-    CreateApplicationResponseTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    DeleteApplicationResponseTypeDef,
-    DeleteEnvironmentResponseTypeDef,
-    DeleteRouteResponseTypeDef,
-    DeleteServiceResponseTypeDef,
     GetApplicationResponseTypeDef,
     GetEnvironmentResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
     GetRouteResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateRouteResponseTypeDef,
+    RouteSummaryTypeDef,
     CreateRouteRequestRequestTypeDef,
     CreateRouteResponseTypeDef,
     CreateServiceRequestRequestTypeDef,
     CreateServiceResponseTypeDef,
     ListEnvironmentVpcsResponseTypeDef,
     GetServiceResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListEnvironmentVpcsRequestListEnvironmentVpcsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
-    ListRoutesRequestListRoutesPaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
     ServiceSummaryTypeDef,
     ListApplicationsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     ListRoutesResponseTypeDef,
     ListServicesResponseTypeDef,
 )
 
@@ -433,43 +433,43 @@
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

### Comparing `types-aiobotocore-migration-hub-refactor-spaces-2.5.0.post1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/SOURCES.txt` & `types-aiobotocore-migration-hub-refactor-spaces-2.5.1/types_aiobotocore_migration_hub_refactor_spaces.egg-info/SOURCES.txt`

 * *Files identical despite different names*

