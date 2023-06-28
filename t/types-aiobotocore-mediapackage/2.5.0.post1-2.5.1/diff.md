# Comparing `tmp/types-aiobotocore-mediapackage-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediapackage-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediapackage-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediapackage-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-mediapackage-2.5.0.post1.tar` & `types-aiobotocore-mediapackage-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.779417 types-aiobotocore-mediapackage-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16171 2023-03-11 12:26:58.775417 types-aiobotocore-mediapackage-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14580 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.779417 types-aiobotocore-mediapackage-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.775417 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/
--rw-r--r--   0 runner    (1001) docker     (123)     1102 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1101 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18424 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18393 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10025 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10023 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4499 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25461 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    25438 2023-03-11 12:18:33.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:31.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.775417 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16171 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.826175 types-aiobotocore-mediapackage-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16168 2023-06-28 01:43:49.826175 types-aiobotocore-mediapackage-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14583 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.830175 types-aiobotocore-mediapackage-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.826175 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/
+-rw-r--r--   0 runner    (1001) docker     (123)     1102 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1101 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18424 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18393 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10234 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10232 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4391 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4386 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25785 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25762 2023-06-28 01:35:15.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:13.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.826175 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16168 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/LICENSE` & `types-aiobotocore-mediapackage-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediapackage-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediapackage
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaPackage 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaPackage 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediapackage"></a>
 
 # types-aiobotocore-mediapackage
 
 [![PyPI - types-aiobotocore-mediapackage](https://img.shields.io/pypi/v/types-aiobotocore-mediapackage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediapackage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediapackage?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediapackage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaPackage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
+[aiobotocore.MediaPackage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
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
 [types-aiobotocore-mediapackage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,46 +348,46 @@
 from types_aiobotocore_mediapackage.type_defs import (
     AuthorizationTypeDef,
     EgressAccessLogsTypeDef,
     IngressAccessLogsTypeDef,
     HlsManifestCreateOrUpdateParametersTypeDef,
     StreamSelectionTypeDef,
     HlsManifestTypeDef,
-    ResponseMetadataTypeDef,
     CreateChannelRequestRequestTypeDef,
     S3DestinationTypeDef,
     DeleteChannelRequestRequestTypeDef,
     DeleteOriginEndpointRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeHarvestJobRequestRequestTypeDef,
     DescribeOriginEndpointRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionContractConfigurationTypeDef,
     IngestEndpointTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListHarvestJobsRequestListHarvestJobsPaginateTypeDef,
     ListHarvestJobsRequestRequestTypeDef,
+    ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef,
     ListOriginEndpointsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RotateChannelCredentialsRequestRequestTypeDef,
     RotateIngestEndpointCredentialsRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
     ConfigureLogsRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateHarvestJobRequestRequestTypeDef,
     CreateHarvestJobResponseTypeDef,
     DescribeHarvestJobResponseTypeDef,
     HarvestJobTypeDef,
     SpekeKeyProviderTypeDef,
     HlsIngestTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListHarvestJobsRequestListHarvestJobsPaginateTypeDef,
-    ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef,
     ListHarvestJobsResponseTypeDef,
     CmafEncryptionTypeDef,
     DashEncryptionTypeDef,
     HlsEncryptionTypeDef,
     MssEncryptionTypeDef,
     ChannelTypeDef,
     ConfigureLogsResponseTypeDef,
@@ -419,43 +419,43 @@
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/README.md` & `types-aiobotocore-mediapackage-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediapackage"></a>
 
 # types-aiobotocore-mediapackage
 
 [![PyPI - types-aiobotocore-mediapackage](https://img.shields.io/pypi/v/types-aiobotocore-mediapackage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediapackage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediapackage?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediapackage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaPackage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
+[aiobotocore.MediaPackage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
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
 [types-aiobotocore-mediapackage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,46 +315,46 @@
 from types_aiobotocore_mediapackage.type_defs import (
     AuthorizationTypeDef,
     EgressAccessLogsTypeDef,
     IngressAccessLogsTypeDef,
     HlsManifestCreateOrUpdateParametersTypeDef,
     StreamSelectionTypeDef,
     HlsManifestTypeDef,
-    ResponseMetadataTypeDef,
     CreateChannelRequestRequestTypeDef,
     S3DestinationTypeDef,
     DeleteChannelRequestRequestTypeDef,
     DeleteOriginEndpointRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeHarvestJobRequestRequestTypeDef,
     DescribeOriginEndpointRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionContractConfigurationTypeDef,
     IngestEndpointTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListHarvestJobsRequestListHarvestJobsPaginateTypeDef,
     ListHarvestJobsRequestRequestTypeDef,
+    ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef,
     ListOriginEndpointsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RotateChannelCredentialsRequestRequestTypeDef,
     RotateIngestEndpointCredentialsRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
     ConfigureLogsRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateHarvestJobRequestRequestTypeDef,
     CreateHarvestJobResponseTypeDef,
     DescribeHarvestJobResponseTypeDef,
     HarvestJobTypeDef,
     SpekeKeyProviderTypeDef,
     HlsIngestTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListHarvestJobsRequestListHarvestJobsPaginateTypeDef,
-    ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef,
     ListHarvestJobsResponseTypeDef,
     CmafEncryptionTypeDef,
     DashEncryptionTypeDef,
     HlsEncryptionTypeDef,
     MssEncryptionTypeDef,
     ChannelTypeDef,
     ConfigureLogsResponseTypeDef,
@@ -386,43 +386,43 @@
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/setup.py` & `types-aiobotocore-mediapackage-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediapackage.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediapackage",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediapackage"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaPackage 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaPackage 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/"
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/__init__.py` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/__init__.pyi` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/__main__.py` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaPackage 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaPackage 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage\nOther"
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/client.py` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/client.pyi` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/literals.py` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -149,14 +149,15 @@
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
@@ -235,14 +236,15 @@
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
@@ -253,14 +255,15 @@
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
@@ -296,14 +299,15 @@
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
@@ -322,16 +326,19 @@
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
@@ -415,15 +422,17 @@
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/literals.pyi` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -147,14 +147,15 @@
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
@@ -233,14 +234,15 @@
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
@@ -251,14 +253,15 @@
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
@@ -294,14 +297,15 @@
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
@@ -320,16 +324,19 @@
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
@@ -413,15 +420,17 @@
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/paginator.py` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: MediaPackageClient
 
         list_channels_paginator: ListChannelsPaginator = client.get_paginator("list_channels")
         list_harvest_jobs_paginator: ListHarvestJobsPaginator = client.get_paginator("list_harvest_jobs")
         list_origin_endpoints_paginator: ListOriginEndpointsPaginator = client.get_paginator("list_origin_endpoints")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChannelsResponseTypeDef,
     ListHarvestJobsResponseTypeDef,
     ListOriginEndpointsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListChannelsPaginator", "ListHarvestJobsPaginator", "ListOriginEndpointsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -59,15 +52,15 @@
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listchannelspaginator)
         """
 
 
@@ -78,28 +71,28 @@
     """
 
     def paginate(
         self,
         *,
         IncludeChannelId: str = ...,
         IncludeStatus: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHarvestJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListHarvestJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listharvestjobspaginator)
         """
 
 
 class ListOriginEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListOriginEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listoriginendpointspaginator)
     """
 
     def paginate(
-        self, *, ChannelId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ChannelId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOriginEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListOriginEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listoriginendpointspaginator)
         """
```

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/paginator.pyi` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: MediaPackageClient
 
         list_channels_paginator: ListChannelsPaginator = client.get_paginator("list_channels")
         list_harvest_jobs_paginator: ListHarvestJobsPaginator = client.get_paginator("list_harvest_jobs")
         list_origin_endpoints_paginator: ListOriginEndpointsPaginator = client.get_paginator("list_origin_endpoints")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChannelsResponseTypeDef,
     ListHarvestJobsResponseTypeDef,
     ListOriginEndpointsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListChannelsPaginator", "ListHarvestJobsPaginator", "ListOriginEndpointsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -55,15 +49,15 @@
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listchannelspaginator)
         """
 
 class ListHarvestJobsPaginator(AioPaginator):
@@ -73,27 +67,27 @@
     """
 
     def paginate(
         self,
         *,
         IncludeChannelId: str = ...,
         IncludeStatus: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHarvestJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListHarvestJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listharvestjobspaginator)
         """
 
 class ListOriginEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListOriginEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listoriginendpointspaginator)
     """
 
     def paginate(
-        self, *, ChannelId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ChannelId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOriginEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage.Paginator.ListOriginEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/paginators/#listoriginendpointspaginator)
         """
```

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/type_defs.py` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -45,46 +45,46 @@
 __all__ = (
     "AuthorizationTypeDef",
     "EgressAccessLogsTypeDef",
     "IngressAccessLogsTypeDef",
     "HlsManifestCreateOrUpdateParametersTypeDef",
     "StreamSelectionTypeDef",
     "HlsManifestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "S3DestinationTypeDef",
     "DeleteChannelRequestRequestTypeDef",
     "DeleteOriginEndpointRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DescribeHarvestJobRequestRequestTypeDef",
     "DescribeOriginEndpointRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionContractConfigurationTypeDef",
     "IngestEndpointTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
     "ListHarvestJobsRequestRequestTypeDef",
+    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
     "ListOriginEndpointsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RotateChannelCredentialsRequestRequestTypeDef",
     "RotateIngestEndpointCredentialsRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateChannelRequestRequestTypeDef",
     "ConfigureLogsRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateHarvestJobRequestRequestTypeDef",
     "CreateHarvestJobResponseTypeDef",
     "DescribeHarvestJobResponseTypeDef",
     "HarvestJobTypeDef",
     "SpekeKeyProviderTypeDef",
     "HlsIngestTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
-    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
     "ListHarvestJobsResponseTypeDef",
     "CmafEncryptionTypeDef",
     "DashEncryptionTypeDef",
     "HlsEncryptionTypeDef",
     "MssEncryptionTypeDef",
     "ChannelTypeDef",
     "ConfigureLogsResponseTypeDef",
@@ -194,25 +194,14 @@
 )
 
 
 class HlsManifestTypeDef(_RequiredHlsManifestTypeDef, _OptionalHlsManifestTypeDef):
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
 _RequiredCreateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalCreateChannelRequestRequestTypeDef = TypedDict(
@@ -271,14 +260,21 @@
 DescribeOriginEndpointRequestRequestTypeDef = TypedDict(
     "DescribeOriginEndpointRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EncryptionContractConfigurationTypeDef = TypedDict(
     "EncryptionContractConfigurationTypeDef",
     {
         "PresetSpeke20Audio": PresetSpeke20AudioType,
         "PresetSpeke20Video": PresetSpeke20VideoType,
     },
 )
@@ -290,44 +286,61 @@
         "Password": str,
         "Url": str,
         "Username": str,
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
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListHarvestJobsRequestListHarvestJobsPaginateTypeDef = TypedDict(
+    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
+    {
+        "IncludeChannelId": str,
+        "IncludeStatus": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHarvestJobsRequestRequestTypeDef = TypedDict(
     "ListHarvestJobsRequestRequestTypeDef",
     {
         "IncludeChannelId": str,
         "IncludeStatus": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef = TypedDict(
+    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
+    {
+        "ChannelId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOriginEndpointsRequestRequestTypeDef = TypedDict(
     "ListOriginEndpointsRequestRequestTypeDef",
     {
         "ChannelId": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -337,14 +350,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
 RotateChannelCredentialsRequestRequestTypeDef = TypedDict(
     "RotateChannelCredentialsRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -411,29 +453,14 @@
 
 class ConfigureLogsRequestRequestTypeDef(
     _RequiredConfigureLogsRequestRequestTypeDef, _OptionalConfigureLogsRequestRequestTypeDef
 ):
     pass
 
 
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
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateHarvestJobRequestRequestTypeDef = TypedDict(
     "CreateHarvestJobRequestRequestTypeDef",
     {
         "EndTime": str,
         "Id": str,
         "OriginEndpointId": str,
         "S3Destination": S3DestinationTypeDef,
@@ -449,15 +476,15 @@
         "CreatedAt": str,
         "EndTime": str,
         "Id": str,
         "OriginEndpointId": str,
         "S3Destination": S3DestinationTypeDef,
         "StartTime": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHarvestJobResponseTypeDef = TypedDict(
     "DescribeHarvestJobResponseTypeDef",
     {
         "Arn": str,
@@ -465,15 +492,15 @@
         "CreatedAt": str,
         "EndTime": str,
         "Id": str,
         "OriginEndpointId": str,
         "S3Destination": S3DestinationTypeDef,
         "StartTime": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HarvestJobTypeDef = TypedDict(
     "HarvestJobTypeDef",
     {
         "Arn": str,
@@ -516,47 +543,20 @@
     "HlsIngestTypeDef",
     {
         "IngestEndpoints": List[IngestEndpointTypeDef],
     },
     total=False,
 )
 
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHarvestJobsRequestListHarvestJobsPaginateTypeDef = TypedDict(
-    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
-    {
-        "IncludeChannelId": str,
-        "IncludeStatus": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef = TypedDict(
-    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
-    {
-        "ChannelId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListHarvestJobsResponseTypeDef = TypedDict(
     "ListHarvestJobsResponseTypeDef",
     {
         "HarvestJobs": List[HarvestJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCmafEncryptionTypeDef = TypedDict(
     "_RequiredCmafEncryptionTypeDef",
     {
         "SpekeKeyProvider": SpekeKeyProviderTypeDef,
@@ -625,105 +625,112 @@
     },
 )
 
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
 ConfigureLogsResponseTypeDef = TypedDict(
     "ConfigureLogsResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RotateChannelCredentialsResponseTypeDef = TypedDict(
     "RotateChannelCredentialsResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RotateIngestEndpointCredentialsResponseTypeDef = TypedDict(
     "RotateIngestEndpointCredentialsResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CmafPackageCreateOrUpdateParametersTypeDef = TypedDict(
     "CmafPackageCreateOrUpdateParametersTypeDef",
     {
         "Encryption": CmafEncryptionTypeDef,
@@ -801,15 +808,15 @@
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "Channels": List[ChannelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateOriginEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateOriginEndpointRequestRequestTypeDef",
     {
         "ChannelId": str,
@@ -846,60 +853,63 @@
 CreateOriginEndpointResponseTypeDef = TypedDict(
     "CreateOriginEndpointResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
         "StartoverWindowSeconds": int,
         "Tags": Dict[str, str],
         "TimeDelaySeconds": int,
         "Url": str,
         "Whitelist": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOriginEndpointResponseTypeDef = TypedDict(
     "DescribeOriginEndpointResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
         "StartoverWindowSeconds": int,
         "Tags": Dict[str, str],
         "TimeDelaySeconds": int,
         "Url": str,
         "Whitelist": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginEndpointTypeDef = TypedDict(
     "OriginEndpointTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
@@ -947,31 +957,32 @@
 UpdateOriginEndpointResponseTypeDef = TypedDict(
     "UpdateOriginEndpointResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
         "StartoverWindowSeconds": int,
         "Tags": Dict[str, str],
         "TimeDelaySeconds": int,
         "Url": str,
         "Whitelist": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOriginEndpointsResponseTypeDef = TypedDict(
     "ListOriginEndpointsResponseTypeDef",
     {
         "NextToken": str,
         "OriginEndpoints": List[OriginEndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage/type_defs.pyi` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -44,46 +44,46 @@
 __all__ = (
     "AuthorizationTypeDef",
     "EgressAccessLogsTypeDef",
     "IngressAccessLogsTypeDef",
     "HlsManifestCreateOrUpdateParametersTypeDef",
     "StreamSelectionTypeDef",
     "HlsManifestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "S3DestinationTypeDef",
     "DeleteChannelRequestRequestTypeDef",
     "DeleteOriginEndpointRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DescribeHarvestJobRequestRequestTypeDef",
     "DescribeOriginEndpointRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionContractConfigurationTypeDef",
     "IngestEndpointTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
     "ListHarvestJobsRequestRequestTypeDef",
+    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
     "ListOriginEndpointsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RotateChannelCredentialsRequestRequestTypeDef",
     "RotateIngestEndpointCredentialsRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateChannelRequestRequestTypeDef",
     "ConfigureLogsRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateHarvestJobRequestRequestTypeDef",
     "CreateHarvestJobResponseTypeDef",
     "DescribeHarvestJobResponseTypeDef",
     "HarvestJobTypeDef",
     "SpekeKeyProviderTypeDef",
     "HlsIngestTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
-    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
     "ListHarvestJobsResponseTypeDef",
     "CmafEncryptionTypeDef",
     "DashEncryptionTypeDef",
     "HlsEncryptionTypeDef",
     "MssEncryptionTypeDef",
     "ChannelTypeDef",
     "ConfigureLogsResponseTypeDef",
@@ -189,25 +189,14 @@
     },
     total=False,
 )
 
 class HlsManifestTypeDef(_RequiredHlsManifestTypeDef, _OptionalHlsManifestTypeDef):
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
 _RequiredCreateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalCreateChannelRequestRequestTypeDef = TypedDict(
@@ -264,14 +253,21 @@
 DescribeOriginEndpointRequestRequestTypeDef = TypedDict(
     "DescribeOriginEndpointRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EncryptionContractConfigurationTypeDef = TypedDict(
     "EncryptionContractConfigurationTypeDef",
     {
         "PresetSpeke20Audio": PresetSpeke20AudioType,
         "PresetSpeke20Video": PresetSpeke20VideoType,
     },
 )
@@ -283,44 +279,61 @@
         "Password": str,
         "Url": str,
         "Username": str,
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
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListHarvestJobsRequestListHarvestJobsPaginateTypeDef = TypedDict(
+    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
+    {
+        "IncludeChannelId": str,
+        "IncludeStatus": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHarvestJobsRequestRequestTypeDef = TypedDict(
     "ListHarvestJobsRequestRequestTypeDef",
     {
         "IncludeChannelId": str,
         "IncludeStatus": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef = TypedDict(
+    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
+    {
+        "ChannelId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOriginEndpointsRequestRequestTypeDef = TypedDict(
     "ListOriginEndpointsRequestRequestTypeDef",
     {
         "ChannelId": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -330,14 +343,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
 RotateChannelCredentialsRequestRequestTypeDef = TypedDict(
     "RotateChannelCredentialsRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -400,29 +442,14 @@
 )
 
 class ConfigureLogsRequestRequestTypeDef(
     _RequiredConfigureLogsRequestRequestTypeDef, _OptionalConfigureLogsRequestRequestTypeDef
 ):
     pass
 
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
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateHarvestJobRequestRequestTypeDef = TypedDict(
     "CreateHarvestJobRequestRequestTypeDef",
     {
         "EndTime": str,
         "Id": str,
         "OriginEndpointId": str,
         "S3Destination": S3DestinationTypeDef,
@@ -438,15 +465,15 @@
         "CreatedAt": str,
         "EndTime": str,
         "Id": str,
         "OriginEndpointId": str,
         "S3Destination": S3DestinationTypeDef,
         "StartTime": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHarvestJobResponseTypeDef = TypedDict(
     "DescribeHarvestJobResponseTypeDef",
     {
         "Arn": str,
@@ -454,15 +481,15 @@
         "CreatedAt": str,
         "EndTime": str,
         "Id": str,
         "OriginEndpointId": str,
         "S3Destination": S3DestinationTypeDef,
         "StartTime": str,
         "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HarvestJobTypeDef = TypedDict(
     "HarvestJobTypeDef",
     {
         "Arn": str,
@@ -503,47 +530,20 @@
     "HlsIngestTypeDef",
     {
         "IngestEndpoints": List[IngestEndpointTypeDef],
     },
     total=False,
 )
 
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListHarvestJobsRequestListHarvestJobsPaginateTypeDef = TypedDict(
-    "ListHarvestJobsRequestListHarvestJobsPaginateTypeDef",
-    {
-        "IncludeChannelId": str,
-        "IncludeStatus": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef = TypedDict(
-    "ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef",
-    {
-        "ChannelId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListHarvestJobsResponseTypeDef = TypedDict(
     "ListHarvestJobsResponseTypeDef",
     {
         "HarvestJobs": List[HarvestJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCmafEncryptionTypeDef = TypedDict(
     "_RequiredCmafEncryptionTypeDef",
     {
         "SpekeKeyProvider": SpekeKeyProviderTypeDef,
@@ -606,105 +606,112 @@
     },
 )
 
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
 ConfigureLogsResponseTypeDef = TypedDict(
     "ConfigureLogsResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RotateChannelCredentialsResponseTypeDef = TypedDict(
     "RotateChannelCredentialsResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RotateIngestEndpointCredentialsResponseTypeDef = TypedDict(
     "RotateIngestEndpointCredentialsResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "Arn": str,
+        "CreatedAt": str,
         "Description": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "HlsIngest": HlsIngestTypeDef,
         "Id": str,
         "IngressAccessLogs": IngressAccessLogsTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CmafPackageCreateOrUpdateParametersTypeDef = TypedDict(
     "CmafPackageCreateOrUpdateParametersTypeDef",
     {
         "Encryption": CmafEncryptionTypeDef,
@@ -782,15 +789,15 @@
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "Channels": List[ChannelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateOriginEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateOriginEndpointRequestRequestTypeDef",
     {
         "ChannelId": str,
@@ -825,60 +832,63 @@
 CreateOriginEndpointResponseTypeDef = TypedDict(
     "CreateOriginEndpointResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
         "StartoverWindowSeconds": int,
         "Tags": Dict[str, str],
         "TimeDelaySeconds": int,
         "Url": str,
         "Whitelist": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOriginEndpointResponseTypeDef = TypedDict(
     "DescribeOriginEndpointResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
         "StartoverWindowSeconds": int,
         "Tags": Dict[str, str],
         "TimeDelaySeconds": int,
         "Url": str,
         "Whitelist": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginEndpointTypeDef = TypedDict(
     "OriginEndpointTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
@@ -924,31 +934,32 @@
 UpdateOriginEndpointResponseTypeDef = TypedDict(
     "UpdateOriginEndpointResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
         "ChannelId": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "Description": str,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "ManifestName": str,
         "MssPackage": MssPackageTypeDef,
         "Origination": OriginationType,
         "StartoverWindowSeconds": int,
         "Tags": Dict[str, str],
         "TimeDelaySeconds": int,
         "Url": str,
         "Whitelist": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOriginEndpointsResponseTypeDef = TypedDict(
     "ListOriginEndpointsResponseTypeDef",
     {
         "NextToken": str,
         "OriginEndpoints": List[OriginEndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/PKG-INFO` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediapackage
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaPackage 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaPackage 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediapackage"></a>
 
 # types-aiobotocore-mediapackage
 
 [![PyPI - types-aiobotocore-mediapackage](https://img.shields.io/pypi/v/types-aiobotocore-mediapackage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediapackage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediapackage?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediapackage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaPackage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
+[aiobotocore.MediaPackage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage.html#MediaPackage)
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
 [types-aiobotocore-mediapackage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,46 +348,46 @@
 from types_aiobotocore_mediapackage.type_defs import (
     AuthorizationTypeDef,
     EgressAccessLogsTypeDef,
     IngressAccessLogsTypeDef,
     HlsManifestCreateOrUpdateParametersTypeDef,
     StreamSelectionTypeDef,
     HlsManifestTypeDef,
-    ResponseMetadataTypeDef,
     CreateChannelRequestRequestTypeDef,
     S3DestinationTypeDef,
     DeleteChannelRequestRequestTypeDef,
     DeleteOriginEndpointRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeHarvestJobRequestRequestTypeDef,
     DescribeOriginEndpointRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionContractConfigurationTypeDef,
     IngestEndpointTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListHarvestJobsRequestListHarvestJobsPaginateTypeDef,
     ListHarvestJobsRequestRequestTypeDef,
+    ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef,
     ListOriginEndpointsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RotateChannelCredentialsRequestRequestTypeDef,
     RotateIngestEndpointCredentialsRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
     ConfigureLogsRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateHarvestJobRequestRequestTypeDef,
     CreateHarvestJobResponseTypeDef,
     DescribeHarvestJobResponseTypeDef,
     HarvestJobTypeDef,
     SpekeKeyProviderTypeDef,
     HlsIngestTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListHarvestJobsRequestListHarvestJobsPaginateTypeDef,
-    ListOriginEndpointsRequestListOriginEndpointsPaginateTypeDef,
     ListHarvestJobsResponseTypeDef,
     CmafEncryptionTypeDef,
     DashEncryptionTypeDef,
     HlsEncryptionTypeDef,
     MssEncryptionTypeDef,
     ChannelTypeDef,
     ConfigureLogsResponseTypeDef,
@@ -419,43 +419,43 @@
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

### Comparing `types-aiobotocore-mediapackage-2.5.0.post1/types_aiobotocore_mediapackage.egg-info/SOURCES.txt` & `types-aiobotocore-mediapackage-2.5.1/types_aiobotocore_mediapackage.egg-info/SOURCES.txt`

 * *Files identical despite different names*

