# Comparing `tmp/types-aiobotocore-dynamodbstreams-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-dynamodbstreams-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-dynamodbstreams-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:32 2023, max compression
+gzip compressed data, was "types-aiobotocore-dynamodbstreams-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1.tar` & `types-aiobotocore-dynamodbstreams-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.235149 types-aiobotocore-dynamodbstreams-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13047 2023-03-11 12:26:32.235149 types-aiobotocore-dynamodbstreams-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11444 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:32.235149 types-aiobotocore-dynamodbstreams-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.235149 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/
--rw-r--r--   0 runner    (1001) docker     (123)      506 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      505 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6920 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6908 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8393 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8391 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6302 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6295 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.235149 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13047 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.870128 types-aiobotocore-dynamodbstreams-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13047 2023-06-28 01:43:24.870128 types-aiobotocore-dynamodbstreams-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11450 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.870128 types-aiobotocore-dynamodbstreams-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2174 2023-06-28 01:29:34.000000 types-aiobotocore-dynamodbstreams-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.866128 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/
+-rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      505 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6920 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6908 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8602 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8600 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6310 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6303 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:35.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.870128 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13047 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/LICENSE` & `types-aiobotocore-dynamodbstreams-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/PKG-INFO` & `types-aiobotocore-dynamodbstreams-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dynamodbstreams
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DynamoDBStreams 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DynamoDBStreams 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dynamodbstreams"></a>
 
 # types-aiobotocore-dynamodbstreams
 
 [![PyPI - types-aiobotocore-dynamodbstreams](https://img.shields.io/pypi/v/types-aiobotocore-dynamodbstreams.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodbstreams)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dynamodbstreams.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodbstreams)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dynamodbstreams?color=blue)](https://pypistats.org/packages/types-aiobotocore-dynamodbstreams)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DynamoDBStreams 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams)
+[aiobotocore.DynamoDBStreams 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams)
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
 [types-aiobotocore-dynamodbstreams docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,24 +296,24 @@
 `types_aiobotocore_dynamodbstreams.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dynamodbstreams.type_defs import (
     AttributeValueTypeDef,
     DescribeStreamInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     GetRecordsInputRequestTypeDef,
     GetShardIteratorInputRequestTypeDef,
+    GetShardIteratorOutputTypeDef,
     IdentityTypeDef,
     KeySchemaElementTypeDef,
     ListStreamsInputRequestTypeDef,
     StreamTypeDef,
     StreamRecordTypeDef,
+    ResponseMetadataTypeDef,
     SequenceNumberRangeTypeDef,
-    GetShardIteratorOutputTypeDef,
     ListStreamsOutputTypeDef,
     RecordTypeDef,
     ShardTypeDef,
     GetRecordsOutputTypeDef,
     StreamDescriptionTypeDef,
     DescribeStreamOutputTypeDef,
 )
@@ -326,43 +326,43 @@
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/README.md` & `types-aiobotocore-dynamodbstreams-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-dynamodbstreams"></a>
 
 # types-aiobotocore-dynamodbstreams
 
 [![PyPI - types-aiobotocore-dynamodbstreams](https://img.shields.io/pypi/v/types-aiobotocore-dynamodbstreams.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodbstreams)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dynamodbstreams.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodbstreams)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dynamodbstreams?color=blue)](https://pypistats.org/packages/types-aiobotocore-dynamodbstreams)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DynamoDBStreams 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams)
+[aiobotocore.DynamoDBStreams 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams)
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
 [types-aiobotocore-dynamodbstreams docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/).
 
 See how it helps to find and fix potential bugs:
 
@@ -263,24 +263,24 @@
 `types_aiobotocore_dynamodbstreams.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dynamodbstreams.type_defs import (
     AttributeValueTypeDef,
     DescribeStreamInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     GetRecordsInputRequestTypeDef,
     GetShardIteratorInputRequestTypeDef,
+    GetShardIteratorOutputTypeDef,
     IdentityTypeDef,
     KeySchemaElementTypeDef,
     ListStreamsInputRequestTypeDef,
     StreamTypeDef,
     StreamRecordTypeDef,
+    ResponseMetadataTypeDef,
     SequenceNumberRangeTypeDef,
-    GetShardIteratorOutputTypeDef,
     ListStreamsOutputTypeDef,
     RecordTypeDef,
     ShardTypeDef,
     GetRecordsOutputTypeDef,
     StreamDescriptionTypeDef,
     DescribeStreamOutputTypeDef,
 )
@@ -293,43 +293,43 @@
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/setup.py` & `types-aiobotocore-dynamodbstreams-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-dynamodbstreams.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-dynamodbstreams",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_dynamodbstreams"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DynamoDBStreams 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DynamoDBStreams 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/"
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/__main__.py` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DynamoDBStreams 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DynamoDBStreams 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams\nOther"
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/client.py` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/client.pyi` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/literals.py` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -98,14 +98,15 @@
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
@@ -184,14 +185,15 @@
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
@@ -202,14 +204,15 @@
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
@@ -245,14 +248,15 @@
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
@@ -271,16 +275,19 @@
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
@@ -364,15 +371,17 @@
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/literals.pyi` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -96,14 +96,15 @@
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
@@ -182,14 +183,15 @@
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
@@ -200,14 +202,15 @@
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
@@ -243,14 +246,15 @@
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
@@ -269,16 +273,19 @@
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
@@ -362,15 +369,17 @@
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/type_defs.py` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -28,24 +28,24 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AttributeValueTypeDef",
     "DescribeStreamInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "GetRecordsInputRequestTypeDef",
     "GetShardIteratorInputRequestTypeDef",
+    "GetShardIteratorOutputTypeDef",
     "IdentityTypeDef",
     "KeySchemaElementTypeDef",
     "ListStreamsInputRequestTypeDef",
     "StreamTypeDef",
     "StreamRecordTypeDef",
+    "ResponseMetadataTypeDef",
     "SequenceNumberRangeTypeDef",
-    "GetShardIteratorOutputTypeDef",
     "ListStreamsOutputTypeDef",
     "RecordTypeDef",
     "ShardTypeDef",
     "GetRecordsOutputTypeDef",
     "StreamDescriptionTypeDef",
     "DescribeStreamOutputTypeDef",
 )
@@ -85,25 +85,14 @@
 
 class DescribeStreamInputRequestTypeDef(
     _RequiredDescribeStreamInputRequestTypeDef, _OptionalDescribeStreamInputRequestTypeDef
 ):
     pass
 
 
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
 _RequiredGetRecordsInputRequestTypeDef = TypedDict(
     "_RequiredGetRecordsInputRequestTypeDef",
     {
         "ShardIterator": str,
     },
 )
 _OptionalGetRecordsInputRequestTypeDef = TypedDict(
@@ -140,14 +129,22 @@
 
 class GetShardIteratorInputRequestTypeDef(
     _RequiredGetShardIteratorInputRequestTypeDef, _OptionalGetShardIteratorInputRequestTypeDef
 ):
     pass
 
 
+GetShardIteratorOutputTypeDef = TypedDict(
+    "GetShardIteratorOutputTypeDef",
+    {
+        "ShardIterator": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IdentityTypeDef = TypedDict(
     "IdentityTypeDef",
     {
         "PrincipalId": str,
         "Type": str,
     },
     total=False,
@@ -191,37 +188,40 @@
         "SequenceNumber": str,
         "SizeBytes": int,
         "StreamViewType": StreamViewTypeType,
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
 SequenceNumberRangeTypeDef = TypedDict(
     "SequenceNumberRangeTypeDef",
     {
         "StartingSequenceNumber": str,
         "EndingSequenceNumber": str,
     },
     total=False,
 )
 
-GetShardIteratorOutputTypeDef = TypedDict(
-    "GetShardIteratorOutputTypeDef",
-    {
-        "ShardIterator": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListStreamsOutputTypeDef = TypedDict(
     "ListStreamsOutputTypeDef",
     {
         "Streams": List[StreamTypeDef],
         "LastEvaluatedStreamArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecordTypeDef = TypedDict(
     "RecordTypeDef",
     {
         "eventID": str,
@@ -246,15 +246,15 @@
 )
 
 GetRecordsOutputTypeDef = TypedDict(
     "GetRecordsOutputTypeDef",
     {
         "Records": List[RecordTypeDef],
         "NextShardIterator": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StreamDescriptionTypeDef = TypedDict(
     "StreamDescriptionTypeDef",
     {
         "StreamArn": str,
@@ -270,10 +270,10 @@
     total=False,
 )
 
 DescribeStreamOutputTypeDef = TypedDict(
     "DescribeStreamOutputTypeDef",
     {
         "StreamDescription": StreamDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams/type_defs.pyi` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -27,24 +27,24 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AttributeValueTypeDef",
     "DescribeStreamInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "GetRecordsInputRequestTypeDef",
     "GetShardIteratorInputRequestTypeDef",
+    "GetShardIteratorOutputTypeDef",
     "IdentityTypeDef",
     "KeySchemaElementTypeDef",
     "ListStreamsInputRequestTypeDef",
     "StreamTypeDef",
     "StreamRecordTypeDef",
+    "ResponseMetadataTypeDef",
     "SequenceNumberRangeTypeDef",
-    "GetShardIteratorOutputTypeDef",
     "ListStreamsOutputTypeDef",
     "RecordTypeDef",
     "ShardTypeDef",
     "GetRecordsOutputTypeDef",
     "StreamDescriptionTypeDef",
     "DescribeStreamOutputTypeDef",
 )
@@ -82,25 +82,14 @@
 )
 
 class DescribeStreamInputRequestTypeDef(
     _RequiredDescribeStreamInputRequestTypeDef, _OptionalDescribeStreamInputRequestTypeDef
 ):
     pass
 
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
 _RequiredGetRecordsInputRequestTypeDef = TypedDict(
     "_RequiredGetRecordsInputRequestTypeDef",
     {
         "ShardIterator": str,
     },
 )
 _OptionalGetRecordsInputRequestTypeDef = TypedDict(
@@ -133,14 +122,22 @@
 )
 
 class GetShardIteratorInputRequestTypeDef(
     _RequiredGetShardIteratorInputRequestTypeDef, _OptionalGetShardIteratorInputRequestTypeDef
 ):
     pass
 
+GetShardIteratorOutputTypeDef = TypedDict(
+    "GetShardIteratorOutputTypeDef",
+    {
+        "ShardIterator": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IdentityTypeDef = TypedDict(
     "IdentityTypeDef",
     {
         "PrincipalId": str,
         "Type": str,
     },
     total=False,
@@ -184,37 +181,40 @@
         "SequenceNumber": str,
         "SizeBytes": int,
         "StreamViewType": StreamViewTypeType,
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
 SequenceNumberRangeTypeDef = TypedDict(
     "SequenceNumberRangeTypeDef",
     {
         "StartingSequenceNumber": str,
         "EndingSequenceNumber": str,
     },
     total=False,
 )
 
-GetShardIteratorOutputTypeDef = TypedDict(
-    "GetShardIteratorOutputTypeDef",
-    {
-        "ShardIterator": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListStreamsOutputTypeDef = TypedDict(
     "ListStreamsOutputTypeDef",
     {
         "Streams": List[StreamTypeDef],
         "LastEvaluatedStreamArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecordTypeDef = TypedDict(
     "RecordTypeDef",
     {
         "eventID": str,
@@ -239,15 +239,15 @@
 )
 
 GetRecordsOutputTypeDef = TypedDict(
     "GetRecordsOutputTypeDef",
     {
         "Records": List[RecordTypeDef],
         "NextShardIterator": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StreamDescriptionTypeDef = TypedDict(
     "StreamDescriptionTypeDef",
     {
         "StreamArn": str,
@@ -263,10 +263,10 @@
     total=False,
 )
 
 DescribeStreamOutputTypeDef = TypedDict(
     "DescribeStreamOutputTypeDef",
     {
         "StreamDescription": StreamDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/PKG-INFO` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dynamodbstreams
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DynamoDBStreams 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DynamoDBStreams 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dynamodbstreams"></a>
 
 # types-aiobotocore-dynamodbstreams
 
 [![PyPI - types-aiobotocore-dynamodbstreams](https://img.shields.io/pypi/v/types-aiobotocore-dynamodbstreams.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodbstreams)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dynamodbstreams.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodbstreams)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dynamodbstreams?color=blue)](https://pypistats.org/packages/types-aiobotocore-dynamodbstreams)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DynamoDBStreams 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams)
+[aiobotocore.DynamoDBStreams 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodbstreams.html#DynamoDBStreams)
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
 [types-aiobotocore-dynamodbstreams docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodbstreams/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,24 +296,24 @@
 `types_aiobotocore_dynamodbstreams.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dynamodbstreams.type_defs import (
     AttributeValueTypeDef,
     DescribeStreamInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     GetRecordsInputRequestTypeDef,
     GetShardIteratorInputRequestTypeDef,
+    GetShardIteratorOutputTypeDef,
     IdentityTypeDef,
     KeySchemaElementTypeDef,
     ListStreamsInputRequestTypeDef,
     StreamTypeDef,
     StreamRecordTypeDef,
+    ResponseMetadataTypeDef,
     SequenceNumberRangeTypeDef,
-    GetShardIteratorOutputTypeDef,
     ListStreamsOutputTypeDef,
     RecordTypeDef,
     ShardTypeDef,
     GetRecordsOutputTypeDef,
     StreamDescriptionTypeDef,
     DescribeStreamOutputTypeDef,
 )
@@ -326,43 +326,43 @@
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

### Comparing `types-aiobotocore-dynamodbstreams-2.5.0.post1/types_aiobotocore_dynamodbstreams.egg-info/SOURCES.txt` & `types-aiobotocore-dynamodbstreams-2.5.1/types_aiobotocore_dynamodbstreams.egg-info/SOURCES.txt`

 * *Files identical despite different names*

