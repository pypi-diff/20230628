# Comparing `tmp/types-aiobotocore-macie-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-macie-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-macie-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-macie-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-macie-2.5.0.post1.tar` & `types-aiobotocore-macie-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.563395 types-aiobotocore-macie-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13953 2023-03-11 12:26:56.563395 types-aiobotocore-macie-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12390 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.563395 types-aiobotocore-macie-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.563395 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/
--rw-r--r--   0 runner    (1001) docker     (123)      847 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      846 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9616 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9598 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7886 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7884 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3211 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3206 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8367 2023-03-11 12:18:00.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8354 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:59.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.563395 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13953 2023-03-11 12:26:56.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-03-11 12:26:56.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:26:56.000000 types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.590170 types-aiobotocore-macie-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13943 2023-06-28 01:43:47.586171 types-aiobotocore-macie-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12386 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.590170 types-aiobotocore-macie-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.586171 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/
+-rw-r--r--   0 runner    (1001) docker     (123)      847 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      846 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9616 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9598 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8095 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8093 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3095 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3091 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8383 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8370 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:41.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.586171 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13943 2023-06-28 01:43:47.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 01:43:47.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:47.000000 types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-macie-2.5.0.post1/LICENSE` & `types-aiobotocore-macie-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-macie-2.5.0.post1/PKG-INFO` & `types-aiobotocore-macie-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-macie
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Macie 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Macie 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-macie"></a>
 
 # types-aiobotocore-macie
 
 [![PyPI - types-aiobotocore-macie](https://img.shields.io/pypi/v/types-aiobotocore-macie.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-macie.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-macie?color=blue)](https://pypistats.org/packages/types-aiobotocore-macie)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Macie 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
+[aiobotocore.Macie 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
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
 [types-aiobotocore-macie docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,30 +321,30 @@
 
 `types_aiobotocore_macie.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_macie.type_defs import (
     AssociateMemberAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ClassificationTypeTypeDef,
     ClassificationTypeUpdateTypeDef,
     DisassociateMemberAccountRequestRequestTypeDef,
     S3ResourceTypeDef,
-    PaginatorConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
     ListMemberAccountsRequestRequestTypeDef,
     MemberAccountTypeDef,
+    ListS3ResourcesRequestListS3ResourcesPaginateTypeDef,
     ListS3ResourcesRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3ResourceClassificationTypeDef,
     S3ResourceClassificationUpdateTypeDef,
     DisassociateS3ResourcesRequestRequestTypeDef,
     FailedS3ResourceTypeDef,
-    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
-    ListS3ResourcesRequestListS3ResourcesPaginateTypeDef,
     ListMemberAccountsResultTypeDef,
     AssociateS3ResourcesRequestRequestTypeDef,
     ListS3ResourcesResultTypeDef,
     UpdateS3ResourcesRequestRequestTypeDef,
     AssociateS3ResourcesResultTypeDef,
     DisassociateS3ResourcesResultTypeDef,
     UpdateS3ResourcesResultTypeDef,
@@ -358,43 +358,43 @@
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

### Comparing `types-aiobotocore-macie-2.5.0.post1/README.md` & `types-aiobotocore-macie-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-macie"></a>
 
 # types-aiobotocore-macie
 
 [![PyPI - types-aiobotocore-macie](https://img.shields.io/pypi/v/types-aiobotocore-macie.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-macie.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-macie?color=blue)](https://pypistats.org/packages/types-aiobotocore-macie)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Macie 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
+[aiobotocore.Macie 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
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
 [types-aiobotocore-macie docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/).
 
 See how it helps to find and fix potential bugs:
 
@@ -288,30 +288,30 @@
 
 `types_aiobotocore_macie.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_macie.type_defs import (
     AssociateMemberAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ClassificationTypeTypeDef,
     ClassificationTypeUpdateTypeDef,
     DisassociateMemberAccountRequestRequestTypeDef,
     S3ResourceTypeDef,
-    PaginatorConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
     ListMemberAccountsRequestRequestTypeDef,
     MemberAccountTypeDef,
+    ListS3ResourcesRequestListS3ResourcesPaginateTypeDef,
     ListS3ResourcesRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3ResourceClassificationTypeDef,
     S3ResourceClassificationUpdateTypeDef,
     DisassociateS3ResourcesRequestRequestTypeDef,
     FailedS3ResourceTypeDef,
-    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
-    ListS3ResourcesRequestListS3ResourcesPaginateTypeDef,
     ListMemberAccountsResultTypeDef,
     AssociateS3ResourcesRequestRequestTypeDef,
     ListS3ResourcesResultTypeDef,
     UpdateS3ResourcesRequestRequestTypeDef,
     AssociateS3ResourcesResultTypeDef,
     DisassociateS3ResourcesResultTypeDef,
     UpdateS3ResourcesResultTypeDef,
@@ -325,43 +325,43 @@
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

### Comparing `types-aiobotocore-macie-2.5.0.post1/setup.py` & `types-aiobotocore-macie-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-macie.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-macie",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_macie"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Macie 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Macie 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/"
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

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/__init__.py` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/__init__.pyi` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/__main__.py` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Macie 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Macie 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie\nOther"
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

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/client.py` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/client.pyi` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/literals.py` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/literals.py`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/literals.pyi` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/literals.pyi`

 * *Files 0% similar despite different names*

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

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/paginator.py` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/paginator.py`

 * *Files 16% similar despite different names*

```diff
@@ -18,32 +18,25 @@
     with session.create_client("macie") as client:
         client: MacieClient
 
         list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator("list_member_accounts")
         list_s3_resources_paginator: ListS3ResourcesPaginator = client.get_paginator("list_s3_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListMemberAccountsResultTypeDef,
     ListS3ResourcesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListMemberAccountsPaginator", "ListS3ResourcesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,28 +49,28 @@
 class ListMemberAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListMemberAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#listmemberaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMemberAccountsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListMemberAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#listmemberaccountspaginator)
         """
 
 
 class ListS3ResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListS3Resources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#lists3resourcespaginator)
     """
 
     def paginate(
-        self, *, memberAccountId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, memberAccountId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListS3ResourcesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListS3Resources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#lists3resourcespaginator)
         """
```

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/paginator.pyi` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/paginator.pyi`

 * *Files 22% similar despite different names*

```diff
@@ -18,31 +18,25 @@
     with session.create_client("macie") as client:
         client: MacieClient
 
         list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator("list_member_accounts")
         list_s3_resources_paginator: ListS3ResourcesPaginator = client.get_paginator("list_s3_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListMemberAccountsResultTypeDef,
     ListS3ResourcesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListMemberAccountsPaginator", "ListS3ResourcesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,27 +46,27 @@
 class ListMemberAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListMemberAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#listmemberaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMemberAccountsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListMemberAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#listmemberaccountspaginator)
         """
 
 class ListS3ResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListS3Resources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#lists3resourcespaginator)
     """
 
     def paginate(
-        self, *, memberAccountId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, memberAccountId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListS3ResourcesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie.Paginator.ListS3Resources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/paginators/#lists3resourcespaginator)
         """
```

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/type_defs.py` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,30 +24,30 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateMemberAccountRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ClassificationTypeTypeDef",
     "ClassificationTypeUpdateTypeDef",
     "DisassociateMemberAccountRequestRequestTypeDef",
     "S3ResourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
     "ListMemberAccountsRequestRequestTypeDef",
     "MemberAccountTypeDef",
+    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
     "ListS3ResourcesRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3ResourceClassificationTypeDef",
     "S3ResourceClassificationUpdateTypeDef",
     "DisassociateS3ResourcesRequestRequestTypeDef",
     "FailedS3ResourceTypeDef",
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
     "ListMemberAccountsResultTypeDef",
     "AssociateS3ResourcesRequestRequestTypeDef",
     "ListS3ResourcesResultTypeDef",
     "UpdateS3ResourcesRequestRequestTypeDef",
     "AssociateS3ResourcesResultTypeDef",
     "DisassociateS3ResourcesResultTypeDef",
     "UpdateS3ResourcesResultTypeDef",
@@ -56,25 +56,14 @@
 AssociateMemberAccountRequestRequestTypeDef = TypedDict(
     "AssociateMemberAccountRequestRequestTypeDef",
     {
         "memberAccountId": str,
     },
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
 ClassificationTypeTypeDef = TypedDict(
     "ClassificationTypeTypeDef",
     {
         "oneTime": S3OneTimeClassificationTypeType,
         "continuous": Literal["FULL"],
     },
 )
@@ -110,20 +99,25 @@
 )
 
 
 class S3ResourceTypeDef(_RequiredS3ResourceTypeDef, _OptionalS3ResourceTypeDef):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListMemberAccountsRequestRequestTypeDef = TypedDict(
     "ListMemberAccountsRequestRequestTypeDef",
     {
@@ -137,28 +131,51 @@
     "MemberAccountTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+ListS3ResourcesRequestListS3ResourcesPaginateTypeDef = TypedDict(
+    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
+    {
+        "memberAccountId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListS3ResourcesRequestRequestTypeDef = TypedDict(
     "ListS3ResourcesRequestRequestTypeDef",
     {
         "memberAccountId": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
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
     },
 )
 
 _RequiredS3ResourceClassificationTypeDef = TypedDict(
     "_RequiredS3ResourceClassificationTypeDef",
     {
         "bucketName": str,
@@ -230,37 +247,20 @@
         "failedItem": S3ResourceTypeDef,
         "errorCode": str,
         "errorMessage": str,
     },
     total=False,
 )
 
-ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListS3ResourcesRequestListS3ResourcesPaginateTypeDef = TypedDict(
-    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
-    {
-        "memberAccountId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListMemberAccountsResultTypeDef = TypedDict(
     "ListMemberAccountsResultTypeDef",
     {
         "memberAccounts": List[MemberAccountTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateS3ResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateS3ResourcesRequestRequestTypeDef",
     {
         "s3Resources": Sequence[S3ResourceClassificationTypeDef],
@@ -283,15 +283,15 @@
 
 
 ListS3ResourcesResultTypeDef = TypedDict(
     "ListS3ResourcesResultTypeDef",
     {
         "s3Resources": List[S3ResourceClassificationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateS3ResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateS3ResourcesRequestRequestTypeDef",
     {
         "s3ResourcesUpdate": Sequence[S3ResourceClassificationUpdateTypeDef],
@@ -312,26 +312,26 @@
     pass
 
 
 AssociateS3ResourcesResultTypeDef = TypedDict(
     "AssociateS3ResourcesResultTypeDef",
     {
         "failedS3Resources": List[FailedS3ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateS3ResourcesResultTypeDef = TypedDict(
     "DisassociateS3ResourcesResultTypeDef",
     {
         "failedS3Resources": List[FailedS3ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateS3ResourcesResultTypeDef = TypedDict(
     "UpdateS3ResourcesResultTypeDef",
     {
         "failedS3Resources": List[FailedS3ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie/type_defs.pyi` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -23,30 +23,30 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateMemberAccountRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ClassificationTypeTypeDef",
     "ClassificationTypeUpdateTypeDef",
     "DisassociateMemberAccountRequestRequestTypeDef",
     "S3ResourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
     "ListMemberAccountsRequestRequestTypeDef",
     "MemberAccountTypeDef",
+    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
     "ListS3ResourcesRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3ResourceClassificationTypeDef",
     "S3ResourceClassificationUpdateTypeDef",
     "DisassociateS3ResourcesRequestRequestTypeDef",
     "FailedS3ResourceTypeDef",
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
     "ListMemberAccountsResultTypeDef",
     "AssociateS3ResourcesRequestRequestTypeDef",
     "ListS3ResourcesResultTypeDef",
     "UpdateS3ResourcesRequestRequestTypeDef",
     "AssociateS3ResourcesResultTypeDef",
     "DisassociateS3ResourcesResultTypeDef",
     "UpdateS3ResourcesResultTypeDef",
@@ -55,25 +55,14 @@
 AssociateMemberAccountRequestRequestTypeDef = TypedDict(
     "AssociateMemberAccountRequestRequestTypeDef",
     {
         "memberAccountId": str,
     },
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
 ClassificationTypeTypeDef = TypedDict(
     "ClassificationTypeTypeDef",
     {
         "oneTime": S3OneTimeClassificationTypeType,
         "continuous": Literal["FULL"],
     },
 )
@@ -107,20 +96,25 @@
     },
     total=False,
 )
 
 class S3ResourceTypeDef(_RequiredS3ResourceTypeDef, _OptionalS3ResourceTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListMemberAccountsRequestRequestTypeDef = TypedDict(
     "ListMemberAccountsRequestRequestTypeDef",
     {
@@ -134,28 +128,51 @@
     "MemberAccountTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+ListS3ResourcesRequestListS3ResourcesPaginateTypeDef = TypedDict(
+    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
+    {
+        "memberAccountId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListS3ResourcesRequestRequestTypeDef = TypedDict(
     "ListS3ResourcesRequestRequestTypeDef",
     {
         "memberAccountId": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
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
     },
 )
 
 _RequiredS3ResourceClassificationTypeDef = TypedDict(
     "_RequiredS3ResourceClassificationTypeDef",
     {
         "bucketName": str,
@@ -221,37 +238,20 @@
         "failedItem": S3ResourceTypeDef,
         "errorCode": str,
         "errorMessage": str,
     },
     total=False,
 )
 
-ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListS3ResourcesRequestListS3ResourcesPaginateTypeDef = TypedDict(
-    "ListS3ResourcesRequestListS3ResourcesPaginateTypeDef",
-    {
-        "memberAccountId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListMemberAccountsResultTypeDef = TypedDict(
     "ListMemberAccountsResultTypeDef",
     {
         "memberAccounts": List[MemberAccountTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateS3ResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateS3ResourcesRequestRequestTypeDef",
     {
         "s3Resources": Sequence[S3ResourceClassificationTypeDef],
@@ -272,15 +272,15 @@
     pass
 
 ListS3ResourcesResultTypeDef = TypedDict(
     "ListS3ResourcesResultTypeDef",
     {
         "s3Resources": List[S3ResourceClassificationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateS3ResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateS3ResourcesRequestRequestTypeDef",
     {
         "s3ResourcesUpdate": Sequence[S3ResourceClassificationUpdateTypeDef],
@@ -299,26 +299,26 @@
 ):
     pass
 
 AssociateS3ResourcesResultTypeDef = TypedDict(
     "AssociateS3ResourcesResultTypeDef",
     {
         "failedS3Resources": List[FailedS3ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateS3ResourcesResultTypeDef = TypedDict(
     "DisassociateS3ResourcesResultTypeDef",
     {
         "failedS3Resources": List[FailedS3ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateS3ResourcesResultTypeDef = TypedDict(
     "UpdateS3ResourcesResultTypeDef",
     {
         "failedS3Resources": List[FailedS3ResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/PKG-INFO` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-macie
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Macie 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Macie 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-macie"></a>
 
 # types-aiobotocore-macie
 
 [![PyPI - types-aiobotocore-macie](https://img.shields.io/pypi/v/types-aiobotocore-macie.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-macie.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-macie?color=blue)](https://pypistats.org/packages/types-aiobotocore-macie)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Macie 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
+[aiobotocore.Macie 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie.html#Macie)
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
 [types-aiobotocore-macie docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,30 +321,30 @@
 
 `types_aiobotocore_macie.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_macie.type_defs import (
     AssociateMemberAccountRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ClassificationTypeTypeDef,
     ClassificationTypeUpdateTypeDef,
     DisassociateMemberAccountRequestRequestTypeDef,
     S3ResourceTypeDef,
-    PaginatorConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
     ListMemberAccountsRequestRequestTypeDef,
     MemberAccountTypeDef,
+    ListS3ResourcesRequestListS3ResourcesPaginateTypeDef,
     ListS3ResourcesRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3ResourceClassificationTypeDef,
     S3ResourceClassificationUpdateTypeDef,
     DisassociateS3ResourcesRequestRequestTypeDef,
     FailedS3ResourceTypeDef,
-    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
-    ListS3ResourcesRequestListS3ResourcesPaginateTypeDef,
     ListMemberAccountsResultTypeDef,
     AssociateS3ResourcesRequestRequestTypeDef,
     ListS3ResourcesResultTypeDef,
     UpdateS3ResourcesRequestRequestTypeDef,
     AssociateS3ResourcesResultTypeDef,
     DisassociateS3ResourcesResultTypeDef,
     UpdateS3ResourcesResultTypeDef,
@@ -358,43 +358,43 @@
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

### Comparing `types-aiobotocore-macie-2.5.0.post1/types_aiobotocore_macie.egg-info/SOURCES.txt` & `types-aiobotocore-macie-2.5.1/types_aiobotocore_macie.egg-info/SOURCES.txt`

 * *Files identical despite different names*

