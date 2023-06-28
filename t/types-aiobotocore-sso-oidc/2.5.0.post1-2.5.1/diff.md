# Comparing `tmp/types-aiobotocore-sso-oidc-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sso-oidc-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sso-oidc-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-sso-oidc-2.5.1.tar", last modified: Wed Jun 28 01:44:14 2023, max compression
```

## Comparing `types-aiobotocore-sso-oidc-2.5.0.post1.tar` & `types-aiobotocore-sso-oidc-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:24.935671 types-aiobotocore-sso-oidc-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12345 2023-03-11 12:27:24.935671 types-aiobotocore-sso-oidc-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    10771 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:24.935671 types-aiobotocore-sso-oidc-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2130 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:24.935671 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      444 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      945 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6480 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6469 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7754 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7752 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     3332 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     3327 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:45.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:24.935671 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12345 2023-03-11 12:27:24.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:24.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:24.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:24.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:24.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:24.000000 types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.578221 types-aiobotocore-sso-oidc-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12338 2023-06-28 01:44:14.578221 types-aiobotocore-sso-oidc-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    10770 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:14.578221 types-aiobotocore-sso-oidc-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.566221 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      444 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      933 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6480 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6469 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7963 2023-06-28 01:41:35.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7961 2023-06-28 01:41:35.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     3338 2023-06-28 01:41:35.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-06-28 01:41:35.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:34.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.578221 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12338 2023-06-28 01:44:14.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:44:14.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:14.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:14.000000 types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/LICENSE` & `types-aiobotocore-sso-oidc-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sso-oidc-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sso-oidc
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSOOIDC 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSOOIDC 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sso-oidc"></a>
 
 # types-aiobotocore-sso-oidc
 
 [![PyPI - types-aiobotocore-sso-oidc](https://img.shields.io/pypi/v/types-aiobotocore-sso-oidc.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-oidc)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso-oidc.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-oidc)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso-oidc?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso-oidc)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSOOIDC 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC)
+[aiobotocore.SSOOIDC 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC)
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
 [types-aiobotocore-sso-oidc docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,19 +289,19 @@
 
 `types_aiobotocore_sso_oidc.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sso_oidc.type_defs import (
     CreateTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    RegisterClientRequestRequestTypeDef,
-    StartDeviceAuthorizationRequestRequestTypeDef,
     CreateTokenResponseTypeDef,
+    RegisterClientRequestRequestTypeDef,
     RegisterClientResponseTypeDef,
+    ResponseMetadataTypeDef,
+    StartDeviceAuthorizationRequestRequestTypeDef,
     StartDeviceAuthorizationResponseTypeDef,
 )
 
 
 def get_structure() -> CreateTokenRequestRequestTypeDef:
     return {...}
 ```
@@ -309,43 +309,43 @@
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/README.md` & `types-aiobotocore-sso-oidc-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sso-oidc"></a>
 
 # types-aiobotocore-sso-oidc
 
 [![PyPI - types-aiobotocore-sso-oidc](https://img.shields.io/pypi/v/types-aiobotocore-sso-oidc.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-oidc)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso-oidc.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-oidc)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso-oidc?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso-oidc)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSOOIDC 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC)
+[aiobotocore.SSOOIDC 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC)
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
 [types-aiobotocore-sso-oidc docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/).
 
 See how it helps to find and fix potential bugs:
 
@@ -256,19 +256,19 @@
 
 `types_aiobotocore_sso_oidc.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sso_oidc.type_defs import (
     CreateTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    RegisterClientRequestRequestTypeDef,
-    StartDeviceAuthorizationRequestRequestTypeDef,
     CreateTokenResponseTypeDef,
+    RegisterClientRequestRequestTypeDef,
     RegisterClientResponseTypeDef,
+    ResponseMetadataTypeDef,
+    StartDeviceAuthorizationRequestRequestTypeDef,
     StartDeviceAuthorizationResponseTypeDef,
 )
 
 
 def get_structure() -> CreateTokenRequestRequestTypeDef:
     return {...}
 ```
@@ -276,43 +276,43 @@
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/setup.py` & `types-aiobotocore-sso-oidc-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sso-oidc.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sso-oidc",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sso_oidc"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SSOOIDC 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SSOOIDC 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/"
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/__main__.py` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SSOOIDC 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SSOOIDC 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC\nOther"
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/client.py` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/client.pyi` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/literals.py` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/literals.py`

 * *Files 7% similar despite different names*

```diff
@@ -81,14 +81,15 @@
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
@@ -167,14 +168,15 @@
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
@@ -185,14 +187,15 @@
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
@@ -228,14 +231,15 @@
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
@@ -254,16 +258,19 @@
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
@@ -347,15 +354,17 @@
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/literals.pyi` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -79,14 +79,15 @@
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
@@ -165,14 +166,15 @@
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
@@ -183,14 +185,15 @@
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
@@ -226,14 +229,15 @@
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
@@ -252,16 +256,19 @@
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
@@ -345,15 +352,17 @@
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/type_defs.py` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -18,19 +18,19 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CreateTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "RegisterClientRequestRequestTypeDef",
-    "StartDeviceAuthorizationRequestRequestTypeDef",
     "CreateTokenResponseTypeDef",
+    "RegisterClientRequestRequestTypeDef",
     "RegisterClientResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartDeviceAuthorizationRequestRequestTypeDef",
     "StartDeviceAuthorizationResponseTypeDef",
 )
 
 _RequiredCreateTokenRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTokenRequestRequestTypeDef",
     {
         "clientId": str,
@@ -53,22 +53,23 @@
 
 class CreateTokenRequestRequestTypeDef(
     _RequiredCreateTokenRequestRequestTypeDef, _OptionalCreateTokenRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateTokenResponseTypeDef = TypedDict(
+    "CreateTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "accessToken": str,
+        "tokenType": str,
+        "expiresIn": int,
+        "refreshToken": str,
+        "idToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterClientRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterClientRequestRequestTypeDef",
     {
         "clientName": str,
@@ -86,53 +87,52 @@
 
 class RegisterClientRequestRequestTypeDef(
     _RequiredRegisterClientRequestRequestTypeDef, _OptionalRegisterClientRequestRequestTypeDef
 ):
     pass
 
 
-StartDeviceAuthorizationRequestRequestTypeDef = TypedDict(
-    "StartDeviceAuthorizationRequestRequestTypeDef",
+RegisterClientResponseTypeDef = TypedDict(
+    "RegisterClientResponseTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
-        "startUrl": str,
+        "clientIdIssuedAt": int,
+        "clientSecretExpiresAt": int,
+        "authorizationEndpoint": str,
+        "tokenEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateTokenResponseTypeDef = TypedDict(
-    "CreateTokenResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "accessToken": str,
-        "tokenType": str,
-        "expiresIn": int,
-        "refreshToken": str,
-        "idToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-RegisterClientResponseTypeDef = TypedDict(
-    "RegisterClientResponseTypeDef",
+StartDeviceAuthorizationRequestRequestTypeDef = TypedDict(
+    "StartDeviceAuthorizationRequestRequestTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
-        "clientIdIssuedAt": int,
-        "clientSecretExpiresAt": int,
-        "authorizationEndpoint": str,
-        "tokenEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "startUrl": str,
     },
 )
 
 StartDeviceAuthorizationResponseTypeDef = TypedDict(
     "StartDeviceAuthorizationResponseTypeDef",
     {
         "deviceCode": str,
         "userCode": str,
         "verificationUri": str,
         "verificationUriComplete": str,
         "expiresIn": int,
         "interval": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc/type_defs.pyi` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -17,19 +17,19 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CreateTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "RegisterClientRequestRequestTypeDef",
-    "StartDeviceAuthorizationRequestRequestTypeDef",
     "CreateTokenResponseTypeDef",
+    "RegisterClientRequestRequestTypeDef",
     "RegisterClientResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartDeviceAuthorizationRequestRequestTypeDef",
     "StartDeviceAuthorizationResponseTypeDef",
 )
 
 _RequiredCreateTokenRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTokenRequestRequestTypeDef",
     {
         "clientId": str,
@@ -50,22 +50,23 @@
 )
 
 class CreateTokenRequestRequestTypeDef(
     _RequiredCreateTokenRequestRequestTypeDef, _OptionalCreateTokenRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateTokenResponseTypeDef = TypedDict(
+    "CreateTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "accessToken": str,
+        "tokenType": str,
+        "expiresIn": int,
+        "refreshToken": str,
+        "idToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterClientRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterClientRequestRequestTypeDef",
     {
         "clientName": str,
@@ -81,53 +82,52 @@
 )
 
 class RegisterClientRequestRequestTypeDef(
     _RequiredRegisterClientRequestRequestTypeDef, _OptionalRegisterClientRequestRequestTypeDef
 ):
     pass
 
-StartDeviceAuthorizationRequestRequestTypeDef = TypedDict(
-    "StartDeviceAuthorizationRequestRequestTypeDef",
+RegisterClientResponseTypeDef = TypedDict(
+    "RegisterClientResponseTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
-        "startUrl": str,
+        "clientIdIssuedAt": int,
+        "clientSecretExpiresAt": int,
+        "authorizationEndpoint": str,
+        "tokenEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateTokenResponseTypeDef = TypedDict(
-    "CreateTokenResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "accessToken": str,
-        "tokenType": str,
-        "expiresIn": int,
-        "refreshToken": str,
-        "idToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-RegisterClientResponseTypeDef = TypedDict(
-    "RegisterClientResponseTypeDef",
+StartDeviceAuthorizationRequestRequestTypeDef = TypedDict(
+    "StartDeviceAuthorizationRequestRequestTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
-        "clientIdIssuedAt": int,
-        "clientSecretExpiresAt": int,
-        "authorizationEndpoint": str,
-        "tokenEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "startUrl": str,
     },
 )
 
 StartDeviceAuthorizationResponseTypeDef = TypedDict(
     "StartDeviceAuthorizationResponseTypeDef",
     {
         "deviceCode": str,
         "userCode": str,
         "verificationUri": str,
         "verificationUriComplete": str,
         "expiresIn": int,
         "interval": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/PKG-INFO` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sso-oidc
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSOOIDC 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSOOIDC 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sso-oidc"></a>
 
 # types-aiobotocore-sso-oidc
 
 [![PyPI - types-aiobotocore-sso-oidc](https://img.shields.io/pypi/v/types-aiobotocore-sso-oidc.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-oidc)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sso-oidc.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sso-oidc)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sso-oidc?color=blue)](https://pypistats.org/packages/types-aiobotocore-sso-oidc)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSOOIDC 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC)
+[aiobotocore.SSOOIDC 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sso-oidc.html#SSOOIDC)
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
 [types-aiobotocore-sso-oidc docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sso_oidc/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,19 +289,19 @@
 
 `types_aiobotocore_sso_oidc.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sso_oidc.type_defs import (
     CreateTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    RegisterClientRequestRequestTypeDef,
-    StartDeviceAuthorizationRequestRequestTypeDef,
     CreateTokenResponseTypeDef,
+    RegisterClientRequestRequestTypeDef,
     RegisterClientResponseTypeDef,
+    ResponseMetadataTypeDef,
+    StartDeviceAuthorizationRequestRequestTypeDef,
     StartDeviceAuthorizationResponseTypeDef,
 )
 
 
 def get_structure() -> CreateTokenRequestRequestTypeDef:
     return {...}
 ```
@@ -309,43 +309,43 @@
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

### Comparing `types-aiobotocore-sso-oidc-2.5.0.post1/types_aiobotocore_sso_oidc.egg-info/SOURCES.txt` & `types-aiobotocore-sso-oidc-2.5.1/types_aiobotocore_sso_oidc.egg-info/SOURCES.txt`

 * *Files identical despite different names*

