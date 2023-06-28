# Comparing `tmp/types-aiobotocore-outposts-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-outposts-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-outposts-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:05 2023, max compression
+gzip compressed data, was "types-aiobotocore-outposts-2.5.1.tar", last modified: Wed Jun 28 01:43:56 2023, max compression
```

## Comparing `types-aiobotocore-outposts-2.5.0.post1.tar` & `types-aiobotocore-outposts-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.979487 types-aiobotocore-outposts-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14776 2023-03-11 12:27:05.971487 types-aiobotocore-outposts-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13201 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:05.979487 types-aiobotocore-outposts-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:19:36.000000 types-aiobotocore-outposts-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.971487 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20144 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20110 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10575 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10573 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    21400 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    21381 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:37.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.971487 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14776 2023-03-11 12:27:05.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:05.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:05.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:05.000000 types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.690188 types-aiobotocore-outposts-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14769 2023-06-28 01:43:56.682187 types-aiobotocore-outposts-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13200 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:56.690188 types-aiobotocore-outposts-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.682187 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/
+-rw-r--r--   0 runner    (1001) docker     (123)      450 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20144 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20110 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10784 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10782 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21442 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21423 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:22.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.682187 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14769 2023-06-28 01:43:56.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:43:56.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:56.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:56.000000 types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-outposts-2.5.0.post1/LICENSE` & `types-aiobotocore-outposts-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/PKG-INFO` & `types-aiobotocore-outposts-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-outposts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Outposts 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Outposts 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-outposts"></a>
 
 # types-aiobotocore-outposts
 
 [![PyPI - types-aiobotocore-outposts](https://img.shields.io/pypi/v/types-aiobotocore-outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-outposts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-outposts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-outposts?color=blue)](https://pypistats.org/packages/types-aiobotocore-outposts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Outposts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
+[aiobotocore.Outposts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
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
 [types-aiobotocore-outposts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,15 +318,14 @@
     AddressTypeDef,
     AssetLocationTypeDef,
     ComputeAttributesTypeDef,
     CancelOrderInputRequestTypeDef,
     EC2CapacityTypeDef,
     ConnectionDetailsTypeDef,
     LineItemRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateOutpostInputRequestTypeDef,
     OutpostTypeDef,
     RackPhysicalPropertiesTypeDef,
     DeleteOutpostInputRequestTypeDef,
     DeleteSiteInputRequestTypeDef,
     GetCatalogItemInputRequestTypeDef,
     GetConnectionRequestRequestTypeDef,
@@ -341,29 +340,30 @@
     ListAssetsInputRequestTypeDef,
     ListCatalogItemsInputRequestTypeDef,
     ListOrdersInputRequestTypeDef,
     OrderSummaryTypeDef,
     ListOutpostsInputRequestTypeDef,
     ListSitesInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartConnectionRequestRequestTypeDef,
+    StartConnectionResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateOutpostInputRequestTypeDef,
     UpdateSiteInputRequestTypeDef,
     UpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
+    GetSiteAddressOutputTypeDef,
     UpdateSiteAddressInputRequestTypeDef,
+    UpdateSiteAddressOutputTypeDef,
     AssetInfoTypeDef,
     CatalogItemTypeDef,
-    CreateOrderInputRequestTypeDef,
     GetConnectionResponseTypeDef,
-    GetSiteAddressOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartConnectionResponseTypeDef,
-    UpdateSiteAddressOutputTypeDef,
+    CreateOrderInputRequestTypeDef,
     CreateOutpostOutputTypeDef,
     GetOutpostOutputTypeDef,
     ListOutpostsOutputTypeDef,
     UpdateOutpostOutputTypeDef,
     CreateSiteInputRequestTypeDef,
     SiteTypeDef,
     GetOutpostInstanceTypesOutputTypeDef,
@@ -390,43 +390,43 @@
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/README.md` & `types-aiobotocore-outposts-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-outposts"></a>
 
 # types-aiobotocore-outposts
 
 [![PyPI - types-aiobotocore-outposts](https://img.shields.io/pypi/v/types-aiobotocore-outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-outposts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-outposts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-outposts?color=blue)](https://pypistats.org/packages/types-aiobotocore-outposts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Outposts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
+[aiobotocore.Outposts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
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
 [types-aiobotocore-outposts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -285,15 +285,14 @@
     AddressTypeDef,
     AssetLocationTypeDef,
     ComputeAttributesTypeDef,
     CancelOrderInputRequestTypeDef,
     EC2CapacityTypeDef,
     ConnectionDetailsTypeDef,
     LineItemRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateOutpostInputRequestTypeDef,
     OutpostTypeDef,
     RackPhysicalPropertiesTypeDef,
     DeleteOutpostInputRequestTypeDef,
     DeleteSiteInputRequestTypeDef,
     GetCatalogItemInputRequestTypeDef,
     GetConnectionRequestRequestTypeDef,
@@ -308,29 +307,30 @@
     ListAssetsInputRequestTypeDef,
     ListCatalogItemsInputRequestTypeDef,
     ListOrdersInputRequestTypeDef,
     OrderSummaryTypeDef,
     ListOutpostsInputRequestTypeDef,
     ListSitesInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartConnectionRequestRequestTypeDef,
+    StartConnectionResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateOutpostInputRequestTypeDef,
     UpdateSiteInputRequestTypeDef,
     UpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
+    GetSiteAddressOutputTypeDef,
     UpdateSiteAddressInputRequestTypeDef,
+    UpdateSiteAddressOutputTypeDef,
     AssetInfoTypeDef,
     CatalogItemTypeDef,
-    CreateOrderInputRequestTypeDef,
     GetConnectionResponseTypeDef,
-    GetSiteAddressOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartConnectionResponseTypeDef,
-    UpdateSiteAddressOutputTypeDef,
+    CreateOrderInputRequestTypeDef,
     CreateOutpostOutputTypeDef,
     GetOutpostOutputTypeDef,
     ListOutpostsOutputTypeDef,
     UpdateOutpostOutputTypeDef,
     CreateSiteInputRequestTypeDef,
     SiteTypeDef,
     GetOutpostInstanceTypesOutputTypeDef,
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/setup.py` & `types-aiobotocore-outposts-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-outposts.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-outposts",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_outposts"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Outposts 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Outposts 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/"
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/__main__.py` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Outposts 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Outposts 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts\nOther"
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/client.py` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/client.pyi` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/literals.py` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -180,14 +180,15 @@
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
@@ -266,14 +267,15 @@
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
@@ -284,14 +286,15 @@
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
@@ -327,14 +330,15 @@
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
@@ -353,16 +357,19 @@
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
@@ -446,15 +453,17 @@
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/literals.pyi` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -178,14 +178,15 @@
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
@@ -264,14 +265,15 @@
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
@@ -282,14 +284,15 @@
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
@@ -325,14 +328,15 @@
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
@@ -351,16 +355,19 @@
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
@@ -444,15 +451,17 @@
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/type_defs.py` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -54,15 +54,14 @@
     "AddressTypeDef",
     "AssetLocationTypeDef",
     "ComputeAttributesTypeDef",
     "CancelOrderInputRequestTypeDef",
     "EC2CapacityTypeDef",
     "ConnectionDetailsTypeDef",
     "LineItemRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateOutpostInputRequestTypeDef",
     "OutpostTypeDef",
     "RackPhysicalPropertiesTypeDef",
     "DeleteOutpostInputRequestTypeDef",
     "DeleteSiteInputRequestTypeDef",
     "GetCatalogItemInputRequestTypeDef",
     "GetConnectionRequestRequestTypeDef",
@@ -77,29 +76,30 @@
     "ListAssetsInputRequestTypeDef",
     "ListCatalogItemsInputRequestTypeDef",
     "ListOrdersInputRequestTypeDef",
     "OrderSummaryTypeDef",
     "ListOutpostsInputRequestTypeDef",
     "ListSitesInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartConnectionRequestRequestTypeDef",
+    "StartConnectionResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateOutpostInputRequestTypeDef",
     "UpdateSiteInputRequestTypeDef",
     "UpdateSiteRackPhysicalPropertiesInputRequestTypeDef",
+    "GetSiteAddressOutputTypeDef",
     "UpdateSiteAddressInputRequestTypeDef",
+    "UpdateSiteAddressOutputTypeDef",
     "AssetInfoTypeDef",
     "CatalogItemTypeDef",
-    "CreateOrderInputRequestTypeDef",
     "GetConnectionResponseTypeDef",
-    "GetSiteAddressOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartConnectionResponseTypeDef",
-    "UpdateSiteAddressOutputTypeDef",
+    "CreateOrderInputRequestTypeDef",
     "CreateOutpostOutputTypeDef",
     "GetOutpostOutputTypeDef",
     "ListOutpostsOutputTypeDef",
     "UpdateOutpostOutputTypeDef",
     "CreateSiteInputRequestTypeDef",
     "SiteTypeDef",
     "GetOutpostInstanceTypesOutputTypeDef",
@@ -198,25 +198,14 @@
     {
         "CatalogItemId": str,
         "Quantity": int,
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
 _RequiredCreateOutpostInputRequestTypeDef = TypedDict(
     "_RequiredCreateOutpostInputRequestTypeDef",
     {
         "Name": str,
         "SiteId": str,
     },
 )
@@ -467,24 +456,52 @@
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
 StartConnectionRequestRequestTypeDef = TypedDict(
     "StartConnectionRequestRequestTypeDef",
     {
         "DeviceSerialNumber": str,
         "AssetId": str,
         "ClientPublicKey": str,
         "NetworkInterfaceDeviceIndex": int,
     },
 )
 
+StartConnectionResponseTypeDef = TypedDict(
+    "StartConnectionResponseTypeDef",
+    {
+        "ConnectionId": str,
+        "UnderlayIpAddress": str,
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
@@ -569,23 +586,42 @@
 class UpdateSiteRackPhysicalPropertiesInputRequestTypeDef(
     _RequiredUpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
     _OptionalUpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
 ):
     pass
 
 
+GetSiteAddressOutputTypeDef = TypedDict(
+    "GetSiteAddressOutputTypeDef",
+    {
+        "SiteId": str,
+        "AddressType": AddressTypeType,
+        "Address": AddressTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSiteAddressInputRequestTypeDef = TypedDict(
     "UpdateSiteAddressInputRequestTypeDef",
     {
         "SiteId": str,
         "AddressType": AddressTypeType,
         "Address": AddressTypeDef,
     },
 )
 
+UpdateSiteAddressOutputTypeDef = TypedDict(
+    "UpdateSiteAddressOutputTypeDef",
+    {
+        "AddressType": AddressTypeType,
+        "Address": AddressTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssetInfoTypeDef = TypedDict(
     "AssetInfoTypeDef",
     {
         "AssetId": str,
         "RackId": str,
         "AssetType": Literal["COMPUTE"],
         "ComputeAttributes": ComputeAttributesTypeDef,
@@ -604,14 +640,23 @@
         "WeightLbs": int,
         "SupportedUplinkGbps": List[int],
         "SupportedStorage": List[SupportedStorageEnumType],
     },
     total=False,
 )
 
+GetConnectionResponseTypeDef = TypedDict(
+    "GetConnectionResponseTypeDef",
+    {
+        "ConnectionId": str,
+        "ConnectionDetails": ConnectionDetailsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateOrderInputRequestTypeDef = TypedDict(
     "_RequiredCreateOrderInputRequestTypeDef",
     {
         "OutpostIdentifier": str,
         "LineItems": Sequence[LineItemRequestTypeDef],
         "PaymentOption": PaymentOptionType,
     },
@@ -627,89 +672,44 @@
 
 class CreateOrderInputRequestTypeDef(
     _RequiredCreateOrderInputRequestTypeDef, _OptionalCreateOrderInputRequestTypeDef
 ):
     pass
 
 
-GetConnectionResponseTypeDef = TypedDict(
-    "GetConnectionResponseTypeDef",
-    {
-        "ConnectionId": str,
-        "ConnectionDetails": ConnectionDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSiteAddressOutputTypeDef = TypedDict(
-    "GetSiteAddressOutputTypeDef",
-    {
-        "SiteId": str,
-        "AddressType": AddressTypeType,
-        "Address": AddressTypeDef,
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
-StartConnectionResponseTypeDef = TypedDict(
-    "StartConnectionResponseTypeDef",
-    {
-        "ConnectionId": str,
-        "UnderlayIpAddress": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSiteAddressOutputTypeDef = TypedDict(
-    "UpdateSiteAddressOutputTypeDef",
-    {
-        "AddressType": AddressTypeType,
-        "Address": AddressTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateOutpostOutputTypeDef = TypedDict(
     "CreateOutpostOutputTypeDef",
     {
         "Outpost": OutpostTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOutpostOutputTypeDef = TypedDict(
     "GetOutpostOutputTypeDef",
     {
         "Outpost": OutpostTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOutpostsOutputTypeDef = TypedDict(
     "ListOutpostsOutputTypeDef",
     {
         "Outposts": List[OutpostTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateOutpostOutputTypeDef = TypedDict(
     "UpdateOutpostOutputTypeDef",
     {
         "Outpost": OutpostTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSiteInputRequestTypeDef = TypedDict(
     "_RequiredCreateSiteInputRequestTypeDef",
     {
         "Name": str,
@@ -756,15 +756,15 @@
 GetOutpostInstanceTypesOutputTypeDef = TypedDict(
     "GetOutpostInstanceTypesOutputTypeDef",
     {
         "InstanceTypes": List[InstanceTypeItemTypeDef],
         "NextToken": str,
         "OutpostId": str,
         "OutpostArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LineItemTypeDef = TypedDict(
     "LineItemTypeDef",
     {
         "CatalogItemId": str,
@@ -780,82 +780,82 @@
 )
 
 ListOrdersOutputTypeDef = TypedDict(
     "ListOrdersOutputTypeDef",
     {
         "Orders": List[OrderSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetsOutputTypeDef = TypedDict(
     "ListAssetsOutputTypeDef",
     {
         "Assets": List[AssetInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCatalogItemOutputTypeDef = TypedDict(
     "GetCatalogItemOutputTypeDef",
     {
         "CatalogItem": CatalogItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCatalogItemsOutputTypeDef = TypedDict(
     "ListCatalogItemsOutputTypeDef",
     {
         "CatalogItems": List[CatalogItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSiteOutputTypeDef = TypedDict(
     "CreateSiteOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSiteOutputTypeDef = TypedDict(
     "GetSiteOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSitesOutputTypeDef = TypedDict(
     "ListSitesOutputTypeDef",
     {
         "Sites": List[SiteTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSiteOutputTypeDef = TypedDict(
     "UpdateSiteOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSiteRackPhysicalPropertiesOutputTypeDef = TypedDict(
     "UpdateSiteRackPhysicalPropertiesOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrderTypeDef = TypedDict(
     "OrderTypeDef",
     {
         "OutpostId": str,
@@ -871,18 +871,18 @@
     total=False,
 )
 
 CreateOrderOutputTypeDef = TypedDict(
     "CreateOrderOutputTypeDef",
     {
         "Order": OrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOrderOutputTypeDef = TypedDict(
     "GetOrderOutputTypeDef",
     {
         "Order": OrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts/type_defs.pyi` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -53,15 +53,14 @@
     "AddressTypeDef",
     "AssetLocationTypeDef",
     "ComputeAttributesTypeDef",
     "CancelOrderInputRequestTypeDef",
     "EC2CapacityTypeDef",
     "ConnectionDetailsTypeDef",
     "LineItemRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateOutpostInputRequestTypeDef",
     "OutpostTypeDef",
     "RackPhysicalPropertiesTypeDef",
     "DeleteOutpostInputRequestTypeDef",
     "DeleteSiteInputRequestTypeDef",
     "GetCatalogItemInputRequestTypeDef",
     "GetConnectionRequestRequestTypeDef",
@@ -76,29 +75,30 @@
     "ListAssetsInputRequestTypeDef",
     "ListCatalogItemsInputRequestTypeDef",
     "ListOrdersInputRequestTypeDef",
     "OrderSummaryTypeDef",
     "ListOutpostsInputRequestTypeDef",
     "ListSitesInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartConnectionRequestRequestTypeDef",
+    "StartConnectionResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateOutpostInputRequestTypeDef",
     "UpdateSiteInputRequestTypeDef",
     "UpdateSiteRackPhysicalPropertiesInputRequestTypeDef",
+    "GetSiteAddressOutputTypeDef",
     "UpdateSiteAddressInputRequestTypeDef",
+    "UpdateSiteAddressOutputTypeDef",
     "AssetInfoTypeDef",
     "CatalogItemTypeDef",
-    "CreateOrderInputRequestTypeDef",
     "GetConnectionResponseTypeDef",
-    "GetSiteAddressOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartConnectionResponseTypeDef",
-    "UpdateSiteAddressOutputTypeDef",
+    "CreateOrderInputRequestTypeDef",
     "CreateOutpostOutputTypeDef",
     "GetOutpostOutputTypeDef",
     "ListOutpostsOutputTypeDef",
     "UpdateOutpostOutputTypeDef",
     "CreateSiteInputRequestTypeDef",
     "SiteTypeDef",
     "GetOutpostInstanceTypesOutputTypeDef",
@@ -195,25 +195,14 @@
     {
         "CatalogItemId": str,
         "Quantity": int,
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
 _RequiredCreateOutpostInputRequestTypeDef = TypedDict(
     "_RequiredCreateOutpostInputRequestTypeDef",
     {
         "Name": str,
         "SiteId": str,
     },
 )
@@ -458,24 +447,52 @@
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
 StartConnectionRequestRequestTypeDef = TypedDict(
     "StartConnectionRequestRequestTypeDef",
     {
         "DeviceSerialNumber": str,
         "AssetId": str,
         "ClientPublicKey": str,
         "NetworkInterfaceDeviceIndex": int,
     },
 )
 
+StartConnectionResponseTypeDef = TypedDict(
+    "StartConnectionResponseTypeDef",
+    {
+        "ConnectionId": str,
+        "UnderlayIpAddress": str,
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
@@ -554,23 +571,42 @@
 
 class UpdateSiteRackPhysicalPropertiesInputRequestTypeDef(
     _RequiredUpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
     _OptionalUpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
 ):
     pass
 
+GetSiteAddressOutputTypeDef = TypedDict(
+    "GetSiteAddressOutputTypeDef",
+    {
+        "SiteId": str,
+        "AddressType": AddressTypeType,
+        "Address": AddressTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSiteAddressInputRequestTypeDef = TypedDict(
     "UpdateSiteAddressInputRequestTypeDef",
     {
         "SiteId": str,
         "AddressType": AddressTypeType,
         "Address": AddressTypeDef,
     },
 )
 
+UpdateSiteAddressOutputTypeDef = TypedDict(
+    "UpdateSiteAddressOutputTypeDef",
+    {
+        "AddressType": AddressTypeType,
+        "Address": AddressTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssetInfoTypeDef = TypedDict(
     "AssetInfoTypeDef",
     {
         "AssetId": str,
         "RackId": str,
         "AssetType": Literal["COMPUTE"],
         "ComputeAttributes": ComputeAttributesTypeDef,
@@ -589,14 +625,23 @@
         "WeightLbs": int,
         "SupportedUplinkGbps": List[int],
         "SupportedStorage": List[SupportedStorageEnumType],
     },
     total=False,
 )
 
+GetConnectionResponseTypeDef = TypedDict(
+    "GetConnectionResponseTypeDef",
+    {
+        "ConnectionId": str,
+        "ConnectionDetails": ConnectionDetailsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateOrderInputRequestTypeDef = TypedDict(
     "_RequiredCreateOrderInputRequestTypeDef",
     {
         "OutpostIdentifier": str,
         "LineItems": Sequence[LineItemRequestTypeDef],
         "PaymentOption": PaymentOptionType,
     },
@@ -610,89 +655,44 @@
 )
 
 class CreateOrderInputRequestTypeDef(
     _RequiredCreateOrderInputRequestTypeDef, _OptionalCreateOrderInputRequestTypeDef
 ):
     pass
 
-GetConnectionResponseTypeDef = TypedDict(
-    "GetConnectionResponseTypeDef",
-    {
-        "ConnectionId": str,
-        "ConnectionDetails": ConnectionDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSiteAddressOutputTypeDef = TypedDict(
-    "GetSiteAddressOutputTypeDef",
-    {
-        "SiteId": str,
-        "AddressType": AddressTypeType,
-        "Address": AddressTypeDef,
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
-StartConnectionResponseTypeDef = TypedDict(
-    "StartConnectionResponseTypeDef",
-    {
-        "ConnectionId": str,
-        "UnderlayIpAddress": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSiteAddressOutputTypeDef = TypedDict(
-    "UpdateSiteAddressOutputTypeDef",
-    {
-        "AddressType": AddressTypeType,
-        "Address": AddressTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateOutpostOutputTypeDef = TypedDict(
     "CreateOutpostOutputTypeDef",
     {
         "Outpost": OutpostTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOutpostOutputTypeDef = TypedDict(
     "GetOutpostOutputTypeDef",
     {
         "Outpost": OutpostTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOutpostsOutputTypeDef = TypedDict(
     "ListOutpostsOutputTypeDef",
     {
         "Outposts": List[OutpostTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateOutpostOutputTypeDef = TypedDict(
     "UpdateOutpostOutputTypeDef",
     {
         "Outpost": OutpostTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSiteInputRequestTypeDef = TypedDict(
     "_RequiredCreateSiteInputRequestTypeDef",
     {
         "Name": str,
@@ -737,15 +737,15 @@
 GetOutpostInstanceTypesOutputTypeDef = TypedDict(
     "GetOutpostInstanceTypesOutputTypeDef",
     {
         "InstanceTypes": List[InstanceTypeItemTypeDef],
         "NextToken": str,
         "OutpostId": str,
         "OutpostArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LineItemTypeDef = TypedDict(
     "LineItemTypeDef",
     {
         "CatalogItemId": str,
@@ -761,82 +761,82 @@
 )
 
 ListOrdersOutputTypeDef = TypedDict(
     "ListOrdersOutputTypeDef",
     {
         "Orders": List[OrderSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetsOutputTypeDef = TypedDict(
     "ListAssetsOutputTypeDef",
     {
         "Assets": List[AssetInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCatalogItemOutputTypeDef = TypedDict(
     "GetCatalogItemOutputTypeDef",
     {
         "CatalogItem": CatalogItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCatalogItemsOutputTypeDef = TypedDict(
     "ListCatalogItemsOutputTypeDef",
     {
         "CatalogItems": List[CatalogItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSiteOutputTypeDef = TypedDict(
     "CreateSiteOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSiteOutputTypeDef = TypedDict(
     "GetSiteOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSitesOutputTypeDef = TypedDict(
     "ListSitesOutputTypeDef",
     {
         "Sites": List[SiteTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSiteOutputTypeDef = TypedDict(
     "UpdateSiteOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSiteRackPhysicalPropertiesOutputTypeDef = TypedDict(
     "UpdateSiteRackPhysicalPropertiesOutputTypeDef",
     {
         "Site": SiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrderTypeDef = TypedDict(
     "OrderTypeDef",
     {
         "OutpostId": str,
@@ -852,18 +852,18 @@
     total=False,
 )
 
 CreateOrderOutputTypeDef = TypedDict(
     "CreateOrderOutputTypeDef",
     {
         "Order": OrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOrderOutputTypeDef = TypedDict(
     "GetOrderOutputTypeDef",
     {
         "Order": OrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/PKG-INFO` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-outposts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Outposts 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Outposts 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-outposts"></a>
 
 # types-aiobotocore-outposts
 
 [![PyPI - types-aiobotocore-outposts](https://img.shields.io/pypi/v/types-aiobotocore-outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-outposts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-outposts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-outposts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-outposts?color=blue)](https://pypistats.org/packages/types-aiobotocore-outposts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Outposts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
+[aiobotocore.Outposts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/outposts.html#Outposts)
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
 [types-aiobotocore-outposts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,15 +318,14 @@
     AddressTypeDef,
     AssetLocationTypeDef,
     ComputeAttributesTypeDef,
     CancelOrderInputRequestTypeDef,
     EC2CapacityTypeDef,
     ConnectionDetailsTypeDef,
     LineItemRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateOutpostInputRequestTypeDef,
     OutpostTypeDef,
     RackPhysicalPropertiesTypeDef,
     DeleteOutpostInputRequestTypeDef,
     DeleteSiteInputRequestTypeDef,
     GetCatalogItemInputRequestTypeDef,
     GetConnectionRequestRequestTypeDef,
@@ -341,29 +340,30 @@
     ListAssetsInputRequestTypeDef,
     ListCatalogItemsInputRequestTypeDef,
     ListOrdersInputRequestTypeDef,
     OrderSummaryTypeDef,
     ListOutpostsInputRequestTypeDef,
     ListSitesInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartConnectionRequestRequestTypeDef,
+    StartConnectionResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateOutpostInputRequestTypeDef,
     UpdateSiteInputRequestTypeDef,
     UpdateSiteRackPhysicalPropertiesInputRequestTypeDef,
+    GetSiteAddressOutputTypeDef,
     UpdateSiteAddressInputRequestTypeDef,
+    UpdateSiteAddressOutputTypeDef,
     AssetInfoTypeDef,
     CatalogItemTypeDef,
-    CreateOrderInputRequestTypeDef,
     GetConnectionResponseTypeDef,
-    GetSiteAddressOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartConnectionResponseTypeDef,
-    UpdateSiteAddressOutputTypeDef,
+    CreateOrderInputRequestTypeDef,
     CreateOutpostOutputTypeDef,
     GetOutpostOutputTypeDef,
     ListOutpostsOutputTypeDef,
     UpdateOutpostOutputTypeDef,
     CreateSiteInputRequestTypeDef,
     SiteTypeDef,
     GetOutpostInstanceTypesOutputTypeDef,
@@ -390,43 +390,43 @@
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

### Comparing `types-aiobotocore-outposts-2.5.0.post1/types_aiobotocore_outposts.egg-info/SOURCES.txt` & `types-aiobotocore-outposts-2.5.1/types_aiobotocore_outposts.egg-info/SOURCES.txt`

 * *Files identical despite different names*

