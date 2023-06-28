# Comparing `tmp/types-aiobotocore-dms-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-dms-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-dms-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:31 2023, max compression
+gzip compressed data, was "types-aiobotocore-dms-2.5.1.tar", last modified: Wed Jun 28 01:43:23 2023, max compression
```

## Comparing `types-aiobotocore-dms-2.5.0.post1.tar` & `types-aiobotocore-dms-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.703143 types-aiobotocore-dms-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    28265 2023-03-11 12:26:31.695143 types-aiobotocore-dms-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    26689 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:31.703143 types-aiobotocore-dms-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2093 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.695143 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/
--rw-r--r--   0 runner    (1001) docker     (123)     5651 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5650 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      958 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    66375 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    66280 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14410 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14408 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17917 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    17901 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    87986 2023-03-11 12:12:37.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    87935 2023-03-11 12:12:35.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:33.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    10058 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)    10050 2023-03-11 12:12:34.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.695143 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    28265 2023-03-11 12:26:31.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:31.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:31.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:31.000000 types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:23.810126 types-aiobotocore-dms-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    28954 2023-06-28 01:43:23.810126 types-aiobotocore-dms-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    27384 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:23.810126 types-aiobotocore-dms-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2087 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:23.810126 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/
+-rw-r--r--   0 runner    (1001) docker     (123)     5651 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5650 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69200 2023-06-28 01:29:13.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69101 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14827 2023-06-28 01:29:14.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14825 2023-06-28 01:29:14.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17836 2023-06-28 01:29:13.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17820 2023-06-28 01:29:13.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    92980 2023-06-28 01:29:15.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    92929 2023-06-28 01:29:15.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:12.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10058 2023-06-28 01:29:14.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10050 2023-06-28 01:29:13.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:23.810126 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    28954 2023-06-28 01:43:23.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:23.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:23.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:23.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:23.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:23.000000 types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/LICENSE` & `types-aiobotocore-dms-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-dms-2.5.0.post1/PKG-INFO` & `types-aiobotocore-dms-2.5.1/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DatabaseMigrationService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DatabaseMigrationService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dms"></a>
 
 # types-aiobotocore-dms
 
 [![PyPI - types-aiobotocore-dms](https://img.shields.io/pypi/v/types-aiobotocore-dms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dms?color=blue)](https://pypistats.org/packages/types-aiobotocore-dms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DatabaseMigrationService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
+[aiobotocore.DatabaseMigrationService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
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
 [types-aiobotocore-dms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -419,14 +419,15 @@
     DescribeSchemasPaginatorName,
     DescribeTableStatisticsPaginatorName,
     DmsSslModeValueType,
     EncodingTypeValueType,
     EncryptionModeValueType,
     EndpointDeletedWaiterName,
     EndpointSettingTypeValueType,
+    KafkaSaslMechanismType,
     KafkaSecurityProtocolType,
     MessageFormatValueType,
     MigrationTypeValueType,
     NestingLevelValueType,
     ParquetVersionValueType,
     PluginNameValueType,
     RedisAuthTypeValueType,
@@ -442,14 +443,15 @@
     ReplicationTaskStoppedWaiterName,
     SafeguardPolicyType,
     SourceTypeType,
     SslSecurityProtocolValueType,
     StartReplicationTaskTypeValueType,
     TargetDbTypeType,
     TestConnectionSucceedsWaiterName,
+    TlogAccessModeType,
     VersionStatusType,
     DatabaseMigrationServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
     RegionName,
@@ -468,16 +470,16 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dms.type_defs import (
     AccountQuotaTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
-    ResponseMetadataTypeDef,
     AvailabilityZoneTypeDef,
+    BatchStartRecommendationsErrorEntryTypeDef,
     CancelReplicationTaskAssessmentRunMessageRequestTypeDef,
     CertificateTypeDef,
     CollectorHealthCheckTypeDef,
     InventoryDataTypeDef,
     CollectorShortInfoResponseTypeDef,
     ConnectionTypeDef,
     DmsTransferSettingsTypeDef,
@@ -496,89 +498,98 @@
     PostgreSQLSettingsTypeDef,
     RedisSettingsTypeDef,
     RedshiftSettingsTypeDef,
     S3SettingsTypeDef,
     SybaseSettingsTypeDef,
     EventSubscriptionTypeDef,
     CreateFleetAdvisorCollectorRequestRequestTypeDef,
+    CreateFleetAdvisorCollectorResponseTypeDef,
     DatabaseInstanceSoftwareDetailsResponseTypeDef,
     ServerShortInfoResponseTypeDef,
     DatabaseShortInfoResponseTypeDef,
     DeleteCertificateMessageRequestTypeDef,
     DeleteCollectorRequestRequestTypeDef,
     DeleteConnectionMessageRequestTypeDef,
     DeleteEndpointMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteFleetAdvisorDatabasesRequestRequestTypeDef,
+    DeleteFleetAdvisorDatabasesResponseTypeDef,
     DeleteReplicationInstanceMessageRequestTypeDef,
     DeleteReplicationSubnetGroupMessageRequestTypeDef,
     DeleteReplicationTaskAssessmentRunMessageRequestTypeDef,
     DeleteReplicationTaskMessageRequestTypeDef,
     DescribeApplicableIndividualAssessmentsMessageRequestTypeDef,
+    DescribeApplicableIndividualAssessmentsResponseTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     WaiterConfigTypeDef,
     DescribeEndpointSettingsMessageRequestTypeDef,
     EndpointSettingTypeDef,
     SupportedEndpointTypeTypeDef,
     EventCategoryGroupTypeDef,
     EventTypeDef,
     DescribeFleetAdvisorLsaAnalysisRequestRequestTypeDef,
     FleetAdvisorLsaAnalysisResponseTypeDef,
     FleetAdvisorSchemaObjectResponseTypeDef,
+    DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef,
     DescribeOrderableReplicationInstancesMessageRequestTypeDef,
     OrderableReplicationInstanceTypeDef,
+    LimitationTypeDef,
     DescribeRefreshSchemasStatusMessageRequestTypeDef,
     RefreshSchemasStatusTypeDef,
     DescribeReplicationInstanceTaskLogsMessageRequestTypeDef,
     ReplicationInstanceTaskLogTypeDef,
+    DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef,
     DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef,
     ReplicationTaskAssessmentResultTypeDef,
     ReplicationTaskIndividualAssessmentTypeDef,
+    DescribeSchemasMessageDescribeSchemasPaginateTypeDef,
     DescribeSchemasMessageRequestTypeDef,
+    DescribeSchemasResponseTypeDef,
     TableStatisticsTypeDef,
+    EmptyResponseMetadataTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyReplicationInstanceMessageRequestTypeDef,
     ModifyReplicationSubnetGroupMessageRequestTypeDef,
     ModifyReplicationTaskMessageRequestTypeDef,
     MoveReplicationTaskMessageRequestTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
+    RdsConfigurationTypeDef,
+    RdsRequirementsTypeDef,
     RebootReplicationInstanceMessageRequestTypeDef,
+    RecommendationSettingsTypeDef,
     RefreshSchemasMessageRequestTypeDef,
     TableToReloadTypeDef,
+    ReloadTablesResponseTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
     ReplicationPendingModifiedValuesTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     ReplicationTaskAssessmentRunProgressTypeDef,
     ReplicationTaskStatsTypeDef,
+    ResponseMetadataTypeDef,
+    RunFleetAdvisorLsaAnalysisResponseTypeDef,
     SchemaShortInfoResponseTypeDef,
     StartReplicationTaskAssessmentMessageRequestTypeDef,
     StartReplicationTaskAssessmentRunMessageRequestTypeDef,
     StartReplicationTaskMessageRequestTypeDef,
     StopReplicationTaskMessageRequestTypeDef,
     TestConnectionMessageRequestTypeDef,
     UpdateSubscriptionsToEventBridgeMessageRequestTypeDef,
+    UpdateSubscriptionsToEventBridgeResponseTypeDef,
+    DescribeAccountAttributesResponseTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CreateEventSubscriptionMessageRequestTypeDef,
     CreateReplicationInstanceMessageRequestTypeDef,
     CreateReplicationSubnetGroupMessageRequestTypeDef,
     CreateReplicationTaskMessageRequestTypeDef,
     ImportCertificateMessageRequestTypeDef,
-    CreateFleetAdvisorCollectorResponseTypeDef,
-    DeleteFleetAdvisorDatabasesResponseTypeDef,
-    DescribeAccountAttributesResponseTypeDef,
-    DescribeApplicableIndividualAssessmentsResponseTypeDef,
-    DescribeSchemasResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    ReloadTablesResponseTypeDef,
-    RunFleetAdvisorLsaAnalysisResponseTypeDef,
-    UpdateSubscriptionsToEventBridgeResponseTypeDef,
     SubnetTypeDef,
+    BatchStartRecommendationsResponseTypeDef,
     DeleteCertificateResponseTypeDef,
     DescribeCertificatesResponseTypeDef,
     ImportCertificateResponseTypeDef,
     CollectorResponseTypeDef,
     DeleteConnectionResponseTypeDef,
     DescribeConnectionsResponseTypeDef,
     TestConnectionResponseTypeDef,
@@ -586,45 +597,44 @@
     EndpointTypeDef,
     ModifyEndpointMessageRequestTypeDef,
     CreateEventSubscriptionResponseTypeDef,
     DeleteEventSubscriptionResponseTypeDef,
     DescribeEventSubscriptionsResponseTypeDef,
     ModifyEventSubscriptionResponseTypeDef,
     DatabaseResponseTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
+    DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef,
     DescribeConnectionsMessageRequestTypeDef,
+    DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef,
     DescribeEndpointTypesMessageRequestTypeDef,
+    DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef,
     DescribeEndpointsMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
     DescribeFleetAdvisorCollectorsRequestRequestTypeDef,
     DescribeFleetAdvisorDatabasesRequestRequestTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryRequestRequestTypeDef,
     DescribeFleetAdvisorSchemasRequestRequestTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
+    DescribeRecommendationLimitationsRequestRequestTypeDef,
+    DescribeRecommendationsRequestRequestTypeDef,
+    DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef,
     DescribeReplicationInstancesMessageRequestTypeDef,
+    DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef,
     DescribeReplicationSubnetGroupsMessageRequestTypeDef,
     DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef,
     DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef,
-    DescribeReplicationTasksMessageRequestTypeDef,
-    DescribeTableStatisticsMessageRequestTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef,
-    DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef,
-    DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef,
-    DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef,
-    DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef,
-    DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef,
     DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef,
-    DescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+    DescribeReplicationTasksMessageRequestTypeDef,
     DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+    DescribeTableStatisticsMessageRequestTypeDef,
     DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef,
     DescribeEndpointsMessageEndpointDeletedWaitTypeDef,
     DescribeReplicationInstancesMessageReplicationInstanceAvailableWaitTypeDef,
     DescribeReplicationInstancesMessageReplicationInstanceDeletedWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskDeletedWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskReadyWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskRunningWaitTypeDef,
@@ -632,34 +642,40 @@
     DescribeEndpointSettingsResponseTypeDef,
     DescribeEndpointTypesResponseTypeDef,
     DescribeEventCategoriesResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeFleetAdvisorLsaAnalysisResponseTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef,
     DescribeOrderableReplicationInstancesResponseTypeDef,
+    DescribeRecommendationLimitationsResponseTypeDef,
     DescribeRefreshSchemasStatusResponseTypeDef,
     RefreshSchemasResponseTypeDef,
     DescribeReplicationInstanceTaskLogsResponseTypeDef,
     DescribeReplicationTaskAssessmentResultsResponseTypeDef,
     DescribeReplicationTaskIndividualAssessmentsResponseTypeDef,
     DescribeTableStatisticsResponseTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
+    RdsRecommendationTypeDef,
+    StartRecommendationsRequestEntryTypeDef,
+    StartRecommendationsRequestRequestTypeDef,
     ReloadTablesMessageRequestTypeDef,
     ReplicationTaskAssessmentRunTypeDef,
     ReplicationTaskTypeDef,
     SchemaResponseTypeDef,
     ReplicationSubnetGroupTypeDef,
     DescribeFleetAdvisorCollectorsResponseTypeDef,
     CreateEndpointResponseTypeDef,
     DeleteEndpointResponseTypeDef,
     DescribeEndpointsResponseTypeDef,
     ModifyEndpointResponseTypeDef,
     DescribeFleetAdvisorDatabasesResponseTypeDef,
     ApplyPendingMaintenanceActionResponseTypeDef,
     DescribePendingMaintenanceActionsResponseTypeDef,
+    RecommendationDataTypeDef,
+    BatchStartRecommendationsRequestRequestTypeDef,
     CancelReplicationTaskAssessmentRunResponseTypeDef,
     DeleteReplicationTaskAssessmentRunResponseTypeDef,
     DescribeReplicationTaskAssessmentRunsResponseTypeDef,
     StartReplicationTaskAssessmentRunResponseTypeDef,
     CreateReplicationTaskResponseTypeDef,
     DeleteReplicationTaskResponseTypeDef,
     DescribeReplicationTasksResponseTypeDef,
@@ -669,62 +685,64 @@
     StartReplicationTaskResponseTypeDef,
     StopReplicationTaskResponseTypeDef,
     DescribeFleetAdvisorSchemasResponseTypeDef,
     CreateReplicationSubnetGroupResponseTypeDef,
     DescribeReplicationSubnetGroupsResponseTypeDef,
     ModifyReplicationSubnetGroupResponseTypeDef,
     ReplicationInstanceTypeDef,
+    RecommendationTypeDef,
     CreateReplicationInstanceResponseTypeDef,
     DeleteReplicationInstanceResponseTypeDef,
     DescribeReplicationInstancesResponseTypeDef,
     ModifyReplicationInstanceResponseTypeDef,
     RebootReplicationInstanceResponseTypeDef,
+    DescribeRecommendationsResponseTypeDef,
 )
 
 
 def get_structure() -> AccountQuotaTypeDef:
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/README.md` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-dms
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DatabaseMigrationService 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore dms type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-dms"></a>
 
 # types-aiobotocore-dms
 
 [![PyPI - types-aiobotocore-dms](https://img.shields.io/pypi/v/types-aiobotocore-dms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dms?color=blue)](https://pypistats.org/packages/types-aiobotocore-dms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DatabaseMigrationService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
+[aiobotocore.DatabaseMigrationService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
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
 [types-aiobotocore-dms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -386,14 +419,15 @@
     DescribeSchemasPaginatorName,
     DescribeTableStatisticsPaginatorName,
     DmsSslModeValueType,
     EncodingTypeValueType,
     EncryptionModeValueType,
     EndpointDeletedWaiterName,
     EndpointSettingTypeValueType,
+    KafkaSaslMechanismType,
     KafkaSecurityProtocolType,
     MessageFormatValueType,
     MigrationTypeValueType,
     NestingLevelValueType,
     ParquetVersionValueType,
     PluginNameValueType,
     RedisAuthTypeValueType,
@@ -409,14 +443,15 @@
     ReplicationTaskStoppedWaiterName,
     SafeguardPolicyType,
     SourceTypeType,
     SslSecurityProtocolValueType,
     StartReplicationTaskTypeValueType,
     TargetDbTypeType,
     TestConnectionSucceedsWaiterName,
+    TlogAccessModeType,
     VersionStatusType,
     DatabaseMigrationServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
     RegionName,
@@ -435,16 +470,16 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dms.type_defs import (
     AccountQuotaTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
-    ResponseMetadataTypeDef,
     AvailabilityZoneTypeDef,
+    BatchStartRecommendationsErrorEntryTypeDef,
     CancelReplicationTaskAssessmentRunMessageRequestTypeDef,
     CertificateTypeDef,
     CollectorHealthCheckTypeDef,
     InventoryDataTypeDef,
     CollectorShortInfoResponseTypeDef,
     ConnectionTypeDef,
     DmsTransferSettingsTypeDef,
@@ -463,89 +498,98 @@
     PostgreSQLSettingsTypeDef,
     RedisSettingsTypeDef,
     RedshiftSettingsTypeDef,
     S3SettingsTypeDef,
     SybaseSettingsTypeDef,
     EventSubscriptionTypeDef,
     CreateFleetAdvisorCollectorRequestRequestTypeDef,
+    CreateFleetAdvisorCollectorResponseTypeDef,
     DatabaseInstanceSoftwareDetailsResponseTypeDef,
     ServerShortInfoResponseTypeDef,
     DatabaseShortInfoResponseTypeDef,
     DeleteCertificateMessageRequestTypeDef,
     DeleteCollectorRequestRequestTypeDef,
     DeleteConnectionMessageRequestTypeDef,
     DeleteEndpointMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteFleetAdvisorDatabasesRequestRequestTypeDef,
+    DeleteFleetAdvisorDatabasesResponseTypeDef,
     DeleteReplicationInstanceMessageRequestTypeDef,
     DeleteReplicationSubnetGroupMessageRequestTypeDef,
     DeleteReplicationTaskAssessmentRunMessageRequestTypeDef,
     DeleteReplicationTaskMessageRequestTypeDef,
     DescribeApplicableIndividualAssessmentsMessageRequestTypeDef,
+    DescribeApplicableIndividualAssessmentsResponseTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     WaiterConfigTypeDef,
     DescribeEndpointSettingsMessageRequestTypeDef,
     EndpointSettingTypeDef,
     SupportedEndpointTypeTypeDef,
     EventCategoryGroupTypeDef,
     EventTypeDef,
     DescribeFleetAdvisorLsaAnalysisRequestRequestTypeDef,
     FleetAdvisorLsaAnalysisResponseTypeDef,
     FleetAdvisorSchemaObjectResponseTypeDef,
+    DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef,
     DescribeOrderableReplicationInstancesMessageRequestTypeDef,
     OrderableReplicationInstanceTypeDef,
+    LimitationTypeDef,
     DescribeRefreshSchemasStatusMessageRequestTypeDef,
     RefreshSchemasStatusTypeDef,
     DescribeReplicationInstanceTaskLogsMessageRequestTypeDef,
     ReplicationInstanceTaskLogTypeDef,
+    DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef,
     DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef,
     ReplicationTaskAssessmentResultTypeDef,
     ReplicationTaskIndividualAssessmentTypeDef,
+    DescribeSchemasMessageDescribeSchemasPaginateTypeDef,
     DescribeSchemasMessageRequestTypeDef,
+    DescribeSchemasResponseTypeDef,
     TableStatisticsTypeDef,
+    EmptyResponseMetadataTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyReplicationInstanceMessageRequestTypeDef,
     ModifyReplicationSubnetGroupMessageRequestTypeDef,
     ModifyReplicationTaskMessageRequestTypeDef,
     MoveReplicationTaskMessageRequestTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
+    RdsConfigurationTypeDef,
+    RdsRequirementsTypeDef,
     RebootReplicationInstanceMessageRequestTypeDef,
+    RecommendationSettingsTypeDef,
     RefreshSchemasMessageRequestTypeDef,
     TableToReloadTypeDef,
+    ReloadTablesResponseTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
     ReplicationPendingModifiedValuesTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     ReplicationTaskAssessmentRunProgressTypeDef,
     ReplicationTaskStatsTypeDef,
+    ResponseMetadataTypeDef,
+    RunFleetAdvisorLsaAnalysisResponseTypeDef,
     SchemaShortInfoResponseTypeDef,
     StartReplicationTaskAssessmentMessageRequestTypeDef,
     StartReplicationTaskAssessmentRunMessageRequestTypeDef,
     StartReplicationTaskMessageRequestTypeDef,
     StopReplicationTaskMessageRequestTypeDef,
     TestConnectionMessageRequestTypeDef,
     UpdateSubscriptionsToEventBridgeMessageRequestTypeDef,
+    UpdateSubscriptionsToEventBridgeResponseTypeDef,
+    DescribeAccountAttributesResponseTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CreateEventSubscriptionMessageRequestTypeDef,
     CreateReplicationInstanceMessageRequestTypeDef,
     CreateReplicationSubnetGroupMessageRequestTypeDef,
     CreateReplicationTaskMessageRequestTypeDef,
     ImportCertificateMessageRequestTypeDef,
-    CreateFleetAdvisorCollectorResponseTypeDef,
-    DeleteFleetAdvisorDatabasesResponseTypeDef,
-    DescribeAccountAttributesResponseTypeDef,
-    DescribeApplicableIndividualAssessmentsResponseTypeDef,
-    DescribeSchemasResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    ReloadTablesResponseTypeDef,
-    RunFleetAdvisorLsaAnalysisResponseTypeDef,
-    UpdateSubscriptionsToEventBridgeResponseTypeDef,
     SubnetTypeDef,
+    BatchStartRecommendationsResponseTypeDef,
     DeleteCertificateResponseTypeDef,
     DescribeCertificatesResponseTypeDef,
     ImportCertificateResponseTypeDef,
     CollectorResponseTypeDef,
     DeleteConnectionResponseTypeDef,
     DescribeConnectionsResponseTypeDef,
     TestConnectionResponseTypeDef,
@@ -553,45 +597,44 @@
     EndpointTypeDef,
     ModifyEndpointMessageRequestTypeDef,
     CreateEventSubscriptionResponseTypeDef,
     DeleteEventSubscriptionResponseTypeDef,
     DescribeEventSubscriptionsResponseTypeDef,
     ModifyEventSubscriptionResponseTypeDef,
     DatabaseResponseTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
+    DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef,
     DescribeConnectionsMessageRequestTypeDef,
+    DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef,
     DescribeEndpointTypesMessageRequestTypeDef,
+    DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef,
     DescribeEndpointsMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
     DescribeFleetAdvisorCollectorsRequestRequestTypeDef,
     DescribeFleetAdvisorDatabasesRequestRequestTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryRequestRequestTypeDef,
     DescribeFleetAdvisorSchemasRequestRequestTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
+    DescribeRecommendationLimitationsRequestRequestTypeDef,
+    DescribeRecommendationsRequestRequestTypeDef,
+    DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef,
     DescribeReplicationInstancesMessageRequestTypeDef,
+    DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef,
     DescribeReplicationSubnetGroupsMessageRequestTypeDef,
     DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef,
     DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef,
-    DescribeReplicationTasksMessageRequestTypeDef,
-    DescribeTableStatisticsMessageRequestTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef,
-    DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef,
-    DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef,
-    DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef,
-    DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef,
-    DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef,
     DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef,
-    DescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+    DescribeReplicationTasksMessageRequestTypeDef,
     DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+    DescribeTableStatisticsMessageRequestTypeDef,
     DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef,
     DescribeEndpointsMessageEndpointDeletedWaitTypeDef,
     DescribeReplicationInstancesMessageReplicationInstanceAvailableWaitTypeDef,
     DescribeReplicationInstancesMessageReplicationInstanceDeletedWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskDeletedWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskReadyWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskRunningWaitTypeDef,
@@ -599,34 +642,40 @@
     DescribeEndpointSettingsResponseTypeDef,
     DescribeEndpointTypesResponseTypeDef,
     DescribeEventCategoriesResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeFleetAdvisorLsaAnalysisResponseTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef,
     DescribeOrderableReplicationInstancesResponseTypeDef,
+    DescribeRecommendationLimitationsResponseTypeDef,
     DescribeRefreshSchemasStatusResponseTypeDef,
     RefreshSchemasResponseTypeDef,
     DescribeReplicationInstanceTaskLogsResponseTypeDef,
     DescribeReplicationTaskAssessmentResultsResponseTypeDef,
     DescribeReplicationTaskIndividualAssessmentsResponseTypeDef,
     DescribeTableStatisticsResponseTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
+    RdsRecommendationTypeDef,
+    StartRecommendationsRequestEntryTypeDef,
+    StartRecommendationsRequestRequestTypeDef,
     ReloadTablesMessageRequestTypeDef,
     ReplicationTaskAssessmentRunTypeDef,
     ReplicationTaskTypeDef,
     SchemaResponseTypeDef,
     ReplicationSubnetGroupTypeDef,
     DescribeFleetAdvisorCollectorsResponseTypeDef,
     CreateEndpointResponseTypeDef,
     DeleteEndpointResponseTypeDef,
     DescribeEndpointsResponseTypeDef,
     ModifyEndpointResponseTypeDef,
     DescribeFleetAdvisorDatabasesResponseTypeDef,
     ApplyPendingMaintenanceActionResponseTypeDef,
     DescribePendingMaintenanceActionsResponseTypeDef,
+    RecommendationDataTypeDef,
+    BatchStartRecommendationsRequestRequestTypeDef,
     CancelReplicationTaskAssessmentRunResponseTypeDef,
     DeleteReplicationTaskAssessmentRunResponseTypeDef,
     DescribeReplicationTaskAssessmentRunsResponseTypeDef,
     StartReplicationTaskAssessmentRunResponseTypeDef,
     CreateReplicationTaskResponseTypeDef,
     DeleteReplicationTaskResponseTypeDef,
     DescribeReplicationTasksResponseTypeDef,
@@ -636,62 +685,64 @@
     StartReplicationTaskResponseTypeDef,
     StopReplicationTaskResponseTypeDef,
     DescribeFleetAdvisorSchemasResponseTypeDef,
     CreateReplicationSubnetGroupResponseTypeDef,
     DescribeReplicationSubnetGroupsResponseTypeDef,
     ModifyReplicationSubnetGroupResponseTypeDef,
     ReplicationInstanceTypeDef,
+    RecommendationTypeDef,
     CreateReplicationInstanceResponseTypeDef,
     DeleteReplicationInstanceResponseTypeDef,
     DescribeReplicationInstancesResponseTypeDef,
     ModifyReplicationInstanceResponseTypeDef,
     RebootReplicationInstanceResponseTypeDef,
+    DescribeRecommendationsResponseTypeDef,
 )
 
 
 def get_structure() -> AccountQuotaTypeDef:
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/setup.py` & `types-aiobotocore-dms-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-dms.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-dms",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_dms"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DatabaseMigrationService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DatabaseMigrationService 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/",
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/__init__.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/__init__.pyi` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/__main__.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DatabaseMigrationService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DatabaseMigrationService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService\nOther"
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/client.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -42,14 +42,15 @@
     DescribeReplicationTaskAssessmentResultsPaginator,
     DescribeReplicationTasksPaginator,
     DescribeSchemasPaginator,
     DescribeTableStatisticsPaginator,
 )
 from .type_defs import (
     ApplyPendingMaintenanceActionResponseTypeDef,
+    BatchStartRecommendationsResponseTypeDef,
     CancelReplicationTaskAssessmentRunResponseTypeDef,
     CreateEndpointResponseTypeDef,
     CreateEventSubscriptionResponseTypeDef,
     CreateFleetAdvisorCollectorResponseTypeDef,
     CreateReplicationInstanceResponseTypeDef,
     CreateReplicationSubnetGroupResponseTypeDef,
     CreateReplicationTaskResponseTypeDef,
@@ -74,14 +75,16 @@
     DescribeFleetAdvisorCollectorsResponseTypeDef,
     DescribeFleetAdvisorDatabasesResponseTypeDef,
     DescribeFleetAdvisorLsaAnalysisResponseTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef,
     DescribeFleetAdvisorSchemasResponseTypeDef,
     DescribeOrderableReplicationInstancesResponseTypeDef,
     DescribePendingMaintenanceActionsResponseTypeDef,
+    DescribeRecommendationLimitationsResponseTypeDef,
+    DescribeRecommendationsResponseTypeDef,
     DescribeRefreshSchemasStatusResponseTypeDef,
     DescribeReplicationInstancesResponseTypeDef,
     DescribeReplicationInstanceTaskLogsResponseTypeDef,
     DescribeReplicationSubnetGroupsResponseTypeDef,
     DescribeReplicationTaskAssessmentResultsResponseTypeDef,
     DescribeReplicationTaskAssessmentRunsResponseTypeDef,
     DescribeReplicationTaskIndividualAssessmentsResponseTypeDef,
@@ -109,20 +112,22 @@
     MongoDbSettingsTypeDef,
     MoveReplicationTaskResponseTypeDef,
     MySQLSettingsTypeDef,
     NeptuneSettingsTypeDef,
     OracleSettingsTypeDef,
     PostgreSQLSettingsTypeDef,
     RebootReplicationInstanceResponseTypeDef,
+    RecommendationSettingsTypeDef,
     RedisSettingsTypeDef,
     RedshiftSettingsTypeDef,
     RefreshSchemasResponseTypeDef,
     ReloadTablesResponseTypeDef,
     RunFleetAdvisorLsaAnalysisResponseTypeDef,
     S3SettingsTypeDef,
+    StartRecommendationsRequestEntryTypeDef,
     StartReplicationTaskAssessmentResponseTypeDef,
     StartReplicationTaskAssessmentRunResponseTypeDef,
     StartReplicationTaskResponseTypeDef,
     StopReplicationTaskResponseTypeDef,
     SybaseSettingsTypeDef,
     TableToReloadTypeDef,
     TagTypeDef,
@@ -204,15 +209,15 @@
         """
 
     async def add_tags_to_resource(
         self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]
     ) -> Dict[str, Any]:
         """
         Adds metadata tags to an DMS resource, including replication instance, endpoint,
-        security group, and migration task.
+        subnet group, and migration task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.add_tags_to_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#add_tags_to_resource)
         """
 
     async def apply_pending_maintenance_action(
         self, *, ReplicationInstanceArn: str, ApplyAction: str, OptInType: str
@@ -221,14 +226,25 @@
         Applies a pending maintenance action to a resource (for example, to a
         replication instance).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.apply_pending_maintenance_action)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#apply_pending_maintenance_action)
         """
 
+    async def batch_start_recommendations(
+        self, *, Data: Sequence[StartRecommendationsRequestEntryTypeDef] = ...
+    ) -> BatchStartRecommendationsResponseTypeDef:
+        """
+        Starts the analysis of up to 20 source databases to recommend target engines for
+        each source database.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.batch_start_recommendations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#batch_start_recommendations)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#can_paginate)
         """
@@ -691,14 +707,36 @@
         For internal use only See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/dms-2016-01-01/DescribePendingMaintenanceActions).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_pending_maintenance_actions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#describe_pending_maintenance_actions)
         """
 
+    async def describe_recommendation_limitations(
+        self, *, Filters: Sequence[FilterTypeDef] = ..., MaxRecords: int = ..., NextToken: str = ...
+    ) -> DescribeRecommendationLimitationsResponseTypeDef:
+        """
+        Returns a paginated list of limitations for recommendations of target Amazon Web
+        Services engines.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_recommendation_limitations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#describe_recommendation_limitations)
+        """
+
+    async def describe_recommendations(
+        self, *, Filters: Sequence[FilterTypeDef] = ..., MaxRecords: int = ..., NextToken: str = ...
+    ) -> DescribeRecommendationsResponseTypeDef:
+        """
+        Returns a paginated list of target engine recommendations for your source
+        databases.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_recommendations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#describe_recommendations)
+        """
+
     async def describe_refresh_schemas_status(
         self, *, EndpointArn: str
     ) -> DescribeRefreshSchemasStatusResponseTypeDef:
         """
         Returns the status of the RefreshSchemas operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_refresh_schemas_status)
@@ -840,15 +878,15 @@
         """
 
     async def list_tags_for_resource(
         self, *, ResourceArn: str = ..., ResourceArnList: Sequence[str] = ...
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all metadata tags attached to an DMS resource, including replication
-        instance, endpoint, security group, and migration task.
+        instance, endpoint, subnet group, and migration task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#list_tags_for_resource)
         """
 
     async def modify_endpoint(
         self,
@@ -1017,29 +1055,40 @@
         """
 
     async def remove_tags_from_resource(
         self, *, ResourceArn: str, TagKeys: Sequence[str]
     ) -> Dict[str, Any]:
         """
         Removes metadata tags from an DMS resource, including replication instance,
-        endpoint, security group, and migration task.
+        endpoint, subnet group, and migration task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.remove_tags_from_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#remove_tags_from_resource)
         """
 
     async def run_fleet_advisor_lsa_analysis(self) -> RunFleetAdvisorLsaAnalysisResponseTypeDef:
         """
         Runs large-scale assessment (LSA) analysis on every Fleet Advisor collector in
         your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.run_fleet_advisor_lsa_analysis)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#run_fleet_advisor_lsa_analysis)
         """
 
+    async def start_recommendations(
+        self, *, DatabaseId: str, Settings: RecommendationSettingsTypeDef
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Starts the analysis of your source database to provide recommendations of target
+        engines.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.start_recommendations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#start_recommendations)
+        """
+
     async def start_replication_task(
         self,
         *,
         ReplicationTaskArn: str,
         StartReplicationTaskType: StartReplicationTaskTypeValueType,
         CdcStartTime: Union[datetime, str] = ...,
         CdcStartPosition: str = ...,
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/client.pyi` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -42,14 +42,15 @@
     DescribeReplicationTaskAssessmentResultsPaginator,
     DescribeReplicationTasksPaginator,
     DescribeSchemasPaginator,
     DescribeTableStatisticsPaginator,
 )
 from .type_defs import (
     ApplyPendingMaintenanceActionResponseTypeDef,
+    BatchStartRecommendationsResponseTypeDef,
     CancelReplicationTaskAssessmentRunResponseTypeDef,
     CreateEndpointResponseTypeDef,
     CreateEventSubscriptionResponseTypeDef,
     CreateFleetAdvisorCollectorResponseTypeDef,
     CreateReplicationInstanceResponseTypeDef,
     CreateReplicationSubnetGroupResponseTypeDef,
     CreateReplicationTaskResponseTypeDef,
@@ -74,14 +75,16 @@
     DescribeFleetAdvisorCollectorsResponseTypeDef,
     DescribeFleetAdvisorDatabasesResponseTypeDef,
     DescribeFleetAdvisorLsaAnalysisResponseTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef,
     DescribeFleetAdvisorSchemasResponseTypeDef,
     DescribeOrderableReplicationInstancesResponseTypeDef,
     DescribePendingMaintenanceActionsResponseTypeDef,
+    DescribeRecommendationLimitationsResponseTypeDef,
+    DescribeRecommendationsResponseTypeDef,
     DescribeRefreshSchemasStatusResponseTypeDef,
     DescribeReplicationInstancesResponseTypeDef,
     DescribeReplicationInstanceTaskLogsResponseTypeDef,
     DescribeReplicationSubnetGroupsResponseTypeDef,
     DescribeReplicationTaskAssessmentResultsResponseTypeDef,
     DescribeReplicationTaskAssessmentRunsResponseTypeDef,
     DescribeReplicationTaskIndividualAssessmentsResponseTypeDef,
@@ -109,20 +112,22 @@
     MongoDbSettingsTypeDef,
     MoveReplicationTaskResponseTypeDef,
     MySQLSettingsTypeDef,
     NeptuneSettingsTypeDef,
     OracleSettingsTypeDef,
     PostgreSQLSettingsTypeDef,
     RebootReplicationInstanceResponseTypeDef,
+    RecommendationSettingsTypeDef,
     RedisSettingsTypeDef,
     RedshiftSettingsTypeDef,
     RefreshSchemasResponseTypeDef,
     ReloadTablesResponseTypeDef,
     RunFleetAdvisorLsaAnalysisResponseTypeDef,
     S3SettingsTypeDef,
+    StartRecommendationsRequestEntryTypeDef,
     StartReplicationTaskAssessmentResponseTypeDef,
     StartReplicationTaskAssessmentRunResponseTypeDef,
     StartReplicationTaskResponseTypeDef,
     StopReplicationTaskResponseTypeDef,
     SybaseSettingsTypeDef,
     TableToReloadTypeDef,
     TagTypeDef,
@@ -199,29 +204,39 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#exceptions)
         """
     async def add_tags_to_resource(
         self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]
     ) -> Dict[str, Any]:
         """
         Adds metadata tags to an DMS resource, including replication instance, endpoint,
-        security group, and migration task.
+        subnet group, and migration task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.add_tags_to_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#add_tags_to_resource)
         """
     async def apply_pending_maintenance_action(
         self, *, ReplicationInstanceArn: str, ApplyAction: str, OptInType: str
     ) -> ApplyPendingMaintenanceActionResponseTypeDef:
         """
         Applies a pending maintenance action to a resource (for example, to a
         replication instance).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.apply_pending_maintenance_action)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#apply_pending_maintenance_action)
         """
+    async def batch_start_recommendations(
+        self, *, Data: Sequence[StartRecommendationsRequestEntryTypeDef] = ...
+    ) -> BatchStartRecommendationsResponseTypeDef:
+        """
+        Starts the analysis of up to 20 source databases to recommend target engines for
+        each source database.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.batch_start_recommendations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#batch_start_recommendations)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#can_paginate)
         """
@@ -648,14 +663,34 @@
         """
         For internal use only See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/dms-2016-01-01/DescribePendingMaintenanceActions).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_pending_maintenance_actions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#describe_pending_maintenance_actions)
         """
+    async def describe_recommendation_limitations(
+        self, *, Filters: Sequence[FilterTypeDef] = ..., MaxRecords: int = ..., NextToken: str = ...
+    ) -> DescribeRecommendationLimitationsResponseTypeDef:
+        """
+        Returns a paginated list of limitations for recommendations of target Amazon Web
+        Services engines.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_recommendation_limitations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#describe_recommendation_limitations)
+        """
+    async def describe_recommendations(
+        self, *, Filters: Sequence[FilterTypeDef] = ..., MaxRecords: int = ..., NextToken: str = ...
+    ) -> DescribeRecommendationsResponseTypeDef:
+        """
+        Returns a paginated list of target engine recommendations for your source
+        databases.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_recommendations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#describe_recommendations)
+        """
     async def describe_refresh_schemas_status(
         self, *, EndpointArn: str
     ) -> DescribeRefreshSchemasStatusResponseTypeDef:
         """
         Returns the status of the RefreshSchemas operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.describe_refresh_schemas_status)
@@ -785,15 +820,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#import_certificate)
         """
     async def list_tags_for_resource(
         self, *, ResourceArn: str = ..., ResourceArnList: Sequence[str] = ...
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all metadata tags attached to an DMS resource, including replication
-        instance, endpoint, security group, and migration task.
+        instance, endpoint, subnet group, and migration task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#list_tags_for_resource)
         """
     async def modify_endpoint(
         self,
         *,
@@ -952,27 +987,37 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#reload_tables)
         """
     async def remove_tags_from_resource(
         self, *, ResourceArn: str, TagKeys: Sequence[str]
     ) -> Dict[str, Any]:
         """
         Removes metadata tags from an DMS resource, including replication instance,
-        endpoint, security group, and migration task.
+        endpoint, subnet group, and migration task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.remove_tags_from_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#remove_tags_from_resource)
         """
     async def run_fleet_advisor_lsa_analysis(self) -> RunFleetAdvisorLsaAnalysisResponseTypeDef:
         """
         Runs large-scale assessment (LSA) analysis on every Fleet Advisor collector in
         your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.run_fleet_advisor_lsa_analysis)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#run_fleet_advisor_lsa_analysis)
         """
+    async def start_recommendations(
+        self, *, DatabaseId: str, Settings: RecommendationSettingsTypeDef
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Starts the analysis of your source database to provide recommendations of target
+        engines.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Client.start_recommendations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/client/#start_recommendations)
+        """
     async def start_replication_task(
         self,
         *,
         ReplicationTaskArn: str,
         StartReplicationTaskType: StartReplicationTaskTypeValueType,
         CdcStartTime: Union[datetime, str] = ...,
         CdcStartPosition: str = ...,
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/literals.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -43,14 +43,15 @@
     "DescribeSchemasPaginatorName",
     "DescribeTableStatisticsPaginatorName",
     "DmsSslModeValueType",
     "EncodingTypeValueType",
     "EncryptionModeValueType",
     "EndpointDeletedWaiterName",
     "EndpointSettingTypeValueType",
+    "KafkaSaslMechanismType",
     "KafkaSecurityProtocolType",
     "MessageFormatValueType",
     "MigrationTypeValueType",
     "NestingLevelValueType",
     "ParquetVersionValueType",
     "PluginNameValueType",
     "RedisAuthTypeValueType",
@@ -66,14 +67,15 @@
     "ReplicationTaskStoppedWaiterName",
     "SafeguardPolicyType",
     "SourceTypeType",
     "SslSecurityProtocolValueType",
     "StartReplicationTaskTypeValueType",
     "TargetDbTypeType",
     "TestConnectionSucceedsWaiterName",
+    "TlogAccessModeType",
     "VersionStatusType",
     "DatabaseMigrationServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
@@ -116,23 +118,24 @@
 DescribeSchemasPaginatorName = Literal["describe_schemas"]
 DescribeTableStatisticsPaginatorName = Literal["describe_table_statistics"]
 DmsSslModeValueType = Literal["none", "require", "verify-ca", "verify-full"]
 EncodingTypeValueType = Literal["plain", "plain-dictionary", "rle-dictionary"]
 EncryptionModeValueType = Literal["sse-kms", "sse-s3"]
 EndpointDeletedWaiterName = Literal["endpoint_deleted"]
 EndpointSettingTypeValueType = Literal["boolean", "enum", "integer", "string"]
+KafkaSaslMechanismType = Literal["plain", "scram-sha-512"]
 KafkaSecurityProtocolType = Literal["plaintext", "sasl-ssl", "ssl-authentication", "ssl-encryption"]
 MessageFormatValueType = Literal["json", "json-unformatted"]
 MigrationTypeValueType = Literal["cdc", "full-load", "full-load-and-cdc"]
 NestingLevelValueType = Literal["none", "one"]
 ParquetVersionValueType = Literal["parquet-1-0", "parquet-2-0"]
 PluginNameValueType = Literal["no-preference", "pglogical", "test-decoding"]
 RedisAuthTypeValueType = Literal["auth-role", "auth-token", "none"]
 RefreshSchemasStatusTypeValueType = Literal["failed", "refreshing", "successful"]
-ReleaseStatusValuesType = Literal["beta"]
+ReleaseStatusValuesType = Literal["beta", "prod"]
 ReloadOptionValueType = Literal["data-reload", "validate-only"]
 ReplicationEndpointTypeValueType = Literal["source", "target"]
 ReplicationInstanceAvailableWaiterName = Literal["replication_instance_available"]
 ReplicationInstanceDeletedWaiterName = Literal["replication_instance_deleted"]
 ReplicationTaskDeletedWaiterName = Literal["replication_task_deleted"]
 ReplicationTaskReadyWaiterName = Literal["replication_task_ready"]
 ReplicationTaskRunningWaiterName = Literal["replication_task_running"]
@@ -145,14 +148,15 @@
 SourceTypeType = Literal["replication-instance"]
 SslSecurityProtocolValueType = Literal["plaintext", "ssl-encryption"]
 StartReplicationTaskTypeValueType = Literal[
     "reload-target", "resume-processing", "start-replication"
 ]
 TargetDbTypeType = Literal["multiple-databases", "specific-database"]
 TestConnectionSucceedsWaiterName = Literal["test_connection_succeeds"]
+TlogAccessModeType = Literal["BackupOnly", "PreferBackup", "PreferTlog", "TlogOnly"]
 VersionStatusType = Literal["OUTDATED", "UNSUPPORTED", "UP_TO_DATE"]
 DatabaseMigrationServiceServiceName = Literal["dms"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -209,14 +213,15 @@
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
@@ -295,14 +300,15 @@
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
@@ -313,14 +319,15 @@
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
@@ -356,14 +363,15 @@
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
@@ -382,16 +390,19 @@
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
@@ -475,15 +486,17 @@
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/literals.pyi` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -42,14 +42,15 @@
     "DescribeSchemasPaginatorName",
     "DescribeTableStatisticsPaginatorName",
     "DmsSslModeValueType",
     "EncodingTypeValueType",
     "EncryptionModeValueType",
     "EndpointDeletedWaiterName",
     "EndpointSettingTypeValueType",
+    "KafkaSaslMechanismType",
     "KafkaSecurityProtocolType",
     "MessageFormatValueType",
     "MigrationTypeValueType",
     "NestingLevelValueType",
     "ParquetVersionValueType",
     "PluginNameValueType",
     "RedisAuthTypeValueType",
@@ -65,14 +66,15 @@
     "ReplicationTaskStoppedWaiterName",
     "SafeguardPolicyType",
     "SourceTypeType",
     "SslSecurityProtocolValueType",
     "StartReplicationTaskTypeValueType",
     "TargetDbTypeType",
     "TestConnectionSucceedsWaiterName",
+    "TlogAccessModeType",
     "VersionStatusType",
     "DatabaseMigrationServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
@@ -114,23 +116,24 @@
 DescribeSchemasPaginatorName = Literal["describe_schemas"]
 DescribeTableStatisticsPaginatorName = Literal["describe_table_statistics"]
 DmsSslModeValueType = Literal["none", "require", "verify-ca", "verify-full"]
 EncodingTypeValueType = Literal["plain", "plain-dictionary", "rle-dictionary"]
 EncryptionModeValueType = Literal["sse-kms", "sse-s3"]
 EndpointDeletedWaiterName = Literal["endpoint_deleted"]
 EndpointSettingTypeValueType = Literal["boolean", "enum", "integer", "string"]
+KafkaSaslMechanismType = Literal["plain", "scram-sha-512"]
 KafkaSecurityProtocolType = Literal["plaintext", "sasl-ssl", "ssl-authentication", "ssl-encryption"]
 MessageFormatValueType = Literal["json", "json-unformatted"]
 MigrationTypeValueType = Literal["cdc", "full-load", "full-load-and-cdc"]
 NestingLevelValueType = Literal["none", "one"]
 ParquetVersionValueType = Literal["parquet-1-0", "parquet-2-0"]
 PluginNameValueType = Literal["no-preference", "pglogical", "test-decoding"]
 RedisAuthTypeValueType = Literal["auth-role", "auth-token", "none"]
 RefreshSchemasStatusTypeValueType = Literal["failed", "refreshing", "successful"]
-ReleaseStatusValuesType = Literal["beta"]
+ReleaseStatusValuesType = Literal["beta", "prod"]
 ReloadOptionValueType = Literal["data-reload", "validate-only"]
 ReplicationEndpointTypeValueType = Literal["source", "target"]
 ReplicationInstanceAvailableWaiterName = Literal["replication_instance_available"]
 ReplicationInstanceDeletedWaiterName = Literal["replication_instance_deleted"]
 ReplicationTaskDeletedWaiterName = Literal["replication_task_deleted"]
 ReplicationTaskReadyWaiterName = Literal["replication_task_ready"]
 ReplicationTaskRunningWaiterName = Literal["replication_task_running"]
@@ -143,14 +146,15 @@
 SourceTypeType = Literal["replication-instance"]
 SslSecurityProtocolValueType = Literal["plaintext", "ssl-encryption"]
 StartReplicationTaskTypeValueType = Literal[
     "reload-target", "resume-processing", "start-replication"
 ]
 TargetDbTypeType = Literal["multiple-databases", "specific-database"]
 TestConnectionSucceedsWaiterName = Literal["test_connection_succeeds"]
+TlogAccessModeType = Literal["BackupOnly", "PreferBackup", "PreferTlog", "TlogOnly"]
 VersionStatusType = Literal["OUTDATED", "UNSUPPORTED", "UP_TO_DATE"]
 DatabaseMigrationServiceServiceName = Literal["dms"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -207,14 +211,15 @@
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
@@ -293,14 +298,15 @@
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
@@ -311,14 +317,15 @@
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
@@ -354,14 +361,15 @@
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
@@ -380,16 +388,19 @@
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
@@ -473,15 +484,17 @@
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/paginator.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -42,15 +42,15 @@
         describe_replication_tasks_paginator: DescribeReplicationTasksPaginator = client.get_paginator("describe_replication_tasks")
         describe_schemas_paginator: DescribeSchemasPaginator = client.get_paginator("describe_schemas")
         describe_table_statistics_paginator: DescribeTableStatisticsPaginator = client.get_paginator("describe_table_statistics")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeCertificatesResponseTypeDef,
     DescribeConnectionsResponseTypeDef,
@@ -65,18 +65,14 @@
     DescribeReplicationTasksResponseTypeDef,
     DescribeSchemasResponseTypeDef,
     DescribeTableStatisticsResponseTypeDef,
     FilterTypeDef,
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
@@ -112,15 +108,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describecertificatespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describecertificatespaginator)
         """
 
 
@@ -130,15 +126,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeconnectionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConnectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeconnectionspaginator)
         """
 
 
@@ -148,15 +144,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointtypespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEndpointTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEndpointTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointtypespaginator)
         """
 
 
@@ -166,15 +162,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointspaginator)
         """
 
 
@@ -185,15 +181,15 @@
     """
 
     def paginate(
         self,
         *,
         SubscriptionName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeeventsubscriptionspaginator)
         """
 
 
@@ -209,30 +205,30 @@
         SourceIdentifier: str = ...,
         SourceType: Literal["replication-instance"] = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
         EventCategories: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeeventspaginator)
         """
 
 
 class DescribeOrderableReplicationInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeOrderableReplicationInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeorderablereplicationinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrderableReplicationInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeOrderableReplicationInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeorderablereplicationinstancespaginator)
         """
 
 
@@ -242,15 +238,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationinstancespaginator)
         """
 
 
@@ -260,30 +256,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationsubnetgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationSubnetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationsubnetgroupspaginator)
         """
 
 
 class DescribeReplicationTaskAssessmentResultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationTaskAssessmentResults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationtaskassessmentresultspaginator)
     """
 
     def paginate(
-        self, *, ReplicationTaskArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ReplicationTaskArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationTaskAssessmentResultsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationTaskAssessmentResults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationtaskassessmentresultspaginator)
         """
 
 
@@ -294,30 +290,30 @@
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
         WithoutSettings: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationtaskspaginator)
         """
 
 
 class DescribeSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeschemaspaginator)
     """
 
     def paginate(
-        self, *, EndpointArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EndpointArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeschemaspaginator)
         """
 
 
@@ -328,13 +324,13 @@
     """
 
     def paginate(
         self,
         *,
         ReplicationTaskArn: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTableStatisticsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeTableStatistics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describetablestatisticspaginator)
         """
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/paginator.pyi` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -42,15 +42,15 @@
         describe_replication_tasks_paginator: DescribeReplicationTasksPaginator = client.get_paginator("describe_replication_tasks")
         describe_schemas_paginator: DescribeSchemasPaginator = client.get_paginator("describe_schemas")
         describe_table_statistics_paginator: DescribeTableStatisticsPaginator = client.get_paginator("describe_table_statistics")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeCertificatesResponseTypeDef,
     DescribeConnectionsResponseTypeDef,
@@ -65,18 +65,14 @@
     DescribeReplicationTasksResponseTypeDef,
     DescribeSchemasResponseTypeDef,
     DescribeTableStatisticsResponseTypeDef,
     FilterTypeDef,
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
     "DescribeCertificatesPaginator",
@@ -108,15 +104,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describecertificatespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describecertificatespaginator)
         """
 
 class DescribeConnectionsPaginator(AioPaginator):
@@ -125,15 +121,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeconnectionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConnectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeconnectionspaginator)
         """
 
 class DescribeEndpointTypesPaginator(AioPaginator):
@@ -142,15 +138,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointtypespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEndpointTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEndpointTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointtypespaginator)
         """
 
 class DescribeEndpointsPaginator(AioPaginator):
@@ -159,15 +155,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeendpointspaginator)
         """
 
 class DescribeEventSubscriptionsPaginator(AioPaginator):
@@ -177,15 +173,15 @@
     """
 
     def paginate(
         self,
         *,
         SubscriptionName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeeventsubscriptionspaginator)
         """
 
 class DescribeEventsPaginator(AioPaginator):
@@ -200,29 +196,29 @@
         SourceIdentifier: str = ...,
         SourceType: Literal["replication-instance"] = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
         EventCategories: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeeventspaginator)
         """
 
 class DescribeOrderableReplicationInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeOrderableReplicationInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeorderablereplicationinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrderableReplicationInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeOrderableReplicationInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeorderablereplicationinstancespaginator)
         """
 
 class DescribeReplicationInstancesPaginator(AioPaginator):
@@ -231,15 +227,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationinstancespaginator)
         """
 
 class DescribeReplicationSubnetGroupsPaginator(AioPaginator):
@@ -248,29 +244,29 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationsubnetgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationSubnetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationsubnetgroupspaginator)
         """
 
 class DescribeReplicationTaskAssessmentResultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationTaskAssessmentResults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationtaskassessmentresultspaginator)
     """
 
     def paginate(
-        self, *, ReplicationTaskArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ReplicationTaskArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationTaskAssessmentResultsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationTaskAssessmentResults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationtaskassessmentresultspaginator)
         """
 
 class DescribeReplicationTasksPaginator(AioPaginator):
@@ -280,29 +276,29 @@
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
         WithoutSettings: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeReplicationTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describereplicationtaskspaginator)
         """
 
 class DescribeSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeschemaspaginator)
     """
 
     def paginate(
-        self, *, EndpointArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EndpointArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describeschemaspaginator)
         """
 
 class DescribeTableStatisticsPaginator(AioPaginator):
@@ -312,13 +308,13 @@
     """
 
     def paginate(
         self,
         *,
         ReplicationTaskArn: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTableStatisticsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService.Paginator.DescribeTableStatistics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/paginators/#describetablestatisticspaginator)
         """
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/type_defs.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/type_defs.py`

 * *Files 12% similar despite different names*

```diff
@@ -27,28 +27,31 @@
     DataFormatValueType,
     DatePartitionDelimiterValueType,
     DatePartitionSequenceValueType,
     DmsSslModeValueType,
     EncodingTypeValueType,
     EncryptionModeValueType,
     EndpointSettingTypeValueType,
+    KafkaSaslMechanismType,
     KafkaSecurityProtocolType,
     MessageFormatValueType,
     MigrationTypeValueType,
     NestingLevelValueType,
     ParquetVersionValueType,
     PluginNameValueType,
     RedisAuthTypeValueType,
     RefreshSchemasStatusTypeValueType,
+    ReleaseStatusValuesType,
     ReloadOptionValueType,
     ReplicationEndpointTypeValueType,
     SafeguardPolicyType,
     SslSecurityProtocolValueType,
     StartReplicationTaskTypeValueType,
     TargetDbTypeType,
+    TlogAccessModeType,
     VersionStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -58,16 +61,16 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountQuotaTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AvailabilityZoneTypeDef",
+    "BatchStartRecommendationsErrorEntryTypeDef",
     "CancelReplicationTaskAssessmentRunMessageRequestTypeDef",
     "CertificateTypeDef",
     "CollectorHealthCheckTypeDef",
     "InventoryDataTypeDef",
     "CollectorShortInfoResponseTypeDef",
     "ConnectionTypeDef",
     "DmsTransferSettingsTypeDef",
@@ -86,89 +89,98 @@
     "PostgreSQLSettingsTypeDef",
     "RedisSettingsTypeDef",
     "RedshiftSettingsTypeDef",
     "S3SettingsTypeDef",
     "SybaseSettingsTypeDef",
     "EventSubscriptionTypeDef",
     "CreateFleetAdvisorCollectorRequestRequestTypeDef",
+    "CreateFleetAdvisorCollectorResponseTypeDef",
     "DatabaseInstanceSoftwareDetailsResponseTypeDef",
     "ServerShortInfoResponseTypeDef",
     "DatabaseShortInfoResponseTypeDef",
     "DeleteCertificateMessageRequestTypeDef",
     "DeleteCollectorRequestRequestTypeDef",
     "DeleteConnectionMessageRequestTypeDef",
     "DeleteEndpointMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteFleetAdvisorDatabasesRequestRequestTypeDef",
+    "DeleteFleetAdvisorDatabasesResponseTypeDef",
     "DeleteReplicationInstanceMessageRequestTypeDef",
     "DeleteReplicationSubnetGroupMessageRequestTypeDef",
     "DeleteReplicationTaskAssessmentRunMessageRequestTypeDef",
     "DeleteReplicationTaskMessageRequestTypeDef",
     "DescribeApplicableIndividualAssessmentsMessageRequestTypeDef",
+    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "WaiterConfigTypeDef",
     "DescribeEndpointSettingsMessageRequestTypeDef",
     "EndpointSettingTypeDef",
     "SupportedEndpointTypeTypeDef",
     "EventCategoryGroupTypeDef",
     "EventTypeDef",
     "DescribeFleetAdvisorLsaAnalysisRequestRequestTypeDef",
     "FleetAdvisorLsaAnalysisResponseTypeDef",
     "FleetAdvisorSchemaObjectResponseTypeDef",
+    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
     "DescribeOrderableReplicationInstancesMessageRequestTypeDef",
     "OrderableReplicationInstanceTypeDef",
+    "LimitationTypeDef",
     "DescribeRefreshSchemasStatusMessageRequestTypeDef",
     "RefreshSchemasStatusTypeDef",
     "DescribeReplicationInstanceTaskLogsMessageRequestTypeDef",
     "ReplicationInstanceTaskLogTypeDef",
+    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
     "DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef",
     "ReplicationTaskAssessmentResultTypeDef",
     "ReplicationTaskIndividualAssessmentTypeDef",
+    "DescribeSchemasMessageDescribeSchemasPaginateTypeDef",
     "DescribeSchemasMessageRequestTypeDef",
+    "DescribeSchemasResponseTypeDef",
     "TableStatisticsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyReplicationInstanceMessageRequestTypeDef",
     "ModifyReplicationSubnetGroupMessageRequestTypeDef",
     "ModifyReplicationTaskMessageRequestTypeDef",
     "MoveReplicationTaskMessageRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
+    "RdsConfigurationTypeDef",
+    "RdsRequirementsTypeDef",
     "RebootReplicationInstanceMessageRequestTypeDef",
+    "RecommendationSettingsTypeDef",
     "RefreshSchemasMessageRequestTypeDef",
     "TableToReloadTypeDef",
+    "ReloadTablesResponseTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
     "ReplicationPendingModifiedValuesTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "ReplicationTaskAssessmentRunProgressTypeDef",
     "ReplicationTaskStatsTypeDef",
+    "ResponseMetadataTypeDef",
+    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
     "SchemaShortInfoResponseTypeDef",
     "StartReplicationTaskAssessmentMessageRequestTypeDef",
     "StartReplicationTaskAssessmentRunMessageRequestTypeDef",
     "StartReplicationTaskMessageRequestTypeDef",
     "StopReplicationTaskMessageRequestTypeDef",
     "TestConnectionMessageRequestTypeDef",
     "UpdateSubscriptionsToEventBridgeMessageRequestTypeDef",
+    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
+    "DescribeAccountAttributesResponseTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CreateEventSubscriptionMessageRequestTypeDef",
     "CreateReplicationInstanceMessageRequestTypeDef",
     "CreateReplicationSubnetGroupMessageRequestTypeDef",
     "CreateReplicationTaskMessageRequestTypeDef",
     "ImportCertificateMessageRequestTypeDef",
-    "CreateFleetAdvisorCollectorResponseTypeDef",
-    "DeleteFleetAdvisorDatabasesResponseTypeDef",
-    "DescribeAccountAttributesResponseTypeDef",
-    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
-    "DescribeSchemasResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "ReloadTablesResponseTypeDef",
-    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
-    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
     "SubnetTypeDef",
+    "BatchStartRecommendationsResponseTypeDef",
     "DeleteCertificateResponseTypeDef",
     "DescribeCertificatesResponseTypeDef",
     "ImportCertificateResponseTypeDef",
     "CollectorResponseTypeDef",
     "DeleteConnectionResponseTypeDef",
     "DescribeConnectionsResponseTypeDef",
     "TestConnectionResponseTypeDef",
@@ -176,45 +188,44 @@
     "EndpointTypeDef",
     "ModifyEndpointMessageRequestTypeDef",
     "CreateEventSubscriptionResponseTypeDef",
     "DeleteEventSubscriptionResponseTypeDef",
     "DescribeEventSubscriptionsResponseTypeDef",
     "ModifyEventSubscriptionResponseTypeDef",
     "DatabaseResponseTypeDef",
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
     "DescribeCertificatesMessageRequestTypeDef",
+    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
     "DescribeConnectionsMessageRequestTypeDef",
+    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
     "DescribeEndpointTypesMessageRequestTypeDef",
+    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
     "DescribeEndpointsMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
     "DescribeFleetAdvisorCollectorsRequestRequestTypeDef",
     "DescribeFleetAdvisorDatabasesRequestRequestTypeDef",
     "DescribeFleetAdvisorSchemaObjectSummaryRequestRequestTypeDef",
     "DescribeFleetAdvisorSchemasRequestRequestTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
+    "DescribeRecommendationLimitationsRequestRequestTypeDef",
+    "DescribeRecommendationsRequestRequestTypeDef",
+    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
     "DescribeReplicationInstancesMessageRequestTypeDef",
+    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
     "DescribeReplicationSubnetGroupsMessageRequestTypeDef",
     "DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef",
     "DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef",
-    "DescribeReplicationTasksMessageRequestTypeDef",
-    "DescribeTableStatisticsMessageRequestTypeDef",
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
-    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
-    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
-    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
-    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
-    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
     "DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef",
-    "DescribeSchemasMessageDescribeSchemasPaginateTypeDef",
+    "DescribeReplicationTasksMessageRequestTypeDef",
     "DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
+    "DescribeTableStatisticsMessageRequestTypeDef",
     "DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef",
     "DescribeEndpointsMessageEndpointDeletedWaitTypeDef",
     "DescribeReplicationInstancesMessageReplicationInstanceAvailableWaitTypeDef",
     "DescribeReplicationInstancesMessageReplicationInstanceDeletedWaitTypeDef",
     "DescribeReplicationTasksMessageReplicationTaskDeletedWaitTypeDef",
     "DescribeReplicationTasksMessageReplicationTaskReadyWaitTypeDef",
     "DescribeReplicationTasksMessageReplicationTaskRunningWaitTypeDef",
@@ -222,34 +233,40 @@
     "DescribeEndpointSettingsResponseTypeDef",
     "DescribeEndpointTypesResponseTypeDef",
     "DescribeEventCategoriesResponseTypeDef",
     "DescribeEventsResponseTypeDef",
     "DescribeFleetAdvisorLsaAnalysisResponseTypeDef",
     "DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef",
     "DescribeOrderableReplicationInstancesResponseTypeDef",
+    "DescribeRecommendationLimitationsResponseTypeDef",
     "DescribeRefreshSchemasStatusResponseTypeDef",
     "RefreshSchemasResponseTypeDef",
     "DescribeReplicationInstanceTaskLogsResponseTypeDef",
     "DescribeReplicationTaskAssessmentResultsResponseTypeDef",
     "DescribeReplicationTaskIndividualAssessmentsResponseTypeDef",
     "DescribeTableStatisticsResponseTypeDef",
     "ResourcePendingMaintenanceActionsTypeDef",
+    "RdsRecommendationTypeDef",
+    "StartRecommendationsRequestEntryTypeDef",
+    "StartRecommendationsRequestRequestTypeDef",
     "ReloadTablesMessageRequestTypeDef",
     "ReplicationTaskAssessmentRunTypeDef",
     "ReplicationTaskTypeDef",
     "SchemaResponseTypeDef",
     "ReplicationSubnetGroupTypeDef",
     "DescribeFleetAdvisorCollectorsResponseTypeDef",
     "CreateEndpointResponseTypeDef",
     "DeleteEndpointResponseTypeDef",
     "DescribeEndpointsResponseTypeDef",
     "ModifyEndpointResponseTypeDef",
     "DescribeFleetAdvisorDatabasesResponseTypeDef",
     "ApplyPendingMaintenanceActionResponseTypeDef",
     "DescribePendingMaintenanceActionsResponseTypeDef",
+    "RecommendationDataTypeDef",
+    "BatchStartRecommendationsRequestRequestTypeDef",
     "CancelReplicationTaskAssessmentRunResponseTypeDef",
     "DeleteReplicationTaskAssessmentRunResponseTypeDef",
     "DescribeReplicationTaskAssessmentRunsResponseTypeDef",
     "StartReplicationTaskAssessmentRunResponseTypeDef",
     "CreateReplicationTaskResponseTypeDef",
     "DeleteReplicationTaskResponseTypeDef",
     "DescribeReplicationTasksResponseTypeDef",
@@ -259,19 +276,21 @@
     "StartReplicationTaskResponseTypeDef",
     "StopReplicationTaskResponseTypeDef",
     "DescribeFleetAdvisorSchemasResponseTypeDef",
     "CreateReplicationSubnetGroupResponseTypeDef",
     "DescribeReplicationSubnetGroupsResponseTypeDef",
     "ModifyReplicationSubnetGroupResponseTypeDef",
     "ReplicationInstanceTypeDef",
+    "RecommendationTypeDef",
     "CreateReplicationInstanceResponseTypeDef",
     "DeleteReplicationInstanceResponseTypeDef",
     "DescribeReplicationInstancesResponseTypeDef",
     "ModifyReplicationInstanceResponseTypeDef",
     "RebootReplicationInstanceResponseTypeDef",
+    "DescribeRecommendationsResponseTypeDef",
 )
 
 AccountQuotaTypeDef = TypedDict(
     "AccountQuotaTypeDef",
     {
         "AccountQuotaName": str,
         "Used": int,
@@ -295,29 +314,28 @@
     {
         "ReplicationInstanceArn": str,
         "ApplyAction": str,
         "OptInType": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AvailabilityZoneTypeDef = TypedDict(
+    "AvailabilityZoneTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Name": str,
     },
+    total=False,
 )
 
-AvailabilityZoneTypeDef = TypedDict(
-    "AvailabilityZoneTypeDef",
+BatchStartRecommendationsErrorEntryTypeDef = TypedDict(
+    "BatchStartRecommendationsErrorEntryTypeDef",
     {
-        "Name": str,
+        "DatabaseId": str,
+        "Message": str,
+        "Code": str,
     },
     total=False,
 )
 
 CancelReplicationTaskAssessmentRunMessageRequestTypeDef = TypedDict(
     "CancelReplicationTaskAssessmentRunMessageRequestTypeDef",
     {
@@ -497,14 +515,15 @@
         "SslClientCertificateArn": str,
         "SslClientKeyArn": str,
         "SslClientKeyPassword": str,
         "SslCaCertificateArn": str,
         "SaslUsername": str,
         "SaslPassword": str,
         "NoHexPrefix": bool,
+        "SaslMechanism": KafkaSaslMechanismType,
     },
     total=False,
 )
 
 KinesisSettingsTypeDef = TypedDict(
     "KinesisSettingsTypeDef",
     {
@@ -536,14 +555,16 @@
         "ServerName": str,
         "Username": str,
         "UseBcpFullLoad": bool,
         "UseThirdPartyBackupDevice": bool,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
         "TrimSpaceInChar": bool,
+        "TlogAccessMode": TlogAccessModeType,
+        "ForceLobLookup": bool,
     },
     total=False,
 )
 
 MongoDbSettingsTypeDef = TypedDict(
     "MongoDbSettingsTypeDef",
     {
@@ -650,14 +671,15 @@
         "UseDirectPathFullLoad": bool,
         "UseLogminerReader": bool,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
         "SecretsManagerOracleAsmAccessRoleArn": str,
         "SecretsManagerOracleAsmSecretId": str,
         "TrimSpaceInChar": bool,
+        "ConvertTimestampWithZoneToUTC": bool,
     },
     total=False,
 )
 
 PostgreSQLSettingsTypeDef = TypedDict(
     "PostgreSQLSettingsTypeDef",
     {
@@ -676,14 +698,15 @@
         "ServerName": str,
         "Username": str,
         "SlotName": str,
         "PluginName": PluginNameValueType,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
         "TrimSpaceInChar": bool,
+        "MapBooleanAsBoolean": bool,
     },
     total=False,
 )
 
 _RequiredRedisSettingsTypeDef = TypedDict(
     "_RequiredRedisSettingsTypeDef",
     {
@@ -737,14 +760,15 @@
         "TimeFormat": str,
         "TrimBlanks": bool,
         "TruncateColumns": bool,
         "Username": str,
         "WriteBufferSize": int,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
+        "MapBooleanAsBoolean": bool,
     },
     total=False,
 )
 
 S3SettingsTypeDef = TypedDict(
     "S3SettingsTypeDef",
     {
@@ -784,14 +808,15 @@
         "CsvNullValue": str,
         "IgnoreHeaderRows": int,
         "MaxFileSize": int,
         "Rfc4180": bool,
         "DatePartitionTimezone": str,
         "AddTrailingPaddingCharacter": bool,
         "ExpectedBucketOwner": str,
+        "GlueCatalogGeneration": bool,
     },
     total=False,
 )
 
 SybaseSettingsTypeDef = TypedDict(
     "SybaseSettingsTypeDef",
     {
@@ -842,14 +867,26 @@
 class CreateFleetAdvisorCollectorRequestRequestTypeDef(
     _RequiredCreateFleetAdvisorCollectorRequestRequestTypeDef,
     _OptionalCreateFleetAdvisorCollectorRequestRequestTypeDef,
 ):
     pass
 
 
+CreateFleetAdvisorCollectorResponseTypeDef = TypedDict(
+    "CreateFleetAdvisorCollectorResponseTypeDef",
+    {
+        "CollectorReferencedId": str,
+        "CollectorName": str,
+        "Description": str,
+        "ServiceAccessRoleArn": str,
+        "S3BucketName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatabaseInstanceSoftwareDetailsResponseTypeDef = TypedDict(
     "DatabaseInstanceSoftwareDetailsResponseTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "EngineEdition": str,
         "ServicePack": str,
@@ -920,14 +957,22 @@
 DeleteFleetAdvisorDatabasesRequestRequestTypeDef = TypedDict(
     "DeleteFleetAdvisorDatabasesRequestRequestTypeDef",
     {
         "DatabaseIds": Sequence[str],
     },
 )
 
+DeleteFleetAdvisorDatabasesResponseTypeDef = TypedDict(
+    "DeleteFleetAdvisorDatabasesResponseTypeDef",
+    {
+        "DatabaseIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteReplicationInstanceMessageRequestTypeDef = TypedDict(
     "DeleteReplicationInstanceMessageRequestTypeDef",
     {
         "ReplicationInstanceArn": str,
     },
 )
 
@@ -962,30 +1007,29 @@
         "MigrationType": MigrationTypeValueType,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-FilterTypeDef = TypedDict(
-    "FilterTypeDef",
+DescribeApplicableIndividualAssessmentsResponseTypeDef = TypedDict(
+    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
     {
-        "Name": str,
-        "Values": Sequence[str],
+        "IndividualAssessmentNames": List[str],
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+FilterTypeDef = TypedDict(
+    "FilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Name": str,
+        "Values": Sequence[str],
     },
-    total=False,
 )
 
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
@@ -1091,14 +1135,22 @@
         "NumberOfObjects": int,
         "CodeLineCount": int,
         "CodeSize": int,
     },
     total=False,
 )
 
+DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef = TypedDict(
+    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrderableReplicationInstancesMessageRequestTypeDef = TypedDict(
     "DescribeOrderableReplicationInstancesMessageRequestTypeDef",
     {
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
@@ -1111,15 +1163,28 @@
         "ReplicationInstanceClass": str,
         "StorageType": str,
         "MinAllocatedStorage": int,
         "MaxAllocatedStorage": int,
         "DefaultAllocatedStorage": int,
         "IncludedAllocatedStorage": int,
         "AvailabilityZones": List[str],
-        "ReleaseStatus": Literal["beta"],
+        "ReleaseStatus": ReleaseStatusValuesType,
+    },
+    total=False,
+)
+
+LimitationTypeDef = TypedDict(
+    "LimitationTypeDef",
+    {
+        "DatabaseId": str,
+        "EngineName": str,
+        "Name": str,
+        "Description": str,
+        "Impact": str,
+        "Type": str,
     },
     total=False,
 )
 
 DescribeRefreshSchemasStatusMessageRequestTypeDef = TypedDict(
     "DescribeRefreshSchemasStatusMessageRequestTypeDef",
     {
@@ -1168,14 +1233,23 @@
         "ReplicationTaskName": str,
         "ReplicationTaskArn": str,
         "ReplicationInstanceTaskLogSize": int,
     },
     total=False,
 )
 
+DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef = TypedDict(
+    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
+    {
+        "ReplicationTaskArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef = TypedDict(
     "DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
         "MaxRecords": int,
         "Marker": str,
     },
@@ -1204,14 +1278,36 @@
         "IndividualAssessmentName": str,
         "Status": str,
         "ReplicationTaskIndividualAssessmentStartDate": datetime,
     },
     total=False,
 )
 
+_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
+    {
+        "EndpointArn": str,
+    },
+)
+_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeSchemasMessageDescribeSchemasPaginateTypeDef(
+    _RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+    _OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeSchemasMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeSchemasMessageRequestTypeDef",
     {
         "EndpointArn": str,
     },
 )
 _OptionalDescribeSchemasMessageRequestTypeDef = TypedDict(
@@ -1226,14 +1322,23 @@
 
 class DescribeSchemasMessageRequestTypeDef(
     _RequiredDescribeSchemasMessageRequestTypeDef, _OptionalDescribeSchemasMessageRequestTypeDef
 ):
     pass
 
 
+DescribeSchemasResponseTypeDef = TypedDict(
+    "DescribeSchemasResponseTypeDef",
+    {
+        "Marker": str,
+        "Schemas": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TableStatisticsTypeDef = TypedDict(
     "TableStatisticsTypeDef",
     {
         "SchemaName": str,
         "TableName": str,
         "Inserts": int,
         "Deletes": int,
@@ -1256,14 +1361,21 @@
         "ValidationSuspendedRecords": int,
         "ValidationState": str,
         "ValidationStateDetails": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceMessageRequestTypeDef = TypedDict(
     "ListTagsForResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
         "ResourceArnList": Sequence[str],
     },
     total=False,
@@ -1382,27 +1494,65 @@
     "MoveReplicationTaskMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
         "TargetReplicationInstanceArn": str,
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
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
         "Action": str,
         "AutoAppliedAfterDate": datetime,
         "ForcedApplyDate": datetime,
         "OptInStatus": str,
         "CurrentApplyDate": datetime,
         "Description": str,
     },
     total=False,
 )
 
+RdsConfigurationTypeDef = TypedDict(
+    "RdsConfigurationTypeDef",
+    {
+        "EngineEdition": str,
+        "InstanceType": str,
+        "InstanceVcpu": float,
+        "InstanceMemory": float,
+        "StorageType": str,
+        "StorageSize": int,
+        "StorageIops": int,
+        "DeploymentOption": str,
+    },
+    total=False,
+)
+
+RdsRequirementsTypeDef = TypedDict(
+    "RdsRequirementsTypeDef",
+    {
+        "EngineEdition": str,
+        "InstanceVcpu": float,
+        "InstanceMemory": float,
+        "StorageSize": int,
+        "StorageIops": int,
+        "DeploymentOption": str,
+    },
+    total=False,
+)
+
 _RequiredRebootReplicationInstanceMessageRequestTypeDef = TypedDict(
     "_RequiredRebootReplicationInstanceMessageRequestTypeDef",
     {
         "ReplicationInstanceArn": str,
     },
 )
 _OptionalRebootReplicationInstanceMessageRequestTypeDef = TypedDict(
@@ -1418,14 +1568,22 @@
 class RebootReplicationInstanceMessageRequestTypeDef(
     _RequiredRebootReplicationInstanceMessageRequestTypeDef,
     _OptionalRebootReplicationInstanceMessageRequestTypeDef,
 ):
     pass
 
 
+RecommendationSettingsTypeDef = TypedDict(
+    "RecommendationSettingsTypeDef",
+    {
+        "InstanceSizingType": str,
+        "WorkloadType": str,
+    },
+)
+
 RefreshSchemasMessageRequestTypeDef = TypedDict(
     "RefreshSchemasMessageRequestTypeDef",
     {
         "EndpointArn": str,
         "ReplicationInstanceArn": str,
     },
 )
@@ -1434,14 +1592,22 @@
     "TableToReloadTypeDef",
     {
         "SchemaName": str,
         "TableName": str,
     },
 )
 
+ReloadTablesResponseTypeDef = TypedDict(
+    "ReloadTablesResponseTypeDef",
+    {
+        "ReplicationTaskArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsFromResourceMessageRequestTypeDef = TypedDict(
     "RemoveTagsFromResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1490,14 +1656,34 @@
         "StopDate": datetime,
         "FullLoadStartDate": datetime,
         "FullLoadFinishDate": datetime,
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
+RunFleetAdvisorLsaAnalysisResponseTypeDef = TypedDict(
+    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
+    {
+        "LsaAnalysisId": str,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SchemaShortInfoResponseTypeDef = TypedDict(
     "SchemaShortInfoResponseTypeDef",
     {
         "SchemaId": str,
         "SchemaName": str,
         "DatabaseId": str,
         "DatabaseName": str,
@@ -1586,14 +1772,31 @@
     "UpdateSubscriptionsToEventBridgeMessageRequestTypeDef",
     {
         "ForceMove": bool,
     },
     total=False,
 )
 
+UpdateSubscriptionsToEventBridgeResponseTypeDef = TypedDict(
+    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
+    {
+        "Result": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAccountAttributesResponseTypeDef = TypedDict(
+    "DescribeAccountAttributesResponseTypeDef",
+    {
+        "AccountQuotas": List[AccountQuotaTypeDef],
+        "UniqueAccountIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AddTagsToResourceMessageRequestTypeDef = TypedDict(
     "AddTagsToResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
@@ -1737,133 +1940,62 @@
 
 class ImportCertificateMessageRequestTypeDef(
     _RequiredImportCertificateMessageRequestTypeDef, _OptionalImportCertificateMessageRequestTypeDef
 ):
     pass
 
 
-CreateFleetAdvisorCollectorResponseTypeDef = TypedDict(
-    "CreateFleetAdvisorCollectorResponseTypeDef",
-    {
-        "CollectorReferencedId": str,
-        "CollectorName": str,
-        "Description": str,
-        "ServiceAccessRoleArn": str,
-        "S3BucketName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteFleetAdvisorDatabasesResponseTypeDef = TypedDict(
-    "DeleteFleetAdvisorDatabasesResponseTypeDef",
-    {
-        "DatabaseIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountAttributesResponseTypeDef = TypedDict(
-    "DescribeAccountAttributesResponseTypeDef",
-    {
-        "AccountQuotas": List[AccountQuotaTypeDef],
-        "UniqueAccountIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicableIndividualAssessmentsResponseTypeDef = TypedDict(
-    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
-    {
-        "IndividualAssessmentNames": List[str],
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeSchemasResponseTypeDef = TypedDict(
-    "DescribeSchemasResponseTypeDef",
-    {
-        "Marker": str,
-        "Schemas": List[str],
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReloadTablesResponseTypeDef = TypedDict(
-    "ReloadTablesResponseTypeDef",
-    {
-        "ReplicationTaskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RunFleetAdvisorLsaAnalysisResponseTypeDef = TypedDict(
-    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
-    {
-        "LsaAnalysisId": str,
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSubscriptionsToEventBridgeResponseTypeDef = TypedDict(
-    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
-    {
-        "Result": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubnetTypeDef = TypedDict(
     "SubnetTypeDef",
     {
         "SubnetIdentifier": str,
         "SubnetAvailabilityZone": AvailabilityZoneTypeDef,
         "SubnetStatus": str,
     },
     total=False,
 )
 
+BatchStartRecommendationsResponseTypeDef = TypedDict(
+    "BatchStartRecommendationsResponseTypeDef",
+    {
+        "ErrorEntries": List[BatchStartRecommendationsErrorEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCertificateResponseTypeDef = TypedDict(
     "DeleteCertificateResponseTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificatesResponseTypeDef = TypedDict(
     "DescribeCertificatesResponseTypeDef",
     {
         "Marker": str,
         "Certificates": List[CertificateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportCertificateResponseTypeDef = TypedDict(
     "ImportCertificateResponseTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CollectorResponseTypeDef = TypedDict(
     "CollectorResponseTypeDef",
     {
         "CollectorReferencedId": str,
@@ -1883,32 +2015,32 @@
     total=False,
 )
 
 DeleteConnectionResponseTypeDef = TypedDict(
     "DeleteConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectionsResponseTypeDef = TypedDict(
     "DescribeConnectionsResponseTypeDef",
     {
         "Marker": str,
         "Connections": List[ConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestConnectionResponseTypeDef = TypedDict(
     "TestConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEndpointMessageRequestTypeDef = TypedDict(
     "_RequiredCreateEndpointMessageRequestTypeDef",
     {
         "EndpointIdentifier": str,
@@ -2055,40 +2187,40 @@
     pass
 
 
 CreateEventSubscriptionResponseTypeDef = TypedDict(
     "CreateEventSubscriptionResponseTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventSubscriptionResponseTypeDef = TypedDict(
     "DeleteEventSubscriptionResponseTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventSubscriptionsResponseTypeDef = TypedDict(
     "DescribeEventSubscriptionsResponseTypeDef",
     {
         "Marker": str,
         "EventSubscriptionsList": List[EventSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyEventSubscriptionResponseTypeDef = TypedDict(
     "ModifyEventSubscriptionResponseTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatabaseResponseTypeDef = TypedDict(
     "DatabaseResponseTypeDef",
     {
         "DatabaseId": str,
@@ -2098,44 +2230,80 @@
         "Server": ServerShortInfoResponseTypeDef,
         "SoftwareDetails": DatabaseInstanceSoftwareDetailsResponseTypeDef,
         "Collectors": List[CollectorShortInfoResponseTypeDef],
     },
     total=False,
 )
 
+DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCertificatesMessageRequestTypeDef = TypedDict(
     "DescribeCertificatesMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef = TypedDict(
+    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConnectionsMessageRequestTypeDef = TypedDict(
     "DescribeConnectionsMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef = TypedDict(
+    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEndpointTypesMessageRequestTypeDef = TypedDict(
     "DescribeEndpointTypesMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef = TypedDict(
+    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEndpointsMessageRequestTypeDef = TypedDict(
     "DescribeEndpointsMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
@@ -2147,25 +2315,50 @@
     {
         "SourceType": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
+    {
+        "SubscriptionName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventSubscriptionsMessageRequestTypeDef = TypedDict(
     "DescribeEventSubscriptionsMessageRequestTypeDef",
     {
         "SubscriptionName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+    {
+        "SourceIdentifier": str,
+        "SourceType": Literal["replication-instance"],
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "EventCategories": Sequence[str],
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsMessageRequestTypeDef = TypedDict(
     "DescribeEventsMessageRequestTypeDef",
     {
         "SourceIdentifier": str,
         "SourceType": Literal["replication-instance"],
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -2225,236 +2418,156 @@
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
-DescribeReplicationInstancesMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationInstancesMessageRequestTypeDef",
+DescribeRecommendationLimitationsRequestRequestTypeDef = TypedDict(
+    "DescribeRecommendationLimitationsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
-        "Marker": str,
+        "NextToken": str,
     },
     total=False,
 )
 
-DescribeReplicationSubnetGroupsMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationSubnetGroupsMessageRequestTypeDef",
+DescribeRecommendationsRequestRequestTypeDef = TypedDict(
+    "DescribeRecommendationsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
-        "Marker": str,
+        "NextToken": str,
     },
     total=False,
 )
 
-DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef",
+DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef = TypedDict(
+    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef",
+DescribeReplicationInstancesMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationInstancesMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-DescribeReplicationTasksMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationTasksMessageRequestTypeDef",
+DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
-        "WithoutSettings": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeTableStatisticsMessageRequestTypeDef",
-    {
-        "ReplicationTaskArn": str,
-    },
-)
-_OptionalDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeTableStatisticsMessageRequestTypeDef",
+DescribeReplicationSubnetGroupsMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationSubnetGroupsMessageRequestTypeDef",
     {
+        "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
-
-
-class DescribeTableStatisticsMessageRequestTypeDef(
-    _RequiredDescribeTableStatisticsMessageRequestTypeDef,
-    _OptionalDescribeTableStatisticsMessageRequestTypeDef,
-):
-    pass
-
-
-DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef = TypedDict(
-    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef = TypedDict(
-    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef = TypedDict(
-    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
+DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef",
     {
-        "SubscriptionName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef",
     {
-        "SourceIdentifier": str,
-        "SourceType": Literal["replication-instance"],
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "EventCategories": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef = TypedDict(
-    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef = TypedDict(
-    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
+DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef = TypedDict(
+    "DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "WithoutSettings": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
+DescribeReplicationTasksMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationTasksMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
+        "WithoutSettings": bool,
     },
     total=False,
 )
 
-DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef = TypedDict(
-    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
+_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
     {
         "ReplicationTaskArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
-    total=False,
 )
-
-DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef = TypedDict(
-    "DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef",
+_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "WithoutSettings": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
-    {
-        "EndpointArn": str,
-    },
-)
-_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
-class DescribeSchemasMessageDescribeSchemasPaginateTypeDef(
-    _RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
-    _OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+class DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef(
+    _RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+    _OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
 ):
     pass
 
 
-_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
+_RequiredDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeTableStatisticsMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
     },
 )
-_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
+_OptionalDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeTableStatisticsMessageRequestTypeDef",
     {
+        "MaxRecords": int,
+        "Marker": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
 
-class DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef(
-    _RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
-    _OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+class DescribeTableStatisticsMessageRequestTypeDef(
+    _RequiredDescribeTableStatisticsMessageRequestTypeDef,
+    _OptionalDescribeTableStatisticsMessageRequestTypeDef,
 ):
     pass
 
 
 DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef = TypedDict(
     "DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef",
     {
@@ -2548,135 +2661,169 @@
 )
 
 DescribeEndpointSettingsResponseTypeDef = TypedDict(
     "DescribeEndpointSettingsResponseTypeDef",
     {
         "Marker": str,
         "EndpointSettings": List[EndpointSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointTypesResponseTypeDef = TypedDict(
     "DescribeEndpointTypesResponseTypeDef",
     {
         "Marker": str,
         "SupportedEndpointTypes": List[SupportedEndpointTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventCategoriesResponseTypeDef = TypedDict(
     "DescribeEventCategoriesResponseTypeDef",
     {
         "EventCategoryGroupList": List[EventCategoryGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "Marker": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorLsaAnalysisResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorLsaAnalysisResponseTypeDef",
     {
         "Analysis": List[FleetAdvisorLsaAnalysisResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef",
     {
         "FleetAdvisorSchemaObjects": List[FleetAdvisorSchemaObjectResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrderableReplicationInstancesResponseTypeDef = TypedDict(
     "DescribeOrderableReplicationInstancesResponseTypeDef",
     {
         "OrderableReplicationInstances": List[OrderableReplicationInstanceTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeRecommendationLimitationsResponseTypeDef = TypedDict(
+    "DescribeRecommendationLimitationsResponseTypeDef",
+    {
+        "NextToken": str,
+        "Limitations": List[LimitationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRefreshSchemasStatusResponseTypeDef = TypedDict(
     "DescribeRefreshSchemasStatusResponseTypeDef",
     {
         "RefreshSchemasStatus": RefreshSchemasStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RefreshSchemasResponseTypeDef = TypedDict(
     "RefreshSchemasResponseTypeDef",
     {
         "RefreshSchemasStatus": RefreshSchemasStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationInstanceTaskLogsResponseTypeDef = TypedDict(
     "DescribeReplicationInstanceTaskLogsResponseTypeDef",
     {
         "ReplicationInstanceArn": str,
         "ReplicationInstanceTaskLogs": List[ReplicationInstanceTaskLogTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTaskAssessmentResultsResponseTypeDef = TypedDict(
     "DescribeReplicationTaskAssessmentResultsResponseTypeDef",
     {
         "Marker": str,
         "BucketName": str,
         "ReplicationTaskAssessmentResults": List[ReplicationTaskAssessmentResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTaskIndividualAssessmentsResponseTypeDef = TypedDict(
     "DescribeReplicationTaskIndividualAssessmentsResponseTypeDef",
     {
         "Marker": str,
         "ReplicationTaskIndividualAssessments": List[ReplicationTaskIndividualAssessmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTableStatisticsResponseTypeDef = TypedDict(
     "DescribeTableStatisticsResponseTypeDef",
     {
         "ReplicationTaskArn": str,
         "TableStatistics": List[TableStatisticsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourcePendingMaintenanceActionsTypeDef = TypedDict(
     "ResourcePendingMaintenanceActionsTypeDef",
     {
         "ResourceIdentifier": str,
         "PendingMaintenanceActionDetails": List[PendingMaintenanceActionTypeDef],
     },
     total=False,
 )
 
+RdsRecommendationTypeDef = TypedDict(
+    "RdsRecommendationTypeDef",
+    {
+        "RequirementsToTarget": RdsRequirementsTypeDef,
+        "TargetConfiguration": RdsConfigurationTypeDef,
+    },
+    total=False,
+)
+
+StartRecommendationsRequestEntryTypeDef = TypedDict(
+    "StartRecommendationsRequestEntryTypeDef",
+    {
+        "DatabaseId": str,
+        "Settings": RecommendationSettingsTypeDef,
+    },
+)
+
+StartRecommendationsRequestRequestTypeDef = TypedDict(
+    "StartRecommendationsRequestRequestTypeDef",
+    {
+        "DatabaseId": str,
+        "Settings": RecommendationSettingsTypeDef,
+    },
+)
+
 _RequiredReloadTablesMessageRequestTypeDef = TypedDict(
     "_RequiredReloadTablesMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
         "TablesToReload": Sequence[TableToReloadTypeDef],
     },
 )
@@ -2770,206 +2917,222 @@
 )
 
 DescribeFleetAdvisorCollectorsResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorCollectorsResponseTypeDef",
     {
         "Collectors": List[CollectorResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEndpointResponseTypeDef = TypedDict(
     "CreateEndpointResponseTypeDef",
     {
         "Endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEndpointResponseTypeDef = TypedDict(
     "DeleteEndpointResponseTypeDef",
     {
         "Endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Marker": str,
         "Endpoints": List[EndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyEndpointResponseTypeDef = TypedDict(
     "ModifyEndpointResponseTypeDef",
     {
         "Endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorDatabasesResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorDatabasesResponseTypeDef",
     {
         "Databases": List[DatabaseResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplyPendingMaintenanceActionResponseTypeDef = TypedDict(
     "ApplyPendingMaintenanceActionResponseTypeDef",
     {
         "ResourcePendingMaintenanceActions": ResourcePendingMaintenanceActionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePendingMaintenanceActionsResponseTypeDef = TypedDict(
     "DescribePendingMaintenanceActionsResponseTypeDef",
     {
         "PendingMaintenanceActions": List[ResourcePendingMaintenanceActionsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+RecommendationDataTypeDef = TypedDict(
+    "RecommendationDataTypeDef",
+    {
+        "RdsEngine": RdsRecommendationTypeDef,
+    },
+    total=False,
+)
+
+BatchStartRecommendationsRequestRequestTypeDef = TypedDict(
+    "BatchStartRecommendationsRequestRequestTypeDef",
+    {
+        "Data": Sequence[StartRecommendationsRequestEntryTypeDef],
+    },
+    total=False,
+)
+
 CancelReplicationTaskAssessmentRunResponseTypeDef = TypedDict(
     "CancelReplicationTaskAssessmentRunResponseTypeDef",
     {
         "ReplicationTaskAssessmentRun": ReplicationTaskAssessmentRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationTaskAssessmentRunResponseTypeDef = TypedDict(
     "DeleteReplicationTaskAssessmentRunResponseTypeDef",
     {
         "ReplicationTaskAssessmentRun": ReplicationTaskAssessmentRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTaskAssessmentRunsResponseTypeDef = TypedDict(
     "DescribeReplicationTaskAssessmentRunsResponseTypeDef",
     {
         "Marker": str,
         "ReplicationTaskAssessmentRuns": List[ReplicationTaskAssessmentRunTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationTaskAssessmentRunResponseTypeDef = TypedDict(
     "StartReplicationTaskAssessmentRunResponseTypeDef",
     {
         "ReplicationTaskAssessmentRun": ReplicationTaskAssessmentRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReplicationTaskResponseTypeDef = TypedDict(
     "CreateReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationTaskResponseTypeDef = TypedDict(
     "DeleteReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTasksResponseTypeDef = TypedDict(
     "DescribeReplicationTasksResponseTypeDef",
     {
         "Marker": str,
         "ReplicationTasks": List[ReplicationTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationTaskResponseTypeDef = TypedDict(
     "ModifyReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MoveReplicationTaskResponseTypeDef = TypedDict(
     "MoveReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationTaskAssessmentResponseTypeDef = TypedDict(
     "StartReplicationTaskAssessmentResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationTaskResponseTypeDef = TypedDict(
     "StartReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopReplicationTaskResponseTypeDef = TypedDict(
     "StopReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorSchemasResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorSchemasResponseTypeDef",
     {
         "FleetAdvisorSchemas": List[SchemaResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReplicationSubnetGroupResponseTypeDef = TypedDict(
     "CreateReplicationSubnetGroupResponseTypeDef",
     {
         "ReplicationSubnetGroup": ReplicationSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationSubnetGroupsResponseTypeDef = TypedDict(
     "DescribeReplicationSubnetGroupsResponseTypeDef",
     {
         "Marker": str,
         "ReplicationSubnetGroups": List[ReplicationSubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationSubnetGroupResponseTypeDef = TypedDict(
     "ModifyReplicationSubnetGroupResponseTypeDef",
     {
         "ReplicationSubnetGroup": ReplicationSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationInstanceTypeDef = TypedDict(
     "ReplicationInstanceTypeDef",
     {
         "ReplicationInstanceIdentifier": str,
@@ -2997,47 +3160,70 @@
         "FreeUntil": datetime,
         "DnsNameServers": str,
         "NetworkType": str,
     },
     total=False,
 )
 
+RecommendationTypeDef = TypedDict(
+    "RecommendationTypeDef",
+    {
+        "DatabaseId": str,
+        "EngineName": str,
+        "CreatedDate": str,
+        "Status": str,
+        "Preferred": bool,
+        "Settings": RecommendationSettingsTypeDef,
+        "Data": RecommendationDataTypeDef,
+    },
+    total=False,
+)
+
 CreateReplicationInstanceResponseTypeDef = TypedDict(
     "CreateReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationInstanceResponseTypeDef = TypedDict(
     "DeleteReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationInstancesResponseTypeDef = TypedDict(
     "DescribeReplicationInstancesResponseTypeDef",
     {
         "Marker": str,
         "ReplicationInstances": List[ReplicationInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationInstanceResponseTypeDef = TypedDict(
     "ModifyReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootReplicationInstanceResponseTypeDef = TypedDict(
     "RebootReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeRecommendationsResponseTypeDef = TypedDict(
+    "DescribeRecommendationsResponseTypeDef",
+    {
+        "NextToken": str,
+        "Recommendations": List[RecommendationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/type_defs.pyi` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/type_defs.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -27,28 +27,31 @@
     DataFormatValueType,
     DatePartitionDelimiterValueType,
     DatePartitionSequenceValueType,
     DmsSslModeValueType,
     EncodingTypeValueType,
     EncryptionModeValueType,
     EndpointSettingTypeValueType,
+    KafkaSaslMechanismType,
     KafkaSecurityProtocolType,
     MessageFormatValueType,
     MigrationTypeValueType,
     NestingLevelValueType,
     ParquetVersionValueType,
     PluginNameValueType,
     RedisAuthTypeValueType,
     RefreshSchemasStatusTypeValueType,
+    ReleaseStatusValuesType,
     ReloadOptionValueType,
     ReplicationEndpointTypeValueType,
     SafeguardPolicyType,
     SslSecurityProtocolValueType,
     StartReplicationTaskTypeValueType,
     TargetDbTypeType,
+    TlogAccessModeType,
     VersionStatusType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -57,16 +60,16 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountQuotaTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AvailabilityZoneTypeDef",
+    "BatchStartRecommendationsErrorEntryTypeDef",
     "CancelReplicationTaskAssessmentRunMessageRequestTypeDef",
     "CertificateTypeDef",
     "CollectorHealthCheckTypeDef",
     "InventoryDataTypeDef",
     "CollectorShortInfoResponseTypeDef",
     "ConnectionTypeDef",
     "DmsTransferSettingsTypeDef",
@@ -85,89 +88,98 @@
     "PostgreSQLSettingsTypeDef",
     "RedisSettingsTypeDef",
     "RedshiftSettingsTypeDef",
     "S3SettingsTypeDef",
     "SybaseSettingsTypeDef",
     "EventSubscriptionTypeDef",
     "CreateFleetAdvisorCollectorRequestRequestTypeDef",
+    "CreateFleetAdvisorCollectorResponseTypeDef",
     "DatabaseInstanceSoftwareDetailsResponseTypeDef",
     "ServerShortInfoResponseTypeDef",
     "DatabaseShortInfoResponseTypeDef",
     "DeleteCertificateMessageRequestTypeDef",
     "DeleteCollectorRequestRequestTypeDef",
     "DeleteConnectionMessageRequestTypeDef",
     "DeleteEndpointMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteFleetAdvisorDatabasesRequestRequestTypeDef",
+    "DeleteFleetAdvisorDatabasesResponseTypeDef",
     "DeleteReplicationInstanceMessageRequestTypeDef",
     "DeleteReplicationSubnetGroupMessageRequestTypeDef",
     "DeleteReplicationTaskAssessmentRunMessageRequestTypeDef",
     "DeleteReplicationTaskMessageRequestTypeDef",
     "DescribeApplicableIndividualAssessmentsMessageRequestTypeDef",
+    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "WaiterConfigTypeDef",
     "DescribeEndpointSettingsMessageRequestTypeDef",
     "EndpointSettingTypeDef",
     "SupportedEndpointTypeTypeDef",
     "EventCategoryGroupTypeDef",
     "EventTypeDef",
     "DescribeFleetAdvisorLsaAnalysisRequestRequestTypeDef",
     "FleetAdvisorLsaAnalysisResponseTypeDef",
     "FleetAdvisorSchemaObjectResponseTypeDef",
+    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
     "DescribeOrderableReplicationInstancesMessageRequestTypeDef",
     "OrderableReplicationInstanceTypeDef",
+    "LimitationTypeDef",
     "DescribeRefreshSchemasStatusMessageRequestTypeDef",
     "RefreshSchemasStatusTypeDef",
     "DescribeReplicationInstanceTaskLogsMessageRequestTypeDef",
     "ReplicationInstanceTaskLogTypeDef",
+    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
     "DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef",
     "ReplicationTaskAssessmentResultTypeDef",
     "ReplicationTaskIndividualAssessmentTypeDef",
+    "DescribeSchemasMessageDescribeSchemasPaginateTypeDef",
     "DescribeSchemasMessageRequestTypeDef",
+    "DescribeSchemasResponseTypeDef",
     "TableStatisticsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyReplicationInstanceMessageRequestTypeDef",
     "ModifyReplicationSubnetGroupMessageRequestTypeDef",
     "ModifyReplicationTaskMessageRequestTypeDef",
     "MoveReplicationTaskMessageRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
+    "RdsConfigurationTypeDef",
+    "RdsRequirementsTypeDef",
     "RebootReplicationInstanceMessageRequestTypeDef",
+    "RecommendationSettingsTypeDef",
     "RefreshSchemasMessageRequestTypeDef",
     "TableToReloadTypeDef",
+    "ReloadTablesResponseTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
     "ReplicationPendingModifiedValuesTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "ReplicationTaskAssessmentRunProgressTypeDef",
     "ReplicationTaskStatsTypeDef",
+    "ResponseMetadataTypeDef",
+    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
     "SchemaShortInfoResponseTypeDef",
     "StartReplicationTaskAssessmentMessageRequestTypeDef",
     "StartReplicationTaskAssessmentRunMessageRequestTypeDef",
     "StartReplicationTaskMessageRequestTypeDef",
     "StopReplicationTaskMessageRequestTypeDef",
     "TestConnectionMessageRequestTypeDef",
     "UpdateSubscriptionsToEventBridgeMessageRequestTypeDef",
+    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
+    "DescribeAccountAttributesResponseTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CreateEventSubscriptionMessageRequestTypeDef",
     "CreateReplicationInstanceMessageRequestTypeDef",
     "CreateReplicationSubnetGroupMessageRequestTypeDef",
     "CreateReplicationTaskMessageRequestTypeDef",
     "ImportCertificateMessageRequestTypeDef",
-    "CreateFleetAdvisorCollectorResponseTypeDef",
-    "DeleteFleetAdvisorDatabasesResponseTypeDef",
-    "DescribeAccountAttributesResponseTypeDef",
-    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
-    "DescribeSchemasResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "ReloadTablesResponseTypeDef",
-    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
-    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
     "SubnetTypeDef",
+    "BatchStartRecommendationsResponseTypeDef",
     "DeleteCertificateResponseTypeDef",
     "DescribeCertificatesResponseTypeDef",
     "ImportCertificateResponseTypeDef",
     "CollectorResponseTypeDef",
     "DeleteConnectionResponseTypeDef",
     "DescribeConnectionsResponseTypeDef",
     "TestConnectionResponseTypeDef",
@@ -175,45 +187,44 @@
     "EndpointTypeDef",
     "ModifyEndpointMessageRequestTypeDef",
     "CreateEventSubscriptionResponseTypeDef",
     "DeleteEventSubscriptionResponseTypeDef",
     "DescribeEventSubscriptionsResponseTypeDef",
     "ModifyEventSubscriptionResponseTypeDef",
     "DatabaseResponseTypeDef",
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
     "DescribeCertificatesMessageRequestTypeDef",
+    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
     "DescribeConnectionsMessageRequestTypeDef",
+    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
     "DescribeEndpointTypesMessageRequestTypeDef",
+    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
     "DescribeEndpointsMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
     "DescribeFleetAdvisorCollectorsRequestRequestTypeDef",
     "DescribeFleetAdvisorDatabasesRequestRequestTypeDef",
     "DescribeFleetAdvisorSchemaObjectSummaryRequestRequestTypeDef",
     "DescribeFleetAdvisorSchemasRequestRequestTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
+    "DescribeRecommendationLimitationsRequestRequestTypeDef",
+    "DescribeRecommendationsRequestRequestTypeDef",
+    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
     "DescribeReplicationInstancesMessageRequestTypeDef",
+    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
     "DescribeReplicationSubnetGroupsMessageRequestTypeDef",
     "DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef",
     "DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef",
-    "DescribeReplicationTasksMessageRequestTypeDef",
-    "DescribeTableStatisticsMessageRequestTypeDef",
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
-    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
-    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
-    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
-    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
-    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
     "DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef",
-    "DescribeSchemasMessageDescribeSchemasPaginateTypeDef",
+    "DescribeReplicationTasksMessageRequestTypeDef",
     "DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
+    "DescribeTableStatisticsMessageRequestTypeDef",
     "DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef",
     "DescribeEndpointsMessageEndpointDeletedWaitTypeDef",
     "DescribeReplicationInstancesMessageReplicationInstanceAvailableWaitTypeDef",
     "DescribeReplicationInstancesMessageReplicationInstanceDeletedWaitTypeDef",
     "DescribeReplicationTasksMessageReplicationTaskDeletedWaitTypeDef",
     "DescribeReplicationTasksMessageReplicationTaskReadyWaitTypeDef",
     "DescribeReplicationTasksMessageReplicationTaskRunningWaitTypeDef",
@@ -221,34 +232,40 @@
     "DescribeEndpointSettingsResponseTypeDef",
     "DescribeEndpointTypesResponseTypeDef",
     "DescribeEventCategoriesResponseTypeDef",
     "DescribeEventsResponseTypeDef",
     "DescribeFleetAdvisorLsaAnalysisResponseTypeDef",
     "DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef",
     "DescribeOrderableReplicationInstancesResponseTypeDef",
+    "DescribeRecommendationLimitationsResponseTypeDef",
     "DescribeRefreshSchemasStatusResponseTypeDef",
     "RefreshSchemasResponseTypeDef",
     "DescribeReplicationInstanceTaskLogsResponseTypeDef",
     "DescribeReplicationTaskAssessmentResultsResponseTypeDef",
     "DescribeReplicationTaskIndividualAssessmentsResponseTypeDef",
     "DescribeTableStatisticsResponseTypeDef",
     "ResourcePendingMaintenanceActionsTypeDef",
+    "RdsRecommendationTypeDef",
+    "StartRecommendationsRequestEntryTypeDef",
+    "StartRecommendationsRequestRequestTypeDef",
     "ReloadTablesMessageRequestTypeDef",
     "ReplicationTaskAssessmentRunTypeDef",
     "ReplicationTaskTypeDef",
     "SchemaResponseTypeDef",
     "ReplicationSubnetGroupTypeDef",
     "DescribeFleetAdvisorCollectorsResponseTypeDef",
     "CreateEndpointResponseTypeDef",
     "DeleteEndpointResponseTypeDef",
     "DescribeEndpointsResponseTypeDef",
     "ModifyEndpointResponseTypeDef",
     "DescribeFleetAdvisorDatabasesResponseTypeDef",
     "ApplyPendingMaintenanceActionResponseTypeDef",
     "DescribePendingMaintenanceActionsResponseTypeDef",
+    "RecommendationDataTypeDef",
+    "BatchStartRecommendationsRequestRequestTypeDef",
     "CancelReplicationTaskAssessmentRunResponseTypeDef",
     "DeleteReplicationTaskAssessmentRunResponseTypeDef",
     "DescribeReplicationTaskAssessmentRunsResponseTypeDef",
     "StartReplicationTaskAssessmentRunResponseTypeDef",
     "CreateReplicationTaskResponseTypeDef",
     "DeleteReplicationTaskResponseTypeDef",
     "DescribeReplicationTasksResponseTypeDef",
@@ -258,19 +275,21 @@
     "StartReplicationTaskResponseTypeDef",
     "StopReplicationTaskResponseTypeDef",
     "DescribeFleetAdvisorSchemasResponseTypeDef",
     "CreateReplicationSubnetGroupResponseTypeDef",
     "DescribeReplicationSubnetGroupsResponseTypeDef",
     "ModifyReplicationSubnetGroupResponseTypeDef",
     "ReplicationInstanceTypeDef",
+    "RecommendationTypeDef",
     "CreateReplicationInstanceResponseTypeDef",
     "DeleteReplicationInstanceResponseTypeDef",
     "DescribeReplicationInstancesResponseTypeDef",
     "ModifyReplicationInstanceResponseTypeDef",
     "RebootReplicationInstanceResponseTypeDef",
+    "DescribeRecommendationsResponseTypeDef",
 )
 
 AccountQuotaTypeDef = TypedDict(
     "AccountQuotaTypeDef",
     {
         "AccountQuotaName": str,
         "Used": int,
@@ -294,29 +313,28 @@
     {
         "ReplicationInstanceArn": str,
         "ApplyAction": str,
         "OptInType": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AvailabilityZoneTypeDef = TypedDict(
+    "AvailabilityZoneTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Name": str,
     },
+    total=False,
 )
 
-AvailabilityZoneTypeDef = TypedDict(
-    "AvailabilityZoneTypeDef",
+BatchStartRecommendationsErrorEntryTypeDef = TypedDict(
+    "BatchStartRecommendationsErrorEntryTypeDef",
     {
-        "Name": str,
+        "DatabaseId": str,
+        "Message": str,
+        "Code": str,
     },
     total=False,
 )
 
 CancelReplicationTaskAssessmentRunMessageRequestTypeDef = TypedDict(
     "CancelReplicationTaskAssessmentRunMessageRequestTypeDef",
     {
@@ -494,14 +512,15 @@
         "SslClientCertificateArn": str,
         "SslClientKeyArn": str,
         "SslClientKeyPassword": str,
         "SslCaCertificateArn": str,
         "SaslUsername": str,
         "SaslPassword": str,
         "NoHexPrefix": bool,
+        "SaslMechanism": KafkaSaslMechanismType,
     },
     total=False,
 )
 
 KinesisSettingsTypeDef = TypedDict(
     "KinesisSettingsTypeDef",
     {
@@ -533,14 +552,16 @@
         "ServerName": str,
         "Username": str,
         "UseBcpFullLoad": bool,
         "UseThirdPartyBackupDevice": bool,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
         "TrimSpaceInChar": bool,
+        "TlogAccessMode": TlogAccessModeType,
+        "ForceLobLookup": bool,
     },
     total=False,
 )
 
 MongoDbSettingsTypeDef = TypedDict(
     "MongoDbSettingsTypeDef",
     {
@@ -645,14 +666,15 @@
         "UseDirectPathFullLoad": bool,
         "UseLogminerReader": bool,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
         "SecretsManagerOracleAsmAccessRoleArn": str,
         "SecretsManagerOracleAsmSecretId": str,
         "TrimSpaceInChar": bool,
+        "ConvertTimestampWithZoneToUTC": bool,
     },
     total=False,
 )
 
 PostgreSQLSettingsTypeDef = TypedDict(
     "PostgreSQLSettingsTypeDef",
     {
@@ -671,14 +693,15 @@
         "ServerName": str,
         "Username": str,
         "SlotName": str,
         "PluginName": PluginNameValueType,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
         "TrimSpaceInChar": bool,
+        "MapBooleanAsBoolean": bool,
     },
     total=False,
 )
 
 _RequiredRedisSettingsTypeDef = TypedDict(
     "_RequiredRedisSettingsTypeDef",
     {
@@ -730,14 +753,15 @@
         "TimeFormat": str,
         "TrimBlanks": bool,
         "TruncateColumns": bool,
         "Username": str,
         "WriteBufferSize": int,
         "SecretsManagerAccessRoleArn": str,
         "SecretsManagerSecretId": str,
+        "MapBooleanAsBoolean": bool,
     },
     total=False,
 )
 
 S3SettingsTypeDef = TypedDict(
     "S3SettingsTypeDef",
     {
@@ -777,14 +801,15 @@
         "CsvNullValue": str,
         "IgnoreHeaderRows": int,
         "MaxFileSize": int,
         "Rfc4180": bool,
         "DatePartitionTimezone": str,
         "AddTrailingPaddingCharacter": bool,
         "ExpectedBucketOwner": str,
+        "GlueCatalogGeneration": bool,
     },
     total=False,
 )
 
 SybaseSettingsTypeDef = TypedDict(
     "SybaseSettingsTypeDef",
     {
@@ -833,14 +858,26 @@
 
 class CreateFleetAdvisorCollectorRequestRequestTypeDef(
     _RequiredCreateFleetAdvisorCollectorRequestRequestTypeDef,
     _OptionalCreateFleetAdvisorCollectorRequestRequestTypeDef,
 ):
     pass
 
+CreateFleetAdvisorCollectorResponseTypeDef = TypedDict(
+    "CreateFleetAdvisorCollectorResponseTypeDef",
+    {
+        "CollectorReferencedId": str,
+        "CollectorName": str,
+        "Description": str,
+        "ServiceAccessRoleArn": str,
+        "S3BucketName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatabaseInstanceSoftwareDetailsResponseTypeDef = TypedDict(
     "DatabaseInstanceSoftwareDetailsResponseTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "EngineEdition": str,
         "ServicePack": str,
@@ -911,14 +948,22 @@
 DeleteFleetAdvisorDatabasesRequestRequestTypeDef = TypedDict(
     "DeleteFleetAdvisorDatabasesRequestRequestTypeDef",
     {
         "DatabaseIds": Sequence[str],
     },
 )
 
+DeleteFleetAdvisorDatabasesResponseTypeDef = TypedDict(
+    "DeleteFleetAdvisorDatabasesResponseTypeDef",
+    {
+        "DatabaseIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteReplicationInstanceMessageRequestTypeDef = TypedDict(
     "DeleteReplicationInstanceMessageRequestTypeDef",
     {
         "ReplicationInstanceArn": str,
     },
 )
 
@@ -953,30 +998,29 @@
         "MigrationType": MigrationTypeValueType,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-FilterTypeDef = TypedDict(
-    "FilterTypeDef",
+DescribeApplicableIndividualAssessmentsResponseTypeDef = TypedDict(
+    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
     {
-        "Name": str,
-        "Values": Sequence[str],
+        "IndividualAssessmentNames": List[str],
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+FilterTypeDef = TypedDict(
+    "FilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Name": str,
+        "Values": Sequence[str],
     },
-    total=False,
 )
 
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
@@ -1080,14 +1124,22 @@
         "NumberOfObjects": int,
         "CodeLineCount": int,
         "CodeSize": int,
     },
     total=False,
 )
 
+DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef = TypedDict(
+    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrderableReplicationInstancesMessageRequestTypeDef = TypedDict(
     "DescribeOrderableReplicationInstancesMessageRequestTypeDef",
     {
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
@@ -1100,15 +1152,28 @@
         "ReplicationInstanceClass": str,
         "StorageType": str,
         "MinAllocatedStorage": int,
         "MaxAllocatedStorage": int,
         "DefaultAllocatedStorage": int,
         "IncludedAllocatedStorage": int,
         "AvailabilityZones": List[str],
-        "ReleaseStatus": Literal["beta"],
+        "ReleaseStatus": ReleaseStatusValuesType,
+    },
+    total=False,
+)
+
+LimitationTypeDef = TypedDict(
+    "LimitationTypeDef",
+    {
+        "DatabaseId": str,
+        "EngineName": str,
+        "Name": str,
+        "Description": str,
+        "Impact": str,
+        "Type": str,
     },
     total=False,
 )
 
 DescribeRefreshSchemasStatusMessageRequestTypeDef = TypedDict(
     "DescribeRefreshSchemasStatusMessageRequestTypeDef",
     {
@@ -1155,14 +1220,23 @@
         "ReplicationTaskName": str,
         "ReplicationTaskArn": str,
         "ReplicationInstanceTaskLogSize": int,
     },
     total=False,
 )
 
+DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef = TypedDict(
+    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
+    {
+        "ReplicationTaskArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef = TypedDict(
     "DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
         "MaxRecords": int,
         "Marker": str,
     },
@@ -1191,14 +1265,34 @@
         "IndividualAssessmentName": str,
         "Status": str,
         "ReplicationTaskIndividualAssessmentStartDate": datetime,
     },
     total=False,
 )
 
+_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
+    {
+        "EndpointArn": str,
+    },
+)
+_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeSchemasMessageDescribeSchemasPaginateTypeDef(
+    _RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+    _OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeSchemasMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeSchemasMessageRequestTypeDef",
     {
         "EndpointArn": str,
     },
 )
 _OptionalDescribeSchemasMessageRequestTypeDef = TypedDict(
@@ -1211,14 +1305,23 @@
 )
 
 class DescribeSchemasMessageRequestTypeDef(
     _RequiredDescribeSchemasMessageRequestTypeDef, _OptionalDescribeSchemasMessageRequestTypeDef
 ):
     pass
 
+DescribeSchemasResponseTypeDef = TypedDict(
+    "DescribeSchemasResponseTypeDef",
+    {
+        "Marker": str,
+        "Schemas": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TableStatisticsTypeDef = TypedDict(
     "TableStatisticsTypeDef",
     {
         "SchemaName": str,
         "TableName": str,
         "Inserts": int,
         "Deletes": int,
@@ -1241,14 +1344,21 @@
         "ValidationSuspendedRecords": int,
         "ValidationState": str,
         "ValidationStateDetails": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceMessageRequestTypeDef = TypedDict(
     "ListTagsForResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
         "ResourceArnList": Sequence[str],
     },
     total=False,
@@ -1359,27 +1469,65 @@
     "MoveReplicationTaskMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
         "TargetReplicationInstanceArn": str,
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
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
         "Action": str,
         "AutoAppliedAfterDate": datetime,
         "ForcedApplyDate": datetime,
         "OptInStatus": str,
         "CurrentApplyDate": datetime,
         "Description": str,
     },
     total=False,
 )
 
+RdsConfigurationTypeDef = TypedDict(
+    "RdsConfigurationTypeDef",
+    {
+        "EngineEdition": str,
+        "InstanceType": str,
+        "InstanceVcpu": float,
+        "InstanceMemory": float,
+        "StorageType": str,
+        "StorageSize": int,
+        "StorageIops": int,
+        "DeploymentOption": str,
+    },
+    total=False,
+)
+
+RdsRequirementsTypeDef = TypedDict(
+    "RdsRequirementsTypeDef",
+    {
+        "EngineEdition": str,
+        "InstanceVcpu": float,
+        "InstanceMemory": float,
+        "StorageSize": int,
+        "StorageIops": int,
+        "DeploymentOption": str,
+    },
+    total=False,
+)
+
 _RequiredRebootReplicationInstanceMessageRequestTypeDef = TypedDict(
     "_RequiredRebootReplicationInstanceMessageRequestTypeDef",
     {
         "ReplicationInstanceArn": str,
     },
 )
 _OptionalRebootReplicationInstanceMessageRequestTypeDef = TypedDict(
@@ -1393,14 +1541,22 @@
 
 class RebootReplicationInstanceMessageRequestTypeDef(
     _RequiredRebootReplicationInstanceMessageRequestTypeDef,
     _OptionalRebootReplicationInstanceMessageRequestTypeDef,
 ):
     pass
 
+RecommendationSettingsTypeDef = TypedDict(
+    "RecommendationSettingsTypeDef",
+    {
+        "InstanceSizingType": str,
+        "WorkloadType": str,
+    },
+)
+
 RefreshSchemasMessageRequestTypeDef = TypedDict(
     "RefreshSchemasMessageRequestTypeDef",
     {
         "EndpointArn": str,
         "ReplicationInstanceArn": str,
     },
 )
@@ -1409,14 +1565,22 @@
     "TableToReloadTypeDef",
     {
         "SchemaName": str,
         "TableName": str,
     },
 )
 
+ReloadTablesResponseTypeDef = TypedDict(
+    "ReloadTablesResponseTypeDef",
+    {
+        "ReplicationTaskArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsFromResourceMessageRequestTypeDef = TypedDict(
     "RemoveTagsFromResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1465,14 +1629,34 @@
         "StopDate": datetime,
         "FullLoadStartDate": datetime,
         "FullLoadFinishDate": datetime,
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
+RunFleetAdvisorLsaAnalysisResponseTypeDef = TypedDict(
+    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
+    {
+        "LsaAnalysisId": str,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SchemaShortInfoResponseTypeDef = TypedDict(
     "SchemaShortInfoResponseTypeDef",
     {
         "SchemaId": str,
         "SchemaName": str,
         "DatabaseId": str,
         "DatabaseName": str,
@@ -1557,14 +1741,31 @@
     "UpdateSubscriptionsToEventBridgeMessageRequestTypeDef",
     {
         "ForceMove": bool,
     },
     total=False,
 )
 
+UpdateSubscriptionsToEventBridgeResponseTypeDef = TypedDict(
+    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
+    {
+        "Result": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAccountAttributesResponseTypeDef = TypedDict(
+    "DescribeAccountAttributesResponseTypeDef",
+    {
+        "AccountQuotas": List[AccountQuotaTypeDef],
+        "UniqueAccountIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AddTagsToResourceMessageRequestTypeDef = TypedDict(
     "AddTagsToResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
@@ -1698,133 +1899,62 @@
 )
 
 class ImportCertificateMessageRequestTypeDef(
     _RequiredImportCertificateMessageRequestTypeDef, _OptionalImportCertificateMessageRequestTypeDef
 ):
     pass
 
-CreateFleetAdvisorCollectorResponseTypeDef = TypedDict(
-    "CreateFleetAdvisorCollectorResponseTypeDef",
-    {
-        "CollectorReferencedId": str,
-        "CollectorName": str,
-        "Description": str,
-        "ServiceAccessRoleArn": str,
-        "S3BucketName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteFleetAdvisorDatabasesResponseTypeDef = TypedDict(
-    "DeleteFleetAdvisorDatabasesResponseTypeDef",
-    {
-        "DatabaseIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountAttributesResponseTypeDef = TypedDict(
-    "DescribeAccountAttributesResponseTypeDef",
-    {
-        "AccountQuotas": List[AccountQuotaTypeDef],
-        "UniqueAccountIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicableIndividualAssessmentsResponseTypeDef = TypedDict(
-    "DescribeApplicableIndividualAssessmentsResponseTypeDef",
-    {
-        "IndividualAssessmentNames": List[str],
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeSchemasResponseTypeDef = TypedDict(
-    "DescribeSchemasResponseTypeDef",
-    {
-        "Marker": str,
-        "Schemas": List[str],
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReloadTablesResponseTypeDef = TypedDict(
-    "ReloadTablesResponseTypeDef",
-    {
-        "ReplicationTaskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RunFleetAdvisorLsaAnalysisResponseTypeDef = TypedDict(
-    "RunFleetAdvisorLsaAnalysisResponseTypeDef",
-    {
-        "LsaAnalysisId": str,
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSubscriptionsToEventBridgeResponseTypeDef = TypedDict(
-    "UpdateSubscriptionsToEventBridgeResponseTypeDef",
-    {
-        "Result": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubnetTypeDef = TypedDict(
     "SubnetTypeDef",
     {
         "SubnetIdentifier": str,
         "SubnetAvailabilityZone": AvailabilityZoneTypeDef,
         "SubnetStatus": str,
     },
     total=False,
 )
 
+BatchStartRecommendationsResponseTypeDef = TypedDict(
+    "BatchStartRecommendationsResponseTypeDef",
+    {
+        "ErrorEntries": List[BatchStartRecommendationsErrorEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCertificateResponseTypeDef = TypedDict(
     "DeleteCertificateResponseTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificatesResponseTypeDef = TypedDict(
     "DescribeCertificatesResponseTypeDef",
     {
         "Marker": str,
         "Certificates": List[CertificateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportCertificateResponseTypeDef = TypedDict(
     "ImportCertificateResponseTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CollectorResponseTypeDef = TypedDict(
     "CollectorResponseTypeDef",
     {
         "CollectorReferencedId": str,
@@ -1844,32 +1974,32 @@
     total=False,
 )
 
 DeleteConnectionResponseTypeDef = TypedDict(
     "DeleteConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectionsResponseTypeDef = TypedDict(
     "DescribeConnectionsResponseTypeDef",
     {
         "Marker": str,
         "Connections": List[ConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestConnectionResponseTypeDef = TypedDict(
     "TestConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEndpointMessageRequestTypeDef = TypedDict(
     "_RequiredCreateEndpointMessageRequestTypeDef",
     {
         "EndpointIdentifier": str,
@@ -2012,40 +2142,40 @@
 ):
     pass
 
 CreateEventSubscriptionResponseTypeDef = TypedDict(
     "CreateEventSubscriptionResponseTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventSubscriptionResponseTypeDef = TypedDict(
     "DeleteEventSubscriptionResponseTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventSubscriptionsResponseTypeDef = TypedDict(
     "DescribeEventSubscriptionsResponseTypeDef",
     {
         "Marker": str,
         "EventSubscriptionsList": List[EventSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyEventSubscriptionResponseTypeDef = TypedDict(
     "ModifyEventSubscriptionResponseTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatabaseResponseTypeDef = TypedDict(
     "DatabaseResponseTypeDef",
     {
         "DatabaseId": str,
@@ -2055,44 +2185,80 @@
         "Server": ServerShortInfoResponseTypeDef,
         "SoftwareDetails": DatabaseInstanceSoftwareDetailsResponseTypeDef,
         "Collectors": List[CollectorShortInfoResponseTypeDef],
     },
     total=False,
 )
 
+DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCertificatesMessageRequestTypeDef = TypedDict(
     "DescribeCertificatesMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef = TypedDict(
+    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConnectionsMessageRequestTypeDef = TypedDict(
     "DescribeConnectionsMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef = TypedDict(
+    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEndpointTypesMessageRequestTypeDef = TypedDict(
     "DescribeEndpointTypesMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef = TypedDict(
+    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEndpointsMessageRequestTypeDef = TypedDict(
     "DescribeEndpointsMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
@@ -2104,25 +2270,50 @@
     {
         "SourceType": str,
         "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
+DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
+    {
+        "SubscriptionName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventSubscriptionsMessageRequestTypeDef = TypedDict(
     "DescribeEventSubscriptionsMessageRequestTypeDef",
     {
         "SubscriptionName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+    {
+        "SourceIdentifier": str,
+        "SourceType": Literal["replication-instance"],
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "EventCategories": Sequence[str],
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsMessageRequestTypeDef = TypedDict(
     "DescribeEventsMessageRequestTypeDef",
     {
         "SourceIdentifier": str,
         "SourceType": Literal["replication-instance"],
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -2182,231 +2373,153 @@
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
-DescribeReplicationInstancesMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationInstancesMessageRequestTypeDef",
+DescribeRecommendationLimitationsRequestRequestTypeDef = TypedDict(
+    "DescribeRecommendationLimitationsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
-        "Marker": str,
+        "NextToken": str,
     },
     total=False,
 )
 
-DescribeReplicationSubnetGroupsMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationSubnetGroupsMessageRequestTypeDef",
+DescribeRecommendationsRequestRequestTypeDef = TypedDict(
+    "DescribeRecommendationsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
-        "Marker": str,
+        "NextToken": str,
     },
     total=False,
 )
 
-DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef",
+DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef = TypedDict(
+    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef",
+DescribeReplicationInstancesMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationInstancesMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-DescribeReplicationTasksMessageRequestTypeDef = TypedDict(
-    "DescribeReplicationTasksMessageRequestTypeDef",
+DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
-        "WithoutSettings": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeTableStatisticsMessageRequestTypeDef",
-    {
-        "ReplicationTaskArn": str,
-    },
-)
-_OptionalDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeTableStatisticsMessageRequestTypeDef",
+DescribeReplicationSubnetGroupsMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationSubnetGroupsMessageRequestTypeDef",
     {
+        "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
-
-class DescribeTableStatisticsMessageRequestTypeDef(
-    _RequiredDescribeTableStatisticsMessageRequestTypeDef,
-    _OptionalDescribeTableStatisticsMessageRequestTypeDef,
-):
-    pass
-
-DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef = TypedDict(
-    "DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef = TypedDict(
-    "DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef = TypedDict(
-    "DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
+DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef",
     {
-        "SubscriptionName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef",
     {
-        "SourceIdentifier": str,
-        "SourceType": Literal["replication-instance"],
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "EventCategories": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef = TypedDict(
-    "DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef = TypedDict(
-    "DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef",
+DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef = TypedDict(
+    "DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "WithoutSettings": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef",
+DescribeReplicationTasksMessageRequestTypeDef = TypedDict(
+    "DescribeReplicationTasksMessageRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
+        "WithoutSettings": bool,
     },
     total=False,
 )
 
-DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef = TypedDict(
-    "DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef",
+_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
     {
         "ReplicationTaskArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
-    total=False,
 )
-
-DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef = TypedDict(
-    "DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef",
+_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "WithoutSettings": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
-    {
-        "EndpointArn": str,
-    },
-)
-_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeSchemasMessageDescribeSchemasPaginateTypeDef(
-    _RequiredDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
-    _OptionalDescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+class DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef(
+    _RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+    _OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
 ):
     pass
 
-_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
+_RequiredDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeTableStatisticsMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
     },
 )
-_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef",
+_OptionalDescribeTableStatisticsMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeTableStatisticsMessageRequestTypeDef",
     {
+        "MaxRecords": int,
+        "Marker": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-class DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef(
-    _RequiredDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
-    _OptionalDescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+class DescribeTableStatisticsMessageRequestTypeDef(
+    _RequiredDescribeTableStatisticsMessageRequestTypeDef,
+    _OptionalDescribeTableStatisticsMessageRequestTypeDef,
 ):
     pass
 
 DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef = TypedDict(
     "DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
@@ -2499,135 +2612,169 @@
 )
 
 DescribeEndpointSettingsResponseTypeDef = TypedDict(
     "DescribeEndpointSettingsResponseTypeDef",
     {
         "Marker": str,
         "EndpointSettings": List[EndpointSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointTypesResponseTypeDef = TypedDict(
     "DescribeEndpointTypesResponseTypeDef",
     {
         "Marker": str,
         "SupportedEndpointTypes": List[SupportedEndpointTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventCategoriesResponseTypeDef = TypedDict(
     "DescribeEventCategoriesResponseTypeDef",
     {
         "EventCategoryGroupList": List[EventCategoryGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "Marker": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorLsaAnalysisResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorLsaAnalysisResponseTypeDef",
     {
         "Analysis": List[FleetAdvisorLsaAnalysisResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef",
     {
         "FleetAdvisorSchemaObjects": List[FleetAdvisorSchemaObjectResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrderableReplicationInstancesResponseTypeDef = TypedDict(
     "DescribeOrderableReplicationInstancesResponseTypeDef",
     {
         "OrderableReplicationInstances": List[OrderableReplicationInstanceTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeRecommendationLimitationsResponseTypeDef = TypedDict(
+    "DescribeRecommendationLimitationsResponseTypeDef",
+    {
+        "NextToken": str,
+        "Limitations": List[LimitationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRefreshSchemasStatusResponseTypeDef = TypedDict(
     "DescribeRefreshSchemasStatusResponseTypeDef",
     {
         "RefreshSchemasStatus": RefreshSchemasStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RefreshSchemasResponseTypeDef = TypedDict(
     "RefreshSchemasResponseTypeDef",
     {
         "RefreshSchemasStatus": RefreshSchemasStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationInstanceTaskLogsResponseTypeDef = TypedDict(
     "DescribeReplicationInstanceTaskLogsResponseTypeDef",
     {
         "ReplicationInstanceArn": str,
         "ReplicationInstanceTaskLogs": List[ReplicationInstanceTaskLogTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTaskAssessmentResultsResponseTypeDef = TypedDict(
     "DescribeReplicationTaskAssessmentResultsResponseTypeDef",
     {
         "Marker": str,
         "BucketName": str,
         "ReplicationTaskAssessmentResults": List[ReplicationTaskAssessmentResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTaskIndividualAssessmentsResponseTypeDef = TypedDict(
     "DescribeReplicationTaskIndividualAssessmentsResponseTypeDef",
     {
         "Marker": str,
         "ReplicationTaskIndividualAssessments": List[ReplicationTaskIndividualAssessmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTableStatisticsResponseTypeDef = TypedDict(
     "DescribeTableStatisticsResponseTypeDef",
     {
         "ReplicationTaskArn": str,
         "TableStatistics": List[TableStatisticsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourcePendingMaintenanceActionsTypeDef = TypedDict(
     "ResourcePendingMaintenanceActionsTypeDef",
     {
         "ResourceIdentifier": str,
         "PendingMaintenanceActionDetails": List[PendingMaintenanceActionTypeDef],
     },
     total=False,
 )
 
+RdsRecommendationTypeDef = TypedDict(
+    "RdsRecommendationTypeDef",
+    {
+        "RequirementsToTarget": RdsRequirementsTypeDef,
+        "TargetConfiguration": RdsConfigurationTypeDef,
+    },
+    total=False,
+)
+
+StartRecommendationsRequestEntryTypeDef = TypedDict(
+    "StartRecommendationsRequestEntryTypeDef",
+    {
+        "DatabaseId": str,
+        "Settings": RecommendationSettingsTypeDef,
+    },
+)
+
+StartRecommendationsRequestRequestTypeDef = TypedDict(
+    "StartRecommendationsRequestRequestTypeDef",
+    {
+        "DatabaseId": str,
+        "Settings": RecommendationSettingsTypeDef,
+    },
+)
+
 _RequiredReloadTablesMessageRequestTypeDef = TypedDict(
     "_RequiredReloadTablesMessageRequestTypeDef",
     {
         "ReplicationTaskArn": str,
         "TablesToReload": Sequence[TableToReloadTypeDef],
     },
 )
@@ -2719,206 +2866,222 @@
 )
 
 DescribeFleetAdvisorCollectorsResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorCollectorsResponseTypeDef",
     {
         "Collectors": List[CollectorResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEndpointResponseTypeDef = TypedDict(
     "CreateEndpointResponseTypeDef",
     {
         "Endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEndpointResponseTypeDef = TypedDict(
     "DeleteEndpointResponseTypeDef",
     {
         "Endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Marker": str,
         "Endpoints": List[EndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyEndpointResponseTypeDef = TypedDict(
     "ModifyEndpointResponseTypeDef",
     {
         "Endpoint": EndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorDatabasesResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorDatabasesResponseTypeDef",
     {
         "Databases": List[DatabaseResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplyPendingMaintenanceActionResponseTypeDef = TypedDict(
     "ApplyPendingMaintenanceActionResponseTypeDef",
     {
         "ResourcePendingMaintenanceActions": ResourcePendingMaintenanceActionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePendingMaintenanceActionsResponseTypeDef = TypedDict(
     "DescribePendingMaintenanceActionsResponseTypeDef",
     {
         "PendingMaintenanceActions": List[ResourcePendingMaintenanceActionsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecommendationDataTypeDef = TypedDict(
+    "RecommendationDataTypeDef",
+    {
+        "RdsEngine": RdsRecommendationTypeDef,
+    },
+    total=False,
+)
+
+BatchStartRecommendationsRequestRequestTypeDef = TypedDict(
+    "BatchStartRecommendationsRequestRequestTypeDef",
+    {
+        "Data": Sequence[StartRecommendationsRequestEntryTypeDef],
     },
+    total=False,
 )
 
 CancelReplicationTaskAssessmentRunResponseTypeDef = TypedDict(
     "CancelReplicationTaskAssessmentRunResponseTypeDef",
     {
         "ReplicationTaskAssessmentRun": ReplicationTaskAssessmentRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationTaskAssessmentRunResponseTypeDef = TypedDict(
     "DeleteReplicationTaskAssessmentRunResponseTypeDef",
     {
         "ReplicationTaskAssessmentRun": ReplicationTaskAssessmentRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTaskAssessmentRunsResponseTypeDef = TypedDict(
     "DescribeReplicationTaskAssessmentRunsResponseTypeDef",
     {
         "Marker": str,
         "ReplicationTaskAssessmentRuns": List[ReplicationTaskAssessmentRunTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationTaskAssessmentRunResponseTypeDef = TypedDict(
     "StartReplicationTaskAssessmentRunResponseTypeDef",
     {
         "ReplicationTaskAssessmentRun": ReplicationTaskAssessmentRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReplicationTaskResponseTypeDef = TypedDict(
     "CreateReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationTaskResponseTypeDef = TypedDict(
     "DeleteReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationTasksResponseTypeDef = TypedDict(
     "DescribeReplicationTasksResponseTypeDef",
     {
         "Marker": str,
         "ReplicationTasks": List[ReplicationTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationTaskResponseTypeDef = TypedDict(
     "ModifyReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MoveReplicationTaskResponseTypeDef = TypedDict(
     "MoveReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationTaskAssessmentResponseTypeDef = TypedDict(
     "StartReplicationTaskAssessmentResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationTaskResponseTypeDef = TypedDict(
     "StartReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopReplicationTaskResponseTypeDef = TypedDict(
     "StopReplicationTaskResponseTypeDef",
     {
         "ReplicationTask": ReplicationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAdvisorSchemasResponseTypeDef = TypedDict(
     "DescribeFleetAdvisorSchemasResponseTypeDef",
     {
         "FleetAdvisorSchemas": List[SchemaResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReplicationSubnetGroupResponseTypeDef = TypedDict(
     "CreateReplicationSubnetGroupResponseTypeDef",
     {
         "ReplicationSubnetGroup": ReplicationSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationSubnetGroupsResponseTypeDef = TypedDict(
     "DescribeReplicationSubnetGroupsResponseTypeDef",
     {
         "Marker": str,
         "ReplicationSubnetGroups": List[ReplicationSubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationSubnetGroupResponseTypeDef = TypedDict(
     "ModifyReplicationSubnetGroupResponseTypeDef",
     {
         "ReplicationSubnetGroup": ReplicationSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationInstanceTypeDef = TypedDict(
     "ReplicationInstanceTypeDef",
     {
         "ReplicationInstanceIdentifier": str,
@@ -2946,47 +3109,70 @@
         "FreeUntil": datetime,
         "DnsNameServers": str,
         "NetworkType": str,
     },
     total=False,
 )
 
+RecommendationTypeDef = TypedDict(
+    "RecommendationTypeDef",
+    {
+        "DatabaseId": str,
+        "EngineName": str,
+        "CreatedDate": str,
+        "Status": str,
+        "Preferred": bool,
+        "Settings": RecommendationSettingsTypeDef,
+        "Data": RecommendationDataTypeDef,
+    },
+    total=False,
+)
+
 CreateReplicationInstanceResponseTypeDef = TypedDict(
     "CreateReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationInstanceResponseTypeDef = TypedDict(
     "DeleteReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReplicationInstancesResponseTypeDef = TypedDict(
     "DescribeReplicationInstancesResponseTypeDef",
     {
         "Marker": str,
         "ReplicationInstances": List[ReplicationInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationInstanceResponseTypeDef = TypedDict(
     "ModifyReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootReplicationInstanceResponseTypeDef = TypedDict(
     "RebootReplicationInstanceResponseTypeDef",
     {
         "ReplicationInstance": ReplicationInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeRecommendationsResponseTypeDef = TypedDict(
+    "DescribeRecommendationsResponseTypeDef",
+    {
+        "NextToken": str,
+        "Recommendations": List[RecommendationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/waiter.py` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms/waiter.pyi` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/PKG-INFO` & `types-aiobotocore-dms-2.5.1/README.md`

 * *Files 20% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-dms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DatabaseMigrationService 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore dms type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-dms"></a>
 
 # types-aiobotocore-dms
 
 [![PyPI - types-aiobotocore-dms](https://img.shields.io/pypi/v/types-aiobotocore-dms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dms?color=blue)](https://pypistats.org/packages/types-aiobotocore-dms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DatabaseMigrationService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
+[aiobotocore.DatabaseMigrationService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dms.html#DatabaseMigrationService)
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
 [types-aiobotocore-dms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -419,14 +386,15 @@
     DescribeSchemasPaginatorName,
     DescribeTableStatisticsPaginatorName,
     DmsSslModeValueType,
     EncodingTypeValueType,
     EncryptionModeValueType,
     EndpointDeletedWaiterName,
     EndpointSettingTypeValueType,
+    KafkaSaslMechanismType,
     KafkaSecurityProtocolType,
     MessageFormatValueType,
     MigrationTypeValueType,
     NestingLevelValueType,
     ParquetVersionValueType,
     PluginNameValueType,
     RedisAuthTypeValueType,
@@ -442,14 +410,15 @@
     ReplicationTaskStoppedWaiterName,
     SafeguardPolicyType,
     SourceTypeType,
     SslSecurityProtocolValueType,
     StartReplicationTaskTypeValueType,
     TargetDbTypeType,
     TestConnectionSucceedsWaiterName,
+    TlogAccessModeType,
     VersionStatusType,
     DatabaseMigrationServiceServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
     RegionName,
@@ -468,16 +437,16 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dms.type_defs import (
     AccountQuotaTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
-    ResponseMetadataTypeDef,
     AvailabilityZoneTypeDef,
+    BatchStartRecommendationsErrorEntryTypeDef,
     CancelReplicationTaskAssessmentRunMessageRequestTypeDef,
     CertificateTypeDef,
     CollectorHealthCheckTypeDef,
     InventoryDataTypeDef,
     CollectorShortInfoResponseTypeDef,
     ConnectionTypeDef,
     DmsTransferSettingsTypeDef,
@@ -496,89 +465,98 @@
     PostgreSQLSettingsTypeDef,
     RedisSettingsTypeDef,
     RedshiftSettingsTypeDef,
     S3SettingsTypeDef,
     SybaseSettingsTypeDef,
     EventSubscriptionTypeDef,
     CreateFleetAdvisorCollectorRequestRequestTypeDef,
+    CreateFleetAdvisorCollectorResponseTypeDef,
     DatabaseInstanceSoftwareDetailsResponseTypeDef,
     ServerShortInfoResponseTypeDef,
     DatabaseShortInfoResponseTypeDef,
     DeleteCertificateMessageRequestTypeDef,
     DeleteCollectorRequestRequestTypeDef,
     DeleteConnectionMessageRequestTypeDef,
     DeleteEndpointMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteFleetAdvisorDatabasesRequestRequestTypeDef,
+    DeleteFleetAdvisorDatabasesResponseTypeDef,
     DeleteReplicationInstanceMessageRequestTypeDef,
     DeleteReplicationSubnetGroupMessageRequestTypeDef,
     DeleteReplicationTaskAssessmentRunMessageRequestTypeDef,
     DeleteReplicationTaskMessageRequestTypeDef,
     DescribeApplicableIndividualAssessmentsMessageRequestTypeDef,
+    DescribeApplicableIndividualAssessmentsResponseTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     WaiterConfigTypeDef,
     DescribeEndpointSettingsMessageRequestTypeDef,
     EndpointSettingTypeDef,
     SupportedEndpointTypeTypeDef,
     EventCategoryGroupTypeDef,
     EventTypeDef,
     DescribeFleetAdvisorLsaAnalysisRequestRequestTypeDef,
     FleetAdvisorLsaAnalysisResponseTypeDef,
     FleetAdvisorSchemaObjectResponseTypeDef,
+    DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef,
     DescribeOrderableReplicationInstancesMessageRequestTypeDef,
     OrderableReplicationInstanceTypeDef,
+    LimitationTypeDef,
     DescribeRefreshSchemasStatusMessageRequestTypeDef,
     RefreshSchemasStatusTypeDef,
     DescribeReplicationInstanceTaskLogsMessageRequestTypeDef,
     ReplicationInstanceTaskLogTypeDef,
+    DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef,
     DescribeReplicationTaskAssessmentResultsMessageRequestTypeDef,
     ReplicationTaskAssessmentResultTypeDef,
     ReplicationTaskIndividualAssessmentTypeDef,
+    DescribeSchemasMessageDescribeSchemasPaginateTypeDef,
     DescribeSchemasMessageRequestTypeDef,
+    DescribeSchemasResponseTypeDef,
     TableStatisticsTypeDef,
+    EmptyResponseMetadataTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyReplicationInstanceMessageRequestTypeDef,
     ModifyReplicationSubnetGroupMessageRequestTypeDef,
     ModifyReplicationTaskMessageRequestTypeDef,
     MoveReplicationTaskMessageRequestTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
+    RdsConfigurationTypeDef,
+    RdsRequirementsTypeDef,
     RebootReplicationInstanceMessageRequestTypeDef,
+    RecommendationSettingsTypeDef,
     RefreshSchemasMessageRequestTypeDef,
     TableToReloadTypeDef,
+    ReloadTablesResponseTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
     ReplicationPendingModifiedValuesTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     ReplicationTaskAssessmentRunProgressTypeDef,
     ReplicationTaskStatsTypeDef,
+    ResponseMetadataTypeDef,
+    RunFleetAdvisorLsaAnalysisResponseTypeDef,
     SchemaShortInfoResponseTypeDef,
     StartReplicationTaskAssessmentMessageRequestTypeDef,
     StartReplicationTaskAssessmentRunMessageRequestTypeDef,
     StartReplicationTaskMessageRequestTypeDef,
     StopReplicationTaskMessageRequestTypeDef,
     TestConnectionMessageRequestTypeDef,
     UpdateSubscriptionsToEventBridgeMessageRequestTypeDef,
+    UpdateSubscriptionsToEventBridgeResponseTypeDef,
+    DescribeAccountAttributesResponseTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CreateEventSubscriptionMessageRequestTypeDef,
     CreateReplicationInstanceMessageRequestTypeDef,
     CreateReplicationSubnetGroupMessageRequestTypeDef,
     CreateReplicationTaskMessageRequestTypeDef,
     ImportCertificateMessageRequestTypeDef,
-    CreateFleetAdvisorCollectorResponseTypeDef,
-    DeleteFleetAdvisorDatabasesResponseTypeDef,
-    DescribeAccountAttributesResponseTypeDef,
-    DescribeApplicableIndividualAssessmentsResponseTypeDef,
-    DescribeSchemasResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    ReloadTablesResponseTypeDef,
-    RunFleetAdvisorLsaAnalysisResponseTypeDef,
-    UpdateSubscriptionsToEventBridgeResponseTypeDef,
     SubnetTypeDef,
+    BatchStartRecommendationsResponseTypeDef,
     DeleteCertificateResponseTypeDef,
     DescribeCertificatesResponseTypeDef,
     ImportCertificateResponseTypeDef,
     CollectorResponseTypeDef,
     DeleteConnectionResponseTypeDef,
     DescribeConnectionsResponseTypeDef,
     TestConnectionResponseTypeDef,
@@ -586,45 +564,44 @@
     EndpointTypeDef,
     ModifyEndpointMessageRequestTypeDef,
     CreateEventSubscriptionResponseTypeDef,
     DeleteEventSubscriptionResponseTypeDef,
     DescribeEventSubscriptionsResponseTypeDef,
     ModifyEventSubscriptionResponseTypeDef,
     DatabaseResponseTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
+    DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef,
     DescribeConnectionsMessageRequestTypeDef,
+    DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef,
     DescribeEndpointTypesMessageRequestTypeDef,
+    DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef,
     DescribeEndpointsMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
     DescribeFleetAdvisorCollectorsRequestRequestTypeDef,
     DescribeFleetAdvisorDatabasesRequestRequestTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryRequestRequestTypeDef,
     DescribeFleetAdvisorSchemasRequestRequestTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
+    DescribeRecommendationLimitationsRequestRequestTypeDef,
+    DescribeRecommendationsRequestRequestTypeDef,
+    DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef,
     DescribeReplicationInstancesMessageRequestTypeDef,
+    DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef,
     DescribeReplicationSubnetGroupsMessageRequestTypeDef,
     DescribeReplicationTaskAssessmentRunsMessageRequestTypeDef,
     DescribeReplicationTaskIndividualAssessmentsMessageRequestTypeDef,
-    DescribeReplicationTasksMessageRequestTypeDef,
-    DescribeTableStatisticsMessageRequestTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeConnectionsMessageDescribeConnectionsPaginateTypeDef,
-    DescribeEndpointTypesMessageDescribeEndpointTypesPaginateTypeDef,
-    DescribeEndpointsMessageDescribeEndpointsPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeOrderableReplicationInstancesMessageDescribeOrderableReplicationInstancesPaginateTypeDef,
-    DescribeReplicationInstancesMessageDescribeReplicationInstancesPaginateTypeDef,
-    DescribeReplicationSubnetGroupsMessageDescribeReplicationSubnetGroupsPaginateTypeDef,
-    DescribeReplicationTaskAssessmentResultsMessageDescribeReplicationTaskAssessmentResultsPaginateTypeDef,
     DescribeReplicationTasksMessageDescribeReplicationTasksPaginateTypeDef,
-    DescribeSchemasMessageDescribeSchemasPaginateTypeDef,
+    DescribeReplicationTasksMessageRequestTypeDef,
     DescribeTableStatisticsMessageDescribeTableStatisticsPaginateTypeDef,
+    DescribeTableStatisticsMessageRequestTypeDef,
     DescribeConnectionsMessageTestConnectionSucceedsWaitTypeDef,
     DescribeEndpointsMessageEndpointDeletedWaitTypeDef,
     DescribeReplicationInstancesMessageReplicationInstanceAvailableWaitTypeDef,
     DescribeReplicationInstancesMessageReplicationInstanceDeletedWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskDeletedWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskReadyWaitTypeDef,
     DescribeReplicationTasksMessageReplicationTaskRunningWaitTypeDef,
@@ -632,34 +609,40 @@
     DescribeEndpointSettingsResponseTypeDef,
     DescribeEndpointTypesResponseTypeDef,
     DescribeEventCategoriesResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeFleetAdvisorLsaAnalysisResponseTypeDef,
     DescribeFleetAdvisorSchemaObjectSummaryResponseTypeDef,
     DescribeOrderableReplicationInstancesResponseTypeDef,
+    DescribeRecommendationLimitationsResponseTypeDef,
     DescribeRefreshSchemasStatusResponseTypeDef,
     RefreshSchemasResponseTypeDef,
     DescribeReplicationInstanceTaskLogsResponseTypeDef,
     DescribeReplicationTaskAssessmentResultsResponseTypeDef,
     DescribeReplicationTaskIndividualAssessmentsResponseTypeDef,
     DescribeTableStatisticsResponseTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
+    RdsRecommendationTypeDef,
+    StartRecommendationsRequestEntryTypeDef,
+    StartRecommendationsRequestRequestTypeDef,
     ReloadTablesMessageRequestTypeDef,
     ReplicationTaskAssessmentRunTypeDef,
     ReplicationTaskTypeDef,
     SchemaResponseTypeDef,
     ReplicationSubnetGroupTypeDef,
     DescribeFleetAdvisorCollectorsResponseTypeDef,
     CreateEndpointResponseTypeDef,
     DeleteEndpointResponseTypeDef,
     DescribeEndpointsResponseTypeDef,
     ModifyEndpointResponseTypeDef,
     DescribeFleetAdvisorDatabasesResponseTypeDef,
     ApplyPendingMaintenanceActionResponseTypeDef,
     DescribePendingMaintenanceActionsResponseTypeDef,
+    RecommendationDataTypeDef,
+    BatchStartRecommendationsRequestRequestTypeDef,
     CancelReplicationTaskAssessmentRunResponseTypeDef,
     DeleteReplicationTaskAssessmentRunResponseTypeDef,
     DescribeReplicationTaskAssessmentRunsResponseTypeDef,
     StartReplicationTaskAssessmentRunResponseTypeDef,
     CreateReplicationTaskResponseTypeDef,
     DeleteReplicationTaskResponseTypeDef,
     DescribeReplicationTasksResponseTypeDef,
@@ -669,62 +652,64 @@
     StartReplicationTaskResponseTypeDef,
     StopReplicationTaskResponseTypeDef,
     DescribeFleetAdvisorSchemasResponseTypeDef,
     CreateReplicationSubnetGroupResponseTypeDef,
     DescribeReplicationSubnetGroupsResponseTypeDef,
     ModifyReplicationSubnetGroupResponseTypeDef,
     ReplicationInstanceTypeDef,
+    RecommendationTypeDef,
     CreateReplicationInstanceResponseTypeDef,
     DeleteReplicationInstanceResponseTypeDef,
     DescribeReplicationInstancesResponseTypeDef,
     ModifyReplicationInstanceResponseTypeDef,
     RebootReplicationInstanceResponseTypeDef,
+    DescribeRecommendationsResponseTypeDef,
 )
 
 
 def get_structure() -> AccountQuotaTypeDef:
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

### Comparing `types-aiobotocore-dms-2.5.0.post1/types_aiobotocore_dms.egg-info/SOURCES.txt` & `types-aiobotocore-dms-2.5.1/types_aiobotocore_dms.egg-info/SOURCES.txt`

 * *Files identical despite different names*

