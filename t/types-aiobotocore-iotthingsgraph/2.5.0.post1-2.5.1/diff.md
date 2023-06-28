# Comparing `tmp/types-aiobotocore-iotthingsgraph-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotthingsgraph-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotthingsgraph-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:48 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotthingsgraph-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1.tar` & `types-aiobotocore-iotthingsgraph-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.847318 types-aiobotocore-iotthingsgraph-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19337 2023-03-11 12:26:48.843318 types-aiobotocore-iotthingsgraph-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17738 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:48.847318 types-aiobotocore-iotthingsgraph-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.835318 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/
--rw-r--r--   0 runner    (1001) docker     (123)     2827 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2826 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    31326 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    31272 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10986 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10984 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13766 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    13753 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    33705 2023-03-11 12:16:32.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    33658 2023-03-11 12:16:32.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:31.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.843318 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19337 2023-03-11 12:26:48.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:48.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:48.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:48.000000 types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.206157 types-aiobotocore-iotthingsgraph-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19336 2023-06-28 01:43:40.206157 types-aiobotocore-iotthingsgraph-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17743 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.206157 types-aiobotocore-iotthingsgraph-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.206157 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/
+-rw-r--r--   0 runner    (1001) docker     (123)     2827 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2826 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31325 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31271 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11195 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11193 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13666 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13654 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    33777 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33730 2023-06-28 01:33:10.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:09.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.206157 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19336 2023-06-28 01:43:40.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:40.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:40.000000 types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/LICENSE` & `types-aiobotocore-iotthingsgraph-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotthingsgraph-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotthingsgraph
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTThingsGraph 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTThingsGraph 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotthingsgraph"></a>
 
 # types-aiobotocore-iotthingsgraph
 
 [![PyPI - types-aiobotocore-iotthingsgraph](https://img.shields.io/pypi/v/types-aiobotocore-iotthingsgraph.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotthingsgraph)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotthingsgraph.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotthingsgraph)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotthingsgraph?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotthingsgraph)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTThingsGraph 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
+[aiobotocore.IoTThingsGraph 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
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
 [types-aiobotocore-iotthingsgraph docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/).
 
 See how it helps to find and fix potential bugs:
 
@@ -375,90 +375,90 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotthingsgraph.type_defs import (
     AssociateEntityToThingRequestRequestTypeDef,
     DefinitionDocumentTypeDef,
     FlowTemplateSummaryTypeDef,
-    ResponseMetadataTypeDef,
     MetricsConfigurationTypeDef,
     TagTypeDef,
     SystemInstanceSummaryTypeDef,
     SystemTemplateSummaryTypeDef,
     DeleteFlowTemplateRequestRequestTypeDef,
+    DeleteNamespaceResponseTypeDef,
     DeleteSystemInstanceRequestRequestTypeDef,
     DeleteSystemTemplateRequestRequestTypeDef,
     DependencyRevisionTypeDef,
     DeploySystemInstanceRequestRequestTypeDef,
     DeprecateFlowTemplateRequestRequestTypeDef,
     DeprecateSystemTemplateRequestRequestTypeDef,
     DescribeNamespaceRequestRequestTypeDef,
+    DescribeNamespaceResponseTypeDef,
     DissociateEntityFromThingRequestRequestTypeDef,
     EntityFilterTypeDef,
     FlowExecutionMessageTypeDef,
     FlowExecutionSummaryTypeDef,
     FlowTemplateFilterTypeDef,
     GetEntitiesRequestRequestTypeDef,
     GetFlowTemplateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
     GetFlowTemplateRevisionsRequestRequestTypeDef,
+    GetNamespaceDeletionStatusResponseTypeDef,
     GetSystemInstanceRequestRequestTypeDef,
     GetSystemTemplateRequestRequestTypeDef,
+    GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
     GetSystemTemplateRevisionsRequestRequestTypeDef,
     GetUploadStatusRequestRequestTypeDef,
+    GetUploadStatusResponseTypeDef,
+    ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
     ListFlowExecutionMessagesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SearchFlowExecutionsRequestRequestTypeDef,
+    SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
     SystemInstanceFilterTypeDef,
     SystemTemplateFilterTypeDef,
     SearchThingsRequestRequestTypeDef,
+    SearchThingsRequestSearchThingsPaginateTypeDef,
     ThingTypeDef,
     UndeploySystemInstanceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UploadEntityDefinitionsResponseTypeDef,
     CreateFlowTemplateRequestRequestTypeDef,
     CreateSystemTemplateRequestRequestTypeDef,
     EntityDescriptionTypeDef,
     UpdateFlowTemplateRequestRequestTypeDef,
     UpdateSystemTemplateRequestRequestTypeDef,
     UploadEntityDefinitionsRequestRequestTypeDef,
-    FlowTemplateDescriptionTypeDef,
     CreateFlowTemplateResponseTypeDef,
-    DeleteNamespaceResponseTypeDef,
-    DescribeNamespaceResponseTypeDef,
+    FlowTemplateDescriptionTypeDef,
     GetFlowTemplateRevisionsResponseTypeDef,
-    GetNamespaceDeletionStatusResponseTypeDef,
-    GetUploadStatusResponseTypeDef,
     SearchFlowTemplatesResponseTypeDef,
     UpdateFlowTemplateResponseTypeDef,
-    UploadEntityDefinitionsResponseTypeDef,
     CreateSystemInstanceRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSystemInstanceResponseTypeDef,
     DeploySystemInstanceResponseTypeDef,
     SearchSystemInstancesResponseTypeDef,
     UndeploySystemInstanceResponseTypeDef,
     CreateSystemTemplateResponseTypeDef,
     GetSystemTemplateRevisionsResponseTypeDef,
     SearchSystemTemplatesResponseTypeDef,
     SystemTemplateDescriptionTypeDef,
     UpdateSystemTemplateResponseTypeDef,
     SystemInstanceDescriptionTypeDef,
     SearchEntitiesRequestRequestTypeDef,
+    SearchEntitiesRequestSearchEntitiesPaginateTypeDef,
     ListFlowExecutionMessagesResponseTypeDef,
     SearchFlowExecutionsResponseTypeDef,
     SearchFlowTemplatesRequestRequestTypeDef,
-    GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-    GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-    ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    SearchEntitiesRequestSearchEntitiesPaginateTypeDef,
-    SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
     SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef,
-    SearchThingsRequestSearchThingsPaginateTypeDef,
     SearchSystemInstancesRequestRequestTypeDef,
     SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef,
     SearchSystemTemplatesRequestRequestTypeDef,
     SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef,
     SearchThingsResponseTypeDef,
     GetEntitiesResponseTypeDef,
     SearchEntitiesResponseTypeDef,
@@ -475,43 +475,43 @@
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/README.md` & `types-aiobotocore-iotthingsgraph-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotthingsgraph"></a>
 
 # types-aiobotocore-iotthingsgraph
 
 [![PyPI - types-aiobotocore-iotthingsgraph](https://img.shields.io/pypi/v/types-aiobotocore-iotthingsgraph.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotthingsgraph)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotthingsgraph.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotthingsgraph)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotthingsgraph?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotthingsgraph)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTThingsGraph 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
+[aiobotocore.IoTThingsGraph 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
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
 [types-aiobotocore-iotthingsgraph docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/).
 
 See how it helps to find and fix potential bugs:
 
@@ -342,90 +342,90 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotthingsgraph.type_defs import (
     AssociateEntityToThingRequestRequestTypeDef,
     DefinitionDocumentTypeDef,
     FlowTemplateSummaryTypeDef,
-    ResponseMetadataTypeDef,
     MetricsConfigurationTypeDef,
     TagTypeDef,
     SystemInstanceSummaryTypeDef,
     SystemTemplateSummaryTypeDef,
     DeleteFlowTemplateRequestRequestTypeDef,
+    DeleteNamespaceResponseTypeDef,
     DeleteSystemInstanceRequestRequestTypeDef,
     DeleteSystemTemplateRequestRequestTypeDef,
     DependencyRevisionTypeDef,
     DeploySystemInstanceRequestRequestTypeDef,
     DeprecateFlowTemplateRequestRequestTypeDef,
     DeprecateSystemTemplateRequestRequestTypeDef,
     DescribeNamespaceRequestRequestTypeDef,
+    DescribeNamespaceResponseTypeDef,
     DissociateEntityFromThingRequestRequestTypeDef,
     EntityFilterTypeDef,
     FlowExecutionMessageTypeDef,
     FlowExecutionSummaryTypeDef,
     FlowTemplateFilterTypeDef,
     GetEntitiesRequestRequestTypeDef,
     GetFlowTemplateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
     GetFlowTemplateRevisionsRequestRequestTypeDef,
+    GetNamespaceDeletionStatusResponseTypeDef,
     GetSystemInstanceRequestRequestTypeDef,
     GetSystemTemplateRequestRequestTypeDef,
+    GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
     GetSystemTemplateRevisionsRequestRequestTypeDef,
     GetUploadStatusRequestRequestTypeDef,
+    GetUploadStatusResponseTypeDef,
+    ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
     ListFlowExecutionMessagesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SearchFlowExecutionsRequestRequestTypeDef,
+    SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
     SystemInstanceFilterTypeDef,
     SystemTemplateFilterTypeDef,
     SearchThingsRequestRequestTypeDef,
+    SearchThingsRequestSearchThingsPaginateTypeDef,
     ThingTypeDef,
     UndeploySystemInstanceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UploadEntityDefinitionsResponseTypeDef,
     CreateFlowTemplateRequestRequestTypeDef,
     CreateSystemTemplateRequestRequestTypeDef,
     EntityDescriptionTypeDef,
     UpdateFlowTemplateRequestRequestTypeDef,
     UpdateSystemTemplateRequestRequestTypeDef,
     UploadEntityDefinitionsRequestRequestTypeDef,
-    FlowTemplateDescriptionTypeDef,
     CreateFlowTemplateResponseTypeDef,
-    DeleteNamespaceResponseTypeDef,
-    DescribeNamespaceResponseTypeDef,
+    FlowTemplateDescriptionTypeDef,
     GetFlowTemplateRevisionsResponseTypeDef,
-    GetNamespaceDeletionStatusResponseTypeDef,
-    GetUploadStatusResponseTypeDef,
     SearchFlowTemplatesResponseTypeDef,
     UpdateFlowTemplateResponseTypeDef,
-    UploadEntityDefinitionsResponseTypeDef,
     CreateSystemInstanceRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSystemInstanceResponseTypeDef,
     DeploySystemInstanceResponseTypeDef,
     SearchSystemInstancesResponseTypeDef,
     UndeploySystemInstanceResponseTypeDef,
     CreateSystemTemplateResponseTypeDef,
     GetSystemTemplateRevisionsResponseTypeDef,
     SearchSystemTemplatesResponseTypeDef,
     SystemTemplateDescriptionTypeDef,
     UpdateSystemTemplateResponseTypeDef,
     SystemInstanceDescriptionTypeDef,
     SearchEntitiesRequestRequestTypeDef,
+    SearchEntitiesRequestSearchEntitiesPaginateTypeDef,
     ListFlowExecutionMessagesResponseTypeDef,
     SearchFlowExecutionsResponseTypeDef,
     SearchFlowTemplatesRequestRequestTypeDef,
-    GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-    GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-    ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    SearchEntitiesRequestSearchEntitiesPaginateTypeDef,
-    SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
     SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef,
-    SearchThingsRequestSearchThingsPaginateTypeDef,
     SearchSystemInstancesRequestRequestTypeDef,
     SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef,
     SearchSystemTemplatesRequestRequestTypeDef,
     SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef,
     SearchThingsResponseTypeDef,
     GetEntitiesResponseTypeDef,
     SearchEntitiesResponseTypeDef,
@@ -442,43 +442,43 @@
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/setup.py` & `types-aiobotocore-iotthingsgraph-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotthingsgraph.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotthingsgraph",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotthingsgraph"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTThingsGraph 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTThingsGraph 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/"
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/__init__.py` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/__init__.pyi` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/__main__.py` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTThingsGraph 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTThingsGraph 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph\nOther"
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/client.py` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -210,15 +210,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.delete_system_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/client/#delete_system_template)
         """
 
     async def deploy_system_instance(self, *, id: str = ...) -> DeploySystemInstanceResponseTypeDef:
         """
         **Greengrass and Cloud Deployments** Deploys the system instance to the target
-        specified in `CreateSystemInstance` .
+        specified in `CreateSystemInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.deploy_system_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/client/#deploy_system_instance)
         """
 
     async def deprecate_flow_template(self, *, id: str) -> Dict[str, Any]:
         """
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/client.pyi` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -195,15 +195,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.delete_system_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/client/#delete_system_template)
         """
     async def deploy_system_instance(self, *, id: str = ...) -> DeploySystemInstanceResponseTypeDef:
         """
         **Greengrass and Cloud Deployments** Deploys the system instance to the target
-        specified in `CreateSystemInstance` .
+        specified in `CreateSystemInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Client.deploy_system_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/client/#deploy_system_instance)
         """
     async def deprecate_flow_template(self, *, id: str) -> Dict[str, Any]:
         """
         Deprecates the specified workflow.
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/literals.py` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/literals.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DefinitionLanguageType",
     "DeploymentTargetType",
     "EntityFilterNameType",
     "EntityTypeType",
     "FlowExecutionEventTypeType",
     "FlowExecutionStatusType",
@@ -46,15 +45,14 @@
     "IoTThingsGraphServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 DefinitionLanguageType = Literal["GRAPHQL"]
 DeploymentTargetType = Literal["CLOUD", "GREENGRASS"]
 EntityFilterNameType = Literal["NAME", "NAMESPACE", "REFERENCED_ENTITY_ID", "SEMANTIC_TYPE_PATH"]
 EntityTypeType = Literal[
     "ACTION",
     "CAPABILITY",
     "DEVICE",
@@ -171,14 +169,15 @@
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
@@ -257,14 +256,15 @@
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
@@ -275,14 +275,15 @@
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
@@ -318,14 +319,15 @@
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
@@ -344,16 +346,19 @@
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
@@ -437,15 +442,17 @@
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/literals.pyi` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DefinitionLanguageType",
     "DeploymentTargetType",
     "EntityFilterNameType",
     "EntityTypeType",
     "FlowExecutionEventTypeType",
     "FlowExecutionStatusType",
@@ -45,14 +46,15 @@
     "IoTThingsGraphServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 DefinitionLanguageType = Literal["GRAPHQL"]
 DeploymentTargetType = Literal["CLOUD", "GREENGRASS"]
 EntityFilterNameType = Literal["NAME", "NAMESPACE", "REFERENCED_ENTITY_ID", "SEMANTIC_TYPE_PATH"]
 EntityTypeType = Literal[
     "ACTION",
     "CAPABILITY",
     "DEVICE",
@@ -169,14 +171,15 @@
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
@@ -255,14 +258,15 @@
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
@@ -273,14 +277,15 @@
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
@@ -316,14 +321,15 @@
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
@@ -342,16 +348,19 @@
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
@@ -435,15 +444,17 @@
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/paginator.py` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         search_flow_executions_paginator: SearchFlowExecutionsPaginator = client.get_paginator("search_flow_executions")
         search_flow_templates_paginator: SearchFlowTemplatesPaginator = client.get_paginator("search_flow_templates")
         search_system_instances_paginator: SearchSystemInstancesPaginator = client.get_paginator("search_system_instances")
         search_system_templates_paginator: SearchSystemTemplatesPaginator = client.get_paginator("search_system_templates")
         search_things_paginator: SearchThingsPaginator = client.get_paginator("search_things")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EntityTypeType
 from .type_defs import (
     EntityFilterTypeDef,
@@ -60,20 +59,14 @@
     SearchSystemInstancesResponseTypeDef,
     SearchSystemTemplatesResponseTypeDef,
     SearchThingsResponseTypeDef,
     SystemInstanceFilterTypeDef,
     SystemTemplateFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetFlowTemplateRevisionsPaginator",
     "GetSystemTemplateRevisionsPaginator",
     "ListFlowExecutionMessagesPaginator",
     "ListTagsForResourcePaginator",
     "SearchEntitiesPaginator",
     "SearchFlowExecutionsPaginator",
@@ -97,60 +90,60 @@
 class GetFlowTemplateRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetFlowTemplateRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getflowtemplaterevisionspaginator)
     """
 
     def paginate(
-        self, *, id: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, id: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetFlowTemplateRevisionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetFlowTemplateRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getflowtemplaterevisionspaginator)
         """
 
 
 class GetSystemTemplateRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetSystemTemplateRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getsystemtemplaterevisionspaginator)
     """
 
     def paginate(
-        self, *, id: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, id: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSystemTemplateRevisionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetSystemTemplateRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getsystemtemplaterevisionspaginator)
         """
 
 
 class ListFlowExecutionMessagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListFlowExecutionMessages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listflowexecutionmessagespaginator)
     """
 
     def paginate(
-        self, *, flowExecutionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, flowExecutionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFlowExecutionMessagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListFlowExecutionMessages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listflowexecutionmessagespaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listtagsforresourcepaginator)
         """
 
 
@@ -162,15 +155,15 @@
 
     def paginate(
         self,
         *,
         entityTypes: Sequence[EntityTypeType],
         filters: Sequence[EntityFilterTypeDef] = ...,
         namespaceVersion: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchEntitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchEntities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchentitiespaginator)
         """
 
 
@@ -183,15 +176,15 @@
     def paginate(
         self,
         *,
         systemInstanceId: str,
         flowExecutionId: str = ...,
         startTime: Union[datetime, str] = ...,
         endTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchFlowExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchFlowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchflowexecutionspaginator)
         """
 
 
@@ -201,15 +194,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchflowtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FlowTemplateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchFlowTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchFlowTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchflowtemplatespaginator)
         """
 
 
@@ -219,15 +212,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsysteminstancespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SystemInstanceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSystemInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchSystemInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsysteminstancespaginator)
         """
 
 
@@ -237,15 +230,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsystemtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SystemTemplateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSystemTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchSystemTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsystemtemplatespaginator)
         """
 
 
@@ -256,13 +249,13 @@
     """
 
     def paginate(
         self,
         *,
         entityId: str,
         namespaceVersion: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchThingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchThings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchthingspaginator)
         """
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/paginator.pyi` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         search_flow_executions_paginator: SearchFlowExecutionsPaginator = client.get_paginator("search_flow_executions")
         search_flow_templates_paginator: SearchFlowTemplatesPaginator = client.get_paginator("search_flow_templates")
         search_system_instances_paginator: SearchSystemInstancesPaginator = client.get_paginator("search_system_instances")
         search_system_templates_paginator: SearchSystemTemplatesPaginator = client.get_paginator("search_system_templates")
         search_things_paginator: SearchThingsPaginator = client.get_paginator("search_things")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EntityTypeType
 from .type_defs import (
     EntityFilterTypeDef,
@@ -60,19 +59,14 @@
     SearchSystemInstancesResponseTypeDef,
     SearchSystemTemplatesResponseTypeDef,
     SearchThingsResponseTypeDef,
     SystemInstanceFilterTypeDef,
     SystemTemplateFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetFlowTemplateRevisionsPaginator",
     "GetSystemTemplateRevisionsPaginator",
     "ListFlowExecutionMessagesPaginator",
     "ListTagsForResourcePaginator",
     "SearchEntitiesPaginator",
     "SearchFlowExecutionsPaginator",
@@ -93,57 +87,57 @@
 class GetFlowTemplateRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetFlowTemplateRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getflowtemplaterevisionspaginator)
     """
 
     def paginate(
-        self, *, id: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, id: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetFlowTemplateRevisionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetFlowTemplateRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getflowtemplaterevisionspaginator)
         """
 
 class GetSystemTemplateRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetSystemTemplateRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getsystemtemplaterevisionspaginator)
     """
 
     def paginate(
-        self, *, id: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, id: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSystemTemplateRevisionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.GetSystemTemplateRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#getsystemtemplaterevisionspaginator)
         """
 
 class ListFlowExecutionMessagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListFlowExecutionMessages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listflowexecutionmessagespaginator)
     """
 
     def paginate(
-        self, *, flowExecutionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, flowExecutionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFlowExecutionMessagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListFlowExecutionMessages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listflowexecutionmessagespaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#listtagsforresourcepaginator)
         """
 
 class SearchEntitiesPaginator(AioPaginator):
@@ -154,15 +148,15 @@
 
     def paginate(
         self,
         *,
         entityTypes: Sequence[EntityTypeType],
         filters: Sequence[EntityFilterTypeDef] = ...,
         namespaceVersion: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchEntitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchEntities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchentitiespaginator)
         """
 
 class SearchFlowExecutionsPaginator(AioPaginator):
@@ -174,15 +168,15 @@
     def paginate(
         self,
         *,
         systemInstanceId: str,
         flowExecutionId: str = ...,
         startTime: Union[datetime, str] = ...,
         endTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchFlowExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchFlowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchflowexecutionspaginator)
         """
 
 class SearchFlowTemplatesPaginator(AioPaginator):
@@ -191,15 +185,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchflowtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FlowTemplateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchFlowTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchFlowTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchflowtemplatespaginator)
         """
 
 class SearchSystemInstancesPaginator(AioPaginator):
@@ -208,15 +202,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsysteminstancespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SystemInstanceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSystemInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchSystemInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsysteminstancespaginator)
         """
 
 class SearchSystemTemplatesPaginator(AioPaginator):
@@ -225,15 +219,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsystemtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[SystemTemplateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSystemTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchSystemTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchsystemtemplatespaginator)
         """
 
 class SearchThingsPaginator(AioPaginator):
@@ -243,13 +237,13 @@
     """
 
     def paginate(
         self,
         *,
         entityId: str,
         namespaceVersion: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchThingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph.Paginator.SearchThings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/paginators/#searchthingspaginator)
         """
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/type_defs.py` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -37,90 +37,90 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateEntityToThingRequestRequestTypeDef",
     "DefinitionDocumentTypeDef",
     "FlowTemplateSummaryTypeDef",
-    "ResponseMetadataTypeDef",
     "MetricsConfigurationTypeDef",
     "TagTypeDef",
     "SystemInstanceSummaryTypeDef",
     "SystemTemplateSummaryTypeDef",
     "DeleteFlowTemplateRequestRequestTypeDef",
+    "DeleteNamespaceResponseTypeDef",
     "DeleteSystemInstanceRequestRequestTypeDef",
     "DeleteSystemTemplateRequestRequestTypeDef",
     "DependencyRevisionTypeDef",
     "DeploySystemInstanceRequestRequestTypeDef",
     "DeprecateFlowTemplateRequestRequestTypeDef",
     "DeprecateSystemTemplateRequestRequestTypeDef",
     "DescribeNamespaceRequestRequestTypeDef",
+    "DescribeNamespaceResponseTypeDef",
     "DissociateEntityFromThingRequestRequestTypeDef",
     "EntityFilterTypeDef",
     "FlowExecutionMessageTypeDef",
     "FlowExecutionSummaryTypeDef",
     "FlowTemplateFilterTypeDef",
     "GetEntitiesRequestRequestTypeDef",
     "GetFlowTemplateRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
     "GetFlowTemplateRevisionsRequestRequestTypeDef",
+    "GetNamespaceDeletionStatusResponseTypeDef",
     "GetSystemInstanceRequestRequestTypeDef",
     "GetSystemTemplateRequestRequestTypeDef",
+    "GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
     "GetSystemTemplateRevisionsRequestRequestTypeDef",
     "GetUploadStatusRequestRequestTypeDef",
+    "GetUploadStatusResponseTypeDef",
+    "ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
     "ListFlowExecutionMessagesRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchFlowExecutionsRequestRequestTypeDef",
+    "SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
     "SystemInstanceFilterTypeDef",
     "SystemTemplateFilterTypeDef",
     "SearchThingsRequestRequestTypeDef",
+    "SearchThingsRequestSearchThingsPaginateTypeDef",
     "ThingTypeDef",
     "UndeploySystemInstanceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UploadEntityDefinitionsResponseTypeDef",
     "CreateFlowTemplateRequestRequestTypeDef",
     "CreateSystemTemplateRequestRequestTypeDef",
     "EntityDescriptionTypeDef",
     "UpdateFlowTemplateRequestRequestTypeDef",
     "UpdateSystemTemplateRequestRequestTypeDef",
     "UploadEntityDefinitionsRequestRequestTypeDef",
-    "FlowTemplateDescriptionTypeDef",
     "CreateFlowTemplateResponseTypeDef",
-    "DeleteNamespaceResponseTypeDef",
-    "DescribeNamespaceResponseTypeDef",
+    "FlowTemplateDescriptionTypeDef",
     "GetFlowTemplateRevisionsResponseTypeDef",
-    "GetNamespaceDeletionStatusResponseTypeDef",
-    "GetUploadStatusResponseTypeDef",
     "SearchFlowTemplatesResponseTypeDef",
     "UpdateFlowTemplateResponseTypeDef",
-    "UploadEntityDefinitionsResponseTypeDef",
     "CreateSystemInstanceRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateSystemInstanceResponseTypeDef",
     "DeploySystemInstanceResponseTypeDef",
     "SearchSystemInstancesResponseTypeDef",
     "UndeploySystemInstanceResponseTypeDef",
     "CreateSystemTemplateResponseTypeDef",
     "GetSystemTemplateRevisionsResponseTypeDef",
     "SearchSystemTemplatesResponseTypeDef",
     "SystemTemplateDescriptionTypeDef",
     "UpdateSystemTemplateResponseTypeDef",
     "SystemInstanceDescriptionTypeDef",
     "SearchEntitiesRequestRequestTypeDef",
+    "SearchEntitiesRequestSearchEntitiesPaginateTypeDef",
     "ListFlowExecutionMessagesResponseTypeDef",
     "SearchFlowExecutionsResponseTypeDef",
     "SearchFlowTemplatesRequestRequestTypeDef",
-    "GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
-    "GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
-    "ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "SearchEntitiesRequestSearchEntitiesPaginateTypeDef",
-    "SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
     "SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef",
-    "SearchThingsRequestSearchThingsPaginateTypeDef",
     "SearchSystemInstancesRequestRequestTypeDef",
     "SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef",
     "SearchSystemTemplatesRequestRequestTypeDef",
     "SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef",
     "SearchThingsResponseTypeDef",
     "GetEntitiesResponseTypeDef",
     "SearchEntitiesResponseTypeDef",
@@ -167,25 +167,14 @@
         "arn": str,
         "revisionNumber": int,
         "createdAt": datetime,
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
 MetricsConfigurationTypeDef = TypedDict(
     "MetricsConfigurationTypeDef",
     {
         "cloudMetricEnabled": bool,
         "metricRuleRoleArn": str,
     },
     total=False,
@@ -229,14 +218,23 @@
 DeleteFlowTemplateRequestRequestTypeDef = TypedDict(
     "DeleteFlowTemplateRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteNamespaceResponseTypeDef = TypedDict(
+    "DeleteNamespaceResponseTypeDef",
+    {
+        "namespaceArn": str,
+        "namespaceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSystemInstanceRequestRequestTypeDef = TypedDict(
     "DeleteSystemInstanceRequestRequestTypeDef",
     {
         "id": str,
     },
     total=False,
 )
@@ -283,14 +281,26 @@
     "DescribeNamespaceRequestRequestTypeDef",
     {
         "namespaceName": str,
     },
     total=False,
 )
 
+DescribeNamespaceResponseTypeDef = TypedDict(
+    "DescribeNamespaceResponseTypeDef",
+    {
+        "namespaceArn": str,
+        "namespaceName": str,
+        "trackingNamespaceName": str,
+        "trackingNamespaceVersion": int,
+        "namespaceVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DissociateEntityFromThingRequestRequestTypeDef = TypedDict(
     "DissociateEntityFromThingRequestRequestTypeDef",
     {
         "thingName": str,
         "entityType": EntityTypeType,
     },
 )
@@ -374,24 +384,36 @@
 
 class GetFlowTemplateRequestRequestTypeDef(
     _RequiredGetFlowTemplateRequestRequestTypeDef, _OptionalGetFlowTemplateRequestRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "id": str,
+    },
+)
+_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef(
+    _RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
+    _OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetFlowTemplateRevisionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetFlowTemplateRevisionsRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalGetFlowTemplateRevisionsRequestRequestTypeDef = TypedDict(
@@ -407,14 +429,26 @@
 class GetFlowTemplateRevisionsRequestRequestTypeDef(
     _RequiredGetFlowTemplateRevisionsRequestRequestTypeDef,
     _OptionalGetFlowTemplateRevisionsRequestRequestTypeDef,
 ):
     pass
 
 
+GetNamespaceDeletionStatusResponseTypeDef = TypedDict(
+    "GetNamespaceDeletionStatusResponseTypeDef",
+    {
+        "namespaceArn": str,
+        "namespaceName": str,
+        "status": NamespaceDeletionStatusType,
+        "errorCode": Literal["VALIDATION_FAILED"],
+        "errorMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSystemInstanceRequestRequestTypeDef = TypedDict(
     "GetSystemInstanceRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -435,14 +469,36 @@
 
 class GetSystemTemplateRequestRequestTypeDef(
     _RequiredGetSystemTemplateRequestRequestTypeDef, _OptionalGetSystemTemplateRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
+    {
+        "id": str,
+    },
+)
+_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef(
+    _RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
+    _OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetSystemTemplateRevisionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSystemTemplateRevisionsRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalGetSystemTemplateRevisionsRequestRequestTypeDef = TypedDict(
@@ -465,14 +521,50 @@
 GetUploadStatusRequestRequestTypeDef = TypedDict(
     "GetUploadStatusRequestRequestTypeDef",
     {
         "uploadId": str,
     },
 )
 
+GetUploadStatusResponseTypeDef = TypedDict(
+    "GetUploadStatusResponseTypeDef",
+    {
+        "uploadId": str,
+        "uploadStatus": UploadStatusType,
+        "namespaceArn": str,
+        "namespaceName": str,
+        "namespaceVersion": int,
+        "failureReason": List[str],
+        "createdDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
+    "_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
+    {
+        "flowExecutionId": str,
+    },
+)
+_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
+    "_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef(
+    _RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
+    _OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFlowExecutionMessagesRequestRequestTypeDef = TypedDict(
     "_RequiredListFlowExecutionMessagesRequestRequestTypeDef",
     {
         "flowExecutionId": str,
     },
 )
 _OptionalListFlowExecutionMessagesRequestRequestTypeDef = TypedDict(
@@ -488,14 +580,36 @@
 class ListFlowExecutionMessagesRequestRequestTypeDef(
     _RequiredListFlowExecutionMessagesRequestRequestTypeDef,
     _OptionalListFlowExecutionMessagesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -511,14 +625,35 @@
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
 
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
 _RequiredSearchFlowExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchFlowExecutionsRequestRequestTypeDef",
     {
         "systemInstanceId": str,
     },
 )
 _OptionalSearchFlowExecutionsRequestRequestTypeDef = TypedDict(
@@ -537,14 +672,39 @@
 class SearchFlowExecutionsRequestRequestTypeDef(
     _RequiredSearchFlowExecutionsRequestRequestTypeDef,
     _OptionalSearchFlowExecutionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+    {
+        "systemInstanceId": str,
+    },
+)
+_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+    {
+        "flowExecutionId": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef(
+    _RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
+    _OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
+):
+    pass
+
+
 SystemInstanceFilterTypeDef = TypedDict(
     "SystemInstanceFilterTypeDef",
     {
         "name": SystemInstanceFilterNameType,
         "value": Sequence[str],
     },
     total=False,
@@ -577,14 +737,37 @@
 
 class SearchThingsRequestRequestTypeDef(
     _RequiredSearchThingsRequestRequestTypeDef, _OptionalSearchThingsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
+    "_RequiredSearchThingsRequestSearchThingsPaginateTypeDef",
+    {
+        "entityId": str,
+    },
+)
+_OptionalSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
+    "_OptionalSearchThingsRequestSearchThingsPaginateTypeDef",
+    {
+        "namespaceVersion": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SearchThingsRequestSearchThingsPaginateTypeDef(
+    _RequiredSearchThingsRequestSearchThingsPaginateTypeDef,
+    _OptionalSearchThingsRequestSearchThingsPaginateTypeDef,
+):
+    pass
+
+
 ThingTypeDef = TypedDict(
     "ThingTypeDef",
     {
         "thingArn": str,
         "thingName": str,
     },
     total=False,
@@ -602,14 +785,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UploadEntityDefinitionsResponseTypeDef = TypedDict(
+    "UploadEntityDefinitionsResponseTypeDef",
+    {
+        "uploadId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFlowTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFlowTemplateRequestRequestTypeDef",
     {
         "definition": DefinitionDocumentTypeDef,
     },
 )
 _OptionalCreateFlowTemplateRequestRequestTypeDef = TypedDict(
@@ -714,110 +905,55 @@
         "document": DefinitionDocumentTypeDef,
         "syncWithPublicNamespace": bool,
         "deprecateExistingEntities": bool,
     },
     total=False,
 )
 
-FlowTemplateDescriptionTypeDef = TypedDict(
-    "FlowTemplateDescriptionTypeDef",
-    {
-        "summary": FlowTemplateSummaryTypeDef,
-        "definition": DefinitionDocumentTypeDef,
-        "validatedNamespaceVersion": int,
-    },
-    total=False,
-)
-
 CreateFlowTemplateResponseTypeDef = TypedDict(
     "CreateFlowTemplateResponseTypeDef",
     {
         "summary": FlowTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteNamespaceResponseTypeDef = TypedDict(
-    "DeleteNamespaceResponseTypeDef",
-    {
-        "namespaceArn": str,
-        "namespaceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeNamespaceResponseTypeDef = TypedDict(
-    "DescribeNamespaceResponseTypeDef",
+FlowTemplateDescriptionTypeDef = TypedDict(
+    "FlowTemplateDescriptionTypeDef",
     {
-        "namespaceArn": str,
-        "namespaceName": str,
-        "trackingNamespaceName": str,
-        "trackingNamespaceVersion": int,
-        "namespaceVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "summary": FlowTemplateSummaryTypeDef,
+        "definition": DefinitionDocumentTypeDef,
+        "validatedNamespaceVersion": int,
     },
+    total=False,
 )
 
 GetFlowTemplateRevisionsResponseTypeDef = TypedDict(
     "GetFlowTemplateRevisionsResponseTypeDef",
     {
         "summaries": List[FlowTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetNamespaceDeletionStatusResponseTypeDef = TypedDict(
-    "GetNamespaceDeletionStatusResponseTypeDef",
-    {
-        "namespaceArn": str,
-        "namespaceName": str,
-        "status": NamespaceDeletionStatusType,
-        "errorCode": Literal["VALIDATION_FAILED"],
-        "errorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUploadStatusResponseTypeDef = TypedDict(
-    "GetUploadStatusResponseTypeDef",
-    {
-        "uploadId": str,
-        "uploadStatus": UploadStatusType,
-        "namespaceArn": str,
-        "namespaceName": str,
-        "namespaceVersion": int,
-        "failureReason": List[str],
-        "createdDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchFlowTemplatesResponseTypeDef = TypedDict(
     "SearchFlowTemplatesResponseTypeDef",
     {
         "summaries": List[FlowTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowTemplateResponseTypeDef = TypedDict(
     "UpdateFlowTemplateResponseTypeDef",
     {
         "summary": FlowTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UploadEntityDefinitionsResponseTypeDef = TypedDict(
-    "UploadEntityDefinitionsResponseTypeDef",
-    {
-        "uploadId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSystemInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSystemInstanceRequestRequestTypeDef",
     {
         "definition": DefinitionDocumentTypeDef,
@@ -845,15 +981,15 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -861,67 +997,67 @@
     },
 )
 
 CreateSystemInstanceResponseTypeDef = TypedDict(
     "CreateSystemInstanceResponseTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploySystemInstanceResponseTypeDef = TypedDict(
     "DeploySystemInstanceResponseTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
         "greengrassDeploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchSystemInstancesResponseTypeDef = TypedDict(
     "SearchSystemInstancesResponseTypeDef",
     {
         "summaries": List[SystemInstanceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UndeploySystemInstanceResponseTypeDef = TypedDict(
     "UndeploySystemInstanceResponseTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSystemTemplateResponseTypeDef = TypedDict(
     "CreateSystemTemplateResponseTypeDef",
     {
         "summary": SystemTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSystemTemplateRevisionsResponseTypeDef = TypedDict(
     "GetSystemTemplateRevisionsResponseTypeDef",
     {
         "summaries": List[SystemTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchSystemTemplatesResponseTypeDef = TypedDict(
     "SearchSystemTemplatesResponseTypeDef",
     {
         "summaries": List[SystemTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SystemTemplateDescriptionTypeDef = TypedDict(
     "SystemTemplateDescriptionTypeDef",
     {
         "summary": SystemTemplateSummaryTypeDef,
@@ -931,15 +1067,15 @@
     total=False,
 )
 
 UpdateSystemTemplateResponseTypeDef = TypedDict(
     "UpdateSystemTemplateResponseTypeDef",
     {
         "summary": SystemTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SystemInstanceDescriptionTypeDef = TypedDict(
     "SystemInstanceDescriptionTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
@@ -973,226 +1109,90 @@
 
 class SearchEntitiesRequestRequestTypeDef(
     _RequiredSearchEntitiesRequestRequestTypeDef, _OptionalSearchEntitiesRequestRequestTypeDef
 ):
     pass
 
 
-ListFlowExecutionMessagesResponseTypeDef = TypedDict(
-    "ListFlowExecutionMessagesResponseTypeDef",
-    {
-        "messages": List[FlowExecutionMessageTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchFlowExecutionsResponseTypeDef = TypedDict(
-    "SearchFlowExecutionsResponseTypeDef",
-    {
-        "summaries": List[FlowExecutionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchFlowTemplatesRequestRequestTypeDef = TypedDict(
-    "SearchFlowTemplatesRequestRequestTypeDef",
-    {
-        "filters": Sequence[FlowTemplateFilterTypeDef],
-        "nextToken": str,
-        "maxResults": int,
-    },
-    total=False,
-)
-
-_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef(
-    _RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-    _OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef(
-    _RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-    _OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
-    "_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
-    {
-        "flowExecutionId": str,
-    },
-)
-_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
-    "_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef(
-    _RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-    _OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
 _RequiredSearchEntitiesRequestSearchEntitiesPaginateTypeDef = TypedDict(
     "_RequiredSearchEntitiesRequestSearchEntitiesPaginateTypeDef",
     {
         "entityTypes": Sequence[EntityTypeType],
     },
 )
 _OptionalSearchEntitiesRequestSearchEntitiesPaginateTypeDef = TypedDict(
     "_OptionalSearchEntitiesRequestSearchEntitiesPaginateTypeDef",
     {
         "filters": Sequence[EntityFilterTypeDef],
         "namespaceVersion": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchEntitiesRequestSearchEntitiesPaginateTypeDef(
     _RequiredSearchEntitiesRequestSearchEntitiesPaginateTypeDef,
     _OptionalSearchEntitiesRequestSearchEntitiesPaginateTypeDef,
 ):
     pass
 
 
-_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+ListFlowExecutionMessagesResponseTypeDef = TypedDict(
+    "ListFlowExecutionMessagesResponseTypeDef",
     {
-        "systemInstanceId": str,
+        "messages": List[FlowExecutionMessageTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+
+SearchFlowExecutionsResponseTypeDef = TypedDict(
+    "SearchFlowExecutionsResponseTypeDef",
     {
-        "flowExecutionId": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "summaries": List[FlowExecutionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef(
-    _RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
-    _OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
-):
-    pass
-
-
-SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef = TypedDict(
-    "SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef",
+SearchFlowTemplatesRequestRequestTypeDef = TypedDict(
+    "SearchFlowTemplatesRequestRequestTypeDef",
     {
         "filters": Sequence[FlowTemplateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-_RequiredSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
-    "_RequiredSearchThingsRequestSearchThingsPaginateTypeDef",
-    {
-        "entityId": str,
-    },
-)
-_OptionalSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
-    "_OptionalSearchThingsRequestSearchThingsPaginateTypeDef",
+SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef = TypedDict(
+    "SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef",
     {
-        "namespaceVersion": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filters": Sequence[FlowTemplateFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class SearchThingsRequestSearchThingsPaginateTypeDef(
-    _RequiredSearchThingsRequestSearchThingsPaginateTypeDef,
-    _OptionalSearchThingsRequestSearchThingsPaginateTypeDef,
-):
-    pass
-
-
 SearchSystemInstancesRequestRequestTypeDef = TypedDict(
     "SearchSystemInstancesRequestRequestTypeDef",
     {
         "filters": Sequence[SystemInstanceFilterTypeDef],
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
 SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef = TypedDict(
     "SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef",
     {
         "filters": Sequence[SystemInstanceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 SearchSystemTemplatesRequestRequestTypeDef = TypedDict(
     "SearchSystemTemplatesRequestRequestTypeDef",
     {
@@ -1203,61 +1203,61 @@
     total=False,
 )
 
 SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef = TypedDict(
     "SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef",
     {
         "filters": Sequence[SystemTemplateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 SearchThingsResponseTypeDef = TypedDict(
     "SearchThingsResponseTypeDef",
     {
         "things": List[ThingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEntitiesResponseTypeDef = TypedDict(
     "GetEntitiesResponseTypeDef",
     {
         "descriptions": List[EntityDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchEntitiesResponseTypeDef = TypedDict(
     "SearchEntitiesResponseTypeDef",
     {
         "descriptions": List[EntityDescriptionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFlowTemplateResponseTypeDef = TypedDict(
     "GetFlowTemplateResponseTypeDef",
     {
         "description": FlowTemplateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSystemTemplateResponseTypeDef = TypedDict(
     "GetSystemTemplateResponseTypeDef",
     {
         "description": SystemTemplateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSystemInstanceResponseTypeDef = TypedDict(
     "GetSystemInstanceResponseTypeDef",
     {
         "description": SystemInstanceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph/type_defs.pyi` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -36,90 +36,90 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateEntityToThingRequestRequestTypeDef",
     "DefinitionDocumentTypeDef",
     "FlowTemplateSummaryTypeDef",
-    "ResponseMetadataTypeDef",
     "MetricsConfigurationTypeDef",
     "TagTypeDef",
     "SystemInstanceSummaryTypeDef",
     "SystemTemplateSummaryTypeDef",
     "DeleteFlowTemplateRequestRequestTypeDef",
+    "DeleteNamespaceResponseTypeDef",
     "DeleteSystemInstanceRequestRequestTypeDef",
     "DeleteSystemTemplateRequestRequestTypeDef",
     "DependencyRevisionTypeDef",
     "DeploySystemInstanceRequestRequestTypeDef",
     "DeprecateFlowTemplateRequestRequestTypeDef",
     "DeprecateSystemTemplateRequestRequestTypeDef",
     "DescribeNamespaceRequestRequestTypeDef",
+    "DescribeNamespaceResponseTypeDef",
     "DissociateEntityFromThingRequestRequestTypeDef",
     "EntityFilterTypeDef",
     "FlowExecutionMessageTypeDef",
     "FlowExecutionSummaryTypeDef",
     "FlowTemplateFilterTypeDef",
     "GetEntitiesRequestRequestTypeDef",
     "GetFlowTemplateRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
     "GetFlowTemplateRevisionsRequestRequestTypeDef",
+    "GetNamespaceDeletionStatusResponseTypeDef",
     "GetSystemInstanceRequestRequestTypeDef",
     "GetSystemTemplateRequestRequestTypeDef",
+    "GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
     "GetSystemTemplateRevisionsRequestRequestTypeDef",
     "GetUploadStatusRequestRequestTypeDef",
+    "GetUploadStatusResponseTypeDef",
+    "ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
     "ListFlowExecutionMessagesRequestRequestTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchFlowExecutionsRequestRequestTypeDef",
+    "SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
     "SystemInstanceFilterTypeDef",
     "SystemTemplateFilterTypeDef",
     "SearchThingsRequestRequestTypeDef",
+    "SearchThingsRequestSearchThingsPaginateTypeDef",
     "ThingTypeDef",
     "UndeploySystemInstanceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UploadEntityDefinitionsResponseTypeDef",
     "CreateFlowTemplateRequestRequestTypeDef",
     "CreateSystemTemplateRequestRequestTypeDef",
     "EntityDescriptionTypeDef",
     "UpdateFlowTemplateRequestRequestTypeDef",
     "UpdateSystemTemplateRequestRequestTypeDef",
     "UploadEntityDefinitionsRequestRequestTypeDef",
-    "FlowTemplateDescriptionTypeDef",
     "CreateFlowTemplateResponseTypeDef",
-    "DeleteNamespaceResponseTypeDef",
-    "DescribeNamespaceResponseTypeDef",
+    "FlowTemplateDescriptionTypeDef",
     "GetFlowTemplateRevisionsResponseTypeDef",
-    "GetNamespaceDeletionStatusResponseTypeDef",
-    "GetUploadStatusResponseTypeDef",
     "SearchFlowTemplatesResponseTypeDef",
     "UpdateFlowTemplateResponseTypeDef",
-    "UploadEntityDefinitionsResponseTypeDef",
     "CreateSystemInstanceRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateSystemInstanceResponseTypeDef",
     "DeploySystemInstanceResponseTypeDef",
     "SearchSystemInstancesResponseTypeDef",
     "UndeploySystemInstanceResponseTypeDef",
     "CreateSystemTemplateResponseTypeDef",
     "GetSystemTemplateRevisionsResponseTypeDef",
     "SearchSystemTemplatesResponseTypeDef",
     "SystemTemplateDescriptionTypeDef",
     "UpdateSystemTemplateResponseTypeDef",
     "SystemInstanceDescriptionTypeDef",
     "SearchEntitiesRequestRequestTypeDef",
+    "SearchEntitiesRequestSearchEntitiesPaginateTypeDef",
     "ListFlowExecutionMessagesResponseTypeDef",
     "SearchFlowExecutionsResponseTypeDef",
     "SearchFlowTemplatesRequestRequestTypeDef",
-    "GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
-    "GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
-    "ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "SearchEntitiesRequestSearchEntitiesPaginateTypeDef",
-    "SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
     "SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef",
-    "SearchThingsRequestSearchThingsPaginateTypeDef",
     "SearchSystemInstancesRequestRequestTypeDef",
     "SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef",
     "SearchSystemTemplatesRequestRequestTypeDef",
     "SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef",
     "SearchThingsResponseTypeDef",
     "GetEntitiesResponseTypeDef",
     "SearchEntitiesResponseTypeDef",
@@ -164,25 +164,14 @@
         "arn": str,
         "revisionNumber": int,
         "createdAt": datetime,
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
 MetricsConfigurationTypeDef = TypedDict(
     "MetricsConfigurationTypeDef",
     {
         "cloudMetricEnabled": bool,
         "metricRuleRoleArn": str,
     },
     total=False,
@@ -226,14 +215,23 @@
 DeleteFlowTemplateRequestRequestTypeDef = TypedDict(
     "DeleteFlowTemplateRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+DeleteNamespaceResponseTypeDef = TypedDict(
+    "DeleteNamespaceResponseTypeDef",
+    {
+        "namespaceArn": str,
+        "namespaceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSystemInstanceRequestRequestTypeDef = TypedDict(
     "DeleteSystemInstanceRequestRequestTypeDef",
     {
         "id": str,
     },
     total=False,
 )
@@ -280,14 +278,26 @@
     "DescribeNamespaceRequestRequestTypeDef",
     {
         "namespaceName": str,
     },
     total=False,
 )
 
+DescribeNamespaceResponseTypeDef = TypedDict(
+    "DescribeNamespaceResponseTypeDef",
+    {
+        "namespaceArn": str,
+        "namespaceName": str,
+        "trackingNamespaceName": str,
+        "trackingNamespaceVersion": int,
+        "namespaceVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DissociateEntityFromThingRequestRequestTypeDef = TypedDict(
     "DissociateEntityFromThingRequestRequestTypeDef",
     {
         "thingName": str,
         "entityType": EntityTypeType,
     },
 )
@@ -367,24 +377,34 @@
 )
 
 class GetFlowTemplateRequestRequestTypeDef(
     _RequiredGetFlowTemplateRequestRequestTypeDef, _OptionalGetFlowTemplateRequestRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "id": str,
+    },
+)
+_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef(
+    _RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
+    _OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetFlowTemplateRevisionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetFlowTemplateRevisionsRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalGetFlowTemplateRevisionsRequestRequestTypeDef = TypedDict(
@@ -398,14 +418,26 @@
 
 class GetFlowTemplateRevisionsRequestRequestTypeDef(
     _RequiredGetFlowTemplateRevisionsRequestRequestTypeDef,
     _OptionalGetFlowTemplateRevisionsRequestRequestTypeDef,
 ):
     pass
 
+GetNamespaceDeletionStatusResponseTypeDef = TypedDict(
+    "GetNamespaceDeletionStatusResponseTypeDef",
+    {
+        "namespaceArn": str,
+        "namespaceName": str,
+        "status": NamespaceDeletionStatusType,
+        "errorCode": Literal["VALIDATION_FAILED"],
+        "errorMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSystemInstanceRequestRequestTypeDef = TypedDict(
     "GetSystemInstanceRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -424,14 +456,34 @@
 )
 
 class GetSystemTemplateRequestRequestTypeDef(
     _RequiredGetSystemTemplateRequestRequestTypeDef, _OptionalGetSystemTemplateRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
+    {
+        "id": str,
+    },
+)
+_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef(
+    _RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
+    _OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetSystemTemplateRevisionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSystemTemplateRevisionsRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalGetSystemTemplateRevisionsRequestRequestTypeDef = TypedDict(
@@ -452,14 +504,48 @@
 GetUploadStatusRequestRequestTypeDef = TypedDict(
     "GetUploadStatusRequestRequestTypeDef",
     {
         "uploadId": str,
     },
 )
 
+GetUploadStatusResponseTypeDef = TypedDict(
+    "GetUploadStatusResponseTypeDef",
+    {
+        "uploadId": str,
+        "uploadStatus": UploadStatusType,
+        "namespaceArn": str,
+        "namespaceName": str,
+        "namespaceVersion": int,
+        "failureReason": List[str],
+        "createdDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
+    "_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
+    {
+        "flowExecutionId": str,
+    },
+)
+_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
+    "_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef(
+    _RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
+    _OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
+):
+    pass
+
 _RequiredListFlowExecutionMessagesRequestRequestTypeDef = TypedDict(
     "_RequiredListFlowExecutionMessagesRequestRequestTypeDef",
     {
         "flowExecutionId": str,
     },
 )
 _OptionalListFlowExecutionMessagesRequestRequestTypeDef = TypedDict(
@@ -473,14 +559,34 @@
 
 class ListFlowExecutionMessagesRequestRequestTypeDef(
     _RequiredListFlowExecutionMessagesRequestRequestTypeDef,
     _OptionalListFlowExecutionMessagesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -494,14 +600,35 @@
 
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
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
 _RequiredSearchFlowExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchFlowExecutionsRequestRequestTypeDef",
     {
         "systemInstanceId": str,
     },
 )
 _OptionalSearchFlowExecutionsRequestRequestTypeDef = TypedDict(
@@ -518,14 +645,37 @@
 
 class SearchFlowExecutionsRequestRequestTypeDef(
     _RequiredSearchFlowExecutionsRequestRequestTypeDef,
     _OptionalSearchFlowExecutionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+    {
+        "systemInstanceId": str,
+    },
+)
+_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+    {
+        "flowExecutionId": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef(
+    _RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
+    _OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
+):
+    pass
+
 SystemInstanceFilterTypeDef = TypedDict(
     "SystemInstanceFilterTypeDef",
     {
         "name": SystemInstanceFilterNameType,
         "value": Sequence[str],
     },
     total=False,
@@ -556,14 +706,35 @@
 )
 
 class SearchThingsRequestRequestTypeDef(
     _RequiredSearchThingsRequestRequestTypeDef, _OptionalSearchThingsRequestRequestTypeDef
 ):
     pass
 
+_RequiredSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
+    "_RequiredSearchThingsRequestSearchThingsPaginateTypeDef",
+    {
+        "entityId": str,
+    },
+)
+_OptionalSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
+    "_OptionalSearchThingsRequestSearchThingsPaginateTypeDef",
+    {
+        "namespaceVersion": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SearchThingsRequestSearchThingsPaginateTypeDef(
+    _RequiredSearchThingsRequestSearchThingsPaginateTypeDef,
+    _OptionalSearchThingsRequestSearchThingsPaginateTypeDef,
+):
+    pass
+
 ThingTypeDef = TypedDict(
     "ThingTypeDef",
     {
         "thingArn": str,
         "thingName": str,
     },
     total=False,
@@ -581,14 +752,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UploadEntityDefinitionsResponseTypeDef = TypedDict(
+    "UploadEntityDefinitionsResponseTypeDef",
+    {
+        "uploadId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFlowTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFlowTemplateRequestRequestTypeDef",
     {
         "definition": DefinitionDocumentTypeDef,
     },
 )
 _OptionalCreateFlowTemplateRequestRequestTypeDef = TypedDict(
@@ -685,110 +864,55 @@
         "document": DefinitionDocumentTypeDef,
         "syncWithPublicNamespace": bool,
         "deprecateExistingEntities": bool,
     },
     total=False,
 )
 
-FlowTemplateDescriptionTypeDef = TypedDict(
-    "FlowTemplateDescriptionTypeDef",
-    {
-        "summary": FlowTemplateSummaryTypeDef,
-        "definition": DefinitionDocumentTypeDef,
-        "validatedNamespaceVersion": int,
-    },
-    total=False,
-)
-
 CreateFlowTemplateResponseTypeDef = TypedDict(
     "CreateFlowTemplateResponseTypeDef",
     {
         "summary": FlowTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteNamespaceResponseTypeDef = TypedDict(
-    "DeleteNamespaceResponseTypeDef",
-    {
-        "namespaceArn": str,
-        "namespaceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeNamespaceResponseTypeDef = TypedDict(
-    "DescribeNamespaceResponseTypeDef",
+FlowTemplateDescriptionTypeDef = TypedDict(
+    "FlowTemplateDescriptionTypeDef",
     {
-        "namespaceArn": str,
-        "namespaceName": str,
-        "trackingNamespaceName": str,
-        "trackingNamespaceVersion": int,
-        "namespaceVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "summary": FlowTemplateSummaryTypeDef,
+        "definition": DefinitionDocumentTypeDef,
+        "validatedNamespaceVersion": int,
     },
+    total=False,
 )
 
 GetFlowTemplateRevisionsResponseTypeDef = TypedDict(
     "GetFlowTemplateRevisionsResponseTypeDef",
     {
         "summaries": List[FlowTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetNamespaceDeletionStatusResponseTypeDef = TypedDict(
-    "GetNamespaceDeletionStatusResponseTypeDef",
-    {
-        "namespaceArn": str,
-        "namespaceName": str,
-        "status": NamespaceDeletionStatusType,
-        "errorCode": Literal["VALIDATION_FAILED"],
-        "errorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUploadStatusResponseTypeDef = TypedDict(
-    "GetUploadStatusResponseTypeDef",
-    {
-        "uploadId": str,
-        "uploadStatus": UploadStatusType,
-        "namespaceArn": str,
-        "namespaceName": str,
-        "namespaceVersion": int,
-        "failureReason": List[str],
-        "createdDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchFlowTemplatesResponseTypeDef = TypedDict(
     "SearchFlowTemplatesResponseTypeDef",
     {
         "summaries": List[FlowTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFlowTemplateResponseTypeDef = TypedDict(
     "UpdateFlowTemplateResponseTypeDef",
     {
         "summary": FlowTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UploadEntityDefinitionsResponseTypeDef = TypedDict(
-    "UploadEntityDefinitionsResponseTypeDef",
-    {
-        "uploadId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSystemInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSystemInstanceRequestRequestTypeDef",
     {
         "definition": DefinitionDocumentTypeDef,
@@ -814,15 +938,15 @@
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -830,67 +954,67 @@
     },
 )
 
 CreateSystemInstanceResponseTypeDef = TypedDict(
     "CreateSystemInstanceResponseTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploySystemInstanceResponseTypeDef = TypedDict(
     "DeploySystemInstanceResponseTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
         "greengrassDeploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchSystemInstancesResponseTypeDef = TypedDict(
     "SearchSystemInstancesResponseTypeDef",
     {
         "summaries": List[SystemInstanceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UndeploySystemInstanceResponseTypeDef = TypedDict(
     "UndeploySystemInstanceResponseTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSystemTemplateResponseTypeDef = TypedDict(
     "CreateSystemTemplateResponseTypeDef",
     {
         "summary": SystemTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSystemTemplateRevisionsResponseTypeDef = TypedDict(
     "GetSystemTemplateRevisionsResponseTypeDef",
     {
         "summaries": List[SystemTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchSystemTemplatesResponseTypeDef = TypedDict(
     "SearchSystemTemplatesResponseTypeDef",
     {
         "summaries": List[SystemTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SystemTemplateDescriptionTypeDef = TypedDict(
     "SystemTemplateDescriptionTypeDef",
     {
         "summary": SystemTemplateSummaryTypeDef,
@@ -900,15 +1024,15 @@
     total=False,
 )
 
 UpdateSystemTemplateResponseTypeDef = TypedDict(
     "UpdateSystemTemplateResponseTypeDef",
     {
         "summary": SystemTemplateSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SystemInstanceDescriptionTypeDef = TypedDict(
     "SystemInstanceDescriptionTypeDef",
     {
         "summary": SystemInstanceSummaryTypeDef,
@@ -940,212 +1064,88 @@
 )
 
 class SearchEntitiesRequestRequestTypeDef(
     _RequiredSearchEntitiesRequestRequestTypeDef, _OptionalSearchEntitiesRequestRequestTypeDef
 ):
     pass
 
-ListFlowExecutionMessagesResponseTypeDef = TypedDict(
-    "ListFlowExecutionMessagesResponseTypeDef",
-    {
-        "messages": List[FlowExecutionMessageTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchFlowExecutionsResponseTypeDef = TypedDict(
-    "SearchFlowExecutionsResponseTypeDef",
-    {
-        "summaries": List[FlowExecutionSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchFlowTemplatesRequestRequestTypeDef = TypedDict(
-    "SearchFlowTemplatesRequestRequestTypeDef",
-    {
-        "filters": Sequence[FlowTemplateFilterTypeDef],
-        "nextToken": str,
-        "maxResults": int,
-    },
-    total=False,
-)
-
-_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef(
-    _RequiredGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-    _OptionalGetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef(
-    _RequiredGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-    _OptionalGetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
-    "_RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
-    {
-        "flowExecutionId": str,
-    },
-)
-_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef = TypedDict(
-    "_OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef(
-    _RequiredListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-    _OptionalListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
 _RequiredSearchEntitiesRequestSearchEntitiesPaginateTypeDef = TypedDict(
     "_RequiredSearchEntitiesRequestSearchEntitiesPaginateTypeDef",
     {
         "entityTypes": Sequence[EntityTypeType],
     },
 )
 _OptionalSearchEntitiesRequestSearchEntitiesPaginateTypeDef = TypedDict(
     "_OptionalSearchEntitiesRequestSearchEntitiesPaginateTypeDef",
     {
         "filters": Sequence[EntityFilterTypeDef],
         "namespaceVersion": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchEntitiesRequestSearchEntitiesPaginateTypeDef(
     _RequiredSearchEntitiesRequestSearchEntitiesPaginateTypeDef,
     _OptionalSearchEntitiesRequestSearchEntitiesPaginateTypeDef,
 ):
     pass
 
-_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+ListFlowExecutionMessagesResponseTypeDef = TypedDict(
+    "ListFlowExecutionMessagesResponseTypeDef",
     {
-        "systemInstanceId": str,
+        "messages": List[FlowExecutionMessageTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef",
+
+SearchFlowExecutionsResponseTypeDef = TypedDict(
+    "SearchFlowExecutionsResponseTypeDef",
     {
-        "flowExecutionId": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "summaries": List[FlowExecutionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef(
-    _RequiredSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
-    _OptionalSearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
-):
-    pass
-
-SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef = TypedDict(
-    "SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef",
+SearchFlowTemplatesRequestRequestTypeDef = TypedDict(
+    "SearchFlowTemplatesRequestRequestTypeDef",
     {
         "filters": Sequence[FlowTemplateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-_RequiredSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
-    "_RequiredSearchThingsRequestSearchThingsPaginateTypeDef",
-    {
-        "entityId": str,
-    },
-)
-_OptionalSearchThingsRequestSearchThingsPaginateTypeDef = TypedDict(
-    "_OptionalSearchThingsRequestSearchThingsPaginateTypeDef",
+SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef = TypedDict(
+    "SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef",
     {
-        "namespaceVersion": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filters": Sequence[FlowTemplateFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class SearchThingsRequestSearchThingsPaginateTypeDef(
-    _RequiredSearchThingsRequestSearchThingsPaginateTypeDef,
-    _OptionalSearchThingsRequestSearchThingsPaginateTypeDef,
-):
-    pass
-
 SearchSystemInstancesRequestRequestTypeDef = TypedDict(
     "SearchSystemInstancesRequestRequestTypeDef",
     {
         "filters": Sequence[SystemInstanceFilterTypeDef],
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
 SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef = TypedDict(
     "SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef",
     {
         "filters": Sequence[SystemInstanceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 SearchSystemTemplatesRequestRequestTypeDef = TypedDict(
     "SearchSystemTemplatesRequestRequestTypeDef",
     {
@@ -1156,61 +1156,61 @@
     total=False,
 )
 
 SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef = TypedDict(
     "SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef",
     {
         "filters": Sequence[SystemTemplateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 SearchThingsResponseTypeDef = TypedDict(
     "SearchThingsResponseTypeDef",
     {
         "things": List[ThingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEntitiesResponseTypeDef = TypedDict(
     "GetEntitiesResponseTypeDef",
     {
         "descriptions": List[EntityDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchEntitiesResponseTypeDef = TypedDict(
     "SearchEntitiesResponseTypeDef",
     {
         "descriptions": List[EntityDescriptionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFlowTemplateResponseTypeDef = TypedDict(
     "GetFlowTemplateResponseTypeDef",
     {
         "description": FlowTemplateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSystemTemplateResponseTypeDef = TypedDict(
     "GetSystemTemplateResponseTypeDef",
     {
         "description": SystemTemplateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSystemInstanceResponseTypeDef = TypedDict(
     "GetSystemInstanceResponseTypeDef",
     {
         "description": SystemInstanceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/PKG-INFO` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotthingsgraph
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTThingsGraph 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTThingsGraph 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotthingsgraph"></a>
 
 # types-aiobotocore-iotthingsgraph
 
 [![PyPI - types-aiobotocore-iotthingsgraph](https://img.shields.io/pypi/v/types-aiobotocore-iotthingsgraph.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotthingsgraph)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotthingsgraph.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotthingsgraph)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotthingsgraph?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotthingsgraph)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTThingsGraph 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
+[aiobotocore.IoTThingsGraph 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotthingsgraph.html#IoTThingsGraph)
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
 [types-aiobotocore-iotthingsgraph docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotthingsgraph/).
 
 See how it helps to find and fix potential bugs:
 
@@ -375,90 +375,90 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotthingsgraph.type_defs import (
     AssociateEntityToThingRequestRequestTypeDef,
     DefinitionDocumentTypeDef,
     FlowTemplateSummaryTypeDef,
-    ResponseMetadataTypeDef,
     MetricsConfigurationTypeDef,
     TagTypeDef,
     SystemInstanceSummaryTypeDef,
     SystemTemplateSummaryTypeDef,
     DeleteFlowTemplateRequestRequestTypeDef,
+    DeleteNamespaceResponseTypeDef,
     DeleteSystemInstanceRequestRequestTypeDef,
     DeleteSystemTemplateRequestRequestTypeDef,
     DependencyRevisionTypeDef,
     DeploySystemInstanceRequestRequestTypeDef,
     DeprecateFlowTemplateRequestRequestTypeDef,
     DeprecateSystemTemplateRequestRequestTypeDef,
     DescribeNamespaceRequestRequestTypeDef,
+    DescribeNamespaceResponseTypeDef,
     DissociateEntityFromThingRequestRequestTypeDef,
     EntityFilterTypeDef,
     FlowExecutionMessageTypeDef,
     FlowExecutionSummaryTypeDef,
     FlowTemplateFilterTypeDef,
     GetEntitiesRequestRequestTypeDef,
     GetFlowTemplateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
     GetFlowTemplateRevisionsRequestRequestTypeDef,
+    GetNamespaceDeletionStatusResponseTypeDef,
     GetSystemInstanceRequestRequestTypeDef,
     GetSystemTemplateRequestRequestTypeDef,
+    GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
     GetSystemTemplateRevisionsRequestRequestTypeDef,
     GetUploadStatusRequestRequestTypeDef,
+    GetUploadStatusResponseTypeDef,
+    ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
     ListFlowExecutionMessagesRequestRequestTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SearchFlowExecutionsRequestRequestTypeDef,
+    SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
     SystemInstanceFilterTypeDef,
     SystemTemplateFilterTypeDef,
     SearchThingsRequestRequestTypeDef,
+    SearchThingsRequestSearchThingsPaginateTypeDef,
     ThingTypeDef,
     UndeploySystemInstanceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UploadEntityDefinitionsResponseTypeDef,
     CreateFlowTemplateRequestRequestTypeDef,
     CreateSystemTemplateRequestRequestTypeDef,
     EntityDescriptionTypeDef,
     UpdateFlowTemplateRequestRequestTypeDef,
     UpdateSystemTemplateRequestRequestTypeDef,
     UploadEntityDefinitionsRequestRequestTypeDef,
-    FlowTemplateDescriptionTypeDef,
     CreateFlowTemplateResponseTypeDef,
-    DeleteNamespaceResponseTypeDef,
-    DescribeNamespaceResponseTypeDef,
+    FlowTemplateDescriptionTypeDef,
     GetFlowTemplateRevisionsResponseTypeDef,
-    GetNamespaceDeletionStatusResponseTypeDef,
-    GetUploadStatusResponseTypeDef,
     SearchFlowTemplatesResponseTypeDef,
     UpdateFlowTemplateResponseTypeDef,
-    UploadEntityDefinitionsResponseTypeDef,
     CreateSystemInstanceRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSystemInstanceResponseTypeDef,
     DeploySystemInstanceResponseTypeDef,
     SearchSystemInstancesResponseTypeDef,
     UndeploySystemInstanceResponseTypeDef,
     CreateSystemTemplateResponseTypeDef,
     GetSystemTemplateRevisionsResponseTypeDef,
     SearchSystemTemplatesResponseTypeDef,
     SystemTemplateDescriptionTypeDef,
     UpdateSystemTemplateResponseTypeDef,
     SystemInstanceDescriptionTypeDef,
     SearchEntitiesRequestRequestTypeDef,
+    SearchEntitiesRequestSearchEntitiesPaginateTypeDef,
     ListFlowExecutionMessagesResponseTypeDef,
     SearchFlowExecutionsResponseTypeDef,
     SearchFlowTemplatesRequestRequestTypeDef,
-    GetFlowTemplateRevisionsRequestGetFlowTemplateRevisionsPaginateTypeDef,
-    GetSystemTemplateRevisionsRequestGetSystemTemplateRevisionsPaginateTypeDef,
-    ListFlowExecutionMessagesRequestListFlowExecutionMessagesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    SearchEntitiesRequestSearchEntitiesPaginateTypeDef,
-    SearchFlowExecutionsRequestSearchFlowExecutionsPaginateTypeDef,
     SearchFlowTemplatesRequestSearchFlowTemplatesPaginateTypeDef,
-    SearchThingsRequestSearchThingsPaginateTypeDef,
     SearchSystemInstancesRequestRequestTypeDef,
     SearchSystemInstancesRequestSearchSystemInstancesPaginateTypeDef,
     SearchSystemTemplatesRequestRequestTypeDef,
     SearchSystemTemplatesRequestSearchSystemTemplatesPaginateTypeDef,
     SearchThingsResponseTypeDef,
     GetEntitiesResponseTypeDef,
     SearchEntitiesResponseTypeDef,
@@ -475,43 +475,43 @@
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

### Comparing `types-aiobotocore-iotthingsgraph-2.5.0.post1/types_aiobotocore_iotthingsgraph.egg-info/SOURCES.txt` & `types-aiobotocore-iotthingsgraph-2.5.1/types_aiobotocore_iotthingsgraph.egg-info/SOURCES.txt`

 * *Files identical despite different names*

