# Comparing `tmp/types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-license-manager-linux-subscriptions-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:53 2023, max compression
+gzip compressed data, was "types-aiobotocore-license-manager-linux-subscriptions-2.5.1.tar", last modified: Wed Jun 28 01:43:45 2023, max compression
```

## Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1.tar` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.967369 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15411 2023-03-11 12:26:53.963369 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13731 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:53.967369 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2320 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.963369 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/
--rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1049 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9217 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9202 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8599 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8597 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4130 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4125 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5829 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5826 2023-03-11 12:17:36.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:35.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.963369 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15411 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       54 2023-03-11 12:26:53.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.190166 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15431 2023-06-28 01:43:45.182166 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13757 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:45.190166 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2314 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.182166 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/
+-rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1037 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9217 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9202 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8999 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8997 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4014 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4010 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5841 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5838 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:16.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.182166 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15431 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 01:43:45.000000 types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/LICENSE` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/PKG-INFO` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-license-manager-linux-subscriptions
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-license-manager-linux-subscriptions"></a>
 
 # types-aiobotocore-license-manager-linux-subscriptions
 
 [![PyPI - types-aiobotocore-license-manager-linux-subscriptions](https://img.shields.io/pypi/v/types-aiobotocore-license-manager-linux-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-linux-subscriptions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager-linux-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-linux-subscriptions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager-linux-subscriptions?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager-linux-subscriptions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions)
+[aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions)
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
 [types-aiobotocore-license-manager-linux-subscriptions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,26 +339,26 @@
 contains structures and shapes assembled to typed dictionaries for additional
 type checking.
 
 ```python
 from types_aiobotocore_license_manager_linux_subscriptions.type_defs import (
     FilterTypeDef,
     LinuxSubscriptionsDiscoverySettingsTypeDef,
-    ResponseMetadataTypeDef,
     InstanceTypeDef,
-    PaginatorConfigTypeDef,
     SubscriptionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef,
     ListLinuxSubscriptionInstancesRequestRequestTypeDef,
+    ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef,
     ListLinuxSubscriptionsRequestRequestTypeDef,
-    UpdateServiceSettingsRequestRequestTypeDef,
     GetServiceSettingsResponseTypeDef,
+    UpdateServiceSettingsRequestRequestTypeDef,
     UpdateServiceSettingsResponseTypeDef,
     ListLinuxSubscriptionInstancesResponseTypeDef,
-    ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef,
-    ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef,
     ListLinuxSubscriptionsResponseTypeDef,
 )
 
 
 def get_structure() -> FilterTypeDef:
     return {...}
 ```
@@ -366,43 +366,43 @@
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

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/README.md` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-license-manager-linux-subscriptions"></a>
 
 # types-aiobotocore-license-manager-linux-subscriptions
 
 [![PyPI - types-aiobotocore-license-manager-linux-subscriptions](https://img.shields.io/pypi/v/types-aiobotocore-license-manager-linux-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-linux-subscriptions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager-linux-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-linux-subscriptions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager-linux-subscriptions?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager-linux-subscriptions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions)
+[aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions)
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
 [types-aiobotocore-license-manager-linux-subscriptions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,26 +306,26 @@
 contains structures and shapes assembled to typed dictionaries for additional
 type checking.
 
 ```python
 from types_aiobotocore_license_manager_linux_subscriptions.type_defs import (
     FilterTypeDef,
     LinuxSubscriptionsDiscoverySettingsTypeDef,
-    ResponseMetadataTypeDef,
     InstanceTypeDef,
-    PaginatorConfigTypeDef,
     SubscriptionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef,
     ListLinuxSubscriptionInstancesRequestRequestTypeDef,
+    ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef,
     ListLinuxSubscriptionsRequestRequestTypeDef,
-    UpdateServiceSettingsRequestRequestTypeDef,
     GetServiceSettingsResponseTypeDef,
+    UpdateServiceSettingsRequestRequestTypeDef,
     UpdateServiceSettingsResponseTypeDef,
     ListLinuxSubscriptionInstancesResponseTypeDef,
-    ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef,
-    ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef,
     ListLinuxSubscriptionsResponseTypeDef,
 )
 
 
 def get_structure() -> FilterTypeDef:
     return {...}
 ```
@@ -333,43 +333,43 @@
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

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/setup.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-license-manager-linux-subscriptions.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-license-manager-linux-subscriptions",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_license_manager_linux_subscriptions"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0 service generated"
-        " with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1 service generated"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/",
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

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/__init__.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/__init__.pyi` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/__main__.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/__main__.py`

 * *Files 7% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions\nOther"
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

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/client.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/client.pyi` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/literals.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,30 +14,28 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "LinuxSubscriptionsDiscoveryType",
     "ListLinuxSubscriptionInstancesPaginatorName",
     "ListLinuxSubscriptionsPaginatorName",
     "OperatorType",
     "OrganizationIntegrationType",
     "StatusType",
     "LicenseManagerLinuxSubscriptionsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 LinuxSubscriptionsDiscoveryType = Literal["Disabled", "Enabled"]
 ListLinuxSubscriptionInstancesPaginatorName = Literal["list_linux_subscription_instances"]
 ListLinuxSubscriptionsPaginatorName = Literal["list_linux_subscriptions"]
 OperatorType = Literal["Contains", "Equal", "NotEqual"]
 OrganizationIntegrationType = Literal["Disabled", "Enabled"]
 StatusType = Literal["Completed", "Failed", "InProgress", "Successful"]
 LicenseManagerLinuxSubscriptionsServiceName = Literal["license-manager-linux-subscriptions"]
@@ -99,14 +97,15 @@
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
@@ -185,14 +184,15 @@
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
@@ -203,14 +203,15 @@
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
@@ -246,14 +247,15 @@
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
@@ -272,16 +274,19 @@
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
@@ -365,15 +370,17 @@
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
@@ -393,25 +400,35 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_linux_subscription_instances", "list_linux_subscriptions"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
+    "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
+    "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/literals.pyi` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,28 +14,30 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "LinuxSubscriptionsDiscoveryType",
     "ListLinuxSubscriptionInstancesPaginatorName",
     "ListLinuxSubscriptionsPaginatorName",
     "OperatorType",
     "OrganizationIntegrationType",
     "StatusType",
     "LicenseManagerLinuxSubscriptionsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 LinuxSubscriptionsDiscoveryType = Literal["Disabled", "Enabled"]
 ListLinuxSubscriptionInstancesPaginatorName = Literal["list_linux_subscription_instances"]
 ListLinuxSubscriptionsPaginatorName = Literal["list_linux_subscriptions"]
 OperatorType = Literal["Contains", "Equal", "NotEqual"]
 OrganizationIntegrationType = Literal["Disabled", "Enabled"]
 StatusType = Literal["Completed", "Failed", "InProgress", "Successful"]
 LicenseManagerLinuxSubscriptionsServiceName = Literal["license-manager-linux-subscriptions"]
@@ -97,14 +99,15 @@
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
@@ -183,14 +186,15 @@
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
@@ -201,14 +205,15 @@
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
@@ -244,14 +249,15 @@
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
@@ -270,16 +276,19 @@
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
@@ -363,15 +372,17 @@
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
@@ -391,25 +402,35 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_linux_subscription_instances", "list_linux_subscriptions"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
+    "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
+    "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/paginator.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,33 +18,26 @@
     with session.create_client("license-manager-linux-subscriptions") as client:
         client: LicenseManagerLinuxSubscriptionsClient
 
         list_linux_subscription_instances_paginator: ListLinuxSubscriptionInstancesPaginator = client.get_paginator("list_linux_subscription_instances")
         list_linux_subscriptions_paginator: ListLinuxSubscriptionsPaginator = client.get_paginator("list_linux_subscriptions")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListLinuxSubscriptionInstancesResponseTypeDef,
     ListLinuxSubscriptionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListLinuxSubscriptionInstancesPaginator", "ListLinuxSubscriptionsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -60,15 +53,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptioninstancespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLinuxSubscriptionInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions.Paginator.ListLinuxSubscriptionInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptioninstancespaginator)
         """
 
 
@@ -78,13 +71,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLinuxSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions.Paginator.ListLinuxSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptionspaginator)
         """
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/paginator.pyi` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -18,32 +18,26 @@
     with session.create_client("license-manager-linux-subscriptions") as client:
         client: LicenseManagerLinuxSubscriptionsClient
 
         list_linux_subscription_instances_paginator: ListLinuxSubscriptionInstancesPaginator = client.get_paginator("list_linux_subscription_instances")
         list_linux_subscriptions_paginator: ListLinuxSubscriptionsPaginator = client.get_paginator("list_linux_subscriptions")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListLinuxSubscriptionInstancesResponseTypeDef,
     ListLinuxSubscriptionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListLinuxSubscriptionInstancesPaginator", "ListLinuxSubscriptionsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -56,15 +50,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptioninstancespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLinuxSubscriptionInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions.Paginator.ListLinuxSubscriptionInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptioninstancespaginator)
         """
 
 class ListLinuxSubscriptionsPaginator(AioPaginator):
@@ -73,13 +67,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLinuxSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions.Paginator.ListLinuxSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/paginators/#listlinuxsubscriptionspaginator)
         """
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.py` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -22,30 +22,29 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "FilterTypeDef",
     "LinuxSubscriptionsDiscoverySettingsTypeDef",
-    "ResponseMetadataTypeDef",
     "InstanceTypeDef",
-    "PaginatorConfigTypeDef",
     "SubscriptionTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
     "ListLinuxSubscriptionInstancesRequestRequestTypeDef",
+    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
     "ListLinuxSubscriptionsRequestRequestTypeDef",
-    "UpdateServiceSettingsRequestRequestTypeDef",
     "GetServiceSettingsResponseTypeDef",
+    "UpdateServiceSettingsRequestRequestTypeDef",
     "UpdateServiceSettingsResponseTypeDef",
     "ListLinuxSubscriptionInstancesResponseTypeDef",
-    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
-    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
     "ListLinuxSubscriptionsResponseTypeDef",
 )
 
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
@@ -59,25 +58,14 @@
     "LinuxSubscriptionsDiscoverySettingsTypeDef",
     {
         "OrganizationIntegration": OrganizationIntegrationType,
         "SourceRegions": List[str],
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
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "AccountID": str,
         "AmiId": str,
         "InstanceID": str,
         "InstanceType": str,
@@ -87,54 +75,95 @@
         "Status": str,
         "SubscriptionName": str,
         "UsageOperation": str,
     },
     total=False,
 )
 
+SubscriptionTypeDef = TypedDict(
+    "SubscriptionTypeDef",
+    {
+        "InstanceCount": int,
+        "Name": str,
+        "Type": str,
+    },
+    total=False,
+)
+
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
 )
 
-SubscriptionTypeDef = TypedDict(
-    "SubscriptionTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "InstanceCount": int,
-        "Name": str,
-        "Type": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
+    },
+)
+
+ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef = TypedDict(
+    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListLinuxSubscriptionInstancesRequestRequestTypeDef = TypedDict(
     "ListLinuxSubscriptionInstancesRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef = TypedDict(
+    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLinuxSubscriptionsRequestRequestTypeDef = TypedDict(
     "ListLinuxSubscriptionsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+GetServiceSettingsResponseTypeDef = TypedDict(
+    "GetServiceSettingsResponseTypeDef",
+    {
+        "HomeRegions": List[str],
+        "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
+        "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
+        "Status": StatusType,
+        "StatusMessage": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateServiceSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceSettingsRequestRequestTypeDef",
     {
         "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
         "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
     },
 )
@@ -142,74 +171,42 @@
     "_OptionalUpdateServiceSettingsRequestRequestTypeDef",
     {
         "AllowUpdate": bool,
     },
     total=False,
 )
 
-
 class UpdateServiceSettingsRequestRequestTypeDef(
     _RequiredUpdateServiceSettingsRequestRequestTypeDef,
     _OptionalUpdateServiceSettingsRequestRequestTypeDef,
 ):
     pass
 
-
-GetServiceSettingsResponseTypeDef = TypedDict(
-    "GetServiceSettingsResponseTypeDef",
-    {
-        "HomeRegions": List[str],
-        "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
-        "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
-        "Status": StatusType,
-        "StatusMessage": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateServiceSettingsResponseTypeDef = TypedDict(
     "UpdateServiceSettingsResponseTypeDef",
     {
         "HomeRegions": List[str],
         "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
         "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
         "Status": StatusType,
         "StatusMessage": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLinuxSubscriptionInstancesResponseTypeDef = TypedDict(
     "ListLinuxSubscriptionInstancesResponseTypeDef",
     {
         "Instances": List[InstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef = TypedDict(
-    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef = TypedDict(
-    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListLinuxSubscriptionsResponseTypeDef = TypedDict(
     "ListLinuxSubscriptionsResponseTypeDef",
     {
         "NextToken": str,
         "Subscriptions": List[SubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.pyi` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,29 +22,30 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "FilterTypeDef",
     "LinuxSubscriptionsDiscoverySettingsTypeDef",
-    "ResponseMetadataTypeDef",
     "InstanceTypeDef",
-    "PaginatorConfigTypeDef",
     "SubscriptionTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
     "ListLinuxSubscriptionInstancesRequestRequestTypeDef",
+    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
     "ListLinuxSubscriptionsRequestRequestTypeDef",
-    "UpdateServiceSettingsRequestRequestTypeDef",
     "GetServiceSettingsResponseTypeDef",
+    "UpdateServiceSettingsRequestRequestTypeDef",
     "UpdateServiceSettingsResponseTypeDef",
     "ListLinuxSubscriptionInstancesResponseTypeDef",
-    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
-    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
     "ListLinuxSubscriptionsResponseTypeDef",
 )
 
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
@@ -58,25 +59,14 @@
     "LinuxSubscriptionsDiscoverySettingsTypeDef",
     {
         "OrganizationIntegration": OrganizationIntegrationType,
         "SourceRegions": List[str],
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
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "AccountID": str,
         "AmiId": str,
         "InstanceID": str,
         "InstanceType": str,
@@ -86,54 +76,95 @@
         "Status": str,
         "SubscriptionName": str,
         "UsageOperation": str,
     },
     total=False,
 )
 
+SubscriptionTypeDef = TypedDict(
+    "SubscriptionTypeDef",
+    {
+        "InstanceCount": int,
+        "Name": str,
+        "Type": str,
+    },
+    total=False,
+)
+
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
 )
 
-SubscriptionTypeDef = TypedDict(
-    "SubscriptionTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "InstanceCount": int,
-        "Name": str,
-        "Type": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
+    },
+)
+
+ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef = TypedDict(
+    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListLinuxSubscriptionInstancesRequestRequestTypeDef = TypedDict(
     "ListLinuxSubscriptionInstancesRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef = TypedDict(
+    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLinuxSubscriptionsRequestRequestTypeDef = TypedDict(
     "ListLinuxSubscriptionsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+GetServiceSettingsResponseTypeDef = TypedDict(
+    "GetServiceSettingsResponseTypeDef",
+    {
+        "HomeRegions": List[str],
+        "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
+        "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
+        "Status": StatusType,
+        "StatusMessage": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateServiceSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateServiceSettingsRequestRequestTypeDef",
     {
         "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
         "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
     },
 )
@@ -141,72 +172,44 @@
     "_OptionalUpdateServiceSettingsRequestRequestTypeDef",
     {
         "AllowUpdate": bool,
     },
     total=False,
 )
 
+
 class UpdateServiceSettingsRequestRequestTypeDef(
     _RequiredUpdateServiceSettingsRequestRequestTypeDef,
     _OptionalUpdateServiceSettingsRequestRequestTypeDef,
 ):
     pass
 
-GetServiceSettingsResponseTypeDef = TypedDict(
-    "GetServiceSettingsResponseTypeDef",
-    {
-        "HomeRegions": List[str],
-        "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
-        "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
-        "Status": StatusType,
-        "StatusMessage": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 UpdateServiceSettingsResponseTypeDef = TypedDict(
     "UpdateServiceSettingsResponseTypeDef",
     {
         "HomeRegions": List[str],
         "LinuxSubscriptionsDiscovery": LinuxSubscriptionsDiscoveryType,
         "LinuxSubscriptionsDiscoverySettings": LinuxSubscriptionsDiscoverySettingsTypeDef,
         "Status": StatusType,
         "StatusMessage": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLinuxSubscriptionInstancesResponseTypeDef = TypedDict(
     "ListLinuxSubscriptionInstancesResponseTypeDef",
     {
         "Instances": List[InstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef = TypedDict(
-    "ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef = TypedDict(
-    "ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListLinuxSubscriptionsResponseTypeDef = TypedDict(
     "ListLinuxSubscriptionsResponseTypeDef",
     {
         "NextToken": str,
         "Subscriptions": List[SubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/PKG-INFO` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-license-manager-linux-subscriptions
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-license-manager-linux-subscriptions"></a>
 
 # types-aiobotocore-license-manager-linux-subscriptions
 
 [![PyPI - types-aiobotocore-license-manager-linux-subscriptions](https://img.shields.io/pypi/v/types-aiobotocore-license-manager-linux-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-linux-subscriptions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-license-manager-linux-subscriptions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-license-manager-linux-subscriptions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-license-manager-linux-subscriptions?color=blue)](https://pypistats.org/packages/types-aiobotocore-license-manager-linux-subscriptions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LicenseManagerLinuxSubscriptions 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions)
+[aiobotocore.LicenseManagerLinuxSubscriptions 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/license-manager-linux-subscriptions.html#LicenseManagerLinuxSubscriptions)
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
 [types-aiobotocore-license-manager-linux-subscriptions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_license_manager_linux_subscriptions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,26 +339,26 @@
 contains structures and shapes assembled to typed dictionaries for additional
 type checking.
 
 ```python
 from types_aiobotocore_license_manager_linux_subscriptions.type_defs import (
     FilterTypeDef,
     LinuxSubscriptionsDiscoverySettingsTypeDef,
-    ResponseMetadataTypeDef,
     InstanceTypeDef,
-    PaginatorConfigTypeDef,
     SubscriptionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef,
     ListLinuxSubscriptionInstancesRequestRequestTypeDef,
+    ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef,
     ListLinuxSubscriptionsRequestRequestTypeDef,
-    UpdateServiceSettingsRequestRequestTypeDef,
     GetServiceSettingsResponseTypeDef,
+    UpdateServiceSettingsRequestRequestTypeDef,
     UpdateServiceSettingsResponseTypeDef,
     ListLinuxSubscriptionInstancesResponseTypeDef,
-    ListLinuxSubscriptionInstancesRequestListLinuxSubscriptionInstancesPaginateTypeDef,
-    ListLinuxSubscriptionsRequestListLinuxSubscriptionsPaginateTypeDef,
     ListLinuxSubscriptionsResponseTypeDef,
 )
 
 
 def get_structure() -> FilterTypeDef:
     return {...}
 ```
@@ -366,43 +366,43 @@
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

### Comparing `types-aiobotocore-license-manager-linux-subscriptions-2.5.0.post1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/SOURCES.txt` & `types-aiobotocore-license-manager-linux-subscriptions-2.5.1/types_aiobotocore_license_manager_linux_subscriptions.egg-info/SOURCES.txt`

 * *Files identical despite different names*

