# Comparing `tmp/types-aiobotocore-lookoutmetrics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lookoutmetrics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lookoutmetrics-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-lookoutmetrics-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1.tar` & `types-aiobotocore-lookoutmetrics-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.127391 types-aiobotocore-lookoutmetrics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16767 2023-03-11 12:26:56.127391 types-aiobotocore-lookoutmetrics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15168 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.127391 types-aiobotocore-lookoutmetrics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.127391 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/
--rw-r--r--   0 runner    (1001) docker     (123)      498 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24304 2023-03-11 12:17:52.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24266 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9407 2023-03-11 12:17:52.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9405 2023-03-11 12:17:52.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    36523 2023-03-11 12:17:52.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    36490 2023-03-11 12:17:52.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:51.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.127391 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16767 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      853 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:55.000000 types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.226170 types-aiobotocore-lookoutmetrics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16766 2023-06-28 01:43:47.226170 types-aiobotocore-lookoutmetrics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15173 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.226170 types-aiobotocore-lookoutmetrics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.226170 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/
+-rw-r--r--   0 runner    (1001) docker     (123)      498 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24304 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24266 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9616 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9614 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    36567 2023-06-28 01:34:34.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36534 2023-06-28 01:34:34.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:33.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.226170 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16766 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      853 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:47.000000 types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/LICENSE` & `types-aiobotocore-lookoutmetrics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lookoutmetrics-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lookoutmetrics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LookoutMetrics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LookoutMetrics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lookoutmetrics"></a>
 
 # types-aiobotocore-lookoutmetrics
 
 [![PyPI - types-aiobotocore-lookoutmetrics](https://img.shields.io/pypi/v/types-aiobotocore-lookoutmetrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutmetrics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutmetrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutmetrics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutmetrics?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutmetrics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutMetrics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
+[aiobotocore.LookoutMetrics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
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
 [types-aiobotocore-lookoutmetrics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,17 +320,19 @@
     AnomalyGroupTimeSeriesFeedbackTypeDef,
     AnomalyGroupTimeSeriesTypeDef,
     AppFlowConfigTypeDef,
     BackTestConfigurationTypeDef,
     AttributeValueTypeDef,
     AutoDetectionS3SourceConfigTypeDef,
     BackTestAnomalyDetectorRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAlertResponseTypeDef,
+    CreateAnomalyDetectorResponseTypeDef,
     MetricTypeDef,
     TimestampColumnTypeDef,
+    CreateMetricSetResponseTypeDef,
     CsvFormatDescriptorTypeDef,
     DataQualityMetricTypeDef,
     DeactivateAnomalyDetectorRequestRequestTypeDef,
     DeleteAlertRequestRequestTypeDef,
     DeleteAnomalyDetectorRequestRequestTypeDef,
     DescribeAlertRequestRequestTypeDef,
     DescribeAnomalyDetectionExecutionsRequestRequestTypeDef,
@@ -340,48 +342,46 @@
     DimensionValueContributionTypeDef,
     DimensionNameValueTypeDef,
     JsonFormatDescriptorTypeDef,
     FilterTypeDef,
     GetAnomalyGroupRequestRequestTypeDef,
     GetDataQualityMetricsRequestRequestTypeDef,
     TimeSeriesFeedbackTypeDef,
+    GetSampleDataResponseTypeDef,
     InterMetricImpactDetailsTypeDef,
     ListAlertsRequestRequestTypeDef,
     ListAnomalyDetectorsRequestRequestTypeDef,
     ListAnomalyGroupRelatedMetricsRequestRequestTypeDef,
     ListAnomalyGroupSummariesRequestRequestTypeDef,
     ListAnomalyGroupTimeSeriesRequestRequestTypeDef,
     ListMetricSetsRequestRequestTypeDef,
     MetricSetSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     VpcConfigurationTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAlertResponseTypeDef,
+    UpdateAnomalyDetectorResponseTypeDef,
+    UpdateMetricSetResponseTypeDef,
     ActionTypeDef,
     AlertFiltersTypeDef,
+    ListAlertsResponseTypeDef,
+    DescribeAnomalyDetectorResponseTypeDef,
     CreateAnomalyDetectorRequestRequestTypeDef,
     UpdateAnomalyDetectorRequestRequestTypeDef,
+    ListAnomalyDetectorsResponseTypeDef,
     AnomalyGroupStatisticsTypeDef,
     PutFeedbackRequestRequestTypeDef,
     GetFeedbackRequestRequestTypeDef,
     AthenaSourceConfigTypeDef,
     CloudWatchConfigTypeDef,
     DetectedFieldTypeDef,
     AutoDetectionMetricSourceTypeDef,
-    CreateAlertResponseTypeDef,
-    CreateAnomalyDetectorResponseTypeDef,
-    CreateMetricSetResponseTypeDef,
-    DescribeAnomalyDetectorResponseTypeDef,
-    GetSampleDataResponseTypeDef,
-    ListAlertsResponseTypeDef,
-    ListAnomalyDetectorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateAlertResponseTypeDef,
-    UpdateAnomalyDetectorResponseTypeDef,
-    UpdateMetricSetResponseTypeDef,
     MetricSetDataQualityMetricTypeDef,
     DescribeAnomalyDetectionExecutionsResponseTypeDef,
     DimensionContributionTypeDef,
     TimeSeriesTypeDef,
     FileFormatDescriptorTypeDef,
     MetricSetDimensionFilterTypeDef,
     GetFeedbackResponseTypeDef,
@@ -426,43 +426,43 @@
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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/README.md` & `types-aiobotocore-lookoutmetrics-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lookoutmetrics"></a>
 
 # types-aiobotocore-lookoutmetrics
 
 [![PyPI - types-aiobotocore-lookoutmetrics](https://img.shields.io/pypi/v/types-aiobotocore-lookoutmetrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutmetrics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutmetrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutmetrics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutmetrics?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutmetrics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutMetrics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
+[aiobotocore.LookoutMetrics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
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
 [types-aiobotocore-lookoutmetrics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,17 +287,19 @@
     AnomalyGroupTimeSeriesFeedbackTypeDef,
     AnomalyGroupTimeSeriesTypeDef,
     AppFlowConfigTypeDef,
     BackTestConfigurationTypeDef,
     AttributeValueTypeDef,
     AutoDetectionS3SourceConfigTypeDef,
     BackTestAnomalyDetectorRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAlertResponseTypeDef,
+    CreateAnomalyDetectorResponseTypeDef,
     MetricTypeDef,
     TimestampColumnTypeDef,
+    CreateMetricSetResponseTypeDef,
     CsvFormatDescriptorTypeDef,
     DataQualityMetricTypeDef,
     DeactivateAnomalyDetectorRequestRequestTypeDef,
     DeleteAlertRequestRequestTypeDef,
     DeleteAnomalyDetectorRequestRequestTypeDef,
     DescribeAlertRequestRequestTypeDef,
     DescribeAnomalyDetectionExecutionsRequestRequestTypeDef,
@@ -307,48 +309,46 @@
     DimensionValueContributionTypeDef,
     DimensionNameValueTypeDef,
     JsonFormatDescriptorTypeDef,
     FilterTypeDef,
     GetAnomalyGroupRequestRequestTypeDef,
     GetDataQualityMetricsRequestRequestTypeDef,
     TimeSeriesFeedbackTypeDef,
+    GetSampleDataResponseTypeDef,
     InterMetricImpactDetailsTypeDef,
     ListAlertsRequestRequestTypeDef,
     ListAnomalyDetectorsRequestRequestTypeDef,
     ListAnomalyGroupRelatedMetricsRequestRequestTypeDef,
     ListAnomalyGroupSummariesRequestRequestTypeDef,
     ListAnomalyGroupTimeSeriesRequestRequestTypeDef,
     ListMetricSetsRequestRequestTypeDef,
     MetricSetSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     VpcConfigurationTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAlertResponseTypeDef,
+    UpdateAnomalyDetectorResponseTypeDef,
+    UpdateMetricSetResponseTypeDef,
     ActionTypeDef,
     AlertFiltersTypeDef,
+    ListAlertsResponseTypeDef,
+    DescribeAnomalyDetectorResponseTypeDef,
     CreateAnomalyDetectorRequestRequestTypeDef,
     UpdateAnomalyDetectorRequestRequestTypeDef,
+    ListAnomalyDetectorsResponseTypeDef,
     AnomalyGroupStatisticsTypeDef,
     PutFeedbackRequestRequestTypeDef,
     GetFeedbackRequestRequestTypeDef,
     AthenaSourceConfigTypeDef,
     CloudWatchConfigTypeDef,
     DetectedFieldTypeDef,
     AutoDetectionMetricSourceTypeDef,
-    CreateAlertResponseTypeDef,
-    CreateAnomalyDetectorResponseTypeDef,
-    CreateMetricSetResponseTypeDef,
-    DescribeAnomalyDetectorResponseTypeDef,
-    GetSampleDataResponseTypeDef,
-    ListAlertsResponseTypeDef,
-    ListAnomalyDetectorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateAlertResponseTypeDef,
-    UpdateAnomalyDetectorResponseTypeDef,
-    UpdateMetricSetResponseTypeDef,
     MetricSetDataQualityMetricTypeDef,
     DescribeAnomalyDetectionExecutionsResponseTypeDef,
     DimensionContributionTypeDef,
     TimeSeriesTypeDef,
     FileFormatDescriptorTypeDef,
     MetricSetDimensionFilterTypeDef,
     GetFeedbackResponseTypeDef,
@@ -393,43 +393,43 @@
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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/setup.py` & `types-aiobotocore-lookoutmetrics-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lookoutmetrics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lookoutmetrics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lookoutmetrics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LookoutMetrics 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LookoutMetrics 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/"
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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/__main__.py` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LookoutMetrics 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LookoutMetrics 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics\nOther"
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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/client.py` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/client.pyi` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/literals.py` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -141,14 +141,15 @@
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
@@ -227,14 +228,15 @@
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
@@ -245,14 +247,15 @@
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
@@ -288,14 +291,15 @@
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
@@ -314,16 +318,19 @@
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
@@ -407,15 +414,17 @@
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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/literals.pyi` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/literals.pyi`

 * *Files 3% similar despite different names*

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
```

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/type_defs.py` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -55,17 +55,19 @@
     "AnomalyGroupTimeSeriesFeedbackTypeDef",
     "AnomalyGroupTimeSeriesTypeDef",
     "AppFlowConfigTypeDef",
     "BackTestConfigurationTypeDef",
     "AttributeValueTypeDef",
     "AutoDetectionS3SourceConfigTypeDef",
     "BackTestAnomalyDetectorRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAlertResponseTypeDef",
+    "CreateAnomalyDetectorResponseTypeDef",
     "MetricTypeDef",
     "TimestampColumnTypeDef",
+    "CreateMetricSetResponseTypeDef",
     "CsvFormatDescriptorTypeDef",
     "DataQualityMetricTypeDef",
     "DeactivateAnomalyDetectorRequestRequestTypeDef",
     "DeleteAlertRequestRequestTypeDef",
     "DeleteAnomalyDetectorRequestRequestTypeDef",
     "DescribeAlertRequestRequestTypeDef",
     "DescribeAnomalyDetectionExecutionsRequestRequestTypeDef",
@@ -75,48 +77,46 @@
     "DimensionValueContributionTypeDef",
     "DimensionNameValueTypeDef",
     "JsonFormatDescriptorTypeDef",
     "FilterTypeDef",
     "GetAnomalyGroupRequestRequestTypeDef",
     "GetDataQualityMetricsRequestRequestTypeDef",
     "TimeSeriesFeedbackTypeDef",
+    "GetSampleDataResponseTypeDef",
     "InterMetricImpactDetailsTypeDef",
     "ListAlertsRequestRequestTypeDef",
     "ListAnomalyDetectorsRequestRequestTypeDef",
     "ListAnomalyGroupRelatedMetricsRequestRequestTypeDef",
     "ListAnomalyGroupSummariesRequestRequestTypeDef",
     "ListAnomalyGroupTimeSeriesRequestRequestTypeDef",
     "ListMetricSetsRequestRequestTypeDef",
     "MetricSetSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "VpcConfigurationTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAlertResponseTypeDef",
+    "UpdateAnomalyDetectorResponseTypeDef",
+    "UpdateMetricSetResponseTypeDef",
     "ActionTypeDef",
     "AlertFiltersTypeDef",
+    "ListAlertsResponseTypeDef",
+    "DescribeAnomalyDetectorResponseTypeDef",
     "CreateAnomalyDetectorRequestRequestTypeDef",
     "UpdateAnomalyDetectorRequestRequestTypeDef",
+    "ListAnomalyDetectorsResponseTypeDef",
     "AnomalyGroupStatisticsTypeDef",
     "PutFeedbackRequestRequestTypeDef",
     "GetFeedbackRequestRequestTypeDef",
     "AthenaSourceConfigTypeDef",
     "CloudWatchConfigTypeDef",
     "DetectedFieldTypeDef",
     "AutoDetectionMetricSourceTypeDef",
-    "CreateAlertResponseTypeDef",
-    "CreateAnomalyDetectorResponseTypeDef",
-    "CreateMetricSetResponseTypeDef",
-    "DescribeAnomalyDetectorResponseTypeDef",
-    "GetSampleDataResponseTypeDef",
-    "ListAlertsResponseTypeDef",
-    "ListAnomalyDetectorsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateAlertResponseTypeDef",
-    "UpdateAnomalyDetectorResponseTypeDef",
-    "UpdateMetricSetResponseTypeDef",
     "MetricSetDataQualityMetricTypeDef",
     "DescribeAnomalyDetectionExecutionsResponseTypeDef",
     "DimensionContributionTypeDef",
     "TimeSeriesTypeDef",
     "FileFormatDescriptorTypeDef",
     "MetricSetDimensionFilterTypeDef",
     "GetFeedbackResponseTypeDef",
@@ -335,22 +335,27 @@
 BackTestAnomalyDetectorRequestRequestTypeDef = TypedDict(
     "BackTestAnomalyDetectorRequestRequestTypeDef",
     {
         "AnomalyDetectorArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAlertResponseTypeDef = TypedDict(
+    "CreateAlertResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AlertArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAnomalyDetectorResponseTypeDef = TypedDict(
+    "CreateAnomalyDetectorResponseTypeDef",
+    {
+        "AnomalyDetectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricTypeDef = TypedDict(
     "_RequiredMetricTypeDef",
     {
         "MetricName": str,
@@ -375,14 +380,22 @@
     {
         "ColumnName": str,
         "ColumnFormat": str,
     },
     total=False,
 )
 
+CreateMetricSetResponseTypeDef = TypedDict(
+    "CreateMetricSetResponseTypeDef",
+    {
+        "MetricSetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CsvFormatDescriptorTypeDef = TypedDict(
     "CsvFormatDescriptorTypeDef",
     {
         "FileCompression": CSVFileCompressionType,
         "Charset": str,
         "ContainsHeader": bool,
         "Delimiter": str,
@@ -549,14 +562,23 @@
     {
         "TimeSeriesId": str,
         "IsAnomaly": bool,
     },
     total=False,
 )
 
+GetSampleDataResponseTypeDef = TypedDict(
+    "GetSampleDataResponseTypeDef",
+    {
+        "HeaderValues": List[str],
+        "SampleRows": List[List[str]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InterMetricImpactDetailsTypeDef = TypedDict(
     "InterMetricImpactDetailsTypeDef",
     {
         "MetricName": str,
         "AnomalyGroupId": str,
         "RelationshipType": RelationshipTypeType,
         "ContributionPercentage": float,
@@ -684,22 +706,41 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VpcConfigurationTypeDef = TypedDict(
     "VpcConfigurationTypeDef",
     {
         "SubnetIdList": Sequence[str],
         "SecurityGroupIdList": Sequence[str],
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -708,14 +749,38 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateAlertResponseTypeDef = TypedDict(
+    "UpdateAlertResponseTypeDef",
+    {
+        "AlertArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateAnomalyDetectorResponseTypeDef = TypedDict(
+    "UpdateAnomalyDetectorResponseTypeDef",
+    {
+        "AnomalyDetectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateMetricSetResponseTypeDef = TypedDict(
+    "UpdateMetricSetResponseTypeDef",
+    {
+        "MetricSetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActionTypeDef = TypedDict(
     "ActionTypeDef",
     {
         "SNSConfiguration": SNSConfigurationTypeDef,
         "LambdaConfiguration": LambdaConfigurationTypeDef,
     },
     total=False,
@@ -726,14 +791,40 @@
     {
         "MetricList": Sequence[str],
         "DimensionFilterList": Sequence[DimensionFilterTypeDef],
     },
     total=False,
 )
 
+ListAlertsResponseTypeDef = TypedDict(
+    "ListAlertsResponseTypeDef",
+    {
+        "AlertSummaryList": List[AlertSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAnomalyDetectorResponseTypeDef = TypedDict(
+    "DescribeAnomalyDetectorResponseTypeDef",
+    {
+        "AnomalyDetectorArn": str,
+        "AnomalyDetectorName": str,
+        "AnomalyDetectorDescription": str,
+        "AnomalyDetectorConfig": AnomalyDetectorConfigSummaryTypeDef,
+        "CreationTime": datetime,
+        "LastModificationTime": datetime,
+        "Status": AnomalyDetectorStatusType,
+        "FailureReason": str,
+        "KmsKeyArn": str,
+        "FailureType": AnomalyDetectorFailureTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateAnomalyDetectorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAnomalyDetectorRequestRequestTypeDef",
     {
         "AnomalyDetectorName": str,
         "AnomalyDetectorConfig": AnomalyDetectorConfigTypeDef,
     },
 )
@@ -775,14 +866,23 @@
 class UpdateAnomalyDetectorRequestRequestTypeDef(
     _RequiredUpdateAnomalyDetectorRequestRequestTypeDef,
     _OptionalUpdateAnomalyDetectorRequestRequestTypeDef,
 ):
     pass
 
 
+ListAnomalyDetectorsResponseTypeDef = TypedDict(
+    "ListAnomalyDetectorsResponseTypeDef",
+    {
+        "AnomalyDetectorSummaryList": List[AnomalyDetectorSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AnomalyGroupStatisticsTypeDef = TypedDict(
     "AnomalyGroupStatisticsTypeDef",
     {
         "EvaluationStartDate": str,
         "TotalCount": int,
         "ItemizedMetricStatsList": List[ItemizedMetricStatsTypeDef],
     },
@@ -857,129 +957,29 @@
     "AutoDetectionMetricSourceTypeDef",
     {
         "S3SourceConfig": AutoDetectionS3SourceConfigTypeDef,
     },
     total=False,
 )
 
-CreateAlertResponseTypeDef = TypedDict(
-    "CreateAlertResponseTypeDef",
-    {
-        "AlertArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAnomalyDetectorResponseTypeDef = TypedDict(
-    "CreateAnomalyDetectorResponseTypeDef",
-    {
-        "AnomalyDetectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMetricSetResponseTypeDef = TypedDict(
-    "CreateMetricSetResponseTypeDef",
-    {
-        "MetricSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAnomalyDetectorResponseTypeDef = TypedDict(
-    "DescribeAnomalyDetectorResponseTypeDef",
-    {
-        "AnomalyDetectorArn": str,
-        "AnomalyDetectorName": str,
-        "AnomalyDetectorDescription": str,
-        "AnomalyDetectorConfig": AnomalyDetectorConfigSummaryTypeDef,
-        "CreationTime": datetime,
-        "LastModificationTime": datetime,
-        "Status": AnomalyDetectorStatusType,
-        "FailureReason": str,
-        "KmsKeyArn": str,
-        "FailureType": AnomalyDetectorFailureTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSampleDataResponseTypeDef = TypedDict(
-    "GetSampleDataResponseTypeDef",
-    {
-        "HeaderValues": List[str],
-        "SampleRows": List[List[str]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlertsResponseTypeDef = TypedDict(
-    "ListAlertsResponseTypeDef",
-    {
-        "AlertSummaryList": List[AlertSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAnomalyDetectorsResponseTypeDef = TypedDict(
-    "ListAnomalyDetectorsResponseTypeDef",
-    {
-        "AnomalyDetectorSummaryList": List[AnomalyDetectorSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAlertResponseTypeDef = TypedDict(
-    "UpdateAlertResponseTypeDef",
-    {
-        "AlertArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAnomalyDetectorResponseTypeDef = TypedDict(
-    "UpdateAnomalyDetectorResponseTypeDef",
-    {
-        "AnomalyDetectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMetricSetResponseTypeDef = TypedDict(
-    "UpdateMetricSetResponseTypeDef",
-    {
-        "MetricSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 MetricSetDataQualityMetricTypeDef = TypedDict(
     "MetricSetDataQualityMetricTypeDef",
     {
         "MetricSetArn": str,
         "DataQualityMetricList": List[DataQualityMetricTypeDef],
     },
     total=False,
 )
 
 DescribeAnomalyDetectionExecutionsResponseTypeDef = TypedDict(
     "DescribeAnomalyDetectionExecutionsResponseTypeDef",
     {
         "ExecutionList": List[ExecutionStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DimensionContributionTypeDef = TypedDict(
     "DimensionContributionTypeDef",
     {
         "DimensionName": str,
@@ -1016,33 +1016,33 @@
 )
 
 GetFeedbackResponseTypeDef = TypedDict(
     "GetFeedbackResponseTypeDef",
     {
         "AnomalyGroupTimeSeriesFeedback": List[TimeSeriesFeedbackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAnomalyGroupRelatedMetricsResponseTypeDef = TypedDict(
     "ListAnomalyGroupRelatedMetricsResponseTypeDef",
     {
         "InterMetricImpactList": List[InterMetricImpactDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMetricSetsResponseTypeDef = TypedDict(
     "ListMetricSetsResponseTypeDef",
     {
         "MetricSetSummaryList": List[MetricSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RDSSourceConfigTypeDef = TypedDict(
     "RDSSourceConfigTypeDef",
     {
         "DBInstanceIdentifier": str,
@@ -1142,15 +1142,15 @@
 
 ListAnomalyGroupSummariesResponseTypeDef = TypedDict(
     "ListAnomalyGroupSummariesResponseTypeDef",
     {
         "AnomalyGroupSummaryList": List[AnomalyGroupSummaryTypeDef],
         "AnomalyGroupStatistics": AnomalyGroupStatisticsTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectedCsvFormatDescriptorTypeDef = TypedDict(
     "DetectedCsvFormatDescriptorTypeDef",
     {
         "FileCompression": DetectedFieldTypeDef,
@@ -1201,15 +1201,15 @@
     "ListAnomalyGroupTimeSeriesResponseTypeDef",
     {
         "AnomalyGroupId": str,
         "MetricName": str,
         "TimestampList": List[str],
         "NextToken": str,
         "TimeSeriesList": List[TimeSeriesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 S3SourceConfigTypeDef = TypedDict(
     "S3SourceConfigTypeDef",
     {
         "RoleArn": str,
@@ -1243,15 +1243,15 @@
     pass
 
 
 DescribeAlertResponseTypeDef = TypedDict(
     "DescribeAlertResponseTypeDef",
     {
         "Alert": AlertTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectedFileFormatDescriptorTypeDef = TypedDict(
     "DetectedFileFormatDescriptorTypeDef",
     {
         "CsvFormatDescriptor": DetectedCsvFormatDescriptorTypeDef,
@@ -1260,15 +1260,15 @@
     total=False,
 )
 
 GetDataQualityMetricsResponseTypeDef = TypedDict(
     "GetDataQualityMetricsResponseTypeDef",
     {
         "AnomalyDetectorDataQualityMetricList": List[AnomalyDetectorDataQualityMetricTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricLevelImpactTypeDef = TypedDict(
     "MetricLevelImpactTypeDef",
     {
         "MetricName": str,
@@ -1364,15 +1364,15 @@
         "MetricList": List[MetricTypeDef],
         "TimestampColumn": TimestampColumnTypeDef,
         "DimensionList": List[str],
         "MetricSetFrequency": FrequencyType,
         "Timezone": str,
         "MetricSource": MetricSourceTypeDef,
         "DimensionFilterList": List[MetricSetDimensionFilterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateMetricSetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateMetricSetRequestRequestTypeDef",
     {
         "MetricSetArn": str,
@@ -1408,15 +1408,15 @@
     total=False,
 )
 
 GetAnomalyGroupResponseTypeDef = TypedDict(
     "GetAnomalyGroupResponseTypeDef",
     {
         "AnomalyGroup": AnomalyGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectedMetricSetConfigTypeDef = TypedDict(
     "DetectedMetricSetConfigTypeDef",
     {
         "Offset": DetectedFieldTypeDef,
@@ -1426,10 +1426,10 @@
     total=False,
 )
 
 DetectMetricSetConfigResponseTypeDef = TypedDict(
     "DetectMetricSetConfigResponseTypeDef",
     {
         "DetectedMetricSetConfig": DetectedMetricSetConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics/type_defs.pyi` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -54,17 +54,19 @@
     "AnomalyGroupTimeSeriesFeedbackTypeDef",
     "AnomalyGroupTimeSeriesTypeDef",
     "AppFlowConfigTypeDef",
     "BackTestConfigurationTypeDef",
     "AttributeValueTypeDef",
     "AutoDetectionS3SourceConfigTypeDef",
     "BackTestAnomalyDetectorRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAlertResponseTypeDef",
+    "CreateAnomalyDetectorResponseTypeDef",
     "MetricTypeDef",
     "TimestampColumnTypeDef",
+    "CreateMetricSetResponseTypeDef",
     "CsvFormatDescriptorTypeDef",
     "DataQualityMetricTypeDef",
     "DeactivateAnomalyDetectorRequestRequestTypeDef",
     "DeleteAlertRequestRequestTypeDef",
     "DeleteAnomalyDetectorRequestRequestTypeDef",
     "DescribeAlertRequestRequestTypeDef",
     "DescribeAnomalyDetectionExecutionsRequestRequestTypeDef",
@@ -74,48 +76,46 @@
     "DimensionValueContributionTypeDef",
     "DimensionNameValueTypeDef",
     "JsonFormatDescriptorTypeDef",
     "FilterTypeDef",
     "GetAnomalyGroupRequestRequestTypeDef",
     "GetDataQualityMetricsRequestRequestTypeDef",
     "TimeSeriesFeedbackTypeDef",
+    "GetSampleDataResponseTypeDef",
     "InterMetricImpactDetailsTypeDef",
     "ListAlertsRequestRequestTypeDef",
     "ListAnomalyDetectorsRequestRequestTypeDef",
     "ListAnomalyGroupRelatedMetricsRequestRequestTypeDef",
     "ListAnomalyGroupSummariesRequestRequestTypeDef",
     "ListAnomalyGroupTimeSeriesRequestRequestTypeDef",
     "ListMetricSetsRequestRequestTypeDef",
     "MetricSetSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "VpcConfigurationTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAlertResponseTypeDef",
+    "UpdateAnomalyDetectorResponseTypeDef",
+    "UpdateMetricSetResponseTypeDef",
     "ActionTypeDef",
     "AlertFiltersTypeDef",
+    "ListAlertsResponseTypeDef",
+    "DescribeAnomalyDetectorResponseTypeDef",
     "CreateAnomalyDetectorRequestRequestTypeDef",
     "UpdateAnomalyDetectorRequestRequestTypeDef",
+    "ListAnomalyDetectorsResponseTypeDef",
     "AnomalyGroupStatisticsTypeDef",
     "PutFeedbackRequestRequestTypeDef",
     "GetFeedbackRequestRequestTypeDef",
     "AthenaSourceConfigTypeDef",
     "CloudWatchConfigTypeDef",
     "DetectedFieldTypeDef",
     "AutoDetectionMetricSourceTypeDef",
-    "CreateAlertResponseTypeDef",
-    "CreateAnomalyDetectorResponseTypeDef",
-    "CreateMetricSetResponseTypeDef",
-    "DescribeAnomalyDetectorResponseTypeDef",
-    "GetSampleDataResponseTypeDef",
-    "ListAlertsResponseTypeDef",
-    "ListAnomalyDetectorsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateAlertResponseTypeDef",
-    "UpdateAnomalyDetectorResponseTypeDef",
-    "UpdateMetricSetResponseTypeDef",
     "MetricSetDataQualityMetricTypeDef",
     "DescribeAnomalyDetectionExecutionsResponseTypeDef",
     "DimensionContributionTypeDef",
     "TimeSeriesTypeDef",
     "FileFormatDescriptorTypeDef",
     "MetricSetDimensionFilterTypeDef",
     "GetFeedbackResponseTypeDef",
@@ -330,22 +330,27 @@
 BackTestAnomalyDetectorRequestRequestTypeDef = TypedDict(
     "BackTestAnomalyDetectorRequestRequestTypeDef",
     {
         "AnomalyDetectorArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAlertResponseTypeDef = TypedDict(
+    "CreateAlertResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AlertArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAnomalyDetectorResponseTypeDef = TypedDict(
+    "CreateAnomalyDetectorResponseTypeDef",
+    {
+        "AnomalyDetectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricTypeDef = TypedDict(
     "_RequiredMetricTypeDef",
     {
         "MetricName": str,
@@ -368,14 +373,22 @@
     {
         "ColumnName": str,
         "ColumnFormat": str,
     },
     total=False,
 )
 
+CreateMetricSetResponseTypeDef = TypedDict(
+    "CreateMetricSetResponseTypeDef",
+    {
+        "MetricSetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CsvFormatDescriptorTypeDef = TypedDict(
     "CsvFormatDescriptorTypeDef",
     {
         "FileCompression": CSVFileCompressionType,
         "Charset": str,
         "ContainsHeader": bool,
         "Delimiter": str,
@@ -538,14 +551,23 @@
     {
         "TimeSeriesId": str,
         "IsAnomaly": bool,
     },
     total=False,
 )
 
+GetSampleDataResponseTypeDef = TypedDict(
+    "GetSampleDataResponseTypeDef",
+    {
+        "HeaderValues": List[str],
+        "SampleRows": List[List[str]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InterMetricImpactDetailsTypeDef = TypedDict(
     "InterMetricImpactDetailsTypeDef",
     {
         "MetricName": str,
         "AnomalyGroupId": str,
         "RelationshipType": RelationshipTypeType,
         "ContributionPercentage": float,
@@ -667,22 +689,41 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VpcConfigurationTypeDef = TypedDict(
     "VpcConfigurationTypeDef",
     {
         "SubnetIdList": Sequence[str],
         "SecurityGroupIdList": Sequence[str],
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -691,14 +732,38 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateAlertResponseTypeDef = TypedDict(
+    "UpdateAlertResponseTypeDef",
+    {
+        "AlertArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateAnomalyDetectorResponseTypeDef = TypedDict(
+    "UpdateAnomalyDetectorResponseTypeDef",
+    {
+        "AnomalyDetectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateMetricSetResponseTypeDef = TypedDict(
+    "UpdateMetricSetResponseTypeDef",
+    {
+        "MetricSetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActionTypeDef = TypedDict(
     "ActionTypeDef",
     {
         "SNSConfiguration": SNSConfigurationTypeDef,
         "LambdaConfiguration": LambdaConfigurationTypeDef,
     },
     total=False,
@@ -709,14 +774,40 @@
     {
         "MetricList": Sequence[str],
         "DimensionFilterList": Sequence[DimensionFilterTypeDef],
     },
     total=False,
 )
 
+ListAlertsResponseTypeDef = TypedDict(
+    "ListAlertsResponseTypeDef",
+    {
+        "AlertSummaryList": List[AlertSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAnomalyDetectorResponseTypeDef = TypedDict(
+    "DescribeAnomalyDetectorResponseTypeDef",
+    {
+        "AnomalyDetectorArn": str,
+        "AnomalyDetectorName": str,
+        "AnomalyDetectorDescription": str,
+        "AnomalyDetectorConfig": AnomalyDetectorConfigSummaryTypeDef,
+        "CreationTime": datetime,
+        "LastModificationTime": datetime,
+        "Status": AnomalyDetectorStatusType,
+        "FailureReason": str,
+        "KmsKeyArn": str,
+        "FailureType": AnomalyDetectorFailureTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateAnomalyDetectorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAnomalyDetectorRequestRequestTypeDef",
     {
         "AnomalyDetectorName": str,
         "AnomalyDetectorConfig": AnomalyDetectorConfigTypeDef,
     },
 )
@@ -754,14 +845,23 @@
 
 class UpdateAnomalyDetectorRequestRequestTypeDef(
     _RequiredUpdateAnomalyDetectorRequestRequestTypeDef,
     _OptionalUpdateAnomalyDetectorRequestRequestTypeDef,
 ):
     pass
 
+ListAnomalyDetectorsResponseTypeDef = TypedDict(
+    "ListAnomalyDetectorsResponseTypeDef",
+    {
+        "AnomalyDetectorSummaryList": List[AnomalyDetectorSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AnomalyGroupStatisticsTypeDef = TypedDict(
     "AnomalyGroupStatisticsTypeDef",
     {
         "EvaluationStartDate": str,
         "TotalCount": int,
         "ItemizedMetricStatsList": List[ItemizedMetricStatsTypeDef],
     },
@@ -834,129 +934,29 @@
     "AutoDetectionMetricSourceTypeDef",
     {
         "S3SourceConfig": AutoDetectionS3SourceConfigTypeDef,
     },
     total=False,
 )
 
-CreateAlertResponseTypeDef = TypedDict(
-    "CreateAlertResponseTypeDef",
-    {
-        "AlertArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAnomalyDetectorResponseTypeDef = TypedDict(
-    "CreateAnomalyDetectorResponseTypeDef",
-    {
-        "AnomalyDetectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMetricSetResponseTypeDef = TypedDict(
-    "CreateMetricSetResponseTypeDef",
-    {
-        "MetricSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAnomalyDetectorResponseTypeDef = TypedDict(
-    "DescribeAnomalyDetectorResponseTypeDef",
-    {
-        "AnomalyDetectorArn": str,
-        "AnomalyDetectorName": str,
-        "AnomalyDetectorDescription": str,
-        "AnomalyDetectorConfig": AnomalyDetectorConfigSummaryTypeDef,
-        "CreationTime": datetime,
-        "LastModificationTime": datetime,
-        "Status": AnomalyDetectorStatusType,
-        "FailureReason": str,
-        "KmsKeyArn": str,
-        "FailureType": AnomalyDetectorFailureTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSampleDataResponseTypeDef = TypedDict(
-    "GetSampleDataResponseTypeDef",
-    {
-        "HeaderValues": List[str],
-        "SampleRows": List[List[str]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAlertsResponseTypeDef = TypedDict(
-    "ListAlertsResponseTypeDef",
-    {
-        "AlertSummaryList": List[AlertSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAnomalyDetectorsResponseTypeDef = TypedDict(
-    "ListAnomalyDetectorsResponseTypeDef",
-    {
-        "AnomalyDetectorSummaryList": List[AnomalyDetectorSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAlertResponseTypeDef = TypedDict(
-    "UpdateAlertResponseTypeDef",
-    {
-        "AlertArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAnomalyDetectorResponseTypeDef = TypedDict(
-    "UpdateAnomalyDetectorResponseTypeDef",
-    {
-        "AnomalyDetectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMetricSetResponseTypeDef = TypedDict(
-    "UpdateMetricSetResponseTypeDef",
-    {
-        "MetricSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 MetricSetDataQualityMetricTypeDef = TypedDict(
     "MetricSetDataQualityMetricTypeDef",
     {
         "MetricSetArn": str,
         "DataQualityMetricList": List[DataQualityMetricTypeDef],
     },
     total=False,
 )
 
 DescribeAnomalyDetectionExecutionsResponseTypeDef = TypedDict(
     "DescribeAnomalyDetectionExecutionsResponseTypeDef",
     {
         "ExecutionList": List[ExecutionStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DimensionContributionTypeDef = TypedDict(
     "DimensionContributionTypeDef",
     {
         "DimensionName": str,
@@ -993,33 +993,33 @@
 )
 
 GetFeedbackResponseTypeDef = TypedDict(
     "GetFeedbackResponseTypeDef",
     {
         "AnomalyGroupTimeSeriesFeedback": List[TimeSeriesFeedbackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAnomalyGroupRelatedMetricsResponseTypeDef = TypedDict(
     "ListAnomalyGroupRelatedMetricsResponseTypeDef",
     {
         "InterMetricImpactList": List[InterMetricImpactDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMetricSetsResponseTypeDef = TypedDict(
     "ListMetricSetsResponseTypeDef",
     {
         "MetricSetSummaryList": List[MetricSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RDSSourceConfigTypeDef = TypedDict(
     "RDSSourceConfigTypeDef",
     {
         "DBInstanceIdentifier": str,
@@ -1115,15 +1115,15 @@
 
 ListAnomalyGroupSummariesResponseTypeDef = TypedDict(
     "ListAnomalyGroupSummariesResponseTypeDef",
     {
         "AnomalyGroupSummaryList": List[AnomalyGroupSummaryTypeDef],
         "AnomalyGroupStatistics": AnomalyGroupStatisticsTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectedCsvFormatDescriptorTypeDef = TypedDict(
     "DetectedCsvFormatDescriptorTypeDef",
     {
         "FileCompression": DetectedFieldTypeDef,
@@ -1174,15 +1174,15 @@
     "ListAnomalyGroupTimeSeriesResponseTypeDef",
     {
         "AnomalyGroupId": str,
         "MetricName": str,
         "TimestampList": List[str],
         "NextToken": str,
         "TimeSeriesList": List[TimeSeriesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 S3SourceConfigTypeDef = TypedDict(
     "S3SourceConfigTypeDef",
     {
         "RoleArn": str,
@@ -1214,15 +1214,15 @@
 ):
     pass
 
 DescribeAlertResponseTypeDef = TypedDict(
     "DescribeAlertResponseTypeDef",
     {
         "Alert": AlertTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectedFileFormatDescriptorTypeDef = TypedDict(
     "DetectedFileFormatDescriptorTypeDef",
     {
         "CsvFormatDescriptor": DetectedCsvFormatDescriptorTypeDef,
@@ -1231,15 +1231,15 @@
     total=False,
 )
 
 GetDataQualityMetricsResponseTypeDef = TypedDict(
     "GetDataQualityMetricsResponseTypeDef",
     {
         "AnomalyDetectorDataQualityMetricList": List[AnomalyDetectorDataQualityMetricTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricLevelImpactTypeDef = TypedDict(
     "MetricLevelImpactTypeDef",
     {
         "MetricName": str,
@@ -1333,15 +1333,15 @@
         "MetricList": List[MetricTypeDef],
         "TimestampColumn": TimestampColumnTypeDef,
         "DimensionList": List[str],
         "MetricSetFrequency": FrequencyType,
         "Timezone": str,
         "MetricSource": MetricSourceTypeDef,
         "DimensionFilterList": List[MetricSetDimensionFilterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateMetricSetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateMetricSetRequestRequestTypeDef",
     {
         "MetricSetArn": str,
@@ -1375,15 +1375,15 @@
     total=False,
 )
 
 GetAnomalyGroupResponseTypeDef = TypedDict(
     "GetAnomalyGroupResponseTypeDef",
     {
         "AnomalyGroup": AnomalyGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectedMetricSetConfigTypeDef = TypedDict(
     "DetectedMetricSetConfigTypeDef",
     {
         "Offset": DetectedFieldTypeDef,
@@ -1393,10 +1393,10 @@
     total=False,
 )
 
 DetectMetricSetConfigResponseTypeDef = TypedDict(
     "DetectMetricSetConfigResponseTypeDef",
     {
         "DetectedMetricSetConfig": DetectedMetricSetConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/PKG-INFO` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lookoutmetrics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LookoutMetrics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LookoutMetrics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lookoutmetrics"></a>
 
 # types-aiobotocore-lookoutmetrics
 
 [![PyPI - types-aiobotocore-lookoutmetrics](https://img.shields.io/pypi/v/types-aiobotocore-lookoutmetrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutmetrics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lookoutmetrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lookoutmetrics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lookoutmetrics?color=blue)](https://pypistats.org/packages/types-aiobotocore-lookoutmetrics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LookoutMetrics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
+[aiobotocore.LookoutMetrics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lookoutmetrics.html#LookoutMetrics)
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
 [types-aiobotocore-lookoutmetrics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lookoutmetrics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,17 +320,19 @@
     AnomalyGroupTimeSeriesFeedbackTypeDef,
     AnomalyGroupTimeSeriesTypeDef,
     AppFlowConfigTypeDef,
     BackTestConfigurationTypeDef,
     AttributeValueTypeDef,
     AutoDetectionS3SourceConfigTypeDef,
     BackTestAnomalyDetectorRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAlertResponseTypeDef,
+    CreateAnomalyDetectorResponseTypeDef,
     MetricTypeDef,
     TimestampColumnTypeDef,
+    CreateMetricSetResponseTypeDef,
     CsvFormatDescriptorTypeDef,
     DataQualityMetricTypeDef,
     DeactivateAnomalyDetectorRequestRequestTypeDef,
     DeleteAlertRequestRequestTypeDef,
     DeleteAnomalyDetectorRequestRequestTypeDef,
     DescribeAlertRequestRequestTypeDef,
     DescribeAnomalyDetectionExecutionsRequestRequestTypeDef,
@@ -340,48 +342,46 @@
     DimensionValueContributionTypeDef,
     DimensionNameValueTypeDef,
     JsonFormatDescriptorTypeDef,
     FilterTypeDef,
     GetAnomalyGroupRequestRequestTypeDef,
     GetDataQualityMetricsRequestRequestTypeDef,
     TimeSeriesFeedbackTypeDef,
+    GetSampleDataResponseTypeDef,
     InterMetricImpactDetailsTypeDef,
     ListAlertsRequestRequestTypeDef,
     ListAnomalyDetectorsRequestRequestTypeDef,
     ListAnomalyGroupRelatedMetricsRequestRequestTypeDef,
     ListAnomalyGroupSummariesRequestRequestTypeDef,
     ListAnomalyGroupTimeSeriesRequestRequestTypeDef,
     ListMetricSetsRequestRequestTypeDef,
     MetricSetSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     VpcConfigurationTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAlertResponseTypeDef,
+    UpdateAnomalyDetectorResponseTypeDef,
+    UpdateMetricSetResponseTypeDef,
     ActionTypeDef,
     AlertFiltersTypeDef,
+    ListAlertsResponseTypeDef,
+    DescribeAnomalyDetectorResponseTypeDef,
     CreateAnomalyDetectorRequestRequestTypeDef,
     UpdateAnomalyDetectorRequestRequestTypeDef,
+    ListAnomalyDetectorsResponseTypeDef,
     AnomalyGroupStatisticsTypeDef,
     PutFeedbackRequestRequestTypeDef,
     GetFeedbackRequestRequestTypeDef,
     AthenaSourceConfigTypeDef,
     CloudWatchConfigTypeDef,
     DetectedFieldTypeDef,
     AutoDetectionMetricSourceTypeDef,
-    CreateAlertResponseTypeDef,
-    CreateAnomalyDetectorResponseTypeDef,
-    CreateMetricSetResponseTypeDef,
-    DescribeAnomalyDetectorResponseTypeDef,
-    GetSampleDataResponseTypeDef,
-    ListAlertsResponseTypeDef,
-    ListAnomalyDetectorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateAlertResponseTypeDef,
-    UpdateAnomalyDetectorResponseTypeDef,
-    UpdateMetricSetResponseTypeDef,
     MetricSetDataQualityMetricTypeDef,
     DescribeAnomalyDetectionExecutionsResponseTypeDef,
     DimensionContributionTypeDef,
     TimeSeriesTypeDef,
     FileFormatDescriptorTypeDef,
     MetricSetDimensionFilterTypeDef,
     GetFeedbackResponseTypeDef,
@@ -426,43 +426,43 @@
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

### Comparing `types-aiobotocore-lookoutmetrics-2.5.0.post1/types_aiobotocore_lookoutmetrics.egg-info/SOURCES.txt` & `types-aiobotocore-lookoutmetrics-2.5.1/types_aiobotocore_lookoutmetrics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

