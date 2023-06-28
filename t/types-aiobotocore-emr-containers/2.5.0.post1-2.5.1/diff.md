# Comparing `tmp/types-aiobotocore-emr-containers-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-emr-containers-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-emr-containers-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:36 2023, max compression
+gzip compressed data, was "types-aiobotocore-emr-containers-2.5.1.tar", last modified: Wed Jun 28 01:43:29 2023, max compression
```

## Comparing `types-aiobotocore-emr-containers-2.5.0.post1.tar` & `types-aiobotocore-emr-containers-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.779197 types-aiobotocore-emr-containers-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16544 2023-03-11 12:26:36.779197 types-aiobotocore-emr-containers-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14946 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:36.779197 types-aiobotocore-emr-containers-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.775197 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/
--rw-r--r--   0 runner    (1001) docker     (123)     1360 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1359 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19022 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18990 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9030 2023-03-11 12:14:21.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9028 2023-03-11 12:14:21.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6707 2023-03-11 12:14:21.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6700 2023-03-11 12:14:21.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    24286 2023-03-11 12:14:21.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24257 2023-03-11 12:14:21.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:20.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:36.779197 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16544 2023-03-11 12:26:36.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:36.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:36.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:36.000000 types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.150136 types-aiobotocore-emr-containers-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16733 2023-06-28 01:43:29.150136 types-aiobotocore-emr-containers-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15141 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:29.150136 types-aiobotocore-emr-containers-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.130136 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/
+-rw-r--r--   0 runner    (1001) docker     (123)     1360 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1359 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19976 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19943 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9274 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9272 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6608 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6601 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    26001 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25970 2023-06-28 01:30:56.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:55.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.150136 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16733 2023-06-28 01:43:28.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:28.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:28.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:28.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:28.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:28.000000 types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/LICENSE` & `types-aiobotocore-emr-containers-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/PKG-INFO` & `types-aiobotocore-emr-containers-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-emr-containers
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EMRContainers 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EMRContainers 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-emr-containers"></a>
 
 # types-aiobotocore-emr-containers
 
 [![PyPI - types-aiobotocore-emr-containers](https://img.shields.io/pypi/v/types-aiobotocore-emr-containers.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-containers)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-emr-containers.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-containers)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-emr-containers?color=blue)](https://pypistats.org/packages/types-aiobotocore-emr-containers)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EMRContainers 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
+[aiobotocore.EMRContainers 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
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
 [types-aiobotocore-emr-containers docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,57 +339,61 @@
 
 `types_aiobotocore_emr_containers.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_emr_containers.type_defs import (
     CancelJobRunRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobRunResponseTypeDef,
     CertificateTypeDef,
     CloudWatchMonitoringConfigurationTypeDef,
     ConfigurationTypeDef,
     EksInfoTypeDef,
+    ContainerLogRotationConfigurationTypeDef,
+    CreateJobTemplateResponseTypeDef,
+    CreateManagedEndpointResponseTypeDef,
+    CreateVirtualClusterResponseTypeDef,
+    CredentialsTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
+    DeleteJobTemplateResponseTypeDef,
     DeleteManagedEndpointRequestRequestTypeDef,
+    DeleteManagedEndpointResponseTypeDef,
     DeleteVirtualClusterRequestRequestTypeDef,
+    DeleteVirtualClusterResponseTypeDef,
     DescribeJobRunRequestRequestTypeDef,
     DescribeJobTemplateRequestRequestTypeDef,
     DescribeManagedEndpointRequestRequestTypeDef,
     DescribeVirtualClusterRequestRequestTypeDef,
+    GetManagedEndpointSessionCredentialsRequestRequestTypeDef,
     SparkSqlJobDriverTypeDef,
     SparkSubmitJobDriverTypeDef,
     RetryPolicyConfigurationTypeDef,
     RetryPolicyExecutionTypeDef,
     TemplateParameterConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobRunsRequestListJobRunsPaginateTypeDef,
     ListJobRunsRequestRequestTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
     ListManagedEndpointsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListVirtualClustersRequestListVirtualClustersPaginateTypeDef,
     ListVirtualClustersRequestRequestTypeDef,
     S3MonitoringConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ParametricCloudWatchMonitoringConfigurationTypeDef,
     ParametricS3MonitoringConfigurationTypeDef,
+    ResponseMetadataTypeDef,
+    StartJobRunResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CancelJobRunResponseTypeDef,
-    CreateJobTemplateResponseTypeDef,
-    CreateManagedEndpointResponseTypeDef,
-    CreateVirtualClusterResponseTypeDef,
-    DeleteJobTemplateResponseTypeDef,
-    DeleteManagedEndpointResponseTypeDef,
-    DeleteVirtualClusterResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartJobRunResponseTypeDef,
     ContainerInfoTypeDef,
+    GetManagedEndpointSessionCredentialsResponseTypeDef,
     JobDriverTypeDef,
-    ListJobRunsRequestListJobRunsPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-    ListVirtualClustersRequestListVirtualClustersPaginateTypeDef,
     MonitoringConfigurationTypeDef,
     ParametricMonitoringConfigurationTypeDef,
     ContainerProviderTypeDef,
     ConfigurationOverridesTypeDef,
     ParametricConfigurationOverridesTypeDef,
     CreateVirtualClusterRequestRequestTypeDef,
     VirtualClusterTypeDef,
@@ -418,43 +422,43 @@
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/README.md` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-emr-containers
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EMRContainers 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore emr-containers type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-emr-containers"></a>
 
 # types-aiobotocore-emr-containers
 
 [![PyPI - types-aiobotocore-emr-containers](https://img.shields.io/pypi/v/types-aiobotocore-emr-containers.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-containers)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-emr-containers.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-containers)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-emr-containers?color=blue)](https://pypistats.org/packages/types-aiobotocore-emr-containers)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EMRContainers 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
+[aiobotocore.EMRContainers 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
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
 [types-aiobotocore-emr-containers docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,57 +339,61 @@
 
 `types_aiobotocore_emr_containers.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_emr_containers.type_defs import (
     CancelJobRunRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobRunResponseTypeDef,
     CertificateTypeDef,
     CloudWatchMonitoringConfigurationTypeDef,
     ConfigurationTypeDef,
     EksInfoTypeDef,
+    ContainerLogRotationConfigurationTypeDef,
+    CreateJobTemplateResponseTypeDef,
+    CreateManagedEndpointResponseTypeDef,
+    CreateVirtualClusterResponseTypeDef,
+    CredentialsTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
+    DeleteJobTemplateResponseTypeDef,
     DeleteManagedEndpointRequestRequestTypeDef,
+    DeleteManagedEndpointResponseTypeDef,
     DeleteVirtualClusterRequestRequestTypeDef,
+    DeleteVirtualClusterResponseTypeDef,
     DescribeJobRunRequestRequestTypeDef,
     DescribeJobTemplateRequestRequestTypeDef,
     DescribeManagedEndpointRequestRequestTypeDef,
     DescribeVirtualClusterRequestRequestTypeDef,
+    GetManagedEndpointSessionCredentialsRequestRequestTypeDef,
     SparkSqlJobDriverTypeDef,
     SparkSubmitJobDriverTypeDef,
     RetryPolicyConfigurationTypeDef,
     RetryPolicyExecutionTypeDef,
     TemplateParameterConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobRunsRequestListJobRunsPaginateTypeDef,
     ListJobRunsRequestRequestTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
     ListManagedEndpointsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListVirtualClustersRequestListVirtualClustersPaginateTypeDef,
     ListVirtualClustersRequestRequestTypeDef,
     S3MonitoringConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ParametricCloudWatchMonitoringConfigurationTypeDef,
     ParametricS3MonitoringConfigurationTypeDef,
+    ResponseMetadataTypeDef,
+    StartJobRunResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CancelJobRunResponseTypeDef,
-    CreateJobTemplateResponseTypeDef,
-    CreateManagedEndpointResponseTypeDef,
-    CreateVirtualClusterResponseTypeDef,
-    DeleteJobTemplateResponseTypeDef,
-    DeleteManagedEndpointResponseTypeDef,
-    DeleteVirtualClusterResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartJobRunResponseTypeDef,
     ContainerInfoTypeDef,
+    GetManagedEndpointSessionCredentialsResponseTypeDef,
     JobDriverTypeDef,
-    ListJobRunsRequestListJobRunsPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-    ListVirtualClustersRequestListVirtualClustersPaginateTypeDef,
     MonitoringConfigurationTypeDef,
     ParametricMonitoringConfigurationTypeDef,
     ContainerProviderTypeDef,
     ConfigurationOverridesTypeDef,
     ParametricConfigurationOverridesTypeDef,
     CreateVirtualClusterRequestRequestTypeDef,
     VirtualClusterTypeDef,
@@ -385,43 +422,43 @@
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/setup.py` & `types-aiobotocore-emr-containers-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-emr-containers.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-emr-containers",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_emr_containers"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EMRContainers 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.EMRContainers 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/"
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/__init__.py` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/__init__.pyi` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/__main__.py` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EMRContainers 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EMRContainers 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers\nOther"
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/client.py` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -38,14 +38,15 @@
     DeleteJobTemplateResponseTypeDef,
     DeleteManagedEndpointResponseTypeDef,
     DeleteVirtualClusterResponseTypeDef,
     DescribeJobRunResponseTypeDef,
     DescribeJobTemplateResponseTypeDef,
     DescribeManagedEndpointResponseTypeDef,
     DescribeVirtualClusterResponseTypeDef,
+    GetManagedEndpointSessionCredentialsResponseTypeDef,
     JobDriverTypeDef,
     JobTemplateDataTypeDef,
     ListJobRunsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedEndpointsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListVirtualClustersResponseTypeDef,
@@ -54,33 +55,30 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("EMRContainersClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    RequestThrottledException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class EMRContainersClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/)
     """
 
     meta: ClientMeta
@@ -89,41 +87,37 @@
     def exceptions(self) -> Exceptions:
         """
         EMRContainersClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#can_paginate)
         """
-
     async def cancel_job_run(
         self, *, id: str, virtualClusterId: str
     ) -> CancelJobRunResponseTypeDef:
         """
         Cancels a job run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.cancel_job_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#cancel_job_run)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#close)
         """
-
     async def create_job_template(
         self,
         *,
         name: str,
         clientToken: str,
         jobTemplateData: JobTemplateDataTypeDef,
         tags: Mapping[str, str] = ...,
@@ -131,15 +125,14 @@
     ) -> CreateJobTemplateResponseTypeDef:
         """
         Creates a job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#create_job_template)
         """
-
     async def create_managed_endpoint(
         self,
         *,
         name: str,
         virtualClusterId: str,
         type: str,
         releaseLabel: str,
@@ -151,106 +144,113 @@
     ) -> CreateManagedEndpointResponseTypeDef:
         """
         Creates a managed endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_managed_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#create_managed_endpoint)
         """
-
     async def create_virtual_cluster(
         self,
         *,
         name: str,
         containerProvider: ContainerProviderTypeDef,
         clientToken: str,
         tags: Mapping[str, str] = ...
     ) -> CreateVirtualClusterResponseTypeDef:
         """
         Creates a virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_virtual_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#create_virtual_cluster)
         """
-
     async def delete_job_template(self, *, id: str) -> DeleteJobTemplateResponseTypeDef:
         """
         Deletes a job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#delete_job_template)
         """
-
     async def delete_managed_endpoint(
         self, *, id: str, virtualClusterId: str
     ) -> DeleteManagedEndpointResponseTypeDef:
         """
         Deletes a managed endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_managed_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#delete_managed_endpoint)
         """
-
     async def delete_virtual_cluster(self, *, id: str) -> DeleteVirtualClusterResponseTypeDef:
         """
         Deletes a virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_virtual_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#delete_virtual_cluster)
         """
-
     async def describe_job_run(
         self, *, id: str, virtualClusterId: str
     ) -> DescribeJobRunResponseTypeDef:
         """
         Displays detailed information about a job run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_job_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_job_run)
         """
-
     async def describe_job_template(self, *, id: str) -> DescribeJobTemplateResponseTypeDef:
         """
         Displays detailed information about a specified job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_job_template)
         """
-
     async def describe_managed_endpoint(
         self, *, id: str, virtualClusterId: str
     ) -> DescribeManagedEndpointResponseTypeDef:
         """
         Displays detailed information about a managed endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_managed_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_managed_endpoint)
         """
-
     async def describe_virtual_cluster(self, *, id: str) -> DescribeVirtualClusterResponseTypeDef:
         """
         Displays detailed information about a specified virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_virtual_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_virtual_cluster)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#generate_presigned_url)
         """
+    async def get_managed_endpoint_session_credentials(
+        self,
+        *,
+        endpointIdentifier: str,
+        virtualClusterIdentifier: str,
+        executionRoleArn: str,
+        credentialType: str,
+        durationInSeconds: int = ...,
+        logContext: str = ...,
+        clientToken: str = ...
+    ) -> GetManagedEndpointSessionCredentialsResponseTypeDef:
+        """
+        Generate a session token to connect to a managed endpoint.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_managed_endpoint_session_credentials)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_managed_endpoint_session_credentials)
+        """
     async def list_job_runs(
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         name: str = ...,
@@ -260,30 +260,28 @@
     ) -> ListJobRunsResponseTypeDef:
         """
         Lists job runs based on a set of parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_job_runs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_job_runs)
         """
-
     async def list_job_templates(
         self,
         *,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListJobTemplatesResponseTypeDef:
         """
         Lists job templates based on a set of parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_job_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_job_templates)
         """
-
     async def list_managed_endpoints(
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         types: Sequence[str] = ...,
@@ -293,25 +291,23 @@
     ) -> ListManagedEndpointsResponseTypeDef:
         """
         Lists managed endpoints based on a set of parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_managed_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_managed_endpoints)
         """
-
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags assigned to the resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_tags_for_resource)
         """
-
     async def list_virtual_clusters(
         self,
         *,
         containerProviderId: str = ...,
         containerProviderType: Literal["EKS"] = ...,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
@@ -321,15 +317,14 @@
     ) -> ListVirtualClustersResponseTypeDef:
         """
         Lists information about the specified virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_virtual_clusters)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_virtual_clusters)
         """
-
     async def start_job_run(
         self,
         *,
         virtualClusterId: str,
         clientToken: str,
         name: str = ...,
         executionRoleArn: str = ...,
@@ -343,69 +338,61 @@
     ) -> StartJobRunResponseTypeDef:
         """
         Starts a job run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.start_job_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#start_job_run)
         """
-
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Assigns tags to resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#tag_resource)
         """
-
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#untag_resource)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_job_runs"]) -> ListJobRunsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_job_templates"]
     ) -> ListJobTemplatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_managed_endpoints"]
     ) -> ListManagedEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_virtual_clusters"]
     ) -> ListVirtualClustersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "EMRContainersClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/)
         """
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/client.pyi` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,14 +38,15 @@
     DeleteJobTemplateResponseTypeDef,
     DeleteManagedEndpointResponseTypeDef,
     DeleteVirtualClusterResponseTypeDef,
     DescribeJobRunResponseTypeDef,
     DescribeJobTemplateResponseTypeDef,
     DescribeManagedEndpointResponseTypeDef,
     DescribeVirtualClusterResponseTypeDef,
+    GetManagedEndpointSessionCredentialsResponseTypeDef,
     JobDriverTypeDef,
     JobTemplateDataTypeDef,
     ListJobRunsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedEndpointsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListVirtualClustersResponseTypeDef,
@@ -54,29 +55,34 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("EMRContainersClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
+    RequestThrottledException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class EMRContainersClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/)
     """
 
     meta: ClientMeta
@@ -85,37 +91,41 @@
     def exceptions(self) -> Exceptions:
         """
         EMRContainersClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#can_paginate)
         """
+
     async def cancel_job_run(
         self, *, id: str, virtualClusterId: str
     ) -> CancelJobRunResponseTypeDef:
         """
         Cancels a job run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.cancel_job_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#cancel_job_run)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#close)
         """
+
     async def create_job_template(
         self,
         *,
         name: str,
         clientToken: str,
         jobTemplateData: JobTemplateDataTypeDef,
         tags: Mapping[str, str] = ...,
@@ -123,14 +133,15 @@
     ) -> CreateJobTemplateResponseTypeDef:
         """
         Creates a job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#create_job_template)
         """
+
     async def create_managed_endpoint(
         self,
         *,
         name: str,
         virtualClusterId: str,
         type: str,
         releaseLabel: str,
@@ -142,96 +153,124 @@
     ) -> CreateManagedEndpointResponseTypeDef:
         """
         Creates a managed endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_managed_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#create_managed_endpoint)
         """
+
     async def create_virtual_cluster(
         self,
         *,
         name: str,
         containerProvider: ContainerProviderTypeDef,
         clientToken: str,
         tags: Mapping[str, str] = ...
     ) -> CreateVirtualClusterResponseTypeDef:
         """
         Creates a virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.create_virtual_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#create_virtual_cluster)
         """
+
     async def delete_job_template(self, *, id: str) -> DeleteJobTemplateResponseTypeDef:
         """
         Deletes a job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#delete_job_template)
         """
+
     async def delete_managed_endpoint(
         self, *, id: str, virtualClusterId: str
     ) -> DeleteManagedEndpointResponseTypeDef:
         """
         Deletes a managed endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_managed_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#delete_managed_endpoint)
         """
+
     async def delete_virtual_cluster(self, *, id: str) -> DeleteVirtualClusterResponseTypeDef:
         """
         Deletes a virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.delete_virtual_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#delete_virtual_cluster)
         """
+
     async def describe_job_run(
         self, *, id: str, virtualClusterId: str
     ) -> DescribeJobRunResponseTypeDef:
         """
         Displays detailed information about a job run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_job_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_job_run)
         """
+
     async def describe_job_template(self, *, id: str) -> DescribeJobTemplateResponseTypeDef:
         """
         Displays detailed information about a specified job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_job_template)
         """
+
     async def describe_managed_endpoint(
         self, *, id: str, virtualClusterId: str
     ) -> DescribeManagedEndpointResponseTypeDef:
         """
         Displays detailed information about a managed endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_managed_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_managed_endpoint)
         """
+
     async def describe_virtual_cluster(self, *, id: str) -> DescribeVirtualClusterResponseTypeDef:
         """
         Displays detailed information about a specified virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.describe_virtual_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#describe_virtual_cluster)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#generate_presigned_url)
         """
+
+    async def get_managed_endpoint_session_credentials(
+        self,
+        *,
+        endpointIdentifier: str,
+        virtualClusterIdentifier: str,
+        executionRoleArn: str,
+        credentialType: str,
+        durationInSeconds: int = ...,
+        logContext: str = ...,
+        clientToken: str = ...
+    ) -> GetManagedEndpointSessionCredentialsResponseTypeDef:
+        """
+        Generate a session token to connect to a managed endpoint.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_managed_endpoint_session_credentials)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_managed_endpoint_session_credentials)
+        """
+
     async def list_job_runs(
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         name: str = ...,
@@ -241,28 +280,30 @@
     ) -> ListJobRunsResponseTypeDef:
         """
         Lists job runs based on a set of parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_job_runs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_job_runs)
         """
+
     async def list_job_templates(
         self,
         *,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> ListJobTemplatesResponseTypeDef:
         """
         Lists job templates based on a set of parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_job_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_job_templates)
         """
+
     async def list_managed_endpoints(
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         types: Sequence[str] = ...,
@@ -272,23 +313,25 @@
     ) -> ListManagedEndpointsResponseTypeDef:
         """
         Lists managed endpoints based on a set of parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_managed_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_managed_endpoints)
         """
+
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags assigned to the resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_tags_for_resource)
         """
+
     async def list_virtual_clusters(
         self,
         *,
         containerProviderId: str = ...,
         containerProviderType: Literal["EKS"] = ...,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
@@ -298,14 +341,15 @@
     ) -> ListVirtualClustersResponseTypeDef:
         """
         Lists information about the specified virtual cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.list_virtual_clusters)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#list_virtual_clusters)
         """
+
     async def start_job_run(
         self,
         *,
         virtualClusterId: str,
         clientToken: str,
         name: str = ...,
         executionRoleArn: str = ...,
@@ -319,61 +363,69 @@
     ) -> StartJobRunResponseTypeDef:
         """
         Starts a job run.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.start_job_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#start_job_run)
         """
+
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Assigns tags to resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#tag_resource)
         """
+
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#untag_resource)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_job_runs"]) -> ListJobRunsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_job_templates"]
     ) -> ListJobTemplatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_managed_endpoints"]
     ) -> ListManagedEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_virtual_clusters"]
     ) -> ListVirtualClustersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "EMRContainersClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/client/)
         """
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/literals.py` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ContainerProviderTypeType",
     "EndpointStateType",
     "FailureReasonType",
     "JobRunStateType",
     "ListJobRunsPaginatorName",
     "ListJobTemplatesPaginatorName",
@@ -34,15 +33,14 @@
     "EMRContainersServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ContainerProviderTypeType = Literal["EKS"]
 EndpointStateType = Literal[
     "ACTIVE", "CREATING", "TERMINATED", "TERMINATED_WITH_ERRORS", "TERMINATING"
 ]
 FailureReasonType = Literal[
     "CLUSTER_UNAVAILABLE", "INTERNAL_ERROR", "USER_ERROR", "VALIDATION_ERROR"
 ]
@@ -115,14 +113,15 @@
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
@@ -201,14 +200,15 @@
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
@@ -219,14 +219,15 @@
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
@@ -262,14 +263,15 @@
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
@@ -288,16 +290,19 @@
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
@@ -381,15 +386,17 @@
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
@@ -411,24 +418,26 @@
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_job_runs", "list_job_templates", "list_managed_endpoints", "list_virtual_clusters"
 ]
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/literals.pyi` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/literals.py`

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
     "ContainerProviderTypeType",
     "EndpointStateType",
     "FailureReasonType",
     "JobRunStateType",
     "ListJobRunsPaginatorName",
     "ListJobTemplatesPaginatorName",
@@ -33,14 +34,15 @@
     "EMRContainersServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ContainerProviderTypeType = Literal["EKS"]
 EndpointStateType = Literal[
     "ACTIVE", "CREATING", "TERMINATED", "TERMINATED_WITH_ERRORS", "TERMINATING"
 ]
 FailureReasonType = Literal[
     "CLUSTER_UNAVAILABLE", "INTERNAL_ERROR", "USER_ERROR", "VALIDATION_ERROR"
 ]
@@ -113,14 +115,15 @@
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
@@ -199,14 +202,15 @@
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
@@ -217,14 +221,15 @@
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
@@ -260,14 +265,15 @@
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
@@ -286,16 +292,19 @@
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
@@ -379,15 +388,17 @@
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
@@ -409,24 +420,26 @@
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_job_runs", "list_job_templates", "list_managed_endpoints", "list_virtual_clusters"
 ]
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/paginator.py` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,32 +24,28 @@
         list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
         list_managed_endpoints_paginator: ListManagedEndpointsPaginator = client.get_paginator("list_managed_endpoints")
         list_virtual_clusters_paginator: ListVirtualClustersPaginator = client.get_paginator("list_virtual_clusters")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EndpointStateType, JobRunStateType, VirtualClusterStateType
 from .type_defs import (
     ListJobRunsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedEndpointsResponseTypeDef,
     ListVirtualClustersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
@@ -80,15 +76,15 @@
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         name: str = ...,
         states: Sequence[JobRunStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListJobRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listjobrunspaginator)
         """
 
 
@@ -99,15 +95,15 @@
     """
 
     def paginate(
         self,
         *,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListJobTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listjobtemplatespaginator)
         """
 
 
@@ -121,15 +117,15 @@
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         types: Sequence[str] = ...,
         states: Sequence[EndpointStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListManagedEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listmanagedendpointspaginator)
         """
 
 
@@ -143,13 +139,13 @@
         self,
         *,
         containerProviderId: str = ...,
         containerProviderType: Literal["EKS"] = ...,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
         states: Sequence[VirtualClusterStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListVirtualClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listvirtualclusterspaginator)
         """
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/paginator.pyi` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,32 +24,28 @@
         list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
         list_managed_endpoints_paginator: ListManagedEndpointsPaginator = client.get_paginator("list_managed_endpoints")
         list_virtual_clusters_paginator: ListVirtualClustersPaginator = client.get_paginator("list_virtual_clusters")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EndpointStateType, JobRunStateType, VirtualClusterStateType
 from .type_defs import (
     ListJobRunsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedEndpointsResponseTypeDef,
     ListVirtualClustersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ListJobRunsPaginator",
@@ -76,15 +72,15 @@
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         name: str = ...,
         states: Sequence[JobRunStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListJobRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listjobrunspaginator)
         """
 
 class ListJobTemplatesPaginator(AioPaginator):
@@ -94,15 +90,15 @@
     """
 
     def paginate(
         self,
         *,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListJobTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listjobtemplatespaginator)
         """
 
 class ListManagedEndpointsPaginator(AioPaginator):
@@ -115,15 +111,15 @@
         self,
         *,
         virtualClusterId: str,
         createdBefore: Union[datetime, str] = ...,
         createdAfter: Union[datetime, str] = ...,
         types: Sequence[str] = ...,
         states: Sequence[EndpointStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListManagedEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listmanagedendpointspaginator)
         """
 
 class ListVirtualClustersPaginator(AioPaginator):
@@ -136,13 +132,13 @@
         self,
         *,
         containerProviderId: str = ...,
         containerProviderType: Literal["EKS"] = ...,
         createdAfter: Union[datetime, str] = ...,
         createdBefore: Union[datetime, str] = ...,
         states: Sequence[VirtualClusterStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVirtualClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers.Paginator.ListVirtualClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/paginators/#listvirtualclusterspaginator)
         """
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/type_defs.py` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -32,57 +32,61 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelJobRunRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobRunResponseTypeDef",
     "CertificateTypeDef",
     "CloudWatchMonitoringConfigurationTypeDef",
     "ConfigurationTypeDef",
     "EksInfoTypeDef",
+    "ContainerLogRotationConfigurationTypeDef",
+    "CreateJobTemplateResponseTypeDef",
+    "CreateManagedEndpointResponseTypeDef",
+    "CreateVirtualClusterResponseTypeDef",
+    "CredentialsTypeDef",
     "DeleteJobTemplateRequestRequestTypeDef",
+    "DeleteJobTemplateResponseTypeDef",
     "DeleteManagedEndpointRequestRequestTypeDef",
+    "DeleteManagedEndpointResponseTypeDef",
     "DeleteVirtualClusterRequestRequestTypeDef",
+    "DeleteVirtualClusterResponseTypeDef",
     "DescribeJobRunRequestRequestTypeDef",
     "DescribeJobTemplateRequestRequestTypeDef",
     "DescribeManagedEndpointRequestRequestTypeDef",
     "DescribeVirtualClusterRequestRequestTypeDef",
+    "GetManagedEndpointSessionCredentialsRequestRequestTypeDef",
     "SparkSqlJobDriverTypeDef",
     "SparkSubmitJobDriverTypeDef",
     "RetryPolicyConfigurationTypeDef",
     "RetryPolicyExecutionTypeDef",
     "TemplateParameterConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobRunsRequestListJobRunsPaginateTypeDef",
     "ListJobRunsRequestRequestTypeDef",
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
     "ListJobTemplatesRequestRequestTypeDef",
+    "ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
     "ListManagedEndpointsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
     "ListVirtualClustersRequestRequestTypeDef",
     "S3MonitoringConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "ParametricCloudWatchMonitoringConfigurationTypeDef",
     "ParametricS3MonitoringConfigurationTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartJobRunResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CancelJobRunResponseTypeDef",
-    "CreateJobTemplateResponseTypeDef",
-    "CreateManagedEndpointResponseTypeDef",
-    "CreateVirtualClusterResponseTypeDef",
-    "DeleteJobTemplateResponseTypeDef",
-    "DeleteManagedEndpointResponseTypeDef",
-    "DeleteVirtualClusterResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartJobRunResponseTypeDef",
     "ContainerInfoTypeDef",
+    "GetManagedEndpointSessionCredentialsResponseTypeDef",
     "JobDriverTypeDef",
-    "ListJobRunsRequestListJobRunsPaginateTypeDef",
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    "ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
-    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
     "MonitoringConfigurationTypeDef",
     "ParametricMonitoringConfigurationTypeDef",
     "ContainerProviderTypeDef",
     "ConfigurationOverridesTypeDef",
     "ParametricConfigurationOverridesTypeDef",
     "CreateVirtualClusterRequestRequestTypeDef",
     "VirtualClusterTypeDef",
@@ -107,22 +111,20 @@
     "CancelJobRunRequestRequestTypeDef",
     {
         "id": str,
         "virtualClusterId": str,
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
+        "id": str,
+        "virtualClusterId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateTypeDef = TypedDict(
     "CertificateTypeDef",
     {
         "certificateArn": str,
@@ -177,36 +179,109 @@
     "EksInfoTypeDef",
     {
         "namespace": str,
     },
     total=False,
 )
 
+ContainerLogRotationConfigurationTypeDef = TypedDict(
+    "ContainerLogRotationConfigurationTypeDef",
+    {
+        "rotationSize": str,
+        "maxFilesToKeep": int,
+    },
+)
+
+CreateJobTemplateResponseTypeDef = TypedDict(
+    "CreateJobTemplateResponseTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "arn": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateManagedEndpointResponseTypeDef = TypedDict(
+    "CreateManagedEndpointResponseTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "arn": str,
+        "virtualClusterId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVirtualClusterResponseTypeDef = TypedDict(
+    "CreateVirtualClusterResponseTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CredentialsTypeDef = TypedDict(
+    "CredentialsTypeDef",
+    {
+        "token": str,
+    },
+    total=False,
+)
+
 DeleteJobTemplateRequestRequestTypeDef = TypedDict(
     "DeleteJobTemplateRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteJobTemplateResponseTypeDef = TypedDict(
+    "DeleteJobTemplateResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteManagedEndpointRequestRequestTypeDef = TypedDict(
     "DeleteManagedEndpointRequestRequestTypeDef",
     {
         "id": str,
         "virtualClusterId": str,
     },
 )
 
+DeleteManagedEndpointResponseTypeDef = TypedDict(
+    "DeleteManagedEndpointResponseTypeDef",
+    {
+        "id": str,
+        "virtualClusterId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteVirtualClusterRequestRequestTypeDef = TypedDict(
     "DeleteVirtualClusterRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteVirtualClusterResponseTypeDef = TypedDict(
+    "DeleteVirtualClusterResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeJobRunRequestRequestTypeDef = TypedDict(
     "DescribeJobRunRequestRequestTypeDef",
     {
         "id": str,
         "virtualClusterId": str,
     },
 )
@@ -229,14 +304,41 @@
 DescribeVirtualClusterRequestRequestTypeDef = TypedDict(
     "DescribeVirtualClusterRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+_RequiredGetManagedEndpointSessionCredentialsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetManagedEndpointSessionCredentialsRequestRequestTypeDef",
+    {
+        "endpointIdentifier": str,
+        "virtualClusterIdentifier": str,
+        "executionRoleArn": str,
+        "credentialType": str,
+    },
+)
+_OptionalGetManagedEndpointSessionCredentialsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetManagedEndpointSessionCredentialsRequestRequestTypeDef",
+    {
+        "durationInSeconds": int,
+        "logContext": str,
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class GetManagedEndpointSessionCredentialsRequestRequestTypeDef(
+    _RequiredGetManagedEndpointSessionCredentialsRequestRequestTypeDef,
+    _OptionalGetManagedEndpointSessionCredentialsRequestRequestTypeDef,
+):
+    pass
+
+
 SparkSqlJobDriverTypeDef = TypedDict(
     "SparkSqlJobDriverTypeDef",
     {
         "entryPoint": str,
         "sparkSqlParameters": str,
     },
     total=False,
@@ -283,24 +385,40 @@
     {
         "type": TemplateParameterDataTypeType,
         "defaultValue": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "virtualClusterId": str,
+    },
+)
+_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
+    {
+        "createdBefore": Union[datetime, str],
+        "createdAfter": Union[datetime, str],
+        "name": str,
+        "states": Sequence[JobRunStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
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
         "virtualClusterId": str,
     },
 )
 _OptionalListJobRunsRequestRequestTypeDef = TypedDict(
@@ -319,25 +437,61 @@
 
 class ListJobRunsRequestRequestTypeDef(
     _RequiredListJobRunsRequestRequestTypeDef, _OptionalListJobRunsRequestRequestTypeDef
 ):
     pass
 
 
+ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
+    {
+        "createdAfter": Union[datetime, str],
+        "createdBefore": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListJobTemplatesRequestRequestTypeDef",
     {
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
+    "_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
+    {
+        "virtualClusterId": str,
+    },
+)
+_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
+    "_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
+    {
+        "createdBefore": Union[datetime, str],
+        "createdAfter": Union[datetime, str],
+        "types": Sequence[str],
+        "states": Sequence[EndpointStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef(
+    _RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
+    _OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListManagedEndpointsRequestRequestTypeDef = TypedDict(
     "_RequiredListManagedEndpointsRequestRequestTypeDef",
     {
         "virtualClusterId": str,
     },
 )
 _OptionalListManagedEndpointsRequestRequestTypeDef = TypedDict(
@@ -364,14 +518,35 @@
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
+ListVirtualClustersRequestListVirtualClustersPaginateTypeDef = TypedDict(
+    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
+    {
+        "containerProviderId": str,
+        "containerProviderType": Literal["EKS"],
+        "createdAfter": Union[datetime, str],
+        "createdBefore": Union[datetime, str],
+        "states": Sequence[VirtualClusterStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVirtualClustersRequestRequestTypeDef = TypedDict(
     "ListVirtualClustersRequestRequestTypeDef",
     {
         "containerProviderId": str,
         "containerProviderType": Literal["EKS"],
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
@@ -385,14 +560,24 @@
 S3MonitoringConfigurationTypeDef = TypedDict(
     "S3MonitoringConfigurationTypeDef",
     {
         "logUri": str,
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
 ParametricCloudWatchMonitoringConfigurationTypeDef = TypedDict(
     "ParametricCloudWatchMonitoringConfigurationTypeDef",
     {
         "logGroupName": str,
         "logStreamNamePrefix": str,
     },
     total=False,
@@ -402,213 +587,86 @@
     "ParametricS3MonitoringConfigurationTypeDef",
     {
         "logUri": str,
     },
     total=False,
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
-    },
-)
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-CancelJobRunResponseTypeDef = TypedDict(
-    "CancelJobRunResponseTypeDef",
-    {
-        "id": str,
-        "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobTemplateResponseTypeDef = TypedDict(
-    "CreateJobTemplateResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "id": str,
-        "name": str,
-        "arn": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-CreateManagedEndpointResponseTypeDef = TypedDict(
-    "CreateManagedEndpointResponseTypeDef",
+StartJobRunResponseTypeDef = TypedDict(
+    "StartJobRunResponseTypeDef",
     {
         "id": str,
         "name": str,
         "arn": str,
         "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVirtualClusterResponseTypeDef = TypedDict(
-    "CreateVirtualClusterResponseTypeDef",
-    {
-        "id": str,
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteJobTemplateResponseTypeDef = TypedDict(
-    "DeleteJobTemplateResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteManagedEndpointResponseTypeDef = TypedDict(
-    "DeleteManagedEndpointResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "id": str,
-        "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-DeleteVirtualClusterResponseTypeDef = TypedDict(
-    "DeleteVirtualClusterResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+ContainerInfoTypeDef = TypedDict(
+    "ContainerInfoTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "eksInfo": EksInfoTypeDef,
     },
+    total=False,
 )
 
-StartJobRunResponseTypeDef = TypedDict(
-    "StartJobRunResponseTypeDef",
+GetManagedEndpointSessionCredentialsResponseTypeDef = TypedDict(
+    "GetManagedEndpointSessionCredentialsResponseTypeDef",
     {
         "id": str,
-        "name": str,
-        "arn": str,
-        "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "credentials": CredentialsTypeDef,
+        "expiresAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ContainerInfoTypeDef = TypedDict(
-    "ContainerInfoTypeDef",
-    {
-        "eksInfo": EksInfoTypeDef,
-    },
-    total=False,
-)
-
 JobDriverTypeDef = TypedDict(
     "JobDriverTypeDef",
     {
         "sparkSubmitJobDriver": SparkSubmitJobDriverTypeDef,
         "sparkSqlJobDriver": SparkSqlJobDriverTypeDef,
     },
     total=False,
 )
 
-_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "virtualClusterId": str,
-    },
-)
-_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "createdBefore": Union[datetime, str],
-        "createdAfter": Union[datetime, str],
-        "name": str,
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
-ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    {
-        "createdAfter": Union[datetime, str],
-        "createdBefore": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
-    "_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
-    {
-        "virtualClusterId": str,
-    },
-)
-_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
-    "_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
-    {
-        "createdBefore": Union[datetime, str],
-        "createdAfter": Union[datetime, str],
-        "types": Sequence[str],
-        "states": Sequence[EndpointStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef(
-    _RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-    _OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-):
-    pass
-
-
-ListVirtualClustersRequestListVirtualClustersPaginateTypeDef = TypedDict(
-    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
-    {
-        "containerProviderId": str,
-        "containerProviderType": Literal["EKS"],
-        "createdAfter": Union[datetime, str],
-        "createdBefore": Union[datetime, str],
-        "states": Sequence[VirtualClusterStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 MonitoringConfigurationTypeDef = TypedDict(
     "MonitoringConfigurationTypeDef",
     {
         "persistentAppUI": PersistentAppUIType,
         "cloudWatchMonitoringConfiguration": CloudWatchMonitoringConfigurationTypeDef,
         "s3MonitoringConfiguration": S3MonitoringConfigurationTypeDef,
+        "containerLogRotationConfiguration": ContainerLogRotationConfigurationTypeDef,
     },
     total=False,
 )
 
 ParametricMonitoringConfigurationTypeDef = TypedDict(
     "ParametricMonitoringConfigurationTypeDef",
     {
@@ -829,58 +887,58 @@
     pass
 
 
 DescribeVirtualClusterResponseTypeDef = TypedDict(
     "DescribeVirtualClusterResponseTypeDef",
     {
         "virtualCluster": VirtualClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualClustersResponseTypeDef = TypedDict(
     "ListVirtualClustersResponseTypeDef",
     {
         "virtualClusters": List[VirtualClusterTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeManagedEndpointResponseTypeDef = TypedDict(
     "DescribeManagedEndpointResponseTypeDef",
     {
         "endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListManagedEndpointsResponseTypeDef = TypedDict(
     "ListManagedEndpointsResponseTypeDef",
     {
         "endpoints": List[EndpointTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeJobRunResponseTypeDef = TypedDict(
     "DescribeJobRunResponseTypeDef",
     {
         "jobRun": JobRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobRunsResponseTypeDef = TypedDict(
     "ListJobRunsResponseTypeDef",
     {
         "jobRuns": List[JobRunTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobTemplateRequestRequestTypeDef",
     {
         "name": str,
@@ -930,19 +988,19 @@
     pass
 
 
 DescribeJobTemplateResponseTypeDef = TypedDict(
     "DescribeJobTemplateResponseTypeDef",
     {
         "jobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobTemplatesResponseTypeDef = TypedDict(
     "ListJobTemplatesResponseTypeDef",
     {
         "templates": List[JobTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers/type_defs.pyi` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -31,57 +31,61 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelJobRunRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelJobRunResponseTypeDef",
     "CertificateTypeDef",
     "CloudWatchMonitoringConfigurationTypeDef",
     "ConfigurationTypeDef",
     "EksInfoTypeDef",
+    "ContainerLogRotationConfigurationTypeDef",
+    "CreateJobTemplateResponseTypeDef",
+    "CreateManagedEndpointResponseTypeDef",
+    "CreateVirtualClusterResponseTypeDef",
+    "CredentialsTypeDef",
     "DeleteJobTemplateRequestRequestTypeDef",
+    "DeleteJobTemplateResponseTypeDef",
     "DeleteManagedEndpointRequestRequestTypeDef",
+    "DeleteManagedEndpointResponseTypeDef",
     "DeleteVirtualClusterRequestRequestTypeDef",
+    "DeleteVirtualClusterResponseTypeDef",
     "DescribeJobRunRequestRequestTypeDef",
     "DescribeJobTemplateRequestRequestTypeDef",
     "DescribeManagedEndpointRequestRequestTypeDef",
     "DescribeVirtualClusterRequestRequestTypeDef",
+    "GetManagedEndpointSessionCredentialsRequestRequestTypeDef",
     "SparkSqlJobDriverTypeDef",
     "SparkSubmitJobDriverTypeDef",
     "RetryPolicyConfigurationTypeDef",
     "RetryPolicyExecutionTypeDef",
     "TemplateParameterConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobRunsRequestListJobRunsPaginateTypeDef",
     "ListJobRunsRequestRequestTypeDef",
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
     "ListJobTemplatesRequestRequestTypeDef",
+    "ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
     "ListManagedEndpointsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
     "ListVirtualClustersRequestRequestTypeDef",
     "S3MonitoringConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "ParametricCloudWatchMonitoringConfigurationTypeDef",
     "ParametricS3MonitoringConfigurationTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartJobRunResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CancelJobRunResponseTypeDef",
-    "CreateJobTemplateResponseTypeDef",
-    "CreateManagedEndpointResponseTypeDef",
-    "CreateVirtualClusterResponseTypeDef",
-    "DeleteJobTemplateResponseTypeDef",
-    "DeleteManagedEndpointResponseTypeDef",
-    "DeleteVirtualClusterResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartJobRunResponseTypeDef",
     "ContainerInfoTypeDef",
+    "GetManagedEndpointSessionCredentialsResponseTypeDef",
     "JobDriverTypeDef",
-    "ListJobRunsRequestListJobRunsPaginateTypeDef",
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    "ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
-    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
     "MonitoringConfigurationTypeDef",
     "ParametricMonitoringConfigurationTypeDef",
     "ContainerProviderTypeDef",
     "ConfigurationOverridesTypeDef",
     "ParametricConfigurationOverridesTypeDef",
     "CreateVirtualClusterRequestRequestTypeDef",
     "VirtualClusterTypeDef",
@@ -106,22 +110,20 @@
     "CancelJobRunRequestRequestTypeDef",
     {
         "id": str,
         "virtualClusterId": str,
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
+        "id": str,
+        "virtualClusterId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateTypeDef = TypedDict(
     "CertificateTypeDef",
     {
         "certificateArn": str,
@@ -172,36 +174,109 @@
     "EksInfoTypeDef",
     {
         "namespace": str,
     },
     total=False,
 )
 
+ContainerLogRotationConfigurationTypeDef = TypedDict(
+    "ContainerLogRotationConfigurationTypeDef",
+    {
+        "rotationSize": str,
+        "maxFilesToKeep": int,
+    },
+)
+
+CreateJobTemplateResponseTypeDef = TypedDict(
+    "CreateJobTemplateResponseTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "arn": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateManagedEndpointResponseTypeDef = TypedDict(
+    "CreateManagedEndpointResponseTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "arn": str,
+        "virtualClusterId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVirtualClusterResponseTypeDef = TypedDict(
+    "CreateVirtualClusterResponseTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CredentialsTypeDef = TypedDict(
+    "CredentialsTypeDef",
+    {
+        "token": str,
+    },
+    total=False,
+)
+
 DeleteJobTemplateRequestRequestTypeDef = TypedDict(
     "DeleteJobTemplateRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteJobTemplateResponseTypeDef = TypedDict(
+    "DeleteJobTemplateResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteManagedEndpointRequestRequestTypeDef = TypedDict(
     "DeleteManagedEndpointRequestRequestTypeDef",
     {
         "id": str,
         "virtualClusterId": str,
     },
 )
 
+DeleteManagedEndpointResponseTypeDef = TypedDict(
+    "DeleteManagedEndpointResponseTypeDef",
+    {
+        "id": str,
+        "virtualClusterId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteVirtualClusterRequestRequestTypeDef = TypedDict(
     "DeleteVirtualClusterRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteVirtualClusterResponseTypeDef = TypedDict(
+    "DeleteVirtualClusterResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeJobRunRequestRequestTypeDef = TypedDict(
     "DescribeJobRunRequestRequestTypeDef",
     {
         "id": str,
         "virtualClusterId": str,
     },
 )
@@ -224,14 +299,39 @@
 DescribeVirtualClusterRequestRequestTypeDef = TypedDict(
     "DescribeVirtualClusterRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+_RequiredGetManagedEndpointSessionCredentialsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetManagedEndpointSessionCredentialsRequestRequestTypeDef",
+    {
+        "endpointIdentifier": str,
+        "virtualClusterIdentifier": str,
+        "executionRoleArn": str,
+        "credentialType": str,
+    },
+)
+_OptionalGetManagedEndpointSessionCredentialsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetManagedEndpointSessionCredentialsRequestRequestTypeDef",
+    {
+        "durationInSeconds": int,
+        "logContext": str,
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class GetManagedEndpointSessionCredentialsRequestRequestTypeDef(
+    _RequiredGetManagedEndpointSessionCredentialsRequestRequestTypeDef,
+    _OptionalGetManagedEndpointSessionCredentialsRequestRequestTypeDef,
+):
+    pass
+
 SparkSqlJobDriverTypeDef = TypedDict(
     "SparkSqlJobDriverTypeDef",
     {
         "entryPoint": str,
         "sparkSqlParameters": str,
     },
     total=False,
@@ -276,24 +376,38 @@
     {
         "type": TemplateParameterDataTypeType,
         "defaultValue": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "virtualClusterId": str,
+    },
+)
+_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
+    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
+    {
+        "createdBefore": Union[datetime, str],
+        "createdAfter": Union[datetime, str],
+        "name": str,
+        "states": Sequence[JobRunStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListJobRunsRequestListJobRunsPaginateTypeDef(
+    _RequiredListJobRunsRequestListJobRunsPaginateTypeDef,
+    _OptionalListJobRunsRequestListJobRunsPaginateTypeDef,
+):
+    pass
+
 _RequiredListJobRunsRequestRequestTypeDef = TypedDict(
     "_RequiredListJobRunsRequestRequestTypeDef",
     {
         "virtualClusterId": str,
     },
 )
 _OptionalListJobRunsRequestRequestTypeDef = TypedDict(
@@ -310,25 +424,59 @@
 )
 
 class ListJobRunsRequestRequestTypeDef(
     _RequiredListJobRunsRequestRequestTypeDef, _OptionalListJobRunsRequestRequestTypeDef
 ):
     pass
 
+ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
+    {
+        "createdAfter": Union[datetime, str],
+        "createdBefore": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListJobTemplatesRequestRequestTypeDef",
     {
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
+    "_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
+    {
+        "virtualClusterId": str,
+    },
+)
+_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
+    "_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
+    {
+        "createdBefore": Union[datetime, str],
+        "createdAfter": Union[datetime, str],
+        "types": Sequence[str],
+        "states": Sequence[EndpointStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef(
+    _RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
+    _OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
+):
+    pass
+
 _RequiredListManagedEndpointsRequestRequestTypeDef = TypedDict(
     "_RequiredListManagedEndpointsRequestRequestTypeDef",
     {
         "virtualClusterId": str,
     },
 )
 _OptionalListManagedEndpointsRequestRequestTypeDef = TypedDict(
@@ -353,14 +501,35 @@
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
+ListVirtualClustersRequestListVirtualClustersPaginateTypeDef = TypedDict(
+    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
+    {
+        "containerProviderId": str,
+        "containerProviderType": Literal["EKS"],
+        "createdAfter": Union[datetime, str],
+        "createdBefore": Union[datetime, str],
+        "states": Sequence[VirtualClusterStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVirtualClustersRequestRequestTypeDef = TypedDict(
     "ListVirtualClustersRequestRequestTypeDef",
     {
         "containerProviderId": str,
         "containerProviderType": Literal["EKS"],
         "createdAfter": Union[datetime, str],
         "createdBefore": Union[datetime, str],
@@ -374,14 +543,24 @@
 S3MonitoringConfigurationTypeDef = TypedDict(
     "S3MonitoringConfigurationTypeDef",
     {
         "logUri": str,
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
 ParametricCloudWatchMonitoringConfigurationTypeDef = TypedDict(
     "ParametricCloudWatchMonitoringConfigurationTypeDef",
     {
         "logGroupName": str,
         "logStreamNamePrefix": str,
     },
     total=False,
@@ -391,209 +570,86 @@
     "ParametricS3MonitoringConfigurationTypeDef",
     {
         "logUri": str,
     },
     total=False,
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
-    },
-)
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-CancelJobRunResponseTypeDef = TypedDict(
-    "CancelJobRunResponseTypeDef",
-    {
-        "id": str,
-        "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobTemplateResponseTypeDef = TypedDict(
-    "CreateJobTemplateResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "id": str,
-        "name": str,
-        "arn": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-CreateManagedEndpointResponseTypeDef = TypedDict(
-    "CreateManagedEndpointResponseTypeDef",
+StartJobRunResponseTypeDef = TypedDict(
+    "StartJobRunResponseTypeDef",
     {
         "id": str,
         "name": str,
         "arn": str,
         "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVirtualClusterResponseTypeDef = TypedDict(
-    "CreateVirtualClusterResponseTypeDef",
-    {
-        "id": str,
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteJobTemplateResponseTypeDef = TypedDict(
-    "DeleteJobTemplateResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteManagedEndpointResponseTypeDef = TypedDict(
-    "DeleteManagedEndpointResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "id": str,
-        "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-DeleteVirtualClusterResponseTypeDef = TypedDict(
-    "DeleteVirtualClusterResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+ContainerInfoTypeDef = TypedDict(
+    "ContainerInfoTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "eksInfo": EksInfoTypeDef,
     },
+    total=False,
 )
 
-StartJobRunResponseTypeDef = TypedDict(
-    "StartJobRunResponseTypeDef",
+GetManagedEndpointSessionCredentialsResponseTypeDef = TypedDict(
+    "GetManagedEndpointSessionCredentialsResponseTypeDef",
     {
         "id": str,
-        "name": str,
-        "arn": str,
-        "virtualClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "credentials": CredentialsTypeDef,
+        "expiresAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ContainerInfoTypeDef = TypedDict(
-    "ContainerInfoTypeDef",
-    {
-        "eksInfo": EksInfoTypeDef,
-    },
-    total=False,
-)
-
 JobDriverTypeDef = TypedDict(
     "JobDriverTypeDef",
     {
         "sparkSubmitJobDriver": SparkSubmitJobDriverTypeDef,
         "sparkSqlJobDriver": SparkSqlJobDriverTypeDef,
     },
     total=False,
 )
 
-_RequiredListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_RequiredListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "virtualClusterId": str,
-    },
-)
-_OptionalListJobRunsRequestListJobRunsPaginateTypeDef = TypedDict(
-    "_OptionalListJobRunsRequestListJobRunsPaginateTypeDef",
-    {
-        "createdBefore": Union[datetime, str],
-        "createdAfter": Union[datetime, str],
-        "name": str,
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
-ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    {
-        "createdAfter": Union[datetime, str],
-        "createdBefore": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
-    "_RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
-    {
-        "virtualClusterId": str,
-    },
-)
-_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef = TypedDict(
-    "_OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef",
-    {
-        "createdBefore": Union[datetime, str],
-        "createdAfter": Union[datetime, str],
-        "types": Sequence[str],
-        "states": Sequence[EndpointStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef(
-    _RequiredListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-    _OptionalListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-):
-    pass
-
-ListVirtualClustersRequestListVirtualClustersPaginateTypeDef = TypedDict(
-    "ListVirtualClustersRequestListVirtualClustersPaginateTypeDef",
-    {
-        "containerProviderId": str,
-        "containerProviderType": Literal["EKS"],
-        "createdAfter": Union[datetime, str],
-        "createdBefore": Union[datetime, str],
-        "states": Sequence[VirtualClusterStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 MonitoringConfigurationTypeDef = TypedDict(
     "MonitoringConfigurationTypeDef",
     {
         "persistentAppUI": PersistentAppUIType,
         "cloudWatchMonitoringConfiguration": CloudWatchMonitoringConfigurationTypeDef,
         "s3MonitoringConfiguration": S3MonitoringConfigurationTypeDef,
+        "containerLogRotationConfiguration": ContainerLogRotationConfigurationTypeDef,
     },
     total=False,
 )
 
 ParametricMonitoringConfigurationTypeDef = TypedDict(
     "ParametricMonitoringConfigurationTypeDef",
     {
@@ -804,58 +860,58 @@
 class JobTemplateDataTypeDef(_RequiredJobTemplateDataTypeDef, _OptionalJobTemplateDataTypeDef):
     pass
 
 DescribeVirtualClusterResponseTypeDef = TypedDict(
     "DescribeVirtualClusterResponseTypeDef",
     {
         "virtualCluster": VirtualClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVirtualClustersResponseTypeDef = TypedDict(
     "ListVirtualClustersResponseTypeDef",
     {
         "virtualClusters": List[VirtualClusterTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeManagedEndpointResponseTypeDef = TypedDict(
     "DescribeManagedEndpointResponseTypeDef",
     {
         "endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListManagedEndpointsResponseTypeDef = TypedDict(
     "ListManagedEndpointsResponseTypeDef",
     {
         "endpoints": List[EndpointTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeJobRunResponseTypeDef = TypedDict(
     "DescribeJobRunResponseTypeDef",
     {
         "jobRun": JobRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobRunsResponseTypeDef = TypedDict(
     "ListJobRunsResponseTypeDef",
     {
         "jobRuns": List[JobRunTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobTemplateRequestRequestTypeDef",
     {
         "name": str,
@@ -901,19 +957,19 @@
 class JobTemplateTypeDef(_RequiredJobTemplateTypeDef, _OptionalJobTemplateTypeDef):
     pass
 
 DescribeJobTemplateResponseTypeDef = TypedDict(
     "DescribeJobTemplateResponseTypeDef",
     {
         "jobTemplate": JobTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobTemplatesResponseTypeDef = TypedDict(
     "ListJobTemplatesResponseTypeDef",
     {
         "templates": List[JobTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/PKG-INFO` & `types-aiobotocore-emr-containers-2.5.1/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-emr-containers
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EMRContainers 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore emr-containers type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-emr-containers"></a>
 
 # types-aiobotocore-emr-containers
 
 [![PyPI - types-aiobotocore-emr-containers](https://img.shields.io/pypi/v/types-aiobotocore-emr-containers.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-containers)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-emr-containers.svg?color=blue)](https://pypi.org/project/types-aiobotocore-emr-containers)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-emr-containers?color=blue)](https://pypistats.org/packages/types-aiobotocore-emr-containers)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EMRContainers 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
+[aiobotocore.EMRContainers 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/emr-containers.html#EMRContainers)
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
 [types-aiobotocore-emr-containers docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_emr_containers/).
 
 See how it helps to find and fix potential bugs:
 
@@ -339,57 +306,61 @@
 
 `types_aiobotocore_emr_containers.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_emr_containers.type_defs import (
     CancelJobRunRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelJobRunResponseTypeDef,
     CertificateTypeDef,
     CloudWatchMonitoringConfigurationTypeDef,
     ConfigurationTypeDef,
     EksInfoTypeDef,
+    ContainerLogRotationConfigurationTypeDef,
+    CreateJobTemplateResponseTypeDef,
+    CreateManagedEndpointResponseTypeDef,
+    CreateVirtualClusterResponseTypeDef,
+    CredentialsTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
+    DeleteJobTemplateResponseTypeDef,
     DeleteManagedEndpointRequestRequestTypeDef,
+    DeleteManagedEndpointResponseTypeDef,
     DeleteVirtualClusterRequestRequestTypeDef,
+    DeleteVirtualClusterResponseTypeDef,
     DescribeJobRunRequestRequestTypeDef,
     DescribeJobTemplateRequestRequestTypeDef,
     DescribeManagedEndpointRequestRequestTypeDef,
     DescribeVirtualClusterRequestRequestTypeDef,
+    GetManagedEndpointSessionCredentialsRequestRequestTypeDef,
     SparkSqlJobDriverTypeDef,
     SparkSubmitJobDriverTypeDef,
     RetryPolicyConfigurationTypeDef,
     RetryPolicyExecutionTypeDef,
     TemplateParameterConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobRunsRequestListJobRunsPaginateTypeDef,
     ListJobRunsRequestRequestTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
     ListManagedEndpointsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListVirtualClustersRequestListVirtualClustersPaginateTypeDef,
     ListVirtualClustersRequestRequestTypeDef,
     S3MonitoringConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ParametricCloudWatchMonitoringConfigurationTypeDef,
     ParametricS3MonitoringConfigurationTypeDef,
+    ResponseMetadataTypeDef,
+    StartJobRunResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CancelJobRunResponseTypeDef,
-    CreateJobTemplateResponseTypeDef,
-    CreateManagedEndpointResponseTypeDef,
-    CreateVirtualClusterResponseTypeDef,
-    DeleteJobTemplateResponseTypeDef,
-    DeleteManagedEndpointResponseTypeDef,
-    DeleteVirtualClusterResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartJobRunResponseTypeDef,
     ContainerInfoTypeDef,
+    GetManagedEndpointSessionCredentialsResponseTypeDef,
     JobDriverTypeDef,
-    ListJobRunsRequestListJobRunsPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListManagedEndpointsRequestListManagedEndpointsPaginateTypeDef,
-    ListVirtualClustersRequestListVirtualClustersPaginateTypeDef,
     MonitoringConfigurationTypeDef,
     ParametricMonitoringConfigurationTypeDef,
     ContainerProviderTypeDef,
     ConfigurationOverridesTypeDef,
     ParametricConfigurationOverridesTypeDef,
     CreateVirtualClusterRequestRequestTypeDef,
     VirtualClusterTypeDef,
@@ -418,43 +389,43 @@
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

### Comparing `types-aiobotocore-emr-containers-2.5.0.post1/types_aiobotocore_emr_containers.egg-info/SOURCES.txt` & `types-aiobotocore-emr-containers-2.5.1/types_aiobotocore_emr_containers.egg-info/SOURCES.txt`

 * *Files identical despite different names*

