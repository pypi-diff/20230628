# Comparing `tmp/types-aiobotocore-applicationcostprofiler-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-applicationcostprofiler-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-applicationcostprofiler-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-applicationcostprofiler-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1.tar` & `types-aiobotocore-applicationcostprofiler-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.714948 types-aiobotocore-applicationcostprofiler-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14513 2023-03-11 12:26:12.714948 types-aiobotocore-applicationcostprofiler-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12878 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.714948 types-aiobotocore-applicationcostprofiler-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2239 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.714948 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      818 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1007 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9517 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9501 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7824 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7822 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2389 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2385 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5663 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5660 2023-03-11 12:09:38.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:37.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.714948 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14513 2023-03-11 12:26:12.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-03-11 12:26:12.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-03-11 12:26:12.000000 types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.514094 types-aiobotocore-applicationcostprofiler-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14521 2023-06-28 01:43:06.514094 types-aiobotocore-applicationcostprofiler-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12892 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.514094 types-aiobotocore-applicationcostprofiler-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2233 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.510094 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      818 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      995 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9517 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9501 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8033 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8031 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2268 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5677 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5674 2023-06-28 01:26:15.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:14.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.514094 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14521 2023-06-28 01:43:06.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-06-28 01:43:06.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 01:43:06.000000 types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/LICENSE` & `types-aiobotocore-applicationcostprofiler-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/PKG-INFO` & `types-aiobotocore-applicationcostprofiler-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-applicationcostprofiler
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationCostProfiler 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationCostProfiler 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-applicationcostprofiler"></a>
 
 # types-aiobotocore-applicationcostprofiler
 
 [![PyPI - types-aiobotocore-applicationcostprofiler](https://img.shields.io/pypi/v/types-aiobotocore-applicationcostprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-applicationcostprofiler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-applicationcostprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-applicationcostprofiler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-applicationcostprofiler?color=blue)](https://pypistats.org/packages/types-aiobotocore-applicationcostprofiler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationCostProfiler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler)
+[aiobotocore.ApplicationCostProfiler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler)
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
 [types-aiobotocore-applicationcostprofiler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,30 +320,30 @@
 `types_aiobotocore_applicationcostprofiler.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_applicationcostprofiler.type_defs import (
     DeleteReportDefinitionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteReportDefinitionResultTypeDef,
     GetReportDefinitionRequestRequestTypeDef,
     S3LocationTypeDef,
     SourceS3LocationTypeDef,
-    PaginatorConfigTypeDef,
-    ListReportDefinitionsRequestRequestTypeDef,
-    DeleteReportDefinitionResultTypeDef,
     ImportApplicationUsageResultTypeDef,
+    ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef,
+    ListReportDefinitionsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutReportDefinitionResultTypeDef,
+    ResponseMetadataTypeDef,
     UpdateReportDefinitionResultTypeDef,
     GetReportDefinitionResultTypeDef,
     PutReportDefinitionRequestRequestTypeDef,
     ReportDefinitionTypeDef,
     UpdateReportDefinitionRequestRequestTypeDef,
     ImportApplicationUsageRequestRequestTypeDef,
-    ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef,
     ListReportDefinitionsResultTypeDef,
 )
 
 
 def get_structure() -> DeleteReportDefinitionRequestRequestTypeDef:
     return {...}
 ```
@@ -351,43 +351,43 @@
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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/README.md` & `types-aiobotocore-applicationcostprofiler-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-applicationcostprofiler"></a>
 
 # types-aiobotocore-applicationcostprofiler
 
 [![PyPI - types-aiobotocore-applicationcostprofiler](https://img.shields.io/pypi/v/types-aiobotocore-applicationcostprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-applicationcostprofiler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-applicationcostprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-applicationcostprofiler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-applicationcostprofiler?color=blue)](https://pypistats.org/packages/types-aiobotocore-applicationcostprofiler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationCostProfiler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler)
+[aiobotocore.ApplicationCostProfiler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler)
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
 [types-aiobotocore-applicationcostprofiler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,30 +287,30 @@
 `types_aiobotocore_applicationcostprofiler.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_applicationcostprofiler.type_defs import (
     DeleteReportDefinitionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteReportDefinitionResultTypeDef,
     GetReportDefinitionRequestRequestTypeDef,
     S3LocationTypeDef,
     SourceS3LocationTypeDef,
-    PaginatorConfigTypeDef,
-    ListReportDefinitionsRequestRequestTypeDef,
-    DeleteReportDefinitionResultTypeDef,
     ImportApplicationUsageResultTypeDef,
+    ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef,
+    ListReportDefinitionsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutReportDefinitionResultTypeDef,
+    ResponseMetadataTypeDef,
     UpdateReportDefinitionResultTypeDef,
     GetReportDefinitionResultTypeDef,
     PutReportDefinitionRequestRequestTypeDef,
     ReportDefinitionTypeDef,
     UpdateReportDefinitionRequestRequestTypeDef,
     ImportApplicationUsageRequestRequestTypeDef,
-    ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef,
     ListReportDefinitionsResultTypeDef,
 )
 
 
 def get_structure() -> DeleteReportDefinitionRequestRequestTypeDef:
     return {...}
 ```
@@ -318,43 +318,43 @@
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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/setup.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-applicationcostprofiler.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-applicationcostprofiler",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_applicationcostprofiler"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ApplicationCostProfiler 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ApplicationCostProfiler 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/",
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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/__init__.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/__init__.pyi` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/__main__.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ApplicationCostProfiler 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ApplicationCostProfiler 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler\nOther"
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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/client.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/client.pyi` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/literals.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/literals.py`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/literals.pyi` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/literals.pyi`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/paginator.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -16,47 +16,37 @@
     session = get_session()
     with session.create_client("applicationcostprofiler") as client:
         client: ApplicationCostProfilerClient
 
         list_report_definitions_paginator: ListReportDefinitionsPaginator = client.get_paginator("list_report_definitions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListReportDefinitionsResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListReportDefinitionsPaginator",)
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListReportDefinitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler.Paginator.ListReportDefinitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/paginators/#listreportdefinitionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportDefinitionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler.Paginator.ListReportDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/paginators/#listreportdefinitionspaginator)
         """
```

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/paginator.pyi` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,43 +16,40 @@
     session = get_session()
     with session.create_client("applicationcostprofiler") as client:
         client: ApplicationCostProfilerClient
 
         list_report_definitions_paginator: ListReportDefinitionsPaginator = client.get_paginator("list_report_definitions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListReportDefinitionsResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListReportDefinitionsPaginator",)
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListReportDefinitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler.Paginator.ListReportDefinitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/paginators/#listreportdefinitionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportDefinitionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler.Paginator.ListReportDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/paginators/#listreportdefinitionspaginator)
         """
```

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/type_defs.py` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -21,48 +21,45 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DeleteReportDefinitionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteReportDefinitionResultTypeDef",
     "GetReportDefinitionRequestRequestTypeDef",
     "S3LocationTypeDef",
     "SourceS3LocationTypeDef",
-    "PaginatorConfigTypeDef",
-    "ListReportDefinitionsRequestRequestTypeDef",
-    "DeleteReportDefinitionResultTypeDef",
     "ImportApplicationUsageResultTypeDef",
+    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
+    "ListReportDefinitionsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutReportDefinitionResultTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateReportDefinitionResultTypeDef",
     "GetReportDefinitionResultTypeDef",
     "PutReportDefinitionRequestRequestTypeDef",
     "ReportDefinitionTypeDef",
     "UpdateReportDefinitionRequestRequestTypeDef",
     "ImportApplicationUsageRequestRequestTypeDef",
-    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
     "ListReportDefinitionsResultTypeDef",
 )
 
 DeleteReportDefinitionRequestRequestTypeDef = TypedDict(
     "DeleteReportDefinitionRequestRequestTypeDef",
     {
         "reportId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteReportDefinitionResultTypeDef = TypedDict(
+    "DeleteReportDefinitionResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "reportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReportDefinitionRequestRequestTypeDef = TypedDict(
     "GetReportDefinitionRequestRequestTypeDef",
     {
         "reportId": str,
@@ -93,76 +90,87 @@
 )
 
 
 class SourceS3LocationTypeDef(_RequiredSourceS3LocationTypeDef, _OptionalSourceS3LocationTypeDef):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ImportApplicationUsageResultTypeDef = TypedDict(
+    "ImportApplicationUsageResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "importId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef = TypedDict(
+    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListReportDefinitionsRequestRequestTypeDef = TypedDict(
     "ListReportDefinitionsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-DeleteReportDefinitionResultTypeDef = TypedDict(
-    "DeleteReportDefinitionResultTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "reportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-ImportApplicationUsageResultTypeDef = TypedDict(
-    "ImportApplicationUsageResultTypeDef",
+PutReportDefinitionResultTypeDef = TypedDict(
+    "PutReportDefinitionResultTypeDef",
     {
-        "importId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "reportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutReportDefinitionResultTypeDef = TypedDict(
-    "PutReportDefinitionResultTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "reportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 UpdateReportDefinitionResultTypeDef = TypedDict(
     "UpdateReportDefinitionResultTypeDef",
     {
         "reportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReportDefinitionResultTypeDef = TypedDict(
     "GetReportDefinitionResultTypeDef",
     {
         "reportId": str,
         "reportDescription": str,
         "reportFrequency": ReportFrequencyType,
         "format": FormatType,
         "destinationS3Location": S3LocationTypeDef,
         "createdAt": datetime,
         "lastUpdated": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutReportDefinitionRequestRequestTypeDef = TypedDict(
     "PutReportDefinitionRequestRequestTypeDef",
     {
         "reportId": str,
@@ -201,23 +209,15 @@
 ImportApplicationUsageRequestRequestTypeDef = TypedDict(
     "ImportApplicationUsageRequestRequestTypeDef",
     {
         "sourceS3Location": SourceS3LocationTypeDef,
     },
 )
 
-ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef = TypedDict(
-    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListReportDefinitionsResultTypeDef = TypedDict(
     "ListReportDefinitionsResultTypeDef",
     {
         "reportDefinitions": List[ReportDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler/type_defs.pyi` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -20,48 +20,45 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DeleteReportDefinitionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteReportDefinitionResultTypeDef",
     "GetReportDefinitionRequestRequestTypeDef",
     "S3LocationTypeDef",
     "SourceS3LocationTypeDef",
-    "PaginatorConfigTypeDef",
-    "ListReportDefinitionsRequestRequestTypeDef",
-    "DeleteReportDefinitionResultTypeDef",
     "ImportApplicationUsageResultTypeDef",
+    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
+    "ListReportDefinitionsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutReportDefinitionResultTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateReportDefinitionResultTypeDef",
     "GetReportDefinitionResultTypeDef",
     "PutReportDefinitionRequestRequestTypeDef",
     "ReportDefinitionTypeDef",
     "UpdateReportDefinitionRequestRequestTypeDef",
     "ImportApplicationUsageRequestRequestTypeDef",
-    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
     "ListReportDefinitionsResultTypeDef",
 )
 
 DeleteReportDefinitionRequestRequestTypeDef = TypedDict(
     "DeleteReportDefinitionRequestRequestTypeDef",
     {
         "reportId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteReportDefinitionResultTypeDef = TypedDict(
+    "DeleteReportDefinitionResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "reportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReportDefinitionRequestRequestTypeDef = TypedDict(
     "GetReportDefinitionRequestRequestTypeDef",
     {
         "reportId": str,
@@ -90,76 +87,87 @@
     },
     total=False,
 )
 
 class SourceS3LocationTypeDef(_RequiredSourceS3LocationTypeDef, _OptionalSourceS3LocationTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ImportApplicationUsageResultTypeDef = TypedDict(
+    "ImportApplicationUsageResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "importId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef = TypedDict(
+    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListReportDefinitionsRequestRequestTypeDef = TypedDict(
     "ListReportDefinitionsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-DeleteReportDefinitionResultTypeDef = TypedDict(
-    "DeleteReportDefinitionResultTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "reportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-ImportApplicationUsageResultTypeDef = TypedDict(
-    "ImportApplicationUsageResultTypeDef",
+PutReportDefinitionResultTypeDef = TypedDict(
+    "PutReportDefinitionResultTypeDef",
     {
-        "importId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "reportId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutReportDefinitionResultTypeDef = TypedDict(
-    "PutReportDefinitionResultTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "reportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 UpdateReportDefinitionResultTypeDef = TypedDict(
     "UpdateReportDefinitionResultTypeDef",
     {
         "reportId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetReportDefinitionResultTypeDef = TypedDict(
     "GetReportDefinitionResultTypeDef",
     {
         "reportId": str,
         "reportDescription": str,
         "reportFrequency": ReportFrequencyType,
         "format": FormatType,
         "destinationS3Location": S3LocationTypeDef,
         "createdAt": datetime,
         "lastUpdated": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutReportDefinitionRequestRequestTypeDef = TypedDict(
     "PutReportDefinitionRequestRequestTypeDef",
     {
         "reportId": str,
@@ -198,23 +206,15 @@
 ImportApplicationUsageRequestRequestTypeDef = TypedDict(
     "ImportApplicationUsageRequestRequestTypeDef",
     {
         "sourceS3Location": SourceS3LocationTypeDef,
     },
 )
 
-ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef = TypedDict(
-    "ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListReportDefinitionsResultTypeDef = TypedDict(
     "ListReportDefinitionsResultTypeDef",
     {
         "reportDefinitions": List[ReportDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/PKG-INFO` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-applicationcostprofiler
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationCostProfiler 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationCostProfiler 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-applicationcostprofiler"></a>
 
 # types-aiobotocore-applicationcostprofiler
 
 [![PyPI - types-aiobotocore-applicationcostprofiler](https://img.shields.io/pypi/v/types-aiobotocore-applicationcostprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-applicationcostprofiler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-applicationcostprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-applicationcostprofiler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-applicationcostprofiler?color=blue)](https://pypistats.org/packages/types-aiobotocore-applicationcostprofiler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationCostProfiler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler)
+[aiobotocore.ApplicationCostProfiler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/applicationcostprofiler.html#ApplicationCostProfiler)
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
 [types-aiobotocore-applicationcostprofiler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_applicationcostprofiler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,30 +320,30 @@
 `types_aiobotocore_applicationcostprofiler.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_applicationcostprofiler.type_defs import (
     DeleteReportDefinitionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteReportDefinitionResultTypeDef,
     GetReportDefinitionRequestRequestTypeDef,
     S3LocationTypeDef,
     SourceS3LocationTypeDef,
-    PaginatorConfigTypeDef,
-    ListReportDefinitionsRequestRequestTypeDef,
-    DeleteReportDefinitionResultTypeDef,
     ImportApplicationUsageResultTypeDef,
+    ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef,
+    ListReportDefinitionsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutReportDefinitionResultTypeDef,
+    ResponseMetadataTypeDef,
     UpdateReportDefinitionResultTypeDef,
     GetReportDefinitionResultTypeDef,
     PutReportDefinitionRequestRequestTypeDef,
     ReportDefinitionTypeDef,
     UpdateReportDefinitionRequestRequestTypeDef,
     ImportApplicationUsageRequestRequestTypeDef,
-    ListReportDefinitionsRequestListReportDefinitionsPaginateTypeDef,
     ListReportDefinitionsResultTypeDef,
 )
 
 
 def get_structure() -> DeleteReportDefinitionRequestRequestTypeDef:
     return {...}
 ```
@@ -351,43 +351,43 @@
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

### Comparing `types-aiobotocore-applicationcostprofiler-2.5.0.post1/types_aiobotocore_applicationcostprofiler.egg-info/SOURCES.txt` & `types-aiobotocore-applicationcostprofiler-2.5.1/types_aiobotocore_applicationcostprofiler.egg-info/SOURCES.txt`

 * *Files identical despite different names*

