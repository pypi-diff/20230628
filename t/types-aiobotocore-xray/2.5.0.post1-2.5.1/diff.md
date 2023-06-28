# Comparing `tmp/types-aiobotocore-xray-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-xray-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-xray-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-xray-2.5.1.tar", last modified: Wed Jun 28 01:44:21 2023, max compression
```

## Comparing `types-aiobotocore-xray-2.5.0.post1.tar` & `types-aiobotocore-xray-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.715725 types-aiobotocore-xray-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19002 2023-03-11 12:27:30.715725 types-aiobotocore-xray-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17443 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.715725 types-aiobotocore-xray-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-03-11 12:25:47.000000 types-aiobotocore-xray-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.715725 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/
--rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2634 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      920 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27777 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27728 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9723 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9721 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12807 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12794 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    43295 2023-03-11 12:25:49.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    43246 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:48.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.715725 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19002 2023-03-11 12:27:30.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      756 2023-03-11 12:27:30.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:30.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-03-11 12:27:30.000000 types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:21.022233 types-aiobotocore-xray-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18991 2023-06-28 01:44:21.022233 types-aiobotocore-xray-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17438 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:21.022233 types-aiobotocore-xray-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2073 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:21.006233 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/
+-rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2634 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27777 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27728 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9932 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9930 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12707 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12695 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    43365 2023-06-28 01:42:45.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43316 2023-06-28 01:42:45.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:44.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:21.022233 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18991 2023-06-28 01:44:20.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      756 2023-06-28 01:44:20.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:20.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 01:44:20.000000 types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-xray-2.5.0.post1/LICENSE` & `types-aiobotocore-xray-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-xray-2.5.0.post1/PKG-INFO` & `types-aiobotocore-xray-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-xray
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.XRay 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.XRay 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-xray"></a>
 
 # types-aiobotocore-xray
 
 [![PyPI - types-aiobotocore-xray](https://img.shields.io/pypi/v/types-aiobotocore-xray.svg?color=blue)](https://pypi.org/project/types-aiobotocore-xray)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-xray.svg?color=blue)](https://pypi.org/project/types-aiobotocore-xray)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-xray?color=blue)](https://pypistats.org/packages/types-aiobotocore-xray)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.XRay 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay)
+[aiobotocore.XRay 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay)
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
 [types-aiobotocore-xray docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,74 +366,74 @@
 ```python
 from types_aiobotocore_xray.type_defs import (
     AliasTypeDef,
     AnnotationValueTypeDef,
     ServiceIdTypeDef,
     AvailabilityZoneDetailTypeDef,
     BackendConnectionErrorsTypeDef,
-    PaginatorConfigTypeDef,
+    BatchGetTracesRequestBatchGetTracesPaginateTypeDef,
     BatchGetTracesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     InsightsConfigurationTypeDef,
     TagTypeDef,
     SamplingRuleTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSamplingRuleRequestRequestTypeDef,
     ErrorStatisticsTypeDef,
     FaultStatisticsTypeDef,
     HistogramEntryTypeDef,
     EncryptionConfigTypeDef,
     RootCauseExceptionTypeDef,
     ForecastStatisticsTypeDef,
     GetGroupRequestRequestTypeDef,
+    GetGroupsRequestGetGroupsPaginateTypeDef,
     GetGroupsRequestRequestTypeDef,
     GetInsightEventsRequestRequestTypeDef,
     GetInsightImpactGraphRequestRequestTypeDef,
     GetInsightRequestRequestTypeDef,
     GetInsightSummariesRequestRequestTypeDef,
+    GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef,
     GetSamplingRulesRequestRequestTypeDef,
+    GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef,
     GetSamplingStatisticSummariesRequestRequestTypeDef,
     SamplingStatisticSummaryTypeDef,
     SamplingStatisticsDocumentTypeDef,
     SamplingTargetDocumentTypeDef,
     UnprocessedStatisticsTypeDef,
+    GetServiceGraphRequestGetServiceGraphPaginateTypeDef,
     GetServiceGraphRequestRequestTypeDef,
+    GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
     GetTimeSeriesServiceStatisticsRequestRequestTypeDef,
+    GetTraceGraphRequestGetTraceGraphPaginateTypeDef,
     GetTraceGraphRequestRequestTypeDef,
     SamplingStrategyTypeDef,
     HttpTypeDef,
     RequestImpactStatisticsTypeDef,
     InsightImpactGraphEdgeTypeDef,
     InstanceIdDetailTypeDef,
+    ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef,
     ListResourcePoliciesRequestRequestTypeDef,
     ResourcePolicyTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutEncryptionConfigRequestRequestTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
     PutTraceSegmentsRequestRequestTypeDef,
     UnprocessedTraceSegmentTypeDef,
     ResourceARNDetailTypeDef,
+    ResponseMetadataTypeDef,
     ResponseTimeRootCauseEntityTypeDef,
     SamplingRuleUpdateTypeDef,
     SegmentTypeDef,
     UntagResourceRequestRequestTypeDef,
     AnomalousServiceTypeDef,
     TraceUserTypeDef,
     ValueWithServiceIdsTypeDef,
     TelemetryRecordTypeDef,
-    BatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-    GetGroupsRequestGetGroupsPaginateTypeDef,
-    GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef,
-    GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef,
-    GetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-    GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-    GetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-    ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     GroupSummaryTypeDef,
     GroupTypeDef,
     UpdateGroupRequestRequestTypeDef,
     CreateGroupRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSamplingRuleRequestRequestTypeDef,
@@ -496,43 +496,43 @@
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/README.md` & `types-aiobotocore-xray-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-xray"></a>
 
 # types-aiobotocore-xray
 
 [![PyPI - types-aiobotocore-xray](https://img.shields.io/pypi/v/types-aiobotocore-xray.svg?color=blue)](https://pypi.org/project/types-aiobotocore-xray)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-xray.svg?color=blue)](https://pypi.org/project/types-aiobotocore-xray)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-xray?color=blue)](https://pypistats.org/packages/types-aiobotocore-xray)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.XRay 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay)
+[aiobotocore.XRay 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay)
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
 [types-aiobotocore-xray docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/).
 
 See how it helps to find and fix potential bugs:
 
@@ -333,74 +333,74 @@
 ```python
 from types_aiobotocore_xray.type_defs import (
     AliasTypeDef,
     AnnotationValueTypeDef,
     ServiceIdTypeDef,
     AvailabilityZoneDetailTypeDef,
     BackendConnectionErrorsTypeDef,
-    PaginatorConfigTypeDef,
+    BatchGetTracesRequestBatchGetTracesPaginateTypeDef,
     BatchGetTracesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     InsightsConfigurationTypeDef,
     TagTypeDef,
     SamplingRuleTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSamplingRuleRequestRequestTypeDef,
     ErrorStatisticsTypeDef,
     FaultStatisticsTypeDef,
     HistogramEntryTypeDef,
     EncryptionConfigTypeDef,
     RootCauseExceptionTypeDef,
     ForecastStatisticsTypeDef,
     GetGroupRequestRequestTypeDef,
+    GetGroupsRequestGetGroupsPaginateTypeDef,
     GetGroupsRequestRequestTypeDef,
     GetInsightEventsRequestRequestTypeDef,
     GetInsightImpactGraphRequestRequestTypeDef,
     GetInsightRequestRequestTypeDef,
     GetInsightSummariesRequestRequestTypeDef,
+    GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef,
     GetSamplingRulesRequestRequestTypeDef,
+    GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef,
     GetSamplingStatisticSummariesRequestRequestTypeDef,
     SamplingStatisticSummaryTypeDef,
     SamplingStatisticsDocumentTypeDef,
     SamplingTargetDocumentTypeDef,
     UnprocessedStatisticsTypeDef,
+    GetServiceGraphRequestGetServiceGraphPaginateTypeDef,
     GetServiceGraphRequestRequestTypeDef,
+    GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
     GetTimeSeriesServiceStatisticsRequestRequestTypeDef,
+    GetTraceGraphRequestGetTraceGraphPaginateTypeDef,
     GetTraceGraphRequestRequestTypeDef,
     SamplingStrategyTypeDef,
     HttpTypeDef,
     RequestImpactStatisticsTypeDef,
     InsightImpactGraphEdgeTypeDef,
     InstanceIdDetailTypeDef,
+    ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef,
     ListResourcePoliciesRequestRequestTypeDef,
     ResourcePolicyTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutEncryptionConfigRequestRequestTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
     PutTraceSegmentsRequestRequestTypeDef,
     UnprocessedTraceSegmentTypeDef,
     ResourceARNDetailTypeDef,
+    ResponseMetadataTypeDef,
     ResponseTimeRootCauseEntityTypeDef,
     SamplingRuleUpdateTypeDef,
     SegmentTypeDef,
     UntagResourceRequestRequestTypeDef,
     AnomalousServiceTypeDef,
     TraceUserTypeDef,
     ValueWithServiceIdsTypeDef,
     TelemetryRecordTypeDef,
-    BatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-    GetGroupsRequestGetGroupsPaginateTypeDef,
-    GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef,
-    GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef,
-    GetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-    GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-    GetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-    ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     GroupSummaryTypeDef,
     GroupTypeDef,
     UpdateGroupRequestRequestTypeDef,
     CreateGroupRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSamplingRuleRequestRequestTypeDef,
@@ -463,43 +463,43 @@
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/setup.py` & `types-aiobotocore-xray-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-xray.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-xray",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_xray"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.XRay 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.XRay 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/",
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/__init__.py` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/__init__.pyi` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/__main__.py` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.XRay 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.XRay 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray//\nBoto3 docs:   "
         "   https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay\nOther"
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/client.py` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/client.pyi` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/literals.py` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -119,14 +119,15 @@
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
@@ -205,14 +206,15 @@
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
@@ -223,14 +225,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -292,16 +296,19 @@
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
@@ -385,15 +392,17 @@
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/literals.pyi` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -117,14 +117,15 @@
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
@@ -203,14 +204,15 @@
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
@@ -221,14 +223,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -290,16 +294,19 @@
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
@@ -383,15 +390,17 @@
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/paginator.py` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         get_time_series_service_statistics_paginator: GetTimeSeriesServiceStatisticsPaginator = client.get_paginator("get_time_series_service_statistics")
         get_trace_graph_paginator: GetTraceGraphPaginator = client.get_paginator("get_trace_graph")
         get_trace_summaries_paginator: GetTraceSummariesPaginator = client.get_paginator("get_trace_summaries")
         list_resource_policies_paginator: ListResourcePoliciesPaginator = client.get_paginator("list_resource_policies")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import TimeRangeTypeType
 from .type_defs import (
     BatchGetTracesResultTypeDef,
@@ -57,20 +56,14 @@
     GetTraceSummariesResultTypeDef,
     ListResourcePoliciesResultTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     SamplingStrategyTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "BatchGetTracesPaginator",
     "GetGroupsPaginator",
     "GetSamplingRulesPaginator",
     "GetSamplingStatisticSummariesPaginator",
     "GetServiceGraphPaginator",
     "GetTimeSeriesServiceStatisticsPaginator",
@@ -94,60 +87,60 @@
 class BatchGetTracesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.BatchGetTraces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#batchgettracespaginator)
     """
 
     def paginate(
-        self, *, TraceIds: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TraceIds: Sequence[str], PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[BatchGetTracesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.BatchGetTraces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#batchgettracespaginator)
         """
 
 
 class GetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getgroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getgroupspaginator)
         """
 
 
 class GetSamplingRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingrulespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSamplingRulesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingrulespaginator)
         """
 
 
 class GetSamplingStatisticSummariesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingStatisticSummaries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingstatisticsummariespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSamplingStatisticSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingStatisticSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingstatisticsummariespaginator)
         """
 
 
@@ -160,15 +153,15 @@
     def paginate(
         self,
         *,
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         GroupName: str = ...,
         GroupARN: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetServiceGraphResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetServiceGraph.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getservicegraphpaginator)
         """
 
 
@@ -184,30 +177,30 @@
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         GroupName: str = ...,
         GroupARN: str = ...,
         EntitySelectorExpression: str = ...,
         Period: int = ...,
         ForecastStatistics: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTimeSeriesServiceStatisticsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTimeSeriesServiceStatistics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettimeseriesservicestatisticspaginator)
         """
 
 
 class GetTraceGraphPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTraceGraph)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettracegraphpaginator)
     """
 
     def paginate(
-        self, *, TraceIds: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TraceIds: Sequence[str], PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTraceGraphResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTraceGraph.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettracegraphpaginator)
         """
 
 
@@ -222,43 +215,43 @@
         *,
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         TimeRangeType: TimeRangeTypeType = ...,
         Sampling: bool = ...,
         SamplingStrategy: SamplingStrategyTypeDef = ...,
         FilterExpression: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTraceSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTraceSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettracesummariespaginator)
         """
 
 
 class ListResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcePoliciesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listresourcepoliciespaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/paginator.pyi` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         get_time_series_service_statistics_paginator: GetTimeSeriesServiceStatisticsPaginator = client.get_paginator("get_time_series_service_statistics")
         get_trace_graph_paginator: GetTraceGraphPaginator = client.get_paginator("get_trace_graph")
         get_trace_summaries_paginator: GetTraceSummariesPaginator = client.get_paginator("get_trace_summaries")
         list_resource_policies_paginator: ListResourcePoliciesPaginator = client.get_paginator("list_resource_policies")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import TimeRangeTypeType
 from .type_defs import (
     BatchGetTracesResultTypeDef,
@@ -57,19 +56,14 @@
     GetTraceSummariesResultTypeDef,
     ListResourcePoliciesResultTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     SamplingStrategyTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "BatchGetTracesPaginator",
     "GetGroupsPaginator",
     "GetSamplingRulesPaginator",
     "GetSamplingStatisticSummariesPaginator",
     "GetServiceGraphPaginator",
     "GetTimeSeriesServiceStatisticsPaginator",
@@ -90,57 +84,57 @@
 class BatchGetTracesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.BatchGetTraces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#batchgettracespaginator)
     """
 
     def paginate(
-        self, *, TraceIds: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TraceIds: Sequence[str], PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[BatchGetTracesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.BatchGetTraces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#batchgettracespaginator)
         """
 
 class GetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getgroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getgroupspaginator)
         """
 
 class GetSamplingRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingrulespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSamplingRulesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingrulespaginator)
         """
 
 class GetSamplingStatisticSummariesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingStatisticSummaries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingstatisticsummariespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSamplingStatisticSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetSamplingStatisticSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getsamplingstatisticsummariespaginator)
         """
 
 class GetServiceGraphPaginator(AioPaginator):
@@ -152,15 +146,15 @@
     def paginate(
         self,
         *,
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         GroupName: str = ...,
         GroupARN: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetServiceGraphResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetServiceGraph.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#getservicegraphpaginator)
         """
 
 class GetTimeSeriesServiceStatisticsPaginator(AioPaginator):
@@ -175,29 +169,29 @@
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         GroupName: str = ...,
         GroupARN: str = ...,
         EntitySelectorExpression: str = ...,
         Period: int = ...,
         ForecastStatistics: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTimeSeriesServiceStatisticsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTimeSeriesServiceStatistics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettimeseriesservicestatisticspaginator)
         """
 
 class GetTraceGraphPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTraceGraph)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettracegraphpaginator)
     """
 
     def paginate(
-        self, *, TraceIds: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TraceIds: Sequence[str], PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTraceGraphResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTraceGraph.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettracegraphpaginator)
         """
 
 class GetTraceSummariesPaginator(AioPaginator):
@@ -211,41 +205,41 @@
         *,
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         TimeRangeType: TimeRangeTypeType = ...,
         Sampling: bool = ...,
         SamplingStrategy: SamplingStrategyTypeDef = ...,
         FilterExpression: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTraceSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.GetTraceSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#gettracesummariespaginator)
         """
 
 class ListResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcePoliciesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listresourcepoliciespaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/type_defs.py` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -28,81 +28,80 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AliasTypeDef",
     "AnnotationValueTypeDef",
     "ServiceIdTypeDef",
     "AvailabilityZoneDetailTypeDef",
     "BackendConnectionErrorsTypeDef",
-    "PaginatorConfigTypeDef",
+    "BatchGetTracesRequestBatchGetTracesPaginateTypeDef",
     "BatchGetTracesRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "InsightsConfigurationTypeDef",
     "TagTypeDef",
     "SamplingRuleTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSamplingRuleRequestRequestTypeDef",
     "ErrorStatisticsTypeDef",
     "FaultStatisticsTypeDef",
     "HistogramEntryTypeDef",
     "EncryptionConfigTypeDef",
     "RootCauseExceptionTypeDef",
     "ForecastStatisticsTypeDef",
     "GetGroupRequestRequestTypeDef",
+    "GetGroupsRequestGetGroupsPaginateTypeDef",
     "GetGroupsRequestRequestTypeDef",
     "GetInsightEventsRequestRequestTypeDef",
     "GetInsightImpactGraphRequestRequestTypeDef",
     "GetInsightRequestRequestTypeDef",
     "GetInsightSummariesRequestRequestTypeDef",
+    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
     "GetSamplingRulesRequestRequestTypeDef",
+    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
     "GetSamplingStatisticSummariesRequestRequestTypeDef",
     "SamplingStatisticSummaryTypeDef",
     "SamplingStatisticsDocumentTypeDef",
     "SamplingTargetDocumentTypeDef",
     "UnprocessedStatisticsTypeDef",
+    "GetServiceGraphRequestGetServiceGraphPaginateTypeDef",
     "GetServiceGraphRequestRequestTypeDef",
+    "GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
     "GetTimeSeriesServiceStatisticsRequestRequestTypeDef",
+    "GetTraceGraphRequestGetTraceGraphPaginateTypeDef",
     "GetTraceGraphRequestRequestTypeDef",
     "SamplingStrategyTypeDef",
     "HttpTypeDef",
     "RequestImpactStatisticsTypeDef",
     "InsightImpactGraphEdgeTypeDef",
     "InstanceIdDetailTypeDef",
+    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
     "ListResourcePoliciesRequestRequestTypeDef",
     "ResourcePolicyTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutEncryptionConfigRequestRequestTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
     "PutTraceSegmentsRequestRequestTypeDef",
     "UnprocessedTraceSegmentTypeDef",
     "ResourceARNDetailTypeDef",
+    "ResponseMetadataTypeDef",
     "ResponseTimeRootCauseEntityTypeDef",
     "SamplingRuleUpdateTypeDef",
     "SegmentTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AnomalousServiceTypeDef",
     "TraceUserTypeDef",
     "ValueWithServiceIdsTypeDef",
     "TelemetryRecordTypeDef",
-    "BatchGetTracesRequestBatchGetTracesPaginateTypeDef",
-    "GetGroupsRequestGetGroupsPaginateTypeDef",
-    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
-    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
-    "GetServiceGraphRequestGetServiceGraphPaginateTypeDef",
-    "GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
-    "GetTraceGraphRequestGetTraceGraphPaginateTypeDef",
-    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "GroupSummaryTypeDef",
     "GroupTypeDef",
     "UpdateGroupRequestRequestTypeDef",
     "CreateGroupRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateSamplingRuleRequestRequestTypeDef",
@@ -205,56 +204,53 @@
         "HTTPCode5XXCount": int,
         "UnknownHostCount": int,
         "OtherCount": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
+    "_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TraceIds": Sequence[str],
+    },
+)
+_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
+    "_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class BatchGetTracesRequestBatchGetTracesPaginateTypeDef(
+    _RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
+    _OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
+):
+    pass
+
 _RequiredBatchGetTracesRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetTracesRequestRequestTypeDef",
     {
         "TraceIds": Sequence[str],
     },
 )
 _OptionalBatchGetTracesRequestRequestTypeDef = TypedDict(
     "_OptionalBatchGetTracesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class BatchGetTracesRequestRequestTypeDef(
     _RequiredBatchGetTracesRequestRequestTypeDef, _OptionalBatchGetTracesRequestRequestTypeDef
 ):
     pass
 
-
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
 InsightsConfigurationTypeDef = TypedDict(
     "InsightsConfigurationTypeDef",
     {
         "InsightsEnabled": bool,
         "NotificationsEnabled": bool,
     },
     total=False,
@@ -289,19 +285,17 @@
         "RuleName": str,
         "RuleARN": str,
         "Attributes": Mapping[str, str],
     },
     total=False,
 )
 
-
 class SamplingRuleTypeDef(_RequiredSamplingRuleTypeDef, _OptionalSamplingRuleTypeDef):
     pass
 
-
 DeleteGroupRequestRequestTypeDef = TypedDict(
     "DeleteGroupRequestRequestTypeDef",
     {
         "GroupName": str,
         "GroupARN": str,
     },
     total=False,
@@ -317,22 +311,20 @@
     "_OptionalDeleteResourcePolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
-
 class DeleteResourcePolicyRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteSamplingRuleRequestRequestTypeDef = TypedDict(
     "DeleteSamplingRuleRequestRequestTypeDef",
     {
         "RuleName": str,
         "RuleARN": str,
     },
     total=False,
@@ -399,14 +391,22 @@
     {
         "GroupName": str,
         "GroupARN": str,
     },
     total=False,
 )
 
+GetGroupsRequestGetGroupsPaginateTypeDef = TypedDict(
+    "GetGroupsRequestGetGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetGroupsRequestRequestTypeDef = TypedDict(
     "GetGroupsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
@@ -422,21 +422,19 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetInsightEventsRequestRequestTypeDef(
     _RequiredGetInsightEventsRequestRequestTypeDef, _OptionalGetInsightEventsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredGetInsightImpactGraphRequestRequestTypeDef = TypedDict(
     "_RequiredGetInsightImpactGraphRequestRequestTypeDef",
     {
         "InsightId": str,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
@@ -445,22 +443,20 @@
     "_OptionalGetInsightImpactGraphRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetInsightImpactGraphRequestRequestTypeDef(
     _RequiredGetInsightImpactGraphRequestRequestTypeDef,
     _OptionalGetInsightImpactGraphRequestRequestTypeDef,
 ):
     pass
 
-
 GetInsightRequestRequestTypeDef = TypedDict(
     "GetInsightRequestRequestTypeDef",
     {
         "InsightId": str,
     },
 )
 
@@ -479,30 +475,44 @@
         "GroupName": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetInsightSummariesRequestRequestTypeDef(
     _RequiredGetInsightSummariesRequestRequestTypeDef,
     _OptionalGetInsightSummariesRequestRequestTypeDef,
 ):
     pass
 
+GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef = TypedDict(
+    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 GetSamplingRulesRequestRequestTypeDef = TypedDict(
     "GetSamplingRulesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef = TypedDict(
+    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSamplingStatisticSummariesRequestRequestTypeDef = TypedDict(
     "GetSamplingStatisticSummariesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
@@ -533,21 +543,19 @@
     "_OptionalSamplingStatisticsDocumentTypeDef",
     {
         "BorrowCount": int,
     },
     total=False,
 )
 
-
 class SamplingStatisticsDocumentTypeDef(
     _RequiredSamplingStatisticsDocumentTypeDef, _OptionalSamplingStatisticsDocumentTypeDef
 ):
     pass
 
-
 SamplingTargetDocumentTypeDef = TypedDict(
     "SamplingTargetDocumentTypeDef",
     {
         "RuleName": str,
         "FixedRate": float,
         "ReservoirQuota": int,
         "ReservoirQuotaTTL": datetime,
@@ -562,14 +570,37 @@
         "RuleName": str,
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
 )
 
+_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
+    "_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+    },
+)
+_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
+    "_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
+    {
+        "GroupName": str,
+        "GroupARN": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetServiceGraphRequestGetServiceGraphPaginateTypeDef(
+    _RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
+    _OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
+):
+    pass
+
 _RequiredGetServiceGraphRequestRequestTypeDef = TypedDict(
     "_RequiredGetServiceGraphRequestRequestTypeDef",
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
 )
@@ -579,20 +610,44 @@
         "GroupName": str,
         "GroupARN": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetServiceGraphRequestRequestTypeDef(
     _RequiredGetServiceGraphRequestRequestTypeDef, _OptionalGetServiceGraphRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
+    "_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+    },
+)
+_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
+    "_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
+    {
+        "GroupName": str,
+        "GroupARN": str,
+        "EntitySelectorExpression": str,
+        "Period": int,
+        "ForecastStatistics": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef(
+    _RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
+    _OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
+):
+    pass
 
 _RequiredGetTimeSeriesServiceStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTimeSeriesServiceStatisticsRequestRequestTypeDef",
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
@@ -606,21 +661,39 @@
         "Period": int,
         "ForecastStatistics": bool,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetTimeSeriesServiceStatisticsRequestRequestTypeDef(
     _RequiredGetTimeSeriesServiceStatisticsRequestRequestTypeDef,
     _OptionalGetTimeSeriesServiceStatisticsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
+    "_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
+    {
+        "TraceIds": Sequence[str],
+    },
+)
+_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
+    "_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTraceGraphRequestGetTraceGraphPaginateTypeDef(
+    _RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
+    _OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
+):
+    pass
 
 _RequiredGetTraceGraphRequestRequestTypeDef = TypedDict(
     "_RequiredGetTraceGraphRequestRequestTypeDef",
     {
         "TraceIds": Sequence[str],
     },
 )
@@ -628,21 +701,19 @@
     "_OptionalGetTraceGraphRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetTraceGraphRequestRequestTypeDef(
     _RequiredGetTraceGraphRequestRequestTypeDef, _OptionalGetTraceGraphRequestRequestTypeDef
 ):
     pass
 
-
 SamplingStrategyTypeDef = TypedDict(
     "SamplingStrategyTypeDef",
     {
         "Name": SamplingStrategyNameType,
         "Value": float,
     },
     total=False,
@@ -682,14 +753,22 @@
     "InstanceIdDetailTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
 
+ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef = TypedDict(
+    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourcePoliciesRequestRequestTypeDef = TypedDict(
     "ListResourcePoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
@@ -701,35 +780,63 @@
         "PolicyDocument": str,
         "PolicyRevisionId": str,
         "LastUpdatedTime": datetime,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
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
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_OptionalListTagsForResourceRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
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
 
 _RequiredPutEncryptionConfigRequestRequestTypeDef = TypedDict(
     "_RequiredPutEncryptionConfigRequestRequestTypeDef",
     {
         "Type": EncryptionTypeType,
     },
 )
@@ -737,22 +844,20 @@
     "_OptionalPutEncryptionConfigRequestRequestTypeDef",
     {
         "KeyId": str,
     },
     total=False,
 )
 
-
 class PutEncryptionConfigRequestRequestTypeDef(
     _RequiredPutEncryptionConfigRequestRequestTypeDef,
     _OptionalPutEncryptionConfigRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "PolicyName": str,
         "PolicyDocument": str,
     },
 )
@@ -761,21 +866,19 @@
     {
         "PolicyRevisionId": str,
         "BypassPolicyLockoutCheck": bool,
     },
     total=False,
 )
 
-
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
-
 PutTraceSegmentsRequestRequestTypeDef = TypedDict(
     "PutTraceSegmentsRequestRequestTypeDef",
     {
         "TraceSegmentDocuments": Sequence[str],
     },
 )
 
@@ -793,14 +896,25 @@
     "ResourceARNDetailTypeDef",
     {
         "ARN": str,
     },
     total=False,
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
 ResponseTimeRootCauseEntityTypeDef = TypedDict(
     "ResponseTimeRootCauseEntityTypeDef",
     {
         "Name": str,
         "Coverage": float,
         "Remote": bool,
     },
@@ -883,170 +997,17 @@
         "SegmentsSpilloverCount": int,
         "SegmentsRejectedCount": int,
         "BackendConnectionErrors": BackendConnectionErrorsTypeDef,
     },
     total=False,
 )
 
-
 class TelemetryRecordTypeDef(_RequiredTelemetryRecordTypeDef, _OptionalTelemetryRecordTypeDef):
     pass
 
-
-_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
-    "_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
-    {
-        "TraceIds": Sequence[str],
-    },
-)
-_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
-    "_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class BatchGetTracesRequestBatchGetTracesPaginateTypeDef(
-    _RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-    _OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-):
-    pass
-
-
-GetGroupsRequestGetGroupsPaginateTypeDef = TypedDict(
-    "GetGroupsRequestGetGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef = TypedDict(
-    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef = TypedDict(
-    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
-    "_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
-    {
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-    },
-)
-_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
-    "_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
-    {
-        "GroupName": str,
-        "GroupARN": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetServiceGraphRequestGetServiceGraphPaginateTypeDef(
-    _RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-    _OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
-    "_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
-    {
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-    },
-)
-_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
-    "_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
-    {
-        "GroupName": str,
-        "GroupARN": str,
-        "EntitySelectorExpression": str,
-        "Period": int,
-        "ForecastStatistics": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef(
-    _RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-    _OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
-    "_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
-    {
-        "TraceIds": Sequence[str],
-    },
-)
-_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
-    "_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTraceGraphRequestGetTraceGraphPaginateTypeDef(
-    _RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-    _OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-):
-    pass
-
-
-ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef = TypedDict(
-    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
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
 GroupSummaryTypeDef = TypedDict(
     "GroupSummaryTypeDef",
     {
         "GroupName": str,
         "GroupARN": str,
         "FilterExpression": str,
         "InsightsConfiguration": InsightsConfigurationTypeDef,
@@ -1088,27 +1049,25 @@
         "FilterExpression": str,
         "InsightsConfiguration": InsightsConfigurationTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateGroupRequestRequestTypeDef(
     _RequiredCreateGroupRequestRequestTypeDef, _OptionalCreateGroupRequestRequestTypeDef
 ):
     pass
 
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -1126,22 +1085,20 @@
     "_OptionalCreateSamplingRuleRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateSamplingRuleRequestRequestTypeDef(
     _RequiredCreateSamplingRuleRequestRequestTypeDef,
     _OptionalCreateSamplingRuleRequestRequestTypeDef,
 ):
     pass
 
-
 SamplingRuleRecordTypeDef = TypedDict(
     "SamplingRuleRecordTypeDef",
     {
         "SamplingRule": SamplingRuleTypeDef,
         "CreatedAt": datetime,
         "ModifiedAt": datetime,
     },
@@ -1172,23 +1129,23 @@
     total=False,
 )
 
 GetEncryptionConfigResultTypeDef = TypedDict(
     "GetEncryptionConfigResultTypeDef",
     {
         "EncryptionConfig": EncryptionConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutEncryptionConfigResultTypeDef = TypedDict(
     "PutEncryptionConfigResultTypeDef",
     {
         "EncryptionConfig": EncryptionConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ErrorRootCauseEntityTypeDef = TypedDict(
     "ErrorRootCauseEntityTypeDef",
     {
         "Name": str,
@@ -1209,15 +1166,15 @@
 )
 
 GetSamplingStatisticSummariesResultTypeDef = TypedDict(
     "GetSamplingStatisticSummariesResultTypeDef",
     {
         "SamplingStatisticSummaries": List[SamplingStatisticSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSamplingTargetsRequestRequestTypeDef = TypedDict(
     "GetSamplingTargetsRequestRequestTypeDef",
     {
         "SamplingStatisticsDocuments": Sequence[SamplingStatisticsDocumentTypeDef],
@@ -1226,15 +1183,15 @@
 
 GetSamplingTargetsResultTypeDef = TypedDict(
     "GetSamplingTargetsResultTypeDef",
     {
         "SamplingTargetDocuments": List[SamplingTargetDocumentTypeDef],
         "LastRuleModification": datetime,
         "UnprocessedStatistics": List[UnprocessedStatisticsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef = TypedDict(
     "_RequiredGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef",
     {
         "StartTime": Union[datetime, str],
@@ -1244,27 +1201,25 @@
 _OptionalGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef = TypedDict(
     "_OptionalGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef",
     {
         "TimeRangeType": TimeRangeTypeType,
         "Sampling": bool,
         "SamplingStrategy": SamplingStrategyTypeDef,
         "FilterExpression": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class GetTraceSummariesRequestGetTraceSummariesPaginateTypeDef(
     _RequiredGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef,
     _OptionalGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef,
 ):
     pass
 
-
 _RequiredGetTraceSummariesRequestRequestTypeDef = TypedDict(
     "_RequiredGetTraceSummariesRequestRequestTypeDef",
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
 )
@@ -1276,21 +1231,19 @@
         "SamplingStrategy": SamplingStrategyTypeDef,
         "FilterExpression": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetTraceSummariesRequestRequestTypeDef(
     _RequiredGetTraceSummariesRequestRequestTypeDef, _OptionalGetTraceSummariesRequestRequestTypeDef
 ):
     pass
 
-
 InsightImpactGraphServiceTypeDef = TypedDict(
     "InsightImpactGraphServiceTypeDef",
     {
         "ReferenceId": int,
         "Type": str,
         "Name": str,
         "Names": List[str],
@@ -1301,31 +1254,31 @@
 )
 
 ListResourcePoliciesResultTypeDef = TypedDict(
     "ListResourcePoliciesResultTypeDef",
     {
         "ResourcePolicies": List[ResourcePolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourcePolicyResultTypeDef = TypedDict(
     "PutResourcePolicyResultTypeDef",
     {
         "ResourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutTraceSegmentsResultTypeDef = TypedDict(
     "PutTraceSegmentsResultTypeDef",
     {
         "UnprocessedTraceSegments": List[UnprocessedTraceSegmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseTimeRootCauseServiceTypeDef = TypedDict(
     "ResponseTimeRootCauseServiceTypeDef",
     {
         "Name": str,
@@ -1419,85 +1372,83 @@
         "EC2InstanceId": str,
         "Hostname": str,
         "ResourceARN": str,
     },
     total=False,
 )
 
-
 class PutTelemetryRecordsRequestRequestTypeDef(
     _RequiredPutTelemetryRecordsRequestRequestTypeDef,
     _OptionalPutTelemetryRecordsRequestRequestTypeDef,
 ):
     pass
 
-
 GetGroupsResultTypeDef = TypedDict(
     "GetGroupsResultTypeDef",
     {
         "Groups": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGroupResultTypeDef = TypedDict(
     "CreateGroupResultTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupResultTypeDef = TypedDict(
     "GetGroupResultTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGroupResultTypeDef = TypedDict(
     "UpdateGroupResultTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSamplingRuleResultTypeDef = TypedDict(
     "CreateSamplingRuleResultTypeDef",
     {
         "SamplingRuleRecord": SamplingRuleRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSamplingRuleResultTypeDef = TypedDict(
     "DeleteSamplingRuleResultTypeDef",
     {
         "SamplingRuleRecord": SamplingRuleRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSamplingRulesResultTypeDef = TypedDict(
     "GetSamplingRulesResultTypeDef",
     {
         "SamplingRuleRecords": List[SamplingRuleRecordTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSamplingRuleResultTypeDef = TypedDict(
     "UpdateSamplingRuleResultTypeDef",
     {
         "SamplingRuleRecord": SamplingRuleRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EdgeTypeDef = TypedDict(
     "EdgeTypeDef",
     {
         "ReferenceId": int,
@@ -1556,15 +1507,15 @@
         "InsightId": str,
         "StartTime": datetime,
         "EndTime": datetime,
         "ServiceGraphStartTime": datetime,
         "ServiceGraphEndTime": datetime,
         "Services": List[InsightImpactGraphServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseTimeRootCauseTypeDef = TypedDict(
     "ResponseTimeRootCauseTypeDef",
     {
         "Services": List[ResponseTimeRootCauseServiceTypeDef],
@@ -1575,41 +1526,41 @@
 
 BatchGetTracesResultTypeDef = TypedDict(
     "BatchGetTracesResultTypeDef",
     {
         "Traces": List[TraceTypeDef],
         "UnprocessedTraceIds": List[str],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightEventsResultTypeDef = TypedDict(
     "GetInsightEventsResultTypeDef",
     {
         "InsightEvents": List[InsightEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightSummariesResultTypeDef = TypedDict(
     "GetInsightSummariesResultTypeDef",
     {
         "InsightSummaries": List[InsightSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightResultTypeDef = TypedDict(
     "GetInsightResultTypeDef",
     {
         "Insight": InsightTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceTypeDef = TypedDict(
     "ServiceTypeDef",
     {
         "ReferenceId": int,
@@ -1631,15 +1582,15 @@
 
 GetTimeSeriesServiceStatisticsResultTypeDef = TypedDict(
     "GetTimeSeriesServiceStatisticsResultTypeDef",
     {
         "TimeSeriesServiceStatistics": List[TimeSeriesServiceStatisticsTypeDef],
         "ContainsOldGroupVersions": bool,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ErrorRootCauseTypeDef = TypedDict(
     "ErrorRootCauseTypeDef",
     {
         "Services": List[ErrorRootCauseServiceTypeDef],
@@ -1661,24 +1612,24 @@
     "GetServiceGraphResultTypeDef",
     {
         "StartTime": datetime,
         "EndTime": datetime,
         "Services": List[ServiceTypeDef],
         "ContainsOldGroupVersions": bool,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTraceGraphResultTypeDef = TypedDict(
     "GetTraceGraphResultTypeDef",
     {
         "Services": List[ServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TraceSummaryTypeDef = TypedDict(
     "TraceSummaryTypeDef",
     {
         "Id": str,
@@ -1708,10 +1659,10 @@
 GetTraceSummariesResultTypeDef = TypedDict(
     "GetTraceSummariesResultTypeDef",
     {
         "TraceSummaries": List[TraceSummaryTypeDef],
         "ApproximateTime": datetime,
         "TracesProcessedCount": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray/type_defs.pyi` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,80 +28,81 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AliasTypeDef",
     "AnnotationValueTypeDef",
     "ServiceIdTypeDef",
     "AvailabilityZoneDetailTypeDef",
     "BackendConnectionErrorsTypeDef",
-    "PaginatorConfigTypeDef",
+    "BatchGetTracesRequestBatchGetTracesPaginateTypeDef",
     "BatchGetTracesRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "InsightsConfigurationTypeDef",
     "TagTypeDef",
     "SamplingRuleTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeleteSamplingRuleRequestRequestTypeDef",
     "ErrorStatisticsTypeDef",
     "FaultStatisticsTypeDef",
     "HistogramEntryTypeDef",
     "EncryptionConfigTypeDef",
     "RootCauseExceptionTypeDef",
     "ForecastStatisticsTypeDef",
     "GetGroupRequestRequestTypeDef",
+    "GetGroupsRequestGetGroupsPaginateTypeDef",
     "GetGroupsRequestRequestTypeDef",
     "GetInsightEventsRequestRequestTypeDef",
     "GetInsightImpactGraphRequestRequestTypeDef",
     "GetInsightRequestRequestTypeDef",
     "GetInsightSummariesRequestRequestTypeDef",
+    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
     "GetSamplingRulesRequestRequestTypeDef",
+    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
     "GetSamplingStatisticSummariesRequestRequestTypeDef",
     "SamplingStatisticSummaryTypeDef",
     "SamplingStatisticsDocumentTypeDef",
     "SamplingTargetDocumentTypeDef",
     "UnprocessedStatisticsTypeDef",
+    "GetServiceGraphRequestGetServiceGraphPaginateTypeDef",
     "GetServiceGraphRequestRequestTypeDef",
+    "GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
     "GetTimeSeriesServiceStatisticsRequestRequestTypeDef",
+    "GetTraceGraphRequestGetTraceGraphPaginateTypeDef",
     "GetTraceGraphRequestRequestTypeDef",
     "SamplingStrategyTypeDef",
     "HttpTypeDef",
     "RequestImpactStatisticsTypeDef",
     "InsightImpactGraphEdgeTypeDef",
     "InstanceIdDetailTypeDef",
+    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
     "ListResourcePoliciesRequestRequestTypeDef",
     "ResourcePolicyTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutEncryptionConfigRequestRequestTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
     "PutTraceSegmentsRequestRequestTypeDef",
     "UnprocessedTraceSegmentTypeDef",
     "ResourceARNDetailTypeDef",
+    "ResponseMetadataTypeDef",
     "ResponseTimeRootCauseEntityTypeDef",
     "SamplingRuleUpdateTypeDef",
     "SegmentTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AnomalousServiceTypeDef",
     "TraceUserTypeDef",
     "ValueWithServiceIdsTypeDef",
     "TelemetryRecordTypeDef",
-    "BatchGetTracesRequestBatchGetTracesPaginateTypeDef",
-    "GetGroupsRequestGetGroupsPaginateTypeDef",
-    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
-    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
-    "GetServiceGraphRequestGetServiceGraphPaginateTypeDef",
-    "GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
-    "GetTraceGraphRequestGetTraceGraphPaginateTypeDef",
-    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "GroupSummaryTypeDef",
     "GroupTypeDef",
     "UpdateGroupRequestRequestTypeDef",
     "CreateGroupRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateSamplingRuleRequestRequestTypeDef",
@@ -204,53 +205,56 @@
         "HTTPCode5XXCount": int,
         "UnknownHostCount": int,
         "OtherCount": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
+    "_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TraceIds": Sequence[str],
+    },
+)
+_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
+    "_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class BatchGetTracesRequestBatchGetTracesPaginateTypeDef(
+    _RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
+    _OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredBatchGetTracesRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetTracesRequestRequestTypeDef",
     {
         "TraceIds": Sequence[str],
     },
 )
 _OptionalBatchGetTracesRequestRequestTypeDef = TypedDict(
     "_OptionalBatchGetTracesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class BatchGetTracesRequestRequestTypeDef(
     _RequiredBatchGetTracesRequestRequestTypeDef, _OptionalBatchGetTracesRequestRequestTypeDef
 ):
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
 
 InsightsConfigurationTypeDef = TypedDict(
     "InsightsConfigurationTypeDef",
     {
         "InsightsEnabled": bool,
         "NotificationsEnabled": bool,
     },
@@ -286,17 +290,19 @@
         "RuleName": str,
         "RuleARN": str,
         "Attributes": Mapping[str, str],
     },
     total=False,
 )
 
+
 class SamplingRuleTypeDef(_RequiredSamplingRuleTypeDef, _OptionalSamplingRuleTypeDef):
     pass
 
+
 DeleteGroupRequestRequestTypeDef = TypedDict(
     "DeleteGroupRequestRequestTypeDef",
     {
         "GroupName": str,
         "GroupARN": str,
     },
     total=False,
@@ -312,20 +318,22 @@
     "_OptionalDeleteResourcePolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
+
 class DeleteResourcePolicyRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteSamplingRuleRequestRequestTypeDef = TypedDict(
     "DeleteSamplingRuleRequestRequestTypeDef",
     {
         "RuleName": str,
         "RuleARN": str,
     },
     total=False,
@@ -392,14 +400,22 @@
     {
         "GroupName": str,
         "GroupARN": str,
     },
     total=False,
 )
 
+GetGroupsRequestGetGroupsPaginateTypeDef = TypedDict(
+    "GetGroupsRequestGetGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetGroupsRequestRequestTypeDef = TypedDict(
     "GetGroupsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
@@ -415,19 +431,21 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetInsightEventsRequestRequestTypeDef(
     _RequiredGetInsightEventsRequestRequestTypeDef, _OptionalGetInsightEventsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredGetInsightImpactGraphRequestRequestTypeDef = TypedDict(
     "_RequiredGetInsightImpactGraphRequestRequestTypeDef",
     {
         "InsightId": str,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
@@ -436,20 +454,22 @@
     "_OptionalGetInsightImpactGraphRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetInsightImpactGraphRequestRequestTypeDef(
     _RequiredGetInsightImpactGraphRequestRequestTypeDef,
     _OptionalGetInsightImpactGraphRequestRequestTypeDef,
 ):
     pass
 
+
 GetInsightRequestRequestTypeDef = TypedDict(
     "GetInsightRequestRequestTypeDef",
     {
         "InsightId": str,
     },
 )
 
@@ -468,28 +488,46 @@
         "GroupName": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetInsightSummariesRequestRequestTypeDef(
     _RequiredGetInsightSummariesRequestRequestTypeDef,
     _OptionalGetInsightSummariesRequestRequestTypeDef,
 ):
     pass
 
+
+GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef = TypedDict(
+    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSamplingRulesRequestRequestTypeDef = TypedDict(
     "GetSamplingRulesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef = TypedDict(
+    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSamplingStatisticSummariesRequestRequestTypeDef = TypedDict(
     "GetSamplingStatisticSummariesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
@@ -520,19 +558,21 @@
     "_OptionalSamplingStatisticsDocumentTypeDef",
     {
         "BorrowCount": int,
     },
     total=False,
 )
 
+
 class SamplingStatisticsDocumentTypeDef(
     _RequiredSamplingStatisticsDocumentTypeDef, _OptionalSamplingStatisticsDocumentTypeDef
 ):
     pass
 
+
 SamplingTargetDocumentTypeDef = TypedDict(
     "SamplingTargetDocumentTypeDef",
     {
         "RuleName": str,
         "FixedRate": float,
         "ReservoirQuota": int,
         "ReservoirQuotaTTL": datetime,
@@ -547,14 +587,39 @@
         "RuleName": str,
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
 )
 
+_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
+    "_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+    },
+)
+_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
+    "_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
+    {
+        "GroupName": str,
+        "GroupARN": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetServiceGraphRequestGetServiceGraphPaginateTypeDef(
+    _RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
+    _OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetServiceGraphRequestRequestTypeDef = TypedDict(
     "_RequiredGetServiceGraphRequestRequestTypeDef",
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
 )
@@ -564,19 +629,49 @@
         "GroupName": str,
         "GroupARN": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetServiceGraphRequestRequestTypeDef(
     _RequiredGetServiceGraphRequestRequestTypeDef, _OptionalGetServiceGraphRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
+    "_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+    },
+)
+_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
+    "_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
+    {
+        "GroupName": str,
+        "GroupARN": str,
+        "EntitySelectorExpression": str,
+        "Period": int,
+        "ForecastStatistics": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef(
+    _RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
+    _OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTimeSeriesServiceStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTimeSeriesServiceStatisticsRequestRequestTypeDef",
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
 )
@@ -589,39 +684,65 @@
         "Period": int,
         "ForecastStatistics": bool,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetTimeSeriesServiceStatisticsRequestRequestTypeDef(
     _RequiredGetTimeSeriesServiceStatisticsRequestRequestTypeDef,
     _OptionalGetTimeSeriesServiceStatisticsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
+    "_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
+    {
+        "TraceIds": Sequence[str],
+    },
+)
+_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
+    "_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTraceGraphRequestGetTraceGraphPaginateTypeDef(
+    _RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
+    _OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTraceGraphRequestRequestTypeDef = TypedDict(
     "_RequiredGetTraceGraphRequestRequestTypeDef",
     {
         "TraceIds": Sequence[str],
     },
 )
 _OptionalGetTraceGraphRequestRequestTypeDef = TypedDict(
     "_OptionalGetTraceGraphRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetTraceGraphRequestRequestTypeDef(
     _RequiredGetTraceGraphRequestRequestTypeDef, _OptionalGetTraceGraphRequestRequestTypeDef
 ):
     pass
 
+
 SamplingStrategyTypeDef = TypedDict(
     "SamplingStrategyTypeDef",
     {
         "Name": SamplingStrategyNameType,
         "Value": float,
     },
     total=False,
@@ -661,14 +782,22 @@
     "InstanceIdDetailTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
 
+ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef = TypedDict(
+    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourcePoliciesRequestRequestTypeDef = TypedDict(
     "ListResourcePoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
@@ -680,54 +809,90 @@
         "PolicyDocument": str,
         "PolicyRevisionId": str,
         "LastUpdatedTime": datetime,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
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
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_OptionalListTagsForResourceRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
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
 _RequiredPutEncryptionConfigRequestRequestTypeDef = TypedDict(
     "_RequiredPutEncryptionConfigRequestRequestTypeDef",
     {
         "Type": EncryptionTypeType,
     },
 )
 _OptionalPutEncryptionConfigRequestRequestTypeDef = TypedDict(
     "_OptionalPutEncryptionConfigRequestRequestTypeDef",
     {
         "KeyId": str,
     },
     total=False,
 )
 
+
 class PutEncryptionConfigRequestRequestTypeDef(
     _RequiredPutEncryptionConfigRequestRequestTypeDef,
     _OptionalPutEncryptionConfigRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "PolicyName": str,
         "PolicyDocument": str,
     },
 )
@@ -736,19 +901,21 @@
     {
         "PolicyRevisionId": str,
         "BypassPolicyLockoutCheck": bool,
     },
     total=False,
 )
 
+
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
+
 PutTraceSegmentsRequestRequestTypeDef = TypedDict(
     "PutTraceSegmentsRequestRequestTypeDef",
     {
         "TraceSegmentDocuments": Sequence[str],
     },
 )
 
@@ -766,14 +933,25 @@
     "ResourceARNDetailTypeDef",
     {
         "ARN": str,
     },
     total=False,
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
 ResponseTimeRootCauseEntityTypeDef = TypedDict(
     "ResponseTimeRootCauseEntityTypeDef",
     {
         "Name": str,
         "Coverage": float,
         "Remote": bool,
     },
@@ -856,157 +1034,18 @@
         "SegmentsSpilloverCount": int,
         "SegmentsRejectedCount": int,
         "BackendConnectionErrors": BackendConnectionErrorsTypeDef,
     },
     total=False,
 )
 
-class TelemetryRecordTypeDef(_RequiredTelemetryRecordTypeDef, _OptionalTelemetryRecordTypeDef):
-    pass
 
-_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
-    "_RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
-    {
-        "TraceIds": Sequence[str],
-    },
-)
-_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef = TypedDict(
-    "_OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class BatchGetTracesRequestBatchGetTracesPaginateTypeDef(
-    _RequiredBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-    _OptionalBatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-):
-    pass
-
-GetGroupsRequestGetGroupsPaginateTypeDef = TypedDict(
-    "GetGroupsRequestGetGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef = TypedDict(
-    "GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef = TypedDict(
-    "GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
-    "_RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
-    {
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-    },
-)
-_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef = TypedDict(
-    "_OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef",
-    {
-        "GroupName": str,
-        "GroupARN": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetServiceGraphRequestGetServiceGraphPaginateTypeDef(
-    _RequiredGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-    _OptionalGetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-):
-    pass
-
-_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
-    "_RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
-    {
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-    },
-)
-_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef = TypedDict(
-    "_OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef",
-    {
-        "GroupName": str,
-        "GroupARN": str,
-        "EntitySelectorExpression": str,
-        "Period": int,
-        "ForecastStatistics": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef(
-    _RequiredGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-    _OptionalGetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
-    "_RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
-    {
-        "TraceIds": Sequence[str],
-    },
-)
-_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef = TypedDict(
-    "_OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTraceGraphRequestGetTraceGraphPaginateTypeDef(
-    _RequiredGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-    _OptionalGetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-):
+class TelemetryRecordTypeDef(_RequiredTelemetryRecordTypeDef, _OptionalTelemetryRecordTypeDef):
     pass
 
-ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef = TypedDict(
-    "ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
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
 
 GroupSummaryTypeDef = TypedDict(
     "GroupSummaryTypeDef",
     {
         "GroupName": str,
         "GroupARN": str,
         "FilterExpression": str,
@@ -1049,25 +1088,27 @@
         "FilterExpression": str,
         "InsightsConfiguration": InsightsConfigurationTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateGroupRequestRequestTypeDef(
     _RequiredCreateGroupRequestRequestTypeDef, _OptionalCreateGroupRequestRequestTypeDef
 ):
     pass
 
+
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -1085,20 +1126,22 @@
     "_OptionalCreateSamplingRuleRequestRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateSamplingRuleRequestRequestTypeDef(
     _RequiredCreateSamplingRuleRequestRequestTypeDef,
     _OptionalCreateSamplingRuleRequestRequestTypeDef,
 ):
     pass
 
+
 SamplingRuleRecordTypeDef = TypedDict(
     "SamplingRuleRecordTypeDef",
     {
         "SamplingRule": SamplingRuleTypeDef,
         "CreatedAt": datetime,
         "ModifiedAt": datetime,
     },
@@ -1129,23 +1172,23 @@
     total=False,
 )
 
 GetEncryptionConfigResultTypeDef = TypedDict(
     "GetEncryptionConfigResultTypeDef",
     {
         "EncryptionConfig": EncryptionConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutEncryptionConfigResultTypeDef = TypedDict(
     "PutEncryptionConfigResultTypeDef",
     {
         "EncryptionConfig": EncryptionConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ErrorRootCauseEntityTypeDef = TypedDict(
     "ErrorRootCauseEntityTypeDef",
     {
         "Name": str,
@@ -1166,15 +1209,15 @@
 )
 
 GetSamplingStatisticSummariesResultTypeDef = TypedDict(
     "GetSamplingStatisticSummariesResultTypeDef",
     {
         "SamplingStatisticSummaries": List[SamplingStatisticSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSamplingTargetsRequestRequestTypeDef = TypedDict(
     "GetSamplingTargetsRequestRequestTypeDef",
     {
         "SamplingStatisticsDocuments": Sequence[SamplingStatisticsDocumentTypeDef],
@@ -1183,15 +1226,15 @@
 
 GetSamplingTargetsResultTypeDef = TypedDict(
     "GetSamplingTargetsResultTypeDef",
     {
         "SamplingTargetDocuments": List[SamplingTargetDocumentTypeDef],
         "LastRuleModification": datetime,
         "UnprocessedStatistics": List[UnprocessedStatisticsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef = TypedDict(
     "_RequiredGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef",
     {
         "StartTime": Union[datetime, str],
@@ -1201,25 +1244,27 @@
 _OptionalGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef = TypedDict(
     "_OptionalGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef",
     {
         "TimeRangeType": TimeRangeTypeType,
         "Sampling": bool,
         "SamplingStrategy": SamplingStrategyTypeDef,
         "FilterExpression": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class GetTraceSummariesRequestGetTraceSummariesPaginateTypeDef(
     _RequiredGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef,
     _OptionalGetTraceSummariesRequestGetTraceSummariesPaginateTypeDef,
 ):
     pass
 
+
 _RequiredGetTraceSummariesRequestRequestTypeDef = TypedDict(
     "_RequiredGetTraceSummariesRequestRequestTypeDef",
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
 )
@@ -1231,19 +1276,21 @@
         "SamplingStrategy": SamplingStrategyTypeDef,
         "FilterExpression": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetTraceSummariesRequestRequestTypeDef(
     _RequiredGetTraceSummariesRequestRequestTypeDef, _OptionalGetTraceSummariesRequestRequestTypeDef
 ):
     pass
 
+
 InsightImpactGraphServiceTypeDef = TypedDict(
     "InsightImpactGraphServiceTypeDef",
     {
         "ReferenceId": int,
         "Type": str,
         "Name": str,
         "Names": List[str],
@@ -1254,31 +1301,31 @@
 )
 
 ListResourcePoliciesResultTypeDef = TypedDict(
     "ListResourcePoliciesResultTypeDef",
     {
         "ResourcePolicies": List[ResourcePolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourcePolicyResultTypeDef = TypedDict(
     "PutResourcePolicyResultTypeDef",
     {
         "ResourcePolicy": ResourcePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutTraceSegmentsResultTypeDef = TypedDict(
     "PutTraceSegmentsResultTypeDef",
     {
         "UnprocessedTraceSegments": List[UnprocessedTraceSegmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseTimeRootCauseServiceTypeDef = TypedDict(
     "ResponseTimeRootCauseServiceTypeDef",
     {
         "Name": str,
@@ -1372,83 +1419,85 @@
         "EC2InstanceId": str,
         "Hostname": str,
         "ResourceARN": str,
     },
     total=False,
 )
 
+
 class PutTelemetryRecordsRequestRequestTypeDef(
     _RequiredPutTelemetryRecordsRequestRequestTypeDef,
     _OptionalPutTelemetryRecordsRequestRequestTypeDef,
 ):
     pass
 
+
 GetGroupsResultTypeDef = TypedDict(
     "GetGroupsResultTypeDef",
     {
         "Groups": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGroupResultTypeDef = TypedDict(
     "CreateGroupResultTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupResultTypeDef = TypedDict(
     "GetGroupResultTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGroupResultTypeDef = TypedDict(
     "UpdateGroupResultTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSamplingRuleResultTypeDef = TypedDict(
     "CreateSamplingRuleResultTypeDef",
     {
         "SamplingRuleRecord": SamplingRuleRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSamplingRuleResultTypeDef = TypedDict(
     "DeleteSamplingRuleResultTypeDef",
     {
         "SamplingRuleRecord": SamplingRuleRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSamplingRulesResultTypeDef = TypedDict(
     "GetSamplingRulesResultTypeDef",
     {
         "SamplingRuleRecords": List[SamplingRuleRecordTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSamplingRuleResultTypeDef = TypedDict(
     "UpdateSamplingRuleResultTypeDef",
     {
         "SamplingRuleRecord": SamplingRuleRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EdgeTypeDef = TypedDict(
     "EdgeTypeDef",
     {
         "ReferenceId": int,
@@ -1507,15 +1556,15 @@
         "InsightId": str,
         "StartTime": datetime,
         "EndTime": datetime,
         "ServiceGraphStartTime": datetime,
         "ServiceGraphEndTime": datetime,
         "Services": List[InsightImpactGraphServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseTimeRootCauseTypeDef = TypedDict(
     "ResponseTimeRootCauseTypeDef",
     {
         "Services": List[ResponseTimeRootCauseServiceTypeDef],
@@ -1526,41 +1575,41 @@
 
 BatchGetTracesResultTypeDef = TypedDict(
     "BatchGetTracesResultTypeDef",
     {
         "Traces": List[TraceTypeDef],
         "UnprocessedTraceIds": List[str],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightEventsResultTypeDef = TypedDict(
     "GetInsightEventsResultTypeDef",
     {
         "InsightEvents": List[InsightEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightSummariesResultTypeDef = TypedDict(
     "GetInsightSummariesResultTypeDef",
     {
         "InsightSummaries": List[InsightSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightResultTypeDef = TypedDict(
     "GetInsightResultTypeDef",
     {
         "Insight": InsightTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceTypeDef = TypedDict(
     "ServiceTypeDef",
     {
         "ReferenceId": int,
@@ -1582,15 +1631,15 @@
 
 GetTimeSeriesServiceStatisticsResultTypeDef = TypedDict(
     "GetTimeSeriesServiceStatisticsResultTypeDef",
     {
         "TimeSeriesServiceStatistics": List[TimeSeriesServiceStatisticsTypeDef],
         "ContainsOldGroupVersions": bool,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ErrorRootCauseTypeDef = TypedDict(
     "ErrorRootCauseTypeDef",
     {
         "Services": List[ErrorRootCauseServiceTypeDef],
@@ -1612,24 +1661,24 @@
     "GetServiceGraphResultTypeDef",
     {
         "StartTime": datetime,
         "EndTime": datetime,
         "Services": List[ServiceTypeDef],
         "ContainsOldGroupVersions": bool,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTraceGraphResultTypeDef = TypedDict(
     "GetTraceGraphResultTypeDef",
     {
         "Services": List[ServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TraceSummaryTypeDef = TypedDict(
     "TraceSummaryTypeDef",
     {
         "Id": str,
@@ -1659,10 +1708,10 @@
 GetTraceSummariesResultTypeDef = TypedDict(
     "GetTraceSummariesResultTypeDef",
     {
         "TraceSummaries": List[TraceSummaryTypeDef],
         "ApproximateTime": datetime,
         "TracesProcessedCount": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/PKG-INFO` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-xray
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.XRay 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.XRay 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-xray"></a>
 
 # types-aiobotocore-xray
 
 [![PyPI - types-aiobotocore-xray](https://img.shields.io/pypi/v/types-aiobotocore-xray.svg?color=blue)](https://pypi.org/project/types-aiobotocore-xray)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-xray.svg?color=blue)](https://pypi.org/project/types-aiobotocore-xray)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-xray?color=blue)](https://pypistats.org/packages/types-aiobotocore-xray)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.XRay 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay)
+[aiobotocore.XRay 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/xray.html#XRay)
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
 [types-aiobotocore-xray docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_xray/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,74 +366,74 @@
 ```python
 from types_aiobotocore_xray.type_defs import (
     AliasTypeDef,
     AnnotationValueTypeDef,
     ServiceIdTypeDef,
     AvailabilityZoneDetailTypeDef,
     BackendConnectionErrorsTypeDef,
-    PaginatorConfigTypeDef,
+    BatchGetTracesRequestBatchGetTracesPaginateTypeDef,
     BatchGetTracesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     InsightsConfigurationTypeDef,
     TagTypeDef,
     SamplingRuleTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeleteSamplingRuleRequestRequestTypeDef,
     ErrorStatisticsTypeDef,
     FaultStatisticsTypeDef,
     HistogramEntryTypeDef,
     EncryptionConfigTypeDef,
     RootCauseExceptionTypeDef,
     ForecastStatisticsTypeDef,
     GetGroupRequestRequestTypeDef,
+    GetGroupsRequestGetGroupsPaginateTypeDef,
     GetGroupsRequestRequestTypeDef,
     GetInsightEventsRequestRequestTypeDef,
     GetInsightImpactGraphRequestRequestTypeDef,
     GetInsightRequestRequestTypeDef,
     GetInsightSummariesRequestRequestTypeDef,
+    GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef,
     GetSamplingRulesRequestRequestTypeDef,
+    GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef,
     GetSamplingStatisticSummariesRequestRequestTypeDef,
     SamplingStatisticSummaryTypeDef,
     SamplingStatisticsDocumentTypeDef,
     SamplingTargetDocumentTypeDef,
     UnprocessedStatisticsTypeDef,
+    GetServiceGraphRequestGetServiceGraphPaginateTypeDef,
     GetServiceGraphRequestRequestTypeDef,
+    GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
     GetTimeSeriesServiceStatisticsRequestRequestTypeDef,
+    GetTraceGraphRequestGetTraceGraphPaginateTypeDef,
     GetTraceGraphRequestRequestTypeDef,
     SamplingStrategyTypeDef,
     HttpTypeDef,
     RequestImpactStatisticsTypeDef,
     InsightImpactGraphEdgeTypeDef,
     InstanceIdDetailTypeDef,
+    ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef,
     ListResourcePoliciesRequestRequestTypeDef,
     ResourcePolicyTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutEncryptionConfigRequestRequestTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
     PutTraceSegmentsRequestRequestTypeDef,
     UnprocessedTraceSegmentTypeDef,
     ResourceARNDetailTypeDef,
+    ResponseMetadataTypeDef,
     ResponseTimeRootCauseEntityTypeDef,
     SamplingRuleUpdateTypeDef,
     SegmentTypeDef,
     UntagResourceRequestRequestTypeDef,
     AnomalousServiceTypeDef,
     TraceUserTypeDef,
     ValueWithServiceIdsTypeDef,
     TelemetryRecordTypeDef,
-    BatchGetTracesRequestBatchGetTracesPaginateTypeDef,
-    GetGroupsRequestGetGroupsPaginateTypeDef,
-    GetSamplingRulesRequestGetSamplingRulesPaginateTypeDef,
-    GetSamplingStatisticSummariesRequestGetSamplingStatisticSummariesPaginateTypeDef,
-    GetServiceGraphRequestGetServiceGraphPaginateTypeDef,
-    GetTimeSeriesServiceStatisticsRequestGetTimeSeriesServiceStatisticsPaginateTypeDef,
-    GetTraceGraphRequestGetTraceGraphPaginateTypeDef,
-    ListResourcePoliciesRequestListResourcePoliciesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     GroupSummaryTypeDef,
     GroupTypeDef,
     UpdateGroupRequestRequestTypeDef,
     CreateGroupRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSamplingRuleRequestRequestTypeDef,
@@ -496,43 +496,43 @@
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

### Comparing `types-aiobotocore-xray-2.5.0.post1/types_aiobotocore_xray.egg-info/SOURCES.txt` & `types-aiobotocore-xray-2.5.1/types_aiobotocore_xray.egg-info/SOURCES.txt`

 * *Files identical despite different names*

