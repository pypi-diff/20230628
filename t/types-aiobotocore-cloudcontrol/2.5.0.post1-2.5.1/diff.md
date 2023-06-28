# Comparing `tmp/types-aiobotocore-cloudcontrol-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudcontrol-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudcontrol-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:19 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudcontrol-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1.tar` & `types-aiobotocore-cloudcontrol-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.831023 types-aiobotocore-cloudcontrol-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15193 2023-03-11 12:26:19.831023 types-aiobotocore-cloudcontrol-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13599 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:19.831023 types-aiobotocore-cloudcontrol-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2162 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.827023 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/
--rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1172 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12087 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12067 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9008 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9006 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3602 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3597 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9721 2023-03-11 12:10:38.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9706 2023-03-11 12:10:38.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1681 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1680 2023-03-11 12:10:37.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.831023 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15193 2023-03-11 12:26:19.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-03-11 12:26:19.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:19.000000 types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.210106 types-aiobotocore-cloudcontrol-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15190 2023-06-28 01:43:13.202107 types-aiobotocore-cloudcontrol-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13602 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.210106 types-aiobotocore-cloudcontrol-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.202107 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/
+-rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1172 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12087 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12067 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9217 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9215 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3486 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3482 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9741 2023-06-28 01:27:15.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9726 2023-06-28 01:27:15.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1681 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1680 2023-06-28 01:27:14.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.202107 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15190 2023-06-28 01:43:13.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-28 01:43:13.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:13.000000 types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudcontrol-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudcontrol-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudcontrol
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudControlApi 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudControlApi 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudcontrol"></a>
 
 # types-aiobotocore-cloudcontrol
 
 [![PyPI - types-aiobotocore-cloudcontrol](https://img.shields.io/pypi/v/types-aiobotocore-cloudcontrol.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudcontrol)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudcontrol.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudcontrol)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudcontrol?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudcontrol)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudControlApi 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
+[aiobotocore.CloudControlApi 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
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
 [types-aiobotocore-cloudcontrol docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/).
 
 See how it helps to find and fix potential bugs:
 
@@ -353,35 +353,35 @@
 `types_aiobotocore_cloudcontrol.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudcontrol.type_defs import (
     CancelResourceRequestInputRequestTypeDef,
     ProgressEventTypeDef,
-    ResponseMetadataTypeDef,
     CreateResourceInputRequestTypeDef,
     DeleteResourceInputRequestTypeDef,
     GetResourceInputRequestTypeDef,
     ResourceDescriptionTypeDef,
     GetResourceRequestStatusInputRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
     ResourceRequestStatusFilterTypeDef,
+    ListResourcesInputListResourcesPaginateTypeDef,
     ListResourcesInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateResourceInputRequestTypeDef,
     CancelResourceRequestOutputTypeDef,
     CreateResourceOutputTypeDef,
     DeleteResourceOutputTypeDef,
     GetResourceRequestStatusOutputTypeDef,
     ListResourceRequestsOutputTypeDef,
     UpdateResourceOutputTypeDef,
     GetResourceOutputTypeDef,
     ListResourcesOutputTypeDef,
     GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
-    ListResourcesInputListResourcesPaginateTypeDef,
     ListResourceRequestsInputListResourceRequestsPaginateTypeDef,
     ListResourceRequestsInputRequestTypeDef,
 )
 
 
 def get_structure() -> CancelResourceRequestInputRequestTypeDef:
     return {...}
@@ -390,43 +390,43 @@
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/README.md` & `types-aiobotocore-cloudcontrol-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudcontrol"></a>
 
 # types-aiobotocore-cloudcontrol
 
 [![PyPI - types-aiobotocore-cloudcontrol](https://img.shields.io/pypi/v/types-aiobotocore-cloudcontrol.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudcontrol)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudcontrol.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudcontrol)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudcontrol?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudcontrol)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudControlApi 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
+[aiobotocore.CloudControlApi 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
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
 [types-aiobotocore-cloudcontrol docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,35 +320,35 @@
 `types_aiobotocore_cloudcontrol.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudcontrol.type_defs import (
     CancelResourceRequestInputRequestTypeDef,
     ProgressEventTypeDef,
-    ResponseMetadataTypeDef,
     CreateResourceInputRequestTypeDef,
     DeleteResourceInputRequestTypeDef,
     GetResourceInputRequestTypeDef,
     ResourceDescriptionTypeDef,
     GetResourceRequestStatusInputRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
     ResourceRequestStatusFilterTypeDef,
+    ListResourcesInputListResourcesPaginateTypeDef,
     ListResourcesInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateResourceInputRequestTypeDef,
     CancelResourceRequestOutputTypeDef,
     CreateResourceOutputTypeDef,
     DeleteResourceOutputTypeDef,
     GetResourceRequestStatusOutputTypeDef,
     ListResourceRequestsOutputTypeDef,
     UpdateResourceOutputTypeDef,
     GetResourceOutputTypeDef,
     ListResourcesOutputTypeDef,
     GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
-    ListResourcesInputListResourcesPaginateTypeDef,
     ListResourceRequestsInputListResourceRequestsPaginateTypeDef,
     ListResourceRequestsInputRequestTypeDef,
 )
 
 
 def get_structure() -> CancelResourceRequestInputRequestTypeDef:
     return {...}
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/setup.py` & `types-aiobotocore-cloudcontrol-2.5.1/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudcontrol.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudcontrol",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudcontrol"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudControlApi 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudControlApi 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/"
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/__init__.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/__init__.pyi` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/__main__.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudControlApi 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudControlApi 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi\nOther"
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/client.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/client.pyi` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/literals.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -118,14 +118,15 @@
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
@@ -204,14 +205,15 @@
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
@@ -222,14 +224,15 @@
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
@@ -265,14 +268,15 @@
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
@@ -291,16 +295,19 @@
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
@@ -384,15 +391,17 @@
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/literals.pyi` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -116,14 +116,15 @@
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
@@ -202,14 +203,15 @@
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
@@ -220,14 +222,15 @@
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
@@ -263,14 +266,15 @@
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
@@ -289,16 +293,19 @@
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
@@ -382,15 +389,17 @@
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/paginator.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,33 +18,26 @@
     with session.create_client("cloudcontrol") as client:
         client: CloudControlApiClient
 
         list_resource_requests_paginator: ListResourceRequestsPaginator = client.get_paginator("list_resource_requests")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListResourceRequestsOutputTypeDef,
     ListResourcesOutputTypeDef,
     PaginatorConfigTypeDef,
     ResourceRequestStatusFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListResourceRequestsPaginator", "ListResourcesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -60,15 +53,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/paginators/#listresourcerequestspaginator)
     """
 
     def paginate(
         self,
         *,
         ResourceRequestStatusFilter: ResourceRequestStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceRequestsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi.Paginator.ListResourceRequests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/paginators/#listresourcerequestspaginator)
         """
 
 
@@ -81,13 +74,13 @@
     def paginate(
         self,
         *,
         TypeName: str,
         TypeVersionId: str = ...,
         RoleArn: str = ...,
         ResourceModel: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/paginators/#listresourcespaginator)
         """
```

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/paginator.pyi` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -18,32 +18,26 @@
     with session.create_client("cloudcontrol") as client:
         client: CloudControlApiClient
 
         list_resource_requests_paginator: ListResourceRequestsPaginator = client.get_paginator("list_resource_requests")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListResourceRequestsOutputTypeDef,
     ListResourcesOutputTypeDef,
     PaginatorConfigTypeDef,
     ResourceRequestStatusFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListResourceRequestsPaginator", "ListResourcesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -56,15 +50,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/paginators/#listresourcerequestspaginator)
     """
 
     def paginate(
         self,
         *,
         ResourceRequestStatusFilter: ResourceRequestStatusFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceRequestsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi.Paginator.ListResourceRequests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/paginators/#listresourcerequestspaginator)
         """
 
 class ListResourcesPaginator(AioPaginator):
@@ -76,13 +70,13 @@
     def paginate(
         self,
         *,
         TypeName: str,
         TypeVersionId: str = ...,
         RoleArn: str = ...,
         ResourceModel: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/paginators/#listresourcespaginator)
         """
```

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/type_defs.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -22,35 +22,35 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelResourceRequestInputRequestTypeDef",
     "ProgressEventTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateResourceInputRequestTypeDef",
     "DeleteResourceInputRequestTypeDef",
     "GetResourceInputRequestTypeDef",
     "ResourceDescriptionTypeDef",
     "GetResourceRequestStatusInputRequestTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
     "ResourceRequestStatusFilterTypeDef",
+    "ListResourcesInputListResourcesPaginateTypeDef",
     "ListResourcesInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateResourceInputRequestTypeDef",
     "CancelResourceRequestOutputTypeDef",
     "CreateResourceOutputTypeDef",
     "DeleteResourceOutputTypeDef",
     "GetResourceRequestStatusOutputTypeDef",
     "ListResourceRequestsOutputTypeDef",
     "UpdateResourceOutputTypeDef",
     "GetResourceOutputTypeDef",
     "ListResourcesOutputTypeDef",
     "GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef",
-    "ListResourcesInputListResourcesPaginateTypeDef",
     "ListResourceRequestsInputListResourceRequestsPaginateTypeDef",
     "ListResourceRequestsInputRequestTypeDef",
 )
 
 CancelResourceRequestInputRequestTypeDef = TypedDict(
     "CancelResourceRequestInputRequestTypeDef",
     {
@@ -71,25 +71,14 @@
         "StatusMessage": str,
         "ErrorCode": HandlerErrorCodeType,
         "RetryAfter": datetime,
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
 _RequiredCreateResourceInputRequestTypeDef = TypedDict(
     "_RequiredCreateResourceInputRequestTypeDef",
     {
         "TypeName": str,
         "DesiredState": str,
     },
 )
@@ -178,33 +167,48 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ResourceRequestStatusFilterTypeDef = TypedDict(
+    "ResourceRequestStatusFilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Operations": Sequence[OperationType],
+        "OperationStatuses": Sequence[OperationStatusType],
     },
     total=False,
 )
 
-ResourceRequestStatusFilterTypeDef = TypedDict(
-    "ResourceRequestStatusFilterTypeDef",
+_RequiredListResourcesInputListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesInputListResourcesPaginateTypeDef",
     {
-        "Operations": Sequence[OperationType],
-        "OperationStatuses": Sequence[OperationStatusType],
+        "TypeName": str,
+    },
+)
+_OptionalListResourcesInputListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesInputListResourcesPaginateTypeDef",
+    {
+        "TypeVersionId": str,
+        "RoleArn": str,
+        "ResourceModel": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListResourcesInputListResourcesPaginateTypeDef(
+    _RequiredListResourcesInputListResourcesPaginateTypeDef,
+    _OptionalListResourcesInputListResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListResourcesInputRequestTypeDef",
     {
         "TypeName": str,
     },
 )
 _OptionalListResourcesInputRequestTypeDef = TypedDict(
@@ -222,14 +226,35 @@
 
 class ListResourcesInputRequestTypeDef(
     _RequiredListResourcesInputRequestTypeDef, _OptionalListResourcesInputRequestTypeDef
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
 _RequiredUpdateResourceInputRequestTypeDef = TypedDict(
     "_RequiredUpdateResourceInputRequestTypeDef",
     {
         "TypeName": str,
         "Identifier": str,
         "PatchDocument": str,
     },
@@ -251,75 +276,75 @@
     pass
 
 
 CancelResourceRequestOutputTypeDef = TypedDict(
     "CancelResourceRequestOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResourceOutputTypeDef = TypedDict(
     "CreateResourceOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResourceOutputTypeDef = TypedDict(
     "DeleteResourceOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceRequestStatusOutputTypeDef = TypedDict(
     "GetResourceRequestStatusOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceRequestsOutputTypeDef = TypedDict(
     "ListResourceRequestsOutputTypeDef",
     {
         "ResourceRequestStatusSummaries": List[ProgressEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResourceOutputTypeDef = TypedDict(
     "UpdateResourceOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceOutputTypeDef = TypedDict(
     "GetResourceOutputTypeDef",
     {
         "TypeName": str,
         "ResourceDescription": ResourceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesOutputTypeDef = TypedDict(
     "ListResourcesOutputTypeDef",
     {
         "TypeName": str,
         "ResourceDescriptions": List[ResourceDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef = TypedDict(
     "_RequiredGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef",
     {
         "RequestToken": str,
@@ -337,44 +362,19 @@
 class GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef(
     _RequiredGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
     _OptionalGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
 ):
     pass
 
 
-_RequiredListResourcesInputListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesInputListResourcesPaginateTypeDef",
-    {
-        "TypeName": str,
-    },
-)
-_OptionalListResourcesInputListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesInputListResourcesPaginateTypeDef",
-    {
-        "TypeVersionId": str,
-        "RoleArn": str,
-        "ResourceModel": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourcesInputListResourcesPaginateTypeDef(
-    _RequiredListResourcesInputListResourcesPaginateTypeDef,
-    _OptionalListResourcesInputListResourcesPaginateTypeDef,
-):
-    pass
-
-
 ListResourceRequestsInputListResourceRequestsPaginateTypeDef = TypedDict(
     "ListResourceRequestsInputListResourceRequestsPaginateTypeDef",
     {
         "ResourceRequestStatusFilter": ResourceRequestStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListResourceRequestsInputRequestTypeDef = TypedDict(
     "ListResourceRequestsInputRequestTypeDef",
     {
```

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/type_defs.pyi` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -21,35 +21,35 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelResourceRequestInputRequestTypeDef",
     "ProgressEventTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateResourceInputRequestTypeDef",
     "DeleteResourceInputRequestTypeDef",
     "GetResourceInputRequestTypeDef",
     "ResourceDescriptionTypeDef",
     "GetResourceRequestStatusInputRequestTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
     "ResourceRequestStatusFilterTypeDef",
+    "ListResourcesInputListResourcesPaginateTypeDef",
     "ListResourcesInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateResourceInputRequestTypeDef",
     "CancelResourceRequestOutputTypeDef",
     "CreateResourceOutputTypeDef",
     "DeleteResourceOutputTypeDef",
     "GetResourceRequestStatusOutputTypeDef",
     "ListResourceRequestsOutputTypeDef",
     "UpdateResourceOutputTypeDef",
     "GetResourceOutputTypeDef",
     "ListResourcesOutputTypeDef",
     "GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef",
-    "ListResourcesInputListResourcesPaginateTypeDef",
     "ListResourceRequestsInputListResourceRequestsPaginateTypeDef",
     "ListResourceRequestsInputRequestTypeDef",
 )
 
 CancelResourceRequestInputRequestTypeDef = TypedDict(
     "CancelResourceRequestInputRequestTypeDef",
     {
@@ -70,25 +70,14 @@
         "StatusMessage": str,
         "ErrorCode": HandlerErrorCodeType,
         "RetryAfter": datetime,
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
 _RequiredCreateResourceInputRequestTypeDef = TypedDict(
     "_RequiredCreateResourceInputRequestTypeDef",
     {
         "TypeName": str,
         "DesiredState": str,
     },
 )
@@ -171,33 +160,46 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ResourceRequestStatusFilterTypeDef = TypedDict(
+    "ResourceRequestStatusFilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Operations": Sequence[OperationType],
+        "OperationStatuses": Sequence[OperationStatusType],
     },
     total=False,
 )
 
-ResourceRequestStatusFilterTypeDef = TypedDict(
-    "ResourceRequestStatusFilterTypeDef",
+_RequiredListResourcesInputListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesInputListResourcesPaginateTypeDef",
     {
-        "Operations": Sequence[OperationType],
-        "OperationStatuses": Sequence[OperationStatusType],
+        "TypeName": str,
+    },
+)
+_OptionalListResourcesInputListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesInputListResourcesPaginateTypeDef",
+    {
+        "TypeVersionId": str,
+        "RoleArn": str,
+        "ResourceModel": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListResourcesInputListResourcesPaginateTypeDef(
+    _RequiredListResourcesInputListResourcesPaginateTypeDef,
+    _OptionalListResourcesInputListResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListResourcesInputRequestTypeDef",
     {
         "TypeName": str,
     },
 )
 _OptionalListResourcesInputRequestTypeDef = TypedDict(
@@ -213,14 +215,35 @@
 )
 
 class ListResourcesInputRequestTypeDef(
     _RequiredListResourcesInputRequestTypeDef, _OptionalListResourcesInputRequestTypeDef
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
 _RequiredUpdateResourceInputRequestTypeDef = TypedDict(
     "_RequiredUpdateResourceInputRequestTypeDef",
     {
         "TypeName": str,
         "Identifier": str,
         "PatchDocument": str,
     },
@@ -240,75 +263,75 @@
 ):
     pass
 
 CancelResourceRequestOutputTypeDef = TypedDict(
     "CancelResourceRequestOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResourceOutputTypeDef = TypedDict(
     "CreateResourceOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteResourceOutputTypeDef = TypedDict(
     "DeleteResourceOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceRequestStatusOutputTypeDef = TypedDict(
     "GetResourceRequestStatusOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceRequestsOutputTypeDef = TypedDict(
     "ListResourceRequestsOutputTypeDef",
     {
         "ResourceRequestStatusSummaries": List[ProgressEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResourceOutputTypeDef = TypedDict(
     "UpdateResourceOutputTypeDef",
     {
         "ProgressEvent": ProgressEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceOutputTypeDef = TypedDict(
     "GetResourceOutputTypeDef",
     {
         "TypeName": str,
         "ResourceDescription": ResourceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesOutputTypeDef = TypedDict(
     "ListResourcesOutputTypeDef",
     {
         "TypeName": str,
         "ResourceDescriptions": List[ResourceDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef = TypedDict(
     "_RequiredGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef",
     {
         "RequestToken": str,
@@ -324,42 +347,19 @@
 
 class GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef(
     _RequiredGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
     _OptionalGetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
 ):
     pass
 
-_RequiredListResourcesInputListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesInputListResourcesPaginateTypeDef",
-    {
-        "TypeName": str,
-    },
-)
-_OptionalListResourcesInputListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesInputListResourcesPaginateTypeDef",
-    {
-        "TypeVersionId": str,
-        "RoleArn": str,
-        "ResourceModel": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResourcesInputListResourcesPaginateTypeDef(
-    _RequiredListResourcesInputListResourcesPaginateTypeDef,
-    _OptionalListResourcesInputListResourcesPaginateTypeDef,
-):
-    pass
-
 ListResourceRequestsInputListResourceRequestsPaginateTypeDef = TypedDict(
     "ListResourceRequestsInputListResourceRequestsPaginateTypeDef",
     {
         "ResourceRequestStatusFilter": ResourceRequestStatusFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListResourceRequestsInputRequestTypeDef = TypedDict(
     "ListResourceRequestsInputRequestTypeDef",
     {
```

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/waiter.py` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol/waiter.pyi` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/PKG-INFO` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudcontrol
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudControlApi 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudControlApi 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudcontrol"></a>
 
 # types-aiobotocore-cloudcontrol
 
 [![PyPI - types-aiobotocore-cloudcontrol](https://img.shields.io/pypi/v/types-aiobotocore-cloudcontrol.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudcontrol)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudcontrol.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudcontrol)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudcontrol?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudcontrol)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudControlApi 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
+[aiobotocore.CloudControlApi 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudcontrol.html#CloudControlApi)
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
 [types-aiobotocore-cloudcontrol docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudcontrol/).
 
 See how it helps to find and fix potential bugs:
 
@@ -353,35 +353,35 @@
 `types_aiobotocore_cloudcontrol.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudcontrol.type_defs import (
     CancelResourceRequestInputRequestTypeDef,
     ProgressEventTypeDef,
-    ResponseMetadataTypeDef,
     CreateResourceInputRequestTypeDef,
     DeleteResourceInputRequestTypeDef,
     GetResourceInputRequestTypeDef,
     ResourceDescriptionTypeDef,
     GetResourceRequestStatusInputRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
     ResourceRequestStatusFilterTypeDef,
+    ListResourcesInputListResourcesPaginateTypeDef,
     ListResourcesInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateResourceInputRequestTypeDef,
     CancelResourceRequestOutputTypeDef,
     CreateResourceOutputTypeDef,
     DeleteResourceOutputTypeDef,
     GetResourceRequestStatusOutputTypeDef,
     ListResourceRequestsOutputTypeDef,
     UpdateResourceOutputTypeDef,
     GetResourceOutputTypeDef,
     ListResourcesOutputTypeDef,
     GetResourceRequestStatusInputResourceRequestSuccessWaitTypeDef,
-    ListResourcesInputListResourcesPaginateTypeDef,
     ListResourceRequestsInputListResourceRequestsPaginateTypeDef,
     ListResourceRequestsInputRequestTypeDef,
 )
 
 
 def get_structure() -> CancelResourceRequestInputRequestTypeDef:
     return {...}
@@ -390,43 +390,43 @@
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

### Comparing `types-aiobotocore-cloudcontrol-2.5.0.post1/types_aiobotocore_cloudcontrol.egg-info/SOURCES.txt` & `types-aiobotocore-cloudcontrol-2.5.1/types_aiobotocore_cloudcontrol.egg-info/SOURCES.txt`

 * *Files identical despite different names*
