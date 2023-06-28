# Comparing `tmp/types-aiobotocore-ssm-sap-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ssm-sap-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ssm-sap-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-ssm-sap-2.5.1.tar", last modified: Wed Jun 28 01:44:14 2023, max compression
```

## Comparing `types-aiobotocore-ssm-sap-2.5.0.post1.tar` & `types-aiobotocore-ssm-sap-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.467657 types-aiobotocore-ssm-sap-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15293 2023-03-11 12:27:23.467657 types-aiobotocore-ssm-sap-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13723 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.467657 types-aiobotocore-ssm-sap-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2123 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.467657 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/
--rw-r--r--   0 runner    (1001) docker     (123)     1242 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1241 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      941 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16516 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16486 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9234 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9232 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5507 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5500 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    15292 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15279 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:42.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.467657 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15293 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.398221 types-aiobotocore-ssm-sap-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15285 2023-06-28 01:44:14.398221 types-aiobotocore-ssm-sap-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13721 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:14.398221 types-aiobotocore-ssm-sap-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.398221 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/
+-rw-r--r--   0 runner    (1001) docker     (123)     1242 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1241 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      929 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16516 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16486 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9443 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9441 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5395 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5389 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    15328 2023-06-28 01:41:32.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15315 2023-06-28 01:41:32.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.398221 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15285 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/LICENSE` & `types-aiobotocore-ssm-sap-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ssm-sap-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm-sap
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SsmSap 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SsmSap 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm-sap"></a>
 
 # types-aiobotocore-ssm-sap
 
 [![PyPI - types-aiobotocore-ssm-sap](https://img.shields.io/pypi/v/types-aiobotocore-ssm-sap.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-sap)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-sap.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-sap)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-sap?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-sap)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SsmSap 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap)
+[aiobotocore.SsmSap 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap)
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
 [types-aiobotocore-ssm-sap docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,52 +344,52 @@
     ApplicationCredentialTypeDef,
     ApplicationSummaryTypeDef,
     ApplicationTypeDef,
     ComponentSummaryTypeDef,
     HostTypeDef,
     DatabaseSummaryTypeDef,
     DeleteResourcePermissionInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteResourcePermissionOutputTypeDef,
     DeregisterApplicationInputRequestTypeDef,
     FilterTypeDef,
     GetApplicationInputRequestTypeDef,
     GetComponentInputRequestTypeDef,
     GetDatabaseInputRequestTypeDef,
     GetOperationInputRequestTypeDef,
     OperationTypeDef,
     GetResourcePermissionInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePermissionOutputTypeDef,
+    ListApplicationsInputListApplicationsPaginateTypeDef,
     ListApplicationsInputRequestTypeDef,
+    ListComponentsInputListComponentsPaginateTypeDef,
     ListComponentsInputRequestTypeDef,
+    ListDatabasesInputListDatabasesPaginateTypeDef,
     ListDatabasesInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePermissionInputRequestTypeDef,
+    PutResourcePermissionOutputTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateApplicationSettingsOutputTypeDef,
     DatabaseTypeDef,
     RegisterApplicationInputRequestTypeDef,
     UpdateApplicationSettingsInputRequestTypeDef,
-    ComponentTypeDef,
-    DeleteResourcePermissionOutputTypeDef,
-    GetApplicationOutputTypeDef,
-    GetResourcePermissionOutputTypeDef,
     ListApplicationsOutputTypeDef,
+    GetApplicationOutputTypeDef,
+    RegisterApplicationOutputTypeDef,
     ListComponentsOutputTypeDef,
+    ComponentTypeDef,
     ListDatabasesOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutResourcePermissionOutputTypeDef,
-    RegisterApplicationOutputTypeDef,
-    UpdateApplicationSettingsOutputTypeDef,
+    ListOperationsInputListOperationsPaginateTypeDef,
     ListOperationsInputRequestTypeDef,
     GetOperationOutputTypeDef,
     ListOperationsOutputTypeDef,
-    ListApplicationsInputListApplicationsPaginateTypeDef,
-    ListComponentsInputListComponentsPaginateTypeDef,
-    ListDatabasesInputListDatabasesPaginateTypeDef,
-    ListOperationsInputListOperationsPaginateTypeDef,
     GetDatabaseOutputTypeDef,
     GetComponentOutputTypeDef,
 )
 
 
 def get_structure() -> ApplicationCredentialTypeDef:
     return {...}
@@ -398,43 +398,43 @@
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/README.md` & `types-aiobotocore-ssm-sap-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ssm-sap"></a>
 
 # types-aiobotocore-ssm-sap
 
 [![PyPI - types-aiobotocore-ssm-sap](https://img.shields.io/pypi/v/types-aiobotocore-ssm-sap.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-sap)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-sap.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-sap)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-sap?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-sap)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SsmSap 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap)
+[aiobotocore.SsmSap 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap)
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
 [types-aiobotocore-ssm-sap docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/).
 
 See how it helps to find and fix potential bugs:
 
@@ -311,52 +311,52 @@
     ApplicationCredentialTypeDef,
     ApplicationSummaryTypeDef,
     ApplicationTypeDef,
     ComponentSummaryTypeDef,
     HostTypeDef,
     DatabaseSummaryTypeDef,
     DeleteResourcePermissionInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteResourcePermissionOutputTypeDef,
     DeregisterApplicationInputRequestTypeDef,
     FilterTypeDef,
     GetApplicationInputRequestTypeDef,
     GetComponentInputRequestTypeDef,
     GetDatabaseInputRequestTypeDef,
     GetOperationInputRequestTypeDef,
     OperationTypeDef,
     GetResourcePermissionInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePermissionOutputTypeDef,
+    ListApplicationsInputListApplicationsPaginateTypeDef,
     ListApplicationsInputRequestTypeDef,
+    ListComponentsInputListComponentsPaginateTypeDef,
     ListComponentsInputRequestTypeDef,
+    ListDatabasesInputListDatabasesPaginateTypeDef,
     ListDatabasesInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePermissionInputRequestTypeDef,
+    PutResourcePermissionOutputTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateApplicationSettingsOutputTypeDef,
     DatabaseTypeDef,
     RegisterApplicationInputRequestTypeDef,
     UpdateApplicationSettingsInputRequestTypeDef,
-    ComponentTypeDef,
-    DeleteResourcePermissionOutputTypeDef,
-    GetApplicationOutputTypeDef,
-    GetResourcePermissionOutputTypeDef,
     ListApplicationsOutputTypeDef,
+    GetApplicationOutputTypeDef,
+    RegisterApplicationOutputTypeDef,
     ListComponentsOutputTypeDef,
+    ComponentTypeDef,
     ListDatabasesOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutResourcePermissionOutputTypeDef,
-    RegisterApplicationOutputTypeDef,
-    UpdateApplicationSettingsOutputTypeDef,
+    ListOperationsInputListOperationsPaginateTypeDef,
     ListOperationsInputRequestTypeDef,
     GetOperationOutputTypeDef,
     ListOperationsOutputTypeDef,
-    ListApplicationsInputListApplicationsPaginateTypeDef,
-    ListComponentsInputListComponentsPaginateTypeDef,
-    ListDatabasesInputListDatabasesPaginateTypeDef,
-    ListOperationsInputListOperationsPaginateTypeDef,
     GetDatabaseOutputTypeDef,
     GetComponentOutputTypeDef,
 )
 
 
 def get_structure() -> ApplicationCredentialTypeDef:
     return {...}
@@ -365,43 +365,43 @@
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/setup.py` & `types-aiobotocore-ssm-sap-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ssm-sap.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ssm-sap",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ssm_sap"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SsmSap 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SsmSap 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/"
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/__init__.py` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/__init__.pyi` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/__main__.py` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/__main__.py`

 * *Files 25% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SsmSap 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SsmSap 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap\nOther"
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/client.py` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/client.pyi` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/literals.py` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -119,14 +119,15 @@
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
@@ -205,14 +206,15 @@
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
@@ -223,14 +225,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -292,16 +296,19 @@
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
@@ -385,15 +392,17 @@
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/literals.pyi` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -117,14 +117,15 @@
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
@@ -203,14 +204,15 @@
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
@@ -221,14 +223,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -290,16 +294,19 @@
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
@@ -383,15 +390,17 @@
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/paginator.py` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
         list_databases_paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
         list_operations_paginator: ListOperationsPaginator = client.get_paginator("list_operations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListApplicationsOutputTypeDef,
     ListComponentsOutputTypeDef,
     ListDatabasesOutputTypeDef,
     ListOperationsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationsPaginator",
     "ListComponentsPaginator",
     "ListDatabasesPaginator",
     "ListOperationsPaginator",
 )
 
@@ -68,30 +61,30 @@
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listapplicationspaginator)
         """
 
 
 class ListComponentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListComponents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listcomponentspaginator)
     """
 
     def paginate(
-        self, *, ApplicationId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApplicationId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listcomponentspaginator)
         """
 
 
@@ -102,15 +95,15 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationId: str = ...,
         ComponentId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatabasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listdatabasespaginator)
         """
 
 
@@ -121,13 +114,13 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOperationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listoperationspaginator)
         """
```

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/paginator.pyi` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/paginator.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
         list_databases_paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
         list_operations_paginator: ListOperationsPaginator = client.get_paginator("list_operations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListApplicationsOutputTypeDef,
     ListComponentsOutputTypeDef,
     ListDatabasesOutputTypeDef,
     ListOperationsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationsPaginator",
     "ListComponentsPaginator",
     "ListDatabasesPaginator",
     "ListOperationsPaginator",
 )
 
@@ -64,29 +58,29 @@
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listapplicationspaginator)
         """
 
 class ListComponentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListComponents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listcomponentspaginator)
     """
 
     def paginate(
-        self, *, ApplicationId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApplicationId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listcomponentspaginator)
         """
 
 class ListDatabasesPaginator(AioPaginator):
@@ -96,15 +90,15 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationId: str = ...,
         ComponentId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatabasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listdatabasespaginator)
         """
 
 class ListOperationsPaginator(AioPaginator):
@@ -114,13 +108,13 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationId: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOperationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap.Paginator.ListOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/paginators/#listoperationspaginator)
         """
```

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/type_defs.py` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,52 +38,52 @@
     "ApplicationCredentialTypeDef",
     "ApplicationSummaryTypeDef",
     "ApplicationTypeDef",
     "ComponentSummaryTypeDef",
     "HostTypeDef",
     "DatabaseSummaryTypeDef",
     "DeleteResourcePermissionInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteResourcePermissionOutputTypeDef",
     "DeregisterApplicationInputRequestTypeDef",
     "FilterTypeDef",
     "GetApplicationInputRequestTypeDef",
     "GetComponentInputRequestTypeDef",
     "GetDatabaseInputRequestTypeDef",
     "GetOperationInputRequestTypeDef",
     "OperationTypeDef",
     "GetResourcePermissionInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePermissionOutputTypeDef",
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
     "ListApplicationsInputRequestTypeDef",
+    "ListComponentsInputListComponentsPaginateTypeDef",
     "ListComponentsInputRequestTypeDef",
+    "ListDatabasesInputListDatabasesPaginateTypeDef",
     "ListDatabasesInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePermissionInputRequestTypeDef",
+    "PutResourcePermissionOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateApplicationSettingsOutputTypeDef",
     "DatabaseTypeDef",
     "RegisterApplicationInputRequestTypeDef",
     "UpdateApplicationSettingsInputRequestTypeDef",
-    "ComponentTypeDef",
-    "DeleteResourcePermissionOutputTypeDef",
-    "GetApplicationOutputTypeDef",
-    "GetResourcePermissionOutputTypeDef",
     "ListApplicationsOutputTypeDef",
+    "GetApplicationOutputTypeDef",
+    "RegisterApplicationOutputTypeDef",
     "ListComponentsOutputTypeDef",
+    "ComponentTypeDef",
     "ListDatabasesOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutResourcePermissionOutputTypeDef",
-    "RegisterApplicationOutputTypeDef",
-    "UpdateApplicationSettingsOutputTypeDef",
+    "ListOperationsInputListOperationsPaginateTypeDef",
     "ListOperationsInputRequestTypeDef",
     "GetOperationOutputTypeDef",
     "ListOperationsOutputTypeDef",
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    "ListDatabasesInputListDatabasesPaginateTypeDef",
-    "ListOperationsInputListOperationsPaginateTypeDef",
     "GetDatabaseOutputTypeDef",
     "GetComponentOutputTypeDef",
 )
 
 ApplicationCredentialTypeDef = TypedDict(
     "ApplicationCredentialTypeDef",
     {
@@ -173,22 +173,19 @@
 class DeleteResourcePermissionInputRequestTypeDef(
     _RequiredDeleteResourcePermissionInputRequestTypeDef,
     _OptionalDeleteResourcePermissionInputRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteResourcePermissionOutputTypeDef = TypedDict(
+    "DeleteResourcePermissionOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterApplicationInputRequestTypeDef = TypedDict(
     "DeregisterApplicationInputRequestTypeDef",
     {
         "ApplicationId": str,
@@ -276,43 +273,68 @@
 class GetResourcePermissionInputRequestTypeDef(
     _RequiredGetResourcePermissionInputRequestTypeDef,
     _OptionalGetResourcePermissionInputRequestTypeDef,
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetResourcePermissionOutputTypeDef = TypedDict(
+    "GetResourcePermissionOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsInputRequestTypeDef = TypedDict(
     "ListApplicationsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
+    "ListComponentsInputListComponentsPaginateTypeDef",
+    {
+        "ApplicationId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComponentsInputRequestTypeDef = TypedDict(
     "ListComponentsInputRequestTypeDef",
     {
         "ApplicationId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
+    "ListDatabasesInputListDatabasesPaginateTypeDef",
+    {
+        "ApplicationId": str,
+        "ComponentId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatabasesInputRequestTypeDef = TypedDict(
     "ListDatabasesInputRequestTypeDef",
     {
         "ApplicationId": str,
         "ComponentId": str,
         "NextToken": str,
         "MaxResults": int,
@@ -323,23 +345,60 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
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
 PutResourcePermissionInputRequestTypeDef = TypedDict(
     "PutResourcePermissionInputRequestTypeDef",
     {
         "ActionType": Literal["RESTORE"],
         "SourceResourceArn": str,
         "ResourceArn": str,
     },
 )
 
+PutResourcePermissionOutputTypeDef = TypedDict(
+    "PutResourcePermissionOutputTypeDef",
+    {
+        "Policy": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -348,14 +407,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateApplicationSettingsOutputTypeDef = TypedDict(
+    "UpdateApplicationSettingsOutputTypeDef",
+    {
+        "Message": str,
+        "OperationIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatabaseTypeDef = TypedDict(
     "DatabaseTypeDef",
     {
         "ApplicationId": str,
         "ComponentId": str,
         "Credentials": List[ApplicationCredentialTypeDef],
         "DatabaseId": str,
@@ -415,114 +483,96 @@
 class UpdateApplicationSettingsInputRequestTypeDef(
     _RequiredUpdateApplicationSettingsInputRequestTypeDef,
     _OptionalUpdateApplicationSettingsInputRequestTypeDef,
 ):
     pass
 
 
-ComponentTypeDef = TypedDict(
-    "ComponentTypeDef",
-    {
-        "ComponentId": str,
-        "ApplicationId": str,
-        "ComponentType": Literal["HANA"],
-        "Status": Literal["ACTIVATED"],
-        "Databases": List[str],
-        "Hosts": List[HostTypeDef],
-        "PrimaryHost": str,
-        "LastUpdated": datetime,
-    },
-    total=False,
-)
-
-DeleteResourcePermissionOutputTypeDef = TypedDict(
-    "DeleteResourcePermissionOutputTypeDef",
+ListApplicationsOutputTypeDef = TypedDict(
+    "ListApplicationsOutputTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Applications": List[ApplicationSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationOutputTypeDef = TypedDict(
     "GetApplicationOutputTypeDef",
     {
         "Application": ApplicationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetResourcePermissionOutputTypeDef = TypedDict(
-    "GetResourcePermissionOutputTypeDef",
+RegisterApplicationOutputTypeDef = TypedDict(
+    "RegisterApplicationOutputTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Application": ApplicationTypeDef,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListApplicationsOutputTypeDef = TypedDict(
-    "ListApplicationsOutputTypeDef",
+ListComponentsOutputTypeDef = TypedDict(
+    "ListComponentsOutputTypeDef",
     {
-        "Applications": List[ApplicationSummaryTypeDef],
+        "Components": List[ComponentSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListComponentsOutputTypeDef = TypedDict(
-    "ListComponentsOutputTypeDef",
+ComponentTypeDef = TypedDict(
+    "ComponentTypeDef",
     {
-        "Components": List[ComponentSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ComponentId": str,
+        "ApplicationId": str,
+        "ComponentType": Literal["HANA"],
+        "Status": Literal["ACTIVATED"],
+        "Databases": List[str],
+        "Hosts": List[HostTypeDef],
+        "PrimaryHost": str,
+        "LastUpdated": datetime,
     },
+    total=False,
 )
 
 ListDatabasesOutputTypeDef = TypedDict(
     "ListDatabasesOutputTypeDef",
     {
         "Databases": List[DatabaseSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_RequiredListOperationsInputListOperationsPaginateTypeDef = TypedDict(
+    "_RequiredListOperationsInputListOperationsPaginateTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationId": str,
     },
 )
-
-PutResourcePermissionOutputTypeDef = TypedDict(
-    "PutResourcePermissionOutputTypeDef",
+_OptionalListOperationsInputListOperationsPaginateTypeDef = TypedDict(
+    "_OptionalListOperationsInputListOperationsPaginateTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-RegisterApplicationOutputTypeDef = TypedDict(
-    "RegisterApplicationOutputTypeDef",
-    {
-        "Application": ApplicationTypeDef,
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateApplicationSettingsOutputTypeDef = TypedDict(
-    "UpdateApplicationSettingsOutputTypeDef",
-    {
-        "Message": str,
-        "OperationIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListOperationsInputListOperationsPaginateTypeDef(
+    _RequiredListOperationsInputListOperationsPaginateTypeDef,
+    _OptionalListOperationsInputListOperationsPaginateTypeDef,
+):
+    pass
+
 
 _RequiredListOperationsInputRequestTypeDef = TypedDict(
     "_RequiredListOperationsInputRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
@@ -543,86 +593,36 @@
     pass
 
 
 GetOperationOutputTypeDef = TypedDict(
     "GetOperationOutputTypeDef",
     {
         "Operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOperationsOutputTypeDef = TypedDict(
     "ListOperationsOutputTypeDef",
     {
         "Operations": List[OperationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    {
-        "ApplicationId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
-    "ListDatabasesInputListDatabasesPaginateTypeDef",
-    {
-        "ApplicationId": str,
-        "ComponentId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListOperationsInputListOperationsPaginateTypeDef = TypedDict(
-    "_RequiredListOperationsInputListOperationsPaginateTypeDef",
-    {
-        "ApplicationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListOperationsInputListOperationsPaginateTypeDef = TypedDict(
-    "_OptionalListOperationsInputListOperationsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListOperationsInputListOperationsPaginateTypeDef(
-    _RequiredListOperationsInputListOperationsPaginateTypeDef,
-    _OptionalListOperationsInputListOperationsPaginateTypeDef,
-):
-    pass
-
 
 GetDatabaseOutputTypeDef = TypedDict(
     "GetDatabaseOutputTypeDef",
     {
         "Database": DatabaseTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComponentOutputTypeDef = TypedDict(
     "GetComponentOutputTypeDef",
     {
         "Component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap/type_defs.pyi` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -37,52 +37,52 @@
     "ApplicationCredentialTypeDef",
     "ApplicationSummaryTypeDef",
     "ApplicationTypeDef",
     "ComponentSummaryTypeDef",
     "HostTypeDef",
     "DatabaseSummaryTypeDef",
     "DeleteResourcePermissionInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DeleteResourcePermissionOutputTypeDef",
     "DeregisterApplicationInputRequestTypeDef",
     "FilterTypeDef",
     "GetApplicationInputRequestTypeDef",
     "GetComponentInputRequestTypeDef",
     "GetDatabaseInputRequestTypeDef",
     "GetOperationInputRequestTypeDef",
     "OperationTypeDef",
     "GetResourcePermissionInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePermissionOutputTypeDef",
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
     "ListApplicationsInputRequestTypeDef",
+    "ListComponentsInputListComponentsPaginateTypeDef",
     "ListComponentsInputRequestTypeDef",
+    "ListDatabasesInputListDatabasesPaginateTypeDef",
     "ListDatabasesInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePermissionInputRequestTypeDef",
+    "PutResourcePermissionOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateApplicationSettingsOutputTypeDef",
     "DatabaseTypeDef",
     "RegisterApplicationInputRequestTypeDef",
     "UpdateApplicationSettingsInputRequestTypeDef",
-    "ComponentTypeDef",
-    "DeleteResourcePermissionOutputTypeDef",
-    "GetApplicationOutputTypeDef",
-    "GetResourcePermissionOutputTypeDef",
     "ListApplicationsOutputTypeDef",
+    "GetApplicationOutputTypeDef",
+    "RegisterApplicationOutputTypeDef",
     "ListComponentsOutputTypeDef",
+    "ComponentTypeDef",
     "ListDatabasesOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutResourcePermissionOutputTypeDef",
-    "RegisterApplicationOutputTypeDef",
-    "UpdateApplicationSettingsOutputTypeDef",
+    "ListOperationsInputListOperationsPaginateTypeDef",
     "ListOperationsInputRequestTypeDef",
     "GetOperationOutputTypeDef",
     "ListOperationsOutputTypeDef",
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    "ListDatabasesInputListDatabasesPaginateTypeDef",
-    "ListOperationsInputListOperationsPaginateTypeDef",
     "GetDatabaseOutputTypeDef",
     "GetComponentOutputTypeDef",
 )
 
 ApplicationCredentialTypeDef = TypedDict(
     "ApplicationCredentialTypeDef",
     {
@@ -170,22 +170,19 @@
 
 class DeleteResourcePermissionInputRequestTypeDef(
     _RequiredDeleteResourcePermissionInputRequestTypeDef,
     _OptionalDeleteResourcePermissionInputRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DeleteResourcePermissionOutputTypeDef = TypedDict(
+    "DeleteResourcePermissionOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterApplicationInputRequestTypeDef = TypedDict(
     "DeregisterApplicationInputRequestTypeDef",
     {
         "ApplicationId": str,
@@ -271,43 +268,68 @@
 
 class GetResourcePermissionInputRequestTypeDef(
     _RequiredGetResourcePermissionInputRequestTypeDef,
     _OptionalGetResourcePermissionInputRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetResourcePermissionOutputTypeDef = TypedDict(
+    "GetResourcePermissionOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsInputRequestTypeDef = TypedDict(
     "ListApplicationsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
+    "ListComponentsInputListComponentsPaginateTypeDef",
+    {
+        "ApplicationId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComponentsInputRequestTypeDef = TypedDict(
     "ListComponentsInputRequestTypeDef",
     {
         "ApplicationId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
+    "ListDatabasesInputListDatabasesPaginateTypeDef",
+    {
+        "ApplicationId": str,
+        "ComponentId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatabasesInputRequestTypeDef = TypedDict(
     "ListDatabasesInputRequestTypeDef",
     {
         "ApplicationId": str,
         "ComponentId": str,
         "NextToken": str,
         "MaxResults": int,
@@ -318,23 +340,60 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
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
 PutResourcePermissionInputRequestTypeDef = TypedDict(
     "PutResourcePermissionInputRequestTypeDef",
     {
         "ActionType": Literal["RESTORE"],
         "SourceResourceArn": str,
         "ResourceArn": str,
     },
 )
 
+PutResourcePermissionOutputTypeDef = TypedDict(
+    "PutResourcePermissionOutputTypeDef",
+    {
+        "Policy": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -343,14 +402,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateApplicationSettingsOutputTypeDef = TypedDict(
+    "UpdateApplicationSettingsOutputTypeDef",
+    {
+        "Message": str,
+        "OperationIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatabaseTypeDef = TypedDict(
     "DatabaseTypeDef",
     {
         "ApplicationId": str,
         "ComponentId": str,
         "Credentials": List[ApplicationCredentialTypeDef],
         "DatabaseId": str,
@@ -406,114 +474,94 @@
 
 class UpdateApplicationSettingsInputRequestTypeDef(
     _RequiredUpdateApplicationSettingsInputRequestTypeDef,
     _OptionalUpdateApplicationSettingsInputRequestTypeDef,
 ):
     pass
 
-ComponentTypeDef = TypedDict(
-    "ComponentTypeDef",
-    {
-        "ComponentId": str,
-        "ApplicationId": str,
-        "ComponentType": Literal["HANA"],
-        "Status": Literal["ACTIVATED"],
-        "Databases": List[str],
-        "Hosts": List[HostTypeDef],
-        "PrimaryHost": str,
-        "LastUpdated": datetime,
-    },
-    total=False,
-)
-
-DeleteResourcePermissionOutputTypeDef = TypedDict(
-    "DeleteResourcePermissionOutputTypeDef",
+ListApplicationsOutputTypeDef = TypedDict(
+    "ListApplicationsOutputTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Applications": List[ApplicationSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationOutputTypeDef = TypedDict(
     "GetApplicationOutputTypeDef",
     {
         "Application": ApplicationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetResourcePermissionOutputTypeDef = TypedDict(
-    "GetResourcePermissionOutputTypeDef",
+RegisterApplicationOutputTypeDef = TypedDict(
+    "RegisterApplicationOutputTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Application": ApplicationTypeDef,
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListApplicationsOutputTypeDef = TypedDict(
-    "ListApplicationsOutputTypeDef",
+ListComponentsOutputTypeDef = TypedDict(
+    "ListComponentsOutputTypeDef",
     {
-        "Applications": List[ApplicationSummaryTypeDef],
+        "Components": List[ComponentSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListComponentsOutputTypeDef = TypedDict(
-    "ListComponentsOutputTypeDef",
+ComponentTypeDef = TypedDict(
+    "ComponentTypeDef",
     {
-        "Components": List[ComponentSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ComponentId": str,
+        "ApplicationId": str,
+        "ComponentType": Literal["HANA"],
+        "Status": Literal["ACTIVATED"],
+        "Databases": List[str],
+        "Hosts": List[HostTypeDef],
+        "PrimaryHost": str,
+        "LastUpdated": datetime,
     },
+    total=False,
 )
 
 ListDatabasesOutputTypeDef = TypedDict(
     "ListDatabasesOutputTypeDef",
     {
         "Databases": List[DatabaseSummaryTypeDef],
         "NextToken": str,
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
 
-PutResourcePermissionOutputTypeDef = TypedDict(
-    "PutResourcePermissionOutputTypeDef",
+_RequiredListOperationsInputListOperationsPaginateTypeDef = TypedDict(
+    "_RequiredListOperationsInputListOperationsPaginateTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationId": str,
     },
 )
-
-RegisterApplicationOutputTypeDef = TypedDict(
-    "RegisterApplicationOutputTypeDef",
+_OptionalListOperationsInputListOperationsPaginateTypeDef = TypedDict(
+    "_OptionalListOperationsInputListOperationsPaginateTypeDef",
     {
-        "Application": ApplicationTypeDef,
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-UpdateApplicationSettingsOutputTypeDef = TypedDict(
-    "UpdateApplicationSettingsOutputTypeDef",
-    {
-        "Message": str,
-        "OperationIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListOperationsInputListOperationsPaginateTypeDef(
+    _RequiredListOperationsInputListOperationsPaginateTypeDef,
+    _OptionalListOperationsInputListOperationsPaginateTypeDef,
+):
+    pass
 
 _RequiredListOperationsInputRequestTypeDef = TypedDict(
     "_RequiredListOperationsInputRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
@@ -532,84 +580,36 @@
 ):
     pass
 
 GetOperationOutputTypeDef = TypedDict(
     "GetOperationOutputTypeDef",
     {
         "Operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOperationsOutputTypeDef = TypedDict(
     "ListOperationsOutputTypeDef",
     {
         "Operations": List[OperationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListComponentsInputListComponentsPaginateTypeDef = TypedDict(
-    "ListComponentsInputListComponentsPaginateTypeDef",
-    {
-        "ApplicationId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
-    "ListDatabasesInputListDatabasesPaginateTypeDef",
-    {
-        "ApplicationId": str,
-        "ComponentId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListOperationsInputListOperationsPaginateTypeDef = TypedDict(
-    "_RequiredListOperationsInputListOperationsPaginateTypeDef",
-    {
-        "ApplicationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListOperationsInputListOperationsPaginateTypeDef = TypedDict(
-    "_OptionalListOperationsInputListOperationsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListOperationsInputListOperationsPaginateTypeDef(
-    _RequiredListOperationsInputListOperationsPaginateTypeDef,
-    _OptionalListOperationsInputListOperationsPaginateTypeDef,
-):
-    pass
 
 GetDatabaseOutputTypeDef = TypedDict(
     "GetDatabaseOutputTypeDef",
     {
         "Database": DatabaseTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComponentOutputTypeDef = TypedDict(
     "GetComponentOutputTypeDef",
     {
         "Component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/PKG-INFO` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm-sap
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SsmSap 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SsmSap 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm-sap"></a>
 
 # types-aiobotocore-ssm-sap
 
 [![PyPI - types-aiobotocore-ssm-sap](https://img.shields.io/pypi/v/types-aiobotocore-ssm-sap.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-sap)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-sap.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-sap)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-sap?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-sap)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SsmSap 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap)
+[aiobotocore.SsmSap 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-sap.html#SsmSap)
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
 [types-aiobotocore-ssm-sap docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_sap/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,52 +344,52 @@
     ApplicationCredentialTypeDef,
     ApplicationSummaryTypeDef,
     ApplicationTypeDef,
     ComponentSummaryTypeDef,
     HostTypeDef,
     DatabaseSummaryTypeDef,
     DeleteResourcePermissionInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DeleteResourcePermissionOutputTypeDef,
     DeregisterApplicationInputRequestTypeDef,
     FilterTypeDef,
     GetApplicationInputRequestTypeDef,
     GetComponentInputRequestTypeDef,
     GetDatabaseInputRequestTypeDef,
     GetOperationInputRequestTypeDef,
     OperationTypeDef,
     GetResourcePermissionInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePermissionOutputTypeDef,
+    ListApplicationsInputListApplicationsPaginateTypeDef,
     ListApplicationsInputRequestTypeDef,
+    ListComponentsInputListComponentsPaginateTypeDef,
     ListComponentsInputRequestTypeDef,
+    ListDatabasesInputListDatabasesPaginateTypeDef,
     ListDatabasesInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePermissionInputRequestTypeDef,
+    PutResourcePermissionOutputTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateApplicationSettingsOutputTypeDef,
     DatabaseTypeDef,
     RegisterApplicationInputRequestTypeDef,
     UpdateApplicationSettingsInputRequestTypeDef,
-    ComponentTypeDef,
-    DeleteResourcePermissionOutputTypeDef,
-    GetApplicationOutputTypeDef,
-    GetResourcePermissionOutputTypeDef,
     ListApplicationsOutputTypeDef,
+    GetApplicationOutputTypeDef,
+    RegisterApplicationOutputTypeDef,
     ListComponentsOutputTypeDef,
+    ComponentTypeDef,
     ListDatabasesOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutResourcePermissionOutputTypeDef,
-    RegisterApplicationOutputTypeDef,
-    UpdateApplicationSettingsOutputTypeDef,
+    ListOperationsInputListOperationsPaginateTypeDef,
     ListOperationsInputRequestTypeDef,
     GetOperationOutputTypeDef,
     ListOperationsOutputTypeDef,
-    ListApplicationsInputListApplicationsPaginateTypeDef,
-    ListComponentsInputListComponentsPaginateTypeDef,
-    ListDatabasesInputListDatabasesPaginateTypeDef,
-    ListOperationsInputListOperationsPaginateTypeDef,
     GetDatabaseOutputTypeDef,
     GetComponentOutputTypeDef,
 )
 
 
 def get_structure() -> ApplicationCredentialTypeDef:
     return {...}
@@ -398,43 +398,43 @@
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

### Comparing `types-aiobotocore-ssm-sap-2.5.0.post1/types_aiobotocore_ssm_sap.egg-info/SOURCES.txt` & `types-aiobotocore-ssm-sap-2.5.1/types_aiobotocore_ssm_sap.egg-info/SOURCES.txt`

 * *Files identical despite different names*

