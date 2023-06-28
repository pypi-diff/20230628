# Comparing `tmp/types-aiobotocore-kinesisvideo-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kinesisvideo-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kinesisvideo-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kinesisvideo-2.5.1.tar", last modified: Wed Jun 28 01:43:43 2023, max compression
```

## Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1.tar` & `types-aiobotocore-kinesisvideo-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.755347 types-aiobotocore-kinesisvideo-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16865 2023-03-11 12:26:51.751347 types-aiobotocore-kinesisvideo-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15274 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.755347 types-aiobotocore-kinesisvideo-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.747347 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/
--rw-r--r--   0 runner    (1001) docker     (123)     1247 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1246 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24842 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24802 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9678 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9676 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4955 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4949 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25195 2023-03-11 12:17:04.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25160 2023-03-11 12:17:04.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:03.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.751347 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16865 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:51.000000 types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:43.094162 types-aiobotocore-kinesisvideo-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16862 2023-06-28 01:43:43.090162 types-aiobotocore-kinesisvideo-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15277 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:43.094162 types-aiobotocore-kinesisvideo-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:43.090162 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/
+-rw-r--r--   0 runner    (1001) docker     (123)     1247 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1246 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24842 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24802 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9887 2023-06-28 01:33:45.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9885 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4841 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4836 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25233 2023-06-28 01:33:45.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25198 2023-06-28 01:33:45.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:44.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:43.090162 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16862 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:42.000000 types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/LICENSE` & `types-aiobotocore-kinesisvideo-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kinesisvideo-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesisvideo
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideo 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideo 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesisvideo"></a>
 
 # types-aiobotocore-kinesisvideo
 
 [![PyPI - types-aiobotocore-kinesisvideo](https://img.shields.io/pypi/v/types-aiobotocore-kinesisvideo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisvideo)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisvideo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisvideo)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisvideo?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisvideo)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideo 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
+[aiobotocore.KinesisVideo 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
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
 [types-aiobotocore-kinesisvideo docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,58 +344,58 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kinesisvideo.type_defs import (
     SingleMasterConfigurationTypeDef,
     ChannelNameConditionTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateSignalingChannelOutputTypeDef,
     CreateStreamInputRequestTypeDef,
+    CreateStreamOutputTypeDef,
     DeleteSignalingChannelInputRequestTypeDef,
     DeleteStreamInputRequestTypeDef,
     LocalSizeConfigTypeDef,
     DescribeEdgeConfigurationInputRequestTypeDef,
     DescribeImageGenerationConfigurationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef,
     DescribeMappedResourceConfigurationInputRequestTypeDef,
     MappedResourceConfigurationListItemTypeDef,
     DescribeMediaStorageConfigurationInputRequestTypeDef,
     MediaStorageConfigurationTypeDef,
     DescribeNotificationConfigurationInputRequestTypeDef,
     DescribeSignalingChannelInputRequestTypeDef,
     DescribeStreamInputRequestTypeDef,
     StreamInfoTypeDef,
     GetDataEndpointInputRequestTypeDef,
+    GetDataEndpointOutputTypeDef,
     SingleMasterChannelEndpointConfigurationTypeDef,
     ResourceEndpointListItemTypeDef,
     ImageGenerationDestinationConfigTypeDef,
     StreamNameConditionTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ListTagsForStreamInputRequestTypeDef,
+    ListTagsForStreamOutputTypeDef,
     MediaSourceConfigTypeDef,
     NotificationDestinationConfigTypeDef,
+    PaginatorConfigTypeDef,
     ScheduleConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagStreamInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UntagStreamInputRequestTypeDef,
     UpdateDataRetentionInputRequestTypeDef,
     UpdateStreamInputRequestTypeDef,
     ChannelInfoTypeDef,
     UpdateSignalingChannelInputRequestTypeDef,
+    ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef,
     ListSignalingChannelsInputRequestTypeDef,
     CreateSignalingChannelInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
-    CreateSignalingChannelOutputTypeDef,
-    CreateStreamOutputTypeDef,
-    GetDataEndpointOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    ListTagsForStreamOutputTypeDef,
     DeletionConfigTypeDef,
-    DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef,
-    ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef,
     DescribeMappedResourceConfigurationOutputTypeDef,
     DescribeMediaStorageConfigurationOutputTypeDef,
     UpdateMediaStorageConfigurationInputRequestTypeDef,
     DescribeStreamOutputTypeDef,
     ListStreamsOutputTypeDef,
     GetSignalingChannelEndpointInputRequestTypeDef,
     GetSignalingChannelEndpointOutputTypeDef,
@@ -425,43 +425,43 @@
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/README.md` & `types-aiobotocore-kinesisvideo-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kinesisvideo"></a>
 
 # types-aiobotocore-kinesisvideo
 
 [![PyPI - types-aiobotocore-kinesisvideo](https://img.shields.io/pypi/v/types-aiobotocore-kinesisvideo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisvideo)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisvideo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisvideo)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisvideo?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisvideo)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideo 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
+[aiobotocore.KinesisVideo 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
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
 [types-aiobotocore-kinesisvideo docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/).
 
 See how it helps to find and fix potential bugs:
 
@@ -311,58 +311,58 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kinesisvideo.type_defs import (
     SingleMasterConfigurationTypeDef,
     ChannelNameConditionTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateSignalingChannelOutputTypeDef,
     CreateStreamInputRequestTypeDef,
+    CreateStreamOutputTypeDef,
     DeleteSignalingChannelInputRequestTypeDef,
     DeleteStreamInputRequestTypeDef,
     LocalSizeConfigTypeDef,
     DescribeEdgeConfigurationInputRequestTypeDef,
     DescribeImageGenerationConfigurationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef,
     DescribeMappedResourceConfigurationInputRequestTypeDef,
     MappedResourceConfigurationListItemTypeDef,
     DescribeMediaStorageConfigurationInputRequestTypeDef,
     MediaStorageConfigurationTypeDef,
     DescribeNotificationConfigurationInputRequestTypeDef,
     DescribeSignalingChannelInputRequestTypeDef,
     DescribeStreamInputRequestTypeDef,
     StreamInfoTypeDef,
     GetDataEndpointInputRequestTypeDef,
+    GetDataEndpointOutputTypeDef,
     SingleMasterChannelEndpointConfigurationTypeDef,
     ResourceEndpointListItemTypeDef,
     ImageGenerationDestinationConfigTypeDef,
     StreamNameConditionTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ListTagsForStreamInputRequestTypeDef,
+    ListTagsForStreamOutputTypeDef,
     MediaSourceConfigTypeDef,
     NotificationDestinationConfigTypeDef,
+    PaginatorConfigTypeDef,
     ScheduleConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagStreamInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UntagStreamInputRequestTypeDef,
     UpdateDataRetentionInputRequestTypeDef,
     UpdateStreamInputRequestTypeDef,
     ChannelInfoTypeDef,
     UpdateSignalingChannelInputRequestTypeDef,
+    ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef,
     ListSignalingChannelsInputRequestTypeDef,
     CreateSignalingChannelInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
-    CreateSignalingChannelOutputTypeDef,
-    CreateStreamOutputTypeDef,
-    GetDataEndpointOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    ListTagsForStreamOutputTypeDef,
     DeletionConfigTypeDef,
-    DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef,
-    ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef,
     DescribeMappedResourceConfigurationOutputTypeDef,
     DescribeMediaStorageConfigurationOutputTypeDef,
     UpdateMediaStorageConfigurationInputRequestTypeDef,
     DescribeStreamOutputTypeDef,
     ListStreamsOutputTypeDef,
     GetSignalingChannelEndpointInputRequestTypeDef,
     GetSignalingChannelEndpointOutputTypeDef,
@@ -392,43 +392,43 @@
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/setup.py` & `types-aiobotocore-kinesisvideo-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kinesisvideo.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kinesisvideo",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kinesisvideo"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KinesisVideo 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KinesisVideo 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/"
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/__init__.py` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/__init__.pyi` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/__main__.py` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KinesisVideo 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KinesisVideo 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo\nOther"
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/client.py` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/client.pyi` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/literals.py` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "APINameType",
     "ChannelProtocolType",
     "ChannelRoleType",
     "ChannelTypeType",
     "ComparisonOperatorType",
     "ConfigurationStatusType",
@@ -41,15 +40,14 @@
     "KinesisVideoServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 APINameType = Literal[
     "GET_CLIP",
     "GET_DASH_STREAMING_SESSION_URL",
     "GET_HLS_STREAMING_SESSION_URL",
     "GET_IMAGES",
     "GET_MEDIA",
     "GET_MEDIA_FOR_FRAGMENT_LIST",
@@ -134,14 +132,15 @@
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
@@ -220,14 +219,15 @@
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
@@ -238,14 +238,15 @@
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
@@ -281,14 +282,15 @@
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
@@ -307,16 +309,19 @@
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
@@ -400,15 +405,17 @@
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/literals.pyi` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "APINameType",
     "ChannelProtocolType",
     "ChannelRoleType",
     "ChannelTypeType",
     "ComparisonOperatorType",
     "ConfigurationStatusType",
@@ -40,14 +41,15 @@
     "KinesisVideoServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 APINameType = Literal[
     "GET_CLIP",
     "GET_DASH_STREAMING_SESSION_URL",
     "GET_HLS_STREAMING_SESSION_URL",
     "GET_IMAGES",
     "GET_MEDIA",
     "GET_MEDIA_FOR_FRAGMENT_LIST",
@@ -132,14 +134,15 @@
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
@@ -218,14 +221,15 @@
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
@@ -236,14 +240,15 @@
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
@@ -279,14 +284,15 @@
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
@@ -305,16 +311,19 @@
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
@@ -398,15 +407,17 @@
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/paginator.py` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -20,35 +20,28 @@
         client: KinesisVideoClient
 
         describe_mapped_resource_configuration_paginator: DescribeMappedResourceConfigurationPaginator = client.get_paginator("describe_mapped_resource_configuration")
         list_signaling_channels_paginator: ListSignalingChannelsPaginator = client.get_paginator("list_signaling_channels")
         list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ChannelNameConditionTypeDef,
     DescribeMappedResourceConfigurationOutputTypeDef,
     ListSignalingChannelsOutputTypeDef,
     ListStreamsOutputTypeDef,
     PaginatorConfigTypeDef,
     StreamNameConditionTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeMappedResourceConfigurationPaginator",
     "ListSignalingChannelsPaginator",
     "ListStreamsPaginator",
 )
 
 
@@ -69,15 +62,15 @@
     """
 
     def paginate(
         self,
         *,
         StreamName: str = ...,
         StreamARN: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMappedResourceConfigurationOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Paginator.DescribeMappedResourceConfiguration.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#describemappedresourceconfigurationpaginator)
         """
 
 
@@ -87,15 +80,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#listsignalingchannelspaginator)
     """
 
     def paginate(
         self,
         *,
         ChannelNameCondition: ChannelNameConditionTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSignalingChannelsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Paginator.ListSignalingChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#listsignalingchannelspaginator)
         """
 
 
@@ -105,13 +98,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#liststreamspaginator)
     """
 
     def paginate(
         self,
         *,
         StreamNameCondition: StreamNameConditionTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Paginator.ListStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#liststreamspaginator)
         """
```

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/paginator.pyi` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -20,34 +20,28 @@
         client: KinesisVideoClient
 
         describe_mapped_resource_configuration_paginator: DescribeMappedResourceConfigurationPaginator = client.get_paginator("describe_mapped_resource_configuration")
         list_signaling_channels_paginator: ListSignalingChannelsPaginator = client.get_paginator("list_signaling_channels")
         list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ChannelNameConditionTypeDef,
     DescribeMappedResourceConfigurationOutputTypeDef,
     ListSignalingChannelsOutputTypeDef,
     ListStreamsOutputTypeDef,
     PaginatorConfigTypeDef,
     StreamNameConditionTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeMappedResourceConfigurationPaginator",
     "ListSignalingChannelsPaginator",
     "ListStreamsPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -65,15 +59,15 @@
     """
 
     def paginate(
         self,
         *,
         StreamName: str = ...,
         StreamARN: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMappedResourceConfigurationOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Paginator.DescribeMappedResourceConfiguration.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#describemappedresourceconfigurationpaginator)
         """
 
 class ListSignalingChannelsPaginator(AioPaginator):
@@ -82,15 +76,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#listsignalingchannelspaginator)
     """
 
     def paginate(
         self,
         *,
         ChannelNameCondition: ChannelNameConditionTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSignalingChannelsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Paginator.ListSignalingChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#listsignalingchannelspaginator)
         """
 
 class ListStreamsPaginator(AioPaginator):
@@ -99,13 +93,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#liststreamspaginator)
     """
 
     def paginate(
         self,
         *,
         StreamNameCondition: StreamNameConditionTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo.Paginator.ListStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/paginators/#liststreamspaginator)
         """
```

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/type_defs.py` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -41,58 +41,58 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "SingleMasterConfigurationTypeDef",
     "ChannelNameConditionTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateSignalingChannelOutputTypeDef",
     "CreateStreamInputRequestTypeDef",
+    "CreateStreamOutputTypeDef",
     "DeleteSignalingChannelInputRequestTypeDef",
     "DeleteStreamInputRequestTypeDef",
     "LocalSizeConfigTypeDef",
     "DescribeEdgeConfigurationInputRequestTypeDef",
     "DescribeImageGenerationConfigurationInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
     "DescribeMappedResourceConfigurationInputRequestTypeDef",
     "MappedResourceConfigurationListItemTypeDef",
     "DescribeMediaStorageConfigurationInputRequestTypeDef",
     "MediaStorageConfigurationTypeDef",
     "DescribeNotificationConfigurationInputRequestTypeDef",
     "DescribeSignalingChannelInputRequestTypeDef",
     "DescribeStreamInputRequestTypeDef",
     "StreamInfoTypeDef",
     "GetDataEndpointInputRequestTypeDef",
+    "GetDataEndpointOutputTypeDef",
     "SingleMasterChannelEndpointConfigurationTypeDef",
     "ResourceEndpointListItemTypeDef",
     "ImageGenerationDestinationConfigTypeDef",
     "StreamNameConditionTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "ListTagsForStreamInputRequestTypeDef",
+    "ListTagsForStreamOutputTypeDef",
     "MediaSourceConfigTypeDef",
     "NotificationDestinationConfigTypeDef",
+    "PaginatorConfigTypeDef",
     "ScheduleConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagStreamInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UntagStreamInputRequestTypeDef",
     "UpdateDataRetentionInputRequestTypeDef",
     "UpdateStreamInputRequestTypeDef",
     "ChannelInfoTypeDef",
     "UpdateSignalingChannelInputRequestTypeDef",
+    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
     "ListSignalingChannelsInputRequestTypeDef",
     "CreateSignalingChannelInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
-    "CreateSignalingChannelOutputTypeDef",
-    "CreateStreamOutputTypeDef",
-    "GetDataEndpointOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "ListTagsForStreamOutputTypeDef",
     "DeletionConfigTypeDef",
-    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
-    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
     "DescribeMappedResourceConfigurationOutputTypeDef",
     "DescribeMediaStorageConfigurationOutputTypeDef",
     "UpdateMediaStorageConfigurationInputRequestTypeDef",
     "DescribeStreamOutputTypeDef",
     "ListStreamsOutputTypeDef",
     "GetSignalingChannelEndpointInputRequestTypeDef",
     "GetSignalingChannelEndpointOutputTypeDef",
@@ -135,22 +135,19 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateSignalingChannelOutputTypeDef = TypedDict(
+    "CreateSignalingChannelOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ChannelARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStreamInputRequestTypeDef = TypedDict(
     "_RequiredCreateStreamInputRequestTypeDef",
     {
         "StreamName": str,
@@ -171,14 +168,22 @@
 
 class CreateStreamInputRequestTypeDef(
     _RequiredCreateStreamInputRequestTypeDef, _OptionalCreateStreamInputRequestTypeDef
 ):
     pass
 
 
+CreateStreamOutputTypeDef = TypedDict(
+    "CreateStreamOutputTypeDef",
+    {
+        "StreamARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteSignalingChannelInputRequestTypeDef = TypedDict(
     "_RequiredDeleteSignalingChannelInputRequestTypeDef",
     {
         "ChannelARN": str,
     },
 )
 _OptionalDeleteSignalingChannelInputRequestTypeDef = TypedDict(
@@ -241,20 +246,20 @@
     {
         "StreamName": str,
         "StreamARN": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef = TypedDict(
+    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "StreamName": str,
+        "StreamARN": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeMappedResourceConfigurationInputRequestTypeDef = TypedDict(
     "DescribeMappedResourceConfigurationInputRequestTypeDef",
     {
@@ -366,14 +371,22 @@
 
 class GetDataEndpointInputRequestTypeDef(
     _RequiredGetDataEndpointInputRequestTypeDef, _OptionalGetDataEndpointInputRequestTypeDef
 ):
     pass
 
 
+GetDataEndpointOutputTypeDef = TypedDict(
+    "GetDataEndpointOutputTypeDef",
+    {
+        "DataEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SingleMasterChannelEndpointConfigurationTypeDef = TypedDict(
     "SingleMasterChannelEndpointConfigurationTypeDef",
     {
         "Protocols": Sequence[ChannelProtocolType],
         "Role": ChannelRoleType,
     },
     total=False,
@@ -422,24 +435,42 @@
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
 ):
     pass
 
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "NextToken": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForStreamInputRequestTypeDef = TypedDict(
     "ListTagsForStreamInputRequestTypeDef",
     {
         "NextToken": str,
         "StreamARN": str,
         "StreamName": str,
     },
     total=False,
 )
 
+ListTagsForStreamOutputTypeDef = TypedDict(
+    "ListTagsForStreamOutputTypeDef",
+    {
+        "NextToken": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MediaSourceConfigTypeDef = TypedDict(
     "MediaSourceConfigTypeDef",
     {
         "MediaUriSecretArn": str,
         "MediaUriType": MediaUriTypeType,
     },
 )
@@ -447,22 +478,43 @@
 NotificationDestinationConfigTypeDef = TypedDict(
     "NotificationDestinationConfigTypeDef",
     {
         "Uri": str,
     },
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
 ScheduleConfigTypeDef = TypedDict(
     "ScheduleConfigTypeDef",
     {
         "ScheduleExpression": str,
         "DurationInSeconds": int,
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
 _RequiredTagStreamInputRequestTypeDef = TypedDict(
     "_RequiredTagStreamInputRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
 )
 _OptionalTagStreamInputRequestTypeDef = TypedDict(
@@ -592,14 +644,23 @@
 class UpdateSignalingChannelInputRequestTypeDef(
     _RequiredUpdateSignalingChannelInputRequestTypeDef,
     _OptionalUpdateSignalingChannelInputRequestTypeDef,
 ):
     pass
 
 
+ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef = TypedDict(
+    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
+    {
+        "ChannelNameCondition": ChannelNameConditionTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSignalingChannelsInputRequestTypeDef = TypedDict(
     "ListSignalingChannelsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "ChannelNameCondition": ChannelNameConditionTypeDef,
     },
@@ -634,99 +695,38 @@
     "TagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-CreateSignalingChannelOutputTypeDef = TypedDict(
-    "CreateSignalingChannelOutputTypeDef",
-    {
-        "ChannelARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStreamOutputTypeDef = TypedDict(
-    "CreateStreamOutputTypeDef",
-    {
-        "StreamARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDataEndpointOutputTypeDef = TypedDict(
-    "GetDataEndpointOutputTypeDef",
-    {
-        "DataEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "NextToken": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForStreamOutputTypeDef = TypedDict(
-    "ListTagsForStreamOutputTypeDef",
-    {
-        "NextToken": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DeletionConfigTypeDef = TypedDict(
     "DeletionConfigTypeDef",
     {
         "EdgeRetentionInHours": int,
         "LocalSizeConfig": LocalSizeConfigTypeDef,
         "DeleteAfterUpload": bool,
     },
     total=False,
 )
 
-DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef = TypedDict(
-    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
-    {
-        "StreamName": str,
-        "StreamARN": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef = TypedDict(
-    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
-    {
-        "ChannelNameCondition": ChannelNameConditionTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeMappedResourceConfigurationOutputTypeDef = TypedDict(
     "DescribeMappedResourceConfigurationOutputTypeDef",
     {
         "MappedResourceConfigurationList": List[MappedResourceConfigurationListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMediaStorageConfigurationOutputTypeDef = TypedDict(
     "DescribeMediaStorageConfigurationOutputTypeDef",
     {
         "MediaStorageConfiguration": MediaStorageConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMediaStorageConfigurationInputRequestTypeDef = TypedDict(
     "UpdateMediaStorageConfigurationInputRequestTypeDef",
     {
         "ChannelARN": str,
@@ -734,24 +734,24 @@
     },
 )
 
 DescribeStreamOutputTypeDef = TypedDict(
     "DescribeStreamOutputTypeDef",
     {
         "StreamInfo": StreamInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamsOutputTypeDef = TypedDict(
     "ListStreamsOutputTypeDef",
     {
         "StreamInfoList": List[StreamInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetSignalingChannelEndpointInputRequestTypeDef = TypedDict(
     "_RequiredGetSignalingChannelEndpointInputRequestTypeDef",
     {
         "ChannelARN": str,
@@ -773,15 +773,15 @@
     pass
 
 
 GetSignalingChannelEndpointOutputTypeDef = TypedDict(
     "GetSignalingChannelEndpointOutputTypeDef",
     {
         "ResourceEndpointList": List[ResourceEndpointListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImageGenerationConfigurationTypeDef = TypedDict(
     "_RequiredImageGenerationConfigurationTypeDef",
     {
         "Status": ConfigurationStatusType,
@@ -808,15 +808,15 @@
     pass
 
 
 ListStreamsInputListStreamsPaginateTypeDef = TypedDict(
     "ListStreamsInputListStreamsPaginateTypeDef",
     {
         "StreamNameCondition": StreamNameConditionTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListStreamsInputRequestTypeDef = TypedDict(
     "ListStreamsInputRequestTypeDef",
     {
@@ -861,32 +861,32 @@
     },
 )
 
 DescribeSignalingChannelOutputTypeDef = TypedDict(
     "DescribeSignalingChannelOutputTypeDef",
     {
         "ChannelInfo": ChannelInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSignalingChannelsOutputTypeDef = TypedDict(
     "ListSignalingChannelsOutputTypeDef",
     {
         "ChannelInfoList": List[ChannelInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImageGenerationConfigurationOutputTypeDef = TypedDict(
     "DescribeImageGenerationConfigurationOutputTypeDef",
     {
         "ImageGenerationConfiguration": ImageGenerationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateImageGenerationConfigurationInputRequestTypeDef = TypedDict(
     "UpdateImageGenerationConfigurationInputRequestTypeDef",
     {
         "StreamName": str,
@@ -896,15 +896,15 @@
     total=False,
 )
 
 DescribeNotificationConfigurationOutputTypeDef = TypedDict(
     "DescribeNotificationConfigurationOutputTypeDef",
     {
         "NotificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNotificationConfigurationInputRequestTypeDef = TypedDict(
     "UpdateNotificationConfigurationInputRequestTypeDef",
     {
         "StreamName": str,
@@ -941,15 +941,15 @@
         "StreamName": str,
         "StreamARN": str,
         "CreationTime": datetime,
         "LastUpdatedTime": datetime,
         "SyncStatus": SyncStatusType,
         "FailedStatusDetails": str,
         "EdgeConfig": EdgeConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartEdgeConfigurationUpdateInputRequestTypeDef = TypedDict(
     "_RequiredStartEdgeConfigurationUpdateInputRequestTypeDef",
     {
         "EdgeConfig": EdgeConfigTypeDef,
@@ -978,10 +978,10 @@
         "StreamName": str,
         "StreamARN": str,
         "CreationTime": datetime,
         "LastUpdatedTime": datetime,
         "SyncStatus": SyncStatusType,
         "FailedStatusDetails": str,
         "EdgeConfig": EdgeConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo/type_defs.pyi` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -40,58 +40,58 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "SingleMasterConfigurationTypeDef",
     "ChannelNameConditionTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateSignalingChannelOutputTypeDef",
     "CreateStreamInputRequestTypeDef",
+    "CreateStreamOutputTypeDef",
     "DeleteSignalingChannelInputRequestTypeDef",
     "DeleteStreamInputRequestTypeDef",
     "LocalSizeConfigTypeDef",
     "DescribeEdgeConfigurationInputRequestTypeDef",
     "DescribeImageGenerationConfigurationInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
     "DescribeMappedResourceConfigurationInputRequestTypeDef",
     "MappedResourceConfigurationListItemTypeDef",
     "DescribeMediaStorageConfigurationInputRequestTypeDef",
     "MediaStorageConfigurationTypeDef",
     "DescribeNotificationConfigurationInputRequestTypeDef",
     "DescribeSignalingChannelInputRequestTypeDef",
     "DescribeStreamInputRequestTypeDef",
     "StreamInfoTypeDef",
     "GetDataEndpointInputRequestTypeDef",
+    "GetDataEndpointOutputTypeDef",
     "SingleMasterChannelEndpointConfigurationTypeDef",
     "ResourceEndpointListItemTypeDef",
     "ImageGenerationDestinationConfigTypeDef",
     "StreamNameConditionTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "ListTagsForStreamInputRequestTypeDef",
+    "ListTagsForStreamOutputTypeDef",
     "MediaSourceConfigTypeDef",
     "NotificationDestinationConfigTypeDef",
+    "PaginatorConfigTypeDef",
     "ScheduleConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagStreamInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UntagStreamInputRequestTypeDef",
     "UpdateDataRetentionInputRequestTypeDef",
     "UpdateStreamInputRequestTypeDef",
     "ChannelInfoTypeDef",
     "UpdateSignalingChannelInputRequestTypeDef",
+    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
     "ListSignalingChannelsInputRequestTypeDef",
     "CreateSignalingChannelInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
-    "CreateSignalingChannelOutputTypeDef",
-    "CreateStreamOutputTypeDef",
-    "GetDataEndpointOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "ListTagsForStreamOutputTypeDef",
     "DeletionConfigTypeDef",
-    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
-    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
     "DescribeMappedResourceConfigurationOutputTypeDef",
     "DescribeMediaStorageConfigurationOutputTypeDef",
     "UpdateMediaStorageConfigurationInputRequestTypeDef",
     "DescribeStreamOutputTypeDef",
     "ListStreamsOutputTypeDef",
     "GetSignalingChannelEndpointInputRequestTypeDef",
     "GetSignalingChannelEndpointOutputTypeDef",
@@ -134,22 +134,19 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateSignalingChannelOutputTypeDef = TypedDict(
+    "CreateSignalingChannelOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ChannelARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStreamInputRequestTypeDef = TypedDict(
     "_RequiredCreateStreamInputRequestTypeDef",
     {
         "StreamName": str,
@@ -168,14 +165,22 @@
 )
 
 class CreateStreamInputRequestTypeDef(
     _RequiredCreateStreamInputRequestTypeDef, _OptionalCreateStreamInputRequestTypeDef
 ):
     pass
 
+CreateStreamOutputTypeDef = TypedDict(
+    "CreateStreamOutputTypeDef",
+    {
+        "StreamARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteSignalingChannelInputRequestTypeDef = TypedDict(
     "_RequiredDeleteSignalingChannelInputRequestTypeDef",
     {
         "ChannelARN": str,
     },
 )
 _OptionalDeleteSignalingChannelInputRequestTypeDef = TypedDict(
@@ -234,20 +239,20 @@
     {
         "StreamName": str,
         "StreamARN": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef = TypedDict(
+    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "StreamName": str,
+        "StreamARN": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeMappedResourceConfigurationInputRequestTypeDef = TypedDict(
     "DescribeMappedResourceConfigurationInputRequestTypeDef",
     {
@@ -355,14 +360,22 @@
 )
 
 class GetDataEndpointInputRequestTypeDef(
     _RequiredGetDataEndpointInputRequestTypeDef, _OptionalGetDataEndpointInputRequestTypeDef
 ):
     pass
 
+GetDataEndpointOutputTypeDef = TypedDict(
+    "GetDataEndpointOutputTypeDef",
+    {
+        "DataEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SingleMasterChannelEndpointConfigurationTypeDef = TypedDict(
     "SingleMasterChannelEndpointConfigurationTypeDef",
     {
         "Protocols": Sequence[ChannelProtocolType],
         "Role": ChannelRoleType,
     },
     total=False,
@@ -409,24 +422,42 @@
 )
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
 ):
     pass
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "NextToken": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForStreamInputRequestTypeDef = TypedDict(
     "ListTagsForStreamInputRequestTypeDef",
     {
         "NextToken": str,
         "StreamARN": str,
         "StreamName": str,
     },
     total=False,
 )
 
+ListTagsForStreamOutputTypeDef = TypedDict(
+    "ListTagsForStreamOutputTypeDef",
+    {
+        "NextToken": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MediaSourceConfigTypeDef = TypedDict(
     "MediaSourceConfigTypeDef",
     {
         "MediaUriSecretArn": str,
         "MediaUriType": MediaUriTypeType,
     },
 )
@@ -434,22 +465,43 @@
 NotificationDestinationConfigTypeDef = TypedDict(
     "NotificationDestinationConfigTypeDef",
     {
         "Uri": str,
     },
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
 ScheduleConfigTypeDef = TypedDict(
     "ScheduleConfigTypeDef",
     {
         "ScheduleExpression": str,
         "DurationInSeconds": int,
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
 _RequiredTagStreamInputRequestTypeDef = TypedDict(
     "_RequiredTagStreamInputRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
 )
 _OptionalTagStreamInputRequestTypeDef = TypedDict(
@@ -569,14 +621,23 @@
 
 class UpdateSignalingChannelInputRequestTypeDef(
     _RequiredUpdateSignalingChannelInputRequestTypeDef,
     _OptionalUpdateSignalingChannelInputRequestTypeDef,
 ):
     pass
 
+ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef = TypedDict(
+    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
+    {
+        "ChannelNameCondition": ChannelNameConditionTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSignalingChannelsInputRequestTypeDef = TypedDict(
     "ListSignalingChannelsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "ChannelNameCondition": ChannelNameConditionTypeDef,
     },
@@ -609,99 +670,38 @@
     "TagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-CreateSignalingChannelOutputTypeDef = TypedDict(
-    "CreateSignalingChannelOutputTypeDef",
-    {
-        "ChannelARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStreamOutputTypeDef = TypedDict(
-    "CreateStreamOutputTypeDef",
-    {
-        "StreamARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDataEndpointOutputTypeDef = TypedDict(
-    "GetDataEndpointOutputTypeDef",
-    {
-        "DataEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "NextToken": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForStreamOutputTypeDef = TypedDict(
-    "ListTagsForStreamOutputTypeDef",
-    {
-        "NextToken": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DeletionConfigTypeDef = TypedDict(
     "DeletionConfigTypeDef",
     {
         "EdgeRetentionInHours": int,
         "LocalSizeConfig": LocalSizeConfigTypeDef,
         "DeleteAfterUpload": bool,
     },
     total=False,
 )
 
-DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef = TypedDict(
-    "DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef",
-    {
-        "StreamName": str,
-        "StreamARN": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef = TypedDict(
-    "ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef",
-    {
-        "ChannelNameCondition": ChannelNameConditionTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeMappedResourceConfigurationOutputTypeDef = TypedDict(
     "DescribeMappedResourceConfigurationOutputTypeDef",
     {
         "MappedResourceConfigurationList": List[MappedResourceConfigurationListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMediaStorageConfigurationOutputTypeDef = TypedDict(
     "DescribeMediaStorageConfigurationOutputTypeDef",
     {
         "MediaStorageConfiguration": MediaStorageConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMediaStorageConfigurationInputRequestTypeDef = TypedDict(
     "UpdateMediaStorageConfigurationInputRequestTypeDef",
     {
         "ChannelARN": str,
@@ -709,24 +709,24 @@
     },
 )
 
 DescribeStreamOutputTypeDef = TypedDict(
     "DescribeStreamOutputTypeDef",
     {
         "StreamInfo": StreamInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamsOutputTypeDef = TypedDict(
     "ListStreamsOutputTypeDef",
     {
         "StreamInfoList": List[StreamInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetSignalingChannelEndpointInputRequestTypeDef = TypedDict(
     "_RequiredGetSignalingChannelEndpointInputRequestTypeDef",
     {
         "ChannelARN": str,
@@ -746,15 +746,15 @@
 ):
     pass
 
 GetSignalingChannelEndpointOutputTypeDef = TypedDict(
     "GetSignalingChannelEndpointOutputTypeDef",
     {
         "ResourceEndpointList": List[ResourceEndpointListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImageGenerationConfigurationTypeDef = TypedDict(
     "_RequiredImageGenerationConfigurationTypeDef",
     {
         "Status": ConfigurationStatusType,
@@ -779,15 +779,15 @@
 ):
     pass
 
 ListStreamsInputListStreamsPaginateTypeDef = TypedDict(
     "ListStreamsInputListStreamsPaginateTypeDef",
     {
         "StreamNameCondition": StreamNameConditionTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListStreamsInputRequestTypeDef = TypedDict(
     "ListStreamsInputRequestTypeDef",
     {
@@ -830,32 +830,32 @@
     },
 )
 
 DescribeSignalingChannelOutputTypeDef = TypedDict(
     "DescribeSignalingChannelOutputTypeDef",
     {
         "ChannelInfo": ChannelInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSignalingChannelsOutputTypeDef = TypedDict(
     "ListSignalingChannelsOutputTypeDef",
     {
         "ChannelInfoList": List[ChannelInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImageGenerationConfigurationOutputTypeDef = TypedDict(
     "DescribeImageGenerationConfigurationOutputTypeDef",
     {
         "ImageGenerationConfiguration": ImageGenerationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateImageGenerationConfigurationInputRequestTypeDef = TypedDict(
     "UpdateImageGenerationConfigurationInputRequestTypeDef",
     {
         "StreamName": str,
@@ -865,15 +865,15 @@
     total=False,
 )
 
 DescribeNotificationConfigurationOutputTypeDef = TypedDict(
     "DescribeNotificationConfigurationOutputTypeDef",
     {
         "NotificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNotificationConfigurationInputRequestTypeDef = TypedDict(
     "UpdateNotificationConfigurationInputRequestTypeDef",
     {
         "StreamName": str,
@@ -908,15 +908,15 @@
         "StreamName": str,
         "StreamARN": str,
         "CreationTime": datetime,
         "LastUpdatedTime": datetime,
         "SyncStatus": SyncStatusType,
         "FailedStatusDetails": str,
         "EdgeConfig": EdgeConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartEdgeConfigurationUpdateInputRequestTypeDef = TypedDict(
     "_RequiredStartEdgeConfigurationUpdateInputRequestTypeDef",
     {
         "EdgeConfig": EdgeConfigTypeDef,
@@ -943,10 +943,10 @@
         "StreamName": str,
         "StreamARN": str,
         "CreationTime": datetime,
         "LastUpdatedTime": datetime,
         "SyncStatus": SyncStatusType,
         "FailedStatusDetails": str,
         "EdgeConfig": EdgeConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/PKG-INFO` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kinesisvideo
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KinesisVideo 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KinesisVideo 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kinesisvideo"></a>
 
 # types-aiobotocore-kinesisvideo
 
 [![PyPI - types-aiobotocore-kinesisvideo](https://img.shields.io/pypi/v/types-aiobotocore-kinesisvideo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisvideo)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kinesisvideo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kinesisvideo)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kinesisvideo?color=blue)](https://pypistats.org/packages/types-aiobotocore-kinesisvideo)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KinesisVideo 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
+[aiobotocore.KinesisVideo 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
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
 [types-aiobotocore-kinesisvideo docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kinesisvideo/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,58 +344,58 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kinesisvideo.type_defs import (
     SingleMasterConfigurationTypeDef,
     ChannelNameConditionTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateSignalingChannelOutputTypeDef,
     CreateStreamInputRequestTypeDef,
+    CreateStreamOutputTypeDef,
     DeleteSignalingChannelInputRequestTypeDef,
     DeleteStreamInputRequestTypeDef,
     LocalSizeConfigTypeDef,
     DescribeEdgeConfigurationInputRequestTypeDef,
     DescribeImageGenerationConfigurationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef,
     DescribeMappedResourceConfigurationInputRequestTypeDef,
     MappedResourceConfigurationListItemTypeDef,
     DescribeMediaStorageConfigurationInputRequestTypeDef,
     MediaStorageConfigurationTypeDef,
     DescribeNotificationConfigurationInputRequestTypeDef,
     DescribeSignalingChannelInputRequestTypeDef,
     DescribeStreamInputRequestTypeDef,
     StreamInfoTypeDef,
     GetDataEndpointInputRequestTypeDef,
+    GetDataEndpointOutputTypeDef,
     SingleMasterChannelEndpointConfigurationTypeDef,
     ResourceEndpointListItemTypeDef,
     ImageGenerationDestinationConfigTypeDef,
     StreamNameConditionTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ListTagsForStreamInputRequestTypeDef,
+    ListTagsForStreamOutputTypeDef,
     MediaSourceConfigTypeDef,
     NotificationDestinationConfigTypeDef,
+    PaginatorConfigTypeDef,
     ScheduleConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagStreamInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UntagStreamInputRequestTypeDef,
     UpdateDataRetentionInputRequestTypeDef,
     UpdateStreamInputRequestTypeDef,
     ChannelInfoTypeDef,
     UpdateSignalingChannelInputRequestTypeDef,
+    ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef,
     ListSignalingChannelsInputRequestTypeDef,
     CreateSignalingChannelInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
-    CreateSignalingChannelOutputTypeDef,
-    CreateStreamOutputTypeDef,
-    GetDataEndpointOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    ListTagsForStreamOutputTypeDef,
     DeletionConfigTypeDef,
-    DescribeMappedResourceConfigurationInputDescribeMappedResourceConfigurationPaginateTypeDef,
-    ListSignalingChannelsInputListSignalingChannelsPaginateTypeDef,
     DescribeMappedResourceConfigurationOutputTypeDef,
     DescribeMediaStorageConfigurationOutputTypeDef,
     UpdateMediaStorageConfigurationInputRequestTypeDef,
     DescribeStreamOutputTypeDef,
     ListStreamsOutputTypeDef,
     GetSignalingChannelEndpointInputRequestTypeDef,
     GetSignalingChannelEndpointOutputTypeDef,
@@ -425,43 +425,43 @@
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

### Comparing `types-aiobotocore-kinesisvideo-2.5.0.post1/types_aiobotocore_kinesisvideo.egg-info/SOURCES.txt` & `types-aiobotocore-kinesisvideo-2.5.1/types_aiobotocore_kinesisvideo.egg-info/SOURCES.txt`

 * *Files identical despite different names*

