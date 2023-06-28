# Comparing `tmp/types-aiobotocore-datapipeline-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-datapipeline-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-datapipeline-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-datapipeline-2.5.1.tar", last modified: Wed Jun 28 01:43:22 2023, max compression
```

## Comparing `types-aiobotocore-datapipeline-2.5.0.post1.tar` & `types-aiobotocore-datapipeline-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.503120 types-aiobotocore-datapipeline-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15266 2023-03-11 12:26:29.499120 types-aiobotocore-datapipeline-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13675 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:29.503120 types-aiobotocore-datapipeline-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.499120 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/
--rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1061 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18109 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18078 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8022 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8020 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4549 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4543 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    17893 2023-03-11 12:12:14.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17861 2023-03-11 12:12:13.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:12.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.499120 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15266 2023-03-11 12:26:29.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:29.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:29.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:29.000000 types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.038123 types-aiobotocore-datapipeline-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15263 2023-06-28 01:43:22.038123 types-aiobotocore-datapipeline-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13678 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:22.038123 types-aiobotocore-datapipeline-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.030122 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/
+-rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1061 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18109 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18078 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8231 2023-06-28 01:28:52.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8229 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4435 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4430 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    17925 2023-06-28 01:28:52.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17893 2023-06-28 01:28:52.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:51.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.038123 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15263 2023-06-28 01:43:21.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:21.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:21.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:21.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:21.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:21.000000 types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/LICENSE` & `types-aiobotocore-datapipeline-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/PKG-INFO` & `types-aiobotocore-datapipeline-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-datapipeline
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DataPipeline 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DataPipeline 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-datapipeline"></a>
 
 # types-aiobotocore-datapipeline
 
 [![PyPI - types-aiobotocore-datapipeline](https://img.shields.io/pypi/v/types-aiobotocore-datapipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-datapipeline)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-datapipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-datapipeline)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-datapipeline?color=blue)](https://pypistats.org/packages/types-aiobotocore-datapipeline)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DataPipeline 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline)
+[aiobotocore.DataPipeline 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline)
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
 [types-aiobotocore-datapipeline docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/).
 
 See how it helps to find and fix potential bugs:
 
@@ -326,45 +326,45 @@
 `types_aiobotocore_datapipeline.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_datapipeline.type_defs import (
     ParameterValueTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreatePipelineOutputTypeDef,
     DeactivatePipelineInputRequestTypeDef,
     DeletePipelineInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeObjectsInputDescribeObjectsPaginateTypeDef,
     DescribeObjectsInputRequestTypeDef,
     DescribePipelinesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluateExpressionInputRequestTypeDef,
+    EvaluateExpressionOutputTypeDef,
     FieldTypeDef,
     GetPipelineDefinitionInputRequestTypeDef,
     InstanceIdentityTypeDef,
+    ListPipelinesInputListPipelinesPaginateTypeDef,
     ListPipelinesInputRequestTypeDef,
     PipelineIdNameTypeDef,
     OperatorTypeDef,
+    PaginatorConfigTypeDef,
     ParameterAttributeTypeDef,
     ValidationErrorTypeDef,
     ValidationWarningTypeDef,
+    QueryObjectsOutputTypeDef,
     RemoveTagsInputRequestTypeDef,
+    ReportTaskProgressOutputTypeDef,
     ReportTaskRunnerHeartbeatInputRequestTypeDef,
+    ReportTaskRunnerHeartbeatOutputTypeDef,
+    ResponseMetadataTypeDef,
     SetStatusInputRequestTypeDef,
     SetTaskStatusInputRequestTypeDef,
     ActivatePipelineInputRequestTypeDef,
     AddTagsInputRequestTypeDef,
     CreatePipelineInputRequestTypeDef,
-    CreatePipelineOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EvaluateExpressionOutputTypeDef,
-    QueryObjectsOutputTypeDef,
-    ReportTaskProgressOutputTypeDef,
-    ReportTaskRunnerHeartbeatOutputTypeDef,
-    DescribeObjectsInputDescribeObjectsPaginateTypeDef,
-    ListPipelinesInputListPipelinesPaginateTypeDef,
     PipelineDescriptionTypeDef,
     PipelineObjectTypeDef,
     ReportTaskProgressInputRequestTypeDef,
     PollForTaskInputRequestTypeDef,
     ListPipelinesOutputTypeDef,
     SelectorTypeDef,
     ParameterObjectTypeDef,
@@ -390,43 +390,43 @@
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/README.md` & `types-aiobotocore-datapipeline-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-datapipeline"></a>
 
 # types-aiobotocore-datapipeline
 
 [![PyPI - types-aiobotocore-datapipeline](https://img.shields.io/pypi/v/types-aiobotocore-datapipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-datapipeline)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-datapipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-datapipeline)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-datapipeline?color=blue)](https://pypistats.org/packages/types-aiobotocore-datapipeline)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DataPipeline 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline)
+[aiobotocore.DataPipeline 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline)
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
 [types-aiobotocore-datapipeline docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,45 +293,45 @@
 `types_aiobotocore_datapipeline.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_datapipeline.type_defs import (
     ParameterValueTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreatePipelineOutputTypeDef,
     DeactivatePipelineInputRequestTypeDef,
     DeletePipelineInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeObjectsInputDescribeObjectsPaginateTypeDef,
     DescribeObjectsInputRequestTypeDef,
     DescribePipelinesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluateExpressionInputRequestTypeDef,
+    EvaluateExpressionOutputTypeDef,
     FieldTypeDef,
     GetPipelineDefinitionInputRequestTypeDef,
     InstanceIdentityTypeDef,
+    ListPipelinesInputListPipelinesPaginateTypeDef,
     ListPipelinesInputRequestTypeDef,
     PipelineIdNameTypeDef,
     OperatorTypeDef,
+    PaginatorConfigTypeDef,
     ParameterAttributeTypeDef,
     ValidationErrorTypeDef,
     ValidationWarningTypeDef,
+    QueryObjectsOutputTypeDef,
     RemoveTagsInputRequestTypeDef,
+    ReportTaskProgressOutputTypeDef,
     ReportTaskRunnerHeartbeatInputRequestTypeDef,
+    ReportTaskRunnerHeartbeatOutputTypeDef,
+    ResponseMetadataTypeDef,
     SetStatusInputRequestTypeDef,
     SetTaskStatusInputRequestTypeDef,
     ActivatePipelineInputRequestTypeDef,
     AddTagsInputRequestTypeDef,
     CreatePipelineInputRequestTypeDef,
-    CreatePipelineOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EvaluateExpressionOutputTypeDef,
-    QueryObjectsOutputTypeDef,
-    ReportTaskProgressOutputTypeDef,
-    ReportTaskRunnerHeartbeatOutputTypeDef,
-    DescribeObjectsInputDescribeObjectsPaginateTypeDef,
-    ListPipelinesInputListPipelinesPaginateTypeDef,
     PipelineDescriptionTypeDef,
     PipelineObjectTypeDef,
     ReportTaskProgressInputRequestTypeDef,
     PollForTaskInputRequestTypeDef,
     ListPipelinesOutputTypeDef,
     SelectorTypeDef,
     ParameterObjectTypeDef,
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/setup.py` & `types-aiobotocore-datapipeline-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-datapipeline.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-datapipeline",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_datapipeline"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DataPipeline 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DataPipeline 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/"
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/__init__.py` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/__init__.pyi` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/__main__.py` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/__main__.py`

 * *Files 23% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DataPipeline 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DataPipeline 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline\nOther"
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/client.py` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/client.pyi` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/literals.py` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/literals.pyi` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/paginator.py` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,93 +20,81 @@
         client: DataPipelineClient
 
         describe_objects_paginator: DescribeObjectsPaginator = client.get_paginator("describe_objects")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
         query_objects_paginator: QueryObjectsPaginator = client.get_paginator("query_objects")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeObjectsOutputTypeDef,
     ListPipelinesOutputTypeDef,
     PaginatorConfigTypeDef,
     QueryObjectsOutputTypeDef,
     QueryTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeObjectsPaginator", "ListPipelinesPaginator", "QueryObjectsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeObjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.DescribeObjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#describeobjectspaginator)
     """
 
     def paginate(
         self,
         *,
         pipelineId: str,
         objectIds: Sequence[str],
         evaluateExpressions: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeObjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.DescribeObjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#describeobjectspaginator)
         """
 
-
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#listpipelinespaginator)
         """
 
-
 class QueryObjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.QueryObjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#queryobjectspaginator)
     """
 
     def paginate(
         self,
         *,
         pipelineId: str,
         sphere: str,
         query: QueryTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryObjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.QueryObjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#queryobjectspaginator)
         """
```

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/paginator.pyi` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,87 +20,86 @@
         client: DataPipelineClient
 
         describe_objects_paginator: DescribeObjectsPaginator = client.get_paginator("describe_objects")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
         query_objects_paginator: QueryObjectsPaginator = client.get_paginator("query_objects")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeObjectsOutputTypeDef,
     ListPipelinesOutputTypeDef,
     PaginatorConfigTypeDef,
     QueryObjectsOutputTypeDef,
     QueryTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeObjectsPaginator", "ListPipelinesPaginator", "QueryObjectsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeObjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.DescribeObjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#describeobjectspaginator)
     """
 
     def paginate(
         self,
         *,
         pipelineId: str,
         objectIds: Sequence[str],
         evaluateExpressions: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeObjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.DescribeObjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#describeobjectspaginator)
         """
 
+
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#listpipelinespaginator)
         """
 
+
 class QueryObjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.QueryObjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#queryobjectspaginator)
     """
 
     def paginate(
         self,
         *,
         pipelineId: str,
         sphere: str,
         query: QueryTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryObjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline.Paginator.QueryObjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/paginators/#queryobjectspaginator)
         """
```

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/type_defs.py` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,45 +22,45 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ParameterValueTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreatePipelineOutputTypeDef",
     "DeactivatePipelineInputRequestTypeDef",
     "DeletePipelineInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeObjectsInputDescribeObjectsPaginateTypeDef",
     "DescribeObjectsInputRequestTypeDef",
     "DescribePipelinesInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EvaluateExpressionInputRequestTypeDef",
+    "EvaluateExpressionOutputTypeDef",
     "FieldTypeDef",
     "GetPipelineDefinitionInputRequestTypeDef",
     "InstanceIdentityTypeDef",
+    "ListPipelinesInputListPipelinesPaginateTypeDef",
     "ListPipelinesInputRequestTypeDef",
     "PipelineIdNameTypeDef",
     "OperatorTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterAttributeTypeDef",
     "ValidationErrorTypeDef",
     "ValidationWarningTypeDef",
+    "QueryObjectsOutputTypeDef",
     "RemoveTagsInputRequestTypeDef",
+    "ReportTaskProgressOutputTypeDef",
     "ReportTaskRunnerHeartbeatInputRequestTypeDef",
+    "ReportTaskRunnerHeartbeatOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "SetStatusInputRequestTypeDef",
     "SetTaskStatusInputRequestTypeDef",
     "ActivatePipelineInputRequestTypeDef",
     "AddTagsInputRequestTypeDef",
     "CreatePipelineInputRequestTypeDef",
-    "CreatePipelineOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EvaluateExpressionOutputTypeDef",
-    "QueryObjectsOutputTypeDef",
-    "ReportTaskProgressOutputTypeDef",
-    "ReportTaskRunnerHeartbeatOutputTypeDef",
-    "DescribeObjectsInputDescribeObjectsPaginateTypeDef",
-    "ListPipelinesInputListPipelinesPaginateTypeDef",
     "PipelineDescriptionTypeDef",
     "PipelineObjectTypeDef",
     "ReportTaskProgressInputRequestTypeDef",
     "PollForTaskInputRequestTypeDef",
     "ListPipelinesOutputTypeDef",
     "SelectorTypeDef",
     "ParameterObjectTypeDef",
@@ -90,22 +90,19 @@
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreatePipelineOutputTypeDef = TypedDict(
+    "CreatePipelineOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "pipelineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeactivatePipelineInputRequestTypeDef = TypedDict(
     "_RequiredDeactivatePipelineInputRequestTypeDef",
     {
         "pipelineId": str,
@@ -129,24 +126,38 @@
 DeletePipelineInputRequestTypeDef = TypedDict(
     "DeletePipelineInputRequestTypeDef",
     {
         "pipelineId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "pipelineId": str,
+        "objectIds": Sequence[str],
+    },
+)
+_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef",
+    {
+        "evaluateExpressions": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeObjectsInputDescribeObjectsPaginateTypeDef(
+    _RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef,
+    _OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeObjectsInputRequestTypeDef = TypedDict(
     "_RequiredDescribeObjectsInputRequestTypeDef",
     {
         "pipelineId": str,
         "objectIds": Sequence[str],
     },
 )
@@ -169,23 +180,38 @@
 DescribePipelinesInputRequestTypeDef = TypedDict(
     "DescribePipelinesInputRequestTypeDef",
     {
         "pipelineIds": Sequence[str],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EvaluateExpressionInputRequestTypeDef = TypedDict(
     "EvaluateExpressionInputRequestTypeDef",
     {
         "pipelineId": str,
         "objectId": str,
         "expression": str,
     },
 )
 
+EvaluateExpressionOutputTypeDef = TypedDict(
+    "EvaluateExpressionOutputTypeDef",
+    {
+        "evaluatedExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFieldTypeDef = TypedDict(
     "_RequiredFieldTypeDef",
     {
         "key": str,
     },
 )
 _OptionalFieldTypeDef = TypedDict(
@@ -229,14 +255,22 @@
     {
         "document": str,
         "signature": str,
     },
     total=False,
 )
 
+ListPipelinesInputListPipelinesPaginateTypeDef = TypedDict(
+    "ListPipelinesInputListPipelinesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPipelinesInputRequestTypeDef = TypedDict(
     "ListPipelinesInputRequestTypeDef",
     {
         "marker": str,
     },
     total=False,
 )
@@ -255,14 +289,24 @@
     {
         "type": OperatorTypeType,
         "values": Sequence[str],
     },
     total=False,
 )
 
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
 ParameterAttributeTypeDef = TypedDict(
     "ParameterAttributeTypeDef",
     {
         "key": str,
         "stringValue": str,
     },
 )
@@ -281,22 +325,40 @@
     {
         "id": str,
         "warnings": List[str],
     },
     total=False,
 )
 
+QueryObjectsOutputTypeDef = TypedDict(
+    "QueryObjectsOutputTypeDef",
+    {
+        "ids": List[str],
+        "marker": str,
+        "hasMoreResults": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsInputRequestTypeDef = TypedDict(
     "RemoveTagsInputRequestTypeDef",
     {
         "pipelineId": str,
         "tagKeys": Sequence[str],
     },
 )
 
+ReportTaskProgressOutputTypeDef = TypedDict(
+    "ReportTaskProgressOutputTypeDef",
+    {
+        "canceled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredReportTaskRunnerHeartbeatInputRequestTypeDef = TypedDict(
     "_RequiredReportTaskRunnerHeartbeatInputRequestTypeDef",
     {
         "taskrunnerId": str,
     },
 )
 _OptionalReportTaskRunnerHeartbeatInputRequestTypeDef = TypedDict(
@@ -312,14 +374,33 @@
 class ReportTaskRunnerHeartbeatInputRequestTypeDef(
     _RequiredReportTaskRunnerHeartbeatInputRequestTypeDef,
     _OptionalReportTaskRunnerHeartbeatInputRequestTypeDef,
 ):
     pass
 
 
+ReportTaskRunnerHeartbeatOutputTypeDef = TypedDict(
+    "ReportTaskRunnerHeartbeatOutputTypeDef",
+    {
+        "terminate": bool,
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
 SetStatusInputRequestTypeDef = TypedDict(
     "SetStatusInputRequestTypeDef",
     {
         "pipelineId": str,
         "objectIds": Sequence[str],
         "status": str,
     },
@@ -398,95 +479,14 @@
 
 class CreatePipelineInputRequestTypeDef(
     _RequiredCreatePipelineInputRequestTypeDef, _OptionalCreatePipelineInputRequestTypeDef
 ):
     pass
 
 
-CreatePipelineOutputTypeDef = TypedDict(
-    "CreatePipelineOutputTypeDef",
-    {
-        "pipelineId": str,
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
-EvaluateExpressionOutputTypeDef = TypedDict(
-    "EvaluateExpressionOutputTypeDef",
-    {
-        "evaluatedExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-QueryObjectsOutputTypeDef = TypedDict(
-    "QueryObjectsOutputTypeDef",
-    {
-        "ids": List[str],
-        "marker": str,
-        "hasMoreResults": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReportTaskProgressOutputTypeDef = TypedDict(
-    "ReportTaskProgressOutputTypeDef",
-    {
-        "canceled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReportTaskRunnerHeartbeatOutputTypeDef = TypedDict(
-    "ReportTaskRunnerHeartbeatOutputTypeDef",
-    {
-        "terminate": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef",
-    {
-        "pipelineId": str,
-        "objectIds": Sequence[str],
-    },
-)
-_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef",
-    {
-        "evaluateExpressions": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeObjectsInputDescribeObjectsPaginateTypeDef(
-    _RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef,
-    _OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef,
-):
-    pass
-
-
-ListPipelinesInputListPipelinesPaginateTypeDef = TypedDict(
-    "ListPipelinesInputListPipelinesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredPipelineDescriptionTypeDef = TypedDict(
     "_RequiredPipelineDescriptionTypeDef",
     {
         "pipelineId": str,
         "name": str,
         "fields": List[FieldTypeDef],
     },
@@ -561,15 +561,15 @@
 
 ListPipelinesOutputTypeDef = TypedDict(
     "ListPipelinesOutputTypeDef",
     {
         "pipelineIdList": List[PipelineIdNameTypeDef],
         "marker": str,
         "hasMoreResults": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectorTypeDef = TypedDict(
     "SelectorTypeDef",
     {
         "fieldName": str,
@@ -588,43 +588,43 @@
 
 PutPipelineDefinitionOutputTypeDef = TypedDict(
     "PutPipelineDefinitionOutputTypeDef",
     {
         "validationErrors": List[ValidationErrorTypeDef],
         "validationWarnings": List[ValidationWarningTypeDef],
         "errored": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidatePipelineDefinitionOutputTypeDef = TypedDict(
     "ValidatePipelineDefinitionOutputTypeDef",
     {
         "validationErrors": List[ValidationErrorTypeDef],
         "validationWarnings": List[ValidationWarningTypeDef],
         "errored": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePipelinesOutputTypeDef = TypedDict(
     "DescribePipelinesOutputTypeDef",
     {
         "pipelineDescriptionList": List[PipelineDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeObjectsOutputTypeDef = TypedDict(
     "DescribeObjectsOutputTypeDef",
     {
         "pipelineObjects": List[PipelineObjectTypeDef],
         "marker": str,
         "hasMoreResults": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TaskObjectTypeDef = TypedDict(
     "TaskObjectTypeDef",
     {
         "taskId": str,
@@ -645,15 +645,15 @@
 
 GetPipelineDefinitionOutputTypeDef = TypedDict(
     "GetPipelineDefinitionOutputTypeDef",
     {
         "pipelineObjects": List[PipelineObjectTypeDef],
         "parameterObjects": List[ParameterObjectTypeDef],
         "parameterValues": List[ParameterValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutPipelineDefinitionInputRequestTypeDef = TypedDict(
     "_RequiredPutPipelineDefinitionInputRequestTypeDef",
     {
         "pipelineId": str,
@@ -701,30 +701,30 @@
     pass
 
 
 PollForTaskOutputTypeDef = TypedDict(
     "PollForTaskOutputTypeDef",
     {
         "taskObject": TaskObjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredQueryObjectsInputQueryObjectsPaginateTypeDef = TypedDict(
     "_RequiredQueryObjectsInputQueryObjectsPaginateTypeDef",
     {
         "pipelineId": str,
         "sphere": str,
     },
 )
 _OptionalQueryObjectsInputQueryObjectsPaginateTypeDef = TypedDict(
     "_OptionalQueryObjectsInputQueryObjectsPaginateTypeDef",
     {
         "query": QueryTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class QueryObjectsInputQueryObjectsPaginateTypeDef(
     _RequiredQueryObjectsInputQueryObjectsPaginateTypeDef,
```

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline/type_defs.pyi` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -21,45 +21,45 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ParameterValueTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreatePipelineOutputTypeDef",
     "DeactivatePipelineInputRequestTypeDef",
     "DeletePipelineInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeObjectsInputDescribeObjectsPaginateTypeDef",
     "DescribeObjectsInputRequestTypeDef",
     "DescribePipelinesInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EvaluateExpressionInputRequestTypeDef",
+    "EvaluateExpressionOutputTypeDef",
     "FieldTypeDef",
     "GetPipelineDefinitionInputRequestTypeDef",
     "InstanceIdentityTypeDef",
+    "ListPipelinesInputListPipelinesPaginateTypeDef",
     "ListPipelinesInputRequestTypeDef",
     "PipelineIdNameTypeDef",
     "OperatorTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterAttributeTypeDef",
     "ValidationErrorTypeDef",
     "ValidationWarningTypeDef",
+    "QueryObjectsOutputTypeDef",
     "RemoveTagsInputRequestTypeDef",
+    "ReportTaskProgressOutputTypeDef",
     "ReportTaskRunnerHeartbeatInputRequestTypeDef",
+    "ReportTaskRunnerHeartbeatOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "SetStatusInputRequestTypeDef",
     "SetTaskStatusInputRequestTypeDef",
     "ActivatePipelineInputRequestTypeDef",
     "AddTagsInputRequestTypeDef",
     "CreatePipelineInputRequestTypeDef",
-    "CreatePipelineOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EvaluateExpressionOutputTypeDef",
-    "QueryObjectsOutputTypeDef",
-    "ReportTaskProgressOutputTypeDef",
-    "ReportTaskRunnerHeartbeatOutputTypeDef",
-    "DescribeObjectsInputDescribeObjectsPaginateTypeDef",
-    "ListPipelinesInputListPipelinesPaginateTypeDef",
     "PipelineDescriptionTypeDef",
     "PipelineObjectTypeDef",
     "ReportTaskProgressInputRequestTypeDef",
     "PollForTaskInputRequestTypeDef",
     "ListPipelinesOutputTypeDef",
     "SelectorTypeDef",
     "ParameterObjectTypeDef",
@@ -89,22 +89,19 @@
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreatePipelineOutputTypeDef = TypedDict(
+    "CreatePipelineOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "pipelineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeactivatePipelineInputRequestTypeDef = TypedDict(
     "_RequiredDeactivatePipelineInputRequestTypeDef",
     {
         "pipelineId": str,
@@ -126,24 +123,36 @@
 DeletePipelineInputRequestTypeDef = TypedDict(
     "DeletePipelineInputRequestTypeDef",
     {
         "pipelineId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "pipelineId": str,
+        "objectIds": Sequence[str],
+    },
+)
+_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef",
+    {
+        "evaluateExpressions": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeObjectsInputDescribeObjectsPaginateTypeDef(
+    _RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef,
+    _OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeObjectsInputRequestTypeDef = TypedDict(
     "_RequiredDescribeObjectsInputRequestTypeDef",
     {
         "pipelineId": str,
         "objectIds": Sequence[str],
     },
 )
@@ -164,23 +173,38 @@
 DescribePipelinesInputRequestTypeDef = TypedDict(
     "DescribePipelinesInputRequestTypeDef",
     {
         "pipelineIds": Sequence[str],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EvaluateExpressionInputRequestTypeDef = TypedDict(
     "EvaluateExpressionInputRequestTypeDef",
     {
         "pipelineId": str,
         "objectId": str,
         "expression": str,
     },
 )
 
+EvaluateExpressionOutputTypeDef = TypedDict(
+    "EvaluateExpressionOutputTypeDef",
+    {
+        "evaluatedExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFieldTypeDef = TypedDict(
     "_RequiredFieldTypeDef",
     {
         "key": str,
     },
 )
 _OptionalFieldTypeDef = TypedDict(
@@ -220,14 +244,22 @@
     {
         "document": str,
         "signature": str,
     },
     total=False,
 )
 
+ListPipelinesInputListPipelinesPaginateTypeDef = TypedDict(
+    "ListPipelinesInputListPipelinesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPipelinesInputRequestTypeDef = TypedDict(
     "ListPipelinesInputRequestTypeDef",
     {
         "marker": str,
     },
     total=False,
 )
@@ -246,14 +278,24 @@
     {
         "type": OperatorTypeType,
         "values": Sequence[str],
     },
     total=False,
 )
 
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
 ParameterAttributeTypeDef = TypedDict(
     "ParameterAttributeTypeDef",
     {
         "key": str,
         "stringValue": str,
     },
 )
@@ -272,22 +314,40 @@
     {
         "id": str,
         "warnings": List[str],
     },
     total=False,
 )
 
+QueryObjectsOutputTypeDef = TypedDict(
+    "QueryObjectsOutputTypeDef",
+    {
+        "ids": List[str],
+        "marker": str,
+        "hasMoreResults": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsInputRequestTypeDef = TypedDict(
     "RemoveTagsInputRequestTypeDef",
     {
         "pipelineId": str,
         "tagKeys": Sequence[str],
     },
 )
 
+ReportTaskProgressOutputTypeDef = TypedDict(
+    "ReportTaskProgressOutputTypeDef",
+    {
+        "canceled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredReportTaskRunnerHeartbeatInputRequestTypeDef = TypedDict(
     "_RequiredReportTaskRunnerHeartbeatInputRequestTypeDef",
     {
         "taskrunnerId": str,
     },
 )
 _OptionalReportTaskRunnerHeartbeatInputRequestTypeDef = TypedDict(
@@ -301,14 +361,33 @@
 
 class ReportTaskRunnerHeartbeatInputRequestTypeDef(
     _RequiredReportTaskRunnerHeartbeatInputRequestTypeDef,
     _OptionalReportTaskRunnerHeartbeatInputRequestTypeDef,
 ):
     pass
 
+ReportTaskRunnerHeartbeatOutputTypeDef = TypedDict(
+    "ReportTaskRunnerHeartbeatOutputTypeDef",
+    {
+        "terminate": bool,
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
 SetStatusInputRequestTypeDef = TypedDict(
     "SetStatusInputRequestTypeDef",
     {
         "pipelineId": str,
         "objectIds": Sequence[str],
         "status": str,
     },
@@ -381,93 +460,14 @@
 )
 
 class CreatePipelineInputRequestTypeDef(
     _RequiredCreatePipelineInputRequestTypeDef, _OptionalCreatePipelineInputRequestTypeDef
 ):
     pass
 
-CreatePipelineOutputTypeDef = TypedDict(
-    "CreatePipelineOutputTypeDef",
-    {
-        "pipelineId": str,
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
-EvaluateExpressionOutputTypeDef = TypedDict(
-    "EvaluateExpressionOutputTypeDef",
-    {
-        "evaluatedExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-QueryObjectsOutputTypeDef = TypedDict(
-    "QueryObjectsOutputTypeDef",
-    {
-        "ids": List[str],
-        "marker": str,
-        "hasMoreResults": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReportTaskProgressOutputTypeDef = TypedDict(
-    "ReportTaskProgressOutputTypeDef",
-    {
-        "canceled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReportTaskRunnerHeartbeatOutputTypeDef = TypedDict(
-    "ReportTaskRunnerHeartbeatOutputTypeDef",
-    {
-        "terminate": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef",
-    {
-        "pipelineId": str,
-        "objectIds": Sequence[str],
-    },
-)
-_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef",
-    {
-        "evaluateExpressions": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeObjectsInputDescribeObjectsPaginateTypeDef(
-    _RequiredDescribeObjectsInputDescribeObjectsPaginateTypeDef,
-    _OptionalDescribeObjectsInputDescribeObjectsPaginateTypeDef,
-):
-    pass
-
-ListPipelinesInputListPipelinesPaginateTypeDef = TypedDict(
-    "ListPipelinesInputListPipelinesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredPipelineDescriptionTypeDef = TypedDict(
     "_RequiredPipelineDescriptionTypeDef",
     {
         "pipelineId": str,
         "name": str,
         "fields": List[FieldTypeDef],
     },
@@ -536,15 +536,15 @@
 
 ListPipelinesOutputTypeDef = TypedDict(
     "ListPipelinesOutputTypeDef",
     {
         "pipelineIdList": List[PipelineIdNameTypeDef],
         "marker": str,
         "hasMoreResults": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectorTypeDef = TypedDict(
     "SelectorTypeDef",
     {
         "fieldName": str,
@@ -563,43 +563,43 @@
 
 PutPipelineDefinitionOutputTypeDef = TypedDict(
     "PutPipelineDefinitionOutputTypeDef",
     {
         "validationErrors": List[ValidationErrorTypeDef],
         "validationWarnings": List[ValidationWarningTypeDef],
         "errored": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidatePipelineDefinitionOutputTypeDef = TypedDict(
     "ValidatePipelineDefinitionOutputTypeDef",
     {
         "validationErrors": List[ValidationErrorTypeDef],
         "validationWarnings": List[ValidationWarningTypeDef],
         "errored": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePipelinesOutputTypeDef = TypedDict(
     "DescribePipelinesOutputTypeDef",
     {
         "pipelineDescriptionList": List[PipelineDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeObjectsOutputTypeDef = TypedDict(
     "DescribeObjectsOutputTypeDef",
     {
         "pipelineObjects": List[PipelineObjectTypeDef],
         "marker": str,
         "hasMoreResults": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TaskObjectTypeDef = TypedDict(
     "TaskObjectTypeDef",
     {
         "taskId": str,
@@ -620,15 +620,15 @@
 
 GetPipelineDefinitionOutputTypeDef = TypedDict(
     "GetPipelineDefinitionOutputTypeDef",
     {
         "pipelineObjects": List[PipelineObjectTypeDef],
         "parameterObjects": List[ParameterObjectTypeDef],
         "parameterValues": List[ParameterValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutPipelineDefinitionInputRequestTypeDef = TypedDict(
     "_RequiredPutPipelineDefinitionInputRequestTypeDef",
     {
         "pipelineId": str,
@@ -672,30 +672,30 @@
 ):
     pass
 
 PollForTaskOutputTypeDef = TypedDict(
     "PollForTaskOutputTypeDef",
     {
         "taskObject": TaskObjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredQueryObjectsInputQueryObjectsPaginateTypeDef = TypedDict(
     "_RequiredQueryObjectsInputQueryObjectsPaginateTypeDef",
     {
         "pipelineId": str,
         "sphere": str,
     },
 )
 _OptionalQueryObjectsInputQueryObjectsPaginateTypeDef = TypedDict(
     "_OptionalQueryObjectsInputQueryObjectsPaginateTypeDef",
     {
         "query": QueryTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class QueryObjectsInputQueryObjectsPaginateTypeDef(
     _RequiredQueryObjectsInputQueryObjectsPaginateTypeDef,
     _OptionalQueryObjectsInputQueryObjectsPaginateTypeDef,
```

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/PKG-INFO` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-datapipeline
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DataPipeline 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DataPipeline 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-datapipeline"></a>
 
 # types-aiobotocore-datapipeline
 
 [![PyPI - types-aiobotocore-datapipeline](https://img.shields.io/pypi/v/types-aiobotocore-datapipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-datapipeline)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-datapipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-datapipeline)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-datapipeline?color=blue)](https://pypistats.org/packages/types-aiobotocore-datapipeline)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DataPipeline 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline)
+[aiobotocore.DataPipeline 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/datapipeline.html#DataPipeline)
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
 [types-aiobotocore-datapipeline docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_datapipeline/).
 
 See how it helps to find and fix potential bugs:
 
@@ -326,45 +326,45 @@
 `types_aiobotocore_datapipeline.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_datapipeline.type_defs import (
     ParameterValueTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreatePipelineOutputTypeDef,
     DeactivatePipelineInputRequestTypeDef,
     DeletePipelineInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeObjectsInputDescribeObjectsPaginateTypeDef,
     DescribeObjectsInputRequestTypeDef,
     DescribePipelinesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluateExpressionInputRequestTypeDef,
+    EvaluateExpressionOutputTypeDef,
     FieldTypeDef,
     GetPipelineDefinitionInputRequestTypeDef,
     InstanceIdentityTypeDef,
+    ListPipelinesInputListPipelinesPaginateTypeDef,
     ListPipelinesInputRequestTypeDef,
     PipelineIdNameTypeDef,
     OperatorTypeDef,
+    PaginatorConfigTypeDef,
     ParameterAttributeTypeDef,
     ValidationErrorTypeDef,
     ValidationWarningTypeDef,
+    QueryObjectsOutputTypeDef,
     RemoveTagsInputRequestTypeDef,
+    ReportTaskProgressOutputTypeDef,
     ReportTaskRunnerHeartbeatInputRequestTypeDef,
+    ReportTaskRunnerHeartbeatOutputTypeDef,
+    ResponseMetadataTypeDef,
     SetStatusInputRequestTypeDef,
     SetTaskStatusInputRequestTypeDef,
     ActivatePipelineInputRequestTypeDef,
     AddTagsInputRequestTypeDef,
     CreatePipelineInputRequestTypeDef,
-    CreatePipelineOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EvaluateExpressionOutputTypeDef,
-    QueryObjectsOutputTypeDef,
-    ReportTaskProgressOutputTypeDef,
-    ReportTaskRunnerHeartbeatOutputTypeDef,
-    DescribeObjectsInputDescribeObjectsPaginateTypeDef,
-    ListPipelinesInputListPipelinesPaginateTypeDef,
     PipelineDescriptionTypeDef,
     PipelineObjectTypeDef,
     ReportTaskProgressInputRequestTypeDef,
     PollForTaskInputRequestTypeDef,
     ListPipelinesOutputTypeDef,
     SelectorTypeDef,
     ParameterObjectTypeDef,
@@ -390,43 +390,43 @@
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

### Comparing `types-aiobotocore-datapipeline-2.5.0.post1/types_aiobotocore_datapipeline.egg-info/SOURCES.txt` & `types-aiobotocore-datapipeline-2.5.1/types_aiobotocore_datapipeline.egg-info/SOURCES.txt`

 * *Files identical despite different names*

