# Comparing `tmp/types-aiobotocore-robomaker-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-robomaker-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-robomaker-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-robomaker-2.5.1.tar", last modified: Wed Jun 28 01:44:03 2023, max compression
```

## Comparing `types-aiobotocore-robomaker-2.5.0.post1.tar` & `types-aiobotocore-robomaker-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.287558 types-aiobotocore-robomaker-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22180 2023-03-11 12:27:13.287558 types-aiobotocore-robomaker-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20601 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.287558 types-aiobotocore-robomaker-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.287558 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/
--rw-r--r--   0 runner    (1001) docker     (123)     2867 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2866 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    44856 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    44779 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13637 2023-03-11 12:22:31.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13635 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14125 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    14111 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    63519 2023-03-11 12:22:32.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    63464 2023-03-11 12:22:31.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:30.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.287558 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22180 2023-03-11 12:27:13.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:27:13.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:27:13.000000 types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.894201 types-aiobotocore-robomaker-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22174 2023-06-28 01:44:03.894201 types-aiobotocore-robomaker-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20601 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.894201 types-aiobotocore-robomaker-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.886201 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/
+-rw-r--r--   0 runner    (1001) docker     (123)     2867 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2866 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44856 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44779 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13846 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13844 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14027 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14014 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    63629 2023-06-28 01:39:20.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    63574 2023-06-28 01:39:19.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:18.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.894201 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22174 2023-06-28 01:44:03.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:44:03.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:03.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:44:03.000000 types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/LICENSE` & `types-aiobotocore-robomaker-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/PKG-INFO` & `types-aiobotocore-robomaker-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-robomaker
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RoboMaker 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RoboMaker 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-robomaker"></a>
 
 # types-aiobotocore-robomaker
 
 [![PyPI - types-aiobotocore-robomaker](https://img.shields.io/pypi/v/types-aiobotocore-robomaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-robomaker)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-robomaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-robomaker)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-robomaker?color=blue)](https://pypistats.org/packages/types-aiobotocore-robomaker)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RoboMaker 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker)
+[aiobotocore.RoboMaker 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker)
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
 [types-aiobotocore-robomaker docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/).
 
 See how it helps to find and fix potential bugs:
 
@@ -385,95 +385,96 @@
 
 `types_aiobotocore_robomaker.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_robomaker.type_defs import (
     BatchDeleteWorldsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BatchDeleteWorldsResponseTypeDef,
     BatchDescribeSimulationJobRequestRequestTypeDef,
     BatchPolicyTypeDef,
     CancelDeploymentJobRequestRequestTypeDef,
     CancelSimulationJobBatchRequestRequestTypeDef,
     CancelSimulationJobRequestRequestTypeDef,
     CancelWorldExportJobRequestRequestTypeDef,
     CancelWorldGenerationJobRequestRequestTypeDef,
     ComputeResponseTypeDef,
     ComputeTypeDef,
     CreateFleetRequestRequestTypeDef,
+    CreateFleetResponseTypeDef,
     EnvironmentTypeDef,
     RobotSoftwareSuiteTypeDef,
     SourceConfigTypeDef,
     SourceTypeDef,
     CreateRobotApplicationVersionRequestRequestTypeDef,
     CreateRobotRequestRequestTypeDef,
+    CreateRobotResponseTypeDef,
     RenderingEngineTypeDef,
     SimulationSoftwareSuiteTypeDef,
     CreateSimulationApplicationVersionRequestRequestTypeDef,
     DataSourceConfigTypeDef,
     LoggingConfigTypeDef,
     OutputLocationTypeDef,
     VPCConfigTypeDef,
     VPCConfigResponseTypeDef,
     WorldCountTypeDef,
     TemplateLocationTypeDef,
+    CreateWorldTemplateResponseTypeDef,
     S3KeyOutputTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DeleteRobotApplicationRequestRequestTypeDef,
     DeleteRobotRequestRequestTypeDef,
     DeleteSimulationApplicationRequestRequestTypeDef,
     DeleteWorldTemplateRequestRequestTypeDef,
     DeploymentLaunchConfigTypeDef,
     S3ObjectTypeDef,
     DeregisterRobotRequestRequestTypeDef,
+    DeregisterRobotResponseTypeDef,
     DescribeDeploymentJobRequestRequestTypeDef,
     DescribeFleetRequestRequestTypeDef,
     RobotTypeDef,
     DescribeRobotApplicationRequestRequestTypeDef,
     DescribeRobotRequestRequestTypeDef,
+    DescribeRobotResponseTypeDef,
     DescribeSimulationApplicationRequestRequestTypeDef,
     DescribeSimulationJobBatchRequestRequestTypeDef,
     SimulationJobSummaryTypeDef,
     DescribeSimulationJobRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
     DescribeWorldExportJobRequestRequestTypeDef,
     DescribeWorldGenerationJobRequestRequestTypeDef,
     DescribeWorldRequestRequestTypeDef,
+    DescribeWorldResponseTypeDef,
     DescribeWorldTemplateRequestRequestTypeDef,
+    DescribeWorldTemplateResponseTypeDef,
     WorldFailureTypeDef,
     FilterTypeDef,
     FleetTypeDef,
     GetWorldTemplateBodyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorldTemplateBodyResponseTypeDef,
     SimulationJobBatchSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef,
     ListWorldTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
     WorldSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PortMappingTypeDef,
     ProgressDetailTypeDef,
     RegisterRobotRequestRequestTypeDef,
+    RegisterRobotResponseTypeDef,
+    ResponseMetadataTypeDef,
     RestartSimulationJobRequestRequestTypeDef,
     ToolTypeDef,
     UploadConfigurationTypeDef,
     WorldConfigTypeDef,
     SyncDeploymentJobRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    BatchDeleteWorldsResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    CreateRobotResponseTypeDef,
-    CreateWorldTemplateResponseTypeDef,
-    DeregisterRobotResponseTypeDef,
-    DescribeRobotResponseTypeDef,
-    DescribeWorldResponseTypeDef,
-    DescribeWorldTemplateResponseTypeDef,
-    GetWorldTemplateBodyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterRobotResponseTypeDef,
     UpdateWorldTemplateResponseTypeDef,
     RobotApplicationSummaryTypeDef,
     CreateRobotApplicationRequestRequestTypeDef,
     UpdateRobotApplicationRequestRequestTypeDef,
     CreateRobotApplicationResponseTypeDef,
     CreateRobotApplicationVersionResponseTypeDef,
     DescribeRobotApplicationResponseTypeDef,
@@ -497,36 +498,35 @@
     DataSourceTypeDef,
     DeploymentApplicationConfigTypeDef,
     DeploymentConfigTypeDef,
     DescribeFleetResponseTypeDef,
     ListRobotsResponseTypeDef,
     ListSimulationJobsResponseTypeDef,
     FailureSummaryTypeDef,
+    ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef,
     ListDeploymentJobsRequestRequestTypeDef,
+    ListFleetsRequestListFleetsPaginateTypeDef,
     ListFleetsRequestRequestTypeDef,
+    ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef,
     ListRobotApplicationsRequestRequestTypeDef,
+    ListRobotsRequestListRobotsPaginateTypeDef,
     ListRobotsRequestRequestTypeDef,
+    ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef,
     ListSimulationApplicationsRequestRequestTypeDef,
+    ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef,
     ListSimulationJobBatchesRequestRequestTypeDef,
+    ListSimulationJobsRequestListSimulationJobsPaginateTypeDef,
     ListSimulationJobsRequestRequestTypeDef,
+    ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef,
     ListWorldExportJobsRequestRequestTypeDef,
+    ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef,
     ListWorldGenerationJobsRequestRequestTypeDef,
+    ListWorldsRequestListWorldsPaginateTypeDef,
     ListWorldsRequestRequestTypeDef,
     ListFleetsResponseTypeDef,
-    ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef,
-    ListFleetsRequestListFleetsPaginateTypeDef,
-    ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef,
-    ListRobotsRequestListRobotsPaginateTypeDef,
-    ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef,
-    ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef,
-    ListSimulationJobsRequestListSimulationJobsPaginateTypeDef,
-    ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef,
-    ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef,
-    ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef,
-    ListWorldsRequestListWorldsPaginateTypeDef,
     ListSimulationJobBatchesResponseTypeDef,
     ListWorldTemplatesResponseTypeDef,
     ListWorldsResponseTypeDef,
     PortForwardingConfigTypeDef,
     RobotDeploymentTypeDef,
     ListRobotApplicationsResponseTypeDef,
     ListSimulationApplicationsResponseTypeDef,
@@ -563,43 +563,43 @@
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/README.md` & `types-aiobotocore-robomaker-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-robomaker"></a>
 
 # types-aiobotocore-robomaker
 
 [![PyPI - types-aiobotocore-robomaker](https://img.shields.io/pypi/v/types-aiobotocore-robomaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-robomaker)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-robomaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-robomaker)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-robomaker?color=blue)](https://pypistats.org/packages/types-aiobotocore-robomaker)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RoboMaker 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker)
+[aiobotocore.RoboMaker 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker)
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
 [types-aiobotocore-robomaker docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/).
 
 See how it helps to find and fix potential bugs:
 
@@ -352,95 +352,96 @@
 
 `types_aiobotocore_robomaker.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_robomaker.type_defs import (
     BatchDeleteWorldsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BatchDeleteWorldsResponseTypeDef,
     BatchDescribeSimulationJobRequestRequestTypeDef,
     BatchPolicyTypeDef,
     CancelDeploymentJobRequestRequestTypeDef,
     CancelSimulationJobBatchRequestRequestTypeDef,
     CancelSimulationJobRequestRequestTypeDef,
     CancelWorldExportJobRequestRequestTypeDef,
     CancelWorldGenerationJobRequestRequestTypeDef,
     ComputeResponseTypeDef,
     ComputeTypeDef,
     CreateFleetRequestRequestTypeDef,
+    CreateFleetResponseTypeDef,
     EnvironmentTypeDef,
     RobotSoftwareSuiteTypeDef,
     SourceConfigTypeDef,
     SourceTypeDef,
     CreateRobotApplicationVersionRequestRequestTypeDef,
     CreateRobotRequestRequestTypeDef,
+    CreateRobotResponseTypeDef,
     RenderingEngineTypeDef,
     SimulationSoftwareSuiteTypeDef,
     CreateSimulationApplicationVersionRequestRequestTypeDef,
     DataSourceConfigTypeDef,
     LoggingConfigTypeDef,
     OutputLocationTypeDef,
     VPCConfigTypeDef,
     VPCConfigResponseTypeDef,
     WorldCountTypeDef,
     TemplateLocationTypeDef,
+    CreateWorldTemplateResponseTypeDef,
     S3KeyOutputTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DeleteRobotApplicationRequestRequestTypeDef,
     DeleteRobotRequestRequestTypeDef,
     DeleteSimulationApplicationRequestRequestTypeDef,
     DeleteWorldTemplateRequestRequestTypeDef,
     DeploymentLaunchConfigTypeDef,
     S3ObjectTypeDef,
     DeregisterRobotRequestRequestTypeDef,
+    DeregisterRobotResponseTypeDef,
     DescribeDeploymentJobRequestRequestTypeDef,
     DescribeFleetRequestRequestTypeDef,
     RobotTypeDef,
     DescribeRobotApplicationRequestRequestTypeDef,
     DescribeRobotRequestRequestTypeDef,
+    DescribeRobotResponseTypeDef,
     DescribeSimulationApplicationRequestRequestTypeDef,
     DescribeSimulationJobBatchRequestRequestTypeDef,
     SimulationJobSummaryTypeDef,
     DescribeSimulationJobRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
     DescribeWorldExportJobRequestRequestTypeDef,
     DescribeWorldGenerationJobRequestRequestTypeDef,
     DescribeWorldRequestRequestTypeDef,
+    DescribeWorldResponseTypeDef,
     DescribeWorldTemplateRequestRequestTypeDef,
+    DescribeWorldTemplateResponseTypeDef,
     WorldFailureTypeDef,
     FilterTypeDef,
     FleetTypeDef,
     GetWorldTemplateBodyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorldTemplateBodyResponseTypeDef,
     SimulationJobBatchSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef,
     ListWorldTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
     WorldSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PortMappingTypeDef,
     ProgressDetailTypeDef,
     RegisterRobotRequestRequestTypeDef,
+    RegisterRobotResponseTypeDef,
+    ResponseMetadataTypeDef,
     RestartSimulationJobRequestRequestTypeDef,
     ToolTypeDef,
     UploadConfigurationTypeDef,
     WorldConfigTypeDef,
     SyncDeploymentJobRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    BatchDeleteWorldsResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    CreateRobotResponseTypeDef,
-    CreateWorldTemplateResponseTypeDef,
-    DeregisterRobotResponseTypeDef,
-    DescribeRobotResponseTypeDef,
-    DescribeWorldResponseTypeDef,
-    DescribeWorldTemplateResponseTypeDef,
-    GetWorldTemplateBodyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterRobotResponseTypeDef,
     UpdateWorldTemplateResponseTypeDef,
     RobotApplicationSummaryTypeDef,
     CreateRobotApplicationRequestRequestTypeDef,
     UpdateRobotApplicationRequestRequestTypeDef,
     CreateRobotApplicationResponseTypeDef,
     CreateRobotApplicationVersionResponseTypeDef,
     DescribeRobotApplicationResponseTypeDef,
@@ -464,36 +465,35 @@
     DataSourceTypeDef,
     DeploymentApplicationConfigTypeDef,
     DeploymentConfigTypeDef,
     DescribeFleetResponseTypeDef,
     ListRobotsResponseTypeDef,
     ListSimulationJobsResponseTypeDef,
     FailureSummaryTypeDef,
+    ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef,
     ListDeploymentJobsRequestRequestTypeDef,
+    ListFleetsRequestListFleetsPaginateTypeDef,
     ListFleetsRequestRequestTypeDef,
+    ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef,
     ListRobotApplicationsRequestRequestTypeDef,
+    ListRobotsRequestListRobotsPaginateTypeDef,
     ListRobotsRequestRequestTypeDef,
+    ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef,
     ListSimulationApplicationsRequestRequestTypeDef,
+    ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef,
     ListSimulationJobBatchesRequestRequestTypeDef,
+    ListSimulationJobsRequestListSimulationJobsPaginateTypeDef,
     ListSimulationJobsRequestRequestTypeDef,
+    ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef,
     ListWorldExportJobsRequestRequestTypeDef,
+    ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef,
     ListWorldGenerationJobsRequestRequestTypeDef,
+    ListWorldsRequestListWorldsPaginateTypeDef,
     ListWorldsRequestRequestTypeDef,
     ListFleetsResponseTypeDef,
-    ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef,
-    ListFleetsRequestListFleetsPaginateTypeDef,
-    ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef,
-    ListRobotsRequestListRobotsPaginateTypeDef,
-    ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef,
-    ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef,
-    ListSimulationJobsRequestListSimulationJobsPaginateTypeDef,
-    ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef,
-    ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef,
-    ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef,
-    ListWorldsRequestListWorldsPaginateTypeDef,
     ListSimulationJobBatchesResponseTypeDef,
     ListWorldTemplatesResponseTypeDef,
     ListWorldsResponseTypeDef,
     PortForwardingConfigTypeDef,
     RobotDeploymentTypeDef,
     ListRobotApplicationsResponseTypeDef,
     ListSimulationApplicationsResponseTypeDef,
@@ -530,43 +530,43 @@
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/setup.py` & `types-aiobotocore-robomaker-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-robomaker.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-robomaker",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_robomaker"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RoboMaker 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.RoboMaker 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/"
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/__init__.py` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/__init__.pyi` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/__main__.py` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RoboMaker 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RoboMaker 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker\nOther"
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/client.py` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/client.pyi` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/literals.py` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -261,14 +261,15 @@
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
@@ -347,14 +348,15 @@
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
@@ -365,14 +367,15 @@
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
@@ -408,14 +411,15 @@
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
@@ -434,16 +438,19 @@
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
@@ -527,15 +534,17 @@
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/literals.pyi` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -259,14 +259,15 @@
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
@@ -345,14 +346,15 @@
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
@@ -363,14 +365,15 @@
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
@@ -406,14 +409,15 @@
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
@@ -432,16 +436,19 @@
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
@@ -525,15 +532,17 @@
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/paginator.py` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -36,16 +36,15 @@
         list_simulation_jobs_paginator: ListSimulationJobsPaginator = client.get_paginator("list_simulation_jobs")
         list_world_export_jobs_paginator: ListWorldExportJobsPaginator = client.get_paginator("list_world_export_jobs")
         list_world_generation_jobs_paginator: ListWorldGenerationJobsPaginator = client.get_paginator("list_world_generation_jobs")
         list_world_templates_paginator: ListWorldTemplatesPaginator = client.get_paginator("list_world_templates")
         list_worlds_paginator: ListWorldsPaginator = client.get_paginator("list_worlds")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListDeploymentJobsResponseTypeDef,
@@ -58,233 +57,214 @@
     ListWorldExportJobsResponseTypeDef,
     ListWorldGenerationJobsResponseTypeDef,
     ListWorldsResponseTypeDef,
     ListWorldTemplatesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDeploymentJobsPaginator",
     "ListFleetsPaginator",
     "ListRobotApplicationsPaginator",
     "ListRobotsPaginator",
     "ListSimulationApplicationsPaginator",
     "ListSimulationJobBatchesPaginator",
     "ListSimulationJobsPaginator",
     "ListWorldExportJobsPaginator",
     "ListWorldGenerationJobsPaginator",
     "ListWorldTemplatesPaginator",
     "ListWorldsPaginator",
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
 class ListDeploymentJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListDeploymentJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listdeploymentjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListDeploymentJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listdeploymentjobspaginator)
         """
 
-
 class ListFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listfleetspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listfleetspaginator)
         """
 
-
 class ListRobotApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobotApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         versionQualifier: str = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRobotApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobotApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotapplicationspaginator)
         """
 
-
 class ListRobotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRobotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotspaginator)
         """
 
-
 class ListSimulationApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         versionQualifier: str = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSimulationApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationapplicationspaginator)
         """
 
-
 class ListSimulationJobBatchesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobBatches)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobbatchespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSimulationJobBatchesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobBatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobbatchespaginator)
         """
 
-
 class ListSimulationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSimulationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobspaginator)
         """
 
-
 class ListWorldExportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldExportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldexportjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldExportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldExportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldexportjobspaginator)
         """
 
-
 class ListWorldGenerationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldGenerationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldgenerationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldGenerationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldGenerationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldgenerationjobspaginator)
         """
 
-
 class ListWorldTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldtemplatespaginator)
         """
 
-
 class ListWorldsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorlds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorlds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldspaginator)
         """
```

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/paginator.pyi` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -36,16 +36,15 @@
         list_simulation_jobs_paginator: ListSimulationJobsPaginator = client.get_paginator("list_simulation_jobs")
         list_world_export_jobs_paginator: ListWorldExportJobsPaginator = client.get_paginator("list_world_export_jobs")
         list_world_generation_jobs_paginator: ListWorldGenerationJobsPaginator = client.get_paginator("list_world_generation_jobs")
         list_world_templates_paginator: ListWorldTemplatesPaginator = client.get_paginator("list_world_templates")
         list_worlds_paginator: ListWorldsPaginator = client.get_paginator("list_worlds")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListDeploymentJobsResponseTypeDef,
@@ -58,219 +57,227 @@
     ListWorldExportJobsResponseTypeDef,
     ListWorldGenerationJobsResponseTypeDef,
     ListWorldsResponseTypeDef,
     ListWorldTemplatesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDeploymentJobsPaginator",
     "ListFleetsPaginator",
     "ListRobotApplicationsPaginator",
     "ListRobotsPaginator",
     "ListSimulationApplicationsPaginator",
     "ListSimulationJobBatchesPaginator",
     "ListSimulationJobsPaginator",
     "ListWorldExportJobsPaginator",
     "ListWorldGenerationJobsPaginator",
     "ListWorldTemplatesPaginator",
     "ListWorldsPaginator",
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
 class ListDeploymentJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListDeploymentJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listdeploymentjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListDeploymentJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listdeploymentjobspaginator)
         """
 
+
 class ListFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listfleetspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listfleetspaginator)
         """
 
+
 class ListRobotApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobotApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         versionQualifier: str = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRobotApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobotApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotapplicationspaginator)
         """
 
+
 class ListRobotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRobotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListRobots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listrobotspaginator)
         """
 
+
 class ListSimulationApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         versionQualifier: str = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSimulationApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationapplicationspaginator)
         """
 
+
 class ListSimulationJobBatchesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobBatches)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobbatchespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSimulationJobBatchesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobBatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobbatchespaginator)
         """
 
+
 class ListSimulationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSimulationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListSimulationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listsimulationjobspaginator)
         """
 
+
 class ListWorldExportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldExportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldexportjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldExportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldExportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldexportjobspaginator)
         """
 
+
 class ListWorldGenerationJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldGenerationJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldgenerationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldGenerationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldGenerationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldgenerationjobspaginator)
         """
 
+
 class ListWorldTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorldTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldtemplatespaginator)
         """
 
+
 class ListWorldsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorlds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorldsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker.Paginator.ListWorlds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/paginators/#listworldspaginator)
         """
```

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/type_defs.py` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -46,95 +46,96 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BatchDeleteWorldsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BatchDeleteWorldsResponseTypeDef",
     "BatchDescribeSimulationJobRequestRequestTypeDef",
     "BatchPolicyTypeDef",
     "CancelDeploymentJobRequestRequestTypeDef",
     "CancelSimulationJobBatchRequestRequestTypeDef",
     "CancelSimulationJobRequestRequestTypeDef",
     "CancelWorldExportJobRequestRequestTypeDef",
     "CancelWorldGenerationJobRequestRequestTypeDef",
     "ComputeResponseTypeDef",
     "ComputeTypeDef",
     "CreateFleetRequestRequestTypeDef",
+    "CreateFleetResponseTypeDef",
     "EnvironmentTypeDef",
     "RobotSoftwareSuiteTypeDef",
     "SourceConfigTypeDef",
     "SourceTypeDef",
     "CreateRobotApplicationVersionRequestRequestTypeDef",
     "CreateRobotRequestRequestTypeDef",
+    "CreateRobotResponseTypeDef",
     "RenderingEngineTypeDef",
     "SimulationSoftwareSuiteTypeDef",
     "CreateSimulationApplicationVersionRequestRequestTypeDef",
     "DataSourceConfigTypeDef",
     "LoggingConfigTypeDef",
     "OutputLocationTypeDef",
     "VPCConfigTypeDef",
     "VPCConfigResponseTypeDef",
     "WorldCountTypeDef",
     "TemplateLocationTypeDef",
+    "CreateWorldTemplateResponseTypeDef",
     "S3KeyOutputTypeDef",
     "DeleteFleetRequestRequestTypeDef",
     "DeleteRobotApplicationRequestRequestTypeDef",
     "DeleteRobotRequestRequestTypeDef",
     "DeleteSimulationApplicationRequestRequestTypeDef",
     "DeleteWorldTemplateRequestRequestTypeDef",
     "DeploymentLaunchConfigTypeDef",
     "S3ObjectTypeDef",
     "DeregisterRobotRequestRequestTypeDef",
+    "DeregisterRobotResponseTypeDef",
     "DescribeDeploymentJobRequestRequestTypeDef",
     "DescribeFleetRequestRequestTypeDef",
     "RobotTypeDef",
     "DescribeRobotApplicationRequestRequestTypeDef",
     "DescribeRobotRequestRequestTypeDef",
+    "DescribeRobotResponseTypeDef",
     "DescribeSimulationApplicationRequestRequestTypeDef",
     "DescribeSimulationJobBatchRequestRequestTypeDef",
     "SimulationJobSummaryTypeDef",
     "DescribeSimulationJobRequestRequestTypeDef",
     "NetworkInterfaceTypeDef",
     "DescribeWorldExportJobRequestRequestTypeDef",
     "DescribeWorldGenerationJobRequestRequestTypeDef",
     "DescribeWorldRequestRequestTypeDef",
+    "DescribeWorldResponseTypeDef",
     "DescribeWorldTemplateRequestRequestTypeDef",
+    "DescribeWorldTemplateResponseTypeDef",
     "WorldFailureTypeDef",
     "FilterTypeDef",
     "FleetTypeDef",
     "GetWorldTemplateBodyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetWorldTemplateBodyResponseTypeDef",
     "SimulationJobBatchSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
     "ListWorldTemplatesRequestRequestTypeDef",
     "TemplateSummaryTypeDef",
     "WorldSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "PortMappingTypeDef",
     "ProgressDetailTypeDef",
     "RegisterRobotRequestRequestTypeDef",
+    "RegisterRobotResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RestartSimulationJobRequestRequestTypeDef",
     "ToolTypeDef",
     "UploadConfigurationTypeDef",
     "WorldConfigTypeDef",
     "SyncDeploymentJobRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "BatchDeleteWorldsResponseTypeDef",
-    "CreateFleetResponseTypeDef",
-    "CreateRobotResponseTypeDef",
-    "CreateWorldTemplateResponseTypeDef",
-    "DeregisterRobotResponseTypeDef",
-    "DescribeRobotResponseTypeDef",
-    "DescribeWorldResponseTypeDef",
-    "DescribeWorldTemplateResponseTypeDef",
-    "GetWorldTemplateBodyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterRobotResponseTypeDef",
     "UpdateWorldTemplateResponseTypeDef",
     "RobotApplicationSummaryTypeDef",
     "CreateRobotApplicationRequestRequestTypeDef",
     "UpdateRobotApplicationRequestRequestTypeDef",
     "CreateRobotApplicationResponseTypeDef",
     "CreateRobotApplicationVersionResponseTypeDef",
     "DescribeRobotApplicationResponseTypeDef",
@@ -158,36 +159,35 @@
     "DataSourceTypeDef",
     "DeploymentApplicationConfigTypeDef",
     "DeploymentConfigTypeDef",
     "DescribeFleetResponseTypeDef",
     "ListRobotsResponseTypeDef",
     "ListSimulationJobsResponseTypeDef",
     "FailureSummaryTypeDef",
+    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
     "ListDeploymentJobsRequestRequestTypeDef",
+    "ListFleetsRequestListFleetsPaginateTypeDef",
     "ListFleetsRequestRequestTypeDef",
+    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
     "ListRobotApplicationsRequestRequestTypeDef",
+    "ListRobotsRequestListRobotsPaginateTypeDef",
     "ListRobotsRequestRequestTypeDef",
+    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
     "ListSimulationApplicationsRequestRequestTypeDef",
+    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
     "ListSimulationJobBatchesRequestRequestTypeDef",
+    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
     "ListSimulationJobsRequestRequestTypeDef",
+    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
     "ListWorldExportJobsRequestRequestTypeDef",
+    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
     "ListWorldGenerationJobsRequestRequestTypeDef",
+    "ListWorldsRequestListWorldsPaginateTypeDef",
     "ListWorldsRequestRequestTypeDef",
     "ListFleetsResponseTypeDef",
-    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
-    "ListFleetsRequestListFleetsPaginateTypeDef",
-    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
-    "ListRobotsRequestListRobotsPaginateTypeDef",
-    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
-    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
-    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
-    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
-    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
-    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
-    "ListWorldsRequestListWorldsPaginateTypeDef",
     "ListSimulationJobBatchesResponseTypeDef",
     "ListWorldTemplatesResponseTypeDef",
     "ListWorldsResponseTypeDef",
     "PortForwardingConfigTypeDef",
     "RobotDeploymentTypeDef",
     "ListRobotApplicationsResponseTypeDef",
     "ListSimulationApplicationsResponseTypeDef",
@@ -219,22 +219,19 @@
 BatchDeleteWorldsRequestRequestTypeDef = TypedDict(
     "BatchDeleteWorldsRequestRequestTypeDef",
     {
         "worlds": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BatchDeleteWorldsResponseTypeDef = TypedDict(
+    "BatchDeleteWorldsResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "unprocessedWorlds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDescribeSimulationJobRequestRequestTypeDef = TypedDict(
     "BatchDescribeSimulationJobRequestRequestTypeDef",
     {
         "jobs": Sequence[str],
@@ -322,14 +319,25 @@
 
 class CreateFleetRequestRequestTypeDef(
     _RequiredCreateFleetRequestRequestTypeDef, _OptionalCreateFleetRequestRequestTypeDef
 ):
     pass
 
 
+CreateFleetResponseTypeDef = TypedDict(
+    "CreateFleetResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "createdAt": datetime,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnvironmentTypeDef = TypedDict(
     "EnvironmentTypeDef",
     {
         "uri": str,
     },
     total=False,
 )
@@ -407,14 +415,27 @@
 
 class CreateRobotRequestRequestTypeDef(
     _RequiredCreateRobotRequestRequestTypeDef, _OptionalCreateRobotRequestRequestTypeDef
 ):
     pass
 
 
+CreateRobotResponseTypeDef = TypedDict(
+    "CreateRobotResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "createdAt": datetime,
+        "greengrassGroupId": str,
+        "architecture": ArchitectureType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RenderingEngineTypeDef = TypedDict(
     "RenderingEngineTypeDef",
     {
         "name": Literal["OGRE"],
         "version": str,
     },
     total=False,
@@ -536,14 +557,26 @@
     "TemplateLocationTypeDef",
     {
         "s3Bucket": str,
         "s3Key": str,
     },
 )
 
+CreateWorldTemplateResponseTypeDef = TypedDict(
+    "CreateWorldTemplateResponseTypeDef",
+    {
+        "arn": str,
+        "clientRequestToken": str,
+        "createdAt": datetime,
+        "name": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3KeyOutputTypeDef = TypedDict(
     "S3KeyOutputTypeDef",
     {
         "s3Key": str,
         "etag": str,
     },
     total=False,
@@ -662,14 +695,23 @@
     "DeregisterRobotRequestRequestTypeDef",
     {
         "fleet": str,
         "robot": str,
     },
 )
 
+DeregisterRobotResponseTypeDef = TypedDict(
+    "DeregisterRobotResponseTypeDef",
+    {
+        "fleet": str,
+        "robot": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeploymentJobRequestRequestTypeDef = TypedDict(
     "DescribeDeploymentJobRequestRequestTypeDef",
     {
         "job": str,
     },
 )
 
@@ -721,14 +763,31 @@
 DescribeRobotRequestRequestTypeDef = TypedDict(
     "DescribeRobotRequestRequestTypeDef",
     {
         "robot": str,
     },
 )
 
+DescribeRobotResponseTypeDef = TypedDict(
+    "DescribeRobotResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "fleetArn": str,
+        "status": RobotStatusType,
+        "greengrassGroupId": str,
+        "createdAt": datetime,
+        "architecture": ArchitectureType,
+        "lastDeploymentJob": str,
+        "lastDeploymentTime": datetime,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeSimulationApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSimulationApplicationRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalDescribeSimulationApplicationRequestRequestTypeDef = TypedDict(
@@ -803,21 +862,48 @@
 DescribeWorldRequestRequestTypeDef = TypedDict(
     "DescribeWorldRequestRequestTypeDef",
     {
         "world": str,
     },
 )
 
+DescribeWorldResponseTypeDef = TypedDict(
+    "DescribeWorldResponseTypeDef",
+    {
+        "arn": str,
+        "generationJob": str,
+        "template": str,
+        "createdAt": datetime,
+        "tags": Dict[str, str],
+        "worldDescriptionBody": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeWorldTemplateRequestRequestTypeDef = TypedDict(
     "DescribeWorldTemplateRequestRequestTypeDef",
     {
         "template": str,
     },
 )
 
+DescribeWorldTemplateResponseTypeDef = TypedDict(
+    "DescribeWorldTemplateResponseTypeDef",
+    {
+        "arn": str,
+        "clientRequestToken": str,
+        "name": str,
+        "createdAt": datetime,
+        "lastUpdatedAt": datetime,
+        "tags": Dict[str, str],
+        "version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorldFailureTypeDef = TypedDict(
     "WorldFailureTypeDef",
     {
         "failureCode": WorldGenerationJobErrorCodeType,
         "sampleFailureReason": str,
         "failureCount": int,
     },
@@ -851,22 +937,20 @@
     {
         "template": str,
         "generationJob": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetWorldTemplateBodyResponseTypeDef = TypedDict(
+    "GetWorldTemplateBodyResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "templateBody": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 SimulationJobBatchSummaryTypeDef = TypedDict(
     "SimulationJobBatchSummaryTypeDef",
     {
         "arn": str,
         "lastUpdatedAt": datetime,
@@ -882,14 +966,30 @@
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
+ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef = TypedDict(
+    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorldTemplatesRequestRequestTypeDef = TypedDict(
     "ListWorldTemplatesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -914,14 +1014,24 @@
         "createdAt": datetime,
         "generationJob": str,
         "template": str,
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
 _RequiredPortMappingTypeDef = TypedDict(
     "_RequiredPortMappingTypeDef",
     {
         "jobPort": int,
         "applicationPort": int,
     },
 )
@@ -953,14 +1063,34 @@
     "RegisterRobotRequestRequestTypeDef",
     {
         "fleet": str,
         "robot": str,
     },
 )
 
+RegisterRobotResponseTypeDef = TypedDict(
+    "RegisterRobotResponseTypeDef",
+    {
+        "fleet": str,
+        "robot": str,
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
 RestartSimulationJobRequestRequestTypeDef = TypedDict(
     "RestartSimulationJobRequestRequestTypeDef",
     {
         "job": str,
     },
 )
 
@@ -1023,144 +1153,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-BatchDeleteWorldsResponseTypeDef = TypedDict(
-    "BatchDeleteWorldsResponseTypeDef",
-    {
-        "unprocessedWorlds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetResponseTypeDef = TypedDict(
-    "CreateFleetResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "createdAt": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRobotResponseTypeDef = TypedDict(
-    "CreateRobotResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "createdAt": datetime,
-        "greengrassGroupId": str,
-        "architecture": ArchitectureType,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorldTemplateResponseTypeDef = TypedDict(
-    "CreateWorldTemplateResponseTypeDef",
-    {
-        "arn": str,
-        "clientRequestToken": str,
-        "createdAt": datetime,
-        "name": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterRobotResponseTypeDef = TypedDict(
-    "DeregisterRobotResponseTypeDef",
-    {
-        "fleet": str,
-        "robot": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRobotResponseTypeDef = TypedDict(
-    "DescribeRobotResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "fleetArn": str,
-        "status": RobotStatusType,
-        "greengrassGroupId": str,
-        "createdAt": datetime,
-        "architecture": ArchitectureType,
-        "lastDeploymentJob": str,
-        "lastDeploymentTime": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWorldResponseTypeDef = TypedDict(
-    "DescribeWorldResponseTypeDef",
-    {
-        "arn": str,
-        "generationJob": str,
-        "template": str,
-        "createdAt": datetime,
-        "tags": Dict[str, str],
-        "worldDescriptionBody": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWorldTemplateResponseTypeDef = TypedDict(
-    "DescribeWorldTemplateResponseTypeDef",
-    {
-        "arn": str,
-        "clientRequestToken": str,
-        "name": str,
-        "createdAt": datetime,
-        "lastUpdatedAt": datetime,
-        "tags": Dict[str, str],
-        "version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorldTemplateBodyResponseTypeDef = TypedDict(
-    "GetWorldTemplateBodyResponseTypeDef",
-    {
-        "templateBody": str,
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
-RegisterRobotResponseTypeDef = TypedDict(
-    "RegisterRobotResponseTypeDef",
-    {
-        "fleet": str,
-        "robot": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateWorldTemplateResponseTypeDef = TypedDict(
     "UpdateWorldTemplateResponseTypeDef",
     {
         "arn": str,
         "name": str,
         "createdAt": datetime,
         "lastUpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RobotApplicationSummaryTypeDef = TypedDict(
     "RobotApplicationSummaryTypeDef",
     {
         "name": str,
@@ -1230,30 +1238,30 @@
         "version": str,
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRobotApplicationVersionResponseTypeDef = TypedDict(
     "CreateRobotApplicationVersionResponseTypeDef",
     {
         "arn": str,
         "name": str,
         "version": str,
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRobotApplicationResponseTypeDef = TypedDict(
     "DescribeRobotApplicationResponseTypeDef",
     {
         "arn": str,
@@ -1262,30 +1270,30 @@
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "revisionId": str,
         "lastUpdatedAt": datetime,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
         "imageDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRobotApplicationResponseTypeDef = TypedDict(
     "UpdateRobotApplicationResponseTypeDef",
     {
         "arn": str,
         "name": str,
         "version": str,
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSimulationApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSimulationApplicationRequestRequestTypeDef",
     {
         "name": str,
@@ -1322,15 +1330,15 @@
         "simulationSoftwareSuite": SimulationSoftwareSuiteTypeDef,
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSimulationApplicationVersionResponseTypeDef = TypedDict(
     "CreateSimulationApplicationVersionResponseTypeDef",
     {
         "arn": str,
@@ -1339,15 +1347,15 @@
         "sources": List[SourceTypeDef],
         "simulationSoftwareSuite": SimulationSoftwareSuiteTypeDef,
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationApplicationResponseTypeDef = TypedDict(
     "DescribeSimulationApplicationResponseTypeDef",
     {
         "arn": str,
@@ -1358,15 +1366,15 @@
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "revisionId": str,
         "lastUpdatedAt": datetime,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
         "imageDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SimulationApplicationSummaryTypeDef = TypedDict(
     "SimulationApplicationSummaryTypeDef",
     {
         "name": str,
@@ -1415,15 +1423,15 @@
         "sources": List[SourceTypeDef],
         "simulationSoftwareSuite": SimulationSoftwareSuiteTypeDef,
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorldExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorldExportJobRequestRequestTypeDef",
     {
         "worlds": Sequence[str],
@@ -1455,15 +1463,15 @@
         "status": WorldExportJobStatusType,
         "createdAt": datetime,
         "failureCode": WorldExportJobErrorCodeType,
         "clientRequestToken": str,
         "outputLocation": OutputLocationTypeDef,
         "iamRole": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorldExportJobResponseTypeDef = TypedDict(
     "DescribeWorldExportJobResponseTypeDef",
     {
         "arn": str,
@@ -1472,15 +1480,15 @@
         "failureCode": WorldExportJobErrorCodeType,
         "failureReason": str,
         "clientRequestToken": str,
         "worlds": List[str],
         "outputLocation": OutputLocationTypeDef,
         "iamRole": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorldExportJobSummaryTypeDef = TypedDict(
     "WorldExportJobSummaryTypeDef",
     {
         "arn": str,
@@ -1525,15 +1533,15 @@
         "createdAt": datetime,
         "failureCode": WorldGenerationJobErrorCodeType,
         "clientRequestToken": str,
         "template": str,
         "worldCount": WorldCountTypeDef,
         "tags": Dict[str, str],
         "worldTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorldGenerationJobSummaryTypeDef = TypedDict(
     "WorldGenerationJobSummaryTypeDef",
     {
         "arn": str,
@@ -1622,280 +1630,272 @@
         "arn": str,
         "robots": List[RobotTypeDef],
         "createdAt": datetime,
         "lastDeploymentStatus": DeploymentStatusType,
         "lastDeploymentJob": str,
         "lastDeploymentTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRobotsResponseTypeDef = TypedDict(
     "ListRobotsResponseTypeDef",
     {
         "robots": List[RobotTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSimulationJobsResponseTypeDef = TypedDict(
     "ListSimulationJobsResponseTypeDef",
     {
         "simulationJobSummaries": List[SimulationJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailureSummaryTypeDef = TypedDict(
     "FailureSummaryTypeDef",
     {
         "totalFailureCount": int,
         "failures": List[WorldFailureTypeDef],
     },
     total=False,
 )
 
-ListDeploymentJobsRequestRequestTypeDef = TypedDict(
-    "ListDeploymentJobsRequestRequestTypeDef",
+ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef = TypedDict(
+    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "nextToken": str,
-        "maxResults": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListFleetsRequestRequestTypeDef = TypedDict(
-    "ListFleetsRequestRequestTypeDef",
+ListDeploymentJobsRequestRequestTypeDef = TypedDict(
+    "ListDeploymentJobsRequestRequestTypeDef",
     {
+        "filters": Sequence[FilterTypeDef],
         "nextToken": str,
         "maxResults": int,
-        "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListRobotApplicationsRequestRequestTypeDef = TypedDict(
-    "ListRobotApplicationsRequestRequestTypeDef",
+ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
+    "ListFleetsRequestListFleetsPaginateTypeDef",
     {
-        "versionQualifier": str,
-        "nextToken": str,
-        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListRobotsRequestRequestTypeDef = TypedDict(
-    "ListRobotsRequestRequestTypeDef",
+ListFleetsRequestRequestTypeDef = TypedDict(
+    "ListFleetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListSimulationApplicationsRequestRequestTypeDef = TypedDict(
-    "ListSimulationApplicationsRequestRequestTypeDef",
+ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef = TypedDict(
+    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
     {
         "versionQualifier": str,
-        "nextToken": str,
-        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListSimulationJobBatchesRequestRequestTypeDef = TypedDict(
-    "ListSimulationJobBatchesRequestRequestTypeDef",
+ListRobotApplicationsRequestRequestTypeDef = TypedDict(
+    "ListRobotApplicationsRequestRequestTypeDef",
     {
+        "versionQualifier": str,
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListSimulationJobsRequestRequestTypeDef = TypedDict(
-    "ListSimulationJobsRequestRequestTypeDef",
+ListRobotsRequestListRobotsPaginateTypeDef = TypedDict(
+    "ListRobotsRequestListRobotsPaginateTypeDef",
     {
-        "nextToken": str,
-        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldExportJobsRequestRequestTypeDef = TypedDict(
-    "ListWorldExportJobsRequestRequestTypeDef",
+ListRobotsRequestRequestTypeDef = TypedDict(
+    "ListRobotsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListWorldGenerationJobsRequestRequestTypeDef = TypedDict(
-    "ListWorldGenerationJobsRequestRequestTypeDef",
+ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef = TypedDict(
+    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
     {
-        "nextToken": str,
-        "maxResults": int,
+        "versionQualifier": str,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldsRequestRequestTypeDef = TypedDict(
-    "ListWorldsRequestRequestTypeDef",
+ListSimulationApplicationsRequestRequestTypeDef = TypedDict(
+    "ListSimulationApplicationsRequestRequestTypeDef",
     {
+        "versionQualifier": str,
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListFleetsResponseTypeDef = TypedDict(
-    "ListFleetsResponseTypeDef",
-    {
-        "fleetDetails": List[FleetTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef = TypedDict(
-    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
+ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef = TypedDict(
+    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
-    "ListFleetsRequestListFleetsPaginateTypeDef",
+ListSimulationJobBatchesRequestRequestTypeDef = TypedDict(
+    "ListSimulationJobBatchesRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef = TypedDict(
-    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
+ListSimulationJobsRequestListSimulationJobsPaginateTypeDef = TypedDict(
+    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
     {
-        "versionQualifier": str,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListRobotsRequestListRobotsPaginateTypeDef = TypedDict(
-    "ListRobotsRequestListRobotsPaginateTypeDef",
+ListSimulationJobsRequestRequestTypeDef = TypedDict(
+    "ListSimulationJobsRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef = TypedDict(
-    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
+ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef = TypedDict(
+    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
     {
-        "versionQualifier": str,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef = TypedDict(
-    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
+ListWorldExportJobsRequestRequestTypeDef = TypedDict(
+    "ListWorldExportJobsRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListSimulationJobsRequestListSimulationJobsPaginateTypeDef = TypedDict(
-    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
+ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef = TypedDict(
+    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef = TypedDict(
-    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
+ListWorldGenerationJobsRequestRequestTypeDef = TypedDict(
+    "ListWorldGenerationJobsRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef = TypedDict(
-    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
+ListWorldsRequestListWorldsPaginateTypeDef = TypedDict(
+    "ListWorldsRequestListWorldsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef = TypedDict(
-    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
+ListWorldsRequestRequestTypeDef = TypedDict(
+    "ListWorldsRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "maxResults": int,
+        "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListWorldsRequestListWorldsPaginateTypeDef = TypedDict(
-    "ListWorldsRequestListWorldsPaginateTypeDef",
+ListFleetsResponseTypeDef = TypedDict(
+    "ListFleetsResponseTypeDef",
     {
-        "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "fleetDetails": List[FleetTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListSimulationJobBatchesResponseTypeDef = TypedDict(
     "ListSimulationJobBatchesResponseTypeDef",
     {
         "simulationJobBatchSummaries": List[SimulationJobBatchSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldTemplatesResponseTypeDef = TypedDict(
     "ListWorldTemplatesResponseTypeDef",
     {
         "templateSummaries": List[TemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldsResponseTypeDef = TypedDict(
     "ListWorldsResponseTypeDef",
     {
         "worldSummaries": List[WorldSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PortForwardingConfigTypeDef = TypedDict(
     "PortForwardingConfigTypeDef",
     {
         "portMappings": List[PortMappingTypeDef],
@@ -1918,42 +1918,42 @@
 )
 
 ListRobotApplicationsResponseTypeDef = TypedDict(
     "ListRobotApplicationsResponseTypeDef",
     {
         "robotApplicationSummaries": List[RobotApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSimulationApplicationsResponseTypeDef = TypedDict(
     "ListSimulationApplicationsResponseTypeDef",
     {
         "simulationApplicationSummaries": List[SimulationApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldExportJobsResponseTypeDef = TypedDict(
     "ListWorldExportJobsResponseTypeDef",
     {
         "worldExportJobSummaries": List[WorldExportJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldGenerationJobsResponseTypeDef = TypedDict(
     "ListWorldGenerationJobsResponseTypeDef",
     {
         "worldGenerationJobSummaries": List[WorldGenerationJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentJobRequestRequestTypeDef",
     {
         "clientRequestToken": str,
@@ -1986,15 +1986,15 @@
         "status": DeploymentStatusType,
         "deploymentApplicationConfigs": List[DeploymentApplicationConfigTypeDef],
         "failureReason": str,
         "failureCode": DeploymentJobErrorCodeType,
         "createdAt": datetime,
         "deploymentConfig": DeploymentConfigTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentJobTypeDef = TypedDict(
     "DeploymentJobTypeDef",
     {
         "arn": str,
@@ -2016,15 +2016,15 @@
         "fleet": str,
         "status": DeploymentStatusType,
         "deploymentConfig": DeploymentConfigTypeDef,
         "deploymentApplicationConfigs": List[DeploymentApplicationConfigTypeDef],
         "failureReason": str,
         "failureCode": DeploymentJobErrorCodeType,
         "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FinishedWorldsSummaryTypeDef = TypedDict(
     "FinishedWorldsSummaryTypeDef",
     {
         "finishedCount": int,
@@ -2056,24 +2056,24 @@
         "deploymentConfig": DeploymentConfigTypeDef,
         "deploymentApplicationConfigs": List[DeploymentApplicationConfigTypeDef],
         "failureReason": str,
         "failureCode": DeploymentJobErrorCodeType,
         "createdAt": datetime,
         "robotDeploymentSummary": List[RobotDeploymentTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeploymentJobsResponseTypeDef = TypedDict(
     "ListDeploymentJobsResponseTypeDef",
     {
         "deploymentJobs": List[DeploymentJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorldGenerationJobResponseTypeDef = TypedDict(
     "DescribeWorldGenerationJobResponseTypeDef",
     {
         "arn": str,
@@ -2083,15 +2083,15 @@
         "failureReason": str,
         "clientRequestToken": str,
         "template": str,
         "worldCount": WorldCountTypeDef,
         "finishedWorldsSummary": FinishedWorldsSummaryTypeDef,
         "tags": Dict[str, str],
         "worldTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRobotApplicationConfigTypeDef = TypedDict(
     "_RequiredRobotApplicationConfigTypeDef",
     {
         "application": str,
@@ -2193,15 +2193,15 @@
         "iamRole": str,
         "robotApplications": List[RobotApplicationConfigTypeDef],
         "simulationApplications": List[SimulationApplicationConfigTypeDef],
         "dataSources": List[DataSourceTypeDef],
         "tags": Dict[str, str],
         "vpcConfig": VPCConfigResponseTypeDef,
         "compute": ComputeResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationJobResponseTypeDef = TypedDict(
     "DescribeSimulationJobResponseTypeDef",
     {
         "arn": str,
@@ -2221,15 +2221,15 @@
         "robotApplications": List[RobotApplicationConfigTypeDef],
         "simulationApplications": List[SimulationApplicationConfigTypeDef],
         "dataSources": List[DataSourceTypeDef],
         "tags": Dict[str, str],
         "vpcConfig": VPCConfigResponseTypeDef,
         "networkInterface": NetworkInterfaceTypeDef,
         "compute": ComputeResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSimulationJobRequestTypeDef = TypedDict(
     "_RequiredSimulationJobRequestTypeDef",
     {
         "maxJobDurationInSeconds": int,
@@ -2324,15 +2324,15 @@
 
 
 BatchDescribeSimulationJobResponseTypeDef = TypedDict(
     "BatchDescribeSimulationJobResponseTypeDef",
     {
         "jobs": List[SimulationJobTypeDef],
         "unprocessedJobs": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationJobBatchResponseTypeDef = TypedDict(
     "DescribeSimulationJobBatchResponseTypeDef",
     {
         "arn": str,
@@ -2343,15 +2343,15 @@
         "batchPolicy": BatchPolicyTypeDef,
         "failureCode": Literal["InternalServiceError"],
         "failureReason": str,
         "failedRequests": List[FailedCreateSimulationJobRequestTypeDef],
         "pendingRequests": List[SimulationJobRequestTypeDef],
         "createdRequests": List[SimulationJobSummaryTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSimulationJobBatchResponseTypeDef = TypedDict(
     "StartSimulationJobBatchResponseTypeDef",
     {
         "arn": str,
@@ -2361,10 +2361,10 @@
         "batchPolicy": BatchPolicyTypeDef,
         "failureCode": Literal["InternalServiceError"],
         "failureReason": str,
         "failedRequests": List[FailedCreateSimulationJobRequestTypeDef],
         "pendingRequests": List[SimulationJobRequestTypeDef],
         "createdRequests": List[SimulationJobSummaryTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker/type_defs.pyi` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -45,95 +45,96 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BatchDeleteWorldsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BatchDeleteWorldsResponseTypeDef",
     "BatchDescribeSimulationJobRequestRequestTypeDef",
     "BatchPolicyTypeDef",
     "CancelDeploymentJobRequestRequestTypeDef",
     "CancelSimulationJobBatchRequestRequestTypeDef",
     "CancelSimulationJobRequestRequestTypeDef",
     "CancelWorldExportJobRequestRequestTypeDef",
     "CancelWorldGenerationJobRequestRequestTypeDef",
     "ComputeResponseTypeDef",
     "ComputeTypeDef",
     "CreateFleetRequestRequestTypeDef",
+    "CreateFleetResponseTypeDef",
     "EnvironmentTypeDef",
     "RobotSoftwareSuiteTypeDef",
     "SourceConfigTypeDef",
     "SourceTypeDef",
     "CreateRobotApplicationVersionRequestRequestTypeDef",
     "CreateRobotRequestRequestTypeDef",
+    "CreateRobotResponseTypeDef",
     "RenderingEngineTypeDef",
     "SimulationSoftwareSuiteTypeDef",
     "CreateSimulationApplicationVersionRequestRequestTypeDef",
     "DataSourceConfigTypeDef",
     "LoggingConfigTypeDef",
     "OutputLocationTypeDef",
     "VPCConfigTypeDef",
     "VPCConfigResponseTypeDef",
     "WorldCountTypeDef",
     "TemplateLocationTypeDef",
+    "CreateWorldTemplateResponseTypeDef",
     "S3KeyOutputTypeDef",
     "DeleteFleetRequestRequestTypeDef",
     "DeleteRobotApplicationRequestRequestTypeDef",
     "DeleteRobotRequestRequestTypeDef",
     "DeleteSimulationApplicationRequestRequestTypeDef",
     "DeleteWorldTemplateRequestRequestTypeDef",
     "DeploymentLaunchConfigTypeDef",
     "S3ObjectTypeDef",
     "DeregisterRobotRequestRequestTypeDef",
+    "DeregisterRobotResponseTypeDef",
     "DescribeDeploymentJobRequestRequestTypeDef",
     "DescribeFleetRequestRequestTypeDef",
     "RobotTypeDef",
     "DescribeRobotApplicationRequestRequestTypeDef",
     "DescribeRobotRequestRequestTypeDef",
+    "DescribeRobotResponseTypeDef",
     "DescribeSimulationApplicationRequestRequestTypeDef",
     "DescribeSimulationJobBatchRequestRequestTypeDef",
     "SimulationJobSummaryTypeDef",
     "DescribeSimulationJobRequestRequestTypeDef",
     "NetworkInterfaceTypeDef",
     "DescribeWorldExportJobRequestRequestTypeDef",
     "DescribeWorldGenerationJobRequestRequestTypeDef",
     "DescribeWorldRequestRequestTypeDef",
+    "DescribeWorldResponseTypeDef",
     "DescribeWorldTemplateRequestRequestTypeDef",
+    "DescribeWorldTemplateResponseTypeDef",
     "WorldFailureTypeDef",
     "FilterTypeDef",
     "FleetTypeDef",
     "GetWorldTemplateBodyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetWorldTemplateBodyResponseTypeDef",
     "SimulationJobBatchSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
     "ListWorldTemplatesRequestRequestTypeDef",
     "TemplateSummaryTypeDef",
     "WorldSummaryTypeDef",
+    "PaginatorConfigTypeDef",
     "PortMappingTypeDef",
     "ProgressDetailTypeDef",
     "RegisterRobotRequestRequestTypeDef",
+    "RegisterRobotResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RestartSimulationJobRequestRequestTypeDef",
     "ToolTypeDef",
     "UploadConfigurationTypeDef",
     "WorldConfigTypeDef",
     "SyncDeploymentJobRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "BatchDeleteWorldsResponseTypeDef",
-    "CreateFleetResponseTypeDef",
-    "CreateRobotResponseTypeDef",
-    "CreateWorldTemplateResponseTypeDef",
-    "DeregisterRobotResponseTypeDef",
-    "DescribeRobotResponseTypeDef",
-    "DescribeWorldResponseTypeDef",
-    "DescribeWorldTemplateResponseTypeDef",
-    "GetWorldTemplateBodyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterRobotResponseTypeDef",
     "UpdateWorldTemplateResponseTypeDef",
     "RobotApplicationSummaryTypeDef",
     "CreateRobotApplicationRequestRequestTypeDef",
     "UpdateRobotApplicationRequestRequestTypeDef",
     "CreateRobotApplicationResponseTypeDef",
     "CreateRobotApplicationVersionResponseTypeDef",
     "DescribeRobotApplicationResponseTypeDef",
@@ -157,36 +158,35 @@
     "DataSourceTypeDef",
     "DeploymentApplicationConfigTypeDef",
     "DeploymentConfigTypeDef",
     "DescribeFleetResponseTypeDef",
     "ListRobotsResponseTypeDef",
     "ListSimulationJobsResponseTypeDef",
     "FailureSummaryTypeDef",
+    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
     "ListDeploymentJobsRequestRequestTypeDef",
+    "ListFleetsRequestListFleetsPaginateTypeDef",
     "ListFleetsRequestRequestTypeDef",
+    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
     "ListRobotApplicationsRequestRequestTypeDef",
+    "ListRobotsRequestListRobotsPaginateTypeDef",
     "ListRobotsRequestRequestTypeDef",
+    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
     "ListSimulationApplicationsRequestRequestTypeDef",
+    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
     "ListSimulationJobBatchesRequestRequestTypeDef",
+    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
     "ListSimulationJobsRequestRequestTypeDef",
+    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
     "ListWorldExportJobsRequestRequestTypeDef",
+    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
     "ListWorldGenerationJobsRequestRequestTypeDef",
+    "ListWorldsRequestListWorldsPaginateTypeDef",
     "ListWorldsRequestRequestTypeDef",
     "ListFleetsResponseTypeDef",
-    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
-    "ListFleetsRequestListFleetsPaginateTypeDef",
-    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
-    "ListRobotsRequestListRobotsPaginateTypeDef",
-    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
-    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
-    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
-    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
-    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
-    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
-    "ListWorldsRequestListWorldsPaginateTypeDef",
     "ListSimulationJobBatchesResponseTypeDef",
     "ListWorldTemplatesResponseTypeDef",
     "ListWorldsResponseTypeDef",
     "PortForwardingConfigTypeDef",
     "RobotDeploymentTypeDef",
     "ListRobotApplicationsResponseTypeDef",
     "ListSimulationApplicationsResponseTypeDef",
@@ -218,22 +218,19 @@
 BatchDeleteWorldsRequestRequestTypeDef = TypedDict(
     "BatchDeleteWorldsRequestRequestTypeDef",
     {
         "worlds": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BatchDeleteWorldsResponseTypeDef = TypedDict(
+    "BatchDeleteWorldsResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "unprocessedWorlds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDescribeSimulationJobRequestRequestTypeDef = TypedDict(
     "BatchDescribeSimulationJobRequestRequestTypeDef",
     {
         "jobs": Sequence[str],
@@ -319,14 +316,25 @@
 )
 
 class CreateFleetRequestRequestTypeDef(
     _RequiredCreateFleetRequestRequestTypeDef, _OptionalCreateFleetRequestRequestTypeDef
 ):
     pass
 
+CreateFleetResponseTypeDef = TypedDict(
+    "CreateFleetResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "createdAt": datetime,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnvironmentTypeDef = TypedDict(
     "EnvironmentTypeDef",
     {
         "uri": str,
     },
     total=False,
 )
@@ -400,14 +408,27 @@
 )
 
 class CreateRobotRequestRequestTypeDef(
     _RequiredCreateRobotRequestRequestTypeDef, _OptionalCreateRobotRequestRequestTypeDef
 ):
     pass
 
+CreateRobotResponseTypeDef = TypedDict(
+    "CreateRobotResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "createdAt": datetime,
+        "greengrassGroupId": str,
+        "architecture": ArchitectureType,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RenderingEngineTypeDef = TypedDict(
     "RenderingEngineTypeDef",
     {
         "name": Literal["OGRE"],
         "version": str,
     },
     total=False,
@@ -523,14 +544,26 @@
     "TemplateLocationTypeDef",
     {
         "s3Bucket": str,
         "s3Key": str,
     },
 )
 
+CreateWorldTemplateResponseTypeDef = TypedDict(
+    "CreateWorldTemplateResponseTypeDef",
+    {
+        "arn": str,
+        "clientRequestToken": str,
+        "createdAt": datetime,
+        "name": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3KeyOutputTypeDef = TypedDict(
     "S3KeyOutputTypeDef",
     {
         "s3Key": str,
         "etag": str,
     },
     total=False,
@@ -641,14 +674,23 @@
     "DeregisterRobotRequestRequestTypeDef",
     {
         "fleet": str,
         "robot": str,
     },
 )
 
+DeregisterRobotResponseTypeDef = TypedDict(
+    "DeregisterRobotResponseTypeDef",
+    {
+        "fleet": str,
+        "robot": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeploymentJobRequestRequestTypeDef = TypedDict(
     "DescribeDeploymentJobRequestRequestTypeDef",
     {
         "job": str,
     },
 )
 
@@ -698,14 +740,31 @@
 DescribeRobotRequestRequestTypeDef = TypedDict(
     "DescribeRobotRequestRequestTypeDef",
     {
         "robot": str,
     },
 )
 
+DescribeRobotResponseTypeDef = TypedDict(
+    "DescribeRobotResponseTypeDef",
+    {
+        "arn": str,
+        "name": str,
+        "fleetArn": str,
+        "status": RobotStatusType,
+        "greengrassGroupId": str,
+        "createdAt": datetime,
+        "architecture": ArchitectureType,
+        "lastDeploymentJob": str,
+        "lastDeploymentTime": datetime,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeSimulationApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSimulationApplicationRequestRequestTypeDef",
     {
         "application": str,
     },
 )
 _OptionalDescribeSimulationApplicationRequestRequestTypeDef = TypedDict(
@@ -778,21 +837,48 @@
 DescribeWorldRequestRequestTypeDef = TypedDict(
     "DescribeWorldRequestRequestTypeDef",
     {
         "world": str,
     },
 )
 
+DescribeWorldResponseTypeDef = TypedDict(
+    "DescribeWorldResponseTypeDef",
+    {
+        "arn": str,
+        "generationJob": str,
+        "template": str,
+        "createdAt": datetime,
+        "tags": Dict[str, str],
+        "worldDescriptionBody": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeWorldTemplateRequestRequestTypeDef = TypedDict(
     "DescribeWorldTemplateRequestRequestTypeDef",
     {
         "template": str,
     },
 )
 
+DescribeWorldTemplateResponseTypeDef = TypedDict(
+    "DescribeWorldTemplateResponseTypeDef",
+    {
+        "arn": str,
+        "clientRequestToken": str,
+        "name": str,
+        "createdAt": datetime,
+        "lastUpdatedAt": datetime,
+        "tags": Dict[str, str],
+        "version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorldFailureTypeDef = TypedDict(
     "WorldFailureTypeDef",
     {
         "failureCode": WorldGenerationJobErrorCodeType,
         "sampleFailureReason": str,
         "failureCount": int,
     },
@@ -826,22 +912,20 @@
     {
         "template": str,
         "generationJob": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetWorldTemplateBodyResponseTypeDef = TypedDict(
+    "GetWorldTemplateBodyResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "templateBody": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 SimulationJobBatchSummaryTypeDef = TypedDict(
     "SimulationJobBatchSummaryTypeDef",
     {
         "arn": str,
         "lastUpdatedAt": datetime,
@@ -857,14 +941,30 @@
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
+ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef = TypedDict(
+    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorldTemplatesRequestRequestTypeDef = TypedDict(
     "ListWorldTemplatesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -889,14 +989,24 @@
         "createdAt": datetime,
         "generationJob": str,
         "template": str,
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
 _RequiredPortMappingTypeDef = TypedDict(
     "_RequiredPortMappingTypeDef",
     {
         "jobPort": int,
         "applicationPort": int,
     },
 )
@@ -926,14 +1036,34 @@
     "RegisterRobotRequestRequestTypeDef",
     {
         "fleet": str,
         "robot": str,
     },
 )
 
+RegisterRobotResponseTypeDef = TypedDict(
+    "RegisterRobotResponseTypeDef",
+    {
+        "fleet": str,
+        "robot": str,
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
 RestartSimulationJobRequestRequestTypeDef = TypedDict(
     "RestartSimulationJobRequestRequestTypeDef",
     {
         "job": str,
     },
 )
 
@@ -994,144 +1124,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-BatchDeleteWorldsResponseTypeDef = TypedDict(
-    "BatchDeleteWorldsResponseTypeDef",
-    {
-        "unprocessedWorlds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetResponseTypeDef = TypedDict(
-    "CreateFleetResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "createdAt": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRobotResponseTypeDef = TypedDict(
-    "CreateRobotResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "createdAt": datetime,
-        "greengrassGroupId": str,
-        "architecture": ArchitectureType,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorldTemplateResponseTypeDef = TypedDict(
-    "CreateWorldTemplateResponseTypeDef",
-    {
-        "arn": str,
-        "clientRequestToken": str,
-        "createdAt": datetime,
-        "name": str,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterRobotResponseTypeDef = TypedDict(
-    "DeregisterRobotResponseTypeDef",
-    {
-        "fleet": str,
-        "robot": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRobotResponseTypeDef = TypedDict(
-    "DescribeRobotResponseTypeDef",
-    {
-        "arn": str,
-        "name": str,
-        "fleetArn": str,
-        "status": RobotStatusType,
-        "greengrassGroupId": str,
-        "createdAt": datetime,
-        "architecture": ArchitectureType,
-        "lastDeploymentJob": str,
-        "lastDeploymentTime": datetime,
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWorldResponseTypeDef = TypedDict(
-    "DescribeWorldResponseTypeDef",
-    {
-        "arn": str,
-        "generationJob": str,
-        "template": str,
-        "createdAt": datetime,
-        "tags": Dict[str, str],
-        "worldDescriptionBody": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeWorldTemplateResponseTypeDef = TypedDict(
-    "DescribeWorldTemplateResponseTypeDef",
-    {
-        "arn": str,
-        "clientRequestToken": str,
-        "name": str,
-        "createdAt": datetime,
-        "lastUpdatedAt": datetime,
-        "tags": Dict[str, str],
-        "version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorldTemplateBodyResponseTypeDef = TypedDict(
-    "GetWorldTemplateBodyResponseTypeDef",
-    {
-        "templateBody": str,
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
-RegisterRobotResponseTypeDef = TypedDict(
-    "RegisterRobotResponseTypeDef",
-    {
-        "fleet": str,
-        "robot": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateWorldTemplateResponseTypeDef = TypedDict(
     "UpdateWorldTemplateResponseTypeDef",
     {
         "arn": str,
         "name": str,
         "createdAt": datetime,
         "lastUpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RobotApplicationSummaryTypeDef = TypedDict(
     "RobotApplicationSummaryTypeDef",
     {
         "name": str,
@@ -1197,30 +1205,30 @@
         "version": str,
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRobotApplicationVersionResponseTypeDef = TypedDict(
     "CreateRobotApplicationVersionResponseTypeDef",
     {
         "arn": str,
         "name": str,
         "version": str,
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRobotApplicationResponseTypeDef = TypedDict(
     "DescribeRobotApplicationResponseTypeDef",
     {
         "arn": str,
@@ -1229,30 +1237,30 @@
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "revisionId": str,
         "lastUpdatedAt": datetime,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
         "imageDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRobotApplicationResponseTypeDef = TypedDict(
     "UpdateRobotApplicationResponseTypeDef",
     {
         "arn": str,
         "name": str,
         "version": str,
         "sources": List[SourceTypeDef],
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSimulationApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSimulationApplicationRequestRequestTypeDef",
     {
         "name": str,
@@ -1287,15 +1295,15 @@
         "simulationSoftwareSuite": SimulationSoftwareSuiteTypeDef,
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSimulationApplicationVersionResponseTypeDef = TypedDict(
     "CreateSimulationApplicationVersionResponseTypeDef",
     {
         "arn": str,
@@ -1304,15 +1312,15 @@
         "sources": List[SourceTypeDef],
         "simulationSoftwareSuite": SimulationSoftwareSuiteTypeDef,
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationApplicationResponseTypeDef = TypedDict(
     "DescribeSimulationApplicationResponseTypeDef",
     {
         "arn": str,
@@ -1323,15 +1331,15 @@
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "revisionId": str,
         "lastUpdatedAt": datetime,
         "tags": Dict[str, str],
         "environment": EnvironmentTypeDef,
         "imageDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SimulationApplicationSummaryTypeDef = TypedDict(
     "SimulationApplicationSummaryTypeDef",
     {
         "name": str,
@@ -1378,15 +1386,15 @@
         "sources": List[SourceTypeDef],
         "simulationSoftwareSuite": SimulationSoftwareSuiteTypeDef,
         "robotSoftwareSuite": RobotSoftwareSuiteTypeDef,
         "renderingEngine": RenderingEngineTypeDef,
         "lastUpdatedAt": datetime,
         "revisionId": str,
         "environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorldExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorldExportJobRequestRequestTypeDef",
     {
         "worlds": Sequence[str],
@@ -1416,15 +1424,15 @@
         "status": WorldExportJobStatusType,
         "createdAt": datetime,
         "failureCode": WorldExportJobErrorCodeType,
         "clientRequestToken": str,
         "outputLocation": OutputLocationTypeDef,
         "iamRole": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorldExportJobResponseTypeDef = TypedDict(
     "DescribeWorldExportJobResponseTypeDef",
     {
         "arn": str,
@@ -1433,15 +1441,15 @@
         "failureCode": WorldExportJobErrorCodeType,
         "failureReason": str,
         "clientRequestToken": str,
         "worlds": List[str],
         "outputLocation": OutputLocationTypeDef,
         "iamRole": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorldExportJobSummaryTypeDef = TypedDict(
     "WorldExportJobSummaryTypeDef",
     {
         "arn": str,
@@ -1484,15 +1492,15 @@
         "createdAt": datetime,
         "failureCode": WorldGenerationJobErrorCodeType,
         "clientRequestToken": str,
         "template": str,
         "worldCount": WorldCountTypeDef,
         "tags": Dict[str, str],
         "worldTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorldGenerationJobSummaryTypeDef = TypedDict(
     "WorldGenerationJobSummaryTypeDef",
     {
         "arn": str,
@@ -1579,280 +1587,272 @@
         "arn": str,
         "robots": List[RobotTypeDef],
         "createdAt": datetime,
         "lastDeploymentStatus": DeploymentStatusType,
         "lastDeploymentJob": str,
         "lastDeploymentTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRobotsResponseTypeDef = TypedDict(
     "ListRobotsResponseTypeDef",
     {
         "robots": List[RobotTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSimulationJobsResponseTypeDef = TypedDict(
     "ListSimulationJobsResponseTypeDef",
     {
         "simulationJobSummaries": List[SimulationJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailureSummaryTypeDef = TypedDict(
     "FailureSummaryTypeDef",
     {
         "totalFailureCount": int,
         "failures": List[WorldFailureTypeDef],
     },
     total=False,
 )
 
-ListDeploymentJobsRequestRequestTypeDef = TypedDict(
-    "ListDeploymentJobsRequestRequestTypeDef",
+ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef = TypedDict(
+    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "nextToken": str,
-        "maxResults": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListFleetsRequestRequestTypeDef = TypedDict(
-    "ListFleetsRequestRequestTypeDef",
+ListDeploymentJobsRequestRequestTypeDef = TypedDict(
+    "ListDeploymentJobsRequestRequestTypeDef",
     {
+        "filters": Sequence[FilterTypeDef],
         "nextToken": str,
         "maxResults": int,
-        "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListRobotApplicationsRequestRequestTypeDef = TypedDict(
-    "ListRobotApplicationsRequestRequestTypeDef",
+ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
+    "ListFleetsRequestListFleetsPaginateTypeDef",
     {
-        "versionQualifier": str,
-        "nextToken": str,
-        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListRobotsRequestRequestTypeDef = TypedDict(
-    "ListRobotsRequestRequestTypeDef",
+ListFleetsRequestRequestTypeDef = TypedDict(
+    "ListFleetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListSimulationApplicationsRequestRequestTypeDef = TypedDict(
-    "ListSimulationApplicationsRequestRequestTypeDef",
+ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef = TypedDict(
+    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
     {
         "versionQualifier": str,
-        "nextToken": str,
-        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListSimulationJobBatchesRequestRequestTypeDef = TypedDict(
-    "ListSimulationJobBatchesRequestRequestTypeDef",
+ListRobotApplicationsRequestRequestTypeDef = TypedDict(
+    "ListRobotApplicationsRequestRequestTypeDef",
     {
+        "versionQualifier": str,
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListSimulationJobsRequestRequestTypeDef = TypedDict(
-    "ListSimulationJobsRequestRequestTypeDef",
+ListRobotsRequestListRobotsPaginateTypeDef = TypedDict(
+    "ListRobotsRequestListRobotsPaginateTypeDef",
     {
-        "nextToken": str,
-        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldExportJobsRequestRequestTypeDef = TypedDict(
-    "ListWorldExportJobsRequestRequestTypeDef",
+ListRobotsRequestRequestTypeDef = TypedDict(
+    "ListRobotsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListWorldGenerationJobsRequestRequestTypeDef = TypedDict(
-    "ListWorldGenerationJobsRequestRequestTypeDef",
+ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef = TypedDict(
+    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
     {
-        "nextToken": str,
-        "maxResults": int,
+        "versionQualifier": str,
         "filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldsRequestRequestTypeDef = TypedDict(
-    "ListWorldsRequestRequestTypeDef",
+ListSimulationApplicationsRequestRequestTypeDef = TypedDict(
+    "ListSimulationApplicationsRequestRequestTypeDef",
     {
+        "versionQualifier": str,
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListFleetsResponseTypeDef = TypedDict(
-    "ListFleetsResponseTypeDef",
-    {
-        "fleetDetails": List[FleetTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef = TypedDict(
-    "ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef",
+ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef = TypedDict(
+    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListFleetsRequestListFleetsPaginateTypeDef = TypedDict(
-    "ListFleetsRequestListFleetsPaginateTypeDef",
+ListSimulationJobBatchesRequestRequestTypeDef = TypedDict(
+    "ListSimulationJobBatchesRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef = TypedDict(
-    "ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef",
+ListSimulationJobsRequestListSimulationJobsPaginateTypeDef = TypedDict(
+    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
     {
-        "versionQualifier": str,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListRobotsRequestListRobotsPaginateTypeDef = TypedDict(
-    "ListRobotsRequestListRobotsPaginateTypeDef",
+ListSimulationJobsRequestRequestTypeDef = TypedDict(
+    "ListSimulationJobsRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef = TypedDict(
-    "ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef",
+ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef = TypedDict(
+    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
     {
-        "versionQualifier": str,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef = TypedDict(
-    "ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef",
+ListWorldExportJobsRequestRequestTypeDef = TypedDict(
+    "ListWorldExportJobsRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListSimulationJobsRequestListSimulationJobsPaginateTypeDef = TypedDict(
-    "ListSimulationJobsRequestListSimulationJobsPaginateTypeDef",
+ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef = TypedDict(
+    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef = TypedDict(
-    "ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef",
+ListWorldGenerationJobsRequestRequestTypeDef = TypedDict(
+    "ListWorldGenerationJobsRequestRequestTypeDef",
     {
+        "nextToken": str,
+        "maxResults": int,
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef = TypedDict(
-    "ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef",
+ListWorldsRequestListWorldsPaginateTypeDef = TypedDict(
+    "ListWorldsRequestListWorldsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef = TypedDict(
-    "ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef",
+ListWorldsRequestRequestTypeDef = TypedDict(
+    "ListWorldsRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "maxResults": int,
+        "filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-ListWorldsRequestListWorldsPaginateTypeDef = TypedDict(
-    "ListWorldsRequestListWorldsPaginateTypeDef",
+ListFleetsResponseTypeDef = TypedDict(
+    "ListFleetsResponseTypeDef",
     {
-        "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "fleetDetails": List[FleetTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListSimulationJobBatchesResponseTypeDef = TypedDict(
     "ListSimulationJobBatchesResponseTypeDef",
     {
         "simulationJobBatchSummaries": List[SimulationJobBatchSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldTemplatesResponseTypeDef = TypedDict(
     "ListWorldTemplatesResponseTypeDef",
     {
         "templateSummaries": List[TemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldsResponseTypeDef = TypedDict(
     "ListWorldsResponseTypeDef",
     {
         "worldSummaries": List[WorldSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PortForwardingConfigTypeDef = TypedDict(
     "PortForwardingConfigTypeDef",
     {
         "portMappings": List[PortMappingTypeDef],
@@ -1875,42 +1875,42 @@
 )
 
 ListRobotApplicationsResponseTypeDef = TypedDict(
     "ListRobotApplicationsResponseTypeDef",
     {
         "robotApplicationSummaries": List[RobotApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSimulationApplicationsResponseTypeDef = TypedDict(
     "ListSimulationApplicationsResponseTypeDef",
     {
         "simulationApplicationSummaries": List[SimulationApplicationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldExportJobsResponseTypeDef = TypedDict(
     "ListWorldExportJobsResponseTypeDef",
     {
         "worldExportJobSummaries": List[WorldExportJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorldGenerationJobsResponseTypeDef = TypedDict(
     "ListWorldGenerationJobsResponseTypeDef",
     {
         "worldGenerationJobSummaries": List[WorldGenerationJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentJobRequestRequestTypeDef",
     {
         "clientRequestToken": str,
@@ -1941,15 +1941,15 @@
         "status": DeploymentStatusType,
         "deploymentApplicationConfigs": List[DeploymentApplicationConfigTypeDef],
         "failureReason": str,
         "failureCode": DeploymentJobErrorCodeType,
         "createdAt": datetime,
         "deploymentConfig": DeploymentConfigTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentJobTypeDef = TypedDict(
     "DeploymentJobTypeDef",
     {
         "arn": str,
@@ -1971,15 +1971,15 @@
         "fleet": str,
         "status": DeploymentStatusType,
         "deploymentConfig": DeploymentConfigTypeDef,
         "deploymentApplicationConfigs": List[DeploymentApplicationConfigTypeDef],
         "failureReason": str,
         "failureCode": DeploymentJobErrorCodeType,
         "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FinishedWorldsSummaryTypeDef = TypedDict(
     "FinishedWorldsSummaryTypeDef",
     {
         "finishedCount": int,
@@ -2011,24 +2011,24 @@
         "deploymentConfig": DeploymentConfigTypeDef,
         "deploymentApplicationConfigs": List[DeploymentApplicationConfigTypeDef],
         "failureReason": str,
         "failureCode": DeploymentJobErrorCodeType,
         "createdAt": datetime,
         "robotDeploymentSummary": List[RobotDeploymentTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeploymentJobsResponseTypeDef = TypedDict(
     "ListDeploymentJobsResponseTypeDef",
     {
         "deploymentJobs": List[DeploymentJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeWorldGenerationJobResponseTypeDef = TypedDict(
     "DescribeWorldGenerationJobResponseTypeDef",
     {
         "arn": str,
@@ -2038,15 +2038,15 @@
         "failureReason": str,
         "clientRequestToken": str,
         "template": str,
         "worldCount": WorldCountTypeDef,
         "finishedWorldsSummary": FinishedWorldsSummaryTypeDef,
         "tags": Dict[str, str],
         "worldTags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRobotApplicationConfigTypeDef = TypedDict(
     "_RequiredRobotApplicationConfigTypeDef",
     {
         "application": str,
@@ -2142,15 +2142,15 @@
         "iamRole": str,
         "robotApplications": List[RobotApplicationConfigTypeDef],
         "simulationApplications": List[SimulationApplicationConfigTypeDef],
         "dataSources": List[DataSourceTypeDef],
         "tags": Dict[str, str],
         "vpcConfig": VPCConfigResponseTypeDef,
         "compute": ComputeResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationJobResponseTypeDef = TypedDict(
     "DescribeSimulationJobResponseTypeDef",
     {
         "arn": str,
@@ -2170,15 +2170,15 @@
         "robotApplications": List[RobotApplicationConfigTypeDef],
         "simulationApplications": List[SimulationApplicationConfigTypeDef],
         "dataSources": List[DataSourceTypeDef],
         "tags": Dict[str, str],
         "vpcConfig": VPCConfigResponseTypeDef,
         "networkInterface": NetworkInterfaceTypeDef,
         "compute": ComputeResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSimulationJobRequestTypeDef = TypedDict(
     "_RequiredSimulationJobRequestTypeDef",
     {
         "maxJobDurationInSeconds": int,
@@ -2269,15 +2269,15 @@
     pass
 
 BatchDescribeSimulationJobResponseTypeDef = TypedDict(
     "BatchDescribeSimulationJobResponseTypeDef",
     {
         "jobs": List[SimulationJobTypeDef],
         "unprocessedJobs": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationJobBatchResponseTypeDef = TypedDict(
     "DescribeSimulationJobBatchResponseTypeDef",
     {
         "arn": str,
@@ -2288,15 +2288,15 @@
         "batchPolicy": BatchPolicyTypeDef,
         "failureCode": Literal["InternalServiceError"],
         "failureReason": str,
         "failedRequests": List[FailedCreateSimulationJobRequestTypeDef],
         "pendingRequests": List[SimulationJobRequestTypeDef],
         "createdRequests": List[SimulationJobSummaryTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSimulationJobBatchResponseTypeDef = TypedDict(
     "StartSimulationJobBatchResponseTypeDef",
     {
         "arn": str,
@@ -2306,10 +2306,10 @@
         "batchPolicy": BatchPolicyTypeDef,
         "failureCode": Literal["InternalServiceError"],
         "failureReason": str,
         "failedRequests": List[FailedCreateSimulationJobRequestTypeDef],
         "pendingRequests": List[SimulationJobRequestTypeDef],
         "createdRequests": List[SimulationJobSummaryTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/PKG-INFO` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-robomaker
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RoboMaker 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RoboMaker 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-robomaker"></a>
 
 # types-aiobotocore-robomaker
 
 [![PyPI - types-aiobotocore-robomaker](https://img.shields.io/pypi/v/types-aiobotocore-robomaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-robomaker)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-robomaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-robomaker)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-robomaker?color=blue)](https://pypistats.org/packages/types-aiobotocore-robomaker)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RoboMaker 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker)
+[aiobotocore.RoboMaker 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/robomaker.html#RoboMaker)
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
 [types-aiobotocore-robomaker docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_robomaker/).
 
 See how it helps to find and fix potential bugs:
 
@@ -385,95 +385,96 @@
 
 `types_aiobotocore_robomaker.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_robomaker.type_defs import (
     BatchDeleteWorldsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BatchDeleteWorldsResponseTypeDef,
     BatchDescribeSimulationJobRequestRequestTypeDef,
     BatchPolicyTypeDef,
     CancelDeploymentJobRequestRequestTypeDef,
     CancelSimulationJobBatchRequestRequestTypeDef,
     CancelSimulationJobRequestRequestTypeDef,
     CancelWorldExportJobRequestRequestTypeDef,
     CancelWorldGenerationJobRequestRequestTypeDef,
     ComputeResponseTypeDef,
     ComputeTypeDef,
     CreateFleetRequestRequestTypeDef,
+    CreateFleetResponseTypeDef,
     EnvironmentTypeDef,
     RobotSoftwareSuiteTypeDef,
     SourceConfigTypeDef,
     SourceTypeDef,
     CreateRobotApplicationVersionRequestRequestTypeDef,
     CreateRobotRequestRequestTypeDef,
+    CreateRobotResponseTypeDef,
     RenderingEngineTypeDef,
     SimulationSoftwareSuiteTypeDef,
     CreateSimulationApplicationVersionRequestRequestTypeDef,
     DataSourceConfigTypeDef,
     LoggingConfigTypeDef,
     OutputLocationTypeDef,
     VPCConfigTypeDef,
     VPCConfigResponseTypeDef,
     WorldCountTypeDef,
     TemplateLocationTypeDef,
+    CreateWorldTemplateResponseTypeDef,
     S3KeyOutputTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DeleteRobotApplicationRequestRequestTypeDef,
     DeleteRobotRequestRequestTypeDef,
     DeleteSimulationApplicationRequestRequestTypeDef,
     DeleteWorldTemplateRequestRequestTypeDef,
     DeploymentLaunchConfigTypeDef,
     S3ObjectTypeDef,
     DeregisterRobotRequestRequestTypeDef,
+    DeregisterRobotResponseTypeDef,
     DescribeDeploymentJobRequestRequestTypeDef,
     DescribeFleetRequestRequestTypeDef,
     RobotTypeDef,
     DescribeRobotApplicationRequestRequestTypeDef,
     DescribeRobotRequestRequestTypeDef,
+    DescribeRobotResponseTypeDef,
     DescribeSimulationApplicationRequestRequestTypeDef,
     DescribeSimulationJobBatchRequestRequestTypeDef,
     SimulationJobSummaryTypeDef,
     DescribeSimulationJobRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
     DescribeWorldExportJobRequestRequestTypeDef,
     DescribeWorldGenerationJobRequestRequestTypeDef,
     DescribeWorldRequestRequestTypeDef,
+    DescribeWorldResponseTypeDef,
     DescribeWorldTemplateRequestRequestTypeDef,
+    DescribeWorldTemplateResponseTypeDef,
     WorldFailureTypeDef,
     FilterTypeDef,
     FleetTypeDef,
     GetWorldTemplateBodyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorldTemplateBodyResponseTypeDef,
     SimulationJobBatchSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef,
     ListWorldTemplatesRequestRequestTypeDef,
     TemplateSummaryTypeDef,
     WorldSummaryTypeDef,
+    PaginatorConfigTypeDef,
     PortMappingTypeDef,
     ProgressDetailTypeDef,
     RegisterRobotRequestRequestTypeDef,
+    RegisterRobotResponseTypeDef,
+    ResponseMetadataTypeDef,
     RestartSimulationJobRequestRequestTypeDef,
     ToolTypeDef,
     UploadConfigurationTypeDef,
     WorldConfigTypeDef,
     SyncDeploymentJobRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    BatchDeleteWorldsResponseTypeDef,
-    CreateFleetResponseTypeDef,
-    CreateRobotResponseTypeDef,
-    CreateWorldTemplateResponseTypeDef,
-    DeregisterRobotResponseTypeDef,
-    DescribeRobotResponseTypeDef,
-    DescribeWorldResponseTypeDef,
-    DescribeWorldTemplateResponseTypeDef,
-    GetWorldTemplateBodyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterRobotResponseTypeDef,
     UpdateWorldTemplateResponseTypeDef,
     RobotApplicationSummaryTypeDef,
     CreateRobotApplicationRequestRequestTypeDef,
     UpdateRobotApplicationRequestRequestTypeDef,
     CreateRobotApplicationResponseTypeDef,
     CreateRobotApplicationVersionResponseTypeDef,
     DescribeRobotApplicationResponseTypeDef,
@@ -497,36 +498,35 @@
     DataSourceTypeDef,
     DeploymentApplicationConfigTypeDef,
     DeploymentConfigTypeDef,
     DescribeFleetResponseTypeDef,
     ListRobotsResponseTypeDef,
     ListSimulationJobsResponseTypeDef,
     FailureSummaryTypeDef,
+    ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef,
     ListDeploymentJobsRequestRequestTypeDef,
+    ListFleetsRequestListFleetsPaginateTypeDef,
     ListFleetsRequestRequestTypeDef,
+    ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef,
     ListRobotApplicationsRequestRequestTypeDef,
+    ListRobotsRequestListRobotsPaginateTypeDef,
     ListRobotsRequestRequestTypeDef,
+    ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef,
     ListSimulationApplicationsRequestRequestTypeDef,
+    ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef,
     ListSimulationJobBatchesRequestRequestTypeDef,
+    ListSimulationJobsRequestListSimulationJobsPaginateTypeDef,
     ListSimulationJobsRequestRequestTypeDef,
+    ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef,
     ListWorldExportJobsRequestRequestTypeDef,
+    ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef,
     ListWorldGenerationJobsRequestRequestTypeDef,
+    ListWorldsRequestListWorldsPaginateTypeDef,
     ListWorldsRequestRequestTypeDef,
     ListFleetsResponseTypeDef,
-    ListDeploymentJobsRequestListDeploymentJobsPaginateTypeDef,
-    ListFleetsRequestListFleetsPaginateTypeDef,
-    ListRobotApplicationsRequestListRobotApplicationsPaginateTypeDef,
-    ListRobotsRequestListRobotsPaginateTypeDef,
-    ListSimulationApplicationsRequestListSimulationApplicationsPaginateTypeDef,
-    ListSimulationJobBatchesRequestListSimulationJobBatchesPaginateTypeDef,
-    ListSimulationJobsRequestListSimulationJobsPaginateTypeDef,
-    ListWorldExportJobsRequestListWorldExportJobsPaginateTypeDef,
-    ListWorldGenerationJobsRequestListWorldGenerationJobsPaginateTypeDef,
-    ListWorldTemplatesRequestListWorldTemplatesPaginateTypeDef,
-    ListWorldsRequestListWorldsPaginateTypeDef,
     ListSimulationJobBatchesResponseTypeDef,
     ListWorldTemplatesResponseTypeDef,
     ListWorldsResponseTypeDef,
     PortForwardingConfigTypeDef,
     RobotDeploymentTypeDef,
     ListRobotApplicationsResponseTypeDef,
     ListSimulationApplicationsResponseTypeDef,
@@ -563,43 +563,43 @@
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

### Comparing `types-aiobotocore-robomaker-2.5.0.post1/types_aiobotocore_robomaker.egg-info/SOURCES.txt` & `types-aiobotocore-robomaker-2.5.1/types_aiobotocore_robomaker.egg-info/SOURCES.txt`

 * *Files identical despite different names*

