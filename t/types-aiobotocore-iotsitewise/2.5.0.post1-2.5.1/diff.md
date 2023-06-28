# Comparing `tmp/types-aiobotocore-iotsitewise-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotsitewise-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotsitewise-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:47 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotsitewise-2.5.1.tar", last modified: Wed Jun 28 01:43:39 2023, max compression
```

## Comparing `types-aiobotocore-iotsitewise-2.5.0.post1.tar` & `types-aiobotocore-iotsitewise-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:47.527305 types-aiobotocore-iotsitewise-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    28990 2023-03-11 12:26:47.527305 types-aiobotocore-iotsitewise-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    27403 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:47.527305 types-aiobotocore-iotsitewise-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:47.527305 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/
--rw-r--r--   0 runner    (1001) docker     (123)     5322 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5321 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    65838 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    65733 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15187 2023-03-11 12:16:28.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    15185 2023-03-11 12:16:28.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    22891 2023-03-11 12:16:28.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    22871 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   105690 2023-03-11 12:16:30.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   105489 2023-03-11 12:16:29.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:26.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     6730 2023-03-11 12:16:28.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     6724 2023-03-11 12:16:28.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:47.527305 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    28990 2023-03-11 12:26:47.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      970 2023-03-11 12:26:47.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:47.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:47.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:47.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:47.000000 types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:39.738156 types-aiobotocore-iotsitewise-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    28986 2023-06-28 01:43:39.738156 types-aiobotocore-iotsitewise-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    27405 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:39.738156 types-aiobotocore-iotsitewise-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:39.734156 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/
+-rw-r--r--   0 runner    (1001) docker     (123)     5322 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5321 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    65838 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    65733 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15396 2023-06-28 01:33:06.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15394 2023-06-28 01:33:06.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    22818 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22798 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   105898 2023-06-28 01:33:09.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   105697 2023-06-28 01:33:07.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:05.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6730 2023-06-28 01:33:06.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6724 2023-06-28 01:33:06.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:39.738156 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    28986 2023-06-28 01:43:39.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-28 01:43:39.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:39.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:39.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:39.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:39.000000 types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/LICENSE` & `types-aiobotocore-iotsitewise-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotsitewise-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotsitewise
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTSiteWise 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTSiteWise 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotsitewise"></a>
 
 # types-aiobotocore-iotsitewise
 
 [![PyPI - types-aiobotocore-iotsitewise](https://img.shields.io/pypi/v/types-aiobotocore-iotsitewise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsitewise)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotsitewise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsitewise)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotsitewise?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotsitewise)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTSiteWise 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
+[aiobotocore.IoTSiteWise 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
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
 [types-aiobotocore-iotsitewise docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/).
 
 See how it helps to find and fix potential bugs:
 
@@ -484,32 +484,36 @@
     PropertyNotificationTypeDef,
     TimeInNanosTypeDef,
     VariantTypeDef,
     AssociateAssetsRequestRequestTypeDef,
     AssociateTimeSeriesToAssetPropertyRequestRequestTypeDef,
     AttributeTypeDef,
     BatchAssociateProjectAssetsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BatchDisassociateProjectAssetsRequestRequestTypeDef,
     BatchGetAssetPropertyAggregatesEntryTypeDef,
     BatchGetAssetPropertyAggregatesErrorEntryTypeDef,
     BatchGetAssetPropertyAggregatesErrorInfoTypeDef,
     BatchGetAssetPropertyValueEntryTypeDef,
     BatchGetAssetPropertyValueErrorEntryTypeDef,
     BatchGetAssetPropertyValueErrorInfoTypeDef,
     BatchGetAssetPropertyValueHistoryEntryTypeDef,
     BatchGetAssetPropertyValueHistoryErrorEntryTypeDef,
     BatchGetAssetPropertyValueHistoryErrorInfoTypeDef,
     ConfigurationErrorDetailsTypeDef,
+    CreateAccessPolicyResponseTypeDef,
     CreateAssetRequestRequestTypeDef,
     ErrorReportLocationTypeDef,
     FileTypeDef,
+    CreateBulkImportJobResponseTypeDef,
     CreateDashboardRequestRequestTypeDef,
+    CreateDashboardResponseTypeDef,
+    CreateGatewayResponseTypeDef,
     ImageFileTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
     CsvTypeDef,
     CustomerManagedS3StorageTypeDef,
     DashboardSummaryTypeDef,
     DeleteAccessPolicyRequestRequestTypeDef,
     DeleteAssetModelRequestRequestTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeleteDashboardRequestRequestTypeDef,
@@ -520,93 +524,106 @@
     DescribeAccessPolicyRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeAssetModelRequestRequestTypeDef,
     DescribeAssetPropertyRequestRequestTypeDef,
     DescribeAssetRequestRequestTypeDef,
     DescribeBulkImportJobRequestRequestTypeDef,
     DescribeDashboardRequestRequestTypeDef,
+    DescribeDashboardResponseTypeDef,
     DescribeGatewayCapabilityConfigurationRequestRequestTypeDef,
+    DescribeGatewayCapabilityConfigurationResponseTypeDef,
     DescribeGatewayRequestRequestTypeDef,
     GatewayCapabilitySummaryTypeDef,
     LoggingOptionsTypeDef,
     DescribePortalRequestRequestTypeDef,
     ImageLocationTypeDef,
     DescribeProjectRequestRequestTypeDef,
+    DescribeProjectResponseTypeDef,
     RetentionPeriodTypeDef,
     DescribeTimeSeriesRequestRequestTypeDef,
+    DescribeTimeSeriesResponseTypeDef,
     DetailedErrorTypeDef,
     DisassociateAssetsRequestRequestTypeDef,
     DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     VariableValueTypeDef,
     ForwardingConfigTypeDef,
     GreengrassTypeDef,
     GreengrassV2TypeDef,
-    PaginatorConfigTypeDef,
+    GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
     GetAssetPropertyAggregatesRequestRequestTypeDef,
+    GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef,
     GetAssetPropertyValueHistoryRequestRequestTypeDef,
     GetAssetPropertyValueRequestRequestTypeDef,
+    GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
     GetInterpolatedAssetPropertyValuesRequestRequestTypeDef,
     GroupIdentityTypeDef,
     IAMRoleIdentityTypeDef,
     IAMUserIdentityTypeDef,
     UserIdentityTypeDef,
     JobSummaryTypeDef,
+    ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef,
     ListAccessPoliciesRequestRequestTypeDef,
+    ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
     ListAssetModelPropertiesRequestRequestTypeDef,
+    ListAssetModelsRequestListAssetModelsPaginateTypeDef,
     ListAssetModelsRequestRequestTypeDef,
+    ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
     ListAssetPropertiesRequestRequestTypeDef,
+    ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
     ListAssetRelationshipsRequestRequestTypeDef,
+    ListAssetsRequestListAssetsPaginateTypeDef,
     ListAssetsRequestRequestTypeDef,
+    ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
     ListAssociatedAssetsRequestRequestTypeDef,
+    ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef,
     ListBulkImportJobsRequestRequestTypeDef,
+    ListDashboardsRequestListDashboardsPaginateTypeDef,
     ListDashboardsRequestRequestTypeDef,
+    ListGatewaysRequestListGatewaysPaginateTypeDef,
     ListGatewaysRequestRequestTypeDef,
+    ListPortalsRequestListPortalsPaginateTypeDef,
     ListPortalsRequestRequestTypeDef,
+    ListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
     ListProjectAssetsRequestRequestTypeDef,
+    ListProjectAssetsResponseTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTimeSeriesRequestListTimeSeriesPaginateTypeDef,
     ListTimeSeriesRequestRequestTypeDef,
     TimeSeriesSummaryTypeDef,
     MetricProcessingConfigTypeDef,
     TumblingWindowTypeDef,
     MonitorErrorDetailsTypeDef,
+    PaginatorConfigTypeDef,
     PortalResourceTypeDef,
     ProjectResourceTypeDef,
     PutDefaultEncryptionConfigurationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssetPropertyRequestRequestTypeDef,
     UpdateAssetRequestRequestTypeDef,
     UpdateDashboardRequestRequestTypeDef,
     UpdateGatewayCapabilityConfigurationRequestRequestTypeDef,
+    UpdateGatewayCapabilityConfigurationResponseTypeDef,
     UpdateGatewayRequestRequestTypeDef,
     UpdateProjectRequestRequestTypeDef,
     AggregatedValueTypeDef,
+    BatchAssociateProjectAssetsResponseTypeDef,
+    BatchDisassociateProjectAssetsResponseTypeDef,
     AssetRelationshipSummaryTypeDef,
     AssetPropertySummaryTypeDef,
     AssetPropertyTypeDef,
     BatchPutAssetPropertyErrorTypeDef,
     AssetPropertyValueTypeDef,
     InterpolatedAssetPropertyValueTypeDef,
-    BatchAssociateProjectAssetsResponseTypeDef,
-    BatchDisassociateProjectAssetsResponseTypeDef,
-    CreateAccessPolicyResponseTypeDef,
-    CreateBulkImportJobResponseTypeDef,
-    CreateDashboardResponseTypeDef,
-    CreateGatewayResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    DescribeDashboardResponseTypeDef,
-    DescribeGatewayCapabilityConfigurationResponseTypeDef,
-    DescribeProjectResponseTypeDef,
-    DescribeTimeSeriesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListProjectAssetsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateGatewayCapabilityConfigurationResponseTypeDef,
     BatchGetAssetPropertyAggregatesRequestRequestTypeDef,
     BatchGetAssetPropertyAggregatesSkippedEntryTypeDef,
     BatchGetAssetPropertyValueRequestRequestTypeDef,
     BatchGetAssetPropertyValueSkippedEntryTypeDef,
     BatchGetAssetPropertyValueHistoryRequestRequestTypeDef,
     BatchGetAssetPropertyValueHistorySkippedEntryTypeDef,
     ConfigurationStatusTypeDef,
@@ -624,31 +641,14 @@
     DescribeLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     ErrorDetailsTypeDef,
     ExpressionVariableTypeDef,
     MeasurementProcessingConfigTypeDef,
     TransformProcessingConfigTypeDef,
     GatewayPlatformTypeDef,
-    GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-    GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef,
-    GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-    ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef,
-    ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-    ListAssetModelsRequestListAssetModelsPaginateTypeDef,
-    ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-    ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-    ListAssetsRequestListAssetsPaginateTypeDef,
-    ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-    ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef,
-    ListDashboardsRequestListDashboardsPaginateTypeDef,
-    ListGatewaysRequestListGatewaysPaginateTypeDef,
-    ListPortalsRequestListPortalsPaginateTypeDef,
-    ListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListTimeSeriesRequestListTimeSeriesPaginateTypeDef,
     IdentityTypeDef,
     ListBulkImportJobsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListTimeSeriesResponseTypeDef,
     MetricWindowTypeDef,
     PortalStatusTypeDef,
     ResourceTypeDef,
@@ -734,43 +734,43 @@
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/README.md` & `types-aiobotocore-iotsitewise-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotsitewise"></a>
 
 # types-aiobotocore-iotsitewise
 
 [![PyPI - types-aiobotocore-iotsitewise](https://img.shields.io/pypi/v/types-aiobotocore-iotsitewise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsitewise)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotsitewise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsitewise)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotsitewise?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotsitewise)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTSiteWise 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
+[aiobotocore.IoTSiteWise 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
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
 [types-aiobotocore-iotsitewise docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/).
 
 See how it helps to find and fix potential bugs:
 
@@ -451,32 +451,36 @@
     PropertyNotificationTypeDef,
     TimeInNanosTypeDef,
     VariantTypeDef,
     AssociateAssetsRequestRequestTypeDef,
     AssociateTimeSeriesToAssetPropertyRequestRequestTypeDef,
     AttributeTypeDef,
     BatchAssociateProjectAssetsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BatchDisassociateProjectAssetsRequestRequestTypeDef,
     BatchGetAssetPropertyAggregatesEntryTypeDef,
     BatchGetAssetPropertyAggregatesErrorEntryTypeDef,
     BatchGetAssetPropertyAggregatesErrorInfoTypeDef,
     BatchGetAssetPropertyValueEntryTypeDef,
     BatchGetAssetPropertyValueErrorEntryTypeDef,
     BatchGetAssetPropertyValueErrorInfoTypeDef,
     BatchGetAssetPropertyValueHistoryEntryTypeDef,
     BatchGetAssetPropertyValueHistoryErrorEntryTypeDef,
     BatchGetAssetPropertyValueHistoryErrorInfoTypeDef,
     ConfigurationErrorDetailsTypeDef,
+    CreateAccessPolicyResponseTypeDef,
     CreateAssetRequestRequestTypeDef,
     ErrorReportLocationTypeDef,
     FileTypeDef,
+    CreateBulkImportJobResponseTypeDef,
     CreateDashboardRequestRequestTypeDef,
+    CreateDashboardResponseTypeDef,
+    CreateGatewayResponseTypeDef,
     ImageFileTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
     CsvTypeDef,
     CustomerManagedS3StorageTypeDef,
     DashboardSummaryTypeDef,
     DeleteAccessPolicyRequestRequestTypeDef,
     DeleteAssetModelRequestRequestTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeleteDashboardRequestRequestTypeDef,
@@ -487,93 +491,106 @@
     DescribeAccessPolicyRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeAssetModelRequestRequestTypeDef,
     DescribeAssetPropertyRequestRequestTypeDef,
     DescribeAssetRequestRequestTypeDef,
     DescribeBulkImportJobRequestRequestTypeDef,
     DescribeDashboardRequestRequestTypeDef,
+    DescribeDashboardResponseTypeDef,
     DescribeGatewayCapabilityConfigurationRequestRequestTypeDef,
+    DescribeGatewayCapabilityConfigurationResponseTypeDef,
     DescribeGatewayRequestRequestTypeDef,
     GatewayCapabilitySummaryTypeDef,
     LoggingOptionsTypeDef,
     DescribePortalRequestRequestTypeDef,
     ImageLocationTypeDef,
     DescribeProjectRequestRequestTypeDef,
+    DescribeProjectResponseTypeDef,
     RetentionPeriodTypeDef,
     DescribeTimeSeriesRequestRequestTypeDef,
+    DescribeTimeSeriesResponseTypeDef,
     DetailedErrorTypeDef,
     DisassociateAssetsRequestRequestTypeDef,
     DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     VariableValueTypeDef,
     ForwardingConfigTypeDef,
     GreengrassTypeDef,
     GreengrassV2TypeDef,
-    PaginatorConfigTypeDef,
+    GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
     GetAssetPropertyAggregatesRequestRequestTypeDef,
+    GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef,
     GetAssetPropertyValueHistoryRequestRequestTypeDef,
     GetAssetPropertyValueRequestRequestTypeDef,
+    GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
     GetInterpolatedAssetPropertyValuesRequestRequestTypeDef,
     GroupIdentityTypeDef,
     IAMRoleIdentityTypeDef,
     IAMUserIdentityTypeDef,
     UserIdentityTypeDef,
     JobSummaryTypeDef,
+    ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef,
     ListAccessPoliciesRequestRequestTypeDef,
+    ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
     ListAssetModelPropertiesRequestRequestTypeDef,
+    ListAssetModelsRequestListAssetModelsPaginateTypeDef,
     ListAssetModelsRequestRequestTypeDef,
+    ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
     ListAssetPropertiesRequestRequestTypeDef,
+    ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
     ListAssetRelationshipsRequestRequestTypeDef,
+    ListAssetsRequestListAssetsPaginateTypeDef,
     ListAssetsRequestRequestTypeDef,
+    ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
     ListAssociatedAssetsRequestRequestTypeDef,
+    ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef,
     ListBulkImportJobsRequestRequestTypeDef,
+    ListDashboardsRequestListDashboardsPaginateTypeDef,
     ListDashboardsRequestRequestTypeDef,
+    ListGatewaysRequestListGatewaysPaginateTypeDef,
     ListGatewaysRequestRequestTypeDef,
+    ListPortalsRequestListPortalsPaginateTypeDef,
     ListPortalsRequestRequestTypeDef,
+    ListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
     ListProjectAssetsRequestRequestTypeDef,
+    ListProjectAssetsResponseTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTimeSeriesRequestListTimeSeriesPaginateTypeDef,
     ListTimeSeriesRequestRequestTypeDef,
     TimeSeriesSummaryTypeDef,
     MetricProcessingConfigTypeDef,
     TumblingWindowTypeDef,
     MonitorErrorDetailsTypeDef,
+    PaginatorConfigTypeDef,
     PortalResourceTypeDef,
     ProjectResourceTypeDef,
     PutDefaultEncryptionConfigurationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssetPropertyRequestRequestTypeDef,
     UpdateAssetRequestRequestTypeDef,
     UpdateDashboardRequestRequestTypeDef,
     UpdateGatewayCapabilityConfigurationRequestRequestTypeDef,
+    UpdateGatewayCapabilityConfigurationResponseTypeDef,
     UpdateGatewayRequestRequestTypeDef,
     UpdateProjectRequestRequestTypeDef,
     AggregatedValueTypeDef,
+    BatchAssociateProjectAssetsResponseTypeDef,
+    BatchDisassociateProjectAssetsResponseTypeDef,
     AssetRelationshipSummaryTypeDef,
     AssetPropertySummaryTypeDef,
     AssetPropertyTypeDef,
     BatchPutAssetPropertyErrorTypeDef,
     AssetPropertyValueTypeDef,
     InterpolatedAssetPropertyValueTypeDef,
-    BatchAssociateProjectAssetsResponseTypeDef,
-    BatchDisassociateProjectAssetsResponseTypeDef,
-    CreateAccessPolicyResponseTypeDef,
-    CreateBulkImportJobResponseTypeDef,
-    CreateDashboardResponseTypeDef,
-    CreateGatewayResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    DescribeDashboardResponseTypeDef,
-    DescribeGatewayCapabilityConfigurationResponseTypeDef,
-    DescribeProjectResponseTypeDef,
-    DescribeTimeSeriesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListProjectAssetsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateGatewayCapabilityConfigurationResponseTypeDef,
     BatchGetAssetPropertyAggregatesRequestRequestTypeDef,
     BatchGetAssetPropertyAggregatesSkippedEntryTypeDef,
     BatchGetAssetPropertyValueRequestRequestTypeDef,
     BatchGetAssetPropertyValueSkippedEntryTypeDef,
     BatchGetAssetPropertyValueHistoryRequestRequestTypeDef,
     BatchGetAssetPropertyValueHistorySkippedEntryTypeDef,
     ConfigurationStatusTypeDef,
@@ -591,31 +608,14 @@
     DescribeLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     ErrorDetailsTypeDef,
     ExpressionVariableTypeDef,
     MeasurementProcessingConfigTypeDef,
     TransformProcessingConfigTypeDef,
     GatewayPlatformTypeDef,
-    GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-    GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef,
-    GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-    ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef,
-    ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-    ListAssetModelsRequestListAssetModelsPaginateTypeDef,
-    ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-    ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-    ListAssetsRequestListAssetsPaginateTypeDef,
-    ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-    ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef,
-    ListDashboardsRequestListDashboardsPaginateTypeDef,
-    ListGatewaysRequestListGatewaysPaginateTypeDef,
-    ListPortalsRequestListPortalsPaginateTypeDef,
-    ListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListTimeSeriesRequestListTimeSeriesPaginateTypeDef,
     IdentityTypeDef,
     ListBulkImportJobsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListTimeSeriesResponseTypeDef,
     MetricWindowTypeDef,
     PortalStatusTypeDef,
     ResourceTypeDef,
@@ -701,43 +701,43 @@
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/setup.py` & `types-aiobotocore-iotsitewise-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotsitewise.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotsitewise",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotsitewise"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTSiteWise 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTSiteWise 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/"
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/__init__.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/__init__.pyi` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/__main__.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTSiteWise 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTSiteWise 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise\nOther"
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/client.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/client.pyi` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/literals.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -245,14 +245,15 @@
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
@@ -331,14 +332,15 @@
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
@@ -349,14 +351,15 @@
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
@@ -392,14 +395,15 @@
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
@@ -418,16 +422,19 @@
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
@@ -511,15 +518,17 @@
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/literals.pyi` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -243,14 +243,15 @@
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
@@ -329,14 +330,15 @@
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
@@ -347,14 +349,15 @@
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
@@ -390,14 +393,15 @@
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
@@ -416,16 +420,19 @@
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
@@ -509,15 +516,17 @@
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/paginator.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -50,15 +50,15 @@
         list_project_assets_paginator: ListProjectAssetsPaginator = client.get_paginator("list_project_assets")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
         list_time_series_paginator: ListTimeSeriesPaginator = client.get_paginator("list_time_series")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AggregateTypeType,
     IdentityTypeType,
@@ -89,24 +89,19 @@
     ListPortalsResponseTypeDef,
     ListProjectAssetsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListTimeSeriesResponseTypeDef,
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
 
-
 __all__ = (
     "GetAssetPropertyAggregatesPaginator",
     "GetAssetPropertyValueHistoryPaginator",
     "GetInterpolatedAssetPropertyValuesPaginator",
     "ListAccessPoliciesPaginator",
     "ListAssetModelPropertiesPaginator",
     "ListAssetModelsPaginator",
@@ -119,25 +114,22 @@
     "ListGatewaysPaginator",
     "ListPortalsPaginator",
     "ListProjectAssetsPaginator",
     "ListProjectsPaginator",
     "ListTimeSeriesPaginator",
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
 class GetAssetPropertyAggregatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyAggregates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyaggregatespaginator)
     """
 
     def paginate(
@@ -148,22 +140,21 @@
         startDate: Union[datetime, str],
         endDate: Union[datetime, str],
         assetId: str = ...,
         propertyId: str = ...,
         propertyAlias: str = ...,
         qualities: Sequence[QualityType] = ...,
         timeOrdering: TimeOrderingType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAssetPropertyAggregatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyAggregates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyaggregatespaginator)
         """
 
-
 class GetAssetPropertyValueHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyValueHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyvaluehistorypaginator)
     """
 
     def paginate(
@@ -172,22 +163,21 @@
         assetId: str = ...,
         propertyId: str = ...,
         propertyAlias: str = ...,
         startDate: Union[datetime, str] = ...,
         endDate: Union[datetime, str] = ...,
         qualities: Sequence[QualityType] = ...,
         timeOrdering: TimeOrderingType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAssetPropertyValueHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyValueHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyvaluehistorypaginator)
         """
 
-
 class GetInterpolatedAssetPropertyValuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetInterpolatedAssetPropertyValues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getinterpolatedassetpropertyvaluespaginator)
     """
 
     def paginate(
@@ -200,259 +190,245 @@
         type: str,
         assetId: str = ...,
         propertyId: str = ...,
         propertyAlias: str = ...,
         startTimeOffsetInNanos: int = ...,
         endTimeOffsetInNanos: int = ...,
         intervalWindowInSeconds: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInterpolatedAssetPropertyValuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetInterpolatedAssetPropertyValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getinterpolatedassetpropertyvaluespaginator)
         """
 
-
 class ListAccessPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAccessPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listaccesspoliciespaginator)
     """
 
     def paginate(
         self,
         *,
         identityType: IdentityTypeType = ...,
         identityId: str = ...,
         resourceType: ResourceTypeType = ...,
         resourceId: str = ...,
         iamArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAccessPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listaccesspoliciespaginator)
         """
 
-
 class ListAssetModelPropertiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModelProperties)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelpropertiespaginator)
     """
 
     def paginate(
         self,
         *,
         assetModelId: str,
         filter: ListAssetModelPropertiesFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetModelPropertiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModelProperties.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelpropertiespaginator)
         """
 
-
 class ListAssetModelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetModelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelspaginator)
         """
 
-
 class ListAssetPropertiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetProperties)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetpropertiespaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str,
         filter: ListAssetPropertiesFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetPropertiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetProperties.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetpropertiespaginator)
         """
 
-
 class ListAssetRelationshipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetRelationships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetrelationshipspaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str,
         traversalType: Literal["PATH_TO_ROOT"],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetRelationshipsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetRelationships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetrelationshipspaginator)
         """
 
-
 class ListAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetspaginator)
     """
 
     def paginate(
         self,
         *,
         assetModelId: str = ...,
         filter: ListAssetsFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetspaginator)
         """
 
-
 class ListAssociatedAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssociatedAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassociatedassetspaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str,
         hierarchyId: str = ...,
         traversalDirection: TraversalDirectionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssociatedAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassociatedassetspaginator)
         """
 
-
 class ListBulkImportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListBulkImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listbulkimportjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filter: ListBulkImportJobsFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBulkImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListBulkImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listbulkimportjobspaginator)
         """
 
-
 class ListDashboardsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListDashboards)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listdashboardspaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDashboardsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListDashboards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listdashboardspaginator)
         """
 
-
 class ListGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listgatewayspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGatewaysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listgatewayspaginator)
         """
 
-
 class ListPortalsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListPortals)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listportalspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPortalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListPortals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listportalspaginator)
         """
 
-
 class ListProjectAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjectAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectassetspaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjectAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectassetspaginator)
         """
 
-
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, portalId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, portalId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectspaginator)
         """
 
-
 class ListTimeSeriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListTimeSeries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listtimeseriespaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str = ...,
         aliasPrefix: str = ...,
         timeSeriesType: ListTimeSeriesTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTimeSeriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListTimeSeries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listtimeseriespaginator)
         """
```

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/paginator.pyi` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -50,15 +50,15 @@
         list_project_assets_paginator: ListProjectAssetsPaginator = client.get_paginator("list_project_assets")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
         list_time_series_paginator: ListTimeSeriesPaginator = client.get_paginator("list_time_series")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AggregateTypeType,
     IdentityTypeType,
@@ -89,23 +89,20 @@
     ListPortalsResponseTypeDef,
     ListProjectAssetsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListTimeSeriesResponseTypeDef,
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
 
+
 __all__ = (
     "GetAssetPropertyAggregatesPaginator",
     "GetAssetPropertyValueHistoryPaginator",
     "GetInterpolatedAssetPropertyValuesPaginator",
     "ListAccessPoliciesPaginator",
     "ListAssetModelPropertiesPaginator",
     "ListAssetModelsPaginator",
@@ -118,22 +115,25 @@
     "ListGatewaysPaginator",
     "ListPortalsPaginator",
     "ListProjectAssetsPaginator",
     "ListProjectsPaginator",
     "ListTimeSeriesPaginator",
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
 class GetAssetPropertyAggregatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyAggregates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyaggregatespaginator)
     """
 
     def paginate(
@@ -144,21 +144,22 @@
         startDate: Union[datetime, str],
         endDate: Union[datetime, str],
         assetId: str = ...,
         propertyId: str = ...,
         propertyAlias: str = ...,
         qualities: Sequence[QualityType] = ...,
         timeOrdering: TimeOrderingType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAssetPropertyAggregatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyAggregates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyaggregatespaginator)
         """
 
+
 class GetAssetPropertyValueHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyValueHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyvaluehistorypaginator)
     """
 
     def paginate(
@@ -167,21 +168,22 @@
         assetId: str = ...,
         propertyId: str = ...,
         propertyAlias: str = ...,
         startDate: Union[datetime, str] = ...,
         endDate: Union[datetime, str] = ...,
         qualities: Sequence[QualityType] = ...,
         timeOrdering: TimeOrderingType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAssetPropertyValueHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetAssetPropertyValueHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getassetpropertyvaluehistorypaginator)
         """
 
+
 class GetInterpolatedAssetPropertyValuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetInterpolatedAssetPropertyValues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getinterpolatedassetpropertyvaluespaginator)
     """
 
     def paginate(
@@ -194,245 +196,259 @@
         type: str,
         assetId: str = ...,
         propertyId: str = ...,
         propertyAlias: str = ...,
         startTimeOffsetInNanos: int = ...,
         endTimeOffsetInNanos: int = ...,
         intervalWindowInSeconds: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInterpolatedAssetPropertyValuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.GetInterpolatedAssetPropertyValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#getinterpolatedassetpropertyvaluespaginator)
         """
 
+
 class ListAccessPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAccessPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listaccesspoliciespaginator)
     """
 
     def paginate(
         self,
         *,
         identityType: IdentityTypeType = ...,
         identityId: str = ...,
         resourceType: ResourceTypeType = ...,
         resourceId: str = ...,
         iamArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAccessPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listaccesspoliciespaginator)
         """
 
+
 class ListAssetModelPropertiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModelProperties)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelpropertiespaginator)
     """
 
     def paginate(
         self,
         *,
         assetModelId: str,
         filter: ListAssetModelPropertiesFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetModelPropertiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModelProperties.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelpropertiespaginator)
         """
 
+
 class ListAssetModelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetModelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetmodelspaginator)
         """
 
+
 class ListAssetPropertiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetProperties)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetpropertiespaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str,
         filter: ListAssetPropertiesFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetPropertiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetProperties.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetpropertiespaginator)
         """
 
+
 class ListAssetRelationshipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetRelationships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetrelationshipspaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str,
         traversalType: Literal["PATH_TO_ROOT"],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetRelationshipsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssetRelationships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetrelationshipspaginator)
         """
 
+
 class ListAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetspaginator)
     """
 
     def paginate(
         self,
         *,
         assetModelId: str = ...,
         filter: ListAssetsFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassetspaginator)
         """
 
+
 class ListAssociatedAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssociatedAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassociatedassetspaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str,
         hierarchyId: str = ...,
         traversalDirection: TraversalDirectionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListAssociatedAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listassociatedassetspaginator)
         """
 
+
 class ListBulkImportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListBulkImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listbulkimportjobspaginator)
     """
 
     def paginate(
         self,
         *,
         filter: ListBulkImportJobsFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBulkImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListBulkImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listbulkimportjobspaginator)
         """
 
+
 class ListDashboardsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListDashboards)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listdashboardspaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDashboardsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListDashboards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listdashboardspaginator)
         """
 
+
 class ListGatewaysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListGateways)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listgatewayspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGatewaysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListGateways.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listgatewayspaginator)
         """
 
+
 class ListPortalsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListPortals)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listportalspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPortalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListPortals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listportalspaginator)
         """
 
+
 class ListProjectAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjectAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectassetspaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjectAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectassetspaginator)
         """
 
+
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, portalId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, portalId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listprojectspaginator)
         """
 
+
 class ListTimeSeriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListTimeSeries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listtimeseriespaginator)
     """
 
     def paginate(
         self,
         *,
         assetId: str = ...,
         aliasPrefix: str = ...,
         timeSeriesType: ListTimeSeriesTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTimeSeriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise.Paginator.ListTimeSeries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/paginators/#listtimeseriespaginator)
         """
```

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/type_defs.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -77,32 +77,36 @@
     "PropertyNotificationTypeDef",
     "TimeInNanosTypeDef",
     "VariantTypeDef",
     "AssociateAssetsRequestRequestTypeDef",
     "AssociateTimeSeriesToAssetPropertyRequestRequestTypeDef",
     "AttributeTypeDef",
     "BatchAssociateProjectAssetsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDisassociateProjectAssetsRequestRequestTypeDef",
     "BatchGetAssetPropertyAggregatesEntryTypeDef",
     "BatchGetAssetPropertyAggregatesErrorEntryTypeDef",
     "BatchGetAssetPropertyAggregatesErrorInfoTypeDef",
     "BatchGetAssetPropertyValueEntryTypeDef",
     "BatchGetAssetPropertyValueErrorEntryTypeDef",
     "BatchGetAssetPropertyValueErrorInfoTypeDef",
     "BatchGetAssetPropertyValueHistoryEntryTypeDef",
     "BatchGetAssetPropertyValueHistoryErrorEntryTypeDef",
     "BatchGetAssetPropertyValueHistoryErrorInfoTypeDef",
     "ConfigurationErrorDetailsTypeDef",
+    "CreateAccessPolicyResponseTypeDef",
     "CreateAssetRequestRequestTypeDef",
     "ErrorReportLocationTypeDef",
     "FileTypeDef",
+    "CreateBulkImportJobResponseTypeDef",
     "CreateDashboardRequestRequestTypeDef",
+    "CreateDashboardResponseTypeDef",
+    "CreateGatewayResponseTypeDef",
     "ImageFileTypeDef",
     "CreateProjectRequestRequestTypeDef",
+    "CreateProjectResponseTypeDef",
     "CsvTypeDef",
     "CustomerManagedS3StorageTypeDef",
     "DashboardSummaryTypeDef",
     "DeleteAccessPolicyRequestRequestTypeDef",
     "DeleteAssetModelRequestRequestTypeDef",
     "DeleteAssetRequestRequestTypeDef",
     "DeleteDashboardRequestRequestTypeDef",
@@ -113,93 +117,106 @@
     "DescribeAccessPolicyRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeAssetModelRequestRequestTypeDef",
     "DescribeAssetPropertyRequestRequestTypeDef",
     "DescribeAssetRequestRequestTypeDef",
     "DescribeBulkImportJobRequestRequestTypeDef",
     "DescribeDashboardRequestRequestTypeDef",
+    "DescribeDashboardResponseTypeDef",
     "DescribeGatewayCapabilityConfigurationRequestRequestTypeDef",
+    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
     "DescribeGatewayRequestRequestTypeDef",
     "GatewayCapabilitySummaryTypeDef",
     "LoggingOptionsTypeDef",
     "DescribePortalRequestRequestTypeDef",
     "ImageLocationTypeDef",
     "DescribeProjectRequestRequestTypeDef",
+    "DescribeProjectResponseTypeDef",
     "RetentionPeriodTypeDef",
     "DescribeTimeSeriesRequestRequestTypeDef",
+    "DescribeTimeSeriesResponseTypeDef",
     "DetailedErrorTypeDef",
     "DisassociateAssetsRequestRequestTypeDef",
     "DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "VariableValueTypeDef",
     "ForwardingConfigTypeDef",
     "GreengrassTypeDef",
     "GreengrassV2TypeDef",
-    "PaginatorConfigTypeDef",
+    "GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
     "GetAssetPropertyAggregatesRequestRequestTypeDef",
+    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
     "GetAssetPropertyValueHistoryRequestRequestTypeDef",
     "GetAssetPropertyValueRequestRequestTypeDef",
+    "GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
     "GetInterpolatedAssetPropertyValuesRequestRequestTypeDef",
     "GroupIdentityTypeDef",
     "IAMRoleIdentityTypeDef",
     "IAMUserIdentityTypeDef",
     "UserIdentityTypeDef",
     "JobSummaryTypeDef",
+    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
     "ListAccessPoliciesRequestRequestTypeDef",
+    "ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
     "ListAssetModelPropertiesRequestRequestTypeDef",
+    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
     "ListAssetModelsRequestRequestTypeDef",
+    "ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
     "ListAssetPropertiesRequestRequestTypeDef",
+    "ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
     "ListAssetRelationshipsRequestRequestTypeDef",
+    "ListAssetsRequestListAssetsPaginateTypeDef",
     "ListAssetsRequestRequestTypeDef",
+    "ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
     "ListAssociatedAssetsRequestRequestTypeDef",
+    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
     "ListBulkImportJobsRequestRequestTypeDef",
+    "ListDashboardsRequestListDashboardsPaginateTypeDef",
     "ListDashboardsRequestRequestTypeDef",
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
     "ListGatewaysRequestRequestTypeDef",
+    "ListPortalsRequestListPortalsPaginateTypeDef",
     "ListPortalsRequestRequestTypeDef",
+    "ListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
     "ListProjectAssetsRequestRequestTypeDef",
+    "ListProjectAssetsResponseTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
     "ListTimeSeriesRequestRequestTypeDef",
     "TimeSeriesSummaryTypeDef",
     "MetricProcessingConfigTypeDef",
     "TumblingWindowTypeDef",
     "MonitorErrorDetailsTypeDef",
+    "PaginatorConfigTypeDef",
     "PortalResourceTypeDef",
     "ProjectResourceTypeDef",
     "PutDefaultEncryptionConfigurationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAssetPropertyRequestRequestTypeDef",
     "UpdateAssetRequestRequestTypeDef",
     "UpdateDashboardRequestRequestTypeDef",
     "UpdateGatewayCapabilityConfigurationRequestRequestTypeDef",
+    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
     "UpdateGatewayRequestRequestTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "AggregatedValueTypeDef",
+    "BatchAssociateProjectAssetsResponseTypeDef",
+    "BatchDisassociateProjectAssetsResponseTypeDef",
     "AssetRelationshipSummaryTypeDef",
     "AssetPropertySummaryTypeDef",
     "AssetPropertyTypeDef",
     "BatchPutAssetPropertyErrorTypeDef",
     "AssetPropertyValueTypeDef",
     "InterpolatedAssetPropertyValueTypeDef",
-    "BatchAssociateProjectAssetsResponseTypeDef",
-    "BatchDisassociateProjectAssetsResponseTypeDef",
-    "CreateAccessPolicyResponseTypeDef",
-    "CreateBulkImportJobResponseTypeDef",
-    "CreateDashboardResponseTypeDef",
-    "CreateGatewayResponseTypeDef",
-    "CreateProjectResponseTypeDef",
-    "DescribeDashboardResponseTypeDef",
-    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
-    "DescribeProjectResponseTypeDef",
-    "DescribeTimeSeriesResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListProjectAssetsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
     "BatchGetAssetPropertyAggregatesRequestRequestTypeDef",
     "BatchGetAssetPropertyAggregatesSkippedEntryTypeDef",
     "BatchGetAssetPropertyValueRequestRequestTypeDef",
     "BatchGetAssetPropertyValueSkippedEntryTypeDef",
     "BatchGetAssetPropertyValueHistoryRequestRequestTypeDef",
     "BatchGetAssetPropertyValueHistorySkippedEntryTypeDef",
     "ConfigurationStatusTypeDef",
@@ -217,31 +234,14 @@
     "DescribeLoggingOptionsResponseTypeDef",
     "PutLoggingOptionsRequestRequestTypeDef",
     "ErrorDetailsTypeDef",
     "ExpressionVariableTypeDef",
     "MeasurementProcessingConfigTypeDef",
     "TransformProcessingConfigTypeDef",
     "GatewayPlatformTypeDef",
-    "GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
-    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
-    "GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
-    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
-    "ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
-    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
-    "ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
-    "ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    "ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
-    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
-    "ListDashboardsRequestListDashboardsPaginateTypeDef",
-    "ListGatewaysRequestListGatewaysPaginateTypeDef",
-    "ListPortalsRequestListPortalsPaginateTypeDef",
-    "ListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
     "IdentityTypeDef",
     "ListBulkImportJobsResponseTypeDef",
     "ListProjectsResponseTypeDef",
     "ListTimeSeriesResponseTypeDef",
     "MetricWindowTypeDef",
     "PortalStatusTypeDef",
     "ResourceTypeDef",
@@ -530,25 +530,14 @@
 class BatchAssociateProjectAssetsRequestRequestTypeDef(
     _RequiredBatchAssociateProjectAssetsRequestRequestTypeDef,
     _OptionalBatchAssociateProjectAssetsRequestRequestTypeDef,
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
-
 _RequiredBatchDisassociateProjectAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDisassociateProjectAssetsRequestRequestTypeDef",
     {
         "projectId": str,
         "assetIds": Sequence[str],
     },
 )
@@ -704,14 +693,23 @@
     "ConfigurationErrorDetailsTypeDef",
     {
         "code": ErrorCodeType,
         "message": str,
     },
 )
 
+CreateAccessPolicyResponseTypeDef = TypedDict(
+    "CreateAccessPolicyResponseTypeDef",
+    {
+        "accessPolicyId": str,
+        "accessPolicyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateAssetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssetRequestRequestTypeDef",
     {
         "assetName": str,
         "assetModelId": str,
     },
 )
@@ -756,14 +754,24 @@
 )
 
 
 class FileTypeDef(_RequiredFileTypeDef, _OptionalFileTypeDef):
     pass
 
 
+CreateBulkImportJobResponseTypeDef = TypedDict(
+    "CreateBulkImportJobResponseTypeDef",
+    {
+        "jobId": str,
+        "jobName": str,
+        "jobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateDashboardRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDashboardRequestRequestTypeDef",
     {
         "projectId": str,
         "dashboardName": str,
         "dashboardDefinition": str,
     },
@@ -781,14 +789,32 @@
 
 class CreateDashboardRequestRequestTypeDef(
     _RequiredCreateDashboardRequestRequestTypeDef, _OptionalCreateDashboardRequestRequestTypeDef
 ):
     pass
 
 
+CreateDashboardResponseTypeDef = TypedDict(
+    "CreateDashboardResponseTypeDef",
+    {
+        "dashboardId": str,
+        "dashboardArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateGatewayResponseTypeDef = TypedDict(
+    "CreateGatewayResponseTypeDef",
+    {
+        "gatewayId": str,
+        "gatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageFileTypeDef = TypedDict(
     "ImageFileTypeDef",
     {
         "data": Union[str, bytes, IO[Any], StreamingBody],
         "type": Literal["PNG"],
     },
 )
@@ -813,14 +839,23 @@
 
 class CreateProjectRequestRequestTypeDef(
     _RequiredCreateProjectRequestRequestTypeDef, _OptionalCreateProjectRequestRequestTypeDef
 ):
     pass
 
 
+CreateProjectResponseTypeDef = TypedDict(
+    "CreateProjectResponseTypeDef",
+    {
+        "projectId": str,
+        "projectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CsvTypeDef = TypedDict(
     "CsvTypeDef",
     {
         "columnNames": Sequence[ColumnNameType],
     },
     total=False,
 )
@@ -1077,22 +1112,48 @@
 DescribeDashboardRequestRequestTypeDef = TypedDict(
     "DescribeDashboardRequestRequestTypeDef",
     {
         "dashboardId": str,
     },
 )
 
+DescribeDashboardResponseTypeDef = TypedDict(
+    "DescribeDashboardResponseTypeDef",
+    {
+        "dashboardId": str,
+        "dashboardArn": str,
+        "dashboardName": str,
+        "projectId": str,
+        "dashboardDescription": str,
+        "dashboardDefinition": str,
+        "dashboardCreationDate": datetime,
+        "dashboardLastUpdateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeGatewayCapabilityConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeGatewayCapabilityConfigurationRequestRequestTypeDef",
     {
         "gatewayId": str,
         "capabilityNamespace": str,
     },
 )
 
+DescribeGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
+    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
+    {
+        "gatewayId": str,
+        "capabilityNamespace": str,
+        "capabilityConfiguration": str,
+        "capabilitySyncStatus": CapabilitySyncStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeGatewayRequestRequestTypeDef = TypedDict(
     "DescribeGatewayRequestRequestTypeDef",
     {
         "gatewayId": str,
     },
 )
 
@@ -1129,14 +1190,28 @@
 DescribeProjectRequestRequestTypeDef = TypedDict(
     "DescribeProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 
+DescribeProjectResponseTypeDef = TypedDict(
+    "DescribeProjectResponseTypeDef",
+    {
+        "projectId": str,
+        "projectArn": str,
+        "projectName": str,
+        "portalId": str,
+        "projectDescription": str,
+        "projectCreationDate": datetime,
+        "projectLastUpdateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RetentionPeriodTypeDef = TypedDict(
     "RetentionPeriodTypeDef",
     {
         "numberOfDays": int,
         "unlimited": bool,
     },
     total=False,
@@ -1148,14 +1223,30 @@
         "alias": str,
         "assetId": str,
         "propertyId": str,
     },
     total=False,
 )
 
+DescribeTimeSeriesResponseTypeDef = TypedDict(
+    "DescribeTimeSeriesResponseTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "alias": str,
+        "timeSeriesId": str,
+        "dataType": PropertyDataTypeType,
+        "dataTypeSpec": str,
+        "timeSeriesCreationDate": datetime,
+        "timeSeriesLastUpdateDate": datetime,
+        "timeSeriesArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DetailedErrorTypeDef = TypedDict(
     "DetailedErrorTypeDef",
     {
         "code": DetailedErrorCodeType,
         "message": str,
     },
 )
@@ -1204,14 +1295,21 @@
 class DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef(
     _RequiredDisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
     _OptionalDisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredVariableValueTypeDef = TypedDict(
     "_RequiredVariableValueTypeDef",
     {
         "propertyId": str,
     },
 )
 _OptionalVariableValueTypeDef = TypedDict(
@@ -1244,24 +1342,44 @@
 GreengrassV2TypeDef = TypedDict(
     "GreengrassV2TypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
+    "_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "aggregateTypes": Sequence[AggregateTypeType],
+        "resolution": str,
+        "startDate": Union[datetime, str],
+        "endDate": Union[datetime, str],
+    },
+)
+_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
+    "_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "propertyAlias": str,
+        "qualities": Sequence[QualityType],
+        "timeOrdering": TimeOrderingType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef(
+    _RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
+    _OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetAssetPropertyAggregatesRequestRequestTypeDef = TypedDict(
     "_RequiredGetAssetPropertyAggregatesRequestRequestTypeDef",
     {
         "aggregateTypes": Sequence[AggregateTypeType],
         "resolution": str,
         "startDate": Union[datetime, str],
         "endDate": Union[datetime, str],
@@ -1285,14 +1403,29 @@
 class GetAssetPropertyAggregatesRequestRequestTypeDef(
     _RequiredGetAssetPropertyAggregatesRequestRequestTypeDef,
     _OptionalGetAssetPropertyAggregatesRequestRequestTypeDef,
 ):
     pass
 
 
+GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef = TypedDict(
+    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "propertyAlias": str,
+        "startDate": Union[datetime, str],
+        "endDate": Union[datetime, str],
+        "qualities": Sequence[QualityType],
+        "timeOrdering": TimeOrderingType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetAssetPropertyValueHistoryRequestRequestTypeDef = TypedDict(
     "GetAssetPropertyValueHistoryRequestRequestTypeDef",
     {
         "assetId": str,
         "propertyId": str,
         "propertyAlias": str,
         "startDate": Union[datetime, str],
@@ -1311,14 +1444,46 @@
         "assetId": str,
         "propertyId": str,
         "propertyAlias": str,
     },
     total=False,
 )
 
+_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
+    "_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
+    {
+        "startTimeInSeconds": int,
+        "endTimeInSeconds": int,
+        "quality": QualityType,
+        "intervalInSeconds": int,
+        "type": str,
+    },
+)
+_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
+    "_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "propertyAlias": str,
+        "startTimeOffsetInNanos": int,
+        "endTimeOffsetInNanos": int,
+        "intervalWindowInSeconds": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef(
+    _RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
+    _OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetInterpolatedAssetPropertyValuesRequestRequestTypeDef = TypedDict(
     "_RequiredGetInterpolatedAssetPropertyValuesRequestRequestTypeDef",
     {
         "startTimeInSeconds": int,
         "endTimeInSeconds": int,
         "quality": QualityType,
         "intervalInSeconds": int,
@@ -1381,28 +1546,64 @@
     {
         "id": str,
         "name": str,
         "status": JobStatusType,
     },
 )
 
+ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef = TypedDict(
+    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
+    {
+        "identityType": IdentityTypeType,
+        "identityId": str,
+        "resourceType": ResourceTypeType,
+        "resourceId": str,
+        "iamArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAccessPoliciesRequestRequestTypeDef = TypedDict(
     "ListAccessPoliciesRequestRequestTypeDef",
     {
         "identityType": IdentityTypeType,
         "identityId": str,
         "resourceType": ResourceTypeType,
         "resourceId": str,
         "iamArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
+    "_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
+    {
+        "assetModelId": str,
+    },
+)
+_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
+    "_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
+    {
+        "filter": ListAssetModelPropertiesFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef(
+    _RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
+    _OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssetModelPropertiesRequestRequestTypeDef = TypedDict(
     "_RequiredListAssetModelPropertiesRequestRequestTypeDef",
     {
         "assetModelId": str,
     },
 )
 _OptionalListAssetModelPropertiesRequestRequestTypeDef = TypedDict(
@@ -1419,23 +1620,54 @@
 class ListAssetModelPropertiesRequestRequestTypeDef(
     _RequiredListAssetModelPropertiesRequestRequestTypeDef,
     _OptionalListAssetModelPropertiesRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssetModelsRequestListAssetModelsPaginateTypeDef = TypedDict(
+    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssetModelsRequestRequestTypeDef = TypedDict(
     "ListAssetModelsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
+    "_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
+    {
+        "assetId": str,
+    },
+)
+_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
+    "_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
+    {
+        "filter": ListAssetPropertiesFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef(
+    _RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
+    _OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssetPropertiesRequestRequestTypeDef = TypedDict(
     "_RequiredListAssetPropertiesRequestRequestTypeDef",
     {
         "assetId": str,
     },
 )
 _OptionalListAssetPropertiesRequestRequestTypeDef = TypedDict(
@@ -1452,14 +1684,37 @@
 class ListAssetPropertiesRequestRequestTypeDef(
     _RequiredListAssetPropertiesRequestRequestTypeDef,
     _OptionalListAssetPropertiesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
+    "_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
+    {
+        "assetId": str,
+        "traversalType": Literal["PATH_TO_ROOT"],
+    },
+)
+_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
+    "_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef(
+    _RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
+    _OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssetRelationshipsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssetRelationshipsRequestRequestTypeDef",
     {
         "assetId": str,
         "traversalType": Literal["PATH_TO_ROOT"],
     },
 )
@@ -1476,25 +1731,59 @@
 class ListAssetRelationshipsRequestRequestTypeDef(
     _RequiredListAssetRelationshipsRequestRequestTypeDef,
     _OptionalListAssetRelationshipsRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
+    "ListAssetsRequestListAssetsPaginateTypeDef",
+    {
+        "assetModelId": str,
+        "filter": ListAssetsFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssetsRequestRequestTypeDef = TypedDict(
     "ListAssetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "assetModelId": str,
         "filter": ListAssetsFilterType,
     },
     total=False,
 )
 
+_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
+    {
+        "assetId": str,
+    },
+)
+_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
+    {
+        "hierarchyId": str,
+        "traversalDirection": TraversalDirectionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef(
+    _RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
+    _OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociatedAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedAssetsRequestRequestTypeDef",
     {
         "assetId": str,
     },
 )
 _OptionalListAssociatedAssetsRequestRequestTypeDef = TypedDict(
@@ -1512,24 +1801,55 @@
 class ListAssociatedAssetsRequestRequestTypeDef(
     _RequiredListAssociatedAssetsRequestRequestTypeDef,
     _OptionalListAssociatedAssetsRequestRequestTypeDef,
 ):
     pass
 
 
+ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef = TypedDict(
+    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
+    {
+        "filter": ListBulkImportJobsFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBulkImportJobsRequestRequestTypeDef = TypedDict(
     "ListBulkImportJobsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "filter": ListBulkImportJobsFilterType,
     },
     total=False,
 )
 
+_RequiredListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
+    "_RequiredListDashboardsRequestListDashboardsPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
+    "_OptionalListDashboardsRequestListDashboardsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDashboardsRequestListDashboardsPaginateTypeDef(
+    _RequiredListDashboardsRequestListDashboardsPaginateTypeDef,
+    _OptionalListDashboardsRequestListDashboardsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDashboardsRequestRequestTypeDef = TypedDict(
     "_RequiredListDashboardsRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListDashboardsRequestRequestTypeDef = TypedDict(
@@ -1544,32 +1864,70 @@
 
 class ListDashboardsRequestRequestTypeDef(
     _RequiredListDashboardsRequestRequestTypeDef, _OptionalListDashboardsRequestRequestTypeDef
 ):
     pass
 
 
+ListGatewaysRequestListGatewaysPaginateTypeDef = TypedDict(
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGatewaysRequestRequestTypeDef = TypedDict(
     "ListGatewaysRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListPortalsRequestListPortalsPaginateTypeDef = TypedDict(
+    "ListPortalsRequestListPortalsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPortalsRequestRequestTypeDef = TypedDict(
     "ListPortalsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProjectAssetsRequestListProjectAssetsPaginateTypeDef(
+    _RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
+    _OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProjectAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectAssetsRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListProjectAssetsRequestRequestTypeDef = TypedDict(
@@ -1584,14 +1942,45 @@
 
 class ListProjectAssetsRequestRequestTypeDef(
     _RequiredListProjectAssetsRequestRequestTypeDef, _OptionalListProjectAssetsRequestRequestTypeDef
 ):
     pass
 
 
+ListProjectAssetsResponseTypeDef = TypedDict(
+    "ListProjectAssetsResponseTypeDef",
+    {
+        "assetIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "_RequiredListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "portalId": str,
+    },
+)
+_OptionalListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "_OptionalListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProjectsRequestListProjectsPaginateTypeDef(
+    _RequiredListProjectsRequestListProjectsPaginateTypeDef,
+    _OptionalListProjectsRequestListProjectsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectsRequestRequestTypeDef",
     {
         "portalId": str,
     },
 )
 _OptionalListProjectsRequestRequestTypeDef = TypedDict(
@@ -1635,14 +2024,33 @@
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
+ListTimeSeriesRequestListTimeSeriesPaginateTypeDef = TypedDict(
+    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
+    {
+        "assetId": str,
+        "aliasPrefix": str,
+        "timeSeriesType": ListTimeSeriesTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTimeSeriesRequestRequestTypeDef = TypedDict(
     "ListTimeSeriesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "assetId": str,
         "aliasPrefix": str,
@@ -1654,14 +2062,15 @@
 _RequiredTimeSeriesSummaryTypeDef = TypedDict(
     "_RequiredTimeSeriesSummaryTypeDef",
     {
         "timeSeriesId": str,
         "dataType": PropertyDataTypeType,
         "timeSeriesCreationDate": datetime,
         "timeSeriesLastUpdateDate": datetime,
+        "timeSeriesArn": str,
     },
 )
 _OptionalTimeSeriesSummaryTypeDef = TypedDict(
     "_OptionalTimeSeriesSummaryTypeDef",
     {
         "assetId": str,
         "propertyId": str,
@@ -1709,14 +2118,24 @@
     {
         "code": MonitorErrorCodeType,
         "message": str,
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
 PortalResourceTypeDef = TypedDict(
     "PortalResourceTypeDef",
     {
         "id": str,
     },
 )
 
@@ -1745,14 +2164,25 @@
 class PutDefaultEncryptionConfigurationRequestRequestTypeDef(
     _RequiredPutDefaultEncryptionConfigurationRequestRequestTypeDef,
     _OptionalPutDefaultEncryptionConfigurationRequestRequestTypeDef,
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -1843,14 +2273,23 @@
     {
         "gatewayId": str,
         "capabilityNamespace": str,
         "capabilityConfiguration": str,
     },
 )
 
+UpdateGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
+    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
+    {
+        "capabilityNamespace": str,
+        "capabilitySyncStatus": CapabilitySyncStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateGatewayRequestRequestTypeDef = TypedDict(
     "UpdateGatewayRequestRequestTypeDef",
     {
         "gatewayId": str,
         "gatewayName": str,
     },
 )
@@ -1894,14 +2333,30 @@
 )
 
 
 class AggregatedValueTypeDef(_RequiredAggregatedValueTypeDef, _OptionalAggregatedValueTypeDef):
     pass
 
 
+BatchAssociateProjectAssetsResponseTypeDef = TypedDict(
+    "BatchAssociateProjectAssetsResponseTypeDef",
+    {
+        "errors": List[AssetErrorDetailsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchDisassociateProjectAssetsResponseTypeDef = TypedDict(
+    "BatchDisassociateProjectAssetsResponseTypeDef",
+    {
+        "errors": List[AssetErrorDetailsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssetRelationshipSummaryTypeDef = TypedDict(
     "_RequiredAssetRelationshipSummaryTypeDef",
     {
         "relationshipType": Literal["HIERARCHY"],
     },
 )
 _OptionalAssetRelationshipSummaryTypeDef = TypedDict(
@@ -1990,164 +2445,14 @@
     "InterpolatedAssetPropertyValueTypeDef",
     {
         "timestamp": TimeInNanosTypeDef,
         "value": VariantTypeDef,
     },
 )
 
-BatchAssociateProjectAssetsResponseTypeDef = TypedDict(
-    "BatchAssociateProjectAssetsResponseTypeDef",
-    {
-        "errors": List[AssetErrorDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchDisassociateProjectAssetsResponseTypeDef = TypedDict(
-    "BatchDisassociateProjectAssetsResponseTypeDef",
-    {
-        "errors": List[AssetErrorDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessPolicyResponseTypeDef = TypedDict(
-    "CreateAccessPolicyResponseTypeDef",
-    {
-        "accessPolicyId": str,
-        "accessPolicyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBulkImportJobResponseTypeDef = TypedDict(
-    "CreateBulkImportJobResponseTypeDef",
-    {
-        "jobId": str,
-        "jobName": str,
-        "jobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDashboardResponseTypeDef = TypedDict(
-    "CreateDashboardResponseTypeDef",
-    {
-        "dashboardId": str,
-        "dashboardArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGatewayResponseTypeDef = TypedDict(
-    "CreateGatewayResponseTypeDef",
-    {
-        "gatewayId": str,
-        "gatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProjectResponseTypeDef = TypedDict(
-    "CreateProjectResponseTypeDef",
-    {
-        "projectId": str,
-        "projectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDashboardResponseTypeDef = TypedDict(
-    "DescribeDashboardResponseTypeDef",
-    {
-        "dashboardId": str,
-        "dashboardArn": str,
-        "dashboardName": str,
-        "projectId": str,
-        "dashboardDescription": str,
-        "dashboardDefinition": str,
-        "dashboardCreationDate": datetime,
-        "dashboardLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
-    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
-    {
-        "gatewayId": str,
-        "capabilityNamespace": str,
-        "capabilityConfiguration": str,
-        "capabilitySyncStatus": CapabilitySyncStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProjectResponseTypeDef = TypedDict(
-    "DescribeProjectResponseTypeDef",
-    {
-        "projectId": str,
-        "projectArn": str,
-        "projectName": str,
-        "portalId": str,
-        "projectDescription": str,
-        "projectCreationDate": datetime,
-        "projectLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeTimeSeriesResponseTypeDef = TypedDict(
-    "DescribeTimeSeriesResponseTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "alias": str,
-        "timeSeriesId": str,
-        "dataType": PropertyDataTypeType,
-        "dataTypeSpec": str,
-        "timeSeriesCreationDate": datetime,
-        "timeSeriesLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListProjectAssetsResponseTypeDef = TypedDict(
-    "ListProjectAssetsResponseTypeDef",
-    {
-        "assetIds": List[str],
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
-UpdateGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
-    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
-    {
-        "capabilityNamespace": str,
-        "capabilitySyncStatus": CapabilitySyncStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredBatchGetAssetPropertyAggregatesRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetAssetPropertyAggregatesRequestRequestTypeDef",
     {
         "entries": Sequence[BatchGetAssetPropertyAggregatesEntryTypeDef],
     },
 )
 _OptionalBatchGetAssetPropertyAggregatesRequestRequestTypeDef = TypedDict(
@@ -2356,15 +2661,15 @@
 )
 
 ListDashboardsResponseTypeDef = TypedDict(
     "ListDashboardsResponseTypeDef",
     {
         "dashboardSummaries": List[DashboardSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeAssetModelRequestAssetModelActiveWaitTypeDef = TypedDict(
     "_RequiredDescribeAssetModelRequestAssetModelActiveWaitTypeDef",
     {
         "assetModelId": str,
@@ -2500,15 +2805,15 @@
     pass
 
 
 DescribeLoggingOptionsResponseTypeDef = TypedDict(
     "DescribeLoggingOptionsResponseTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
@@ -2576,317 +2881,14 @@
     {
         "greengrass": GreengrassTypeDef,
         "greengrassV2": GreengrassV2TypeDef,
     },
     total=False,
 )
 
-_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
-    "_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
-    {
-        "aggregateTypes": Sequence[AggregateTypeType],
-        "resolution": str,
-        "startDate": Union[datetime, str],
-        "endDate": Union[datetime, str],
-    },
-)
-_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
-    "_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "propertyAlias": str,
-        "qualities": Sequence[QualityType],
-        "timeOrdering": TimeOrderingType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef(
-    _RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-    _OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-):
-    pass
-
-
-GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef = TypedDict(
-    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "propertyAlias": str,
-        "startDate": Union[datetime, str],
-        "endDate": Union[datetime, str],
-        "qualities": Sequence[QualityType],
-        "timeOrdering": TimeOrderingType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
-    "_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
-    {
-        "startTimeInSeconds": int,
-        "endTimeInSeconds": int,
-        "quality": QualityType,
-        "intervalInSeconds": int,
-        "type": str,
-    },
-)
-_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
-    "_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "propertyAlias": str,
-        "startTimeOffsetInNanos": int,
-        "endTimeOffsetInNanos": int,
-        "intervalWindowInSeconds": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef(
-    _RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-    _OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-):
-    pass
-
-
-ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef = TypedDict(
-    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
-    {
-        "identityType": IdentityTypeType,
-        "identityId": str,
-        "resourceType": ResourceTypeType,
-        "resourceId": str,
-        "iamArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
-    "_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
-    {
-        "assetModelId": str,
-    },
-)
-_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
-    "_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
-    {
-        "filter": ListAssetModelPropertiesFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef(
-    _RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-    _OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-):
-    pass
-
-
-ListAssetModelsRequestListAssetModelsPaginateTypeDef = TypedDict(
-    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
-    "_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
-    {
-        "assetId": str,
-    },
-)
-_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
-    "_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
-    {
-        "filter": ListAssetPropertiesFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef(
-    _RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-    _OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
-    "_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
-    {
-        "assetId": str,
-        "traversalType": Literal["PATH_TO_ROOT"],
-    },
-)
-_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
-    "_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef(
-    _RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-    _OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-):
-    pass
-
-
-ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    {
-        "assetModelId": str,
-        "filter": ListAssetsFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
-    {
-        "assetId": str,
-    },
-)
-_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
-    {
-        "hierarchyId": str,
-        "traversalDirection": TraversalDirectionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef(
-    _RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-    _OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-):
-    pass
-
-
-ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef = TypedDict(
-    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
-    {
-        "filter": ListBulkImportJobsFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
-    "_RequiredListDashboardsRequestListDashboardsPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
-    "_OptionalListDashboardsRequestListDashboardsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDashboardsRequestListDashboardsPaginateTypeDef(
-    _RequiredListDashboardsRequestListDashboardsPaginateTypeDef,
-    _OptionalListDashboardsRequestListDashboardsPaginateTypeDef,
-):
-    pass
-
-
-ListGatewaysRequestListGatewaysPaginateTypeDef = TypedDict(
-    "ListGatewaysRequestListGatewaysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPortalsRequestListPortalsPaginateTypeDef = TypedDict(
-    "ListPortalsRequestListPortalsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProjectAssetsRequestListProjectAssetsPaginateTypeDef(
-    _RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-    _OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "_RequiredListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "portalId": str,
-    },
-)
-_OptionalListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "_OptionalListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProjectsRequestListProjectsPaginateTypeDef(
-    _RequiredListProjectsRequestListProjectsPaginateTypeDef,
-    _OptionalListProjectsRequestListProjectsPaginateTypeDef,
-):
-    pass
-
-
-ListTimeSeriesRequestListTimeSeriesPaginateTypeDef = TypedDict(
-    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
-    {
-        "assetId": str,
-        "aliasPrefix": str,
-        "timeSeriesType": ListTimeSeriesTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 IdentityTypeDef = TypedDict(
     "IdentityTypeDef",
     {
         "user": UserIdentityTypeDef,
         "group": GroupIdentityTypeDef,
         "iamUser": IAMUserIdentityTypeDef,
         "iamRole": IAMRoleIdentityTypeDef,
@@ -2895,33 +2897,33 @@
 )
 
 ListBulkImportJobsResponseTypeDef = TypedDict(
     "ListBulkImportJobsResponseTypeDef",
     {
         "jobSummaries": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "projectSummaries": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTimeSeriesResponseTypeDef = TypedDict(
     "ListTimeSeriesResponseTypeDef",
     {
         "TimeSeriesSummaries": List[TimeSeriesSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricWindowTypeDef = TypedDict(
     "MetricWindowTypeDef",
     {
         "tumbling": TumblingWindowTypeDef,
@@ -2966,33 +2968,33 @@
 )
 
 GetAssetPropertyAggregatesResponseTypeDef = TypedDict(
     "GetAssetPropertyAggregatesResponseTypeDef",
     {
         "aggregatedValues": List[AggregatedValueTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetRelationshipsResponseTypeDef = TypedDict(
     "ListAssetRelationshipsResponseTypeDef",
     {
         "assetRelationshipSummaries": List[AssetRelationshipSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetPropertiesResponseTypeDef = TypedDict(
     "ListAssetPropertiesResponseTypeDef",
     {
         "assetPropertySummaries": List[AssetPropertySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetCompositeModelTypeDef = TypedDict(
     "_RequiredAssetCompositeModelTypeDef",
     {
         "name": str,
@@ -3055,23 +3057,23 @@
 
 
 GetAssetPropertyValueHistoryResponseTypeDef = TypedDict(
     "GetAssetPropertyValueHistoryResponseTypeDef",
     {
         "assetPropertyValueHistory": List[AssetPropertyValueTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssetPropertyValueResponseTypeDef = TypedDict(
     "GetAssetPropertyValueResponseTypeDef",
     {
         "propertyValue": AssetPropertyValueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAssetPropertyValueEntryTypeDef = TypedDict(
     "_RequiredPutAssetPropertyValueEntryTypeDef",
     {
         "entryId": str,
@@ -3096,35 +3098,35 @@
 
 
 GetInterpolatedAssetPropertyValuesResponseTypeDef = TypedDict(
     "GetInterpolatedAssetPropertyValuesResponseTypeDef",
     {
         "interpolatedAssetPropertyValues": List[InterpolatedAssetPropertyValueTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDefaultEncryptionConfigurationResponseTypeDef = TypedDict(
     "DescribeDefaultEncryptionConfigurationResponseTypeDef",
     {
         "encryptionType": EncryptionTypeType,
         "kmsKeyArn": str,
         "configurationStatus": ConfigurationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDefaultEncryptionConfigurationResponseTypeDef = TypedDict(
     "PutDefaultEncryptionConfigurationResponseTypeDef",
     {
         "encryptionType": EncryptionTypeType,
         "kmsKeyArn": str,
         "configurationStatus": ConfigurationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePortalRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePortalRequestRequestTypeDef",
     {
         "portalId": str,
@@ -3164,15 +3166,15 @@
     {
         "storageType": StorageTypeType,
         "multiLayerStorage": MultiLayerStorageTypeDef,
         "disassociatedDataStorage": DisassociatedDataStorageStateType,
         "retentionPeriod": RetentionPeriodTypeDef,
         "configurationStatus": ConfigurationStatusTypeDef,
         "lastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutStorageConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutStorageConfigurationRequestRequestTypeDef",
     {
         "storageType": StorageTypeType,
@@ -3200,15 +3202,15 @@
     "PutStorageConfigurationResponseTypeDef",
     {
         "storageType": StorageTypeType,
         "multiLayerStorage": MultiLayerStorageTypeDef,
         "disassociatedDataStorage": DisassociatedDataStorageStateType,
         "retentionPeriod": RetentionPeriodTypeDef,
         "configurationStatus": ConfigurationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetModelStatusTypeDef = TypedDict(
     "_RequiredAssetModelStatusTypeDef",
     {
         "state": AssetModelStateType,
@@ -3302,15 +3304,15 @@
         "gatewayId": str,
         "gatewayName": str,
         "gatewayArn": str,
         "gatewayPlatform": GatewayPlatformTypeDef,
         "gatewayCapabilitySummaries": List[GatewayCapabilitySummaryTypeDef],
         "creationDate": datetime,
         "lastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGatewaySummaryTypeDef = TypedDict(
     "_RequiredGatewaySummaryTypeDef",
     {
         "gatewayId": str,
@@ -3358,23 +3360,23 @@
     "CreatePortalResponseTypeDef",
     {
         "portalId": str,
         "portalArn": str,
         "portalStartUrl": str,
         "portalStatus": PortalStatusTypeDef,
         "ssoApplicationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePortalResponseTypeDef = TypedDict(
     "DeletePortalResponseTypeDef",
     {
         "portalStatus": PortalStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePortalResponseTypeDef = TypedDict(
     "DescribePortalResponseTypeDef",
     {
         "portalId": str,
@@ -3388,15 +3390,15 @@
         "portalCreationDate": datetime,
         "portalLastUpdateDate": datetime,
         "portalLogoImageLocation": ImageLocationTypeDef,
         "roleArn": str,
         "portalAuthMode": AuthModeType,
         "notificationSenderEmail": str,
         "alarms": AlarmsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPortalSummaryTypeDef = TypedDict(
     "_RequiredPortalSummaryTypeDef",
     {
         "id": str,
@@ -3421,15 +3423,15 @@
     pass
 
 
 UpdatePortalResponseTypeDef = TypedDict(
     "UpdatePortalResponseTypeDef",
     {
         "portalStatus": PortalStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAccessPolicySummaryTypeDef = TypedDict(
     "_RequiredAccessPolicySummaryTypeDef",
     {
         "id": str,
@@ -3485,15 +3487,15 @@
         "accessPolicyId": str,
         "accessPolicyArn": str,
         "accessPolicyIdentity": IdentityTypeDef,
         "accessPolicyResource": ResourceTypeDef,
         "accessPolicyPermission": PermissionType,
         "accessPolicyCreationDate": datetime,
         "accessPolicyLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAccessPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAccessPolicyRequestRequestTypeDef",
     {
         "accessPolicyId": str,
@@ -3521,45 +3523,45 @@
 BatchGetAssetPropertyAggregatesResponseTypeDef = TypedDict(
     "BatchGetAssetPropertyAggregatesResponseTypeDef",
     {
         "errorEntries": List[BatchGetAssetPropertyAggregatesErrorEntryTypeDef],
         "successEntries": List[BatchGetAssetPropertyAggregatesSuccessEntryTypeDef],
         "skippedEntries": List[BatchGetAssetPropertyAggregatesSkippedEntryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutAssetPropertyValueResponseTypeDef = TypedDict(
     "BatchPutAssetPropertyValueResponseTypeDef",
     {
         "errorEntries": List[BatchPutAssetPropertyErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetAssetPropertyValueHistoryResponseTypeDef = TypedDict(
     "BatchGetAssetPropertyValueHistoryResponseTypeDef",
     {
         "errorEntries": List[BatchGetAssetPropertyValueHistoryErrorEntryTypeDef],
         "successEntries": List[BatchGetAssetPropertyValueHistorySuccessEntryTypeDef],
         "skippedEntries": List[BatchGetAssetPropertyValueHistorySkippedEntryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetAssetPropertyValueResponseTypeDef = TypedDict(
     "BatchGetAssetPropertyValueResponseTypeDef",
     {
         "errorEntries": List[BatchGetAssetPropertyValueErrorEntryTypeDef],
         "successEntries": List[BatchGetAssetPropertyValueSuccessEntryTypeDef],
         "skippedEntries": List[BatchGetAssetPropertyValueSkippedEntryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutAssetPropertyValueRequestRequestTypeDef = TypedDict(
     "BatchPutAssetPropertyValueRequestRequestTypeDef",
     {
         "entries": Sequence[PutAssetPropertyValueEntryTypeDef],
@@ -3585,15 +3587,15 @@
         "jobStatus": JobStatusType,
         "jobRoleArn": str,
         "files": List[FileTypeDef],
         "errorReportLocation": ErrorReportLocationTypeDef,
         "jobConfiguration": JobConfigurationTypeDef,
         "jobCreationDate": datetime,
         "jobLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssetModelSummaryTypeDef = TypedDict(
     "AssetModelSummaryTypeDef",
     {
         "id": str,
@@ -3608,31 +3610,31 @@
 
 CreateAssetModelResponseTypeDef = TypedDict(
     "CreateAssetModelResponseTypeDef",
     {
         "assetModelId": str,
         "assetModelArn": str,
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAssetModelResponseTypeDef = TypedDict(
     "DeleteAssetModelResponseTypeDef",
     {
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssetModelResponseTypeDef = TypedDict(
     "UpdateAssetModelResponseTypeDef",
     {
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetSummaryTypeDef = TypedDict(
     "_RequiredAssetSummaryTypeDef",
     {
         "id": str,
@@ -3688,23 +3690,23 @@
 
 CreateAssetResponseTypeDef = TypedDict(
     "CreateAssetResponseTypeDef",
     {
         "assetId": str,
         "assetArn": str,
         "assetStatus": AssetStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAssetResponseTypeDef = TypedDict(
     "DeleteAssetResponseTypeDef",
     {
         "assetStatus": AssetStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssetResponseTypeDef = TypedDict(
     "DescribeAssetResponseTypeDef",
     {
         "assetId": str,
@@ -3714,32 +3716,32 @@
         "assetProperties": List[AssetPropertyTypeDef],
         "assetHierarchies": List[AssetHierarchyTypeDef],
         "assetCompositeModels": List[AssetCompositeModelTypeDef],
         "assetCreationDate": datetime,
         "assetLastUpdateDate": datetime,
         "assetStatus": AssetStatusTypeDef,
         "assetDescription": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssetResponseTypeDef = TypedDict(
     "UpdateAssetResponseTypeDef",
     {
         "assetStatus": AssetStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGatewaysResponseTypeDef = TypedDict(
     "ListGatewaysResponseTypeDef",
     {
         "gatewaySummaries": List[GatewaySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PropertyTypeTypeDef = TypedDict(
     "PropertyTypeTypeDef",
     {
         "attribute": AttributeTypeDef,
@@ -3751,51 +3753,51 @@
 )
 
 ListPortalsResponseTypeDef = TypedDict(
     "ListPortalsResponseTypeDef",
     {
         "portalSummaries": List[PortalSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccessPoliciesResponseTypeDef = TypedDict(
     "ListAccessPoliciesResponseTypeDef",
     {
         "accessPolicySummaries": List[AccessPolicySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetModelsResponseTypeDef = TypedDict(
     "ListAssetModelsResponseTypeDef",
     {
         "assetModelSummaries": List[AssetModelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetsResponseTypeDef = TypedDict(
     "ListAssetsResponseTypeDef",
     {
         "assetSummaries": List[AssetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssociatedAssetsResponseTypeDef = TypedDict(
     "ListAssociatedAssetsResponseTypeDef",
     {
         "assetSummaries": List[AssociatedAssetsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetModelPropertyDefinitionTypeDef = TypedDict(
     "_RequiredAssetModelPropertyDefinitionTypeDef",
     {
         "name": str,
@@ -3919,15 +3921,15 @@
 
 
 ListAssetModelPropertiesResponseTypeDef = TypedDict(
     "ListAssetModelPropertiesResponseTypeDef",
     {
         "assetModelPropertySummaries": List[AssetModelPropertySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetModelCompositeModelTypeDef = TypedDict(
     "_RequiredAssetModelCompositeModelTypeDef",
     {
         "name": str,
@@ -4009,15 +4011,15 @@
         "assetModelDescription": str,
         "assetModelProperties": List[AssetModelPropertyTypeDef],
         "assetModelHierarchies": List[AssetModelHierarchyTypeDef],
         "assetModelCompositeModels": List[AssetModelCompositeModelTypeDef],
         "assetModelCreationDate": datetime,
         "assetModelLastUpdateDate": datetime,
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAssetModelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAssetModelRequestRequestTypeDef",
     {
         "assetModelId": str,
@@ -4047,10 +4049,10 @@
     "DescribeAssetPropertyResponseTypeDef",
     {
         "assetId": str,
         "assetName": str,
         "assetModelId": str,
         "assetProperty": PropertyTypeDef,
         "compositeModel": CompositeModelPropertyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/type_defs.pyi` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/type_defs.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -76,32 +76,36 @@
     "PropertyNotificationTypeDef",
     "TimeInNanosTypeDef",
     "VariantTypeDef",
     "AssociateAssetsRequestRequestTypeDef",
     "AssociateTimeSeriesToAssetPropertyRequestRequestTypeDef",
     "AttributeTypeDef",
     "BatchAssociateProjectAssetsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDisassociateProjectAssetsRequestRequestTypeDef",
     "BatchGetAssetPropertyAggregatesEntryTypeDef",
     "BatchGetAssetPropertyAggregatesErrorEntryTypeDef",
     "BatchGetAssetPropertyAggregatesErrorInfoTypeDef",
     "BatchGetAssetPropertyValueEntryTypeDef",
     "BatchGetAssetPropertyValueErrorEntryTypeDef",
     "BatchGetAssetPropertyValueErrorInfoTypeDef",
     "BatchGetAssetPropertyValueHistoryEntryTypeDef",
     "BatchGetAssetPropertyValueHistoryErrorEntryTypeDef",
     "BatchGetAssetPropertyValueHistoryErrorInfoTypeDef",
     "ConfigurationErrorDetailsTypeDef",
+    "CreateAccessPolicyResponseTypeDef",
     "CreateAssetRequestRequestTypeDef",
     "ErrorReportLocationTypeDef",
     "FileTypeDef",
+    "CreateBulkImportJobResponseTypeDef",
     "CreateDashboardRequestRequestTypeDef",
+    "CreateDashboardResponseTypeDef",
+    "CreateGatewayResponseTypeDef",
     "ImageFileTypeDef",
     "CreateProjectRequestRequestTypeDef",
+    "CreateProjectResponseTypeDef",
     "CsvTypeDef",
     "CustomerManagedS3StorageTypeDef",
     "DashboardSummaryTypeDef",
     "DeleteAccessPolicyRequestRequestTypeDef",
     "DeleteAssetModelRequestRequestTypeDef",
     "DeleteAssetRequestRequestTypeDef",
     "DeleteDashboardRequestRequestTypeDef",
@@ -112,93 +116,106 @@
     "DescribeAccessPolicyRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeAssetModelRequestRequestTypeDef",
     "DescribeAssetPropertyRequestRequestTypeDef",
     "DescribeAssetRequestRequestTypeDef",
     "DescribeBulkImportJobRequestRequestTypeDef",
     "DescribeDashboardRequestRequestTypeDef",
+    "DescribeDashboardResponseTypeDef",
     "DescribeGatewayCapabilityConfigurationRequestRequestTypeDef",
+    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
     "DescribeGatewayRequestRequestTypeDef",
     "GatewayCapabilitySummaryTypeDef",
     "LoggingOptionsTypeDef",
     "DescribePortalRequestRequestTypeDef",
     "ImageLocationTypeDef",
     "DescribeProjectRequestRequestTypeDef",
+    "DescribeProjectResponseTypeDef",
     "RetentionPeriodTypeDef",
     "DescribeTimeSeriesRequestRequestTypeDef",
+    "DescribeTimeSeriesResponseTypeDef",
     "DetailedErrorTypeDef",
     "DisassociateAssetsRequestRequestTypeDef",
     "DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "VariableValueTypeDef",
     "ForwardingConfigTypeDef",
     "GreengrassTypeDef",
     "GreengrassV2TypeDef",
-    "PaginatorConfigTypeDef",
+    "GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
     "GetAssetPropertyAggregatesRequestRequestTypeDef",
+    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
     "GetAssetPropertyValueHistoryRequestRequestTypeDef",
     "GetAssetPropertyValueRequestRequestTypeDef",
+    "GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
     "GetInterpolatedAssetPropertyValuesRequestRequestTypeDef",
     "GroupIdentityTypeDef",
     "IAMRoleIdentityTypeDef",
     "IAMUserIdentityTypeDef",
     "UserIdentityTypeDef",
     "JobSummaryTypeDef",
+    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
     "ListAccessPoliciesRequestRequestTypeDef",
+    "ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
     "ListAssetModelPropertiesRequestRequestTypeDef",
+    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
     "ListAssetModelsRequestRequestTypeDef",
+    "ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
     "ListAssetPropertiesRequestRequestTypeDef",
+    "ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
     "ListAssetRelationshipsRequestRequestTypeDef",
+    "ListAssetsRequestListAssetsPaginateTypeDef",
     "ListAssetsRequestRequestTypeDef",
+    "ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
     "ListAssociatedAssetsRequestRequestTypeDef",
+    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
     "ListBulkImportJobsRequestRequestTypeDef",
+    "ListDashboardsRequestListDashboardsPaginateTypeDef",
     "ListDashboardsRequestRequestTypeDef",
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
     "ListGatewaysRequestRequestTypeDef",
+    "ListPortalsRequestListPortalsPaginateTypeDef",
     "ListPortalsRequestRequestTypeDef",
+    "ListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
     "ListProjectAssetsRequestRequestTypeDef",
+    "ListProjectAssetsResponseTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
     "ListTimeSeriesRequestRequestTypeDef",
     "TimeSeriesSummaryTypeDef",
     "MetricProcessingConfigTypeDef",
     "TumblingWindowTypeDef",
     "MonitorErrorDetailsTypeDef",
+    "PaginatorConfigTypeDef",
     "PortalResourceTypeDef",
     "ProjectResourceTypeDef",
     "PutDefaultEncryptionConfigurationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAssetPropertyRequestRequestTypeDef",
     "UpdateAssetRequestRequestTypeDef",
     "UpdateDashboardRequestRequestTypeDef",
     "UpdateGatewayCapabilityConfigurationRequestRequestTypeDef",
+    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
     "UpdateGatewayRequestRequestTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "AggregatedValueTypeDef",
+    "BatchAssociateProjectAssetsResponseTypeDef",
+    "BatchDisassociateProjectAssetsResponseTypeDef",
     "AssetRelationshipSummaryTypeDef",
     "AssetPropertySummaryTypeDef",
     "AssetPropertyTypeDef",
     "BatchPutAssetPropertyErrorTypeDef",
     "AssetPropertyValueTypeDef",
     "InterpolatedAssetPropertyValueTypeDef",
-    "BatchAssociateProjectAssetsResponseTypeDef",
-    "BatchDisassociateProjectAssetsResponseTypeDef",
-    "CreateAccessPolicyResponseTypeDef",
-    "CreateBulkImportJobResponseTypeDef",
-    "CreateDashboardResponseTypeDef",
-    "CreateGatewayResponseTypeDef",
-    "CreateProjectResponseTypeDef",
-    "DescribeDashboardResponseTypeDef",
-    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
-    "DescribeProjectResponseTypeDef",
-    "DescribeTimeSeriesResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListProjectAssetsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
     "BatchGetAssetPropertyAggregatesRequestRequestTypeDef",
     "BatchGetAssetPropertyAggregatesSkippedEntryTypeDef",
     "BatchGetAssetPropertyValueRequestRequestTypeDef",
     "BatchGetAssetPropertyValueSkippedEntryTypeDef",
     "BatchGetAssetPropertyValueHistoryRequestRequestTypeDef",
     "BatchGetAssetPropertyValueHistorySkippedEntryTypeDef",
     "ConfigurationStatusTypeDef",
@@ -216,31 +233,14 @@
     "DescribeLoggingOptionsResponseTypeDef",
     "PutLoggingOptionsRequestRequestTypeDef",
     "ErrorDetailsTypeDef",
     "ExpressionVariableTypeDef",
     "MeasurementProcessingConfigTypeDef",
     "TransformProcessingConfigTypeDef",
     "GatewayPlatformTypeDef",
-    "GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
-    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
-    "GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
-    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
-    "ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
-    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
-    "ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
-    "ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    "ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
-    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
-    "ListDashboardsRequestListDashboardsPaginateTypeDef",
-    "ListGatewaysRequestListGatewaysPaginateTypeDef",
-    "ListPortalsRequestListPortalsPaginateTypeDef",
-    "ListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
     "IdentityTypeDef",
     "ListBulkImportJobsResponseTypeDef",
     "ListProjectsResponseTypeDef",
     "ListTimeSeriesResponseTypeDef",
     "MetricWindowTypeDef",
     "PortalStatusTypeDef",
     "ResourceTypeDef",
@@ -515,25 +515,14 @@
 
 class BatchAssociateProjectAssetsRequestRequestTypeDef(
     _RequiredBatchAssociateProjectAssetsRequestRequestTypeDef,
     _OptionalBatchAssociateProjectAssetsRequestRequestTypeDef,
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
-
 _RequiredBatchDisassociateProjectAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDisassociateProjectAssetsRequestRequestTypeDef",
     {
         "projectId": str,
         "assetIds": Sequence[str],
     },
 )
@@ -681,14 +670,23 @@
     "ConfigurationErrorDetailsTypeDef",
     {
         "code": ErrorCodeType,
         "message": str,
     },
 )
 
+CreateAccessPolicyResponseTypeDef = TypedDict(
+    "CreateAccessPolicyResponseTypeDef",
+    {
+        "accessPolicyId": str,
+        "accessPolicyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateAssetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssetRequestRequestTypeDef",
     {
         "assetName": str,
         "assetModelId": str,
     },
 )
@@ -729,14 +727,24 @@
     },
     total=False,
 )
 
 class FileTypeDef(_RequiredFileTypeDef, _OptionalFileTypeDef):
     pass
 
+CreateBulkImportJobResponseTypeDef = TypedDict(
+    "CreateBulkImportJobResponseTypeDef",
+    {
+        "jobId": str,
+        "jobName": str,
+        "jobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateDashboardRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDashboardRequestRequestTypeDef",
     {
         "projectId": str,
         "dashboardName": str,
         "dashboardDefinition": str,
     },
@@ -752,14 +760,32 @@
 )
 
 class CreateDashboardRequestRequestTypeDef(
     _RequiredCreateDashboardRequestRequestTypeDef, _OptionalCreateDashboardRequestRequestTypeDef
 ):
     pass
 
+CreateDashboardResponseTypeDef = TypedDict(
+    "CreateDashboardResponseTypeDef",
+    {
+        "dashboardId": str,
+        "dashboardArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateGatewayResponseTypeDef = TypedDict(
+    "CreateGatewayResponseTypeDef",
+    {
+        "gatewayId": str,
+        "gatewayArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageFileTypeDef = TypedDict(
     "ImageFileTypeDef",
     {
         "data": Union[str, bytes, IO[Any], StreamingBody],
         "type": Literal["PNG"],
     },
 )
@@ -782,14 +808,23 @@
 )
 
 class CreateProjectRequestRequestTypeDef(
     _RequiredCreateProjectRequestRequestTypeDef, _OptionalCreateProjectRequestRequestTypeDef
 ):
     pass
 
+CreateProjectResponseTypeDef = TypedDict(
+    "CreateProjectResponseTypeDef",
+    {
+        "projectId": str,
+        "projectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CsvTypeDef = TypedDict(
     "CsvTypeDef",
     {
         "columnNames": Sequence[ColumnNameType],
     },
     total=False,
 )
@@ -1028,22 +1063,48 @@
 DescribeDashboardRequestRequestTypeDef = TypedDict(
     "DescribeDashboardRequestRequestTypeDef",
     {
         "dashboardId": str,
     },
 )
 
+DescribeDashboardResponseTypeDef = TypedDict(
+    "DescribeDashboardResponseTypeDef",
+    {
+        "dashboardId": str,
+        "dashboardArn": str,
+        "dashboardName": str,
+        "projectId": str,
+        "dashboardDescription": str,
+        "dashboardDefinition": str,
+        "dashboardCreationDate": datetime,
+        "dashboardLastUpdateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeGatewayCapabilityConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeGatewayCapabilityConfigurationRequestRequestTypeDef",
     {
         "gatewayId": str,
         "capabilityNamespace": str,
     },
 )
 
+DescribeGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
+    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
+    {
+        "gatewayId": str,
+        "capabilityNamespace": str,
+        "capabilityConfiguration": str,
+        "capabilitySyncStatus": CapabilitySyncStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeGatewayRequestRequestTypeDef = TypedDict(
     "DescribeGatewayRequestRequestTypeDef",
     {
         "gatewayId": str,
     },
 )
 
@@ -1080,14 +1141,28 @@
 DescribeProjectRequestRequestTypeDef = TypedDict(
     "DescribeProjectRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 
+DescribeProjectResponseTypeDef = TypedDict(
+    "DescribeProjectResponseTypeDef",
+    {
+        "projectId": str,
+        "projectArn": str,
+        "projectName": str,
+        "portalId": str,
+        "projectDescription": str,
+        "projectCreationDate": datetime,
+        "projectLastUpdateDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RetentionPeriodTypeDef = TypedDict(
     "RetentionPeriodTypeDef",
     {
         "numberOfDays": int,
         "unlimited": bool,
     },
     total=False,
@@ -1099,14 +1174,30 @@
         "alias": str,
         "assetId": str,
         "propertyId": str,
     },
     total=False,
 )
 
+DescribeTimeSeriesResponseTypeDef = TypedDict(
+    "DescribeTimeSeriesResponseTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "alias": str,
+        "timeSeriesId": str,
+        "dataType": PropertyDataTypeType,
+        "dataTypeSpec": str,
+        "timeSeriesCreationDate": datetime,
+        "timeSeriesLastUpdateDate": datetime,
+        "timeSeriesArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DetailedErrorTypeDef = TypedDict(
     "DetailedErrorTypeDef",
     {
         "code": DetailedErrorCodeType,
         "message": str,
     },
 )
@@ -1151,14 +1242,21 @@
 
 class DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef(
     _RequiredDisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
     _OptionalDisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredVariableValueTypeDef = TypedDict(
     "_RequiredVariableValueTypeDef",
     {
         "propertyId": str,
     },
 )
 _OptionalVariableValueTypeDef = TypedDict(
@@ -1189,24 +1287,42 @@
 GreengrassV2TypeDef = TypedDict(
     "GreengrassV2TypeDef",
     {
         "coreDeviceThingName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
+    "_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "aggregateTypes": Sequence[AggregateTypeType],
+        "resolution": str,
+        "startDate": Union[datetime, str],
+        "endDate": Union[datetime, str],
+    },
+)
+_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
+    "_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "propertyAlias": str,
+        "qualities": Sequence[QualityType],
+        "timeOrdering": TimeOrderingType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef(
+    _RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
+    _OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetAssetPropertyAggregatesRequestRequestTypeDef = TypedDict(
     "_RequiredGetAssetPropertyAggregatesRequestRequestTypeDef",
     {
         "aggregateTypes": Sequence[AggregateTypeType],
         "resolution": str,
         "startDate": Union[datetime, str],
         "endDate": Union[datetime, str],
@@ -1228,14 +1344,29 @@
 
 class GetAssetPropertyAggregatesRequestRequestTypeDef(
     _RequiredGetAssetPropertyAggregatesRequestRequestTypeDef,
     _OptionalGetAssetPropertyAggregatesRequestRequestTypeDef,
 ):
     pass
 
+GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef = TypedDict(
+    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "propertyAlias": str,
+        "startDate": Union[datetime, str],
+        "endDate": Union[datetime, str],
+        "qualities": Sequence[QualityType],
+        "timeOrdering": TimeOrderingType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetAssetPropertyValueHistoryRequestRequestTypeDef = TypedDict(
     "GetAssetPropertyValueHistoryRequestRequestTypeDef",
     {
         "assetId": str,
         "propertyId": str,
         "propertyAlias": str,
         "startDate": Union[datetime, str],
@@ -1254,14 +1385,44 @@
         "assetId": str,
         "propertyId": str,
         "propertyAlias": str,
     },
     total=False,
 )
 
+_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
+    "_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
+    {
+        "startTimeInSeconds": int,
+        "endTimeInSeconds": int,
+        "quality": QualityType,
+        "intervalInSeconds": int,
+        "type": str,
+    },
+)
+_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
+    "_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
+    {
+        "assetId": str,
+        "propertyId": str,
+        "propertyAlias": str,
+        "startTimeOffsetInNanos": int,
+        "endTimeOffsetInNanos": int,
+        "intervalWindowInSeconds": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef(
+    _RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
+    _OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetInterpolatedAssetPropertyValuesRequestRequestTypeDef = TypedDict(
     "_RequiredGetInterpolatedAssetPropertyValuesRequestRequestTypeDef",
     {
         "startTimeInSeconds": int,
         "endTimeInSeconds": int,
         "quality": QualityType,
         "intervalInSeconds": int,
@@ -1322,28 +1483,62 @@
     {
         "id": str,
         "name": str,
         "status": JobStatusType,
     },
 )
 
+ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef = TypedDict(
+    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
+    {
+        "identityType": IdentityTypeType,
+        "identityId": str,
+        "resourceType": ResourceTypeType,
+        "resourceId": str,
+        "iamArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAccessPoliciesRequestRequestTypeDef = TypedDict(
     "ListAccessPoliciesRequestRequestTypeDef",
     {
         "identityType": IdentityTypeType,
         "identityId": str,
         "resourceType": ResourceTypeType,
         "resourceId": str,
         "iamArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
+    "_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
+    {
+        "assetModelId": str,
+    },
+)
+_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
+    "_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
+    {
+        "filter": ListAssetModelPropertiesFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef(
+    _RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
+    _OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssetModelPropertiesRequestRequestTypeDef = TypedDict(
     "_RequiredListAssetModelPropertiesRequestRequestTypeDef",
     {
         "assetModelId": str,
     },
 )
 _OptionalListAssetModelPropertiesRequestRequestTypeDef = TypedDict(
@@ -1358,23 +1553,52 @@
 
 class ListAssetModelPropertiesRequestRequestTypeDef(
     _RequiredListAssetModelPropertiesRequestRequestTypeDef,
     _OptionalListAssetModelPropertiesRequestRequestTypeDef,
 ):
     pass
 
+ListAssetModelsRequestListAssetModelsPaginateTypeDef = TypedDict(
+    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssetModelsRequestRequestTypeDef = TypedDict(
     "ListAssetModelsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
+    "_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
+    {
+        "assetId": str,
+    },
+)
+_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
+    "_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
+    {
+        "filter": ListAssetPropertiesFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef(
+    _RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
+    _OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssetPropertiesRequestRequestTypeDef = TypedDict(
     "_RequiredListAssetPropertiesRequestRequestTypeDef",
     {
         "assetId": str,
     },
 )
 _OptionalListAssetPropertiesRequestRequestTypeDef = TypedDict(
@@ -1389,14 +1613,35 @@
 
 class ListAssetPropertiesRequestRequestTypeDef(
     _RequiredListAssetPropertiesRequestRequestTypeDef,
     _OptionalListAssetPropertiesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
+    "_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
+    {
+        "assetId": str,
+        "traversalType": Literal["PATH_TO_ROOT"],
+    },
+)
+_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
+    "_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef(
+    _RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
+    _OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssetRelationshipsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssetRelationshipsRequestRequestTypeDef",
     {
         "assetId": str,
         "traversalType": Literal["PATH_TO_ROOT"],
     },
 )
@@ -1411,25 +1656,57 @@
 
 class ListAssetRelationshipsRequestRequestTypeDef(
     _RequiredListAssetRelationshipsRequestRequestTypeDef,
     _OptionalListAssetRelationshipsRequestRequestTypeDef,
 ):
     pass
 
+ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
+    "ListAssetsRequestListAssetsPaginateTypeDef",
+    {
+        "assetModelId": str,
+        "filter": ListAssetsFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssetsRequestRequestTypeDef = TypedDict(
     "ListAssetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "assetModelId": str,
         "filter": ListAssetsFilterType,
     },
     total=False,
 )
 
+_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
+    {
+        "assetId": str,
+    },
+)
+_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
+    {
+        "hierarchyId": str,
+        "traversalDirection": TraversalDirectionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef(
+    _RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
+    _OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociatedAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedAssetsRequestRequestTypeDef",
     {
         "assetId": str,
     },
 )
 _OptionalListAssociatedAssetsRequestRequestTypeDef = TypedDict(
@@ -1445,24 +1722,53 @@
 
 class ListAssociatedAssetsRequestRequestTypeDef(
     _RequiredListAssociatedAssetsRequestRequestTypeDef,
     _OptionalListAssociatedAssetsRequestRequestTypeDef,
 ):
     pass
 
+ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef = TypedDict(
+    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
+    {
+        "filter": ListBulkImportJobsFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBulkImportJobsRequestRequestTypeDef = TypedDict(
     "ListBulkImportJobsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "filter": ListBulkImportJobsFilterType,
     },
     total=False,
 )
 
+_RequiredListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
+    "_RequiredListDashboardsRequestListDashboardsPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
+    "_OptionalListDashboardsRequestListDashboardsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDashboardsRequestListDashboardsPaginateTypeDef(
+    _RequiredListDashboardsRequestListDashboardsPaginateTypeDef,
+    _OptionalListDashboardsRequestListDashboardsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDashboardsRequestRequestTypeDef = TypedDict(
     "_RequiredListDashboardsRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListDashboardsRequestRequestTypeDef = TypedDict(
@@ -1475,32 +1781,68 @@
 )
 
 class ListDashboardsRequestRequestTypeDef(
     _RequiredListDashboardsRequestRequestTypeDef, _OptionalListDashboardsRequestRequestTypeDef
 ):
     pass
 
+ListGatewaysRequestListGatewaysPaginateTypeDef = TypedDict(
+    "ListGatewaysRequestListGatewaysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGatewaysRequestRequestTypeDef = TypedDict(
     "ListGatewaysRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListPortalsRequestListPortalsPaginateTypeDef = TypedDict(
+    "ListPortalsRequestListPortalsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPortalsRequestRequestTypeDef = TypedDict(
     "ListPortalsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProjectAssetsRequestListProjectAssetsPaginateTypeDef(
+    _RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
+    _OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListProjectAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectAssetsRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListProjectAssetsRequestRequestTypeDef = TypedDict(
@@ -1513,14 +1855,43 @@
 )
 
 class ListProjectAssetsRequestRequestTypeDef(
     _RequiredListProjectAssetsRequestRequestTypeDef, _OptionalListProjectAssetsRequestRequestTypeDef
 ):
     pass
 
+ListProjectAssetsResponseTypeDef = TypedDict(
+    "ListProjectAssetsResponseTypeDef",
+    {
+        "assetIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "_RequiredListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "portalId": str,
+    },
+)
+_OptionalListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "_OptionalListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProjectsRequestListProjectsPaginateTypeDef(
+    _RequiredListProjectsRequestListProjectsPaginateTypeDef,
+    _OptionalListProjectsRequestListProjectsPaginateTypeDef,
+):
+    pass
+
 _RequiredListProjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectsRequestRequestTypeDef",
     {
         "portalId": str,
     },
 )
 _OptionalListProjectsRequestRequestTypeDef = TypedDict(
@@ -1560,14 +1931,33 @@
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
+ListTimeSeriesRequestListTimeSeriesPaginateTypeDef = TypedDict(
+    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
+    {
+        "assetId": str,
+        "aliasPrefix": str,
+        "timeSeriesType": ListTimeSeriesTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTimeSeriesRequestRequestTypeDef = TypedDict(
     "ListTimeSeriesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "assetId": str,
         "aliasPrefix": str,
@@ -1579,14 +1969,15 @@
 _RequiredTimeSeriesSummaryTypeDef = TypedDict(
     "_RequiredTimeSeriesSummaryTypeDef",
     {
         "timeSeriesId": str,
         "dataType": PropertyDataTypeType,
         "timeSeriesCreationDate": datetime,
         "timeSeriesLastUpdateDate": datetime,
+        "timeSeriesArn": str,
     },
 )
 _OptionalTimeSeriesSummaryTypeDef = TypedDict(
     "_OptionalTimeSeriesSummaryTypeDef",
     {
         "assetId": str,
         "propertyId": str,
@@ -1630,14 +2021,24 @@
     {
         "code": MonitorErrorCodeType,
         "message": str,
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
 PortalResourceTypeDef = TypedDict(
     "PortalResourceTypeDef",
     {
         "id": str,
     },
 )
 
@@ -1664,14 +2065,25 @@
 
 class PutDefaultEncryptionConfigurationRequestRequestTypeDef(
     _RequiredPutDefaultEncryptionConfigurationRequestRequestTypeDef,
     _OptionalPutDefaultEncryptionConfigurationRequestRequestTypeDef,
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -1756,14 +2168,23 @@
     {
         "gatewayId": str,
         "capabilityNamespace": str,
         "capabilityConfiguration": str,
     },
 )
 
+UpdateGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
+    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
+    {
+        "capabilityNamespace": str,
+        "capabilitySyncStatus": CapabilitySyncStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateGatewayRequestRequestTypeDef = TypedDict(
     "UpdateGatewayRequestRequestTypeDef",
     {
         "gatewayId": str,
         "gatewayName": str,
     },
 )
@@ -1803,14 +2224,30 @@
     },
     total=False,
 )
 
 class AggregatedValueTypeDef(_RequiredAggregatedValueTypeDef, _OptionalAggregatedValueTypeDef):
     pass
 
+BatchAssociateProjectAssetsResponseTypeDef = TypedDict(
+    "BatchAssociateProjectAssetsResponseTypeDef",
+    {
+        "errors": List[AssetErrorDetailsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchDisassociateProjectAssetsResponseTypeDef = TypedDict(
+    "BatchDisassociateProjectAssetsResponseTypeDef",
+    {
+        "errors": List[AssetErrorDetailsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssetRelationshipSummaryTypeDef = TypedDict(
     "_RequiredAssetRelationshipSummaryTypeDef",
     {
         "relationshipType": Literal["HIERARCHY"],
     },
 )
 _OptionalAssetRelationshipSummaryTypeDef = TypedDict(
@@ -1893,164 +2330,14 @@
     "InterpolatedAssetPropertyValueTypeDef",
     {
         "timestamp": TimeInNanosTypeDef,
         "value": VariantTypeDef,
     },
 )
 
-BatchAssociateProjectAssetsResponseTypeDef = TypedDict(
-    "BatchAssociateProjectAssetsResponseTypeDef",
-    {
-        "errors": List[AssetErrorDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchDisassociateProjectAssetsResponseTypeDef = TypedDict(
-    "BatchDisassociateProjectAssetsResponseTypeDef",
-    {
-        "errors": List[AssetErrorDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessPolicyResponseTypeDef = TypedDict(
-    "CreateAccessPolicyResponseTypeDef",
-    {
-        "accessPolicyId": str,
-        "accessPolicyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBulkImportJobResponseTypeDef = TypedDict(
-    "CreateBulkImportJobResponseTypeDef",
-    {
-        "jobId": str,
-        "jobName": str,
-        "jobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDashboardResponseTypeDef = TypedDict(
-    "CreateDashboardResponseTypeDef",
-    {
-        "dashboardId": str,
-        "dashboardArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGatewayResponseTypeDef = TypedDict(
-    "CreateGatewayResponseTypeDef",
-    {
-        "gatewayId": str,
-        "gatewayArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProjectResponseTypeDef = TypedDict(
-    "CreateProjectResponseTypeDef",
-    {
-        "projectId": str,
-        "projectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDashboardResponseTypeDef = TypedDict(
-    "DescribeDashboardResponseTypeDef",
-    {
-        "dashboardId": str,
-        "dashboardArn": str,
-        "dashboardName": str,
-        "projectId": str,
-        "dashboardDescription": str,
-        "dashboardDefinition": str,
-        "dashboardCreationDate": datetime,
-        "dashboardLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
-    "DescribeGatewayCapabilityConfigurationResponseTypeDef",
-    {
-        "gatewayId": str,
-        "capabilityNamespace": str,
-        "capabilityConfiguration": str,
-        "capabilitySyncStatus": CapabilitySyncStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProjectResponseTypeDef = TypedDict(
-    "DescribeProjectResponseTypeDef",
-    {
-        "projectId": str,
-        "projectArn": str,
-        "projectName": str,
-        "portalId": str,
-        "projectDescription": str,
-        "projectCreationDate": datetime,
-        "projectLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeTimeSeriesResponseTypeDef = TypedDict(
-    "DescribeTimeSeriesResponseTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "alias": str,
-        "timeSeriesId": str,
-        "dataType": PropertyDataTypeType,
-        "dataTypeSpec": str,
-        "timeSeriesCreationDate": datetime,
-        "timeSeriesLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListProjectAssetsResponseTypeDef = TypedDict(
-    "ListProjectAssetsResponseTypeDef",
-    {
-        "assetIds": List[str],
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
-UpdateGatewayCapabilityConfigurationResponseTypeDef = TypedDict(
-    "UpdateGatewayCapabilityConfigurationResponseTypeDef",
-    {
-        "capabilityNamespace": str,
-        "capabilitySyncStatus": CapabilitySyncStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredBatchGetAssetPropertyAggregatesRequestRequestTypeDef = TypedDict(
     "_RequiredBatchGetAssetPropertyAggregatesRequestRequestTypeDef",
     {
         "entries": Sequence[BatchGetAssetPropertyAggregatesEntryTypeDef],
     },
 )
 _OptionalBatchGetAssetPropertyAggregatesRequestRequestTypeDef = TypedDict(
@@ -2243,15 +2530,15 @@
 )
 
 ListDashboardsResponseTypeDef = TypedDict(
     "ListDashboardsResponseTypeDef",
     {
         "dashboardSummaries": List[DashboardSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeAssetModelRequestAssetModelActiveWaitTypeDef = TypedDict(
     "_RequiredDescribeAssetModelRequestAssetModelActiveWaitTypeDef",
     {
         "assetModelId": str,
@@ -2375,15 +2662,15 @@
 ):
     pass
 
 DescribeLoggingOptionsResponseTypeDef = TypedDict(
     "DescribeLoggingOptionsResponseTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
@@ -2447,299 +2734,14 @@
     {
         "greengrass": GreengrassTypeDef,
         "greengrassV2": GreengrassV2TypeDef,
     },
     total=False,
 )
 
-_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
-    "_RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
-    {
-        "aggregateTypes": Sequence[AggregateTypeType],
-        "resolution": str,
-        "startDate": Union[datetime, str],
-        "endDate": Union[datetime, str],
-    },
-)
-_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef = TypedDict(
-    "_OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "propertyAlias": str,
-        "qualities": Sequence[QualityType],
-        "timeOrdering": TimeOrderingType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef(
-    _RequiredGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-    _OptionalGetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-):
-    pass
-
-GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef = TypedDict(
-    "GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "propertyAlias": str,
-        "startDate": Union[datetime, str],
-        "endDate": Union[datetime, str],
-        "qualities": Sequence[QualityType],
-        "timeOrdering": TimeOrderingType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
-    "_RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
-    {
-        "startTimeInSeconds": int,
-        "endTimeInSeconds": int,
-        "quality": QualityType,
-        "intervalInSeconds": int,
-        "type": str,
-    },
-)
-_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef = TypedDict(
-    "_OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef",
-    {
-        "assetId": str,
-        "propertyId": str,
-        "propertyAlias": str,
-        "startTimeOffsetInNanos": int,
-        "endTimeOffsetInNanos": int,
-        "intervalWindowInSeconds": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef(
-    _RequiredGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-    _OptionalGetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-):
-    pass
-
-ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef = TypedDict(
-    "ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef",
-    {
-        "identityType": IdentityTypeType,
-        "identityId": str,
-        "resourceType": ResourceTypeType,
-        "resourceId": str,
-        "iamArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
-    "_RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
-    {
-        "assetModelId": str,
-    },
-)
-_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef = TypedDict(
-    "_OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef",
-    {
-        "filter": ListAssetModelPropertiesFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef(
-    _RequiredListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-    _OptionalListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-):
-    pass
-
-ListAssetModelsRequestListAssetModelsPaginateTypeDef = TypedDict(
-    "ListAssetModelsRequestListAssetModelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
-    "_RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
-    {
-        "assetId": str,
-    },
-)
-_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef = TypedDict(
-    "_OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef",
-    {
-        "filter": ListAssetPropertiesFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef(
-    _RequiredListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-    _OptionalListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
-    "_RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
-    {
-        "assetId": str,
-        "traversalType": Literal["PATH_TO_ROOT"],
-    },
-)
-_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef = TypedDict(
-    "_OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef(
-    _RequiredListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-    _OptionalListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-):
-    pass
-
-ListAssetsRequestListAssetsPaginateTypeDef = TypedDict(
-    "ListAssetsRequestListAssetsPaginateTypeDef",
-    {
-        "assetModelId": str,
-        "filter": ListAssetsFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
-    {
-        "assetId": str,
-    },
-)
-_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef",
-    {
-        "hierarchyId": str,
-        "traversalDirection": TraversalDirectionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef(
-    _RequiredListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-    _OptionalListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-):
-    pass
-
-ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef = TypedDict(
-    "ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef",
-    {
-        "filter": ListBulkImportJobsFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
-    "_RequiredListDashboardsRequestListDashboardsPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListDashboardsRequestListDashboardsPaginateTypeDef = TypedDict(
-    "_OptionalListDashboardsRequestListDashboardsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDashboardsRequestListDashboardsPaginateTypeDef(
-    _RequiredListDashboardsRequestListDashboardsPaginateTypeDef,
-    _OptionalListDashboardsRequestListDashboardsPaginateTypeDef,
-):
-    pass
-
-ListGatewaysRequestListGatewaysPaginateTypeDef = TypedDict(
-    "ListGatewaysRequestListGatewaysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPortalsRequestListPortalsPaginateTypeDef = TypedDict(
-    "ListPortalsRequestListPortalsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProjectAssetsRequestListProjectAssetsPaginateTypeDef(
-    _RequiredListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-    _OptionalListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "_RequiredListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "portalId": str,
-    },
-)
-_OptionalListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "_OptionalListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProjectsRequestListProjectsPaginateTypeDef(
-    _RequiredListProjectsRequestListProjectsPaginateTypeDef,
-    _OptionalListProjectsRequestListProjectsPaginateTypeDef,
-):
-    pass
-
-ListTimeSeriesRequestListTimeSeriesPaginateTypeDef = TypedDict(
-    "ListTimeSeriesRequestListTimeSeriesPaginateTypeDef",
-    {
-        "assetId": str,
-        "aliasPrefix": str,
-        "timeSeriesType": ListTimeSeriesTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 IdentityTypeDef = TypedDict(
     "IdentityTypeDef",
     {
         "user": UserIdentityTypeDef,
         "group": GroupIdentityTypeDef,
         "iamUser": IAMUserIdentityTypeDef,
         "iamRole": IAMRoleIdentityTypeDef,
@@ -2748,33 +2750,33 @@
 )
 
 ListBulkImportJobsResponseTypeDef = TypedDict(
     "ListBulkImportJobsResponseTypeDef",
     {
         "jobSummaries": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "projectSummaries": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTimeSeriesResponseTypeDef = TypedDict(
     "ListTimeSeriesResponseTypeDef",
     {
         "TimeSeriesSummaries": List[TimeSeriesSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricWindowTypeDef = TypedDict(
     "MetricWindowTypeDef",
     {
         "tumbling": TumblingWindowTypeDef,
@@ -2817,33 +2819,33 @@
 )
 
 GetAssetPropertyAggregatesResponseTypeDef = TypedDict(
     "GetAssetPropertyAggregatesResponseTypeDef",
     {
         "aggregatedValues": List[AggregatedValueTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetRelationshipsResponseTypeDef = TypedDict(
     "ListAssetRelationshipsResponseTypeDef",
     {
         "assetRelationshipSummaries": List[AssetRelationshipSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetPropertiesResponseTypeDef = TypedDict(
     "ListAssetPropertiesResponseTypeDef",
     {
         "assetPropertySummaries": List[AssetPropertySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetCompositeModelTypeDef = TypedDict(
     "_RequiredAssetCompositeModelTypeDef",
     {
         "name": str,
@@ -2902,23 +2904,23 @@
     pass
 
 GetAssetPropertyValueHistoryResponseTypeDef = TypedDict(
     "GetAssetPropertyValueHistoryResponseTypeDef",
     {
         "assetPropertyValueHistory": List[AssetPropertyValueTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssetPropertyValueResponseTypeDef = TypedDict(
     "GetAssetPropertyValueResponseTypeDef",
     {
         "propertyValue": AssetPropertyValueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAssetPropertyValueEntryTypeDef = TypedDict(
     "_RequiredPutAssetPropertyValueEntryTypeDef",
     {
         "entryId": str,
@@ -2941,35 +2943,35 @@
     pass
 
 GetInterpolatedAssetPropertyValuesResponseTypeDef = TypedDict(
     "GetInterpolatedAssetPropertyValuesResponseTypeDef",
     {
         "interpolatedAssetPropertyValues": List[InterpolatedAssetPropertyValueTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDefaultEncryptionConfigurationResponseTypeDef = TypedDict(
     "DescribeDefaultEncryptionConfigurationResponseTypeDef",
     {
         "encryptionType": EncryptionTypeType,
         "kmsKeyArn": str,
         "configurationStatus": ConfigurationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDefaultEncryptionConfigurationResponseTypeDef = TypedDict(
     "PutDefaultEncryptionConfigurationResponseTypeDef",
     {
         "encryptionType": EncryptionTypeType,
         "kmsKeyArn": str,
         "configurationStatus": ConfigurationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePortalRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePortalRequestRequestTypeDef",
     {
         "portalId": str,
@@ -3007,15 +3009,15 @@
     {
         "storageType": StorageTypeType,
         "multiLayerStorage": MultiLayerStorageTypeDef,
         "disassociatedDataStorage": DisassociatedDataStorageStateType,
         "retentionPeriod": RetentionPeriodTypeDef,
         "configurationStatus": ConfigurationStatusTypeDef,
         "lastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutStorageConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutStorageConfigurationRequestRequestTypeDef",
     {
         "storageType": StorageTypeType,
@@ -3041,15 +3043,15 @@
     "PutStorageConfigurationResponseTypeDef",
     {
         "storageType": StorageTypeType,
         "multiLayerStorage": MultiLayerStorageTypeDef,
         "disassociatedDataStorage": DisassociatedDataStorageStateType,
         "retentionPeriod": RetentionPeriodTypeDef,
         "configurationStatus": ConfigurationStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetModelStatusTypeDef = TypedDict(
     "_RequiredAssetModelStatusTypeDef",
     {
         "state": AssetModelStateType,
@@ -3135,15 +3137,15 @@
         "gatewayId": str,
         "gatewayName": str,
         "gatewayArn": str,
         "gatewayPlatform": GatewayPlatformTypeDef,
         "gatewayCapabilitySummaries": List[GatewayCapabilitySummaryTypeDef],
         "creationDate": datetime,
         "lastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGatewaySummaryTypeDef = TypedDict(
     "_RequiredGatewaySummaryTypeDef",
     {
         "gatewayId": str,
@@ -3187,23 +3189,23 @@
     "CreatePortalResponseTypeDef",
     {
         "portalId": str,
         "portalArn": str,
         "portalStartUrl": str,
         "portalStatus": PortalStatusTypeDef,
         "ssoApplicationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePortalResponseTypeDef = TypedDict(
     "DeletePortalResponseTypeDef",
     {
         "portalStatus": PortalStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePortalResponseTypeDef = TypedDict(
     "DescribePortalResponseTypeDef",
     {
         "portalId": str,
@@ -3217,15 +3219,15 @@
         "portalCreationDate": datetime,
         "portalLastUpdateDate": datetime,
         "portalLogoImageLocation": ImageLocationTypeDef,
         "roleArn": str,
         "portalAuthMode": AuthModeType,
         "notificationSenderEmail": str,
         "alarms": AlarmsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPortalSummaryTypeDef = TypedDict(
     "_RequiredPortalSummaryTypeDef",
     {
         "id": str,
@@ -3248,15 +3250,15 @@
 class PortalSummaryTypeDef(_RequiredPortalSummaryTypeDef, _OptionalPortalSummaryTypeDef):
     pass
 
 UpdatePortalResponseTypeDef = TypedDict(
     "UpdatePortalResponseTypeDef",
     {
         "portalStatus": PortalStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAccessPolicySummaryTypeDef = TypedDict(
     "_RequiredAccessPolicySummaryTypeDef",
     {
         "id": str,
@@ -3308,15 +3310,15 @@
         "accessPolicyId": str,
         "accessPolicyArn": str,
         "accessPolicyIdentity": IdentityTypeDef,
         "accessPolicyResource": ResourceTypeDef,
         "accessPolicyPermission": PermissionType,
         "accessPolicyCreationDate": datetime,
         "accessPolicyLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAccessPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAccessPolicyRequestRequestTypeDef",
     {
         "accessPolicyId": str,
@@ -3342,45 +3344,45 @@
 BatchGetAssetPropertyAggregatesResponseTypeDef = TypedDict(
     "BatchGetAssetPropertyAggregatesResponseTypeDef",
     {
         "errorEntries": List[BatchGetAssetPropertyAggregatesErrorEntryTypeDef],
         "successEntries": List[BatchGetAssetPropertyAggregatesSuccessEntryTypeDef],
         "skippedEntries": List[BatchGetAssetPropertyAggregatesSkippedEntryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutAssetPropertyValueResponseTypeDef = TypedDict(
     "BatchPutAssetPropertyValueResponseTypeDef",
     {
         "errorEntries": List[BatchPutAssetPropertyErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetAssetPropertyValueHistoryResponseTypeDef = TypedDict(
     "BatchGetAssetPropertyValueHistoryResponseTypeDef",
     {
         "errorEntries": List[BatchGetAssetPropertyValueHistoryErrorEntryTypeDef],
         "successEntries": List[BatchGetAssetPropertyValueHistorySuccessEntryTypeDef],
         "skippedEntries": List[BatchGetAssetPropertyValueHistorySkippedEntryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetAssetPropertyValueResponseTypeDef = TypedDict(
     "BatchGetAssetPropertyValueResponseTypeDef",
     {
         "errorEntries": List[BatchGetAssetPropertyValueErrorEntryTypeDef],
         "successEntries": List[BatchGetAssetPropertyValueSuccessEntryTypeDef],
         "skippedEntries": List[BatchGetAssetPropertyValueSkippedEntryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutAssetPropertyValueRequestRequestTypeDef = TypedDict(
     "BatchPutAssetPropertyValueRequestRequestTypeDef",
     {
         "entries": Sequence[PutAssetPropertyValueEntryTypeDef],
@@ -3406,15 +3408,15 @@
         "jobStatus": JobStatusType,
         "jobRoleArn": str,
         "files": List[FileTypeDef],
         "errorReportLocation": ErrorReportLocationTypeDef,
         "jobConfiguration": JobConfigurationTypeDef,
         "jobCreationDate": datetime,
         "jobLastUpdateDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssetModelSummaryTypeDef = TypedDict(
     "AssetModelSummaryTypeDef",
     {
         "id": str,
@@ -3429,31 +3431,31 @@
 
 CreateAssetModelResponseTypeDef = TypedDict(
     "CreateAssetModelResponseTypeDef",
     {
         "assetModelId": str,
         "assetModelArn": str,
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAssetModelResponseTypeDef = TypedDict(
     "DeleteAssetModelResponseTypeDef",
     {
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssetModelResponseTypeDef = TypedDict(
     "UpdateAssetModelResponseTypeDef",
     {
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetSummaryTypeDef = TypedDict(
     "_RequiredAssetSummaryTypeDef",
     {
         "id": str,
@@ -3505,23 +3507,23 @@
 
 CreateAssetResponseTypeDef = TypedDict(
     "CreateAssetResponseTypeDef",
     {
         "assetId": str,
         "assetArn": str,
         "assetStatus": AssetStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAssetResponseTypeDef = TypedDict(
     "DeleteAssetResponseTypeDef",
     {
         "assetStatus": AssetStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssetResponseTypeDef = TypedDict(
     "DescribeAssetResponseTypeDef",
     {
         "assetId": str,
@@ -3531,32 +3533,32 @@
         "assetProperties": List[AssetPropertyTypeDef],
         "assetHierarchies": List[AssetHierarchyTypeDef],
         "assetCompositeModels": List[AssetCompositeModelTypeDef],
         "assetCreationDate": datetime,
         "assetLastUpdateDate": datetime,
         "assetStatus": AssetStatusTypeDef,
         "assetDescription": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssetResponseTypeDef = TypedDict(
     "UpdateAssetResponseTypeDef",
     {
         "assetStatus": AssetStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGatewaysResponseTypeDef = TypedDict(
     "ListGatewaysResponseTypeDef",
     {
         "gatewaySummaries": List[GatewaySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PropertyTypeTypeDef = TypedDict(
     "PropertyTypeTypeDef",
     {
         "attribute": AttributeTypeDef,
@@ -3568,51 +3570,51 @@
 )
 
 ListPortalsResponseTypeDef = TypedDict(
     "ListPortalsResponseTypeDef",
     {
         "portalSummaries": List[PortalSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccessPoliciesResponseTypeDef = TypedDict(
     "ListAccessPoliciesResponseTypeDef",
     {
         "accessPolicySummaries": List[AccessPolicySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetModelsResponseTypeDef = TypedDict(
     "ListAssetModelsResponseTypeDef",
     {
         "assetModelSummaries": List[AssetModelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssetsResponseTypeDef = TypedDict(
     "ListAssetsResponseTypeDef",
     {
         "assetSummaries": List[AssetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssociatedAssetsResponseTypeDef = TypedDict(
     "ListAssociatedAssetsResponseTypeDef",
     {
         "assetSummaries": List[AssociatedAssetsSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetModelPropertyDefinitionTypeDef = TypedDict(
     "_RequiredAssetModelPropertyDefinitionTypeDef",
     {
         "name": str,
@@ -3726,15 +3728,15 @@
     pass
 
 ListAssetModelPropertiesResponseTypeDef = TypedDict(
     "ListAssetModelPropertiesResponseTypeDef",
     {
         "assetModelPropertySummaries": List[AssetModelPropertySummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetModelCompositeModelTypeDef = TypedDict(
     "_RequiredAssetModelCompositeModelTypeDef",
     {
         "name": str,
@@ -3810,15 +3812,15 @@
         "assetModelDescription": str,
         "assetModelProperties": List[AssetModelPropertyTypeDef],
         "assetModelHierarchies": List[AssetModelHierarchyTypeDef],
         "assetModelCompositeModels": List[AssetModelCompositeModelTypeDef],
         "assetModelCreationDate": datetime,
         "assetModelLastUpdateDate": datetime,
         "assetModelStatus": AssetModelStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAssetModelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAssetModelRequestRequestTypeDef",
     {
         "assetModelId": str,
@@ -3846,10 +3848,10 @@
     "DescribeAssetPropertyResponseTypeDef",
     {
         "assetId": str,
         "assetName": str,
         "assetModelId": str,
         "assetProperty": PropertyTypeDef,
         "compositeModel": CompositeModelPropertyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/waiter.py` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise/waiter.pyi` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/PKG-INFO` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotsitewise
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTSiteWise 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTSiteWise 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotsitewise"></a>
 
 # types-aiobotocore-iotsitewise
 
 [![PyPI - types-aiobotocore-iotsitewise](https://img.shields.io/pypi/v/types-aiobotocore-iotsitewise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsitewise)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotsitewise.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsitewise)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotsitewise?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotsitewise)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTSiteWise 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
+[aiobotocore.IoTSiteWise 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsitewise.html#IoTSiteWise)
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
 [types-aiobotocore-iotsitewise docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsitewise/).
 
 See how it helps to find and fix potential bugs:
 
@@ -484,32 +484,36 @@
     PropertyNotificationTypeDef,
     TimeInNanosTypeDef,
     VariantTypeDef,
     AssociateAssetsRequestRequestTypeDef,
     AssociateTimeSeriesToAssetPropertyRequestRequestTypeDef,
     AttributeTypeDef,
     BatchAssociateProjectAssetsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BatchDisassociateProjectAssetsRequestRequestTypeDef,
     BatchGetAssetPropertyAggregatesEntryTypeDef,
     BatchGetAssetPropertyAggregatesErrorEntryTypeDef,
     BatchGetAssetPropertyAggregatesErrorInfoTypeDef,
     BatchGetAssetPropertyValueEntryTypeDef,
     BatchGetAssetPropertyValueErrorEntryTypeDef,
     BatchGetAssetPropertyValueErrorInfoTypeDef,
     BatchGetAssetPropertyValueHistoryEntryTypeDef,
     BatchGetAssetPropertyValueHistoryErrorEntryTypeDef,
     BatchGetAssetPropertyValueHistoryErrorInfoTypeDef,
     ConfigurationErrorDetailsTypeDef,
+    CreateAccessPolicyResponseTypeDef,
     CreateAssetRequestRequestTypeDef,
     ErrorReportLocationTypeDef,
     FileTypeDef,
+    CreateBulkImportJobResponseTypeDef,
     CreateDashboardRequestRequestTypeDef,
+    CreateDashboardResponseTypeDef,
+    CreateGatewayResponseTypeDef,
     ImageFileTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
     CsvTypeDef,
     CustomerManagedS3StorageTypeDef,
     DashboardSummaryTypeDef,
     DeleteAccessPolicyRequestRequestTypeDef,
     DeleteAssetModelRequestRequestTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeleteDashboardRequestRequestTypeDef,
@@ -520,93 +524,106 @@
     DescribeAccessPolicyRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeAssetModelRequestRequestTypeDef,
     DescribeAssetPropertyRequestRequestTypeDef,
     DescribeAssetRequestRequestTypeDef,
     DescribeBulkImportJobRequestRequestTypeDef,
     DescribeDashboardRequestRequestTypeDef,
+    DescribeDashboardResponseTypeDef,
     DescribeGatewayCapabilityConfigurationRequestRequestTypeDef,
+    DescribeGatewayCapabilityConfigurationResponseTypeDef,
     DescribeGatewayRequestRequestTypeDef,
     GatewayCapabilitySummaryTypeDef,
     LoggingOptionsTypeDef,
     DescribePortalRequestRequestTypeDef,
     ImageLocationTypeDef,
     DescribeProjectRequestRequestTypeDef,
+    DescribeProjectResponseTypeDef,
     RetentionPeriodTypeDef,
     DescribeTimeSeriesRequestRequestTypeDef,
+    DescribeTimeSeriesResponseTypeDef,
     DetailedErrorTypeDef,
     DisassociateAssetsRequestRequestTypeDef,
     DisassociateTimeSeriesFromAssetPropertyRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     VariableValueTypeDef,
     ForwardingConfigTypeDef,
     GreengrassTypeDef,
     GreengrassV2TypeDef,
-    PaginatorConfigTypeDef,
+    GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
     GetAssetPropertyAggregatesRequestRequestTypeDef,
+    GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef,
     GetAssetPropertyValueHistoryRequestRequestTypeDef,
     GetAssetPropertyValueRequestRequestTypeDef,
+    GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
     GetInterpolatedAssetPropertyValuesRequestRequestTypeDef,
     GroupIdentityTypeDef,
     IAMRoleIdentityTypeDef,
     IAMUserIdentityTypeDef,
     UserIdentityTypeDef,
     JobSummaryTypeDef,
+    ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef,
     ListAccessPoliciesRequestRequestTypeDef,
+    ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
     ListAssetModelPropertiesRequestRequestTypeDef,
+    ListAssetModelsRequestListAssetModelsPaginateTypeDef,
     ListAssetModelsRequestRequestTypeDef,
+    ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
     ListAssetPropertiesRequestRequestTypeDef,
+    ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
     ListAssetRelationshipsRequestRequestTypeDef,
+    ListAssetsRequestListAssetsPaginateTypeDef,
     ListAssetsRequestRequestTypeDef,
+    ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
     ListAssociatedAssetsRequestRequestTypeDef,
+    ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef,
     ListBulkImportJobsRequestRequestTypeDef,
+    ListDashboardsRequestListDashboardsPaginateTypeDef,
     ListDashboardsRequestRequestTypeDef,
+    ListGatewaysRequestListGatewaysPaginateTypeDef,
     ListGatewaysRequestRequestTypeDef,
+    ListPortalsRequestListPortalsPaginateTypeDef,
     ListPortalsRequestRequestTypeDef,
+    ListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
     ListProjectAssetsRequestRequestTypeDef,
+    ListProjectAssetsResponseTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTimeSeriesRequestListTimeSeriesPaginateTypeDef,
     ListTimeSeriesRequestRequestTypeDef,
     TimeSeriesSummaryTypeDef,
     MetricProcessingConfigTypeDef,
     TumblingWindowTypeDef,
     MonitorErrorDetailsTypeDef,
+    PaginatorConfigTypeDef,
     PortalResourceTypeDef,
     ProjectResourceTypeDef,
     PutDefaultEncryptionConfigurationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssetPropertyRequestRequestTypeDef,
     UpdateAssetRequestRequestTypeDef,
     UpdateDashboardRequestRequestTypeDef,
     UpdateGatewayCapabilityConfigurationRequestRequestTypeDef,
+    UpdateGatewayCapabilityConfigurationResponseTypeDef,
     UpdateGatewayRequestRequestTypeDef,
     UpdateProjectRequestRequestTypeDef,
     AggregatedValueTypeDef,
+    BatchAssociateProjectAssetsResponseTypeDef,
+    BatchDisassociateProjectAssetsResponseTypeDef,
     AssetRelationshipSummaryTypeDef,
     AssetPropertySummaryTypeDef,
     AssetPropertyTypeDef,
     BatchPutAssetPropertyErrorTypeDef,
     AssetPropertyValueTypeDef,
     InterpolatedAssetPropertyValueTypeDef,
-    BatchAssociateProjectAssetsResponseTypeDef,
-    BatchDisassociateProjectAssetsResponseTypeDef,
-    CreateAccessPolicyResponseTypeDef,
-    CreateBulkImportJobResponseTypeDef,
-    CreateDashboardResponseTypeDef,
-    CreateGatewayResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    DescribeDashboardResponseTypeDef,
-    DescribeGatewayCapabilityConfigurationResponseTypeDef,
-    DescribeProjectResponseTypeDef,
-    DescribeTimeSeriesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListProjectAssetsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateGatewayCapabilityConfigurationResponseTypeDef,
     BatchGetAssetPropertyAggregatesRequestRequestTypeDef,
     BatchGetAssetPropertyAggregatesSkippedEntryTypeDef,
     BatchGetAssetPropertyValueRequestRequestTypeDef,
     BatchGetAssetPropertyValueSkippedEntryTypeDef,
     BatchGetAssetPropertyValueHistoryRequestRequestTypeDef,
     BatchGetAssetPropertyValueHistorySkippedEntryTypeDef,
     ConfigurationStatusTypeDef,
@@ -624,31 +641,14 @@
     DescribeLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     ErrorDetailsTypeDef,
     ExpressionVariableTypeDef,
     MeasurementProcessingConfigTypeDef,
     TransformProcessingConfigTypeDef,
     GatewayPlatformTypeDef,
-    GetAssetPropertyAggregatesRequestGetAssetPropertyAggregatesPaginateTypeDef,
-    GetAssetPropertyValueHistoryRequestGetAssetPropertyValueHistoryPaginateTypeDef,
-    GetInterpolatedAssetPropertyValuesRequestGetInterpolatedAssetPropertyValuesPaginateTypeDef,
-    ListAccessPoliciesRequestListAccessPoliciesPaginateTypeDef,
-    ListAssetModelPropertiesRequestListAssetModelPropertiesPaginateTypeDef,
-    ListAssetModelsRequestListAssetModelsPaginateTypeDef,
-    ListAssetPropertiesRequestListAssetPropertiesPaginateTypeDef,
-    ListAssetRelationshipsRequestListAssetRelationshipsPaginateTypeDef,
-    ListAssetsRequestListAssetsPaginateTypeDef,
-    ListAssociatedAssetsRequestListAssociatedAssetsPaginateTypeDef,
-    ListBulkImportJobsRequestListBulkImportJobsPaginateTypeDef,
-    ListDashboardsRequestListDashboardsPaginateTypeDef,
-    ListGatewaysRequestListGatewaysPaginateTypeDef,
-    ListPortalsRequestListPortalsPaginateTypeDef,
-    ListProjectAssetsRequestListProjectAssetsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListTimeSeriesRequestListTimeSeriesPaginateTypeDef,
     IdentityTypeDef,
     ListBulkImportJobsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListTimeSeriesResponseTypeDef,
     MetricWindowTypeDef,
     PortalStatusTypeDef,
     ResourceTypeDef,
@@ -734,43 +734,43 @@
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

### Comparing `types-aiobotocore-iotsitewise-2.5.0.post1/types_aiobotocore_iotsitewise.egg-info/SOURCES.txt` & `types-aiobotocore-iotsitewise-2.5.1/types_aiobotocore_iotsitewise.egg-info/SOURCES.txt`

 * *Files identical despite different names*

