# Comparing `tmp/types-aiobotocore-marketplace-catalog-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-marketplace-catalog-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-marketplace-catalog-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:57 2023, max compression
+gzip compressed data, was "types-aiobotocore-marketplace-catalog-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1.tar` & `types-aiobotocore-marketplace-catalog-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:57.191401 types-aiobotocore-marketplace-catalog-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13533 2023-03-11 12:26:57.187401 types-aiobotocore-marketplace-catalog-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11915 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:57.191401 types-aiobotocore-marketplace-catalog-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2199 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:57.175401 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/
--rw-r--r--   0 runner    (1001) docker     (123)      533 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      532 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11081 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    11064 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7695 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7693 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8486 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8476 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:06.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:57.187401 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13533 2023-03-11 12:26:57.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:26:57.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:57.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:57.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:57.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:57.000000 types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.142173 types-aiobotocore-marketplace-catalog-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14862 2023-06-28 01:43:49.142173 types-aiobotocore-marketplace-catalog-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13250 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.142173 types-aiobotocore-marketplace-catalog-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2193 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.134173 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/
+-rw-r--r--   0 runner    (1001) docker     (123)      910 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      909 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13997 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13974 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8236 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8234 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3652 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3648 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    11113 2023-06-28 01:34:49.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11099 2023-06-28 01:34:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:47.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.142173 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14862 2023-06-28 01:43:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1041 2023-06-28 01:43:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:48.000000 types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/LICENSE` & `types-aiobotocore-marketplace-catalog-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/PKG-INFO` & `types-aiobotocore-marketplace-catalog-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-marketplace-catalog
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceCatalog 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceCatalog 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-marketplace-catalog"></a>
 
 # types-aiobotocore-marketplace-catalog
 
 [![PyPI - types-aiobotocore-marketplace-catalog](https://img.shields.io/pypi/v/types-aiobotocore-marketplace-catalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-catalog)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplace-catalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-catalog)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplace-catalog?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplace-catalog)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceCatalog 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
+[aiobotocore.MarketplaceCatalog 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
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
 [types-aiobotocore-marketplace-catalog docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/).
 
 See how it helps to find and fix potential bugs:
 
@@ -72,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -260,29 +261,59 @@
 
 session = get_session()
 async with session.create_client("marketplace-catalog") as client:
     client: MarketplaceCatalogClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_marketplace_catalog.paginator` module contains type
+annotations for all paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_marketplace_catalog import MarketplaceCatalogClient
+from types_aiobotocore_marketplace_catalog.paginator import (
+    ListChangeSetsPaginator,
+    ListEntitiesPaginator,
+)
+
+session = get_session()
+async with session.create_client("marketplace-catalog") as client:
+    client: MarketplaceCatalogClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_change_sets_paginator: ListChangeSetsPaginator = client.get_paginator("list_change_sets")
+    list_entities_paginator: ListEntitiesPaginator = client.get_paginator("list_entities")
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_marketplace_catalog.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_marketplace_catalog.literals import (
     ChangeStatusType,
     FailureCodeType,
+    ListChangeSetsPaginatorName,
+    ListEntitiesPaginatorName,
+    OwnershipTypeType,
     SortOrderType,
     MarketplaceCatalogServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
 def check_value(value: ChangeStatusType) -> bool:
     ...
 ```
@@ -293,36 +324,43 @@
 
 `types_aiobotocore_marketplace_catalog.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_marketplace_catalog.type_defs import (
     CancelChangeSetRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelChangeSetResponseTypeDef,
     ChangeSetSummaryListItemTypeDef,
     EntityTypeDef,
     ErrorDetailTypeDef,
     TagTypeDef,
+    DeleteResourcePolicyRequestRequestTypeDef,
     DescribeChangeSetRequestRequestTypeDef,
     DescribeEntityRequestRequestTypeDef,
+    DescribeEntityResponseTypeDef,
     EntitySummaryTypeDef,
     FilterTypeDef,
+    GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     SortTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    CancelChangeSetResponseTypeDef,
-    DescribeEntityResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartChangeSetResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     ListChangeSetsResponseTypeDef,
     ChangeSummaryTypeDef,
     ChangeTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListEntitiesResponseTypeDef,
+    ListChangeSetsRequestListChangeSetsPaginateTypeDef,
     ListChangeSetsRequestRequestTypeDef,
+    ListEntitiesRequestListEntitiesPaginateTypeDef,
     ListEntitiesRequestRequestTypeDef,
     DescribeChangeSetResponseTypeDef,
     StartChangeSetRequestRequestTypeDef,
 )
 
 
 def get_structure() -> CancelChangeSetRequestRequestTypeDef:
@@ -332,43 +370,43 @@
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

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/README.md` & `types-aiobotocore-marketplace-catalog-2.5.1/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-marketplace-catalog"></a>
 
 # types-aiobotocore-marketplace-catalog
 
 [![PyPI - types-aiobotocore-marketplace-catalog](https://img.shields.io/pypi/v/types-aiobotocore-marketplace-catalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-catalog)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplace-catalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-catalog)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplace-catalog?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplace-catalog)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceCatalog 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
+[aiobotocore.MarketplaceCatalog 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
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
 [types-aiobotocore-marketplace-catalog docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/).
 
 See how it helps to find and fix potential bugs:
 
@@ -39,14 +39,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -227,29 +228,59 @@
 
 session = get_session()
 async with session.create_client("marketplace-catalog") as client:
     client: MarketplaceCatalogClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_marketplace_catalog.paginator` module contains type
+annotations for all paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_marketplace_catalog import MarketplaceCatalogClient
+from types_aiobotocore_marketplace_catalog.paginator import (
+    ListChangeSetsPaginator,
+    ListEntitiesPaginator,
+)
+
+session = get_session()
+async with session.create_client("marketplace-catalog") as client:
+    client: MarketplaceCatalogClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_change_sets_paginator: ListChangeSetsPaginator = client.get_paginator("list_change_sets")
+    list_entities_paginator: ListEntitiesPaginator = client.get_paginator("list_entities")
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_marketplace_catalog.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_marketplace_catalog.literals import (
     ChangeStatusType,
     FailureCodeType,
+    ListChangeSetsPaginatorName,
+    ListEntitiesPaginatorName,
+    OwnershipTypeType,
     SortOrderType,
     MarketplaceCatalogServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
 def check_value(value: ChangeStatusType) -> bool:
     ...
 ```
@@ -260,36 +291,43 @@
 
 `types_aiobotocore_marketplace_catalog.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_marketplace_catalog.type_defs import (
     CancelChangeSetRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelChangeSetResponseTypeDef,
     ChangeSetSummaryListItemTypeDef,
     EntityTypeDef,
     ErrorDetailTypeDef,
     TagTypeDef,
+    DeleteResourcePolicyRequestRequestTypeDef,
     DescribeChangeSetRequestRequestTypeDef,
     DescribeEntityRequestRequestTypeDef,
+    DescribeEntityResponseTypeDef,
     EntitySummaryTypeDef,
     FilterTypeDef,
+    GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     SortTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    CancelChangeSetResponseTypeDef,
-    DescribeEntityResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartChangeSetResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     ListChangeSetsResponseTypeDef,
     ChangeSummaryTypeDef,
     ChangeTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListEntitiesResponseTypeDef,
+    ListChangeSetsRequestListChangeSetsPaginateTypeDef,
     ListChangeSetsRequestRequestTypeDef,
+    ListEntitiesRequestListEntitiesPaginateTypeDef,
     ListEntitiesRequestRequestTypeDef,
     DescribeChangeSetResponseTypeDef,
     StartChangeSetRequestRequestTypeDef,
 )
 
 
 def get_structure() -> CancelChangeSetRequestRequestTypeDef:
@@ -299,43 +337,43 @@
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

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/setup.py` & `types-aiobotocore-marketplace-catalog-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-marketplace-catalog.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-marketplace-catalog",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_marketplace_catalog"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MarketplaceCatalog 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MarketplaceCatalog 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/",
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

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/__main__.py` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MarketplaceCatalog 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MarketplaceCatalog 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog\nOther"
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

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/client.py` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/client.py`

 * *Files 13% similar despite different names*

```diff
@@ -10,33 +10,43 @@
     from types_aiobotocore_marketplace_catalog.client import MarketplaceCatalogClient
 
     session = get_session()
     async with session.create_client("marketplace-catalog") as client:
         client: MarketplaceCatalogClient
     ```
 """
-from typing import Any, Dict, Mapping, Sequence, Type
+import sys
+from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import OwnershipTypeType
+from .paginator import ListChangeSetsPaginator, ListEntitiesPaginator
 from .type_defs import (
     CancelChangeSetResponseTypeDef,
     ChangeTypeDef,
     DescribeChangeSetResponseTypeDef,
     DescribeEntityResponseTypeDef,
     FilterTypeDef,
+    GetResourcePolicyResponseTypeDef,
     ListChangeSetsResponseTypeDef,
     ListEntitiesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     SortTypeDef,
     StartChangeSetResponseTypeDef,
     TagTypeDef,
 )
 
+if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+
+
 __all__ = ("MarketplaceCatalogClient",)
 
 
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
@@ -95,14 +105,23 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#close)
         """
 
+    async def delete_resource_policy(self, *, ResourceArn: str) -> Dict[str, Any]:
+        """
+        Deletes a resource-based policy on an Entity that is identified by its resource
+        ARN.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.delete_resource_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#delete_resource_policy)
+        """
+
     async def describe_change_set(
         self, *, Catalog: str, ChangeSetId: str
     ) -> DescribeChangeSetResponseTypeDef:
         """
         Provides information about a given change set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.describe_change_set)
@@ -129,14 +148,23 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#generate_presigned_url)
         """
 
+    async def get_resource_policy(self, *, ResourceArn: str) -> GetResourcePolicyResponseTypeDef:
+        """
+        Gets a resource-based policy of an Entity that is identified by its resource
+        ARN.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.get_resource_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#get_resource_policy)
+        """
+
     async def list_change_sets(
         self,
         *,
         Catalog: str,
         FilterList: Sequence[FilterTypeDef] = ...,
         Sort: SortTypeDef = ...,
         MaxResults: int = ...,
@@ -154,15 +182,16 @@
         self,
         *,
         Catalog: str,
         EntityType: str,
         FilterList: Sequence[FilterTypeDef] = ...,
         Sort: SortTypeDef = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        OwnershipType: OwnershipTypeType = ...
     ) -> ListEntitiesResponseTypeDef:
         """
         Provides the list of entities of a given type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.list_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#list_entities)
         """
@@ -177,14 +206,22 @@
         <https://docs.aws.amazon.com/marketplace-catalog/latest/api-
         reference/welcome.html#working-with-change-se...`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#list_tags_for_resource)
         """
 
+    async def put_resource_policy(self, *, ResourceArn: str, Policy: str) -> Dict[str, Any]:
+        """
+        Attaches a resource-based policy to an Entity.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.put_resource_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#put_resource_policy)
+        """
+
     async def start_change_set(
         self,
         *,
         Catalog: str,
         ChangeSet: Sequence[ChangeTypeDef],
         ChangeSetName: str = ...,
         ClientRequestToken: str = ...,
@@ -198,15 +235,15 @@
         """
 
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Tags a resource (either an [entity](https://docs.aws.amazon.com/marketplace-
         catalog/latest/api-reference/welcome.html#catalog-api-entities)_ or [change
         set](https://docs.aws.amazon.com/marketplace-catalog/latest/api-
-        reference/welcome.html#working-with-change-sets)_ ).
+        reference/welcome.html#working-with-change-sets)_).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#tag_resource)
         """
 
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
@@ -216,14 +253,28 @@
         set](https://docs.aws.amazon.com/marketplace-catalog/latest/api-
         reference/welcome.html#working-with-change-sets)...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#untag_resource)
         """
 
+    @overload
+    def get_paginator(self, operation_name: Literal["list_change_sets"]) -> ListChangeSetsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_entities"]) -> ListEntitiesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "MarketplaceCatalogClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/)
         """
 
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/client.pyi` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/client.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -10,33 +10,42 @@
     from types_aiobotocore_marketplace_catalog.client import MarketplaceCatalogClient
 
     session = get_session()
     async with session.create_client("marketplace-catalog") as client:
         client: MarketplaceCatalogClient
     ```
 """
-from typing import Any, Dict, Mapping, Sequence, Type
+import sys
+from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import OwnershipTypeType
+from .paginator import ListChangeSetsPaginator, ListEntitiesPaginator
 from .type_defs import (
     CancelChangeSetResponseTypeDef,
     ChangeTypeDef,
     DescribeChangeSetResponseTypeDef,
     DescribeEntityResponseTypeDef,
     FilterTypeDef,
+    GetResourcePolicyResponseTypeDef,
     ListChangeSetsResponseTypeDef,
     ListEntitiesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     SortTypeDef,
     StartChangeSetResponseTypeDef,
     TagTypeDef,
 )
 
+if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+
 __all__ = ("MarketplaceCatalogClient",)
 
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
@@ -88,14 +97,22 @@
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#close)
         """
+    async def delete_resource_policy(self, *, ResourceArn: str) -> Dict[str, Any]:
+        """
+        Deletes a resource-based policy on an Entity that is identified by its resource
+        ARN.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.delete_resource_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#delete_resource_policy)
+        """
     async def describe_change_set(
         self, *, Catalog: str, ChangeSetId: str
     ) -> DescribeChangeSetResponseTypeDef:
         """
         Provides information about a given change set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.describe_change_set)
@@ -119,14 +136,22 @@
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#generate_presigned_url)
         """
+    async def get_resource_policy(self, *, ResourceArn: str) -> GetResourcePolicyResponseTypeDef:
+        """
+        Gets a resource-based policy of an Entity that is identified by its resource
+        ARN.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.get_resource_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#get_resource_policy)
+        """
     async def list_change_sets(
         self,
         *,
         Catalog: str,
         FilterList: Sequence[FilterTypeDef] = ...,
         Sort: SortTypeDef = ...,
         MaxResults: int = ...,
@@ -143,15 +168,16 @@
         self,
         *,
         Catalog: str,
         EntityType: str,
         FilterList: Sequence[FilterTypeDef] = ...,
         Sort: SortTypeDef = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        OwnershipType: OwnershipTypeType = ...
     ) -> ListEntitiesResponseTypeDef:
         """
         Provides the list of entities of a given type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.list_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#list_entities)
         """
@@ -164,14 +190,21 @@
         reference/welcome.html#catalog-api-entities)_ or `change set
         <https://docs.aws.amazon.com/marketplace-catalog/latest/api-
         reference/welcome.html#working-with-change-se...`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#list_tags_for_resource)
         """
+    async def put_resource_policy(self, *, ResourceArn: str, Policy: str) -> Dict[str, Any]:
+        """
+        Attaches a resource-based policy to an Entity.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.put_resource_policy)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#put_resource_policy)
+        """
     async def start_change_set(
         self,
         *,
         Catalog: str,
         ChangeSet: Sequence[ChangeTypeDef],
         ChangeSetName: str = ...,
         ClientRequestToken: str = ...,
@@ -184,15 +217,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#start_change_set)
         """
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Tags a resource (either an [entity](https://docs.aws.amazon.com/marketplace-
         catalog/latest/api-reference/welcome.html#catalog-api-entities)_ or [change
         set](https://docs.aws.amazon.com/marketplace-catalog/latest/api-
-        reference/welcome.html#working-with-change-sets)_ ).
+        reference/welcome.html#working-with-change-sets)_).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#tag_resource)
         """
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a tag or list of tags from a resource (either an
@@ -200,14 +233,26 @@
         reference/welcome.html#catalog-api-entities)_ or [change
         set](https://docs.aws.amazon.com/marketplace-catalog/latest/api-
         reference/welcome.html#working-with-change-sets)...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#untag_resource)
         """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_change_sets"]) -> ListChangeSetsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_entities"]) -> ListEntitiesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/#get_paginator)
+        """
     async def __aenter__(self) -> "MarketplaceCatalogClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/client/)
         """
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/literals.py` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/literals.py`

 * *Files 10% similar despite different names*

```diff
@@ -18,24 +18,31 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "ChangeStatusType",
     "FailureCodeType",
+    "ListChangeSetsPaginatorName",
+    "ListEntitiesPaginatorName",
+    "OwnershipTypeType",
     "SortOrderType",
     "MarketplaceCatalogServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
     "RegionName",
 )
 
 
 ChangeStatusType = Literal["APPLYING", "CANCELLED", "FAILED", "PREPARING", "SUCCEEDED"]
 FailureCodeType = Literal["CLIENT_ERROR", "SERVER_FAULT"]
+ListChangeSetsPaginatorName = Literal["list_change_sets"]
+ListEntitiesPaginatorName = Literal["list_entities"]
+OwnershipTypeType = Literal["SELF", "SHARED"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
 MarketplaceCatalogServiceName = Literal["marketplace-catalog"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -92,14 +99,15 @@
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
@@ -178,14 +186,15 @@
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
@@ -196,14 +205,15 @@
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
@@ -239,14 +249,15 @@
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
@@ -265,16 +276,19 @@
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
@@ -358,15 +372,17 @@
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
@@ -384,8 +400,9 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_change_sets", "list_entities"]
 RegionName = Literal["us-east-1"]
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/literals.pyi` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/literals.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -17,23 +17,30 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ChangeStatusType",
     "FailureCodeType",
+    "ListChangeSetsPaginatorName",
+    "ListEntitiesPaginatorName",
+    "OwnershipTypeType",
     "SortOrderType",
     "MarketplaceCatalogServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
     "RegionName",
 )
 
 ChangeStatusType = Literal["APPLYING", "CANCELLED", "FAILED", "PREPARING", "SUCCEEDED"]
 FailureCodeType = Literal["CLIENT_ERROR", "SERVER_FAULT"]
+ListChangeSetsPaginatorName = Literal["list_change_sets"]
+ListEntitiesPaginatorName = Literal["list_entities"]
+OwnershipTypeType = Literal["SELF", "SHARED"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
 MarketplaceCatalogServiceName = Literal["marketplace-catalog"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -90,14 +97,15 @@
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
@@ -176,14 +184,15 @@
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
@@ -194,14 +203,15 @@
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
@@ -237,14 +247,15 @@
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
@@ -263,16 +274,19 @@
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
@@ -356,15 +370,17 @@
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
@@ -382,8 +398,9 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_change_sets", "list_entities"]
 RegionName = Literal["us-east-1"]
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/type_defs.py` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/type_defs.py`

 * *Files 15% similar despite different names*

```diff
@@ -10,67 +10,72 @@
 
     data: CancelChangeSetRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Sequence
 
-from .literals import ChangeStatusType, FailureCodeType, SortOrderType
+from .literals import ChangeStatusType, FailureCodeType, OwnershipTypeType, SortOrderType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelChangeSetRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelChangeSetResponseTypeDef",
     "ChangeSetSummaryListItemTypeDef",
     "EntityTypeDef",
     "ErrorDetailTypeDef",
     "TagTypeDef",
+    "DeleteResourcePolicyRequestRequestTypeDef",
     "DescribeChangeSetRequestRequestTypeDef",
     "DescribeEntityRequestRequestTypeDef",
+    "DescribeEntityResponseTypeDef",
     "EntitySummaryTypeDef",
     "FilterTypeDef",
+    "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "SortTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "CancelChangeSetResponseTypeDef",
-    "DescribeEntityResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartChangeSetResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "ListChangeSetsResponseTypeDef",
     "ChangeSummaryTypeDef",
     "ChangeTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ListEntitiesResponseTypeDef",
+    "ListChangeSetsRequestListChangeSetsPaginateTypeDef",
     "ListChangeSetsRequestRequestTypeDef",
+    "ListEntitiesRequestListEntitiesPaginateTypeDef",
     "ListEntitiesRequestRequestTypeDef",
     "DescribeChangeSetResponseTypeDef",
     "StartChangeSetRequestRequestTypeDef",
 )
 
 CancelChangeSetRequestRequestTypeDef = TypedDict(
     "CancelChangeSetRequestRequestTypeDef",
     {
         "Catalog": str,
         "ChangeSetId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelChangeSetResponseTypeDef = TypedDict(
+    "CancelChangeSetResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ChangeSetId": str,
+        "ChangeSetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeSetSummaryListItemTypeDef = TypedDict(
     "ChangeSetSummaryListItemTypeDef",
     {
         "ChangeSetId": str,
@@ -117,14 +122,21 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
+    "DeleteResourcePolicyRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+
 DescribeChangeSetRequestRequestTypeDef = TypedDict(
     "DescribeChangeSetRequestRequestTypeDef",
     {
         "Catalog": str,
         "ChangeSetId": str,
     },
 )
@@ -133,14 +145,26 @@
     "DescribeEntityRequestRequestTypeDef",
     {
         "Catalog": str,
         "EntityId": str,
     },
 )
 
+DescribeEntityResponseTypeDef = TypedDict(
+    "DescribeEntityResponseTypeDef",
+    {
+        "EntityType": str,
+        "EntityIdentifier": str,
+        "EntityArn": str,
+        "LastModifiedDate": str,
+        "Details": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EntitySummaryTypeDef = TypedDict(
     "EntitySummaryTypeDef",
     {
         "Name": str,
         "EntityType": str,
         "EntityId": str,
         "EntityArn": str,
@@ -155,14 +179,29 @@
     {
         "Name": str,
         "ValueList": Sequence[str],
     },
     total=False,
 )
 
+GetResourcePolicyRequestRequestTypeDef = TypedDict(
+    "GetResourcePolicyRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SortTypeDef = TypedDict(
     "SortTypeDef",
     {
         "SortBy": str,
         "SortOrder": SortOrderType,
     },
     total=False,
@@ -171,58 +210,66 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-CancelChangeSetResponseTypeDef = TypedDict(
-    "CancelChangeSetResponseTypeDef",
+PutResourcePolicyRequestRequestTypeDef = TypedDict(
+    "PutResourcePolicyRequestRequestTypeDef",
     {
-        "ChangeSetId": str,
-        "ChangeSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Policy": str,
     },
 )
 
-DescribeEntityResponseTypeDef = TypedDict(
-    "DescribeEntityResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "EntityType": str,
-        "EntityIdentifier": str,
-        "EntityArn": str,
-        "LastModifiedDate": str,
-        "Details": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 StartChangeSetResponseTypeDef = TypedDict(
     "StartChangeSetResponseTypeDef",
     {
         "ChangeSetId": str,
         "ChangeSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 ListChangeSetsResponseTypeDef = TypedDict(
     "ListChangeSetsResponseTypeDef",
     {
         "ChangeSetSummaryList": List[ChangeSetSummaryListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeSummaryTypeDef = TypedDict(
     "ChangeSummaryTypeDef",
     {
         "ChangeType": str,
@@ -257,15 +304,15 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -274,18 +321,42 @@
 )
 
 ListEntitiesResponseTypeDef = TypedDict(
     "ListEntitiesResponseTypeDef",
     {
         "EntitySummaryList": List[EntitySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListChangeSetsRequestListChangeSetsPaginateTypeDef = TypedDict(
+    "_RequiredListChangeSetsRequestListChangeSetsPaginateTypeDef",
+    {
+        "Catalog": str,
+    },
+)
+_OptionalListChangeSetsRequestListChangeSetsPaginateTypeDef = TypedDict(
+    "_OptionalListChangeSetsRequestListChangeSetsPaginateTypeDef",
+    {
+        "FilterList": Sequence[FilterTypeDef],
+        "Sort": SortTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
+
+class ListChangeSetsRequestListChangeSetsPaginateTypeDef(
+    _RequiredListChangeSetsRequestListChangeSetsPaginateTypeDef,
+    _OptionalListChangeSetsRequestListChangeSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListChangeSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListChangeSetsRequestRequestTypeDef",
     {
         "Catalog": str,
     },
 )
 _OptionalListChangeSetsRequestRequestTypeDef = TypedDict(
@@ -302,28 +373,55 @@
 
 class ListChangeSetsRequestRequestTypeDef(
     _RequiredListChangeSetsRequestRequestTypeDef, _OptionalListChangeSetsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListEntitiesRequestListEntitiesPaginateTypeDef = TypedDict(
+    "_RequiredListEntitiesRequestListEntitiesPaginateTypeDef",
+    {
+        "Catalog": str,
+        "EntityType": str,
+    },
+)
+_OptionalListEntitiesRequestListEntitiesPaginateTypeDef = TypedDict(
+    "_OptionalListEntitiesRequestListEntitiesPaginateTypeDef",
+    {
+        "FilterList": Sequence[FilterTypeDef],
+        "Sort": SortTypeDef,
+        "OwnershipType": OwnershipTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEntitiesRequestListEntitiesPaginateTypeDef(
+    _RequiredListEntitiesRequestListEntitiesPaginateTypeDef,
+    _OptionalListEntitiesRequestListEntitiesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEntitiesRequestRequestTypeDef = TypedDict(
     "_RequiredListEntitiesRequestRequestTypeDef",
     {
         "Catalog": str,
         "EntityType": str,
     },
 )
 _OptionalListEntitiesRequestRequestTypeDef = TypedDict(
     "_OptionalListEntitiesRequestRequestTypeDef",
     {
         "FilterList": Sequence[FilterTypeDef],
         "Sort": SortTypeDef,
         "NextToken": str,
         "MaxResults": int,
+        "OwnershipType": OwnershipTypeType,
     },
     total=False,
 )
 
 
 class ListEntitiesRequestRequestTypeDef(
     _RequiredListEntitiesRequestRequestTypeDef, _OptionalListEntitiesRequestRequestTypeDef
@@ -339,15 +437,15 @@
         "ChangeSetName": str,
         "StartTime": str,
         "EndTime": str,
         "Status": ChangeStatusType,
         "FailureCode": FailureCodeType,
         "FailureDescription": str,
         "ChangeSet": List[ChangeSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartChangeSetRequestRequestTypeDef = TypedDict(
     "_RequiredStartChangeSetRequestRequestTypeDef",
     {
         "Catalog": str,
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog/type_defs.pyi` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog/type_defs.pyi`

 * *Files 15% similar despite different names*

```diff
@@ -10,66 +10,71 @@
 
     data: CancelChangeSetRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Sequence
 
-from .literals import ChangeStatusType, FailureCodeType, SortOrderType
+from .literals import ChangeStatusType, FailureCodeType, OwnershipTypeType, SortOrderType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelChangeSetRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelChangeSetResponseTypeDef",
     "ChangeSetSummaryListItemTypeDef",
     "EntityTypeDef",
     "ErrorDetailTypeDef",
     "TagTypeDef",
+    "DeleteResourcePolicyRequestRequestTypeDef",
     "DescribeChangeSetRequestRequestTypeDef",
     "DescribeEntityRequestRequestTypeDef",
+    "DescribeEntityResponseTypeDef",
     "EntitySummaryTypeDef",
     "FilterTypeDef",
+    "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "SortTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "CancelChangeSetResponseTypeDef",
-    "DescribeEntityResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutResourcePolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartChangeSetResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "ListChangeSetsResponseTypeDef",
     "ChangeSummaryTypeDef",
     "ChangeTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ListEntitiesResponseTypeDef",
+    "ListChangeSetsRequestListChangeSetsPaginateTypeDef",
     "ListChangeSetsRequestRequestTypeDef",
+    "ListEntitiesRequestListEntitiesPaginateTypeDef",
     "ListEntitiesRequestRequestTypeDef",
     "DescribeChangeSetResponseTypeDef",
     "StartChangeSetRequestRequestTypeDef",
 )
 
 CancelChangeSetRequestRequestTypeDef = TypedDict(
     "CancelChangeSetRequestRequestTypeDef",
     {
         "Catalog": str,
         "ChangeSetId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelChangeSetResponseTypeDef = TypedDict(
+    "CancelChangeSetResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ChangeSetId": str,
+        "ChangeSetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeSetSummaryListItemTypeDef = TypedDict(
     "ChangeSetSummaryListItemTypeDef",
     {
         "ChangeSetId": str,
@@ -114,14 +119,21 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
+    "DeleteResourcePolicyRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+
 DescribeChangeSetRequestRequestTypeDef = TypedDict(
     "DescribeChangeSetRequestRequestTypeDef",
     {
         "Catalog": str,
         "ChangeSetId": str,
     },
 )
@@ -130,14 +142,26 @@
     "DescribeEntityRequestRequestTypeDef",
     {
         "Catalog": str,
         "EntityId": str,
     },
 )
 
+DescribeEntityResponseTypeDef = TypedDict(
+    "DescribeEntityResponseTypeDef",
+    {
+        "EntityType": str,
+        "EntityIdentifier": str,
+        "EntityArn": str,
+        "LastModifiedDate": str,
+        "Details": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EntitySummaryTypeDef = TypedDict(
     "EntitySummaryTypeDef",
     {
         "Name": str,
         "EntityType": str,
         "EntityId": str,
         "EntityArn": str,
@@ -152,14 +176,29 @@
     {
         "Name": str,
         "ValueList": Sequence[str],
     },
     total=False,
 )
 
+GetResourcePolicyRequestRequestTypeDef = TypedDict(
+    "GetResourcePolicyRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SortTypeDef = TypedDict(
     "SortTypeDef",
     {
         "SortBy": str,
         "SortOrder": SortOrderType,
     },
     total=False,
@@ -168,58 +207,66 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-CancelChangeSetResponseTypeDef = TypedDict(
-    "CancelChangeSetResponseTypeDef",
+PutResourcePolicyRequestRequestTypeDef = TypedDict(
+    "PutResourcePolicyRequestRequestTypeDef",
     {
-        "ChangeSetId": str,
-        "ChangeSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Policy": str,
     },
 )
 
-DescribeEntityResponseTypeDef = TypedDict(
-    "DescribeEntityResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "EntityType": str,
-        "EntityIdentifier": str,
-        "EntityArn": str,
-        "LastModifiedDate": str,
-        "Details": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 StartChangeSetResponseTypeDef = TypedDict(
     "StartChangeSetResponseTypeDef",
     {
         "ChangeSetId": str,
         "ChangeSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 ListChangeSetsResponseTypeDef = TypedDict(
     "ListChangeSetsResponseTypeDef",
     {
         "ChangeSetSummaryList": List[ChangeSetSummaryListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeSummaryTypeDef = TypedDict(
     "ChangeSummaryTypeDef",
     {
         "ChangeType": str,
@@ -252,15 +299,15 @@
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -269,17 +316,39 @@
 )
 
 ListEntitiesResponseTypeDef = TypedDict(
     "ListEntitiesResponseTypeDef",
     {
         "EntitySummaryList": List[EntitySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListChangeSetsRequestListChangeSetsPaginateTypeDef = TypedDict(
+    "_RequiredListChangeSetsRequestListChangeSetsPaginateTypeDef",
+    {
+        "Catalog": str,
     },
 )
+_OptionalListChangeSetsRequestListChangeSetsPaginateTypeDef = TypedDict(
+    "_OptionalListChangeSetsRequestListChangeSetsPaginateTypeDef",
+    {
+        "FilterList": Sequence[FilterTypeDef],
+        "Sort": SortTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListChangeSetsRequestListChangeSetsPaginateTypeDef(
+    _RequiredListChangeSetsRequestListChangeSetsPaginateTypeDef,
+    _OptionalListChangeSetsRequestListChangeSetsPaginateTypeDef,
+):
+    pass
 
 _RequiredListChangeSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListChangeSetsRequestRequestTypeDef",
     {
         "Catalog": str,
     },
 )
@@ -295,28 +364,53 @@
 )
 
 class ListChangeSetsRequestRequestTypeDef(
     _RequiredListChangeSetsRequestRequestTypeDef, _OptionalListChangeSetsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListEntitiesRequestListEntitiesPaginateTypeDef = TypedDict(
+    "_RequiredListEntitiesRequestListEntitiesPaginateTypeDef",
+    {
+        "Catalog": str,
+        "EntityType": str,
+    },
+)
+_OptionalListEntitiesRequestListEntitiesPaginateTypeDef = TypedDict(
+    "_OptionalListEntitiesRequestListEntitiesPaginateTypeDef",
+    {
+        "FilterList": Sequence[FilterTypeDef],
+        "Sort": SortTypeDef,
+        "OwnershipType": OwnershipTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEntitiesRequestListEntitiesPaginateTypeDef(
+    _RequiredListEntitiesRequestListEntitiesPaginateTypeDef,
+    _OptionalListEntitiesRequestListEntitiesPaginateTypeDef,
+):
+    pass
+
 _RequiredListEntitiesRequestRequestTypeDef = TypedDict(
     "_RequiredListEntitiesRequestRequestTypeDef",
     {
         "Catalog": str,
         "EntityType": str,
     },
 )
 _OptionalListEntitiesRequestRequestTypeDef = TypedDict(
     "_OptionalListEntitiesRequestRequestTypeDef",
     {
         "FilterList": Sequence[FilterTypeDef],
         "Sort": SortTypeDef,
         "NextToken": str,
         "MaxResults": int,
+        "OwnershipType": OwnershipTypeType,
     },
     total=False,
 )
 
 class ListEntitiesRequestRequestTypeDef(
     _RequiredListEntitiesRequestRequestTypeDef, _OptionalListEntitiesRequestRequestTypeDef
 ):
@@ -330,15 +424,15 @@
         "ChangeSetName": str,
         "StartTime": str,
         "EndTime": str,
         "Status": ChangeStatusType,
         "FailureCode": FailureCodeType,
         "FailureDescription": str,
         "ChangeSet": List[ChangeSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartChangeSetRequestRequestTypeDef = TypedDict(
     "_RequiredStartChangeSetRequestRequestTypeDef",
     {
         "Catalog": str,
```

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/PKG-INFO` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-marketplace-catalog
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceCatalog 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceCatalog 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-marketplace-catalog"></a>
 
 # types-aiobotocore-marketplace-catalog
 
 [![PyPI - types-aiobotocore-marketplace-catalog](https://img.shields.io/pypi/v/types-aiobotocore-marketplace-catalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-catalog)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplace-catalog.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-catalog)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplace-catalog?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplace-catalog)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceCatalog 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
+[aiobotocore.MarketplaceCatalog 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-catalog.html#MarketplaceCatalog)
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
 [types-aiobotocore-marketplace-catalog docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_catalog/).
 
 See how it helps to find and fix potential bugs:
 
@@ -72,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -260,29 +261,59 @@
 
 session = get_session()
 async with session.create_client("marketplace-catalog") as client:
     client: MarketplaceCatalogClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_marketplace_catalog.paginator` module contains type
+annotations for all paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_marketplace_catalog import MarketplaceCatalogClient
+from types_aiobotocore_marketplace_catalog.paginator import (
+    ListChangeSetsPaginator,
+    ListEntitiesPaginator,
+)
+
+session = get_session()
+async with session.create_client("marketplace-catalog") as client:
+    client: MarketplaceCatalogClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_change_sets_paginator: ListChangeSetsPaginator = client.get_paginator("list_change_sets")
+    list_entities_paginator: ListEntitiesPaginator = client.get_paginator("list_entities")
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_marketplace_catalog.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_marketplace_catalog.literals import (
     ChangeStatusType,
     FailureCodeType,
+    ListChangeSetsPaginatorName,
+    ListEntitiesPaginatorName,
+    OwnershipTypeType,
     SortOrderType,
     MarketplaceCatalogServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
 def check_value(value: ChangeStatusType) -> bool:
     ...
 ```
@@ -293,36 +324,43 @@
 
 `types_aiobotocore_marketplace_catalog.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_marketplace_catalog.type_defs import (
     CancelChangeSetRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelChangeSetResponseTypeDef,
     ChangeSetSummaryListItemTypeDef,
     EntityTypeDef,
     ErrorDetailTypeDef,
     TagTypeDef,
+    DeleteResourcePolicyRequestRequestTypeDef,
     DescribeChangeSetRequestRequestTypeDef,
     DescribeEntityRequestRequestTypeDef,
+    DescribeEntityResponseTypeDef,
     EntitySummaryTypeDef,
     FilterTypeDef,
+    GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     SortTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    CancelChangeSetResponseTypeDef,
-    DescribeEntityResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutResourcePolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartChangeSetResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     ListChangeSetsResponseTypeDef,
     ChangeSummaryTypeDef,
     ChangeTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListEntitiesResponseTypeDef,
+    ListChangeSetsRequestListChangeSetsPaginateTypeDef,
     ListChangeSetsRequestRequestTypeDef,
+    ListEntitiesRequestListEntitiesPaginateTypeDef,
     ListEntitiesRequestRequestTypeDef,
     DescribeChangeSetResponseTypeDef,
     StartChangeSetRequestRequestTypeDef,
 )
 
 
 def get_structure() -> CancelChangeSetRequestRequestTypeDef:
@@ -332,43 +370,43 @@
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

### Comparing `types-aiobotocore-marketplace-catalog-2.5.0.post1/types_aiobotocore_marketplace_catalog.egg-info/SOURCES.txt` & `types-aiobotocore-marketplace-catalog-2.5.1/types_aiobotocore_marketplace_catalog.egg-info/SOURCES.txt`

 * *Files 11% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 types_aiobotocore_marketplace_catalog/__init__.py
 types_aiobotocore_marketplace_catalog/__init__.pyi
 types_aiobotocore_marketplace_catalog/__main__.py
 types_aiobotocore_marketplace_catalog/client.py
 types_aiobotocore_marketplace_catalog/client.pyi
 types_aiobotocore_marketplace_catalog/literals.py
 types_aiobotocore_marketplace_catalog/literals.pyi
+types_aiobotocore_marketplace_catalog/paginator.py
+types_aiobotocore_marketplace_catalog/paginator.pyi
 types_aiobotocore_marketplace_catalog/py.typed
 types_aiobotocore_marketplace_catalog/type_defs.py
 types_aiobotocore_marketplace_catalog/type_defs.pyi
 types_aiobotocore_marketplace_catalog/version.py
 types_aiobotocore_marketplace_catalog.egg-info/PKG-INFO
 types_aiobotocore_marketplace_catalog.egg-info/SOURCES.txt
 types_aiobotocore_marketplace_catalog.egg-info/dependency_links.txt
```

