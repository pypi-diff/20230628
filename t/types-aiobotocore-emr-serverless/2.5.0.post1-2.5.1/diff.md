# Comparing `tmp/types-aiobotocore-emr-serverless-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-emr-serverless-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-emr-serverless-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:36 2023, max compression
+gzip compressed data, was "types-aiobotocore-emr-serverless-2.5.1.tar", last modified: Wed Jun 28 01:43:29 2023, max compression
```

## Comparing `types-aiobotocore-emr-serverless-2.5.0.post1.tar` & `types-aiobotocore-emr-serverless-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.939199 types-aiobotocore-emr-serverless-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15286 2023-03-11 12:26:36.939199 types-aiobotocore-emr-serverless-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13688 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:36.939199 types-aiobotocore-emr-serverless-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:14:21.000000 types-aiobotocore-emr-serverless-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.939199 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/
--rw-r--r--   0 runner    (1001) docker     (123)      876 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      875 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15564 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15538 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8331 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8329 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3657 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3652 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19592 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19559 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:22.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.939199 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15286 2023-03-11 12:26:36.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:36.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:36.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:36.000000 types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.266136 types-aiobotocore-emr-serverless-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15317 2023-06-28 01:43:29.266136 types-aiobotocore-emr-serverless-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:29.266136 types-aiobotocore-emr-serverless-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.262136 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/
+-rw-r--r--   0 runner    (1001) docker     (123)      876 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      875 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15564 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15538 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8575 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8573 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3541 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3537 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19952 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19919 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:58.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.266136 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15317 2023-06-28 01:43:29.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:29.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:29.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:29.000000 types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/LICENSE` & `types-aiobotocore-emr-serverless-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/PKG-INFO` & `types-aiobotocore-emr-serverless-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-emr-serverless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EMRServerless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EMRServerless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-emr-serverless"></a>
 
 # types-aiobotocore-emr-serverless
 
 [![PyPI - types-aiobotocore-emr-serverless](https://img.shields.io/pypi/v/types-aiobotocore-emr-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-serverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-emr-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-serverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-emr-serverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-emr-serverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EMRServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless)
+[aiobotocore.EMRServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless)
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
 [types-aiobotocore-emr-serverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,49 +331,50 @@
     ApplicationSummaryTypeDef,
     AutoStartConfigTypeDef,
     AutoStopConfigTypeDef,
     ImageConfigurationTypeDef,
     MaximumAllowedResourcesTypeDef,
     NetworkConfigurationTypeDef,
     CancelJobRunRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobRunResponseTypeDef,
     ConfigurationTypeDef,
     ImageConfigurationInputTypeDef,
+    CreateApplicationResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetDashboardForJobRunRequestRequestTypeDef,
+    GetDashboardForJobRunResponseTypeDef,
     GetJobRunRequestRequestTypeDef,
     HiveTypeDef,
     WorkerResourceConfigTypeDef,
     SparkSubmitTypeDef,
     JobRunSummaryTypeDef,
+    ResourceUtilizationTypeDef,
     TotalResourceUtilizationTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListJobRunsRequestListJobRunsPaginateTypeDef,
     ListJobRunsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ManagedPersistenceMonitoringConfigurationTypeDef,
     S3MonitoringConfigurationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartApplicationRequestRequestTypeDef,
+    StartJobRunResponseTypeDef,
     StopApplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    WorkerTypeSpecificationTypeDef,
-    CancelJobRunResponseTypeDef,
-    CreateApplicationResponseTypeDef,
-    GetDashboardForJobRunResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartJobRunResponseTypeDef,
+    WorkerTypeSpecificationTypeDef,
     WorkerTypeSpecificationInputTypeDef,
     InitialCapacityConfigTypeDef,
     JobDriverTypeDef,
     ListJobRunsResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListJobRunsRequestListJobRunsPaginateTypeDef,
     MonitoringConfigurationTypeDef,
     ApplicationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     ConfigurationOverridesTypeDef,
     GetApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
@@ -390,43 +391,43 @@
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/README.md` & `types-aiobotocore-emr-serverless-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-emr-serverless"></a>
 
 # types-aiobotocore-emr-serverless
 
 [![PyPI - types-aiobotocore-emr-serverless](https://img.shields.io/pypi/v/types-aiobotocore-emr-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-serverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-emr-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-serverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-emr-serverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-emr-serverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EMRServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless)
+[aiobotocore.EMRServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless)
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
 [types-aiobotocore-emr-serverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,49 +298,50 @@
     ApplicationSummaryTypeDef,
     AutoStartConfigTypeDef,
     AutoStopConfigTypeDef,
     ImageConfigurationTypeDef,
     MaximumAllowedResourcesTypeDef,
     NetworkConfigurationTypeDef,
     CancelJobRunRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobRunResponseTypeDef,
     ConfigurationTypeDef,
     ImageConfigurationInputTypeDef,
+    CreateApplicationResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetDashboardForJobRunRequestRequestTypeDef,
+    GetDashboardForJobRunResponseTypeDef,
     GetJobRunRequestRequestTypeDef,
     HiveTypeDef,
     WorkerResourceConfigTypeDef,
     SparkSubmitTypeDef,
     JobRunSummaryTypeDef,
+    ResourceUtilizationTypeDef,
     TotalResourceUtilizationTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListJobRunsRequestListJobRunsPaginateTypeDef,
     ListJobRunsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ManagedPersistenceMonitoringConfigurationTypeDef,
     S3MonitoringConfigurationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartApplicationRequestRequestTypeDef,
+    StartJobRunResponseTypeDef,
     StopApplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    WorkerTypeSpecificationTypeDef,
-    CancelJobRunResponseTypeDef,
-    CreateApplicationResponseTypeDef,
-    GetDashboardForJobRunResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartJobRunResponseTypeDef,
+    WorkerTypeSpecificationTypeDef,
     WorkerTypeSpecificationInputTypeDef,
     InitialCapacityConfigTypeDef,
     JobDriverTypeDef,
     ListJobRunsResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListJobRunsRequestListJobRunsPaginateTypeDef,
     MonitoringConfigurationTypeDef,
     ApplicationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     ConfigurationOverridesTypeDef,
     GetApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
@@ -357,43 +358,43 @@
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/setup.py` & `types-aiobotocore-emr-serverless-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-emr-serverless.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-emr-serverless",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_emr_serverless"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EMRServerless 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.EMRServerless 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/"
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/__init__.py` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/__init__.pyi` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/__main__.py` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EMRServerless 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EMRServerless 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless\nOther"
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/client.py` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/client.pyi` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/literals.py` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,29 +14,27 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ApplicationStateType",
     "ArchitectureType",
     "JobRunStateType",
     "ListApplicationsPaginatorName",
     "ListJobRunsPaginatorName",
     "EMRServerlessServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ApplicationStateType = Literal[
     "CREATED", "CREATING", "STARTED", "STARTING", "STOPPED", "STOPPING", "TERMINATED"
 ]
 ArchitectureType = Literal["ARM64", "X86_64"]
 JobRunStateType = Literal[
     "CANCELLED", "CANCELLING", "FAILED", "PENDING", "RUNNING", "SCHEDULED", "SUBMITTED", "SUCCESS"
 ]
@@ -101,14 +99,15 @@
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
@@ -187,14 +186,15 @@
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
@@ -205,14 +205,15 @@
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
@@ -248,14 +249,15 @@
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
@@ -274,16 +276,19 @@
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
@@ -367,15 +372,17 @@
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
@@ -395,24 +402,26 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_applications", "list_job_runs"]
 RegionName = Literal[
+    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/literals.pyi` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -14,27 +14,29 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ApplicationStateType",
     "ArchitectureType",
     "JobRunStateType",
     "ListApplicationsPaginatorName",
     "ListJobRunsPaginatorName",
     "EMRServerlessServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ApplicationStateType = Literal[
     "CREATED", "CREATING", "STARTED", "STARTING", "STOPPED", "STOPPING", "TERMINATED"
 ]
 ArchitectureType = Literal["ARM64", "X86_64"]
 JobRunStateType = Literal[
     "CANCELLED", "CANCELLING", "FAILED", "PENDING", "RUNNING", "SCHEDULED", "SUBMITTED", "SUCCESS"
 ]
@@ -99,14 +101,15 @@
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
@@ -185,14 +188,15 @@
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
@@ -203,14 +207,15 @@
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
@@ -246,14 +251,15 @@
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
@@ -272,16 +278,19 @@
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
@@ -365,15 +374,17 @@
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
@@ -393,24 +404,26 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_applications", "list_job_runs"]
 RegionName = Literal[
+    "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/paginator.py` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,34 +18,27 @@
     with session.create_client("emr-serverless") as client:
         client: EMRServerlessClient
 
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_job_runs_paginator: ListJobRunsPaginator = client.get_paginator("list_job_runs")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ApplicationStateType, JobRunStateType
 from .type_defs import (
     ListApplicationsResponseTypeDef,
     ListJobRunsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListApplicationsPaginator", "ListJobRunsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -61,15 +54,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/paginators/#listapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         states: Sequence[ApplicationStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/paginators/#listapplicationspaginator)
         """
 
 
@@ -82,13 +75,13 @@
     def paginate(
         self,
         *,
         applicationId: str,
         createdAtAfter: Union[datetime, str] = ...,
         createdAtBefore: Union[datetime, str] = ...,
         states: Sequence[JobRunStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless.Paginator.ListJobRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/paginators/#listjobrunspaginator)
         """
```

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/paginator.pyi` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -18,33 +18,27 @@
     with session.create_client("emr-serverless") as client:
         client: EMRServerlessClient
 
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
         list_job_runs_paginator: ListJobRunsPaginator = client.get_paginator("list_job_runs")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ApplicationStateType, JobRunStateType
 from .type_defs import (
     ListApplicationsResponseTypeDef,
     ListJobRunsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListApplicationsPaginator", "ListJobRunsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -57,15 +51,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/paginators/#listapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         states: Sequence[ApplicationStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/paginators/#listapplicationspaginator)
         """
 
 class ListJobRunsPaginator(AioPaginator):
@@ -77,13 +71,13 @@
     def paginate(
         self,
         *,
         applicationId: str,
         createdAtAfter: Union[datetime, str] = ...,
         createdAtBefore: Union[datetime, str] = ...,
         states: Sequence[JobRunStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless.Paginator.ListJobRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/paginators/#listjobrunspaginator)
         """
```

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/type_defs.py` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,49 +27,50 @@
     "ApplicationSummaryTypeDef",
     "AutoStartConfigTypeDef",
     "AutoStopConfigTypeDef",
     "ImageConfigurationTypeDef",
     "MaximumAllowedResourcesTypeDef",
     "NetworkConfigurationTypeDef",
     "CancelJobRunRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobRunResponseTypeDef",
     "ConfigurationTypeDef",
     "ImageConfigurationInputTypeDef",
+    "CreateApplicationResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetDashboardForJobRunRequestRequestTypeDef",
+    "GetDashboardForJobRunResponseTypeDef",
     "GetJobRunRequestRequestTypeDef",
     "HiveTypeDef",
     "WorkerResourceConfigTypeDef",
     "SparkSubmitTypeDef",
     "JobRunSummaryTypeDef",
+    "ResourceUtilizationTypeDef",
     "TotalResourceUtilizationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListJobRunsRequestListJobRunsPaginateTypeDef",
     "ListJobRunsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ManagedPersistenceMonitoringConfigurationTypeDef",
     "S3MonitoringConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartApplicationRequestRequestTypeDef",
+    "StartJobRunResponseTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "WorkerTypeSpecificationTypeDef",
-    "CancelJobRunResponseTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "GetDashboardForJobRunResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartJobRunResponseTypeDef",
+    "WorkerTypeSpecificationTypeDef",
     "WorkerTypeSpecificationInputTypeDef",
     "InitialCapacityConfigTypeDef",
     "JobDriverTypeDef",
     "ListJobRunsResponseTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListJobRunsRequestListJobRunsPaginateTypeDef",
     "MonitoringConfigurationTypeDef",
     "ApplicationTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "ConfigurationOverridesTypeDef",
     "GetApplicationResponseTypeDef",
     "UpdateApplicationResponseTypeDef",
@@ -180,22 +181,20 @@
     "CancelJobRunRequestRequestTypeDef",
     {
         "applicationId": str,
         "jobRunId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJobRunResponseTypeDef = TypedDict(
+    "CancelJobRunResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationId": str,
+        "jobRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConfigurationTypeDef = TypedDict(
     "_RequiredConfigurationTypeDef",
     {
         "classification": str,
@@ -219,14 +218,24 @@
     "ImageConfigurationInputTypeDef",
     {
         "imageUri": str,
     },
     total=False,
 )
 
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
+    {
+        "applicationId": str,
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
@@ -241,14 +250,22 @@
     "GetDashboardForJobRunRequestRequestTypeDef",
     {
         "applicationId": str,
         "jobRunId": str,
     },
 )
 
+GetDashboardForJobRunResponseTypeDef = TypedDict(
+    "GetDashboardForJobRunResponseTypeDef",
+    {
+        "url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobRunRequestRequestTypeDef = TypedDict(
     "GetJobRunRequestRequestTypeDef",
     {
         "applicationId": str,
         "jobRunId": str,
     },
 )
@@ -340,44 +357,78 @@
 )
 
 
 class JobRunSummaryTypeDef(_RequiredJobRunSummaryTypeDef, _OptionalJobRunSummaryTypeDef):
     pass
 
 
+ResourceUtilizationTypeDef = TypedDict(
+    "ResourceUtilizationTypeDef",
+    {
+        "vCPUHour": float,
+        "memoryGBHour": float,
+        "storageGBHour": float,
+    },
+    total=False,
+)
+
 TotalResourceUtilizationTypeDef = TypedDict(
     "TotalResourceUtilizationTypeDef",
     {
         "vCPUHour": float,
         "memoryGBHour": float,
         "storageGBHour": float,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "states": Sequence[ApplicationStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "states": Sequence[ApplicationStateType],
     },
     total=False,
 )
 
+_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
+    {
+        "createdAtAfter": Union[datetime, str],
+        "createdAtBefore": Union[datetime, str],
+        "states": Sequence[JobRunStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListJobRunsRequestListJobRunsPaginateTypeDef(
+    _RequiredListJobRunsRequestListJobRunsPaginateTypeDef,
+    _OptionalListJobRunsRequestListJobRunsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListJobRunsRequestRequestTypeDef = TypedDict(
     "_RequiredListJobRunsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListJobRunsRequestRequestTypeDef = TypedDict(
@@ -402,14 +453,22 @@
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
 ManagedPersistenceMonitoringConfigurationTypeDef = TypedDict(
     "ManagedPersistenceMonitoringConfigurationTypeDef",
     {
         "enabled": bool,
         "encryptionKeyArn": str,
     },
     total=False,
@@ -420,21 +479,52 @@
     {
         "logUri": str,
         "encryptionKeyArn": str,
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
 StartApplicationRequestRequestTypeDef = TypedDict(
     "StartApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
+StartJobRunResponseTypeDef = TypedDict(
+    "StartJobRunResponseTypeDef",
+    {
+        "applicationId": str,
+        "jobRunId": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopApplicationRequestRequestTypeDef = TypedDict(
     "StopApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
@@ -450,74 +540,29 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-WorkerTypeSpecificationTypeDef = TypedDict(
-    "WorkerTypeSpecificationTypeDef",
-    {
-        "imageConfiguration": ImageConfigurationTypeDef,
-    },
-    total=False,
-)
-
-CancelJobRunResponseTypeDef = TypedDict(
-    "CancelJobRunResponseTypeDef",
-    {
-        "applicationId": str,
-        "jobRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "applicationId": str,
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDashboardForJobRunResponseTypeDef = TypedDict(
-    "GetDashboardForJobRunResponseTypeDef",
-    {
-        "url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "applications": List[ApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartJobRunResponseTypeDef = TypedDict(
-    "StartJobRunResponseTypeDef",
+WorkerTypeSpecificationTypeDef = TypedDict(
+    "WorkerTypeSpecificationTypeDef",
     {
-        "applicationId": str,
-        "jobRunId": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageConfiguration": ImageConfigurationTypeDef,
     },
+    total=False,
 )
 
 WorkerTypeSpecificationInputTypeDef = TypedDict(
     "WorkerTypeSpecificationInputTypeDef",
     {
         "imageConfiguration": ImageConfigurationInputTypeDef,
     },
@@ -555,52 +600,18 @@
 )
 
 ListJobRunsResponseTypeDef = TypedDict(
     "ListJobRunsResponseTypeDef",
     {
         "jobRuns": List[JobRunSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "states": Sequence[ApplicationStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "createdAtAfter": Union[datetime, str],
-        "createdAtBefore": Union[datetime, str],
-        "states": Sequence[JobRunStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobRunsRequestListJobRunsPaginateTypeDef(
-    _RequiredListJobRunsRequestListJobRunsPaginateTypeDef,
-    _OptionalListJobRunsRequestListJobRunsPaginateTypeDef,
-):
-    pass
-
-
 MonitoringConfigurationTypeDef = TypedDict(
     "MonitoringConfigurationTypeDef",
     {
         "s3MonitoringConfiguration": S3MonitoringConfigurationTypeDef,
         "managedPersistenceMonitoringConfiguration": (
             ManagedPersistenceMonitoringConfigurationTypeDef
         ),
@@ -713,23 +724,23 @@
     total=False,
 )
 
 GetApplicationResponseTypeDef = TypedDict(
     "GetApplicationResponseTypeDef",
     {
         "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJobRunTypeDef = TypedDict(
     "_RequiredJobRunTypeDef",
     {
         "applicationId": str,
@@ -750,14 +761,16 @@
     {
         "name": str,
         "configurationOverrides": ConfigurationOverridesTypeDef,
         "tags": Dict[str, str],
         "totalResourceUtilization": TotalResourceUtilizationTypeDef,
         "networkConfiguration": NetworkConfigurationTypeDef,
         "totalExecutionDurationSeconds": int,
+        "executionTimeoutMinutes": int,
+        "billedResourceUtilization": ResourceUtilizationTypeDef,
     },
     total=False,
 )
 
 
 class JobRunTypeDef(_RequiredJobRunTypeDef, _OptionalJobRunTypeDef):
     pass
@@ -790,10 +803,10 @@
     pass
 
 
 GetJobRunResponseTypeDef = TypedDict(
     "GetJobRunResponseTypeDef",
     {
         "jobRun": JobRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless/type_defs.pyi` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -26,49 +26,50 @@
     "ApplicationSummaryTypeDef",
     "AutoStartConfigTypeDef",
     "AutoStopConfigTypeDef",
     "ImageConfigurationTypeDef",
     "MaximumAllowedResourcesTypeDef",
     "NetworkConfigurationTypeDef",
     "CancelJobRunRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobRunResponseTypeDef",
     "ConfigurationTypeDef",
     "ImageConfigurationInputTypeDef",
+    "CreateApplicationResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetDashboardForJobRunRequestRequestTypeDef",
+    "GetDashboardForJobRunResponseTypeDef",
     "GetJobRunRequestRequestTypeDef",
     "HiveTypeDef",
     "WorkerResourceConfigTypeDef",
     "SparkSubmitTypeDef",
     "JobRunSummaryTypeDef",
+    "ResourceUtilizationTypeDef",
     "TotalResourceUtilizationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListJobRunsRequestListJobRunsPaginateTypeDef",
     "ListJobRunsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ManagedPersistenceMonitoringConfigurationTypeDef",
     "S3MonitoringConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartApplicationRequestRequestTypeDef",
+    "StartJobRunResponseTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "WorkerTypeSpecificationTypeDef",
-    "CancelJobRunResponseTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "GetDashboardForJobRunResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartJobRunResponseTypeDef",
+    "WorkerTypeSpecificationTypeDef",
     "WorkerTypeSpecificationInputTypeDef",
     "InitialCapacityConfigTypeDef",
     "JobDriverTypeDef",
     "ListJobRunsResponseTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListJobRunsRequestListJobRunsPaginateTypeDef",
     "MonitoringConfigurationTypeDef",
     "ApplicationTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "ConfigurationOverridesTypeDef",
     "GetApplicationResponseTypeDef",
     "UpdateApplicationResponseTypeDef",
@@ -173,22 +174,20 @@
     "CancelJobRunRequestRequestTypeDef",
     {
         "applicationId": str,
         "jobRunId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelJobRunResponseTypeDef = TypedDict(
+    "CancelJobRunResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationId": str,
+        "jobRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConfigurationTypeDef = TypedDict(
     "_RequiredConfigurationTypeDef",
     {
         "classification": str,
@@ -210,14 +209,24 @@
     "ImageConfigurationInputTypeDef",
     {
         "imageUri": str,
     },
     total=False,
 )
 
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
+    {
+        "applicationId": str,
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
@@ -232,14 +241,22 @@
     "GetDashboardForJobRunRequestRequestTypeDef",
     {
         "applicationId": str,
         "jobRunId": str,
     },
 )
 
+GetDashboardForJobRunResponseTypeDef = TypedDict(
+    "GetDashboardForJobRunResponseTypeDef",
+    {
+        "url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobRunRequestRequestTypeDef = TypedDict(
     "GetJobRunRequestRequestTypeDef",
     {
         "applicationId": str,
         "jobRunId": str,
     },
 )
@@ -323,44 +340,76 @@
     },
     total=False,
 )
 
 class JobRunSummaryTypeDef(_RequiredJobRunSummaryTypeDef, _OptionalJobRunSummaryTypeDef):
     pass
 
+ResourceUtilizationTypeDef = TypedDict(
+    "ResourceUtilizationTypeDef",
+    {
+        "vCPUHour": float,
+        "memoryGBHour": float,
+        "storageGBHour": float,
+    },
+    total=False,
+)
+
 TotalResourceUtilizationTypeDef = TypedDict(
     "TotalResourceUtilizationTypeDef",
     {
         "vCPUHour": float,
         "memoryGBHour": float,
         "storageGBHour": float,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "states": Sequence[ApplicationStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "states": Sequence[ApplicationStateType],
     },
     total=False,
 )
 
+_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
+    {
+        "createdAtAfter": Union[datetime, str],
+        "createdAtBefore": Union[datetime, str],
+        "states": Sequence[JobRunStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListJobRunsRequestListJobRunsPaginateTypeDef(
+    _RequiredListJobRunsRequestListJobRunsPaginateTypeDef,
+    _OptionalListJobRunsRequestListJobRunsPaginateTypeDef,
+):
+    pass
+
 _RequiredListJobRunsRequestRequestTypeDef = TypedDict(
     "_RequiredListJobRunsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListJobRunsRequestRequestTypeDef = TypedDict(
@@ -383,14 +432,22 @@
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
 ManagedPersistenceMonitoringConfigurationTypeDef = TypedDict(
     "ManagedPersistenceMonitoringConfigurationTypeDef",
     {
         "enabled": bool,
         "encryptionKeyArn": str,
     },
     total=False,
@@ -401,21 +458,52 @@
     {
         "logUri": str,
         "encryptionKeyArn": str,
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
 StartApplicationRequestRequestTypeDef = TypedDict(
     "StartApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
+StartJobRunResponseTypeDef = TypedDict(
+    "StartJobRunResponseTypeDef",
+    {
+        "applicationId": str,
+        "jobRunId": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopApplicationRequestRequestTypeDef = TypedDict(
     "StopApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
@@ -431,74 +519,29 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-WorkerTypeSpecificationTypeDef = TypedDict(
-    "WorkerTypeSpecificationTypeDef",
-    {
-        "imageConfiguration": ImageConfigurationTypeDef,
-    },
-    total=False,
-)
-
-CancelJobRunResponseTypeDef = TypedDict(
-    "CancelJobRunResponseTypeDef",
-    {
-        "applicationId": str,
-        "jobRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "applicationId": str,
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDashboardForJobRunResponseTypeDef = TypedDict(
-    "GetDashboardForJobRunResponseTypeDef",
-    {
-        "url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "applications": List[ApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartJobRunResponseTypeDef = TypedDict(
-    "StartJobRunResponseTypeDef",
+WorkerTypeSpecificationTypeDef = TypedDict(
+    "WorkerTypeSpecificationTypeDef",
     {
-        "applicationId": str,
-        "jobRunId": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "imageConfiguration": ImageConfigurationTypeDef,
     },
+    total=False,
 )
 
 WorkerTypeSpecificationInputTypeDef = TypedDict(
     "WorkerTypeSpecificationInputTypeDef",
     {
         "imageConfiguration": ImageConfigurationInputTypeDef,
     },
@@ -534,50 +577,18 @@
 )
 
 ListJobRunsResponseTypeDef = TypedDict(
     "ListJobRunsResponseTypeDef",
     {
         "jobRuns": List[JobRunSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "states": Sequence[ApplicationStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "createdAtAfter": Union[datetime, str],
-        "createdAtBefore": Union[datetime, str],
-        "states": Sequence[JobRunStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobRunsRequestListJobRunsPaginateTypeDef(
-    _RequiredListJobRunsRequestListJobRunsPaginateTypeDef,
-    _OptionalListJobRunsRequestListJobRunsPaginateTypeDef,
-):
-    pass
-
 MonitoringConfigurationTypeDef = TypedDict(
     "MonitoringConfigurationTypeDef",
     {
         "s3MonitoringConfiguration": S3MonitoringConfigurationTypeDef,
         "managedPersistenceMonitoringConfiguration": (
             ManagedPersistenceMonitoringConfigurationTypeDef
         ),
@@ -684,23 +695,23 @@
     total=False,
 )
 
 GetApplicationResponseTypeDef = TypedDict(
     "GetApplicationResponseTypeDef",
     {
         "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJobRunTypeDef = TypedDict(
     "_RequiredJobRunTypeDef",
     {
         "applicationId": str,
@@ -721,14 +732,16 @@
     {
         "name": str,
         "configurationOverrides": ConfigurationOverridesTypeDef,
         "tags": Dict[str, str],
         "totalResourceUtilization": TotalResourceUtilizationTypeDef,
         "networkConfiguration": NetworkConfigurationTypeDef,
         "totalExecutionDurationSeconds": int,
+        "executionTimeoutMinutes": int,
+        "billedResourceUtilization": ResourceUtilizationTypeDef,
     },
     total=False,
 )
 
 class JobRunTypeDef(_RequiredJobRunTypeDef, _OptionalJobRunTypeDef):
     pass
 
@@ -757,10 +770,10 @@
 ):
     pass
 
 GetJobRunResponseTypeDef = TypedDict(
     "GetJobRunResponseTypeDef",
     {
         "jobRun": JobRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/PKG-INFO` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-emr-serverless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EMRServerless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EMRServerless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-emr-serverless"></a>
 
 # types-aiobotocore-emr-serverless
 
 [![PyPI - types-aiobotocore-emr-serverless](https://img.shields.io/pypi/v/types-aiobotocore-emr-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-serverless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-emr-serverless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-serverless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-emr-serverless?color=blue)](https://pypistats.org/packages/types-aiobotocore-emr-serverless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EMRServerless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless)
+[aiobotocore.EMRServerless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-serverless.html#EMRServerless)
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
 [types-aiobotocore-emr-serverless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_serverless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,49 +331,50 @@
     ApplicationSummaryTypeDef,
     AutoStartConfigTypeDef,
     AutoStopConfigTypeDef,
     ImageConfigurationTypeDef,
     MaximumAllowedResourcesTypeDef,
     NetworkConfigurationTypeDef,
     CancelJobRunRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobRunResponseTypeDef,
     ConfigurationTypeDef,
     ImageConfigurationInputTypeDef,
+    CreateApplicationResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetDashboardForJobRunRequestRequestTypeDef,
+    GetDashboardForJobRunResponseTypeDef,
     GetJobRunRequestRequestTypeDef,
     HiveTypeDef,
     WorkerResourceConfigTypeDef,
     SparkSubmitTypeDef,
     JobRunSummaryTypeDef,
+    ResourceUtilizationTypeDef,
     TotalResourceUtilizationTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListJobRunsRequestListJobRunsPaginateTypeDef,
     ListJobRunsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ManagedPersistenceMonitoringConfigurationTypeDef,
     S3MonitoringConfigurationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartApplicationRequestRequestTypeDef,
+    StartJobRunResponseTypeDef,
     StopApplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    WorkerTypeSpecificationTypeDef,
-    CancelJobRunResponseTypeDef,
-    CreateApplicationResponseTypeDef,
-    GetDashboardForJobRunResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartJobRunResponseTypeDef,
+    WorkerTypeSpecificationTypeDef,
     WorkerTypeSpecificationInputTypeDef,
     InitialCapacityConfigTypeDef,
     JobDriverTypeDef,
     ListJobRunsResponseTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListJobRunsRequestListJobRunsPaginateTypeDef,
     MonitoringConfigurationTypeDef,
     ApplicationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     ConfigurationOverridesTypeDef,
     GetApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
@@ -390,43 +391,43 @@
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

### Comparing `types-aiobotocore-emr-serverless-2.5.0.post1/types_aiobotocore_emr_serverless.egg-info/SOURCES.txt` & `types-aiobotocore-emr-serverless-2.5.1/types_aiobotocore_emr_serverless.egg-info/SOURCES.txt`

 * *Files identical despite different names*

