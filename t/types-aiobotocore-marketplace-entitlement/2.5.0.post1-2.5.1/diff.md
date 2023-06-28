# Comparing `tmp/types-aiobotocore-marketplace-entitlement-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-marketplace-entitlement-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-marketplace-entitlement-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-marketplace-entitlement-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1.tar` & `types-aiobotocore-marketplace-entitlement-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.491414 types-aiobotocore-marketplace-entitlement-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14020 2023-03-11 12:26:58.491414 types-aiobotocore-marketplace-entitlement-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12379 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.491414 types-aiobotocore-marketplace-entitlement-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2245 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.487414 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/
--rw-r--r--   0 runner    (1001) docker     (123)      811 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      810 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1019 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6002 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5991 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7774 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7772 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2527 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2523 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     3291 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     3286 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:07.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.491414 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14020 2023-03-11 12:26:58.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-03-11 12:26:58.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-03-11 12:26:58.000000 types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.502174 types-aiobotocore-marketplace-entitlement-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14028 2023-06-28 01:43:49.502174 types-aiobotocore-marketplace-entitlement-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12393 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.502174 types-aiobotocore-marketplace-entitlement-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2239 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.494174 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/
+-rw-r--r--   0 runner    (1001) docker     (123)      811 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      810 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1007 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6002 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5991 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7983 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7981 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2409 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2406 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     3295 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3290 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:50.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.502174 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14028 2023-06-28 01:43:49.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-06-28 01:43:49.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 01:43:49.000000 types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/LICENSE` & `types-aiobotocore-marketplace-entitlement-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/PKG-INFO` & `types-aiobotocore-marketplace-entitlement-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-marketplace-entitlement
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-marketplace-entitlement"></a>
 
 # types-aiobotocore-marketplace-entitlement
 
 [![PyPI - types-aiobotocore-marketplace-entitlement](https://img.shields.io/pypi/v/types-aiobotocore-marketplace-entitlement.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-entitlement)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplace-entitlement.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-entitlement)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplace-entitlement?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplace-entitlement)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceEntitlementService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService)
+[aiobotocore.MarketplaceEntitlementService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService)
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
 [types-aiobotocore-marketplace-entitlement docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,19 +317,19 @@
 `types_aiobotocore_marketplace_entitlement.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_marketplace_entitlement.type_defs import (
     EntitlementValueTypeDef,
-    PaginatorConfigTypeDef,
+    GetEntitlementsRequestGetEntitlementsPaginateTypeDef,
     GetEntitlementsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ResponseMetadataTypeDef,
     EntitlementTypeDef,
-    GetEntitlementsRequestGetEntitlementsPaginateTypeDef,
     GetEntitlementsResultTypeDef,
 )
 
 
 def get_structure() -> EntitlementValueTypeDef:
     return {...}
 ```
@@ -337,43 +337,43 @@
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/README.md` & `types-aiobotocore-marketplace-entitlement-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-marketplace-entitlement"></a>
 
 # types-aiobotocore-marketplace-entitlement
 
 [![PyPI - types-aiobotocore-marketplace-entitlement](https://img.shields.io/pypi/v/types-aiobotocore-marketplace-entitlement.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-entitlement)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplace-entitlement.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-entitlement)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplace-entitlement?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplace-entitlement)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceEntitlementService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService)
+[aiobotocore.MarketplaceEntitlementService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService)
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
 [types-aiobotocore-marketplace-entitlement docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/).
 
 See how it helps to find and fix potential bugs:
 
@@ -284,19 +284,19 @@
 `types_aiobotocore_marketplace_entitlement.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_marketplace_entitlement.type_defs import (
     EntitlementValueTypeDef,
-    PaginatorConfigTypeDef,
+    GetEntitlementsRequestGetEntitlementsPaginateTypeDef,
     GetEntitlementsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ResponseMetadataTypeDef,
     EntitlementTypeDef,
-    GetEntitlementsRequestGetEntitlementsPaginateTypeDef,
     GetEntitlementsResultTypeDef,
 )
 
 
 def get_structure() -> EntitlementValueTypeDef:
     return {...}
 ```
@@ -304,43 +304,43 @@
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/setup.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-marketplace-entitlement.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-marketplace-entitlement",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_marketplace_entitlement"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.0 service generated"
-        " with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.1 service generated"
+        " with mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/",
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/__init__.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/__init__.pyi` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/__main__.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService\nOther"
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/client.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/client.pyi` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/literals.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -91,14 +91,15 @@
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
@@ -177,14 +178,15 @@
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
@@ -195,14 +197,15 @@
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
@@ -238,14 +241,15 @@
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
@@ -264,16 +268,19 @@
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
@@ -357,15 +364,17 @@
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/literals.pyi` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -89,14 +89,15 @@
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
@@ -175,14 +176,15 @@
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
@@ -193,14 +195,15 @@
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
@@ -236,14 +239,15 @@
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
@@ -262,16 +266,19 @@
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
@@ -355,15 +362,17 @@
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/paginator.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,29 +16,22 @@
     session = get_session()
     with session.create_client("marketplace-entitlement") as client:
         client: MarketplaceEntitlementServiceClient
 
         get_entitlements_paginator: GetEntitlementsPaginator = client.get_paginator("get_entitlements")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import GetEntitlementFilterNameType
 from .type_defs import GetEntitlementsResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("GetEntitlementsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -55,13 +48,13 @@
     """
 
     def paginate(
         self,
         *,
         ProductCode: str,
         Filter: Mapping[GetEntitlementFilterNameType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetEntitlementsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService.Paginator.GetEntitlements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/paginators/#getentitlementspaginator)
         """
```

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/paginator.pyi` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,28 +16,22 @@
     session = get_session()
     with session.create_client("marketplace-entitlement") as client:
         client: MarketplaceEntitlementServiceClient
 
         get_entitlements_paginator: GetEntitlementsPaginator = client.get_paginator("get_entitlements")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import GetEntitlementFilterNameType
 from .type_defs import GetEntitlementsResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("GetEntitlementsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -51,13 +45,13 @@
     """
 
     def paginate(
         self,
         *,
         ProductCode: str,
         Filter: Mapping[GetEntitlementFilterNameType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetEntitlementsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService.Paginator.GetEntitlements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/paginators/#getentitlementspaginator)
         """
```

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/type_defs.py` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -21,43 +21,56 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "EntitlementValueTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetEntitlementsRequestGetEntitlementsPaginateTypeDef",
     "GetEntitlementsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ResponseMetadataTypeDef",
     "EntitlementTypeDef",
-    "GetEntitlementsRequestGetEntitlementsPaginateTypeDef",
     "GetEntitlementsResultTypeDef",
 )
 
 EntitlementValueTypeDef = TypedDict(
     "EntitlementValueTypeDef",
     {
         "IntegerValue": int,
         "DoubleValue": float,
         "BooleanValue": bool,
         "StringValue": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
+    "_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProductCode": str,
+    },
+)
+_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
+    "_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
+    {
+        "Filter": Mapping[GetEntitlementFilterNameType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetEntitlementsRequestGetEntitlementsPaginateTypeDef(
+    _RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
+    _OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetEntitlementsRequestRequestTypeDef = TypedDict(
     "_RequiredGetEntitlementsRequestRequestTypeDef",
     {
         "ProductCode": str,
     },
 )
 _OptionalGetEntitlementsRequestRequestTypeDef = TypedDict(
@@ -73,14 +86,24 @@
 
 class GetEntitlementsRequestRequestTypeDef(
     _RequiredGetEntitlementsRequestRequestTypeDef, _OptionalGetEntitlementsRequestRequestTypeDef
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
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -96,38 +119,15 @@
         "CustomerIdentifier": str,
         "Value": EntitlementValueTypeDef,
         "ExpirationDate": datetime,
     },
     total=False,
 )
 
-_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
-    "_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
-    {
-        "ProductCode": str,
-    },
-)
-_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
-    "_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
-    {
-        "Filter": Mapping[GetEntitlementFilterNameType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetEntitlementsRequestGetEntitlementsPaginateTypeDef(
-    _RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
-    _OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
-):
-    pass
-
-
 GetEntitlementsResultTypeDef = TypedDict(
     "GetEntitlementsResultTypeDef",
     {
         "Entitlements": List[EntitlementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement/type_defs.pyi` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement/type_defs.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -20,43 +20,54 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "EntitlementValueTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetEntitlementsRequestGetEntitlementsPaginateTypeDef",
     "GetEntitlementsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ResponseMetadataTypeDef",
     "EntitlementTypeDef",
-    "GetEntitlementsRequestGetEntitlementsPaginateTypeDef",
     "GetEntitlementsResultTypeDef",
 )
 
 EntitlementValueTypeDef = TypedDict(
     "EntitlementValueTypeDef",
     {
         "IntegerValue": int,
         "DoubleValue": float,
         "BooleanValue": bool,
         "StringValue": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
+    "_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProductCode": str,
+    },
+)
+_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
+    "_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
+    {
+        "Filter": Mapping[GetEntitlementFilterNameType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetEntitlementsRequestGetEntitlementsPaginateTypeDef(
+    _RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
+    _OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetEntitlementsRequestRequestTypeDef = TypedDict(
     "_RequiredGetEntitlementsRequestRequestTypeDef",
     {
         "ProductCode": str,
     },
 )
 _OptionalGetEntitlementsRequestRequestTypeDef = TypedDict(
@@ -70,14 +81,24 @@
 )
 
 class GetEntitlementsRequestRequestTypeDef(
     _RequiredGetEntitlementsRequestRequestTypeDef, _OptionalGetEntitlementsRequestRequestTypeDef
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
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -93,36 +114,15 @@
         "CustomerIdentifier": str,
         "Value": EntitlementValueTypeDef,
         "ExpirationDate": datetime,
     },
     total=False,
 )
 
-_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
-    "_RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
-    {
-        "ProductCode": str,
-    },
-)
-_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef = TypedDict(
-    "_OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef",
-    {
-        "Filter": Mapping[GetEntitlementFilterNameType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetEntitlementsRequestGetEntitlementsPaginateTypeDef(
-    _RequiredGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
-    _OptionalGetEntitlementsRequestGetEntitlementsPaginateTypeDef,
-):
-    pass
-
 GetEntitlementsResultTypeDef = TypedDict(
     "GetEntitlementsResultTypeDef",
     {
         "Entitlements": List[EntitlementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/PKG-INFO` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-marketplace-entitlement
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceEntitlementService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-marketplace-entitlement"></a>
 
 # types-aiobotocore-marketplace-entitlement
 
 [![PyPI - types-aiobotocore-marketplace-entitlement](https://img.shields.io/pypi/v/types-aiobotocore-marketplace-entitlement.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-entitlement)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplace-entitlement.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplace-entitlement)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplace-entitlement?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplace-entitlement)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceEntitlementService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService)
+[aiobotocore.MarketplaceEntitlementService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplace-entitlement.html#MarketplaceEntitlementService)
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
 [types-aiobotocore-marketplace-entitlement docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplace_entitlement/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,19 +317,19 @@
 `types_aiobotocore_marketplace_entitlement.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_marketplace_entitlement.type_defs import (
     EntitlementValueTypeDef,
-    PaginatorConfigTypeDef,
+    GetEntitlementsRequestGetEntitlementsPaginateTypeDef,
     GetEntitlementsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ResponseMetadataTypeDef,
     EntitlementTypeDef,
-    GetEntitlementsRequestGetEntitlementsPaginateTypeDef,
     GetEntitlementsResultTypeDef,
 )
 
 
 def get_structure() -> EntitlementValueTypeDef:
     return {...}
 ```
@@ -337,43 +337,43 @@
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

### Comparing `types-aiobotocore-marketplace-entitlement-2.5.0.post1/types_aiobotocore_marketplace_entitlement.egg-info/SOURCES.txt` & `types-aiobotocore-marketplace-entitlement-2.5.1/types_aiobotocore_marketplace_entitlement.egg-info/SOURCES.txt`

 * *Files identical despite different names*

