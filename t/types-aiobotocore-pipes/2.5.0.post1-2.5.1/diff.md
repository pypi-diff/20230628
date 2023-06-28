# Comparing `tmp/types-aiobotocore-pipes-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-pipes-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-pipes-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-pipes-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-pipes-2.5.0.post1.tar` & `types-aiobotocore-pipes-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.367510 types-aiobotocore-pipes-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16393 2023-03-11 12:27:08.367510 types-aiobotocore-pipes-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14819 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.367510 types-aiobotocore-pipes-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2121 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.359510 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/
--rw-r--r--   0 runner    (1001) docker     (123)      656 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      655 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10880 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    10860 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9858 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9856 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2325 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2321 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    31883 2023-03-11 12:20:04.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    31853 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:20:01.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.367510 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16393 2023-03-11 12:27:08.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-03-11 12:27:08.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:27:08.000000 types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.974192 types-aiobotocore-pipes-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16383 2023-06-28 01:43:58.966192 types-aiobotocore-pipes-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14815 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.974192 types-aiobotocore-pipes-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2115 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.962192 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/
+-rw-r--r--   0 runner    (1001) docker     (123)      656 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      655 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      934 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10880 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10860 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10067 2023-06-28 01:36:50.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10065 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2207 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2204 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    31901 2023-06-28 01:36:50.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31871 2023-06-28 01:36:50.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:49.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.966192 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16383 2023-06-28 01:43:58.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 01:43:58.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:58.000000 types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-pipes-2.5.0.post1/LICENSE` & `types-aiobotocore-pipes-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/PKG-INFO` & `types-aiobotocore-pipes-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pipes
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EventBridgePipes 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EventBridgePipes 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pipes"></a>
 
 # types-aiobotocore-pipes
 
 [![PyPI - types-aiobotocore-pipes](https://img.shields.io/pypi/v/types-aiobotocore-pipes.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pipes)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pipes.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pipes)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pipes?color=blue)](https://pypistats.org/packages/types-aiobotocore-pipes)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridgePipes 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes)
+[aiobotocore.EventBridgePipes 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes)
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
 [types-aiobotocore-pipes docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/).
 
 See how it helps to find and fix potential bugs:
 
@@ -338,30 +338,33 @@
     AwsVpcConfigurationTypeDef,
     BatchArrayPropertiesTypeDef,
     BatchEnvironmentVariableTypeDef,
     BatchResourceRequirementTypeDef,
     BatchJobDependencyTypeDef,
     BatchRetryStrategyTypeDef,
     CapacityProviderStrategyItemTypeDef,
-    ResponseMetadataTypeDef,
+    CreatePipeResponseTypeDef,
     DeadLetterConfigTypeDef,
     DeletePipeRequestRequestTypeDef,
+    DeletePipeResponseTypeDef,
     DescribePipeRequestRequestTypeDef,
     EcsEnvironmentFileTypeDef,
     EcsEnvironmentVariableTypeDef,
     EcsResourceRequirementTypeDef,
     EcsEphemeralStorageTypeDef,
     EcsInferenceAcceleratorOverrideTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
+    ListPipesRequestListPipesPaginateTypeDef,
     ListPipesRequestRequestTypeDef,
     PipeTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MQBrokerAccessCredentialsTypeDef,
     MSKAccessCredentialsTypeDef,
+    PaginatorConfigTypeDef,
     PipeEnrichmentHttpParametersTypeDef,
     PipeSourceSqsQueueParametersTypeDef,
     SelfManagedKafkaAccessConfigurationCredentialsTypeDef,
     SelfManagedKafkaAccessConfigurationVpcTypeDef,
     PipeTargetCloudWatchLogsParametersTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
@@ -370,34 +373,31 @@
     PipeTargetHttpParametersTypeDef,
     PipeTargetKinesisStreamParametersTypeDef,
     PipeTargetLambdaFunctionParametersTypeDef,
     PipeTargetRedshiftDataParametersTypeDef,
     PipeTargetSqsQueueParametersTypeDef,
     PipeTargetStateMachineParametersTypeDef,
     SageMakerPipelineParameterTypeDef,
+    ResponseMetadataTypeDef,
     StartPipeRequestRequestTypeDef,
+    StartPipeResponseTypeDef,
     StopPipeRequestRequestTypeDef,
+    StopPipeResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdatePipeResponseTypeDef,
     UpdatePipeSourceSqsQueueParametersTypeDef,
     NetworkConfigurationTypeDef,
     BatchContainerOverridesTypeDef,
-    CreatePipeResponseTypeDef,
-    DeletePipeResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartPipeResponseTypeDef,
-    StopPipeResponseTypeDef,
-    UpdatePipeResponseTypeDef,
     PipeSourceDynamoDBStreamParametersTypeDef,
     PipeSourceKinesisStreamParametersTypeDef,
     UpdatePipeSourceDynamoDBStreamParametersTypeDef,
     UpdatePipeSourceKinesisStreamParametersTypeDef,
     EcsContainerOverrideTypeDef,
     FilterCriteriaTypeDef,
-    ListPipesRequestListPipesPaginateTypeDef,
     ListPipesResponseTypeDef,
     PipeSourceActiveMQBrokerParametersTypeDef,
     PipeSourceRabbitMQBrokerParametersTypeDef,
     UpdatePipeSourceActiveMQBrokerParametersTypeDef,
     UpdatePipeSourceRabbitMQBrokerParametersTypeDef,
     PipeSourceManagedStreamingKafkaParametersTypeDef,
     UpdatePipeSourceManagedStreamingKafkaParametersTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/README.md` & `types-aiobotocore-pipes-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-pipes"></a>
 
 # types-aiobotocore-pipes
 
 [![PyPI - types-aiobotocore-pipes](https://img.shields.io/pypi/v/types-aiobotocore-pipes.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pipes)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pipes.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pipes)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pipes?color=blue)](https://pypistats.org/packages/types-aiobotocore-pipes)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridgePipes 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes)
+[aiobotocore.EventBridgePipes 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes)
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
 [types-aiobotocore-pipes docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/).
 
 See how it helps to find and fix potential bugs:
 
@@ -305,30 +305,33 @@
     AwsVpcConfigurationTypeDef,
     BatchArrayPropertiesTypeDef,
     BatchEnvironmentVariableTypeDef,
     BatchResourceRequirementTypeDef,
     BatchJobDependencyTypeDef,
     BatchRetryStrategyTypeDef,
     CapacityProviderStrategyItemTypeDef,
-    ResponseMetadataTypeDef,
+    CreatePipeResponseTypeDef,
     DeadLetterConfigTypeDef,
     DeletePipeRequestRequestTypeDef,
+    DeletePipeResponseTypeDef,
     DescribePipeRequestRequestTypeDef,
     EcsEnvironmentFileTypeDef,
     EcsEnvironmentVariableTypeDef,
     EcsResourceRequirementTypeDef,
     EcsEphemeralStorageTypeDef,
     EcsInferenceAcceleratorOverrideTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
+    ListPipesRequestListPipesPaginateTypeDef,
     ListPipesRequestRequestTypeDef,
     PipeTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MQBrokerAccessCredentialsTypeDef,
     MSKAccessCredentialsTypeDef,
+    PaginatorConfigTypeDef,
     PipeEnrichmentHttpParametersTypeDef,
     PipeSourceSqsQueueParametersTypeDef,
     SelfManagedKafkaAccessConfigurationCredentialsTypeDef,
     SelfManagedKafkaAccessConfigurationVpcTypeDef,
     PipeTargetCloudWatchLogsParametersTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
@@ -337,34 +340,31 @@
     PipeTargetHttpParametersTypeDef,
     PipeTargetKinesisStreamParametersTypeDef,
     PipeTargetLambdaFunctionParametersTypeDef,
     PipeTargetRedshiftDataParametersTypeDef,
     PipeTargetSqsQueueParametersTypeDef,
     PipeTargetStateMachineParametersTypeDef,
     SageMakerPipelineParameterTypeDef,
+    ResponseMetadataTypeDef,
     StartPipeRequestRequestTypeDef,
+    StartPipeResponseTypeDef,
     StopPipeRequestRequestTypeDef,
+    StopPipeResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdatePipeResponseTypeDef,
     UpdatePipeSourceSqsQueueParametersTypeDef,
     NetworkConfigurationTypeDef,
     BatchContainerOverridesTypeDef,
-    CreatePipeResponseTypeDef,
-    DeletePipeResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartPipeResponseTypeDef,
-    StopPipeResponseTypeDef,
-    UpdatePipeResponseTypeDef,
     PipeSourceDynamoDBStreamParametersTypeDef,
     PipeSourceKinesisStreamParametersTypeDef,
     UpdatePipeSourceDynamoDBStreamParametersTypeDef,
     UpdatePipeSourceKinesisStreamParametersTypeDef,
     EcsContainerOverrideTypeDef,
     FilterCriteriaTypeDef,
-    ListPipesRequestListPipesPaginateTypeDef,
     ListPipesResponseTypeDef,
     PipeSourceActiveMQBrokerParametersTypeDef,
     PipeSourceRabbitMQBrokerParametersTypeDef,
     UpdatePipeSourceActiveMQBrokerParametersTypeDef,
     UpdatePipeSourceRabbitMQBrokerParametersTypeDef,
     PipeSourceManagedStreamingKafkaParametersTypeDef,
     UpdatePipeSourceManagedStreamingKafkaParametersTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/setup.py` & `types-aiobotocore-pipes-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-pipes.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-pipes",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_pipes"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EventBridgePipes 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.EventBridgePipes 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/"
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/__init__.py` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/__init__.pyi` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/__main__.py` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EventBridgePipes 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EventBridgePipes 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes\nOther"
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/client.py` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/client.pyi` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/literals.py` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -137,14 +137,15 @@
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
@@ -223,14 +224,15 @@
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
@@ -241,14 +243,15 @@
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
@@ -284,14 +287,15 @@
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
@@ -310,16 +314,19 @@
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
@@ -403,15 +410,17 @@
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/literals.pyi` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -135,14 +135,15 @@
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
@@ -221,14 +222,15 @@
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
@@ -239,14 +241,15 @@
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
@@ -282,14 +285,15 @@
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
@@ -308,16 +312,19 @@
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
@@ -401,15 +408,17 @@
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/paginator.py` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,29 +16,22 @@
     session = get_session()
     with session.create_client("pipes") as client:
         client: EventBridgePipesClient
 
         list_pipes_paginator: ListPipesPaginator = client.get_paginator("list_pipes")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import PipeStateType, RequestedPipeStateType
 from .type_defs import ListPipesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListPipesPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -58,13 +51,13 @@
         self,
         *,
         CurrentState: PipeStateType = ...,
         DesiredState: RequestedPipeStateType = ...,
         NamePrefix: str = ...,
         SourcePrefix: str = ...,
         TargetPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes.Paginator.ListPipes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/paginators/#listpipespaginator)
         """
```

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/paginator.pyi` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,28 +16,22 @@
     session = get_session()
     with session.create_client("pipes") as client:
         client: EventBridgePipesClient
 
         list_pipes_paginator: ListPipesPaginator = client.get_paginator("list_pipes")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import PipeStateType, RequestedPipeStateType
 from .type_defs import ListPipesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListPipesPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -54,13 +48,13 @@
         self,
         *,
         CurrentState: PipeStateType = ...,
         DesiredState: RequestedPipeStateType = ...,
         NamePrefix: str = ...,
         SourcePrefix: str = ...,
         TargetPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes.Paginator.ListPipes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/paginators/#listpipespaginator)
         """
```

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/type_defs.py` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -38,39 +38,41 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AwsVpcConfigurationTypeDef",
     "BatchArrayPropertiesTypeDef",
     "BatchEnvironmentVariableTypeDef",
     "BatchResourceRequirementTypeDef",
     "BatchJobDependencyTypeDef",
     "BatchRetryStrategyTypeDef",
     "CapacityProviderStrategyItemTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreatePipeResponseTypeDef",
     "DeadLetterConfigTypeDef",
     "DeletePipeRequestRequestTypeDef",
+    "DeletePipeResponseTypeDef",
     "DescribePipeRequestRequestTypeDef",
     "EcsEnvironmentFileTypeDef",
     "EcsEnvironmentVariableTypeDef",
     "EcsResourceRequirementTypeDef",
     "EcsEphemeralStorageTypeDef",
     "EcsInferenceAcceleratorOverrideTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListPipesRequestListPipesPaginateTypeDef",
     "ListPipesRequestRequestTypeDef",
     "PipeTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MQBrokerAccessCredentialsTypeDef",
     "MSKAccessCredentialsTypeDef",
+    "PaginatorConfigTypeDef",
     "PipeEnrichmentHttpParametersTypeDef",
     "PipeSourceSqsQueueParametersTypeDef",
     "SelfManagedKafkaAccessConfigurationCredentialsTypeDef",
     "SelfManagedKafkaAccessConfigurationVpcTypeDef",
     "PipeTargetCloudWatchLogsParametersTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
@@ -79,34 +81,31 @@
     "PipeTargetHttpParametersTypeDef",
     "PipeTargetKinesisStreamParametersTypeDef",
     "PipeTargetLambdaFunctionParametersTypeDef",
     "PipeTargetRedshiftDataParametersTypeDef",
     "PipeTargetSqsQueueParametersTypeDef",
     "PipeTargetStateMachineParametersTypeDef",
     "SageMakerPipelineParameterTypeDef",
+    "ResponseMetadataTypeDef",
     "StartPipeRequestRequestTypeDef",
+    "StartPipeResponseTypeDef",
     "StopPipeRequestRequestTypeDef",
+    "StopPipeResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdatePipeResponseTypeDef",
     "UpdatePipeSourceSqsQueueParametersTypeDef",
     "NetworkConfigurationTypeDef",
     "BatchContainerOverridesTypeDef",
-    "CreatePipeResponseTypeDef",
-    "DeletePipeResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartPipeResponseTypeDef",
-    "StopPipeResponseTypeDef",
-    "UpdatePipeResponseTypeDef",
     "PipeSourceDynamoDBStreamParametersTypeDef",
     "PipeSourceKinesisStreamParametersTypeDef",
     "UpdatePipeSourceDynamoDBStreamParametersTypeDef",
     "UpdatePipeSourceKinesisStreamParametersTypeDef",
     "EcsContainerOverrideTypeDef",
     "FilterCriteriaTypeDef",
-    "ListPipesRequestListPipesPaginateTypeDef",
     "ListPipesResponseTypeDef",
     "PipeSourceActiveMQBrokerParametersTypeDef",
     "PipeSourceRabbitMQBrokerParametersTypeDef",
     "UpdatePipeSourceActiveMQBrokerParametersTypeDef",
     "UpdatePipeSourceRabbitMQBrokerParametersTypeDef",
     "PipeSourceManagedStreamingKafkaParametersTypeDef",
     "UpdatePipeSourceManagedStreamingKafkaParametersTypeDef",
@@ -136,21 +135,19 @@
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
 BatchArrayPropertiesTypeDef = TypedDict(
     "BatchArrayPropertiesTypeDef",
     {
         "Size": int,
     },
     total=False,
 )
@@ -200,29 +197,29 @@
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
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreatePipeResponseTypeDef = TypedDict(
+    "CreatePipeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeadLetterConfigTypeDef = TypedDict(
     "DeadLetterConfigTypeDef",
     {
         "Arn": str,
@@ -233,14 +230,27 @@
 DeletePipeRequestRequestTypeDef = TypedDict(
     "DeletePipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeletePipeResponseTypeDef = TypedDict(
+    "DeletePipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateDescribeResponseType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePipeRequestRequestTypeDef = TypedDict(
     "DescribePipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -289,20 +299,23 @@
     "FilterTypeDef",
     {
         "Pattern": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListPipesRequestListPipesPaginateTypeDef = TypedDict(
+    "ListPipesRequestListPipesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "NamePrefix": str,
+        "SourcePrefix": str,
+        "TargetPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPipesRequestRequestTypeDef = TypedDict(
     "ListPipesRequestRequestTypeDef",
     {
@@ -337,14 +350,22 @@
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
 MQBrokerAccessCredentialsTypeDef = TypedDict(
     "MQBrokerAccessCredentialsTypeDef",
     {
         "BasicAuth": str,
     },
     total=False,
 )
@@ -354,14 +375,24 @@
     {
         "ClientCertificateTlsAuth": str,
         "SaslScram512Auth": str,
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
 PipeEnrichmentHttpParametersTypeDef = TypedDict(
     "PipeEnrichmentHttpParametersTypeDef",
     {
         "HeaderParameters": Mapping[str, str],
         "PathParameterValues": Sequence[str],
         "QueryStringParameters": Mapping[str, str],
     },
@@ -483,22 +514,20 @@
         "SecretManagerArn": str,
         "StatementName": str,
         "WithEvent": bool,
     },
     total=False,
 )
 
-
 class PipeTargetRedshiftDataParametersTypeDef(
     _RequiredPipeTargetRedshiftDataParametersTypeDef,
     _OptionalPipeTargetRedshiftDataParametersTypeDef,
 ):
     pass
 
-
 PipeTargetSqsQueueParametersTypeDef = TypedDict(
     "PipeTargetSqsQueueParametersTypeDef",
     {
         "MessageDeduplicationId": str,
         "MessageGroupId": str,
     },
     total=False,
@@ -516,28 +545,65 @@
     "SageMakerPipelineParameterTypeDef",
     {
         "Name": str,
         "Value": str,
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
 StartPipeRequestRequestTypeDef = TypedDict(
     "StartPipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StartPipeResponseTypeDef = TypedDict(
+    "StartPipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopPipeRequestRequestTypeDef = TypedDict(
     "StopPipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StopPipeResponseTypeDef = TypedDict(
+    "StopPipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
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
@@ -546,14 +612,27 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdatePipeResponseTypeDef = TypedDict(
+    "UpdatePipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdatePipeSourceSqsQueueParametersTypeDef = TypedDict(
     "UpdatePipeSourceSqsQueueParametersTypeDef",
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
@@ -574,87 +653,14 @@
         "Environment": Sequence[BatchEnvironmentVariableTypeDef],
         "InstanceType": str,
         "ResourceRequirements": Sequence[BatchResourceRequirementTypeDef],
     },
     total=False,
 )
 
-CreatePipeResponseTypeDef = TypedDict(
-    "CreatePipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePipeResponseTypeDef = TypedDict(
-    "DeletePipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateDescribeResponseType,
-        "LastModifiedTime": datetime,
-        "Name": str,
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
-StartPipeResponseTypeDef = TypedDict(
-    "StartPipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopPipeResponseTypeDef = TypedDict(
-    "StopPipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePipeResponseTypeDef = TypedDict(
-    "UpdatePipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredPipeSourceDynamoDBStreamParametersTypeDef = TypedDict(
     "_RequiredPipeSourceDynamoDBStreamParametersTypeDef",
     {
         "StartingPosition": DynamoDBStreamStartPositionType,
     },
 )
 _OptionalPipeSourceDynamoDBStreamParametersTypeDef = TypedDict(
@@ -667,22 +673,20 @@
         "MaximumRetryAttempts": int,
         "OnPartialBatchItemFailure": Literal["AUTOMATIC_BISECT"],
         "ParallelizationFactor": int,
     },
     total=False,
 )
 
-
 class PipeSourceDynamoDBStreamParametersTypeDef(
     _RequiredPipeSourceDynamoDBStreamParametersTypeDef,
     _OptionalPipeSourceDynamoDBStreamParametersTypeDef,
 ):
     pass
 
-
 _RequiredPipeSourceKinesisStreamParametersTypeDef = TypedDict(
     "_RequiredPipeSourceKinesisStreamParametersTypeDef",
     {
         "StartingPosition": KinesisStreamStartPositionType,
     },
 )
 _OptionalPipeSourceKinesisStreamParametersTypeDef = TypedDict(
@@ -696,22 +700,20 @@
         "OnPartialBatchItemFailure": Literal["AUTOMATIC_BISECT"],
         "ParallelizationFactor": int,
         "StartingPositionTimestamp": Union[datetime, str],
     },
     total=False,
 )
 
-
 class PipeSourceKinesisStreamParametersTypeDef(
     _RequiredPipeSourceKinesisStreamParametersTypeDef,
     _OptionalPipeSourceKinesisStreamParametersTypeDef,
 ):
     pass
 
-
 UpdatePipeSourceDynamoDBStreamParametersTypeDef = TypedDict(
     "UpdatePipeSourceDynamoDBStreamParametersTypeDef",
     {
         "BatchSize": int,
         "DeadLetterConfig": DeadLetterConfigTypeDef,
         "MaximumBatchingWindowInSeconds": int,
         "MaximumRecordAgeInSeconds": int,
@@ -755,33 +757,20 @@
     "FilterCriteriaTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListPipesRequestListPipesPaginateTypeDef = TypedDict(
-    "ListPipesRequestListPipesPaginateTypeDef",
-    {
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "NamePrefix": str,
-        "SourcePrefix": str,
-        "TargetPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPipesResponseTypeDef = TypedDict(
     "ListPipesResponseTypeDef",
     {
         "NextToken": str,
         "Pipes": List[PipeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPipeSourceActiveMQBrokerParametersTypeDef = TypedDict(
     "_RequiredPipeSourceActiveMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
@@ -793,22 +782,20 @@
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
 )
 
-
 class PipeSourceActiveMQBrokerParametersTypeDef(
     _RequiredPipeSourceActiveMQBrokerParametersTypeDef,
     _OptionalPipeSourceActiveMQBrokerParametersTypeDef,
 ):
     pass
 
-
 _RequiredPipeSourceRabbitMQBrokerParametersTypeDef = TypedDict(
     "_RequiredPipeSourceRabbitMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
         "QueueName": str,
     },
 )
@@ -818,22 +805,20 @@
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
         "VirtualHost": str,
     },
     total=False,
 )
 
-
 class PipeSourceRabbitMQBrokerParametersTypeDef(
     _RequiredPipeSourceRabbitMQBrokerParametersTypeDef,
     _OptionalPipeSourceRabbitMQBrokerParametersTypeDef,
 ):
     pass
 
-
 _RequiredUpdatePipeSourceActiveMQBrokerParametersTypeDef = TypedDict(
     "_RequiredUpdatePipeSourceActiveMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
     },
 )
 _OptionalUpdatePipeSourceActiveMQBrokerParametersTypeDef = TypedDict(
@@ -841,22 +826,20 @@
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
 )
 
-
 class UpdatePipeSourceActiveMQBrokerParametersTypeDef(
     _RequiredUpdatePipeSourceActiveMQBrokerParametersTypeDef,
     _OptionalUpdatePipeSourceActiveMQBrokerParametersTypeDef,
 ):
     pass
 
-
 _RequiredUpdatePipeSourceRabbitMQBrokerParametersTypeDef = TypedDict(
     "_RequiredUpdatePipeSourceRabbitMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
     },
 )
 _OptionalUpdatePipeSourceRabbitMQBrokerParametersTypeDef = TypedDict(
@@ -864,22 +847,20 @@
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
 )
 
-
 class UpdatePipeSourceRabbitMQBrokerParametersTypeDef(
     _RequiredUpdatePipeSourceRabbitMQBrokerParametersTypeDef,
     _OptionalUpdatePipeSourceRabbitMQBrokerParametersTypeDef,
 ):
     pass
 
-
 _RequiredPipeSourceManagedStreamingKafkaParametersTypeDef = TypedDict(
     "_RequiredPipeSourceManagedStreamingKafkaParametersTypeDef",
     {
         "TopicName": str,
     },
 )
 _OptionalPipeSourceManagedStreamingKafkaParametersTypeDef = TypedDict(
@@ -890,22 +871,20 @@
         "Credentials": MSKAccessCredentialsTypeDef,
         "MaximumBatchingWindowInSeconds": int,
         "StartingPosition": MSKStartPositionType,
     },
     total=False,
 )
 
-
 class PipeSourceManagedStreamingKafkaParametersTypeDef(
     _RequiredPipeSourceManagedStreamingKafkaParametersTypeDef,
     _OptionalPipeSourceManagedStreamingKafkaParametersTypeDef,
 ):
     pass
 
-
 UpdatePipeSourceManagedStreamingKafkaParametersTypeDef = TypedDict(
     "UpdatePipeSourceManagedStreamingKafkaParametersTypeDef",
     {
         "BatchSize": int,
         "Credentials": MSKAccessCredentialsTypeDef,
         "MaximumBatchingWindowInSeconds": int,
     },
@@ -938,22 +917,20 @@
         "ServerRootCaCertificate": str,
         "StartingPosition": SelfManagedKafkaStartPositionType,
         "Vpc": SelfManagedKafkaAccessConfigurationVpcTypeDef,
     },
     total=False,
 )
 
-
 class PipeSourceSelfManagedKafkaParametersTypeDef(
     _RequiredPipeSourceSelfManagedKafkaParametersTypeDef,
     _OptionalPipeSourceSelfManagedKafkaParametersTypeDef,
 ):
     pass
 
-
 UpdatePipeSourceSelfManagedKafkaParametersTypeDef = TypedDict(
     "UpdatePipeSourceSelfManagedKafkaParametersTypeDef",
     {
         "BatchSize": int,
         "Credentials": SelfManagedKafkaAccessConfigurationCredentialsTypeDef,
         "MaximumBatchingWindowInSeconds": int,
         "ServerRootCaCertificate": str,
@@ -985,21 +962,19 @@
         "DependsOn": Sequence[BatchJobDependencyTypeDef],
         "Parameters": Mapping[str, str],
         "RetryStrategy": BatchRetryStrategyTypeDef,
     },
     total=False,
 )
 
-
 class PipeTargetBatchJobParametersTypeDef(
     _RequiredPipeTargetBatchJobParametersTypeDef, _OptionalPipeTargetBatchJobParametersTypeDef
 ):
     pass
 
-
 EcsTaskOverrideTypeDef = TypedDict(
     "EcsTaskOverrideTypeDef",
     {
         "ContainerOverrides": Sequence[EcsContainerOverrideTypeDef],
         "Cpu": str,
         "EphemeralStorage": EcsEphemeralStorageTypeDef,
         "ExecutionRoleArn": str,
@@ -1063,21 +1038,19 @@
         "ReferenceId": str,
         "Tags": Sequence[TagTypeDef],
         "TaskCount": int,
     },
     total=False,
 )
 
-
 class PipeTargetEcsTaskParametersTypeDef(
     _RequiredPipeTargetEcsTaskParametersTypeDef, _OptionalPipeTargetEcsTaskParametersTypeDef
 ):
     pass
 
-
 PipeTargetParametersTypeDef = TypedDict(
     "PipeTargetParametersTypeDef",
     {
         "BatchJobParameters": PipeTargetBatchJobParametersTypeDef,
         "CloudWatchLogsParameters": PipeTargetCloudWatchLogsParametersTypeDef,
         "EcsTaskParameters": PipeTargetEcsTaskParametersTypeDef,
         "EventBridgeEventBusParameters": PipeTargetEventBridgeEventBusParametersTypeDef,
@@ -1112,21 +1085,19 @@
         "SourceParameters": PipeSourceParametersTypeDef,
         "Tags": Mapping[str, str],
         "TargetParameters": PipeTargetParametersTypeDef,
     },
     total=False,
 )
 
-
 class CreatePipeRequestRequestTypeDef(
     _RequiredCreatePipeRequestRequestTypeDef, _OptionalCreatePipeRequestRequestTypeDef
 ):
     pass
 
-
 DescribePipeResponseTypeDef = TypedDict(
     "DescribePipeResponseTypeDef",
     {
         "Arn": str,
         "CreationTime": datetime,
         "CurrentState": PipeStateType,
         "Description": str,
@@ -1138,15 +1109,15 @@
         "RoleArn": str,
         "Source": str,
         "SourceParameters": PipeSourceParametersTypeDef,
         "StateReason": str,
         "Tags": Dict[str, str],
         "Target": str,
         "TargetParameters": PipeTargetParametersTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePipeRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePipeRequestRequestTypeDef",
     {
         "Name": str,
@@ -1163,12 +1134,11 @@
         "SourceParameters": UpdatePipeSourceParametersTypeDef,
         "Target": str,
         "TargetParameters": PipeTargetParametersTypeDef,
     },
     total=False,
 )
 
-
 class UpdatePipeRequestRequestTypeDef(
     _RequiredUpdatePipeRequestRequestTypeDef, _OptionalUpdatePipeRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes/type_defs.pyi` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -38,38 +38,42 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AwsVpcConfigurationTypeDef",
     "BatchArrayPropertiesTypeDef",
     "BatchEnvironmentVariableTypeDef",
     "BatchResourceRequirementTypeDef",
     "BatchJobDependencyTypeDef",
     "BatchRetryStrategyTypeDef",
     "CapacityProviderStrategyItemTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreatePipeResponseTypeDef",
     "DeadLetterConfigTypeDef",
     "DeletePipeRequestRequestTypeDef",
+    "DeletePipeResponseTypeDef",
     "DescribePipeRequestRequestTypeDef",
     "EcsEnvironmentFileTypeDef",
     "EcsEnvironmentVariableTypeDef",
     "EcsResourceRequirementTypeDef",
     "EcsEphemeralStorageTypeDef",
     "EcsInferenceAcceleratorOverrideTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListPipesRequestListPipesPaginateTypeDef",
     "ListPipesRequestRequestTypeDef",
     "PipeTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MQBrokerAccessCredentialsTypeDef",
     "MSKAccessCredentialsTypeDef",
+    "PaginatorConfigTypeDef",
     "PipeEnrichmentHttpParametersTypeDef",
     "PipeSourceSqsQueueParametersTypeDef",
     "SelfManagedKafkaAccessConfigurationCredentialsTypeDef",
     "SelfManagedKafkaAccessConfigurationVpcTypeDef",
     "PipeTargetCloudWatchLogsParametersTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
@@ -78,34 +82,31 @@
     "PipeTargetHttpParametersTypeDef",
     "PipeTargetKinesisStreamParametersTypeDef",
     "PipeTargetLambdaFunctionParametersTypeDef",
     "PipeTargetRedshiftDataParametersTypeDef",
     "PipeTargetSqsQueueParametersTypeDef",
     "PipeTargetStateMachineParametersTypeDef",
     "SageMakerPipelineParameterTypeDef",
+    "ResponseMetadataTypeDef",
     "StartPipeRequestRequestTypeDef",
+    "StartPipeResponseTypeDef",
     "StopPipeRequestRequestTypeDef",
+    "StopPipeResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdatePipeResponseTypeDef",
     "UpdatePipeSourceSqsQueueParametersTypeDef",
     "NetworkConfigurationTypeDef",
     "BatchContainerOverridesTypeDef",
-    "CreatePipeResponseTypeDef",
-    "DeletePipeResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartPipeResponseTypeDef",
-    "StopPipeResponseTypeDef",
-    "UpdatePipeResponseTypeDef",
     "PipeSourceDynamoDBStreamParametersTypeDef",
     "PipeSourceKinesisStreamParametersTypeDef",
     "UpdatePipeSourceDynamoDBStreamParametersTypeDef",
     "UpdatePipeSourceKinesisStreamParametersTypeDef",
     "EcsContainerOverrideTypeDef",
     "FilterCriteriaTypeDef",
-    "ListPipesRequestListPipesPaginateTypeDef",
     "ListPipesResponseTypeDef",
     "PipeSourceActiveMQBrokerParametersTypeDef",
     "PipeSourceRabbitMQBrokerParametersTypeDef",
     "UpdatePipeSourceActiveMQBrokerParametersTypeDef",
     "UpdatePipeSourceRabbitMQBrokerParametersTypeDef",
     "PipeSourceManagedStreamingKafkaParametersTypeDef",
     "UpdatePipeSourceManagedStreamingKafkaParametersTypeDef",
@@ -135,19 +136,21 @@
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
 BatchArrayPropertiesTypeDef = TypedDict(
     "BatchArrayPropertiesTypeDef",
     {
         "Size": int,
     },
     total=False,
 )
@@ -197,27 +200,31 @@
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
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+CreatePipeResponseTypeDef = TypedDict(
+    "CreatePipeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeadLetterConfigTypeDef = TypedDict(
     "DeadLetterConfigTypeDef",
     {
         "Arn": str,
@@ -228,14 +235,27 @@
 DeletePipeRequestRequestTypeDef = TypedDict(
     "DeletePipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeletePipeResponseTypeDef = TypedDict(
+    "DeletePipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateDescribeResponseType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePipeRequestRequestTypeDef = TypedDict(
     "DescribePipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -284,20 +304,23 @@
     "FilterTypeDef",
     {
         "Pattern": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListPipesRequestListPipesPaginateTypeDef = TypedDict(
+    "ListPipesRequestListPipesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "NamePrefix": str,
+        "SourcePrefix": str,
+        "TargetPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPipesRequestRequestTypeDef = TypedDict(
     "ListPipesRequestRequestTypeDef",
     {
@@ -332,14 +355,22 @@
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
 MQBrokerAccessCredentialsTypeDef = TypedDict(
     "MQBrokerAccessCredentialsTypeDef",
     {
         "BasicAuth": str,
     },
     total=False,
 )
@@ -349,14 +380,24 @@
     {
         "ClientCertificateTlsAuth": str,
         "SaslScram512Auth": str,
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
 PipeEnrichmentHttpParametersTypeDef = TypedDict(
     "PipeEnrichmentHttpParametersTypeDef",
     {
         "HeaderParameters": Mapping[str, str],
         "PathParameterValues": Sequence[str],
         "QueryStringParameters": Mapping[str, str],
     },
@@ -478,20 +519,22 @@
         "SecretManagerArn": str,
         "StatementName": str,
         "WithEvent": bool,
     },
     total=False,
 )
 
+
 class PipeTargetRedshiftDataParametersTypeDef(
     _RequiredPipeTargetRedshiftDataParametersTypeDef,
     _OptionalPipeTargetRedshiftDataParametersTypeDef,
 ):
     pass
 
+
 PipeTargetSqsQueueParametersTypeDef = TypedDict(
     "PipeTargetSqsQueueParametersTypeDef",
     {
         "MessageDeduplicationId": str,
         "MessageGroupId": str,
     },
     total=False,
@@ -509,28 +552,65 @@
     "SageMakerPipelineParameterTypeDef",
     {
         "Name": str,
         "Value": str,
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
 StartPipeRequestRequestTypeDef = TypedDict(
     "StartPipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StartPipeResponseTypeDef = TypedDict(
+    "StartPipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopPipeRequestRequestTypeDef = TypedDict(
     "StopPipeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StopPipeResponseTypeDef = TypedDict(
+    "StopPipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
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
@@ -539,14 +619,27 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdatePipeResponseTypeDef = TypedDict(
+    "UpdatePipeResponseTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "CurrentState": PipeStateType,
+        "DesiredState": RequestedPipeStateType,
+        "LastModifiedTime": datetime,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdatePipeSourceSqsQueueParametersTypeDef = TypedDict(
     "UpdatePipeSourceSqsQueueParametersTypeDef",
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
@@ -567,87 +660,14 @@
         "Environment": Sequence[BatchEnvironmentVariableTypeDef],
         "InstanceType": str,
         "ResourceRequirements": Sequence[BatchResourceRequirementTypeDef],
     },
     total=False,
 )
 
-CreatePipeResponseTypeDef = TypedDict(
-    "CreatePipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePipeResponseTypeDef = TypedDict(
-    "DeletePipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateDescribeResponseType,
-        "LastModifiedTime": datetime,
-        "Name": str,
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
-StartPipeResponseTypeDef = TypedDict(
-    "StartPipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopPipeResponseTypeDef = TypedDict(
-    "StopPipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePipeResponseTypeDef = TypedDict(
-    "UpdatePipeResponseTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "LastModifiedTime": datetime,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredPipeSourceDynamoDBStreamParametersTypeDef = TypedDict(
     "_RequiredPipeSourceDynamoDBStreamParametersTypeDef",
     {
         "StartingPosition": DynamoDBStreamStartPositionType,
     },
 )
 _OptionalPipeSourceDynamoDBStreamParametersTypeDef = TypedDict(
@@ -660,20 +680,22 @@
         "MaximumRetryAttempts": int,
         "OnPartialBatchItemFailure": Literal["AUTOMATIC_BISECT"],
         "ParallelizationFactor": int,
     },
     total=False,
 )
 
+
 class PipeSourceDynamoDBStreamParametersTypeDef(
     _RequiredPipeSourceDynamoDBStreamParametersTypeDef,
     _OptionalPipeSourceDynamoDBStreamParametersTypeDef,
 ):
     pass
 
+
 _RequiredPipeSourceKinesisStreamParametersTypeDef = TypedDict(
     "_RequiredPipeSourceKinesisStreamParametersTypeDef",
     {
         "StartingPosition": KinesisStreamStartPositionType,
     },
 )
 _OptionalPipeSourceKinesisStreamParametersTypeDef = TypedDict(
@@ -687,20 +709,22 @@
         "OnPartialBatchItemFailure": Literal["AUTOMATIC_BISECT"],
         "ParallelizationFactor": int,
         "StartingPositionTimestamp": Union[datetime, str],
     },
     total=False,
 )
 
+
 class PipeSourceKinesisStreamParametersTypeDef(
     _RequiredPipeSourceKinesisStreamParametersTypeDef,
     _OptionalPipeSourceKinesisStreamParametersTypeDef,
 ):
     pass
 
+
 UpdatePipeSourceDynamoDBStreamParametersTypeDef = TypedDict(
     "UpdatePipeSourceDynamoDBStreamParametersTypeDef",
     {
         "BatchSize": int,
         "DeadLetterConfig": DeadLetterConfigTypeDef,
         "MaximumBatchingWindowInSeconds": int,
         "MaximumRecordAgeInSeconds": int,
@@ -744,33 +768,20 @@
     "FilterCriteriaTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListPipesRequestListPipesPaginateTypeDef = TypedDict(
-    "ListPipesRequestListPipesPaginateTypeDef",
-    {
-        "CurrentState": PipeStateType,
-        "DesiredState": RequestedPipeStateType,
-        "NamePrefix": str,
-        "SourcePrefix": str,
-        "TargetPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPipesResponseTypeDef = TypedDict(
     "ListPipesResponseTypeDef",
     {
         "NextToken": str,
         "Pipes": List[PipeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPipeSourceActiveMQBrokerParametersTypeDef = TypedDict(
     "_RequiredPipeSourceActiveMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
@@ -782,20 +793,22 @@
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
 )
 
+
 class PipeSourceActiveMQBrokerParametersTypeDef(
     _RequiredPipeSourceActiveMQBrokerParametersTypeDef,
     _OptionalPipeSourceActiveMQBrokerParametersTypeDef,
 ):
     pass
 
+
 _RequiredPipeSourceRabbitMQBrokerParametersTypeDef = TypedDict(
     "_RequiredPipeSourceRabbitMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
         "QueueName": str,
     },
 )
@@ -805,20 +818,22 @@
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
         "VirtualHost": str,
     },
     total=False,
 )
 
+
 class PipeSourceRabbitMQBrokerParametersTypeDef(
     _RequiredPipeSourceRabbitMQBrokerParametersTypeDef,
     _OptionalPipeSourceRabbitMQBrokerParametersTypeDef,
 ):
     pass
 
+
 _RequiredUpdatePipeSourceActiveMQBrokerParametersTypeDef = TypedDict(
     "_RequiredUpdatePipeSourceActiveMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
     },
 )
 _OptionalUpdatePipeSourceActiveMQBrokerParametersTypeDef = TypedDict(
@@ -826,20 +841,22 @@
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
 )
 
+
 class UpdatePipeSourceActiveMQBrokerParametersTypeDef(
     _RequiredUpdatePipeSourceActiveMQBrokerParametersTypeDef,
     _OptionalUpdatePipeSourceActiveMQBrokerParametersTypeDef,
 ):
     pass
 
+
 _RequiredUpdatePipeSourceRabbitMQBrokerParametersTypeDef = TypedDict(
     "_RequiredUpdatePipeSourceRabbitMQBrokerParametersTypeDef",
     {
         "Credentials": MQBrokerAccessCredentialsTypeDef,
     },
 )
 _OptionalUpdatePipeSourceRabbitMQBrokerParametersTypeDef = TypedDict(
@@ -847,20 +864,22 @@
     {
         "BatchSize": int,
         "MaximumBatchingWindowInSeconds": int,
     },
     total=False,
 )
 
+
 class UpdatePipeSourceRabbitMQBrokerParametersTypeDef(
     _RequiredUpdatePipeSourceRabbitMQBrokerParametersTypeDef,
     _OptionalUpdatePipeSourceRabbitMQBrokerParametersTypeDef,
 ):
     pass
 
+
 _RequiredPipeSourceManagedStreamingKafkaParametersTypeDef = TypedDict(
     "_RequiredPipeSourceManagedStreamingKafkaParametersTypeDef",
     {
         "TopicName": str,
     },
 )
 _OptionalPipeSourceManagedStreamingKafkaParametersTypeDef = TypedDict(
@@ -871,20 +890,22 @@
         "Credentials": MSKAccessCredentialsTypeDef,
         "MaximumBatchingWindowInSeconds": int,
         "StartingPosition": MSKStartPositionType,
     },
     total=False,
 )
 
+
 class PipeSourceManagedStreamingKafkaParametersTypeDef(
     _RequiredPipeSourceManagedStreamingKafkaParametersTypeDef,
     _OptionalPipeSourceManagedStreamingKafkaParametersTypeDef,
 ):
     pass
 
+
 UpdatePipeSourceManagedStreamingKafkaParametersTypeDef = TypedDict(
     "UpdatePipeSourceManagedStreamingKafkaParametersTypeDef",
     {
         "BatchSize": int,
         "Credentials": MSKAccessCredentialsTypeDef,
         "MaximumBatchingWindowInSeconds": int,
     },
@@ -917,20 +938,22 @@
         "ServerRootCaCertificate": str,
         "StartingPosition": SelfManagedKafkaStartPositionType,
         "Vpc": SelfManagedKafkaAccessConfigurationVpcTypeDef,
     },
     total=False,
 )
 
+
 class PipeSourceSelfManagedKafkaParametersTypeDef(
     _RequiredPipeSourceSelfManagedKafkaParametersTypeDef,
     _OptionalPipeSourceSelfManagedKafkaParametersTypeDef,
 ):
     pass
 
+
 UpdatePipeSourceSelfManagedKafkaParametersTypeDef = TypedDict(
     "UpdatePipeSourceSelfManagedKafkaParametersTypeDef",
     {
         "BatchSize": int,
         "Credentials": SelfManagedKafkaAccessConfigurationCredentialsTypeDef,
         "MaximumBatchingWindowInSeconds": int,
         "ServerRootCaCertificate": str,
@@ -962,19 +985,21 @@
         "DependsOn": Sequence[BatchJobDependencyTypeDef],
         "Parameters": Mapping[str, str],
         "RetryStrategy": BatchRetryStrategyTypeDef,
     },
     total=False,
 )
 
+
 class PipeTargetBatchJobParametersTypeDef(
     _RequiredPipeTargetBatchJobParametersTypeDef, _OptionalPipeTargetBatchJobParametersTypeDef
 ):
     pass
 
+
 EcsTaskOverrideTypeDef = TypedDict(
     "EcsTaskOverrideTypeDef",
     {
         "ContainerOverrides": Sequence[EcsContainerOverrideTypeDef],
         "Cpu": str,
         "EphemeralStorage": EcsEphemeralStorageTypeDef,
         "ExecutionRoleArn": str,
@@ -1038,19 +1063,21 @@
         "ReferenceId": str,
         "Tags": Sequence[TagTypeDef],
         "TaskCount": int,
     },
     total=False,
 )
 
+
 class PipeTargetEcsTaskParametersTypeDef(
     _RequiredPipeTargetEcsTaskParametersTypeDef, _OptionalPipeTargetEcsTaskParametersTypeDef
 ):
     pass
 
+
 PipeTargetParametersTypeDef = TypedDict(
     "PipeTargetParametersTypeDef",
     {
         "BatchJobParameters": PipeTargetBatchJobParametersTypeDef,
         "CloudWatchLogsParameters": PipeTargetCloudWatchLogsParametersTypeDef,
         "EcsTaskParameters": PipeTargetEcsTaskParametersTypeDef,
         "EventBridgeEventBusParameters": PipeTargetEventBridgeEventBusParametersTypeDef,
@@ -1085,19 +1112,21 @@
         "SourceParameters": PipeSourceParametersTypeDef,
         "Tags": Mapping[str, str],
         "TargetParameters": PipeTargetParametersTypeDef,
     },
     total=False,
 )
 
+
 class CreatePipeRequestRequestTypeDef(
     _RequiredCreatePipeRequestRequestTypeDef, _OptionalCreatePipeRequestRequestTypeDef
 ):
     pass
 
+
 DescribePipeResponseTypeDef = TypedDict(
     "DescribePipeResponseTypeDef",
     {
         "Arn": str,
         "CreationTime": datetime,
         "CurrentState": PipeStateType,
         "Description": str,
@@ -1109,15 +1138,15 @@
         "RoleArn": str,
         "Source": str,
         "SourceParameters": PipeSourceParametersTypeDef,
         "StateReason": str,
         "Tags": Dict[str, str],
         "Target": str,
         "TargetParameters": PipeTargetParametersTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePipeRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePipeRequestRequestTypeDef",
     {
         "Name": str,
@@ -1134,11 +1163,12 @@
         "SourceParameters": UpdatePipeSourceParametersTypeDef,
         "Target": str,
         "TargetParameters": PipeTargetParametersTypeDef,
     },
     total=False,
 )
 
+
 class UpdatePipeRequestRequestTypeDef(
     _RequiredUpdatePipeRequestRequestTypeDef, _OptionalUpdatePipeRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/PKG-INFO` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pipes
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EventBridgePipes 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EventBridgePipes 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pipes"></a>
 
 # types-aiobotocore-pipes
 
 [![PyPI - types-aiobotocore-pipes](https://img.shields.io/pypi/v/types-aiobotocore-pipes.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pipes)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pipes.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pipes)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pipes?color=blue)](https://pypistats.org/packages/types-aiobotocore-pipes)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridgePipes 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes)
+[aiobotocore.EventBridgePipes 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pipes.html#EventBridgePipes)
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
 [types-aiobotocore-pipes docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pipes/).
 
 See how it helps to find and fix potential bugs:
 
@@ -338,30 +338,33 @@
     AwsVpcConfigurationTypeDef,
     BatchArrayPropertiesTypeDef,
     BatchEnvironmentVariableTypeDef,
     BatchResourceRequirementTypeDef,
     BatchJobDependencyTypeDef,
     BatchRetryStrategyTypeDef,
     CapacityProviderStrategyItemTypeDef,
-    ResponseMetadataTypeDef,
+    CreatePipeResponseTypeDef,
     DeadLetterConfigTypeDef,
     DeletePipeRequestRequestTypeDef,
+    DeletePipeResponseTypeDef,
     DescribePipeRequestRequestTypeDef,
     EcsEnvironmentFileTypeDef,
     EcsEnvironmentVariableTypeDef,
     EcsResourceRequirementTypeDef,
     EcsEphemeralStorageTypeDef,
     EcsInferenceAcceleratorOverrideTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
+    ListPipesRequestListPipesPaginateTypeDef,
     ListPipesRequestRequestTypeDef,
     PipeTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MQBrokerAccessCredentialsTypeDef,
     MSKAccessCredentialsTypeDef,
+    PaginatorConfigTypeDef,
     PipeEnrichmentHttpParametersTypeDef,
     PipeSourceSqsQueueParametersTypeDef,
     SelfManagedKafkaAccessConfigurationCredentialsTypeDef,
     SelfManagedKafkaAccessConfigurationVpcTypeDef,
     PipeTargetCloudWatchLogsParametersTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
@@ -370,34 +373,31 @@
     PipeTargetHttpParametersTypeDef,
     PipeTargetKinesisStreamParametersTypeDef,
     PipeTargetLambdaFunctionParametersTypeDef,
     PipeTargetRedshiftDataParametersTypeDef,
     PipeTargetSqsQueueParametersTypeDef,
     PipeTargetStateMachineParametersTypeDef,
     SageMakerPipelineParameterTypeDef,
+    ResponseMetadataTypeDef,
     StartPipeRequestRequestTypeDef,
+    StartPipeResponseTypeDef,
     StopPipeRequestRequestTypeDef,
+    StopPipeResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdatePipeResponseTypeDef,
     UpdatePipeSourceSqsQueueParametersTypeDef,
     NetworkConfigurationTypeDef,
     BatchContainerOverridesTypeDef,
-    CreatePipeResponseTypeDef,
-    DeletePipeResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartPipeResponseTypeDef,
-    StopPipeResponseTypeDef,
-    UpdatePipeResponseTypeDef,
     PipeSourceDynamoDBStreamParametersTypeDef,
     PipeSourceKinesisStreamParametersTypeDef,
     UpdatePipeSourceDynamoDBStreamParametersTypeDef,
     UpdatePipeSourceKinesisStreamParametersTypeDef,
     EcsContainerOverrideTypeDef,
     FilterCriteriaTypeDef,
-    ListPipesRequestListPipesPaginateTypeDef,
     ListPipesResponseTypeDef,
     PipeSourceActiveMQBrokerParametersTypeDef,
     PipeSourceRabbitMQBrokerParametersTypeDef,
     UpdatePipeSourceActiveMQBrokerParametersTypeDef,
     UpdatePipeSourceRabbitMQBrokerParametersTypeDef,
     PipeSourceManagedStreamingKafkaParametersTypeDef,
     UpdatePipeSourceManagedStreamingKafkaParametersTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-pipes-2.5.0.post1/types_aiobotocore_pipes.egg-info/SOURCES.txt` & `types-aiobotocore-pipes-2.5.1/types_aiobotocore_pipes.egg-info/SOURCES.txt`

 * *Files identical despite different names*

