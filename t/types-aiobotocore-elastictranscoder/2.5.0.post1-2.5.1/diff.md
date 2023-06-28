# Comparing `tmp/types-aiobotocore-elastictranscoder-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-elastictranscoder-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-elastictranscoder-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:35 2023, max compression
+gzip compressed data, was "types-aiobotocore-elastictranscoder-2.5.1.tar", last modified: Wed Jun 28 01:43:27 2023, max compression
```

## Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1.tar` & `types-aiobotocore-elastictranscoder-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:35.599185 types-aiobotocore-elastictranscoder-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16918 2023-03-11 12:26:35.599185 types-aiobotocore-elastictranscoder-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15307 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:35.599185 types-aiobotocore-elastictranscoder-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:35.599185 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/
--rw-r--r--   0 runner    (1001) docker     (123)     1511 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18560 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18529 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8219 2023-03-11 12:14:10.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8217 2023-03-11 12:14:10.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5784 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5777 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    22855 2023-03-11 12:14:11.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22836 2023-03-11 12:14:11.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1612 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1611 2023-03-11 12:14:09.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:35.599185 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16918 2023-03-11 12:26:35.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-03-11 12:26:35.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:35.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:35.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:35.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:35.000000 types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.258132 types-aiobotocore-elastictranscoder-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16920 2023-06-28 01:43:27.250132 types-aiobotocore-elastictranscoder-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15315 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:27.258132 types-aiobotocore-elastictranscoder-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2204 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.250132 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/
+-rw-r--r--   0 runner    (1001) docker     (123)     1511 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18560 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18529 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8428 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8426 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5672 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5666 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22891 2023-06-28 01:30:47.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22872 2023-06-28 01:30:47.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1612 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1611 2023-06-28 01:30:46.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.250132 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16920 2023-06-28 01:43:27.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-06-28 01:43:27.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:27.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:27.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:27.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:27.000000 types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/LICENSE` & `types-aiobotocore-elastictranscoder-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/PKG-INFO` & `types-aiobotocore-elastictranscoder-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elastictranscoder
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticTranscoder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticTranscoder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elastictranscoder"></a>
 
 # types-aiobotocore-elastictranscoder
 
 [![PyPI - types-aiobotocore-elastictranscoder](https://img.shields.io/pypi/v/types-aiobotocore-elastictranscoder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastictranscoder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elastictranscoder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastictranscoder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elastictranscoder?color=blue)](https://pypistats.org/packages/types-aiobotocore-elastictranscoder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticTranscoder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
+[aiobotocore.ElasticTranscoder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
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
 [types-aiobotocore-elastictranscoder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -360,49 +360,49 @@
 from types_aiobotocore_elastictranscoder.type_defs import (
     EncryptionTypeDef,
     AudioCodecOptionsTypeDef,
     CancelJobRequestRequestTypeDef,
     TimeSpanTypeDef,
     HlsContentProtectionTypeDef,
     PlayReadyDrmTypeDef,
-    ResponseMetadataTypeDef,
     NotificationsTypeDef,
     WarningTypeDef,
     ThumbnailsTypeDef,
     DeletePipelineRequestRequestTypeDef,
     DeletePresetRequestRequestTypeDef,
     DetectedPropertiesTypeDef,
     TimingTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
     ListJobsByPipelineRequestRequestTypeDef,
+    ListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
     ListJobsByStatusRequestRequestTypeDef,
+    ListPipelinesRequestListPipelinesPaginateTypeDef,
     ListPipelinesRequestRequestTypeDef,
+    ListPresetsRequestListPresetsPaginateTypeDef,
     ListPresetsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PermissionTypeDef,
     PresetWatermarkTypeDef,
     WaiterConfigTypeDef,
     ReadJobRequestRequestTypeDef,
     ReadPipelineRequestRequestTypeDef,
     ReadPresetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TestRoleRequestRequestTypeDef,
+    TestRoleResponseTypeDef,
     UpdatePipelineStatusRequestRequestTypeDef,
     ArtworkTypeDef,
     CaptionFormatTypeDef,
     CaptionSourceTypeDef,
     JobWatermarkTypeDef,
     AudioParametersTypeDef,
     ClipTypeDef,
     CreateJobPlaylistTypeDef,
     PlaylistTypeDef,
-    TestRoleResponseTypeDef,
     UpdatePipelineNotificationsRequestRequestTypeDef,
-    ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-    ListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-    ListPipelinesRequestListPipelinesPaginateTypeDef,
-    ListPresetsRequestListPresetsPaginateTypeDef,
     PipelineOutputConfigTypeDef,
     VideoParametersTypeDef,
     ReadJobRequestJobCompleteWaitTypeDef,
     JobAlbumArtTypeDef,
     CaptionsTypeDef,
     InputCaptionsTypeDef,
     CreatePipelineRequestRequestTypeDef,
@@ -438,43 +438,43 @@
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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/README.md` & `types-aiobotocore-elastictranscoder-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-elastictranscoder"></a>
 
 # types-aiobotocore-elastictranscoder
 
 [![PyPI - types-aiobotocore-elastictranscoder](https://img.shields.io/pypi/v/types-aiobotocore-elastictranscoder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastictranscoder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elastictranscoder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastictranscoder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elastictranscoder?color=blue)](https://pypistats.org/packages/types-aiobotocore-elastictranscoder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticTranscoder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
+[aiobotocore.ElasticTranscoder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
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
 [types-aiobotocore-elastictranscoder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,49 +327,49 @@
 from types_aiobotocore_elastictranscoder.type_defs import (
     EncryptionTypeDef,
     AudioCodecOptionsTypeDef,
     CancelJobRequestRequestTypeDef,
     TimeSpanTypeDef,
     HlsContentProtectionTypeDef,
     PlayReadyDrmTypeDef,
-    ResponseMetadataTypeDef,
     NotificationsTypeDef,
     WarningTypeDef,
     ThumbnailsTypeDef,
     DeletePipelineRequestRequestTypeDef,
     DeletePresetRequestRequestTypeDef,
     DetectedPropertiesTypeDef,
     TimingTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
     ListJobsByPipelineRequestRequestTypeDef,
+    ListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
     ListJobsByStatusRequestRequestTypeDef,
+    ListPipelinesRequestListPipelinesPaginateTypeDef,
     ListPipelinesRequestRequestTypeDef,
+    ListPresetsRequestListPresetsPaginateTypeDef,
     ListPresetsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PermissionTypeDef,
     PresetWatermarkTypeDef,
     WaiterConfigTypeDef,
     ReadJobRequestRequestTypeDef,
     ReadPipelineRequestRequestTypeDef,
     ReadPresetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TestRoleRequestRequestTypeDef,
+    TestRoleResponseTypeDef,
     UpdatePipelineStatusRequestRequestTypeDef,
     ArtworkTypeDef,
     CaptionFormatTypeDef,
     CaptionSourceTypeDef,
     JobWatermarkTypeDef,
     AudioParametersTypeDef,
     ClipTypeDef,
     CreateJobPlaylistTypeDef,
     PlaylistTypeDef,
-    TestRoleResponseTypeDef,
     UpdatePipelineNotificationsRequestRequestTypeDef,
-    ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-    ListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-    ListPipelinesRequestListPipelinesPaginateTypeDef,
-    ListPresetsRequestListPresetsPaginateTypeDef,
     PipelineOutputConfigTypeDef,
     VideoParametersTypeDef,
     ReadJobRequestJobCompleteWaitTypeDef,
     JobAlbumArtTypeDef,
     CaptionsTypeDef,
     InputCaptionsTypeDef,
     CreatePipelineRequestRequestTypeDef,
@@ -405,43 +405,43 @@
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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/setup.py` & `types-aiobotocore-elastictranscoder-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-elastictranscoder.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-elastictranscoder",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_elastictranscoder"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ElasticTranscoder 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ElasticTranscoder 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/"
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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/__init__.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/__init__.pyi` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/__main__.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ElasticTranscoder 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ElasticTranscoder 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder\nOther"
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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/client.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/client.pyi` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/literals.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/literals.py`

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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/literals.pyi` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/literals.pyi`

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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/paginator.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,34 +22,27 @@
 
         list_jobs_by_pipeline_paginator: ListJobsByPipelinePaginator = client.get_paginator("list_jobs_by_pipeline")
         list_jobs_by_status_paginator: ListJobsByStatusPaginator = client.get_paginator("list_jobs_by_status")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
         list_presets_paginator: ListPresetsPaginator = client.get_paginator("list_presets")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListJobsByPipelineResponseTypeDef,
     ListJobsByStatusResponseTypeDef,
     ListPipelinesResponseTypeDef,
     ListPresetsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListJobsByPipelinePaginator",
     "ListJobsByStatusPaginator",
     "ListPipelinesPaginator",
     "ListPresetsPaginator",
 )
 
@@ -71,58 +64,58 @@
     """
 
     def paginate(
         self,
         *,
         PipelineId: str,
         Ascending: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsByPipelineResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByPipeline.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listjobsbypipelinepaginator)
         """
 
 
 class ListJobsByStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listjobsbystatuspaginator)
     """
 
     def paginate(
-        self, *, Status: str, Ascending: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Status: str, Ascending: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsByStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listjobsbystatuspaginator)
         """
 
 
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, Ascending: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Ascending: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpipelinespaginator)
         """
 
 
 class ListPresetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPresets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpresetspaginator)
     """
 
     def paginate(
-        self, *, Ascending: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Ascending: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPresetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPresets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpresetspaginator)
         """
```

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/paginator.pyi` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,33 +22,27 @@
 
         list_jobs_by_pipeline_paginator: ListJobsByPipelinePaginator = client.get_paginator("list_jobs_by_pipeline")
         list_jobs_by_status_paginator: ListJobsByStatusPaginator = client.get_paginator("list_jobs_by_status")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
         list_presets_paginator: ListPresetsPaginator = client.get_paginator("list_presets")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListJobsByPipelineResponseTypeDef,
     ListJobsByStatusResponseTypeDef,
     ListPipelinesResponseTypeDef,
     ListPresetsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListJobsByPipelinePaginator",
     "ListJobsByStatusPaginator",
     "ListPipelinesPaginator",
     "ListPresetsPaginator",
 )
 
@@ -67,55 +61,55 @@
     """
 
     def paginate(
         self,
         *,
         PipelineId: str,
         Ascending: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsByPipelineResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByPipeline.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listjobsbypipelinepaginator)
         """
 
 class ListJobsByStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listjobsbystatuspaginator)
     """
 
     def paginate(
-        self, *, Status: str, Ascending: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Status: str, Ascending: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsByStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListJobsByStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listjobsbystatuspaginator)
         """
 
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, Ascending: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Ascending: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpipelinespaginator)
         """
 
 class ListPresetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPresets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpresetspaginator)
     """
 
     def paginate(
-        self, *, Ascending: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Ascending: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPresetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder.Paginator.ListPresets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/paginators/#listpresetspaginator)
         """
```

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/type_defs.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,49 +23,49 @@
 __all__ = (
     "EncryptionTypeDef",
     "AudioCodecOptionsTypeDef",
     "CancelJobRequestRequestTypeDef",
     "TimeSpanTypeDef",
     "HlsContentProtectionTypeDef",
     "PlayReadyDrmTypeDef",
-    "ResponseMetadataTypeDef",
     "NotificationsTypeDef",
     "WarningTypeDef",
     "ThumbnailsTypeDef",
     "DeletePipelineRequestRequestTypeDef",
     "DeletePresetRequestRequestTypeDef",
     "DetectedPropertiesTypeDef",
     "TimingTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
     "ListJobsByPipelineRequestRequestTypeDef",
+    "ListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
     "ListJobsByStatusRequestRequestTypeDef",
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
     "ListPipelinesRequestRequestTypeDef",
+    "ListPresetsRequestListPresetsPaginateTypeDef",
     "ListPresetsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PermissionTypeDef",
     "PresetWatermarkTypeDef",
     "WaiterConfigTypeDef",
     "ReadJobRequestRequestTypeDef",
     "ReadPipelineRequestRequestTypeDef",
     "ReadPresetRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TestRoleRequestRequestTypeDef",
+    "TestRoleResponseTypeDef",
     "UpdatePipelineStatusRequestRequestTypeDef",
     "ArtworkTypeDef",
     "CaptionFormatTypeDef",
     "CaptionSourceTypeDef",
     "JobWatermarkTypeDef",
     "AudioParametersTypeDef",
     "ClipTypeDef",
     "CreateJobPlaylistTypeDef",
     "PlaylistTypeDef",
-    "TestRoleResponseTypeDef",
     "UpdatePipelineNotificationsRequestRequestTypeDef",
-    "ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
-    "ListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
-    "ListPresetsRequestListPresetsPaginateTypeDef",
     "PipelineOutputConfigTypeDef",
     "VideoParametersTypeDef",
     "ReadJobRequestJobCompleteWaitTypeDef",
     "JobAlbumArtTypeDef",
     "CaptionsTypeDef",
     "InputCaptionsTypeDef",
     "CreatePipelineRequestRequestTypeDef",
@@ -153,25 +153,14 @@
         "KeyId": str,
         "InitializationVector": str,
         "LicenseAcquisitionUrl": str,
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
 NotificationsTypeDef = TypedDict(
     "NotificationsTypeDef",
     {
         "Progressing": str,
         "Completed": str,
         "Warning": str,
         "Error": str,
@@ -235,24 +224,37 @@
         "SubmitTimeMillis": int,
         "StartTimeMillis": int,
         "FinishTimeMillis": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
+    "_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PipelineId": str,
+    },
+)
+_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
+    "_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef(
+    _RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
+    _OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListJobsByPipelineRequestRequestTypeDef = TypedDict(
     "_RequiredListJobsByPipelineRequestRequestTypeDef",
     {
         "PipelineId": str,
     },
 )
 _OptionalListJobsByPipelineRequestRequestTypeDef = TypedDict(
@@ -268,14 +270,37 @@
 class ListJobsByPipelineRequestRequestTypeDef(
     _RequiredListJobsByPipelineRequestRequestTypeDef,
     _OptionalListJobsByPipelineRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
+    "_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
+    {
+        "Status": str,
+    },
+)
+_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
+    "_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListJobsByStatusRequestListJobsByStatusPaginateTypeDef(
+    _RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
+    _OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListJobsByStatusRequestRequestTypeDef = TypedDict(
     "_RequiredListJobsByStatusRequestRequestTypeDef",
     {
         "Status": str,
     },
 )
 _OptionalListJobsByStatusRequestRequestTypeDef = TypedDict(
@@ -290,32 +315,60 @@
 
 class ListJobsByStatusRequestRequestTypeDef(
     _RequiredListJobsByStatusRequestRequestTypeDef, _OptionalListJobsByStatusRequestRequestTypeDef
 ):
     pass
 
 
+ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPipelinesRequestRequestTypeDef = TypedDict(
     "ListPipelinesRequestRequestTypeDef",
     {
         "Ascending": str,
         "PageToken": str,
     },
     total=False,
 )
 
+ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
+    "ListPresetsRequestListPresetsPaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPresetsRequestRequestTypeDef = TypedDict(
     "ListPresetsRequestRequestTypeDef",
     {
         "Ascending": str,
         "PageToken": str,
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
 PermissionTypeDef = TypedDict(
     "PermissionTypeDef",
     {
         "GranteeType": str,
         "Grantee": str,
         "Access": Sequence[str],
     },
@@ -365,24 +418,44 @@
 ReadPresetRequestRequestTypeDef = TypedDict(
     "ReadPresetRequestRequestTypeDef",
     {
         "Id": str,
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
 TestRoleRequestRequestTypeDef = TypedDict(
     "TestRoleRequestRequestTypeDef",
     {
         "Role": str,
         "InputBucket": str,
         "OutputBucket": str,
         "Topics": Sequence[str],
     },
 )
 
+TestRoleResponseTypeDef = TypedDict(
+    "TestRoleResponseTypeDef",
+    {
+        "Success": str,
+        "Messages": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdatePipelineStatusRequestRequestTypeDef = TypedDict(
     "UpdatePipelineStatusRequestRequestTypeDef",
     {
         "Id": str,
         "Status": str,
     },
 )
@@ -476,95 +549,22 @@
         "PlayReadyDrm": PlayReadyDrmTypeDef,
         "Status": str,
         "StatusDetail": str,
     },
     total=False,
 )
 
-TestRoleResponseTypeDef = TypedDict(
-    "TestRoleResponseTypeDef",
-    {
-        "Success": str,
-        "Messages": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdatePipelineNotificationsRequestRequestTypeDef = TypedDict(
     "UpdatePipelineNotificationsRequestRequestTypeDef",
     {
         "Id": str,
         "Notifications": NotificationsTypeDef,
     },
 )
 
-_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
-    "_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
-    {
-        "PipelineId": str,
-    },
-)
-_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
-    "_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef(
-    _RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-    _OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
-    "_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
-    {
-        "Status": str,
-    },
-)
-_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
-    "_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobsByStatusRequestListJobsByStatusPaginateTypeDef(
-    _RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-    _OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-):
-    pass
-
-
-ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
-    "ListPresetsRequestListPresetsPaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 PipelineOutputConfigTypeDef = TypedDict(
     "PipelineOutputConfigTypeDef",
     {
         "Bucket": str,
         "StorageClass": str,
         "Permissions": Sequence[PermissionTypeDef],
     },
@@ -819,84 +819,84 @@
 )
 
 CreatePipelineResponseTypeDef = TypedDict(
     "CreatePipelineResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
         "Warnings": List[WarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPipelinesResponseTypeDef = TypedDict(
     "ListPipelinesResponseTypeDef",
     {
         "Pipelines": List[PipelineTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReadPipelineResponseTypeDef = TypedDict(
     "ReadPipelineResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
         "Warnings": List[WarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineNotificationsResponseTypeDef = TypedDict(
     "UpdatePipelineNotificationsResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineResponseTypeDef = TypedDict(
     "UpdatePipelineResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
         "Warnings": List[WarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineStatusResponseTypeDef = TypedDict(
     "UpdatePipelineStatusResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePresetResponseTypeDef = TypedDict(
     "CreatePresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
         "Warning": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPresetsResponseTypeDef = TypedDict(
     "ListPresetsResponseTypeDef",
     {
         "Presets": List[PresetTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReadPresetResponseTypeDef = TypedDict(
     "ReadPresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobRequestRequestTypeDef",
     {
         "PipelineId": str,
@@ -942,36 +942,36 @@
     total=False,
 )
 
 CreateJobResponseTypeDef = TypedDict(
     "CreateJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsByPipelineResponseTypeDef = TypedDict(
     "ListJobsByPipelineResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsByStatusResponseTypeDef = TypedDict(
     "ListJobsByStatusResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReadJobResponseTypeDef = TypedDict(
     "ReadJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/type_defs.pyi` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,49 +22,49 @@
 __all__ = (
     "EncryptionTypeDef",
     "AudioCodecOptionsTypeDef",
     "CancelJobRequestRequestTypeDef",
     "TimeSpanTypeDef",
     "HlsContentProtectionTypeDef",
     "PlayReadyDrmTypeDef",
-    "ResponseMetadataTypeDef",
     "NotificationsTypeDef",
     "WarningTypeDef",
     "ThumbnailsTypeDef",
     "DeletePipelineRequestRequestTypeDef",
     "DeletePresetRequestRequestTypeDef",
     "DetectedPropertiesTypeDef",
     "TimingTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
     "ListJobsByPipelineRequestRequestTypeDef",
+    "ListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
     "ListJobsByStatusRequestRequestTypeDef",
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
     "ListPipelinesRequestRequestTypeDef",
+    "ListPresetsRequestListPresetsPaginateTypeDef",
     "ListPresetsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PermissionTypeDef",
     "PresetWatermarkTypeDef",
     "WaiterConfigTypeDef",
     "ReadJobRequestRequestTypeDef",
     "ReadPipelineRequestRequestTypeDef",
     "ReadPresetRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TestRoleRequestRequestTypeDef",
+    "TestRoleResponseTypeDef",
     "UpdatePipelineStatusRequestRequestTypeDef",
     "ArtworkTypeDef",
     "CaptionFormatTypeDef",
     "CaptionSourceTypeDef",
     "JobWatermarkTypeDef",
     "AudioParametersTypeDef",
     "ClipTypeDef",
     "CreateJobPlaylistTypeDef",
     "PlaylistTypeDef",
-    "TestRoleResponseTypeDef",
     "UpdatePipelineNotificationsRequestRequestTypeDef",
-    "ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
-    "ListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
-    "ListPresetsRequestListPresetsPaginateTypeDef",
     "PipelineOutputConfigTypeDef",
     "VideoParametersTypeDef",
     "ReadJobRequestJobCompleteWaitTypeDef",
     "JobAlbumArtTypeDef",
     "CaptionsTypeDef",
     "InputCaptionsTypeDef",
     "CreatePipelineRequestRequestTypeDef",
@@ -152,25 +152,14 @@
         "KeyId": str,
         "InitializationVector": str,
         "LicenseAcquisitionUrl": str,
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
 NotificationsTypeDef = TypedDict(
     "NotificationsTypeDef",
     {
         "Progressing": str,
         "Completed": str,
         "Warning": str,
         "Error": str,
@@ -234,24 +223,35 @@
         "SubmitTimeMillis": int,
         "StartTimeMillis": int,
         "FinishTimeMillis": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
+    "_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PipelineId": str,
+    },
+)
+_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
+    "_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef(
+    _RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
+    _OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
+):
+    pass
+
 _RequiredListJobsByPipelineRequestRequestTypeDef = TypedDict(
     "_RequiredListJobsByPipelineRequestRequestTypeDef",
     {
         "PipelineId": str,
     },
 )
 _OptionalListJobsByPipelineRequestRequestTypeDef = TypedDict(
@@ -265,14 +265,35 @@
 
 class ListJobsByPipelineRequestRequestTypeDef(
     _RequiredListJobsByPipelineRequestRequestTypeDef,
     _OptionalListJobsByPipelineRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
+    "_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
+    {
+        "Status": str,
+    },
+)
+_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
+    "_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListJobsByStatusRequestListJobsByStatusPaginateTypeDef(
+    _RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
+    _OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredListJobsByStatusRequestRequestTypeDef = TypedDict(
     "_RequiredListJobsByStatusRequestRequestTypeDef",
     {
         "Status": str,
     },
 )
 _OptionalListJobsByStatusRequestRequestTypeDef = TypedDict(
@@ -285,32 +306,60 @@
 )
 
 class ListJobsByStatusRequestRequestTypeDef(
     _RequiredListJobsByStatusRequestRequestTypeDef, _OptionalListJobsByStatusRequestRequestTypeDef
 ):
     pass
 
+ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPipelinesRequestRequestTypeDef = TypedDict(
     "ListPipelinesRequestRequestTypeDef",
     {
         "Ascending": str,
         "PageToken": str,
     },
     total=False,
 )
 
+ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
+    "ListPresetsRequestListPresetsPaginateTypeDef",
+    {
+        "Ascending": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPresetsRequestRequestTypeDef = TypedDict(
     "ListPresetsRequestRequestTypeDef",
     {
         "Ascending": str,
         "PageToken": str,
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
 PermissionTypeDef = TypedDict(
     "PermissionTypeDef",
     {
         "GranteeType": str,
         "Grantee": str,
         "Access": Sequence[str],
     },
@@ -360,24 +409,44 @@
 ReadPresetRequestRequestTypeDef = TypedDict(
     "ReadPresetRequestRequestTypeDef",
     {
         "Id": str,
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
 TestRoleRequestRequestTypeDef = TypedDict(
     "TestRoleRequestRequestTypeDef",
     {
         "Role": str,
         "InputBucket": str,
         "OutputBucket": str,
         "Topics": Sequence[str],
     },
 )
 
+TestRoleResponseTypeDef = TypedDict(
+    "TestRoleResponseTypeDef",
+    {
+        "Success": str,
+        "Messages": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdatePipelineStatusRequestRequestTypeDef = TypedDict(
     "UpdatePipelineStatusRequestRequestTypeDef",
     {
         "Id": str,
         "Status": str,
     },
 )
@@ -471,91 +540,22 @@
         "PlayReadyDrm": PlayReadyDrmTypeDef,
         "Status": str,
         "StatusDetail": str,
     },
     total=False,
 )
 
-TestRoleResponseTypeDef = TypedDict(
-    "TestRoleResponseTypeDef",
-    {
-        "Success": str,
-        "Messages": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdatePipelineNotificationsRequestRequestTypeDef = TypedDict(
     "UpdatePipelineNotificationsRequestRequestTypeDef",
     {
         "Id": str,
         "Notifications": NotificationsTypeDef,
     },
 )
 
-_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
-    "_RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
-    {
-        "PipelineId": str,
-    },
-)
-_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef = TypedDict(
-    "_OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef(
-    _RequiredListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-    _OptionalListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-):
-    pass
-
-_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
-    "_RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
-    {
-        "Status": str,
-    },
-)
-_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef = TypedDict(
-    "_OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobsByStatusRequestListJobsByStatusPaginateTypeDef(
-    _RequiredListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-    _OptionalListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-):
-    pass
-
-ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPresetsRequestListPresetsPaginateTypeDef = TypedDict(
-    "ListPresetsRequestListPresetsPaginateTypeDef",
-    {
-        "Ascending": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 PipelineOutputConfigTypeDef = TypedDict(
     "PipelineOutputConfigTypeDef",
     {
         "Bucket": str,
         "StorageClass": str,
         "Permissions": Sequence[PermissionTypeDef],
     },
@@ -802,84 +802,84 @@
 )
 
 CreatePipelineResponseTypeDef = TypedDict(
     "CreatePipelineResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
         "Warnings": List[WarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPipelinesResponseTypeDef = TypedDict(
     "ListPipelinesResponseTypeDef",
     {
         "Pipelines": List[PipelineTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReadPipelineResponseTypeDef = TypedDict(
     "ReadPipelineResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
         "Warnings": List[WarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineNotificationsResponseTypeDef = TypedDict(
     "UpdatePipelineNotificationsResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineResponseTypeDef = TypedDict(
     "UpdatePipelineResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
         "Warnings": List[WarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineStatusResponseTypeDef = TypedDict(
     "UpdatePipelineStatusResponseTypeDef",
     {
         "Pipeline": PipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePresetResponseTypeDef = TypedDict(
     "CreatePresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
         "Warning": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPresetsResponseTypeDef = TypedDict(
     "ListPresetsResponseTypeDef",
     {
         "Presets": List[PresetTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReadPresetResponseTypeDef = TypedDict(
     "ReadPresetResponseTypeDef",
     {
         "Preset": PresetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobRequestRequestTypeDef",
     {
         "PipelineId": str,
@@ -923,36 +923,36 @@
     total=False,
 )
 
 CreateJobResponseTypeDef = TypedDict(
     "CreateJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsByPipelineResponseTypeDef = TypedDict(
     "ListJobsByPipelineResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsByStatusResponseTypeDef = TypedDict(
     "ListJobsByStatusResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReadJobResponseTypeDef = TypedDict(
     "ReadJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/waiter.py` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder/waiter.pyi` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/PKG-INFO` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elastictranscoder
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticTranscoder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticTranscoder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elastictranscoder"></a>
 
 # types-aiobotocore-elastictranscoder
 
 [![PyPI - types-aiobotocore-elastictranscoder](https://img.shields.io/pypi/v/types-aiobotocore-elastictranscoder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastictranscoder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elastictranscoder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastictranscoder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elastictranscoder?color=blue)](https://pypistats.org/packages/types-aiobotocore-elastictranscoder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticTranscoder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
+[aiobotocore.ElasticTranscoder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastictranscoder.html#ElasticTranscoder)
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
 [types-aiobotocore-elastictranscoder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastictranscoder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -360,49 +360,49 @@
 from types_aiobotocore_elastictranscoder.type_defs import (
     EncryptionTypeDef,
     AudioCodecOptionsTypeDef,
     CancelJobRequestRequestTypeDef,
     TimeSpanTypeDef,
     HlsContentProtectionTypeDef,
     PlayReadyDrmTypeDef,
-    ResponseMetadataTypeDef,
     NotificationsTypeDef,
     WarningTypeDef,
     ThumbnailsTypeDef,
     DeletePipelineRequestRequestTypeDef,
     DeletePresetRequestRequestTypeDef,
     DetectedPropertiesTypeDef,
     TimingTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
     ListJobsByPipelineRequestRequestTypeDef,
+    ListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
     ListJobsByStatusRequestRequestTypeDef,
+    ListPipelinesRequestListPipelinesPaginateTypeDef,
     ListPipelinesRequestRequestTypeDef,
+    ListPresetsRequestListPresetsPaginateTypeDef,
     ListPresetsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PermissionTypeDef,
     PresetWatermarkTypeDef,
     WaiterConfigTypeDef,
     ReadJobRequestRequestTypeDef,
     ReadPipelineRequestRequestTypeDef,
     ReadPresetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TestRoleRequestRequestTypeDef,
+    TestRoleResponseTypeDef,
     UpdatePipelineStatusRequestRequestTypeDef,
     ArtworkTypeDef,
     CaptionFormatTypeDef,
     CaptionSourceTypeDef,
     JobWatermarkTypeDef,
     AudioParametersTypeDef,
     ClipTypeDef,
     CreateJobPlaylistTypeDef,
     PlaylistTypeDef,
-    TestRoleResponseTypeDef,
     UpdatePipelineNotificationsRequestRequestTypeDef,
-    ListJobsByPipelineRequestListJobsByPipelinePaginateTypeDef,
-    ListJobsByStatusRequestListJobsByStatusPaginateTypeDef,
-    ListPipelinesRequestListPipelinesPaginateTypeDef,
-    ListPresetsRequestListPresetsPaginateTypeDef,
     PipelineOutputConfigTypeDef,
     VideoParametersTypeDef,
     ReadJobRequestJobCompleteWaitTypeDef,
     JobAlbumArtTypeDef,
     CaptionsTypeDef,
     InputCaptionsTypeDef,
     CreatePipelineRequestRequestTypeDef,
@@ -438,43 +438,43 @@
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

### Comparing `types-aiobotocore-elastictranscoder-2.5.0.post1/types_aiobotocore_elastictranscoder.egg-info/SOURCES.txt` & `types-aiobotocore-elastictranscoder-2.5.1/types_aiobotocore_elastictranscoder.egg-info/SOURCES.txt`

 * *Files identical despite different names*

