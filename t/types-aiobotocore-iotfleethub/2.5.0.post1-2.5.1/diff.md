# Comparing `tmp/types-aiobotocore-iotfleethub-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotfleethub-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotfleethub-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotfleethub-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotfleethub-2.5.0.post1.tar` & `types-aiobotocore-iotfleethub-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.939299 types-aiobotocore-iotfleethub-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13709 2023-03-11 12:26:46.935299 types-aiobotocore-iotfleethub-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12122 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.939299 types-aiobotocore-iotfleethub-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.935299 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/
--rw-r--r--   0 runner    (1001) docker     (123)      691 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      690 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9569 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9551 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7920 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7918 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2175 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6167 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6158 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:22.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.935299 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13709 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      889 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:46.000000 types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.498154 types-aiobotocore-iotfleethub-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13705 2023-06-28 01:43:38.498154 types-aiobotocore-iotfleethub-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12124 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.498154 types-aiobotocore-iotfleethub-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.494153 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/
+-rw-r--r--   0 runner    (1001) docker     (123)      691 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      690 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9569 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9551 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8129 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8127 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2057 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2054 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6177 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6168 2023-06-28 01:33:00.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:59.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.498154 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13705 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      889 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:38.000000 types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/LICENSE` & `types-aiobotocore-iotfleethub-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotfleethub-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotfleethub
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTFleetHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTFleetHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotfleethub"></a>
 
 # types-aiobotocore-iotfleethub
 
 [![PyPI - types-aiobotocore-iotfleethub](https://img.shields.io/pypi/v/types-aiobotocore-iotfleethub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleethub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotfleethub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleethub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotfleethub?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotfleethub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTFleetHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
+[aiobotocore.IoTFleetHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
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
 [types-aiobotocore-iotfleethub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,71 +319,71 @@
 `types_aiobotocore_iotfleethub.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotfleethub.type_defs import (
     ApplicationSummaryTypeDef,
     CreateApplicationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeApplicationResponseTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    CreateApplicationResponseTypeDef,
-    DescribeApplicationResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
 )
 
 
 def get_structure() -> ApplicationSummaryTypeDef:
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/README.md` & `types-aiobotocore-iotfleethub-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotfleethub"></a>
 
 # types-aiobotocore-iotfleethub
 
 [![PyPI - types-aiobotocore-iotfleethub](https://img.shields.io/pypi/v/types-aiobotocore-iotfleethub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleethub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotfleethub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleethub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotfleethub?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotfleethub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTFleetHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
+[aiobotocore.IoTFleetHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
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
 [types-aiobotocore-iotfleethub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -286,71 +286,71 @@
 `types_aiobotocore_iotfleethub.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotfleethub.type_defs import (
     ApplicationSummaryTypeDef,
     CreateApplicationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeApplicationResponseTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    CreateApplicationResponseTypeDef,
-    DescribeApplicationResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
 )
 
 
 def get_structure() -> ApplicationSummaryTypeDef:
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/setup.py` & `types-aiobotocore-iotfleethub-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotfleethub.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotfleethub",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotfleethub"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTFleetHub 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTFleetHub 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/"
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/__init__.py` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/__init__.pyi` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/__main__.py` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTFleetHub 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTFleetHub 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub\nOther"
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/client.py` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/client.pyi` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/literals.py` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,26 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ApplicationStateType",
     "ListApplicationsPaginatorName",
     "IoTFleetHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ApplicationStateType = Literal["ACTIVE", "CREATE_FAILED", "CREATING", "DELETE_FAILED", "DELETING"]
 ListApplicationsPaginatorName = Literal["list_applications"]
 IoTFleetHubServiceName = Literal["iotfleethub"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -91,14 +89,15 @@
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
@@ -177,14 +176,15 @@
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
@@ -195,14 +195,15 @@
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
@@ -238,14 +239,15 @@
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
@@ -264,16 +266,19 @@
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
@@ -357,15 +362,17 @@
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/literals.pyi` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -14,24 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ApplicationStateType",
     "ListApplicationsPaginatorName",
     "IoTFleetHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ApplicationStateType = Literal["ACTIVE", "CREATE_FAILED", "CREATING", "DELETE_FAILED", "DELETING"]
 ListApplicationsPaginatorName = Literal["list_applications"]
 IoTFleetHubServiceName = Literal["iotfleethub"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -89,14 +91,15 @@
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
@@ -175,14 +178,15 @@
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
@@ -193,14 +197,15 @@
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
@@ -236,14 +241,15 @@
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
@@ -262,16 +268,19 @@
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
@@ -355,15 +364,17 @@
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/paginator.py` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("iotfleethub") as client:
         client: IoTFleetHubClient
 
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListApplicationsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListApplicationsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/paginators/#listapplicationspaginator)
         """
```

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/paginator.pyi` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("iotfleethub") as client:
         client: IoTFleetHubClient
 
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListApplicationsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListApplicationsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/paginators/#listapplicationspaginator)
         """
```

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/type_defs.py` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -21,28 +21,28 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ApplicationSummaryTypeDef",
     "CreateApplicationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApplicationResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeApplicationResponseTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "DescribeApplicationResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
 )
 
 _RequiredApplicationSummaryTypeDef = TypedDict(
     "_RequiredApplicationSummaryTypeDef",
     {
         "applicationId": str,
         "applicationName": str,
@@ -87,22 +87,20 @@
 
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationId": str,
+        "applicationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeleteApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
@@ -126,20 +124,37 @@
 DescribeApplicationRequestRequestTypeDef = TypedDict(
     "DescribeApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeApplicationResponseTypeDef = TypedDict(
+    "DescribeApplicationResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "applicationId": str,
+        "applicationArn": str,
+        "applicationName": str,
+        "applicationDescription": str,
+        "applicationUrl": str,
+        "applicationState": ApplicationStateType,
+        "applicationCreationDate": int,
+        "applicationLastUpdateDate": int,
+        "roleArn": str,
+        "ssoClientId": str,
+        "errorMessage": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
@@ -151,14 +166,43 @@
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -190,59 +234,15 @@
 
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
 
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "applicationId": str,
-        "applicationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicationResponseTypeDef = TypedDict(
-    "DescribeApplicationResponseTypeDef",
-    {
-        "applicationId": str,
-        "applicationArn": str,
-        "applicationName": str,
-        "applicationDescription": str,
-        "applicationUrl": str,
-        "applicationState": ApplicationStateType,
-        "applicationCreationDate": int,
-        "applicationLastUpdateDate": int,
-        "roleArn": str,
-        "ssoClientId": str,
-        "errorMessage": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "applicationSummaries": List[ApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
```

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub/type_defs.pyi` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -20,28 +20,28 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ApplicationSummaryTypeDef",
     "CreateApplicationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApplicationResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeApplicationResponseTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "DescribeApplicationResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
 )
 
 _RequiredApplicationSummaryTypeDef = TypedDict(
     "_RequiredApplicationSummaryTypeDef",
     {
         "applicationId": str,
         "applicationName": str,
@@ -82,22 +82,20 @@
 )
 
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationId": str,
+        "applicationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeleteApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
@@ -119,20 +117,37 @@
 DescribeApplicationRequestRequestTypeDef = TypedDict(
     "DescribeApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeApplicationResponseTypeDef = TypedDict(
+    "DescribeApplicationResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "applicationId": str,
+        "applicationArn": str,
+        "applicationName": str,
+        "applicationDescription": str,
+        "applicationUrl": str,
+        "applicationState": ApplicationStateType,
+        "applicationCreationDate": int,
+        "applicationLastUpdateDate": int,
+        "roleArn": str,
+        "ssoClientId": str,
+        "errorMessage": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
@@ -144,14 +159,43 @@
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -181,59 +225,15 @@
 )
 
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "applicationId": str,
-        "applicationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicationResponseTypeDef = TypedDict(
-    "DescribeApplicationResponseTypeDef",
-    {
-        "applicationId": str,
-        "applicationArn": str,
-        "applicationName": str,
-        "applicationDescription": str,
-        "applicationUrl": str,
-        "applicationState": ApplicationStateType,
-        "applicationCreationDate": int,
-        "applicationLastUpdateDate": int,
-        "roleArn": str,
-        "ssoClientId": str,
-        "errorMessage": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "applicationSummaries": List[ApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
```

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/PKG-INFO` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotfleethub
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTFleetHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTFleetHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotfleethub"></a>
 
 # types-aiobotocore-iotfleethub
 
 [![PyPI - types-aiobotocore-iotfleethub](https://img.shields.io/pypi/v/types-aiobotocore-iotfleethub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleethub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotfleethub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotfleethub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotfleethub?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotfleethub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTFleetHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
+[aiobotocore.IoTFleetHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotfleethub.html#IoTFleetHub)
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
 [types-aiobotocore-iotfleethub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotfleethub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,71 +319,71 @@
 `types_aiobotocore_iotfleethub.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotfleethub.type_defs import (
     ApplicationSummaryTypeDef,
     CreateApplicationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeApplicationResponseTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    CreateApplicationResponseTypeDef,
-    DescribeApplicationResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
 )
 
 
 def get_structure() -> ApplicationSummaryTypeDef:
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

### Comparing `types-aiobotocore-iotfleethub-2.5.0.post1/types_aiobotocore_iotfleethub.egg-info/SOURCES.txt` & `types-aiobotocore-iotfleethub-2.5.1/types_aiobotocore_iotfleethub.egg-info/SOURCES.txt`

 * *Files identical despite different names*

