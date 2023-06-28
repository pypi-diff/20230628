# Comparing `tmp/types-aiobotocore-connectparticipant-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-connectparticipant-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-connectparticipant-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-connectparticipant-2.5.1.tar", last modified: Wed Jun 28 01:43:20 2023, max compression
```

## Comparing `types-aiobotocore-connectparticipant-2.5.0.post1.tar` & `types-aiobotocore-connectparticipant-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.287098 types-aiobotocore-connectparticipant-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13501 2023-03-11 12:26:27.287098 types-aiobotocore-connectparticipant-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11886 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:27.287098 types-aiobotocore-connectparticipant-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2217 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.287098 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/
--rw-r--r--   0 runner    (1001) docker     (123)      530 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      529 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      987 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9841 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9825 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8335 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8333 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8336 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8325 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:02.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.287098 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13501 2023-03-11 12:26:27.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-03-11 12:26:27.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:27.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:26:27.000000 types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.222119 types-aiobotocore-connectparticipant-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13504 2023-06-28 01:43:20.222119 types-aiobotocore-connectparticipant-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11895 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:20.222119 types-aiobotocore-connectparticipant-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2211 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.222119 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/
+-rw-r--r--   0 runner    (1001) docker     (123)      530 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      529 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9841 2023-06-28 01:28:41.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9825 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8544 2023-06-28 01:28:41.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8542 2023-06-28 01:28:41.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8348 2023-06-28 01:28:41.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8337 2023-06-28 01:28:41.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:40.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.222119 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13504 2023-06-28 01:43:20.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-28 01:43:20.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:20.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:20.000000 types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/LICENSE` & `types-aiobotocore-connectparticipant-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/PKG-INFO` & `types-aiobotocore-connectparticipant-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-connectparticipant
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectParticipant 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectParticipant 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-connectparticipant"></a>
 
 # types-aiobotocore-connectparticipant
 
 [![PyPI - types-aiobotocore-connectparticipant](https://img.shields.io/pypi/v/types-aiobotocore-connectparticipant.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectparticipant)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectparticipant.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectparticipant)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectparticipant?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectparticipant)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectParticipant 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant)
+[aiobotocore.ConnectParticipant 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant)
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
 [types-aiobotocore-connectparticipant docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,27 +299,27 @@
 
 ```python
 from types_aiobotocore_connectparticipant.type_defs import (
     AttachmentItemTypeDef,
     CompleteAttachmentUploadRequestRequestTypeDef,
     ConnectionCredentialsTypeDef,
     CreateParticipantConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     WebsocketTypeDef,
     DisconnectParticipantRequestRequestTypeDef,
     GetAttachmentRequestRequestTypeDef,
+    GetAttachmentResponseTypeDef,
     StartPositionTypeDef,
     ReceiptTypeDef,
+    ResponseMetadataTypeDef,
     SendEventRequestRequestTypeDef,
+    SendEventResponseTypeDef,
     SendMessageRequestRequestTypeDef,
+    SendMessageResponseTypeDef,
     StartAttachmentUploadRequestRequestTypeDef,
     UploadMetadataTypeDef,
-    GetAttachmentResponseTypeDef,
-    SendEventResponseTypeDef,
-    SendMessageResponseTypeDef,
     CreateParticipantConnectionResponseTypeDef,
     GetTranscriptRequestRequestTypeDef,
     MessageMetadataTypeDef,
     StartAttachmentUploadResponseTypeDef,
     ItemTypeDef,
     GetTranscriptResponseTypeDef,
 )
@@ -332,43 +332,43 @@
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/README.md` & `types-aiobotocore-connectparticipant-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-connectparticipant"></a>
 
 # types-aiobotocore-connectparticipant
 
 [![PyPI - types-aiobotocore-connectparticipant](https://img.shields.io/pypi/v/types-aiobotocore-connectparticipant.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectparticipant)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectparticipant.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectparticipant)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectparticipant?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectparticipant)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectParticipant 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant)
+[aiobotocore.ConnectParticipant 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant)
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
 [types-aiobotocore-connectparticipant docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/).
 
 See how it helps to find and fix potential bugs:
 
@@ -266,27 +266,27 @@
 
 ```python
 from types_aiobotocore_connectparticipant.type_defs import (
     AttachmentItemTypeDef,
     CompleteAttachmentUploadRequestRequestTypeDef,
     ConnectionCredentialsTypeDef,
     CreateParticipantConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     WebsocketTypeDef,
     DisconnectParticipantRequestRequestTypeDef,
     GetAttachmentRequestRequestTypeDef,
+    GetAttachmentResponseTypeDef,
     StartPositionTypeDef,
     ReceiptTypeDef,
+    ResponseMetadataTypeDef,
     SendEventRequestRequestTypeDef,
+    SendEventResponseTypeDef,
     SendMessageRequestRequestTypeDef,
+    SendMessageResponseTypeDef,
     StartAttachmentUploadRequestRequestTypeDef,
     UploadMetadataTypeDef,
-    GetAttachmentResponseTypeDef,
-    SendEventResponseTypeDef,
-    SendMessageResponseTypeDef,
     CreateParticipantConnectionResponseTypeDef,
     GetTranscriptRequestRequestTypeDef,
     MessageMetadataTypeDef,
     StartAttachmentUploadResponseTypeDef,
     ItemTypeDef,
     GetTranscriptResponseTypeDef,
 )
@@ -299,43 +299,43 @@
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/setup.py` & `types-aiobotocore-connectparticipant-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-connectparticipant.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-connectparticipant",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_connectparticipant"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ConnectParticipant 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ConnectParticipant 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/"
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/__init__.py` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/__init__.pyi` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/__main__.py` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ConnectParticipant 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ConnectParticipant 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant\nOther"
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/client.py` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/client.pyi` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/literals.py` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -111,14 +111,15 @@
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
@@ -197,14 +198,15 @@
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
@@ -215,14 +217,15 @@
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
@@ -258,14 +261,15 @@
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
@@ -284,16 +288,19 @@
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
@@ -377,15 +384,17 @@
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/literals.pyi` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -109,14 +109,15 @@
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
@@ -195,14 +196,15 @@
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
@@ -213,14 +215,15 @@
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
@@ -256,14 +259,15 @@
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
@@ -282,16 +286,19 @@
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
@@ -375,15 +382,17 @@
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/type_defs.py` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -30,27 +30,27 @@
 
 
 __all__ = (
     "AttachmentItemTypeDef",
     "CompleteAttachmentUploadRequestRequestTypeDef",
     "ConnectionCredentialsTypeDef",
     "CreateParticipantConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "WebsocketTypeDef",
     "DisconnectParticipantRequestRequestTypeDef",
     "GetAttachmentRequestRequestTypeDef",
+    "GetAttachmentResponseTypeDef",
     "StartPositionTypeDef",
     "ReceiptTypeDef",
+    "ResponseMetadataTypeDef",
     "SendEventRequestRequestTypeDef",
+    "SendEventResponseTypeDef",
     "SendMessageRequestRequestTypeDef",
+    "SendMessageResponseTypeDef",
     "StartAttachmentUploadRequestRequestTypeDef",
     "UploadMetadataTypeDef",
-    "GetAttachmentResponseTypeDef",
-    "SendEventResponseTypeDef",
-    "SendMessageResponseTypeDef",
     "CreateParticipantConnectionResponseTypeDef",
     "GetTranscriptRequestRequestTypeDef",
     "MessageMetadataTypeDef",
     "StartAttachmentUploadResponseTypeDef",
     "ItemTypeDef",
     "GetTranscriptResponseTypeDef",
 )
@@ -103,25 +103,14 @@
 class CreateParticipantConnectionRequestRequestTypeDef(
     _RequiredCreateParticipantConnectionRequestRequestTypeDef,
     _OptionalCreateParticipantConnectionRequestRequestTypeDef,
 ):
     pass
 
 
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
 WebsocketTypeDef = TypedDict(
     "WebsocketTypeDef",
     {
         "Url": str,
         "ConnectionExpiry": str,
     },
     total=False,
@@ -153,14 +142,23 @@
     "GetAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
         "ConnectionToken": str,
     },
 )
 
+GetAttachmentResponseTypeDef = TypedDict(
+    "GetAttachmentResponseTypeDef",
+    {
+        "Url": str,
+        "UrlExpiry": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartPositionTypeDef = TypedDict(
     "StartPositionTypeDef",
     {
         "Id": str,
         "AbsoluteTime": str,
         "MostRecent": int,
     },
@@ -173,14 +171,25 @@
         "DeliveredTimestamp": str,
         "ReadTimestamp": str,
         "RecipientParticipantId": str,
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
 _RequiredSendEventRequestRequestTypeDef = TypedDict(
     "_RequiredSendEventRequestRequestTypeDef",
     {
         "ContentType": str,
         "ConnectionToken": str,
     },
 )
@@ -196,14 +205,23 @@
 
 class SendEventRequestRequestTypeDef(
     _RequiredSendEventRequestRequestTypeDef, _OptionalSendEventRequestRequestTypeDef
 ):
     pass
 
 
+SendEventResponseTypeDef = TypedDict(
+    "SendEventResponseTypeDef",
+    {
+        "Id": str,
+        "AbsoluteTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendMessageRequestRequestTypeDef = TypedDict(
     "_RequiredSendMessageRequestRequestTypeDef",
     {
         "ContentType": str,
         "Content": str,
         "ConnectionToken": str,
     },
@@ -219,14 +237,23 @@
 
 class SendMessageRequestRequestTypeDef(
     _RequiredSendMessageRequestRequestTypeDef, _OptionalSendMessageRequestRequestTypeDef
 ):
     pass
 
 
+SendMessageResponseTypeDef = TypedDict(
+    "SendMessageResponseTypeDef",
+    {
+        "Id": str,
+        "AbsoluteTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartAttachmentUploadRequestRequestTypeDef = TypedDict(
     "StartAttachmentUploadRequestRequestTypeDef",
     {
         "ContentType": str,
         "AttachmentSizeInBytes": int,
         "AttachmentName": str,
         "ClientToken": str,
@@ -240,47 +267,20 @@
         "Url": str,
         "UrlExpiry": str,
         "HeadersToInclude": Dict[str, str],
     },
     total=False,
 )
 
-GetAttachmentResponseTypeDef = TypedDict(
-    "GetAttachmentResponseTypeDef",
-    {
-        "Url": str,
-        "UrlExpiry": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEventResponseTypeDef = TypedDict(
-    "SendEventResponseTypeDef",
-    {
-        "Id": str,
-        "AbsoluteTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendMessageResponseTypeDef = TypedDict(
-    "SendMessageResponseTypeDef",
-    {
-        "Id": str,
-        "AbsoluteTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateParticipantConnectionResponseTypeDef = TypedDict(
     "CreateParticipantConnectionResponseTypeDef",
     {
         "Websocket": WebsocketTypeDef,
         "ConnectionCredentials": ConnectionCredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTranscriptRequestRequestTypeDef = TypedDict(
     "_RequiredGetTranscriptRequestRequestTypeDef",
     {
         "ConnectionToken": str,
@@ -316,15 +316,15 @@
 )
 
 StartAttachmentUploadResponseTypeDef = TypedDict(
     "StartAttachmentUploadResponseTypeDef",
     {
         "AttachmentId": str,
         "UploadMetadata": UploadMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ItemTypeDef = TypedDict(
     "ItemTypeDef",
     {
         "AbsoluteTime": str,
@@ -345,10 +345,10 @@
 
 GetTranscriptResponseTypeDef = TypedDict(
     "GetTranscriptResponseTypeDef",
     {
         "InitialContactId": str,
         "Transcript": List[ItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant/type_defs.pyi` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -29,27 +29,27 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AttachmentItemTypeDef",
     "CompleteAttachmentUploadRequestRequestTypeDef",
     "ConnectionCredentialsTypeDef",
     "CreateParticipantConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "WebsocketTypeDef",
     "DisconnectParticipantRequestRequestTypeDef",
     "GetAttachmentRequestRequestTypeDef",
+    "GetAttachmentResponseTypeDef",
     "StartPositionTypeDef",
     "ReceiptTypeDef",
+    "ResponseMetadataTypeDef",
     "SendEventRequestRequestTypeDef",
+    "SendEventResponseTypeDef",
     "SendMessageRequestRequestTypeDef",
+    "SendMessageResponseTypeDef",
     "StartAttachmentUploadRequestRequestTypeDef",
     "UploadMetadataTypeDef",
-    "GetAttachmentResponseTypeDef",
-    "SendEventResponseTypeDef",
-    "SendMessageResponseTypeDef",
     "CreateParticipantConnectionResponseTypeDef",
     "GetTranscriptRequestRequestTypeDef",
     "MessageMetadataTypeDef",
     "StartAttachmentUploadResponseTypeDef",
     "ItemTypeDef",
     "GetTranscriptResponseTypeDef",
 )
@@ -100,25 +100,14 @@
 
 class CreateParticipantConnectionRequestRequestTypeDef(
     _RequiredCreateParticipantConnectionRequestRequestTypeDef,
     _OptionalCreateParticipantConnectionRequestRequestTypeDef,
 ):
     pass
 
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
 WebsocketTypeDef = TypedDict(
     "WebsocketTypeDef",
     {
         "Url": str,
         "ConnectionExpiry": str,
     },
     total=False,
@@ -148,14 +137,23 @@
     "GetAttachmentRequestRequestTypeDef",
     {
         "AttachmentId": str,
         "ConnectionToken": str,
     },
 )
 
+GetAttachmentResponseTypeDef = TypedDict(
+    "GetAttachmentResponseTypeDef",
+    {
+        "Url": str,
+        "UrlExpiry": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartPositionTypeDef = TypedDict(
     "StartPositionTypeDef",
     {
         "Id": str,
         "AbsoluteTime": str,
         "MostRecent": int,
     },
@@ -168,14 +166,25 @@
         "DeliveredTimestamp": str,
         "ReadTimestamp": str,
         "RecipientParticipantId": str,
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
 _RequiredSendEventRequestRequestTypeDef = TypedDict(
     "_RequiredSendEventRequestRequestTypeDef",
     {
         "ContentType": str,
         "ConnectionToken": str,
     },
 )
@@ -189,14 +198,23 @@
 )
 
 class SendEventRequestRequestTypeDef(
     _RequiredSendEventRequestRequestTypeDef, _OptionalSendEventRequestRequestTypeDef
 ):
     pass
 
+SendEventResponseTypeDef = TypedDict(
+    "SendEventResponseTypeDef",
+    {
+        "Id": str,
+        "AbsoluteTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendMessageRequestRequestTypeDef = TypedDict(
     "_RequiredSendMessageRequestRequestTypeDef",
     {
         "ContentType": str,
         "Content": str,
         "ConnectionToken": str,
     },
@@ -210,14 +228,23 @@
 )
 
 class SendMessageRequestRequestTypeDef(
     _RequiredSendMessageRequestRequestTypeDef, _OptionalSendMessageRequestRequestTypeDef
 ):
     pass
 
+SendMessageResponseTypeDef = TypedDict(
+    "SendMessageResponseTypeDef",
+    {
+        "Id": str,
+        "AbsoluteTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartAttachmentUploadRequestRequestTypeDef = TypedDict(
     "StartAttachmentUploadRequestRequestTypeDef",
     {
         "ContentType": str,
         "AttachmentSizeInBytes": int,
         "AttachmentName": str,
         "ClientToken": str,
@@ -231,47 +258,20 @@
         "Url": str,
         "UrlExpiry": str,
         "HeadersToInclude": Dict[str, str],
     },
     total=False,
 )
 
-GetAttachmentResponseTypeDef = TypedDict(
-    "GetAttachmentResponseTypeDef",
-    {
-        "Url": str,
-        "UrlExpiry": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEventResponseTypeDef = TypedDict(
-    "SendEventResponseTypeDef",
-    {
-        "Id": str,
-        "AbsoluteTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendMessageResponseTypeDef = TypedDict(
-    "SendMessageResponseTypeDef",
-    {
-        "Id": str,
-        "AbsoluteTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateParticipantConnectionResponseTypeDef = TypedDict(
     "CreateParticipantConnectionResponseTypeDef",
     {
         "Websocket": WebsocketTypeDef,
         "ConnectionCredentials": ConnectionCredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTranscriptRequestRequestTypeDef = TypedDict(
     "_RequiredGetTranscriptRequestRequestTypeDef",
     {
         "ConnectionToken": str,
@@ -305,15 +305,15 @@
 )
 
 StartAttachmentUploadResponseTypeDef = TypedDict(
     "StartAttachmentUploadResponseTypeDef",
     {
         "AttachmentId": str,
         "UploadMetadata": UploadMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ItemTypeDef = TypedDict(
     "ItemTypeDef",
     {
         "AbsoluteTime": str,
@@ -334,10 +334,10 @@
 
 GetTranscriptResponseTypeDef = TypedDict(
     "GetTranscriptResponseTypeDef",
     {
         "InitialContactId": str,
         "Transcript": List[ItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/PKG-INFO` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-connectparticipant
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectParticipant 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectParticipant 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-connectparticipant"></a>
 
 # types-aiobotocore-connectparticipant
 
 [![PyPI - types-aiobotocore-connectparticipant](https://img.shields.io/pypi/v/types-aiobotocore-connectparticipant.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectparticipant)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectparticipant.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectparticipant)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectparticipant?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectparticipant)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectParticipant 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant)
+[aiobotocore.ConnectParticipant 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectparticipant.html#ConnectParticipant)
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
 [types-aiobotocore-connectparticipant docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectparticipant/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,27 +299,27 @@
 
 ```python
 from types_aiobotocore_connectparticipant.type_defs import (
     AttachmentItemTypeDef,
     CompleteAttachmentUploadRequestRequestTypeDef,
     ConnectionCredentialsTypeDef,
     CreateParticipantConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     WebsocketTypeDef,
     DisconnectParticipantRequestRequestTypeDef,
     GetAttachmentRequestRequestTypeDef,
+    GetAttachmentResponseTypeDef,
     StartPositionTypeDef,
     ReceiptTypeDef,
+    ResponseMetadataTypeDef,
     SendEventRequestRequestTypeDef,
+    SendEventResponseTypeDef,
     SendMessageRequestRequestTypeDef,
+    SendMessageResponseTypeDef,
     StartAttachmentUploadRequestRequestTypeDef,
     UploadMetadataTypeDef,
-    GetAttachmentResponseTypeDef,
-    SendEventResponseTypeDef,
-    SendMessageResponseTypeDef,
     CreateParticipantConnectionResponseTypeDef,
     GetTranscriptRequestRequestTypeDef,
     MessageMetadataTypeDef,
     StartAttachmentUploadResponseTypeDef,
     ItemTypeDef,
     GetTranscriptResponseTypeDef,
 )
@@ -332,43 +332,43 @@
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

### Comparing `types-aiobotocore-connectparticipant-2.5.0.post1/types_aiobotocore_connectparticipant.egg-info/SOURCES.txt` & `types-aiobotocore-connectparticipant-2.5.1/types_aiobotocore_connectparticipant.egg-info/SOURCES.txt`

 * *Files identical despite different names*

