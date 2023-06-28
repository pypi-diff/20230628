# Comparing `tmp/types-aiobotocore-honeycode-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-honeycode-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-honeycode-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:42 2023, max compression
+gzip compressed data, was "types-aiobotocore-honeycode-2.5.1.tar", last modified: Wed Jun 28 01:43:34 2023, max compression
```

## Comparing `types-aiobotocore-honeycode-2.5.0.post1.tar` & `types-aiobotocore-honeycode-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.819258 types-aiobotocore-honeycode-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15608 2023-03-11 12:26:42.819258 types-aiobotocore-honeycode-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14029 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:42.819258 types-aiobotocore-honeycode-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:15:35.000000 types-aiobotocore-honeycode-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.819258 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/
--rw-r--r--   0 runner    (1001) docker     (123)     1245 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1244 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16914 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16886 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8959 2023-03-11 12:15:37.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8957 2023-03-11 12:15:37.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5586 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5579 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20820 2023-03-11 12:15:38.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20785 2023-03-11 12:15:38.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:36.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.819258 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15608 2023-03-11 12:26:42.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:42.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:42.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:42.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:42.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:42.000000 types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.254145 types-aiobotocore-honeycode-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15602 2023-06-28 01:43:34.250146 types-aiobotocore-honeycode-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14029 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:34.254145 types-aiobotocore-honeycode-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.242145 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/
+-rw-r--r--   0 runner    (1001) docker     (123)     1245 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1244 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16914 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16886 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9168 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9166 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5474 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5468 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    20854 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20819 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:13.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.242145 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15602 2023-06-28 01:43:34.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:34.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:34.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:34.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:34.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:34.000000 types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/LICENSE` & `types-aiobotocore-honeycode-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/PKG-INFO` & `types-aiobotocore-honeycode-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-honeycode
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Honeycode 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Honeycode 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-honeycode"></a>
 
 # types-aiobotocore-honeycode
 
 [![PyPI - types-aiobotocore-honeycode](https://img.shields.io/pypi/v/types-aiobotocore-honeycode.svg?color=blue)](https://pypi.org/project/types-aiobotocore-honeycode)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-honeycode.svg?color=blue)](https://pypi.org/project/types-aiobotocore-honeycode)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-honeycode?color=blue)](https://pypistats.org/packages/types-aiobotocore-honeycode)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Honeycode 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
+[aiobotocore.Honeycode 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
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
 [types-aiobotocore-honeycode docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,58 +334,58 @@
 
 `types_aiobotocore_honeycode.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_honeycode.type_defs import (
     FailedBatchItemTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteTableRowsRequestRequestTypeDef,
     UpsertRowsResultTypeDef,
     CellInputTypeDef,
     CellTypeDef,
     ColumnMetadataTypeDef,
     DataItemTypeDef,
     DelimitedTextImportOptionsTypeDef,
     DescribeTableDataImportJobRequestRequestTypeDef,
     SourceDataColumnPropertiesTypeDef,
     FilterTypeDef,
     VariableValueTypeDef,
     ImportDataSourceConfigTypeDef,
     ImportJobSubmitterTypeDef,
-    PaginatorConfigTypeDef,
+    InvokeScreenAutomationResultTypeDef,
+    ListTableColumnsRequestListTableColumnsPaginateTypeDef,
     ListTableColumnsRequestRequestTypeDef,
     TableColumnTypeDef,
+    ListTableRowsRequestListTableRowsPaginateTypeDef,
     ListTableRowsRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartTableDataImportJobResultTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     BatchCreateTableRowsResultTypeDef,
     BatchDeleteTableRowsResultTypeDef,
     BatchUpdateTableRowsResultTypeDef,
-    InvokeScreenAutomationResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    StartTableDataImportJobResultTypeDef,
     BatchUpsertTableRowsResultTypeDef,
     CreateRowDataTypeDef,
     UpdateRowDataTypeDef,
     TableRowTypeDef,
     ResultRowTypeDef,
     DestinationOptionsTypeDef,
+    QueryTableRowsRequestQueryTableRowsPaginateTypeDef,
     QueryTableRowsRequestRequestTypeDef,
     UpsertRowDataTypeDef,
     GetScreenDataRequestRequestTypeDef,
     InvokeScreenAutomationRequestRequestTypeDef,
     ImportDataSourceTypeDef,
-    ListTableColumnsRequestListTableColumnsPaginateTypeDef,
-    ListTableRowsRequestListTableRowsPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
-    QueryTableRowsRequestQueryTableRowsPaginateTypeDef,
     ListTableColumnsResultTypeDef,
     ListTablesResultTypeDef,
     BatchCreateTableRowsRequestRequestTypeDef,
     BatchUpdateTableRowsRequestRequestTypeDef,
     ListTableRowsResultTypeDef,
     QueryTableRowsResultTypeDef,
     ResultSetTypeDef,
@@ -405,43 +405,43 @@
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/README.md` & `types-aiobotocore-honeycode-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-honeycode"></a>
 
 # types-aiobotocore-honeycode
 
 [![PyPI - types-aiobotocore-honeycode](https://img.shields.io/pypi/v/types-aiobotocore-honeycode.svg?color=blue)](https://pypi.org/project/types-aiobotocore-honeycode)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-honeycode.svg?color=blue)](https://pypi.org/project/types-aiobotocore-honeycode)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-honeycode?color=blue)](https://pypistats.org/packages/types-aiobotocore-honeycode)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Honeycode 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
+[aiobotocore.Honeycode 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
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
 [types-aiobotocore-honeycode docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/).
 
 See how it helps to find and fix potential bugs:
 
@@ -301,58 +301,58 @@
 
 `types_aiobotocore_honeycode.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_honeycode.type_defs import (
     FailedBatchItemTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteTableRowsRequestRequestTypeDef,
     UpsertRowsResultTypeDef,
     CellInputTypeDef,
     CellTypeDef,
     ColumnMetadataTypeDef,
     DataItemTypeDef,
     DelimitedTextImportOptionsTypeDef,
     DescribeTableDataImportJobRequestRequestTypeDef,
     SourceDataColumnPropertiesTypeDef,
     FilterTypeDef,
     VariableValueTypeDef,
     ImportDataSourceConfigTypeDef,
     ImportJobSubmitterTypeDef,
-    PaginatorConfigTypeDef,
+    InvokeScreenAutomationResultTypeDef,
+    ListTableColumnsRequestListTableColumnsPaginateTypeDef,
     ListTableColumnsRequestRequestTypeDef,
     TableColumnTypeDef,
+    ListTableRowsRequestListTableRowsPaginateTypeDef,
     ListTableRowsRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartTableDataImportJobResultTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     BatchCreateTableRowsResultTypeDef,
     BatchDeleteTableRowsResultTypeDef,
     BatchUpdateTableRowsResultTypeDef,
-    InvokeScreenAutomationResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    StartTableDataImportJobResultTypeDef,
     BatchUpsertTableRowsResultTypeDef,
     CreateRowDataTypeDef,
     UpdateRowDataTypeDef,
     TableRowTypeDef,
     ResultRowTypeDef,
     DestinationOptionsTypeDef,
+    QueryTableRowsRequestQueryTableRowsPaginateTypeDef,
     QueryTableRowsRequestRequestTypeDef,
     UpsertRowDataTypeDef,
     GetScreenDataRequestRequestTypeDef,
     InvokeScreenAutomationRequestRequestTypeDef,
     ImportDataSourceTypeDef,
-    ListTableColumnsRequestListTableColumnsPaginateTypeDef,
-    ListTableRowsRequestListTableRowsPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
-    QueryTableRowsRequestQueryTableRowsPaginateTypeDef,
     ListTableColumnsResultTypeDef,
     ListTablesResultTypeDef,
     BatchCreateTableRowsRequestRequestTypeDef,
     BatchUpdateTableRowsRequestRequestTypeDef,
     ListTableRowsResultTypeDef,
     QueryTableRowsResultTypeDef,
     ResultSetTypeDef,
@@ -372,43 +372,43 @@
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/setup.py` & `types-aiobotocore-honeycode-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-honeycode.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-honeycode",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_honeycode"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Honeycode 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Honeycode 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/"
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/__init__.py` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/__init__.pyi` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/__main__.py` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Honeycode 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Honeycode 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode\nOther"
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/client.py` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/client.pyi` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/literals.py` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -137,14 +137,15 @@
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
@@ -223,14 +224,15 @@
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
@@ -241,14 +243,15 @@
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
@@ -284,14 +287,15 @@
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
@@ -310,16 +314,19 @@
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
@@ -403,15 +410,17 @@
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/literals.pyi` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -135,14 +135,15 @@
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
@@ -221,14 +222,15 @@
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
@@ -239,14 +241,15 @@
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
@@ -282,14 +285,15 @@
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
@@ -308,16 +312,19 @@
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
@@ -401,15 +408,17 @@
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/paginator.py` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         list_table_columns_paginator: ListTableColumnsPaginator = client.get_paginator("list_table_columns")
         list_table_rows_paginator: ListTableRowsPaginator = client.get_paginator("list_table_rows")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
         query_table_rows_paginator: QueryTableRowsPaginator = client.get_paginator("query_table_rows")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListTableColumnsResultTypeDef,
     ListTableRowsResultTypeDef,
     ListTablesResultTypeDef,
     PaginatorConfigTypeDef,
     QueryTableRowsResultTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListTableColumnsPaginator",
     "ListTableRowsPaginator",
     "ListTablesPaginator",
     "QueryTableRowsPaginator",
 )
 
@@ -68,15 +61,15 @@
 class ListTableColumnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTableColumns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablecolumnspaginator)
     """
 
     def paginate(
-        self, *, workbookId: str, tableId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workbookId: str, tableId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableColumnsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTableColumns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablecolumnspaginator)
         """
 
 
@@ -88,30 +81,30 @@
 
     def paginate(
         self,
         *,
         workbookId: str,
         tableId: str,
         rowIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableRowsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTableRows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablerowspaginator)
         """
 
 
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablespaginator)
     """
 
     def paginate(
-        self, *, workbookId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workbookId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablespaginator)
         """
 
 
@@ -123,13 +116,13 @@
 
     def paginate(
         self,
         *,
         workbookId: str,
         tableId: str,
         filterFormula: FilterTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryTableRowsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.QueryTableRows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#querytablerowspaginator)
         """
```

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/paginator.pyi` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         list_table_columns_paginator: ListTableColumnsPaginator = client.get_paginator("list_table_columns")
         list_table_rows_paginator: ListTableRowsPaginator = client.get_paginator("list_table_rows")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
         query_table_rows_paginator: QueryTableRowsPaginator = client.get_paginator("query_table_rows")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListTableColumnsResultTypeDef,
     ListTableRowsResultTypeDef,
     ListTablesResultTypeDef,
     PaginatorConfigTypeDef,
     QueryTableRowsResultTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListTableColumnsPaginator",
     "ListTableRowsPaginator",
     "ListTablesPaginator",
     "QueryTableRowsPaginator",
 )
 
@@ -64,15 +58,15 @@
 class ListTableColumnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTableColumns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablecolumnspaginator)
     """
 
     def paginate(
-        self, *, workbookId: str, tableId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workbookId: str, tableId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableColumnsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTableColumns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablecolumnspaginator)
         """
 
 class ListTableRowsPaginator(AioPaginator):
@@ -83,29 +77,29 @@
 
     def paginate(
         self,
         *,
         workbookId: str,
         tableId: str,
         rowIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableRowsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTableRows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablerowspaginator)
         """
 
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablespaginator)
     """
 
     def paginate(
-        self, *, workbookId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workbookId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#listtablespaginator)
         """
 
 class QueryTableRowsPaginator(AioPaginator):
@@ -116,13 +110,13 @@
 
     def paginate(
         self,
         *,
         workbookId: str,
         tableId: str,
         filterFormula: FilterTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryTableRowsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode.Paginator.QueryTableRows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/paginators/#querytablerowspaginator)
         """
```

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/type_defs.py` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -31,58 +31,58 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "FailedBatchItemTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteTableRowsRequestRequestTypeDef",
     "UpsertRowsResultTypeDef",
     "CellInputTypeDef",
     "CellTypeDef",
     "ColumnMetadataTypeDef",
     "DataItemTypeDef",
     "DelimitedTextImportOptionsTypeDef",
     "DescribeTableDataImportJobRequestRequestTypeDef",
     "SourceDataColumnPropertiesTypeDef",
     "FilterTypeDef",
     "VariableValueTypeDef",
     "ImportDataSourceConfigTypeDef",
     "ImportJobSubmitterTypeDef",
-    "PaginatorConfigTypeDef",
+    "InvokeScreenAutomationResultTypeDef",
+    "ListTableColumnsRequestListTableColumnsPaginateTypeDef",
     "ListTableColumnsRequestRequestTypeDef",
     "TableColumnTypeDef",
+    "ListTableRowsRequestListTableRowsPaginateTypeDef",
     "ListTableRowsRequestRequestTypeDef",
+    "ListTablesRequestListTablesPaginateTypeDef",
     "ListTablesRequestRequestTypeDef",
     "TableTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartTableDataImportJobResultTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "BatchCreateTableRowsResultTypeDef",
     "BatchDeleteTableRowsResultTypeDef",
     "BatchUpdateTableRowsResultTypeDef",
-    "InvokeScreenAutomationResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "StartTableDataImportJobResultTypeDef",
     "BatchUpsertTableRowsResultTypeDef",
     "CreateRowDataTypeDef",
     "UpdateRowDataTypeDef",
     "TableRowTypeDef",
     "ResultRowTypeDef",
     "DestinationOptionsTypeDef",
+    "QueryTableRowsRequestQueryTableRowsPaginateTypeDef",
     "QueryTableRowsRequestRequestTypeDef",
     "UpsertRowDataTypeDef",
     "GetScreenDataRequestRequestTypeDef",
     "InvokeScreenAutomationRequestRequestTypeDef",
     "ImportDataSourceTypeDef",
-    "ListTableColumnsRequestListTableColumnsPaginateTypeDef",
-    "ListTableRowsRequestListTableRowsPaginateTypeDef",
-    "ListTablesRequestListTablesPaginateTypeDef",
-    "QueryTableRowsRequestQueryTableRowsPaginateTypeDef",
     "ListTableColumnsResultTypeDef",
     "ListTablesResultTypeDef",
     "BatchCreateTableRowsRequestRequestTypeDef",
     "BatchUpdateTableRowsRequestRequestTypeDef",
     "ListTableRowsResultTypeDef",
     "QueryTableRowsResultTypeDef",
     "ResultSetTypeDef",
@@ -98,25 +98,14 @@
     "FailedBatchItemTypeDef",
     {
         "id": str,
         "errorMessage": str,
     },
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
 _RequiredBatchDeleteTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDeleteTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
         "rowIds": Sequence[str],
     },
@@ -263,24 +252,45 @@
     {
         "email": str,
         "userArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+InvokeScreenAutomationResultTypeDef = TypedDict(
+    "InvokeScreenAutomationResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "workbookCursor": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
+    "_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef",
+    {
+        "workbookId": str,
+        "tableId": str,
+    },
+)
+_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
+    "_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListTableColumnsRequestListTableColumnsPaginateTypeDef(
+    _RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef,
+    _OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTableColumnsRequestRequestTypeDef = TypedDict(
     "_RequiredListTableColumnsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
     },
 )
@@ -305,14 +315,38 @@
         "tableColumnId": str,
         "tableColumnName": str,
         "format": FormatType,
     },
     total=False,
 )
 
+_RequiredListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
+    "_RequiredListTableRowsRequestListTableRowsPaginateTypeDef",
+    {
+        "workbookId": str,
+        "tableId": str,
+    },
+)
+_OptionalListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
+    "_OptionalListTableRowsRequestListTableRowsPaginateTypeDef",
+    {
+        "rowIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTableRowsRequestListTableRowsPaginateTypeDef(
+    _RequiredListTableRowsRequestListTableRowsPaginateTypeDef,
+    _OptionalListTableRowsRequestListTableRowsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredListTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
     },
 )
@@ -329,14 +363,36 @@
 
 class ListTableRowsRequestRequestTypeDef(
     _RequiredListTableRowsRequestRequestTypeDef, _OptionalListTableRowsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_RequiredListTablesRequestListTablesPaginateTypeDef",
+    {
+        "workbookId": str,
+    },
+)
+_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_OptionalListTablesRequestListTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTablesRequestListTablesPaginateTypeDef(
+    _RequiredListTablesRequestListTablesPaginateTypeDef,
+    _OptionalListTablesRequestListTablesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTablesRequestRequestTypeDef = TypedDict(
     "_RequiredListTablesRequestRequestTypeDef",
     {
         "workbookId": str,
     },
 )
 _OptionalListTablesRequestRequestTypeDef = TypedDict(
@@ -367,14 +423,52 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "tags": Dict[str, str],
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
+StartTableDataImportJobResultTypeDef = TypedDict(
+    "StartTableDataImportJobResultTypeDef",
+    {
+        "jobId": str,
+        "jobStatus": TableDataImportJobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -389,68 +483,43 @@
 
 BatchCreateTableRowsResultTypeDef = TypedDict(
     "BatchCreateTableRowsResultTypeDef",
     {
         "workbookCursor": int,
         "createdRows": Dict[str, str],
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteTableRowsResultTypeDef = TypedDict(
     "BatchDeleteTableRowsResultTypeDef",
     {
         "workbookCursor": int,
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateTableRowsResultTypeDef = TypedDict(
     "BatchUpdateTableRowsResultTypeDef",
     {
         "workbookCursor": int,
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvokeScreenAutomationResultTypeDef = TypedDict(
-    "InvokeScreenAutomationResultTypeDef",
-    {
-        "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTableDataImportJobResultTypeDef = TypedDict(
-    "StartTableDataImportJobResultTypeDef",
-    {
-        "jobId": str,
-        "jobStatus": TableDataImportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpsertTableRowsResultTypeDef = TypedDict(
     "BatchUpsertTableRowsResultTypeDef",
     {
         "rows": Dict[str, UpsertRowsResultTypeDef],
         "workbookCursor": int,
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRowDataTypeDef = TypedDict(
     "CreateRowDataTypeDef",
     {
         "batchItemId": str,
@@ -497,14 +566,38 @@
     "DestinationOptionsTypeDef",
     {
         "columnMap": Dict[str, SourceDataColumnPropertiesTypeDef],
     },
     total=False,
 )
 
+_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
+    "_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
+    {
+        "workbookId": str,
+        "tableId": str,
+        "filterFormula": FilterTypeDef,
+    },
+)
+_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
+    "_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class QueryTableRowsRequestQueryTableRowsPaginateTypeDef(
+    _RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
+    _OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredQueryTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredQueryTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
         "filterFormula": FilterTypeDef,
     },
@@ -589,124 +682,31 @@
 ImportDataSourceTypeDef = TypedDict(
     "ImportDataSourceTypeDef",
     {
         "dataSourceConfig": ImportDataSourceConfigTypeDef,
     },
 )
 
-_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
-    "_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef",
-    {
-        "workbookId": str,
-        "tableId": str,
-    },
-)
-_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
-    "_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTableColumnsRequestListTableColumnsPaginateTypeDef(
-    _RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef,
-    _OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
-    "_RequiredListTableRowsRequestListTableRowsPaginateTypeDef",
-    {
-        "workbookId": str,
-        "tableId": str,
-    },
-)
-_OptionalListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
-    "_OptionalListTableRowsRequestListTableRowsPaginateTypeDef",
-    {
-        "rowIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTableRowsRequestListTableRowsPaginateTypeDef(
-    _RequiredListTableRowsRequestListTableRowsPaginateTypeDef,
-    _OptionalListTableRowsRequestListTableRowsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_RequiredListTablesRequestListTablesPaginateTypeDef",
-    {
-        "workbookId": str,
-    },
-)
-_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_OptionalListTablesRequestListTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTablesRequestListTablesPaginateTypeDef(
-    _RequiredListTablesRequestListTablesPaginateTypeDef,
-    _OptionalListTablesRequestListTablesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
-    "_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
-    {
-        "workbookId": str,
-        "tableId": str,
-        "filterFormula": FilterTypeDef,
-    },
-)
-_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
-    "_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class QueryTableRowsRequestQueryTableRowsPaginateTypeDef(
-    _RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
-    _OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
-):
-    pass
-
-
 ListTableColumnsResultTypeDef = TypedDict(
     "ListTableColumnsResultTypeDef",
     {
         "tableColumns": List[TableColumnTypeDef],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTablesResultTypeDef = TypedDict(
     "ListTablesResultTypeDef",
     {
         "tables": List[TableTypeDef],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchCreateTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchCreateTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
@@ -758,26 +758,26 @@
     "ListTableRowsResultTypeDef",
     {
         "columnIds": List[str],
         "rows": List[TableRowTypeDef],
         "rowIdsNotFound": List[str],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryTableRowsResultTypeDef = TypedDict(
     "QueryTableRowsResultTypeDef",
     {
         "columnIds": List[str],
         "rows": List[TableRowTypeDef],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResultSetTypeDef = TypedDict(
     "ResultSetTypeDef",
     {
         "headers": List[ColumnMetadataTypeDef],
@@ -820,15 +820,15 @@
 
 GetScreenDataResultTypeDef = TypedDict(
     "GetScreenDataResultTypeDef",
     {
         "results": Dict[str, ResultSetTypeDef],
         "workbookCursor": int,
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTableDataImportJobRequestRequestTypeDef = TypedDict(
     "StartTableDataImportJobRequestRequestTypeDef",
     {
         "workbookId": str,
@@ -853,10 +853,10 @@
 DescribeTableDataImportJobResultTypeDef = TypedDict(
     "DescribeTableDataImportJobResultTypeDef",
     {
         "jobStatus": TableDataImportJobStatusType,
         "message": str,
         "jobMetadata": TableDataImportJobMetadataTypeDef,
         "errorCode": ErrorCodeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode/type_defs.pyi` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -30,58 +30,58 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "FailedBatchItemTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteTableRowsRequestRequestTypeDef",
     "UpsertRowsResultTypeDef",
     "CellInputTypeDef",
     "CellTypeDef",
     "ColumnMetadataTypeDef",
     "DataItemTypeDef",
     "DelimitedTextImportOptionsTypeDef",
     "DescribeTableDataImportJobRequestRequestTypeDef",
     "SourceDataColumnPropertiesTypeDef",
     "FilterTypeDef",
     "VariableValueTypeDef",
     "ImportDataSourceConfigTypeDef",
     "ImportJobSubmitterTypeDef",
-    "PaginatorConfigTypeDef",
+    "InvokeScreenAutomationResultTypeDef",
+    "ListTableColumnsRequestListTableColumnsPaginateTypeDef",
     "ListTableColumnsRequestRequestTypeDef",
     "TableColumnTypeDef",
+    "ListTableRowsRequestListTableRowsPaginateTypeDef",
     "ListTableRowsRequestRequestTypeDef",
+    "ListTablesRequestListTablesPaginateTypeDef",
     "ListTablesRequestRequestTypeDef",
     "TableTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartTableDataImportJobResultTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "BatchCreateTableRowsResultTypeDef",
     "BatchDeleteTableRowsResultTypeDef",
     "BatchUpdateTableRowsResultTypeDef",
-    "InvokeScreenAutomationResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "StartTableDataImportJobResultTypeDef",
     "BatchUpsertTableRowsResultTypeDef",
     "CreateRowDataTypeDef",
     "UpdateRowDataTypeDef",
     "TableRowTypeDef",
     "ResultRowTypeDef",
     "DestinationOptionsTypeDef",
+    "QueryTableRowsRequestQueryTableRowsPaginateTypeDef",
     "QueryTableRowsRequestRequestTypeDef",
     "UpsertRowDataTypeDef",
     "GetScreenDataRequestRequestTypeDef",
     "InvokeScreenAutomationRequestRequestTypeDef",
     "ImportDataSourceTypeDef",
-    "ListTableColumnsRequestListTableColumnsPaginateTypeDef",
-    "ListTableRowsRequestListTableRowsPaginateTypeDef",
-    "ListTablesRequestListTablesPaginateTypeDef",
-    "QueryTableRowsRequestQueryTableRowsPaginateTypeDef",
     "ListTableColumnsResultTypeDef",
     "ListTablesResultTypeDef",
     "BatchCreateTableRowsRequestRequestTypeDef",
     "BatchUpdateTableRowsRequestRequestTypeDef",
     "ListTableRowsResultTypeDef",
     "QueryTableRowsResultTypeDef",
     "ResultSetTypeDef",
@@ -97,25 +97,14 @@
     "FailedBatchItemTypeDef",
     {
         "id": str,
         "errorMessage": str,
     },
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
 _RequiredBatchDeleteTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDeleteTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
         "rowIds": Sequence[str],
     },
@@ -256,24 +245,43 @@
     {
         "email": str,
         "userArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+InvokeScreenAutomationResultTypeDef = TypedDict(
+    "InvokeScreenAutomationResultTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "workbookCursor": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
+    "_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef",
+    {
+        "workbookId": str,
+        "tableId": str,
+    },
+)
+_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
+    "_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListTableColumnsRequestListTableColumnsPaginateTypeDef(
+    _RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef,
+    _OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef,
+):
+    pass
+
 _RequiredListTableColumnsRequestRequestTypeDef = TypedDict(
     "_RequiredListTableColumnsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
     },
 )
@@ -296,14 +304,36 @@
         "tableColumnId": str,
         "tableColumnName": str,
         "format": FormatType,
     },
     total=False,
 )
 
+_RequiredListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
+    "_RequiredListTableRowsRequestListTableRowsPaginateTypeDef",
+    {
+        "workbookId": str,
+        "tableId": str,
+    },
+)
+_OptionalListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
+    "_OptionalListTableRowsRequestListTableRowsPaginateTypeDef",
+    {
+        "rowIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTableRowsRequestListTableRowsPaginateTypeDef(
+    _RequiredListTableRowsRequestListTableRowsPaginateTypeDef,
+    _OptionalListTableRowsRequestListTableRowsPaginateTypeDef,
+):
+    pass
+
 _RequiredListTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredListTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
     },
 )
@@ -318,14 +348,34 @@
 )
 
 class ListTableRowsRequestRequestTypeDef(
     _RequiredListTableRowsRequestRequestTypeDef, _OptionalListTableRowsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_RequiredListTablesRequestListTablesPaginateTypeDef",
+    {
+        "workbookId": str,
+    },
+)
+_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_OptionalListTablesRequestListTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTablesRequestListTablesPaginateTypeDef(
+    _RequiredListTablesRequestListTablesPaginateTypeDef,
+    _OptionalListTablesRequestListTablesPaginateTypeDef,
+):
+    pass
+
 _RequiredListTablesRequestRequestTypeDef = TypedDict(
     "_RequiredListTablesRequestRequestTypeDef",
     {
         "workbookId": str,
     },
 )
 _OptionalListTablesRequestRequestTypeDef = TypedDict(
@@ -354,14 +404,52 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "tags": Dict[str, str],
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
+StartTableDataImportJobResultTypeDef = TypedDict(
+    "StartTableDataImportJobResultTypeDef",
+    {
+        "jobId": str,
+        "jobStatus": TableDataImportJobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -376,68 +464,43 @@
 
 BatchCreateTableRowsResultTypeDef = TypedDict(
     "BatchCreateTableRowsResultTypeDef",
     {
         "workbookCursor": int,
         "createdRows": Dict[str, str],
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteTableRowsResultTypeDef = TypedDict(
     "BatchDeleteTableRowsResultTypeDef",
     {
         "workbookCursor": int,
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateTableRowsResultTypeDef = TypedDict(
     "BatchUpdateTableRowsResultTypeDef",
     {
         "workbookCursor": int,
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvokeScreenAutomationResultTypeDef = TypedDict(
-    "InvokeScreenAutomationResultTypeDef",
-    {
-        "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTableDataImportJobResultTypeDef = TypedDict(
-    "StartTableDataImportJobResultTypeDef",
-    {
-        "jobId": str,
-        "jobStatus": TableDataImportJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpsertTableRowsResultTypeDef = TypedDict(
     "BatchUpsertTableRowsResultTypeDef",
     {
         "rows": Dict[str, UpsertRowsResultTypeDef],
         "workbookCursor": int,
         "failedBatchItems": List[FailedBatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRowDataTypeDef = TypedDict(
     "CreateRowDataTypeDef",
     {
         "batchItemId": str,
@@ -482,14 +545,36 @@
     "DestinationOptionsTypeDef",
     {
         "columnMap": Dict[str, SourceDataColumnPropertiesTypeDef],
     },
     total=False,
 )
 
+_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
+    "_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
+    {
+        "workbookId": str,
+        "tableId": str,
+        "filterFormula": FilterTypeDef,
+    },
+)
+_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
+    "_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class QueryTableRowsRequestQueryTableRowsPaginateTypeDef(
+    _RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
+    _OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
+):
+    pass
+
 _RequiredQueryTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredQueryTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
         "tableId": str,
         "filterFormula": FilterTypeDef,
     },
@@ -568,116 +653,31 @@
 ImportDataSourceTypeDef = TypedDict(
     "ImportDataSourceTypeDef",
     {
         "dataSourceConfig": ImportDataSourceConfigTypeDef,
     },
 )
 
-_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
-    "_RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef",
-    {
-        "workbookId": str,
-        "tableId": str,
-    },
-)
-_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef = TypedDict(
-    "_OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTableColumnsRequestListTableColumnsPaginateTypeDef(
-    _RequiredListTableColumnsRequestListTableColumnsPaginateTypeDef,
-    _OptionalListTableColumnsRequestListTableColumnsPaginateTypeDef,
-):
-    pass
-
-_RequiredListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
-    "_RequiredListTableRowsRequestListTableRowsPaginateTypeDef",
-    {
-        "workbookId": str,
-        "tableId": str,
-    },
-)
-_OptionalListTableRowsRequestListTableRowsPaginateTypeDef = TypedDict(
-    "_OptionalListTableRowsRequestListTableRowsPaginateTypeDef",
-    {
-        "rowIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTableRowsRequestListTableRowsPaginateTypeDef(
-    _RequiredListTableRowsRequestListTableRowsPaginateTypeDef,
-    _OptionalListTableRowsRequestListTableRowsPaginateTypeDef,
-):
-    pass
-
-_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_RequiredListTablesRequestListTablesPaginateTypeDef",
-    {
-        "workbookId": str,
-    },
-)
-_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_OptionalListTablesRequestListTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTablesRequestListTablesPaginateTypeDef(
-    _RequiredListTablesRequestListTablesPaginateTypeDef,
-    _OptionalListTablesRequestListTablesPaginateTypeDef,
-):
-    pass
-
-_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
-    "_RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
-    {
-        "workbookId": str,
-        "tableId": str,
-        "filterFormula": FilterTypeDef,
-    },
-)
-_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef = TypedDict(
-    "_OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class QueryTableRowsRequestQueryTableRowsPaginateTypeDef(
-    _RequiredQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
-    _OptionalQueryTableRowsRequestQueryTableRowsPaginateTypeDef,
-):
-    pass
-
 ListTableColumnsResultTypeDef = TypedDict(
     "ListTableColumnsResultTypeDef",
     {
         "tableColumns": List[TableColumnTypeDef],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTablesResultTypeDef = TypedDict(
     "ListTablesResultTypeDef",
     {
         "tables": List[TableTypeDef],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchCreateTableRowsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchCreateTableRowsRequestRequestTypeDef",
     {
         "workbookId": str,
@@ -725,26 +725,26 @@
     "ListTableRowsResultTypeDef",
     {
         "columnIds": List[str],
         "rows": List[TableRowTypeDef],
         "rowIdsNotFound": List[str],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryTableRowsResultTypeDef = TypedDict(
     "QueryTableRowsResultTypeDef",
     {
         "columnIds": List[str],
         "rows": List[TableRowTypeDef],
         "nextToken": str,
         "workbookCursor": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResultSetTypeDef = TypedDict(
     "ResultSetTypeDef",
     {
         "headers": List[ColumnMetadataTypeDef],
@@ -785,15 +785,15 @@
 
 GetScreenDataResultTypeDef = TypedDict(
     "GetScreenDataResultTypeDef",
     {
         "results": Dict[str, ResultSetTypeDef],
         "workbookCursor": int,
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTableDataImportJobRequestRequestTypeDef = TypedDict(
     "StartTableDataImportJobRequestRequestTypeDef",
     {
         "workbookId": str,
@@ -818,10 +818,10 @@
 DescribeTableDataImportJobResultTypeDef = TypedDict(
     "DescribeTableDataImportJobResultTypeDef",
     {
         "jobStatus": TableDataImportJobStatusType,
         "message": str,
         "jobMetadata": TableDataImportJobMetadataTypeDef,
         "errorCode": ErrorCodeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/PKG-INFO` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-honeycode
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Honeycode 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Honeycode 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-honeycode"></a>
 
 # types-aiobotocore-honeycode
 
 [![PyPI - types-aiobotocore-honeycode](https://img.shields.io/pypi/v/types-aiobotocore-honeycode.svg?color=blue)](https://pypi.org/project/types-aiobotocore-honeycode)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-honeycode.svg?color=blue)](https://pypi.org/project/types-aiobotocore-honeycode)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-honeycode?color=blue)](https://pypistats.org/packages/types-aiobotocore-honeycode)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Honeycode 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
+[aiobotocore.Honeycode 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/honeycode.html#Honeycode)
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
 [types-aiobotocore-honeycode docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_honeycode/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,58 +334,58 @@
 
 `types_aiobotocore_honeycode.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_honeycode.type_defs import (
     FailedBatchItemTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteTableRowsRequestRequestTypeDef,
     UpsertRowsResultTypeDef,
     CellInputTypeDef,
     CellTypeDef,
     ColumnMetadataTypeDef,
     DataItemTypeDef,
     DelimitedTextImportOptionsTypeDef,
     DescribeTableDataImportJobRequestRequestTypeDef,
     SourceDataColumnPropertiesTypeDef,
     FilterTypeDef,
     VariableValueTypeDef,
     ImportDataSourceConfigTypeDef,
     ImportJobSubmitterTypeDef,
-    PaginatorConfigTypeDef,
+    InvokeScreenAutomationResultTypeDef,
+    ListTableColumnsRequestListTableColumnsPaginateTypeDef,
     ListTableColumnsRequestRequestTypeDef,
     TableColumnTypeDef,
+    ListTableRowsRequestListTableRowsPaginateTypeDef,
     ListTableRowsRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartTableDataImportJobResultTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     BatchCreateTableRowsResultTypeDef,
     BatchDeleteTableRowsResultTypeDef,
     BatchUpdateTableRowsResultTypeDef,
-    InvokeScreenAutomationResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    StartTableDataImportJobResultTypeDef,
     BatchUpsertTableRowsResultTypeDef,
     CreateRowDataTypeDef,
     UpdateRowDataTypeDef,
     TableRowTypeDef,
     ResultRowTypeDef,
     DestinationOptionsTypeDef,
+    QueryTableRowsRequestQueryTableRowsPaginateTypeDef,
     QueryTableRowsRequestRequestTypeDef,
     UpsertRowDataTypeDef,
     GetScreenDataRequestRequestTypeDef,
     InvokeScreenAutomationRequestRequestTypeDef,
     ImportDataSourceTypeDef,
-    ListTableColumnsRequestListTableColumnsPaginateTypeDef,
-    ListTableRowsRequestListTableRowsPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
-    QueryTableRowsRequestQueryTableRowsPaginateTypeDef,
     ListTableColumnsResultTypeDef,
     ListTablesResultTypeDef,
     BatchCreateTableRowsRequestRequestTypeDef,
     BatchUpdateTableRowsRequestRequestTypeDef,
     ListTableRowsResultTypeDef,
     QueryTableRowsResultTypeDef,
     ResultSetTypeDef,
@@ -405,43 +405,43 @@
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

### Comparing `types-aiobotocore-honeycode-2.5.0.post1/types_aiobotocore_honeycode.egg-info/SOURCES.txt` & `types-aiobotocore-honeycode-2.5.1/types_aiobotocore_honeycode.egg-info/SOURCES.txt`

 * *Files identical despite different names*

