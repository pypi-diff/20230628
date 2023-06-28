# Comparing `tmp/types-aiobotocore-swf-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-swf-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-swf-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:25 2023, max compression
+gzip compressed data, was "types-aiobotocore-swf-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-swf-2.5.0.post1.tar` & `types-aiobotocore-swf-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.847680 types-aiobotocore-swf-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21866 2023-03-11 12:27:25.843680 types-aiobotocore-swf-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20311 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:25.847680 types-aiobotocore-swf-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.843680 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/
--rw-r--r--   0 runner    (1001) docker     (123)     2081 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2080 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    32936 2023-03-11 12:24:57.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    32883 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15794 2023-03-11 12:24:57.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    15792 2023-03-11 12:24:57.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10219 2023-03-11 12:24:57.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10209 2023-03-11 12:24:57.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    83818 2023-03-11 12:24:58.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    83661 2023-03-11 12:24:58.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:56.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.843680 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21866 2023-03-11 12:27:25.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:25.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:25.000000 types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.578225 types-aiobotocore-swf-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21854 2023-06-28 01:44:16.578225 types-aiobotocore-swf-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20305 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.578225 types-aiobotocore-swf-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.578225 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/
+-rw-r--r--   0 runner    (1001) docker     (123)     2081 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2080 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32985 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32932 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    16003 2023-06-28 01:41:46.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16001 2023-06-28 01:41:46.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10162 2023-06-28 01:41:46.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10153 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    83956 2023-06-28 01:41:47.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83799 2023-06-28 01:41:46.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:45.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.578225 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21854 2023-06-28 01:44:16.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:16.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:16.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:16.000000 types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/LICENSE` & `types-aiobotocore-swf-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-swf-2.5.0.post1/PKG-INFO` & `types-aiobotocore-swf-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-swf
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SWF 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SWF 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-swf"></a>
 
 # types-aiobotocore-swf
 
 [![PyPI - types-aiobotocore-swf](https://img.shields.io/pypi/v/types-aiobotocore-swf.svg?color=blue)](https://pypi.org/project/types-aiobotocore-swf)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-swf.svg?color=blue)](https://pypi.org/project/types-aiobotocore-swf)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-swf?color=blue)](https://pypistats.org/packages/types-aiobotocore-swf)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SWF 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
+[aiobotocore.SWF 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
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
 [types-aiobotocore-swf docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/).
 
 See how it helps to find and fix potential bugs:
 
@@ -377,15 +377,15 @@
     ActivityTaskCancelRequestedEventAttributesTypeDef,
     ActivityTaskCanceledEventAttributesTypeDef,
     ActivityTaskCompletedEventAttributesTypeDef,
     ActivityTaskFailedEventAttributesTypeDef,
     ActivityTypeTypeDef,
     TaskListTypeDef,
     ActivityTaskStartedEventAttributesTypeDef,
-    ResponseMetadataTypeDef,
+    ActivityTaskStatusTypeDef,
     ActivityTaskTimedOutEventAttributesTypeDef,
     WorkflowExecutionTypeDef,
     CancelTimerDecisionAttributesTypeDef,
     CancelTimerFailedEventAttributesTypeDef,
     CancelWorkflowExecutionDecisionAttributesTypeDef,
     CancelWorkflowExecutionFailedEventAttributesTypeDef,
     WorkflowTypeTypeDef,
@@ -407,16 +407,16 @@
     ScheduleLambdaFunctionDecisionAttributesTypeDef,
     SignalExternalWorkflowExecutionDecisionAttributesTypeDef,
     StartTimerDecisionAttributesTypeDef,
     DeprecateDomainInputRequestTypeDef,
     DescribeDomainInputRequestTypeDef,
     DomainConfigurationTypeDef,
     DomainInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     FailWorkflowExecutionFailedEventAttributesTypeDef,
-    PaginatorConfigTypeDef,
     LambdaFunctionCompletedEventAttributesTypeDef,
     LambdaFunctionFailedEventAttributesTypeDef,
     LambdaFunctionScheduledEventAttributesTypeDef,
     LambdaFunctionStartedEventAttributesTypeDef,
     LambdaFunctionTimedOutEventAttributesTypeDef,
     MarkerRecordedEventAttributesTypeDef,
     RecordMarkerFailedEventAttributesTypeDef,
@@ -432,56 +432,61 @@
     TimerFiredEventAttributesTypeDef,
     TimerStartedEventAttributesTypeDef,
     WorkflowExecutionCanceledEventAttributesTypeDef,
     WorkflowExecutionCompletedEventAttributesTypeDef,
     WorkflowExecutionFailedEventAttributesTypeDef,
     WorkflowExecutionTerminatedEventAttributesTypeDef,
     WorkflowExecutionTimedOutEventAttributesTypeDef,
+    ListActivityTypesInputListActivityTypesPaginateTypeDef,
     ListActivityTypesInputRequestTypeDef,
+    ListDomainsInputListDomainsPaginateTypeDef,
     ListDomainsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     ResourceTagTypeDef,
+    ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
     ListWorkflowTypesInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PendingTaskCountTypeDef,
     RecordActivityTaskHeartbeatInputRequestTypeDef,
     RequestCancelWorkflowExecutionInputRequestTypeDef,
     RespondActivityTaskCanceledInputRequestTypeDef,
     RespondActivityTaskCompletedInputRequestTypeDef,
     RespondActivityTaskFailedInputRequestTypeDef,
+    ResponseMetadataTypeDef,
+    RunTypeDef,
     SignalWorkflowExecutionInputRequestTypeDef,
     TerminateWorkflowExecutionInputRequestTypeDef,
     UndeprecateDomainInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    WorkflowExecutionCountTypeDef,
     WorkflowExecutionOpenCountsTypeDef,
     ActivityTypeInfoTypeDef,
     DeprecateActivityTypeInputRequestTypeDef,
     DescribeActivityTypeInputRequestTypeDef,
     ScheduleActivityTaskFailedEventAttributesTypeDef,
     UndeprecateActivityTypeInputRequestTypeDef,
     ActivityTaskScheduledEventAttributesTypeDef,
     ActivityTypeConfigurationTypeDef,
     ContinueAsNewWorkflowExecutionDecisionAttributesTypeDef,
     CountPendingActivityTasksInputRequestTypeDef,
     CountPendingDecisionTasksInputRequestTypeDef,
     DecisionTaskScheduledEventAttributesTypeDef,
     PollForActivityTaskInputRequestTypeDef,
+    PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
     PollForDecisionTaskInputRequestTypeDef,
     RegisterActivityTypeInputRequestTypeDef,
     RegisterWorkflowTypeInputRequestTypeDef,
     ScheduleActivityTaskDecisionAttributesTypeDef,
     WorkflowExecutionConfigurationTypeDef,
     WorkflowTypeConfigurationTypeDef,
-    ActivityTaskStatusTypeDef,
-    EmptyResponseMetadataTypeDef,
-    PendingTaskCountTypeDef,
-    RunTypeDef,
-    WorkflowExecutionCountTypeDef,
     ActivityTaskTypeDef,
     DescribeWorkflowExecutionInputRequestTypeDef,
     ExternalWorkflowExecutionCancelRequestedEventAttributesTypeDef,
     ExternalWorkflowExecutionSignaledEventAttributesTypeDef,
+    GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
     GetWorkflowExecutionHistoryInputRequestTypeDef,
     WorkflowExecutionCancelRequestedEventAttributesTypeDef,
     WorkflowExecutionSignaledEventAttributesTypeDef,
     ChildWorkflowExecutionCanceledEventAttributesTypeDef,
     ChildWorkflowExecutionCompletedEventAttributesTypeDef,
     ChildWorkflowExecutionFailedEventAttributesTypeDef,
     ChildWorkflowExecutionStartedEventAttributesTypeDef,
@@ -496,25 +501,20 @@
     UndeprecateWorkflowTypeInputRequestTypeDef,
     WorkflowExecutionContinuedAsNewEventAttributesTypeDef,
     WorkflowExecutionInfoTypeDef,
     WorkflowExecutionStartedEventAttributesTypeDef,
     WorkflowTypeInfoTypeDef,
     CountClosedWorkflowExecutionsInputRequestTypeDef,
     CountOpenWorkflowExecutionsInputRequestTypeDef,
+    ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
     ListClosedWorkflowExecutionsInputRequestTypeDef,
+    ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
     ListOpenWorkflowExecutionsInputRequestTypeDef,
     DomainDetailTypeDef,
     DomainInfosTypeDef,
-    GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-    ListActivityTypesInputListActivityTypesPaginateTypeDef,
-    ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
-    ListDomainsInputListDomainsPaginateTypeDef,
-    ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
-    ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
-    PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
     ListTagsForResourceOutputTypeDef,
     RegisterDomainInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     ActivityTypeInfosTypeDef,
     ActivityTypeDetailTypeDef,
     DecisionTypeDef,
     WorkflowExecutionDetailTypeDef,
@@ -535,43 +535,43 @@
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/README.md` & `types-aiobotocore-swf-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-swf"></a>
 
 # types-aiobotocore-swf
 
 [![PyPI - types-aiobotocore-swf](https://img.shields.io/pypi/v/types-aiobotocore-swf.svg?color=blue)](https://pypi.org/project/types-aiobotocore-swf)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-swf.svg?color=blue)](https://pypi.org/project/types-aiobotocore-swf)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-swf?color=blue)](https://pypistats.org/packages/types-aiobotocore-swf)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SWF 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
+[aiobotocore.SWF 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
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
 [types-aiobotocore-swf docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,15 +344,15 @@
     ActivityTaskCancelRequestedEventAttributesTypeDef,
     ActivityTaskCanceledEventAttributesTypeDef,
     ActivityTaskCompletedEventAttributesTypeDef,
     ActivityTaskFailedEventAttributesTypeDef,
     ActivityTypeTypeDef,
     TaskListTypeDef,
     ActivityTaskStartedEventAttributesTypeDef,
-    ResponseMetadataTypeDef,
+    ActivityTaskStatusTypeDef,
     ActivityTaskTimedOutEventAttributesTypeDef,
     WorkflowExecutionTypeDef,
     CancelTimerDecisionAttributesTypeDef,
     CancelTimerFailedEventAttributesTypeDef,
     CancelWorkflowExecutionDecisionAttributesTypeDef,
     CancelWorkflowExecutionFailedEventAttributesTypeDef,
     WorkflowTypeTypeDef,
@@ -374,16 +374,16 @@
     ScheduleLambdaFunctionDecisionAttributesTypeDef,
     SignalExternalWorkflowExecutionDecisionAttributesTypeDef,
     StartTimerDecisionAttributesTypeDef,
     DeprecateDomainInputRequestTypeDef,
     DescribeDomainInputRequestTypeDef,
     DomainConfigurationTypeDef,
     DomainInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     FailWorkflowExecutionFailedEventAttributesTypeDef,
-    PaginatorConfigTypeDef,
     LambdaFunctionCompletedEventAttributesTypeDef,
     LambdaFunctionFailedEventAttributesTypeDef,
     LambdaFunctionScheduledEventAttributesTypeDef,
     LambdaFunctionStartedEventAttributesTypeDef,
     LambdaFunctionTimedOutEventAttributesTypeDef,
     MarkerRecordedEventAttributesTypeDef,
     RecordMarkerFailedEventAttributesTypeDef,
@@ -399,56 +399,61 @@
     TimerFiredEventAttributesTypeDef,
     TimerStartedEventAttributesTypeDef,
     WorkflowExecutionCanceledEventAttributesTypeDef,
     WorkflowExecutionCompletedEventAttributesTypeDef,
     WorkflowExecutionFailedEventAttributesTypeDef,
     WorkflowExecutionTerminatedEventAttributesTypeDef,
     WorkflowExecutionTimedOutEventAttributesTypeDef,
+    ListActivityTypesInputListActivityTypesPaginateTypeDef,
     ListActivityTypesInputRequestTypeDef,
+    ListDomainsInputListDomainsPaginateTypeDef,
     ListDomainsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     ResourceTagTypeDef,
+    ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
     ListWorkflowTypesInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PendingTaskCountTypeDef,
     RecordActivityTaskHeartbeatInputRequestTypeDef,
     RequestCancelWorkflowExecutionInputRequestTypeDef,
     RespondActivityTaskCanceledInputRequestTypeDef,
     RespondActivityTaskCompletedInputRequestTypeDef,
     RespondActivityTaskFailedInputRequestTypeDef,
+    ResponseMetadataTypeDef,
+    RunTypeDef,
     SignalWorkflowExecutionInputRequestTypeDef,
     TerminateWorkflowExecutionInputRequestTypeDef,
     UndeprecateDomainInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    WorkflowExecutionCountTypeDef,
     WorkflowExecutionOpenCountsTypeDef,
     ActivityTypeInfoTypeDef,
     DeprecateActivityTypeInputRequestTypeDef,
     DescribeActivityTypeInputRequestTypeDef,
     ScheduleActivityTaskFailedEventAttributesTypeDef,
     UndeprecateActivityTypeInputRequestTypeDef,
     ActivityTaskScheduledEventAttributesTypeDef,
     ActivityTypeConfigurationTypeDef,
     ContinueAsNewWorkflowExecutionDecisionAttributesTypeDef,
     CountPendingActivityTasksInputRequestTypeDef,
     CountPendingDecisionTasksInputRequestTypeDef,
     DecisionTaskScheduledEventAttributesTypeDef,
     PollForActivityTaskInputRequestTypeDef,
+    PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
     PollForDecisionTaskInputRequestTypeDef,
     RegisterActivityTypeInputRequestTypeDef,
     RegisterWorkflowTypeInputRequestTypeDef,
     ScheduleActivityTaskDecisionAttributesTypeDef,
     WorkflowExecutionConfigurationTypeDef,
     WorkflowTypeConfigurationTypeDef,
-    ActivityTaskStatusTypeDef,
-    EmptyResponseMetadataTypeDef,
-    PendingTaskCountTypeDef,
-    RunTypeDef,
-    WorkflowExecutionCountTypeDef,
     ActivityTaskTypeDef,
     DescribeWorkflowExecutionInputRequestTypeDef,
     ExternalWorkflowExecutionCancelRequestedEventAttributesTypeDef,
     ExternalWorkflowExecutionSignaledEventAttributesTypeDef,
+    GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
     GetWorkflowExecutionHistoryInputRequestTypeDef,
     WorkflowExecutionCancelRequestedEventAttributesTypeDef,
     WorkflowExecutionSignaledEventAttributesTypeDef,
     ChildWorkflowExecutionCanceledEventAttributesTypeDef,
     ChildWorkflowExecutionCompletedEventAttributesTypeDef,
     ChildWorkflowExecutionFailedEventAttributesTypeDef,
     ChildWorkflowExecutionStartedEventAttributesTypeDef,
@@ -463,25 +468,20 @@
     UndeprecateWorkflowTypeInputRequestTypeDef,
     WorkflowExecutionContinuedAsNewEventAttributesTypeDef,
     WorkflowExecutionInfoTypeDef,
     WorkflowExecutionStartedEventAttributesTypeDef,
     WorkflowTypeInfoTypeDef,
     CountClosedWorkflowExecutionsInputRequestTypeDef,
     CountOpenWorkflowExecutionsInputRequestTypeDef,
+    ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
     ListClosedWorkflowExecutionsInputRequestTypeDef,
+    ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
     ListOpenWorkflowExecutionsInputRequestTypeDef,
     DomainDetailTypeDef,
     DomainInfosTypeDef,
-    GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-    ListActivityTypesInputListActivityTypesPaginateTypeDef,
-    ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
-    ListDomainsInputListDomainsPaginateTypeDef,
-    ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
-    ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
-    PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
     ListTagsForResourceOutputTypeDef,
     RegisterDomainInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     ActivityTypeInfosTypeDef,
     ActivityTypeDetailTypeDef,
     DecisionTypeDef,
     WorkflowExecutionDetailTypeDef,
@@ -502,43 +502,43 @@
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/setup.py` & `types-aiobotocore-swf-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-swf.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-swf",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_swf"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SWF 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SWF 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/",
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/__init__.py` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/__init__.pyi` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/__main__.py` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SWF 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SWF 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF\nOther"
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/client.py` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -393,15 +393,16 @@
         self,
         *,
         domain: str,
         taskList: TaskListTypeDef,
         identity: str = ...,
         nextPageToken: str = ...,
         maximumPageSize: int = ...,
-        reverseOrder: bool = ...
+        reverseOrder: bool = ...,
+        startAtPreviousStartedEvent: bool = ...
     ) -> DecisionTaskTypeDef:
         """
         Used by deciders to get a  DecisionTask from the specified decision `taskList`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Client.poll_for_decision_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/client/#poll_for_decision_task)
         """
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/client.pyi` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -366,15 +366,16 @@
         self,
         *,
         domain: str,
         taskList: TaskListTypeDef,
         identity: str = ...,
         nextPageToken: str = ...,
         maximumPageSize: int = ...,
-        reverseOrder: bool = ...
+        reverseOrder: bool = ...,
+        startAtPreviousStartedEvent: bool = ...
     ) -> DecisionTaskTypeDef:
         """
         Used by deciders to get a  DecisionTask from the specified decision `taskList`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Client.poll_for_decision_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/client/#poll_for_decision_task)
         """
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/literals.py` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -280,14 +280,15 @@
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
@@ -366,14 +367,15 @@
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
@@ -384,14 +386,15 @@
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
@@ -427,14 +430,15 @@
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
@@ -453,16 +457,19 @@
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
@@ -546,15 +553,17 @@
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/literals.pyi` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -278,14 +278,15 @@
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
@@ -364,14 +365,15 @@
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
@@ -382,14 +384,15 @@
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
@@ -425,14 +428,15 @@
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
@@ -451,16 +455,19 @@
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
@@ -544,15 +551,17 @@
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/paginator.py` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_closed_workflow_executions_paginator: ListClosedWorkflowExecutionsPaginator = client.get_paginator("list_closed_workflow_executions")
         list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
         list_open_workflow_executions_paginator: ListOpenWorkflowExecutionsPaginator = client.get_paginator("list_open_workflow_executions")
         list_workflow_types_paginator: ListWorkflowTypesPaginator = client.get_paginator("list_workflow_types")
         poll_for_decision_task_paginator: PollForDecisionTaskPaginator = client.get_paginator("poll_for_decision_task")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import RegistrationStatusType
 from .type_defs import (
     ActivityTypeInfosTypeDef,
@@ -52,82 +51,71 @@
     WorkflowExecutionFilterTypeDef,
     WorkflowExecutionInfosTypeDef,
     WorkflowExecutionTypeDef,
     WorkflowTypeFilterTypeDef,
     WorkflowTypeInfosTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetWorkflowExecutionHistoryPaginator",
     "ListActivityTypesPaginator",
     "ListClosedWorkflowExecutionsPaginator",
     "ListDomainsPaginator",
     "ListOpenWorkflowExecutionsPaginator",
     "ListWorkflowTypesPaginator",
     "PollForDecisionTaskPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class GetWorkflowExecutionHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.GetWorkflowExecutionHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#getworkflowexecutionhistorypaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         execution: WorkflowExecutionTypeDef,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[HistoryTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.GetWorkflowExecutionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#getworkflowexecutionhistorypaginator)
         """
 
-
 class ListActivityTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListActivityTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listactivitytypespaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         registrationStatus: RegistrationStatusType,
         name: str = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ActivityTypeInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListActivityTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listactivitytypespaginator)
         """
 
-
 class ListClosedWorkflowExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListClosedWorkflowExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listclosedworkflowexecutionspaginator)
     """
 
     def paginate(
@@ -137,41 +125,39 @@
         startTimeFilter: ExecutionTimeFilterTypeDef = ...,
         closeTimeFilter: ExecutionTimeFilterTypeDef = ...,
         executionFilter: WorkflowExecutionFilterTypeDef = ...,
         closeStatusFilter: CloseStatusFilterTypeDef = ...,
         typeFilter: WorkflowTypeFilterTypeDef = ...,
         tagFilter: TagFilterTypeDef = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[WorkflowExecutionInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListClosedWorkflowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listclosedworkflowexecutionspaginator)
         """
 
-
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listdomainspaginator)
     """
 
     def paginate(
         self,
         *,
         registrationStatus: RegistrationStatusType,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DomainInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listdomainspaginator)
         """
 
-
 class ListOpenWorkflowExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListOpenWorkflowExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listopenworkflowexecutionspaginator)
     """
 
     def paginate(
@@ -179,55 +165,54 @@
         *,
         domain: str,
         startTimeFilter: ExecutionTimeFilterTypeDef,
         typeFilter: WorkflowTypeFilterTypeDef = ...,
         tagFilter: TagFilterTypeDef = ...,
         reverseOrder: bool = ...,
         executionFilter: WorkflowExecutionFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[WorkflowExecutionInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListOpenWorkflowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listopenworkflowexecutionspaginator)
         """
 
-
 class ListWorkflowTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListWorkflowTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listworkflowtypespaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         registrationStatus: RegistrationStatusType,
         name: str = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[WorkflowTypeInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListWorkflowTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listworkflowtypespaginator)
         """
 
-
 class PollForDecisionTaskPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.PollForDecisionTask)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#pollfordecisiontaskpaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         taskList: TaskListTypeDef,
         identity: str = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        startAtPreviousStartedEvent: bool = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DecisionTaskTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.PollForDecisionTask.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#pollfordecisiontaskpaginator)
         """
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/paginator.pyi` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_closed_workflow_executions_paginator: ListClosedWorkflowExecutionsPaginator = client.get_paginator("list_closed_workflow_executions")
         list_domains_paginator: ListDomainsPaginator = client.get_paginator("list_domains")
         list_open_workflow_executions_paginator: ListOpenWorkflowExecutionsPaginator = client.get_paginator("list_open_workflow_executions")
         list_workflow_types_paginator: ListWorkflowTypesPaginator = client.get_paginator("list_workflow_types")
         poll_for_decision_task_paginator: PollForDecisionTaskPaginator = client.get_paginator("poll_for_decision_task")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import RegistrationStatusType
 from .type_defs import (
     ActivityTypeInfosTypeDef,
@@ -52,76 +51,76 @@
     WorkflowExecutionFilterTypeDef,
     WorkflowExecutionInfosTypeDef,
     WorkflowExecutionTypeDef,
     WorkflowTypeFilterTypeDef,
     WorkflowTypeInfosTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetWorkflowExecutionHistoryPaginator",
     "ListActivityTypesPaginator",
     "ListClosedWorkflowExecutionsPaginator",
     "ListDomainsPaginator",
     "ListOpenWorkflowExecutionsPaginator",
     "ListWorkflowTypesPaginator",
     "PollForDecisionTaskPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class GetWorkflowExecutionHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.GetWorkflowExecutionHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#getworkflowexecutionhistorypaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         execution: WorkflowExecutionTypeDef,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[HistoryTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.GetWorkflowExecutionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#getworkflowexecutionhistorypaginator)
         """
 
+
 class ListActivityTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListActivityTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listactivitytypespaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         registrationStatus: RegistrationStatusType,
         name: str = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ActivityTypeInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListActivityTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listactivitytypespaginator)
         """
 
+
 class ListClosedWorkflowExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListClosedWorkflowExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listclosedworkflowexecutionspaginator)
     """
 
     def paginate(
@@ -131,39 +130,41 @@
         startTimeFilter: ExecutionTimeFilterTypeDef = ...,
         closeTimeFilter: ExecutionTimeFilterTypeDef = ...,
         executionFilter: WorkflowExecutionFilterTypeDef = ...,
         closeStatusFilter: CloseStatusFilterTypeDef = ...,
         typeFilter: WorkflowTypeFilterTypeDef = ...,
         tagFilter: TagFilterTypeDef = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[WorkflowExecutionInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListClosedWorkflowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listclosedworkflowexecutionspaginator)
         """
 
+
 class ListDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listdomainspaginator)
     """
 
     def paginate(
         self,
         *,
         registrationStatus: RegistrationStatusType,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DomainInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listdomainspaginator)
         """
 
+
 class ListOpenWorkflowExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListOpenWorkflowExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listopenworkflowexecutionspaginator)
     """
 
     def paginate(
@@ -171,53 +172,56 @@
         *,
         domain: str,
         startTimeFilter: ExecutionTimeFilterTypeDef,
         typeFilter: WorkflowTypeFilterTypeDef = ...,
         tagFilter: TagFilterTypeDef = ...,
         reverseOrder: bool = ...,
         executionFilter: WorkflowExecutionFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[WorkflowExecutionInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListOpenWorkflowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listopenworkflowexecutionspaginator)
         """
 
+
 class ListWorkflowTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListWorkflowTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listworkflowtypespaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         registrationStatus: RegistrationStatusType,
         name: str = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[WorkflowTypeInfosTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.ListWorkflowTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#listworkflowtypespaginator)
         """
 
+
 class PollForDecisionTaskPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.PollForDecisionTask)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#pollfordecisiontaskpaginator)
     """
 
     def paginate(
         self,
         *,
         domain: str,
         taskList: TaskListTypeDef,
         identity: str = ...,
         reverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        startAtPreviousStartedEvent: bool = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DecisionTaskTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF.Paginator.PollForDecisionTask.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/paginators/#pollfordecisiontaskpaginator)
         """
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/type_defs.py` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -52,15 +52,15 @@
     "ActivityTaskCancelRequestedEventAttributesTypeDef",
     "ActivityTaskCanceledEventAttributesTypeDef",
     "ActivityTaskCompletedEventAttributesTypeDef",
     "ActivityTaskFailedEventAttributesTypeDef",
     "ActivityTypeTypeDef",
     "TaskListTypeDef",
     "ActivityTaskStartedEventAttributesTypeDef",
-    "ResponseMetadataTypeDef",
+    "ActivityTaskStatusTypeDef",
     "ActivityTaskTimedOutEventAttributesTypeDef",
     "WorkflowExecutionTypeDef",
     "CancelTimerDecisionAttributesTypeDef",
     "CancelTimerFailedEventAttributesTypeDef",
     "CancelWorkflowExecutionDecisionAttributesTypeDef",
     "CancelWorkflowExecutionFailedEventAttributesTypeDef",
     "WorkflowTypeTypeDef",
@@ -82,16 +82,16 @@
     "ScheduleLambdaFunctionDecisionAttributesTypeDef",
     "SignalExternalWorkflowExecutionDecisionAttributesTypeDef",
     "StartTimerDecisionAttributesTypeDef",
     "DeprecateDomainInputRequestTypeDef",
     "DescribeDomainInputRequestTypeDef",
     "DomainConfigurationTypeDef",
     "DomainInfoTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FailWorkflowExecutionFailedEventAttributesTypeDef",
-    "PaginatorConfigTypeDef",
     "LambdaFunctionCompletedEventAttributesTypeDef",
     "LambdaFunctionFailedEventAttributesTypeDef",
     "LambdaFunctionScheduledEventAttributesTypeDef",
     "LambdaFunctionStartedEventAttributesTypeDef",
     "LambdaFunctionTimedOutEventAttributesTypeDef",
     "MarkerRecordedEventAttributesTypeDef",
     "RecordMarkerFailedEventAttributesTypeDef",
@@ -107,56 +107,61 @@
     "TimerFiredEventAttributesTypeDef",
     "TimerStartedEventAttributesTypeDef",
     "WorkflowExecutionCanceledEventAttributesTypeDef",
     "WorkflowExecutionCompletedEventAttributesTypeDef",
     "WorkflowExecutionFailedEventAttributesTypeDef",
     "WorkflowExecutionTerminatedEventAttributesTypeDef",
     "WorkflowExecutionTimedOutEventAttributesTypeDef",
+    "ListActivityTypesInputListActivityTypesPaginateTypeDef",
     "ListActivityTypesInputRequestTypeDef",
+    "ListDomainsInputListDomainsPaginateTypeDef",
     "ListDomainsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "ResourceTagTypeDef",
+    "ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
     "ListWorkflowTypesInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "PendingTaskCountTypeDef",
     "RecordActivityTaskHeartbeatInputRequestTypeDef",
     "RequestCancelWorkflowExecutionInputRequestTypeDef",
     "RespondActivityTaskCanceledInputRequestTypeDef",
     "RespondActivityTaskCompletedInputRequestTypeDef",
     "RespondActivityTaskFailedInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "RunTypeDef",
     "SignalWorkflowExecutionInputRequestTypeDef",
     "TerminateWorkflowExecutionInputRequestTypeDef",
     "UndeprecateDomainInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "WorkflowExecutionCountTypeDef",
     "WorkflowExecutionOpenCountsTypeDef",
     "ActivityTypeInfoTypeDef",
     "DeprecateActivityTypeInputRequestTypeDef",
     "DescribeActivityTypeInputRequestTypeDef",
     "ScheduleActivityTaskFailedEventAttributesTypeDef",
     "UndeprecateActivityTypeInputRequestTypeDef",
     "ActivityTaskScheduledEventAttributesTypeDef",
     "ActivityTypeConfigurationTypeDef",
     "ContinueAsNewWorkflowExecutionDecisionAttributesTypeDef",
     "CountPendingActivityTasksInputRequestTypeDef",
     "CountPendingDecisionTasksInputRequestTypeDef",
     "DecisionTaskScheduledEventAttributesTypeDef",
     "PollForActivityTaskInputRequestTypeDef",
+    "PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
     "PollForDecisionTaskInputRequestTypeDef",
     "RegisterActivityTypeInputRequestTypeDef",
     "RegisterWorkflowTypeInputRequestTypeDef",
     "ScheduleActivityTaskDecisionAttributesTypeDef",
     "WorkflowExecutionConfigurationTypeDef",
     "WorkflowTypeConfigurationTypeDef",
-    "ActivityTaskStatusTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "PendingTaskCountTypeDef",
-    "RunTypeDef",
-    "WorkflowExecutionCountTypeDef",
     "ActivityTaskTypeDef",
     "DescribeWorkflowExecutionInputRequestTypeDef",
     "ExternalWorkflowExecutionCancelRequestedEventAttributesTypeDef",
     "ExternalWorkflowExecutionSignaledEventAttributesTypeDef",
+    "GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
     "GetWorkflowExecutionHistoryInputRequestTypeDef",
     "WorkflowExecutionCancelRequestedEventAttributesTypeDef",
     "WorkflowExecutionSignaledEventAttributesTypeDef",
     "ChildWorkflowExecutionCanceledEventAttributesTypeDef",
     "ChildWorkflowExecutionCompletedEventAttributesTypeDef",
     "ChildWorkflowExecutionFailedEventAttributesTypeDef",
     "ChildWorkflowExecutionStartedEventAttributesTypeDef",
@@ -171,25 +176,20 @@
     "UndeprecateWorkflowTypeInputRequestTypeDef",
     "WorkflowExecutionContinuedAsNewEventAttributesTypeDef",
     "WorkflowExecutionInfoTypeDef",
     "WorkflowExecutionStartedEventAttributesTypeDef",
     "WorkflowTypeInfoTypeDef",
     "CountClosedWorkflowExecutionsInputRequestTypeDef",
     "CountOpenWorkflowExecutionsInputRequestTypeDef",
+    "ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef",
     "ListClosedWorkflowExecutionsInputRequestTypeDef",
+    "ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
     "ListOpenWorkflowExecutionsInputRequestTypeDef",
     "DomainDetailTypeDef",
     "DomainInfosTypeDef",
-    "GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
-    "ListActivityTypesInputListActivityTypesPaginateTypeDef",
-    "ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef",
-    "ListDomainsInputListDomainsPaginateTypeDef",
-    "ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
-    "ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
-    "PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "RegisterDomainInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "ActivityTypeInfosTypeDef",
     "ActivityTypeDetailTypeDef",
     "DecisionTypeDef",
     "WorkflowExecutionDetailTypeDef",
@@ -314,22 +314,19 @@
 class ActivityTaskStartedEventAttributesTypeDef(
     _RequiredActivityTaskStartedEventAttributesTypeDef,
     _OptionalActivityTaskStartedEventAttributesTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ActivityTaskStatusTypeDef = TypedDict(
+    "ActivityTaskStatusTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "cancelRequested": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActivityTaskTimedOutEventAttributesTypeDef = TypedDict(
     "_RequiredActivityTaskTimedOutEventAttributesTypeDef",
     {
         "timeoutType": ActivityTaskTimeoutTypeType,
@@ -712,30 +709,27 @@
 )
 
 
 class DomainInfoTypeDef(_RequiredDomainInfoTypeDef, _OptionalDomainInfoTypeDef):
     pass
 
 
-FailWorkflowExecutionFailedEventAttributesTypeDef = TypedDict(
-    "FailWorkflowExecutionFailedEventAttributesTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "cause": FailWorkflowExecutionFailedCauseType,
-        "decisionTaskCompletedEventId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+FailWorkflowExecutionFailedEventAttributesTypeDef = TypedDict(
+    "FailWorkflowExecutionFailedEventAttributesTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "cause": FailWorkflowExecutionFailedCauseType,
+        "decisionTaskCompletedEventId": int,
     },
-    total=False,
 )
 
 _RequiredLambdaFunctionCompletedEventAttributesTypeDef = TypedDict(
     "_RequiredLambdaFunctionCompletedEventAttributesTypeDef",
     {
         "scheduledEventId": int,
         "startedEventId": int,
@@ -1143,14 +1137,39 @@
     "WorkflowExecutionTimedOutEventAttributesTypeDef",
     {
         "timeoutType": Literal["START_TO_CLOSE"],
         "childPolicy": ChildPolicyType,
     },
 )
 
+_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
+    "_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef",
+    {
+        "domain": str,
+        "registrationStatus": RegistrationStatusType,
+    },
+)
+_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
+    "_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef",
+    {
+        "name": str,
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListActivityTypesInputListActivityTypesPaginateTypeDef(
+    _RequiredListActivityTypesInputListActivityTypesPaginateTypeDef,
+    _OptionalListActivityTypesInputListActivityTypesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListActivityTypesInputRequestTypeDef = TypedDict(
     "_RequiredListActivityTypesInputRequestTypeDef",
     {
         "domain": str,
         "registrationStatus": RegistrationStatusType,
     },
 )
@@ -1168,14 +1187,37 @@
 
 class ListActivityTypesInputRequestTypeDef(
     _RequiredListActivityTypesInputRequestTypeDef, _OptionalListActivityTypesInputRequestTypeDef
 ):
     pass
 
 
+_RequiredListDomainsInputListDomainsPaginateTypeDef = TypedDict(
+    "_RequiredListDomainsInputListDomainsPaginateTypeDef",
+    {
+        "registrationStatus": RegistrationStatusType,
+    },
+)
+_OptionalListDomainsInputListDomainsPaginateTypeDef = TypedDict(
+    "_OptionalListDomainsInputListDomainsPaginateTypeDef",
+    {
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDomainsInputListDomainsPaginateTypeDef(
+    _RequiredListDomainsInputListDomainsPaginateTypeDef,
+    _OptionalListDomainsInputListDomainsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDomainsInputRequestTypeDef = TypedDict(
     "_RequiredListDomainsInputRequestTypeDef",
     {
         "registrationStatus": RegistrationStatusType,
     },
 )
 _OptionalListDomainsInputRequestTypeDef = TypedDict(
@@ -1217,14 +1259,39 @@
 )
 
 
 class ResourceTagTypeDef(_RequiredResourceTagTypeDef, _OptionalResourceTagTypeDef):
     pass
 
 
+_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
+    "_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+    {
+        "domain": str,
+        "registrationStatus": RegistrationStatusType,
+    },
+)
+_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
+    "_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+    {
+        "name": str,
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef(
+    _RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
+    _OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListWorkflowTypesInputRequestTypeDef = TypedDict(
     "_RequiredListWorkflowTypesInputRequestTypeDef",
     {
         "domain": str,
         "registrationStatus": RegistrationStatusType,
     },
 )
@@ -1242,14 +1309,33 @@
 
 class ListWorkflowTypesInputRequestTypeDef(
     _RequiredListWorkflowTypesInputRequestTypeDef, _OptionalListWorkflowTypesInputRequestTypeDef
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
+PendingTaskCountTypeDef = TypedDict(
+    "PendingTaskCountTypeDef",
+    {
+        "count": int,
+        "truncated": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRecordActivityTaskHeartbeatInputRequestTypeDef = TypedDict(
     "_RequiredRecordActivityTaskHeartbeatInputRequestTypeDef",
     {
         "taskToken": str,
     },
 )
 _OptionalRecordActivityTaskHeartbeatInputRequestTypeDef = TypedDict(
@@ -1354,14 +1440,33 @@
 class RespondActivityTaskFailedInputRequestTypeDef(
     _RequiredRespondActivityTaskFailedInputRequestTypeDef,
     _OptionalRespondActivityTaskFailedInputRequestTypeDef,
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
+
+RunTypeDef = TypedDict(
+    "RunTypeDef",
+    {
+        "runId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSignalWorkflowExecutionInputRequestTypeDef = TypedDict(
     "_RequiredSignalWorkflowExecutionInputRequestTypeDef",
     {
         "domain": str,
         "workflowId": str,
         "signalName": str,
     },
@@ -1420,14 +1525,23 @@
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+WorkflowExecutionCountTypeDef = TypedDict(
+    "WorkflowExecutionCountTypeDef",
+    {
+        "count": int,
+        "truncated": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredWorkflowExecutionOpenCountsTypeDef = TypedDict(
     "_RequiredWorkflowExecutionOpenCountsTypeDef",
     {
         "openActivityTasks": int,
         "openDecisionTasks": int,
         "openTimers": int,
         "openChildWorkflowExecutions": int,
@@ -1621,28 +1735,55 @@
 
 class PollForActivityTaskInputRequestTypeDef(
     _RequiredPollForActivityTaskInputRequestTypeDef, _OptionalPollForActivityTaskInputRequestTypeDef
 ):
     pass
 
 
+_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
+    "_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+    {
+        "domain": str,
+        "taskList": TaskListTypeDef,
+    },
+)
+_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
+    "_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+    {
+        "identity": str,
+        "reverseOrder": bool,
+        "startAtPreviousStartedEvent": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef(
+    _RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
+    _OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
+):
+    pass
+
+
 _RequiredPollForDecisionTaskInputRequestTypeDef = TypedDict(
     "_RequiredPollForDecisionTaskInputRequestTypeDef",
     {
         "domain": str,
         "taskList": TaskListTypeDef,
     },
 )
 _OptionalPollForDecisionTaskInputRequestTypeDef = TypedDict(
     "_OptionalPollForDecisionTaskInputRequestTypeDef",
     {
         "identity": str,
         "nextPageToken": str,
         "maximumPageSize": int,
         "reverseOrder": bool,
+        "startAtPreviousStartedEvent": bool,
     },
     total=False,
 )
 
 
 class PollForDecisionTaskInputRequestTypeDef(
     _RequiredPollForDecisionTaskInputRequestTypeDef, _OptionalPollForDecisionTaskInputRequestTypeDef
@@ -1774,65 +1915,24 @@
         "defaultTaskPriority": str,
         "defaultChildPolicy": ChildPolicyType,
         "defaultLambdaRole": str,
     },
     total=False,
 )
 
-ActivityTaskStatusTypeDef = TypedDict(
-    "ActivityTaskStatusTypeDef",
-    {
-        "cancelRequested": bool,
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
-PendingTaskCountTypeDef = TypedDict(
-    "PendingTaskCountTypeDef",
-    {
-        "count": int,
-        "truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RunTypeDef = TypedDict(
-    "RunTypeDef",
-    {
-        "runId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-WorkflowExecutionCountTypeDef = TypedDict(
-    "WorkflowExecutionCountTypeDef",
-    {
-        "count": int,
-        "truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ActivityTaskTypeDef = TypedDict(
     "ActivityTaskTypeDef",
     {
         "taskToken": str,
         "activityId": str,
         "startedEventId": int,
         "workflowExecution": WorkflowExecutionTypeDef,
         "activityType": ActivityTypeTypeDef,
         "input": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorkflowExecutionInputRequestTypeDef = TypedDict(
     "DescribeWorkflowExecutionInputRequestTypeDef",
     {
         "domain": str,
@@ -1852,14 +1952,38 @@
     "ExternalWorkflowExecutionSignaledEventAttributesTypeDef",
     {
         "workflowExecution": WorkflowExecutionTypeDef,
         "initiatedEventId": int,
     },
 )
 
+_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
+    {
+        "domain": str,
+        "execution": WorkflowExecutionTypeDef,
+    },
+)
+_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
+    {
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef(
+    _RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
+    _OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetWorkflowExecutionHistoryInputRequestTypeDef = TypedDict(
     "_RequiredGetWorkflowExecutionHistoryInputRequestTypeDef",
     {
         "domain": str,
         "execution": WorkflowExecutionTypeDef,
     },
 )
@@ -2326,139 +2450,14 @@
 class CountOpenWorkflowExecutionsInputRequestTypeDef(
     _RequiredCountOpenWorkflowExecutionsInputRequestTypeDef,
     _OptionalCountOpenWorkflowExecutionsInputRequestTypeDef,
 ):
     pass
 
 
-_RequiredListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_RequiredListClosedWorkflowExecutionsInputRequestTypeDef",
-    {
-        "domain": str,
-    },
-)
-_OptionalListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_OptionalListClosedWorkflowExecutionsInputRequestTypeDef",
-    {
-        "startTimeFilter": ExecutionTimeFilterTypeDef,
-        "closeTimeFilter": ExecutionTimeFilterTypeDef,
-        "executionFilter": WorkflowExecutionFilterTypeDef,
-        "closeStatusFilter": CloseStatusFilterTypeDef,
-        "typeFilter": WorkflowTypeFilterTypeDef,
-        "tagFilter": TagFilterTypeDef,
-        "nextPageToken": str,
-        "maximumPageSize": int,
-        "reverseOrder": bool,
-    },
-    total=False,
-)
-
-
-class ListClosedWorkflowExecutionsInputRequestTypeDef(
-    _RequiredListClosedWorkflowExecutionsInputRequestTypeDef,
-    _OptionalListClosedWorkflowExecutionsInputRequestTypeDef,
-):
-    pass
-
-
-_RequiredListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_RequiredListOpenWorkflowExecutionsInputRequestTypeDef",
-    {
-        "domain": str,
-        "startTimeFilter": ExecutionTimeFilterTypeDef,
-    },
-)
-_OptionalListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_OptionalListOpenWorkflowExecutionsInputRequestTypeDef",
-    {
-        "typeFilter": WorkflowTypeFilterTypeDef,
-        "tagFilter": TagFilterTypeDef,
-        "nextPageToken": str,
-        "maximumPageSize": int,
-        "reverseOrder": bool,
-        "executionFilter": WorkflowExecutionFilterTypeDef,
-    },
-    total=False,
-)
-
-
-class ListOpenWorkflowExecutionsInputRequestTypeDef(
-    _RequiredListOpenWorkflowExecutionsInputRequestTypeDef,
-    _OptionalListOpenWorkflowExecutionsInputRequestTypeDef,
-):
-    pass
-
-
-DomainDetailTypeDef = TypedDict(
-    "DomainDetailTypeDef",
-    {
-        "domainInfo": DomainInfoTypeDef,
-        "configuration": DomainConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DomainInfosTypeDef = TypedDict(
-    "DomainInfosTypeDef",
-    {
-        "domainInfos": List[DomainInfoTypeDef],
-        "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
-    {
-        "domain": str,
-        "execution": WorkflowExecutionTypeDef,
-    },
-)
-_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
-    {
-        "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef(
-    _RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-    _OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
-    "_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef",
-    {
-        "domain": str,
-        "registrationStatus": RegistrationStatusType,
-    },
-)
-_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
-    "_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef",
-    {
-        "name": str,
-        "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListActivityTypesInputListActivityTypesPaginateTypeDef(
-    _RequiredListActivityTypesInputListActivityTypesPaginateTypeDef,
-    _OptionalListActivityTypesInputListActivityTypesPaginateTypeDef,
-):
-    pass
-
-
 _RequiredListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef = TypedDict(
     "_RequiredListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef",
     {
         "domain": str,
     },
 )
 _OptionalListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef = TypedDict(
@@ -2467,46 +2466,53 @@
         "startTimeFilter": ExecutionTimeFilterTypeDef,
         "closeTimeFilter": ExecutionTimeFilterTypeDef,
         "executionFilter": WorkflowExecutionFilterTypeDef,
         "closeStatusFilter": CloseStatusFilterTypeDef,
         "typeFilter": WorkflowTypeFilterTypeDef,
         "tagFilter": TagFilterTypeDef,
         "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef(
     _RequiredListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
     _OptionalListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListDomainsInputListDomainsPaginateTypeDef = TypedDict(
-    "_RequiredListDomainsInputListDomainsPaginateTypeDef",
+_RequiredListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_RequiredListClosedWorkflowExecutionsInputRequestTypeDef",
     {
-        "registrationStatus": RegistrationStatusType,
+        "domain": str,
     },
 )
-_OptionalListDomainsInputListDomainsPaginateTypeDef = TypedDict(
-    "_OptionalListDomainsInputListDomainsPaginateTypeDef",
+_OptionalListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_OptionalListClosedWorkflowExecutionsInputRequestTypeDef",
     {
+        "startTimeFilter": ExecutionTimeFilterTypeDef,
+        "closeTimeFilter": ExecutionTimeFilterTypeDef,
+        "executionFilter": WorkflowExecutionFilterTypeDef,
+        "closeStatusFilter": CloseStatusFilterTypeDef,
+        "typeFilter": WorkflowTypeFilterTypeDef,
+        "tagFilter": TagFilterTypeDef,
+        "nextPageToken": str,
+        "maximumPageSize": int,
         "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
 
-class ListDomainsInputListDomainsPaginateTypeDef(
-    _RequiredListDomainsInputListDomainsPaginateTypeDef,
-    _OptionalListDomainsInputListDomainsPaginateTypeDef,
+class ListClosedWorkflowExecutionsInputRequestTypeDef(
+    _RequiredListClosedWorkflowExecutionsInputRequestTypeDef,
+    _OptionalListClosedWorkflowExecutionsInputRequestTypeDef,
 ):
     pass
 
 
 _RequiredListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef = TypedDict(
     "_RequiredListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
     {
@@ -2517,82 +2523,78 @@
 _OptionalListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef = TypedDict(
     "_OptionalListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
     {
         "typeFilter": WorkflowTypeFilterTypeDef,
         "tagFilter": TagFilterTypeDef,
         "reverseOrder": bool,
         "executionFilter": WorkflowExecutionFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef(
     _RequiredListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
     _OptionalListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
 ):
     pass
 
 
-_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
-    "_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+_RequiredListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_RequiredListOpenWorkflowExecutionsInputRequestTypeDef",
     {
         "domain": str,
-        "registrationStatus": RegistrationStatusType,
+        "startTimeFilter": ExecutionTimeFilterTypeDef,
     },
 )
-_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
-    "_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+_OptionalListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_OptionalListOpenWorkflowExecutionsInputRequestTypeDef",
     {
-        "name": str,
+        "typeFilter": WorkflowTypeFilterTypeDef,
+        "tagFilter": TagFilterTypeDef,
+        "nextPageToken": str,
+        "maximumPageSize": int,
         "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "executionFilter": WorkflowExecutionFilterTypeDef,
     },
     total=False,
 )
 
 
-class ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef(
-    _RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
-    _OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
+class ListOpenWorkflowExecutionsInputRequestTypeDef(
+    _RequiredListOpenWorkflowExecutionsInputRequestTypeDef,
+    _OptionalListOpenWorkflowExecutionsInputRequestTypeDef,
 ):
     pass
 
 
-_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
-    "_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+DomainDetailTypeDef = TypedDict(
+    "DomainDetailTypeDef",
     {
-        "domain": str,
-        "taskList": TaskListTypeDef,
+        "domainInfo": DomainInfoTypeDef,
+        "configuration": DomainConfigurationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
-    "_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+
+DomainInfosTypeDef = TypedDict(
+    "DomainInfosTypeDef",
     {
-        "identity": str,
-        "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "domainInfos": List[DomainInfoTypeDef],
+        "nextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef(
-    _RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
-    _OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
-):
-    pass
-
-
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "tags": List[ResourceTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterDomainInputRequestTypeDef = TypedDict(
     "_RequiredRegisterDomainInputRequestTypeDef",
     {
         "name": str,
@@ -2624,24 +2626,24 @@
 )
 
 ActivityTypeInfosTypeDef = TypedDict(
     "ActivityTypeInfosTypeDef",
     {
         "typeInfos": List[ActivityTypeInfoTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivityTypeDetailTypeDef = TypedDict(
     "ActivityTypeDetailTypeDef",
     {
         "typeInfo": ActivityTypeInfoTypeDef,
         "configuration": ActivityTypeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDecisionTypeDef = TypedDict(
     "_RequiredDecisionTypeDef",
     {
         "decisionType": DecisionTypeType,
@@ -2690,24 +2692,24 @@
     "WorkflowExecutionDetailTypeDef",
     {
         "executionInfo": WorkflowExecutionInfoTypeDef,
         "executionConfiguration": WorkflowExecutionConfigurationTypeDef,
         "openCounts": WorkflowExecutionOpenCountsTypeDef,
         "latestActivityTaskTimestamp": datetime,
         "latestExecutionContext": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkflowExecutionInfosTypeDef = TypedDict(
     "WorkflowExecutionInfosTypeDef",
     {
         "executionInfos": List[WorkflowExecutionInfoTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHistoryEventTypeDef = TypedDict(
     "_RequiredHistoryEventTypeDef",
     {
         "eventTimestamp": datetime,
@@ -2834,24 +2836,24 @@
 
 
 WorkflowTypeDetailTypeDef = TypedDict(
     "WorkflowTypeDetailTypeDef",
     {
         "typeInfo": WorkflowTypeInfoTypeDef,
         "configuration": WorkflowTypeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkflowTypeInfosTypeDef = TypedDict(
     "WorkflowTypeInfosTypeDef",
     {
         "typeInfos": List[WorkflowTypeInfoTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRespondDecisionTaskCompletedInputRequestTypeDef = TypedDict(
     "_RequiredRespondDecisionTaskCompletedInputRequestTypeDef",
     {
         "taskToken": str,
@@ -2880,19 +2882,19 @@
         "taskToken": str,
         "startedEventId": int,
         "workflowExecution": WorkflowExecutionTypeDef,
         "workflowType": WorkflowTypeTypeDef,
         "events": List[HistoryEventTypeDef],
         "nextPageToken": str,
         "previousStartedEventId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HistoryTypeDef = TypedDict(
     "HistoryTypeDef",
     {
         "events": List[HistoryEventTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf/type_defs.pyi` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -51,15 +51,15 @@
     "ActivityTaskCancelRequestedEventAttributesTypeDef",
     "ActivityTaskCanceledEventAttributesTypeDef",
     "ActivityTaskCompletedEventAttributesTypeDef",
     "ActivityTaskFailedEventAttributesTypeDef",
     "ActivityTypeTypeDef",
     "TaskListTypeDef",
     "ActivityTaskStartedEventAttributesTypeDef",
-    "ResponseMetadataTypeDef",
+    "ActivityTaskStatusTypeDef",
     "ActivityTaskTimedOutEventAttributesTypeDef",
     "WorkflowExecutionTypeDef",
     "CancelTimerDecisionAttributesTypeDef",
     "CancelTimerFailedEventAttributesTypeDef",
     "CancelWorkflowExecutionDecisionAttributesTypeDef",
     "CancelWorkflowExecutionFailedEventAttributesTypeDef",
     "WorkflowTypeTypeDef",
@@ -81,16 +81,16 @@
     "ScheduleLambdaFunctionDecisionAttributesTypeDef",
     "SignalExternalWorkflowExecutionDecisionAttributesTypeDef",
     "StartTimerDecisionAttributesTypeDef",
     "DeprecateDomainInputRequestTypeDef",
     "DescribeDomainInputRequestTypeDef",
     "DomainConfigurationTypeDef",
     "DomainInfoTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FailWorkflowExecutionFailedEventAttributesTypeDef",
-    "PaginatorConfigTypeDef",
     "LambdaFunctionCompletedEventAttributesTypeDef",
     "LambdaFunctionFailedEventAttributesTypeDef",
     "LambdaFunctionScheduledEventAttributesTypeDef",
     "LambdaFunctionStartedEventAttributesTypeDef",
     "LambdaFunctionTimedOutEventAttributesTypeDef",
     "MarkerRecordedEventAttributesTypeDef",
     "RecordMarkerFailedEventAttributesTypeDef",
@@ -106,56 +106,61 @@
     "TimerFiredEventAttributesTypeDef",
     "TimerStartedEventAttributesTypeDef",
     "WorkflowExecutionCanceledEventAttributesTypeDef",
     "WorkflowExecutionCompletedEventAttributesTypeDef",
     "WorkflowExecutionFailedEventAttributesTypeDef",
     "WorkflowExecutionTerminatedEventAttributesTypeDef",
     "WorkflowExecutionTimedOutEventAttributesTypeDef",
+    "ListActivityTypesInputListActivityTypesPaginateTypeDef",
     "ListActivityTypesInputRequestTypeDef",
+    "ListDomainsInputListDomainsPaginateTypeDef",
     "ListDomainsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "ResourceTagTypeDef",
+    "ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
     "ListWorkflowTypesInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "PendingTaskCountTypeDef",
     "RecordActivityTaskHeartbeatInputRequestTypeDef",
     "RequestCancelWorkflowExecutionInputRequestTypeDef",
     "RespondActivityTaskCanceledInputRequestTypeDef",
     "RespondActivityTaskCompletedInputRequestTypeDef",
     "RespondActivityTaskFailedInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "RunTypeDef",
     "SignalWorkflowExecutionInputRequestTypeDef",
     "TerminateWorkflowExecutionInputRequestTypeDef",
     "UndeprecateDomainInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "WorkflowExecutionCountTypeDef",
     "WorkflowExecutionOpenCountsTypeDef",
     "ActivityTypeInfoTypeDef",
     "DeprecateActivityTypeInputRequestTypeDef",
     "DescribeActivityTypeInputRequestTypeDef",
     "ScheduleActivityTaskFailedEventAttributesTypeDef",
     "UndeprecateActivityTypeInputRequestTypeDef",
     "ActivityTaskScheduledEventAttributesTypeDef",
     "ActivityTypeConfigurationTypeDef",
     "ContinueAsNewWorkflowExecutionDecisionAttributesTypeDef",
     "CountPendingActivityTasksInputRequestTypeDef",
     "CountPendingDecisionTasksInputRequestTypeDef",
     "DecisionTaskScheduledEventAttributesTypeDef",
     "PollForActivityTaskInputRequestTypeDef",
+    "PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
     "PollForDecisionTaskInputRequestTypeDef",
     "RegisterActivityTypeInputRequestTypeDef",
     "RegisterWorkflowTypeInputRequestTypeDef",
     "ScheduleActivityTaskDecisionAttributesTypeDef",
     "WorkflowExecutionConfigurationTypeDef",
     "WorkflowTypeConfigurationTypeDef",
-    "ActivityTaskStatusTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "PendingTaskCountTypeDef",
-    "RunTypeDef",
-    "WorkflowExecutionCountTypeDef",
     "ActivityTaskTypeDef",
     "DescribeWorkflowExecutionInputRequestTypeDef",
     "ExternalWorkflowExecutionCancelRequestedEventAttributesTypeDef",
     "ExternalWorkflowExecutionSignaledEventAttributesTypeDef",
+    "GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
     "GetWorkflowExecutionHistoryInputRequestTypeDef",
     "WorkflowExecutionCancelRequestedEventAttributesTypeDef",
     "WorkflowExecutionSignaledEventAttributesTypeDef",
     "ChildWorkflowExecutionCanceledEventAttributesTypeDef",
     "ChildWorkflowExecutionCompletedEventAttributesTypeDef",
     "ChildWorkflowExecutionFailedEventAttributesTypeDef",
     "ChildWorkflowExecutionStartedEventAttributesTypeDef",
@@ -170,25 +175,20 @@
     "UndeprecateWorkflowTypeInputRequestTypeDef",
     "WorkflowExecutionContinuedAsNewEventAttributesTypeDef",
     "WorkflowExecutionInfoTypeDef",
     "WorkflowExecutionStartedEventAttributesTypeDef",
     "WorkflowTypeInfoTypeDef",
     "CountClosedWorkflowExecutionsInputRequestTypeDef",
     "CountOpenWorkflowExecutionsInputRequestTypeDef",
+    "ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef",
     "ListClosedWorkflowExecutionsInputRequestTypeDef",
+    "ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
     "ListOpenWorkflowExecutionsInputRequestTypeDef",
     "DomainDetailTypeDef",
     "DomainInfosTypeDef",
-    "GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
-    "ListActivityTypesInputListActivityTypesPaginateTypeDef",
-    "ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef",
-    "ListDomainsInputListDomainsPaginateTypeDef",
-    "ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
-    "ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
-    "PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "RegisterDomainInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "ActivityTypeInfosTypeDef",
     "ActivityTypeDetailTypeDef",
     "DecisionTypeDef",
     "WorkflowExecutionDetailTypeDef",
@@ -305,22 +305,19 @@
 
 class ActivityTaskStartedEventAttributesTypeDef(
     _RequiredActivityTaskStartedEventAttributesTypeDef,
     _OptionalActivityTaskStartedEventAttributesTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ActivityTaskStatusTypeDef = TypedDict(
+    "ActivityTaskStatusTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "cancelRequested": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActivityTaskTimedOutEventAttributesTypeDef = TypedDict(
     "_RequiredActivityTaskTimedOutEventAttributesTypeDef",
     {
         "timeoutType": ActivityTaskTimeoutTypeType,
@@ -681,30 +678,27 @@
     },
     total=False,
 )
 
 class DomainInfoTypeDef(_RequiredDomainInfoTypeDef, _OptionalDomainInfoTypeDef):
     pass
 
-FailWorkflowExecutionFailedEventAttributesTypeDef = TypedDict(
-    "FailWorkflowExecutionFailedEventAttributesTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "cause": FailWorkflowExecutionFailedCauseType,
-        "decisionTaskCompletedEventId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+FailWorkflowExecutionFailedEventAttributesTypeDef = TypedDict(
+    "FailWorkflowExecutionFailedEventAttributesTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "cause": FailWorkflowExecutionFailedCauseType,
+        "decisionTaskCompletedEventId": int,
     },
-    total=False,
 )
 
 _RequiredLambdaFunctionCompletedEventAttributesTypeDef = TypedDict(
     "_RequiredLambdaFunctionCompletedEventAttributesTypeDef",
     {
         "scheduledEventId": int,
         "startedEventId": int,
@@ -1084,14 +1078,37 @@
     "WorkflowExecutionTimedOutEventAttributesTypeDef",
     {
         "timeoutType": Literal["START_TO_CLOSE"],
         "childPolicy": ChildPolicyType,
     },
 )
 
+_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
+    "_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef",
+    {
+        "domain": str,
+        "registrationStatus": RegistrationStatusType,
+    },
+)
+_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
+    "_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef",
+    {
+        "name": str,
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListActivityTypesInputListActivityTypesPaginateTypeDef(
+    _RequiredListActivityTypesInputListActivityTypesPaginateTypeDef,
+    _OptionalListActivityTypesInputListActivityTypesPaginateTypeDef,
+):
+    pass
+
 _RequiredListActivityTypesInputRequestTypeDef = TypedDict(
     "_RequiredListActivityTypesInputRequestTypeDef",
     {
         "domain": str,
         "registrationStatus": RegistrationStatusType,
     },
 )
@@ -1107,14 +1124,35 @@
 )
 
 class ListActivityTypesInputRequestTypeDef(
     _RequiredListActivityTypesInputRequestTypeDef, _OptionalListActivityTypesInputRequestTypeDef
 ):
     pass
 
+_RequiredListDomainsInputListDomainsPaginateTypeDef = TypedDict(
+    "_RequiredListDomainsInputListDomainsPaginateTypeDef",
+    {
+        "registrationStatus": RegistrationStatusType,
+    },
+)
+_OptionalListDomainsInputListDomainsPaginateTypeDef = TypedDict(
+    "_OptionalListDomainsInputListDomainsPaginateTypeDef",
+    {
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDomainsInputListDomainsPaginateTypeDef(
+    _RequiredListDomainsInputListDomainsPaginateTypeDef,
+    _OptionalListDomainsInputListDomainsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDomainsInputRequestTypeDef = TypedDict(
     "_RequiredListDomainsInputRequestTypeDef",
     {
         "registrationStatus": RegistrationStatusType,
     },
 )
 _OptionalListDomainsInputRequestTypeDef = TypedDict(
@@ -1152,14 +1190,37 @@
     },
     total=False,
 )
 
 class ResourceTagTypeDef(_RequiredResourceTagTypeDef, _OptionalResourceTagTypeDef):
     pass
 
+_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
+    "_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+    {
+        "domain": str,
+        "registrationStatus": RegistrationStatusType,
+    },
+)
+_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
+    "_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+    {
+        "name": str,
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef(
+    _RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
+    _OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
+):
+    pass
+
 _RequiredListWorkflowTypesInputRequestTypeDef = TypedDict(
     "_RequiredListWorkflowTypesInputRequestTypeDef",
     {
         "domain": str,
         "registrationStatus": RegistrationStatusType,
     },
 )
@@ -1175,14 +1236,33 @@
 )
 
 class ListWorkflowTypesInputRequestTypeDef(
     _RequiredListWorkflowTypesInputRequestTypeDef, _OptionalListWorkflowTypesInputRequestTypeDef
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
+PendingTaskCountTypeDef = TypedDict(
+    "PendingTaskCountTypeDef",
+    {
+        "count": int,
+        "truncated": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRecordActivityTaskHeartbeatInputRequestTypeDef = TypedDict(
     "_RequiredRecordActivityTaskHeartbeatInputRequestTypeDef",
     {
         "taskToken": str,
     },
 )
 _OptionalRecordActivityTaskHeartbeatInputRequestTypeDef = TypedDict(
@@ -1277,14 +1357,33 @@
 
 class RespondActivityTaskFailedInputRequestTypeDef(
     _RequiredRespondActivityTaskFailedInputRequestTypeDef,
     _OptionalRespondActivityTaskFailedInputRequestTypeDef,
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
+
+RunTypeDef = TypedDict(
+    "RunTypeDef",
+    {
+        "runId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSignalWorkflowExecutionInputRequestTypeDef = TypedDict(
     "_RequiredSignalWorkflowExecutionInputRequestTypeDef",
     {
         "domain": str,
         "workflowId": str,
         "signalName": str,
     },
@@ -1339,14 +1438,23 @@
     "UntagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+WorkflowExecutionCountTypeDef = TypedDict(
+    "WorkflowExecutionCountTypeDef",
+    {
+        "count": int,
+        "truncated": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredWorkflowExecutionOpenCountsTypeDef = TypedDict(
     "_RequiredWorkflowExecutionOpenCountsTypeDef",
     {
         "openActivityTasks": int,
         "openDecisionTasks": int,
         "openTimers": int,
         "openChildWorkflowExecutions": int,
@@ -1530,28 +1638,53 @@
 )
 
 class PollForActivityTaskInputRequestTypeDef(
     _RequiredPollForActivityTaskInputRequestTypeDef, _OptionalPollForActivityTaskInputRequestTypeDef
 ):
     pass
 
+_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
+    "_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+    {
+        "domain": str,
+        "taskList": TaskListTypeDef,
+    },
+)
+_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
+    "_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+    {
+        "identity": str,
+        "reverseOrder": bool,
+        "startAtPreviousStartedEvent": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef(
+    _RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
+    _OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
+):
+    pass
+
 _RequiredPollForDecisionTaskInputRequestTypeDef = TypedDict(
     "_RequiredPollForDecisionTaskInputRequestTypeDef",
     {
         "domain": str,
         "taskList": TaskListTypeDef,
     },
 )
 _OptionalPollForDecisionTaskInputRequestTypeDef = TypedDict(
     "_OptionalPollForDecisionTaskInputRequestTypeDef",
     {
         "identity": str,
         "nextPageToken": str,
         "maximumPageSize": int,
         "reverseOrder": bool,
+        "startAtPreviousStartedEvent": bool,
     },
     total=False,
 )
 
 class PollForDecisionTaskInputRequestTypeDef(
     _RequiredPollForDecisionTaskInputRequestTypeDef, _OptionalPollForDecisionTaskInputRequestTypeDef
 ):
@@ -1673,65 +1806,24 @@
         "defaultTaskPriority": str,
         "defaultChildPolicy": ChildPolicyType,
         "defaultLambdaRole": str,
     },
     total=False,
 )
 
-ActivityTaskStatusTypeDef = TypedDict(
-    "ActivityTaskStatusTypeDef",
-    {
-        "cancelRequested": bool,
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
-PendingTaskCountTypeDef = TypedDict(
-    "PendingTaskCountTypeDef",
-    {
-        "count": int,
-        "truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RunTypeDef = TypedDict(
-    "RunTypeDef",
-    {
-        "runId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-WorkflowExecutionCountTypeDef = TypedDict(
-    "WorkflowExecutionCountTypeDef",
-    {
-        "count": int,
-        "truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ActivityTaskTypeDef = TypedDict(
     "ActivityTaskTypeDef",
     {
         "taskToken": str,
         "activityId": str,
         "startedEventId": int,
         "workflowExecution": WorkflowExecutionTypeDef,
         "activityType": ActivityTypeTypeDef,
         "input": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorkflowExecutionInputRequestTypeDef = TypedDict(
     "DescribeWorkflowExecutionInputRequestTypeDef",
     {
         "domain": str,
@@ -1751,14 +1843,36 @@
     "ExternalWorkflowExecutionSignaledEventAttributesTypeDef",
     {
         "workflowExecution": WorkflowExecutionTypeDef,
         "initiatedEventId": int,
     },
 )
 
+_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
+    {
+        "domain": str,
+        "execution": WorkflowExecutionTypeDef,
+    },
+)
+_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
+    {
+        "reverseOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef(
+    _RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
+    _OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetWorkflowExecutionHistoryInputRequestTypeDef = TypedDict(
     "_RequiredGetWorkflowExecutionHistoryInputRequestTypeDef",
     {
         "domain": str,
         "execution": WorkflowExecutionTypeDef,
     },
 )
@@ -2195,131 +2309,14 @@
 
 class CountOpenWorkflowExecutionsInputRequestTypeDef(
     _RequiredCountOpenWorkflowExecutionsInputRequestTypeDef,
     _OptionalCountOpenWorkflowExecutionsInputRequestTypeDef,
 ):
     pass
 
-_RequiredListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_RequiredListClosedWorkflowExecutionsInputRequestTypeDef",
-    {
-        "domain": str,
-    },
-)
-_OptionalListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_OptionalListClosedWorkflowExecutionsInputRequestTypeDef",
-    {
-        "startTimeFilter": ExecutionTimeFilterTypeDef,
-        "closeTimeFilter": ExecutionTimeFilterTypeDef,
-        "executionFilter": WorkflowExecutionFilterTypeDef,
-        "closeStatusFilter": CloseStatusFilterTypeDef,
-        "typeFilter": WorkflowTypeFilterTypeDef,
-        "tagFilter": TagFilterTypeDef,
-        "nextPageToken": str,
-        "maximumPageSize": int,
-        "reverseOrder": bool,
-    },
-    total=False,
-)
-
-class ListClosedWorkflowExecutionsInputRequestTypeDef(
-    _RequiredListClosedWorkflowExecutionsInputRequestTypeDef,
-    _OptionalListClosedWorkflowExecutionsInputRequestTypeDef,
-):
-    pass
-
-_RequiredListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_RequiredListOpenWorkflowExecutionsInputRequestTypeDef",
-    {
-        "domain": str,
-        "startTimeFilter": ExecutionTimeFilterTypeDef,
-    },
-)
-_OptionalListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
-    "_OptionalListOpenWorkflowExecutionsInputRequestTypeDef",
-    {
-        "typeFilter": WorkflowTypeFilterTypeDef,
-        "tagFilter": TagFilterTypeDef,
-        "nextPageToken": str,
-        "maximumPageSize": int,
-        "reverseOrder": bool,
-        "executionFilter": WorkflowExecutionFilterTypeDef,
-    },
-    total=False,
-)
-
-class ListOpenWorkflowExecutionsInputRequestTypeDef(
-    _RequiredListOpenWorkflowExecutionsInputRequestTypeDef,
-    _OptionalListOpenWorkflowExecutionsInputRequestTypeDef,
-):
-    pass
-
-DomainDetailTypeDef = TypedDict(
-    "DomainDetailTypeDef",
-    {
-        "domainInfo": DomainInfoTypeDef,
-        "configuration": DomainConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DomainInfosTypeDef = TypedDict(
-    "DomainInfosTypeDef",
-    {
-        "domainInfos": List[DomainInfoTypeDef],
-        "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
-    {
-        "domain": str,
-        "execution": WorkflowExecutionTypeDef,
-    },
-)
-_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef",
-    {
-        "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef(
-    _RequiredGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-    _OptionalGetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-):
-    pass
-
-_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
-    "_RequiredListActivityTypesInputListActivityTypesPaginateTypeDef",
-    {
-        "domain": str,
-        "registrationStatus": RegistrationStatusType,
-    },
-)
-_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef = TypedDict(
-    "_OptionalListActivityTypesInputListActivityTypesPaginateTypeDef",
-    {
-        "name": str,
-        "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListActivityTypesInputListActivityTypesPaginateTypeDef(
-    _RequiredListActivityTypesInputListActivityTypesPaginateTypeDef,
-    _OptionalListActivityTypesInputListActivityTypesPaginateTypeDef,
-):
-    pass
-
 _RequiredListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef = TypedDict(
     "_RequiredListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef",
     {
         "domain": str,
     },
 )
 _OptionalListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef = TypedDict(
@@ -2328,43 +2325,50 @@
         "startTimeFilter": ExecutionTimeFilterTypeDef,
         "closeTimeFilter": ExecutionTimeFilterTypeDef,
         "executionFilter": WorkflowExecutionFilterTypeDef,
         "closeStatusFilter": CloseStatusFilterTypeDef,
         "typeFilter": WorkflowTypeFilterTypeDef,
         "tagFilter": TagFilterTypeDef,
         "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef(
     _RequiredListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
     _OptionalListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
 ):
     pass
 
-_RequiredListDomainsInputListDomainsPaginateTypeDef = TypedDict(
-    "_RequiredListDomainsInputListDomainsPaginateTypeDef",
+_RequiredListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_RequiredListClosedWorkflowExecutionsInputRequestTypeDef",
     {
-        "registrationStatus": RegistrationStatusType,
+        "domain": str,
     },
 )
-_OptionalListDomainsInputListDomainsPaginateTypeDef = TypedDict(
-    "_OptionalListDomainsInputListDomainsPaginateTypeDef",
+_OptionalListClosedWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_OptionalListClosedWorkflowExecutionsInputRequestTypeDef",
     {
+        "startTimeFilter": ExecutionTimeFilterTypeDef,
+        "closeTimeFilter": ExecutionTimeFilterTypeDef,
+        "executionFilter": WorkflowExecutionFilterTypeDef,
+        "closeStatusFilter": CloseStatusFilterTypeDef,
+        "typeFilter": WorkflowTypeFilterTypeDef,
+        "tagFilter": TagFilterTypeDef,
+        "nextPageToken": str,
+        "maximumPageSize": int,
         "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-class ListDomainsInputListDomainsPaginateTypeDef(
-    _RequiredListDomainsInputListDomainsPaginateTypeDef,
-    _OptionalListDomainsInputListDomainsPaginateTypeDef,
+class ListClosedWorkflowExecutionsInputRequestTypeDef(
+    _RequiredListClosedWorkflowExecutionsInputRequestTypeDef,
+    _OptionalListClosedWorkflowExecutionsInputRequestTypeDef,
 ):
     pass
 
 _RequiredListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef = TypedDict(
     "_RequiredListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
     {
         "domain": str,
@@ -2374,76 +2378,74 @@
 _OptionalListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef = TypedDict(
     "_OptionalListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef",
     {
         "typeFilter": WorkflowTypeFilterTypeDef,
         "tagFilter": TagFilterTypeDef,
         "reverseOrder": bool,
         "executionFilter": WorkflowExecutionFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef(
     _RequiredListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
     _OptionalListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
 ):
     pass
 
-_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
-    "_RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+_RequiredListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_RequiredListOpenWorkflowExecutionsInputRequestTypeDef",
     {
         "domain": str,
-        "registrationStatus": RegistrationStatusType,
+        "startTimeFilter": ExecutionTimeFilterTypeDef,
     },
 )
-_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef = TypedDict(
-    "_OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef",
+_OptionalListOpenWorkflowExecutionsInputRequestTypeDef = TypedDict(
+    "_OptionalListOpenWorkflowExecutionsInputRequestTypeDef",
     {
-        "name": str,
+        "typeFilter": WorkflowTypeFilterTypeDef,
+        "tagFilter": TagFilterTypeDef,
+        "nextPageToken": str,
+        "maximumPageSize": int,
         "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "executionFilter": WorkflowExecutionFilterTypeDef,
     },
     total=False,
 )
 
-class ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef(
-    _RequiredListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
-    _OptionalListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
+class ListOpenWorkflowExecutionsInputRequestTypeDef(
+    _RequiredListOpenWorkflowExecutionsInputRequestTypeDef,
+    _OptionalListOpenWorkflowExecutionsInputRequestTypeDef,
 ):
     pass
 
-_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
-    "_RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+DomainDetailTypeDef = TypedDict(
+    "DomainDetailTypeDef",
     {
-        "domain": str,
-        "taskList": TaskListTypeDef,
+        "domainInfo": DomainInfoTypeDef,
+        "configuration": DomainConfigurationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef = TypedDict(
-    "_OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef",
+
+DomainInfosTypeDef = TypedDict(
+    "DomainInfosTypeDef",
     {
-        "identity": str,
-        "reverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "domainInfos": List[DomainInfoTypeDef],
+        "nextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef(
-    _RequiredPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
-    _OptionalPollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
-):
-    pass
-
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "tags": List[ResourceTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterDomainInputRequestTypeDef = TypedDict(
     "_RequiredRegisterDomainInputRequestTypeDef",
     {
         "name": str,
@@ -2473,24 +2475,24 @@
 )
 
 ActivityTypeInfosTypeDef = TypedDict(
     "ActivityTypeInfosTypeDef",
     {
         "typeInfos": List[ActivityTypeInfoTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivityTypeDetailTypeDef = TypedDict(
     "ActivityTypeDetailTypeDef",
     {
         "typeInfo": ActivityTypeInfoTypeDef,
         "configuration": ActivityTypeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDecisionTypeDef = TypedDict(
     "_RequiredDecisionTypeDef",
     {
         "decisionType": DecisionTypeType,
@@ -2537,24 +2539,24 @@
     "WorkflowExecutionDetailTypeDef",
     {
         "executionInfo": WorkflowExecutionInfoTypeDef,
         "executionConfiguration": WorkflowExecutionConfigurationTypeDef,
         "openCounts": WorkflowExecutionOpenCountsTypeDef,
         "latestActivityTaskTimestamp": datetime,
         "latestExecutionContext": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkflowExecutionInfosTypeDef = TypedDict(
     "WorkflowExecutionInfosTypeDef",
     {
         "executionInfos": List[WorkflowExecutionInfoTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHistoryEventTypeDef = TypedDict(
     "_RequiredHistoryEventTypeDef",
     {
         "eventTimestamp": datetime,
@@ -2679,24 +2681,24 @@
     pass
 
 WorkflowTypeDetailTypeDef = TypedDict(
     "WorkflowTypeDetailTypeDef",
     {
         "typeInfo": WorkflowTypeInfoTypeDef,
         "configuration": WorkflowTypeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkflowTypeInfosTypeDef = TypedDict(
     "WorkflowTypeInfosTypeDef",
     {
         "typeInfos": List[WorkflowTypeInfoTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRespondDecisionTaskCompletedInputRequestTypeDef = TypedDict(
     "_RequiredRespondDecisionTaskCompletedInputRequestTypeDef",
     {
         "taskToken": str,
@@ -2723,19 +2725,19 @@
         "taskToken": str,
         "startedEventId": int,
         "workflowExecution": WorkflowExecutionTypeDef,
         "workflowType": WorkflowTypeTypeDef,
         "events": List[HistoryEventTypeDef],
         "nextPageToken": str,
         "previousStartedEventId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HistoryTypeDef = TypedDict(
     "HistoryTypeDef",
     {
         "events": List[HistoryEventTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/PKG-INFO` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-swf
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SWF 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SWF 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-swf"></a>
 
 # types-aiobotocore-swf
 
 [![PyPI - types-aiobotocore-swf](https://img.shields.io/pypi/v/types-aiobotocore-swf.svg?color=blue)](https://pypi.org/project/types-aiobotocore-swf)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-swf.svg?color=blue)](https://pypi.org/project/types-aiobotocore-swf)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-swf?color=blue)](https://pypistats.org/packages/types-aiobotocore-swf)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SWF 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
+[aiobotocore.SWF 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/swf.html#SWF)
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
 [types-aiobotocore-swf docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_swf/).
 
 See how it helps to find and fix potential bugs:
 
@@ -377,15 +377,15 @@
     ActivityTaskCancelRequestedEventAttributesTypeDef,
     ActivityTaskCanceledEventAttributesTypeDef,
     ActivityTaskCompletedEventAttributesTypeDef,
     ActivityTaskFailedEventAttributesTypeDef,
     ActivityTypeTypeDef,
     TaskListTypeDef,
     ActivityTaskStartedEventAttributesTypeDef,
-    ResponseMetadataTypeDef,
+    ActivityTaskStatusTypeDef,
     ActivityTaskTimedOutEventAttributesTypeDef,
     WorkflowExecutionTypeDef,
     CancelTimerDecisionAttributesTypeDef,
     CancelTimerFailedEventAttributesTypeDef,
     CancelWorkflowExecutionDecisionAttributesTypeDef,
     CancelWorkflowExecutionFailedEventAttributesTypeDef,
     WorkflowTypeTypeDef,
@@ -407,16 +407,16 @@
     ScheduleLambdaFunctionDecisionAttributesTypeDef,
     SignalExternalWorkflowExecutionDecisionAttributesTypeDef,
     StartTimerDecisionAttributesTypeDef,
     DeprecateDomainInputRequestTypeDef,
     DescribeDomainInputRequestTypeDef,
     DomainConfigurationTypeDef,
     DomainInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     FailWorkflowExecutionFailedEventAttributesTypeDef,
-    PaginatorConfigTypeDef,
     LambdaFunctionCompletedEventAttributesTypeDef,
     LambdaFunctionFailedEventAttributesTypeDef,
     LambdaFunctionScheduledEventAttributesTypeDef,
     LambdaFunctionStartedEventAttributesTypeDef,
     LambdaFunctionTimedOutEventAttributesTypeDef,
     MarkerRecordedEventAttributesTypeDef,
     RecordMarkerFailedEventAttributesTypeDef,
@@ -432,56 +432,61 @@
     TimerFiredEventAttributesTypeDef,
     TimerStartedEventAttributesTypeDef,
     WorkflowExecutionCanceledEventAttributesTypeDef,
     WorkflowExecutionCompletedEventAttributesTypeDef,
     WorkflowExecutionFailedEventAttributesTypeDef,
     WorkflowExecutionTerminatedEventAttributesTypeDef,
     WorkflowExecutionTimedOutEventAttributesTypeDef,
+    ListActivityTypesInputListActivityTypesPaginateTypeDef,
     ListActivityTypesInputRequestTypeDef,
+    ListDomainsInputListDomainsPaginateTypeDef,
     ListDomainsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     ResourceTagTypeDef,
+    ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
     ListWorkflowTypesInputRequestTypeDef,
+    PaginatorConfigTypeDef,
+    PendingTaskCountTypeDef,
     RecordActivityTaskHeartbeatInputRequestTypeDef,
     RequestCancelWorkflowExecutionInputRequestTypeDef,
     RespondActivityTaskCanceledInputRequestTypeDef,
     RespondActivityTaskCompletedInputRequestTypeDef,
     RespondActivityTaskFailedInputRequestTypeDef,
+    ResponseMetadataTypeDef,
+    RunTypeDef,
     SignalWorkflowExecutionInputRequestTypeDef,
     TerminateWorkflowExecutionInputRequestTypeDef,
     UndeprecateDomainInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    WorkflowExecutionCountTypeDef,
     WorkflowExecutionOpenCountsTypeDef,
     ActivityTypeInfoTypeDef,
     DeprecateActivityTypeInputRequestTypeDef,
     DescribeActivityTypeInputRequestTypeDef,
     ScheduleActivityTaskFailedEventAttributesTypeDef,
     UndeprecateActivityTypeInputRequestTypeDef,
     ActivityTaskScheduledEventAttributesTypeDef,
     ActivityTypeConfigurationTypeDef,
     ContinueAsNewWorkflowExecutionDecisionAttributesTypeDef,
     CountPendingActivityTasksInputRequestTypeDef,
     CountPendingDecisionTasksInputRequestTypeDef,
     DecisionTaskScheduledEventAttributesTypeDef,
     PollForActivityTaskInputRequestTypeDef,
+    PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
     PollForDecisionTaskInputRequestTypeDef,
     RegisterActivityTypeInputRequestTypeDef,
     RegisterWorkflowTypeInputRequestTypeDef,
     ScheduleActivityTaskDecisionAttributesTypeDef,
     WorkflowExecutionConfigurationTypeDef,
     WorkflowTypeConfigurationTypeDef,
-    ActivityTaskStatusTypeDef,
-    EmptyResponseMetadataTypeDef,
-    PendingTaskCountTypeDef,
-    RunTypeDef,
-    WorkflowExecutionCountTypeDef,
     ActivityTaskTypeDef,
     DescribeWorkflowExecutionInputRequestTypeDef,
     ExternalWorkflowExecutionCancelRequestedEventAttributesTypeDef,
     ExternalWorkflowExecutionSignaledEventAttributesTypeDef,
+    GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
     GetWorkflowExecutionHistoryInputRequestTypeDef,
     WorkflowExecutionCancelRequestedEventAttributesTypeDef,
     WorkflowExecutionSignaledEventAttributesTypeDef,
     ChildWorkflowExecutionCanceledEventAttributesTypeDef,
     ChildWorkflowExecutionCompletedEventAttributesTypeDef,
     ChildWorkflowExecutionFailedEventAttributesTypeDef,
     ChildWorkflowExecutionStartedEventAttributesTypeDef,
@@ -496,25 +501,20 @@
     UndeprecateWorkflowTypeInputRequestTypeDef,
     WorkflowExecutionContinuedAsNewEventAttributesTypeDef,
     WorkflowExecutionInfoTypeDef,
     WorkflowExecutionStartedEventAttributesTypeDef,
     WorkflowTypeInfoTypeDef,
     CountClosedWorkflowExecutionsInputRequestTypeDef,
     CountOpenWorkflowExecutionsInputRequestTypeDef,
+    ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
     ListClosedWorkflowExecutionsInputRequestTypeDef,
+    ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
     ListOpenWorkflowExecutionsInputRequestTypeDef,
     DomainDetailTypeDef,
     DomainInfosTypeDef,
-    GetWorkflowExecutionHistoryInputGetWorkflowExecutionHistoryPaginateTypeDef,
-    ListActivityTypesInputListActivityTypesPaginateTypeDef,
-    ListClosedWorkflowExecutionsInputListClosedWorkflowExecutionsPaginateTypeDef,
-    ListDomainsInputListDomainsPaginateTypeDef,
-    ListOpenWorkflowExecutionsInputListOpenWorkflowExecutionsPaginateTypeDef,
-    ListWorkflowTypesInputListWorkflowTypesPaginateTypeDef,
-    PollForDecisionTaskInputPollForDecisionTaskPaginateTypeDef,
     ListTagsForResourceOutputTypeDef,
     RegisterDomainInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     ActivityTypeInfosTypeDef,
     ActivityTypeDetailTypeDef,
     DecisionTypeDef,
     WorkflowExecutionDetailTypeDef,
@@ -535,43 +535,43 @@
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

### Comparing `types-aiobotocore-swf-2.5.0.post1/types_aiobotocore_swf.egg-info/SOURCES.txt` & `types-aiobotocore-swf-2.5.1/types_aiobotocore_swf.egg-info/SOURCES.txt`

 * *Files identical despite different names*

