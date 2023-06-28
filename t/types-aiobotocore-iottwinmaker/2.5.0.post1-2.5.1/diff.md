# Comparing `tmp/types-aiobotocore-iottwinmaker-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iottwinmaker-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iottwinmaker-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:48 2023, max compression
+gzip compressed data, was "types-aiobotocore-iottwinmaker-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1.tar` & `types-aiobotocore-iottwinmaker-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.955319 types-aiobotocore-iottwinmaker-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16583 2023-03-11 12:26:48.955319 types-aiobotocore-iottwinmaker-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14992 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:48.955319 types-aiobotocore-iottwinmaker-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.951319 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/
--rw-r--r--   0 runner    (1001) docker     (123)      482 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      481 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26517 2023-03-11 12:16:34.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    26475 2023-03-11 12:16:34.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9285 2023-03-11 12:16:34.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9283 2023-03-11 12:16:34.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    43099 2023-03-11 12:16:35.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    43026 2023-03-11 12:16:35.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:32.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.955319 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16583 2023-03-11 12:26:48.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-03-11 12:26:48.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:48.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:48.000000 types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.442157 types-aiobotocore-iottwinmaker-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16628 2023-06-28 01:43:40.442157 types-aiobotocore-iottwinmaker-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15043 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.442157 types-aiobotocore-iottwinmaker-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.442157 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/
+-rw-r--r--   0 runner    (1001) docker     (123)      482 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      481 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26613 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26571 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9569 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9567 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    43559 2023-06-28 01:33:13.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43486 2023-06-28 01:33:12.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:11.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.442157 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16628 2023-06-28 01:43:40.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 01:43:40.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:40.000000 types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/LICENSE` & `types-aiobotocore-iottwinmaker-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iottwinmaker-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iottwinmaker
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTTwinMaker 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTTwinMaker 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iottwinmaker"></a>
 
 # types-aiobotocore-iottwinmaker
 
 [![PyPI - types-aiobotocore-iottwinmaker](https://img.shields.io/pypi/v/types-aiobotocore-iottwinmaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iottwinmaker)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iottwinmaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iottwinmaker)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iottwinmaker?color=blue)](https://pypistats.org/packages/types-aiobotocore-iottwinmaker)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTTwinMaker 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker)
+[aiobotocore.IoTTwinMaker 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker)
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
 [types-aiobotocore-iottwinmaker docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/).
 
 See how it helps to find and fix potential bugs:
 
@@ -281,14 +281,15 @@
     OrderByTimeType,
     OrderType,
     ParentEntityUpdateTypeType,
     PricingModeType,
     PricingTierType,
     PropertyGroupUpdateTypeType,
     PropertyUpdateTypeType,
+    SceneErrorCodeType,
     ScopeType,
     StateType,
     SyncJobStateType,
     SyncResourceStateType,
     SyncResourceTypeType,
     TypeType,
     UpdateReasonType,
@@ -308,89 +309,90 @@
 ### Typed dictionaries
 
 `types_aiobotocore_iottwinmaker.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iottwinmaker.type_defs import (
-    ResponseMetadataTypeDef,
     BundleInformationTypeDef,
     ColumnDescriptionTypeDef,
     ComponentPropertyGroupRequestTypeDef,
     ComponentPropertyGroupResponseTypeDef,
     PropertyDefinitionRequestTypeDef,
     PropertyGroupRequestTypeDef,
+    CreateComponentTypeResponseTypeDef,
+    CreateEntityResponseTypeDef,
     CreateSceneRequestRequestTypeDef,
+    CreateSceneResponseTypeDef,
     CreateSyncJobRequestRequestTypeDef,
+    CreateSyncJobResponseTypeDef,
     CreateWorkspaceRequestRequestTypeDef,
+    CreateWorkspaceResponseTypeDef,
     LambdaFunctionTypeDef,
     RelationshipTypeDef,
     RelationshipValueTypeDef,
     DeleteComponentTypeRequestRequestTypeDef,
+    DeleteComponentTypeResponseTypeDef,
     DeleteEntityRequestRequestTypeDef,
+    DeleteEntityResponseTypeDef,
     DeleteSceneRequestRequestTypeDef,
     DeleteSyncJobRequestRequestTypeDef,
+    DeleteSyncJobResponseTypeDef,
     DeleteWorkspaceRequestRequestTypeDef,
     EntityPropertyReferenceTypeDef,
     ErrorDetailsTypeDef,
     ExecuteQueryRequestRequestTypeDef,
     RowTypeDef,
     GetComponentTypeRequestRequestTypeDef,
     PropertyDefinitionResponseTypeDef,
     PropertyGroupResponseTypeDef,
     GetEntityRequestRequestTypeDef,
     InterpolationParametersTypeDef,
     PropertyFilterTypeDef,
     GetSceneRequestRequestTypeDef,
+    SceneErrorTypeDef,
     GetSyncJobRequestRequestTypeDef,
     GetWorkspaceRequestRequestTypeDef,
+    GetWorkspaceResponseTypeDef,
     ListComponentTypesFilterTypeDef,
     ListEntitiesFilterTypeDef,
     ListScenesRequestRequestTypeDef,
     SceneSummaryTypeDef,
     ListSyncJobsRequestRequestTypeDef,
     SyncResourceFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWorkspacesRequestRequestTypeDef,
     WorkspaceSummaryTypeDef,
     OrderByTypeDef,
     ParentEntityUpdateRequestTypeDef,
     PropertyValueTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    UpdatePricingPlanRequestRequestTypeDef,
-    UpdateSceneRequestRequestTypeDef,
-    UpdateWorkspaceRequestRequestTypeDef,
-    CreateComponentTypeResponseTypeDef,
-    CreateEntityResponseTypeDef,
-    CreateSceneResponseTypeDef,
-    CreateSyncJobResponseTypeDef,
-    CreateWorkspaceResponseTypeDef,
-    DeleteComponentTypeResponseTypeDef,
-    DeleteEntityResponseTypeDef,
-    DeleteSyncJobResponseTypeDef,
-    GetSceneResponseTypeDef,
-    GetWorkspaceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateComponentTypeResponseTypeDef,
     UpdateEntityResponseTypeDef,
+    UpdatePricingPlanRequestRequestTypeDef,
+    UpdateSceneRequestRequestTypeDef,
     UpdateSceneResponseTypeDef,
+    UpdateWorkspaceRequestRequestTypeDef,
     UpdateWorkspaceResponseTypeDef,
     PricingPlanTypeDef,
     PropertyRequestTypeDef,
     DataConnectorTypeDef,
     DataTypeTypeDef,
     DataValueTypeDef,
     PropertyLatestValueTypeDef,
     StatusTypeDef,
     SyncJobStatusTypeDef,
     SyncResourceStatusTypeDef,
     ExecuteQueryResponseTypeDef,
     PropertyResponseTypeDef,
     GetPropertyValueHistoryRequestRequestTypeDef,
+    GetSceneResponseTypeDef,
     ListComponentTypesRequestRequestTypeDef,
     ListEntitiesRequestRequestTypeDef,
     ListScenesResponseTypeDef,
     ListSyncResourcesRequestRequestTypeDef,
     ListWorkspacesResponseTypeDef,
     TabularConditionsTypeDef,
     PropertyValueEntryTypeDef,
@@ -423,54 +425,54 @@
     ListSyncResourcesResponseTypeDef,
     GetEntityResponseTypeDef,
     BatchPutPropertyErrorEntryTypeDef,
     BatchPutPropertyValuesResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> BundleInformationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/README.md` & `types-aiobotocore-iottwinmaker-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iottwinmaker"></a>
 
 # types-aiobotocore-iottwinmaker
 
 [![PyPI - types-aiobotocore-iottwinmaker](https://img.shields.io/pypi/v/types-aiobotocore-iottwinmaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iottwinmaker)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iottwinmaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iottwinmaker)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iottwinmaker?color=blue)](https://pypistats.org/packages/types-aiobotocore-iottwinmaker)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTTwinMaker 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker)
+[aiobotocore.IoTTwinMaker 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker)
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
 [types-aiobotocore-iottwinmaker docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/).
 
 See how it helps to find and fix potential bugs:
 
@@ -248,14 +248,15 @@
     OrderByTimeType,
     OrderType,
     ParentEntityUpdateTypeType,
     PricingModeType,
     PricingTierType,
     PropertyGroupUpdateTypeType,
     PropertyUpdateTypeType,
+    SceneErrorCodeType,
     ScopeType,
     StateType,
     SyncJobStateType,
     SyncResourceStateType,
     SyncResourceTypeType,
     TypeType,
     UpdateReasonType,
@@ -275,89 +276,90 @@
 ### Typed dictionaries
 
 `types_aiobotocore_iottwinmaker.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iottwinmaker.type_defs import (
-    ResponseMetadataTypeDef,
     BundleInformationTypeDef,
     ColumnDescriptionTypeDef,
     ComponentPropertyGroupRequestTypeDef,
     ComponentPropertyGroupResponseTypeDef,
     PropertyDefinitionRequestTypeDef,
     PropertyGroupRequestTypeDef,
+    CreateComponentTypeResponseTypeDef,
+    CreateEntityResponseTypeDef,
     CreateSceneRequestRequestTypeDef,
+    CreateSceneResponseTypeDef,
     CreateSyncJobRequestRequestTypeDef,
+    CreateSyncJobResponseTypeDef,
     CreateWorkspaceRequestRequestTypeDef,
+    CreateWorkspaceResponseTypeDef,
     LambdaFunctionTypeDef,
     RelationshipTypeDef,
     RelationshipValueTypeDef,
     DeleteComponentTypeRequestRequestTypeDef,
+    DeleteComponentTypeResponseTypeDef,
     DeleteEntityRequestRequestTypeDef,
+    DeleteEntityResponseTypeDef,
     DeleteSceneRequestRequestTypeDef,
     DeleteSyncJobRequestRequestTypeDef,
+    DeleteSyncJobResponseTypeDef,
     DeleteWorkspaceRequestRequestTypeDef,
     EntityPropertyReferenceTypeDef,
     ErrorDetailsTypeDef,
     ExecuteQueryRequestRequestTypeDef,
     RowTypeDef,
     GetComponentTypeRequestRequestTypeDef,
     PropertyDefinitionResponseTypeDef,
     PropertyGroupResponseTypeDef,
     GetEntityRequestRequestTypeDef,
     InterpolationParametersTypeDef,
     PropertyFilterTypeDef,
     GetSceneRequestRequestTypeDef,
+    SceneErrorTypeDef,
     GetSyncJobRequestRequestTypeDef,
     GetWorkspaceRequestRequestTypeDef,
+    GetWorkspaceResponseTypeDef,
     ListComponentTypesFilterTypeDef,
     ListEntitiesFilterTypeDef,
     ListScenesRequestRequestTypeDef,
     SceneSummaryTypeDef,
     ListSyncJobsRequestRequestTypeDef,
     SyncResourceFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWorkspacesRequestRequestTypeDef,
     WorkspaceSummaryTypeDef,
     OrderByTypeDef,
     ParentEntityUpdateRequestTypeDef,
     PropertyValueTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    UpdatePricingPlanRequestRequestTypeDef,
-    UpdateSceneRequestRequestTypeDef,
-    UpdateWorkspaceRequestRequestTypeDef,
-    CreateComponentTypeResponseTypeDef,
-    CreateEntityResponseTypeDef,
-    CreateSceneResponseTypeDef,
-    CreateSyncJobResponseTypeDef,
-    CreateWorkspaceResponseTypeDef,
-    DeleteComponentTypeResponseTypeDef,
-    DeleteEntityResponseTypeDef,
-    DeleteSyncJobResponseTypeDef,
-    GetSceneResponseTypeDef,
-    GetWorkspaceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateComponentTypeResponseTypeDef,
     UpdateEntityResponseTypeDef,
+    UpdatePricingPlanRequestRequestTypeDef,
+    UpdateSceneRequestRequestTypeDef,
     UpdateSceneResponseTypeDef,
+    UpdateWorkspaceRequestRequestTypeDef,
     UpdateWorkspaceResponseTypeDef,
     PricingPlanTypeDef,
     PropertyRequestTypeDef,
     DataConnectorTypeDef,
     DataTypeTypeDef,
     DataValueTypeDef,
     PropertyLatestValueTypeDef,
     StatusTypeDef,
     SyncJobStatusTypeDef,
     SyncResourceStatusTypeDef,
     ExecuteQueryResponseTypeDef,
     PropertyResponseTypeDef,
     GetPropertyValueHistoryRequestRequestTypeDef,
+    GetSceneResponseTypeDef,
     ListComponentTypesRequestRequestTypeDef,
     ListEntitiesRequestRequestTypeDef,
     ListScenesResponseTypeDef,
     ListSyncResourcesRequestRequestTypeDef,
     ListWorkspacesResponseTypeDef,
     TabularConditionsTypeDef,
     PropertyValueEntryTypeDef,
@@ -390,54 +392,54 @@
     ListSyncResourcesResponseTypeDef,
     GetEntityResponseTypeDef,
     BatchPutPropertyErrorEntryTypeDef,
     BatchPutPropertyValuesResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> BundleInformationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/setup.py` & `types-aiobotocore-iottwinmaker-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iottwinmaker.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iottwinmaker",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iottwinmaker"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTTwinMaker 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTTwinMaker 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/"
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/__main__.py` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTTwinMaker 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTTwinMaker 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker\nOther"
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/client.py` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -179,15 +179,16 @@
         self,
         *,
         workspaceId: str,
         sceneId: str,
         contentLocation: str,
         description: str = ...,
         capabilities: Sequence[str] = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        sceneMetadata: Mapping[str, str] = ...
     ) -> CreateSceneResponseTypeDef:
         """
         Creates a scene.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker.Client.create_scene)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/client/#create_scene)
         """
@@ -539,15 +540,16 @@
     async def update_scene(
         self,
         *,
         workspaceId: str,
         sceneId: str,
         contentLocation: str = ...,
         description: str = ...,
-        capabilities: Sequence[str] = ...
+        capabilities: Sequence[str] = ...,
+        sceneMetadata: Mapping[str, str] = ...
     ) -> UpdateSceneResponseTypeDef:
         """
         Updates a scene.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker.Client.update_scene)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/client/#update_scene)
         """
```

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/client.pyi` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -170,15 +170,16 @@
         self,
         *,
         workspaceId: str,
         sceneId: str,
         contentLocation: str,
         description: str = ...,
         capabilities: Sequence[str] = ...,
-        tags: Mapping[str, str] = ...
+        tags: Mapping[str, str] = ...,
+        sceneMetadata: Mapping[str, str] = ...
     ) -> CreateSceneResponseTypeDef:
         """
         Creates a scene.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker.Client.create_scene)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/client/#create_scene)
         """
@@ -500,15 +501,16 @@
     async def update_scene(
         self,
         *,
         workspaceId: str,
         sceneId: str,
         contentLocation: str = ...,
         description: str = ...,
-        capabilities: Sequence[str] = ...
+        capabilities: Sequence[str] = ...,
+        sceneMetadata: Mapping[str, str] = ...
     ) -> UpdateSceneResponseTypeDef:
         """
         Updates a scene.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker.Client.update_scene)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/client/#update_scene)
         """
```

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/literals.py` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,14 +28,15 @@
     "OrderByTimeType",
     "OrderType",
     "ParentEntityUpdateTypeType",
     "PricingModeType",
     "PricingTierType",
     "PropertyGroupUpdateTypeType",
     "PropertyUpdateTypeType",
+    "SceneErrorCodeType",
     "ScopeType",
     "StateType",
     "SyncJobStateType",
     "SyncResourceStateType",
     "SyncResourceTypeType",
     "TypeType",
     "UpdateReasonType",
@@ -60,14 +61,15 @@
 OrderByTimeType = Literal["ASCENDING", "DESCENDING"]
 OrderType = Literal["ASCENDING", "DESCENDING"]
 ParentEntityUpdateTypeType = Literal["DELETE", "UPDATE"]
 PricingModeType = Literal["BASIC", "STANDARD", "TIERED_BUNDLE"]
 PricingTierType = Literal["TIER_1", "TIER_2", "TIER_3", "TIER_4"]
 PropertyGroupUpdateTypeType = Literal["CREATE", "DELETE", "UPDATE"]
 PropertyUpdateTypeType = Literal["CREATE", "DELETE", "UPDATE"]
+SceneErrorCodeType = Literal["MATTERPORT_ERROR"]
 ScopeType = Literal["ENTITY", "WORKSPACE"]
 StateType = Literal["ACTIVE", "CREATING", "DELETING", "ERROR", "UPDATING"]
 SyncJobStateType = Literal["ACTIVE", "CREATING", "DELETING", "ERROR", "INITIALIZING"]
 SyncResourceStateType = Literal["DELETED", "ERROR", "INITIALIZING", "IN_SYNC", "PROCESSING"]
 SyncResourceTypeType = Literal["COMPONENT_TYPE", "ENTITY"]
 TypeType = Literal["BOOLEAN", "DOUBLE", "INTEGER", "LIST", "LONG", "MAP", "RELATIONSHIP", "STRING"]
 UpdateReasonType = Literal[
@@ -132,14 +134,15 @@
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
@@ -218,14 +221,15 @@
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
@@ -236,14 +240,15 @@
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
@@ -279,14 +284,15 @@
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
@@ -305,16 +311,19 @@
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
@@ -398,15 +407,17 @@
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/literals.pyi` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -27,14 +27,15 @@
     "OrderByTimeType",
     "OrderType",
     "ParentEntityUpdateTypeType",
     "PricingModeType",
     "PricingTierType",
     "PropertyGroupUpdateTypeType",
     "PropertyUpdateTypeType",
+    "SceneErrorCodeType",
     "ScopeType",
     "StateType",
     "SyncJobStateType",
     "SyncResourceStateType",
     "SyncResourceTypeType",
     "TypeType",
     "UpdateReasonType",
@@ -58,14 +59,15 @@
 OrderByTimeType = Literal["ASCENDING", "DESCENDING"]
 OrderType = Literal["ASCENDING", "DESCENDING"]
 ParentEntityUpdateTypeType = Literal["DELETE", "UPDATE"]
 PricingModeType = Literal["BASIC", "STANDARD", "TIERED_BUNDLE"]
 PricingTierType = Literal["TIER_1", "TIER_2", "TIER_3", "TIER_4"]
 PropertyGroupUpdateTypeType = Literal["CREATE", "DELETE", "UPDATE"]
 PropertyUpdateTypeType = Literal["CREATE", "DELETE", "UPDATE"]
+SceneErrorCodeType = Literal["MATTERPORT_ERROR"]
 ScopeType = Literal["ENTITY", "WORKSPACE"]
 StateType = Literal["ACTIVE", "CREATING", "DELETING", "ERROR", "UPDATING"]
 SyncJobStateType = Literal["ACTIVE", "CREATING", "DELETING", "ERROR", "INITIALIZING"]
 SyncResourceStateType = Literal["DELETED", "ERROR", "INITIALIZING", "IN_SYNC", "PROCESSING"]
 SyncResourceTypeType = Literal["COMPONENT_TYPE", "ENTITY"]
 TypeType = Literal["BOOLEAN", "DOUBLE", "INTEGER", "LIST", "LONG", "MAP", "RELATIONSHIP", "STRING"]
 UpdateReasonType = Literal[
@@ -130,14 +132,15 @@
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
@@ -216,14 +219,15 @@
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
@@ -234,14 +238,15 @@
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
@@ -277,14 +282,15 @@
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
@@ -303,16 +309,19 @@
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
@@ -396,15 +405,17 @@
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/type_defs.py` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for iottwinmaker service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iottwinmaker.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_iottwinmaker.type_defs import BundleInformationTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: BundleInformationTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence, Union
 
 from .literals import (
@@ -42,89 +42,90 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
     "BundleInformationTypeDef",
     "ColumnDescriptionTypeDef",
     "ComponentPropertyGroupRequestTypeDef",
     "ComponentPropertyGroupResponseTypeDef",
     "PropertyDefinitionRequestTypeDef",
     "PropertyGroupRequestTypeDef",
+    "CreateComponentTypeResponseTypeDef",
+    "CreateEntityResponseTypeDef",
     "CreateSceneRequestRequestTypeDef",
+    "CreateSceneResponseTypeDef",
     "CreateSyncJobRequestRequestTypeDef",
+    "CreateSyncJobResponseTypeDef",
     "CreateWorkspaceRequestRequestTypeDef",
+    "CreateWorkspaceResponseTypeDef",
     "LambdaFunctionTypeDef",
     "RelationshipTypeDef",
     "RelationshipValueTypeDef",
     "DeleteComponentTypeRequestRequestTypeDef",
+    "DeleteComponentTypeResponseTypeDef",
     "DeleteEntityRequestRequestTypeDef",
+    "DeleteEntityResponseTypeDef",
     "DeleteSceneRequestRequestTypeDef",
     "DeleteSyncJobRequestRequestTypeDef",
+    "DeleteSyncJobResponseTypeDef",
     "DeleteWorkspaceRequestRequestTypeDef",
     "EntityPropertyReferenceTypeDef",
     "ErrorDetailsTypeDef",
     "ExecuteQueryRequestRequestTypeDef",
     "RowTypeDef",
     "GetComponentTypeRequestRequestTypeDef",
     "PropertyDefinitionResponseTypeDef",
     "PropertyGroupResponseTypeDef",
     "GetEntityRequestRequestTypeDef",
     "InterpolationParametersTypeDef",
     "PropertyFilterTypeDef",
     "GetSceneRequestRequestTypeDef",
+    "SceneErrorTypeDef",
     "GetSyncJobRequestRequestTypeDef",
     "GetWorkspaceRequestRequestTypeDef",
+    "GetWorkspaceResponseTypeDef",
     "ListComponentTypesFilterTypeDef",
     "ListEntitiesFilterTypeDef",
     "ListScenesRequestRequestTypeDef",
     "SceneSummaryTypeDef",
     "ListSyncJobsRequestRequestTypeDef",
     "SyncResourceFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListWorkspacesRequestRequestTypeDef",
     "WorkspaceSummaryTypeDef",
     "OrderByTypeDef",
     "ParentEntityUpdateRequestTypeDef",
     "PropertyValueTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "UpdatePricingPlanRequestRequestTypeDef",
-    "UpdateSceneRequestRequestTypeDef",
-    "UpdateWorkspaceRequestRequestTypeDef",
-    "CreateComponentTypeResponseTypeDef",
-    "CreateEntityResponseTypeDef",
-    "CreateSceneResponseTypeDef",
-    "CreateSyncJobResponseTypeDef",
-    "CreateWorkspaceResponseTypeDef",
-    "DeleteComponentTypeResponseTypeDef",
-    "DeleteEntityResponseTypeDef",
-    "DeleteSyncJobResponseTypeDef",
-    "GetSceneResponseTypeDef",
-    "GetWorkspaceResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateComponentTypeResponseTypeDef",
     "UpdateEntityResponseTypeDef",
+    "UpdatePricingPlanRequestRequestTypeDef",
+    "UpdateSceneRequestRequestTypeDef",
     "UpdateSceneResponseTypeDef",
+    "UpdateWorkspaceRequestRequestTypeDef",
     "UpdateWorkspaceResponseTypeDef",
     "PricingPlanTypeDef",
     "PropertyRequestTypeDef",
     "DataConnectorTypeDef",
     "DataTypeTypeDef",
     "DataValueTypeDef",
     "PropertyLatestValueTypeDef",
     "StatusTypeDef",
     "SyncJobStatusTypeDef",
     "SyncResourceStatusTypeDef",
     "ExecuteQueryResponseTypeDef",
     "PropertyResponseTypeDef",
     "GetPropertyValueHistoryRequestRequestTypeDef",
+    "GetSceneResponseTypeDef",
     "ListComponentTypesRequestRequestTypeDef",
     "ListEntitiesRequestRequestTypeDef",
     "ListScenesResponseTypeDef",
     "ListSyncResourcesRequestRequestTypeDef",
     "ListWorkspacesResponseTypeDef",
     "TabularConditionsTypeDef",
     "PropertyValueEntryTypeDef",
@@ -156,25 +157,14 @@
     "ListSyncJobsResponseTypeDef",
     "ListSyncResourcesResponseTypeDef",
     "GetEntityResponseTypeDef",
     "BatchPutPropertyErrorEntryTypeDef",
     "BatchPutPropertyValuesResponseTypeDef",
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
 _RequiredBundleInformationTypeDef = TypedDict(
     "_RequiredBundleInformationTypeDef",
     {
         "bundleNames": List[str],
     },
 )
 _OptionalBundleInformationTypeDef = TypedDict(
@@ -240,39 +230,70 @@
     {
         "groupType": Literal["TABULAR"],
         "propertyNames": Sequence[str],
     },
     total=False,
 )
 
+CreateComponentTypeResponseTypeDef = TypedDict(
+    "CreateComponentTypeResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEntityResponseTypeDef = TypedDict(
+    "CreateEntityResponseTypeDef",
+    {
+        "entityId": str,
+        "arn": str,
+        "creationDateTime": datetime,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSceneRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSceneRequestRequestTypeDef",
     {
         "workspaceId": str,
         "sceneId": str,
         "contentLocation": str,
     },
 )
 _OptionalCreateSceneRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSceneRequestRequestTypeDef",
     {
         "description": str,
         "capabilities": Sequence[str],
         "tags": Mapping[str, str],
+        "sceneMetadata": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateSceneRequestRequestTypeDef(
     _RequiredCreateSceneRequestRequestTypeDef, _OptionalCreateSceneRequestRequestTypeDef
 ):
     pass
 
 
+CreateSceneResponseTypeDef = TypedDict(
+    "CreateSceneResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSyncJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSyncJobRequestRequestTypeDef",
     {
         "workspaceId": str,
         "syncSource": str,
         "syncRole": str,
     },
@@ -288,14 +309,24 @@
 
 class CreateSyncJobRequestRequestTypeDef(
     _RequiredCreateSyncJobRequestRequestTypeDef, _OptionalCreateSyncJobRequestRequestTypeDef
 ):
     pass
 
 
+CreateSyncJobResponseTypeDef = TypedDict(
+    "CreateSyncJobResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "state": SyncJobStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateWorkspaceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
         "s3Location": str,
         "role": str,
     },
@@ -312,14 +343,23 @@
 
 class CreateWorkspaceRequestRequestTypeDef(
     _RequiredCreateWorkspaceRequestRequestTypeDef, _OptionalCreateWorkspaceRequestRequestTypeDef
 ):
     pass
 
 
+CreateWorkspaceResponseTypeDef = TypedDict(
+    "CreateWorkspaceResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LambdaFunctionTypeDef = TypedDict(
     "LambdaFunctionTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -345,14 +385,22 @@
     "DeleteComponentTypeRequestRequestTypeDef",
     {
         "workspaceId": str,
         "componentTypeId": str,
     },
 )
 
+DeleteComponentTypeResponseTypeDef = TypedDict(
+    "DeleteComponentTypeResponseTypeDef",
+    {
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteEntityRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteEntityRequestRequestTypeDef",
     {
         "workspaceId": str,
         "entityId": str,
     },
 )
@@ -367,14 +415,22 @@
 
 class DeleteEntityRequestRequestTypeDef(
     _RequiredDeleteEntityRequestRequestTypeDef, _OptionalDeleteEntityRequestRequestTypeDef
 ):
     pass
 
 
+DeleteEntityResponseTypeDef = TypedDict(
+    "DeleteEntityResponseTypeDef",
+    {
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSceneRequestRequestTypeDef = TypedDict(
     "DeleteSceneRequestRequestTypeDef",
     {
         "workspaceId": str,
         "sceneId": str,
     },
 )
@@ -383,14 +439,22 @@
     "DeleteSyncJobRequestRequestTypeDef",
     {
         "workspaceId": str,
         "syncSource": str,
     },
 )
 
+DeleteSyncJobResponseTypeDef = TypedDict(
+    "DeleteSyncJobResponseTypeDef",
+    {
+        "state": SyncJobStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkspaceRequestRequestTypeDef = TypedDict(
     "DeleteWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
@@ -535,14 +599,23 @@
     "GetSceneRequestRequestTypeDef",
     {
         "workspaceId": str,
         "sceneId": str,
     },
 )
 
+SceneErrorTypeDef = TypedDict(
+    "SceneErrorTypeDef",
+    {
+        "code": Literal["MATTERPORT_ERROR"],
+        "message": str,
+    },
+    total=False,
+)
+
 _RequiredGetSyncJobRequestRequestTypeDef = TypedDict(
     "_RequiredGetSyncJobRequestRequestTypeDef",
     {
         "syncSource": str,
     },
 )
 _OptionalGetSyncJobRequestRequestTypeDef = TypedDict(
@@ -563,14 +636,28 @@
 GetWorkspaceRequestRequestTypeDef = TypedDict(
     "GetWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
+GetWorkspaceResponseTypeDef = TypedDict(
+    "GetWorkspaceResponseTypeDef",
+    {
+        "workspaceId": str,
+        "arn": str,
+        "description": str,
+        "s3Location": str,
+        "role": str,
+        "creationDateTime": datetime,
+        "updateDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListComponentTypesFilterTypeDef = TypedDict(
     "ListComponentTypesFilterTypeDef",
     {
         "extendsFrom": str,
         "namespace": str,
         "isAbstract": bool,
     },
@@ -684,14 +771,23 @@
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListWorkspacesRequestRequestTypeDef = TypedDict(
     "ListWorkspacesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -775,14 +871,25 @@
 )
 
 
 class PropertyValueTypeDef(_RequiredPropertyValueTypeDef, _OptionalPropertyValueTypeDef):
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tags": Mapping[str, str],
     },
 )
@@ -791,14 +898,34 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateComponentTypeResponseTypeDef = TypedDict(
+    "UpdateComponentTypeResponseTypeDef",
+    {
+        "workspaceId": str,
+        "arn": str,
+        "componentTypeId": str,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateEntityResponseTypeDef = TypedDict(
+    "UpdateEntityResponseTypeDef",
+    {
+        "updateDateTime": datetime,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdatePricingPlanRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePricingPlanRequestRequestTypeDef",
     {
         "pricingMode": PricingModeType,
     },
 )
 _OptionalUpdatePricingPlanRequestRequestTypeDef = TypedDict(
@@ -825,25 +952,34 @@
 )
 _OptionalUpdateSceneRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateSceneRequestRequestTypeDef",
     {
         "contentLocation": str,
         "description": str,
         "capabilities": Sequence[str],
+        "sceneMetadata": Mapping[str, str],
     },
     total=False,
 )
 
 
 class UpdateSceneRequestRequestTypeDef(
     _RequiredUpdateSceneRequestRequestTypeDef, _OptionalUpdateSceneRequestRequestTypeDef
 ):
     pass
 
 
+UpdateSceneResponseTypeDef = TypedDict(
+    "UpdateSceneResponseTypeDef",
+    {
+        "updateDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateWorkspaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 _OptionalUpdateWorkspaceRequestRequestTypeDef = TypedDict(
@@ -858,158 +994,19 @@
 
 class UpdateWorkspaceRequestRequestTypeDef(
     _RequiredUpdateWorkspaceRequestRequestTypeDef, _OptionalUpdateWorkspaceRequestRequestTypeDef
 ):
     pass
 
 
-CreateComponentTypeResponseTypeDef = TypedDict(
-    "CreateComponentTypeResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEntityResponseTypeDef = TypedDict(
-    "CreateEntityResponseTypeDef",
-    {
-        "entityId": str,
-        "arn": str,
-        "creationDateTime": datetime,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSceneResponseTypeDef = TypedDict(
-    "CreateSceneResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSyncJobResponseTypeDef = TypedDict(
-    "CreateSyncJobResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "state": SyncJobStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkspaceResponseTypeDef = TypedDict(
-    "CreateWorkspaceResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteComponentTypeResponseTypeDef = TypedDict(
-    "DeleteComponentTypeResponseTypeDef",
-    {
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEntityResponseTypeDef = TypedDict(
-    "DeleteEntityResponseTypeDef",
-    {
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSyncJobResponseTypeDef = TypedDict(
-    "DeleteSyncJobResponseTypeDef",
-    {
-        "state": SyncJobStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSceneResponseTypeDef = TypedDict(
-    "GetSceneResponseTypeDef",
-    {
-        "workspaceId": str,
-        "sceneId": str,
-        "contentLocation": str,
-        "arn": str,
-        "creationDateTime": datetime,
-        "updateDateTime": datetime,
-        "description": str,
-        "capabilities": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkspaceResponseTypeDef = TypedDict(
-    "GetWorkspaceResponseTypeDef",
-    {
-        "workspaceId": str,
-        "arn": str,
-        "description": str,
-        "s3Location": str,
-        "role": str,
-        "creationDateTime": datetime,
-        "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateComponentTypeResponseTypeDef = TypedDict(
-    "UpdateComponentTypeResponseTypeDef",
-    {
-        "workspaceId": str,
-        "arn": str,
-        "componentTypeId": str,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateEntityResponseTypeDef = TypedDict(
-    "UpdateEntityResponseTypeDef",
-    {
-        "updateDateTime": datetime,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSceneResponseTypeDef = TypedDict(
-    "UpdateSceneResponseTypeDef",
-    {
-        "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateWorkspaceResponseTypeDef = TypedDict(
     "UpdateWorkspaceResponseTypeDef",
     {
         "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPricingPlanTypeDef = TypedDict(
     "_RequiredPricingPlanTypeDef",
     {
         "effectiveDateTime": datetime,
@@ -1139,15 +1136,15 @@
 
 ExecuteQueryResponseTypeDef = TypedDict(
     "ExecuteQueryResponseTypeDef",
     {
         "columnDescriptions": List[ColumnDescriptionTypeDef],
         "rows": List[RowTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PropertyResponseTypeDef = TypedDict(
     "PropertyResponseTypeDef",
     {
         "definition": PropertyDefinitionResponseTypeDef,
@@ -1186,14 +1183,32 @@
 class GetPropertyValueHistoryRequestRequestTypeDef(
     _RequiredGetPropertyValueHistoryRequestRequestTypeDef,
     _OptionalGetPropertyValueHistoryRequestRequestTypeDef,
 ):
     pass
 
 
+GetSceneResponseTypeDef = TypedDict(
+    "GetSceneResponseTypeDef",
+    {
+        "workspaceId": str,
+        "sceneId": str,
+        "contentLocation": str,
+        "arn": str,
+        "creationDateTime": datetime,
+        "updateDateTime": datetime,
+        "description": str,
+        "capabilities": List[str],
+        "sceneMetadata": Dict[str, str],
+        "generatedSceneMetadata": Dict[str, str],
+        "error": SceneErrorTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListComponentTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListComponentTypesRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 _OptionalListComponentTypesRequestRequestTypeDef = TypedDict(
@@ -1238,15 +1253,15 @@
 
 
 ListScenesResponseTypeDef = TypedDict(
     "ListScenesResponseTypeDef",
     {
         "sceneSummaries": List[SceneSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListSyncResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListSyncResourcesRequestRequestTypeDef",
     {
         "workspaceId": str,
@@ -1271,15 +1286,15 @@
 
 
 ListWorkspacesResponseTypeDef = TypedDict(
     "ListWorkspacesResponseTypeDef",
     {
         "workspaceSummaries": List[WorkspaceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TabularConditionsTypeDef = TypedDict(
     "TabularConditionsTypeDef",
     {
         "orderBy": Sequence[OrderByTypeDef],
@@ -1331,24 +1346,24 @@
 
 
 GetPricingPlanResponseTypeDef = TypedDict(
     "GetPricingPlanResponseTypeDef",
     {
         "currentPricingPlan": PricingPlanTypeDef,
         "pendingPricingPlan": PricingPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePricingPlanResponseTypeDef = TypedDict(
     "UpdatePricingPlanResponseTypeDef",
     {
         "currentPricingPlan": PricingPlanTypeDef,
         "pendingPricingPlan": PricingPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentRequestTypeDef = TypedDict(
     "ComponentRequestTypeDef",
     {
         "description": str,
@@ -1394,15 +1409,15 @@
 
 GetPropertyValueResponseTypeDef = TypedDict(
     "GetPropertyValueResponseTypeDef",
     {
         "propertyValues": Dict[str, PropertyLatestValueTypeDef],
         "nextToken": str,
         "tabularPropertyValues": List[List[Dict[str, "DataValueTypeDef"]]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredComponentTypeSummaryTypeDef = TypedDict(
     "_RequiredComponentTypeSummaryTypeDef",
     {
         "arn": str,
@@ -1460,15 +1475,15 @@
         "arn": str,
         "workspaceId": str,
         "syncSource": str,
         "syncRole": str,
         "status": SyncJobStatusTypeDef,
         "creationDateTime": datetime,
         "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SyncJobSummaryTypeDef = TypedDict(
     "SyncJobSummaryTypeDef",
     {
         "arn": str,
@@ -1554,15 +1569,15 @@
 )
 
 GetPropertyValueHistoryResponseTypeDef = TypedDict(
     "GetPropertyValueHistoryResponseTypeDef",
     {
         "propertyValues": List[PropertyValueHistoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEntityRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEntityRequestRequestTypeDef",
     {
         "workspaceId": str,
@@ -1687,53 +1702,53 @@
         "arn": str,
         "isAbstract": bool,
         "isSchemaInitialized": bool,
         "status": StatusTypeDef,
         "propertyGroups": Dict[str, PropertyGroupResponseTypeDef],
         "syncSource": str,
         "componentTypeName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComponentTypesResponseTypeDef = TypedDict(
     "ListComponentTypesResponseTypeDef",
     {
         "workspaceId": str,
         "componentTypeSummaries": List[ComponentTypeSummaryTypeDef],
         "nextToken": str,
         "maxResults": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitiesResponseTypeDef = TypedDict(
     "ListEntitiesResponseTypeDef",
     {
         "entitySummaries": List[EntitySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSyncJobsResponseTypeDef = TypedDict(
     "ListSyncJobsResponseTypeDef",
     {
         "syncJobSummaries": List[SyncJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSyncResourcesResponseTypeDef = TypedDict(
     "ListSyncResourcesResponseTypeDef",
     {
         "syncResources": List[SyncResourceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEntityResponseTypeDef = TypedDict(
     "GetEntityResponseTypeDef",
     {
         "entityId": str,
@@ -1744,25 +1759,25 @@
         "description": str,
         "components": Dict[str, ComponentResponseTypeDef],
         "parentEntityId": str,
         "hasChildEntities": bool,
         "creationDateTime": datetime,
         "updateDateTime": datetime,
         "syncSource": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutPropertyErrorEntryTypeDef = TypedDict(
     "BatchPutPropertyErrorEntryTypeDef",
     {
         "errors": List[BatchPutPropertyErrorTypeDef],
     },
 )
 
 BatchPutPropertyValuesResponseTypeDef = TypedDict(
     "BatchPutPropertyValuesResponseTypeDef",
     {
         "errorEntries": List[BatchPutPropertyErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker/type_defs.pyi` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for iottwinmaker service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iottwinmaker.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_iottwinmaker.type_defs import BundleInformationTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: BundleInformationTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence, Union
 
 from .literals import (
@@ -41,89 +41,90 @@
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
-    "ResponseMetadataTypeDef",
     "BundleInformationTypeDef",
     "ColumnDescriptionTypeDef",
     "ComponentPropertyGroupRequestTypeDef",
     "ComponentPropertyGroupResponseTypeDef",
     "PropertyDefinitionRequestTypeDef",
     "PropertyGroupRequestTypeDef",
+    "CreateComponentTypeResponseTypeDef",
+    "CreateEntityResponseTypeDef",
     "CreateSceneRequestRequestTypeDef",
+    "CreateSceneResponseTypeDef",
     "CreateSyncJobRequestRequestTypeDef",
+    "CreateSyncJobResponseTypeDef",
     "CreateWorkspaceRequestRequestTypeDef",
+    "CreateWorkspaceResponseTypeDef",
     "LambdaFunctionTypeDef",
     "RelationshipTypeDef",
     "RelationshipValueTypeDef",
     "DeleteComponentTypeRequestRequestTypeDef",
+    "DeleteComponentTypeResponseTypeDef",
     "DeleteEntityRequestRequestTypeDef",
+    "DeleteEntityResponseTypeDef",
     "DeleteSceneRequestRequestTypeDef",
     "DeleteSyncJobRequestRequestTypeDef",
+    "DeleteSyncJobResponseTypeDef",
     "DeleteWorkspaceRequestRequestTypeDef",
     "EntityPropertyReferenceTypeDef",
     "ErrorDetailsTypeDef",
     "ExecuteQueryRequestRequestTypeDef",
     "RowTypeDef",
     "GetComponentTypeRequestRequestTypeDef",
     "PropertyDefinitionResponseTypeDef",
     "PropertyGroupResponseTypeDef",
     "GetEntityRequestRequestTypeDef",
     "InterpolationParametersTypeDef",
     "PropertyFilterTypeDef",
     "GetSceneRequestRequestTypeDef",
+    "SceneErrorTypeDef",
     "GetSyncJobRequestRequestTypeDef",
     "GetWorkspaceRequestRequestTypeDef",
+    "GetWorkspaceResponseTypeDef",
     "ListComponentTypesFilterTypeDef",
     "ListEntitiesFilterTypeDef",
     "ListScenesRequestRequestTypeDef",
     "SceneSummaryTypeDef",
     "ListSyncJobsRequestRequestTypeDef",
     "SyncResourceFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListWorkspacesRequestRequestTypeDef",
     "WorkspaceSummaryTypeDef",
     "OrderByTypeDef",
     "ParentEntityUpdateRequestTypeDef",
     "PropertyValueTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "UpdatePricingPlanRequestRequestTypeDef",
-    "UpdateSceneRequestRequestTypeDef",
-    "UpdateWorkspaceRequestRequestTypeDef",
-    "CreateComponentTypeResponseTypeDef",
-    "CreateEntityResponseTypeDef",
-    "CreateSceneResponseTypeDef",
-    "CreateSyncJobResponseTypeDef",
-    "CreateWorkspaceResponseTypeDef",
-    "DeleteComponentTypeResponseTypeDef",
-    "DeleteEntityResponseTypeDef",
-    "DeleteSyncJobResponseTypeDef",
-    "GetSceneResponseTypeDef",
-    "GetWorkspaceResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateComponentTypeResponseTypeDef",
     "UpdateEntityResponseTypeDef",
+    "UpdatePricingPlanRequestRequestTypeDef",
+    "UpdateSceneRequestRequestTypeDef",
     "UpdateSceneResponseTypeDef",
+    "UpdateWorkspaceRequestRequestTypeDef",
     "UpdateWorkspaceResponseTypeDef",
     "PricingPlanTypeDef",
     "PropertyRequestTypeDef",
     "DataConnectorTypeDef",
     "DataTypeTypeDef",
     "DataValueTypeDef",
     "PropertyLatestValueTypeDef",
     "StatusTypeDef",
     "SyncJobStatusTypeDef",
     "SyncResourceStatusTypeDef",
     "ExecuteQueryResponseTypeDef",
     "PropertyResponseTypeDef",
     "GetPropertyValueHistoryRequestRequestTypeDef",
+    "GetSceneResponseTypeDef",
     "ListComponentTypesRequestRequestTypeDef",
     "ListEntitiesRequestRequestTypeDef",
     "ListScenesResponseTypeDef",
     "ListSyncResourcesRequestRequestTypeDef",
     "ListWorkspacesResponseTypeDef",
     "TabularConditionsTypeDef",
     "PropertyValueEntryTypeDef",
@@ -155,25 +156,14 @@
     "ListSyncJobsResponseTypeDef",
     "ListSyncResourcesResponseTypeDef",
     "GetEntityResponseTypeDef",
     "BatchPutPropertyErrorEntryTypeDef",
     "BatchPutPropertyValuesResponseTypeDef",
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
 _RequiredBundleInformationTypeDef = TypedDict(
     "_RequiredBundleInformationTypeDef",
     {
         "bundleNames": List[str],
     },
 )
 _OptionalBundleInformationTypeDef = TypedDict(
@@ -237,37 +227,68 @@
     {
         "groupType": Literal["TABULAR"],
         "propertyNames": Sequence[str],
     },
     total=False,
 )
 
+CreateComponentTypeResponseTypeDef = TypedDict(
+    "CreateComponentTypeResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEntityResponseTypeDef = TypedDict(
+    "CreateEntityResponseTypeDef",
+    {
+        "entityId": str,
+        "arn": str,
+        "creationDateTime": datetime,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSceneRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSceneRequestRequestTypeDef",
     {
         "workspaceId": str,
         "sceneId": str,
         "contentLocation": str,
     },
 )
 _OptionalCreateSceneRequestRequestTypeDef = TypedDict(
     "_OptionalCreateSceneRequestRequestTypeDef",
     {
         "description": str,
         "capabilities": Sequence[str],
         "tags": Mapping[str, str],
+        "sceneMetadata": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateSceneRequestRequestTypeDef(
     _RequiredCreateSceneRequestRequestTypeDef, _OptionalCreateSceneRequestRequestTypeDef
 ):
     pass
 
+CreateSceneResponseTypeDef = TypedDict(
+    "CreateSceneResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSyncJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSyncJobRequestRequestTypeDef",
     {
         "workspaceId": str,
         "syncSource": str,
         "syncRole": str,
     },
@@ -281,14 +302,24 @@
 )
 
 class CreateSyncJobRequestRequestTypeDef(
     _RequiredCreateSyncJobRequestRequestTypeDef, _OptionalCreateSyncJobRequestRequestTypeDef
 ):
     pass
 
+CreateSyncJobResponseTypeDef = TypedDict(
+    "CreateSyncJobResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "state": SyncJobStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateWorkspaceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
         "s3Location": str,
         "role": str,
     },
@@ -303,14 +334,23 @@
 )
 
 class CreateWorkspaceRequestRequestTypeDef(
     _RequiredCreateWorkspaceRequestRequestTypeDef, _OptionalCreateWorkspaceRequestRequestTypeDef
 ):
     pass
 
+CreateWorkspaceResponseTypeDef = TypedDict(
+    "CreateWorkspaceResponseTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LambdaFunctionTypeDef = TypedDict(
     "LambdaFunctionTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -336,14 +376,22 @@
     "DeleteComponentTypeRequestRequestTypeDef",
     {
         "workspaceId": str,
         "componentTypeId": str,
     },
 )
 
+DeleteComponentTypeResponseTypeDef = TypedDict(
+    "DeleteComponentTypeResponseTypeDef",
+    {
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteEntityRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteEntityRequestRequestTypeDef",
     {
         "workspaceId": str,
         "entityId": str,
     },
 )
@@ -356,14 +404,22 @@
 )
 
 class DeleteEntityRequestRequestTypeDef(
     _RequiredDeleteEntityRequestRequestTypeDef, _OptionalDeleteEntityRequestRequestTypeDef
 ):
     pass
 
+DeleteEntityResponseTypeDef = TypedDict(
+    "DeleteEntityResponseTypeDef",
+    {
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSceneRequestRequestTypeDef = TypedDict(
     "DeleteSceneRequestRequestTypeDef",
     {
         "workspaceId": str,
         "sceneId": str,
     },
 )
@@ -372,14 +428,22 @@
     "DeleteSyncJobRequestRequestTypeDef",
     {
         "workspaceId": str,
         "syncSource": str,
     },
 )
 
+DeleteSyncJobResponseTypeDef = TypedDict(
+    "DeleteSyncJobResponseTypeDef",
+    {
+        "state": SyncJobStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkspaceRequestRequestTypeDef = TypedDict(
     "DeleteWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
@@ -518,14 +582,23 @@
     "GetSceneRequestRequestTypeDef",
     {
         "workspaceId": str,
         "sceneId": str,
     },
 )
 
+SceneErrorTypeDef = TypedDict(
+    "SceneErrorTypeDef",
+    {
+        "code": Literal["MATTERPORT_ERROR"],
+        "message": str,
+    },
+    total=False,
+)
+
 _RequiredGetSyncJobRequestRequestTypeDef = TypedDict(
     "_RequiredGetSyncJobRequestRequestTypeDef",
     {
         "syncSource": str,
     },
 )
 _OptionalGetSyncJobRequestRequestTypeDef = TypedDict(
@@ -544,14 +617,28 @@
 GetWorkspaceRequestRequestTypeDef = TypedDict(
     "GetWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 
+GetWorkspaceResponseTypeDef = TypedDict(
+    "GetWorkspaceResponseTypeDef",
+    {
+        "workspaceId": str,
+        "arn": str,
+        "description": str,
+        "s3Location": str,
+        "role": str,
+        "creationDateTime": datetime,
+        "updateDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListComponentTypesFilterTypeDef = TypedDict(
     "ListComponentTypesFilterTypeDef",
     {
         "extendsFrom": str,
         "namespace": str,
         "isAbstract": bool,
     },
@@ -657,14 +744,23 @@
 
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListWorkspacesRequestRequestTypeDef = TypedDict(
     "ListWorkspacesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -740,14 +836,25 @@
     },
     total=False,
 )
 
 class PropertyValueTypeDef(_RequiredPropertyValueTypeDef, _OptionalPropertyValueTypeDef):
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tags": Mapping[str, str],
     },
 )
@@ -756,14 +863,34 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateComponentTypeResponseTypeDef = TypedDict(
+    "UpdateComponentTypeResponseTypeDef",
+    {
+        "workspaceId": str,
+        "arn": str,
+        "componentTypeId": str,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateEntityResponseTypeDef = TypedDict(
+    "UpdateEntityResponseTypeDef",
+    {
+        "updateDateTime": datetime,
+        "state": StateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdatePricingPlanRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePricingPlanRequestRequestTypeDef",
     {
         "pricingMode": PricingModeType,
     },
 )
 _OptionalUpdatePricingPlanRequestRequestTypeDef = TypedDict(
@@ -788,23 +915,32 @@
 )
 _OptionalUpdateSceneRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateSceneRequestRequestTypeDef",
     {
         "contentLocation": str,
         "description": str,
         "capabilities": Sequence[str],
+        "sceneMetadata": Mapping[str, str],
     },
     total=False,
 )
 
 class UpdateSceneRequestRequestTypeDef(
     _RequiredUpdateSceneRequestRequestTypeDef, _OptionalUpdateSceneRequestRequestTypeDef
 ):
     pass
 
+UpdateSceneResponseTypeDef = TypedDict(
+    "UpdateSceneResponseTypeDef",
+    {
+        "updateDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateWorkspaceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkspaceRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 _OptionalUpdateWorkspaceRequestRequestTypeDef = TypedDict(
@@ -817,158 +953,19 @@
 )
 
 class UpdateWorkspaceRequestRequestTypeDef(
     _RequiredUpdateWorkspaceRequestRequestTypeDef, _OptionalUpdateWorkspaceRequestRequestTypeDef
 ):
     pass
 
-CreateComponentTypeResponseTypeDef = TypedDict(
-    "CreateComponentTypeResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEntityResponseTypeDef = TypedDict(
-    "CreateEntityResponseTypeDef",
-    {
-        "entityId": str,
-        "arn": str,
-        "creationDateTime": datetime,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSceneResponseTypeDef = TypedDict(
-    "CreateSceneResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSyncJobResponseTypeDef = TypedDict(
-    "CreateSyncJobResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "state": SyncJobStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkspaceResponseTypeDef = TypedDict(
-    "CreateWorkspaceResponseTypeDef",
-    {
-        "arn": str,
-        "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteComponentTypeResponseTypeDef = TypedDict(
-    "DeleteComponentTypeResponseTypeDef",
-    {
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEntityResponseTypeDef = TypedDict(
-    "DeleteEntityResponseTypeDef",
-    {
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSyncJobResponseTypeDef = TypedDict(
-    "DeleteSyncJobResponseTypeDef",
-    {
-        "state": SyncJobStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSceneResponseTypeDef = TypedDict(
-    "GetSceneResponseTypeDef",
-    {
-        "workspaceId": str,
-        "sceneId": str,
-        "contentLocation": str,
-        "arn": str,
-        "creationDateTime": datetime,
-        "updateDateTime": datetime,
-        "description": str,
-        "capabilities": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkspaceResponseTypeDef = TypedDict(
-    "GetWorkspaceResponseTypeDef",
-    {
-        "workspaceId": str,
-        "arn": str,
-        "description": str,
-        "s3Location": str,
-        "role": str,
-        "creationDateTime": datetime,
-        "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateComponentTypeResponseTypeDef = TypedDict(
-    "UpdateComponentTypeResponseTypeDef",
-    {
-        "workspaceId": str,
-        "arn": str,
-        "componentTypeId": str,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateEntityResponseTypeDef = TypedDict(
-    "UpdateEntityResponseTypeDef",
-    {
-        "updateDateTime": datetime,
-        "state": StateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSceneResponseTypeDef = TypedDict(
-    "UpdateSceneResponseTypeDef",
-    {
-        "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateWorkspaceResponseTypeDef = TypedDict(
     "UpdateWorkspaceResponseTypeDef",
     {
         "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPricingPlanTypeDef = TypedDict(
     "_RequiredPricingPlanTypeDef",
     {
         "effectiveDateTime": datetime,
@@ -1092,15 +1089,15 @@
 
 ExecuteQueryResponseTypeDef = TypedDict(
     "ExecuteQueryResponseTypeDef",
     {
         "columnDescriptions": List[ColumnDescriptionTypeDef],
         "rows": List[RowTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PropertyResponseTypeDef = TypedDict(
     "PropertyResponseTypeDef",
     {
         "definition": PropertyDefinitionResponseTypeDef,
@@ -1137,14 +1134,32 @@
 
 class GetPropertyValueHistoryRequestRequestTypeDef(
     _RequiredGetPropertyValueHistoryRequestRequestTypeDef,
     _OptionalGetPropertyValueHistoryRequestRequestTypeDef,
 ):
     pass
 
+GetSceneResponseTypeDef = TypedDict(
+    "GetSceneResponseTypeDef",
+    {
+        "workspaceId": str,
+        "sceneId": str,
+        "contentLocation": str,
+        "arn": str,
+        "creationDateTime": datetime,
+        "updateDateTime": datetime,
+        "description": str,
+        "capabilities": List[str],
+        "sceneMetadata": Dict[str, str],
+        "generatedSceneMetadata": Dict[str, str],
+        "error": SceneErrorTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListComponentTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListComponentTypesRequestRequestTypeDef",
     {
         "workspaceId": str,
     },
 )
 _OptionalListComponentTypesRequestRequestTypeDef = TypedDict(
@@ -1185,15 +1200,15 @@
     pass
 
 ListScenesResponseTypeDef = TypedDict(
     "ListScenesResponseTypeDef",
     {
         "sceneSummaries": List[SceneSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListSyncResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListSyncResourcesRequestRequestTypeDef",
     {
         "workspaceId": str,
@@ -1216,15 +1231,15 @@
     pass
 
 ListWorkspacesResponseTypeDef = TypedDict(
     "ListWorkspacesResponseTypeDef",
     {
         "workspaceSummaries": List[WorkspaceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TabularConditionsTypeDef = TypedDict(
     "TabularConditionsTypeDef",
     {
         "orderBy": Sequence[OrderByTypeDef],
@@ -1272,24 +1287,24 @@
     pass
 
 GetPricingPlanResponseTypeDef = TypedDict(
     "GetPricingPlanResponseTypeDef",
     {
         "currentPricingPlan": PricingPlanTypeDef,
         "pendingPricingPlan": PricingPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePricingPlanResponseTypeDef = TypedDict(
     "UpdatePricingPlanResponseTypeDef",
     {
         "currentPricingPlan": PricingPlanTypeDef,
         "pendingPricingPlan": PricingPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentRequestTypeDef = TypedDict(
     "ComponentRequestTypeDef",
     {
         "description": str,
@@ -1335,15 +1350,15 @@
 
 GetPropertyValueResponseTypeDef = TypedDict(
     "GetPropertyValueResponseTypeDef",
     {
         "propertyValues": Dict[str, PropertyLatestValueTypeDef],
         "nextToken": str,
         "tabularPropertyValues": List[List[Dict[str, "DataValueTypeDef"]]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredComponentTypeSummaryTypeDef = TypedDict(
     "_RequiredComponentTypeSummaryTypeDef",
     {
         "arn": str,
@@ -1397,15 +1412,15 @@
         "arn": str,
         "workspaceId": str,
         "syncSource": str,
         "syncRole": str,
         "status": SyncJobStatusTypeDef,
         "creationDateTime": datetime,
         "updateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SyncJobSummaryTypeDef = TypedDict(
     "SyncJobSummaryTypeDef",
     {
         "arn": str,
@@ -1489,15 +1504,15 @@
 )
 
 GetPropertyValueHistoryResponseTypeDef = TypedDict(
     "GetPropertyValueHistoryResponseTypeDef",
     {
         "propertyValues": List[PropertyValueHistoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEntityRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEntityRequestRequestTypeDef",
     {
         "workspaceId": str,
@@ -1614,53 +1629,53 @@
         "arn": str,
         "isAbstract": bool,
         "isSchemaInitialized": bool,
         "status": StatusTypeDef,
         "propertyGroups": Dict[str, PropertyGroupResponseTypeDef],
         "syncSource": str,
         "componentTypeName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComponentTypesResponseTypeDef = TypedDict(
     "ListComponentTypesResponseTypeDef",
     {
         "workspaceId": str,
         "componentTypeSummaries": List[ComponentTypeSummaryTypeDef],
         "nextToken": str,
         "maxResults": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitiesResponseTypeDef = TypedDict(
     "ListEntitiesResponseTypeDef",
     {
         "entitySummaries": List[EntitySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSyncJobsResponseTypeDef = TypedDict(
     "ListSyncJobsResponseTypeDef",
     {
         "syncJobSummaries": List[SyncJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSyncResourcesResponseTypeDef = TypedDict(
     "ListSyncResourcesResponseTypeDef",
     {
         "syncResources": List[SyncResourceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEntityResponseTypeDef = TypedDict(
     "GetEntityResponseTypeDef",
     {
         "entityId": str,
@@ -1671,25 +1686,25 @@
         "description": str,
         "components": Dict[str, ComponentResponseTypeDef],
         "parentEntityId": str,
         "hasChildEntities": bool,
         "creationDateTime": datetime,
         "updateDateTime": datetime,
         "syncSource": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutPropertyErrorEntryTypeDef = TypedDict(
     "BatchPutPropertyErrorEntryTypeDef",
     {
         "errors": List[BatchPutPropertyErrorTypeDef],
     },
 )
 
 BatchPutPropertyValuesResponseTypeDef = TypedDict(
     "BatchPutPropertyValuesResponseTypeDef",
     {
         "errorEntries": List[BatchPutPropertyErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/PKG-INFO` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iottwinmaker
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTTwinMaker 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTTwinMaker 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iottwinmaker"></a>
 
 # types-aiobotocore-iottwinmaker
 
 [![PyPI - types-aiobotocore-iottwinmaker](https://img.shields.io/pypi/v/types-aiobotocore-iottwinmaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iottwinmaker)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iottwinmaker.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iottwinmaker)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iottwinmaker?color=blue)](https://pypistats.org/packages/types-aiobotocore-iottwinmaker)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTTwinMaker 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker)
+[aiobotocore.IoTTwinMaker 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iottwinmaker.html#IoTTwinMaker)
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
 [types-aiobotocore-iottwinmaker docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iottwinmaker/).
 
 See how it helps to find and fix potential bugs:
 
@@ -281,14 +281,15 @@
     OrderByTimeType,
     OrderType,
     ParentEntityUpdateTypeType,
     PricingModeType,
     PricingTierType,
     PropertyGroupUpdateTypeType,
     PropertyUpdateTypeType,
+    SceneErrorCodeType,
     ScopeType,
     StateType,
     SyncJobStateType,
     SyncResourceStateType,
     SyncResourceTypeType,
     TypeType,
     UpdateReasonType,
@@ -308,89 +309,90 @@
 ### Typed dictionaries
 
 `types_aiobotocore_iottwinmaker.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iottwinmaker.type_defs import (
-    ResponseMetadataTypeDef,
     BundleInformationTypeDef,
     ColumnDescriptionTypeDef,
     ComponentPropertyGroupRequestTypeDef,
     ComponentPropertyGroupResponseTypeDef,
     PropertyDefinitionRequestTypeDef,
     PropertyGroupRequestTypeDef,
+    CreateComponentTypeResponseTypeDef,
+    CreateEntityResponseTypeDef,
     CreateSceneRequestRequestTypeDef,
+    CreateSceneResponseTypeDef,
     CreateSyncJobRequestRequestTypeDef,
+    CreateSyncJobResponseTypeDef,
     CreateWorkspaceRequestRequestTypeDef,
+    CreateWorkspaceResponseTypeDef,
     LambdaFunctionTypeDef,
     RelationshipTypeDef,
     RelationshipValueTypeDef,
     DeleteComponentTypeRequestRequestTypeDef,
+    DeleteComponentTypeResponseTypeDef,
     DeleteEntityRequestRequestTypeDef,
+    DeleteEntityResponseTypeDef,
     DeleteSceneRequestRequestTypeDef,
     DeleteSyncJobRequestRequestTypeDef,
+    DeleteSyncJobResponseTypeDef,
     DeleteWorkspaceRequestRequestTypeDef,
     EntityPropertyReferenceTypeDef,
     ErrorDetailsTypeDef,
     ExecuteQueryRequestRequestTypeDef,
     RowTypeDef,
     GetComponentTypeRequestRequestTypeDef,
     PropertyDefinitionResponseTypeDef,
     PropertyGroupResponseTypeDef,
     GetEntityRequestRequestTypeDef,
     InterpolationParametersTypeDef,
     PropertyFilterTypeDef,
     GetSceneRequestRequestTypeDef,
+    SceneErrorTypeDef,
     GetSyncJobRequestRequestTypeDef,
     GetWorkspaceRequestRequestTypeDef,
+    GetWorkspaceResponseTypeDef,
     ListComponentTypesFilterTypeDef,
     ListEntitiesFilterTypeDef,
     ListScenesRequestRequestTypeDef,
     SceneSummaryTypeDef,
     ListSyncJobsRequestRequestTypeDef,
     SyncResourceFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWorkspacesRequestRequestTypeDef,
     WorkspaceSummaryTypeDef,
     OrderByTypeDef,
     ParentEntityUpdateRequestTypeDef,
     PropertyValueTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    UpdatePricingPlanRequestRequestTypeDef,
-    UpdateSceneRequestRequestTypeDef,
-    UpdateWorkspaceRequestRequestTypeDef,
-    CreateComponentTypeResponseTypeDef,
-    CreateEntityResponseTypeDef,
-    CreateSceneResponseTypeDef,
-    CreateSyncJobResponseTypeDef,
-    CreateWorkspaceResponseTypeDef,
-    DeleteComponentTypeResponseTypeDef,
-    DeleteEntityResponseTypeDef,
-    DeleteSyncJobResponseTypeDef,
-    GetSceneResponseTypeDef,
-    GetWorkspaceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateComponentTypeResponseTypeDef,
     UpdateEntityResponseTypeDef,
+    UpdatePricingPlanRequestRequestTypeDef,
+    UpdateSceneRequestRequestTypeDef,
     UpdateSceneResponseTypeDef,
+    UpdateWorkspaceRequestRequestTypeDef,
     UpdateWorkspaceResponseTypeDef,
     PricingPlanTypeDef,
     PropertyRequestTypeDef,
     DataConnectorTypeDef,
     DataTypeTypeDef,
     DataValueTypeDef,
     PropertyLatestValueTypeDef,
     StatusTypeDef,
     SyncJobStatusTypeDef,
     SyncResourceStatusTypeDef,
     ExecuteQueryResponseTypeDef,
     PropertyResponseTypeDef,
     GetPropertyValueHistoryRequestRequestTypeDef,
+    GetSceneResponseTypeDef,
     ListComponentTypesRequestRequestTypeDef,
     ListEntitiesRequestRequestTypeDef,
     ListScenesResponseTypeDef,
     ListSyncResourcesRequestRequestTypeDef,
     ListWorkspacesResponseTypeDef,
     TabularConditionsTypeDef,
     PropertyValueEntryTypeDef,
@@ -423,54 +425,54 @@
     ListSyncResourcesResponseTypeDef,
     GetEntityResponseTypeDef,
     BatchPutPropertyErrorEntryTypeDef,
     BatchPutPropertyValuesResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> BundleInformationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-iottwinmaker-2.5.0.post1/types_aiobotocore_iottwinmaker.egg-info/SOURCES.txt` & `types-aiobotocore-iottwinmaker-2.5.1/types_aiobotocore_iottwinmaker.egg-info/SOURCES.txt`

 * *Files identical despite different names*

