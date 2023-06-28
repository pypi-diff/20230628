# Comparing `tmp/types-aiobotocore-sagemaker-edge-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sagemaker-edge-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sagemaker-edge-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:16 2023, max compression
+gzip compressed data, was "types-aiobotocore-sagemaker-edge-2.5.1.tar", last modified: Wed Jun 28 01:44:07 2023, max compression
```

## Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1.tar` & `types-aiobotocore-sagemaker-edge-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.027585 types-aiobotocore-sagemaker-edge-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12962 2023-03-11 12:27:16.027585 types-aiobotocore-sagemaker-edge-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:16.027585 types-aiobotocore-sagemaker-edge-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2179 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.027585 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/
--rw-r--r--   0 runner    (1001) docker     (123)      528 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      527 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6228 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6217 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7865 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7863 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     4845 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     4842 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.027585 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12962 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      853 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:15.000000 types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.322208 types-aiobotocore-sagemaker-edge-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12961 2023-06-28 01:44:07.322208 types-aiobotocore-sagemaker-edge-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11362 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:07.322208 types-aiobotocore-sagemaker-edge-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-06-28 01:40:16.000000 types-aiobotocore-sagemaker-edge-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.322208 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/
+-rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      527 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6228 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6217 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8074 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8072 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     4851 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4848 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.322208 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12961 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      853 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/LICENSE` & `types-aiobotocore-sagemaker-edge-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sagemaker-edge-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-edge
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SagemakerEdgeManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SagemakerEdgeManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-edge"></a>
 
 # types-aiobotocore-sagemaker-edge
 
 [![PyPI - types-aiobotocore-sagemaker-edge](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-edge.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-edge)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-edge.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-edge)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-edge?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-edge)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SagemakerEdgeManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
+[aiobotocore.SagemakerEdgeManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
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
 [types-aiobotocore-sagemaker-edge docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,22 +297,22 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_edge.type_defs import (
     ChecksumTypeDef,
     DeploymentModelTypeDef,
     EdgeMetricTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetDeploymentsRequestRequestTypeDef,
     GetDeviceRegistrationRequestRequestTypeDef,
+    GetDeviceRegistrationResultTypeDef,
+    ResponseMetadataTypeDef,
     DefinitionTypeDef,
     DeploymentResultTypeDef,
     ModelTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDeviceRegistrationResultTypeDef,
     EdgeDeploymentTypeDef,
     SendHeartbeatRequestRequestTypeDef,
     GetDeploymentsResultTypeDef,
 )
 
 
 def get_structure() -> ChecksumTypeDef:
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/README.md` & `types-aiobotocore-sagemaker-edge-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sagemaker-edge"></a>
 
 # types-aiobotocore-sagemaker-edge
 
 [![PyPI - types-aiobotocore-sagemaker-edge](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-edge.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-edge)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-edge.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-edge)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-edge?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-edge)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SagemakerEdgeManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
+[aiobotocore.SagemakerEdgeManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
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
 [types-aiobotocore-sagemaker-edge docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/).
 
 See how it helps to find and fix potential bugs:
 
@@ -264,22 +264,22 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_edge.type_defs import (
     ChecksumTypeDef,
     DeploymentModelTypeDef,
     EdgeMetricTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetDeploymentsRequestRequestTypeDef,
     GetDeviceRegistrationRequestRequestTypeDef,
+    GetDeviceRegistrationResultTypeDef,
+    ResponseMetadataTypeDef,
     DefinitionTypeDef,
     DeploymentResultTypeDef,
     ModelTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDeviceRegistrationResultTypeDef,
     EdgeDeploymentTypeDef,
     SendHeartbeatRequestRequestTypeDef,
     GetDeploymentsResultTypeDef,
 )
 
 
 def get_structure() -> ChecksumTypeDef:
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/setup.py` & `types-aiobotocore-sagemaker-edge-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sagemaker-edge.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sagemaker-edge",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sagemaker_edge"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SagemakerEdgeManager 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SagemakerEdgeManager 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/"
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/__init__.py` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/__init__.pyi` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/__main__.py` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SagemakerEdgeManager 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SagemakerEdgeManager 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager\nOther"
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/client.py` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/client.pyi` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/literals.py` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,28 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ChecksumTypeType",
     "DeploymentStatusType",
     "DeploymentTypeType",
     "FailureHandlingPolicyType",
     "ModelStateType",
     "SagemakerEdgeManagerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 ChecksumTypeType = Literal["SHA1"]
 DeploymentStatusType = Literal["FAIL", "SUCCESS"]
 DeploymentTypeType = Literal["Model"]
 FailureHandlingPolicyType = Literal["DO_NOTHING", "ROLLBACK_ON_FAILURE"]
 ModelStateType = Literal["DEPLOY", "UNDEPLOY"]
 SagemakerEdgeManagerServiceName = Literal["sagemaker-edge"]
 ServiceName = Literal[
@@ -96,14 +94,15 @@
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
@@ -182,14 +181,15 @@
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
@@ -200,14 +200,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -269,16 +271,19 @@
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
@@ -362,15 +367,17 @@
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/literals.pyi` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,26 +14,28 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ChecksumTypeType",
     "DeploymentStatusType",
     "DeploymentTypeType",
     "FailureHandlingPolicyType",
     "ModelStateType",
     "SagemakerEdgeManagerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 ChecksumTypeType = Literal["SHA1"]
 DeploymentStatusType = Literal["FAIL", "SUCCESS"]
 DeploymentTypeType = Literal["Model"]
 FailureHandlingPolicyType = Literal["DO_NOTHING", "ROLLBACK_ON_FAILURE"]
 ModelStateType = Literal["DEPLOY", "UNDEPLOY"]
 SagemakerEdgeManagerServiceName = Literal["sagemaker-edge"]
 ServiceName = Literal[
@@ -94,14 +96,15 @@
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
@@ -180,14 +183,15 @@
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
@@ -198,14 +202,15 @@
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
@@ -241,14 +246,15 @@
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
@@ -267,16 +273,19 @@
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
@@ -360,15 +369,17 @@
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/type_defs.py` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,22 +27,22 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ChecksumTypeDef",
     "DeploymentModelTypeDef",
     "EdgeMetricTypeDef",
-    "ResponseMetadataTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetDeploymentsRequestRequestTypeDef",
     "GetDeviceRegistrationRequestRequestTypeDef",
+    "GetDeviceRegistrationResultTypeDef",
+    "ResponseMetadataTypeDef",
     "DefinitionTypeDef",
     "DeploymentResultTypeDef",
     "ModelTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetDeviceRegistrationResultTypeDef",
     "EdgeDeploymentTypeDef",
     "SendHeartbeatRequestRequestTypeDef",
     "GetDeploymentsResultTypeDef",
 )
 
 ChecksumTypeDef = TypedDict(
     "ChecksumTypeDef",
@@ -75,22 +75,18 @@
         "MetricName": str,
         "Value": float,
         "Timestamp": Union[datetime, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentsRequestRequestTypeDef = TypedDict(
     "GetDeploymentsRequestRequestTypeDef",
     {
         "DeviceName": str,
@@ -102,14 +98,34 @@
     "GetDeviceRegistrationRequestRequestTypeDef",
     {
         "DeviceName": str,
         "DeviceFleetName": str,
     },
 )
 
+GetDeviceRegistrationResultTypeDef = TypedDict(
+    "GetDeviceRegistrationResultTypeDef",
+    {
+        "DeviceRegistration": str,
+        "CacheTTL": str,
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
 DefinitionTypeDef = TypedDict(
     "DefinitionTypeDef",
     {
         "ModelHandle": str,
         "S3Url": str,
         "Checksum": ChecksumTypeDef,
         "State": ModelStateType,
@@ -138,30 +154,14 @@
         "LatestSampleTime": Union[datetime, str],
         "LatestInference": Union[datetime, str],
         "ModelMetrics": Sequence[EdgeMetricTypeDef],
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeviceRegistrationResultTypeDef = TypedDict(
-    "GetDeviceRegistrationResultTypeDef",
-    {
-        "DeviceRegistration": str,
-        "CacheTTL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 EdgeDeploymentTypeDef = TypedDict(
     "EdgeDeploymentTypeDef",
     {
         "DeploymentName": str,
         "Type": Literal["Model"],
         "FailureHandlingPolicy": FailureHandlingPolicyType,
         "Definitions": List[DefinitionTypeDef],
@@ -194,10 +194,10 @@
     pass
 
 
 GetDeploymentsResultTypeDef = TypedDict(
     "GetDeploymentsResultTypeDef",
     {
         "Deployments": List[EdgeDeploymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge/type_defs.pyi` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,22 +26,22 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ChecksumTypeDef",
     "DeploymentModelTypeDef",
     "EdgeMetricTypeDef",
-    "ResponseMetadataTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetDeploymentsRequestRequestTypeDef",
     "GetDeviceRegistrationRequestRequestTypeDef",
+    "GetDeviceRegistrationResultTypeDef",
+    "ResponseMetadataTypeDef",
     "DefinitionTypeDef",
     "DeploymentResultTypeDef",
     "ModelTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetDeviceRegistrationResultTypeDef",
     "EdgeDeploymentTypeDef",
     "SendHeartbeatRequestRequestTypeDef",
     "GetDeploymentsResultTypeDef",
 )
 
 ChecksumTypeDef = TypedDict(
     "ChecksumTypeDef",
@@ -74,22 +74,18 @@
         "MetricName": str,
         "Value": float,
         "Timestamp": Union[datetime, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentsRequestRequestTypeDef = TypedDict(
     "GetDeploymentsRequestRequestTypeDef",
     {
         "DeviceName": str,
@@ -101,14 +97,34 @@
     "GetDeviceRegistrationRequestRequestTypeDef",
     {
         "DeviceName": str,
         "DeviceFleetName": str,
     },
 )
 
+GetDeviceRegistrationResultTypeDef = TypedDict(
+    "GetDeviceRegistrationResultTypeDef",
+    {
+        "DeviceRegistration": str,
+        "CacheTTL": str,
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
 DefinitionTypeDef = TypedDict(
     "DefinitionTypeDef",
     {
         "ModelHandle": str,
         "S3Url": str,
         "Checksum": ChecksumTypeDef,
         "State": ModelStateType,
@@ -137,30 +153,14 @@
         "LatestSampleTime": Union[datetime, str],
         "LatestInference": Union[datetime, str],
         "ModelMetrics": Sequence[EdgeMetricTypeDef],
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeviceRegistrationResultTypeDef = TypedDict(
-    "GetDeviceRegistrationResultTypeDef",
-    {
-        "DeviceRegistration": str,
-        "CacheTTL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 EdgeDeploymentTypeDef = TypedDict(
     "EdgeDeploymentTypeDef",
     {
         "DeploymentName": str,
         "Type": Literal["Model"],
         "FailureHandlingPolicy": FailureHandlingPolicyType,
         "Definitions": List[DefinitionTypeDef],
@@ -191,10 +191,10 @@
 ):
     pass
 
 GetDeploymentsResultTypeDef = TypedDict(
     "GetDeploymentsResultTypeDef",
     {
         "Deployments": List[EdgeDeploymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/PKG-INFO` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-edge
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SagemakerEdgeManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SagemakerEdgeManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-edge"></a>
 
 # types-aiobotocore-sagemaker-edge
 
 [![PyPI - types-aiobotocore-sagemaker-edge](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-edge.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-edge)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-edge.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-edge)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-edge?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-edge)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SagemakerEdgeManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
+[aiobotocore.SagemakerEdgeManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-edge.html#SagemakerEdgeManager)
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
 [types-aiobotocore-sagemaker-edge docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_edge/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,22 +297,22 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_edge.type_defs import (
     ChecksumTypeDef,
     DeploymentModelTypeDef,
     EdgeMetricTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetDeploymentsRequestRequestTypeDef,
     GetDeviceRegistrationRequestRequestTypeDef,
+    GetDeviceRegistrationResultTypeDef,
+    ResponseMetadataTypeDef,
     DefinitionTypeDef,
     DeploymentResultTypeDef,
     ModelTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetDeviceRegistrationResultTypeDef,
     EdgeDeploymentTypeDef,
     SendHeartbeatRequestRequestTypeDef,
     GetDeploymentsResultTypeDef,
 )
 
 
 def get_structure() -> ChecksumTypeDef:
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

### Comparing `types-aiobotocore-sagemaker-edge-2.5.0.post1/types_aiobotocore_sagemaker_edge.egg-info/SOURCES.txt` & `types-aiobotocore-sagemaker-edge-2.5.1/types_aiobotocore_sagemaker_edge.egg-info/SOURCES.txt`

 * *Files identical despite different names*

