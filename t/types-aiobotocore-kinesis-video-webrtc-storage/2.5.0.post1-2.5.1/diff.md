# Comparing `tmp/types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kinesis-video-webrtc-storage-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kinesis-video-webrtc-storage-2.5.1.tar", last modified: Wed Jun 28 01:43:42 2023, max compression
```

## Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1.tar` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.495344 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13159 2023-03-11 12:26:51.495344 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11507 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.495344 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.491345 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/
--rw-r--r--   0 runner    (1001) docker     (123)      595 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      594 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5283 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5274 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7830 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7828 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     1183 2023-03-11 12:16:58.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     1182 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.495344 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13159 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.854162 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13177 2023-06-28 01:43:42.854162 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11531 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.854162 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2265 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.846162 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/
+-rw-r--r--   0 runner    (1001) docker     (123)      595 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      594 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5283 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5274 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8039 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8037 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     1195 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1194 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:38.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.854162 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13177 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/LICENSE` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesis-video-webrtc-storage
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesis-video-webrtc-storage"></a>
 
 # types-aiobotocore-kinesis-video-webrtc-storage
 
 [![PyPI - types-aiobotocore-kinesis-video-webrtc-storage](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-webrtc-storage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-webrtc-storage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-webrtc-storage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-webrtc-storage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-webrtc-storage?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-webrtc-storage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoWebRTCStorage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage)
+[aiobotocore.KinesisVideoWebRTCStorage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage)
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
 [types-aiobotocore-kinesis-video-webrtc-storage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,60 +294,60 @@
 
 `types_aiobotocore_kinesis_video_webrtc_storage.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import (
-    ResponseMetadataTypeDef,
-    JoinStorageSessionInputRequestTypeDef,
     EmptyResponseMetadataTypeDef,
+    JoinStorageSessionInputRequestTypeDef,
+    ResponseMetadataTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> EmptyResponseMetadataTypeDef:
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/README.md` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kinesis-video-webrtc-storage"></a>
 
 # types-aiobotocore-kinesis-video-webrtc-storage
 
 [![PyPI - types-aiobotocore-kinesis-video-webrtc-storage](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-webrtc-storage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-webrtc-storage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-webrtc-storage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-webrtc-storage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-webrtc-storage?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-webrtc-storage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoWebRTCStorage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage)
+[aiobotocore.KinesisVideoWebRTCStorage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage)
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
 [types-aiobotocore-kinesis-video-webrtc-storage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,60 +261,60 @@
 
 `types_aiobotocore_kinesis_video_webrtc_storage.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import (
-    ResponseMetadataTypeDef,
-    JoinStorageSessionInputRequestTypeDef,
     EmptyResponseMetadataTypeDef,
+    JoinStorageSessionInputRequestTypeDef,
+    ResponseMetadataTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> EmptyResponseMetadataTypeDef:
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/setup.py` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kinesis-video-webrtc-storage.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kinesis-video-webrtc-storage",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kinesis_video_webrtc_storage"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/",
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.py` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.pyi` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/__main__.py` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage\nOther"
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/client.py` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/client.pyi` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/literals.py` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,23 +14,21 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "KinesisVideoWebRTCStorageServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 KinesisVideoWebRTCStorageServiceName = Literal["kinesis-video-webrtc-storage"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -86,14 +84,15 @@
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
@@ -172,14 +171,15 @@
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
@@ -190,14 +190,15 @@
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
@@ -233,14 +234,15 @@
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
@@ -259,16 +261,19 @@
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
@@ -352,15 +357,17 @@
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/literals.pyi` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,21 +14,23 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "KinesisVideoWebRTCStorageServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 KinesisVideoWebRTCStorageServiceName = Literal["kinesis-video-webrtc-storage"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -84,14 +86,15 @@
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
@@ -170,14 +173,15 @@
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
@@ -188,14 +192,15 @@
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
@@ -231,14 +236,15 @@
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
@@ -257,16 +263,19 @@
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
@@ -350,15 +359,17 @@
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.py` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -2,51 +2,51 @@
 Type annotations for kinesis-video-webrtc-storage service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import EmptyResponseMetadataTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: EmptyResponseMetadataTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
-    "JoinStorageSessionInputRequestTypeDef",
     "EmptyResponseMetadataTypeDef",
+    "JoinStorageSessionInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
 )
 
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
 
 JoinStorageSessionInputRequestTypeDef = TypedDict(
     "JoinStorageSessionInputRequestTypeDef",
     {
         "channelArn": str,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
```

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.pyi` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -2,50 +2,50 @@
 Type annotations for kinesis-video-webrtc-storage service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import EmptyResponseMetadataTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: EmptyResponseMetadataTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
-    "ResponseMetadataTypeDef",
-    "JoinStorageSessionInputRequestTypeDef",
     "EmptyResponseMetadataTypeDef",
+    "JoinStorageSessionInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
 )
 
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
 
 JoinStorageSessionInputRequestTypeDef = TypedDict(
     "JoinStorageSessionInputRequestTypeDef",
     {
         "channelArn": str,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
```

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/PKG-INFO` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesis-video-webrtc-storage
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideoWebRTCStorage 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesis-video-webrtc-storage"></a>
 
 # types-aiobotocore-kinesis-video-webrtc-storage
 
 [![PyPI - types-aiobotocore-kinesis-video-webrtc-storage](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-webrtc-storage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-webrtc-storage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-webrtc-storage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-webrtc-storage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-webrtc-storage?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-webrtc-storage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoWebRTCStorage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage)
+[aiobotocore.KinesisVideoWebRTCStorage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-webrtc-storage.html#KinesisVideoWebRTCStorage)
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
 [types-aiobotocore-kinesis-video-webrtc-storage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_webrtc_storage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,60 +294,60 @@
 
 `types_aiobotocore_kinesis_video_webrtc_storage.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_kinesis_video_webrtc_storage.type_defs import (
-    ResponseMetadataTypeDef,
-    JoinStorageSessionInputRequestTypeDef,
     EmptyResponseMetadataTypeDef,
+    JoinStorageSessionInputRequestTypeDef,
+    ResponseMetadataTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> EmptyResponseMetadataTypeDef:
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

### Comparing `types-aiobotocore-kinesis-video-webrtc-storage-2.5.0.post1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/SOURCES.txt` & `types-aiobotocore-kinesis-video-webrtc-storage-2.5.1/types_aiobotocore_kinesis_video_webrtc_storage.egg-info/SOURCES.txt`

 * *Files identical despite different names*

