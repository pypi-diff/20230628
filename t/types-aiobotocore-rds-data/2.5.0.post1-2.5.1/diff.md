# Comparing `tmp/types-aiobotocore-rds-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-rds-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-rds-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-rds-data-2.5.1.tar", last modified: Wed Jun 28 01:44:01 2023, max compression
```

## Comparing `types-aiobotocore-rds-data-2.5.0.post1.tar` & `types-aiobotocore-rds-data-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.795534 types-aiobotocore-rds-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:06.000000 types-aiobotocore-rds-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13022 2023-03-11 12:27:10.795534 types-aiobotocore-rds-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11441 2023-03-11 12:22:06.000000 types-aiobotocore-rds-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:10.795534 types-aiobotocore-rds-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2137 2023-03-11 12:22:06.000000 types-aiobotocore-rds-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.795534 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/
--rw-r--r--   0 runner    (1001) docker     (123)      480 2023-03-11 12:22:06.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      479 2023-03-11 12:22:06.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8553 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8539 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7987 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7985 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8905 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8896 2023-03-11 12:22:07.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:06.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.795534 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13022 2023-03-11 12:27:10.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:10.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:10.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:10.000000 types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.322196 types-aiobotocore-rds-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13015 2023-06-28 01:44:01.322196 types-aiobotocore-rds-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11440 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:01.322196 types-aiobotocore-rds-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-06-28 01:38:52.000000 types-aiobotocore-rds-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.318196 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/
+-rw-r--r--   0 runner    (1001) docker     (123)      480 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      479 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8553 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8539 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8196 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8194 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8917 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8908 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:38:53.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.322196 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13015 2023-06-28 01:44:01.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:44:01.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:01.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:01.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:01.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:01.000000 types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/LICENSE` & `types-aiobotocore-rds-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-rds-data-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rds-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RDSDataService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RDSDataService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rds-data"></a>
 
 # types-aiobotocore-rds-data
 
 [![PyPI - types-aiobotocore-rds-data](https://img.shields.io/pypi/v/types-aiobotocore-rds-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rds-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rds-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-rds-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RDSDataService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
+[aiobotocore.RDSDataService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
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
 [types-aiobotocore-rds-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,28 +294,28 @@
 
 `types_aiobotocore_rds_data.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rds_data.type_defs import (
     ArrayValueTypeDef,
-    ResponseMetadataTypeDef,
     BeginTransactionRequestRequestTypeDef,
+    BeginTransactionResponseTypeDef,
     ColumnMetadataTypeDef,
     CommitTransactionRequestRequestTypeDef,
+    CommitTransactionResponseTypeDef,
     ExecuteSqlRequestRequestTypeDef,
     ResultSetOptionsTypeDef,
     FieldTypeDef,
     RecordTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTransactionRequestRequestTypeDef,
+    RollbackTransactionResponseTypeDef,
     StructValueTypeDef,
     ValueTypeDef,
-    BeginTransactionResponseTypeDef,
-    CommitTransactionResponseTypeDef,
-    RollbackTransactionResponseTypeDef,
     ResultSetMetadataTypeDef,
     ExecuteStatementResponseTypeDef,
     SqlParameterTypeDef,
     UpdateResultTypeDef,
     ResultFrameTypeDef,
     BatchExecuteStatementRequestRequestTypeDef,
     ExecuteStatementRequestRequestTypeDef,
@@ -332,43 +332,43 @@
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/README.md` & `types-aiobotocore-rds-data-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-rds-data"></a>
 
 # types-aiobotocore-rds-data
 
 [![PyPI - types-aiobotocore-rds-data](https://img.shields.io/pypi/v/types-aiobotocore-rds-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rds-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rds-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-rds-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RDSDataService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
+[aiobotocore.RDSDataService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
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
 [types-aiobotocore-rds-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,28 +261,28 @@
 
 `types_aiobotocore_rds_data.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rds_data.type_defs import (
     ArrayValueTypeDef,
-    ResponseMetadataTypeDef,
     BeginTransactionRequestRequestTypeDef,
+    BeginTransactionResponseTypeDef,
     ColumnMetadataTypeDef,
     CommitTransactionRequestRequestTypeDef,
+    CommitTransactionResponseTypeDef,
     ExecuteSqlRequestRequestTypeDef,
     ResultSetOptionsTypeDef,
     FieldTypeDef,
     RecordTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTransactionRequestRequestTypeDef,
+    RollbackTransactionResponseTypeDef,
     StructValueTypeDef,
     ValueTypeDef,
-    BeginTransactionResponseTypeDef,
-    CommitTransactionResponseTypeDef,
-    RollbackTransactionResponseTypeDef,
     ResultSetMetadataTypeDef,
     ExecuteStatementResponseTypeDef,
     SqlParameterTypeDef,
     UpdateResultTypeDef,
     ResultFrameTypeDef,
     BatchExecuteStatementRequestRequestTypeDef,
     ExecuteStatementRequestRequestTypeDef,
@@ -299,43 +299,43 @@
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/setup.py` & `types-aiobotocore-rds-data-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-rds-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-rds-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_rds_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RDSDataService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.RDSDataService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/"
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/__main__.py` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RDSDataService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RDSDataService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService\nOther"
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/client.py` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/client.pyi` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/literals.py` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,27 +14,25 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DecimalReturnTypeType",
     "LongReturnTypeType",
     "RecordsFormatTypeType",
     "TypeHintType",
     "RDSDataServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 DecimalReturnTypeType = Literal["DOUBLE_OR_LONG", "STRING"]
 LongReturnTypeType = Literal["LONG", "STRING"]
 RecordsFormatTypeType = Literal["JSON", "NONE"]
 TypeHintType = Literal["DATE", "DECIMAL", "JSON", "TIME", "TIMESTAMP", "UUID"]
 RDSDataServiceServiceName = Literal["rds-data"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -94,14 +92,15 @@
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
@@ -180,14 +179,15 @@
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
@@ -198,14 +198,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -267,16 +269,19 @@
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
@@ -360,15 +365,17 @@
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/literals.pyi` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,25 +14,27 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DecimalReturnTypeType",
     "LongReturnTypeType",
     "RecordsFormatTypeType",
     "TypeHintType",
     "RDSDataServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 DecimalReturnTypeType = Literal["DOUBLE_OR_LONG", "STRING"]
 LongReturnTypeType = Literal["LONG", "STRING"]
 RecordsFormatTypeType = Literal["JSON", "NONE"]
 TypeHintType = Literal["DATE", "DECIMAL", "JSON", "TIME", "TIMESTAMP", "UUID"]
 RDSDataServiceServiceName = Literal["rds-data"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -92,14 +94,15 @@
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
@@ -178,14 +181,15 @@
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
@@ -196,14 +200,15 @@
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
@@ -239,14 +244,15 @@
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
@@ -265,16 +271,19 @@
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
@@ -358,15 +367,17 @@
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/type_defs.py` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -19,31 +19,30 @@
 from .literals import DecimalReturnTypeType, LongReturnTypeType, RecordsFormatTypeType, TypeHintType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ArrayValueTypeDef",
-    "ResponseMetadataTypeDef",
     "BeginTransactionRequestRequestTypeDef",
+    "BeginTransactionResponseTypeDef",
     "ColumnMetadataTypeDef",
     "CommitTransactionRequestRequestTypeDef",
+    "CommitTransactionResponseTypeDef",
     "ExecuteSqlRequestRequestTypeDef",
     "ResultSetOptionsTypeDef",
     "FieldTypeDef",
     "RecordTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackTransactionRequestRequestTypeDef",
+    "RollbackTransactionResponseTypeDef",
     "StructValueTypeDef",
     "ValueTypeDef",
-    "BeginTransactionResponseTypeDef",
-    "CommitTransactionResponseTypeDef",
-    "RollbackTransactionResponseTypeDef",
     "ResultSetMetadataTypeDef",
     "ExecuteStatementResponseTypeDef",
     "SqlParameterTypeDef",
     "UpdateResultTypeDef",
     "ResultFrameTypeDef",
     "BatchExecuteStatementRequestRequestTypeDef",
     "ExecuteStatementRequestRequestTypeDef",
@@ -60,25 +59,14 @@
         "doubleValues": Sequence[float],
         "stringValues": Sequence[str],
         "arrayValues": Sequence[Dict[str, Any]],
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
 _RequiredBeginTransactionRequestRequestTypeDef = TypedDict(
     "_RequiredBeginTransactionRequestRequestTypeDef",
     {
         "resourceArn": str,
         "secretArn": str,
     },
 )
@@ -87,20 +75,26 @@
     {
         "database": str,
         "schema": str,
     },
     total=False,
 )
 
-
 class BeginTransactionRequestRequestTypeDef(
     _RequiredBeginTransactionRequestRequestTypeDef, _OptionalBeginTransactionRequestRequestTypeDef
 ):
     pass
 
+BeginTransactionResponseTypeDef = TypedDict(
+    "BeginTransactionResponseTypeDef",
+    {
+        "transactionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ColumnMetadataTypeDef = TypedDict(
     "ColumnMetadataTypeDef",
     {
         "name": str,
         "type": int,
         "typeName": str,
@@ -124,14 +118,22 @@
     {
         "resourceArn": str,
         "secretArn": str,
         "transactionId": str,
     },
 )
 
+CommitTransactionResponseTypeDef = TypedDict(
+    "CommitTransactionResponseTypeDef",
+    {
+        "transactionStatus": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExecuteSqlRequestRequestTypeDef = TypedDict(
     "_RequiredExecuteSqlRequestRequestTypeDef",
     {
         "dbClusterOrInstanceArn": str,
         "awsSecretStoreArn": str,
         "sqlStatements": str,
     },
@@ -141,21 +143,19 @@
     {
         "database": str,
         "schema": str,
     },
     total=False,
 )
 
-
 class ExecuteSqlRequestRequestTypeDef(
     _RequiredExecuteSqlRequestRequestTypeDef, _OptionalExecuteSqlRequestRequestTypeDef
 ):
     pass
 
-
 ResultSetOptionsTypeDef = TypedDict(
     "ResultSetOptionsTypeDef",
     {
         "decimalReturnType": DecimalReturnTypeType,
         "longReturnType": LongReturnTypeType,
     },
     total=False,
@@ -179,23 +179,42 @@
     "RecordTypeDef",
     {
         "values": List["ValueTypeDef"],
     },
     total=False,
 )
 
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
 RollbackTransactionRequestRequestTypeDef = TypedDict(
     "RollbackTransactionRequestRequestTypeDef",
     {
         "resourceArn": str,
         "secretArn": str,
         "transactionId": str,
     },
 )
 
+RollbackTransactionResponseTypeDef = TypedDict(
+    "RollbackTransactionResponseTypeDef",
+    {
+        "transactionStatus": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StructValueTypeDef = TypedDict(
     "StructValueTypeDef",
     {
         "attributes": List[Dict[str, Any]],
     },
     total=False,
 )
@@ -213,38 +232,14 @@
         "blobValue": bytes,
         "arrayValues": List[Dict[str, Any]],
         "structValue": Dict[str, Any],
     },
     total=False,
 )
 
-BeginTransactionResponseTypeDef = TypedDict(
-    "BeginTransactionResponseTypeDef",
-    {
-        "transactionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CommitTransactionResponseTypeDef = TypedDict(
-    "CommitTransactionResponseTypeDef",
-    {
-        "transactionStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RollbackTransactionResponseTypeDef = TypedDict(
-    "RollbackTransactionResponseTypeDef",
-    {
-        "transactionStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ResultSetMetadataTypeDef = TypedDict(
     "ResultSetMetadataTypeDef",
     {
         "columnCount": int,
         "columnMetadata": List[ColumnMetadataTypeDef],
     },
     total=False,
@@ -254,15 +249,15 @@
     "ExecuteStatementResponseTypeDef",
     {
         "records": List[List[FieldTypeDef]],
         "columnMetadata": List[ColumnMetadataTypeDef],
         "numberOfRecordsUpdated": int,
         "generatedFields": List[FieldTypeDef],
         "formattedRecords": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlParameterTypeDef = TypedDict(
     "SqlParameterTypeDef",
     {
         "name": str,
@@ -304,22 +299,20 @@
         "schema": str,
         "parameterSets": Sequence[Sequence[SqlParameterTypeDef]],
         "transactionId": str,
     },
     total=False,
 )
 
-
 class BatchExecuteStatementRequestRequestTypeDef(
     _RequiredBatchExecuteStatementRequestRequestTypeDef,
     _OptionalBatchExecuteStatementRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredExecuteStatementRequestRequestTypeDef = TypedDict(
     "_RequiredExecuteStatementRequestRequestTypeDef",
     {
         "resourceArn": str,
         "secretArn": str,
         "sql": str,
     },
@@ -335,26 +328,24 @@
         "continueAfterTimeout": bool,
         "resultSetOptions": ResultSetOptionsTypeDef,
         "formatRecordsAs": RecordsFormatTypeType,
     },
     total=False,
 )
 
-
 class ExecuteStatementRequestRequestTypeDef(
     _RequiredExecuteStatementRequestRequestTypeDef, _OptionalExecuteStatementRequestRequestTypeDef
 ):
     pass
 
-
 BatchExecuteStatementResponseTypeDef = TypedDict(
     "BatchExecuteStatementResponseTypeDef",
     {
         "updateResults": List[UpdateResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlStatementResultTypeDef = TypedDict(
     "SqlStatementResultTypeDef",
     {
         "resultFrame": ResultFrameTypeDef,
@@ -363,10 +354,10 @@
     total=False,
 )
 
 ExecuteSqlResponseTypeDef = TypedDict(
     "ExecuteSqlResponseTypeDef",
     {
         "sqlStatementResults": List[SqlStatementResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data/type_defs.pyi` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -19,30 +19,31 @@
 from .literals import DecimalReturnTypeType, LongReturnTypeType, RecordsFormatTypeType, TypeHintType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ArrayValueTypeDef",
-    "ResponseMetadataTypeDef",
     "BeginTransactionRequestRequestTypeDef",
+    "BeginTransactionResponseTypeDef",
     "ColumnMetadataTypeDef",
     "CommitTransactionRequestRequestTypeDef",
+    "CommitTransactionResponseTypeDef",
     "ExecuteSqlRequestRequestTypeDef",
     "ResultSetOptionsTypeDef",
     "FieldTypeDef",
     "RecordTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackTransactionRequestRequestTypeDef",
+    "RollbackTransactionResponseTypeDef",
     "StructValueTypeDef",
     "ValueTypeDef",
-    "BeginTransactionResponseTypeDef",
-    "CommitTransactionResponseTypeDef",
-    "RollbackTransactionResponseTypeDef",
     "ResultSetMetadataTypeDef",
     "ExecuteStatementResponseTypeDef",
     "SqlParameterTypeDef",
     "UpdateResultTypeDef",
     "ResultFrameTypeDef",
     "BatchExecuteStatementRequestRequestTypeDef",
     "ExecuteStatementRequestRequestTypeDef",
@@ -59,25 +60,14 @@
         "doubleValues": Sequence[float],
         "stringValues": Sequence[str],
         "arrayValues": Sequence[Dict[str, Any]],
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
 _RequiredBeginTransactionRequestRequestTypeDef = TypedDict(
     "_RequiredBeginTransactionRequestRequestTypeDef",
     {
         "resourceArn": str,
         "secretArn": str,
     },
 )
@@ -86,19 +76,29 @@
     {
         "database": str,
         "schema": str,
     },
     total=False,
 )
 
+
 class BeginTransactionRequestRequestTypeDef(
     _RequiredBeginTransactionRequestRequestTypeDef, _OptionalBeginTransactionRequestRequestTypeDef
 ):
     pass
 
+
+BeginTransactionResponseTypeDef = TypedDict(
+    "BeginTransactionResponseTypeDef",
+    {
+        "transactionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ColumnMetadataTypeDef = TypedDict(
     "ColumnMetadataTypeDef",
     {
         "name": str,
         "type": int,
         "typeName": str,
         "label": str,
@@ -121,14 +121,22 @@
     {
         "resourceArn": str,
         "secretArn": str,
         "transactionId": str,
     },
 )
 
+CommitTransactionResponseTypeDef = TypedDict(
+    "CommitTransactionResponseTypeDef",
+    {
+        "transactionStatus": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExecuteSqlRequestRequestTypeDef = TypedDict(
     "_RequiredExecuteSqlRequestRequestTypeDef",
     {
         "dbClusterOrInstanceArn": str,
         "awsSecretStoreArn": str,
         "sqlStatements": str,
     },
@@ -138,19 +146,21 @@
     {
         "database": str,
         "schema": str,
     },
     total=False,
 )
 
+
 class ExecuteSqlRequestRequestTypeDef(
     _RequiredExecuteSqlRequestRequestTypeDef, _OptionalExecuteSqlRequestRequestTypeDef
 ):
     pass
 
+
 ResultSetOptionsTypeDef = TypedDict(
     "ResultSetOptionsTypeDef",
     {
         "decimalReturnType": DecimalReturnTypeType,
         "longReturnType": LongReturnTypeType,
     },
     total=False,
@@ -174,23 +184,42 @@
     "RecordTypeDef",
     {
         "values": List["ValueTypeDef"],
     },
     total=False,
 )
 
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
 RollbackTransactionRequestRequestTypeDef = TypedDict(
     "RollbackTransactionRequestRequestTypeDef",
     {
         "resourceArn": str,
         "secretArn": str,
         "transactionId": str,
     },
 )
 
+RollbackTransactionResponseTypeDef = TypedDict(
+    "RollbackTransactionResponseTypeDef",
+    {
+        "transactionStatus": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StructValueTypeDef = TypedDict(
     "StructValueTypeDef",
     {
         "attributes": List[Dict[str, Any]],
     },
     total=False,
 )
@@ -208,38 +237,14 @@
         "blobValue": bytes,
         "arrayValues": List[Dict[str, Any]],
         "structValue": Dict[str, Any],
     },
     total=False,
 )
 
-BeginTransactionResponseTypeDef = TypedDict(
-    "BeginTransactionResponseTypeDef",
-    {
-        "transactionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CommitTransactionResponseTypeDef = TypedDict(
-    "CommitTransactionResponseTypeDef",
-    {
-        "transactionStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RollbackTransactionResponseTypeDef = TypedDict(
-    "RollbackTransactionResponseTypeDef",
-    {
-        "transactionStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ResultSetMetadataTypeDef = TypedDict(
     "ResultSetMetadataTypeDef",
     {
         "columnCount": int,
         "columnMetadata": List[ColumnMetadataTypeDef],
     },
     total=False,
@@ -249,15 +254,15 @@
     "ExecuteStatementResponseTypeDef",
     {
         "records": List[List[FieldTypeDef]],
         "columnMetadata": List[ColumnMetadataTypeDef],
         "numberOfRecordsUpdated": int,
         "generatedFields": List[FieldTypeDef],
         "formattedRecords": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlParameterTypeDef = TypedDict(
     "SqlParameterTypeDef",
     {
         "name": str,
@@ -299,20 +304,22 @@
         "schema": str,
         "parameterSets": Sequence[Sequence[SqlParameterTypeDef]],
         "transactionId": str,
     },
     total=False,
 )
 
+
 class BatchExecuteStatementRequestRequestTypeDef(
     _RequiredBatchExecuteStatementRequestRequestTypeDef,
     _OptionalBatchExecuteStatementRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredExecuteStatementRequestRequestTypeDef = TypedDict(
     "_RequiredExecuteStatementRequestRequestTypeDef",
     {
         "resourceArn": str,
         "secretArn": str,
         "sql": str,
     },
@@ -328,24 +335,26 @@
         "continueAfterTimeout": bool,
         "resultSetOptions": ResultSetOptionsTypeDef,
         "formatRecordsAs": RecordsFormatTypeType,
     },
     total=False,
 )
 
+
 class ExecuteStatementRequestRequestTypeDef(
     _RequiredExecuteStatementRequestRequestTypeDef, _OptionalExecuteStatementRequestRequestTypeDef
 ):
     pass
 
+
 BatchExecuteStatementResponseTypeDef = TypedDict(
     "BatchExecuteStatementResponseTypeDef",
     {
         "updateResults": List[UpdateResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SqlStatementResultTypeDef = TypedDict(
     "SqlStatementResultTypeDef",
     {
         "resultFrame": ResultFrameTypeDef,
@@ -354,10 +363,10 @@
     total=False,
 )
 
 ExecuteSqlResponseTypeDef = TypedDict(
     "ExecuteSqlResponseTypeDef",
     {
         "sqlStatementResults": List[SqlStatementResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/PKG-INFO` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rds-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RDSDataService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RDSDataService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rds-data"></a>
 
 # types-aiobotocore-rds-data
 
 [![PyPI - types-aiobotocore-rds-data](https://img.shields.io/pypi/v/types-aiobotocore-rds-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rds-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rds-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-rds-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RDSDataService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
+[aiobotocore.RDSDataService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds-data.html#RDSDataService)
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
 [types-aiobotocore-rds-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,28 +294,28 @@
 
 `types_aiobotocore_rds_data.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rds_data.type_defs import (
     ArrayValueTypeDef,
-    ResponseMetadataTypeDef,
     BeginTransactionRequestRequestTypeDef,
+    BeginTransactionResponseTypeDef,
     ColumnMetadataTypeDef,
     CommitTransactionRequestRequestTypeDef,
+    CommitTransactionResponseTypeDef,
     ExecuteSqlRequestRequestTypeDef,
     ResultSetOptionsTypeDef,
     FieldTypeDef,
     RecordTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTransactionRequestRequestTypeDef,
+    RollbackTransactionResponseTypeDef,
     StructValueTypeDef,
     ValueTypeDef,
-    BeginTransactionResponseTypeDef,
-    CommitTransactionResponseTypeDef,
-    RollbackTransactionResponseTypeDef,
     ResultSetMetadataTypeDef,
     ExecuteStatementResponseTypeDef,
     SqlParameterTypeDef,
     UpdateResultTypeDef,
     ResultFrameTypeDef,
     BatchExecuteStatementRequestRequestTypeDef,
     ExecuteStatementRequestRequestTypeDef,
@@ -332,43 +332,43 @@
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

### Comparing `types-aiobotocore-rds-data-2.5.0.post1/types_aiobotocore_rds_data.egg-info/SOURCES.txt` & `types-aiobotocore-rds-data-2.5.1/types_aiobotocore_rds_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

