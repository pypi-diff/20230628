# Comparing `tmp/types-aiobotocore-kinesis-video-archived-media-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kinesis-video-archived-media-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kinesis-video-archived-media-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kinesis-video-archived-media-2.5.1.tar", last modified: Wed Jun 28 01:43:42 2023, max compression
```

## Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1.tar` & `types-aiobotocore-kinesis-video-archived-media-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.359343 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15411 2023-03-11 12:26:51.359343 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13759 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.359343 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.347343 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      964 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12159 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12142 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9486 2023-03-11 12:16:56.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9484 2023-03-11 12:16:56.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4248 2023-03-11 12:16:56.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4243 2023-03-11 12:16:56.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10219 2023-03-11 12:16:56.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    10210 2023-03-11 12:16:56.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:55.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.359343 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15411 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1212 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-03-11 12:26:51.000000 types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.686161 types-aiobotocore-kinesis-video-archived-media-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15424 2023-06-28 01:43:42.686161 types-aiobotocore-kinesis-video-archived-media-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13778 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.686161 types-aiobotocore-kinesis-video-archived-media-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2265 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.686161 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1009 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12159 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12142 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9695 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9693 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4145 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4140 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10235 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10226 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:36.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.686161 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15424 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1212 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 01:43:42.000000 types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/LICENSE` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesis-video-archived-media
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesis-video-archived-media"></a>
 
 # types-aiobotocore-kinesis-video-archived-media
 
 [![PyPI - types-aiobotocore-kinesis-video-archived-media](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-archived-media.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-archived-media.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-archived-media?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-archived-media)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoArchivedMedia 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
+[aiobotocore.KinesisVideoArchivedMedia 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
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
 [types-aiobotocore-kinesis-video-archived-media docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/).
 
 See how it helps to find and fix potential bugs:
 
@@ -343,29 +343,29 @@
 
 ```python
 from types_aiobotocore_kinesis_video_archived_media.type_defs import (
     ClipTimestampRangeTypeDef,
     DASHTimestampRangeTypeDef,
     TimestampRangeTypeDef,
     FragmentTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    GetClipOutputTypeDef,
+    GetDASHStreamingSessionURLOutputTypeDef,
+    GetHLSStreamingSessionURLOutputTypeDef,
+    GetImagesInputGetImagesPaginateTypeDef,
     GetImagesInputRequestTypeDef,
     ImageTypeDef,
     GetMediaForFragmentListInputRequestTypeDef,
+    GetMediaForFragmentListOutputTypeDef,
     HLSTimestampRangeTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ClipFragmentSelectorTypeDef,
     DASHFragmentSelectorTypeDef,
     FragmentSelectorTypeDef,
-    GetClipOutputTypeDef,
-    GetDASHStreamingSessionURLOutputTypeDef,
-    GetHLSStreamingSessionURLOutputTypeDef,
-    GetMediaForFragmentListOutputTypeDef,
     ListFragmentsOutputTypeDef,
-    GetImagesInputGetImagesPaginateTypeDef,
     GetImagesOutputTypeDef,
     HLSFragmentSelectorTypeDef,
     GetClipInputRequestTypeDef,
     GetDASHStreamingSessionURLInputRequestTypeDef,
     ListFragmentsInputListFragmentsPaginateTypeDef,
     ListFragmentsInputRequestTypeDef,
     GetHLSStreamingSessionURLInputRequestTypeDef,
@@ -379,43 +379,43 @@
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/README.md` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kinesis-video-archived-media"></a>
 
 # types-aiobotocore-kinesis-video-archived-media
 
 [![PyPI - types-aiobotocore-kinesis-video-archived-media](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-archived-media.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-archived-media.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-archived-media?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-archived-media)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoArchivedMedia 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
+[aiobotocore.KinesisVideoArchivedMedia 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
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
 [types-aiobotocore-kinesis-video-archived-media docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/).
 
 See how it helps to find and fix potential bugs:
 
@@ -310,29 +310,29 @@
 
 ```python
 from types_aiobotocore_kinesis_video_archived_media.type_defs import (
     ClipTimestampRangeTypeDef,
     DASHTimestampRangeTypeDef,
     TimestampRangeTypeDef,
     FragmentTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    GetClipOutputTypeDef,
+    GetDASHStreamingSessionURLOutputTypeDef,
+    GetHLSStreamingSessionURLOutputTypeDef,
+    GetImagesInputGetImagesPaginateTypeDef,
     GetImagesInputRequestTypeDef,
     ImageTypeDef,
     GetMediaForFragmentListInputRequestTypeDef,
+    GetMediaForFragmentListOutputTypeDef,
     HLSTimestampRangeTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ClipFragmentSelectorTypeDef,
     DASHFragmentSelectorTypeDef,
     FragmentSelectorTypeDef,
-    GetClipOutputTypeDef,
-    GetDASHStreamingSessionURLOutputTypeDef,
-    GetHLSStreamingSessionURLOutputTypeDef,
-    GetMediaForFragmentListOutputTypeDef,
     ListFragmentsOutputTypeDef,
-    GetImagesInputGetImagesPaginateTypeDef,
     GetImagesOutputTypeDef,
     HLSFragmentSelectorTypeDef,
     GetClipInputRequestTypeDef,
     GetDASHStreamingSessionURLInputRequestTypeDef,
     ListFragmentsInputListFragmentsPaginateTypeDef,
     ListFragmentsInputRequestTypeDef,
     GetHLSStreamingSessionURLInputRequestTypeDef,
@@ -346,43 +346,43 @@
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/setup.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kinesis-video-archived-media.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kinesis-video-archived-media",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kinesis_video_archived_media"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/",
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/__init__.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/__init__.pyi` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/__main__.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia\nOther"
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/client.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/client.pyi` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/literals.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -121,14 +121,15 @@
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
@@ -207,14 +208,15 @@
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
@@ -225,14 +227,15 @@
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
@@ -268,14 +271,15 @@
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
@@ -294,16 +298,19 @@
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
@@ -387,15 +394,17 @@
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/literals.pyi` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -119,14 +119,15 @@
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
@@ -205,14 +206,15 @@
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
@@ -223,14 +225,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -292,16 +296,19 @@
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
@@ -385,15 +392,17 @@
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/paginator.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -20,31 +20,27 @@
 
         get_images_paginator: GetImagesPaginator = client.get_paginator("get_images")
         list_fragments_paginator: ListFragmentsPaginator = client.get_paginator("list_fragments")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Mapping, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Mapping, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import FormatType, ImageSelectorTypeType
 from .type_defs import (
     FragmentSelectorTypeDef,
     GetImagesOutputTypeDef,
     ListFragmentsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = ("GetImagesPaginator", "ListFragmentsPaginator")
@@ -75,15 +71,15 @@
         SamplingInterval: int,
         Format: FormatType,
         StreamName: str = ...,
         StreamARN: str = ...,
         FormatConfig: Mapping[Literal["JPEGQuality"], str] = ...,
         WidthPixels: int = ...,
         HeightPixels: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetImagesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia.Paginator.GetImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/paginators/#getimagespaginator)
         """
 
 
@@ -95,13 +91,13 @@
 
     def paginate(
         self,
         *,
         StreamName: str = ...,
         StreamARN: str = ...,
         FragmentSelector: FragmentSelectorTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFragmentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia.Paginator.ListFragments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/paginators/#listfragmentspaginator)
         """
```

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/paginator.pyi` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -20,31 +20,27 @@
 
         get_images_paginator: GetImagesPaginator = client.get_paginator("get_images")
         list_fragments_paginator: ListFragmentsPaginator = client.get_paginator("list_fragments")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Mapping, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Mapping, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import FormatType, ImageSelectorTypeType
 from .type_defs import (
     FragmentSelectorTypeDef,
     GetImagesOutputTypeDef,
     ListFragmentsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = ("GetImagesPaginator", "ListFragmentsPaginator")
 
@@ -71,15 +67,15 @@
         SamplingInterval: int,
         Format: FormatType,
         StreamName: str = ...,
         StreamARN: str = ...,
         FormatConfig: Mapping[Literal["JPEGQuality"], str] = ...,
         WidthPixels: int = ...,
         HeightPixels: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetImagesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia.Paginator.GetImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/paginators/#getimagespaginator)
         """
 
 class ListFragmentsPaginator(AioPaginator):
@@ -90,13 +86,13 @@
 
     def paginate(
         self,
         *,
         StreamName: str = ...,
         StreamARN: str = ...,
         FragmentSelector: FragmentSelectorTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFragmentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia.Paginator.ListFragments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/paginators/#listfragmentspaginator)
         """
```

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/type_defs.py` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -39,35 +39,34 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ClipTimestampRangeTypeDef",
     "DASHTimestampRangeTypeDef",
     "TimestampRangeTypeDef",
     "FragmentTypeDef",
-    "ResponseMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetClipOutputTypeDef",
+    "GetDASHStreamingSessionURLOutputTypeDef",
+    "GetHLSStreamingSessionURLOutputTypeDef",
+    "GetImagesInputGetImagesPaginateTypeDef",
     "GetImagesInputRequestTypeDef",
     "ImageTypeDef",
     "GetMediaForFragmentListInputRequestTypeDef",
+    "GetMediaForFragmentListOutputTypeDef",
     "HLSTimestampRangeTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ClipFragmentSelectorTypeDef",
     "DASHFragmentSelectorTypeDef",
     "FragmentSelectorTypeDef",
-    "GetClipOutputTypeDef",
-    "GetDASHStreamingSessionURLOutputTypeDef",
-    "GetHLSStreamingSessionURLOutputTypeDef",
-    "GetMediaForFragmentListOutputTypeDef",
     "ListFragmentsOutputTypeDef",
-    "GetImagesInputGetImagesPaginateTypeDef",
     "GetImagesOutputTypeDef",
     "HLSFragmentSelectorTypeDef",
     "GetClipInputRequestTypeDef",
     "GetDASHStreamingSessionURLInputRequestTypeDef",
     "ListFragmentsInputListFragmentsPaginateTypeDef",
     "ListFragmentsInputRequestTypeDef",
     "GetHLSStreamingSessionURLInputRequestTypeDef",
@@ -106,35 +105,67 @@
         "ProducerTimestamp": datetime,
         "ServerTimestamp": datetime,
         "FragmentLengthInMilliseconds": int,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetClipOutputTypeDef = TypedDict(
+    "GetClipOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ContentType": str,
+        "Payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDASHStreamingSessionURLOutputTypeDef = TypedDict(
+    "GetDASHStreamingSessionURLOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DASHStreamingSessionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetHLSStreamingSessionURLOutputTypeDef = TypedDict(
+    "GetHLSStreamingSessionURLOutputTypeDef",
+    {
+        "HLSStreamingSessionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetImagesInputGetImagesPaginateTypeDef = TypedDict(
+    "_RequiredGetImagesInputGetImagesPaginateTypeDef",
+    {
+        "ImageSelectorType": ImageSelectorTypeType,
+        "StartTimestamp": Union[datetime, str],
+        "EndTimestamp": Union[datetime, str],
+        "SamplingInterval": int,
+        "Format": FormatType,
+    },
+)
+_OptionalGetImagesInputGetImagesPaginateTypeDef = TypedDict(
+    "_OptionalGetImagesInputGetImagesPaginateTypeDef",
+    {
+        "StreamName": str,
+        "StreamARN": str,
+        "FormatConfig": Mapping[Literal["JPEGQuality"], str],
+        "WidthPixels": int,
+        "HeightPixels": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetImagesInputGetImagesPaginateTypeDef(
+    _RequiredGetImagesInputGetImagesPaginateTypeDef, _OptionalGetImagesInputGetImagesPaginateTypeDef
+):
+    pass
+
 _RequiredGetImagesInputRequestTypeDef = TypedDict(
     "_RequiredGetImagesInputRequestTypeDef",
     {
         "ImageSelectorType": ImageSelectorTypeType,
         "StartTimestamp": Union[datetime, str],
         "EndTimestamp": Union[datetime, str],
         "SamplingInterval": int,
@@ -151,21 +182,19 @@
         "HeightPixels": int,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetImagesInputRequestTypeDef(
     _RequiredGetImagesInputRequestTypeDef, _OptionalGetImagesInputRequestTypeDef
 ):
     pass
 
-
 ImageTypeDef = TypedDict(
     "ImageTypeDef",
     {
         "TimeStamp": datetime,
         "Error": ImageErrorType,
         "ImageContent": str,
     },
@@ -183,31 +212,59 @@
     {
         "StreamName": str,
         "StreamARN": str,
     },
     total=False,
 )
 
-
 class GetMediaForFragmentListInputRequestTypeDef(
     _RequiredGetMediaForFragmentListInputRequestTypeDef,
     _OptionalGetMediaForFragmentListInputRequestTypeDef,
 ):
     pass
 
+GetMediaForFragmentListOutputTypeDef = TypedDict(
+    "GetMediaForFragmentListOutputTypeDef",
+    {
+        "ContentType": str,
+        "Payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 HLSTimestampRangeTypeDef = TypedDict(
     "HLSTimestampRangeTypeDef",
     {
         "StartTimestamp": Union[datetime, str],
         "EndTimestamp": Union[datetime, str],
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
 ClipFragmentSelectorTypeDef = TypedDict(
     "ClipFragmentSelectorTypeDef",
     {
         "FragmentSelectorType": ClipFragmentSelectorTypeType,
         "TimestampRange": ClipTimestampRangeTypeDef,
     },
 )
@@ -225,93 +282,29 @@
     "FragmentSelectorTypeDef",
     {
         "FragmentSelectorType": FragmentSelectorTypeType,
         "TimestampRange": TimestampRangeTypeDef,
     },
 )
 
-GetClipOutputTypeDef = TypedDict(
-    "GetClipOutputTypeDef",
-    {
-        "ContentType": str,
-        "Payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDASHStreamingSessionURLOutputTypeDef = TypedDict(
-    "GetDASHStreamingSessionURLOutputTypeDef",
-    {
-        "DASHStreamingSessionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetHLSStreamingSessionURLOutputTypeDef = TypedDict(
-    "GetHLSStreamingSessionURLOutputTypeDef",
-    {
-        "HLSStreamingSessionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMediaForFragmentListOutputTypeDef = TypedDict(
-    "GetMediaForFragmentListOutputTypeDef",
-    {
-        "ContentType": str,
-        "Payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListFragmentsOutputTypeDef = TypedDict(
     "ListFragmentsOutputTypeDef",
     {
         "Fragments": List[FragmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredGetImagesInputGetImagesPaginateTypeDef = TypedDict(
-    "_RequiredGetImagesInputGetImagesPaginateTypeDef",
-    {
-        "ImageSelectorType": ImageSelectorTypeType,
-        "StartTimestamp": Union[datetime, str],
-        "EndTimestamp": Union[datetime, str],
-        "SamplingInterval": int,
-        "Format": FormatType,
-    },
-)
-_OptionalGetImagesInputGetImagesPaginateTypeDef = TypedDict(
-    "_OptionalGetImagesInputGetImagesPaginateTypeDef",
-    {
-        "StreamName": str,
-        "StreamARN": str,
-        "FormatConfig": Mapping[Literal["JPEGQuality"], str],
-        "WidthPixels": int,
-        "HeightPixels": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetImagesInputGetImagesPaginateTypeDef(
-    _RequiredGetImagesInputGetImagesPaginateTypeDef, _OptionalGetImagesInputGetImagesPaginateTypeDef
-):
-    pass
-
-
 GetImagesOutputTypeDef = TypedDict(
     "GetImagesOutputTypeDef",
     {
         "Images": List[ImageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HLSFragmentSelectorTypeDef = TypedDict(
     "HLSFragmentSelectorTypeDef",
     {
         "FragmentSelectorType": HLSFragmentSelectorTypeType,
@@ -331,21 +324,19 @@
     {
         "StreamName": str,
         "StreamARN": str,
     },
     total=False,
 )
 
-
 class GetClipInputRequestTypeDef(
     _RequiredGetClipInputRequestTypeDef, _OptionalGetClipInputRequestTypeDef
 ):
     pass
 
-
 GetDASHStreamingSessionURLInputRequestTypeDef = TypedDict(
     "GetDASHStreamingSessionURLInputRequestTypeDef",
     {
         "StreamName": str,
         "StreamARN": str,
         "PlaybackMode": DASHPlaybackModeType,
         "DisplayFragmentTimestamp": DASHDisplayFragmentTimestampType,
@@ -359,15 +350,15 @@
 
 ListFragmentsInputListFragmentsPaginateTypeDef = TypedDict(
     "ListFragmentsInputListFragmentsPaginateTypeDef",
     {
         "StreamName": str,
         "StreamARN": str,
         "FragmentSelector": FragmentSelectorTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFragmentsInputRequestTypeDef = TypedDict(
     "ListFragmentsInputRequestTypeDef",
     {
```

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media/type_defs.pyi` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -39,34 +39,35 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ClipTimestampRangeTypeDef",
     "DASHTimestampRangeTypeDef",
     "TimestampRangeTypeDef",
     "FragmentTypeDef",
-    "ResponseMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetClipOutputTypeDef",
+    "GetDASHStreamingSessionURLOutputTypeDef",
+    "GetHLSStreamingSessionURLOutputTypeDef",
+    "GetImagesInputGetImagesPaginateTypeDef",
     "GetImagesInputRequestTypeDef",
     "ImageTypeDef",
     "GetMediaForFragmentListInputRequestTypeDef",
+    "GetMediaForFragmentListOutputTypeDef",
     "HLSTimestampRangeTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ClipFragmentSelectorTypeDef",
     "DASHFragmentSelectorTypeDef",
     "FragmentSelectorTypeDef",
-    "GetClipOutputTypeDef",
-    "GetDASHStreamingSessionURLOutputTypeDef",
-    "GetHLSStreamingSessionURLOutputTypeDef",
-    "GetMediaForFragmentListOutputTypeDef",
     "ListFragmentsOutputTypeDef",
-    "GetImagesInputGetImagesPaginateTypeDef",
     "GetImagesOutputTypeDef",
     "HLSFragmentSelectorTypeDef",
     "GetClipInputRequestTypeDef",
     "GetDASHStreamingSessionURLInputRequestTypeDef",
     "ListFragmentsInputListFragmentsPaginateTypeDef",
     "ListFragmentsInputRequestTypeDef",
     "GetHLSStreamingSessionURLInputRequestTypeDef",
@@ -105,35 +106,69 @@
         "ProducerTimestamp": datetime,
         "ServerTimestamp": datetime,
         "FragmentLengthInMilliseconds": int,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetClipOutputTypeDef = TypedDict(
+    "GetClipOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ContentType": str,
+        "Payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDASHStreamingSessionURLOutputTypeDef = TypedDict(
+    "GetDASHStreamingSessionURLOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DASHStreamingSessionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetHLSStreamingSessionURLOutputTypeDef = TypedDict(
+    "GetHLSStreamingSessionURLOutputTypeDef",
+    {
+        "HLSStreamingSessionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetImagesInputGetImagesPaginateTypeDef = TypedDict(
+    "_RequiredGetImagesInputGetImagesPaginateTypeDef",
+    {
+        "ImageSelectorType": ImageSelectorTypeType,
+        "StartTimestamp": Union[datetime, str],
+        "EndTimestamp": Union[datetime, str],
+        "SamplingInterval": int,
+        "Format": FormatType,
+    },
+)
+_OptionalGetImagesInputGetImagesPaginateTypeDef = TypedDict(
+    "_OptionalGetImagesInputGetImagesPaginateTypeDef",
+    {
+        "StreamName": str,
+        "StreamARN": str,
+        "FormatConfig": Mapping[Literal["JPEGQuality"], str],
+        "WidthPixels": int,
+        "HeightPixels": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetImagesInputGetImagesPaginateTypeDef(
+    _RequiredGetImagesInputGetImagesPaginateTypeDef, _OptionalGetImagesInputGetImagesPaginateTypeDef
+):
+    pass
+
+
 _RequiredGetImagesInputRequestTypeDef = TypedDict(
     "_RequiredGetImagesInputRequestTypeDef",
     {
         "ImageSelectorType": ImageSelectorTypeType,
         "StartTimestamp": Union[datetime, str],
         "EndTimestamp": Union[datetime, str],
         "SamplingInterval": int,
@@ -150,19 +185,21 @@
         "HeightPixels": int,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetImagesInputRequestTypeDef(
     _RequiredGetImagesInputRequestTypeDef, _OptionalGetImagesInputRequestTypeDef
 ):
     pass
 
+
 ImageTypeDef = TypedDict(
     "ImageTypeDef",
     {
         "TimeStamp": datetime,
         "Error": ImageErrorType,
         "ImageContent": str,
     },
@@ -180,29 +217,61 @@
     {
         "StreamName": str,
         "StreamARN": str,
     },
     total=False,
 )
 
+
 class GetMediaForFragmentListInputRequestTypeDef(
     _RequiredGetMediaForFragmentListInputRequestTypeDef,
     _OptionalGetMediaForFragmentListInputRequestTypeDef,
 ):
     pass
 
+
+GetMediaForFragmentListOutputTypeDef = TypedDict(
+    "GetMediaForFragmentListOutputTypeDef",
+    {
+        "ContentType": str,
+        "Payload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HLSTimestampRangeTypeDef = TypedDict(
     "HLSTimestampRangeTypeDef",
     {
         "StartTimestamp": Union[datetime, str],
         "EndTimestamp": Union[datetime, str],
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
 ClipFragmentSelectorTypeDef = TypedDict(
     "ClipFragmentSelectorTypeDef",
     {
         "FragmentSelectorType": ClipFragmentSelectorTypeType,
         "TimestampRange": ClipTimestampRangeTypeDef,
     },
 )
@@ -220,91 +289,29 @@
     "FragmentSelectorTypeDef",
     {
         "FragmentSelectorType": FragmentSelectorTypeType,
         "TimestampRange": TimestampRangeTypeDef,
     },
 )
 
-GetClipOutputTypeDef = TypedDict(
-    "GetClipOutputTypeDef",
-    {
-        "ContentType": str,
-        "Payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDASHStreamingSessionURLOutputTypeDef = TypedDict(
-    "GetDASHStreamingSessionURLOutputTypeDef",
-    {
-        "DASHStreamingSessionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetHLSStreamingSessionURLOutputTypeDef = TypedDict(
-    "GetHLSStreamingSessionURLOutputTypeDef",
-    {
-        "HLSStreamingSessionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMediaForFragmentListOutputTypeDef = TypedDict(
-    "GetMediaForFragmentListOutputTypeDef",
-    {
-        "ContentType": str,
-        "Payload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListFragmentsOutputTypeDef = TypedDict(
     "ListFragmentsOutputTypeDef",
     {
         "Fragments": List[FragmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetImagesInputGetImagesPaginateTypeDef = TypedDict(
-    "_RequiredGetImagesInputGetImagesPaginateTypeDef",
-    {
-        "ImageSelectorType": ImageSelectorTypeType,
-        "StartTimestamp": Union[datetime, str],
-        "EndTimestamp": Union[datetime, str],
-        "SamplingInterval": int,
-        "Format": FormatType,
-    },
-)
-_OptionalGetImagesInputGetImagesPaginateTypeDef = TypedDict(
-    "_OptionalGetImagesInputGetImagesPaginateTypeDef",
-    {
-        "StreamName": str,
-        "StreamARN": str,
-        "FormatConfig": Mapping[Literal["JPEGQuality"], str],
-        "WidthPixels": int,
-        "HeightPixels": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class GetImagesInputGetImagesPaginateTypeDef(
-    _RequiredGetImagesInputGetImagesPaginateTypeDef, _OptionalGetImagesInputGetImagesPaginateTypeDef
-):
-    pass
-
 GetImagesOutputTypeDef = TypedDict(
     "GetImagesOutputTypeDef",
     {
         "Images": List[ImageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HLSFragmentSelectorTypeDef = TypedDict(
     "HLSFragmentSelectorTypeDef",
     {
         "FragmentSelectorType": HLSFragmentSelectorTypeType,
@@ -324,19 +331,21 @@
     {
         "StreamName": str,
         "StreamARN": str,
     },
     total=False,
 )
 
+
 class GetClipInputRequestTypeDef(
     _RequiredGetClipInputRequestTypeDef, _OptionalGetClipInputRequestTypeDef
 ):
     pass
 
+
 GetDASHStreamingSessionURLInputRequestTypeDef = TypedDict(
     "GetDASHStreamingSessionURLInputRequestTypeDef",
     {
         "StreamName": str,
         "StreamARN": str,
         "PlaybackMode": DASHPlaybackModeType,
         "DisplayFragmentTimestamp": DASHDisplayFragmentTimestampType,
@@ -350,15 +359,15 @@
 
 ListFragmentsInputListFragmentsPaginateTypeDef = TypedDict(
     "ListFragmentsInputListFragmentsPaginateTypeDef",
     {
         "StreamName": str,
         "StreamARN": str,
         "FragmentSelector": FragmentSelectorTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFragmentsInputRequestTypeDef = TypedDict(
     "ListFragmentsInputRequestTypeDef",
     {
```

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/PKG-INFO` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesis-video-archived-media
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideoArchivedMedia 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesis-video-archived-media"></a>
 
 # types-aiobotocore-kinesis-video-archived-media
 
 [![PyPI - types-aiobotocore-kinesis-video-archived-media](https://img.shields.io/pypi/v/types-aiobotocore-kinesis-video-archived-media.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesis-video-archived-media.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesis-video-archived-media)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesis-video-archived-media?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesis-video-archived-media)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideoArchivedMedia 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
+[aiobotocore.KinesisVideoArchivedMedia 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesis-video-archived-media.html#KinesisVideoArchivedMedia)
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
 [types-aiobotocore-kinesis-video-archived-media docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesis_video_archived_media/).
 
 See how it helps to find and fix potential bugs:
 
@@ -343,29 +343,29 @@
 
 ```python
 from types_aiobotocore_kinesis_video_archived_media.type_defs import (
     ClipTimestampRangeTypeDef,
     DASHTimestampRangeTypeDef,
     TimestampRangeTypeDef,
     FragmentTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    GetClipOutputTypeDef,
+    GetDASHStreamingSessionURLOutputTypeDef,
+    GetHLSStreamingSessionURLOutputTypeDef,
+    GetImagesInputGetImagesPaginateTypeDef,
     GetImagesInputRequestTypeDef,
     ImageTypeDef,
     GetMediaForFragmentListInputRequestTypeDef,
+    GetMediaForFragmentListOutputTypeDef,
     HLSTimestampRangeTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ClipFragmentSelectorTypeDef,
     DASHFragmentSelectorTypeDef,
     FragmentSelectorTypeDef,
-    GetClipOutputTypeDef,
-    GetDASHStreamingSessionURLOutputTypeDef,
-    GetHLSStreamingSessionURLOutputTypeDef,
-    GetMediaForFragmentListOutputTypeDef,
     ListFragmentsOutputTypeDef,
-    GetImagesInputGetImagesPaginateTypeDef,
     GetImagesOutputTypeDef,
     HLSFragmentSelectorTypeDef,
     GetClipInputRequestTypeDef,
     GetDASHStreamingSessionURLInputRequestTypeDef,
     ListFragmentsInputListFragmentsPaginateTypeDef,
     ListFragmentsInputRequestTypeDef,
     GetHLSStreamingSessionURLInputRequestTypeDef,
@@ -379,43 +379,43 @@
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

### Comparing `types-aiobotocore-kinesis-video-archived-media-2.5.0.post1/types_aiobotocore_kinesis_video_archived_media.egg-info/SOURCES.txt` & `types-aiobotocore-kinesis-video-archived-media-2.5.1/types_aiobotocore_kinesis_video_archived_media.egg-info/SOURCES.txt`

 * *Files identical despite different names*

