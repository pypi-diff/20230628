# Comparing `tmp/types-aiobotocore-workmailmessageflow-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-workmailmessageflow-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-workmailmessageflow-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-workmailmessageflow-2.5.1.tar", last modified: Wed Jun 28 01:44:20 2023, max compression
```

## Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1.tar` & `types-aiobotocore-workmailmessageflow-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.295721 types-aiobotocore-workmailmessageflow-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12844 2023-03-11 12:27:30.287721 types-aiobotocore-workmailmessageflow-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11225 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.295721 types-aiobotocore-workmailmessageflow-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2200 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.283721 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/
--rw-r--r--   0 runner    (1001) docker     (123)      538 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      537 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5596 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5586 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7404 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7402 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2109 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2106 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:43.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.287721 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12844 2023-03-11 12:27:30.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:27:30.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:30.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.000000 types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.830233 types-aiobotocore-workmailmessageflow-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12848 2023-06-28 01:44:20.830233 types-aiobotocore-workmailmessageflow-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11235 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.830233 types-aiobotocore-workmailmessageflow-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2194 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.830233 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/
+-rw-r--r--   0 runner    (1001) docker     (123)      538 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      979 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5596 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5586 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7613 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7611 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2108 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:39.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.830233 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12848 2023-06-28 01:44:20.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:44:20.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:20.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.000000 types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/LICENSE` & `types-aiobotocore-workmailmessageflow-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/PKG-INFO` & `types-aiobotocore-workmailmessageflow-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workmailmessageflow
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkMailMessageFlow 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkMailMessageFlow 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workmailmessageflow"></a>
 
 # types-aiobotocore-workmailmessageflow
 
 [![PyPI - types-aiobotocore-workmailmessageflow](https://img.shields.io/pypi/v/types-aiobotocore-workmailmessageflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmailmessageflow)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workmailmessageflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmailmessageflow)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workmailmessageflow?color=blue)](https://pypistats.org/packages/types-aiobotocore-workmailmessageflow)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkMailMessageFlow 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
+[aiobotocore.WorkMailMessageFlow 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
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
 [types-aiobotocore-workmailmessageflow docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,17 +289,17 @@
 
 `types_aiobotocore_workmailmessageflow.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workmailmessageflow.type_defs import (
     GetRawMessageContentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    S3ReferenceTypeDef,
     GetRawMessageContentResponseTypeDef,
+    S3ReferenceTypeDef,
+    ResponseMetadataTypeDef,
     RawMessageContentTypeDef,
     PutRawMessageContentRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetRawMessageContentRequestRequestTypeDef:
     return {...}
@@ -308,43 +308,43 @@
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/README.md` & `types-aiobotocore-workmailmessageflow-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-workmailmessageflow"></a>
 
 # types-aiobotocore-workmailmessageflow
 
 [![PyPI - types-aiobotocore-workmailmessageflow](https://img.shields.io/pypi/v/types-aiobotocore-workmailmessageflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmailmessageflow)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workmailmessageflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmailmessageflow)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workmailmessageflow?color=blue)](https://pypistats.org/packages/types-aiobotocore-workmailmessageflow)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkMailMessageFlow 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
+[aiobotocore.WorkMailMessageFlow 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
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
 [types-aiobotocore-workmailmessageflow docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/).
 
 See how it helps to find and fix potential bugs:
 
@@ -256,17 +256,17 @@
 
 `types_aiobotocore_workmailmessageflow.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workmailmessageflow.type_defs import (
     GetRawMessageContentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    S3ReferenceTypeDef,
     GetRawMessageContentResponseTypeDef,
+    S3ReferenceTypeDef,
+    ResponseMetadataTypeDef,
     RawMessageContentTypeDef,
     PutRawMessageContentRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetRawMessageContentRequestRequestTypeDef:
     return {...}
@@ -275,43 +275,43 @@
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/setup.py` & `types-aiobotocore-workmailmessageflow-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-workmailmessageflow.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-workmailmessageflow",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_workmailmessageflow"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WorkMailMessageFlow 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.WorkMailMessageFlow 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/",
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/__init__.py` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/__init__.pyi` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/__main__.py` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WorkMailMessageFlow 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WorkMailMessageFlow 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow\nOther"
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/client.py` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/client.pyi` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/literals.py` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -14,18 +14,16 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("WorkMailMessageFlowServiceName", "ServiceName", "ResourceServiceName")
 
-
 WorkMailMessageFlowServiceName = Literal["workmailmessageflow"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -81,14 +79,15 @@
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
@@ -167,14 +166,15 @@
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
@@ -185,14 +185,15 @@
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
@@ -228,14 +229,15 @@
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
@@ -254,16 +256,19 @@
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
@@ -347,15 +352,17 @@
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/literals.pyi` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,16 +14,18 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("WorkMailMessageFlowServiceName", "ServiceName", "ResourceServiceName")
 
+
 WorkMailMessageFlowServiceName = Literal["workmailmessageflow"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -79,14 +81,15 @@
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
@@ -165,14 +168,15 @@
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
@@ -183,14 +187,15 @@
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
@@ -226,14 +231,15 @@
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
@@ -252,16 +258,19 @@
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
@@ -345,15 +354,17 @@
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/type_defs.py` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,36 +20,33 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "GetRawMessageContentRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "S3ReferenceTypeDef",
     "GetRawMessageContentResponseTypeDef",
+    "S3ReferenceTypeDef",
+    "ResponseMetadataTypeDef",
     "RawMessageContentTypeDef",
     "PutRawMessageContentRequestRequestTypeDef",
 )
 
 GetRawMessageContentRequestRequestTypeDef = TypedDict(
     "GetRawMessageContentRequestRequestTypeDef",
     {
         "messageId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetRawMessageContentResponseTypeDef = TypedDict(
+    "GetRawMessageContentResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "messageContent": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredS3ReferenceTypeDef = TypedDict(
     "_RequiredS3ReferenceTypeDef",
     {
         "bucket": str,
@@ -65,19 +62,22 @@
 )
 
 
 class S3ReferenceTypeDef(_RequiredS3ReferenceTypeDef, _OptionalS3ReferenceTypeDef):
     pass
 
 
-GetRawMessageContentResponseTypeDef = TypedDict(
-    "GetRawMessageContentResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "messageContent": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 RawMessageContentTypeDef = TypedDict(
     "RawMessageContentTypeDef",
     {
         "s3Reference": S3ReferenceTypeDef,
```

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow/type_defs.pyi` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -19,36 +19,33 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "GetRawMessageContentRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "S3ReferenceTypeDef",
     "GetRawMessageContentResponseTypeDef",
+    "S3ReferenceTypeDef",
+    "ResponseMetadataTypeDef",
     "RawMessageContentTypeDef",
     "PutRawMessageContentRequestRequestTypeDef",
 )
 
 GetRawMessageContentRequestRequestTypeDef = TypedDict(
     "GetRawMessageContentRequestRequestTypeDef",
     {
         "messageId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetRawMessageContentResponseTypeDef = TypedDict(
+    "GetRawMessageContentResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "messageContent": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredS3ReferenceTypeDef = TypedDict(
     "_RequiredS3ReferenceTypeDef",
     {
         "bucket": str,
@@ -62,19 +59,22 @@
     },
     total=False,
 )
 
 class S3ReferenceTypeDef(_RequiredS3ReferenceTypeDef, _OptionalS3ReferenceTypeDef):
     pass
 
-GetRawMessageContentResponseTypeDef = TypedDict(
-    "GetRawMessageContentResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "messageContent": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 RawMessageContentTypeDef = TypedDict(
     "RawMessageContentTypeDef",
     {
         "s3Reference": S3ReferenceTypeDef,
```

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/PKG-INFO` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workmailmessageflow
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkMailMessageFlow 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkMailMessageFlow 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workmailmessageflow"></a>
 
 # types-aiobotocore-workmailmessageflow
 
 [![PyPI - types-aiobotocore-workmailmessageflow](https://img.shields.io/pypi/v/types-aiobotocore-workmailmessageflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmailmessageflow)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workmailmessageflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workmailmessageflow)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workmailmessageflow?color=blue)](https://pypistats.org/packages/types-aiobotocore-workmailmessageflow)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkMailMessageFlow 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
+[aiobotocore.WorkMailMessageFlow 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workmailmessageflow.html#WorkMailMessageFlow)
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
 [types-aiobotocore-workmailmessageflow docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workmailmessageflow/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,17 +289,17 @@
 
 `types_aiobotocore_workmailmessageflow.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workmailmessageflow.type_defs import (
     GetRawMessageContentRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    S3ReferenceTypeDef,
     GetRawMessageContentResponseTypeDef,
+    S3ReferenceTypeDef,
+    ResponseMetadataTypeDef,
     RawMessageContentTypeDef,
     PutRawMessageContentRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetRawMessageContentRequestRequestTypeDef:
     return {...}
@@ -308,43 +308,43 @@
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

### Comparing `types-aiobotocore-workmailmessageflow-2.5.0.post1/types_aiobotocore_workmailmessageflow.egg-info/SOURCES.txt` & `types-aiobotocore-workmailmessageflow-2.5.1/types_aiobotocore_workmailmessageflow.egg-info/SOURCES.txt`

 * *Files identical despite different names*

