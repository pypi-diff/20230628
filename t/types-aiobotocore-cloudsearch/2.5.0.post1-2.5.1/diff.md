# Comparing `tmp/types-aiobotocore-cloudsearch-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudsearch-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudsearch-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:21 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudsearch-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudsearch-2.5.0.post1.tar` & `types-aiobotocore-cloudsearch-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:21.351039 types-aiobotocore-cloudsearch-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15554 2023-03-11 12:26:21.351039 types-aiobotocore-cloudsearch-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13967 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:21.351039 types-aiobotocore-cloudsearch-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:21.351039 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/
--rw-r--r--   0 runner    (1001) docker     (123)      474 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      473 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20176 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20142 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9203 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9201 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25499 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25474 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:57.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:21.351039 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15554 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.490107 types-aiobotocore-cloudsearch-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15550 2023-06-28 01:43:13.490107 types-aiobotocore-cloudsearch-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13969 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.490107 types-aiobotocore-cloudsearch-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.490107 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      473 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20176 2023-06-28 01:27:34.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20142 2023-06-28 01:27:34.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9412 2023-06-28 01:27:34.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9410 2023-06-28 01:27:34.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25551 2023-06-28 01:27:34.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25526 2023-06-28 01:27:34.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:33.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.490107 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15550 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudsearch-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudsearch-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudsearch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudSearch 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudSearch 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudsearch"></a>
 
 # types-aiobotocore-cloudsearch
 
 [![PyPI - types-aiobotocore-cloudsearch](https://img.shields.io/pypi/v/types-aiobotocore-cloudsearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudsearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudsearch?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudsearch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudSearch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
+[aiobotocore.CloudSearch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
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
 [types-aiobotocore-cloudsearch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,15 +299,15 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudsearch.type_defs import (
     OptionStatusTypeDef,
     AnalysisOptionsTypeDef,
     BuildSuggestersRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BuildSuggestersResponseTypeDef,
     CreateDomainRequestRequestTypeDef,
     DateArrayOptionsTypeDef,
     DateOptionsTypeDef,
     ExpressionTypeDef,
     DeleteAnalysisSchemeRequestRequestTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteExpressionRequestRequestTypeDef,
@@ -325,30 +325,30 @@
     DocumentSuggesterOptionsTypeDef,
     DomainEndpointOptionsTypeDef,
     LimitsTypeDef,
     ServiceEndpointTypeDef,
     DoubleArrayOptionsTypeDef,
     DoubleOptionsTypeDef,
     IndexDocumentsRequestRequestTypeDef,
+    IndexDocumentsResponseTypeDef,
     IntArrayOptionsTypeDef,
     IntOptionsTypeDef,
     LatLonOptionsTypeDef,
     LiteralArrayOptionsTypeDef,
     LiteralOptionsTypeDef,
     TextArrayOptionsTypeDef,
     TextOptionsTypeDef,
+    ListDomainNamesResponseTypeDef,
+    ResponseMetadataTypeDef,
     ScalingParametersTypeDef,
     UpdateAvailabilityOptionsRequestRequestTypeDef,
     UpdateServiceAccessPoliciesRequestRequestTypeDef,
     AccessPoliciesStatusTypeDef,
     AvailabilityOptionsStatusTypeDef,
     AnalysisSchemeTypeDef,
-    BuildSuggestersResponseTypeDef,
-    IndexDocumentsResponseTypeDef,
-    ListDomainNamesResponseTypeDef,
     DefineExpressionRequestRequestTypeDef,
     ExpressionStatusTypeDef,
     SuggesterTypeDef,
     DomainEndpointOptionsStatusTypeDef,
     UpdateDomainEndpointOptionsRequestRequestTypeDef,
     DomainStatusTypeDef,
     IndexFieldTypeDef,
@@ -393,43 +393,43 @@
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/README.md` & `types-aiobotocore-cloudsearch-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudsearch"></a>
 
 # types-aiobotocore-cloudsearch
 
 [![PyPI - types-aiobotocore-cloudsearch](https://img.shields.io/pypi/v/types-aiobotocore-cloudsearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudsearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudsearch?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudsearch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudSearch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
+[aiobotocore.CloudSearch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
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
 [types-aiobotocore-cloudsearch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -266,15 +266,15 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudsearch.type_defs import (
     OptionStatusTypeDef,
     AnalysisOptionsTypeDef,
     BuildSuggestersRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BuildSuggestersResponseTypeDef,
     CreateDomainRequestRequestTypeDef,
     DateArrayOptionsTypeDef,
     DateOptionsTypeDef,
     ExpressionTypeDef,
     DeleteAnalysisSchemeRequestRequestTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteExpressionRequestRequestTypeDef,
@@ -292,30 +292,30 @@
     DocumentSuggesterOptionsTypeDef,
     DomainEndpointOptionsTypeDef,
     LimitsTypeDef,
     ServiceEndpointTypeDef,
     DoubleArrayOptionsTypeDef,
     DoubleOptionsTypeDef,
     IndexDocumentsRequestRequestTypeDef,
+    IndexDocumentsResponseTypeDef,
     IntArrayOptionsTypeDef,
     IntOptionsTypeDef,
     LatLonOptionsTypeDef,
     LiteralArrayOptionsTypeDef,
     LiteralOptionsTypeDef,
     TextArrayOptionsTypeDef,
     TextOptionsTypeDef,
+    ListDomainNamesResponseTypeDef,
+    ResponseMetadataTypeDef,
     ScalingParametersTypeDef,
     UpdateAvailabilityOptionsRequestRequestTypeDef,
     UpdateServiceAccessPoliciesRequestRequestTypeDef,
     AccessPoliciesStatusTypeDef,
     AvailabilityOptionsStatusTypeDef,
     AnalysisSchemeTypeDef,
-    BuildSuggestersResponseTypeDef,
-    IndexDocumentsResponseTypeDef,
-    ListDomainNamesResponseTypeDef,
     DefineExpressionRequestRequestTypeDef,
     ExpressionStatusTypeDef,
     SuggesterTypeDef,
     DomainEndpointOptionsStatusTypeDef,
     UpdateDomainEndpointOptionsRequestRequestTypeDef,
     DomainStatusTypeDef,
     IndexFieldTypeDef,
@@ -360,43 +360,43 @@
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/setup.py` & `types-aiobotocore-cloudsearch-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudsearch.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudsearch",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudsearch"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudSearch 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudSearch 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/"
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/__main__.py` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudSearch 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudSearch 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch\nOther"
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/client.py` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/client.pyi` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/literals.py` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -166,14 +166,15 @@
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
@@ -252,14 +253,15 @@
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
@@ -270,14 +272,15 @@
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
@@ -313,14 +316,15 @@
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
@@ -339,16 +343,19 @@
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
@@ -432,15 +439,17 @@
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/literals.pyi` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -164,14 +164,15 @@
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
@@ -250,14 +251,15 @@
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
@@ -268,14 +270,15 @@
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
@@ -311,14 +314,15 @@
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
@@ -337,16 +341,19 @@
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
@@ -430,15 +437,17 @@
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/type_defs.py` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -31,15 +31,15 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "OptionStatusTypeDef",
     "AnalysisOptionsTypeDef",
     "BuildSuggestersRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BuildSuggestersResponseTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "DateArrayOptionsTypeDef",
     "DateOptionsTypeDef",
     "ExpressionTypeDef",
     "DeleteAnalysisSchemeRequestRequestTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DeleteExpressionRequestRequestTypeDef",
@@ -57,30 +57,30 @@
     "DocumentSuggesterOptionsTypeDef",
     "DomainEndpointOptionsTypeDef",
     "LimitsTypeDef",
     "ServiceEndpointTypeDef",
     "DoubleArrayOptionsTypeDef",
     "DoubleOptionsTypeDef",
     "IndexDocumentsRequestRequestTypeDef",
+    "IndexDocumentsResponseTypeDef",
     "IntArrayOptionsTypeDef",
     "IntOptionsTypeDef",
     "LatLonOptionsTypeDef",
     "LiteralArrayOptionsTypeDef",
     "LiteralOptionsTypeDef",
     "TextArrayOptionsTypeDef",
     "TextOptionsTypeDef",
+    "ListDomainNamesResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "ScalingParametersTypeDef",
     "UpdateAvailabilityOptionsRequestRequestTypeDef",
     "UpdateServiceAccessPoliciesRequestRequestTypeDef",
     "AccessPoliciesStatusTypeDef",
     "AvailabilityOptionsStatusTypeDef",
     "AnalysisSchemeTypeDef",
-    "BuildSuggestersResponseTypeDef",
-    "IndexDocumentsResponseTypeDef",
-    "ListDomainNamesResponseTypeDef",
     "DefineExpressionRequestRequestTypeDef",
     "ExpressionStatusTypeDef",
     "SuggesterTypeDef",
     "DomainEndpointOptionsStatusTypeDef",
     "UpdateDomainEndpointOptionsRequestRequestTypeDef",
     "DomainStatusTypeDef",
     "IndexFieldTypeDef",
@@ -154,22 +154,19 @@
 BuildSuggestersRequestRequestTypeDef = TypedDict(
     "BuildSuggestersRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BuildSuggestersResponseTypeDef = TypedDict(
+    "BuildSuggestersResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "FieldNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainRequestRequestTypeDef = TypedDict(
     "CreateDomainRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -496,14 +493,22 @@
 IndexDocumentsRequestRequestTypeDef = TypedDict(
     "IndexDocumentsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+IndexDocumentsResponseTypeDef = TypedDict(
+    "IndexDocumentsResponseTypeDef",
+    {
+        "FieldNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IntArrayOptionsTypeDef = TypedDict(
     "IntArrayOptionsTypeDef",
     {
         "DefaultValue": int,
         "SourceFields": str,
         "FacetEnabled": bool,
         "SearchEnabled": bool,
@@ -584,14 +589,33 @@
         "SortEnabled": bool,
         "HighlightEnabled": bool,
         "AnalysisScheme": str,
     },
     total=False,
 )
 
+ListDomainNamesResponseTypeDef = TypedDict(
+    "ListDomainNamesResponseTypeDef",
+    {
+        "DomainNames": Dict[str, str],
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
 ScalingParametersTypeDef = TypedDict(
     "ScalingParametersTypeDef",
     {
         "DesiredInstanceType": PartitionInstanceTypeType,
         "DesiredReplicationCount": int,
         "DesiredPartitionCount": int,
     },
@@ -646,38 +670,14 @@
 )
 
 
 class AnalysisSchemeTypeDef(_RequiredAnalysisSchemeTypeDef, _OptionalAnalysisSchemeTypeDef):
     pass
 
 
-BuildSuggestersResponseTypeDef = TypedDict(
-    "BuildSuggestersResponseTypeDef",
-    {
-        "FieldNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IndexDocumentsResponseTypeDef = TypedDict(
-    "IndexDocumentsResponseTypeDef",
-    {
-        "FieldNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainNamesResponseTypeDef = TypedDict(
-    "ListDomainNamesResponseTypeDef",
-    {
-        "DomainNames": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DefineExpressionRequestRequestTypeDef = TypedDict(
     "DefineExpressionRequestRequestTypeDef",
     {
         "DomainName": str,
         "Expression": ExpressionTypeDef,
     },
 )
@@ -790,39 +790,39 @@
     },
 )
 
 DescribeServiceAccessPoliciesResponseTypeDef = TypedDict(
     "DescribeServiceAccessPoliciesResponseTypeDef",
     {
         "AccessPolicies": AccessPoliciesStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceAccessPoliciesResponseTypeDef = TypedDict(
     "UpdateServiceAccessPoliciesResponseTypeDef",
     {
         "AccessPolicies": AccessPoliciesStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAvailabilityOptionsResponseTypeDef = TypedDict(
     "DescribeAvailabilityOptionsResponseTypeDef",
     {
         "AvailabilityOptions": AvailabilityOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAvailabilityOptionsResponseTypeDef = TypedDict(
     "UpdateAvailabilityOptionsResponseTypeDef",
     {
         "AvailabilityOptions": AvailabilityOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnalysisSchemeStatusTypeDef = TypedDict(
     "AnalysisSchemeStatusTypeDef",
     {
         "Options": AnalysisSchemeTypeDef,
@@ -838,31 +838,31 @@
     },
 )
 
 DefineExpressionResponseTypeDef = TypedDict(
     "DefineExpressionResponseTypeDef",
     {
         "Expression": ExpressionStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteExpressionResponseTypeDef = TypedDict(
     "DeleteExpressionResponseTypeDef",
     {
         "Expression": ExpressionStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExpressionsResponseTypeDef = TypedDict(
     "DescribeExpressionsResponseTypeDef",
     {
         "Expressions": List[ExpressionStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineSuggesterRequestRequestTypeDef = TypedDict(
     "DefineSuggesterRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -878,47 +878,47 @@
     },
 )
 
 DescribeDomainEndpointOptionsResponseTypeDef = TypedDict(
     "DescribeDomainEndpointOptionsResponseTypeDef",
     {
         "DomainEndpointOptions": DomainEndpointOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainEndpointOptionsResponseTypeDef = TypedDict(
     "UpdateDomainEndpointOptionsResponseTypeDef",
     {
         "DomainEndpointOptions": DomainEndpointOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainResponseTypeDef = TypedDict(
     "CreateDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResponseTypeDef = TypedDict(
     "DeleteDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainsResponseTypeDef = TypedDict(
     "DescribeDomainsResponseTypeDef",
     {
         "DomainStatusList": List[DomainStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineIndexFieldRequestRequestTypeDef = TypedDict(
     "DefineIndexFieldRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -934,90 +934,90 @@
     },
 )
 
 DescribeScalingParametersResponseTypeDef = TypedDict(
     "DescribeScalingParametersResponseTypeDef",
     {
         "ScalingParameters": ScalingParametersStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateScalingParametersResponseTypeDef = TypedDict(
     "UpdateScalingParametersResponseTypeDef",
     {
         "ScalingParameters": ScalingParametersStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineAnalysisSchemeResponseTypeDef = TypedDict(
     "DefineAnalysisSchemeResponseTypeDef",
     {
         "AnalysisScheme": AnalysisSchemeStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAnalysisSchemeResponseTypeDef = TypedDict(
     "DeleteAnalysisSchemeResponseTypeDef",
     {
         "AnalysisScheme": AnalysisSchemeStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAnalysisSchemesResponseTypeDef = TypedDict(
     "DescribeAnalysisSchemesResponseTypeDef",
     {
         "AnalysisSchemes": List[AnalysisSchemeStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineSuggesterResponseTypeDef = TypedDict(
     "DefineSuggesterResponseTypeDef",
     {
         "Suggester": SuggesterStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSuggesterResponseTypeDef = TypedDict(
     "DeleteSuggesterResponseTypeDef",
     {
         "Suggester": SuggesterStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSuggestersResponseTypeDef = TypedDict(
     "DescribeSuggestersResponseTypeDef",
     {
         "Suggesters": List[SuggesterStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineIndexFieldResponseTypeDef = TypedDict(
     "DefineIndexFieldResponseTypeDef",
     {
         "IndexField": IndexFieldStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteIndexFieldResponseTypeDef = TypedDict(
     "DeleteIndexFieldResponseTypeDef",
     {
         "IndexField": IndexFieldStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIndexFieldsResponseTypeDef = TypedDict(
     "DescribeIndexFieldsResponseTypeDef",
     {
         "IndexFields": List[IndexFieldStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch/type_defs.pyi` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,15 +30,15 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "OptionStatusTypeDef",
     "AnalysisOptionsTypeDef",
     "BuildSuggestersRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BuildSuggestersResponseTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "DateArrayOptionsTypeDef",
     "DateOptionsTypeDef",
     "ExpressionTypeDef",
     "DeleteAnalysisSchemeRequestRequestTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DeleteExpressionRequestRequestTypeDef",
@@ -56,30 +56,30 @@
     "DocumentSuggesterOptionsTypeDef",
     "DomainEndpointOptionsTypeDef",
     "LimitsTypeDef",
     "ServiceEndpointTypeDef",
     "DoubleArrayOptionsTypeDef",
     "DoubleOptionsTypeDef",
     "IndexDocumentsRequestRequestTypeDef",
+    "IndexDocumentsResponseTypeDef",
     "IntArrayOptionsTypeDef",
     "IntOptionsTypeDef",
     "LatLonOptionsTypeDef",
     "LiteralArrayOptionsTypeDef",
     "LiteralOptionsTypeDef",
     "TextArrayOptionsTypeDef",
     "TextOptionsTypeDef",
+    "ListDomainNamesResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "ScalingParametersTypeDef",
     "UpdateAvailabilityOptionsRequestRequestTypeDef",
     "UpdateServiceAccessPoliciesRequestRequestTypeDef",
     "AccessPoliciesStatusTypeDef",
     "AvailabilityOptionsStatusTypeDef",
     "AnalysisSchemeTypeDef",
-    "BuildSuggestersResponseTypeDef",
-    "IndexDocumentsResponseTypeDef",
-    "ListDomainNamesResponseTypeDef",
     "DefineExpressionRequestRequestTypeDef",
     "ExpressionStatusTypeDef",
     "SuggesterTypeDef",
     "DomainEndpointOptionsStatusTypeDef",
     "UpdateDomainEndpointOptionsRequestRequestTypeDef",
     "DomainStatusTypeDef",
     "IndexFieldTypeDef",
@@ -151,22 +151,19 @@
 BuildSuggestersRequestRequestTypeDef = TypedDict(
     "BuildSuggestersRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BuildSuggestersResponseTypeDef = TypedDict(
+    "BuildSuggestersResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "FieldNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainRequestRequestTypeDef = TypedDict(
     "CreateDomainRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -477,14 +474,22 @@
 IndexDocumentsRequestRequestTypeDef = TypedDict(
     "IndexDocumentsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+IndexDocumentsResponseTypeDef = TypedDict(
+    "IndexDocumentsResponseTypeDef",
+    {
+        "FieldNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IntArrayOptionsTypeDef = TypedDict(
     "IntArrayOptionsTypeDef",
     {
         "DefaultValue": int,
         "SourceFields": str,
         "FacetEnabled": bool,
         "SearchEnabled": bool,
@@ -565,14 +570,33 @@
         "SortEnabled": bool,
         "HighlightEnabled": bool,
         "AnalysisScheme": str,
     },
     total=False,
 )
 
+ListDomainNamesResponseTypeDef = TypedDict(
+    "ListDomainNamesResponseTypeDef",
+    {
+        "DomainNames": Dict[str, str],
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
 ScalingParametersTypeDef = TypedDict(
     "ScalingParametersTypeDef",
     {
         "DesiredInstanceType": PartitionInstanceTypeType,
         "DesiredReplicationCount": int,
         "DesiredPartitionCount": int,
     },
@@ -625,38 +649,14 @@
     },
     total=False,
 )
 
 class AnalysisSchemeTypeDef(_RequiredAnalysisSchemeTypeDef, _OptionalAnalysisSchemeTypeDef):
     pass
 
-BuildSuggestersResponseTypeDef = TypedDict(
-    "BuildSuggestersResponseTypeDef",
-    {
-        "FieldNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IndexDocumentsResponseTypeDef = TypedDict(
-    "IndexDocumentsResponseTypeDef",
-    {
-        "FieldNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainNamesResponseTypeDef = TypedDict(
-    "ListDomainNamesResponseTypeDef",
-    {
-        "DomainNames": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DefineExpressionRequestRequestTypeDef = TypedDict(
     "DefineExpressionRequestRequestTypeDef",
     {
         "DomainName": str,
         "Expression": ExpressionTypeDef,
     },
 )
@@ -765,39 +765,39 @@
     },
 )
 
 DescribeServiceAccessPoliciesResponseTypeDef = TypedDict(
     "DescribeServiceAccessPoliciesResponseTypeDef",
     {
         "AccessPolicies": AccessPoliciesStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceAccessPoliciesResponseTypeDef = TypedDict(
     "UpdateServiceAccessPoliciesResponseTypeDef",
     {
         "AccessPolicies": AccessPoliciesStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAvailabilityOptionsResponseTypeDef = TypedDict(
     "DescribeAvailabilityOptionsResponseTypeDef",
     {
         "AvailabilityOptions": AvailabilityOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAvailabilityOptionsResponseTypeDef = TypedDict(
     "UpdateAvailabilityOptionsResponseTypeDef",
     {
         "AvailabilityOptions": AvailabilityOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnalysisSchemeStatusTypeDef = TypedDict(
     "AnalysisSchemeStatusTypeDef",
     {
         "Options": AnalysisSchemeTypeDef,
@@ -813,31 +813,31 @@
     },
 )
 
 DefineExpressionResponseTypeDef = TypedDict(
     "DefineExpressionResponseTypeDef",
     {
         "Expression": ExpressionStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteExpressionResponseTypeDef = TypedDict(
     "DeleteExpressionResponseTypeDef",
     {
         "Expression": ExpressionStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExpressionsResponseTypeDef = TypedDict(
     "DescribeExpressionsResponseTypeDef",
     {
         "Expressions": List[ExpressionStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineSuggesterRequestRequestTypeDef = TypedDict(
     "DefineSuggesterRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -853,47 +853,47 @@
     },
 )
 
 DescribeDomainEndpointOptionsResponseTypeDef = TypedDict(
     "DescribeDomainEndpointOptionsResponseTypeDef",
     {
         "DomainEndpointOptions": DomainEndpointOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainEndpointOptionsResponseTypeDef = TypedDict(
     "UpdateDomainEndpointOptionsResponseTypeDef",
     {
         "DomainEndpointOptions": DomainEndpointOptionsStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainResponseTypeDef = TypedDict(
     "CreateDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResponseTypeDef = TypedDict(
     "DeleteDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainsResponseTypeDef = TypedDict(
     "DescribeDomainsResponseTypeDef",
     {
         "DomainStatusList": List[DomainStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineIndexFieldRequestRequestTypeDef = TypedDict(
     "DefineIndexFieldRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -909,90 +909,90 @@
     },
 )
 
 DescribeScalingParametersResponseTypeDef = TypedDict(
     "DescribeScalingParametersResponseTypeDef",
     {
         "ScalingParameters": ScalingParametersStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateScalingParametersResponseTypeDef = TypedDict(
     "UpdateScalingParametersResponseTypeDef",
     {
         "ScalingParameters": ScalingParametersStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineAnalysisSchemeResponseTypeDef = TypedDict(
     "DefineAnalysisSchemeResponseTypeDef",
     {
         "AnalysisScheme": AnalysisSchemeStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAnalysisSchemeResponseTypeDef = TypedDict(
     "DeleteAnalysisSchemeResponseTypeDef",
     {
         "AnalysisScheme": AnalysisSchemeStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAnalysisSchemesResponseTypeDef = TypedDict(
     "DescribeAnalysisSchemesResponseTypeDef",
     {
         "AnalysisSchemes": List[AnalysisSchemeStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineSuggesterResponseTypeDef = TypedDict(
     "DefineSuggesterResponseTypeDef",
     {
         "Suggester": SuggesterStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSuggesterResponseTypeDef = TypedDict(
     "DeleteSuggesterResponseTypeDef",
     {
         "Suggester": SuggesterStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSuggestersResponseTypeDef = TypedDict(
     "DescribeSuggestersResponseTypeDef",
     {
         "Suggesters": List[SuggesterStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DefineIndexFieldResponseTypeDef = TypedDict(
     "DefineIndexFieldResponseTypeDef",
     {
         "IndexField": IndexFieldStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteIndexFieldResponseTypeDef = TypedDict(
     "DeleteIndexFieldResponseTypeDef",
     {
         "IndexField": IndexFieldStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIndexFieldsResponseTypeDef = TypedDict(
     "DescribeIndexFieldsResponseTypeDef",
     {
         "IndexFields": List[IndexFieldStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/PKG-INFO` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudsearch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudSearch 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudSearch 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudsearch"></a>
 
 # types-aiobotocore-cloudsearch
 
 [![PyPI - types-aiobotocore-cloudsearch](https://img.shields.io/pypi/v/types-aiobotocore-cloudsearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudsearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudsearch?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudsearch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudSearch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
+[aiobotocore.CloudSearch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
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
 [types-aiobotocore-cloudsearch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,15 +299,15 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudsearch.type_defs import (
     OptionStatusTypeDef,
     AnalysisOptionsTypeDef,
     BuildSuggestersRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BuildSuggestersResponseTypeDef,
     CreateDomainRequestRequestTypeDef,
     DateArrayOptionsTypeDef,
     DateOptionsTypeDef,
     ExpressionTypeDef,
     DeleteAnalysisSchemeRequestRequestTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteExpressionRequestRequestTypeDef,
@@ -325,30 +325,30 @@
     DocumentSuggesterOptionsTypeDef,
     DomainEndpointOptionsTypeDef,
     LimitsTypeDef,
     ServiceEndpointTypeDef,
     DoubleArrayOptionsTypeDef,
     DoubleOptionsTypeDef,
     IndexDocumentsRequestRequestTypeDef,
+    IndexDocumentsResponseTypeDef,
     IntArrayOptionsTypeDef,
     IntOptionsTypeDef,
     LatLonOptionsTypeDef,
     LiteralArrayOptionsTypeDef,
     LiteralOptionsTypeDef,
     TextArrayOptionsTypeDef,
     TextOptionsTypeDef,
+    ListDomainNamesResponseTypeDef,
+    ResponseMetadataTypeDef,
     ScalingParametersTypeDef,
     UpdateAvailabilityOptionsRequestRequestTypeDef,
     UpdateServiceAccessPoliciesRequestRequestTypeDef,
     AccessPoliciesStatusTypeDef,
     AvailabilityOptionsStatusTypeDef,
     AnalysisSchemeTypeDef,
-    BuildSuggestersResponseTypeDef,
-    IndexDocumentsResponseTypeDef,
-    ListDomainNamesResponseTypeDef,
     DefineExpressionRequestRequestTypeDef,
     ExpressionStatusTypeDef,
     SuggesterTypeDef,
     DomainEndpointOptionsStatusTypeDef,
     UpdateDomainEndpointOptionsRequestRequestTypeDef,
     DomainStatusTypeDef,
     IndexFieldTypeDef,
@@ -393,43 +393,43 @@
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

### Comparing `types-aiobotocore-cloudsearch-2.5.0.post1/types_aiobotocore_cloudsearch.egg-info/SOURCES.txt` & `types-aiobotocore-cloudsearch-2.5.1/types_aiobotocore_cloudsearch.egg-info/SOURCES.txt`

 * *Files identical despite different names*

