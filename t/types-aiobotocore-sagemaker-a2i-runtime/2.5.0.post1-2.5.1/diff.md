# Comparing `tmp/types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sagemaker-a2i-runtime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-sagemaker-a2i-runtime-2.5.1.tar", last modified: Wed Jun 28 01:44:07 2023, max compression
```

## Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1.tar` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.967585 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14149 2023-03-11 12:27:15.963585 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12525 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:15.967585 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2211 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.963585 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/
--rw-r--r--   0 runner    (1001) docker     (123)      746 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      745 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      993 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8431 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8416 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7879 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7877 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2543 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2539 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5606 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5600 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:29.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.963585 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14149 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1079 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       40 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.242207 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14155 2023-06-28 01:44:07.242207 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12537 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:07.242207 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2205 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.230207 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/
+-rw-r--r--   0 runner    (1001) docker     (123)      746 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      981 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8431 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8416 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8088 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8086 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2425 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2422 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5615 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5608 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.242207 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14155 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1079 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       40 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/LICENSE` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-a2i-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AugmentedAIRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AugmentedAIRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-a2i-runtime"></a>
 
 # types-aiobotocore-sagemaker-a2i-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-a2i-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-a2i-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-a2i-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-a2i-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-a2i-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AugmentedAIRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
+[aiobotocore.AugmentedAIRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
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
 [types-aiobotocore-sagemaker-a2i-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,69 +319,69 @@
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_a2i_runtime.type_defs import (
     DeleteHumanLoopRequestRequestTypeDef,
     DescribeHumanLoopRequestRequestTypeDef,
     HumanLoopOutputTypeDef,
-    ResponseMetadataTypeDef,
     HumanLoopDataAttributesTypeDef,
     HumanLoopInputTypeDef,
     HumanLoopSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
     ListHumanLoopsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartHumanLoopResponseTypeDef,
     StopHumanLoopRequestRequestTypeDef,
     DescribeHumanLoopResponseTypeDef,
-    StartHumanLoopResponseTypeDef,
     StartHumanLoopRequestRequestTypeDef,
     ListHumanLoopsResponseTypeDef,
-    ListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
 )
 
 
 def get_structure() -> DeleteHumanLoopRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/README.md` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sagemaker-a2i-runtime"></a>
 
 # types-aiobotocore-sagemaker-a2i-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-a2i-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-a2i-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-a2i-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-a2i-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-a2i-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AugmentedAIRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
+[aiobotocore.AugmentedAIRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
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
 [types-aiobotocore-sagemaker-a2i-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -286,69 +286,69 @@
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_a2i_runtime.type_defs import (
     DeleteHumanLoopRequestRequestTypeDef,
     DescribeHumanLoopRequestRequestTypeDef,
     HumanLoopOutputTypeDef,
-    ResponseMetadataTypeDef,
     HumanLoopDataAttributesTypeDef,
     HumanLoopInputTypeDef,
     HumanLoopSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
     ListHumanLoopsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartHumanLoopResponseTypeDef,
     StopHumanLoopRequestRequestTypeDef,
     DescribeHumanLoopResponseTypeDef,
-    StartHumanLoopResponseTypeDef,
     StartHumanLoopRequestRequestTypeDef,
     ListHumanLoopsResponseTypeDef,
-    ListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
 )
 
 
 def get_structure() -> DeleteHumanLoopRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/setup.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/setup.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sagemaker-a2i-runtime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sagemaker-a2i-runtime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sagemaker_a2i_runtime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AugmentedAIRuntime 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AugmentedAIRuntime 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/",
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/__init__.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/__init__.pyi` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/__main__.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AugmentedAIRuntime 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AugmentedAIRuntime 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime\nOther"
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/client.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/client.pyi` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/literals.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -94,14 +94,15 @@
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
@@ -180,14 +181,15 @@
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
@@ -198,14 +200,15 @@
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
@@ -241,14 +244,15 @@
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
@@ -267,16 +271,19 @@
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
@@ -360,15 +367,17 @@
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/literals.pyi` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -92,14 +92,15 @@
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
@@ -178,14 +179,15 @@
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
@@ -196,14 +198,15 @@
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
@@ -239,14 +242,15 @@
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
@@ -265,16 +269,19 @@
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
@@ -358,15 +365,17 @@
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/paginator.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,30 +16,23 @@
     session = get_session()
     with session.create_client("sagemaker-a2i-runtime") as client:
         client: AugmentedAIRuntimeClient
 
         list_human_loops_paginator: ListHumanLoopsPaginator = client.get_paginator("list_human_loops")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SortOrderType
 from .type_defs import ListHumanLoopsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListHumanLoopsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -58,13 +51,13 @@
     def paginate(
         self,
         *,
         FlowDefinitionArn: str,
         CreationTimeAfter: Union[datetime, str] = ...,
         CreationTimeBefore: Union[datetime, str] = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHumanLoopsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime.Paginator.ListHumanLoops.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/paginators/#listhumanloopspaginator)
         """
```

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/paginator.pyi` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,29 +16,23 @@
     session = get_session()
     with session.create_client("sagemaker-a2i-runtime") as client:
         client: AugmentedAIRuntimeClient
 
         list_human_loops_paginator: ListHumanLoopsPaginator = client.get_paginator("list_human_loops")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SortOrderType
 from .type_defs import ListHumanLoopsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListHumanLoopsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -54,13 +48,13 @@
     def paginate(
         self,
         *,
         FlowDefinitionArn: str,
         CreationTimeAfter: Union[datetime, str] = ...,
         CreationTimeBefore: Union[datetime, str] = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHumanLoopsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime.Paginator.ListHumanLoops.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/paginators/#listhumanloopspaginator)
         """
```

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.py` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -23,26 +23,26 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DeleteHumanLoopRequestRequestTypeDef",
     "DescribeHumanLoopRequestRequestTypeDef",
     "HumanLoopOutputTypeDef",
-    "ResponseMetadataTypeDef",
     "HumanLoopDataAttributesTypeDef",
     "HumanLoopInputTypeDef",
     "HumanLoopSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
     "ListHumanLoopsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartHumanLoopResponseTypeDef",
     "StopHumanLoopRequestRequestTypeDef",
     "DescribeHumanLoopResponseTypeDef",
-    "StartHumanLoopResponseTypeDef",
     "StartHumanLoopRequestRequestTypeDef",
     "ListHumanLoopsResponseTypeDef",
-    "ListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
 )
 
 DeleteHumanLoopRequestRequestTypeDef = TypedDict(
     "DeleteHumanLoopRequestRequestTypeDef",
     {
         "HumanLoopName": str,
     },
@@ -58,25 +58,14 @@
 HumanLoopOutputTypeDef = TypedDict(
     "HumanLoopOutputTypeDef",
     {
         "OutputS3Uri": str,
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
 HumanLoopDataAttributesTypeDef = TypedDict(
     "HumanLoopDataAttributesTypeDef",
     {
         "ContentClassifiers": Sequence[ContentClassifierType],
     },
 )
 
@@ -95,24 +84,39 @@
         "CreationTime": datetime,
         "FailureReason": str,
         "FlowDefinitionArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
+    "_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FlowDefinitionArn": str,
+    },
+)
+_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
+    "_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
+    {
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListHumanLoopsRequestListHumanLoopsPaginateTypeDef(
+    _RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
+    _OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListHumanLoopsRequestRequestTypeDef = TypedDict(
     "_RequiredListHumanLoopsRequestRequestTypeDef",
     {
         "FlowDefinitionArn": str,
     },
 )
 _OptionalListHumanLoopsRequestRequestTypeDef = TypedDict(
@@ -130,14 +134,43 @@
 
 class ListHumanLoopsRequestRequestTypeDef(
     _RequiredListHumanLoopsRequestRequestTypeDef, _OptionalListHumanLoopsRequestRequestTypeDef
 ):
     pass
 
 
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
+StartHumanLoopResponseTypeDef = TypedDict(
+    "StartHumanLoopResponseTypeDef",
+    {
+        "HumanLoopArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopHumanLoopRequestRequestTypeDef = TypedDict(
     "StopHumanLoopRequestRequestTypeDef",
     {
         "HumanLoopName": str,
     },
 )
 
@@ -148,23 +181,15 @@
         "FailureReason": str,
         "FailureCode": str,
         "HumanLoopStatus": HumanLoopStatusType,
         "HumanLoopName": str,
         "HumanLoopArn": str,
         "FlowDefinitionArn": str,
         "HumanLoopOutput": HumanLoopOutputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartHumanLoopResponseTypeDef = TypedDict(
-    "StartHumanLoopResponseTypeDef",
-    {
-        "HumanLoopArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartHumanLoopRequestRequestTypeDef = TypedDict(
     "_RequiredStartHumanLoopRequestRequestTypeDef",
     {
         "HumanLoopName": str,
@@ -188,34 +213,10 @@
 
 
 ListHumanLoopsResponseTypeDef = TypedDict(
     "ListHumanLoopsResponseTypeDef",
     {
         "HumanLoopSummaries": List[HumanLoopSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-
-_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
-    "_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
-    {
-        "FlowDefinitionArn": str,
-    },
-)
-_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
-    "_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
-    {
-        "CreationTimeAfter": Union[datetime, str],
-        "CreationTimeBefore": Union[datetime, str],
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListHumanLoopsRequestListHumanLoopsPaginateTypeDef(
-    _RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
-    _OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
-):
-    pass
```

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.pyi` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -22,26 +22,26 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DeleteHumanLoopRequestRequestTypeDef",
     "DescribeHumanLoopRequestRequestTypeDef",
     "HumanLoopOutputTypeDef",
-    "ResponseMetadataTypeDef",
     "HumanLoopDataAttributesTypeDef",
     "HumanLoopInputTypeDef",
     "HumanLoopSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
     "ListHumanLoopsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartHumanLoopResponseTypeDef",
     "StopHumanLoopRequestRequestTypeDef",
     "DescribeHumanLoopResponseTypeDef",
-    "StartHumanLoopResponseTypeDef",
     "StartHumanLoopRequestRequestTypeDef",
     "ListHumanLoopsResponseTypeDef",
-    "ListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
 )
 
 DeleteHumanLoopRequestRequestTypeDef = TypedDict(
     "DeleteHumanLoopRequestRequestTypeDef",
     {
         "HumanLoopName": str,
     },
@@ -57,25 +57,14 @@
 HumanLoopOutputTypeDef = TypedDict(
     "HumanLoopOutputTypeDef",
     {
         "OutputS3Uri": str,
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
 HumanLoopDataAttributesTypeDef = TypedDict(
     "HumanLoopDataAttributesTypeDef",
     {
         "ContentClassifiers": Sequence[ContentClassifierType],
     },
 )
 
@@ -94,24 +83,37 @@
         "CreationTime": datetime,
         "FailureReason": str,
         "FlowDefinitionArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
+    "_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FlowDefinitionArn": str,
+    },
+)
+_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
+    "_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
+    {
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListHumanLoopsRequestListHumanLoopsPaginateTypeDef(
+    _RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
+    _OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
+):
+    pass
+
 _RequiredListHumanLoopsRequestRequestTypeDef = TypedDict(
     "_RequiredListHumanLoopsRequestRequestTypeDef",
     {
         "FlowDefinitionArn": str,
     },
 )
 _OptionalListHumanLoopsRequestRequestTypeDef = TypedDict(
@@ -127,14 +129,43 @@
 )
 
 class ListHumanLoopsRequestRequestTypeDef(
     _RequiredListHumanLoopsRequestRequestTypeDef, _OptionalListHumanLoopsRequestRequestTypeDef
 ):
     pass
 
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
+StartHumanLoopResponseTypeDef = TypedDict(
+    "StartHumanLoopResponseTypeDef",
+    {
+        "HumanLoopArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopHumanLoopRequestRequestTypeDef = TypedDict(
     "StopHumanLoopRequestRequestTypeDef",
     {
         "HumanLoopName": str,
     },
 )
 
@@ -145,23 +176,15 @@
         "FailureReason": str,
         "FailureCode": str,
         "HumanLoopStatus": HumanLoopStatusType,
         "HumanLoopName": str,
         "HumanLoopArn": str,
         "FlowDefinitionArn": str,
         "HumanLoopOutput": HumanLoopOutputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartHumanLoopResponseTypeDef = TypedDict(
-    "StartHumanLoopResponseTypeDef",
-    {
-        "HumanLoopArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartHumanLoopRequestRequestTypeDef = TypedDict(
     "_RequiredStartHumanLoopRequestRequestTypeDef",
     {
         "HumanLoopName": str,
@@ -183,33 +206,10 @@
     pass
 
 ListHumanLoopsResponseTypeDef = TypedDict(
     "ListHumanLoopsResponseTypeDef",
     {
         "HumanLoopSummaries": List[HumanLoopSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
-    "_RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
-    {
-        "FlowDefinitionArn": str,
-    },
-)
-_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef = TypedDict(
-    "_OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef",
-    {
-        "CreationTimeAfter": Union[datetime, str],
-        "CreationTimeBefore": Union[datetime, str],
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
-
-class ListHumanLoopsRequestListHumanLoopsPaginateTypeDef(
-    _RequiredListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
-    _OptionalListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
-):
-    pass
```

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/PKG-INFO` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-a2i-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AugmentedAIRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AugmentedAIRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-a2i-runtime"></a>
 
 # types-aiobotocore-sagemaker-a2i-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-a2i-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-a2i-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-a2i-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-a2i-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-a2i-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-a2i-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AugmentedAIRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
+[aiobotocore.AugmentedAIRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-a2i-runtime.html#AugmentedAIRuntime)
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
 [types-aiobotocore-sagemaker-a2i-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_a2i_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,69 +319,69 @@
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_a2i_runtime.type_defs import (
     DeleteHumanLoopRequestRequestTypeDef,
     DescribeHumanLoopRequestRequestTypeDef,
     HumanLoopOutputTypeDef,
-    ResponseMetadataTypeDef,
     HumanLoopDataAttributesTypeDef,
     HumanLoopInputTypeDef,
     HumanLoopSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
     ListHumanLoopsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    StartHumanLoopResponseTypeDef,
     StopHumanLoopRequestRequestTypeDef,
     DescribeHumanLoopResponseTypeDef,
-    StartHumanLoopResponseTypeDef,
     StartHumanLoopRequestRequestTypeDef,
     ListHumanLoopsResponseTypeDef,
-    ListHumanLoopsRequestListHumanLoopsPaginateTypeDef,
 )
 
 
 def get_structure() -> DeleteHumanLoopRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-sagemaker-a2i-runtime-2.5.0.post1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/SOURCES.txt` & `types-aiobotocore-sagemaker-a2i-runtime-2.5.1/types_aiobotocore_sagemaker_a2i_runtime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

