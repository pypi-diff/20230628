# Comparing `tmp/types-aiobotocore-scheduler-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-scheduler-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-scheduler-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-scheduler-2.5.1.tar", last modified: Wed Jun 28 01:44:08 2023, max compression
```

## Comparing `types-aiobotocore-scheduler-2.5.0.post1.tar` & `types-aiobotocore-scheduler-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.223607 types-aiobotocore-scheduler-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14920 2023-03-11 12:27:18.215607 types-aiobotocore-scheduler-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13330 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.223607 types-aiobotocore-scheduler-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2149 2023-03-11 12:23:34.000000 types-aiobotocore-scheduler-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.215607 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/
--rw-r--r--   0 runner    (1001) docker     (123)      939 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13131 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13108 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8524 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8522 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3479 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3474 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    15546 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15524 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:35.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.215607 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14920 2023-03-11 12:27:18.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:27:18.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:27:18.000000 types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:08.486210 types-aiobotocore-scheduler-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14914 2023-06-28 01:44:08.478210 types-aiobotocore-scheduler-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13330 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:08.486210 types-aiobotocore-scheduler-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:08.478210 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13131 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13108 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9074 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9072 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3363 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3359 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    15566 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15544 2023-06-28 01:40:22.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:21.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:08.478210 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14914 2023-06-28 01:44:08.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:44:08.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:08.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:08.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:08.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:44:08.000000 types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/LICENSE` & `types-aiobotocore-scheduler-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/PKG-INFO` & `types-aiobotocore-scheduler-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-scheduler
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EventBridgeScheduler 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EventBridgeScheduler 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-scheduler"></a>
 
 # types-aiobotocore-scheduler
 
 [![PyPI - types-aiobotocore-scheduler](https://img.shields.io/pypi/v/types-aiobotocore-scheduler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-scheduler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-scheduler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-scheduler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-scheduler?color=blue)](https://pypistats.org/packages/types-aiobotocore-scheduler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridgeScheduler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler)
+[aiobotocore.EventBridgeScheduler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler)
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
 [types-aiobotocore-scheduler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,45 +332,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_scheduler.type_defs import (
     AwsVpcConfigurationTypeDef,
     CapacityProviderStrategyItemTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateScheduleGroupOutputTypeDef,
     FlexibleTimeWindowTypeDef,
+    CreateScheduleOutputTypeDef,
     DeadLetterConfigTypeDef,
     DeleteScheduleGroupInputRequestTypeDef,
     DeleteScheduleInputRequestTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
     EventBridgeParametersTypeDef,
     GetScheduleGroupInputRequestTypeDef,
+    GetScheduleGroupOutputTypeDef,
     GetScheduleInputRequestTypeDef,
     KinesisParametersTypeDef,
-    PaginatorConfigTypeDef,
+    ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef,
     ListScheduleGroupsInputRequestTypeDef,
     ScheduleGroupSummaryTypeDef,
+    ListSchedulesInputListSchedulesPaginateTypeDef,
     ListSchedulesInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RetryPolicyTypeDef,
     SageMakerPipelineParameterTypeDef,
     TargetSummaryTypeDef,
     SqsParametersTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateScheduleOutputTypeDef,
     NetworkConfigurationTypeDef,
     CreateScheduleGroupInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
-    CreateScheduleGroupOutputTypeDef,
-    CreateScheduleOutputTypeDef,
-    GetScheduleGroupOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
-    UpdateScheduleOutputTypeDef,
-    ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef,
-    ListSchedulesInputListSchedulesPaginateTypeDef,
+    TagResourceInputRequestTypeDef,
     ListScheduleGroupsOutputTypeDef,
     SageMakerPipelineParametersTypeDef,
     ScheduleSummaryTypeDef,
     EcsParametersTypeDef,
     ListSchedulesOutputTypeDef,
     TargetTypeDef,
     CreateScheduleInputRequestTypeDef,
@@ -386,43 +386,43 @@
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

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/README.md` & `types-aiobotocore-scheduler-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-scheduler"></a>
 
 # types-aiobotocore-scheduler
 
 [![PyPI - types-aiobotocore-scheduler](https://img.shields.io/pypi/v/types-aiobotocore-scheduler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-scheduler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-scheduler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-scheduler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-scheduler?color=blue)](https://pypistats.org/packages/types-aiobotocore-scheduler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridgeScheduler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler)
+[aiobotocore.EventBridgeScheduler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler)
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
 [types-aiobotocore-scheduler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,45 +299,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_scheduler.type_defs import (
     AwsVpcConfigurationTypeDef,
     CapacityProviderStrategyItemTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateScheduleGroupOutputTypeDef,
     FlexibleTimeWindowTypeDef,
+    CreateScheduleOutputTypeDef,
     DeadLetterConfigTypeDef,
     DeleteScheduleGroupInputRequestTypeDef,
     DeleteScheduleInputRequestTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
     EventBridgeParametersTypeDef,
     GetScheduleGroupInputRequestTypeDef,
+    GetScheduleGroupOutputTypeDef,
     GetScheduleInputRequestTypeDef,
     KinesisParametersTypeDef,
-    PaginatorConfigTypeDef,
+    ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef,
     ListScheduleGroupsInputRequestTypeDef,
     ScheduleGroupSummaryTypeDef,
+    ListSchedulesInputListSchedulesPaginateTypeDef,
     ListSchedulesInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RetryPolicyTypeDef,
     SageMakerPipelineParameterTypeDef,
     TargetSummaryTypeDef,
     SqsParametersTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateScheduleOutputTypeDef,
     NetworkConfigurationTypeDef,
     CreateScheduleGroupInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
-    CreateScheduleGroupOutputTypeDef,
-    CreateScheduleOutputTypeDef,
-    GetScheduleGroupOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
-    UpdateScheduleOutputTypeDef,
-    ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef,
-    ListSchedulesInputListSchedulesPaginateTypeDef,
+    TagResourceInputRequestTypeDef,
     ListScheduleGroupsOutputTypeDef,
     SageMakerPipelineParametersTypeDef,
     ScheduleSummaryTypeDef,
     EcsParametersTypeDef,
     ListSchedulesOutputTypeDef,
     TargetTypeDef,
     CreateScheduleInputRequestTypeDef,
@@ -353,43 +353,43 @@
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

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/setup.py` & `types-aiobotocore-scheduler-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-scheduler.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-scheduler",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_scheduler"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EventBridgeScheduler 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.EventBridgeScheduler 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/"
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

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/__init__.py` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/__init__.pyi` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/__main__.py` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EventBridgeScheduler 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EventBridgeScheduler 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler\nOther"
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

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/client.py` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/client.pyi` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/literals.py` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -107,14 +107,15 @@
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
@@ -193,14 +194,15 @@
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
@@ -211,14 +213,15 @@
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
@@ -254,14 +257,15 @@
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
@@ -280,16 +284,19 @@
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
@@ -373,15 +380,17 @@
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
@@ -401,17 +410,35 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_schedule_groups", "list_schedules"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-northeast-3",
+    "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
+    "ap-southeast-4",
+    "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
+    "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
+    "eu-west-2",
+    "eu-west-3",
+    "me-central-1",
+    "me-south-1",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/literals.pyi` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -105,14 +105,15 @@
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
@@ -191,14 +192,15 @@
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
@@ -209,14 +211,15 @@
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
@@ -252,14 +255,15 @@
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
@@ -278,16 +282,19 @@
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
@@ -371,15 +378,17 @@
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
@@ -399,17 +408,35 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_schedule_groups", "list_schedules"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-northeast-3",
+    "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
+    "ap-southeast-4",
+    "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
+    "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
+    "eu-west-2",
+    "eu-west-3",
+    "me-central-1",
+    "me-south-1",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/paginator.py` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,33 +18,26 @@
     with session.create_client("scheduler") as client:
         client: EventBridgeSchedulerClient
 
         list_schedule_groups_paginator: ListScheduleGroupsPaginator = client.get_paginator("list_schedule_groups")
         list_schedules_paginator: ListSchedulesPaginator = client.get_paginator("list_schedules")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ScheduleStateType
 from .type_defs import (
     ListScheduleGroupsOutputTypeDef,
     ListSchedulesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListScheduleGroupsPaginator", "ListSchedulesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -57,15 +50,15 @@
 class ListScheduleGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler.Paginator.ListScheduleGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/paginators/#listschedulegroupspaginator)
     """
 
     def paginate(
-        self, *, NamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, NamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScheduleGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler.Paginator.ListScheduleGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/paginators/#listschedulegroupspaginator)
         """
 
 
@@ -77,13 +70,13 @@
 
     def paginate(
         self,
         *,
         GroupName: str = ...,
         NamePrefix: str = ...,
         State: ScheduleStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchedulesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler.Paginator.ListSchedules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/paginators/#listschedulespaginator)
         """
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/paginator.pyi` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -18,32 +18,26 @@
     with session.create_client("scheduler") as client:
         client: EventBridgeSchedulerClient
 
         list_schedule_groups_paginator: ListScheduleGroupsPaginator = client.get_paginator("list_schedule_groups")
         list_schedules_paginator: ListSchedulesPaginator = client.get_paginator("list_schedules")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ScheduleStateType
 from .type_defs import (
     ListScheduleGroupsOutputTypeDef,
     ListSchedulesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListScheduleGroupsPaginator", "ListSchedulesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -53,15 +47,15 @@
 class ListScheduleGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler.Paginator.ListScheduleGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/paginators/#listschedulegroupspaginator)
     """
 
     def paginate(
-        self, *, NamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, NamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScheduleGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler.Paginator.ListScheduleGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/paginators/#listschedulegroupspaginator)
         """
 
 class ListSchedulesPaginator(AioPaginator):
@@ -72,13 +66,13 @@
 
     def paginate(
         self,
         *,
         GroupName: str = ...,
         NamePrefix: str = ...,
         State: ScheduleStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchedulesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler.Paginator.ListSchedules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/paginators/#listschedulespaginator)
         """
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/type_defs.py` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,50 +30,49 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AwsVpcConfigurationTypeDef",
     "CapacityProviderStrategyItemTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateScheduleGroupOutputTypeDef",
     "FlexibleTimeWindowTypeDef",
+    "CreateScheduleOutputTypeDef",
     "DeadLetterConfigTypeDef",
     "DeleteScheduleGroupInputRequestTypeDef",
     "DeleteScheduleInputRequestTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
     "EventBridgeParametersTypeDef",
     "GetScheduleGroupInputRequestTypeDef",
+    "GetScheduleGroupOutputTypeDef",
     "GetScheduleInputRequestTypeDef",
     "KinesisParametersTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
     "ListScheduleGroupsInputRequestTypeDef",
     "ScheduleGroupSummaryTypeDef",
+    "ListSchedulesInputListSchedulesPaginateTypeDef",
     "ListSchedulesInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryPolicyTypeDef",
     "SageMakerPipelineParameterTypeDef",
     "TargetSummaryTypeDef",
     "SqsParametersTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "UpdateScheduleOutputTypeDef",
     "NetworkConfigurationTypeDef",
     "CreateScheduleGroupInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
-    "CreateScheduleGroupOutputTypeDef",
-    "CreateScheduleOutputTypeDef",
-    "GetScheduleGroupOutputTypeDef",
     "ListTagsForResourceOutputTypeDef",
-    "UpdateScheduleOutputTypeDef",
-    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
-    "ListSchedulesInputListSchedulesPaginateTypeDef",
+    "TagResourceInputRequestTypeDef",
     "ListScheduleGroupsOutputTypeDef",
     "SageMakerPipelineParametersTypeDef",
     "ScheduleSummaryTypeDef",
     "EcsParametersTypeDef",
     "ListSchedulesOutputTypeDef",
     "TargetTypeDef",
     "CreateScheduleInputRequestTypeDef",
@@ -92,21 +91,19 @@
     {
         "AssignPublicIp": AssignPublicIpType,
         "SecurityGroups": Sequence[str],
     },
     total=False,
 )
 
-
 class AwsVpcConfigurationTypeDef(
     _RequiredAwsVpcConfigurationTypeDef, _OptionalAwsVpcConfigurationTypeDef
 ):
     pass
 
-
 _RequiredCapacityProviderStrategyItemTypeDef = TypedDict(
     "_RequiredCapacityProviderStrategyItemTypeDef",
     {
         "capacityProvider": str,
     },
 )
 _OptionalCapacityProviderStrategyItemTypeDef = TypedDict(
@@ -114,37 +111,32 @@
     {
         "base": int,
         "weight": int,
     },
     total=False,
 )
 
-
 class CapacityProviderStrategyItemTypeDef(
     _RequiredCapacityProviderStrategyItemTypeDef, _OptionalCapacityProviderStrategyItemTypeDef
 ):
     pass
 
-
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateScheduleGroupOutputTypeDef = TypedDict(
+    "CreateScheduleGroupOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScheduleGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFlexibleTimeWindowTypeDef = TypedDict(
     "_RequiredFlexibleTimeWindowTypeDef",
     {
         "Mode": FlexibleTimeWindowModeType,
@@ -154,20 +146,26 @@
     "_OptionalFlexibleTimeWindowTypeDef",
     {
         "MaximumWindowInMinutes": int,
     },
     total=False,
 )
 
-
 class FlexibleTimeWindowTypeDef(
     _RequiredFlexibleTimeWindowTypeDef, _OptionalFlexibleTimeWindowTypeDef
 ):
     pass
 
+CreateScheduleOutputTypeDef = TypedDict(
+    "CreateScheduleOutputTypeDef",
+    {
+        "ScheduleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeadLetterConfigTypeDef = TypedDict(
     "DeadLetterConfigTypeDef",
     {
         "Arn": str,
     },
     total=False,
@@ -183,21 +181,19 @@
     "_OptionalDeleteScheduleGroupInputRequestTypeDef",
     {
         "ClientToken": str,
     },
     total=False,
 )
 
-
 class DeleteScheduleGroupInputRequestTypeDef(
     _RequiredDeleteScheduleGroupInputRequestTypeDef, _OptionalDeleteScheduleGroupInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDeleteScheduleInputRequestTypeDef = TypedDict(
     "_RequiredDeleteScheduleInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDeleteScheduleInputRequestTypeDef = TypedDict(
@@ -205,21 +201,19 @@
     {
         "ClientToken": str,
         "GroupName": str,
     },
     total=False,
 )
 
-
 class DeleteScheduleInputRequestTypeDef(
     _RequiredDeleteScheduleInputRequestTypeDef, _OptionalDeleteScheduleInputRequestTypeDef
 ):
     pass
 
-
 PlacementConstraintTypeDef = TypedDict(
     "PlacementConstraintTypeDef",
     {
         "expression": str,
         "type": PlacementConstraintTypeType,
     },
     total=False,
@@ -245,48 +239,57 @@
 GetScheduleGroupInputRequestTypeDef = TypedDict(
     "GetScheduleGroupInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetScheduleGroupOutputTypeDef = TypedDict(
+    "GetScheduleGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "CreationDate": datetime,
+        "LastModificationDate": datetime,
+        "Name": str,
+        "State": ScheduleGroupStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetScheduleInputRequestTypeDef = TypedDict(
     "_RequiredGetScheduleInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGetScheduleInputRequestTypeDef = TypedDict(
     "_OptionalGetScheduleInputRequestTypeDef",
     {
         "GroupName": str,
     },
     total=False,
 )
 
-
 class GetScheduleInputRequestTypeDef(
     _RequiredGetScheduleInputRequestTypeDef, _OptionalGetScheduleInputRequestTypeDef
 ):
     pass
 
-
 KinesisParametersTypeDef = TypedDict(
     "KinesisParametersTypeDef",
     {
         "PartitionKey": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef = TypedDict(
+    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "NamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListScheduleGroupsInputRequestTypeDef = TypedDict(
     "ListScheduleGroupsInputRequestTypeDef",
     {
@@ -305,14 +308,25 @@
         "LastModificationDate": datetime,
         "Name": str,
         "State": ScheduleGroupStateType,
     },
     total=False,
 )
 
+ListSchedulesInputListSchedulesPaginateTypeDef = TypedDict(
+    "ListSchedulesInputListSchedulesPaginateTypeDef",
+    {
+        "GroupName": str,
+        "NamePrefix": str,
+        "State": ScheduleStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchedulesInputRequestTypeDef = TypedDict(
     "ListSchedulesInputRequestTypeDef",
     {
         "GroupName": str,
         "MaxResults": int,
         "NamePrefix": str,
         "NextToken": str,
@@ -324,14 +338,35 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
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
 RetryPolicyTypeDef = TypedDict(
     "RetryPolicyTypeDef",
     {
         "MaximumEventAgeInSeconds": int,
         "MaximumRetryAttempts": int,
     },
     total=False,
@@ -364,14 +399,22 @@
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateScheduleOutputTypeDef = TypedDict(
+    "UpdateScheduleOutputTypeDef",
+    {
+        "ScheduleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NetworkConfigurationTypeDef = TypedDict(
     "NetworkConfigurationTypeDef",
     {
         "awsvpcConfiguration": AwsVpcConfigurationTypeDef,
     },
     total=False,
 )
@@ -387,99 +430,41 @@
     {
         "ClientToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateScheduleGroupInputRequestTypeDef(
     _RequiredCreateScheduleGroupInputRequestTypeDef, _OptionalCreateScheduleGroupInputRequestTypeDef
 ):
     pass
 
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateScheduleGroupOutputTypeDef = TypedDict(
-    "CreateScheduleGroupOutputTypeDef",
-    {
-        "ScheduleGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateScheduleOutputTypeDef = TypedDict(
-    "CreateScheduleOutputTypeDef",
-    {
-        "ScheduleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetScheduleGroupOutputTypeDef = TypedDict(
-    "GetScheduleGroupOutputTypeDef",
-    {
-        "Arn": str,
-        "CreationDate": datetime,
-        "LastModificationDate": datetime,
-        "Name": str,
-        "State": ScheduleGroupStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateScheduleOutputTypeDef = TypedDict(
-    "UpdateScheduleOutputTypeDef",
-    {
-        "ScheduleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef = TypedDict(
-    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
-    {
-        "NamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListSchedulesInputListSchedulesPaginateTypeDef = TypedDict(
-    "ListSchedulesInputListSchedulesPaginateTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "GroupName": str,
-        "NamePrefix": str,
-        "State": ScheduleStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
 ListScheduleGroupsOutputTypeDef = TypedDict(
     "ListScheduleGroupsOutputTypeDef",
     {
         "NextToken": str,
         "ScheduleGroups": List[ScheduleGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SageMakerPipelineParametersTypeDef = TypedDict(
     "SageMakerPipelineParametersTypeDef",
     {
         "PipelineParameterList": Sequence[SageMakerPipelineParameterTypeDef],
@@ -523,25 +508,23 @@
         "ReferenceId": str,
         "Tags": Sequence[Mapping[str, str]],
         "TaskCount": int,
     },
     total=False,
 )
 
-
 class EcsParametersTypeDef(_RequiredEcsParametersTypeDef, _OptionalEcsParametersTypeDef):
     pass
 
-
 ListSchedulesOutputTypeDef = TypedDict(
     "ListSchedulesOutputTypeDef",
     {
         "NextToken": str,
         "Schedules": List[ScheduleSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTargetTypeDef = TypedDict(
     "_RequiredTargetTypeDef",
     {
         "Arn": str,
@@ -559,19 +542,17 @@
         "RetryPolicy": RetryPolicyTypeDef,
         "SageMakerPipelineParameters": SageMakerPipelineParametersTypeDef,
         "SqsParameters": SqsParametersTypeDef,
     },
     total=False,
 )
 
-
 class TargetTypeDef(_RequiredTargetTypeDef, _OptionalTargetTypeDef):
     pass
 
-
 _RequiredCreateScheduleInputRequestTypeDef = TypedDict(
     "_RequiredCreateScheduleInputRequestTypeDef",
     {
         "FlexibleTimeWindow": FlexibleTimeWindowTypeDef,
         "Name": str,
         "ScheduleExpression": str,
         "Target": TargetTypeDef,
@@ -588,21 +569,19 @@
         "ScheduleExpressionTimezone": str,
         "StartDate": Union[datetime, str],
         "State": ScheduleStateType,
     },
     total=False,
 )
 
-
 class CreateScheduleInputRequestTypeDef(
     _RequiredCreateScheduleInputRequestTypeDef, _OptionalCreateScheduleInputRequestTypeDef
 ):
     pass
 
-
 GetScheduleOutputTypeDef = TypedDict(
     "GetScheduleOutputTypeDef",
     {
         "Arn": str,
         "CreationDate": datetime,
         "Description": str,
         "EndDate": datetime,
@@ -612,15 +591,15 @@
         "LastModificationDate": datetime,
         "Name": str,
         "ScheduleExpression": str,
         "ScheduleExpressionTimezone": str,
         "StartDate": datetime,
         "State": ScheduleStateType,
         "Target": TargetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateScheduleInputRequestTypeDef = TypedDict(
     "_RequiredUpdateScheduleInputRequestTypeDef",
     {
         "FlexibleTimeWindow": FlexibleTimeWindowTypeDef,
@@ -640,12 +619,11 @@
         "ScheduleExpressionTimezone": str,
         "StartDate": Union[datetime, str],
         "State": ScheduleStateType,
     },
     total=False,
 )
 
-
 class UpdateScheduleInputRequestTypeDef(
     _RequiredUpdateScheduleInputRequestTypeDef, _OptionalUpdateScheduleInputRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler/type_defs.pyi` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -30,49 +30,50 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AwsVpcConfigurationTypeDef",
     "CapacityProviderStrategyItemTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateScheduleGroupOutputTypeDef",
     "FlexibleTimeWindowTypeDef",
+    "CreateScheduleOutputTypeDef",
     "DeadLetterConfigTypeDef",
     "DeleteScheduleGroupInputRequestTypeDef",
     "DeleteScheduleInputRequestTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
     "EventBridgeParametersTypeDef",
     "GetScheduleGroupInputRequestTypeDef",
+    "GetScheduleGroupOutputTypeDef",
     "GetScheduleInputRequestTypeDef",
     "KinesisParametersTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
     "ListScheduleGroupsInputRequestTypeDef",
     "ScheduleGroupSummaryTypeDef",
+    "ListSchedulesInputListSchedulesPaginateTypeDef",
     "ListSchedulesInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryPolicyTypeDef",
     "SageMakerPipelineParameterTypeDef",
     "TargetSummaryTypeDef",
     "SqsParametersTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "UpdateScheduleOutputTypeDef",
     "NetworkConfigurationTypeDef",
     "CreateScheduleGroupInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
-    "CreateScheduleGroupOutputTypeDef",
-    "CreateScheduleOutputTypeDef",
-    "GetScheduleGroupOutputTypeDef",
     "ListTagsForResourceOutputTypeDef",
-    "UpdateScheduleOutputTypeDef",
-    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
-    "ListSchedulesInputListSchedulesPaginateTypeDef",
+    "TagResourceInputRequestTypeDef",
     "ListScheduleGroupsOutputTypeDef",
     "SageMakerPipelineParametersTypeDef",
     "ScheduleSummaryTypeDef",
     "EcsParametersTypeDef",
     "ListSchedulesOutputTypeDef",
     "TargetTypeDef",
     "CreateScheduleInputRequestTypeDef",
@@ -91,19 +92,21 @@
     {
         "AssignPublicIp": AssignPublicIpType,
         "SecurityGroups": Sequence[str],
     },
     total=False,
 )
 
+
 class AwsVpcConfigurationTypeDef(
     _RequiredAwsVpcConfigurationTypeDef, _OptionalAwsVpcConfigurationTypeDef
 ):
     pass
 
+
 _RequiredCapacityProviderStrategyItemTypeDef = TypedDict(
     "_RequiredCapacityProviderStrategyItemTypeDef",
     {
         "capacityProvider": str,
     },
 )
 _OptionalCapacityProviderStrategyItemTypeDef = TypedDict(
@@ -111,35 +114,34 @@
     {
         "base": int,
         "weight": int,
     },
     total=False,
 )
 
+
 class CapacityProviderStrategyItemTypeDef(
     _RequiredCapacityProviderStrategyItemTypeDef, _OptionalCapacityProviderStrategyItemTypeDef
 ):
     pass
 
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateScheduleGroupOutputTypeDef = TypedDict(
+    "CreateScheduleGroupOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScheduleGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFlexibleTimeWindowTypeDef = TypedDict(
     "_RequiredFlexibleTimeWindowTypeDef",
     {
         "Mode": FlexibleTimeWindowModeType,
@@ -149,19 +151,29 @@
     "_OptionalFlexibleTimeWindowTypeDef",
     {
         "MaximumWindowInMinutes": int,
     },
     total=False,
 )
 
+
 class FlexibleTimeWindowTypeDef(
     _RequiredFlexibleTimeWindowTypeDef, _OptionalFlexibleTimeWindowTypeDef
 ):
     pass
 
+
+CreateScheduleOutputTypeDef = TypedDict(
+    "CreateScheduleOutputTypeDef",
+    {
+        "ScheduleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeadLetterConfigTypeDef = TypedDict(
     "DeadLetterConfigTypeDef",
     {
         "Arn": str,
     },
     total=False,
 )
@@ -176,19 +188,21 @@
     "_OptionalDeleteScheduleGroupInputRequestTypeDef",
     {
         "ClientToken": str,
     },
     total=False,
 )
 
+
 class DeleteScheduleGroupInputRequestTypeDef(
     _RequiredDeleteScheduleGroupInputRequestTypeDef, _OptionalDeleteScheduleGroupInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDeleteScheduleInputRequestTypeDef = TypedDict(
     "_RequiredDeleteScheduleInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDeleteScheduleInputRequestTypeDef = TypedDict(
@@ -196,19 +210,21 @@
     {
         "ClientToken": str,
         "GroupName": str,
     },
     total=False,
 )
 
+
 class DeleteScheduleInputRequestTypeDef(
     _RequiredDeleteScheduleInputRequestTypeDef, _OptionalDeleteScheduleInputRequestTypeDef
 ):
     pass
 
+
 PlacementConstraintTypeDef = TypedDict(
     "PlacementConstraintTypeDef",
     {
         "expression": str,
         "type": PlacementConstraintTypeType,
     },
     total=False,
@@ -234,46 +250,59 @@
 GetScheduleGroupInputRequestTypeDef = TypedDict(
     "GetScheduleGroupInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetScheduleGroupOutputTypeDef = TypedDict(
+    "GetScheduleGroupOutputTypeDef",
+    {
+        "Arn": str,
+        "CreationDate": datetime,
+        "LastModificationDate": datetime,
+        "Name": str,
+        "State": ScheduleGroupStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetScheduleInputRequestTypeDef = TypedDict(
     "_RequiredGetScheduleInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGetScheduleInputRequestTypeDef = TypedDict(
     "_OptionalGetScheduleInputRequestTypeDef",
     {
         "GroupName": str,
     },
     total=False,
 )
 
+
 class GetScheduleInputRequestTypeDef(
     _RequiredGetScheduleInputRequestTypeDef, _OptionalGetScheduleInputRequestTypeDef
 ):
     pass
 
+
 KinesisParametersTypeDef = TypedDict(
     "KinesisParametersTypeDef",
     {
         "PartitionKey": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef = TypedDict(
+    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "NamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListScheduleGroupsInputRequestTypeDef = TypedDict(
     "ListScheduleGroupsInputRequestTypeDef",
     {
@@ -292,14 +321,25 @@
         "LastModificationDate": datetime,
         "Name": str,
         "State": ScheduleGroupStateType,
     },
     total=False,
 )
 
+ListSchedulesInputListSchedulesPaginateTypeDef = TypedDict(
+    "ListSchedulesInputListSchedulesPaginateTypeDef",
+    {
+        "GroupName": str,
+        "NamePrefix": str,
+        "State": ScheduleStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchedulesInputRequestTypeDef = TypedDict(
     "ListSchedulesInputRequestTypeDef",
     {
         "GroupName": str,
         "MaxResults": int,
         "NamePrefix": str,
         "NextToken": str,
@@ -311,14 +351,35 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
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
 RetryPolicyTypeDef = TypedDict(
     "RetryPolicyTypeDef",
     {
         "MaximumEventAgeInSeconds": int,
         "MaximumRetryAttempts": int,
     },
     total=False,
@@ -351,14 +412,22 @@
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateScheduleOutputTypeDef = TypedDict(
+    "UpdateScheduleOutputTypeDef",
+    {
+        "ScheduleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NetworkConfigurationTypeDef = TypedDict(
     "NetworkConfigurationTypeDef",
     {
         "awsvpcConfiguration": AwsVpcConfigurationTypeDef,
     },
     total=False,
 )
@@ -374,97 +443,43 @@
     {
         "ClientToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateScheduleGroupInputRequestTypeDef(
     _RequiredCreateScheduleGroupInputRequestTypeDef, _OptionalCreateScheduleGroupInputRequestTypeDef
 ):
     pass
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateScheduleGroupOutputTypeDef = TypedDict(
-    "CreateScheduleGroupOutputTypeDef",
-    {
-        "ScheduleGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateScheduleOutputTypeDef = TypedDict(
-    "CreateScheduleOutputTypeDef",
-    {
-        "ScheduleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetScheduleGroupOutputTypeDef = TypedDict(
-    "GetScheduleGroupOutputTypeDef",
-    {
-        "Arn": str,
-        "CreationDate": datetime,
-        "LastModificationDate": datetime,
-        "Name": str,
-        "State": ScheduleGroupStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateScheduleOutputTypeDef = TypedDict(
-    "UpdateScheduleOutputTypeDef",
-    {
-        "ScheduleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef = TypedDict(
-    "ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef",
-    {
-        "NamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListSchedulesInputListSchedulesPaginateTypeDef = TypedDict(
-    "ListSchedulesInputListSchedulesPaginateTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "GroupName": str,
-        "NamePrefix": str,
-        "State": ScheduleStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
 ListScheduleGroupsOutputTypeDef = TypedDict(
     "ListScheduleGroupsOutputTypeDef",
     {
         "NextToken": str,
         "ScheduleGroups": List[ScheduleGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SageMakerPipelineParametersTypeDef = TypedDict(
     "SageMakerPipelineParametersTypeDef",
     {
         "PipelineParameterList": Sequence[SageMakerPipelineParameterTypeDef],
@@ -508,23 +523,25 @@
         "ReferenceId": str,
         "Tags": Sequence[Mapping[str, str]],
         "TaskCount": int,
     },
     total=False,
 )
 
+
 class EcsParametersTypeDef(_RequiredEcsParametersTypeDef, _OptionalEcsParametersTypeDef):
     pass
 
+
 ListSchedulesOutputTypeDef = TypedDict(
     "ListSchedulesOutputTypeDef",
     {
         "NextToken": str,
         "Schedules": List[ScheduleSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTargetTypeDef = TypedDict(
     "_RequiredTargetTypeDef",
     {
         "Arn": str,
@@ -542,17 +559,19 @@
         "RetryPolicy": RetryPolicyTypeDef,
         "SageMakerPipelineParameters": SageMakerPipelineParametersTypeDef,
         "SqsParameters": SqsParametersTypeDef,
     },
     total=False,
 )
 
+
 class TargetTypeDef(_RequiredTargetTypeDef, _OptionalTargetTypeDef):
     pass
 
+
 _RequiredCreateScheduleInputRequestTypeDef = TypedDict(
     "_RequiredCreateScheduleInputRequestTypeDef",
     {
         "FlexibleTimeWindow": FlexibleTimeWindowTypeDef,
         "Name": str,
         "ScheduleExpression": str,
         "Target": TargetTypeDef,
@@ -569,19 +588,21 @@
         "ScheduleExpressionTimezone": str,
         "StartDate": Union[datetime, str],
         "State": ScheduleStateType,
     },
     total=False,
 )
 
+
 class CreateScheduleInputRequestTypeDef(
     _RequiredCreateScheduleInputRequestTypeDef, _OptionalCreateScheduleInputRequestTypeDef
 ):
     pass
 
+
 GetScheduleOutputTypeDef = TypedDict(
     "GetScheduleOutputTypeDef",
     {
         "Arn": str,
         "CreationDate": datetime,
         "Description": str,
         "EndDate": datetime,
@@ -591,15 +612,15 @@
         "LastModificationDate": datetime,
         "Name": str,
         "ScheduleExpression": str,
         "ScheduleExpressionTimezone": str,
         "StartDate": datetime,
         "State": ScheduleStateType,
         "Target": TargetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateScheduleInputRequestTypeDef = TypedDict(
     "_RequiredUpdateScheduleInputRequestTypeDef",
     {
         "FlexibleTimeWindow": FlexibleTimeWindowTypeDef,
@@ -619,11 +640,12 @@
         "ScheduleExpressionTimezone": str,
         "StartDate": Union[datetime, str],
         "State": ScheduleStateType,
     },
     total=False,
 )
 
+
 class UpdateScheduleInputRequestTypeDef(
     _RequiredUpdateScheduleInputRequestTypeDef, _OptionalUpdateScheduleInputRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/PKG-INFO` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-scheduler
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EventBridgeScheduler 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EventBridgeScheduler 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-scheduler"></a>
 
 # types-aiobotocore-scheduler
 
 [![PyPI - types-aiobotocore-scheduler](https://img.shields.io/pypi/v/types-aiobotocore-scheduler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-scheduler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-scheduler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-scheduler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-scheduler?color=blue)](https://pypistats.org/packages/types-aiobotocore-scheduler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridgeScheduler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler)
+[aiobotocore.EventBridgeScheduler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/scheduler.html#EventBridgeScheduler)
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
 [types-aiobotocore-scheduler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_scheduler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,45 +332,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_scheduler.type_defs import (
     AwsVpcConfigurationTypeDef,
     CapacityProviderStrategyItemTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateScheduleGroupOutputTypeDef,
     FlexibleTimeWindowTypeDef,
+    CreateScheduleOutputTypeDef,
     DeadLetterConfigTypeDef,
     DeleteScheduleGroupInputRequestTypeDef,
     DeleteScheduleInputRequestTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
     EventBridgeParametersTypeDef,
     GetScheduleGroupInputRequestTypeDef,
+    GetScheduleGroupOutputTypeDef,
     GetScheduleInputRequestTypeDef,
     KinesisParametersTypeDef,
-    PaginatorConfigTypeDef,
+    ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef,
     ListScheduleGroupsInputRequestTypeDef,
     ScheduleGroupSummaryTypeDef,
+    ListSchedulesInputListSchedulesPaginateTypeDef,
     ListSchedulesInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RetryPolicyTypeDef,
     SageMakerPipelineParameterTypeDef,
     TargetSummaryTypeDef,
     SqsParametersTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateScheduleOutputTypeDef,
     NetworkConfigurationTypeDef,
     CreateScheduleGroupInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
-    CreateScheduleGroupOutputTypeDef,
-    CreateScheduleOutputTypeDef,
-    GetScheduleGroupOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
-    UpdateScheduleOutputTypeDef,
-    ListScheduleGroupsInputListScheduleGroupsPaginateTypeDef,
-    ListSchedulesInputListSchedulesPaginateTypeDef,
+    TagResourceInputRequestTypeDef,
     ListScheduleGroupsOutputTypeDef,
     SageMakerPipelineParametersTypeDef,
     ScheduleSummaryTypeDef,
     EcsParametersTypeDef,
     ListSchedulesOutputTypeDef,
     TargetTypeDef,
     CreateScheduleInputRequestTypeDef,
@@ -386,43 +386,43 @@
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

### Comparing `types-aiobotocore-scheduler-2.5.0.post1/types_aiobotocore_scheduler.egg-info/SOURCES.txt` & `types-aiobotocore-scheduler-2.5.1/types_aiobotocore_scheduler.egg-info/SOURCES.txt`

 * *Files identical despite different names*

