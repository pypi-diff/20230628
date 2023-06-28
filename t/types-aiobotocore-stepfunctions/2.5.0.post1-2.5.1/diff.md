# Comparing `tmp/types-aiobotocore-stepfunctions-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-stepfunctions-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-stepfunctions-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:25 2023, max compression
+gzip compressed data, was "types-aiobotocore-stepfunctions-2.5.1.tar", last modified: Wed Jun 28 01:44:15 2023, max compression
```

## Comparing `types-aiobotocore-stepfunctions-2.5.0.post1.tar` & `types-aiobotocore-stepfunctions-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.475676 types-aiobotocore-stepfunctions-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17733 2023-03-11 12:27:25.467676 types-aiobotocore-stepfunctions-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16148 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:25.475676 types-aiobotocore-stepfunctions-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.467676 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/
--rw-r--r--   0 runner    (1001) docker     (123)     1465 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1464 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23974 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23934 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10622 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10620 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6809 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6801 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    37038 2023-03-11 12:24:47.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    36983 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:46.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.467676 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17733 2023-03-11 12:27:25.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:27:25.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:27:25.000000 types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:15.134222 types-aiobotocore-stepfunctions-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18500 2023-06-28 01:44:15.130222 types-aiobotocore-stepfunctions-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16921 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:15.134222 types-aiobotocore-stepfunctions-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2150 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:15.122222 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/
+-rw-r--r--   0 runner    (1001) docker     (123)     1465 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1464 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30282 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30234 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10831 2023-06-28 01:41:36.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10829 2023-06-28 01:41:36.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6699 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6692 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    43965 2023-06-28 01:41:36.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43900 2023-06-28 01:41:36.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:35.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:15.130222 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18500 2023-06-28 01:44:14.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:44:14.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:14.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:44:14.000000 types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/LICENSE` & `types-aiobotocore-stepfunctions-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/PKG-INFO` & `types-aiobotocore-stepfunctions-2.5.1/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-stepfunctions
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SFN 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SFN 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-stepfunctions"></a>
 
 # types-aiobotocore-stepfunctions
 
 [![PyPI - types-aiobotocore-stepfunctions](https://img.shields.io/pypi/v/types-aiobotocore-stepfunctions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-stepfunctions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-stepfunctions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-stepfunctions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-stepfunctions?color=blue)](https://pypistats.org/packages/types-aiobotocore-stepfunctions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SFN 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN)
+[aiobotocore.SFN 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN)
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
 [types-aiobotocore-stepfunctions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,31 +348,39 @@
     HistoryEventExecutionDataDetailsTypeDef,
     ActivityStartedEventDetailsTypeDef,
     ActivityTimedOutEventDetailsTypeDef,
     BillingDetailsTypeDef,
     CloudWatchEventsExecutionDataDetailsTypeDef,
     CloudWatchLogsLogGroupTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateActivityOutputTypeDef,
+    RoutingConfigurationListItemTypeDef,
+    CreateStateMachineAliasOutputTypeDef,
     TracingConfigurationTypeDef,
+    CreateStateMachineOutputTypeDef,
     DeleteActivityInputRequestTypeDef,
+    DeleteStateMachineAliasInputRequestTypeDef,
     DeleteStateMachineInputRequestTypeDef,
+    DeleteStateMachineVersionInputRequestTypeDef,
     DescribeActivityInputRequestTypeDef,
+    DescribeActivityOutputTypeDef,
     DescribeExecutionInputRequestTypeDef,
     DescribeMapRunInputRequestTypeDef,
     MapRunExecutionCountsTypeDef,
     MapRunItemCountsTypeDef,
+    DescribeStateMachineAliasInputRequestTypeDef,
     DescribeStateMachineForExecutionInputRequestTypeDef,
     DescribeStateMachineInputRequestTypeDef,
     ExecutionAbortedEventDetailsTypeDef,
     ExecutionFailedEventDetailsTypeDef,
     ExecutionListItemTypeDef,
     ExecutionTimedOutEventDetailsTypeDef,
     GetActivityTaskInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetActivityTaskOutputTypeDef,
+    GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
     GetExecutionHistoryInputRequestTypeDef,
     LambdaFunctionFailedEventDetailsTypeDef,
     LambdaFunctionScheduleFailedEventDetailsTypeDef,
     LambdaFunctionStartFailedEventDetailsTypeDef,
     LambdaFunctionTimedOutEventDetailsTypeDef,
     MapIterationEventDetailsTypeDef,
     MapRunFailedEventDetailsTypeDef,
@@ -380,62 +388,71 @@
     MapStateStartedEventDetailsTypeDef,
     TaskFailedEventDetailsTypeDef,
     TaskStartFailedEventDetailsTypeDef,
     TaskStartedEventDetailsTypeDef,
     TaskSubmitFailedEventDetailsTypeDef,
     TaskTimedOutEventDetailsTypeDef,
     TaskCredentialsTypeDef,
+    ListActivitiesInputListActivitiesPaginateTypeDef,
     ListActivitiesInputRequestTypeDef,
+    ListExecutionsInputListExecutionsPaginateTypeDef,
     ListExecutionsInputRequestTypeDef,
+    ListMapRunsInputListMapRunsPaginateTypeDef,
     ListMapRunsInputRequestTypeDef,
     MapRunListItemTypeDef,
+    ListStateMachineAliasesInputRequestTypeDef,
+    StateMachineAliasListItemTypeDef,
+    ListStateMachineVersionsInputRequestTypeDef,
+    StateMachineVersionListItemTypeDef,
+    ListStateMachinesInputListStateMachinesPaginateTypeDef,
     ListStateMachinesInputRequestTypeDef,
     StateMachineListItemTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PublishStateMachineVersionInputRequestTypeDef,
+    PublishStateMachineVersionOutputTypeDef,
+    ResponseMetadataTypeDef,
     SendTaskFailureInputRequestTypeDef,
     SendTaskHeartbeatInputRequestTypeDef,
     SendTaskSuccessInputRequestTypeDef,
     StartExecutionInputRequestTypeDef,
+    StartExecutionOutputTypeDef,
     StartSyncExecutionInputRequestTypeDef,
     StopExecutionInputRequestTypeDef,
+    StopExecutionOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateMapRunInputRequestTypeDef,
+    UpdateStateMachineAliasOutputTypeDef,
+    UpdateStateMachineOutputTypeDef,
+    ListActivitiesOutputTypeDef,
     ActivityScheduledEventDetailsTypeDef,
     ActivitySucceededEventDetailsTypeDef,
     ExecutionStartedEventDetailsTypeDef,
     ExecutionSucceededEventDetailsTypeDef,
     LambdaFunctionSucceededEventDetailsTypeDef,
     StateEnteredEventDetailsTypeDef,
     StateExitedEventDetailsTypeDef,
     TaskSubmittedEventDetailsTypeDef,
     TaskSucceededEventDetailsTypeDef,
+    DescribeExecutionOutputTypeDef,
+    StartSyncExecutionOutputTypeDef,
     LogDestinationTypeDef,
     CreateActivityInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
-    CreateActivityOutputTypeDef,
-    CreateStateMachineOutputTypeDef,
-    DescribeActivityOutputTypeDef,
-    DescribeExecutionOutputTypeDef,
-    GetActivityTaskOutputTypeDef,
-    ListActivitiesOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
-    StartExecutionOutputTypeDef,
-    StartSyncExecutionOutputTypeDef,
-    StopExecutionOutputTypeDef,
-    UpdateStateMachineOutputTypeDef,
+    TagResourceInputRequestTypeDef,
+    CreateStateMachineAliasInputRequestTypeDef,
+    DescribeStateMachineAliasOutputTypeDef,
+    UpdateStateMachineAliasInputRequestTypeDef,
     DescribeMapRunOutputTypeDef,
     ListExecutionsOutputTypeDef,
-    GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
-    ListActivitiesInputListActivitiesPaginateTypeDef,
-    ListExecutionsInputListExecutionsPaginateTypeDef,
-    ListMapRunsInputListMapRunsPaginateTypeDef,
-    ListStateMachinesInputListStateMachinesPaginateTypeDef,
     LambdaFunctionScheduledEventDetailsTypeDef,
     TaskScheduledEventDetailsTypeDef,
     ListMapRunsOutputTypeDef,
+    ListStateMachineAliasesOutputTypeDef,
+    ListStateMachineVersionsOutputTypeDef,
     ListStateMachinesOutputTypeDef,
     LoggingConfigurationTypeDef,
     HistoryEventTypeDef,
     CreateStateMachineInputRequestTypeDef,
     DescribeStateMachineForExecutionOutputTypeDef,
     DescribeStateMachineOutputTypeDef,
     UpdateStateMachineInputRequestTypeDef,
@@ -450,43 +467,43 @@
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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/README.md` & `types-aiobotocore-stepfunctions-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-stepfunctions"></a>
 
 # types-aiobotocore-stepfunctions
 
 [![PyPI - types-aiobotocore-stepfunctions](https://img.shields.io/pypi/v/types-aiobotocore-stepfunctions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-stepfunctions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-stepfunctions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-stepfunctions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-stepfunctions?color=blue)](https://pypistats.org/packages/types-aiobotocore-stepfunctions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SFN 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN)
+[aiobotocore.SFN 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN)
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
 [types-aiobotocore-stepfunctions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,31 +315,39 @@
     HistoryEventExecutionDataDetailsTypeDef,
     ActivityStartedEventDetailsTypeDef,
     ActivityTimedOutEventDetailsTypeDef,
     BillingDetailsTypeDef,
     CloudWatchEventsExecutionDataDetailsTypeDef,
     CloudWatchLogsLogGroupTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateActivityOutputTypeDef,
+    RoutingConfigurationListItemTypeDef,
+    CreateStateMachineAliasOutputTypeDef,
     TracingConfigurationTypeDef,
+    CreateStateMachineOutputTypeDef,
     DeleteActivityInputRequestTypeDef,
+    DeleteStateMachineAliasInputRequestTypeDef,
     DeleteStateMachineInputRequestTypeDef,
+    DeleteStateMachineVersionInputRequestTypeDef,
     DescribeActivityInputRequestTypeDef,
+    DescribeActivityOutputTypeDef,
     DescribeExecutionInputRequestTypeDef,
     DescribeMapRunInputRequestTypeDef,
     MapRunExecutionCountsTypeDef,
     MapRunItemCountsTypeDef,
+    DescribeStateMachineAliasInputRequestTypeDef,
     DescribeStateMachineForExecutionInputRequestTypeDef,
     DescribeStateMachineInputRequestTypeDef,
     ExecutionAbortedEventDetailsTypeDef,
     ExecutionFailedEventDetailsTypeDef,
     ExecutionListItemTypeDef,
     ExecutionTimedOutEventDetailsTypeDef,
     GetActivityTaskInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetActivityTaskOutputTypeDef,
+    GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
     GetExecutionHistoryInputRequestTypeDef,
     LambdaFunctionFailedEventDetailsTypeDef,
     LambdaFunctionScheduleFailedEventDetailsTypeDef,
     LambdaFunctionStartFailedEventDetailsTypeDef,
     LambdaFunctionTimedOutEventDetailsTypeDef,
     MapIterationEventDetailsTypeDef,
     MapRunFailedEventDetailsTypeDef,
@@ -347,62 +355,71 @@
     MapStateStartedEventDetailsTypeDef,
     TaskFailedEventDetailsTypeDef,
     TaskStartFailedEventDetailsTypeDef,
     TaskStartedEventDetailsTypeDef,
     TaskSubmitFailedEventDetailsTypeDef,
     TaskTimedOutEventDetailsTypeDef,
     TaskCredentialsTypeDef,
+    ListActivitiesInputListActivitiesPaginateTypeDef,
     ListActivitiesInputRequestTypeDef,
+    ListExecutionsInputListExecutionsPaginateTypeDef,
     ListExecutionsInputRequestTypeDef,
+    ListMapRunsInputListMapRunsPaginateTypeDef,
     ListMapRunsInputRequestTypeDef,
     MapRunListItemTypeDef,
+    ListStateMachineAliasesInputRequestTypeDef,
+    StateMachineAliasListItemTypeDef,
+    ListStateMachineVersionsInputRequestTypeDef,
+    StateMachineVersionListItemTypeDef,
+    ListStateMachinesInputListStateMachinesPaginateTypeDef,
     ListStateMachinesInputRequestTypeDef,
     StateMachineListItemTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PublishStateMachineVersionInputRequestTypeDef,
+    PublishStateMachineVersionOutputTypeDef,
+    ResponseMetadataTypeDef,
     SendTaskFailureInputRequestTypeDef,
     SendTaskHeartbeatInputRequestTypeDef,
     SendTaskSuccessInputRequestTypeDef,
     StartExecutionInputRequestTypeDef,
+    StartExecutionOutputTypeDef,
     StartSyncExecutionInputRequestTypeDef,
     StopExecutionInputRequestTypeDef,
+    StopExecutionOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateMapRunInputRequestTypeDef,
+    UpdateStateMachineAliasOutputTypeDef,
+    UpdateStateMachineOutputTypeDef,
+    ListActivitiesOutputTypeDef,
     ActivityScheduledEventDetailsTypeDef,
     ActivitySucceededEventDetailsTypeDef,
     ExecutionStartedEventDetailsTypeDef,
     ExecutionSucceededEventDetailsTypeDef,
     LambdaFunctionSucceededEventDetailsTypeDef,
     StateEnteredEventDetailsTypeDef,
     StateExitedEventDetailsTypeDef,
     TaskSubmittedEventDetailsTypeDef,
     TaskSucceededEventDetailsTypeDef,
+    DescribeExecutionOutputTypeDef,
+    StartSyncExecutionOutputTypeDef,
     LogDestinationTypeDef,
     CreateActivityInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
-    CreateActivityOutputTypeDef,
-    CreateStateMachineOutputTypeDef,
-    DescribeActivityOutputTypeDef,
-    DescribeExecutionOutputTypeDef,
-    GetActivityTaskOutputTypeDef,
-    ListActivitiesOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
-    StartExecutionOutputTypeDef,
-    StartSyncExecutionOutputTypeDef,
-    StopExecutionOutputTypeDef,
-    UpdateStateMachineOutputTypeDef,
+    TagResourceInputRequestTypeDef,
+    CreateStateMachineAliasInputRequestTypeDef,
+    DescribeStateMachineAliasOutputTypeDef,
+    UpdateStateMachineAliasInputRequestTypeDef,
     DescribeMapRunOutputTypeDef,
     ListExecutionsOutputTypeDef,
-    GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
-    ListActivitiesInputListActivitiesPaginateTypeDef,
-    ListExecutionsInputListExecutionsPaginateTypeDef,
-    ListMapRunsInputListMapRunsPaginateTypeDef,
-    ListStateMachinesInputListStateMachinesPaginateTypeDef,
     LambdaFunctionScheduledEventDetailsTypeDef,
     TaskScheduledEventDetailsTypeDef,
     ListMapRunsOutputTypeDef,
+    ListStateMachineAliasesOutputTypeDef,
+    ListStateMachineVersionsOutputTypeDef,
     ListStateMachinesOutputTypeDef,
     LoggingConfigurationTypeDef,
     HistoryEventTypeDef,
     CreateStateMachineInputRequestTypeDef,
     DescribeStateMachineForExecutionOutputTypeDef,
     DescribeStateMachineOutputTypeDef,
     UpdateStateMachineInputRequestTypeDef,
@@ -417,43 +434,43 @@
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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/setup.py` & `types-aiobotocore-stepfunctions-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-stepfunctions.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-stepfunctions",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_stepfunctions"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SFN 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SFN 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/"
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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/__init__.py` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/__init__.pyi` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/__main__.py` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SFN 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SFN 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN\nOther"
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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/client.py` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/client.py`

 * *Files 8% similar despite different names*

```diff
@@ -26,33 +26,40 @@
     ListActivitiesPaginator,
     ListExecutionsPaginator,
     ListMapRunsPaginator,
     ListStateMachinesPaginator,
 )
 from .type_defs import (
     CreateActivityOutputTypeDef,
+    CreateStateMachineAliasOutputTypeDef,
     CreateStateMachineOutputTypeDef,
     DescribeActivityOutputTypeDef,
     DescribeExecutionOutputTypeDef,
     DescribeMapRunOutputTypeDef,
+    DescribeStateMachineAliasOutputTypeDef,
     DescribeStateMachineForExecutionOutputTypeDef,
     DescribeStateMachineOutputTypeDef,
     GetActivityTaskOutputTypeDef,
     GetExecutionHistoryOutputTypeDef,
     ListActivitiesOutputTypeDef,
     ListExecutionsOutputTypeDef,
     ListMapRunsOutputTypeDef,
+    ListStateMachineAliasesOutputTypeDef,
     ListStateMachinesOutputTypeDef,
+    ListStateMachineVersionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     LoggingConfigurationTypeDef,
+    PublishStateMachineVersionOutputTypeDef,
+    RoutingConfigurationListItemTypeDef,
     StartExecutionOutputTypeDef,
     StartSyncExecutionOutputTypeDef,
     StopExecutionOutputTypeDef,
     TagTypeDef,
     TracingConfigurationTypeDef,
+    UpdateStateMachineAliasOutputTypeDef,
     UpdateStateMachineOutputTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -70,27 +77,29 @@
 
 
 class Exceptions:
     ActivityDoesNotExist: Type[BotocoreClientError]
     ActivityLimitExceeded: Type[BotocoreClientError]
     ActivityWorkerLimitExceeded: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     ExecutionAlreadyExists: Type[BotocoreClientError]
     ExecutionDoesNotExist: Type[BotocoreClientError]
     ExecutionLimitExceeded: Type[BotocoreClientError]
     InvalidArn: Type[BotocoreClientError]
     InvalidDefinition: Type[BotocoreClientError]
     InvalidExecutionInput: Type[BotocoreClientError]
     InvalidLoggingConfiguration: Type[BotocoreClientError]
     InvalidName: Type[BotocoreClientError]
     InvalidOutput: Type[BotocoreClientError]
     InvalidToken: Type[BotocoreClientError]
     InvalidTracingConfiguration: Type[BotocoreClientError]
     MissingRequiredParameter: Type[BotocoreClientError]
     ResourceNotFound: Type[BotocoreClientError]
+    ServiceQuotaExceededException: Type[BotocoreClientError]
     StateMachineAlreadyExists: Type[BotocoreClientError]
     StateMachineDeleting: Type[BotocoreClientError]
     StateMachineDoesNotExist: Type[BotocoreClientError]
     StateMachineLimitExceeded: Type[BotocoreClientError]
     StateMachineTypeNotSupported: Type[BotocoreClientError]
     TaskDoesNotExist: Type[BotocoreClientError]
     TaskTimedOut: Type[BotocoreClientError]
@@ -146,23 +155,43 @@
         *,
         name: str,
         definition: str,
         roleArn: str,
         type: StateMachineTypeType = ...,
         loggingConfiguration: LoggingConfigurationTypeDef = ...,
         tags: Sequence[TagTypeDef] = ...,
-        tracingConfiguration: TracingConfigurationTypeDef = ...
+        tracingConfiguration: TracingConfigurationTypeDef = ...,
+        publish: bool = ...,
+        versionDescription: str = ...
     ) -> CreateStateMachineOutputTypeDef:
         """
         Creates a state machine.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.create_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#create_state_machine)
         """
 
+    async def create_state_machine_alias(
+        self,
+        *,
+        name: str,
+        routingConfiguration: Sequence[RoutingConfigurationListItemTypeDef],
+        description: str = ...
+    ) -> CreateStateMachineAliasOutputTypeDef:
+        """
+        Creates an [alias](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-alias.html)_ for a state machine that
+        points to one or two [versions](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-version.html)_ of the same state
+        machine.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.create_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#create_state_machine_alias)
+        """
+
     async def delete_activity(self, *, activityArn: str) -> Dict[str, Any]:
         """
         Deletes an activity.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_activity)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_activity)
         """
@@ -171,27 +200,45 @@
         """
         Deletes a state machine.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_state_machine)
         """
 
+    async def delete_state_machine_alias(self, *, stateMachineAliasArn: str) -> Dict[str, Any]:
+        """
+        Deletes a state machine [alias](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-alias.html)_.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_state_machine_alias)
+        """
+
+    async def delete_state_machine_version(self, *, stateMachineVersionArn: str) -> Dict[str, Any]:
+        """
+        Deletes a state machine [version](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-version.html)_.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_state_machine_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_state_machine_version)
+        """
+
     async def describe_activity(self, *, activityArn: str) -> DescribeActivityOutputTypeDef:
         """
         Describes an activity.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_activity)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_activity)
         """
 
     async def describe_execution(self, *, executionArn: str) -> DescribeExecutionOutputTypeDef:
         """
-        Provides all information about a state machine execution, such as the state
-        machine associated with the execution, the execution input and output, and
-        relevant execution metadata.
+        Provides information about a state machine execution, such as the state machine
+        associated with the execution, the execution input and output, and relevant
+        execution metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_execution)
         """
 
     async def describe_map_run(self, *, mapRunArn: str) -> DescribeMapRunOutputTypeDef:
         """
@@ -208,14 +255,25 @@
         Provides information about a state machine's definition, its IAM role Amazon
         Resource Name (ARN), and configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_state_machine)
         """
 
+    async def describe_state_machine_alias(
+        self, *, stateMachineAliasArn: str
+    ) -> DescribeStateMachineAliasOutputTypeDef:
+        """
+        Returns details about a state machine [alias](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-alias.html)_.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_state_machine_alias)
+        """
+
     async def describe_state_machine_for_execution(
         self, *, executionArn: str
     ) -> DescribeStateMachineForExecutionOutputTypeDef:
         """
         Provides information about a state machine's definition, its execution role ARN,
         and configuration.
 
@@ -296,14 +354,37 @@
         """
         Lists all Map Runs that were started by a given state machine execution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_map_runs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_map_runs)
         """
 
+    async def list_state_machine_aliases(
+        self, *, stateMachineArn: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListStateMachineAliasesOutputTypeDef:
+        """
+        Lists [aliases](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-
+        state-machine-alias.html)_ for a specified state machine ARN.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_state_machine_aliases)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_state_machine_aliases)
+        """
+
+    async def list_state_machine_versions(
+        self, *, stateMachineArn: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListStateMachineVersionsOutputTypeDef:
+        """
+        Lists [versions](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-
+        state-machine-version.html)_ for the specified state machine Amazon Resource
+        Name (ARN).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_state_machine_versions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_state_machine_versions)
+        """
+
     async def list_state_machines(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListStateMachinesOutputTypeDef:
         """
         Lists the existing state machines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_state_machines)
@@ -314,14 +395,26 @@
         """
         List tags for a given resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_tags_for_resource)
         """
 
+    async def publish_state_machine_version(
+        self, *, stateMachineArn: str, revisionId: str = ..., description: str = ...
+    ) -> PublishStateMachineVersionOutputTypeDef:
+        """
+        Creates a [version](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-version.html)_ from the current
+        revision of a state machine.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.publish_state_machine_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#publish_state_machine_version)
+        """
+
     async def send_task_failure(
         self, *, taskToken: str, error: str = ..., cause: str = ...
     ) -> Dict[str, Any]:
         """
         Used by activity workers and task states using the
         [callback](https://docs.aws.amazon.com/step-functions/latest/dg/connect-to-
         resource.html#connect-wait-token)_ pattern to report that the task identified by
@@ -419,24 +512,42 @@
     async def update_state_machine(
         self,
         *,
         stateMachineArn: str,
         definition: str = ...,
         roleArn: str = ...,
         loggingConfiguration: LoggingConfigurationTypeDef = ...,
-        tracingConfiguration: TracingConfigurationTypeDef = ...
+        tracingConfiguration: TracingConfigurationTypeDef = ...,
+        publish: bool = ...,
+        versionDescription: str = ...
     ) -> UpdateStateMachineOutputTypeDef:
         """
-        Updates an existing state machine by modifying its `definition` , `roleArn` , or
+        Updates an existing state machine by modifying its `definition`, `roleArn`, or
         `loggingConfiguration`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.update_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#update_state_machine)
         """
 
+    async def update_state_machine_alias(
+        self,
+        *,
+        stateMachineAliasArn: str,
+        description: str = ...,
+        routingConfiguration: Sequence[RoutingConfigurationListItemTypeDef] = ...
+    ) -> UpdateStateMachineAliasOutputTypeDef:
+        """
+        Updates the configuration of an existing state machine
+        [alias](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-state-
+        machine-alias.html)_ by modifying its `description` or `routingConfiguration`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.update_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#update_state_machine_alias)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["get_execution_history"]
     ) -> GetExecutionHistoryPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#get_paginator)
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/client.pyi` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/client.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -26,33 +26,40 @@
     ListActivitiesPaginator,
     ListExecutionsPaginator,
     ListMapRunsPaginator,
     ListStateMachinesPaginator,
 )
 from .type_defs import (
     CreateActivityOutputTypeDef,
+    CreateStateMachineAliasOutputTypeDef,
     CreateStateMachineOutputTypeDef,
     DescribeActivityOutputTypeDef,
     DescribeExecutionOutputTypeDef,
     DescribeMapRunOutputTypeDef,
+    DescribeStateMachineAliasOutputTypeDef,
     DescribeStateMachineForExecutionOutputTypeDef,
     DescribeStateMachineOutputTypeDef,
     GetActivityTaskOutputTypeDef,
     GetExecutionHistoryOutputTypeDef,
     ListActivitiesOutputTypeDef,
     ListExecutionsOutputTypeDef,
     ListMapRunsOutputTypeDef,
+    ListStateMachineAliasesOutputTypeDef,
     ListStateMachinesOutputTypeDef,
+    ListStateMachineVersionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     LoggingConfigurationTypeDef,
+    PublishStateMachineVersionOutputTypeDef,
+    RoutingConfigurationListItemTypeDef,
     StartExecutionOutputTypeDef,
     StartSyncExecutionOutputTypeDef,
     StopExecutionOutputTypeDef,
     TagTypeDef,
     TracingConfigurationTypeDef,
+    UpdateStateMachineAliasOutputTypeDef,
     UpdateStateMachineOutputTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -67,27 +74,29 @@
         self.operation_name: str
 
 class Exceptions:
     ActivityDoesNotExist: Type[BotocoreClientError]
     ActivityLimitExceeded: Type[BotocoreClientError]
     ActivityWorkerLimitExceeded: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     ExecutionAlreadyExists: Type[BotocoreClientError]
     ExecutionDoesNotExist: Type[BotocoreClientError]
     ExecutionLimitExceeded: Type[BotocoreClientError]
     InvalidArn: Type[BotocoreClientError]
     InvalidDefinition: Type[BotocoreClientError]
     InvalidExecutionInput: Type[BotocoreClientError]
     InvalidLoggingConfiguration: Type[BotocoreClientError]
     InvalidName: Type[BotocoreClientError]
     InvalidOutput: Type[BotocoreClientError]
     InvalidToken: Type[BotocoreClientError]
     InvalidTracingConfiguration: Type[BotocoreClientError]
     MissingRequiredParameter: Type[BotocoreClientError]
     ResourceNotFound: Type[BotocoreClientError]
+    ServiceQuotaExceededException: Type[BotocoreClientError]
     StateMachineAlreadyExists: Type[BotocoreClientError]
     StateMachineDeleting: Type[BotocoreClientError]
     StateMachineDoesNotExist: Type[BotocoreClientError]
     StateMachineLimitExceeded: Type[BotocoreClientError]
     StateMachineTypeNotSupported: Type[BotocoreClientError]
     TaskDoesNotExist: Type[BotocoreClientError]
     TaskTimedOut: Type[BotocoreClientError]
@@ -138,48 +147,83 @@
         *,
         name: str,
         definition: str,
         roleArn: str,
         type: StateMachineTypeType = ...,
         loggingConfiguration: LoggingConfigurationTypeDef = ...,
         tags: Sequence[TagTypeDef] = ...,
-        tracingConfiguration: TracingConfigurationTypeDef = ...
+        tracingConfiguration: TracingConfigurationTypeDef = ...,
+        publish: bool = ...,
+        versionDescription: str = ...
     ) -> CreateStateMachineOutputTypeDef:
         """
         Creates a state machine.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.create_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#create_state_machine)
         """
+    async def create_state_machine_alias(
+        self,
+        *,
+        name: str,
+        routingConfiguration: Sequence[RoutingConfigurationListItemTypeDef],
+        description: str = ...
+    ) -> CreateStateMachineAliasOutputTypeDef:
+        """
+        Creates an [alias](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-alias.html)_ for a state machine that
+        points to one or two [versions](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-version.html)_ of the same state
+        machine.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.create_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#create_state_machine_alias)
+        """
     async def delete_activity(self, *, activityArn: str) -> Dict[str, Any]:
         """
         Deletes an activity.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_activity)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_activity)
         """
     async def delete_state_machine(self, *, stateMachineArn: str) -> Dict[str, Any]:
         """
         Deletes a state machine.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_state_machine)
         """
+    async def delete_state_machine_alias(self, *, stateMachineAliasArn: str) -> Dict[str, Any]:
+        """
+        Deletes a state machine [alias](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-alias.html)_.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_state_machine_alias)
+        """
+    async def delete_state_machine_version(self, *, stateMachineVersionArn: str) -> Dict[str, Any]:
+        """
+        Deletes a state machine [version](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-version.html)_.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.delete_state_machine_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#delete_state_machine_version)
+        """
     async def describe_activity(self, *, activityArn: str) -> DescribeActivityOutputTypeDef:
         """
         Describes an activity.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_activity)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_activity)
         """
     async def describe_execution(self, *, executionArn: str) -> DescribeExecutionOutputTypeDef:
         """
-        Provides all information about a state machine execution, such as the state
-        machine associated with the execution, the execution input and output, and
-        relevant execution metadata.
+        Provides information about a state machine execution, such as the state machine
+        associated with the execution, the execution input and output, and relevant
+        execution metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_execution)
         """
     async def describe_map_run(self, *, mapRunArn: str) -> DescribeMapRunOutputTypeDef:
         """
         Provides information about a Map Run's configuration, progress, and results.
@@ -193,14 +237,24 @@
         """
         Provides information about a state machine's definition, its IAM role Amazon
         Resource Name (ARN), and configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_state_machine)
         """
+    async def describe_state_machine_alias(
+        self, *, stateMachineAliasArn: str
+    ) -> DescribeStateMachineAliasOutputTypeDef:
+        """
+        Returns details about a state machine [alias](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-alias.html)_.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.describe_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#describe_state_machine_alias)
+        """
     async def describe_state_machine_for_execution(
         self, *, executionArn: str
     ) -> DescribeStateMachineForExecutionOutputTypeDef:
         """
         Provides information about a state machine's definition, its execution role ARN,
         and configuration.
 
@@ -274,14 +328,35 @@
     ) -> ListMapRunsOutputTypeDef:
         """
         Lists all Map Runs that were started by a given state machine execution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_map_runs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_map_runs)
         """
+    async def list_state_machine_aliases(
+        self, *, stateMachineArn: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListStateMachineAliasesOutputTypeDef:
+        """
+        Lists [aliases](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-
+        state-machine-alias.html)_ for a specified state machine ARN.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_state_machine_aliases)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_state_machine_aliases)
+        """
+    async def list_state_machine_versions(
+        self, *, stateMachineArn: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListStateMachineVersionsOutputTypeDef:
+        """
+        Lists [versions](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-
+        state-machine-version.html)_ for the specified state machine Amazon Resource
+        Name (ARN).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_state_machine_versions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_state_machine_versions)
+        """
     async def list_state_machines(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListStateMachinesOutputTypeDef:
         """
         Lists the existing state machines.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_state_machines)
@@ -290,14 +365,25 @@
     async def list_tags_for_resource(self, *, resourceArn: str) -> ListTagsForResourceOutputTypeDef:
         """
         List tags for a given resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#list_tags_for_resource)
         """
+    async def publish_state_machine_version(
+        self, *, stateMachineArn: str, revisionId: str = ..., description: str = ...
+    ) -> PublishStateMachineVersionOutputTypeDef:
+        """
+        Creates a [version](https://docs.aws.amazon.com/step-
+        functions/latest/dg/concepts-state-machine-version.html)_ from the current
+        revision of a state machine.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.publish_state_machine_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#publish_state_machine_version)
+        """
     async def send_task_failure(
         self, *, taskToken: str, error: str = ..., cause: str = ...
     ) -> Dict[str, Any]:
         """
         Used by activity workers and task states using the
         [callback](https://docs.aws.amazon.com/step-functions/latest/dg/connect-to-
         resource.html#connect-wait-token)_ pattern to report that the task identified by
@@ -386,23 +472,40 @@
     async def update_state_machine(
         self,
         *,
         stateMachineArn: str,
         definition: str = ...,
         roleArn: str = ...,
         loggingConfiguration: LoggingConfigurationTypeDef = ...,
-        tracingConfiguration: TracingConfigurationTypeDef = ...
+        tracingConfiguration: TracingConfigurationTypeDef = ...,
+        publish: bool = ...,
+        versionDescription: str = ...
     ) -> UpdateStateMachineOutputTypeDef:
         """
-        Updates an existing state machine by modifying its `definition` , `roleArn` , or
+        Updates an existing state machine by modifying its `definition`, `roleArn`, or
         `loggingConfiguration`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.update_state_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#update_state_machine)
         """
+    async def update_state_machine_alias(
+        self,
+        *,
+        stateMachineAliasArn: str,
+        description: str = ...,
+        routingConfiguration: Sequence[RoutingConfigurationListItemTypeDef] = ...
+    ) -> UpdateStateMachineAliasOutputTypeDef:
+        """
+        Updates the configuration of an existing state machine
+        [alias](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-state-
+        machine-alias.html)_ by modifying its `description` or `routingConfiguration`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.update_state_machine_alias)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#update_state_machine_alias)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["get_execution_history"]
     ) -> GetExecutionHistoryPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/client/#get_paginator)
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/literals.py` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -171,14 +171,15 @@
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
@@ -257,14 +258,15 @@
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
@@ -275,14 +277,15 @@
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
@@ -318,14 +321,15 @@
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
@@ -344,16 +348,19 @@
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
@@ -437,15 +444,17 @@
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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/literals.pyi` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/literals.pyi`

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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/paginator.py` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,36 +24,29 @@
         get_execution_history_paginator: GetExecutionHistoryPaginator = client.get_paginator("get_execution_history")
         list_activities_paginator: ListActivitiesPaginator = client.get_paginator("list_activities")
         list_executions_paginator: ListExecutionsPaginator = client.get_paginator("list_executions")
         list_map_runs_paginator: ListMapRunsPaginator = client.get_paginator("list_map_runs")
         list_state_machines_paginator: ListStateMachinesPaginator = client.get_paginator("list_state_machines")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ExecutionStatusType
 from .type_defs import (
     GetExecutionHistoryOutputTypeDef,
     ListActivitiesOutputTypeDef,
     ListExecutionsOutputTypeDef,
     ListMapRunsOutputTypeDef,
     ListStateMachinesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetExecutionHistoryPaginator",
     "ListActivitiesPaginator",
     "ListExecutionsPaginator",
     "ListMapRunsPaginator",
     "ListStateMachinesPaginator",
 )
@@ -77,30 +70,30 @@
 
     def paginate(
         self,
         *,
         executionArn: str,
         reverseOrder: bool = ...,
         includeExecutionData: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetExecutionHistoryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.GetExecutionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#getexecutionhistorypaginator)
         """
 
 
 class ListActivitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListActivities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listactivitiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActivitiesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listactivitiespaginator)
         """
 
 
@@ -112,43 +105,43 @@
 
     def paginate(
         self,
         *,
         stateMachineArn: str = ...,
         statusFilter: ExecutionStatusType = ...,
         mapRunArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listexecutionspaginator)
         """
 
 
 class ListMapRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListMapRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listmaprunspaginator)
     """
 
     def paginate(
-        self, *, executionArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, executionArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMapRunsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListMapRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listmaprunspaginator)
         """
 
 
 class ListStateMachinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListStateMachines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#liststatemachinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStateMachinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListStateMachines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#liststatemachinespaginator)
         """
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/paginator.pyi` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,29 @@
         get_execution_history_paginator: GetExecutionHistoryPaginator = client.get_paginator("get_execution_history")
         list_activities_paginator: ListActivitiesPaginator = client.get_paginator("list_activities")
         list_executions_paginator: ListExecutionsPaginator = client.get_paginator("list_executions")
         list_map_runs_paginator: ListMapRunsPaginator = client.get_paginator("list_map_runs")
         list_state_machines_paginator: ListStateMachinesPaginator = client.get_paginator("list_state_machines")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ExecutionStatusType
 from .type_defs import (
     GetExecutionHistoryOutputTypeDef,
     ListActivitiesOutputTypeDef,
     ListExecutionsOutputTypeDef,
     ListMapRunsOutputTypeDef,
     ListStateMachinesOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetExecutionHistoryPaginator",
     "ListActivitiesPaginator",
     "ListExecutionsPaginator",
     "ListMapRunsPaginator",
     "ListStateMachinesPaginator",
 )
@@ -73,29 +67,29 @@
 
     def paginate(
         self,
         *,
         executionArn: str,
         reverseOrder: bool = ...,
         includeExecutionData: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetExecutionHistoryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.GetExecutionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#getexecutionhistorypaginator)
         """
 
 class ListActivitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListActivities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listactivitiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActivitiesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listactivitiespaginator)
         """
 
 class ListExecutionsPaginator(AioPaginator):
@@ -106,41 +100,41 @@
 
     def paginate(
         self,
         *,
         stateMachineArn: str = ...,
         statusFilter: ExecutionStatusType = ...,
         mapRunArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listexecutionspaginator)
         """
 
 class ListMapRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListMapRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listmaprunspaginator)
     """
 
     def paginate(
-        self, *, executionArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, executionArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMapRunsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListMapRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#listmaprunspaginator)
         """
 
 class ListStateMachinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListStateMachines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#liststatemachinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStateMachinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN.Paginator.ListStateMachines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/paginators/#liststatemachinespaginator)
         """
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/type_defs.py` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/type_defs.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -26,43 +26,50 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ActivityFailedEventDetailsTypeDef",
     "ActivityListItemTypeDef",
     "ActivityScheduleFailedEventDetailsTypeDef",
     "HistoryEventExecutionDataDetailsTypeDef",
     "ActivityStartedEventDetailsTypeDef",
     "ActivityTimedOutEventDetailsTypeDef",
     "BillingDetailsTypeDef",
     "CloudWatchEventsExecutionDataDetailsTypeDef",
     "CloudWatchLogsLogGroupTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateActivityOutputTypeDef",
+    "RoutingConfigurationListItemTypeDef",
+    "CreateStateMachineAliasOutputTypeDef",
     "TracingConfigurationTypeDef",
+    "CreateStateMachineOutputTypeDef",
     "DeleteActivityInputRequestTypeDef",
+    "DeleteStateMachineAliasInputRequestTypeDef",
     "DeleteStateMachineInputRequestTypeDef",
+    "DeleteStateMachineVersionInputRequestTypeDef",
     "DescribeActivityInputRequestTypeDef",
+    "DescribeActivityOutputTypeDef",
     "DescribeExecutionInputRequestTypeDef",
     "DescribeMapRunInputRequestTypeDef",
     "MapRunExecutionCountsTypeDef",
     "MapRunItemCountsTypeDef",
+    "DescribeStateMachineAliasInputRequestTypeDef",
     "DescribeStateMachineForExecutionInputRequestTypeDef",
     "DescribeStateMachineInputRequestTypeDef",
     "ExecutionAbortedEventDetailsTypeDef",
     "ExecutionFailedEventDetailsTypeDef",
     "ExecutionListItemTypeDef",
     "ExecutionTimedOutEventDetailsTypeDef",
     "GetActivityTaskInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetActivityTaskOutputTypeDef",
+    "GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
     "GetExecutionHistoryInputRequestTypeDef",
     "LambdaFunctionFailedEventDetailsTypeDef",
     "LambdaFunctionScheduleFailedEventDetailsTypeDef",
     "LambdaFunctionStartFailedEventDetailsTypeDef",
     "LambdaFunctionTimedOutEventDetailsTypeDef",
     "MapIterationEventDetailsTypeDef",
     "MapRunFailedEventDetailsTypeDef",
@@ -70,62 +77,71 @@
     "MapStateStartedEventDetailsTypeDef",
     "TaskFailedEventDetailsTypeDef",
     "TaskStartFailedEventDetailsTypeDef",
     "TaskStartedEventDetailsTypeDef",
     "TaskSubmitFailedEventDetailsTypeDef",
     "TaskTimedOutEventDetailsTypeDef",
     "TaskCredentialsTypeDef",
+    "ListActivitiesInputListActivitiesPaginateTypeDef",
     "ListActivitiesInputRequestTypeDef",
+    "ListExecutionsInputListExecutionsPaginateTypeDef",
     "ListExecutionsInputRequestTypeDef",
+    "ListMapRunsInputListMapRunsPaginateTypeDef",
     "ListMapRunsInputRequestTypeDef",
     "MapRunListItemTypeDef",
+    "ListStateMachineAliasesInputRequestTypeDef",
+    "StateMachineAliasListItemTypeDef",
+    "ListStateMachineVersionsInputRequestTypeDef",
+    "StateMachineVersionListItemTypeDef",
+    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
     "ListStateMachinesInputRequestTypeDef",
     "StateMachineListItemTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "PublishStateMachineVersionInputRequestTypeDef",
+    "PublishStateMachineVersionOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "SendTaskFailureInputRequestTypeDef",
     "SendTaskHeartbeatInputRequestTypeDef",
     "SendTaskSuccessInputRequestTypeDef",
     "StartExecutionInputRequestTypeDef",
+    "StartExecutionOutputTypeDef",
     "StartSyncExecutionInputRequestTypeDef",
     "StopExecutionInputRequestTypeDef",
+    "StopExecutionOutputTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateMapRunInputRequestTypeDef",
+    "UpdateStateMachineAliasOutputTypeDef",
+    "UpdateStateMachineOutputTypeDef",
+    "ListActivitiesOutputTypeDef",
     "ActivityScheduledEventDetailsTypeDef",
     "ActivitySucceededEventDetailsTypeDef",
     "ExecutionStartedEventDetailsTypeDef",
     "ExecutionSucceededEventDetailsTypeDef",
     "LambdaFunctionSucceededEventDetailsTypeDef",
     "StateEnteredEventDetailsTypeDef",
     "StateExitedEventDetailsTypeDef",
     "TaskSubmittedEventDetailsTypeDef",
     "TaskSucceededEventDetailsTypeDef",
+    "DescribeExecutionOutputTypeDef",
+    "StartSyncExecutionOutputTypeDef",
     "LogDestinationTypeDef",
     "CreateActivityInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
-    "CreateActivityOutputTypeDef",
-    "CreateStateMachineOutputTypeDef",
-    "DescribeActivityOutputTypeDef",
-    "DescribeExecutionOutputTypeDef",
-    "GetActivityTaskOutputTypeDef",
-    "ListActivitiesOutputTypeDef",
     "ListTagsForResourceOutputTypeDef",
-    "StartExecutionOutputTypeDef",
-    "StartSyncExecutionOutputTypeDef",
-    "StopExecutionOutputTypeDef",
-    "UpdateStateMachineOutputTypeDef",
+    "TagResourceInputRequestTypeDef",
+    "CreateStateMachineAliasInputRequestTypeDef",
+    "DescribeStateMachineAliasOutputTypeDef",
+    "UpdateStateMachineAliasInputRequestTypeDef",
     "DescribeMapRunOutputTypeDef",
     "ListExecutionsOutputTypeDef",
-    "GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
-    "ListActivitiesInputListActivitiesPaginateTypeDef",
-    "ListExecutionsInputListExecutionsPaginateTypeDef",
-    "ListMapRunsInputListMapRunsPaginateTypeDef",
-    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
     "LambdaFunctionScheduledEventDetailsTypeDef",
     "TaskScheduledEventDetailsTypeDef",
     "ListMapRunsOutputTypeDef",
+    "ListStateMachineAliasesOutputTypeDef",
+    "ListStateMachineVersionsOutputTypeDef",
     "ListStateMachinesOutputTypeDef",
     "LoggingConfigurationTypeDef",
     "HistoryEventTypeDef",
     "CreateStateMachineInputRequestTypeDef",
     "DescribeStateMachineForExecutionOutputTypeDef",
     "DescribeStateMachineOutputTypeDef",
     "UpdateStateMachineInputRequestTypeDef",
@@ -214,54 +230,103 @@
     {
         "key": str,
         "value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateActivityOutputTypeDef = TypedDict(
+    "CreateActivityOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "activityArn": str,
+        "creationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RoutingConfigurationListItemTypeDef = TypedDict(
+    "RoutingConfigurationListItemTypeDef",
+    {
+        "stateMachineVersionArn": str,
+        "weight": int,
+    },
+)
+
+CreateStateMachineAliasOutputTypeDef = TypedDict(
+    "CreateStateMachineAliasOutputTypeDef",
+    {
+        "stateMachineAliasArn": str,
+        "creationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TracingConfigurationTypeDef = TypedDict(
     "TracingConfigurationTypeDef",
     {
         "enabled": bool,
     },
     total=False,
 )
 
+CreateStateMachineOutputTypeDef = TypedDict(
+    "CreateStateMachineOutputTypeDef",
+    {
+        "stateMachineArn": str,
+        "creationDate": datetime,
+        "stateMachineVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteActivityInputRequestTypeDef = TypedDict(
     "DeleteActivityInputRequestTypeDef",
     {
         "activityArn": str,
     },
 )
 
+DeleteStateMachineAliasInputRequestTypeDef = TypedDict(
+    "DeleteStateMachineAliasInputRequestTypeDef",
+    {
+        "stateMachineAliasArn": str,
+    },
+)
+
 DeleteStateMachineInputRequestTypeDef = TypedDict(
     "DeleteStateMachineInputRequestTypeDef",
     {
         "stateMachineArn": str,
     },
 )
 
+DeleteStateMachineVersionInputRequestTypeDef = TypedDict(
+    "DeleteStateMachineVersionInputRequestTypeDef",
+    {
+        "stateMachineVersionArn": str,
+    },
+)
+
 DescribeActivityInputRequestTypeDef = TypedDict(
     "DescribeActivityInputRequestTypeDef",
     {
         "activityArn": str,
     },
 )
 
+DescribeActivityOutputTypeDef = TypedDict(
+    "DescribeActivityOutputTypeDef",
+    {
+        "activityArn": str,
+        "name": str,
+        "creationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeExecutionInputRequestTypeDef = TypedDict(
     "DescribeExecutionInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 
@@ -296,14 +361,21 @@
         "timedOut": int,
         "aborted": int,
         "total": int,
         "resultsWritten": int,
     },
 )
 
+DescribeStateMachineAliasInputRequestTypeDef = TypedDict(
+    "DescribeStateMachineAliasInputRequestTypeDef",
+    {
+        "stateMachineAliasArn": str,
+    },
+)
+
 DescribeStateMachineForExecutionInputRequestTypeDef = TypedDict(
     "DescribeStateMachineForExecutionInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 
@@ -344,25 +416,25 @@
 )
 _OptionalExecutionListItemTypeDef = TypedDict(
     "_OptionalExecutionListItemTypeDef",
     {
         "stopDate": datetime,
         "mapRunArn": str,
         "itemCount": int,
+        "stateMachineVersionArn": str,
+        "stateMachineAliasArn": str,
     },
     total=False,
 )
 
-
 class ExecutionListItemTypeDef(
     _RequiredExecutionListItemTypeDef, _OptionalExecutionListItemTypeDef
 ):
     pass
 
-
 ExecutionTimedOutEventDetailsTypeDef = TypedDict(
     "ExecutionTimedOutEventDetailsTypeDef",
     {
         "error": str,
         "cause": str,
     },
     total=False,
@@ -378,31 +450,50 @@
     "_OptionalGetActivityTaskInputRequestTypeDef",
     {
         "workerName": str,
     },
     total=False,
 )
 
-
 class GetActivityTaskInputRequestTypeDef(
     _RequiredGetActivityTaskInputRequestTypeDef, _OptionalGetActivityTaskInputRequestTypeDef
 ):
     pass
 
+GetActivityTaskOutputTypeDef = TypedDict(
+    "GetActivityTaskOutputTypeDef",
+    {
+        "taskToken": str,
+        "input": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "executionArn": str,
+    },
+)
+_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+    {
+        "reverseOrder": bool,
+        "includeExecutionData": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef(
+    _RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
+    _OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetExecutionHistoryInputRequestTypeDef = TypedDict(
     "_RequiredGetExecutionHistoryInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 _OptionalGetExecutionHistoryInputRequestTypeDef = TypedDict(
@@ -412,21 +503,19 @@
         "reverseOrder": bool,
         "nextToken": str,
         "includeExecutionData": bool,
     },
     total=False,
 )
 
-
 class GetExecutionHistoryInputRequestTypeDef(
     _RequiredGetExecutionHistoryInputRequestTypeDef, _OptionalGetExecutionHistoryInputRequestTypeDef
 ):
     pass
 
-
 LambdaFunctionFailedEventDetailsTypeDef = TypedDict(
     "LambdaFunctionFailedEventDetailsTypeDef",
     {
         "error": str,
         "cause": str,
     },
     total=False,
@@ -505,21 +594,19 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
-
 class TaskFailedEventDetailsTypeDef(
     _RequiredTaskFailedEventDetailsTypeDef, _OptionalTaskFailedEventDetailsTypeDef
 ):
     pass
 
-
 _RequiredTaskStartFailedEventDetailsTypeDef = TypedDict(
     "_RequiredTaskStartFailedEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -528,21 +615,19 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
-
 class TaskStartFailedEventDetailsTypeDef(
     _RequiredTaskStartFailedEventDetailsTypeDef, _OptionalTaskStartFailedEventDetailsTypeDef
 ):
     pass
 
-
 TaskStartedEventDetailsTypeDef = TypedDict(
     "TaskStartedEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -559,21 +644,19 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
-
 class TaskSubmitFailedEventDetailsTypeDef(
     _RequiredTaskSubmitFailedEventDetailsTypeDef, _OptionalTaskSubmitFailedEventDetailsTypeDef
 ):
     pass
 
-
 _RequiredTaskTimedOutEventDetailsTypeDef = TypedDict(
     "_RequiredTaskTimedOutEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -582,50 +665,87 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
-
 class TaskTimedOutEventDetailsTypeDef(
     _RequiredTaskTimedOutEventDetailsTypeDef, _OptionalTaskTimedOutEventDetailsTypeDef
 ):
     pass
 
-
 TaskCredentialsTypeDef = TypedDict(
     "TaskCredentialsTypeDef",
     {
         "roleArn": str,
     },
     total=False,
 )
 
+ListActivitiesInputListActivitiesPaginateTypeDef = TypedDict(
+    "ListActivitiesInputListActivitiesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListActivitiesInputRequestTypeDef = TypedDict(
     "ListActivitiesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
+    "ListExecutionsInputListExecutionsPaginateTypeDef",
+    {
+        "stateMachineArn": str,
+        "statusFilter": ExecutionStatusType,
+        "mapRunArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListExecutionsInputRequestTypeDef = TypedDict(
     "ListExecutionsInputRequestTypeDef",
     {
         "stateMachineArn": str,
         "statusFilter": ExecutionStatusType,
         "maxResults": int,
         "nextToken": str,
         "mapRunArn": str,
     },
     total=False,
 )
 
+_RequiredListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
+    "_RequiredListMapRunsInputListMapRunsPaginateTypeDef",
+    {
+        "executionArn": str,
+    },
+)
+_OptionalListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
+    "_OptionalListMapRunsInputListMapRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMapRunsInputListMapRunsPaginateTypeDef(
+    _RequiredListMapRunsInputListMapRunsPaginateTypeDef,
+    _OptionalListMapRunsInputListMapRunsPaginateTypeDef,
+):
+    pass
+
 _RequiredListMapRunsInputRequestTypeDef = TypedDict(
     "_RequiredListMapRunsInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 _OptionalListMapRunsInputRequestTypeDef = TypedDict(
@@ -633,21 +753,19 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListMapRunsInputRequestTypeDef(
     _RequiredListMapRunsInputRequestTypeDef, _OptionalListMapRunsInputRequestTypeDef
 ):
     pass
 
-
 _RequiredMapRunListItemTypeDef = TypedDict(
     "_RequiredMapRunListItemTypeDef",
     {
         "executionArn": str,
         "mapRunArn": str,
         "stateMachineArn": str,
         "startDate": datetime,
@@ -657,18 +775,82 @@
     "_OptionalMapRunListItemTypeDef",
     {
         "stopDate": datetime,
     },
     total=False,
 )
 
-
 class MapRunListItemTypeDef(_RequiredMapRunListItemTypeDef, _OptionalMapRunListItemTypeDef):
     pass
 
+_RequiredListStateMachineAliasesInputRequestTypeDef = TypedDict(
+    "_RequiredListStateMachineAliasesInputRequestTypeDef",
+    {
+        "stateMachineArn": str,
+    },
+)
+_OptionalListStateMachineAliasesInputRequestTypeDef = TypedDict(
+    "_OptionalListStateMachineAliasesInputRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListStateMachineAliasesInputRequestTypeDef(
+    _RequiredListStateMachineAliasesInputRequestTypeDef,
+    _OptionalListStateMachineAliasesInputRequestTypeDef,
+):
+    pass
+
+StateMachineAliasListItemTypeDef = TypedDict(
+    "StateMachineAliasListItemTypeDef",
+    {
+        "stateMachineAliasArn": str,
+        "creationDate": datetime,
+    },
+)
+
+_RequiredListStateMachineVersionsInputRequestTypeDef = TypedDict(
+    "_RequiredListStateMachineVersionsInputRequestTypeDef",
+    {
+        "stateMachineArn": str,
+    },
+)
+_OptionalListStateMachineVersionsInputRequestTypeDef = TypedDict(
+    "_OptionalListStateMachineVersionsInputRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListStateMachineVersionsInputRequestTypeDef(
+    _RequiredListStateMachineVersionsInputRequestTypeDef,
+    _OptionalListStateMachineVersionsInputRequestTypeDef,
+):
+    pass
+
+StateMachineVersionListItemTypeDef = TypedDict(
+    "StateMachineVersionListItemTypeDef",
+    {
+        "stateMachineVersionArn": str,
+        "creationDate": datetime,
+    },
+)
+
+ListStateMachinesInputListStateMachinesPaginateTypeDef = TypedDict(
+    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListStateMachinesInputRequestTypeDef = TypedDict(
     "ListStateMachinesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
@@ -688,14 +870,65 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
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
+_RequiredPublishStateMachineVersionInputRequestTypeDef = TypedDict(
+    "_RequiredPublishStateMachineVersionInputRequestTypeDef",
+    {
+        "stateMachineArn": str,
+    },
+)
+_OptionalPublishStateMachineVersionInputRequestTypeDef = TypedDict(
+    "_OptionalPublishStateMachineVersionInputRequestTypeDef",
+    {
+        "revisionId": str,
+        "description": str,
+    },
+    total=False,
+)
+
+class PublishStateMachineVersionInputRequestTypeDef(
+    _RequiredPublishStateMachineVersionInputRequestTypeDef,
+    _OptionalPublishStateMachineVersionInputRequestTypeDef,
+):
+    pass
+
+PublishStateMachineVersionOutputTypeDef = TypedDict(
+    "PublishStateMachineVersionOutputTypeDef",
+    {
+        "creationDate": datetime,
+        "stateMachineVersionArn": str,
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
 _RequiredSendTaskFailureInputRequestTypeDef = TypedDict(
     "_RequiredSendTaskFailureInputRequestTypeDef",
     {
         "taskToken": str,
     },
 )
 _OptionalSendTaskFailureInputRequestTypeDef = TypedDict(
@@ -703,21 +936,19 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
-
 class SendTaskFailureInputRequestTypeDef(
     _RequiredSendTaskFailureInputRequestTypeDef, _OptionalSendTaskFailureInputRequestTypeDef
 ):
     pass
 
-
 SendTaskHeartbeatInputRequestTypeDef = TypedDict(
     "SendTaskHeartbeatInputRequestTypeDef",
     {
         "taskToken": str,
     },
 )
 
@@ -741,20 +972,27 @@
         "name": str,
         "input": str,
         "traceHeader": str,
     },
     total=False,
 )
 
-
 class StartExecutionInputRequestTypeDef(
     _RequiredStartExecutionInputRequestTypeDef, _OptionalStartExecutionInputRequestTypeDef
 ):
     pass
 
+StartExecutionOutputTypeDef = TypedDict(
+    "StartExecutionOutputTypeDef",
+    {
+        "executionArn": str,
+        "startDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredStartSyncExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStartSyncExecutionInputRequestTypeDef",
     {
         "stateMachineArn": str,
     },
 )
@@ -764,21 +1002,19 @@
         "name": str,
         "input": str,
         "traceHeader": str,
     },
     total=False,
 )
 
-
 class StartSyncExecutionInputRequestTypeDef(
     _RequiredStartSyncExecutionInputRequestTypeDef, _OptionalStartSyncExecutionInputRequestTypeDef
 ):
     pass
 
-
 _RequiredStopExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStopExecutionInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 _OptionalStopExecutionInputRequestTypeDef = TypedDict(
@@ -786,20 +1022,26 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
-
 class StopExecutionInputRequestTypeDef(
     _RequiredStopExecutionInputRequestTypeDef, _OptionalStopExecutionInputRequestTypeDef
 ):
     pass
 
+StopExecutionOutputTypeDef = TypedDict(
+    "StopExecutionOutputTypeDef",
+    {
+        "stopDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
@@ -817,20 +1059,45 @@
         "maxConcurrency": int,
         "toleratedFailurePercentage": float,
         "toleratedFailureCount": int,
     },
     total=False,
 )
 
-
 class UpdateMapRunInputRequestTypeDef(
     _RequiredUpdateMapRunInputRequestTypeDef, _OptionalUpdateMapRunInputRequestTypeDef
 ):
     pass
 
+UpdateStateMachineAliasOutputTypeDef = TypedDict(
+    "UpdateStateMachineAliasOutputTypeDef",
+    {
+        "updateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStateMachineOutputTypeDef = TypedDict(
+    "UpdateStateMachineOutputTypeDef",
+    {
+        "updateDate": datetime,
+        "revisionId": str,
+        "stateMachineVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListActivitiesOutputTypeDef = TypedDict(
+    "ListActivitiesOutputTypeDef",
+    {
+        "activities": List[ActivityListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredActivityScheduledEventDetailsTypeDef = TypedDict(
     "_RequiredActivityScheduledEventDetailsTypeDef",
     {
         "resource": str,
     },
 )
@@ -841,21 +1108,19 @@
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
         "timeoutInSeconds": int,
         "heartbeatInSeconds": int,
     },
     total=False,
 )
 
-
 class ActivityScheduledEventDetailsTypeDef(
     _RequiredActivityScheduledEventDetailsTypeDef, _OptionalActivityScheduledEventDetailsTypeDef
 ):
     pass
 
-
 ActivitySucceededEventDetailsTypeDef = TypedDict(
     "ActivitySucceededEventDetailsTypeDef",
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
@@ -863,14 +1128,16 @@
 
 ExecutionStartedEventDetailsTypeDef = TypedDict(
     "ExecutionStartedEventDetailsTypeDef",
     {
         "input": str,
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
         "roleArn": str,
+        "stateMachineAliasArn": str,
+        "stateMachineVersionArn": str,
     },
     total=False,
 )
 
 ExecutionSucceededEventDetailsTypeDef = TypedDict(
     "ExecutionSucceededEventDetailsTypeDef",
     {
@@ -900,21 +1167,19 @@
     {
         "input": str,
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
-
 class StateEnteredEventDetailsTypeDef(
     _RequiredStateEnteredEventDetailsTypeDef, _OptionalStateEnteredEventDetailsTypeDef
 ):
     pass
 
-
 _RequiredStateExitedEventDetailsTypeDef = TypedDict(
     "_RequiredStateExitedEventDetailsTypeDef",
     {
         "name": str,
     },
 )
 _OptionalStateExitedEventDetailsTypeDef = TypedDict(
@@ -922,21 +1187,19 @@
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
-
 class StateExitedEventDetailsTypeDef(
     _RequiredStateExitedEventDetailsTypeDef, _OptionalStateExitedEventDetailsTypeDef
 ):
     pass
 
-
 _RequiredTaskSubmittedEventDetailsTypeDef = TypedDict(
     "_RequiredTaskSubmittedEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -945,21 +1208,19 @@
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
-
 class TaskSubmittedEventDetailsTypeDef(
     _RequiredTaskSubmittedEventDetailsTypeDef, _OptionalTaskSubmittedEventDetailsTypeDef
 ):
     pass
 
-
 _RequiredTaskSucceededEventDetailsTypeDef = TypedDict(
     "_RequiredTaskSucceededEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -968,86 +1229,19 @@
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
-
 class TaskSucceededEventDetailsTypeDef(
     _RequiredTaskSucceededEventDetailsTypeDef, _OptionalTaskSucceededEventDetailsTypeDef
 ):
     pass
 
-
-LogDestinationTypeDef = TypedDict(
-    "LogDestinationTypeDef",
-    {
-        "cloudWatchLogsLogGroup": CloudWatchLogsLogGroupTypeDef,
-    },
-    total=False,
-)
-
-_RequiredCreateActivityInputRequestTypeDef = TypedDict(
-    "_RequiredCreateActivityInputRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalCreateActivityInputRequestTypeDef = TypedDict(
-    "_OptionalCreateActivityInputRequestTypeDef",
-    {
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-
-class CreateActivityInputRequestTypeDef(
-    _RequiredCreateActivityInputRequestTypeDef, _OptionalCreateActivityInputRequestTypeDef
-):
-    pass
-
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateActivityOutputTypeDef = TypedDict(
-    "CreateActivityOutputTypeDef",
-    {
-        "activityArn": str,
-        "creationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStateMachineOutputTypeDef = TypedDict(
-    "CreateStateMachineOutputTypeDef",
-    {
-        "stateMachineArn": str,
-        "creationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeActivityOutputTypeDef = TypedDict(
-    "DescribeActivityOutputTypeDef",
-    {
-        "activityArn": str,
-        "name": str,
-        "creationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeExecutionOutputTypeDef = TypedDict(
     "DescribeExecutionOutputTypeDef",
     {
         "executionArn": str,
         "stateMachineArn": str,
         "name": str,
         "status": ExecutionStatusType,
@@ -1057,50 +1251,17 @@
         "inputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "output": str,
         "outputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "traceHeader": str,
         "mapRunArn": str,
         "error": str,
         "cause": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetActivityTaskOutputTypeDef = TypedDict(
-    "GetActivityTaskOutputTypeDef",
-    {
-        "taskToken": str,
-        "input": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListActivitiesOutputTypeDef = TypedDict(
-    "ListActivitiesOutputTypeDef",
-    {
-        "activities": List[ActivityListItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartExecutionOutputTypeDef = TypedDict(
-    "StartExecutionOutputTypeDef",
-    {
-        "executionArn": str,
-        "startDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "stateMachineVersionArn": str,
+        "stateMachineAliasArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSyncExecutionOutputTypeDef = TypedDict(
     "StartSyncExecutionOutputTypeDef",
     {
         "executionArn": str,
@@ -1113,131 +1274,140 @@
         "cause": str,
         "input": str,
         "inputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "output": str,
         "outputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "traceHeader": str,
         "billingDetails": BillingDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopExecutionOutputTypeDef = TypedDict(
-    "StopExecutionOutputTypeDef",
+LogDestinationTypeDef = TypedDict(
+    "LogDestinationTypeDef",
     {
-        "stopDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cloudWatchLogsLogGroup": CloudWatchLogsLogGroupTypeDef,
     },
+    total=False,
 )
 
-UpdateStateMachineOutputTypeDef = TypedDict(
-    "UpdateStateMachineOutputTypeDef",
+_RequiredCreateActivityInputRequestTypeDef = TypedDict(
+    "_RequiredCreateActivityInputRequestTypeDef",
     {
-        "updateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
     },
 )
+_OptionalCreateActivityInputRequestTypeDef = TypedDict(
+    "_OptionalCreateActivityInputRequestTypeDef",
+    {
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
 
-DescribeMapRunOutputTypeDef = TypedDict(
-    "DescribeMapRunOutputTypeDef",
+class CreateActivityInputRequestTypeDef(
+    _RequiredCreateActivityInputRequestTypeDef, _OptionalCreateActivityInputRequestTypeDef
+):
+    pass
+
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
     {
-        "mapRunArn": str,
-        "executionArn": str,
-        "status": MapRunStatusType,
-        "startDate": datetime,
-        "stopDate": datetime,
-        "maxConcurrency": int,
-        "toleratedFailurePercentage": float,
-        "toleratedFailureCount": int,
-        "itemCounts": MapRunItemCountsTypeDef,
-        "executionCounts": MapRunExecutionCountsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListExecutionsOutputTypeDef = TypedDict(
-    "ListExecutionsOutputTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "executions": List[ExecutionListItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
-_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+_RequiredCreateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_RequiredCreateStateMachineAliasInputRequestTypeDef",
     {
-        "executionArn": str,
+        "name": str,
+        "routingConfiguration": Sequence[RoutingConfigurationListItemTypeDef],
     },
 )
-_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+_OptionalCreateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_OptionalCreateStateMachineAliasInputRequestTypeDef",
     {
-        "reverseOrder": bool,
-        "includeExecutionData": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "description": str,
     },
     total=False,
 )
 
-
-class GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef(
-    _RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
-    _OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
+class CreateStateMachineAliasInputRequestTypeDef(
+    _RequiredCreateStateMachineAliasInputRequestTypeDef,
+    _OptionalCreateStateMachineAliasInputRequestTypeDef,
 ):
     pass
 
-
-ListActivitiesInputListActivitiesPaginateTypeDef = TypedDict(
-    "ListActivitiesInputListActivitiesPaginateTypeDef",
+DescribeStateMachineAliasOutputTypeDef = TypedDict(
+    "DescribeStateMachineAliasOutputTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
-    "ListExecutionsInputListExecutionsPaginateTypeDef",
-    {
-        "stateMachineArn": str,
-        "statusFilter": ExecutionStatusType,
-        "mapRunArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "stateMachineAliasArn": str,
+        "name": str,
+        "description": str,
+        "routingConfiguration": List[RoutingConfigurationListItemTypeDef],
+        "creationDate": datetime,
+        "updateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
-    "_RequiredListMapRunsInputListMapRunsPaginateTypeDef",
+_RequiredUpdateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_RequiredUpdateStateMachineAliasInputRequestTypeDef",
     {
-        "executionArn": str,
+        "stateMachineAliasArn": str,
     },
 )
-_OptionalListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
-    "_OptionalListMapRunsInputListMapRunsPaginateTypeDef",
+_OptionalUpdateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_OptionalUpdateStateMachineAliasInputRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "description": str,
+        "routingConfiguration": Sequence[RoutingConfigurationListItemTypeDef],
     },
     total=False,
 )
 
-
-class ListMapRunsInputListMapRunsPaginateTypeDef(
-    _RequiredListMapRunsInputListMapRunsPaginateTypeDef,
-    _OptionalListMapRunsInputListMapRunsPaginateTypeDef,
+class UpdateStateMachineAliasInputRequestTypeDef(
+    _RequiredUpdateStateMachineAliasInputRequestTypeDef,
+    _OptionalUpdateStateMachineAliasInputRequestTypeDef,
 ):
     pass
 
+DescribeMapRunOutputTypeDef = TypedDict(
+    "DescribeMapRunOutputTypeDef",
+    {
+        "mapRunArn": str,
+        "executionArn": str,
+        "status": MapRunStatusType,
+        "startDate": datetime,
+        "stopDate": datetime,
+        "maxConcurrency": int,
+        "toleratedFailurePercentage": float,
+        "toleratedFailureCount": int,
+        "itemCounts": MapRunItemCountsTypeDef,
+        "executionCounts": MapRunExecutionCountsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-ListStateMachinesInputListStateMachinesPaginateTypeDef = TypedDict(
-    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
+ListExecutionsOutputTypeDef = TypedDict(
+    "ListExecutionsOutputTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "executions": List[ExecutionListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredLambdaFunctionScheduledEventDetailsTypeDef = TypedDict(
     "_RequiredLambdaFunctionScheduledEventDetailsTypeDef",
     {
         "resource": str,
     },
@@ -1249,22 +1419,20 @@
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
         "timeoutInSeconds": int,
         "taskCredentials": TaskCredentialsTypeDef,
     },
     total=False,
 )
 
-
 class LambdaFunctionScheduledEventDetailsTypeDef(
     _RequiredLambdaFunctionScheduledEventDetailsTypeDef,
     _OptionalLambdaFunctionScheduledEventDetailsTypeDef,
 ):
     pass
 
-
 _RequiredTaskScheduledEventDetailsTypeDef = TypedDict(
     "_RequiredTaskScheduledEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
         "region": str,
         "parameters": str,
@@ -1276,36 +1444,52 @@
         "timeoutInSeconds": int,
         "heartbeatInSeconds": int,
         "taskCredentials": TaskCredentialsTypeDef,
     },
     total=False,
 )
 
-
 class TaskScheduledEventDetailsTypeDef(
     _RequiredTaskScheduledEventDetailsTypeDef, _OptionalTaskScheduledEventDetailsTypeDef
 ):
     pass
 
-
 ListMapRunsOutputTypeDef = TypedDict(
     "ListMapRunsOutputTypeDef",
     {
         "mapRuns": List[MapRunListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStateMachineAliasesOutputTypeDef = TypedDict(
+    "ListStateMachineAliasesOutputTypeDef",
+    {
+        "stateMachineAliases": List[StateMachineAliasListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStateMachineVersionsOutputTypeDef = TypedDict(
+    "ListStateMachineVersionsOutputTypeDef",
+    {
+        "stateMachineVersions": List[StateMachineVersionListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStateMachinesOutputTypeDef = TypedDict(
     "ListStateMachinesOutputTypeDef",
     {
         "stateMachines": List[StateMachineListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingConfigurationTypeDef = TypedDict(
     "LoggingConfigurationTypeDef",
     {
         "level": LogLevelType,
@@ -1361,19 +1545,17 @@
         "stateExitedEventDetails": StateExitedEventDetailsTypeDef,
         "mapRunStartedEventDetails": MapRunStartedEventDetailsTypeDef,
         "mapRunFailedEventDetails": MapRunFailedEventDetailsTypeDef,
     },
     total=False,
 )
 
-
 class HistoryEventTypeDef(_RequiredHistoryEventTypeDef, _OptionalHistoryEventTypeDef):
     pass
 
-
 _RequiredCreateStateMachineInputRequestTypeDef = TypedDict(
     "_RequiredCreateStateMachineInputRequestTypeDef",
     {
         "name": str,
         "definition": str,
         "roleArn": str,
     },
@@ -1381,38 +1563,39 @@
 _OptionalCreateStateMachineInputRequestTypeDef = TypedDict(
     "_OptionalCreateStateMachineInputRequestTypeDef",
     {
         "type": StateMachineTypeType,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tags": Sequence[TagTypeDef],
         "tracingConfiguration": TracingConfigurationTypeDef,
+        "publish": bool,
+        "versionDescription": str,
     },
     total=False,
 )
 
-
 class CreateStateMachineInputRequestTypeDef(
     _RequiredCreateStateMachineInputRequestTypeDef, _OptionalCreateStateMachineInputRequestTypeDef
 ):
     pass
 
-
 DescribeStateMachineForExecutionOutputTypeDef = TypedDict(
     "DescribeStateMachineForExecutionOutputTypeDef",
     {
         "stateMachineArn": str,
         "name": str,
         "definition": str,
         "roleArn": str,
         "updateDate": datetime,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tracingConfiguration": TracingConfigurationTypeDef,
         "mapRunArn": str,
         "label": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStateMachineOutputTypeDef = TypedDict(
     "DescribeStateMachineOutputTypeDef",
     {
         "stateMachineArn": str,
@@ -1421,15 +1604,17 @@
         "definition": str,
         "roleArn": str,
         "type": StateMachineTypeType,
         "creationDate": datetime,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tracingConfiguration": TracingConfigurationTypeDef,
         "label": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "revisionId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateStateMachineInputRequestTypeDef = TypedDict(
     "_RequiredUpdateStateMachineInputRequestTypeDef",
     {
         "stateMachineArn": str,
@@ -1438,26 +1623,26 @@
 _OptionalUpdateStateMachineInputRequestTypeDef = TypedDict(
     "_OptionalUpdateStateMachineInputRequestTypeDef",
     {
         "definition": str,
         "roleArn": str,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tracingConfiguration": TracingConfigurationTypeDef,
+        "publish": bool,
+        "versionDescription": str,
     },
     total=False,
 )
 
-
 class UpdateStateMachineInputRequestTypeDef(
     _RequiredUpdateStateMachineInputRequestTypeDef, _OptionalUpdateStateMachineInputRequestTypeDef
 ):
     pass
 
-
 GetExecutionHistoryOutputTypeDef = TypedDict(
     "GetExecutionHistoryOutputTypeDef",
     {
         "events": List[HistoryEventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions/type_defs.pyi` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions/type_defs.py`

 * *Files 16% similar despite different names*

```diff
@@ -26,42 +26,51 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ActivityFailedEventDetailsTypeDef",
     "ActivityListItemTypeDef",
     "ActivityScheduleFailedEventDetailsTypeDef",
     "HistoryEventExecutionDataDetailsTypeDef",
     "ActivityStartedEventDetailsTypeDef",
     "ActivityTimedOutEventDetailsTypeDef",
     "BillingDetailsTypeDef",
     "CloudWatchEventsExecutionDataDetailsTypeDef",
     "CloudWatchLogsLogGroupTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateActivityOutputTypeDef",
+    "RoutingConfigurationListItemTypeDef",
+    "CreateStateMachineAliasOutputTypeDef",
     "TracingConfigurationTypeDef",
+    "CreateStateMachineOutputTypeDef",
     "DeleteActivityInputRequestTypeDef",
+    "DeleteStateMachineAliasInputRequestTypeDef",
     "DeleteStateMachineInputRequestTypeDef",
+    "DeleteStateMachineVersionInputRequestTypeDef",
     "DescribeActivityInputRequestTypeDef",
+    "DescribeActivityOutputTypeDef",
     "DescribeExecutionInputRequestTypeDef",
     "DescribeMapRunInputRequestTypeDef",
     "MapRunExecutionCountsTypeDef",
     "MapRunItemCountsTypeDef",
+    "DescribeStateMachineAliasInputRequestTypeDef",
     "DescribeStateMachineForExecutionInputRequestTypeDef",
     "DescribeStateMachineInputRequestTypeDef",
     "ExecutionAbortedEventDetailsTypeDef",
     "ExecutionFailedEventDetailsTypeDef",
     "ExecutionListItemTypeDef",
     "ExecutionTimedOutEventDetailsTypeDef",
     "GetActivityTaskInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetActivityTaskOutputTypeDef",
+    "GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
     "GetExecutionHistoryInputRequestTypeDef",
     "LambdaFunctionFailedEventDetailsTypeDef",
     "LambdaFunctionScheduleFailedEventDetailsTypeDef",
     "LambdaFunctionStartFailedEventDetailsTypeDef",
     "LambdaFunctionTimedOutEventDetailsTypeDef",
     "MapIterationEventDetailsTypeDef",
     "MapRunFailedEventDetailsTypeDef",
@@ -69,62 +78,71 @@
     "MapStateStartedEventDetailsTypeDef",
     "TaskFailedEventDetailsTypeDef",
     "TaskStartFailedEventDetailsTypeDef",
     "TaskStartedEventDetailsTypeDef",
     "TaskSubmitFailedEventDetailsTypeDef",
     "TaskTimedOutEventDetailsTypeDef",
     "TaskCredentialsTypeDef",
+    "ListActivitiesInputListActivitiesPaginateTypeDef",
     "ListActivitiesInputRequestTypeDef",
+    "ListExecutionsInputListExecutionsPaginateTypeDef",
     "ListExecutionsInputRequestTypeDef",
+    "ListMapRunsInputListMapRunsPaginateTypeDef",
     "ListMapRunsInputRequestTypeDef",
     "MapRunListItemTypeDef",
+    "ListStateMachineAliasesInputRequestTypeDef",
+    "StateMachineAliasListItemTypeDef",
+    "ListStateMachineVersionsInputRequestTypeDef",
+    "StateMachineVersionListItemTypeDef",
+    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
     "ListStateMachinesInputRequestTypeDef",
     "StateMachineListItemTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "PublishStateMachineVersionInputRequestTypeDef",
+    "PublishStateMachineVersionOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "SendTaskFailureInputRequestTypeDef",
     "SendTaskHeartbeatInputRequestTypeDef",
     "SendTaskSuccessInputRequestTypeDef",
     "StartExecutionInputRequestTypeDef",
+    "StartExecutionOutputTypeDef",
     "StartSyncExecutionInputRequestTypeDef",
     "StopExecutionInputRequestTypeDef",
+    "StopExecutionOutputTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateMapRunInputRequestTypeDef",
+    "UpdateStateMachineAliasOutputTypeDef",
+    "UpdateStateMachineOutputTypeDef",
+    "ListActivitiesOutputTypeDef",
     "ActivityScheduledEventDetailsTypeDef",
     "ActivitySucceededEventDetailsTypeDef",
     "ExecutionStartedEventDetailsTypeDef",
     "ExecutionSucceededEventDetailsTypeDef",
     "LambdaFunctionSucceededEventDetailsTypeDef",
     "StateEnteredEventDetailsTypeDef",
     "StateExitedEventDetailsTypeDef",
     "TaskSubmittedEventDetailsTypeDef",
     "TaskSucceededEventDetailsTypeDef",
+    "DescribeExecutionOutputTypeDef",
+    "StartSyncExecutionOutputTypeDef",
     "LogDestinationTypeDef",
     "CreateActivityInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
-    "CreateActivityOutputTypeDef",
-    "CreateStateMachineOutputTypeDef",
-    "DescribeActivityOutputTypeDef",
-    "DescribeExecutionOutputTypeDef",
-    "GetActivityTaskOutputTypeDef",
-    "ListActivitiesOutputTypeDef",
     "ListTagsForResourceOutputTypeDef",
-    "StartExecutionOutputTypeDef",
-    "StartSyncExecutionOutputTypeDef",
-    "StopExecutionOutputTypeDef",
-    "UpdateStateMachineOutputTypeDef",
+    "TagResourceInputRequestTypeDef",
+    "CreateStateMachineAliasInputRequestTypeDef",
+    "DescribeStateMachineAliasOutputTypeDef",
+    "UpdateStateMachineAliasInputRequestTypeDef",
     "DescribeMapRunOutputTypeDef",
     "ListExecutionsOutputTypeDef",
-    "GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
-    "ListActivitiesInputListActivitiesPaginateTypeDef",
-    "ListExecutionsInputListExecutionsPaginateTypeDef",
-    "ListMapRunsInputListMapRunsPaginateTypeDef",
-    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
     "LambdaFunctionScheduledEventDetailsTypeDef",
     "TaskScheduledEventDetailsTypeDef",
     "ListMapRunsOutputTypeDef",
+    "ListStateMachineAliasesOutputTypeDef",
+    "ListStateMachineVersionsOutputTypeDef",
     "ListStateMachinesOutputTypeDef",
     "LoggingConfigurationTypeDef",
     "HistoryEventTypeDef",
     "CreateStateMachineInputRequestTypeDef",
     "DescribeStateMachineForExecutionOutputTypeDef",
     "DescribeStateMachineOutputTypeDef",
     "UpdateStateMachineInputRequestTypeDef",
@@ -213,54 +231,103 @@
     {
         "key": str,
         "value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateActivityOutputTypeDef = TypedDict(
+    "CreateActivityOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "activityArn": str,
+        "creationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RoutingConfigurationListItemTypeDef = TypedDict(
+    "RoutingConfigurationListItemTypeDef",
+    {
+        "stateMachineVersionArn": str,
+        "weight": int,
+    },
+)
+
+CreateStateMachineAliasOutputTypeDef = TypedDict(
+    "CreateStateMachineAliasOutputTypeDef",
+    {
+        "stateMachineAliasArn": str,
+        "creationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TracingConfigurationTypeDef = TypedDict(
     "TracingConfigurationTypeDef",
     {
         "enabled": bool,
     },
     total=False,
 )
 
+CreateStateMachineOutputTypeDef = TypedDict(
+    "CreateStateMachineOutputTypeDef",
+    {
+        "stateMachineArn": str,
+        "creationDate": datetime,
+        "stateMachineVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteActivityInputRequestTypeDef = TypedDict(
     "DeleteActivityInputRequestTypeDef",
     {
         "activityArn": str,
     },
 )
 
+DeleteStateMachineAliasInputRequestTypeDef = TypedDict(
+    "DeleteStateMachineAliasInputRequestTypeDef",
+    {
+        "stateMachineAliasArn": str,
+    },
+)
+
 DeleteStateMachineInputRequestTypeDef = TypedDict(
     "DeleteStateMachineInputRequestTypeDef",
     {
         "stateMachineArn": str,
     },
 )
 
+DeleteStateMachineVersionInputRequestTypeDef = TypedDict(
+    "DeleteStateMachineVersionInputRequestTypeDef",
+    {
+        "stateMachineVersionArn": str,
+    },
+)
+
 DescribeActivityInputRequestTypeDef = TypedDict(
     "DescribeActivityInputRequestTypeDef",
     {
         "activityArn": str,
     },
 )
 
+DescribeActivityOutputTypeDef = TypedDict(
+    "DescribeActivityOutputTypeDef",
+    {
+        "activityArn": str,
+        "name": str,
+        "creationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeExecutionInputRequestTypeDef = TypedDict(
     "DescribeExecutionInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 
@@ -295,14 +362,21 @@
         "timedOut": int,
         "aborted": int,
         "total": int,
         "resultsWritten": int,
     },
 )
 
+DescribeStateMachineAliasInputRequestTypeDef = TypedDict(
+    "DescribeStateMachineAliasInputRequestTypeDef",
+    {
+        "stateMachineAliasArn": str,
+    },
+)
+
 DescribeStateMachineForExecutionInputRequestTypeDef = TypedDict(
     "DescribeStateMachineForExecutionInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 
@@ -343,23 +417,27 @@
 )
 _OptionalExecutionListItemTypeDef = TypedDict(
     "_OptionalExecutionListItemTypeDef",
     {
         "stopDate": datetime,
         "mapRunArn": str,
         "itemCount": int,
+        "stateMachineVersionArn": str,
+        "stateMachineAliasArn": str,
     },
     total=False,
 )
 
+
 class ExecutionListItemTypeDef(
     _RequiredExecutionListItemTypeDef, _OptionalExecutionListItemTypeDef
 ):
     pass
 
+
 ExecutionTimedOutEventDetailsTypeDef = TypedDict(
     "ExecutionTimedOutEventDetailsTypeDef",
     {
         "error": str,
         "cause": str,
     },
     total=False,
@@ -375,29 +453,54 @@
     "_OptionalGetActivityTaskInputRequestTypeDef",
     {
         "workerName": str,
     },
     total=False,
 )
 
+
 class GetActivityTaskInputRequestTypeDef(
     _RequiredGetActivityTaskInputRequestTypeDef, _OptionalGetActivityTaskInputRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+GetActivityTaskOutputTypeDef = TypedDict(
+    "GetActivityTaskOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "taskToken": str,
+        "input": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+    {
+        "executionArn": str,
+    },
+)
+_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+    {
+        "reverseOrder": bool,
+        "includeExecutionData": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef(
+    _RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
+    _OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetExecutionHistoryInputRequestTypeDef = TypedDict(
     "_RequiredGetExecutionHistoryInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 _OptionalGetExecutionHistoryInputRequestTypeDef = TypedDict(
@@ -407,19 +510,21 @@
         "reverseOrder": bool,
         "nextToken": str,
         "includeExecutionData": bool,
     },
     total=False,
 )
 
+
 class GetExecutionHistoryInputRequestTypeDef(
     _RequiredGetExecutionHistoryInputRequestTypeDef, _OptionalGetExecutionHistoryInputRequestTypeDef
 ):
     pass
 
+
 LambdaFunctionFailedEventDetailsTypeDef = TypedDict(
     "LambdaFunctionFailedEventDetailsTypeDef",
     {
         "error": str,
         "cause": str,
     },
     total=False,
@@ -498,19 +603,21 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
+
 class TaskFailedEventDetailsTypeDef(
     _RequiredTaskFailedEventDetailsTypeDef, _OptionalTaskFailedEventDetailsTypeDef
 ):
     pass
 
+
 _RequiredTaskStartFailedEventDetailsTypeDef = TypedDict(
     "_RequiredTaskStartFailedEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -519,19 +626,21 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
+
 class TaskStartFailedEventDetailsTypeDef(
     _RequiredTaskStartFailedEventDetailsTypeDef, _OptionalTaskStartFailedEventDetailsTypeDef
 ):
     pass
 
+
 TaskStartedEventDetailsTypeDef = TypedDict(
     "TaskStartedEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -548,19 +657,21 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
+
 class TaskSubmitFailedEventDetailsTypeDef(
     _RequiredTaskSubmitFailedEventDetailsTypeDef, _OptionalTaskSubmitFailedEventDetailsTypeDef
 ):
     pass
 
+
 _RequiredTaskTimedOutEventDetailsTypeDef = TypedDict(
     "_RequiredTaskTimedOutEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -569,48 +680,91 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
+
 class TaskTimedOutEventDetailsTypeDef(
     _RequiredTaskTimedOutEventDetailsTypeDef, _OptionalTaskTimedOutEventDetailsTypeDef
 ):
     pass
 
+
 TaskCredentialsTypeDef = TypedDict(
     "TaskCredentialsTypeDef",
     {
         "roleArn": str,
     },
     total=False,
 )
 
+ListActivitiesInputListActivitiesPaginateTypeDef = TypedDict(
+    "ListActivitiesInputListActivitiesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListActivitiesInputRequestTypeDef = TypedDict(
     "ListActivitiesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
+    "ListExecutionsInputListExecutionsPaginateTypeDef",
+    {
+        "stateMachineArn": str,
+        "statusFilter": ExecutionStatusType,
+        "mapRunArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListExecutionsInputRequestTypeDef = TypedDict(
     "ListExecutionsInputRequestTypeDef",
     {
         "stateMachineArn": str,
         "statusFilter": ExecutionStatusType,
         "maxResults": int,
         "nextToken": str,
         "mapRunArn": str,
     },
     total=False,
 )
 
+_RequiredListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
+    "_RequiredListMapRunsInputListMapRunsPaginateTypeDef",
+    {
+        "executionArn": str,
+    },
+)
+_OptionalListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
+    "_OptionalListMapRunsInputListMapRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMapRunsInputListMapRunsPaginateTypeDef(
+    _RequiredListMapRunsInputListMapRunsPaginateTypeDef,
+    _OptionalListMapRunsInputListMapRunsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMapRunsInputRequestTypeDef = TypedDict(
     "_RequiredListMapRunsInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 _OptionalListMapRunsInputRequestTypeDef = TypedDict(
@@ -618,19 +772,21 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListMapRunsInputRequestTypeDef(
     _RequiredListMapRunsInputRequestTypeDef, _OptionalListMapRunsInputRequestTypeDef
 ):
     pass
 
+
 _RequiredMapRunListItemTypeDef = TypedDict(
     "_RequiredMapRunListItemTypeDef",
     {
         "executionArn": str,
         "mapRunArn": str,
         "stateMachineArn": str,
         "startDate": datetime,
@@ -640,17 +796,89 @@
     "_OptionalMapRunListItemTypeDef",
     {
         "stopDate": datetime,
     },
     total=False,
 )
 
+
 class MapRunListItemTypeDef(_RequiredMapRunListItemTypeDef, _OptionalMapRunListItemTypeDef):
     pass
 
+
+_RequiredListStateMachineAliasesInputRequestTypeDef = TypedDict(
+    "_RequiredListStateMachineAliasesInputRequestTypeDef",
+    {
+        "stateMachineArn": str,
+    },
+)
+_OptionalListStateMachineAliasesInputRequestTypeDef = TypedDict(
+    "_OptionalListStateMachineAliasesInputRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListStateMachineAliasesInputRequestTypeDef(
+    _RequiredListStateMachineAliasesInputRequestTypeDef,
+    _OptionalListStateMachineAliasesInputRequestTypeDef,
+):
+    pass
+
+
+StateMachineAliasListItemTypeDef = TypedDict(
+    "StateMachineAliasListItemTypeDef",
+    {
+        "stateMachineAliasArn": str,
+        "creationDate": datetime,
+    },
+)
+
+_RequiredListStateMachineVersionsInputRequestTypeDef = TypedDict(
+    "_RequiredListStateMachineVersionsInputRequestTypeDef",
+    {
+        "stateMachineArn": str,
+    },
+)
+_OptionalListStateMachineVersionsInputRequestTypeDef = TypedDict(
+    "_OptionalListStateMachineVersionsInputRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListStateMachineVersionsInputRequestTypeDef(
+    _RequiredListStateMachineVersionsInputRequestTypeDef,
+    _OptionalListStateMachineVersionsInputRequestTypeDef,
+):
+    pass
+
+
+StateMachineVersionListItemTypeDef = TypedDict(
+    "StateMachineVersionListItemTypeDef",
+    {
+        "stateMachineVersionArn": str,
+        "creationDate": datetime,
+    },
+)
+
+ListStateMachinesInputListStateMachinesPaginateTypeDef = TypedDict(
+    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStateMachinesInputRequestTypeDef = TypedDict(
     "ListStateMachinesInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -669,14 +897,67 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
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
+_RequiredPublishStateMachineVersionInputRequestTypeDef = TypedDict(
+    "_RequiredPublishStateMachineVersionInputRequestTypeDef",
+    {
+        "stateMachineArn": str,
+    },
+)
+_OptionalPublishStateMachineVersionInputRequestTypeDef = TypedDict(
+    "_OptionalPublishStateMachineVersionInputRequestTypeDef",
+    {
+        "revisionId": str,
+        "description": str,
+    },
+    total=False,
+)
+
+
+class PublishStateMachineVersionInputRequestTypeDef(
+    _RequiredPublishStateMachineVersionInputRequestTypeDef,
+    _OptionalPublishStateMachineVersionInputRequestTypeDef,
+):
+    pass
+
+
+PublishStateMachineVersionOutputTypeDef = TypedDict(
+    "PublishStateMachineVersionOutputTypeDef",
+    {
+        "creationDate": datetime,
+        "stateMachineVersionArn": str,
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
 _RequiredSendTaskFailureInputRequestTypeDef = TypedDict(
     "_RequiredSendTaskFailureInputRequestTypeDef",
     {
         "taskToken": str,
     },
 )
 _OptionalSendTaskFailureInputRequestTypeDef = TypedDict(
@@ -684,19 +965,21 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
+
 class SendTaskFailureInputRequestTypeDef(
     _RequiredSendTaskFailureInputRequestTypeDef, _OptionalSendTaskFailureInputRequestTypeDef
 ):
     pass
 
+
 SendTaskHeartbeatInputRequestTypeDef = TypedDict(
     "SendTaskHeartbeatInputRequestTypeDef",
     {
         "taskToken": str,
     },
 )
 
@@ -720,19 +1003,30 @@
         "name": str,
         "input": str,
         "traceHeader": str,
     },
     total=False,
 )
 
+
 class StartExecutionInputRequestTypeDef(
     _RequiredStartExecutionInputRequestTypeDef, _OptionalStartExecutionInputRequestTypeDef
 ):
     pass
 
+
+StartExecutionOutputTypeDef = TypedDict(
+    "StartExecutionOutputTypeDef",
+    {
+        "executionArn": str,
+        "startDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartSyncExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStartSyncExecutionInputRequestTypeDef",
     {
         "stateMachineArn": str,
     },
 )
 _OptionalStartSyncExecutionInputRequestTypeDef = TypedDict(
@@ -741,19 +1035,21 @@
         "name": str,
         "input": str,
         "traceHeader": str,
     },
     total=False,
 )
 
+
 class StartSyncExecutionInputRequestTypeDef(
     _RequiredStartSyncExecutionInputRequestTypeDef, _OptionalStartSyncExecutionInputRequestTypeDef
 ):
     pass
 
+
 _RequiredStopExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStopExecutionInputRequestTypeDef",
     {
         "executionArn": str,
     },
 )
 _OptionalStopExecutionInputRequestTypeDef = TypedDict(
@@ -761,19 +1057,29 @@
     {
         "error": str,
         "cause": str,
     },
     total=False,
 )
 
+
 class StopExecutionInputRequestTypeDef(
     _RequiredStopExecutionInputRequestTypeDef, _OptionalStopExecutionInputRequestTypeDef
 ):
     pass
 
+
+StopExecutionOutputTypeDef = TypedDict(
+    "StopExecutionOutputTypeDef",
+    {
+        "stopDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -790,19 +1096,48 @@
         "maxConcurrency": int,
         "toleratedFailurePercentage": float,
         "toleratedFailureCount": int,
     },
     total=False,
 )
 
+
 class UpdateMapRunInputRequestTypeDef(
     _RequiredUpdateMapRunInputRequestTypeDef, _OptionalUpdateMapRunInputRequestTypeDef
 ):
     pass
 
+
+UpdateStateMachineAliasOutputTypeDef = TypedDict(
+    "UpdateStateMachineAliasOutputTypeDef",
+    {
+        "updateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateStateMachineOutputTypeDef = TypedDict(
+    "UpdateStateMachineOutputTypeDef",
+    {
+        "updateDate": datetime,
+        "revisionId": str,
+        "stateMachineVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListActivitiesOutputTypeDef = TypedDict(
+    "ListActivitiesOutputTypeDef",
+    {
+        "activities": List[ActivityListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredActivityScheduledEventDetailsTypeDef = TypedDict(
     "_RequiredActivityScheduledEventDetailsTypeDef",
     {
         "resource": str,
     },
 )
 _OptionalActivityScheduledEventDetailsTypeDef = TypedDict(
@@ -812,19 +1147,21 @@
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
         "timeoutInSeconds": int,
         "heartbeatInSeconds": int,
     },
     total=False,
 )
 
+
 class ActivityScheduledEventDetailsTypeDef(
     _RequiredActivityScheduledEventDetailsTypeDef, _OptionalActivityScheduledEventDetailsTypeDef
 ):
     pass
 
+
 ActivitySucceededEventDetailsTypeDef = TypedDict(
     "ActivitySucceededEventDetailsTypeDef",
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
@@ -832,14 +1169,16 @@
 
 ExecutionStartedEventDetailsTypeDef = TypedDict(
     "ExecutionStartedEventDetailsTypeDef",
     {
         "input": str,
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
         "roleArn": str,
+        "stateMachineAliasArn": str,
+        "stateMachineVersionArn": str,
     },
     total=False,
 )
 
 ExecutionSucceededEventDetailsTypeDef = TypedDict(
     "ExecutionSucceededEventDetailsTypeDef",
     {
@@ -869,19 +1208,21 @@
     {
         "input": str,
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
+
 class StateEnteredEventDetailsTypeDef(
     _RequiredStateEnteredEventDetailsTypeDef, _OptionalStateEnteredEventDetailsTypeDef
 ):
     pass
 
+
 _RequiredStateExitedEventDetailsTypeDef = TypedDict(
     "_RequiredStateExitedEventDetailsTypeDef",
     {
         "name": str,
     },
 )
 _OptionalStateExitedEventDetailsTypeDef = TypedDict(
@@ -889,19 +1230,21 @@
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
+
 class StateExitedEventDetailsTypeDef(
     _RequiredStateExitedEventDetailsTypeDef, _OptionalStateExitedEventDetailsTypeDef
 ):
     pass
 
+
 _RequiredTaskSubmittedEventDetailsTypeDef = TypedDict(
     "_RequiredTaskSubmittedEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -910,19 +1253,21 @@
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
+
 class TaskSubmittedEventDetailsTypeDef(
     _RequiredTaskSubmittedEventDetailsTypeDef, _OptionalTaskSubmittedEventDetailsTypeDef
 ):
     pass
 
+
 _RequiredTaskSucceededEventDetailsTypeDef = TypedDict(
     "_RequiredTaskSucceededEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
     },
 )
@@ -931,81 +1276,20 @@
     {
         "output": str,
         "outputDetails": HistoryEventExecutionDataDetailsTypeDef,
     },
     total=False,
 )
 
+
 class TaskSucceededEventDetailsTypeDef(
     _RequiredTaskSucceededEventDetailsTypeDef, _OptionalTaskSucceededEventDetailsTypeDef
 ):
     pass
 
-LogDestinationTypeDef = TypedDict(
-    "LogDestinationTypeDef",
-    {
-        "cloudWatchLogsLogGroup": CloudWatchLogsLogGroupTypeDef,
-    },
-    total=False,
-)
-
-_RequiredCreateActivityInputRequestTypeDef = TypedDict(
-    "_RequiredCreateActivityInputRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalCreateActivityInputRequestTypeDef = TypedDict(
-    "_OptionalCreateActivityInputRequestTypeDef",
-    {
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-class CreateActivityInputRequestTypeDef(
-    _RequiredCreateActivityInputRequestTypeDef, _OptionalCreateActivityInputRequestTypeDef
-):
-    pass
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateActivityOutputTypeDef = TypedDict(
-    "CreateActivityOutputTypeDef",
-    {
-        "activityArn": str,
-        "creationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStateMachineOutputTypeDef = TypedDict(
-    "CreateStateMachineOutputTypeDef",
-    {
-        "stateMachineArn": str,
-        "creationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeActivityOutputTypeDef = TypedDict(
-    "DescribeActivityOutputTypeDef",
-    {
-        "activityArn": str,
-        "name": str,
-        "creationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 DescribeExecutionOutputTypeDef = TypedDict(
     "DescribeExecutionOutputTypeDef",
     {
         "executionArn": str,
         "stateMachineArn": str,
         "name": str,
@@ -1016,50 +1300,17 @@
         "inputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "output": str,
         "outputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "traceHeader": str,
         "mapRunArn": str,
         "error": str,
         "cause": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetActivityTaskOutputTypeDef = TypedDict(
-    "GetActivityTaskOutputTypeDef",
-    {
-        "taskToken": str,
-        "input": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListActivitiesOutputTypeDef = TypedDict(
-    "ListActivitiesOutputTypeDef",
-    {
-        "activities": List[ActivityListItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartExecutionOutputTypeDef = TypedDict(
-    "StartExecutionOutputTypeDef",
-    {
-        "executionArn": str,
-        "startDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "stateMachineVersionArn": str,
+        "stateMachineAliasArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSyncExecutionOutputTypeDef = TypedDict(
     "StartSyncExecutionOutputTypeDef",
     {
         "executionArn": str,
@@ -1072,127 +1323,146 @@
         "cause": str,
         "input": str,
         "inputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "output": str,
         "outputDetails": CloudWatchEventsExecutionDataDetailsTypeDef,
         "traceHeader": str,
         "billingDetails": BillingDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopExecutionOutputTypeDef = TypedDict(
-    "StopExecutionOutputTypeDef",
+LogDestinationTypeDef = TypedDict(
+    "LogDestinationTypeDef",
     {
-        "stopDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cloudWatchLogsLogGroup": CloudWatchLogsLogGroupTypeDef,
     },
+    total=False,
 )
 
-UpdateStateMachineOutputTypeDef = TypedDict(
-    "UpdateStateMachineOutputTypeDef",
+_RequiredCreateActivityInputRequestTypeDef = TypedDict(
+    "_RequiredCreateActivityInputRequestTypeDef",
     {
-        "updateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
     },
 )
+_OptionalCreateActivityInputRequestTypeDef = TypedDict(
+    "_OptionalCreateActivityInputRequestTypeDef",
+    {
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
 
-DescribeMapRunOutputTypeDef = TypedDict(
-    "DescribeMapRunOutputTypeDef",
+
+class CreateActivityInputRequestTypeDef(
+    _RequiredCreateActivityInputRequestTypeDef, _OptionalCreateActivityInputRequestTypeDef
+):
+    pass
+
+
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
     {
-        "mapRunArn": str,
-        "executionArn": str,
-        "status": MapRunStatusType,
-        "startDate": datetime,
-        "stopDate": datetime,
-        "maxConcurrency": int,
-        "toleratedFailurePercentage": float,
-        "toleratedFailureCount": int,
-        "itemCounts": MapRunItemCountsTypeDef,
-        "executionCounts": MapRunExecutionCountsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListExecutionsOutputTypeDef = TypedDict(
-    "ListExecutionsOutputTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "executions": List[ExecutionListItemTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
-_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+_RequiredCreateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_RequiredCreateStateMachineAliasInputRequestTypeDef",
     {
-        "executionArn": str,
+        "name": str,
+        "routingConfiguration": Sequence[RoutingConfigurationListItemTypeDef],
     },
 )
-_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef",
+_OptionalCreateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_OptionalCreateStateMachineAliasInputRequestTypeDef",
     {
-        "reverseOrder": bool,
-        "includeExecutionData": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "description": str,
     },
     total=False,
 )
 
-class GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef(
-    _RequiredGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
-    _OptionalGetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
+
+class CreateStateMachineAliasInputRequestTypeDef(
+    _RequiredCreateStateMachineAliasInputRequestTypeDef,
+    _OptionalCreateStateMachineAliasInputRequestTypeDef,
 ):
     pass
 
-ListActivitiesInputListActivitiesPaginateTypeDef = TypedDict(
-    "ListActivitiesInputListActivitiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-ListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
-    "ListExecutionsInputListExecutionsPaginateTypeDef",
+DescribeStateMachineAliasOutputTypeDef = TypedDict(
+    "DescribeStateMachineAliasOutputTypeDef",
     {
-        "stateMachineArn": str,
-        "statusFilter": ExecutionStatusType,
-        "mapRunArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "stateMachineAliasArn": str,
+        "name": str,
+        "description": str,
+        "routingConfiguration": List[RoutingConfigurationListItemTypeDef],
+        "creationDate": datetime,
+        "updateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
-    "_RequiredListMapRunsInputListMapRunsPaginateTypeDef",
+_RequiredUpdateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_RequiredUpdateStateMachineAliasInputRequestTypeDef",
     {
-        "executionArn": str,
+        "stateMachineAliasArn": str,
     },
 )
-_OptionalListMapRunsInputListMapRunsPaginateTypeDef = TypedDict(
-    "_OptionalListMapRunsInputListMapRunsPaginateTypeDef",
+_OptionalUpdateStateMachineAliasInputRequestTypeDef = TypedDict(
+    "_OptionalUpdateStateMachineAliasInputRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "description": str,
+        "routingConfiguration": Sequence[RoutingConfigurationListItemTypeDef],
     },
     total=False,
 )
 
-class ListMapRunsInputListMapRunsPaginateTypeDef(
-    _RequiredListMapRunsInputListMapRunsPaginateTypeDef,
-    _OptionalListMapRunsInputListMapRunsPaginateTypeDef,
+
+class UpdateStateMachineAliasInputRequestTypeDef(
+    _RequiredUpdateStateMachineAliasInputRequestTypeDef,
+    _OptionalUpdateStateMachineAliasInputRequestTypeDef,
 ):
     pass
 
-ListStateMachinesInputListStateMachinesPaginateTypeDef = TypedDict(
-    "ListStateMachinesInputListStateMachinesPaginateTypeDef",
+
+DescribeMapRunOutputTypeDef = TypedDict(
+    "DescribeMapRunOutputTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "mapRunArn": str,
+        "executionArn": str,
+        "status": MapRunStatusType,
+        "startDate": datetime,
+        "stopDate": datetime,
+        "maxConcurrency": int,
+        "toleratedFailurePercentage": float,
+        "toleratedFailureCount": int,
+        "itemCounts": MapRunItemCountsTypeDef,
+        "executionCounts": MapRunExecutionCountsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListExecutionsOutputTypeDef = TypedDict(
+    "ListExecutionsOutputTypeDef",
+    {
+        "executions": List[ExecutionListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredLambdaFunctionScheduledEventDetailsTypeDef = TypedDict(
     "_RequiredLambdaFunctionScheduledEventDetailsTypeDef",
     {
         "resource": str,
     },
@@ -1204,20 +1474,22 @@
         "inputDetails": HistoryEventExecutionDataDetailsTypeDef,
         "timeoutInSeconds": int,
         "taskCredentials": TaskCredentialsTypeDef,
     },
     total=False,
 )
 
+
 class LambdaFunctionScheduledEventDetailsTypeDef(
     _RequiredLambdaFunctionScheduledEventDetailsTypeDef,
     _OptionalLambdaFunctionScheduledEventDetailsTypeDef,
 ):
     pass
 
+
 _RequiredTaskScheduledEventDetailsTypeDef = TypedDict(
     "_RequiredTaskScheduledEventDetailsTypeDef",
     {
         "resourceType": str,
         "resource": str,
         "region": str,
         "parameters": str,
@@ -1229,34 +1501,54 @@
         "timeoutInSeconds": int,
         "heartbeatInSeconds": int,
         "taskCredentials": TaskCredentialsTypeDef,
     },
     total=False,
 )
 
+
 class TaskScheduledEventDetailsTypeDef(
     _RequiredTaskScheduledEventDetailsTypeDef, _OptionalTaskScheduledEventDetailsTypeDef
 ):
     pass
 
+
 ListMapRunsOutputTypeDef = TypedDict(
     "ListMapRunsOutputTypeDef",
     {
         "mapRuns": List[MapRunListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStateMachineAliasesOutputTypeDef = TypedDict(
+    "ListStateMachineAliasesOutputTypeDef",
+    {
+        "stateMachineAliases": List[StateMachineAliasListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStateMachineVersionsOutputTypeDef = TypedDict(
+    "ListStateMachineVersionsOutputTypeDef",
+    {
+        "stateMachineVersions": List[StateMachineVersionListItemTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStateMachinesOutputTypeDef = TypedDict(
     "ListStateMachinesOutputTypeDef",
     {
         "stateMachines": List[StateMachineListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoggingConfigurationTypeDef = TypedDict(
     "LoggingConfigurationTypeDef",
     {
         "level": LogLevelType,
@@ -1312,17 +1604,19 @@
         "stateExitedEventDetails": StateExitedEventDetailsTypeDef,
         "mapRunStartedEventDetails": MapRunStartedEventDetailsTypeDef,
         "mapRunFailedEventDetails": MapRunFailedEventDetailsTypeDef,
     },
     total=False,
 )
 
+
 class HistoryEventTypeDef(_RequiredHistoryEventTypeDef, _OptionalHistoryEventTypeDef):
     pass
 
+
 _RequiredCreateStateMachineInputRequestTypeDef = TypedDict(
     "_RequiredCreateStateMachineInputRequestTypeDef",
     {
         "name": str,
         "definition": str,
         "roleArn": str,
     },
@@ -1330,36 +1624,41 @@
 _OptionalCreateStateMachineInputRequestTypeDef = TypedDict(
     "_OptionalCreateStateMachineInputRequestTypeDef",
     {
         "type": StateMachineTypeType,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tags": Sequence[TagTypeDef],
         "tracingConfiguration": TracingConfigurationTypeDef,
+        "publish": bool,
+        "versionDescription": str,
     },
     total=False,
 )
 
+
 class CreateStateMachineInputRequestTypeDef(
     _RequiredCreateStateMachineInputRequestTypeDef, _OptionalCreateStateMachineInputRequestTypeDef
 ):
     pass
 
+
 DescribeStateMachineForExecutionOutputTypeDef = TypedDict(
     "DescribeStateMachineForExecutionOutputTypeDef",
     {
         "stateMachineArn": str,
         "name": str,
         "definition": str,
         "roleArn": str,
         "updateDate": datetime,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tracingConfiguration": TracingConfigurationTypeDef,
         "mapRunArn": str,
         "label": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStateMachineOutputTypeDef = TypedDict(
     "DescribeStateMachineOutputTypeDef",
     {
         "stateMachineArn": str,
@@ -1368,15 +1667,17 @@
         "definition": str,
         "roleArn": str,
         "type": StateMachineTypeType,
         "creationDate": datetime,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tracingConfiguration": TracingConfigurationTypeDef,
         "label": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "revisionId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateStateMachineInputRequestTypeDef = TypedDict(
     "_RequiredUpdateStateMachineInputRequestTypeDef",
     {
         "stateMachineArn": str,
@@ -1385,24 +1686,28 @@
 _OptionalUpdateStateMachineInputRequestTypeDef = TypedDict(
     "_OptionalUpdateStateMachineInputRequestTypeDef",
     {
         "definition": str,
         "roleArn": str,
         "loggingConfiguration": LoggingConfigurationTypeDef,
         "tracingConfiguration": TracingConfigurationTypeDef,
+        "publish": bool,
+        "versionDescription": str,
     },
     total=False,
 )
 
+
 class UpdateStateMachineInputRequestTypeDef(
     _RequiredUpdateStateMachineInputRequestTypeDef, _OptionalUpdateStateMachineInputRequestTypeDef
 ):
     pass
 
+
 GetExecutionHistoryOutputTypeDef = TypedDict(
     "GetExecutionHistoryOutputTypeDef",
     {
         "events": List[HistoryEventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/PKG-INFO` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-stepfunctions
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SFN 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SFN 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-stepfunctions"></a>
 
 # types-aiobotocore-stepfunctions
 
 [![PyPI - types-aiobotocore-stepfunctions](https://img.shields.io/pypi/v/types-aiobotocore-stepfunctions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-stepfunctions)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-stepfunctions.svg?color=blue)](https://pypi.org/project/types-aiobotocore-stepfunctions)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-stepfunctions?color=blue)](https://pypistats.org/packages/types-aiobotocore-stepfunctions)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SFN 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN)
+[aiobotocore.SFN 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/stepfunctions.html#SFN)
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
 [types-aiobotocore-stepfunctions docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_stepfunctions/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,31 +348,39 @@
     HistoryEventExecutionDataDetailsTypeDef,
     ActivityStartedEventDetailsTypeDef,
     ActivityTimedOutEventDetailsTypeDef,
     BillingDetailsTypeDef,
     CloudWatchEventsExecutionDataDetailsTypeDef,
     CloudWatchLogsLogGroupTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateActivityOutputTypeDef,
+    RoutingConfigurationListItemTypeDef,
+    CreateStateMachineAliasOutputTypeDef,
     TracingConfigurationTypeDef,
+    CreateStateMachineOutputTypeDef,
     DeleteActivityInputRequestTypeDef,
+    DeleteStateMachineAliasInputRequestTypeDef,
     DeleteStateMachineInputRequestTypeDef,
+    DeleteStateMachineVersionInputRequestTypeDef,
     DescribeActivityInputRequestTypeDef,
+    DescribeActivityOutputTypeDef,
     DescribeExecutionInputRequestTypeDef,
     DescribeMapRunInputRequestTypeDef,
     MapRunExecutionCountsTypeDef,
     MapRunItemCountsTypeDef,
+    DescribeStateMachineAliasInputRequestTypeDef,
     DescribeStateMachineForExecutionInputRequestTypeDef,
     DescribeStateMachineInputRequestTypeDef,
     ExecutionAbortedEventDetailsTypeDef,
     ExecutionFailedEventDetailsTypeDef,
     ExecutionListItemTypeDef,
     ExecutionTimedOutEventDetailsTypeDef,
     GetActivityTaskInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetActivityTaskOutputTypeDef,
+    GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
     GetExecutionHistoryInputRequestTypeDef,
     LambdaFunctionFailedEventDetailsTypeDef,
     LambdaFunctionScheduleFailedEventDetailsTypeDef,
     LambdaFunctionStartFailedEventDetailsTypeDef,
     LambdaFunctionTimedOutEventDetailsTypeDef,
     MapIterationEventDetailsTypeDef,
     MapRunFailedEventDetailsTypeDef,
@@ -380,62 +388,71 @@
     MapStateStartedEventDetailsTypeDef,
     TaskFailedEventDetailsTypeDef,
     TaskStartFailedEventDetailsTypeDef,
     TaskStartedEventDetailsTypeDef,
     TaskSubmitFailedEventDetailsTypeDef,
     TaskTimedOutEventDetailsTypeDef,
     TaskCredentialsTypeDef,
+    ListActivitiesInputListActivitiesPaginateTypeDef,
     ListActivitiesInputRequestTypeDef,
+    ListExecutionsInputListExecutionsPaginateTypeDef,
     ListExecutionsInputRequestTypeDef,
+    ListMapRunsInputListMapRunsPaginateTypeDef,
     ListMapRunsInputRequestTypeDef,
     MapRunListItemTypeDef,
+    ListStateMachineAliasesInputRequestTypeDef,
+    StateMachineAliasListItemTypeDef,
+    ListStateMachineVersionsInputRequestTypeDef,
+    StateMachineVersionListItemTypeDef,
+    ListStateMachinesInputListStateMachinesPaginateTypeDef,
     ListStateMachinesInputRequestTypeDef,
     StateMachineListItemTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PublishStateMachineVersionInputRequestTypeDef,
+    PublishStateMachineVersionOutputTypeDef,
+    ResponseMetadataTypeDef,
     SendTaskFailureInputRequestTypeDef,
     SendTaskHeartbeatInputRequestTypeDef,
     SendTaskSuccessInputRequestTypeDef,
     StartExecutionInputRequestTypeDef,
+    StartExecutionOutputTypeDef,
     StartSyncExecutionInputRequestTypeDef,
     StopExecutionInputRequestTypeDef,
+    StopExecutionOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateMapRunInputRequestTypeDef,
+    UpdateStateMachineAliasOutputTypeDef,
+    UpdateStateMachineOutputTypeDef,
+    ListActivitiesOutputTypeDef,
     ActivityScheduledEventDetailsTypeDef,
     ActivitySucceededEventDetailsTypeDef,
     ExecutionStartedEventDetailsTypeDef,
     ExecutionSucceededEventDetailsTypeDef,
     LambdaFunctionSucceededEventDetailsTypeDef,
     StateEnteredEventDetailsTypeDef,
     StateExitedEventDetailsTypeDef,
     TaskSubmittedEventDetailsTypeDef,
     TaskSucceededEventDetailsTypeDef,
+    DescribeExecutionOutputTypeDef,
+    StartSyncExecutionOutputTypeDef,
     LogDestinationTypeDef,
     CreateActivityInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
-    CreateActivityOutputTypeDef,
-    CreateStateMachineOutputTypeDef,
-    DescribeActivityOutputTypeDef,
-    DescribeExecutionOutputTypeDef,
-    GetActivityTaskOutputTypeDef,
-    ListActivitiesOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
-    StartExecutionOutputTypeDef,
-    StartSyncExecutionOutputTypeDef,
-    StopExecutionOutputTypeDef,
-    UpdateStateMachineOutputTypeDef,
+    TagResourceInputRequestTypeDef,
+    CreateStateMachineAliasInputRequestTypeDef,
+    DescribeStateMachineAliasOutputTypeDef,
+    UpdateStateMachineAliasInputRequestTypeDef,
     DescribeMapRunOutputTypeDef,
     ListExecutionsOutputTypeDef,
-    GetExecutionHistoryInputGetExecutionHistoryPaginateTypeDef,
-    ListActivitiesInputListActivitiesPaginateTypeDef,
-    ListExecutionsInputListExecutionsPaginateTypeDef,
-    ListMapRunsInputListMapRunsPaginateTypeDef,
-    ListStateMachinesInputListStateMachinesPaginateTypeDef,
     LambdaFunctionScheduledEventDetailsTypeDef,
     TaskScheduledEventDetailsTypeDef,
     ListMapRunsOutputTypeDef,
+    ListStateMachineAliasesOutputTypeDef,
+    ListStateMachineVersionsOutputTypeDef,
     ListStateMachinesOutputTypeDef,
     LoggingConfigurationTypeDef,
     HistoryEventTypeDef,
     CreateStateMachineInputRequestTypeDef,
     DescribeStateMachineForExecutionOutputTypeDef,
     DescribeStateMachineOutputTypeDef,
     UpdateStateMachineInputRequestTypeDef,
@@ -450,43 +467,43 @@
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

### Comparing `types-aiobotocore-stepfunctions-2.5.0.post1/types_aiobotocore_stepfunctions.egg-info/SOURCES.txt` & `types-aiobotocore-stepfunctions-2.5.1/types_aiobotocore_stepfunctions.egg-info/SOURCES.txt`

 * *Files identical despite different names*

