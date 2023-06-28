# Comparing `tmp/types-aiobotocore-m2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-m2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-m2-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-m2-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-m2-2.5.0.post1.tar` & `types-aiobotocore-m2-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.311393 types-aiobotocore-m2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18782 2023-03-11 12:26:56.311393 types-aiobotocore-m2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17211 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.311393 types-aiobotocore-m2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2085 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.307393 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/
--rw-r--r--   0 runner    (1001) docker     (123)     2529 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2528 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      952 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29306 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    29256 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10151 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10149 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12009 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11997 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    40910 2023-03-11 12:17:57.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    40846 2023-03-11 12:17:57.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.311393 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18782 2023-03-11 12:26:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      718 2023-03-11 12:26:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-03-11 12:26:56.000000 types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.394170 types-aiobotocore-m2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18881 2023-06-28 01:43:47.394170 types-aiobotocore-m2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17316 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.394170 types-aiobotocore-m2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.394170 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/
+-rw-r--r--   0 runner    (1001) docker     (123)     2529 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2528 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      940 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29334 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29284 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10360 2023-06-28 01:34:38.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10358 2023-06-28 01:34:38.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11907 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11896 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    42341 2023-06-28 01:34:39.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42273 2023-06-28 01:34:38.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:36.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.394170 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18881 2023-06-28 01:43:47.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      718 2023-06-28 01:43:47.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 01:43:47.000000 types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/LICENSE` & `types-aiobotocore-m2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-m2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-m2-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-m2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MainframeModernization 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MainframeModernization 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-m2"></a>
 
 # types-aiobotocore-m2
 
 [![PyPI - types-aiobotocore-m2](https://img.shields.io/pypi/v/types-aiobotocore-m2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-m2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-m2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-m2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-m2?color=blue)](https://pypistats.org/packages/types-aiobotocore-m2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MainframeModernization 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization)
+[aiobotocore.MainframeModernization 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization)
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
 [types-aiobotocore-m2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -371,91 +371,95 @@
     ApplicationVersionSummaryTypeDef,
     FileBatchJobDefinitionTypeDef,
     ScriptBatchJobDefinitionTypeDef,
     FileBatchJobIdentifierTypeDef,
     ScriptBatchJobIdentifierTypeDef,
     CancelBatchJobExecutionRequestRequestTypeDef,
     DefinitionTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationResponseTypeDef,
+    CreateDataSetImportTaskResponseTypeDef,
     CreateDeploymentRequestRequestTypeDef,
+    CreateDeploymentResponseTypeDef,
     HighAvailabilityConfigTypeDef,
+    CreateEnvironmentResponseTypeDef,
     ExternalLocationTypeDef,
     DataSetImportSummaryTypeDef,
     DataSetSummaryTypeDef,
     RecordLengthTypeDef,
     GdgDetailAttributesTypeDef,
+    PoDetailAttributesTypeDef,
+    PsDetailAttributesTypeDef,
     GdgAttributesTypeDef,
+    PoAttributesTypeDef,
+    PsAttributesTypeDef,
     DeleteApplicationFromEnvironmentRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
     DeployedVersionSummaryTypeDef,
     DeploymentSummaryTypeDef,
     EfsStorageConfigurationTypeDef,
     EngineVersionsSummaryTypeDef,
     EnvironmentSummaryTypeDef,
     FsxStorageConfigurationTypeDef,
     GetApplicationRequestRequestTypeDef,
     LogGroupSummaryTypeDef,
     GetApplicationVersionRequestRequestTypeDef,
+    GetApplicationVersionResponseTypeDef,
     GetBatchJobExecutionRequestRequestTypeDef,
     GetDataSetDetailsRequestRequestTypeDef,
     GetDataSetImportTaskRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetDeploymentResponseTypeDef,
     GetEnvironmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
     ListBatchJobDefinitionsRequestRequestTypeDef,
+    ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
     ListBatchJobExecutionsRequestRequestTypeDef,
+    ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
     ListDataSetImportHistoryRequestRequestTypeDef,
+    ListDataSetsRequestListDataSetsPaginateTypeDef,
     ListDataSetsRequestRequestTypeDef,
+    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
     ListDeploymentsRequestRequestTypeDef,
+    ListEngineVersionsRequestListEngineVersionsPaginateTypeDef,
     ListEngineVersionsRequestRequestTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MaintenanceScheduleTypeDef,
+    PaginatorConfigTypeDef,
     PrimaryKeyTypeDef,
+    ResponseMetadataTypeDef,
     StartApplicationRequestRequestTypeDef,
+    StartBatchJobResponseTypeDef,
     StopApplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateApplicationResponseTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
+    UpdateEnvironmentResponseTypeDef,
+    ListApplicationsResponseTypeDef,
+    ListApplicationVersionsResponseTypeDef,
     BatchJobDefinitionTypeDef,
     BatchJobIdentifierTypeDef,
     CreateApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    CreateApplicationResponseTypeDef,
-    CreateDataSetImportTaskResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    GetApplicationVersionResponseTypeDef,
-    GetDeploymentResponseTypeDef,
-    ListApplicationVersionsResponseTypeDef,
-    ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartBatchJobResponseTypeDef,
-    UpdateApplicationResponseTypeDef,
-    UpdateEnvironmentResponseTypeDef,
     DataSetImportTaskTypeDef,
     GetDataSetImportTaskResponseTypeDef,
     ListDataSetsResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEngineVersionsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     StorageConfigurationTypeDef,
     GetApplicationResponseTypeDef,
-    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-    ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-    ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-    ListDataSetsRequestListDataSetsPaginateTypeDef,
-    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    ListEngineVersionsRequestListEngineVersionsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     PendingMaintenanceTypeDef,
     VsamAttributesTypeDef,
     VsamDetailAttributesTypeDef,
     ListBatchJobDefinitionsResponseTypeDef,
     BatchJobExecutionSummaryTypeDef,
     GetBatchJobExecutionResponseTypeDef,
     StartBatchJobRequestRequestTypeDef,
@@ -480,43 +484,43 @@
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/README.md` & `types-aiobotocore-m2-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-m2"></a>
 
 # types-aiobotocore-m2
 
 [![PyPI - types-aiobotocore-m2](https://img.shields.io/pypi/v/types-aiobotocore-m2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-m2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-m2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-m2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-m2?color=blue)](https://pypistats.org/packages/types-aiobotocore-m2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MainframeModernization 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization)
+[aiobotocore.MainframeModernization 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization)
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
 [types-aiobotocore-m2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -338,91 +338,95 @@
     ApplicationVersionSummaryTypeDef,
     FileBatchJobDefinitionTypeDef,
     ScriptBatchJobDefinitionTypeDef,
     FileBatchJobIdentifierTypeDef,
     ScriptBatchJobIdentifierTypeDef,
     CancelBatchJobExecutionRequestRequestTypeDef,
     DefinitionTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationResponseTypeDef,
+    CreateDataSetImportTaskResponseTypeDef,
     CreateDeploymentRequestRequestTypeDef,
+    CreateDeploymentResponseTypeDef,
     HighAvailabilityConfigTypeDef,
+    CreateEnvironmentResponseTypeDef,
     ExternalLocationTypeDef,
     DataSetImportSummaryTypeDef,
     DataSetSummaryTypeDef,
     RecordLengthTypeDef,
     GdgDetailAttributesTypeDef,
+    PoDetailAttributesTypeDef,
+    PsDetailAttributesTypeDef,
     GdgAttributesTypeDef,
+    PoAttributesTypeDef,
+    PsAttributesTypeDef,
     DeleteApplicationFromEnvironmentRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
     DeployedVersionSummaryTypeDef,
     DeploymentSummaryTypeDef,
     EfsStorageConfigurationTypeDef,
     EngineVersionsSummaryTypeDef,
     EnvironmentSummaryTypeDef,
     FsxStorageConfigurationTypeDef,
     GetApplicationRequestRequestTypeDef,
     LogGroupSummaryTypeDef,
     GetApplicationVersionRequestRequestTypeDef,
+    GetApplicationVersionResponseTypeDef,
     GetBatchJobExecutionRequestRequestTypeDef,
     GetDataSetDetailsRequestRequestTypeDef,
     GetDataSetImportTaskRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetDeploymentResponseTypeDef,
     GetEnvironmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
     ListBatchJobDefinitionsRequestRequestTypeDef,
+    ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
     ListBatchJobExecutionsRequestRequestTypeDef,
+    ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
     ListDataSetImportHistoryRequestRequestTypeDef,
+    ListDataSetsRequestListDataSetsPaginateTypeDef,
     ListDataSetsRequestRequestTypeDef,
+    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
     ListDeploymentsRequestRequestTypeDef,
+    ListEngineVersionsRequestListEngineVersionsPaginateTypeDef,
     ListEngineVersionsRequestRequestTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MaintenanceScheduleTypeDef,
+    PaginatorConfigTypeDef,
     PrimaryKeyTypeDef,
+    ResponseMetadataTypeDef,
     StartApplicationRequestRequestTypeDef,
+    StartBatchJobResponseTypeDef,
     StopApplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateApplicationResponseTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
+    UpdateEnvironmentResponseTypeDef,
+    ListApplicationsResponseTypeDef,
+    ListApplicationVersionsResponseTypeDef,
     BatchJobDefinitionTypeDef,
     BatchJobIdentifierTypeDef,
     CreateApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    CreateApplicationResponseTypeDef,
-    CreateDataSetImportTaskResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    GetApplicationVersionResponseTypeDef,
-    GetDeploymentResponseTypeDef,
-    ListApplicationVersionsResponseTypeDef,
-    ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartBatchJobResponseTypeDef,
-    UpdateApplicationResponseTypeDef,
-    UpdateEnvironmentResponseTypeDef,
     DataSetImportTaskTypeDef,
     GetDataSetImportTaskResponseTypeDef,
     ListDataSetsResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEngineVersionsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     StorageConfigurationTypeDef,
     GetApplicationResponseTypeDef,
-    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-    ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-    ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-    ListDataSetsRequestListDataSetsPaginateTypeDef,
-    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    ListEngineVersionsRequestListEngineVersionsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     PendingMaintenanceTypeDef,
     VsamAttributesTypeDef,
     VsamDetailAttributesTypeDef,
     ListBatchJobDefinitionsResponseTypeDef,
     BatchJobExecutionSummaryTypeDef,
     GetBatchJobExecutionResponseTypeDef,
     StartBatchJobRequestRequestTypeDef,
@@ -447,43 +451,43 @@
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/setup.py` & `types-aiobotocore-m2-2.5.1/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-m2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-m2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_m2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MainframeModernization 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MainframeModernization 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/",
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/__init__.py` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/__init__.pyi` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/__main__.py` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MainframeModernization 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MainframeModernization 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2//\nBoto3 docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization\nOther"
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/client.py` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -141,14 +141,15 @@
         *,
         definition: DefinitionTypeDef,
         engineType: EngineTypeType,
         name: str,
         clientToken: str = ...,
         description: str = ...,
         kmsKeyId: str = ...,
+        roleArn: str = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateApplicationResponseTypeDef:
         """
         Creates a new application with given parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Client.create_application)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/client/#create_application)
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/client.pyi` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -133,14 +133,15 @@
         *,
         definition: DefinitionTypeDef,
         engineType: EngineTypeType,
         name: str,
         clientToken: str = ...,
         description: str = ...,
         kmsKeyId: str = ...,
+        roleArn: str = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateApplicationResponseTypeDef:
         """
         Creates a new application with given parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Client.create_application)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/client/#create_application)
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/literals.py` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -145,14 +145,15 @@
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
@@ -231,14 +232,15 @@
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
@@ -249,14 +251,15 @@
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
@@ -292,14 +295,15 @@
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
@@ -318,16 +322,19 @@
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
@@ -411,15 +418,17 @@
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/literals.pyi` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -143,14 +143,15 @@
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
@@ -229,14 +230,15 @@
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
@@ -247,14 +249,15 @@
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
@@ -290,14 +293,15 @@
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
@@ -316,16 +320,19 @@
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
@@ -409,15 +416,17 @@
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/paginator.py` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -32,17 +32,16 @@
         list_data_set_import_history_paginator: ListDataSetImportHistoryPaginator = client.get_paginator("list_data_set_import_history")
         list_data_sets_paginator: ListDataSetsPaginator = client.get_paginator("list_data_sets")
         list_deployments_paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
         list_engine_versions_paginator: ListEngineVersionsPaginator = client.get_paginator("list_engine_versions")
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import BatchJobExecutionStatusType, EngineTypeType
 from .type_defs import (
     ListApplicationsResponseTypeDef,
@@ -53,20 +52,14 @@
     ListDataSetsResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEngineVersionsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationVersionsPaginator",
     "ListApplicationsPaginator",
     "ListBatchJobDefinitionsPaginator",
     "ListBatchJobExecutionsPaginator",
     "ListDataSetImportHistoryPaginator",
     "ListDataSetsPaginator",
@@ -89,15 +82,15 @@
 class ListApplicationVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListApplicationVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listapplicationversionspaginator)
     """
 
     def paginate(
-        self, *, applicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListApplicationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listapplicationversionspaginator)
         """
 
 
@@ -108,15 +101,15 @@
     """
 
     def paginate(
         self,
         *,
         environmentId: str = ...,
         names: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listapplicationspaginator)
         """
 
 
@@ -127,15 +120,15 @@
     """
 
     def paginate(
         self,
         *,
         applicationId: str,
         prefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchJobDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListBatchJobDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listbatchjobdefinitionspaginator)
         """
 
 
@@ -150,30 +143,30 @@
         *,
         applicationId: str,
         executionIds: Sequence[str] = ...,
         jobName: str = ...,
         startedAfter: Union[datetime, str] = ...,
         startedBefore: Union[datetime, str] = ...,
         status: BatchJobExecutionStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchJobExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListBatchJobExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listbatchjobexecutionspaginator)
         """
 
 
 class ListDataSetImportHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDataSetImportHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdatasetimporthistorypaginator)
     """
 
     def paginate(
-        self, *, applicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetImportHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDataSetImportHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdatasetimporthistorypaginator)
         """
 
 
@@ -184,45 +177,45 @@
     """
 
     def paginate(
         self,
         *,
         applicationId: str,
         prefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDataSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdatasetspaginator)
         """
 
 
 class ListDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdeploymentspaginator)
     """
 
     def paginate(
-        self, *, applicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdeploymentspaginator)
         """
 
 
 class ListEngineVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListEngineVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listengineversionspaginator)
     """
 
     def paginate(
-        self, *, engineType: EngineTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, engineType: EngineTypeType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEngineVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listengineversionspaginator)
         """
 
 
@@ -233,13 +226,13 @@
     """
 
     def paginate(
         self,
         *,
         engineType: EngineTypeType = ...,
         names: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listenvironmentspaginator)
         """
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/paginator.pyi` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -32,17 +32,16 @@
         list_data_set_import_history_paginator: ListDataSetImportHistoryPaginator = client.get_paginator("list_data_set_import_history")
         list_data_sets_paginator: ListDataSetsPaginator = client.get_paginator("list_data_sets")
         list_deployments_paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
         list_engine_versions_paginator: ListEngineVersionsPaginator = client.get_paginator("list_engine_versions")
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import BatchJobExecutionStatusType, EngineTypeType
 from .type_defs import (
     ListApplicationsResponseTypeDef,
@@ -53,19 +52,14 @@
     ListDataSetsResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEngineVersionsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationVersionsPaginator",
     "ListApplicationsPaginator",
     "ListBatchJobDefinitionsPaginator",
     "ListBatchJobExecutionsPaginator",
     "ListDataSetImportHistoryPaginator",
     "ListDataSetsPaginator",
@@ -85,15 +79,15 @@
 class ListApplicationVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListApplicationVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listapplicationversionspaginator)
     """
 
     def paginate(
-        self, *, applicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListApplicationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listapplicationversionspaginator)
         """
 
 class ListApplicationsPaginator(AioPaginator):
@@ -103,15 +97,15 @@
     """
 
     def paginate(
         self,
         *,
         environmentId: str = ...,
         names: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listapplicationspaginator)
         """
 
 class ListBatchJobDefinitionsPaginator(AioPaginator):
@@ -121,15 +115,15 @@
     """
 
     def paginate(
         self,
         *,
         applicationId: str,
         prefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchJobDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListBatchJobDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listbatchjobdefinitionspaginator)
         """
 
 class ListBatchJobExecutionsPaginator(AioPaginator):
@@ -143,29 +137,29 @@
         *,
         applicationId: str,
         executionIds: Sequence[str] = ...,
         jobName: str = ...,
         startedAfter: Union[datetime, str] = ...,
         startedBefore: Union[datetime, str] = ...,
         status: BatchJobExecutionStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchJobExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListBatchJobExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listbatchjobexecutionspaginator)
         """
 
 class ListDataSetImportHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDataSetImportHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdatasetimporthistorypaginator)
     """
 
     def paginate(
-        self, *, applicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetImportHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDataSetImportHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdatasetimporthistorypaginator)
         """
 
 class ListDataSetsPaginator(AioPaginator):
@@ -175,43 +169,43 @@
     """
 
     def paginate(
         self,
         *,
         applicationId: str,
         prefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDataSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdatasetspaginator)
         """
 
 class ListDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdeploymentspaginator)
     """
 
     def paginate(
-        self, *, applicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listdeploymentspaginator)
         """
 
 class ListEngineVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListEngineVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listengineversionspaginator)
     """
 
     def paginate(
-        self, *, engineType: EngineTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, engineType: EngineTypeType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEngineVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listengineversionspaginator)
         """
 
 class ListEnvironmentsPaginator(AioPaginator):
@@ -221,13 +215,13 @@
     """
 
     def paginate(
         self,
         *,
         engineType: EngineTypeType = ...,
         names: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/paginators/#listenvironmentspaginator)
         """
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/type_defs.py` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -39,91 +39,95 @@
     "ApplicationVersionSummaryTypeDef",
     "FileBatchJobDefinitionTypeDef",
     "ScriptBatchJobDefinitionTypeDef",
     "FileBatchJobIdentifierTypeDef",
     "ScriptBatchJobIdentifierTypeDef",
     "CancelBatchJobExecutionRequestRequestTypeDef",
     "DefinitionTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApplicationResponseTypeDef",
+    "CreateDataSetImportTaskResponseTypeDef",
     "CreateDeploymentRequestRequestTypeDef",
+    "CreateDeploymentResponseTypeDef",
     "HighAvailabilityConfigTypeDef",
+    "CreateEnvironmentResponseTypeDef",
     "ExternalLocationTypeDef",
     "DataSetImportSummaryTypeDef",
     "DataSetSummaryTypeDef",
     "RecordLengthTypeDef",
     "GdgDetailAttributesTypeDef",
+    "PoDetailAttributesTypeDef",
+    "PsDetailAttributesTypeDef",
     "GdgAttributesTypeDef",
+    "PoAttributesTypeDef",
+    "PsAttributesTypeDef",
     "DeleteApplicationFromEnvironmentRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
     "DeployedVersionSummaryTypeDef",
     "DeploymentSummaryTypeDef",
     "EfsStorageConfigurationTypeDef",
     "EngineVersionsSummaryTypeDef",
     "EnvironmentSummaryTypeDef",
     "FsxStorageConfigurationTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "LogGroupSummaryTypeDef",
     "GetApplicationVersionRequestRequestTypeDef",
+    "GetApplicationVersionResponseTypeDef",
     "GetBatchJobExecutionRequestRequestTypeDef",
     "GetDataSetDetailsRequestRequestTypeDef",
     "GetDataSetImportTaskRequestRequestTypeDef",
     "GetDeploymentRequestRequestTypeDef",
+    "GetDeploymentResponseTypeDef",
     "GetEnvironmentRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
     "ListApplicationVersionsRequestRequestTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
     "ListBatchJobDefinitionsRequestRequestTypeDef",
+    "ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
     "ListBatchJobExecutionsRequestRequestTypeDef",
+    "ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
     "ListDataSetImportHistoryRequestRequestTypeDef",
+    "ListDataSetsRequestListDataSetsPaginateTypeDef",
     "ListDataSetsRequestRequestTypeDef",
+    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
     "ListDeploymentsRequestRequestTypeDef",
+    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
     "ListEngineVersionsRequestRequestTypeDef",
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MaintenanceScheduleTypeDef",
+    "PaginatorConfigTypeDef",
     "PrimaryKeyTypeDef",
+    "ResponseMetadataTypeDef",
     "StartApplicationRequestRequestTypeDef",
+    "StartBatchJobResponseTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateApplicationResponseTypeDef",
     "UpdateEnvironmentRequestRequestTypeDef",
+    "UpdateEnvironmentResponseTypeDef",
+    "ListApplicationsResponseTypeDef",
+    "ListApplicationVersionsResponseTypeDef",
     "BatchJobDefinitionTypeDef",
     "BatchJobIdentifierTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "CreateDataSetImportTaskResponseTypeDef",
-    "CreateDeploymentResponseTypeDef",
-    "CreateEnvironmentResponseTypeDef",
-    "GetApplicationVersionResponseTypeDef",
-    "GetDeploymentResponseTypeDef",
-    "ListApplicationVersionsResponseTypeDef",
-    "ListApplicationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartBatchJobResponseTypeDef",
-    "UpdateApplicationResponseTypeDef",
-    "UpdateEnvironmentResponseTypeDef",
     "DataSetImportTaskTypeDef",
     "GetDataSetImportTaskResponseTypeDef",
     "ListDataSetsResponseTypeDef",
     "ListDeploymentsResponseTypeDef",
     "ListEngineVersionsResponseTypeDef",
     "ListEnvironmentsResponseTypeDef",
     "StorageConfigurationTypeDef",
     "GetApplicationResponseTypeDef",
-    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
-    "ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
-    "ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
-    "ListDataSetsRequestListDataSetsPaginateTypeDef",
-    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "PendingMaintenanceTypeDef",
     "VsamAttributesTypeDef",
     "VsamDetailAttributesTypeDef",
     "ListBatchJobDefinitionsResponseTypeDef",
     "BatchJobExecutionSummaryTypeDef",
     "GetBatchJobExecutionResponseTypeDef",
     "StartBatchJobRequestRequestTypeDef",
@@ -176,14 +180,15 @@
 _OptionalApplicationSummaryTypeDef = TypedDict(
     "_OptionalApplicationSummaryTypeDef",
     {
         "deploymentStatus": ApplicationDeploymentLifecycleType,
         "description": str,
         "environmentId": str,
         "lastStartTime": datetime,
+        "roleArn": str,
         "versionStatus": ApplicationVersionLifecycleType,
     },
     total=False,
 )
 
 
 class ApplicationSummaryTypeDef(
@@ -284,22 +289,29 @@
     {
         "content": str,
         "s3Location": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationArn": str,
+        "applicationId": str,
+        "applicationVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDataSetImportTaskResponseTypeDef = TypedDict(
+    "CreateDataSetImportTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentRequestRequestTypeDef",
     {
         "applicationId": str,
@@ -318,21 +330,37 @@
 
 class CreateDeploymentRequestRequestTypeDef(
     _RequiredCreateDeploymentRequestRequestTypeDef, _OptionalCreateDeploymentRequestRequestTypeDef
 ):
     pass
 
 
+CreateDeploymentResponseTypeDef = TypedDict(
+    "CreateDeploymentResponseTypeDef",
+    {
+        "deploymentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HighAvailabilityConfigTypeDef = TypedDict(
     "HighAvailabilityConfigTypeDef",
     {
         "desiredCapacity": int,
     },
 )
 
+CreateEnvironmentResponseTypeDef = TypedDict(
+    "CreateEnvironmentResponseTypeDef",
+    {
+        "environmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExternalLocationTypeDef = TypedDict(
     "ExternalLocationTypeDef",
     {
         "s3Location": str,
     },
     total=False,
 )
@@ -384,23 +412,78 @@
     {
         "limit": int,
         "rollDisposition": str,
     },
     total=False,
 )
 
+PoDetailAttributesTypeDef = TypedDict(
+    "PoDetailAttributesTypeDef",
+    {
+        "encoding": str,
+        "format": str,
+    },
+)
+
+PsDetailAttributesTypeDef = TypedDict(
+    "PsDetailAttributesTypeDef",
+    {
+        "encoding": str,
+        "format": str,
+    },
+)
+
 GdgAttributesTypeDef = TypedDict(
     "GdgAttributesTypeDef",
     {
         "limit": int,
         "rollDisposition": str,
     },
     total=False,
 )
 
+_RequiredPoAttributesTypeDef = TypedDict(
+    "_RequiredPoAttributesTypeDef",
+    {
+        "format": str,
+        "memberFileExtensions": Sequence[str],
+    },
+)
+_OptionalPoAttributesTypeDef = TypedDict(
+    "_OptionalPoAttributesTypeDef",
+    {
+        "encoding": str,
+    },
+    total=False,
+)
+
+
+class PoAttributesTypeDef(_RequiredPoAttributesTypeDef, _OptionalPoAttributesTypeDef):
+    pass
+
+
+_RequiredPsAttributesTypeDef = TypedDict(
+    "_RequiredPsAttributesTypeDef",
+    {
+        "format": str,
+    },
+)
+_OptionalPsAttributesTypeDef = TypedDict(
+    "_OptionalPsAttributesTypeDef",
+    {
+        "encoding": str,
+    },
+    total=False,
+)
+
+
+class PsAttributesTypeDef(_RequiredPsAttributesTypeDef, _OptionalPsAttributesTypeDef):
+    pass
+
+
 DeleteApplicationFromEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteApplicationFromEnvironmentRequestRequestTypeDef",
     {
         "applicationId": str,
         "environmentId": str,
     },
 )
@@ -524,14 +607,28 @@
     "GetApplicationVersionRequestRequestTypeDef",
     {
         "applicationId": str,
         "applicationVersion": int,
     },
 )
 
+GetApplicationVersionResponseTypeDef = TypedDict(
+    "GetApplicationVersionResponseTypeDef",
+    {
+        "applicationVersion": int,
+        "creationTime": datetime,
+        "definitionContent": str,
+        "description": str,
+        "name": str,
+        "status": ApplicationVersionLifecycleType,
+        "statusReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBatchJobExecutionRequestRequestTypeDef = TypedDict(
     "GetBatchJobExecutionRequestRequestTypeDef",
     {
         "applicationId": str,
         "executionId": str,
     },
 )
@@ -556,31 +653,57 @@
     "GetDeploymentRequestRequestTypeDef",
     {
         "applicationId": str,
         "deploymentId": str,
     },
 )
 
+GetDeploymentResponseTypeDef = TypedDict(
+    "GetDeploymentResponseTypeDef",
+    {
+        "applicationId": str,
+        "applicationVersion": int,
+        "creationTime": datetime,
+        "deploymentId": str,
+        "environmentId": str,
+        "status": DeploymentLifecycleType,
+        "statusReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEnvironmentRequestRequestTypeDef = TypedDict(
     "GetEnvironmentRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "applicationId": str,
+    },
+)
+_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
+    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApplicationVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationVersionsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListApplicationVersionsRequestRequestTypeDef = TypedDict(
@@ -596,25 +719,58 @@
 class ListApplicationVersionsRequestRequestTypeDef(
     _RequiredListApplicationVersionsRequestRequestTypeDef,
     _OptionalListApplicationVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "environmentId": str,
+        "names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "environmentId": str,
         "maxResults": int,
         "names": Sequence[str],
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
+    "_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
+    "_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
+    {
+        "prefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef(
+    _RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
+    _OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListBatchJobDefinitionsRequestRequestTypeDef = TypedDict(
     "_RequiredListBatchJobDefinitionsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListBatchJobDefinitionsRequestRequestTypeDef = TypedDict(
@@ -631,14 +787,41 @@
 class ListBatchJobDefinitionsRequestRequestTypeDef(
     _RequiredListBatchJobDefinitionsRequestRequestTypeDef,
     _OptionalListBatchJobDefinitionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
+    {
+        "executionIds": Sequence[str],
+        "jobName": str,
+        "startedAfter": Union[datetime, str],
+        "startedBefore": Union[datetime, str],
+        "status": BatchJobExecutionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef(
+    _RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
+    _OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListBatchJobExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredListBatchJobExecutionsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListBatchJobExecutionsRequestRequestTypeDef = TypedDict(
@@ -659,14 +842,36 @@
 class ListBatchJobExecutionsRequestRequestTypeDef(
     _RequiredListBatchJobExecutionsRequestRequestTypeDef,
     _OptionalListBatchJobExecutionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
+    "_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
+    "_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef(
+    _RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
+    _OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDataSetImportHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSetImportHistoryRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListDataSetImportHistoryRequestRequestTypeDef = TypedDict(
@@ -682,14 +887,37 @@
 class ListDataSetImportHistoryRequestRequestTypeDef(
     _RequiredListDataSetImportHistoryRequestRequestTypeDef,
     _OptionalListDataSetImportHistoryRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
+    "_RequiredListDataSetsRequestListDataSetsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
+    "_OptionalListDataSetsRequestListDataSetsPaginateTypeDef",
+    {
+        "prefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDataSetsRequestListDataSetsPaginateTypeDef(
+    _RequiredListDataSetsRequestListDataSetsPaginateTypeDef,
+    _OptionalListDataSetsRequestListDataSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDataSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSetsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListDataSetsRequestRequestTypeDef = TypedDict(
@@ -705,14 +933,36 @@
 
 class ListDataSetsRequestRequestTypeDef(
     _RequiredListDataSetsRequestRequestTypeDef, _OptionalListDataSetsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDeploymentsRequestListDeploymentsPaginateTypeDef(
+    _RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef,
+    _OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredListDeploymentsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListDeploymentsRequestRequestTypeDef = TypedDict(
@@ -727,24 +977,43 @@
 
 class ListDeploymentsRequestRequestTypeDef(
     _RequiredListDeploymentsRequestRequestTypeDef, _OptionalListDeploymentsRequestRequestTypeDef
 ):
     pass
 
 
+ListEngineVersionsRequestListEngineVersionsPaginateTypeDef = TypedDict(
+    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
+    {
+        "engineType": EngineTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEngineVersionsRequestRequestTypeDef = TypedDict(
     "ListEngineVersionsRequestRequestTypeDef",
     {
         "engineType": EngineTypeType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
+    {
+        "engineType": EngineTypeType,
+        "names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentsRequestRequestTypeDef = TypedDict(
     "ListEnvironmentsRequestRequestTypeDef",
     {
         "engineType": EngineTypeType,
         "maxResults": int,
         "names": Sequence[str],
         "nextToken": str,
@@ -755,23 +1024,41 @@
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
 MaintenanceScheduleTypeDef = TypedDict(
     "MaintenanceScheduleTypeDef",
     {
         "endTime": datetime,
         "startTime": datetime,
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
 _RequiredPrimaryKeyTypeDef = TypedDict(
     "_RequiredPrimaryKeyTypeDef",
     {
         "length": int,
         "offset": int,
     },
 )
@@ -784,21 +1071,40 @@
 )
 
 
 class PrimaryKeyTypeDef(_RequiredPrimaryKeyTypeDef, _OptionalPrimaryKeyTypeDef):
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
 StartApplicationRequestRequestTypeDef = TypedDict(
     "StartApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
+StartBatchJobResponseTypeDef = TypedDict(
+    "StartBatchJobResponseTypeDef",
+    {
+        "executionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredStopApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalStopApplicationRequestRequestTypeDef = TypedDict(
@@ -828,14 +1134,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateApplicationResponseTypeDef = TypedDict(
+    "UpdateApplicationResponseTypeDef",
+    {
+        "applicationVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEnvironmentRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 _OptionalUpdateEnvironmentRequestRequestTypeDef = TypedDict(
@@ -853,14 +1167,40 @@
 
 class UpdateEnvironmentRequestRequestTypeDef(
     _RequiredUpdateEnvironmentRequestRequestTypeDef, _OptionalUpdateEnvironmentRequestRequestTypeDef
 ):
     pass
 
 
+UpdateEnvironmentResponseTypeDef = TypedDict(
+    "UpdateEnvironmentResponseTypeDef",
+    {
+        "environmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationsResponseTypeDef = TypedDict(
+    "ListApplicationsResponseTypeDef",
+    {
+        "applications": List[ApplicationSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationVersionsResponseTypeDef = TypedDict(
+    "ListApplicationVersionsResponseTypeDef",
+    {
+        "applicationVersions": List[ApplicationVersionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchJobDefinitionTypeDef = TypedDict(
     "BatchJobDefinitionTypeDef",
     {
         "fileBatchJobDefinition": FileBatchJobDefinitionTypeDef,
         "scriptBatchJobDefinition": ScriptBatchJobDefinitionTypeDef,
     },
     total=False,
@@ -885,14 +1225,15 @@
 )
 _OptionalCreateApplicationRequestRequestTypeDef = TypedDict(
     "_OptionalCreateApplicationRequestRequestTypeDef",
     {
         "clientToken": str,
         "description": str,
         "kmsKeyId": str,
+        "roleArn": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateApplicationRequestRequestTypeDef(
@@ -920,126 +1261,14 @@
 
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
 
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "applicationArn": str,
-        "applicationId": str,
-        "applicationVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSetImportTaskResponseTypeDef = TypedDict(
-    "CreateDataSetImportTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResponseTypeDef = TypedDict(
-    "CreateDeploymentResponseTypeDef",
-    {
-        "deploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEnvironmentResponseTypeDef = TypedDict(
-    "CreateEnvironmentResponseTypeDef",
-    {
-        "environmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApplicationVersionResponseTypeDef = TypedDict(
-    "GetApplicationVersionResponseTypeDef",
-    {
-        "applicationVersion": int,
-        "creationTime": datetime,
-        "definitionContent": str,
-        "description": str,
-        "name": str,
-        "status": ApplicationVersionLifecycleType,
-        "statusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeploymentResponseTypeDef = TypedDict(
-    "GetDeploymentResponseTypeDef",
-    {
-        "applicationId": str,
-        "applicationVersion": int,
-        "creationTime": datetime,
-        "deploymentId": str,
-        "environmentId": str,
-        "status": DeploymentLifecycleType,
-        "statusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationVersionsResponseTypeDef = TypedDict(
-    "ListApplicationVersionsResponseTypeDef",
-    {
-        "applicationVersions": List[ApplicationVersionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsResponseTypeDef = TypedDict(
-    "ListApplicationsResponseTypeDef",
-    {
-        "applications": List[ApplicationSummaryTypeDef],
-        "nextToken": str,
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
-StartBatchJobResponseTypeDef = TypedDict(
-    "StartBatchJobResponseTypeDef",
-    {
-        "executionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateApplicationResponseTypeDef = TypedDict(
-    "UpdateApplicationResponseTypeDef",
-    {
-        "applicationVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateEnvironmentResponseTypeDef = TypedDict(
-    "UpdateEnvironmentResponseTypeDef",
-    {
-        "environmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DataSetImportTaskTypeDef = TypedDict(
     "DataSetImportTaskTypeDef",
     {
         "status": DataSetTaskLifecycleType,
         "summary": DataSetImportSummaryTypeDef,
         "taskId": str,
     },
@@ -1047,51 +1276,51 @@
 
 GetDataSetImportTaskResponseTypeDef = TypedDict(
     "GetDataSetImportTaskResponseTypeDef",
     {
         "status": DataSetTaskLifecycleType,
         "summary": DataSetImportSummaryTypeDef,
         "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataSetsResponseTypeDef = TypedDict(
     "ListDataSetsResponseTypeDef",
     {
         "dataSets": List[DataSetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeploymentsResponseTypeDef = TypedDict(
     "ListDeploymentsResponseTypeDef",
     {
         "deployments": List[DeploymentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEngineVersionsResponseTypeDef = TypedDict(
     "ListEngineVersionsResponseTypeDef",
     {
         "engineVersions": List[EngineVersionsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentsResponseTypeDef = TypedDict(
     "ListEnvironmentsResponseTypeDef",
     {
         "environments": List[EnvironmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StorageConfigurationTypeDef = TypedDict(
     "StorageConfigurationTypeDef",
     {
         "efs": EfsStorageConfigurationTypeDef,
@@ -1114,189 +1343,22 @@
         "lastStartTime": datetime,
         "latestVersion": ApplicationVersionSummaryTypeDef,
         "listenerArns": List[str],
         "listenerPorts": List[int],
         "loadBalancerDnsName": str,
         "logGroups": List[LogGroupSummaryTypeDef],
         "name": str,
+        "roleArn": str,
         "status": ApplicationLifecycleType,
         "statusReason": str,
         "tags": Dict[str, str],
         "targetGroupArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
-    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "environmentId": str,
-        "names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
-    "_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
-    {
-        "applicationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
-    "_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
-    {
-        "prefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef(
-    _RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-    _OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
-    {
-        "executionIds": Sequence[str],
-        "jobName": str,
-        "startedAfter": Union[datetime, str],
-        "startedBefore": Union[datetime, str],
-        "status": BatchJobExecutionStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef(
-    _RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-    _OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
-    "_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
-    "_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef(
-    _RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-    _OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
-    "_RequiredListDataSetsRequestListDataSetsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
-    "_OptionalListDataSetsRequestListDataSetsPaginateTypeDef",
-    {
-        "prefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDataSetsRequestListDataSetsPaginateTypeDef(
-    _RequiredListDataSetsRequestListDataSetsPaginateTypeDef,
-    _OptionalListDataSetsRequestListDataSetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDeploymentsRequestListDeploymentsPaginateTypeDef(
-    _RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    _OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef,
-):
-    pass
-
-
-ListEngineVersionsRequestListEngineVersionsPaginateTypeDef = TypedDict(
-    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
-    {
-        "engineType": EngineTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    {
-        "engineType": EngineTypeType,
-        "names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 PendingMaintenanceTypeDef = TypedDict(
     "PendingMaintenanceTypeDef",
     {
         "engineVersion": str,
         "schedule": MaintenanceScheduleTypeDef,
     },
@@ -1339,15 +1401,15 @@
 )
 
 ListBatchJobDefinitionsResponseTypeDef = TypedDict(
     "ListBatchJobDefinitionsResponseTypeDef",
     {
         "batchJobDefinitions": List[BatchJobDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchJobExecutionSummaryTypeDef = TypedDict(
     "_RequiredBatchJobExecutionSummaryTypeDef",
     {
         "applicationId": str,
@@ -1387,15 +1449,15 @@
         "jobName": str,
         "jobType": BatchJobTypeType,
         "jobUser": str,
         "returnCode": str,
         "startTime": datetime,
         "status": BatchJobExecutionStatusType,
         "statusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartBatchJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartBatchJobRequestRequestTypeDef",
     {
         "applicationId": str,
@@ -1418,15 +1480,15 @@
 
 
 ListDataSetImportHistoryResponseTypeDef = TypedDict(
     "ListDataSetImportHistoryResponseTypeDef",
     {
         "dataSetImportTasks": List[DataSetImportTaskTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentRequestRequestTypeDef",
     {
         "engineType": EngineTypeType,
@@ -1480,42 +1542,46 @@
         "securityGroupIds": List[str],
         "status": EnvironmentLifecycleType,
         "statusReason": str,
         "storageConfigurations": List[StorageConfigurationTypeDef],
         "subnetIds": List[str],
         "tags": Dict[str, str],
         "vpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetOrgAttributesTypeDef = TypedDict(
     "DatasetOrgAttributesTypeDef",
     {
         "gdg": GdgAttributesTypeDef,
+        "po": PoAttributesTypeDef,
+        "ps": PsAttributesTypeDef,
         "vsam": VsamAttributesTypeDef,
     },
     total=False,
 )
 
 DatasetDetailOrgAttributesTypeDef = TypedDict(
     "DatasetDetailOrgAttributesTypeDef",
     {
         "gdg": GdgDetailAttributesTypeDef,
+        "po": PoDetailAttributesTypeDef,
+        "ps": PsDetailAttributesTypeDef,
         "vsam": VsamDetailAttributesTypeDef,
     },
     total=False,
 )
 
 ListBatchJobExecutionsResponseTypeDef = TypedDict(
     "ListBatchJobExecutionsResponseTypeDef",
     {
         "batchJobExecutions": List[BatchJobExecutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDataSetTypeDef = TypedDict(
     "_RequiredDataSetTypeDef",
     {
         "datasetName": str,
@@ -1544,15 +1610,15 @@
         "creationTime": datetime,
         "dataSetName": str,
         "dataSetOrg": DatasetDetailOrgAttributesTypeDef,
         "lastReferencedTime": datetime,
         "lastUpdatedTime": datetime,
         "location": str,
         "recordLength": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSetImportItemTypeDef = TypedDict(
     "DataSetImportItemTypeDef",
     {
         "dataSet": DataSetTypeDef,
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2/type_defs.pyi` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -38,91 +38,95 @@
     "ApplicationVersionSummaryTypeDef",
     "FileBatchJobDefinitionTypeDef",
     "ScriptBatchJobDefinitionTypeDef",
     "FileBatchJobIdentifierTypeDef",
     "ScriptBatchJobIdentifierTypeDef",
     "CancelBatchJobExecutionRequestRequestTypeDef",
     "DefinitionTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApplicationResponseTypeDef",
+    "CreateDataSetImportTaskResponseTypeDef",
     "CreateDeploymentRequestRequestTypeDef",
+    "CreateDeploymentResponseTypeDef",
     "HighAvailabilityConfigTypeDef",
+    "CreateEnvironmentResponseTypeDef",
     "ExternalLocationTypeDef",
     "DataSetImportSummaryTypeDef",
     "DataSetSummaryTypeDef",
     "RecordLengthTypeDef",
     "GdgDetailAttributesTypeDef",
+    "PoDetailAttributesTypeDef",
+    "PsDetailAttributesTypeDef",
     "GdgAttributesTypeDef",
+    "PoAttributesTypeDef",
+    "PsAttributesTypeDef",
     "DeleteApplicationFromEnvironmentRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
     "DeployedVersionSummaryTypeDef",
     "DeploymentSummaryTypeDef",
     "EfsStorageConfigurationTypeDef",
     "EngineVersionsSummaryTypeDef",
     "EnvironmentSummaryTypeDef",
     "FsxStorageConfigurationTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "LogGroupSummaryTypeDef",
     "GetApplicationVersionRequestRequestTypeDef",
+    "GetApplicationVersionResponseTypeDef",
     "GetBatchJobExecutionRequestRequestTypeDef",
     "GetDataSetDetailsRequestRequestTypeDef",
     "GetDataSetImportTaskRequestRequestTypeDef",
     "GetDeploymentRequestRequestTypeDef",
+    "GetDeploymentResponseTypeDef",
     "GetEnvironmentRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
     "ListApplicationVersionsRequestRequestTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
     "ListBatchJobDefinitionsRequestRequestTypeDef",
+    "ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
     "ListBatchJobExecutionsRequestRequestTypeDef",
+    "ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
     "ListDataSetImportHistoryRequestRequestTypeDef",
+    "ListDataSetsRequestListDataSetsPaginateTypeDef",
     "ListDataSetsRequestRequestTypeDef",
+    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
     "ListDeploymentsRequestRequestTypeDef",
+    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
     "ListEngineVersionsRequestRequestTypeDef",
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MaintenanceScheduleTypeDef",
+    "PaginatorConfigTypeDef",
     "PrimaryKeyTypeDef",
+    "ResponseMetadataTypeDef",
     "StartApplicationRequestRequestTypeDef",
+    "StartBatchJobResponseTypeDef",
     "StopApplicationRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateApplicationResponseTypeDef",
     "UpdateEnvironmentRequestRequestTypeDef",
+    "UpdateEnvironmentResponseTypeDef",
+    "ListApplicationsResponseTypeDef",
+    "ListApplicationVersionsResponseTypeDef",
     "BatchJobDefinitionTypeDef",
     "BatchJobIdentifierTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "CreateApplicationResponseTypeDef",
-    "CreateDataSetImportTaskResponseTypeDef",
-    "CreateDeploymentResponseTypeDef",
-    "CreateEnvironmentResponseTypeDef",
-    "GetApplicationVersionResponseTypeDef",
-    "GetDeploymentResponseTypeDef",
-    "ListApplicationVersionsResponseTypeDef",
-    "ListApplicationsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartBatchJobResponseTypeDef",
-    "UpdateApplicationResponseTypeDef",
-    "UpdateEnvironmentResponseTypeDef",
     "DataSetImportTaskTypeDef",
     "GetDataSetImportTaskResponseTypeDef",
     "ListDataSetsResponseTypeDef",
     "ListDeploymentsResponseTypeDef",
     "ListEngineVersionsResponseTypeDef",
     "ListEnvironmentsResponseTypeDef",
     "StorageConfigurationTypeDef",
     "GetApplicationResponseTypeDef",
-    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    "ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
-    "ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
-    "ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
-    "ListDataSetsRequestListDataSetsPaginateTypeDef",
-    "ListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "PendingMaintenanceTypeDef",
     "VsamAttributesTypeDef",
     "VsamDetailAttributesTypeDef",
     "ListBatchJobDefinitionsResponseTypeDef",
     "BatchJobExecutionSummaryTypeDef",
     "GetBatchJobExecutionResponseTypeDef",
     "StartBatchJobRequestRequestTypeDef",
@@ -173,14 +177,15 @@
 _OptionalApplicationSummaryTypeDef = TypedDict(
     "_OptionalApplicationSummaryTypeDef",
     {
         "deploymentStatus": ApplicationDeploymentLifecycleType,
         "description": str,
         "environmentId": str,
         "lastStartTime": datetime,
+        "roleArn": str,
         "versionStatus": ApplicationVersionLifecycleType,
     },
     total=False,
 )
 
 class ApplicationSummaryTypeDef(
     _RequiredApplicationSummaryTypeDef, _OptionalApplicationSummaryTypeDef
@@ -273,22 +278,29 @@
     {
         "content": str,
         "s3Location": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApplicationResponseTypeDef = TypedDict(
+    "CreateApplicationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "applicationArn": str,
+        "applicationId": str,
+        "applicationVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDataSetImportTaskResponseTypeDef = TypedDict(
+    "CreateDataSetImportTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentRequestRequestTypeDef",
     {
         "applicationId": str,
@@ -305,21 +317,37 @@
 )
 
 class CreateDeploymentRequestRequestTypeDef(
     _RequiredCreateDeploymentRequestRequestTypeDef, _OptionalCreateDeploymentRequestRequestTypeDef
 ):
     pass
 
+CreateDeploymentResponseTypeDef = TypedDict(
+    "CreateDeploymentResponseTypeDef",
+    {
+        "deploymentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HighAvailabilityConfigTypeDef = TypedDict(
     "HighAvailabilityConfigTypeDef",
     {
         "desiredCapacity": int,
     },
 )
 
+CreateEnvironmentResponseTypeDef = TypedDict(
+    "CreateEnvironmentResponseTypeDef",
+    {
+        "environmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExternalLocationTypeDef = TypedDict(
     "ExternalLocationTypeDef",
     {
         "s3Location": str,
     },
     total=False,
 )
@@ -369,23 +397,74 @@
     {
         "limit": int,
         "rollDisposition": str,
     },
     total=False,
 )
 
+PoDetailAttributesTypeDef = TypedDict(
+    "PoDetailAttributesTypeDef",
+    {
+        "encoding": str,
+        "format": str,
+    },
+)
+
+PsDetailAttributesTypeDef = TypedDict(
+    "PsDetailAttributesTypeDef",
+    {
+        "encoding": str,
+        "format": str,
+    },
+)
+
 GdgAttributesTypeDef = TypedDict(
     "GdgAttributesTypeDef",
     {
         "limit": int,
         "rollDisposition": str,
     },
     total=False,
 )
 
+_RequiredPoAttributesTypeDef = TypedDict(
+    "_RequiredPoAttributesTypeDef",
+    {
+        "format": str,
+        "memberFileExtensions": Sequence[str],
+    },
+)
+_OptionalPoAttributesTypeDef = TypedDict(
+    "_OptionalPoAttributesTypeDef",
+    {
+        "encoding": str,
+    },
+    total=False,
+)
+
+class PoAttributesTypeDef(_RequiredPoAttributesTypeDef, _OptionalPoAttributesTypeDef):
+    pass
+
+_RequiredPsAttributesTypeDef = TypedDict(
+    "_RequiredPsAttributesTypeDef",
+    {
+        "format": str,
+    },
+)
+_OptionalPsAttributesTypeDef = TypedDict(
+    "_OptionalPsAttributesTypeDef",
+    {
+        "encoding": str,
+    },
+    total=False,
+)
+
+class PsAttributesTypeDef(_RequiredPsAttributesTypeDef, _OptionalPsAttributesTypeDef):
+    pass
+
 DeleteApplicationFromEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteApplicationFromEnvironmentRequestRequestTypeDef",
     {
         "applicationId": str,
         "environmentId": str,
     },
 )
@@ -505,14 +584,28 @@
     "GetApplicationVersionRequestRequestTypeDef",
     {
         "applicationId": str,
         "applicationVersion": int,
     },
 )
 
+GetApplicationVersionResponseTypeDef = TypedDict(
+    "GetApplicationVersionResponseTypeDef",
+    {
+        "applicationVersion": int,
+        "creationTime": datetime,
+        "definitionContent": str,
+        "description": str,
+        "name": str,
+        "status": ApplicationVersionLifecycleType,
+        "statusReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBatchJobExecutionRequestRequestTypeDef = TypedDict(
     "GetBatchJobExecutionRequestRequestTypeDef",
     {
         "applicationId": str,
         "executionId": str,
     },
 )
@@ -537,31 +630,55 @@
     "GetDeploymentRequestRequestTypeDef",
     {
         "applicationId": str,
         "deploymentId": str,
     },
 )
 
+GetDeploymentResponseTypeDef = TypedDict(
+    "GetDeploymentResponseTypeDef",
+    {
+        "applicationId": str,
+        "applicationVersion": int,
+        "creationTime": datetime,
+        "deploymentId": str,
+        "environmentId": str,
+        "status": DeploymentLifecycleType,
+        "statusReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEnvironmentRequestRequestTypeDef = TypedDict(
     "GetEnvironmentRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "applicationId": str,
+    },
+)
+_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
+    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListApplicationVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationVersionsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListApplicationVersionsRequestRequestTypeDef = TypedDict(
@@ -575,25 +692,56 @@
 
 class ListApplicationVersionsRequestRequestTypeDef(
     _RequiredListApplicationVersionsRequestRequestTypeDef,
     _OptionalListApplicationVersionsRequestRequestTypeDef,
 ):
     pass
 
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "environmentId": str,
+        "names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "environmentId": str,
         "maxResults": int,
         "names": Sequence[str],
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
+    "_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
+    "_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
+    {
+        "prefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef(
+    _RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
+    _OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListBatchJobDefinitionsRequestRequestTypeDef = TypedDict(
     "_RequiredListBatchJobDefinitionsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListBatchJobDefinitionsRequestRequestTypeDef = TypedDict(
@@ -608,14 +756,39 @@
 
 class ListBatchJobDefinitionsRequestRequestTypeDef(
     _RequiredListBatchJobDefinitionsRequestRequestTypeDef,
     _OptionalListBatchJobDefinitionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
+    {
+        "executionIds": Sequence[str],
+        "jobName": str,
+        "startedAfter": Union[datetime, str],
+        "startedBefore": Union[datetime, str],
+        "status": BatchJobExecutionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef(
+    _RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
+    _OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListBatchJobExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredListBatchJobExecutionsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListBatchJobExecutionsRequestRequestTypeDef = TypedDict(
@@ -634,14 +807,34 @@
 
 class ListBatchJobExecutionsRequestRequestTypeDef(
     _RequiredListBatchJobExecutionsRequestRequestTypeDef,
     _OptionalListBatchJobExecutionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
+    "_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
+    "_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef(
+    _RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
+    _OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredListDataSetImportHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSetImportHistoryRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListDataSetImportHistoryRequestRequestTypeDef = TypedDict(
@@ -655,14 +848,35 @@
 
 class ListDataSetImportHistoryRequestRequestTypeDef(
     _RequiredListDataSetImportHistoryRequestRequestTypeDef,
     _OptionalListDataSetImportHistoryRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
+    "_RequiredListDataSetsRequestListDataSetsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
+    "_OptionalListDataSetsRequestListDataSetsPaginateTypeDef",
+    {
+        "prefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDataSetsRequestListDataSetsPaginateTypeDef(
+    _RequiredListDataSetsRequestListDataSetsPaginateTypeDef,
+    _OptionalListDataSetsRequestListDataSetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDataSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSetsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListDataSetsRequestRequestTypeDef = TypedDict(
@@ -676,14 +890,34 @@
 )
 
 class ListDataSetsRequestRequestTypeDef(
     _RequiredListDataSetsRequestRequestTypeDef, _OptionalListDataSetsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef",
+    {
+        "applicationId": str,
+    },
+)
+_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDeploymentsRequestListDeploymentsPaginateTypeDef(
+    _RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef,
+    _OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredListDeploymentsRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalListDeploymentsRequestRequestTypeDef = TypedDict(
@@ -696,24 +930,43 @@
 )
 
 class ListDeploymentsRequestRequestTypeDef(
     _RequiredListDeploymentsRequestRequestTypeDef, _OptionalListDeploymentsRequestRequestTypeDef
 ):
     pass
 
+ListEngineVersionsRequestListEngineVersionsPaginateTypeDef = TypedDict(
+    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
+    {
+        "engineType": EngineTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEngineVersionsRequestRequestTypeDef = TypedDict(
     "ListEngineVersionsRequestRequestTypeDef",
     {
         "engineType": EngineTypeType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
+    {
+        "engineType": EngineTypeType,
+        "names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentsRequestRequestTypeDef = TypedDict(
     "ListEnvironmentsRequestRequestTypeDef",
     {
         "engineType": EngineTypeType,
         "maxResults": int,
         "names": Sequence[str],
         "nextToken": str,
@@ -724,23 +977,41 @@
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
 MaintenanceScheduleTypeDef = TypedDict(
     "MaintenanceScheduleTypeDef",
     {
         "endTime": datetime,
         "startTime": datetime,
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
 _RequiredPrimaryKeyTypeDef = TypedDict(
     "_RequiredPrimaryKeyTypeDef",
     {
         "length": int,
         "offset": int,
     },
 )
@@ -751,21 +1022,40 @@
     },
     total=False,
 )
 
 class PrimaryKeyTypeDef(_RequiredPrimaryKeyTypeDef, _OptionalPrimaryKeyTypeDef):
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
 StartApplicationRequestRequestTypeDef = TypedDict(
     "StartApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 
+StartBatchJobResponseTypeDef = TypedDict(
+    "StartBatchJobResponseTypeDef",
+    {
+        "executionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredStopApplicationRequestRequestTypeDef",
     {
         "applicationId": str,
     },
 )
 _OptionalStopApplicationRequestRequestTypeDef = TypedDict(
@@ -793,14 +1083,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateApplicationResponseTypeDef = TypedDict(
+    "UpdateApplicationResponseTypeDef",
+    {
+        "applicationVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEnvironmentRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 _OptionalUpdateEnvironmentRequestRequestTypeDef = TypedDict(
@@ -816,14 +1114,40 @@
 )
 
 class UpdateEnvironmentRequestRequestTypeDef(
     _RequiredUpdateEnvironmentRequestRequestTypeDef, _OptionalUpdateEnvironmentRequestRequestTypeDef
 ):
     pass
 
+UpdateEnvironmentResponseTypeDef = TypedDict(
+    "UpdateEnvironmentResponseTypeDef",
+    {
+        "environmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationsResponseTypeDef = TypedDict(
+    "ListApplicationsResponseTypeDef",
+    {
+        "applications": List[ApplicationSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationVersionsResponseTypeDef = TypedDict(
+    "ListApplicationVersionsResponseTypeDef",
+    {
+        "applicationVersions": List[ApplicationVersionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchJobDefinitionTypeDef = TypedDict(
     "BatchJobDefinitionTypeDef",
     {
         "fileBatchJobDefinition": FileBatchJobDefinitionTypeDef,
         "scriptBatchJobDefinition": ScriptBatchJobDefinitionTypeDef,
     },
     total=False,
@@ -848,14 +1172,15 @@
 )
 _OptionalCreateApplicationRequestRequestTypeDef = TypedDict(
     "_OptionalCreateApplicationRequestRequestTypeDef",
     {
         "clientToken": str,
         "description": str,
         "kmsKeyId": str,
+        "roleArn": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
@@ -879,126 +1204,14 @@
 )
 
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
-CreateApplicationResponseTypeDef = TypedDict(
-    "CreateApplicationResponseTypeDef",
-    {
-        "applicationArn": str,
-        "applicationId": str,
-        "applicationVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSetImportTaskResponseTypeDef = TypedDict(
-    "CreateDataSetImportTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResponseTypeDef = TypedDict(
-    "CreateDeploymentResponseTypeDef",
-    {
-        "deploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEnvironmentResponseTypeDef = TypedDict(
-    "CreateEnvironmentResponseTypeDef",
-    {
-        "environmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApplicationVersionResponseTypeDef = TypedDict(
-    "GetApplicationVersionResponseTypeDef",
-    {
-        "applicationVersion": int,
-        "creationTime": datetime,
-        "definitionContent": str,
-        "description": str,
-        "name": str,
-        "status": ApplicationVersionLifecycleType,
-        "statusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeploymentResponseTypeDef = TypedDict(
-    "GetDeploymentResponseTypeDef",
-    {
-        "applicationId": str,
-        "applicationVersion": int,
-        "creationTime": datetime,
-        "deploymentId": str,
-        "environmentId": str,
-        "status": DeploymentLifecycleType,
-        "statusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationVersionsResponseTypeDef = TypedDict(
-    "ListApplicationVersionsResponseTypeDef",
-    {
-        "applicationVersions": List[ApplicationVersionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsResponseTypeDef = TypedDict(
-    "ListApplicationsResponseTypeDef",
-    {
-        "applications": List[ApplicationSummaryTypeDef],
-        "nextToken": str,
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
-StartBatchJobResponseTypeDef = TypedDict(
-    "StartBatchJobResponseTypeDef",
-    {
-        "executionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateApplicationResponseTypeDef = TypedDict(
-    "UpdateApplicationResponseTypeDef",
-    {
-        "applicationVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateEnvironmentResponseTypeDef = TypedDict(
-    "UpdateEnvironmentResponseTypeDef",
-    {
-        "environmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DataSetImportTaskTypeDef = TypedDict(
     "DataSetImportTaskTypeDef",
     {
         "status": DataSetTaskLifecycleType,
         "summary": DataSetImportSummaryTypeDef,
         "taskId": str,
     },
@@ -1006,51 +1219,51 @@
 
 GetDataSetImportTaskResponseTypeDef = TypedDict(
     "GetDataSetImportTaskResponseTypeDef",
     {
         "status": DataSetTaskLifecycleType,
         "summary": DataSetImportSummaryTypeDef,
         "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataSetsResponseTypeDef = TypedDict(
     "ListDataSetsResponseTypeDef",
     {
         "dataSets": List[DataSetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeploymentsResponseTypeDef = TypedDict(
     "ListDeploymentsResponseTypeDef",
     {
         "deployments": List[DeploymentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEngineVersionsResponseTypeDef = TypedDict(
     "ListEngineVersionsResponseTypeDef",
     {
         "engineVersions": List[EngineVersionsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEnvironmentsResponseTypeDef = TypedDict(
     "ListEnvironmentsResponseTypeDef",
     {
         "environments": List[EnvironmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StorageConfigurationTypeDef = TypedDict(
     "StorageConfigurationTypeDef",
     {
         "efs": EfsStorageConfigurationTypeDef,
@@ -1073,177 +1286,22 @@
         "lastStartTime": datetime,
         "latestVersion": ApplicationVersionSummaryTypeDef,
         "listenerArns": List[str],
         "listenerPorts": List[int],
         "loadBalancerDnsName": str,
         "logGroups": List[LogGroupSummaryTypeDef],
         "name": str,
+        "roleArn": str,
         "status": ApplicationLifecycleType,
         "statusReason": str,
         "tags": Dict[str, str],
         "targetGroupArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
-    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-):
-    pass
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "environmentId": str,
-        "names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
-    "_RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef = TypedDict(
-    "_OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef",
-    {
-        "prefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef(
-    _RequiredListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-    _OptionalListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef",
-    {
-        "executionIds": Sequence[str],
-        "jobName": str,
-        "startedAfter": Union[datetime, str],
-        "startedBefore": Union[datetime, str],
-        "status": BatchJobExecutionStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef(
-    _RequiredListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-    _OptionalListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
-    "_RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef = TypedDict(
-    "_OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef(
-    _RequiredListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-    _OptionalListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-):
-    pass
-
-_RequiredListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
-    "_RequiredListDataSetsRequestListDataSetsPaginateTypeDef",
-    {
-        "applicationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
-    "_OptionalListDataSetsRequestListDataSetsPaginateTypeDef",
-    {
-        "prefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDataSetsRequestListDataSetsPaginateTypeDef(
-    _RequiredListDataSetsRequestListDataSetsPaginateTypeDef,
-    _OptionalListDataSetsRequestListDataSetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    {
-        "applicationId": str,
-    },
-)
-_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDeploymentsRequestListDeploymentsPaginateTypeDef(
-    _RequiredListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    _OptionalListDeploymentsRequestListDeploymentsPaginateTypeDef,
-):
-    pass
-
-ListEngineVersionsRequestListEngineVersionsPaginateTypeDef = TypedDict(
-    "ListEngineVersionsRequestListEngineVersionsPaginateTypeDef",
-    {
-        "engineType": EngineTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    {
-        "engineType": EngineTypeType,
-        "names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 PendingMaintenanceTypeDef = TypedDict(
     "PendingMaintenanceTypeDef",
     {
         "engineVersion": str,
         "schedule": MaintenanceScheduleTypeDef,
     },
@@ -1284,15 +1342,15 @@
 )
 
 ListBatchJobDefinitionsResponseTypeDef = TypedDict(
     "ListBatchJobDefinitionsResponseTypeDef",
     {
         "batchJobDefinitions": List[BatchJobDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchJobExecutionSummaryTypeDef = TypedDict(
     "_RequiredBatchJobExecutionSummaryTypeDef",
     {
         "applicationId": str,
@@ -1330,15 +1388,15 @@
         "jobName": str,
         "jobType": BatchJobTypeType,
         "jobUser": str,
         "returnCode": str,
         "startTime": datetime,
         "status": BatchJobExecutionStatusType,
         "statusReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartBatchJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartBatchJobRequestRequestTypeDef",
     {
         "applicationId": str,
@@ -1359,15 +1417,15 @@
     pass
 
 ListDataSetImportHistoryResponseTypeDef = TypedDict(
     "ListDataSetImportHistoryResponseTypeDef",
     {
         "dataSetImportTasks": List[DataSetImportTaskTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentRequestRequestTypeDef",
     {
         "engineType": EngineTypeType,
@@ -1419,42 +1477,46 @@
         "securityGroupIds": List[str],
         "status": EnvironmentLifecycleType,
         "statusReason": str,
         "storageConfigurations": List[StorageConfigurationTypeDef],
         "subnetIds": List[str],
         "tags": Dict[str, str],
         "vpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetOrgAttributesTypeDef = TypedDict(
     "DatasetOrgAttributesTypeDef",
     {
         "gdg": GdgAttributesTypeDef,
+        "po": PoAttributesTypeDef,
+        "ps": PsAttributesTypeDef,
         "vsam": VsamAttributesTypeDef,
     },
     total=False,
 )
 
 DatasetDetailOrgAttributesTypeDef = TypedDict(
     "DatasetDetailOrgAttributesTypeDef",
     {
         "gdg": GdgDetailAttributesTypeDef,
+        "po": PoDetailAttributesTypeDef,
+        "ps": PsDetailAttributesTypeDef,
         "vsam": VsamDetailAttributesTypeDef,
     },
     total=False,
 )
 
 ListBatchJobExecutionsResponseTypeDef = TypedDict(
     "ListBatchJobExecutionsResponseTypeDef",
     {
         "batchJobExecutions": List[BatchJobExecutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDataSetTypeDef = TypedDict(
     "_RequiredDataSetTypeDef",
     {
         "datasetName": str,
@@ -1481,15 +1543,15 @@
         "creationTime": datetime,
         "dataSetName": str,
         "dataSetOrg": DatasetDetailOrgAttributesTypeDef,
         "lastReferencedTime": datetime,
         "lastUpdatedTime": datetime,
         "location": str,
         "recordLength": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSetImportItemTypeDef = TypedDict(
     "DataSetImportItemTypeDef",
     {
         "dataSet": DataSetTypeDef,
```

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/PKG-INFO` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-m2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MainframeModernization 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MainframeModernization 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-m2"></a>
 
 # types-aiobotocore-m2
 
 [![PyPI - types-aiobotocore-m2](https://img.shields.io/pypi/v/types-aiobotocore-m2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-m2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-m2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-m2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-m2?color=blue)](https://pypistats.org/packages/types-aiobotocore-m2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MainframeModernization 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization)
+[aiobotocore.MainframeModernization 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/m2.html#MainframeModernization)
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
 [types-aiobotocore-m2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_m2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -371,91 +371,95 @@
     ApplicationVersionSummaryTypeDef,
     FileBatchJobDefinitionTypeDef,
     ScriptBatchJobDefinitionTypeDef,
     FileBatchJobIdentifierTypeDef,
     ScriptBatchJobIdentifierTypeDef,
     CancelBatchJobExecutionRequestRequestTypeDef,
     DefinitionTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationResponseTypeDef,
+    CreateDataSetImportTaskResponseTypeDef,
     CreateDeploymentRequestRequestTypeDef,
+    CreateDeploymentResponseTypeDef,
     HighAvailabilityConfigTypeDef,
+    CreateEnvironmentResponseTypeDef,
     ExternalLocationTypeDef,
     DataSetImportSummaryTypeDef,
     DataSetSummaryTypeDef,
     RecordLengthTypeDef,
     GdgDetailAttributesTypeDef,
+    PoDetailAttributesTypeDef,
+    PsDetailAttributesTypeDef,
     GdgAttributesTypeDef,
+    PoAttributesTypeDef,
+    PsAttributesTypeDef,
     DeleteApplicationFromEnvironmentRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
     DeployedVersionSummaryTypeDef,
     DeploymentSummaryTypeDef,
     EfsStorageConfigurationTypeDef,
     EngineVersionsSummaryTypeDef,
     EnvironmentSummaryTypeDef,
     FsxStorageConfigurationTypeDef,
     GetApplicationRequestRequestTypeDef,
     LogGroupSummaryTypeDef,
     GetApplicationVersionRequestRequestTypeDef,
+    GetApplicationVersionResponseTypeDef,
     GetBatchJobExecutionRequestRequestTypeDef,
     GetDataSetDetailsRequestRequestTypeDef,
     GetDataSetImportTaskRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetDeploymentResponseTypeDef,
     GetEnvironmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
     ListBatchJobDefinitionsRequestRequestTypeDef,
+    ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
     ListBatchJobExecutionsRequestRequestTypeDef,
+    ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
     ListDataSetImportHistoryRequestRequestTypeDef,
+    ListDataSetsRequestListDataSetsPaginateTypeDef,
     ListDataSetsRequestRequestTypeDef,
+    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
     ListDeploymentsRequestRequestTypeDef,
+    ListEngineVersionsRequestListEngineVersionsPaginateTypeDef,
     ListEngineVersionsRequestRequestTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MaintenanceScheduleTypeDef,
+    PaginatorConfigTypeDef,
     PrimaryKeyTypeDef,
+    ResponseMetadataTypeDef,
     StartApplicationRequestRequestTypeDef,
+    StartBatchJobResponseTypeDef,
     StopApplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateApplicationResponseTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
+    UpdateEnvironmentResponseTypeDef,
+    ListApplicationsResponseTypeDef,
+    ListApplicationVersionsResponseTypeDef,
     BatchJobDefinitionTypeDef,
     BatchJobIdentifierTypeDef,
     CreateApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    CreateApplicationResponseTypeDef,
-    CreateDataSetImportTaskResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    GetApplicationVersionResponseTypeDef,
-    GetDeploymentResponseTypeDef,
-    ListApplicationVersionsResponseTypeDef,
-    ListApplicationsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartBatchJobResponseTypeDef,
-    UpdateApplicationResponseTypeDef,
-    UpdateEnvironmentResponseTypeDef,
     DataSetImportTaskTypeDef,
     GetDataSetImportTaskResponseTypeDef,
     ListDataSetsResponseTypeDef,
     ListDeploymentsResponseTypeDef,
     ListEngineVersionsResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     StorageConfigurationTypeDef,
     GetApplicationResponseTypeDef,
-    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
-    ListBatchJobDefinitionsRequestListBatchJobDefinitionsPaginateTypeDef,
-    ListBatchJobExecutionsRequestListBatchJobExecutionsPaginateTypeDef,
-    ListDataSetImportHistoryRequestListDataSetImportHistoryPaginateTypeDef,
-    ListDataSetsRequestListDataSetsPaginateTypeDef,
-    ListDeploymentsRequestListDeploymentsPaginateTypeDef,
-    ListEngineVersionsRequestListEngineVersionsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     PendingMaintenanceTypeDef,
     VsamAttributesTypeDef,
     VsamDetailAttributesTypeDef,
     ListBatchJobDefinitionsResponseTypeDef,
     BatchJobExecutionSummaryTypeDef,
     GetBatchJobExecutionResponseTypeDef,
     StartBatchJobRequestRequestTypeDef,
@@ -480,43 +484,43 @@
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

### Comparing `types-aiobotocore-m2-2.5.0.post1/types_aiobotocore_m2.egg-info/SOURCES.txt` & `types-aiobotocore-m2-2.5.1/types_aiobotocore_m2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

