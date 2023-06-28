# Comparing `tmp/types-aiobotocore-mediastore-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediastore-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediastore-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:59 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediastore-data-2.5.1.tar", last modified: Wed Jun 28 01:43:51 2023, max compression
```

## Comparing `types-aiobotocore-mediastore-data-2.5.0.post1.tar` & `types-aiobotocore-mediastore-data-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.051420 types-aiobotocore-mediastore-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13697 2023-03-11 12:26:59.051420 types-aiobotocore-mediastore-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12095 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:59.051420 types-aiobotocore-mediastore-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2179 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.051420 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/
--rw-r--r--   0 runner    (1001) docker     (123)      676 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      675 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7841 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7826 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7908 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7906 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     4712 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     4707 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.051420 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13697 2023-03-11 12:26:58.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:26:58.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:58.000000 types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.210177 types-aiobotocore-mediastore-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13697 2023-06-28 01:43:51.210177 types-aiobotocore-mediastore-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12101 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:51.210177 types-aiobotocore-mediastore-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.210177 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/
+-rw-r--r--   0 runner    (1001) docker     (123)      676 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      675 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7841 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7826 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8117 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8115 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2038 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2035 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     4722 2023-06-28 01:35:20.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4717 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.210177 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13697 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/LICENSE` & `types-aiobotocore-mediastore-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediastore-data-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediastore-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaStoreData 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaStoreData 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediastore-data"></a>
 
 # types-aiobotocore-mediastore-data
 
 [![PyPI - types-aiobotocore-mediastore-data](https://img.shields.io/pypi/v/types-aiobotocore-mediastore-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediastore-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediastore-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediastore-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaStoreData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
+[aiobotocore.MediaStoreData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
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
 [types-aiobotocore-mediastore-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,68 +319,68 @@
 `types_aiobotocore_mediastore_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediastore_data.type_defs import (
     DeleteObjectRequestRequestTypeDef,
     DescribeObjectRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeObjectResponseTypeDef,
     GetObjectRequestRequestTypeDef,
+    GetObjectResponseTypeDef,
     ItemTypeDef,
-    PaginatorConfigTypeDef,
+    ListItemsRequestListItemsPaginateTypeDef,
     ListItemsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutObjectRequestRequestTypeDef,
-    DescribeObjectResponseTypeDef,
-    GetObjectResponseTypeDef,
     PutObjectResponseTypeDef,
+    ResponseMetadataTypeDef,
     ListItemsResponseTypeDef,
-    ListItemsRequestListItemsPaginateTypeDef,
 )
 
 
 def get_structure() -> DeleteObjectRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/README.md` & `types-aiobotocore-mediastore-data-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediastore-data"></a>
 
 # types-aiobotocore-mediastore-data
 
 [![PyPI - types-aiobotocore-mediastore-data](https://img.shields.io/pypi/v/types-aiobotocore-mediastore-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediastore-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediastore-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediastore-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaStoreData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
+[aiobotocore.MediaStoreData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
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
 [types-aiobotocore-mediastore-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -286,68 +286,68 @@
 `types_aiobotocore_mediastore_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediastore_data.type_defs import (
     DeleteObjectRequestRequestTypeDef,
     DescribeObjectRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeObjectResponseTypeDef,
     GetObjectRequestRequestTypeDef,
+    GetObjectResponseTypeDef,
     ItemTypeDef,
-    PaginatorConfigTypeDef,
+    ListItemsRequestListItemsPaginateTypeDef,
     ListItemsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutObjectRequestRequestTypeDef,
-    DescribeObjectResponseTypeDef,
-    GetObjectResponseTypeDef,
     PutObjectResponseTypeDef,
+    ResponseMetadataTypeDef,
     ListItemsResponseTypeDef,
-    ListItemsRequestListItemsPaginateTypeDef,
 )
 
 
 def get_structure() -> DeleteObjectRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/setup.py` & `types-aiobotocore-mediastore-data-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediastore-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediastore-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediastore_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaStoreData 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaStoreData 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/"
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/__init__.py` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/__init__.pyi` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/__main__.py` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaStoreData 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaStoreData 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData\nOther"
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/client.py` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/client.pyi` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/literals.py` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,28 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ItemTypeType",
     "ListItemsPaginatorName",
     "StorageClassType",
     "UploadAvailabilityType",
     "MediaStoreDataServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ItemTypeType = Literal["FOLDER", "OBJECT"]
 ListItemsPaginatorName = Literal["list_items"]
 StorageClassType = Literal["TEMPORAL"]
 UploadAvailabilityType = Literal["STANDARD", "STREAMING"]
 MediaStoreDataServiceName = Literal["mediastore-data"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -95,14 +93,15 @@
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
@@ -181,14 +180,15 @@
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
@@ -199,14 +199,15 @@
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
@@ -242,14 +243,15 @@
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
@@ -268,16 +270,19 @@
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
@@ -361,15 +366,17 @@
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/literals.pyi` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,26 +14,28 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ItemTypeType",
     "ListItemsPaginatorName",
     "StorageClassType",
     "UploadAvailabilityType",
     "MediaStoreDataServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ItemTypeType = Literal["FOLDER", "OBJECT"]
 ListItemsPaginatorName = Literal["list_items"]
 StorageClassType = Literal["TEMPORAL"]
 UploadAvailabilityType = Literal["STANDARD", "STREAMING"]
 MediaStoreDataServiceName = Literal["mediastore-data"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -93,14 +95,15 @@
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
@@ -179,14 +182,15 @@
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
@@ -197,14 +201,15 @@
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
@@ -240,14 +245,15 @@
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
@@ -266,16 +272,19 @@
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
@@ -359,15 +368,17 @@
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/paginator.py` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("mediastore-data") as client:
         client: MediaStoreDataClient
 
         list_items_paginator: ListItemsPaginator = client.get_paginator("list_items")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListItemsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListItemsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData.Paginator.ListItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/paginators/#listitemspaginator)
     """
 
     def paginate(
-        self, *, Path: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Path: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData.Paginator.ListItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/paginators/#listitemspaginator)
         """
```

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/paginator.pyi` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("mediastore-data") as client:
         client: MediaStoreDataClient
 
         list_items_paginator: ListItemsPaginator = client.get_paginator("list_items")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListItemsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListItemsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData.Paginator.ListItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/paginators/#listitemspaginator)
     """
 
     def paginate(
-        self, *, Path: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Path: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData.Paginator.ListItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/paginators/#listitemspaginator)
         """
```

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/type_defs.py` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -28,25 +28,25 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DeleteObjectRequestRequestTypeDef",
     "DescribeObjectRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeObjectResponseTypeDef",
     "GetObjectRequestRequestTypeDef",
+    "GetObjectResponseTypeDef",
     "ItemTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListItemsRequestListItemsPaginateTypeDef",
     "ListItemsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutObjectRequestRequestTypeDef",
-    "DescribeObjectResponseTypeDef",
-    "GetObjectResponseTypeDef",
     "PutObjectResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "ListItemsResponseTypeDef",
-    "ListItemsRequestListItemsPaginateTypeDef",
 )
 
 DeleteObjectRequestRequestTypeDef = TypedDict(
     "DeleteObjectRequestRequestTypeDef",
     {
         "Path": str,
     },
@@ -55,22 +55,23 @@
 DescribeObjectRequestRequestTypeDef = TypedDict(
     "DescribeObjectRequestRequestTypeDef",
     {
         "Path": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeObjectResponseTypeDef = TypedDict(
+    "DescribeObjectResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ETag": str,
+        "ContentType": str,
+        "ContentLength": int,
+        "CacheControl": str,
+        "LastModified": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetObjectRequestRequestTypeDef = TypedDict(
     "_RequiredGetObjectRequestRequestTypeDef",
     {
         "Path": str,
@@ -87,47 +88,71 @@
 
 class GetObjectRequestRequestTypeDef(
     _RequiredGetObjectRequestRequestTypeDef, _OptionalGetObjectRequestRequestTypeDef
 ):
     pass
 
 
+GetObjectResponseTypeDef = TypedDict(
+    "GetObjectResponseTypeDef",
+    {
+        "Body": StreamingBody,
+        "CacheControl": str,
+        "ContentRange": str,
+        "ContentLength": int,
+        "ContentType": str,
+        "ETag": str,
+        "LastModified": datetime,
+        "StatusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ItemTypeDef = TypedDict(
     "ItemTypeDef",
     {
         "Name": str,
         "Type": ItemTypeType,
         "ETag": str,
         "LastModified": datetime,
         "ContentType": str,
         "ContentLength": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListItemsRequestListItemsPaginateTypeDef = TypedDict(
+    "ListItemsRequestListItemsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Path": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListItemsRequestRequestTypeDef = TypedDict(
     "ListItemsRequestRequestTypeDef",
     {
         "Path": str,
         "MaxResults": int,
         "NextToken": str,
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
 _RequiredPutObjectRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectRequestRequestTypeDef",
     {
         "Body": Union[str, bytes, IO[Any], StreamingBody],
         "Path": str,
     },
 )
@@ -145,61 +170,36 @@
 
 class PutObjectRequestRequestTypeDef(
     _RequiredPutObjectRequestRequestTypeDef, _OptionalPutObjectRequestRequestTypeDef
 ):
     pass
 
 
-DescribeObjectResponseTypeDef = TypedDict(
-    "DescribeObjectResponseTypeDef",
-    {
-        "ETag": str,
-        "ContentType": str,
-        "ContentLength": int,
-        "CacheControl": str,
-        "LastModified": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectResponseTypeDef = TypedDict(
-    "GetObjectResponseTypeDef",
-    {
-        "Body": StreamingBody,
-        "CacheControl": str,
-        "ContentRange": str,
-        "ContentLength": int,
-        "ContentType": str,
-        "ETag": str,
-        "LastModified": datetime,
-        "StatusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 PutObjectResponseTypeDef = TypedDict(
     "PutObjectResponseTypeDef",
     {
         "ContentSHA256": str,
         "ETag": str,
         "StorageClass": Literal["TEMPORAL"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListItemsResponseTypeDef = TypedDict(
-    "ListItemsResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Items": List[ItemTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-ListItemsRequestListItemsPaginateTypeDef = TypedDict(
-    "ListItemsRequestListItemsPaginateTypeDef",
+ListItemsResponseTypeDef = TypedDict(
+    "ListItemsResponseTypeDef",
     {
-        "Path": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Items": List[ItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
```

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data/type_defs.pyi` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -27,25 +27,25 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DeleteObjectRequestRequestTypeDef",
     "DescribeObjectRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeObjectResponseTypeDef",
     "GetObjectRequestRequestTypeDef",
+    "GetObjectResponseTypeDef",
     "ItemTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListItemsRequestListItemsPaginateTypeDef",
     "ListItemsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutObjectRequestRequestTypeDef",
-    "DescribeObjectResponseTypeDef",
-    "GetObjectResponseTypeDef",
     "PutObjectResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "ListItemsResponseTypeDef",
-    "ListItemsRequestListItemsPaginateTypeDef",
 )
 
 DeleteObjectRequestRequestTypeDef = TypedDict(
     "DeleteObjectRequestRequestTypeDef",
     {
         "Path": str,
     },
@@ -54,22 +54,23 @@
 DescribeObjectRequestRequestTypeDef = TypedDict(
     "DescribeObjectRequestRequestTypeDef",
     {
         "Path": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeObjectResponseTypeDef = TypedDict(
+    "DescribeObjectResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ETag": str,
+        "ContentType": str,
+        "ContentLength": int,
+        "CacheControl": str,
+        "LastModified": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetObjectRequestRequestTypeDef = TypedDict(
     "_RequiredGetObjectRequestRequestTypeDef",
     {
         "Path": str,
@@ -84,47 +85,71 @@
 )
 
 class GetObjectRequestRequestTypeDef(
     _RequiredGetObjectRequestRequestTypeDef, _OptionalGetObjectRequestRequestTypeDef
 ):
     pass
 
+GetObjectResponseTypeDef = TypedDict(
+    "GetObjectResponseTypeDef",
+    {
+        "Body": StreamingBody,
+        "CacheControl": str,
+        "ContentRange": str,
+        "ContentLength": int,
+        "ContentType": str,
+        "ETag": str,
+        "LastModified": datetime,
+        "StatusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ItemTypeDef = TypedDict(
     "ItemTypeDef",
     {
         "Name": str,
         "Type": ItemTypeType,
         "ETag": str,
         "LastModified": datetime,
         "ContentType": str,
         "ContentLength": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListItemsRequestListItemsPaginateTypeDef = TypedDict(
+    "ListItemsRequestListItemsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Path": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListItemsRequestRequestTypeDef = TypedDict(
     "ListItemsRequestRequestTypeDef",
     {
         "Path": str,
         "MaxResults": int,
         "NextToken": str,
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
 _RequiredPutObjectRequestRequestTypeDef = TypedDict(
     "_RequiredPutObjectRequestRequestTypeDef",
     {
         "Body": Union[str, bytes, IO[Any], StreamingBody],
         "Path": str,
     },
 )
@@ -140,61 +165,36 @@
 )
 
 class PutObjectRequestRequestTypeDef(
     _RequiredPutObjectRequestRequestTypeDef, _OptionalPutObjectRequestRequestTypeDef
 ):
     pass
 
-DescribeObjectResponseTypeDef = TypedDict(
-    "DescribeObjectResponseTypeDef",
-    {
-        "ETag": str,
-        "ContentType": str,
-        "ContentLength": int,
-        "CacheControl": str,
-        "LastModified": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectResponseTypeDef = TypedDict(
-    "GetObjectResponseTypeDef",
-    {
-        "Body": StreamingBody,
-        "CacheControl": str,
-        "ContentRange": str,
-        "ContentLength": int,
-        "ContentType": str,
-        "ETag": str,
-        "LastModified": datetime,
-        "StatusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 PutObjectResponseTypeDef = TypedDict(
     "PutObjectResponseTypeDef",
     {
         "ContentSHA256": str,
         "ETag": str,
         "StorageClass": Literal["TEMPORAL"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListItemsResponseTypeDef = TypedDict(
-    "ListItemsResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Items": List[ItemTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-ListItemsRequestListItemsPaginateTypeDef = TypedDict(
-    "ListItemsRequestListItemsPaginateTypeDef",
+ListItemsResponseTypeDef = TypedDict(
+    "ListItemsResponseTypeDef",
     {
-        "Path": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Items": List[ItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
```

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/PKG-INFO` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediastore-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaStoreData 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaStoreData 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediastore-data"></a>
 
 # types-aiobotocore-mediastore-data
 
 [![PyPI - types-aiobotocore-mediastore-data](https://img.shields.io/pypi/v/types-aiobotocore-mediastore-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediastore-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediastore-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediastore-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaStoreData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
+[aiobotocore.MediaStoreData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore-data.html#MediaStoreData)
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
 [types-aiobotocore-mediastore-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,68 +319,68 @@
 `types_aiobotocore_mediastore_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediastore_data.type_defs import (
     DeleteObjectRequestRequestTypeDef,
     DescribeObjectRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeObjectResponseTypeDef,
     GetObjectRequestRequestTypeDef,
+    GetObjectResponseTypeDef,
     ItemTypeDef,
-    PaginatorConfigTypeDef,
+    ListItemsRequestListItemsPaginateTypeDef,
     ListItemsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutObjectRequestRequestTypeDef,
-    DescribeObjectResponseTypeDef,
-    GetObjectResponseTypeDef,
     PutObjectResponseTypeDef,
+    ResponseMetadataTypeDef,
     ListItemsResponseTypeDef,
-    ListItemsRequestListItemsPaginateTypeDef,
 )
 
 
 def get_structure() -> DeleteObjectRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-mediastore-data-2.5.0.post1/types_aiobotocore_mediastore_data.egg-info/SOURCES.txt` & `types-aiobotocore-mediastore-data-2.5.1/types_aiobotocore_mediastore_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

