# Comparing `tmp/types-aiobotocore-iotdeviceadvisor-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotdeviceadvisor-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotdeviceadvisor-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotdeviceadvisor-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1.tar` & `types-aiobotocore-iotdeviceadvisor-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.611296 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13855 2023-03-11 12:26:46.611296 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12248 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.611296 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.607296 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/
--rw-r--r--   0 runner    (1001) docker     (123)      514 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      513 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12796 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12774 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8201 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8199 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    12140 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12129 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:17.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.611296 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13855 2023-03-11 12:26:46.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      887 2023-03-11 12:26:46.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:46.000000 types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.298153 types-aiobotocore-iotdeviceadvisor-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13911 2023-06-28 01:43:38.294153 types-aiobotocore-iotdeviceadvisor-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12310 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.298153 types-aiobotocore-iotdeviceadvisor-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.294153 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/
+-rw-r--r--   0 runner    (1001) docker     (123)      514 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12963 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12941 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8606 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8604 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    12334 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12323 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:55.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.294153 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13911 2023-06-28 01:43:38.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      887 2023-06-28 01:43:38.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:38.000000 types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/LICENSE` & `types-aiobotocore-iotdeviceadvisor-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotdeviceadvisor-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotdeviceadvisor
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotdeviceadvisor"></a>
 
 # types-aiobotocore-iotdeviceadvisor
 
 [![PyPI - types-aiobotocore-iotdeviceadvisor](https://img.shields.io/pypi/v/types-aiobotocore-iotdeviceadvisor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotdeviceadvisor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotdeviceadvisor?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotdeviceadvisor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTDeviceAdvisor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
+[aiobotocore.IoTDeviceAdvisor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
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
 [types-aiobotocore-iotdeviceadvisor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,59 +269,60 @@
 ### Literals
 
 `types_aiobotocore_iotdeviceadvisor.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotdeviceadvisor.literals import (
+    AuthenticationMethodType,
     ProtocolType,
     StatusType,
     SuiteRunStatusType,
     TestCaseScenarioStatusType,
     TestCaseScenarioTypeType,
     IoTDeviceAdvisorServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: ProtocolType) -> bool:
+def check_value(value: AuthenticationMethodType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_iotdeviceadvisor.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotdeviceadvisor.type_defs import (
-    ResponseMetadataTypeDef,
+    CreateSuiteDefinitionResponseTypeDef,
     DeleteSuiteDefinitionRequestRequestTypeDef,
     DeviceUnderTestTypeDef,
     GetEndpointRequestRequestTypeDef,
+    GetEndpointResponseTypeDef,
     GetSuiteDefinitionRequestRequestTypeDef,
     GetSuiteRunReportRequestRequestTypeDef,
+    GetSuiteRunReportResponseTypeDef,
     GetSuiteRunRequestRequestTypeDef,
     ListSuiteDefinitionsRequestRequestTypeDef,
     ListSuiteRunsRequestRequestTypeDef,
     SuiteRunInformationTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
+    StartSuiteRunResponseTypeDef,
     StopSuiteRunRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TestCaseScenarioTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateSuiteDefinitionResponseTypeDef,
-    GetEndpointResponseTypeDef,
-    GetSuiteRunReportResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartSuiteRunResponseTypeDef,
     UpdateSuiteDefinitionResponseTypeDef,
     SuiteDefinitionConfigurationTypeDef,
     SuiteDefinitionInformationTypeDef,
     SuiteRunConfigurationTypeDef,
     ListSuiteRunsResponseTypeDef,
     TestCaseRunTypeDef,
     CreateSuiteDefinitionRequestRequestTypeDef,
@@ -331,54 +332,54 @@
     StartSuiteRunRequestRequestTypeDef,
     GroupResultTypeDef,
     TestResultTypeDef,
     GetSuiteRunResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> CreateSuiteDefinitionResponseTypeDef:
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/README.md` & `types-aiobotocore-iotdeviceadvisor-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotdeviceadvisor"></a>
 
 # types-aiobotocore-iotdeviceadvisor
 
 [![PyPI - types-aiobotocore-iotdeviceadvisor](https://img.shields.io/pypi/v/types-aiobotocore-iotdeviceadvisor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotdeviceadvisor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotdeviceadvisor?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotdeviceadvisor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTDeviceAdvisor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
+[aiobotocore.IoTDeviceAdvisor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
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
 [types-aiobotocore-iotdeviceadvisor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -236,59 +236,60 @@
 ### Literals
 
 `types_aiobotocore_iotdeviceadvisor.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotdeviceadvisor.literals import (
+    AuthenticationMethodType,
     ProtocolType,
     StatusType,
     SuiteRunStatusType,
     TestCaseScenarioStatusType,
     TestCaseScenarioTypeType,
     IoTDeviceAdvisorServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: ProtocolType) -> bool:
+def check_value(value: AuthenticationMethodType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_iotdeviceadvisor.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotdeviceadvisor.type_defs import (
-    ResponseMetadataTypeDef,
+    CreateSuiteDefinitionResponseTypeDef,
     DeleteSuiteDefinitionRequestRequestTypeDef,
     DeviceUnderTestTypeDef,
     GetEndpointRequestRequestTypeDef,
+    GetEndpointResponseTypeDef,
     GetSuiteDefinitionRequestRequestTypeDef,
     GetSuiteRunReportRequestRequestTypeDef,
+    GetSuiteRunReportResponseTypeDef,
     GetSuiteRunRequestRequestTypeDef,
     ListSuiteDefinitionsRequestRequestTypeDef,
     ListSuiteRunsRequestRequestTypeDef,
     SuiteRunInformationTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
+    StartSuiteRunResponseTypeDef,
     StopSuiteRunRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TestCaseScenarioTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateSuiteDefinitionResponseTypeDef,
-    GetEndpointResponseTypeDef,
-    GetSuiteRunReportResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartSuiteRunResponseTypeDef,
     UpdateSuiteDefinitionResponseTypeDef,
     SuiteDefinitionConfigurationTypeDef,
     SuiteDefinitionInformationTypeDef,
     SuiteRunConfigurationTypeDef,
     ListSuiteRunsResponseTypeDef,
     TestCaseRunTypeDef,
     CreateSuiteDefinitionRequestRequestTypeDef,
@@ -298,54 +299,54 @@
     StartSuiteRunRequestRequestTypeDef,
     GroupResultTypeDef,
     TestResultTypeDef,
     GetSuiteRunResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> CreateSuiteDefinitionResponseTypeDef:
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/setup.py` & `types-aiobotocore-iotdeviceadvisor-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotdeviceadvisor.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotdeviceadvisor",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotdeviceadvisor"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/"
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/__init__.py` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/__init__.pyi` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/__main__.py` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor\nOther"
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/client.py` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -15,14 +15,15 @@
     ```
 """
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import AuthenticationMethodType
 from .type_defs import (
     CreateSuiteDefinitionResponseTypeDef,
     GetEndpointResponseTypeDef,
     GetSuiteDefinitionResponseTypeDef,
     GetSuiteRunReportResponseTypeDef,
     GetSuiteRunResponseTypeDef,
     ListSuiteDefinitionsResponseTypeDef,
@@ -118,15 +119,20 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/client/#generate_presigned_url)
         """
 
     async def get_endpoint(
-        self, *, thingArn: str = ..., certificateArn: str = ...
+        self,
+        *,
+        thingArn: str = ...,
+        certificateArn: str = ...,
+        deviceRoleArn: str = ...,
+        authenticationMethod: AuthenticationMethodType = ...
     ) -> GetEndpointResponseTypeDef:
         """
         Gets information about an Device Advisor endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor.Client.get_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/client/#get_endpoint)
         """
```

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/client.pyi` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -15,14 +15,15 @@
     ```
 """
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
+from .literals import AuthenticationMethodType
 from .type_defs import (
     CreateSuiteDefinitionResponseTypeDef,
     GetEndpointResponseTypeDef,
     GetSuiteDefinitionResponseTypeDef,
     GetSuiteRunReportResponseTypeDef,
     GetSuiteRunResponseTypeDef,
     ListSuiteDefinitionsResponseTypeDef,
@@ -109,15 +110,20 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/client/#generate_presigned_url)
         """
     async def get_endpoint(
-        self, *, thingArn: str = ..., certificateArn: str = ...
+        self,
+        *,
+        thingArn: str = ...,
+        certificateArn: str = ...,
+        deviceRoleArn: str = ...,
+        authenticationMethod: AuthenticationMethodType = ...
     ) -> GetEndpointResponseTypeDef:
         """
         Gets information about an Device Advisor endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor.Client.get_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/client/#get_endpoint)
         """
```

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/literals.py` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,41 +2,43 @@
 Type annotations for iotdeviceadvisor service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iotdeviceadvisor.literals import ProtocolType
+    from types_aiobotocore_iotdeviceadvisor.literals import AuthenticationMethodType
 
-    data: ProtocolType = "MqttV3_1_1"
+    data: AuthenticationMethodType = "SignatureVersion4"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "AuthenticationMethodType",
     "ProtocolType",
     "StatusType",
     "SuiteRunStatusType",
     "TestCaseScenarioStatusType",
     "TestCaseScenarioTypeType",
     "IoTDeviceAdvisorServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
-ProtocolType = Literal["MqttV3_1_1", "MqttV5"]
+AuthenticationMethodType = Literal["SignatureVersion4", "X509ClientCertificate"]
+ProtocolType = Literal["MqttV3_1_1", "MqttV3_1_1_OverWebSocket", "MqttV5", "MqttV5_OverWebSocket"]
 StatusType = Literal[
     "CANCELED",
     "ERROR",
     "FAIL",
     "PASS",
     "PASS_WITH_WARNINGS",
     "PENDING",
@@ -126,14 +128,15 @@
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
@@ -212,14 +215,15 @@
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
@@ -230,14 +234,15 @@
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
@@ -273,14 +278,15 @@
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
@@ -299,16 +305,19 @@
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
@@ -392,15 +401,17 @@
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/literals.pyi` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -2,39 +2,41 @@
 Type annotations for iotdeviceadvisor service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iotdeviceadvisor.literals import ProtocolType
+    from types_aiobotocore_iotdeviceadvisor.literals import AuthenticationMethodType
 
-    data: ProtocolType = "MqttV3_1_1"
+    data: AuthenticationMethodType = "SignatureVersion4"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "AuthenticationMethodType",
     "ProtocolType",
     "StatusType",
     "SuiteRunStatusType",
     "TestCaseScenarioStatusType",
     "TestCaseScenarioTypeType",
     "IoTDeviceAdvisorServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-ProtocolType = Literal["MqttV3_1_1", "MqttV5"]
+AuthenticationMethodType = Literal["SignatureVersion4", "X509ClientCertificate"]
+ProtocolType = Literal["MqttV3_1_1", "MqttV3_1_1_OverWebSocket", "MqttV5", "MqttV5_OverWebSocket"]
 StatusType = Literal[
     "CANCELED",
     "ERROR",
     "FAIL",
     "PASS",
     "PASS_WITH_WARNINGS",
     "PENDING",
@@ -124,14 +126,15 @@
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
@@ -210,14 +213,15 @@
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
@@ -228,14 +232,15 @@
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
@@ -271,14 +276,15 @@
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
@@ -297,16 +303,19 @@
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
@@ -390,15 +399,17 @@
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/type_defs.py` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,58 +2,59 @@
 Type annotations for iotdeviceadvisor service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iotdeviceadvisor.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_iotdeviceadvisor.type_defs import CreateSuiteDefinitionResponseTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: CreateSuiteDefinitionResponseTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
+    AuthenticationMethodType,
     ProtocolType,
     StatusType,
     SuiteRunStatusType,
     TestCaseScenarioStatusType,
     TestCaseScenarioTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
+    "CreateSuiteDefinitionResponseTypeDef",
     "DeleteSuiteDefinitionRequestRequestTypeDef",
     "DeviceUnderTestTypeDef",
     "GetEndpointRequestRequestTypeDef",
+    "GetEndpointResponseTypeDef",
     "GetSuiteDefinitionRequestRequestTypeDef",
     "GetSuiteRunReportRequestRequestTypeDef",
+    "GetSuiteRunReportResponseTypeDef",
     "GetSuiteRunRequestRequestTypeDef",
     "ListSuiteDefinitionsRequestRequestTypeDef",
     "ListSuiteRunsRequestRequestTypeDef",
     "SuiteRunInformationTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartSuiteRunResponseTypeDef",
     "StopSuiteRunRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TestCaseScenarioTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CreateSuiteDefinitionResponseTypeDef",
-    "GetEndpointResponseTypeDef",
-    "GetSuiteRunReportResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartSuiteRunResponseTypeDef",
     "UpdateSuiteDefinitionResponseTypeDef",
     "SuiteDefinitionConfigurationTypeDef",
     "SuiteDefinitionInformationTypeDef",
     "SuiteRunConfigurationTypeDef",
     "ListSuiteRunsResponseTypeDef",
     "TestCaseRunTypeDef",
     "CreateSuiteDefinitionRequestRequestTypeDef",
@@ -62,22 +63,22 @@
     "ListSuiteDefinitionsResponseTypeDef",
     "StartSuiteRunRequestRequestTypeDef",
     "GroupResultTypeDef",
     "TestResultTypeDef",
     "GetSuiteRunResponseTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateSuiteDefinitionResponseTypeDef = TypedDict(
+    "CreateSuiteDefinitionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "suiteDefinitionId": str,
+        "suiteDefinitionArn": str,
+        "suiteDefinitionName": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSuiteDefinitionRequestRequestTypeDef = TypedDict(
     "DeleteSuiteDefinitionRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
@@ -85,27 +86,38 @@
 )
 
 DeviceUnderTestTypeDef = TypedDict(
     "DeviceUnderTestTypeDef",
     {
         "thingArn": str,
         "certificateArn": str,
+        "deviceRoleArn": str,
     },
     total=False,
 )
 
 GetEndpointRequestRequestTypeDef = TypedDict(
     "GetEndpointRequestRequestTypeDef",
     {
         "thingArn": str,
         "certificateArn": str,
+        "deviceRoleArn": str,
+        "authenticationMethod": AuthenticationMethodType,
     },
     total=False,
 )
 
+GetEndpointResponseTypeDef = TypedDict(
+    "GetEndpointResponseTypeDef",
+    {
+        "endpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetSuiteDefinitionRequestRequestTypeDef = TypedDict(
     "_RequiredGetSuiteDefinitionRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
     },
 )
 _OptionalGetSuiteDefinitionRequestRequestTypeDef = TypedDict(
@@ -128,14 +140,22 @@
     "GetSuiteRunReportRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteRunId": str,
     },
 )
 
+GetSuiteRunReportResponseTypeDef = TypedDict(
+    "GetSuiteRunReportResponseTypeDef",
+    {
+        "qualificationReportDownloadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSuiteRunRequestRequestTypeDef = TypedDict(
     "GetSuiteRunRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteRunId": str,
     },
 )
@@ -180,14 +200,44 @@
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
+StartSuiteRunResponseTypeDef = TypedDict(
+    "StartSuiteRunResponseTypeDef",
+    {
+        "suiteRunId": str,
+        "suiteRunArn": str,
+        "createdAt": datetime,
+        "endpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopSuiteRunRequestRequestTypeDef = TypedDict(
     "StopSuiteRunRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteRunId": str,
     },
 )
@@ -216,70 +266,24 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-CreateSuiteDefinitionResponseTypeDef = TypedDict(
-    "CreateSuiteDefinitionResponseTypeDef",
-    {
-        "suiteDefinitionId": str,
-        "suiteDefinitionArn": str,
-        "suiteDefinitionName": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetEndpointResponseTypeDef = TypedDict(
-    "GetEndpointResponseTypeDef",
-    {
-        "endpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSuiteRunReportResponseTypeDef = TypedDict(
-    "GetSuiteRunReportResponseTypeDef",
-    {
-        "qualificationReportDownloadUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSuiteRunResponseTypeDef = TypedDict(
-    "StartSuiteRunResponseTypeDef",
-    {
-        "suiteRunId": str,
-        "suiteRunArn": str,
-        "createdAt": datetime,
-        "endpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSuiteDefinitionResponseTypeDef = TypedDict(
     "UpdateSuiteDefinitionResponseTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteDefinitionArn": str,
         "suiteDefinitionName": str,
         "suiteDefinitionVersion": str,
         "createdAt": datetime,
         "lastUpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSuiteDefinitionConfigurationTypeDef = TypedDict(
     "_RequiredSuiteDefinitionConfigurationTypeDef",
     {
         "suiteDefinitionName": str,
@@ -342,15 +346,15 @@
 
 
 ListSuiteRunsResponseTypeDef = TypedDict(
     "ListSuiteRunsResponseTypeDef",
     {
         "suiteRunsList": List[SuiteRunInformationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestCaseRunTypeDef = TypedDict(
     "TestCaseRunTypeDef",
     {
         "testCaseRunId": str,
@@ -396,15 +400,15 @@
         "suiteDefinitionArn": str,
         "suiteDefinitionVersion": str,
         "latestVersion": str,
         "suiteDefinitionConfiguration": SuiteDefinitionConfigurationTypeDef,
         "createdAt": datetime,
         "lastModifiedAt": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSuiteDefinitionRequestRequestTypeDef = TypedDict(
     "UpdateSuiteDefinitionRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
@@ -413,15 +417,15 @@
 )
 
 ListSuiteDefinitionsResponseTypeDef = TypedDict(
     "ListSuiteDefinitionsResponseTypeDef",
     {
         "suiteDefinitionInformationList": List[SuiteDefinitionInformationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartSuiteRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartSuiteRunRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
@@ -472,10 +476,10 @@
         "suiteRunConfiguration": SuiteRunConfigurationTypeDef,
         "testResult": TestResultTypeDef,
         "startTime": datetime,
         "endTime": datetime,
         "status": SuiteRunStatusType,
         "errorReason": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor/type_defs.pyi` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,57 +2,58 @@
 Type annotations for iotdeviceadvisor service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iotdeviceadvisor.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_iotdeviceadvisor.type_defs import CreateSuiteDefinitionResponseTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: CreateSuiteDefinitionResponseTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
+    AuthenticationMethodType,
     ProtocolType,
     StatusType,
     SuiteRunStatusType,
     TestCaseScenarioStatusType,
     TestCaseScenarioTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
-    "ResponseMetadataTypeDef",
+    "CreateSuiteDefinitionResponseTypeDef",
     "DeleteSuiteDefinitionRequestRequestTypeDef",
     "DeviceUnderTestTypeDef",
     "GetEndpointRequestRequestTypeDef",
+    "GetEndpointResponseTypeDef",
     "GetSuiteDefinitionRequestRequestTypeDef",
     "GetSuiteRunReportRequestRequestTypeDef",
+    "GetSuiteRunReportResponseTypeDef",
     "GetSuiteRunRequestRequestTypeDef",
     "ListSuiteDefinitionsRequestRequestTypeDef",
     "ListSuiteRunsRequestRequestTypeDef",
     "SuiteRunInformationTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartSuiteRunResponseTypeDef",
     "StopSuiteRunRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TestCaseScenarioTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CreateSuiteDefinitionResponseTypeDef",
-    "GetEndpointResponseTypeDef",
-    "GetSuiteRunReportResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartSuiteRunResponseTypeDef",
     "UpdateSuiteDefinitionResponseTypeDef",
     "SuiteDefinitionConfigurationTypeDef",
     "SuiteDefinitionInformationTypeDef",
     "SuiteRunConfigurationTypeDef",
     "ListSuiteRunsResponseTypeDef",
     "TestCaseRunTypeDef",
     "CreateSuiteDefinitionRequestRequestTypeDef",
@@ -61,22 +62,22 @@
     "ListSuiteDefinitionsResponseTypeDef",
     "StartSuiteRunRequestRequestTypeDef",
     "GroupResultTypeDef",
     "TestResultTypeDef",
     "GetSuiteRunResponseTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateSuiteDefinitionResponseTypeDef = TypedDict(
+    "CreateSuiteDefinitionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "suiteDefinitionId": str,
+        "suiteDefinitionArn": str,
+        "suiteDefinitionName": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSuiteDefinitionRequestRequestTypeDef = TypedDict(
     "DeleteSuiteDefinitionRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
@@ -84,27 +85,38 @@
 )
 
 DeviceUnderTestTypeDef = TypedDict(
     "DeviceUnderTestTypeDef",
     {
         "thingArn": str,
         "certificateArn": str,
+        "deviceRoleArn": str,
     },
     total=False,
 )
 
 GetEndpointRequestRequestTypeDef = TypedDict(
     "GetEndpointRequestRequestTypeDef",
     {
         "thingArn": str,
         "certificateArn": str,
+        "deviceRoleArn": str,
+        "authenticationMethod": AuthenticationMethodType,
     },
     total=False,
 )
 
+GetEndpointResponseTypeDef = TypedDict(
+    "GetEndpointResponseTypeDef",
+    {
+        "endpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetSuiteDefinitionRequestRequestTypeDef = TypedDict(
     "_RequiredGetSuiteDefinitionRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
     },
 )
 _OptionalGetSuiteDefinitionRequestRequestTypeDef = TypedDict(
@@ -125,14 +137,22 @@
     "GetSuiteRunReportRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteRunId": str,
     },
 )
 
+GetSuiteRunReportResponseTypeDef = TypedDict(
+    "GetSuiteRunReportResponseTypeDef",
+    {
+        "qualificationReportDownloadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSuiteRunRequestRequestTypeDef = TypedDict(
     "GetSuiteRunRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteRunId": str,
     },
 )
@@ -177,14 +197,44 @@
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
+StartSuiteRunResponseTypeDef = TypedDict(
+    "StartSuiteRunResponseTypeDef",
+    {
+        "suiteRunId": str,
+        "suiteRunArn": str,
+        "createdAt": datetime,
+        "endpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopSuiteRunRequestRequestTypeDef = TypedDict(
     "StopSuiteRunRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteRunId": str,
     },
 )
@@ -213,70 +263,24 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-CreateSuiteDefinitionResponseTypeDef = TypedDict(
-    "CreateSuiteDefinitionResponseTypeDef",
-    {
-        "suiteDefinitionId": str,
-        "suiteDefinitionArn": str,
-        "suiteDefinitionName": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetEndpointResponseTypeDef = TypedDict(
-    "GetEndpointResponseTypeDef",
-    {
-        "endpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSuiteRunReportResponseTypeDef = TypedDict(
-    "GetSuiteRunReportResponseTypeDef",
-    {
-        "qualificationReportDownloadUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSuiteRunResponseTypeDef = TypedDict(
-    "StartSuiteRunResponseTypeDef",
-    {
-        "suiteRunId": str,
-        "suiteRunArn": str,
-        "createdAt": datetime,
-        "endpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateSuiteDefinitionResponseTypeDef = TypedDict(
     "UpdateSuiteDefinitionResponseTypeDef",
     {
         "suiteDefinitionId": str,
         "suiteDefinitionArn": str,
         "suiteDefinitionName": str,
         "suiteDefinitionVersion": str,
         "createdAt": datetime,
         "lastUpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSuiteDefinitionConfigurationTypeDef = TypedDict(
     "_RequiredSuiteDefinitionConfigurationTypeDef",
     {
         "suiteDefinitionName": str,
@@ -335,15 +339,15 @@
     pass
 
 ListSuiteRunsResponseTypeDef = TypedDict(
     "ListSuiteRunsResponseTypeDef",
     {
         "suiteRunsList": List[SuiteRunInformationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestCaseRunTypeDef = TypedDict(
     "TestCaseRunTypeDef",
     {
         "testCaseRunId": str,
@@ -387,15 +391,15 @@
         "suiteDefinitionArn": str,
         "suiteDefinitionVersion": str,
         "latestVersion": str,
         "suiteDefinitionConfiguration": SuiteDefinitionConfigurationTypeDef,
         "createdAt": datetime,
         "lastModifiedAt": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSuiteDefinitionRequestRequestTypeDef = TypedDict(
     "UpdateSuiteDefinitionRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
@@ -404,15 +408,15 @@
 )
 
 ListSuiteDefinitionsResponseTypeDef = TypedDict(
     "ListSuiteDefinitionsResponseTypeDef",
     {
         "suiteDefinitionInformationList": List[SuiteDefinitionInformationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartSuiteRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartSuiteRunRequestRequestTypeDef",
     {
         "suiteDefinitionId": str,
@@ -461,10 +465,10 @@
         "suiteRunConfiguration": SuiteRunConfigurationTypeDef,
         "testResult": TestResultTypeDef,
         "startTime": datetime,
         "endTime": datetime,
         "status": SuiteRunStatusType,
         "errorReason": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/PKG-INFO` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotdeviceadvisor
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTDeviceAdvisor 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotdeviceadvisor"></a>
 
 # types-aiobotocore-iotdeviceadvisor
 
 [![PyPI - types-aiobotocore-iotdeviceadvisor](https://img.shields.io/pypi/v/types-aiobotocore-iotdeviceadvisor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotdeviceadvisor.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotdeviceadvisor)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotdeviceadvisor?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotdeviceadvisor)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTDeviceAdvisor 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
+[aiobotocore.IoTDeviceAdvisor 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotdeviceadvisor.html#IoTDeviceAdvisor)
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
 [types-aiobotocore-iotdeviceadvisor docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotdeviceadvisor/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,59 +269,60 @@
 ### Literals
 
 `types_aiobotocore_iotdeviceadvisor.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotdeviceadvisor.literals import (
+    AuthenticationMethodType,
     ProtocolType,
     StatusType,
     SuiteRunStatusType,
     TestCaseScenarioStatusType,
     TestCaseScenarioTypeType,
     IoTDeviceAdvisorServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: ProtocolType) -> bool:
+def check_value(value: AuthenticationMethodType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_iotdeviceadvisor.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotdeviceadvisor.type_defs import (
-    ResponseMetadataTypeDef,
+    CreateSuiteDefinitionResponseTypeDef,
     DeleteSuiteDefinitionRequestRequestTypeDef,
     DeviceUnderTestTypeDef,
     GetEndpointRequestRequestTypeDef,
+    GetEndpointResponseTypeDef,
     GetSuiteDefinitionRequestRequestTypeDef,
     GetSuiteRunReportRequestRequestTypeDef,
+    GetSuiteRunReportResponseTypeDef,
     GetSuiteRunRequestRequestTypeDef,
     ListSuiteDefinitionsRequestRequestTypeDef,
     ListSuiteRunsRequestRequestTypeDef,
     SuiteRunInformationTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
+    StartSuiteRunResponseTypeDef,
     StopSuiteRunRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TestCaseScenarioTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateSuiteDefinitionResponseTypeDef,
-    GetEndpointResponseTypeDef,
-    GetSuiteRunReportResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartSuiteRunResponseTypeDef,
     UpdateSuiteDefinitionResponseTypeDef,
     SuiteDefinitionConfigurationTypeDef,
     SuiteDefinitionInformationTypeDef,
     SuiteRunConfigurationTypeDef,
     ListSuiteRunsResponseTypeDef,
     TestCaseRunTypeDef,
     CreateSuiteDefinitionRequestRequestTypeDef,
@@ -331,54 +332,54 @@
     StartSuiteRunRequestRequestTypeDef,
     GroupResultTypeDef,
     TestResultTypeDef,
     GetSuiteRunResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> CreateSuiteDefinitionResponseTypeDef:
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

### Comparing `types-aiobotocore-iotdeviceadvisor-2.5.0.post1/types_aiobotocore_iotdeviceadvisor.egg-info/SOURCES.txt` & `types-aiobotocore-iotdeviceadvisor-2.5.1/types_aiobotocore_iotdeviceadvisor.egg-info/SOURCES.txt`

 * *Files identical despite different names*

