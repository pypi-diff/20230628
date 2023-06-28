# Comparing `tmp/types-aiobotocore-personalize-runtime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-personalize-runtime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-personalize-runtime-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:06 2023, max compression
+gzip compressed data, was "types-aiobotocore-personalize-runtime-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1.tar` & `types-aiobotocore-personalize-runtime-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.331491 types-aiobotocore-personalize-runtime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12872 2023-03-11 12:27:06.327491 types-aiobotocore-personalize-runtime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11254 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:06.331491 types-aiobotocore-personalize-runtime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2199 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.323491 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/
--rw-r--r--   0 runner    (1001) docker     (123)      533 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      532 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5978 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5968 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7400 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7398 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     3069 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     3066 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:45.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.327491 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12872 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.390191 types-aiobotocore-personalize-runtime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12876 2023-06-28 01:43:58.390191 types-aiobotocore-personalize-runtime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11264 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.390191 types-aiobotocore-personalize-runtime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2193 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.390191 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/
+-rw-r--r--   0 runner    (1001) docker     (123)      533 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5978 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5968 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7609 2023-06-28 01:36:32.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7607 2023-06-28 01:36:32.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     3073 2023-06-28 01:36:32.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3070 2023-06-28 01:36:32.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:31.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.390191 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12876 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/LICENSE` & `types-aiobotocore-personalize-runtime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-personalize-runtime-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-personalize-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PersonalizeRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PersonalizeRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-personalize-runtime"></a>
 
 # types-aiobotocore-personalize-runtime
 
 [![PyPI - types-aiobotocore-personalize-runtime](https://img.shields.io/pypi/v/types-aiobotocore-personalize-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-personalize-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-personalize-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-personalize-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PersonalizeRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
+[aiobotocore.PersonalizeRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
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
 [types-aiobotocore-personalize-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,16 +290,16 @@
 `types_aiobotocore_personalize_runtime.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_personalize_runtime.type_defs import (
     GetPersonalizedRankingRequestRequestTypeDef,
     PredictedItemTypeDef,
-    ResponseMetadataTypeDef,
     PromotionTypeDef,
+    ResponseMetadataTypeDef,
     GetPersonalizedRankingResponseTypeDef,
     GetRecommendationsResponseTypeDef,
     GetRecommendationsRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetPersonalizedRankingRequestRequestTypeDef:
@@ -309,43 +309,43 @@
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/README.md` & `types-aiobotocore-personalize-runtime-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-personalize-runtime"></a>
 
 # types-aiobotocore-personalize-runtime
 
 [![PyPI - types-aiobotocore-personalize-runtime](https://img.shields.io/pypi/v/types-aiobotocore-personalize-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-personalize-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-personalize-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-personalize-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PersonalizeRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
+[aiobotocore.PersonalizeRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
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
 [types-aiobotocore-personalize-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -257,16 +257,16 @@
 `types_aiobotocore_personalize_runtime.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_personalize_runtime.type_defs import (
     GetPersonalizedRankingRequestRequestTypeDef,
     PredictedItemTypeDef,
-    ResponseMetadataTypeDef,
     PromotionTypeDef,
+    ResponseMetadataTypeDef,
     GetPersonalizedRankingResponseTypeDef,
     GetRecommendationsResponseTypeDef,
     GetRecommendationsRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetPersonalizedRankingRequestRequestTypeDef:
@@ -276,43 +276,43 @@
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/setup.py` & `types-aiobotocore-personalize-runtime-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-personalize-runtime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-personalize-runtime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_personalize_runtime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.PersonalizeRuntime 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.PersonalizeRuntime 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/",
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/__init__.py` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/__init__.pyi` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/__main__.py` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/__main__.py`

 * *Files 19% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.PersonalizeRuntime 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.PersonalizeRuntime 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime\nOther"
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/client.py` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/client.pyi` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/literals.py` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -81,14 +81,15 @@
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
@@ -167,14 +168,15 @@
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
@@ -185,14 +187,15 @@
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
@@ -228,14 +231,15 @@
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
@@ -254,16 +258,19 @@
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
@@ -347,15 +354,17 @@
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/literals.pyi` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -79,14 +79,15 @@
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
@@ -165,14 +166,15 @@
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
@@ -183,14 +185,15 @@
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
@@ -226,14 +229,15 @@
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
@@ -252,16 +256,19 @@
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
@@ -345,15 +352,17 @@
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/type_defs.py` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "GetPersonalizedRankingRequestRequestTypeDef",
     "PredictedItemTypeDef",
-    "ResponseMetadataTypeDef",
     "PromotionTypeDef",
+    "ResponseMetadataTypeDef",
     "GetPersonalizedRankingResponseTypeDef",
     "GetRecommendationsResponseTypeDef",
     "GetRecommendationsRequestRequestTypeDef",
 )
 
 _RequiredGetPersonalizedRankingRequestRequestTypeDef = TypedDict(
     "_RequiredGetPersonalizedRankingRequestRequestTypeDef",
@@ -62,51 +62,51 @@
         "itemId": str,
         "score": float,
         "promotionName": str,
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
 PromotionTypeDef = TypedDict(
     "PromotionTypeDef",
     {
         "name": str,
         "percentPromotedItems": int,
         "filterArn": str,
         "filterValues": Mapping[str, str],
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
 GetPersonalizedRankingResponseTypeDef = TypedDict(
     "GetPersonalizedRankingResponseTypeDef",
     {
         "personalizedRanking": List[PredictedItemTypeDef],
         "recommendationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommendationsResponseTypeDef = TypedDict(
     "GetRecommendationsResponseTypeDef",
     {
         "itemList": List[PredictedItemTypeDef],
         "recommendationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommendationsRequestRequestTypeDef = TypedDict(
     "GetRecommendationsRequestRequestTypeDef",
     {
         "campaignArn": str,
```

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime/type_defs.pyi` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,16 +18,16 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "GetPersonalizedRankingRequestRequestTypeDef",
     "PredictedItemTypeDef",
-    "ResponseMetadataTypeDef",
     "PromotionTypeDef",
+    "ResponseMetadataTypeDef",
     "GetPersonalizedRankingResponseTypeDef",
     "GetRecommendationsResponseTypeDef",
     "GetRecommendationsRequestRequestTypeDef",
 )
 
 _RequiredGetPersonalizedRankingRequestRequestTypeDef = TypedDict(
     "_RequiredGetPersonalizedRankingRequestRequestTypeDef",
@@ -59,51 +59,51 @@
         "itemId": str,
         "score": float,
         "promotionName": str,
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
 PromotionTypeDef = TypedDict(
     "PromotionTypeDef",
     {
         "name": str,
         "percentPromotedItems": int,
         "filterArn": str,
         "filterValues": Mapping[str, str],
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
 GetPersonalizedRankingResponseTypeDef = TypedDict(
     "GetPersonalizedRankingResponseTypeDef",
     {
         "personalizedRanking": List[PredictedItemTypeDef],
         "recommendationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommendationsResponseTypeDef = TypedDict(
     "GetRecommendationsResponseTypeDef",
     {
         "itemList": List[PredictedItemTypeDef],
         "recommendationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommendationsRequestRequestTypeDef = TypedDict(
     "GetRecommendationsRequestRequestTypeDef",
     {
         "campaignArn": str,
```

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/PKG-INFO` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-personalize-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PersonalizeRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PersonalizeRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-personalize-runtime"></a>
 
 # types-aiobotocore-personalize-runtime
 
 [![PyPI - types-aiobotocore-personalize-runtime](https://img.shields.io/pypi/v/types-aiobotocore-personalize-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-personalize-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-personalize-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-personalize-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PersonalizeRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
+[aiobotocore.PersonalizeRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize-runtime.html#PersonalizeRuntime)
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
 [types-aiobotocore-personalize-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,16 +290,16 @@
 `types_aiobotocore_personalize_runtime.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_personalize_runtime.type_defs import (
     GetPersonalizedRankingRequestRequestTypeDef,
     PredictedItemTypeDef,
-    ResponseMetadataTypeDef,
     PromotionTypeDef,
+    ResponseMetadataTypeDef,
     GetPersonalizedRankingResponseTypeDef,
     GetRecommendationsResponseTypeDef,
     GetRecommendationsRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetPersonalizedRankingRequestRequestTypeDef:
@@ -309,43 +309,43 @@
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

### Comparing `types-aiobotocore-personalize-runtime-2.5.0.post1/types_aiobotocore_personalize_runtime.egg-info/SOURCES.txt` & `types-aiobotocore-personalize-runtime-2.5.1/types_aiobotocore_personalize_runtime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

