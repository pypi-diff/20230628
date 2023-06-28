# Comparing `tmp/types-aiobotocore-braket-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-braket-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-braket-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-braket-2.5.1.tar", last modified: Wed Jun 28 01:43:10 2023, max compression
```

## Comparing `types-aiobotocore-braket-2.5.0.post1.tar` & `types-aiobotocore-braket-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.454998 types-aiobotocore-braket-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14973 2023-03-11 12:26:17.446998 types-aiobotocore-braket-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13406 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.454998 types-aiobotocore-braket-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:10:12.000000 types-aiobotocore-braket-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.438997 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/
--rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13700 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9860 2023-03-11 12:10:14.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9858 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4507 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4501 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    17657 2023-03-11 12:10:14.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17626 2023-03-11 12:10:14.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:13.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.446998 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14973 2023-03-11 12:26:17.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:17.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.274101 types-aiobotocore-braket-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14964 2023-06-28 01:43:10.274101 types-aiobotocore-braket-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13403 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:10.274101 types-aiobotocore-braket-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:26:49.000000 types-aiobotocore-braket-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.270101 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/
+-rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1021 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13700 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10069 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10067 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4393 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4388 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    17685 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17654 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:50.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.274101 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14964 2023-06-28 01:43:10.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:10.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:10.000000 types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-braket-2.5.0.post1/LICENSE` & `types-aiobotocore-braket-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-braket-2.5.0.post1/PKG-INFO` & `types-aiobotocore-braket-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-braket
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Braket 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Braket 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-braket"></a>
 
 # types-aiobotocore-braket
 
 [![PyPI - types-aiobotocore-braket](https://img.shields.io/pypi/v/types-aiobotocore-braket.svg?color=blue)](https://pypi.org/project/types-aiobotocore-braket)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-braket.svg?color=blue)](https://pypi.org/project/types-aiobotocore-braket)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-braket?color=blue)](https://pypistats.org/packages/types-aiobotocore-braket)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Braket 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket)
+[aiobotocore.Braket 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket)
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
 [types-aiobotocore-braket docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,45 +336,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_braket.type_defs import (
     ContainerImageTypeDef,
     ScriptModeConfigTypeDef,
     CancelJobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobResponseTypeDef,
     CancelQuantumTaskRequestRequestTypeDef,
+    CancelQuantumTaskResponseTypeDef,
     DeviceConfigTypeDef,
     InstanceConfigTypeDef,
     JobCheckpointConfigTypeDef,
     JobOutputDataConfigTypeDef,
     JobStoppingConditionTypeDef,
+    CreateJobResponseTypeDef,
     CreateQuantumTaskRequestRequestTypeDef,
+    CreateQuantumTaskResponseTypeDef,
     S3DataSourceTypeDef,
     DeviceSummaryTypeDef,
     GetDeviceRequestRequestTypeDef,
+    GetDeviceResponseTypeDef,
     GetJobRequestRequestTypeDef,
     JobEventDetailsTypeDef,
     GetQuantumTaskRequestRequestTypeDef,
+    GetQuantumTaskResponseTypeDef,
     JobSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     QuantumTaskSummaryTypeDef,
+    ResponseMetadataTypeDef,
     SearchDevicesFilterTypeDef,
     SearchJobsFilterTypeDef,
     SearchQuantumTasksFilterTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AlgorithmSpecificationTypeDef,
-    CancelJobResponseTypeDef,
-    CancelQuantumTaskResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateQuantumTaskResponseTypeDef,
-    GetDeviceResponseTypeDef,
-    GetQuantumTaskResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     DataSourceTypeDef,
     SearchDevicesResponseTypeDef,
     SearchJobsResponseTypeDef,
     SearchQuantumTasksResponseTypeDef,
     SearchDevicesRequestRequestTypeDef,
     SearchDevicesRequestSearchDevicesPaginateTypeDef,
     SearchJobsRequestRequestTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/README.md` & `types-aiobotocore-braket-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-braket"></a>
 
 # types-aiobotocore-braket
 
 [![PyPI - types-aiobotocore-braket](https://img.shields.io/pypi/v/types-aiobotocore-braket.svg?color=blue)](https://pypi.org/project/types-aiobotocore-braket)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-braket.svg?color=blue)](https://pypi.org/project/types-aiobotocore-braket)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-braket?color=blue)](https://pypistats.org/packages/types-aiobotocore-braket)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Braket 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket)
+[aiobotocore.Braket 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket)
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
 [types-aiobotocore-braket docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/).
 
 See how it helps to find and fix potential bugs:
 
@@ -303,45 +303,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_braket.type_defs import (
     ContainerImageTypeDef,
     ScriptModeConfigTypeDef,
     CancelJobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobResponseTypeDef,
     CancelQuantumTaskRequestRequestTypeDef,
+    CancelQuantumTaskResponseTypeDef,
     DeviceConfigTypeDef,
     InstanceConfigTypeDef,
     JobCheckpointConfigTypeDef,
     JobOutputDataConfigTypeDef,
     JobStoppingConditionTypeDef,
+    CreateJobResponseTypeDef,
     CreateQuantumTaskRequestRequestTypeDef,
+    CreateQuantumTaskResponseTypeDef,
     S3DataSourceTypeDef,
     DeviceSummaryTypeDef,
     GetDeviceRequestRequestTypeDef,
+    GetDeviceResponseTypeDef,
     GetJobRequestRequestTypeDef,
     JobEventDetailsTypeDef,
     GetQuantumTaskRequestRequestTypeDef,
+    GetQuantumTaskResponseTypeDef,
     JobSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     QuantumTaskSummaryTypeDef,
+    ResponseMetadataTypeDef,
     SearchDevicesFilterTypeDef,
     SearchJobsFilterTypeDef,
     SearchQuantumTasksFilterTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AlgorithmSpecificationTypeDef,
-    CancelJobResponseTypeDef,
-    CancelQuantumTaskResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateQuantumTaskResponseTypeDef,
-    GetDeviceResponseTypeDef,
-    GetQuantumTaskResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     DataSourceTypeDef,
     SearchDevicesResponseTypeDef,
     SearchJobsResponseTypeDef,
     SearchQuantumTasksResponseTypeDef,
     SearchDevicesRequestRequestTypeDef,
     SearchDevicesRequestSearchDevicesPaginateTypeDef,
     SearchJobsRequestRequestTypeDef,
@@ -361,43 +361,43 @@
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/setup.py` & `types-aiobotocore-braket-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-braket.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-braket",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_braket"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Braket 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Braket 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/"
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/__init__.py` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/__init__.pyi` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/__main__.py` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Braket 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Braket 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket\nOther"
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/client.py` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/client.pyi` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/literals.py` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -169,14 +169,15 @@
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
@@ -255,14 +256,15 @@
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
@@ -273,14 +275,15 @@
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
@@ -316,14 +319,15 @@
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
@@ -342,16 +346,19 @@
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
@@ -435,15 +442,17 @@
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/literals.pyi` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -167,14 +167,15 @@
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
@@ -253,14 +254,15 @@
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
@@ -271,14 +273,15 @@
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
@@ -314,14 +317,15 @@
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
@@ -340,16 +344,19 @@
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
@@ -433,15 +440,17 @@
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/paginator.py` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,36 +20,29 @@
         client: BraketClient
 
         search_devices_paginator: SearchDevicesPaginator = client.get_paginator("search_devices")
         search_jobs_paginator: SearchJobsPaginator = client.get_paginator("search_jobs")
         search_quantum_tasks_paginator: SearchQuantumTasksPaginator = client.get_paginator("search_quantum_tasks")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     PaginatorConfigTypeDef,
     SearchDevicesFilterTypeDef,
     SearchDevicesResponseTypeDef,
     SearchJobsFilterTypeDef,
     SearchJobsResponseTypeDef,
     SearchQuantumTasksFilterTypeDef,
     SearchQuantumTasksResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("SearchDevicesPaginator", "SearchJobsPaginator", "SearchQuantumTasksPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -65,15 +58,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchdevicespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SearchDevicesFilterTypeDef],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket.Paginator.SearchDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchdevicespaginator)
         """
 
 
@@ -83,15 +76,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SearchJobsFilterTypeDef],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket.Paginator.SearchJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchjobspaginator)
         """
 
 
@@ -101,13 +94,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchquantumtaskspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SearchQuantumTasksFilterTypeDef],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchQuantumTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket.Paginator.SearchQuantumTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchquantumtaskspaginator)
         """
```

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/paginator.pyi` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -20,35 +20,29 @@
         client: BraketClient
 
         search_devices_paginator: SearchDevicesPaginator = client.get_paginator("search_devices")
         search_jobs_paginator: SearchJobsPaginator = client.get_paginator("search_jobs")
         search_quantum_tasks_paginator: SearchQuantumTasksPaginator = client.get_paginator("search_quantum_tasks")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     PaginatorConfigTypeDef,
     SearchDevicesFilterTypeDef,
     SearchDevicesResponseTypeDef,
     SearchJobsFilterTypeDef,
     SearchJobsResponseTypeDef,
     SearchQuantumTasksFilterTypeDef,
     SearchQuantumTasksResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("SearchDevicesPaginator", "SearchJobsPaginator", "SearchQuantumTasksPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -61,15 +55,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchdevicespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SearchDevicesFilterTypeDef],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket.Paginator.SearchDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchdevicespaginator)
         """
 
 class SearchJobsPaginator(AioPaginator):
@@ -78,15 +72,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SearchJobsFilterTypeDef],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket.Paginator.SearchJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchjobspaginator)
         """
 
 class SearchQuantumTasksPaginator(AioPaginator):
@@ -95,13 +89,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchquantumtaskspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SearchQuantumTasksFilterTypeDef],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchQuantumTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket.Paginator.SearchQuantumTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/paginators/#searchquantumtaskspaginator)
         """
```

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/type_defs.py` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -29,50 +29,49 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ContainerImageTypeDef",
     "ScriptModeConfigTypeDef",
     "CancelJobRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobResponseTypeDef",
     "CancelQuantumTaskRequestRequestTypeDef",
+    "CancelQuantumTaskResponseTypeDef",
     "DeviceConfigTypeDef",
     "InstanceConfigTypeDef",
     "JobCheckpointConfigTypeDef",
     "JobOutputDataConfigTypeDef",
     "JobStoppingConditionTypeDef",
+    "CreateJobResponseTypeDef",
     "CreateQuantumTaskRequestRequestTypeDef",
+    "CreateQuantumTaskResponseTypeDef",
     "S3DataSourceTypeDef",
     "DeviceSummaryTypeDef",
     "GetDeviceRequestRequestTypeDef",
+    "GetDeviceResponseTypeDef",
     "GetJobRequestRequestTypeDef",
     "JobEventDetailsTypeDef",
     "GetQuantumTaskRequestRequestTypeDef",
+    "GetQuantumTaskResponseTypeDef",
     "JobSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "PaginatorConfigTypeDef",
     "QuantumTaskSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchDevicesFilterTypeDef",
     "SearchJobsFilterTypeDef",
     "SearchQuantumTasksFilterTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AlgorithmSpecificationTypeDef",
-    "CancelJobResponseTypeDef",
-    "CancelQuantumTaskResponseTypeDef",
-    "CreateJobResponseTypeDef",
-    "CreateQuantumTaskResponseTypeDef",
-    "GetDeviceResponseTypeDef",
-    "GetQuantumTaskResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "DataSourceTypeDef",
     "SearchDevicesResponseTypeDef",
     "SearchJobsResponseTypeDef",
     "SearchQuantumTasksResponseTypeDef",
     "SearchDevicesRequestRequestTypeDef",
     "SearchDevicesRequestSearchDevicesPaginateTypeDef",
     "SearchJobsRequestRequestTypeDef",
@@ -102,45 +101,50 @@
     "_OptionalScriptModeConfigTypeDef",
     {
         "compressionType": CompressionTypeType,
     },
     total=False,
 )
 
-
 class ScriptModeConfigTypeDef(_RequiredScriptModeConfigTypeDef, _OptionalScriptModeConfigTypeDef):
     pass
 
-
 CancelJobRequestRequestTypeDef = TypedDict(
     "CancelJobRequestRequestTypeDef",
     {
         "jobArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJobResponseTypeDef = TypedDict(
+    "CancelJobResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "cancellationStatus": CancellationStatusType,
+        "jobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelQuantumTaskRequestRequestTypeDef = TypedDict(
     "CancelQuantumTaskRequestRequestTypeDef",
     {
         "clientToken": str,
         "quantumTaskArn": str,
     },
 )
 
+CancelQuantumTaskResponseTypeDef = TypedDict(
+    "CancelQuantumTaskResponseTypeDef",
+    {
+        "cancellationStatus": CancellationStatusType,
+        "quantumTaskArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeviceConfigTypeDef = TypedDict(
     "DeviceConfigTypeDef",
     {
         "device": str,
     },
 )
 
@@ -155,69 +159,71 @@
     "_OptionalInstanceConfigTypeDef",
     {
         "instanceCount": int,
     },
     total=False,
 )
 
-
 class InstanceConfigTypeDef(_RequiredInstanceConfigTypeDef, _OptionalInstanceConfigTypeDef):
     pass
 
-
 _RequiredJobCheckpointConfigTypeDef = TypedDict(
     "_RequiredJobCheckpointConfigTypeDef",
     {
         "s3Uri": str,
     },
 )
 _OptionalJobCheckpointConfigTypeDef = TypedDict(
     "_OptionalJobCheckpointConfigTypeDef",
     {
         "localPath": str,
     },
     total=False,
 )
 
-
 class JobCheckpointConfigTypeDef(
     _RequiredJobCheckpointConfigTypeDef, _OptionalJobCheckpointConfigTypeDef
 ):
     pass
 
-
 _RequiredJobOutputDataConfigTypeDef = TypedDict(
     "_RequiredJobOutputDataConfigTypeDef",
     {
         "s3Path": str,
     },
 )
 _OptionalJobOutputDataConfigTypeDef = TypedDict(
     "_OptionalJobOutputDataConfigTypeDef",
     {
         "kmsKeyId": str,
     },
     total=False,
 )
 
-
 class JobOutputDataConfigTypeDef(
     _RequiredJobOutputDataConfigTypeDef, _OptionalJobOutputDataConfigTypeDef
 ):
     pass
 
-
 JobStoppingConditionTypeDef = TypedDict(
     "JobStoppingConditionTypeDef",
     {
         "maxRuntimeInSeconds": int,
     },
     total=False,
 )
 
+CreateJobResponseTypeDef = TypedDict(
+    "CreateJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateQuantumTaskRequestRequestTypeDef = TypedDict(
     "_RequiredCreateQuantumTaskRequestRequestTypeDef",
     {
         "action": str,
         "clientToken": str,
         "deviceArn": str,
         "outputS3Bucket": str,
@@ -231,20 +237,26 @@
         "deviceParameters": str,
         "jobToken": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateQuantumTaskRequestRequestTypeDef(
     _RequiredCreateQuantumTaskRequestRequestTypeDef, _OptionalCreateQuantumTaskRequestRequestTypeDef
 ):
     pass
 
+CreateQuantumTaskResponseTypeDef = TypedDict(
+    "CreateQuantumTaskResponseTypeDef",
+    {
+        "quantumTaskArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 S3DataSourceTypeDef = TypedDict(
     "S3DataSourceTypeDef",
     {
         "s3Uri": str,
     },
 )
@@ -263,14 +275,27 @@
 GetDeviceRequestRequestTypeDef = TypedDict(
     "GetDeviceRequestRequestTypeDef",
     {
         "deviceArn": str,
     },
 )
 
+GetDeviceResponseTypeDef = TypedDict(
+    "GetDeviceResponseTypeDef",
+    {
+        "deviceArn": str,
+        "deviceCapabilities": str,
+        "deviceName": str,
+        "deviceStatus": DeviceStatusType,
+        "deviceType": DeviceTypeType,
+        "providerName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobRequestRequestTypeDef = TypedDict(
     "GetJobRequestRequestTypeDef",
     {
         "jobArn": str,
     },
 )
 
@@ -287,14 +312,33 @@
 GetQuantumTaskRequestRequestTypeDef = TypedDict(
     "GetQuantumTaskRequestRequestTypeDef",
     {
         "quantumTaskArn": str,
     },
 )
 
+GetQuantumTaskResponseTypeDef = TypedDict(
+    "GetQuantumTaskResponseTypeDef",
+    {
+        "createdAt": datetime,
+        "deviceArn": str,
+        "deviceParameters": str,
+        "endedAt": datetime,
+        "failureReason": str,
+        "jobArn": str,
+        "outputS3Bucket": str,
+        "outputS3Directory": str,
+        "quantumTaskArn": str,
+        "shots": int,
+        "status": QuantumTaskStatusType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredJobSummaryTypeDef = TypedDict(
     "_RequiredJobSummaryTypeDef",
     {
         "createdAt": datetime,
         "device": str,
         "jobArn": str,
         "jobName": str,
@@ -307,26 +351,32 @@
         "endedAt": datetime,
         "startedAt": datetime,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class JobSummaryTypeDef(_RequiredJobSummaryTypeDef, _OptionalJobSummaryTypeDef):
     pass
 
-
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
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
@@ -350,20 +400,29 @@
     {
         "endedAt": datetime,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class QuantumTaskSummaryTypeDef(
     _RequiredQuantumTaskSummaryTypeDef, _OptionalQuantumTaskSummaryTypeDef
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
 
 SearchDevicesFilterTypeDef = TypedDict(
     "SearchDevicesFilterTypeDef",
     {
         "name": str,
         "values": Sequence[str],
     },
@@ -408,119 +467,45 @@
     {
         "containerImage": ContainerImageTypeDef,
         "scriptModeConfig": ScriptModeConfigTypeDef,
     },
     total=False,
 )
 
-CancelJobResponseTypeDef = TypedDict(
-    "CancelJobResponseTypeDef",
-    {
-        "cancellationStatus": CancellationStatusType,
-        "jobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelQuantumTaskResponseTypeDef = TypedDict(
-    "CancelQuantumTaskResponseTypeDef",
-    {
-        "cancellationStatus": CancellationStatusType,
-        "quantumTaskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResponseTypeDef = TypedDict(
-    "CreateJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateQuantumTaskResponseTypeDef = TypedDict(
-    "CreateQuantumTaskResponseTypeDef",
-    {
-        "quantumTaskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeviceResponseTypeDef = TypedDict(
-    "GetDeviceResponseTypeDef",
-    {
-        "deviceArn": str,
-        "deviceCapabilities": str,
-        "deviceName": str,
-        "deviceStatus": DeviceStatusType,
-        "deviceType": DeviceTypeType,
-        "providerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetQuantumTaskResponseTypeDef = TypedDict(
-    "GetQuantumTaskResponseTypeDef",
-    {
-        "createdAt": datetime,
-        "deviceArn": str,
-        "deviceParameters": str,
-        "endedAt": datetime,
-        "failureReason": str,
-        "jobArn": str,
-        "outputS3Bucket": str,
-        "outputS3Directory": str,
-        "quantumTaskArn": str,
-        "shots": int,
-        "status": QuantumTaskStatusType,
-        "tags": Dict[str, str],
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
 DataSourceTypeDef = TypedDict(
     "DataSourceTypeDef",
     {
         "s3DataSource": S3DataSourceTypeDef,
     },
 )
 
 SearchDevicesResponseTypeDef = TypedDict(
     "SearchDevicesResponseTypeDef",
     {
         "devices": List[DeviceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchJobsResponseTypeDef = TypedDict(
     "SearchJobsResponseTypeDef",
     {
         "jobs": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchQuantumTasksResponseTypeDef = TypedDict(
     "SearchQuantumTasksResponseTypeDef",
     {
         "nextToken": str,
         "quantumTasks": List[QuantumTaskSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchDevicesRequestRequestTypeDef = TypedDict(
     "_RequiredSearchDevicesRequestRequestTypeDef",
     {
         "filters": Sequence[SearchDevicesFilterTypeDef],
@@ -531,43 +516,39 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class SearchDevicesRequestRequestTypeDef(
     _RequiredSearchDevicesRequestRequestTypeDef, _OptionalSearchDevicesRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredSearchDevicesRequestSearchDevicesPaginateTypeDef = TypedDict(
     "_RequiredSearchDevicesRequestSearchDevicesPaginateTypeDef",
     {
         "filters": Sequence[SearchDevicesFilterTypeDef],
     },
 )
 _OptionalSearchDevicesRequestSearchDevicesPaginateTypeDef = TypedDict(
     "_OptionalSearchDevicesRequestSearchDevicesPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class SearchDevicesRequestSearchDevicesPaginateTypeDef(
     _RequiredSearchDevicesRequestSearchDevicesPaginateTypeDef,
     _OptionalSearchDevicesRequestSearchDevicesPaginateTypeDef,
 ):
     pass
 
-
 _RequiredSearchJobsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchJobsRequestRequestTypeDef",
     {
         "filters": Sequence[SearchJobsFilterTypeDef],
     },
 )
 _OptionalSearchJobsRequestRequestTypeDef = TypedDict(
@@ -575,43 +556,39 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class SearchJobsRequestRequestTypeDef(
     _RequiredSearchJobsRequestRequestTypeDef, _OptionalSearchJobsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredSearchJobsRequestSearchJobsPaginateTypeDef = TypedDict(
     "_RequiredSearchJobsRequestSearchJobsPaginateTypeDef",
     {
         "filters": Sequence[SearchJobsFilterTypeDef],
     },
 )
 _OptionalSearchJobsRequestSearchJobsPaginateTypeDef = TypedDict(
     "_OptionalSearchJobsRequestSearchJobsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class SearchJobsRequestSearchJobsPaginateTypeDef(
     _RequiredSearchJobsRequestSearchJobsPaginateTypeDef,
     _OptionalSearchJobsRequestSearchJobsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredSearchQuantumTasksRequestRequestTypeDef = TypedDict(
     "_RequiredSearchQuantumTasksRequestRequestTypeDef",
     {
         "filters": Sequence[SearchQuantumTasksFilterTypeDef],
     },
 )
 _OptionalSearchQuantumTasksRequestRequestTypeDef = TypedDict(
@@ -619,44 +596,40 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class SearchQuantumTasksRequestRequestTypeDef(
     _RequiredSearchQuantumTasksRequestRequestTypeDef,
     _OptionalSearchQuantumTasksRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef = TypedDict(
     "_RequiredSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef",
     {
         "filters": Sequence[SearchQuantumTasksFilterTypeDef],
     },
 )
 _OptionalSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef = TypedDict(
     "_OptionalSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class SearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef(
     _RequiredSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef,
     _OptionalSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef,
 ):
     pass
 
-
 _RequiredInputFileConfigTypeDef = TypedDict(
     "_RequiredInputFileConfigTypeDef",
     {
         "channelName": str,
         "dataSource": DataSourceTypeDef,
     },
 )
@@ -664,19 +637,17 @@
     "_OptionalInputFileConfigTypeDef",
     {
         "contentType": str,
     },
     total=False,
 )
 
-
 class InputFileConfigTypeDef(_RequiredInputFileConfigTypeDef, _OptionalInputFileConfigTypeDef):
     pass
 
-
 _RequiredCreateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobRequestRequestTypeDef",
     {
         "algorithmSpecification": AlgorithmSpecificationTypeDef,
         "clientToken": str,
         "deviceConfig": DeviceConfigTypeDef,
         "instanceConfig": InstanceConfigTypeDef,
@@ -693,21 +664,19 @@
         "inputDataConfig": Sequence[InputFileConfigTypeDef],
         "stoppingCondition": JobStoppingConditionTypeDef,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateJobRequestRequestTypeDef(
     _RequiredCreateJobRequestRequestTypeDef, _OptionalCreateJobRequestRequestTypeDef
 ):
     pass
 
-
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "algorithmSpecification": AlgorithmSpecificationTypeDef,
         "billableDuration": int,
         "checkpointConfig": JobCheckpointConfigTypeDef,
         "createdAt": datetime,
@@ -722,10 +691,10 @@
         "jobName": str,
         "outputDataConfig": JobOutputDataConfigTypeDef,
         "roleArn": str,
         "startedAt": datetime,
         "status": JobPrimaryStatusType,
         "stoppingCondition": JobStoppingConditionTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket/type_defs.pyi` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket/type_defs.py`

 * *Files 11% similar despite different names*

```diff
@@ -29,49 +29,50 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ContainerImageTypeDef",
     "ScriptModeConfigTypeDef",
     "CancelJobRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobResponseTypeDef",
     "CancelQuantumTaskRequestRequestTypeDef",
+    "CancelQuantumTaskResponseTypeDef",
     "DeviceConfigTypeDef",
     "InstanceConfigTypeDef",
     "JobCheckpointConfigTypeDef",
     "JobOutputDataConfigTypeDef",
     "JobStoppingConditionTypeDef",
+    "CreateJobResponseTypeDef",
     "CreateQuantumTaskRequestRequestTypeDef",
+    "CreateQuantumTaskResponseTypeDef",
     "S3DataSourceTypeDef",
     "DeviceSummaryTypeDef",
     "GetDeviceRequestRequestTypeDef",
+    "GetDeviceResponseTypeDef",
     "GetJobRequestRequestTypeDef",
     "JobEventDetailsTypeDef",
     "GetQuantumTaskRequestRequestTypeDef",
+    "GetQuantumTaskResponseTypeDef",
     "JobSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "PaginatorConfigTypeDef",
     "QuantumTaskSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchDevicesFilterTypeDef",
     "SearchJobsFilterTypeDef",
     "SearchQuantumTasksFilterTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AlgorithmSpecificationTypeDef",
-    "CancelJobResponseTypeDef",
-    "CancelQuantumTaskResponseTypeDef",
-    "CreateJobResponseTypeDef",
-    "CreateQuantumTaskResponseTypeDef",
-    "GetDeviceResponseTypeDef",
-    "GetQuantumTaskResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "DataSourceTypeDef",
     "SearchDevicesResponseTypeDef",
     "SearchJobsResponseTypeDef",
     "SearchQuantumTasksResponseTypeDef",
     "SearchDevicesRequestRequestTypeDef",
     "SearchDevicesRequestSearchDevicesPaginateTypeDef",
     "SearchJobsRequestRequestTypeDef",
@@ -101,43 +102,52 @@
     "_OptionalScriptModeConfigTypeDef",
     {
         "compressionType": CompressionTypeType,
     },
     total=False,
 )
 
+
 class ScriptModeConfigTypeDef(_RequiredScriptModeConfigTypeDef, _OptionalScriptModeConfigTypeDef):
     pass
 
+
 CancelJobRequestRequestTypeDef = TypedDict(
     "CancelJobRequestRequestTypeDef",
     {
         "jobArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJobResponseTypeDef = TypedDict(
+    "CancelJobResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "cancellationStatus": CancellationStatusType,
+        "jobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelQuantumTaskRequestRequestTypeDef = TypedDict(
     "CancelQuantumTaskRequestRequestTypeDef",
     {
         "clientToken": str,
         "quantumTaskArn": str,
     },
 )
 
+CancelQuantumTaskResponseTypeDef = TypedDict(
+    "CancelQuantumTaskResponseTypeDef",
+    {
+        "cancellationStatus": CancellationStatusType,
+        "quantumTaskArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeviceConfigTypeDef = TypedDict(
     "DeviceConfigTypeDef",
     {
         "device": str,
     },
 )
 
@@ -152,63 +162,77 @@
     "_OptionalInstanceConfigTypeDef",
     {
         "instanceCount": int,
     },
     total=False,
 )
 
+
 class InstanceConfigTypeDef(_RequiredInstanceConfigTypeDef, _OptionalInstanceConfigTypeDef):
     pass
 
+
 _RequiredJobCheckpointConfigTypeDef = TypedDict(
     "_RequiredJobCheckpointConfigTypeDef",
     {
         "s3Uri": str,
     },
 )
 _OptionalJobCheckpointConfigTypeDef = TypedDict(
     "_OptionalJobCheckpointConfigTypeDef",
     {
         "localPath": str,
     },
     total=False,
 )
 
+
 class JobCheckpointConfigTypeDef(
     _RequiredJobCheckpointConfigTypeDef, _OptionalJobCheckpointConfigTypeDef
 ):
     pass
 
+
 _RequiredJobOutputDataConfigTypeDef = TypedDict(
     "_RequiredJobOutputDataConfigTypeDef",
     {
         "s3Path": str,
     },
 )
 _OptionalJobOutputDataConfigTypeDef = TypedDict(
     "_OptionalJobOutputDataConfigTypeDef",
     {
         "kmsKeyId": str,
     },
     total=False,
 )
 
+
 class JobOutputDataConfigTypeDef(
     _RequiredJobOutputDataConfigTypeDef, _OptionalJobOutputDataConfigTypeDef
 ):
     pass
 
+
 JobStoppingConditionTypeDef = TypedDict(
     "JobStoppingConditionTypeDef",
     {
         "maxRuntimeInSeconds": int,
     },
     total=False,
 )
 
+CreateJobResponseTypeDef = TypedDict(
+    "CreateJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateQuantumTaskRequestRequestTypeDef = TypedDict(
     "_RequiredCreateQuantumTaskRequestRequestTypeDef",
     {
         "action": str,
         "clientToken": str,
         "deviceArn": str,
         "outputS3Bucket": str,
@@ -222,19 +246,29 @@
         "deviceParameters": str,
         "jobToken": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateQuantumTaskRequestRequestTypeDef(
     _RequiredCreateQuantumTaskRequestRequestTypeDef, _OptionalCreateQuantumTaskRequestRequestTypeDef
 ):
     pass
 
+
+CreateQuantumTaskResponseTypeDef = TypedDict(
+    "CreateQuantumTaskResponseTypeDef",
+    {
+        "quantumTaskArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3DataSourceTypeDef = TypedDict(
     "S3DataSourceTypeDef",
     {
         "s3Uri": str,
     },
 )
 
@@ -252,14 +286,27 @@
 GetDeviceRequestRequestTypeDef = TypedDict(
     "GetDeviceRequestRequestTypeDef",
     {
         "deviceArn": str,
     },
 )
 
+GetDeviceResponseTypeDef = TypedDict(
+    "GetDeviceResponseTypeDef",
+    {
+        "deviceArn": str,
+        "deviceCapabilities": str,
+        "deviceName": str,
+        "deviceStatus": DeviceStatusType,
+        "deviceType": DeviceTypeType,
+        "providerName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobRequestRequestTypeDef = TypedDict(
     "GetJobRequestRequestTypeDef",
     {
         "jobArn": str,
     },
 )
 
@@ -276,14 +323,33 @@
 GetQuantumTaskRequestRequestTypeDef = TypedDict(
     "GetQuantumTaskRequestRequestTypeDef",
     {
         "quantumTaskArn": str,
     },
 )
 
+GetQuantumTaskResponseTypeDef = TypedDict(
+    "GetQuantumTaskResponseTypeDef",
+    {
+        "createdAt": datetime,
+        "deviceArn": str,
+        "deviceParameters": str,
+        "endedAt": datetime,
+        "failureReason": str,
+        "jobArn": str,
+        "outputS3Bucket": str,
+        "outputS3Directory": str,
+        "quantumTaskArn": str,
+        "shots": int,
+        "status": QuantumTaskStatusType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredJobSummaryTypeDef = TypedDict(
     "_RequiredJobSummaryTypeDef",
     {
         "createdAt": datetime,
         "device": str,
         "jobArn": str,
         "jobName": str,
@@ -296,24 +362,34 @@
         "endedAt": datetime,
         "startedAt": datetime,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class JobSummaryTypeDef(_RequiredJobSummaryTypeDef, _OptionalJobSummaryTypeDef):
     pass
 
+
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
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
@@ -337,19 +413,32 @@
     {
         "endedAt": datetime,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class QuantumTaskSummaryTypeDef(
     _RequiredQuantumTaskSummaryTypeDef, _OptionalQuantumTaskSummaryTypeDef
 ):
     pass
 
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
 SearchDevicesFilterTypeDef = TypedDict(
     "SearchDevicesFilterTypeDef",
     {
         "name": str,
         "values": Sequence[str],
     },
 )
@@ -393,119 +482,45 @@
     {
         "containerImage": ContainerImageTypeDef,
         "scriptModeConfig": ScriptModeConfigTypeDef,
     },
     total=False,
 )
 
-CancelJobResponseTypeDef = TypedDict(
-    "CancelJobResponseTypeDef",
-    {
-        "cancellationStatus": CancellationStatusType,
-        "jobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelQuantumTaskResponseTypeDef = TypedDict(
-    "CancelQuantumTaskResponseTypeDef",
-    {
-        "cancellationStatus": CancellationStatusType,
-        "quantumTaskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResponseTypeDef = TypedDict(
-    "CreateJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateQuantumTaskResponseTypeDef = TypedDict(
-    "CreateQuantumTaskResponseTypeDef",
-    {
-        "quantumTaskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeviceResponseTypeDef = TypedDict(
-    "GetDeviceResponseTypeDef",
-    {
-        "deviceArn": str,
-        "deviceCapabilities": str,
-        "deviceName": str,
-        "deviceStatus": DeviceStatusType,
-        "deviceType": DeviceTypeType,
-        "providerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetQuantumTaskResponseTypeDef = TypedDict(
-    "GetQuantumTaskResponseTypeDef",
-    {
-        "createdAt": datetime,
-        "deviceArn": str,
-        "deviceParameters": str,
-        "endedAt": datetime,
-        "failureReason": str,
-        "jobArn": str,
-        "outputS3Bucket": str,
-        "outputS3Directory": str,
-        "quantumTaskArn": str,
-        "shots": int,
-        "status": QuantumTaskStatusType,
-        "tags": Dict[str, str],
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
 DataSourceTypeDef = TypedDict(
     "DataSourceTypeDef",
     {
         "s3DataSource": S3DataSourceTypeDef,
     },
 )
 
 SearchDevicesResponseTypeDef = TypedDict(
     "SearchDevicesResponseTypeDef",
     {
         "devices": List[DeviceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchJobsResponseTypeDef = TypedDict(
     "SearchJobsResponseTypeDef",
     {
         "jobs": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchQuantumTasksResponseTypeDef = TypedDict(
     "SearchQuantumTasksResponseTypeDef",
     {
         "nextToken": str,
         "quantumTasks": List[QuantumTaskSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchDevicesRequestRequestTypeDef = TypedDict(
     "_RequiredSearchDevicesRequestRequestTypeDef",
     {
         "filters": Sequence[SearchDevicesFilterTypeDef],
@@ -516,39 +531,43 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class SearchDevicesRequestRequestTypeDef(
     _RequiredSearchDevicesRequestRequestTypeDef, _OptionalSearchDevicesRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredSearchDevicesRequestSearchDevicesPaginateTypeDef = TypedDict(
     "_RequiredSearchDevicesRequestSearchDevicesPaginateTypeDef",
     {
         "filters": Sequence[SearchDevicesFilterTypeDef],
     },
 )
 _OptionalSearchDevicesRequestSearchDevicesPaginateTypeDef = TypedDict(
     "_OptionalSearchDevicesRequestSearchDevicesPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class SearchDevicesRequestSearchDevicesPaginateTypeDef(
     _RequiredSearchDevicesRequestSearchDevicesPaginateTypeDef,
     _OptionalSearchDevicesRequestSearchDevicesPaginateTypeDef,
 ):
     pass
 
+
 _RequiredSearchJobsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchJobsRequestRequestTypeDef",
     {
         "filters": Sequence[SearchJobsFilterTypeDef],
     },
 )
 _OptionalSearchJobsRequestRequestTypeDef = TypedDict(
@@ -556,39 +575,43 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class SearchJobsRequestRequestTypeDef(
     _RequiredSearchJobsRequestRequestTypeDef, _OptionalSearchJobsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredSearchJobsRequestSearchJobsPaginateTypeDef = TypedDict(
     "_RequiredSearchJobsRequestSearchJobsPaginateTypeDef",
     {
         "filters": Sequence[SearchJobsFilterTypeDef],
     },
 )
 _OptionalSearchJobsRequestSearchJobsPaginateTypeDef = TypedDict(
     "_OptionalSearchJobsRequestSearchJobsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class SearchJobsRequestSearchJobsPaginateTypeDef(
     _RequiredSearchJobsRequestSearchJobsPaginateTypeDef,
     _OptionalSearchJobsRequestSearchJobsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredSearchQuantumTasksRequestRequestTypeDef = TypedDict(
     "_RequiredSearchQuantumTasksRequestRequestTypeDef",
     {
         "filters": Sequence[SearchQuantumTasksFilterTypeDef],
     },
 )
 _OptionalSearchQuantumTasksRequestRequestTypeDef = TypedDict(
@@ -596,40 +619,44 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class SearchQuantumTasksRequestRequestTypeDef(
     _RequiredSearchQuantumTasksRequestRequestTypeDef,
     _OptionalSearchQuantumTasksRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef = TypedDict(
     "_RequiredSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef",
     {
         "filters": Sequence[SearchQuantumTasksFilterTypeDef],
     },
 )
 _OptionalSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef = TypedDict(
     "_OptionalSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class SearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef(
     _RequiredSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef,
     _OptionalSearchQuantumTasksRequestSearchQuantumTasksPaginateTypeDef,
 ):
     pass
 
+
 _RequiredInputFileConfigTypeDef = TypedDict(
     "_RequiredInputFileConfigTypeDef",
     {
         "channelName": str,
         "dataSource": DataSourceTypeDef,
     },
 )
@@ -637,17 +664,19 @@
     "_OptionalInputFileConfigTypeDef",
     {
         "contentType": str,
     },
     total=False,
 )
 
+
 class InputFileConfigTypeDef(_RequiredInputFileConfigTypeDef, _OptionalInputFileConfigTypeDef):
     pass
 
+
 _RequiredCreateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobRequestRequestTypeDef",
     {
         "algorithmSpecification": AlgorithmSpecificationTypeDef,
         "clientToken": str,
         "deviceConfig": DeviceConfigTypeDef,
         "instanceConfig": InstanceConfigTypeDef,
@@ -664,19 +693,21 @@
         "inputDataConfig": Sequence[InputFileConfigTypeDef],
         "stoppingCondition": JobStoppingConditionTypeDef,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateJobRequestRequestTypeDef(
     _RequiredCreateJobRequestRequestTypeDef, _OptionalCreateJobRequestRequestTypeDef
 ):
     pass
 
+
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "algorithmSpecification": AlgorithmSpecificationTypeDef,
         "billableDuration": int,
         "checkpointConfig": JobCheckpointConfigTypeDef,
         "createdAt": datetime,
@@ -691,10 +722,10 @@
         "jobName": str,
         "outputDataConfig": JobOutputDataConfigTypeDef,
         "roleArn": str,
         "startedAt": datetime,
         "status": JobPrimaryStatusType,
         "stoppingCondition": JobStoppingConditionTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/PKG-INFO` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-braket
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Braket 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Braket 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-braket"></a>
 
 # types-aiobotocore-braket
 
 [![PyPI - types-aiobotocore-braket](https://img.shields.io/pypi/v/types-aiobotocore-braket.svg?color=blue)](https://pypi.org/project/types-aiobotocore-braket)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-braket.svg?color=blue)](https://pypi.org/project/types-aiobotocore-braket)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-braket?color=blue)](https://pypistats.org/packages/types-aiobotocore-braket)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Braket 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket)
+[aiobotocore.Braket 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/braket.html#Braket)
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
 [types-aiobotocore-braket docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_braket/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,45 +336,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_braket.type_defs import (
     ContainerImageTypeDef,
     ScriptModeConfigTypeDef,
     CancelJobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobResponseTypeDef,
     CancelQuantumTaskRequestRequestTypeDef,
+    CancelQuantumTaskResponseTypeDef,
     DeviceConfigTypeDef,
     InstanceConfigTypeDef,
     JobCheckpointConfigTypeDef,
     JobOutputDataConfigTypeDef,
     JobStoppingConditionTypeDef,
+    CreateJobResponseTypeDef,
     CreateQuantumTaskRequestRequestTypeDef,
+    CreateQuantumTaskResponseTypeDef,
     S3DataSourceTypeDef,
     DeviceSummaryTypeDef,
     GetDeviceRequestRequestTypeDef,
+    GetDeviceResponseTypeDef,
     GetJobRequestRequestTypeDef,
     JobEventDetailsTypeDef,
     GetQuantumTaskRequestRequestTypeDef,
+    GetQuantumTaskResponseTypeDef,
     JobSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     QuantumTaskSummaryTypeDef,
+    ResponseMetadataTypeDef,
     SearchDevicesFilterTypeDef,
     SearchJobsFilterTypeDef,
     SearchQuantumTasksFilterTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AlgorithmSpecificationTypeDef,
-    CancelJobResponseTypeDef,
-    CancelQuantumTaskResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateQuantumTaskResponseTypeDef,
-    GetDeviceResponseTypeDef,
-    GetQuantumTaskResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     DataSourceTypeDef,
     SearchDevicesResponseTypeDef,
     SearchJobsResponseTypeDef,
     SearchQuantumTasksResponseTypeDef,
     SearchDevicesRequestRequestTypeDef,
     SearchDevicesRequestSearchDevicesPaginateTypeDef,
     SearchJobsRequestRequestTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-braket-2.5.0.post1/types_aiobotocore_braket.egg-info/SOURCES.txt` & `types-aiobotocore-braket-2.5.1/types_aiobotocore_braket.egg-info/SOURCES.txt`

 * *Files identical despite different names*

