# Comparing `tmp/types-aiobotocore-account-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-account-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-account-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-account-2.5.1.tar", last modified: Wed Jun 28 01:43:01 2023, max compression
```

## Comparing `types-aiobotocore-account-2.5.0.post1.tar` & `types-aiobotocore-account-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.798904 types-aiobotocore-account-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12763 2023-03-11 12:26:07.790904 types-aiobotocore-account-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11192 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:07.798904 types-aiobotocore-account-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.782904 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/
--rw-r--r--   0 runner    (1001) docker     (123)      442 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      441 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9697 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9680 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7554 2023-03-11 12:09:04.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7552 2023-03-11 12:09:04.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     7834 2023-03-11 12:09:04.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7817 2023-03-11 12:09:04.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:03.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.790904 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12763 2023-03-11 12:26:07.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      734 2023-03-11 12:26:07.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:07.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:07.000000 types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.698085 types-aiobotocore-account-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13581 2023-06-28 01:43:01.694085 types-aiobotocore-account-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12016 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:01.698085 types-aiobotocore-account-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.690085 types-aiobotocore-account-2.5.1/types_aiobotocore_account/
+-rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      628 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10281 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10262 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7907 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7905 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2108 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8382 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8365 2023-06-28 01:25:41.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:40.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.694085 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13581 2023-06-28 01:43:01.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:43:01.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:01.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:01.000000 types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-account-2.5.0.post1/LICENSE` & `types-aiobotocore-account-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-account-2.5.0.post1/PKG-INFO` & `types-aiobotocore-account-2.5.1/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-account
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Account 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Account 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-account"></a>
 
 # types-aiobotocore-account
 
 [![PyPI - types-aiobotocore-account](https://img.shields.io/pypi/v/types-aiobotocore-account.svg?color=blue)](https://pypi.org/project/types-aiobotocore-account)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-account.svg?color=blue)](https://pypi.org/project/types-aiobotocore-account)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-account?color=blue)](https://pypistats.org/packages/types-aiobotocore-account)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Account 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account)
+[aiobotocore.Account 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account)
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
 [types-aiobotocore-account docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/).
 
 See how it helps to find and fix potential bugs:
 
@@ -72,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -259,28 +260,52 @@
 
 session = get_session()
 async with session.create_client("account") as client:
     client: AccountClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_account.paginator` module contains type annotations for all
+paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_account import AccountClient
+from types_aiobotocore_account.paginator import ListRegionsPaginator
+
+session = get_session()
+async with session.create_client("account") as client:
+    client: AccountClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_regions_paginator: ListRegionsPaginator = client.get_paginator("list_regions")
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_account.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_account.literals import (
     AlternateContactTypeType,
+    ListRegionsPaginatorName,
     RegionOptStatusType,
     AccountServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
 )
 
 
 def check_value(value: AlternateContactTypeType) -> bool:
     ...
 ```
 
@@ -298,22 +323,24 @@
     DeleteAlternateContactRequestRequestTypeDef,
     DisableRegionRequestRequestTypeDef,
     ResponseMetadataTypeDef,
     EnableRegionRequestRequestTypeDef,
     GetAlternateContactRequestRequestTypeDef,
     GetContactInformationRequestRequestTypeDef,
     GetRegionOptStatusRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ListRegionsRequestRequestTypeDef,
     RegionTypeDef,
     PutAlternateContactRequestRequestTypeDef,
     PutContactInformationRequestRequestTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAlternateContactResponseTypeDef,
     GetContactInformationResponseTypeDef,
     GetRegionOptStatusResponseTypeDef,
+    ListRegionsRequestListRegionsPaginateTypeDef,
     ListRegionsResponseTypeDef,
 )
 
 
 def get_structure() -> AlternateContactTypeDef:
     return {...}
 ```
@@ -321,43 +348,43 @@
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

### Comparing `types-aiobotocore-account-2.5.0.post1/README.md` & `types-aiobotocore-account-2.5.1/README.md`

 * *Files 9% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-account"></a>
 
 # types-aiobotocore-account
 
 [![PyPI - types-aiobotocore-account](https://img.shields.io/pypi/v/types-aiobotocore-account.svg?color=blue)](https://pypi.org/project/types-aiobotocore-account)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-account.svg?color=blue)](https://pypi.org/project/types-aiobotocore-account)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-account?color=blue)](https://pypistats.org/packages/types-aiobotocore-account)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Account 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account)
+[aiobotocore.Account 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account)
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
 [types-aiobotocore-account docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/).
 
 See how it helps to find and fix potential bugs:
 
@@ -39,14 +39,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -226,28 +227,52 @@
 
 session = get_session()
 async with session.create_client("account") as client:
     client: AccountClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_account.paginator` module contains type annotations for all
+paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_account import AccountClient
+from types_aiobotocore_account.paginator import ListRegionsPaginator
+
+session = get_session()
+async with session.create_client("account") as client:
+    client: AccountClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_regions_paginator: ListRegionsPaginator = client.get_paginator("list_regions")
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_account.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_account.literals import (
     AlternateContactTypeType,
+    ListRegionsPaginatorName,
     RegionOptStatusType,
     AccountServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
 )
 
 
 def check_value(value: AlternateContactTypeType) -> bool:
     ...
 ```
 
@@ -265,22 +290,24 @@
     DeleteAlternateContactRequestRequestTypeDef,
     DisableRegionRequestRequestTypeDef,
     ResponseMetadataTypeDef,
     EnableRegionRequestRequestTypeDef,
     GetAlternateContactRequestRequestTypeDef,
     GetContactInformationRequestRequestTypeDef,
     GetRegionOptStatusRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ListRegionsRequestRequestTypeDef,
     RegionTypeDef,
     PutAlternateContactRequestRequestTypeDef,
     PutContactInformationRequestRequestTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAlternateContactResponseTypeDef,
     GetContactInformationResponseTypeDef,
     GetRegionOptStatusResponseTypeDef,
+    ListRegionsRequestListRegionsPaginateTypeDef,
     ListRegionsResponseTypeDef,
 )
 
 
 def get_structure() -> AlternateContactTypeDef:
     return {...}
 ```
@@ -288,43 +315,43 @@
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

### Comparing `types-aiobotocore-account-2.5.0.post1/setup.py` & `types-aiobotocore-account-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-account.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-account",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_account"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Account 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Account 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/"
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

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/__main__.py` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Account 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Account 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account\nOther"
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

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/client.py` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,29 +10,37 @@
     from types_aiobotocore_account.client import AccountClient
 
     session = get_session()
     async with session.create_client("account") as client:
         client: AccountClient
     ```
 """
+import sys
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import AlternateContactTypeType, RegionOptStatusType
+from .paginator import ListRegionsPaginator
 from .type_defs import (
     ContactInformationTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAlternateContactResponseTypeDef,
     GetContactInformationResponseTypeDef,
     GetRegionOptStatusResponseTypeDef,
     ListRegionsResponseTypeDef,
 )
 
+if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+
+
 __all__ = ("AccountClient",)
 
 
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
@@ -197,14 +205,20 @@
         """
         Updates the primary contact information of an Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account.Client.put_contact_information)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/client/#put_contact_information)
         """
 
+    def get_paginator(self, operation_name: Literal["list_regions"]) -> ListRegionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "AccountClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/client/)
         """
 
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
```

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/client.pyi` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -10,29 +10,36 @@
     from types_aiobotocore_account.client import AccountClient
 
     session = get_session()
     async with session.create_client("account") as client:
         client: AccountClient
     ```
 """
+import sys
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import AlternateContactTypeType, RegionOptStatusType
+from .paginator import ListRegionsPaginator
 from .type_defs import (
     ContactInformationTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAlternateContactResponseTypeDef,
     GetContactInformationResponseTypeDef,
     GetRegionOptStatusResponseTypeDef,
     ListRegionsResponseTypeDef,
 )
 
+if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+
 __all__ = ("AccountClient",)
 
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
@@ -181,14 +188,19 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates the primary contact information of an Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account.Client.put_contact_information)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/client/#put_contact_information)
         """
+    def get_paginator(self, operation_name: Literal["list_regions"]) -> ListRegionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/client/#get_paginator)
+        """
     async def __aenter__(self) -> "AccountClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/client/)
         """
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
```

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/literals.py` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,22 +17,25 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AlternateContactTypeType",
+    "ListRegionsPaginatorName",
     "RegionOptStatusType",
     "AccountServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
 )
 
 
 AlternateContactTypeType = Literal["BILLING", "OPERATIONS", "SECURITY"]
+ListRegionsPaginatorName = Literal["list_regions"]
 RegionOptStatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLED_BY_DEFAULT", "ENABLING"]
 AccountServiceName = Literal["account"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -89,14 +92,15 @@
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
@@ -175,14 +179,15 @@
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
@@ -193,14 +198,15 @@
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
@@ -236,14 +242,15 @@
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
@@ -262,16 +269,19 @@
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
@@ -355,15 +365,17 @@
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
@@ -381,7 +393,8 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_regions"]
```

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/literals.pyi` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -16,21 +16,24 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AlternateContactTypeType",
+    "ListRegionsPaginatorName",
     "RegionOptStatusType",
     "AccountServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
 )
 
 AlternateContactTypeType = Literal["BILLING", "OPERATIONS", "SECURITY"]
+ListRegionsPaginatorName = Literal["list_regions"]
 RegionOptStatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLED_BY_DEFAULT", "ENABLING"]
 AccountServiceName = Literal["account"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -87,14 +90,15 @@
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
@@ -173,14 +177,15 @@
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
@@ -191,14 +196,15 @@
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
@@ -234,14 +240,15 @@
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
@@ -260,16 +267,19 @@
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
@@ -353,15 +363,17 @@
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
@@ -379,7 +391,8 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_regions"]
```

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/type_defs.py` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -17,33 +17,34 @@
 from .literals import AlternateContactTypeType, RegionOptStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AlternateContactTypeDef",
     "ContactInformationTypeDef",
     "DeleteAlternateContactRequestRequestTypeDef",
     "DisableRegionRequestRequestTypeDef",
     "ResponseMetadataTypeDef",
     "EnableRegionRequestRequestTypeDef",
     "GetAlternateContactRequestRequestTypeDef",
     "GetContactInformationRequestRequestTypeDef",
     "GetRegionOptStatusRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ListRegionsRequestRequestTypeDef",
     "RegionTypeDef",
     "PutAlternateContactRequestRequestTypeDef",
     "PutContactInformationRequestRequestTypeDef",
     "EmptyResponseMetadataTypeDef",
     "GetAlternateContactResponseTypeDef",
     "GetContactInformationResponseTypeDef",
     "GetRegionOptStatusResponseTypeDef",
+    "ListRegionsRequestListRegionsPaginateTypeDef",
     "ListRegionsResponseTypeDef",
 )
 
 AlternateContactTypeDef = TypedDict(
     "AlternateContactTypeDef",
     {
         "AlternateContactType": AlternateContactTypeType,
@@ -75,64 +76,58 @@
         "DistrictOrCounty": str,
         "StateOrRegion": str,
         "WebsiteUrl": str,
     },
     total=False,
 )
 
-
 class ContactInformationTypeDef(
     _RequiredContactInformationTypeDef, _OptionalContactInformationTypeDef
 ):
     pass
 
-
 _RequiredDeleteAlternateContactRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAlternateContactRequestRequestTypeDef",
     {
         "AlternateContactType": AlternateContactTypeType,
     },
 )
 _OptionalDeleteAlternateContactRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteAlternateContactRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class DeleteAlternateContactRequestRequestTypeDef(
     _RequiredDeleteAlternateContactRequestRequestTypeDef,
     _OptionalDeleteAlternateContactRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDisableRegionRequestRequestTypeDef = TypedDict(
     "_RequiredDisableRegionRequestRequestTypeDef",
     {
         "RegionName": str,
     },
 )
 _OptionalDisableRegionRequestRequestTypeDef = TypedDict(
     "_OptionalDisableRegionRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class DisableRegionRequestRequestTypeDef(
     _RequiredDisableRegionRequestRequestTypeDef, _OptionalDisableRegionRequestRequestTypeDef
 ):
     pass
 
-
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -150,43 +145,39 @@
     "_OptionalEnableRegionRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class EnableRegionRequestRequestTypeDef(
     _RequiredEnableRegionRequestRequestTypeDef, _OptionalEnableRegionRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredGetAlternateContactRequestRequestTypeDef = TypedDict(
     "_RequiredGetAlternateContactRequestRequestTypeDef",
     {
         "AlternateContactType": AlternateContactTypeType,
     },
 )
 _OptionalGetAlternateContactRequestRequestTypeDef = TypedDict(
     "_OptionalGetAlternateContactRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class GetAlternateContactRequestRequestTypeDef(
     _RequiredGetAlternateContactRequestRequestTypeDef,
     _OptionalGetAlternateContactRequestRequestTypeDef,
 ):
     pass
 
-
 GetContactInformationRequestRequestTypeDef = TypedDict(
     "GetContactInformationRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
@@ -201,21 +192,29 @@
     "_OptionalGetRegionOptStatusRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class GetRegionOptStatusRequestRequestTypeDef(
     _RequiredGetRegionOptStatusRequestRequestTypeDef,
     _OptionalGetRegionOptStatusRequestRequestTypeDef,
 ):
     pass
 
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
 
 ListRegionsRequestRequestTypeDef = TypedDict(
     "ListRegionsRequestRequestTypeDef",
     {
         "AccountId": str,
         "MaxResults": int,
         "NextToken": str,
@@ -247,44 +246,40 @@
     "_OptionalPutAlternateContactRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class PutAlternateContactRequestRequestTypeDef(
     _RequiredPutAlternateContactRequestRequestTypeDef,
     _OptionalPutAlternateContactRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredPutContactInformationRequestRequestTypeDef = TypedDict(
     "_RequiredPutContactInformationRequestRequestTypeDef",
     {
         "ContactInformation": ContactInformationTypeDef,
     },
 )
 _OptionalPutContactInformationRequestRequestTypeDef = TypedDict(
     "_OptionalPutContactInformationRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
-
 class PutContactInformationRequestRequestTypeDef(
     _RequiredPutContactInformationRequestRequestTypeDef,
     _OptionalPutContactInformationRequestRequestTypeDef,
 ):
     pass
 
-
 EmptyResponseMetadataTypeDef = TypedDict(
     "EmptyResponseMetadataTypeDef",
     {
         "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
@@ -309,14 +304,24 @@
     {
         "RegionName": str,
         "RegionOptStatus": RegionOptStatusType,
         "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
+ListRegionsRequestListRegionsPaginateTypeDef = TypedDict(
+    "ListRegionsRequestListRegionsPaginateTypeDef",
+    {
+        "AccountId": str,
+        "RegionOptStatusContains": Sequence[RegionOptStatusType],
+        "PaginationConfig": PaginatorConfigTypeDef,
+    },
+    total=False,
+)
+
 ListRegionsResponseTypeDef = TypedDict(
     "ListRegionsResponseTypeDef",
     {
         "NextToken": str,
         "Regions": List[RegionTypeDef],
         "ResponseMetadata": ResponseMetadataTypeDef,
     },
```

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account/type_defs.pyi` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,32 +17,35 @@
 from .literals import AlternateContactTypeType, RegionOptStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AlternateContactTypeDef",
     "ContactInformationTypeDef",
     "DeleteAlternateContactRequestRequestTypeDef",
     "DisableRegionRequestRequestTypeDef",
     "ResponseMetadataTypeDef",
     "EnableRegionRequestRequestTypeDef",
     "GetAlternateContactRequestRequestTypeDef",
     "GetContactInformationRequestRequestTypeDef",
     "GetRegionOptStatusRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ListRegionsRequestRequestTypeDef",
     "RegionTypeDef",
     "PutAlternateContactRequestRequestTypeDef",
     "PutContactInformationRequestRequestTypeDef",
     "EmptyResponseMetadataTypeDef",
     "GetAlternateContactResponseTypeDef",
     "GetContactInformationResponseTypeDef",
     "GetRegionOptStatusResponseTypeDef",
+    "ListRegionsRequestListRegionsPaginateTypeDef",
     "ListRegionsResponseTypeDef",
 )
 
 AlternateContactTypeDef = TypedDict(
     "AlternateContactTypeDef",
     {
         "AlternateContactType": AlternateContactTypeType,
@@ -74,58 +77,64 @@
         "DistrictOrCounty": str,
         "StateOrRegion": str,
         "WebsiteUrl": str,
     },
     total=False,
 )
 
+
 class ContactInformationTypeDef(
     _RequiredContactInformationTypeDef, _OptionalContactInformationTypeDef
 ):
     pass
 
+
 _RequiredDeleteAlternateContactRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAlternateContactRequestRequestTypeDef",
     {
         "AlternateContactType": AlternateContactTypeType,
     },
 )
 _OptionalDeleteAlternateContactRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteAlternateContactRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class DeleteAlternateContactRequestRequestTypeDef(
     _RequiredDeleteAlternateContactRequestRequestTypeDef,
     _OptionalDeleteAlternateContactRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDisableRegionRequestRequestTypeDef = TypedDict(
     "_RequiredDisableRegionRequestRequestTypeDef",
     {
         "RegionName": str,
     },
 )
 _OptionalDisableRegionRequestRequestTypeDef = TypedDict(
     "_OptionalDisableRegionRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class DisableRegionRequestRequestTypeDef(
     _RequiredDisableRegionRequestRequestTypeDef, _OptionalDisableRegionRequestRequestTypeDef
 ):
     pass
 
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -143,39 +152,43 @@
     "_OptionalEnableRegionRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class EnableRegionRequestRequestTypeDef(
     _RequiredEnableRegionRequestRequestTypeDef, _OptionalEnableRegionRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredGetAlternateContactRequestRequestTypeDef = TypedDict(
     "_RequiredGetAlternateContactRequestRequestTypeDef",
     {
         "AlternateContactType": AlternateContactTypeType,
     },
 )
 _OptionalGetAlternateContactRequestRequestTypeDef = TypedDict(
     "_OptionalGetAlternateContactRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class GetAlternateContactRequestRequestTypeDef(
     _RequiredGetAlternateContactRequestRequestTypeDef,
     _OptionalGetAlternateContactRequestRequestTypeDef,
 ):
     pass
 
+
 GetContactInformationRequestRequestTypeDef = TypedDict(
     "GetContactInformationRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
@@ -190,20 +203,32 @@
     "_OptionalGetRegionOptStatusRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class GetRegionOptStatusRequestRequestTypeDef(
     _RequiredGetRegionOptStatusRequestRequestTypeDef,
     _OptionalGetRegionOptStatusRequestRequestTypeDef,
 ):
     pass
 
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
 ListRegionsRequestRequestTypeDef = TypedDict(
     "ListRegionsRequestRequestTypeDef",
     {
         "AccountId": str,
         "MaxResults": int,
         "NextToken": str,
         "RegionOptStatusContains": Sequence[RegionOptStatusType],
@@ -234,40 +259,44 @@
     "_OptionalPutAlternateContactRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class PutAlternateContactRequestRequestTypeDef(
     _RequiredPutAlternateContactRequestRequestTypeDef,
     _OptionalPutAlternateContactRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredPutContactInformationRequestRequestTypeDef = TypedDict(
     "_RequiredPutContactInformationRequestRequestTypeDef",
     {
         "ContactInformation": ContactInformationTypeDef,
     },
 )
 _OptionalPutContactInformationRequestRequestTypeDef = TypedDict(
     "_OptionalPutContactInformationRequestRequestTypeDef",
     {
         "AccountId": str,
     },
     total=False,
 )
 
+
 class PutContactInformationRequestRequestTypeDef(
     _RequiredPutContactInformationRequestRequestTypeDef,
     _OptionalPutContactInformationRequestRequestTypeDef,
 ):
     pass
 
+
 EmptyResponseMetadataTypeDef = TypedDict(
     "EmptyResponseMetadataTypeDef",
     {
         "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
@@ -292,14 +321,24 @@
     {
         "RegionName": str,
         "RegionOptStatus": RegionOptStatusType,
         "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
+ListRegionsRequestListRegionsPaginateTypeDef = TypedDict(
+    "ListRegionsRequestListRegionsPaginateTypeDef",
+    {
+        "AccountId": str,
+        "RegionOptStatusContains": Sequence[RegionOptStatusType],
+        "PaginationConfig": PaginatorConfigTypeDef,
+    },
+    total=False,
+)
+
 ListRegionsResponseTypeDef = TypedDict(
     "ListRegionsResponseTypeDef",
     {
         "NextToken": str,
         "Regions": List[RegionTypeDef],
         "ResponseMetadata": ResponseMetadataTypeDef,
     },
```

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/PKG-INFO` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-account
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Account 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Account 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-account"></a>
 
 # types-aiobotocore-account
 
 [![PyPI - types-aiobotocore-account](https://img.shields.io/pypi/v/types-aiobotocore-account.svg?color=blue)](https://pypi.org/project/types-aiobotocore-account)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-account.svg?color=blue)](https://pypi.org/project/types-aiobotocore-account)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-account?color=blue)](https://pypistats.org/packages/types-aiobotocore-account)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Account 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account)
+[aiobotocore.Account 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/account.html#Account)
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
 [types-aiobotocore-account docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_account/).
 
 See how it helps to find and fix potential bugs:
 
@@ -72,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -259,28 +260,52 @@
 
 session = get_session()
 async with session.create_client("account") as client:
     client: AccountClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_account.paginator` module contains type annotations for all
+paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_account import AccountClient
+from types_aiobotocore_account.paginator import ListRegionsPaginator
+
+session = get_session()
+async with session.create_client("account") as client:
+    client: AccountClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_regions_paginator: ListRegionsPaginator = client.get_paginator("list_regions")
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_account.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_account.literals import (
     AlternateContactTypeType,
+    ListRegionsPaginatorName,
     RegionOptStatusType,
     AccountServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
 )
 
 
 def check_value(value: AlternateContactTypeType) -> bool:
     ...
 ```
 
@@ -298,22 +323,24 @@
     DeleteAlternateContactRequestRequestTypeDef,
     DisableRegionRequestRequestTypeDef,
     ResponseMetadataTypeDef,
     EnableRegionRequestRequestTypeDef,
     GetAlternateContactRequestRequestTypeDef,
     GetContactInformationRequestRequestTypeDef,
     GetRegionOptStatusRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ListRegionsRequestRequestTypeDef,
     RegionTypeDef,
     PutAlternateContactRequestRequestTypeDef,
     PutContactInformationRequestRequestTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAlternateContactResponseTypeDef,
     GetContactInformationResponseTypeDef,
     GetRegionOptStatusResponseTypeDef,
+    ListRegionsRequestListRegionsPaginateTypeDef,
     ListRegionsResponseTypeDef,
 )
 
 
 def get_structure() -> AlternateContactTypeDef:
     return {...}
 ```
@@ -321,43 +348,43 @@
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

### Comparing `types-aiobotocore-account-2.5.0.post1/types_aiobotocore_account.egg-info/SOURCES.txt` & `types-aiobotocore-account-2.5.1/types_aiobotocore_account.egg-info/SOURCES.txt`

 * *Files 9% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 types_aiobotocore_account/__init__.py
 types_aiobotocore_account/__init__.pyi
 types_aiobotocore_account/__main__.py
 types_aiobotocore_account/client.py
 types_aiobotocore_account/client.pyi
 types_aiobotocore_account/literals.py
 types_aiobotocore_account/literals.pyi
+types_aiobotocore_account/paginator.py
+types_aiobotocore_account/paginator.pyi
 types_aiobotocore_account/py.typed
 types_aiobotocore_account/type_defs.py
 types_aiobotocore_account/type_defs.pyi
 types_aiobotocore_account/version.py
 types_aiobotocore_account.egg-info/PKG-INFO
 types_aiobotocore_account.egg-info/SOURCES.txt
 types_aiobotocore_account.egg-info/dependency_links.txt
```

