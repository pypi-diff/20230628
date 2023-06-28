# Comparing `tmp/types-aiobotocore-cloudhsm-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudhsm-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudhsm-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudhsm-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudhsm-2.5.0.post1.tar` & `types-aiobotocore-cloudhsm-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:20.007025 types-aiobotocore-cloudhsm-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14880 2023-03-11 12:26:19.999024 types-aiobotocore-cloudhsm-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13305 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:20.007025 types-aiobotocore-cloudhsm-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.999024 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16664 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16632 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8080 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8078 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4126 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4120 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    12605 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12596 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:54.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.999024 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14880 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.342107 types-aiobotocore-cloudhsm-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14873 2023-06-28 01:43:13.342107 types-aiobotocore-cloudhsm-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13304 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.342107 types-aiobotocore-cloudhsm-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.342107 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      983 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16664 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16632 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8289 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8287 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4012 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4007 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    12651 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12642 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:31.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.342107 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14873 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudhsm-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudhsm-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudhsm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudHSM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudHSM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudhsm"></a>
 
 # types-aiobotocore-cloudhsm
 
 [![PyPI - types-aiobotocore-cloudhsm](https://img.shields.io/pypi/v/types-aiobotocore-cloudhsm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudhsm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudhsm?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudhsm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudHSM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
+[aiobotocore.CloudHSM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
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
 [types-aiobotocore-cloudhsm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -328,101 +328,101 @@
 
 `types_aiobotocore_cloudhsm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudhsm.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AddTagsToResourceResponseTypeDef,
     CreateHapgRequestRequestTypeDef,
+    CreateHapgResponseTypeDef,
     CreateHsmRequestRequestTypeDef,
+    CreateHsmResponseTypeDef,
     CreateLunaClientRequestRequestTypeDef,
+    CreateLunaClientResponseTypeDef,
     DeleteHapgRequestRequestTypeDef,
+    DeleteHapgResponseTypeDef,
     DeleteHsmRequestRequestTypeDef,
+    DeleteHsmResponseTypeDef,
     DeleteLunaClientRequestRequestTypeDef,
+    DeleteLunaClientResponseTypeDef,
     DescribeHapgRequestRequestTypeDef,
+    DescribeHapgResponseTypeDef,
     DescribeHsmRequestRequestTypeDef,
+    DescribeHsmResponseTypeDef,
     DescribeLunaClientRequestRequestTypeDef,
+    DescribeLunaClientResponseTypeDef,
     GetConfigRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetConfigResponseTypeDef,
+    ListAvailableZonesResponseTypeDef,
+    ListHapgsRequestListHapgsPaginateTypeDef,
     ListHapgsRequestRequestTypeDef,
+    ListHapgsResponseTypeDef,
+    ListHsmsRequestListHsmsPaginateTypeDef,
     ListHsmsRequestRequestTypeDef,
+    ListHsmsResponseTypeDef,
+    ListLunaClientsRequestListLunaClientsPaginateTypeDef,
     ListLunaClientsRequestRequestTypeDef,
+    ListLunaClientsResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModifyHapgRequestRequestTypeDef,
+    ModifyHapgResponseTypeDef,
     ModifyHsmRequestRequestTypeDef,
+    ModifyHsmResponseTypeDef,
     ModifyLunaClientRequestRequestTypeDef,
+    ModifyLunaClientResponseTypeDef,
+    PaginatorConfigTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
+    RemoveTagsFromResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
-    AddTagsToResourceResponseTypeDef,
-    CreateHapgResponseTypeDef,
-    CreateHsmResponseTypeDef,
-    CreateLunaClientResponseTypeDef,
-    DeleteHapgResponseTypeDef,
-    DeleteHsmResponseTypeDef,
-    DeleteLunaClientResponseTypeDef,
-    DescribeHapgResponseTypeDef,
-    DescribeHsmResponseTypeDef,
-    DescribeLunaClientResponseTypeDef,
-    GetConfigResponseTypeDef,
-    ListAvailableZonesResponseTypeDef,
-    ListHapgsResponseTypeDef,
-    ListHsmsResponseTypeDef,
-    ListLunaClientsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    ModifyHapgResponseTypeDef,
-    ModifyHsmResponseTypeDef,
-    ModifyLunaClientResponseTypeDef,
-    RemoveTagsFromResourceResponseTypeDef,
-    ListHapgsRequestListHapgsPaginateTypeDef,
-    ListHsmsRequestListHsmsPaginateTypeDef,
-    ListLunaClientsRequestListLunaClientsPaginateTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/README.md` & `types-aiobotocore-cloudhsm-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudhsm"></a>
 
 # types-aiobotocore-cloudhsm
 
 [![PyPI - types-aiobotocore-cloudhsm](https://img.shields.io/pypi/v/types-aiobotocore-cloudhsm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudhsm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudhsm?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudhsm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudHSM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
+[aiobotocore.CloudHSM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
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
 [types-aiobotocore-cloudhsm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,101 +295,101 @@
 
 `types_aiobotocore_cloudhsm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudhsm.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AddTagsToResourceResponseTypeDef,
     CreateHapgRequestRequestTypeDef,
+    CreateHapgResponseTypeDef,
     CreateHsmRequestRequestTypeDef,
+    CreateHsmResponseTypeDef,
     CreateLunaClientRequestRequestTypeDef,
+    CreateLunaClientResponseTypeDef,
     DeleteHapgRequestRequestTypeDef,
+    DeleteHapgResponseTypeDef,
     DeleteHsmRequestRequestTypeDef,
+    DeleteHsmResponseTypeDef,
     DeleteLunaClientRequestRequestTypeDef,
+    DeleteLunaClientResponseTypeDef,
     DescribeHapgRequestRequestTypeDef,
+    DescribeHapgResponseTypeDef,
     DescribeHsmRequestRequestTypeDef,
+    DescribeHsmResponseTypeDef,
     DescribeLunaClientRequestRequestTypeDef,
+    DescribeLunaClientResponseTypeDef,
     GetConfigRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetConfigResponseTypeDef,
+    ListAvailableZonesResponseTypeDef,
+    ListHapgsRequestListHapgsPaginateTypeDef,
     ListHapgsRequestRequestTypeDef,
+    ListHapgsResponseTypeDef,
+    ListHsmsRequestListHsmsPaginateTypeDef,
     ListHsmsRequestRequestTypeDef,
+    ListHsmsResponseTypeDef,
+    ListLunaClientsRequestListLunaClientsPaginateTypeDef,
     ListLunaClientsRequestRequestTypeDef,
+    ListLunaClientsResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModifyHapgRequestRequestTypeDef,
+    ModifyHapgResponseTypeDef,
     ModifyHsmRequestRequestTypeDef,
+    ModifyHsmResponseTypeDef,
     ModifyLunaClientRequestRequestTypeDef,
+    ModifyLunaClientResponseTypeDef,
+    PaginatorConfigTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
+    RemoveTagsFromResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
-    AddTagsToResourceResponseTypeDef,
-    CreateHapgResponseTypeDef,
-    CreateHsmResponseTypeDef,
-    CreateLunaClientResponseTypeDef,
-    DeleteHapgResponseTypeDef,
-    DeleteHsmResponseTypeDef,
-    DeleteLunaClientResponseTypeDef,
-    DescribeHapgResponseTypeDef,
-    DescribeHsmResponseTypeDef,
-    DescribeLunaClientResponseTypeDef,
-    GetConfigResponseTypeDef,
-    ListAvailableZonesResponseTypeDef,
-    ListHapgsResponseTypeDef,
-    ListHsmsResponseTypeDef,
-    ListLunaClientsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    ModifyHapgResponseTypeDef,
-    ModifyHsmResponseTypeDef,
-    ModifyLunaClientResponseTypeDef,
-    RemoveTagsFromResourceResponseTypeDef,
-    ListHapgsRequestListHapgsPaginateTypeDef,
-    ListHsmsRequestListHsmsPaginateTypeDef,
-    ListLunaClientsRequestListLunaClientsPaginateTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/setup.py` & `types-aiobotocore-cloudhsm-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudhsm.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudhsm",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudhsm"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudHSM 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.CloudHSM 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/"
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/__init__.py` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/__init__.pyi` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/__main__.py` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudHSM 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudHSM 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM\nOther"
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/client.py` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/client.pyi` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/literals.py` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -103,14 +103,15 @@
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
@@ -189,14 +190,15 @@
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
@@ -207,14 +209,15 @@
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
@@ -250,14 +253,15 @@
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
@@ -276,16 +280,19 @@
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
@@ -369,15 +376,17 @@
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/literals.pyi` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -101,14 +101,15 @@
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
@@ -187,14 +188,15 @@
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
@@ -205,14 +207,15 @@
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
@@ -248,14 +251,15 @@
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
@@ -274,16 +278,19 @@
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
@@ -367,15 +374,17 @@
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/paginator.py` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: CloudHSMClient
 
         list_hapgs_paginator: ListHapgsPaginator = client.get_paginator("list_hapgs")
         list_hsms_paginator: ListHsmsPaginator = client.get_paginator("list_hsms")
         list_luna_clients_paginator: ListLunaClientsPaginator = client.get_paginator("list_luna_clients")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListHapgsResponseTypeDef,
     ListHsmsResponseTypeDef,
     ListLunaClientsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListHapgsPaginator", "ListHsmsPaginator", "ListLunaClientsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -59,43 +52,43 @@
 class ListHapgsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHapgs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhapgspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHapgsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHapgs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhapgspaginator)
         """
 
 
 class ListHsmsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHsms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhsmspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHsmsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHsms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhsmspaginator)
         """
 
 
 class ListLunaClientsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListLunaClients)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listlunaclientspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLunaClientsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListLunaClients.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listlunaclientspaginator)
         """
```

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/paginator.pyi` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: CloudHSMClient
 
         list_hapgs_paginator: ListHapgsPaginator = client.get_paginator("list_hapgs")
         list_hsms_paginator: ListHsmsPaginator = client.get_paginator("list_hsms")
         list_luna_clients_paginator: ListLunaClientsPaginator = client.get_paginator("list_luna_clients")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListHapgsResponseTypeDef,
     ListHsmsResponseTypeDef,
     ListLunaClientsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListHapgsPaginator", "ListHsmsPaginator", "ListLunaClientsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -55,41 +49,41 @@
 class ListHapgsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHapgs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhapgspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHapgsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHapgs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhapgspaginator)
         """
 
 class ListHsmsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHsms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhsmspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHsmsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListHsms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listhsmspaginator)
         """
 
 class ListLunaClientsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListLunaClients)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listlunaclientspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLunaClientsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM.Paginator.ListLunaClients.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/paginators/#listlunaclientspaginator)
         """
```

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/type_defs.py` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,86 +24,91 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddTagsToResourceResponseTypeDef",
     "CreateHapgRequestRequestTypeDef",
+    "CreateHapgResponseTypeDef",
     "CreateHsmRequestRequestTypeDef",
+    "CreateHsmResponseTypeDef",
     "CreateLunaClientRequestRequestTypeDef",
+    "CreateLunaClientResponseTypeDef",
     "DeleteHapgRequestRequestTypeDef",
+    "DeleteHapgResponseTypeDef",
     "DeleteHsmRequestRequestTypeDef",
+    "DeleteHsmResponseTypeDef",
     "DeleteLunaClientRequestRequestTypeDef",
+    "DeleteLunaClientResponseTypeDef",
     "DescribeHapgRequestRequestTypeDef",
+    "DescribeHapgResponseTypeDef",
     "DescribeHsmRequestRequestTypeDef",
+    "DescribeHsmResponseTypeDef",
     "DescribeLunaClientRequestRequestTypeDef",
+    "DescribeLunaClientResponseTypeDef",
     "GetConfigRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetConfigResponseTypeDef",
+    "ListAvailableZonesResponseTypeDef",
+    "ListHapgsRequestListHapgsPaginateTypeDef",
     "ListHapgsRequestRequestTypeDef",
+    "ListHapgsResponseTypeDef",
+    "ListHsmsRequestListHsmsPaginateTypeDef",
     "ListHsmsRequestRequestTypeDef",
+    "ListHsmsResponseTypeDef",
+    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
     "ListLunaClientsRequestRequestTypeDef",
+    "ListLunaClientsResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ModifyHapgRequestRequestTypeDef",
+    "ModifyHapgResponseTypeDef",
     "ModifyHsmRequestRequestTypeDef",
+    "ModifyHsmResponseTypeDef",
     "ModifyLunaClientRequestRequestTypeDef",
+    "ModifyLunaClientResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveTagsFromResourceRequestRequestTypeDef",
+    "RemoveTagsFromResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "AddTagsToResourceRequestRequestTypeDef",
-    "AddTagsToResourceResponseTypeDef",
-    "CreateHapgResponseTypeDef",
-    "CreateHsmResponseTypeDef",
-    "CreateLunaClientResponseTypeDef",
-    "DeleteHapgResponseTypeDef",
-    "DeleteHsmResponseTypeDef",
-    "DeleteLunaClientResponseTypeDef",
-    "DescribeHapgResponseTypeDef",
-    "DescribeHsmResponseTypeDef",
-    "DescribeLunaClientResponseTypeDef",
-    "GetConfigResponseTypeDef",
-    "ListAvailableZonesResponseTypeDef",
-    "ListHapgsResponseTypeDef",
-    "ListHsmsResponseTypeDef",
-    "ListLunaClientsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "ModifyHapgResponseTypeDef",
-    "ModifyHsmResponseTypeDef",
-    "ModifyLunaClientResponseTypeDef",
-    "RemoveTagsFromResourceResponseTypeDef",
-    "ListHapgsRequestListHapgsPaginateTypeDef",
-    "ListHsmsRequestListHsmsPaginateTypeDef",
-    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddTagsToResourceResponseTypeDef = TypedDict(
+    "AddTagsToResourceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHapgRequestRequestTypeDef = TypedDict(
     "CreateHapgRequestRequestTypeDef",
     {
         "Label": str,
     },
 )
 
+CreateHapgResponseTypeDef = TypedDict(
+    "CreateHapgResponseTypeDef",
+    {
+        "HapgArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateHsmRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHsmRequestRequestTypeDef",
     {
         "SubnetId": str,
         "SshKey": str,
         "IamRoleArn": str,
         "SubscriptionType": Literal["PRODUCTION"],
@@ -123,14 +128,22 @@
 
 class CreateHsmRequestRequestTypeDef(
     _RequiredCreateHsmRequestRequestTypeDef, _OptionalCreateHsmRequestRequestTypeDef
 ):
     pass
 
 
+CreateHsmResponseTypeDef = TypedDict(
+    "CreateHsmResponseTypeDef",
+    {
+        "HsmArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateLunaClientRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLunaClientRequestRequestTypeDef",
     {
         "Certificate": str,
     },
 )
 _OptionalCreateLunaClientRequestRequestTypeDef = TypedDict(
@@ -144,103 +157,250 @@
 
 class CreateLunaClientRequestRequestTypeDef(
     _RequiredCreateLunaClientRequestRequestTypeDef, _OptionalCreateLunaClientRequestRequestTypeDef
 ):
     pass
 
 
+CreateLunaClientResponseTypeDef = TypedDict(
+    "CreateLunaClientResponseTypeDef",
+    {
+        "ClientArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteHapgRequestRequestTypeDef = TypedDict(
     "DeleteHapgRequestRequestTypeDef",
     {
         "HapgArn": str,
     },
 )
 
+DeleteHapgResponseTypeDef = TypedDict(
+    "DeleteHapgResponseTypeDef",
+    {
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteHsmRequestRequestTypeDef = TypedDict(
     "DeleteHsmRequestRequestTypeDef",
     {
         "HsmArn": str,
     },
 )
 
+DeleteHsmResponseTypeDef = TypedDict(
+    "DeleteHsmResponseTypeDef",
+    {
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLunaClientRequestRequestTypeDef = TypedDict(
     "DeleteLunaClientRequestRequestTypeDef",
     {
         "ClientArn": str,
     },
 )
 
+DeleteLunaClientResponseTypeDef = TypedDict(
+    "DeleteLunaClientResponseTypeDef",
+    {
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeHapgRequestRequestTypeDef = TypedDict(
     "DescribeHapgRequestRequestTypeDef",
     {
         "HapgArn": str,
     },
 )
 
+DescribeHapgResponseTypeDef = TypedDict(
+    "DescribeHapgResponseTypeDef",
+    {
+        "HapgArn": str,
+        "HapgSerial": str,
+        "HsmsLastActionFailed": List[str],
+        "HsmsPendingDeletion": List[str],
+        "HsmsPendingRegistration": List[str],
+        "Label": str,
+        "LastModifiedTimestamp": str,
+        "PartitionSerialList": List[str],
+        "State": CloudHsmObjectStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeHsmRequestRequestTypeDef = TypedDict(
     "DescribeHsmRequestRequestTypeDef",
     {
         "HsmArn": str,
         "HsmSerialNumber": str,
     },
     total=False,
 )
 
+DescribeHsmResponseTypeDef = TypedDict(
+    "DescribeHsmResponseTypeDef",
+    {
+        "HsmArn": str,
+        "Status": HsmStatusType,
+        "StatusDetails": str,
+        "AvailabilityZone": str,
+        "EniId": str,
+        "EniIp": str,
+        "SubscriptionType": Literal["PRODUCTION"],
+        "SubscriptionStartDate": str,
+        "SubscriptionEndDate": str,
+        "VpcId": str,
+        "SubnetId": str,
+        "IamRoleArn": str,
+        "SerialNumber": str,
+        "VendorName": str,
+        "HsmType": str,
+        "SoftwareVersion": str,
+        "SshPublicKey": str,
+        "SshKeyLastUpdated": str,
+        "ServerCertUri": str,
+        "ServerCertLastUpdated": str,
+        "Partitions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeLunaClientRequestRequestTypeDef = TypedDict(
     "DescribeLunaClientRequestRequestTypeDef",
     {
         "ClientArn": str,
         "CertificateFingerprint": str,
     },
     total=False,
 )
 
+DescribeLunaClientResponseTypeDef = TypedDict(
+    "DescribeLunaClientResponseTypeDef",
+    {
+        "ClientArn": str,
+        "Certificate": str,
+        "CertificateFingerprint": str,
+        "LastModifiedTimestamp": str,
+        "Label": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetConfigRequestRequestTypeDef = TypedDict(
     "GetConfigRequestRequestTypeDef",
     {
         "ClientArn": str,
         "ClientVersion": ClientVersionType,
         "HapgList": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetConfigResponseTypeDef = TypedDict(
+    "GetConfigResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ConfigType": str,
+        "ConfigFile": str,
+        "ConfigCred": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAvailableZonesResponseTypeDef = TypedDict(
+    "ListAvailableZonesResponseTypeDef",
+    {
+        "AZList": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListHapgsRequestListHapgsPaginateTypeDef = TypedDict(
+    "ListHapgsRequestListHapgsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListHapgsRequestRequestTypeDef = TypedDict(
     "ListHapgsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListHapgsResponseTypeDef = TypedDict(
+    "ListHapgsResponseTypeDef",
+    {
+        "HapgList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListHsmsRequestListHsmsPaginateTypeDef = TypedDict(
+    "ListHsmsRequestListHsmsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHsmsRequestRequestTypeDef = TypedDict(
     "ListHsmsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListHsmsResponseTypeDef = TypedDict(
+    "ListHsmsResponseTypeDef",
+    {
+        "HsmList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListLunaClientsRequestListLunaClientsPaginateTypeDef = TypedDict(
+    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLunaClientsRequestRequestTypeDef = TypedDict(
     "ListLunaClientsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListLunaClientsResponseTypeDef = TypedDict(
+    "ListLunaClientsResponseTypeDef",
+    {
+        "ClientList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
@@ -262,14 +422,22 @@
 
 class ModifyHapgRequestRequestTypeDef(
     _RequiredModifyHapgRequestRequestTypeDef, _OptionalModifyHapgRequestRequestTypeDef
 ):
     pass
 
 
+ModifyHapgResponseTypeDef = TypedDict(
+    "ModifyHapgResponseTypeDef",
+    {
+        "HapgArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredModifyHsmRequestRequestTypeDef = TypedDict(
     "_RequiredModifyHsmRequestRequestTypeDef",
     {
         "HsmArn": str,
     },
 )
 _OptionalModifyHsmRequestRequestTypeDef = TypedDict(
@@ -287,251 +455,83 @@
 
 class ModifyHsmRequestRequestTypeDef(
     _RequiredModifyHsmRequestRequestTypeDef, _OptionalModifyHsmRequestRequestTypeDef
 ):
     pass
 
 
-ModifyLunaClientRequestRequestTypeDef = TypedDict(
-    "ModifyLunaClientRequestRequestTypeDef",
-    {
-        "ClientArn": str,
-        "Certificate": str,
-    },
-)
-
-RemoveTagsFromResourceRequestRequestTypeDef = TypedDict(
-    "RemoveTagsFromResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeyList": Sequence[str],
-    },
-)
-
-AddTagsToResourceRequestRequestTypeDef = TypedDict(
-    "AddTagsToResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagList": Sequence[TagTypeDef],
-    },
-)
-
-AddTagsToResourceResponseTypeDef = TypedDict(
-    "AddTagsToResourceResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateHapgResponseTypeDef = TypedDict(
-    "CreateHapgResponseTypeDef",
-    {
-        "HapgArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateHsmResponseTypeDef = TypedDict(
-    "CreateHsmResponseTypeDef",
-    {
-        "HsmArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLunaClientResponseTypeDef = TypedDict(
-    "CreateLunaClientResponseTypeDef",
-    {
-        "ClientArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHapgResponseTypeDef = TypedDict(
-    "DeleteHapgResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHsmResponseTypeDef = TypedDict(
-    "DeleteHsmResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteLunaClientResponseTypeDef = TypedDict(
-    "DeleteLunaClientResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeHapgResponseTypeDef = TypedDict(
-    "DescribeHapgResponseTypeDef",
-    {
-        "HapgArn": str,
-        "HapgSerial": str,
-        "HsmsLastActionFailed": List[str],
-        "HsmsPendingDeletion": List[str],
-        "HsmsPendingRegistration": List[str],
-        "Label": str,
-        "LastModifiedTimestamp": str,
-        "PartitionSerialList": List[str],
-        "State": CloudHsmObjectStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeHsmResponseTypeDef = TypedDict(
-    "DescribeHsmResponseTypeDef",
+ModifyHsmResponseTypeDef = TypedDict(
+    "ModifyHsmResponseTypeDef",
     {
         "HsmArn": str,
-        "Status": HsmStatusType,
-        "StatusDetails": str,
-        "AvailabilityZone": str,
-        "EniId": str,
-        "EniIp": str,
-        "SubscriptionType": Literal["PRODUCTION"],
-        "SubscriptionStartDate": str,
-        "SubscriptionEndDate": str,
-        "VpcId": str,
-        "SubnetId": str,
-        "IamRoleArn": str,
-        "SerialNumber": str,
-        "VendorName": str,
-        "HsmType": str,
-        "SoftwareVersion": str,
-        "SshPublicKey": str,
-        "SshKeyLastUpdated": str,
-        "ServerCertUri": str,
-        "ServerCertLastUpdated": str,
-        "Partitions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeLunaClientResponseTypeDef = TypedDict(
-    "DescribeLunaClientResponseTypeDef",
+ModifyLunaClientRequestRequestTypeDef = TypedDict(
+    "ModifyLunaClientRequestRequestTypeDef",
     {
         "ClientArn": str,
         "Certificate": str,
-        "CertificateFingerprint": str,
-        "LastModifiedTimestamp": str,
-        "Label": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetConfigResponseTypeDef = TypedDict(
-    "GetConfigResponseTypeDef",
-    {
-        "ConfigType": str,
-        "ConfigFile": str,
-        "ConfigCred": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAvailableZonesResponseTypeDef = TypedDict(
-    "ListAvailableZonesResponseTypeDef",
-    {
-        "AZList": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListHapgsResponseTypeDef = TypedDict(
-    "ListHapgsResponseTypeDef",
-    {
-        "HapgList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListHsmsResponseTypeDef = TypedDict(
-    "ListHsmsResponseTypeDef",
-    {
-        "HsmList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListLunaClientsResponseTypeDef = TypedDict(
-    "ListLunaClientsResponseTypeDef",
-    {
-        "ClientList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-ModifyHapgResponseTypeDef = TypedDict(
-    "ModifyHapgResponseTypeDef",
+ModifyLunaClientResponseTypeDef = TypedDict(
+    "ModifyLunaClientResponseTypeDef",
     {
-        "HapgArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ClientArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ModifyHsmResponseTypeDef = TypedDict(
-    "ModifyHsmResponseTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "HsmArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-ModifyLunaClientResponseTypeDef = TypedDict(
-    "ModifyLunaClientResponseTypeDef",
+RemoveTagsFromResourceRequestRequestTypeDef = TypedDict(
+    "RemoveTagsFromResourceRequestRequestTypeDef",
     {
-        "ClientArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeyList": Sequence[str],
     },
 )
 
 RemoveTagsFromResourceResponseTypeDef = TypedDict(
     "RemoveTagsFromResourceResponseTypeDef",
     {
         "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListHapgsRequestListHapgsPaginateTypeDef = TypedDict(
-    "ListHapgsRequestListHapgsPaginateTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
-ListHsmsRequestListHsmsPaginateTypeDef = TypedDict(
-    "ListHsmsRequestListHsmsPaginateTypeDef",
+AddTagsToResourceRequestRequestTypeDef = TypedDict(
+    "AddTagsToResourceRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceArn": str,
+        "TagList": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
-ListLunaClientsRequestListLunaClientsPaginateTypeDef = TypedDict(
-    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "TagList": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
```

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm/type_defs.pyi` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -23,86 +23,91 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddTagsToResourceResponseTypeDef",
     "CreateHapgRequestRequestTypeDef",
+    "CreateHapgResponseTypeDef",
     "CreateHsmRequestRequestTypeDef",
+    "CreateHsmResponseTypeDef",
     "CreateLunaClientRequestRequestTypeDef",
+    "CreateLunaClientResponseTypeDef",
     "DeleteHapgRequestRequestTypeDef",
+    "DeleteHapgResponseTypeDef",
     "DeleteHsmRequestRequestTypeDef",
+    "DeleteHsmResponseTypeDef",
     "DeleteLunaClientRequestRequestTypeDef",
+    "DeleteLunaClientResponseTypeDef",
     "DescribeHapgRequestRequestTypeDef",
+    "DescribeHapgResponseTypeDef",
     "DescribeHsmRequestRequestTypeDef",
+    "DescribeHsmResponseTypeDef",
     "DescribeLunaClientRequestRequestTypeDef",
+    "DescribeLunaClientResponseTypeDef",
     "GetConfigRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetConfigResponseTypeDef",
+    "ListAvailableZonesResponseTypeDef",
+    "ListHapgsRequestListHapgsPaginateTypeDef",
     "ListHapgsRequestRequestTypeDef",
+    "ListHapgsResponseTypeDef",
+    "ListHsmsRequestListHsmsPaginateTypeDef",
     "ListHsmsRequestRequestTypeDef",
+    "ListHsmsResponseTypeDef",
+    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
     "ListLunaClientsRequestRequestTypeDef",
+    "ListLunaClientsResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ModifyHapgRequestRequestTypeDef",
+    "ModifyHapgResponseTypeDef",
     "ModifyHsmRequestRequestTypeDef",
+    "ModifyHsmResponseTypeDef",
     "ModifyLunaClientRequestRequestTypeDef",
+    "ModifyLunaClientResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveTagsFromResourceRequestRequestTypeDef",
+    "RemoveTagsFromResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "AddTagsToResourceRequestRequestTypeDef",
-    "AddTagsToResourceResponseTypeDef",
-    "CreateHapgResponseTypeDef",
-    "CreateHsmResponseTypeDef",
-    "CreateLunaClientResponseTypeDef",
-    "DeleteHapgResponseTypeDef",
-    "DeleteHsmResponseTypeDef",
-    "DeleteLunaClientResponseTypeDef",
-    "DescribeHapgResponseTypeDef",
-    "DescribeHsmResponseTypeDef",
-    "DescribeLunaClientResponseTypeDef",
-    "GetConfigResponseTypeDef",
-    "ListAvailableZonesResponseTypeDef",
-    "ListHapgsResponseTypeDef",
-    "ListHsmsResponseTypeDef",
-    "ListLunaClientsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "ModifyHapgResponseTypeDef",
-    "ModifyHsmResponseTypeDef",
-    "ModifyLunaClientResponseTypeDef",
-    "RemoveTagsFromResourceResponseTypeDef",
-    "ListHapgsRequestListHapgsPaginateTypeDef",
-    "ListHsmsRequestListHsmsPaginateTypeDef",
-    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddTagsToResourceResponseTypeDef = TypedDict(
+    "AddTagsToResourceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHapgRequestRequestTypeDef = TypedDict(
     "CreateHapgRequestRequestTypeDef",
     {
         "Label": str,
     },
 )
 
+CreateHapgResponseTypeDef = TypedDict(
+    "CreateHapgResponseTypeDef",
+    {
+        "HapgArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateHsmRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHsmRequestRequestTypeDef",
     {
         "SubnetId": str,
         "SshKey": str,
         "IamRoleArn": str,
         "SubscriptionType": Literal["PRODUCTION"],
@@ -120,14 +125,22 @@
 )
 
 class CreateHsmRequestRequestTypeDef(
     _RequiredCreateHsmRequestRequestTypeDef, _OptionalCreateHsmRequestRequestTypeDef
 ):
     pass
 
+CreateHsmResponseTypeDef = TypedDict(
+    "CreateHsmResponseTypeDef",
+    {
+        "HsmArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateLunaClientRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLunaClientRequestRequestTypeDef",
     {
         "Certificate": str,
     },
 )
 _OptionalCreateLunaClientRequestRequestTypeDef = TypedDict(
@@ -139,103 +152,250 @@
 )
 
 class CreateLunaClientRequestRequestTypeDef(
     _RequiredCreateLunaClientRequestRequestTypeDef, _OptionalCreateLunaClientRequestRequestTypeDef
 ):
     pass
 
+CreateLunaClientResponseTypeDef = TypedDict(
+    "CreateLunaClientResponseTypeDef",
+    {
+        "ClientArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteHapgRequestRequestTypeDef = TypedDict(
     "DeleteHapgRequestRequestTypeDef",
     {
         "HapgArn": str,
     },
 )
 
+DeleteHapgResponseTypeDef = TypedDict(
+    "DeleteHapgResponseTypeDef",
+    {
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteHsmRequestRequestTypeDef = TypedDict(
     "DeleteHsmRequestRequestTypeDef",
     {
         "HsmArn": str,
     },
 )
 
+DeleteHsmResponseTypeDef = TypedDict(
+    "DeleteHsmResponseTypeDef",
+    {
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLunaClientRequestRequestTypeDef = TypedDict(
     "DeleteLunaClientRequestRequestTypeDef",
     {
         "ClientArn": str,
     },
 )
 
+DeleteLunaClientResponseTypeDef = TypedDict(
+    "DeleteLunaClientResponseTypeDef",
+    {
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeHapgRequestRequestTypeDef = TypedDict(
     "DescribeHapgRequestRequestTypeDef",
     {
         "HapgArn": str,
     },
 )
 
+DescribeHapgResponseTypeDef = TypedDict(
+    "DescribeHapgResponseTypeDef",
+    {
+        "HapgArn": str,
+        "HapgSerial": str,
+        "HsmsLastActionFailed": List[str],
+        "HsmsPendingDeletion": List[str],
+        "HsmsPendingRegistration": List[str],
+        "Label": str,
+        "LastModifiedTimestamp": str,
+        "PartitionSerialList": List[str],
+        "State": CloudHsmObjectStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeHsmRequestRequestTypeDef = TypedDict(
     "DescribeHsmRequestRequestTypeDef",
     {
         "HsmArn": str,
         "HsmSerialNumber": str,
     },
     total=False,
 )
 
+DescribeHsmResponseTypeDef = TypedDict(
+    "DescribeHsmResponseTypeDef",
+    {
+        "HsmArn": str,
+        "Status": HsmStatusType,
+        "StatusDetails": str,
+        "AvailabilityZone": str,
+        "EniId": str,
+        "EniIp": str,
+        "SubscriptionType": Literal["PRODUCTION"],
+        "SubscriptionStartDate": str,
+        "SubscriptionEndDate": str,
+        "VpcId": str,
+        "SubnetId": str,
+        "IamRoleArn": str,
+        "SerialNumber": str,
+        "VendorName": str,
+        "HsmType": str,
+        "SoftwareVersion": str,
+        "SshPublicKey": str,
+        "SshKeyLastUpdated": str,
+        "ServerCertUri": str,
+        "ServerCertLastUpdated": str,
+        "Partitions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeLunaClientRequestRequestTypeDef = TypedDict(
     "DescribeLunaClientRequestRequestTypeDef",
     {
         "ClientArn": str,
         "CertificateFingerprint": str,
     },
     total=False,
 )
 
+DescribeLunaClientResponseTypeDef = TypedDict(
+    "DescribeLunaClientResponseTypeDef",
+    {
+        "ClientArn": str,
+        "Certificate": str,
+        "CertificateFingerprint": str,
+        "LastModifiedTimestamp": str,
+        "Label": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetConfigRequestRequestTypeDef = TypedDict(
     "GetConfigRequestRequestTypeDef",
     {
         "ClientArn": str,
         "ClientVersion": ClientVersionType,
         "HapgList": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetConfigResponseTypeDef = TypedDict(
+    "GetConfigResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ConfigType": str,
+        "ConfigFile": str,
+        "ConfigCred": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAvailableZonesResponseTypeDef = TypedDict(
+    "ListAvailableZonesResponseTypeDef",
+    {
+        "AZList": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListHapgsRequestListHapgsPaginateTypeDef = TypedDict(
+    "ListHapgsRequestListHapgsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListHapgsRequestRequestTypeDef = TypedDict(
     "ListHapgsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListHapgsResponseTypeDef = TypedDict(
+    "ListHapgsResponseTypeDef",
+    {
+        "HapgList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListHsmsRequestListHsmsPaginateTypeDef = TypedDict(
+    "ListHsmsRequestListHsmsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHsmsRequestRequestTypeDef = TypedDict(
     "ListHsmsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListHsmsResponseTypeDef = TypedDict(
+    "ListHsmsResponseTypeDef",
+    {
+        "HsmList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListLunaClientsRequestListLunaClientsPaginateTypeDef = TypedDict(
+    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLunaClientsRequestRequestTypeDef = TypedDict(
     "ListLunaClientsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListLunaClientsResponseTypeDef = TypedDict(
+    "ListLunaClientsResponseTypeDef",
+    {
+        "ClientList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
@@ -255,14 +415,22 @@
 )
 
 class ModifyHapgRequestRequestTypeDef(
     _RequiredModifyHapgRequestRequestTypeDef, _OptionalModifyHapgRequestRequestTypeDef
 ):
     pass
 
+ModifyHapgResponseTypeDef = TypedDict(
+    "ModifyHapgResponseTypeDef",
+    {
+        "HapgArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredModifyHsmRequestRequestTypeDef = TypedDict(
     "_RequiredModifyHsmRequestRequestTypeDef",
     {
         "HsmArn": str,
     },
 )
 _OptionalModifyHsmRequestRequestTypeDef = TypedDict(
@@ -278,251 +446,83 @@
 )
 
 class ModifyHsmRequestRequestTypeDef(
     _RequiredModifyHsmRequestRequestTypeDef, _OptionalModifyHsmRequestRequestTypeDef
 ):
     pass
 
-ModifyLunaClientRequestRequestTypeDef = TypedDict(
-    "ModifyLunaClientRequestRequestTypeDef",
-    {
-        "ClientArn": str,
-        "Certificate": str,
-    },
-)
-
-RemoveTagsFromResourceRequestRequestTypeDef = TypedDict(
-    "RemoveTagsFromResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeyList": Sequence[str],
-    },
-)
-
-AddTagsToResourceRequestRequestTypeDef = TypedDict(
-    "AddTagsToResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagList": Sequence[TagTypeDef],
-    },
-)
-
-AddTagsToResourceResponseTypeDef = TypedDict(
-    "AddTagsToResourceResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateHapgResponseTypeDef = TypedDict(
-    "CreateHapgResponseTypeDef",
-    {
-        "HapgArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateHsmResponseTypeDef = TypedDict(
-    "CreateHsmResponseTypeDef",
-    {
-        "HsmArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLunaClientResponseTypeDef = TypedDict(
-    "CreateLunaClientResponseTypeDef",
-    {
-        "ClientArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHapgResponseTypeDef = TypedDict(
-    "DeleteHapgResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHsmResponseTypeDef = TypedDict(
-    "DeleteHsmResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteLunaClientResponseTypeDef = TypedDict(
-    "DeleteLunaClientResponseTypeDef",
-    {
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeHapgResponseTypeDef = TypedDict(
-    "DescribeHapgResponseTypeDef",
-    {
-        "HapgArn": str,
-        "HapgSerial": str,
-        "HsmsLastActionFailed": List[str],
-        "HsmsPendingDeletion": List[str],
-        "HsmsPendingRegistration": List[str],
-        "Label": str,
-        "LastModifiedTimestamp": str,
-        "PartitionSerialList": List[str],
-        "State": CloudHsmObjectStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeHsmResponseTypeDef = TypedDict(
-    "DescribeHsmResponseTypeDef",
+ModifyHsmResponseTypeDef = TypedDict(
+    "ModifyHsmResponseTypeDef",
     {
         "HsmArn": str,
-        "Status": HsmStatusType,
-        "StatusDetails": str,
-        "AvailabilityZone": str,
-        "EniId": str,
-        "EniIp": str,
-        "SubscriptionType": Literal["PRODUCTION"],
-        "SubscriptionStartDate": str,
-        "SubscriptionEndDate": str,
-        "VpcId": str,
-        "SubnetId": str,
-        "IamRoleArn": str,
-        "SerialNumber": str,
-        "VendorName": str,
-        "HsmType": str,
-        "SoftwareVersion": str,
-        "SshPublicKey": str,
-        "SshKeyLastUpdated": str,
-        "ServerCertUri": str,
-        "ServerCertLastUpdated": str,
-        "Partitions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeLunaClientResponseTypeDef = TypedDict(
-    "DescribeLunaClientResponseTypeDef",
+ModifyLunaClientRequestRequestTypeDef = TypedDict(
+    "ModifyLunaClientRequestRequestTypeDef",
     {
         "ClientArn": str,
         "Certificate": str,
-        "CertificateFingerprint": str,
-        "LastModifiedTimestamp": str,
-        "Label": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetConfigResponseTypeDef = TypedDict(
-    "GetConfigResponseTypeDef",
-    {
-        "ConfigType": str,
-        "ConfigFile": str,
-        "ConfigCred": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAvailableZonesResponseTypeDef = TypedDict(
-    "ListAvailableZonesResponseTypeDef",
-    {
-        "AZList": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListHapgsResponseTypeDef = TypedDict(
-    "ListHapgsResponseTypeDef",
-    {
-        "HapgList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListHsmsResponseTypeDef = TypedDict(
-    "ListHsmsResponseTypeDef",
-    {
-        "HsmList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListLunaClientsResponseTypeDef = TypedDict(
-    "ListLunaClientsResponseTypeDef",
-    {
-        "ClientList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-ModifyHapgResponseTypeDef = TypedDict(
-    "ModifyHapgResponseTypeDef",
+ModifyLunaClientResponseTypeDef = TypedDict(
+    "ModifyLunaClientResponseTypeDef",
     {
-        "HapgArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ClientArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ModifyHsmResponseTypeDef = TypedDict(
-    "ModifyHsmResponseTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "HsmArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-ModifyLunaClientResponseTypeDef = TypedDict(
-    "ModifyLunaClientResponseTypeDef",
+RemoveTagsFromResourceRequestRequestTypeDef = TypedDict(
+    "RemoveTagsFromResourceRequestRequestTypeDef",
     {
-        "ClientArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeyList": Sequence[str],
     },
 )
 
 RemoveTagsFromResourceResponseTypeDef = TypedDict(
     "RemoveTagsFromResourceResponseTypeDef",
     {
         "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListHapgsRequestListHapgsPaginateTypeDef = TypedDict(
-    "ListHapgsRequestListHapgsPaginateTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
-ListHsmsRequestListHsmsPaginateTypeDef = TypedDict(
-    "ListHsmsRequestListHsmsPaginateTypeDef",
+AddTagsToResourceRequestRequestTypeDef = TypedDict(
+    "AddTagsToResourceRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceArn": str,
+        "TagList": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
-ListLunaClientsRequestListLunaClientsPaginateTypeDef = TypedDict(
-    "ListLunaClientsRequestListLunaClientsPaginateTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "TagList": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
```

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/PKG-INFO` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudhsm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudHSM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudHSM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudhsm"></a>
 
 # types-aiobotocore-cloudhsm
 
 [![PyPI - types-aiobotocore-cloudhsm](https://img.shields.io/pypi/v/types-aiobotocore-cloudhsm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudhsm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudhsm?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudhsm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudHSM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
+[aiobotocore.CloudHSM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsm.html#CloudHSM)
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
 [types-aiobotocore-cloudhsm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -328,101 +328,101 @@
 
 `types_aiobotocore_cloudhsm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudhsm.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AddTagsToResourceResponseTypeDef,
     CreateHapgRequestRequestTypeDef,
+    CreateHapgResponseTypeDef,
     CreateHsmRequestRequestTypeDef,
+    CreateHsmResponseTypeDef,
     CreateLunaClientRequestRequestTypeDef,
+    CreateLunaClientResponseTypeDef,
     DeleteHapgRequestRequestTypeDef,
+    DeleteHapgResponseTypeDef,
     DeleteHsmRequestRequestTypeDef,
+    DeleteHsmResponseTypeDef,
     DeleteLunaClientRequestRequestTypeDef,
+    DeleteLunaClientResponseTypeDef,
     DescribeHapgRequestRequestTypeDef,
+    DescribeHapgResponseTypeDef,
     DescribeHsmRequestRequestTypeDef,
+    DescribeHsmResponseTypeDef,
     DescribeLunaClientRequestRequestTypeDef,
+    DescribeLunaClientResponseTypeDef,
     GetConfigRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetConfigResponseTypeDef,
+    ListAvailableZonesResponseTypeDef,
+    ListHapgsRequestListHapgsPaginateTypeDef,
     ListHapgsRequestRequestTypeDef,
+    ListHapgsResponseTypeDef,
+    ListHsmsRequestListHsmsPaginateTypeDef,
     ListHsmsRequestRequestTypeDef,
+    ListHsmsResponseTypeDef,
+    ListLunaClientsRequestListLunaClientsPaginateTypeDef,
     ListLunaClientsRequestRequestTypeDef,
+    ListLunaClientsResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModifyHapgRequestRequestTypeDef,
+    ModifyHapgResponseTypeDef,
     ModifyHsmRequestRequestTypeDef,
+    ModifyHsmResponseTypeDef,
     ModifyLunaClientRequestRequestTypeDef,
+    ModifyLunaClientResponseTypeDef,
+    PaginatorConfigTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
+    RemoveTagsFromResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
-    AddTagsToResourceResponseTypeDef,
-    CreateHapgResponseTypeDef,
-    CreateHsmResponseTypeDef,
-    CreateLunaClientResponseTypeDef,
-    DeleteHapgResponseTypeDef,
-    DeleteHsmResponseTypeDef,
-    DeleteLunaClientResponseTypeDef,
-    DescribeHapgResponseTypeDef,
-    DescribeHsmResponseTypeDef,
-    DescribeLunaClientResponseTypeDef,
-    GetConfigResponseTypeDef,
-    ListAvailableZonesResponseTypeDef,
-    ListHapgsResponseTypeDef,
-    ListHsmsResponseTypeDef,
-    ListLunaClientsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    ModifyHapgResponseTypeDef,
-    ModifyHsmResponseTypeDef,
-    ModifyLunaClientResponseTypeDef,
-    RemoveTagsFromResourceResponseTypeDef,
-    ListHapgsRequestListHapgsPaginateTypeDef,
-    ListHsmsRequestListHsmsPaginateTypeDef,
-    ListLunaClientsRequestListLunaClientsPaginateTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
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

### Comparing `types-aiobotocore-cloudhsm-2.5.0.post1/types_aiobotocore_cloudhsm.egg-info/SOURCES.txt` & `types-aiobotocore-cloudhsm-2.5.1/types_aiobotocore_cloudhsm.egg-info/SOURCES.txt`

 * *Files identical despite different names*

