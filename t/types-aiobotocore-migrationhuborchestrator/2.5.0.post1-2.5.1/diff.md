# Comparing `tmp/types-aiobotocore-migrationhuborchestrator-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-migrationhuborchestrator-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-migrationhuborchestrator-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-migrationhuborchestrator-2.5.1.tar", last modified: Wed Jun 28 01:43:52 2023, max compression
```

## Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1.tar` & `types-aiobotocore-migrationhuborchestrator-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.367443 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18396 2023-03-11 12:27:01.363443 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16757 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.367443 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2246 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.359443 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/
--rw-r--r--   0 runner    (1001) docker     (123)     2061 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2060 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1011 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27081 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27037 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9779 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9777 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9921 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9911 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    31840 2023-03-11 12:18:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    31812 2023-03-11 12:18:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.363443 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18396 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.206179 types-aiobotocore-migrationhuborchestrator-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18405 2023-06-28 01:43:52.206179 types-aiobotocore-migrationhuborchestrator-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16772 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:52.206179 types-aiobotocore-migrationhuborchestrator-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2240 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.206179 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/
+-rw-r--r--   0 runner    (1001) docker     (123)     2061 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2060 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      999 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27081 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27037 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9988 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9986 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9815 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9806 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    31902 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31874 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:35.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.206179 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18405 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/LICENSE` & `types-aiobotocore-migrationhuborchestrator-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/PKG-INFO` & `types-aiobotocore-migrationhuborchestrator-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migrationhuborchestrator
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migrationhuborchestrator"></a>
 
 # types-aiobotocore-migrationhuborchestrator
 
 [![PyPI - types-aiobotocore-migrationhuborchestrator](https://img.shields.io/pypi/v/types-aiobotocore-migrationhuborchestrator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhuborchestrator)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhuborchestrator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhuborchestrator)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhuborchestrator?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhuborchestrator)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubOrchestrator 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator)
+[aiobotocore.MigrationHubOrchestrator 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator)
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
 [types-aiobotocore-migrationhuborchestrator docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/).
 
 See how it helps to find and fix potential bugs:
 
@@ -354,77 +354,77 @@
 `types_aiobotocore_migrationhuborchestrator.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_migrationhuborchestrator.type_defs import (
     StepInputTypeDef,
-    ResponseMetadataTypeDef,
     CreateWorkflowStepGroupRequestRequestTypeDef,
     ToolTypeDef,
+    CreateWorkflowStepResponseTypeDef,
     DeleteMigrationWorkflowRequestRequestTypeDef,
+    DeleteMigrationWorkflowResponseTypeDef,
     DeleteWorkflowStepGroupRequestRequestTypeDef,
     DeleteWorkflowStepRequestRequestTypeDef,
     GetMigrationWorkflowRequestRequestTypeDef,
     GetMigrationWorkflowTemplateRequestRequestTypeDef,
     TemplateInputTypeDef,
     GetTemplateStepGroupRequestRequestTypeDef,
     GetTemplateStepRequestRequestTypeDef,
     StepOutputTypeDef,
     GetWorkflowStepGroupRequestRequestTypeDef,
     GetWorkflowStepRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef,
     ListMigrationWorkflowTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
+    ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListMigrationWorkflowsRequestRequestTypeDef,
     MigrationWorkflowSummaryTypeDef,
+    ListPluginsRequestListPluginsPaginateTypeDef,
     ListPluginsRequestRequestTypeDef,
     PluginSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
     ListTemplateStepGroupsRequestRequestTypeDef,
     TemplateStepGroupSummaryTypeDef,
+    ListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
     ListTemplateStepsRequestRequestTypeDef,
     TemplateStepSummaryTypeDef,
+    ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
     ListWorkflowStepGroupsRequestRequestTypeDef,
     WorkflowStepGroupSummaryTypeDef,
+    ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
     ListWorkflowStepsRequestRequestTypeDef,
     WorkflowStepSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PlatformCommandTypeDef,
     PlatformScriptKeyTypeDef,
+    ResponseMetadataTypeDef,
     RetryWorkflowStepRequestRequestTypeDef,
+    RetryWorkflowStepResponseTypeDef,
     StartMigrationWorkflowRequestRequestTypeDef,
+    StartMigrationWorkflowResponseTypeDef,
     StopMigrationWorkflowRequestRequestTypeDef,
+    StopMigrationWorkflowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateWorkflowStepGroupRequestRequestTypeDef,
+    UpdateWorkflowStepResponseTypeDef,
     WorkflowStepOutputUnionTypeDef,
     CreateMigrationWorkflowRequestRequestTypeDef,
-    UpdateMigrationWorkflowRequestRequestTypeDef,
     CreateMigrationWorkflowResponseTypeDef,
-    CreateWorkflowStepResponseTypeDef,
-    DeleteMigrationWorkflowResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RetryWorkflowStepResponseTypeDef,
-    StartMigrationWorkflowResponseTypeDef,
-    StopMigrationWorkflowResponseTypeDef,
+    UpdateMigrationWorkflowRequestRequestTypeDef,
     UpdateMigrationWorkflowResponseTypeDef,
-    UpdateWorkflowStepResponseTypeDef,
     CreateWorkflowStepGroupResponseTypeDef,
     GetMigrationWorkflowResponseTypeDef,
     GetTemplateStepGroupResponseTypeDef,
     GetWorkflowStepGroupResponseTypeDef,
     UpdateWorkflowStepGroupResponseTypeDef,
     GetMigrationWorkflowTemplateResponseTypeDef,
-    ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef,
-    ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef,
-    ListPluginsRequestListPluginsPaginateTypeDef,
-    ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-    ListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-    ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-    ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
     ListMigrationWorkflowTemplatesResponseTypeDef,
     ListMigrationWorkflowsResponseTypeDef,
     ListPluginsResponseTypeDef,
     ListTemplateStepGroupsResponseTypeDef,
     ListTemplateStepsResponseTypeDef,
     ListWorkflowStepGroupsResponseTypeDef,
     ListWorkflowStepsResponseTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/README.md` & `types-aiobotocore-migrationhuborchestrator-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-migrationhuborchestrator"></a>
 
 # types-aiobotocore-migrationhuborchestrator
 
 [![PyPI - types-aiobotocore-migrationhuborchestrator](https://img.shields.io/pypi/v/types-aiobotocore-migrationhuborchestrator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhuborchestrator)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhuborchestrator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhuborchestrator)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhuborchestrator?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhuborchestrator)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubOrchestrator 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator)
+[aiobotocore.MigrationHubOrchestrator 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator)
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
 [types-aiobotocore-migrationhuborchestrator docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,77 +321,77 @@
 `types_aiobotocore_migrationhuborchestrator.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_migrationhuborchestrator.type_defs import (
     StepInputTypeDef,
-    ResponseMetadataTypeDef,
     CreateWorkflowStepGroupRequestRequestTypeDef,
     ToolTypeDef,
+    CreateWorkflowStepResponseTypeDef,
     DeleteMigrationWorkflowRequestRequestTypeDef,
+    DeleteMigrationWorkflowResponseTypeDef,
     DeleteWorkflowStepGroupRequestRequestTypeDef,
     DeleteWorkflowStepRequestRequestTypeDef,
     GetMigrationWorkflowRequestRequestTypeDef,
     GetMigrationWorkflowTemplateRequestRequestTypeDef,
     TemplateInputTypeDef,
     GetTemplateStepGroupRequestRequestTypeDef,
     GetTemplateStepRequestRequestTypeDef,
     StepOutputTypeDef,
     GetWorkflowStepGroupRequestRequestTypeDef,
     GetWorkflowStepRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef,
     ListMigrationWorkflowTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
+    ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListMigrationWorkflowsRequestRequestTypeDef,
     MigrationWorkflowSummaryTypeDef,
+    ListPluginsRequestListPluginsPaginateTypeDef,
     ListPluginsRequestRequestTypeDef,
     PluginSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
     ListTemplateStepGroupsRequestRequestTypeDef,
     TemplateStepGroupSummaryTypeDef,
+    ListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
     ListTemplateStepsRequestRequestTypeDef,
     TemplateStepSummaryTypeDef,
+    ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
     ListWorkflowStepGroupsRequestRequestTypeDef,
     WorkflowStepGroupSummaryTypeDef,
+    ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
     ListWorkflowStepsRequestRequestTypeDef,
     WorkflowStepSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PlatformCommandTypeDef,
     PlatformScriptKeyTypeDef,
+    ResponseMetadataTypeDef,
     RetryWorkflowStepRequestRequestTypeDef,
+    RetryWorkflowStepResponseTypeDef,
     StartMigrationWorkflowRequestRequestTypeDef,
+    StartMigrationWorkflowResponseTypeDef,
     StopMigrationWorkflowRequestRequestTypeDef,
+    StopMigrationWorkflowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateWorkflowStepGroupRequestRequestTypeDef,
+    UpdateWorkflowStepResponseTypeDef,
     WorkflowStepOutputUnionTypeDef,
     CreateMigrationWorkflowRequestRequestTypeDef,
-    UpdateMigrationWorkflowRequestRequestTypeDef,
     CreateMigrationWorkflowResponseTypeDef,
-    CreateWorkflowStepResponseTypeDef,
-    DeleteMigrationWorkflowResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RetryWorkflowStepResponseTypeDef,
-    StartMigrationWorkflowResponseTypeDef,
-    StopMigrationWorkflowResponseTypeDef,
+    UpdateMigrationWorkflowRequestRequestTypeDef,
     UpdateMigrationWorkflowResponseTypeDef,
-    UpdateWorkflowStepResponseTypeDef,
     CreateWorkflowStepGroupResponseTypeDef,
     GetMigrationWorkflowResponseTypeDef,
     GetTemplateStepGroupResponseTypeDef,
     GetWorkflowStepGroupResponseTypeDef,
     UpdateWorkflowStepGroupResponseTypeDef,
     GetMigrationWorkflowTemplateResponseTypeDef,
-    ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef,
-    ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef,
-    ListPluginsRequestListPluginsPaginateTypeDef,
-    ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-    ListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-    ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-    ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
     ListMigrationWorkflowTemplatesResponseTypeDef,
     ListMigrationWorkflowsResponseTypeDef,
     ListPluginsResponseTypeDef,
     ListTemplateStepGroupsResponseTypeDef,
     ListTemplateStepsResponseTypeDef,
     ListWorkflowStepGroupsResponseTypeDef,
     ListWorkflowStepsResponseTypeDef,
@@ -412,43 +412,43 @@
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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/setup.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-migrationhuborchestrator.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-migrationhuborchestrator",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_migrationhuborchestrator"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/",
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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/__init__.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/__init__.pyi` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/__main__.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/__main__.py`

 * *Files 22% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator\nOther"
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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/client.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/client.pyi` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/literals.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/literals.py`

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
```

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/literals.pyi` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -151,14 +151,15 @@
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
@@ -237,14 +238,15 @@
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
@@ -255,14 +257,15 @@
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
@@ -298,14 +301,15 @@
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
@@ -324,16 +328,19 @@
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
@@ -417,15 +424,17 @@
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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/paginator.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_template_steps_paginator: ListTemplateStepsPaginator = client.get_paginator("list_template_steps")
         list_templates_paginator: ListTemplatesPaginator = client.get_paginator("list_templates")
         list_workflow_step_groups_paginator: ListWorkflowStepGroupsPaginator = client.get_paginator("list_workflow_step_groups")
         list_workflow_steps_paginator: ListWorkflowStepsPaginator = client.get_paginator("list_workflow_steps")
         list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import MigrationWorkflowStatusEnumType
 from .type_defs import (
     ListMigrationWorkflowsResponseTypeDef,
@@ -46,20 +45,14 @@
     ListTemplateStepGroupsResponseTypeDef,
     ListTemplateStepsResponseTypeDef,
     ListWorkflowStepGroupsResponseTypeDef,
     ListWorkflowStepsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListPluginsPaginator",
     "ListTemplateStepGroupsPaginator",
     "ListTemplateStepsPaginator",
     "ListTemplatesPaginator",
     "ListWorkflowStepGroupsPaginator",
     "ListWorkflowStepsPaginator",
@@ -80,90 +73,90 @@
 class ListPluginsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListPlugins)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listpluginspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPluginsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListPlugins.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listpluginspaginator)
         """
 
 
 class ListTemplateStepGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateStepGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepgroupspaginator)
     """
 
     def paginate(
-        self, *, templateId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, templateId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplateStepGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateStepGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepgroupspaginator)
         """
 
 
 class ListTemplateStepsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateSteps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepspaginator)
     """
 
     def paginate(
-        self, *, templateId: str, stepGroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, templateId: str, stepGroupId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplateStepsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateSteps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepspaginator)
         """
 
 
 class ListTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatespaginator)
     """
 
     def paginate(
-        self, *, name: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMigrationWorkflowTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatespaginator)
         """
 
 
 class ListWorkflowStepGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowStepGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepgroupspaginator)
     """
 
     def paginate(
-        self, *, workflowId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workflowId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowStepGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowStepGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepgroupspaginator)
         """
 
 
 class ListWorkflowStepsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowSteps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepspaginator)
     """
 
     def paginate(
-        self, *, workflowId: str, stepGroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workflowId: str, stepGroupId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowStepsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowSteps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepspaginator)
         """
 
 
@@ -176,13 +169,13 @@
     def paginate(
         self,
         *,
         templateId: str = ...,
         adsApplicationConfigurationName: str = ...,
         status: MigrationWorkflowStatusEnumType = ...,
         name: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMigrationWorkflowsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowspaginator)
         """
```

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/paginator.pyi` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_template_steps_paginator: ListTemplateStepsPaginator = client.get_paginator("list_template_steps")
         list_templates_paginator: ListTemplatesPaginator = client.get_paginator("list_templates")
         list_workflow_step_groups_paginator: ListWorkflowStepGroupsPaginator = client.get_paginator("list_workflow_step_groups")
         list_workflow_steps_paginator: ListWorkflowStepsPaginator = client.get_paginator("list_workflow_steps")
         list_workflows_paginator: ListWorkflowsPaginator = client.get_paginator("list_workflows")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import MigrationWorkflowStatusEnumType
 from .type_defs import (
     ListMigrationWorkflowsResponseTypeDef,
@@ -46,19 +45,14 @@
     ListTemplateStepGroupsResponseTypeDef,
     ListTemplateStepsResponseTypeDef,
     ListWorkflowStepGroupsResponseTypeDef,
     ListWorkflowStepsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListPluginsPaginator",
     "ListTemplateStepGroupsPaginator",
     "ListTemplateStepsPaginator",
     "ListTemplatesPaginator",
     "ListWorkflowStepGroupsPaginator",
     "ListWorkflowStepsPaginator",
@@ -76,85 +70,85 @@
 class ListPluginsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListPlugins)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listpluginspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPluginsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListPlugins.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listpluginspaginator)
         """
 
 class ListTemplateStepGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateStepGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepgroupspaginator)
     """
 
     def paginate(
-        self, *, templateId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, templateId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplateStepGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateStepGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepgroupspaginator)
         """
 
 class ListTemplateStepsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateSteps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepspaginator)
     """
 
     def paginate(
-        self, *, templateId: str, stepGroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, templateId: str, stepGroupId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplateStepsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplateSteps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatestepspaginator)
         """
 
 class ListTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatespaginator)
     """
 
     def paginate(
-        self, *, name: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMigrationWorkflowTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listtemplatespaginator)
         """
 
 class ListWorkflowStepGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowStepGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepgroupspaginator)
     """
 
     def paginate(
-        self, *, workflowId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workflowId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowStepGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowStepGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepgroupspaginator)
         """
 
 class ListWorkflowStepsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowSteps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepspaginator)
     """
 
     def paginate(
-        self, *, workflowId: str, stepGroupId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, workflowId: str, stepGroupId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkflowStepsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflowSteps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowstepspaginator)
         """
 
 class ListWorkflowsPaginator(AioPaginator):
@@ -166,13 +160,13 @@
     def paginate(
         self,
         *,
         templateId: str = ...,
         adsApplicationConfigurationName: str = ...,
         status: MigrationWorkflowStatusEnumType = ...,
         name: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMigrationWorkflowsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator.Paginator.ListWorkflows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/paginators/#listworkflowspaginator)
         """
```

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/type_defs.py` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/type_defs.py`

 * *Files 14% similar despite different names*

```diff
@@ -35,77 +35,77 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "StepInputTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateWorkflowStepGroupRequestRequestTypeDef",
     "ToolTypeDef",
+    "CreateWorkflowStepResponseTypeDef",
     "DeleteMigrationWorkflowRequestRequestTypeDef",
+    "DeleteMigrationWorkflowResponseTypeDef",
     "DeleteWorkflowStepGroupRequestRequestTypeDef",
     "DeleteWorkflowStepRequestRequestTypeDef",
     "GetMigrationWorkflowRequestRequestTypeDef",
     "GetMigrationWorkflowTemplateRequestRequestTypeDef",
     "TemplateInputTypeDef",
     "GetTemplateStepGroupRequestRequestTypeDef",
     "GetTemplateStepRequestRequestTypeDef",
     "StepOutputTypeDef",
     "GetWorkflowStepGroupRequestRequestTypeDef",
     "GetWorkflowStepRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
     "ListMigrationWorkflowTemplatesRequestRequestTypeDef",
     "TemplateSummaryTypeDef",
+    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListMigrationWorkflowsRequestRequestTypeDef",
     "MigrationWorkflowSummaryTypeDef",
+    "ListPluginsRequestListPluginsPaginateTypeDef",
     "ListPluginsRequestRequestTypeDef",
     "PluginSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
     "ListTemplateStepGroupsRequestRequestTypeDef",
     "TemplateStepGroupSummaryTypeDef",
+    "ListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
     "ListTemplateStepsRequestRequestTypeDef",
     "TemplateStepSummaryTypeDef",
+    "ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
     "ListWorkflowStepGroupsRequestRequestTypeDef",
     "WorkflowStepGroupSummaryTypeDef",
+    "ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
     "ListWorkflowStepsRequestRequestTypeDef",
     "WorkflowStepSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "PlatformCommandTypeDef",
     "PlatformScriptKeyTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryWorkflowStepRequestRequestTypeDef",
+    "RetryWorkflowStepResponseTypeDef",
     "StartMigrationWorkflowRequestRequestTypeDef",
+    "StartMigrationWorkflowResponseTypeDef",
     "StopMigrationWorkflowRequestRequestTypeDef",
+    "StopMigrationWorkflowResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateWorkflowStepGroupRequestRequestTypeDef",
+    "UpdateWorkflowStepResponseTypeDef",
     "WorkflowStepOutputUnionTypeDef",
     "CreateMigrationWorkflowRequestRequestTypeDef",
-    "UpdateMigrationWorkflowRequestRequestTypeDef",
     "CreateMigrationWorkflowResponseTypeDef",
-    "CreateWorkflowStepResponseTypeDef",
-    "DeleteMigrationWorkflowResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RetryWorkflowStepResponseTypeDef",
-    "StartMigrationWorkflowResponseTypeDef",
-    "StopMigrationWorkflowResponseTypeDef",
+    "UpdateMigrationWorkflowRequestRequestTypeDef",
     "UpdateMigrationWorkflowResponseTypeDef",
-    "UpdateWorkflowStepResponseTypeDef",
     "CreateWorkflowStepGroupResponseTypeDef",
     "GetMigrationWorkflowResponseTypeDef",
     "GetTemplateStepGroupResponseTypeDef",
     "GetWorkflowStepGroupResponseTypeDef",
     "UpdateWorkflowStepGroupResponseTypeDef",
     "GetMigrationWorkflowTemplateResponseTypeDef",
-    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
-    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
-    "ListPluginsRequestListPluginsPaginateTypeDef",
-    "ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
-    "ListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
-    "ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
-    "ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
     "ListMigrationWorkflowTemplatesResponseTypeDef",
     "ListMigrationWorkflowsResponseTypeDef",
     "ListPluginsResponseTypeDef",
     "ListTemplateStepGroupsResponseTypeDef",
     "ListTemplateStepsResponseTypeDef",
     "ListWorkflowStepGroupsResponseTypeDef",
     "ListWorkflowStepsResponseTypeDef",
@@ -125,25 +125,14 @@
         "stringValue": str,
         "listOfStringsValue": Sequence[str],
         "mapOfStringValue": Mapping[str, str],
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
 _RequiredCreateWorkflowStepGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowStepGroupRequestRequestTypeDef",
     {
         "workflowId": str,
         "name": str,
     },
 )
@@ -170,21 +159,42 @@
     {
         "name": str,
         "url": str,
     },
     total=False,
 )
 
+CreateWorkflowStepResponseTypeDef = TypedDict(
+    "CreateWorkflowStepResponseTypeDef",
+    {
+        "id": str,
+        "stepGroupId": str,
+        "workflowId": str,
+        "name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMigrationWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteMigrationWorkflowResponseTypeDef = TypedDict(
+    "DeleteMigrationWorkflowResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkflowStepGroupRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowStepGroupRequestRequestTypeDef",
     {
         "workflowId": str,
         "id": str,
     },
 )
@@ -262,20 +272,19 @@
     {
         "workflowId": str,
         "stepGroupId": str,
         "id": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
+    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListMigrationWorkflowTemplatesRequestRequestTypeDef = TypedDict(
     "ListMigrationWorkflowTemplatesRequestRequestTypeDef",
     {
@@ -293,14 +302,26 @@
         "name": str,
         "arn": str,
         "description": str,
     },
     total=False,
 )
 
+ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
+    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
+    {
+        "templateId": str,
+        "adsApplicationConfigurationName": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMigrationWorkflowsRequestRequestTypeDef = TypedDict(
     "ListMigrationWorkflowsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "templateId": str,
         "adsApplicationConfigurationName": str,
@@ -323,14 +344,22 @@
         "statusMessage": str,
         "completedSteps": int,
         "totalSteps": int,
     },
     total=False,
 )
 
+ListPluginsRequestListPluginsPaginateTypeDef = TypedDict(
+    "ListPluginsRequestListPluginsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPluginsRequestRequestTypeDef = TypedDict(
     "ListPluginsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -352,14 +381,44 @@
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
+_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
+    {
+        "templateId": str,
+    },
+)
+_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef(
+    _RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
+    _OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTemplateStepGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplateStepGroupsRequestRequestTypeDef",
     {
         "templateId": str,
     },
 )
 _OptionalListTemplateStepGroupsRequestRequestTypeDef = TypedDict(
@@ -386,14 +445,37 @@
         "name": str,
         "previous": List[str],
         "next": List[str],
     },
     total=False,
 )
 
+_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
+    "_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
+    {
+        "templateId": str,
+        "stepGroupId": str,
+    },
+)
+_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
+    "_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTemplateStepsRequestListTemplateStepsPaginateTypeDef(
+    _RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
+    _OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTemplateStepsRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplateStepsRequestRequestTypeDef",
     {
         "templateId": str,
         "stepGroupId": str,
     },
 )
@@ -425,14 +507,36 @@
         "owner": OwnerType,
         "previous": List[str],
         "next": List[str],
     },
     total=False,
 )
 
+_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
+    {
+        "workflowId": str,
+    },
+)
+_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef(
+    _RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
+    _OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListWorkflowStepGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkflowStepGroupsRequestRequestTypeDef",
     {
         "workflowId": str,
     },
 )
 _OptionalListWorkflowStepGroupsRequestRequestTypeDef = TypedDict(
@@ -461,14 +565,37 @@
         "status": StepGroupStatusType,
         "previous": List[str],
         "next": List[str],
     },
     total=False,
 )
 
+_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
+    "_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
+    {
+        "workflowId": str,
+        "stepGroupId": str,
+    },
+)
+_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
+    "_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef(
+    _RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
+    _OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListWorkflowStepsRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkflowStepsRequestRequestTypeDef",
     {
         "workflowId": str,
         "stepGroupId": str,
     },
 )
@@ -504,14 +631,24 @@
         "totalNoOfSrv": int,
         "description": str,
         "scriptLocation": str,
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
 PlatformCommandTypeDef = TypedDict(
     "PlatformCommandTypeDef",
     {
         "linux": str,
         "windows": str,
     },
     total=False,
@@ -522,37 +659,83 @@
     {
         "linux": str,
         "windows": str,
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
 RetryWorkflowStepRequestRequestTypeDef = TypedDict(
     "RetryWorkflowStepRequestRequestTypeDef",
     {
         "workflowId": str,
         "stepGroupId": str,
         "id": str,
     },
 )
 
+RetryWorkflowStepResponseTypeDef = TypedDict(
+    "RetryWorkflowStepResponseTypeDef",
+    {
+        "stepGroupId": str,
+        "workflowId": str,
+        "id": str,
+        "status": StepStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMigrationWorkflowRequestRequestTypeDef = TypedDict(
     "StartMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+StartMigrationWorkflowResponseTypeDef = TypedDict(
+    "StartMigrationWorkflowResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "statusMessage": str,
+        "lastStartTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopMigrationWorkflowRequestRequestTypeDef = TypedDict(
     "StopMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+StopMigrationWorkflowResponseTypeDef = TypedDict(
+    "StopMigrationWorkflowResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "statusMessage": str,
+        "lastStopTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -587,14 +770,25 @@
 class UpdateWorkflowStepGroupRequestRequestTypeDef(
     _RequiredUpdateWorkflowStepGroupRequestRequestTypeDef,
     _OptionalUpdateWorkflowStepGroupRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateWorkflowStepResponseTypeDef = TypedDict(
+    "UpdateWorkflowStepResponseTypeDef",
+    {
+        "id": str,
+        "stepGroupId": str,
+        "workflowId": str,
+        "name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowStepOutputUnionTypeDef = TypedDict(
     "WorkflowStepOutputUnionTypeDef",
     {
         "integerValue": int,
         "stringValue": str,
         "listOfStringValue": Sequence[str],
     },
@@ -624,120 +818,56 @@
 class CreateMigrationWorkflowRequestRequestTypeDef(
     _RequiredCreateMigrationWorkflowRequestRequestTypeDef,
     _OptionalCreateMigrationWorkflowRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateMigrationWorkflowRequestRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateMigrationWorkflowRequestRequestTypeDef",
-    {
-        "name": str,
-        "description": str,
-        "inputParameters": Mapping[str, StepInputTypeDef],
-        "stepTargets": Sequence[str],
-    },
-    total=False,
-)
-
-
-class UpdateMigrationWorkflowRequestRequestTypeDef(
-    _RequiredUpdateMigrationWorkflowRequestRequestTypeDef,
-    _OptionalUpdateMigrationWorkflowRequestRequestTypeDef,
-):
-    pass
-
-
 CreateMigrationWorkflowResponseTypeDef = TypedDict(
     "CreateMigrationWorkflowResponseTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
         "description": str,
         "templateId": str,
         "adsApplicationConfigurationId": str,
         "workflowInputs": Dict[str, StepInputTypeDef],
         "stepTargets": List[str],
         "status": MigrationWorkflowStatusEnumType,
         "creationTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowStepResponseTypeDef = TypedDict(
-    "CreateWorkflowStepResponseTypeDef",
-    {
-        "id": str,
-        "stepGroupId": str,
-        "workflowId": str,
-        "name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteMigrationWorkflowResponseTypeDef = TypedDict(
-    "DeleteMigrationWorkflowResponseTypeDef",
+_RequiredUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
-        "arn": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateMigrationWorkflowRequestRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
+        "description": str,
+        "inputParameters": Mapping[str, StepInputTypeDef],
+        "stepTargets": Sequence[str],
     },
+    total=False,
 )
 
-RetryWorkflowStepResponseTypeDef = TypedDict(
-    "RetryWorkflowStepResponseTypeDef",
-    {
-        "stepGroupId": str,
-        "workflowId": str,
-        "id": str,
-        "status": StepStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-StartMigrationWorkflowResponseTypeDef = TypedDict(
-    "StartMigrationWorkflowResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "statusMessage": str,
-        "lastStartTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateMigrationWorkflowRequestRequestTypeDef(
+    _RequiredUpdateMigrationWorkflowRequestRequestTypeDef,
+    _OptionalUpdateMigrationWorkflowRequestRequestTypeDef,
+):
+    pass
 
-StopMigrationWorkflowResponseTypeDef = TypedDict(
-    "StopMigrationWorkflowResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "statusMessage": str,
-        "lastStopTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 UpdateMigrationWorkflowResponseTypeDef = TypedDict(
     "UpdateMigrationWorkflowResponseTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
@@ -746,41 +876,30 @@
         "adsApplicationConfigurationId": str,
         "workflowInputs": Dict[str, StepInputTypeDef],
         "stepTargets": List[str],
         "status": MigrationWorkflowStatusEnumType,
         "creationTime": datetime,
         "lastModifiedTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateWorkflowStepResponseTypeDef = TypedDict(
-    "UpdateWorkflowStepResponseTypeDef",
-    {
-        "id": str,
-        "stepGroupId": str,
-        "workflowId": str,
-        "name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateWorkflowStepGroupResponseTypeDef = TypedDict(
     "CreateWorkflowStepGroupResponseTypeDef",
     {
         "workflowId": str,
         "name": str,
         "id": str,
         "description": str,
         "tools": List[ToolTypeDef],
         "next": List[str],
         "previous": List[str],
         "creationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationWorkflowResponseTypeDef = TypedDict(
     "GetMigrationWorkflowResponseTypeDef",
     {
         "id": str,
@@ -799,15 +918,15 @@
         "endTime": datetime,
         "tools": List[ToolTypeDef],
         "totalSteps": int,
         "completedSteps": int,
         "workflowInputs": Dict[str, StepInputTypeDef],
         "tags": Dict[str, str],
         "workflowBucket": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateStepGroupResponseTypeDef = TypedDict(
     "GetTemplateStepGroupResponseTypeDef",
     {
         "templateId": str,
@@ -816,15 +935,15 @@
         "description": str,
         "status": StepGroupStatusType,
         "creationTime": datetime,
         "lastModifiedTime": datetime,
         "tools": List[ToolTypeDef],
         "previous": List[str],
         "next": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowStepGroupResponseTypeDef = TypedDict(
     "GetWorkflowStepGroupResponseTypeDef",
     {
         "id": str,
@@ -835,226 +954,107 @@
         "owner": OwnerType,
         "creationTime": datetime,
         "lastModifiedTime": datetime,
         "endTime": datetime,
         "tools": List[ToolTypeDef],
         "previous": List[str],
         "next": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkflowStepGroupResponseTypeDef = TypedDict(
     "UpdateWorkflowStepGroupResponseTypeDef",
     {
         "workflowId": str,
         "name": str,
         "id": str,
         "description": str,
         "tools": List[ToolTypeDef],
         "next": List[str],
         "previous": List[str],
         "lastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationWorkflowTemplateResponseTypeDef = TypedDict(
     "GetMigrationWorkflowTemplateResponseTypeDef",
     {
         "id": str,
         "name": str,
         "description": str,
         "inputs": List[TemplateInputTypeDef],
         "tools": List[ToolTypeDef],
         "status": Literal["CREATED"],
         "creationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
-    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
-    {
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
-    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
-    {
-        "templateId": str,
-        "adsApplicationConfigurationName": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPluginsRequestListPluginsPaginateTypeDef = TypedDict(
-    "ListPluginsRequestListPluginsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
-    {
-        "templateId": str,
-    },
-)
-_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef(
-    _RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-    _OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
-    "_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
-    {
-        "templateId": str,
-        "stepGroupId": str,
-    },
-)
-_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
-    "_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTemplateStepsRequestListTemplateStepsPaginateTypeDef(
-    _RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-    _OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
-    {
-        "workflowId": str,
-    },
-)
-_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef(
-    _RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-    _OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
-    "_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
-    {
-        "workflowId": str,
-        "stepGroupId": str,
-    },
-)
-_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
-    "_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef(
-    _RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
-    _OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
-):
-    pass
-
-
 ListMigrationWorkflowTemplatesResponseTypeDef = TypedDict(
     "ListMigrationWorkflowTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "templateSummary": List[TemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMigrationWorkflowsResponseTypeDef = TypedDict(
     "ListMigrationWorkflowsResponseTypeDef",
     {
         "nextToken": str,
         "migrationWorkflowSummary": List[MigrationWorkflowSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPluginsResponseTypeDef = TypedDict(
     "ListPluginsResponseTypeDef",
     {
         "nextToken": str,
         "plugins": List[PluginSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplateStepGroupsResponseTypeDef = TypedDict(
     "ListTemplateStepGroupsResponseTypeDef",
     {
         "nextToken": str,
         "templateStepGroupSummary": List[TemplateStepGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplateStepsResponseTypeDef = TypedDict(
     "ListTemplateStepsResponseTypeDef",
     {
         "nextToken": str,
         "templateStepSummaryList": List[TemplateStepSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkflowStepGroupsResponseTypeDef = TypedDict(
     "ListWorkflowStepGroupsResponseTypeDef",
     {
         "nextToken": str,
         "workflowStepGroupsSummary": List[WorkflowStepGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkflowStepsResponseTypeDef = TypedDict(
     "ListWorkflowStepsResponseTypeDef",
     {
         "nextToken": str,
         "workflowStepsSummary": List[WorkflowStepSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StepAutomationConfigurationTypeDef = TypedDict(
     "StepAutomationConfigurationTypeDef",
     {
         "scriptLocationS3Bucket": str,
@@ -1099,15 +1099,15 @@
         "description": str,
         "stepActionType": StepActionTypeType,
         "creationTime": str,
         "previous": List[str],
         "next": List[str],
         "outputs": List[StepOutputTypeDef],
         "stepAutomationConfiguration": StepAutomationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkflowStepRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowStepRequestRequestTypeDef",
     {
         "name": str,
@@ -1157,15 +1157,15 @@
         "scriptOutputLocation": str,
         "creationTime": datetime,
         "lastStartTime": datetime,
         "endTime": datetime,
         "noOfSrvCompleted": int,
         "noOfSrvFailed": int,
         "totalNoOfSrv": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateWorkflowStepRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkflowStepRequestRequestTypeDef",
     {
         "id": str,
```

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator/type_defs.pyi` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator/type_defs.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -34,77 +34,77 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "StepInputTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateWorkflowStepGroupRequestRequestTypeDef",
     "ToolTypeDef",
+    "CreateWorkflowStepResponseTypeDef",
     "DeleteMigrationWorkflowRequestRequestTypeDef",
+    "DeleteMigrationWorkflowResponseTypeDef",
     "DeleteWorkflowStepGroupRequestRequestTypeDef",
     "DeleteWorkflowStepRequestRequestTypeDef",
     "GetMigrationWorkflowRequestRequestTypeDef",
     "GetMigrationWorkflowTemplateRequestRequestTypeDef",
     "TemplateInputTypeDef",
     "GetTemplateStepGroupRequestRequestTypeDef",
     "GetTemplateStepRequestRequestTypeDef",
     "StepOutputTypeDef",
     "GetWorkflowStepGroupRequestRequestTypeDef",
     "GetWorkflowStepRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
     "ListMigrationWorkflowTemplatesRequestRequestTypeDef",
     "TemplateSummaryTypeDef",
+    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
     "ListMigrationWorkflowsRequestRequestTypeDef",
     "MigrationWorkflowSummaryTypeDef",
+    "ListPluginsRequestListPluginsPaginateTypeDef",
     "ListPluginsRequestRequestTypeDef",
     "PluginSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
     "ListTemplateStepGroupsRequestRequestTypeDef",
     "TemplateStepGroupSummaryTypeDef",
+    "ListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
     "ListTemplateStepsRequestRequestTypeDef",
     "TemplateStepSummaryTypeDef",
+    "ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
     "ListWorkflowStepGroupsRequestRequestTypeDef",
     "WorkflowStepGroupSummaryTypeDef",
+    "ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
     "ListWorkflowStepsRequestRequestTypeDef",
     "WorkflowStepSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "PlatformCommandTypeDef",
     "PlatformScriptKeyTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryWorkflowStepRequestRequestTypeDef",
+    "RetryWorkflowStepResponseTypeDef",
     "StartMigrationWorkflowRequestRequestTypeDef",
+    "StartMigrationWorkflowResponseTypeDef",
     "StopMigrationWorkflowRequestRequestTypeDef",
+    "StopMigrationWorkflowResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateWorkflowStepGroupRequestRequestTypeDef",
+    "UpdateWorkflowStepResponseTypeDef",
     "WorkflowStepOutputUnionTypeDef",
     "CreateMigrationWorkflowRequestRequestTypeDef",
-    "UpdateMigrationWorkflowRequestRequestTypeDef",
     "CreateMigrationWorkflowResponseTypeDef",
-    "CreateWorkflowStepResponseTypeDef",
-    "DeleteMigrationWorkflowResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RetryWorkflowStepResponseTypeDef",
-    "StartMigrationWorkflowResponseTypeDef",
-    "StopMigrationWorkflowResponseTypeDef",
+    "UpdateMigrationWorkflowRequestRequestTypeDef",
     "UpdateMigrationWorkflowResponseTypeDef",
-    "UpdateWorkflowStepResponseTypeDef",
     "CreateWorkflowStepGroupResponseTypeDef",
     "GetMigrationWorkflowResponseTypeDef",
     "GetTemplateStepGroupResponseTypeDef",
     "GetWorkflowStepGroupResponseTypeDef",
     "UpdateWorkflowStepGroupResponseTypeDef",
     "GetMigrationWorkflowTemplateResponseTypeDef",
-    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
-    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
-    "ListPluginsRequestListPluginsPaginateTypeDef",
-    "ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
-    "ListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
-    "ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
-    "ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
     "ListMigrationWorkflowTemplatesResponseTypeDef",
     "ListMigrationWorkflowsResponseTypeDef",
     "ListPluginsResponseTypeDef",
     "ListTemplateStepGroupsResponseTypeDef",
     "ListTemplateStepsResponseTypeDef",
     "ListWorkflowStepGroupsResponseTypeDef",
     "ListWorkflowStepsResponseTypeDef",
@@ -124,25 +124,14 @@
         "stringValue": str,
         "listOfStringsValue": Sequence[str],
         "mapOfStringValue": Mapping[str, str],
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
 _RequiredCreateWorkflowStepGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowStepGroupRequestRequestTypeDef",
     {
         "workflowId": str,
         "name": str,
     },
 )
@@ -167,21 +156,42 @@
     {
         "name": str,
         "url": str,
     },
     total=False,
 )
 
+CreateWorkflowStepResponseTypeDef = TypedDict(
+    "CreateWorkflowStepResponseTypeDef",
+    {
+        "id": str,
+        "stepGroupId": str,
+        "workflowId": str,
+        "name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMigrationWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteMigrationWorkflowResponseTypeDef = TypedDict(
+    "DeleteMigrationWorkflowResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkflowStepGroupRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowStepGroupRequestRequestTypeDef",
     {
         "workflowId": str,
         "id": str,
     },
 )
@@ -259,20 +269,19 @@
     {
         "workflowId": str,
         "stepGroupId": str,
         "id": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
+    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListMigrationWorkflowTemplatesRequestRequestTypeDef = TypedDict(
     "ListMigrationWorkflowTemplatesRequestRequestTypeDef",
     {
@@ -290,14 +299,26 @@
         "name": str,
         "arn": str,
         "description": str,
     },
     total=False,
 )
 
+ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
+    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
+    {
+        "templateId": str,
+        "adsApplicationConfigurationName": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMigrationWorkflowsRequestRequestTypeDef = TypedDict(
     "ListMigrationWorkflowsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "templateId": str,
         "adsApplicationConfigurationName": str,
@@ -320,14 +341,22 @@
         "statusMessage": str,
         "completedSteps": int,
         "totalSteps": int,
     },
     total=False,
 )
 
+ListPluginsRequestListPluginsPaginateTypeDef = TypedDict(
+    "ListPluginsRequestListPluginsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPluginsRequestRequestTypeDef = TypedDict(
     "ListPluginsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -349,14 +378,42 @@
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
+_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
+    {
+        "templateId": str,
+    },
+)
+_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef(
+    _RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
+    _OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListTemplateStepGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplateStepGroupsRequestRequestTypeDef",
     {
         "templateId": str,
     },
 )
 _OptionalListTemplateStepGroupsRequestRequestTypeDef = TypedDict(
@@ -381,14 +438,35 @@
         "name": str,
         "previous": List[str],
         "next": List[str],
     },
     total=False,
 )
 
+_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
+    "_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
+    {
+        "templateId": str,
+        "stepGroupId": str,
+    },
+)
+_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
+    "_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTemplateStepsRequestListTemplateStepsPaginateTypeDef(
+    _RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
+    _OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
+):
+    pass
+
 _RequiredListTemplateStepsRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplateStepsRequestRequestTypeDef",
     {
         "templateId": str,
         "stepGroupId": str,
     },
 )
@@ -418,14 +496,34 @@
         "owner": OwnerType,
         "previous": List[str],
         "next": List[str],
     },
     total=False,
 )
 
+_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
+    {
+        "workflowId": str,
+    },
+)
+_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef(
+    _RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
+    _OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListWorkflowStepGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkflowStepGroupsRequestRequestTypeDef",
     {
         "workflowId": str,
     },
 )
 _OptionalListWorkflowStepGroupsRequestRequestTypeDef = TypedDict(
@@ -452,14 +550,35 @@
         "status": StepGroupStatusType,
         "previous": List[str],
         "next": List[str],
     },
     total=False,
 )
 
+_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
+    "_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
+    {
+        "workflowId": str,
+        "stepGroupId": str,
+    },
+)
+_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
+    "_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef(
+    _RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
+    _OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
+):
+    pass
+
 _RequiredListWorkflowStepsRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkflowStepsRequestRequestTypeDef",
     {
         "workflowId": str,
         "stepGroupId": str,
     },
 )
@@ -493,14 +612,24 @@
         "totalNoOfSrv": int,
         "description": str,
         "scriptLocation": str,
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
 PlatformCommandTypeDef = TypedDict(
     "PlatformCommandTypeDef",
     {
         "linux": str,
         "windows": str,
     },
     total=False,
@@ -511,37 +640,83 @@
     {
         "linux": str,
         "windows": str,
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
 RetryWorkflowStepRequestRequestTypeDef = TypedDict(
     "RetryWorkflowStepRequestRequestTypeDef",
     {
         "workflowId": str,
         "stepGroupId": str,
         "id": str,
     },
 )
 
+RetryWorkflowStepResponseTypeDef = TypedDict(
+    "RetryWorkflowStepResponseTypeDef",
+    {
+        "stepGroupId": str,
+        "workflowId": str,
+        "id": str,
+        "status": StepStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMigrationWorkflowRequestRequestTypeDef = TypedDict(
     "StartMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+StartMigrationWorkflowResponseTypeDef = TypedDict(
+    "StartMigrationWorkflowResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "statusMessage": str,
+        "lastStartTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopMigrationWorkflowRequestRequestTypeDef = TypedDict(
     "StopMigrationWorkflowRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+StopMigrationWorkflowResponseTypeDef = TypedDict(
+    "StopMigrationWorkflowResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "status": MigrationWorkflowStatusEnumType,
+        "statusMessage": str,
+        "lastStopTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -574,14 +749,25 @@
 
 class UpdateWorkflowStepGroupRequestRequestTypeDef(
     _RequiredUpdateWorkflowStepGroupRequestRequestTypeDef,
     _OptionalUpdateWorkflowStepGroupRequestRequestTypeDef,
 ):
     pass
 
+UpdateWorkflowStepResponseTypeDef = TypedDict(
+    "UpdateWorkflowStepResponseTypeDef",
+    {
+        "id": str,
+        "stepGroupId": str,
+        "workflowId": str,
+        "name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowStepOutputUnionTypeDef = TypedDict(
     "WorkflowStepOutputUnionTypeDef",
     {
         "integerValue": int,
         "stringValue": str,
         "listOfStringValue": Sequence[str],
     },
@@ -609,118 +795,54 @@
 
 class CreateMigrationWorkflowRequestRequestTypeDef(
     _RequiredCreateMigrationWorkflowRequestRequestTypeDef,
     _OptionalCreateMigrationWorkflowRequestRequestTypeDef,
 ):
     pass
 
-_RequiredUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateMigrationWorkflowRequestRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateMigrationWorkflowRequestRequestTypeDef",
-    {
-        "name": str,
-        "description": str,
-        "inputParameters": Mapping[str, StepInputTypeDef],
-        "stepTargets": Sequence[str],
-    },
-    total=False,
-)
-
-class UpdateMigrationWorkflowRequestRequestTypeDef(
-    _RequiredUpdateMigrationWorkflowRequestRequestTypeDef,
-    _OptionalUpdateMigrationWorkflowRequestRequestTypeDef,
-):
-    pass
-
 CreateMigrationWorkflowResponseTypeDef = TypedDict(
     "CreateMigrationWorkflowResponseTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
         "description": str,
         "templateId": str,
         "adsApplicationConfigurationId": str,
         "workflowInputs": Dict[str, StepInputTypeDef],
         "stepTargets": List[str],
         "status": MigrationWorkflowStatusEnumType,
         "creationTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowStepResponseTypeDef = TypedDict(
-    "CreateWorkflowStepResponseTypeDef",
-    {
-        "id": str,
-        "stepGroupId": str,
-        "workflowId": str,
-        "name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMigrationWorkflowResponseTypeDef = TypedDict(
-    "DeleteMigrationWorkflowResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RetryWorkflowStepResponseTypeDef = TypedDict(
-    "RetryWorkflowStepResponseTypeDef",
+_RequiredUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateMigrationWorkflowRequestRequestTypeDef",
     {
-        "stepGroupId": str,
-        "workflowId": str,
         "id": str,
-        "status": StepStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-StartMigrationWorkflowResponseTypeDef = TypedDict(
-    "StartMigrationWorkflowResponseTypeDef",
+_OptionalUpdateMigrationWorkflowRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateMigrationWorkflowRequestRequestTypeDef",
     {
-        "id": str,
-        "arn": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "statusMessage": str,
-        "lastStartTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "name": str,
+        "description": str,
+        "inputParameters": Mapping[str, StepInputTypeDef],
+        "stepTargets": Sequence[str],
     },
+    total=False,
 )
 
-StopMigrationWorkflowResponseTypeDef = TypedDict(
-    "StopMigrationWorkflowResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "statusMessage": str,
-        "lastStopTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateMigrationWorkflowRequestRequestTypeDef(
+    _RequiredUpdateMigrationWorkflowRequestRequestTypeDef,
+    _OptionalUpdateMigrationWorkflowRequestRequestTypeDef,
+):
+    pass
 
 UpdateMigrationWorkflowResponseTypeDef = TypedDict(
     "UpdateMigrationWorkflowResponseTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
@@ -729,41 +851,30 @@
         "adsApplicationConfigurationId": str,
         "workflowInputs": Dict[str, StepInputTypeDef],
         "stepTargets": List[str],
         "status": MigrationWorkflowStatusEnumType,
         "creationTime": datetime,
         "lastModifiedTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateWorkflowStepResponseTypeDef = TypedDict(
-    "UpdateWorkflowStepResponseTypeDef",
-    {
-        "id": str,
-        "stepGroupId": str,
-        "workflowId": str,
-        "name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateWorkflowStepGroupResponseTypeDef = TypedDict(
     "CreateWorkflowStepGroupResponseTypeDef",
     {
         "workflowId": str,
         "name": str,
         "id": str,
         "description": str,
         "tools": List[ToolTypeDef],
         "next": List[str],
         "previous": List[str],
         "creationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationWorkflowResponseTypeDef = TypedDict(
     "GetMigrationWorkflowResponseTypeDef",
     {
         "id": str,
@@ -782,15 +893,15 @@
         "endTime": datetime,
         "tools": List[ToolTypeDef],
         "totalSteps": int,
         "completedSteps": int,
         "workflowInputs": Dict[str, StepInputTypeDef],
         "tags": Dict[str, str],
         "workflowBucket": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTemplateStepGroupResponseTypeDef = TypedDict(
     "GetTemplateStepGroupResponseTypeDef",
     {
         "templateId": str,
@@ -799,15 +910,15 @@
         "description": str,
         "status": StepGroupStatusType,
         "creationTime": datetime,
         "lastModifiedTime": datetime,
         "tools": List[ToolTypeDef],
         "previous": List[str],
         "next": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowStepGroupResponseTypeDef = TypedDict(
     "GetWorkflowStepGroupResponseTypeDef",
     {
         "id": str,
@@ -818,218 +929,107 @@
         "owner": OwnerType,
         "creationTime": datetime,
         "lastModifiedTime": datetime,
         "endTime": datetime,
         "tools": List[ToolTypeDef],
         "previous": List[str],
         "next": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkflowStepGroupResponseTypeDef = TypedDict(
     "UpdateWorkflowStepGroupResponseTypeDef",
     {
         "workflowId": str,
         "name": str,
         "id": str,
         "description": str,
         "tools": List[ToolTypeDef],
         "next": List[str],
         "previous": List[str],
         "lastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationWorkflowTemplateResponseTypeDef = TypedDict(
     "GetMigrationWorkflowTemplateResponseTypeDef",
     {
         "id": str,
         "name": str,
         "description": str,
         "inputs": List[TemplateInputTypeDef],
         "tools": List[ToolTypeDef],
         "status": Literal["CREATED"],
         "creationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
-    "ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef",
-    {
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef = TypedDict(
-    "ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef",
-    {
-        "templateId": str,
-        "adsApplicationConfigurationName": str,
-        "status": MigrationWorkflowStatusEnumType,
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListPluginsRequestListPluginsPaginateTypeDef = TypedDict(
-    "ListPluginsRequestListPluginsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
-    {
-        "templateId": str,
-    },
-)
-_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef(
-    _RequiredListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-    _OptionalListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
-    "_RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
-    {
-        "templateId": str,
-        "stepGroupId": str,
-    },
-)
-_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef = TypedDict(
-    "_OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTemplateStepsRequestListTemplateStepsPaginateTypeDef(
-    _RequiredListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-    _OptionalListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-):
-    pass
-
-_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
-    {
-        "workflowId": str,
-    },
-)
-_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef(
-    _RequiredListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-    _OptionalListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
-    "_RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
-    {
-        "workflowId": str,
-        "stepGroupId": str,
-    },
-)
-_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef = TypedDict(
-    "_OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef(
-    _RequiredListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
-    _OptionalListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
-):
-    pass
-
 ListMigrationWorkflowTemplatesResponseTypeDef = TypedDict(
     "ListMigrationWorkflowTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "templateSummary": List[TemplateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMigrationWorkflowsResponseTypeDef = TypedDict(
     "ListMigrationWorkflowsResponseTypeDef",
     {
         "nextToken": str,
         "migrationWorkflowSummary": List[MigrationWorkflowSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPluginsResponseTypeDef = TypedDict(
     "ListPluginsResponseTypeDef",
     {
         "nextToken": str,
         "plugins": List[PluginSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplateStepGroupsResponseTypeDef = TypedDict(
     "ListTemplateStepGroupsResponseTypeDef",
     {
         "nextToken": str,
         "templateStepGroupSummary": List[TemplateStepGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplateStepsResponseTypeDef = TypedDict(
     "ListTemplateStepsResponseTypeDef",
     {
         "nextToken": str,
         "templateStepSummaryList": List[TemplateStepSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkflowStepGroupsResponseTypeDef = TypedDict(
     "ListWorkflowStepGroupsResponseTypeDef",
     {
         "nextToken": str,
         "workflowStepGroupsSummary": List[WorkflowStepGroupSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkflowStepsResponseTypeDef = TypedDict(
     "ListWorkflowStepsResponseTypeDef",
     {
         "nextToken": str,
         "workflowStepsSummary": List[WorkflowStepSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StepAutomationConfigurationTypeDef = TypedDict(
     "StepAutomationConfigurationTypeDef",
     {
         "scriptLocationS3Bucket": str,
@@ -1074,15 +1074,15 @@
         "description": str,
         "stepActionType": StepActionTypeType,
         "creationTime": str,
         "previous": List[str],
         "next": List[str],
         "outputs": List[StepOutputTypeDef],
         "stepAutomationConfiguration": StepAutomationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkflowStepRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowStepRequestRequestTypeDef",
     {
         "name": str,
@@ -1130,15 +1130,15 @@
         "scriptOutputLocation": str,
         "creationTime": datetime,
         "lastStartTime": datetime,
         "endTime": datetime,
         "noOfSrvCompleted": int,
         "noOfSrvFailed": int,
         "totalNoOfSrv": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateWorkflowStepRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkflowStepRequestRequestTypeDef",
     {
         "id": str,
```

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/PKG-INFO` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migrationhuborchestrator
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubOrchestrator 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migrationhuborchestrator"></a>
 
 # types-aiobotocore-migrationhuborchestrator
 
 [![PyPI - types-aiobotocore-migrationhuborchestrator](https://img.shields.io/pypi/v/types-aiobotocore-migrationhuborchestrator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhuborchestrator)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhuborchestrator.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhuborchestrator)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhuborchestrator?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhuborchestrator)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubOrchestrator 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator)
+[aiobotocore.MigrationHubOrchestrator 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhuborchestrator.html#MigrationHubOrchestrator)
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
 [types-aiobotocore-migrationhuborchestrator docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhuborchestrator/).
 
 See how it helps to find and fix potential bugs:
 
@@ -354,77 +354,77 @@
 `types_aiobotocore_migrationhuborchestrator.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_migrationhuborchestrator.type_defs import (
     StepInputTypeDef,
-    ResponseMetadataTypeDef,
     CreateWorkflowStepGroupRequestRequestTypeDef,
     ToolTypeDef,
+    CreateWorkflowStepResponseTypeDef,
     DeleteMigrationWorkflowRequestRequestTypeDef,
+    DeleteMigrationWorkflowResponseTypeDef,
     DeleteWorkflowStepGroupRequestRequestTypeDef,
     DeleteWorkflowStepRequestRequestTypeDef,
     GetMigrationWorkflowRequestRequestTypeDef,
     GetMigrationWorkflowTemplateRequestRequestTypeDef,
     TemplateInputTypeDef,
     GetTemplateStepGroupRequestRequestTypeDef,
     GetTemplateStepRequestRequestTypeDef,
     StepOutputTypeDef,
     GetWorkflowStepGroupRequestRequestTypeDef,
     GetWorkflowStepRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef,
     ListMigrationWorkflowTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
+    ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef,
     ListMigrationWorkflowsRequestRequestTypeDef,
     MigrationWorkflowSummaryTypeDef,
+    ListPluginsRequestListPluginsPaginateTypeDef,
     ListPluginsRequestRequestTypeDef,
     PluginSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
     ListTemplateStepGroupsRequestRequestTypeDef,
     TemplateStepGroupSummaryTypeDef,
+    ListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
     ListTemplateStepsRequestRequestTypeDef,
     TemplateStepSummaryTypeDef,
+    ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
     ListWorkflowStepGroupsRequestRequestTypeDef,
     WorkflowStepGroupSummaryTypeDef,
+    ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
     ListWorkflowStepsRequestRequestTypeDef,
     WorkflowStepSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PlatformCommandTypeDef,
     PlatformScriptKeyTypeDef,
+    ResponseMetadataTypeDef,
     RetryWorkflowStepRequestRequestTypeDef,
+    RetryWorkflowStepResponseTypeDef,
     StartMigrationWorkflowRequestRequestTypeDef,
+    StartMigrationWorkflowResponseTypeDef,
     StopMigrationWorkflowRequestRequestTypeDef,
+    StopMigrationWorkflowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateWorkflowStepGroupRequestRequestTypeDef,
+    UpdateWorkflowStepResponseTypeDef,
     WorkflowStepOutputUnionTypeDef,
     CreateMigrationWorkflowRequestRequestTypeDef,
-    UpdateMigrationWorkflowRequestRequestTypeDef,
     CreateMigrationWorkflowResponseTypeDef,
-    CreateWorkflowStepResponseTypeDef,
-    DeleteMigrationWorkflowResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RetryWorkflowStepResponseTypeDef,
-    StartMigrationWorkflowResponseTypeDef,
-    StopMigrationWorkflowResponseTypeDef,
+    UpdateMigrationWorkflowRequestRequestTypeDef,
     UpdateMigrationWorkflowResponseTypeDef,
-    UpdateWorkflowStepResponseTypeDef,
     CreateWorkflowStepGroupResponseTypeDef,
     GetMigrationWorkflowResponseTypeDef,
     GetTemplateStepGroupResponseTypeDef,
     GetWorkflowStepGroupResponseTypeDef,
     UpdateWorkflowStepGroupResponseTypeDef,
     GetMigrationWorkflowTemplateResponseTypeDef,
-    ListMigrationWorkflowTemplatesRequestListTemplatesPaginateTypeDef,
-    ListMigrationWorkflowsRequestListWorkflowsPaginateTypeDef,
-    ListPluginsRequestListPluginsPaginateTypeDef,
-    ListTemplateStepGroupsRequestListTemplateStepGroupsPaginateTypeDef,
-    ListTemplateStepsRequestListTemplateStepsPaginateTypeDef,
-    ListWorkflowStepGroupsRequestListWorkflowStepGroupsPaginateTypeDef,
-    ListWorkflowStepsRequestListWorkflowStepsPaginateTypeDef,
     ListMigrationWorkflowTemplatesResponseTypeDef,
     ListMigrationWorkflowsResponseTypeDef,
     ListPluginsResponseTypeDef,
     ListTemplateStepGroupsResponseTypeDef,
     ListTemplateStepsResponseTypeDef,
     ListWorkflowStepGroupsResponseTypeDef,
     ListWorkflowStepsResponseTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-migrationhuborchestrator-2.5.0.post1/types_aiobotocore_migrationhuborchestrator.egg-info/SOURCES.txt` & `types-aiobotocore-migrationhuborchestrator-2.5.1/types_aiobotocore_migrationhuborchestrator.egg-info/SOURCES.txt`

 * *Files identical despite different names*

