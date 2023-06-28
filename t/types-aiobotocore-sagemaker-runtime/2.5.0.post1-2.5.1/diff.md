# Comparing `tmp/types-aiobotocore-sagemaker-runtime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sagemaker-runtime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sagemaker-runtime-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-sagemaker-runtime-2.5.1.tar", last modified: Wed Jun 28 01:44:07 2023, max compression
```

## Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1.tar` & `types-aiobotocore-sagemaker-runtime-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:17.995604 types-aiobotocore-sagemaker-runtime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12713 2023-03-11 12:27:17.995604 types-aiobotocore-sagemaker-runtime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11103 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:17.995604 types-aiobotocore-sagemaker-runtime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:17.995604 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/
--rw-r--r--   0 runner    (1001) docker     (123)      517 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      516 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6503 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6493 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7855 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7853 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2959 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2954 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:17.995604 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12713 2023-03-11 12:27:17.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-03-11 12:27:17.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:17.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:17.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:17.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:27:17.000000 types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.982209 types-aiobotocore-sagemaker-runtime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12715 2023-06-28 01:44:07.982209 types-aiobotocore-sagemaker-runtime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11111 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:07.982209 types-aiobotocore-sagemaker-runtime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2203 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.982209 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/
+-rw-r--r--   0 runner    (1001) docker     (123)      517 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      516 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6503 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6493 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8142 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8140 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2995 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2990 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.982209 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12715 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/LICENSE` & `types-aiobotocore-sagemaker-runtime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sagemaker-runtime-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SageMakerRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SageMakerRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-runtime"></a>
 
 # types-aiobotocore-sagemaker-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
+[aiobotocore.SageMakerRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
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
 [types-aiobotocore-sagemaker-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,61 +290,61 @@
 
 `types_aiobotocore_sagemaker_runtime.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_runtime.type_defs import (
     InvokeEndpointAsyncInputRequestTypeDef,
-    ResponseMetadataTypeDef,
-    InvokeEndpointInputRequestTypeDef,
     InvokeEndpointAsyncOutputTypeDef,
+    InvokeEndpointInputRequestTypeDef,
     InvokeEndpointOutputTypeDef,
+    ResponseMetadataTypeDef,
 )
 
 
 def get_structure() -> InvokeEndpointAsyncInputRequestTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/README.md` & `types-aiobotocore-sagemaker-runtime-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sagemaker-runtime"></a>
 
 # types-aiobotocore-sagemaker-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
+[aiobotocore.SageMakerRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
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
 [types-aiobotocore-sagemaker-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -257,61 +257,61 @@
 
 `types_aiobotocore_sagemaker_runtime.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_runtime.type_defs import (
     InvokeEndpointAsyncInputRequestTypeDef,
-    ResponseMetadataTypeDef,
-    InvokeEndpointInputRequestTypeDef,
     InvokeEndpointAsyncOutputTypeDef,
+    InvokeEndpointInputRequestTypeDef,
     InvokeEndpointOutputTypeDef,
+    ResponseMetadataTypeDef,
 )
 
 
 def get_structure() -> InvokeEndpointAsyncInputRequestTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/setup.py` & `types-aiobotocore-sagemaker-runtime-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sagemaker-runtime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sagemaker-runtime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sagemaker_runtime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SageMakerRuntime 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SageMakerRuntime 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/"
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

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/__init__.py` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/__init__.pyi` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/__main__.py` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/__main__.py`

 * *Files 18% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SageMakerRuntime 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SageMakerRuntime 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime\nOther"
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

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/client.py` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/client.pyi` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/literals.py` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/literals.py`

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
@@ -380,21 +389,25 @@
 RegionName = Literal[
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
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/literals.pyi` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/literals.pyi`

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
@@ -378,21 +387,25 @@
 RegionName = Literal[
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
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/type_defs.py` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -17,21 +17,20 @@
 from aiobotocore.response import StreamingBody
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "InvokeEndpointAsyncInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "InvokeEndpointInputRequestTypeDef",
     "InvokeEndpointAsyncOutputTypeDef",
+    "InvokeEndpointInputRequestTypeDef",
     "InvokeEndpointOutputTypeDef",
+    "ResponseMetadataTypeDef",
 )
 
 _RequiredInvokeEndpointAsyncInputRequestTypeDef = TypedDict(
     "_RequiredInvokeEndpointAsyncInputRequestTypeDef",
     {
         "EndpointName": str,
         "InputLocation": str,
@@ -46,29 +45,26 @@
         "InferenceId": str,
         "RequestTTLSeconds": int,
         "InvocationTimeoutSeconds": int,
     },
     total=False,
 )
 
-
 class InvokeEndpointAsyncInputRequestTypeDef(
     _RequiredInvokeEndpointAsyncInputRequestTypeDef, _OptionalInvokeEndpointAsyncInputRequestTypeDef
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+InvokeEndpointAsyncOutputTypeDef = TypedDict(
+    "InvokeEndpointAsyncOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "InferenceId": str,
+        "OutputLocation": str,
+        "FailureLocation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInvokeEndpointInputRequestTypeDef = TypedDict(
     "_RequiredInvokeEndpointInputRequestTypeDef",
     {
         "EndpointName": str,
@@ -86,33 +82,33 @@
         "TargetContainerHostname": str,
         "InferenceId": str,
         "EnableExplanations": str,
     },
     total=False,
 )
 
-
 class InvokeEndpointInputRequestTypeDef(
     _RequiredInvokeEndpointInputRequestTypeDef, _OptionalInvokeEndpointInputRequestTypeDef
 ):
     pass
 
-
-InvokeEndpointAsyncOutputTypeDef = TypedDict(
-    "InvokeEndpointAsyncOutputTypeDef",
-    {
-        "InferenceId": str,
-        "OutputLocation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 InvokeEndpointOutputTypeDef = TypedDict(
     "InvokeEndpointOutputTypeDef",
     {
         "Body": StreamingBody,
         "ContentType": str,
         "InvokedProductionVariant": str,
         "CustomAttributes": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
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
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime/type_defs.pyi` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -17,20 +17,21 @@
 from aiobotocore.response import StreamingBody
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "InvokeEndpointAsyncInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "InvokeEndpointInputRequestTypeDef",
     "InvokeEndpointAsyncOutputTypeDef",
+    "InvokeEndpointInputRequestTypeDef",
     "InvokeEndpointOutputTypeDef",
+    "ResponseMetadataTypeDef",
 )
 
 _RequiredInvokeEndpointAsyncInputRequestTypeDef = TypedDict(
     "_RequiredInvokeEndpointAsyncInputRequestTypeDef",
     {
         "EndpointName": str,
         "InputLocation": str,
@@ -45,27 +46,28 @@
         "InferenceId": str,
         "RequestTTLSeconds": int,
         "InvocationTimeoutSeconds": int,
     },
     total=False,
 )
 
+
 class InvokeEndpointAsyncInputRequestTypeDef(
     _RequiredInvokeEndpointAsyncInputRequestTypeDef, _OptionalInvokeEndpointAsyncInputRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+InvokeEndpointAsyncOutputTypeDef = TypedDict(
+    "InvokeEndpointAsyncOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "InferenceId": str,
+        "OutputLocation": str,
+        "FailureLocation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInvokeEndpointInputRequestTypeDef = TypedDict(
     "_RequiredInvokeEndpointInputRequestTypeDef",
     {
         "EndpointName": str,
@@ -83,31 +85,35 @@
         "TargetContainerHostname": str,
         "InferenceId": str,
         "EnableExplanations": str,
     },
     total=False,
 )
 
+
 class InvokeEndpointInputRequestTypeDef(
     _RequiredInvokeEndpointInputRequestTypeDef, _OptionalInvokeEndpointInputRequestTypeDef
 ):
     pass
 
-InvokeEndpointAsyncOutputTypeDef = TypedDict(
-    "InvokeEndpointAsyncOutputTypeDef",
-    {
-        "InferenceId": str,
-        "OutputLocation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 InvokeEndpointOutputTypeDef = TypedDict(
     "InvokeEndpointOutputTypeDef",
     {
         "Body": StreamingBody,
         "ContentType": str,
         "InvokedProductionVariant": str,
         "CustomAttributes": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
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
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/PKG-INFO` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SageMakerRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SageMakerRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-runtime"></a>
 
 # types-aiobotocore-sagemaker-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
+[aiobotocore.SageMakerRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-runtime.html#SageMakerRuntime)
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
 [types-aiobotocore-sagemaker-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,61 +290,61 @@
 
 `types_aiobotocore_sagemaker_runtime.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_runtime.type_defs import (
     InvokeEndpointAsyncInputRequestTypeDef,
-    ResponseMetadataTypeDef,
-    InvokeEndpointInputRequestTypeDef,
     InvokeEndpointAsyncOutputTypeDef,
+    InvokeEndpointInputRequestTypeDef,
     InvokeEndpointOutputTypeDef,
+    ResponseMetadataTypeDef,
 )
 
 
 def get_structure() -> InvokeEndpointAsyncInputRequestTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-sagemaker-runtime-2.5.0.post1/types_aiobotocore_sagemaker_runtime.egg-info/SOURCES.txt` & `types-aiobotocore-sagemaker-runtime-2.5.1/types_aiobotocore_sagemaker_runtime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

