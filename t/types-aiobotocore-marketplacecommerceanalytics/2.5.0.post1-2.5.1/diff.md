# Comparing `tmp/types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-marketplacecommerceanalytics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-marketplacecommerceanalytics-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1.tar` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.535415 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13313 2023-03-11 12:26:58.535415 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11658 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.535415 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2274 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.531415 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/
--rw-r--r--   0 runner    (1001) docker     (123)      610 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      609 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1027 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6669 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6659 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8809 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8807 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2962 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2957 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:08.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.531415 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13313 2023-03-11 12:26:58.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-03-11 12:26:58.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-03-11 12:26:58.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.486174 types-aiobotocore-marketplacecommerceanalytics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13326 2023-06-28 01:43:49.486174 types-aiobotocore-marketplacecommerceanalytics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11677 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.486174 types-aiobotocore-marketplacecommerceanalytics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2268 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.486174 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/
+-rw-r--r--   0 runner    (1001) docker     (123)      610 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      609 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6669 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6659 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9018 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9016 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2966 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2961 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:50.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.486174 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13326 2023-06-28 01:43:49.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-06-28 01:43:49.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 01:43:49.000000 types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/LICENSE` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-marketplacecommerceanalytics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-marketplacecommerceanalytics"></a>
 
 # types-aiobotocore-marketplacecommerceanalytics
 
 [![PyPI - types-aiobotocore-marketplacecommerceanalytics](https://img.shields.io/pypi/v/types-aiobotocore-marketplacecommerceanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplacecommerceanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplacecommerceanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplacecommerceanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplacecommerceanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplacecommerceanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceCommerceAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics)
+[aiobotocore.MarketplaceCommerceAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics)
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
 [types-aiobotocore-marketplacecommerceanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,17 +297,17 @@
 `types_aiobotocore_marketplacecommerceanalytics.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_marketplacecommerceanalytics.type_defs import (
     GenerateDataSetRequestRequestTypeDef,
+    GenerateDataSetResultTypeDef,
     ResponseMetadataTypeDef,
     StartSupportDataExportRequestRequestTypeDef,
-    GenerateDataSetResultTypeDef,
     StartSupportDataExportResultTypeDef,
 )
 
 
 def get_structure() -> GenerateDataSetRequestRequestTypeDef:
     return {...}
 ```
@@ -315,43 +315,43 @@
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/README.md` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-marketplacecommerceanalytics"></a>
 
 # types-aiobotocore-marketplacecommerceanalytics
 
 [![PyPI - types-aiobotocore-marketplacecommerceanalytics](https://img.shields.io/pypi/v/types-aiobotocore-marketplacecommerceanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplacecommerceanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplacecommerceanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplacecommerceanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplacecommerceanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplacecommerceanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceCommerceAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics)
+[aiobotocore.MarketplaceCommerceAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics)
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
 [types-aiobotocore-marketplacecommerceanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -264,17 +264,17 @@
 `types_aiobotocore_marketplacecommerceanalytics.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_marketplacecommerceanalytics.type_defs import (
     GenerateDataSetRequestRequestTypeDef,
+    GenerateDataSetResultTypeDef,
     ResponseMetadataTypeDef,
     StartSupportDataExportRequestRequestTypeDef,
-    GenerateDataSetResultTypeDef,
     StartSupportDataExportResultTypeDef,
 )
 
 
 def get_structure() -> GenerateDataSetRequestRequestTypeDef:
     return {...}
 ```
@@ -282,43 +282,43 @@
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/setup.py` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-marketplacecommerceanalytics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-marketplacecommerceanalytics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_marketplacecommerceanalytics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/",
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/__init__.py` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/__init__.pyi` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/__main__.py` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics\nOther"
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/client.py` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/client.pyi` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/literals.py` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -118,14 +118,15 @@
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
@@ -204,14 +205,15 @@
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
@@ -222,14 +224,15 @@
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
@@ -265,14 +268,15 @@
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
@@ -291,16 +295,19 @@
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
@@ -384,15 +391,17 @@
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/literals.pyi` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/literals.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -116,14 +116,15 @@
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
@@ -202,14 +203,15 @@
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
@@ -220,14 +222,15 @@
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
@@ -263,14 +266,15 @@
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
@@ -289,16 +293,19 @@
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
@@ -382,15 +389,17 @@
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/type_defs.py` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -21,17 +21,17 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "GenerateDataSetRequestRequestTypeDef",
+    "GenerateDataSetResultTypeDef",
     "ResponseMetadataTypeDef",
     "StartSupportDataExportRequestRequestTypeDef",
-    "GenerateDataSetResultTypeDef",
     "StartSupportDataExportResultTypeDef",
 )
 
 _RequiredGenerateDataSetRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateDataSetRequestRequestTypeDef",
     {
         "dataSetType": DataSetTypeType,
@@ -53,14 +53,22 @@
 
 class GenerateDataSetRequestRequestTypeDef(
     _RequiredGenerateDataSetRequestRequestTypeDef, _OptionalGenerateDataSetRequestRequestTypeDef
 ):
     pass
 
 
+GenerateDataSetResultTypeDef = TypedDict(
+    "GenerateDataSetResultTypeDef",
+    {
+        "dataSetRequestId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -91,22 +99,14 @@
 class StartSupportDataExportRequestRequestTypeDef(
     _RequiredStartSupportDataExportRequestRequestTypeDef,
     _OptionalStartSupportDataExportRequestRequestTypeDef,
 ):
     pass
 
 
-GenerateDataSetResultTypeDef = TypedDict(
-    "GenerateDataSetResultTypeDef",
-    {
-        "dataSetRequestId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 StartSupportDataExportResultTypeDef = TypedDict(
     "StartSupportDataExportResultTypeDef",
     {
         "dataSetRequestId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics/type_defs.pyi` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,17 +20,17 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "GenerateDataSetRequestRequestTypeDef",
+    "GenerateDataSetResultTypeDef",
     "ResponseMetadataTypeDef",
     "StartSupportDataExportRequestRequestTypeDef",
-    "GenerateDataSetResultTypeDef",
     "StartSupportDataExportResultTypeDef",
 )
 
 _RequiredGenerateDataSetRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateDataSetRequestRequestTypeDef",
     {
         "dataSetType": DataSetTypeType,
@@ -50,14 +50,22 @@
 )
 
 class GenerateDataSetRequestRequestTypeDef(
     _RequiredGenerateDataSetRequestRequestTypeDef, _OptionalGenerateDataSetRequestRequestTypeDef
 ):
     pass
 
+GenerateDataSetResultTypeDef = TypedDict(
+    "GenerateDataSetResultTypeDef",
+    {
+        "dataSetRequestId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -86,22 +94,14 @@
 
 class StartSupportDataExportRequestRequestTypeDef(
     _RequiredStartSupportDataExportRequestRequestTypeDef,
     _OptionalStartSupportDataExportRequestRequestTypeDef,
 ):
     pass
 
-GenerateDataSetResultTypeDef = TypedDict(
-    "GenerateDataSetResultTypeDef",
-    {
-        "dataSetRequestId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 StartSupportDataExportResultTypeDef = TypedDict(
     "StartSupportDataExportResultTypeDef",
     {
         "dataSetRequestId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/PKG-INFO` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-marketplacecommerceanalytics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceCommerceAnalytics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-marketplacecommerceanalytics"></a>
 
 # types-aiobotocore-marketplacecommerceanalytics
 
 [![PyPI - types-aiobotocore-marketplacecommerceanalytics](https://img.shields.io/pypi/v/types-aiobotocore-marketplacecommerceanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplacecommerceanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-marketplacecommerceanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-marketplacecommerceanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-marketplacecommerceanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-marketplacecommerceanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceCommerceAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics)
+[aiobotocore.MarketplaceCommerceAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/marketplacecommerceanalytics.html#MarketplaceCommerceAnalytics)
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
 [types-aiobotocore-marketplacecommerceanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_marketplacecommerceanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,17 +297,17 @@
 `types_aiobotocore_marketplacecommerceanalytics.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_marketplacecommerceanalytics.type_defs import (
     GenerateDataSetRequestRequestTypeDef,
+    GenerateDataSetResultTypeDef,
     ResponseMetadataTypeDef,
     StartSupportDataExportRequestRequestTypeDef,
-    GenerateDataSetResultTypeDef,
     StartSupportDataExportResultTypeDef,
 )
 
 
 def get_structure() -> GenerateDataSetRequestRequestTypeDef:
     return {...}
 ```
@@ -315,43 +315,43 @@
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

### Comparing `types-aiobotocore-marketplacecommerceanalytics-2.5.0.post1/types_aiobotocore_marketplacecommerceanalytics.egg-info/SOURCES.txt` & `types-aiobotocore-marketplacecommerceanalytics-2.5.1/types_aiobotocore_marketplacecommerceanalytics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

