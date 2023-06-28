# Comparing `tmp/types-aiobotocore-sdb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sdb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sdb-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-sdb-2.5.1.tar", last modified: Wed Jun 28 01:44:09 2023, max compression
```

## Comparing `types-aiobotocore-sdb-2.5.0.post1.tar` & `types-aiobotocore-sdb-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.367608 types-aiobotocore-sdb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13573 2023-03-11 12:27:18.363608 types-aiobotocore-sdb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12013 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.367608 types-aiobotocore-sdb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2077 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.359608 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/
--rw-r--r--   0 runner    (1001) docker     (123)      754 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      753 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      926 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11703 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    11682 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7728 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7726 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3043 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3038 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8652 2023-03-11 12:23:41.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8633 2023-03-11 12:23:41.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:37.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.363608 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13573 2023-03-11 12:27:18.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:18.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:18.000000 types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.470212 types-aiobotocore-sdb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13561 2023-06-28 01:44:09.470212 types-aiobotocore-sdb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12007 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:09.470212 types-aiobotocore-sdb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2071 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.462211 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/
+-rw-r--r--   0 runner    (1001) docker     (123)      754 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      753 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      914 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11703 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11682 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7937 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7935 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2927 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2923 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8666 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8647 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:24.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.470212 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13561 2023-06-28 01:44:09.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:09.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:09.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:09.000000 types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sdb-2.5.0.post1/LICENSE` & `types-aiobotocore-sdb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sdb-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sdb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SimpleDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SimpleDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sdb"></a>
 
 # types-aiobotocore-sdb
 
 [![PyPI - types-aiobotocore-sdb](https://img.shields.io/pypi/v/types-aiobotocore-sdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sdb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sdb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sdb?color=blue)](https://pypistats.org/packages/types-aiobotocore-sdb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SimpleDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
+[aiobotocore.SimpleDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
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
 [types-aiobotocore-sdb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,29 +319,29 @@
 ```python
 from types_aiobotocore_sdb.type_defs import (
     AttributeTypeDef,
     CreateDomainRequestRequestTypeDef,
     UpdateConditionTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DomainMetadataRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DomainMetadataResultTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetAttributesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListDomainsResultTypeDef,
+    PaginatorConfigTypeDef,
     ReplaceableAttributeTypeDef,
+    ResponseMetadataTypeDef,
     SelectRequestRequestTypeDef,
+    SelectRequestSelectPaginateTypeDef,
     DeletableItemTypeDef,
+    GetAttributesResultTypeDef,
     ItemTypeDef,
     DeleteAttributesRequestRequestTypeDef,
-    DomainMetadataResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAttributesResultTypeDef,
-    ListDomainsResultTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    SelectRequestSelectPaginateTypeDef,
     PutAttributesRequestRequestTypeDef,
     ReplaceableItemTypeDef,
     BatchDeleteAttributesRequestRequestTypeDef,
     SelectResultTypeDef,
     BatchPutAttributesRequestRequestTypeDef,
 )
 
@@ -353,43 +353,43 @@
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/README.md` & `types-aiobotocore-sdb-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sdb"></a>
 
 # types-aiobotocore-sdb
 
 [![PyPI - types-aiobotocore-sdb](https://img.shields.io/pypi/v/types-aiobotocore-sdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sdb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sdb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sdb?color=blue)](https://pypistats.org/packages/types-aiobotocore-sdb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SimpleDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
+[aiobotocore.SimpleDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
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
 [types-aiobotocore-sdb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -286,29 +286,29 @@
 ```python
 from types_aiobotocore_sdb.type_defs import (
     AttributeTypeDef,
     CreateDomainRequestRequestTypeDef,
     UpdateConditionTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DomainMetadataRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DomainMetadataResultTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetAttributesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListDomainsResultTypeDef,
+    PaginatorConfigTypeDef,
     ReplaceableAttributeTypeDef,
+    ResponseMetadataTypeDef,
     SelectRequestRequestTypeDef,
+    SelectRequestSelectPaginateTypeDef,
     DeletableItemTypeDef,
+    GetAttributesResultTypeDef,
     ItemTypeDef,
     DeleteAttributesRequestRequestTypeDef,
-    DomainMetadataResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAttributesResultTypeDef,
-    ListDomainsResultTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    SelectRequestSelectPaginateTypeDef,
     PutAttributesRequestRequestTypeDef,
     ReplaceableItemTypeDef,
     BatchDeleteAttributesRequestRequestTypeDef,
     SelectResultTypeDef,
     BatchPutAttributesRequestRequestTypeDef,
 )
 
@@ -320,43 +320,43 @@
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/setup.py` & `types-aiobotocore-sdb-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sdb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sdb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sdb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SimpleDB 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SimpleDB 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/",
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/__init__.py` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/__init__.pyi` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/__main__.py` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SimpleDB 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SimpleDB 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB\nOther"
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/client.py` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/client.pyi` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/literals.py` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -91,14 +91,15 @@
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
@@ -177,14 +178,15 @@
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
@@ -195,14 +197,15 @@
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
@@ -238,14 +241,15 @@
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
@@ -264,16 +268,19 @@
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
@@ -357,15 +364,17 @@
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/literals.pyi` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -89,14 +89,15 @@
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
@@ -175,14 +176,15 @@
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
@@ -193,14 +195,15 @@
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
@@ -236,14 +239,15 @@
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
@@ -262,16 +266,19 @@
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
@@ -355,15 +362,17 @@
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/paginator.py` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/paginator.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -18,66 +18,55 @@
     with session.create_client("sdb") as client:
         client: SimpleDBClient
 
         list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
         select_paginator: SelectPaginator = client.get_paginator("select")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListDomainsResultTypeDef, PaginatorConfigTypeDef, SelectResultTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListDomainsPaginator", "SelectPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#listdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#listdomainspaginator)
         """
 
-
 class SelectPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.Select)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#selectpaginator)
     """
 
     def paginate(
         self,
         *,
         SelectExpression: str,
         ConsistentRead: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SelectResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.Select.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#selectpaginator)
         """
```

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/paginator.pyi` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/paginator.py`

 * *Files 15% similar despite different names*

```diff
@@ -18,61 +18,59 @@
     with session.create_client("sdb") as client:
         client: SimpleDBClient
 
         list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
         select_paginator: SelectPaginator = client.get_paginator("select")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListDomainsResultTypeDef, PaginatorConfigTypeDef, SelectResultTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListDomainsPaginator", "SelectPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#listdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#listdomainspaginator)
         """
 
+
 class SelectPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.Select)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#selectpaginator)
     """
 
     def paginate(
         self,
         *,
         SelectExpression: str,
         ConsistentRead: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SelectResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB.Paginator.Select.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/paginators/#selectpaginator)
         """
```

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/type_defs.py` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,29 +22,29 @@
 
 __all__ = (
     "AttributeTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "UpdateConditionTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DomainMetadataRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DomainMetadataResultTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetAttributesRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListDomainsResultTypeDef",
+    "PaginatorConfigTypeDef",
     "ReplaceableAttributeTypeDef",
+    "ResponseMetadataTypeDef",
     "SelectRequestRequestTypeDef",
+    "SelectRequestSelectPaginateTypeDef",
     "DeletableItemTypeDef",
+    "GetAttributesResultTypeDef",
     "ItemTypeDef",
     "DeleteAttributesRequestRequestTypeDef",
-    "DomainMetadataResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAttributesResultTypeDef",
-    "ListDomainsResultTypeDef",
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    "SelectRequestSelectPaginateTypeDef",
     "PutAttributesRequestRequestTypeDef",
     "ReplaceableItemTypeDef",
     "BatchDeleteAttributesRequestRequestTypeDef",
     "SelectResultTypeDef",
     "BatchPutAttributesRequestRequestTypeDef",
 )
 
@@ -96,22 +96,32 @@
 DomainMetadataRequestRequestTypeDef = TypedDict(
     "DomainMetadataRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DomainMetadataResultTypeDef = TypedDict(
+    "DomainMetadataResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ItemCount": int,
+        "ItemNamesSizeBytes": int,
+        "AttributeNameCount": int,
+        "AttributeNamesSizeBytes": int,
+        "AttributeValueCount": int,
+        "AttributeValuesSizeBytes": int,
+        "Timestamp": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredGetAttributesRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -130,33 +140,50 @@
 
 class GetAttributesRequestRequestTypeDef(
     _RequiredGetAttributesRequestRequestTypeDef, _OptionalGetAttributesRequestRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
         "MaxNumberOfDomains": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListDomainsResultTypeDef = TypedDict(
+    "ListDomainsResultTypeDef",
+    {
+        "DomainNames": List[str],
+        "NextToken": str,
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
 _RequiredReplaceableAttributeTypeDef = TypedDict(
     "_RequiredReplaceableAttributeTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
@@ -171,14 +198,25 @@
 
 class ReplaceableAttributeTypeDef(
     _RequiredReplaceableAttributeTypeDef, _OptionalReplaceableAttributeTypeDef
 ):
     pass
 
 
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
 _RequiredSelectRequestRequestTypeDef = TypedDict(
     "_RequiredSelectRequestRequestTypeDef",
     {
         "SelectExpression": str,
     },
 )
 _OptionalSelectRequestRequestTypeDef = TypedDict(
@@ -193,14 +231,36 @@
 
 class SelectRequestRequestTypeDef(
     _RequiredSelectRequestRequestTypeDef, _OptionalSelectRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredSelectRequestSelectPaginateTypeDef = TypedDict(
+    "_RequiredSelectRequestSelectPaginateTypeDef",
+    {
+        "SelectExpression": str,
+    },
+)
+_OptionalSelectRequestSelectPaginateTypeDef = TypedDict(
+    "_OptionalSelectRequestSelectPaginateTypeDef",
+    {
+        "ConsistentRead": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SelectRequestSelectPaginateTypeDef(
+    _RequiredSelectRequestSelectPaginateTypeDef, _OptionalSelectRequestSelectPaginateTypeDef
+):
+    pass
+
+
 _RequiredDeletableItemTypeDef = TypedDict(
     "_RequiredDeletableItemTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDeletableItemTypeDef = TypedDict(
@@ -212,14 +272,22 @@
 )
 
 
 class DeletableItemTypeDef(_RequiredDeletableItemTypeDef, _OptionalDeletableItemTypeDef):
     pass
 
 
+GetAttributesResultTypeDef = TypedDict(
+    "GetAttributesResultTypeDef",
+    {
+        "Attributes": List[AttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredItemTypeDef = TypedDict(
     "_RequiredItemTypeDef",
     {
         "Name": str,
         "Attributes": List[AttributeTypeDef],
     },
 )
@@ -255,82 +323,14 @@
 
 class DeleteAttributesRequestRequestTypeDef(
     _RequiredDeleteAttributesRequestRequestTypeDef, _OptionalDeleteAttributesRequestRequestTypeDef
 ):
     pass
 
 
-DomainMetadataResultTypeDef = TypedDict(
-    "DomainMetadataResultTypeDef",
-    {
-        "ItemCount": int,
-        "ItemNamesSizeBytes": int,
-        "AttributeNameCount": int,
-        "AttributeNamesSizeBytes": int,
-        "AttributeValueCount": int,
-        "AttributeValuesSizeBytes": int,
-        "Timestamp": int,
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
-GetAttributesResultTypeDef = TypedDict(
-    "GetAttributesResultTypeDef",
-    {
-        "Attributes": List[AttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainsResultTypeDef = TypedDict(
-    "ListDomainsResultTypeDef",
-    {
-        "DomainNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSelectRequestSelectPaginateTypeDef = TypedDict(
-    "_RequiredSelectRequestSelectPaginateTypeDef",
-    {
-        "SelectExpression": str,
-    },
-)
-_OptionalSelectRequestSelectPaginateTypeDef = TypedDict(
-    "_OptionalSelectRequestSelectPaginateTypeDef",
-    {
-        "ConsistentRead": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class SelectRequestSelectPaginateTypeDef(
-    _RequiredSelectRequestSelectPaginateTypeDef, _OptionalSelectRequestSelectPaginateTypeDef
-):
-    pass
-
-
 _RequiredPutAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutAttributesRequestRequestTypeDef",
     {
         "DomainName": str,
         "ItemName": str,
         "Attributes": Sequence[ReplaceableAttributeTypeDef],
     },
@@ -367,15 +367,15 @@
 )
 
 SelectResultTypeDef = TypedDict(
     "SelectResultTypeDef",
     {
         "Items": List[ItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutAttributesRequestRequestTypeDef = TypedDict(
     "BatchPutAttributesRequestRequestTypeDef",
     {
         "DomainName": str,
```

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb/type_defs.pyi` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -21,29 +21,29 @@
 
 __all__ = (
     "AttributeTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "UpdateConditionTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DomainMetadataRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DomainMetadataResultTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetAttributesRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListDomainsResultTypeDef",
+    "PaginatorConfigTypeDef",
     "ReplaceableAttributeTypeDef",
+    "ResponseMetadataTypeDef",
     "SelectRequestRequestTypeDef",
+    "SelectRequestSelectPaginateTypeDef",
     "DeletableItemTypeDef",
+    "GetAttributesResultTypeDef",
     "ItemTypeDef",
     "DeleteAttributesRequestRequestTypeDef",
-    "DomainMetadataResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAttributesResultTypeDef",
-    "ListDomainsResultTypeDef",
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    "SelectRequestSelectPaginateTypeDef",
     "PutAttributesRequestRequestTypeDef",
     "ReplaceableItemTypeDef",
     "BatchDeleteAttributesRequestRequestTypeDef",
     "SelectResultTypeDef",
     "BatchPutAttributesRequestRequestTypeDef",
 )
 
@@ -93,22 +93,32 @@
 DomainMetadataRequestRequestTypeDef = TypedDict(
     "DomainMetadataRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DomainMetadataResultTypeDef = TypedDict(
+    "DomainMetadataResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ItemCount": int,
+        "ItemNamesSizeBytes": int,
+        "AttributeNameCount": int,
+        "AttributeNamesSizeBytes": int,
+        "AttributeValueCount": int,
+        "AttributeValuesSizeBytes": int,
+        "Timestamp": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredGetAttributesRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -125,33 +135,50 @@
 )
 
 class GetAttributesRequestRequestTypeDef(
     _RequiredGetAttributesRequestRequestTypeDef, _OptionalGetAttributesRequestRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
+    "ListDomainsRequestListDomainsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDomainsRequestRequestTypeDef = TypedDict(
     "ListDomainsRequestRequestTypeDef",
     {
         "MaxNumberOfDomains": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListDomainsResultTypeDef = TypedDict(
+    "ListDomainsResultTypeDef",
+    {
+        "DomainNames": List[str],
+        "NextToken": str,
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
 _RequiredReplaceableAttributeTypeDef = TypedDict(
     "_RequiredReplaceableAttributeTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
@@ -164,14 +191,25 @@
 )
 
 class ReplaceableAttributeTypeDef(
     _RequiredReplaceableAttributeTypeDef, _OptionalReplaceableAttributeTypeDef
 ):
     pass
 
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
 _RequiredSelectRequestRequestTypeDef = TypedDict(
     "_RequiredSelectRequestRequestTypeDef",
     {
         "SelectExpression": str,
     },
 )
 _OptionalSelectRequestRequestTypeDef = TypedDict(
@@ -184,14 +222,34 @@
 )
 
 class SelectRequestRequestTypeDef(
     _RequiredSelectRequestRequestTypeDef, _OptionalSelectRequestRequestTypeDef
 ):
     pass
 
+_RequiredSelectRequestSelectPaginateTypeDef = TypedDict(
+    "_RequiredSelectRequestSelectPaginateTypeDef",
+    {
+        "SelectExpression": str,
+    },
+)
+_OptionalSelectRequestSelectPaginateTypeDef = TypedDict(
+    "_OptionalSelectRequestSelectPaginateTypeDef",
+    {
+        "ConsistentRead": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SelectRequestSelectPaginateTypeDef(
+    _RequiredSelectRequestSelectPaginateTypeDef, _OptionalSelectRequestSelectPaginateTypeDef
+):
+    pass
+
 _RequiredDeletableItemTypeDef = TypedDict(
     "_RequiredDeletableItemTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDeletableItemTypeDef = TypedDict(
@@ -201,14 +259,22 @@
     },
     total=False,
 )
 
 class DeletableItemTypeDef(_RequiredDeletableItemTypeDef, _OptionalDeletableItemTypeDef):
     pass
 
+GetAttributesResultTypeDef = TypedDict(
+    "GetAttributesResultTypeDef",
+    {
+        "Attributes": List[AttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredItemTypeDef = TypedDict(
     "_RequiredItemTypeDef",
     {
         "Name": str,
         "Attributes": List[AttributeTypeDef],
     },
 )
@@ -240,80 +306,14 @@
 )
 
 class DeleteAttributesRequestRequestTypeDef(
     _RequiredDeleteAttributesRequestRequestTypeDef, _OptionalDeleteAttributesRequestRequestTypeDef
 ):
     pass
 
-DomainMetadataResultTypeDef = TypedDict(
-    "DomainMetadataResultTypeDef",
-    {
-        "ItemCount": int,
-        "ItemNamesSizeBytes": int,
-        "AttributeNameCount": int,
-        "AttributeNamesSizeBytes": int,
-        "AttributeValueCount": int,
-        "AttributeValuesSizeBytes": int,
-        "Timestamp": int,
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
-GetAttributesResultTypeDef = TypedDict(
-    "GetAttributesResultTypeDef",
-    {
-        "Attributes": List[AttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainsResultTypeDef = TypedDict(
-    "ListDomainsResultTypeDef",
-    {
-        "DomainNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDomainsRequestListDomainsPaginateTypeDef = TypedDict(
-    "ListDomainsRequestListDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSelectRequestSelectPaginateTypeDef = TypedDict(
-    "_RequiredSelectRequestSelectPaginateTypeDef",
-    {
-        "SelectExpression": str,
-    },
-)
-_OptionalSelectRequestSelectPaginateTypeDef = TypedDict(
-    "_OptionalSelectRequestSelectPaginateTypeDef",
-    {
-        "ConsistentRead": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SelectRequestSelectPaginateTypeDef(
-    _RequiredSelectRequestSelectPaginateTypeDef, _OptionalSelectRequestSelectPaginateTypeDef
-):
-    pass
-
 _RequiredPutAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutAttributesRequestRequestTypeDef",
     {
         "DomainName": str,
         "ItemName": str,
         "Attributes": Sequence[ReplaceableAttributeTypeDef],
     },
@@ -348,15 +348,15 @@
 )
 
 SelectResultTypeDef = TypedDict(
     "SelectResultTypeDef",
     {
         "Items": List[ItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutAttributesRequestRequestTypeDef = TypedDict(
     "BatchPutAttributesRequestRequestTypeDef",
     {
         "DomainName": str,
```

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/PKG-INFO` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sdb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SimpleDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SimpleDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sdb"></a>
 
 # types-aiobotocore-sdb
 
 [![PyPI - types-aiobotocore-sdb](https://img.shields.io/pypi/v/types-aiobotocore-sdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sdb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sdb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sdb?color=blue)](https://pypistats.org/packages/types-aiobotocore-sdb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SimpleDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
+[aiobotocore.SimpleDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sdb.html#SimpleDB)
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
 [types-aiobotocore-sdb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sdb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,29 +319,29 @@
 ```python
 from types_aiobotocore_sdb.type_defs import (
     AttributeTypeDef,
     CreateDomainRequestRequestTypeDef,
     UpdateConditionTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DomainMetadataRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DomainMetadataResultTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetAttributesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDomainsRequestListDomainsPaginateTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListDomainsResultTypeDef,
+    PaginatorConfigTypeDef,
     ReplaceableAttributeTypeDef,
+    ResponseMetadataTypeDef,
     SelectRequestRequestTypeDef,
+    SelectRequestSelectPaginateTypeDef,
     DeletableItemTypeDef,
+    GetAttributesResultTypeDef,
     ItemTypeDef,
     DeleteAttributesRequestRequestTypeDef,
-    DomainMetadataResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAttributesResultTypeDef,
-    ListDomainsResultTypeDef,
-    ListDomainsRequestListDomainsPaginateTypeDef,
-    SelectRequestSelectPaginateTypeDef,
     PutAttributesRequestRequestTypeDef,
     ReplaceableItemTypeDef,
     BatchDeleteAttributesRequestRequestTypeDef,
     SelectResultTypeDef,
     BatchPutAttributesRequestRequestTypeDef,
 )
 
@@ -353,43 +353,43 @@
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

### Comparing `types-aiobotocore-sdb-2.5.0.post1/types_aiobotocore_sdb.egg-info/SOURCES.txt` & `types-aiobotocore-sdb-2.5.1/types_aiobotocore_sdb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

