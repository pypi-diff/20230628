# Comparing `tmp/types-aiobotocore-codepipeline-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codepipeline-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codepipeline-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-codepipeline-2.5.1.tar", last modified: Wed Jun 28 01:43:16 2023, max compression
```

## Comparing `types-aiobotocore-codepipeline-2.5.0.post1.tar` & `types-aiobotocore-codepipeline-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.491070 types-aiobotocore-codepipeline-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19523 2023-03-11 12:26:24.483070 types-aiobotocore-codepipeline-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17932 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.491070 types-aiobotocore-codepipeline-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.483070 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/
--rw-r--r--   0 runner    (1001) docker     (123)     1773 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1772 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    34346 2023-03-11 12:11:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    34292 2023-03-11 12:11:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10505 2023-03-11 12:11:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10503 2023-03-11 12:11:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8116 2023-03-11 12:11:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8107 2023-03-11 12:11:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    46160 2023-03-11 12:11:26.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    46099 2023-03-11 12:11:25.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:23.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.483070 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19523 2023-03-11 12:26:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:24.000000 types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:16.878113 types-aiobotocore-codepipeline-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19520 2023-06-28 01:43:16.878113 types-aiobotocore-codepipeline-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17935 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:16.878113 types-aiobotocore-codepipeline-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:16.878113 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/
+-rw-r--r--   0 runner    (1001) docker     (123)     1773 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1772 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34378 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34324 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10770 2023-06-28 01:28:02.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10768 2023-06-28 01:28:02.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8008 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8000 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    46263 2023-06-28 01:28:03.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46202 2023-06-28 01:28:02.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:01.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:16.878113 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19520 2023-06-28 01:43:16.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:16.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:16.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:16.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:16.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:16.000000 types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/LICENSE` & `types-aiobotocore-codepipeline-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codepipeline-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codepipeline
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodePipeline 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodePipeline 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codepipeline"></a>
 
 # types-aiobotocore-codepipeline
 
 [![PyPI - types-aiobotocore-codepipeline](https://img.shields.io/pypi/v/types-aiobotocore-codepipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codepipeline)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codepipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codepipeline)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codepipeline?color=blue)](https://pypistats.org/packages/types-aiobotocore-codepipeline)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodePipeline 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline)
+[aiobotocore.CodePipeline 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline)
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
 [types-aiobotocore-codepipeline docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/).
 
 See how it helps to find and fix potential bugs:
 
@@ -359,16 +359,17 @@
 `types_aiobotocore_codepipeline.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codepipeline.type_defs import (
     AWSSessionCredentialsTypeDef,
     AcknowledgeJobInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcknowledgeJobOutputTypeDef,
     AcknowledgeThirdPartyJobInputRequestTypeDef,
+    AcknowledgeThirdPartyJobOutputTypeDef,
     ActionConfigurationPropertyTypeDef,
     ActionConfigurationTypeDef,
     ActionContextTypeDef,
     ActionTypeIdTypeDef,
     InputArtifactTypeDef,
     OutputArtifactTypeDef,
     ActionExecutionFilterTypeDef,
@@ -391,58 +392,63 @@
     TagTypeDef,
     CurrentRevisionTypeDef,
     DeleteCustomActionTypeInputRequestTypeDef,
     DeletePipelineInputRequestTypeDef,
     DeleteWebhookInputRequestTypeDef,
     DeregisterWebhookWithThirdPartyInputRequestTypeDef,
     DisableStageTransitionInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableStageTransitionInputRequestTypeDef,
     ExecutionDetailsTypeDef,
     ExecutionTriggerTypeDef,
     JobWorkerExecutorConfigurationTypeDef,
     LambdaExecutorConfigurationTypeDef,
     FailureDetailsTypeDef,
     GetActionTypeInputRequestTypeDef,
     GetJobDetailsInputRequestTypeDef,
     GetPipelineExecutionInputRequestTypeDef,
     GetPipelineInputRequestTypeDef,
     PipelineMetadataTypeDef,
     GetPipelineStateInputRequestTypeDef,
     GetThirdPartyJobDetailsInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListActionTypesInputListActionTypesPaginateTypeDef,
     ListActionTypesInputRequestTypeDef,
+    ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
     ListPipelineExecutionsInputRequestTypeDef,
+    ListPipelinesInputListPipelinesPaginateTypeDef,
     ListPipelinesInputRequestTypeDef,
     PipelineSummaryTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListWebhooksInputListWebhooksPaginateTypeDef,
     ListWebhooksInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     StageContextTypeDef,
     SourceRevisionTypeDef,
     StopExecutionTriggerTypeDef,
     ThirdPartyJobTypeDef,
+    PutActionRevisionOutputTypeDef,
+    PutApprovalResultOutputTypeDef,
     RegisterWebhookWithThirdPartyInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     RetryStageExecutionInputRequestTypeDef,
+    RetryStageExecutionOutputTypeDef,
     StageExecutionTypeDef,
     TransitionStateTypeDef,
     StartPipelineExecutionInputRequestTypeDef,
+    StartPipelineExecutionOutputTypeDef,
     StopPipelineExecutionInputRequestTypeDef,
+    StopPipelineExecutionOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     WebhookAuthConfigurationTypeDef,
     WebhookFilterRuleTypeDef,
-    AcknowledgeJobOutputTypeDef,
-    AcknowledgeThirdPartyJobOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    PutActionRevisionOutputTypeDef,
-    PutApprovalResultOutputTypeDef,
-    RetryStageExecutionOutputTypeDef,
-    StartPipelineExecutionOutputTypeDef,
-    StopPipelineExecutionOutputTypeDef,
     PollForJobsInputRequestTypeDef,
     PollForThirdPartyJobsInputRequestTypeDef,
     ActionDeclarationTypeDef,
+    ListActionExecutionsInputListActionExecutionsPaginateTypeDef,
     ListActionExecutionsInputRequestTypeDef,
     ActionExecutionTypeDef,
     PutActionRevisionInputRequestTypeDef,
     ActionTypeTypeDef,
     PutApprovalResultInputRequestTypeDef,
     ArtifactDetailTypeDef,
     ArtifactLocationTypeDef,
@@ -452,20 +458,14 @@
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     PutJobSuccessResultInputRequestTypeDef,
     PutThirdPartyJobSuccessResultInputRequestTypeDef,
     ExecutorConfigurationTypeDef,
     PutJobFailureResultInputRequestTypeDef,
     PutThirdPartyJobFailureResultInputRequestTypeDef,
-    ListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-    ListActionTypesInputListActionTypesPaginateTypeDef,
-    ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
-    ListPipelinesInputListPipelinesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    ListWebhooksInputListWebhooksPaginateTypeDef,
     ListPipelinesOutputTypeDef,
     PipelineContextTypeDef,
     PipelineExecutionSummaryTypeDef,
     PollForThirdPartyJobsOutputTypeDef,
     WebhookDefinitionTypeDef,
     StageDeclarationTypeDef,
     ActionStateTypeDef,
@@ -512,43 +512,43 @@
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

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/README.md` & `types-aiobotocore-codepipeline-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codepipeline"></a>
 
 # types-aiobotocore-codepipeline
 
 [![PyPI - types-aiobotocore-codepipeline](https://img.shields.io/pypi/v/types-aiobotocore-codepipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codepipeline)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codepipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codepipeline)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codepipeline?color=blue)](https://pypistats.org/packages/types-aiobotocore-codepipeline)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodePipeline 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline)
+[aiobotocore.CodePipeline 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline)
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
 [types-aiobotocore-codepipeline docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/).
 
 See how it helps to find and fix potential bugs:
 
@@ -326,16 +326,17 @@
 `types_aiobotocore_codepipeline.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codepipeline.type_defs import (
     AWSSessionCredentialsTypeDef,
     AcknowledgeJobInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcknowledgeJobOutputTypeDef,
     AcknowledgeThirdPartyJobInputRequestTypeDef,
+    AcknowledgeThirdPartyJobOutputTypeDef,
     ActionConfigurationPropertyTypeDef,
     ActionConfigurationTypeDef,
     ActionContextTypeDef,
     ActionTypeIdTypeDef,
     InputArtifactTypeDef,
     OutputArtifactTypeDef,
     ActionExecutionFilterTypeDef,
@@ -358,58 +359,63 @@
     TagTypeDef,
     CurrentRevisionTypeDef,
     DeleteCustomActionTypeInputRequestTypeDef,
     DeletePipelineInputRequestTypeDef,
     DeleteWebhookInputRequestTypeDef,
     DeregisterWebhookWithThirdPartyInputRequestTypeDef,
     DisableStageTransitionInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableStageTransitionInputRequestTypeDef,
     ExecutionDetailsTypeDef,
     ExecutionTriggerTypeDef,
     JobWorkerExecutorConfigurationTypeDef,
     LambdaExecutorConfigurationTypeDef,
     FailureDetailsTypeDef,
     GetActionTypeInputRequestTypeDef,
     GetJobDetailsInputRequestTypeDef,
     GetPipelineExecutionInputRequestTypeDef,
     GetPipelineInputRequestTypeDef,
     PipelineMetadataTypeDef,
     GetPipelineStateInputRequestTypeDef,
     GetThirdPartyJobDetailsInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListActionTypesInputListActionTypesPaginateTypeDef,
     ListActionTypesInputRequestTypeDef,
+    ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
     ListPipelineExecutionsInputRequestTypeDef,
+    ListPipelinesInputListPipelinesPaginateTypeDef,
     ListPipelinesInputRequestTypeDef,
     PipelineSummaryTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListWebhooksInputListWebhooksPaginateTypeDef,
     ListWebhooksInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     StageContextTypeDef,
     SourceRevisionTypeDef,
     StopExecutionTriggerTypeDef,
     ThirdPartyJobTypeDef,
+    PutActionRevisionOutputTypeDef,
+    PutApprovalResultOutputTypeDef,
     RegisterWebhookWithThirdPartyInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     RetryStageExecutionInputRequestTypeDef,
+    RetryStageExecutionOutputTypeDef,
     StageExecutionTypeDef,
     TransitionStateTypeDef,
     StartPipelineExecutionInputRequestTypeDef,
+    StartPipelineExecutionOutputTypeDef,
     StopPipelineExecutionInputRequestTypeDef,
+    StopPipelineExecutionOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     WebhookAuthConfigurationTypeDef,
     WebhookFilterRuleTypeDef,
-    AcknowledgeJobOutputTypeDef,
-    AcknowledgeThirdPartyJobOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    PutActionRevisionOutputTypeDef,
-    PutApprovalResultOutputTypeDef,
-    RetryStageExecutionOutputTypeDef,
-    StartPipelineExecutionOutputTypeDef,
-    StopPipelineExecutionOutputTypeDef,
     PollForJobsInputRequestTypeDef,
     PollForThirdPartyJobsInputRequestTypeDef,
     ActionDeclarationTypeDef,
+    ListActionExecutionsInputListActionExecutionsPaginateTypeDef,
     ListActionExecutionsInputRequestTypeDef,
     ActionExecutionTypeDef,
     PutActionRevisionInputRequestTypeDef,
     ActionTypeTypeDef,
     PutApprovalResultInputRequestTypeDef,
     ArtifactDetailTypeDef,
     ArtifactLocationTypeDef,
@@ -419,20 +425,14 @@
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     PutJobSuccessResultInputRequestTypeDef,
     PutThirdPartyJobSuccessResultInputRequestTypeDef,
     ExecutorConfigurationTypeDef,
     PutJobFailureResultInputRequestTypeDef,
     PutThirdPartyJobFailureResultInputRequestTypeDef,
-    ListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-    ListActionTypesInputListActionTypesPaginateTypeDef,
-    ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
-    ListPipelinesInputListPipelinesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    ListWebhooksInputListWebhooksPaginateTypeDef,
     ListPipelinesOutputTypeDef,
     PipelineContextTypeDef,
     PipelineExecutionSummaryTypeDef,
     PollForThirdPartyJobsOutputTypeDef,
     WebhookDefinitionTypeDef,
     StageDeclarationTypeDef,
     ActionStateTypeDef,
@@ -479,43 +479,43 @@
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

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/setup.py` & `types-aiobotocore-codepipeline-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codepipeline.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codepipeline",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codepipeline"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodePipeline 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodePipeline 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/"
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

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/__init__.py` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/__init__.pyi` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/__main__.py` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodePipeline 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodePipeline 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline\nOther"
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

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/client.py` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -192,15 +192,15 @@
         outputArtifactDetails: ArtifactDetailsTypeDef,
         settings: ActionTypeSettingsTypeDef = ...,
         configurationProperties: Sequence[ActionConfigurationPropertyTypeDef] = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> CreateCustomActionTypeOutputTypeDef:
         """
         Creates a new custom action that can be used in all pipelines associated with
-        the AWS account.
+        the Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.create_custom_action_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#create_custom_action_type)
         """
 
     async def create_pipeline(
         self, *, pipeline: PipelineDeclarationTypeDef, tags: Sequence[TagTypeDef] = ...
@@ -366,16 +366,15 @@
         self,
         *,
         actionOwnerFilter: ActionOwnerType = ...,
         nextToken: str = ...,
         regionFilter: str = ...
     ) -> ListActionTypesOutputTypeDef:
         """
-        Gets a summary of all AWS CodePipeline action types associated with your
-        account.
+        Gets a summary of all CodePipeline action types associated with your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.list_action_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#list_action_types)
         """
 
     async def list_pipeline_executions(
         self, *, pipelineName: str, maxResults: int = ..., nextToken: str = ...
@@ -407,29 +406,30 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#list_tags_for_resource)
         """
 
     async def list_webhooks(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListWebhooksOutputTypeDef:
         """
-        Gets a listing of all the webhooks in this AWS Region for this account.
+        Gets a listing of all the webhooks in this Amazon Web Services Region for this
+        account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.list_webhooks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#list_webhooks)
         """
 
     async def poll_for_jobs(
         self,
         *,
         actionTypeId: ActionTypeIdTypeDef,
         maxBatchSize: int = ...,
         queryParam: Mapping[str, str] = ...
     ) -> PollForJobsOutputTypeDef:
         """
-        Returns information about any jobs for AWS CodePipeline to act on.
+        Returns information about any jobs for CodePipeline to act on.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.poll_for_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#poll_for_jobs)
         """
 
     async def poll_for_third_party_jobs(
         self, *, actionTypeId: ActionTypeIdTypeDef, maxBatchSize: int = ...
@@ -446,15 +446,15 @@
         *,
         pipelineName: str,
         stageName: str,
         actionName: str,
         actionRevision: ActionRevisionTypeDef
     ) -> PutActionRevisionOutputTypeDef:
         """
-        Provides information to AWS CodePipeline about new revisions to a source.
+        Provides information to CodePipeline about new revisions to a source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.put_action_revision)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#put_action_revision)
         """
 
     async def put_approval_result(
         self,
@@ -462,15 +462,15 @@
         pipelineName: str,
         stageName: str,
         actionName: str,
         result: ApprovalResultTypeDef,
         token: str
     ) -> PutApprovalResultOutputTypeDef:
         """
-        Provides the response to a manual approval request to AWS CodePipeline.
+        Provides the response to a manual approval request to CodePipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.put_approval_result)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#put_approval_result)
         """
 
     async def put_job_failure_result(
         self, *, jobId: str, failureDetails: FailureDetailsTypeDef
@@ -586,15 +586,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#tag_resource)
         """
 
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Removes tags from an AWS resource.
+        Removes tags from an Amazon Web Services resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#untag_resource)
         """
 
     async def update_action_type(
         self, *, actionType: ActionTypeDeclarationTypeDef
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/client.pyi` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -183,15 +183,15 @@
         outputArtifactDetails: ArtifactDetailsTypeDef,
         settings: ActionTypeSettingsTypeDef = ...,
         configurationProperties: Sequence[ActionConfigurationPropertyTypeDef] = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> CreateCustomActionTypeOutputTypeDef:
         """
         Creates a new custom action that can be used in all pipelines associated with
-        the AWS account.
+        the Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.create_custom_action_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#create_custom_action_type)
         """
     async def create_pipeline(
         self, *, pipeline: PipelineDeclarationTypeDef, tags: Sequence[TagTypeDef] = ...
     ) -> CreatePipelineOutputTypeDef:
@@ -341,16 +341,15 @@
         self,
         *,
         actionOwnerFilter: ActionOwnerType = ...,
         nextToken: str = ...,
         regionFilter: str = ...
     ) -> ListActionTypesOutputTypeDef:
         """
-        Gets a summary of all AWS CodePipeline action types associated with your
-        account.
+        Gets a summary of all CodePipeline action types associated with your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.list_action_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#list_action_types)
         """
     async def list_pipeline_executions(
         self, *, pipelineName: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListPipelineExecutionsOutputTypeDef:
@@ -378,28 +377,29 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#list_tags_for_resource)
         """
     async def list_webhooks(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListWebhooksOutputTypeDef:
         """
-        Gets a listing of all the webhooks in this AWS Region for this account.
+        Gets a listing of all the webhooks in this Amazon Web Services Region for this
+        account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.list_webhooks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#list_webhooks)
         """
     async def poll_for_jobs(
         self,
         *,
         actionTypeId: ActionTypeIdTypeDef,
         maxBatchSize: int = ...,
         queryParam: Mapping[str, str] = ...
     ) -> PollForJobsOutputTypeDef:
         """
-        Returns information about any jobs for AWS CodePipeline to act on.
+        Returns information about any jobs for CodePipeline to act on.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.poll_for_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#poll_for_jobs)
         """
     async def poll_for_third_party_jobs(
         self, *, actionTypeId: ActionTypeIdTypeDef, maxBatchSize: int = ...
     ) -> PollForThirdPartyJobsOutputTypeDef:
@@ -414,30 +414,30 @@
         *,
         pipelineName: str,
         stageName: str,
         actionName: str,
         actionRevision: ActionRevisionTypeDef
     ) -> PutActionRevisionOutputTypeDef:
         """
-        Provides information to AWS CodePipeline about new revisions to a source.
+        Provides information to CodePipeline about new revisions to a source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.put_action_revision)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#put_action_revision)
         """
     async def put_approval_result(
         self,
         *,
         pipelineName: str,
         stageName: str,
         actionName: str,
         result: ApprovalResultTypeDef,
         token: str
     ) -> PutApprovalResultOutputTypeDef:
         """
-        Provides the response to a manual approval request to AWS CodePipeline.
+        Provides the response to a manual approval request to CodePipeline.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.put_approval_result)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#put_approval_result)
         """
     async def put_job_failure_result(
         self, *, jobId: str, failureDetails: FailureDetailsTypeDef
     ) -> EmptyResponseMetadataTypeDef:
@@ -542,15 +542,15 @@
         Adds to or modifies the tags of the given resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#tag_resource)
         """
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Removes tags from an AWS resource.
+        Removes tags from an Amazon Web Services resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/client/#untag_resource)
         """
     async def update_action_type(
         self, *, actionType: ActionTypeDeclarationTypeDef
     ) -> EmptyResponseMetadataTypeDef:
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/literals.py` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/literals.py`

 * *Files 2% similar despite different names*

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
@@ -456,26 +465,29 @@
     "list_action_types",
     "list_pipeline_executions",
     "list_pipelines",
     "list_tags_for_resource",
     "list_webhooks",
 ]
 RegionName = Literal[
+    "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/literals.pyi` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -153,14 +153,15 @@
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
@@ -239,14 +240,15 @@
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
@@ -257,14 +259,15 @@
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
@@ -300,14 +303,15 @@
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
@@ -326,16 +330,19 @@
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
@@ -419,15 +426,17 @@
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
@@ -454,26 +463,29 @@
     "list_action_types",
     "list_pipeline_executions",
     "list_pipelines",
     "list_tags_for_resource",
     "list_webhooks",
 ]
 RegionName = Literal[
+    "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/paginator.py` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         list_action_types_paginator: ListActionTypesPaginator = client.get_paginator("list_action_types")
         list_pipeline_executions_paginator: ListPipelineExecutionsPaginator = client.get_paginator("list_pipeline_executions")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_webhooks_paginator: ListWebhooksPaginator = client.get_paginator("list_webhooks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ActionOwnerType
 from .type_defs import (
     ActionExecutionFilterTypeDef,
@@ -44,129 +43,115 @@
     ListPipelineExecutionsOutputTypeDef,
     ListPipelinesOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     ListWebhooksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListActionExecutionsPaginator",
     "ListActionTypesPaginator",
     "ListPipelineExecutionsPaginator",
     "ListPipelinesPaginator",
     "ListTagsForResourcePaginator",
     "ListWebhooksPaginator",
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
 class ListActionExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactionexecutionspaginator)
     """
 
     def paginate(
         self,
         *,
         pipelineName: str,
         filter: ActionExecutionFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActionExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactionexecutionspaginator)
         """
 
-
 class ListActionTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactiontypespaginator)
     """
 
     def paginate(
         self,
         *,
         actionOwnerFilter: ActionOwnerType = ...,
         regionFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActionTypesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactiontypespaginator)
         """
 
-
 class ListPipelineExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelineExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelineexecutionspaginator)
     """
 
     def paginate(
-        self, *, pipelineName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pipelineName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelineExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelineExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelineexecutionspaginator)
         """
 
-
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelinespaginator)
         """
 
-
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listtagsforresourcepaginator)
         """
 
-
 class ListWebhooksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListWebhooks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listwebhookspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWebhooksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListWebhooks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listwebhookspaginator)
         """
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/paginator.pyi` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         list_action_types_paginator: ListActionTypesPaginator = client.get_paginator("list_action_types")
         list_pipeline_executions_paginator: ListPipelineExecutionsPaginator = client.get_paginator("list_pipeline_executions")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_webhooks_paginator: ListWebhooksPaginator = client.get_paginator("list_webhooks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ActionOwnerType
 from .type_defs import (
     ActionExecutionFilterTypeDef,
@@ -44,120 +43,123 @@
     ListPipelineExecutionsOutputTypeDef,
     ListPipelinesOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     ListWebhooksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListActionExecutionsPaginator",
     "ListActionTypesPaginator",
     "ListPipelineExecutionsPaginator",
     "ListPipelinesPaginator",
     "ListTagsForResourcePaginator",
     "ListWebhooksPaginator",
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
 class ListActionExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactionexecutionspaginator)
     """
 
     def paginate(
         self,
         *,
         pipelineName: str,
         filter: ActionExecutionFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActionExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactionexecutionspaginator)
         """
 
+
 class ListActionTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactiontypespaginator)
     """
 
     def paginate(
         self,
         *,
         actionOwnerFilter: ActionOwnerType = ...,
         regionFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActionTypesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListActionTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listactiontypespaginator)
         """
 
+
 class ListPipelineExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelineExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelineexecutionspaginator)
     """
 
     def paginate(
-        self, *, pipelineName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pipelineName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelineExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelineExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelineexecutionspaginator)
         """
 
+
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listpipelinespaginator)
         """
 
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listtagsforresourcepaginator)
         """
 
+
 class ListWebhooksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListWebhooks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listwebhookspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWebhooksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline.Paginator.ListWebhooks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/paginators/#listwebhookspaginator)
         """
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/type_defs.py` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,16 +40,17 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AWSSessionCredentialsTypeDef",
     "AcknowledgeJobInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AcknowledgeJobOutputTypeDef",
     "AcknowledgeThirdPartyJobInputRequestTypeDef",
+    "AcknowledgeThirdPartyJobOutputTypeDef",
     "ActionConfigurationPropertyTypeDef",
     "ActionConfigurationTypeDef",
     "ActionContextTypeDef",
     "ActionTypeIdTypeDef",
     "InputArtifactTypeDef",
     "OutputArtifactTypeDef",
     "ActionExecutionFilterTypeDef",
@@ -72,58 +73,63 @@
     "TagTypeDef",
     "CurrentRevisionTypeDef",
     "DeleteCustomActionTypeInputRequestTypeDef",
     "DeletePipelineInputRequestTypeDef",
     "DeleteWebhookInputRequestTypeDef",
     "DeregisterWebhookWithThirdPartyInputRequestTypeDef",
     "DisableStageTransitionInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableStageTransitionInputRequestTypeDef",
     "ExecutionDetailsTypeDef",
     "ExecutionTriggerTypeDef",
     "JobWorkerExecutorConfigurationTypeDef",
     "LambdaExecutorConfigurationTypeDef",
     "FailureDetailsTypeDef",
     "GetActionTypeInputRequestTypeDef",
     "GetJobDetailsInputRequestTypeDef",
     "GetPipelineExecutionInputRequestTypeDef",
     "GetPipelineInputRequestTypeDef",
     "PipelineMetadataTypeDef",
     "GetPipelineStateInputRequestTypeDef",
     "GetThirdPartyJobDetailsInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListActionTypesInputListActionTypesPaginateTypeDef",
     "ListActionTypesInputRequestTypeDef",
+    "ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
     "ListPipelineExecutionsInputRequestTypeDef",
+    "ListPipelinesInputListPipelinesPaginateTypeDef",
     "ListPipelinesInputRequestTypeDef",
     "PipelineSummaryTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListWebhooksInputListWebhooksPaginateTypeDef",
     "ListWebhooksInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "StageContextTypeDef",
     "SourceRevisionTypeDef",
     "StopExecutionTriggerTypeDef",
     "ThirdPartyJobTypeDef",
+    "PutActionRevisionOutputTypeDef",
+    "PutApprovalResultOutputTypeDef",
     "RegisterWebhookWithThirdPartyInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryStageExecutionInputRequestTypeDef",
+    "RetryStageExecutionOutputTypeDef",
     "StageExecutionTypeDef",
     "TransitionStateTypeDef",
     "StartPipelineExecutionInputRequestTypeDef",
+    "StartPipelineExecutionOutputTypeDef",
     "StopPipelineExecutionInputRequestTypeDef",
+    "StopPipelineExecutionOutputTypeDef",
     "UntagResourceInputRequestTypeDef",
     "WebhookAuthConfigurationTypeDef",
     "WebhookFilterRuleTypeDef",
-    "AcknowledgeJobOutputTypeDef",
-    "AcknowledgeThirdPartyJobOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "PutActionRevisionOutputTypeDef",
-    "PutApprovalResultOutputTypeDef",
-    "RetryStageExecutionOutputTypeDef",
-    "StartPipelineExecutionOutputTypeDef",
-    "StopPipelineExecutionOutputTypeDef",
     "PollForJobsInputRequestTypeDef",
     "PollForThirdPartyJobsInputRequestTypeDef",
     "ActionDeclarationTypeDef",
+    "ListActionExecutionsInputListActionExecutionsPaginateTypeDef",
     "ListActionExecutionsInputRequestTypeDef",
     "ActionExecutionTypeDef",
     "PutActionRevisionInputRequestTypeDef",
     "ActionTypeTypeDef",
     "PutApprovalResultInputRequestTypeDef",
     "ArtifactDetailTypeDef",
     "ArtifactLocationTypeDef",
@@ -133,20 +139,14 @@
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "PutJobSuccessResultInputRequestTypeDef",
     "PutThirdPartyJobSuccessResultInputRequestTypeDef",
     "ExecutorConfigurationTypeDef",
     "PutJobFailureResultInputRequestTypeDef",
     "PutThirdPartyJobFailureResultInputRequestTypeDef",
-    "ListActionExecutionsInputListActionExecutionsPaginateTypeDef",
-    "ListActionTypesInputListActionTypesPaginateTypeDef",
-    "ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
-    "ListPipelinesInputListPipelinesPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    "ListWebhooksInputListWebhooksPaginateTypeDef",
     "ListPipelinesOutputTypeDef",
     "PipelineContextTypeDef",
     "PipelineExecutionSummaryTypeDef",
     "PollForThirdPartyJobsOutputTypeDef",
     "WebhookDefinitionTypeDef",
     "StageDeclarationTypeDef",
     "ActionStateTypeDef",
@@ -198,34 +198,39 @@
     "AcknowledgeJobInputRequestTypeDef",
     {
         "jobId": str,
         "nonce": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AcknowledgeJobOutputTypeDef = TypedDict(
+    "AcknowledgeJobOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "status": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcknowledgeThirdPartyJobInputRequestTypeDef = TypedDict(
     "AcknowledgeThirdPartyJobInputRequestTypeDef",
     {
         "jobId": str,
         "nonce": str,
         "clientToken": str,
     },
 )
 
+AcknowledgeThirdPartyJobOutputTypeDef = TypedDict(
+    "AcknowledgeThirdPartyJobOutputTypeDef",
+    {
+        "status": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredActionConfigurationPropertyTypeDef = TypedDict(
     "_RequiredActionConfigurationPropertyTypeDef",
     {
         "name": str,
         "required": bool,
         "key": bool,
         "secret": bool,
@@ -525,14 +530,21 @@
         "pipelineName": str,
         "stageName": str,
         "transitionType": StageTransitionTypeType,
         "reason": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableStageTransitionInputRequestTypeDef = TypedDict(
     "EnableStageTransitionInputRequestTypeDef",
     {
         "pipelineName": str,
         "stageName": str,
         "transitionType": StageTransitionTypeType,
     },
@@ -641,14 +653,15 @@
 
 PipelineMetadataTypeDef = TypedDict(
     "PipelineMetadataTypeDef",
     {
         "pipelineArn": str,
         "created": datetime,
         "updated": datetime,
+        "pollingDisabledAt": datetime,
     },
     total=False,
 )
 
 GetPipelineStateInputRequestTypeDef = TypedDict(
     "GetPipelineStateInputRequestTypeDef",
     {
@@ -660,34 +673,56 @@
     "GetThirdPartyJobDetailsInputRequestTypeDef",
     {
         "jobId": str,
         "clientToken": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListActionTypesInputListActionTypesPaginateTypeDef = TypedDict(
+    "ListActionTypesInputListActionTypesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "actionOwnerFilter": ActionOwnerType,
+        "regionFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListActionTypesInputRequestTypeDef = TypedDict(
     "ListActionTypesInputRequestTypeDef",
     {
         "actionOwnerFilter": ActionOwnerType,
         "nextToken": str,
         "regionFilter": str,
     },
     total=False,
 )
 
+_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
+    {
+        "pipelineName": str,
+    },
+)
+_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef(
+    _RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
+    _OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPipelineExecutionsInputRequestTypeDef = TypedDict(
     "_RequiredListPipelineExecutionsInputRequestTypeDef",
     {
         "pipelineName": str,
     },
 )
 _OptionalListPipelineExecutionsInputRequestTypeDef = TypedDict(
@@ -703,14 +738,22 @@
 class ListPipelineExecutionsInputRequestTypeDef(
     _RequiredListPipelineExecutionsInputRequestTypeDef,
     _OptionalListPipelineExecutionsInputRequestTypeDef,
 ):
     pass
 
 
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
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -723,14 +766,36 @@
         "version": int,
         "created": datetime,
         "updated": datetime,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -745,23 +810,41 @@
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
 ):
     pass
 
 
+ListWebhooksInputListWebhooksPaginateTypeDef = TypedDict(
+    "ListWebhooksInputListWebhooksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWebhooksInputRequestTypeDef = TypedDict(
     "ListWebhooksInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
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
 StageContextTypeDef = TypedDict(
     "StageContextTypeDef",
     {
         "name": str,
     },
     total=False,
 )
@@ -800,32 +883,68 @@
     {
         "clientId": str,
         "jobId": str,
     },
     total=False,
 )
 
+PutActionRevisionOutputTypeDef = TypedDict(
+    "PutActionRevisionOutputTypeDef",
+    {
+        "newRevision": bool,
+        "pipelineExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutApprovalResultOutputTypeDef = TypedDict(
+    "PutApprovalResultOutputTypeDef",
+    {
+        "approvedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterWebhookWithThirdPartyInputRequestTypeDef = TypedDict(
     "RegisterWebhookWithThirdPartyInputRequestTypeDef",
     {
         "webhookName": str,
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
 RetryStageExecutionInputRequestTypeDef = TypedDict(
     "RetryStageExecutionInputRequestTypeDef",
     {
         "pipelineName": str,
         "stageName": str,
         "pipelineExecutionId": str,
         "retryMode": Literal["FAILED_ACTIONS"],
     },
 )
 
+RetryStageExecutionOutputTypeDef = TypedDict(
+    "RetryStageExecutionOutputTypeDef",
+    {
+        "pipelineExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StageExecutionTypeDef = TypedDict(
     "StageExecutionTypeDef",
     {
         "pipelineExecutionId": str,
         "status": StageExecutionStatusType,
     },
 )
@@ -859,14 +978,22 @@
 class StartPipelineExecutionInputRequestTypeDef(
     _RequiredStartPipelineExecutionInputRequestTypeDef,
     _OptionalStartPipelineExecutionInputRequestTypeDef,
 ):
     pass
 
 
+StartPipelineExecutionOutputTypeDef = TypedDict(
+    "StartPipelineExecutionOutputTypeDef",
+    {
+        "pipelineExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopPipelineExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStopPipelineExecutionInputRequestTypeDef",
     {
         "pipelineName": str,
         "pipelineExecutionId": str,
     },
 )
@@ -883,14 +1010,22 @@
 class StopPipelineExecutionInputRequestTypeDef(
     _RequiredStopPipelineExecutionInputRequestTypeDef,
     _OptionalStopPipelineExecutionInputRequestTypeDef,
 ):
     pass
 
 
+StopPipelineExecutionOutputTypeDef = TypedDict(
+    "StopPipelineExecutionOutputTypeDef",
+    {
+        "pipelineExecutionId": str,
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
@@ -921,78 +1056,14 @@
 
 class WebhookFilterRuleTypeDef(
     _RequiredWebhookFilterRuleTypeDef, _OptionalWebhookFilterRuleTypeDef
 ):
     pass
 
 
-AcknowledgeJobOutputTypeDef = TypedDict(
-    "AcknowledgeJobOutputTypeDef",
-    {
-        "status": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AcknowledgeThirdPartyJobOutputTypeDef = TypedDict(
-    "AcknowledgeThirdPartyJobOutputTypeDef",
-    {
-        "status": JobStatusType,
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
-PutActionRevisionOutputTypeDef = TypedDict(
-    "PutActionRevisionOutputTypeDef",
-    {
-        "newRevision": bool,
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutApprovalResultOutputTypeDef = TypedDict(
-    "PutApprovalResultOutputTypeDef",
-    {
-        "approvedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RetryStageExecutionOutputTypeDef = TypedDict(
-    "RetryStageExecutionOutputTypeDef",
-    {
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartPipelineExecutionOutputTypeDef = TypedDict(
-    "StartPipelineExecutionOutputTypeDef",
-    {
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopPipelineExecutionOutputTypeDef = TypedDict(
-    "StopPipelineExecutionOutputTypeDef",
-    {
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredPollForJobsInputRequestTypeDef = TypedDict(
     "_RequiredPollForJobsInputRequestTypeDef",
     {
         "actionTypeId": ActionTypeIdTypeDef,
     },
 )
 _OptionalPollForJobsInputRequestTypeDef = TypedDict(
@@ -1057,14 +1128,37 @@
 
 class ActionDeclarationTypeDef(
     _RequiredActionDeclarationTypeDef, _OptionalActionDeclarationTypeDef
 ):
     pass
 
 
+_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef",
+    {
+        "pipelineName": str,
+    },
+)
+_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef",
+    {
+        "filter": ActionExecutionFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListActionExecutionsInputListActionExecutionsPaginateTypeDef(
+    _RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef,
+    _OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListActionExecutionsInputRequestTypeDef = TypedDict(
     "_RequiredListActionExecutionsInputRequestTypeDef",
     {
         "pipelineName": str,
     },
 )
 _OptionalListActionExecutionsInputRequestTypeDef = TypedDict(
@@ -1225,15 +1319,15 @@
 
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "tags": List[TagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
@@ -1312,113 +1406,20 @@
     {
         "jobId": str,
         "clientToken": str,
         "failureDetails": FailureDetailsTypeDef,
     },
 )
 
-_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef",
-    {
-        "pipelineName": str,
-    },
-)
-_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef",
-    {
-        "filter": ActionExecutionFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListActionExecutionsInputListActionExecutionsPaginateTypeDef(
-    _RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-    _OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-):
-    pass
-
-
-ListActionTypesInputListActionTypesPaginateTypeDef = TypedDict(
-    "ListActionTypesInputListActionTypesPaginateTypeDef",
-    {
-        "actionOwnerFilter": ActionOwnerType,
-        "regionFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
-    {
-        "pipelineName": str,
-    },
-)
-_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef(
-    _RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
-    _OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
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
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-ListWebhooksInputListWebhooksPaginateTypeDef = TypedDict(
-    "ListWebhooksInputListWebhooksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPipelinesOutputTypeDef = TypedDict(
     "ListPipelinesOutputTypeDef",
     {
         "pipelines": List[PipelineSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PipelineContextTypeDef = TypedDict(
     "PipelineContextTypeDef",
     {
         "pipelineName": str,
@@ -1444,15 +1445,15 @@
     total=False,
 )
 
 PollForThirdPartyJobsOutputTypeDef = TypedDict(
     "PollForThirdPartyJobsOutputTypeDef",
     {
         "jobs": List[ThirdPartyJobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WebhookDefinitionTypeDef = TypedDict(
     "WebhookDefinitionTypeDef",
     {
         "name": str,
@@ -1497,24 +1498,24 @@
 )
 
 CreateCustomActionTypeOutputTypeDef = TypedDict(
     "CreateCustomActionTypeOutputTypeDef",
     {
         "actionType": ActionTypeTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListActionTypesOutputTypeDef = TypedDict(
     "ListActionTypesOutputTypeDef",
     {
         "actionTypes": List[ActionTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionExecutionInputTypeDef = TypedDict(
     "ActionExecutionInputTypeDef",
     {
         "actionTypeId": ActionTypeIdTypeDef,
@@ -1548,15 +1549,15 @@
     total=False,
 )
 
 GetPipelineExecutionOutputTypeDef = TypedDict(
     "GetPipelineExecutionOutputTypeDef",
     {
         "pipelineExecution": PipelineExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActionTypeExecutorTypeDef = TypedDict(
     "_RequiredActionTypeExecutorTypeDef",
     {
         "configuration": ExecutorConfigurationTypeDef,
@@ -1580,15 +1581,15 @@
 
 
 ListPipelineExecutionsOutputTypeDef = TypedDict(
     "ListPipelineExecutionsOutputTypeDef",
     {
         "pipelineExecutionSummaries": List[PipelineExecutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListWebhookItemTypeDef = TypedDict(
     "_RequiredListWebhookItemTypeDef",
     {
         "definition": WebhookDefinitionTypeDef,
@@ -1745,23 +1746,23 @@
 
 
 ListWebhooksOutputTypeDef = TypedDict(
     "ListWebhooksOutputTypeDef",
     {
         "webhooks": List[ListWebhookItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutWebhookOutputTypeDef = TypedDict(
     "PutWebhookOutputTypeDef",
     {
         "webhook": ListWebhookItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePipelineInputRequestTypeDef = TypedDict(
     "_RequiredCreatePipelineInputRequestTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
@@ -1783,60 +1784,60 @@
 
 
 CreatePipelineOutputTypeDef = TypedDict(
     "CreatePipelineOutputTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPipelineOutputTypeDef = TypedDict(
     "GetPipelineOutputTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
         "metadata": PipelineMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineInputRequestTypeDef = TypedDict(
     "UpdatePipelineInputRequestTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
     },
 )
 
 UpdatePipelineOutputTypeDef = TypedDict(
     "UpdatePipelineOutputTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPipelineStateOutputTypeDef = TypedDict(
     "GetPipelineStateOutputTypeDef",
     {
         "pipelineName": str,
         "pipelineVersion": int,
         "stageStates": List[StageStateTypeDef],
         "created": datetime,
         "updated": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListActionExecutionsOutputTypeDef = TypedDict(
     "ListActionExecutionsOutputTypeDef",
     {
         "actionExecutionDetails": List[ActionExecutionDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobDetailsTypeDef = TypedDict(
     "JobDetailsTypeDef",
     {
         "id": str,
@@ -1867,41 +1868,41 @@
     total=False,
 )
 
 GetActionTypeOutputTypeDef = TypedDict(
     "GetActionTypeOutputTypeDef",
     {
         "actionType": ActionTypeDeclarationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateActionTypeInputRequestTypeDef = TypedDict(
     "UpdateActionTypeInputRequestTypeDef",
     {
         "actionType": ActionTypeDeclarationTypeDef,
     },
 )
 
 GetJobDetailsOutputTypeDef = TypedDict(
     "GetJobDetailsOutputTypeDef",
     {
         "jobDetails": JobDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PollForJobsOutputTypeDef = TypedDict(
     "PollForJobsOutputTypeDef",
     {
         "jobs": List[JobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetThirdPartyJobDetailsOutputTypeDef = TypedDict(
     "GetThirdPartyJobDetailsOutputTypeDef",
     {
         "jobDetails": ThirdPartyJobDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline/type_defs.pyi` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -39,16 +39,17 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AWSSessionCredentialsTypeDef",
     "AcknowledgeJobInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AcknowledgeJobOutputTypeDef",
     "AcknowledgeThirdPartyJobInputRequestTypeDef",
+    "AcknowledgeThirdPartyJobOutputTypeDef",
     "ActionConfigurationPropertyTypeDef",
     "ActionConfigurationTypeDef",
     "ActionContextTypeDef",
     "ActionTypeIdTypeDef",
     "InputArtifactTypeDef",
     "OutputArtifactTypeDef",
     "ActionExecutionFilterTypeDef",
@@ -71,58 +72,63 @@
     "TagTypeDef",
     "CurrentRevisionTypeDef",
     "DeleteCustomActionTypeInputRequestTypeDef",
     "DeletePipelineInputRequestTypeDef",
     "DeleteWebhookInputRequestTypeDef",
     "DeregisterWebhookWithThirdPartyInputRequestTypeDef",
     "DisableStageTransitionInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableStageTransitionInputRequestTypeDef",
     "ExecutionDetailsTypeDef",
     "ExecutionTriggerTypeDef",
     "JobWorkerExecutorConfigurationTypeDef",
     "LambdaExecutorConfigurationTypeDef",
     "FailureDetailsTypeDef",
     "GetActionTypeInputRequestTypeDef",
     "GetJobDetailsInputRequestTypeDef",
     "GetPipelineExecutionInputRequestTypeDef",
     "GetPipelineInputRequestTypeDef",
     "PipelineMetadataTypeDef",
     "GetPipelineStateInputRequestTypeDef",
     "GetThirdPartyJobDetailsInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListActionTypesInputListActionTypesPaginateTypeDef",
     "ListActionTypesInputRequestTypeDef",
+    "ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
     "ListPipelineExecutionsInputRequestTypeDef",
+    "ListPipelinesInputListPipelinesPaginateTypeDef",
     "ListPipelinesInputRequestTypeDef",
     "PipelineSummaryTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListWebhooksInputListWebhooksPaginateTypeDef",
     "ListWebhooksInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "StageContextTypeDef",
     "SourceRevisionTypeDef",
     "StopExecutionTriggerTypeDef",
     "ThirdPartyJobTypeDef",
+    "PutActionRevisionOutputTypeDef",
+    "PutApprovalResultOutputTypeDef",
     "RegisterWebhookWithThirdPartyInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryStageExecutionInputRequestTypeDef",
+    "RetryStageExecutionOutputTypeDef",
     "StageExecutionTypeDef",
     "TransitionStateTypeDef",
     "StartPipelineExecutionInputRequestTypeDef",
+    "StartPipelineExecutionOutputTypeDef",
     "StopPipelineExecutionInputRequestTypeDef",
+    "StopPipelineExecutionOutputTypeDef",
     "UntagResourceInputRequestTypeDef",
     "WebhookAuthConfigurationTypeDef",
     "WebhookFilterRuleTypeDef",
-    "AcknowledgeJobOutputTypeDef",
-    "AcknowledgeThirdPartyJobOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "PutActionRevisionOutputTypeDef",
-    "PutApprovalResultOutputTypeDef",
-    "RetryStageExecutionOutputTypeDef",
-    "StartPipelineExecutionOutputTypeDef",
-    "StopPipelineExecutionOutputTypeDef",
     "PollForJobsInputRequestTypeDef",
     "PollForThirdPartyJobsInputRequestTypeDef",
     "ActionDeclarationTypeDef",
+    "ListActionExecutionsInputListActionExecutionsPaginateTypeDef",
     "ListActionExecutionsInputRequestTypeDef",
     "ActionExecutionTypeDef",
     "PutActionRevisionInputRequestTypeDef",
     "ActionTypeTypeDef",
     "PutApprovalResultInputRequestTypeDef",
     "ArtifactDetailTypeDef",
     "ArtifactLocationTypeDef",
@@ -132,20 +138,14 @@
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "PutJobSuccessResultInputRequestTypeDef",
     "PutThirdPartyJobSuccessResultInputRequestTypeDef",
     "ExecutorConfigurationTypeDef",
     "PutJobFailureResultInputRequestTypeDef",
     "PutThirdPartyJobFailureResultInputRequestTypeDef",
-    "ListActionExecutionsInputListActionExecutionsPaginateTypeDef",
-    "ListActionTypesInputListActionTypesPaginateTypeDef",
-    "ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
-    "ListPipelinesInputListPipelinesPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    "ListWebhooksInputListWebhooksPaginateTypeDef",
     "ListPipelinesOutputTypeDef",
     "PipelineContextTypeDef",
     "PipelineExecutionSummaryTypeDef",
     "PollForThirdPartyJobsOutputTypeDef",
     "WebhookDefinitionTypeDef",
     "StageDeclarationTypeDef",
     "ActionStateTypeDef",
@@ -197,34 +197,39 @@
     "AcknowledgeJobInputRequestTypeDef",
     {
         "jobId": str,
         "nonce": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AcknowledgeJobOutputTypeDef = TypedDict(
+    "AcknowledgeJobOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "status": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcknowledgeThirdPartyJobInputRequestTypeDef = TypedDict(
     "AcknowledgeThirdPartyJobInputRequestTypeDef",
     {
         "jobId": str,
         "nonce": str,
         "clientToken": str,
     },
 )
 
+AcknowledgeThirdPartyJobOutputTypeDef = TypedDict(
+    "AcknowledgeThirdPartyJobOutputTypeDef",
+    {
+        "status": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredActionConfigurationPropertyTypeDef = TypedDict(
     "_RequiredActionConfigurationPropertyTypeDef",
     {
         "name": str,
         "required": bool,
         "key": bool,
         "secret": bool,
@@ -518,14 +523,21 @@
         "pipelineName": str,
         "stageName": str,
         "transitionType": StageTransitionTypeType,
         "reason": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableStageTransitionInputRequestTypeDef = TypedDict(
     "EnableStageTransitionInputRequestTypeDef",
     {
         "pipelineName": str,
         "stageName": str,
         "transitionType": StageTransitionTypeType,
     },
@@ -630,14 +642,15 @@
 
 PipelineMetadataTypeDef = TypedDict(
     "PipelineMetadataTypeDef",
     {
         "pipelineArn": str,
         "created": datetime,
         "updated": datetime,
+        "pollingDisabledAt": datetime,
     },
     total=False,
 )
 
 GetPipelineStateInputRequestTypeDef = TypedDict(
     "GetPipelineStateInputRequestTypeDef",
     {
@@ -649,34 +662,54 @@
     "GetThirdPartyJobDetailsInputRequestTypeDef",
     {
         "jobId": str,
         "clientToken": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListActionTypesInputListActionTypesPaginateTypeDef = TypedDict(
+    "ListActionTypesInputListActionTypesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "actionOwnerFilter": ActionOwnerType,
+        "regionFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListActionTypesInputRequestTypeDef = TypedDict(
     "ListActionTypesInputRequestTypeDef",
     {
         "actionOwnerFilter": ActionOwnerType,
         "nextToken": str,
         "regionFilter": str,
     },
     total=False,
 )
 
+_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
+    {
+        "pipelineName": str,
+    },
+)
+_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef(
+    _RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
+    _OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPipelineExecutionsInputRequestTypeDef = TypedDict(
     "_RequiredListPipelineExecutionsInputRequestTypeDef",
     {
         "pipelineName": str,
     },
 )
 _OptionalListPipelineExecutionsInputRequestTypeDef = TypedDict(
@@ -690,14 +723,22 @@
 
 class ListPipelineExecutionsInputRequestTypeDef(
     _RequiredListPipelineExecutionsInputRequestTypeDef,
     _OptionalListPipelineExecutionsInputRequestTypeDef,
 ):
     pass
 
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
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -710,14 +751,34 @@
         "version": int,
         "created": datetime,
         "updated": datetime,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -730,23 +791,41 @@
 )
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
 ):
     pass
 
+ListWebhooksInputListWebhooksPaginateTypeDef = TypedDict(
+    "ListWebhooksInputListWebhooksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWebhooksInputRequestTypeDef = TypedDict(
     "ListWebhooksInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
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
 StageContextTypeDef = TypedDict(
     "StageContextTypeDef",
     {
         "name": str,
     },
     total=False,
 )
@@ -783,32 +862,68 @@
     {
         "clientId": str,
         "jobId": str,
     },
     total=False,
 )
 
+PutActionRevisionOutputTypeDef = TypedDict(
+    "PutActionRevisionOutputTypeDef",
+    {
+        "newRevision": bool,
+        "pipelineExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutApprovalResultOutputTypeDef = TypedDict(
+    "PutApprovalResultOutputTypeDef",
+    {
+        "approvedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterWebhookWithThirdPartyInputRequestTypeDef = TypedDict(
     "RegisterWebhookWithThirdPartyInputRequestTypeDef",
     {
         "webhookName": str,
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
 RetryStageExecutionInputRequestTypeDef = TypedDict(
     "RetryStageExecutionInputRequestTypeDef",
     {
         "pipelineName": str,
         "stageName": str,
         "pipelineExecutionId": str,
         "retryMode": Literal["FAILED_ACTIONS"],
     },
 )
 
+RetryStageExecutionOutputTypeDef = TypedDict(
+    "RetryStageExecutionOutputTypeDef",
+    {
+        "pipelineExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StageExecutionTypeDef = TypedDict(
     "StageExecutionTypeDef",
     {
         "pipelineExecutionId": str,
         "status": StageExecutionStatusType,
     },
 )
@@ -840,14 +955,22 @@
 
 class StartPipelineExecutionInputRequestTypeDef(
     _RequiredStartPipelineExecutionInputRequestTypeDef,
     _OptionalStartPipelineExecutionInputRequestTypeDef,
 ):
     pass
 
+StartPipelineExecutionOutputTypeDef = TypedDict(
+    "StartPipelineExecutionOutputTypeDef",
+    {
+        "pipelineExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopPipelineExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStopPipelineExecutionInputRequestTypeDef",
     {
         "pipelineName": str,
         "pipelineExecutionId": str,
     },
 )
@@ -862,14 +985,22 @@
 
 class StopPipelineExecutionInputRequestTypeDef(
     _RequiredStopPipelineExecutionInputRequestTypeDef,
     _OptionalStopPipelineExecutionInputRequestTypeDef,
 ):
     pass
 
+StopPipelineExecutionOutputTypeDef = TypedDict(
+    "StopPipelineExecutionOutputTypeDef",
+    {
+        "pipelineExecutionId": str,
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
@@ -898,78 +1029,14 @@
 )
 
 class WebhookFilterRuleTypeDef(
     _RequiredWebhookFilterRuleTypeDef, _OptionalWebhookFilterRuleTypeDef
 ):
     pass
 
-AcknowledgeJobOutputTypeDef = TypedDict(
-    "AcknowledgeJobOutputTypeDef",
-    {
-        "status": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AcknowledgeThirdPartyJobOutputTypeDef = TypedDict(
-    "AcknowledgeThirdPartyJobOutputTypeDef",
-    {
-        "status": JobStatusType,
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
-PutActionRevisionOutputTypeDef = TypedDict(
-    "PutActionRevisionOutputTypeDef",
-    {
-        "newRevision": bool,
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutApprovalResultOutputTypeDef = TypedDict(
-    "PutApprovalResultOutputTypeDef",
-    {
-        "approvedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RetryStageExecutionOutputTypeDef = TypedDict(
-    "RetryStageExecutionOutputTypeDef",
-    {
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartPipelineExecutionOutputTypeDef = TypedDict(
-    "StartPipelineExecutionOutputTypeDef",
-    {
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopPipelineExecutionOutputTypeDef = TypedDict(
-    "StopPipelineExecutionOutputTypeDef",
-    {
-        "pipelineExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredPollForJobsInputRequestTypeDef = TypedDict(
     "_RequiredPollForJobsInputRequestTypeDef",
     {
         "actionTypeId": ActionTypeIdTypeDef,
     },
 )
 _OptionalPollForJobsInputRequestTypeDef = TypedDict(
@@ -1028,14 +1095,35 @@
 )
 
 class ActionDeclarationTypeDef(
     _RequiredActionDeclarationTypeDef, _OptionalActionDeclarationTypeDef
 ):
     pass
 
+_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef",
+    {
+        "pipelineName": str,
+    },
+)
+_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef",
+    {
+        "filter": ActionExecutionFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListActionExecutionsInputListActionExecutionsPaginateTypeDef(
+    _RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef,
+    _OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListActionExecutionsInputRequestTypeDef = TypedDict(
     "_RequiredListActionExecutionsInputRequestTypeDef",
     {
         "pipelineName": str,
     },
 )
 _OptionalListActionExecutionsInputRequestTypeDef = TypedDict(
@@ -1188,15 +1276,15 @@
     pass
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "tags": List[TagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "resourceArn": str,
@@ -1271,107 +1359,20 @@
     {
         "jobId": str,
         "clientToken": str,
         "failureDetails": FailureDetailsTypeDef,
     },
 )
 
-_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef",
-    {
-        "pipelineName": str,
-    },
-)
-_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef",
-    {
-        "filter": ActionExecutionFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListActionExecutionsInputListActionExecutionsPaginateTypeDef(
-    _RequiredListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-    _OptionalListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-):
-    pass
-
-ListActionTypesInputListActionTypesPaginateTypeDef = TypedDict(
-    "ListActionTypesInputListActionTypesPaginateTypeDef",
-    {
-        "actionOwnerFilter": ActionOwnerType,
-        "regionFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
-    {
-        "pipelineName": str,
-    },
-)
-_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef(
-    _RequiredListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
-    _OptionalListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
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
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-ListWebhooksInputListWebhooksPaginateTypeDef = TypedDict(
-    "ListWebhooksInputListWebhooksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPipelinesOutputTypeDef = TypedDict(
     "ListPipelinesOutputTypeDef",
     {
         "pipelines": List[PipelineSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PipelineContextTypeDef = TypedDict(
     "PipelineContextTypeDef",
     {
         "pipelineName": str,
@@ -1397,15 +1398,15 @@
     total=False,
 )
 
 PollForThirdPartyJobsOutputTypeDef = TypedDict(
     "PollForThirdPartyJobsOutputTypeDef",
     {
         "jobs": List[ThirdPartyJobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WebhookDefinitionTypeDef = TypedDict(
     "WebhookDefinitionTypeDef",
     {
         "name": str,
@@ -1448,24 +1449,24 @@
 )
 
 CreateCustomActionTypeOutputTypeDef = TypedDict(
     "CreateCustomActionTypeOutputTypeDef",
     {
         "actionType": ActionTypeTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListActionTypesOutputTypeDef = TypedDict(
     "ListActionTypesOutputTypeDef",
     {
         "actionTypes": List[ActionTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionExecutionInputTypeDef = TypedDict(
     "ActionExecutionInputTypeDef",
     {
         "actionTypeId": ActionTypeIdTypeDef,
@@ -1499,15 +1500,15 @@
     total=False,
 )
 
 GetPipelineExecutionOutputTypeDef = TypedDict(
     "GetPipelineExecutionOutputTypeDef",
     {
         "pipelineExecution": PipelineExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActionTypeExecutorTypeDef = TypedDict(
     "_RequiredActionTypeExecutorTypeDef",
     {
         "configuration": ExecutorConfigurationTypeDef,
@@ -1529,15 +1530,15 @@
     pass
 
 ListPipelineExecutionsOutputTypeDef = TypedDict(
     "ListPipelineExecutionsOutputTypeDef",
     {
         "pipelineExecutionSummaries": List[PipelineExecutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListWebhookItemTypeDef = TypedDict(
     "_RequiredListWebhookItemTypeDef",
     {
         "definition": WebhookDefinitionTypeDef,
@@ -1686,23 +1687,23 @@
     pass
 
 ListWebhooksOutputTypeDef = TypedDict(
     "ListWebhooksOutputTypeDef",
     {
         "webhooks": List[ListWebhookItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutWebhookOutputTypeDef = TypedDict(
     "PutWebhookOutputTypeDef",
     {
         "webhook": ListWebhookItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePipelineInputRequestTypeDef = TypedDict(
     "_RequiredCreatePipelineInputRequestTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
@@ -1722,60 +1723,60 @@
     pass
 
 CreatePipelineOutputTypeDef = TypedDict(
     "CreatePipelineOutputTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPipelineOutputTypeDef = TypedDict(
     "GetPipelineOutputTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
         "metadata": PipelineMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePipelineInputRequestTypeDef = TypedDict(
     "UpdatePipelineInputRequestTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
     },
 )
 
 UpdatePipelineOutputTypeDef = TypedDict(
     "UpdatePipelineOutputTypeDef",
     {
         "pipeline": PipelineDeclarationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPipelineStateOutputTypeDef = TypedDict(
     "GetPipelineStateOutputTypeDef",
     {
         "pipelineName": str,
         "pipelineVersion": int,
         "stageStates": List[StageStateTypeDef],
         "created": datetime,
         "updated": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListActionExecutionsOutputTypeDef = TypedDict(
     "ListActionExecutionsOutputTypeDef",
     {
         "actionExecutionDetails": List[ActionExecutionDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobDetailsTypeDef = TypedDict(
     "JobDetailsTypeDef",
     {
         "id": str,
@@ -1806,41 +1807,41 @@
     total=False,
 )
 
 GetActionTypeOutputTypeDef = TypedDict(
     "GetActionTypeOutputTypeDef",
     {
         "actionType": ActionTypeDeclarationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateActionTypeInputRequestTypeDef = TypedDict(
     "UpdateActionTypeInputRequestTypeDef",
     {
         "actionType": ActionTypeDeclarationTypeDef,
     },
 )
 
 GetJobDetailsOutputTypeDef = TypedDict(
     "GetJobDetailsOutputTypeDef",
     {
         "jobDetails": JobDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PollForJobsOutputTypeDef = TypedDict(
     "PollForJobsOutputTypeDef",
     {
         "jobs": List[JobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetThirdPartyJobDetailsOutputTypeDef = TypedDict(
     "GetThirdPartyJobDetailsOutputTypeDef",
     {
         "jobDetails": ThirdPartyJobDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/PKG-INFO` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codepipeline
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodePipeline 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodePipeline 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codepipeline"></a>
 
 # types-aiobotocore-codepipeline
 
 [![PyPI - types-aiobotocore-codepipeline](https://img.shields.io/pypi/v/types-aiobotocore-codepipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codepipeline)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codepipeline.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codepipeline)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codepipeline?color=blue)](https://pypistats.org/packages/types-aiobotocore-codepipeline)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodePipeline 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline)
+[aiobotocore.CodePipeline 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codepipeline.html#CodePipeline)
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
 [types-aiobotocore-codepipeline docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/).
 
 See how it helps to find and fix potential bugs:
 
@@ -359,16 +359,17 @@
 `types_aiobotocore_codepipeline.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codepipeline.type_defs import (
     AWSSessionCredentialsTypeDef,
     AcknowledgeJobInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AcknowledgeJobOutputTypeDef,
     AcknowledgeThirdPartyJobInputRequestTypeDef,
+    AcknowledgeThirdPartyJobOutputTypeDef,
     ActionConfigurationPropertyTypeDef,
     ActionConfigurationTypeDef,
     ActionContextTypeDef,
     ActionTypeIdTypeDef,
     InputArtifactTypeDef,
     OutputArtifactTypeDef,
     ActionExecutionFilterTypeDef,
@@ -391,58 +392,63 @@
     TagTypeDef,
     CurrentRevisionTypeDef,
     DeleteCustomActionTypeInputRequestTypeDef,
     DeletePipelineInputRequestTypeDef,
     DeleteWebhookInputRequestTypeDef,
     DeregisterWebhookWithThirdPartyInputRequestTypeDef,
     DisableStageTransitionInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableStageTransitionInputRequestTypeDef,
     ExecutionDetailsTypeDef,
     ExecutionTriggerTypeDef,
     JobWorkerExecutorConfigurationTypeDef,
     LambdaExecutorConfigurationTypeDef,
     FailureDetailsTypeDef,
     GetActionTypeInputRequestTypeDef,
     GetJobDetailsInputRequestTypeDef,
     GetPipelineExecutionInputRequestTypeDef,
     GetPipelineInputRequestTypeDef,
     PipelineMetadataTypeDef,
     GetPipelineStateInputRequestTypeDef,
     GetThirdPartyJobDetailsInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListActionTypesInputListActionTypesPaginateTypeDef,
     ListActionTypesInputRequestTypeDef,
+    ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
     ListPipelineExecutionsInputRequestTypeDef,
+    ListPipelinesInputListPipelinesPaginateTypeDef,
     ListPipelinesInputRequestTypeDef,
     PipelineSummaryTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListWebhooksInputListWebhooksPaginateTypeDef,
     ListWebhooksInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     StageContextTypeDef,
     SourceRevisionTypeDef,
     StopExecutionTriggerTypeDef,
     ThirdPartyJobTypeDef,
+    PutActionRevisionOutputTypeDef,
+    PutApprovalResultOutputTypeDef,
     RegisterWebhookWithThirdPartyInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     RetryStageExecutionInputRequestTypeDef,
+    RetryStageExecutionOutputTypeDef,
     StageExecutionTypeDef,
     TransitionStateTypeDef,
     StartPipelineExecutionInputRequestTypeDef,
+    StartPipelineExecutionOutputTypeDef,
     StopPipelineExecutionInputRequestTypeDef,
+    StopPipelineExecutionOutputTypeDef,
     UntagResourceInputRequestTypeDef,
     WebhookAuthConfigurationTypeDef,
     WebhookFilterRuleTypeDef,
-    AcknowledgeJobOutputTypeDef,
-    AcknowledgeThirdPartyJobOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    PutActionRevisionOutputTypeDef,
-    PutApprovalResultOutputTypeDef,
-    RetryStageExecutionOutputTypeDef,
-    StartPipelineExecutionOutputTypeDef,
-    StopPipelineExecutionOutputTypeDef,
     PollForJobsInputRequestTypeDef,
     PollForThirdPartyJobsInputRequestTypeDef,
     ActionDeclarationTypeDef,
+    ListActionExecutionsInputListActionExecutionsPaginateTypeDef,
     ListActionExecutionsInputRequestTypeDef,
     ActionExecutionTypeDef,
     PutActionRevisionInputRequestTypeDef,
     ActionTypeTypeDef,
     PutApprovalResultInputRequestTypeDef,
     ArtifactDetailTypeDef,
     ArtifactLocationTypeDef,
@@ -452,20 +458,14 @@
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     PutJobSuccessResultInputRequestTypeDef,
     PutThirdPartyJobSuccessResultInputRequestTypeDef,
     ExecutorConfigurationTypeDef,
     PutJobFailureResultInputRequestTypeDef,
     PutThirdPartyJobFailureResultInputRequestTypeDef,
-    ListActionExecutionsInputListActionExecutionsPaginateTypeDef,
-    ListActionTypesInputListActionTypesPaginateTypeDef,
-    ListPipelineExecutionsInputListPipelineExecutionsPaginateTypeDef,
-    ListPipelinesInputListPipelinesPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    ListWebhooksInputListWebhooksPaginateTypeDef,
     ListPipelinesOutputTypeDef,
     PipelineContextTypeDef,
     PipelineExecutionSummaryTypeDef,
     PollForThirdPartyJobsOutputTypeDef,
     WebhookDefinitionTypeDef,
     StageDeclarationTypeDef,
     ActionStateTypeDef,
@@ -512,43 +512,43 @@
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

### Comparing `types-aiobotocore-codepipeline-2.5.0.post1/types_aiobotocore_codepipeline.egg-info/SOURCES.txt` & `types-aiobotocore-codepipeline-2.5.1/types_aiobotocore_codepipeline.egg-info/SOURCES.txt`

 * *Files identical despite different names*

