# Comparing `tmp/types-aiobotocore-ivs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ivs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ivs-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:49 2023, max compression
+gzip compressed data, was "types-aiobotocore-ivs-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-ivs-2.5.0.post1.tar` & `types-aiobotocore-ivs-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.079321 types-aiobotocore-ivs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16459 2023-03-11 12:26:49.079321 types-aiobotocore-ivs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14904 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:49.079321 types-aiobotocore-ivs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:16:39.000000 types-aiobotocore-ivs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.079321 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/
--rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1490 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23002 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22960 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8653 2023-03-11 12:16:41.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8651 2023-03-11 12:16:41.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6586 2023-03-11 12:16:41.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6578 2023-03-11 12:16:41.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    23285 2023-03-11 12:16:41.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    23264 2023-03-11 12:16:41.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:40.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.079321 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16459 2023-03-11 12:26:48.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:48.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:48.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:48.000000 types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.498157 types-aiobotocore-ivs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16472 2023-06-28 01:43:40.498157 types-aiobotocore-ivs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14923 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.498157 types-aiobotocore-ivs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.494157 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1490 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23181 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23139 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9012 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9010 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6476 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6469 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    23679 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23658 2023-06-28 01:33:19.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:18.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.498157 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16472 2023-06-28 01:43:40.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:40.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:40.000000 types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/LICENSE` & `types-aiobotocore-ivs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ivs-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ivs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IVS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IVS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ivs"></a>
 
 # types-aiobotocore-ivs
 
 [![PyPI - types-aiobotocore-ivs](https://img.shields.io/pypi/v/types-aiobotocore-ivs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ivs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ivs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ivs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IVS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
+[aiobotocore.IVS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
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
 [types-aiobotocore-ivs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,14 +315,15 @@
     ListRecordingConfigurationsPaginatorName,
     ListStreamKeysPaginatorName,
     ListStreamsPaginatorName,
     RecordingConfigurationStateType,
     RecordingModeType,
     StreamHealthType,
     StreamStateType,
+    TranscodePresetType,
     IVSServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -340,73 +341,73 @@
 
 ```python
 from types_aiobotocore_ivs.type_defs import (
     AudioConfigurationTypeDef,
     BatchErrorTypeDef,
     BatchGetChannelRequestRequestTypeDef,
     ChannelTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetStreamKeyRequestRequestTypeDef,
     StreamKeyTypeDef,
     ChannelSummaryTypeDef,
     CreateChannelRequestRequestTypeDef,
     ThumbnailConfigurationTypeDef,
     CreateStreamKeyRequestRequestTypeDef,
     DeleteChannelRequestRequestTypeDef,
     DeletePlaybackKeyPairRequestRequestTypeDef,
     DeleteRecordingConfigurationRequestRequestTypeDef,
     DeleteStreamKeyRequestRequestTypeDef,
     S3DestinationConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelRequestRequestTypeDef,
     GetPlaybackKeyPairRequestRequestTypeDef,
     PlaybackKeyPairTypeDef,
     GetRecordingConfigurationRequestRequestTypeDef,
     GetStreamKeyRequestRequestTypeDef,
     GetStreamRequestRequestTypeDef,
     StreamTypeDef,
     GetStreamSessionRequestRequestTypeDef,
     ImportPlaybackKeyPairRequestRequestTypeDef,
     VideoConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef,
     ListPlaybackKeyPairsRequestRequestTypeDef,
     PlaybackKeyPairSummaryTypeDef,
+    ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef,
     ListRecordingConfigurationsRequestRequestTypeDef,
+    ListStreamKeysRequestListStreamKeysPaginateTypeDef,
     ListStreamKeysRequestRequestTypeDef,
     StreamKeySummaryTypeDef,
     ListStreamSessionsRequestRequestTypeDef,
     StreamSessionSummaryTypeDef,
     StreamFiltersTypeDef,
     StreamSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutMetadataRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StopStreamRequestRequestTypeDef,
     StreamEventTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
     BatchGetChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetChannelResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateChannelResponseTypeDef,
     BatchGetStreamKeyResponseTypeDef,
     CreateChannelResponseTypeDef,
     CreateStreamKeyResponseTypeDef,
     GetStreamKeyResponseTypeDef,
     ListChannelsResponseTypeDef,
     DestinationConfigurationTypeDef,
     GetPlaybackKeyPairResponseTypeDef,
     ImportPlaybackKeyPairResponseTypeDef,
     GetStreamResponseTypeDef,
     IngestConfigurationTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef,
-    ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef,
-    ListStreamKeysRequestListStreamKeysPaginateTypeDef,
     ListPlaybackKeyPairsResponseTypeDef,
     ListStreamKeysResponseTypeDef,
     ListStreamSessionsResponseTypeDef,
     ListStreamsRequestListStreamsPaginateTypeDef,
     ListStreamsRequestRequestTypeDef,
     ListStreamsResponseTypeDef,
     CreateRecordingConfigurationRequestRequestTypeDef,
@@ -427,43 +428,43 @@
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/README.md` & `types-aiobotocore-ivs-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ivs"></a>
 
 # types-aiobotocore-ivs
 
 [![PyPI - types-aiobotocore-ivs](https://img.shields.io/pypi/v/types-aiobotocore-ivs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ivs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ivs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ivs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IVS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
+[aiobotocore.IVS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
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
 [types-aiobotocore-ivs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -282,14 +282,15 @@
     ListRecordingConfigurationsPaginatorName,
     ListStreamKeysPaginatorName,
     ListStreamsPaginatorName,
     RecordingConfigurationStateType,
     RecordingModeType,
     StreamHealthType,
     StreamStateType,
+    TranscodePresetType,
     IVSServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -307,73 +308,73 @@
 
 ```python
 from types_aiobotocore_ivs.type_defs import (
     AudioConfigurationTypeDef,
     BatchErrorTypeDef,
     BatchGetChannelRequestRequestTypeDef,
     ChannelTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetStreamKeyRequestRequestTypeDef,
     StreamKeyTypeDef,
     ChannelSummaryTypeDef,
     CreateChannelRequestRequestTypeDef,
     ThumbnailConfigurationTypeDef,
     CreateStreamKeyRequestRequestTypeDef,
     DeleteChannelRequestRequestTypeDef,
     DeletePlaybackKeyPairRequestRequestTypeDef,
     DeleteRecordingConfigurationRequestRequestTypeDef,
     DeleteStreamKeyRequestRequestTypeDef,
     S3DestinationConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelRequestRequestTypeDef,
     GetPlaybackKeyPairRequestRequestTypeDef,
     PlaybackKeyPairTypeDef,
     GetRecordingConfigurationRequestRequestTypeDef,
     GetStreamKeyRequestRequestTypeDef,
     GetStreamRequestRequestTypeDef,
     StreamTypeDef,
     GetStreamSessionRequestRequestTypeDef,
     ImportPlaybackKeyPairRequestRequestTypeDef,
     VideoConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef,
     ListPlaybackKeyPairsRequestRequestTypeDef,
     PlaybackKeyPairSummaryTypeDef,
+    ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef,
     ListRecordingConfigurationsRequestRequestTypeDef,
+    ListStreamKeysRequestListStreamKeysPaginateTypeDef,
     ListStreamKeysRequestRequestTypeDef,
     StreamKeySummaryTypeDef,
     ListStreamSessionsRequestRequestTypeDef,
     StreamSessionSummaryTypeDef,
     StreamFiltersTypeDef,
     StreamSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutMetadataRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StopStreamRequestRequestTypeDef,
     StreamEventTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
     BatchGetChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetChannelResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateChannelResponseTypeDef,
     BatchGetStreamKeyResponseTypeDef,
     CreateChannelResponseTypeDef,
     CreateStreamKeyResponseTypeDef,
     GetStreamKeyResponseTypeDef,
     ListChannelsResponseTypeDef,
     DestinationConfigurationTypeDef,
     GetPlaybackKeyPairResponseTypeDef,
     ImportPlaybackKeyPairResponseTypeDef,
     GetStreamResponseTypeDef,
     IngestConfigurationTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef,
-    ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef,
-    ListStreamKeysRequestListStreamKeysPaginateTypeDef,
     ListPlaybackKeyPairsResponseTypeDef,
     ListStreamKeysResponseTypeDef,
     ListStreamSessionsResponseTypeDef,
     ListStreamsRequestListStreamsPaginateTypeDef,
     ListStreamsRequestRequestTypeDef,
     ListStreamsResponseTypeDef,
     CreateRecordingConfigurationRequestRequestTypeDef,
@@ -394,43 +395,43 @@
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/setup.py` & `types-aiobotocore-ivs-2.5.1/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ivs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ivs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ivs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IVS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.IVS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/",
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/__init__.py` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/__init__.pyi` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/__main__.py` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IVS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IVS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS\nOther"
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/client.py` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import ChannelLatencyModeType, ChannelTypeType
+from .literals import ChannelLatencyModeType, ChannelTypeType, TranscodePresetType
 from .paginator import (
     ListChannelsPaginator,
     ListPlaybackKeyPairsPaginator,
     ListRecordingConfigurationsPaginator,
     ListStreamKeysPaginator,
     ListStreamsPaginator,
 )
@@ -56,40 +56,36 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("IVSClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ChannelNotBroadcasting: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     PendingVerification: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     StreamUnavailable: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class IVSClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/)
     """
 
     meta: ClientMeta
@@ -98,66 +94,62 @@
     def exceptions(self) -> Exceptions:
         """
         IVSClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#exceptions)
         """
-
     async def batch_get_channel(self, *, arns: Sequence[str]) -> BatchGetChannelResponseTypeDef:
         """
         Performs  GetChannel on multiple ARNs simultaneously.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.batch_get_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#batch_get_channel)
         """
-
     async def batch_get_stream_key(
         self, *, arns: Sequence[str]
     ) -> BatchGetStreamKeyResponseTypeDef:
         """
         Performs  GetStreamKey on multiple ARNs simultaneously.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.batch_get_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#batch_get_stream_key)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#close)
         """
-
     async def create_channel(
         self,
         *,
         authorized: bool = ...,
+        insecureIngest: bool = ...,
         latencyMode: ChannelLatencyModeType = ...,
         name: str = ...,
+        preset: TranscodePresetType = ...,
         recordingConfigurationArn: str = ...,
         tags: Mapping[str, str] = ...,
         type: ChannelTypeType = ...
     ) -> CreateChannelResponseTypeDef:
         """
         Creates a new channel and an associated stream key to start streaming.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#create_channel)
         """
-
     async def create_recording_configuration(
         self,
         *,
         destinationConfiguration: DestinationConfigurationTypeDef,
         name: str = ...,
         recordingReconnectWindowSeconds: int = ...,
         tags: Mapping[str, str] = ...,
@@ -165,136 +157,122 @@
     ) -> CreateRecordingConfigurationResponseTypeDef:
         """
         Creates a new recording configuration, used to enable recording to Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_recording_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#create_recording_configuration)
         """
-
     async def create_stream_key(
         self, *, channelArn: str, tags: Mapping[str, str] = ...
     ) -> CreateStreamKeyResponseTypeDef:
         """
         Creates a stream key, used to initiate a stream, for the specified channel ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#create_stream_key)
         """
-
     async def delete_channel(self, *, arn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified channel and its associated stream keys.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_channel)
         """
-
     async def delete_playback_key_pair(self, *, arn: str) -> Dict[str, Any]:
         """
         Deletes a specified authorization key pair.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_playback_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_playback_key_pair)
         """
-
     async def delete_recording_configuration(self, *, arn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the recording configuration for the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_recording_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_recording_configuration)
         """
-
     async def delete_stream_key(self, *, arn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the stream key for the specified ARN, so it can no longer be used to
         stream.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_stream_key)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#generate_presigned_url)
         """
-
     async def get_channel(self, *, arn: str) -> GetChannelResponseTypeDef:
         """
         Gets the channel configuration for the specified channel ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_channel)
         """
-
     async def get_playback_key_pair(self, *, arn: str) -> GetPlaybackKeyPairResponseTypeDef:
         """
         Gets a specified playback authorization key pair and returns the `arn` and
         `fingerprint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_playback_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_playback_key_pair)
         """
-
     async def get_recording_configuration(
         self, *, arn: str
     ) -> GetRecordingConfigurationResponseTypeDef:
         """
         Gets the recording configuration for the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_recording_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_recording_configuration)
         """
-
     async def get_stream(self, *, channelArn: str) -> GetStreamResponseTypeDef:
         """
         Gets information about the active (live) stream on a specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_stream)
         """
-
     async def get_stream_key(self, *, arn: str) -> GetStreamKeyResponseTypeDef:
         """
         Gets stream-key information for a specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_stream_key)
         """
-
     async def get_stream_session(
         self, *, channelArn: str, streamId: str = ...
     ) -> GetStreamSessionResponseTypeDef:
         """
         Gets metadata on a specified stream.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_stream_session)
         """
-
     async def import_playback_key_pair(
         self, *, publicKeyMaterial: str, name: str = ..., tags: Mapping[str, str] = ...
     ) -> ImportPlaybackKeyPairResponseTypeDef:
         """
         Imports the public portion of a new key pair and returns its `arn` and
         `fingerprint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.import_playback_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#import_playback_key_pair)
         """
-
     async def list_channels(
         self,
         *,
         filterByName: str = ...,
         filterByRecordingConfigurationArn: str = ...,
         maxResults: int = ...,
         nextToken: str = ...
@@ -302,171 +280,155 @@
         """
         Gets summary information about all channels in your account, in the Amazon Web
         Services region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_channels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_channels)
         """
-
     async def list_playback_key_pairs(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListPlaybackKeyPairsResponseTypeDef:
         """
         Gets summary information about playback key pairs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_playback_key_pairs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_playback_key_pairs)
         """
-
     async def list_recording_configurations(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListRecordingConfigurationsResponseTypeDef:
         """
         Gets summary information about all recording configurations in your account, in
         the Amazon Web Services region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_recording_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_recording_configurations)
         """
-
     async def list_stream_keys(
         self, *, channelArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListStreamKeysResponseTypeDef:
         """
         Gets summary information about stream keys for the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_stream_keys)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_stream_keys)
         """
-
     async def list_stream_sessions(
         self, *, channelArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListStreamSessionsResponseTypeDef:
         """
         Gets a summary of current and previous streams for a specified channel in your
         account, in the AWS region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_stream_sessions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_stream_sessions)
         """
-
     async def list_streams(
         self, *, filterBy: StreamFiltersTypeDef = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListStreamsResponseTypeDef:
         """
         Gets summary information about live streams in your account, in the Amazon Web
         Services region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_streams)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_streams)
         """
-
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Gets information about Amazon Web Services tags for the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_tags_for_resource)
         """
-
     async def put_metadata(self, *, channelArn: str, metadata: str) -> EmptyResponseMetadataTypeDef:
         """
         Inserts metadata into the active stream of the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.put_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#put_metadata)
         """
-
     async def stop_stream(self, *, channelArn: str) -> Dict[str, Any]:
         """
         Disconnects the incoming RTMPS stream for the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.stop_stream)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#stop_stream)
         """
-
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Adds or updates tags for the Amazon Web Services resource with the specified
         ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#tag_resource)
         """
-
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from the resource with the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#untag_resource)
         """
-
     async def update_channel(
         self,
         *,
         arn: str,
         authorized: bool = ...,
+        insecureIngest: bool = ...,
         latencyMode: ChannelLatencyModeType = ...,
         name: str = ...,
+        preset: TranscodePresetType = ...,
         recordingConfigurationArn: str = ...,
         type: ChannelTypeType = ...
     ) -> UpdateChannelResponseTypeDef:
         """
         Updates a channel's configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.update_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#update_channel)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_channels"]) -> ListChannelsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_playback_key_pairs"]
     ) -> ListPlaybackKeyPairsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_recording_configurations"]
     ) -> ListRecordingConfigurationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_stream_keys"]) -> ListStreamKeysPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_streams"]) -> ListStreamsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "IVSClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/)
         """
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/client.pyi` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/client.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 """
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import ChannelLatencyModeType, ChannelTypeType
+from .literals import ChannelLatencyModeType, ChannelTypeType, TranscodePresetType
 from .paginator import (
     ListChannelsPaginator,
     ListPlaybackKeyPairsPaginator,
     ListRecordingConfigurationsPaginator,
     ListStreamKeysPaginator,
     ListStreamsPaginator,
 )
@@ -56,36 +56,40 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("IVSClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ChannelNotBroadcasting: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     PendingVerification: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     StreamUnavailable: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class IVSClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/)
     """
 
     meta: ClientMeta
@@ -94,60 +98,68 @@
     def exceptions(self) -> Exceptions:
         """
         IVSClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#exceptions)
         """
+
     async def batch_get_channel(self, *, arns: Sequence[str]) -> BatchGetChannelResponseTypeDef:
         """
         Performs  GetChannel on multiple ARNs simultaneously.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.batch_get_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#batch_get_channel)
         """
+
     async def batch_get_stream_key(
         self, *, arns: Sequence[str]
     ) -> BatchGetStreamKeyResponseTypeDef:
         """
         Performs  GetStreamKey on multiple ARNs simultaneously.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.batch_get_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#batch_get_stream_key)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#close)
         """
+
     async def create_channel(
         self,
         *,
         authorized: bool = ...,
+        insecureIngest: bool = ...,
         latencyMode: ChannelLatencyModeType = ...,
         name: str = ...,
+        preset: TranscodePresetType = ...,
         recordingConfigurationArn: str = ...,
         tags: Mapping[str, str] = ...,
         type: ChannelTypeType = ...
     ) -> CreateChannelResponseTypeDef:
         """
         Creates a new channel and an associated stream key to start streaming.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#create_channel)
         """
+
     async def create_recording_configuration(
         self,
         *,
         destinationConfiguration: DestinationConfigurationTypeDef,
         name: str = ...,
         recordingReconnectWindowSeconds: int = ...,
         tags: Mapping[str, str] = ...,
@@ -155,122 +167,136 @@
     ) -> CreateRecordingConfigurationResponseTypeDef:
         """
         Creates a new recording configuration, used to enable recording to Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_recording_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#create_recording_configuration)
         """
+
     async def create_stream_key(
         self, *, channelArn: str, tags: Mapping[str, str] = ...
     ) -> CreateStreamKeyResponseTypeDef:
         """
         Creates a stream key, used to initiate a stream, for the specified channel ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.create_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#create_stream_key)
         """
+
     async def delete_channel(self, *, arn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified channel and its associated stream keys.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_channel)
         """
+
     async def delete_playback_key_pair(self, *, arn: str) -> Dict[str, Any]:
         """
         Deletes a specified authorization key pair.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_playback_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_playback_key_pair)
         """
+
     async def delete_recording_configuration(self, *, arn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the recording configuration for the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_recording_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_recording_configuration)
         """
+
     async def delete_stream_key(self, *, arn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the stream key for the specified ARN, so it can no longer be used to
         stream.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.delete_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#delete_stream_key)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#generate_presigned_url)
         """
+
     async def get_channel(self, *, arn: str) -> GetChannelResponseTypeDef:
         """
         Gets the channel configuration for the specified channel ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_channel)
         """
+
     async def get_playback_key_pair(self, *, arn: str) -> GetPlaybackKeyPairResponseTypeDef:
         """
         Gets a specified playback authorization key pair and returns the `arn` and
         `fingerprint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_playback_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_playback_key_pair)
         """
+
     async def get_recording_configuration(
         self, *, arn: str
     ) -> GetRecordingConfigurationResponseTypeDef:
         """
         Gets the recording configuration for the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_recording_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_recording_configuration)
         """
+
     async def get_stream(self, *, channelArn: str) -> GetStreamResponseTypeDef:
         """
         Gets information about the active (live) stream on a specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_stream)
         """
+
     async def get_stream_key(self, *, arn: str) -> GetStreamKeyResponseTypeDef:
         """
         Gets stream-key information for a specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_stream_key)
         """
+
     async def get_stream_session(
         self, *, channelArn: str, streamId: str = ...
     ) -> GetStreamSessionResponseTypeDef:
         """
         Gets metadata on a specified stream.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_stream_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_stream_session)
         """
+
     async def import_playback_key_pair(
         self, *, publicKeyMaterial: str, name: str = ..., tags: Mapping[str, str] = ...
     ) -> ImportPlaybackKeyPairResponseTypeDef:
         """
         Imports the public portion of a new key pair and returns its `arn` and
         `fingerprint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.import_playback_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#import_playback_key_pair)
         """
+
     async def list_channels(
         self,
         *,
         filterByName: str = ...,
         filterByRecordingConfigurationArn: str = ...,
         maxResults: int = ...,
         nextToken: str = ...
@@ -278,153 +304,173 @@
         """
         Gets summary information about all channels in your account, in the Amazon Web
         Services region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_channels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_channels)
         """
+
     async def list_playback_key_pairs(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListPlaybackKeyPairsResponseTypeDef:
         """
         Gets summary information about playback key pairs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_playback_key_pairs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_playback_key_pairs)
         """
+
     async def list_recording_configurations(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListRecordingConfigurationsResponseTypeDef:
         """
         Gets summary information about all recording configurations in your account, in
         the Amazon Web Services region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_recording_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_recording_configurations)
         """
+
     async def list_stream_keys(
         self, *, channelArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListStreamKeysResponseTypeDef:
         """
         Gets summary information about stream keys for the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_stream_keys)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_stream_keys)
         """
+
     async def list_stream_sessions(
         self, *, channelArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListStreamSessionsResponseTypeDef:
         """
         Gets a summary of current and previous streams for a specified channel in your
         account, in the AWS region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_stream_sessions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_stream_sessions)
         """
+
     async def list_streams(
         self, *, filterBy: StreamFiltersTypeDef = ..., maxResults: int = ..., nextToken: str = ...
     ) -> ListStreamsResponseTypeDef:
         """
         Gets summary information about live streams in your account, in the Amazon Web
         Services region where the API request is processed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_streams)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_streams)
         """
+
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Gets information about Amazon Web Services tags for the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#list_tags_for_resource)
         """
+
     async def put_metadata(self, *, channelArn: str, metadata: str) -> EmptyResponseMetadataTypeDef:
         """
         Inserts metadata into the active stream of the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.put_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#put_metadata)
         """
+
     async def stop_stream(self, *, channelArn: str) -> Dict[str, Any]:
         """
         Disconnects the incoming RTMPS stream for the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.stop_stream)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#stop_stream)
         """
+
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Adds or updates tags for the Amazon Web Services resource with the specified
         ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#tag_resource)
         """
+
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from the resource with the specified ARN.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#untag_resource)
         """
+
     async def update_channel(
         self,
         *,
         arn: str,
         authorized: bool = ...,
+        insecureIngest: bool = ...,
         latencyMode: ChannelLatencyModeType = ...,
         name: str = ...,
+        preset: TranscodePresetType = ...,
         recordingConfigurationArn: str = ...,
         type: ChannelTypeType = ...
     ) -> UpdateChannelResponseTypeDef:
         """
         Updates a channel's configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.update_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#update_channel)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_channels"]) -> ListChannelsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_playback_key_pairs"]
     ) -> ListPlaybackKeyPairsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_recording_configurations"]
     ) -> ListRecordingConfigurationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_stream_keys"]) -> ListStreamKeysPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_streams"]) -> ListStreamsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "IVSClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/client/)
         """
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/literals.py` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -27,33 +27,35 @@
     "ListRecordingConfigurationsPaginatorName",
     "ListStreamKeysPaginatorName",
     "ListStreamsPaginatorName",
     "RecordingConfigurationStateType",
     "RecordingModeType",
     "StreamHealthType",
     "StreamStateType",
+    "TranscodePresetType",
     "IVSServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 ChannelLatencyModeType = Literal["LOW", "NORMAL"]
-ChannelTypeType = Literal["BASIC", "STANDARD"]
+ChannelTypeType = Literal["ADVANCED_HD", "ADVANCED_SD", "BASIC", "STANDARD"]
 ListChannelsPaginatorName = Literal["list_channels"]
 ListPlaybackKeyPairsPaginatorName = Literal["list_playback_key_pairs"]
 ListRecordingConfigurationsPaginatorName = Literal["list_recording_configurations"]
 ListStreamKeysPaginatorName = Literal["list_stream_keys"]
 ListStreamsPaginatorName = Literal["list_streams"]
 RecordingConfigurationStateType = Literal["ACTIVE", "CREATE_FAILED", "CREATING"]
 RecordingModeType = Literal["DISABLED", "INTERVAL"]
 StreamHealthType = Literal["HEALTHY", "STARVING", "UNKNOWN"]
 StreamStateType = Literal["LIVE", "OFFLINE"]
+TranscodePresetType = Literal["CONSTRAINED_BANDWIDTH_DELIVERY", "HIGHER_BANDWIDTH_DELIVERY"]
 IVSServiceName = Literal["ivs"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -109,14 +111,15 @@
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
@@ -195,14 +198,15 @@
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
@@ -213,14 +217,15 @@
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
@@ -256,14 +261,15 @@
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
@@ -282,16 +288,19 @@
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
@@ -375,15 +384,17 @@
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/literals.pyi` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -26,32 +26,34 @@
     "ListRecordingConfigurationsPaginatorName",
     "ListStreamKeysPaginatorName",
     "ListStreamsPaginatorName",
     "RecordingConfigurationStateType",
     "RecordingModeType",
     "StreamHealthType",
     "StreamStateType",
+    "TranscodePresetType",
     "IVSServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 ChannelLatencyModeType = Literal["LOW", "NORMAL"]
-ChannelTypeType = Literal["BASIC", "STANDARD"]
+ChannelTypeType = Literal["ADVANCED_HD", "ADVANCED_SD", "BASIC", "STANDARD"]
 ListChannelsPaginatorName = Literal["list_channels"]
 ListPlaybackKeyPairsPaginatorName = Literal["list_playback_key_pairs"]
 ListRecordingConfigurationsPaginatorName = Literal["list_recording_configurations"]
 ListStreamKeysPaginatorName = Literal["list_stream_keys"]
 ListStreamsPaginatorName = Literal["list_streams"]
 RecordingConfigurationStateType = Literal["ACTIVE", "CREATE_FAILED", "CREATING"]
 RecordingModeType = Literal["DISABLED", "INTERVAL"]
 StreamHealthType = Literal["HEALTHY", "STARVING", "UNKNOWN"]
 StreamStateType = Literal["LIVE", "OFFLINE"]
+TranscodePresetType = Literal["CONSTRAINED_BANDWIDTH_DELIVERY", "HIGHER_BANDWIDTH_DELIVERY"]
 IVSServiceName = Literal["ivs"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -107,14 +109,15 @@
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
@@ -193,14 +196,15 @@
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
@@ -211,14 +215,15 @@
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
@@ -254,14 +259,15 @@
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
@@ -280,16 +286,19 @@
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
@@ -373,15 +382,17 @@
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/paginator.py` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,36 +24,29 @@
         list_channels_paginator: ListChannelsPaginator = client.get_paginator("list_channels")
         list_playback_key_pairs_paginator: ListPlaybackKeyPairsPaginator = client.get_paginator("list_playback_key_pairs")
         list_recording_configurations_paginator: ListRecordingConfigurationsPaginator = client.get_paginator("list_recording_configurations")
         list_stream_keys_paginator: ListStreamKeysPaginator = client.get_paginator("list_stream_keys")
         list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChannelsResponseTypeDef,
     ListPlaybackKeyPairsResponseTypeDef,
     ListRecordingConfigurationsResponseTypeDef,
     ListStreamKeysResponseTypeDef,
     ListStreamsResponseTypeDef,
     PaginatorConfigTypeDef,
     StreamFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListChannelsPaginator",
     "ListPlaybackKeyPairsPaginator",
     "ListRecordingConfigurationsPaginator",
     "ListStreamKeysPaginator",
     "ListStreamsPaginator",
 )
@@ -76,60 +69,60 @@
     """
 
     def paginate(
         self,
         *,
         filterByName: str = ...,
         filterByRecordingConfigurationArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listchannelspaginator)
         """
 
 
 class ListPlaybackKeyPairsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListPlaybackKeyPairs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listplaybackkeypairspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlaybackKeyPairsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListPlaybackKeyPairs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listplaybackkeypairspaginator)
         """
 
 
 class ListRecordingConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListRecordingConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listrecordingconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecordingConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListRecordingConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listrecordingconfigurationspaginator)
         """
 
 
 class ListStreamKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListStreamKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamkeyspaginator)
     """
 
     def paginate(
-        self, *, channelArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, channelArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListStreamKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamkeyspaginator)
         """
 
 
@@ -139,13 +132,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamspaginator)
     """
 
     def paginate(
         self,
         *,
         filterBy: StreamFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamspaginator)
         """
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/paginator.pyi` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,29 @@
         list_channels_paginator: ListChannelsPaginator = client.get_paginator("list_channels")
         list_playback_key_pairs_paginator: ListPlaybackKeyPairsPaginator = client.get_paginator("list_playback_key_pairs")
         list_recording_configurations_paginator: ListRecordingConfigurationsPaginator = client.get_paginator("list_recording_configurations")
         list_stream_keys_paginator: ListStreamKeysPaginator = client.get_paginator("list_stream_keys")
         list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChannelsResponseTypeDef,
     ListPlaybackKeyPairsResponseTypeDef,
     ListRecordingConfigurationsResponseTypeDef,
     ListStreamKeysResponseTypeDef,
     ListStreamsResponseTypeDef,
     PaginatorConfigTypeDef,
     StreamFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListChannelsPaginator",
     "ListPlaybackKeyPairsPaginator",
     "ListRecordingConfigurationsPaginator",
     "ListStreamKeysPaginator",
     "ListStreamsPaginator",
 )
@@ -72,57 +66,57 @@
     """
 
     def paginate(
         self,
         *,
         filterByName: str = ...,
         filterByRecordingConfigurationArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listchannelspaginator)
         """
 
 class ListPlaybackKeyPairsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListPlaybackKeyPairs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listplaybackkeypairspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlaybackKeyPairsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListPlaybackKeyPairs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listplaybackkeypairspaginator)
         """
 
 class ListRecordingConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListRecordingConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listrecordingconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecordingConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListRecordingConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#listrecordingconfigurationspaginator)
         """
 
 class ListStreamKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListStreamKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamkeyspaginator)
     """
 
     def paginate(
-        self, *, channelArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, channelArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListStreamKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamkeyspaginator)
         """
 
 class ListStreamsPaginator(AioPaginator):
@@ -131,13 +125,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamspaginator)
     """
 
     def paginate(
         self,
         *,
         filterBy: StreamFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS.Paginator.ListStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/paginators/#liststreamspaginator)
         """
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/type_defs.py` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,86 +18,87 @@
 from .literals import (
     ChannelLatencyModeType,
     ChannelTypeType,
     RecordingConfigurationStateType,
     RecordingModeType,
     StreamHealthType,
     StreamStateType,
+    TranscodePresetType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AudioConfigurationTypeDef",
     "BatchErrorTypeDef",
     "BatchGetChannelRequestRequestTypeDef",
     "ChannelTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetStreamKeyRequestRequestTypeDef",
     "StreamKeyTypeDef",
     "ChannelSummaryTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "ThumbnailConfigurationTypeDef",
     "CreateStreamKeyRequestRequestTypeDef",
     "DeleteChannelRequestRequestTypeDef",
     "DeletePlaybackKeyPairRequestRequestTypeDef",
     "DeleteRecordingConfigurationRequestRequestTypeDef",
     "DeleteStreamKeyRequestRequestTypeDef",
     "S3DestinationConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChannelRequestRequestTypeDef",
     "GetPlaybackKeyPairRequestRequestTypeDef",
     "PlaybackKeyPairTypeDef",
     "GetRecordingConfigurationRequestRequestTypeDef",
     "GetStreamKeyRequestRequestTypeDef",
     "GetStreamRequestRequestTypeDef",
     "StreamTypeDef",
     "GetStreamSessionRequestRequestTypeDef",
     "ImportPlaybackKeyPairRequestRequestTypeDef",
     "VideoConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
     "ListPlaybackKeyPairsRequestRequestTypeDef",
     "PlaybackKeyPairSummaryTypeDef",
+    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
     "ListRecordingConfigurationsRequestRequestTypeDef",
+    "ListStreamKeysRequestListStreamKeysPaginateTypeDef",
     "ListStreamKeysRequestRequestTypeDef",
     "StreamKeySummaryTypeDef",
     "ListStreamSessionsRequestRequestTypeDef",
     "StreamSessionSummaryTypeDef",
     "StreamFiltersTypeDef",
     "StreamSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutMetadataRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StopStreamRequestRequestTypeDef",
     "StreamEventTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateChannelRequestRequestTypeDef",
     "BatchGetChannelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetChannelResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateChannelResponseTypeDef",
     "BatchGetStreamKeyResponseTypeDef",
     "CreateChannelResponseTypeDef",
     "CreateStreamKeyResponseTypeDef",
     "GetStreamKeyResponseTypeDef",
     "ListChannelsResponseTypeDef",
     "DestinationConfigurationTypeDef",
     "GetPlaybackKeyPairResponseTypeDef",
     "ImportPlaybackKeyPairResponseTypeDef",
     "GetStreamResponseTypeDef",
     "IngestConfigurationTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
-    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
-    "ListStreamKeysRequestListStreamKeysPaginateTypeDef",
     "ListPlaybackKeyPairsResponseTypeDef",
     "ListStreamKeysResponseTypeDef",
     "ListStreamSessionsResponseTypeDef",
     "ListStreamsRequestListStreamsPaginateTypeDef",
     "ListStreamsRequestRequestTypeDef",
     "ListStreamsResponseTypeDef",
     "CreateRecordingConfigurationRequestRequestTypeDef",
@@ -140,35 +141,26 @@
 
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "arn": str,
         "authorized": bool,
         "ingestEndpoint": str,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
         "playbackUrl": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "tags": Dict[str, str],
         "type": ChannelTypeType,
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
 BatchGetStreamKeyRequestRequestTypeDef = TypedDict(
     "BatchGetStreamKeyRequestRequestTypeDef",
     {
         "arns": Sequence[str],
     },
 )
 
@@ -184,28 +176,33 @@
 )
 
 ChannelSummaryTypeDef = TypedDict(
     "ChannelSummaryTypeDef",
     {
         "arn": str,
         "authorized": bool,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "tags": Dict[str, str],
+        "type": ChannelTypeType,
     },
     total=False,
 )
 
 CreateChannelRequestRequestTypeDef = TypedDict(
     "CreateChannelRequestRequestTypeDef",
     {
         "authorized": bool,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "tags": Mapping[str, str],
         "type": ChannelTypeType,
     },
     total=False,
 )
 
@@ -270,14 +267,21 @@
 S3DestinationConfigurationTypeDef = TypedDict(
     "S3DestinationConfigurationTypeDef",
     {
         "bucketName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChannelRequestRequestTypeDef = TypedDict(
     "GetChannelRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -389,20 +393,20 @@
         "targetFramerate": int,
         "videoHeight": int,
         "videoWidth": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "filterByName": str,
+        "filterByRecordingConfigurationArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
@@ -410,14 +414,22 @@
         "filterByRecordingConfigurationArn": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef = TypedDict(
+    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPlaybackKeyPairsRequestRequestTypeDef = TypedDict(
     "ListPlaybackKeyPairsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -429,23 +441,53 @@
         "arn": str,
         "name": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef = TypedDict(
+    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecordingConfigurationsRequestRequestTypeDef = TypedDict(
     "ListRecordingConfigurationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
+    "_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef",
+    {
+        "channelArn": str,
+    },
+)
+_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
+    "_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStreamKeysRequestListStreamKeysPaginateTypeDef(
+    _RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef,
+    _OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStreamKeysRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamKeysRequestRequestTypeDef",
     {
         "channelArn": str,
     },
 )
 _OptionalListStreamKeysRequestRequestTypeDef = TypedDict(
@@ -532,22 +574,51 @@
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
 PutMetadataRequestRequestTypeDef = TypedDict(
     "PutMetadataRequestRequestTypeDef",
     {
         "channelArn": str,
         "metadata": str,
     },
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
 StopStreamRequestRequestTypeDef = TypedDict(
     "StopStreamRequestRequestTypeDef",
     {
         "channelArn": str,
     },
 )
 
@@ -583,16 +654,18 @@
         "arn": str,
     },
 )
 _OptionalUpdateChannelRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateChannelRequestRequestTypeDef",
     {
         "authorized": bool,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "type": ChannelTypeType,
     },
     total=False,
 )
 
 
@@ -603,89 +676,74 @@
 
 
 BatchGetChannelResponseTypeDef = TypedDict(
     "BatchGetChannelResponseTypeDef",
     {
         "channels": List[ChannelTypeDef],
         "errors": List[BatchErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelResponseTypeDef = TypedDict(
     "GetChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetStreamKeyResponseTypeDef = TypedDict(
     "BatchGetStreamKeyResponseTypeDef",
     {
         "errors": List[BatchErrorTypeDef],
         "streamKeys": List[StreamKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
         "streamKey": StreamKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamKeyResponseTypeDef = TypedDict(
     "CreateStreamKeyResponseTypeDef",
     {
         "streamKey": StreamKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamKeyResponseTypeDef = TypedDict(
     "GetStreamKeyResponseTypeDef",
     {
         "streamKey": StreamKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "channels": List[ChannelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DestinationConfigurationTypeDef = TypedDict(
     "DestinationConfigurationTypeDef",
     {
         "s3": S3DestinationConfigurationTypeDef,
@@ -693,123 +751,75 @@
     total=False,
 )
 
 GetPlaybackKeyPairResponseTypeDef = TypedDict(
     "GetPlaybackKeyPairResponseTypeDef",
     {
         "keyPair": PlaybackKeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportPlaybackKeyPairResponseTypeDef = TypedDict(
     "ImportPlaybackKeyPairResponseTypeDef",
     {
         "keyPair": PlaybackKeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamResponseTypeDef = TypedDict(
     "GetStreamResponseTypeDef",
     {
         "stream": StreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IngestConfigurationTypeDef = TypedDict(
     "IngestConfigurationTypeDef",
     {
         "audio": AudioConfigurationTypeDef,
         "video": VideoConfigurationTypeDef,
     },
     total=False,
 )
 
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "filterByName": str,
-        "filterByRecordingConfigurationArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef = TypedDict(
-    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef = TypedDict(
-    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
-    "_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef",
-    {
-        "channelArn": str,
-    },
-)
-_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
-    "_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStreamKeysRequestListStreamKeysPaginateTypeDef(
-    _RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef,
-    _OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef,
-):
-    pass
-
-
 ListPlaybackKeyPairsResponseTypeDef = TypedDict(
     "ListPlaybackKeyPairsResponseTypeDef",
     {
         "keyPairs": List[PlaybackKeyPairSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamKeysResponseTypeDef = TypedDict(
     "ListStreamKeysResponseTypeDef",
     {
         "nextToken": str,
         "streamKeys": List[StreamKeySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamSessionsResponseTypeDef = TypedDict(
     "ListStreamSessionsResponseTypeDef",
     {
         "nextToken": str,
         "streamSessions": List[StreamSessionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamsRequestListStreamsPaginateTypeDef = TypedDict(
     "ListStreamsRequestListStreamsPaginateTypeDef",
     {
         "filterBy": StreamFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListStreamsRequestRequestTypeDef = TypedDict(
     "ListStreamsRequestRequestTypeDef",
     {
@@ -821,15 +831,15 @@
 )
 
 ListStreamsResponseTypeDef = TypedDict(
     "ListStreamsResponseTypeDef",
     {
         "nextToken": str,
         "streams": List[StreamSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRecordingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRecordingConfigurationRequestRequestTypeDef",
     {
         "destinationConfiguration": DestinationConfigurationTypeDef,
@@ -905,31 +915,31 @@
 
 
 ListRecordingConfigurationsResponseTypeDef = TypedDict(
     "ListRecordingConfigurationsResponseTypeDef",
     {
         "nextToken": str,
         "recordingConfigurations": List[RecordingConfigurationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRecordingConfigurationResponseTypeDef = TypedDict(
     "CreateRecordingConfigurationResponseTypeDef",
     {
         "recordingConfiguration": RecordingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecordingConfigurationResponseTypeDef = TypedDict(
     "GetRecordingConfigurationResponseTypeDef",
     {
         "recordingConfiguration": RecordingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StreamSessionTypeDef = TypedDict(
     "StreamSessionTypeDef",
     {
         "channel": ChannelTypeDef,
@@ -943,10 +953,10 @@
     total=False,
 )
 
 GetStreamSessionResponseTypeDef = TypedDict(
     "GetStreamSessionResponseTypeDef",
     {
         "streamSession": StreamSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs/type_defs.pyi` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,85 +18,86 @@
 from .literals import (
     ChannelLatencyModeType,
     ChannelTypeType,
     RecordingConfigurationStateType,
     RecordingModeType,
     StreamHealthType,
     StreamStateType,
+    TranscodePresetType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AudioConfigurationTypeDef",
     "BatchErrorTypeDef",
     "BatchGetChannelRequestRequestTypeDef",
     "ChannelTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetStreamKeyRequestRequestTypeDef",
     "StreamKeyTypeDef",
     "ChannelSummaryTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "ThumbnailConfigurationTypeDef",
     "CreateStreamKeyRequestRequestTypeDef",
     "DeleteChannelRequestRequestTypeDef",
     "DeletePlaybackKeyPairRequestRequestTypeDef",
     "DeleteRecordingConfigurationRequestRequestTypeDef",
     "DeleteStreamKeyRequestRequestTypeDef",
     "S3DestinationConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChannelRequestRequestTypeDef",
     "GetPlaybackKeyPairRequestRequestTypeDef",
     "PlaybackKeyPairTypeDef",
     "GetRecordingConfigurationRequestRequestTypeDef",
     "GetStreamKeyRequestRequestTypeDef",
     "GetStreamRequestRequestTypeDef",
     "StreamTypeDef",
     "GetStreamSessionRequestRequestTypeDef",
     "ImportPlaybackKeyPairRequestRequestTypeDef",
     "VideoConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
     "ListPlaybackKeyPairsRequestRequestTypeDef",
     "PlaybackKeyPairSummaryTypeDef",
+    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
     "ListRecordingConfigurationsRequestRequestTypeDef",
+    "ListStreamKeysRequestListStreamKeysPaginateTypeDef",
     "ListStreamKeysRequestRequestTypeDef",
     "StreamKeySummaryTypeDef",
     "ListStreamSessionsRequestRequestTypeDef",
     "StreamSessionSummaryTypeDef",
     "StreamFiltersTypeDef",
     "StreamSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutMetadataRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StopStreamRequestRequestTypeDef",
     "StreamEventTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateChannelRequestRequestTypeDef",
     "BatchGetChannelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetChannelResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateChannelResponseTypeDef",
     "BatchGetStreamKeyResponseTypeDef",
     "CreateChannelResponseTypeDef",
     "CreateStreamKeyResponseTypeDef",
     "GetStreamKeyResponseTypeDef",
     "ListChannelsResponseTypeDef",
     "DestinationConfigurationTypeDef",
     "GetPlaybackKeyPairResponseTypeDef",
     "ImportPlaybackKeyPairResponseTypeDef",
     "GetStreamResponseTypeDef",
     "IngestConfigurationTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
-    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
-    "ListStreamKeysRequestListStreamKeysPaginateTypeDef",
     "ListPlaybackKeyPairsResponseTypeDef",
     "ListStreamKeysResponseTypeDef",
     "ListStreamSessionsResponseTypeDef",
     "ListStreamsRequestListStreamsPaginateTypeDef",
     "ListStreamsRequestRequestTypeDef",
     "ListStreamsResponseTypeDef",
     "CreateRecordingConfigurationRequestRequestTypeDef",
@@ -139,35 +140,26 @@
 
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "arn": str,
         "authorized": bool,
         "ingestEndpoint": str,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
         "playbackUrl": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "tags": Dict[str, str],
         "type": ChannelTypeType,
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
 BatchGetStreamKeyRequestRequestTypeDef = TypedDict(
     "BatchGetStreamKeyRequestRequestTypeDef",
     {
         "arns": Sequence[str],
     },
 )
 
@@ -183,28 +175,33 @@
 )
 
 ChannelSummaryTypeDef = TypedDict(
     "ChannelSummaryTypeDef",
     {
         "arn": str,
         "authorized": bool,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "tags": Dict[str, str],
+        "type": ChannelTypeType,
     },
     total=False,
 )
 
 CreateChannelRequestRequestTypeDef = TypedDict(
     "CreateChannelRequestRequestTypeDef",
     {
         "authorized": bool,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "tags": Mapping[str, str],
         "type": ChannelTypeType,
     },
     total=False,
 )
 
@@ -267,14 +264,21 @@
 S3DestinationConfigurationTypeDef = TypedDict(
     "S3DestinationConfigurationTypeDef",
     {
         "bucketName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChannelRequestRequestTypeDef = TypedDict(
     "GetChannelRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -382,20 +386,20 @@
         "targetFramerate": int,
         "videoHeight": int,
         "videoWidth": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "filterByName": str,
+        "filterByRecordingConfigurationArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
@@ -403,14 +407,22 @@
         "filterByRecordingConfigurationArn": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef = TypedDict(
+    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPlaybackKeyPairsRequestRequestTypeDef = TypedDict(
     "ListPlaybackKeyPairsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -422,23 +434,51 @@
         "arn": str,
         "name": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef = TypedDict(
+    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecordingConfigurationsRequestRequestTypeDef = TypedDict(
     "ListRecordingConfigurationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
+    "_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef",
+    {
+        "channelArn": str,
+    },
+)
+_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
+    "_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStreamKeysRequestListStreamKeysPaginateTypeDef(
+    _RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef,
+    _OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef,
+):
+    pass
+
 _RequiredListStreamKeysRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamKeysRequestRequestTypeDef",
     {
         "channelArn": str,
     },
 )
 _OptionalListStreamKeysRequestRequestTypeDef = TypedDict(
@@ -521,22 +561,51 @@
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
 PutMetadataRequestRequestTypeDef = TypedDict(
     "PutMetadataRequestRequestTypeDef",
     {
         "channelArn": str,
         "metadata": str,
     },
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
 StopStreamRequestRequestTypeDef = TypedDict(
     "StopStreamRequestRequestTypeDef",
     {
         "channelArn": str,
     },
 )
 
@@ -572,16 +641,18 @@
         "arn": str,
     },
 )
 _OptionalUpdateChannelRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateChannelRequestRequestTypeDef",
     {
         "authorized": bool,
+        "insecureIngest": bool,
         "latencyMode": ChannelLatencyModeType,
         "name": str,
+        "preset": TranscodePresetType,
         "recordingConfigurationArn": str,
         "type": ChannelTypeType,
     },
     total=False,
 )
 
 class UpdateChannelRequestRequestTypeDef(
@@ -590,89 +661,74 @@
     pass
 
 BatchGetChannelResponseTypeDef = TypedDict(
     "BatchGetChannelResponseTypeDef",
     {
         "channels": List[ChannelTypeDef],
         "errors": List[BatchErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelResponseTypeDef = TypedDict(
     "GetChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetStreamKeyResponseTypeDef = TypedDict(
     "BatchGetStreamKeyResponseTypeDef",
     {
         "errors": List[BatchErrorTypeDef],
         "streamKeys": List[StreamKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
         "streamKey": StreamKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamKeyResponseTypeDef = TypedDict(
     "CreateStreamKeyResponseTypeDef",
     {
         "streamKey": StreamKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamKeyResponseTypeDef = TypedDict(
     "GetStreamKeyResponseTypeDef",
     {
         "streamKey": StreamKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "channels": List[ChannelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DestinationConfigurationTypeDef = TypedDict(
     "DestinationConfigurationTypeDef",
     {
         "s3": S3DestinationConfigurationTypeDef,
@@ -680,121 +736,75 @@
     total=False,
 )
 
 GetPlaybackKeyPairResponseTypeDef = TypedDict(
     "GetPlaybackKeyPairResponseTypeDef",
     {
         "keyPair": PlaybackKeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportPlaybackKeyPairResponseTypeDef = TypedDict(
     "ImportPlaybackKeyPairResponseTypeDef",
     {
         "keyPair": PlaybackKeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamResponseTypeDef = TypedDict(
     "GetStreamResponseTypeDef",
     {
         "stream": StreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IngestConfigurationTypeDef = TypedDict(
     "IngestConfigurationTypeDef",
     {
         "audio": AudioConfigurationTypeDef,
         "video": VideoConfigurationTypeDef,
     },
     total=False,
 )
 
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "filterByName": str,
-        "filterByRecordingConfigurationArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef = TypedDict(
-    "ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef = TypedDict(
-    "ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
-    "_RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef",
-    {
-        "channelArn": str,
-    },
-)
-_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef = TypedDict(
-    "_OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStreamKeysRequestListStreamKeysPaginateTypeDef(
-    _RequiredListStreamKeysRequestListStreamKeysPaginateTypeDef,
-    _OptionalListStreamKeysRequestListStreamKeysPaginateTypeDef,
-):
-    pass
-
 ListPlaybackKeyPairsResponseTypeDef = TypedDict(
     "ListPlaybackKeyPairsResponseTypeDef",
     {
         "keyPairs": List[PlaybackKeyPairSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamKeysResponseTypeDef = TypedDict(
     "ListStreamKeysResponseTypeDef",
     {
         "nextToken": str,
         "streamKeys": List[StreamKeySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamSessionsResponseTypeDef = TypedDict(
     "ListStreamSessionsResponseTypeDef",
     {
         "nextToken": str,
         "streamSessions": List[StreamSessionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamsRequestListStreamsPaginateTypeDef = TypedDict(
     "ListStreamsRequestListStreamsPaginateTypeDef",
     {
         "filterBy": StreamFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListStreamsRequestRequestTypeDef = TypedDict(
     "ListStreamsRequestRequestTypeDef",
     {
@@ -806,15 +816,15 @@
 )
 
 ListStreamsResponseTypeDef = TypedDict(
     "ListStreamsResponseTypeDef",
     {
         "nextToken": str,
         "streams": List[StreamSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRecordingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRecordingConfigurationRequestRequestTypeDef",
     {
         "destinationConfiguration": DestinationConfigurationTypeDef,
@@ -884,31 +894,31 @@
     pass
 
 ListRecordingConfigurationsResponseTypeDef = TypedDict(
     "ListRecordingConfigurationsResponseTypeDef",
     {
         "nextToken": str,
         "recordingConfigurations": List[RecordingConfigurationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRecordingConfigurationResponseTypeDef = TypedDict(
     "CreateRecordingConfigurationResponseTypeDef",
     {
         "recordingConfiguration": RecordingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecordingConfigurationResponseTypeDef = TypedDict(
     "GetRecordingConfigurationResponseTypeDef",
     {
         "recordingConfiguration": RecordingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StreamSessionTypeDef = TypedDict(
     "StreamSessionTypeDef",
     {
         "channel": ChannelTypeDef,
@@ -922,10 +932,10 @@
     total=False,
 )
 
 GetStreamSessionResponseTypeDef = TypedDict(
     "GetStreamSessionResponseTypeDef",
     {
         "streamSession": StreamSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/PKG-INFO` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ivs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IVS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IVS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ivs"></a>
 
 # types-aiobotocore-ivs
 
 [![PyPI - types-aiobotocore-ivs](https://img.shields.io/pypi/v/types-aiobotocore-ivs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ivs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ivs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ivs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ivs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IVS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
+[aiobotocore.IVS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ivs.html#IVS)
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
 [types-aiobotocore-ivs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,14 +315,15 @@
     ListRecordingConfigurationsPaginatorName,
     ListStreamKeysPaginatorName,
     ListStreamsPaginatorName,
     RecordingConfigurationStateType,
     RecordingModeType,
     StreamHealthType,
     StreamStateType,
+    TranscodePresetType,
     IVSServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
@@ -340,73 +341,73 @@
 
 ```python
 from types_aiobotocore_ivs.type_defs import (
     AudioConfigurationTypeDef,
     BatchErrorTypeDef,
     BatchGetChannelRequestRequestTypeDef,
     ChannelTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetStreamKeyRequestRequestTypeDef,
     StreamKeyTypeDef,
     ChannelSummaryTypeDef,
     CreateChannelRequestRequestTypeDef,
     ThumbnailConfigurationTypeDef,
     CreateStreamKeyRequestRequestTypeDef,
     DeleteChannelRequestRequestTypeDef,
     DeletePlaybackKeyPairRequestRequestTypeDef,
     DeleteRecordingConfigurationRequestRequestTypeDef,
     DeleteStreamKeyRequestRequestTypeDef,
     S3DestinationConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelRequestRequestTypeDef,
     GetPlaybackKeyPairRequestRequestTypeDef,
     PlaybackKeyPairTypeDef,
     GetRecordingConfigurationRequestRequestTypeDef,
     GetStreamKeyRequestRequestTypeDef,
     GetStreamRequestRequestTypeDef,
     StreamTypeDef,
     GetStreamSessionRequestRequestTypeDef,
     ImportPlaybackKeyPairRequestRequestTypeDef,
     VideoConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef,
     ListPlaybackKeyPairsRequestRequestTypeDef,
     PlaybackKeyPairSummaryTypeDef,
+    ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef,
     ListRecordingConfigurationsRequestRequestTypeDef,
+    ListStreamKeysRequestListStreamKeysPaginateTypeDef,
     ListStreamKeysRequestRequestTypeDef,
     StreamKeySummaryTypeDef,
     ListStreamSessionsRequestRequestTypeDef,
     StreamSessionSummaryTypeDef,
     StreamFiltersTypeDef,
     StreamSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutMetadataRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StopStreamRequestRequestTypeDef,
     StreamEventTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
     BatchGetChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetChannelResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateChannelResponseTypeDef,
     BatchGetStreamKeyResponseTypeDef,
     CreateChannelResponseTypeDef,
     CreateStreamKeyResponseTypeDef,
     GetStreamKeyResponseTypeDef,
     ListChannelsResponseTypeDef,
     DestinationConfigurationTypeDef,
     GetPlaybackKeyPairResponseTypeDef,
     ImportPlaybackKeyPairResponseTypeDef,
     GetStreamResponseTypeDef,
     IngestConfigurationTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListPlaybackKeyPairsRequestListPlaybackKeyPairsPaginateTypeDef,
-    ListRecordingConfigurationsRequestListRecordingConfigurationsPaginateTypeDef,
-    ListStreamKeysRequestListStreamKeysPaginateTypeDef,
     ListPlaybackKeyPairsResponseTypeDef,
     ListStreamKeysResponseTypeDef,
     ListStreamSessionsResponseTypeDef,
     ListStreamsRequestListStreamsPaginateTypeDef,
     ListStreamsRequestRequestTypeDef,
     ListStreamsResponseTypeDef,
     CreateRecordingConfigurationRequestRequestTypeDef,
@@ -427,43 +428,43 @@
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

### Comparing `types-aiobotocore-ivs-2.5.0.post1/types_aiobotocore_ivs.egg-info/SOURCES.txt` & `types-aiobotocore-ivs-2.5.1/types_aiobotocore_ivs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

