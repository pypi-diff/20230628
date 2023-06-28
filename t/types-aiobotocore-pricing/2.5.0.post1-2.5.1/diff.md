# Comparing `tmp/types-aiobotocore-pricing-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-pricing-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-pricing-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-pricing-2.5.1.tar", last modified: Wed Jun 28 01:44:00 2023, max compression
```

## Comparing `types-aiobotocore-pricing-2.5.0.post1.tar` & `types-aiobotocore-pricing-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.507512 types-aiobotocore-pricing-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13719 2023-03-11 12:27:08.507512 types-aiobotocore-pricing-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12148 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.507512 types-aiobotocore-pricing-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.507512 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/
--rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7642 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7627 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7862 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7860 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4562 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4556 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5874 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5864 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:20:05.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.507512 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13719 2023-03-11 12:27:08.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:27:08.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:27:08.000000 types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.242194 types-aiobotocore-pricing-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14112 2023-06-28 01:44:00.242194 types-aiobotocore-pricing-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12547 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:00.242194 types-aiobotocore-pricing-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.238194 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/
+-rw-r--r--   0 runner    (1001) docker     (123)     1263 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1262 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9525 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9507 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8190 2023-06-28 01:36:52.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8188 2023-06-28 01:36:52.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5707 2023-06-28 01:36:52.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5701 2023-06-28 01:36:52.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8281 2023-06-28 01:36:52.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8266 2023-06-28 01:36:52.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:51.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.242194 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14112 2023-06-28 01:44:00.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:44:00.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:00.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:44:00.000000 types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/LICENSE` & `types-aiobotocore-pricing-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-pricing-2.5.0.post1/PKG-INFO` & `types-aiobotocore-pricing-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pricing
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Pricing 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Pricing 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pricing"></a>
 
 # types-aiobotocore-pricing
 
 [![PyPI - types-aiobotocore-pricing](https://img.shields.io/pypi/v/types-aiobotocore-pricing.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pricing)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pricing.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pricing)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pricing?color=blue)](https://pypistats.org/packages/types-aiobotocore-pricing)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Pricing 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing)
+[aiobotocore.Pricing 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing)
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
 [types-aiobotocore-pricing docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/).
 
 See how it helps to find and fix potential bugs:
 
@@ -275,14 +275,15 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_pricing import PricingClient
 from types_aiobotocore_pricing.paginator import (
     DescribeServicesPaginator,
     GetAttributeValuesPaginator,
     GetProductsPaginator,
+    ListPriceListsPaginator,
 )
 
 session = get_session()
 async with session.create_client("pricing") as client:
     client: PricingClient
 
     # Explicit type annotations are optional here
@@ -290,14 +291,15 @@
     describe_services_paginator: DescribeServicesPaginator = client.get_paginator(
         "describe_services"
     )
     get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator(
         "get_attribute_values"
     )
     get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+    list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_pricing.literals` module contains literals extracted from
@@ -305,14 +307,15 @@
 
 ```python
 from types_aiobotocore_pricing.literals import (
     DescribeServicesPaginatorName,
     FilterTypeType,
     GetAttributeValuesPaginatorName,
     GetProductsPaginatorName,
+    ListPriceListsPaginatorName,
     PricingServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -327,70 +330,76 @@
 
 `types_aiobotocore_pricing.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_pricing.type_defs import (
     AttributeValueTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeServicesRequestDescribeServicesPaginateTypeDef,
     DescribeServicesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ServiceTypeDef,
     FilterTypeDef,
-    GetAttributeValuesRequestRequestTypeDef,
-    DescribeServicesRequestDescribeServicesPaginateTypeDef,
     GetAttributeValuesRequestGetAttributeValuesPaginateTypeDef,
-    GetAttributeValuesResponseTypeDef,
+    GetAttributeValuesRequestRequestTypeDef,
+    GetPriceListFileUrlRequestRequestTypeDef,
+    GetPriceListFileUrlResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsRequestListPriceListsPaginateTypeDef,
+    ListPriceListsRequestRequestTypeDef,
+    PriceListTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    GetAttributeValuesResponseTypeDef,
     DescribeServicesResponseTypeDef,
     GetProductsRequestGetProductsPaginateTypeDef,
     GetProductsRequestRequestTypeDef,
+    ListPriceListsResponseTypeDef,
 )
 
 
 def get_structure() -> AttributeValueTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-pricing-2.5.0.post1/README.md` & `types-aiobotocore-pricing-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-pricing"></a>
 
 # types-aiobotocore-pricing
 
 [![PyPI - types-aiobotocore-pricing](https://img.shields.io/pypi/v/types-aiobotocore-pricing.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pricing)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pricing.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pricing)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pricing?color=blue)](https://pypistats.org/packages/types-aiobotocore-pricing)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Pricing 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing)
+[aiobotocore.Pricing 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing)
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
 [types-aiobotocore-pricing docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/).
 
 See how it helps to find and fix potential bugs:
 
@@ -242,14 +242,15 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_pricing import PricingClient
 from types_aiobotocore_pricing.paginator import (
     DescribeServicesPaginator,
     GetAttributeValuesPaginator,
     GetProductsPaginator,
+    ListPriceListsPaginator,
 )
 
 session = get_session()
 async with session.create_client("pricing") as client:
     client: PricingClient
 
     # Explicit type annotations are optional here
@@ -257,14 +258,15 @@
     describe_services_paginator: DescribeServicesPaginator = client.get_paginator(
         "describe_services"
     )
     get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator(
         "get_attribute_values"
     )
     get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+    list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_pricing.literals` module contains literals extracted from
@@ -272,14 +274,15 @@
 
 ```python
 from types_aiobotocore_pricing.literals import (
     DescribeServicesPaginatorName,
     FilterTypeType,
     GetAttributeValuesPaginatorName,
     GetProductsPaginatorName,
+    ListPriceListsPaginatorName,
     PricingServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -294,70 +297,76 @@
 
 `types_aiobotocore_pricing.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_pricing.type_defs import (
     AttributeValueTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeServicesRequestDescribeServicesPaginateTypeDef,
     DescribeServicesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ServiceTypeDef,
     FilterTypeDef,
-    GetAttributeValuesRequestRequestTypeDef,
-    DescribeServicesRequestDescribeServicesPaginateTypeDef,
     GetAttributeValuesRequestGetAttributeValuesPaginateTypeDef,
-    GetAttributeValuesResponseTypeDef,
+    GetAttributeValuesRequestRequestTypeDef,
+    GetPriceListFileUrlRequestRequestTypeDef,
+    GetPriceListFileUrlResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsRequestListPriceListsPaginateTypeDef,
+    ListPriceListsRequestRequestTypeDef,
+    PriceListTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    GetAttributeValuesResponseTypeDef,
     DescribeServicesResponseTypeDef,
     GetProductsRequestGetProductsPaginateTypeDef,
     GetProductsRequestRequestTypeDef,
+    ListPriceListsResponseTypeDef,
 )
 
 
 def get_structure() -> AttributeValueTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-pricing-2.5.0.post1/setup.py` & `types-aiobotocore-pricing-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-pricing.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-pricing",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_pricing"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Pricing 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Pricing 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/"
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

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/__init__.py` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/__init__.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -6,34 +6,41 @@
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_pricing import (
         Client,
         DescribeServicesPaginator,
         GetAttributeValuesPaginator,
         GetProductsPaginator,
+        ListPriceListsPaginator,
         PricingClient,
     )
 
     session = get_session()
     async with session.create_client("pricing") as client:
         client: PricingClient
         ...
 
 
     describe_services_paginator: DescribeServicesPaginator = client.get_paginator("describe_services")
     get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator("get_attribute_values")
     get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+    list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
     ```
 """
 from .client import PricingClient
-from .paginator import DescribeServicesPaginator, GetAttributeValuesPaginator, GetProductsPaginator
+from .paginator import (
+    DescribeServicesPaginator,
+    GetAttributeValuesPaginator,
+    GetProductsPaginator,
+    ListPriceListsPaginator,
+)
 
 Client = PricingClient
 
-
 __all__ = (
     "Client",
     "DescribeServicesPaginator",
     "GetAttributeValuesPaginator",
     "GetProductsPaginator",
+    "ListPriceListsPaginator",
     "PricingClient",
 )
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/__init__.pyi` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/__init__.py`

 * *Files 14% similar despite different names*

```diff
@@ -6,33 +6,42 @@
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_pricing import (
         Client,
         DescribeServicesPaginator,
         GetAttributeValuesPaginator,
         GetProductsPaginator,
+        ListPriceListsPaginator,
         PricingClient,
     )
 
     session = get_session()
     async with session.create_client("pricing") as client:
         client: PricingClient
         ...
 
 
     describe_services_paginator: DescribeServicesPaginator = client.get_paginator("describe_services")
     get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator("get_attribute_values")
     get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+    list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
     ```
 """
 from .client import PricingClient
-from .paginator import DescribeServicesPaginator, GetAttributeValuesPaginator, GetProductsPaginator
+from .paginator import (
+    DescribeServicesPaginator,
+    GetAttributeValuesPaginator,
+    GetProductsPaginator,
+    ListPriceListsPaginator,
+)
 
 Client = PricingClient
 
+
 __all__ = (
     "Client",
     "DescribeServicesPaginator",
     "GetAttributeValuesPaginator",
     "GetProductsPaginator",
+    "ListPriceListsPaginator",
     "PricingClient",
 )
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/__main__.py` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Pricing 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Pricing 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing\nOther"
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

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/client.py` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/client.py`

 * *Files 10% similar despite different names*

```diff
@@ -11,25 +11,33 @@
 
     session = get_session()
     async with session.create_client("pricing") as client:
         client: PricingClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from datetime import datetime
+from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .paginator import DescribeServicesPaginator, GetAttributeValuesPaginator, GetProductsPaginator
+from .paginator import (
+    DescribeServicesPaginator,
+    GetAttributeValuesPaginator,
+    GetProductsPaginator,
+    ListPriceListsPaginator,
+)
 from .type_defs import (
     DescribeServicesResponseTypeDef,
     FilterTypeDef,
     GetAttributeValuesResponseTypeDef,
+    GetPriceListFileUrlResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -42,14 +50,15 @@
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 
 class Exceptions:
+    AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ExpiredNextTokenException: Type[BotocoreClientError]
     InternalErrorException: Type[BotocoreClientError]
     InvalidNextTokenException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
     NotFoundException: Type[BotocoreClientError]
 
@@ -122,14 +131,24 @@
         """
         Returns a list of attribute values.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_attribute_values)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_attribute_values)
         """
 
+    async def get_price_list_file_url(
+        self, *, PriceListArn: str, FileFormat: str
+    ) -> GetPriceListFileUrlResponseTypeDef:
+        """
+        This feature is in preview release and is subject to change.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_price_list_file_url)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_price_list_file_url)
+        """
+
     async def get_products(
         self,
         *,
         ServiceCode: str,
         Filters: Sequence[FilterTypeDef] = ...,
         FormatVersion: str = ...,
         NextToken: str = ...,
@@ -138,14 +157,31 @@
         """
         Returns a list of all products that match the filter criteria.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_products)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_products)
         """
 
+    async def list_price_lists(
+        self,
+        *,
+        ServiceCode: str,
+        EffectiveDate: Union[datetime, str],
+        CurrencyCode: str,
+        RegionCode: str = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListPriceListsResponseTypeDef:
+        """
+        This feature is in preview release and is subject to change.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.list_price_lists)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#list_price_lists)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_services"]
     ) -> DescribeServicesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_paginator)
@@ -163,14 +199,21 @@
     @overload
     def get_paginator(self, operation_name: Literal["get_products"]) -> GetProductsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_paginator)
         """
 
+    @overload
+    def get_paginator(self, operation_name: Literal["list_price_lists"]) -> ListPriceListsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "PricingClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/)
         """
 
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/client.pyi` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/client.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -11,25 +11,33 @@
 
     session = get_session()
     async with session.create_client("pricing") as client:
         client: PricingClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from datetime import datetime
+from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .paginator import DescribeServicesPaginator, GetAttributeValuesPaginator, GetProductsPaginator
+from .paginator import (
+    DescribeServicesPaginator,
+    GetAttributeValuesPaginator,
+    GetProductsPaginator,
+    ListPriceListsPaginator,
+)
 from .type_defs import (
     DescribeServicesResponseTypeDef,
     FilterTypeDef,
     GetAttributeValuesResponseTypeDef,
+    GetPriceListFileUrlResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -39,14 +47,15 @@
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
+    AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ExpiredNextTokenException: Type[BotocoreClientError]
     InternalErrorException: Type[BotocoreClientError]
     InvalidNextTokenException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
     NotFoundException: Type[BotocoreClientError]
 
@@ -112,14 +121,23 @@
     ) -> GetAttributeValuesResponseTypeDef:
         """
         Returns a list of attribute values.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_attribute_values)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_attribute_values)
         """
+    async def get_price_list_file_url(
+        self, *, PriceListArn: str, FileFormat: str
+    ) -> GetPriceListFileUrlResponseTypeDef:
+        """
+        This feature is in preview release and is subject to change.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_price_list_file_url)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_price_list_file_url)
+        """
     async def get_products(
         self,
         *,
         ServiceCode: str,
         Filters: Sequence[FilterTypeDef] = ...,
         FormatVersion: str = ...,
         NextToken: str = ...,
@@ -127,14 +145,30 @@
     ) -> GetProductsResponseTypeDef:
         """
         Returns a list of all products that match the filter criteria.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_products)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_products)
         """
+    async def list_price_lists(
+        self,
+        *,
+        ServiceCode: str,
+        EffectiveDate: Union[datetime, str],
+        CurrencyCode: str,
+        RegionCode: str = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListPriceListsResponseTypeDef:
+        """
+        This feature is in preview release and is subject to change.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.list_price_lists)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#list_price_lists)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_services"]
     ) -> DescribeServicesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_paginator)
@@ -149,14 +183,20 @@
         """
     @overload
     def get_paginator(self, operation_name: Literal["get_products"]) -> GetProductsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_paginator)
         """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_price_lists"]) -> ListPriceListsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/#get_paginator)
+        """
     async def __aenter__(self) -> "PricingClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/client/)
         """
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/literals.py` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/literals.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -14,32 +14,32 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DescribeServicesPaginatorName",
     "FilterTypeType",
     "GetAttributeValuesPaginatorName",
     "GetProductsPaginatorName",
+    "ListPriceListsPaginatorName",
     "PricingServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 DescribeServicesPaginatorName = Literal["describe_services"]
 FilterTypeType = Literal["TERM_MATCH"]
 GetAttributeValuesPaginatorName = Literal["get_attribute_values"]
 GetProductsPaginatorName = Literal["get_products"]
+ListPriceListsPaginatorName = Literal["list_price_lists"]
 PricingServiceName = Literal["pricing"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
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
@@ -387,9 +396,11 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-PaginatorName = Literal["describe_services", "get_attribute_values", "get_products"]
+PaginatorName = Literal[
+    "describe_services", "get_attribute_values", "get_products", "list_price_lists"
+]
 RegionName = Literal["ap-south-1", "us-east-1"]
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/literals.pyi` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,30 +14,34 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DescribeServicesPaginatorName",
     "FilterTypeType",
     "GetAttributeValuesPaginatorName",
     "GetProductsPaginatorName",
+    "ListPriceListsPaginatorName",
     "PricingServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 DescribeServicesPaginatorName = Literal["describe_services"]
 FilterTypeType = Literal["TERM_MATCH"]
 GetAttributeValuesPaginatorName = Literal["get_attribute_values"]
 GetProductsPaginatorName = Literal["get_products"]
+ListPriceListsPaginatorName = Literal["list_price_lists"]
 PricingServiceName = Literal["pricing"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -93,14 +97,15 @@
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
@@ -179,14 +184,15 @@
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
@@ -197,14 +203,15 @@
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
@@ -240,14 +247,15 @@
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
@@ -266,16 +274,19 @@
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
@@ -359,15 +370,17 @@
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
@@ -385,9 +398,11 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-PaginatorName = Literal["describe_services", "get_attribute_values", "get_products"]
+PaginatorName = Literal[
+    "describe_services", "get_attribute_values", "get_products", "list_price_lists"
+]
 RegionName = Literal["ap-south-1", "us-east-1"]
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/paginator.py` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/paginator.py`

 * *Files 18% similar despite different names*

```diff
@@ -9,46 +9,48 @@
     from aiobotocore.session import get_session
 
     from types_aiobotocore_pricing.client import PricingClient
     from types_aiobotocore_pricing.paginator import (
         DescribeServicesPaginator,
         GetAttributeValuesPaginator,
         GetProductsPaginator,
+        ListPriceListsPaginator,
     )
 
     session = get_session()
     with session.create_client("pricing") as client:
         client: PricingClient
 
         describe_services_paginator: DescribeServicesPaginator = client.get_paginator("describe_services")
         get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator("get_attribute_values")
         get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+        list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from datetime import datetime
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeServicesResponseTypeDef,
     FilterTypeDef,
     GetAttributeValuesResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
-__all__ = ("DescribeServicesPaginator", "GetAttributeValuesPaginator", "GetProductsPaginator")
+__all__ = (
+    "DescribeServicesPaginator",
+    "GetAttributeValuesPaginator",
+    "GetProductsPaginator",
+    "ListPriceListsPaginator",
+)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
@@ -64,15 +66,15 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str = ...,
         FormatVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.DescribeServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#describeservicespaginator)
         """
 
 
@@ -83,15 +85,15 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str,
         AttributeName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAttributeValuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.GetAttributeValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#getattributevaluespaginator)
         """
 
 
@@ -103,13 +105,34 @@
 
     def paginate(
         self,
         *,
         ServiceCode: str,
         Filters: Sequence[FilterTypeDef] = ...,
         FormatVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetProductsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.GetProducts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#getproductspaginator)
         """
+
+
+class ListPriceListsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.ListPriceLists)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#listpricelistspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        ServiceCode: str,
+        EffectiveDate: Union[datetime, str],
+        CurrencyCode: str,
+        RegionCode: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPriceListsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.ListPriceLists.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#listpricelistspaginator)
+        """
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing/paginator.pyi` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing/paginator.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -9,45 +9,48 @@
     from aiobotocore.session import get_session
 
     from types_aiobotocore_pricing.client import PricingClient
     from types_aiobotocore_pricing.paginator import (
         DescribeServicesPaginator,
         GetAttributeValuesPaginator,
         GetProductsPaginator,
+        ListPriceListsPaginator,
     )
 
     session = get_session()
     with session.create_client("pricing") as client:
         client: PricingClient
 
         describe_services_paginator: DescribeServicesPaginator = client.get_paginator("describe_services")
         get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator("get_attribute_values")
         get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+        list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from datetime import datetime
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeServicesResponseTypeDef,
     FilterTypeDef,
     GetAttributeValuesResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-__all__ = ("DescribeServicesPaginator", "GetAttributeValuesPaginator", "GetProductsPaginator")
+__all__ = (
+    "DescribeServicesPaginator",
+    "GetAttributeValuesPaginator",
+    "GetProductsPaginator",
+    "ListPriceListsPaginator",
+)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
@@ -60,15 +63,15 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str = ...,
         FormatVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.DescribeServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#describeservicespaginator)
         """
 
 class GetAttributeValuesPaginator(AioPaginator):
@@ -78,15 +81,15 @@
     """
 
     def paginate(
         self,
         *,
         ServiceCode: str,
         AttributeName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAttributeValuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.GetAttributeValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#getattributevaluespaginator)
         """
 
 class GetProductsPaginator(AioPaginator):
@@ -97,13 +100,33 @@
 
     def paginate(
         self,
         *,
         ServiceCode: str,
         Filters: Sequence[FilterTypeDef] = ...,
         FormatVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetProductsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.GetProducts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#getproductspaginator)
         """
+
+class ListPriceListsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.ListPriceLists)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#listpricelistspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        ServiceCode: str,
+        EffectiveDate: Union[datetime, str],
+        CurrencyCode: str,
+        RegionCode: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPriceListsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing.Paginator.ListPriceLists.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/paginators/#listpricelistspaginator)
+        """
```

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/PKG-INFO` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pricing
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Pricing 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Pricing 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pricing"></a>
 
 # types-aiobotocore-pricing
 
 [![PyPI - types-aiobotocore-pricing](https://img.shields.io/pypi/v/types-aiobotocore-pricing.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pricing)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pricing.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pricing)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pricing?color=blue)](https://pypistats.org/packages/types-aiobotocore-pricing)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Pricing 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing)
+[aiobotocore.Pricing 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pricing.html#Pricing)
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
 [types-aiobotocore-pricing docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pricing/).
 
 See how it helps to find and fix potential bugs:
 
@@ -275,14 +275,15 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_pricing import PricingClient
 from types_aiobotocore_pricing.paginator import (
     DescribeServicesPaginator,
     GetAttributeValuesPaginator,
     GetProductsPaginator,
+    ListPriceListsPaginator,
 )
 
 session = get_session()
 async with session.create_client("pricing") as client:
     client: PricingClient
 
     # Explicit type annotations are optional here
@@ -290,14 +291,15 @@
     describe_services_paginator: DescribeServicesPaginator = client.get_paginator(
         "describe_services"
     )
     get_attribute_values_paginator: GetAttributeValuesPaginator = client.get_paginator(
         "get_attribute_values"
     )
     get_products_paginator: GetProductsPaginator = client.get_paginator("get_products")
+    list_price_lists_paginator: ListPriceListsPaginator = client.get_paginator("list_price_lists")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_pricing.literals` module contains literals extracted from
@@ -305,14 +307,15 @@
 
 ```python
 from types_aiobotocore_pricing.literals import (
     DescribeServicesPaginatorName,
     FilterTypeType,
     GetAttributeValuesPaginatorName,
     GetProductsPaginatorName,
+    ListPriceListsPaginatorName,
     PricingServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -327,70 +330,76 @@
 
 `types_aiobotocore_pricing.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_pricing.type_defs import (
     AttributeValueTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeServicesRequestDescribeServicesPaginateTypeDef,
     DescribeServicesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ServiceTypeDef,
     FilterTypeDef,
-    GetAttributeValuesRequestRequestTypeDef,
-    DescribeServicesRequestDescribeServicesPaginateTypeDef,
     GetAttributeValuesRequestGetAttributeValuesPaginateTypeDef,
-    GetAttributeValuesResponseTypeDef,
+    GetAttributeValuesRequestRequestTypeDef,
+    GetPriceListFileUrlRequestRequestTypeDef,
+    GetPriceListFileUrlResponseTypeDef,
     GetProductsResponseTypeDef,
+    ListPriceListsRequestListPriceListsPaginateTypeDef,
+    ListPriceListsRequestRequestTypeDef,
+    PriceListTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    GetAttributeValuesResponseTypeDef,
     DescribeServicesResponseTypeDef,
     GetProductsRequestGetProductsPaginateTypeDef,
     GetProductsRequestRequestTypeDef,
+    ListPriceListsResponseTypeDef,
 )
 
 
 def get_structure() -> AttributeValueTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-pricing-2.5.0.post1/types_aiobotocore_pricing.egg-info/SOURCES.txt` & `types-aiobotocore-pricing-2.5.1/types_aiobotocore_pricing.egg-info/SOURCES.txt`

 * *Files identical despite different names*

