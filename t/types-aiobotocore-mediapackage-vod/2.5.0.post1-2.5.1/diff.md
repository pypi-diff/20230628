# Comparing `tmp/types-aiobotocore-mediapackage-vod-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediapackage-vod-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediapackage-vod-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediapackage-vod-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1.tar` & `types-aiobotocore-mediapackage-vod-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.955419 types-aiobotocore-mediapackage-vod-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16034 2023-03-11 12:26:58.951419 types-aiobotocore-mediapackage-vod-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14428 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.955419 types-aiobotocore-mediapackage-vod-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.951419 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/
--rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1205 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      977 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16842 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16813 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9262 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9260 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4681 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4675 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19927 2023-03-11 12:18:35.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19902 2023-03-11 12:18:35.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:34.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.951419 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16034 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:58.000000 types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.846175 types-aiobotocore-mediapackage-vod-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16035 2023-06-28 01:43:49.846175 types-aiobotocore-mediapackage-vod-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14435 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.846175 types-aiobotocore-mediapackage-vod-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.846175 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/
+-rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1205 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16842 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16813 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9471 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9469 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4567 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4562 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    20167 2023-06-28 01:35:17.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20142 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:16.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.846175 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16035 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:49.000000 types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/LICENSE` & `types-aiobotocore-mediapackage-vod-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediapackage-vod-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediapackage-vod
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaPackageVod 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaPackageVod 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediapackage-vod"></a>
 
 # types-aiobotocore-mediapackage-vod
 
 [![PyPI - types-aiobotocore-mediapackage-vod](https://img.shields.io/pypi/v/types-aiobotocore-mediapackage-vod.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage-vod)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediapackage-vod.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage-vod)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediapackage-vod?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediapackage-vod)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaPackageVod 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod)
+[aiobotocore.MediaPackageVod 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod)
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
 [types-aiobotocore-mediapackage-vod docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,52 +339,52 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediapackage_vod.type_defs import (
     AssetShallowTypeDef,
     AuthorizationTypeDef,
     EgressAccessLogsTypeDef,
-    ResponseMetadataTypeDef,
     CreateAssetRequestRequestTypeDef,
     EgressEndpointTypeDef,
     StreamSelectionTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeletePackagingConfigurationRequestRequestTypeDef,
     DeletePackagingGroupRequestRequestTypeDef,
     DescribeAssetRequestRequestTypeDef,
     DescribePackagingConfigurationRequestRequestTypeDef,
     DescribePackagingGroupRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionContractConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssetsRequestListAssetsPaginateTypeDef,
     ListAssetsRequestRequestTypeDef,
+    ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef,
     ListPackagingConfigurationsRequestRequestTypeDef,
+    ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef,
     ListPackagingGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListAssetsResponseTypeDef,
     UpdatePackagingGroupRequestRequestTypeDef,
     ConfigureLogsRequestRequestTypeDef,
-    CreatePackagingGroupRequestRequestTypeDef,
-    PackagingGroupTypeDef,
     ConfigureLogsResponseTypeDef,
+    CreatePackagingGroupRequestRequestTypeDef,
     CreatePackagingGroupResponseTypeDef,
     DescribePackagingGroupResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAssetsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    PackagingGroupTypeDef,
     UpdatePackagingGroupResponseTypeDef,
     CreateAssetResponseTypeDef,
     DescribeAssetResponseTypeDef,
     DashManifestTypeDef,
     HlsManifestTypeDef,
     MssManifestTypeDef,
     SpekeKeyProviderTypeDef,
-    ListAssetsRequestListAssetsPaginateTypeDef,
-    ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef,
-    ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef,
     ListPackagingGroupsResponseTypeDef,
     CmafEncryptionTypeDef,
     DashEncryptionTypeDef,
     HlsEncryptionTypeDef,
     MssEncryptionTypeDef,
     CmafPackageTypeDef,
     DashPackageTypeDef,
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/README.md` & `types-aiobotocore-mediapackage-vod-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediapackage-vod"></a>
 
 # types-aiobotocore-mediapackage-vod
 
 [![PyPI - types-aiobotocore-mediapackage-vod](https://img.shields.io/pypi/v/types-aiobotocore-mediapackage-vod.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage-vod)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediapackage-vod.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage-vod)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediapackage-vod?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediapackage-vod)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaPackageVod 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod)
+[aiobotocore.MediaPackageVod 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod)
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
 [types-aiobotocore-mediapackage-vod docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,52 +306,52 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediapackage_vod.type_defs import (
     AssetShallowTypeDef,
     AuthorizationTypeDef,
     EgressAccessLogsTypeDef,
-    ResponseMetadataTypeDef,
     CreateAssetRequestRequestTypeDef,
     EgressEndpointTypeDef,
     StreamSelectionTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeletePackagingConfigurationRequestRequestTypeDef,
     DeletePackagingGroupRequestRequestTypeDef,
     DescribeAssetRequestRequestTypeDef,
     DescribePackagingConfigurationRequestRequestTypeDef,
     DescribePackagingGroupRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionContractConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssetsRequestListAssetsPaginateTypeDef,
     ListAssetsRequestRequestTypeDef,
+    ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef,
     ListPackagingConfigurationsRequestRequestTypeDef,
+    ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef,
     ListPackagingGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListAssetsResponseTypeDef,
     UpdatePackagingGroupRequestRequestTypeDef,
     ConfigureLogsRequestRequestTypeDef,
-    CreatePackagingGroupRequestRequestTypeDef,
-    PackagingGroupTypeDef,
     ConfigureLogsResponseTypeDef,
+    CreatePackagingGroupRequestRequestTypeDef,
     CreatePackagingGroupResponseTypeDef,
     DescribePackagingGroupResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAssetsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    PackagingGroupTypeDef,
     UpdatePackagingGroupResponseTypeDef,
     CreateAssetResponseTypeDef,
     DescribeAssetResponseTypeDef,
     DashManifestTypeDef,
     HlsManifestTypeDef,
     MssManifestTypeDef,
     SpekeKeyProviderTypeDef,
-    ListAssetsRequestListAssetsPaginateTypeDef,
-    ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef,
-    ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef,
     ListPackagingGroupsResponseTypeDef,
     CmafEncryptionTypeDef,
     DashEncryptionTypeDef,
     HlsEncryptionTypeDef,
     MssEncryptionTypeDef,
     CmafPackageTypeDef,
     DashPackageTypeDef,
@@ -372,43 +372,43 @@
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/setup.py` & `types-aiobotocore-mediapackage-vod-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediapackage-vod.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediapackage-vod",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediapackage_vod"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaPackageVod 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaPackageVod 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/"
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/__init__.py` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/__init__.pyi` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/__main__.py` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaPackageVod 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaPackageVod 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod\nOther"
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/client.py` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/client.pyi` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/literals.py` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -128,14 +128,15 @@
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
@@ -214,14 +215,15 @@
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
@@ -232,14 +234,15 @@
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
@@ -275,14 +278,15 @@
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
@@ -301,16 +305,19 @@
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
@@ -394,15 +401,17 @@
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/literals.pyi` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -126,14 +126,15 @@
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
@@ -212,14 +213,15 @@
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
@@ -230,14 +232,15 @@
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
@@ -273,14 +276,15 @@
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
@@ -299,16 +303,19 @@
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
@@ -392,15 +399,17 @@
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/paginator.py` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: MediaPackageVodClient
 
         list_assets_paginator: ListAssetsPaginator = client.get_paginator("list_assets")
         list_packaging_configurations_paginator: ListPackagingConfigurationsPaginator = client.get_paginator("list_packaging_configurations")
         list_packaging_groups_paginator: ListPackagingGroupsPaginator = client.get_paginator("list_packaging_groups")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAssetsResponseTypeDef,
     ListPackagingConfigurationsResponseTypeDef,
     ListPackagingGroupsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAssetsPaginator",
     "ListPackagingConfigurationsPaginator",
     "ListPackagingGroupsPaginator",
 )
 
 
@@ -63,43 +56,43 @@
 class ListAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listassetspaginator)
     """
 
     def paginate(
-        self, *, PackagingGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PackagingGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listassetspaginator)
         """
 
 
 class ListPackagingConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackagingconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PackagingGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PackagingGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackagingConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackagingconfigurationspaginator)
         """
 
 
 class ListPackagingGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackaginggroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackagingGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackaginggroupspaginator)
         """
```

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/paginator.pyi` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: MediaPackageVodClient
 
         list_assets_paginator: ListAssetsPaginator = client.get_paginator("list_assets")
         list_packaging_configurations_paginator: ListPackagingConfigurationsPaginator = client.get_paginator("list_packaging_configurations")
         list_packaging_groups_paginator: ListPackagingGroupsPaginator = client.get_paginator("list_packaging_groups")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAssetsResponseTypeDef,
     ListPackagingConfigurationsResponseTypeDef,
     ListPackagingGroupsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAssetsPaginator",
     "ListPackagingConfigurationsPaginator",
     "ListPackagingGroupsPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -59,41 +53,41 @@
 class ListAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listassetspaginator)
     """
 
     def paginate(
-        self, *, PackagingGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PackagingGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listassetspaginator)
         """
 
 class ListPackagingConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackagingconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PackagingGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PackagingGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackagingConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackagingconfigurationspaginator)
         """
 
 class ListPackagingGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackaginggroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPackagingGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod.Paginator.ListPackagingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/paginators/#listpackaginggroupspaginator)
         """
```

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/type_defs.py` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -36,52 +36,52 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssetShallowTypeDef",
     "AuthorizationTypeDef",
     "EgressAccessLogsTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateAssetRequestRequestTypeDef",
     "EgressEndpointTypeDef",
     "StreamSelectionTypeDef",
     "DeleteAssetRequestRequestTypeDef",
     "DeletePackagingConfigurationRequestRequestTypeDef",
     "DeletePackagingGroupRequestRequestTypeDef",
     "DescribeAssetRequestRequestTypeDef",
     "DescribePackagingConfigurationRequestRequestTypeDef",
     "DescribePackagingGroupRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionContractConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssetsRequestListAssetsPaginateTypeDef",
     "ListAssetsRequestRequestTypeDef",
+    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
     "ListPackagingConfigurationsRequestRequestTypeDef",
+    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
     "ListPackagingGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "ListAssetsResponseTypeDef",
     "UpdatePackagingGroupRequestRequestTypeDef",
     "ConfigureLogsRequestRequestTypeDef",
-    "CreatePackagingGroupRequestRequestTypeDef",
-    "PackagingGroupTypeDef",
     "ConfigureLogsResponseTypeDef",
+    "CreatePackagingGroupRequestRequestTypeDef",
     "CreatePackagingGroupResponseTypeDef",
     "DescribePackagingGroupResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListAssetsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "PackagingGroupTypeDef",
     "UpdatePackagingGroupResponseTypeDef",
     "CreateAssetResponseTypeDef",
     "DescribeAssetResponseTypeDef",
     "DashManifestTypeDef",
     "HlsManifestTypeDef",
     "MssManifestTypeDef",
     "SpekeKeyProviderTypeDef",
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
-    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
     "ListPackagingGroupsResponseTypeDef",
     "CmafEncryptionTypeDef",
     "DashEncryptionTypeDef",
     "HlsEncryptionTypeDef",
     "MssEncryptionTypeDef",
     "CmafPackageTypeDef",
     "DashPackageTypeDef",
@@ -121,25 +121,14 @@
     "EgressAccessLogsTypeDef",
     {
         "LogGroupName": str,
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
 _RequiredCreateAssetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssetRequestRequestTypeDef",
     {
         "Id": str,
         "PackagingGroupId": str,
         "SourceArn": str,
         "SourceRoleArn": str,
@@ -219,52 +208,75 @@
 DescribePackagingGroupRequestRequestTypeDef = TypedDict(
     "DescribePackagingGroupRequestRequestTypeDef",
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
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
+    "ListAssetsRequestListAssetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PackagingGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAssetsRequestRequestTypeDef = TypedDict(
     "ListAssetsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "PackagingGroupId": str,
     },
     total=False,
 )
 
+ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef = TypedDict(
+    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
+    {
+        "PackagingGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPackagingConfigurationsRequestRequestTypeDef = TypedDict(
     "ListPackagingConfigurationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "PackagingGroupId": str,
     },
     total=False,
 )
 
+ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef = TypedDict(
+    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPackagingGroupsRequestRequestTypeDef = TypedDict(
     "ListPackagingGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -273,14 +285,43 @@
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -289,14 +330,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+ListAssetsResponseTypeDef = TypedDict(
+    "ListAssetsResponseTypeDef",
+    {
+        "Assets": List[AssetShallowTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdatePackagingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePackagingGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdatePackagingGroupRequestRequestTypeDef = TypedDict(
@@ -332,14 +382,28 @@
 
 class ConfigureLogsRequestRequestTypeDef(
     _RequiredConfigureLogsRequestRequestTypeDef, _OptionalConfigureLogsRequestRequestTypeDef
 ):
     pass
 
 
+ConfigureLogsResponseTypeDef = TypedDict(
+    "ConfigureLogsResponseTypeDef",
+    {
+        "Arn": str,
+        "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
+        "DomainName": str,
+        "EgressAccessLogs": EgressAccessLogsTypeDef,
+        "Id": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePackagingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePackagingGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalCreatePackagingGroupRequestRequestTypeDef = TypedDict(
@@ -356,103 +420,70 @@
 class CreatePackagingGroupRequestRequestTypeDef(
     _RequiredCreatePackagingGroupRequestRequestTypeDef,
     _OptionalCreatePackagingGroupRequestRequestTypeDef,
 ):
     pass
 
 
-PackagingGroupTypeDef = TypedDict(
-    "PackagingGroupTypeDef",
-    {
-        "ApproximateAssetCount": int,
-        "Arn": str,
-        "Authorization": AuthorizationTypeDef,
-        "DomainName": str,
-        "EgressAccessLogs": EgressAccessLogsTypeDef,
-        "Id": str,
-        "Tags": Dict[str, str],
-    },
-    total=False,
-)
-
-ConfigureLogsResponseTypeDef = TypedDict(
-    "ConfigureLogsResponseTypeDef",
+CreatePackagingGroupResponseTypeDef = TypedDict(
+    "CreatePackagingGroupResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreatePackagingGroupResponseTypeDef = TypedDict(
-    "CreatePackagingGroupResponseTypeDef",
+DescribePackagingGroupResponseTypeDef = TypedDict(
+    "DescribePackagingGroupResponseTypeDef",
     {
+        "ApproximateAssetCount": int,
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribePackagingGroupResponseTypeDef = TypedDict(
-    "DescribePackagingGroupResponseTypeDef",
+PackagingGroupTypeDef = TypedDict(
+    "PackagingGroupTypeDef",
     {
         "ApproximateAssetCount": int,
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
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
-ListAssetsResponseTypeDef = TypedDict(
-    "ListAssetsResponseTypeDef",
-    {
-        "Assets": List[AssetShallowTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
 UpdatePackagingGroupResponseTypeDef = TypedDict(
     "UpdatePackagingGroupResponseTypeDef",
     {
         "ApproximateAssetCount": int,
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssetResponseTypeDef = TypedDict(
     "CreateAssetResponseTypeDef",
     {
         "Arn": str,
@@ -460,15 +491,15 @@
         "EgressEndpoints": List[EgressEndpointTypeDef],
         "Id": str,
         "PackagingGroupId": str,
         "ResourceId": str,
         "SourceArn": str,
         "SourceRoleArn": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssetResponseTypeDef = TypedDict(
     "DescribeAssetResponseTypeDef",
     {
         "Arn": str,
@@ -476,15 +507,15 @@
         "EgressEndpoints": List[EgressEndpointTypeDef],
         "Id": str,
         "PackagingGroupId": str,
         "ResourceId": str,
         "SourceArn": str,
         "SourceRoleArn": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DashManifestTypeDef = TypedDict(
     "DashManifestTypeDef",
     {
         "ManifestLayout": ManifestLayoutType,
@@ -536,46 +567,20 @@
 )
 
 
 class SpekeKeyProviderTypeDef(_RequiredSpekeKeyProviderTypeDef, _OptionalSpekeKeyProviderTypeDef):
     pass
 
 
-ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    {
-        "PackagingGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef = TypedDict(
-    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
-    {
-        "PackagingGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef = TypedDict(
-    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPackagingGroupsResponseTypeDef = TypedDict(
     "ListPackagingGroupsResponseTypeDef",
     {
         "NextToken": str,
         "PackagingGroups": List[PackagingGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCmafEncryptionTypeDef = TypedDict(
     "_RequiredCmafEncryptionTypeDef",
     {
         "SpekeKeyProvider": SpekeKeyProviderTypeDef,
@@ -743,44 +748,47 @@
 
 
 CreatePackagingConfigurationResponseTypeDef = TypedDict(
     "CreatePackagingConfigurationResponseTypeDef",
     {
         "Arn": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "MssPackage": MssPackageTypeDef,
         "PackagingGroupId": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackagingConfigurationResponseTypeDef = TypedDict(
     "DescribePackagingConfigurationResponseTypeDef",
     {
         "Arn": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "MssPackage": MssPackageTypeDef,
         "PackagingGroupId": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackagingConfigurationTypeDef = TypedDict(
     "PackagingConfigurationTypeDef",
     {
         "Arn": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "MssPackage": MssPackageTypeDef,
         "PackagingGroupId": str,
         "Tags": Dict[str, str],
     },
@@ -788,10 +796,10 @@
 )
 
 ListPackagingConfigurationsResponseTypeDef = TypedDict(
     "ListPackagingConfigurationsResponseTypeDef",
     {
         "NextToken": str,
         "PackagingConfigurations": List[PackagingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod/type_defs.pyi` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod/type_defs.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -35,52 +35,52 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssetShallowTypeDef",
     "AuthorizationTypeDef",
     "EgressAccessLogsTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateAssetRequestRequestTypeDef",
     "EgressEndpointTypeDef",
     "StreamSelectionTypeDef",
     "DeleteAssetRequestRequestTypeDef",
     "DeletePackagingConfigurationRequestRequestTypeDef",
     "DeletePackagingGroupRequestRequestTypeDef",
     "DescribeAssetRequestRequestTypeDef",
     "DescribePackagingConfigurationRequestRequestTypeDef",
     "DescribePackagingGroupRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionContractConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssetsRequestListAssetsPaginateTypeDef",
     "ListAssetsRequestRequestTypeDef",
+    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
     "ListPackagingConfigurationsRequestRequestTypeDef",
+    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
     "ListPackagingGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "ListAssetsResponseTypeDef",
     "UpdatePackagingGroupRequestRequestTypeDef",
     "ConfigureLogsRequestRequestTypeDef",
-    "CreatePackagingGroupRequestRequestTypeDef",
-    "PackagingGroupTypeDef",
     "ConfigureLogsResponseTypeDef",
+    "CreatePackagingGroupRequestRequestTypeDef",
     "CreatePackagingGroupResponseTypeDef",
     "DescribePackagingGroupResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListAssetsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "PackagingGroupTypeDef",
     "UpdatePackagingGroupResponseTypeDef",
     "CreateAssetResponseTypeDef",
     "DescribeAssetResponseTypeDef",
     "DashManifestTypeDef",
     "HlsManifestTypeDef",
     "MssManifestTypeDef",
     "SpekeKeyProviderTypeDef",
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
-    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
     "ListPackagingGroupsResponseTypeDef",
     "CmafEncryptionTypeDef",
     "DashEncryptionTypeDef",
     "HlsEncryptionTypeDef",
     "MssEncryptionTypeDef",
     "CmafPackageTypeDef",
     "DashPackageTypeDef",
@@ -120,25 +120,14 @@
     "EgressAccessLogsTypeDef",
     {
         "LogGroupName": str,
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
 _RequiredCreateAssetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssetRequestRequestTypeDef",
     {
         "Id": str,
         "PackagingGroupId": str,
         "SourceArn": str,
         "SourceRoleArn": str,
@@ -216,52 +205,75 @@
 DescribePackagingGroupRequestRequestTypeDef = TypedDict(
     "DescribePackagingGroupRequestRequestTypeDef",
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
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
+    "ListAssetsRequestListAssetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PackagingGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAssetsRequestRequestTypeDef = TypedDict(
     "ListAssetsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "PackagingGroupId": str,
     },
     total=False,
 )
 
+ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef = TypedDict(
+    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
+    {
+        "PackagingGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPackagingConfigurationsRequestRequestTypeDef = TypedDict(
     "ListPackagingConfigurationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "PackagingGroupId": str,
     },
     total=False,
 )
 
+ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef = TypedDict(
+    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPackagingGroupsRequestRequestTypeDef = TypedDict(
     "ListPackagingGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -270,14 +282,43 @@
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -286,14 +327,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+ListAssetsResponseTypeDef = TypedDict(
+    "ListAssetsResponseTypeDef",
+    {
+        "Assets": List[AssetShallowTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdatePackagingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePackagingGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdatePackagingGroupRequestRequestTypeDef = TypedDict(
@@ -325,14 +375,28 @@
 )
 
 class ConfigureLogsRequestRequestTypeDef(
     _RequiredConfigureLogsRequestRequestTypeDef, _OptionalConfigureLogsRequestRequestTypeDef
 ):
     pass
 
+ConfigureLogsResponseTypeDef = TypedDict(
+    "ConfigureLogsResponseTypeDef",
+    {
+        "Arn": str,
+        "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
+        "DomainName": str,
+        "EgressAccessLogs": EgressAccessLogsTypeDef,
+        "Id": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePackagingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePackagingGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalCreatePackagingGroupRequestRequestTypeDef = TypedDict(
@@ -347,103 +411,70 @@
 
 class CreatePackagingGroupRequestRequestTypeDef(
     _RequiredCreatePackagingGroupRequestRequestTypeDef,
     _OptionalCreatePackagingGroupRequestRequestTypeDef,
 ):
     pass
 
-PackagingGroupTypeDef = TypedDict(
-    "PackagingGroupTypeDef",
-    {
-        "ApproximateAssetCount": int,
-        "Arn": str,
-        "Authorization": AuthorizationTypeDef,
-        "DomainName": str,
-        "EgressAccessLogs": EgressAccessLogsTypeDef,
-        "Id": str,
-        "Tags": Dict[str, str],
-    },
-    total=False,
-)
-
-ConfigureLogsResponseTypeDef = TypedDict(
-    "ConfigureLogsResponseTypeDef",
+CreatePackagingGroupResponseTypeDef = TypedDict(
+    "CreatePackagingGroupResponseTypeDef",
     {
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreatePackagingGroupResponseTypeDef = TypedDict(
-    "CreatePackagingGroupResponseTypeDef",
+DescribePackagingGroupResponseTypeDef = TypedDict(
+    "DescribePackagingGroupResponseTypeDef",
     {
+        "ApproximateAssetCount": int,
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribePackagingGroupResponseTypeDef = TypedDict(
-    "DescribePackagingGroupResponseTypeDef",
+PackagingGroupTypeDef = TypedDict(
+    "PackagingGroupTypeDef",
     {
         "ApproximateAssetCount": int,
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
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
-ListAssetsResponseTypeDef = TypedDict(
-    "ListAssetsResponseTypeDef",
-    {
-        "Assets": List[AssetShallowTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
 UpdatePackagingGroupResponseTypeDef = TypedDict(
     "UpdatePackagingGroupResponseTypeDef",
     {
         "ApproximateAssetCount": int,
         "Arn": str,
         "Authorization": AuthorizationTypeDef,
+        "CreatedAt": str,
         "DomainName": str,
         "EgressAccessLogs": EgressAccessLogsTypeDef,
         "Id": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssetResponseTypeDef = TypedDict(
     "CreateAssetResponseTypeDef",
     {
         "Arn": str,
@@ -451,15 +482,15 @@
         "EgressEndpoints": List[EgressEndpointTypeDef],
         "Id": str,
         "PackagingGroupId": str,
         "ResourceId": str,
         "SourceArn": str,
         "SourceRoleArn": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssetResponseTypeDef = TypedDict(
     "DescribeAssetResponseTypeDef",
     {
         "Arn": str,
@@ -467,15 +498,15 @@
         "EgressEndpoints": List[EgressEndpointTypeDef],
         "Id": str,
         "PackagingGroupId": str,
         "ResourceId": str,
         "SourceArn": str,
         "SourceRoleArn": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DashManifestTypeDef = TypedDict(
     "DashManifestTypeDef",
     {
         "ManifestLayout": ManifestLayoutType,
@@ -525,46 +556,20 @@
     },
     total=False,
 )
 
 class SpekeKeyProviderTypeDef(_RequiredSpekeKeyProviderTypeDef, _OptionalSpekeKeyProviderTypeDef):
     pass
 
-ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    {
-        "PackagingGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef = TypedDict(
-    "ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef",
-    {
-        "PackagingGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef = TypedDict(
-    "ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPackagingGroupsResponseTypeDef = TypedDict(
     "ListPackagingGroupsResponseTypeDef",
     {
         "NextToken": str,
         "PackagingGroups": List[PackagingGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCmafEncryptionTypeDef = TypedDict(
     "_RequiredCmafEncryptionTypeDef",
     {
         "SpekeKeyProvider": SpekeKeyProviderTypeDef,
@@ -718,44 +723,47 @@
     pass
 
 CreatePackagingConfigurationResponseTypeDef = TypedDict(
     "CreatePackagingConfigurationResponseTypeDef",
     {
         "Arn": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "MssPackage": MssPackageTypeDef,
         "PackagingGroupId": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackagingConfigurationResponseTypeDef = TypedDict(
     "DescribePackagingConfigurationResponseTypeDef",
     {
         "Arn": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "MssPackage": MssPackageTypeDef,
         "PackagingGroupId": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackagingConfigurationTypeDef = TypedDict(
     "PackagingConfigurationTypeDef",
     {
         "Arn": str,
         "CmafPackage": CmafPackageTypeDef,
+        "CreatedAt": str,
         "DashPackage": DashPackageTypeDef,
         "HlsPackage": HlsPackageTypeDef,
         "Id": str,
         "MssPackage": MssPackageTypeDef,
         "PackagingGroupId": str,
         "Tags": Dict[str, str],
     },
@@ -763,10 +771,10 @@
 )
 
 ListPackagingConfigurationsResponseTypeDef = TypedDict(
     "ListPackagingConfigurationsResponseTypeDef",
     {
         "NextToken": str,
         "PackagingConfigurations": List[PackagingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/PKG-INFO` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediapackage-vod
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaPackageVod 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaPackageVod 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediapackage-vod"></a>
 
 # types-aiobotocore-mediapackage-vod
 
 [![PyPI - types-aiobotocore-mediapackage-vod](https://img.shields.io/pypi/v/types-aiobotocore-mediapackage-vod.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage-vod)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediapackage-vod.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediapackage-vod)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediapackage-vod?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediapackage-vod)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaPackageVod 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod)
+[aiobotocore.MediaPackageVod 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediapackage-vod.html#MediaPackageVod)
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
 [types-aiobotocore-mediapackage-vod docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,52 +339,52 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediapackage_vod.type_defs import (
     AssetShallowTypeDef,
     AuthorizationTypeDef,
     EgressAccessLogsTypeDef,
-    ResponseMetadataTypeDef,
     CreateAssetRequestRequestTypeDef,
     EgressEndpointTypeDef,
     StreamSelectionTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeletePackagingConfigurationRequestRequestTypeDef,
     DeletePackagingGroupRequestRequestTypeDef,
     DescribeAssetRequestRequestTypeDef,
     DescribePackagingConfigurationRequestRequestTypeDef,
     DescribePackagingGroupRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionContractConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssetsRequestListAssetsPaginateTypeDef,
     ListAssetsRequestRequestTypeDef,
+    ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef,
     ListPackagingConfigurationsRequestRequestTypeDef,
+    ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef,
     ListPackagingGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListAssetsResponseTypeDef,
     UpdatePackagingGroupRequestRequestTypeDef,
     ConfigureLogsRequestRequestTypeDef,
-    CreatePackagingGroupRequestRequestTypeDef,
-    PackagingGroupTypeDef,
     ConfigureLogsResponseTypeDef,
+    CreatePackagingGroupRequestRequestTypeDef,
     CreatePackagingGroupResponseTypeDef,
     DescribePackagingGroupResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAssetsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    PackagingGroupTypeDef,
     UpdatePackagingGroupResponseTypeDef,
     CreateAssetResponseTypeDef,
     DescribeAssetResponseTypeDef,
     DashManifestTypeDef,
     HlsManifestTypeDef,
     MssManifestTypeDef,
     SpekeKeyProviderTypeDef,
-    ListAssetsRequestListAssetsPaginateTypeDef,
-    ListPackagingConfigurationsRequestListPackagingConfigurationsPaginateTypeDef,
-    ListPackagingGroupsRequestListPackagingGroupsPaginateTypeDef,
     ListPackagingGroupsResponseTypeDef,
     CmafEncryptionTypeDef,
     DashEncryptionTypeDef,
     HlsEncryptionTypeDef,
     MssEncryptionTypeDef,
     CmafPackageTypeDef,
     DashPackageTypeDef,
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

### Comparing `types-aiobotocore-mediapackage-vod-2.5.0.post1/types_aiobotocore_mediapackage_vod.egg-info/SOURCES.txt` & `types-aiobotocore-mediapackage-vod-2.5.1/types_aiobotocore_mediapackage_vod.egg-info/SOURCES.txt`

 * *Files identical despite different names*

