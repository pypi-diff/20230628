# Comparing `tmp/types-aiobotocore-sso-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sso-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sso-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:25 2023, max compression
+gzip compressed data, was "types-aiobotocore-sso-2.5.1.tar", last modified: Wed Jun 28 01:44:14 2023, max compression
```

## Comparing `types-aiobotocore-sso-2.5.0.post1.tar` & `types-aiobotocore-sso-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.195674 types-aiobotocore-sso-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13287 2023-03-11 12:27:25.195674 types-aiobotocore-sso-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11732 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:25.195674 types-aiobotocore-sso-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.195674 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/
--rw-r--r--   0 runner    (1001) docker     (123)      799 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      798 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7370 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7355 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8046 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8044 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3143 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3138 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5375 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5366 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:43.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.195674 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13287 2023-03-11 12:27:25.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:25.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:25.000000 types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.710221 types-aiobotocore-sso-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13275 2023-06-28 01:44:14.702221 types-aiobotocore-sso-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11726 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:14.710221 types-aiobotocore-sso-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.698221 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/
+-rw-r--r--   0 runner    (1001) docker     (123)      799 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      798 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7370 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7355 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8255 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8253 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3027 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3023 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5387 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5378 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:32.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.702221 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13275 2023-06-28 01:44:14.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:14.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:14.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:14.000000 types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sso-2.5.0.post1/LICENSE` & `types-aiobotocore-sso-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sso-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sso-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sso
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSO 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSO 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sso"></a>
 
 # types-aiobotocore-sso
 
 [![PyPI - types-aiobotocore-sso](https://img.shields.io/pypi/v/types-aiobotocore-sso.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSO 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
+[aiobotocore.SSO 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
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
 [types-aiobotocore-sso docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,27 +317,27 @@
 
 `types_aiobotocore_sso.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sso.type_defs import (
     AccountInfoTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRoleCredentialsRequestRequestTypeDef,
     RoleCredentialsTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountRolesRequestListAccountRolesPaginateTypeDef,
     ListAccountRolesRequestRequestTypeDef,
     RoleInfoTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
     LogoutRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ListAccountsResponseTypeDef,
     GetRoleCredentialsResponseTypeDef,
-    ListAccountRolesRequestListAccountRolesPaginateTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountRolesResponseTypeDef,
 )
 
 
 def get_structure() -> AccountInfoTypeDef:
     return {...}
 ```
@@ -345,43 +345,43 @@
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/README.md` & `types-aiobotocore-sso-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sso"></a>
 
 # types-aiobotocore-sso
 
 [![PyPI - types-aiobotocore-sso](https://img.shields.io/pypi/v/types-aiobotocore-sso.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSO 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
+[aiobotocore.SSO 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
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
 [types-aiobotocore-sso docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/).
 
 See how it helps to find and fix potential bugs:
 
@@ -284,27 +284,27 @@
 
 `types_aiobotocore_sso.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sso.type_defs import (
     AccountInfoTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRoleCredentialsRequestRequestTypeDef,
     RoleCredentialsTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountRolesRequestListAccountRolesPaginateTypeDef,
     ListAccountRolesRequestRequestTypeDef,
     RoleInfoTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
     LogoutRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ListAccountsResponseTypeDef,
     GetRoleCredentialsResponseTypeDef,
-    ListAccountRolesRequestListAccountRolesPaginateTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountRolesResponseTypeDef,
 )
 
 
 def get_structure() -> AccountInfoTypeDef:
     return {...}
 ```
@@ -312,43 +312,43 @@
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/setup.py` & `types-aiobotocore-sso-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sso.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sso",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sso"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SSO 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SSO 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/",
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/__init__.py` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/__init__.pyi` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/__main__.py` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/__main__.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SSO 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SSO 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO\nOther"
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/client.py` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/client.pyi` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/literals.py` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/literals.pyi`

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
     "ListAccountRolesPaginatorName",
     "ListAccountsPaginatorName",
     "SSOServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ListAccountRolesPaginatorName = Literal["list_account_roles"]
 ListAccountsPaginatorName = Literal["list_accounts"]
 SSOServiceName = Literal["sso"]
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/literals.pyi` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -14,24 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ListAccountRolesPaginatorName",
     "ListAccountsPaginatorName",
     "SSOServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ListAccountRolesPaginatorName = Literal["list_account_roles"]
 ListAccountsPaginatorName = Literal["list_accounts"]
 SSOServiceName = Literal["sso"]
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/paginator.py` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,32 +18,25 @@
     with session.create_client("sso") as client:
         client: SSOClient
 
         list_account_roles_paginator: ListAccountRolesPaginator = client.get_paginator("list_account_roles")
         list_accounts_paginator: ListAccountsPaginator = client.get_paginator("list_accounts")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAccountRolesResponseTypeDef,
     ListAccountsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListAccountRolesPaginator", "ListAccountsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,28 +49,28 @@
 class ListAccountRolesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccountRoles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountrolespaginator)
     """
 
     def paginate(
-        self, *, accessToken: str, accountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accessToken: str, accountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountRolesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccountRoles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountrolespaginator)
         """
 
 
 class ListAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountspaginator)
     """
 
     def paginate(
-        self, *, accessToken: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accessToken: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountspaginator)
         """
```

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/paginator.pyi` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,31 +18,25 @@
     with session.create_client("sso") as client:
         client: SSOClient
 
         list_account_roles_paginator: ListAccountRolesPaginator = client.get_paginator("list_account_roles")
         list_accounts_paginator: ListAccountsPaginator = client.get_paginator("list_accounts")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAccountRolesResponseTypeDef,
     ListAccountsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListAccountRolesPaginator", "ListAccountsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,27 +46,27 @@
 class ListAccountRolesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccountRoles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountrolespaginator)
     """
 
     def paginate(
-        self, *, accessToken: str, accountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accessToken: str, accountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountRolesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccountRoles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountrolespaginator)
         """
 
 class ListAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountspaginator)
     """
 
     def paginate(
-        self, *, accessToken: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accessToken: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO.Paginator.ListAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/paginators/#listaccountspaginator)
         """
```

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/type_defs.py` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,48 +18,44 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountInfoTypeDef",
-    "ResponseMetadataTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetRoleCredentialsRequestRequestTypeDef",
     "RoleCredentialsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountRolesRequestListAccountRolesPaginateTypeDef",
     "ListAccountRolesRequestRequestTypeDef",
     "RoleInfoTypeDef",
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountsRequestRequestTypeDef",
     "LogoutRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ListAccountsResponseTypeDef",
     "GetRoleCredentialsResponseTypeDef",
-    "ListAccountRolesRequestListAccountRolesPaginateTypeDef",
-    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountRolesResponseTypeDef",
 )
 
 AccountInfoTypeDef = TypedDict(
     "AccountInfoTypeDef",
     {
         "accountId": str,
         "accountName": str,
         "emailAddress": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoleCredentialsRequestRequestTypeDef = TypedDict(
     "GetRoleCredentialsRequestRequestTypeDef",
     {
         "roleName": str,
@@ -75,24 +71,37 @@
         "secretAccessKey": str,
         "sessionToken": str,
         "expiration": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
+    "_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "accessToken": str,
+        "accountId": str,
+    },
+)
+_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
+    "_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAccountRolesRequestListAccountRolesPaginateTypeDef(
+    _RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef,
+    _OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccountRolesRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountRolesRequestRequestTypeDef",
     {
         "accessToken": str,
         "accountId": str,
     },
 )
@@ -117,14 +126,36 @@
     {
         "roleName": str,
         "accountId": str,
     },
     total=False,
 )
 
+_RequiredListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "_RequiredListAccountsRequestListAccountsPaginateTypeDef",
+    {
+        "accessToken": str,
+    },
+)
+_OptionalListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "_OptionalListAccountsRequestListAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAccountsRequestListAccountsPaginateTypeDef(
+    _RequiredListAccountsRequestListAccountsPaginateTypeDef,
+    _OptionalListAccountsRequestListAccountsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAccountsRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountsRequestRequestTypeDef",
     {
         "accessToken": str,
     },
 )
 _OptionalListAccountsRequestRequestTypeDef = TypedDict(
@@ -146,84 +177,53 @@
 LogoutRequestRequestTypeDef = TypedDict(
     "LogoutRequestRequestTypeDef",
     {
         "accessToken": str,
     },
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
 
 ListAccountsResponseTypeDef = TypedDict(
     "ListAccountsResponseTypeDef",
     {
         "nextToken": str,
         "accountList": List[AccountInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoleCredentialsResponseTypeDef = TypedDict(
     "GetRoleCredentialsResponseTypeDef",
     {
         "roleCredentials": RoleCredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
-    "_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef",
-    {
-        "accessToken": str,
-        "accountId": str,
-    },
-)
-_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
-    "_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListAccountRolesRequestListAccountRolesPaginateTypeDef(
-    _RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef,
-    _OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "_RequiredListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "accessToken": str,
-    },
-)
-_OptionalListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "_OptionalListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAccountsRequestListAccountsPaginateTypeDef(
-    _RequiredListAccountsRequestListAccountsPaginateTypeDef,
-    _OptionalListAccountsRequestListAccountsPaginateTypeDef,
-):
-    pass
-
-
 ListAccountRolesResponseTypeDef = TypedDict(
     "ListAccountRolesResponseTypeDef",
     {
         "nextToken": str,
         "roleList": List[RoleInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso/type_defs.pyi` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -17,48 +17,44 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountInfoTypeDef",
-    "ResponseMetadataTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetRoleCredentialsRequestRequestTypeDef",
     "RoleCredentialsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountRolesRequestListAccountRolesPaginateTypeDef",
     "ListAccountRolesRequestRequestTypeDef",
     "RoleInfoTypeDef",
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountsRequestRequestTypeDef",
     "LogoutRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ListAccountsResponseTypeDef",
     "GetRoleCredentialsResponseTypeDef",
-    "ListAccountRolesRequestListAccountRolesPaginateTypeDef",
-    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountRolesResponseTypeDef",
 )
 
 AccountInfoTypeDef = TypedDict(
     "AccountInfoTypeDef",
     {
         "accountId": str,
         "accountName": str,
         "emailAddress": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoleCredentialsRequestRequestTypeDef = TypedDict(
     "GetRoleCredentialsRequestRequestTypeDef",
     {
         "roleName": str,
@@ -74,24 +70,35 @@
         "secretAccessKey": str,
         "sessionToken": str,
         "expiration": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
+    "_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "accessToken": str,
+        "accountId": str,
+    },
+)
+_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
+    "_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAccountRolesRequestListAccountRolesPaginateTypeDef(
+    _RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef,
+    _OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccountRolesRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountRolesRequestRequestTypeDef",
     {
         "accessToken": str,
         "accountId": str,
     },
 )
@@ -114,14 +121,34 @@
     {
         "roleName": str,
         "accountId": str,
     },
     total=False,
 )
 
+_RequiredListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "_RequiredListAccountsRequestListAccountsPaginateTypeDef",
+    {
+        "accessToken": str,
+    },
+)
+_OptionalListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "_OptionalListAccountsRequestListAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAccountsRequestListAccountsPaginateTypeDef(
+    _RequiredListAccountsRequestListAccountsPaginateTypeDef,
+    _OptionalListAccountsRequestListAccountsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAccountsRequestRequestTypeDef = TypedDict(
     "_RequiredListAccountsRequestRequestTypeDef",
     {
         "accessToken": str,
     },
 )
 _OptionalListAccountsRequestRequestTypeDef = TypedDict(
@@ -141,80 +168,53 @@
 LogoutRequestRequestTypeDef = TypedDict(
     "LogoutRequestRequestTypeDef",
     {
         "accessToken": str,
     },
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
 
 ListAccountsResponseTypeDef = TypedDict(
     "ListAccountsResponseTypeDef",
     {
         "nextToken": str,
         "accountList": List[AccountInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoleCredentialsResponseTypeDef = TypedDict(
     "GetRoleCredentialsResponseTypeDef",
     {
         "roleCredentials": RoleCredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
-    "_RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef",
-    {
-        "accessToken": str,
-        "accountId": str,
-    },
-)
-_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef = TypedDict(
-    "_OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListAccountRolesRequestListAccountRolesPaginateTypeDef(
-    _RequiredListAccountRolesRequestListAccountRolesPaginateTypeDef,
-    _OptionalListAccountRolesRequestListAccountRolesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "_RequiredListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "accessToken": str,
-    },
-)
-_OptionalListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "_OptionalListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAccountsRequestListAccountsPaginateTypeDef(
-    _RequiredListAccountsRequestListAccountsPaginateTypeDef,
-    _OptionalListAccountsRequestListAccountsPaginateTypeDef,
-):
-    pass
-
 ListAccountRolesResponseTypeDef = TypedDict(
     "ListAccountRolesResponseTypeDef",
     {
         "nextToken": str,
         "roleList": List[RoleInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/PKG-INFO` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sso
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSO 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSO 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sso"></a>
 
 # types-aiobotocore-sso
 
 [![PyPI - types-aiobotocore-sso](https://img.shields.io/pypi/v/types-aiobotocore-sso.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSO 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
+[aiobotocore.SSO 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso.html#SSO)
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
 [types-aiobotocore-sso docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,27 +317,27 @@
 
 `types_aiobotocore_sso.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sso.type_defs import (
     AccountInfoTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRoleCredentialsRequestRequestTypeDef,
     RoleCredentialsTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountRolesRequestListAccountRolesPaginateTypeDef,
     ListAccountRolesRequestRequestTypeDef,
     RoleInfoTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
     LogoutRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ListAccountsResponseTypeDef,
     GetRoleCredentialsResponseTypeDef,
-    ListAccountRolesRequestListAccountRolesPaginateTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountRolesResponseTypeDef,
 )
 
 
 def get_structure() -> AccountInfoTypeDef:
     return {...}
 ```
@@ -345,43 +345,43 @@
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

### Comparing `types-aiobotocore-sso-2.5.0.post1/types_aiobotocore_sso.egg-info/SOURCES.txt` & `types-aiobotocore-sso-2.5.1/types_aiobotocore_sso.egg-info/SOURCES.txt`

 * *Files identical despite different names*

