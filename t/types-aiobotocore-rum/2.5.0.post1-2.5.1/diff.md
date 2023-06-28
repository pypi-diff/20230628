# Comparing `tmp/types-aiobotocore-rum-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-rum-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-rum-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-rum-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-rum-2.5.0.post1.tar` & `types-aiobotocore-rum-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.643581 types-aiobotocore-rum-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15502 2023-03-11 12:27:15.639582 types-aiobotocore-rum-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13937 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:15.643581 types-aiobotocore-rum-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2082 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.631581 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/
--rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1454 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      936 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18040 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18010 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8583 2023-03-11 12:22:50.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8581 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6014 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6007 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20074 2023-03-11 12:22:50.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20039 2023-03-11 12:22:50.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:49.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:15.639582 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15502 2023-03-11 12:27:15.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:15.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:15.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:15.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:15.000000 types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.706205 types-aiobotocore-rum-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15490 2023-06-28 01:44:05.698204 types-aiobotocore-rum-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13931 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.706205 types-aiobotocore-rum-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.694204 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/
+-rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1454 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      924 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18059 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18029 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8792 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8790 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5902 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5896 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    20152 2023-06-28 01:39:37.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20117 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:36.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.698204 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15490 2023-06-28 01:44:05.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:44:05.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:05.000000 types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/LICENSE` & `types-aiobotocore-rum-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-rum-2.5.0.post1/PKG-INFO` & `types-aiobotocore-rum-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rum
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudWatchRUM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudWatchRUM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rum"></a>
 
 # types-aiobotocore-rum
 
 [![PyPI - types-aiobotocore-rum](https://img.shields.io/pypi/v/types-aiobotocore-rum.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rum)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rum.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rum)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rum?color=blue)](https://pypistats.org/packages/types-aiobotocore-rum)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatchRUM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
+[aiobotocore.CloudWatchRUM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
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
 [types-aiobotocore-rum docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/).
 
 See how it helps to find and fix potential bugs:
 
@@ -341,48 +341,48 @@
 from types_aiobotocore_rum.type_defs import (
     AppMonitorConfigurationTypeDef,
     AppMonitorDetailsTypeDef,
     AppMonitorSummaryTypeDef,
     CustomEventsTypeDef,
     MetricDefinitionRequestTypeDef,
     MetricDefinitionTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteRumMetricDefinitionsErrorTypeDef,
     BatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
     BatchGetRumMetricDefinitionsRequestRequestTypeDef,
+    CreateAppMonitorResponseTypeDef,
     CwLogTypeDef,
     DeleteAppMonitorRequestRequestTypeDef,
     DeleteRumMetricsDestinationRequestRequestTypeDef,
     QueryFilterTypeDef,
     TimeRangeTypeDef,
+    GetAppMonitorDataResponseTypeDef,
     GetAppMonitorRequestRequestTypeDef,
+    ListAppMonitorsRequestListAppMonitorsPaginateTypeDef,
     ListAppMonitorsRequestRequestTypeDef,
+    ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
     ListRumMetricsDestinationsRequestRequestTypeDef,
     MetricDestinationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     RumEventTypeDef,
     UserDetailsTypeDef,
     PutRumMetricsDestinationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListAppMonitorsResponseTypeDef,
     CreateAppMonitorRequestRequestTypeDef,
     UpdateAppMonitorRequestRequestTypeDef,
     BatchCreateRumMetricDefinitionsErrorTypeDef,
     BatchCreateRumMetricDefinitionsRequestRequestTypeDef,
     UpdateRumMetricDefinitionRequestRequestTypeDef,
     BatchGetRumMetricDefinitionsResponseTypeDef,
-    CreateAppMonitorResponseTypeDef,
-    GetAppMonitorDataResponseTypeDef,
-    ListAppMonitorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchDeleteRumMetricDefinitionsResponseTypeDef,
-    BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-    ListAppMonitorsRequestListAppMonitorsPaginateTypeDef,
-    ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
     DataStorageTypeDef,
     GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef,
     GetAppMonitorDataRequestRequestTypeDef,
     ListRumMetricsDestinationsResponseTypeDef,
     PutRumEventsRequestRequestTypeDef,
     BatchCreateRumMetricDefinitionsResponseTypeDef,
     AppMonitorTypeDef,
@@ -397,43 +397,43 @@
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/README.md` & `types-aiobotocore-rum-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-rum"></a>
 
 # types-aiobotocore-rum
 
 [![PyPI - types-aiobotocore-rum](https://img.shields.io/pypi/v/types-aiobotocore-rum.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rum)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rum.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rum)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rum?color=blue)](https://pypistats.org/packages/types-aiobotocore-rum)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatchRUM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
+[aiobotocore.CloudWatchRUM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
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
 [types-aiobotocore-rum docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/).
 
 See how it helps to find and fix potential bugs:
 
@@ -308,48 +308,48 @@
 from types_aiobotocore_rum.type_defs import (
     AppMonitorConfigurationTypeDef,
     AppMonitorDetailsTypeDef,
     AppMonitorSummaryTypeDef,
     CustomEventsTypeDef,
     MetricDefinitionRequestTypeDef,
     MetricDefinitionTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteRumMetricDefinitionsErrorTypeDef,
     BatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
     BatchGetRumMetricDefinitionsRequestRequestTypeDef,
+    CreateAppMonitorResponseTypeDef,
     CwLogTypeDef,
     DeleteAppMonitorRequestRequestTypeDef,
     DeleteRumMetricsDestinationRequestRequestTypeDef,
     QueryFilterTypeDef,
     TimeRangeTypeDef,
+    GetAppMonitorDataResponseTypeDef,
     GetAppMonitorRequestRequestTypeDef,
+    ListAppMonitorsRequestListAppMonitorsPaginateTypeDef,
     ListAppMonitorsRequestRequestTypeDef,
+    ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
     ListRumMetricsDestinationsRequestRequestTypeDef,
     MetricDestinationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     RumEventTypeDef,
     UserDetailsTypeDef,
     PutRumMetricsDestinationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListAppMonitorsResponseTypeDef,
     CreateAppMonitorRequestRequestTypeDef,
     UpdateAppMonitorRequestRequestTypeDef,
     BatchCreateRumMetricDefinitionsErrorTypeDef,
     BatchCreateRumMetricDefinitionsRequestRequestTypeDef,
     UpdateRumMetricDefinitionRequestRequestTypeDef,
     BatchGetRumMetricDefinitionsResponseTypeDef,
-    CreateAppMonitorResponseTypeDef,
-    GetAppMonitorDataResponseTypeDef,
-    ListAppMonitorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchDeleteRumMetricDefinitionsResponseTypeDef,
-    BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-    ListAppMonitorsRequestListAppMonitorsPaginateTypeDef,
-    ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
     DataStorageTypeDef,
     GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef,
     GetAppMonitorDataRequestRequestTypeDef,
     ListRumMetricsDestinationsResponseTypeDef,
     PutRumEventsRequestRequestTypeDef,
     BatchCreateRumMetricDefinitionsResponseTypeDef,
     AppMonitorTypeDef,
@@ -364,43 +364,43 @@
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/setup.py` & `types-aiobotocore-rum-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-rum.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-rum",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_rum"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudWatchRUM 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudWatchRUM 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/",
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/__init__.py` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/__init__.pyi` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/__main__.py` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudWatchRUM 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudWatchRUM 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM\nOther"
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/client.py` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -97,16 +97,16 @@
         *,
         AppMonitorName: str,
         Destination: MetricDestinationType,
         MetricDefinitions: Sequence[MetricDefinitionRequestTypeDef],
         DestinationArn: str = ...
     ) -> BatchCreateRumMetricDefinitionsResponseTypeDef:
         """
-        Specifies the extended metrics that you want a CloudWatch RUM app monitor to
-        send to a destination.
+        Specifies the extended metrics and custom metrics that you want a CloudWatch RUM
+        app monitor to send to a destination.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.batch_create_rum_metric_definitions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/client/#batch_create_rum_metric_definitions)
         """
 
     async def batch_delete_rum_metric_definitions(
         self,
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/client.pyi` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -92,16 +92,16 @@
         *,
         AppMonitorName: str,
         Destination: MetricDestinationType,
         MetricDefinitions: Sequence[MetricDefinitionRequestTypeDef],
         DestinationArn: str = ...
     ) -> BatchCreateRumMetricDefinitionsResponseTypeDef:
         """
-        Specifies the extended metrics that you want a CloudWatch RUM app monitor to
-        send to a destination.
+        Specifies the extended metrics and custom metrics that you want a CloudWatch RUM
+        app monitor to send to a destination.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Client.batch_create_rum_metric_definitions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/client/#batch_create_rum_metric_definitions)
         """
     async def batch_delete_rum_metric_definitions(
         self,
         *,
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/literals.py` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -103,14 +103,15 @@
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
@@ -189,14 +190,15 @@
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
@@ -207,14 +209,15 @@
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
@@ -250,14 +253,15 @@
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
@@ -276,16 +280,19 @@
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
@@ -369,15 +376,17 @@
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/literals.pyi` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -101,14 +101,15 @@
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
@@ -187,14 +188,15 @@
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
@@ -205,14 +207,15 @@
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
@@ -248,14 +251,15 @@
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
@@ -274,16 +278,19 @@
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
@@ -367,15 +374,17 @@
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/paginator.py` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,16 +22,15 @@
 
         batch_get_rum_metric_definitions_paginator: BatchGetRumMetricDefinitionsPaginator = client.get_paginator("batch_get_rum_metric_definitions")
         get_app_monitor_data_paginator: GetAppMonitorDataPaginator = client.get_paginator("get_app_monitor_data")
         list_app_monitors_paginator: ListAppMonitorsPaginator = client.get_paginator("list_app_monitors")
         list_rum_metrics_destinations_paginator: ListRumMetricsDestinationsPaginator = client.get_paginator("list_rum_metrics_destinations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import MetricDestinationType
 from .type_defs import (
     BatchGetRumMetricDefinitionsResponseTypeDef,
@@ -39,20 +38,14 @@
     ListAppMonitorsResponseTypeDef,
     ListRumMetricsDestinationsResponseTypeDef,
     PaginatorConfigTypeDef,
     QueryFilterTypeDef,
     TimeRangeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "BatchGetRumMetricDefinitionsPaginator",
     "GetAppMonitorDataPaginator",
     "ListAppMonitorsPaginator",
     "ListRumMetricsDestinationsPaginator",
 )
 
@@ -75,15 +68,15 @@
 
     def paginate(
         self,
         *,
         AppMonitorName: str,
         Destination: MetricDestinationType,
         DestinationArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[BatchGetRumMetricDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.BatchGetRumMetricDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#batchgetrummetricdefinitionspaginator)
         """
 
 
@@ -95,43 +88,43 @@
 
     def paginate(
         self,
         *,
         Name: str,
         TimeRange: TimeRangeTypeDef,
         Filters: Sequence[QueryFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAppMonitorDataResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.GetAppMonitorData.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#getappmonitordatapaginator)
         """
 
 
 class ListAppMonitorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListAppMonitors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listappmonitorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppMonitorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListAppMonitors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listappmonitorspaginator)
         """
 
 
 class ListRumMetricsDestinationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListRumMetricsDestinations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listrummetricsdestinationspaginator)
     """
 
     def paginate(
-        self, *, AppMonitorName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AppMonitorName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRumMetricsDestinationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListRumMetricsDestinations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listrummetricsdestinationspaginator)
         """
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/paginator.pyi` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -22,16 +22,15 @@
 
         batch_get_rum_metric_definitions_paginator: BatchGetRumMetricDefinitionsPaginator = client.get_paginator("batch_get_rum_metric_definitions")
         get_app_monitor_data_paginator: GetAppMonitorDataPaginator = client.get_paginator("get_app_monitor_data")
         list_app_monitors_paginator: ListAppMonitorsPaginator = client.get_paginator("list_app_monitors")
         list_rum_metrics_destinations_paginator: ListRumMetricsDestinationsPaginator = client.get_paginator("list_rum_metrics_destinations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import MetricDestinationType
 from .type_defs import (
     BatchGetRumMetricDefinitionsResponseTypeDef,
@@ -39,19 +38,14 @@
     ListAppMonitorsResponseTypeDef,
     ListRumMetricsDestinationsResponseTypeDef,
     PaginatorConfigTypeDef,
     QueryFilterTypeDef,
     TimeRangeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "BatchGetRumMetricDefinitionsPaginator",
     "GetAppMonitorDataPaginator",
     "ListAppMonitorsPaginator",
     "ListRumMetricsDestinationsPaginator",
 )
 
@@ -71,15 +65,15 @@
 
     def paginate(
         self,
         *,
         AppMonitorName: str,
         Destination: MetricDestinationType,
         DestinationArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[BatchGetRumMetricDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.BatchGetRumMetricDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#batchgetrummetricdefinitionspaginator)
         """
 
 class GetAppMonitorDataPaginator(AioPaginator):
@@ -90,41 +84,41 @@
 
     def paginate(
         self,
         *,
         Name: str,
         TimeRange: TimeRangeTypeDef,
         Filters: Sequence[QueryFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAppMonitorDataResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.GetAppMonitorData.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#getappmonitordatapaginator)
         """
 
 class ListAppMonitorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListAppMonitors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listappmonitorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppMonitorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListAppMonitors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listappmonitorspaginator)
         """
 
 class ListRumMetricsDestinationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListRumMetricsDestinations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listrummetricsdestinationspaginator)
     """
 
     def paginate(
-        self, *, AppMonitorName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AppMonitorName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRumMetricsDestinationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM.Paginator.ListRumMetricsDestinations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/paginators/#listrummetricsdestinationspaginator)
         """
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/type_defs.py` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,48 +26,48 @@
 __all__ = (
     "AppMonitorConfigurationTypeDef",
     "AppMonitorDetailsTypeDef",
     "AppMonitorSummaryTypeDef",
     "CustomEventsTypeDef",
     "MetricDefinitionRequestTypeDef",
     "MetricDefinitionTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteRumMetricDefinitionsErrorTypeDef",
     "BatchDeleteRumMetricDefinitionsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
     "BatchGetRumMetricDefinitionsRequestRequestTypeDef",
+    "CreateAppMonitorResponseTypeDef",
     "CwLogTypeDef",
     "DeleteAppMonitorRequestRequestTypeDef",
     "DeleteRumMetricsDestinationRequestRequestTypeDef",
     "QueryFilterTypeDef",
     "TimeRangeTypeDef",
+    "GetAppMonitorDataResponseTypeDef",
     "GetAppMonitorRequestRequestTypeDef",
+    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
     "ListAppMonitorsRequestRequestTypeDef",
+    "ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
     "ListRumMetricsDestinationsRequestRequestTypeDef",
     "MetricDestinationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "RumEventTypeDef",
     "UserDetailsTypeDef",
     "PutRumMetricsDestinationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "ListAppMonitorsResponseTypeDef",
     "CreateAppMonitorRequestRequestTypeDef",
     "UpdateAppMonitorRequestRequestTypeDef",
     "BatchCreateRumMetricDefinitionsErrorTypeDef",
     "BatchCreateRumMetricDefinitionsRequestRequestTypeDef",
     "UpdateRumMetricDefinitionRequestRequestTypeDef",
     "BatchGetRumMetricDefinitionsResponseTypeDef",
-    "CreateAppMonitorResponseTypeDef",
-    "GetAppMonitorDataResponseTypeDef",
-    "ListAppMonitorsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "BatchDeleteRumMetricDefinitionsResponseTypeDef",
-    "BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
-    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
-    "ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
     "DataStorageTypeDef",
     "GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef",
     "GetAppMonitorDataRequestRequestTypeDef",
     "ListRumMetricsDestinationsResponseTypeDef",
     "PutRumEventsRequestRequestTypeDef",
     "BatchCreateRumMetricDefinitionsResponseTypeDef",
     "AppMonitorTypeDef",
@@ -127,14 +127,15 @@
     },
 )
 _OptionalMetricDefinitionRequestTypeDef = TypedDict(
     "_OptionalMetricDefinitionRequestTypeDef",
     {
         "DimensionKeys": Mapping[str, str],
         "EventPattern": str,
+        "Namespace": str,
         "UnitLabel": str,
         "ValueKey": str,
     },
     total=False,
 )
 
 
@@ -152,36 +153,26 @@
     },
 )
 _OptionalMetricDefinitionTypeDef = TypedDict(
     "_OptionalMetricDefinitionTypeDef",
     {
         "DimensionKeys": Dict[str, str],
         "EventPattern": str,
+        "Namespace": str,
         "UnitLabel": str,
         "ValueKey": str,
     },
     total=False,
 )
 
 
 class MetricDefinitionTypeDef(_RequiredMetricDefinitionTypeDef, _OptionalMetricDefinitionTypeDef):
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
 BatchDeleteRumMetricDefinitionsErrorTypeDef = TypedDict(
     "BatchDeleteRumMetricDefinitionsErrorTypeDef",
     {
         "ErrorCode": str,
         "ErrorMessage": str,
         "MetricDefinitionId": str,
     },
@@ -207,24 +198,38 @@
 class BatchDeleteRumMetricDefinitionsRequestRequestTypeDef(
     _RequiredBatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
     _OptionalBatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
+    "_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AppMonitorName": str,
+        "Destination": MetricDestinationType,
+    },
+)
+_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
+    "_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
+    {
+        "DestinationArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef(
+    _RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
+    _OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredBatchGetRumMetricDefinitionsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetRumMetricDefinitionsRequestRequestTypeDef",
     {
         "AppMonitorName": str,
         "Destination": MetricDestinationType,
     },
 )
@@ -242,14 +247,22 @@
 class BatchGetRumMetricDefinitionsRequestRequestTypeDef(
     _RequiredBatchGetRumMetricDefinitionsRequestRequestTypeDef,
     _OptionalBatchGetRumMetricDefinitionsRequestRequestTypeDef,
 ):
     pass
 
 
+CreateAppMonitorResponseTypeDef = TypedDict(
+    "CreateAppMonitorResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CwLogTypeDef = TypedDict(
     "CwLogTypeDef",
     {
         "CwLogEnabled": bool,
         "CwLogGroup": str,
     },
     total=False,
@@ -309,30 +322,69 @@
 )
 
 
 class TimeRangeTypeDef(_RequiredTimeRangeTypeDef, _OptionalTimeRangeTypeDef):
     pass
 
 
+GetAppMonitorDataResponseTypeDef = TypedDict(
+    "GetAppMonitorDataResponseTypeDef",
+    {
+        "Events": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAppMonitorRequestRequestTypeDef = TypedDict(
     "GetAppMonitorRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+ListAppMonitorsRequestListAppMonitorsPaginateTypeDef = TypedDict(
+    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAppMonitorsRequestRequestTypeDef = TypedDict(
     "ListAppMonitorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
+    "_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
+    {
+        "AppMonitorName": str,
+    },
+)
+_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
+    "_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef(
+    _RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
+    _OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRumMetricsDestinationsRequestRequestTypeDef = TypedDict(
     "_RequiredListRumMetricsDestinationsRequestRequestTypeDef",
     {
         "AppMonitorName": str,
     },
 )
 _OptionalListRumMetricsDestinationsRequestRequestTypeDef = TypedDict(
@@ -365,14 +417,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "ResourceArn": str,
+        "Tags": Dict[str, str],
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
 _RequiredRumEventTypeDef = TypedDict(
     "_RequiredRumEventTypeDef",
     {
         "details": str,
         "id": str,
         "timestamp": Union[datetime, str],
         "type": str,
@@ -420,14 +491,25 @@
 class PutRumMetricsDestinationRequestRequestTypeDef(
     _RequiredPutRumMetricsDestinationRequestRequestTypeDef,
     _OptionalPutRumMetricsDestinationRequestRequestTypeDef,
 ):
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
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -436,14 +518,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+ListAppMonitorsResponseTypeDef = TypedDict(
+    "ListAppMonitorsResponseTypeDef",
+    {
+        "AppMonitorSummaries": List[AppMonitorSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateAppMonitorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppMonitorRequestRequestTypeDef",
     {
         "Domain": str,
         "Name": str,
     },
 )
@@ -548,115 +639,26 @@
 
 
 BatchGetRumMetricDefinitionsResponseTypeDef = TypedDict(
     "BatchGetRumMetricDefinitionsResponseTypeDef",
     {
         "MetricDefinitions": List[MetricDefinitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppMonitorResponseTypeDef = TypedDict(
-    "CreateAppMonitorResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAppMonitorDataResponseTypeDef = TypedDict(
-    "GetAppMonitorDataResponseTypeDef",
-    {
-        "Events": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAppMonitorsResponseTypeDef = TypedDict(
-    "ListAppMonitorsResponseTypeDef",
-    {
-        "AppMonitorSummaries": List[AppMonitorSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteRumMetricDefinitionsResponseTypeDef = TypedDict(
     "BatchDeleteRumMetricDefinitionsResponseTypeDef",
     {
         "Errors": List[BatchDeleteRumMetricDefinitionsErrorTypeDef],
         "MetricDefinitionIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
-    "_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
-    {
-        "AppMonitorName": str,
-        "Destination": MetricDestinationType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
-    "_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
-    {
-        "DestinationArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef(
-    _RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-    _OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-):
-    pass
-
-
-ListAppMonitorsRequestListAppMonitorsPaginateTypeDef = TypedDict(
-    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
-    "_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
-    {
-        "AppMonitorName": str,
-    },
-)
-_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
-    "_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef(
-    _RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
-    _OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
-):
-    pass
-
 
 DataStorageTypeDef = TypedDict(
     "DataStorageTypeDef",
     {
         "CwLog": CwLogTypeDef,
     },
     total=False,
@@ -669,15 +671,15 @@
         "TimeRange": TimeRangeTypeDef,
     },
 )
 _OptionalGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef = TypedDict(
     "_OptionalGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef",
     {
         "Filters": Sequence[QueryFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef(
     _RequiredGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef,
@@ -711,15 +713,15 @@
 
 
 ListRumMetricsDestinationsResponseTypeDef = TypedDict(
     "ListRumMetricsDestinationsResponseTypeDef",
     {
         "Destinations": List[MetricDestinationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRumEventsRequestRequestTypeDef = TypedDict(
     "PutRumEventsRequestRequestTypeDef",
     {
         "AppMonitorDetails": AppMonitorDetailsTypeDef,
@@ -731,15 +733,15 @@
 )
 
 BatchCreateRumMetricDefinitionsResponseTypeDef = TypedDict(
     "BatchCreateRumMetricDefinitionsResponseTypeDef",
     {
         "Errors": List[BatchCreateRumMetricDefinitionsErrorTypeDef],
         "MetricDefinitions": List[MetricDefinitionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AppMonitorTypeDef = TypedDict(
     "AppMonitorTypeDef",
     {
         "AppMonitorConfiguration": AppMonitorConfigurationTypeDef,
@@ -756,10 +758,10 @@
     total=False,
 )
 
 GetAppMonitorResponseTypeDef = TypedDict(
     "GetAppMonitorResponseTypeDef",
     {
         "AppMonitor": AppMonitorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum/type_defs.pyi` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -25,48 +25,48 @@
 __all__ = (
     "AppMonitorConfigurationTypeDef",
     "AppMonitorDetailsTypeDef",
     "AppMonitorSummaryTypeDef",
     "CustomEventsTypeDef",
     "MetricDefinitionRequestTypeDef",
     "MetricDefinitionTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteRumMetricDefinitionsErrorTypeDef",
     "BatchDeleteRumMetricDefinitionsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
     "BatchGetRumMetricDefinitionsRequestRequestTypeDef",
+    "CreateAppMonitorResponseTypeDef",
     "CwLogTypeDef",
     "DeleteAppMonitorRequestRequestTypeDef",
     "DeleteRumMetricsDestinationRequestRequestTypeDef",
     "QueryFilterTypeDef",
     "TimeRangeTypeDef",
+    "GetAppMonitorDataResponseTypeDef",
     "GetAppMonitorRequestRequestTypeDef",
+    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
     "ListAppMonitorsRequestRequestTypeDef",
+    "ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
     "ListRumMetricsDestinationsRequestRequestTypeDef",
     "MetricDestinationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "RumEventTypeDef",
     "UserDetailsTypeDef",
     "PutRumMetricsDestinationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "ListAppMonitorsResponseTypeDef",
     "CreateAppMonitorRequestRequestTypeDef",
     "UpdateAppMonitorRequestRequestTypeDef",
     "BatchCreateRumMetricDefinitionsErrorTypeDef",
     "BatchCreateRumMetricDefinitionsRequestRequestTypeDef",
     "UpdateRumMetricDefinitionRequestRequestTypeDef",
     "BatchGetRumMetricDefinitionsResponseTypeDef",
-    "CreateAppMonitorResponseTypeDef",
-    "GetAppMonitorDataResponseTypeDef",
-    "ListAppMonitorsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "BatchDeleteRumMetricDefinitionsResponseTypeDef",
-    "BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
-    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
-    "ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
     "DataStorageTypeDef",
     "GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef",
     "GetAppMonitorDataRequestRequestTypeDef",
     "ListRumMetricsDestinationsResponseTypeDef",
     "PutRumEventsRequestRequestTypeDef",
     "BatchCreateRumMetricDefinitionsResponseTypeDef",
     "AppMonitorTypeDef",
@@ -126,14 +126,15 @@
     },
 )
 _OptionalMetricDefinitionRequestTypeDef = TypedDict(
     "_OptionalMetricDefinitionRequestTypeDef",
     {
         "DimensionKeys": Mapping[str, str],
         "EventPattern": str,
+        "Namespace": str,
         "UnitLabel": str,
         "ValueKey": str,
     },
     total=False,
 )
 
 class MetricDefinitionRequestTypeDef(
@@ -149,34 +150,24 @@
     },
 )
 _OptionalMetricDefinitionTypeDef = TypedDict(
     "_OptionalMetricDefinitionTypeDef",
     {
         "DimensionKeys": Dict[str, str],
         "EventPattern": str,
+        "Namespace": str,
         "UnitLabel": str,
         "ValueKey": str,
     },
     total=False,
 )
 
 class MetricDefinitionTypeDef(_RequiredMetricDefinitionTypeDef, _OptionalMetricDefinitionTypeDef):
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
 BatchDeleteRumMetricDefinitionsErrorTypeDef = TypedDict(
     "BatchDeleteRumMetricDefinitionsErrorTypeDef",
     {
         "ErrorCode": str,
         "ErrorMessage": str,
         "MetricDefinitionId": str,
     },
@@ -200,24 +191,36 @@
 
 class BatchDeleteRumMetricDefinitionsRequestRequestTypeDef(
     _RequiredBatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
     _OptionalBatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
+    "_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AppMonitorName": str,
+        "Destination": MetricDestinationType,
+    },
+)
+_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
+    "_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
+    {
+        "DestinationArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef(
+    _RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
+    _OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
+):
+    pass
+
 _RequiredBatchGetRumMetricDefinitionsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetRumMetricDefinitionsRequestRequestTypeDef",
     {
         "AppMonitorName": str,
         "Destination": MetricDestinationType,
     },
 )
@@ -233,14 +236,22 @@
 
 class BatchGetRumMetricDefinitionsRequestRequestTypeDef(
     _RequiredBatchGetRumMetricDefinitionsRequestRequestTypeDef,
     _OptionalBatchGetRumMetricDefinitionsRequestRequestTypeDef,
 ):
     pass
 
+CreateAppMonitorResponseTypeDef = TypedDict(
+    "CreateAppMonitorResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CwLogTypeDef = TypedDict(
     "CwLogTypeDef",
     {
         "CwLogEnabled": bool,
         "CwLogGroup": str,
     },
     total=False,
@@ -296,30 +307,67 @@
     },
     total=False,
 )
 
 class TimeRangeTypeDef(_RequiredTimeRangeTypeDef, _OptionalTimeRangeTypeDef):
     pass
 
+GetAppMonitorDataResponseTypeDef = TypedDict(
+    "GetAppMonitorDataResponseTypeDef",
+    {
+        "Events": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAppMonitorRequestRequestTypeDef = TypedDict(
     "GetAppMonitorRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+ListAppMonitorsRequestListAppMonitorsPaginateTypeDef = TypedDict(
+    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAppMonitorsRequestRequestTypeDef = TypedDict(
     "ListAppMonitorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
+    "_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
+    {
+        "AppMonitorName": str,
+    },
+)
+_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
+    "_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef(
+    _RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
+    _OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRumMetricsDestinationsRequestRequestTypeDef = TypedDict(
     "_RequiredListRumMetricsDestinationsRequestRequestTypeDef",
     {
         "AppMonitorName": str,
     },
 )
 _OptionalListRumMetricsDestinationsRequestRequestTypeDef = TypedDict(
@@ -350,14 +398,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "ResourceArn": str,
+        "Tags": Dict[str, str],
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
 _RequiredRumEventTypeDef = TypedDict(
     "_RequiredRumEventTypeDef",
     {
         "details": str,
         "id": str,
         "timestamp": Union[datetime, str],
         "type": str,
@@ -401,14 +468,25 @@
 
 class PutRumMetricsDestinationRequestRequestTypeDef(
     _RequiredPutRumMetricsDestinationRequestRequestTypeDef,
     _OptionalPutRumMetricsDestinationRequestRequestTypeDef,
 ):
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
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -417,14 +495,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+ListAppMonitorsResponseTypeDef = TypedDict(
+    "ListAppMonitorsResponseTypeDef",
+    {
+        "AppMonitorSummaries": List[AppMonitorSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateAppMonitorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppMonitorRequestRequestTypeDef",
     {
         "Domain": str,
         "Name": str,
     },
 )
@@ -521,112 +608,27 @@
     pass
 
 BatchGetRumMetricDefinitionsResponseTypeDef = TypedDict(
     "BatchGetRumMetricDefinitionsResponseTypeDef",
     {
         "MetricDefinitions": List[MetricDefinitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppMonitorResponseTypeDef = TypedDict(
-    "CreateAppMonitorResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAppMonitorDataResponseTypeDef = TypedDict(
-    "GetAppMonitorDataResponseTypeDef",
-    {
-        "Events": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAppMonitorsResponseTypeDef = TypedDict(
-    "ListAppMonitorsResponseTypeDef",
-    {
-        "AppMonitorSummaries": List[AppMonitorSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteRumMetricDefinitionsResponseTypeDef = TypedDict(
     "BatchDeleteRumMetricDefinitionsResponseTypeDef",
     {
         "Errors": List[BatchDeleteRumMetricDefinitionsErrorTypeDef],
         "MetricDefinitionIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
-    "_RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
-    {
-        "AppMonitorName": str,
-        "Destination": MetricDestinationType,
-    },
-)
-_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef = TypedDict(
-    "_OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef",
-    {
-        "DestinationArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef(
-    _RequiredBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-    _OptionalBatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-):
-    pass
-
-ListAppMonitorsRequestListAppMonitorsPaginateTypeDef = TypedDict(
-    "ListAppMonitorsRequestListAppMonitorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
-    "_RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
-    {
-        "AppMonitorName": str,
-    },
-)
-_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef = TypedDict(
-    "_OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef(
-    _RequiredListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
-    _OptionalListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
-):
-    pass
-
 DataStorageTypeDef = TypedDict(
     "DataStorageTypeDef",
     {
         "CwLog": CwLogTypeDef,
     },
     total=False,
 )
@@ -638,15 +640,15 @@
         "TimeRange": TimeRangeTypeDef,
     },
 )
 _OptionalGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef = TypedDict(
     "_OptionalGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef",
     {
         "Filters": Sequence[QueryFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef(
     _RequiredGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef,
     _OptionalGetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef,
@@ -676,15 +678,15 @@
     pass
 
 ListRumMetricsDestinationsResponseTypeDef = TypedDict(
     "ListRumMetricsDestinationsResponseTypeDef",
     {
         "Destinations": List[MetricDestinationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRumEventsRequestRequestTypeDef = TypedDict(
     "PutRumEventsRequestRequestTypeDef",
     {
         "AppMonitorDetails": AppMonitorDetailsTypeDef,
@@ -696,15 +698,15 @@
 )
 
 BatchCreateRumMetricDefinitionsResponseTypeDef = TypedDict(
     "BatchCreateRumMetricDefinitionsResponseTypeDef",
     {
         "Errors": List[BatchCreateRumMetricDefinitionsErrorTypeDef],
         "MetricDefinitions": List[MetricDefinitionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AppMonitorTypeDef = TypedDict(
     "AppMonitorTypeDef",
     {
         "AppMonitorConfiguration": AppMonitorConfigurationTypeDef,
@@ -721,10 +723,10 @@
     total=False,
 )
 
 GetAppMonitorResponseTypeDef = TypedDict(
     "GetAppMonitorResponseTypeDef",
     {
         "AppMonitor": AppMonitorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/PKG-INFO` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rum
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudWatchRUM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudWatchRUM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rum"></a>
 
 # types-aiobotocore-rum
 
 [![PyPI - types-aiobotocore-rum](https://img.shields.io/pypi/v/types-aiobotocore-rum.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rum)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rum.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rum)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rum?color=blue)](https://pypistats.org/packages/types-aiobotocore-rum)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatchRUM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
+[aiobotocore.CloudWatchRUM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rum.html#CloudWatchRUM)
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
 [types-aiobotocore-rum docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rum/).
 
 See how it helps to find and fix potential bugs:
 
@@ -341,48 +341,48 @@
 from types_aiobotocore_rum.type_defs import (
     AppMonitorConfigurationTypeDef,
     AppMonitorDetailsTypeDef,
     AppMonitorSummaryTypeDef,
     CustomEventsTypeDef,
     MetricDefinitionRequestTypeDef,
     MetricDefinitionTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteRumMetricDefinitionsErrorTypeDef,
     BatchDeleteRumMetricDefinitionsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
     BatchGetRumMetricDefinitionsRequestRequestTypeDef,
+    CreateAppMonitorResponseTypeDef,
     CwLogTypeDef,
     DeleteAppMonitorRequestRequestTypeDef,
     DeleteRumMetricsDestinationRequestRequestTypeDef,
     QueryFilterTypeDef,
     TimeRangeTypeDef,
+    GetAppMonitorDataResponseTypeDef,
     GetAppMonitorRequestRequestTypeDef,
+    ListAppMonitorsRequestListAppMonitorsPaginateTypeDef,
     ListAppMonitorsRequestRequestTypeDef,
+    ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
     ListRumMetricsDestinationsRequestRequestTypeDef,
     MetricDestinationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     RumEventTypeDef,
     UserDetailsTypeDef,
     PutRumMetricsDestinationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListAppMonitorsResponseTypeDef,
     CreateAppMonitorRequestRequestTypeDef,
     UpdateAppMonitorRequestRequestTypeDef,
     BatchCreateRumMetricDefinitionsErrorTypeDef,
     BatchCreateRumMetricDefinitionsRequestRequestTypeDef,
     UpdateRumMetricDefinitionRequestRequestTypeDef,
     BatchGetRumMetricDefinitionsResponseTypeDef,
-    CreateAppMonitorResponseTypeDef,
-    GetAppMonitorDataResponseTypeDef,
-    ListAppMonitorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchDeleteRumMetricDefinitionsResponseTypeDef,
-    BatchGetRumMetricDefinitionsRequestBatchGetRumMetricDefinitionsPaginateTypeDef,
-    ListAppMonitorsRequestListAppMonitorsPaginateTypeDef,
-    ListRumMetricsDestinationsRequestListRumMetricsDestinationsPaginateTypeDef,
     DataStorageTypeDef,
     GetAppMonitorDataRequestGetAppMonitorDataPaginateTypeDef,
     GetAppMonitorDataRequestRequestTypeDef,
     ListRumMetricsDestinationsResponseTypeDef,
     PutRumEventsRequestRequestTypeDef,
     BatchCreateRumMetricDefinitionsResponseTypeDef,
     AppMonitorTypeDef,
@@ -397,43 +397,43 @@
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

### Comparing `types-aiobotocore-rum-2.5.0.post1/types_aiobotocore_rum.egg-info/SOURCES.txt` & `types-aiobotocore-rum-2.5.1/types_aiobotocore_rum.egg-info/SOURCES.txt`

 * *Files identical despite different names*

