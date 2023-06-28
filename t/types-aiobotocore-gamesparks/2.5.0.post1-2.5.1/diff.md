# Comparing `tmp/types-aiobotocore-gamesparks-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-gamesparks-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-gamesparks-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-gamesparks-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-gamesparks-2.5.0.post1.tar` & `types-aiobotocore-gamesparks-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.851228 types-aiobotocore-gamesparks-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17563 2023-03-11 12:26:39.851228 types-aiobotocore-gamesparks-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15980 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.851228 types-aiobotocore-gamesparks-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.843228 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/
--rw-r--r--   0 runner    (1001) docker     (123)     1903 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26620 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    26571 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8922 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8920 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8833 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8823 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    29813 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    29770 2023-03-11 12:15:00.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:59.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.851228 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17563 2023-03-11 12:26:39.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:39.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:39.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:39.000000 types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.794141 types-aiobotocore-gamesparks-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17558 2023-06-28 01:43:31.794141 types-aiobotocore-gamesparks-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15981 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.794141 types-aiobotocore-gamesparks-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.794141 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/
+-rw-r--r--   0 runner    (1001) docker     (123)     1903 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26620 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26571 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9131 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9129 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8727 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8718 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    29885 2023-06-28 01:31:37.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29842 2023-06-28 01:31:37.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:36.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.794141 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17558 2023-06-28 01:43:31.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:31.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:31.000000 types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/LICENSE` & `types-aiobotocore-gamesparks-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/PKG-INFO` & `types-aiobotocore-gamesparks-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-gamesparks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GameSparks 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GameSparks 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-gamesparks"></a>
 
 # types-aiobotocore-gamesparks
 
 [![PyPI - types-aiobotocore-gamesparks](https://img.shields.io/pypi/v/types-aiobotocore-gamesparks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamesparks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-gamesparks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamesparks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-gamesparks?color=blue)](https://pypistats.org/packages/types-aiobotocore-gamesparks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GameSparks 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks)
+[aiobotocore.GameSparks 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks)
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
 [types-aiobotocore-gamesparks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,23 +350,24 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_gamesparks.type_defs import (
     ConnectionTypeDef,
     CreateGameRequestRequestTypeDef,
     GameDetailsTypeDef,
-    ResponseMetadataTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateStageRequestRequestTypeDef,
     StageDetailsTypeDef,
     DeleteGameRequestRequestTypeDef,
     DeleteStageRequestRequestTypeDef,
     DeploymentResultTypeDef,
     DisconnectPlayerRequestRequestTypeDef,
+    DisconnectPlayerResultTypeDef,
     ExportSnapshotRequestRequestTypeDef,
+    ExportSnapshotResultTypeDef,
     ExtensionDetailsTypeDef,
     ExtensionVersionDetailsTypeDef,
     SectionTypeDef,
     GameSummaryTypeDef,
     GeneratedCodeJobDetailsTypeDef,
     GeneratorTypeDef,
     GetExtensionRequestRequestTypeDef,
@@ -375,39 +376,45 @@
     GetGameRequestRequestTypeDef,
     GetGeneratedCodeJobRequestRequestTypeDef,
     GetPlayerConnectionStatusRequestRequestTypeDef,
     GetSnapshotRequestRequestTypeDef,
     GetStageDeploymentRequestRequestTypeDef,
     GetStageRequestRequestTypeDef,
     ImportGameConfigurationSourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
     ListExtensionVersionsRequestRequestTypeDef,
+    ListExtensionsRequestListExtensionsPaginateTypeDef,
     ListExtensionsRequestRequestTypeDef,
+    ListGamesRequestListGamesPaginateTypeDef,
     ListGamesRequestRequestTypeDef,
+    ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
     ListGeneratedCodeJobsRequestRequestTypeDef,
+    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
     ListSnapshotsRequestRequestTypeDef,
     SnapshotSummaryTypeDef,
+    ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
     ListStageDeploymentsRequestRequestTypeDef,
+    ListStagesRequestListStagesPaginateTypeDef,
     ListStagesRequestRequestTypeDef,
     StageSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SectionModificationTypeDef,
+    StartGeneratedCodeJobResultTypeDef,
     StartStageDeploymentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateGameRequestRequestTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     UpdateStageRequestRequestTypeDef,
+    GetPlayerConnectionStatusResultTypeDef,
     CreateGameResultTypeDef,
-    DisconnectPlayerResultTypeDef,
-    ExportSnapshotResultTypeDef,
     GetGameResultTypeDef,
-    GetPlayerConnectionStatusResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    StartGeneratedCodeJobResultTypeDef,
     UpdateGameResultTypeDef,
     CreateStageResultTypeDef,
     GetStageResultTypeDef,
     UpdateStageResultTypeDef,
     StageDeploymentDetailsTypeDef,
     StageDeploymentSummaryTypeDef,
     GetExtensionResultTypeDef,
@@ -417,21 +424,14 @@
     GameConfigurationDetailsTypeDef,
     SnapshotDetailsTypeDef,
     ListGamesResultTypeDef,
     GetGeneratedCodeJobResultTypeDef,
     ListGeneratedCodeJobsResultTypeDef,
     StartGeneratedCodeJobRequestRequestTypeDef,
     ImportGameConfigurationRequestRequestTypeDef,
-    ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-    ListExtensionsRequestListExtensionsPaginateTypeDef,
-    ListGamesRequestListGamesPaginateTypeDef,
-    ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-    ListStagesRequestListStagesPaginateTypeDef,
     ListSnapshotsResultTypeDef,
     ListStagesResultTypeDef,
     UpdateGameConfigurationRequestRequestTypeDef,
     GetStageDeploymentResultTypeDef,
     StartStageDeploymentResultTypeDef,
     ListStageDeploymentsResultTypeDef,
     GetGameConfigurationResultTypeDef,
@@ -450,43 +450,43 @@
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/README.md` & `types-aiobotocore-gamesparks-2.5.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-gamesparks"></a>
 
 # types-aiobotocore-gamesparks
 
 [![PyPI - types-aiobotocore-gamesparks](https://img.shields.io/pypi/v/types-aiobotocore-gamesparks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamesparks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-gamesparks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamesparks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-gamesparks?color=blue)](https://pypistats.org/packages/types-aiobotocore-gamesparks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GameSparks 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks)
+[aiobotocore.GameSparks 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks)
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
 [types-aiobotocore-gamesparks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,23 +317,24 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_gamesparks.type_defs import (
     ConnectionTypeDef,
     CreateGameRequestRequestTypeDef,
     GameDetailsTypeDef,
-    ResponseMetadataTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateStageRequestRequestTypeDef,
     StageDetailsTypeDef,
     DeleteGameRequestRequestTypeDef,
     DeleteStageRequestRequestTypeDef,
     DeploymentResultTypeDef,
     DisconnectPlayerRequestRequestTypeDef,
+    DisconnectPlayerResultTypeDef,
     ExportSnapshotRequestRequestTypeDef,
+    ExportSnapshotResultTypeDef,
     ExtensionDetailsTypeDef,
     ExtensionVersionDetailsTypeDef,
     SectionTypeDef,
     GameSummaryTypeDef,
     GeneratedCodeJobDetailsTypeDef,
     GeneratorTypeDef,
     GetExtensionRequestRequestTypeDef,
@@ -342,39 +343,45 @@
     GetGameRequestRequestTypeDef,
     GetGeneratedCodeJobRequestRequestTypeDef,
     GetPlayerConnectionStatusRequestRequestTypeDef,
     GetSnapshotRequestRequestTypeDef,
     GetStageDeploymentRequestRequestTypeDef,
     GetStageRequestRequestTypeDef,
     ImportGameConfigurationSourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
     ListExtensionVersionsRequestRequestTypeDef,
+    ListExtensionsRequestListExtensionsPaginateTypeDef,
     ListExtensionsRequestRequestTypeDef,
+    ListGamesRequestListGamesPaginateTypeDef,
     ListGamesRequestRequestTypeDef,
+    ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
     ListGeneratedCodeJobsRequestRequestTypeDef,
+    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
     ListSnapshotsRequestRequestTypeDef,
     SnapshotSummaryTypeDef,
+    ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
     ListStageDeploymentsRequestRequestTypeDef,
+    ListStagesRequestListStagesPaginateTypeDef,
     ListStagesRequestRequestTypeDef,
     StageSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SectionModificationTypeDef,
+    StartGeneratedCodeJobResultTypeDef,
     StartStageDeploymentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateGameRequestRequestTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     UpdateStageRequestRequestTypeDef,
+    GetPlayerConnectionStatusResultTypeDef,
     CreateGameResultTypeDef,
-    DisconnectPlayerResultTypeDef,
-    ExportSnapshotResultTypeDef,
     GetGameResultTypeDef,
-    GetPlayerConnectionStatusResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    StartGeneratedCodeJobResultTypeDef,
     UpdateGameResultTypeDef,
     CreateStageResultTypeDef,
     GetStageResultTypeDef,
     UpdateStageResultTypeDef,
     StageDeploymentDetailsTypeDef,
     StageDeploymentSummaryTypeDef,
     GetExtensionResultTypeDef,
@@ -384,21 +391,14 @@
     GameConfigurationDetailsTypeDef,
     SnapshotDetailsTypeDef,
     ListGamesResultTypeDef,
     GetGeneratedCodeJobResultTypeDef,
     ListGeneratedCodeJobsResultTypeDef,
     StartGeneratedCodeJobRequestRequestTypeDef,
     ImportGameConfigurationRequestRequestTypeDef,
-    ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-    ListExtensionsRequestListExtensionsPaginateTypeDef,
-    ListGamesRequestListGamesPaginateTypeDef,
-    ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-    ListStagesRequestListStagesPaginateTypeDef,
     ListSnapshotsResultTypeDef,
     ListStagesResultTypeDef,
     UpdateGameConfigurationRequestRequestTypeDef,
     GetStageDeploymentResultTypeDef,
     StartStageDeploymentResultTypeDef,
     ListStageDeploymentsResultTypeDef,
     GetGameConfigurationResultTypeDef,
@@ -417,43 +417,43 @@
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/setup.py` & `types-aiobotocore-gamesparks-2.5.1/setup.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-gamesparks.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-gamesparks",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_gamesparks"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.GameSparks 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.GameSparks 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/"
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/__init__.py` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/__init__.pyi` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/__main__.py` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.GameSparks 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.GameSparks 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks\nOther"
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/client.py` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/client.pyi` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/literals.py` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -115,14 +115,15 @@
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
@@ -201,14 +202,15 @@
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
@@ -219,14 +221,15 @@
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
@@ -262,14 +265,15 @@
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
@@ -288,16 +292,19 @@
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
@@ -381,15 +388,17 @@
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/literals.pyi` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -113,14 +113,15 @@
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
@@ -199,14 +200,15 @@
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
@@ -217,14 +219,15 @@
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
@@ -260,14 +263,15 @@
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
@@ -286,16 +290,19 @@
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
@@ -379,15 +386,17 @@
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/paginator.py` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_games_paginator: ListGamesPaginator = client.get_paginator("list_games")
         list_generated_code_jobs_paginator: ListGeneratedCodeJobsPaginator = client.get_paginator("list_generated_code_jobs")
         list_snapshots_paginator: ListSnapshotsPaginator = client.get_paginator("list_snapshots")
         list_stage_deployments_paginator: ListStageDeploymentsPaginator = client.get_paginator("list_stage_deployments")
         list_stages_paginator: ListStagesPaginator = client.get_paginator("list_stages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListExtensionsResultTypeDef,
     ListExtensionVersionsResultTypeDef,
@@ -45,20 +44,14 @@
     ListGeneratedCodeJobsResultTypeDef,
     ListSnapshotsResultTypeDef,
     ListStageDeploymentsResultTypeDef,
     ListStagesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListExtensionVersionsPaginator",
     "ListExtensionsPaginator",
     "ListGamesPaginator",
     "ListGeneratedCodeJobsPaginator",
     "ListSnapshotsPaginator",
     "ListStageDeploymentsPaginator",
@@ -79,103 +72,103 @@
 class ListExtensionVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensionVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionversionspaginator)
     """
 
     def paginate(
-        self, *, Name: str, Namespace: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Name: str, Namespace: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExtensionVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensionVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionversionspaginator)
         """
 
 
 class ListExtensionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExtensionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionspaginator)
         """
 
 
 class ListGamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGamesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgamespaginator)
         """
 
 
 class ListGeneratedCodeJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGeneratedCodeJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgeneratedcodejobspaginator)
     """
 
     def paginate(
-        self, *, GameName: str, SnapshotId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, SnapshotId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGeneratedCodeJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGeneratedCodeJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgeneratedcodejobspaginator)
         """
 
 
 class ListSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listsnapshotspaginator)
     """
 
     def paginate(
-        self, *, GameName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listsnapshotspaginator)
         """
 
 
 class ListStageDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStageDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagedeploymentspaginator)
     """
 
     def paginate(
-        self, *, GameName: str, StageName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, StageName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStageDeploymentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStageDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagedeploymentspaginator)
         """
 
 
 class ListStagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagespaginator)
     """
 
     def paginate(
-        self, *, GameName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagespaginator)
         """
```

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/paginator.pyi` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_games_paginator: ListGamesPaginator = client.get_paginator("list_games")
         list_generated_code_jobs_paginator: ListGeneratedCodeJobsPaginator = client.get_paginator("list_generated_code_jobs")
         list_snapshots_paginator: ListSnapshotsPaginator = client.get_paginator("list_snapshots")
         list_stage_deployments_paginator: ListStageDeploymentsPaginator = client.get_paginator("list_stage_deployments")
         list_stages_paginator: ListStagesPaginator = client.get_paginator("list_stages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListExtensionsResultTypeDef,
     ListExtensionVersionsResultTypeDef,
@@ -45,19 +44,14 @@
     ListGeneratedCodeJobsResultTypeDef,
     ListSnapshotsResultTypeDef,
     ListStageDeploymentsResultTypeDef,
     ListStagesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListExtensionVersionsPaginator",
     "ListExtensionsPaginator",
     "ListGamesPaginator",
     "ListGeneratedCodeJobsPaginator",
     "ListSnapshotsPaginator",
     "ListStageDeploymentsPaginator",
@@ -75,97 +69,97 @@
 class ListExtensionVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensionVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionversionspaginator)
     """
 
     def paginate(
-        self, *, Name: str, Namespace: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Name: str, Namespace: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExtensionVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensionVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionversionspaginator)
         """
 
 class ListExtensionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExtensionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListExtensions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listextensionspaginator)
         """
 
 class ListGamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGamesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgamespaginator)
         """
 
 class ListGeneratedCodeJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGeneratedCodeJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgeneratedcodejobspaginator)
     """
 
     def paginate(
-        self, *, GameName: str, SnapshotId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, SnapshotId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGeneratedCodeJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListGeneratedCodeJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listgeneratedcodejobspaginator)
         """
 
 class ListSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listsnapshotspaginator)
     """
 
     def paginate(
-        self, *, GameName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#listsnapshotspaginator)
         """
 
 class ListStageDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStageDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagedeploymentspaginator)
     """
 
     def paginate(
-        self, *, GameName: str, StageName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, StageName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStageDeploymentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStageDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagedeploymentspaginator)
         """
 
 class ListStagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagespaginator)
     """
 
     def paginate(
-        self, *, GameName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, GameName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks.Paginator.ListStages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/paginators/#liststagespaginator)
         """
```

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/type_defs.py` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -28,28 +28,28 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ConnectionTypeDef",
     "CreateGameRequestRequestTypeDef",
     "GameDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "CreateStageRequestRequestTypeDef",
     "StageDetailsTypeDef",
     "DeleteGameRequestRequestTypeDef",
     "DeleteStageRequestRequestTypeDef",
     "DeploymentResultTypeDef",
     "DisconnectPlayerRequestRequestTypeDef",
+    "DisconnectPlayerResultTypeDef",
     "ExportSnapshotRequestRequestTypeDef",
+    "ExportSnapshotResultTypeDef",
     "ExtensionDetailsTypeDef",
     "ExtensionVersionDetailsTypeDef",
     "SectionTypeDef",
     "GameSummaryTypeDef",
     "GeneratedCodeJobDetailsTypeDef",
     "GeneratorTypeDef",
     "GetExtensionRequestRequestTypeDef",
@@ -58,39 +58,45 @@
     "GetGameRequestRequestTypeDef",
     "GetGeneratedCodeJobRequestRequestTypeDef",
     "GetPlayerConnectionStatusRequestRequestTypeDef",
     "GetSnapshotRequestRequestTypeDef",
     "GetStageDeploymentRequestRequestTypeDef",
     "GetStageRequestRequestTypeDef",
     "ImportGameConfigurationSourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
     "ListExtensionVersionsRequestRequestTypeDef",
+    "ListExtensionsRequestListExtensionsPaginateTypeDef",
     "ListExtensionsRequestRequestTypeDef",
+    "ListGamesRequestListGamesPaginateTypeDef",
     "ListGamesRequestRequestTypeDef",
+    "ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
     "ListGeneratedCodeJobsRequestRequestTypeDef",
+    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
     "ListSnapshotsRequestRequestTypeDef",
     "SnapshotSummaryTypeDef",
+    "ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
     "ListStageDeploymentsRequestRequestTypeDef",
+    "ListStagesRequestListStagesPaginateTypeDef",
     "ListStagesRequestRequestTypeDef",
     "StageSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SectionModificationTypeDef",
+    "StartGeneratedCodeJobResultTypeDef",
     "StartStageDeploymentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateGameRequestRequestTypeDef",
     "UpdateSnapshotRequestRequestTypeDef",
     "UpdateStageRequestRequestTypeDef",
+    "GetPlayerConnectionStatusResultTypeDef",
     "CreateGameResultTypeDef",
-    "DisconnectPlayerResultTypeDef",
-    "ExportSnapshotResultTypeDef",
     "GetGameResultTypeDef",
-    "GetPlayerConnectionStatusResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "StartGeneratedCodeJobResultTypeDef",
     "UpdateGameResultTypeDef",
     "CreateStageResultTypeDef",
     "GetStageResultTypeDef",
     "UpdateStageResultTypeDef",
     "StageDeploymentDetailsTypeDef",
     "StageDeploymentSummaryTypeDef",
     "GetExtensionResultTypeDef",
@@ -100,21 +106,14 @@
     "GameConfigurationDetailsTypeDef",
     "SnapshotDetailsTypeDef",
     "ListGamesResultTypeDef",
     "GetGeneratedCodeJobResultTypeDef",
     "ListGeneratedCodeJobsResultTypeDef",
     "StartGeneratedCodeJobRequestRequestTypeDef",
     "ImportGameConfigurationRequestRequestTypeDef",
-    "ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
-    "ListExtensionsRequestListExtensionsPaginateTypeDef",
-    "ListGamesRequestListGamesPaginateTypeDef",
-    "ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
-    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    "ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
-    "ListStagesRequestListStagesPaginateTypeDef",
     "ListSnapshotsResultTypeDef",
     "ListStagesResultTypeDef",
     "UpdateGameConfigurationRequestRequestTypeDef",
     "GetStageDeploymentResultTypeDef",
     "StartStageDeploymentResultTypeDef",
     "ListStageDeploymentsResultTypeDef",
     "GetGameConfigurationResultTypeDef",
@@ -146,21 +145,19 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateGameRequestRequestTypeDef(
     _RequiredCreateGameRequestRequestTypeDef, _OptionalCreateGameRequestRequestTypeDef
 ):
     pass
 
-
 GameDetailsTypeDef = TypedDict(
     "GameDetailsTypeDef",
     {
         "Arn": str,
         "Created": datetime,
         "Description": str,
         "EnableTerminationProtection": bool,
@@ -168,46 +165,33 @@
         "Name": str,
         "State": GameStateType,
         "Tags": Dict[str, str],
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
 _RequiredCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSnapshotRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
 _OptionalCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSnapshotRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class CreateSnapshotRequestRequestTypeDef(
     _RequiredCreateSnapshotRequestRequestTypeDef, _OptionalCreateSnapshotRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateStageRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStageRequestRequestTypeDef",
     {
         "GameName": str,
         "Role": str,
         "StageName": str,
     },
@@ -218,21 +202,19 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateStageRequestRequestTypeDef(
     _RequiredCreateStageRequestRequestTypeDef, _OptionalCreateStageRequestRequestTypeDef
 ):
     pass
 
-
 StageDetailsTypeDef = TypedDict(
     "StageDetailsTypeDef",
     {
         "Arn": str,
         "Created": datetime,
         "Description": str,
         "GameKey": str,
@@ -275,22 +257,39 @@
     {
         "GameName": str,
         "PlayerId": str,
         "StageName": str,
     },
 )
 
+DisconnectPlayerResultTypeDef = TypedDict(
+    "DisconnectPlayerResultTypeDef",
+    {
+        "DisconnectFailures": List[str],
+        "DisconnectSuccesses": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportSnapshotRequestRequestTypeDef = TypedDict(
     "ExportSnapshotRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
     },
 )
 
+ExportSnapshotResultTypeDef = TypedDict(
+    "ExportSnapshotResultTypeDef",
+    {
+        "S3Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExtensionDetailsTypeDef = TypedDict(
     "ExtensionDetailsTypeDef",
     {
         "Description": str,
         "Name": str,
         "Namespace": str,
     },
@@ -378,22 +377,20 @@
     "_OptionalGetGameConfigurationRequestRequestTypeDef",
     {
         "Sections": Sequence[str],
     },
     total=False,
 )
 
-
 class GetGameConfigurationRequestRequestTypeDef(
     _RequiredGetGameConfigurationRequestRequestTypeDef,
     _OptionalGetGameConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetGameRequestRequestTypeDef = TypedDict(
     "GetGameRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
 
@@ -426,21 +423,19 @@
     "_OptionalGetSnapshotRequestRequestTypeDef",
     {
         "Sections": Sequence[str],
     },
     total=False,
 )
 
-
 class GetSnapshotRequestRequestTypeDef(
     _RequiredGetSnapshotRequestRequestTypeDef, _OptionalGetSnapshotRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredGetStageDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredGetStageDeploymentRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -448,22 +443,20 @@
     "_OptionalGetStageDeploymentRequestRequestTypeDef",
     {
         "DeploymentId": str,
     },
     total=False,
 )
 
-
 class GetStageDeploymentRequestRequestTypeDef(
     _RequiredGetStageDeploymentRequestRequestTypeDef,
     _OptionalGetStageDeploymentRequestRequestTypeDef,
 ):
     pass
 
-
 GetStageRequestRequestTypeDef = TypedDict(
     "GetStageRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -471,24 +464,35 @@
 ImportGameConfigurationSourceTypeDef = TypedDict(
     "ImportGameConfigurationSourceTypeDef",
     {
         "File": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Name": str,
+        "Namespace": str,
+    },
+)
+_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef(
+    _RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
+    _OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListExtensionVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListExtensionVersionsRequestRequestTypeDef",
     {
         "Name": str,
         "Namespace": str,
     },
 )
@@ -497,40 +501,75 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListExtensionVersionsRequestRequestTypeDef(
     _RequiredListExtensionVersionsRequestRequestTypeDef,
     _OptionalListExtensionVersionsRequestRequestTypeDef,
 ):
     pass
 
+ListExtensionsRequestListExtensionsPaginateTypeDef = TypedDict(
+    "ListExtensionsRequestListExtensionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListExtensionsRequestRequestTypeDef = TypedDict(
     "ListExtensionsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListGamesRequestListGamesPaginateTypeDef = TypedDict(
+    "ListGamesRequestListGamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGamesRequestRequestTypeDef = TypedDict(
     "ListGamesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
+    "_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
+    {
+        "GameName": str,
+        "SnapshotId": str,
+    },
+)
+_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
+    "_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef(
+    _RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
+    _OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListGeneratedCodeJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListGeneratedCodeJobsRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
     },
 )
@@ -539,21 +578,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListGeneratedCodeJobsRequestRequestTypeDef(
     _RequiredListGeneratedCodeJobsRequestRequestTypeDef,
     _OptionalListGeneratedCodeJobsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
+    "_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef",
+    {
+        "GameName": str,
+    },
+)
+_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
+    "_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSnapshotsRequestListSnapshotsPaginateTypeDef(
+    _RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef,
+    _OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef,
+):
+    pass
 
 _RequiredListSnapshotsRequestRequestTypeDef = TypedDict(
     "_RequiredListSnapshotsRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
@@ -562,32 +619,51 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListSnapshotsRequestRequestTypeDef(
     _RequiredListSnapshotsRequestRequestTypeDef, _OptionalListSnapshotsRequestRequestTypeDef
 ):
     pass
 
-
 SnapshotSummaryTypeDef = TypedDict(
     "SnapshotSummaryTypeDef",
     {
         "Created": datetime,
         "Description": str,
         "Id": str,
         "LastUpdated": datetime,
     },
     total=False,
 )
 
+_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
+    {
+        "GameName": str,
+        "StageName": str,
+    },
+)
+_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef(
+    _RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
+    _OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListStageDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredListStageDeploymentsRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -596,21 +672,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListStageDeploymentsRequestRequestTypeDef(
     _RequiredListStageDeploymentsRequestRequestTypeDef,
     _OptionalListStageDeploymentsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListStagesRequestListStagesPaginateTypeDef = TypedDict(
+    "_RequiredListStagesRequestListStagesPaginateTypeDef",
+    {
+        "GameName": str,
+    },
+)
+_OptionalListStagesRequestListStagesPaginateTypeDef = TypedDict(
+    "_OptionalListStagesRequestListStagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStagesRequestListStagesPaginateTypeDef(
+    _RequiredListStagesRequestListStagesPaginateTypeDef,
+    _OptionalListStagesRequestListStagesPaginateTypeDef,
+):
+    pass
 
 _RequiredListStagesRequestRequestTypeDef = TypedDict(
     "_RequiredListStagesRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
@@ -619,21 +713,19 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListStagesRequestRequestTypeDef(
     _RequiredListStagesRequestRequestTypeDef, _OptionalListStagesRequestRequestTypeDef
 ):
     pass
 
-
 StageSummaryTypeDef = TypedDict(
     "StageSummaryTypeDef",
     {
         "Description": str,
         "GameKey": str,
         "Name": str,
         "State": StageStateType,
@@ -645,14 +737,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
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
 _RequiredSectionModificationTypeDef = TypedDict(
     "_RequiredSectionModificationTypeDef",
     {
         "Operation": OperationType,
         "Path": str,
         "Section": str,
     },
@@ -661,20 +782,26 @@
     "_OptionalSectionModificationTypeDef",
     {
         "Value": Mapping[str, Any],
     },
     total=False,
 )
 
-
 class SectionModificationTypeDef(
     _RequiredSectionModificationTypeDef, _OptionalSectionModificationTypeDef
 ):
     pass
 
+StartGeneratedCodeJobResultTypeDef = TypedDict(
+    "StartGeneratedCodeJobResultTypeDef",
+    {
+        "GeneratedCodeJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredStartStageDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredStartStageDeploymentRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
         "StageName": str,
@@ -684,22 +811,20 @@
     "_OptionalStartStageDeploymentRequestRequestTypeDef",
     {
         "ClientToken": str,
     },
     total=False,
 )
 
-
 class StartStageDeploymentRequestRequestTypeDef(
     _RequiredStartStageDeploymentRequestRequestTypeDef,
     _OptionalStartStageDeploymentRequestRequestTypeDef,
 ):
     pass
 
-
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -722,21 +847,19 @@
     "_OptionalUpdateGameRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateGameRequestRequestTypeDef(
     _RequiredUpdateGameRequestRequestTypeDef, _OptionalUpdateGameRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSnapshotRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
     },
 )
@@ -744,21 +867,19 @@
     "_OptionalUpdateSnapshotRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateSnapshotRequestRequestTypeDef(
     _RequiredUpdateSnapshotRequestRequestTypeDef, _OptionalUpdateSnapshotRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateStageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStageRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -767,107 +888,72 @@
     {
         "Description": str,
         "Role": str,
     },
     total=False,
 )
 
-
 class UpdateStageRequestRequestTypeDef(
     _RequiredUpdateStageRequestRequestTypeDef, _OptionalUpdateStageRequestRequestTypeDef
 ):
     pass
 
-
-CreateGameResultTypeDef = TypedDict(
-    "CreateGameResultTypeDef",
-    {
-        "Game": GameDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisconnectPlayerResultTypeDef = TypedDict(
-    "DisconnectPlayerResultTypeDef",
-    {
-        "DisconnectFailures": List[str],
-        "DisconnectSuccesses": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportSnapshotResultTypeDef = TypedDict(
-    "ExportSnapshotResultTypeDef",
-    {
-        "S3Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGameResultTypeDef = TypedDict(
-    "GetGameResultTypeDef",
-    {
-        "Game": GameDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetPlayerConnectionStatusResultTypeDef = TypedDict(
     "GetPlayerConnectionStatusResultTypeDef",
     {
         "Connections": List[ConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
+CreateGameResultTypeDef = TypedDict(
+    "CreateGameResultTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Game": GameDetailsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartGeneratedCodeJobResultTypeDef = TypedDict(
-    "StartGeneratedCodeJobResultTypeDef",
+GetGameResultTypeDef = TypedDict(
+    "GetGameResultTypeDef",
     {
-        "GeneratedCodeJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Game": GameDetailsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameResultTypeDef = TypedDict(
     "UpdateGameResultTypeDef",
     {
         "Game": GameDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStageResultTypeDef = TypedDict(
     "CreateStageResultTypeDef",
     {
         "Stage": StageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStageResultTypeDef = TypedDict(
     "GetStageResultTypeDef",
     {
         "Stage": StageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStageResultTypeDef = TypedDict(
     "UpdateStageResultTypeDef",
     {
         "Stage": StageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StageDeploymentDetailsTypeDef = TypedDict(
     "StageDeploymentDetailsTypeDef",
     {
         "Created": datetime,
@@ -894,41 +980,41 @@
     total=False,
 )
 
 GetExtensionResultTypeDef = TypedDict(
     "GetExtensionResultTypeDef",
     {
         "Extension": ExtensionDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExtensionsResultTypeDef = TypedDict(
     "ListExtensionsResultTypeDef",
     {
         "Extensions": List[ExtensionDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExtensionVersionResultTypeDef = TypedDict(
     "GetExtensionVersionResultTypeDef",
     {
         "ExtensionVersion": ExtensionVersionDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExtensionVersionsResultTypeDef = TypedDict(
     "ListExtensionVersionsResultTypeDef",
     {
         "ExtensionVersions": List[ExtensionVersionDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GameConfigurationDetailsTypeDef = TypedDict(
     "GameConfigurationDetailsTypeDef",
     {
         "Created": datetime,
@@ -951,32 +1037,32 @@
 )
 
 ListGamesResultTypeDef = TypedDict(
     "ListGamesResultTypeDef",
     {
         "Games": List[GameSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGeneratedCodeJobResultTypeDef = TypedDict(
     "GetGeneratedCodeJobResultTypeDef",
     {
         "GeneratedCodeJob": GeneratedCodeJobDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGeneratedCodeJobsResultTypeDef = TypedDict(
     "ListGeneratedCodeJobsResultTypeDef",
     {
         "GeneratedCodeJobs": List[GeneratedCodeJobDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartGeneratedCodeJobRequestRequestTypeDef = TypedDict(
     "StartGeneratedCodeJobRequestRequestTypeDef",
     {
         "GameName": str,
@@ -989,158 +1075,29 @@
     "ImportGameConfigurationRequestRequestTypeDef",
     {
         "GameName": str,
         "ImportSource": ImportGameConfigurationSourceTypeDef,
     },
 )
 
-_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
-    {
-        "Name": str,
-        "Namespace": str,
-    },
-)
-_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef(
-    _RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-    _OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListExtensionsRequestListExtensionsPaginateTypeDef = TypedDict(
-    "ListExtensionsRequestListExtensionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListGamesRequestListGamesPaginateTypeDef = TypedDict(
-    "ListGamesRequestListGamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
-    "_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
-    {
-        "GameName": str,
-        "SnapshotId": str,
-    },
-)
-_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
-    "_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef(
-    _RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-    _OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
-    "_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    {
-        "GameName": str,
-    },
-)
-_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
-    "_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSnapshotsRequestListSnapshotsPaginateTypeDef(
-    _RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    _OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
-    {
-        "GameName": str,
-        "StageName": str,
-    },
-)
-_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef(
-    _RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-    _OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStagesRequestListStagesPaginateTypeDef = TypedDict(
-    "_RequiredListStagesRequestListStagesPaginateTypeDef",
-    {
-        "GameName": str,
-    },
-)
-_OptionalListStagesRequestListStagesPaginateTypeDef = TypedDict(
-    "_OptionalListStagesRequestListStagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStagesRequestListStagesPaginateTypeDef(
-    _RequiredListStagesRequestListStagesPaginateTypeDef,
-    _OptionalListStagesRequestListStagesPaginateTypeDef,
-):
-    pass
-
-
 ListSnapshotsResultTypeDef = TypedDict(
     "ListSnapshotsResultTypeDef",
     {
         "NextToken": str,
         "Snapshots": List[SnapshotSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStagesResultTypeDef = TypedDict(
     "ListStagesResultTypeDef",
     {
         "NextToken": str,
         "Stages": List[StageSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateGameConfigurationRequestRequestTypeDef",
     {
         "GameName": str,
@@ -1148,75 +1105,75 @@
     },
 )
 
 GetStageDeploymentResultTypeDef = TypedDict(
     "GetStageDeploymentResultTypeDef",
     {
         "StageDeployment": StageDeploymentDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartStageDeploymentResultTypeDef = TypedDict(
     "StartStageDeploymentResultTypeDef",
     {
         "StageDeployment": StageDeploymentDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStageDeploymentsResultTypeDef = TypedDict(
     "ListStageDeploymentsResultTypeDef",
     {
         "NextToken": str,
         "StageDeployments": List[StageDeploymentSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGameConfigurationResultTypeDef = TypedDict(
     "GetGameConfigurationResultTypeDef",
     {
         "GameConfiguration": GameConfigurationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportGameConfigurationResultTypeDef = TypedDict(
     "ImportGameConfigurationResultTypeDef",
     {
         "GameConfiguration": GameConfigurationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameConfigurationResultTypeDef = TypedDict(
     "UpdateGameConfigurationResultTypeDef",
     {
         "GameConfiguration": GameConfigurationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResultTypeDef = TypedDict(
     "CreateSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotResultTypeDef = TypedDict(
     "GetSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSnapshotResultTypeDef = TypedDict(
     "UpdateSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks/type_defs.pyi` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -28,27 +28,29 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ConnectionTypeDef",
     "CreateGameRequestRequestTypeDef",
     "GameDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "CreateStageRequestRequestTypeDef",
     "StageDetailsTypeDef",
     "DeleteGameRequestRequestTypeDef",
     "DeleteStageRequestRequestTypeDef",
     "DeploymentResultTypeDef",
     "DisconnectPlayerRequestRequestTypeDef",
+    "DisconnectPlayerResultTypeDef",
     "ExportSnapshotRequestRequestTypeDef",
+    "ExportSnapshotResultTypeDef",
     "ExtensionDetailsTypeDef",
     "ExtensionVersionDetailsTypeDef",
     "SectionTypeDef",
     "GameSummaryTypeDef",
     "GeneratedCodeJobDetailsTypeDef",
     "GeneratorTypeDef",
     "GetExtensionRequestRequestTypeDef",
@@ -57,39 +59,45 @@
     "GetGameRequestRequestTypeDef",
     "GetGeneratedCodeJobRequestRequestTypeDef",
     "GetPlayerConnectionStatusRequestRequestTypeDef",
     "GetSnapshotRequestRequestTypeDef",
     "GetStageDeploymentRequestRequestTypeDef",
     "GetStageRequestRequestTypeDef",
     "ImportGameConfigurationSourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
     "ListExtensionVersionsRequestRequestTypeDef",
+    "ListExtensionsRequestListExtensionsPaginateTypeDef",
     "ListExtensionsRequestRequestTypeDef",
+    "ListGamesRequestListGamesPaginateTypeDef",
     "ListGamesRequestRequestTypeDef",
+    "ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
     "ListGeneratedCodeJobsRequestRequestTypeDef",
+    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
     "ListSnapshotsRequestRequestTypeDef",
     "SnapshotSummaryTypeDef",
+    "ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
     "ListStageDeploymentsRequestRequestTypeDef",
+    "ListStagesRequestListStagesPaginateTypeDef",
     "ListStagesRequestRequestTypeDef",
     "StageSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SectionModificationTypeDef",
+    "StartGeneratedCodeJobResultTypeDef",
     "StartStageDeploymentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateGameRequestRequestTypeDef",
     "UpdateSnapshotRequestRequestTypeDef",
     "UpdateStageRequestRequestTypeDef",
+    "GetPlayerConnectionStatusResultTypeDef",
     "CreateGameResultTypeDef",
-    "DisconnectPlayerResultTypeDef",
-    "ExportSnapshotResultTypeDef",
     "GetGameResultTypeDef",
-    "GetPlayerConnectionStatusResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "StartGeneratedCodeJobResultTypeDef",
     "UpdateGameResultTypeDef",
     "CreateStageResultTypeDef",
     "GetStageResultTypeDef",
     "UpdateStageResultTypeDef",
     "StageDeploymentDetailsTypeDef",
     "StageDeploymentSummaryTypeDef",
     "GetExtensionResultTypeDef",
@@ -99,21 +107,14 @@
     "GameConfigurationDetailsTypeDef",
     "SnapshotDetailsTypeDef",
     "ListGamesResultTypeDef",
     "GetGeneratedCodeJobResultTypeDef",
     "ListGeneratedCodeJobsResultTypeDef",
     "StartGeneratedCodeJobRequestRequestTypeDef",
     "ImportGameConfigurationRequestRequestTypeDef",
-    "ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
-    "ListExtensionsRequestListExtensionsPaginateTypeDef",
-    "ListGamesRequestListGamesPaginateTypeDef",
-    "ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
-    "ListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    "ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
-    "ListStagesRequestListStagesPaginateTypeDef",
     "ListSnapshotsResultTypeDef",
     "ListStagesResultTypeDef",
     "UpdateGameConfigurationRequestRequestTypeDef",
     "GetStageDeploymentResultTypeDef",
     "StartStageDeploymentResultTypeDef",
     "ListStageDeploymentsResultTypeDef",
     "GetGameConfigurationResultTypeDef",
@@ -145,19 +146,21 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateGameRequestRequestTypeDef(
     _RequiredCreateGameRequestRequestTypeDef, _OptionalCreateGameRequestRequestTypeDef
 ):
     pass
 
+
 GameDetailsTypeDef = TypedDict(
     "GameDetailsTypeDef",
     {
         "Arn": str,
         "Created": datetime,
         "Description": str,
         "EnableTerminationProtection": bool,
@@ -165,44 +168,35 @@
         "Name": str,
         "State": GameStateType,
         "Tags": Dict[str, str],
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
 _RequiredCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSnapshotRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
 _OptionalCreateSnapshotRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSnapshotRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class CreateSnapshotRequestRequestTypeDef(
     _RequiredCreateSnapshotRequestRequestTypeDef, _OptionalCreateSnapshotRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateStageRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStageRequestRequestTypeDef",
     {
         "GameName": str,
         "Role": str,
         "StageName": str,
     },
@@ -213,19 +207,21 @@
         "ClientToken": str,
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateStageRequestRequestTypeDef(
     _RequiredCreateStageRequestRequestTypeDef, _OptionalCreateStageRequestRequestTypeDef
 ):
     pass
 
+
 StageDetailsTypeDef = TypedDict(
     "StageDetailsTypeDef",
     {
         "Arn": str,
         "Created": datetime,
         "Description": str,
         "GameKey": str,
@@ -268,22 +264,39 @@
     {
         "GameName": str,
         "PlayerId": str,
         "StageName": str,
     },
 )
 
+DisconnectPlayerResultTypeDef = TypedDict(
+    "DisconnectPlayerResultTypeDef",
+    {
+        "DisconnectFailures": List[str],
+        "DisconnectSuccesses": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportSnapshotRequestRequestTypeDef = TypedDict(
     "ExportSnapshotRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
     },
 )
 
+ExportSnapshotResultTypeDef = TypedDict(
+    "ExportSnapshotResultTypeDef",
+    {
+        "S3Url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExtensionDetailsTypeDef = TypedDict(
     "ExtensionDetailsTypeDef",
     {
         "Description": str,
         "Name": str,
         "Namespace": str,
     },
@@ -371,20 +384,22 @@
     "_OptionalGetGameConfigurationRequestRequestTypeDef",
     {
         "Sections": Sequence[str],
     },
     total=False,
 )
 
+
 class GetGameConfigurationRequestRequestTypeDef(
     _RequiredGetGameConfigurationRequestRequestTypeDef,
     _OptionalGetGameConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetGameRequestRequestTypeDef = TypedDict(
     "GetGameRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
 
@@ -417,19 +432,21 @@
     "_OptionalGetSnapshotRequestRequestTypeDef",
     {
         "Sections": Sequence[str],
     },
     total=False,
 )
 
+
 class GetSnapshotRequestRequestTypeDef(
     _RequiredGetSnapshotRequestRequestTypeDef, _OptionalGetSnapshotRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredGetStageDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredGetStageDeploymentRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -437,20 +454,22 @@
     "_OptionalGetStageDeploymentRequestRequestTypeDef",
     {
         "DeploymentId": str,
     },
     total=False,
 )
 
+
 class GetStageDeploymentRequestRequestTypeDef(
     _RequiredGetStageDeploymentRequestRequestTypeDef,
     _OptionalGetStageDeploymentRequestRequestTypeDef,
 ):
     pass
 
+
 GetStageRequestRequestTypeDef = TypedDict(
     "GetStageRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -458,24 +477,37 @@
 ImportGameConfigurationSourceTypeDef = TypedDict(
     "ImportGameConfigurationSourceTypeDef",
     {
         "File": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Name": str,
+        "Namespace": str,
+    },
+)
+_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef(
+    _RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
+    _OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListExtensionVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListExtensionVersionsRequestRequestTypeDef",
     {
         "Name": str,
         "Namespace": str,
     },
 )
@@ -484,38 +516,79 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListExtensionVersionsRequestRequestTypeDef(
     _RequiredListExtensionVersionsRequestRequestTypeDef,
     _OptionalListExtensionVersionsRequestRequestTypeDef,
 ):
     pass
 
+
+ListExtensionsRequestListExtensionsPaginateTypeDef = TypedDict(
+    "ListExtensionsRequestListExtensionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListExtensionsRequestRequestTypeDef = TypedDict(
     "ListExtensionsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListGamesRequestListGamesPaginateTypeDef = TypedDict(
+    "ListGamesRequestListGamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGamesRequestRequestTypeDef = TypedDict(
     "ListGamesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
+    "_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
+    {
+        "GameName": str,
+        "SnapshotId": str,
+    },
+)
+_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
+    "_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef(
+    _RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
+    _OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGeneratedCodeJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListGeneratedCodeJobsRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
     },
 )
@@ -524,20 +597,44 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListGeneratedCodeJobsRequestRequestTypeDef(
     _RequiredListGeneratedCodeJobsRequestRequestTypeDef,
     _OptionalListGeneratedCodeJobsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
+    "_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef",
+    {
+        "GameName": str,
+    },
+)
+_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
+    "_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSnapshotsRequestListSnapshotsPaginateTypeDef(
+    _RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef,
+    _OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSnapshotsRequestRequestTypeDef = TypedDict(
     "_RequiredListSnapshotsRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
 _OptionalListSnapshotsRequestRequestTypeDef = TypedDict(
@@ -545,30 +642,55 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListSnapshotsRequestRequestTypeDef(
     _RequiredListSnapshotsRequestRequestTypeDef, _OptionalListSnapshotsRequestRequestTypeDef
 ):
     pass
 
+
 SnapshotSummaryTypeDef = TypedDict(
     "SnapshotSummaryTypeDef",
     {
         "Created": datetime,
         "Description": str,
         "Id": str,
         "LastUpdated": datetime,
     },
     total=False,
 )
 
+_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
+    {
+        "GameName": str,
+        "StageName": str,
+    },
+)
+_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef(
+    _RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
+    _OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStageDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredListStageDeploymentsRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -577,20 +699,44 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListStageDeploymentsRequestRequestTypeDef(
     _RequiredListStageDeploymentsRequestRequestTypeDef,
     _OptionalListStageDeploymentsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListStagesRequestListStagesPaginateTypeDef = TypedDict(
+    "_RequiredListStagesRequestListStagesPaginateTypeDef",
+    {
+        "GameName": str,
+    },
+)
+_OptionalListStagesRequestListStagesPaginateTypeDef = TypedDict(
+    "_OptionalListStagesRequestListStagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStagesRequestListStagesPaginateTypeDef(
+    _RequiredListStagesRequestListStagesPaginateTypeDef,
+    _OptionalListStagesRequestListStagesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStagesRequestRequestTypeDef = TypedDict(
     "_RequiredListStagesRequestRequestTypeDef",
     {
         "GameName": str,
     },
 )
 _OptionalListStagesRequestRequestTypeDef = TypedDict(
@@ -598,19 +744,21 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListStagesRequestRequestTypeDef(
     _RequiredListStagesRequestRequestTypeDef, _OptionalListStagesRequestRequestTypeDef
 ):
     pass
 
+
 StageSummaryTypeDef = TypedDict(
     "StageSummaryTypeDef",
     {
         "Description": str,
         "GameKey": str,
         "Name": str,
         "State": StageStateType,
@@ -622,14 +770,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
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
 _RequiredSectionModificationTypeDef = TypedDict(
     "_RequiredSectionModificationTypeDef",
     {
         "Operation": OperationType,
         "Path": str,
         "Section": str,
     },
@@ -638,19 +815,29 @@
     "_OptionalSectionModificationTypeDef",
     {
         "Value": Mapping[str, Any],
     },
     total=False,
 )
 
+
 class SectionModificationTypeDef(
     _RequiredSectionModificationTypeDef, _OptionalSectionModificationTypeDef
 ):
     pass
 
+
+StartGeneratedCodeJobResultTypeDef = TypedDict(
+    "StartGeneratedCodeJobResultTypeDef",
+    {
+        "GeneratedCodeJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartStageDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredStartStageDeploymentRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
         "StageName": str,
     },
@@ -659,20 +846,22 @@
     "_OptionalStartStageDeploymentRequestRequestTypeDef",
     {
         "ClientToken": str,
     },
     total=False,
 )
 
+
 class StartStageDeploymentRequestRequestTypeDef(
     _RequiredStartStageDeploymentRequestRequestTypeDef,
     _OptionalStartStageDeploymentRequestRequestTypeDef,
 ):
     pass
 
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -695,19 +884,21 @@
     "_OptionalUpdateGameRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateGameRequestRequestTypeDef(
     _RequiredUpdateGameRequestRequestTypeDef, _OptionalUpdateGameRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSnapshotRequestRequestTypeDef",
     {
         "GameName": str,
         "SnapshotId": str,
     },
 )
@@ -715,19 +906,21 @@
     "_OptionalUpdateSnapshotRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateSnapshotRequestRequestTypeDef(
     _RequiredUpdateSnapshotRequestRequestTypeDef, _OptionalUpdateSnapshotRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateStageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStageRequestRequestTypeDef",
     {
         "GameName": str,
         "StageName": str,
     },
 )
@@ -736,105 +929,74 @@
     {
         "Description": str,
         "Role": str,
     },
     total=False,
 )
 
+
 class UpdateStageRequestRequestTypeDef(
     _RequiredUpdateStageRequestRequestTypeDef, _OptionalUpdateStageRequestRequestTypeDef
 ):
     pass
 
-CreateGameResultTypeDef = TypedDict(
-    "CreateGameResultTypeDef",
-    {
-        "Game": GameDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisconnectPlayerResultTypeDef = TypedDict(
-    "DisconnectPlayerResultTypeDef",
-    {
-        "DisconnectFailures": List[str],
-        "DisconnectSuccesses": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportSnapshotResultTypeDef = TypedDict(
-    "ExportSnapshotResultTypeDef",
-    {
-        "S3Url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetGameResultTypeDef = TypedDict(
-    "GetGameResultTypeDef",
-    {
-        "Game": GameDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 GetPlayerConnectionStatusResultTypeDef = TypedDict(
     "GetPlayerConnectionStatusResultTypeDef",
     {
         "Connections": List[ConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
+CreateGameResultTypeDef = TypedDict(
+    "CreateGameResultTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Game": GameDetailsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartGeneratedCodeJobResultTypeDef = TypedDict(
-    "StartGeneratedCodeJobResultTypeDef",
+GetGameResultTypeDef = TypedDict(
+    "GetGameResultTypeDef",
     {
-        "GeneratedCodeJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Game": GameDetailsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameResultTypeDef = TypedDict(
     "UpdateGameResultTypeDef",
     {
         "Game": GameDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStageResultTypeDef = TypedDict(
     "CreateStageResultTypeDef",
     {
         "Stage": StageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStageResultTypeDef = TypedDict(
     "GetStageResultTypeDef",
     {
         "Stage": StageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStageResultTypeDef = TypedDict(
     "UpdateStageResultTypeDef",
     {
         "Stage": StageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StageDeploymentDetailsTypeDef = TypedDict(
     "StageDeploymentDetailsTypeDef",
     {
         "Created": datetime,
@@ -861,41 +1023,41 @@
     total=False,
 )
 
 GetExtensionResultTypeDef = TypedDict(
     "GetExtensionResultTypeDef",
     {
         "Extension": ExtensionDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExtensionsResultTypeDef = TypedDict(
     "ListExtensionsResultTypeDef",
     {
         "Extensions": List[ExtensionDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExtensionVersionResultTypeDef = TypedDict(
     "GetExtensionVersionResultTypeDef",
     {
         "ExtensionVersion": ExtensionVersionDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExtensionVersionsResultTypeDef = TypedDict(
     "ListExtensionVersionsResultTypeDef",
     {
         "ExtensionVersions": List[ExtensionVersionDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GameConfigurationDetailsTypeDef = TypedDict(
     "GameConfigurationDetailsTypeDef",
     {
         "Created": datetime,
@@ -918,32 +1080,32 @@
 )
 
 ListGamesResultTypeDef = TypedDict(
     "ListGamesResultTypeDef",
     {
         "Games": List[GameSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGeneratedCodeJobResultTypeDef = TypedDict(
     "GetGeneratedCodeJobResultTypeDef",
     {
         "GeneratedCodeJob": GeneratedCodeJobDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGeneratedCodeJobsResultTypeDef = TypedDict(
     "ListGeneratedCodeJobsResultTypeDef",
     {
         "GeneratedCodeJobs": List[GeneratedCodeJobDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartGeneratedCodeJobRequestRequestTypeDef = TypedDict(
     "StartGeneratedCodeJobRequestRequestTypeDef",
     {
         "GameName": str,
@@ -956,148 +1118,29 @@
     "ImportGameConfigurationRequestRequestTypeDef",
     {
         "GameName": str,
         "ImportSource": ImportGameConfigurationSourceTypeDef,
     },
 )
 
-_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
-    {
-        "Name": str,
-        "Namespace": str,
-    },
-)
-_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef(
-    _RequiredListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-    _OptionalListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-):
-    pass
-
-ListExtensionsRequestListExtensionsPaginateTypeDef = TypedDict(
-    "ListExtensionsRequestListExtensionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListGamesRequestListGamesPaginateTypeDef = TypedDict(
-    "ListGamesRequestListGamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
-    "_RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
-    {
-        "GameName": str,
-        "SnapshotId": str,
-    },
-)
-_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef = TypedDict(
-    "_OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef(
-    _RequiredListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-    _OptionalListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-):
-    pass
-
-_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
-    "_RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    {
-        "GameName": str,
-    },
-)
-_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef = TypedDict(
-    "_OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSnapshotsRequestListSnapshotsPaginateTypeDef(
-    _RequiredListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    _OptionalListSnapshotsRequestListSnapshotsPaginateTypeDef,
-):
-    pass
-
-_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
-    {
-        "GameName": str,
-        "StageName": str,
-    },
-)
-_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef(
-    _RequiredListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-    _OptionalListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-):
-    pass
-
-_RequiredListStagesRequestListStagesPaginateTypeDef = TypedDict(
-    "_RequiredListStagesRequestListStagesPaginateTypeDef",
-    {
-        "GameName": str,
-    },
-)
-_OptionalListStagesRequestListStagesPaginateTypeDef = TypedDict(
-    "_OptionalListStagesRequestListStagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStagesRequestListStagesPaginateTypeDef(
-    _RequiredListStagesRequestListStagesPaginateTypeDef,
-    _OptionalListStagesRequestListStagesPaginateTypeDef,
-):
-    pass
-
 ListSnapshotsResultTypeDef = TypedDict(
     "ListSnapshotsResultTypeDef",
     {
         "NextToken": str,
         "Snapshots": List[SnapshotSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStagesResultTypeDef = TypedDict(
     "ListStagesResultTypeDef",
     {
         "NextToken": str,
         "Stages": List[StageSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateGameConfigurationRequestRequestTypeDef",
     {
         "GameName": str,
@@ -1105,75 +1148,75 @@
     },
 )
 
 GetStageDeploymentResultTypeDef = TypedDict(
     "GetStageDeploymentResultTypeDef",
     {
         "StageDeployment": StageDeploymentDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartStageDeploymentResultTypeDef = TypedDict(
     "StartStageDeploymentResultTypeDef",
     {
         "StageDeployment": StageDeploymentDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStageDeploymentsResultTypeDef = TypedDict(
     "ListStageDeploymentsResultTypeDef",
     {
         "NextToken": str,
         "StageDeployments": List[StageDeploymentSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGameConfigurationResultTypeDef = TypedDict(
     "GetGameConfigurationResultTypeDef",
     {
         "GameConfiguration": GameConfigurationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportGameConfigurationResultTypeDef = TypedDict(
     "ImportGameConfigurationResultTypeDef",
     {
         "GameConfiguration": GameConfigurationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameConfigurationResultTypeDef = TypedDict(
     "UpdateGameConfigurationResultTypeDef",
     {
         "GameConfiguration": GameConfigurationDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResultTypeDef = TypedDict(
     "CreateSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotResultTypeDef = TypedDict(
     "GetSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSnapshotResultTypeDef = TypedDict(
     "UpdateSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/PKG-INFO` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-gamesparks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GameSparks 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GameSparks 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-gamesparks"></a>
 
 # types-aiobotocore-gamesparks
 
 [![PyPI - types-aiobotocore-gamesparks](https://img.shields.io/pypi/v/types-aiobotocore-gamesparks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamesparks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-gamesparks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamesparks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-gamesparks?color=blue)](https://pypistats.org/packages/types-aiobotocore-gamesparks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GameSparks 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks)
+[aiobotocore.GameSparks 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamesparks.html#GameSparks)
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
 [types-aiobotocore-gamesparks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamesparks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,23 +350,24 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_gamesparks.type_defs import (
     ConnectionTypeDef,
     CreateGameRequestRequestTypeDef,
     GameDetailsTypeDef,
-    ResponseMetadataTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateStageRequestRequestTypeDef,
     StageDetailsTypeDef,
     DeleteGameRequestRequestTypeDef,
     DeleteStageRequestRequestTypeDef,
     DeploymentResultTypeDef,
     DisconnectPlayerRequestRequestTypeDef,
+    DisconnectPlayerResultTypeDef,
     ExportSnapshotRequestRequestTypeDef,
+    ExportSnapshotResultTypeDef,
     ExtensionDetailsTypeDef,
     ExtensionVersionDetailsTypeDef,
     SectionTypeDef,
     GameSummaryTypeDef,
     GeneratedCodeJobDetailsTypeDef,
     GeneratorTypeDef,
     GetExtensionRequestRequestTypeDef,
@@ -375,39 +376,45 @@
     GetGameRequestRequestTypeDef,
     GetGeneratedCodeJobRequestRequestTypeDef,
     GetPlayerConnectionStatusRequestRequestTypeDef,
     GetSnapshotRequestRequestTypeDef,
     GetStageDeploymentRequestRequestTypeDef,
     GetStageRequestRequestTypeDef,
     ImportGameConfigurationSourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
     ListExtensionVersionsRequestRequestTypeDef,
+    ListExtensionsRequestListExtensionsPaginateTypeDef,
     ListExtensionsRequestRequestTypeDef,
+    ListGamesRequestListGamesPaginateTypeDef,
     ListGamesRequestRequestTypeDef,
+    ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
     ListGeneratedCodeJobsRequestRequestTypeDef,
+    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
     ListSnapshotsRequestRequestTypeDef,
     SnapshotSummaryTypeDef,
+    ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
     ListStageDeploymentsRequestRequestTypeDef,
+    ListStagesRequestListStagesPaginateTypeDef,
     ListStagesRequestRequestTypeDef,
     StageSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SectionModificationTypeDef,
+    StartGeneratedCodeJobResultTypeDef,
     StartStageDeploymentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateGameRequestRequestTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     UpdateStageRequestRequestTypeDef,
+    GetPlayerConnectionStatusResultTypeDef,
     CreateGameResultTypeDef,
-    DisconnectPlayerResultTypeDef,
-    ExportSnapshotResultTypeDef,
     GetGameResultTypeDef,
-    GetPlayerConnectionStatusResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    StartGeneratedCodeJobResultTypeDef,
     UpdateGameResultTypeDef,
     CreateStageResultTypeDef,
     GetStageResultTypeDef,
     UpdateStageResultTypeDef,
     StageDeploymentDetailsTypeDef,
     StageDeploymentSummaryTypeDef,
     GetExtensionResultTypeDef,
@@ -417,21 +424,14 @@
     GameConfigurationDetailsTypeDef,
     SnapshotDetailsTypeDef,
     ListGamesResultTypeDef,
     GetGeneratedCodeJobResultTypeDef,
     ListGeneratedCodeJobsResultTypeDef,
     StartGeneratedCodeJobRequestRequestTypeDef,
     ImportGameConfigurationRequestRequestTypeDef,
-    ListExtensionVersionsRequestListExtensionVersionsPaginateTypeDef,
-    ListExtensionsRequestListExtensionsPaginateTypeDef,
-    ListGamesRequestListGamesPaginateTypeDef,
-    ListGeneratedCodeJobsRequestListGeneratedCodeJobsPaginateTypeDef,
-    ListSnapshotsRequestListSnapshotsPaginateTypeDef,
-    ListStageDeploymentsRequestListStageDeploymentsPaginateTypeDef,
-    ListStagesRequestListStagesPaginateTypeDef,
     ListSnapshotsResultTypeDef,
     ListStagesResultTypeDef,
     UpdateGameConfigurationRequestRequestTypeDef,
     GetStageDeploymentResultTypeDef,
     StartStageDeploymentResultTypeDef,
     ListStageDeploymentsResultTypeDef,
     GetGameConfigurationResultTypeDef,
@@ -450,43 +450,43 @@
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

### Comparing `types-aiobotocore-gamesparks-2.5.0.post1/types_aiobotocore_gamesparks.egg-info/SOURCES.txt` & `types-aiobotocore-gamesparks-2.5.1/types_aiobotocore_gamesparks.egg-info/SOURCES.txt`

 * *Files identical despite different names*

