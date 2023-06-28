# Comparing `tmp/types-aiobotocore-lookoutequipment-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lookoutequipment-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lookoutequipment-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-lookoutequipment-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1.tar` & `types-aiobotocore-lookoutequipment-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.103391 types-aiobotocore-lookoutequipment-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16428 2023-03-11 12:26:56.091390 types-aiobotocore-lookoutequipment-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14821 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.103391 types-aiobotocore-lookoutequipment-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.083390 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/
--rw-r--r--   0 runner    (1001) docker     (123)      514 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      513 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27606 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27565 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8627 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8625 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    35926 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    35885 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:50.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.091390 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16428 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      887 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.238170 types-aiobotocore-lookoutequipment-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16429 2023-06-28 01:43:47.238170 types-aiobotocore-lookoutequipment-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14828 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.238170 types-aiobotocore-lookoutequipment-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.230170 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/
+-rw-r--r--   0 runner    (1001) docker     (123)      514 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27606 2023-06-28 01:34:31.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27565 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8836 2023-06-28 01:34:32.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8834 2023-06-28 01:34:32.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    35976 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35935 2023-06-28 01:34:32.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:30.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.238170 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16429 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      887 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/LICENSE` & `types-aiobotocore-lookoutequipment-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lookoutequipment-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lookoutequipment
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LookoutEquipment 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LookoutEquipment 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lookoutequipment"></a>
 
 # types-aiobotocore-lookoutequipment
 
 [![PyPI - types-aiobotocore-lookoutequipment](https://img.shields.io/pypi/v/types-aiobotocore-lookoutequipment.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutequipment)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutequipment.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutequipment)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutequipment?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutequipment)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutEquipment 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
+[aiobotocore.LookoutEquipment 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
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
 [types-aiobotocore-lookoutequipment docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/).
 
 See how it helps to find and fix potential bugs:
 
@@ -304,33 +304,40 @@
 
 ```python
 from types_aiobotocore_lookoutequipment.type_defs import (
     CategoricalValuesTypeDef,
     CountPercentTypeDef,
     DatasetSchemaTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDatasetResponseTypeDef,
+    CreateInferenceSchedulerResponseTypeDef,
+    CreateLabelGroupResponseTypeDef,
     CreateLabelRequestRequestTypeDef,
+    CreateLabelResponseTypeDef,
     DataPreProcessingConfigurationTypeDef,
+    CreateModelResponseTypeDef,
     DuplicateTimestampsTypeDef,
     InvalidSensorDataTypeDef,
     MissingSensorDataTypeDef,
     UnsupportedTimestampsTypeDef,
     DatasetSummaryTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteInferenceSchedulerRequestRequestTypeDef,
     DeleteLabelGroupRequestRequestTypeDef,
     DeleteLabelRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
     DescribeDataIngestionJobRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeInferenceSchedulerRequestRequestTypeDef,
     DescribeLabelGroupRequestRequestTypeDef,
+    DescribeLabelGroupResponseTypeDef,
     DescribeLabelRequestRequestTypeDef,
+    DescribeLabelResponseTypeDef,
     DescribeModelRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     InferenceEventSummaryTypeDef,
     S3ObjectTypeDef,
     InferenceInputNameConfigurationTypeDef,
     InferenceS3InputConfigurationTypeDef,
     InferenceS3OutputConfigurationTypeDef,
     InferenceSchedulerSummaryTypeDef,
     IngestionS3InputConfigurationTypeDef,
@@ -349,33 +356,26 @@
     ListLabelsRequestRequestTypeDef,
     ListModelsRequestRequestTypeDef,
     ModelSummaryTypeDef,
     ListSensorStatisticsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MonotonicValuesTypeDef,
     MultipleOperatingModesTypeDef,
+    ResponseMetadataTypeDef,
+    StartDataIngestionJobResponseTypeDef,
     StartInferenceSchedulerRequestRequestTypeDef,
+    StartInferenceSchedulerResponseTypeDef,
     StopInferenceSchedulerRequestRequestTypeDef,
+    StopInferenceSchedulerResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLabelGroupRequestRequestTypeDef,
     CreateDatasetRequestRequestTypeDef,
     CreateLabelGroupRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateInferenceSchedulerResponseTypeDef,
-    CreateLabelGroupResponseTypeDef,
-    CreateLabelResponseTypeDef,
-    CreateModelResponseTypeDef,
-    DescribeLabelGroupResponseTypeDef,
-    DescribeLabelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartDataIngestionJobResponseTypeDef,
-    StartInferenceSchedulerResponseTypeDef,
-    StopInferenceSchedulerResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ListDatasetsResponseTypeDef,
     ListInferenceEventsResponseTypeDef,
     IngestedFilesSummaryTypeDef,
     InferenceInputConfigurationTypeDef,
     InferenceOutputConfigurationTypeDef,
     ListInferenceSchedulersResponseTypeDef,
     IngestionInputConfigurationTypeDef,
@@ -409,43 +409,43 @@
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/README.md` & `types-aiobotocore-lookoutequipment-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lookoutequipment"></a>
 
 # types-aiobotocore-lookoutequipment
 
 [![PyPI - types-aiobotocore-lookoutequipment](https://img.shields.io/pypi/v/types-aiobotocore-lookoutequipment.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutequipment)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutequipment.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutequipment)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutequipment?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutequipment)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutEquipment 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
+[aiobotocore.LookoutEquipment 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
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
 [types-aiobotocore-lookoutequipment docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/).
 
 See how it helps to find and fix potential bugs:
 
@@ -271,33 +271,40 @@
 
 ```python
 from types_aiobotocore_lookoutequipment.type_defs import (
     CategoricalValuesTypeDef,
     CountPercentTypeDef,
     DatasetSchemaTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDatasetResponseTypeDef,
+    CreateInferenceSchedulerResponseTypeDef,
+    CreateLabelGroupResponseTypeDef,
     CreateLabelRequestRequestTypeDef,
+    CreateLabelResponseTypeDef,
     DataPreProcessingConfigurationTypeDef,
+    CreateModelResponseTypeDef,
     DuplicateTimestampsTypeDef,
     InvalidSensorDataTypeDef,
     MissingSensorDataTypeDef,
     UnsupportedTimestampsTypeDef,
     DatasetSummaryTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteInferenceSchedulerRequestRequestTypeDef,
     DeleteLabelGroupRequestRequestTypeDef,
     DeleteLabelRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
     DescribeDataIngestionJobRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeInferenceSchedulerRequestRequestTypeDef,
     DescribeLabelGroupRequestRequestTypeDef,
+    DescribeLabelGroupResponseTypeDef,
     DescribeLabelRequestRequestTypeDef,
+    DescribeLabelResponseTypeDef,
     DescribeModelRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     InferenceEventSummaryTypeDef,
     S3ObjectTypeDef,
     InferenceInputNameConfigurationTypeDef,
     InferenceS3InputConfigurationTypeDef,
     InferenceS3OutputConfigurationTypeDef,
     InferenceSchedulerSummaryTypeDef,
     IngestionS3InputConfigurationTypeDef,
@@ -316,33 +323,26 @@
     ListLabelsRequestRequestTypeDef,
     ListModelsRequestRequestTypeDef,
     ModelSummaryTypeDef,
     ListSensorStatisticsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MonotonicValuesTypeDef,
     MultipleOperatingModesTypeDef,
+    ResponseMetadataTypeDef,
+    StartDataIngestionJobResponseTypeDef,
     StartInferenceSchedulerRequestRequestTypeDef,
+    StartInferenceSchedulerResponseTypeDef,
     StopInferenceSchedulerRequestRequestTypeDef,
+    StopInferenceSchedulerResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLabelGroupRequestRequestTypeDef,
     CreateDatasetRequestRequestTypeDef,
     CreateLabelGroupRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateInferenceSchedulerResponseTypeDef,
-    CreateLabelGroupResponseTypeDef,
-    CreateLabelResponseTypeDef,
-    CreateModelResponseTypeDef,
-    DescribeLabelGroupResponseTypeDef,
-    DescribeLabelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartDataIngestionJobResponseTypeDef,
-    StartInferenceSchedulerResponseTypeDef,
-    StopInferenceSchedulerResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ListDatasetsResponseTypeDef,
     ListInferenceEventsResponseTypeDef,
     IngestedFilesSummaryTypeDef,
     InferenceInputConfigurationTypeDef,
     InferenceOutputConfigurationTypeDef,
     ListInferenceSchedulersResponseTypeDef,
     IngestionInputConfigurationTypeDef,
@@ -376,43 +376,43 @@
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/setup.py` & `types-aiobotocore-lookoutequipment-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lookoutequipment.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lookoutequipment",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lookoutequipment"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LookoutEquipment 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LookoutEquipment 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/"
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/__init__.py` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/__init__.pyi` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/__main__.py` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LookoutEquipment 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LookoutEquipment 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment\nOther"
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/client.py` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/client.pyi` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/literals.py` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/literals.py`

 * *Files 0% similar despite different names*

```diff
@@ -110,14 +110,15 @@
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
@@ -196,14 +197,15 @@
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
@@ -214,14 +216,15 @@
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
@@ -257,14 +260,15 @@
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
@@ -283,16 +287,19 @@
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
@@ -376,15 +383,17 @@
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/literals.pyi` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -108,14 +108,15 @@
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
@@ -194,14 +195,15 @@
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
@@ -212,14 +214,15 @@
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
@@ -255,14 +258,15 @@
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
@@ -281,16 +285,19 @@
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
@@ -374,15 +381,17 @@
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/type_defs.py` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -36,33 +36,40 @@
 
 
 __all__ = (
     "CategoricalValuesTypeDef",
     "CountPercentTypeDef",
     "DatasetSchemaTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "CreateInferenceSchedulerResponseTypeDef",
+    "CreateLabelGroupResponseTypeDef",
     "CreateLabelRequestRequestTypeDef",
+    "CreateLabelResponseTypeDef",
     "DataPreProcessingConfigurationTypeDef",
+    "CreateModelResponseTypeDef",
     "DuplicateTimestampsTypeDef",
     "InvalidSensorDataTypeDef",
     "MissingSensorDataTypeDef",
     "UnsupportedTimestampsTypeDef",
     "DatasetSummaryTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DeleteInferenceSchedulerRequestRequestTypeDef",
     "DeleteLabelGroupRequestRequestTypeDef",
     "DeleteLabelRequestRequestTypeDef",
     "DeleteModelRequestRequestTypeDef",
     "DescribeDataIngestionJobRequestRequestTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeInferenceSchedulerRequestRequestTypeDef",
     "DescribeLabelGroupRequestRequestTypeDef",
+    "DescribeLabelGroupResponseTypeDef",
     "DescribeLabelRequestRequestTypeDef",
+    "DescribeLabelResponseTypeDef",
     "DescribeModelRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "InferenceEventSummaryTypeDef",
     "S3ObjectTypeDef",
     "InferenceInputNameConfigurationTypeDef",
     "InferenceS3InputConfigurationTypeDef",
     "InferenceS3OutputConfigurationTypeDef",
     "InferenceSchedulerSummaryTypeDef",
     "IngestionS3InputConfigurationTypeDef",
@@ -81,33 +88,26 @@
     "ListLabelsRequestRequestTypeDef",
     "ListModelsRequestRequestTypeDef",
     "ModelSummaryTypeDef",
     "ListSensorStatisticsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MonotonicValuesTypeDef",
     "MultipleOperatingModesTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartDataIngestionJobResponseTypeDef",
     "StartInferenceSchedulerRequestRequestTypeDef",
+    "StartInferenceSchedulerResponseTypeDef",
     "StopInferenceSchedulerRequestRequestTypeDef",
+    "StopInferenceSchedulerResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateLabelGroupRequestRequestTypeDef",
     "CreateDatasetRequestRequestTypeDef",
     "CreateLabelGroupRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreateInferenceSchedulerResponseTypeDef",
-    "CreateLabelGroupResponseTypeDef",
-    "CreateLabelResponseTypeDef",
-    "CreateModelResponseTypeDef",
-    "DescribeLabelGroupResponseTypeDef",
-    "DescribeLabelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartDataIngestionJobResponseTypeDef",
-    "StartInferenceSchedulerResponseTypeDef",
-    "StopInferenceSchedulerResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ListDatasetsResponseTypeDef",
     "ListInferenceEventsResponseTypeDef",
     "IngestedFilesSummaryTypeDef",
     "InferenceInputConfigurationTypeDef",
     "InferenceOutputConfigurationTypeDef",
     "ListInferenceSchedulersResponseTypeDef",
     "IngestionInputConfigurationTypeDef",
@@ -174,22 +174,40 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DatasetName": str,
+        "DatasetArn": str,
+        "Status": DatasetStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateInferenceSchedulerResponseTypeDef = TypedDict(
+    "CreateInferenceSchedulerResponseTypeDef",
+    {
+        "InferenceSchedulerArn": str,
+        "InferenceSchedulerName": str,
+        "Status": InferenceSchedulerStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLabelGroupResponseTypeDef = TypedDict(
+    "CreateLabelGroupResponseTypeDef",
+    {
+        "LabelGroupName": str,
+        "LabelGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLabelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLabelRequestRequestTypeDef",
     {
         "LabelGroupName": str,
@@ -212,22 +230,39 @@
 
 class CreateLabelRequestRequestTypeDef(
     _RequiredCreateLabelRequestRequestTypeDef, _OptionalCreateLabelRequestRequestTypeDef
 ):
     pass
 
 
+CreateLabelResponseTypeDef = TypedDict(
+    "CreateLabelResponseTypeDef",
+    {
+        "LabelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataPreProcessingConfigurationTypeDef = TypedDict(
     "DataPreProcessingConfigurationTypeDef",
     {
         "TargetSamplingRate": TargetSamplingRateType,
     },
     total=False,
 )
 
+CreateModelResponseTypeDef = TypedDict(
+    "CreateModelResponseTypeDef",
+    {
+        "ModelArn": str,
+        "Status": ModelStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DuplicateTimestampsTypeDef = TypedDict(
     "DuplicateTimestampsTypeDef",
     {
         "TotalNumberOfDuplicateTimestamps": int,
     },
 )
 
@@ -325,29 +360,65 @@
 DescribeLabelGroupRequestRequestTypeDef = TypedDict(
     "DescribeLabelGroupRequestRequestTypeDef",
     {
         "LabelGroupName": str,
     },
 )
 
+DescribeLabelGroupResponseTypeDef = TypedDict(
+    "DescribeLabelGroupResponseTypeDef",
+    {
+        "LabelGroupName": str,
+        "LabelGroupArn": str,
+        "FaultCodes": List[str],
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeLabelRequestRequestTypeDef = TypedDict(
     "DescribeLabelRequestRequestTypeDef",
     {
         "LabelGroupName": str,
         "LabelId": str,
     },
 )
 
+DescribeLabelResponseTypeDef = TypedDict(
+    "DescribeLabelResponseTypeDef",
+    {
+        "LabelGroupName": str,
+        "LabelGroupArn": str,
+        "LabelId": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "Rating": LabelRatingType,
+        "FaultCode": str,
+        "Notes": str,
+        "Equipment": str,
+        "CreatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeModelRequestRequestTypeDef = TypedDict(
     "DescribeModelRequestRequestTypeDef",
     {
         "ModelName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InferenceEventSummaryTypeDef = TypedDict(
     "InferenceEventSummaryTypeDef",
     {
         "InferenceSchedulerArn": str,
         "InferenceSchedulerName": str,
         "EventStartTime": datetime,
         "EventEndTime": datetime,
@@ -735,28 +806,72 @@
 MultipleOperatingModesTypeDef = TypedDict(
     "MultipleOperatingModesTypeDef",
     {
         "Status": StatisticalIssueStatusType,
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
+StartDataIngestionJobResponseTypeDef = TypedDict(
+    "StartDataIngestionJobResponseTypeDef",
+    {
+        "JobId": str,
+        "Status": IngestionJobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartInferenceSchedulerRequestRequestTypeDef = TypedDict(
     "StartInferenceSchedulerRequestRequestTypeDef",
     {
         "InferenceSchedulerName": str,
     },
 )
 
+StartInferenceSchedulerResponseTypeDef = TypedDict(
+    "StartInferenceSchedulerResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ModelName": str,
+        "InferenceSchedulerName": str,
+        "InferenceSchedulerArn": str,
+        "Status": InferenceSchedulerStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopInferenceSchedulerRequestRequestTypeDef = TypedDict(
     "StopInferenceSchedulerRequestRequestTypeDef",
     {
         "InferenceSchedulerName": str,
     },
 )
 
+StopInferenceSchedulerResponseTypeDef = TypedDict(
+    "StopInferenceSchedulerResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ModelName": str,
+        "InferenceSchedulerName": str,
+        "InferenceSchedulerArn": str,
+        "Status": InferenceSchedulerStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -825,160 +940,45 @@
 
 class CreateLabelGroupRequestRequestTypeDef(
     _RequiredCreateLabelGroupRequestRequestTypeDef, _OptionalCreateLabelGroupRequestRequestTypeDef
 ):
     pass
 
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
-    {
-        "DatasetName": str,
-        "DatasetArn": str,
-        "Status": DatasetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateInferenceSchedulerResponseTypeDef = TypedDict(
-    "CreateInferenceSchedulerResponseTypeDef",
-    {
-        "InferenceSchedulerArn": str,
-        "InferenceSchedulerName": str,
-        "Status": InferenceSchedulerStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLabelGroupResponseTypeDef = TypedDict(
-    "CreateLabelGroupResponseTypeDef",
-    {
-        "LabelGroupName": str,
-        "LabelGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLabelResponseTypeDef = TypedDict(
-    "CreateLabelResponseTypeDef",
-    {
-        "LabelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelResponseTypeDef = TypedDict(
-    "CreateModelResponseTypeDef",
-    {
-        "ModelArn": str,
-        "Status": ModelStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLabelGroupResponseTypeDef = TypedDict(
-    "DescribeLabelGroupResponseTypeDef",
-    {
-        "LabelGroupName": str,
-        "LabelGroupArn": str,
-        "FaultCodes": List[str],
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLabelResponseTypeDef = TypedDict(
-    "DescribeLabelResponseTypeDef",
-    {
-        "LabelGroupName": str,
-        "LabelGroupArn": str,
-        "LabelId": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "Rating": LabelRatingType,
-        "FaultCode": str,
-        "Notes": str,
-        "Equipment": str,
-        "CreatedAt": datetime,
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataIngestionJobResponseTypeDef = TypedDict(
-    "StartDataIngestionJobResponseTypeDef",
-    {
-        "JobId": str,
-        "Status": IngestionJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartInferenceSchedulerResponseTypeDef = TypedDict(
-    "StartInferenceSchedulerResponseTypeDef",
-    {
-        "ModelArn": str,
-        "ModelName": str,
-        "InferenceSchedulerName": str,
-        "InferenceSchedulerArn": str,
-        "Status": InferenceSchedulerStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopInferenceSchedulerResponseTypeDef = TypedDict(
-    "StopInferenceSchedulerResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ModelArn": str,
-        "ModelName": str,
-        "InferenceSchedulerName": str,
-        "InferenceSchedulerArn": str,
-        "Status": InferenceSchedulerStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "NextToken": str,
         "DatasetSummaries": List[DatasetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInferenceEventsResponseTypeDef = TypedDict(
     "ListInferenceEventsResponseTypeDef",
     {
         "NextToken": str,
         "InferenceEventSummaries": List[InferenceEventSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIngestedFilesSummaryTypeDef = TypedDict(
     "_RequiredIngestedFilesSummaryTypeDef",
     {
         "TotalNumberOfFiles": int,
@@ -1032,15 +1032,15 @@
 
 
 ListInferenceSchedulersResponseTypeDef = TypedDict(
     "ListInferenceSchedulersResponseTypeDef",
     {
         "NextToken": str,
         "InferenceSchedulerSummaries": List[InferenceSchedulerSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IngestionInputConfigurationTypeDef = TypedDict(
     "IngestionInputConfigurationTypeDef",
     {
         "S3InputConfiguration": IngestionS3InputConfigurationTypeDef,
@@ -1056,24 +1056,24 @@
 )
 
 ListLabelGroupsResponseTypeDef = TypedDict(
     "ListLabelGroupsResponseTypeDef",
     {
         "NextToken": str,
         "LabelGroupSummaries": List[LabelGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLabelsResponseTypeDef = TypedDict(
     "ListLabelsResponseTypeDef",
     {
         "NextToken": str,
         "LabelSummaries": List[LabelSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LabelsInputConfigurationTypeDef = TypedDict(
     "LabelsInputConfigurationTypeDef",
     {
         "S3InputConfiguration": LabelsS3InputConfigurationTypeDef,
@@ -1083,15 +1083,15 @@
 )
 
 ListModelsResponseTypeDef = TypedDict(
     "ListModelsResponseTypeDef",
     {
         "NextToken": str,
         "ModelSummaries": List[ModelSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SensorStatisticsSummaryTypeDef = TypedDict(
     "SensorStatisticsSummaryTypeDef",
     {
         "ComponentName": str,
@@ -1154,15 +1154,15 @@
         "CreatedAt": datetime,
         "UpdatedAt": datetime,
         "DataInputConfiguration": InferenceInputConfigurationTypeDef,
         "DataOutputConfiguration": InferenceOutputConfigurationTypeDef,
         "RoleArn": str,
         "ServerSideKmsKeyId": str,
         "LatestInferenceResult": LatestInferenceResultType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferenceExecutionSummaryTypeDef = TypedDict(
     "InferenceExecutionSummaryTypeDef",
     {
         "ModelName": str,
@@ -1293,42 +1293,42 @@
         "TrainingExecutionEndTime": datetime,
         "FailedReason": str,
         "ModelMetrics": str,
         "LastUpdatedTime": datetime,
         "CreatedAt": datetime,
         "ServerSideKmsKeyId": str,
         "OffCondition": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSensorStatisticsResponseTypeDef = TypedDict(
     "ListSensorStatisticsResponseTypeDef",
     {
         "SensorStatisticsSummaries": List[SensorStatisticsSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInferenceExecutionsResponseTypeDef = TypedDict(
     "ListInferenceExecutionsResponseTypeDef",
     {
         "NextToken": str,
         "InferenceExecutionSummaries": List[InferenceExecutionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataIngestionJobsResponseTypeDef = TypedDict(
     "ListDataIngestionJobsResponseTypeDef",
     {
         "NextToken": str,
         "DataIngestionJobSummaries": List[DataIngestionJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataIngestionJobResponseTypeDef = TypedDict(
     "DescribeDataIngestionJobResponseTypeDef",
     {
         "JobId": str,
@@ -1340,15 +1340,15 @@
         "FailedReason": str,
         "DataQualitySummary": DataQualitySummaryTypeDef,
         "IngestedFilesSummary": IngestedFilesSummaryTypeDef,
         "StatusDetail": str,
         "IngestedDataSize": int,
         "DataStartTime": datetime,
         "DataEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "DatasetName": str,
@@ -1360,10 +1360,10 @@
         "ServerSideKmsKeyId": str,
         "IngestionInputConfiguration": IngestionInputConfigurationTypeDef,
         "DataQualitySummary": DataQualitySummaryTypeDef,
         "IngestedFilesSummary": IngestedFilesSummaryTypeDef,
         "RoleArn": str,
         "DataStartTime": datetime,
         "DataEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment/type_defs.pyi` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -35,33 +35,40 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "CategoricalValuesTypeDef",
     "CountPercentTypeDef",
     "DatasetSchemaTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "CreateInferenceSchedulerResponseTypeDef",
+    "CreateLabelGroupResponseTypeDef",
     "CreateLabelRequestRequestTypeDef",
+    "CreateLabelResponseTypeDef",
     "DataPreProcessingConfigurationTypeDef",
+    "CreateModelResponseTypeDef",
     "DuplicateTimestampsTypeDef",
     "InvalidSensorDataTypeDef",
     "MissingSensorDataTypeDef",
     "UnsupportedTimestampsTypeDef",
     "DatasetSummaryTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DeleteInferenceSchedulerRequestRequestTypeDef",
     "DeleteLabelGroupRequestRequestTypeDef",
     "DeleteLabelRequestRequestTypeDef",
     "DeleteModelRequestRequestTypeDef",
     "DescribeDataIngestionJobRequestRequestTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeInferenceSchedulerRequestRequestTypeDef",
     "DescribeLabelGroupRequestRequestTypeDef",
+    "DescribeLabelGroupResponseTypeDef",
     "DescribeLabelRequestRequestTypeDef",
+    "DescribeLabelResponseTypeDef",
     "DescribeModelRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "InferenceEventSummaryTypeDef",
     "S3ObjectTypeDef",
     "InferenceInputNameConfigurationTypeDef",
     "InferenceS3InputConfigurationTypeDef",
     "InferenceS3OutputConfigurationTypeDef",
     "InferenceSchedulerSummaryTypeDef",
     "IngestionS3InputConfigurationTypeDef",
@@ -80,33 +87,26 @@
     "ListLabelsRequestRequestTypeDef",
     "ListModelsRequestRequestTypeDef",
     "ModelSummaryTypeDef",
     "ListSensorStatisticsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MonotonicValuesTypeDef",
     "MultipleOperatingModesTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartDataIngestionJobResponseTypeDef",
     "StartInferenceSchedulerRequestRequestTypeDef",
+    "StartInferenceSchedulerResponseTypeDef",
     "StopInferenceSchedulerRequestRequestTypeDef",
+    "StopInferenceSchedulerResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateLabelGroupRequestRequestTypeDef",
     "CreateDatasetRequestRequestTypeDef",
     "CreateLabelGroupRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreateInferenceSchedulerResponseTypeDef",
-    "CreateLabelGroupResponseTypeDef",
-    "CreateLabelResponseTypeDef",
-    "CreateModelResponseTypeDef",
-    "DescribeLabelGroupResponseTypeDef",
-    "DescribeLabelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartDataIngestionJobResponseTypeDef",
-    "StartInferenceSchedulerResponseTypeDef",
-    "StopInferenceSchedulerResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ListDatasetsResponseTypeDef",
     "ListInferenceEventsResponseTypeDef",
     "IngestedFilesSummaryTypeDef",
     "InferenceInputConfigurationTypeDef",
     "InferenceOutputConfigurationTypeDef",
     "ListInferenceSchedulersResponseTypeDef",
     "IngestionInputConfigurationTypeDef",
@@ -171,22 +171,40 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "DatasetName": str,
+        "DatasetArn": str,
+        "Status": DatasetStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateInferenceSchedulerResponseTypeDef = TypedDict(
+    "CreateInferenceSchedulerResponseTypeDef",
+    {
+        "InferenceSchedulerArn": str,
+        "InferenceSchedulerName": str,
+        "Status": InferenceSchedulerStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLabelGroupResponseTypeDef = TypedDict(
+    "CreateLabelGroupResponseTypeDef",
+    {
+        "LabelGroupName": str,
+        "LabelGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLabelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLabelRequestRequestTypeDef",
     {
         "LabelGroupName": str,
@@ -207,22 +225,39 @@
 )
 
 class CreateLabelRequestRequestTypeDef(
     _RequiredCreateLabelRequestRequestTypeDef, _OptionalCreateLabelRequestRequestTypeDef
 ):
     pass
 
+CreateLabelResponseTypeDef = TypedDict(
+    "CreateLabelResponseTypeDef",
+    {
+        "LabelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataPreProcessingConfigurationTypeDef = TypedDict(
     "DataPreProcessingConfigurationTypeDef",
     {
         "TargetSamplingRate": TargetSamplingRateType,
     },
     total=False,
 )
 
+CreateModelResponseTypeDef = TypedDict(
+    "CreateModelResponseTypeDef",
+    {
+        "ModelArn": str,
+        "Status": ModelStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DuplicateTimestampsTypeDef = TypedDict(
     "DuplicateTimestampsTypeDef",
     {
         "TotalNumberOfDuplicateTimestamps": int,
     },
 )
 
@@ -320,29 +355,65 @@
 DescribeLabelGroupRequestRequestTypeDef = TypedDict(
     "DescribeLabelGroupRequestRequestTypeDef",
     {
         "LabelGroupName": str,
     },
 )
 
+DescribeLabelGroupResponseTypeDef = TypedDict(
+    "DescribeLabelGroupResponseTypeDef",
+    {
+        "LabelGroupName": str,
+        "LabelGroupArn": str,
+        "FaultCodes": List[str],
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeLabelRequestRequestTypeDef = TypedDict(
     "DescribeLabelRequestRequestTypeDef",
     {
         "LabelGroupName": str,
         "LabelId": str,
     },
 )
 
+DescribeLabelResponseTypeDef = TypedDict(
+    "DescribeLabelResponseTypeDef",
+    {
+        "LabelGroupName": str,
+        "LabelGroupArn": str,
+        "LabelId": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "Rating": LabelRatingType,
+        "FaultCode": str,
+        "Notes": str,
+        "Equipment": str,
+        "CreatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeModelRequestRequestTypeDef = TypedDict(
     "DescribeModelRequestRequestTypeDef",
     {
         "ModelName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InferenceEventSummaryTypeDef = TypedDict(
     "InferenceEventSummaryTypeDef",
     {
         "InferenceSchedulerArn": str,
         "InferenceSchedulerName": str,
         "EventStartTime": datetime,
         "EventEndTime": datetime,
@@ -710,28 +781,72 @@
 MultipleOperatingModesTypeDef = TypedDict(
     "MultipleOperatingModesTypeDef",
     {
         "Status": StatisticalIssueStatusType,
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
+StartDataIngestionJobResponseTypeDef = TypedDict(
+    "StartDataIngestionJobResponseTypeDef",
+    {
+        "JobId": str,
+        "Status": IngestionJobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartInferenceSchedulerRequestRequestTypeDef = TypedDict(
     "StartInferenceSchedulerRequestRequestTypeDef",
     {
         "InferenceSchedulerName": str,
     },
 )
 
+StartInferenceSchedulerResponseTypeDef = TypedDict(
+    "StartInferenceSchedulerResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ModelName": str,
+        "InferenceSchedulerName": str,
+        "InferenceSchedulerArn": str,
+        "Status": InferenceSchedulerStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopInferenceSchedulerRequestRequestTypeDef = TypedDict(
     "StopInferenceSchedulerRequestRequestTypeDef",
     {
         "InferenceSchedulerName": str,
     },
 )
 
+StopInferenceSchedulerResponseTypeDef = TypedDict(
+    "StopInferenceSchedulerResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ModelName": str,
+        "InferenceSchedulerName": str,
+        "InferenceSchedulerArn": str,
+        "Status": InferenceSchedulerStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -794,160 +909,45 @@
 )
 
 class CreateLabelGroupRequestRequestTypeDef(
     _RequiredCreateLabelGroupRequestRequestTypeDef, _OptionalCreateLabelGroupRequestRequestTypeDef
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
-    {
-        "DatasetName": str,
-        "DatasetArn": str,
-        "Status": DatasetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateInferenceSchedulerResponseTypeDef = TypedDict(
-    "CreateInferenceSchedulerResponseTypeDef",
-    {
-        "InferenceSchedulerArn": str,
-        "InferenceSchedulerName": str,
-        "Status": InferenceSchedulerStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLabelGroupResponseTypeDef = TypedDict(
-    "CreateLabelGroupResponseTypeDef",
-    {
-        "LabelGroupName": str,
-        "LabelGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLabelResponseTypeDef = TypedDict(
-    "CreateLabelResponseTypeDef",
-    {
-        "LabelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelResponseTypeDef = TypedDict(
-    "CreateModelResponseTypeDef",
-    {
-        "ModelArn": str,
-        "Status": ModelStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLabelGroupResponseTypeDef = TypedDict(
-    "DescribeLabelGroupResponseTypeDef",
-    {
-        "LabelGroupName": str,
-        "LabelGroupArn": str,
-        "FaultCodes": List[str],
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLabelResponseTypeDef = TypedDict(
-    "DescribeLabelResponseTypeDef",
-    {
-        "LabelGroupName": str,
-        "LabelGroupArn": str,
-        "LabelId": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "Rating": LabelRatingType,
-        "FaultCode": str,
-        "Notes": str,
-        "Equipment": str,
-        "CreatedAt": datetime,
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataIngestionJobResponseTypeDef = TypedDict(
-    "StartDataIngestionJobResponseTypeDef",
-    {
-        "JobId": str,
-        "Status": IngestionJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartInferenceSchedulerResponseTypeDef = TypedDict(
-    "StartInferenceSchedulerResponseTypeDef",
-    {
-        "ModelArn": str,
-        "ModelName": str,
-        "InferenceSchedulerName": str,
-        "InferenceSchedulerArn": str,
-        "Status": InferenceSchedulerStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopInferenceSchedulerResponseTypeDef = TypedDict(
-    "StopInferenceSchedulerResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ModelArn": str,
-        "ModelName": str,
-        "InferenceSchedulerName": str,
-        "InferenceSchedulerArn": str,
-        "Status": InferenceSchedulerStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "NextToken": str,
         "DatasetSummaries": List[DatasetSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInferenceEventsResponseTypeDef = TypedDict(
     "ListInferenceEventsResponseTypeDef",
     {
         "NextToken": str,
         "InferenceEventSummaries": List[InferenceEventSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIngestedFilesSummaryTypeDef = TypedDict(
     "_RequiredIngestedFilesSummaryTypeDef",
     {
         "TotalNumberOfFiles": int,
@@ -997,15 +997,15 @@
     pass
 
 ListInferenceSchedulersResponseTypeDef = TypedDict(
     "ListInferenceSchedulersResponseTypeDef",
     {
         "NextToken": str,
         "InferenceSchedulerSummaries": List[InferenceSchedulerSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IngestionInputConfigurationTypeDef = TypedDict(
     "IngestionInputConfigurationTypeDef",
     {
         "S3InputConfiguration": IngestionS3InputConfigurationTypeDef,
@@ -1021,24 +1021,24 @@
 )
 
 ListLabelGroupsResponseTypeDef = TypedDict(
     "ListLabelGroupsResponseTypeDef",
     {
         "NextToken": str,
         "LabelGroupSummaries": List[LabelGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLabelsResponseTypeDef = TypedDict(
     "ListLabelsResponseTypeDef",
     {
         "NextToken": str,
         "LabelSummaries": List[LabelSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LabelsInputConfigurationTypeDef = TypedDict(
     "LabelsInputConfigurationTypeDef",
     {
         "S3InputConfiguration": LabelsS3InputConfigurationTypeDef,
@@ -1048,15 +1048,15 @@
 )
 
 ListModelsResponseTypeDef = TypedDict(
     "ListModelsResponseTypeDef",
     {
         "NextToken": str,
         "ModelSummaries": List[ModelSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SensorStatisticsSummaryTypeDef = TypedDict(
     "SensorStatisticsSummaryTypeDef",
     {
         "ComponentName": str,
@@ -1117,15 +1117,15 @@
         "CreatedAt": datetime,
         "UpdatedAt": datetime,
         "DataInputConfiguration": InferenceInputConfigurationTypeDef,
         "DataOutputConfiguration": InferenceOutputConfigurationTypeDef,
         "RoleArn": str,
         "ServerSideKmsKeyId": str,
         "LatestInferenceResult": LatestInferenceResultType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferenceExecutionSummaryTypeDef = TypedDict(
     "InferenceExecutionSummaryTypeDef",
     {
         "ModelName": str,
@@ -1252,42 +1252,42 @@
         "TrainingExecutionEndTime": datetime,
         "FailedReason": str,
         "ModelMetrics": str,
         "LastUpdatedTime": datetime,
         "CreatedAt": datetime,
         "ServerSideKmsKeyId": str,
         "OffCondition": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSensorStatisticsResponseTypeDef = TypedDict(
     "ListSensorStatisticsResponseTypeDef",
     {
         "SensorStatisticsSummaries": List[SensorStatisticsSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInferenceExecutionsResponseTypeDef = TypedDict(
     "ListInferenceExecutionsResponseTypeDef",
     {
         "NextToken": str,
         "InferenceExecutionSummaries": List[InferenceExecutionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataIngestionJobsResponseTypeDef = TypedDict(
     "ListDataIngestionJobsResponseTypeDef",
     {
         "NextToken": str,
         "DataIngestionJobSummaries": List[DataIngestionJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataIngestionJobResponseTypeDef = TypedDict(
     "DescribeDataIngestionJobResponseTypeDef",
     {
         "JobId": str,
@@ -1299,15 +1299,15 @@
         "FailedReason": str,
         "DataQualitySummary": DataQualitySummaryTypeDef,
         "IngestedFilesSummary": IngestedFilesSummaryTypeDef,
         "StatusDetail": str,
         "IngestedDataSize": int,
         "DataStartTime": datetime,
         "DataEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "DatasetName": str,
@@ -1319,10 +1319,10 @@
         "ServerSideKmsKeyId": str,
         "IngestionInputConfiguration": IngestionInputConfigurationTypeDef,
         "DataQualitySummary": DataQualitySummaryTypeDef,
         "IngestedFilesSummary": IngestedFilesSummaryTypeDef,
         "RoleArn": str,
         "DataStartTime": datetime,
         "DataEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/PKG-INFO` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lookoutequipment
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LookoutEquipment 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LookoutEquipment 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lookoutequipment"></a>
 
 # types-aiobotocore-lookoutequipment
 
 [![PyPI - types-aiobotocore-lookoutequipment](https://img.shields.io/pypi/v/types-aiobotocore-lookoutequipment.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutequipment)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutequipment.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutequipment)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutequipment?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutequipment)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutEquipment 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
+[aiobotocore.LookoutEquipment 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutequipment.html#LookoutEquipment)
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
 [types-aiobotocore-lookoutequipment docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutequipment/).
 
 See how it helps to find and fix potential bugs:
 
@@ -304,33 +304,40 @@
 
 ```python
 from types_aiobotocore_lookoutequipment.type_defs import (
     CategoricalValuesTypeDef,
     CountPercentTypeDef,
     DatasetSchemaTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDatasetResponseTypeDef,
+    CreateInferenceSchedulerResponseTypeDef,
+    CreateLabelGroupResponseTypeDef,
     CreateLabelRequestRequestTypeDef,
+    CreateLabelResponseTypeDef,
     DataPreProcessingConfigurationTypeDef,
+    CreateModelResponseTypeDef,
     DuplicateTimestampsTypeDef,
     InvalidSensorDataTypeDef,
     MissingSensorDataTypeDef,
     UnsupportedTimestampsTypeDef,
     DatasetSummaryTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DeleteInferenceSchedulerRequestRequestTypeDef,
     DeleteLabelGroupRequestRequestTypeDef,
     DeleteLabelRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
     DescribeDataIngestionJobRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeInferenceSchedulerRequestRequestTypeDef,
     DescribeLabelGroupRequestRequestTypeDef,
+    DescribeLabelGroupResponseTypeDef,
     DescribeLabelRequestRequestTypeDef,
+    DescribeLabelResponseTypeDef,
     DescribeModelRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     InferenceEventSummaryTypeDef,
     S3ObjectTypeDef,
     InferenceInputNameConfigurationTypeDef,
     InferenceS3InputConfigurationTypeDef,
     InferenceS3OutputConfigurationTypeDef,
     InferenceSchedulerSummaryTypeDef,
     IngestionS3InputConfigurationTypeDef,
@@ -349,33 +356,26 @@
     ListLabelsRequestRequestTypeDef,
     ListModelsRequestRequestTypeDef,
     ModelSummaryTypeDef,
     ListSensorStatisticsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MonotonicValuesTypeDef,
     MultipleOperatingModesTypeDef,
+    ResponseMetadataTypeDef,
+    StartDataIngestionJobResponseTypeDef,
     StartInferenceSchedulerRequestRequestTypeDef,
+    StartInferenceSchedulerResponseTypeDef,
     StopInferenceSchedulerRequestRequestTypeDef,
+    StopInferenceSchedulerResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLabelGroupRequestRequestTypeDef,
     CreateDatasetRequestRequestTypeDef,
     CreateLabelGroupRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateInferenceSchedulerResponseTypeDef,
-    CreateLabelGroupResponseTypeDef,
-    CreateLabelResponseTypeDef,
-    CreateModelResponseTypeDef,
-    DescribeLabelGroupResponseTypeDef,
-    DescribeLabelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartDataIngestionJobResponseTypeDef,
-    StartInferenceSchedulerResponseTypeDef,
-    StopInferenceSchedulerResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ListDatasetsResponseTypeDef,
     ListInferenceEventsResponseTypeDef,
     IngestedFilesSummaryTypeDef,
     InferenceInputConfigurationTypeDef,
     InferenceOutputConfigurationTypeDef,
     ListInferenceSchedulersResponseTypeDef,
     IngestionInputConfigurationTypeDef,
@@ -409,43 +409,43 @@
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

### Comparing `types-aiobotocore-lookoutequipment-2.5.0.post1/types_aiobotocore_lookoutequipment.egg-info/SOURCES.txt` & `types-aiobotocore-lookoutequipment-2.5.1/types_aiobotocore_lookoutequipment.egg-info/SOURCES.txt`

 * *Files identical despite different names*

