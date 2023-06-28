# Comparing `tmp/types-aiobotocore-tnb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-tnb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-tnb-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-tnb-2.5.1.tar", last modified: Wed Jun 28 01:44:17 2023, max compression
```

## Comparing `types-aiobotocore-tnb-2.5.0.post1.tar` & `types-aiobotocore-tnb-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.891698 types-aiobotocore-tnb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18576 2023-03-11 12:27:27.891698 types-aiobotocore-tnb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17005 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:27.891698 types-aiobotocore-tnb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2088 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.891698 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/
--rw-r--r--   0 runner    (1001) docker     (123)     1775 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1774 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      948 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27164 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27117 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9701 2023-03-11 12:25:07.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9699 2023-03-11 12:25:07.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6946 2023-03-11 12:25:07.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6938 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    34133 2023-03-11 12:25:07.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    34104 2023-03-11 12:25:07.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:06.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.891698 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18576 2023-03-11 12:27:27.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:27.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:27.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:27.000000 types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.386227 types-aiobotocore-tnb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18564 2023-06-28 01:44:17.378226 types-aiobotocore-tnb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16999 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:17.386227 types-aiobotocore-tnb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2082 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.378226 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/
+-rw-r--r--   0 runner    (1001) docker     (123)     1775 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1774 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      936 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27273 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27226 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9910 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9908 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6836 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6829 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    34773 2023-06-28 01:41:56.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34742 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:55.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.378226 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18564 2023-06-28 01:44:17.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:17.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:17.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:17.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:17.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:17.000000 types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/LICENSE` & `types-aiobotocore-tnb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-tnb-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-tnb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-tnb"></a>
 
 # types-aiobotocore-tnb
 
 [![PyPI - types-aiobotocore-tnb](https://img.shields.io/pypi/v/types-aiobotocore-tnb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-tnb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-tnb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-tnb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-tnb?color=blue)](https://pypistats.org/packages/types-aiobotocore-tnb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TelcoNetworkBuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder)
+[aiobotocore.TelcoNetworkBuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder)
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
 [types-aiobotocore-tnb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -353,86 +353,86 @@
 `types_aiobotocore_tnb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_tnb.type_defs import (
     CancelSolNetworkOperationInputRequestTypeDef,
     CreateSolFunctionPackageInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateSolFunctionPackageOutputTypeDef,
     CreateSolNetworkInstanceInputRequestTypeDef,
+    CreateSolNetworkInstanceOutputTypeDef,
     CreateSolNetworkPackageInputRequestTypeDef,
+    CreateSolNetworkPackageOutputTypeDef,
     DeleteSolFunctionPackageInputRequestTypeDef,
     DeleteSolNetworkInstanceInputRequestTypeDef,
     DeleteSolNetworkPackageInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ErrorInfoTypeDef,
     ToscaOverrideTypeDef,
     GetSolFunctionInstanceInputRequestTypeDef,
     GetSolFunctionInstanceMetadataTypeDef,
     GetSolFunctionPackageContentInputRequestTypeDef,
+    GetSolFunctionPackageContentOutputTypeDef,
     GetSolFunctionPackageDescriptorInputRequestTypeDef,
+    GetSolFunctionPackageDescriptorOutputTypeDef,
     GetSolFunctionPackageInputRequestTypeDef,
     GetSolInstantiatedVnfInfoTypeDef,
     GetSolNetworkInstanceInputRequestTypeDef,
     GetSolNetworkInstanceMetadataTypeDef,
     LcmOperationInfoTypeDef,
     GetSolNetworkOperationInputRequestTypeDef,
     GetSolNetworkOperationMetadataTypeDef,
     ProblemDetailsTypeDef,
     GetSolNetworkPackageContentInputRequestTypeDef,
+    GetSolNetworkPackageContentOutputTypeDef,
     GetSolNetworkPackageDescriptorInputRequestTypeDef,
+    GetSolNetworkPackageDescriptorOutputTypeDef,
     GetSolNetworkPackageInputRequestTypeDef,
     GetSolVnfcResourceInfoMetadataTypeDef,
     InstantiateSolNetworkInstanceInputRequestTypeDef,
+    InstantiateSolNetworkInstanceOutputTypeDef,
     ListSolFunctionInstanceMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef,
     ListSolFunctionInstancesInputRequestTypeDef,
     ListSolFunctionPackageMetadataTypeDef,
+    ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef,
     ListSolFunctionPackagesInputRequestTypeDef,
     ListSolNetworkInstanceMetadataTypeDef,
+    ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef,
     ListSolNetworkInstancesInputRequestTypeDef,
     ListSolNetworkOperationsMetadataTypeDef,
+    ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef,
     ListSolNetworkOperationsInputRequestTypeDef,
     ListSolNetworkPackageMetadataTypeDef,
+    ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef,
     ListSolNetworkPackagesInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutSolFunctionPackageContentInputRequestTypeDef,
     PutSolNetworkPackageContentInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     TerminateSolNetworkInstanceInputRequestTypeDef,
+    TerminateSolNetworkInstanceOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateSolFunctionPackageInputRequestTypeDef,
+    UpdateSolFunctionPackageOutputTypeDef,
     UpdateSolNetworkModifyTypeDef,
+    UpdateSolNetworkInstanceOutputTypeDef,
     UpdateSolNetworkPackageInputRequestTypeDef,
+    UpdateSolNetworkPackageOutputTypeDef,
     ValidateSolFunctionPackageContentInputRequestTypeDef,
     ValidateSolNetworkPackageContentInputRequestTypeDef,
-    CreateSolFunctionPackageOutputTypeDef,
-    CreateSolNetworkInstanceOutputTypeDef,
-    CreateSolNetworkPackageOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetSolFunctionPackageContentOutputTypeDef,
-    GetSolFunctionPackageDescriptorOutputTypeDef,
-    GetSolNetworkPackageContentOutputTypeDef,
-    GetSolNetworkPackageDescriptorOutputTypeDef,
-    InstantiateSolNetworkInstanceOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    TerminateSolNetworkInstanceOutputTypeDef,
-    UpdateSolFunctionPackageOutputTypeDef,
-    UpdateSolNetworkInstanceOutputTypeDef,
-    UpdateSolNetworkPackageOutputTypeDef,
     GetSolNetworkOperationTaskDetailsTypeDef,
     FunctionArtifactMetaTypeDef,
     NetworkArtifactMetaTypeDef,
     GetSolNetworkInstanceOutputTypeDef,
     GetSolVnfcResourceInfoTypeDef,
     ListSolFunctionInstanceInfoTypeDef,
-    ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef,
-    ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef,
-    ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef,
-    ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef,
-    ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef,
     ListSolFunctionPackageInfoTypeDef,
     ListSolNetworkInstanceInfoTypeDef,
     ListSolNetworkOperationsInfoTypeDef,
     ListSolNetworkPackageInfoTypeDef,
     UpdateSolNetworkInstanceInputRequestTypeDef,
     GetSolNetworkOperationOutputTypeDef,
     GetSolFunctionPackageMetadataTypeDef,
@@ -464,43 +464,43 @@
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/README.md` & `types-aiobotocore-tnb-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-tnb"></a>
 
 # types-aiobotocore-tnb
 
 [![PyPI - types-aiobotocore-tnb](https://img.shields.io/pypi/v/types-aiobotocore-tnb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-tnb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-tnb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-tnb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-tnb?color=blue)](https://pypistats.org/packages/types-aiobotocore-tnb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TelcoNetworkBuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder)
+[aiobotocore.TelcoNetworkBuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder)
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
 [types-aiobotocore-tnb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,86 +320,86 @@
 `types_aiobotocore_tnb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_tnb.type_defs import (
     CancelSolNetworkOperationInputRequestTypeDef,
     CreateSolFunctionPackageInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateSolFunctionPackageOutputTypeDef,
     CreateSolNetworkInstanceInputRequestTypeDef,
+    CreateSolNetworkInstanceOutputTypeDef,
     CreateSolNetworkPackageInputRequestTypeDef,
+    CreateSolNetworkPackageOutputTypeDef,
     DeleteSolFunctionPackageInputRequestTypeDef,
     DeleteSolNetworkInstanceInputRequestTypeDef,
     DeleteSolNetworkPackageInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ErrorInfoTypeDef,
     ToscaOverrideTypeDef,
     GetSolFunctionInstanceInputRequestTypeDef,
     GetSolFunctionInstanceMetadataTypeDef,
     GetSolFunctionPackageContentInputRequestTypeDef,
+    GetSolFunctionPackageContentOutputTypeDef,
     GetSolFunctionPackageDescriptorInputRequestTypeDef,
+    GetSolFunctionPackageDescriptorOutputTypeDef,
     GetSolFunctionPackageInputRequestTypeDef,
     GetSolInstantiatedVnfInfoTypeDef,
     GetSolNetworkInstanceInputRequestTypeDef,
     GetSolNetworkInstanceMetadataTypeDef,
     LcmOperationInfoTypeDef,
     GetSolNetworkOperationInputRequestTypeDef,
     GetSolNetworkOperationMetadataTypeDef,
     ProblemDetailsTypeDef,
     GetSolNetworkPackageContentInputRequestTypeDef,
+    GetSolNetworkPackageContentOutputTypeDef,
     GetSolNetworkPackageDescriptorInputRequestTypeDef,
+    GetSolNetworkPackageDescriptorOutputTypeDef,
     GetSolNetworkPackageInputRequestTypeDef,
     GetSolVnfcResourceInfoMetadataTypeDef,
     InstantiateSolNetworkInstanceInputRequestTypeDef,
+    InstantiateSolNetworkInstanceOutputTypeDef,
     ListSolFunctionInstanceMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef,
     ListSolFunctionInstancesInputRequestTypeDef,
     ListSolFunctionPackageMetadataTypeDef,
+    ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef,
     ListSolFunctionPackagesInputRequestTypeDef,
     ListSolNetworkInstanceMetadataTypeDef,
+    ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef,
     ListSolNetworkInstancesInputRequestTypeDef,
     ListSolNetworkOperationsMetadataTypeDef,
+    ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef,
     ListSolNetworkOperationsInputRequestTypeDef,
     ListSolNetworkPackageMetadataTypeDef,
+    ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef,
     ListSolNetworkPackagesInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutSolFunctionPackageContentInputRequestTypeDef,
     PutSolNetworkPackageContentInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     TerminateSolNetworkInstanceInputRequestTypeDef,
+    TerminateSolNetworkInstanceOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateSolFunctionPackageInputRequestTypeDef,
+    UpdateSolFunctionPackageOutputTypeDef,
     UpdateSolNetworkModifyTypeDef,
+    UpdateSolNetworkInstanceOutputTypeDef,
     UpdateSolNetworkPackageInputRequestTypeDef,
+    UpdateSolNetworkPackageOutputTypeDef,
     ValidateSolFunctionPackageContentInputRequestTypeDef,
     ValidateSolNetworkPackageContentInputRequestTypeDef,
-    CreateSolFunctionPackageOutputTypeDef,
-    CreateSolNetworkInstanceOutputTypeDef,
-    CreateSolNetworkPackageOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetSolFunctionPackageContentOutputTypeDef,
-    GetSolFunctionPackageDescriptorOutputTypeDef,
-    GetSolNetworkPackageContentOutputTypeDef,
-    GetSolNetworkPackageDescriptorOutputTypeDef,
-    InstantiateSolNetworkInstanceOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    TerminateSolNetworkInstanceOutputTypeDef,
-    UpdateSolFunctionPackageOutputTypeDef,
-    UpdateSolNetworkInstanceOutputTypeDef,
-    UpdateSolNetworkPackageOutputTypeDef,
     GetSolNetworkOperationTaskDetailsTypeDef,
     FunctionArtifactMetaTypeDef,
     NetworkArtifactMetaTypeDef,
     GetSolNetworkInstanceOutputTypeDef,
     GetSolVnfcResourceInfoTypeDef,
     ListSolFunctionInstanceInfoTypeDef,
-    ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef,
-    ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef,
-    ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef,
-    ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef,
-    ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef,
     ListSolFunctionPackageInfoTypeDef,
     ListSolNetworkInstanceInfoTypeDef,
     ListSolNetworkOperationsInfoTypeDef,
     ListSolNetworkPackageInfoTypeDef,
     UpdateSolNetworkInstanceInputRequestTypeDef,
     GetSolNetworkOperationOutputTypeDef,
     GetSolFunctionPackageMetadataTypeDef,
@@ -431,43 +431,43 @@
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/setup.py` & `types-aiobotocore-tnb-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-tnb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-tnb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_tnb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/",
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/__init__.py` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/__init__.pyi` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/__main__.py` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder\nOther"
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/client.py` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -62,36 +62,32 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("TelcoNetworkBuilderClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class TelcoNetworkBuilderClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/)
     """
 
     meta: ClientMeta
@@ -100,446 +96,405 @@
     def exceptions(self) -> Exceptions:
         """
         TelcoNetworkBuilderClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#can_paginate)
         """
-
     async def cancel_sol_network_operation(
         self, *, nsLcmOpOccId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Cancels a network operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.cancel_sol_network_operation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#cancel_sol_network_operation)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#close)
         """
-
     async def create_sol_function_package(
         self, *, tags: Mapping[str, str] = ...
     ) -> CreateSolFunctionPackageOutputTypeDef:
         """
         Creates a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.create_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#create_sol_function_package)
         """
-
     async def create_sol_network_instance(
         self,
         *,
         nsName: str,
         nsdInfoId: str,
         nsDescription: str = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateSolNetworkInstanceOutputTypeDef:
         """
         Creates a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.create_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#create_sol_network_instance)
         """
-
     async def create_sol_network_package(
         self, *, tags: Mapping[str, str] = ...
     ) -> CreateSolNetworkPackageOutputTypeDef:
         """
         Creates a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.create_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#create_sol_network_package)
         """
-
     async def delete_sol_function_package(self, *, vnfPkgId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.delete_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#delete_sol_function_package)
         """
-
     async def delete_sol_network_instance(
         self, *, nsInstanceId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.delete_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#delete_sol_network_instance)
         """
-
     async def delete_sol_network_package(self, *, nsdInfoId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.delete_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#delete_sol_network_package)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#generate_presigned_url)
         """
-
     async def get_sol_function_instance(
         self, *, vnfInstanceId: str
     ) -> GetSolFunctionInstanceOutputTypeDef:
         """
         Gets the details of a network function instance, including the instantation
         state and metadata from the function package descriptor in the network function
         package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_instance)
         """
-
     async def get_sol_function_package(
         self, *, vnfPkgId: str
     ) -> GetSolFunctionPackageOutputTypeDef:
         """
         Gets the details of an individual function package, such as the operational
         state and whether the package is in use.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_package)
         """
-
     async def get_sol_function_package_content(
         self, *, accept: Literal["application/zip"], vnfPkgId: str
     ) -> GetSolFunctionPackageContentOutputTypeDef:
         """
         Gets the contents of a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_package_content)
         """
-
     async def get_sol_function_package_descriptor(
         self, *, accept: Literal["text/plain"], vnfPkgId: str
     ) -> GetSolFunctionPackageDescriptorOutputTypeDef:
         """
         Gets a function package descriptor in a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_package_descriptor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_package_descriptor)
         """
-
     async def get_sol_network_instance(
         self, *, nsInstanceId: str
     ) -> GetSolNetworkInstanceOutputTypeDef:
         """
         Gets the details of the network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_instance)
         """
-
     async def get_sol_network_operation(
         self, *, nsLcmOpOccId: str
     ) -> GetSolNetworkOperationOutputTypeDef:
         """
         Gets the details of a network operation, including the tasks involved in the
         network operation and the status of the tasks.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_operation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_operation)
         """
-
     async def get_sol_network_package(self, *, nsdInfoId: str) -> GetSolNetworkPackageOutputTypeDef:
         """
         Gets the details of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_package)
         """
-
     async def get_sol_network_package_content(
         self, *, accept: Literal["application/zip"], nsdInfoId: str
     ) -> GetSolNetworkPackageContentOutputTypeDef:
         """
         Gets the contents of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_package_content)
         """
-
     async def get_sol_network_package_descriptor(
         self, *, nsdInfoId: str
     ) -> GetSolNetworkPackageDescriptorOutputTypeDef:
         """
         Gets the content of the network service descriptor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_package_descriptor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_package_descriptor)
         """
-
     async def instantiate_sol_network_instance(
         self,
         *,
         nsInstanceId: str,
         additionalParamsForNs: Mapping[str, Any] = ...,
-        dryRun: bool = ...
+        dryRun: bool = ...,
+        tags: Mapping[str, str] = ...
     ) -> InstantiateSolNetworkInstanceOutputTypeDef:
         """
         Instantiates a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.instantiate_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#instantiate_sol_network_instance)
         """
-
     async def list_sol_function_instances(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolFunctionInstancesOutputTypeDef:
         """
         Lists network function instances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_function_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_function_instances)
         """
-
     async def list_sol_function_packages(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolFunctionPackagesOutputTypeDef:
         """
         Lists information about function packages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_function_packages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_function_packages)
         """
-
     async def list_sol_network_instances(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolNetworkInstancesOutputTypeDef:
         """
         Lists your network instances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_network_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_network_instances)
         """
-
     async def list_sol_network_operations(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolNetworkOperationsOutputTypeDef:
         """
         Lists details for a network operation, including when the operation started and
         the status of the operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_network_operations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_network_operations)
         """
-
     async def list_sol_network_packages(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolNetworkPackagesOutputTypeDef:
         """
         Lists network packages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_network_packages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_network_packages)
         """
-
     async def list_tags_for_resource(self, *, resourceArn: str) -> ListTagsForResourceOutputTypeDef:
         """
         Lists tags for AWS TNB resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_tags_for_resource)
         """
-
     async def put_sol_function_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         vnfPkgId: str,
         contentType: Literal["application/zip"] = ...
     ) -> PutSolFunctionPackageContentOutputTypeDef:
         """
         Uploads the contents of a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.put_sol_function_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#put_sol_function_package_content)
         """
-
     async def put_sol_network_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         nsdInfoId: str,
         contentType: Literal["application/zip"] = ...
     ) -> PutSolNetworkPackageContentOutputTypeDef:
         """
         Uploads the contents of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.put_sol_network_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#put_sol_network_package_content)
         """
-
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Tags an AWS TNB resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#tag_resource)
         """
-
     async def terminate_sol_network_instance(
-        self, *, nsInstanceId: str
+        self, *, nsInstanceId: str, tags: Mapping[str, str] = ...
     ) -> TerminateSolNetworkInstanceOutputTypeDef:
         """
         Terminates a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.terminate_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#terminate_sol_network_instance)
         """
-
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Untags an AWS TNB resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#untag_resource)
         """
-
     async def update_sol_function_package(
         self, *, operationalState: OperationalStateType, vnfPkgId: str
     ) -> UpdateSolFunctionPackageOutputTypeDef:
         """
         Updates the operational state of function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.update_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#update_sol_function_package)
         """
-
     async def update_sol_network_instance(
         self,
         *,
         nsInstanceId: str,
         updateType: Literal["MODIFY_VNF_INFORMATION"],
-        modifyVnfInfoData: UpdateSolNetworkModifyTypeDef = ...
+        modifyVnfInfoData: UpdateSolNetworkModifyTypeDef = ...,
+        tags: Mapping[str, str] = ...
     ) -> UpdateSolNetworkInstanceOutputTypeDef:
         """
         Update a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.update_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#update_sol_network_instance)
         """
-
     async def update_sol_network_package(
         self, *, nsdInfoId: str, nsdOperationalState: NsdOperationalStateType
     ) -> UpdateSolNetworkPackageOutputTypeDef:
         """
         Updates the operational state of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.update_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#update_sol_network_package)
         """
-
     async def validate_sol_function_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         vnfPkgId: str,
         contentType: Literal["application/zip"] = ...
     ) -> ValidateSolFunctionPackageContentOutputTypeDef:
         """
         Validates function package content.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.validate_sol_function_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#validate_sol_function_package_content)
         """
-
     async def validate_sol_network_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         nsdInfoId: str,
         contentType: Literal["application/zip"] = ...
     ) -> ValidateSolNetworkPackageContentOutputTypeDef:
         """
         Validates network package content.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.validate_sol_network_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#validate_sol_network_package_content)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_function_instances"]
     ) -> ListSolFunctionInstancesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_function_packages"]
     ) -> ListSolFunctionPackagesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_network_instances"]
     ) -> ListSolNetworkInstancesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_network_operations"]
     ) -> ListSolNetworkOperationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_network_packages"]
     ) -> ListSolNetworkPackagesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "TelcoNetworkBuilderClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/)
         """
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/client.pyi` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -62,32 +62,36 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("TelcoNetworkBuilderClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class TelcoNetworkBuilderClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/)
     """
 
     meta: ClientMeta
@@ -96,403 +100,448 @@
     def exceptions(self) -> Exceptions:
         """
         TelcoNetworkBuilderClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#can_paginate)
         """
+
     async def cancel_sol_network_operation(
         self, *, nsLcmOpOccId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Cancels a network operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.cancel_sol_network_operation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#cancel_sol_network_operation)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#close)
         """
+
     async def create_sol_function_package(
         self, *, tags: Mapping[str, str] = ...
     ) -> CreateSolFunctionPackageOutputTypeDef:
         """
         Creates a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.create_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#create_sol_function_package)
         """
+
     async def create_sol_network_instance(
         self,
         *,
         nsName: str,
         nsdInfoId: str,
         nsDescription: str = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateSolNetworkInstanceOutputTypeDef:
         """
         Creates a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.create_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#create_sol_network_instance)
         """
+
     async def create_sol_network_package(
         self, *, tags: Mapping[str, str] = ...
     ) -> CreateSolNetworkPackageOutputTypeDef:
         """
         Creates a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.create_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#create_sol_network_package)
         """
+
     async def delete_sol_function_package(self, *, vnfPkgId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.delete_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#delete_sol_function_package)
         """
+
     async def delete_sol_network_instance(
         self, *, nsInstanceId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.delete_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#delete_sol_network_instance)
         """
+
     async def delete_sol_network_package(self, *, nsdInfoId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.delete_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#delete_sol_network_package)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#generate_presigned_url)
         """
+
     async def get_sol_function_instance(
         self, *, vnfInstanceId: str
     ) -> GetSolFunctionInstanceOutputTypeDef:
         """
         Gets the details of a network function instance, including the instantation
         state and metadata from the function package descriptor in the network function
         package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_instance)
         """
+
     async def get_sol_function_package(
         self, *, vnfPkgId: str
     ) -> GetSolFunctionPackageOutputTypeDef:
         """
         Gets the details of an individual function package, such as the operational
         state and whether the package is in use.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_package)
         """
+
     async def get_sol_function_package_content(
         self, *, accept: Literal["application/zip"], vnfPkgId: str
     ) -> GetSolFunctionPackageContentOutputTypeDef:
         """
         Gets the contents of a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_package_content)
         """
+
     async def get_sol_function_package_descriptor(
         self, *, accept: Literal["text/plain"], vnfPkgId: str
     ) -> GetSolFunctionPackageDescriptorOutputTypeDef:
         """
         Gets a function package descriptor in a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_function_package_descriptor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_function_package_descriptor)
         """
+
     async def get_sol_network_instance(
         self, *, nsInstanceId: str
     ) -> GetSolNetworkInstanceOutputTypeDef:
         """
         Gets the details of the network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_instance)
         """
+
     async def get_sol_network_operation(
         self, *, nsLcmOpOccId: str
     ) -> GetSolNetworkOperationOutputTypeDef:
         """
         Gets the details of a network operation, including the tasks involved in the
         network operation and the status of the tasks.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_operation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_operation)
         """
+
     async def get_sol_network_package(self, *, nsdInfoId: str) -> GetSolNetworkPackageOutputTypeDef:
         """
         Gets the details of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_package)
         """
+
     async def get_sol_network_package_content(
         self, *, accept: Literal["application/zip"], nsdInfoId: str
     ) -> GetSolNetworkPackageContentOutputTypeDef:
         """
         Gets the contents of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_package_content)
         """
+
     async def get_sol_network_package_descriptor(
         self, *, nsdInfoId: str
     ) -> GetSolNetworkPackageDescriptorOutputTypeDef:
         """
         Gets the content of the network service descriptor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_sol_network_package_descriptor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_sol_network_package_descriptor)
         """
+
     async def instantiate_sol_network_instance(
         self,
         *,
         nsInstanceId: str,
         additionalParamsForNs: Mapping[str, Any] = ...,
-        dryRun: bool = ...
+        dryRun: bool = ...,
+        tags: Mapping[str, str] = ...
     ) -> InstantiateSolNetworkInstanceOutputTypeDef:
         """
         Instantiates a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.instantiate_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#instantiate_sol_network_instance)
         """
+
     async def list_sol_function_instances(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolFunctionInstancesOutputTypeDef:
         """
         Lists network function instances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_function_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_function_instances)
         """
+
     async def list_sol_function_packages(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolFunctionPackagesOutputTypeDef:
         """
         Lists information about function packages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_function_packages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_function_packages)
         """
+
     async def list_sol_network_instances(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolNetworkInstancesOutputTypeDef:
         """
         Lists your network instances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_network_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_network_instances)
         """
+
     async def list_sol_network_operations(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolNetworkOperationsOutputTypeDef:
         """
         Lists details for a network operation, including when the operation started and
         the status of the operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_network_operations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_network_operations)
         """
+
     async def list_sol_network_packages(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSolNetworkPackagesOutputTypeDef:
         """
         Lists network packages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_sol_network_packages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_sol_network_packages)
         """
+
     async def list_tags_for_resource(self, *, resourceArn: str) -> ListTagsForResourceOutputTypeDef:
         """
         Lists tags for AWS TNB resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#list_tags_for_resource)
         """
+
     async def put_sol_function_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         vnfPkgId: str,
         contentType: Literal["application/zip"] = ...
     ) -> PutSolFunctionPackageContentOutputTypeDef:
         """
         Uploads the contents of a function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.put_sol_function_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#put_sol_function_package_content)
         """
+
     async def put_sol_network_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         nsdInfoId: str,
         contentType: Literal["application/zip"] = ...
     ) -> PutSolNetworkPackageContentOutputTypeDef:
         """
         Uploads the contents of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.put_sol_network_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#put_sol_network_package_content)
         """
+
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Tags an AWS TNB resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#tag_resource)
         """
+
     async def terminate_sol_network_instance(
-        self, *, nsInstanceId: str
+        self, *, nsInstanceId: str, tags: Mapping[str, str] = ...
     ) -> TerminateSolNetworkInstanceOutputTypeDef:
         """
         Terminates a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.terminate_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#terminate_sol_network_instance)
         """
+
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Untags an AWS TNB resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#untag_resource)
         """
+
     async def update_sol_function_package(
         self, *, operationalState: OperationalStateType, vnfPkgId: str
     ) -> UpdateSolFunctionPackageOutputTypeDef:
         """
         Updates the operational state of function package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.update_sol_function_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#update_sol_function_package)
         """
+
     async def update_sol_network_instance(
         self,
         *,
         nsInstanceId: str,
         updateType: Literal["MODIFY_VNF_INFORMATION"],
-        modifyVnfInfoData: UpdateSolNetworkModifyTypeDef = ...
+        modifyVnfInfoData: UpdateSolNetworkModifyTypeDef = ...,
+        tags: Mapping[str, str] = ...
     ) -> UpdateSolNetworkInstanceOutputTypeDef:
         """
         Update a network instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.update_sol_network_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#update_sol_network_instance)
         """
+
     async def update_sol_network_package(
         self, *, nsdInfoId: str, nsdOperationalState: NsdOperationalStateType
     ) -> UpdateSolNetworkPackageOutputTypeDef:
         """
         Updates the operational state of a network package.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.update_sol_network_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#update_sol_network_package)
         """
+
     async def validate_sol_function_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         vnfPkgId: str,
         contentType: Literal["application/zip"] = ...
     ) -> ValidateSolFunctionPackageContentOutputTypeDef:
         """
         Validates function package content.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.validate_sol_function_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#validate_sol_function_package_content)
         """
+
     async def validate_sol_network_package_content(
         self,
         *,
         file: Union[str, bytes, IO[Any], StreamingBody],
         nsdInfoId: str,
         contentType: Literal["application/zip"] = ...
     ) -> ValidateSolNetworkPackageContentOutputTypeDef:
         """
         Validates network package content.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.validate_sol_network_package_content)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#validate_sol_network_package_content)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_function_instances"]
     ) -> ListSolFunctionInstancesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_function_packages"]
     ) -> ListSolFunctionPackagesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_network_instances"]
     ) -> ListSolNetworkInstancesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_network_operations"]
     ) -> ListSolNetworkOperationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sol_network_packages"]
     ) -> ListSolNetworkPackagesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "TelcoNetworkBuilderClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/client/)
         """
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/literals.py` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DescriptorContentTypeType",
     "LcmOperationTypeType",
     "ListSolFunctionInstancesPaginatorName",
     "ListSolFunctionPackagesPaginatorName",
     "ListSolNetworkInstancesPaginatorName",
     "ListSolNetworkOperationsPaginatorName",
@@ -42,15 +41,14 @@
     "VnfOperationalStateType",
     "TelcoNetworkBuilderServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 DescriptorContentTypeType = Literal["text/plain"]
 LcmOperationTypeType = Literal["INSTANTIATE", "TERMINATE", "UPDATE"]
 ListSolFunctionInstancesPaginatorName = Literal["list_sol_function_instances"]
 ListSolFunctionPackagesPaginatorName = Literal["list_sol_function_packages"]
 ListSolNetworkInstancesPaginatorName = Literal["list_sol_network_instances"]
 ListSolNetworkOperationsPaginatorName = Literal["list_sol_network_operations"]
 ListSolNetworkPackagesPaginatorName = Literal["list_sol_network_packages"]
@@ -137,14 +135,15 @@
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
@@ -223,14 +222,15 @@
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
@@ -241,14 +241,15 @@
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
@@ -284,14 +285,15 @@
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
@@ -310,16 +312,19 @@
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
@@ -403,15 +408,17 @@
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/literals.pyi` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DescriptorContentTypeType",
     "LcmOperationTypeType",
     "ListSolFunctionInstancesPaginatorName",
     "ListSolFunctionPackagesPaginatorName",
     "ListSolNetworkInstancesPaginatorName",
     "ListSolNetworkOperationsPaginatorName",
@@ -41,14 +42,15 @@
     "VnfOperationalStateType",
     "TelcoNetworkBuilderServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 DescriptorContentTypeType = Literal["text/plain"]
 LcmOperationTypeType = Literal["INSTANTIATE", "TERMINATE", "UPDATE"]
 ListSolFunctionInstancesPaginatorName = Literal["list_sol_function_instances"]
 ListSolFunctionPackagesPaginatorName = Literal["list_sol_function_packages"]
 ListSolNetworkInstancesPaginatorName = Literal["list_sol_network_instances"]
 ListSolNetworkOperationsPaginatorName = Literal["list_sol_network_operations"]
 ListSolNetworkPackagesPaginatorName = Literal["list_sol_network_packages"]
@@ -135,14 +137,15 @@
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
@@ -221,14 +224,15 @@
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
@@ -239,14 +243,15 @@
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
@@ -282,14 +287,15 @@
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
@@ -308,16 +314,19 @@
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
@@ -401,15 +410,17 @@
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/paginator.py` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_sol_function_instances_paginator: ListSolFunctionInstancesPaginator = client.get_paginator("list_sol_function_instances")
         list_sol_function_packages_paginator: ListSolFunctionPackagesPaginator = client.get_paginator("list_sol_function_packages")
         list_sol_network_instances_paginator: ListSolNetworkInstancesPaginator = client.get_paginator("list_sol_network_instances")
         list_sol_network_operations_paginator: ListSolNetworkOperationsPaginator = client.get_paginator("list_sol_network_operations")
         list_sol_network_packages_paginator: ListSolNetworkPackagesPaginator = client.get_paginator("list_sol_network_packages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListSolFunctionInstancesOutputTypeDef,
     ListSolFunctionPackagesOutputTypeDef,
     ListSolNetworkInstancesOutputTypeDef,
     ListSolNetworkOperationsOutputTypeDef,
     ListSolNetworkPackagesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListSolFunctionInstancesPaginator",
     "ListSolFunctionPackagesPaginator",
     "ListSolNetworkInstancesPaginator",
     "ListSolNetworkOperationsPaginator",
     "ListSolNetworkPackagesPaginator",
 )
@@ -71,73 +64,73 @@
 class ListSolFunctionInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctioninstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolFunctionInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctioninstancespaginator)
         """
 
 
 class ListSolFunctionPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctionpackagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolFunctionPackagesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctionpackagespaginator)
         """
 
 
 class ListSolNetworkInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolNetworkInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkinstancespaginator)
         """
 
 
 class ListSolNetworkOperationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkOperations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkoperationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolNetworkOperationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkoperationspaginator)
         """
 
 
 class ListSolNetworkPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkpackagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolNetworkPackagesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkpackagespaginator)
         """
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/paginator.pyi` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_sol_function_instances_paginator: ListSolFunctionInstancesPaginator = client.get_paginator("list_sol_function_instances")
         list_sol_function_packages_paginator: ListSolFunctionPackagesPaginator = client.get_paginator("list_sol_function_packages")
         list_sol_network_instances_paginator: ListSolNetworkInstancesPaginator = client.get_paginator("list_sol_network_instances")
         list_sol_network_operations_paginator: ListSolNetworkOperationsPaginator = client.get_paginator("list_sol_network_operations")
         list_sol_network_packages_paginator: ListSolNetworkPackagesPaginator = client.get_paginator("list_sol_network_packages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListSolFunctionInstancesOutputTypeDef,
     ListSolFunctionPackagesOutputTypeDef,
     ListSolNetworkInstancesOutputTypeDef,
     ListSolNetworkOperationsOutputTypeDef,
     ListSolNetworkPackagesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListSolFunctionInstancesPaginator",
     "ListSolFunctionPackagesPaginator",
     "ListSolNetworkInstancesPaginator",
     "ListSolNetworkOperationsPaginator",
     "ListSolNetworkPackagesPaginator",
 )
@@ -67,69 +61,69 @@
 class ListSolFunctionInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctioninstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolFunctionInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctioninstancespaginator)
         """
 
 class ListSolFunctionPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctionpackagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolFunctionPackagesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolFunctionPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolfunctionpackagespaginator)
         """
 
 class ListSolNetworkInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolNetworkInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkinstancespaginator)
         """
 
 class ListSolNetworkOperationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkOperations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkoperationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolNetworkOperationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkoperationspaginator)
         """
 
 class ListSolNetworkPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkpackagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolNetworkPackagesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder.Paginator.ListSolNetworkPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/paginators/#listsolnetworkpackagespaginator)
         """
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/type_defs.py` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -41,86 +41,86 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelSolNetworkOperationInputRequestTypeDef",
     "CreateSolFunctionPackageInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateSolFunctionPackageOutputTypeDef",
     "CreateSolNetworkInstanceInputRequestTypeDef",
+    "CreateSolNetworkInstanceOutputTypeDef",
     "CreateSolNetworkPackageInputRequestTypeDef",
+    "CreateSolNetworkPackageOutputTypeDef",
     "DeleteSolFunctionPackageInputRequestTypeDef",
     "DeleteSolNetworkInstanceInputRequestTypeDef",
     "DeleteSolNetworkPackageInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ErrorInfoTypeDef",
     "ToscaOverrideTypeDef",
     "GetSolFunctionInstanceInputRequestTypeDef",
     "GetSolFunctionInstanceMetadataTypeDef",
     "GetSolFunctionPackageContentInputRequestTypeDef",
+    "GetSolFunctionPackageContentOutputTypeDef",
     "GetSolFunctionPackageDescriptorInputRequestTypeDef",
+    "GetSolFunctionPackageDescriptorOutputTypeDef",
     "GetSolFunctionPackageInputRequestTypeDef",
     "GetSolInstantiatedVnfInfoTypeDef",
     "GetSolNetworkInstanceInputRequestTypeDef",
     "GetSolNetworkInstanceMetadataTypeDef",
     "LcmOperationInfoTypeDef",
     "GetSolNetworkOperationInputRequestTypeDef",
     "GetSolNetworkOperationMetadataTypeDef",
     "ProblemDetailsTypeDef",
     "GetSolNetworkPackageContentInputRequestTypeDef",
+    "GetSolNetworkPackageContentOutputTypeDef",
     "GetSolNetworkPackageDescriptorInputRequestTypeDef",
+    "GetSolNetworkPackageDescriptorOutputTypeDef",
     "GetSolNetworkPackageInputRequestTypeDef",
     "GetSolVnfcResourceInfoMetadataTypeDef",
     "InstantiateSolNetworkInstanceInputRequestTypeDef",
+    "InstantiateSolNetworkInstanceOutputTypeDef",
     "ListSolFunctionInstanceMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
     "ListSolFunctionInstancesInputRequestTypeDef",
     "ListSolFunctionPackageMetadataTypeDef",
+    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
     "ListSolFunctionPackagesInputRequestTypeDef",
     "ListSolNetworkInstanceMetadataTypeDef",
+    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
     "ListSolNetworkInstancesInputRequestTypeDef",
     "ListSolNetworkOperationsMetadataTypeDef",
+    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
     "ListSolNetworkOperationsInputRequestTypeDef",
     "ListSolNetworkPackageMetadataTypeDef",
+    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
     "ListSolNetworkPackagesInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutSolFunctionPackageContentInputRequestTypeDef",
     "PutSolNetworkPackageContentInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "TerminateSolNetworkInstanceInputRequestTypeDef",
+    "TerminateSolNetworkInstanceOutputTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateSolFunctionPackageInputRequestTypeDef",
+    "UpdateSolFunctionPackageOutputTypeDef",
     "UpdateSolNetworkModifyTypeDef",
+    "UpdateSolNetworkInstanceOutputTypeDef",
     "UpdateSolNetworkPackageInputRequestTypeDef",
+    "UpdateSolNetworkPackageOutputTypeDef",
     "ValidateSolFunctionPackageContentInputRequestTypeDef",
     "ValidateSolNetworkPackageContentInputRequestTypeDef",
-    "CreateSolFunctionPackageOutputTypeDef",
-    "CreateSolNetworkInstanceOutputTypeDef",
-    "CreateSolNetworkPackageOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetSolFunctionPackageContentOutputTypeDef",
-    "GetSolFunctionPackageDescriptorOutputTypeDef",
-    "GetSolNetworkPackageContentOutputTypeDef",
-    "GetSolNetworkPackageDescriptorOutputTypeDef",
-    "InstantiateSolNetworkInstanceOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "TerminateSolNetworkInstanceOutputTypeDef",
-    "UpdateSolFunctionPackageOutputTypeDef",
-    "UpdateSolNetworkInstanceOutputTypeDef",
-    "UpdateSolNetworkPackageOutputTypeDef",
     "GetSolNetworkOperationTaskDetailsTypeDef",
     "FunctionArtifactMetaTypeDef",
     "NetworkArtifactMetaTypeDef",
     "GetSolNetworkInstanceOutputTypeDef",
     "GetSolVnfcResourceInfoTypeDef",
     "ListSolFunctionInstanceInfoTypeDef",
-    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
-    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
-    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
-    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
-    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
     "ListSolFunctionPackageInfoTypeDef",
     "ListSolNetworkInstanceInfoTypeDef",
     "ListSolNetworkOperationsInfoTypeDef",
     "ListSolNetworkPackageInfoTypeDef",
     "UpdateSolNetworkInstanceInputRequestTypeDef",
     "GetSolNetworkOperationOutputTypeDef",
     "GetSolFunctionPackageMetadataTypeDef",
@@ -155,22 +155,24 @@
     "CreateSolFunctionPackageInputRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateSolFunctionPackageOutputTypeDef = TypedDict(
+    "CreateSolFunctionPackageOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "id": str,
+        "onboardingState": OnboardingStateType,
+        "operationalState": OperationalStateType,
+        "tags": Dict[str, str],
+        "usageState": UsageStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSolNetworkInstanceInputRequestTypeDef = TypedDict(
     "_RequiredCreateSolNetworkInstanceInputRequestTypeDef",
     {
         "nsName": str,
@@ -190,22 +192,47 @@
 class CreateSolNetworkInstanceInputRequestTypeDef(
     _RequiredCreateSolNetworkInstanceInputRequestTypeDef,
     _OptionalCreateSolNetworkInstanceInputRequestTypeDef,
 ):
     pass
 
 
+CreateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "CreateSolNetworkInstanceOutputTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "nsInstanceName": str,
+        "nsdInfoId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateSolNetworkPackageInputRequestTypeDef = TypedDict(
     "CreateSolNetworkPackageInputRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+CreateSolNetworkPackageOutputTypeDef = TypedDict(
+    "CreateSolNetworkPackageOutputTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "nsdOnboardingState": NsdOnboardingStateType,
+        "nsdOperationalState": NsdOperationalStateType,
+        "nsdUsageState": NsdUsageStateType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSolFunctionPackageInputRequestTypeDef = TypedDict(
     "DeleteSolFunctionPackageInputRequestTypeDef",
     {
         "vnfPkgId": str,
     },
 )
 
@@ -219,14 +246,21 @@
 DeleteSolNetworkPackageInputRequestTypeDef = TypedDict(
     "DeleteSolNetworkPackageInputRequestTypeDef",
     {
         "nsdInfoId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ErrorInfoTypeDef = TypedDict(
     "ErrorInfoTypeDef",
     {
         "cause": str,
         "details": str,
     },
     total=False,
@@ -260,22 +294,40 @@
     "GetSolFunctionPackageContentInputRequestTypeDef",
     {
         "accept": Literal["application/zip"],
         "vnfPkgId": str,
     },
 )
 
+GetSolFunctionPackageContentOutputTypeDef = TypedDict(
+    "GetSolFunctionPackageContentOutputTypeDef",
+    {
+        "contentType": Literal["application/zip"],
+        "packageContent": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolFunctionPackageDescriptorInputRequestTypeDef = TypedDict(
     "GetSolFunctionPackageDescriptorInputRequestTypeDef",
     {
         "accept": Literal["text/plain"],
         "vnfPkgId": str,
     },
 )
 
+GetSolFunctionPackageDescriptorOutputTypeDef = TypedDict(
+    "GetSolFunctionPackageDescriptorOutputTypeDef",
+    {
+        "contentType": Literal["text/plain"],
+        "vnfd": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolFunctionPackageInputRequestTypeDef = TypedDict(
     "GetSolFunctionPackageInputRequestTypeDef",
     {
         "vnfPkgId": str,
     },
 )
 
@@ -347,21 +399,39 @@
     "GetSolNetworkPackageContentInputRequestTypeDef",
     {
         "accept": Literal["application/zip"],
         "nsdInfoId": str,
     },
 )
 
+GetSolNetworkPackageContentOutputTypeDef = TypedDict(
+    "GetSolNetworkPackageContentOutputTypeDef",
+    {
+        "contentType": Literal["application/zip"],
+        "nsdContent": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolNetworkPackageDescriptorInputRequestTypeDef = TypedDict(
     "GetSolNetworkPackageDescriptorInputRequestTypeDef",
     {
         "nsdInfoId": str,
     },
 )
 
+GetSolNetworkPackageDescriptorOutputTypeDef = TypedDict(
+    "GetSolNetworkPackageDescriptorOutputTypeDef",
+    {
+        "contentType": Literal["text/plain"],
+        "nsd": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolNetworkPackageInputRequestTypeDef = TypedDict(
     "GetSolNetworkPackageInputRequestTypeDef",
     {
         "nsdInfoId": str,
     },
 )
 
@@ -382,40 +452,48 @@
     },
 )
 _OptionalInstantiateSolNetworkInstanceInputRequestTypeDef = TypedDict(
     "_OptionalInstantiateSolNetworkInstanceInputRequestTypeDef",
     {
         "additionalParamsForNs": Mapping[str, Any],
         "dryRun": bool,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class InstantiateSolNetworkInstanceInputRequestTypeDef(
     _RequiredInstantiateSolNetworkInstanceInputRequestTypeDef,
     _OptionalInstantiateSolNetworkInstanceInputRequestTypeDef,
 ):
     pass
 
 
+InstantiateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "InstantiateSolNetworkInstanceOutputTypeDef",
+    {
+        "nsLcmOpOccId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListSolFunctionInstanceMetadataTypeDef = TypedDict(
     "ListSolFunctionInstanceMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef = TypedDict(
+    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSolFunctionInstancesInputRequestTypeDef = TypedDict(
     "ListSolFunctionInstancesInputRequestTypeDef",
     {
@@ -429,14 +507,22 @@
     "ListSolFunctionPackageMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef = TypedDict(
+    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolFunctionPackagesInputRequestTypeDef = TypedDict(
     "ListSolFunctionPackagesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -446,14 +532,22 @@
     "ListSolNetworkInstanceMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef = TypedDict(
+    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolNetworkInstancesInputRequestTypeDef = TypedDict(
     "ListSolNetworkInstancesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -463,14 +557,22 @@
     "ListSolNetworkOperationsMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef = TypedDict(
+    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolNetworkOperationsInputRequestTypeDef = TypedDict(
     "ListSolNetworkOperationsInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -480,14 +582,22 @@
     "ListSolNetworkPackageMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef = TypedDict(
+    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolNetworkPackagesInputRequestTypeDef = TypedDict(
     "ListSolNetworkPackagesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -496,14 +606,32 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
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
 _RequiredPutSolFunctionPackageContentInputRequestTypeDef = TypedDict(
     "_RequiredPutSolFunctionPackageContentInputRequestTypeDef",
     {
         "file": Union[str, bytes, IO[Any], StreamingBody],
         "vnfPkgId": str,
     },
 )
@@ -542,28 +670,63 @@
 class PutSolNetworkPackageContentInputRequestTypeDef(
     _RequiredPutSolNetworkPackageContentInputRequestTypeDef,
     _OptionalPutSolNetworkPackageContentInputRequestTypeDef,
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
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
 
-TerminateSolNetworkInstanceInputRequestTypeDef = TypedDict(
-    "TerminateSolNetworkInstanceInputRequestTypeDef",
+_RequiredTerminateSolNetworkInstanceInputRequestTypeDef = TypedDict(
+    "_RequiredTerminateSolNetworkInstanceInputRequestTypeDef",
     {
         "nsInstanceId": str,
     },
 )
+_OptionalTerminateSolNetworkInstanceInputRequestTypeDef = TypedDict(
+    "_OptionalTerminateSolNetworkInstanceInputRequestTypeDef",
+    {
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class TerminateSolNetworkInstanceInputRequestTypeDef(
+    _RequiredTerminateSolNetworkInstanceInputRequestTypeDef,
+    _OptionalTerminateSolNetworkInstanceInputRequestTypeDef,
+):
+    pass
+
+
+TerminateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "TerminateSolNetworkInstanceOutputTypeDef",
+    {
+        "nsLcmOpOccId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
@@ -573,30 +736,55 @@
     "UpdateSolFunctionPackageInputRequestTypeDef",
     {
         "operationalState": OperationalStateType,
         "vnfPkgId": str,
     },
 )
 
+UpdateSolFunctionPackageOutputTypeDef = TypedDict(
+    "UpdateSolFunctionPackageOutputTypeDef",
+    {
+        "operationalState": OperationalStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSolNetworkModifyTypeDef = TypedDict(
     "UpdateSolNetworkModifyTypeDef",
     {
         "vnfConfigurableProperties": Mapping[str, Any],
         "vnfInstanceId": str,
     },
 )
 
+UpdateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "UpdateSolNetworkInstanceOutputTypeDef",
+    {
+        "nsLcmOpOccId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSolNetworkPackageInputRequestTypeDef = TypedDict(
     "UpdateSolNetworkPackageInputRequestTypeDef",
     {
         "nsdInfoId": str,
         "nsdOperationalState": NsdOperationalStateType,
     },
 )
 
+UpdateSolNetworkPackageOutputTypeDef = TypedDict(
+    "UpdateSolNetworkPackageOutputTypeDef",
+    {
+        "nsdOperationalState": NsdOperationalStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredValidateSolFunctionPackageContentInputRequestTypeDef = TypedDict(
     "_RequiredValidateSolFunctionPackageContentInputRequestTypeDef",
     {
         "file": Union[str, bytes, IO[Any], StreamingBody],
         "vnfPkgId": str,
     },
 )
@@ -635,143 +823,14 @@
 class ValidateSolNetworkPackageContentInputRequestTypeDef(
     _RequiredValidateSolNetworkPackageContentInputRequestTypeDef,
     _OptionalValidateSolNetworkPackageContentInputRequestTypeDef,
 ):
     pass
 
 
-CreateSolFunctionPackageOutputTypeDef = TypedDict(
-    "CreateSolFunctionPackageOutputTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "onboardingState": OnboardingStateType,
-        "operationalState": OperationalStateType,
-        "tags": Dict[str, str],
-        "usageState": UsageStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "CreateSolNetworkInstanceOutputTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "nsInstanceName": str,
-        "nsdInfoId": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolNetworkPackageOutputTypeDef = TypedDict(
-    "CreateSolNetworkPackageOutputTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "nsdOnboardingState": NsdOnboardingStateType,
-        "nsdOperationalState": NsdOperationalStateType,
-        "nsdUsageState": NsdUsageStateType,
-        "tags": Dict[str, str],
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
-GetSolFunctionPackageContentOutputTypeDef = TypedDict(
-    "GetSolFunctionPackageContentOutputTypeDef",
-    {
-        "contentType": Literal["application/zip"],
-        "packageContent": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSolFunctionPackageDescriptorOutputTypeDef = TypedDict(
-    "GetSolFunctionPackageDescriptorOutputTypeDef",
-    {
-        "contentType": Literal["text/plain"],
-        "vnfd": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSolNetworkPackageContentOutputTypeDef = TypedDict(
-    "GetSolNetworkPackageContentOutputTypeDef",
-    {
-        "contentType": Literal["application/zip"],
-        "nsdContent": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSolNetworkPackageDescriptorOutputTypeDef = TypedDict(
-    "GetSolNetworkPackageDescriptorOutputTypeDef",
-    {
-        "contentType": Literal["text/plain"],
-        "nsd": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InstantiateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "InstantiateSolNetworkInstanceOutputTypeDef",
-    {
-        "nsLcmOpOccId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "TerminateSolNetworkInstanceOutputTypeDef",
-    {
-        "nsLcmOpOccId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSolFunctionPackageOutputTypeDef = TypedDict(
-    "UpdateSolFunctionPackageOutputTypeDef",
-    {
-        "operationalState": OperationalStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "UpdateSolNetworkInstanceOutputTypeDef",
-    {
-        "nsLcmOpOccId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSolNetworkPackageOutputTypeDef = TypedDict(
-    "UpdateSolNetworkPackageOutputTypeDef",
-    {
-        "nsdOperationalState": NsdOperationalStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetSolNetworkOperationTaskDetailsTypeDef = TypedDict(
     "GetSolNetworkOperationTaskDetailsTypeDef",
     {
         "taskContext": Dict[str, str],
         "taskEndTime": datetime,
         "taskErrorDetails": ErrorInfoTypeDef,
         "taskName": str,
@@ -806,15 +865,15 @@
         "metadata": GetSolNetworkInstanceMetadataTypeDef,
         "nsInstanceDescription": str,
         "nsInstanceName": str,
         "nsState": NsStateType,
         "nsdId": str,
         "nsdInfoId": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolVnfcResourceInfoTypeDef = TypedDict(
     "GetSolVnfcResourceInfoTypeDef",
     {
         "metadata": GetSolVnfcResourceInfoMetadataTypeDef,
@@ -845,54 +904,14 @@
 
 class ListSolFunctionInstanceInfoTypeDef(
     _RequiredListSolFunctionInstanceInfoTypeDef, _OptionalListSolFunctionInstanceInfoTypeDef
 ):
     pass
 
 
-ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef = TypedDict(
-    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef = TypedDict(
-    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef = TypedDict(
-    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef = TypedDict(
-    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef = TypedDict(
-    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredListSolFunctionPackageInfoTypeDef = TypedDict(
     "_RequiredListSolFunctionPackageInfoTypeDef",
     {
         "arn": str,
         "id": str,
         "onboardingState": OnboardingStateType,
         "operationalState": OperationalStateType,
@@ -996,14 +1015,15 @@
         "updateType": Literal["MODIFY_VNF_INFORMATION"],
     },
 )
 _OptionalUpdateSolNetworkInstanceInputRequestTypeDef = TypedDict(
     "_OptionalUpdateSolNetworkInstanceInputRequestTypeDef",
     {
         "modifyVnfInfoData": UpdateSolNetworkModifyTypeDef,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class UpdateSolNetworkInstanceInputRequestTypeDef(
     _RequiredUpdateSolNetworkInstanceInputRequestTypeDef,
@@ -1020,15 +1040,15 @@
         "id": str,
         "lcmOperationType": LcmOperationTypeType,
         "metadata": GetSolNetworkOperationMetadataTypeDef,
         "nsInstanceId": str,
         "operationState": NsLcmOperationStateType,
         "tags": Dict[str, str],
         "tasks": List[GetSolNetworkOperationTaskDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetSolFunctionPackageMetadataTypeDef = TypedDict(
     "_RequiredGetSolFunctionPackageMetadataTypeDef",
     {
         "createdAt": datetime,
@@ -1114,51 +1134,51 @@
 )
 
 ListSolFunctionInstancesOutputTypeDef = TypedDict(
     "ListSolFunctionInstancesOutputTypeDef",
     {
         "functionInstances": List[ListSolFunctionInstanceInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolFunctionPackagesOutputTypeDef = TypedDict(
     "ListSolFunctionPackagesOutputTypeDef",
     {
         "functionPackages": List[ListSolFunctionPackageInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolNetworkInstancesOutputTypeDef = TypedDict(
     "ListSolNetworkInstancesOutputTypeDef",
     {
         "networkInstances": List[ListSolNetworkInstanceInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolNetworkOperationsOutputTypeDef = TypedDict(
     "ListSolNetworkOperationsOutputTypeDef",
     {
         "networkOperations": List[ListSolNetworkOperationsInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolNetworkPackagesOutputTypeDef = TypedDict(
     "ListSolNetworkPackagesOutputTypeDef",
     {
         "networkPackages": List[ListSolNetworkPackageInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolFunctionPackageOutputTypeDef = TypedDict(
     "GetSolFunctionPackageOutputTypeDef",
     {
         "arn": str,
@@ -1168,41 +1188,41 @@
         "operationalState": OperationalStateType,
         "tags": Dict[str, str],
         "usageState": UsageStateType,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutSolFunctionPackageContentOutputTypeDef = TypedDict(
     "PutSolFunctionPackageContentOutputTypeDef",
     {
         "id": str,
         "metadata": PutSolFunctionPackageContentMetadataTypeDef,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateSolFunctionPackageContentOutputTypeDef = TypedDict(
     "ValidateSolFunctionPackageContentOutputTypeDef",
     {
         "id": str,
         "metadata": ValidateSolFunctionPackageContentMetadataTypeDef,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolNetworkPackageOutputTypeDef = TypedDict(
     "GetSolNetworkPackageOutputTypeDef",
     {
         "arn": str,
@@ -1212,43 +1232,43 @@
         "nsdName": str,
         "nsdOnboardingState": NsdOnboardingStateType,
         "nsdOperationalState": NsdOperationalStateType,
         "nsdUsageState": NsdUsageStateType,
         "nsdVersion": str,
         "tags": Dict[str, str],
         "vnfPkgIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutSolNetworkPackageContentOutputTypeDef = TypedDict(
     "PutSolNetworkPackageContentOutputTypeDef",
     {
         "arn": str,
         "id": str,
         "metadata": PutSolNetworkPackageContentMetadataTypeDef,
         "nsdId": str,
         "nsdName": str,
         "nsdVersion": str,
         "vnfPkgIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateSolNetworkPackageContentOutputTypeDef = TypedDict(
     "ValidateSolNetworkPackageContentOutputTypeDef",
     {
         "arn": str,
         "id": str,
         "metadata": ValidateSolNetworkPackageContentMetadataTypeDef,
         "nsdId": str,
         "nsdName": str,
         "nsdVersion": str,
         "vnfPkgIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolFunctionInstanceOutputTypeDef = TypedDict(
     "GetSolFunctionInstanceOutputTypeDef",
     {
         "arn": str,
@@ -1259,10 +1279,10 @@
         "nsInstanceId": str,
         "tags": Dict[str, str],
         "vnfPkgId": str,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb/type_defs.pyi` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -40,86 +40,86 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelSolNetworkOperationInputRequestTypeDef",
     "CreateSolFunctionPackageInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateSolFunctionPackageOutputTypeDef",
     "CreateSolNetworkInstanceInputRequestTypeDef",
+    "CreateSolNetworkInstanceOutputTypeDef",
     "CreateSolNetworkPackageInputRequestTypeDef",
+    "CreateSolNetworkPackageOutputTypeDef",
     "DeleteSolFunctionPackageInputRequestTypeDef",
     "DeleteSolNetworkInstanceInputRequestTypeDef",
     "DeleteSolNetworkPackageInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ErrorInfoTypeDef",
     "ToscaOverrideTypeDef",
     "GetSolFunctionInstanceInputRequestTypeDef",
     "GetSolFunctionInstanceMetadataTypeDef",
     "GetSolFunctionPackageContentInputRequestTypeDef",
+    "GetSolFunctionPackageContentOutputTypeDef",
     "GetSolFunctionPackageDescriptorInputRequestTypeDef",
+    "GetSolFunctionPackageDescriptorOutputTypeDef",
     "GetSolFunctionPackageInputRequestTypeDef",
     "GetSolInstantiatedVnfInfoTypeDef",
     "GetSolNetworkInstanceInputRequestTypeDef",
     "GetSolNetworkInstanceMetadataTypeDef",
     "LcmOperationInfoTypeDef",
     "GetSolNetworkOperationInputRequestTypeDef",
     "GetSolNetworkOperationMetadataTypeDef",
     "ProblemDetailsTypeDef",
     "GetSolNetworkPackageContentInputRequestTypeDef",
+    "GetSolNetworkPackageContentOutputTypeDef",
     "GetSolNetworkPackageDescriptorInputRequestTypeDef",
+    "GetSolNetworkPackageDescriptorOutputTypeDef",
     "GetSolNetworkPackageInputRequestTypeDef",
     "GetSolVnfcResourceInfoMetadataTypeDef",
     "InstantiateSolNetworkInstanceInputRequestTypeDef",
+    "InstantiateSolNetworkInstanceOutputTypeDef",
     "ListSolFunctionInstanceMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
     "ListSolFunctionInstancesInputRequestTypeDef",
     "ListSolFunctionPackageMetadataTypeDef",
+    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
     "ListSolFunctionPackagesInputRequestTypeDef",
     "ListSolNetworkInstanceMetadataTypeDef",
+    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
     "ListSolNetworkInstancesInputRequestTypeDef",
     "ListSolNetworkOperationsMetadataTypeDef",
+    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
     "ListSolNetworkOperationsInputRequestTypeDef",
     "ListSolNetworkPackageMetadataTypeDef",
+    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
     "ListSolNetworkPackagesInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutSolFunctionPackageContentInputRequestTypeDef",
     "PutSolNetworkPackageContentInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "TerminateSolNetworkInstanceInputRequestTypeDef",
+    "TerminateSolNetworkInstanceOutputTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateSolFunctionPackageInputRequestTypeDef",
+    "UpdateSolFunctionPackageOutputTypeDef",
     "UpdateSolNetworkModifyTypeDef",
+    "UpdateSolNetworkInstanceOutputTypeDef",
     "UpdateSolNetworkPackageInputRequestTypeDef",
+    "UpdateSolNetworkPackageOutputTypeDef",
     "ValidateSolFunctionPackageContentInputRequestTypeDef",
     "ValidateSolNetworkPackageContentInputRequestTypeDef",
-    "CreateSolFunctionPackageOutputTypeDef",
-    "CreateSolNetworkInstanceOutputTypeDef",
-    "CreateSolNetworkPackageOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetSolFunctionPackageContentOutputTypeDef",
-    "GetSolFunctionPackageDescriptorOutputTypeDef",
-    "GetSolNetworkPackageContentOutputTypeDef",
-    "GetSolNetworkPackageDescriptorOutputTypeDef",
-    "InstantiateSolNetworkInstanceOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "TerminateSolNetworkInstanceOutputTypeDef",
-    "UpdateSolFunctionPackageOutputTypeDef",
-    "UpdateSolNetworkInstanceOutputTypeDef",
-    "UpdateSolNetworkPackageOutputTypeDef",
     "GetSolNetworkOperationTaskDetailsTypeDef",
     "FunctionArtifactMetaTypeDef",
     "NetworkArtifactMetaTypeDef",
     "GetSolNetworkInstanceOutputTypeDef",
     "GetSolVnfcResourceInfoTypeDef",
     "ListSolFunctionInstanceInfoTypeDef",
-    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
-    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
-    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
-    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
-    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
     "ListSolFunctionPackageInfoTypeDef",
     "ListSolNetworkInstanceInfoTypeDef",
     "ListSolNetworkOperationsInfoTypeDef",
     "ListSolNetworkPackageInfoTypeDef",
     "UpdateSolNetworkInstanceInputRequestTypeDef",
     "GetSolNetworkOperationOutputTypeDef",
     "GetSolFunctionPackageMetadataTypeDef",
@@ -154,22 +154,24 @@
     "CreateSolFunctionPackageInputRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateSolFunctionPackageOutputTypeDef = TypedDict(
+    "CreateSolFunctionPackageOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "id": str,
+        "onboardingState": OnboardingStateType,
+        "operationalState": OperationalStateType,
+        "tags": Dict[str, str],
+        "usageState": UsageStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSolNetworkInstanceInputRequestTypeDef = TypedDict(
     "_RequiredCreateSolNetworkInstanceInputRequestTypeDef",
     {
         "nsName": str,
@@ -187,22 +189,47 @@
 
 class CreateSolNetworkInstanceInputRequestTypeDef(
     _RequiredCreateSolNetworkInstanceInputRequestTypeDef,
     _OptionalCreateSolNetworkInstanceInputRequestTypeDef,
 ):
     pass
 
+CreateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "CreateSolNetworkInstanceOutputTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "nsInstanceName": str,
+        "nsdInfoId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateSolNetworkPackageInputRequestTypeDef = TypedDict(
     "CreateSolNetworkPackageInputRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+CreateSolNetworkPackageOutputTypeDef = TypedDict(
+    "CreateSolNetworkPackageOutputTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "nsdOnboardingState": NsdOnboardingStateType,
+        "nsdOperationalState": NsdOperationalStateType,
+        "nsdUsageState": NsdUsageStateType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSolFunctionPackageInputRequestTypeDef = TypedDict(
     "DeleteSolFunctionPackageInputRequestTypeDef",
     {
         "vnfPkgId": str,
     },
 )
 
@@ -216,14 +243,21 @@
 DeleteSolNetworkPackageInputRequestTypeDef = TypedDict(
     "DeleteSolNetworkPackageInputRequestTypeDef",
     {
         "nsdInfoId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ErrorInfoTypeDef = TypedDict(
     "ErrorInfoTypeDef",
     {
         "cause": str,
         "details": str,
     },
     total=False,
@@ -257,22 +291,40 @@
     "GetSolFunctionPackageContentInputRequestTypeDef",
     {
         "accept": Literal["application/zip"],
         "vnfPkgId": str,
     },
 )
 
+GetSolFunctionPackageContentOutputTypeDef = TypedDict(
+    "GetSolFunctionPackageContentOutputTypeDef",
+    {
+        "contentType": Literal["application/zip"],
+        "packageContent": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolFunctionPackageDescriptorInputRequestTypeDef = TypedDict(
     "GetSolFunctionPackageDescriptorInputRequestTypeDef",
     {
         "accept": Literal["text/plain"],
         "vnfPkgId": str,
     },
 )
 
+GetSolFunctionPackageDescriptorOutputTypeDef = TypedDict(
+    "GetSolFunctionPackageDescriptorOutputTypeDef",
+    {
+        "contentType": Literal["text/plain"],
+        "vnfd": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolFunctionPackageInputRequestTypeDef = TypedDict(
     "GetSolFunctionPackageInputRequestTypeDef",
     {
         "vnfPkgId": str,
     },
 )
 
@@ -342,21 +394,39 @@
     "GetSolNetworkPackageContentInputRequestTypeDef",
     {
         "accept": Literal["application/zip"],
         "nsdInfoId": str,
     },
 )
 
+GetSolNetworkPackageContentOutputTypeDef = TypedDict(
+    "GetSolNetworkPackageContentOutputTypeDef",
+    {
+        "contentType": Literal["application/zip"],
+        "nsdContent": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolNetworkPackageDescriptorInputRequestTypeDef = TypedDict(
     "GetSolNetworkPackageDescriptorInputRequestTypeDef",
     {
         "nsdInfoId": str,
     },
 )
 
+GetSolNetworkPackageDescriptorOutputTypeDef = TypedDict(
+    "GetSolNetworkPackageDescriptorOutputTypeDef",
+    {
+        "contentType": Literal["text/plain"],
+        "nsd": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSolNetworkPackageInputRequestTypeDef = TypedDict(
     "GetSolNetworkPackageInputRequestTypeDef",
     {
         "nsdInfoId": str,
     },
 )
 
@@ -377,38 +447,46 @@
     },
 )
 _OptionalInstantiateSolNetworkInstanceInputRequestTypeDef = TypedDict(
     "_OptionalInstantiateSolNetworkInstanceInputRequestTypeDef",
     {
         "additionalParamsForNs": Mapping[str, Any],
         "dryRun": bool,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class InstantiateSolNetworkInstanceInputRequestTypeDef(
     _RequiredInstantiateSolNetworkInstanceInputRequestTypeDef,
     _OptionalInstantiateSolNetworkInstanceInputRequestTypeDef,
 ):
     pass
 
+InstantiateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "InstantiateSolNetworkInstanceOutputTypeDef",
+    {
+        "nsLcmOpOccId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListSolFunctionInstanceMetadataTypeDef = TypedDict(
     "ListSolFunctionInstanceMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef = TypedDict(
+    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSolFunctionInstancesInputRequestTypeDef = TypedDict(
     "ListSolFunctionInstancesInputRequestTypeDef",
     {
@@ -422,14 +500,22 @@
     "ListSolFunctionPackageMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef = TypedDict(
+    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolFunctionPackagesInputRequestTypeDef = TypedDict(
     "ListSolFunctionPackagesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -439,14 +525,22 @@
     "ListSolNetworkInstanceMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef = TypedDict(
+    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolNetworkInstancesInputRequestTypeDef = TypedDict(
     "ListSolNetworkInstancesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -456,14 +550,22 @@
     "ListSolNetworkOperationsMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef = TypedDict(
+    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolNetworkOperationsInputRequestTypeDef = TypedDict(
     "ListSolNetworkOperationsInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -473,14 +575,22 @@
     "ListSolNetworkPackageMetadataTypeDef",
     {
         "createdAt": datetime,
         "lastModified": datetime,
     },
 )
 
+ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef = TypedDict(
+    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolNetworkPackagesInputRequestTypeDef = TypedDict(
     "ListSolNetworkPackagesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -489,14 +599,32 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
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
 _RequiredPutSolFunctionPackageContentInputRequestTypeDef = TypedDict(
     "_RequiredPutSolFunctionPackageContentInputRequestTypeDef",
     {
         "file": Union[str, bytes, IO[Any], StreamingBody],
         "vnfPkgId": str,
     },
 )
@@ -531,28 +659,61 @@
 
 class PutSolNetworkPackageContentInputRequestTypeDef(
     _RequiredPutSolNetworkPackageContentInputRequestTypeDef,
     _OptionalPutSolNetworkPackageContentInputRequestTypeDef,
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
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
 
-TerminateSolNetworkInstanceInputRequestTypeDef = TypedDict(
-    "TerminateSolNetworkInstanceInputRequestTypeDef",
+_RequiredTerminateSolNetworkInstanceInputRequestTypeDef = TypedDict(
+    "_RequiredTerminateSolNetworkInstanceInputRequestTypeDef",
     {
         "nsInstanceId": str,
     },
 )
+_OptionalTerminateSolNetworkInstanceInputRequestTypeDef = TypedDict(
+    "_OptionalTerminateSolNetworkInstanceInputRequestTypeDef",
+    {
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class TerminateSolNetworkInstanceInputRequestTypeDef(
+    _RequiredTerminateSolNetworkInstanceInputRequestTypeDef,
+    _OptionalTerminateSolNetworkInstanceInputRequestTypeDef,
+):
+    pass
+
+TerminateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "TerminateSolNetworkInstanceOutputTypeDef",
+    {
+        "nsLcmOpOccId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
@@ -562,30 +723,55 @@
     "UpdateSolFunctionPackageInputRequestTypeDef",
     {
         "operationalState": OperationalStateType,
         "vnfPkgId": str,
     },
 )
 
+UpdateSolFunctionPackageOutputTypeDef = TypedDict(
+    "UpdateSolFunctionPackageOutputTypeDef",
+    {
+        "operationalState": OperationalStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSolNetworkModifyTypeDef = TypedDict(
     "UpdateSolNetworkModifyTypeDef",
     {
         "vnfConfigurableProperties": Mapping[str, Any],
         "vnfInstanceId": str,
     },
 )
 
+UpdateSolNetworkInstanceOutputTypeDef = TypedDict(
+    "UpdateSolNetworkInstanceOutputTypeDef",
+    {
+        "nsLcmOpOccId": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSolNetworkPackageInputRequestTypeDef = TypedDict(
     "UpdateSolNetworkPackageInputRequestTypeDef",
     {
         "nsdInfoId": str,
         "nsdOperationalState": NsdOperationalStateType,
     },
 )
 
+UpdateSolNetworkPackageOutputTypeDef = TypedDict(
+    "UpdateSolNetworkPackageOutputTypeDef",
+    {
+        "nsdOperationalState": NsdOperationalStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredValidateSolFunctionPackageContentInputRequestTypeDef = TypedDict(
     "_RequiredValidateSolFunctionPackageContentInputRequestTypeDef",
     {
         "file": Union[str, bytes, IO[Any], StreamingBody],
         "vnfPkgId": str,
     },
 )
@@ -620,143 +806,14 @@
 
 class ValidateSolNetworkPackageContentInputRequestTypeDef(
     _RequiredValidateSolNetworkPackageContentInputRequestTypeDef,
     _OptionalValidateSolNetworkPackageContentInputRequestTypeDef,
 ):
     pass
 
-CreateSolFunctionPackageOutputTypeDef = TypedDict(
-    "CreateSolFunctionPackageOutputTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "onboardingState": OnboardingStateType,
-        "operationalState": OperationalStateType,
-        "tags": Dict[str, str],
-        "usageState": UsageStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "CreateSolNetworkInstanceOutputTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "nsInstanceName": str,
-        "nsdInfoId": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolNetworkPackageOutputTypeDef = TypedDict(
-    "CreateSolNetworkPackageOutputTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "nsdOnboardingState": NsdOnboardingStateType,
-        "nsdOperationalState": NsdOperationalStateType,
-        "nsdUsageState": NsdUsageStateType,
-        "tags": Dict[str, str],
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
-GetSolFunctionPackageContentOutputTypeDef = TypedDict(
-    "GetSolFunctionPackageContentOutputTypeDef",
-    {
-        "contentType": Literal["application/zip"],
-        "packageContent": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSolFunctionPackageDescriptorOutputTypeDef = TypedDict(
-    "GetSolFunctionPackageDescriptorOutputTypeDef",
-    {
-        "contentType": Literal["text/plain"],
-        "vnfd": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSolNetworkPackageContentOutputTypeDef = TypedDict(
-    "GetSolNetworkPackageContentOutputTypeDef",
-    {
-        "contentType": Literal["application/zip"],
-        "nsdContent": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSolNetworkPackageDescriptorOutputTypeDef = TypedDict(
-    "GetSolNetworkPackageDescriptorOutputTypeDef",
-    {
-        "contentType": Literal["text/plain"],
-        "nsd": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InstantiateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "InstantiateSolNetworkInstanceOutputTypeDef",
-    {
-        "nsLcmOpOccId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "TerminateSolNetworkInstanceOutputTypeDef",
-    {
-        "nsLcmOpOccId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSolFunctionPackageOutputTypeDef = TypedDict(
-    "UpdateSolFunctionPackageOutputTypeDef",
-    {
-        "operationalState": OperationalStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSolNetworkInstanceOutputTypeDef = TypedDict(
-    "UpdateSolNetworkInstanceOutputTypeDef",
-    {
-        "nsLcmOpOccId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSolNetworkPackageOutputTypeDef = TypedDict(
-    "UpdateSolNetworkPackageOutputTypeDef",
-    {
-        "nsdOperationalState": NsdOperationalStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetSolNetworkOperationTaskDetailsTypeDef = TypedDict(
     "GetSolNetworkOperationTaskDetailsTypeDef",
     {
         "taskContext": Dict[str, str],
         "taskEndTime": datetime,
         "taskErrorDetails": ErrorInfoTypeDef,
         "taskName": str,
@@ -791,15 +848,15 @@
         "metadata": GetSolNetworkInstanceMetadataTypeDef,
         "nsInstanceDescription": str,
         "nsInstanceName": str,
         "nsState": NsStateType,
         "nsdId": str,
         "nsdInfoId": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolVnfcResourceInfoTypeDef = TypedDict(
     "GetSolVnfcResourceInfoTypeDef",
     {
         "metadata": GetSolVnfcResourceInfoMetadataTypeDef,
@@ -828,54 +885,14 @@
 )
 
 class ListSolFunctionInstanceInfoTypeDef(
     _RequiredListSolFunctionInstanceInfoTypeDef, _OptionalListSolFunctionInstanceInfoTypeDef
 ):
     pass
 
-ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef = TypedDict(
-    "ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef = TypedDict(
-    "ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef = TypedDict(
-    "ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef = TypedDict(
-    "ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef = TypedDict(
-    "ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredListSolFunctionPackageInfoTypeDef = TypedDict(
     "_RequiredListSolFunctionPackageInfoTypeDef",
     {
         "arn": str,
         "id": str,
         "onboardingState": OnboardingStateType,
         "operationalState": OperationalStateType,
@@ -973,14 +990,15 @@
         "updateType": Literal["MODIFY_VNF_INFORMATION"],
     },
 )
 _OptionalUpdateSolNetworkInstanceInputRequestTypeDef = TypedDict(
     "_OptionalUpdateSolNetworkInstanceInputRequestTypeDef",
     {
         "modifyVnfInfoData": UpdateSolNetworkModifyTypeDef,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class UpdateSolNetworkInstanceInputRequestTypeDef(
     _RequiredUpdateSolNetworkInstanceInputRequestTypeDef,
     _OptionalUpdateSolNetworkInstanceInputRequestTypeDef,
@@ -995,15 +1013,15 @@
         "id": str,
         "lcmOperationType": LcmOperationTypeType,
         "metadata": GetSolNetworkOperationMetadataTypeDef,
         "nsInstanceId": str,
         "operationState": NsLcmOperationStateType,
         "tags": Dict[str, str],
         "tasks": List[GetSolNetworkOperationTaskDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetSolFunctionPackageMetadataTypeDef = TypedDict(
     "_RequiredGetSolFunctionPackageMetadataTypeDef",
     {
         "createdAt": datetime,
@@ -1085,51 +1103,51 @@
 )
 
 ListSolFunctionInstancesOutputTypeDef = TypedDict(
     "ListSolFunctionInstancesOutputTypeDef",
     {
         "functionInstances": List[ListSolFunctionInstanceInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolFunctionPackagesOutputTypeDef = TypedDict(
     "ListSolFunctionPackagesOutputTypeDef",
     {
         "functionPackages": List[ListSolFunctionPackageInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolNetworkInstancesOutputTypeDef = TypedDict(
     "ListSolNetworkInstancesOutputTypeDef",
     {
         "networkInstances": List[ListSolNetworkInstanceInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolNetworkOperationsOutputTypeDef = TypedDict(
     "ListSolNetworkOperationsOutputTypeDef",
     {
         "networkOperations": List[ListSolNetworkOperationsInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolNetworkPackagesOutputTypeDef = TypedDict(
     "ListSolNetworkPackagesOutputTypeDef",
     {
         "networkPackages": List[ListSolNetworkPackageInfoTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolFunctionPackageOutputTypeDef = TypedDict(
     "GetSolFunctionPackageOutputTypeDef",
     {
         "arn": str,
@@ -1139,41 +1157,41 @@
         "operationalState": OperationalStateType,
         "tags": Dict[str, str],
         "usageState": UsageStateType,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutSolFunctionPackageContentOutputTypeDef = TypedDict(
     "PutSolFunctionPackageContentOutputTypeDef",
     {
         "id": str,
         "metadata": PutSolFunctionPackageContentMetadataTypeDef,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateSolFunctionPackageContentOutputTypeDef = TypedDict(
     "ValidateSolFunctionPackageContentOutputTypeDef",
     {
         "id": str,
         "metadata": ValidateSolFunctionPackageContentMetadataTypeDef,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolNetworkPackageOutputTypeDef = TypedDict(
     "GetSolNetworkPackageOutputTypeDef",
     {
         "arn": str,
@@ -1183,43 +1201,43 @@
         "nsdName": str,
         "nsdOnboardingState": NsdOnboardingStateType,
         "nsdOperationalState": NsdOperationalStateType,
         "nsdUsageState": NsdUsageStateType,
         "nsdVersion": str,
         "tags": Dict[str, str],
         "vnfPkgIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutSolNetworkPackageContentOutputTypeDef = TypedDict(
     "PutSolNetworkPackageContentOutputTypeDef",
     {
         "arn": str,
         "id": str,
         "metadata": PutSolNetworkPackageContentMetadataTypeDef,
         "nsdId": str,
         "nsdName": str,
         "nsdVersion": str,
         "vnfPkgIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateSolNetworkPackageContentOutputTypeDef = TypedDict(
     "ValidateSolNetworkPackageContentOutputTypeDef",
     {
         "arn": str,
         "id": str,
         "metadata": ValidateSolNetworkPackageContentMetadataTypeDef,
         "nsdId": str,
         "nsdName": str,
         "nsdVersion": str,
         "vnfPkgIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSolFunctionInstanceOutputTypeDef = TypedDict(
     "GetSolFunctionInstanceOutputTypeDef",
     {
         "arn": str,
@@ -1230,10 +1248,10 @@
         "nsInstanceId": str,
         "tags": Dict[str, str],
         "vnfPkgId": str,
         "vnfProductName": str,
         "vnfProvider": str,
         "vnfdId": str,
         "vnfdVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/PKG-INFO` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-tnb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TelcoNetworkBuilder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-tnb"></a>
 
 # types-aiobotocore-tnb
 
 [![PyPI - types-aiobotocore-tnb](https://img.shields.io/pypi/v/types-aiobotocore-tnb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-tnb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-tnb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-tnb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-tnb?color=blue)](https://pypistats.org/packages/types-aiobotocore-tnb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TelcoNetworkBuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder)
+[aiobotocore.TelcoNetworkBuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/tnb.html#TelcoNetworkBuilder)
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
 [types-aiobotocore-tnb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_tnb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -353,86 +353,86 @@
 `types_aiobotocore_tnb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_tnb.type_defs import (
     CancelSolNetworkOperationInputRequestTypeDef,
     CreateSolFunctionPackageInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateSolFunctionPackageOutputTypeDef,
     CreateSolNetworkInstanceInputRequestTypeDef,
+    CreateSolNetworkInstanceOutputTypeDef,
     CreateSolNetworkPackageInputRequestTypeDef,
+    CreateSolNetworkPackageOutputTypeDef,
     DeleteSolFunctionPackageInputRequestTypeDef,
     DeleteSolNetworkInstanceInputRequestTypeDef,
     DeleteSolNetworkPackageInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ErrorInfoTypeDef,
     ToscaOverrideTypeDef,
     GetSolFunctionInstanceInputRequestTypeDef,
     GetSolFunctionInstanceMetadataTypeDef,
     GetSolFunctionPackageContentInputRequestTypeDef,
+    GetSolFunctionPackageContentOutputTypeDef,
     GetSolFunctionPackageDescriptorInputRequestTypeDef,
+    GetSolFunctionPackageDescriptorOutputTypeDef,
     GetSolFunctionPackageInputRequestTypeDef,
     GetSolInstantiatedVnfInfoTypeDef,
     GetSolNetworkInstanceInputRequestTypeDef,
     GetSolNetworkInstanceMetadataTypeDef,
     LcmOperationInfoTypeDef,
     GetSolNetworkOperationInputRequestTypeDef,
     GetSolNetworkOperationMetadataTypeDef,
     ProblemDetailsTypeDef,
     GetSolNetworkPackageContentInputRequestTypeDef,
+    GetSolNetworkPackageContentOutputTypeDef,
     GetSolNetworkPackageDescriptorInputRequestTypeDef,
+    GetSolNetworkPackageDescriptorOutputTypeDef,
     GetSolNetworkPackageInputRequestTypeDef,
     GetSolVnfcResourceInfoMetadataTypeDef,
     InstantiateSolNetworkInstanceInputRequestTypeDef,
+    InstantiateSolNetworkInstanceOutputTypeDef,
     ListSolFunctionInstanceMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef,
     ListSolFunctionInstancesInputRequestTypeDef,
     ListSolFunctionPackageMetadataTypeDef,
+    ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef,
     ListSolFunctionPackagesInputRequestTypeDef,
     ListSolNetworkInstanceMetadataTypeDef,
+    ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef,
     ListSolNetworkInstancesInputRequestTypeDef,
     ListSolNetworkOperationsMetadataTypeDef,
+    ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef,
     ListSolNetworkOperationsInputRequestTypeDef,
     ListSolNetworkPackageMetadataTypeDef,
+    ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef,
     ListSolNetworkPackagesInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutSolFunctionPackageContentInputRequestTypeDef,
     PutSolNetworkPackageContentInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     TerminateSolNetworkInstanceInputRequestTypeDef,
+    TerminateSolNetworkInstanceOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateSolFunctionPackageInputRequestTypeDef,
+    UpdateSolFunctionPackageOutputTypeDef,
     UpdateSolNetworkModifyTypeDef,
+    UpdateSolNetworkInstanceOutputTypeDef,
     UpdateSolNetworkPackageInputRequestTypeDef,
+    UpdateSolNetworkPackageOutputTypeDef,
     ValidateSolFunctionPackageContentInputRequestTypeDef,
     ValidateSolNetworkPackageContentInputRequestTypeDef,
-    CreateSolFunctionPackageOutputTypeDef,
-    CreateSolNetworkInstanceOutputTypeDef,
-    CreateSolNetworkPackageOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetSolFunctionPackageContentOutputTypeDef,
-    GetSolFunctionPackageDescriptorOutputTypeDef,
-    GetSolNetworkPackageContentOutputTypeDef,
-    GetSolNetworkPackageDescriptorOutputTypeDef,
-    InstantiateSolNetworkInstanceOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    TerminateSolNetworkInstanceOutputTypeDef,
-    UpdateSolFunctionPackageOutputTypeDef,
-    UpdateSolNetworkInstanceOutputTypeDef,
-    UpdateSolNetworkPackageOutputTypeDef,
     GetSolNetworkOperationTaskDetailsTypeDef,
     FunctionArtifactMetaTypeDef,
     NetworkArtifactMetaTypeDef,
     GetSolNetworkInstanceOutputTypeDef,
     GetSolVnfcResourceInfoTypeDef,
     ListSolFunctionInstanceInfoTypeDef,
-    ListSolFunctionInstancesInputListSolFunctionInstancesPaginateTypeDef,
-    ListSolFunctionPackagesInputListSolFunctionPackagesPaginateTypeDef,
-    ListSolNetworkInstancesInputListSolNetworkInstancesPaginateTypeDef,
-    ListSolNetworkOperationsInputListSolNetworkOperationsPaginateTypeDef,
-    ListSolNetworkPackagesInputListSolNetworkPackagesPaginateTypeDef,
     ListSolFunctionPackageInfoTypeDef,
     ListSolNetworkInstanceInfoTypeDef,
     ListSolNetworkOperationsInfoTypeDef,
     ListSolNetworkPackageInfoTypeDef,
     UpdateSolNetworkInstanceInputRequestTypeDef,
     GetSolNetworkOperationOutputTypeDef,
     GetSolFunctionPackageMetadataTypeDef,
@@ -464,43 +464,43 @@
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

### Comparing `types-aiobotocore-tnb-2.5.0.post1/types_aiobotocore_tnb.egg-info/SOURCES.txt` & `types-aiobotocore-tnb-2.5.1/types_aiobotocore_tnb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

