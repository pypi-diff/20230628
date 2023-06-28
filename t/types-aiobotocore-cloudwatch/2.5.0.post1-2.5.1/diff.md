# Comparing `tmp/types-aiobotocore-cloudwatch-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudwatch-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudwatch-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudwatch-2.5.1.tar", last modified: Wed Jun 28 01:43:15 2023, max compression
```

## Comparing `types-aiobotocore-cloudwatch-2.5.0.post1.tar` & `types-aiobotocore-cloudwatch-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.239047 types-aiobotocore-cloudwatch-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21615 2023-03-11 12:26:22.239047 types-aiobotocore-cloudwatch-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20032 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:22.239047 types-aiobotocore-cloudwatch-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.235047 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/
--rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2270 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    34952 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    34897 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10935 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10933 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9366 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9357 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    25937 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    25889 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    42790 2023-03-11 12:11:05.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    42745 2023-03-11 12:11:04.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:02.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3335 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-03-11 12:11:03.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.239047 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21615 2023-03-11 12:26:22.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1048 2023-03-11 12:26:22.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:22.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:22.000000 types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.426111 types-aiobotocore-cloudwatch-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21529 2023-06-28 01:43:15.422111 types-aiobotocore-cloudwatch-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19952 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:15.426111 types-aiobotocore-cloudwatch-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.418111 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/
+-rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2270 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34952 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34897 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11144 2023-06-28 01:27:40.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11142 2023-06-28 01:27:40.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9271 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9262 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25830 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25782 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    42515 2023-06-28 01:27:41.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42470 2023-06-28 01:27:41.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3335 2023-06-28 01:27:40.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-06-28 01:27:39.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.422111 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21529 2023-06-28 01:43:15.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1048 2023-06-28 01:43:15.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:15.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:15.000000 types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudwatch-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudwatch-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudwatch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudWatch 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudWatch 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudwatch"></a>
 
 # types-aiobotocore-cloudwatch
 
 [![PyPI - types-aiobotocore-cloudwatch](https://img.shields.io/pypi/v/types-aiobotocore-cloudwatch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudwatch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudwatch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudwatch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudwatch?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudwatch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
+[aiobotocore.CloudWatch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
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
 [types-aiobotocore-cloudwatch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -459,77 +459,75 @@
     DashboardEntryTypeDef,
     DashboardValidationMessageTypeDef,
     DatapointTypeDef,
     DeleteAlarmsInputRequestTypeDef,
     DeleteDashboardsInputRequestTypeDef,
     DeleteInsightRulesInputRequestTypeDef,
     PartialFailureTypeDef,
-    ResponseMetadataTypeDef,
     DeleteMetricStreamInputRequestTypeDef,
     DescribeAlarmHistoryInputAlarmDescribeHistoryTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef,
     DescribeAlarmHistoryInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeAlarmsInputDescribeAlarmsPaginateTypeDef,
     DescribeAlarmsInputRequestTypeDef,
     DescribeInsightRulesInputRequestTypeDef,
     InsightRuleTypeDef,
     DimensionFilterTypeDef,
     DisableAlarmActionsInputRequestTypeDef,
     DisableInsightRulesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableAlarmActionsInputRequestTypeDef,
     EnableInsightRulesInputRequestTypeDef,
     GetDashboardInputRequestTypeDef,
+    GetDashboardOutputTypeDef,
     GetInsightRuleReportInputRequestTypeDef,
     InsightRuleMetricDatapointTypeDef,
     LabelOptionsTypeDef,
     MessageDataTypeDef,
     GetMetricStreamInputRequestTypeDef,
     MetricStreamFilterTypeDef,
     GetMetricWidgetImageInputRequestTypeDef,
+    GetMetricWidgetImageOutputTypeDef,
     InsightRuleContributorDatapointTypeDef,
+    ListDashboardsInputListDashboardsPaginateTypeDef,
     ListDashboardsInputRequestTypeDef,
     ListManagedInsightRulesInputRequestTypeDef,
     ListMetricStreamsInputRequestTypeDef,
     MetricStreamEntryTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     TagTypeDef,
     ManagedRuleStateTypeDef,
     StatisticSetTypeDef,
     MetricStreamStatisticsMetricTypeDef,
+    PaginatorConfigTypeDef,
     PutDashboardInputRequestTypeDef,
-    ServiceResourceAlarmRequestTypeDef,
-    ServiceResourceMetricRequestTypeDef,
+    PutMetricStreamOutputTypeDef,
+    ResponseMetadataTypeDef,
     SetAlarmStateInputAlarmSetStateTypeDef,
     SetAlarmStateInputRequestTypeDef,
     StartMetricStreamsInputRequestTypeDef,
     StopMetricStreamsInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    DescribeAlarmHistoryOutputTypeDef,
     AnomalyDetectorConfigurationTypeDef,
     DescribeAlarmsForMetricInputRequestTypeDef,
+    DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef,
     DescribeAnomalyDetectorsInputRequestTypeDef,
     GetMetricStatisticsInputMetricGetStatisticsTypeDef,
     GetMetricStatisticsInputRequestTypeDef,
     MetricTypeDef,
     SingleMetricAnomalyDetectorTypeDef,
+    ListDashboardsOutputTypeDef,
+    PutDashboardOutputTypeDef,
+    GetMetricStatisticsOutputTypeDef,
     DeleteInsightRulesOutputTypeDef,
-    DescribeAlarmHistoryOutputTypeDef,
     DisableInsightRulesOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     EnableInsightRulesOutputTypeDef,
-    GetDashboardOutputTypeDef,
-    GetMetricStatisticsOutputTypeDef,
-    GetMetricWidgetImageOutputTypeDef,
-    ListDashboardsOutputTypeDef,
-    PutDashboardOutputTypeDef,
     PutManagedInsightRulesOutputTypeDef,
-    PutMetricStreamOutputTypeDef,
-    DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef,
-    DescribeAlarmsInputDescribeAlarmsPaginateTypeDef,
-    DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef,
-    ListDashboardsInputListDashboardsPaginateTypeDef,
     DescribeAlarmsInputAlarmExistsWaitTypeDef,
     DescribeAlarmsInputCompositeAlarmExistsWaitTypeDef,
     DescribeInsightRulesOutputTypeDef,
     ListMetricsInputListMetricsPaginateTypeDef,
     ListMetricsInputRequestTypeDef,
     MetricDataResultTypeDef,
     InsightRuleContributorTypeDef,
@@ -574,43 +572,43 @@
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/README.md` & `types-aiobotocore-cloudwatch-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudwatch"></a>
 
 # types-aiobotocore-cloudwatch
 
 [![PyPI - types-aiobotocore-cloudwatch](https://img.shields.io/pypi/v/types-aiobotocore-cloudwatch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudwatch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudwatch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudwatch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudwatch?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudwatch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
+[aiobotocore.CloudWatch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
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
 [types-aiobotocore-cloudwatch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -426,77 +426,75 @@
     DashboardEntryTypeDef,
     DashboardValidationMessageTypeDef,
     DatapointTypeDef,
     DeleteAlarmsInputRequestTypeDef,
     DeleteDashboardsInputRequestTypeDef,
     DeleteInsightRulesInputRequestTypeDef,
     PartialFailureTypeDef,
-    ResponseMetadataTypeDef,
     DeleteMetricStreamInputRequestTypeDef,
     DescribeAlarmHistoryInputAlarmDescribeHistoryTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef,
     DescribeAlarmHistoryInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeAlarmsInputDescribeAlarmsPaginateTypeDef,
     DescribeAlarmsInputRequestTypeDef,
     DescribeInsightRulesInputRequestTypeDef,
     InsightRuleTypeDef,
     DimensionFilterTypeDef,
     DisableAlarmActionsInputRequestTypeDef,
     DisableInsightRulesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableAlarmActionsInputRequestTypeDef,
     EnableInsightRulesInputRequestTypeDef,
     GetDashboardInputRequestTypeDef,
+    GetDashboardOutputTypeDef,
     GetInsightRuleReportInputRequestTypeDef,
     InsightRuleMetricDatapointTypeDef,
     LabelOptionsTypeDef,
     MessageDataTypeDef,
     GetMetricStreamInputRequestTypeDef,
     MetricStreamFilterTypeDef,
     GetMetricWidgetImageInputRequestTypeDef,
+    GetMetricWidgetImageOutputTypeDef,
     InsightRuleContributorDatapointTypeDef,
+    ListDashboardsInputListDashboardsPaginateTypeDef,
     ListDashboardsInputRequestTypeDef,
     ListManagedInsightRulesInputRequestTypeDef,
     ListMetricStreamsInputRequestTypeDef,
     MetricStreamEntryTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     TagTypeDef,
     ManagedRuleStateTypeDef,
     StatisticSetTypeDef,
     MetricStreamStatisticsMetricTypeDef,
+    PaginatorConfigTypeDef,
     PutDashboardInputRequestTypeDef,
-    ServiceResourceAlarmRequestTypeDef,
-    ServiceResourceMetricRequestTypeDef,
+    PutMetricStreamOutputTypeDef,
+    ResponseMetadataTypeDef,
     SetAlarmStateInputAlarmSetStateTypeDef,
     SetAlarmStateInputRequestTypeDef,
     StartMetricStreamsInputRequestTypeDef,
     StopMetricStreamsInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    DescribeAlarmHistoryOutputTypeDef,
     AnomalyDetectorConfigurationTypeDef,
     DescribeAlarmsForMetricInputRequestTypeDef,
+    DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef,
     DescribeAnomalyDetectorsInputRequestTypeDef,
     GetMetricStatisticsInputMetricGetStatisticsTypeDef,
     GetMetricStatisticsInputRequestTypeDef,
     MetricTypeDef,
     SingleMetricAnomalyDetectorTypeDef,
+    ListDashboardsOutputTypeDef,
+    PutDashboardOutputTypeDef,
+    GetMetricStatisticsOutputTypeDef,
     DeleteInsightRulesOutputTypeDef,
-    DescribeAlarmHistoryOutputTypeDef,
     DisableInsightRulesOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     EnableInsightRulesOutputTypeDef,
-    GetDashboardOutputTypeDef,
-    GetMetricStatisticsOutputTypeDef,
-    GetMetricWidgetImageOutputTypeDef,
-    ListDashboardsOutputTypeDef,
-    PutDashboardOutputTypeDef,
     PutManagedInsightRulesOutputTypeDef,
-    PutMetricStreamOutputTypeDef,
-    DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef,
-    DescribeAlarmsInputDescribeAlarmsPaginateTypeDef,
-    DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef,
-    ListDashboardsInputListDashboardsPaginateTypeDef,
     DescribeAlarmsInputAlarmExistsWaitTypeDef,
     DescribeAlarmsInputCompositeAlarmExistsWaitTypeDef,
     DescribeInsightRulesOutputTypeDef,
     ListMetricsInputListMetricsPaginateTypeDef,
     ListMetricsInputRequestTypeDef,
     MetricDataResultTypeDef,
     InsightRuleContributorTypeDef,
@@ -541,43 +539,43 @@
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/setup.py` & `types-aiobotocore-cloudwatch-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudwatch.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudwatch",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudwatch"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudWatch 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudWatch 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/"
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/__init__.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/__init__.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/__main__.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudWatch 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudWatch 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch\nOther"
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/client.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/client.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/literals.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -168,14 +168,15 @@
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
@@ -254,14 +255,15 @@
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
@@ -272,14 +274,15 @@
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
@@ -315,14 +318,15 @@
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
@@ -341,16 +345,19 @@
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
@@ -434,15 +441,17 @@
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/literals.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -166,14 +166,15 @@
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
@@ -252,14 +253,15 @@
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
@@ -270,14 +272,15 @@
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
@@ -313,14 +316,15 @@
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
@@ -339,16 +343,19 @@
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
@@ -432,15 +439,17 @@
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/paginator.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,15 +28,15 @@
         get_metric_data_paginator: GetMetricDataPaginator = client.get_paginator("get_metric_data")
         list_dashboards_paginator: ListDashboardsPaginator = client.get_paginator("list_dashboards")
         list_metrics_paginator: ListMetricsPaginator = client.get_paginator("list_metrics")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AlarmTypeType,
     AnomalyDetectorTypeType,
@@ -54,18 +54,14 @@
     LabelOptionsTypeDef,
     ListDashboardsOutputTypeDef,
     ListMetricsOutputTypeDef,
     MetricDataQueryTypeDef,
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
@@ -99,15 +95,15 @@
         *,
         AlarmName: str = ...,
         AlarmTypes: Sequence[AlarmTypeType] = ...,
         HistoryItemType: HistoryItemTypeType = ...,
         StartDate: Union[datetime, str] = ...,
         EndDate: Union[datetime, str] = ...,
         ScanBy: ScanByType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAlarmHistoryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.DescribeAlarmHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#describealarmhistorypaginator)
         """
 
 
@@ -123,15 +119,15 @@
         AlarmNames: Sequence[str] = ...,
         AlarmNamePrefix: str = ...,
         AlarmTypes: Sequence[AlarmTypeType] = ...,
         ChildrenOfAlarmName: str = ...,
         ParentsOfAlarmName: str = ...,
         StateValue: StateValueType = ...,
         ActionPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAlarmsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.DescribeAlarms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#describealarmspaginator)
         """
 
 
@@ -144,15 +140,15 @@
     def paginate(
         self,
         *,
         Namespace: str = ...,
         MetricName: str = ...,
         Dimensions: Sequence[DimensionTypeDef] = ...,
         AnomalyDetectorTypes: Sequence[AnomalyDetectorTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAnomalyDetectorsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.DescribeAnomalyDetectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#describeanomalydetectorspaginator)
         """
 
 
@@ -166,30 +162,30 @@
         self,
         *,
         MetricDataQueries: Sequence[MetricDataQueryTypeDef],
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         ScanBy: ScanByType = ...,
         LabelOptions: LabelOptionsTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetMetricDataOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.GetMetricData.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#getmetricdatapaginator)
         """
 
 
 class ListDashboardsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.ListDashboards)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#listdashboardspaginator)
     """
 
     def paginate(
-        self, *, DashboardNamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DashboardNamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDashboardsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.ListDashboards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#listdashboardspaginator)
         """
 
 
@@ -204,13 +200,13 @@
         *,
         Namespace: str = ...,
         MetricName: str = ...,
         Dimensions: Sequence[DimensionFilterTypeDef] = ...,
         RecentlyActive: Literal["PT3H"] = ...,
         IncludeLinkedAccounts: bool = ...,
         OwningAccount: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.ListMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#listmetricspaginator)
         """
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/paginator.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -28,15 +28,15 @@
         get_metric_data_paginator: GetMetricDataPaginator = client.get_paginator("get_metric_data")
         list_dashboards_paginator: ListDashboardsPaginator = client.get_paginator("list_dashboards")
         list_metrics_paginator: ListMetricsPaginator = client.get_paginator("list_metrics")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AlarmTypeType,
     AnomalyDetectorTypeType,
@@ -54,18 +54,14 @@
     LabelOptionsTypeDef,
     ListDashboardsOutputTypeDef,
     ListMetricsOutputTypeDef,
     MetricDataQueryTypeDef,
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
     "DescribeAlarmHistoryPaginator",
@@ -95,15 +91,15 @@
         *,
         AlarmName: str = ...,
         AlarmTypes: Sequence[AlarmTypeType] = ...,
         HistoryItemType: HistoryItemTypeType = ...,
         StartDate: Union[datetime, str] = ...,
         EndDate: Union[datetime, str] = ...,
         ScanBy: ScanByType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAlarmHistoryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.DescribeAlarmHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#describealarmhistorypaginator)
         """
 
 class DescribeAlarmsPaginator(AioPaginator):
@@ -118,15 +114,15 @@
         AlarmNames: Sequence[str] = ...,
         AlarmNamePrefix: str = ...,
         AlarmTypes: Sequence[AlarmTypeType] = ...,
         ChildrenOfAlarmName: str = ...,
         ParentsOfAlarmName: str = ...,
         StateValue: StateValueType = ...,
         ActionPrefix: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAlarmsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.DescribeAlarms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#describealarmspaginator)
         """
 
 class DescribeAnomalyDetectorsPaginator(AioPaginator):
@@ -138,15 +134,15 @@
     def paginate(
         self,
         *,
         Namespace: str = ...,
         MetricName: str = ...,
         Dimensions: Sequence[DimensionTypeDef] = ...,
         AnomalyDetectorTypes: Sequence[AnomalyDetectorTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAnomalyDetectorsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.DescribeAnomalyDetectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#describeanomalydetectorspaginator)
         """
 
 class GetMetricDataPaginator(AioPaginator):
@@ -159,29 +155,29 @@
         self,
         *,
         MetricDataQueries: Sequence[MetricDataQueryTypeDef],
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         ScanBy: ScanByType = ...,
         LabelOptions: LabelOptionsTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetMetricDataOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.GetMetricData.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#getmetricdatapaginator)
         """
 
 class ListDashboardsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.ListDashboards)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#listdashboardspaginator)
     """
 
     def paginate(
-        self, *, DashboardNamePrefix: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DashboardNamePrefix: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDashboardsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.ListDashboards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#listdashboardspaginator)
         """
 
 class ListMetricsPaginator(AioPaginator):
@@ -195,13 +191,13 @@
         *,
         Namespace: str = ...,
         MetricName: str = ...,
         Dimensions: Sequence[DimensionFilterTypeDef] = ...,
         RecentlyActive: Literal["PT3H"] = ...,
         IncludeLinkedAccounts: bool = ...,
         OwningAccount: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch.Paginator.ListMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/paginators/#listmetricspaginator)
         """
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/service_resource.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/service_resource.py`

 * *Files 0% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 
         my_alarm: cloudwatch_resources.Alarm = resource.Alarm(...)
         my_metric: cloudwatch_resources.Metric = resource.Metric(...)
 ```
 """
 import sys
 from datetime import datetime
-from typing import Awaitable, List, NoReturn, Sequence, Union
+from typing import AsyncIterator, Awaitable, List, NoReturn, Sequence, Union
 
 from .client import CloudWatchClient
 from .literals import (
     AlarmTypeType,
     ComparisonOperatorType,
     HistoryItemTypeType,
     ScanByType,
@@ -46,18 +46,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/service_resource.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/service_resource.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 
         my_alarm: cloudwatch_resources.Alarm = resource.Alarm(...)
         my_metric: cloudwatch_resources.Metric = resource.Metric(...)
 ```
 """
 import sys
 from datetime import datetime
-from typing import Awaitable, List, NoReturn, Sequence, Union
+from typing import AsyncIterator, Awaitable, List, NoReturn, Sequence, Union
 
 from .client import CloudWatchClient
 from .literals import (
     AlarmTypeType,
     ComparisonOperatorType,
     HistoryItemTypeType,
     ScanByType,
@@ -46,18 +46,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/type_defs.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -48,77 +48,75 @@
     "DashboardEntryTypeDef",
     "DashboardValidationMessageTypeDef",
     "DatapointTypeDef",
     "DeleteAlarmsInputRequestTypeDef",
     "DeleteDashboardsInputRequestTypeDef",
     "DeleteInsightRulesInputRequestTypeDef",
     "PartialFailureTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteMetricStreamInputRequestTypeDef",
     "DescribeAlarmHistoryInputAlarmDescribeHistoryTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
     "DescribeAlarmHistoryInputRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
     "DescribeAlarmsInputRequestTypeDef",
     "DescribeInsightRulesInputRequestTypeDef",
     "InsightRuleTypeDef",
     "DimensionFilterTypeDef",
     "DisableAlarmActionsInputRequestTypeDef",
     "DisableInsightRulesInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableAlarmActionsInputRequestTypeDef",
     "EnableInsightRulesInputRequestTypeDef",
     "GetDashboardInputRequestTypeDef",
+    "GetDashboardOutputTypeDef",
     "GetInsightRuleReportInputRequestTypeDef",
     "InsightRuleMetricDatapointTypeDef",
     "LabelOptionsTypeDef",
     "MessageDataTypeDef",
     "GetMetricStreamInputRequestTypeDef",
     "MetricStreamFilterTypeDef",
     "GetMetricWidgetImageInputRequestTypeDef",
+    "GetMetricWidgetImageOutputTypeDef",
     "InsightRuleContributorDatapointTypeDef",
+    "ListDashboardsInputListDashboardsPaginateTypeDef",
     "ListDashboardsInputRequestTypeDef",
     "ListManagedInsightRulesInputRequestTypeDef",
     "ListMetricStreamsInputRequestTypeDef",
     "MetricStreamEntryTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "TagTypeDef",
     "ManagedRuleStateTypeDef",
     "StatisticSetTypeDef",
     "MetricStreamStatisticsMetricTypeDef",
+    "PaginatorConfigTypeDef",
     "PutDashboardInputRequestTypeDef",
-    "ServiceResourceAlarmRequestTypeDef",
-    "ServiceResourceMetricRequestTypeDef",
+    "PutMetricStreamOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "SetAlarmStateInputAlarmSetStateTypeDef",
     "SetAlarmStateInputRequestTypeDef",
     "StartMetricStreamsInputRequestTypeDef",
     "StopMetricStreamsInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "DescribeAlarmHistoryOutputTypeDef",
     "AnomalyDetectorConfigurationTypeDef",
     "DescribeAlarmsForMetricInputRequestTypeDef",
+    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
     "DescribeAnomalyDetectorsInputRequestTypeDef",
     "GetMetricStatisticsInputMetricGetStatisticsTypeDef",
     "GetMetricStatisticsInputRequestTypeDef",
     "MetricTypeDef",
     "SingleMetricAnomalyDetectorTypeDef",
+    "ListDashboardsOutputTypeDef",
+    "PutDashboardOutputTypeDef",
+    "GetMetricStatisticsOutputTypeDef",
     "DeleteInsightRulesOutputTypeDef",
-    "DescribeAlarmHistoryOutputTypeDef",
     "DisableInsightRulesOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EnableInsightRulesOutputTypeDef",
-    "GetDashboardOutputTypeDef",
-    "GetMetricStatisticsOutputTypeDef",
-    "GetMetricWidgetImageOutputTypeDef",
-    "ListDashboardsOutputTypeDef",
-    "PutDashboardOutputTypeDef",
     "PutManagedInsightRulesOutputTypeDef",
-    "PutMetricStreamOutputTypeDef",
-    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
-    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
-    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
-    "ListDashboardsInputListDashboardsPaginateTypeDef",
     "DescribeAlarmsInputAlarmExistsWaitTypeDef",
     "DescribeAlarmsInputCompositeAlarmExistsWaitTypeDef",
     "DescribeInsightRulesOutputTypeDef",
     "ListMetricsInputListMetricsPaginateTypeDef",
     "ListMetricsInputRequestTypeDef",
     "MetricDataResultTypeDef",
     "InsightRuleContributorTypeDef",
@@ -273,25 +271,14 @@
         "ExceptionType": str,
         "FailureCode": str,
         "FailureDescription": str,
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
 DeleteMetricStreamInputRequestTypeDef = TypedDict(
     "DeleteMetricStreamInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -305,20 +292,24 @@
         "MaxRecords": int,
         "NextToken": str,
         "ScanBy": ScanByType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef = TypedDict(
+    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AlarmName": str,
+        "AlarmTypes": Sequence[AlarmTypeType],
+        "HistoryItemType": HistoryItemTypeType,
+        "StartDate": Union[datetime, str],
+        "EndDate": Union[datetime, str],
+        "ScanBy": ScanByType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAlarmHistoryInputRequestTypeDef = TypedDict(
     "DescribeAlarmHistoryInputRequestTypeDef",
     {
@@ -339,14 +330,29 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+DescribeAlarmsInputDescribeAlarmsPaginateTypeDef = TypedDict(
+    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
+    {
+        "AlarmNames": Sequence[str],
+        "AlarmNamePrefix": str,
+        "AlarmTypes": Sequence[AlarmTypeType],
+        "ChildrenOfAlarmName": str,
+        "ParentsOfAlarmName": str,
+        "StateValue": StateValueType,
+        "ActionPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAlarmsInputRequestTypeDef = TypedDict(
     "DescribeAlarmsInputRequestTypeDef",
     {
         "AlarmNames": Sequence[str],
         "AlarmNamePrefix": str,
         "AlarmTypes": Sequence[AlarmTypeType],
         "ChildrenOfAlarmName": str,
@@ -419,14 +425,21 @@
 DisableInsightRulesInputRequestTypeDef = TypedDict(
     "DisableInsightRulesInputRequestTypeDef",
     {
         "RuleNames": Sequence[str],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableAlarmActionsInputRequestTypeDef = TypedDict(
     "EnableAlarmActionsInputRequestTypeDef",
     {
         "AlarmNames": Sequence[str],
     },
 )
 
@@ -440,14 +453,24 @@
 GetDashboardInputRequestTypeDef = TypedDict(
     "GetDashboardInputRequestTypeDef",
     {
         "DashboardName": str,
     },
 )
 
+GetDashboardOutputTypeDef = TypedDict(
+    "GetDashboardOutputTypeDef",
+    {
+        "DashboardArn": str,
+        "DashboardBody": str,
+        "DashboardName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetInsightRuleReportInputRequestTypeDef = TypedDict(
     "_RequiredGetInsightRuleReportInputRequestTypeDef",
     {
         "RuleName": str,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "Period": int,
@@ -522,14 +545,15 @@
     },
 )
 
 MetricStreamFilterTypeDef = TypedDict(
     "MetricStreamFilterTypeDef",
     {
         "Namespace": str,
+        "MetricNames": List[str],
     },
     total=False,
 )
 
 _RequiredGetMetricWidgetImageInputRequestTypeDef = TypedDict(
     "_RequiredGetMetricWidgetImageInputRequestTypeDef",
     {
@@ -548,22 +572,39 @@
 class GetMetricWidgetImageInputRequestTypeDef(
     _RequiredGetMetricWidgetImageInputRequestTypeDef,
     _OptionalGetMetricWidgetImageInputRequestTypeDef,
 ):
     pass
 
 
+GetMetricWidgetImageOutputTypeDef = TypedDict(
+    "GetMetricWidgetImageOutputTypeDef",
+    {
+        "MetricWidgetImage": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InsightRuleContributorDatapointTypeDef = TypedDict(
     "InsightRuleContributorDatapointTypeDef",
     {
         "Timestamp": datetime,
         "ApproximateValue": float,
     },
 )
 
+ListDashboardsInputListDashboardsPaginateTypeDef = TypedDict(
+    "ListDashboardsInputListDashboardsPaginateTypeDef",
+    {
+        "DashboardNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDashboardsInputRequestTypeDef = TypedDict(
     "ListDashboardsInputRequestTypeDef",
     {
         "DashboardNamePrefix": str,
         "NextToken": str,
     },
     total=False,
@@ -652,34 +693,48 @@
     "MetricStreamStatisticsMetricTypeDef",
     {
         "Namespace": str,
         "MetricName": str,
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
 PutDashboardInputRequestTypeDef = TypedDict(
     "PutDashboardInputRequestTypeDef",
     {
         "DashboardName": str,
         "DashboardBody": str,
     },
 )
 
-ServiceResourceAlarmRequestTypeDef = TypedDict(
-    "ServiceResourceAlarmRequestTypeDef",
+PutMetricStreamOutputTypeDef = TypedDict(
+    "PutMetricStreamOutputTypeDef",
     {
-        "name": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ServiceResourceMetricRequestTypeDef = TypedDict(
-    "ServiceResourceMetricRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "namespace": str,
-        "name": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 _RequiredSetAlarmStateInputAlarmSetStateTypeDef = TypedDict(
     "_RequiredSetAlarmStateInputAlarmSetStateTypeDef",
     {
         "StateValue": StateValueType,
@@ -742,14 +797,23 @@
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+DescribeAlarmHistoryOutputTypeDef = TypedDict(
+    "DescribeAlarmHistoryOutputTypeDef",
+    {
+        "AlarmHistoryItems": List[AlarmHistoryItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AnomalyDetectorConfigurationTypeDef = TypedDict(
     "AnomalyDetectorConfigurationTypeDef",
     {
         "ExcludedTimeRanges": List[RangeTypeDef],
         "MetricTimezone": str,
     },
     total=False,
@@ -778,14 +842,26 @@
 class DescribeAlarmsForMetricInputRequestTypeDef(
     _RequiredDescribeAlarmsForMetricInputRequestTypeDef,
     _OptionalDescribeAlarmsForMetricInputRequestTypeDef,
 ):
     pass
 
 
+DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef = TypedDict(
+    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
+    {
+        "Namespace": str,
+        "MetricName": str,
+        "Dimensions": Sequence[DimensionTypeDef],
+        "AnomalyDetectorTypes": Sequence[AnomalyDetectorTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAnomalyDetectorsInputRequestTypeDef = TypedDict(
     "DescribeAnomalyDetectorsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Namespace": str,
         "MetricName": str,
@@ -867,162 +943,70 @@
         "MetricName": str,
         "Dimensions": Sequence[DimensionTypeDef],
         "Stat": str,
     },
     total=False,
 )
 
-DeleteInsightRulesOutputTypeDef = TypedDict(
-    "DeleteInsightRulesOutputTypeDef",
-    {
-        "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAlarmHistoryOutputTypeDef = TypedDict(
-    "DescribeAlarmHistoryOutputTypeDef",
+ListDashboardsOutputTypeDef = TypedDict(
+    "ListDashboardsOutputTypeDef",
     {
-        "AlarmHistoryItems": List[AlarmHistoryItemTypeDef],
+        "DashboardEntries": List[DashboardEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisableInsightRulesOutputTypeDef = TypedDict(
-    "DisableInsightRulesOutputTypeDef",
-    {
-        "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EnableInsightRulesOutputTypeDef = TypedDict(
-    "EnableInsightRulesOutputTypeDef",
-    {
-        "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDashboardOutputTypeDef = TypedDict(
-    "GetDashboardOutputTypeDef",
+PutDashboardOutputTypeDef = TypedDict(
+    "PutDashboardOutputTypeDef",
     {
-        "DashboardArn": str,
-        "DashboardBody": str,
-        "DashboardName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DashboardValidationMessages": List[DashboardValidationMessageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMetricStatisticsOutputTypeDef = TypedDict(
     "GetMetricStatisticsOutputTypeDef",
     {
         "Label": str,
         "Datapoints": List[DatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetMetricWidgetImageOutputTypeDef = TypedDict(
-    "GetMetricWidgetImageOutputTypeDef",
+DeleteInsightRulesOutputTypeDef = TypedDict(
+    "DeleteInsightRulesOutputTypeDef",
     {
-        "MetricWidgetImage": bytes,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Failures": List[PartialFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListDashboardsOutputTypeDef = TypedDict(
-    "ListDashboardsOutputTypeDef",
+DisableInsightRulesOutputTypeDef = TypedDict(
+    "DisableInsightRulesOutputTypeDef",
     {
-        "DashboardEntries": List[DashboardEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Failures": List[PartialFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutDashboardOutputTypeDef = TypedDict(
-    "PutDashboardOutputTypeDef",
+EnableInsightRulesOutputTypeDef = TypedDict(
+    "EnableInsightRulesOutputTypeDef",
     {
-        "DashboardValidationMessages": List[DashboardValidationMessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Failures": List[PartialFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutManagedInsightRulesOutputTypeDef = TypedDict(
     "PutManagedInsightRulesOutputTypeDef",
     {
         "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutMetricStreamOutputTypeDef = TypedDict(
-    "PutMetricStreamOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef = TypedDict(
-    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
-    {
-        "AlarmName": str,
-        "AlarmTypes": Sequence[AlarmTypeType],
-        "HistoryItemType": HistoryItemTypeType,
-        "StartDate": Union[datetime, str],
-        "EndDate": Union[datetime, str],
-        "ScanBy": ScanByType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeAlarmsInputDescribeAlarmsPaginateTypeDef = TypedDict(
-    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
-    {
-        "AlarmNames": Sequence[str],
-        "AlarmNamePrefix": str,
-        "AlarmTypes": Sequence[AlarmTypeType],
-        "ChildrenOfAlarmName": str,
-        "ParentsOfAlarmName": str,
-        "StateValue": StateValueType,
-        "ActionPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef = TypedDict(
-    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
-    {
-        "Namespace": str,
-        "MetricName": str,
-        "Dimensions": Sequence[DimensionTypeDef],
-        "AnomalyDetectorTypes": Sequence[AnomalyDetectorTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDashboardsInputListDashboardsPaginateTypeDef = TypedDict(
-    "ListDashboardsInputListDashboardsPaginateTypeDef",
-    {
-        "DashboardNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeAlarmsInputAlarmExistsWaitTypeDef = TypedDict(
     "DescribeAlarmsInputAlarmExistsWaitTypeDef",
     {
         "AlarmNames": Sequence[str],
         "AlarmNamePrefix": str,
@@ -1056,28 +1040,28 @@
 )
 
 DescribeInsightRulesOutputTypeDef = TypedDict(
     "DescribeInsightRulesOutputTypeDef",
     {
         "NextToken": str,
         "InsightRules": List[InsightRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMetricsInputListMetricsPaginateTypeDef = TypedDict(
     "ListMetricsInputListMetricsPaginateTypeDef",
     {
         "Namespace": str,
         "MetricName": str,
         "Dimensions": Sequence[DimensionFilterTypeDef],
         "RecentlyActive": Literal["PT3H"],
         "IncludeLinkedAccounts": bool,
         "OwningAccount": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListMetricsInputRequestTypeDef = TypedDict(
     "ListMetricsInputRequestTypeDef",
     {
@@ -1115,23 +1099,23 @@
 )
 
 ListMetricStreamsOutputTypeDef = TypedDict(
     "ListMetricStreamsOutputTypeDef",
     {
         "NextToken": str,
         "Entries": List[MetricStreamEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredManagedRuleTypeDef = TypedDict(
     "_RequiredManagedRuleTypeDef",
     {
         "TemplateName": str,
@@ -1258,15 +1242,15 @@
 
 ListMetricsOutputTypeDef = TypedDict(
     "ListMetricsOutputTypeDef",
     {
         "Metrics": List[MetricTypeDef],
         "NextToken": str,
         "OwningAccounts": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricStatTypeDef = TypedDict(
     "_RequiredMetricStatTypeDef",
     {
         "Metric": MetricTypeDef,
@@ -1289,28 +1273,28 @@
 
 GetMetricDataOutputTypeDef = TypedDict(
     "GetMetricDataOutputTypeDef",
     {
         "MetricDataResults": List[MetricDataResultTypeDef],
         "NextToken": str,
         "Messages": List[MessageDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightRuleReportOutputTypeDef = TypedDict(
     "GetInsightRuleReportOutputTypeDef",
     {
         "KeyLabels": List[str],
         "AggregationStatistic": str,
         "AggregateValue": float,
         "ApproximateUniqueCount": int,
         "Contributors": List[InsightRuleContributorTypeDef],
         "MetricDatapoints": List[InsightRuleMetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutManagedInsightRulesInputRequestTypeDef = TypedDict(
     "PutManagedInsightRulesInputRequestTypeDef",
     {
         "ManagedRules": Sequence[ManagedRuleTypeDef],
@@ -1318,15 +1302,15 @@
 )
 
 ListManagedInsightRulesOutputTypeDef = TypedDict(
     "ListManagedInsightRulesOutputTypeDef",
     {
         "ManagedRules": List[ManagedRuleDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutMetricDataInputRequestTypeDef = TypedDict(
     "PutMetricDataInputRequestTypeDef",
     {
         "Namespace": str,
@@ -1345,15 +1329,15 @@
         "RoleArn": str,
         "State": str,
         "CreationDate": datetime,
         "LastUpdateDate": datetime,
         "OutputFormat": MetricStreamOutputFormatType,
         "StatisticsConfigurations": List[MetricStreamStatisticsConfigurationTypeDef],
         "IncludeLinkedAccountsMetrics": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutMetricStreamInputRequestTypeDef = TypedDict(
     "_RequiredPutMetricStreamInputRequestTypeDef",
     {
         "Name": str,
@@ -1414,15 +1398,15 @@
     },
 )
 _OptionalGetMetricDataInputGetMetricDataPaginateTypeDef = TypedDict(
     "_OptionalGetMetricDataInputGetMetricDataPaginateTypeDef",
     {
         "ScanBy": ScanByType,
         "LabelOptions": LabelOptionsTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetMetricDataInputGetMetricDataPaginateTypeDef(
     _RequiredGetMetricDataInputGetMetricDataPaginateTypeDef,
@@ -1582,25 +1566,25 @@
     pass
 
 
 DescribeAlarmsForMetricOutputTypeDef = TypedDict(
     "DescribeAlarmsForMetricOutputTypeDef",
     {
         "MetricAlarms": List[MetricAlarmTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAlarmsOutputTypeDef = TypedDict(
     "DescribeAlarmsOutputTypeDef",
     {
         "CompositeAlarms": List[CompositeAlarmTypeDef],
         "MetricAlarms": List[MetricAlarmTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnomalyDetectorTypeDef = TypedDict(
     "AnomalyDetectorTypeDef",
     {
         "Namespace": str,
@@ -1643,10 +1627,10 @@
 )
 
 DescribeAnomalyDetectorsOutputTypeDef = TypedDict(
     "DescribeAnomalyDetectorsOutputTypeDef",
     {
         "AnomalyDetectors": List[AnomalyDetectorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/type_defs.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -47,77 +47,75 @@
     "DashboardEntryTypeDef",
     "DashboardValidationMessageTypeDef",
     "DatapointTypeDef",
     "DeleteAlarmsInputRequestTypeDef",
     "DeleteDashboardsInputRequestTypeDef",
     "DeleteInsightRulesInputRequestTypeDef",
     "PartialFailureTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteMetricStreamInputRequestTypeDef",
     "DescribeAlarmHistoryInputAlarmDescribeHistoryTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
     "DescribeAlarmHistoryInputRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
     "DescribeAlarmsInputRequestTypeDef",
     "DescribeInsightRulesInputRequestTypeDef",
     "InsightRuleTypeDef",
     "DimensionFilterTypeDef",
     "DisableAlarmActionsInputRequestTypeDef",
     "DisableInsightRulesInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableAlarmActionsInputRequestTypeDef",
     "EnableInsightRulesInputRequestTypeDef",
     "GetDashboardInputRequestTypeDef",
+    "GetDashboardOutputTypeDef",
     "GetInsightRuleReportInputRequestTypeDef",
     "InsightRuleMetricDatapointTypeDef",
     "LabelOptionsTypeDef",
     "MessageDataTypeDef",
     "GetMetricStreamInputRequestTypeDef",
     "MetricStreamFilterTypeDef",
     "GetMetricWidgetImageInputRequestTypeDef",
+    "GetMetricWidgetImageOutputTypeDef",
     "InsightRuleContributorDatapointTypeDef",
+    "ListDashboardsInputListDashboardsPaginateTypeDef",
     "ListDashboardsInputRequestTypeDef",
     "ListManagedInsightRulesInputRequestTypeDef",
     "ListMetricStreamsInputRequestTypeDef",
     "MetricStreamEntryTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "TagTypeDef",
     "ManagedRuleStateTypeDef",
     "StatisticSetTypeDef",
     "MetricStreamStatisticsMetricTypeDef",
+    "PaginatorConfigTypeDef",
     "PutDashboardInputRequestTypeDef",
-    "ServiceResourceAlarmRequestTypeDef",
-    "ServiceResourceMetricRequestTypeDef",
+    "PutMetricStreamOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "SetAlarmStateInputAlarmSetStateTypeDef",
     "SetAlarmStateInputRequestTypeDef",
     "StartMetricStreamsInputRequestTypeDef",
     "StopMetricStreamsInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "DescribeAlarmHistoryOutputTypeDef",
     "AnomalyDetectorConfigurationTypeDef",
     "DescribeAlarmsForMetricInputRequestTypeDef",
+    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
     "DescribeAnomalyDetectorsInputRequestTypeDef",
     "GetMetricStatisticsInputMetricGetStatisticsTypeDef",
     "GetMetricStatisticsInputRequestTypeDef",
     "MetricTypeDef",
     "SingleMetricAnomalyDetectorTypeDef",
+    "ListDashboardsOutputTypeDef",
+    "PutDashboardOutputTypeDef",
+    "GetMetricStatisticsOutputTypeDef",
     "DeleteInsightRulesOutputTypeDef",
-    "DescribeAlarmHistoryOutputTypeDef",
     "DisableInsightRulesOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EnableInsightRulesOutputTypeDef",
-    "GetDashboardOutputTypeDef",
-    "GetMetricStatisticsOutputTypeDef",
-    "GetMetricWidgetImageOutputTypeDef",
-    "ListDashboardsOutputTypeDef",
-    "PutDashboardOutputTypeDef",
     "PutManagedInsightRulesOutputTypeDef",
-    "PutMetricStreamOutputTypeDef",
-    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
-    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
-    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
-    "ListDashboardsInputListDashboardsPaginateTypeDef",
     "DescribeAlarmsInputAlarmExistsWaitTypeDef",
     "DescribeAlarmsInputCompositeAlarmExistsWaitTypeDef",
     "DescribeInsightRulesOutputTypeDef",
     "ListMetricsInputListMetricsPaginateTypeDef",
     "ListMetricsInputRequestTypeDef",
     "MetricDataResultTypeDef",
     "InsightRuleContributorTypeDef",
@@ -272,25 +270,14 @@
         "ExceptionType": str,
         "FailureCode": str,
         "FailureDescription": str,
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
 DeleteMetricStreamInputRequestTypeDef = TypedDict(
     "DeleteMetricStreamInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -304,20 +291,24 @@
         "MaxRecords": int,
         "NextToken": str,
         "ScanBy": ScanByType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef = TypedDict(
+    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AlarmName": str,
+        "AlarmTypes": Sequence[AlarmTypeType],
+        "HistoryItemType": HistoryItemTypeType,
+        "StartDate": Union[datetime, str],
+        "EndDate": Union[datetime, str],
+        "ScanBy": ScanByType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAlarmHistoryInputRequestTypeDef = TypedDict(
     "DescribeAlarmHistoryInputRequestTypeDef",
     {
@@ -338,14 +329,29 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+DescribeAlarmsInputDescribeAlarmsPaginateTypeDef = TypedDict(
+    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
+    {
+        "AlarmNames": Sequence[str],
+        "AlarmNamePrefix": str,
+        "AlarmTypes": Sequence[AlarmTypeType],
+        "ChildrenOfAlarmName": str,
+        "ParentsOfAlarmName": str,
+        "StateValue": StateValueType,
+        "ActionPrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAlarmsInputRequestTypeDef = TypedDict(
     "DescribeAlarmsInputRequestTypeDef",
     {
         "AlarmNames": Sequence[str],
         "AlarmNamePrefix": str,
         "AlarmTypes": Sequence[AlarmTypeType],
         "ChildrenOfAlarmName": str,
@@ -414,14 +420,21 @@
 DisableInsightRulesInputRequestTypeDef = TypedDict(
     "DisableInsightRulesInputRequestTypeDef",
     {
         "RuleNames": Sequence[str],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableAlarmActionsInputRequestTypeDef = TypedDict(
     "EnableAlarmActionsInputRequestTypeDef",
     {
         "AlarmNames": Sequence[str],
     },
 )
 
@@ -435,14 +448,24 @@
 GetDashboardInputRequestTypeDef = TypedDict(
     "GetDashboardInputRequestTypeDef",
     {
         "DashboardName": str,
     },
 )
 
+GetDashboardOutputTypeDef = TypedDict(
+    "GetDashboardOutputTypeDef",
+    {
+        "DashboardArn": str,
+        "DashboardBody": str,
+        "DashboardName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetInsightRuleReportInputRequestTypeDef = TypedDict(
     "_RequiredGetInsightRuleReportInputRequestTypeDef",
     {
         "RuleName": str,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "Period": int,
@@ -513,14 +536,15 @@
     },
 )
 
 MetricStreamFilterTypeDef = TypedDict(
     "MetricStreamFilterTypeDef",
     {
         "Namespace": str,
+        "MetricNames": List[str],
     },
     total=False,
 )
 
 _RequiredGetMetricWidgetImageInputRequestTypeDef = TypedDict(
     "_RequiredGetMetricWidgetImageInputRequestTypeDef",
     {
@@ -537,22 +561,39 @@
 
 class GetMetricWidgetImageInputRequestTypeDef(
     _RequiredGetMetricWidgetImageInputRequestTypeDef,
     _OptionalGetMetricWidgetImageInputRequestTypeDef,
 ):
     pass
 
+GetMetricWidgetImageOutputTypeDef = TypedDict(
+    "GetMetricWidgetImageOutputTypeDef",
+    {
+        "MetricWidgetImage": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InsightRuleContributorDatapointTypeDef = TypedDict(
     "InsightRuleContributorDatapointTypeDef",
     {
         "Timestamp": datetime,
         "ApproximateValue": float,
     },
 )
 
+ListDashboardsInputListDashboardsPaginateTypeDef = TypedDict(
+    "ListDashboardsInputListDashboardsPaginateTypeDef",
+    {
+        "DashboardNamePrefix": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDashboardsInputRequestTypeDef = TypedDict(
     "ListDashboardsInputRequestTypeDef",
     {
         "DashboardNamePrefix": str,
         "NextToken": str,
     },
     total=False,
@@ -639,34 +680,48 @@
     "MetricStreamStatisticsMetricTypeDef",
     {
         "Namespace": str,
         "MetricName": str,
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
 PutDashboardInputRequestTypeDef = TypedDict(
     "PutDashboardInputRequestTypeDef",
     {
         "DashboardName": str,
         "DashboardBody": str,
     },
 )
 
-ServiceResourceAlarmRequestTypeDef = TypedDict(
-    "ServiceResourceAlarmRequestTypeDef",
+PutMetricStreamOutputTypeDef = TypedDict(
+    "PutMetricStreamOutputTypeDef",
     {
-        "name": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ServiceResourceMetricRequestTypeDef = TypedDict(
-    "ServiceResourceMetricRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "namespace": str,
-        "name": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 _RequiredSetAlarmStateInputAlarmSetStateTypeDef = TypedDict(
     "_RequiredSetAlarmStateInputAlarmSetStateTypeDef",
     {
         "StateValue": StateValueType,
@@ -725,14 +780,23 @@
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+DescribeAlarmHistoryOutputTypeDef = TypedDict(
+    "DescribeAlarmHistoryOutputTypeDef",
+    {
+        "AlarmHistoryItems": List[AlarmHistoryItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AnomalyDetectorConfigurationTypeDef = TypedDict(
     "AnomalyDetectorConfigurationTypeDef",
     {
         "ExcludedTimeRanges": List[RangeTypeDef],
         "MetricTimezone": str,
     },
     total=False,
@@ -759,14 +823,26 @@
 
 class DescribeAlarmsForMetricInputRequestTypeDef(
     _RequiredDescribeAlarmsForMetricInputRequestTypeDef,
     _OptionalDescribeAlarmsForMetricInputRequestTypeDef,
 ):
     pass
 
+DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef = TypedDict(
+    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
+    {
+        "Namespace": str,
+        "MetricName": str,
+        "Dimensions": Sequence[DimensionTypeDef],
+        "AnomalyDetectorTypes": Sequence[AnomalyDetectorTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAnomalyDetectorsInputRequestTypeDef = TypedDict(
     "DescribeAnomalyDetectorsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Namespace": str,
         "MetricName": str,
@@ -844,162 +920,70 @@
         "MetricName": str,
         "Dimensions": Sequence[DimensionTypeDef],
         "Stat": str,
     },
     total=False,
 )
 
-DeleteInsightRulesOutputTypeDef = TypedDict(
-    "DeleteInsightRulesOutputTypeDef",
-    {
-        "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAlarmHistoryOutputTypeDef = TypedDict(
-    "DescribeAlarmHistoryOutputTypeDef",
+ListDashboardsOutputTypeDef = TypedDict(
+    "ListDashboardsOutputTypeDef",
     {
-        "AlarmHistoryItems": List[AlarmHistoryItemTypeDef],
+        "DashboardEntries": List[DashboardEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisableInsightRulesOutputTypeDef = TypedDict(
-    "DisableInsightRulesOutputTypeDef",
-    {
-        "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EnableInsightRulesOutputTypeDef = TypedDict(
-    "EnableInsightRulesOutputTypeDef",
-    {
-        "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDashboardOutputTypeDef = TypedDict(
-    "GetDashboardOutputTypeDef",
+PutDashboardOutputTypeDef = TypedDict(
+    "PutDashboardOutputTypeDef",
     {
-        "DashboardArn": str,
-        "DashboardBody": str,
-        "DashboardName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DashboardValidationMessages": List[DashboardValidationMessageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMetricStatisticsOutputTypeDef = TypedDict(
     "GetMetricStatisticsOutputTypeDef",
     {
         "Label": str,
         "Datapoints": List[DatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetMetricWidgetImageOutputTypeDef = TypedDict(
-    "GetMetricWidgetImageOutputTypeDef",
+DeleteInsightRulesOutputTypeDef = TypedDict(
+    "DeleteInsightRulesOutputTypeDef",
     {
-        "MetricWidgetImage": bytes,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Failures": List[PartialFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListDashboardsOutputTypeDef = TypedDict(
-    "ListDashboardsOutputTypeDef",
+DisableInsightRulesOutputTypeDef = TypedDict(
+    "DisableInsightRulesOutputTypeDef",
     {
-        "DashboardEntries": List[DashboardEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Failures": List[PartialFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutDashboardOutputTypeDef = TypedDict(
-    "PutDashboardOutputTypeDef",
+EnableInsightRulesOutputTypeDef = TypedDict(
+    "EnableInsightRulesOutputTypeDef",
     {
-        "DashboardValidationMessages": List[DashboardValidationMessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Failures": List[PartialFailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutManagedInsightRulesOutputTypeDef = TypedDict(
     "PutManagedInsightRulesOutputTypeDef",
     {
         "Failures": List[PartialFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutMetricStreamOutputTypeDef = TypedDict(
-    "PutMetricStreamOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef = TypedDict(
-    "DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef",
-    {
-        "AlarmName": str,
-        "AlarmTypes": Sequence[AlarmTypeType],
-        "HistoryItemType": HistoryItemTypeType,
-        "StartDate": Union[datetime, str],
-        "EndDate": Union[datetime, str],
-        "ScanBy": ScanByType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeAlarmsInputDescribeAlarmsPaginateTypeDef = TypedDict(
-    "DescribeAlarmsInputDescribeAlarmsPaginateTypeDef",
-    {
-        "AlarmNames": Sequence[str],
-        "AlarmNamePrefix": str,
-        "AlarmTypes": Sequence[AlarmTypeType],
-        "ChildrenOfAlarmName": str,
-        "ParentsOfAlarmName": str,
-        "StateValue": StateValueType,
-        "ActionPrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef = TypedDict(
-    "DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef",
-    {
-        "Namespace": str,
-        "MetricName": str,
-        "Dimensions": Sequence[DimensionTypeDef],
-        "AnomalyDetectorTypes": Sequence[AnomalyDetectorTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDashboardsInputListDashboardsPaginateTypeDef = TypedDict(
-    "ListDashboardsInputListDashboardsPaginateTypeDef",
-    {
-        "DashboardNamePrefix": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeAlarmsInputAlarmExistsWaitTypeDef = TypedDict(
     "DescribeAlarmsInputAlarmExistsWaitTypeDef",
     {
         "AlarmNames": Sequence[str],
         "AlarmNamePrefix": str,
@@ -1033,28 +1017,28 @@
 )
 
 DescribeInsightRulesOutputTypeDef = TypedDict(
     "DescribeInsightRulesOutputTypeDef",
     {
         "NextToken": str,
         "InsightRules": List[InsightRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMetricsInputListMetricsPaginateTypeDef = TypedDict(
     "ListMetricsInputListMetricsPaginateTypeDef",
     {
         "Namespace": str,
         "MetricName": str,
         "Dimensions": Sequence[DimensionFilterTypeDef],
         "RecentlyActive": Literal["PT3H"],
         "IncludeLinkedAccounts": bool,
         "OwningAccount": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListMetricsInputRequestTypeDef = TypedDict(
     "ListMetricsInputRequestTypeDef",
     {
@@ -1092,23 +1076,23 @@
 )
 
 ListMetricStreamsOutputTypeDef = TypedDict(
     "ListMetricStreamsOutputTypeDef",
     {
         "NextToken": str,
         "Entries": List[MetricStreamEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredManagedRuleTypeDef = TypedDict(
     "_RequiredManagedRuleTypeDef",
     {
         "TemplateName": str,
@@ -1227,15 +1211,15 @@
 
 ListMetricsOutputTypeDef = TypedDict(
     "ListMetricsOutputTypeDef",
     {
         "Metrics": List[MetricTypeDef],
         "NextToken": str,
         "OwningAccounts": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricStatTypeDef = TypedDict(
     "_RequiredMetricStatTypeDef",
     {
         "Metric": MetricTypeDef,
@@ -1256,28 +1240,28 @@
 
 GetMetricDataOutputTypeDef = TypedDict(
     "GetMetricDataOutputTypeDef",
     {
         "MetricDataResults": List[MetricDataResultTypeDef],
         "NextToken": str,
         "Messages": List[MessageDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightRuleReportOutputTypeDef = TypedDict(
     "GetInsightRuleReportOutputTypeDef",
     {
         "KeyLabels": List[str],
         "AggregationStatistic": str,
         "AggregateValue": float,
         "ApproximateUniqueCount": int,
         "Contributors": List[InsightRuleContributorTypeDef],
         "MetricDatapoints": List[InsightRuleMetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutManagedInsightRulesInputRequestTypeDef = TypedDict(
     "PutManagedInsightRulesInputRequestTypeDef",
     {
         "ManagedRules": Sequence[ManagedRuleTypeDef],
@@ -1285,15 +1269,15 @@
 )
 
 ListManagedInsightRulesOutputTypeDef = TypedDict(
     "ListManagedInsightRulesOutputTypeDef",
     {
         "ManagedRules": List[ManagedRuleDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutMetricDataInputRequestTypeDef = TypedDict(
     "PutMetricDataInputRequestTypeDef",
     {
         "Namespace": str,
@@ -1312,15 +1296,15 @@
         "RoleArn": str,
         "State": str,
         "CreationDate": datetime,
         "LastUpdateDate": datetime,
         "OutputFormat": MetricStreamOutputFormatType,
         "StatisticsConfigurations": List[MetricStreamStatisticsConfigurationTypeDef],
         "IncludeLinkedAccountsMetrics": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutMetricStreamInputRequestTypeDef = TypedDict(
     "_RequiredPutMetricStreamInputRequestTypeDef",
     {
         "Name": str,
@@ -1377,15 +1361,15 @@
     },
 )
 _OptionalGetMetricDataInputGetMetricDataPaginateTypeDef = TypedDict(
     "_OptionalGetMetricDataInputGetMetricDataPaginateTypeDef",
     {
         "ScanBy": ScanByType,
         "LabelOptions": LabelOptionsTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetMetricDataInputGetMetricDataPaginateTypeDef(
     _RequiredGetMetricDataInputGetMetricDataPaginateTypeDef,
     _OptionalGetMetricDataInputGetMetricDataPaginateTypeDef,
@@ -1537,25 +1521,25 @@
 ):
     pass
 
 DescribeAlarmsForMetricOutputTypeDef = TypedDict(
     "DescribeAlarmsForMetricOutputTypeDef",
     {
         "MetricAlarms": List[MetricAlarmTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAlarmsOutputTypeDef = TypedDict(
     "DescribeAlarmsOutputTypeDef",
     {
         "CompositeAlarms": List[CompositeAlarmTypeDef],
         "MetricAlarms": List[MetricAlarmTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnomalyDetectorTypeDef = TypedDict(
     "AnomalyDetectorTypeDef",
     {
         "Namespace": str,
@@ -1598,10 +1582,10 @@
 )
 
 DescribeAnomalyDetectorsOutputTypeDef = TypedDict(
     "DescribeAnomalyDetectorsOutputTypeDef",
     {
         "AnomalyDetectors": List[AnomalyDetectorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/waiter.py` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch/waiter.pyi` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/PKG-INFO` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudwatch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudWatch 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudWatch 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudwatch"></a>
 
 # types-aiobotocore-cloudwatch
 
 [![PyPI - types-aiobotocore-cloudwatch](https://img.shields.io/pypi/v/types-aiobotocore-cloudwatch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudwatch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudwatch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudwatch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudwatch?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudwatch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudWatch 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
+[aiobotocore.CloudWatch 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudwatch.html#CloudWatch)
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
 [types-aiobotocore-cloudwatch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudwatch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -459,77 +459,75 @@
     DashboardEntryTypeDef,
     DashboardValidationMessageTypeDef,
     DatapointTypeDef,
     DeleteAlarmsInputRequestTypeDef,
     DeleteDashboardsInputRequestTypeDef,
     DeleteInsightRulesInputRequestTypeDef,
     PartialFailureTypeDef,
-    ResponseMetadataTypeDef,
     DeleteMetricStreamInputRequestTypeDef,
     DescribeAlarmHistoryInputAlarmDescribeHistoryTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef,
     DescribeAlarmHistoryInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeAlarmsInputDescribeAlarmsPaginateTypeDef,
     DescribeAlarmsInputRequestTypeDef,
     DescribeInsightRulesInputRequestTypeDef,
     InsightRuleTypeDef,
     DimensionFilterTypeDef,
     DisableAlarmActionsInputRequestTypeDef,
     DisableInsightRulesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableAlarmActionsInputRequestTypeDef,
     EnableInsightRulesInputRequestTypeDef,
     GetDashboardInputRequestTypeDef,
+    GetDashboardOutputTypeDef,
     GetInsightRuleReportInputRequestTypeDef,
     InsightRuleMetricDatapointTypeDef,
     LabelOptionsTypeDef,
     MessageDataTypeDef,
     GetMetricStreamInputRequestTypeDef,
     MetricStreamFilterTypeDef,
     GetMetricWidgetImageInputRequestTypeDef,
+    GetMetricWidgetImageOutputTypeDef,
     InsightRuleContributorDatapointTypeDef,
+    ListDashboardsInputListDashboardsPaginateTypeDef,
     ListDashboardsInputRequestTypeDef,
     ListManagedInsightRulesInputRequestTypeDef,
     ListMetricStreamsInputRequestTypeDef,
     MetricStreamEntryTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     TagTypeDef,
     ManagedRuleStateTypeDef,
     StatisticSetTypeDef,
     MetricStreamStatisticsMetricTypeDef,
+    PaginatorConfigTypeDef,
     PutDashboardInputRequestTypeDef,
-    ServiceResourceAlarmRequestTypeDef,
-    ServiceResourceMetricRequestTypeDef,
+    PutMetricStreamOutputTypeDef,
+    ResponseMetadataTypeDef,
     SetAlarmStateInputAlarmSetStateTypeDef,
     SetAlarmStateInputRequestTypeDef,
     StartMetricStreamsInputRequestTypeDef,
     StopMetricStreamsInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    DescribeAlarmHistoryOutputTypeDef,
     AnomalyDetectorConfigurationTypeDef,
     DescribeAlarmsForMetricInputRequestTypeDef,
+    DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef,
     DescribeAnomalyDetectorsInputRequestTypeDef,
     GetMetricStatisticsInputMetricGetStatisticsTypeDef,
     GetMetricStatisticsInputRequestTypeDef,
     MetricTypeDef,
     SingleMetricAnomalyDetectorTypeDef,
+    ListDashboardsOutputTypeDef,
+    PutDashboardOutputTypeDef,
+    GetMetricStatisticsOutputTypeDef,
     DeleteInsightRulesOutputTypeDef,
-    DescribeAlarmHistoryOutputTypeDef,
     DisableInsightRulesOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     EnableInsightRulesOutputTypeDef,
-    GetDashboardOutputTypeDef,
-    GetMetricStatisticsOutputTypeDef,
-    GetMetricWidgetImageOutputTypeDef,
-    ListDashboardsOutputTypeDef,
-    PutDashboardOutputTypeDef,
     PutManagedInsightRulesOutputTypeDef,
-    PutMetricStreamOutputTypeDef,
-    DescribeAlarmHistoryInputDescribeAlarmHistoryPaginateTypeDef,
-    DescribeAlarmsInputDescribeAlarmsPaginateTypeDef,
-    DescribeAnomalyDetectorsInputDescribeAnomalyDetectorsPaginateTypeDef,
-    ListDashboardsInputListDashboardsPaginateTypeDef,
     DescribeAlarmsInputAlarmExistsWaitTypeDef,
     DescribeAlarmsInputCompositeAlarmExistsWaitTypeDef,
     DescribeInsightRulesOutputTypeDef,
     ListMetricsInputListMetricsPaginateTypeDef,
     ListMetricsInputRequestTypeDef,
     MetricDataResultTypeDef,
     InsightRuleContributorTypeDef,
@@ -574,43 +572,43 @@
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

### Comparing `types-aiobotocore-cloudwatch-2.5.0.post1/types_aiobotocore_cloudwatch.egg-info/SOURCES.txt` & `types-aiobotocore-cloudwatch-2.5.1/types_aiobotocore_cloudwatch.egg-info/SOURCES.txt`

 * *Files identical despite different names*

