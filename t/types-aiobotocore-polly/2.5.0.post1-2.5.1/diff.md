# Comparing `tmp/types-aiobotocore-polly-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-polly-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-polly-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-polly-2.5.1.tar", last modified: Wed Jun 28 01:44:00 2023, max compression
```

## Comparing `types-aiobotocore-polly-2.5.0.post1.tar` & `types-aiobotocore-polly-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.475511 types-aiobotocore-polly-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14218 2023-03-11 12:27:08.471511 types-aiobotocore-polly-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12655 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.475511 types-aiobotocore-polly-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.463511 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/
--rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12645 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12624 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10339 2023-03-11 12:20:05.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10337 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4502 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4496 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8923 2023-03-11 12:20:05.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8918 2023-03-11 12:20:05.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:20:04.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.471511 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14218 2023-03-11 12:27:08.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-03-11 12:27:08.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:27:08.000000 types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.206194 types-aiobotocore-polly-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14208 2023-06-28 01:44:00.206194 types-aiobotocore-polly-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12651 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:00.206194 types-aiobotocore-polly-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:36:50.000000 types-aiobotocore-polly-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.202194 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/
+-rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12645 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12624 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10609 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10607 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4388 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4383 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8943 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8938 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:51.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.202194 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14208 2023-06-28 01:44:00.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 01:44:00.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:00.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:44:00.000000 types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/LICENSE` & `types-aiobotocore-polly-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-polly-2.5.0.post1/PKG-INFO` & `types-aiobotocore-polly-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-polly
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Polly 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Polly 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-polly"></a>
 
 # types-aiobotocore-polly
 
 [![PyPI - types-aiobotocore-polly](https://img.shields.io/pypi/v/types-aiobotocore-polly.svg?color=blue)](https://pypi.org/project/types-aiobotocore-polly)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-polly.svg?color=blue)](https://pypi.org/project/types-aiobotocore-polly)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-polly?color=blue)](https://pypistats.org/packages/types-aiobotocore-polly)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Polly 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly)
+[aiobotocore.Polly 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly)
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
 [types-aiobotocore-polly docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,31 +331,31 @@
 
 `types_aiobotocore_polly.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_polly.type_defs import (
     DeleteLexiconInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeVoicesInputDescribeVoicesPaginateTypeDef,
     DescribeVoicesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     VoiceTypeDef,
     GetLexiconInputRequestTypeDef,
     LexiconAttributesTypeDef,
     LexiconTypeDef,
     GetSpeechSynthesisTaskInputRequestTypeDef,
     SynthesisTaskTypeDef,
+    ListLexiconsInputListLexiconsPaginateTypeDef,
     ListLexiconsInputRequestTypeDef,
+    ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef,
     ListSpeechSynthesisTasksInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutLexiconInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartSpeechSynthesisTaskInputRequestTypeDef,
     SynthesizeSpeechInputRequestTypeDef,
-    DescribeVoicesInputDescribeVoicesPaginateTypeDef,
-    ListLexiconsInputListLexiconsPaginateTypeDef,
-    ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef,
     SynthesizeSpeechOutputTypeDef,
     DescribeVoicesOutputTypeDef,
     LexiconDescriptionTypeDef,
     GetLexiconOutputTypeDef,
     GetSpeechSynthesisTaskOutputTypeDef,
     ListSpeechSynthesisTasksOutputTypeDef,
     StartSpeechSynthesisTaskOutputTypeDef,
@@ -370,43 +370,43 @@
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

### Comparing `types-aiobotocore-polly-2.5.0.post1/README.md` & `types-aiobotocore-polly-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-polly"></a>
 
 # types-aiobotocore-polly
 
 [![PyPI - types-aiobotocore-polly](https://img.shields.io/pypi/v/types-aiobotocore-polly.svg?color=blue)](https://pypi.org/project/types-aiobotocore-polly)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-polly.svg?color=blue)](https://pypi.org/project/types-aiobotocore-polly)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-polly?color=blue)](https://pypistats.org/packages/types-aiobotocore-polly)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Polly 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly)
+[aiobotocore.Polly 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly)
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
 [types-aiobotocore-polly docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,31 +298,31 @@
 
 `types_aiobotocore_polly.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_polly.type_defs import (
     DeleteLexiconInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeVoicesInputDescribeVoicesPaginateTypeDef,
     DescribeVoicesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     VoiceTypeDef,
     GetLexiconInputRequestTypeDef,
     LexiconAttributesTypeDef,
     LexiconTypeDef,
     GetSpeechSynthesisTaskInputRequestTypeDef,
     SynthesisTaskTypeDef,
+    ListLexiconsInputListLexiconsPaginateTypeDef,
     ListLexiconsInputRequestTypeDef,
+    ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef,
     ListSpeechSynthesisTasksInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutLexiconInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartSpeechSynthesisTaskInputRequestTypeDef,
     SynthesizeSpeechInputRequestTypeDef,
-    DescribeVoicesInputDescribeVoicesPaginateTypeDef,
-    ListLexiconsInputListLexiconsPaginateTypeDef,
-    ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef,
     SynthesizeSpeechOutputTypeDef,
     DescribeVoicesOutputTypeDef,
     LexiconDescriptionTypeDef,
     GetLexiconOutputTypeDef,
     GetSpeechSynthesisTaskOutputTypeDef,
     ListSpeechSynthesisTasksOutputTypeDef,
     StartSpeechSynthesisTaskOutputTypeDef,
@@ -337,43 +337,43 @@
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

### Comparing `types-aiobotocore-polly-2.5.0.post1/setup.py` & `types-aiobotocore-polly-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-polly.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-polly",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_polly"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Polly 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Polly 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/"
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

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/__init__.py` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/__init__.pyi` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/__main__.py` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Polly 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Polly 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly\nOther"
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

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/client.py` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/client.pyi` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/literals.py` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -50,14 +50,15 @@
     "cy-GB",
     "da-DK",
     "de-AT",
     "de-DE",
     "en-AU",
     "en-GB",
     "en-GB-WLS",
+    "en-IE",
     "en-IN",
     "en-NZ",
     "en-US",
     "en-ZA",
     "es-ES",
     "es-MX",
     "es-US",
@@ -147,28 +148,30 @@
     "Mathieu",
     "Matthew",
     "Maxim",
     "Mia",
     "Miguel",
     "Mizuki",
     "Naja",
+    "Niamh",
     "Nicole",
     "Ola",
     "Olivia",
     "Pedro",
     "Penelope",
     "Raveena",
     "Remi",
     "Ricardo",
     "Ruben",
     "Russell",
     "Ruth",
     "Salli",
     "Seoyeon",
     "Sergio",
+    "Sofie",
     "Stephen",
     "Suvi",
     "Takumi",
     "Tatyana",
     "Thiago",
     "Tomoko",
     "Vicki",
@@ -235,14 +238,15 @@
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
@@ -321,14 +325,15 @@
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
@@ -339,14 +344,15 @@
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
@@ -382,14 +388,15 @@
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
@@ -408,16 +415,19 @@
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
@@ -501,15 +511,17 @@
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
@@ -533,14 +545,15 @@
 ]
 PaginatorName = Literal["describe_voices", "list_lexicons", "list_speech_synthesis_tasks"]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
+    "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/literals.pyi` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -48,14 +48,15 @@
     "cy-GB",
     "da-DK",
     "de-AT",
     "de-DE",
     "en-AU",
     "en-GB",
     "en-GB-WLS",
+    "en-IE",
     "en-IN",
     "en-NZ",
     "en-US",
     "en-ZA",
     "es-ES",
     "es-MX",
     "es-US",
@@ -145,28 +146,30 @@
     "Mathieu",
     "Matthew",
     "Maxim",
     "Mia",
     "Miguel",
     "Mizuki",
     "Naja",
+    "Niamh",
     "Nicole",
     "Ola",
     "Olivia",
     "Pedro",
     "Penelope",
     "Raveena",
     "Remi",
     "Ricardo",
     "Ruben",
     "Russell",
     "Ruth",
     "Salli",
     "Seoyeon",
     "Sergio",
+    "Sofie",
     "Stephen",
     "Suvi",
     "Takumi",
     "Tatyana",
     "Thiago",
     "Tomoko",
     "Vicki",
@@ -233,14 +236,15 @@
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
@@ -319,14 +323,15 @@
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
@@ -337,14 +342,15 @@
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
@@ -380,14 +386,15 @@
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
@@ -406,16 +413,19 @@
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
@@ -499,15 +509,17 @@
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
@@ -531,14 +543,15 @@
 ]
 PaginatorName = Literal["describe_voices", "list_lexicons", "list_speech_synthesis_tasks"]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
+    "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/paginator.py` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -20,34 +20,27 @@
         client: PollyClient
 
         describe_voices_paginator: DescribeVoicesPaginator = client.get_paginator("describe_voices")
         list_lexicons_paginator: ListLexiconsPaginator = client.get_paginator("list_lexicons")
         list_speech_synthesis_tasks_paginator: ListSpeechSynthesisTasksPaginator = client.get_paginator("list_speech_synthesis_tasks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EngineType, LanguageCodeType, TaskStatusType
 from .type_defs import (
     DescribeVoicesOutputTypeDef,
     ListLexiconsOutputTypeDef,
     ListSpeechSynthesisTasksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeVoicesPaginator", "ListLexiconsPaginator", "ListSpeechSynthesisTasksPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -65,43 +58,43 @@
 
     def paginate(
         self,
         *,
         Engine: EngineType = ...,
         LanguageCode: LanguageCodeType = ...,
         IncludeAdditionalLanguageCodes: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeVoicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.DescribeVoices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#describevoicespaginator)
         """
 
 
 class ListLexiconsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListLexicons)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listlexiconspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLexiconsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListLexicons.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listlexiconspaginator)
         """
 
 
 class ListSpeechSynthesisTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListSpeechSynthesisTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listspeechsynthesistaskspaginator)
     """
 
     def paginate(
-        self, *, Status: TaskStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Status: TaskStatusType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpeechSynthesisTasksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListSpeechSynthesisTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listspeechsynthesistaskspaginator)
         """
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/paginator.pyi` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -20,33 +20,27 @@
         client: PollyClient
 
         describe_voices_paginator: DescribeVoicesPaginator = client.get_paginator("describe_voices")
         list_lexicons_paginator: ListLexiconsPaginator = client.get_paginator("list_lexicons")
         list_speech_synthesis_tasks_paginator: ListSpeechSynthesisTasksPaginator = client.get_paginator("list_speech_synthesis_tasks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EngineType, LanguageCodeType, TaskStatusType
 from .type_defs import (
     DescribeVoicesOutputTypeDef,
     ListLexiconsOutputTypeDef,
     ListSpeechSynthesisTasksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeVoicesPaginator", "ListLexiconsPaginator", "ListSpeechSynthesisTasksPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -61,41 +55,41 @@
 
     def paginate(
         self,
         *,
         Engine: EngineType = ...,
         LanguageCode: LanguageCodeType = ...,
         IncludeAdditionalLanguageCodes: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeVoicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.DescribeVoices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#describevoicespaginator)
         """
 
 class ListLexiconsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListLexicons)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listlexiconspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLexiconsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListLexicons.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listlexiconspaginator)
         """
 
 class ListSpeechSynthesisTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListSpeechSynthesisTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listspeechsynthesistaskspaginator)
     """
 
     def paginate(
-        self, *, Status: TaskStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Status: TaskStatusType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpeechSynthesisTasksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly.Paginator.ListSpeechSynthesisTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/paginators/#listspeechsynthesistaskspaginator)
         """
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/type_defs.py` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -32,31 +32,31 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DeleteLexiconInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
     "DescribeVoicesInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "VoiceTypeDef",
     "GetLexiconInputRequestTypeDef",
     "LexiconAttributesTypeDef",
     "LexiconTypeDef",
     "GetSpeechSynthesisTaskInputRequestTypeDef",
     "SynthesisTaskTypeDef",
+    "ListLexiconsInputListLexiconsPaginateTypeDef",
     "ListLexiconsInputRequestTypeDef",
+    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
     "ListSpeechSynthesisTasksInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutLexiconInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartSpeechSynthesisTaskInputRequestTypeDef",
     "SynthesizeSpeechInputRequestTypeDef",
-    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
-    "ListLexiconsInputListLexiconsPaginateTypeDef",
-    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
     "SynthesizeSpeechOutputTypeDef",
     "DescribeVoicesOutputTypeDef",
     "LexiconDescriptionTypeDef",
     "GetLexiconOutputTypeDef",
     "GetSpeechSynthesisTaskOutputTypeDef",
     "ListSpeechSynthesisTasksOutputTypeDef",
     "StartSpeechSynthesisTaskOutputTypeDef",
@@ -66,20 +66,21 @@
 DeleteLexiconInputRequestTypeDef = TypedDict(
     "DeleteLexiconInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeVoicesInputDescribeVoicesPaginateTypeDef = TypedDict(
+    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Engine": EngineType,
+        "LanguageCode": LanguageCodeType,
+        "IncludeAdditionalLanguageCodes": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeVoicesInputRequestTypeDef = TypedDict(
     "DescribeVoicesInputRequestTypeDef",
     {
@@ -87,25 +88,14 @@
         "LanguageCode": LanguageCodeType,
         "IncludeAdditionalLanguageCodes": bool,
         "NextToken": str,
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
 VoiceTypeDef = TypedDict(
     "VoiceTypeDef",
     {
         "Gender": GenderType,
         "Id": VoiceIdType,
         "LanguageCode": LanguageCodeType,
         "LanguageName": str,
@@ -170,40 +160,78 @@
         "TextType": TextTypeType,
         "VoiceId": VoiceIdType,
         "LanguageCode": LanguageCodeType,
     },
     total=False,
 )
 
+ListLexiconsInputListLexiconsPaginateTypeDef = TypedDict(
+    "ListLexiconsInputListLexiconsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLexiconsInputRequestTypeDef = TypedDict(
     "ListLexiconsInputRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef = TypedDict(
+    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
+    {
+        "Status": TaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSpeechSynthesisTasksInputRequestTypeDef = TypedDict(
     "ListSpeechSynthesisTasksInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Status": TaskStatusType,
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
 PutLexiconInputRequestTypeDef = TypedDict(
     "PutLexiconInputRequestTypeDef",
     {
         "Name": str,
         "Content": str,
     },
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
 _RequiredStartSpeechSynthesisTaskInputRequestTypeDef = TypedDict(
     "_RequiredStartSpeechSynthesisTaskInputRequestTypeDef",
     {
         "OutputFormat": OutputFormatType,
         "OutputS3BucketName": str,
         "Text": str,
         "VoiceId": VoiceIdType,
@@ -256,58 +284,30 @@
 
 class SynthesizeSpeechInputRequestTypeDef(
     _RequiredSynthesizeSpeechInputRequestTypeDef, _OptionalSynthesizeSpeechInputRequestTypeDef
 ):
     pass
 
 
-DescribeVoicesInputDescribeVoicesPaginateTypeDef = TypedDict(
-    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
-    {
-        "Engine": EngineType,
-        "LanguageCode": LanguageCodeType,
-        "IncludeAdditionalLanguageCodes": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListLexiconsInputListLexiconsPaginateTypeDef = TypedDict(
-    "ListLexiconsInputListLexiconsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef = TypedDict(
-    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
-    {
-        "Status": TaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 SynthesizeSpeechOutputTypeDef = TypedDict(
     "SynthesizeSpeechOutputTypeDef",
     {
         "AudioStream": StreamingBody,
         "ContentType": str,
         "RequestCharacters": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVoicesOutputTypeDef = TypedDict(
     "DescribeVoicesOutputTypeDef",
     {
         "Voices": List[VoiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LexiconDescriptionTypeDef = TypedDict(
     "LexiconDescriptionTypeDef",
     {
         "Name": str,
@@ -317,44 +317,44 @@
 )
 
 GetLexiconOutputTypeDef = TypedDict(
     "GetLexiconOutputTypeDef",
     {
         "Lexicon": LexiconTypeDef,
         "LexiconAttributes": LexiconAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSpeechSynthesisTaskOutputTypeDef = TypedDict(
     "GetSpeechSynthesisTaskOutputTypeDef",
     {
         "SynthesisTask": SynthesisTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSpeechSynthesisTasksOutputTypeDef = TypedDict(
     "ListSpeechSynthesisTasksOutputTypeDef",
     {
         "NextToken": str,
         "SynthesisTasks": List[SynthesisTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSpeechSynthesisTaskOutputTypeDef = TypedDict(
     "StartSpeechSynthesisTaskOutputTypeDef",
     {
         "SynthesisTask": SynthesisTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLexiconsOutputTypeDef = TypedDict(
     "ListLexiconsOutputTypeDef",
     {
         "Lexicons": List[LexiconDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly/type_defs.pyi` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -31,31 +31,31 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DeleteLexiconInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
     "DescribeVoicesInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "VoiceTypeDef",
     "GetLexiconInputRequestTypeDef",
     "LexiconAttributesTypeDef",
     "LexiconTypeDef",
     "GetSpeechSynthesisTaskInputRequestTypeDef",
     "SynthesisTaskTypeDef",
+    "ListLexiconsInputListLexiconsPaginateTypeDef",
     "ListLexiconsInputRequestTypeDef",
+    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
     "ListSpeechSynthesisTasksInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutLexiconInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartSpeechSynthesisTaskInputRequestTypeDef",
     "SynthesizeSpeechInputRequestTypeDef",
-    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
-    "ListLexiconsInputListLexiconsPaginateTypeDef",
-    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
     "SynthesizeSpeechOutputTypeDef",
     "DescribeVoicesOutputTypeDef",
     "LexiconDescriptionTypeDef",
     "GetLexiconOutputTypeDef",
     "GetSpeechSynthesisTaskOutputTypeDef",
     "ListSpeechSynthesisTasksOutputTypeDef",
     "StartSpeechSynthesisTaskOutputTypeDef",
@@ -65,20 +65,21 @@
 DeleteLexiconInputRequestTypeDef = TypedDict(
     "DeleteLexiconInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeVoicesInputDescribeVoicesPaginateTypeDef = TypedDict(
+    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Engine": EngineType,
+        "LanguageCode": LanguageCodeType,
+        "IncludeAdditionalLanguageCodes": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeVoicesInputRequestTypeDef = TypedDict(
     "DescribeVoicesInputRequestTypeDef",
     {
@@ -86,25 +87,14 @@
         "LanguageCode": LanguageCodeType,
         "IncludeAdditionalLanguageCodes": bool,
         "NextToken": str,
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
 VoiceTypeDef = TypedDict(
     "VoiceTypeDef",
     {
         "Gender": GenderType,
         "Id": VoiceIdType,
         "LanguageCode": LanguageCodeType,
         "LanguageName": str,
@@ -169,40 +159,78 @@
         "TextType": TextTypeType,
         "VoiceId": VoiceIdType,
         "LanguageCode": LanguageCodeType,
     },
     total=False,
 )
 
+ListLexiconsInputListLexiconsPaginateTypeDef = TypedDict(
+    "ListLexiconsInputListLexiconsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLexiconsInputRequestTypeDef = TypedDict(
     "ListLexiconsInputRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef = TypedDict(
+    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
+    {
+        "Status": TaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSpeechSynthesisTasksInputRequestTypeDef = TypedDict(
     "ListSpeechSynthesisTasksInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Status": TaskStatusType,
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
 PutLexiconInputRequestTypeDef = TypedDict(
     "PutLexiconInputRequestTypeDef",
     {
         "Name": str,
         "Content": str,
     },
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
 _RequiredStartSpeechSynthesisTaskInputRequestTypeDef = TypedDict(
     "_RequiredStartSpeechSynthesisTaskInputRequestTypeDef",
     {
         "OutputFormat": OutputFormatType,
         "OutputS3BucketName": str,
         "Text": str,
         "VoiceId": VoiceIdType,
@@ -251,58 +279,30 @@
 )
 
 class SynthesizeSpeechInputRequestTypeDef(
     _RequiredSynthesizeSpeechInputRequestTypeDef, _OptionalSynthesizeSpeechInputRequestTypeDef
 ):
     pass
 
-DescribeVoicesInputDescribeVoicesPaginateTypeDef = TypedDict(
-    "DescribeVoicesInputDescribeVoicesPaginateTypeDef",
-    {
-        "Engine": EngineType,
-        "LanguageCode": LanguageCodeType,
-        "IncludeAdditionalLanguageCodes": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListLexiconsInputListLexiconsPaginateTypeDef = TypedDict(
-    "ListLexiconsInputListLexiconsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef = TypedDict(
-    "ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef",
-    {
-        "Status": TaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 SynthesizeSpeechOutputTypeDef = TypedDict(
     "SynthesizeSpeechOutputTypeDef",
     {
         "AudioStream": StreamingBody,
         "ContentType": str,
         "RequestCharacters": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVoicesOutputTypeDef = TypedDict(
     "DescribeVoicesOutputTypeDef",
     {
         "Voices": List[VoiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LexiconDescriptionTypeDef = TypedDict(
     "LexiconDescriptionTypeDef",
     {
         "Name": str,
@@ -312,44 +312,44 @@
 )
 
 GetLexiconOutputTypeDef = TypedDict(
     "GetLexiconOutputTypeDef",
     {
         "Lexicon": LexiconTypeDef,
         "LexiconAttributes": LexiconAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSpeechSynthesisTaskOutputTypeDef = TypedDict(
     "GetSpeechSynthesisTaskOutputTypeDef",
     {
         "SynthesisTask": SynthesisTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSpeechSynthesisTasksOutputTypeDef = TypedDict(
     "ListSpeechSynthesisTasksOutputTypeDef",
     {
         "NextToken": str,
         "SynthesisTasks": List[SynthesisTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSpeechSynthesisTaskOutputTypeDef = TypedDict(
     "StartSpeechSynthesisTaskOutputTypeDef",
     {
         "SynthesisTask": SynthesisTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLexiconsOutputTypeDef = TypedDict(
     "ListLexiconsOutputTypeDef",
     {
         "Lexicons": List[LexiconDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/PKG-INFO` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-polly
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Polly 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Polly 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-polly"></a>
 
 # types-aiobotocore-polly
 
 [![PyPI - types-aiobotocore-polly](https://img.shields.io/pypi/v/types-aiobotocore-polly.svg?color=blue)](https://pypi.org/project/types-aiobotocore-polly)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-polly.svg?color=blue)](https://pypi.org/project/types-aiobotocore-polly)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-polly?color=blue)](https://pypistats.org/packages/types-aiobotocore-polly)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Polly 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly)
+[aiobotocore.Polly 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/polly.html#Polly)
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
 [types-aiobotocore-polly docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_polly/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,31 +331,31 @@
 
 `types_aiobotocore_polly.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_polly.type_defs import (
     DeleteLexiconInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeVoicesInputDescribeVoicesPaginateTypeDef,
     DescribeVoicesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     VoiceTypeDef,
     GetLexiconInputRequestTypeDef,
     LexiconAttributesTypeDef,
     LexiconTypeDef,
     GetSpeechSynthesisTaskInputRequestTypeDef,
     SynthesisTaskTypeDef,
+    ListLexiconsInputListLexiconsPaginateTypeDef,
     ListLexiconsInputRequestTypeDef,
+    ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef,
     ListSpeechSynthesisTasksInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutLexiconInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartSpeechSynthesisTaskInputRequestTypeDef,
     SynthesizeSpeechInputRequestTypeDef,
-    DescribeVoicesInputDescribeVoicesPaginateTypeDef,
-    ListLexiconsInputListLexiconsPaginateTypeDef,
-    ListSpeechSynthesisTasksInputListSpeechSynthesisTasksPaginateTypeDef,
     SynthesizeSpeechOutputTypeDef,
     DescribeVoicesOutputTypeDef,
     LexiconDescriptionTypeDef,
     GetLexiconOutputTypeDef,
     GetSpeechSynthesisTaskOutputTypeDef,
     ListSpeechSynthesisTasksOutputTypeDef,
     StartSpeechSynthesisTaskOutputTypeDef,
@@ -370,43 +370,43 @@
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

### Comparing `types-aiobotocore-polly-2.5.0.post1/types_aiobotocore_polly.egg-info/SOURCES.txt` & `types-aiobotocore-polly-2.5.1/types_aiobotocore_polly.egg-info/SOURCES.txt`

 * *Files identical despite different names*

