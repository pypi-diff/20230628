# Comparing `tmp/types-aiobotocore-iot-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iot-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iot-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-iot-data-2.5.1.tar", last modified: Wed Jun 28 01:43:36 2023, max compression
```

## Comparing `types-aiobotocore-iot-data-2.5.0.post1.tar` & `types-aiobotocore-iot-data-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.619276 types-aiobotocore-iot-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13726 2023-03-11 12:26:44.615276 types-aiobotocore-iot-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12147 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.619276 types-aiobotocore-iot-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2135 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.611276 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/
--rw-r--r--   0 runner    (1001) docker     (123)      713 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      712 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9600 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9583 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8054 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8052 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2202 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6880 2023-03-11 12:16:10.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6869 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:09.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.615276 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13726 2023-03-11 12:26:44.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:26:44.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:44.000000 types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.434150 types-aiobotocore-iot-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13719 2023-06-28 01:43:36.434150 types-aiobotocore-iot-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12146 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:36.434150 types-aiobotocore-iot-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2129 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.434150 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/
+-rw-r--r--   0 runner    (1001) docker     (123)      713 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      712 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9600 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9583 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8263 2023-06-28 01:32:48.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8261 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2084 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2081 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6929 2023-06-28 01:32:48.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6918 2023-06-28 01:32:48.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:47.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.434150 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13719 2023-06-28 01:43:36.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:36.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:36.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:36.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:36.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:36.000000 types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/LICENSE` & `types-aiobotocore-iot-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iot-data-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTDataPlane 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTDataPlane 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot-data"></a>
 
 # types-aiobotocore-iot-data
 
 [![PyPI - types-aiobotocore-iot-data](https://img.shields.io/pypi/v/types-aiobotocore-iot-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTDataPlane 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
+[aiobotocore.IoTDataPlane 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
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
 [types-aiobotocore-iot-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,30 +318,30 @@
 
 `types_aiobotocore_iot_data.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_data.type_defs import (
     DeleteThingShadowRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteThingShadowResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRetainedMessageRequestRequestTypeDef,
+    GetRetainedMessageResponseTypeDef,
     GetThingShadowRequestRequestTypeDef,
+    GetThingShadowResponseTypeDef,
     ListNamedShadowsForThingRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListNamedShadowsForThingResponseTypeDef,
+    ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef,
     ListRetainedMessagesRequestRequestTypeDef,
     RetainedMessageSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PublishRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UpdateThingShadowRequestRequestTypeDef,
-    DeleteThingShadowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetRetainedMessageResponseTypeDef,
-    GetThingShadowResponseTypeDef,
-    ListNamedShadowsForThingResponseTypeDef,
     UpdateThingShadowResponseTypeDef,
-    ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef,
     ListRetainedMessagesResponseTypeDef,
 )
 
 
 def get_structure() -> DeleteThingShadowRequestRequestTypeDef:
     return {...}
 ```
@@ -349,43 +349,43 @@
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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/README.md` & `types-aiobotocore-iot-data-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iot-data"></a>
 
 # types-aiobotocore-iot-data
 
 [![PyPI - types-aiobotocore-iot-data](https://img.shields.io/pypi/v/types-aiobotocore-iot-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTDataPlane 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
+[aiobotocore.IoTDataPlane 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
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
 [types-aiobotocore-iot-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -285,30 +285,30 @@
 
 `types_aiobotocore_iot_data.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_data.type_defs import (
     DeleteThingShadowRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteThingShadowResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRetainedMessageRequestRequestTypeDef,
+    GetRetainedMessageResponseTypeDef,
     GetThingShadowRequestRequestTypeDef,
+    GetThingShadowResponseTypeDef,
     ListNamedShadowsForThingRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListNamedShadowsForThingResponseTypeDef,
+    ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef,
     ListRetainedMessagesRequestRequestTypeDef,
     RetainedMessageSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PublishRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UpdateThingShadowRequestRequestTypeDef,
-    DeleteThingShadowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetRetainedMessageResponseTypeDef,
-    GetThingShadowResponseTypeDef,
-    ListNamedShadowsForThingResponseTypeDef,
     UpdateThingShadowResponseTypeDef,
-    ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef,
     ListRetainedMessagesResponseTypeDef,
 )
 
 
 def get_structure() -> DeleteThingShadowRequestRequestTypeDef:
     return {...}
 ```
@@ -316,43 +316,43 @@
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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/setup.py` & `types-aiobotocore-iot-data-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iot-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iot-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iot_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTDataPlane 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTDataPlane 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/"
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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/__init__.py` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/__init__.pyi` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/__main__.py` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTDataPlane 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTDataPlane 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane\nOther"
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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/client.py` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/client.pyi` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/literals.py` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/literals.py`

 * *Files 2% similar despite different names*

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
```

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/literals.pyi` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -89,14 +89,15 @@
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
@@ -175,14 +176,15 @@
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
@@ -193,14 +195,15 @@
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
@@ -236,14 +239,15 @@
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
@@ -262,16 +266,19 @@
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
@@ -355,15 +362,17 @@
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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/paginator.py` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/paginator.py`

 * *Files 7% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("iot-data") as client:
         client: IoTDataPlaneClient
 
         list_retained_messages_paginator: ListRetainedMessagesPaginator = client.get_paginator("list_retained_messages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListRetainedMessagesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListRetainedMessagesPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListRetainedMessagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane.Paginator.ListRetainedMessages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/paginators/#listretainedmessagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRetainedMessagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane.Paginator.ListRetainedMessages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/paginators/#listretainedmessagespaginator)
         """
```

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/paginator.pyi` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/paginator.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("iot-data") as client:
         client: IoTDataPlaneClient
 
         list_retained_messages_paginator: ListRetainedMessagesPaginator = client.get_paginator("list_retained_messages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListRetainedMessagesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListRetainedMessagesPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListRetainedMessagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane.Paginator.ListRetainedMessages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/paginators/#listretainedmessagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRetainedMessagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane.Paginator.ListRetainedMessages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/paginators/#listretainedmessagespaginator)
         """
```

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/type_defs.py` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/type_defs.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -19,33 +19,32 @@
 from .literals import PayloadFormatIndicatorType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "DeleteThingShadowRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteThingShadowResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetRetainedMessageRequestRequestTypeDef",
+    "GetRetainedMessageResponseTypeDef",
     "GetThingShadowRequestRequestTypeDef",
+    "GetThingShadowResponseTypeDef",
     "ListNamedShadowsForThingRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListNamedShadowsForThingResponseTypeDef",
+    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
     "ListRetainedMessagesRequestRequestTypeDef",
     "RetainedMessageSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "PublishRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateThingShadowRequestRequestTypeDef",
-    "DeleteThingShadowResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetRetainedMessageResponseTypeDef",
-    "GetThingShadowResponseTypeDef",
-    "ListNamedShadowsForThingResponseTypeDef",
     "UpdateThingShadowResponseTypeDef",
-    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
     "ListRetainedMessagesResponseTypeDef",
 )
 
 _RequiredDeleteThingShadowRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteThingShadowRequestRequestTypeDef",
     {
         "thingName": str,
@@ -55,59 +54,79 @@
     "_OptionalDeleteThingShadowRequestRequestTypeDef",
     {
         "shadowName": str,
     },
     total=False,
 )
 
-
 class DeleteThingShadowRequestRequestTypeDef(
     _RequiredDeleteThingShadowRequestRequestTypeDef, _OptionalDeleteThingShadowRequestRequestTypeDef
 ):
     pass
 
+DeleteThingShadowResponseTypeDef = TypedDict(
+    "DeleteThingShadowResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRetainedMessageRequestRequestTypeDef = TypedDict(
     "GetRetainedMessageRequestRequestTypeDef",
     {
         "topic": str,
     },
 )
 
+GetRetainedMessageResponseTypeDef = TypedDict(
+    "GetRetainedMessageResponseTypeDef",
+    {
+        "topic": str,
+        "payload": bytes,
+        "qos": int,
+        "lastModifiedTime": int,
+        "userProperties": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetThingShadowRequestRequestTypeDef = TypedDict(
     "_RequiredGetThingShadowRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalGetThingShadowRequestRequestTypeDef = TypedDict(
     "_OptionalGetThingShadowRequestRequestTypeDef",
     {
         "shadowName": str,
     },
     total=False,
 )
 
-
 class GetThingShadowRequestRequestTypeDef(
     _RequiredGetThingShadowRequestRequestTypeDef, _OptionalGetThingShadowRequestRequestTypeDef
 ):
     pass
 
+GetThingShadowResponseTypeDef = TypedDict(
+    "GetThingShadowResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredListNamedShadowsForThingRequestRequestTypeDef = TypedDict(
     "_RequiredListNamedShadowsForThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
@@ -116,28 +135,34 @@
     {
         "nextToken": str,
         "pageSize": int,
     },
     total=False,
 )
 
-
 class ListNamedShadowsForThingRequestRequestTypeDef(
     _RequiredListNamedShadowsForThingRequestRequestTypeDef,
     _OptionalListNamedShadowsForThingRequestRequestTypeDef,
 ):
     pass
 
+ListNamedShadowsForThingResponseTypeDef = TypedDict(
+    "ListNamedShadowsForThingResponseTypeDef",
+    {
+        "results": List[str],
+        "nextToken": str,
+        "timestamp": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef = TypedDict(
+    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRetainedMessagesRequestRequestTypeDef = TypedDict(
     "ListRetainedMessagesRequestRequestTypeDef",
     {
@@ -154,14 +179,24 @@
         "payloadSize": int,
         "qos": int,
         "lastModifiedTime": int,
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
 _RequiredPublishRequestRequestTypeDef = TypedDict(
     "_RequiredPublishRequestRequestTypeDef",
     {
         "topic": str,
     },
 )
 _OptionalPublishRequestRequestTypeDef = TypedDict(
@@ -176,20 +211,29 @@
         "responseTopic": str,
         "correlationData": str,
         "messageExpiry": int,
     },
     total=False,
 )
 
-
 class PublishRequestRequestTypeDef(
     _RequiredPublishRequestRequestTypeDef, _OptionalPublishRequestRequestTypeDef
 ):
     pass
 
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
 
 _RequiredUpdateThingShadowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateThingShadowRequestRequestTypeDef",
     {
         "thingName": str,
         "payload": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -198,82 +242,28 @@
     "_OptionalUpdateThingShadowRequestRequestTypeDef",
     {
         "shadowName": str,
     },
     total=False,
 )
 
-
 class UpdateThingShadowRequestRequestTypeDef(
     _RequiredUpdateThingShadowRequestRequestTypeDef, _OptionalUpdateThingShadowRequestRequestTypeDef
 ):
     pass
 
-
-DeleteThingShadowResponseTypeDef = TypedDict(
-    "DeleteThingShadowResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRetainedMessageResponseTypeDef = TypedDict(
-    "GetRetainedMessageResponseTypeDef",
-    {
-        "topic": str,
-        "payload": bytes,
-        "qos": int,
-        "lastModifiedTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetThingShadowResponseTypeDef = TypedDict(
-    "GetThingShadowResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListNamedShadowsForThingResponseTypeDef = TypedDict(
-    "ListNamedShadowsForThingResponseTypeDef",
-    {
-        "results": List[str],
-        "nextToken": str,
-        "timestamp": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateThingShadowResponseTypeDef = TypedDict(
     "UpdateThingShadowResponseTypeDef",
     {
         "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef = TypedDict(
-    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListRetainedMessagesResponseTypeDef = TypedDict(
     "ListRetainedMessagesResponseTypeDef",
     {
         "retainedTopics": List[RetainedMessageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data/type_defs.pyi` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -19,32 +19,33 @@
 from .literals import PayloadFormatIndicatorType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "DeleteThingShadowRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteThingShadowResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetRetainedMessageRequestRequestTypeDef",
+    "GetRetainedMessageResponseTypeDef",
     "GetThingShadowRequestRequestTypeDef",
+    "GetThingShadowResponseTypeDef",
     "ListNamedShadowsForThingRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListNamedShadowsForThingResponseTypeDef",
+    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
     "ListRetainedMessagesRequestRequestTypeDef",
     "RetainedMessageSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "PublishRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateThingShadowRequestRequestTypeDef",
-    "DeleteThingShadowResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetRetainedMessageResponseTypeDef",
-    "GetThingShadowResponseTypeDef",
-    "ListNamedShadowsForThingResponseTypeDef",
     "UpdateThingShadowResponseTypeDef",
-    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
     "ListRetainedMessagesResponseTypeDef",
 )
 
 _RequiredDeleteThingShadowRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteThingShadowRequestRequestTypeDef",
     {
         "thingName": str,
@@ -54,56 +55,84 @@
     "_OptionalDeleteThingShadowRequestRequestTypeDef",
     {
         "shadowName": str,
     },
     total=False,
 )
 
+
 class DeleteThingShadowRequestRequestTypeDef(
     _RequiredDeleteThingShadowRequestRequestTypeDef, _OptionalDeleteThingShadowRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+DeleteThingShadowResponseTypeDef = TypedDict(
+    "DeleteThingShadowResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRetainedMessageRequestRequestTypeDef = TypedDict(
     "GetRetainedMessageRequestRequestTypeDef",
     {
         "topic": str,
     },
 )
 
+GetRetainedMessageResponseTypeDef = TypedDict(
+    "GetRetainedMessageResponseTypeDef",
+    {
+        "topic": str,
+        "payload": bytes,
+        "qos": int,
+        "lastModifiedTime": int,
+        "userProperties": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetThingShadowRequestRequestTypeDef = TypedDict(
     "_RequiredGetThingShadowRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalGetThingShadowRequestRequestTypeDef = TypedDict(
     "_OptionalGetThingShadowRequestRequestTypeDef",
     {
         "shadowName": str,
     },
     total=False,
 )
 
+
 class GetThingShadowRequestRequestTypeDef(
     _RequiredGetThingShadowRequestRequestTypeDef, _OptionalGetThingShadowRequestRequestTypeDef
 ):
     pass
 
+
+GetThingShadowResponseTypeDef = TypedDict(
+    "GetThingShadowResponseTypeDef",
+    {
+        "payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListNamedShadowsForThingRequestRequestTypeDef = TypedDict(
     "_RequiredListNamedShadowsForThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListNamedShadowsForThingRequestRequestTypeDef = TypedDict(
@@ -111,26 +140,36 @@
     {
         "nextToken": str,
         "pageSize": int,
     },
     total=False,
 )
 
+
 class ListNamedShadowsForThingRequestRequestTypeDef(
     _RequiredListNamedShadowsForThingRequestRequestTypeDef,
     _OptionalListNamedShadowsForThingRequestRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+ListNamedShadowsForThingResponseTypeDef = TypedDict(
+    "ListNamedShadowsForThingResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "results": List[str],
+        "nextToken": str,
+        "timestamp": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef = TypedDict(
+    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRetainedMessagesRequestRequestTypeDef = TypedDict(
     "ListRetainedMessagesRequestRequestTypeDef",
     {
@@ -147,14 +186,24 @@
         "payloadSize": int,
         "qos": int,
         "lastModifiedTime": int,
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
 _RequiredPublishRequestRequestTypeDef = TypedDict(
     "_RequiredPublishRequestRequestTypeDef",
     {
         "topic": str,
     },
 )
 _OptionalPublishRequestRequestTypeDef = TypedDict(
@@ -169,19 +218,32 @@
         "responseTopic": str,
         "correlationData": str,
         "messageExpiry": int,
     },
     total=False,
 )
 
+
 class PublishRequestRequestTypeDef(
     _RequiredPublishRequestRequestTypeDef, _OptionalPublishRequestRequestTypeDef
 ):
     pass
 
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
 _RequiredUpdateThingShadowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateThingShadowRequestRequestTypeDef",
     {
         "thingName": str,
         "payload": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
@@ -189,80 +251,30 @@
     "_OptionalUpdateThingShadowRequestRequestTypeDef",
     {
         "shadowName": str,
     },
     total=False,
 )
 
+
 class UpdateThingShadowRequestRequestTypeDef(
     _RequiredUpdateThingShadowRequestRequestTypeDef, _OptionalUpdateThingShadowRequestRequestTypeDef
 ):
     pass
 
-DeleteThingShadowResponseTypeDef = TypedDict(
-    "DeleteThingShadowResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRetainedMessageResponseTypeDef = TypedDict(
-    "GetRetainedMessageResponseTypeDef",
-    {
-        "topic": str,
-        "payload": bytes,
-        "qos": int,
-        "lastModifiedTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetThingShadowResponseTypeDef = TypedDict(
-    "GetThingShadowResponseTypeDef",
-    {
-        "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListNamedShadowsForThingResponseTypeDef = TypedDict(
-    "ListNamedShadowsForThingResponseTypeDef",
-    {
-        "results": List[str],
-        "nextToken": str,
-        "timestamp": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 UpdateThingShadowResponseTypeDef = TypedDict(
     "UpdateThingShadowResponseTypeDef",
     {
         "payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef = TypedDict(
-    "ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListRetainedMessagesResponseTypeDef = TypedDict(
     "ListRetainedMessagesResponseTypeDef",
     {
         "retainedTopics": List[RetainedMessageSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/PKG-INFO` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTDataPlane 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTDataPlane 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot-data"></a>
 
 # types-aiobotocore-iot-data
 
 [![PyPI - types-aiobotocore-iot-data](https://img.shields.io/pypi/v/types-aiobotocore-iot-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTDataPlane 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
+[aiobotocore.IoTDataPlane 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-data.html#IoTDataPlane)
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
 [types-aiobotocore-iot-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,30 +318,30 @@
 
 `types_aiobotocore_iot_data.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_data.type_defs import (
     DeleteThingShadowRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteThingShadowResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRetainedMessageRequestRequestTypeDef,
+    GetRetainedMessageResponseTypeDef,
     GetThingShadowRequestRequestTypeDef,
+    GetThingShadowResponseTypeDef,
     ListNamedShadowsForThingRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListNamedShadowsForThingResponseTypeDef,
+    ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef,
     ListRetainedMessagesRequestRequestTypeDef,
     RetainedMessageSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PublishRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UpdateThingShadowRequestRequestTypeDef,
-    DeleteThingShadowResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetRetainedMessageResponseTypeDef,
-    GetThingShadowResponseTypeDef,
-    ListNamedShadowsForThingResponseTypeDef,
     UpdateThingShadowResponseTypeDef,
-    ListRetainedMessagesRequestListRetainedMessagesPaginateTypeDef,
     ListRetainedMessagesResponseTypeDef,
 )
 
 
 def get_structure() -> DeleteThingShadowRequestRequestTypeDef:
     return {...}
 ```
@@ -349,43 +349,43 @@
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

### Comparing `types-aiobotocore-iot-data-2.5.0.post1/types_aiobotocore_iot_data.egg-info/SOURCES.txt` & `types-aiobotocore-iot-data-2.5.1/types_aiobotocore_iot_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

