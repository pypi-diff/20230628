# Comparing `tmp/types-aiobotocore-codeguruprofiler-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codeguruprofiler-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codeguruprofiler-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-codeguruprofiler-2.5.1.tar", last modified: Wed Jun 28 01:43:16 2023, max compression
```

## Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1.tar` & `types-aiobotocore-codeguruprofiler-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:23.783063 types-aiobotocore-codeguruprofiler-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15893 2023-03-11 12:26:23.775063 types-aiobotocore-codeguruprofiler-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14286 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:23.783063 types-aiobotocore-codeguruprofiler-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:23.775063 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/
--rw-r--r--   0 runner    (1001) docker     (123)      733 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      732 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21466 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    21433 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8659 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8657 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2540 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2536 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    22281 2023-03-11 12:11:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22252 2023-03-11 12:11:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:22.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:23.775063 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15893 2023-03-11 12:26:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:23.000000 types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:16.806113 types-aiobotocore-codeguruprofiler-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15894 2023-06-28 01:43:16.806113 types-aiobotocore-codeguruprofiler-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14293 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:16.806113 types-aiobotocore-codeguruprofiler-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:16.806113 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/
+-rw-r--r--   0 runner    (1001) docker     (123)      733 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      732 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21466 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21433 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8868 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8866 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2422 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2419 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22319 2023-06-28 01:28:01.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22290 2023-06-28 01:28:00.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:59.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:16.806113 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15894 2023-06-28 01:43:16.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:16.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:16.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:16.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:16.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:16.000000 types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/LICENSE` & `types-aiobotocore-codeguruprofiler-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codeguruprofiler-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codeguruprofiler
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeGuruProfiler 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeGuruProfiler 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codeguruprofiler"></a>
 
 # types-aiobotocore-codeguruprofiler
 
 [![PyPI - types-aiobotocore-codeguruprofiler](https://img.shields.io/pypi/v/types-aiobotocore-codeguruprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguruprofiler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeguruprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguruprofiler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeguruprofiler?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeguruprofiler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeGuruProfiler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
+[aiobotocore.CodeGuruProfiler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
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
 [types-aiobotocore-codeguruprofiler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,63 +325,63 @@
 
 `types_aiobotocore_codeguruprofiler.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeguruprofiler.type_defs import (
     ChannelTypeDef,
-    ResponseMetadataTypeDef,
     AgentConfigurationTypeDef,
     AgentOrchestrationConfigTypeDef,
     AggregatedProfileTimeTypeDef,
     UserFeedbackTypeDef,
     MetricTypeDef,
     FrameMetricTypeDef,
     TimestampStructureTypeDef,
     ConfigureAgentRequestRequestTypeDef,
     DeleteProfilingGroupRequestRequestTypeDef,
     DescribeProfilingGroupRequestRequestTypeDef,
     FindingsReportSummaryTypeDef,
     GetFindingsReportAccountSummaryRequestRequestTypeDef,
     GetNotificationConfigurationRequestRequestTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetProfileRequestRequestTypeDef,
+    GetProfileResponseTypeDef,
     GetRecommendationsRequestRequestTypeDef,
     ListFindingsReportsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListProfileTimesRequestListProfileTimesPaginateTypeDef,
     ListProfileTimesRequestRequestTypeDef,
     ProfileTimeTypeDef,
     ListProfilingGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MatchTypeDef,
+    PaginatorConfigTypeDef,
     PatternTypeDef,
     PostAgentProfileRequestRequestTypeDef,
     PutPermissionRequestRequestTypeDef,
+    PutPermissionResponseTypeDef,
     RemoveNotificationChannelRequestRequestTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    RemovePermissionResponseTypeDef,
+    ResponseMetadataTypeDef,
     SubmitFeedbackRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AddNotificationChannelsRequestRequestTypeDef,
     NotificationConfigurationTypeDef,
-    GetPolicyResponseTypeDef,
-    GetProfileResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutPermissionResponseTypeDef,
-    RemovePermissionResponseTypeDef,
     ConfigureAgentResponseTypeDef,
     CreateProfilingGroupRequestRequestTypeDef,
     UpdateProfilingGroupRequestRequestTypeDef,
     ProfilingStatusTypeDef,
     AnomalyInstanceTypeDef,
     BatchGetFrameMetricDataRequestRequestTypeDef,
     FrameMetricDatumTypeDef,
     GetFindingsReportAccountSummaryResponseTypeDef,
     ListFindingsReportsResponseTypeDef,
-    ListProfileTimesRequestListProfileTimesPaginateTypeDef,
     ListProfileTimesResponseTypeDef,
     RecommendationTypeDef,
     AddNotificationChannelsResponseTypeDef,
     GetNotificationConfigurationResponseTypeDef,
     RemoveNotificationChannelResponseTypeDef,
     ProfilingGroupDescriptionTypeDef,
     AnomalyTypeDef,
@@ -401,43 +401,43 @@
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/README.md` & `types-aiobotocore-codeguruprofiler-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codeguruprofiler"></a>
 
 # types-aiobotocore-codeguruprofiler
 
 [![PyPI - types-aiobotocore-codeguruprofiler](https://img.shields.io/pypi/v/types-aiobotocore-codeguruprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguruprofiler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeguruprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguruprofiler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeguruprofiler?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeguruprofiler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeGuruProfiler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
+[aiobotocore.CodeGuruProfiler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
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
 [types-aiobotocore-codeguruprofiler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,63 +292,63 @@
 
 `types_aiobotocore_codeguruprofiler.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeguruprofiler.type_defs import (
     ChannelTypeDef,
-    ResponseMetadataTypeDef,
     AgentConfigurationTypeDef,
     AgentOrchestrationConfigTypeDef,
     AggregatedProfileTimeTypeDef,
     UserFeedbackTypeDef,
     MetricTypeDef,
     FrameMetricTypeDef,
     TimestampStructureTypeDef,
     ConfigureAgentRequestRequestTypeDef,
     DeleteProfilingGroupRequestRequestTypeDef,
     DescribeProfilingGroupRequestRequestTypeDef,
     FindingsReportSummaryTypeDef,
     GetFindingsReportAccountSummaryRequestRequestTypeDef,
     GetNotificationConfigurationRequestRequestTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetProfileRequestRequestTypeDef,
+    GetProfileResponseTypeDef,
     GetRecommendationsRequestRequestTypeDef,
     ListFindingsReportsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListProfileTimesRequestListProfileTimesPaginateTypeDef,
     ListProfileTimesRequestRequestTypeDef,
     ProfileTimeTypeDef,
     ListProfilingGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MatchTypeDef,
+    PaginatorConfigTypeDef,
     PatternTypeDef,
     PostAgentProfileRequestRequestTypeDef,
     PutPermissionRequestRequestTypeDef,
+    PutPermissionResponseTypeDef,
     RemoveNotificationChannelRequestRequestTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    RemovePermissionResponseTypeDef,
+    ResponseMetadataTypeDef,
     SubmitFeedbackRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AddNotificationChannelsRequestRequestTypeDef,
     NotificationConfigurationTypeDef,
-    GetPolicyResponseTypeDef,
-    GetProfileResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutPermissionResponseTypeDef,
-    RemovePermissionResponseTypeDef,
     ConfigureAgentResponseTypeDef,
     CreateProfilingGroupRequestRequestTypeDef,
     UpdateProfilingGroupRequestRequestTypeDef,
     ProfilingStatusTypeDef,
     AnomalyInstanceTypeDef,
     BatchGetFrameMetricDataRequestRequestTypeDef,
     FrameMetricDatumTypeDef,
     GetFindingsReportAccountSummaryResponseTypeDef,
     ListFindingsReportsResponseTypeDef,
-    ListProfileTimesRequestListProfileTimesPaginateTypeDef,
     ListProfileTimesResponseTypeDef,
     RecommendationTypeDef,
     AddNotificationChannelsResponseTypeDef,
     GetNotificationConfigurationResponseTypeDef,
     RemoveNotificationChannelResponseTypeDef,
     ProfilingGroupDescriptionTypeDef,
     AnomalyTypeDef,
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/setup.py` & `types-aiobotocore-codeguruprofiler-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codeguruprofiler.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codeguruprofiler",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codeguruprofiler"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeGuruProfiler 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeGuruProfiler 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/"
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/__init__.py` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/__init__.pyi` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/__main__.py` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/__main__.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeGuruProfiler 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeGuruProfiler 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler\nOther"
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/client.py` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/client.pyi` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/literals.py` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ActionGroupType",
     "AgentParameterFieldType",
     "AggregationPeriodType",
     "ComputePlatformType",
     "EventPublisherType",
     "FeedbackTypeType",
@@ -32,15 +31,14 @@
     "OrderByType",
     "CodeGuruProfilerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 ActionGroupType = Literal["agentPermissions"]
 AgentParameterFieldType = Literal[
     "MaxStackDepth",
     "MemoryUsageLimitPercent",
     "MinimumTimeForReportingInMilliseconds",
     "ReportingIntervalInMilliseconds",
     "SamplingIntervalInMilliseconds",
@@ -122,14 +120,15 @@
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
@@ -208,14 +207,15 @@
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
@@ -226,14 +226,15 @@
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
@@ -269,14 +270,15 @@
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
@@ -295,16 +297,19 @@
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
@@ -388,15 +393,17 @@
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/literals.pyi` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ActionGroupType",
     "AgentParameterFieldType",
     "AggregationPeriodType",
     "ComputePlatformType",
     "EventPublisherType",
     "FeedbackTypeType",
@@ -31,14 +32,15 @@
     "OrderByType",
     "CodeGuruProfilerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 ActionGroupType = Literal["agentPermissions"]
 AgentParameterFieldType = Literal[
     "MaxStackDepth",
     "MemoryUsageLimitPercent",
     "MinimumTimeForReportingInMilliseconds",
     "ReportingIntervalInMilliseconds",
     "SamplingIntervalInMilliseconds",
@@ -120,14 +122,15 @@
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
@@ -206,14 +209,15 @@
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
@@ -224,14 +228,15 @@
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
@@ -267,14 +272,15 @@
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
@@ -293,16 +299,19 @@
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
@@ -386,15 +395,17 @@
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/paginator.py` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,30 +16,23 @@
     session = get_session()
     with session.create_client("codeguruprofiler") as client:
         client: CodeGuruProfilerClient
 
         list_profile_times_paginator: ListProfileTimesPaginator = client.get_paginator("list_profile_times")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AggregationPeriodType, OrderByType
 from .type_defs import ListProfileTimesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListProfileTimesPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -59,13 +52,13 @@
         self,
         *,
         endTime: Union[datetime, str],
         period: AggregationPeriodType,
         profilingGroupName: str,
         startTime: Union[datetime, str],
         orderBy: OrderByType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProfileTimesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Paginator.ListProfileTimes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/paginators/#listprofiletimespaginator)
         """
```

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/paginator.pyi` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,29 +16,23 @@
     session = get_session()
     with session.create_client("codeguruprofiler") as client:
         client: CodeGuruProfilerClient
 
         list_profile_times_paginator: ListProfileTimesPaginator = client.get_paginator("list_profile_times")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AggregationPeriodType, OrderByType
 from .type_defs import ListProfileTimesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListProfileTimesPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -55,13 +49,13 @@
         self,
         *,
         endTime: Union[datetime, str],
         period: AggregationPeriodType,
         profilingGroupName: str,
         startTime: Union[datetime, str],
         orderBy: OrderByType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProfileTimesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler.Paginator.ListProfileTimes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/paginators/#listprofiletimespaginator)
         """
```

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/type_defs.py` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -31,66 +31,65 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ChannelTypeDef",
-    "ResponseMetadataTypeDef",
     "AgentConfigurationTypeDef",
     "AgentOrchestrationConfigTypeDef",
     "AggregatedProfileTimeTypeDef",
     "UserFeedbackTypeDef",
     "MetricTypeDef",
     "FrameMetricTypeDef",
     "TimestampStructureTypeDef",
     "ConfigureAgentRequestRequestTypeDef",
     "DeleteProfilingGroupRequestRequestTypeDef",
     "DescribeProfilingGroupRequestRequestTypeDef",
     "FindingsReportSummaryTypeDef",
     "GetFindingsReportAccountSummaryRequestRequestTypeDef",
     "GetNotificationConfigurationRequestRequestTypeDef",
     "GetPolicyRequestRequestTypeDef",
+    "GetPolicyResponseTypeDef",
     "GetProfileRequestRequestTypeDef",
+    "GetProfileResponseTypeDef",
     "GetRecommendationsRequestRequestTypeDef",
     "ListFindingsReportsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListProfileTimesRequestListProfileTimesPaginateTypeDef",
     "ListProfileTimesRequestRequestTypeDef",
     "ProfileTimeTypeDef",
     "ListProfilingGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MatchTypeDef",
+    "PaginatorConfigTypeDef",
     "PatternTypeDef",
     "PostAgentProfileRequestRequestTypeDef",
     "PutPermissionRequestRequestTypeDef",
+    "PutPermissionResponseTypeDef",
     "RemoveNotificationChannelRequestRequestTypeDef",
     "RemovePermissionRequestRequestTypeDef",
+    "RemovePermissionResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SubmitFeedbackRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AddNotificationChannelsRequestRequestTypeDef",
     "NotificationConfigurationTypeDef",
-    "GetPolicyResponseTypeDef",
-    "GetProfileResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutPermissionResponseTypeDef",
-    "RemovePermissionResponseTypeDef",
     "ConfigureAgentResponseTypeDef",
     "CreateProfilingGroupRequestRequestTypeDef",
     "UpdateProfilingGroupRequestRequestTypeDef",
     "ProfilingStatusTypeDef",
     "AnomalyInstanceTypeDef",
     "BatchGetFrameMetricDataRequestRequestTypeDef",
     "FrameMetricDatumTypeDef",
     "GetFindingsReportAccountSummaryResponseTypeDef",
     "ListFindingsReportsResponseTypeDef",
-    "ListProfileTimesRequestListProfileTimesPaginateTypeDef",
     "ListProfileTimesResponseTypeDef",
     "RecommendationTypeDef",
     "AddNotificationChannelsResponseTypeDef",
     "GetNotificationConfigurationResponseTypeDef",
     "RemoveNotificationChannelResponseTypeDef",
     "ProfilingGroupDescriptionTypeDef",
     "AnomalyTypeDef",
@@ -113,30 +112,17 @@
     "_OptionalChannelTypeDef",
     {
         "id": str,
     },
     total=False,
 )
 
-
 class ChannelTypeDef(_RequiredChannelTypeDef, _OptionalChannelTypeDef):
     pass
 
-
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
 _RequiredAgentConfigurationTypeDef = TypedDict(
     "_RequiredAgentConfigurationTypeDef",
     {
         "periodInSeconds": int,
         "shouldProfile": bool,
     },
 )
@@ -144,21 +130,19 @@
     "_OptionalAgentConfigurationTypeDef",
     {
         "agentParameters": Dict[AgentParameterFieldType, str],
     },
     total=False,
 )
 
-
 class AgentConfigurationTypeDef(
     _RequiredAgentConfigurationTypeDef, _OptionalAgentConfigurationTypeDef
 ):
     pass
 
-
 AgentOrchestrationConfigTypeDef = TypedDict(
     "AgentOrchestrationConfigTypeDef",
     {
         "profilingEnabled": bool,
     },
 )
 
@@ -214,21 +198,19 @@
     {
         "fleetInstanceId": str,
         "metadata": Mapping[MetadataFieldType, str],
     },
     total=False,
 )
 
-
 class ConfigureAgentRequestRequestTypeDef(
     _RequiredConfigureAgentRequestRequestTypeDef, _OptionalConfigureAgentRequestRequestTypeDef
 ):
     pass
 
-
 DeleteProfilingGroupRequestRequestTypeDef = TypedDict(
     "DeleteProfilingGroupRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 
@@ -271,14 +253,23 @@
 GetPolicyRequestRequestTypeDef = TypedDict(
     "GetPolicyRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 
+GetPolicyResponseTypeDef = TypedDict(
+    "GetPolicyResponseTypeDef",
+    {
+        "policy": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetProfileRequestRequestTypeDef = TypedDict(
     "_RequiredGetProfileRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 _OptionalGetProfileRequestRequestTypeDef = TypedDict(
@@ -289,20 +280,28 @@
         "maxDepth": int,
         "period": str,
         "startTime": Union[datetime, str],
     },
     total=False,
 )
 
-
 class GetProfileRequestRequestTypeDef(
     _RequiredGetProfileRequestRequestTypeDef, _OptionalGetProfileRequestRequestTypeDef
 ):
     pass
 
+GetProfileResponseTypeDef = TypedDict(
+    "GetProfileResponseTypeDef",
+    {
+        "contentEncoding": str,
+        "contentType": str,
+        "profile": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetRecommendationsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "profilingGroupName": str,
         "startTime": Union[datetime, str],
@@ -312,22 +311,20 @@
     "_OptionalGetRecommendationsRequestRequestTypeDef",
     {
         "locale": str,
     },
     total=False,
 )
 
-
 class GetRecommendationsRequestRequestTypeDef(
     _RequiredGetRecommendationsRequestRequestTypeDef,
     _OptionalGetRecommendationsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListFindingsReportsRequestRequestTypeDef = TypedDict(
     "_RequiredListFindingsReportsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "profilingGroupName": str,
         "startTime": Union[datetime, str],
     },
@@ -338,32 +335,44 @@
         "dailyReportsOnly": bool,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListFindingsReportsRequestRequestTypeDef(
     _RequiredListFindingsReportsRequestRequestTypeDef,
     _OptionalListFindingsReportsRequestRequestTypeDef,
 ):
     pass
 
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
+    "_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "endTime": Union[datetime, str],
+        "period": AggregationPeriodType,
+        "profilingGroupName": str,
+        "startTime": Union[datetime, str],
+    },
+)
+_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
+    "_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef",
+    {
+        "orderBy": OrderByType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListProfileTimesRequestListProfileTimesPaginateTypeDef(
+    _RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef,
+    _OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef,
+):
+    pass
+
 _RequiredListProfileTimesRequestRequestTypeDef = TypedDict(
     "_RequiredListProfileTimesRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "period": AggregationPeriodType,
         "profilingGroupName": str,
         "startTime": Union[datetime, str],
@@ -375,21 +384,19 @@
         "maxResults": int,
         "nextToken": str,
         "orderBy": OrderByType,
     },
     total=False,
 )
 
-
 class ListProfileTimesRequestRequestTypeDef(
     _RequiredListProfileTimesRequestRequestTypeDef, _OptionalListProfileTimesRequestRequestTypeDef
 ):
     pass
 
-
 ProfileTimeTypeDef = TypedDict(
     "ProfileTimeTypeDef",
     {
         "start": datetime,
     },
     total=False,
 )
@@ -407,24 +414,42 @@
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
 MatchTypeDef = TypedDict(
     "MatchTypeDef",
     {
         "frameAddress": str,
         "targetFramesIndex": int,
         "thresholdBreachValue": float,
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
 PatternTypeDef = TypedDict(
     "PatternTypeDef",
     {
         "countersToAggregate": List[str],
         "description": str,
         "id": str,
         "name": str,
@@ -447,21 +472,19 @@
     "_OptionalPostAgentProfileRequestRequestTypeDef",
     {
         "profileToken": str,
     },
     total=False,
 )
 
-
 class PostAgentProfileRequestRequestTypeDef(
     _RequiredPostAgentProfileRequestRequestTypeDef, _OptionalPostAgentProfileRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredPutPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredPutPermissionRequestRequestTypeDef",
     {
         "actionGroup": Literal["agentPermissions"],
         "principals": Sequence[str],
         "profilingGroupName": str,
     },
@@ -470,20 +493,27 @@
     "_OptionalPutPermissionRequestRequestTypeDef",
     {
         "revisionId": str,
     },
     total=False,
 )
 
-
 class PutPermissionRequestRequestTypeDef(
     _RequiredPutPermissionRequestRequestTypeDef, _OptionalPutPermissionRequestRequestTypeDef
 ):
     pass
 
+PutPermissionResponseTypeDef = TypedDict(
+    "PutPermissionResponseTypeDef",
+    {
+        "policy": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 RemoveNotificationChannelRequestRequestTypeDef = TypedDict(
     "RemoveNotificationChannelRequestRequestTypeDef",
     {
         "channelId": str,
         "profilingGroupName": str,
     },
@@ -494,14 +524,34 @@
     {
         "actionGroup": Literal["agentPermissions"],
         "profilingGroupName": str,
         "revisionId": str,
     },
 )
 
+RemovePermissionResponseTypeDef = TypedDict(
+    "RemovePermissionResponseTypeDef",
+    {
+        "policy": str,
+        "revisionId": str,
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
 _RequiredSubmitFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredSubmitFeedbackRequestRequestTypeDef",
     {
         "anomalyInstanceId": str,
         "profilingGroupName": str,
         "type": FeedbackTypeType,
     },
@@ -510,21 +560,19 @@
     "_OptionalSubmitFeedbackRequestRequestTypeDef",
     {
         "comment": str,
     },
     total=False,
 )
 
-
 class SubmitFeedbackRequestRequestTypeDef(
     _RequiredSubmitFeedbackRequestRequestTypeDef, _OptionalSubmitFeedbackRequestRequestTypeDef
 ):
     pass
 
-
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -549,64 +597,19 @@
     "NotificationConfigurationTypeDef",
     {
         "channels": List[ChannelTypeDef],
     },
     total=False,
 )
 
-GetPolicyResponseTypeDef = TypedDict(
-    "GetPolicyResponseTypeDef",
-    {
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetProfileResponseTypeDef = TypedDict(
-    "GetProfileResponseTypeDef",
-    {
-        "contentEncoding": str,
-        "contentType": str,
-        "profile": StreamingBody,
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
-PutPermissionResponseTypeDef = TypedDict(
-    "PutPermissionResponseTypeDef",
-    {
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemovePermissionResponseTypeDef = TypedDict(
-    "RemovePermissionResponseTypeDef",
-    {
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ConfigureAgentResponseTypeDef = TypedDict(
     "ConfigureAgentResponseTypeDef",
     {
         "configuration": AgentConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProfilingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProfilingGroupRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -619,22 +622,20 @@
         "agentOrchestrationConfig": AgentOrchestrationConfigTypeDef,
         "computePlatform": ComputePlatformType,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateProfilingGroupRequestRequestTypeDef(
     _RequiredCreateProfilingGroupRequestRequestTypeDef,
     _OptionalCreateProfilingGroupRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateProfilingGroupRequestRequestTypeDef = TypedDict(
     "UpdateProfilingGroupRequestRequestTypeDef",
     {
         "agentOrchestrationConfig": AgentOrchestrationConfigTypeDef,
         "profilingGroupName": str,
     },
 )
@@ -661,19 +662,17 @@
     {
         "endTime": datetime,
         "userFeedback": UserFeedbackTypeDef,
     },
     total=False,
 )
 
-
 class AnomalyInstanceTypeDef(_RequiredAnomalyInstanceTypeDef, _OptionalAnomalyInstanceTypeDef):
     pass
 
-
 _RequiredBatchGetFrameMetricDataRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetFrameMetricDataRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 _OptionalBatchGetFrameMetricDataRequestRequestTypeDef = TypedDict(
@@ -684,80 +683,52 @@
         "period": str,
         "startTime": Union[datetime, str],
         "targetResolution": AggregationPeriodType,
     },
     total=False,
 )
 
-
 class BatchGetFrameMetricDataRequestRequestTypeDef(
     _RequiredBatchGetFrameMetricDataRequestRequestTypeDef,
     _OptionalBatchGetFrameMetricDataRequestRequestTypeDef,
 ):
     pass
 
-
 FrameMetricDatumTypeDef = TypedDict(
     "FrameMetricDatumTypeDef",
     {
         "frameMetric": FrameMetricTypeDef,
         "values": List[float],
     },
 )
 
 GetFindingsReportAccountSummaryResponseTypeDef = TypedDict(
     "GetFindingsReportAccountSummaryResponseTypeDef",
     {
         "nextToken": str,
         "reportSummaries": List[FindingsReportSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFindingsReportsResponseTypeDef = TypedDict(
     "ListFindingsReportsResponseTypeDef",
     {
         "findingsReportSummaries": List[FindingsReportSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
-    "_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef",
-    {
-        "endTime": Union[datetime, str],
-        "period": AggregationPeriodType,
-        "profilingGroupName": str,
-        "startTime": Union[datetime, str],
-    },
-)
-_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
-    "_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef",
-    {
-        "orderBy": OrderByType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProfileTimesRequestListProfileTimesPaginateTypeDef(
-    _RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef,
-    _OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef,
-):
-    pass
-
-
 ListProfileTimesResponseTypeDef = TypedDict(
     "ListProfileTimesResponseTypeDef",
     {
         "nextToken": str,
         "profileTimes": List[ProfileTimeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "allMatchesCount": int,
@@ -769,31 +740,31 @@
     },
 )
 
 AddNotificationChannelsResponseTypeDef = TypedDict(
     "AddNotificationChannelsResponseTypeDef",
     {
         "notificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNotificationConfigurationResponseTypeDef = TypedDict(
     "GetNotificationConfigurationResponseTypeDef",
     {
         "notificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveNotificationChannelResponseTypeDef = TypedDict(
     "RemoveNotificationChannelResponseTypeDef",
     {
         "notificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProfilingGroupDescriptionTypeDef = TypedDict(
     "ProfilingGroupDescriptionTypeDef",
     {
         "agentOrchestrationConfig": AgentOrchestrationConfigTypeDef,
@@ -822,56 +793,56 @@
     {
         "endTime": datetime,
         "endTimes": List[TimestampStructureTypeDef],
         "frameMetricData": List[FrameMetricDatumTypeDef],
         "resolution": AggregationPeriodType,
         "startTime": datetime,
         "unprocessedEndTimes": Dict[str, List[TimestampStructureTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProfilingGroupResponseTypeDef = TypedDict(
     "CreateProfilingGroupResponseTypeDef",
     {
         "profilingGroup": ProfilingGroupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProfilingGroupResponseTypeDef = TypedDict(
     "DescribeProfilingGroupResponseTypeDef",
     {
         "profilingGroup": ProfilingGroupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfilingGroupsResponseTypeDef = TypedDict(
     "ListProfilingGroupsResponseTypeDef",
     {
         "nextToken": str,
         "profilingGroupNames": List[str],
         "profilingGroups": List[ProfilingGroupDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProfilingGroupResponseTypeDef = TypedDict(
     "UpdateProfilingGroupResponseTypeDef",
     {
         "profilingGroup": ProfilingGroupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommendationsResponseTypeDef = TypedDict(
     "GetRecommendationsResponseTypeDef",
     {
         "anomalies": List[AnomalyTypeDef],
         "profileEndTime": datetime,
         "profileStartTime": datetime,
         "profilingGroupName": str,
         "recommendations": List[RecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler/type_defs.pyi` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler/type_defs.py`

 * *Files 11% similar despite different names*

```diff
@@ -31,65 +31,66 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ChannelTypeDef",
-    "ResponseMetadataTypeDef",
     "AgentConfigurationTypeDef",
     "AgentOrchestrationConfigTypeDef",
     "AggregatedProfileTimeTypeDef",
     "UserFeedbackTypeDef",
     "MetricTypeDef",
     "FrameMetricTypeDef",
     "TimestampStructureTypeDef",
     "ConfigureAgentRequestRequestTypeDef",
     "DeleteProfilingGroupRequestRequestTypeDef",
     "DescribeProfilingGroupRequestRequestTypeDef",
     "FindingsReportSummaryTypeDef",
     "GetFindingsReportAccountSummaryRequestRequestTypeDef",
     "GetNotificationConfigurationRequestRequestTypeDef",
     "GetPolicyRequestRequestTypeDef",
+    "GetPolicyResponseTypeDef",
     "GetProfileRequestRequestTypeDef",
+    "GetProfileResponseTypeDef",
     "GetRecommendationsRequestRequestTypeDef",
     "ListFindingsReportsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListProfileTimesRequestListProfileTimesPaginateTypeDef",
     "ListProfileTimesRequestRequestTypeDef",
     "ProfileTimeTypeDef",
     "ListProfilingGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MatchTypeDef",
+    "PaginatorConfigTypeDef",
     "PatternTypeDef",
     "PostAgentProfileRequestRequestTypeDef",
     "PutPermissionRequestRequestTypeDef",
+    "PutPermissionResponseTypeDef",
     "RemoveNotificationChannelRequestRequestTypeDef",
     "RemovePermissionRequestRequestTypeDef",
+    "RemovePermissionResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SubmitFeedbackRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AddNotificationChannelsRequestRequestTypeDef",
     "NotificationConfigurationTypeDef",
-    "GetPolicyResponseTypeDef",
-    "GetProfileResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutPermissionResponseTypeDef",
-    "RemovePermissionResponseTypeDef",
     "ConfigureAgentResponseTypeDef",
     "CreateProfilingGroupRequestRequestTypeDef",
     "UpdateProfilingGroupRequestRequestTypeDef",
     "ProfilingStatusTypeDef",
     "AnomalyInstanceTypeDef",
     "BatchGetFrameMetricDataRequestRequestTypeDef",
     "FrameMetricDatumTypeDef",
     "GetFindingsReportAccountSummaryResponseTypeDef",
     "ListFindingsReportsResponseTypeDef",
-    "ListProfileTimesRequestListProfileTimesPaginateTypeDef",
     "ListProfileTimesResponseTypeDef",
     "RecommendationTypeDef",
     "AddNotificationChannelsResponseTypeDef",
     "GetNotificationConfigurationResponseTypeDef",
     "RemoveNotificationChannelResponseTypeDef",
     "ProfilingGroupDescriptionTypeDef",
     "AnomalyTypeDef",
@@ -112,27 +113,18 @@
     "_OptionalChannelTypeDef",
     {
         "id": str,
     },
     total=False,
 )
 
+
 class ChannelTypeDef(_RequiredChannelTypeDef, _OptionalChannelTypeDef):
     pass
 
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
 
 _RequiredAgentConfigurationTypeDef = TypedDict(
     "_RequiredAgentConfigurationTypeDef",
     {
         "periodInSeconds": int,
         "shouldProfile": bool,
     },
@@ -141,19 +133,21 @@
     "_OptionalAgentConfigurationTypeDef",
     {
         "agentParameters": Dict[AgentParameterFieldType, str],
     },
     total=False,
 )
 
+
 class AgentConfigurationTypeDef(
     _RequiredAgentConfigurationTypeDef, _OptionalAgentConfigurationTypeDef
 ):
     pass
 
+
 AgentOrchestrationConfigTypeDef = TypedDict(
     "AgentOrchestrationConfigTypeDef",
     {
         "profilingEnabled": bool,
     },
 )
 
@@ -209,19 +203,21 @@
     {
         "fleetInstanceId": str,
         "metadata": Mapping[MetadataFieldType, str],
     },
     total=False,
 )
 
+
 class ConfigureAgentRequestRequestTypeDef(
     _RequiredConfigureAgentRequestRequestTypeDef, _OptionalConfigureAgentRequestRequestTypeDef
 ):
     pass
 
+
 DeleteProfilingGroupRequestRequestTypeDef = TypedDict(
     "DeleteProfilingGroupRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 
@@ -264,14 +260,23 @@
 GetPolicyRequestRequestTypeDef = TypedDict(
     "GetPolicyRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 
+GetPolicyResponseTypeDef = TypedDict(
+    "GetPolicyResponseTypeDef",
+    {
+        "policy": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetProfileRequestRequestTypeDef = TypedDict(
     "_RequiredGetProfileRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 _OptionalGetProfileRequestRequestTypeDef = TypedDict(
@@ -282,19 +287,31 @@
         "maxDepth": int,
         "period": str,
         "startTime": Union[datetime, str],
     },
     total=False,
 )
 
+
 class GetProfileRequestRequestTypeDef(
     _RequiredGetProfileRequestRequestTypeDef, _OptionalGetProfileRequestRequestTypeDef
 ):
     pass
 
+
+GetProfileResponseTypeDef = TypedDict(
+    "GetProfileResponseTypeDef",
+    {
+        "contentEncoding": str,
+        "contentType": str,
+        "profile": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetRecommendationsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "profilingGroupName": str,
         "startTime": Union[datetime, str],
     },
@@ -303,20 +320,22 @@
     "_OptionalGetRecommendationsRequestRequestTypeDef",
     {
         "locale": str,
     },
     total=False,
 )
 
+
 class GetRecommendationsRequestRequestTypeDef(
     _RequiredGetRecommendationsRequestRequestTypeDef,
     _OptionalGetRecommendationsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListFindingsReportsRequestRequestTypeDef = TypedDict(
     "_RequiredListFindingsReportsRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "profilingGroupName": str,
         "startTime": Union[datetime, str],
     },
@@ -327,30 +346,48 @@
         "dailyReportsOnly": bool,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListFindingsReportsRequestRequestTypeDef(
     _RequiredListFindingsReportsRequestRequestTypeDef,
     _OptionalListFindingsReportsRequestRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
+    "_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "endTime": Union[datetime, str],
+        "period": AggregationPeriodType,
+        "profilingGroupName": str,
+        "startTime": Union[datetime, str],
+    },
+)
+_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
+    "_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef",
+    {
+        "orderBy": OrderByType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListProfileTimesRequestListProfileTimesPaginateTypeDef(
+    _RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef,
+    _OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProfileTimesRequestRequestTypeDef = TypedDict(
     "_RequiredListProfileTimesRequestRequestTypeDef",
     {
         "endTime": Union[datetime, str],
         "period": AggregationPeriodType,
         "profilingGroupName": str,
         "startTime": Union[datetime, str],
@@ -362,19 +399,21 @@
         "maxResults": int,
         "nextToken": str,
         "orderBy": OrderByType,
     },
     total=False,
 )
 
+
 class ListProfileTimesRequestRequestTypeDef(
     _RequiredListProfileTimesRequestRequestTypeDef, _OptionalListProfileTimesRequestRequestTypeDef
 ):
     pass
 
+
 ProfileTimeTypeDef = TypedDict(
     "ProfileTimeTypeDef",
     {
         "start": datetime,
     },
     total=False,
 )
@@ -392,24 +431,42 @@
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
 MatchTypeDef = TypedDict(
     "MatchTypeDef",
     {
         "frameAddress": str,
         "targetFramesIndex": int,
         "thresholdBreachValue": float,
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
 PatternTypeDef = TypedDict(
     "PatternTypeDef",
     {
         "countersToAggregate": List[str],
         "description": str,
         "id": str,
         "name": str,
@@ -432,19 +489,21 @@
     "_OptionalPostAgentProfileRequestRequestTypeDef",
     {
         "profileToken": str,
     },
     total=False,
 )
 
+
 class PostAgentProfileRequestRequestTypeDef(
     _RequiredPostAgentProfileRequestRequestTypeDef, _OptionalPostAgentProfileRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredPutPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredPutPermissionRequestRequestTypeDef",
     {
         "actionGroup": Literal["agentPermissions"],
         "principals": Sequence[str],
         "profilingGroupName": str,
     },
@@ -453,19 +512,30 @@
     "_OptionalPutPermissionRequestRequestTypeDef",
     {
         "revisionId": str,
     },
     total=False,
 )
 
+
 class PutPermissionRequestRequestTypeDef(
     _RequiredPutPermissionRequestRequestTypeDef, _OptionalPutPermissionRequestRequestTypeDef
 ):
     pass
 
+
+PutPermissionResponseTypeDef = TypedDict(
+    "PutPermissionResponseTypeDef",
+    {
+        "policy": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveNotificationChannelRequestRequestTypeDef = TypedDict(
     "RemoveNotificationChannelRequestRequestTypeDef",
     {
         "channelId": str,
         "profilingGroupName": str,
     },
 )
@@ -475,14 +545,34 @@
     {
         "actionGroup": Literal["agentPermissions"],
         "profilingGroupName": str,
         "revisionId": str,
     },
 )
 
+RemovePermissionResponseTypeDef = TypedDict(
+    "RemovePermissionResponseTypeDef",
+    {
+        "policy": str,
+        "revisionId": str,
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
 _RequiredSubmitFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredSubmitFeedbackRequestRequestTypeDef",
     {
         "anomalyInstanceId": str,
         "profilingGroupName": str,
         "type": FeedbackTypeType,
     },
@@ -491,19 +581,21 @@
     "_OptionalSubmitFeedbackRequestRequestTypeDef",
     {
         "comment": str,
     },
     total=False,
 )
 
+
 class SubmitFeedbackRequestRequestTypeDef(
     _RequiredSubmitFeedbackRequestRequestTypeDef, _OptionalSubmitFeedbackRequestRequestTypeDef
 ):
     pass
 
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -528,64 +620,19 @@
     "NotificationConfigurationTypeDef",
     {
         "channels": List[ChannelTypeDef],
     },
     total=False,
 )
 
-GetPolicyResponseTypeDef = TypedDict(
-    "GetPolicyResponseTypeDef",
-    {
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetProfileResponseTypeDef = TypedDict(
-    "GetProfileResponseTypeDef",
-    {
-        "contentEncoding": str,
-        "contentType": str,
-        "profile": StreamingBody,
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
-PutPermissionResponseTypeDef = TypedDict(
-    "PutPermissionResponseTypeDef",
-    {
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemovePermissionResponseTypeDef = TypedDict(
-    "RemovePermissionResponseTypeDef",
-    {
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ConfigureAgentResponseTypeDef = TypedDict(
     "ConfigureAgentResponseTypeDef",
     {
         "configuration": AgentConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProfilingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProfilingGroupRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -598,20 +645,22 @@
         "agentOrchestrationConfig": AgentOrchestrationConfigTypeDef,
         "computePlatform": ComputePlatformType,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateProfilingGroupRequestRequestTypeDef(
     _RequiredCreateProfilingGroupRequestRequestTypeDef,
     _OptionalCreateProfilingGroupRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateProfilingGroupRequestRequestTypeDef = TypedDict(
     "UpdateProfilingGroupRequestRequestTypeDef",
     {
         "agentOrchestrationConfig": AgentOrchestrationConfigTypeDef,
         "profilingGroupName": str,
     },
 )
@@ -638,17 +687,19 @@
     {
         "endTime": datetime,
         "userFeedback": UserFeedbackTypeDef,
     },
     total=False,
 )
 
+
 class AnomalyInstanceTypeDef(_RequiredAnomalyInstanceTypeDef, _OptionalAnomalyInstanceTypeDef):
     pass
 
+
 _RequiredBatchGetFrameMetricDataRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetFrameMetricDataRequestRequestTypeDef",
     {
         "profilingGroupName": str,
     },
 )
 _OptionalBatchGetFrameMetricDataRequestRequestTypeDef = TypedDict(
@@ -659,76 +710,54 @@
         "period": str,
         "startTime": Union[datetime, str],
         "targetResolution": AggregationPeriodType,
     },
     total=False,
 )
 
+
 class BatchGetFrameMetricDataRequestRequestTypeDef(
     _RequiredBatchGetFrameMetricDataRequestRequestTypeDef,
     _OptionalBatchGetFrameMetricDataRequestRequestTypeDef,
 ):
     pass
 
+
 FrameMetricDatumTypeDef = TypedDict(
     "FrameMetricDatumTypeDef",
     {
         "frameMetric": FrameMetricTypeDef,
         "values": List[float],
     },
 )
 
 GetFindingsReportAccountSummaryResponseTypeDef = TypedDict(
     "GetFindingsReportAccountSummaryResponseTypeDef",
     {
         "nextToken": str,
         "reportSummaries": List[FindingsReportSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFindingsReportsResponseTypeDef = TypedDict(
     "ListFindingsReportsResponseTypeDef",
     {
         "findingsReportSummaries": List[FindingsReportSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
-    "_RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef",
-    {
-        "endTime": Union[datetime, str],
-        "period": AggregationPeriodType,
-        "profilingGroupName": str,
-        "startTime": Union[datetime, str],
-    },
-)
-_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef = TypedDict(
-    "_OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef",
-    {
-        "orderBy": OrderByType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProfileTimesRequestListProfileTimesPaginateTypeDef(
-    _RequiredListProfileTimesRequestListProfileTimesPaginateTypeDef,
-    _OptionalListProfileTimesRequestListProfileTimesPaginateTypeDef,
-):
-    pass
-
 ListProfileTimesResponseTypeDef = TypedDict(
     "ListProfileTimesResponseTypeDef",
     {
         "nextToken": str,
         "profileTimes": List[ProfileTimeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "allMatchesCount": int,
@@ -740,31 +769,31 @@
     },
 )
 
 AddNotificationChannelsResponseTypeDef = TypedDict(
     "AddNotificationChannelsResponseTypeDef",
     {
         "notificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNotificationConfigurationResponseTypeDef = TypedDict(
     "GetNotificationConfigurationResponseTypeDef",
     {
         "notificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveNotificationChannelResponseTypeDef = TypedDict(
     "RemoveNotificationChannelResponseTypeDef",
     {
         "notificationConfiguration": NotificationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProfilingGroupDescriptionTypeDef = TypedDict(
     "ProfilingGroupDescriptionTypeDef",
     {
         "agentOrchestrationConfig": AgentOrchestrationConfigTypeDef,
@@ -793,56 +822,56 @@
     {
         "endTime": datetime,
         "endTimes": List[TimestampStructureTypeDef],
         "frameMetricData": List[FrameMetricDatumTypeDef],
         "resolution": AggregationPeriodType,
         "startTime": datetime,
         "unprocessedEndTimes": Dict[str, List[TimestampStructureTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProfilingGroupResponseTypeDef = TypedDict(
     "CreateProfilingGroupResponseTypeDef",
     {
         "profilingGroup": ProfilingGroupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProfilingGroupResponseTypeDef = TypedDict(
     "DescribeProfilingGroupResponseTypeDef",
     {
         "profilingGroup": ProfilingGroupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfilingGroupsResponseTypeDef = TypedDict(
     "ListProfilingGroupsResponseTypeDef",
     {
         "nextToken": str,
         "profilingGroupNames": List[str],
         "profilingGroups": List[ProfilingGroupDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProfilingGroupResponseTypeDef = TypedDict(
     "UpdateProfilingGroupResponseTypeDef",
     {
         "profilingGroup": ProfilingGroupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommendationsResponseTypeDef = TypedDict(
     "GetRecommendationsResponseTypeDef",
     {
         "anomalies": List[AnomalyTypeDef],
         "profileEndTime": datetime,
         "profileStartTime": datetime,
         "profilingGroupName": str,
         "recommendations": List[RecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/PKG-INFO` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codeguruprofiler
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeGuruProfiler 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeGuruProfiler 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codeguruprofiler"></a>
 
 # types-aiobotocore-codeguruprofiler
 
 [![PyPI - types-aiobotocore-codeguruprofiler](https://img.shields.io/pypi/v/types-aiobotocore-codeguruprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguruprofiler)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeguruprofiler.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguruprofiler)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeguruprofiler?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeguruprofiler)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeGuruProfiler 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
+[aiobotocore.CodeGuruProfiler 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguruprofiler.html#CodeGuruProfiler)
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
 [types-aiobotocore-codeguruprofiler docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,63 +325,63 @@
 
 `types_aiobotocore_codeguruprofiler.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeguruprofiler.type_defs import (
     ChannelTypeDef,
-    ResponseMetadataTypeDef,
     AgentConfigurationTypeDef,
     AgentOrchestrationConfigTypeDef,
     AggregatedProfileTimeTypeDef,
     UserFeedbackTypeDef,
     MetricTypeDef,
     FrameMetricTypeDef,
     TimestampStructureTypeDef,
     ConfigureAgentRequestRequestTypeDef,
     DeleteProfilingGroupRequestRequestTypeDef,
     DescribeProfilingGroupRequestRequestTypeDef,
     FindingsReportSummaryTypeDef,
     GetFindingsReportAccountSummaryRequestRequestTypeDef,
     GetNotificationConfigurationRequestRequestTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetProfileRequestRequestTypeDef,
+    GetProfileResponseTypeDef,
     GetRecommendationsRequestRequestTypeDef,
     ListFindingsReportsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListProfileTimesRequestListProfileTimesPaginateTypeDef,
     ListProfileTimesRequestRequestTypeDef,
     ProfileTimeTypeDef,
     ListProfilingGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MatchTypeDef,
+    PaginatorConfigTypeDef,
     PatternTypeDef,
     PostAgentProfileRequestRequestTypeDef,
     PutPermissionRequestRequestTypeDef,
+    PutPermissionResponseTypeDef,
     RemoveNotificationChannelRequestRequestTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    RemovePermissionResponseTypeDef,
+    ResponseMetadataTypeDef,
     SubmitFeedbackRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AddNotificationChannelsRequestRequestTypeDef,
     NotificationConfigurationTypeDef,
-    GetPolicyResponseTypeDef,
-    GetProfileResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutPermissionResponseTypeDef,
-    RemovePermissionResponseTypeDef,
     ConfigureAgentResponseTypeDef,
     CreateProfilingGroupRequestRequestTypeDef,
     UpdateProfilingGroupRequestRequestTypeDef,
     ProfilingStatusTypeDef,
     AnomalyInstanceTypeDef,
     BatchGetFrameMetricDataRequestRequestTypeDef,
     FrameMetricDatumTypeDef,
     GetFindingsReportAccountSummaryResponseTypeDef,
     ListFindingsReportsResponseTypeDef,
-    ListProfileTimesRequestListProfileTimesPaginateTypeDef,
     ListProfileTimesResponseTypeDef,
     RecommendationTypeDef,
     AddNotificationChannelsResponseTypeDef,
     GetNotificationConfigurationResponseTypeDef,
     RemoveNotificationChannelResponseTypeDef,
     ProfilingGroupDescriptionTypeDef,
     AnomalyTypeDef,
@@ -401,43 +401,43 @@
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

### Comparing `types-aiobotocore-codeguruprofiler-2.5.0.post1/types_aiobotocore_codeguruprofiler.egg-info/SOURCES.txt` & `types-aiobotocore-codeguruprofiler-2.5.1/types_aiobotocore_codeguruprofiler.egg-info/SOURCES.txt`

 * *Files identical despite different names*

