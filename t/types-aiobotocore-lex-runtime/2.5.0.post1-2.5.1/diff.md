# Comparing `tmp/types-aiobotocore-lex-runtime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lex-runtime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lex-runtime-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:53 2023, max compression
+gzip compressed data, was "types-aiobotocore-lex-runtime-2.5.1.tar", last modified: Wed Jun 28 01:43:45 2023, max compression
```

## Comparing `types-aiobotocore-lex-runtime-2.5.0.post1.tar` & `types-aiobotocore-lex-runtime-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.823368 types-aiobotocore-lex-runtime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13075 2023-03-11 12:26:53.823368 types-aiobotocore-lex-runtime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11482 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:53.823368 types-aiobotocore-lex-runtime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2158 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.819368 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/
--rw-r--r--   0 runner    (1001) docker     (123)      504 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      503 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8336 2023-03-11 12:17:17.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8323 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8230 2023-03-11 12:17:17.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8228 2023-03-11 12:17:17.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9686 2023-03-11 12:17:19.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9673 2023-03-11 12:17:17.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:16.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.823368 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13075 2023-03-11 12:26:53.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:53.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:53.000000 types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.002166 types-aiobotocore-lex-runtime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13071 2023-06-28 01:43:45.002166 types-aiobotocore-lex-runtime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11484 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:45.002166 types-aiobotocore-lex-runtime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.998166 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/
+-rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8336 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8323 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8439 2023-06-28 01:33:58.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8437 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9696 2023-06-28 01:33:59.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9683 2023-06-28 01:33:58.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:57.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.002166 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13071 2023-06-28 01:43:44.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:44.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:44.000000 types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/LICENSE` & `types-aiobotocore-lex-runtime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lex-runtime-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lex-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LexRuntimeService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexRuntimeService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lex-runtime"></a>
 
 # types-aiobotocore-lex-runtime
 
 [![PyPI - types-aiobotocore-lex-runtime](https://img.shields.io/pypi/v/types-aiobotocore-lex-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lex-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lex-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-lex-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexRuntimeService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
+[aiobotocore.LexRuntimeService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
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
 [types-aiobotocore-lex-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,26 +298,26 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lex_runtime.type_defs import (
     ActiveContextTimeToLiveTypeDef,
     ButtonTypeDef,
     DeleteSessionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteSessionResponseTypeDef,
     DialogActionTypeDef,
     GetSessionRequestRequestTypeDef,
     IntentSummaryTypeDef,
     IntentConfidenceTypeDef,
     PostContentRequestRequestTypeDef,
+    PostContentResponseTypeDef,
     SentimentResponseTypeDef,
+    PutSessionResponseTypeDef,
+    ResponseMetadataTypeDef,
     ActiveContextTypeDef,
     GenericAttachmentTypeDef,
-    DeleteSessionResponseTypeDef,
-    PostContentResponseTypeDef,
-    PutSessionResponseTypeDef,
     PredictedIntentTypeDef,
     GetSessionResponseTypeDef,
     PostTextRequestRequestTypeDef,
     PutSessionRequestRequestTypeDef,
     ResponseCardTypeDef,
     PostTextResponseTypeDef,
 )
@@ -330,43 +330,43 @@
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/README.md` & `types-aiobotocore-lex-runtime-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lex-runtime"></a>
 
 # types-aiobotocore-lex-runtime
 
 [![PyPI - types-aiobotocore-lex-runtime](https://img.shields.io/pypi/v/types-aiobotocore-lex-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lex-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lex-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-lex-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexRuntimeService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
+[aiobotocore.LexRuntimeService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
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
 [types-aiobotocore-lex-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -265,26 +265,26 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lex_runtime.type_defs import (
     ActiveContextTimeToLiveTypeDef,
     ButtonTypeDef,
     DeleteSessionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteSessionResponseTypeDef,
     DialogActionTypeDef,
     GetSessionRequestRequestTypeDef,
     IntentSummaryTypeDef,
     IntentConfidenceTypeDef,
     PostContentRequestRequestTypeDef,
+    PostContentResponseTypeDef,
     SentimentResponseTypeDef,
+    PutSessionResponseTypeDef,
+    ResponseMetadataTypeDef,
     ActiveContextTypeDef,
     GenericAttachmentTypeDef,
-    DeleteSessionResponseTypeDef,
-    PostContentResponseTypeDef,
-    PutSessionResponseTypeDef,
     PredictedIntentTypeDef,
     GetSessionResponseTypeDef,
     PostTextRequestRequestTypeDef,
     PutSessionRequestRequestTypeDef,
     ResponseCardTypeDef,
     PostTextResponseTypeDef,
 )
@@ -297,43 +297,43 @@
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/setup.py` & `types-aiobotocore-lex-runtime-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lex-runtime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lex-runtime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lex_runtime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LexRuntimeService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LexRuntimeService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/"
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/__main__.py` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LexRuntimeService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LexRuntimeService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService\nOther"
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/client.py` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/client.pyi` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/literals.py` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,29 +14,27 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ConfirmationStatusType",
     "ContentTypeType",
     "DialogActionTypeType",
     "DialogStateType",
     "FulfillmentStateType",
     "MessageFormatTypeType",
     "LexRuntimeServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 ConfirmationStatusType = Literal["Confirmed", "Denied", "None"]
 ContentTypeType = Literal["application/vnd.amazonaws.card.generic"]
 DialogActionTypeType = Literal["Close", "ConfirmIntent", "Delegate", "ElicitIntent", "ElicitSlot"]
 DialogStateType = Literal[
     "ConfirmIntent", "ElicitIntent", "ElicitSlot", "Failed", "Fulfilled", "ReadyForFulfillment"
 ]
 FulfillmentStateType = Literal["Failed", "Fulfilled", "ReadyForFulfillment"]
@@ -100,14 +98,15 @@
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
@@ -186,14 +185,15 @@
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
@@ -204,14 +204,15 @@
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
@@ -247,14 +248,15 @@
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
@@ -273,16 +275,19 @@
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
@@ -366,15 +371,17 @@
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/literals.pyi` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,27 +14,29 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ConfirmationStatusType",
     "ContentTypeType",
     "DialogActionTypeType",
     "DialogStateType",
     "FulfillmentStateType",
     "MessageFormatTypeType",
     "LexRuntimeServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 ConfirmationStatusType = Literal["Confirmed", "Denied", "None"]
 ContentTypeType = Literal["application/vnd.amazonaws.card.generic"]
 DialogActionTypeType = Literal["Close", "ConfirmIntent", "Delegate", "ElicitIntent", "ElicitSlot"]
 DialogStateType = Literal[
     "ConfirmIntent", "ElicitIntent", "ElicitSlot", "Failed", "Fulfilled", "ReadyForFulfillment"
 ]
 FulfillmentStateType = Literal["Failed", "Fulfilled", "ReadyForFulfillment"]
@@ -98,14 +100,15 @@
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
@@ -184,14 +187,15 @@
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
@@ -202,14 +206,15 @@
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
@@ -245,14 +250,15 @@
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
@@ -271,16 +277,19 @@
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
@@ -364,15 +373,17 @@
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/type_defs.py` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -34,26 +34,26 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ActiveContextTimeToLiveTypeDef",
     "ButtonTypeDef",
     "DeleteSessionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteSessionResponseTypeDef",
     "DialogActionTypeDef",
     "GetSessionRequestRequestTypeDef",
     "IntentSummaryTypeDef",
     "IntentConfidenceTypeDef",
     "PostContentRequestRequestTypeDef",
+    "PostContentResponseTypeDef",
     "SentimentResponseTypeDef",
+    "PutSessionResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "ActiveContextTypeDef",
     "GenericAttachmentTypeDef",
-    "DeleteSessionResponseTypeDef",
-    "PostContentResponseTypeDef",
-    "PutSessionResponseTypeDef",
     "PredictedIntentTypeDef",
     "GetSessionResponseTypeDef",
     "PostTextRequestRequestTypeDef",
     "PutSessionRequestRequestTypeDef",
     "ResponseCardTypeDef",
     "PostTextResponseTypeDef",
 )
@@ -80,22 +80,22 @@
     {
         "botName": str,
         "botAlias": str,
         "userId": str,
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
+        "botName": str,
+        "botAlias": str,
+        "userId": str,
+        "sessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDialogActionTypeDef = TypedDict(
     "_RequiredDialogActionTypeDef",
     {
         "type": DialogActionTypeType,
@@ -198,55 +198,14 @@
 
 class PostContentRequestRequestTypeDef(
     _RequiredPostContentRequestRequestTypeDef, _OptionalPostContentRequestRequestTypeDef
 ):
     pass
 
 
-SentimentResponseTypeDef = TypedDict(
-    "SentimentResponseTypeDef",
-    {
-        "sentimentLabel": str,
-        "sentimentScore": str,
-    },
-    total=False,
-)
-
-ActiveContextTypeDef = TypedDict(
-    "ActiveContextTypeDef",
-    {
-        "name": str,
-        "timeToLive": ActiveContextTimeToLiveTypeDef,
-        "parameters": Dict[str, str],
-    },
-)
-
-GenericAttachmentTypeDef = TypedDict(
-    "GenericAttachmentTypeDef",
-    {
-        "title": str,
-        "subTitle": str,
-        "attachmentLinkUrl": str,
-        "imageUrl": str,
-        "buttons": List[ButtonTypeDef],
-    },
-    total=False,
-)
-
-DeleteSessionResponseTypeDef = TypedDict(
-    "DeleteSessionResponseTypeDef",
-    {
-        "botName": str,
-        "botAlias": str,
-        "userId": str,
-        "sessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 PostContentResponseTypeDef = TypedDict(
     "PostContentResponseTypeDef",
     {
         "contentType": str,
         "intentName": str,
         "nluIntentConfidence": str,
         "alternativeIntents": str,
@@ -260,16 +219,25 @@
         "slotToElicit": str,
         "inputTranscript": str,
         "encodedInputTranscript": str,
         "audioStream": StreamingBody,
         "botVersion": str,
         "sessionId": str,
         "activeContexts": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SentimentResponseTypeDef = TypedDict(
+    "SentimentResponseTypeDef",
+    {
+        "sentimentLabel": str,
+        "sentimentScore": str,
     },
+    total=False,
 )
 
 PutSessionResponseTypeDef = TypedDict(
     "PutSessionResponseTypeDef",
     {
         "contentType": str,
         "intentName": str,
@@ -279,18 +247,50 @@
         "encodedMessage": str,
         "messageFormat": MessageFormatTypeType,
         "dialogState": DialogStateType,
         "slotToElicit": str,
         "audioStream": StreamingBody,
         "sessionId": str,
         "activeContexts": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
+ActiveContextTypeDef = TypedDict(
+    "ActiveContextTypeDef",
+    {
+        "name": str,
+        "timeToLive": ActiveContextTimeToLiveTypeDef,
+        "parameters": Dict[str, str],
+    },
+)
+
+GenericAttachmentTypeDef = TypedDict(
+    "GenericAttachmentTypeDef",
+    {
+        "title": str,
+        "subTitle": str,
+        "attachmentLinkUrl": str,
+        "imageUrl": str,
+        "buttons": List[ButtonTypeDef],
+    },
+    total=False,
+)
+
 PredictedIntentTypeDef = TypedDict(
     "PredictedIntentTypeDef",
     {
         "intentName": str,
         "nluIntentConfidence": IntentConfidenceTypeDef,
         "slots": Dict[str, str],
     },
@@ -301,15 +301,15 @@
     "GetSessionResponseTypeDef",
     {
         "recentIntentSummaryView": List[IntentSummaryTypeDef],
         "sessionAttributes": Dict[str, str],
         "sessionId": str,
         "dialogAction": DialogActionTypeDef,
         "activeContexts": List[ActiveContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPostTextRequestRequestTypeDef = TypedDict(
     "_RequiredPostTextRequestRequestTypeDef",
     {
         "botName": str,
@@ -385,10 +385,10 @@
         "messageFormat": MessageFormatTypeType,
         "dialogState": DialogStateType,
         "slotToElicit": str,
         "responseCard": ResponseCardTypeDef,
         "sessionId": str,
         "botVersion": str,
         "activeContexts": List[ActiveContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime/type_defs.pyi` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -33,26 +33,26 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ActiveContextTimeToLiveTypeDef",
     "ButtonTypeDef",
     "DeleteSessionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteSessionResponseTypeDef",
     "DialogActionTypeDef",
     "GetSessionRequestRequestTypeDef",
     "IntentSummaryTypeDef",
     "IntentConfidenceTypeDef",
     "PostContentRequestRequestTypeDef",
+    "PostContentResponseTypeDef",
     "SentimentResponseTypeDef",
+    "PutSessionResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "ActiveContextTypeDef",
     "GenericAttachmentTypeDef",
-    "DeleteSessionResponseTypeDef",
-    "PostContentResponseTypeDef",
-    "PutSessionResponseTypeDef",
     "PredictedIntentTypeDef",
     "GetSessionResponseTypeDef",
     "PostTextRequestRequestTypeDef",
     "PutSessionRequestRequestTypeDef",
     "ResponseCardTypeDef",
     "PostTextResponseTypeDef",
 )
@@ -79,22 +79,22 @@
     {
         "botName": str,
         "botAlias": str,
         "userId": str,
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
+        "botName": str,
+        "botAlias": str,
+        "userId": str,
+        "sessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDialogActionTypeDef = TypedDict(
     "_RequiredDialogActionTypeDef",
     {
         "type": DialogActionTypeType,
@@ -189,55 +189,14 @@
 )
 
 class PostContentRequestRequestTypeDef(
     _RequiredPostContentRequestRequestTypeDef, _OptionalPostContentRequestRequestTypeDef
 ):
     pass
 
-SentimentResponseTypeDef = TypedDict(
-    "SentimentResponseTypeDef",
-    {
-        "sentimentLabel": str,
-        "sentimentScore": str,
-    },
-    total=False,
-)
-
-ActiveContextTypeDef = TypedDict(
-    "ActiveContextTypeDef",
-    {
-        "name": str,
-        "timeToLive": ActiveContextTimeToLiveTypeDef,
-        "parameters": Dict[str, str],
-    },
-)
-
-GenericAttachmentTypeDef = TypedDict(
-    "GenericAttachmentTypeDef",
-    {
-        "title": str,
-        "subTitle": str,
-        "attachmentLinkUrl": str,
-        "imageUrl": str,
-        "buttons": List[ButtonTypeDef],
-    },
-    total=False,
-)
-
-DeleteSessionResponseTypeDef = TypedDict(
-    "DeleteSessionResponseTypeDef",
-    {
-        "botName": str,
-        "botAlias": str,
-        "userId": str,
-        "sessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 PostContentResponseTypeDef = TypedDict(
     "PostContentResponseTypeDef",
     {
         "contentType": str,
         "intentName": str,
         "nluIntentConfidence": str,
         "alternativeIntents": str,
@@ -251,16 +210,25 @@
         "slotToElicit": str,
         "inputTranscript": str,
         "encodedInputTranscript": str,
         "audioStream": StreamingBody,
         "botVersion": str,
         "sessionId": str,
         "activeContexts": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SentimentResponseTypeDef = TypedDict(
+    "SentimentResponseTypeDef",
+    {
+        "sentimentLabel": str,
+        "sentimentScore": str,
     },
+    total=False,
 )
 
 PutSessionResponseTypeDef = TypedDict(
     "PutSessionResponseTypeDef",
     {
         "contentType": str,
         "intentName": str,
@@ -270,18 +238,50 @@
         "encodedMessage": str,
         "messageFormat": MessageFormatTypeType,
         "dialogState": DialogStateType,
         "slotToElicit": str,
         "audioStream": StreamingBody,
         "sessionId": str,
         "activeContexts": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
+ActiveContextTypeDef = TypedDict(
+    "ActiveContextTypeDef",
+    {
+        "name": str,
+        "timeToLive": ActiveContextTimeToLiveTypeDef,
+        "parameters": Dict[str, str],
+    },
+)
+
+GenericAttachmentTypeDef = TypedDict(
+    "GenericAttachmentTypeDef",
+    {
+        "title": str,
+        "subTitle": str,
+        "attachmentLinkUrl": str,
+        "imageUrl": str,
+        "buttons": List[ButtonTypeDef],
+    },
+    total=False,
+)
+
 PredictedIntentTypeDef = TypedDict(
     "PredictedIntentTypeDef",
     {
         "intentName": str,
         "nluIntentConfidence": IntentConfidenceTypeDef,
         "slots": Dict[str, str],
     },
@@ -292,15 +292,15 @@
     "GetSessionResponseTypeDef",
     {
         "recentIntentSummaryView": List[IntentSummaryTypeDef],
         "sessionAttributes": Dict[str, str],
         "sessionId": str,
         "dialogAction": DialogActionTypeDef,
         "activeContexts": List[ActiveContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPostTextRequestRequestTypeDef = TypedDict(
     "_RequiredPostTextRequestRequestTypeDef",
     {
         "botName": str,
@@ -372,10 +372,10 @@
         "messageFormat": MessageFormatTypeType,
         "dialogState": DialogStateType,
         "slotToElicit": str,
         "responseCard": ResponseCardTypeDef,
         "sessionId": str,
         "botVersion": str,
         "activeContexts": List[ActiveContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/PKG-INFO` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lex-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LexRuntimeService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexRuntimeService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lex-runtime"></a>
 
 # types-aiobotocore-lex-runtime
 
 [![PyPI - types-aiobotocore-lex-runtime](https://img.shields.io/pypi/v/types-aiobotocore-lex-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lex-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lex-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-lex-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexRuntimeService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
+[aiobotocore.LexRuntimeService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-runtime.html#LexRuntimeService)
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
 [types-aiobotocore-lex-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,26 +298,26 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lex_runtime.type_defs import (
     ActiveContextTimeToLiveTypeDef,
     ButtonTypeDef,
     DeleteSessionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteSessionResponseTypeDef,
     DialogActionTypeDef,
     GetSessionRequestRequestTypeDef,
     IntentSummaryTypeDef,
     IntentConfidenceTypeDef,
     PostContentRequestRequestTypeDef,
+    PostContentResponseTypeDef,
     SentimentResponseTypeDef,
+    PutSessionResponseTypeDef,
+    ResponseMetadataTypeDef,
     ActiveContextTypeDef,
     GenericAttachmentTypeDef,
-    DeleteSessionResponseTypeDef,
-    PostContentResponseTypeDef,
-    PutSessionResponseTypeDef,
     PredictedIntentTypeDef,
     GetSessionResponseTypeDef,
     PostTextRequestRequestTypeDef,
     PutSessionRequestRequestTypeDef,
     ResponseCardTypeDef,
     PostTextResponseTypeDef,
 )
@@ -330,43 +330,43 @@
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

### Comparing `types-aiobotocore-lex-runtime-2.5.0.post1/types_aiobotocore_lex_runtime.egg-info/SOURCES.txt` & `types-aiobotocore-lex-runtime-2.5.1/types_aiobotocore_lex_runtime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

