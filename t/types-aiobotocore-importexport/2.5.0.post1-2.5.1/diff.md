# Comparing `tmp/types-aiobotocore-importexport-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-importexport-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-importexport-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-importexport-2.5.1.tar", last modified: Wed Jun 28 01:43:35 2023, max compression
```

## Comparing `types-aiobotocore-importexport-2.5.0.post1.tar` & `types-aiobotocore-importexport-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.251272 types-aiobotocore-importexport-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13538 2023-03-11 12:26:44.251272 types-aiobotocore-importexport-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11947 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.251272 types-aiobotocore-importexport-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.247272 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/
--rw-r--r--   0 runner    (1001) docker     (123)      651 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      650 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9826 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9810 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7519 2023-03-11 12:15:51.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7517 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2107 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6597 2023-03-11 12:15:51.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6586 2023-03-11 12:15:51.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:50.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.251272 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13538 2023-03-11 12:26:44.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:44.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:44.000000 types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.974149 types-aiobotocore-importexport-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13535 2023-06-28 01:43:35.966149 types-aiobotocore-importexport-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11950 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:35.974149 types-aiobotocore-importexport-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.966149 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/
+-rw-r--r--   0 runner    (1001) docker     (123)      651 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      650 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9826 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9810 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7728 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7726 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1993 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1990 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6611 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6600 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:27.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:35.966149 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13535 2023-06-28 01:43:35.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:35.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:35.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:35.000000 types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-importexport-2.5.0.post1/LICENSE` & `types-aiobotocore-importexport-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/PKG-INFO` & `types-aiobotocore-importexport-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-importexport
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ImportExport 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ImportExport 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-importexport"></a>
 
 # types-aiobotocore-importexport
 
 [![PyPI - types-aiobotocore-importexport](https://img.shields.io/pypi/v/types-aiobotocore-importexport.svg?color=blue)](https://pypi.org/project/types-aiobotocore-importexport)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-importexport.svg?color=blue)](https://pypi.org/project/types-aiobotocore-importexport)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-importexport?color=blue)](https://pypistats.org/packages/types-aiobotocore-importexport)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ImportExport 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport)
+[aiobotocore.ImportExport 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport)
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
 [types-aiobotocore-importexport docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/).
 
 See how it helps to find and fix potential bugs:
 
@@ -316,72 +316,72 @@
 `types_aiobotocore_importexport.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_importexport.type_defs import (
     ArtifactTypeDef,
     CancelJobInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobOutputTypeDef,
     CreateJobInputRequestTypeDef,
     GetShippingLabelInputRequestTypeDef,
+    GetShippingLabelOutputTypeDef,
     GetStatusInputRequestTypeDef,
     JobTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsInputListJobsPaginateTypeDef,
     ListJobsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateJobInputRequestTypeDef,
-    CancelJobOutputTypeDef,
     CreateJobOutputTypeDef,
-    GetShippingLabelOutputTypeDef,
     GetStatusOutputTypeDef,
     UpdateJobOutputTypeDef,
     ListJobsOutputTypeDef,
-    ListJobsInputListJobsPaginateTypeDef,
 )
 
 
 def get_structure() -> ArtifactTypeDef:
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/README.md` & `types-aiobotocore-importexport-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-importexport"></a>
 
 # types-aiobotocore-importexport
 
 [![PyPI - types-aiobotocore-importexport](https://img.shields.io/pypi/v/types-aiobotocore-importexport.svg?color=blue)](https://pypi.org/project/types-aiobotocore-importexport)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-importexport.svg?color=blue)](https://pypi.org/project/types-aiobotocore-importexport)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-importexport?color=blue)](https://pypistats.org/packages/types-aiobotocore-importexport)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ImportExport 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport)
+[aiobotocore.ImportExport 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport)
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
 [types-aiobotocore-importexport docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/).
 
 See how it helps to find and fix potential bugs:
 
@@ -283,72 +283,72 @@
 `types_aiobotocore_importexport.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_importexport.type_defs import (
     ArtifactTypeDef,
     CancelJobInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobOutputTypeDef,
     CreateJobInputRequestTypeDef,
     GetShippingLabelInputRequestTypeDef,
+    GetShippingLabelOutputTypeDef,
     GetStatusInputRequestTypeDef,
     JobTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsInputListJobsPaginateTypeDef,
     ListJobsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateJobInputRequestTypeDef,
-    CancelJobOutputTypeDef,
     CreateJobOutputTypeDef,
-    GetShippingLabelOutputTypeDef,
     GetStatusOutputTypeDef,
     UpdateJobOutputTypeDef,
     ListJobsOutputTypeDef,
-    ListJobsInputListJobsPaginateTypeDef,
 )
 
 
 def get_structure() -> ArtifactTypeDef:
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/setup.py` & `types-aiobotocore-importexport-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-importexport.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-importexport",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_importexport"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ImportExport 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ImportExport 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/"
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/__init__.py` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/__init__.pyi` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/__main__.py` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ImportExport 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ImportExport 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport\nOther"
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/client.py` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/client.pyi` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/literals.py` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -90,14 +90,15 @@
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
@@ -176,14 +177,15 @@
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
@@ -194,14 +196,15 @@
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
@@ -237,14 +240,15 @@
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
@@ -263,16 +267,19 @@
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
@@ -356,15 +363,17 @@
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/literals.pyi` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -88,14 +88,15 @@
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
@@ -174,14 +175,15 @@
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
@@ -192,14 +194,15 @@
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
@@ -235,14 +238,15 @@
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
@@ -261,16 +265,19 @@
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
@@ -354,15 +361,17 @@
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/paginator.py` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("importexport") as client:
         client: ImportExportClient
 
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListJobsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListJobsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/paginators/#listjobspaginator)
     """
 
     def paginate(
-        self, *, APIVersion: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, APIVersion: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/paginators/#listjobspaginator)
         """
```

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/paginator.pyi` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("importexport") as client:
         client: ImportExportClient
 
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListJobsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListJobsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/paginators/#listjobspaginator)
     """
 
     def paginate(
-        self, *, APIVersion: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, APIVersion: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/paginators/#listjobspaginator)
         """
```

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/type_defs.py` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -18,33 +18,32 @@
 from .literals import JobTypeType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ArtifactTypeDef",
     "CancelJobInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobOutputTypeDef",
     "CreateJobInputRequestTypeDef",
     "GetShippingLabelInputRequestTypeDef",
+    "GetShippingLabelOutputTypeDef",
     "GetStatusInputRequestTypeDef",
     "JobTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobsInputListJobsPaginateTypeDef",
     "ListJobsInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateJobInputRequestTypeDef",
-    "CancelJobOutputTypeDef",
     "CreateJobOutputTypeDef",
-    "GetShippingLabelOutputTypeDef",
     "GetStatusOutputTypeDef",
     "UpdateJobOutputTypeDef",
     "ListJobsOutputTypeDef",
-    "ListJobsInputListJobsPaginateTypeDef",
 )
 
 ArtifactTypeDef = TypedDict(
     "ArtifactTypeDef",
     {
         "Description": str,
         "URL": str,
@@ -62,29 +61,24 @@
     "_OptionalCancelJobInputRequestTypeDef",
     {
         "APIVersion": str,
     },
     total=False,
 )
 
-
 class CancelJobInputRequestTypeDef(
     _RequiredCancelJobInputRequestTypeDef, _OptionalCancelJobInputRequestTypeDef
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJobOutputTypeDef = TypedDict(
+    "CancelJobOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Success": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobInputRequestTypeDef = TypedDict(
     "_RequiredCreateJobInputRequestTypeDef",
     {
         "JobType": JobTypeType,
@@ -97,21 +91,19 @@
     {
         "ManifestAddendum": str,
         "APIVersion": str,
     },
     total=False,
 )
 
-
 class CreateJobInputRequestTypeDef(
     _RequiredCreateJobInputRequestTypeDef, _OptionalCreateJobInputRequestTypeDef
 ):
     pass
 
-
 _RequiredGetShippingLabelInputRequestTypeDef = TypedDict(
     "_RequiredGetShippingLabelInputRequestTypeDef",
     {
         "jobIds": Sequence[str],
     },
 )
 _OptionalGetShippingLabelInputRequestTypeDef = TypedDict(
@@ -128,20 +120,27 @@
         "street2": str,
         "street3": str,
         "APIVersion": str,
     },
     total=False,
 )
 
-
 class GetShippingLabelInputRequestTypeDef(
     _RequiredGetShippingLabelInputRequestTypeDef, _OptionalGetShippingLabelInputRequestTypeDef
 ):
     pass
 
+GetShippingLabelOutputTypeDef = TypedDict(
+    "GetShippingLabelOutputTypeDef",
+    {
+        "ShippingLabelURL": str,
+        "Warning": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetStatusInputRequestTypeDef = TypedDict(
     "_RequiredGetStatusInputRequestTypeDef",
     {
         "JobId": str,
     },
 )
@@ -149,52 +148,70 @@
     "_OptionalGetStatusInputRequestTypeDef",
     {
         "APIVersion": str,
     },
     total=False,
 )
 
-
 class GetStatusInputRequestTypeDef(
     _RequiredGetStatusInputRequestTypeDef, _OptionalGetStatusInputRequestTypeDef
 ):
     pass
 
-
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "JobId": str,
         "CreationDate": datetime,
         "IsCanceled": bool,
         "JobType": JobTypeType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListJobsInputListJobsPaginateTypeDef = TypedDict(
+    "ListJobsInputListJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "APIVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListJobsInputRequestTypeDef = TypedDict(
     "ListJobsInputRequestTypeDef",
     {
         "MaxJobs": int,
         "Marker": str,
         "APIVersion": str,
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
 _RequiredUpdateJobInputRequestTypeDef = TypedDict(
     "_RequiredUpdateJobInputRequestTypeDef",
     {
         "JobId": str,
         "Manifest": str,
         "JobType": JobTypeType,
         "ValidateOnly": bool,
@@ -204,48 +221,29 @@
     "_OptionalUpdateJobInputRequestTypeDef",
     {
         "APIVersion": str,
     },
     total=False,
 )
 
-
 class UpdateJobInputRequestTypeDef(
     _RequiredUpdateJobInputRequestTypeDef, _OptionalUpdateJobInputRequestTypeDef
 ):
     pass
 
-
-CancelJobOutputTypeDef = TypedDict(
-    "CancelJobOutputTypeDef",
-    {
-        "Success": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateJobOutputTypeDef = TypedDict(
     "CreateJobOutputTypeDef",
     {
         "JobId": str,
         "JobType": JobTypeType,
         "Signature": str,
         "SignatureFileContents": str,
         "WarningMessage": str,
         "ArtifactList": List[ArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetShippingLabelOutputTypeDef = TypedDict(
-    "GetShippingLabelOutputTypeDef",
-    {
-        "ShippingLabelURL": str,
-        "Warning": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStatusOutputTypeDef = TypedDict(
     "GetStatusOutputTypeDef",
     {
         "JobId": str,
@@ -260,38 +258,29 @@
         "LogKey": str,
         "ErrorCount": int,
         "Signature": str,
         "SignatureFileContents": str,
         "CurrentManifest": str,
         "CreationDate": datetime,
         "ArtifactList": List[ArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobOutputTypeDef = TypedDict(
     "UpdateJobOutputTypeDef",
     {
         "Success": bool,
         "WarningMessage": str,
         "ArtifactList": List[ArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsOutputTypeDef = TypedDict(
     "ListJobsOutputTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "IsTruncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-
-ListJobsInputListJobsPaginateTypeDef = TypedDict(
-    "ListJobsInputListJobsPaginateTypeDef",
-    {
-        "APIVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
```

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport/type_defs.pyi` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,32 +18,33 @@
 from .literals import JobTypeType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ArtifactTypeDef",
     "CancelJobInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobOutputTypeDef",
     "CreateJobInputRequestTypeDef",
     "GetShippingLabelInputRequestTypeDef",
+    "GetShippingLabelOutputTypeDef",
     "GetStatusInputRequestTypeDef",
     "JobTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobsInputListJobsPaginateTypeDef",
     "ListJobsInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateJobInputRequestTypeDef",
-    "CancelJobOutputTypeDef",
     "CreateJobOutputTypeDef",
-    "GetShippingLabelOutputTypeDef",
     "GetStatusOutputTypeDef",
     "UpdateJobOutputTypeDef",
     "ListJobsOutputTypeDef",
-    "ListJobsInputListJobsPaginateTypeDef",
 )
 
 ArtifactTypeDef = TypedDict(
     "ArtifactTypeDef",
     {
         "Description": str,
         "URL": str,
@@ -61,27 +62,26 @@
     "_OptionalCancelJobInputRequestTypeDef",
     {
         "APIVersion": str,
     },
     total=False,
 )
 
+
 class CancelJobInputRequestTypeDef(
     _RequiredCancelJobInputRequestTypeDef, _OptionalCancelJobInputRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+CancelJobOutputTypeDef = TypedDict(
+    "CancelJobOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Success": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobInputRequestTypeDef = TypedDict(
     "_RequiredCreateJobInputRequestTypeDef",
     {
         "JobType": JobTypeType,
@@ -94,19 +94,21 @@
     {
         "ManifestAddendum": str,
         "APIVersion": str,
     },
     total=False,
 )
 
+
 class CreateJobInputRequestTypeDef(
     _RequiredCreateJobInputRequestTypeDef, _OptionalCreateJobInputRequestTypeDef
 ):
     pass
 
+
 _RequiredGetShippingLabelInputRequestTypeDef = TypedDict(
     "_RequiredGetShippingLabelInputRequestTypeDef",
     {
         "jobIds": Sequence[str],
     },
 )
 _OptionalGetShippingLabelInputRequestTypeDef = TypedDict(
@@ -123,69 +125,102 @@
         "street2": str,
         "street3": str,
         "APIVersion": str,
     },
     total=False,
 )
 
+
 class GetShippingLabelInputRequestTypeDef(
     _RequiredGetShippingLabelInputRequestTypeDef, _OptionalGetShippingLabelInputRequestTypeDef
 ):
     pass
 
+
+GetShippingLabelOutputTypeDef = TypedDict(
+    "GetShippingLabelOutputTypeDef",
+    {
+        "ShippingLabelURL": str,
+        "Warning": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetStatusInputRequestTypeDef = TypedDict(
     "_RequiredGetStatusInputRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalGetStatusInputRequestTypeDef = TypedDict(
     "_OptionalGetStatusInputRequestTypeDef",
     {
         "APIVersion": str,
     },
     total=False,
 )
 
+
 class GetStatusInputRequestTypeDef(
     _RequiredGetStatusInputRequestTypeDef, _OptionalGetStatusInputRequestTypeDef
 ):
     pass
 
+
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "JobId": str,
         "CreationDate": datetime,
         "IsCanceled": bool,
         "JobType": JobTypeType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListJobsInputListJobsPaginateTypeDef = TypedDict(
+    "ListJobsInputListJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "APIVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListJobsInputRequestTypeDef = TypedDict(
     "ListJobsInputRequestTypeDef",
     {
         "MaxJobs": int,
         "Marker": str,
         "APIVersion": str,
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
 _RequiredUpdateJobInputRequestTypeDef = TypedDict(
     "_RequiredUpdateJobInputRequestTypeDef",
     {
         "JobId": str,
         "Manifest": str,
         "JobType": JobTypeType,
         "ValidateOnly": bool,
@@ -195,46 +230,31 @@
     "_OptionalUpdateJobInputRequestTypeDef",
     {
         "APIVersion": str,
     },
     total=False,
 )
 
+
 class UpdateJobInputRequestTypeDef(
     _RequiredUpdateJobInputRequestTypeDef, _OptionalUpdateJobInputRequestTypeDef
 ):
     pass
 
-CancelJobOutputTypeDef = TypedDict(
-    "CancelJobOutputTypeDef",
-    {
-        "Success": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 CreateJobOutputTypeDef = TypedDict(
     "CreateJobOutputTypeDef",
     {
         "JobId": str,
         "JobType": JobTypeType,
         "Signature": str,
         "SignatureFileContents": str,
         "WarningMessage": str,
         "ArtifactList": List[ArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetShippingLabelOutputTypeDef = TypedDict(
-    "GetShippingLabelOutputTypeDef",
-    {
-        "ShippingLabelURL": str,
-        "Warning": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStatusOutputTypeDef = TypedDict(
     "GetStatusOutputTypeDef",
     {
         "JobId": str,
@@ -249,38 +269,29 @@
         "LogKey": str,
         "ErrorCount": int,
         "Signature": str,
         "SignatureFileContents": str,
         "CurrentManifest": str,
         "CreationDate": datetime,
         "ArtifactList": List[ArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobOutputTypeDef = TypedDict(
     "UpdateJobOutputTypeDef",
     {
         "Success": bool,
         "WarningMessage": str,
         "ArtifactList": List[ArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsOutputTypeDef = TypedDict(
     "ListJobsOutputTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "IsTruncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-
-ListJobsInputListJobsPaginateTypeDef = TypedDict(
-    "ListJobsInputListJobsPaginateTypeDef",
-    {
-        "APIVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
```

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/PKG-INFO` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-importexport
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ImportExport 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ImportExport 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-importexport"></a>
 
 # types-aiobotocore-importexport
 
 [![PyPI - types-aiobotocore-importexport](https://img.shields.io/pypi/v/types-aiobotocore-importexport.svg?color=blue)](https://pypi.org/project/types-aiobotocore-importexport)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-importexport.svg?color=blue)](https://pypi.org/project/types-aiobotocore-importexport)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-importexport?color=blue)](https://pypistats.org/packages/types-aiobotocore-importexport)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ImportExport 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport)
+[aiobotocore.ImportExport 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/importexport.html#ImportExport)
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
 [types-aiobotocore-importexport docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_importexport/).
 
 See how it helps to find and fix potential bugs:
 
@@ -316,72 +316,72 @@
 `types_aiobotocore_importexport.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_importexport.type_defs import (
     ArtifactTypeDef,
     CancelJobInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobOutputTypeDef,
     CreateJobInputRequestTypeDef,
     GetShippingLabelInputRequestTypeDef,
+    GetShippingLabelOutputTypeDef,
     GetStatusInputRequestTypeDef,
     JobTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsInputListJobsPaginateTypeDef,
     ListJobsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateJobInputRequestTypeDef,
-    CancelJobOutputTypeDef,
     CreateJobOutputTypeDef,
-    GetShippingLabelOutputTypeDef,
     GetStatusOutputTypeDef,
     UpdateJobOutputTypeDef,
     ListJobsOutputTypeDef,
-    ListJobsInputListJobsPaginateTypeDef,
 )
 
 
 def get_structure() -> ArtifactTypeDef:
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

### Comparing `types-aiobotocore-importexport-2.5.0.post1/types_aiobotocore_importexport.egg-info/SOURCES.txt` & `types-aiobotocore-importexport-2.5.1/types_aiobotocore_importexport.egg-info/SOURCES.txt`

 * *Files identical despite different names*

