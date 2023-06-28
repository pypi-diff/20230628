# Comparing `tmp/types-aiobotocore-healthlake-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-healthlake-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-healthlake-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:42 2023, max compression
+gzip compressed data, was "types-aiobotocore-healthlake-2.5.1.tar", last modified: Wed Jun 28 01:43:34 2023, max compression
```

## Comparing `types-aiobotocore-healthlake-2.5.0.post1.tar` & `types-aiobotocore-healthlake-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.259252 types-aiobotocore-healthlake-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13643 2023-03-11 12:26:42.251252 types-aiobotocore-healthlake-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12060 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:42.259252 types-aiobotocore-healthlake-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.247252 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/
--rw-r--r--   0 runner    (1001) docker     (123)      466 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      465 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13320 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13298 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7839 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7837 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    13393 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    13374 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:35.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.251252 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13643 2023-03-11 12:26:42.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      785 2023-03-11 12:26:42.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:42.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:42.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:42.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:42.000000 types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.154145 types-aiobotocore-healthlake-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13737 2023-06-28 01:43:34.150145 types-aiobotocore-healthlake-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12160 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:34.154145 types-aiobotocore-healthlake-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.142145 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/
+-rw-r--r--   0 runner    (1001) docker     (123)      466 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      465 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13434 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13412 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8300 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8298 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14225 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14204 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:12.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.150145 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13737 2023-06-28 01:43:33.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-28 01:43:34.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:33.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:33.000000 types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/LICENSE` & `types-aiobotocore-healthlake-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/PKG-INFO` & `types-aiobotocore-healthlake-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-healthlake
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.HealthLake 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.HealthLake 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-healthlake"></a>
 
 # types-aiobotocore-healthlake
 
 [![PyPI - types-aiobotocore-healthlake](https://img.shields.io/pypi/v/types-aiobotocore-healthlake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-healthlake)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-healthlake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-healthlake)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-healthlake?color=blue)](https://pypistats.org/packages/types-aiobotocore-healthlake)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.HealthLake 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
+[aiobotocore.HealthLake 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
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
 [types-aiobotocore-healthlake docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,60 +269,62 @@
 ### Literals
 
 `types_aiobotocore_healthlake.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_healthlake.literals import (
+    AuthorizationStrategyType,
     CmkTypeType,
     DatastoreStatusType,
     FHIRVersionType,
     JobStatusType,
     PreloadDataTypeType,
     HealthLakeServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: CmkTypeType) -> bool:
+def check_value(value: AuthorizationStrategyType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_healthlake.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_healthlake.type_defs import (
+    IdentityProviderConfigurationTypeDef,
     PreloadDataConfigTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateFHIRDatastoreResponseTypeDef,
     DatastoreFilterTypeDef,
     DeleteFHIRDatastoreRequestRequestTypeDef,
+    DeleteFHIRDatastoreResponseTypeDef,
     DescribeFHIRDatastoreRequestRequestTypeDef,
     DescribeFHIRExportJobRequestRequestTypeDef,
     DescribeFHIRImportJobRequestRequestTypeDef,
     InputDataConfigTypeDef,
     KmsEncryptionConfigTypeDef,
     ListFHIRExportJobsRequestRequestTypeDef,
     ListFHIRImportJobsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ConfigurationTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateFHIRDatastoreResponseTypeDef,
-    DeleteFHIRDatastoreResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartFHIRExportJobResponseTypeDef,
     StartFHIRImportJobResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ListFHIRDatastoresRequestRequestTypeDef,
     SseConfigurationTypeDef,
     OutputDataConfigTypeDef,
     CreateFHIRDatastoreRequestRequestTypeDef,
     DatastorePropertiesTypeDef,
     ExportJobPropertiesTypeDef,
     ImportJobPropertiesTypeDef,
@@ -333,54 +335,54 @@
     DescribeFHIRExportJobResponseTypeDef,
     ListFHIRExportJobsResponseTypeDef,
     DescribeFHIRImportJobResponseTypeDef,
     ListFHIRImportJobsResponseTypeDef,
 )
 
 
-def get_structure() -> PreloadDataConfigTypeDef:
+def get_structure() -> IdentityProviderConfigurationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/README.md` & `types-aiobotocore-healthlake-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-healthlake"></a>
 
 # types-aiobotocore-healthlake
 
 [![PyPI - types-aiobotocore-healthlake](https://img.shields.io/pypi/v/types-aiobotocore-healthlake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-healthlake)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-healthlake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-healthlake)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-healthlake?color=blue)](https://pypistats.org/packages/types-aiobotocore-healthlake)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.HealthLake 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
+[aiobotocore.HealthLake 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
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
 [types-aiobotocore-healthlake docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/).
 
 See how it helps to find and fix potential bugs:
 
@@ -236,60 +236,62 @@
 ### Literals
 
 `types_aiobotocore_healthlake.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_healthlake.literals import (
+    AuthorizationStrategyType,
     CmkTypeType,
     DatastoreStatusType,
     FHIRVersionType,
     JobStatusType,
     PreloadDataTypeType,
     HealthLakeServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: CmkTypeType) -> bool:
+def check_value(value: AuthorizationStrategyType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_healthlake.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_healthlake.type_defs import (
+    IdentityProviderConfigurationTypeDef,
     PreloadDataConfigTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateFHIRDatastoreResponseTypeDef,
     DatastoreFilterTypeDef,
     DeleteFHIRDatastoreRequestRequestTypeDef,
+    DeleteFHIRDatastoreResponseTypeDef,
     DescribeFHIRDatastoreRequestRequestTypeDef,
     DescribeFHIRExportJobRequestRequestTypeDef,
     DescribeFHIRImportJobRequestRequestTypeDef,
     InputDataConfigTypeDef,
     KmsEncryptionConfigTypeDef,
     ListFHIRExportJobsRequestRequestTypeDef,
     ListFHIRImportJobsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ConfigurationTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateFHIRDatastoreResponseTypeDef,
-    DeleteFHIRDatastoreResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartFHIRExportJobResponseTypeDef,
     StartFHIRImportJobResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ListFHIRDatastoresRequestRequestTypeDef,
     SseConfigurationTypeDef,
     OutputDataConfigTypeDef,
     CreateFHIRDatastoreRequestRequestTypeDef,
     DatastorePropertiesTypeDef,
     ExportJobPropertiesTypeDef,
     ImportJobPropertiesTypeDef,
@@ -300,54 +302,54 @@
     DescribeFHIRExportJobResponseTypeDef,
     ListFHIRExportJobsResponseTypeDef,
     DescribeFHIRImportJobResponseTypeDef,
     ListFHIRImportJobsResponseTypeDef,
 )
 
 
-def get_structure() -> PreloadDataConfigTypeDef:
+def get_structure() -> IdentityProviderConfigurationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/setup.py` & `types-aiobotocore-healthlake-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-healthlake.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-healthlake",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_healthlake"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.HealthLake 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.HealthLake 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/"
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

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/__main__.py` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.HealthLake 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.HealthLake 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake\nOther"
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

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/client.py` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -25,14 +25,15 @@
 from .type_defs import (
     CreateFHIRDatastoreResponseTypeDef,
     DatastoreFilterTypeDef,
     DeleteFHIRDatastoreResponseTypeDef,
     DescribeFHIRDatastoreResponseTypeDef,
     DescribeFHIRExportJobResponseTypeDef,
     DescribeFHIRImportJobResponseTypeDef,
+    IdentityProviderConfigurationTypeDef,
     InputDataConfigTypeDef,
     ListFHIRDatastoresResponseTypeDef,
     ListFHIRExportJobsResponseTypeDef,
     ListFHIRImportJobsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     OutputDataConfigTypeDef,
     PreloadDataConfigTypeDef,
@@ -106,35 +107,36 @@
         self,
         *,
         DatastoreTypeVersion: Literal["R4"],
         DatastoreName: str = ...,
         SseConfiguration: SseConfigurationTypeDef = ...,
         PreloadDataConfig: PreloadDataConfigTypeDef = ...,
         ClientToken: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        IdentityProviderConfiguration: IdentityProviderConfigurationTypeDef = ...
     ) -> CreateFHIRDatastoreResponseTypeDef:
         """
         Creates a Data Store that can ingest and export FHIR formatted data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.create_fhir_datastore)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#create_fhir_datastore)
         """
 
     async def delete_fhir_datastore(
-        self, *, DatastoreId: str = ...
+        self, *, DatastoreId: str
     ) -> DeleteFHIRDatastoreResponseTypeDef:
         """
         Deletes a Data Store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.delete_fhir_datastore)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#delete_fhir_datastore)
         """
 
     async def describe_fhir_datastore(
-        self, *, DatastoreId: str = ...
+        self, *, DatastoreId: str
     ) -> DescribeFHIRDatastoreResponseTypeDef:
         """
         Gets the properties associated with the FHIR Data Store, including the Data
         Store ID, Data Store ARN, Data Store name, Data Store status, created at, Data
         Store type version, and Data Store endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.describe_fhir_datastore)
@@ -265,15 +267,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.start_fhir_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#start_fhir_import_job)
         """
 
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
-        Adds a user specifed key and value tag to a Data Store.
+        Adds a user specified key and value tag to a Data Store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#tag_resource)
         """
 
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/client.pyi` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -25,14 +25,15 @@
 from .type_defs import (
     CreateFHIRDatastoreResponseTypeDef,
     DatastoreFilterTypeDef,
     DeleteFHIRDatastoreResponseTypeDef,
     DescribeFHIRDatastoreResponseTypeDef,
     DescribeFHIRExportJobResponseTypeDef,
     DescribeFHIRImportJobResponseTypeDef,
+    IdentityProviderConfigurationTypeDef,
     InputDataConfigTypeDef,
     ListFHIRDatastoresResponseTypeDef,
     ListFHIRExportJobsResponseTypeDef,
     ListFHIRImportJobsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     OutputDataConfigTypeDef,
     PreloadDataConfigTypeDef,
@@ -99,33 +100,34 @@
         self,
         *,
         DatastoreTypeVersion: Literal["R4"],
         DatastoreName: str = ...,
         SseConfiguration: SseConfigurationTypeDef = ...,
         PreloadDataConfig: PreloadDataConfigTypeDef = ...,
         ClientToken: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        IdentityProviderConfiguration: IdentityProviderConfigurationTypeDef = ...
     ) -> CreateFHIRDatastoreResponseTypeDef:
         """
         Creates a Data Store that can ingest and export FHIR formatted data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.create_fhir_datastore)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#create_fhir_datastore)
         """
     async def delete_fhir_datastore(
-        self, *, DatastoreId: str = ...
+        self, *, DatastoreId: str
     ) -> DeleteFHIRDatastoreResponseTypeDef:
         """
         Deletes a Data Store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.delete_fhir_datastore)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#delete_fhir_datastore)
         """
     async def describe_fhir_datastore(
-        self, *, DatastoreId: str = ...
+        self, *, DatastoreId: str
     ) -> DescribeFHIRDatastoreResponseTypeDef:
         """
         Gets the properties associated with the FHIR Data Store, including the Data
         Store ID, Data Store ARN, Data Store name, Data Store status, created at, Data
         Store type version, and Data Store endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.describe_fhir_datastore)
@@ -246,15 +248,15 @@
         Begins a FHIR Import job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.start_fhir_import_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#start_fhir_import_job)
         """
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
-        Adds a user specifed key and value tag to a Data Store.
+        Adds a user specified key and value tag to a Data Store.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/client/#tag_resource)
         """
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from a Data Store.
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/literals.py` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/literals.py`

 * *Files 19% similar despite different names*

```diff
@@ -2,44 +2,56 @@
 Type annotations for healthlake service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_healthlake.literals import CmkTypeType
+    from types_aiobotocore_healthlake.literals import AuthorizationStrategyType
 
-    data: CmkTypeType = "AWS_OWNED_KMS_KEY"
+    data: AuthorizationStrategyType = "AWS_AUTH"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "AuthorizationStrategyType",
     "CmkTypeType",
     "DatastoreStatusType",
     "FHIRVersionType",
     "JobStatusType",
     "PreloadDataTypeType",
     "HealthLakeServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
+AuthorizationStrategyType = Literal["AWS_AUTH", "SMART_ON_FHIR_V1"]
 CmkTypeType = Literal["AWS_OWNED_KMS_KEY", "CUSTOMER_MANAGED_KMS_KEY"]
 DatastoreStatusType = Literal["ACTIVE", "CREATING", "DELETED", "DELETING"]
 FHIRVersionType = Literal["R4"]
-JobStatusType = Literal["COMPLETED", "COMPLETED_WITH_ERRORS", "FAILED", "IN_PROGRESS", "SUBMITTED"]
+JobStatusType = Literal[
+    "CANCEL_COMPLETED",
+    "CANCEL_FAILED",
+    "CANCEL_IN_PROGRESS",
+    "CANCEL_SUBMITTED",
+    "COMPLETED",
+    "COMPLETED_WITH_ERRORS",
+    "FAILED",
+    "IN_PROGRESS",
+    "SUBMITTED",
+]
 PreloadDataTypeType = Literal["SYNTHEA"]
 HealthLakeServiceName = Literal["healthlake"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -96,14 +108,15 @@
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
@@ -182,14 +195,15 @@
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
@@ -200,14 +214,15 @@
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
@@ -243,14 +258,15 @@
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
@@ -269,16 +285,19 @@
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
@@ -362,15 +381,17 @@
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
@@ -388,8 +409,8 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-RegionName = Literal["us-east-1", "us-east-2", "us-west-2"]
+RegionName = Literal["ap-south-1", "us-east-1", "us-east-2", "us-west-2"]
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/literals.pyi` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/literals.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -2,42 +2,54 @@
 Type annotations for healthlake service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_healthlake.literals import CmkTypeType
+    from types_aiobotocore_healthlake.literals import AuthorizationStrategyType
 
-    data: CmkTypeType = "AWS_OWNED_KMS_KEY"
+    data: AuthorizationStrategyType = "AWS_AUTH"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "AuthorizationStrategyType",
     "CmkTypeType",
     "DatastoreStatusType",
     "FHIRVersionType",
     "JobStatusType",
     "PreloadDataTypeType",
     "HealthLakeServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+AuthorizationStrategyType = Literal["AWS_AUTH", "SMART_ON_FHIR_V1"]
 CmkTypeType = Literal["AWS_OWNED_KMS_KEY", "CUSTOMER_MANAGED_KMS_KEY"]
 DatastoreStatusType = Literal["ACTIVE", "CREATING", "DELETED", "DELETING"]
 FHIRVersionType = Literal["R4"]
-JobStatusType = Literal["COMPLETED", "COMPLETED_WITH_ERRORS", "FAILED", "IN_PROGRESS", "SUBMITTED"]
+JobStatusType = Literal[
+    "CANCEL_COMPLETED",
+    "CANCEL_FAILED",
+    "CANCEL_IN_PROGRESS",
+    "CANCEL_SUBMITTED",
+    "COMPLETED",
+    "COMPLETED_WITH_ERRORS",
+    "FAILED",
+    "IN_PROGRESS",
+    "SUBMITTED",
+]
 PreloadDataTypeType = Literal["SYNTHEA"]
 HealthLakeServiceName = Literal["healthlake"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -94,14 +106,15 @@
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
@@ -180,14 +193,15 @@
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
@@ -198,14 +212,15 @@
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
@@ -241,14 +256,15 @@
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
@@ -267,16 +283,19 @@
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
@@ -360,15 +379,17 @@
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
@@ -386,8 +407,8 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-RegionName = Literal["us-east-1", "us-east-2", "us-west-2"]
+RegionName = Literal["ap-south-1", "us-east-1", "us-east-2", "us-west-2"]
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/type_defs.py` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/type_defs.py`

 * *Files 20% similar despite different names*

```diff
@@ -2,57 +2,58 @@
 Type annotations for healthlake service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_healthlake.type_defs import PreloadDataConfigTypeDef
+    from types_aiobotocore_healthlake.type_defs import IdentityProviderConfigurationTypeDef
 
-    data: PreloadDataConfigTypeDef = {...}
+    data: IdentityProviderConfigurationTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
-from .literals import CmkTypeType, DatastoreStatusType, JobStatusType
+from .literals import AuthorizationStrategyType, CmkTypeType, DatastoreStatusType, JobStatusType
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
+    "IdentityProviderConfigurationTypeDef",
     "PreloadDataConfigTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateFHIRDatastoreResponseTypeDef",
     "DatastoreFilterTypeDef",
     "DeleteFHIRDatastoreRequestRequestTypeDef",
+    "DeleteFHIRDatastoreResponseTypeDef",
     "DescribeFHIRDatastoreRequestRequestTypeDef",
     "DescribeFHIRExportJobRequestRequestTypeDef",
     "DescribeFHIRImportJobRequestRequestTypeDef",
     "InputDataConfigTypeDef",
     "KmsEncryptionConfigTypeDef",
     "ListFHIRExportJobsRequestRequestTypeDef",
     "ListFHIRImportJobsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "S3ConfigurationTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateFHIRDatastoreResponseTypeDef",
-    "DeleteFHIRDatastoreResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartFHIRExportJobResponseTypeDef",
     "StartFHIRImportJobResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ListFHIRDatastoresRequestRequestTypeDef",
     "SseConfigurationTypeDef",
     "OutputDataConfigTypeDef",
     "CreateFHIRDatastoreRequestRequestTypeDef",
     "DatastorePropertiesTypeDef",
     "ExportJobPropertiesTypeDef",
     "ImportJobPropertiesTypeDef",
@@ -62,14 +63,37 @@
     "ListFHIRDatastoresResponseTypeDef",
     "DescribeFHIRExportJobResponseTypeDef",
     "ListFHIRExportJobsResponseTypeDef",
     "DescribeFHIRImportJobResponseTypeDef",
     "ListFHIRImportJobsResponseTypeDef",
 )
 
+_RequiredIdentityProviderConfigurationTypeDef = TypedDict(
+    "_RequiredIdentityProviderConfigurationTypeDef",
+    {
+        "AuthorizationStrategy": AuthorizationStrategyType,
+    },
+)
+_OptionalIdentityProviderConfigurationTypeDef = TypedDict(
+    "_OptionalIdentityProviderConfigurationTypeDef",
+    {
+        "FineGrainedAuthorizationEnabled": bool,
+        "Metadata": str,
+        "IdpLambdaArn": str,
+    },
+    total=False,
+)
+
+
+class IdentityProviderConfigurationTypeDef(
+    _RequiredIdentityProviderConfigurationTypeDef, _OptionalIdentityProviderConfigurationTypeDef
+):
+    pass
+
+
 PreloadDataConfigTypeDef = TypedDict(
     "PreloadDataConfigTypeDef",
     {
         "PreloadDataType": Literal["SYNTHEA"],
     },
 )
 
@@ -77,22 +101,22 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateFHIRDatastoreResponseTypeDef = TypedDict(
+    "CreateFHIRDatastoreResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DatastoreId": str,
+        "DatastoreArn": str,
+        "DatastoreStatus": DatastoreStatusType,
+        "DatastoreEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatastoreFilterTypeDef = TypedDict(
     "DatastoreFilterTypeDef",
     {
         "DatastoreName": str,
@@ -104,23 +128,32 @@
 )
 
 DeleteFHIRDatastoreRequestRequestTypeDef = TypedDict(
     "DeleteFHIRDatastoreRequestRequestTypeDef",
     {
         "DatastoreId": str,
     },
-    total=False,
+)
+
+DeleteFHIRDatastoreResponseTypeDef = TypedDict(
+    "DeleteFHIRDatastoreResponseTypeDef",
+    {
+        "DatastoreId": str,
+        "DatastoreArn": str,
+        "DatastoreStatus": DatastoreStatusType,
+        "DatastoreEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
 )
 
 DescribeFHIRDatastoreRequestRequestTypeDef = TypedDict(
     "DescribeFHIRDatastoreRequestRequestTypeDef",
     {
         "DatastoreId": str,
     },
-    total=False,
 )
 
 DescribeFHIRExportJobRequestRequestTypeDef = TypedDict(
     "DescribeFHIRExportJobRequestRequestTypeDef",
     {
         "DatastoreId": str,
         "JobId": str,
@@ -229,77 +262,66 @@
     "S3ConfigurationTypeDef",
     {
         "S3Uri": str,
         "KmsKeyId": str,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResourceARN": str,
-        "TagKeys": Sequence[str],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+StartFHIRExportJobResponseTypeDef = TypedDict(
+    "StartFHIRExportJobResponseTypeDef",
     {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "DatastoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateFHIRDatastoreResponseTypeDef = TypedDict(
-    "CreateFHIRDatastoreResponseTypeDef",
+StartFHIRImportJobResponseTypeDef = TypedDict(
+    "StartFHIRImportJobResponseTypeDef",
     {
+        "JobId": str,
+        "JobStatus": JobStatusType,
         "DatastoreId": str,
-        "DatastoreArn": str,
-        "DatastoreStatus": DatastoreStatusType,
-        "DatastoreEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteFHIRDatastoreResponseTypeDef = TypedDict(
-    "DeleteFHIRDatastoreResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "DatastoreId": str,
-        "DatastoreArn": str,
-        "DatastoreStatus": DatastoreStatusType,
-        "DatastoreEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFHIRExportJobResponseTypeDef = TypedDict(
-    "StartFHIRExportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "DatastoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartFHIRImportJobResponseTypeDef = TypedDict(
-    "StartFHIRImportJobResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "DatastoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 ListFHIRDatastoresRequestRequestTypeDef = TypedDict(
     "ListFHIRDatastoresRequestRequestTypeDef",
     {
         "Filter": DatastoreFilterTypeDef,
@@ -334,14 +356,15 @@
     "_OptionalCreateFHIRDatastoreRequestRequestTypeDef",
     {
         "DatastoreName": str,
         "SseConfiguration": SseConfigurationTypeDef,
         "PreloadDataConfig": PreloadDataConfigTypeDef,
         "ClientToken": str,
         "Tags": Sequence[TagTypeDef],
+        "IdentityProviderConfiguration": IdentityProviderConfigurationTypeDef,
     },
     total=False,
 )
 
 
 class CreateFHIRDatastoreRequestRequestTypeDef(
     _RequiredCreateFHIRDatastoreRequestRequestTypeDef,
@@ -363,14 +386,15 @@
 _OptionalDatastorePropertiesTypeDef = TypedDict(
     "_OptionalDatastorePropertiesTypeDef",
     {
         "DatastoreName": str,
         "CreatedAt": datetime,
         "SseConfiguration": SseConfigurationTypeDef,
         "PreloadDataConfig": PreloadDataConfigTypeDef,
+        "IdentityProviderConfiguration": IdentityProviderConfigurationTypeDef,
     },
     total=False,
 )
 
 
 class DatastorePropertiesTypeDef(
     _RequiredDatastorePropertiesTypeDef, _OptionalDatastorePropertiesTypeDef
@@ -486,53 +510,53 @@
     pass
 
 
 DescribeFHIRDatastoreResponseTypeDef = TypedDict(
     "DescribeFHIRDatastoreResponseTypeDef",
     {
         "DatastoreProperties": DatastorePropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFHIRDatastoresResponseTypeDef = TypedDict(
     "ListFHIRDatastoresResponseTypeDef",
     {
         "DatastorePropertiesList": List[DatastorePropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFHIRExportJobResponseTypeDef = TypedDict(
     "DescribeFHIRExportJobResponseTypeDef",
     {
         "ExportJobProperties": ExportJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFHIRExportJobsResponseTypeDef = TypedDict(
     "ListFHIRExportJobsResponseTypeDef",
     {
         "ExportJobPropertiesList": List[ExportJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFHIRImportJobResponseTypeDef = TypedDict(
     "DescribeFHIRImportJobResponseTypeDef",
     {
         "ImportJobProperties": ImportJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFHIRImportJobsResponseTypeDef = TypedDict(
     "ListFHIRImportJobsResponseTypeDef",
     {
         "ImportJobPropertiesList": List[ImportJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake/type_defs.pyi` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -2,56 +2,57 @@
 Type annotations for healthlake service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_healthlake.type_defs import PreloadDataConfigTypeDef
+    from types_aiobotocore_healthlake.type_defs import IdentityProviderConfigurationTypeDef
 
-    data: PreloadDataConfigTypeDef = {...}
+    data: IdentityProviderConfigurationTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
-from .literals import CmkTypeType, DatastoreStatusType, JobStatusType
+from .literals import AuthorizationStrategyType, CmkTypeType, DatastoreStatusType, JobStatusType
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
+    "IdentityProviderConfigurationTypeDef",
     "PreloadDataConfigTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateFHIRDatastoreResponseTypeDef",
     "DatastoreFilterTypeDef",
     "DeleteFHIRDatastoreRequestRequestTypeDef",
+    "DeleteFHIRDatastoreResponseTypeDef",
     "DescribeFHIRDatastoreRequestRequestTypeDef",
     "DescribeFHIRExportJobRequestRequestTypeDef",
     "DescribeFHIRImportJobRequestRequestTypeDef",
     "InputDataConfigTypeDef",
     "KmsEncryptionConfigTypeDef",
     "ListFHIRExportJobsRequestRequestTypeDef",
     "ListFHIRImportJobsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "S3ConfigurationTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateFHIRDatastoreResponseTypeDef",
-    "DeleteFHIRDatastoreResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartFHIRExportJobResponseTypeDef",
     "StartFHIRImportJobResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ListFHIRDatastoresRequestRequestTypeDef",
     "SseConfigurationTypeDef",
     "OutputDataConfigTypeDef",
     "CreateFHIRDatastoreRequestRequestTypeDef",
     "DatastorePropertiesTypeDef",
     "ExportJobPropertiesTypeDef",
     "ImportJobPropertiesTypeDef",
@@ -61,14 +62,35 @@
     "ListFHIRDatastoresResponseTypeDef",
     "DescribeFHIRExportJobResponseTypeDef",
     "ListFHIRExportJobsResponseTypeDef",
     "DescribeFHIRImportJobResponseTypeDef",
     "ListFHIRImportJobsResponseTypeDef",
 )
 
+_RequiredIdentityProviderConfigurationTypeDef = TypedDict(
+    "_RequiredIdentityProviderConfigurationTypeDef",
+    {
+        "AuthorizationStrategy": AuthorizationStrategyType,
+    },
+)
+_OptionalIdentityProviderConfigurationTypeDef = TypedDict(
+    "_OptionalIdentityProviderConfigurationTypeDef",
+    {
+        "FineGrainedAuthorizationEnabled": bool,
+        "Metadata": str,
+        "IdpLambdaArn": str,
+    },
+    total=False,
+)
+
+class IdentityProviderConfigurationTypeDef(
+    _RequiredIdentityProviderConfigurationTypeDef, _OptionalIdentityProviderConfigurationTypeDef
+):
+    pass
+
 PreloadDataConfigTypeDef = TypedDict(
     "PreloadDataConfigTypeDef",
     {
         "PreloadDataType": Literal["SYNTHEA"],
     },
 )
 
@@ -76,22 +98,22 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateFHIRDatastoreResponseTypeDef = TypedDict(
+    "CreateFHIRDatastoreResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DatastoreId": str,
+        "DatastoreArn": str,
+        "DatastoreStatus": DatastoreStatusType,
+        "DatastoreEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatastoreFilterTypeDef = TypedDict(
     "DatastoreFilterTypeDef",
     {
         "DatastoreName": str,
@@ -103,23 +125,32 @@
 )
 
 DeleteFHIRDatastoreRequestRequestTypeDef = TypedDict(
     "DeleteFHIRDatastoreRequestRequestTypeDef",
     {
         "DatastoreId": str,
     },
-    total=False,
+)
+
+DeleteFHIRDatastoreResponseTypeDef = TypedDict(
+    "DeleteFHIRDatastoreResponseTypeDef",
+    {
+        "DatastoreId": str,
+        "DatastoreArn": str,
+        "DatastoreStatus": DatastoreStatusType,
+        "DatastoreEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
 )
 
 DescribeFHIRDatastoreRequestRequestTypeDef = TypedDict(
     "DescribeFHIRDatastoreRequestRequestTypeDef",
     {
         "DatastoreId": str,
     },
-    total=False,
 )
 
 DescribeFHIRExportJobRequestRequestTypeDef = TypedDict(
     "DescribeFHIRExportJobRequestRequestTypeDef",
     {
         "DatastoreId": str,
         "JobId": str,
@@ -222,77 +253,66 @@
     "S3ConfigurationTypeDef",
     {
         "S3Uri": str,
         "KmsKeyId": str,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "ResourceARN": str,
-        "TagKeys": Sequence[str],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+StartFHIRExportJobResponseTypeDef = TypedDict(
+    "StartFHIRExportJobResponseTypeDef",
     {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "DatastoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateFHIRDatastoreResponseTypeDef = TypedDict(
-    "CreateFHIRDatastoreResponseTypeDef",
+StartFHIRImportJobResponseTypeDef = TypedDict(
+    "StartFHIRImportJobResponseTypeDef",
     {
+        "JobId": str,
+        "JobStatus": JobStatusType,
         "DatastoreId": str,
-        "DatastoreArn": str,
-        "DatastoreStatus": DatastoreStatusType,
-        "DatastoreEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteFHIRDatastoreResponseTypeDef = TypedDict(
-    "DeleteFHIRDatastoreResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "DatastoreId": str,
-        "DatastoreArn": str,
-        "DatastoreStatus": DatastoreStatusType,
-        "DatastoreEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFHIRExportJobResponseTypeDef = TypedDict(
-    "StartFHIRExportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "DatastoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartFHIRImportJobResponseTypeDef = TypedDict(
-    "StartFHIRImportJobResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "DatastoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 ListFHIRDatastoresRequestRequestTypeDef = TypedDict(
     "ListFHIRDatastoresRequestRequestTypeDef",
     {
         "Filter": DatastoreFilterTypeDef,
@@ -327,14 +347,15 @@
     "_OptionalCreateFHIRDatastoreRequestRequestTypeDef",
     {
         "DatastoreName": str,
         "SseConfiguration": SseConfigurationTypeDef,
         "PreloadDataConfig": PreloadDataConfigTypeDef,
         "ClientToken": str,
         "Tags": Sequence[TagTypeDef],
+        "IdentityProviderConfiguration": IdentityProviderConfigurationTypeDef,
     },
     total=False,
 )
 
 class CreateFHIRDatastoreRequestRequestTypeDef(
     _RequiredCreateFHIRDatastoreRequestRequestTypeDef,
     _OptionalCreateFHIRDatastoreRequestRequestTypeDef,
@@ -354,14 +375,15 @@
 _OptionalDatastorePropertiesTypeDef = TypedDict(
     "_OptionalDatastorePropertiesTypeDef",
     {
         "DatastoreName": str,
         "CreatedAt": datetime,
         "SseConfiguration": SseConfigurationTypeDef,
         "PreloadDataConfig": PreloadDataConfigTypeDef,
+        "IdentityProviderConfiguration": IdentityProviderConfigurationTypeDef,
     },
     total=False,
 )
 
 class DatastorePropertiesTypeDef(
     _RequiredDatastorePropertiesTypeDef, _OptionalDatastorePropertiesTypeDef
 ):
@@ -467,53 +489,53 @@
 ):
     pass
 
 DescribeFHIRDatastoreResponseTypeDef = TypedDict(
     "DescribeFHIRDatastoreResponseTypeDef",
     {
         "DatastoreProperties": DatastorePropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFHIRDatastoresResponseTypeDef = TypedDict(
     "ListFHIRDatastoresResponseTypeDef",
     {
         "DatastorePropertiesList": List[DatastorePropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFHIRExportJobResponseTypeDef = TypedDict(
     "DescribeFHIRExportJobResponseTypeDef",
     {
         "ExportJobProperties": ExportJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFHIRExportJobsResponseTypeDef = TypedDict(
     "ListFHIRExportJobsResponseTypeDef",
     {
         "ExportJobPropertiesList": List[ExportJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFHIRImportJobResponseTypeDef = TypedDict(
     "DescribeFHIRImportJobResponseTypeDef",
     {
         "ImportJobProperties": ImportJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFHIRImportJobsResponseTypeDef = TypedDict(
     "ListFHIRImportJobsResponseTypeDef",
     {
         "ImportJobPropertiesList": List[ImportJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/PKG-INFO` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-healthlake
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.HealthLake 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.HealthLake 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-healthlake"></a>
 
 # types-aiobotocore-healthlake
 
 [![PyPI - types-aiobotocore-healthlake](https://img.shields.io/pypi/v/types-aiobotocore-healthlake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-healthlake)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-healthlake.svg?color=blue)](https://pypi.org/project/types-aiobotocore-healthlake)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-healthlake?color=blue)](https://pypistats.org/packages/types-aiobotocore-healthlake)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.HealthLake 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
+[aiobotocore.HealthLake 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
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
 [types-aiobotocore-healthlake docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_healthlake/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,60 +269,62 @@
 ### Literals
 
 `types_aiobotocore_healthlake.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_healthlake.literals import (
+    AuthorizationStrategyType,
     CmkTypeType,
     DatastoreStatusType,
     FHIRVersionType,
     JobStatusType,
     PreloadDataTypeType,
     HealthLakeServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: CmkTypeType) -> bool:
+def check_value(value: AuthorizationStrategyType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_healthlake.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_healthlake.type_defs import (
+    IdentityProviderConfigurationTypeDef,
     PreloadDataConfigTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateFHIRDatastoreResponseTypeDef,
     DatastoreFilterTypeDef,
     DeleteFHIRDatastoreRequestRequestTypeDef,
+    DeleteFHIRDatastoreResponseTypeDef,
     DescribeFHIRDatastoreRequestRequestTypeDef,
     DescribeFHIRExportJobRequestRequestTypeDef,
     DescribeFHIRImportJobRequestRequestTypeDef,
     InputDataConfigTypeDef,
     KmsEncryptionConfigTypeDef,
     ListFHIRExportJobsRequestRequestTypeDef,
     ListFHIRImportJobsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     S3ConfigurationTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateFHIRDatastoreResponseTypeDef,
-    DeleteFHIRDatastoreResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartFHIRExportJobResponseTypeDef,
     StartFHIRImportJobResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ListFHIRDatastoresRequestRequestTypeDef,
     SseConfigurationTypeDef,
     OutputDataConfigTypeDef,
     CreateFHIRDatastoreRequestRequestTypeDef,
     DatastorePropertiesTypeDef,
     ExportJobPropertiesTypeDef,
     ImportJobPropertiesTypeDef,
@@ -333,54 +335,54 @@
     DescribeFHIRExportJobResponseTypeDef,
     ListFHIRExportJobsResponseTypeDef,
     DescribeFHIRImportJobResponseTypeDef,
     ListFHIRImportJobsResponseTypeDef,
 )
 
 
-def get_structure() -> PreloadDataConfigTypeDef:
+def get_structure() -> IdentityProviderConfigurationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-healthlake-2.5.0.post1/types_aiobotocore_healthlake.egg-info/SOURCES.txt` & `types-aiobotocore-healthlake-2.5.1/types_aiobotocore_healthlake.egg-info/SOURCES.txt`

 * *Files identical despite different names*

