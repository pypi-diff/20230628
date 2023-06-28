# Comparing `tmp/types-aiobotocore-cognito-identity-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cognito-identity-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cognito-identity-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-cognito-identity-2.5.1.tar", last modified: Wed Jun 28 01:43:18 2023, max compression
```

## Comparing `types-aiobotocore-cognito-identity-2.5.0.post1.tar` & `types-aiobotocore-cognito-identity-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.791073 types-aiobotocore-cognito-identity-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15446 2023-03-11 12:26:24.787073 types-aiobotocore-cognito-identity-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13840 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.791073 types-aiobotocore-cognito-identity-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.787073 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/
--rw-r--r--   0 runner    (1001) docker     (123)      734 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      733 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      977 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21137 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    21104 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8331 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8329 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2250 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2246 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    18285 2023-03-11 12:11:30.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18261 2023-03-11 12:11:30.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:29.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.787073 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15446 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.998115 types-aiobotocore-cognito-identity-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15447 2023-06-28 01:43:17.998115 types-aiobotocore-cognito-identity-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13847 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:17.998115 types-aiobotocore-cognito-identity-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 01:28:06.000000 types-aiobotocore-cognito-identity-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.990115 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/
+-rw-r--r--   0 runner    (1001) docker     (123)      734 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      733 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21136 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21103 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8540 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8538 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2129 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    18319 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18295 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:07.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.998115 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15447 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/LICENSE` & `types-aiobotocore-cognito-identity-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cognito-identity-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cognito-identity
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CognitoIdentity 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CognitoIdentity 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cognito-identity"></a>
 
 # types-aiobotocore-cognito-identity
 
 [![PyPI - types-aiobotocore-cognito-identity](https://img.shields.io/pypi/v/types-aiobotocore-cognito-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-identity)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cognito-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-identity)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cognito-identity?color=blue)](https://pypistats.org/packages/types-aiobotocore-cognito-identity)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CognitoIdentity 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
+[aiobotocore.CognitoIdentity 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
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
 [types-aiobotocore-cognito-identity docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,57 +323,57 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cognito_identity.type_defs import (
     CognitoIdentityProviderTypeDef,
     CredentialsTypeDef,
     DeleteIdentitiesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedIdentityIdTypeDef,
     DeleteIdentityPoolInputRequestTypeDef,
     DescribeIdentityInputRequestTypeDef,
     DescribeIdentityPoolInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCredentialsForIdentityInputRequestTypeDef,
     GetIdInputRequestTypeDef,
+    GetIdResponseTypeDef,
     GetIdentityPoolRolesInputRequestTypeDef,
     GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
+    GetOpenIdTokenForDeveloperIdentityResponseTypeDef,
     GetOpenIdTokenInputRequestTypeDef,
+    GetOpenIdTokenResponseTypeDef,
     GetPrincipalTagAttributeMapInputRequestTypeDef,
+    GetPrincipalTagAttributeMapResponseTypeDef,
+    IdentityDescriptionResponseMetadataTypeDef,
     IdentityDescriptionTypeDef,
     IdentityPoolShortDescriptionTypeDef,
     ListIdentitiesInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef,
     ListIdentityPoolsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     LookupDeveloperIdentityInputRequestTypeDef,
+    LookupDeveloperIdentityResponseTypeDef,
     MappingRuleTypeDef,
     MergeDeveloperIdentitiesInputRequestTypeDef,
+    MergeDeveloperIdentitiesResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SetPrincipalTagAttributeMapInputRequestTypeDef,
+    SetPrincipalTagAttributeMapResponseTypeDef,
     TagResourceInputRequestTypeDef,
     UnlinkDeveloperIdentityInputRequestTypeDef,
     UnlinkIdentityInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     CreateIdentityPoolInputRequestTypeDef,
     IdentityPoolRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCredentialsForIdentityResponseTypeDef,
-    GetIdResponseTypeDef,
-    GetOpenIdTokenForDeveloperIdentityResponseTypeDef,
-    GetOpenIdTokenResponseTypeDef,
-    GetPrincipalTagAttributeMapResponseTypeDef,
-    IdentityDescriptionResponseMetadataTypeDef,
     IdentityPoolTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    LookupDeveloperIdentityResponseTypeDef,
-    MergeDeveloperIdentitiesResponseTypeDef,
-    SetPrincipalTagAttributeMapResponseTypeDef,
+    GetCredentialsForIdentityResponseTypeDef,
     DeleteIdentitiesResponseTypeDef,
     ListIdentitiesResponseTypeDef,
     ListIdentityPoolsResponseTypeDef,
-    ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef,
     RulesConfigurationTypeTypeDef,
     RoleMappingTypeDef,
     GetIdentityPoolRolesResponseTypeDef,
     SetIdentityPoolRolesInputRequestTypeDef,
 )
 
 
@@ -384,43 +384,43 @@
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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/README.md` & `types-aiobotocore-cognito-identity-2.5.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cognito-identity"></a>
 
 # types-aiobotocore-cognito-identity
 
 [![PyPI - types-aiobotocore-cognito-identity](https://img.shields.io/pypi/v/types-aiobotocore-cognito-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-identity)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cognito-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-identity)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cognito-identity?color=blue)](https://pypistats.org/packages/types-aiobotocore-cognito-identity)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CognitoIdentity 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
+[aiobotocore.CognitoIdentity 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
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
 [types-aiobotocore-cognito-identity docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,57 +290,57 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cognito_identity.type_defs import (
     CognitoIdentityProviderTypeDef,
     CredentialsTypeDef,
     DeleteIdentitiesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedIdentityIdTypeDef,
     DeleteIdentityPoolInputRequestTypeDef,
     DescribeIdentityInputRequestTypeDef,
     DescribeIdentityPoolInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCredentialsForIdentityInputRequestTypeDef,
     GetIdInputRequestTypeDef,
+    GetIdResponseTypeDef,
     GetIdentityPoolRolesInputRequestTypeDef,
     GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
+    GetOpenIdTokenForDeveloperIdentityResponseTypeDef,
     GetOpenIdTokenInputRequestTypeDef,
+    GetOpenIdTokenResponseTypeDef,
     GetPrincipalTagAttributeMapInputRequestTypeDef,
+    GetPrincipalTagAttributeMapResponseTypeDef,
+    IdentityDescriptionResponseMetadataTypeDef,
     IdentityDescriptionTypeDef,
     IdentityPoolShortDescriptionTypeDef,
     ListIdentitiesInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef,
     ListIdentityPoolsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     LookupDeveloperIdentityInputRequestTypeDef,
+    LookupDeveloperIdentityResponseTypeDef,
     MappingRuleTypeDef,
     MergeDeveloperIdentitiesInputRequestTypeDef,
+    MergeDeveloperIdentitiesResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SetPrincipalTagAttributeMapInputRequestTypeDef,
+    SetPrincipalTagAttributeMapResponseTypeDef,
     TagResourceInputRequestTypeDef,
     UnlinkDeveloperIdentityInputRequestTypeDef,
     UnlinkIdentityInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     CreateIdentityPoolInputRequestTypeDef,
     IdentityPoolRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCredentialsForIdentityResponseTypeDef,
-    GetIdResponseTypeDef,
-    GetOpenIdTokenForDeveloperIdentityResponseTypeDef,
-    GetOpenIdTokenResponseTypeDef,
-    GetPrincipalTagAttributeMapResponseTypeDef,
-    IdentityDescriptionResponseMetadataTypeDef,
     IdentityPoolTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    LookupDeveloperIdentityResponseTypeDef,
-    MergeDeveloperIdentitiesResponseTypeDef,
-    SetPrincipalTagAttributeMapResponseTypeDef,
+    GetCredentialsForIdentityResponseTypeDef,
     DeleteIdentitiesResponseTypeDef,
     ListIdentitiesResponseTypeDef,
     ListIdentityPoolsResponseTypeDef,
-    ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef,
     RulesConfigurationTypeTypeDef,
     RoleMappingTypeDef,
     GetIdentityPoolRolesResponseTypeDef,
     SetIdentityPoolRolesInputRequestTypeDef,
 )
 
 
@@ -351,43 +351,43 @@
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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/setup.py` & `types-aiobotocore-cognito-identity-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cognito-identity.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cognito-identity",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cognito_identity"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CognitoIdentity 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CognitoIdentity 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/"
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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/__init__.py` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/__init__.pyi` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/__main__.py` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CognitoIdentity 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CognitoIdentity 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity\nOther"
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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/client.py` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -305,15 +305,15 @@
         *,
         SourceUserIdentifier: str,
         DestinationUserIdentifier: str,
         DeveloperProviderName: str,
         IdentityPoolId: str
     ) -> MergeDeveloperIdentitiesResponseTypeDef:
         """
-        Merges two users having different `IdentityId` s, existing in the same identity
+        Merges two users having different `IdentityId`s, existing in the same identity
         pool, and identified by the same developer provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity.Client.merge_developer_identities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/client/#merge_developer_identities)
         """
 
     async def set_identity_pool_roles(
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/client.pyi` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -282,15 +282,15 @@
         *,
         SourceUserIdentifier: str,
         DestinationUserIdentifier: str,
         DeveloperProviderName: str,
         IdentityPoolId: str
     ) -> MergeDeveloperIdentitiesResponseTypeDef:
         """
-        Merges two users having different `IdentityId` s, existing in the same identity
+        Merges two users having different `IdentityId`s, existing in the same identity
         pool, and identified by the same developer provider.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity.Client.merge_developer_identities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/client/#merge_developer_identities)
         """
     async def set_identity_pool_roles(
         self,
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/literals.py` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/literals.pyi` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/literals.pyi`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/paginator.py` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/paginator.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -16,47 +16,37 @@
     session = get_session()
     with session.create_client("cognito-identity") as client:
         client: CognitoIdentityClient
 
         list_identity_pools_paginator: ListIdentityPoolsPaginator = client.get_paginator("list_identity_pools")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListIdentityPoolsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListIdentityPoolsPaginator",)
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListIdentityPoolsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity.Paginator.ListIdentityPools)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/paginators/#listidentitypoolspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentityPoolsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity.Paginator.ListIdentityPools.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/paginators/#listidentitypoolspaginator)
         """
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/paginator.pyi` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/paginator.py`

 * *Files 7% similar despite different names*

```diff
@@ -16,43 +16,40 @@
     session = get_session()
     with session.create_client("cognito-identity") as client:
         client: CognitoIdentityClient
 
         list_identity_pools_paginator: ListIdentityPoolsPaginator = client.get_paginator("list_identity_pools")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListIdentityPoolsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListIdentityPoolsPaginator",)
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListIdentityPoolsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity.Paginator.ListIdentityPools)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/paginators/#listidentitypoolspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentityPoolsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity.Paginator.ListIdentityPools.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/paginators/#listidentitypoolspaginator)
         """
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/type_defs.py` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -28,57 +28,57 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CognitoIdentityProviderTypeDef",
     "CredentialsTypeDef",
     "DeleteIdentitiesInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedIdentityIdTypeDef",
     "DeleteIdentityPoolInputRequestTypeDef",
     "DescribeIdentityInputRequestTypeDef",
     "DescribeIdentityPoolInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCredentialsForIdentityInputRequestTypeDef",
     "GetIdInputRequestTypeDef",
+    "GetIdResponseTypeDef",
     "GetIdentityPoolRolesInputRequestTypeDef",
     "GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef",
+    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
     "GetOpenIdTokenInputRequestTypeDef",
+    "GetOpenIdTokenResponseTypeDef",
     "GetPrincipalTagAttributeMapInputRequestTypeDef",
+    "GetPrincipalTagAttributeMapResponseTypeDef",
+    "IdentityDescriptionResponseMetadataTypeDef",
     "IdentityDescriptionTypeDef",
     "IdentityPoolShortDescriptionTypeDef",
     "ListIdentitiesInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
     "ListIdentityPoolsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "LookupDeveloperIdentityInputRequestTypeDef",
+    "LookupDeveloperIdentityResponseTypeDef",
     "MappingRuleTypeDef",
     "MergeDeveloperIdentitiesInputRequestTypeDef",
+    "MergeDeveloperIdentitiesResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SetPrincipalTagAttributeMapInputRequestTypeDef",
+    "SetPrincipalTagAttributeMapResponseTypeDef",
     "TagResourceInputRequestTypeDef",
     "UnlinkDeveloperIdentityInputRequestTypeDef",
     "UnlinkIdentityInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "CreateIdentityPoolInputRequestTypeDef",
     "IdentityPoolRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCredentialsForIdentityResponseTypeDef",
-    "GetIdResponseTypeDef",
-    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
-    "GetOpenIdTokenResponseTypeDef",
-    "GetPrincipalTagAttributeMapResponseTypeDef",
-    "IdentityDescriptionResponseMetadataTypeDef",
     "IdentityPoolTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "LookupDeveloperIdentityResponseTypeDef",
-    "MergeDeveloperIdentitiesResponseTypeDef",
-    "SetPrincipalTagAttributeMapResponseTypeDef",
+    "GetCredentialsForIdentityResponseTypeDef",
     "DeleteIdentitiesResponseTypeDef",
     "ListIdentitiesResponseTypeDef",
     "ListIdentityPoolsResponseTypeDef",
-    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
     "RulesConfigurationTypeTypeDef",
     "RoleMappingTypeDef",
     "GetIdentityPoolRolesResponseTypeDef",
     "SetIdentityPoolRolesInputRequestTypeDef",
 )
 
 CognitoIdentityProviderTypeDef = TypedDict(
@@ -105,25 +105,14 @@
 DeleteIdentitiesInputRequestTypeDef = TypedDict(
     "DeleteIdentitiesInputRequestTypeDef",
     {
         "IdentityIdsToDelete": Sequence[str],
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
 UnprocessedIdentityIdTypeDef = TypedDict(
     "UnprocessedIdentityIdTypeDef",
     {
         "IdentityId": str,
         "ErrorCode": ErrorCodeType,
     },
     total=False,
@@ -146,14 +135,21 @@
 DescribeIdentityPoolInputRequestTypeDef = TypedDict(
     "DescribeIdentityPoolInputRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetCredentialsForIdentityInputRequestTypeDef = TypedDict(
     "_RequiredGetCredentialsForIdentityInputRequestTypeDef",
     {
         "IdentityId": str,
     },
 )
 _OptionalGetCredentialsForIdentityInputRequestTypeDef = TypedDict(
@@ -191,14 +187,22 @@
 
 class GetIdInputRequestTypeDef(
     _RequiredGetIdInputRequestTypeDef, _OptionalGetIdInputRequestTypeDef
 ):
     pass
 
 
+GetIdResponseTypeDef = TypedDict(
+    "GetIdResponseTypeDef",
+    {
+        "IdentityId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIdentityPoolRolesInputRequestTypeDef = TypedDict(
     "GetIdentityPoolRolesInputRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
@@ -223,14 +227,23 @@
 class GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef(
     _RequiredGetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
     _OptionalGetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
 ):
     pass
 
 
+GetOpenIdTokenForDeveloperIdentityResponseTypeDef = TypedDict(
+    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
+    {
+        "IdentityId": str,
+        "Token": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetOpenIdTokenInputRequestTypeDef = TypedDict(
     "_RequiredGetOpenIdTokenInputRequestTypeDef",
     {
         "IdentityId": str,
     },
 )
 _OptionalGetOpenIdTokenInputRequestTypeDef = TypedDict(
@@ -244,22 +257,53 @@
 
 class GetOpenIdTokenInputRequestTypeDef(
     _RequiredGetOpenIdTokenInputRequestTypeDef, _OptionalGetOpenIdTokenInputRequestTypeDef
 ):
     pass
 
 
+GetOpenIdTokenResponseTypeDef = TypedDict(
+    "GetOpenIdTokenResponseTypeDef",
+    {
+        "IdentityId": str,
+        "Token": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPrincipalTagAttributeMapInputRequestTypeDef = TypedDict(
     "GetPrincipalTagAttributeMapInputRequestTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityProviderName": str,
     },
 )
 
+GetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
+    "GetPrincipalTagAttributeMapResponseTypeDef",
+    {
+        "IdentityPoolId": str,
+        "IdentityProviderName": str,
+        "UseDefaults": bool,
+        "PrincipalTags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+IdentityDescriptionResponseMetadataTypeDef = TypedDict(
+    "IdentityDescriptionResponseMetadataTypeDef",
+    {
+        "IdentityId": str,
+        "Logins": List[str],
+        "CreationDate": datetime,
+        "LastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IdentityDescriptionTypeDef = TypedDict(
     "IdentityDescriptionTypeDef",
     {
         "IdentityId": str,
         "Logins": List[str],
         "CreationDate": datetime,
         "LastModifiedDate": datetime,
@@ -295,20 +339,18 @@
 
 class ListIdentitiesInputRequestTypeDef(
     _RequiredListIdentitiesInputRequestTypeDef, _OptionalListIdentitiesInputRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef = TypedDict(
+    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 _RequiredListIdentityPoolsInputRequestTypeDef = TypedDict(
     "_RequiredListIdentityPoolsInputRequestTypeDef",
     {
@@ -333,14 +375,22 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredLookupDeveloperIdentityInputRequestTypeDef = TypedDict(
     "_RequiredLookupDeveloperIdentityInputRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 _OptionalLookupDeveloperIdentityInputRequestTypeDef = TypedDict(
@@ -358,14 +408,24 @@
 class LookupDeveloperIdentityInputRequestTypeDef(
     _RequiredLookupDeveloperIdentityInputRequestTypeDef,
     _OptionalLookupDeveloperIdentityInputRequestTypeDef,
 ):
     pass
 
 
+LookupDeveloperIdentityResponseTypeDef = TypedDict(
+    "LookupDeveloperIdentityResponseTypeDef",
+    {
+        "IdentityId": str,
+        "DeveloperUserIdentifierList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MappingRuleTypeDef = TypedDict(
     "MappingRuleTypeDef",
     {
         "Claim": str,
         "MatchType": MappingRuleMatchTypeType,
         "Value": str,
         "RoleARN": str,
@@ -378,14 +438,43 @@
         "SourceUserIdentifier": str,
         "DestinationUserIdentifier": str,
         "DeveloperProviderName": str,
         "IdentityPoolId": str,
     },
 )
 
+MergeDeveloperIdentitiesResponseTypeDef = TypedDict(
+    "MergeDeveloperIdentitiesResponseTypeDef",
+    {
+        "IdentityId": str,
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
 _RequiredSetPrincipalTagAttributeMapInputRequestTypeDef = TypedDict(
     "_RequiredSetPrincipalTagAttributeMapInputRequestTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityProviderName": str,
     },
 )
@@ -402,14 +491,25 @@
 class SetPrincipalTagAttributeMapInputRequestTypeDef(
     _RequiredSetPrincipalTagAttributeMapInputRequestTypeDef,
     _OptionalSetPrincipalTagAttributeMapInputRequestTypeDef,
 ):
     pass
 
 
+SetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
+    "SetPrincipalTagAttributeMapResponseTypeDef",
+    {
+        "IdentityPoolId": str,
+        "IdentityProviderName": str,
+        "UseDefaults": bool,
+        "PrincipalTags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -494,167 +594,67 @@
 
 class IdentityPoolRequestTypeDef(
     _RequiredIdentityPoolRequestTypeDef, _OptionalIdentityPoolRequestTypeDef
 ):
     pass
 
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCredentialsForIdentityResponseTypeDef = TypedDict(
-    "GetCredentialsForIdentityResponseTypeDef",
-    {
-        "IdentityId": str,
-        "Credentials": CredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIdResponseTypeDef = TypedDict(
-    "GetIdResponseTypeDef",
-    {
-        "IdentityId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOpenIdTokenForDeveloperIdentityResponseTypeDef = TypedDict(
-    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
-    {
-        "IdentityId": str,
-        "Token": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOpenIdTokenResponseTypeDef = TypedDict(
-    "GetOpenIdTokenResponseTypeDef",
-    {
-        "IdentityId": str,
-        "Token": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
-    "GetPrincipalTagAttributeMapResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "IdentityProviderName": str,
-        "UseDefaults": bool,
-        "PrincipalTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IdentityDescriptionResponseMetadataTypeDef = TypedDict(
-    "IdentityDescriptionResponseMetadataTypeDef",
-    {
-        "IdentityId": str,
-        "Logins": List[str],
-        "CreationDate": datetime,
-        "LastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 IdentityPoolTypeDef = TypedDict(
     "IdentityPoolTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityPoolName": str,
         "AllowUnauthenticatedIdentities": bool,
         "AllowClassicFlow": bool,
         "SupportedLoginProviders": Dict[str, str],
         "DeveloperProviderName": str,
         "OpenIdConnectProviderARNs": List[str],
         "CognitoIdentityProviders": List[CognitoIdentityProviderTypeDef],
         "SamlProviderARNs": List[str],
         "IdentityPoolTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-LookupDeveloperIdentityResponseTypeDef = TypedDict(
-    "LookupDeveloperIdentityResponseTypeDef",
-    {
-        "IdentityId": str,
-        "DeveloperUserIdentifierList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-MergeDeveloperIdentitiesResponseTypeDef = TypedDict(
-    "MergeDeveloperIdentitiesResponseTypeDef",
+GetCredentialsForIdentityResponseTypeDef = TypedDict(
+    "GetCredentialsForIdentityResponseTypeDef",
     {
         "IdentityId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
-    "SetPrincipalTagAttributeMapResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "IdentityProviderName": str,
-        "UseDefaults": bool,
-        "PrincipalTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Credentials": CredentialsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteIdentitiesResponseTypeDef = TypedDict(
     "DeleteIdentitiesResponseTypeDef",
     {
         "UnprocessedIdentityIds": List[UnprocessedIdentityIdTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentitiesResponseTypeDef = TypedDict(
     "ListIdentitiesResponseTypeDef",
     {
         "IdentityPoolId": str,
         "Identities": List[IdentityDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityPoolsResponseTypeDef = TypedDict(
     "ListIdentityPoolsResponseTypeDef",
     {
         "IdentityPools": List[IdentityPoolShortDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef = TypedDict(
-    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 RulesConfigurationTypeTypeDef = TypedDict(
     "RulesConfigurationTypeTypeDef",
     {
         "Rules": List[MappingRuleTypeDef],
     },
 )
 
@@ -680,15 +680,15 @@
 
 GetIdentityPoolRolesResponseTypeDef = TypedDict(
     "GetIdentityPoolRolesResponseTypeDef",
     {
         "IdentityPoolId": str,
         "Roles": Dict[str, str],
         "RoleMappings": Dict[str, RoleMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetIdentityPoolRolesInputRequestTypeDef = TypedDict(
     "_RequiredSetIdentityPoolRolesInputRequestTypeDef",
     {
         "IdentityPoolId": str,
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity/type_defs.pyi` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -27,57 +27,57 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CognitoIdentityProviderTypeDef",
     "CredentialsTypeDef",
     "DeleteIdentitiesInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedIdentityIdTypeDef",
     "DeleteIdentityPoolInputRequestTypeDef",
     "DescribeIdentityInputRequestTypeDef",
     "DescribeIdentityPoolInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCredentialsForIdentityInputRequestTypeDef",
     "GetIdInputRequestTypeDef",
+    "GetIdResponseTypeDef",
     "GetIdentityPoolRolesInputRequestTypeDef",
     "GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef",
+    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
     "GetOpenIdTokenInputRequestTypeDef",
+    "GetOpenIdTokenResponseTypeDef",
     "GetPrincipalTagAttributeMapInputRequestTypeDef",
+    "GetPrincipalTagAttributeMapResponseTypeDef",
+    "IdentityDescriptionResponseMetadataTypeDef",
     "IdentityDescriptionTypeDef",
     "IdentityPoolShortDescriptionTypeDef",
     "ListIdentitiesInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
     "ListIdentityPoolsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "LookupDeveloperIdentityInputRequestTypeDef",
+    "LookupDeveloperIdentityResponseTypeDef",
     "MappingRuleTypeDef",
     "MergeDeveloperIdentitiesInputRequestTypeDef",
+    "MergeDeveloperIdentitiesResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SetPrincipalTagAttributeMapInputRequestTypeDef",
+    "SetPrincipalTagAttributeMapResponseTypeDef",
     "TagResourceInputRequestTypeDef",
     "UnlinkDeveloperIdentityInputRequestTypeDef",
     "UnlinkIdentityInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "CreateIdentityPoolInputRequestTypeDef",
     "IdentityPoolRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCredentialsForIdentityResponseTypeDef",
-    "GetIdResponseTypeDef",
-    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
-    "GetOpenIdTokenResponseTypeDef",
-    "GetPrincipalTagAttributeMapResponseTypeDef",
-    "IdentityDescriptionResponseMetadataTypeDef",
     "IdentityPoolTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "LookupDeveloperIdentityResponseTypeDef",
-    "MergeDeveloperIdentitiesResponseTypeDef",
-    "SetPrincipalTagAttributeMapResponseTypeDef",
+    "GetCredentialsForIdentityResponseTypeDef",
     "DeleteIdentitiesResponseTypeDef",
     "ListIdentitiesResponseTypeDef",
     "ListIdentityPoolsResponseTypeDef",
-    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
     "RulesConfigurationTypeTypeDef",
     "RoleMappingTypeDef",
     "GetIdentityPoolRolesResponseTypeDef",
     "SetIdentityPoolRolesInputRequestTypeDef",
 )
 
 CognitoIdentityProviderTypeDef = TypedDict(
@@ -104,25 +104,14 @@
 DeleteIdentitiesInputRequestTypeDef = TypedDict(
     "DeleteIdentitiesInputRequestTypeDef",
     {
         "IdentityIdsToDelete": Sequence[str],
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
 UnprocessedIdentityIdTypeDef = TypedDict(
     "UnprocessedIdentityIdTypeDef",
     {
         "IdentityId": str,
         "ErrorCode": ErrorCodeType,
     },
     total=False,
@@ -145,14 +134,21 @@
 DescribeIdentityPoolInputRequestTypeDef = TypedDict(
     "DescribeIdentityPoolInputRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetCredentialsForIdentityInputRequestTypeDef = TypedDict(
     "_RequiredGetCredentialsForIdentityInputRequestTypeDef",
     {
         "IdentityId": str,
     },
 )
 _OptionalGetCredentialsForIdentityInputRequestTypeDef = TypedDict(
@@ -186,14 +182,22 @@
 )
 
 class GetIdInputRequestTypeDef(
     _RequiredGetIdInputRequestTypeDef, _OptionalGetIdInputRequestTypeDef
 ):
     pass
 
+GetIdResponseTypeDef = TypedDict(
+    "GetIdResponseTypeDef",
+    {
+        "IdentityId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIdentityPoolRolesInputRequestTypeDef = TypedDict(
     "GetIdentityPoolRolesInputRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
@@ -216,14 +220,23 @@
 
 class GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef(
     _RequiredGetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
     _OptionalGetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
 ):
     pass
 
+GetOpenIdTokenForDeveloperIdentityResponseTypeDef = TypedDict(
+    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
+    {
+        "IdentityId": str,
+        "Token": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetOpenIdTokenInputRequestTypeDef = TypedDict(
     "_RequiredGetOpenIdTokenInputRequestTypeDef",
     {
         "IdentityId": str,
     },
 )
 _OptionalGetOpenIdTokenInputRequestTypeDef = TypedDict(
@@ -235,22 +248,53 @@
 )
 
 class GetOpenIdTokenInputRequestTypeDef(
     _RequiredGetOpenIdTokenInputRequestTypeDef, _OptionalGetOpenIdTokenInputRequestTypeDef
 ):
     pass
 
+GetOpenIdTokenResponseTypeDef = TypedDict(
+    "GetOpenIdTokenResponseTypeDef",
+    {
+        "IdentityId": str,
+        "Token": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPrincipalTagAttributeMapInputRequestTypeDef = TypedDict(
     "GetPrincipalTagAttributeMapInputRequestTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityProviderName": str,
     },
 )
 
+GetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
+    "GetPrincipalTagAttributeMapResponseTypeDef",
+    {
+        "IdentityPoolId": str,
+        "IdentityProviderName": str,
+        "UseDefaults": bool,
+        "PrincipalTags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+IdentityDescriptionResponseMetadataTypeDef = TypedDict(
+    "IdentityDescriptionResponseMetadataTypeDef",
+    {
+        "IdentityId": str,
+        "Logins": List[str],
+        "CreationDate": datetime,
+        "LastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IdentityDescriptionTypeDef = TypedDict(
     "IdentityDescriptionTypeDef",
     {
         "IdentityId": str,
         "Logins": List[str],
         "CreationDate": datetime,
         "LastModifiedDate": datetime,
@@ -284,20 +328,18 @@
 )
 
 class ListIdentitiesInputRequestTypeDef(
     _RequiredListIdentitiesInputRequestTypeDef, _OptionalListIdentitiesInputRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef = TypedDict(
+    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 _RequiredListIdentityPoolsInputRequestTypeDef = TypedDict(
     "_RequiredListIdentityPoolsInputRequestTypeDef",
     {
@@ -320,14 +362,22 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredLookupDeveloperIdentityInputRequestTypeDef = TypedDict(
     "_RequiredLookupDeveloperIdentityInputRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 _OptionalLookupDeveloperIdentityInputRequestTypeDef = TypedDict(
@@ -343,14 +393,24 @@
 
 class LookupDeveloperIdentityInputRequestTypeDef(
     _RequiredLookupDeveloperIdentityInputRequestTypeDef,
     _OptionalLookupDeveloperIdentityInputRequestTypeDef,
 ):
     pass
 
+LookupDeveloperIdentityResponseTypeDef = TypedDict(
+    "LookupDeveloperIdentityResponseTypeDef",
+    {
+        "IdentityId": str,
+        "DeveloperUserIdentifierList": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MappingRuleTypeDef = TypedDict(
     "MappingRuleTypeDef",
     {
         "Claim": str,
         "MatchType": MappingRuleMatchTypeType,
         "Value": str,
         "RoleARN": str,
@@ -363,14 +423,43 @@
         "SourceUserIdentifier": str,
         "DestinationUserIdentifier": str,
         "DeveloperProviderName": str,
         "IdentityPoolId": str,
     },
 )
 
+MergeDeveloperIdentitiesResponseTypeDef = TypedDict(
+    "MergeDeveloperIdentitiesResponseTypeDef",
+    {
+        "IdentityId": str,
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
 _RequiredSetPrincipalTagAttributeMapInputRequestTypeDef = TypedDict(
     "_RequiredSetPrincipalTagAttributeMapInputRequestTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityProviderName": str,
     },
 )
@@ -385,14 +474,25 @@
 
 class SetPrincipalTagAttributeMapInputRequestTypeDef(
     _RequiredSetPrincipalTagAttributeMapInputRequestTypeDef,
     _OptionalSetPrincipalTagAttributeMapInputRequestTypeDef,
 ):
     pass
 
+SetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
+    "SetPrincipalTagAttributeMapResponseTypeDef",
+    {
+        "IdentityPoolId": str,
+        "IdentityProviderName": str,
+        "UseDefaults": bool,
+        "PrincipalTags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -473,167 +573,67 @@
 )
 
 class IdentityPoolRequestTypeDef(
     _RequiredIdentityPoolRequestTypeDef, _OptionalIdentityPoolRequestTypeDef
 ):
     pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCredentialsForIdentityResponseTypeDef = TypedDict(
-    "GetCredentialsForIdentityResponseTypeDef",
-    {
-        "IdentityId": str,
-        "Credentials": CredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIdResponseTypeDef = TypedDict(
-    "GetIdResponseTypeDef",
-    {
-        "IdentityId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOpenIdTokenForDeveloperIdentityResponseTypeDef = TypedDict(
-    "GetOpenIdTokenForDeveloperIdentityResponseTypeDef",
-    {
-        "IdentityId": str,
-        "Token": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOpenIdTokenResponseTypeDef = TypedDict(
-    "GetOpenIdTokenResponseTypeDef",
-    {
-        "IdentityId": str,
-        "Token": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
-    "GetPrincipalTagAttributeMapResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "IdentityProviderName": str,
-        "UseDefaults": bool,
-        "PrincipalTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IdentityDescriptionResponseMetadataTypeDef = TypedDict(
-    "IdentityDescriptionResponseMetadataTypeDef",
-    {
-        "IdentityId": str,
-        "Logins": List[str],
-        "CreationDate": datetime,
-        "LastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 IdentityPoolTypeDef = TypedDict(
     "IdentityPoolTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityPoolName": str,
         "AllowUnauthenticatedIdentities": bool,
         "AllowClassicFlow": bool,
         "SupportedLoginProviders": Dict[str, str],
         "DeveloperProviderName": str,
         "OpenIdConnectProviderARNs": List[str],
         "CognitoIdentityProviders": List[CognitoIdentityProviderTypeDef],
         "SamlProviderARNs": List[str],
         "IdentityPoolTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-LookupDeveloperIdentityResponseTypeDef = TypedDict(
-    "LookupDeveloperIdentityResponseTypeDef",
-    {
-        "IdentityId": str,
-        "DeveloperUserIdentifierList": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-MergeDeveloperIdentitiesResponseTypeDef = TypedDict(
-    "MergeDeveloperIdentitiesResponseTypeDef",
+GetCredentialsForIdentityResponseTypeDef = TypedDict(
+    "GetCredentialsForIdentityResponseTypeDef",
     {
         "IdentityId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetPrincipalTagAttributeMapResponseTypeDef = TypedDict(
-    "SetPrincipalTagAttributeMapResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "IdentityProviderName": str,
-        "UseDefaults": bool,
-        "PrincipalTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Credentials": CredentialsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteIdentitiesResponseTypeDef = TypedDict(
     "DeleteIdentitiesResponseTypeDef",
     {
         "UnprocessedIdentityIds": List[UnprocessedIdentityIdTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentitiesResponseTypeDef = TypedDict(
     "ListIdentitiesResponseTypeDef",
     {
         "IdentityPoolId": str,
         "Identities": List[IdentityDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityPoolsResponseTypeDef = TypedDict(
     "ListIdentityPoolsResponseTypeDef",
     {
         "IdentityPools": List[IdentityPoolShortDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef = TypedDict(
-    "ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 RulesConfigurationTypeTypeDef = TypedDict(
     "RulesConfigurationTypeTypeDef",
     {
         "Rules": List[MappingRuleTypeDef],
     },
 )
 
@@ -657,15 +657,15 @@
 
 GetIdentityPoolRolesResponseTypeDef = TypedDict(
     "GetIdentityPoolRolesResponseTypeDef",
     {
         "IdentityPoolId": str,
         "Roles": Dict[str, str],
         "RoleMappings": Dict[str, RoleMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetIdentityPoolRolesInputRequestTypeDef = TypedDict(
     "_RequiredSetIdentityPoolRolesInputRequestTypeDef",
     {
         "IdentityPoolId": str,
```

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/PKG-INFO` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cognito-identity
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CognitoIdentity 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CognitoIdentity 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cognito-identity"></a>
 
 # types-aiobotocore-cognito-identity
 
 [![PyPI - types-aiobotocore-cognito-identity](https://img.shields.io/pypi/v/types-aiobotocore-cognito-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-identity)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cognito-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-identity)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cognito-identity?color=blue)](https://pypistats.org/packages/types-aiobotocore-cognito-identity)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CognitoIdentity 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
+[aiobotocore.CognitoIdentity 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-identity.html#CognitoIdentity)
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
 [types-aiobotocore-cognito-identity docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_identity/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,57 +323,57 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cognito_identity.type_defs import (
     CognitoIdentityProviderTypeDef,
     CredentialsTypeDef,
     DeleteIdentitiesInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedIdentityIdTypeDef,
     DeleteIdentityPoolInputRequestTypeDef,
     DescribeIdentityInputRequestTypeDef,
     DescribeIdentityPoolInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCredentialsForIdentityInputRequestTypeDef,
     GetIdInputRequestTypeDef,
+    GetIdResponseTypeDef,
     GetIdentityPoolRolesInputRequestTypeDef,
     GetOpenIdTokenForDeveloperIdentityInputRequestTypeDef,
+    GetOpenIdTokenForDeveloperIdentityResponseTypeDef,
     GetOpenIdTokenInputRequestTypeDef,
+    GetOpenIdTokenResponseTypeDef,
     GetPrincipalTagAttributeMapInputRequestTypeDef,
+    GetPrincipalTagAttributeMapResponseTypeDef,
+    IdentityDescriptionResponseMetadataTypeDef,
     IdentityDescriptionTypeDef,
     IdentityPoolShortDescriptionTypeDef,
     ListIdentitiesInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef,
     ListIdentityPoolsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     LookupDeveloperIdentityInputRequestTypeDef,
+    LookupDeveloperIdentityResponseTypeDef,
     MappingRuleTypeDef,
     MergeDeveloperIdentitiesInputRequestTypeDef,
+    MergeDeveloperIdentitiesResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SetPrincipalTagAttributeMapInputRequestTypeDef,
+    SetPrincipalTagAttributeMapResponseTypeDef,
     TagResourceInputRequestTypeDef,
     UnlinkDeveloperIdentityInputRequestTypeDef,
     UnlinkIdentityInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     CreateIdentityPoolInputRequestTypeDef,
     IdentityPoolRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCredentialsForIdentityResponseTypeDef,
-    GetIdResponseTypeDef,
-    GetOpenIdTokenForDeveloperIdentityResponseTypeDef,
-    GetOpenIdTokenResponseTypeDef,
-    GetPrincipalTagAttributeMapResponseTypeDef,
-    IdentityDescriptionResponseMetadataTypeDef,
     IdentityPoolTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    LookupDeveloperIdentityResponseTypeDef,
-    MergeDeveloperIdentitiesResponseTypeDef,
-    SetPrincipalTagAttributeMapResponseTypeDef,
+    GetCredentialsForIdentityResponseTypeDef,
     DeleteIdentitiesResponseTypeDef,
     ListIdentitiesResponseTypeDef,
     ListIdentityPoolsResponseTypeDef,
-    ListIdentityPoolsInputListIdentityPoolsPaginateTypeDef,
     RulesConfigurationTypeTypeDef,
     RoleMappingTypeDef,
     GetIdentityPoolRolesResponseTypeDef,
     SetIdentityPoolRolesInputRequestTypeDef,
 )
 
 
@@ -384,43 +384,43 @@
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

### Comparing `types-aiobotocore-cognito-identity-2.5.0.post1/types_aiobotocore_cognito_identity.egg-info/SOURCES.txt` & `types-aiobotocore-cognito-identity-2.5.1/types_aiobotocore_cognito_identity.egg-info/SOURCES.txt`

 * *Files identical despite different names*

