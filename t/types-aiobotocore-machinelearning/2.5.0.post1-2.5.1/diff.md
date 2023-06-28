# Comparing `tmp/types-aiobotocore-machinelearning-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-machinelearning-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-machinelearning-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-machinelearning-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-machinelearning-2.5.0.post1.tar` & `types-aiobotocore-machinelearning-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.359393 types-aiobotocore-machinelearning-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18759 2023-03-11 12:26:56.355393 types-aiobotocore-machinelearning-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17156 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.359393 types-aiobotocore-machinelearning-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.351393 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/
--rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2293 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    28052 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    28007 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10078 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10076 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7103 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7096 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    31655 2023-03-11 12:17:59.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    31630 2023-03-11 12:17:59.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     6335 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     6331 2023-03-11 12:17:58.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.355393 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18759 2023-03-11 12:26:56.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-03-11 12:26:56.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:56.000000 types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.570170 types-aiobotocore-machinelearning-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18759 2023-06-28 01:43:47.566171 types-aiobotocore-machinelearning-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17162 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.570170 types-aiobotocore-machinelearning-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2174 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.566171 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/
+-rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2293 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28039 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27994 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10287 2023-06-28 01:34:40.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10285 2023-06-28 01:34:40.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6991 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6985 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    31719 2023-06-28 01:34:40.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31694 2023-06-28 01:34:40.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6335 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6331 2023-06-28 01:34:39.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.566171 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18759 2023-06-28 01:43:47.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-06-28 01:43:47.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:47.000000 types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/LICENSE` & `types-aiobotocore-machinelearning-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/PKG-INFO` & `types-aiobotocore-machinelearning-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-machinelearning
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MachineLearning 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MachineLearning 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-machinelearning"></a>
 
 # types-aiobotocore-machinelearning
 
 [![PyPI - types-aiobotocore-machinelearning](https://img.shields.io/pypi/v/types-aiobotocore-machinelearning.svg?color=blue)](https://pypi.org/project/types-aiobotocore-machinelearning)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-machinelearning.svg?color=blue)](https://pypi.org/project/types-aiobotocore-machinelearning)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-machinelearning?color=blue)](https://pypistats.org/packages/types-aiobotocore-machinelearning)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MachineLearning 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning)
+[aiobotocore.MachineLearning 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning)
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
 [types-aiobotocore-machinelearning docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/).
 
 See how it helps to find and fix potential bugs:
 
@@ -387,83 +387,83 @@
 
 `types_aiobotocore_machinelearning.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_machinelearning.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AddTagsOutputTypeDef,
     BatchPredictionTypeDef,
     CreateBatchPredictionInputRequestTypeDef,
+    CreateBatchPredictionOutputTypeDef,
+    CreateDataSourceFromRDSOutputTypeDef,
+    CreateDataSourceFromRedshiftOutputTypeDef,
     S3DataSpecTypeDef,
+    CreateDataSourceFromS3OutputTypeDef,
     CreateEvaluationInputRequestTypeDef,
+    CreateEvaluationOutputTypeDef,
     CreateMLModelInputRequestTypeDef,
+    CreateMLModelOutputTypeDef,
     CreateRealtimeEndpointInputRequestTypeDef,
     RealtimeEndpointInfoTypeDef,
     DeleteBatchPredictionInputRequestTypeDef,
+    DeleteBatchPredictionOutputTypeDef,
     DeleteDataSourceInputRequestTypeDef,
+    DeleteDataSourceOutputTypeDef,
     DeleteEvaluationInputRequestTypeDef,
+    DeleteEvaluationOutputTypeDef,
     DeleteMLModelInputRequestTypeDef,
+    DeleteMLModelOutputTypeDef,
     DeleteRealtimeEndpointInputRequestTypeDef,
     DeleteTagsInputRequestTypeDef,
+    DeleteTagsOutputTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef,
     DescribeBatchPredictionsInputRequestTypeDef,
+    DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef,
     DescribeDataSourcesInputRequestTypeDef,
+    DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef,
     DescribeEvaluationsInputRequestTypeDef,
+    DescribeMLModelsInputDescribeMLModelsPaginateTypeDef,
     DescribeMLModelsInputRequestTypeDef,
     DescribeTagsInputRequestTypeDef,
     PerformanceMetricsTypeDef,
     GetBatchPredictionInputRequestTypeDef,
+    GetBatchPredictionOutputTypeDef,
     GetDataSourceInputRequestTypeDef,
     GetEvaluationInputRequestTypeDef,
     GetMLModelInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredictInputRequestTypeDef,
     PredictionTypeDef,
     RDSDatabaseCredentialsTypeDef,
     RDSDatabaseTypeDef,
     RedshiftDatabaseCredentialsTypeDef,
     RedshiftDatabaseTypeDef,
+    ResponseMetadataTypeDef,
     UpdateBatchPredictionInputRequestTypeDef,
+    UpdateBatchPredictionOutputTypeDef,
     UpdateDataSourceInputRequestTypeDef,
+    UpdateDataSourceOutputTypeDef,
     UpdateEvaluationInputRequestTypeDef,
+    UpdateEvaluationOutputTypeDef,
     UpdateMLModelInputRequestTypeDef,
+    UpdateMLModelOutputTypeDef,
     AddTagsInputRequestTypeDef,
-    AddTagsOutputTypeDef,
-    CreateBatchPredictionOutputTypeDef,
-    CreateDataSourceFromRDSOutputTypeDef,
-    CreateDataSourceFromRedshiftOutputTypeDef,
-    CreateDataSourceFromS3OutputTypeDef,
-    CreateEvaluationOutputTypeDef,
-    CreateMLModelOutputTypeDef,
-    DeleteBatchPredictionOutputTypeDef,
-    DeleteDataSourceOutputTypeDef,
-    DeleteEvaluationOutputTypeDef,
-    DeleteMLModelOutputTypeDef,
-    DeleteTagsOutputTypeDef,
     DescribeTagsOutputTypeDef,
-    GetBatchPredictionOutputTypeDef,
-    UpdateBatchPredictionOutputTypeDef,
-    UpdateDataSourceOutputTypeDef,
-    UpdateEvaluationOutputTypeDef,
-    UpdateMLModelOutputTypeDef,
     DescribeBatchPredictionsOutputTypeDef,
     CreateDataSourceFromS3InputRequestTypeDef,
     CreateRealtimeEndpointOutputTypeDef,
     DeleteRealtimeEndpointOutputTypeDef,
     GetMLModelOutputTypeDef,
     MLModelTypeDef,
     DescribeBatchPredictionsInputBatchPredictionAvailableWaitTypeDef,
     DescribeDataSourcesInputDataSourceAvailableWaitTypeDef,
     DescribeEvaluationsInputEvaluationAvailableWaitTypeDef,
     DescribeMLModelsInputMLModelAvailableWaitTypeDef,
-    DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef,
-    DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef,
-    DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef,
-    DescribeMLModelsInputDescribeMLModelsPaginateTypeDef,
     EvaluationTypeDef,
     GetEvaluationOutputTypeDef,
     PredictOutputTypeDef,
     RDSDataSpecTypeDef,
     RDSMetadataTypeDef,
     RedshiftDataSpecTypeDef,
     RedshiftMetadataTypeDef,
@@ -484,43 +484,43 @@
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/README.md` & `types-aiobotocore-machinelearning-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-machinelearning"></a>
 
 # types-aiobotocore-machinelearning
 
 [![PyPI - types-aiobotocore-machinelearning](https://img.shields.io/pypi/v/types-aiobotocore-machinelearning.svg?color=blue)](https://pypi.org/project/types-aiobotocore-machinelearning)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-machinelearning.svg?color=blue)](https://pypi.org/project/types-aiobotocore-machinelearning)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-machinelearning?color=blue)](https://pypistats.org/packages/types-aiobotocore-machinelearning)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MachineLearning 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning)
+[aiobotocore.MachineLearning 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning)
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
 [types-aiobotocore-machinelearning docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/).
 
 See how it helps to find and fix potential bugs:
 
@@ -354,83 +354,83 @@
 
 `types_aiobotocore_machinelearning.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_machinelearning.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AddTagsOutputTypeDef,
     BatchPredictionTypeDef,
     CreateBatchPredictionInputRequestTypeDef,
+    CreateBatchPredictionOutputTypeDef,
+    CreateDataSourceFromRDSOutputTypeDef,
+    CreateDataSourceFromRedshiftOutputTypeDef,
     S3DataSpecTypeDef,
+    CreateDataSourceFromS3OutputTypeDef,
     CreateEvaluationInputRequestTypeDef,
+    CreateEvaluationOutputTypeDef,
     CreateMLModelInputRequestTypeDef,
+    CreateMLModelOutputTypeDef,
     CreateRealtimeEndpointInputRequestTypeDef,
     RealtimeEndpointInfoTypeDef,
     DeleteBatchPredictionInputRequestTypeDef,
+    DeleteBatchPredictionOutputTypeDef,
     DeleteDataSourceInputRequestTypeDef,
+    DeleteDataSourceOutputTypeDef,
     DeleteEvaluationInputRequestTypeDef,
+    DeleteEvaluationOutputTypeDef,
     DeleteMLModelInputRequestTypeDef,
+    DeleteMLModelOutputTypeDef,
     DeleteRealtimeEndpointInputRequestTypeDef,
     DeleteTagsInputRequestTypeDef,
+    DeleteTagsOutputTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef,
     DescribeBatchPredictionsInputRequestTypeDef,
+    DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef,
     DescribeDataSourcesInputRequestTypeDef,
+    DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef,
     DescribeEvaluationsInputRequestTypeDef,
+    DescribeMLModelsInputDescribeMLModelsPaginateTypeDef,
     DescribeMLModelsInputRequestTypeDef,
     DescribeTagsInputRequestTypeDef,
     PerformanceMetricsTypeDef,
     GetBatchPredictionInputRequestTypeDef,
+    GetBatchPredictionOutputTypeDef,
     GetDataSourceInputRequestTypeDef,
     GetEvaluationInputRequestTypeDef,
     GetMLModelInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredictInputRequestTypeDef,
     PredictionTypeDef,
     RDSDatabaseCredentialsTypeDef,
     RDSDatabaseTypeDef,
     RedshiftDatabaseCredentialsTypeDef,
     RedshiftDatabaseTypeDef,
+    ResponseMetadataTypeDef,
     UpdateBatchPredictionInputRequestTypeDef,
+    UpdateBatchPredictionOutputTypeDef,
     UpdateDataSourceInputRequestTypeDef,
+    UpdateDataSourceOutputTypeDef,
     UpdateEvaluationInputRequestTypeDef,
+    UpdateEvaluationOutputTypeDef,
     UpdateMLModelInputRequestTypeDef,
+    UpdateMLModelOutputTypeDef,
     AddTagsInputRequestTypeDef,
-    AddTagsOutputTypeDef,
-    CreateBatchPredictionOutputTypeDef,
-    CreateDataSourceFromRDSOutputTypeDef,
-    CreateDataSourceFromRedshiftOutputTypeDef,
-    CreateDataSourceFromS3OutputTypeDef,
-    CreateEvaluationOutputTypeDef,
-    CreateMLModelOutputTypeDef,
-    DeleteBatchPredictionOutputTypeDef,
-    DeleteDataSourceOutputTypeDef,
-    DeleteEvaluationOutputTypeDef,
-    DeleteMLModelOutputTypeDef,
-    DeleteTagsOutputTypeDef,
     DescribeTagsOutputTypeDef,
-    GetBatchPredictionOutputTypeDef,
-    UpdateBatchPredictionOutputTypeDef,
-    UpdateDataSourceOutputTypeDef,
-    UpdateEvaluationOutputTypeDef,
-    UpdateMLModelOutputTypeDef,
     DescribeBatchPredictionsOutputTypeDef,
     CreateDataSourceFromS3InputRequestTypeDef,
     CreateRealtimeEndpointOutputTypeDef,
     DeleteRealtimeEndpointOutputTypeDef,
     GetMLModelOutputTypeDef,
     MLModelTypeDef,
     DescribeBatchPredictionsInputBatchPredictionAvailableWaitTypeDef,
     DescribeDataSourcesInputDataSourceAvailableWaitTypeDef,
     DescribeEvaluationsInputEvaluationAvailableWaitTypeDef,
     DescribeMLModelsInputMLModelAvailableWaitTypeDef,
-    DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef,
-    DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef,
-    DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef,
-    DescribeMLModelsInputDescribeMLModelsPaginateTypeDef,
     EvaluationTypeDef,
     GetEvaluationOutputTypeDef,
     PredictOutputTypeDef,
     RDSDataSpecTypeDef,
     RDSMetadataTypeDef,
     RedshiftDataSpecTypeDef,
     RedshiftMetadataTypeDef,
@@ -451,43 +451,43 @@
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/setup.py` & `types-aiobotocore-machinelearning-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-machinelearning.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-machinelearning",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_machinelearning"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MachineLearning 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MachineLearning 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/"
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/__init__.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/__init__.pyi` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/__main__.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MachineLearning 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MachineLearning 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning\nOther"
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/client.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -256,49 +256,49 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#create_realtime_endpoint)
         """
 
     async def delete_batch_prediction(
         self, *, BatchPredictionId: str
     ) -> DeleteBatchPredictionOutputTypeDef:
         """
-        Assigns the DELETED status to a `BatchPrediction` , rendering it unusable.
+        Assigns the DELETED status to a `BatchPrediction`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_batch_prediction)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_batch_prediction)
         """
 
     async def delete_data_source(self, *, DataSourceId: str) -> DeleteDataSourceOutputTypeDef:
         """
-        Assigns the DELETED status to a `DataSource` , rendering it unusable.
+        Assigns the DELETED status to a `DataSource`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_data_source)
         """
 
     async def delete_evaluation(self, *, EvaluationId: str) -> DeleteEvaluationOutputTypeDef:
         """
-        Assigns the `DELETED` status to an `Evaluation` , rendering it unusable.
+        Assigns the `DELETED` status to an `Evaluation`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_evaluation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_evaluation)
         """
 
     async def delete_ml_model(self, *, MLModelId: str) -> DeleteMLModelOutputTypeDef:
         """
-        Assigns the `DELETED` status to an `MLModel` , rendering it unusable.
+        Assigns the `DELETED` status to an `MLModel`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_ml_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_ml_model)
         """
 
     async def delete_realtime_endpoint(
         self, *, MLModelId: str
     ) -> DeleteRealtimeEndpointOutputTypeDef:
         """
-        Deletes a real time endpoint of an `MLModel` .
+        Deletes a real time endpoint of an `MLModel`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_realtime_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_realtime_endpoint)
         """
 
     async def delete_tags(
         self, *, TagKeys: Sequence[str], ResourceId: str, ResourceType: TaggableResourceTypeType
@@ -436,83 +436,83 @@
         """
 
     async def get_data_source(
         self, *, DataSourceId: str, Verbose: bool = ...
     ) -> GetDataSourceOutputTypeDef:
         """
         Returns a `DataSource` that includes metadata and data file information, as well
-        as the current status of the `DataSource` .
+        as the current status of the `DataSource`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.get_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_data_source)
         """
 
     async def get_evaluation(self, *, EvaluationId: str) -> GetEvaluationOutputTypeDef:
         """
         Returns an `Evaluation` that includes metadata as well as the current status of
-        the `Evaluation` .
+        the `Evaluation`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.get_evaluation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_evaluation)
         """
 
     async def get_ml_model(self, *, MLModelId: str, Verbose: bool = ...) -> GetMLModelOutputTypeDef:
         """
         Returns an `MLModel` that includes detailed metadata, data source information,
-        and the current status of the `MLModel` .
+        and the current status of the `MLModel`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.get_ml_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_ml_model)
         """
 
     async def predict(
         self, *, MLModelId: str, Record: Mapping[str, str], PredictEndpoint: str
     ) -> PredictOutputTypeDef:
         """
-        Generates a prediction for the observation using the specified `ML Model` .
+        Generates a prediction for the observation using the specified `ML Model`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.predict)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#predict)
         """
 
     async def update_batch_prediction(
         self, *, BatchPredictionId: str, BatchPredictionName: str
     ) -> UpdateBatchPredictionOutputTypeDef:
         """
-        Updates the `BatchPredictionName` of a `BatchPrediction` .
+        Updates the `BatchPredictionName` of a `BatchPrediction`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_batch_prediction)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_batch_prediction)
         """
 
     async def update_data_source(
         self, *, DataSourceId: str, DataSourceName: str
     ) -> UpdateDataSourceOutputTypeDef:
         """
-        Updates the `DataSourceName` of a `DataSource` .
+        Updates the `DataSourceName` of a `DataSource`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_data_source)
         """
 
     async def update_evaluation(
         self, *, EvaluationId: str, EvaluationName: str
     ) -> UpdateEvaluationOutputTypeDef:
         """
-        Updates the `EvaluationName` of an `Evaluation` .
+        Updates the `EvaluationName` of an `Evaluation`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_evaluation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_evaluation)
         """
 
     async def update_ml_model(
         self, *, MLModelId: str, MLModelName: str = ..., ScoreThreshold: float = ...
     ) -> UpdateMLModelOutputTypeDef:
         """
-        Updates the `MLModelName` and the `ScoreThreshold` of an `MLModel` .
+        Updates the `MLModelName` and the `ScoreThreshold` of an `MLModel`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_ml_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_ml_model)
         """
 
     @overload
     def get_paginator(
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/client.pyi` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -241,45 +241,45 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.create_realtime_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#create_realtime_endpoint)
         """
     async def delete_batch_prediction(
         self, *, BatchPredictionId: str
     ) -> DeleteBatchPredictionOutputTypeDef:
         """
-        Assigns the DELETED status to a `BatchPrediction` , rendering it unusable.
+        Assigns the DELETED status to a `BatchPrediction`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_batch_prediction)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_batch_prediction)
         """
     async def delete_data_source(self, *, DataSourceId: str) -> DeleteDataSourceOutputTypeDef:
         """
-        Assigns the DELETED status to a `DataSource` , rendering it unusable.
+        Assigns the DELETED status to a `DataSource`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_data_source)
         """
     async def delete_evaluation(self, *, EvaluationId: str) -> DeleteEvaluationOutputTypeDef:
         """
-        Assigns the `DELETED` status to an `Evaluation` , rendering it unusable.
+        Assigns the `DELETED` status to an `Evaluation`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_evaluation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_evaluation)
         """
     async def delete_ml_model(self, *, MLModelId: str) -> DeleteMLModelOutputTypeDef:
         """
-        Assigns the `DELETED` status to an `MLModel` , rendering it unusable.
+        Assigns the `DELETED` status to an `MLModel`, rendering it unusable.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_ml_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_ml_model)
         """
     async def delete_realtime_endpoint(
         self, *, MLModelId: str
     ) -> DeleteRealtimeEndpointOutputTypeDef:
         """
-        Deletes a real time endpoint of an `MLModel` .
+        Deletes a real time endpoint of an `MLModel`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.delete_realtime_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#delete_realtime_endpoint)
         """
     async def delete_tags(
         self, *, TagKeys: Sequence[str], ResourceId: str, ResourceType: TaggableResourceTypeType
     ) -> DeleteTagsOutputTypeDef:
@@ -408,76 +408,76 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_batch_prediction)
         """
     async def get_data_source(
         self, *, DataSourceId: str, Verbose: bool = ...
     ) -> GetDataSourceOutputTypeDef:
         """
         Returns a `DataSource` that includes metadata and data file information, as well
-        as the current status of the `DataSource` .
+        as the current status of the `DataSource`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.get_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_data_source)
         """
     async def get_evaluation(self, *, EvaluationId: str) -> GetEvaluationOutputTypeDef:
         """
         Returns an `Evaluation` that includes metadata as well as the current status of
-        the `Evaluation` .
+        the `Evaluation`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.get_evaluation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_evaluation)
         """
     async def get_ml_model(self, *, MLModelId: str, Verbose: bool = ...) -> GetMLModelOutputTypeDef:
         """
         Returns an `MLModel` that includes detailed metadata, data source information,
-        and the current status of the `MLModel` .
+        and the current status of the `MLModel`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.get_ml_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#get_ml_model)
         """
     async def predict(
         self, *, MLModelId: str, Record: Mapping[str, str], PredictEndpoint: str
     ) -> PredictOutputTypeDef:
         """
-        Generates a prediction for the observation using the specified `ML Model` .
+        Generates a prediction for the observation using the specified `ML Model`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.predict)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#predict)
         """
     async def update_batch_prediction(
         self, *, BatchPredictionId: str, BatchPredictionName: str
     ) -> UpdateBatchPredictionOutputTypeDef:
         """
-        Updates the `BatchPredictionName` of a `BatchPrediction` .
+        Updates the `BatchPredictionName` of a `BatchPrediction`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_batch_prediction)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_batch_prediction)
         """
     async def update_data_source(
         self, *, DataSourceId: str, DataSourceName: str
     ) -> UpdateDataSourceOutputTypeDef:
         """
-        Updates the `DataSourceName` of a `DataSource` .
+        Updates the `DataSourceName` of a `DataSource`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_data_source)
         """
     async def update_evaluation(
         self, *, EvaluationId: str, EvaluationName: str
     ) -> UpdateEvaluationOutputTypeDef:
         """
-        Updates the `EvaluationName` of an `Evaluation` .
+        Updates the `EvaluationName` of an `Evaluation`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_evaluation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_evaluation)
         """
     async def update_ml_model(
         self, *, MLModelId: str, MLModelName: str = ..., ScoreThreshold: float = ...
     ) -> UpdateMLModelOutputTypeDef:
         """
-        Updates the `MLModelName` and the `ScoreThreshold` of an `MLModel` .
+        Updates the `MLModelName` and the `ScoreThreshold` of an `MLModel`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Client.update_ml_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/client/#update_ml_model)
         """
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_batch_predictions"]
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/literals.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -157,14 +157,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -261,14 +263,15 @@
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
@@ -304,14 +307,15 @@
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
@@ -330,16 +334,19 @@
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
@@ -423,15 +430,17 @@
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/literals.pyi` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -155,14 +155,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -259,14 +261,15 @@
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
@@ -302,14 +305,15 @@
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
@@ -328,16 +332,19 @@
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
@@ -421,15 +428,17 @@
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/paginator.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,16 +22,15 @@
 
         describe_batch_predictions_paginator: DescribeBatchPredictionsPaginator = client.get_paginator("describe_batch_predictions")
         describe_data_sources_paginator: DescribeDataSourcesPaginator = client.get_paginator("describe_data_sources")
         describe_evaluations_paginator: DescribeEvaluationsPaginator = client.get_paginator("describe_evaluations")
         describe_ml_models_paginator: DescribeMLModelsPaginator = client.get_paginator("describe_ml_models")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     BatchPredictionFilterVariableType,
     DataSourceFilterVariableType,
@@ -43,20 +42,14 @@
     DescribeBatchPredictionsOutputTypeDef,
     DescribeDataSourcesOutputTypeDef,
     DescribeEvaluationsOutputTypeDef,
     DescribeMLModelsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeBatchPredictionsPaginator",
     "DescribeDataSourcesPaginator",
     "DescribeEvaluationsPaginator",
     "DescribeMLModelsPaginator",
 )
 
@@ -85,15 +78,15 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBatchPredictionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeBatchPredictions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describebatchpredictionspaginator)
         """
 
 
@@ -111,15 +104,15 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDataSourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeDataSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describedatasourcespaginator)
         """
 
 
@@ -137,15 +130,15 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEvaluationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeEvaluations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describeevaluationspaginator)
         """
 
 
@@ -163,13 +156,13 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMLModelsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeMLModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describemlmodelspaginator)
         """
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/paginator.pyi` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -22,16 +22,15 @@
 
         describe_batch_predictions_paginator: DescribeBatchPredictionsPaginator = client.get_paginator("describe_batch_predictions")
         describe_data_sources_paginator: DescribeDataSourcesPaginator = client.get_paginator("describe_data_sources")
         describe_evaluations_paginator: DescribeEvaluationsPaginator = client.get_paginator("describe_evaluations")
         describe_ml_models_paginator: DescribeMLModelsPaginator = client.get_paginator("describe_ml_models")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     BatchPredictionFilterVariableType,
     DataSourceFilterVariableType,
@@ -43,19 +42,14 @@
     DescribeBatchPredictionsOutputTypeDef,
     DescribeDataSourcesOutputTypeDef,
     DescribeEvaluationsOutputTypeDef,
     DescribeMLModelsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeBatchPredictionsPaginator",
     "DescribeDataSourcesPaginator",
     "DescribeEvaluationsPaginator",
     "DescribeMLModelsPaginator",
 )
 
@@ -81,15 +75,15 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBatchPredictionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeBatchPredictions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describebatchpredictionspaginator)
         """
 
 class DescribeDataSourcesPaginator(AioPaginator):
@@ -106,15 +100,15 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDataSourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeDataSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describedatasourcespaginator)
         """
 
 class DescribeEvaluationsPaginator(AioPaginator):
@@ -131,15 +125,15 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEvaluationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeEvaluations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describeevaluationspaginator)
         """
 
 class DescribeMLModelsPaginator(AioPaginator):
@@ -156,13 +150,13 @@
         GT: str = ...,
         LT: str = ...,
         GE: str = ...,
         LE: str = ...,
         NE: str = ...,
         Prefix: str = ...,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMLModelsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning.Paginator.DescribeMLModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/paginators/#describemlmodelspaginator)
         """
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/type_defs.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -36,83 +36,83 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddTagsOutputTypeDef",
     "BatchPredictionTypeDef",
     "CreateBatchPredictionInputRequestTypeDef",
+    "CreateBatchPredictionOutputTypeDef",
+    "CreateDataSourceFromRDSOutputTypeDef",
+    "CreateDataSourceFromRedshiftOutputTypeDef",
     "S3DataSpecTypeDef",
+    "CreateDataSourceFromS3OutputTypeDef",
     "CreateEvaluationInputRequestTypeDef",
+    "CreateEvaluationOutputTypeDef",
     "CreateMLModelInputRequestTypeDef",
+    "CreateMLModelOutputTypeDef",
     "CreateRealtimeEndpointInputRequestTypeDef",
     "RealtimeEndpointInfoTypeDef",
     "DeleteBatchPredictionInputRequestTypeDef",
+    "DeleteBatchPredictionOutputTypeDef",
     "DeleteDataSourceInputRequestTypeDef",
+    "DeleteDataSourceOutputTypeDef",
     "DeleteEvaluationInputRequestTypeDef",
+    "DeleteEvaluationOutputTypeDef",
     "DeleteMLModelInputRequestTypeDef",
+    "DeleteMLModelOutputTypeDef",
     "DeleteRealtimeEndpointInputRequestTypeDef",
     "DeleteTagsInputRequestTypeDef",
+    "DeleteTagsOutputTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
     "DescribeBatchPredictionsInputRequestTypeDef",
+    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
     "DescribeDataSourcesInputRequestTypeDef",
+    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
     "DescribeEvaluationsInputRequestTypeDef",
+    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
     "DescribeMLModelsInputRequestTypeDef",
     "DescribeTagsInputRequestTypeDef",
     "PerformanceMetricsTypeDef",
     "GetBatchPredictionInputRequestTypeDef",
+    "GetBatchPredictionOutputTypeDef",
     "GetDataSourceInputRequestTypeDef",
     "GetEvaluationInputRequestTypeDef",
     "GetMLModelInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PredictInputRequestTypeDef",
     "PredictionTypeDef",
     "RDSDatabaseCredentialsTypeDef",
     "RDSDatabaseTypeDef",
     "RedshiftDatabaseCredentialsTypeDef",
     "RedshiftDatabaseTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateBatchPredictionInputRequestTypeDef",
+    "UpdateBatchPredictionOutputTypeDef",
     "UpdateDataSourceInputRequestTypeDef",
+    "UpdateDataSourceOutputTypeDef",
     "UpdateEvaluationInputRequestTypeDef",
+    "UpdateEvaluationOutputTypeDef",
     "UpdateMLModelInputRequestTypeDef",
+    "UpdateMLModelOutputTypeDef",
     "AddTagsInputRequestTypeDef",
-    "AddTagsOutputTypeDef",
-    "CreateBatchPredictionOutputTypeDef",
-    "CreateDataSourceFromRDSOutputTypeDef",
-    "CreateDataSourceFromRedshiftOutputTypeDef",
-    "CreateDataSourceFromS3OutputTypeDef",
-    "CreateEvaluationOutputTypeDef",
-    "CreateMLModelOutputTypeDef",
-    "DeleteBatchPredictionOutputTypeDef",
-    "DeleteDataSourceOutputTypeDef",
-    "DeleteEvaluationOutputTypeDef",
-    "DeleteMLModelOutputTypeDef",
-    "DeleteTagsOutputTypeDef",
     "DescribeTagsOutputTypeDef",
-    "GetBatchPredictionOutputTypeDef",
-    "UpdateBatchPredictionOutputTypeDef",
-    "UpdateDataSourceOutputTypeDef",
-    "UpdateEvaluationOutputTypeDef",
-    "UpdateMLModelOutputTypeDef",
     "DescribeBatchPredictionsOutputTypeDef",
     "CreateDataSourceFromS3InputRequestTypeDef",
     "CreateRealtimeEndpointOutputTypeDef",
     "DeleteRealtimeEndpointOutputTypeDef",
     "GetMLModelOutputTypeDef",
     "MLModelTypeDef",
     "DescribeBatchPredictionsInputBatchPredictionAvailableWaitTypeDef",
     "DescribeDataSourcesInputDataSourceAvailableWaitTypeDef",
     "DescribeEvaluationsInputEvaluationAvailableWaitTypeDef",
     "DescribeMLModelsInputMLModelAvailableWaitTypeDef",
-    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
-    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
-    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
-    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
     "EvaluationTypeDef",
     "GetEvaluationOutputTypeDef",
     "PredictOutputTypeDef",
     "RDSDataSpecTypeDef",
     "RDSMetadataTypeDef",
     "RedshiftDataSpecTypeDef",
     "RedshiftMetadataTypeDef",
@@ -130,22 +130,20 @@
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddTagsOutputTypeDef = TypedDict(
+    "AddTagsOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResourceId": str,
+        "ResourceType": TaggableResourceTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPredictionTypeDef = TypedDict(
     "BatchPredictionTypeDef",
     {
         "BatchPredictionId": str,
@@ -189,14 +187,38 @@
 class CreateBatchPredictionInputRequestTypeDef(
     _RequiredCreateBatchPredictionInputRequestTypeDef,
     _OptionalCreateBatchPredictionInputRequestTypeDef,
 ):
     pass
 
 
+CreateBatchPredictionOutputTypeDef = TypedDict(
+    "CreateBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDataSourceFromRDSOutputTypeDef = TypedDict(
+    "CreateDataSourceFromRDSOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDataSourceFromRedshiftOutputTypeDef = TypedDict(
+    "CreateDataSourceFromRedshiftOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredS3DataSpecTypeDef = TypedDict(
     "_RequiredS3DataSpecTypeDef",
     {
         "DataLocationS3": str,
     },
 )
 _OptionalS3DataSpecTypeDef = TypedDict(
@@ -210,14 +232,22 @@
 )
 
 
 class S3DataSpecTypeDef(_RequiredS3DataSpecTypeDef, _OptionalS3DataSpecTypeDef):
     pass
 
 
+CreateDataSourceFromS3OutputTypeDef = TypedDict(
+    "CreateDataSourceFromS3OutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateEvaluationInputRequestTypeDef = TypedDict(
     "_RequiredCreateEvaluationInputRequestTypeDef",
     {
         "EvaluationId": str,
         "MLModelId": str,
         "EvaluationDataSourceId": str,
     },
@@ -233,14 +263,22 @@
 
 class CreateEvaluationInputRequestTypeDef(
     _RequiredCreateEvaluationInputRequestTypeDef, _OptionalCreateEvaluationInputRequestTypeDef
 ):
     pass
 
 
+CreateEvaluationOutputTypeDef = TypedDict(
+    "CreateEvaluationOutputTypeDef",
+    {
+        "EvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateMLModelInputRequestTypeDef = TypedDict(
     "_RequiredCreateMLModelInputRequestTypeDef",
     {
         "MLModelId": str,
         "MLModelType": MLModelTypeType,
         "TrainingDataSourceId": str,
     },
@@ -259,14 +297,22 @@
 
 class CreateMLModelInputRequestTypeDef(
     _RequiredCreateMLModelInputRequestTypeDef, _OptionalCreateMLModelInputRequestTypeDef
 ):
     pass
 
 
+CreateMLModelOutputTypeDef = TypedDict(
+    "CreateMLModelOutputTypeDef",
+    {
+        "MLModelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateRealtimeEndpointInputRequestTypeDef = TypedDict(
     "CreateRealtimeEndpointInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 
@@ -284,35 +330,67 @@
 DeleteBatchPredictionInputRequestTypeDef = TypedDict(
     "DeleteBatchPredictionInputRequestTypeDef",
     {
         "BatchPredictionId": str,
     },
 )
 
+DeleteBatchPredictionOutputTypeDef = TypedDict(
+    "DeleteBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDataSourceInputRequestTypeDef = TypedDict(
     "DeleteDataSourceInputRequestTypeDef",
     {
         "DataSourceId": str,
     },
 )
 
+DeleteDataSourceOutputTypeDef = TypedDict(
+    "DeleteDataSourceOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEvaluationInputRequestTypeDef = TypedDict(
     "DeleteEvaluationInputRequestTypeDef",
     {
         "EvaluationId": str,
     },
 )
 
+DeleteEvaluationOutputTypeDef = TypedDict(
+    "DeleteEvaluationOutputTypeDef",
+    {
+        "EvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMLModelInputRequestTypeDef = TypedDict(
     "DeleteMLModelInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 
+DeleteMLModelOutputTypeDef = TypedDict(
+    "DeleteMLModelOutputTypeDef",
+    {
+        "MLModelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteRealtimeEndpointInputRequestTypeDef = TypedDict(
     "DeleteRealtimeEndpointInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 
@@ -321,29 +399,45 @@
     {
         "TagKeys": Sequence[str],
         "ResourceId": str,
         "ResourceType": TaggableResourceTypeType,
     },
 )
 
+DeleteTagsOutputTypeDef = TypedDict(
+    "DeleteTagsOutputTypeDef",
+    {
+        "ResourceId": str,
+        "ResourceType": TaggableResourceTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef = TypedDict(
+    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FilterVariable": BatchPredictionFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeBatchPredictionsInputRequestTypeDef = TypedDict(
     "DescribeBatchPredictionsInputRequestTypeDef",
     {
@@ -358,14 +452,31 @@
         "SortOrder": SortOrderType,
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef = TypedDict(
+    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
+    {
+        "FilterVariable": DataSourceFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDataSourcesInputRequestTypeDef = TypedDict(
     "DescribeDataSourcesInputRequestTypeDef",
     {
         "FilterVariable": DataSourceFilterVariableType,
         "EQ": str,
         "GT": str,
         "LT": str,
@@ -376,14 +487,31 @@
         "SortOrder": SortOrderType,
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef = TypedDict(
+    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
+    {
+        "FilterVariable": EvaluationFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEvaluationsInputRequestTypeDef = TypedDict(
     "DescribeEvaluationsInputRequestTypeDef",
     {
         "FilterVariable": EvaluationFilterVariableType,
         "EQ": str,
         "GT": str,
         "LT": str,
@@ -394,14 +522,31 @@
         "SortOrder": SortOrderType,
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+DescribeMLModelsInputDescribeMLModelsPaginateTypeDef = TypedDict(
+    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
+    {
+        "FilterVariable": MLModelFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMLModelsInputRequestTypeDef = TypedDict(
     "DescribeMLModelsInputRequestTypeDef",
     {
         "FilterVariable": MLModelFilterVariableType,
         "EQ": str,
         "GT": str,
         "LT": str,
@@ -435,14 +580,38 @@
 GetBatchPredictionInputRequestTypeDef = TypedDict(
     "GetBatchPredictionInputRequestTypeDef",
     {
         "BatchPredictionId": str,
     },
 )
 
+GetBatchPredictionOutputTypeDef = TypedDict(
+    "GetBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "MLModelId": str,
+        "BatchPredictionDataSourceId": str,
+        "InputDataLocationS3": str,
+        "CreatedByIamUser": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Name": str,
+        "Status": EntityStatusType,
+        "OutputUri": str,
+        "LogUri": str,
+        "Message": str,
+        "ComputeTime": int,
+        "FinishedAt": datetime,
+        "StartedAt": datetime,
+        "TotalRecordCount": int,
+        "InvalidRecordCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDataSourceInputRequestTypeDef = TypedDict(
     "_RequiredGetDataSourceInputRequestTypeDef",
     {
         "DataSourceId": str,
     },
 )
 _OptionalGetDataSourceInputRequestTypeDef = TypedDict(
@@ -484,14 +653,24 @@
 
 class GetMLModelInputRequestTypeDef(
     _RequiredGetMLModelInputRequestTypeDef, _OptionalGetMLModelInputRequestTypeDef
 ):
     pass
 
 
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
 PredictInputRequestTypeDef = TypedDict(
     "PredictInputRequestTypeDef",
     {
         "MLModelId": str,
         "Record": Mapping[str, str],
         "PredictEndpoint": str,
     },
@@ -536,38 +715,73 @@
     "RedshiftDatabaseTypeDef",
     {
         "DatabaseName": str,
         "ClusterIdentifier": str,
     },
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
 UpdateBatchPredictionInputRequestTypeDef = TypedDict(
     "UpdateBatchPredictionInputRequestTypeDef",
     {
         "BatchPredictionId": str,
         "BatchPredictionName": str,
     },
 )
 
+UpdateBatchPredictionOutputTypeDef = TypedDict(
+    "UpdateBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateDataSourceInputRequestTypeDef = TypedDict(
     "UpdateDataSourceInputRequestTypeDef",
     {
         "DataSourceId": str,
         "DataSourceName": str,
     },
 )
 
+UpdateDataSourceOutputTypeDef = TypedDict(
+    "UpdateDataSourceOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateEvaluationInputRequestTypeDef = TypedDict(
     "UpdateEvaluationInputRequestTypeDef",
     {
         "EvaluationId": str,
         "EvaluationName": str,
     },
 )
 
+UpdateEvaluationOutputTypeDef = TypedDict(
+    "UpdateEvaluationOutputTypeDef",
+    {
+        "EvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateMLModelInputRequestTypeDef = TypedDict(
     "_RequiredUpdateMLModelInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 _OptionalUpdateMLModelInputRequestTypeDef = TypedDict(
@@ -582,193 +796,47 @@
 
 class UpdateMLModelInputRequestTypeDef(
     _RequiredUpdateMLModelInputRequestTypeDef, _OptionalUpdateMLModelInputRequestTypeDef
 ):
     pass
 
 
-AddTagsInputRequestTypeDef = TypedDict(
-    "AddTagsInputRequestTypeDef",
-    {
-        "Tags": Sequence[TagTypeDef],
-        "ResourceId": str,
-        "ResourceType": TaggableResourceTypeType,
-    },
-)
-
-AddTagsOutputTypeDef = TypedDict(
-    "AddTagsOutputTypeDef",
-    {
-        "ResourceId": str,
-        "ResourceType": TaggableResourceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBatchPredictionOutputTypeDef = TypedDict(
-    "CreateBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceFromRDSOutputTypeDef = TypedDict(
-    "CreateDataSourceFromRDSOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceFromRedshiftOutputTypeDef = TypedDict(
-    "CreateDataSourceFromRedshiftOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceFromS3OutputTypeDef = TypedDict(
-    "CreateDataSourceFromS3OutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEvaluationOutputTypeDef = TypedDict(
-    "CreateEvaluationOutputTypeDef",
-    {
-        "EvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMLModelOutputTypeDef = TypedDict(
-    "CreateMLModelOutputTypeDef",
-    {
-        "MLModelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBatchPredictionOutputTypeDef = TypedDict(
-    "DeleteBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDataSourceOutputTypeDef = TypedDict(
-    "DeleteDataSourceOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEvaluationOutputTypeDef = TypedDict(
-    "DeleteEvaluationOutputTypeDef",
-    {
-        "EvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMLModelOutputTypeDef = TypedDict(
-    "DeleteMLModelOutputTypeDef",
+UpdateMLModelOutputTypeDef = TypedDict(
+    "UpdateMLModelOutputTypeDef",
     {
         "MLModelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteTagsOutputTypeDef = TypedDict(
-    "DeleteTagsOutputTypeDef",
+AddTagsInputRequestTypeDef = TypedDict(
+    "AddTagsInputRequestTypeDef",
     {
+        "Tags": Sequence[TagTypeDef],
         "ResourceId": str,
         "ResourceType": TaggableResourceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
 DescribeTagsOutputTypeDef = TypedDict(
     "DescribeTagsOutputTypeDef",
     {
         "ResourceId": str,
         "ResourceType": TaggableResourceTypeType,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBatchPredictionOutputTypeDef = TypedDict(
-    "GetBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "MLModelId": str,
-        "BatchPredictionDataSourceId": str,
-        "InputDataLocationS3": str,
-        "CreatedByIamUser": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "Name": str,
-        "Status": EntityStatusType,
-        "OutputUri": str,
-        "LogUri": str,
-        "Message": str,
-        "ComputeTime": int,
-        "FinishedAt": datetime,
-        "StartedAt": datetime,
-        "TotalRecordCount": int,
-        "InvalidRecordCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBatchPredictionOutputTypeDef = TypedDict(
-    "UpdateBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDataSourceOutputTypeDef = TypedDict(
-    "UpdateDataSourceOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateEvaluationOutputTypeDef = TypedDict(
-    "UpdateEvaluationOutputTypeDef",
-    {
-        "EvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMLModelOutputTypeDef = TypedDict(
-    "UpdateMLModelOutputTypeDef",
-    {
-        "MLModelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBatchPredictionsOutputTypeDef = TypedDict(
     "DescribeBatchPredictionsOutputTypeDef",
     {
         "Results": List[BatchPredictionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceFromS3InputRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceFromS3InputRequestTypeDef",
     {
         "DataSourceId": str,
@@ -793,24 +861,24 @@
 
 
 CreateRealtimeEndpointOutputTypeDef = TypedDict(
     "CreateRealtimeEndpointOutputTypeDef",
     {
         "MLModelId": str,
         "RealtimeEndpointInfo": RealtimeEndpointInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRealtimeEndpointOutputTypeDef = TypedDict(
     "DeleteRealtimeEndpointOutputTypeDef",
     {
         "MLModelId": str,
         "RealtimeEndpointInfo": RealtimeEndpointInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMLModelOutputTypeDef = TypedDict(
     "GetMLModelOutputTypeDef",
     {
         "MLModelId": str,
@@ -830,15 +898,15 @@
         "LogUri": str,
         "Message": str,
         "ComputeTime": int,
         "FinishedAt": datetime,
         "StartedAt": datetime,
         "Recipe": str,
         "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MLModelTypeDef = TypedDict(
     "MLModelTypeDef",
     {
         "MLModelId": str,
@@ -936,82 +1004,14 @@
         "NextToken": str,
         "Limit": int,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef = TypedDict(
-    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
-    {
-        "FilterVariable": BatchPredictionFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef = TypedDict(
-    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
-    {
-        "FilterVariable": DataSourceFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef = TypedDict(
-    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
-    {
-        "FilterVariable": EvaluationFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeMLModelsInputDescribeMLModelsPaginateTypeDef = TypedDict(
-    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
-    {
-        "FilterVariable": MLModelFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 EvaluationTypeDef = TypedDict(
     "EvaluationTypeDef",
     {
         "EvaluationId": str,
         "MLModelId": str,
         "EvaluationDataSourceId": str,
         "InputDataLocationS3": str,
@@ -1043,23 +1043,23 @@
         "Status": EntityStatusType,
         "PerformanceMetrics": PerformanceMetricsTypeDef,
         "LogUri": str,
         "Message": str,
         "ComputeTime": int,
         "FinishedAt": datetime,
         "StartedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PredictOutputTypeDef = TypedDict(
     "PredictOutputTypeDef",
     {
         "Prediction": PredictionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRDSDataSpecTypeDef = TypedDict(
     "_RequiredRDSDataSpecTypeDef",
     {
         "DatabaseInformation": RDSDatabaseTypeDef,
@@ -1135,24 +1135,24 @@
 )
 
 DescribeMLModelsOutputTypeDef = TypedDict(
     "DescribeMLModelsOutputTypeDef",
     {
         "Results": List[MLModelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEvaluationsOutputTypeDef = TypedDict(
     "DescribeEvaluationsOutputTypeDef",
     {
         "Results": List[EvaluationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceFromRDSInputRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceFromRDSInputRequestTypeDef",
     {
         "DataSourceId": str,
@@ -1246,19 +1246,19 @@
         "RDSMetadata": RDSMetadataTypeDef,
         "RoleARN": str,
         "ComputeStatistics": bool,
         "ComputeTime": int,
         "FinishedAt": datetime,
         "StartedAt": datetime,
         "DataSourceSchema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataSourcesOutputTypeDef = TypedDict(
     "DescribeDataSourcesOutputTypeDef",
     {
         "Results": List[DataSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/type_defs.pyi` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -35,83 +35,83 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddTagsOutputTypeDef",
     "BatchPredictionTypeDef",
     "CreateBatchPredictionInputRequestTypeDef",
+    "CreateBatchPredictionOutputTypeDef",
+    "CreateDataSourceFromRDSOutputTypeDef",
+    "CreateDataSourceFromRedshiftOutputTypeDef",
     "S3DataSpecTypeDef",
+    "CreateDataSourceFromS3OutputTypeDef",
     "CreateEvaluationInputRequestTypeDef",
+    "CreateEvaluationOutputTypeDef",
     "CreateMLModelInputRequestTypeDef",
+    "CreateMLModelOutputTypeDef",
     "CreateRealtimeEndpointInputRequestTypeDef",
     "RealtimeEndpointInfoTypeDef",
     "DeleteBatchPredictionInputRequestTypeDef",
+    "DeleteBatchPredictionOutputTypeDef",
     "DeleteDataSourceInputRequestTypeDef",
+    "DeleteDataSourceOutputTypeDef",
     "DeleteEvaluationInputRequestTypeDef",
+    "DeleteEvaluationOutputTypeDef",
     "DeleteMLModelInputRequestTypeDef",
+    "DeleteMLModelOutputTypeDef",
     "DeleteRealtimeEndpointInputRequestTypeDef",
     "DeleteTagsInputRequestTypeDef",
+    "DeleteTagsOutputTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
     "DescribeBatchPredictionsInputRequestTypeDef",
+    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
     "DescribeDataSourcesInputRequestTypeDef",
+    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
     "DescribeEvaluationsInputRequestTypeDef",
+    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
     "DescribeMLModelsInputRequestTypeDef",
     "DescribeTagsInputRequestTypeDef",
     "PerformanceMetricsTypeDef",
     "GetBatchPredictionInputRequestTypeDef",
+    "GetBatchPredictionOutputTypeDef",
     "GetDataSourceInputRequestTypeDef",
     "GetEvaluationInputRequestTypeDef",
     "GetMLModelInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PredictInputRequestTypeDef",
     "PredictionTypeDef",
     "RDSDatabaseCredentialsTypeDef",
     "RDSDatabaseTypeDef",
     "RedshiftDatabaseCredentialsTypeDef",
     "RedshiftDatabaseTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateBatchPredictionInputRequestTypeDef",
+    "UpdateBatchPredictionOutputTypeDef",
     "UpdateDataSourceInputRequestTypeDef",
+    "UpdateDataSourceOutputTypeDef",
     "UpdateEvaluationInputRequestTypeDef",
+    "UpdateEvaluationOutputTypeDef",
     "UpdateMLModelInputRequestTypeDef",
+    "UpdateMLModelOutputTypeDef",
     "AddTagsInputRequestTypeDef",
-    "AddTagsOutputTypeDef",
-    "CreateBatchPredictionOutputTypeDef",
-    "CreateDataSourceFromRDSOutputTypeDef",
-    "CreateDataSourceFromRedshiftOutputTypeDef",
-    "CreateDataSourceFromS3OutputTypeDef",
-    "CreateEvaluationOutputTypeDef",
-    "CreateMLModelOutputTypeDef",
-    "DeleteBatchPredictionOutputTypeDef",
-    "DeleteDataSourceOutputTypeDef",
-    "DeleteEvaluationOutputTypeDef",
-    "DeleteMLModelOutputTypeDef",
-    "DeleteTagsOutputTypeDef",
     "DescribeTagsOutputTypeDef",
-    "GetBatchPredictionOutputTypeDef",
-    "UpdateBatchPredictionOutputTypeDef",
-    "UpdateDataSourceOutputTypeDef",
-    "UpdateEvaluationOutputTypeDef",
-    "UpdateMLModelOutputTypeDef",
     "DescribeBatchPredictionsOutputTypeDef",
     "CreateDataSourceFromS3InputRequestTypeDef",
     "CreateRealtimeEndpointOutputTypeDef",
     "DeleteRealtimeEndpointOutputTypeDef",
     "GetMLModelOutputTypeDef",
     "MLModelTypeDef",
     "DescribeBatchPredictionsInputBatchPredictionAvailableWaitTypeDef",
     "DescribeDataSourcesInputDataSourceAvailableWaitTypeDef",
     "DescribeEvaluationsInputEvaluationAvailableWaitTypeDef",
     "DescribeMLModelsInputMLModelAvailableWaitTypeDef",
-    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
-    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
-    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
-    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
     "EvaluationTypeDef",
     "GetEvaluationOutputTypeDef",
     "PredictOutputTypeDef",
     "RDSDataSpecTypeDef",
     "RDSMetadataTypeDef",
     "RedshiftDataSpecTypeDef",
     "RedshiftMetadataTypeDef",
@@ -129,22 +129,20 @@
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddTagsOutputTypeDef = TypedDict(
+    "AddTagsOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResourceId": str,
+        "ResourceType": TaggableResourceTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPredictionTypeDef = TypedDict(
     "BatchPredictionTypeDef",
     {
         "BatchPredictionId": str,
@@ -186,14 +184,38 @@
 
 class CreateBatchPredictionInputRequestTypeDef(
     _RequiredCreateBatchPredictionInputRequestTypeDef,
     _OptionalCreateBatchPredictionInputRequestTypeDef,
 ):
     pass
 
+CreateBatchPredictionOutputTypeDef = TypedDict(
+    "CreateBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDataSourceFromRDSOutputTypeDef = TypedDict(
+    "CreateDataSourceFromRDSOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDataSourceFromRedshiftOutputTypeDef = TypedDict(
+    "CreateDataSourceFromRedshiftOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredS3DataSpecTypeDef = TypedDict(
     "_RequiredS3DataSpecTypeDef",
     {
         "DataLocationS3": str,
     },
 )
 _OptionalS3DataSpecTypeDef = TypedDict(
@@ -205,14 +227,22 @@
     },
     total=False,
 )
 
 class S3DataSpecTypeDef(_RequiredS3DataSpecTypeDef, _OptionalS3DataSpecTypeDef):
     pass
 
+CreateDataSourceFromS3OutputTypeDef = TypedDict(
+    "CreateDataSourceFromS3OutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateEvaluationInputRequestTypeDef = TypedDict(
     "_RequiredCreateEvaluationInputRequestTypeDef",
     {
         "EvaluationId": str,
         "MLModelId": str,
         "EvaluationDataSourceId": str,
     },
@@ -226,14 +256,22 @@
 )
 
 class CreateEvaluationInputRequestTypeDef(
     _RequiredCreateEvaluationInputRequestTypeDef, _OptionalCreateEvaluationInputRequestTypeDef
 ):
     pass
 
+CreateEvaluationOutputTypeDef = TypedDict(
+    "CreateEvaluationOutputTypeDef",
+    {
+        "EvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateMLModelInputRequestTypeDef = TypedDict(
     "_RequiredCreateMLModelInputRequestTypeDef",
     {
         "MLModelId": str,
         "MLModelType": MLModelTypeType,
         "TrainingDataSourceId": str,
     },
@@ -250,14 +288,22 @@
 )
 
 class CreateMLModelInputRequestTypeDef(
     _RequiredCreateMLModelInputRequestTypeDef, _OptionalCreateMLModelInputRequestTypeDef
 ):
     pass
 
+CreateMLModelOutputTypeDef = TypedDict(
+    "CreateMLModelOutputTypeDef",
+    {
+        "MLModelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateRealtimeEndpointInputRequestTypeDef = TypedDict(
     "CreateRealtimeEndpointInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 
@@ -275,35 +321,67 @@
 DeleteBatchPredictionInputRequestTypeDef = TypedDict(
     "DeleteBatchPredictionInputRequestTypeDef",
     {
         "BatchPredictionId": str,
     },
 )
 
+DeleteBatchPredictionOutputTypeDef = TypedDict(
+    "DeleteBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDataSourceInputRequestTypeDef = TypedDict(
     "DeleteDataSourceInputRequestTypeDef",
     {
         "DataSourceId": str,
     },
 )
 
+DeleteDataSourceOutputTypeDef = TypedDict(
+    "DeleteDataSourceOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEvaluationInputRequestTypeDef = TypedDict(
     "DeleteEvaluationInputRequestTypeDef",
     {
         "EvaluationId": str,
     },
 )
 
+DeleteEvaluationOutputTypeDef = TypedDict(
+    "DeleteEvaluationOutputTypeDef",
+    {
+        "EvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMLModelInputRequestTypeDef = TypedDict(
     "DeleteMLModelInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 
+DeleteMLModelOutputTypeDef = TypedDict(
+    "DeleteMLModelOutputTypeDef",
+    {
+        "MLModelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteRealtimeEndpointInputRequestTypeDef = TypedDict(
     "DeleteRealtimeEndpointInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 
@@ -312,29 +390,45 @@
     {
         "TagKeys": Sequence[str],
         "ResourceId": str,
         "ResourceType": TaggableResourceTypeType,
     },
 )
 
+DeleteTagsOutputTypeDef = TypedDict(
+    "DeleteTagsOutputTypeDef",
+    {
+        "ResourceId": str,
+        "ResourceType": TaggableResourceTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef = TypedDict(
+    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FilterVariable": BatchPredictionFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeBatchPredictionsInputRequestTypeDef = TypedDict(
     "DescribeBatchPredictionsInputRequestTypeDef",
     {
@@ -349,14 +443,31 @@
         "SortOrder": SortOrderType,
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef = TypedDict(
+    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
+    {
+        "FilterVariable": DataSourceFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDataSourcesInputRequestTypeDef = TypedDict(
     "DescribeDataSourcesInputRequestTypeDef",
     {
         "FilterVariable": DataSourceFilterVariableType,
         "EQ": str,
         "GT": str,
         "LT": str,
@@ -367,14 +478,31 @@
         "SortOrder": SortOrderType,
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef = TypedDict(
+    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
+    {
+        "FilterVariable": EvaluationFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEvaluationsInputRequestTypeDef = TypedDict(
     "DescribeEvaluationsInputRequestTypeDef",
     {
         "FilterVariable": EvaluationFilterVariableType,
         "EQ": str,
         "GT": str,
         "LT": str,
@@ -385,14 +513,31 @@
         "SortOrder": SortOrderType,
         "NextToken": str,
         "Limit": int,
     },
     total=False,
 )
 
+DescribeMLModelsInputDescribeMLModelsPaginateTypeDef = TypedDict(
+    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
+    {
+        "FilterVariable": MLModelFilterVariableType,
+        "EQ": str,
+        "GT": str,
+        "LT": str,
+        "GE": str,
+        "LE": str,
+        "NE": str,
+        "Prefix": str,
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMLModelsInputRequestTypeDef = TypedDict(
     "DescribeMLModelsInputRequestTypeDef",
     {
         "FilterVariable": MLModelFilterVariableType,
         "EQ": str,
         "GT": str,
         "LT": str,
@@ -426,14 +571,38 @@
 GetBatchPredictionInputRequestTypeDef = TypedDict(
     "GetBatchPredictionInputRequestTypeDef",
     {
         "BatchPredictionId": str,
     },
 )
 
+GetBatchPredictionOutputTypeDef = TypedDict(
+    "GetBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "MLModelId": str,
+        "BatchPredictionDataSourceId": str,
+        "InputDataLocationS3": str,
+        "CreatedByIamUser": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Name": str,
+        "Status": EntityStatusType,
+        "OutputUri": str,
+        "LogUri": str,
+        "Message": str,
+        "ComputeTime": int,
+        "FinishedAt": datetime,
+        "StartedAt": datetime,
+        "TotalRecordCount": int,
+        "InvalidRecordCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDataSourceInputRequestTypeDef = TypedDict(
     "_RequiredGetDataSourceInputRequestTypeDef",
     {
         "DataSourceId": str,
     },
 )
 _OptionalGetDataSourceInputRequestTypeDef = TypedDict(
@@ -471,14 +640,24 @@
 )
 
 class GetMLModelInputRequestTypeDef(
     _RequiredGetMLModelInputRequestTypeDef, _OptionalGetMLModelInputRequestTypeDef
 ):
     pass
 
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
 PredictInputRequestTypeDef = TypedDict(
     "PredictInputRequestTypeDef",
     {
         "MLModelId": str,
         "Record": Mapping[str, str],
         "PredictEndpoint": str,
     },
@@ -523,38 +702,73 @@
     "RedshiftDatabaseTypeDef",
     {
         "DatabaseName": str,
         "ClusterIdentifier": str,
     },
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
 UpdateBatchPredictionInputRequestTypeDef = TypedDict(
     "UpdateBatchPredictionInputRequestTypeDef",
     {
         "BatchPredictionId": str,
         "BatchPredictionName": str,
     },
 )
 
+UpdateBatchPredictionOutputTypeDef = TypedDict(
+    "UpdateBatchPredictionOutputTypeDef",
+    {
+        "BatchPredictionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateDataSourceInputRequestTypeDef = TypedDict(
     "UpdateDataSourceInputRequestTypeDef",
     {
         "DataSourceId": str,
         "DataSourceName": str,
     },
 )
 
+UpdateDataSourceOutputTypeDef = TypedDict(
+    "UpdateDataSourceOutputTypeDef",
+    {
+        "DataSourceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateEvaluationInputRequestTypeDef = TypedDict(
     "UpdateEvaluationInputRequestTypeDef",
     {
         "EvaluationId": str,
         "EvaluationName": str,
     },
 )
 
+UpdateEvaluationOutputTypeDef = TypedDict(
+    "UpdateEvaluationOutputTypeDef",
+    {
+        "EvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateMLModelInputRequestTypeDef = TypedDict(
     "_RequiredUpdateMLModelInputRequestTypeDef",
     {
         "MLModelId": str,
     },
 )
 _OptionalUpdateMLModelInputRequestTypeDef = TypedDict(
@@ -567,193 +781,47 @@
 )
 
 class UpdateMLModelInputRequestTypeDef(
     _RequiredUpdateMLModelInputRequestTypeDef, _OptionalUpdateMLModelInputRequestTypeDef
 ):
     pass
 
-AddTagsInputRequestTypeDef = TypedDict(
-    "AddTagsInputRequestTypeDef",
-    {
-        "Tags": Sequence[TagTypeDef],
-        "ResourceId": str,
-        "ResourceType": TaggableResourceTypeType,
-    },
-)
-
-AddTagsOutputTypeDef = TypedDict(
-    "AddTagsOutputTypeDef",
-    {
-        "ResourceId": str,
-        "ResourceType": TaggableResourceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBatchPredictionOutputTypeDef = TypedDict(
-    "CreateBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceFromRDSOutputTypeDef = TypedDict(
-    "CreateDataSourceFromRDSOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceFromRedshiftOutputTypeDef = TypedDict(
-    "CreateDataSourceFromRedshiftOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceFromS3OutputTypeDef = TypedDict(
-    "CreateDataSourceFromS3OutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEvaluationOutputTypeDef = TypedDict(
-    "CreateEvaluationOutputTypeDef",
-    {
-        "EvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMLModelOutputTypeDef = TypedDict(
-    "CreateMLModelOutputTypeDef",
-    {
-        "MLModelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBatchPredictionOutputTypeDef = TypedDict(
-    "DeleteBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDataSourceOutputTypeDef = TypedDict(
-    "DeleteDataSourceOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEvaluationOutputTypeDef = TypedDict(
-    "DeleteEvaluationOutputTypeDef",
-    {
-        "EvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMLModelOutputTypeDef = TypedDict(
-    "DeleteMLModelOutputTypeDef",
+UpdateMLModelOutputTypeDef = TypedDict(
+    "UpdateMLModelOutputTypeDef",
     {
         "MLModelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteTagsOutputTypeDef = TypedDict(
-    "DeleteTagsOutputTypeDef",
+AddTagsInputRequestTypeDef = TypedDict(
+    "AddTagsInputRequestTypeDef",
     {
+        "Tags": Sequence[TagTypeDef],
         "ResourceId": str,
         "ResourceType": TaggableResourceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
 DescribeTagsOutputTypeDef = TypedDict(
     "DescribeTagsOutputTypeDef",
     {
         "ResourceId": str,
         "ResourceType": TaggableResourceTypeType,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBatchPredictionOutputTypeDef = TypedDict(
-    "GetBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "MLModelId": str,
-        "BatchPredictionDataSourceId": str,
-        "InputDataLocationS3": str,
-        "CreatedByIamUser": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "Name": str,
-        "Status": EntityStatusType,
-        "OutputUri": str,
-        "LogUri": str,
-        "Message": str,
-        "ComputeTime": int,
-        "FinishedAt": datetime,
-        "StartedAt": datetime,
-        "TotalRecordCount": int,
-        "InvalidRecordCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBatchPredictionOutputTypeDef = TypedDict(
-    "UpdateBatchPredictionOutputTypeDef",
-    {
-        "BatchPredictionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDataSourceOutputTypeDef = TypedDict(
-    "UpdateDataSourceOutputTypeDef",
-    {
-        "DataSourceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateEvaluationOutputTypeDef = TypedDict(
-    "UpdateEvaluationOutputTypeDef",
-    {
-        "EvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMLModelOutputTypeDef = TypedDict(
-    "UpdateMLModelOutputTypeDef",
-    {
-        "MLModelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBatchPredictionsOutputTypeDef = TypedDict(
     "DescribeBatchPredictionsOutputTypeDef",
     {
         "Results": List[BatchPredictionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceFromS3InputRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceFromS3InputRequestTypeDef",
     {
         "DataSourceId": str,
@@ -776,24 +844,24 @@
     pass
 
 CreateRealtimeEndpointOutputTypeDef = TypedDict(
     "CreateRealtimeEndpointOutputTypeDef",
     {
         "MLModelId": str,
         "RealtimeEndpointInfo": RealtimeEndpointInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRealtimeEndpointOutputTypeDef = TypedDict(
     "DeleteRealtimeEndpointOutputTypeDef",
     {
         "MLModelId": str,
         "RealtimeEndpointInfo": RealtimeEndpointInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMLModelOutputTypeDef = TypedDict(
     "GetMLModelOutputTypeDef",
     {
         "MLModelId": str,
@@ -813,15 +881,15 @@
         "LogUri": str,
         "Message": str,
         "ComputeTime": int,
         "FinishedAt": datetime,
         "StartedAt": datetime,
         "Recipe": str,
         "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MLModelTypeDef = TypedDict(
     "MLModelTypeDef",
     {
         "MLModelId": str,
@@ -919,82 +987,14 @@
         "NextToken": str,
         "Limit": int,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef = TypedDict(
-    "DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef",
-    {
-        "FilterVariable": BatchPredictionFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef = TypedDict(
-    "DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef",
-    {
-        "FilterVariable": DataSourceFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef = TypedDict(
-    "DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef",
-    {
-        "FilterVariable": EvaluationFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeMLModelsInputDescribeMLModelsPaginateTypeDef = TypedDict(
-    "DescribeMLModelsInputDescribeMLModelsPaginateTypeDef",
-    {
-        "FilterVariable": MLModelFilterVariableType,
-        "EQ": str,
-        "GT": str,
-        "LT": str,
-        "GE": str,
-        "LE": str,
-        "NE": str,
-        "Prefix": str,
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 EvaluationTypeDef = TypedDict(
     "EvaluationTypeDef",
     {
         "EvaluationId": str,
         "MLModelId": str,
         "EvaluationDataSourceId": str,
         "InputDataLocationS3": str,
@@ -1026,23 +1026,23 @@
         "Status": EntityStatusType,
         "PerformanceMetrics": PerformanceMetricsTypeDef,
         "LogUri": str,
         "Message": str,
         "ComputeTime": int,
         "FinishedAt": datetime,
         "StartedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PredictOutputTypeDef = TypedDict(
     "PredictOutputTypeDef",
     {
         "Prediction": PredictionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRDSDataSpecTypeDef = TypedDict(
     "_RequiredRDSDataSpecTypeDef",
     {
         "DatabaseInformation": RDSDatabaseTypeDef,
@@ -1114,24 +1114,24 @@
 )
 
 DescribeMLModelsOutputTypeDef = TypedDict(
     "DescribeMLModelsOutputTypeDef",
     {
         "Results": List[MLModelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEvaluationsOutputTypeDef = TypedDict(
     "DescribeEvaluationsOutputTypeDef",
     {
         "Results": List[EvaluationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceFromRDSInputRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceFromRDSInputRequestTypeDef",
     {
         "DataSourceId": str,
@@ -1221,19 +1221,19 @@
         "RDSMetadata": RDSMetadataTypeDef,
         "RoleARN": str,
         "ComputeStatistics": bool,
         "ComputeTime": int,
         "FinishedAt": datetime,
         "StartedAt": datetime,
         "DataSourceSchema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataSourcesOutputTypeDef = TypedDict(
     "DescribeDataSourcesOutputTypeDef",
     {
         "Results": List[DataSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/waiter.py` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning/waiter.pyi` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/PKG-INFO` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-machinelearning
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MachineLearning 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MachineLearning 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-machinelearning"></a>
 
 # types-aiobotocore-machinelearning
 
 [![PyPI - types-aiobotocore-machinelearning](https://img.shields.io/pypi/v/types-aiobotocore-machinelearning.svg?color=blue)](https://pypi.org/project/types-aiobotocore-machinelearning)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-machinelearning.svg?color=blue)](https://pypi.org/project/types-aiobotocore-machinelearning)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-machinelearning?color=blue)](https://pypistats.org/packages/types-aiobotocore-machinelearning)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MachineLearning 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning)
+[aiobotocore.MachineLearning 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/machinelearning.html#MachineLearning)
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
 [types-aiobotocore-machinelearning docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_machinelearning/).
 
 See how it helps to find and fix potential bugs:
 
@@ -387,83 +387,83 @@
 
 `types_aiobotocore_machinelearning.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_machinelearning.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AddTagsOutputTypeDef,
     BatchPredictionTypeDef,
     CreateBatchPredictionInputRequestTypeDef,
+    CreateBatchPredictionOutputTypeDef,
+    CreateDataSourceFromRDSOutputTypeDef,
+    CreateDataSourceFromRedshiftOutputTypeDef,
     S3DataSpecTypeDef,
+    CreateDataSourceFromS3OutputTypeDef,
     CreateEvaluationInputRequestTypeDef,
+    CreateEvaluationOutputTypeDef,
     CreateMLModelInputRequestTypeDef,
+    CreateMLModelOutputTypeDef,
     CreateRealtimeEndpointInputRequestTypeDef,
     RealtimeEndpointInfoTypeDef,
     DeleteBatchPredictionInputRequestTypeDef,
+    DeleteBatchPredictionOutputTypeDef,
     DeleteDataSourceInputRequestTypeDef,
+    DeleteDataSourceOutputTypeDef,
     DeleteEvaluationInputRequestTypeDef,
+    DeleteEvaluationOutputTypeDef,
     DeleteMLModelInputRequestTypeDef,
+    DeleteMLModelOutputTypeDef,
     DeleteRealtimeEndpointInputRequestTypeDef,
     DeleteTagsInputRequestTypeDef,
+    DeleteTagsOutputTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef,
     DescribeBatchPredictionsInputRequestTypeDef,
+    DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef,
     DescribeDataSourcesInputRequestTypeDef,
+    DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef,
     DescribeEvaluationsInputRequestTypeDef,
+    DescribeMLModelsInputDescribeMLModelsPaginateTypeDef,
     DescribeMLModelsInputRequestTypeDef,
     DescribeTagsInputRequestTypeDef,
     PerformanceMetricsTypeDef,
     GetBatchPredictionInputRequestTypeDef,
+    GetBatchPredictionOutputTypeDef,
     GetDataSourceInputRequestTypeDef,
     GetEvaluationInputRequestTypeDef,
     GetMLModelInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredictInputRequestTypeDef,
     PredictionTypeDef,
     RDSDatabaseCredentialsTypeDef,
     RDSDatabaseTypeDef,
     RedshiftDatabaseCredentialsTypeDef,
     RedshiftDatabaseTypeDef,
+    ResponseMetadataTypeDef,
     UpdateBatchPredictionInputRequestTypeDef,
+    UpdateBatchPredictionOutputTypeDef,
     UpdateDataSourceInputRequestTypeDef,
+    UpdateDataSourceOutputTypeDef,
     UpdateEvaluationInputRequestTypeDef,
+    UpdateEvaluationOutputTypeDef,
     UpdateMLModelInputRequestTypeDef,
+    UpdateMLModelOutputTypeDef,
     AddTagsInputRequestTypeDef,
-    AddTagsOutputTypeDef,
-    CreateBatchPredictionOutputTypeDef,
-    CreateDataSourceFromRDSOutputTypeDef,
-    CreateDataSourceFromRedshiftOutputTypeDef,
-    CreateDataSourceFromS3OutputTypeDef,
-    CreateEvaluationOutputTypeDef,
-    CreateMLModelOutputTypeDef,
-    DeleteBatchPredictionOutputTypeDef,
-    DeleteDataSourceOutputTypeDef,
-    DeleteEvaluationOutputTypeDef,
-    DeleteMLModelOutputTypeDef,
-    DeleteTagsOutputTypeDef,
     DescribeTagsOutputTypeDef,
-    GetBatchPredictionOutputTypeDef,
-    UpdateBatchPredictionOutputTypeDef,
-    UpdateDataSourceOutputTypeDef,
-    UpdateEvaluationOutputTypeDef,
-    UpdateMLModelOutputTypeDef,
     DescribeBatchPredictionsOutputTypeDef,
     CreateDataSourceFromS3InputRequestTypeDef,
     CreateRealtimeEndpointOutputTypeDef,
     DeleteRealtimeEndpointOutputTypeDef,
     GetMLModelOutputTypeDef,
     MLModelTypeDef,
     DescribeBatchPredictionsInputBatchPredictionAvailableWaitTypeDef,
     DescribeDataSourcesInputDataSourceAvailableWaitTypeDef,
     DescribeEvaluationsInputEvaluationAvailableWaitTypeDef,
     DescribeMLModelsInputMLModelAvailableWaitTypeDef,
-    DescribeBatchPredictionsInputDescribeBatchPredictionsPaginateTypeDef,
-    DescribeDataSourcesInputDescribeDataSourcesPaginateTypeDef,
-    DescribeEvaluationsInputDescribeEvaluationsPaginateTypeDef,
-    DescribeMLModelsInputDescribeMLModelsPaginateTypeDef,
     EvaluationTypeDef,
     GetEvaluationOutputTypeDef,
     PredictOutputTypeDef,
     RDSDataSpecTypeDef,
     RDSMetadataTypeDef,
     RedshiftDataSpecTypeDef,
     RedshiftMetadataTypeDef,
@@ -484,43 +484,43 @@
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

### Comparing `types-aiobotocore-machinelearning-2.5.0.post1/types_aiobotocore_machinelearning.egg-info/SOURCES.txt` & `types-aiobotocore-machinelearning-2.5.1/types_aiobotocore_machinelearning.egg-info/SOURCES.txt`

 * *Files identical despite different names*

