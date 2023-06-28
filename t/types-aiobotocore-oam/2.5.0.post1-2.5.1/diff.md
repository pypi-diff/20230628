# Comparing `tmp/types-aiobotocore-oam-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-oam-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-oam-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-oam-2.5.1.tar", last modified: Wed Jun 28 01:43:54 2023, max compression
```

## Comparing `types-aiobotocore-oam-2.5.0.post1.tar` & `types-aiobotocore-oam-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.759466 types-aiobotocore-oam-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14410 2023-03-11 12:27:03.759466 types-aiobotocore-oam-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12822 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.759466 types-aiobotocore-oam-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2105 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.759466 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/
--rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1126 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      982 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14752 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14725 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8417 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8415 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4310 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4304 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9649 2023-03-11 12:19:17.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9640 2023-03-11 12:19:17.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:16.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.759466 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14410 2023-03-11 12:27:03.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:03.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:03.000000 types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.482183 types-aiobotocore-oam-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14398 2023-06-28 01:43:54.470183 types-aiobotocore-oam-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12816 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:54.482183 types-aiobotocore-oam-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2099 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.470183 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/
+-rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1126 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14752 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14725 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8626 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8624 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4196 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4191 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9677 2023-06-28 01:36:01.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9668 2023-06-28 01:36:01.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:00.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.470183 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14398 2023-06-28 01:43:54.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:54.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:54.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:54.000000 types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-oam-2.5.0.post1/LICENSE` & `types-aiobotocore-oam-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-oam-2.5.0.post1/PKG-INFO` & `types-aiobotocore-oam-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-oam
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-oam"></a>
 
 # types-aiobotocore-oam
 
 [![PyPI - types-aiobotocore-oam](https://img.shields.io/pypi/v/types-aiobotocore-oam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-oam)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-oam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-oam)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-oam?color=blue)](https://pypistats.org/packages/types-aiobotocore-oam)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatchObservabilityAccessManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager)
+[aiobotocore.CloudWatchObservabilityAccessManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager)
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
 [types-aiobotocore-oam docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,44 +325,44 @@
 
 `types_aiobotocore_oam.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_oam.type_defs import (
     CreateLinkInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLinkOutputTypeDef,
     CreateSinkInputRequestTypeDef,
+    CreateSinkOutputTypeDef,
     DeleteLinkInputRequestTypeDef,
     DeleteSinkInputRequestTypeDef,
     GetLinkInputRequestTypeDef,
+    GetLinkOutputTypeDef,
     GetSinkInputRequestTypeDef,
+    GetSinkOutputTypeDef,
     GetSinkPolicyInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetSinkPolicyOutputTypeDef,
+    ListAttachedLinksInputListAttachedLinksPaginateTypeDef,
     ListAttachedLinksInputRequestTypeDef,
     ListAttachedLinksItemTypeDef,
+    ListLinksInputListLinksPaginateTypeDef,
     ListLinksInputRequestTypeDef,
     ListLinksItemTypeDef,
+    ListSinksInputListSinksPaginateTypeDef,
     ListSinksInputRequestTypeDef,
     ListSinksItemTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutSinkPolicyInputRequestTypeDef,
+    PutSinkPolicyOutputTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateLinkInputRequestTypeDef,
-    CreateLinkOutputTypeDef,
-    CreateSinkOutputTypeDef,
-    GetLinkOutputTypeDef,
-    GetSinkOutputTypeDef,
-    GetSinkPolicyOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    PutSinkPolicyOutputTypeDef,
     UpdateLinkOutputTypeDef,
-    ListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-    ListLinksInputListLinksPaginateTypeDef,
-    ListSinksInputListSinksPaginateTypeDef,
     ListAttachedLinksOutputTypeDef,
     ListLinksOutputTypeDef,
     ListSinksOutputTypeDef,
 )
 
 
 def get_structure() -> CreateLinkInputRequestTypeDef:
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/README.md` & `types-aiobotocore-oam-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-oam"></a>
 
 # types-aiobotocore-oam
 
 [![PyPI - types-aiobotocore-oam](https://img.shields.io/pypi/v/types-aiobotocore-oam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-oam)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-oam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-oam)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-oam?color=blue)](https://pypistats.org/packages/types-aiobotocore-oam)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatchObservabilityAccessManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager)
+[aiobotocore.CloudWatchObservabilityAccessManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager)
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
 [types-aiobotocore-oam docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,44 +292,44 @@
 
 `types_aiobotocore_oam.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_oam.type_defs import (
     CreateLinkInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLinkOutputTypeDef,
     CreateSinkInputRequestTypeDef,
+    CreateSinkOutputTypeDef,
     DeleteLinkInputRequestTypeDef,
     DeleteSinkInputRequestTypeDef,
     GetLinkInputRequestTypeDef,
+    GetLinkOutputTypeDef,
     GetSinkInputRequestTypeDef,
+    GetSinkOutputTypeDef,
     GetSinkPolicyInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetSinkPolicyOutputTypeDef,
+    ListAttachedLinksInputListAttachedLinksPaginateTypeDef,
     ListAttachedLinksInputRequestTypeDef,
     ListAttachedLinksItemTypeDef,
+    ListLinksInputListLinksPaginateTypeDef,
     ListLinksInputRequestTypeDef,
     ListLinksItemTypeDef,
+    ListSinksInputListSinksPaginateTypeDef,
     ListSinksInputRequestTypeDef,
     ListSinksItemTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutSinkPolicyInputRequestTypeDef,
+    PutSinkPolicyOutputTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateLinkInputRequestTypeDef,
-    CreateLinkOutputTypeDef,
-    CreateSinkOutputTypeDef,
-    GetLinkOutputTypeDef,
-    GetSinkOutputTypeDef,
-    GetSinkPolicyOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    PutSinkPolicyOutputTypeDef,
     UpdateLinkOutputTypeDef,
-    ListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-    ListLinksInputListLinksPaginateTypeDef,
-    ListSinksInputListSinksPaginateTypeDef,
     ListAttachedLinksOutputTypeDef,
     ListLinksOutputTypeDef,
     ListSinksOutputTypeDef,
 )
 
 
 def get_structure() -> CreateLinkInputRequestTypeDef:
@@ -339,43 +339,43 @@
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/setup.py` & `types-aiobotocore-oam-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-oam.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-oam",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_oam"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.0 service"
-        " generated with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.1 service"
+        " generated with mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/",
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/__init__.py` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/__init__.pyi` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/__main__.py` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.0\nVersion:     "
-        "    2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.1\nVersion:     "
+        "    2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager\nOther"
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/client.py` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/client.pyi` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/literals.py` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/literals.pyi` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -93,14 +93,15 @@
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
@@ -179,14 +180,15 @@
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
@@ -197,14 +199,15 @@
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
@@ -240,14 +243,15 @@
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
@@ -266,16 +270,19 @@
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
@@ -359,15 +366,17 @@
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/paginator.py` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: CloudWatchObservabilityAccessManagerClient
 
         list_attached_links_paginator: ListAttachedLinksPaginator = client.get_paginator("list_attached_links")
         list_links_paginator: ListLinksPaginator = client.get_paginator("list_links")
         list_sinks_paginator: ListSinksPaginator = client.get_paginator("list_sinks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAttachedLinksOutputTypeDef,
     ListLinksOutputTypeDef,
     ListSinksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListAttachedLinksPaginator", "ListLinksPaginator", "ListSinksPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -59,43 +52,43 @@
 class ListAttachedLinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListAttachedLinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listattachedlinkspaginator)
     """
 
     def paginate(
-        self, *, SinkIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SinkIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedLinksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListAttachedLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listattachedlinkspaginator)
         """
 
 
 class ListLinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListLinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listlinkspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLinksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listlinkspaginator)
         """
 
 
 class ListSinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListSinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listsinkspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSinksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListSinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listsinkspaginator)
         """
```

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/paginator.pyi` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: CloudWatchObservabilityAccessManagerClient
 
         list_attached_links_paginator: ListAttachedLinksPaginator = client.get_paginator("list_attached_links")
         list_links_paginator: ListLinksPaginator = client.get_paginator("list_links")
         list_sinks_paginator: ListSinksPaginator = client.get_paginator("list_sinks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAttachedLinksOutputTypeDef,
     ListLinksOutputTypeDef,
     ListSinksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListAttachedLinksPaginator", "ListLinksPaginator", "ListSinksPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -55,41 +49,41 @@
 class ListAttachedLinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListAttachedLinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listattachedlinkspaginator)
     """
 
     def paginate(
-        self, *, SinkIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SinkIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedLinksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListAttachedLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listattachedlinkspaginator)
         """
 
 class ListLinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListLinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listlinkspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLinksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listlinkspaginator)
         """
 
 class ListSinksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListSinks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listsinkspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSinksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager.Paginator.ListSinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/paginators/#listsinkspaginator)
         """
```

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/type_defs.py` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -20,44 +20,44 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CreateLinkInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateLinkOutputTypeDef",
     "CreateSinkInputRequestTypeDef",
+    "CreateSinkOutputTypeDef",
     "DeleteLinkInputRequestTypeDef",
     "DeleteSinkInputRequestTypeDef",
     "GetLinkInputRequestTypeDef",
+    "GetLinkOutputTypeDef",
     "GetSinkInputRequestTypeDef",
+    "GetSinkOutputTypeDef",
     "GetSinkPolicyInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetSinkPolicyOutputTypeDef",
+    "ListAttachedLinksInputListAttachedLinksPaginateTypeDef",
     "ListAttachedLinksInputRequestTypeDef",
     "ListAttachedLinksItemTypeDef",
+    "ListLinksInputListLinksPaginateTypeDef",
     "ListLinksInputRequestTypeDef",
     "ListLinksItemTypeDef",
+    "ListSinksInputListSinksPaginateTypeDef",
     "ListSinksInputRequestTypeDef",
     "ListSinksItemTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutSinkPolicyInputRequestTypeDef",
+    "PutSinkPolicyOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateLinkInputRequestTypeDef",
-    "CreateLinkOutputTypeDef",
-    "CreateSinkOutputTypeDef",
-    "GetLinkOutputTypeDef",
-    "GetSinkOutputTypeDef",
-    "GetSinkPolicyOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "PutSinkPolicyOutputTypeDef",
     "UpdateLinkOutputTypeDef",
-    "ListAttachedLinksInputListAttachedLinksPaginateTypeDef",
-    "ListLinksInputListLinksPaginateTypeDef",
-    "ListSinksInputListSinksPaginateTypeDef",
     "ListAttachedLinksOutputTypeDef",
     "ListLinksOutputTypeDef",
     "ListSinksOutputTypeDef",
 )
 
 _RequiredCreateLinkInputRequestTypeDef = TypedDict(
     "_RequiredCreateLinkInputRequestTypeDef",
@@ -78,22 +78,25 @@
 
 class CreateLinkInputRequestTypeDef(
     _RequiredCreateLinkInputRequestTypeDef, _OptionalCreateLinkInputRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateLinkOutputTypeDef = TypedDict(
+    "CreateLinkOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "Id": str,
+        "Label": str,
+        "LabelTemplate": str,
+        "ResourceTypes": List[str],
+        "SinkArn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSinkInputRequestTypeDef = TypedDict(
     "_RequiredCreateSinkInputRequestTypeDef",
     {
         "Name": str,
@@ -110,14 +113,25 @@
 
 class CreateSinkInputRequestTypeDef(
     _RequiredCreateSinkInputRequestTypeDef, _OptionalCreateSinkInputRequestTypeDef
 ):
     pass
 
 
+CreateSinkOutputTypeDef = TypedDict(
+    "CreateSinkOutputTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "Name": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLinkInputRequestTypeDef = TypedDict(
     "DeleteLinkInputRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
@@ -131,38 +145,85 @@
 GetLinkInputRequestTypeDef = TypedDict(
     "GetLinkInputRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
+GetLinkOutputTypeDef = TypedDict(
+    "GetLinkOutputTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "Label": str,
+        "LabelTemplate": str,
+        "ResourceTypes": List[str],
+        "SinkArn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSinkInputRequestTypeDef = TypedDict(
     "GetSinkInputRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
+GetSinkOutputTypeDef = TypedDict(
+    "GetSinkOutputTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "Name": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSinkPolicyInputRequestTypeDef = TypedDict(
     "GetSinkPolicyInputRequestTypeDef",
     {
         "SinkIdentifier": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetSinkPolicyOutputTypeDef = TypedDict(
+    "GetSinkPolicyOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "SinkArn": str,
+        "SinkId": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef",
+    {
+        "SinkIdentifier": str,
+    },
+)
+_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAttachedLinksInputListAttachedLinksPaginateTypeDef(
+    _RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef,
+    _OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttachedLinksInputRequestTypeDef = TypedDict(
     "_RequiredListAttachedLinksInputRequestTypeDef",
     {
         "SinkIdentifier": str,
     },
 )
 _OptionalListAttachedLinksInputRequestTypeDef = TypedDict(
@@ -187,14 +248,22 @@
         "Label": str,
         "LinkArn": str,
         "ResourceTypes": List[str],
     },
     total=False,
 )
 
+ListLinksInputListLinksPaginateTypeDef = TypedDict(
+    "ListLinksInputListLinksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLinksInputRequestTypeDef = TypedDict(
     "ListLinksInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -208,14 +277,22 @@
         "Label": str,
         "ResourceTypes": List[str],
         "SinkArn": str,
     },
     total=False,
 )
 
+ListSinksInputListSinksPaginateTypeDef = TypedDict(
+    "ListSinksInputListSinksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSinksInputRequestTypeDef = TypedDict(
     "ListSinksInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -234,195 +311,118 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
-PutSinkPolicyInputRequestTypeDef = TypedDict(
-    "PutSinkPolicyInputRequestTypeDef",
-    {
-        "SinkIdentifier": str,
-        "Policy": str,
-    },
-)
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Mapping[str, str],
-    },
-)
-
-UntagResourceInputRequestTypeDef = TypedDict(
-    "UntagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
-    },
-)
-
-UpdateLinkInputRequestTypeDef = TypedDict(
-    "UpdateLinkInputRequestTypeDef",
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
     {
-        "Identifier": str,
-        "ResourceTypes": Sequence[ResourceTypeType],
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateLinkOutputTypeDef = TypedDict(
-    "CreateLinkOutputTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Label": str,
-        "LabelTemplate": str,
-        "ResourceTypes": List[str],
-        "SinkArn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-CreateSinkOutputTypeDef = TypedDict(
-    "CreateSinkOutputTypeDef",
+PutSinkPolicyInputRequestTypeDef = TypedDict(
+    "PutSinkPolicyInputRequestTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Name": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SinkIdentifier": str,
+        "Policy": str,
     },
 )
 
-GetLinkOutputTypeDef = TypedDict(
-    "GetLinkOutputTypeDef",
+PutSinkPolicyOutputTypeDef = TypedDict(
+    "PutSinkPolicyOutputTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Label": str,
-        "LabelTemplate": str,
-        "ResourceTypes": List[str],
         "SinkArn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SinkId": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetSinkOutputTypeDef = TypedDict(
-    "GetSinkOutputTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Name": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-GetSinkPolicyOutputTypeDef = TypedDict(
-    "GetSinkPolicyOutputTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "SinkArn": str,
-        "SinkId": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Mapping[str, str],
     },
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
+UntagResourceInputRequestTypeDef = TypedDict(
+    "UntagResourceInputRequestTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
-PutSinkPolicyOutputTypeDef = TypedDict(
-    "PutSinkPolicyOutputTypeDef",
+UpdateLinkInputRequestTypeDef = TypedDict(
+    "UpdateLinkInputRequestTypeDef",
     {
-        "SinkArn": str,
-        "SinkId": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Identifier": str,
+        "ResourceTypes": Sequence[ResourceTypeType],
     },
 )
 
 UpdateLinkOutputTypeDef = TypedDict(
     "UpdateLinkOutputTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Label": str,
         "LabelTemplate": str,
         "ResourceTypes": List[str],
         "SinkArn": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef",
-    {
-        "SinkIdentifier": str,
-    },
-)
-_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttachedLinksInputListAttachedLinksPaginateTypeDef(
-    _RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-    _OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-):
-    pass
-
-
-ListLinksInputListLinksPaginateTypeDef = TypedDict(
-    "ListLinksInputListLinksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListSinksInputListSinksPaginateTypeDef = TypedDict(
-    "ListSinksInputListSinksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListAttachedLinksOutputTypeDef = TypedDict(
     "ListAttachedLinksOutputTypeDef",
     {
         "Items": List[ListAttachedLinksItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLinksOutputTypeDef = TypedDict(
     "ListLinksOutputTypeDef",
     {
         "Items": List[ListLinksItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSinksOutputTypeDef = TypedDict(
     "ListSinksOutputTypeDef",
     {
         "Items": List[ListSinksItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam/type_defs.pyi` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam/type_defs.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -19,44 +19,44 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CreateLinkInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateLinkOutputTypeDef",
     "CreateSinkInputRequestTypeDef",
+    "CreateSinkOutputTypeDef",
     "DeleteLinkInputRequestTypeDef",
     "DeleteSinkInputRequestTypeDef",
     "GetLinkInputRequestTypeDef",
+    "GetLinkOutputTypeDef",
     "GetSinkInputRequestTypeDef",
+    "GetSinkOutputTypeDef",
     "GetSinkPolicyInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetSinkPolicyOutputTypeDef",
+    "ListAttachedLinksInputListAttachedLinksPaginateTypeDef",
     "ListAttachedLinksInputRequestTypeDef",
     "ListAttachedLinksItemTypeDef",
+    "ListLinksInputListLinksPaginateTypeDef",
     "ListLinksInputRequestTypeDef",
     "ListLinksItemTypeDef",
+    "ListSinksInputListSinksPaginateTypeDef",
     "ListSinksInputRequestTypeDef",
     "ListSinksItemTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutSinkPolicyInputRequestTypeDef",
+    "PutSinkPolicyOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateLinkInputRequestTypeDef",
-    "CreateLinkOutputTypeDef",
-    "CreateSinkOutputTypeDef",
-    "GetLinkOutputTypeDef",
-    "GetSinkOutputTypeDef",
-    "GetSinkPolicyOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "PutSinkPolicyOutputTypeDef",
     "UpdateLinkOutputTypeDef",
-    "ListAttachedLinksInputListAttachedLinksPaginateTypeDef",
-    "ListLinksInputListLinksPaginateTypeDef",
-    "ListSinksInputListSinksPaginateTypeDef",
     "ListAttachedLinksOutputTypeDef",
     "ListLinksOutputTypeDef",
     "ListSinksOutputTypeDef",
 )
 
 _RequiredCreateLinkInputRequestTypeDef = TypedDict(
     "_RequiredCreateLinkInputRequestTypeDef",
@@ -75,22 +75,25 @@
 )
 
 class CreateLinkInputRequestTypeDef(
     _RequiredCreateLinkInputRequestTypeDef, _OptionalCreateLinkInputRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateLinkOutputTypeDef = TypedDict(
+    "CreateLinkOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "Id": str,
+        "Label": str,
+        "LabelTemplate": str,
+        "ResourceTypes": List[str],
+        "SinkArn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSinkInputRequestTypeDef = TypedDict(
     "_RequiredCreateSinkInputRequestTypeDef",
     {
         "Name": str,
@@ -105,14 +108,25 @@
 )
 
 class CreateSinkInputRequestTypeDef(
     _RequiredCreateSinkInputRequestTypeDef, _OptionalCreateSinkInputRequestTypeDef
 ):
     pass
 
+CreateSinkOutputTypeDef = TypedDict(
+    "CreateSinkOutputTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "Name": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLinkInputRequestTypeDef = TypedDict(
     "DeleteLinkInputRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
@@ -126,38 +140,83 @@
 GetLinkInputRequestTypeDef = TypedDict(
     "GetLinkInputRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
+GetLinkOutputTypeDef = TypedDict(
+    "GetLinkOutputTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "Label": str,
+        "LabelTemplate": str,
+        "ResourceTypes": List[str],
+        "SinkArn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSinkInputRequestTypeDef = TypedDict(
     "GetSinkInputRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
+GetSinkOutputTypeDef = TypedDict(
+    "GetSinkOutputTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "Name": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSinkPolicyInputRequestTypeDef = TypedDict(
     "GetSinkPolicyInputRequestTypeDef",
     {
         "SinkIdentifier": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetSinkPolicyOutputTypeDef = TypedDict(
+    "GetSinkPolicyOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "SinkArn": str,
+        "SinkId": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef",
+    {
+        "SinkIdentifier": str,
+    },
+)
+_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAttachedLinksInputListAttachedLinksPaginateTypeDef(
+    _RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef,
+    _OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttachedLinksInputRequestTypeDef = TypedDict(
     "_RequiredListAttachedLinksInputRequestTypeDef",
     {
         "SinkIdentifier": str,
     },
 )
 _OptionalListAttachedLinksInputRequestTypeDef = TypedDict(
@@ -180,14 +239,22 @@
         "Label": str,
         "LinkArn": str,
         "ResourceTypes": List[str],
     },
     total=False,
 )
 
+ListLinksInputListLinksPaginateTypeDef = TypedDict(
+    "ListLinksInputListLinksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLinksInputRequestTypeDef = TypedDict(
     "ListLinksInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -201,14 +268,22 @@
         "Label": str,
         "ResourceTypes": List[str],
         "SinkArn": str,
     },
     total=False,
 )
 
+ListSinksInputListSinksPaginateTypeDef = TypedDict(
+    "ListSinksInputListSinksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSinksInputRequestTypeDef = TypedDict(
     "ListSinksInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -227,193 +302,118 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
-PutSinkPolicyInputRequestTypeDef = TypedDict(
-    "PutSinkPolicyInputRequestTypeDef",
-    {
-        "SinkIdentifier": str,
-        "Policy": str,
-    },
-)
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Mapping[str, str],
-    },
-)
-
-UntagResourceInputRequestTypeDef = TypedDict(
-    "UntagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
-    },
-)
-
-UpdateLinkInputRequestTypeDef = TypedDict(
-    "UpdateLinkInputRequestTypeDef",
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
     {
-        "Identifier": str,
-        "ResourceTypes": Sequence[ResourceTypeType],
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateLinkOutputTypeDef = TypedDict(
-    "CreateLinkOutputTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Label": str,
-        "LabelTemplate": str,
-        "ResourceTypes": List[str],
-        "SinkArn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-CreateSinkOutputTypeDef = TypedDict(
-    "CreateSinkOutputTypeDef",
+PutSinkPolicyInputRequestTypeDef = TypedDict(
+    "PutSinkPolicyInputRequestTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Name": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SinkIdentifier": str,
+        "Policy": str,
     },
 )
 
-GetLinkOutputTypeDef = TypedDict(
-    "GetLinkOutputTypeDef",
+PutSinkPolicyOutputTypeDef = TypedDict(
+    "PutSinkPolicyOutputTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Label": str,
-        "LabelTemplate": str,
-        "ResourceTypes": List[str],
         "SinkArn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SinkId": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetSinkOutputTypeDef = TypedDict(
-    "GetSinkOutputTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Arn": str,
-        "Id": str,
-        "Name": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-GetSinkPolicyOutputTypeDef = TypedDict(
-    "GetSinkPolicyOutputTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "SinkArn": str,
-        "SinkId": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Mapping[str, str],
     },
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
+UntagResourceInputRequestTypeDef = TypedDict(
+    "UntagResourceInputRequestTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
-PutSinkPolicyOutputTypeDef = TypedDict(
-    "PutSinkPolicyOutputTypeDef",
+UpdateLinkInputRequestTypeDef = TypedDict(
+    "UpdateLinkInputRequestTypeDef",
     {
-        "SinkArn": str,
-        "SinkId": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Identifier": str,
+        "ResourceTypes": Sequence[ResourceTypeType],
     },
 )
 
 UpdateLinkOutputTypeDef = TypedDict(
     "UpdateLinkOutputTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Label": str,
         "LabelTemplate": str,
         "ResourceTypes": List[str],
         "SinkArn": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef",
-    {
-        "SinkIdentifier": str,
-    },
-)
-_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttachedLinksInputListAttachedLinksPaginateTypeDef(
-    _RequiredListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-    _OptionalListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-):
-    pass
-
-ListLinksInputListLinksPaginateTypeDef = TypedDict(
-    "ListLinksInputListLinksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSinksInputListSinksPaginateTypeDef = TypedDict(
-    "ListSinksInputListSinksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListAttachedLinksOutputTypeDef = TypedDict(
     "ListAttachedLinksOutputTypeDef",
     {
         "Items": List[ListAttachedLinksItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLinksOutputTypeDef = TypedDict(
     "ListLinksOutputTypeDef",
     {
         "Items": List[ListLinksItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSinksOutputTypeDef = TypedDict(
     "ListSinksOutputTypeDef",
     {
         "Items": List[ListSinksItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/PKG-INFO` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-oam
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudWatchObservabilityAccessManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-oam"></a>
 
 # types-aiobotocore-oam
 
 [![PyPI - types-aiobotocore-oam](https://img.shields.io/pypi/v/types-aiobotocore-oam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-oam)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-oam.svg?color=blue)](https://pypi.org/project/types-aiobotocore-oam)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-oam?color=blue)](https://pypistats.org/packages/types-aiobotocore-oam)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatchObservabilityAccessManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager)
+[aiobotocore.CloudWatchObservabilityAccessManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/oam.html#CloudWatchObservabilityAccessManager)
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
 [types-aiobotocore-oam docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_oam/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,44 +325,44 @@
 
 `types_aiobotocore_oam.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_oam.type_defs import (
     CreateLinkInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLinkOutputTypeDef,
     CreateSinkInputRequestTypeDef,
+    CreateSinkOutputTypeDef,
     DeleteLinkInputRequestTypeDef,
     DeleteSinkInputRequestTypeDef,
     GetLinkInputRequestTypeDef,
+    GetLinkOutputTypeDef,
     GetSinkInputRequestTypeDef,
+    GetSinkOutputTypeDef,
     GetSinkPolicyInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetSinkPolicyOutputTypeDef,
+    ListAttachedLinksInputListAttachedLinksPaginateTypeDef,
     ListAttachedLinksInputRequestTypeDef,
     ListAttachedLinksItemTypeDef,
+    ListLinksInputListLinksPaginateTypeDef,
     ListLinksInputRequestTypeDef,
     ListLinksItemTypeDef,
+    ListSinksInputListSinksPaginateTypeDef,
     ListSinksInputRequestTypeDef,
     ListSinksItemTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutSinkPolicyInputRequestTypeDef,
+    PutSinkPolicyOutputTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateLinkInputRequestTypeDef,
-    CreateLinkOutputTypeDef,
-    CreateSinkOutputTypeDef,
-    GetLinkOutputTypeDef,
-    GetSinkOutputTypeDef,
-    GetSinkPolicyOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    PutSinkPolicyOutputTypeDef,
     UpdateLinkOutputTypeDef,
-    ListAttachedLinksInputListAttachedLinksPaginateTypeDef,
-    ListLinksInputListLinksPaginateTypeDef,
-    ListSinksInputListSinksPaginateTypeDef,
     ListAttachedLinksOutputTypeDef,
     ListLinksOutputTypeDef,
     ListSinksOutputTypeDef,
 )
 
 
 def get_structure() -> CreateLinkInputRequestTypeDef:
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

### Comparing `types-aiobotocore-oam-2.5.0.post1/types_aiobotocore_oam.egg-info/SOURCES.txt` & `types-aiobotocore-oam-2.5.1/types_aiobotocore_oam.egg-info/SOURCES.txt`

 * *Files identical despite different names*

