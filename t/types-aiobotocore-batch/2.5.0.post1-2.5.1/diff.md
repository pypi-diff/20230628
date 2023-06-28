# Comparing `tmp/types-aiobotocore-batch-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-batch-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-batch-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-batch-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-batch-2.5.0.post1.tar` & `types-aiobotocore-batch-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.258974 types-aiobotocore-batch-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18165 2023-03-11 12:26:15.258974 types-aiobotocore-batch-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16602 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.258974 types-aiobotocore-batch-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.258974 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/
--rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1578 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22153 2023-03-11 12:10:09.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22115 2023-03-11 12:10:09.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10360 2023-03-11 12:10:09.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10358 2023-03-11 12:10:09.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7098 2023-03-11 12:10:09.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7090 2023-03-11 12:10:09.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    43523 2023-03-11 12:10:10.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    43466 2023-03-11 12:10:10.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:08.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.258974 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18165 2023-03-11 12:26:15.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-03-11 12:26:15.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:15.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:15.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:15.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:26:15.000000 types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.938099 types-aiobotocore-batch-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18208 2023-06-28 01:43:08.938099 types-aiobotocore-batch-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16651 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.938099 types-aiobotocore-batch-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.930099 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/
+-rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1578 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22153 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22115 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10647 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10645 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6988 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6981 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    44081 2023-06-28 01:26:47.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44024 2023-06-28 01:26:46.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:45.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.938099 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18208 2023-06-28 01:43:08.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 01:43:08.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:08.000000 types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/LICENSE` & `types-aiobotocore-batch-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-batch-2.5.0.post1/PKG-INFO` & `types-aiobotocore-batch-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-batch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Batch 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Batch 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-batch"></a>
 
 # types-aiobotocore-batch
 
 [![PyPI - types-aiobotocore-batch](https://img.shields.io/pypi/v/types-aiobotocore-batch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-batch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-batch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-batch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-batch?color=blue)](https://pypistats.org/packages/types-aiobotocore-batch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Batch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch)
+[aiobotocore.Batch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch)
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
 [types-aiobotocore-batch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -364,78 +364,80 @@
     NetworkInterfaceTypeDef,
     CancelJobRequestRequestTypeDef,
     EksConfigurationTypeDef,
     UpdatePolicyTypeDef,
     ComputeEnvironmentOrderTypeDef,
     Ec2ConfigurationTypeDef,
     LaunchTemplateSpecificationTypeDef,
+    EphemeralStorageTypeDef,
     FargatePlatformConfigurationTypeDef,
     KeyValuePairTypeDef,
     MountPointTypeDef,
     NetworkConfigurationTypeDef,
     ResourceRequirementTypeDef,
     SecretTypeDef,
     UlimitTypeDef,
     ContainerSummaryTypeDef,
-    ResponseMetadataTypeDef,
+    CreateComputeEnvironmentResponseTypeDef,
+    CreateJobQueueResponseTypeDef,
+    CreateSchedulingPolicyResponseTypeDef,
     DeleteComputeEnvironmentRequestRequestTypeDef,
     DeleteJobQueueRequestRequestTypeDef,
     DeleteSchedulingPolicyRequestRequestTypeDef,
     DeregisterJobDefinitionRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef,
     DescribeComputeEnvironmentsRequestRequestTypeDef,
+    DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef,
     DescribeJobDefinitionsRequestRequestTypeDef,
+    DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef,
     DescribeJobQueuesRequestRequestTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeSchedulingPoliciesRequestRequestTypeDef,
     DeviceTypeDef,
     EFSAuthorizationConfigTypeDef,
     EksAttemptContainerDetailTypeDef,
     EksContainerEnvironmentVariableTypeDef,
     EksContainerResourceRequirementsTypeDef,
     EksContainerSecurityContextTypeDef,
     EksContainerVolumeMountTypeDef,
     EksEmptyDirTypeDef,
     EksHostPathTypeDef,
+    EksMetadataTypeDef,
     EksSecretTypeDef,
     EvaluateOnExitTypeDef,
     ShareAttributesTypeDef,
     HostTypeDef,
     JobTimeoutTypeDef,
     JobDependencyTypeDef,
     NodeDetailsTypeDef,
     NodePropertiesSummaryTypeDef,
     KeyValuesPairTypeDef,
     TmpfsTypeDef,
+    ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef,
     ListSchedulingPoliciesRequestRequestTypeDef,
     SchedulingPolicyListingDetailTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterJobDefinitionResponseTypeDef,
+    ResponseMetadataTypeDef,
+    SubmitJobResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateJobRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateComputeEnvironmentResponseTypeDef,
+    UpdateJobQueueResponseTypeDef,
     AttemptContainerDetailTypeDef,
     CreateJobQueueRequestRequestTypeDef,
     JobQueueDetailTypeDef,
     UpdateJobQueueRequestRequestTypeDef,
     ComputeResourceTypeDef,
     ComputeResourceUpdateTypeDef,
     ContainerOverridesTypeDef,
     LogConfigurationTypeDef,
-    CreateComputeEnvironmentResponseTypeDef,
-    CreateJobQueueResponseTypeDef,
-    CreateSchedulingPolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterJobDefinitionResponseTypeDef,
-    SubmitJobResponseTypeDef,
-    UpdateComputeEnvironmentResponseTypeDef,
-    UpdateJobQueueResponseTypeDef,
-    DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef,
-    DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef,
-    DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef,
-    ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef,
     EFSVolumeConfigurationTypeDef,
     EksAttemptDetailTypeDef,
     EksContainerOverrideTypeDef,
     EksContainerDetailTypeDef,
     EksContainerTypeDef,
     EksVolumeTypeDef,
     RetryStrategyTypeDef,
@@ -485,43 +487,43 @@
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

### Comparing `types-aiobotocore-batch-2.5.0.post1/README.md` & `types-aiobotocore-batch-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-batch"></a>
 
 # types-aiobotocore-batch
 
 [![PyPI - types-aiobotocore-batch](https://img.shields.io/pypi/v/types-aiobotocore-batch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-batch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-batch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-batch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-batch?color=blue)](https://pypistats.org/packages/types-aiobotocore-batch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Batch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch)
+[aiobotocore.Batch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch)
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
 [types-aiobotocore-batch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,78 +331,80 @@
     NetworkInterfaceTypeDef,
     CancelJobRequestRequestTypeDef,
     EksConfigurationTypeDef,
     UpdatePolicyTypeDef,
     ComputeEnvironmentOrderTypeDef,
     Ec2ConfigurationTypeDef,
     LaunchTemplateSpecificationTypeDef,
+    EphemeralStorageTypeDef,
     FargatePlatformConfigurationTypeDef,
     KeyValuePairTypeDef,
     MountPointTypeDef,
     NetworkConfigurationTypeDef,
     ResourceRequirementTypeDef,
     SecretTypeDef,
     UlimitTypeDef,
     ContainerSummaryTypeDef,
-    ResponseMetadataTypeDef,
+    CreateComputeEnvironmentResponseTypeDef,
+    CreateJobQueueResponseTypeDef,
+    CreateSchedulingPolicyResponseTypeDef,
     DeleteComputeEnvironmentRequestRequestTypeDef,
     DeleteJobQueueRequestRequestTypeDef,
     DeleteSchedulingPolicyRequestRequestTypeDef,
     DeregisterJobDefinitionRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef,
     DescribeComputeEnvironmentsRequestRequestTypeDef,
+    DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef,
     DescribeJobDefinitionsRequestRequestTypeDef,
+    DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef,
     DescribeJobQueuesRequestRequestTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeSchedulingPoliciesRequestRequestTypeDef,
     DeviceTypeDef,
     EFSAuthorizationConfigTypeDef,
     EksAttemptContainerDetailTypeDef,
     EksContainerEnvironmentVariableTypeDef,
     EksContainerResourceRequirementsTypeDef,
     EksContainerSecurityContextTypeDef,
     EksContainerVolumeMountTypeDef,
     EksEmptyDirTypeDef,
     EksHostPathTypeDef,
+    EksMetadataTypeDef,
     EksSecretTypeDef,
     EvaluateOnExitTypeDef,
     ShareAttributesTypeDef,
     HostTypeDef,
     JobTimeoutTypeDef,
     JobDependencyTypeDef,
     NodeDetailsTypeDef,
     NodePropertiesSummaryTypeDef,
     KeyValuesPairTypeDef,
     TmpfsTypeDef,
+    ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef,
     ListSchedulingPoliciesRequestRequestTypeDef,
     SchedulingPolicyListingDetailTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterJobDefinitionResponseTypeDef,
+    ResponseMetadataTypeDef,
+    SubmitJobResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateJobRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateComputeEnvironmentResponseTypeDef,
+    UpdateJobQueueResponseTypeDef,
     AttemptContainerDetailTypeDef,
     CreateJobQueueRequestRequestTypeDef,
     JobQueueDetailTypeDef,
     UpdateJobQueueRequestRequestTypeDef,
     ComputeResourceTypeDef,
     ComputeResourceUpdateTypeDef,
     ContainerOverridesTypeDef,
     LogConfigurationTypeDef,
-    CreateComputeEnvironmentResponseTypeDef,
-    CreateJobQueueResponseTypeDef,
-    CreateSchedulingPolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterJobDefinitionResponseTypeDef,
-    SubmitJobResponseTypeDef,
-    UpdateComputeEnvironmentResponseTypeDef,
-    UpdateJobQueueResponseTypeDef,
-    DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef,
-    DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef,
-    DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef,
-    ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef,
     EFSVolumeConfigurationTypeDef,
     EksAttemptDetailTypeDef,
     EksContainerOverrideTypeDef,
     EksContainerDetailTypeDef,
     EksContainerTypeDef,
     EksVolumeTypeDef,
     RetryStrategyTypeDef,
@@ -452,43 +454,43 @@
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

### Comparing `types-aiobotocore-batch-2.5.0.post1/setup.py` & `types-aiobotocore-batch-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-batch.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-batch",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_batch"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Batch 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Batch 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/"
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

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/__init__.py` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/__init__.pyi` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/__main__.py` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Batch 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Batch 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch\nOther"
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

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/client.py` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/client.pyi` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/literals.py` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -139,14 +139,15 @@
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
@@ -225,14 +226,15 @@
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
@@ -243,14 +245,15 @@
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
@@ -286,14 +289,15 @@
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
@@ -312,16 +316,19 @@
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
@@ -405,15 +412,17 @@
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
@@ -445,21 +454,25 @@
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/literals.pyi` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/literals.pyi`

 * *Files 5% similar despite different names*

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
@@ -443,21 +452,25 @@
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/paginator.py` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         describe_compute_environments_paginator: DescribeComputeEnvironmentsPaginator = client.get_paginator("describe_compute_environments")
         describe_job_definitions_paginator: DescribeJobDefinitionsPaginator = client.get_paginator("describe_job_definitions")
         describe_job_queues_paginator: DescribeJobQueuesPaginator = client.get_paginator("describe_job_queues")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_scheduling_policies_paginator: ListSchedulingPoliciesPaginator = client.get_paginator("list_scheduling_policies")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import JobStatusType
 from .type_defs import (
     DescribeComputeEnvironmentsResponseTypeDef,
@@ -41,120 +40,107 @@
     DescribeJobQueuesResponseTypeDef,
     KeyValuesPairTypeDef,
     ListJobsResponseTypeDef,
     ListSchedulingPoliciesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeComputeEnvironmentsPaginator",
     "DescribeJobDefinitionsPaginator",
     "DescribeJobQueuesPaginator",
     "ListJobsPaginator",
     "ListSchedulingPoliciesPaginator",
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
 class DescribeComputeEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeComputeEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describecomputeenvironmentspaginator)
     """
 
     def paginate(
         self,
         *,
         computeEnvironments: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeComputeEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeComputeEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describecomputeenvironmentspaginator)
         """
 
-
 class DescribeJobDefinitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobDefinitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobdefinitionspaginator)
     """
 
     def paginate(
         self,
         *,
         jobDefinitions: Sequence[str] = ...,
         jobDefinitionName: str = ...,
         status: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobdefinitionspaginator)
         """
 
-
 class DescribeJobQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobqueuespaginator)
     """
 
     def paginate(
-        self, *, jobQueues: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobQueues: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobQueuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobqueuespaginator)
         """
 
-
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listjobspaginator)
     """
 
     def paginate(
         self,
         *,
         jobQueue: str = ...,
         arrayJobId: str = ...,
         multiNodeJobId: str = ...,
         jobStatus: JobStatusType = ...,
         filters: Sequence[KeyValuesPairTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listjobspaginator)
         """
 
-
 class ListSchedulingPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListSchedulingPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listschedulingpoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchedulingPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListSchedulingPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listschedulingpoliciespaginator)
         """
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/paginator.pyi` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         describe_compute_environments_paginator: DescribeComputeEnvironmentsPaginator = client.get_paginator("describe_compute_environments")
         describe_job_definitions_paginator: DescribeJobDefinitionsPaginator = client.get_paginator("describe_job_definitions")
         describe_job_queues_paginator: DescribeJobQueuesPaginator = client.get_paginator("describe_job_queues")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_scheduling_policies_paginator: ListSchedulingPoliciesPaginator = client.get_paginator("list_scheduling_policies")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import JobStatusType
 from .type_defs import (
     DescribeComputeEnvironmentsResponseTypeDef,
@@ -41,112 +40,114 @@
     DescribeJobQueuesResponseTypeDef,
     KeyValuesPairTypeDef,
     ListJobsResponseTypeDef,
     ListSchedulingPoliciesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeComputeEnvironmentsPaginator",
     "DescribeJobDefinitionsPaginator",
     "DescribeJobQueuesPaginator",
     "ListJobsPaginator",
     "ListSchedulingPoliciesPaginator",
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
 class DescribeComputeEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeComputeEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describecomputeenvironmentspaginator)
     """
 
     def paginate(
         self,
         *,
         computeEnvironments: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeComputeEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeComputeEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describecomputeenvironmentspaginator)
         """
 
+
 class DescribeJobDefinitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobDefinitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobdefinitionspaginator)
     """
 
     def paginate(
         self,
         *,
         jobDefinitions: Sequence[str] = ...,
         jobDefinitionName: str = ...,
         status: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobdefinitionspaginator)
         """
 
+
 class DescribeJobQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobqueuespaginator)
     """
 
     def paginate(
-        self, *, jobQueues: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobQueues: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobQueuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.DescribeJobQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#describejobqueuespaginator)
         """
 
+
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listjobspaginator)
     """
 
     def paginate(
         self,
         *,
         jobQueue: str = ...,
         arrayJobId: str = ...,
         multiNodeJobId: str = ...,
         jobStatus: JobStatusType = ...,
         filters: Sequence[KeyValuesPairTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listjobspaginator)
         """
 
+
 class ListSchedulingPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListSchedulingPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listschedulingpoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchedulingPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch.Paginator.ListSchedulingPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/paginators/#listschedulingpoliciespaginator)
         """
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/type_defs.py` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -50,78 +50,80 @@
     "NetworkInterfaceTypeDef",
     "CancelJobRequestRequestTypeDef",
     "EksConfigurationTypeDef",
     "UpdatePolicyTypeDef",
     "ComputeEnvironmentOrderTypeDef",
     "Ec2ConfigurationTypeDef",
     "LaunchTemplateSpecificationTypeDef",
+    "EphemeralStorageTypeDef",
     "FargatePlatformConfigurationTypeDef",
     "KeyValuePairTypeDef",
     "MountPointTypeDef",
     "NetworkConfigurationTypeDef",
     "ResourceRequirementTypeDef",
     "SecretTypeDef",
     "UlimitTypeDef",
     "ContainerSummaryTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateComputeEnvironmentResponseTypeDef",
+    "CreateJobQueueResponseTypeDef",
+    "CreateSchedulingPolicyResponseTypeDef",
     "DeleteComputeEnvironmentRequestRequestTypeDef",
     "DeleteJobQueueRequestRequestTypeDef",
     "DeleteSchedulingPolicyRequestRequestTypeDef",
     "DeregisterJobDefinitionRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
     "DescribeComputeEnvironmentsRequestRequestTypeDef",
+    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
     "DescribeJobDefinitionsRequestRequestTypeDef",
+    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
     "DescribeJobQueuesRequestRequestTypeDef",
     "DescribeJobsRequestRequestTypeDef",
     "DescribeSchedulingPoliciesRequestRequestTypeDef",
     "DeviceTypeDef",
     "EFSAuthorizationConfigTypeDef",
     "EksAttemptContainerDetailTypeDef",
     "EksContainerEnvironmentVariableTypeDef",
     "EksContainerResourceRequirementsTypeDef",
     "EksContainerSecurityContextTypeDef",
     "EksContainerVolumeMountTypeDef",
     "EksEmptyDirTypeDef",
     "EksHostPathTypeDef",
+    "EksMetadataTypeDef",
     "EksSecretTypeDef",
     "EvaluateOnExitTypeDef",
     "ShareAttributesTypeDef",
     "HostTypeDef",
     "JobTimeoutTypeDef",
     "JobDependencyTypeDef",
     "NodeDetailsTypeDef",
     "NodePropertiesSummaryTypeDef",
     "KeyValuesPairTypeDef",
     "TmpfsTypeDef",
+    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
     "ListSchedulingPoliciesRequestRequestTypeDef",
     "SchedulingPolicyListingDetailTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "RegisterJobDefinitionResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "SubmitJobResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TerminateJobRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateComputeEnvironmentResponseTypeDef",
+    "UpdateJobQueueResponseTypeDef",
     "AttemptContainerDetailTypeDef",
     "CreateJobQueueRequestRequestTypeDef",
     "JobQueueDetailTypeDef",
     "UpdateJobQueueRequestRequestTypeDef",
     "ComputeResourceTypeDef",
     "ComputeResourceUpdateTypeDef",
     "ContainerOverridesTypeDef",
     "LogConfigurationTypeDef",
-    "CreateComputeEnvironmentResponseTypeDef",
-    "CreateJobQueueResponseTypeDef",
-    "CreateSchedulingPolicyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterJobDefinitionResponseTypeDef",
-    "SubmitJobResponseTypeDef",
-    "UpdateComputeEnvironmentResponseTypeDef",
-    "UpdateJobQueueResponseTypeDef",
-    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
-    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
-    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
-    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
     "EFSVolumeConfigurationTypeDef",
     "EksAttemptDetailTypeDef",
     "EksContainerOverrideTypeDef",
     "EksContainerDetailTypeDef",
     "EksContainerTypeDef",
     "EksVolumeTypeDef",
     "RetryStrategyTypeDef",
@@ -259,14 +261,21 @@
         "launchTemplateId": str,
         "launchTemplateName": str,
         "version": str,
     },
     total=False,
 )
 
+EphemeralStorageTypeDef = TypedDict(
+    "EphemeralStorageTypeDef",
+    {
+        "sizeInGiB": int,
+    },
+)
+
 FargatePlatformConfigurationTypeDef = TypedDict(
     "FargatePlatformConfigurationTypeDef",
     {
         "platformVersion": str,
     },
     total=False,
 )
@@ -328,22 +337,38 @@
     {
         "exitCode": int,
         "reason": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateComputeEnvironmentResponseTypeDef = TypedDict(
+    "CreateComputeEnvironmentResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "computeEnvironmentName": str,
+        "computeEnvironmentArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateJobQueueResponseTypeDef = TypedDict(
+    "CreateJobQueueResponseTypeDef",
+    {
+        "jobQueueName": str,
+        "jobQueueArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSchedulingPolicyResponseTypeDef = TypedDict(
+    "CreateSchedulingPolicyResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteComputeEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteComputeEnvironmentRequestRequestTypeDef",
     {
         "computeEnvironment": str,
@@ -367,46 +392,65 @@
 DeregisterJobDefinitionRequestRequestTypeDef = TypedDict(
     "DeregisterJobDefinitionRequestRequestTypeDef",
     {
         "jobDefinition": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef = TypedDict(
+    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "computeEnvironments": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeComputeEnvironmentsRequestRequestTypeDef = TypedDict(
     "DescribeComputeEnvironmentsRequestRequestTypeDef",
     {
         "computeEnvironments": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef = TypedDict(
+    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
+    {
+        "jobDefinitions": Sequence[str],
+        "jobDefinitionName": str,
+        "status": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeJobDefinitionsRequestRequestTypeDef = TypedDict(
     "DescribeJobDefinitionsRequestRequestTypeDef",
     {
         "jobDefinitions": Sequence[str],
         "maxResults": int,
         "jobDefinitionName": str,
         "status": str,
         "nextToken": str,
     },
     total=False,
 )
 
+DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef = TypedDict(
+    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
+    {
+        "jobQueues": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeJobQueuesRequestRequestTypeDef = TypedDict(
     "DescribeJobQueuesRequestRequestTypeDef",
     {
         "jobQueues": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
@@ -530,14 +574,22 @@
     "EksHostPathTypeDef",
     {
         "path": str,
     },
     total=False,
 )
 
+EksMetadataTypeDef = TypedDict(
+    "EksMetadataTypeDef",
+    {
+        "labels": Dict[str, str],
+    },
+    total=False,
+)
+
 _RequiredEksSecretTypeDef = TypedDict(
     "_RequiredEksSecretTypeDef",
     {
         "secretName": str,
     },
 )
 _OptionalEksSecretTypeDef = TypedDict(
@@ -662,14 +714,22 @@
 )
 
 
 class TmpfsTypeDef(_RequiredTmpfsTypeDef, _OptionalTmpfsTypeDef):
     pass
 
 
+ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef = TypedDict(
+    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchedulingPoliciesRequestRequestTypeDef = TypedDict(
     "ListSchedulingPoliciesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -685,14 +745,63 @@
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
+RegisterJobDefinitionResponseTypeDef = TypedDict(
+    "RegisterJobDefinitionResponseTypeDef",
+    {
+        "jobDefinitionName": str,
+        "jobDefinitionArn": str,
+        "revision": int,
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
+SubmitJobResponseTypeDef = TypedDict(
+    "SubmitJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobName": str,
+        "jobId": str,
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
@@ -709,14 +818,32 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateComputeEnvironmentResponseTypeDef = TypedDict(
+    "UpdateComputeEnvironmentResponseTypeDef",
+    {
+        "computeEnvironmentName": str,
+        "computeEnvironmentArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateJobQueueResponseTypeDef = TypedDict(
+    "UpdateJobQueueResponseTypeDef",
+    {
+        "jobQueueName": str,
+        "jobQueueArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttemptContainerDetailTypeDef = TypedDict(
     "AttemptContainerDetailTypeDef",
     {
         "containerInstanceArn": str,
         "taskArn": str,
         "exitCode": int,
         "reason": str,
@@ -888,124 +1015,14 @@
 )
 
 
 class LogConfigurationTypeDef(_RequiredLogConfigurationTypeDef, _OptionalLogConfigurationTypeDef):
     pass
 
 
-CreateComputeEnvironmentResponseTypeDef = TypedDict(
-    "CreateComputeEnvironmentResponseTypeDef",
-    {
-        "computeEnvironmentName": str,
-        "computeEnvironmentArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobQueueResponseTypeDef = TypedDict(
-    "CreateJobQueueResponseTypeDef",
-    {
-        "jobQueueName": str,
-        "jobQueueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchedulingPolicyResponseTypeDef = TypedDict(
-    "CreateSchedulingPolicyResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
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
-RegisterJobDefinitionResponseTypeDef = TypedDict(
-    "RegisterJobDefinitionResponseTypeDef",
-    {
-        "jobDefinitionName": str,
-        "jobDefinitionArn": str,
-        "revision": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitJobResponseTypeDef = TypedDict(
-    "SubmitJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobName": str,
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateComputeEnvironmentResponseTypeDef = TypedDict(
-    "UpdateComputeEnvironmentResponseTypeDef",
-    {
-        "computeEnvironmentName": str,
-        "computeEnvironmentArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateJobQueueResponseTypeDef = TypedDict(
-    "UpdateJobQueueResponseTypeDef",
-    {
-        "jobQueueName": str,
-        "jobQueueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef = TypedDict(
-    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
-    {
-        "computeEnvironments": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef = TypedDict(
-    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
-    {
-        "jobDefinitions": Sequence[str],
-        "jobDefinitionName": str,
-        "status": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef = TypedDict(
-    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
-    {
-        "jobQueues": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef = TypedDict(
-    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredEFSVolumeConfigurationTypeDef = TypedDict(
     "_RequiredEFSVolumeConfigurationTypeDef",
     {
         "fileSystemId": str,
     },
 )
 _OptionalEFSVolumeConfigurationTypeDef = TypedDict(
@@ -1168,15 +1185,15 @@
     "ListJobsRequestListJobsPaginateTypeDef",
     {
         "jobQueue": str,
         "arrayJobId": str,
         "multiNodeJobId": str,
         "jobStatus": JobStatusType,
         "filters": Sequence[KeyValuesPairTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
@@ -1205,15 +1222,15 @@
 )
 
 ListSchedulingPoliciesResponseTypeDef = TypedDict(
     "ListSchedulingPoliciesResponseTypeDef",
     {
         "schedulingPolicies": List[SchedulingPolicyListingDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttemptDetailTypeDef = TypedDict(
     "AttemptDetailTypeDef",
     {
         "container": AttemptContainerDetailTypeDef,
@@ -1225,15 +1242,15 @@
 )
 
 DescribeJobQueuesResponseTypeDef = TypedDict(
     "DescribeJobQueuesResponseTypeDef",
     {
         "jobQueues": List[JobQueueDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredComputeEnvironmentDetailTypeDef = TypedDict(
     "_RequiredComputeEnvironmentDetailTypeDef",
     {
         "computeEnvironmentName": str,
@@ -1352,40 +1369,43 @@
     total=False,
 )
 
 EksPodPropertiesOverrideTypeDef = TypedDict(
     "EksPodPropertiesOverrideTypeDef",
     {
         "containers": Sequence[EksContainerOverrideTypeDef],
+        "metadata": EksMetadataTypeDef,
     },
     total=False,
 )
 
 EksPodPropertiesDetailTypeDef = TypedDict(
     "EksPodPropertiesDetailTypeDef",
     {
         "serviceAccountName": str,
         "hostNetwork": bool,
         "dnsPolicy": str,
         "containers": List[EksContainerDetailTypeDef],
         "volumes": List[EksVolumeTypeDef],
         "podName": str,
         "nodeName": str,
+        "metadata": EksMetadataTypeDef,
     },
     total=False,
 )
 
 EksPodPropertiesTypeDef = TypedDict(
     "EksPodPropertiesTypeDef",
     {
         "serviceAccountName": str,
         "hostNetwork": bool,
         "dnsPolicy": str,
         "containers": List[EksContainerTypeDef],
         "volumes": List[EksVolumeTypeDef],
+        "metadata": EksMetadataTypeDef,
     },
     total=False,
 )
 
 _RequiredCreateSchedulingPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSchedulingPolicyRequestRequestTypeDef",
     {
@@ -1455,24 +1475,24 @@
 
 
 ListJobsResponseTypeDef = TypedDict(
     "ListJobsResponseTypeDef",
     {
         "jobSummaryList": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComputeEnvironmentsResponseTypeDef = TypedDict(
     "DescribeComputeEnvironmentsResponseTypeDef",
     {
         "computeEnvironments": List[ComputeEnvironmentDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodeOverridesTypeDef = TypedDict(
     "NodeOverridesTypeDef",
     {
         "numNodes": int,
@@ -1506,14 +1526,15 @@
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "resourceRequirements": List[ResourceRequirementTypeDef],
         "linuxParameters": LinuxParametersTypeDef,
         "logConfiguration": LogConfigurationTypeDef,
         "secrets": List[SecretTypeDef],
         "networkConfiguration": NetworkConfigurationTypeDef,
         "fargatePlatformConfiguration": FargatePlatformConfigurationTypeDef,
+        "ephemeralStorage": EphemeralStorageTypeDef,
     },
     total=False,
 )
 
 ContainerPropertiesTypeDef = TypedDict(
     "ContainerPropertiesTypeDef",
     {
@@ -1533,14 +1554,15 @@
         "instanceType": str,
         "resourceRequirements": List[ResourceRequirementTypeDef],
         "linuxParameters": LinuxParametersTypeDef,
         "logConfiguration": LogConfigurationTypeDef,
         "secrets": List[SecretTypeDef],
         "networkConfiguration": NetworkConfigurationTypeDef,
         "fargatePlatformConfiguration": FargatePlatformConfigurationTypeDef,
+        "ephemeralStorage": EphemeralStorageTypeDef,
     },
     total=False,
 )
 
 EksPropertiesOverrideTypeDef = TypedDict(
     "EksPropertiesOverrideTypeDef",
     {
@@ -1565,15 +1587,15 @@
     total=False,
 )
 
 DescribeSchedulingPoliciesResponseTypeDef = TypedDict(
     "DescribeSchedulingPoliciesResponseTypeDef",
     {
         "schedulingPolicies": List[SchedulingPolicyDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNodeRangePropertyTypeDef = TypedDict(
     "_RequiredNodeRangePropertyTypeDef",
     {
         "targetNodes": str,
@@ -1748,18 +1770,18 @@
 
 
 DescribeJobDefinitionsResponseTypeDef = TypedDict(
     "DescribeJobDefinitionsResponseTypeDef",
     {
         "jobDefinitions": List[JobDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeJobsResponseTypeDef = TypedDict(
     "DescribeJobsResponseTypeDef",
     {
         "jobs": List[JobDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch/type_defs.pyi` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -49,78 +49,80 @@
     "NetworkInterfaceTypeDef",
     "CancelJobRequestRequestTypeDef",
     "EksConfigurationTypeDef",
     "UpdatePolicyTypeDef",
     "ComputeEnvironmentOrderTypeDef",
     "Ec2ConfigurationTypeDef",
     "LaunchTemplateSpecificationTypeDef",
+    "EphemeralStorageTypeDef",
     "FargatePlatformConfigurationTypeDef",
     "KeyValuePairTypeDef",
     "MountPointTypeDef",
     "NetworkConfigurationTypeDef",
     "ResourceRequirementTypeDef",
     "SecretTypeDef",
     "UlimitTypeDef",
     "ContainerSummaryTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateComputeEnvironmentResponseTypeDef",
+    "CreateJobQueueResponseTypeDef",
+    "CreateSchedulingPolicyResponseTypeDef",
     "DeleteComputeEnvironmentRequestRequestTypeDef",
     "DeleteJobQueueRequestRequestTypeDef",
     "DeleteSchedulingPolicyRequestRequestTypeDef",
     "DeregisterJobDefinitionRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
     "DescribeComputeEnvironmentsRequestRequestTypeDef",
+    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
     "DescribeJobDefinitionsRequestRequestTypeDef",
+    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
     "DescribeJobQueuesRequestRequestTypeDef",
     "DescribeJobsRequestRequestTypeDef",
     "DescribeSchedulingPoliciesRequestRequestTypeDef",
     "DeviceTypeDef",
     "EFSAuthorizationConfigTypeDef",
     "EksAttemptContainerDetailTypeDef",
     "EksContainerEnvironmentVariableTypeDef",
     "EksContainerResourceRequirementsTypeDef",
     "EksContainerSecurityContextTypeDef",
     "EksContainerVolumeMountTypeDef",
     "EksEmptyDirTypeDef",
     "EksHostPathTypeDef",
+    "EksMetadataTypeDef",
     "EksSecretTypeDef",
     "EvaluateOnExitTypeDef",
     "ShareAttributesTypeDef",
     "HostTypeDef",
     "JobTimeoutTypeDef",
     "JobDependencyTypeDef",
     "NodeDetailsTypeDef",
     "NodePropertiesSummaryTypeDef",
     "KeyValuesPairTypeDef",
     "TmpfsTypeDef",
+    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
     "ListSchedulingPoliciesRequestRequestTypeDef",
     "SchedulingPolicyListingDetailTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "RegisterJobDefinitionResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "SubmitJobResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TerminateJobRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateComputeEnvironmentResponseTypeDef",
+    "UpdateJobQueueResponseTypeDef",
     "AttemptContainerDetailTypeDef",
     "CreateJobQueueRequestRequestTypeDef",
     "JobQueueDetailTypeDef",
     "UpdateJobQueueRequestRequestTypeDef",
     "ComputeResourceTypeDef",
     "ComputeResourceUpdateTypeDef",
     "ContainerOverridesTypeDef",
     "LogConfigurationTypeDef",
-    "CreateComputeEnvironmentResponseTypeDef",
-    "CreateJobQueueResponseTypeDef",
-    "CreateSchedulingPolicyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterJobDefinitionResponseTypeDef",
-    "SubmitJobResponseTypeDef",
-    "UpdateComputeEnvironmentResponseTypeDef",
-    "UpdateJobQueueResponseTypeDef",
-    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
-    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
-    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
-    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
     "EFSVolumeConfigurationTypeDef",
     "EksAttemptDetailTypeDef",
     "EksContainerOverrideTypeDef",
     "EksContainerDetailTypeDef",
     "EksContainerTypeDef",
     "EksVolumeTypeDef",
     "RetryStrategyTypeDef",
@@ -256,14 +258,21 @@
         "launchTemplateId": str,
         "launchTemplateName": str,
         "version": str,
     },
     total=False,
 )
 
+EphemeralStorageTypeDef = TypedDict(
+    "EphemeralStorageTypeDef",
+    {
+        "sizeInGiB": int,
+    },
+)
+
 FargatePlatformConfigurationTypeDef = TypedDict(
     "FargatePlatformConfigurationTypeDef",
     {
         "platformVersion": str,
     },
     total=False,
 )
@@ -325,22 +334,38 @@
     {
         "exitCode": int,
         "reason": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateComputeEnvironmentResponseTypeDef = TypedDict(
+    "CreateComputeEnvironmentResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "computeEnvironmentName": str,
+        "computeEnvironmentArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateJobQueueResponseTypeDef = TypedDict(
+    "CreateJobQueueResponseTypeDef",
+    {
+        "jobQueueName": str,
+        "jobQueueArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSchedulingPolicyResponseTypeDef = TypedDict(
+    "CreateSchedulingPolicyResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteComputeEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteComputeEnvironmentRequestRequestTypeDef",
     {
         "computeEnvironment": str,
@@ -364,46 +389,65 @@
 DeregisterJobDefinitionRequestRequestTypeDef = TypedDict(
     "DeregisterJobDefinitionRequestRequestTypeDef",
     {
         "jobDefinition": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef = TypedDict(
+    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "computeEnvironments": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeComputeEnvironmentsRequestRequestTypeDef = TypedDict(
     "DescribeComputeEnvironmentsRequestRequestTypeDef",
     {
         "computeEnvironments": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef = TypedDict(
+    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
+    {
+        "jobDefinitions": Sequence[str],
+        "jobDefinitionName": str,
+        "status": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeJobDefinitionsRequestRequestTypeDef = TypedDict(
     "DescribeJobDefinitionsRequestRequestTypeDef",
     {
         "jobDefinitions": Sequence[str],
         "maxResults": int,
         "jobDefinitionName": str,
         "status": str,
         "nextToken": str,
     },
     total=False,
 )
 
+DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef = TypedDict(
+    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
+    {
+        "jobQueues": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeJobQueuesRequestRequestTypeDef = TypedDict(
     "DescribeJobQueuesRequestRequestTypeDef",
     {
         "jobQueues": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
@@ -523,14 +567,22 @@
     "EksHostPathTypeDef",
     {
         "path": str,
     },
     total=False,
 )
 
+EksMetadataTypeDef = TypedDict(
+    "EksMetadataTypeDef",
+    {
+        "labels": Dict[str, str],
+    },
+    total=False,
+)
+
 _RequiredEksSecretTypeDef = TypedDict(
     "_RequiredEksSecretTypeDef",
     {
         "secretName": str,
     },
 )
 _OptionalEksSecretTypeDef = TypedDict(
@@ -647,14 +699,22 @@
     },
     total=False,
 )
 
 class TmpfsTypeDef(_RequiredTmpfsTypeDef, _OptionalTmpfsTypeDef):
     pass
 
+ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef = TypedDict(
+    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchedulingPoliciesRequestRequestTypeDef = TypedDict(
     "ListSchedulingPoliciesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -670,14 +730,63 @@
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
+RegisterJobDefinitionResponseTypeDef = TypedDict(
+    "RegisterJobDefinitionResponseTypeDef",
+    {
+        "jobDefinitionName": str,
+        "jobDefinitionArn": str,
+        "revision": int,
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
+SubmitJobResponseTypeDef = TypedDict(
+    "SubmitJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobName": str,
+        "jobId": str,
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
@@ -694,14 +803,32 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateComputeEnvironmentResponseTypeDef = TypedDict(
+    "UpdateComputeEnvironmentResponseTypeDef",
+    {
+        "computeEnvironmentName": str,
+        "computeEnvironmentArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateJobQueueResponseTypeDef = TypedDict(
+    "UpdateJobQueueResponseTypeDef",
+    {
+        "jobQueueName": str,
+        "jobQueueArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttemptContainerDetailTypeDef = TypedDict(
     "AttemptContainerDetailTypeDef",
     {
         "containerInstanceArn": str,
         "taskArn": str,
         "exitCode": int,
         "reason": str,
@@ -863,124 +990,14 @@
     },
     total=False,
 )
 
 class LogConfigurationTypeDef(_RequiredLogConfigurationTypeDef, _OptionalLogConfigurationTypeDef):
     pass
 
-CreateComputeEnvironmentResponseTypeDef = TypedDict(
-    "CreateComputeEnvironmentResponseTypeDef",
-    {
-        "computeEnvironmentName": str,
-        "computeEnvironmentArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobQueueResponseTypeDef = TypedDict(
-    "CreateJobQueueResponseTypeDef",
-    {
-        "jobQueueName": str,
-        "jobQueueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchedulingPolicyResponseTypeDef = TypedDict(
-    "CreateSchedulingPolicyResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
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
-RegisterJobDefinitionResponseTypeDef = TypedDict(
-    "RegisterJobDefinitionResponseTypeDef",
-    {
-        "jobDefinitionName": str,
-        "jobDefinitionArn": str,
-        "revision": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitJobResponseTypeDef = TypedDict(
-    "SubmitJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobName": str,
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateComputeEnvironmentResponseTypeDef = TypedDict(
-    "UpdateComputeEnvironmentResponseTypeDef",
-    {
-        "computeEnvironmentName": str,
-        "computeEnvironmentArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateJobQueueResponseTypeDef = TypedDict(
-    "UpdateJobQueueResponseTypeDef",
-    {
-        "jobQueueName": str,
-        "jobQueueArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef = TypedDict(
-    "DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef",
-    {
-        "computeEnvironments": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef = TypedDict(
-    "DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef",
-    {
-        "jobDefinitions": Sequence[str],
-        "jobDefinitionName": str,
-        "status": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef = TypedDict(
-    "DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef",
-    {
-        "jobQueues": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef = TypedDict(
-    "ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredEFSVolumeConfigurationTypeDef = TypedDict(
     "_RequiredEFSVolumeConfigurationTypeDef",
     {
         "fileSystemId": str,
     },
 )
 _OptionalEFSVolumeConfigurationTypeDef = TypedDict(
@@ -1135,15 +1152,15 @@
     "ListJobsRequestListJobsPaginateTypeDef",
     {
         "jobQueue": str,
         "arrayJobId": str,
         "multiNodeJobId": str,
         "jobStatus": JobStatusType,
         "filters": Sequence[KeyValuesPairTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
@@ -1172,15 +1189,15 @@
 )
 
 ListSchedulingPoliciesResponseTypeDef = TypedDict(
     "ListSchedulingPoliciesResponseTypeDef",
     {
         "schedulingPolicies": List[SchedulingPolicyListingDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttemptDetailTypeDef = TypedDict(
     "AttemptDetailTypeDef",
     {
         "container": AttemptContainerDetailTypeDef,
@@ -1192,15 +1209,15 @@
 )
 
 DescribeJobQueuesResponseTypeDef = TypedDict(
     "DescribeJobQueuesResponseTypeDef",
     {
         "jobQueues": List[JobQueueDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredComputeEnvironmentDetailTypeDef = TypedDict(
     "_RequiredComputeEnvironmentDetailTypeDef",
     {
         "computeEnvironmentName": str,
@@ -1311,40 +1328,43 @@
     total=False,
 )
 
 EksPodPropertiesOverrideTypeDef = TypedDict(
     "EksPodPropertiesOverrideTypeDef",
     {
         "containers": Sequence[EksContainerOverrideTypeDef],
+        "metadata": EksMetadataTypeDef,
     },
     total=False,
 )
 
 EksPodPropertiesDetailTypeDef = TypedDict(
     "EksPodPropertiesDetailTypeDef",
     {
         "serviceAccountName": str,
         "hostNetwork": bool,
         "dnsPolicy": str,
         "containers": List[EksContainerDetailTypeDef],
         "volumes": List[EksVolumeTypeDef],
         "podName": str,
         "nodeName": str,
+        "metadata": EksMetadataTypeDef,
     },
     total=False,
 )
 
 EksPodPropertiesTypeDef = TypedDict(
     "EksPodPropertiesTypeDef",
     {
         "serviceAccountName": str,
         "hostNetwork": bool,
         "dnsPolicy": str,
         "containers": List[EksContainerTypeDef],
         "volumes": List[EksVolumeTypeDef],
+        "metadata": EksMetadataTypeDef,
     },
     total=False,
 )
 
 _RequiredCreateSchedulingPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSchedulingPolicyRequestRequestTypeDef",
     {
@@ -1408,24 +1428,24 @@
     pass
 
 ListJobsResponseTypeDef = TypedDict(
     "ListJobsResponseTypeDef",
     {
         "jobSummaryList": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComputeEnvironmentsResponseTypeDef = TypedDict(
     "DescribeComputeEnvironmentsResponseTypeDef",
     {
         "computeEnvironments": List[ComputeEnvironmentDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodeOverridesTypeDef = TypedDict(
     "NodeOverridesTypeDef",
     {
         "numNodes": int,
@@ -1459,14 +1479,15 @@
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "resourceRequirements": List[ResourceRequirementTypeDef],
         "linuxParameters": LinuxParametersTypeDef,
         "logConfiguration": LogConfigurationTypeDef,
         "secrets": List[SecretTypeDef],
         "networkConfiguration": NetworkConfigurationTypeDef,
         "fargatePlatformConfiguration": FargatePlatformConfigurationTypeDef,
+        "ephemeralStorage": EphemeralStorageTypeDef,
     },
     total=False,
 )
 
 ContainerPropertiesTypeDef = TypedDict(
     "ContainerPropertiesTypeDef",
     {
@@ -1486,14 +1507,15 @@
         "instanceType": str,
         "resourceRequirements": List[ResourceRequirementTypeDef],
         "linuxParameters": LinuxParametersTypeDef,
         "logConfiguration": LogConfigurationTypeDef,
         "secrets": List[SecretTypeDef],
         "networkConfiguration": NetworkConfigurationTypeDef,
         "fargatePlatformConfiguration": FargatePlatformConfigurationTypeDef,
+        "ephemeralStorage": EphemeralStorageTypeDef,
     },
     total=False,
 )
 
 EksPropertiesOverrideTypeDef = TypedDict(
     "EksPropertiesOverrideTypeDef",
     {
@@ -1518,15 +1540,15 @@
     total=False,
 )
 
 DescribeSchedulingPoliciesResponseTypeDef = TypedDict(
     "DescribeSchedulingPoliciesResponseTypeDef",
     {
         "schedulingPolicies": List[SchedulingPolicyDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNodeRangePropertyTypeDef = TypedDict(
     "_RequiredNodeRangePropertyTypeDef",
     {
         "targetNodes": str,
@@ -1691,18 +1713,18 @@
     pass
 
 DescribeJobDefinitionsResponseTypeDef = TypedDict(
     "DescribeJobDefinitionsResponseTypeDef",
     {
         "jobDefinitions": List[JobDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeJobsResponseTypeDef = TypedDict(
     "DescribeJobsResponseTypeDef",
     {
         "jobs": List[JobDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/PKG-INFO` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-batch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Batch 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Batch 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-batch"></a>
 
 # types-aiobotocore-batch
 
 [![PyPI - types-aiobotocore-batch](https://img.shields.io/pypi/v/types-aiobotocore-batch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-batch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-batch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-batch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-batch?color=blue)](https://pypistats.org/packages/types-aiobotocore-batch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Batch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch)
+[aiobotocore.Batch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/batch.html#Batch)
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
 [types-aiobotocore-batch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_batch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -364,78 +364,80 @@
     NetworkInterfaceTypeDef,
     CancelJobRequestRequestTypeDef,
     EksConfigurationTypeDef,
     UpdatePolicyTypeDef,
     ComputeEnvironmentOrderTypeDef,
     Ec2ConfigurationTypeDef,
     LaunchTemplateSpecificationTypeDef,
+    EphemeralStorageTypeDef,
     FargatePlatformConfigurationTypeDef,
     KeyValuePairTypeDef,
     MountPointTypeDef,
     NetworkConfigurationTypeDef,
     ResourceRequirementTypeDef,
     SecretTypeDef,
     UlimitTypeDef,
     ContainerSummaryTypeDef,
-    ResponseMetadataTypeDef,
+    CreateComputeEnvironmentResponseTypeDef,
+    CreateJobQueueResponseTypeDef,
+    CreateSchedulingPolicyResponseTypeDef,
     DeleteComputeEnvironmentRequestRequestTypeDef,
     DeleteJobQueueRequestRequestTypeDef,
     DeleteSchedulingPolicyRequestRequestTypeDef,
     DeregisterJobDefinitionRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef,
     DescribeComputeEnvironmentsRequestRequestTypeDef,
+    DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef,
     DescribeJobDefinitionsRequestRequestTypeDef,
+    DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef,
     DescribeJobQueuesRequestRequestTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeSchedulingPoliciesRequestRequestTypeDef,
     DeviceTypeDef,
     EFSAuthorizationConfigTypeDef,
     EksAttemptContainerDetailTypeDef,
     EksContainerEnvironmentVariableTypeDef,
     EksContainerResourceRequirementsTypeDef,
     EksContainerSecurityContextTypeDef,
     EksContainerVolumeMountTypeDef,
     EksEmptyDirTypeDef,
     EksHostPathTypeDef,
+    EksMetadataTypeDef,
     EksSecretTypeDef,
     EvaluateOnExitTypeDef,
     ShareAttributesTypeDef,
     HostTypeDef,
     JobTimeoutTypeDef,
     JobDependencyTypeDef,
     NodeDetailsTypeDef,
     NodePropertiesSummaryTypeDef,
     KeyValuesPairTypeDef,
     TmpfsTypeDef,
+    ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef,
     ListSchedulingPoliciesRequestRequestTypeDef,
     SchedulingPolicyListingDetailTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    RegisterJobDefinitionResponseTypeDef,
+    ResponseMetadataTypeDef,
+    SubmitJobResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateJobRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateComputeEnvironmentResponseTypeDef,
+    UpdateJobQueueResponseTypeDef,
     AttemptContainerDetailTypeDef,
     CreateJobQueueRequestRequestTypeDef,
     JobQueueDetailTypeDef,
     UpdateJobQueueRequestRequestTypeDef,
     ComputeResourceTypeDef,
     ComputeResourceUpdateTypeDef,
     ContainerOverridesTypeDef,
     LogConfigurationTypeDef,
-    CreateComputeEnvironmentResponseTypeDef,
-    CreateJobQueueResponseTypeDef,
-    CreateSchedulingPolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterJobDefinitionResponseTypeDef,
-    SubmitJobResponseTypeDef,
-    UpdateComputeEnvironmentResponseTypeDef,
-    UpdateJobQueueResponseTypeDef,
-    DescribeComputeEnvironmentsRequestDescribeComputeEnvironmentsPaginateTypeDef,
-    DescribeJobDefinitionsRequestDescribeJobDefinitionsPaginateTypeDef,
-    DescribeJobQueuesRequestDescribeJobQueuesPaginateTypeDef,
-    ListSchedulingPoliciesRequestListSchedulingPoliciesPaginateTypeDef,
     EFSVolumeConfigurationTypeDef,
     EksAttemptDetailTypeDef,
     EksContainerOverrideTypeDef,
     EksContainerDetailTypeDef,
     EksContainerTypeDef,
     EksVolumeTypeDef,
     RetryStrategyTypeDef,
@@ -485,43 +487,43 @@
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

### Comparing `types-aiobotocore-batch-2.5.0.post1/types_aiobotocore_batch.egg-info/SOURCES.txt` & `types-aiobotocore-batch-2.5.1/types_aiobotocore_batch.egg-info/SOURCES.txt`

 * *Files identical despite different names*

