# Comparing `tmp/types-aiobotocore-fis-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-fis-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-fis-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-fis-2.5.1.tar", last modified: Wed Jun 28 01:43:30 2023, max compression
```

## Comparing `types-aiobotocore-fis-2.5.0.post1.tar` & `types-aiobotocore-fis-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.079221 types-aiobotocore-fis-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14727 2023-03-11 12:26:39.079221 types-aiobotocore-fis-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13172 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.079221 types-aiobotocore-fis-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.079221 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      409 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13614 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13590 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7624 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7622 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    23891 2023-03-11 12:14:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    23868 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:37.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.079221 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14727 2023-03-11 12:26:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      666 2023-03-11 12:26:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:38.000000 types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:30.878139 types-aiobotocore-fis-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14715 2023-06-28 01:43:30.878139 types-aiobotocore-fis-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13166 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:30.878139 types-aiobotocore-fis-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:30.878139 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      409 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13614 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13590 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7833 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7831 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    23919 2023-06-28 01:31:15.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23896 2023-06-28 01:31:15.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:14.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:30.878139 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14715 2023-06-28 01:43:30.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 01:43:30.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:30.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:30.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:30.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:30.000000 types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-fis-2.5.0.post1/LICENSE` & `types-aiobotocore-fis-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-fis-2.5.0.post1/PKG-INFO` & `types-aiobotocore-fis-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-fis
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FIS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FIS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-fis"></a>
 
 # types-aiobotocore-fis
 
 [![PyPI - types-aiobotocore-fis](https://img.shields.io/pypi/v/types-aiobotocore-fis.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fis)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fis.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fis)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fis?color=blue)](https://pypistats.org/packages/types-aiobotocore-fis)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FIS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
+[aiobotocore.FIS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
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
 [types-aiobotocore-fis docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,15 +294,14 @@
 from types_aiobotocore_fis.type_defs import (
     ActionParameterTypeDef,
     ActionTargetTypeDef,
     CreateExperimentTemplateActionInputTypeDef,
     ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef,
     ExperimentTemplateS3LogConfigurationInputTypeDef,
     CreateExperimentTemplateStopConditionInputTypeDef,
-    ResponseMetadataTypeDef,
     ExperimentTemplateTargetInputFilterTypeDef,
     DeleteExperimentTemplateRequestRequestTypeDef,
     ExperimentActionStateTypeDef,
     ExperimentCloudWatchLogsLogConfigurationTypeDef,
     ExperimentS3LogConfigurationTypeDef,
     ExperimentStateTypeDef,
     ExperimentStopConditionTypeDef,
@@ -317,28 +316,29 @@
     GetExperimentRequestRequestTypeDef,
     GetExperimentTemplateRequestRequestTypeDef,
     GetTargetResourceTypeRequestRequestTypeDef,
     ListActionsRequestRequestTypeDef,
     ListExperimentTemplatesRequestRequestTypeDef,
     ListExperimentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTargetResourceTypesRequestRequestTypeDef,
     TargetResourceTypeSummaryTypeDef,
+    ResponseMetadataTypeDef,
     StartExperimentRequestRequestTypeDef,
     StopExperimentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TargetResourceTypeParameterTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateExperimentTemplateActionInputItemTypeDef,
     UpdateExperimentTemplateStopConditionInputTypeDef,
     ActionSummaryTypeDef,
     ActionTypeDef,
     CreateExperimentTemplateLogConfigurationInputTypeDef,
     UpdateExperimentTemplateLogConfigurationInputTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateExperimentTemplateTargetInputTypeDef,
     UpdateExperimentTemplateTargetInputTypeDef,
     ExperimentActionTypeDef,
     ExperimentLogConfigurationTypeDef,
     ExperimentSummaryTypeDef,
     ExperimentTargetTypeDef,
     ExperimentTemplateLogConfigurationTypeDef,
@@ -371,43 +371,43 @@
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/README.md` & `types-aiobotocore-fis-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-fis"></a>
 
 # types-aiobotocore-fis
 
 [![PyPI - types-aiobotocore-fis](https://img.shields.io/pypi/v/types-aiobotocore-fis.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fis)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fis.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fis)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fis?color=blue)](https://pypistats.org/packages/types-aiobotocore-fis)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FIS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
+[aiobotocore.FIS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
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
 [types-aiobotocore-fis docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,15 +261,14 @@
 from types_aiobotocore_fis.type_defs import (
     ActionParameterTypeDef,
     ActionTargetTypeDef,
     CreateExperimentTemplateActionInputTypeDef,
     ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef,
     ExperimentTemplateS3LogConfigurationInputTypeDef,
     CreateExperimentTemplateStopConditionInputTypeDef,
-    ResponseMetadataTypeDef,
     ExperimentTemplateTargetInputFilterTypeDef,
     DeleteExperimentTemplateRequestRequestTypeDef,
     ExperimentActionStateTypeDef,
     ExperimentCloudWatchLogsLogConfigurationTypeDef,
     ExperimentS3LogConfigurationTypeDef,
     ExperimentStateTypeDef,
     ExperimentStopConditionTypeDef,
@@ -284,28 +283,29 @@
     GetExperimentRequestRequestTypeDef,
     GetExperimentTemplateRequestRequestTypeDef,
     GetTargetResourceTypeRequestRequestTypeDef,
     ListActionsRequestRequestTypeDef,
     ListExperimentTemplatesRequestRequestTypeDef,
     ListExperimentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTargetResourceTypesRequestRequestTypeDef,
     TargetResourceTypeSummaryTypeDef,
+    ResponseMetadataTypeDef,
     StartExperimentRequestRequestTypeDef,
     StopExperimentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TargetResourceTypeParameterTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateExperimentTemplateActionInputItemTypeDef,
     UpdateExperimentTemplateStopConditionInputTypeDef,
     ActionSummaryTypeDef,
     ActionTypeDef,
     CreateExperimentTemplateLogConfigurationInputTypeDef,
     UpdateExperimentTemplateLogConfigurationInputTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateExperimentTemplateTargetInputTypeDef,
     UpdateExperimentTemplateTargetInputTypeDef,
     ExperimentActionTypeDef,
     ExperimentLogConfigurationTypeDef,
     ExperimentSummaryTypeDef,
     ExperimentTargetTypeDef,
     ExperimentTemplateLogConfigurationTypeDef,
@@ -338,43 +338,43 @@
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/setup.py` & `types-aiobotocore-fis-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-fis.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-fis",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_fis"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.FIS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.FIS 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/",
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/__main__.py` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.FIS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.FIS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS\nOther"
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/client.py` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/client.pyi` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/literals.py` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -93,14 +93,15 @@
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
@@ -179,14 +180,15 @@
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
@@ -197,14 +199,15 @@
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
@@ -240,14 +243,15 @@
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
@@ -266,16 +270,19 @@
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
@@ -359,15 +366,17 @@
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/literals.pyi` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -91,14 +91,15 @@
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
@@ -177,14 +178,15 @@
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
@@ -195,14 +197,15 @@
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
@@ -238,14 +241,15 @@
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
@@ -264,16 +268,19 @@
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
@@ -357,15 +364,17 @@
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/type_defs.py` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,15 +26,14 @@
 __all__ = (
     "ActionParameterTypeDef",
     "ActionTargetTypeDef",
     "CreateExperimentTemplateActionInputTypeDef",
     "ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef",
     "ExperimentTemplateS3LogConfigurationInputTypeDef",
     "CreateExperimentTemplateStopConditionInputTypeDef",
-    "ResponseMetadataTypeDef",
     "ExperimentTemplateTargetInputFilterTypeDef",
     "DeleteExperimentTemplateRequestRequestTypeDef",
     "ExperimentActionStateTypeDef",
     "ExperimentCloudWatchLogsLogConfigurationTypeDef",
     "ExperimentS3LogConfigurationTypeDef",
     "ExperimentStateTypeDef",
     "ExperimentStopConditionTypeDef",
@@ -49,28 +48,29 @@
     "GetExperimentRequestRequestTypeDef",
     "GetExperimentTemplateRequestRequestTypeDef",
     "GetTargetResourceTypeRequestRequestTypeDef",
     "ListActionsRequestRequestTypeDef",
     "ListExperimentTemplatesRequestRequestTypeDef",
     "ListExperimentsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListTargetResourceTypesRequestRequestTypeDef",
     "TargetResourceTypeSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "StartExperimentRequestRequestTypeDef",
     "StopExperimentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TargetResourceTypeParameterTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateExperimentTemplateActionInputItemTypeDef",
     "UpdateExperimentTemplateStopConditionInputTypeDef",
     "ActionSummaryTypeDef",
     "ActionTypeDef",
     "CreateExperimentTemplateLogConfigurationInputTypeDef",
     "UpdateExperimentTemplateLogConfigurationInputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateExperimentTemplateTargetInputTypeDef",
     "UpdateExperimentTemplateTargetInputTypeDef",
     "ExperimentActionTypeDef",
     "ExperimentLogConfigurationTypeDef",
     "ExperimentSummaryTypeDef",
     "ExperimentTargetTypeDef",
     "ExperimentTemplateLogConfigurationTypeDef",
@@ -184,25 +184,14 @@
 class CreateExperimentTemplateStopConditionInputTypeDef(
     _RequiredCreateExperimentTemplateStopConditionInputTypeDef,
     _OptionalCreateExperimentTemplateStopConditionInputTypeDef,
 ):
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
-
 ExperimentTemplateTargetInputFilterTypeDef = TypedDict(
     "ExperimentTemplateTargetInputFilterTypeDef",
     {
         "path": str,
         "values": Sequence[str],
     },
 )
@@ -384,14 +373,22 @@
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
 ListTargetResourceTypesRequestRequestTypeDef = TypedDict(
     "ListTargetResourceTypesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -402,14 +399,25 @@
     {
         "resourceType": str,
         "description": str,
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
 _RequiredStartExperimentRequestRequestTypeDef = TypedDict(
     "_RequiredStartExperimentRequestRequestTypeDef",
     {
         "clientToken": str,
         "experimentTemplateId": str,
     },
 )
@@ -559,22 +567,14 @@
         "cloudWatchLogsConfiguration": ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef,
         "s3Configuration": ExperimentTemplateS3LogConfigurationInputTypeDef,
         "logSchemaVersion": int,
     },
     total=False,
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateExperimentTemplateTargetInputTypeDef = TypedDict(
     "_RequiredCreateExperimentTemplateTargetInputTypeDef",
     {
         "resourceType": str,
         "selectionMode": str,
     },
 )
@@ -684,15 +684,15 @@
 )
 
 ListExperimentTemplatesResponseTypeDef = TypedDict(
     "ListExperimentTemplatesResponseTypeDef",
     {
         "experimentTemplates": List[ExperimentTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExperimentTemplateTargetTypeDef = TypedDict(
     "ExperimentTemplateTargetTypeDef",
     {
         "resourceType": str,
@@ -706,15 +706,15 @@
 )
 
 ListTargetResourceTypesResponseTypeDef = TypedDict(
     "ListTargetResourceTypesResponseTypeDef",
     {
         "targetResourceTypes": List[TargetResourceTypeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetResourceTypeTypeDef = TypedDict(
     "TargetResourceTypeTypeDef",
     {
         "resourceType": str,
@@ -725,23 +725,23 @@
 )
 
 ListActionsResponseTypeDef = TypedDict(
     "ListActionsResponseTypeDef",
     {
         "actions": List[ActionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetActionResponseTypeDef = TypedDict(
     "GetActionResponseTypeDef",
     {
         "action": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateExperimentTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExperimentTemplateRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -797,15 +797,15 @@
 
 
 ListExperimentsResponseTypeDef = TypedDict(
     "ListExperimentsResponseTypeDef",
     {
         "experiments": List[ExperimentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExperimentTypeDef = TypedDict(
     "ExperimentTypeDef",
     {
         "id": str,
@@ -841,66 +841,66 @@
     total=False,
 )
 
 GetTargetResourceTypeResponseTypeDef = TypedDict(
     "GetTargetResourceTypeResponseTypeDef",
     {
         "targetResourceType": TargetResourceTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExperimentResponseTypeDef = TypedDict(
     "GetExperimentResponseTypeDef",
     {
         "experiment": ExperimentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartExperimentResponseTypeDef = TypedDict(
     "StartExperimentResponseTypeDef",
     {
         "experiment": ExperimentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopExperimentResponseTypeDef = TypedDict(
     "StopExperimentResponseTypeDef",
     {
         "experiment": ExperimentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateExperimentTemplateResponseTypeDef = TypedDict(
     "CreateExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteExperimentTemplateResponseTypeDef = TypedDict(
     "DeleteExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExperimentTemplateResponseTypeDef = TypedDict(
     "GetExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateExperimentTemplateResponseTypeDef = TypedDict(
     "UpdateExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis/type_defs.pyi` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -25,15 +25,14 @@
 __all__ = (
     "ActionParameterTypeDef",
     "ActionTargetTypeDef",
     "CreateExperimentTemplateActionInputTypeDef",
     "ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef",
     "ExperimentTemplateS3LogConfigurationInputTypeDef",
     "CreateExperimentTemplateStopConditionInputTypeDef",
-    "ResponseMetadataTypeDef",
     "ExperimentTemplateTargetInputFilterTypeDef",
     "DeleteExperimentTemplateRequestRequestTypeDef",
     "ExperimentActionStateTypeDef",
     "ExperimentCloudWatchLogsLogConfigurationTypeDef",
     "ExperimentS3LogConfigurationTypeDef",
     "ExperimentStateTypeDef",
     "ExperimentStopConditionTypeDef",
@@ -48,28 +47,29 @@
     "GetExperimentRequestRequestTypeDef",
     "GetExperimentTemplateRequestRequestTypeDef",
     "GetTargetResourceTypeRequestRequestTypeDef",
     "ListActionsRequestRequestTypeDef",
     "ListExperimentTemplatesRequestRequestTypeDef",
     "ListExperimentsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListTargetResourceTypesRequestRequestTypeDef",
     "TargetResourceTypeSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "StartExperimentRequestRequestTypeDef",
     "StopExperimentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TargetResourceTypeParameterTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateExperimentTemplateActionInputItemTypeDef",
     "UpdateExperimentTemplateStopConditionInputTypeDef",
     "ActionSummaryTypeDef",
     "ActionTypeDef",
     "CreateExperimentTemplateLogConfigurationInputTypeDef",
     "UpdateExperimentTemplateLogConfigurationInputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateExperimentTemplateTargetInputTypeDef",
     "UpdateExperimentTemplateTargetInputTypeDef",
     "ExperimentActionTypeDef",
     "ExperimentLogConfigurationTypeDef",
     "ExperimentSummaryTypeDef",
     "ExperimentTargetTypeDef",
     "ExperimentTemplateLogConfigurationTypeDef",
@@ -177,25 +177,14 @@
 
 class CreateExperimentTemplateStopConditionInputTypeDef(
     _RequiredCreateExperimentTemplateStopConditionInputTypeDef,
     _OptionalCreateExperimentTemplateStopConditionInputTypeDef,
 ):
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
-
 ExperimentTemplateTargetInputFilterTypeDef = TypedDict(
     "ExperimentTemplateTargetInputFilterTypeDef",
     {
         "path": str,
         "values": Sequence[str],
     },
 )
@@ -377,14 +366,22 @@
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
 ListTargetResourceTypesRequestRequestTypeDef = TypedDict(
     "ListTargetResourceTypesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -395,14 +392,25 @@
     {
         "resourceType": str,
         "description": str,
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
 _RequiredStartExperimentRequestRequestTypeDef = TypedDict(
     "_RequiredStartExperimentRequestRequestTypeDef",
     {
         "clientToken": str,
         "experimentTemplateId": str,
     },
 )
@@ -544,22 +552,14 @@
         "cloudWatchLogsConfiguration": ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef,
         "s3Configuration": ExperimentTemplateS3LogConfigurationInputTypeDef,
         "logSchemaVersion": int,
     },
     total=False,
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateExperimentTemplateTargetInputTypeDef = TypedDict(
     "_RequiredCreateExperimentTemplateTargetInputTypeDef",
     {
         "resourceType": str,
         "selectionMode": str,
     },
 )
@@ -665,15 +665,15 @@
 )
 
 ListExperimentTemplatesResponseTypeDef = TypedDict(
     "ListExperimentTemplatesResponseTypeDef",
     {
         "experimentTemplates": List[ExperimentTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExperimentTemplateTargetTypeDef = TypedDict(
     "ExperimentTemplateTargetTypeDef",
     {
         "resourceType": str,
@@ -687,15 +687,15 @@
 )
 
 ListTargetResourceTypesResponseTypeDef = TypedDict(
     "ListTargetResourceTypesResponseTypeDef",
     {
         "targetResourceTypes": List[TargetResourceTypeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetResourceTypeTypeDef = TypedDict(
     "TargetResourceTypeTypeDef",
     {
         "resourceType": str,
@@ -706,23 +706,23 @@
 )
 
 ListActionsResponseTypeDef = TypedDict(
     "ListActionsResponseTypeDef",
     {
         "actions": List[ActionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetActionResponseTypeDef = TypedDict(
     "GetActionResponseTypeDef",
     {
         "action": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateExperimentTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExperimentTemplateRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -774,15 +774,15 @@
     pass
 
 ListExperimentsResponseTypeDef = TypedDict(
     "ListExperimentsResponseTypeDef",
     {
         "experiments": List[ExperimentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExperimentTypeDef = TypedDict(
     "ExperimentTypeDef",
     {
         "id": str,
@@ -818,66 +818,66 @@
     total=False,
 )
 
 GetTargetResourceTypeResponseTypeDef = TypedDict(
     "GetTargetResourceTypeResponseTypeDef",
     {
         "targetResourceType": TargetResourceTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExperimentResponseTypeDef = TypedDict(
     "GetExperimentResponseTypeDef",
     {
         "experiment": ExperimentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartExperimentResponseTypeDef = TypedDict(
     "StartExperimentResponseTypeDef",
     {
         "experiment": ExperimentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopExperimentResponseTypeDef = TypedDict(
     "StopExperimentResponseTypeDef",
     {
         "experiment": ExperimentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateExperimentTemplateResponseTypeDef = TypedDict(
     "CreateExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteExperimentTemplateResponseTypeDef = TypedDict(
     "DeleteExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExperimentTemplateResponseTypeDef = TypedDict(
     "GetExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateExperimentTemplateResponseTypeDef = TypedDict(
     "UpdateExperimentTemplateResponseTypeDef",
     {
         "experimentTemplate": ExperimentTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/PKG-INFO` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-fis
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FIS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FIS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-fis"></a>
 
 # types-aiobotocore-fis
 
 [![PyPI - types-aiobotocore-fis](https://img.shields.io/pypi/v/types-aiobotocore-fis.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fis)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fis.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fis)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fis?color=blue)](https://pypistats.org/packages/types-aiobotocore-fis)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FIS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
+[aiobotocore.FIS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fis.html#FIS)
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
 [types-aiobotocore-fis docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fis/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,15 +294,14 @@
 from types_aiobotocore_fis.type_defs import (
     ActionParameterTypeDef,
     ActionTargetTypeDef,
     CreateExperimentTemplateActionInputTypeDef,
     ExperimentTemplateCloudWatchLogsLogConfigurationInputTypeDef,
     ExperimentTemplateS3LogConfigurationInputTypeDef,
     CreateExperimentTemplateStopConditionInputTypeDef,
-    ResponseMetadataTypeDef,
     ExperimentTemplateTargetInputFilterTypeDef,
     DeleteExperimentTemplateRequestRequestTypeDef,
     ExperimentActionStateTypeDef,
     ExperimentCloudWatchLogsLogConfigurationTypeDef,
     ExperimentS3LogConfigurationTypeDef,
     ExperimentStateTypeDef,
     ExperimentStopConditionTypeDef,
@@ -317,28 +316,29 @@
     GetExperimentRequestRequestTypeDef,
     GetExperimentTemplateRequestRequestTypeDef,
     GetTargetResourceTypeRequestRequestTypeDef,
     ListActionsRequestRequestTypeDef,
     ListExperimentTemplatesRequestRequestTypeDef,
     ListExperimentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTargetResourceTypesRequestRequestTypeDef,
     TargetResourceTypeSummaryTypeDef,
+    ResponseMetadataTypeDef,
     StartExperimentRequestRequestTypeDef,
     StopExperimentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TargetResourceTypeParameterTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateExperimentTemplateActionInputItemTypeDef,
     UpdateExperimentTemplateStopConditionInputTypeDef,
     ActionSummaryTypeDef,
     ActionTypeDef,
     CreateExperimentTemplateLogConfigurationInputTypeDef,
     UpdateExperimentTemplateLogConfigurationInputTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateExperimentTemplateTargetInputTypeDef,
     UpdateExperimentTemplateTargetInputTypeDef,
     ExperimentActionTypeDef,
     ExperimentLogConfigurationTypeDef,
     ExperimentSummaryTypeDef,
     ExperimentTargetTypeDef,
     ExperimentTemplateLogConfigurationTypeDef,
@@ -371,43 +371,43 @@
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

### Comparing `types-aiobotocore-fis-2.5.0.post1/types_aiobotocore_fis.egg-info/SOURCES.txt` & `types-aiobotocore-fis-2.5.1/types_aiobotocore_fis.egg-info/SOURCES.txt`

 * *Files identical despite different names*

