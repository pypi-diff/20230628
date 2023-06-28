# Comparing `tmp/types-aiobotocore-lexv2-runtime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lexv2-runtime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lexv2-runtime-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:53 2023, max compression
+gzip compressed data, was "types-aiobotocore-lexv2-runtime-2.5.1.tar", last modified: Wed Jun 28 01:43:45 2023, max compression
```

## Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1.tar` & `types-aiobotocore-lexv2-runtime-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.831368 types-aiobotocore-lexv2-runtime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13366 2023-03-11 12:26:53.831368 types-aiobotocore-lexv2-runtime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11772 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:53.831368 types-aiobotocore-lexv2-runtime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2165 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.819368 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/
--rw-r--r--   0 runner    (1001) docker     (123)      485 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      484 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8073 2023-03-11 12:17:31.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8060 2023-03-11 12:17:31.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8368 2023-03-11 12:17:31.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8366 2023-03-11 12:17:31.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    11334 2023-03-11 12:17:31.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    11313 2023-03-11 12:17:31.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.831368 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13366 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-runtime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13364 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-runtime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11776 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-runtime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/
+-rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      484 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8073 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8060 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8577 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8575 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    11344 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11323 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:12.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13364 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/LICENSE` & `types-aiobotocore-lexv2-runtime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lexv2-runtime-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lexv2-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LexRuntimeV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexRuntimeV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lexv2-runtime"></a>
 
 # types-aiobotocore-lexv2-runtime
 
 [![PyPI - types-aiobotocore-lexv2-runtime](https://img.shields.io/pypi/v/types-aiobotocore-lexv2-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lexv2-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lexv2-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-lexv2-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexRuntimeV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
+[aiobotocore.LexRuntimeV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
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
 [types-aiobotocore-lexv2-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -300,30 +300,30 @@
 
 ```python
 from types_aiobotocore_lexv2_runtime.type_defs import (
     ActiveContextTimeToLiveTypeDef,
     ButtonTypeDef,
     ConfidenceScoreTypeDef,
     DeleteSessionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteSessionResponseTypeDef,
     DialogActionTypeDef,
     ElicitSubSlotTypeDef,
     GetSessionRequestRequestTypeDef,
     IntentTypeDef,
+    PutSessionResponseTypeDef,
     RecognizedBotMemberTypeDef,
     RecognizeUtteranceRequestRequestTypeDef,
+    RecognizeUtteranceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RuntimeHintValueTypeDef,
     RuntimeHintsTypeDef,
     SentimentScoreTypeDef,
     ValueTypeDef,
     ActiveContextTypeDef,
     ImageResponseCardTypeDef,
-    DeleteSessionResponseTypeDef,
-    PutSessionResponseTypeDef,
-    RecognizeUtteranceResponseTypeDef,
     RuntimeHintDetailsTypeDef,
     SentimentResponseTypeDef,
     SlotTypeDef,
     SessionStateTypeDef,
     MessageTypeDef,
     InterpretationTypeDef,
     RecognizeTextRequestRequestTypeDef,
@@ -340,43 +340,43 @@
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/README.md` & `types-aiobotocore-lexv2-runtime-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lexv2-runtime"></a>
 
 # types-aiobotocore-lexv2-runtime
 
 [![PyPI - types-aiobotocore-lexv2-runtime](https://img.shields.io/pypi/v/types-aiobotocore-lexv2-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lexv2-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lexv2-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-lexv2-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexRuntimeV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
+[aiobotocore.LexRuntimeV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
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
 [types-aiobotocore-lexv2-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -267,30 +267,30 @@
 
 ```python
 from types_aiobotocore_lexv2_runtime.type_defs import (
     ActiveContextTimeToLiveTypeDef,
     ButtonTypeDef,
     ConfidenceScoreTypeDef,
     DeleteSessionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteSessionResponseTypeDef,
     DialogActionTypeDef,
     ElicitSubSlotTypeDef,
     GetSessionRequestRequestTypeDef,
     IntentTypeDef,
+    PutSessionResponseTypeDef,
     RecognizedBotMemberTypeDef,
     RecognizeUtteranceRequestRequestTypeDef,
+    RecognizeUtteranceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RuntimeHintValueTypeDef,
     RuntimeHintsTypeDef,
     SentimentScoreTypeDef,
     ValueTypeDef,
     ActiveContextTypeDef,
     ImageResponseCardTypeDef,
-    DeleteSessionResponseTypeDef,
-    PutSessionResponseTypeDef,
-    RecognizeUtteranceResponseTypeDef,
     RuntimeHintDetailsTypeDef,
     SentimentResponseTypeDef,
     SlotTypeDef,
     SessionStateTypeDef,
     MessageTypeDef,
     InterpretationTypeDef,
     RecognizeTextRequestRequestTypeDef,
@@ -307,43 +307,43 @@
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/setup.py` & `types-aiobotocore-lexv2-runtime-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lexv2-runtime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lexv2-runtime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lexv2_runtime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LexRuntimeV2 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LexRuntimeV2 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/"
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/__main__.py` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/__main__.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LexRuntimeV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LexRuntimeV2 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2\nOther"
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/client.py` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/client.pyi` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/literals.py` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/literals.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -14,30 +14,28 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ConfirmationStateType",
     "DialogActionTypeType",
     "IntentStateType",
     "MessageContentTypeType",
     "SentimentTypeType",
     "ShapeType",
     "StyleTypeType",
     "LexRuntimeV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 ConfirmationStateType = Literal["Confirmed", "Denied", "None"]
 DialogActionTypeType = Literal[
     "Close", "ConfirmIntent", "Delegate", "ElicitIntent", "ElicitSlot", "None"
 ]
 IntentStateType = Literal[
     "Failed", "Fulfilled", "FulfillmentInProgress", "InProgress", "ReadyForFulfillment", "Waiting"
 ]
@@ -104,14 +102,15 @@
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
@@ -190,14 +189,15 @@
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
@@ -208,14 +208,15 @@
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
@@ -251,14 +252,15 @@
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
@@ -277,16 +279,19 @@
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
@@ -370,15 +375,17 @@
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/literals.pyi` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,28 +14,30 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ConfirmationStateType",
     "DialogActionTypeType",
     "IntentStateType",
     "MessageContentTypeType",
     "SentimentTypeType",
     "ShapeType",
     "StyleTypeType",
     "LexRuntimeV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 ConfirmationStateType = Literal["Confirmed", "Denied", "None"]
 DialogActionTypeType = Literal[
     "Close", "ConfirmIntent", "Delegate", "ElicitIntent", "ElicitSlot", "None"
 ]
 IntentStateType = Literal[
     "Failed", "Fulfilled", "FulfillmentInProgress", "InProgress", "ReadyForFulfillment", "Waiting"
 ]
@@ -102,14 +104,15 @@
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
@@ -188,14 +191,15 @@
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
@@ -206,14 +210,15 @@
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
@@ -249,14 +254,15 @@
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
@@ -275,16 +281,19 @@
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
@@ -368,15 +377,17 @@
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/type_defs.py` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -33,30 +33,30 @@
 
 
 __all__ = (
     "ActiveContextTimeToLiveTypeDef",
     "ButtonTypeDef",
     "ConfidenceScoreTypeDef",
     "DeleteSessionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteSessionResponseTypeDef",
     "DialogActionTypeDef",
     "ElicitSubSlotTypeDef",
     "GetSessionRequestRequestTypeDef",
     "IntentTypeDef",
+    "PutSessionResponseTypeDef",
     "RecognizedBotMemberTypeDef",
     "RecognizeUtteranceRequestRequestTypeDef",
+    "RecognizeUtteranceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RuntimeHintValueTypeDef",
     "RuntimeHintsTypeDef",
     "SentimentScoreTypeDef",
     "ValueTypeDef",
     "ActiveContextTypeDef",
     "ImageResponseCardTypeDef",
-    "DeleteSessionResponseTypeDef",
-    "PutSessionResponseTypeDef",
-    "RecognizeUtteranceResponseTypeDef",
     "RuntimeHintDetailsTypeDef",
     "SentimentResponseTypeDef",
     "SlotTypeDef",
     "SessionStateTypeDef",
     "MessageTypeDef",
     "InterpretationTypeDef",
     "RecognizeTextRequestRequestTypeDef",
@@ -95,22 +95,22 @@
         "botId": str,
         "botAliasId": str,
         "localeId": str,
         "sessionId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteSessionResponseTypeDef = TypedDict(
+    "DeleteSessionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+        "sessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDialogActionTypeDef = TypedDict(
     "_RequiredDialogActionTypeDef",
     {
         "type": DialogActionTypeType,
@@ -177,14 +177,27 @@
 )
 
 
 class IntentTypeDef(_RequiredIntentTypeDef, _OptionalIntentTypeDef):
     pass
 
 
+PutSessionResponseTypeDef = TypedDict(
+    "PutSessionResponseTypeDef",
+    {
+        "contentType": str,
+        "messages": str,
+        "sessionState": str,
+        "requestAttributes": str,
+        "sessionId": str,
+        "audioStream": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRecognizedBotMemberTypeDef = TypedDict(
     "_RequiredRecognizedBotMemberTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalRecognizedBotMemberTypeDef = TypedDict(
@@ -227,14 +240,42 @@
 class RecognizeUtteranceRequestRequestTypeDef(
     _RequiredRecognizeUtteranceRequestRequestTypeDef,
     _OptionalRecognizeUtteranceRequestRequestTypeDef,
 ):
     pass
 
 
+RecognizeUtteranceResponseTypeDef = TypedDict(
+    "RecognizeUtteranceResponseTypeDef",
+    {
+        "inputMode": str,
+        "contentType": str,
+        "messages": str,
+        "interpretations": str,
+        "sessionState": str,
+        "requestAttributes": str,
+        "sessionId": str,
+        "inputTranscript": str,
+        "audioStream": StreamingBody,
+        "recognizedBotMember": str,
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
 RuntimeHintValueTypeDef = TypedDict(
     "RuntimeHintValueTypeDef",
     {
         "phrase": str,
     },
 )
 
@@ -305,55 +346,14 @@
 
 class ImageResponseCardTypeDef(
     _RequiredImageResponseCardTypeDef, _OptionalImageResponseCardTypeDef
 ):
     pass
 
 
-DeleteSessionResponseTypeDef = TypedDict(
-    "DeleteSessionResponseTypeDef",
-    {
-        "botId": str,
-        "botAliasId": str,
-        "localeId": str,
-        "sessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSessionResponseTypeDef = TypedDict(
-    "PutSessionResponseTypeDef",
-    {
-        "contentType": str,
-        "messages": str,
-        "sessionState": str,
-        "requestAttributes": str,
-        "sessionId": str,
-        "audioStream": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RecognizeUtteranceResponseTypeDef = TypedDict(
-    "RecognizeUtteranceResponseTypeDef",
-    {
-        "inputMode": str,
-        "contentType": str,
-        "messages": str,
-        "interpretations": str,
-        "sessionState": str,
-        "requestAttributes": str,
-        "sessionId": str,
-        "inputTranscript": str,
-        "audioStream": StreamingBody,
-        "recognizedBotMember": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 RuntimeHintDetailsTypeDef = TypedDict(
     "RuntimeHintDetailsTypeDef",
     {
         "runtimeHintValues": List[RuntimeHintValueTypeDef],
         "subSlotHints": Dict[str, Dict[str, Any]],
     },
     total=False,
@@ -478,23 +478,23 @@
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
         "sessionId": str,
         "messages": List[MessageTypeDef],
         "interpretations": List[InterpretationTypeDef],
         "sessionState": SessionStateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecognizeTextResponseTypeDef = TypedDict(
     "RecognizeTextResponseTypeDef",
     {
         "messages": List[MessageTypeDef],
         "sessionState": SessionStateTypeDef,
         "interpretations": List[InterpretationTypeDef],
         "requestAttributes": Dict[str, str],
         "sessionId": str,
         "recognizedBotMember": RecognizedBotMemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime/type_defs.pyi` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -32,30 +32,30 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "ActiveContextTimeToLiveTypeDef",
     "ButtonTypeDef",
     "ConfidenceScoreTypeDef",
     "DeleteSessionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteSessionResponseTypeDef",
     "DialogActionTypeDef",
     "ElicitSubSlotTypeDef",
     "GetSessionRequestRequestTypeDef",
     "IntentTypeDef",
+    "PutSessionResponseTypeDef",
     "RecognizedBotMemberTypeDef",
     "RecognizeUtteranceRequestRequestTypeDef",
+    "RecognizeUtteranceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RuntimeHintValueTypeDef",
     "RuntimeHintsTypeDef",
     "SentimentScoreTypeDef",
     "ValueTypeDef",
     "ActiveContextTypeDef",
     "ImageResponseCardTypeDef",
-    "DeleteSessionResponseTypeDef",
-    "PutSessionResponseTypeDef",
-    "RecognizeUtteranceResponseTypeDef",
     "RuntimeHintDetailsTypeDef",
     "SentimentResponseTypeDef",
     "SlotTypeDef",
     "SessionStateTypeDef",
     "MessageTypeDef",
     "InterpretationTypeDef",
     "RecognizeTextRequestRequestTypeDef",
@@ -94,22 +94,22 @@
         "botId": str,
         "botAliasId": str,
         "localeId": str,
         "sessionId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteSessionResponseTypeDef = TypedDict(
+    "DeleteSessionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+        "sessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDialogActionTypeDef = TypedDict(
     "_RequiredDialogActionTypeDef",
     {
         "type": DialogActionTypeType,
@@ -170,14 +170,27 @@
     },
     total=False,
 )
 
 class IntentTypeDef(_RequiredIntentTypeDef, _OptionalIntentTypeDef):
     pass
 
+PutSessionResponseTypeDef = TypedDict(
+    "PutSessionResponseTypeDef",
+    {
+        "contentType": str,
+        "messages": str,
+        "sessionState": str,
+        "requestAttributes": str,
+        "sessionId": str,
+        "audioStream": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRecognizedBotMemberTypeDef = TypedDict(
     "_RequiredRecognizedBotMemberTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalRecognizedBotMemberTypeDef = TypedDict(
@@ -216,14 +229,42 @@
 
 class RecognizeUtteranceRequestRequestTypeDef(
     _RequiredRecognizeUtteranceRequestRequestTypeDef,
     _OptionalRecognizeUtteranceRequestRequestTypeDef,
 ):
     pass
 
+RecognizeUtteranceResponseTypeDef = TypedDict(
+    "RecognizeUtteranceResponseTypeDef",
+    {
+        "inputMode": str,
+        "contentType": str,
+        "messages": str,
+        "interpretations": str,
+        "sessionState": str,
+        "requestAttributes": str,
+        "sessionId": str,
+        "inputTranscript": str,
+        "audioStream": StreamingBody,
+        "recognizedBotMember": str,
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
 RuntimeHintValueTypeDef = TypedDict(
     "RuntimeHintValueTypeDef",
     {
         "phrase": str,
     },
 )
 
@@ -290,55 +331,14 @@
 )
 
 class ImageResponseCardTypeDef(
     _RequiredImageResponseCardTypeDef, _OptionalImageResponseCardTypeDef
 ):
     pass
 
-DeleteSessionResponseTypeDef = TypedDict(
-    "DeleteSessionResponseTypeDef",
-    {
-        "botId": str,
-        "botAliasId": str,
-        "localeId": str,
-        "sessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSessionResponseTypeDef = TypedDict(
-    "PutSessionResponseTypeDef",
-    {
-        "contentType": str,
-        "messages": str,
-        "sessionState": str,
-        "requestAttributes": str,
-        "sessionId": str,
-        "audioStream": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RecognizeUtteranceResponseTypeDef = TypedDict(
-    "RecognizeUtteranceResponseTypeDef",
-    {
-        "inputMode": str,
-        "contentType": str,
-        "messages": str,
-        "interpretations": str,
-        "sessionState": str,
-        "requestAttributes": str,
-        "sessionId": str,
-        "inputTranscript": str,
-        "audioStream": StreamingBody,
-        "recognizedBotMember": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 RuntimeHintDetailsTypeDef = TypedDict(
     "RuntimeHintDetailsTypeDef",
     {
         "runtimeHintValues": List[RuntimeHintValueTypeDef],
         "subSlotHints": Dict[str, Dict[str, Any]],
     },
     total=False,
@@ -457,23 +457,23 @@
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
         "sessionId": str,
         "messages": List[MessageTypeDef],
         "interpretations": List[InterpretationTypeDef],
         "sessionState": SessionStateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecognizeTextResponseTypeDef = TypedDict(
     "RecognizeTextResponseTypeDef",
     {
         "messages": List[MessageTypeDef],
         "sessionState": SessionStateTypeDef,
         "interpretations": List[InterpretationTypeDef],
         "requestAttributes": Dict[str, str],
         "sessionId": str,
         "recognizedBotMember": RecognizedBotMemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/PKG-INFO` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lexv2-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LexRuntimeV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexRuntimeV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lexv2-runtime"></a>
 
 # types-aiobotocore-lexv2-runtime
 
 [![PyPI - types-aiobotocore-lexv2-runtime](https://img.shields.io/pypi/v/types-aiobotocore-lexv2-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lexv2-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lexv2-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-lexv2-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexRuntimeV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
+[aiobotocore.LexRuntimeV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
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
 [types-aiobotocore-lexv2-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -300,30 +300,30 @@
 
 ```python
 from types_aiobotocore_lexv2_runtime.type_defs import (
     ActiveContextTimeToLiveTypeDef,
     ButtonTypeDef,
     ConfidenceScoreTypeDef,
     DeleteSessionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteSessionResponseTypeDef,
     DialogActionTypeDef,
     ElicitSubSlotTypeDef,
     GetSessionRequestRequestTypeDef,
     IntentTypeDef,
+    PutSessionResponseTypeDef,
     RecognizedBotMemberTypeDef,
     RecognizeUtteranceRequestRequestTypeDef,
+    RecognizeUtteranceResponseTypeDef,
+    ResponseMetadataTypeDef,
     RuntimeHintValueTypeDef,
     RuntimeHintsTypeDef,
     SentimentScoreTypeDef,
     ValueTypeDef,
     ActiveContextTypeDef,
     ImageResponseCardTypeDef,
-    DeleteSessionResponseTypeDef,
-    PutSessionResponseTypeDef,
-    RecognizeUtteranceResponseTypeDef,
     RuntimeHintDetailsTypeDef,
     SentimentResponseTypeDef,
     SlotTypeDef,
     SessionStateTypeDef,
     MessageTypeDef,
     InterpretationTypeDef,
     RecognizeTextRequestRequestTypeDef,
@@ -340,43 +340,43 @@
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

### Comparing `types-aiobotocore-lexv2-runtime-2.5.0.post1/types_aiobotocore_lexv2_runtime.egg-info/SOURCES.txt` & `types-aiobotocore-lexv2-runtime-2.5.1/types_aiobotocore_lexv2_runtime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

