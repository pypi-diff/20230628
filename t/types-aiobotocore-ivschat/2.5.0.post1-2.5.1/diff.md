# Comparing `tmp/types-aiobotocore-ivschat-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ivschat-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ivschat-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:49 2023, max compression
+gzip compressed data, was "types-aiobotocore-ivschat-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-ivschat-2.5.0.post1.tar` & `types-aiobotocore-ivschat-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.123321 types-aiobotocore-ivschat-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13722 2023-03-11 12:26:49.123321 types-aiobotocore-ivschat-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12151 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:49.123321 types-aiobotocore-ivschat-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:16:41.000000 types-aiobotocore-ivschat-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.123321 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/
--rw-r--r--   0 runner    (1001) docker     (123)      442 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      441 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14863 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14838 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8071 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8069 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    14341 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    14326 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:42.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.123321 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13722 2023-03-11 12:26:48.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      734 2023-03-11 12:26:48.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:48.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:48.000000 types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.666158 types-aiobotocore-ivschat-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13714 2023-06-28 01:43:40.666158 types-aiobotocore-ivschat-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12149 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.666158 types-aiobotocore-ivschat-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:33:20.000000 types-aiobotocore-ivschat-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.666158 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/
+-rw-r--r--   0 runner    (1001) docker     (123)      442 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      441 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14863 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14838 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8280 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8278 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14367 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14352 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:21.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.666158 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13714 2023-06-28 01:43:40.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      734 2023-06-28 01:43:40.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:40.000000 types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/LICENSE` & `types-aiobotocore-ivschat-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ivschat-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ivschat
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ivschat 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ivschat 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ivschat"></a>
 
 # types-aiobotocore-ivschat
 
 [![PyPI - types-aiobotocore-ivschat](https://img.shields.io/pypi/v/types-aiobotocore-ivschat.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivschat)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ivschat.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivschat)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ivschat?color=blue)](https://pypistats.org/packages/types-aiobotocore-ivschat)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ivschat 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat)
+[aiobotocore.ivschat 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat)
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
 [types-aiobotocore-ivschat docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,35 +295,35 @@
 `types_aiobotocore_ivschat.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ivschat.type_defs import (
     CloudWatchLogsDestinationConfigurationTypeDef,
     CreateChatTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateChatTokenResponseTypeDef,
     MessageReviewHandlerTypeDef,
     DeleteLoggingConfigurationRequestRequestTypeDef,
     DeleteMessageRequestRequestTypeDef,
+    DeleteMessageResponseTypeDef,
     DeleteRoomRequestRequestTypeDef,
     FirehoseDestinationConfigurationTypeDef,
     S3DestinationConfigurationTypeDef,
     DisconnectUserRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetLoggingConfigurationRequestRequestTypeDef,
     GetRoomRequestRequestTypeDef,
     ListLoggingConfigurationsRequestRequestTypeDef,
     ListRoomsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     SendEventRequestRequestTypeDef,
+    SendEventResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateChatTokenResponseTypeDef,
-    DeleteMessageResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendEventResponseTypeDef,
     CreateRoomRequestRequestTypeDef,
     CreateRoomResponseTypeDef,
     GetRoomResponseTypeDef,
     RoomSummaryTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateRoomResponseTypeDef,
     DestinationConfigurationTypeDef,
@@ -345,43 +345,43 @@
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/README.md` & `types-aiobotocore-ivschat-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ivschat"></a>
 
 # types-aiobotocore-ivschat
 
 [![PyPI - types-aiobotocore-ivschat](https://img.shields.io/pypi/v/types-aiobotocore-ivschat.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivschat)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ivschat.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivschat)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ivschat?color=blue)](https://pypistats.org/packages/types-aiobotocore-ivschat)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ivschat 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat)
+[aiobotocore.ivschat 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat)
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
 [types-aiobotocore-ivschat docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/).
 
 See how it helps to find and fix potential bugs:
 
@@ -262,35 +262,35 @@
 `types_aiobotocore_ivschat.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ivschat.type_defs import (
     CloudWatchLogsDestinationConfigurationTypeDef,
     CreateChatTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateChatTokenResponseTypeDef,
     MessageReviewHandlerTypeDef,
     DeleteLoggingConfigurationRequestRequestTypeDef,
     DeleteMessageRequestRequestTypeDef,
+    DeleteMessageResponseTypeDef,
     DeleteRoomRequestRequestTypeDef,
     FirehoseDestinationConfigurationTypeDef,
     S3DestinationConfigurationTypeDef,
     DisconnectUserRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetLoggingConfigurationRequestRequestTypeDef,
     GetRoomRequestRequestTypeDef,
     ListLoggingConfigurationsRequestRequestTypeDef,
     ListRoomsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     SendEventRequestRequestTypeDef,
+    SendEventResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateChatTokenResponseTypeDef,
-    DeleteMessageResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendEventResponseTypeDef,
     CreateRoomRequestRequestTypeDef,
     CreateRoomResponseTypeDef,
     GetRoomResponseTypeDef,
     RoomSummaryTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateRoomResponseTypeDef,
     DestinationConfigurationTypeDef,
@@ -312,43 +312,43 @@
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/setup.py` & `types-aiobotocore-ivschat-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ivschat.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ivschat",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ivschat"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ivschat 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.ivschat 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/"
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/__main__.py` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ivschat 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ivschat 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat\nOther"
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/client.py` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/client.pyi` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/literals.py` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -98,14 +98,15 @@
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
@@ -184,14 +185,15 @@
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
@@ -202,14 +204,15 @@
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
@@ -245,14 +248,15 @@
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
@@ -271,16 +275,19 @@
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
@@ -364,15 +371,17 @@
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/literals.pyi` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -96,14 +96,15 @@
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
@@ -182,14 +183,15 @@
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
@@ -200,14 +202,15 @@
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
@@ -243,14 +246,15 @@
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
@@ -269,16 +273,19 @@
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
@@ -362,15 +369,17 @@
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/type_defs.py` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -26,35 +26,35 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CloudWatchLogsDestinationConfigurationTypeDef",
     "CreateChatTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateChatTokenResponseTypeDef",
     "MessageReviewHandlerTypeDef",
     "DeleteLoggingConfigurationRequestRequestTypeDef",
     "DeleteMessageRequestRequestTypeDef",
+    "DeleteMessageResponseTypeDef",
     "DeleteRoomRequestRequestTypeDef",
     "FirehoseDestinationConfigurationTypeDef",
     "S3DestinationConfigurationTypeDef",
     "DisconnectUserRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetLoggingConfigurationRequestRequestTypeDef",
     "GetRoomRequestRequestTypeDef",
     "ListLoggingConfigurationsRequestRequestTypeDef",
     "ListRoomsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SendEventRequestRequestTypeDef",
+    "SendEventResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CreateChatTokenResponseTypeDef",
-    "DeleteMessageResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SendEventResponseTypeDef",
     "CreateRoomRequestRequestTypeDef",
     "CreateRoomResponseTypeDef",
     "GetRoomResponseTypeDef",
     "RoomSummaryTypeDef",
     "UpdateRoomRequestRequestTypeDef",
     "UpdateRoomResponseTypeDef",
     "DestinationConfigurationTypeDef",
@@ -95,22 +95,21 @@
 
 class CreateChatTokenRequestRequestTypeDef(
     _RequiredCreateChatTokenRequestRequestTypeDef, _OptionalCreateChatTokenRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateChatTokenResponseTypeDef = TypedDict(
+    "CreateChatTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "sessionExpirationTime": datetime,
+        "token": str,
+        "tokenExpirationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MessageReviewHandlerTypeDef = TypedDict(
     "MessageReviewHandlerTypeDef",
     {
         "fallbackResult": FallbackResultType,
@@ -144,14 +143,22 @@
 
 class DeleteMessageRequestRequestTypeDef(
     _RequiredDeleteMessageRequestRequestTypeDef, _OptionalDeleteMessageRequestRequestTypeDef
 ):
     pass
 
 
+DeleteMessageResponseTypeDef = TypedDict(
+    "DeleteMessageResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteRoomRequestRequestTypeDef = TypedDict(
     "DeleteRoomRequestRequestTypeDef",
     {
         "identifier": str,
     },
 )
 
@@ -187,14 +194,21 @@
 
 class DisconnectUserRequestRequestTypeDef(
     _RequiredDisconnectUserRequestRequestTypeDef, _OptionalDisconnectUserRequestRequestTypeDef
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "GetLoggingConfigurationRequestRequestTypeDef",
     {
         "identifier": str,
     },
 )
 
@@ -229,14 +243,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
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
 _RequiredSendEventRequestRequestTypeDef = TypedDict(
     "_RequiredSendEventRequestRequestTypeDef",
     {
         "eventName": str,
         "roomIdentifier": str,
     },
 )
@@ -251,14 +284,22 @@
 
 class SendEventRequestRequestTypeDef(
     _RequiredSendEventRequestRequestTypeDef, _OptionalSendEventRequestRequestTypeDef
 ):
     pass
 
 
+SendEventResponseTypeDef = TypedDict(
+    "SendEventResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -267,55 +308,14 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-CreateChatTokenResponseTypeDef = TypedDict(
-    "CreateChatTokenResponseTypeDef",
-    {
-        "sessionExpirationTime": datetime,
-        "token": str,
-        "tokenExpirationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMessageResponseTypeDef = TypedDict(
-    "DeleteMessageResponseTypeDef",
-    {
-        "id": str,
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEventResponseTypeDef = TypedDict(
-    "SendEventResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateRoomRequestRequestTypeDef = TypedDict(
     "CreateRoomRequestRequestTypeDef",
     {
         "loggingConfigurationIdentifiers": Sequence[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
@@ -334,15 +334,15 @@
         "loggingConfigurationIdentifiers": List[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
         "name": str,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoomResponseTypeDef = TypedDict(
     "GetRoomResponseTypeDef",
     {
         "arn": str,
@@ -351,15 +351,15 @@
         "loggingConfigurationIdentifiers": List[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
         "name": str,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RoomSummaryTypeDef = TypedDict(
     "RoomSummaryTypeDef",
     {
         "arn": str,
@@ -408,15 +408,15 @@
         "loggingConfigurationIdentifiers": List[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
         "name": str,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DestinationConfigurationTypeDef = TypedDict(
     "DestinationConfigurationTypeDef",
     {
         "cloudWatchLogs": CloudWatchLogsDestinationConfigurationTypeDef,
@@ -427,15 +427,15 @@
 )
 
 ListRoomsResponseTypeDef = TypedDict(
     "ListRoomsResponseTypeDef",
     {
         "nextToken": str,
         "rooms": List[RoomSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLoggingConfigurationRequestRequestTypeDef",
     {
         "destinationConfiguration": DestinationConfigurationTypeDef,
@@ -465,30 +465,30 @@
         "createTime": datetime,
         "destinationConfiguration": DestinationConfigurationTypeDef,
         "id": str,
         "name": str,
         "state": Literal["ACTIVE"],
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoggingConfigurationResponseTypeDef = TypedDict(
     "GetLoggingConfigurationResponseTypeDef",
     {
         "arn": str,
         "createTime": datetime,
         "destinationConfiguration": DestinationConfigurationTypeDef,
         "id": str,
         "name": str,
         "state": LoggingConfigurationStateType,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingConfigurationSummaryTypeDef = TypedDict(
     "LoggingConfigurationSummaryTypeDef",
     {
         "arn": str,
@@ -533,19 +533,19 @@
         "createTime": datetime,
         "destinationConfiguration": DestinationConfigurationTypeDef,
         "id": str,
         "name": str,
         "state": Literal["ACTIVE"],
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLoggingConfigurationsResponseTypeDef = TypedDict(
     "ListLoggingConfigurationsResponseTypeDef",
     {
         "loggingConfigurations": List[LoggingConfigurationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat/type_defs.pyi` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -25,35 +25,35 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CloudWatchLogsDestinationConfigurationTypeDef",
     "CreateChatTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateChatTokenResponseTypeDef",
     "MessageReviewHandlerTypeDef",
     "DeleteLoggingConfigurationRequestRequestTypeDef",
     "DeleteMessageRequestRequestTypeDef",
+    "DeleteMessageResponseTypeDef",
     "DeleteRoomRequestRequestTypeDef",
     "FirehoseDestinationConfigurationTypeDef",
     "S3DestinationConfigurationTypeDef",
     "DisconnectUserRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetLoggingConfigurationRequestRequestTypeDef",
     "GetRoomRequestRequestTypeDef",
     "ListLoggingConfigurationsRequestRequestTypeDef",
     "ListRoomsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SendEventRequestRequestTypeDef",
+    "SendEventResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CreateChatTokenResponseTypeDef",
-    "DeleteMessageResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SendEventResponseTypeDef",
     "CreateRoomRequestRequestTypeDef",
     "CreateRoomResponseTypeDef",
     "GetRoomResponseTypeDef",
     "RoomSummaryTypeDef",
     "UpdateRoomRequestRequestTypeDef",
     "UpdateRoomResponseTypeDef",
     "DestinationConfigurationTypeDef",
@@ -92,22 +92,21 @@
 )
 
 class CreateChatTokenRequestRequestTypeDef(
     _RequiredCreateChatTokenRequestRequestTypeDef, _OptionalCreateChatTokenRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateChatTokenResponseTypeDef = TypedDict(
+    "CreateChatTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "sessionExpirationTime": datetime,
+        "token": str,
+        "tokenExpirationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MessageReviewHandlerTypeDef = TypedDict(
     "MessageReviewHandlerTypeDef",
     {
         "fallbackResult": FallbackResultType,
@@ -139,14 +138,22 @@
 )
 
 class DeleteMessageRequestRequestTypeDef(
     _RequiredDeleteMessageRequestRequestTypeDef, _OptionalDeleteMessageRequestRequestTypeDef
 ):
     pass
 
+DeleteMessageResponseTypeDef = TypedDict(
+    "DeleteMessageResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteRoomRequestRequestTypeDef = TypedDict(
     "DeleteRoomRequestRequestTypeDef",
     {
         "identifier": str,
     },
 )
 
@@ -180,14 +187,21 @@
 )
 
 class DisconnectUserRequestRequestTypeDef(
     _RequiredDisconnectUserRequestRequestTypeDef, _OptionalDisconnectUserRequestRequestTypeDef
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "GetLoggingConfigurationRequestRequestTypeDef",
     {
         "identifier": str,
     },
 )
 
@@ -222,14 +236,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
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
 _RequiredSendEventRequestRequestTypeDef = TypedDict(
     "_RequiredSendEventRequestRequestTypeDef",
     {
         "eventName": str,
         "roomIdentifier": str,
     },
 )
@@ -242,14 +275,22 @@
 )
 
 class SendEventRequestRequestTypeDef(
     _RequiredSendEventRequestRequestTypeDef, _OptionalSendEventRequestRequestTypeDef
 ):
     pass
 
+SendEventResponseTypeDef = TypedDict(
+    "SendEventResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -258,55 +299,14 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-CreateChatTokenResponseTypeDef = TypedDict(
-    "CreateChatTokenResponseTypeDef",
-    {
-        "sessionExpirationTime": datetime,
-        "token": str,
-        "tokenExpirationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMessageResponseTypeDef = TypedDict(
-    "DeleteMessageResponseTypeDef",
-    {
-        "id": str,
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEventResponseTypeDef = TypedDict(
-    "SendEventResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateRoomRequestRequestTypeDef = TypedDict(
     "CreateRoomRequestRequestTypeDef",
     {
         "loggingConfigurationIdentifiers": Sequence[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
@@ -325,15 +325,15 @@
         "loggingConfigurationIdentifiers": List[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
         "name": str,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoomResponseTypeDef = TypedDict(
     "GetRoomResponseTypeDef",
     {
         "arn": str,
@@ -342,15 +342,15 @@
         "loggingConfigurationIdentifiers": List[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
         "name": str,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RoomSummaryTypeDef = TypedDict(
     "RoomSummaryTypeDef",
     {
         "arn": str,
@@ -397,15 +397,15 @@
         "loggingConfigurationIdentifiers": List[str],
         "maximumMessageLength": int,
         "maximumMessageRatePerSecond": int,
         "messageReviewHandler": MessageReviewHandlerTypeDef,
         "name": str,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DestinationConfigurationTypeDef = TypedDict(
     "DestinationConfigurationTypeDef",
     {
         "cloudWatchLogs": CloudWatchLogsDestinationConfigurationTypeDef,
@@ -416,15 +416,15 @@
 )
 
 ListRoomsResponseTypeDef = TypedDict(
     "ListRoomsResponseTypeDef",
     {
         "nextToken": str,
         "rooms": List[RoomSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLoggingConfigurationRequestRequestTypeDef",
     {
         "destinationConfiguration": DestinationConfigurationTypeDef,
@@ -452,30 +452,30 @@
         "createTime": datetime,
         "destinationConfiguration": DestinationConfigurationTypeDef,
         "id": str,
         "name": str,
         "state": Literal["ACTIVE"],
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoggingConfigurationResponseTypeDef = TypedDict(
     "GetLoggingConfigurationResponseTypeDef",
     {
         "arn": str,
         "createTime": datetime,
         "destinationConfiguration": DestinationConfigurationTypeDef,
         "id": str,
         "name": str,
         "state": LoggingConfigurationStateType,
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingConfigurationSummaryTypeDef = TypedDict(
     "LoggingConfigurationSummaryTypeDef",
     {
         "arn": str,
@@ -518,19 +518,19 @@
         "createTime": datetime,
         "destinationConfiguration": DestinationConfigurationTypeDef,
         "id": str,
         "name": str,
         "state": Literal["ACTIVE"],
         "tags": Dict[str, str],
         "updateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLoggingConfigurationsResponseTypeDef = TypedDict(
     "ListLoggingConfigurationsResponseTypeDef",
     {
         "loggingConfigurations": List[LoggingConfigurationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/PKG-INFO` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ivschat
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ivschat 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ivschat 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ivschat"></a>
 
 # types-aiobotocore-ivschat
 
 [![PyPI - types-aiobotocore-ivschat](https://img.shields.io/pypi/v/types-aiobotocore-ivschat.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivschat)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ivschat.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivschat)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ivschat?color=blue)](https://pypistats.org/packages/types-aiobotocore-ivschat)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ivschat 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat)
+[aiobotocore.ivschat 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivschat.html#ivschat)
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
 [types-aiobotocore-ivschat docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,35 +295,35 @@
 `types_aiobotocore_ivschat.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ivschat.type_defs import (
     CloudWatchLogsDestinationConfigurationTypeDef,
     CreateChatTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateChatTokenResponseTypeDef,
     MessageReviewHandlerTypeDef,
     DeleteLoggingConfigurationRequestRequestTypeDef,
     DeleteMessageRequestRequestTypeDef,
+    DeleteMessageResponseTypeDef,
     DeleteRoomRequestRequestTypeDef,
     FirehoseDestinationConfigurationTypeDef,
     S3DestinationConfigurationTypeDef,
     DisconnectUserRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetLoggingConfigurationRequestRequestTypeDef,
     GetRoomRequestRequestTypeDef,
     ListLoggingConfigurationsRequestRequestTypeDef,
     ListRoomsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     SendEventRequestRequestTypeDef,
+    SendEventResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateChatTokenResponseTypeDef,
-    DeleteMessageResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendEventResponseTypeDef,
     CreateRoomRequestRequestTypeDef,
     CreateRoomResponseTypeDef,
     GetRoomResponseTypeDef,
     RoomSummaryTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateRoomResponseTypeDef,
     DestinationConfigurationTypeDef,
@@ -345,43 +345,43 @@
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

### Comparing `types-aiobotocore-ivschat-2.5.0.post1/types_aiobotocore_ivschat.egg-info/SOURCES.txt` & `types-aiobotocore-ivschat-2.5.1/types_aiobotocore_ivschat.egg-info/SOURCES.txt`

 * *Files identical despite different names*

