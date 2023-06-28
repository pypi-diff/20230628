# Comparing `tmp/types-aiobotocore-connectcases-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-connectcases-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-connectcases-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-connectcases-2.5.1.tar", last modified: Wed Jun 28 01:43:20 2023, max compression
```

## Comparing `types-aiobotocore-connectcases-2.5.0.post1.tar` & `types-aiobotocore-connectcases-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.195097 types-aiobotocore-connectcases-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16554 2023-03-11 12:26:27.195097 types-aiobotocore-connectcases-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14963 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:27.195097 types-aiobotocore-connectcases-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:11:59.000000 types-aiobotocore-connectcases-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.171096 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/
--rw-r--r--   0 runner    (1001) docker     (123)      877 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      876 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23449 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23409 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8369 2023-03-11 12:12:01.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8367 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3722 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3717 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    29302 2023-03-11 12:12:01.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    29258 2023-03-11 12:12:01.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:00.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.195097 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16554 2023-03-11 12:26:27.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:27.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:27.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:27.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:27.000000 types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.234119 types-aiobotocore-connectcases-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16590 2023-06-28 01:43:20.234119 types-aiobotocore-connectcases-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15005 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:20.234119 types-aiobotocore-connectcases-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:28:38.000000 types-aiobotocore-connectcases-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.226119 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/
+-rw-r--r--   0 runner    (1001) docker     (123)      877 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      876 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23885 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23844 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8585 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8583 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3606 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3602 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    29522 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29478 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:39.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.234119 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16590 2023-06-28 01:43:20.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:20.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:20.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:20.000000 types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/LICENSE` & `types-aiobotocore-connectcases-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/PKG-INFO` & `types-aiobotocore-connectcases-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-connectcases
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectCases 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectCases 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-connectcases"></a>
 
 # types-aiobotocore-connectcases
 
 [![PyPI - types-aiobotocore-connectcases](https://img.shields.io/pypi/v/types-aiobotocore-connectcases.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcases)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectcases.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcases)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectcases?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectcases)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectCases 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases)
+[aiobotocore.ConnectCases 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases)
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
 [types-aiobotocore-connectcases docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,62 +331,63 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_connectcases.type_defs import (
     FieldIdentifierTypeDef,
     FieldErrorTypeDef,
     GetFieldResponseTypeDef,
-    ResponseMetadataTypeDef,
     FieldOptionTypeDef,
     FieldOptionErrorTypeDef,
     CaseSummaryTypeDef,
     CommentContentTypeDef,
     ContactContentTypeDef,
     ContactFilterTypeDef,
     ContactTypeDef,
+    CreateCaseResponseTypeDef,
     CreateDomainRequestRequestTypeDef,
+    CreateDomainResponseTypeDef,
     CreateFieldRequestRequestTypeDef,
+    CreateFieldResponseTypeDef,
+    CreateLayoutResponseTypeDef,
+    CreateRelatedItemResponseTypeDef,
     LayoutConfigurationTypeDef,
     RequiredFieldTypeDef,
+    CreateTemplateResponseTypeDef,
+    DeleteDomainRequestRequestTypeDef,
     DomainSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     RelatedItemEventIncludedDataTypeDef,
     FieldItemTypeDef,
     FieldSummaryTypeDef,
     FieldValueUnionTypeDef,
     GetCaseEventConfigurationRequestRequestTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetDomainResponseTypeDef,
     GetLayoutRequestRequestTypeDef,
     GetTemplateRequestRequestTypeDef,
     LayoutSummaryTypeDef,
     ListCasesForContactRequestRequestTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListFieldOptionsRequestRequestTypeDef,
     ListFieldsRequestRequestTypeDef,
     ListLayoutsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
     PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SortTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFieldRequestRequestTypeDef,
     BatchGetFieldRequestRequestTypeDef,
     CaseEventIncludedDataTypeDef,
     GetCaseRequestRequestTypeDef,
     BatchGetFieldResponseTypeDef,
-    CreateCaseResponseTypeDef,
-    CreateDomainResponseTypeDef,
-    CreateFieldResponseTypeDef,
-    CreateLayoutResponseTypeDef,
-    CreateRelatedItemResponseTypeDef,
-    CreateTemplateResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDomainResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchPutFieldOptionsRequestRequestTypeDef,
     ListFieldOptionsResponseTypeDef,
     BatchPutFieldOptionsResponseTypeDef,
     ListCasesForContactResponseTypeDef,
     RelatedItemContentTypeDef,
     RelatedItemTypeFilterTypeDef,
     RelatedItemInputContentTypeDef,
@@ -434,43 +435,43 @@
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/README.md` & `types-aiobotocore-connectcases-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-connectcases"></a>
 
 # types-aiobotocore-connectcases
 
 [![PyPI - types-aiobotocore-connectcases](https://img.shields.io/pypi/v/types-aiobotocore-connectcases.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcases)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectcases.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcases)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectcases?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectcases)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectCases 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases)
+[aiobotocore.ConnectCases 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases)
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
 [types-aiobotocore-connectcases docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,62 +298,63 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_connectcases.type_defs import (
     FieldIdentifierTypeDef,
     FieldErrorTypeDef,
     GetFieldResponseTypeDef,
-    ResponseMetadataTypeDef,
     FieldOptionTypeDef,
     FieldOptionErrorTypeDef,
     CaseSummaryTypeDef,
     CommentContentTypeDef,
     ContactContentTypeDef,
     ContactFilterTypeDef,
     ContactTypeDef,
+    CreateCaseResponseTypeDef,
     CreateDomainRequestRequestTypeDef,
+    CreateDomainResponseTypeDef,
     CreateFieldRequestRequestTypeDef,
+    CreateFieldResponseTypeDef,
+    CreateLayoutResponseTypeDef,
+    CreateRelatedItemResponseTypeDef,
     LayoutConfigurationTypeDef,
     RequiredFieldTypeDef,
+    CreateTemplateResponseTypeDef,
+    DeleteDomainRequestRequestTypeDef,
     DomainSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     RelatedItemEventIncludedDataTypeDef,
     FieldItemTypeDef,
     FieldSummaryTypeDef,
     FieldValueUnionTypeDef,
     GetCaseEventConfigurationRequestRequestTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetDomainResponseTypeDef,
     GetLayoutRequestRequestTypeDef,
     GetTemplateRequestRequestTypeDef,
     LayoutSummaryTypeDef,
     ListCasesForContactRequestRequestTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListFieldOptionsRequestRequestTypeDef,
     ListFieldsRequestRequestTypeDef,
     ListLayoutsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
     PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SortTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFieldRequestRequestTypeDef,
     BatchGetFieldRequestRequestTypeDef,
     CaseEventIncludedDataTypeDef,
     GetCaseRequestRequestTypeDef,
     BatchGetFieldResponseTypeDef,
-    CreateCaseResponseTypeDef,
-    CreateDomainResponseTypeDef,
-    CreateFieldResponseTypeDef,
-    CreateLayoutResponseTypeDef,
-    CreateRelatedItemResponseTypeDef,
-    CreateTemplateResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDomainResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchPutFieldOptionsRequestRequestTypeDef,
     ListFieldOptionsResponseTypeDef,
     BatchPutFieldOptionsResponseTypeDef,
     ListCasesForContactResponseTypeDef,
     RelatedItemContentTypeDef,
     RelatedItemTypeFilterTypeDef,
     RelatedItemInputContentTypeDef,
@@ -401,43 +402,43 @@
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/setup.py` & `types-aiobotocore-connectcases-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-connectcases.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-connectcases",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_connectcases"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ConnectCases 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ConnectCases 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/"
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/__init__.py` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/__init__.pyi` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/__main__.py` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ConnectCases 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ConnectCases 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases\nOther"
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/client.py` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -214,14 +214,22 @@
         """
         Creates a template in the Cases domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Client.create_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/client/#create_template)
         """
 
+    async def delete_domain(self, *, domainId: str) -> Dict[str, Any]:
+        """
+        Deletes a domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Client.delete_domain)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/client/#delete_domain)
+        """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/client.pyi` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -199,14 +199,21 @@
     ) -> CreateTemplateResponseTypeDef:
         """
         Creates a template in the Cases domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Client.create_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/client/#create_template)
         """
+    async def delete_domain(self, *, domainId: str) -> Dict[str, Any]:
+        """
+        Deletes a domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Client.delete_domain)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/client/#delete_domain)
+        """
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/literals.py` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -36,15 +36,15 @@
     "RegionName",
 )
 
 
 CommentBodyTextTypeType = Literal["Text/Plain"]
 DomainStatusType = Literal["Active", "CreationFailed", "CreationInProgress"]
 FieldNamespaceType = Literal["Custom", "System"]
-FieldTypeType = Literal["Boolean", "DateTime", "Number", "SingleSelect", "Text"]
+FieldTypeType = Literal["Boolean", "DateTime", "Number", "SingleSelect", "Text", "Url"]
 OrderType = Literal["Asc", "Desc"]
 RelatedItemTypeType = Literal["Comment", "Contact"]
 SearchCasesPaginatorName = Literal["search_cases"]
 SearchRelatedItemsPaginatorName = Literal["search_related_items"]
 TemplateStatusType = Literal["Active", "Inactive"]
 ConnectCasesServiceName = Literal["connectcases"]
 ServiceName = Literal[
@@ -105,14 +105,15 @@
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
@@ -191,14 +192,15 @@
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
@@ -209,14 +211,15 @@
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
@@ -252,14 +255,15 @@
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
@@ -278,16 +282,19 @@
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
@@ -371,15 +378,17 @@
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/literals.pyi` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,15 +34,15 @@
     "PaginatorName",
     "RegionName",
 )
 
 CommentBodyTextTypeType = Literal["Text/Plain"]
 DomainStatusType = Literal["Active", "CreationFailed", "CreationInProgress"]
 FieldNamespaceType = Literal["Custom", "System"]
-FieldTypeType = Literal["Boolean", "DateTime", "Number", "SingleSelect", "Text"]
+FieldTypeType = Literal["Boolean", "DateTime", "Number", "SingleSelect", "Text", "Url"]
 OrderType = Literal["Asc", "Desc"]
 RelatedItemTypeType = Literal["Comment", "Contact"]
 SearchCasesPaginatorName = Literal["search_cases"]
 SearchRelatedItemsPaginatorName = Literal["search_related_items"]
 TemplateStatusType = Literal["Active", "Inactive"]
 ConnectCasesServiceName = Literal["connectcases"]
 ServiceName = Literal[
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/paginator.py` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -18,82 +18,71 @@
     with session.create_client("connectcases") as client:
         client: ConnectCasesClient
 
         search_cases_paginator: SearchCasesPaginator = client.get_paginator("search_cases")
         search_related_items_paginator: SearchRelatedItemsPaginator = client.get_paginator("search_related_items")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     CaseFilterTypeDef,
     FieldIdentifierTypeDef,
     PaginatorConfigTypeDef,
     RelatedItemTypeFilterTypeDef,
     SearchCasesResponseTypeDef,
     SearchRelatedItemsResponseTypeDef,
     SortTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("SearchCasesPaginator", "SearchRelatedItemsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class SearchCasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchCases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchcasespaginator)
     """
 
     def paginate(
         self,
         *,
         domainId: str,
         fields: Sequence[FieldIdentifierTypeDef] = ...,
         filter: "CaseFilterTypeDef" = ...,
         searchTerm: str = ...,
         sorts: Sequence[SortTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchCasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchCases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchcasespaginator)
         """
 
-
 class SearchRelatedItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchRelatedItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchrelateditemspaginator)
     """
 
     def paginate(
         self,
         *,
         caseId: str,
         domainId: str,
         filters: Sequence[RelatedItemTypeFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchRelatedItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchRelatedItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchrelateditemspaginator)
         """
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/paginator.pyi` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/paginator.py`

 * *Files 9% similar despite different names*

```diff
@@ -18,77 +18,75 @@
     with session.create_client("connectcases") as client:
         client: ConnectCasesClient
 
         search_cases_paginator: SearchCasesPaginator = client.get_paginator("search_cases")
         search_related_items_paginator: SearchRelatedItemsPaginator = client.get_paginator("search_related_items")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     CaseFilterTypeDef,
     FieldIdentifierTypeDef,
     PaginatorConfigTypeDef,
     RelatedItemTypeFilterTypeDef,
     SearchCasesResponseTypeDef,
     SearchRelatedItemsResponseTypeDef,
     SortTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("SearchCasesPaginator", "SearchRelatedItemsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class SearchCasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchCases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchcasespaginator)
     """
 
     def paginate(
         self,
         *,
         domainId: str,
         fields: Sequence[FieldIdentifierTypeDef] = ...,
         filter: "CaseFilterTypeDef" = ...,
         searchTerm: str = ...,
         sorts: Sequence[SortTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchCasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchCases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchcasespaginator)
         """
 
+
 class SearchRelatedItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchRelatedItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchrelateditemspaginator)
     """
 
     def paginate(
         self,
         *,
         caseId: str,
         domainId: str,
         filters: Sequence[RelatedItemTypeFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchRelatedItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases.Paginator.SearchRelatedItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/paginators/#searchrelateditemspaginator)
         """
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/type_defs.py` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,62 +34,63 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "FieldIdentifierTypeDef",
     "FieldErrorTypeDef",
     "GetFieldResponseTypeDef",
-    "ResponseMetadataTypeDef",
     "FieldOptionTypeDef",
     "FieldOptionErrorTypeDef",
     "CaseSummaryTypeDef",
     "CommentContentTypeDef",
     "ContactContentTypeDef",
     "ContactFilterTypeDef",
     "ContactTypeDef",
+    "CreateCaseResponseTypeDef",
     "CreateDomainRequestRequestTypeDef",
+    "CreateDomainResponseTypeDef",
     "CreateFieldRequestRequestTypeDef",
+    "CreateFieldResponseTypeDef",
+    "CreateLayoutResponseTypeDef",
+    "CreateRelatedItemResponseTypeDef",
     "LayoutConfigurationTypeDef",
     "RequiredFieldTypeDef",
+    "CreateTemplateResponseTypeDef",
+    "DeleteDomainRequestRequestTypeDef",
     "DomainSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "RelatedItemEventIncludedDataTypeDef",
     "FieldItemTypeDef",
     "FieldSummaryTypeDef",
     "FieldValueUnionTypeDef",
     "GetCaseEventConfigurationRequestRequestTypeDef",
     "GetDomainRequestRequestTypeDef",
+    "GetDomainResponseTypeDef",
     "GetLayoutRequestRequestTypeDef",
     "GetTemplateRequestRequestTypeDef",
     "LayoutSummaryTypeDef",
     "ListCasesForContactRequestRequestTypeDef",
     "ListDomainsRequestRequestTypeDef",
     "ListFieldOptionsRequestRequestTypeDef",
     "ListFieldsRequestRequestTypeDef",
     "ListLayoutsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListTemplatesRequestRequestTypeDef",
     "TemplateSummaryTypeDef",
     "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SortTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFieldRequestRequestTypeDef",
     "BatchGetFieldRequestRequestTypeDef",
     "CaseEventIncludedDataTypeDef",
     "GetCaseRequestRequestTypeDef",
     "BatchGetFieldResponseTypeDef",
-    "CreateCaseResponseTypeDef",
-    "CreateDomainResponseTypeDef",
-    "CreateFieldResponseTypeDef",
-    "CreateLayoutResponseTypeDef",
-    "CreateRelatedItemResponseTypeDef",
-    "CreateTemplateResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetDomainResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "BatchPutFieldOptionsRequestRequestTypeDef",
     "ListFieldOptionsResponseTypeDef",
     "BatchPutFieldOptionsResponseTypeDef",
     "ListCasesForContactResponseTypeDef",
     "RelatedItemContentTypeDef",
     "RelatedItemTypeFilterTypeDef",
     "RelatedItemInputContentTypeDef",
@@ -176,25 +177,14 @@
 )
 
 
 class GetFieldResponseTypeDef(_RequiredGetFieldResponseTypeDef, _OptionalGetFieldResponseTypeDef):
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
 FieldOptionTypeDef = TypedDict(
     "FieldOptionTypeDef",
     {
         "active": bool,
         "name": str,
         "value": str,
     },
@@ -246,21 +236,40 @@
 ContactTypeDef = TypedDict(
     "ContactTypeDef",
     {
         "contactArn": str,
     },
 )
 
+CreateCaseResponseTypeDef = TypedDict(
+    "CreateCaseResponseTypeDef",
+    {
+        "caseArn": str,
+        "caseId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateDomainRequestRequestTypeDef = TypedDict(
     "CreateDomainRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+CreateDomainResponseTypeDef = TypedDict(
+    "CreateDomainResponseTypeDef",
+    {
+        "domainArn": str,
+        "domainId": str,
+        "domainStatus": DomainStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFieldRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFieldRequestRequestTypeDef",
     {
         "domainId": str,
         "name": str,
         "type": FieldTypeType,
     },
@@ -276,14 +285,41 @@
 
 class CreateFieldRequestRequestTypeDef(
     _RequiredCreateFieldRequestRequestTypeDef, _OptionalCreateFieldRequestRequestTypeDef
 ):
     pass
 
 
+CreateFieldResponseTypeDef = TypedDict(
+    "CreateFieldResponseTypeDef",
+    {
+        "fieldArn": str,
+        "fieldId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLayoutResponseTypeDef = TypedDict(
+    "CreateLayoutResponseTypeDef",
+    {
+        "layoutArn": str,
+        "layoutId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateRelatedItemResponseTypeDef = TypedDict(
+    "CreateRelatedItemResponseTypeDef",
+    {
+        "relatedItemArn": str,
+        "relatedItemId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LayoutConfigurationTypeDef = TypedDict(
     "LayoutConfigurationTypeDef",
     {
         "defaultLayout": str,
     },
     total=False,
 )
@@ -291,23 +327,46 @@
 RequiredFieldTypeDef = TypedDict(
     "RequiredFieldTypeDef",
     {
         "fieldId": str,
     },
 )
 
+CreateTemplateResponseTypeDef = TypedDict(
+    "CreateTemplateResponseTypeDef",
+    {
+        "templateArn": str,
+        "templateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteDomainRequestRequestTypeDef = TypedDict(
+    "DeleteDomainRequestRequestTypeDef",
+    {
+        "domainId": str,
+    },
+)
+
 DomainSummaryTypeDef = TypedDict(
     "DomainSummaryTypeDef",
     {
         "domainArn": str,
         "domainId": str,
         "name": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RelatedItemEventIncludedDataTypeDef = TypedDict(
     "RelatedItemEventIncludedDataTypeDef",
     {
         "includeContent": bool,
     },
 )
 
@@ -349,14 +408,27 @@
 GetDomainRequestRequestTypeDef = TypedDict(
     "GetDomainRequestRequestTypeDef",
     {
         "domainId": str,
     },
 )
 
+GetDomainResponseTypeDef = TypedDict(
+    "GetDomainResponseTypeDef",
+    {
+        "createdTime": datetime,
+        "domainArn": str,
+        "domainId": str,
+        "domainStatus": DomainStatusType,
+        "name": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLayoutRequestRequestTypeDef = TypedDict(
     "GetLayoutRequestRequestTypeDef",
     {
         "domainId": str,
         "layoutId": str,
     },
 )
@@ -482,14 +554,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "arn": str,
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
 _RequiredListTemplatesRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplatesRequestRequestTypeDef",
     {
         "domainId": str,
     },
 )
 _OptionalListTemplatesRequestRequestTypeDef = TypedDict(
@@ -525,14 +605,25 @@
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
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
 SortTypeDef = TypedDict(
     "SortTypeDef",
     {
         "fieldId": str,
         "sortOrder": OrderType,
     },
 )
@@ -615,98 +706,15 @@
 
 
 BatchGetFieldResponseTypeDef = TypedDict(
     "BatchGetFieldResponseTypeDef",
     {
         "errors": List[FieldErrorTypeDef],
         "fields": List[GetFieldResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCaseResponseTypeDef = TypedDict(
-    "CreateCaseResponseTypeDef",
-    {
-        "caseArn": str,
-        "caseId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDomainResponseTypeDef = TypedDict(
-    "CreateDomainResponseTypeDef",
-    {
-        "domainArn": str,
-        "domainId": str,
-        "domainStatus": DomainStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFieldResponseTypeDef = TypedDict(
-    "CreateFieldResponseTypeDef",
-    {
-        "fieldArn": str,
-        "fieldId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLayoutResponseTypeDef = TypedDict(
-    "CreateLayoutResponseTypeDef",
-    {
-        "layoutArn": str,
-        "layoutId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRelatedItemResponseTypeDef = TypedDict(
-    "CreateRelatedItemResponseTypeDef",
-    {
-        "relatedItemArn": str,
-        "relatedItemId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTemplateResponseTypeDef = TypedDict(
-    "CreateTemplateResponseTypeDef",
-    {
-        "templateArn": str,
-        "templateId": str,
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
-GetDomainResponseTypeDef = TypedDict(
-    "GetDomainResponseTypeDef",
-    {
-        "createdTime": datetime,
-        "domainArn": str,
-        "domainId": str,
-        "domainStatus": DomainStatusType,
-        "name": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutFieldOptionsRequestRequestTypeDef = TypedDict(
     "BatchPutFieldOptionsRequestRequestTypeDef",
     {
         "domainId": str,
@@ -716,32 +724,32 @@
 )
 
 ListFieldOptionsResponseTypeDef = TypedDict(
     "ListFieldOptionsResponseTypeDef",
     {
         "nextToken": str,
         "options": List[FieldOptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutFieldOptionsResponseTypeDef = TypedDict(
     "BatchPutFieldOptionsResponseTypeDef",
     {
         "errors": List[FieldOptionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCasesForContactResponseTypeDef = TypedDict(
     "ListCasesForContactResponseTypeDef",
     {
         "cases": List[CaseSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RelatedItemContentTypeDef = TypedDict(
     "RelatedItemContentTypeDef",
     {
         "comment": CommentContentTypeDef,
@@ -800,15 +808,15 @@
         "layoutConfiguration": LayoutConfigurationTypeDef,
         "name": str,
         "requiredFields": List[RequiredFieldTypeDef],
         "status": TemplateStatusType,
         "tags": Dict[str, str],
         "templateArn": str,
         "templateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTemplateRequestRequestTypeDef",
     {
         "domainId": str,
@@ -835,15 +843,15 @@
 
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "domains": List[DomainSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFieldGroupTypeDef = TypedDict(
     "_RequiredFieldGroupTypeDef",
     {
         "fields": Sequence[FieldItemTypeDef],
@@ -863,15 +871,15 @@
 
 
 ListFieldsResponseTypeDef = TypedDict(
     "ListFieldsResponseTypeDef",
     {
         "fields": List[FieldSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FieldValueTypeDef = TypedDict(
     "FieldValueTypeDef",
     {
         "id": str,
@@ -880,24 +888,24 @@
 )
 
 ListLayoutsResponseTypeDef = TypedDict(
     "ListLayoutsResponseTypeDef",
     {
         "layouts": List[LayoutSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplatesResponseTypeDef = TypedDict(
     "ListTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "templates": List[TemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchCasesRequestRequestTypeDef = TypedDict(
     "_RequiredSearchCasesRequestRequestTypeDef",
     {
         "domainId": str,
@@ -932,15 +940,15 @@
 _OptionalSearchCasesRequestSearchCasesPaginateTypeDef = TypedDict(
     "_OptionalSearchCasesRequestSearchCasesPaginateTypeDef",
     {
         "fields": Sequence[FieldIdentifierTypeDef],
         "filter": "CaseFilterTypeDef",
         "searchTerm": str,
         "sorts": Sequence[SortTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchCasesRequestSearchCasesPaginateTypeDef(
     _RequiredSearchCasesRequestSearchCasesPaginateTypeDef,
@@ -1014,15 +1022,15 @@
         "domainId": str,
     },
 )
 _OptionalSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef = TypedDict(
     "_OptionalSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef",
     {
         "filters": Sequence[RelatedItemTypeFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef(
     _RequiredSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef,
@@ -1088,15 +1096,15 @@
 GetCaseResponseTypeDef = TypedDict(
     "GetCaseResponseTypeDef",
     {
         "fields": List[FieldValueTypeDef],
         "nextToken": str,
         "tags": Dict[str, str],
         "templateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchCasesResponseItemTypeDef = TypedDict(
     "_RequiredSearchCasesResponseItemTypeDef",
     {
         "caseId": str,
@@ -1150,15 +1158,15 @@
 
 
 SearchRelatedItemsResponseTypeDef = TypedDict(
     "SearchRelatedItemsResponseTypeDef",
     {
         "nextToken": str,
         "relatedItems": List[SearchRelatedItemsResponseItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LayoutSectionsTypeDef = TypedDict(
     "LayoutSectionsTypeDef",
     {
         "sections": Sequence[SectionTypeDef],
@@ -1177,23 +1185,23 @@
 )
 
 SearchCasesResponseTypeDef = TypedDict(
     "SearchCasesResponseTypeDef",
     {
         "cases": List[SearchCasesResponseItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCaseEventConfigurationResponseTypeDef = TypedDict(
     "GetCaseEventConfigurationResponseTypeDef",
     {
         "eventBridge": EventBridgeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutCaseEventConfigurationRequestRequestTypeDef = TypedDict(
     "PutCaseEventConfigurationRequestRequestTypeDef",
     {
         "domainId": str,
@@ -1231,15 +1239,15 @@
     "GetLayoutResponseTypeDef",
     {
         "content": LayoutContentTypeDef,
         "layoutArn": str,
         "layoutId": str,
         "name": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateLayoutRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLayoutRequestRequestTypeDef",
     {
         "domainId": str,
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases/type_defs.pyi` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -33,62 +33,63 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "FieldIdentifierTypeDef",
     "FieldErrorTypeDef",
     "GetFieldResponseTypeDef",
-    "ResponseMetadataTypeDef",
     "FieldOptionTypeDef",
     "FieldOptionErrorTypeDef",
     "CaseSummaryTypeDef",
     "CommentContentTypeDef",
     "ContactContentTypeDef",
     "ContactFilterTypeDef",
     "ContactTypeDef",
+    "CreateCaseResponseTypeDef",
     "CreateDomainRequestRequestTypeDef",
+    "CreateDomainResponseTypeDef",
     "CreateFieldRequestRequestTypeDef",
+    "CreateFieldResponseTypeDef",
+    "CreateLayoutResponseTypeDef",
+    "CreateRelatedItemResponseTypeDef",
     "LayoutConfigurationTypeDef",
     "RequiredFieldTypeDef",
+    "CreateTemplateResponseTypeDef",
+    "DeleteDomainRequestRequestTypeDef",
     "DomainSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "RelatedItemEventIncludedDataTypeDef",
     "FieldItemTypeDef",
     "FieldSummaryTypeDef",
     "FieldValueUnionTypeDef",
     "GetCaseEventConfigurationRequestRequestTypeDef",
     "GetDomainRequestRequestTypeDef",
+    "GetDomainResponseTypeDef",
     "GetLayoutRequestRequestTypeDef",
     "GetTemplateRequestRequestTypeDef",
     "LayoutSummaryTypeDef",
     "ListCasesForContactRequestRequestTypeDef",
     "ListDomainsRequestRequestTypeDef",
     "ListFieldOptionsRequestRequestTypeDef",
     "ListFieldsRequestRequestTypeDef",
     "ListLayoutsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListTemplatesRequestRequestTypeDef",
     "TemplateSummaryTypeDef",
     "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SortTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFieldRequestRequestTypeDef",
     "BatchGetFieldRequestRequestTypeDef",
     "CaseEventIncludedDataTypeDef",
     "GetCaseRequestRequestTypeDef",
     "BatchGetFieldResponseTypeDef",
-    "CreateCaseResponseTypeDef",
-    "CreateDomainResponseTypeDef",
-    "CreateFieldResponseTypeDef",
-    "CreateLayoutResponseTypeDef",
-    "CreateRelatedItemResponseTypeDef",
-    "CreateTemplateResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetDomainResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "BatchPutFieldOptionsRequestRequestTypeDef",
     "ListFieldOptionsResponseTypeDef",
     "BatchPutFieldOptionsResponseTypeDef",
     "ListCasesForContactResponseTypeDef",
     "RelatedItemContentTypeDef",
     "RelatedItemTypeFilterTypeDef",
     "RelatedItemInputContentTypeDef",
@@ -171,25 +172,14 @@
     },
     total=False,
 )
 
 class GetFieldResponseTypeDef(_RequiredGetFieldResponseTypeDef, _OptionalGetFieldResponseTypeDef):
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
 FieldOptionTypeDef = TypedDict(
     "FieldOptionTypeDef",
     {
         "active": bool,
         "name": str,
         "value": str,
     },
@@ -241,21 +231,40 @@
 ContactTypeDef = TypedDict(
     "ContactTypeDef",
     {
         "contactArn": str,
     },
 )
 
+CreateCaseResponseTypeDef = TypedDict(
+    "CreateCaseResponseTypeDef",
+    {
+        "caseArn": str,
+        "caseId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateDomainRequestRequestTypeDef = TypedDict(
     "CreateDomainRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+CreateDomainResponseTypeDef = TypedDict(
+    "CreateDomainResponseTypeDef",
+    {
+        "domainArn": str,
+        "domainId": str,
+        "domainStatus": DomainStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFieldRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFieldRequestRequestTypeDef",
     {
         "domainId": str,
         "name": str,
         "type": FieldTypeType,
     },
@@ -269,14 +278,41 @@
 )
 
 class CreateFieldRequestRequestTypeDef(
     _RequiredCreateFieldRequestRequestTypeDef, _OptionalCreateFieldRequestRequestTypeDef
 ):
     pass
 
+CreateFieldResponseTypeDef = TypedDict(
+    "CreateFieldResponseTypeDef",
+    {
+        "fieldArn": str,
+        "fieldId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLayoutResponseTypeDef = TypedDict(
+    "CreateLayoutResponseTypeDef",
+    {
+        "layoutArn": str,
+        "layoutId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateRelatedItemResponseTypeDef = TypedDict(
+    "CreateRelatedItemResponseTypeDef",
+    {
+        "relatedItemArn": str,
+        "relatedItemId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LayoutConfigurationTypeDef = TypedDict(
     "LayoutConfigurationTypeDef",
     {
         "defaultLayout": str,
     },
     total=False,
 )
@@ -284,23 +320,46 @@
 RequiredFieldTypeDef = TypedDict(
     "RequiredFieldTypeDef",
     {
         "fieldId": str,
     },
 )
 
+CreateTemplateResponseTypeDef = TypedDict(
+    "CreateTemplateResponseTypeDef",
+    {
+        "templateArn": str,
+        "templateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteDomainRequestRequestTypeDef = TypedDict(
+    "DeleteDomainRequestRequestTypeDef",
+    {
+        "domainId": str,
+    },
+)
+
 DomainSummaryTypeDef = TypedDict(
     "DomainSummaryTypeDef",
     {
         "domainArn": str,
         "domainId": str,
         "name": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RelatedItemEventIncludedDataTypeDef = TypedDict(
     "RelatedItemEventIncludedDataTypeDef",
     {
         "includeContent": bool,
     },
 )
 
@@ -342,14 +401,27 @@
 GetDomainRequestRequestTypeDef = TypedDict(
     "GetDomainRequestRequestTypeDef",
     {
         "domainId": str,
     },
 )
 
+GetDomainResponseTypeDef = TypedDict(
+    "GetDomainResponseTypeDef",
+    {
+        "createdTime": datetime,
+        "domainArn": str,
+        "domainId": str,
+        "domainStatus": DomainStatusType,
+        "name": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLayoutRequestRequestTypeDef = TypedDict(
     "GetLayoutRequestRequestTypeDef",
     {
         "domainId": str,
         "layoutId": str,
     },
 )
@@ -467,14 +539,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "arn": str,
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
 _RequiredListTemplatesRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplatesRequestRequestTypeDef",
     {
         "domainId": str,
     },
 )
 _OptionalListTemplatesRequestRequestTypeDef = TypedDict(
@@ -508,14 +588,25 @@
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
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
 SortTypeDef = TypedDict(
     "SortTypeDef",
     {
         "fieldId": str,
         "sortOrder": OrderType,
     },
 )
@@ -594,98 +685,15 @@
     pass
 
 BatchGetFieldResponseTypeDef = TypedDict(
     "BatchGetFieldResponseTypeDef",
     {
         "errors": List[FieldErrorTypeDef],
         "fields": List[GetFieldResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCaseResponseTypeDef = TypedDict(
-    "CreateCaseResponseTypeDef",
-    {
-        "caseArn": str,
-        "caseId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDomainResponseTypeDef = TypedDict(
-    "CreateDomainResponseTypeDef",
-    {
-        "domainArn": str,
-        "domainId": str,
-        "domainStatus": DomainStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFieldResponseTypeDef = TypedDict(
-    "CreateFieldResponseTypeDef",
-    {
-        "fieldArn": str,
-        "fieldId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLayoutResponseTypeDef = TypedDict(
-    "CreateLayoutResponseTypeDef",
-    {
-        "layoutArn": str,
-        "layoutId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRelatedItemResponseTypeDef = TypedDict(
-    "CreateRelatedItemResponseTypeDef",
-    {
-        "relatedItemArn": str,
-        "relatedItemId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTemplateResponseTypeDef = TypedDict(
-    "CreateTemplateResponseTypeDef",
-    {
-        "templateArn": str,
-        "templateId": str,
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
-GetDomainResponseTypeDef = TypedDict(
-    "GetDomainResponseTypeDef",
-    {
-        "createdTime": datetime,
-        "domainArn": str,
-        "domainId": str,
-        "domainStatus": DomainStatusType,
-        "name": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutFieldOptionsRequestRequestTypeDef = TypedDict(
     "BatchPutFieldOptionsRequestRequestTypeDef",
     {
         "domainId": str,
@@ -695,32 +703,32 @@
 )
 
 ListFieldOptionsResponseTypeDef = TypedDict(
     "ListFieldOptionsResponseTypeDef",
     {
         "nextToken": str,
         "options": List[FieldOptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutFieldOptionsResponseTypeDef = TypedDict(
     "BatchPutFieldOptionsResponseTypeDef",
     {
         "errors": List[FieldOptionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCasesForContactResponseTypeDef = TypedDict(
     "ListCasesForContactResponseTypeDef",
     {
         "cases": List[CaseSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RelatedItemContentTypeDef = TypedDict(
     "RelatedItemContentTypeDef",
     {
         "comment": CommentContentTypeDef,
@@ -777,15 +785,15 @@
         "layoutConfiguration": LayoutConfigurationTypeDef,
         "name": str,
         "requiredFields": List[RequiredFieldTypeDef],
         "status": TemplateStatusType,
         "tags": Dict[str, str],
         "templateArn": str,
         "templateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTemplateRequestRequestTypeDef",
     {
         "domainId": str,
@@ -810,15 +818,15 @@
     pass
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "domains": List[DomainSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFieldGroupTypeDef = TypedDict(
     "_RequiredFieldGroupTypeDef",
     {
         "fields": Sequence[FieldItemTypeDef],
@@ -836,15 +844,15 @@
     pass
 
 ListFieldsResponseTypeDef = TypedDict(
     "ListFieldsResponseTypeDef",
     {
         "fields": List[FieldSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FieldValueTypeDef = TypedDict(
     "FieldValueTypeDef",
     {
         "id": str,
@@ -853,24 +861,24 @@
 )
 
 ListLayoutsResponseTypeDef = TypedDict(
     "ListLayoutsResponseTypeDef",
     {
         "layouts": List[LayoutSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplatesResponseTypeDef = TypedDict(
     "ListTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "templates": List[TemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchCasesRequestRequestTypeDef = TypedDict(
     "_RequiredSearchCasesRequestRequestTypeDef",
     {
         "domainId": str,
@@ -903,15 +911,15 @@
 _OptionalSearchCasesRequestSearchCasesPaginateTypeDef = TypedDict(
     "_OptionalSearchCasesRequestSearchCasesPaginateTypeDef",
     {
         "fields": Sequence[FieldIdentifierTypeDef],
         "filter": "CaseFilterTypeDef",
         "searchTerm": str,
         "sorts": Sequence[SortTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchCasesRequestSearchCasesPaginateTypeDef(
     _RequiredSearchCasesRequestSearchCasesPaginateTypeDef,
     _OptionalSearchCasesRequestSearchCasesPaginateTypeDef,
@@ -979,15 +987,15 @@
         "domainId": str,
     },
 )
 _OptionalSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef = TypedDict(
     "_OptionalSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef",
     {
         "filters": Sequence[RelatedItemTypeFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef(
     _RequiredSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef,
     _OptionalSearchRelatedItemsRequestSearchRelatedItemsPaginateTypeDef,
@@ -1049,15 +1057,15 @@
 GetCaseResponseTypeDef = TypedDict(
     "GetCaseResponseTypeDef",
     {
         "fields": List[FieldValueTypeDef],
         "nextToken": str,
         "tags": Dict[str, str],
         "templateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchCasesResponseItemTypeDef = TypedDict(
     "_RequiredSearchCasesResponseItemTypeDef",
     {
         "caseId": str,
@@ -1107,15 +1115,15 @@
     pass
 
 SearchRelatedItemsResponseTypeDef = TypedDict(
     "SearchRelatedItemsResponseTypeDef",
     {
         "nextToken": str,
         "relatedItems": List[SearchRelatedItemsResponseItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LayoutSectionsTypeDef = TypedDict(
     "LayoutSectionsTypeDef",
     {
         "sections": Sequence[SectionTypeDef],
@@ -1134,23 +1142,23 @@
 )
 
 SearchCasesResponseTypeDef = TypedDict(
     "SearchCasesResponseTypeDef",
     {
         "cases": List[SearchCasesResponseItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCaseEventConfigurationResponseTypeDef = TypedDict(
     "GetCaseEventConfigurationResponseTypeDef",
     {
         "eventBridge": EventBridgeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutCaseEventConfigurationRequestRequestTypeDef = TypedDict(
     "PutCaseEventConfigurationRequestRequestTypeDef",
     {
         "domainId": str,
@@ -1188,15 +1196,15 @@
     "GetLayoutResponseTypeDef",
     {
         "content": LayoutContentTypeDef,
         "layoutArn": str,
         "layoutId": str,
         "name": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateLayoutRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLayoutRequestRequestTypeDef",
     {
         "domainId": str,
```

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/PKG-INFO` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-connectcases
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectCases 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectCases 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-connectcases"></a>
 
 # types-aiobotocore-connectcases
 
 [![PyPI - types-aiobotocore-connectcases](https://img.shields.io/pypi/v/types-aiobotocore-connectcases.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcases)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectcases.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcases)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectcases?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectcases)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectCases 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases)
+[aiobotocore.ConnectCases 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcases.html#ConnectCases)
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
 [types-aiobotocore-connectcases docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcases/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,62 +331,63 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_connectcases.type_defs import (
     FieldIdentifierTypeDef,
     FieldErrorTypeDef,
     GetFieldResponseTypeDef,
-    ResponseMetadataTypeDef,
     FieldOptionTypeDef,
     FieldOptionErrorTypeDef,
     CaseSummaryTypeDef,
     CommentContentTypeDef,
     ContactContentTypeDef,
     ContactFilterTypeDef,
     ContactTypeDef,
+    CreateCaseResponseTypeDef,
     CreateDomainRequestRequestTypeDef,
+    CreateDomainResponseTypeDef,
     CreateFieldRequestRequestTypeDef,
+    CreateFieldResponseTypeDef,
+    CreateLayoutResponseTypeDef,
+    CreateRelatedItemResponseTypeDef,
     LayoutConfigurationTypeDef,
     RequiredFieldTypeDef,
+    CreateTemplateResponseTypeDef,
+    DeleteDomainRequestRequestTypeDef,
     DomainSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     RelatedItemEventIncludedDataTypeDef,
     FieldItemTypeDef,
     FieldSummaryTypeDef,
     FieldValueUnionTypeDef,
     GetCaseEventConfigurationRequestRequestTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetDomainResponseTypeDef,
     GetLayoutRequestRequestTypeDef,
     GetTemplateRequestRequestTypeDef,
     LayoutSummaryTypeDef,
     ListCasesForContactRequestRequestTypeDef,
     ListDomainsRequestRequestTypeDef,
     ListFieldOptionsRequestRequestTypeDef,
     ListFieldsRequestRequestTypeDef,
     ListLayoutsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
     PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SortTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFieldRequestRequestTypeDef,
     BatchGetFieldRequestRequestTypeDef,
     CaseEventIncludedDataTypeDef,
     GetCaseRequestRequestTypeDef,
     BatchGetFieldResponseTypeDef,
-    CreateCaseResponseTypeDef,
-    CreateDomainResponseTypeDef,
-    CreateFieldResponseTypeDef,
-    CreateLayoutResponseTypeDef,
-    CreateRelatedItemResponseTypeDef,
-    CreateTemplateResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDomainResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchPutFieldOptionsRequestRequestTypeDef,
     ListFieldOptionsResponseTypeDef,
     BatchPutFieldOptionsResponseTypeDef,
     ListCasesForContactResponseTypeDef,
     RelatedItemContentTypeDef,
     RelatedItemTypeFilterTypeDef,
     RelatedItemInputContentTypeDef,
@@ -434,43 +435,43 @@
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

### Comparing `types-aiobotocore-connectcases-2.5.0.post1/types_aiobotocore_connectcases.egg-info/SOURCES.txt` & `types-aiobotocore-connectcases-2.5.1/types_aiobotocore_connectcases.egg-info/SOURCES.txt`

 * *Files identical despite different names*

