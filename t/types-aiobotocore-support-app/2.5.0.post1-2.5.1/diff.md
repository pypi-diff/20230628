# Comparing `tmp/types-aiobotocore-support-app-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-support-app-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-support-app-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:25 2023, max compression
+gzip compressed data, was "types-aiobotocore-support-app-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-support-app-2.5.0.post1.tar` & `types-aiobotocore-support-app-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.559677 types-aiobotocore-support-app-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13097 2023-03-11 12:27:25.559677 types-aiobotocore-support-app-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11511 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:25.559677 types-aiobotocore-support-app-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2151 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.555677 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/
--rw-r--r--   0 runner    (1001) docker     (123)      469 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      468 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      957 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10743 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    10725 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7581 2023-03-11 12:24:56.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7579 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     7157 2023-03-11 12:24:56.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7148 2023-03-11 12:24:56.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:55.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.559677 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13097 2023-03-11 12:27:25.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:27:25.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:27:25.000000 types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.114224 types-aiobotocore-support-app-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13093 2023-06-28 01:44:16.110224 types-aiobotocore-support-app-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11513 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.114224 types-aiobotocore-support-app-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.102224 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/
+-rw-r--r--   0 runner    (1001) docker     (123)      469 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      468 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      945 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10743 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10725 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7790 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7788 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     7167 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7158 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:44.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.110224 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13093 2023-06-28 01:44:15.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:44:15.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:15.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:15.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:15.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:44:15.000000 types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-support-app-2.5.0.post1/LICENSE` & `types-aiobotocore-support-app-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/PKG-INFO` & `types-aiobotocore-support-app-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-support-app
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SupportApp 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SupportApp 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-support-app"></a>
 
 # types-aiobotocore-support-app
 
 [![PyPI - types-aiobotocore-support-app](https://img.shields.io/pypi/v/types-aiobotocore-support-app.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support-app)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-support-app.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support-app)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-support-app?color=blue)](https://pypistats.org/packages/types-aiobotocore-support-app)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SupportApp 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp)
+[aiobotocore.SupportApp 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp)
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
 [types-aiobotocore-support-app docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,24 +294,24 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_support_app.type_defs import (
     CreateSlackChannelConfigurationRequestRequestTypeDef,
     DeleteSlackChannelConfigurationRequestRequestTypeDef,
     DeleteSlackWorkspaceConfigurationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    GetAccountAliasResultTypeDef,
     ListSlackChannelConfigurationsRequestRequestTypeDef,
     SlackChannelConfigurationTypeDef,
     ListSlackWorkspaceConfigurationsRequestRequestTypeDef,
     SlackWorkspaceConfigurationTypeDef,
     PutAccountAliasRequestRequestTypeDef,
     RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef,
-    UpdateSlackChannelConfigurationRequestRequestTypeDef,
-    GetAccountAliasResultTypeDef,
     RegisterSlackWorkspaceForOrganizationResultTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateSlackChannelConfigurationRequestRequestTypeDef,
     UpdateSlackChannelConfigurationResultTypeDef,
     ListSlackChannelConfigurationsResultTypeDef,
     ListSlackWorkspaceConfigurationsResultTypeDef,
 )
 
 
 def get_structure() -> CreateSlackChannelConfigurationRequestRequestTypeDef:
@@ -321,43 +321,43 @@
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/README.md` & `types-aiobotocore-support-app-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-support-app"></a>
 
 # types-aiobotocore-support-app
 
 [![PyPI - types-aiobotocore-support-app](https://img.shields.io/pypi/v/types-aiobotocore-support-app.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support-app)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-support-app.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support-app)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-support-app?color=blue)](https://pypistats.org/packages/types-aiobotocore-support-app)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SupportApp 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp)
+[aiobotocore.SupportApp 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp)
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
 [types-aiobotocore-support-app docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,24 +261,24 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_support_app.type_defs import (
     CreateSlackChannelConfigurationRequestRequestTypeDef,
     DeleteSlackChannelConfigurationRequestRequestTypeDef,
     DeleteSlackWorkspaceConfigurationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    GetAccountAliasResultTypeDef,
     ListSlackChannelConfigurationsRequestRequestTypeDef,
     SlackChannelConfigurationTypeDef,
     ListSlackWorkspaceConfigurationsRequestRequestTypeDef,
     SlackWorkspaceConfigurationTypeDef,
     PutAccountAliasRequestRequestTypeDef,
     RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef,
-    UpdateSlackChannelConfigurationRequestRequestTypeDef,
-    GetAccountAliasResultTypeDef,
     RegisterSlackWorkspaceForOrganizationResultTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateSlackChannelConfigurationRequestRequestTypeDef,
     UpdateSlackChannelConfigurationResultTypeDef,
     ListSlackChannelConfigurationsResultTypeDef,
     ListSlackWorkspaceConfigurationsResultTypeDef,
 )
 
 
 def get_structure() -> CreateSlackChannelConfigurationRequestRequestTypeDef:
@@ -288,43 +288,43 @@
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/setup.py` & `types-aiobotocore-support-app-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-support-app.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-support-app",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_support_app"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SupportApp 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SupportApp 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/"
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/__main__.py` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SupportApp 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SupportApp 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp\nOther"
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/client.py` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/client.pyi` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/literals.py` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -90,14 +90,15 @@
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
@@ -176,14 +177,15 @@
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
@@ -194,14 +196,15 @@
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
@@ -237,14 +240,15 @@
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
@@ -263,16 +267,19 @@
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
@@ -356,15 +363,17 @@
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/literals.pyi` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -88,14 +88,15 @@
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
@@ -174,14 +175,15 @@
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
@@ -192,14 +194,15 @@
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
@@ -235,14 +238,15 @@
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
@@ -261,16 +265,19 @@
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
@@ -354,15 +361,17 @@
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/type_defs.py` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,24 +22,24 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CreateSlackChannelConfigurationRequestRequestTypeDef",
     "DeleteSlackChannelConfigurationRequestRequestTypeDef",
     "DeleteSlackWorkspaceConfigurationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "GetAccountAliasResultTypeDef",
     "ListSlackChannelConfigurationsRequestRequestTypeDef",
     "SlackChannelConfigurationTypeDef",
     "ListSlackWorkspaceConfigurationsRequestRequestTypeDef",
     "SlackWorkspaceConfigurationTypeDef",
     "PutAccountAliasRequestRequestTypeDef",
     "RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef",
-    "UpdateSlackChannelConfigurationRequestRequestTypeDef",
-    "GetAccountAliasResultTypeDef",
     "RegisterSlackWorkspaceForOrganizationResultTypeDef",
+    "ResponseMetadataTypeDef",
+    "UpdateSlackChannelConfigurationRequestRequestTypeDef",
     "UpdateSlackChannelConfigurationResultTypeDef",
     "ListSlackChannelConfigurationsResultTypeDef",
     "ListSlackWorkspaceConfigurationsResultTypeDef",
 )
 
 _RequiredCreateSlackChannelConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSlackChannelConfigurationRequestRequestTypeDef",
@@ -80,22 +80,19 @@
 DeleteSlackWorkspaceConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteSlackWorkspaceConfigurationRequestRequestTypeDef",
     {
         "teamId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetAccountAliasResultTypeDef = TypedDict(
+    "GetAccountAliasResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "accountAlias": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSlackChannelConfigurationsRequestRequestTypeDef = TypedDict(
     "ListSlackChannelConfigurationsRequestRequestTypeDef",
     {
         "nextToken": str,
@@ -170,14 +167,35 @@
 RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef = TypedDict(
     "RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef",
     {
         "teamId": str,
     },
 )
 
+RegisterSlackWorkspaceForOrganizationResultTypeDef = TypedDict(
+    "RegisterSlackWorkspaceForOrganizationResultTypeDef",
+    {
+        "accountType": AccountTypeType,
+        "teamId": str,
+        "teamName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 _RequiredUpdateSlackChannelConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSlackChannelConfigurationRequestRequestTypeDef",
     {
         "channelId": str,
         "teamId": str,
     },
 )
@@ -198,57 +216,39 @@
 class UpdateSlackChannelConfigurationRequestRequestTypeDef(
     _RequiredUpdateSlackChannelConfigurationRequestRequestTypeDef,
     _OptionalUpdateSlackChannelConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
-GetAccountAliasResultTypeDef = TypedDict(
-    "GetAccountAliasResultTypeDef",
-    {
-        "accountAlias": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterSlackWorkspaceForOrganizationResultTypeDef = TypedDict(
-    "RegisterSlackWorkspaceForOrganizationResultTypeDef",
-    {
-        "accountType": AccountTypeType,
-        "teamId": str,
-        "teamName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSlackChannelConfigurationResultTypeDef = TypedDict(
     "UpdateSlackChannelConfigurationResultTypeDef",
     {
         "channelId": str,
         "channelName": str,
         "channelRoleArn": str,
         "notifyOnAddCorrespondenceToCase": bool,
         "notifyOnCaseSeverity": NotificationSeverityLevelType,
         "notifyOnCreateOrReopenCase": bool,
         "notifyOnResolveCase": bool,
         "teamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSlackChannelConfigurationsResultTypeDef = TypedDict(
     "ListSlackChannelConfigurationsResultTypeDef",
     {
         "nextToken": str,
         "slackChannelConfigurations": List[SlackChannelConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSlackWorkspaceConfigurationsResultTypeDef = TypedDict(
     "ListSlackWorkspaceConfigurationsResultTypeDef",
     {
         "nextToken": str,
         "slackWorkspaceConfigurations": List[SlackWorkspaceConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app/type_defs.pyi` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -21,24 +21,24 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CreateSlackChannelConfigurationRequestRequestTypeDef",
     "DeleteSlackChannelConfigurationRequestRequestTypeDef",
     "DeleteSlackWorkspaceConfigurationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "GetAccountAliasResultTypeDef",
     "ListSlackChannelConfigurationsRequestRequestTypeDef",
     "SlackChannelConfigurationTypeDef",
     "ListSlackWorkspaceConfigurationsRequestRequestTypeDef",
     "SlackWorkspaceConfigurationTypeDef",
     "PutAccountAliasRequestRequestTypeDef",
     "RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef",
-    "UpdateSlackChannelConfigurationRequestRequestTypeDef",
-    "GetAccountAliasResultTypeDef",
     "RegisterSlackWorkspaceForOrganizationResultTypeDef",
+    "ResponseMetadataTypeDef",
+    "UpdateSlackChannelConfigurationRequestRequestTypeDef",
     "UpdateSlackChannelConfigurationResultTypeDef",
     "ListSlackChannelConfigurationsResultTypeDef",
     "ListSlackWorkspaceConfigurationsResultTypeDef",
 )
 
 _RequiredCreateSlackChannelConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSlackChannelConfigurationRequestRequestTypeDef",
@@ -77,22 +77,19 @@
 DeleteSlackWorkspaceConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteSlackWorkspaceConfigurationRequestRequestTypeDef",
     {
         "teamId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetAccountAliasResultTypeDef = TypedDict(
+    "GetAccountAliasResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "accountAlias": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSlackChannelConfigurationsRequestRequestTypeDef = TypedDict(
     "ListSlackChannelConfigurationsRequestRequestTypeDef",
     {
         "nextToken": str,
@@ -163,14 +160,35 @@
 RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef = TypedDict(
     "RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef",
     {
         "teamId": str,
     },
 )
 
+RegisterSlackWorkspaceForOrganizationResultTypeDef = TypedDict(
+    "RegisterSlackWorkspaceForOrganizationResultTypeDef",
+    {
+        "accountType": AccountTypeType,
+        "teamId": str,
+        "teamName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 _RequiredUpdateSlackChannelConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSlackChannelConfigurationRequestRequestTypeDef",
     {
         "channelId": str,
         "teamId": str,
     },
 )
@@ -189,57 +207,39 @@
 
 class UpdateSlackChannelConfigurationRequestRequestTypeDef(
     _RequiredUpdateSlackChannelConfigurationRequestRequestTypeDef,
     _OptionalUpdateSlackChannelConfigurationRequestRequestTypeDef,
 ):
     pass
 
-GetAccountAliasResultTypeDef = TypedDict(
-    "GetAccountAliasResultTypeDef",
-    {
-        "accountAlias": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterSlackWorkspaceForOrganizationResultTypeDef = TypedDict(
-    "RegisterSlackWorkspaceForOrganizationResultTypeDef",
-    {
-        "accountType": AccountTypeType,
-        "teamId": str,
-        "teamName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSlackChannelConfigurationResultTypeDef = TypedDict(
     "UpdateSlackChannelConfigurationResultTypeDef",
     {
         "channelId": str,
         "channelName": str,
         "channelRoleArn": str,
         "notifyOnAddCorrespondenceToCase": bool,
         "notifyOnCaseSeverity": NotificationSeverityLevelType,
         "notifyOnCreateOrReopenCase": bool,
         "notifyOnResolveCase": bool,
         "teamId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSlackChannelConfigurationsResultTypeDef = TypedDict(
     "ListSlackChannelConfigurationsResultTypeDef",
     {
         "nextToken": str,
         "slackChannelConfigurations": List[SlackChannelConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSlackWorkspaceConfigurationsResultTypeDef = TypedDict(
     "ListSlackWorkspaceConfigurationsResultTypeDef",
     {
         "nextToken": str,
         "slackWorkspaceConfigurations": List[SlackWorkspaceConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/PKG-INFO` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-support-app
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SupportApp 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SupportApp 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-support-app"></a>
 
 # types-aiobotocore-support-app
 
 [![PyPI - types-aiobotocore-support-app](https://img.shields.io/pypi/v/types-aiobotocore-support-app.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support-app)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-support-app.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support-app)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-support-app?color=blue)](https://pypistats.org/packages/types-aiobotocore-support-app)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SupportApp 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp)
+[aiobotocore.SupportApp 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support-app.html#SupportApp)
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
 [types-aiobotocore-support-app docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support_app/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,24 +294,24 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_support_app.type_defs import (
     CreateSlackChannelConfigurationRequestRequestTypeDef,
     DeleteSlackChannelConfigurationRequestRequestTypeDef,
     DeleteSlackWorkspaceConfigurationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    GetAccountAliasResultTypeDef,
     ListSlackChannelConfigurationsRequestRequestTypeDef,
     SlackChannelConfigurationTypeDef,
     ListSlackWorkspaceConfigurationsRequestRequestTypeDef,
     SlackWorkspaceConfigurationTypeDef,
     PutAccountAliasRequestRequestTypeDef,
     RegisterSlackWorkspaceForOrganizationRequestRequestTypeDef,
-    UpdateSlackChannelConfigurationRequestRequestTypeDef,
-    GetAccountAliasResultTypeDef,
     RegisterSlackWorkspaceForOrganizationResultTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateSlackChannelConfigurationRequestRequestTypeDef,
     UpdateSlackChannelConfigurationResultTypeDef,
     ListSlackChannelConfigurationsResultTypeDef,
     ListSlackWorkspaceConfigurationsResultTypeDef,
 )
 
 
 def get_structure() -> CreateSlackChannelConfigurationRequestRequestTypeDef:
@@ -321,43 +321,43 @@
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

### Comparing `types-aiobotocore-support-app-2.5.0.post1/types_aiobotocore_support_app.egg-info/SOURCES.txt` & `types-aiobotocore-support-app-2.5.1/types_aiobotocore_support_app.egg-info/SOURCES.txt`

 * *Files identical despite different names*

