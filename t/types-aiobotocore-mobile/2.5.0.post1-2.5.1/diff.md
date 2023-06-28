# Comparing `tmp/types-aiobotocore-mobile-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mobile-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mobile-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-mobile-2.5.1.tar", last modified: Wed Jun 28 01:43:53 2023, max compression
```

## Comparing `types-aiobotocore-mobile-2.5.0.post1.tar` & `types-aiobotocore-mobile-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.579445 types-aiobotocore-mobile-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13795 2023-03-11 12:27:01.575445 types-aiobotocore-mobile-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12228 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.579445 types-aiobotocore-mobile-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.571445 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/
--rw-r--r--   0 runner    (1001) docker     (123)      791 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      790 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10305 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    10285 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7766 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7764 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3061 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3056 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     7660 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7653 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:54.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.575445 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13795 2023-03-11 12:27:01.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:27:01.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:01.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:01.000000 types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.542182 types-aiobotocore-mobile-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13786 2023-06-28 01:43:53.542182 types-aiobotocore-mobile-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12225 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:53.542182 types-aiobotocore-mobile-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.542182 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/
+-rw-r--r--   0 runner    (1001) docker     (123)      791 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      790 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10305 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10285 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7975 2023-06-28 01:35:40.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7973 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2945 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2941 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     7682 2023-06-28 01:35:40.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7675 2023-06-28 01:35:40.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:38.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.542182 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13786 2023-06-28 01:43:53.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:53.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:53.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:53.000000 types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mobile-2.5.0.post1/LICENSE` & `types-aiobotocore-mobile-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mobile-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mobile
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Mobile 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Mobile 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mobile"></a>
 
 # types-aiobotocore-mobile
 
 [![PyPI - types-aiobotocore-mobile](https://img.shields.io/pypi/v/types-aiobotocore-mobile.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mobile)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mobile.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mobile)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mobile?color=blue)](https://pypistats.org/packages/types-aiobotocore-mobile)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Mobile 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile)
+[aiobotocore.Mobile 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile)
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
 [types-aiobotocore-mobile docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,34 +318,34 @@
 `types_aiobotocore_mobile.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mobile.type_defs import (
     BundleDetailsTypeDef,
     CreateProjectRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DeleteProjectRequestRequestTypeDef,
     ResourceTypeDef,
     DescribeBundleRequestRequestTypeDef,
     DescribeProjectRequestRequestTypeDef,
     ExportBundleRequestRequestTypeDef,
+    ExportBundleResultTypeDef,
     ExportProjectRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ExportProjectResultTypeDef,
+    ListBundlesRequestListBundlesPaginateTypeDef,
     ListBundlesRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateProjectRequestRequestTypeDef,
     DescribeBundleResultTypeDef,
-    ExportBundleResultTypeDef,
-    ExportProjectResultTypeDef,
     ListBundlesResultTypeDef,
     DeleteProjectResultTypeDef,
     ProjectDetailsTypeDef,
-    ListBundlesRequestListBundlesPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsResultTypeDef,
     CreateProjectResultTypeDef,
     DescribeProjectResultTypeDef,
     UpdateProjectResultTypeDef,
 )
 
 
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/README.md` & `types-aiobotocore-mobile-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mobile"></a>
 
 # types-aiobotocore-mobile
 
 [![PyPI - types-aiobotocore-mobile](https://img.shields.io/pypi/v/types-aiobotocore-mobile.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mobile)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mobile.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mobile)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mobile?color=blue)](https://pypistats.org/packages/types-aiobotocore-mobile)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Mobile 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile)
+[aiobotocore.Mobile 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile)
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
 [types-aiobotocore-mobile docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/).
 
 See how it helps to find and fix potential bugs:
 
@@ -285,34 +285,34 @@
 `types_aiobotocore_mobile.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mobile.type_defs import (
     BundleDetailsTypeDef,
     CreateProjectRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DeleteProjectRequestRequestTypeDef,
     ResourceTypeDef,
     DescribeBundleRequestRequestTypeDef,
     DescribeProjectRequestRequestTypeDef,
     ExportBundleRequestRequestTypeDef,
+    ExportBundleResultTypeDef,
     ExportProjectRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ExportProjectResultTypeDef,
+    ListBundlesRequestListBundlesPaginateTypeDef,
     ListBundlesRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateProjectRequestRequestTypeDef,
     DescribeBundleResultTypeDef,
-    ExportBundleResultTypeDef,
-    ExportProjectResultTypeDef,
     ListBundlesResultTypeDef,
     DeleteProjectResultTypeDef,
     ProjectDetailsTypeDef,
-    ListBundlesRequestListBundlesPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsResultTypeDef,
     CreateProjectResultTypeDef,
     DescribeProjectResultTypeDef,
     UpdateProjectResultTypeDef,
 )
 
 
@@ -323,43 +323,43 @@
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/setup.py` & `types-aiobotocore-mobile-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mobile.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mobile",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mobile"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Mobile 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Mobile 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/"
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/__init__.py` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/__init__.pyi` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/__main__.py` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Mobile 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Mobile 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile\nOther"
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/client.py` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/client.pyi` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/literals.py` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -94,14 +94,15 @@
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
@@ -180,14 +181,15 @@
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
@@ -198,14 +200,15 @@
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
@@ -241,14 +244,15 @@
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
@@ -267,16 +271,19 @@
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
@@ -360,15 +367,17 @@
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/literals.pyi` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -92,14 +92,15 @@
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
@@ -178,14 +179,15 @@
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
@@ -196,14 +198,15 @@
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
@@ -239,14 +242,15 @@
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
@@ -265,16 +269,19 @@
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
@@ -358,15 +365,17 @@
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/paginator.py` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,28 +18,21 @@
     with session.create_client("mobile") as client:
         client: MobileClient
 
         list_bundles_paginator: ListBundlesPaginator = client.get_paginator("list_bundles")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListBundlesResultTypeDef, ListProjectsResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListBundlesPaginator", "ListProjectsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -52,28 +45,28 @@
 class ListBundlesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListBundles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listbundlespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBundlesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListBundles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listbundlespaginator)
         """
 
 
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listprojectspaginator)
         """
```

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/paginator.pyi` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/paginator.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -18,27 +18,21 @@
     with session.create_client("mobile") as client:
         client: MobileClient
 
         list_bundles_paginator: ListBundlesPaginator = client.get_paginator("list_bundles")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListBundlesResultTypeDef, ListProjectsResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListBundlesPaginator", "ListProjectsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -48,27 +42,27 @@
 class ListBundlesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListBundles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listbundlespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBundlesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListBundles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listbundlespaginator)
         """
 
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/paginators/#listprojectspaginator)
         """
```

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/type_defs.py` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,34 +24,34 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BundleDetailsTypeDef",
     "CreateProjectRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteProjectRequestRequestTypeDef",
     "ResourceTypeDef",
     "DescribeBundleRequestRequestTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "ExportBundleRequestRequestTypeDef",
+    "ExportBundleResultTypeDef",
     "ExportProjectRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ExportProjectResultTypeDef",
+    "ListBundlesRequestListBundlesPaginateTypeDef",
     "ListBundlesRequestRequestTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "DescribeBundleResultTypeDef",
-    "ExportBundleResultTypeDef",
-    "ExportProjectResultTypeDef",
     "ListBundlesResultTypeDef",
     "DeleteProjectResultTypeDef",
     "ProjectDetailsTypeDef",
-    "ListBundlesRequestListBundlesPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsResultTypeDef",
     "CreateProjectResultTypeDef",
     "DescribeProjectResultTypeDef",
     "UpdateProjectResultTypeDef",
 )
 
 BundleDetailsTypeDef = TypedDict(
@@ -74,25 +74,14 @@
         "region": str,
         "contents": Union[str, bytes, IO[Any], StreamingBody],
         "snapshotId": str,
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
 DeleteProjectRequestRequestTypeDef = TypedDict(
     "DeleteProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 
@@ -154,40 +143,64 @@
 
 class ExportBundleRequestRequestTypeDef(
     _RequiredExportBundleRequestRequestTypeDef, _OptionalExportBundleRequestRequestTypeDef
 ):
     pass
 
 
+ExportBundleResultTypeDef = TypedDict(
+    "ExportBundleResultTypeDef",
+    {
+        "downloadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportProjectRequestRequestTypeDef = TypedDict(
     "ExportProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ExportProjectResultTypeDef = TypedDict(
+    "ExportProjectResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "downloadUrl": str,
+        "shareUrl": str,
+        "snapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBundlesRequestListBundlesPaginateTypeDef = TypedDict(
+    "ListBundlesRequestListBundlesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBundlesRequestRequestTypeDef = TypedDict(
     "ListBundlesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -198,14 +211,35 @@
     {
         "name": str,
         "projectId": str,
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
 _RequiredUpdateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalUpdateProjectRequestRequestTypeDef = TypedDict(
@@ -223,51 +257,33 @@
     pass
 
 
 DescribeBundleResultTypeDef = TypedDict(
     "DescribeBundleResultTypeDef",
     {
         "details": BundleDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportBundleResultTypeDef = TypedDict(
-    "ExportBundleResultTypeDef",
-    {
-        "downloadUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportProjectResultTypeDef = TypedDict(
-    "ExportProjectResultTypeDef",
-    {
-        "downloadUrl": str,
-        "shareUrl": str,
-        "snapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBundlesResultTypeDef = TypedDict(
     "ListBundlesResultTypeDef",
     {
         "bundleList": List[BundleDetailsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteProjectResultTypeDef = TypedDict(
     "DeleteProjectResultTypeDef",
     {
         "deletedResources": List[ResourceTypeDef],
         "orphanedResources": List[ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProjectDetailsTypeDef = TypedDict(
     "ProjectDetailsTypeDef",
     {
         "name": str,
@@ -278,55 +294,39 @@
         "lastUpdatedDate": datetime,
         "consoleUrl": str,
         "resources": List[ResourceTypeDef],
     },
     total=False,
 )
 
-ListBundlesRequestListBundlesPaginateTypeDef = TypedDict(
-    "ListBundlesRequestListBundlesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListProjectsResultTypeDef = TypedDict(
     "ListProjectsResultTypeDef",
     {
         "projects": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProjectResultTypeDef = TypedDict(
     "CreateProjectResultTypeDef",
     {
         "details": ProjectDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProjectResultTypeDef = TypedDict(
     "DescribeProjectResultTypeDef",
     {
         "details": ProjectDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProjectResultTypeDef = TypedDict(
     "UpdateProjectResultTypeDef",
     {
         "details": ProjectDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile/type_defs.pyi` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -23,34 +23,34 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BundleDetailsTypeDef",
     "CreateProjectRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteProjectRequestRequestTypeDef",
     "ResourceTypeDef",
     "DescribeBundleRequestRequestTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "ExportBundleRequestRequestTypeDef",
+    "ExportBundleResultTypeDef",
     "ExportProjectRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ExportProjectResultTypeDef",
+    "ListBundlesRequestListBundlesPaginateTypeDef",
     "ListBundlesRequestRequestTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "DescribeBundleResultTypeDef",
-    "ExportBundleResultTypeDef",
-    "ExportProjectResultTypeDef",
     "ListBundlesResultTypeDef",
     "DeleteProjectResultTypeDef",
     "ProjectDetailsTypeDef",
-    "ListBundlesRequestListBundlesPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsResultTypeDef",
     "CreateProjectResultTypeDef",
     "DescribeProjectResultTypeDef",
     "UpdateProjectResultTypeDef",
 )
 
 BundleDetailsTypeDef = TypedDict(
@@ -73,25 +73,14 @@
         "region": str,
         "contents": Union[str, bytes, IO[Any], StreamingBody],
         "snapshotId": str,
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
 DeleteProjectRequestRequestTypeDef = TypedDict(
     "DeleteProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 
@@ -149,40 +138,64 @@
 )
 
 class ExportBundleRequestRequestTypeDef(
     _RequiredExportBundleRequestRequestTypeDef, _OptionalExportBundleRequestRequestTypeDef
 ):
     pass
 
+ExportBundleResultTypeDef = TypedDict(
+    "ExportBundleResultTypeDef",
+    {
+        "downloadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportProjectRequestRequestTypeDef = TypedDict(
     "ExportProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ExportProjectResultTypeDef = TypedDict(
+    "ExportProjectResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "downloadUrl": str,
+        "shareUrl": str,
+        "snapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBundlesRequestListBundlesPaginateTypeDef = TypedDict(
+    "ListBundlesRequestListBundlesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBundlesRequestRequestTypeDef = TypedDict(
     "ListBundlesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -193,14 +206,35 @@
     {
         "name": str,
         "projectId": str,
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
 _RequiredUpdateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalUpdateProjectRequestRequestTypeDef = TypedDict(
@@ -216,51 +250,33 @@
 ):
     pass
 
 DescribeBundleResultTypeDef = TypedDict(
     "DescribeBundleResultTypeDef",
     {
         "details": BundleDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportBundleResultTypeDef = TypedDict(
-    "ExportBundleResultTypeDef",
-    {
-        "downloadUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportProjectResultTypeDef = TypedDict(
-    "ExportProjectResultTypeDef",
-    {
-        "downloadUrl": str,
-        "shareUrl": str,
-        "snapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBundlesResultTypeDef = TypedDict(
     "ListBundlesResultTypeDef",
     {
         "bundleList": List[BundleDetailsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteProjectResultTypeDef = TypedDict(
     "DeleteProjectResultTypeDef",
     {
         "deletedResources": List[ResourceTypeDef],
         "orphanedResources": List[ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProjectDetailsTypeDef = TypedDict(
     "ProjectDetailsTypeDef",
     {
         "name": str,
@@ -271,55 +287,39 @@
         "lastUpdatedDate": datetime,
         "consoleUrl": str,
         "resources": List[ResourceTypeDef],
     },
     total=False,
 )
 
-ListBundlesRequestListBundlesPaginateTypeDef = TypedDict(
-    "ListBundlesRequestListBundlesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListProjectsResultTypeDef = TypedDict(
     "ListProjectsResultTypeDef",
     {
         "projects": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProjectResultTypeDef = TypedDict(
     "CreateProjectResultTypeDef",
     {
         "details": ProjectDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProjectResultTypeDef = TypedDict(
     "DescribeProjectResultTypeDef",
     {
         "details": ProjectDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProjectResultTypeDef = TypedDict(
     "UpdateProjectResultTypeDef",
     {
         "details": ProjectDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/PKG-INFO` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mobile
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Mobile 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Mobile 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mobile"></a>
 
 # types-aiobotocore-mobile
 
 [![PyPI - types-aiobotocore-mobile](https://img.shields.io/pypi/v/types-aiobotocore-mobile.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mobile)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mobile.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mobile)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mobile?color=blue)](https://pypistats.org/packages/types-aiobotocore-mobile)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Mobile 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile)
+[aiobotocore.Mobile 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mobile.html#Mobile)
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
 [types-aiobotocore-mobile docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mobile/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,34 +318,34 @@
 `types_aiobotocore_mobile.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mobile.type_defs import (
     BundleDetailsTypeDef,
     CreateProjectRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DeleteProjectRequestRequestTypeDef,
     ResourceTypeDef,
     DescribeBundleRequestRequestTypeDef,
     DescribeProjectRequestRequestTypeDef,
     ExportBundleRequestRequestTypeDef,
+    ExportBundleResultTypeDef,
     ExportProjectRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ExportProjectResultTypeDef,
+    ListBundlesRequestListBundlesPaginateTypeDef,
     ListBundlesRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateProjectRequestRequestTypeDef,
     DescribeBundleResultTypeDef,
-    ExportBundleResultTypeDef,
-    ExportProjectResultTypeDef,
     ListBundlesResultTypeDef,
     DeleteProjectResultTypeDef,
     ProjectDetailsTypeDef,
-    ListBundlesRequestListBundlesPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsResultTypeDef,
     CreateProjectResultTypeDef,
     DescribeProjectResultTypeDef,
     UpdateProjectResultTypeDef,
 )
 
 
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-mobile-2.5.0.post1/types_aiobotocore_mobile.egg-info/SOURCES.txt` & `types-aiobotocore-mobile-2.5.1/types_aiobotocore_mobile.egg-info/SOURCES.txt`

 * *Files identical despite different names*

