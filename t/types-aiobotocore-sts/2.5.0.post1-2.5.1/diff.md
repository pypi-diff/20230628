# Comparing `tmp/types-aiobotocore-sts-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sts-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sts-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:25 2023, max compression
+gzip compressed data, was "types-aiobotocore-sts-2.5.1.tar", last modified: Wed Jun 28 01:44:15 2023, max compression
```

## Comparing `types-aiobotocore-sts-2.5.0.post1.tar` & `types-aiobotocore-sts-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.551677 types-aiobotocore-sts-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12612 2023-03-11 12:27:25.551677 types-aiobotocore-sts-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11057 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:25.551677 types-aiobotocore-sts-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:53.000000 types-aiobotocore-sts-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.551677 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      409 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10101 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    10085 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7811 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7809 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     7810 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7801 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:54.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.551677 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12612 2023-03-11 12:27:25.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      666 2023-03-11 12:27:25.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:25.000000 types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:15.822224 types-aiobotocore-sts-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12600 2023-06-28 01:44:15.818224 types-aiobotocore-sts-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11051 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:15.822224 types-aiobotocore-sts-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:15.818224 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      409 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10091 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10075 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8020 2023-06-28 01:41:43.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8018 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     7826 2023-06-28 01:41:43.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7817 2023-06-28 01:41:43.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:42.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:15.818224 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12600 2023-06-28 01:44:15.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 01:44:15.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:15.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:15.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:15.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:15.000000 types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sts-2.5.0.post1/LICENSE` & `types-aiobotocore-sts-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sts-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sts-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.STS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.STS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sts"></a>
 
 # types-aiobotocore-sts
 
 [![PyPI - types-aiobotocore-sts](https://img.shields.io/pypi/v/types-aiobotocore-sts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sts?color=blue)](https://pypistats.org/packages/types-aiobotocore-sts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.STS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
+[aiobotocore.STS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
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
 [types-aiobotocore-sts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,29 +291,29 @@
 
 ```python
 from types_aiobotocore_sts.type_defs import (
     PolicyDescriptorTypeTypeDef,
     TagTypeDef,
     AssumedRoleUserTypeDef,
     CredentialsTypeDef,
-    ResponseMetadataTypeDef,
     DecodeAuthorizationMessageRequestRequestTypeDef,
+    DecodeAuthorizationMessageResponseTypeDef,
     FederatedUserTypeDef,
     GetAccessKeyInfoRequestRequestTypeDef,
+    GetAccessKeyInfoResponseTypeDef,
+    GetCallerIdentityResponseTypeDef,
     GetSessionTokenRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     AssumeRoleWithSAMLRequestRequestTypeDef,
     AssumeRoleWithWebIdentityRequestRequestTypeDef,
     AssumeRoleRequestRequestTypeDef,
     GetFederationTokenRequestRequestTypeDef,
     AssumeRoleResponseTypeDef,
     AssumeRoleWithSAMLResponseTypeDef,
     AssumeRoleWithWebIdentityResponseTypeDef,
-    DecodeAuthorizationMessageResponseTypeDef,
-    GetAccessKeyInfoResponseTypeDef,
-    GetCallerIdentityResponseTypeDef,
     GetSessionTokenResponseTypeDef,
     GetFederationTokenResponseTypeDef,
 )
 
 
 def get_structure() -> PolicyDescriptorTypeTypeDef:
     return {...}
@@ -322,43 +322,43 @@
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

### Comparing `types-aiobotocore-sts-2.5.0.post1/README.md` & `types-aiobotocore-sts-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sts"></a>
 
 # types-aiobotocore-sts
 
 [![PyPI - types-aiobotocore-sts](https://img.shields.io/pypi/v/types-aiobotocore-sts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sts?color=blue)](https://pypistats.org/packages/types-aiobotocore-sts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.STS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
+[aiobotocore.STS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
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
 [types-aiobotocore-sts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -258,29 +258,29 @@
 
 ```python
 from types_aiobotocore_sts.type_defs import (
     PolicyDescriptorTypeTypeDef,
     TagTypeDef,
     AssumedRoleUserTypeDef,
     CredentialsTypeDef,
-    ResponseMetadataTypeDef,
     DecodeAuthorizationMessageRequestRequestTypeDef,
+    DecodeAuthorizationMessageResponseTypeDef,
     FederatedUserTypeDef,
     GetAccessKeyInfoRequestRequestTypeDef,
+    GetAccessKeyInfoResponseTypeDef,
+    GetCallerIdentityResponseTypeDef,
     GetSessionTokenRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     AssumeRoleWithSAMLRequestRequestTypeDef,
     AssumeRoleWithWebIdentityRequestRequestTypeDef,
     AssumeRoleRequestRequestTypeDef,
     GetFederationTokenRequestRequestTypeDef,
     AssumeRoleResponseTypeDef,
     AssumeRoleWithSAMLResponseTypeDef,
     AssumeRoleWithWebIdentityResponseTypeDef,
-    DecodeAuthorizationMessageResponseTypeDef,
-    GetAccessKeyInfoResponseTypeDef,
-    GetCallerIdentityResponseTypeDef,
     GetSessionTokenResponseTypeDef,
     GetFederationTokenResponseTypeDef,
 )
 
 
 def get_structure() -> PolicyDescriptorTypeTypeDef:
     return {...}
@@ -289,43 +289,43 @@
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

### Comparing `types-aiobotocore-sts-2.5.0.post1/setup.py` & `types-aiobotocore-sts-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sts.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sts",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sts"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.STS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.STS 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/",
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

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/__main__.py` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.STS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.STS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS\nOther"
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

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/client.py` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -197,15 +197,15 @@
         Policy: str = ...,
         PolicyArns: Sequence[PolicyDescriptorTypeTypeDef] = ...,
         DurationSeconds: int = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> GetFederationTokenResponseTypeDef:
         """
         Returns a set of temporary security credentials (consisting of an access key ID,
-        a secret access key, and a security token) for a federated user.
+        a secret access key, and a security token) for a user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS.Client.get_federation_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/client/#get_federation_token)
         """
 
     async def get_session_token(
         self, *, DurationSeconds: int = ..., SerialNumber: str = ..., TokenCode: str = ...
```

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/client.pyi` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -184,15 +184,15 @@
         Policy: str = ...,
         PolicyArns: Sequence[PolicyDescriptorTypeTypeDef] = ...,
         DurationSeconds: int = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> GetFederationTokenResponseTypeDef:
         """
         Returns a set of temporary security credentials (consisting of an access key ID,
-        a secret access key, and a security token) for a federated user.
+        a secret access key, and a security token) for a user.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS.Client.get_federation_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/client/#get_federation_token)
         """
     async def get_session_token(
         self, *, DurationSeconds: int = ..., SerialNumber: str = ..., TokenCode: str = ...
     ) -> GetSessionTokenResponseTypeDef:
```

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/literals.py` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/literals.py`

 * *Files 1% similar despite different names*

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

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/literals.pyi` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/literals.pyi`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/type_defs.py` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,29 +22,29 @@
 
 
 __all__ = (
     "PolicyDescriptorTypeTypeDef",
     "TagTypeDef",
     "AssumedRoleUserTypeDef",
     "CredentialsTypeDef",
-    "ResponseMetadataTypeDef",
     "DecodeAuthorizationMessageRequestRequestTypeDef",
+    "DecodeAuthorizationMessageResponseTypeDef",
     "FederatedUserTypeDef",
     "GetAccessKeyInfoRequestRequestTypeDef",
+    "GetAccessKeyInfoResponseTypeDef",
+    "GetCallerIdentityResponseTypeDef",
     "GetSessionTokenRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "AssumeRoleWithSAMLRequestRequestTypeDef",
     "AssumeRoleWithWebIdentityRequestRequestTypeDef",
     "AssumeRoleRequestRequestTypeDef",
     "GetFederationTokenRequestRequestTypeDef",
     "AssumeRoleResponseTypeDef",
     "AssumeRoleWithSAMLResponseTypeDef",
     "AssumeRoleWithWebIdentityResponseTypeDef",
-    "DecodeAuthorizationMessageResponseTypeDef",
-    "GetAccessKeyInfoResponseTypeDef",
-    "GetCallerIdentityResponseTypeDef",
     "GetSessionTokenResponseTypeDef",
     "GetFederationTokenResponseTypeDef",
 )
 
 PolicyDescriptorTypeTypeDef = TypedDict(
     "PolicyDescriptorTypeTypeDef",
     {
@@ -75,29 +75,26 @@
         "AccessKeyId": str,
         "SecretAccessKey": str,
         "SessionToken": str,
         "Expiration": datetime,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DecodeAuthorizationMessageRequestRequestTypeDef = TypedDict(
+    "DecodeAuthorizationMessageRequestRequestTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "EncodedMessage": str,
     },
 )
 
-DecodeAuthorizationMessageRequestRequestTypeDef = TypedDict(
-    "DecodeAuthorizationMessageRequestRequestTypeDef",
+DecodeAuthorizationMessageResponseTypeDef = TypedDict(
+    "DecodeAuthorizationMessageResponseTypeDef",
     {
-        "EncodedMessage": str,
+        "DecodedMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FederatedUserTypeDef = TypedDict(
     "FederatedUserTypeDef",
     {
         "FederatedUserId": str,
@@ -108,24 +105,53 @@
 GetAccessKeyInfoRequestRequestTypeDef = TypedDict(
     "GetAccessKeyInfoRequestRequestTypeDef",
     {
         "AccessKeyId": str,
     },
 )
 
+GetAccessKeyInfoResponseTypeDef = TypedDict(
+    "GetAccessKeyInfoResponseTypeDef",
+    {
+        "Account": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCallerIdentityResponseTypeDef = TypedDict(
+    "GetCallerIdentityResponseTypeDef",
+    {
+        "UserId": str,
+        "Account": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSessionTokenRequestRequestTypeDef = TypedDict(
     "GetSessionTokenRequestRequestTypeDef",
     {
         "DurationSeconds": int,
         "SerialNumber": str,
         "TokenCode": str,
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
 _RequiredAssumeRoleWithSAMLRequestRequestTypeDef = TypedDict(
     "_RequiredAssumeRoleWithSAMLRequestRequestTypeDef",
     {
         "RoleArn": str,
         "PrincipalArn": str,
         "SAMLAssertion": str,
     },
@@ -233,15 +259,15 @@
 AssumeRoleResponseTypeDef = TypedDict(
     "AssumeRoleResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
         "AssumedRoleUser": AssumedRoleUserTypeDef,
         "PackedPolicySize": int,
         "SourceIdentity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssumeRoleWithSAMLResponseTypeDef = TypedDict(
     "AssumeRoleWithSAMLResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
@@ -249,68 +275,42 @@
         "PackedPolicySize": int,
         "Subject": str,
         "SubjectType": str,
         "Issuer": str,
         "Audience": str,
         "NameQualifier": str,
         "SourceIdentity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssumeRoleWithWebIdentityResponseTypeDef = TypedDict(
     "AssumeRoleWithWebIdentityResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
         "SubjectFromWebIdentityToken": str,
         "AssumedRoleUser": AssumedRoleUserTypeDef,
         "PackedPolicySize": int,
         "Provider": str,
         "Audience": str,
         "SourceIdentity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DecodeAuthorizationMessageResponseTypeDef = TypedDict(
-    "DecodeAuthorizationMessageResponseTypeDef",
-    {
-        "DecodedMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccessKeyInfoResponseTypeDef = TypedDict(
-    "GetAccessKeyInfoResponseTypeDef",
-    {
-        "Account": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCallerIdentityResponseTypeDef = TypedDict(
-    "GetCallerIdentityResponseTypeDef",
-    {
-        "UserId": str,
-        "Account": str,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSessionTokenResponseTypeDef = TypedDict(
     "GetSessionTokenResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFederationTokenResponseTypeDef = TypedDict(
     "GetFederationTokenResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
         "FederatedUser": FederatedUserTypeDef,
         "PackedPolicySize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts/type_defs.pyi` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -21,29 +21,29 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "PolicyDescriptorTypeTypeDef",
     "TagTypeDef",
     "AssumedRoleUserTypeDef",
     "CredentialsTypeDef",
-    "ResponseMetadataTypeDef",
     "DecodeAuthorizationMessageRequestRequestTypeDef",
+    "DecodeAuthorizationMessageResponseTypeDef",
     "FederatedUserTypeDef",
     "GetAccessKeyInfoRequestRequestTypeDef",
+    "GetAccessKeyInfoResponseTypeDef",
+    "GetCallerIdentityResponseTypeDef",
     "GetSessionTokenRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "AssumeRoleWithSAMLRequestRequestTypeDef",
     "AssumeRoleWithWebIdentityRequestRequestTypeDef",
     "AssumeRoleRequestRequestTypeDef",
     "GetFederationTokenRequestRequestTypeDef",
     "AssumeRoleResponseTypeDef",
     "AssumeRoleWithSAMLResponseTypeDef",
     "AssumeRoleWithWebIdentityResponseTypeDef",
-    "DecodeAuthorizationMessageResponseTypeDef",
-    "GetAccessKeyInfoResponseTypeDef",
-    "GetCallerIdentityResponseTypeDef",
     "GetSessionTokenResponseTypeDef",
     "GetFederationTokenResponseTypeDef",
 )
 
 PolicyDescriptorTypeTypeDef = TypedDict(
     "PolicyDescriptorTypeTypeDef",
     {
@@ -74,29 +74,26 @@
         "AccessKeyId": str,
         "SecretAccessKey": str,
         "SessionToken": str,
         "Expiration": datetime,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DecodeAuthorizationMessageRequestRequestTypeDef = TypedDict(
+    "DecodeAuthorizationMessageRequestRequestTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "EncodedMessage": str,
     },
 )
 
-DecodeAuthorizationMessageRequestRequestTypeDef = TypedDict(
-    "DecodeAuthorizationMessageRequestRequestTypeDef",
+DecodeAuthorizationMessageResponseTypeDef = TypedDict(
+    "DecodeAuthorizationMessageResponseTypeDef",
     {
-        "EncodedMessage": str,
+        "DecodedMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FederatedUserTypeDef = TypedDict(
     "FederatedUserTypeDef",
     {
         "FederatedUserId": str,
@@ -107,24 +104,53 @@
 GetAccessKeyInfoRequestRequestTypeDef = TypedDict(
     "GetAccessKeyInfoRequestRequestTypeDef",
     {
         "AccessKeyId": str,
     },
 )
 
+GetAccessKeyInfoResponseTypeDef = TypedDict(
+    "GetAccessKeyInfoResponseTypeDef",
+    {
+        "Account": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCallerIdentityResponseTypeDef = TypedDict(
+    "GetCallerIdentityResponseTypeDef",
+    {
+        "UserId": str,
+        "Account": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSessionTokenRequestRequestTypeDef = TypedDict(
     "GetSessionTokenRequestRequestTypeDef",
     {
         "DurationSeconds": int,
         "SerialNumber": str,
         "TokenCode": str,
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
 _RequiredAssumeRoleWithSAMLRequestRequestTypeDef = TypedDict(
     "_RequiredAssumeRoleWithSAMLRequestRequestTypeDef",
     {
         "RoleArn": str,
         "PrincipalArn": str,
         "SAMLAssertion": str,
     },
@@ -224,15 +250,15 @@
 AssumeRoleResponseTypeDef = TypedDict(
     "AssumeRoleResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
         "AssumedRoleUser": AssumedRoleUserTypeDef,
         "PackedPolicySize": int,
         "SourceIdentity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssumeRoleWithSAMLResponseTypeDef = TypedDict(
     "AssumeRoleWithSAMLResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
@@ -240,68 +266,42 @@
         "PackedPolicySize": int,
         "Subject": str,
         "SubjectType": str,
         "Issuer": str,
         "Audience": str,
         "NameQualifier": str,
         "SourceIdentity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssumeRoleWithWebIdentityResponseTypeDef = TypedDict(
     "AssumeRoleWithWebIdentityResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
         "SubjectFromWebIdentityToken": str,
         "AssumedRoleUser": AssumedRoleUserTypeDef,
         "PackedPolicySize": int,
         "Provider": str,
         "Audience": str,
         "SourceIdentity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DecodeAuthorizationMessageResponseTypeDef = TypedDict(
-    "DecodeAuthorizationMessageResponseTypeDef",
-    {
-        "DecodedMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccessKeyInfoResponseTypeDef = TypedDict(
-    "GetAccessKeyInfoResponseTypeDef",
-    {
-        "Account": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCallerIdentityResponseTypeDef = TypedDict(
-    "GetCallerIdentityResponseTypeDef",
-    {
-        "UserId": str,
-        "Account": str,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSessionTokenResponseTypeDef = TypedDict(
     "GetSessionTokenResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFederationTokenResponseTypeDef = TypedDict(
     "GetFederationTokenResponseTypeDef",
     {
         "Credentials": CredentialsTypeDef,
         "FederatedUser": FederatedUserTypeDef,
         "PackedPolicySize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/PKG-INFO` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.STS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.STS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sts"></a>
 
 # types-aiobotocore-sts
 
 [![PyPI - types-aiobotocore-sts](https://img.shields.io/pypi/v/types-aiobotocore-sts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sts?color=blue)](https://pypistats.org/packages/types-aiobotocore-sts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.STS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
+[aiobotocore.STS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sts.html#STS)
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
 [types-aiobotocore-sts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,29 +291,29 @@
 
 ```python
 from types_aiobotocore_sts.type_defs import (
     PolicyDescriptorTypeTypeDef,
     TagTypeDef,
     AssumedRoleUserTypeDef,
     CredentialsTypeDef,
-    ResponseMetadataTypeDef,
     DecodeAuthorizationMessageRequestRequestTypeDef,
+    DecodeAuthorizationMessageResponseTypeDef,
     FederatedUserTypeDef,
     GetAccessKeyInfoRequestRequestTypeDef,
+    GetAccessKeyInfoResponseTypeDef,
+    GetCallerIdentityResponseTypeDef,
     GetSessionTokenRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     AssumeRoleWithSAMLRequestRequestTypeDef,
     AssumeRoleWithWebIdentityRequestRequestTypeDef,
     AssumeRoleRequestRequestTypeDef,
     GetFederationTokenRequestRequestTypeDef,
     AssumeRoleResponseTypeDef,
     AssumeRoleWithSAMLResponseTypeDef,
     AssumeRoleWithWebIdentityResponseTypeDef,
-    DecodeAuthorizationMessageResponseTypeDef,
-    GetAccessKeyInfoResponseTypeDef,
-    GetCallerIdentityResponseTypeDef,
     GetSessionTokenResponseTypeDef,
     GetFederationTokenResponseTypeDef,
 )
 
 
 def get_structure() -> PolicyDescriptorTypeTypeDef:
     return {...}
@@ -322,43 +322,43 @@
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

### Comparing `types-aiobotocore-sts-2.5.0.post1/types_aiobotocore_sts.egg-info/SOURCES.txt` & `types-aiobotocore-sts-2.5.1/types_aiobotocore_sts.egg-info/SOURCES.txt`

 * *Files identical despite different names*

