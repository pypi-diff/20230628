# Comparing `tmp/types-aiobotocore-resource-explorer-2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-resource-explorer-2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-resource-explorer-2-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-resource-explorer-2-2.5.1.tar", last modified: Wed Jun 28 01:44:03 2023, max compression
```

## Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1.tar` & `types-aiobotocore-resource-explorer-2-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:12.923555 types-aiobotocore-resource-explorer-2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15584 2023-03-11 12:27:12.915555 types-aiobotocore-resource-explorer-2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13968 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:12.923555 types-aiobotocore-resource-explorer-2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2197 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:12.911555 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/
--rw-r--r--   0 runner    (1001) docker     (123)     1300 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1299 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      985 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18703 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18671 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8474 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8472 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5777 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5770 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    13072 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    13061 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:27.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:12.915555 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15584 2023-03-11 12:27:12.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-03-11 12:27:12.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:12.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:12.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:12.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:12.000000 types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.466200 types-aiobotocore-resource-explorer-2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15588 2023-06-28 01:44:03.466200 types-aiobotocore-resource-explorer-2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13978 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.466200 types-aiobotocore-resource-explorer-2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2191 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.466200 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1300 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1299 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      973 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18703 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18671 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8648 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8646 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5665 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5659 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    13114 2023-06-28 01:39:13.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13103 2023-06-28 01:39:13.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:12.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.466200 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15588 2023-06-28 01:44:03.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-28 01:44:03.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:03.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.000000 types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/LICENSE` & `types-aiobotocore-resource-explorer-2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-resource-explorer-2-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resource-explorer-2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResourceExplorer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResourceExplorer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resource-explorer-2"></a>
 
 # types-aiobotocore-resource-explorer-2
 
 [![PyPI - types-aiobotocore-resource-explorer-2](https://img.shields.io/pypi/v/types-aiobotocore-resource-explorer-2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-explorer-2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resource-explorer-2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-explorer-2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resource-explorer-2?color=blue)](https://pypistats.org/packages/types-aiobotocore-resource-explorer-2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceExplorer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer)
+[aiobotocore.ResourceExplorer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer)
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
 [types-aiobotocore-resource-explorer-2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,54 +330,54 @@
 
 `types_aiobotocore_resource_explorer_2.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resource_explorer_2.type_defs import (
     AssociateDefaultViewInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateDefaultViewOutputTypeDef,
     BatchGetViewErrorTypeDef,
     BatchGetViewInputRequestTypeDef,
     CreateIndexInputRequestTypeDef,
+    CreateIndexOutputTypeDef,
     IncludedPropertyTypeDef,
     SearchFilterTypeDef,
     DeleteIndexInputRequestTypeDef,
+    DeleteIndexOutputTypeDef,
     DeleteViewInputRequestTypeDef,
+    DeleteViewOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
+    GetDefaultViewOutputTypeDef,
+    GetIndexOutputTypeDef,
     GetViewInputRequestTypeDef,
     IndexTypeDef,
-    PaginatorConfigTypeDef,
+    ListIndexesInputListIndexesPaginateTypeDef,
     ListIndexesInputRequestTypeDef,
+    ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef,
     ListSupportedResourceTypesInputRequestTypeDef,
     SupportedResourceTypeTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    ListViewsInputListViewsPaginateTypeDef,
     ListViewsInputRequestTypeDef,
+    ListViewsOutputTypeDef,
+    PaginatorConfigTypeDef,
     ResourceCountTypeDef,
     ResourcePropertyTypeDef,
+    ResponseMetadataTypeDef,
     SearchInputRequestTypeDef,
+    SearchInputSearchPaginateTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateIndexTypeInputRequestTypeDef,
-    AssociateDefaultViewOutputTypeDef,
-    CreateIndexOutputTypeDef,
-    DeleteIndexOutputTypeDef,
-    DeleteViewOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDefaultViewOutputTypeDef,
-    GetIndexOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    ListViewsOutputTypeDef,
     UpdateIndexTypeOutputTypeDef,
     CreateViewInputRequestTypeDef,
     UpdateViewInputRequestTypeDef,
     ViewTypeDef,
     ListIndexesOutputTypeDef,
-    ListIndexesInputListIndexesPaginateTypeDef,
-    ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef,
-    ListViewsInputListViewsPaginateTypeDef,
-    SearchInputSearchPaginateTypeDef,
     ListSupportedResourceTypesOutputTypeDef,
     ResourceTypeDef,
     BatchGetViewOutputTypeDef,
     CreateViewOutputTypeDef,
     GetViewOutputTypeDef,
     UpdateViewOutputTypeDef,
     SearchOutputTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/README.md` & `types-aiobotocore-resource-explorer-2-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-resource-explorer-2"></a>
 
 # types-aiobotocore-resource-explorer-2
 
 [![PyPI - types-aiobotocore-resource-explorer-2](https://img.shields.io/pypi/v/types-aiobotocore-resource-explorer-2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-explorer-2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resource-explorer-2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-explorer-2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resource-explorer-2?color=blue)](https://pypistats.org/packages/types-aiobotocore-resource-explorer-2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceExplorer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer)
+[aiobotocore.ResourceExplorer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer)
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
 [types-aiobotocore-resource-explorer-2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,54 +297,54 @@
 
 `types_aiobotocore_resource_explorer_2.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resource_explorer_2.type_defs import (
     AssociateDefaultViewInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateDefaultViewOutputTypeDef,
     BatchGetViewErrorTypeDef,
     BatchGetViewInputRequestTypeDef,
     CreateIndexInputRequestTypeDef,
+    CreateIndexOutputTypeDef,
     IncludedPropertyTypeDef,
     SearchFilterTypeDef,
     DeleteIndexInputRequestTypeDef,
+    DeleteIndexOutputTypeDef,
     DeleteViewInputRequestTypeDef,
+    DeleteViewOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
+    GetDefaultViewOutputTypeDef,
+    GetIndexOutputTypeDef,
     GetViewInputRequestTypeDef,
     IndexTypeDef,
-    PaginatorConfigTypeDef,
+    ListIndexesInputListIndexesPaginateTypeDef,
     ListIndexesInputRequestTypeDef,
+    ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef,
     ListSupportedResourceTypesInputRequestTypeDef,
     SupportedResourceTypeTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    ListViewsInputListViewsPaginateTypeDef,
     ListViewsInputRequestTypeDef,
+    ListViewsOutputTypeDef,
+    PaginatorConfigTypeDef,
     ResourceCountTypeDef,
     ResourcePropertyTypeDef,
+    ResponseMetadataTypeDef,
     SearchInputRequestTypeDef,
+    SearchInputSearchPaginateTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateIndexTypeInputRequestTypeDef,
-    AssociateDefaultViewOutputTypeDef,
-    CreateIndexOutputTypeDef,
-    DeleteIndexOutputTypeDef,
-    DeleteViewOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDefaultViewOutputTypeDef,
-    GetIndexOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    ListViewsOutputTypeDef,
     UpdateIndexTypeOutputTypeDef,
     CreateViewInputRequestTypeDef,
     UpdateViewInputRequestTypeDef,
     ViewTypeDef,
     ListIndexesOutputTypeDef,
-    ListIndexesInputListIndexesPaginateTypeDef,
-    ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef,
-    ListViewsInputListViewsPaginateTypeDef,
-    SearchInputSearchPaginateTypeDef,
     ListSupportedResourceTypesOutputTypeDef,
     ResourceTypeDef,
     BatchGetViewOutputTypeDef,
     CreateViewOutputTypeDef,
     GetViewOutputTypeDef,
     UpdateViewOutputTypeDef,
     SearchOutputTypeDef,
@@ -358,43 +358,43 @@
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

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/setup.py` & `types-aiobotocore-resource-explorer-2-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-resource-explorer-2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-resource-explorer-2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_resource_explorer_2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ResourceExplorer 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ResourceExplorer 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/",
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

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/__init__.py` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/__init__.pyi` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/__main__.py` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ResourceExplorer 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ResourceExplorer 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer\nOther"
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

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/client.py` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/client.pyi` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/literals.py` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -99,14 +99,15 @@
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
@@ -185,14 +186,15 @@
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
@@ -203,14 +205,15 @@
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
@@ -246,14 +249,15 @@
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
@@ -272,16 +276,19 @@
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
@@ -365,15 +372,17 @@
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
@@ -393,16 +402,14 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_indexes", "list_supported_resource_types", "list_views", "search"]
 RegionName = Literal[
-    "af-south-1",
-    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/literals.pyi` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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
@@ -391,16 +400,14 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_indexes", "list_supported_resource_types", "list_views", "search"]
 RegionName = Literal[
-    "af-south-1",
-    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/paginator.py` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         list_indexes_paginator: ListIndexesPaginator = client.get_paginator("list_indexes")
         list_supported_resource_types_paginator: ListSupportedResourceTypesPaginator = client.get_paginator("list_supported_resource_types")
         list_views_paginator: ListViewsPaginator = client.get_paginator("list_views")
         search_paginator: SearchPaginator = client.get_paginator("search")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import IndexTypeType
 from .type_defs import (
     ListIndexesOutputTypeDef,
     ListSupportedResourceTypesOutputTypeDef,
     ListViewsOutputTypeDef,
     PaginatorConfigTypeDef,
     SearchOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListIndexesPaginator",
     "ListSupportedResourceTypesPaginator",
     "ListViewsPaginator",
     "SearchPaginator",
 )
 
@@ -72,45 +65,45 @@
     """
 
     def paginate(
         self,
         *,
         Regions: Sequence[str] = ...,
         Type: IndexTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIndexesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListIndexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listindexespaginator)
         """
 
 
 class ListSupportedResourceTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListSupportedResourceTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listsupportedresourcetypespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSupportedResourceTypesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListSupportedResourceTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listsupportedresourcetypespaginator)
         """
 
 
 class ListViewsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListViews)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listviewspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListViewsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListViews.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listviewspaginator)
         """
 
 
@@ -121,13 +114,13 @@
     """
 
     def paginate(
         self,
         *,
         QueryString: str,
         ViewArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.Search.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#searchpaginator)
         """
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/paginator.pyi` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         list_indexes_paginator: ListIndexesPaginator = client.get_paginator("list_indexes")
         list_supported_resource_types_paginator: ListSupportedResourceTypesPaginator = client.get_paginator("list_supported_resource_types")
         list_views_paginator: ListViewsPaginator = client.get_paginator("list_views")
         search_paginator: SearchPaginator = client.get_paginator("search")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import IndexTypeType
 from .type_defs import (
     ListIndexesOutputTypeDef,
     ListSupportedResourceTypesOutputTypeDef,
     ListViewsOutputTypeDef,
     PaginatorConfigTypeDef,
     SearchOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListIndexesPaginator",
     "ListSupportedResourceTypesPaginator",
     "ListViewsPaginator",
     "SearchPaginator",
 )
 
@@ -68,43 +62,43 @@
     """
 
     def paginate(
         self,
         *,
         Regions: Sequence[str] = ...,
         Type: IndexTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIndexesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListIndexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listindexespaginator)
         """
 
 class ListSupportedResourceTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListSupportedResourceTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listsupportedresourcetypespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSupportedResourceTypesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListSupportedResourceTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listsupportedresourcetypespaginator)
         """
 
 class ListViewsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListViews)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listviewspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListViewsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.ListViews.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#listviewspaginator)
         """
 
 class SearchPaginator(AioPaginator):
@@ -114,13 +108,13 @@
     """
 
     def paginate(
         self,
         *,
         QueryString: str,
         ViewArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer.Paginator.Search.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/paginators/#searchpaginator)
         """
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/type_defs.py` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -21,54 +21,54 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateDefaultViewInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateDefaultViewOutputTypeDef",
     "BatchGetViewErrorTypeDef",
     "BatchGetViewInputRequestTypeDef",
     "CreateIndexInputRequestTypeDef",
+    "CreateIndexOutputTypeDef",
     "IncludedPropertyTypeDef",
     "SearchFilterTypeDef",
     "DeleteIndexInputRequestTypeDef",
+    "DeleteIndexOutputTypeDef",
     "DeleteViewInputRequestTypeDef",
+    "DeleteViewOutputTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "GetDefaultViewOutputTypeDef",
+    "GetIndexOutputTypeDef",
     "GetViewInputRequestTypeDef",
     "IndexTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListIndexesInputListIndexesPaginateTypeDef",
     "ListIndexesInputRequestTypeDef",
+    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
     "ListSupportedResourceTypesInputRequestTypeDef",
     "SupportedResourceTypeTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "ListViewsInputListViewsPaginateTypeDef",
     "ListViewsInputRequestTypeDef",
+    "ListViewsOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourceCountTypeDef",
     "ResourcePropertyTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchInputRequestTypeDef",
+    "SearchInputSearchPaginateTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateIndexTypeInputRequestTypeDef",
-    "AssociateDefaultViewOutputTypeDef",
-    "CreateIndexOutputTypeDef",
-    "DeleteIndexOutputTypeDef",
-    "DeleteViewOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetDefaultViewOutputTypeDef",
-    "GetIndexOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "ListViewsOutputTypeDef",
     "UpdateIndexTypeOutputTypeDef",
     "CreateViewInputRequestTypeDef",
     "UpdateViewInputRequestTypeDef",
     "ViewTypeDef",
     "ListIndexesOutputTypeDef",
-    "ListIndexesInputListIndexesPaginateTypeDef",
-    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
-    "ListViewsInputListViewsPaginateTypeDef",
-    "SearchInputSearchPaginateTypeDef",
     "ListSupportedResourceTypesOutputTypeDef",
     "ResourceTypeDef",
     "BatchGetViewOutputTypeDef",
     "CreateViewOutputTypeDef",
     "GetViewOutputTypeDef",
     "UpdateViewOutputTypeDef",
     "SearchOutputTypeDef",
@@ -77,22 +77,19 @@
 AssociateDefaultViewInputRequestTypeDef = TypedDict(
     "AssociateDefaultViewInputRequestTypeDef",
     {
         "ViewArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateDefaultViewOutputTypeDef = TypedDict(
+    "AssociateDefaultViewOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ViewArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetViewErrorTypeDef = TypedDict(
     "BatchGetViewErrorTypeDef",
     {
         "ErrorMessage": str,
@@ -113,14 +110,24 @@
     {
         "ClientToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+CreateIndexOutputTypeDef = TypedDict(
+    "CreateIndexOutputTypeDef",
+    {
+        "Arn": str,
+        "CreatedAt": datetime,
+        "State": IndexStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IncludedPropertyTypeDef = TypedDict(
     "IncludedPropertyTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -134,21 +141,69 @@
 DeleteIndexInputRequestTypeDef = TypedDict(
     "DeleteIndexInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeleteIndexOutputTypeDef = TypedDict(
+    "DeleteIndexOutputTypeDef",
+    {
+        "Arn": str,
+        "LastUpdatedAt": datetime,
+        "State": IndexStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteViewInputRequestTypeDef = TypedDict(
     "DeleteViewInputRequestTypeDef",
     {
         "ViewArn": str,
     },
 )
 
+DeleteViewOutputTypeDef = TypedDict(
+    "DeleteViewOutputTypeDef",
+    {
+        "ViewArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetDefaultViewOutputTypeDef = TypedDict(
+    "GetDefaultViewOutputTypeDef",
+    {
+        "ViewArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetIndexOutputTypeDef = TypedDict(
+    "GetIndexOutputTypeDef",
+    {
+        "Arn": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "ReplicatingFrom": List[str],
+        "ReplicatingTo": List[str],
+        "State": IndexStateType,
+        "Tags": Dict[str, str],
+        "Type": IndexTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetViewInputRequestTypeDef = TypedDict(
     "GetViewInputRequestTypeDef",
     {
         "ViewArn": str,
     },
 )
 
@@ -158,20 +213,20 @@
         "Arn": str,
         "Region": str,
         "Type": IndexTypeType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListIndexesInputListIndexesPaginateTypeDef = TypedDict(
+    "ListIndexesInputListIndexesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Regions": Sequence[str],
+        "Type": IndexTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListIndexesInputRequestTypeDef = TypedDict(
     "ListIndexesInputRequestTypeDef",
     {
@@ -179,14 +234,22 @@
         "NextToken": str,
         "Regions": Sequence[str],
         "Type": IndexTypeType,
     },
     total=False,
 )
 
+ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef = TypedDict(
+    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSupportedResourceTypesInputRequestTypeDef = TypedDict(
     "ListSupportedResourceTypesInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -204,23 +267,58 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListViewsInputListViewsPaginateTypeDef = TypedDict(
+    "ListViewsInputListViewsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListViewsInputRequestTypeDef = TypedDict(
     "ListViewsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListViewsOutputTypeDef = TypedDict(
+    "ListViewsOutputTypeDef",
+    {
+        "NextToken": str,
+        "Views": List[str],
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
 ResourceCountTypeDef = TypedDict(
     "ResourceCountTypeDef",
     {
         "Complete": bool,
         "TotalResources": int,
     },
     total=False,
@@ -232,14 +330,25 @@
         "Data": Dict[str, Any],
         "LastReportedAt": datetime,
         "Name": str,
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
 _RequiredSearchInputRequestTypeDef = TypedDict(
     "_RequiredSearchInputRequestTypeDef",
     {
         "QueryString": str,
     },
 )
 _OptionalSearchInputRequestTypeDef = TypedDict(
@@ -255,14 +364,36 @@
 
 class SearchInputRequestTypeDef(
     _RequiredSearchInputRequestTypeDef, _OptionalSearchInputRequestTypeDef
 ):
     pass
 
 
+_RequiredSearchInputSearchPaginateTypeDef = TypedDict(
+    "_RequiredSearchInputSearchPaginateTypeDef",
+    {
+        "QueryString": str,
+    },
+)
+_OptionalSearchInputSearchPaginateTypeDef = TypedDict(
+    "_OptionalSearchInputSearchPaginateTypeDef",
+    {
+        "ViewArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SearchInputSearchPaginateTypeDef(
+    _RequiredSearchInputSearchPaginateTypeDef, _OptionalSearchInputSearchPaginateTypeDef
+):
+    pass
+
+
 _RequiredTagResourceInputRequestTypeDef = TypedDict(
     "_RequiredTagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalTagResourceInputRequestTypeDef = TypedDict(
@@ -292,105 +423,22 @@
     "UpdateIndexTypeInputRequestTypeDef",
     {
         "Arn": str,
         "Type": IndexTypeType,
     },
 )
 
-AssociateDefaultViewOutputTypeDef = TypedDict(
-    "AssociateDefaultViewOutputTypeDef",
-    {
-        "ViewArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIndexOutputTypeDef = TypedDict(
-    "CreateIndexOutputTypeDef",
-    {
-        "Arn": str,
-        "CreatedAt": datetime,
-        "State": IndexStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteIndexOutputTypeDef = TypedDict(
-    "DeleteIndexOutputTypeDef",
-    {
-        "Arn": str,
-        "LastUpdatedAt": datetime,
-        "State": IndexStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteViewOutputTypeDef = TypedDict(
-    "DeleteViewOutputTypeDef",
-    {
-        "ViewArn": str,
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
-GetDefaultViewOutputTypeDef = TypedDict(
-    "GetDefaultViewOutputTypeDef",
-    {
-        "ViewArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIndexOutputTypeDef = TypedDict(
-    "GetIndexOutputTypeDef",
-    {
-        "Arn": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "ReplicatingFrom": List[str],
-        "ReplicatingTo": List[str],
-        "State": IndexStateType,
-        "Tags": Dict[str, str],
-        "Type": IndexTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListViewsOutputTypeDef = TypedDict(
-    "ListViewsOutputTypeDef",
-    {
-        "NextToken": str,
-        "Views": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateIndexTypeOutputTypeDef = TypedDict(
     "UpdateIndexTypeOutputTypeDef",
     {
         "Arn": str,
         "LastUpdatedAt": datetime,
         "State": IndexStateType,
         "Type": IndexTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateViewInputRequestTypeDef = TypedDict(
     "_RequiredCreateViewInputRequestTypeDef",
     {
         "ViewName": str,
@@ -450,72 +498,24 @@
 )
 
 ListIndexesOutputTypeDef = TypedDict(
     "ListIndexesOutputTypeDef",
     {
         "Indexes": List[IndexTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIndexesInputListIndexesPaginateTypeDef = TypedDict(
-    "ListIndexesInputListIndexesPaginateTypeDef",
-    {
-        "Regions": Sequence[str],
-        "Type": IndexTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef = TypedDict(
-    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListViewsInputListViewsPaginateTypeDef = TypedDict(
-    "ListViewsInputListViewsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSearchInputSearchPaginateTypeDef = TypedDict(
-    "_RequiredSearchInputSearchPaginateTypeDef",
-    {
-        "QueryString": str,
-    },
-)
-_OptionalSearchInputSearchPaginateTypeDef = TypedDict(
-    "_OptionalSearchInputSearchPaginateTypeDef",
-    {
-        "ViewArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
-
-class SearchInputSearchPaginateTypeDef(
-    _RequiredSearchInputSearchPaginateTypeDef, _OptionalSearchInputSearchPaginateTypeDef
-):
-    pass
-
-
 ListSupportedResourceTypesOutputTypeDef = TypedDict(
     "ListSupportedResourceTypesOutputTypeDef",
     {
         "NextToken": str,
         "ResourceTypes": List[SupportedResourceTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceTypeDef = TypedDict(
     "ResourceTypeDef",
     {
         "Arn": str,
@@ -530,46 +530,46 @@
 )
 
 BatchGetViewOutputTypeDef = TypedDict(
     "BatchGetViewOutputTypeDef",
     {
         "Errors": List[BatchGetViewErrorTypeDef],
         "Views": List[ViewTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateViewOutputTypeDef = TypedDict(
     "CreateViewOutputTypeDef",
     {
         "View": ViewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetViewOutputTypeDef = TypedDict(
     "GetViewOutputTypeDef",
     {
         "Tags": Dict[str, str],
         "View": ViewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateViewOutputTypeDef = TypedDict(
     "UpdateViewOutputTypeDef",
     {
         "View": ViewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchOutputTypeDef = TypedDict(
     "SearchOutputTypeDef",
     {
         "Count": ResourceCountTypeDef,
         "NextToken": str,
         "Resources": List[ResourceTypeDef],
         "ViewArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2/type_defs.pyi` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2/type_defs.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -20,54 +20,54 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateDefaultViewInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateDefaultViewOutputTypeDef",
     "BatchGetViewErrorTypeDef",
     "BatchGetViewInputRequestTypeDef",
     "CreateIndexInputRequestTypeDef",
+    "CreateIndexOutputTypeDef",
     "IncludedPropertyTypeDef",
     "SearchFilterTypeDef",
     "DeleteIndexInputRequestTypeDef",
+    "DeleteIndexOutputTypeDef",
     "DeleteViewInputRequestTypeDef",
+    "DeleteViewOutputTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "GetDefaultViewOutputTypeDef",
+    "GetIndexOutputTypeDef",
     "GetViewInputRequestTypeDef",
     "IndexTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListIndexesInputListIndexesPaginateTypeDef",
     "ListIndexesInputRequestTypeDef",
+    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
     "ListSupportedResourceTypesInputRequestTypeDef",
     "SupportedResourceTypeTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "ListViewsInputListViewsPaginateTypeDef",
     "ListViewsInputRequestTypeDef",
+    "ListViewsOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourceCountTypeDef",
     "ResourcePropertyTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchInputRequestTypeDef",
+    "SearchInputSearchPaginateTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateIndexTypeInputRequestTypeDef",
-    "AssociateDefaultViewOutputTypeDef",
-    "CreateIndexOutputTypeDef",
-    "DeleteIndexOutputTypeDef",
-    "DeleteViewOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetDefaultViewOutputTypeDef",
-    "GetIndexOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "ListViewsOutputTypeDef",
     "UpdateIndexTypeOutputTypeDef",
     "CreateViewInputRequestTypeDef",
     "UpdateViewInputRequestTypeDef",
     "ViewTypeDef",
     "ListIndexesOutputTypeDef",
-    "ListIndexesInputListIndexesPaginateTypeDef",
-    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
-    "ListViewsInputListViewsPaginateTypeDef",
-    "SearchInputSearchPaginateTypeDef",
     "ListSupportedResourceTypesOutputTypeDef",
     "ResourceTypeDef",
     "BatchGetViewOutputTypeDef",
     "CreateViewOutputTypeDef",
     "GetViewOutputTypeDef",
     "UpdateViewOutputTypeDef",
     "SearchOutputTypeDef",
@@ -76,22 +76,19 @@
 AssociateDefaultViewInputRequestTypeDef = TypedDict(
     "AssociateDefaultViewInputRequestTypeDef",
     {
         "ViewArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateDefaultViewOutputTypeDef = TypedDict(
+    "AssociateDefaultViewOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ViewArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetViewErrorTypeDef = TypedDict(
     "BatchGetViewErrorTypeDef",
     {
         "ErrorMessage": str,
@@ -112,14 +109,24 @@
     {
         "ClientToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+CreateIndexOutputTypeDef = TypedDict(
+    "CreateIndexOutputTypeDef",
+    {
+        "Arn": str,
+        "CreatedAt": datetime,
+        "State": IndexStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IncludedPropertyTypeDef = TypedDict(
     "IncludedPropertyTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -133,21 +140,69 @@
 DeleteIndexInputRequestTypeDef = TypedDict(
     "DeleteIndexInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeleteIndexOutputTypeDef = TypedDict(
+    "DeleteIndexOutputTypeDef",
+    {
+        "Arn": str,
+        "LastUpdatedAt": datetime,
+        "State": IndexStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteViewInputRequestTypeDef = TypedDict(
     "DeleteViewInputRequestTypeDef",
     {
         "ViewArn": str,
     },
 )
 
+DeleteViewOutputTypeDef = TypedDict(
+    "DeleteViewOutputTypeDef",
+    {
+        "ViewArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetDefaultViewOutputTypeDef = TypedDict(
+    "GetDefaultViewOutputTypeDef",
+    {
+        "ViewArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetIndexOutputTypeDef = TypedDict(
+    "GetIndexOutputTypeDef",
+    {
+        "Arn": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "ReplicatingFrom": List[str],
+        "ReplicatingTo": List[str],
+        "State": IndexStateType,
+        "Tags": Dict[str, str],
+        "Type": IndexTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetViewInputRequestTypeDef = TypedDict(
     "GetViewInputRequestTypeDef",
     {
         "ViewArn": str,
     },
 )
 
@@ -157,20 +212,20 @@
         "Arn": str,
         "Region": str,
         "Type": IndexTypeType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListIndexesInputListIndexesPaginateTypeDef = TypedDict(
+    "ListIndexesInputListIndexesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Regions": Sequence[str],
+        "Type": IndexTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListIndexesInputRequestTypeDef = TypedDict(
     "ListIndexesInputRequestTypeDef",
     {
@@ -178,14 +233,22 @@
         "NextToken": str,
         "Regions": Sequence[str],
         "Type": IndexTypeType,
     },
     total=False,
 )
 
+ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef = TypedDict(
+    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSupportedResourceTypesInputRequestTypeDef = TypedDict(
     "ListSupportedResourceTypesInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -203,23 +266,58 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListViewsInputListViewsPaginateTypeDef = TypedDict(
+    "ListViewsInputListViewsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListViewsInputRequestTypeDef = TypedDict(
     "ListViewsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListViewsOutputTypeDef = TypedDict(
+    "ListViewsOutputTypeDef",
+    {
+        "NextToken": str,
+        "Views": List[str],
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
 ResourceCountTypeDef = TypedDict(
     "ResourceCountTypeDef",
     {
         "Complete": bool,
         "TotalResources": int,
     },
     total=False,
@@ -231,14 +329,25 @@
         "Data": Dict[str, Any],
         "LastReportedAt": datetime,
         "Name": str,
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
 _RequiredSearchInputRequestTypeDef = TypedDict(
     "_RequiredSearchInputRequestTypeDef",
     {
         "QueryString": str,
     },
 )
 _OptionalSearchInputRequestTypeDef = TypedDict(
@@ -252,14 +361,34 @@
 )
 
 class SearchInputRequestTypeDef(
     _RequiredSearchInputRequestTypeDef, _OptionalSearchInputRequestTypeDef
 ):
     pass
 
+_RequiredSearchInputSearchPaginateTypeDef = TypedDict(
+    "_RequiredSearchInputSearchPaginateTypeDef",
+    {
+        "QueryString": str,
+    },
+)
+_OptionalSearchInputSearchPaginateTypeDef = TypedDict(
+    "_OptionalSearchInputSearchPaginateTypeDef",
+    {
+        "ViewArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SearchInputSearchPaginateTypeDef(
+    _RequiredSearchInputSearchPaginateTypeDef, _OptionalSearchInputSearchPaginateTypeDef
+):
+    pass
+
 _RequiredTagResourceInputRequestTypeDef = TypedDict(
     "_RequiredTagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalTagResourceInputRequestTypeDef = TypedDict(
@@ -287,105 +416,22 @@
     "UpdateIndexTypeInputRequestTypeDef",
     {
         "Arn": str,
         "Type": IndexTypeType,
     },
 )
 
-AssociateDefaultViewOutputTypeDef = TypedDict(
-    "AssociateDefaultViewOutputTypeDef",
-    {
-        "ViewArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIndexOutputTypeDef = TypedDict(
-    "CreateIndexOutputTypeDef",
-    {
-        "Arn": str,
-        "CreatedAt": datetime,
-        "State": IndexStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteIndexOutputTypeDef = TypedDict(
-    "DeleteIndexOutputTypeDef",
-    {
-        "Arn": str,
-        "LastUpdatedAt": datetime,
-        "State": IndexStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteViewOutputTypeDef = TypedDict(
-    "DeleteViewOutputTypeDef",
-    {
-        "ViewArn": str,
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
-GetDefaultViewOutputTypeDef = TypedDict(
-    "GetDefaultViewOutputTypeDef",
-    {
-        "ViewArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIndexOutputTypeDef = TypedDict(
-    "GetIndexOutputTypeDef",
-    {
-        "Arn": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "ReplicatingFrom": List[str],
-        "ReplicatingTo": List[str],
-        "State": IndexStateType,
-        "Tags": Dict[str, str],
-        "Type": IndexTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListViewsOutputTypeDef = TypedDict(
-    "ListViewsOutputTypeDef",
-    {
-        "NextToken": str,
-        "Views": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateIndexTypeOutputTypeDef = TypedDict(
     "UpdateIndexTypeOutputTypeDef",
     {
         "Arn": str,
         "LastUpdatedAt": datetime,
         "State": IndexStateType,
         "Type": IndexTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateViewInputRequestTypeDef = TypedDict(
     "_RequiredCreateViewInputRequestTypeDef",
     {
         "ViewName": str,
@@ -441,70 +487,24 @@
 )
 
 ListIndexesOutputTypeDef = TypedDict(
     "ListIndexesOutputTypeDef",
     {
         "Indexes": List[IndexTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListIndexesInputListIndexesPaginateTypeDef = TypedDict(
-    "ListIndexesInputListIndexesPaginateTypeDef",
-    {
-        "Regions": Sequence[str],
-        "Type": IndexTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef = TypedDict(
-    "ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListViewsInputListViewsPaginateTypeDef = TypedDict(
-    "ListViewsInputListViewsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSearchInputSearchPaginateTypeDef = TypedDict(
-    "_RequiredSearchInputSearchPaginateTypeDef",
-    {
-        "QueryString": str,
-    },
-)
-_OptionalSearchInputSearchPaginateTypeDef = TypedDict(
-    "_OptionalSearchInputSearchPaginateTypeDef",
-    {
-        "ViewArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SearchInputSearchPaginateTypeDef(
-    _RequiredSearchInputSearchPaginateTypeDef, _OptionalSearchInputSearchPaginateTypeDef
-):
-    pass
-
 ListSupportedResourceTypesOutputTypeDef = TypedDict(
     "ListSupportedResourceTypesOutputTypeDef",
     {
         "NextToken": str,
         "ResourceTypes": List[SupportedResourceTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourceTypeDef = TypedDict(
     "ResourceTypeDef",
     {
         "Arn": str,
@@ -519,46 +519,46 @@
 )
 
 BatchGetViewOutputTypeDef = TypedDict(
     "BatchGetViewOutputTypeDef",
     {
         "Errors": List[BatchGetViewErrorTypeDef],
         "Views": List[ViewTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateViewOutputTypeDef = TypedDict(
     "CreateViewOutputTypeDef",
     {
         "View": ViewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetViewOutputTypeDef = TypedDict(
     "GetViewOutputTypeDef",
     {
         "Tags": Dict[str, str],
         "View": ViewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateViewOutputTypeDef = TypedDict(
     "UpdateViewOutputTypeDef",
     {
         "View": ViewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchOutputTypeDef = TypedDict(
     "SearchOutputTypeDef",
     {
         "Count": ResourceCountTypeDef,
         "NextToken": str,
         "Resources": List[ResourceTypeDef],
         "ViewArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/PKG-INFO` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resource-explorer-2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResourceExplorer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResourceExplorer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resource-explorer-2"></a>
 
 # types-aiobotocore-resource-explorer-2
 
 [![PyPI - types-aiobotocore-resource-explorer-2](https://img.shields.io/pypi/v/types-aiobotocore-resource-explorer-2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-explorer-2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resource-explorer-2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-explorer-2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resource-explorer-2?color=blue)](https://pypistats.org/packages/types-aiobotocore-resource-explorer-2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceExplorer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer)
+[aiobotocore.ResourceExplorer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-explorer-2.html#ResourceExplorer)
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
 [types-aiobotocore-resource-explorer-2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_explorer_2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,54 +330,54 @@
 
 `types_aiobotocore_resource_explorer_2.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resource_explorer_2.type_defs import (
     AssociateDefaultViewInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateDefaultViewOutputTypeDef,
     BatchGetViewErrorTypeDef,
     BatchGetViewInputRequestTypeDef,
     CreateIndexInputRequestTypeDef,
+    CreateIndexOutputTypeDef,
     IncludedPropertyTypeDef,
     SearchFilterTypeDef,
     DeleteIndexInputRequestTypeDef,
+    DeleteIndexOutputTypeDef,
     DeleteViewInputRequestTypeDef,
+    DeleteViewOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
+    GetDefaultViewOutputTypeDef,
+    GetIndexOutputTypeDef,
     GetViewInputRequestTypeDef,
     IndexTypeDef,
-    PaginatorConfigTypeDef,
+    ListIndexesInputListIndexesPaginateTypeDef,
     ListIndexesInputRequestTypeDef,
+    ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef,
     ListSupportedResourceTypesInputRequestTypeDef,
     SupportedResourceTypeTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    ListViewsInputListViewsPaginateTypeDef,
     ListViewsInputRequestTypeDef,
+    ListViewsOutputTypeDef,
+    PaginatorConfigTypeDef,
     ResourceCountTypeDef,
     ResourcePropertyTypeDef,
+    ResponseMetadataTypeDef,
     SearchInputRequestTypeDef,
+    SearchInputSearchPaginateTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateIndexTypeInputRequestTypeDef,
-    AssociateDefaultViewOutputTypeDef,
-    CreateIndexOutputTypeDef,
-    DeleteIndexOutputTypeDef,
-    DeleteViewOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDefaultViewOutputTypeDef,
-    GetIndexOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    ListViewsOutputTypeDef,
     UpdateIndexTypeOutputTypeDef,
     CreateViewInputRequestTypeDef,
     UpdateViewInputRequestTypeDef,
     ViewTypeDef,
     ListIndexesOutputTypeDef,
-    ListIndexesInputListIndexesPaginateTypeDef,
-    ListSupportedResourceTypesInputListSupportedResourceTypesPaginateTypeDef,
-    ListViewsInputListViewsPaginateTypeDef,
-    SearchInputSearchPaginateTypeDef,
     ListSupportedResourceTypesOutputTypeDef,
     ResourceTypeDef,
     BatchGetViewOutputTypeDef,
     CreateViewOutputTypeDef,
     GetViewOutputTypeDef,
     UpdateViewOutputTypeDef,
     SearchOutputTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-resource-explorer-2-2.5.0.post1/types_aiobotocore_resource_explorer_2.egg-info/SOURCES.txt` & `types-aiobotocore-resource-explorer-2-2.5.1/types_aiobotocore_resource_explorer_2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

