# Comparing `tmp/types-aiobotocore-redshift-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-redshift-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-redshift-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-redshift-data-2.5.1.tar", last modified: Wed Jun 28 01:44:02 2023, max compression
```

## Comparing `types-aiobotocore-redshift-data-2.5.0.post1.tar` & `types-aiobotocore-redshift-data-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.907535 types-aiobotocore-redshift-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15364 2023-03-11 12:27:10.907535 types-aiobotocore-redshift-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13760 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:10.907535 types-aiobotocore-redshift-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2175 2023-03-11 12:22:15.000000 types-aiobotocore-redshift-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.907535 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/
--rw-r--r--   0 runner    (1001) docker     (123)     1686 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1685 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      985 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15175 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15150 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8375 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8373 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8843 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8834 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    16704 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    16675 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:16.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.907535 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15364 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:27:10.000000 types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.434198 types-aiobotocore-redshift-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15362 2023-06-28 01:44:02.434198 types-aiobotocore-redshift-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13764 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:02.434198 types-aiobotocore-redshift-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2169 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.434198 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/
+-rw-r--r--   0 runner    (1001) docker     (123)     1686 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1685 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      973 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15175 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15150 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8584 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8582 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8735 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8727 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    16736 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16707 2023-06-28 01:39:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:01.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.434198 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15362 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:44:02.000000 types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/LICENSE` & `types-aiobotocore-redshift-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-redshift-data-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-redshift-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RedshiftDataAPIService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RedshiftDataAPIService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-redshift-data"></a>
 
 # types-aiobotocore-redshift-data
 
 [![PyPI - types-aiobotocore-redshift-data](https://img.shields.io/pypi/v/types-aiobotocore-redshift-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-redshift-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-redshift-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-redshift-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RedshiftDataAPIService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
+[aiobotocore.RedshiftDataAPIService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
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
 [types-aiobotocore-redshift-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -335,44 +335,44 @@
 
 `types_aiobotocore_redshift_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_redshift_data.type_defs import (
     BatchExecuteStatementInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BatchExecuteStatementOutputTypeDef,
     CancelStatementRequestRequestTypeDef,
+    CancelStatementResponseTypeDef,
     ColumnMetadataTypeDef,
     DescribeStatementRequestRequestTypeDef,
     SqlParameterTypeDef,
     SubStatementDataTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeTableRequestDescribeTablePaginateTypeDef,
     DescribeTableRequestRequestTypeDef,
+    ExecuteStatementOutputTypeDef,
     FieldTypeDef,
+    GetStatementResultRequestGetStatementResultPaginateTypeDef,
     GetStatementResultRequestRequestTypeDef,
+    ListDatabasesRequestListDatabasesPaginateTypeDef,
     ListDatabasesRequestRequestTypeDef,
+    ListDatabasesResponseTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
+    ListSchemasResponseTypeDef,
+    ListStatementsRequestListStatementsPaginateTypeDef,
     ListStatementsRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableMemberTypeDef,
-    BatchExecuteStatementOutputTypeDef,
-    CancelStatementResponseTypeDef,
-    ExecuteStatementOutputTypeDef,
-    ListDatabasesResponseTypeDef,
-    ListSchemasResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     DescribeTableResponseTypeDef,
     ExecuteStatementInputRequestTypeDef,
     StatementDataTypeDef,
     DescribeStatementResponseTypeDef,
-    DescribeTableRequestDescribeTablePaginateTypeDef,
-    GetStatementResultRequestGetStatementResultPaginateTypeDef,
-    ListDatabasesRequestListDatabasesPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    ListStatementsRequestListStatementsPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
     GetStatementResultResponseTypeDef,
     ListTablesResponseTypeDef,
     ListStatementsResponseTypeDef,
 )
 
 
 def get_structure() -> BatchExecuteStatementInputRequestTypeDef:
@@ -382,43 +382,43 @@
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/README.md` & `types-aiobotocore-redshift-data-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-redshift-data"></a>
 
 # types-aiobotocore-redshift-data
 
 [![PyPI - types-aiobotocore-redshift-data](https://img.shields.io/pypi/v/types-aiobotocore-redshift-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-redshift-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-redshift-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-redshift-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RedshiftDataAPIService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
+[aiobotocore.RedshiftDataAPIService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
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
 [types-aiobotocore-redshift-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -302,44 +302,44 @@
 
 `types_aiobotocore_redshift_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_redshift_data.type_defs import (
     BatchExecuteStatementInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BatchExecuteStatementOutputTypeDef,
     CancelStatementRequestRequestTypeDef,
+    CancelStatementResponseTypeDef,
     ColumnMetadataTypeDef,
     DescribeStatementRequestRequestTypeDef,
     SqlParameterTypeDef,
     SubStatementDataTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeTableRequestDescribeTablePaginateTypeDef,
     DescribeTableRequestRequestTypeDef,
+    ExecuteStatementOutputTypeDef,
     FieldTypeDef,
+    GetStatementResultRequestGetStatementResultPaginateTypeDef,
     GetStatementResultRequestRequestTypeDef,
+    ListDatabasesRequestListDatabasesPaginateTypeDef,
     ListDatabasesRequestRequestTypeDef,
+    ListDatabasesResponseTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
+    ListSchemasResponseTypeDef,
+    ListStatementsRequestListStatementsPaginateTypeDef,
     ListStatementsRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableMemberTypeDef,
-    BatchExecuteStatementOutputTypeDef,
-    CancelStatementResponseTypeDef,
-    ExecuteStatementOutputTypeDef,
-    ListDatabasesResponseTypeDef,
-    ListSchemasResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     DescribeTableResponseTypeDef,
     ExecuteStatementInputRequestTypeDef,
     StatementDataTypeDef,
     DescribeStatementResponseTypeDef,
-    DescribeTableRequestDescribeTablePaginateTypeDef,
-    GetStatementResultRequestGetStatementResultPaginateTypeDef,
-    ListDatabasesRequestListDatabasesPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    ListStatementsRequestListStatementsPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
     GetStatementResultResponseTypeDef,
     ListTablesResponseTypeDef,
     ListStatementsResponseTypeDef,
 )
 
 
 def get_structure() -> BatchExecuteStatementInputRequestTypeDef:
@@ -349,43 +349,43 @@
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/setup.py` & `types-aiobotocore-redshift-data-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-redshift-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-redshift-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_redshift_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RedshiftDataAPIService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.RedshiftDataAPIService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/"
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/__init__.py` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/__init__.pyi` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/__main__.py` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/__main__.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RedshiftDataAPIService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RedshiftDataAPIService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService\nOther"
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/client.py` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/client.pyi` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/literals.py` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -104,14 +104,15 @@
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
@@ -190,14 +191,15 @@
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
@@ -208,14 +210,15 @@
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
@@ -251,14 +254,15 @@
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
@@ -277,16 +281,19 @@
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
@@ -370,15 +377,17 @@
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/literals.pyi` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -102,14 +102,15 @@
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
@@ -188,14 +189,15 @@
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
@@ -206,14 +208,15 @@
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
@@ -249,14 +252,15 @@
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
@@ -275,16 +279,19 @@
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
@@ -368,15 +375,17 @@
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/paginator.py` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         get_statement_result_paginator: GetStatementResultPaginator = client.get_paginator("get_statement_result")
         list_databases_paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
         list_statements_paginator: ListStatementsPaginator = client.get_paginator("list_statements")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import StatusStringType
 from .type_defs import (
     DescribeTableResponseTypeDef,
@@ -43,40 +42,31 @@
     ListDatabasesResponseTypeDef,
     ListSchemasResponseTypeDef,
     ListStatementsResponseTypeDef,
     ListTablesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeTablePaginator",
     "GetStatementResultPaginator",
     "ListDatabasesPaginator",
     "ListSchemasPaginator",
     "ListStatementsPaginator",
     "ListTablesPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeTablePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.DescribeTable)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#describetablepaginator)
     """
 
     def paginate(
@@ -86,59 +76,56 @@
         ClusterIdentifier: str = ...,
         ConnectedDatabase: str = ...,
         DbUser: str = ...,
         Schema: str = ...,
         SecretArn: str = ...,
         Table: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTableResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.DescribeTable.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#describetablepaginator)
         """
 
-
 class GetStatementResultPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.GetStatementResult)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#getstatementresultpaginator)
     """
 
     def paginate(
-        self, *, Id: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Id: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetStatementResultResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.GetStatementResult.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#getstatementresultpaginator)
         """
 
-
 class ListDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listdatabasespaginator)
     """
 
     def paginate(
         self,
         *,
         Database: str,
         ClusterIdentifier: str = ...,
         DbUser: str = ...,
         SecretArn: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatabasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listdatabasespaginator)
         """
 
-
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listschemaspaginator)
     """
 
     def paginate(
@@ -147,42 +134,40 @@
         Database: str,
         ClusterIdentifier: str = ...,
         ConnectedDatabase: str = ...,
         DbUser: str = ...,
         SchemaPattern: str = ...,
         SecretArn: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listschemaspaginator)
         """
 
-
 class ListStatementsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListStatements)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#liststatementspaginator)
     """
 
     def paginate(
         self,
         *,
         RoleLevel: bool = ...,
         StatementName: str = ...,
         Status: StatusStringType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStatementsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListStatements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#liststatementspaginator)
         """
 
-
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listtablespaginator)
     """
 
     def paginate(
@@ -192,13 +177,13 @@
         ClusterIdentifier: str = ...,
         ConnectedDatabase: str = ...,
         DbUser: str = ...,
         SchemaPattern: str = ...,
         SecretArn: str = ...,
         TablePattern: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listtablespaginator)
         """
```

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/paginator.pyi` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         get_statement_result_paginator: GetStatementResultPaginator = client.get_paginator("get_statement_result")
         list_databases_paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
         list_statements_paginator: ListStatementsPaginator = client.get_paginator("list_statements")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import StatusStringType
 from .type_defs import (
     DescribeTableResponseTypeDef,
@@ -43,36 +42,34 @@
     ListDatabasesResponseTypeDef,
     ListSchemasResponseTypeDef,
     ListStatementsResponseTypeDef,
     ListTablesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeTablePaginator",
     "GetStatementResultPaginator",
     "ListDatabasesPaginator",
     "ListSchemasPaginator",
     "ListStatementsPaginator",
     "ListTablesPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeTablePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.DescribeTable)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#describetablepaginator)
     """
 
     def paginate(
@@ -82,56 +79,59 @@
         ClusterIdentifier: str = ...,
         ConnectedDatabase: str = ...,
         DbUser: str = ...,
         Schema: str = ...,
         SecretArn: str = ...,
         Table: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTableResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.DescribeTable.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#describetablepaginator)
         """
 
+
 class GetStatementResultPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.GetStatementResult)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#getstatementresultpaginator)
     """
 
     def paginate(
-        self, *, Id: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Id: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetStatementResultResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.GetStatementResult.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#getstatementresultpaginator)
         """
 
+
 class ListDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listdatabasespaginator)
     """
 
     def paginate(
         self,
         *,
         Database: str,
         ClusterIdentifier: str = ...,
         DbUser: str = ...,
         SecretArn: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatabasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listdatabasespaginator)
         """
 
+
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listschemaspaginator)
     """
 
     def paginate(
@@ -140,40 +140,42 @@
         Database: str,
         ClusterIdentifier: str = ...,
         ConnectedDatabase: str = ...,
         DbUser: str = ...,
         SchemaPattern: str = ...,
         SecretArn: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listschemaspaginator)
         """
 
+
 class ListStatementsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListStatements)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#liststatementspaginator)
     """
 
     def paginate(
         self,
         *,
         RoleLevel: bool = ...,
         StatementName: str = ...,
         Status: StatusStringType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStatementsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListStatements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#liststatementspaginator)
         """
 
+
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listtablespaginator)
     """
 
     def paginate(
@@ -183,13 +185,13 @@
         ClusterIdentifier: str = ...,
         ConnectedDatabase: str = ...,
         DbUser: str = ...,
         SchemaPattern: str = ...,
         SecretArn: str = ...,
         TablePattern: str = ...,
         WorkgroupName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/paginators/#listtablespaginator)
         """
```

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/type_defs.py` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -21,44 +21,44 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BatchExecuteStatementInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BatchExecuteStatementOutputTypeDef",
     "CancelStatementRequestRequestTypeDef",
+    "CancelStatementResponseTypeDef",
     "ColumnMetadataTypeDef",
     "DescribeStatementRequestRequestTypeDef",
     "SqlParameterTypeDef",
     "SubStatementDataTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeTableRequestDescribeTablePaginateTypeDef",
     "DescribeTableRequestRequestTypeDef",
+    "ExecuteStatementOutputTypeDef",
     "FieldTypeDef",
+    "GetStatementResultRequestGetStatementResultPaginateTypeDef",
     "GetStatementResultRequestRequestTypeDef",
+    "ListDatabasesRequestListDatabasesPaginateTypeDef",
     "ListDatabasesRequestRequestTypeDef",
+    "ListDatabasesResponseTypeDef",
+    "ListSchemasRequestListSchemasPaginateTypeDef",
     "ListSchemasRequestRequestTypeDef",
+    "ListSchemasResponseTypeDef",
+    "ListStatementsRequestListStatementsPaginateTypeDef",
     "ListStatementsRequestRequestTypeDef",
+    "ListTablesRequestListTablesPaginateTypeDef",
     "ListTablesRequestRequestTypeDef",
     "TableMemberTypeDef",
-    "BatchExecuteStatementOutputTypeDef",
-    "CancelStatementResponseTypeDef",
-    "ExecuteStatementOutputTypeDef",
-    "ListDatabasesResponseTypeDef",
-    "ListSchemasResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "DescribeTableResponseTypeDef",
     "ExecuteStatementInputRequestTypeDef",
     "StatementDataTypeDef",
     "DescribeStatementResponseTypeDef",
-    "DescribeTableRequestDescribeTablePaginateTypeDef",
-    "GetStatementResultRequestGetStatementResultPaginateTypeDef",
-    "ListDatabasesRequestListDatabasesPaginateTypeDef",
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    "ListStatementsRequestListStatementsPaginateTypeDef",
-    "ListTablesRequestListTablesPaginateTypeDef",
     "GetStatementResultResponseTypeDef",
     "ListTablesResponseTypeDef",
     "ListStatementsResponseTypeDef",
 )
 
 _RequiredBatchExecuteStatementInputRequestTypeDef = TypedDict(
     "_RequiredBatchExecuteStatementInputRequestTypeDef",
@@ -85,32 +85,43 @@
 class BatchExecuteStatementInputRequestTypeDef(
     _RequiredBatchExecuteStatementInputRequestTypeDef,
     _OptionalBatchExecuteStatementInputRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BatchExecuteStatementOutputTypeDef = TypedDict(
+    "BatchExecuteStatementOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ClusterIdentifier": str,
+        "CreatedAt": datetime,
+        "Database": str,
+        "DbUser": str,
+        "Id": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelStatementRequestRequestTypeDef = TypedDict(
     "CancelStatementRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+CancelStatementResponseTypeDef = TypedDict(
+    "CancelStatementResponseTypeDef",
+    {
+        "Status": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ColumnMetadataTypeDef = TypedDict(
     "ColumnMetadataTypeDef",
     {
         "columnDefault": str,
         "isCaseSensitive": bool,
         "isCurrency": bool,
         "isSigned": bool,
@@ -166,24 +177,43 @@
 )
 
 
 class SubStatementDataTypeDef(_RequiredSubStatementDataTypeDef, _OptionalSubStatementDataTypeDef):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
+    "_RequiredDescribeTableRequestDescribeTablePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Database": str,
+    },
+)
+_OptionalDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
+    "_OptionalDescribeTableRequestDescribeTablePaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "ConnectedDatabase": str,
+        "DbUser": str,
+        "Schema": str,
+        "SecretArn": str,
+        "Table": str,
+        "WorkgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeTableRequestDescribeTablePaginateTypeDef(
+    _RequiredDescribeTableRequestDescribeTablePaginateTypeDef,
+    _OptionalDescribeTableRequestDescribeTablePaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeTableRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeTableRequestRequestTypeDef",
     {
         "Database": str,
     },
 )
 _OptionalDescribeTableRequestRequestTypeDef = TypedDict(
@@ -205,27 +235,63 @@
 
 class DescribeTableRequestRequestTypeDef(
     _RequiredDescribeTableRequestRequestTypeDef, _OptionalDescribeTableRequestRequestTypeDef
 ):
     pass
 
 
+ExecuteStatementOutputTypeDef = TypedDict(
+    "ExecuteStatementOutputTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "CreatedAt": datetime,
+        "Database": str,
+        "DbUser": str,
+        "Id": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FieldTypeDef = TypedDict(
     "FieldTypeDef",
     {
         "blobValue": bytes,
         "booleanValue": bool,
         "doubleValue": float,
         "isNull": bool,
         "longValue": int,
         "stringValue": str,
     },
     total=False,
 )
 
+_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
+    "_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
+    "_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetStatementResultRequestGetStatementResultPaginateTypeDef(
+    _RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef,
+    _OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetStatementResultRequestRequestTypeDef = TypedDict(
     "_RequiredGetStatementResultRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalGetStatementResultRequestRequestTypeDef = TypedDict(
@@ -240,14 +306,40 @@
 class GetStatementResultRequestRequestTypeDef(
     _RequiredGetStatementResultRequestRequestTypeDef,
     _OptionalGetStatementResultRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
+    "_RequiredListDatabasesRequestListDatabasesPaginateTypeDef",
+    {
+        "Database": str,
+    },
+)
+_OptionalListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
+    "_OptionalListDatabasesRequestListDatabasesPaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "DbUser": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDatabasesRequestListDatabasesPaginateTypeDef(
+    _RequiredListDatabasesRequestListDatabasesPaginateTypeDef,
+    _OptionalListDatabasesRequestListDatabasesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDatabasesRequestRequestTypeDef = TypedDict(
     "_RequiredListDatabasesRequestRequestTypeDef",
     {
         "Database": str,
     },
 )
 _OptionalListDatabasesRequestRequestTypeDef = TypedDict(
@@ -266,14 +358,51 @@
 
 class ListDatabasesRequestRequestTypeDef(
     _RequiredListDatabasesRequestRequestTypeDef, _OptionalListDatabasesRequestRequestTypeDef
 ):
     pass
 
 
+ListDatabasesResponseTypeDef = TypedDict(
+    "ListDatabasesResponseTypeDef",
+    {
+        "Databases": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "Database": str,
+    },
+)
+_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "ConnectedDatabase": str,
+        "DbUser": str,
+        "SchemaPattern": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSchemasRequestListSchemasPaginateTypeDef(
+    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
+    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSchemasRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemasRequestRequestTypeDef",
     {
         "Database": str,
     },
 )
 _OptionalListSchemasRequestRequestTypeDef = TypedDict(
@@ -294,26 +423,75 @@
 
 class ListSchemasRequestRequestTypeDef(
     _RequiredListSchemasRequestRequestTypeDef, _OptionalListSchemasRequestRequestTypeDef
 ):
     pass
 
 
+ListSchemasResponseTypeDef = TypedDict(
+    "ListSchemasResponseTypeDef",
+    {
+        "NextToken": str,
+        "Schemas": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStatementsRequestListStatementsPaginateTypeDef = TypedDict(
+    "ListStatementsRequestListStatementsPaginateTypeDef",
+    {
+        "RoleLevel": bool,
+        "StatementName": str,
+        "Status": StatusStringType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStatementsRequestRequestTypeDef = TypedDict(
     "ListStatementsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "RoleLevel": bool,
         "StatementName": str,
         "Status": StatusStringType,
     },
     total=False,
 )
 
+_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_RequiredListTablesRequestListTablesPaginateTypeDef",
+    {
+        "Database": str,
+    },
+)
+_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_OptionalListTablesRequestListTablesPaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "ConnectedDatabase": str,
+        "DbUser": str,
+        "SchemaPattern": str,
+        "SecretArn": str,
+        "TablePattern": str,
+        "WorkgroupName": str,
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
         "Database": str,
     },
 )
 _OptionalListTablesRequestRequestTypeDef = TypedDict(
@@ -345,75 +523,42 @@
         "name": str,
         "schema": str,
         "type": str,
     },
     total=False,
 )
 
-BatchExecuteStatementOutputTypeDef = TypedDict(
-    "BatchExecuteStatementOutputTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "CreatedAt": datetime,
-        "Database": str,
-        "DbUser": str,
-        "Id": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelStatementResponseTypeDef = TypedDict(
-    "CancelStatementResponseTypeDef",
-    {
-        "Status": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExecuteStatementOutputTypeDef = TypedDict(
-    "ExecuteStatementOutputTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "CreatedAt": datetime,
-        "Database": str,
-        "DbUser": str,
-        "Id": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatabasesResponseTypeDef = TypedDict(
-    "ListDatabasesResponseTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "Databases": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-ListSchemasResponseTypeDef = TypedDict(
-    "ListSchemasResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "NextToken": str,
-        "Schemas": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 DescribeTableResponseTypeDef = TypedDict(
     "DescribeTableResponseTypeDef",
     {
         "ColumnList": List[ColumnMetadataTypeDef],
         "NextToken": str,
         "TableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredExecuteStatementInputRequestTypeDef = TypedDict(
     "_RequiredExecuteStatementInputRequestTypeDef",
     {
         "Database": str,
@@ -487,184 +632,39 @@
         "ResultRows": int,
         "ResultSize": int,
         "SecretArn": str,
         "Status": StatusStringType,
         "SubStatements": List[SubStatementDataTypeDef],
         "UpdatedAt": datetime,
         "WorkgroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
-    "_RequiredDescribeTableRequestDescribeTablePaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
-    "_OptionalDescribeTableRequestDescribeTablePaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "ConnectedDatabase": str,
-        "DbUser": str,
-        "Schema": str,
-        "SecretArn": str,
-        "Table": str,
-        "WorkgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeTableRequestDescribeTablePaginateTypeDef(
-    _RequiredDescribeTableRequestDescribeTablePaginateTypeDef,
-    _OptionalDescribeTableRequestDescribeTablePaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
-    "_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef",
-    {
-        "Id": str,
-    },
-)
-_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
-    "_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetStatementResultRequestGetStatementResultPaginateTypeDef(
-    _RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef,
-    _OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
-    "_RequiredListDatabasesRequestListDatabasesPaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
-    "_OptionalListDatabasesRequestListDatabasesPaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "DbUser": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDatabasesRequestListDatabasesPaginateTypeDef(
-    _RequiredListDatabasesRequestListDatabasesPaginateTypeDef,
-    _OptionalListDatabasesRequestListDatabasesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "ConnectedDatabase": str,
-        "DbUser": str,
-        "SchemaPattern": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSchemasRequestListSchemasPaginateTypeDef(
-    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
-    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
-):
-    pass
-
-
-ListStatementsRequestListStatementsPaginateTypeDef = TypedDict(
-    "ListStatementsRequestListStatementsPaginateTypeDef",
-    {
-        "RoleLevel": bool,
-        "StatementName": str,
-        "Status": StatusStringType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_RequiredListTablesRequestListTablesPaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_OptionalListTablesRequestListTablesPaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "ConnectedDatabase": str,
-        "DbUser": str,
-        "SchemaPattern": str,
-        "SecretArn": str,
-        "TablePattern": str,
-        "WorkgroupName": str,
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
 GetStatementResultResponseTypeDef = TypedDict(
     "GetStatementResultResponseTypeDef",
     {
         "ColumnMetadata": List[ColumnMetadataTypeDef],
         "NextToken": str,
         "Records": List[List[FieldTypeDef]],
         "TotalNumRows": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTablesResponseTypeDef = TypedDict(
     "ListTablesResponseTypeDef",
     {
         "NextToken": str,
         "Tables": List[TableMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStatementsResponseTypeDef = TypedDict(
     "ListStatementsResponseTypeDef",
     {
         "NextToken": str,
         "Statements": List[StatementDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data/type_defs.pyi` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -20,44 +20,44 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BatchExecuteStatementInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BatchExecuteStatementOutputTypeDef",
     "CancelStatementRequestRequestTypeDef",
+    "CancelStatementResponseTypeDef",
     "ColumnMetadataTypeDef",
     "DescribeStatementRequestRequestTypeDef",
     "SqlParameterTypeDef",
     "SubStatementDataTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeTableRequestDescribeTablePaginateTypeDef",
     "DescribeTableRequestRequestTypeDef",
+    "ExecuteStatementOutputTypeDef",
     "FieldTypeDef",
+    "GetStatementResultRequestGetStatementResultPaginateTypeDef",
     "GetStatementResultRequestRequestTypeDef",
+    "ListDatabasesRequestListDatabasesPaginateTypeDef",
     "ListDatabasesRequestRequestTypeDef",
+    "ListDatabasesResponseTypeDef",
+    "ListSchemasRequestListSchemasPaginateTypeDef",
     "ListSchemasRequestRequestTypeDef",
+    "ListSchemasResponseTypeDef",
+    "ListStatementsRequestListStatementsPaginateTypeDef",
     "ListStatementsRequestRequestTypeDef",
+    "ListTablesRequestListTablesPaginateTypeDef",
     "ListTablesRequestRequestTypeDef",
     "TableMemberTypeDef",
-    "BatchExecuteStatementOutputTypeDef",
-    "CancelStatementResponseTypeDef",
-    "ExecuteStatementOutputTypeDef",
-    "ListDatabasesResponseTypeDef",
-    "ListSchemasResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "DescribeTableResponseTypeDef",
     "ExecuteStatementInputRequestTypeDef",
     "StatementDataTypeDef",
     "DescribeStatementResponseTypeDef",
-    "DescribeTableRequestDescribeTablePaginateTypeDef",
-    "GetStatementResultRequestGetStatementResultPaginateTypeDef",
-    "ListDatabasesRequestListDatabasesPaginateTypeDef",
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    "ListStatementsRequestListStatementsPaginateTypeDef",
-    "ListTablesRequestListTablesPaginateTypeDef",
     "GetStatementResultResponseTypeDef",
     "ListTablesResponseTypeDef",
     "ListStatementsResponseTypeDef",
 )
 
 _RequiredBatchExecuteStatementInputRequestTypeDef = TypedDict(
     "_RequiredBatchExecuteStatementInputRequestTypeDef",
@@ -82,32 +82,43 @@
 
 class BatchExecuteStatementInputRequestTypeDef(
     _RequiredBatchExecuteStatementInputRequestTypeDef,
     _OptionalBatchExecuteStatementInputRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BatchExecuteStatementOutputTypeDef = TypedDict(
+    "BatchExecuteStatementOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ClusterIdentifier": str,
+        "CreatedAt": datetime,
+        "Database": str,
+        "DbUser": str,
+        "Id": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelStatementRequestRequestTypeDef = TypedDict(
     "CancelStatementRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+CancelStatementResponseTypeDef = TypedDict(
+    "CancelStatementResponseTypeDef",
+    {
+        "Status": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ColumnMetadataTypeDef = TypedDict(
     "ColumnMetadataTypeDef",
     {
         "columnDefault": str,
         "isCaseSensitive": bool,
         "isCurrency": bool,
         "isSigned": bool,
@@ -161,24 +172,41 @@
     },
     total=False,
 )
 
 class SubStatementDataTypeDef(_RequiredSubStatementDataTypeDef, _OptionalSubStatementDataTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
+    "_RequiredDescribeTableRequestDescribeTablePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Database": str,
+    },
+)
+_OptionalDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
+    "_OptionalDescribeTableRequestDescribeTablePaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "ConnectedDatabase": str,
+        "DbUser": str,
+        "Schema": str,
+        "SecretArn": str,
+        "Table": str,
+        "WorkgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeTableRequestDescribeTablePaginateTypeDef(
+    _RequiredDescribeTableRequestDescribeTablePaginateTypeDef,
+    _OptionalDescribeTableRequestDescribeTablePaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeTableRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeTableRequestRequestTypeDef",
     {
         "Database": str,
     },
 )
 _OptionalDescribeTableRequestRequestTypeDef = TypedDict(
@@ -198,27 +226,61 @@
 )
 
 class DescribeTableRequestRequestTypeDef(
     _RequiredDescribeTableRequestRequestTypeDef, _OptionalDescribeTableRequestRequestTypeDef
 ):
     pass
 
+ExecuteStatementOutputTypeDef = TypedDict(
+    "ExecuteStatementOutputTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "CreatedAt": datetime,
+        "Database": str,
+        "DbUser": str,
+        "Id": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FieldTypeDef = TypedDict(
     "FieldTypeDef",
     {
         "blobValue": bytes,
         "booleanValue": bool,
         "doubleValue": float,
         "isNull": bool,
         "longValue": int,
         "stringValue": str,
     },
     total=False,
 )
 
+_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
+    "_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
+    "_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetStatementResultRequestGetStatementResultPaginateTypeDef(
+    _RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef,
+    _OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef,
+):
+    pass
+
 _RequiredGetStatementResultRequestRequestTypeDef = TypedDict(
     "_RequiredGetStatementResultRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalGetStatementResultRequestRequestTypeDef = TypedDict(
@@ -231,14 +293,38 @@
 
 class GetStatementResultRequestRequestTypeDef(
     _RequiredGetStatementResultRequestRequestTypeDef,
     _OptionalGetStatementResultRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
+    "_RequiredListDatabasesRequestListDatabasesPaginateTypeDef",
+    {
+        "Database": str,
+    },
+)
+_OptionalListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
+    "_OptionalListDatabasesRequestListDatabasesPaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "DbUser": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDatabasesRequestListDatabasesPaginateTypeDef(
+    _RequiredListDatabasesRequestListDatabasesPaginateTypeDef,
+    _OptionalListDatabasesRequestListDatabasesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDatabasesRequestRequestTypeDef = TypedDict(
     "_RequiredListDatabasesRequestRequestTypeDef",
     {
         "Database": str,
     },
 )
 _OptionalListDatabasesRequestRequestTypeDef = TypedDict(
@@ -255,14 +341,49 @@
 )
 
 class ListDatabasesRequestRequestTypeDef(
     _RequiredListDatabasesRequestRequestTypeDef, _OptionalListDatabasesRequestRequestTypeDef
 ):
     pass
 
+ListDatabasesResponseTypeDef = TypedDict(
+    "ListDatabasesResponseTypeDef",
+    {
+        "Databases": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "Database": str,
+    },
+)
+_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "ConnectedDatabase": str,
+        "DbUser": str,
+        "SchemaPattern": str,
+        "SecretArn": str,
+        "WorkgroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSchemasRequestListSchemasPaginateTypeDef(
+    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
+    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
+):
+    pass
+
 _RequiredListSchemasRequestRequestTypeDef = TypedDict(
     "_RequiredListSchemasRequestRequestTypeDef",
     {
         "Database": str,
     },
 )
 _OptionalListSchemasRequestRequestTypeDef = TypedDict(
@@ -281,26 +402,73 @@
 )
 
 class ListSchemasRequestRequestTypeDef(
     _RequiredListSchemasRequestRequestTypeDef, _OptionalListSchemasRequestRequestTypeDef
 ):
     pass
 
+ListSchemasResponseTypeDef = TypedDict(
+    "ListSchemasResponseTypeDef",
+    {
+        "NextToken": str,
+        "Schemas": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStatementsRequestListStatementsPaginateTypeDef = TypedDict(
+    "ListStatementsRequestListStatementsPaginateTypeDef",
+    {
+        "RoleLevel": bool,
+        "StatementName": str,
+        "Status": StatusStringType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStatementsRequestRequestTypeDef = TypedDict(
     "ListStatementsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "RoleLevel": bool,
         "StatementName": str,
         "Status": StatusStringType,
     },
     total=False,
 )
 
+_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_RequiredListTablesRequestListTablesPaginateTypeDef",
+    {
+        "Database": str,
+    },
+)
+_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_OptionalListTablesRequestListTablesPaginateTypeDef",
+    {
+        "ClusterIdentifier": str,
+        "ConnectedDatabase": str,
+        "DbUser": str,
+        "SchemaPattern": str,
+        "SecretArn": str,
+        "TablePattern": str,
+        "WorkgroupName": str,
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
         "Database": str,
     },
 )
 _OptionalListTablesRequestRequestTypeDef = TypedDict(
@@ -330,75 +498,42 @@
         "name": str,
         "schema": str,
         "type": str,
     },
     total=False,
 )
 
-BatchExecuteStatementOutputTypeDef = TypedDict(
-    "BatchExecuteStatementOutputTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "CreatedAt": datetime,
-        "Database": str,
-        "DbUser": str,
-        "Id": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelStatementResponseTypeDef = TypedDict(
-    "CancelStatementResponseTypeDef",
-    {
-        "Status": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExecuteStatementOutputTypeDef = TypedDict(
-    "ExecuteStatementOutputTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "CreatedAt": datetime,
-        "Database": str,
-        "DbUser": str,
-        "Id": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDatabasesResponseTypeDef = TypedDict(
-    "ListDatabasesResponseTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "Databases": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-ListSchemasResponseTypeDef = TypedDict(
-    "ListSchemasResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "NextToken": str,
-        "Schemas": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 DescribeTableResponseTypeDef = TypedDict(
     "DescribeTableResponseTypeDef",
     {
         "ColumnList": List[ColumnMetadataTypeDef],
         "NextToken": str,
         "TableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredExecuteStatementInputRequestTypeDef = TypedDict(
     "_RequiredExecuteStatementInputRequestTypeDef",
     {
         "Database": str,
@@ -468,174 +603,39 @@
         "ResultRows": int,
         "ResultSize": int,
         "SecretArn": str,
         "Status": StatusStringType,
         "SubStatements": List[SubStatementDataTypeDef],
         "UpdatedAt": datetime,
         "WorkgroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
-    "_RequiredDescribeTableRequestDescribeTablePaginateTypeDef",
-    {
-        "Database": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalDescribeTableRequestDescribeTablePaginateTypeDef = TypedDict(
-    "_OptionalDescribeTableRequestDescribeTablePaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "ConnectedDatabase": str,
-        "DbUser": str,
-        "Schema": str,
-        "SecretArn": str,
-        "Table": str,
-        "WorkgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeTableRequestDescribeTablePaginateTypeDef(
-    _RequiredDescribeTableRequestDescribeTablePaginateTypeDef,
-    _OptionalDescribeTableRequestDescribeTablePaginateTypeDef,
-):
-    pass
-
-_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
-    "_RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef",
-    {
-        "Id": str,
-    },
-)
-_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef = TypedDict(
-    "_OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetStatementResultRequestGetStatementResultPaginateTypeDef(
-    _RequiredGetStatementResultRequestGetStatementResultPaginateTypeDef,
-    _OptionalGetStatementResultRequestGetStatementResultPaginateTypeDef,
-):
-    pass
-
-_RequiredListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
-    "_RequiredListDatabasesRequestListDatabasesPaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalListDatabasesRequestListDatabasesPaginateTypeDef = TypedDict(
-    "_OptionalListDatabasesRequestListDatabasesPaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "DbUser": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDatabasesRequestListDatabasesPaginateTypeDef(
-    _RequiredListDatabasesRequestListDatabasesPaginateTypeDef,
-    _OptionalListDatabasesRequestListDatabasesPaginateTypeDef,
-):
-    pass
-
-_RequiredListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_RequiredListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "_OptionalListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "ConnectedDatabase": str,
-        "DbUser": str,
-        "SchemaPattern": str,
-        "SecretArn": str,
-        "WorkgroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSchemasRequestListSchemasPaginateTypeDef(
-    _RequiredListSchemasRequestListSchemasPaginateTypeDef,
-    _OptionalListSchemasRequestListSchemasPaginateTypeDef,
-):
-    pass
-
-ListStatementsRequestListStatementsPaginateTypeDef = TypedDict(
-    "ListStatementsRequestListStatementsPaginateTypeDef",
-    {
-        "RoleLevel": bool,
-        "StatementName": str,
-        "Status": StatusStringType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_RequiredListTablesRequestListTablesPaginateTypeDef",
-    {
-        "Database": str,
-    },
-)
-_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_OptionalListTablesRequestListTablesPaginateTypeDef",
-    {
-        "ClusterIdentifier": str,
-        "ConnectedDatabase": str,
-        "DbUser": str,
-        "SchemaPattern": str,
-        "SecretArn": str,
-        "TablePattern": str,
-        "WorkgroupName": str,
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
 
 GetStatementResultResponseTypeDef = TypedDict(
     "GetStatementResultResponseTypeDef",
     {
         "ColumnMetadata": List[ColumnMetadataTypeDef],
         "NextToken": str,
         "Records": List[List[FieldTypeDef]],
         "TotalNumRows": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTablesResponseTypeDef = TypedDict(
     "ListTablesResponseTypeDef",
     {
         "NextToken": str,
         "Tables": List[TableMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStatementsResponseTypeDef = TypedDict(
     "ListStatementsResponseTypeDef",
     {
         "NextToken": str,
         "Statements": List[StatementDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/PKG-INFO` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-redshift-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RedshiftDataAPIService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RedshiftDataAPIService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-redshift-data"></a>
 
 # types-aiobotocore-redshift-data
 
 [![PyPI - types-aiobotocore-redshift-data](https://img.shields.io/pypi/v/types-aiobotocore-redshift-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-redshift-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-redshift-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-redshift-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-redshift-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RedshiftDataAPIService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
+[aiobotocore.RedshiftDataAPIService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html#RedshiftDataAPIService)
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
 [types-aiobotocore-redshift-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_redshift_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -335,44 +335,44 @@
 
 `types_aiobotocore_redshift_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_redshift_data.type_defs import (
     BatchExecuteStatementInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BatchExecuteStatementOutputTypeDef,
     CancelStatementRequestRequestTypeDef,
+    CancelStatementResponseTypeDef,
     ColumnMetadataTypeDef,
     DescribeStatementRequestRequestTypeDef,
     SqlParameterTypeDef,
     SubStatementDataTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeTableRequestDescribeTablePaginateTypeDef,
     DescribeTableRequestRequestTypeDef,
+    ExecuteStatementOutputTypeDef,
     FieldTypeDef,
+    GetStatementResultRequestGetStatementResultPaginateTypeDef,
     GetStatementResultRequestRequestTypeDef,
+    ListDatabasesRequestListDatabasesPaginateTypeDef,
     ListDatabasesRequestRequestTypeDef,
+    ListDatabasesResponseTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
+    ListSchemasResponseTypeDef,
+    ListStatementsRequestListStatementsPaginateTypeDef,
     ListStatementsRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableMemberTypeDef,
-    BatchExecuteStatementOutputTypeDef,
-    CancelStatementResponseTypeDef,
-    ExecuteStatementOutputTypeDef,
-    ListDatabasesResponseTypeDef,
-    ListSchemasResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     DescribeTableResponseTypeDef,
     ExecuteStatementInputRequestTypeDef,
     StatementDataTypeDef,
     DescribeStatementResponseTypeDef,
-    DescribeTableRequestDescribeTablePaginateTypeDef,
-    GetStatementResultRequestGetStatementResultPaginateTypeDef,
-    ListDatabasesRequestListDatabasesPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    ListStatementsRequestListStatementsPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
     GetStatementResultResponseTypeDef,
     ListTablesResponseTypeDef,
     ListStatementsResponseTypeDef,
 )
 
 
 def get_structure() -> BatchExecuteStatementInputRequestTypeDef:
@@ -382,43 +382,43 @@
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

### Comparing `types-aiobotocore-redshift-data-2.5.0.post1/types_aiobotocore_redshift_data.egg-info/SOURCES.txt` & `types-aiobotocore-redshift-data-2.5.1/types_aiobotocore_redshift_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

