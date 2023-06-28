# Comparing `tmp/types-aiobotocore-iot-jobs-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iot-jobs-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iot-jobs-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:45 2023, max compression
+gzip compressed data, was "types-aiobotocore-iot-jobs-data-2.5.1.tar", last modified: Wed Jun 28 01:43:37 2023, max compression
```

## Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1.tar` & `types-aiobotocore-iot-jobs-data-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:45.167281 types-aiobotocore-iot-jobs-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12878 2023-03-11 12:26:45.163282 types-aiobotocore-iot-jobs-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11280 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:45.167281 types-aiobotocore-iot-jobs-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2169 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:45.159281 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/
--rw-r--r--   0 runner    (1001) docker     (123)      505 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      504 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7414 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7402 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7904 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7902 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5355 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5348 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:10.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:45.163282 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12878 2023-03-11 12:26:44.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-03-11 12:26:45.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:44.000000 types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:37.558152 types-aiobotocore-iot-jobs-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12876 2023-06-28 01:43:37.558152 types-aiobotocore-iot-jobs-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11284 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:37.558152 types-aiobotocore-iot-jobs-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2163 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:37.558152 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/
+-rw-r--r--   0 runner    (1001) docker     (123)      505 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7414 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7402 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8113 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8111 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5363 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5356 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:48.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:37.558152 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12876 2023-06-28 01:43:37.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 01:43:37.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:37.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:37.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:37.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:37.000000 types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/LICENSE` & `types-aiobotocore-iot-jobs-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iot-jobs-data-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot-jobs-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTJobsDataPlane 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTJobsDataPlane 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot-jobs-data"></a>
 
 # types-aiobotocore-iot-jobs-data
 
 [![PyPI - types-aiobotocore-iot-jobs-data](https://img.shields.io/pypi/v/types-aiobotocore-iot-jobs-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-jobs-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-jobs-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-jobs-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-jobs-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-jobs-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTJobsDataPlane 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane)
+[aiobotocore.IoTJobsDataPlane 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane)
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
 [types-aiobotocore-iot-jobs-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,18 +292,18 @@
 `types_aiobotocore_iot_jobs_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_jobs_data.type_defs import (
     DescribeJobExecutionRequestRequestTypeDef,
     JobExecutionTypeDef,
-    ResponseMetadataTypeDef,
     GetPendingJobExecutionsRequestRequestTypeDef,
     JobExecutionSummaryTypeDef,
     JobExecutionStateTypeDef,
+    ResponseMetadataTypeDef,
     StartNextPendingJobExecutionRequestRequestTypeDef,
     UpdateJobExecutionRequestRequestTypeDef,
     DescribeJobExecutionResponseTypeDef,
     StartNextPendingJobExecutionResponseTypeDef,
     GetPendingJobExecutionsResponseTypeDef,
     UpdateJobExecutionResponseTypeDef,
 )
@@ -316,43 +316,43 @@
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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/README.md` & `types-aiobotocore-iot-jobs-data-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iot-jobs-data"></a>
 
 # types-aiobotocore-iot-jobs-data
 
 [![PyPI - types-aiobotocore-iot-jobs-data](https://img.shields.io/pypi/v/types-aiobotocore-iot-jobs-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-jobs-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-jobs-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-jobs-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-jobs-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-jobs-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTJobsDataPlane 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane)
+[aiobotocore.IoTJobsDataPlane 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane)
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
 [types-aiobotocore-iot-jobs-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -259,18 +259,18 @@
 `types_aiobotocore_iot_jobs_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_jobs_data.type_defs import (
     DescribeJobExecutionRequestRequestTypeDef,
     JobExecutionTypeDef,
-    ResponseMetadataTypeDef,
     GetPendingJobExecutionsRequestRequestTypeDef,
     JobExecutionSummaryTypeDef,
     JobExecutionStateTypeDef,
+    ResponseMetadataTypeDef,
     StartNextPendingJobExecutionRequestRequestTypeDef,
     UpdateJobExecutionRequestRequestTypeDef,
     DescribeJobExecutionResponseTypeDef,
     StartNextPendingJobExecutionResponseTypeDef,
     GetPendingJobExecutionsResponseTypeDef,
     UpdateJobExecutionResponseTypeDef,
 )
@@ -283,43 +283,43 @@
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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/setup.py` & `types-aiobotocore-iot-jobs-data-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iot-jobs-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iot-jobs-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iot_jobs_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTJobsDataPlane 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTJobsDataPlane 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/"
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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/__main__.py` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTJobsDataPlane 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTJobsDataPlane 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane\nOther"
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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/client.py` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/client.pyi` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/literals.py` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/literals.py`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/literals.pyi` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/literals.pyi`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/type_defs.py` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -21,18 +21,18 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DescribeJobExecutionRequestRequestTypeDef",
     "JobExecutionTypeDef",
-    "ResponseMetadataTypeDef",
     "GetPendingJobExecutionsRequestRequestTypeDef",
     "JobExecutionSummaryTypeDef",
     "JobExecutionStateTypeDef",
+    "ResponseMetadataTypeDef",
     "StartNextPendingJobExecutionRequestRequestTypeDef",
     "UpdateJobExecutionRequestRequestTypeDef",
     "DescribeJobExecutionResponseTypeDef",
     "StartNextPendingJobExecutionResponseTypeDef",
     "GetPendingJobExecutionsResponseTypeDef",
     "UpdateJobExecutionResponseTypeDef",
 )
@@ -75,25 +75,14 @@
         "versionNumber": int,
         "executionNumber": int,
         "jobDocument": str,
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
 GetPendingJobExecutionsRequestRequestTypeDef = TypedDict(
     "GetPendingJobExecutionsRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 
@@ -116,14 +105,25 @@
         "status": JobExecutionStatusType,
         "statusDetails": Dict[str, str],
         "versionNumber": int,
     },
     total=False,
 )
 
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
 _RequiredStartNextPendingJobExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredStartNextPendingJobExecutionRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalStartNextPendingJobExecutionRequestRequestTypeDef = TypedDict(
@@ -172,36 +172,36 @@
     pass
 
 
 DescribeJobExecutionResponseTypeDef = TypedDict(
     "DescribeJobExecutionResponseTypeDef",
     {
         "execution": JobExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartNextPendingJobExecutionResponseTypeDef = TypedDict(
     "StartNextPendingJobExecutionResponseTypeDef",
     {
         "execution": JobExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPendingJobExecutionsResponseTypeDef = TypedDict(
     "GetPendingJobExecutionsResponseTypeDef",
     {
         "inProgressJobs": List[JobExecutionSummaryTypeDef],
         "queuedJobs": List[JobExecutionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobExecutionResponseTypeDef = TypedDict(
     "UpdateJobExecutionResponseTypeDef",
     {
         "executionState": JobExecutionStateTypeDef,
         "jobDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data/type_defs.pyi` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -20,18 +20,18 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DescribeJobExecutionRequestRequestTypeDef",
     "JobExecutionTypeDef",
-    "ResponseMetadataTypeDef",
     "GetPendingJobExecutionsRequestRequestTypeDef",
     "JobExecutionSummaryTypeDef",
     "JobExecutionStateTypeDef",
+    "ResponseMetadataTypeDef",
     "StartNextPendingJobExecutionRequestRequestTypeDef",
     "UpdateJobExecutionRequestRequestTypeDef",
     "DescribeJobExecutionResponseTypeDef",
     "StartNextPendingJobExecutionResponseTypeDef",
     "GetPendingJobExecutionsResponseTypeDef",
     "UpdateJobExecutionResponseTypeDef",
 )
@@ -72,25 +72,14 @@
         "versionNumber": int,
         "executionNumber": int,
         "jobDocument": str,
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
 GetPendingJobExecutionsRequestRequestTypeDef = TypedDict(
     "GetPendingJobExecutionsRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 
@@ -113,14 +102,25 @@
         "status": JobExecutionStatusType,
         "statusDetails": Dict[str, str],
         "versionNumber": int,
     },
     total=False,
 )
 
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
 _RequiredStartNextPendingJobExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredStartNextPendingJobExecutionRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalStartNextPendingJobExecutionRequestRequestTypeDef = TypedDict(
@@ -165,36 +165,36 @@
 ):
     pass
 
 DescribeJobExecutionResponseTypeDef = TypedDict(
     "DescribeJobExecutionResponseTypeDef",
     {
         "execution": JobExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartNextPendingJobExecutionResponseTypeDef = TypedDict(
     "StartNextPendingJobExecutionResponseTypeDef",
     {
         "execution": JobExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPendingJobExecutionsResponseTypeDef = TypedDict(
     "GetPendingJobExecutionsResponseTypeDef",
     {
         "inProgressJobs": List[JobExecutionSummaryTypeDef],
         "queuedJobs": List[JobExecutionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobExecutionResponseTypeDef = TypedDict(
     "UpdateJobExecutionResponseTypeDef",
     {
         "executionState": JobExecutionStateTypeDef,
         "jobDocument": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/PKG-INFO` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot-jobs-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTJobsDataPlane 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTJobsDataPlane 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot-jobs-data"></a>
 
 # types-aiobotocore-iot-jobs-data
 
 [![PyPI - types-aiobotocore-iot-jobs-data](https://img.shields.io/pypi/v/types-aiobotocore-iot-jobs-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-jobs-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-jobs-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-jobs-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-jobs-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-jobs-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTJobsDataPlane 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane)
+[aiobotocore.IoTJobsDataPlane 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-jobs-data.html#IoTJobsDataPlane)
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
 [types-aiobotocore-iot-jobs-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_jobs_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,18 +292,18 @@
 `types_aiobotocore_iot_jobs_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_jobs_data.type_defs import (
     DescribeJobExecutionRequestRequestTypeDef,
     JobExecutionTypeDef,
-    ResponseMetadataTypeDef,
     GetPendingJobExecutionsRequestRequestTypeDef,
     JobExecutionSummaryTypeDef,
     JobExecutionStateTypeDef,
+    ResponseMetadataTypeDef,
     StartNextPendingJobExecutionRequestRequestTypeDef,
     UpdateJobExecutionRequestRequestTypeDef,
     DescribeJobExecutionResponseTypeDef,
     StartNextPendingJobExecutionResponseTypeDef,
     GetPendingJobExecutionsResponseTypeDef,
     UpdateJobExecutionResponseTypeDef,
 )
@@ -316,43 +316,43 @@
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

### Comparing `types-aiobotocore-iot-jobs-data-2.5.0.post1/types_aiobotocore_iot_jobs_data.egg-info/SOURCES.txt` & `types-aiobotocore-iot-jobs-data-2.5.1/types_aiobotocore_iot_jobs_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

