# Comparing `tmp/types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-license-manager-user-subscriptions-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:54 2023, max compression
+gzip compressed data, was "types-aiobotocore-license-manager-user-subscriptions-2.5.1.tar", last modified: Wed Jun 28 01:43:45 2023, max compression
```

## Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1.tar` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.163371 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16529 2023-03-11 12:26:54.159371 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14853 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:54.163371 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2313 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.159371 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/
--rw-r--r--   0 runner    (1001) docker     (123)     1580 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1045 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15988 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15964 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8552 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8550 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6768 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6761 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    15849 2023-03-11 12:17:37.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15820 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.159371 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16529 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1326 2023-03-11 12:26:54.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       53 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.338166 types-aiobotocore-license-manager-user-subscriptions-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16548 2023-06-28 01:43:45.338166 types-aiobotocore-license-manager-user-subscriptions-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14878 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:45.338166 types-aiobotocore-license-manager-user-subscriptions-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2307 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.338166 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/
+-rw-r--r--   0 runner    (1001) docker     (123)     1580 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15988 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15964 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8761 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8759 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6656 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6650 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    15879 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15850 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:17.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.338166 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16548 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1326 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       53 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/LICENSE` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/PKG-INFO` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-license-manager-user-subscriptions
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-license-manager-user-subscriptions"></a>
 
 # types-aiobotocore-license-manager-user-subscriptions
 
 [![PyPI - types-aiobotocore-license-manager-user-subscriptions](https://img.shields.io/pypi/v/types-aiobotocore-license-manager-user-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-user-subscriptions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager-user-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-user-subscriptions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager-user-subscriptions?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager-user-subscriptions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManagerUserSubscriptions 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions)
+[aiobotocore.LicenseManagerUserSubscriptions 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions)
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
 [types-aiobotocore-license-manager-user-subscriptions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -341,26 +341,26 @@
 `types_aiobotocore_license_manager_user_subscriptions.type_defs` module
 contains structures and shapes assembled to typed dictionaries for additional
 type checking.
 
 ```python
 from types_aiobotocore_license_manager_user_subscriptions.type_defs import (
     ActiveDirectoryIdentityProviderTypeDef,
-    ResponseMetadataTypeDef,
     FilterTypeDef,
     SettingsTypeDef,
     InstanceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef,
     ListIdentityProvidersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateSettingsTypeDef,
     IdentityProviderTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
     ListInstancesResponseTypeDef,
-    ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
     AssociateUserRequestRequestTypeDef,
     DeregisterIdentityProviderRequestRequestTypeDef,
     DisassociateUserRequestRequestTypeDef,
     IdentityProviderSummaryTypeDef,
     InstanceUserSummaryTypeDef,
     ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
     ListProductSubscriptionsRequestRequestTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/README.md` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-license-manager-user-subscriptions"></a>
 
 # types-aiobotocore-license-manager-user-subscriptions
 
 [![PyPI - types-aiobotocore-license-manager-user-subscriptions](https://img.shields.io/pypi/v/types-aiobotocore-license-manager-user-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-user-subscriptions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager-user-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-user-subscriptions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager-user-subscriptions?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager-user-subscriptions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManagerUserSubscriptions 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions)
+[aiobotocore.LicenseManagerUserSubscriptions 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions)
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
 [types-aiobotocore-license-manager-user-subscriptions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -308,26 +308,26 @@
 `types_aiobotocore_license_manager_user_subscriptions.type_defs` module
 contains structures and shapes assembled to typed dictionaries for additional
 type checking.
 
 ```python
 from types_aiobotocore_license_manager_user_subscriptions.type_defs import (
     ActiveDirectoryIdentityProviderTypeDef,
-    ResponseMetadataTypeDef,
     FilterTypeDef,
     SettingsTypeDef,
     InstanceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef,
     ListIdentityProvidersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateSettingsTypeDef,
     IdentityProviderTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
     ListInstancesResponseTypeDef,
-    ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
     AssociateUserRequestRequestTypeDef,
     DeregisterIdentityProviderRequestRequestTypeDef,
     DisassociateUserRequestRequestTypeDef,
     IdentityProviderSummaryTypeDef,
     InstanceUserSummaryTypeDef,
     ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
     ListProductSubscriptionsRequestRequestTypeDef,
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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/setup.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-license-manager-user-subscriptions.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-license-manager-user-subscriptions",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_license_manager_user_subscriptions"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.0 service generated"
-        " with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.1 service generated"
+        " with mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/",
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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/__init__.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/__init__.pyi` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/__main__.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions\nOther"
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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/client.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/client.pyi` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/literals.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/literals.py`

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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/literals.pyi` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/literals.pyi`

 * *Files 4% similar despite different names*

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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/paginator.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,36 +22,29 @@
 
         list_identity_providers_paginator: ListIdentityProvidersPaginator = client.get_paginator("list_identity_providers")
         list_instances_paginator: ListInstancesPaginator = client.get_paginator("list_instances")
         list_product_subscriptions_paginator: ListProductSubscriptionsPaginator = client.get_paginator("list_product_subscriptions")
         list_user_associations_paginator: ListUserAssociationsPaginator = client.get_paginator("list_user_associations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     IdentityProviderTypeDef,
     ListIdentityProvidersResponseTypeDef,
     ListInstancesResponseTypeDef,
     ListProductSubscriptionsResponseTypeDef,
     ListUserAssociationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListIdentityProvidersPaginator",
     "ListInstancesPaginator",
     "ListProductSubscriptionsPaginator",
     "ListUserAssociationsPaginator",
 )
 
@@ -69,15 +62,15 @@
 class ListIdentityProvidersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListIdentityProviders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listidentityproviderspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentityProvidersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListIdentityProviders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listidentityproviderspaginator)
         """
 
 
@@ -87,15 +80,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listinstancespaginator)
         """
 
 
@@ -107,15 +100,15 @@
 
     def paginate(
         self,
         *,
         IdentityProvider: IdentityProviderTypeDef,
         Product: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProductSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListProductSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listproductsubscriptionspaginator)
         """
 
 
@@ -127,13 +120,13 @@
 
     def paginate(
         self,
         *,
         IdentityProvider: IdentityProviderTypeDef,
         InstanceId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListUserAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listuserassociationspaginator)
         """
```

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/paginator.pyi` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,29 @@
 
         list_identity_providers_paginator: ListIdentityProvidersPaginator = client.get_paginator("list_identity_providers")
         list_instances_paginator: ListInstancesPaginator = client.get_paginator("list_instances")
         list_product_subscriptions_paginator: ListProductSubscriptionsPaginator = client.get_paginator("list_product_subscriptions")
         list_user_associations_paginator: ListUserAssociationsPaginator = client.get_paginator("list_user_associations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     IdentityProviderTypeDef,
     ListIdentityProvidersResponseTypeDef,
     ListInstancesResponseTypeDef,
     ListProductSubscriptionsResponseTypeDef,
     ListUserAssociationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListIdentityProvidersPaginator",
     "ListInstancesPaginator",
     "ListProductSubscriptionsPaginator",
     "ListUserAssociationsPaginator",
 )
 
@@ -65,15 +59,15 @@
 class ListIdentityProvidersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListIdentityProviders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listidentityproviderspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentityProvidersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListIdentityProviders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listidentityproviderspaginator)
         """
 
 class ListInstancesPaginator(AioPaginator):
@@ -82,15 +76,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listinstancespaginator)
         """
 
 class ListProductSubscriptionsPaginator(AioPaginator):
@@ -101,15 +95,15 @@
 
     def paginate(
         self,
         *,
         IdentityProvider: IdentityProviderTypeDef,
         Product: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProductSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListProductSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listproductsubscriptionspaginator)
         """
 
 class ListUserAssociationsPaginator(AioPaginator):
@@ -120,13 +114,13 @@
 
     def paginate(
         self,
         *,
         IdentityProvider: IdentityProviderTypeDef,
         InstanceId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions.Paginator.ListUserAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/paginators/#listuserassociationspaginator)
         """
```

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/type_defs.py` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -15,29 +15,28 @@
 from typing import Dict, List, Sequence
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ActiveDirectoryIdentityProviderTypeDef",
-    "ResponseMetadataTypeDef",
     "FilterTypeDef",
     "SettingsTypeDef",
     "InstanceSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
     "ListIdentityProvidersRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateSettingsTypeDef",
     "IdentityProviderTypeDef",
+    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListInstancesRequestRequestTypeDef",
     "ListInstancesResponseTypeDef",
-    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
-    "ListInstancesRequestListInstancesPaginateTypeDef",
     "AssociateUserRequestRequestTypeDef",
     "DeregisterIdentityProviderRequestRequestTypeDef",
     "DisassociateUserRequestRequestTypeDef",
     "IdentityProviderSummaryTypeDef",
     "InstanceUserSummaryTypeDef",
     "ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef",
     "ListProductSubscriptionsRequestRequestTypeDef",
@@ -64,25 +63,14 @@
     "ActiveDirectoryIdentityProviderTypeDef",
     {
         "DirectoryId": str,
     },
     total=False,
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
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Attribute": str,
         "Operation": str,
         "Value": str,
     },
@@ -110,36 +98,53 @@
     {
         "LastStatusCheckDate": str,
         "StatusMessage": str,
     },
     total=False,
 )
 
-
 class InstanceSummaryTypeDef(_RequiredInstanceSummaryTypeDef, _OptionalInstanceSummaryTypeDef):
     pass
 
+ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef = TypedDict(
+    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListIdentityProvidersRequestRequestTypeDef = TypedDict(
+    "ListIdentityProvidersRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
 
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
 )
 
-ListIdentityProvidersRequestRequestTypeDef = TypedDict(
-    "ListIdentityProvidersRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "MaxResults": int,
-        "NextToken": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
 _RequiredUpdateSettingsTypeDef = TypedDict(
     "_RequiredUpdateSettingsTypeDef",
     {
         "AddSubnets": Sequence[str],
         "RemoveSubnets": Sequence[str],
@@ -149,27 +154,34 @@
     "_OptionalUpdateSettingsTypeDef",
     {
         "SecurityGroupId": str,
     },
     total=False,
 )
 
-
 class UpdateSettingsTypeDef(_RequiredUpdateSettingsTypeDef, _OptionalUpdateSettingsTypeDef):
     pass
 
-
 IdentityProviderTypeDef = TypedDict(
     "IdentityProviderTypeDef",
     {
         "ActiveDirectoryIdentityProvider": ActiveDirectoryIdentityProviderTypeDef,
     },
     total=False,
 )
 
+ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "ListInstancesRequestListInstancesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstancesRequestRequestTypeDef = TypedDict(
     "ListInstancesRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -177,33 +189,16 @@
 )
 
 ListInstancesResponseTypeDef = TypedDict(
     "ListInstancesResponseTypeDef",
     {
         "InstanceSummaries": List[InstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef = TypedDict(
-    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "ListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredAssociateUserRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateUserRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
@@ -214,21 +209,19 @@
     "_OptionalAssociateUserRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
-
 class AssociateUserRequestRequestTypeDef(
     _RequiredAssociateUserRequestRequestTypeDef, _OptionalAssociateUserRequestRequestTypeDef
 ):
     pass
 
-
 DeregisterIdentityProviderRequestRequestTypeDef = TypedDict(
     "DeregisterIdentityProviderRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
@@ -245,21 +238,19 @@
     "_OptionalDisassociateUserRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
-
 class DisassociateUserRequestRequestTypeDef(
     _RequiredDisassociateUserRequestRequestTypeDef, _OptionalDisassociateUserRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredIdentityProviderSummaryTypeDef = TypedDict(
     "_RequiredIdentityProviderSummaryTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Settings": SettingsTypeDef,
         "Status": str,
@@ -269,21 +260,19 @@
     "_OptionalIdentityProviderSummaryTypeDef",
     {
         "FailureMessage": str,
     },
     total=False,
 )
 
-
 class IdentityProviderSummaryTypeDef(
     _RequiredIdentityProviderSummaryTypeDef, _OptionalIdentityProviderSummaryTypeDef
 ):
     pass
 
-
 _RequiredInstanceUserSummaryTypeDef = TypedDict(
     "_RequiredInstanceUserSummaryTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
         "Status": str,
         "Username": str,
@@ -296,45 +285,41 @@
         "DisassociationDate": str,
         "Domain": str,
         "StatusMessage": str,
     },
     total=False,
 )
 
-
 class InstanceUserSummaryTypeDef(
     _RequiredInstanceUserSummaryTypeDef, _OptionalInstanceUserSummaryTypeDef
 ):
     pass
 
-
 _RequiredListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef = TypedDict(
     "_RequiredListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
 _OptionalListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef = TypedDict(
     "_OptionalListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef(
     _RequiredListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
     _OptionalListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListProductSubscriptionsRequestRequestTypeDef = TypedDict(
     "_RequiredListProductSubscriptionsRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
@@ -344,46 +329,42 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListProductSubscriptionsRequestRequestTypeDef(
     _RequiredListProductSubscriptionsRequestRequestTypeDef,
     _OptionalListProductSubscriptionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListUserAssociationsRequestListUserAssociationsPaginateTypeDef = TypedDict(
     "_RequiredListUserAssociationsRequestListUserAssociationsPaginateTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
     },
 )
 _OptionalListUserAssociationsRequestListUserAssociationsPaginateTypeDef = TypedDict(
     "_OptionalListUserAssociationsRequestListUserAssociationsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListUserAssociationsRequestListUserAssociationsPaginateTypeDef(
     _RequiredListUserAssociationsRequestListUserAssociationsPaginateTypeDef,
     _OptionalListUserAssociationsRequestListUserAssociationsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListUserAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredListUserAssociationsRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
     },
 )
@@ -393,22 +374,20 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListUserAssociationsRequestRequestTypeDef(
     _RequiredListUserAssociationsRequestRequestTypeDef,
     _OptionalListUserAssociationsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredProductUserSummaryTypeDef = TypedDict(
     "_RequiredProductUserSummaryTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Status": str,
         "Username": str,
@@ -421,21 +400,19 @@
         "StatusMessage": str,
         "SubscriptionEndDate": str,
         "SubscriptionStartDate": str,
     },
     total=False,
 )
 
-
 class ProductUserSummaryTypeDef(
     _RequiredProductUserSummaryTypeDef, _OptionalProductUserSummaryTypeDef
 ):
     pass
 
-
 _RequiredRegisterIdentityProviderRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterIdentityProviderRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
@@ -443,22 +420,20 @@
     "_OptionalRegisterIdentityProviderRequestRequestTypeDef",
     {
         "Settings": SettingsTypeDef,
     },
     total=False,
 )
 
-
 class RegisterIdentityProviderRequestRequestTypeDef(
     _RequiredRegisterIdentityProviderRequestRequestTypeDef,
     _OptionalRegisterIdentityProviderRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartProductSubscriptionRequestRequestTypeDef = TypedDict(
     "_RequiredStartProductSubscriptionRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Username": str,
     },
@@ -467,22 +442,20 @@
     "_OptionalStartProductSubscriptionRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
-
 class StartProductSubscriptionRequestRequestTypeDef(
     _RequiredStartProductSubscriptionRequestRequestTypeDef,
     _OptionalStartProductSubscriptionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStopProductSubscriptionRequestRequestTypeDef = TypedDict(
     "_RequiredStopProductSubscriptionRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Username": str,
     },
@@ -491,106 +464,104 @@
     "_OptionalStopProductSubscriptionRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
-
 class StopProductSubscriptionRequestRequestTypeDef(
     _RequiredStopProductSubscriptionRequestRequestTypeDef,
     _OptionalStopProductSubscriptionRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateIdentityProviderSettingsRequestRequestTypeDef = TypedDict(
     "UpdateIdentityProviderSettingsRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "UpdateSettings": UpdateSettingsTypeDef,
     },
 )
 
 DeregisterIdentityProviderResponseTypeDef = TypedDict(
     "DeregisterIdentityProviderResponseTypeDef",
     {
         "IdentityProviderSummary": IdentityProviderSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityProvidersResponseTypeDef = TypedDict(
     "ListIdentityProvidersResponseTypeDef",
     {
         "IdentityProviderSummaries": List[IdentityProviderSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterIdentityProviderResponseTypeDef = TypedDict(
     "RegisterIdentityProviderResponseTypeDef",
     {
         "IdentityProviderSummary": IdentityProviderSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateIdentityProviderSettingsResponseTypeDef = TypedDict(
     "UpdateIdentityProviderSettingsResponseTypeDef",
     {
         "IdentityProviderSummary": IdentityProviderSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateUserResponseTypeDef = TypedDict(
     "AssociateUserResponseTypeDef",
     {
         "InstanceUserSummary": InstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateUserResponseTypeDef = TypedDict(
     "DisassociateUserResponseTypeDef",
     {
         "InstanceUserSummary": InstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserAssociationsResponseTypeDef = TypedDict(
     "ListUserAssociationsResponseTypeDef",
     {
         "InstanceUserSummaries": List[InstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProductSubscriptionsResponseTypeDef = TypedDict(
     "ListProductSubscriptionsResponseTypeDef",
     {
         "NextToken": str,
         "ProductUserSummaries": List[ProductUserSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartProductSubscriptionResponseTypeDef = TypedDict(
     "StartProductSubscriptionResponseTypeDef",
     {
         "ProductUserSummary": ProductUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopProductSubscriptionResponseTypeDef = TypedDict(
     "StopProductSubscriptionResponseTypeDef",
     {
         "ProductUserSummary": ProductUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions/type_defs.pyi` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -15,28 +15,29 @@
 from typing import Dict, List, Sequence
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ActiveDirectoryIdentityProviderTypeDef",
-    "ResponseMetadataTypeDef",
     "FilterTypeDef",
     "SettingsTypeDef",
     "InstanceSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
     "ListIdentityProvidersRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateSettingsTypeDef",
     "IdentityProviderTypeDef",
+    "ListInstancesRequestListInstancesPaginateTypeDef",
     "ListInstancesRequestRequestTypeDef",
     "ListInstancesResponseTypeDef",
-    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
-    "ListInstancesRequestListInstancesPaginateTypeDef",
     "AssociateUserRequestRequestTypeDef",
     "DeregisterIdentityProviderRequestRequestTypeDef",
     "DisassociateUserRequestRequestTypeDef",
     "IdentityProviderSummaryTypeDef",
     "InstanceUserSummaryTypeDef",
     "ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef",
     "ListProductSubscriptionsRequestRequestTypeDef",
@@ -63,25 +64,14 @@
     "ActiveDirectoryIdentityProviderTypeDef",
     {
         "DirectoryId": str,
     },
     total=False,
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
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Attribute": str,
         "Operation": str,
         "Value": str,
     },
@@ -109,36 +99,57 @@
     {
         "LastStatusCheckDate": str,
         "StatusMessage": str,
     },
     total=False,
 )
 
+
 class InstanceSummaryTypeDef(_RequiredInstanceSummaryTypeDef, _OptionalInstanceSummaryTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef = TypedDict(
+    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListIdentityProvidersRequestRequestTypeDef = TypedDict(
     "ListIdentityProvidersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
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
 _RequiredUpdateSettingsTypeDef = TypedDict(
     "_RequiredUpdateSettingsTypeDef",
     {
         "AddSubnets": Sequence[str],
         "RemoveSubnets": Sequence[str],
     },
 )
@@ -146,25 +157,36 @@
     "_OptionalUpdateSettingsTypeDef",
     {
         "SecurityGroupId": str,
     },
     total=False,
 )
 
+
 class UpdateSettingsTypeDef(_RequiredUpdateSettingsTypeDef, _OptionalUpdateSettingsTypeDef):
     pass
 
+
 IdentityProviderTypeDef = TypedDict(
     "IdentityProviderTypeDef",
     {
         "ActiveDirectoryIdentityProvider": ActiveDirectoryIdentityProviderTypeDef,
     },
     total=False,
 )
 
+ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
+    "ListInstancesRequestListInstancesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstancesRequestRequestTypeDef = TypedDict(
     "ListInstancesRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -172,35 +194,18 @@
 )
 
 ListInstancesResponseTypeDef = TypedDict(
     "ListInstancesResponseTypeDef",
     {
         "InstanceSummaries": List[InstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef = TypedDict(
-    "ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInstancesRequestListInstancesPaginateTypeDef = TypedDict(
-    "ListInstancesRequestListInstancesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredAssociateUserRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateUserRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
         "Username": str,
     },
@@ -209,19 +214,21 @@
     "_OptionalAssociateUserRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
+
 class AssociateUserRequestRequestTypeDef(
     _RequiredAssociateUserRequestRequestTypeDef, _OptionalAssociateUserRequestRequestTypeDef
 ):
     pass
 
+
 DeregisterIdentityProviderRequestRequestTypeDef = TypedDict(
     "DeregisterIdentityProviderRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
@@ -238,19 +245,21 @@
     "_OptionalDisassociateUserRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
+
 class DisassociateUserRequestRequestTypeDef(
     _RequiredDisassociateUserRequestRequestTypeDef, _OptionalDisassociateUserRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredIdentityProviderSummaryTypeDef = TypedDict(
     "_RequiredIdentityProviderSummaryTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Settings": SettingsTypeDef,
         "Status": str,
@@ -260,19 +269,21 @@
     "_OptionalIdentityProviderSummaryTypeDef",
     {
         "FailureMessage": str,
     },
     total=False,
 )
 
+
 class IdentityProviderSummaryTypeDef(
     _RequiredIdentityProviderSummaryTypeDef, _OptionalIdentityProviderSummaryTypeDef
 ):
     pass
 
+
 _RequiredInstanceUserSummaryTypeDef = TypedDict(
     "_RequiredInstanceUserSummaryTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
         "Status": str,
         "Username": str,
@@ -285,41 +296,45 @@
         "DisassociationDate": str,
         "Domain": str,
         "StatusMessage": str,
     },
     total=False,
 )
 
+
 class InstanceUserSummaryTypeDef(
     _RequiredInstanceUserSummaryTypeDef, _OptionalInstanceUserSummaryTypeDef
 ):
     pass
 
+
 _RequiredListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef = TypedDict(
     "_RequiredListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
 _OptionalListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef = TypedDict(
     "_OptionalListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef(
     _RequiredListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
     _OptionalListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListProductSubscriptionsRequestRequestTypeDef = TypedDict(
     "_RequiredListProductSubscriptionsRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
@@ -329,42 +344,46 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListProductSubscriptionsRequestRequestTypeDef(
     _RequiredListProductSubscriptionsRequestRequestTypeDef,
     _OptionalListProductSubscriptionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListUserAssociationsRequestListUserAssociationsPaginateTypeDef = TypedDict(
     "_RequiredListUserAssociationsRequestListUserAssociationsPaginateTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
     },
 )
 _OptionalListUserAssociationsRequestListUserAssociationsPaginateTypeDef = TypedDict(
     "_OptionalListUserAssociationsRequestListUserAssociationsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListUserAssociationsRequestListUserAssociationsPaginateTypeDef(
     _RequiredListUserAssociationsRequestListUserAssociationsPaginateTypeDef,
     _OptionalListUserAssociationsRequestListUserAssociationsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListUserAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredListUserAssociationsRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "InstanceId": str,
     },
 )
@@ -374,20 +393,22 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListUserAssociationsRequestRequestTypeDef(
     _RequiredListUserAssociationsRequestRequestTypeDef,
     _OptionalListUserAssociationsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredProductUserSummaryTypeDef = TypedDict(
     "_RequiredProductUserSummaryTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Status": str,
         "Username": str,
@@ -400,19 +421,21 @@
         "StatusMessage": str,
         "SubscriptionEndDate": str,
         "SubscriptionStartDate": str,
     },
     total=False,
 )
 
+
 class ProductUserSummaryTypeDef(
     _RequiredProductUserSummaryTypeDef, _OptionalProductUserSummaryTypeDef
 ):
     pass
 
+
 _RequiredRegisterIdentityProviderRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterIdentityProviderRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
     },
 )
@@ -420,20 +443,22 @@
     "_OptionalRegisterIdentityProviderRequestRequestTypeDef",
     {
         "Settings": SettingsTypeDef,
     },
     total=False,
 )
 
+
 class RegisterIdentityProviderRequestRequestTypeDef(
     _RequiredRegisterIdentityProviderRequestRequestTypeDef,
     _OptionalRegisterIdentityProviderRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartProductSubscriptionRequestRequestTypeDef = TypedDict(
     "_RequiredStartProductSubscriptionRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Username": str,
     },
@@ -442,20 +467,22 @@
     "_OptionalStartProductSubscriptionRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
+
 class StartProductSubscriptionRequestRequestTypeDef(
     _RequiredStartProductSubscriptionRequestRequestTypeDef,
     _OptionalStartProductSubscriptionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStopProductSubscriptionRequestRequestTypeDef = TypedDict(
     "_RequiredStopProductSubscriptionRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "Username": str,
     },
@@ -464,104 +491,106 @@
     "_OptionalStopProductSubscriptionRequestRequestTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
 
+
 class StopProductSubscriptionRequestRequestTypeDef(
     _RequiredStopProductSubscriptionRequestRequestTypeDef,
     _OptionalStopProductSubscriptionRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateIdentityProviderSettingsRequestRequestTypeDef = TypedDict(
     "UpdateIdentityProviderSettingsRequestRequestTypeDef",
     {
         "IdentityProvider": IdentityProviderTypeDef,
         "Product": str,
         "UpdateSettings": UpdateSettingsTypeDef,
     },
 )
 
 DeregisterIdentityProviderResponseTypeDef = TypedDict(
     "DeregisterIdentityProviderResponseTypeDef",
     {
         "IdentityProviderSummary": IdentityProviderSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityProvidersResponseTypeDef = TypedDict(
     "ListIdentityProvidersResponseTypeDef",
     {
         "IdentityProviderSummaries": List[IdentityProviderSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterIdentityProviderResponseTypeDef = TypedDict(
     "RegisterIdentityProviderResponseTypeDef",
     {
         "IdentityProviderSummary": IdentityProviderSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateIdentityProviderSettingsResponseTypeDef = TypedDict(
     "UpdateIdentityProviderSettingsResponseTypeDef",
     {
         "IdentityProviderSummary": IdentityProviderSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateUserResponseTypeDef = TypedDict(
     "AssociateUserResponseTypeDef",
     {
         "InstanceUserSummary": InstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateUserResponseTypeDef = TypedDict(
     "DisassociateUserResponseTypeDef",
     {
         "InstanceUserSummary": InstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserAssociationsResponseTypeDef = TypedDict(
     "ListUserAssociationsResponseTypeDef",
     {
         "InstanceUserSummaries": List[InstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProductSubscriptionsResponseTypeDef = TypedDict(
     "ListProductSubscriptionsResponseTypeDef",
     {
         "NextToken": str,
         "ProductUserSummaries": List[ProductUserSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartProductSubscriptionResponseTypeDef = TypedDict(
     "StartProductSubscriptionResponseTypeDef",
     {
         "ProductUserSummary": ProductUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopProductSubscriptionResponseTypeDef = TypedDict(
     "StopProductSubscriptionResponseTypeDef",
     {
         "ProductUserSummary": ProductUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/PKG-INFO` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-license-manager-user-subscriptions
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LicenseManagerUserSubscriptions 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-license-manager-user-subscriptions"></a>
 
 # types-aiobotocore-license-manager-user-subscriptions
 
 [![PyPI - types-aiobotocore-license-manager-user-subscriptions](https://img.shields.io/pypi/v/types-aiobotocore-license-manager-user-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-user-subscriptions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager-user-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-user-subscriptions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager-user-subscriptions?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager-user-subscriptions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManagerUserSubscriptions 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions)
+[aiobotocore.LicenseManagerUserSubscriptions 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-user-subscriptions.html#LicenseManagerUserSubscriptions)
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
 [types-aiobotocore-license-manager-user-subscriptions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_user_subscriptions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -341,26 +341,26 @@
 `types_aiobotocore_license_manager_user_subscriptions.type_defs` module
 contains structures and shapes assembled to typed dictionaries for additional
 type checking.
 
 ```python
 from types_aiobotocore_license_manager_user_subscriptions.type_defs import (
     ActiveDirectoryIdentityProviderTypeDef,
-    ResponseMetadataTypeDef,
     FilterTypeDef,
     SettingsTypeDef,
     InstanceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef,
     ListIdentityProvidersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateSettingsTypeDef,
     IdentityProviderTypeDef,
+    ListInstancesRequestListInstancesPaginateTypeDef,
     ListInstancesRequestRequestTypeDef,
     ListInstancesResponseTypeDef,
-    ListIdentityProvidersRequestListIdentityProvidersPaginateTypeDef,
-    ListInstancesRequestListInstancesPaginateTypeDef,
     AssociateUserRequestRequestTypeDef,
     DeregisterIdentityProviderRequestRequestTypeDef,
     DisassociateUserRequestRequestTypeDef,
     IdentityProviderSummaryTypeDef,
     InstanceUserSummaryTypeDef,
     ListProductSubscriptionsRequestListProductSubscriptionsPaginateTypeDef,
     ListProductSubscriptionsRequestRequestTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-license-manager-user-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_user_subscriptions.egg-info/SOURCES.txt` & `types-aiobotocore-license-manager-user-subscriptions-2.5.1/types_aiobotocore_license_manager_user_subscriptions.egg-info/SOURCES.txt`

 * *Files identical despite different names*

