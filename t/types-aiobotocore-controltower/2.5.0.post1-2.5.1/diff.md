# Comparing `tmp/types-aiobotocore-controltower-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-controltower-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-controltower-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-controltower-2.5.1.tar", last modified: Wed Jun 28 01:43:20 2023, max compression
```

## Comparing `types-aiobotocore-controltower-2.5.0.post1.tar` & `types-aiobotocore-controltower-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.395099 types-aiobotocore-controltower-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13663 2023-03-11 12:26:27.395099 types-aiobotocore-controltower-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12072 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:27.395099 types-aiobotocore-controltower-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:12:02.000000 types-aiobotocore-controltower-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.395099 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/
--rw-r--r--   0 runner    (1001) docker     (123)      719 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      718 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7361 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7347 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8072 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8070 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2245 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2241 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     4478 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     4474 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:03.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.395099 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13663 2023-03-11 12:26:27.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:27.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:27.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:27.000000 types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.310119 types-aiobotocore-controltower-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13660 2023-06-28 01:43:20.310119 types-aiobotocore-controltower-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12075 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:20.310119 types-aiobotocore-controltower-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.306119 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/
+-rw-r--r--   0 runner    (1001) docker     (123)      719 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      718 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7361 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7347 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8413 2023-06-28 01:28:42.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8411 2023-06-28 01:28:42.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2127 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     4489 2023-06-28 01:28:42.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4484 2023-06-28 01:28:42.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:41.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.310119 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13660 2023-06-28 01:43:20.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:20.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:20.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:20.000000 types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/LICENSE` & `types-aiobotocore-controltower-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-controltower-2.5.0.post1/PKG-INFO` & `types-aiobotocore-controltower-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-controltower
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ControlTower 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ControlTower 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-controltower"></a>
 
 # types-aiobotocore-controltower
 
 [![PyPI - types-aiobotocore-controltower](https://img.shields.io/pypi/v/types-aiobotocore-controltower.svg?color=blue)](https://pypi.org/project/types-aiobotocore-controltower)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-controltower.svg?color=blue)](https://pypi.org/project/types-aiobotocore-controltower)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-controltower?color=blue)](https://pypistats.org/packages/types-aiobotocore-controltower)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ControlTower 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower)
+[aiobotocore.ControlTower 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower)
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
 [types-aiobotocore-controltower docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,68 +320,68 @@
 `types_aiobotocore_controltower.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_controltower.type_defs import (
     ControlOperationTypeDef,
     DisableControlInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DisableControlOutputTypeDef,
     EnableControlInputRequestTypeDef,
+    EnableControlOutputTypeDef,
     EnabledControlSummaryTypeDef,
     GetControlOperationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListEnabledControlsInputListEnabledControlsPaginateTypeDef,
     ListEnabledControlsInputRequestTypeDef,
-    DisableControlOutputTypeDef,
-    EnableControlOutputTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     GetControlOperationOutputTypeDef,
     ListEnabledControlsOutputTypeDef,
-    ListEnabledControlsInputListEnabledControlsPaginateTypeDef,
 )
 
 
 def get_structure() -> ControlOperationTypeDef:
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

### Comparing `types-aiobotocore-controltower-2.5.0.post1/README.md` & `types-aiobotocore-controltower-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-controltower"></a>
 
 # types-aiobotocore-controltower
 
 [![PyPI - types-aiobotocore-controltower](https://img.shields.io/pypi/v/types-aiobotocore-controltower.svg?color=blue)](https://pypi.org/project/types-aiobotocore-controltower)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-controltower.svg?color=blue)](https://pypi.org/project/types-aiobotocore-controltower)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-controltower?color=blue)](https://pypistats.org/packages/types-aiobotocore-controltower)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ControlTower 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower)
+[aiobotocore.ControlTower 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower)
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
 [types-aiobotocore-controltower docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,68 +287,68 @@
 `types_aiobotocore_controltower.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_controltower.type_defs import (
     ControlOperationTypeDef,
     DisableControlInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DisableControlOutputTypeDef,
     EnableControlInputRequestTypeDef,
+    EnableControlOutputTypeDef,
     EnabledControlSummaryTypeDef,
     GetControlOperationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListEnabledControlsInputListEnabledControlsPaginateTypeDef,
     ListEnabledControlsInputRequestTypeDef,
-    DisableControlOutputTypeDef,
-    EnableControlOutputTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     GetControlOperationOutputTypeDef,
     ListEnabledControlsOutputTypeDef,
-    ListEnabledControlsInputListEnabledControlsPaginateTypeDef,
 )
 
 
 def get_structure() -> ControlOperationTypeDef:
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

### Comparing `types-aiobotocore-controltower-2.5.0.post1/setup.py` & `types-aiobotocore-controltower-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-controltower.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-controltower",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_controltower"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ControlTower 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ControlTower 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/"
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

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/__init__.py` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/__init__.pyi` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/__main__.py` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ControlTower 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ControlTower 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower\nOther"
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

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/client.py` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/client.pyi` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/literals.py` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/literals.py`

 * *Files 12% similar despite different names*

```diff
@@ -93,14 +93,15 @@
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
@@ -179,14 +180,15 @@
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
@@ -197,14 +199,15 @@
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
@@ -240,14 +243,15 @@
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
@@ -266,16 +270,19 @@
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
@@ -359,15 +366,17 @@
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
@@ -387,23 +396,30 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_enabled_controls"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
+    "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
+    "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/literals.pyi` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/literals.pyi`

 * *Files 11% similar despite different names*

```diff
@@ -91,14 +91,15 @@
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
@@ -177,14 +178,15 @@
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
@@ -195,14 +197,15 @@
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
@@ -238,14 +241,15 @@
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
@@ -264,16 +268,19 @@
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
@@ -357,15 +364,17 @@
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
@@ -385,23 +394,30 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_enabled_controls"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
+    "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
+    "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/paginator.py` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("controltower") as client:
         client: ControlTowerClient
 
         list_enabled_controls_paginator: ListEnabledControlsPaginator = client.get_paginator("list_enabled_controls")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListEnabledControlsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListEnabledControlsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListEnabledControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower.Paginator.ListEnabledControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/paginators/#listenabledcontrolspaginator)
     """
 
     def paginate(
-        self, *, targetIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, targetIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnabledControlsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower.Paginator.ListEnabledControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/paginators/#listenabledcontrolspaginator)
         """
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/paginator.pyi` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/paginator.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("controltower") as client:
         client: ControlTowerClient
 
         list_enabled_controls_paginator: ListEnabledControlsPaginator = client.get_paginator("list_enabled_controls")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListEnabledControlsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListEnabledControlsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListEnabledControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower.Paginator.ListEnabledControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/paginators/#listenabledcontrolspaginator)
     """
 
     def paginate(
-        self, *, targetIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, targetIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnabledControlsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower.Paginator.ListEnabledControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/paginators/#listenabledcontrolspaginator)
         """
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/type_defs.py` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,29 +18,28 @@
 from .literals import ControlOperationStatusType, ControlOperationTypeType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ControlOperationTypeDef",
     "DisableControlInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DisableControlOutputTypeDef",
     "EnableControlInputRequestTypeDef",
+    "EnableControlOutputTypeDef",
     "EnabledControlSummaryTypeDef",
     "GetControlOperationInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEnabledControlsInputListEnabledControlsPaginateTypeDef",
     "ListEnabledControlsInputRequestTypeDef",
-    "DisableControlOutputTypeDef",
-    "EnableControlOutputTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "GetControlOperationOutputTypeDef",
     "ListEnabledControlsOutputTypeDef",
-    "ListEnabledControlsInputListEnabledControlsPaginateTypeDef",
 )
 
 ControlOperationTypeDef = TypedDict(
     "ControlOperationTypeDef",
     {
         "endTime": datetime,
         "operationType": ControlOperationTypeType,
@@ -55,33 +54,38 @@
     "DisableControlInputRequestTypeDef",
     {
         "controlIdentifier": str,
         "targetIdentifier": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DisableControlOutputTypeDef = TypedDict(
+    "DisableControlOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "operationIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableControlInputRequestTypeDef = TypedDict(
     "EnableControlInputRequestTypeDef",
     {
         "controlIdentifier": str,
         "targetIdentifier": str,
     },
 )
 
+EnableControlOutputTypeDef = TypedDict(
+    "EnableControlOutputTypeDef",
+    {
+        "operationIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnabledControlSummaryTypeDef = TypedDict(
     "EnabledControlSummaryTypeDef",
     {
         "controlIdentifier": str,
     },
     total=False,
 )
@@ -89,24 +93,34 @@
 GetControlOperationInputRequestTypeDef = TypedDict(
     "GetControlOperationInputRequestTypeDef",
     {
         "operationIdentifier": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
+    "_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "targetIdentifier": str,
+    },
+)
+_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
+    "_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListEnabledControlsInputListEnabledControlsPaginateTypeDef(
+    _RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef,
+    _OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEnabledControlsInputRequestTypeDef = TypedDict(
     "_RequiredListEnabledControlsInputRequestTypeDef",
     {
         "targetIdentifier": str,
     },
 )
 _OptionalListEnabledControlsInputRequestTypeDef = TypedDict(
@@ -114,67 +128,49 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListEnabledControlsInputRequestTypeDef(
     _RequiredListEnabledControlsInputRequestTypeDef, _OptionalListEnabledControlsInputRequestTypeDef
 ):
     pass
 
-
-DisableControlOutputTypeDef = TypedDict(
-    "DisableControlOutputTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "operationIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-EnableControlOutputTypeDef = TypedDict(
-    "EnableControlOutputTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "operationIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 GetControlOperationOutputTypeDef = TypedDict(
     "GetControlOperationOutputTypeDef",
     {
         "controlOperation": ControlOperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnabledControlsOutputTypeDef = TypedDict(
     "ListEnabledControlsOutputTypeDef",
     {
         "enabledControls": List[EnabledControlSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
-    "_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef",
-    {
-        "targetIdentifier": str,
-    },
-)
-_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
-    "_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
-
-
-class ListEnabledControlsInputListEnabledControlsPaginateTypeDef(
-    _RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef,
-    _OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef,
-):
-    pass
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower/type_defs.pyi` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,28 +18,29 @@
 from .literals import ControlOperationStatusType, ControlOperationTypeType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ControlOperationTypeDef",
     "DisableControlInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DisableControlOutputTypeDef",
     "EnableControlInputRequestTypeDef",
+    "EnableControlOutputTypeDef",
     "EnabledControlSummaryTypeDef",
     "GetControlOperationInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEnabledControlsInputListEnabledControlsPaginateTypeDef",
     "ListEnabledControlsInputRequestTypeDef",
-    "DisableControlOutputTypeDef",
-    "EnableControlOutputTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "GetControlOperationOutputTypeDef",
     "ListEnabledControlsOutputTypeDef",
-    "ListEnabledControlsInputListEnabledControlsPaginateTypeDef",
 )
 
 ControlOperationTypeDef = TypedDict(
     "ControlOperationTypeDef",
     {
         "endTime": datetime,
         "operationType": ControlOperationTypeType,
@@ -54,33 +55,38 @@
     "DisableControlInputRequestTypeDef",
     {
         "controlIdentifier": str,
         "targetIdentifier": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DisableControlOutputTypeDef = TypedDict(
+    "DisableControlOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "operationIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableControlInputRequestTypeDef = TypedDict(
     "EnableControlInputRequestTypeDef",
     {
         "controlIdentifier": str,
         "targetIdentifier": str,
     },
 )
 
+EnableControlOutputTypeDef = TypedDict(
+    "EnableControlOutputTypeDef",
+    {
+        "operationIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnabledControlSummaryTypeDef = TypedDict(
     "EnabledControlSummaryTypeDef",
     {
         "controlIdentifier": str,
     },
     total=False,
 )
@@ -88,24 +94,36 @@
 GetControlOperationInputRequestTypeDef = TypedDict(
     "GetControlOperationInputRequestTypeDef",
     {
         "operationIdentifier": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
+    "_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "targetIdentifier": str,
+    },
+)
+_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
+    "_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListEnabledControlsInputListEnabledControlsPaginateTypeDef(
+    _RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef,
+    _OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEnabledControlsInputRequestTypeDef = TypedDict(
     "_RequiredListEnabledControlsInputRequestTypeDef",
     {
         "targetIdentifier": str,
     },
 )
 _OptionalListEnabledControlsInputRequestTypeDef = TypedDict(
@@ -113,64 +131,51 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListEnabledControlsInputRequestTypeDef(
     _RequiredListEnabledControlsInputRequestTypeDef, _OptionalListEnabledControlsInputRequestTypeDef
 ):
     pass
 
-DisableControlOutputTypeDef = TypedDict(
-    "DisableControlOutputTypeDef",
+
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "operationIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-EnableControlOutputTypeDef = TypedDict(
-    "EnableControlOutputTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "operationIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 GetControlOperationOutputTypeDef = TypedDict(
     "GetControlOperationOutputTypeDef",
     {
         "controlOperation": ControlOperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnabledControlsOutputTypeDef = TypedDict(
     "ListEnabledControlsOutputTypeDef",
     {
         "enabledControls": List[EnabledControlSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
-    "_RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef",
-    {
-        "targetIdentifier": str,
-    },
-)
-_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef = TypedDict(
-    "_OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
-
-class ListEnabledControlsInputListEnabledControlsPaginateTypeDef(
-    _RequiredListEnabledControlsInputListEnabledControlsPaginateTypeDef,
-    _OptionalListEnabledControlsInputListEnabledControlsPaginateTypeDef,
-):
-    pass
```

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/PKG-INFO` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-controltower
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ControlTower 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ControlTower 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-controltower"></a>
 
 # types-aiobotocore-controltower
 
 [![PyPI - types-aiobotocore-controltower](https://img.shields.io/pypi/v/types-aiobotocore-controltower.svg?color=blue)](https://pypi.org/project/types-aiobotocore-controltower)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-controltower.svg?color=blue)](https://pypi.org/project/types-aiobotocore-controltower)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-controltower?color=blue)](https://pypistats.org/packages/types-aiobotocore-controltower)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ControlTower 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower)
+[aiobotocore.ControlTower 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/controltower.html#ControlTower)
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
 [types-aiobotocore-controltower docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_controltower/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,68 +320,68 @@
 `types_aiobotocore_controltower.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_controltower.type_defs import (
     ControlOperationTypeDef,
     DisableControlInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DisableControlOutputTypeDef,
     EnableControlInputRequestTypeDef,
+    EnableControlOutputTypeDef,
     EnabledControlSummaryTypeDef,
     GetControlOperationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListEnabledControlsInputListEnabledControlsPaginateTypeDef,
     ListEnabledControlsInputRequestTypeDef,
-    DisableControlOutputTypeDef,
-    EnableControlOutputTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     GetControlOperationOutputTypeDef,
     ListEnabledControlsOutputTypeDef,
-    ListEnabledControlsInputListEnabledControlsPaginateTypeDef,
 )
 
 
 def get_structure() -> ControlOperationTypeDef:
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

### Comparing `types-aiobotocore-controltower-2.5.0.post1/types_aiobotocore_controltower.egg-info/SOURCES.txt` & `types-aiobotocore-controltower-2.5.1/types_aiobotocore_controltower.egg-info/SOURCES.txt`

 * *Files identical despite different names*

