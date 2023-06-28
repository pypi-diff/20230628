# Comparing `tmp/types-aiobotocore-kinesis-video-signaling-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kinesis-video-signaling-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kinesis-video-signaling-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kinesis-video-signaling-2.5.1.tar", last modified: Wed Jun 28 01:43:42 2023, max compression
```

## Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1.tar` & `types-aiobotocore-kinesis-video-signaling-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.475345 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13109 2023-03-11 12:26:51.471344 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11468 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.475345 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2245 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.471344 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/
--rw-r--r--   0 runner    (1001) docker     (123)      600 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      599 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1019 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6389 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6378 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7793 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7791 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2515 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:57.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.471344 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13109 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.846162 types-aiobotocore-kinesis-video-signaling-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13117 2023-06-28 01:43:42.846162 types-aiobotocore-kinesis-video-signaling-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11482 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.846162 types-aiobotocore-kinesis-video-signaling-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2239 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.846162 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/
+-rw-r--r--   0 runner    (1001) docker     (123)      600 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      599 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1007 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6389 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6378 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8002 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8000 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2519 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2516 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:37.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.846162 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13117 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/LICENSE` & `types-aiobotocore-kinesis-video-signaling-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kinesis-video-signaling-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesis-video-signaling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideoSignalingChannels 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideoSignalingChannels 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesis-video-signaling"></a>
 
 # types-aiobotocore-kinesis-video-signaling
 
 [![PyPI - types-aiobotocore-kinesis-video-signaling](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-signaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-signaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-signaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-signaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-signaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-signaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoSignalingChannels 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-signaling.html#KinesisVideoSignalingChannels)
+[aiobotocore.KinesisVideoSignalingChannels 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-signaling.html#KinesisVideoSignalingChannels)
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
 [types-aiobotocore-kinesis-video-signaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,59 +295,59 @@
 
 ```python
 from types_aiobotocore_kinesis_video_signaling.type_defs import (
     GetIceServerConfigRequestRequestTypeDef,
     IceServerTypeDef,
     ResponseMetadataTypeDef,
     SendAlexaOfferToMasterRequestRequestTypeDef,
-    GetIceServerConfigResponseTypeDef,
     SendAlexaOfferToMasterResponseTypeDef,
+    GetIceServerConfigResponseTypeDef,
 )
 
 
 def get_structure() -> GetIceServerConfigRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/README.md` & `types-aiobotocore-kinesis-video-signaling-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kinesis-video-signaling"></a>
 
 # types-aiobotocore-kinesis-video-signaling
 
 [![PyPI - types-aiobotocore-kinesis-video-signaling](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-signaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-signaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-signaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-signaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-signaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-signaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoSignalingChannels 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-signaling.html#KinesisVideoSignalingChannels)
+[aiobotocore.KinesisVideoSignalingChannels 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-signaling.html#KinesisVideoSignalingChannels)
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
 [types-aiobotocore-kinesis-video-signaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -262,59 +262,59 @@
 
 ```python
 from types_aiobotocore_kinesis_video_signaling.type_defs import (
     GetIceServerConfigRequestRequestTypeDef,
     IceServerTypeDef,
     ResponseMetadataTypeDef,
     SendAlexaOfferToMasterRequestRequestTypeDef,
-    GetIceServerConfigResponseTypeDef,
     SendAlexaOfferToMasterResponseTypeDef,
+    GetIceServerConfigResponseTypeDef,
 )
 
 
 def get_structure() -> GetIceServerConfigRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/setup.py` & `types-aiobotocore-kinesis-video-signaling-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kinesis-video-signaling.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kinesis-video-signaling",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kinesis_video_signaling"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KinesisVideoSignalingChannels 2.5.0 service generated"
-        " with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KinesisVideoSignalingChannels 2.5.1 service generated"
+        " with mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/",
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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/__init__.py` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/__init__.pyi` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/client.py` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/client.pyi` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/literals.py` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -14,24 +14,22 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ServiceType",
     "KinesisVideoSignalingChannelsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 ServiceType = Literal["TURN"]
 KinesisVideoSignalingChannelsServiceName = Literal["kinesis-video-signaling"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -88,14 +86,15 @@
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
@@ -174,14 +173,15 @@
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
@@ -192,14 +192,15 @@
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
@@ -235,14 +236,15 @@
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
@@ -261,16 +263,19 @@
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
@@ -354,15 +359,17 @@
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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/literals.pyi` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,22 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ServiceType",
     "KinesisVideoSignalingChannelsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 ServiceType = Literal["TURN"]
 KinesisVideoSignalingChannelsServiceName = Literal["kinesis-video-signaling"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -86,14 +88,15 @@
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
@@ -172,14 +175,15 @@
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
@@ -190,14 +194,15 @@
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
@@ -233,14 +238,15 @@
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
@@ -259,16 +265,19 @@
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
@@ -352,15 +361,17 @@
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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/type_defs.py` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -25,16 +25,16 @@
 
 
 __all__ = (
     "GetIceServerConfigRequestRequestTypeDef",
     "IceServerTypeDef",
     "ResponseMetadataTypeDef",
     "SendAlexaOfferToMasterRequestRequestTypeDef",
-    "GetIceServerConfigResponseTypeDef",
     "SendAlexaOfferToMasterResponseTypeDef",
+    "GetIceServerConfigResponseTypeDef",
 )
 
 _RequiredGetIceServerConfigRequestRequestTypeDef = TypedDict(
     "_RequiredGetIceServerConfigRequestRequestTypeDef",
     {
         "ChannelARN": str,
     },
@@ -84,22 +84,22 @@
     {
         "ChannelARN": str,
         "SenderClientId": str,
         "MessagePayload": str,
     },
 )
 
-GetIceServerConfigResponseTypeDef = TypedDict(
-    "GetIceServerConfigResponseTypeDef",
+SendAlexaOfferToMasterResponseTypeDef = TypedDict(
+    "SendAlexaOfferToMasterResponseTypeDef",
     {
-        "IceServerList": List[IceServerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Answer": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-SendAlexaOfferToMasterResponseTypeDef = TypedDict(
-    "SendAlexaOfferToMasterResponseTypeDef",
+GetIceServerConfigResponseTypeDef = TypedDict(
+    "GetIceServerConfigResponseTypeDef",
     {
-        "Answer": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "IceServerList": List[IceServerTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling/type_defs.pyi` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -24,16 +24,16 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "GetIceServerConfigRequestRequestTypeDef",
     "IceServerTypeDef",
     "ResponseMetadataTypeDef",
     "SendAlexaOfferToMasterRequestRequestTypeDef",
-    "GetIceServerConfigResponseTypeDef",
     "SendAlexaOfferToMasterResponseTypeDef",
+    "GetIceServerConfigResponseTypeDef",
 )
 
 _RequiredGetIceServerConfigRequestRequestTypeDef = TypedDict(
     "_RequiredGetIceServerConfigRequestRequestTypeDef",
     {
         "ChannelARN": str,
     },
@@ -81,22 +81,22 @@
     {
         "ChannelARN": str,
         "SenderClientId": str,
         "MessagePayload": str,
     },
 )
 
-GetIceServerConfigResponseTypeDef = TypedDict(
-    "GetIceServerConfigResponseTypeDef",
+SendAlexaOfferToMasterResponseTypeDef = TypedDict(
+    "SendAlexaOfferToMasterResponseTypeDef",
     {
-        "IceServerList": List[IceServerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Answer": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-SendAlexaOfferToMasterResponseTypeDef = TypedDict(
-    "SendAlexaOfferToMasterResponseTypeDef",
+GetIceServerConfigResponseTypeDef = TypedDict(
+    "GetIceServerConfigResponseTypeDef",
     {
-        "Answer": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "IceServerList": List[IceServerTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/PKG-INFO` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesis-video-signaling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideoSignalingChannels 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideoSignalingChannels 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesis-video-signaling"></a>
 
 # types-aiobotocore-kinesis-video-signaling
 
 [![PyPI - types-aiobotocore-kinesis-video-signaling](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-signaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-signaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-signaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-signaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-signaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-signaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoSignalingChannels 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-signaling.html#KinesisVideoSignalingChannels)
+[aiobotocore.KinesisVideoSignalingChannels 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-signaling.html#KinesisVideoSignalingChannels)
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
 [types-aiobotocore-kinesis-video-signaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_signaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,59 +295,59 @@
 
 ```python
 from types_aiobotocore_kinesis_video_signaling.type_defs import (
     GetIceServerConfigRequestRequestTypeDef,
     IceServerTypeDef,
     ResponseMetadataTypeDef,
     SendAlexaOfferToMasterRequestRequestTypeDef,
-    GetIceServerConfigResponseTypeDef,
     SendAlexaOfferToMasterResponseTypeDef,
+    GetIceServerConfigResponseTypeDef,
 )
 
 
 def get_structure() -> GetIceServerConfigRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-kinesis-video-signaling-2.5.0.post1/types_aiobotocore_kinesis_video_signaling.egg-info/SOURCES.txt` & `types-aiobotocore-kinesis-video-signaling-2.5.1/types_aiobotocore_kinesis_video_signaling.egg-info/SOURCES.txt`

 * *Files identical despite different names*

