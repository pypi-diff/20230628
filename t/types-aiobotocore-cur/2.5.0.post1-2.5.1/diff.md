# Comparing `tmp/types-aiobotocore-cur-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cur-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cur-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-cur-2.5.1.tar", last modified: Wed Jun 28 01:43:20 2023, max compression
```

## Comparing `types-aiobotocore-cur-2.5.0.post1.tar` & `types-aiobotocore-cur-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.435099 types-aiobotocore-cur-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13485 2023-03-11 12:26:27.435099 types-aiobotocore-cur-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11908 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:27.435099 types-aiobotocore-cur-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2094 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.431099 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/
--rw-r--r--   0 runner    (1001) docker     (123)      793 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      792 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      960 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7165 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7151 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8619 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8617 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2269 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2265 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     3932 2023-03-11 12:12:04.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     3929 2023-03-11 12:12:04.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:03.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.435099 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13485 2023-03-11 12:26:27.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:27.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:27.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:27.000000 types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.378120 types-aiobotocore-cur-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13473 2023-06-28 01:43:20.374120 types-aiobotocore-cur-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11902 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:20.378120 types-aiobotocore-cur-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2088 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.374120 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/
+-rw-r--r--   0 runner    (1001) docker     (123)      793 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      792 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      948 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7165 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7151 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8896 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8894 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2151 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2148 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     3848 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3845 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:42.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.374120 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13473 2023-06-28 01:43:20.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:20.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:20.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:20.000000 types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cur-2.5.0.post1/LICENSE` & `types-aiobotocore-cur-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cur-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cur-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cur
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CostandUsageReportService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CostandUsageReportService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cur"></a>
 
 # types-aiobotocore-cur
 
 [![PyPI - types-aiobotocore-cur](https://img.shields.io/pypi/v/types-aiobotocore-cur.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cur)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cur.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cur)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cur?color=blue)](https://pypistats.org/packages/types-aiobotocore-cur)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CostandUsageReportService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
+[aiobotocore.CostandUsageReportService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
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
 [types-aiobotocore-cur docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,20 +323,20 @@
 
 `types_aiobotocore_cur.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cur.type_defs import (
     DeleteReportDefinitionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
-    DescribeReportDefinitionsRequestRequestTypeDef,
-    ReportDefinitionTypeDef,
     DeleteReportDefinitionResponseTypeDef,
     DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef,
+    DescribeReportDefinitionsRequestRequestTypeDef,
+    ReportDefinitionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     DescribeReportDefinitionsResponseTypeDef,
     ModifyReportDefinitionRequestRequestTypeDef,
     PutReportDefinitionRequestRequestTypeDef,
 )
 
 
 def get_structure() -> DeleteReportDefinitionRequestRequestTypeDef:
@@ -346,43 +346,43 @@
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/README.md` & `types-aiobotocore-cur-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cur"></a>
 
 # types-aiobotocore-cur
 
 [![PyPI - types-aiobotocore-cur](https://img.shields.io/pypi/v/types-aiobotocore-cur.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cur)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cur.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cur)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cur?color=blue)](https://pypistats.org/packages/types-aiobotocore-cur)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CostandUsageReportService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
+[aiobotocore.CostandUsageReportService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
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
 [types-aiobotocore-cur docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,20 +290,20 @@
 
 `types_aiobotocore_cur.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cur.type_defs import (
     DeleteReportDefinitionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
-    DescribeReportDefinitionsRequestRequestTypeDef,
-    ReportDefinitionTypeDef,
     DeleteReportDefinitionResponseTypeDef,
     DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef,
+    DescribeReportDefinitionsRequestRequestTypeDef,
+    ReportDefinitionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     DescribeReportDefinitionsResponseTypeDef,
     ModifyReportDefinitionRequestRequestTypeDef,
     PutReportDefinitionRequestRequestTypeDef,
 )
 
 
 def get_structure() -> DeleteReportDefinitionRequestRequestTypeDef:
@@ -313,43 +313,43 @@
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/setup.py` & `types-aiobotocore-cur-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cur.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cur",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cur"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CostandUsageReportService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CostandUsageReportService 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/",
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/__init__.py` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/__init__.pyi` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/__main__.py` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CostandUsageReportService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CostandUsageReportService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService\nOther"
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/client.py` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/client.pyi` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/literals.py` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,21 +39,23 @@
 AWSRegionType = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
     "ca-central-1",
     "cn-north-1",
     "cn-northwest-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
@@ -65,15 +67,15 @@
     "us-west-2",
 ]
 AdditionalArtifactType = Literal["ATHENA", "QUICKSIGHT", "REDSHIFT"]
 CompressionFormatType = Literal["GZIP", "Parquet", "ZIP"]
 DescribeReportDefinitionsPaginatorName = Literal["describe_report_definitions"]
 ReportFormatType = Literal["Parquet", "textORcsv"]
 ReportVersioningType = Literal["CREATE_NEW_REPORT", "OVERWRITE_REPORT"]
-SchemaElementType = Literal["RESOURCES"]
+SchemaElementType = Literal["RESOURCES", "SPLIT_COST_ALLOCATION_DATA"]
 TimeUnitType = Literal["DAILY", "HOURLY", "MONTHLY"]
 CostandUsageReportServiceServiceName = Literal["cur"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -130,14 +132,15 @@
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
@@ -216,14 +219,15 @@
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
@@ -234,14 +238,15 @@
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
@@ -277,14 +282,15 @@
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
@@ -303,16 +309,19 @@
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
@@ -396,15 +405,17 @@
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/literals.pyi` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -37,21 +37,23 @@
 AWSRegionType = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
     "ca-central-1",
     "cn-north-1",
     "cn-northwest-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
@@ -63,15 +65,15 @@
     "us-west-2",
 ]
 AdditionalArtifactType = Literal["ATHENA", "QUICKSIGHT", "REDSHIFT"]
 CompressionFormatType = Literal["GZIP", "Parquet", "ZIP"]
 DescribeReportDefinitionsPaginatorName = Literal["describe_report_definitions"]
 ReportFormatType = Literal["Parquet", "textORcsv"]
 ReportVersioningType = Literal["CREATE_NEW_REPORT", "OVERWRITE_REPORT"]
-SchemaElementType = Literal["RESOURCES"]
+SchemaElementType = Literal["RESOURCES", "SPLIT_COST_ALLOCATION_DATA"]
 TimeUnitType = Literal["DAILY", "HOURLY", "MONTHLY"]
 CostandUsageReportServiceServiceName = Literal["cur"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -128,14 +130,15 @@
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
@@ -214,14 +217,15 @@
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
@@ -232,14 +236,15 @@
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
@@ -275,14 +280,15 @@
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
@@ -301,16 +307,19 @@
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
@@ -394,15 +403,17 @@
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/paginator.py` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/paginator.py`

 * *Files 12% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("cur") as client:
         client: CostandUsageReportServiceClient
 
         describe_report_definitions_paginator: DescribeReportDefinitionsPaginator = client.get_paginator("describe_report_definitions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import DescribeReportDefinitionsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeReportDefinitionsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class DescribeReportDefinitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService.Paginator.DescribeReportDefinitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/paginators/#describereportdefinitionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReportDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService.Paginator.DescribeReportDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/paginators/#describereportdefinitionspaginator)
         """
```

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/paginator.pyi` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/paginator.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("cur") as client:
         client: CostandUsageReportServiceClient
 
         describe_report_definitions_paginator: DescribeReportDefinitionsPaginator = client.get_paginator("describe_report_definitions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import DescribeReportDefinitionsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeReportDefinitionsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class DescribeReportDefinitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService.Paginator.DescribeReportDefinitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/paginators/#describereportdefinitionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReportDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService.Paginator.DescribeReportDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/paginators/#describereportdefinitionspaginator)
         """
```

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/type_defs.py` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -16,65 +16,57 @@
 
 from .literals import (
     AdditionalArtifactType,
     AWSRegionType,
     CompressionFormatType,
     ReportFormatType,
     ReportVersioningType,
+    SchemaElementType,
     TimeUnitType,
 )
 
 if sys.version_info >= (3, 9):
-    from typing import Literal
-else:
-    from typing_extensions import Literal
-if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DeleteReportDefinitionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "PaginatorConfigTypeDef",
-    "DescribeReportDefinitionsRequestRequestTypeDef",
-    "ReportDefinitionTypeDef",
     "DeleteReportDefinitionResponseTypeDef",
     "DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef",
+    "DescribeReportDefinitionsRequestRequestTypeDef",
+    "ReportDefinitionTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "DescribeReportDefinitionsResponseTypeDef",
     "ModifyReportDefinitionRequestRequestTypeDef",
     "PutReportDefinitionRequestRequestTypeDef",
 )
 
 DeleteReportDefinitionRequestRequestTypeDef = TypedDict(
     "DeleteReportDefinitionRequestRequestTypeDef",
     {
         "ReportName": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteReportDefinitionResponseTypeDef = TypedDict(
+    "DeleteReportDefinitionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef = TypedDict(
+    "DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeReportDefinitionsRequestRequestTypeDef = TypedDict(
     "DescribeReportDefinitionsRequestRequestTypeDef",
     {
@@ -87,15 +79,15 @@
 _RequiredReportDefinitionTypeDef = TypedDict(
     "_RequiredReportDefinitionTypeDef",
     {
         "ReportName": str,
         "TimeUnit": TimeUnitType,
         "Format": ReportFormatType,
         "Compression": CompressionFormatType,
-        "AdditionalSchemaElements": List[Literal["RESOURCES"]],
+        "AdditionalSchemaElements": List[SchemaElementType],
         "S3Bucket": str,
         "S3Prefix": str,
         "S3Region": AWSRegionType,
     },
 )
 _OptionalReportDefinitionTypeDef = TypedDict(
     "_OptionalReportDefinitionTypeDef",
@@ -109,36 +101,41 @@
 )
 
 
 class ReportDefinitionTypeDef(_RequiredReportDefinitionTypeDef, _OptionalReportDefinitionTypeDef):
     pass
 
 
-DeleteReportDefinitionResponseTypeDef = TypedDict(
-    "DeleteReportDefinitionResponseTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "ResponseMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef = TypedDict(
-    "DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
 DescribeReportDefinitionsResponseTypeDef = TypedDict(
     "DescribeReportDefinitionsResponseTypeDef",
     {
         "ReportDefinitions": List[ReportDefinitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReportDefinitionRequestRequestTypeDef = TypedDict(
     "ModifyReportDefinitionRequestRequestTypeDef",
     {
         "ReportName": str,
```

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur/type_defs.pyi` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,64 +16,56 @@
 
 from .literals import (
     AdditionalArtifactType,
     AWSRegionType,
     CompressionFormatType,
     ReportFormatType,
     ReportVersioningType,
+    SchemaElementType,
     TimeUnitType,
 )
 
 if sys.version_info >= (3, 9):
-    from typing import Literal
-else:
-    from typing_extensions import Literal
-if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DeleteReportDefinitionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "PaginatorConfigTypeDef",
-    "DescribeReportDefinitionsRequestRequestTypeDef",
-    "ReportDefinitionTypeDef",
     "DeleteReportDefinitionResponseTypeDef",
     "DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef",
+    "DescribeReportDefinitionsRequestRequestTypeDef",
+    "ReportDefinitionTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "DescribeReportDefinitionsResponseTypeDef",
     "ModifyReportDefinitionRequestRequestTypeDef",
     "PutReportDefinitionRequestRequestTypeDef",
 )
 
 DeleteReportDefinitionRequestRequestTypeDef = TypedDict(
     "DeleteReportDefinitionRequestRequestTypeDef",
     {
         "ReportName": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteReportDefinitionResponseTypeDef = TypedDict(
+    "DeleteReportDefinitionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef = TypedDict(
+    "DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeReportDefinitionsRequestRequestTypeDef = TypedDict(
     "DescribeReportDefinitionsRequestRequestTypeDef",
     {
@@ -86,15 +78,15 @@
 _RequiredReportDefinitionTypeDef = TypedDict(
     "_RequiredReportDefinitionTypeDef",
     {
         "ReportName": str,
         "TimeUnit": TimeUnitType,
         "Format": ReportFormatType,
         "Compression": CompressionFormatType,
-        "AdditionalSchemaElements": List[Literal["RESOURCES"]],
+        "AdditionalSchemaElements": List[SchemaElementType],
         "S3Bucket": str,
         "S3Prefix": str,
         "S3Region": AWSRegionType,
     },
 )
 _OptionalReportDefinitionTypeDef = TypedDict(
     "_OptionalReportDefinitionTypeDef",
@@ -106,36 +98,41 @@
     },
     total=False,
 )
 
 class ReportDefinitionTypeDef(_RequiredReportDefinitionTypeDef, _OptionalReportDefinitionTypeDef):
     pass
 
-DeleteReportDefinitionResponseTypeDef = TypedDict(
-    "DeleteReportDefinitionResponseTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "ResponseMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef = TypedDict(
-    "DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
 DescribeReportDefinitionsResponseTypeDef = TypedDict(
     "DescribeReportDefinitionsResponseTypeDef",
     {
         "ReportDefinitions": List[ReportDefinitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReportDefinitionRequestRequestTypeDef = TypedDict(
     "ModifyReportDefinitionRequestRequestTypeDef",
     {
         "ReportName": str,
```

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/PKG-INFO` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cur
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CostandUsageReportService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CostandUsageReportService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cur"></a>
 
 # types-aiobotocore-cur
 
 [![PyPI - types-aiobotocore-cur](https://img.shields.io/pypi/v/types-aiobotocore-cur.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cur)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cur.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cur)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cur?color=blue)](https://pypistats.org/packages/types-aiobotocore-cur)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CostandUsageReportService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
+[aiobotocore.CostandUsageReportService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cur.html#CostandUsageReportService)
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
 [types-aiobotocore-cur docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cur/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,20 +323,20 @@
 
 `types_aiobotocore_cur.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cur.type_defs import (
     DeleteReportDefinitionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
-    DescribeReportDefinitionsRequestRequestTypeDef,
-    ReportDefinitionTypeDef,
     DeleteReportDefinitionResponseTypeDef,
     DescribeReportDefinitionsRequestDescribeReportDefinitionsPaginateTypeDef,
+    DescribeReportDefinitionsRequestRequestTypeDef,
+    ReportDefinitionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     DescribeReportDefinitionsResponseTypeDef,
     ModifyReportDefinitionRequestRequestTypeDef,
     PutReportDefinitionRequestRequestTypeDef,
 )
 
 
 def get_structure() -> DeleteReportDefinitionRequestRequestTypeDef:
@@ -346,43 +346,43 @@
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

### Comparing `types-aiobotocore-cur-2.5.0.post1/types_aiobotocore_cur.egg-info/SOURCES.txt` & `types-aiobotocore-cur-2.5.1/types_aiobotocore_cur.egg-info/SOURCES.txt`

 * *Files identical despite different names*

