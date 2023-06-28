# Comparing `tmp/types-aiobotocore-ecr-public-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ecr-public-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ecr-public-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-ecr-public-2.5.1.tar", last modified: Wed Jun 28 01:43:26 2023, max compression
```

## Comparing `types-aiobotocore-ecr-public-2.5.0.post1.tar` & `types-aiobotocore-ecr-public-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.203170 types-aiobotocore-ecr-public-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16168 2023-03-11 12:26:34.203170 types-aiobotocore-ecr-public-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14586 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.203170 types-aiobotocore-ecr-public-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2144 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.203170 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/
--rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      953 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22197 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22161 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8513 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8511 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5874 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5867 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    23731 2023-03-11 12:13:48.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    23696 2023-03-11 12:13:48.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.203170 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16168 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.386131 types-aiobotocore-ecr-public-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16163 2023-06-28 01:43:26.386131 types-aiobotocore-ecr-public-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14587 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:26.386131 types-aiobotocore-ecr-public-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.374131 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/
+-rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      941 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22197 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22161 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8722 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8720 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5762 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5756 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    23781 2023-06-28 01:30:25.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23746 2023-06-28 01:30:25.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.386131 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16163 2023-06-28 01:43:26.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:26.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:26.000000 types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/LICENSE` & `types-aiobotocore-ecr-public-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ecr-public-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ecr-public
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ECRPublic 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ECRPublic 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ecr-public"></a>
 
 # types-aiobotocore-ecr-public
 
 [![PyPI - types-aiobotocore-ecr-public](https://img.shields.io/pypi/v/types-aiobotocore-ecr-public.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr-public)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecr-public.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr-public)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecr-public?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecr-public)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECRPublic 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic)
+[aiobotocore.ECRPublic 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic)
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
 [types-aiobotocore-ecr-public docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,65 +339,65 @@
 
 ```python
 from types_aiobotocore_ecr_public.type_defs import (
     AuthorizationDataTypeDef,
     BatchCheckLayerAvailabilityRequestRequestTypeDef,
     LayerFailureTypeDef,
     LayerTypeDef,
-    ResponseMetadataTypeDef,
     ImageIdentifierTypeDef,
     CompleteLayerUploadRequestRequestTypeDef,
+    CompleteLayerUploadResponseTypeDef,
     RepositoryCatalogDataInputTypeDef,
     TagTypeDef,
     RepositoryCatalogDataTypeDef,
     RepositoryTypeDef,
     DeleteRepositoryPolicyRequestRequestTypeDef,
+    DeleteRepositoryPolicyResponseTypeDef,
     DeleteRepositoryRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
     DescribeImageTagsRequestRequestTypeDef,
     ImageDetailTypeDef,
+    DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef,
     DescribeRegistriesRequestRequestTypeDef,
+    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeRepositoriesRequestRequestTypeDef,
     RegistryCatalogDataTypeDef,
     GetRepositoryCatalogDataRequestRequestTypeDef,
     GetRepositoryPolicyRequestRequestTypeDef,
+    GetRepositoryPolicyResponseTypeDef,
     ReferencedImageDetailTypeDef,
     InitiateLayerUploadRequestRequestTypeDef,
+    InitiateLayerUploadResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutImageRequestRequestTypeDef,
     PutRegistryCatalogDataRequestRequestTypeDef,
     RegistryAliasTypeDef,
+    ResponseMetadataTypeDef,
     SetRepositoryPolicyRequestRequestTypeDef,
+    SetRepositoryPolicyResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UploadLayerPartRequestRequestTypeDef,
-    BatchCheckLayerAvailabilityResponseTypeDef,
-    CompleteLayerUploadResponseTypeDef,
-    DeleteRepositoryPolicyResponseTypeDef,
-    GetAuthorizationTokenResponseTypeDef,
-    GetRepositoryPolicyResponseTypeDef,
-    InitiateLayerUploadResponseTypeDef,
-    SetRepositoryPolicyResponseTypeDef,
     UploadLayerPartResponseTypeDef,
+    GetAuthorizationTokenResponseTypeDef,
+    BatchCheckLayerAvailabilityResponseTypeDef,
     BatchDeleteImageRequestRequestTypeDef,
+    DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
     ImageFailureTypeDef,
     ImageTypeDef,
     PutRepositoryCatalogDataRequestRequestTypeDef,
     CreateRepositoryRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     GetRepositoryCatalogDataResponseTypeDef,
     PutRepositoryCatalogDataResponseTypeDef,
     CreateRepositoryResponseTypeDef,
     DeleteRepositoryResponseTypeDef,
     DescribeRepositoriesResponseTypeDef,
-    DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-    DescribeImagesRequestDescribeImagesPaginateTypeDef,
-    DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef,
-    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeImagesResponseTypeDef,
     GetRegistryCatalogDataResponseTypeDef,
     PutRegistryCatalogDataResponseTypeDef,
     ImageTagDetailTypeDef,
     RegistryTypeDef,
     BatchDeleteImageResponseTypeDef,
     PutImageResponseTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/README.md` & `types-aiobotocore-ecr-public-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ecr-public"></a>
 
 # types-aiobotocore-ecr-public
 
 [![PyPI - types-aiobotocore-ecr-public](https://img.shields.io/pypi/v/types-aiobotocore-ecr-public.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr-public)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecr-public.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr-public)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecr-public?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecr-public)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECRPublic 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic)
+[aiobotocore.ECRPublic 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic)
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
 [types-aiobotocore-ecr-public docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,65 +306,65 @@
 
 ```python
 from types_aiobotocore_ecr_public.type_defs import (
     AuthorizationDataTypeDef,
     BatchCheckLayerAvailabilityRequestRequestTypeDef,
     LayerFailureTypeDef,
     LayerTypeDef,
-    ResponseMetadataTypeDef,
     ImageIdentifierTypeDef,
     CompleteLayerUploadRequestRequestTypeDef,
+    CompleteLayerUploadResponseTypeDef,
     RepositoryCatalogDataInputTypeDef,
     TagTypeDef,
     RepositoryCatalogDataTypeDef,
     RepositoryTypeDef,
     DeleteRepositoryPolicyRequestRequestTypeDef,
+    DeleteRepositoryPolicyResponseTypeDef,
     DeleteRepositoryRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
     DescribeImageTagsRequestRequestTypeDef,
     ImageDetailTypeDef,
+    DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef,
     DescribeRegistriesRequestRequestTypeDef,
+    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeRepositoriesRequestRequestTypeDef,
     RegistryCatalogDataTypeDef,
     GetRepositoryCatalogDataRequestRequestTypeDef,
     GetRepositoryPolicyRequestRequestTypeDef,
+    GetRepositoryPolicyResponseTypeDef,
     ReferencedImageDetailTypeDef,
     InitiateLayerUploadRequestRequestTypeDef,
+    InitiateLayerUploadResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutImageRequestRequestTypeDef,
     PutRegistryCatalogDataRequestRequestTypeDef,
     RegistryAliasTypeDef,
+    ResponseMetadataTypeDef,
     SetRepositoryPolicyRequestRequestTypeDef,
+    SetRepositoryPolicyResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UploadLayerPartRequestRequestTypeDef,
-    BatchCheckLayerAvailabilityResponseTypeDef,
-    CompleteLayerUploadResponseTypeDef,
-    DeleteRepositoryPolicyResponseTypeDef,
-    GetAuthorizationTokenResponseTypeDef,
-    GetRepositoryPolicyResponseTypeDef,
-    InitiateLayerUploadResponseTypeDef,
-    SetRepositoryPolicyResponseTypeDef,
     UploadLayerPartResponseTypeDef,
+    GetAuthorizationTokenResponseTypeDef,
+    BatchCheckLayerAvailabilityResponseTypeDef,
     BatchDeleteImageRequestRequestTypeDef,
+    DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
     ImageFailureTypeDef,
     ImageTypeDef,
     PutRepositoryCatalogDataRequestRequestTypeDef,
     CreateRepositoryRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     GetRepositoryCatalogDataResponseTypeDef,
     PutRepositoryCatalogDataResponseTypeDef,
     CreateRepositoryResponseTypeDef,
     DeleteRepositoryResponseTypeDef,
     DescribeRepositoriesResponseTypeDef,
-    DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-    DescribeImagesRequestDescribeImagesPaginateTypeDef,
-    DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef,
-    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeImagesResponseTypeDef,
     GetRegistryCatalogDataResponseTypeDef,
     PutRegistryCatalogDataResponseTypeDef,
     ImageTagDetailTypeDef,
     RegistryTypeDef,
     BatchDeleteImageResponseTypeDef,
     PutImageResponseTypeDef,
@@ -380,43 +380,43 @@
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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/setup.py` & `types-aiobotocore-ecr-public-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ecr-public.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ecr-public",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ecr_public"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ECRPublic 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.ECRPublic 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/"
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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/__init__.py` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/__init__.pyi` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/__main__.py` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ECRPublic 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ECRPublic 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic\nOther"
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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/client.py` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/client.pyi` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/literals.py` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/literals.py`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/literals.pyi` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/literals.pyi`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/paginator.py` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         describe_image_tags_paginator: DescribeImageTagsPaginator = client.get_paginator("describe_image_tags")
         describe_images_paginator: DescribeImagesPaginator = client.get_paginator("describe_images")
         describe_registries_paginator: DescribeRegistriesPaginator = client.get_paginator("describe_registries")
         describe_repositories_paginator: DescribeRepositoriesPaginator = client.get_paginator("describe_repositories")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeImagesResponseTypeDef,
     DescribeImageTagsResponseTypeDef,
     DescribeRegistriesResponseTypeDef,
     DescribeRepositoriesResponseTypeDef,
     ImageIdentifierTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeImageTagsPaginator",
     "DescribeImagesPaginator",
     "DescribeRegistriesPaginator",
     "DescribeRepositoriesPaginator",
 )
 
@@ -72,15 +65,15 @@
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImageTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeImageTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeimagetagspaginator)
         """
 
 
@@ -92,30 +85,30 @@
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         imageIds: Sequence[ImageIdentifierTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeimagespaginator)
         """
 
 
 class DescribeRegistriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeRegistries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeregistriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRegistriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeRegistries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeregistriespaginator)
         """
 
 
@@ -126,13 +119,13 @@
     """
 
     def paginate(
         self,
         *,
         registryId: str = ...,
         repositoryNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRepositoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describerepositoriespaginator)
         """
```

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/paginator.pyi` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         describe_image_tags_paginator: DescribeImageTagsPaginator = client.get_paginator("describe_image_tags")
         describe_images_paginator: DescribeImagesPaginator = client.get_paginator("describe_images")
         describe_registries_paginator: DescribeRegistriesPaginator = client.get_paginator("describe_registries")
         describe_repositories_paginator: DescribeRepositoriesPaginator = client.get_paginator("describe_repositories")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeImagesResponseTypeDef,
     DescribeImageTagsResponseTypeDef,
     DescribeRegistriesResponseTypeDef,
     DescribeRepositoriesResponseTypeDef,
     ImageIdentifierTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeImageTagsPaginator",
     "DescribeImagesPaginator",
     "DescribeRegistriesPaginator",
     "DescribeRepositoriesPaginator",
 )
 
@@ -68,15 +62,15 @@
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImageTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeImageTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeimagetagspaginator)
         """
 
 class DescribeImagesPaginator(AioPaginator):
@@ -87,29 +81,29 @@
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         imageIds: Sequence[ImageIdentifierTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeimagespaginator)
         """
 
 class DescribeRegistriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeRegistries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeregistriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRegistriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeRegistries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describeregistriespaginator)
         """
 
 class DescribeRepositoriesPaginator(AioPaginator):
@@ -119,13 +113,13 @@
     """
 
     def paginate(
         self,
         *,
         registryId: str = ...,
         repositoryNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRepositoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic.Paginator.DescribeRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/paginators/#describerepositoriespaginator)
         """
```

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/type_defs.py` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -31,65 +31,65 @@
 
 
 __all__ = (
     "AuthorizationDataTypeDef",
     "BatchCheckLayerAvailabilityRequestRequestTypeDef",
     "LayerFailureTypeDef",
     "LayerTypeDef",
-    "ResponseMetadataTypeDef",
     "ImageIdentifierTypeDef",
     "CompleteLayerUploadRequestRequestTypeDef",
+    "CompleteLayerUploadResponseTypeDef",
     "RepositoryCatalogDataInputTypeDef",
     "TagTypeDef",
     "RepositoryCatalogDataTypeDef",
     "RepositoryTypeDef",
     "DeleteRepositoryPolicyRequestRequestTypeDef",
+    "DeleteRepositoryPolicyResponseTypeDef",
     "DeleteRepositoryRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
     "DescribeImageTagsRequestRequestTypeDef",
     "ImageDetailTypeDef",
+    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
     "DescribeRegistriesRequestRequestTypeDef",
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeRepositoriesRequestRequestTypeDef",
     "RegistryCatalogDataTypeDef",
     "GetRepositoryCatalogDataRequestRequestTypeDef",
     "GetRepositoryPolicyRequestRequestTypeDef",
+    "GetRepositoryPolicyResponseTypeDef",
     "ReferencedImageDetailTypeDef",
     "InitiateLayerUploadRequestRequestTypeDef",
+    "InitiateLayerUploadResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutImageRequestRequestTypeDef",
     "PutRegistryCatalogDataRequestRequestTypeDef",
     "RegistryAliasTypeDef",
+    "ResponseMetadataTypeDef",
     "SetRepositoryPolicyRequestRequestTypeDef",
+    "SetRepositoryPolicyResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UploadLayerPartRequestRequestTypeDef",
-    "BatchCheckLayerAvailabilityResponseTypeDef",
-    "CompleteLayerUploadResponseTypeDef",
-    "DeleteRepositoryPolicyResponseTypeDef",
-    "GetAuthorizationTokenResponseTypeDef",
-    "GetRepositoryPolicyResponseTypeDef",
-    "InitiateLayerUploadResponseTypeDef",
-    "SetRepositoryPolicyResponseTypeDef",
     "UploadLayerPartResponseTypeDef",
+    "GetAuthorizationTokenResponseTypeDef",
+    "BatchCheckLayerAvailabilityResponseTypeDef",
     "BatchDeleteImageRequestRequestTypeDef",
+    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
     "DescribeImagesRequestRequestTypeDef",
     "ImageFailureTypeDef",
     "ImageTypeDef",
     "PutRepositoryCatalogDataRequestRequestTypeDef",
     "CreateRepositoryRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "GetRepositoryCatalogDataResponseTypeDef",
     "PutRepositoryCatalogDataResponseTypeDef",
     "CreateRepositoryResponseTypeDef",
     "DeleteRepositoryResponseTypeDef",
     "DescribeRepositoriesResponseTypeDef",
-    "DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
-    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
-    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeImagesResponseTypeDef",
     "GetRegistryCatalogDataResponseTypeDef",
     "PutRegistryCatalogDataResponseTypeDef",
     "ImageTagDetailTypeDef",
     "RegistryTypeDef",
     "BatchDeleteImageResponseTypeDef",
     "PutImageResponseTypeDef",
@@ -146,25 +146,14 @@
         "layerAvailability": LayerAvailabilityType,
         "layerSize": int,
         "mediaType": str,
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
 ImageIdentifierTypeDef = TypedDict(
     "ImageIdentifierTypeDef",
     {
         "imageDigest": str,
         "imageTag": str,
     },
     total=False,
@@ -190,14 +179,25 @@
 class CompleteLayerUploadRequestRequestTypeDef(
     _RequiredCompleteLayerUploadRequestRequestTypeDef,
     _OptionalCompleteLayerUploadRequestRequestTypeDef,
 ):
     pass
 
 
+CompleteLayerUploadResponseTypeDef = TypedDict(
+    "CompleteLayerUploadResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "uploadId": str,
+        "layerDigest": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RepositoryCatalogDataInputTypeDef = TypedDict(
     "RepositoryCatalogDataInputTypeDef",
     {
         "description": str,
         "architectures": Sequence[str],
         "operatingSystems": Sequence[str],
         "logoImageBlob": Union[str, bytes, IO[Any], StreamingBody],
@@ -260,14 +260,24 @@
 class DeleteRepositoryPolicyRequestRequestTypeDef(
     _RequiredDeleteRepositoryPolicyRequestRequestTypeDef,
     _OptionalDeleteRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteRepositoryPolicyResponseTypeDef = TypedDict(
+    "DeleteRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRepositoryRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDeleteRepositoryRequestRequestTypeDef = TypedDict(
@@ -282,24 +292,37 @@
 
 class DeleteRepositoryRequestRequestTypeDef(
     _RequiredDeleteRepositoryRequestRequestTypeDef, _OptionalDeleteRepositoryRequestRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "repositoryName": str,
+    },
+)
+_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
+    {
+        "registryId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef(
+    _RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
+    _OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeImageTagsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeImageTagsRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDescribeImageTagsRequestRequestTypeDef = TypedDict(
@@ -330,23 +353,41 @@
         "imagePushedAt": datetime,
         "imageManifestMediaType": str,
         "artifactMediaType": str,
     },
     total=False,
 )
 
+DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef = TypedDict(
+    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRegistriesRequestRequestTypeDef = TypedDict(
     "DescribeRegistriesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
+    {
+        "registryId": str,
+        "repositoryNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRepositoriesRequestRequestTypeDef = TypedDict(
     "DescribeRepositoriesRequestRequestTypeDef",
     {
         "registryId": str,
         "repositoryNames": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -402,14 +443,24 @@
 class GetRepositoryPolicyRequestRequestTypeDef(
     _RequiredGetRepositoryPolicyRequestRequestTypeDef,
     _OptionalGetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+GetRepositoryPolicyResponseTypeDef = TypedDict(
+    "GetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ReferencedImageDetailTypeDef = TypedDict(
     "ReferencedImageDetailTypeDef",
     {
         "imageDigest": str,
         "imageSizeInBytes": int,
         "imagePushedAt": datetime,
         "imageManifestMediaType": str,
@@ -436,21 +487,40 @@
 class InitiateLayerUploadRequestRequestTypeDef(
     _RequiredInitiateLayerUploadRequestRequestTypeDef,
     _OptionalInitiateLayerUploadRequestRequestTypeDef,
 ):
     pass
 
 
+InitiateLayerUploadResponseTypeDef = TypedDict(
+    "InitiateLayerUploadResponseTypeDef",
+    {
+        "uploadId": str,
+        "partSize": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
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
 _RequiredPutImageRequestRequestTypeDef = TypedDict(
     "_RequiredPutImageRequestRequestTypeDef",
     {
         "repositoryName": str,
         "imageManifest": str,
     },
 )
@@ -486,14 +556,25 @@
         "name": str,
         "status": RegistryAliasStatusType,
         "primaryRegistryAlias": bool,
         "defaultRegistryAlias": bool,
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
 _RequiredSetRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSetRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
         "policyText": str,
     },
 )
@@ -510,14 +591,24 @@
 class SetRepositoryPolicyRequestRequestTypeDef(
     _RequiredSetRepositoryPolicyRequestRequestTypeDef,
     _OptionalSetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+SetRepositoryPolicyResponseTypeDef = TypedDict(
+    "SetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -543,110 +634,84 @@
 
 class UploadLayerPartRequestRequestTypeDef(
     _RequiredUploadLayerPartRequestRequestTypeDef, _OptionalUploadLayerPartRequestRequestTypeDef
 ):
     pass
 
 
-BatchCheckLayerAvailabilityResponseTypeDef = TypedDict(
-    "BatchCheckLayerAvailabilityResponseTypeDef",
-    {
-        "layers": List[LayerTypeDef],
-        "failures": List[LayerFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CompleteLayerUploadResponseTypeDef = TypedDict(
-    "CompleteLayerUploadResponseTypeDef",
+UploadLayerPartResponseTypeDef = TypedDict(
+    "UploadLayerPartResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "uploadId": str,
-        "layerDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRepositoryPolicyResponseTypeDef = TypedDict(
-    "DeleteRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "lastByteReceived": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAuthorizationTokenResponseTypeDef = TypedDict(
     "GetAuthorizationTokenResponseTypeDef",
     {
         "authorizationData": AuthorizationDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetRepositoryPolicyResponseTypeDef = TypedDict(
-    "GetRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateLayerUploadResponseTypeDef = TypedDict(
-    "InitiateLayerUploadResponseTypeDef",
+BatchCheckLayerAvailabilityResponseTypeDef = TypedDict(
+    "BatchCheckLayerAvailabilityResponseTypeDef",
     {
-        "uploadId": str,
-        "partSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "layers": List[LayerTypeDef],
+        "failures": List[LayerFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-SetRepositoryPolicyResponseTypeDef = TypedDict(
-    "SetRepositoryPolicyResponseTypeDef",
+_RequiredBatchDeleteImageRequestRequestTypeDef = TypedDict(
+    "_RequiredBatchDeleteImageRequestRequestTypeDef",
     {
-        "registryId": str,
         "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageIds": Sequence[ImageIdentifierTypeDef],
     },
 )
-
-UploadLayerPartResponseTypeDef = TypedDict(
-    "UploadLayerPartResponseTypeDef",
+_OptionalBatchDeleteImageRequestRequestTypeDef = TypedDict(
+    "_OptionalBatchDeleteImageRequestRequestTypeDef",
     {
         "registryId": str,
-        "repositoryName": str,
-        "uploadId": str,
-        "lastByteReceived": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-_RequiredBatchDeleteImageRequestRequestTypeDef = TypedDict(
-    "_RequiredBatchDeleteImageRequestRequestTypeDef",
+
+class BatchDeleteImageRequestRequestTypeDef(
+    _RequiredBatchDeleteImageRequestRequestTypeDef, _OptionalBatchDeleteImageRequestRequestTypeDef
+):
+    pass
+
+
+_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "repositoryName": str,
-        "imageIds": Sequence[ImageIdentifierTypeDef],
     },
 )
-_OptionalBatchDeleteImageRequestRequestTypeDef = TypedDict(
-    "_OptionalBatchDeleteImageRequestRequestTypeDef",
+_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "registryId": str,
+        "imageIds": Sequence[ImageIdentifierTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
-class BatchDeleteImageRequestRequestTypeDef(
-    _RequiredBatchDeleteImageRequestRequestTypeDef, _OptionalBatchDeleteImageRequestRequestTypeDef
+class DescribeImagesRequestDescribeImagesPaginateTypeDef(
+    _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef,
+    _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef,
 ):
     pass
 
 
 _RequiredDescribeImagesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeImagesRequestRequestTypeDef",
     {
@@ -738,15 +803,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -754,139 +819,74 @@
     },
 )
 
 GetRepositoryCatalogDataResponseTypeDef = TypedDict(
     "GetRepositoryCatalogDataResponseTypeDef",
     {
         "catalogData": RepositoryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRepositoryCatalogDataResponseTypeDef = TypedDict(
     "PutRepositoryCatalogDataResponseTypeDef",
     {
         "catalogData": RepositoryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryResponseTypeDef = TypedDict(
     "CreateRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
         "catalogData": RepositoryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryResponseTypeDef = TypedDict(
     "DeleteRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoriesResponseTypeDef = TypedDict(
     "DescribeRepositoriesResponseTypeDef",
     {
         "repositories": List[RepositoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
-    {
-        "repositoryName": str,
-    },
-)
-_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
-    {
-        "registryId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef(
-    _RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-    _OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef",
-    {
-        "repositoryName": str,
-    },
-)
-_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef",
-    {
-        "registryId": str,
-        "imageIds": Sequence[ImageIdentifierTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-
-class DescribeImagesRequestDescribeImagesPaginateTypeDef(
-    _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef,
-    _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef,
-):
-    pass
-
-
-DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef = TypedDict(
-    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
-    {
-        "registryId": str,
-        "repositoryNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeImagesResponseTypeDef = TypedDict(
     "DescribeImagesResponseTypeDef",
     {
         "imageDetails": List[ImageDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRegistryCatalogDataResponseTypeDef = TypedDict(
     "GetRegistryCatalogDataResponseTypeDef",
     {
         "registryCatalogData": RegistryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRegistryCatalogDataResponseTypeDef = TypedDict(
     "PutRegistryCatalogDataResponseTypeDef",
     {
         "registryCatalogData": RegistryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageTagDetailTypeDef = TypedDict(
     "ImageTagDetailTypeDef",
     {
         "imageTag": str,
@@ -908,36 +908,36 @@
 )
 
 BatchDeleteImageResponseTypeDef = TypedDict(
     "BatchDeleteImageResponseTypeDef",
     {
         "imageIds": List[ImageIdentifierTypeDef],
         "failures": List[ImageFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutImageResponseTypeDef = TypedDict(
     "PutImageResponseTypeDef",
     {
         "image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImageTagsResponseTypeDef = TypedDict(
     "DescribeImageTagsResponseTypeDef",
     {
         "imageTagDetails": List[ImageTagDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRegistriesResponseTypeDef = TypedDict(
     "DescribeRegistriesResponseTypeDef",
     {
         "registries": List[RegistryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public/type_defs.pyi` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,65 +30,65 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AuthorizationDataTypeDef",
     "BatchCheckLayerAvailabilityRequestRequestTypeDef",
     "LayerFailureTypeDef",
     "LayerTypeDef",
-    "ResponseMetadataTypeDef",
     "ImageIdentifierTypeDef",
     "CompleteLayerUploadRequestRequestTypeDef",
+    "CompleteLayerUploadResponseTypeDef",
     "RepositoryCatalogDataInputTypeDef",
     "TagTypeDef",
     "RepositoryCatalogDataTypeDef",
     "RepositoryTypeDef",
     "DeleteRepositoryPolicyRequestRequestTypeDef",
+    "DeleteRepositoryPolicyResponseTypeDef",
     "DeleteRepositoryRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
     "DescribeImageTagsRequestRequestTypeDef",
     "ImageDetailTypeDef",
+    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
     "DescribeRegistriesRequestRequestTypeDef",
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeRepositoriesRequestRequestTypeDef",
     "RegistryCatalogDataTypeDef",
     "GetRepositoryCatalogDataRequestRequestTypeDef",
     "GetRepositoryPolicyRequestRequestTypeDef",
+    "GetRepositoryPolicyResponseTypeDef",
     "ReferencedImageDetailTypeDef",
     "InitiateLayerUploadRequestRequestTypeDef",
+    "InitiateLayerUploadResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutImageRequestRequestTypeDef",
     "PutRegistryCatalogDataRequestRequestTypeDef",
     "RegistryAliasTypeDef",
+    "ResponseMetadataTypeDef",
     "SetRepositoryPolicyRequestRequestTypeDef",
+    "SetRepositoryPolicyResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UploadLayerPartRequestRequestTypeDef",
-    "BatchCheckLayerAvailabilityResponseTypeDef",
-    "CompleteLayerUploadResponseTypeDef",
-    "DeleteRepositoryPolicyResponseTypeDef",
-    "GetAuthorizationTokenResponseTypeDef",
-    "GetRepositoryPolicyResponseTypeDef",
-    "InitiateLayerUploadResponseTypeDef",
-    "SetRepositoryPolicyResponseTypeDef",
     "UploadLayerPartResponseTypeDef",
+    "GetAuthorizationTokenResponseTypeDef",
+    "BatchCheckLayerAvailabilityResponseTypeDef",
     "BatchDeleteImageRequestRequestTypeDef",
+    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
     "DescribeImagesRequestRequestTypeDef",
     "ImageFailureTypeDef",
     "ImageTypeDef",
     "PutRepositoryCatalogDataRequestRequestTypeDef",
     "CreateRepositoryRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "GetRepositoryCatalogDataResponseTypeDef",
     "PutRepositoryCatalogDataResponseTypeDef",
     "CreateRepositoryResponseTypeDef",
     "DeleteRepositoryResponseTypeDef",
     "DescribeRepositoriesResponseTypeDef",
-    "DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
-    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
-    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeImagesResponseTypeDef",
     "GetRegistryCatalogDataResponseTypeDef",
     "PutRegistryCatalogDataResponseTypeDef",
     "ImageTagDetailTypeDef",
     "RegistryTypeDef",
     "BatchDeleteImageResponseTypeDef",
     "PutImageResponseTypeDef",
@@ -143,25 +143,14 @@
         "layerAvailability": LayerAvailabilityType,
         "layerSize": int,
         "mediaType": str,
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
 ImageIdentifierTypeDef = TypedDict(
     "ImageIdentifierTypeDef",
     {
         "imageDigest": str,
         "imageTag": str,
     },
     total=False,
@@ -185,14 +174,25 @@
 
 class CompleteLayerUploadRequestRequestTypeDef(
     _RequiredCompleteLayerUploadRequestRequestTypeDef,
     _OptionalCompleteLayerUploadRequestRequestTypeDef,
 ):
     pass
 
+CompleteLayerUploadResponseTypeDef = TypedDict(
+    "CompleteLayerUploadResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "uploadId": str,
+        "layerDigest": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RepositoryCatalogDataInputTypeDef = TypedDict(
     "RepositoryCatalogDataInputTypeDef",
     {
         "description": str,
         "architectures": Sequence[str],
         "operatingSystems": Sequence[str],
         "logoImageBlob": Union[str, bytes, IO[Any], StreamingBody],
@@ -253,14 +253,24 @@
 
 class DeleteRepositoryPolicyRequestRequestTypeDef(
     _RequiredDeleteRepositoryPolicyRequestRequestTypeDef,
     _OptionalDeleteRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
+DeleteRepositoryPolicyResponseTypeDef = TypedDict(
+    "DeleteRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRepositoryRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDeleteRepositoryRequestRequestTypeDef = TypedDict(
@@ -273,24 +283,35 @@
 )
 
 class DeleteRepositoryRequestRequestTypeDef(
     _RequiredDeleteRepositoryRequestRequestTypeDef, _OptionalDeleteRepositoryRequestRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "repositoryName": str,
+    },
+)
+_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
+    {
+        "registryId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef(
+    _RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
+    _OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeImageTagsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeImageTagsRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDescribeImageTagsRequestRequestTypeDef = TypedDict(
@@ -319,23 +340,41 @@
         "imagePushedAt": datetime,
         "imageManifestMediaType": str,
         "artifactMediaType": str,
     },
     total=False,
 )
 
+DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef = TypedDict(
+    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRegistriesRequestRequestTypeDef = TypedDict(
     "DescribeRegistriesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
+    {
+        "registryId": str,
+        "repositoryNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRepositoriesRequestRequestTypeDef = TypedDict(
     "DescribeRepositoriesRequestRequestTypeDef",
     {
         "registryId": str,
         "repositoryNames": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -387,14 +426,24 @@
 
 class GetRepositoryPolicyRequestRequestTypeDef(
     _RequiredGetRepositoryPolicyRequestRequestTypeDef,
     _OptionalGetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
+GetRepositoryPolicyResponseTypeDef = TypedDict(
+    "GetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ReferencedImageDetailTypeDef = TypedDict(
     "ReferencedImageDetailTypeDef",
     {
         "imageDigest": str,
         "imageSizeInBytes": int,
         "imagePushedAt": datetime,
         "imageManifestMediaType": str,
@@ -419,21 +468,40 @@
 
 class InitiateLayerUploadRequestRequestTypeDef(
     _RequiredInitiateLayerUploadRequestRequestTypeDef,
     _OptionalInitiateLayerUploadRequestRequestTypeDef,
 ):
     pass
 
+InitiateLayerUploadResponseTypeDef = TypedDict(
+    "InitiateLayerUploadResponseTypeDef",
+    {
+        "uploadId": str,
+        "partSize": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
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
 _RequiredPutImageRequestRequestTypeDef = TypedDict(
     "_RequiredPutImageRequestRequestTypeDef",
     {
         "repositoryName": str,
         "imageManifest": str,
     },
 )
@@ -467,14 +535,25 @@
         "name": str,
         "status": RegistryAliasStatusType,
         "primaryRegistryAlias": bool,
         "defaultRegistryAlias": bool,
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
 _RequiredSetRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSetRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
         "policyText": str,
     },
 )
@@ -489,14 +568,24 @@
 
 class SetRepositoryPolicyRequestRequestTypeDef(
     _RequiredSetRepositoryPolicyRequestRequestTypeDef,
     _OptionalSetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
+SetRepositoryPolicyResponseTypeDef = TypedDict(
+    "SetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -520,109 +609,81 @@
 )
 
 class UploadLayerPartRequestRequestTypeDef(
     _RequiredUploadLayerPartRequestRequestTypeDef, _OptionalUploadLayerPartRequestRequestTypeDef
 ):
     pass
 
-BatchCheckLayerAvailabilityResponseTypeDef = TypedDict(
-    "BatchCheckLayerAvailabilityResponseTypeDef",
-    {
-        "layers": List[LayerTypeDef],
-        "failures": List[LayerFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CompleteLayerUploadResponseTypeDef = TypedDict(
-    "CompleteLayerUploadResponseTypeDef",
+UploadLayerPartResponseTypeDef = TypedDict(
+    "UploadLayerPartResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "uploadId": str,
-        "layerDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRepositoryPolicyResponseTypeDef = TypedDict(
-    "DeleteRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "lastByteReceived": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAuthorizationTokenResponseTypeDef = TypedDict(
     "GetAuthorizationTokenResponseTypeDef",
     {
         "authorizationData": AuthorizationDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRepositoryPolicyResponseTypeDef = TypedDict(
-    "GetRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-InitiateLayerUploadResponseTypeDef = TypedDict(
-    "InitiateLayerUploadResponseTypeDef",
+BatchCheckLayerAvailabilityResponseTypeDef = TypedDict(
+    "BatchCheckLayerAvailabilityResponseTypeDef",
     {
-        "uploadId": str,
-        "partSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "layers": List[LayerTypeDef],
+        "failures": List[LayerFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-SetRepositoryPolicyResponseTypeDef = TypedDict(
-    "SetRepositoryPolicyResponseTypeDef",
+_RequiredBatchDeleteImageRequestRequestTypeDef = TypedDict(
+    "_RequiredBatchDeleteImageRequestRequestTypeDef",
     {
-        "registryId": str,
         "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageIds": Sequence[ImageIdentifierTypeDef],
     },
 )
-
-UploadLayerPartResponseTypeDef = TypedDict(
-    "UploadLayerPartResponseTypeDef",
+_OptionalBatchDeleteImageRequestRequestTypeDef = TypedDict(
+    "_OptionalBatchDeleteImageRequestRequestTypeDef",
     {
         "registryId": str,
-        "repositoryName": str,
-        "uploadId": str,
-        "lastByteReceived": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-_RequiredBatchDeleteImageRequestRequestTypeDef = TypedDict(
-    "_RequiredBatchDeleteImageRequestRequestTypeDef",
+class BatchDeleteImageRequestRequestTypeDef(
+    _RequiredBatchDeleteImageRequestRequestTypeDef, _OptionalBatchDeleteImageRequestRequestTypeDef
+):
+    pass
+
+_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "repositoryName": str,
-        "imageIds": Sequence[ImageIdentifierTypeDef],
     },
 )
-_OptionalBatchDeleteImageRequestRequestTypeDef = TypedDict(
-    "_OptionalBatchDeleteImageRequestRequestTypeDef",
+_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "registryId": str,
+        "imageIds": Sequence[ImageIdentifierTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class BatchDeleteImageRequestRequestTypeDef(
-    _RequiredBatchDeleteImageRequestRequestTypeDef, _OptionalBatchDeleteImageRequestRequestTypeDef
+class DescribeImagesRequestDescribeImagesPaginateTypeDef(
+    _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef,
+    _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef,
 ):
     pass
 
 _RequiredDescribeImagesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeImagesRequestRequestTypeDef",
     {
         "repositoryName": str,
@@ -707,15 +768,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -723,135 +784,74 @@
     },
 )
 
 GetRepositoryCatalogDataResponseTypeDef = TypedDict(
     "GetRepositoryCatalogDataResponseTypeDef",
     {
         "catalogData": RepositoryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRepositoryCatalogDataResponseTypeDef = TypedDict(
     "PutRepositoryCatalogDataResponseTypeDef",
     {
         "catalogData": RepositoryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryResponseTypeDef = TypedDict(
     "CreateRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
         "catalogData": RepositoryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryResponseTypeDef = TypedDict(
     "DeleteRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoriesResponseTypeDef = TypedDict(
     "DescribeRepositoriesResponseTypeDef",
     {
         "repositories": List[RepositoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
-    {
-        "repositoryName": str,
-    },
-)
-_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef",
-    {
-        "registryId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef(
-    _RequiredDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-    _OptionalDescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef",
-    {
-        "repositoryName": str,
-    },
-)
-_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef",
-    {
-        "registryId": str,
-        "imageIds": Sequence[ImageIdentifierTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeImagesRequestDescribeImagesPaginateTypeDef(
-    _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef,
-    _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef,
-):
-    pass
-
-DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef = TypedDict(
-    "DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
-    {
-        "registryId": str,
-        "repositoryNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeImagesResponseTypeDef = TypedDict(
     "DescribeImagesResponseTypeDef",
     {
         "imageDetails": List[ImageDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRegistryCatalogDataResponseTypeDef = TypedDict(
     "GetRegistryCatalogDataResponseTypeDef",
     {
         "registryCatalogData": RegistryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRegistryCatalogDataResponseTypeDef = TypedDict(
     "PutRegistryCatalogDataResponseTypeDef",
     {
         "registryCatalogData": RegistryCatalogDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageTagDetailTypeDef = TypedDict(
     "ImageTagDetailTypeDef",
     {
         "imageTag": str,
@@ -873,36 +873,36 @@
 )
 
 BatchDeleteImageResponseTypeDef = TypedDict(
     "BatchDeleteImageResponseTypeDef",
     {
         "imageIds": List[ImageIdentifierTypeDef],
         "failures": List[ImageFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutImageResponseTypeDef = TypedDict(
     "PutImageResponseTypeDef",
     {
         "image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImageTagsResponseTypeDef = TypedDict(
     "DescribeImageTagsResponseTypeDef",
     {
         "imageTagDetails": List[ImageTagDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRegistriesResponseTypeDef = TypedDict(
     "DescribeRegistriesResponseTypeDef",
     {
         "registries": List[RegistryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/PKG-INFO` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ecr-public
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ECRPublic 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ECRPublic 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ecr-public"></a>
 
 # types-aiobotocore-ecr-public
 
 [![PyPI - types-aiobotocore-ecr-public](https://img.shields.io/pypi/v/types-aiobotocore-ecr-public.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr-public)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecr-public.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr-public)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecr-public?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecr-public)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECRPublic 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic)
+[aiobotocore.ECRPublic 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr-public.html#ECRPublic)
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
 [types-aiobotocore-ecr-public docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr_public/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,65 +339,65 @@
 
 ```python
 from types_aiobotocore_ecr_public.type_defs import (
     AuthorizationDataTypeDef,
     BatchCheckLayerAvailabilityRequestRequestTypeDef,
     LayerFailureTypeDef,
     LayerTypeDef,
-    ResponseMetadataTypeDef,
     ImageIdentifierTypeDef,
     CompleteLayerUploadRequestRequestTypeDef,
+    CompleteLayerUploadResponseTypeDef,
     RepositoryCatalogDataInputTypeDef,
     TagTypeDef,
     RepositoryCatalogDataTypeDef,
     RepositoryTypeDef,
     DeleteRepositoryPolicyRequestRequestTypeDef,
+    DeleteRepositoryPolicyResponseTypeDef,
     DeleteRepositoryRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
     DescribeImageTagsRequestRequestTypeDef,
     ImageDetailTypeDef,
+    DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef,
     DescribeRegistriesRequestRequestTypeDef,
+    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeRepositoriesRequestRequestTypeDef,
     RegistryCatalogDataTypeDef,
     GetRepositoryCatalogDataRequestRequestTypeDef,
     GetRepositoryPolicyRequestRequestTypeDef,
+    GetRepositoryPolicyResponseTypeDef,
     ReferencedImageDetailTypeDef,
     InitiateLayerUploadRequestRequestTypeDef,
+    InitiateLayerUploadResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutImageRequestRequestTypeDef,
     PutRegistryCatalogDataRequestRequestTypeDef,
     RegistryAliasTypeDef,
+    ResponseMetadataTypeDef,
     SetRepositoryPolicyRequestRequestTypeDef,
+    SetRepositoryPolicyResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UploadLayerPartRequestRequestTypeDef,
-    BatchCheckLayerAvailabilityResponseTypeDef,
-    CompleteLayerUploadResponseTypeDef,
-    DeleteRepositoryPolicyResponseTypeDef,
-    GetAuthorizationTokenResponseTypeDef,
-    GetRepositoryPolicyResponseTypeDef,
-    InitiateLayerUploadResponseTypeDef,
-    SetRepositoryPolicyResponseTypeDef,
     UploadLayerPartResponseTypeDef,
+    GetAuthorizationTokenResponseTypeDef,
+    BatchCheckLayerAvailabilityResponseTypeDef,
     BatchDeleteImageRequestRequestTypeDef,
+    DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
     ImageFailureTypeDef,
     ImageTypeDef,
     PutRepositoryCatalogDataRequestRequestTypeDef,
     CreateRepositoryRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     GetRepositoryCatalogDataResponseTypeDef,
     PutRepositoryCatalogDataResponseTypeDef,
     CreateRepositoryResponseTypeDef,
     DeleteRepositoryResponseTypeDef,
     DescribeRepositoriesResponseTypeDef,
-    DescribeImageTagsRequestDescribeImageTagsPaginateTypeDef,
-    DescribeImagesRequestDescribeImagesPaginateTypeDef,
-    DescribeRegistriesRequestDescribeRegistriesPaginateTypeDef,
-    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeImagesResponseTypeDef,
     GetRegistryCatalogDataResponseTypeDef,
     PutRegistryCatalogDataResponseTypeDef,
     ImageTagDetailTypeDef,
     RegistryTypeDef,
     BatchDeleteImageResponseTypeDef,
     PutImageResponseTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-ecr-public-2.5.0.post1/types_aiobotocore_ecr_public.egg-info/SOURCES.txt` & `types-aiobotocore-ecr-public-2.5.1/types_aiobotocore_ecr_public.egg-info/SOURCES.txt`

 * *Files identical despite different names*

