# Comparing `tmp/types-aiobotocore-schemas-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-schemas-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-schemas-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-schemas-2.5.1.tar", last modified: Wed Jun 28 01:44:09 2023, max compression
```

## Comparing `types-aiobotocore-schemas-2.5.0.post1.tar` & `types-aiobotocore-schemas-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.335608 types-aiobotocore-schemas-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17123 2023-03-11 12:27:18.331608 types-aiobotocore-schemas-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15552 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.335608 types-aiobotocore-schemas-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:23:35.000000 types-aiobotocore-schemas-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.331608 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/
--rw-r--r--   0 runner    (1001) docker     (123)     1647 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1646 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25263 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    25217 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8741 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8739 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6686 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6678 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    26136 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    26097 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1674 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1673 2023-03-11 12:23:36.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.331608 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17123 2023-03-11 12:27:18.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      886 2023-03-11 12:27:18.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:27:18.000000 types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.058211 types-aiobotocore-schemas-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17115 2023-06-28 01:44:09.058211 types-aiobotocore-schemas-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15550 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:09.058211 types-aiobotocore-schemas-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.058211 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/
+-rw-r--r--   0 runner    (1001) docker     (123)     1647 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1646 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25263 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25217 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8950 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8948 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6608 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6601 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    26196 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26157 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:22.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1674 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1673 2023-06-28 01:40:23.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.058211 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17115 2023-06-28 01:44:08.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      886 2023-06-28 01:44:08.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:08.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:08.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:08.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:44:08.000000 types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-schemas-2.5.0.post1/LICENSE` & `types-aiobotocore-schemas-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/PKG-INFO` & `types-aiobotocore-schemas-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-schemas
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Schemas 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Schemas 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-schemas"></a>
 
 # types-aiobotocore-schemas
 
 [![PyPI - types-aiobotocore-schemas](https://img.shields.io/pypi/v/types-aiobotocore-schemas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-schemas)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-schemas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-schemas)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-schemas?color=blue)](https://pypistats.org/packages/types-aiobotocore-schemas)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Schemas 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
+[aiobotocore.Schemas 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
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
 [types-aiobotocore-schemas docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,79 +358,79 @@
 
 `types_aiobotocore_schemas.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_schemas.type_defs import (
     CreateDiscovererRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDiscovererResponseTypeDef,
     CreateRegistryRequestRequestTypeDef,
+    CreateRegistryResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
     DeleteDiscovererRequestRequestTypeDef,
     DeleteRegistryRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSchemaRequestRequestTypeDef,
     DeleteSchemaVersionRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeCodeBindingRequestRequestTypeDef,
+    DescribeCodeBindingResponseTypeDef,
     DescribeDiscovererRequestRequestTypeDef,
+    DescribeDiscovererResponseTypeDef,
     DescribeRegistryRequestRequestTypeDef,
+    DescribeRegistryResponseTypeDef,
     DescribeSchemaRequestRequestTypeDef,
+    DescribeSchemaResponseTypeDef,
     DiscovererSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportSchemaRequestRequestTypeDef,
+    ExportSchemaResponseTypeDef,
     GetCodeBindingSourceRequestRequestTypeDef,
+    GetCodeBindingSourceResponseTypeDef,
     GetDiscoveredSchemaRequestRequestTypeDef,
+    GetDiscoveredSchemaResponseTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePolicyResponseTypeDef,
+    ListDiscoverersRequestListDiscoverersPaginateTypeDef,
     ListDiscoverersRequestRequestTypeDef,
+    ListRegistriesRequestListRegistriesPaginateTypeDef,
     ListRegistriesRequestRequestTypeDef,
     RegistrySummaryTypeDef,
+    ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
     ListSchemaVersionsRequestRequestTypeDef,
     SchemaVersionSummaryTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
     SchemaSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutCodeBindingRequestRequestTypeDef,
+    PutCodeBindingResponseTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     SearchSchemaVersionSummaryTypeDef,
     SearchSchemasRequestRequestTypeDef,
+    SearchSchemasRequestSearchSchemasPaginateTypeDef,
     StartDiscovererRequestRequestTypeDef,
+    StartDiscovererResponseTypeDef,
     StopDiscovererRequestRequestTypeDef,
+    StopDiscovererResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDiscovererRequestRequestTypeDef,
-    UpdateRegistryRequestRequestTypeDef,
-    UpdateSchemaRequestRequestTypeDef,
-    CreateDiscovererResponseTypeDef,
-    CreateRegistryResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    DescribeCodeBindingResponseTypeDef,
-    DescribeDiscovererResponseTypeDef,
-    DescribeRegistryResponseTypeDef,
-    DescribeSchemaResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportSchemaResponseTypeDef,
-    GetCodeBindingSourceResponseTypeDef,
-    GetDiscoveredSchemaResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutCodeBindingResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    StartDiscovererResponseTypeDef,
-    StopDiscovererResponseTypeDef,
     UpdateDiscovererResponseTypeDef,
+    UpdateRegistryRequestRequestTypeDef,
     UpdateRegistryResponseTypeDef,
+    UpdateSchemaRequestRequestTypeDef,
     UpdateSchemaResponseTypeDef,
     DescribeCodeBindingRequestCodeBindingExistsWaitTypeDef,
     ListDiscoverersResponseTypeDef,
-    ListDiscoverersRequestListDiscoverersPaginateTypeDef,
-    ListRegistriesRequestListRegistriesPaginateTypeDef,
-    ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    SearchSchemasRequestSearchSchemasPaginateTypeDef,
     ListRegistriesResponseTypeDef,
     ListSchemaVersionsResponseTypeDef,
     ListSchemasResponseTypeDef,
     SearchSchemaSummaryTypeDef,
     SearchSchemasResponseTypeDef,
 )
 
@@ -442,43 +442,43 @@
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/README.md` & `types-aiobotocore-schemas-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-schemas"></a>
 
 # types-aiobotocore-schemas
 
 [![PyPI - types-aiobotocore-schemas](https://img.shields.io/pypi/v/types-aiobotocore-schemas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-schemas)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-schemas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-schemas)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-schemas?color=blue)](https://pypistats.org/packages/types-aiobotocore-schemas)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Schemas 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
+[aiobotocore.Schemas 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
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
 [types-aiobotocore-schemas docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,79 +325,79 @@
 
 `types_aiobotocore_schemas.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_schemas.type_defs import (
     CreateDiscovererRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDiscovererResponseTypeDef,
     CreateRegistryRequestRequestTypeDef,
+    CreateRegistryResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
     DeleteDiscovererRequestRequestTypeDef,
     DeleteRegistryRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSchemaRequestRequestTypeDef,
     DeleteSchemaVersionRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeCodeBindingRequestRequestTypeDef,
+    DescribeCodeBindingResponseTypeDef,
     DescribeDiscovererRequestRequestTypeDef,
+    DescribeDiscovererResponseTypeDef,
     DescribeRegistryRequestRequestTypeDef,
+    DescribeRegistryResponseTypeDef,
     DescribeSchemaRequestRequestTypeDef,
+    DescribeSchemaResponseTypeDef,
     DiscovererSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportSchemaRequestRequestTypeDef,
+    ExportSchemaResponseTypeDef,
     GetCodeBindingSourceRequestRequestTypeDef,
+    GetCodeBindingSourceResponseTypeDef,
     GetDiscoveredSchemaRequestRequestTypeDef,
+    GetDiscoveredSchemaResponseTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePolicyResponseTypeDef,
+    ListDiscoverersRequestListDiscoverersPaginateTypeDef,
     ListDiscoverersRequestRequestTypeDef,
+    ListRegistriesRequestListRegistriesPaginateTypeDef,
     ListRegistriesRequestRequestTypeDef,
     RegistrySummaryTypeDef,
+    ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
     ListSchemaVersionsRequestRequestTypeDef,
     SchemaVersionSummaryTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
     SchemaSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutCodeBindingRequestRequestTypeDef,
+    PutCodeBindingResponseTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     SearchSchemaVersionSummaryTypeDef,
     SearchSchemasRequestRequestTypeDef,
+    SearchSchemasRequestSearchSchemasPaginateTypeDef,
     StartDiscovererRequestRequestTypeDef,
+    StartDiscovererResponseTypeDef,
     StopDiscovererRequestRequestTypeDef,
+    StopDiscovererResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDiscovererRequestRequestTypeDef,
-    UpdateRegistryRequestRequestTypeDef,
-    UpdateSchemaRequestRequestTypeDef,
-    CreateDiscovererResponseTypeDef,
-    CreateRegistryResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    DescribeCodeBindingResponseTypeDef,
-    DescribeDiscovererResponseTypeDef,
-    DescribeRegistryResponseTypeDef,
-    DescribeSchemaResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportSchemaResponseTypeDef,
-    GetCodeBindingSourceResponseTypeDef,
-    GetDiscoveredSchemaResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutCodeBindingResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    StartDiscovererResponseTypeDef,
-    StopDiscovererResponseTypeDef,
     UpdateDiscovererResponseTypeDef,
+    UpdateRegistryRequestRequestTypeDef,
     UpdateRegistryResponseTypeDef,
+    UpdateSchemaRequestRequestTypeDef,
     UpdateSchemaResponseTypeDef,
     DescribeCodeBindingRequestCodeBindingExistsWaitTypeDef,
     ListDiscoverersResponseTypeDef,
-    ListDiscoverersRequestListDiscoverersPaginateTypeDef,
-    ListRegistriesRequestListRegistriesPaginateTypeDef,
-    ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    SearchSchemasRequestSearchSchemasPaginateTypeDef,
     ListRegistriesResponseTypeDef,
     ListSchemaVersionsResponseTypeDef,
     ListSchemasResponseTypeDef,
     SearchSchemaSummaryTypeDef,
     SearchSchemasResponseTypeDef,
 )
 
@@ -409,43 +409,43 @@
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/setup.py` & `types-aiobotocore-schemas-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-schemas.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-schemas",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_schemas"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Schemas 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Schemas 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/"
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/__init__.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/__init__.pyi` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/__main__.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Schemas 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Schemas 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas\nOther"
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/client.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/client.pyi` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/literals.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -106,14 +106,15 @@
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
@@ -192,14 +193,15 @@
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
@@ -210,14 +212,15 @@
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
@@ -253,14 +256,15 @@
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
@@ -279,16 +283,19 @@
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
@@ -372,15 +379,17 @@
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/literals.pyi` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -104,14 +104,15 @@
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
@@ -190,14 +191,15 @@
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
@@ -208,14 +210,15 @@
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
@@ -251,14 +254,15 @@
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
@@ -277,16 +281,19 @@
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
@@ -370,15 +377,17 @@
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/paginator.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_discoverers_paginator: ListDiscoverersPaginator = client.get_paginator("list_discoverers")
         list_registries_paginator: ListRegistriesPaginator = client.get_paginator("list_registries")
         list_schema_versions_paginator: ListSchemaVersionsPaginator = client.get_paginator("list_schema_versions")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
         search_schemas_paginator: SearchSchemasPaginator = client.get_paginator("search_schemas")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDiscoverersResponseTypeDef,
     ListRegistriesResponseTypeDef,
     ListSchemasResponseTypeDef,
     ListSchemaVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
     SearchSchemasResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDiscoverersPaginator",
     "ListRegistriesPaginator",
     "ListSchemaVersionsPaginator",
     "ListSchemasPaginator",
     "SearchSchemasPaginator",
 )
@@ -75,15 +68,15 @@
     """
 
     def paginate(
         self,
         *,
         DiscovererIdPrefix: str = ...,
         SourceArnPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDiscoverersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListDiscoverers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listdiscovererspaginator)
         """
 
 
@@ -94,30 +87,34 @@
     """
 
     def paginate(
         self,
         *,
         RegistryNamePrefix: str = ...,
         Scope: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRegistriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListRegistries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listregistriespaginator)
         """
 
 
 class ListSchemaVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemaVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listschemaversionspaginator)
     """
 
     def paginate(
-        self, *, RegistryName: str, SchemaName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        RegistryName: str,
+        SchemaName: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemaVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemaVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listschemaversionspaginator)
         """
 
 
@@ -128,28 +125,28 @@
     """
 
     def paginate(
         self,
         *,
         RegistryName: str,
         SchemaNamePrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listschemaspaginator)
         """
 
 
 class SearchSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.SearchSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#searchschemaspaginator)
     """
 
     def paginate(
-        self, *, Keywords: str, RegistryName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Keywords: str, RegistryName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.SearchSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#searchschemaspaginator)
         """
```

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/paginator.pyi` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_discoverers_paginator: ListDiscoverersPaginator = client.get_paginator("list_discoverers")
         list_registries_paginator: ListRegistriesPaginator = client.get_paginator("list_registries")
         list_schema_versions_paginator: ListSchemaVersionsPaginator = client.get_paginator("list_schema_versions")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
         search_schemas_paginator: SearchSchemasPaginator = client.get_paginator("search_schemas")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDiscoverersResponseTypeDef,
     ListRegistriesResponseTypeDef,
     ListSchemasResponseTypeDef,
     ListSchemaVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
     SearchSchemasResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDiscoverersPaginator",
     "ListRegistriesPaginator",
     "ListSchemaVersionsPaginator",
     "ListSchemasPaginator",
     "SearchSchemasPaginator",
 )
@@ -71,15 +65,15 @@
     """
 
     def paginate(
         self,
         *,
         DiscovererIdPrefix: str = ...,
         SourceArnPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDiscoverersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListDiscoverers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listdiscovererspaginator)
         """
 
 class ListRegistriesPaginator(AioPaginator):
@@ -89,29 +83,33 @@
     """
 
     def paginate(
         self,
         *,
         RegistryNamePrefix: str = ...,
         Scope: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRegistriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListRegistries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listregistriespaginator)
         """
 
 class ListSchemaVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemaVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listschemaversionspaginator)
     """
 
     def paginate(
-        self, *, RegistryName: str, SchemaName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        RegistryName: str,
+        SchemaName: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemaVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemaVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listschemaversionspaginator)
         """
 
 class ListSchemasPaginator(AioPaginator):
@@ -121,27 +119,27 @@
     """
 
     def paginate(
         self,
         *,
         RegistryName: str,
         SchemaNamePrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#listschemaspaginator)
         """
 
 class SearchSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.SearchSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#searchschemaspaginator)
     """
 
     def paginate(
-        self, *, Keywords: str, RegistryName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Keywords: str, RegistryName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas.Paginator.SearchSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/paginators/#searchschemaspaginator)
         """
```

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/type_defs.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,79 +23,79 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CreateDiscovererRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDiscovererResponseTypeDef",
     "CreateRegistryRequestRequestTypeDef",
+    "CreateRegistryResponseTypeDef",
     "CreateSchemaRequestRequestTypeDef",
+    "CreateSchemaResponseTypeDef",
     "DeleteDiscovererRequestRequestTypeDef",
     "DeleteRegistryRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSchemaRequestRequestTypeDef",
     "DeleteSchemaVersionRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeCodeBindingRequestRequestTypeDef",
+    "DescribeCodeBindingResponseTypeDef",
     "DescribeDiscovererRequestRequestTypeDef",
+    "DescribeDiscovererResponseTypeDef",
     "DescribeRegistryRequestRequestTypeDef",
+    "DescribeRegistryResponseTypeDef",
     "DescribeSchemaRequestRequestTypeDef",
+    "DescribeSchemaResponseTypeDef",
     "DiscovererSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportSchemaRequestRequestTypeDef",
+    "ExportSchemaResponseTypeDef",
     "GetCodeBindingSourceRequestRequestTypeDef",
+    "GetCodeBindingSourceResponseTypeDef",
     "GetDiscoveredSchemaRequestRequestTypeDef",
+    "GetDiscoveredSchemaResponseTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePolicyResponseTypeDef",
+    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
     "ListDiscoverersRequestRequestTypeDef",
+    "ListRegistriesRequestListRegistriesPaginateTypeDef",
     "ListRegistriesRequestRequestTypeDef",
     "RegistrySummaryTypeDef",
+    "ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
     "ListSchemaVersionsRequestRequestTypeDef",
     "SchemaVersionSummaryTypeDef",
+    "ListSchemasRequestListSchemasPaginateTypeDef",
     "ListSchemasRequestRequestTypeDef",
     "SchemaSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutCodeBindingRequestRequestTypeDef",
+    "PutCodeBindingResponseTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchSchemaVersionSummaryTypeDef",
     "SearchSchemasRequestRequestTypeDef",
+    "SearchSchemasRequestSearchSchemasPaginateTypeDef",
     "StartDiscovererRequestRequestTypeDef",
+    "StartDiscovererResponseTypeDef",
     "StopDiscovererRequestRequestTypeDef",
+    "StopDiscovererResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDiscovererRequestRequestTypeDef",
-    "UpdateRegistryRequestRequestTypeDef",
-    "UpdateSchemaRequestRequestTypeDef",
-    "CreateDiscovererResponseTypeDef",
-    "CreateRegistryResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "DescribeCodeBindingResponseTypeDef",
-    "DescribeDiscovererResponseTypeDef",
-    "DescribeRegistryResponseTypeDef",
-    "DescribeSchemaResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportSchemaResponseTypeDef",
-    "GetCodeBindingSourceResponseTypeDef",
-    "GetDiscoveredSchemaResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutCodeBindingResponseTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "StartDiscovererResponseTypeDef",
-    "StopDiscovererResponseTypeDef",
     "UpdateDiscovererResponseTypeDef",
+    "UpdateRegistryRequestRequestTypeDef",
     "UpdateRegistryResponseTypeDef",
+    "UpdateSchemaRequestRequestTypeDef",
     "UpdateSchemaResponseTypeDef",
     "DescribeCodeBindingRequestCodeBindingExistsWaitTypeDef",
     "ListDiscoverersResponseTypeDef",
-    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
-    "ListRegistriesRequestListRegistriesPaginateTypeDef",
-    "ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    "SearchSchemasRequestSearchSchemasPaginateTypeDef",
     "ListRegistriesResponseTypeDef",
     "ListSchemaVersionsResponseTypeDef",
     "ListSchemasResponseTypeDef",
     "SearchSchemaSummaryTypeDef",
     "SearchSchemasResponseTypeDef",
 )
 
@@ -118,22 +118,25 @@
 
 class CreateDiscovererRequestRequestTypeDef(
     _RequiredCreateDiscovererRequestRequestTypeDef, _OptionalCreateDiscovererRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDiscovererResponseTypeDef = TypedDict(
+    "CreateDiscovererResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Description": str,
+        "DiscovererArn": str,
+        "DiscovererId": str,
+        "SourceArn": str,
+        "State": DiscovererStateType,
+        "CrossAccount": bool,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRegistryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRegistryRequestRequestTypeDef",
     {
         "RegistryName": str,
@@ -151,14 +154,25 @@
 
 class CreateRegistryRequestRequestTypeDef(
     _RequiredCreateRegistryRequestRequestTypeDef, _OptionalCreateRegistryRequestRequestTypeDef
 ):
     pass
 
 
+CreateRegistryResponseTypeDef = TypedDict(
+    "CreateRegistryResponseTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSchemaRequestRequestTypeDef",
     {
         "Content": str,
         "RegistryName": str,
         "SchemaName": str,
         "Type": TypeType,
@@ -176,14 +190,29 @@
 
 class CreateSchemaRequestRequestTypeDef(
     _RequiredCreateSchemaRequestRequestTypeDef, _OptionalCreateSchemaRequestRequestTypeDef
 ):
     pass
 
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "Description": str,
+        "LastModified": datetime,
+        "SchemaArn": str,
+        "SchemaName": str,
+        "SchemaVersion": str,
+        "Tags": Dict[str, str],
+        "Type": str,
+        "VersionCreatedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDiscovererRequestRequestTypeDef = TypedDict(
     "DeleteDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
@@ -248,28 +277,64 @@
 class DescribeCodeBindingRequestRequestTypeDef(
     _RequiredDescribeCodeBindingRequestRequestTypeDef,
     _OptionalDescribeCodeBindingRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeCodeBindingResponseTypeDef = TypedDict(
+    "DescribeCodeBindingResponseTypeDef",
+    {
+        "CreationDate": datetime,
+        "LastModified": datetime,
+        "SchemaVersion": str,
+        "Status": CodeGenerationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDiscovererRequestRequestTypeDef = TypedDict(
     "DescribeDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
+DescribeDiscovererResponseTypeDef = TypedDict(
+    "DescribeDiscovererResponseTypeDef",
+    {
+        "Description": str,
+        "DiscovererArn": str,
+        "DiscovererId": str,
+        "SourceArn": str,
+        "State": DiscovererStateType,
+        "CrossAccount": bool,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRegistryRequestRequestTypeDef = TypedDict(
     "DescribeRegistryRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
 )
 
+DescribeRegistryResponseTypeDef = TypedDict(
+    "DescribeRegistryResponseTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSchemaRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
     },
 )
@@ -284,27 +349,50 @@
 
 class DescribeSchemaRequestRequestTypeDef(
     _RequiredDescribeSchemaRequestRequestTypeDef, _OptionalDescribeSchemaRequestRequestTypeDef
 ):
     pass
 
 
+DescribeSchemaResponseTypeDef = TypedDict(
+    "DescribeSchemaResponseTypeDef",
+    {
+        "Content": str,
+        "Description": str,
+        "LastModified": datetime,
+        "SchemaArn": str,
+        "SchemaName": str,
+        "SchemaVersion": str,
+        "Tags": Dict[str, str],
+        "Type": str,
+        "VersionCreatedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DiscovererSummaryTypeDef = TypedDict(
     "DiscovererSummaryTypeDef",
     {
         "DiscovererArn": str,
         "DiscovererId": str,
         "SourceArn": str,
         "State": DiscovererStateType,
         "CrossAccount": bool,
         "Tags": Dict[str, str],
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
 _RequiredExportSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredExportSchemaRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
         "Type": str,
     },
@@ -320,14 +408,26 @@
 
 class ExportSchemaRequestRequestTypeDef(
     _RequiredExportSchemaRequestRequestTypeDef, _OptionalExportSchemaRequestRequestTypeDef
 ):
     pass
 
 
+ExportSchemaResponseTypeDef = TypedDict(
+    "ExportSchemaResponseTypeDef",
+    {
+        "Content": str,
+        "SchemaArn": str,
+        "SchemaName": str,
+        "SchemaVersion": str,
+        "Type": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetCodeBindingSourceRequestRequestTypeDef = TypedDict(
     "_RequiredGetCodeBindingSourceRequestRequestTypeDef",
     {
         "Language": str,
         "RegistryName": str,
         "SchemaName": str,
     },
@@ -344,36 +444,61 @@
 class GetCodeBindingSourceRequestRequestTypeDef(
     _RequiredGetCodeBindingSourceRequestRequestTypeDef,
     _OptionalGetCodeBindingSourceRequestRequestTypeDef,
 ):
     pass
 
 
+GetCodeBindingSourceResponseTypeDef = TypedDict(
+    "GetCodeBindingSourceResponseTypeDef",
+    {
+        "Body": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDiscoveredSchemaRequestRequestTypeDef = TypedDict(
     "GetDiscoveredSchemaRequestRequestTypeDef",
     {
         "Events": Sequence[str],
         "Type": TypeType,
     },
 )
 
+GetDiscoveredSchemaResponseTypeDef = TypedDict(
+    "GetDiscoveredSchemaResponseTypeDef",
+    {
+        "Content": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDiscoverersRequestListDiscoverersPaginateTypeDef = TypedDict(
+    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
+    {
+        "DiscovererIdPrefix": str,
+        "SourceArnPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDiscoverersRequestRequestTypeDef = TypedDict(
     "ListDiscoverersRequestRequestTypeDef",
     {
@@ -381,14 +506,24 @@
         "Limit": int,
         "NextToken": str,
         "SourceArnPrefix": str,
     },
     total=False,
 )
 
+ListRegistriesRequestListRegistriesPaginateTypeDef = TypedDict(
+    "ListRegistriesRequestListRegistriesPaginateTypeDef",
+    {
+        "RegistryNamePrefix": str,
+        "Scope": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRegistriesRequestRequestTypeDef = TypedDict(
     "ListRegistriesRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
         "RegistryNamePrefix": str,
         "Scope": str,
@@ -402,14 +537,37 @@
         "RegistryArn": str,
         "RegistryName": str,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
+_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
+    {
+        "RegistryName": str,
+        "SchemaName": str,
+    },
+)
+_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef(
+    _RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
+    _OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSchemaVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemaVersionsRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
     },
 )
@@ -437,14 +595,37 @@
         "SchemaName": str,
         "SchemaVersion": str,
         "Type": TypeType,
     },
     total=False,
 )
 
+_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "RegistryName": str,
+    },
+)
+_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "SchemaNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSchemasRequestListSchemasPaginateTypeDef(
+    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
+    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSchemasRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemasRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
 )
 _OptionalListSchemasRequestRequestTypeDef = TypedDict(
@@ -479,14 +660,32 @@
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
 _RequiredPutCodeBindingRequestRequestTypeDef = TypedDict(
     "_RequiredPutCodeBindingRequestRequestTypeDef",
     {
         "Language": str,
         "RegistryName": str,
         "SchemaName": str,
     },
@@ -502,14 +701,25 @@
 
 class PutCodeBindingRequestRequestTypeDef(
     _RequiredPutCodeBindingRequestRequestTypeDef, _OptionalPutCodeBindingRequestRequestTypeDef
 ):
     pass
 
 
+PutCodeBindingResponseTypeDef = TypedDict(
+    "PutCodeBindingResponseTypeDef",
+    {
+        "CreationDate": datetime,
+        "LastModified": datetime,
+        "SchemaVersion": str,
+        "Status": CodeGenerationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "Policy": str,
     },
 )
 _OptionalPutResourcePolicyRequestRequestTypeDef = TypedDict(
@@ -524,14 +734,34 @@
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 SearchSchemaVersionSummaryTypeDef = TypedDict(
     "SearchSchemaVersionSummaryTypeDef",
     {
         "CreatedDate": datetime,
         "SchemaVersion": str,
         "Type": TypeType,
     },
@@ -557,28 +787,69 @@
 
 class SearchSchemasRequestRequestTypeDef(
     _RequiredSearchSchemasRequestRequestTypeDef, _OptionalSearchSchemasRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
+    "_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef",
+    {
+        "Keywords": str,
+        "RegistryName": str,
+    },
+)
+_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
+    "_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SearchSchemasRequestSearchSchemasPaginateTypeDef(
+    _RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef,
+    _OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef,
+):
+    pass
+
+
 StartDiscovererRequestRequestTypeDef = TypedDict(
     "StartDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
+StartDiscovererResponseTypeDef = TypedDict(
+    "StartDiscovererResponseTypeDef",
+    {
+        "DiscovererId": str,
+        "State": DiscovererStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDiscovererRequestRequestTypeDef = TypedDict(
     "StopDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
+StopDiscovererResponseTypeDef = TypedDict(
+    "StopDiscovererResponseTypeDef",
+    {
+        "DiscovererId": str,
+        "State": DiscovererStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -609,14 +880,28 @@
 
 class UpdateDiscovererRequestRequestTypeDef(
     _RequiredUpdateDiscovererRequestRequestTypeDef, _OptionalUpdateDiscovererRequestRequestTypeDef
 ):
     pass
 
 
+UpdateDiscovererResponseTypeDef = TypedDict(
+    "UpdateDiscovererResponseTypeDef",
+    {
+        "Description": str,
+        "DiscovererArn": str,
+        "DiscovererId": str,
+        "SourceArn": str,
+        "State": DiscovererStateType,
+        "CrossAccount": bool,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateRegistryRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRegistryRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
 )
 _OptionalUpdateRegistryRequestRequestTypeDef = TypedDict(
@@ -630,14 +915,25 @@
 
 class UpdateRegistryRequestRequestTypeDef(
     _RequiredUpdateRegistryRequestRequestTypeDef, _OptionalUpdateRegistryRequestRequestTypeDef
 ):
     pass
 
 
+UpdateRegistryResponseTypeDef = TypedDict(
+    "UpdateRegistryResponseTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSchemaRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
     },
 )
@@ -655,233 +951,26 @@
 
 class UpdateSchemaRequestRequestTypeDef(
     _RequiredUpdateSchemaRequestRequestTypeDef, _OptionalUpdateSchemaRequestRequestTypeDef
 ):
     pass
 
 
-CreateDiscovererResponseTypeDef = TypedDict(
-    "CreateDiscovererResponseTypeDef",
-    {
-        "Description": str,
-        "DiscovererArn": str,
-        "DiscovererId": str,
-        "SourceArn": str,
-        "State": DiscovererStateType,
-        "CrossAccount": bool,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRegistryResponseTypeDef = TypedDict(
-    "CreateRegistryResponseTypeDef",
-    {
-        "Description": str,
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "Description": str,
-        "LastModified": datetime,
-        "SchemaArn": str,
-        "SchemaName": str,
-        "SchemaVersion": str,
-        "Tags": Dict[str, str],
-        "Type": str,
-        "VersionCreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCodeBindingResponseTypeDef = TypedDict(
-    "DescribeCodeBindingResponseTypeDef",
-    {
-        "CreationDate": datetime,
-        "LastModified": datetime,
-        "SchemaVersion": str,
-        "Status": CodeGenerationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDiscovererResponseTypeDef = TypedDict(
-    "DescribeDiscovererResponseTypeDef",
-    {
-        "Description": str,
-        "DiscovererArn": str,
-        "DiscovererId": str,
-        "SourceArn": str,
-        "State": DiscovererStateType,
-        "CrossAccount": bool,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRegistryResponseTypeDef = TypedDict(
-    "DescribeRegistryResponseTypeDef",
-    {
-        "Description": str,
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeSchemaResponseTypeDef = TypedDict(
-    "DescribeSchemaResponseTypeDef",
-    {
-        "Content": str,
-        "Description": str,
-        "LastModified": datetime,
-        "SchemaArn": str,
-        "SchemaName": str,
-        "SchemaVersion": str,
-        "Tags": Dict[str, str],
-        "Type": str,
-        "VersionCreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportSchemaResponseTypeDef = TypedDict(
-    "ExportSchemaResponseTypeDef",
-    {
-        "Content": str,
-        "SchemaArn": str,
-        "SchemaName": str,
-        "SchemaVersion": str,
-        "Type": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCodeBindingSourceResponseTypeDef = TypedDict(
-    "GetCodeBindingSourceResponseTypeDef",
-    {
-        "Body": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDiscoveredSchemaResponseTypeDef = TypedDict(
-    "GetDiscoveredSchemaResponseTypeDef",
-    {
-        "Content": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutCodeBindingResponseTypeDef = TypedDict(
-    "PutCodeBindingResponseTypeDef",
-    {
-        "CreationDate": datetime,
-        "LastModified": datetime,
-        "SchemaVersion": str,
-        "Status": CodeGenerationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDiscovererResponseTypeDef = TypedDict(
-    "StartDiscovererResponseTypeDef",
-    {
-        "DiscovererId": str,
-        "State": DiscovererStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDiscovererResponseTypeDef = TypedDict(
-    "StopDiscovererResponseTypeDef",
-    {
-        "DiscovererId": str,
-        "State": DiscovererStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDiscovererResponseTypeDef = TypedDict(
-    "UpdateDiscovererResponseTypeDef",
-    {
-        "Description": str,
-        "DiscovererArn": str,
-        "DiscovererId": str,
-        "SourceArn": str,
-        "State": DiscovererStateType,
-        "CrossAccount": bool,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRegistryResponseTypeDef = TypedDict(
-    "UpdateRegistryResponseTypeDef",
-    {
-        "Description": str,
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSchemaResponseTypeDef = TypedDict(
     "UpdateSchemaResponseTypeDef",
     {
         "Description": str,
         "LastModified": datetime,
         "SchemaArn": str,
         "SchemaName": str,
         "SchemaVersion": str,
         "Tags": Dict[str, str],
         "Type": str,
         "VersionCreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeCodeBindingRequestCodeBindingExistsWaitTypeDef = TypedDict(
     "_RequiredDescribeCodeBindingRequestCodeBindingExistsWaitTypeDef",
     {
         "Language": str,
@@ -907,131 +996,42 @@
 
 
 ListDiscoverersResponseTypeDef = TypedDict(
     "ListDiscoverersResponseTypeDef",
     {
         "Discoverers": List[DiscovererSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListDiscoverersRequestListDiscoverersPaginateTypeDef = TypedDict(
-    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
-    {
-        "DiscovererIdPrefix": str,
-        "SourceArnPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRegistriesRequestListRegistriesPaginateTypeDef = TypedDict(
-    "ListRegistriesRequestListRegistriesPaginateTypeDef",
-    {
-        "RegistryNamePrefix": str,
-        "Scope": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
-    {
-        "RegistryName": str,
-        "SchemaName": str,
-    },
-)
-_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef(
-    _RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-    _OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "RegistryName": str,
-    },
-)
-_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "SchemaNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSchemasRequestListSchemasPaginateTypeDef(
-    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
-    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
-):
-    pass
-
-
-_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
-    "_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef",
-    {
-        "Keywords": str,
-        "RegistryName": str,
-    },
-)
-_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
-    "_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class SearchSchemasRequestSearchSchemasPaginateTypeDef(
-    _RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef,
-    _OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef,
-):
-    pass
-
-
 ListRegistriesResponseTypeDef = TypedDict(
     "ListRegistriesResponseTypeDef",
     {
         "NextToken": str,
         "Registries": List[RegistrySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemaVersionsResponseTypeDef = TypedDict(
     "ListSchemaVersionsResponseTypeDef",
     {
         "NextToken": str,
         "SchemaVersions": List[SchemaVersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasResponseTypeDef = TypedDict(
     "ListSchemasResponseTypeDef",
     {
         "NextToken": str,
         "Schemas": List[SchemaSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchSchemaSummaryTypeDef = TypedDict(
     "SearchSchemaSummaryTypeDef",
     {
         "RegistryName": str,
@@ -1043,10 +1043,10 @@
 )
 
 SearchSchemasResponseTypeDef = TypedDict(
     "SearchSchemasResponseTypeDef",
     {
         "NextToken": str,
         "Schemas": List[SearchSchemaSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/type_defs.pyi` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -22,79 +22,79 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CreateDiscovererRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDiscovererResponseTypeDef",
     "CreateRegistryRequestRequestTypeDef",
+    "CreateRegistryResponseTypeDef",
     "CreateSchemaRequestRequestTypeDef",
+    "CreateSchemaResponseTypeDef",
     "DeleteDiscovererRequestRequestTypeDef",
     "DeleteRegistryRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSchemaRequestRequestTypeDef",
     "DeleteSchemaVersionRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeCodeBindingRequestRequestTypeDef",
+    "DescribeCodeBindingResponseTypeDef",
     "DescribeDiscovererRequestRequestTypeDef",
+    "DescribeDiscovererResponseTypeDef",
     "DescribeRegistryRequestRequestTypeDef",
+    "DescribeRegistryResponseTypeDef",
     "DescribeSchemaRequestRequestTypeDef",
+    "DescribeSchemaResponseTypeDef",
     "DiscovererSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportSchemaRequestRequestTypeDef",
+    "ExportSchemaResponseTypeDef",
     "GetCodeBindingSourceRequestRequestTypeDef",
+    "GetCodeBindingSourceResponseTypeDef",
     "GetDiscoveredSchemaRequestRequestTypeDef",
+    "GetDiscoveredSchemaResponseTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePolicyResponseTypeDef",
+    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
     "ListDiscoverersRequestRequestTypeDef",
+    "ListRegistriesRequestListRegistriesPaginateTypeDef",
     "ListRegistriesRequestRequestTypeDef",
     "RegistrySummaryTypeDef",
+    "ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
     "ListSchemaVersionsRequestRequestTypeDef",
     "SchemaVersionSummaryTypeDef",
+    "ListSchemasRequestListSchemasPaginateTypeDef",
     "ListSchemasRequestRequestTypeDef",
     "SchemaSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutCodeBindingRequestRequestTypeDef",
+    "PutCodeBindingResponseTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchSchemaVersionSummaryTypeDef",
     "SearchSchemasRequestRequestTypeDef",
+    "SearchSchemasRequestSearchSchemasPaginateTypeDef",
     "StartDiscovererRequestRequestTypeDef",
+    "StartDiscovererResponseTypeDef",
     "StopDiscovererRequestRequestTypeDef",
+    "StopDiscovererResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDiscovererRequestRequestTypeDef",
-    "UpdateRegistryRequestRequestTypeDef",
-    "UpdateSchemaRequestRequestTypeDef",
-    "CreateDiscovererResponseTypeDef",
-    "CreateRegistryResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "DescribeCodeBindingResponseTypeDef",
-    "DescribeDiscovererResponseTypeDef",
-    "DescribeRegistryResponseTypeDef",
-    "DescribeSchemaResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportSchemaResponseTypeDef",
-    "GetCodeBindingSourceResponseTypeDef",
-    "GetDiscoveredSchemaResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutCodeBindingResponseTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "StartDiscovererResponseTypeDef",
-    "StopDiscovererResponseTypeDef",
     "UpdateDiscovererResponseTypeDef",
+    "UpdateRegistryRequestRequestTypeDef",
     "UpdateRegistryResponseTypeDef",
+    "UpdateSchemaRequestRequestTypeDef",
     "UpdateSchemaResponseTypeDef",
     "DescribeCodeBindingRequestCodeBindingExistsWaitTypeDef",
     "ListDiscoverersResponseTypeDef",
-    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
-    "ListRegistriesRequestListRegistriesPaginateTypeDef",
-    "ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    "SearchSchemasRequestSearchSchemasPaginateTypeDef",
     "ListRegistriesResponseTypeDef",
     "ListSchemaVersionsResponseTypeDef",
     "ListSchemasResponseTypeDef",
     "SearchSchemaSummaryTypeDef",
     "SearchSchemasResponseTypeDef",
 )
 
@@ -115,22 +115,25 @@
 )
 
 class CreateDiscovererRequestRequestTypeDef(
     _RequiredCreateDiscovererRequestRequestTypeDef, _OptionalCreateDiscovererRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDiscovererResponseTypeDef = TypedDict(
+    "CreateDiscovererResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Description": str,
+        "DiscovererArn": str,
+        "DiscovererId": str,
+        "SourceArn": str,
+        "State": DiscovererStateType,
+        "CrossAccount": bool,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRegistryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRegistryRequestRequestTypeDef",
     {
         "RegistryName": str,
@@ -146,14 +149,25 @@
 )
 
 class CreateRegistryRequestRequestTypeDef(
     _RequiredCreateRegistryRequestRequestTypeDef, _OptionalCreateRegistryRequestRequestTypeDef
 ):
     pass
 
+CreateRegistryResponseTypeDef = TypedDict(
+    "CreateRegistryResponseTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSchemaRequestRequestTypeDef",
     {
         "Content": str,
         "RegistryName": str,
         "SchemaName": str,
         "Type": TypeType,
@@ -169,14 +183,29 @@
 )
 
 class CreateSchemaRequestRequestTypeDef(
     _RequiredCreateSchemaRequestRequestTypeDef, _OptionalCreateSchemaRequestRequestTypeDef
 ):
     pass
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "Description": str,
+        "LastModified": datetime,
+        "SchemaArn": str,
+        "SchemaName": str,
+        "SchemaVersion": str,
+        "Tags": Dict[str, str],
+        "Type": str,
+        "VersionCreatedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDiscovererRequestRequestTypeDef = TypedDict(
     "DeleteDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
@@ -239,28 +268,64 @@
 
 class DescribeCodeBindingRequestRequestTypeDef(
     _RequiredDescribeCodeBindingRequestRequestTypeDef,
     _OptionalDescribeCodeBindingRequestRequestTypeDef,
 ):
     pass
 
+DescribeCodeBindingResponseTypeDef = TypedDict(
+    "DescribeCodeBindingResponseTypeDef",
+    {
+        "CreationDate": datetime,
+        "LastModified": datetime,
+        "SchemaVersion": str,
+        "Status": CodeGenerationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDiscovererRequestRequestTypeDef = TypedDict(
     "DescribeDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
+DescribeDiscovererResponseTypeDef = TypedDict(
+    "DescribeDiscovererResponseTypeDef",
+    {
+        "Description": str,
+        "DiscovererArn": str,
+        "DiscovererId": str,
+        "SourceArn": str,
+        "State": DiscovererStateType,
+        "CrossAccount": bool,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRegistryRequestRequestTypeDef = TypedDict(
     "DescribeRegistryRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
 )
 
+DescribeRegistryResponseTypeDef = TypedDict(
+    "DescribeRegistryResponseTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSchemaRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
     },
 )
@@ -273,27 +338,50 @@
 )
 
 class DescribeSchemaRequestRequestTypeDef(
     _RequiredDescribeSchemaRequestRequestTypeDef, _OptionalDescribeSchemaRequestRequestTypeDef
 ):
     pass
 
+DescribeSchemaResponseTypeDef = TypedDict(
+    "DescribeSchemaResponseTypeDef",
+    {
+        "Content": str,
+        "Description": str,
+        "LastModified": datetime,
+        "SchemaArn": str,
+        "SchemaName": str,
+        "SchemaVersion": str,
+        "Tags": Dict[str, str],
+        "Type": str,
+        "VersionCreatedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DiscovererSummaryTypeDef = TypedDict(
     "DiscovererSummaryTypeDef",
     {
         "DiscovererArn": str,
         "DiscovererId": str,
         "SourceArn": str,
         "State": DiscovererStateType,
         "CrossAccount": bool,
         "Tags": Dict[str, str],
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
 _RequiredExportSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredExportSchemaRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
         "Type": str,
     },
@@ -307,14 +395,26 @@
 )
 
 class ExportSchemaRequestRequestTypeDef(
     _RequiredExportSchemaRequestRequestTypeDef, _OptionalExportSchemaRequestRequestTypeDef
 ):
     pass
 
+ExportSchemaResponseTypeDef = TypedDict(
+    "ExportSchemaResponseTypeDef",
+    {
+        "Content": str,
+        "SchemaArn": str,
+        "SchemaName": str,
+        "SchemaVersion": str,
+        "Type": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetCodeBindingSourceRequestRequestTypeDef = TypedDict(
     "_RequiredGetCodeBindingSourceRequestRequestTypeDef",
     {
         "Language": str,
         "RegistryName": str,
         "SchemaName": str,
     },
@@ -329,36 +429,61 @@
 
 class GetCodeBindingSourceRequestRequestTypeDef(
     _RequiredGetCodeBindingSourceRequestRequestTypeDef,
     _OptionalGetCodeBindingSourceRequestRequestTypeDef,
 ):
     pass
 
+GetCodeBindingSourceResponseTypeDef = TypedDict(
+    "GetCodeBindingSourceResponseTypeDef",
+    {
+        "Body": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDiscoveredSchemaRequestRequestTypeDef = TypedDict(
     "GetDiscoveredSchemaRequestRequestTypeDef",
     {
         "Events": Sequence[str],
         "Type": TypeType,
     },
 )
 
+GetDiscoveredSchemaResponseTypeDef = TypedDict(
+    "GetDiscoveredSchemaResponseTypeDef",
+    {
+        "Content": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDiscoverersRequestListDiscoverersPaginateTypeDef = TypedDict(
+    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
+    {
+        "DiscovererIdPrefix": str,
+        "SourceArnPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDiscoverersRequestRequestTypeDef = TypedDict(
     "ListDiscoverersRequestRequestTypeDef",
     {
@@ -366,14 +491,24 @@
         "Limit": int,
         "NextToken": str,
         "SourceArnPrefix": str,
     },
     total=False,
 )
 
+ListRegistriesRequestListRegistriesPaginateTypeDef = TypedDict(
+    "ListRegistriesRequestListRegistriesPaginateTypeDef",
+    {
+        "RegistryNamePrefix": str,
+        "Scope": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRegistriesRequestRequestTypeDef = TypedDict(
     "ListRegistriesRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
         "RegistryNamePrefix": str,
         "Scope": str,
@@ -387,14 +522,35 @@
         "RegistryArn": str,
         "RegistryName": str,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
+_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
+    {
+        "RegistryName": str,
+        "SchemaName": str,
+    },
+)
+_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef(
+    _RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
+    _OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListSchemaVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemaVersionsRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
     },
 )
@@ -420,14 +576,35 @@
         "SchemaName": str,
         "SchemaVersion": str,
         "Type": TypeType,
     },
     total=False,
 )
 
+_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "RegistryName": str,
+    },
+)
+_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "SchemaNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSchemasRequestListSchemasPaginateTypeDef(
+    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
+    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
+):
+    pass
+
 _RequiredListSchemasRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemasRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
 )
 _OptionalListSchemasRequestRequestTypeDef = TypedDict(
@@ -460,14 +637,32 @@
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
 _RequiredPutCodeBindingRequestRequestTypeDef = TypedDict(
     "_RequiredPutCodeBindingRequestRequestTypeDef",
     {
         "Language": str,
         "RegistryName": str,
         "SchemaName": str,
     },
@@ -481,14 +676,25 @@
 )
 
 class PutCodeBindingRequestRequestTypeDef(
     _RequiredPutCodeBindingRequestRequestTypeDef, _OptionalPutCodeBindingRequestRequestTypeDef
 ):
     pass
 
+PutCodeBindingResponseTypeDef = TypedDict(
+    "PutCodeBindingResponseTypeDef",
+    {
+        "CreationDate": datetime,
+        "LastModified": datetime,
+        "SchemaVersion": str,
+        "Status": CodeGenerationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "Policy": str,
     },
 )
 _OptionalPutResourcePolicyRequestRequestTypeDef = TypedDict(
@@ -501,14 +707,34 @@
 )
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 SearchSchemaVersionSummaryTypeDef = TypedDict(
     "SearchSchemaVersionSummaryTypeDef",
     {
         "CreatedDate": datetime,
         "SchemaVersion": str,
         "Type": TypeType,
     },
@@ -532,28 +758,67 @@
 )
 
 class SearchSchemasRequestRequestTypeDef(
     _RequiredSearchSchemasRequestRequestTypeDef, _OptionalSearchSchemasRequestRequestTypeDef
 ):
     pass
 
+_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
+    "_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef",
+    {
+        "Keywords": str,
+        "RegistryName": str,
+    },
+)
+_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
+    "_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SearchSchemasRequestSearchSchemasPaginateTypeDef(
+    _RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef,
+    _OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef,
+):
+    pass
+
 StartDiscovererRequestRequestTypeDef = TypedDict(
     "StartDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
+StartDiscovererResponseTypeDef = TypedDict(
+    "StartDiscovererResponseTypeDef",
+    {
+        "DiscovererId": str,
+        "State": DiscovererStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDiscovererRequestRequestTypeDef = TypedDict(
     "StopDiscovererRequestRequestTypeDef",
     {
         "DiscovererId": str,
     },
 )
 
+StopDiscovererResponseTypeDef = TypedDict(
+    "StopDiscovererResponseTypeDef",
+    {
+        "DiscovererId": str,
+        "State": DiscovererStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -582,14 +847,28 @@
 )
 
 class UpdateDiscovererRequestRequestTypeDef(
     _RequiredUpdateDiscovererRequestRequestTypeDef, _OptionalUpdateDiscovererRequestRequestTypeDef
 ):
     pass
 
+UpdateDiscovererResponseTypeDef = TypedDict(
+    "UpdateDiscovererResponseTypeDef",
+    {
+        "Description": str,
+        "DiscovererArn": str,
+        "DiscovererId": str,
+        "SourceArn": str,
+        "State": DiscovererStateType,
+        "CrossAccount": bool,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateRegistryRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRegistryRequestRequestTypeDef",
     {
         "RegistryName": str,
     },
 )
 _OptionalUpdateRegistryRequestRequestTypeDef = TypedDict(
@@ -601,14 +880,25 @@
 )
 
 class UpdateRegistryRequestRequestTypeDef(
     _RequiredUpdateRegistryRequestRequestTypeDef, _OptionalUpdateRegistryRequestRequestTypeDef
 ):
     pass
 
+UpdateRegistryResponseTypeDef = TypedDict(
+    "UpdateRegistryResponseTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSchemaRequestRequestTypeDef",
     {
         "RegistryName": str,
         "SchemaName": str,
     },
 )
@@ -624,233 +914,26 @@
 )
 
 class UpdateSchemaRequestRequestTypeDef(
     _RequiredUpdateSchemaRequestRequestTypeDef, _OptionalUpdateSchemaRequestRequestTypeDef
 ):
     pass
 
-CreateDiscovererResponseTypeDef = TypedDict(
-    "CreateDiscovererResponseTypeDef",
-    {
-        "Description": str,
-        "DiscovererArn": str,
-        "DiscovererId": str,
-        "SourceArn": str,
-        "State": DiscovererStateType,
-        "CrossAccount": bool,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRegistryResponseTypeDef = TypedDict(
-    "CreateRegistryResponseTypeDef",
-    {
-        "Description": str,
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "Description": str,
-        "LastModified": datetime,
-        "SchemaArn": str,
-        "SchemaName": str,
-        "SchemaVersion": str,
-        "Tags": Dict[str, str],
-        "Type": str,
-        "VersionCreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCodeBindingResponseTypeDef = TypedDict(
-    "DescribeCodeBindingResponseTypeDef",
-    {
-        "CreationDate": datetime,
-        "LastModified": datetime,
-        "SchemaVersion": str,
-        "Status": CodeGenerationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDiscovererResponseTypeDef = TypedDict(
-    "DescribeDiscovererResponseTypeDef",
-    {
-        "Description": str,
-        "DiscovererArn": str,
-        "DiscovererId": str,
-        "SourceArn": str,
-        "State": DiscovererStateType,
-        "CrossAccount": bool,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRegistryResponseTypeDef = TypedDict(
-    "DescribeRegistryResponseTypeDef",
-    {
-        "Description": str,
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeSchemaResponseTypeDef = TypedDict(
-    "DescribeSchemaResponseTypeDef",
-    {
-        "Content": str,
-        "Description": str,
-        "LastModified": datetime,
-        "SchemaArn": str,
-        "SchemaName": str,
-        "SchemaVersion": str,
-        "Tags": Dict[str, str],
-        "Type": str,
-        "VersionCreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportSchemaResponseTypeDef = TypedDict(
-    "ExportSchemaResponseTypeDef",
-    {
-        "Content": str,
-        "SchemaArn": str,
-        "SchemaName": str,
-        "SchemaVersion": str,
-        "Type": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCodeBindingSourceResponseTypeDef = TypedDict(
-    "GetCodeBindingSourceResponseTypeDef",
-    {
-        "Body": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDiscoveredSchemaResponseTypeDef = TypedDict(
-    "GetDiscoveredSchemaResponseTypeDef",
-    {
-        "Content": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutCodeBindingResponseTypeDef = TypedDict(
-    "PutCodeBindingResponseTypeDef",
-    {
-        "CreationDate": datetime,
-        "LastModified": datetime,
-        "SchemaVersion": str,
-        "Status": CodeGenerationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDiscovererResponseTypeDef = TypedDict(
-    "StartDiscovererResponseTypeDef",
-    {
-        "DiscovererId": str,
-        "State": DiscovererStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDiscovererResponseTypeDef = TypedDict(
-    "StopDiscovererResponseTypeDef",
-    {
-        "DiscovererId": str,
-        "State": DiscovererStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDiscovererResponseTypeDef = TypedDict(
-    "UpdateDiscovererResponseTypeDef",
-    {
-        "Description": str,
-        "DiscovererArn": str,
-        "DiscovererId": str,
-        "SourceArn": str,
-        "State": DiscovererStateType,
-        "CrossAccount": bool,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRegistryResponseTypeDef = TypedDict(
-    "UpdateRegistryResponseTypeDef",
-    {
-        "Description": str,
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSchemaResponseTypeDef = TypedDict(
     "UpdateSchemaResponseTypeDef",
     {
         "Description": str,
         "LastModified": datetime,
         "SchemaArn": str,
         "SchemaName": str,
         "SchemaVersion": str,
         "Tags": Dict[str, str],
         "Type": str,
         "VersionCreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeCodeBindingRequestCodeBindingExistsWaitTypeDef = TypedDict(
     "_RequiredDescribeCodeBindingRequestCodeBindingExistsWaitTypeDef",
     {
         "Language": str,
@@ -874,125 +957,42 @@
     pass
 
 ListDiscoverersResponseTypeDef = TypedDict(
     "ListDiscoverersResponseTypeDef",
     {
         "Discoverers": List[DiscovererSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDiscoverersRequestListDiscoverersPaginateTypeDef = TypedDict(
-    "ListDiscoverersRequestListDiscoverersPaginateTypeDef",
-    {
-        "DiscovererIdPrefix": str,
-        "SourceArnPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRegistriesRequestListRegistriesPaginateTypeDef = TypedDict(
-    "ListRegistriesRequestListRegistriesPaginateTypeDef",
-    {
-        "RegistryNamePrefix": str,
-        "Scope": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
-    {
-        "RegistryName": str,
-        "SchemaName": str,
-    },
-)
-_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef(
-    _RequiredListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-    _OptionalListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "RegistryName": str,
-    },
-)
-_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "SchemaNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSchemasRequestListSchemasPaginateTypeDef(
-    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
-    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
-):
-    pass
-
-_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
-    "_RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef",
-    {
-        "Keywords": str,
-        "RegistryName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef = TypedDict(
-    "_OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SearchSchemasRequestSearchSchemasPaginateTypeDef(
-    _RequiredSearchSchemasRequestSearchSchemasPaginateTypeDef,
-    _OptionalSearchSchemasRequestSearchSchemasPaginateTypeDef,
-):
-    pass
 
 ListRegistriesResponseTypeDef = TypedDict(
     "ListRegistriesResponseTypeDef",
     {
         "NextToken": str,
         "Registries": List[RegistrySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemaVersionsResponseTypeDef = TypedDict(
     "ListSchemaVersionsResponseTypeDef",
     {
         "NextToken": str,
         "SchemaVersions": List[SchemaVersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasResponseTypeDef = TypedDict(
     "ListSchemasResponseTypeDef",
     {
         "NextToken": str,
         "Schemas": List[SchemaSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchSchemaSummaryTypeDef = TypedDict(
     "SearchSchemaSummaryTypeDef",
     {
         "RegistryName": str,
@@ -1004,10 +1004,10 @@
 )
 
 SearchSchemasResponseTypeDef = TypedDict(
     "SearchSchemasResponseTypeDef",
     {
         "NextToken": str,
         "Schemas": List[SearchSchemaSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/waiter.py` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas/waiter.pyi` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/PKG-INFO` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-schemas
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Schemas 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Schemas 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-schemas"></a>
 
 # types-aiobotocore-schemas
 
 [![PyPI - types-aiobotocore-schemas](https://img.shields.io/pypi/v/types-aiobotocore-schemas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-schemas)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-schemas.svg?color=blue)](https://pypi.org/project/types-aiobotocore-schemas)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-schemas?color=blue)](https://pypistats.org/packages/types-aiobotocore-schemas)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Schemas 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
+[aiobotocore.Schemas 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/schemas.html#Schemas)
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
 [types-aiobotocore-schemas docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_schemas/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,79 +358,79 @@
 
 `types_aiobotocore_schemas.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_schemas.type_defs import (
     CreateDiscovererRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDiscovererResponseTypeDef,
     CreateRegistryRequestRequestTypeDef,
+    CreateRegistryResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
     DeleteDiscovererRequestRequestTypeDef,
     DeleteRegistryRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSchemaRequestRequestTypeDef,
     DeleteSchemaVersionRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeCodeBindingRequestRequestTypeDef,
+    DescribeCodeBindingResponseTypeDef,
     DescribeDiscovererRequestRequestTypeDef,
+    DescribeDiscovererResponseTypeDef,
     DescribeRegistryRequestRequestTypeDef,
+    DescribeRegistryResponseTypeDef,
     DescribeSchemaRequestRequestTypeDef,
+    DescribeSchemaResponseTypeDef,
     DiscovererSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportSchemaRequestRequestTypeDef,
+    ExportSchemaResponseTypeDef,
     GetCodeBindingSourceRequestRequestTypeDef,
+    GetCodeBindingSourceResponseTypeDef,
     GetDiscoveredSchemaRequestRequestTypeDef,
+    GetDiscoveredSchemaResponseTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePolicyResponseTypeDef,
+    ListDiscoverersRequestListDiscoverersPaginateTypeDef,
     ListDiscoverersRequestRequestTypeDef,
+    ListRegistriesRequestListRegistriesPaginateTypeDef,
     ListRegistriesRequestRequestTypeDef,
     RegistrySummaryTypeDef,
+    ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
     ListSchemaVersionsRequestRequestTypeDef,
     SchemaVersionSummaryTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
     SchemaSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutCodeBindingRequestRequestTypeDef,
+    PutCodeBindingResponseTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     SearchSchemaVersionSummaryTypeDef,
     SearchSchemasRequestRequestTypeDef,
+    SearchSchemasRequestSearchSchemasPaginateTypeDef,
     StartDiscovererRequestRequestTypeDef,
+    StartDiscovererResponseTypeDef,
     StopDiscovererRequestRequestTypeDef,
+    StopDiscovererResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDiscovererRequestRequestTypeDef,
-    UpdateRegistryRequestRequestTypeDef,
-    UpdateSchemaRequestRequestTypeDef,
-    CreateDiscovererResponseTypeDef,
-    CreateRegistryResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    DescribeCodeBindingResponseTypeDef,
-    DescribeDiscovererResponseTypeDef,
-    DescribeRegistryResponseTypeDef,
-    DescribeSchemaResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportSchemaResponseTypeDef,
-    GetCodeBindingSourceResponseTypeDef,
-    GetDiscoveredSchemaResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutCodeBindingResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    StartDiscovererResponseTypeDef,
-    StopDiscovererResponseTypeDef,
     UpdateDiscovererResponseTypeDef,
+    UpdateRegistryRequestRequestTypeDef,
     UpdateRegistryResponseTypeDef,
+    UpdateSchemaRequestRequestTypeDef,
     UpdateSchemaResponseTypeDef,
     DescribeCodeBindingRequestCodeBindingExistsWaitTypeDef,
     ListDiscoverersResponseTypeDef,
-    ListDiscoverersRequestListDiscoverersPaginateTypeDef,
-    ListRegistriesRequestListRegistriesPaginateTypeDef,
-    ListSchemaVersionsRequestListSchemaVersionsPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    SearchSchemasRequestSearchSchemasPaginateTypeDef,
     ListRegistriesResponseTypeDef,
     ListSchemaVersionsResponseTypeDef,
     ListSchemasResponseTypeDef,
     SearchSchemaSummaryTypeDef,
     SearchSchemasResponseTypeDef,
 )
 
@@ -442,43 +442,43 @@
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

### Comparing `types-aiobotocore-schemas-2.5.0.post1/types_aiobotocore_schemas.egg-info/SOURCES.txt` & `types-aiobotocore-schemas-2.5.1/types_aiobotocore_schemas.egg-info/SOURCES.txt`

 * *Files identical despite different names*

