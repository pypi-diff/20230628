# Comparing `tmp/types-aiobotocore-rds-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-rds-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-rds-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-rds-2.5.1.tar", last modified: Wed Jun 28 01:44:02 2023, max compression
```

## Comparing `types-aiobotocore-rds-2.5.0.post1.tar` & `types-aiobotocore-rds-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.883535 types-aiobotocore-rds-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    41682 2023-03-11 12:27:10.879535 types-aiobotocore-rds-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    40127 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:10.883535 types-aiobotocore-rds-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.875535 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/
--rw-r--r--   0 runner    (1001) docker     (123)    11394 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11393 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   148510 2023-03-11 12:21:59.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   148315 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17589 2023-03-11 12:22:00.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    17587 2023-03-11 12:22:00.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    47063 2023-03-11 12:21:59.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    47025 2023-03-11 12:21:59.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   190070 2023-03-11 12:22:06.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   189893 2023-03-11 12:22:01.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:21:58.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    11684 2023-03-11 12:21:59.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)    11675 2023-03-11 12:21:59.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.879535 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    41682 2023-03-11 12:27:10.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:27:10.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:10.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:10.000000 types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.390198 types-aiobotocore-rds-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:38:44.000000 types-aiobotocore-rds-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    41670 2023-06-28 01:44:02.390198 types-aiobotocore-rds-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    40121 2023-06-28 01:38:44.000000 types-aiobotocore-rds-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:02.390198 types-aiobotocore-rds-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:38:44.000000 types-aiobotocore-rds-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.390198 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/
+-rw-r--r--   0 runner    (1001) docker     (123)    11394 2023-06-28 01:38:45.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11393 2023-06-28 01:38:44.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:38:45.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   148836 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   148641 2023-06-28 01:38:45.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17798 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17796 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    47013 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46976 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:38:45.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   190757 2023-06-28 01:38:52.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   190580 2023-06-28 01:38:48.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:38:44.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11684 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11675 2023-06-28 01:38:46.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:02.390198 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    41670 2023-06-28 01:44:02.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:44:02.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:02.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:02.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:02.000000 types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/LICENSE` & `types-aiobotocore-rds-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-rds-2.5.0.post1/PKG-INFO` & `types-aiobotocore-rds-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rds
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RDS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RDS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rds"></a>
 
 # types-aiobotocore-rds
 
 [![PyPI - types-aiobotocore-rds](https://img.shields.io/pypi/v/types-aiobotocore-rds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rds?color=blue)](https://pypistats.org/packages/types-aiobotocore-rds)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RDS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
+[aiobotocore.RDS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
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
 [types-aiobotocore-rds docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/).
 
 See how it helps to find and fix potential bugs:
 
@@ -571,15 +571,14 @@
 
 `types_aiobotocore_rds.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rds.type_defs import (
     AccountQuotaTypeDef,
-    ResponseMetadataTypeDef,
     AddRoleToDBClusterMessageRequestTypeDef,
     AddRoleToDBInstanceMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
@@ -603,18 +602,22 @@
     ServerlessV2ScalingConfigurationTypeDef,
     ProcessorFeatureTypeDef,
     DBProxyEndpointTypeDef,
     UserAuthConfigTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     CustomDBEngineVersionAMITypeDef,
     DBClusterBacktrackTypeDef,
+    DBClusterBacktrackResponseMetadataTypeDef,
+    DBClusterCapacityInfoTypeDef,
     DBClusterEndpointTypeDef,
+    DBClusterEndpointResponseMetadataTypeDef,
     DBClusterMemberTypeDef,
     DBClusterOptionGroupStatusTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     DomainMembershipTypeDef,
     MasterUserSecretTypeDef,
     ScalingConfigurationInfoTypeDef,
     ServerlessV2ScalingConfigurationInfoTypeDef,
     VpcSecurityGroupMembershipTypeDef,
@@ -624,14 +627,15 @@
     RestoreWindowTypeDef,
     DBInstanceRoleTypeDef,
     DBInstanceStatusInfoTypeDef,
     DBParameterGroupStatusTypeDef,
     DBSecurityGroupMembershipTypeDef,
     EndpointTypeDef,
     OptionGroupMembershipTypeDef,
+    DBParameterGroupNameMessageTypeDef,
     TargetHealthTypeDef,
     UserAuthConfigInfoTypeDef,
     EC2SecurityGroupTypeDef,
     IPRangeTypeDef,
     DBSnapshotAttributeTypeDef,
     DeleteBlueGreenDeploymentRequestRequestTypeDef,
     DeleteCustomDBEngineVersionMessageRequestTypeDef,
@@ -648,83 +652,80 @@
     DeleteDBSnapshotMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     DeleteOptionGroupMessageRequestTypeDef,
     DeregisterDBProxyTargetsRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeDBLogFilesDetailsTypeDef,
     DescribeDBSnapshotAttributesMessageRequestTypeDef,
     DescribeValidDBInstanceModificationsMessageRequestTypeDef,
     DoubleRangeTypeDef,
+    DownloadDBLogFilePortionDetailsTypeDef,
+    DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
     DownloadDBLogFilePortionMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
+    ExportTaskResponseMetadataTypeDef,
     ExportTaskTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     FailoverGlobalClusterMessageRequestTypeDef,
     FailoverStateTypeDef,
     GlobalClusterMemberTypeDef,
     MinimumEngineVersionPerAllowedValueTypeDef,
     ModifyActivityStreamRequestRequestTypeDef,
+    ModifyActivityStreamResponseTypeDef,
     ModifyCertificatesMessageRequestTypeDef,
     ModifyCurrentDBClusterCapacityMessageRequestTypeDef,
     ModifyCustomDBEngineVersionMessageRequestTypeDef,
     ModifyDBClusterEndpointMessageRequestTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBProxyEndpointRequestRequestTypeDef,
     ModifyDBSnapshotAttributeMessageRequestTypeDef,
     ModifyDBSnapshotMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
     OptionSettingTypeDef,
     OptionVersionTypeDef,
     OutpostTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PromoteReadReplicaDBClusterMessageRequestTypeDef,
     PromoteReadReplicaMessageRequestTypeDef,
     RangeTypeDef,
     RebootDBClusterMessageRequestTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RecurringChargeTypeDef,
     RegisterDBProxyTargetsRequestRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveRoleFromDBClusterMessageRequestTypeDef,
     RemoveRoleFromDBInstanceMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeDBSecurityGroupIngressMessageRequestTypeDef,
     SourceRegionTypeDef,
     StartActivityStreamRequestRequestTypeDef,
+    StartActivityStreamResponseTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     StartDBInstanceMessageRequestTypeDef,
     StartExportTaskMessageRequestTypeDef,
     StopActivityStreamRequestRequestTypeDef,
+    StopActivityStreamResponseTypeDef,
     StopDBClusterMessageRequestTypeDef,
     StopDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     StopDBInstanceMessageRequestTypeDef,
     SwitchoverBlueGreenDeploymentRequestRequestTypeDef,
     SwitchoverReadReplicaMessageRequestTypeDef,
     AccountAttributesMessageTypeDef,
-    DBClusterBacktrackResponseMetadataTypeDef,
-    DBClusterCapacityInfoTypeDef,
-    DBClusterEndpointResponseMetadataTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
-    DBParameterGroupNameMessageTypeDef,
-    DownloadDBLogFilePortionDetailsTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportTaskResponseMetadataTypeDef,
-    ModifyActivityStreamResponseTypeDef,
-    StartActivityStreamResponseTypeDef,
-    StopActivityStreamResponseTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
     CreateEventSubscriptionResultTypeDef,
     DeleteEventSubscriptionResultTypeDef,
     EventSubscriptionsMessageTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
@@ -793,85 +794,84 @@
     DBEngineVersionResponseMetadataTypeDef,
     DBEngineVersionTypeDef,
     DBInstanceAutomatedBackupTypeDef,
     DBProxyTargetTypeDef,
     DBProxyTypeDef,
     DBSecurityGroupTypeDef,
     DBSnapshotAttributesResultTypeDef,
+    DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef,
     DescribeBlueGreenDeploymentsRequestRequestTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
+    DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
     DescribeDBClusterBacktracksMessageRequestTypeDef,
+    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
     DescribeDBClusterEndpointsMessageRequestTypeDef,
+    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
     DescribeDBClusterParameterGroupsMessageRequestTypeDef,
+    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
     DescribeDBClusterParametersMessageRequestTypeDef,
+    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
     DescribeDBClusterSnapshotsMessageRequestTypeDef,
+    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
     DescribeDBClustersMessageRequestTypeDef,
+    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
     DescribeDBEngineVersionsMessageRequestTypeDef,
+    DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef,
     DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef,
+    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
     DescribeDBInstancesMessageRequestTypeDef,
+    DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
     DescribeDBLogFilesMessageRequestTypeDef,
+    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
     DescribeDBParameterGroupsMessageRequestTypeDef,
+    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
     DescribeDBParametersMessageRequestTypeDef,
+    DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef,
     DescribeDBProxiesRequestRequestTypeDef,
+    DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef,
     DescribeDBProxyEndpointsRequestRequestTypeDef,
+    DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
     DescribeDBProxyTargetGroupsRequestRequestTypeDef,
+    DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
     DescribeDBProxyTargetsRequestRequestTypeDef,
+    DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef,
     DescribeDBSecurityGroupsMessageRequestTypeDef,
+    DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef,
     DescribeDBSnapshotsMessageRequestTypeDef,
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
+    DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef,
     DescribeExportTasksMessageRequestTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
+    DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
     DescribeOptionGroupOptionsMessageRequestTypeDef,
+    DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef,
     DescribeOptionGroupsMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
+    DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef,
     DescribeReservedDBInstancesMessageRequestTypeDef,
+    DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef,
     DescribeReservedDBInstancesOfferingsMessageRequestTypeDef,
+    DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef,
     DescribeSourceRegionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
-    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
-    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
-    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef,
-    DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef,
-    DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
-    DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
-    DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef,
-    DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef,
-    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
-    DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
-    DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef,
-    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
-    DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef,
-    DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef,
-    DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef,
-    DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
     DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef,
     DescribeDBClusterSnapshotsMessageDBClusterSnapshotDeletedWaitTypeDef,
     DescribeDBClustersMessageDBClusterAvailableWaitTypeDef,
     DescribeDBClustersMessageDBClusterDeletedWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef,
     DescribeDBSnapshotsMessageDBSnapshotAvailableWaitTypeDef,
@@ -990,43 +990,43 @@
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/README.md` & `types-aiobotocore-rds-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-rds"></a>
 
 # types-aiobotocore-rds
 
 [![PyPI - types-aiobotocore-rds](https://img.shields.io/pypi/v/types-aiobotocore-rds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rds?color=blue)](https://pypistats.org/packages/types-aiobotocore-rds)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RDS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
+[aiobotocore.RDS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
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
 [types-aiobotocore-rds docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/).
 
 See how it helps to find and fix potential bugs:
 
@@ -538,15 +538,14 @@
 
 `types_aiobotocore_rds.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rds.type_defs import (
     AccountQuotaTypeDef,
-    ResponseMetadataTypeDef,
     AddRoleToDBClusterMessageRequestTypeDef,
     AddRoleToDBInstanceMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
@@ -570,18 +569,22 @@
     ServerlessV2ScalingConfigurationTypeDef,
     ProcessorFeatureTypeDef,
     DBProxyEndpointTypeDef,
     UserAuthConfigTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     CustomDBEngineVersionAMITypeDef,
     DBClusterBacktrackTypeDef,
+    DBClusterBacktrackResponseMetadataTypeDef,
+    DBClusterCapacityInfoTypeDef,
     DBClusterEndpointTypeDef,
+    DBClusterEndpointResponseMetadataTypeDef,
     DBClusterMemberTypeDef,
     DBClusterOptionGroupStatusTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     DomainMembershipTypeDef,
     MasterUserSecretTypeDef,
     ScalingConfigurationInfoTypeDef,
     ServerlessV2ScalingConfigurationInfoTypeDef,
     VpcSecurityGroupMembershipTypeDef,
@@ -591,14 +594,15 @@
     RestoreWindowTypeDef,
     DBInstanceRoleTypeDef,
     DBInstanceStatusInfoTypeDef,
     DBParameterGroupStatusTypeDef,
     DBSecurityGroupMembershipTypeDef,
     EndpointTypeDef,
     OptionGroupMembershipTypeDef,
+    DBParameterGroupNameMessageTypeDef,
     TargetHealthTypeDef,
     UserAuthConfigInfoTypeDef,
     EC2SecurityGroupTypeDef,
     IPRangeTypeDef,
     DBSnapshotAttributeTypeDef,
     DeleteBlueGreenDeploymentRequestRequestTypeDef,
     DeleteCustomDBEngineVersionMessageRequestTypeDef,
@@ -615,83 +619,80 @@
     DeleteDBSnapshotMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     DeleteOptionGroupMessageRequestTypeDef,
     DeregisterDBProxyTargetsRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeDBLogFilesDetailsTypeDef,
     DescribeDBSnapshotAttributesMessageRequestTypeDef,
     DescribeValidDBInstanceModificationsMessageRequestTypeDef,
     DoubleRangeTypeDef,
+    DownloadDBLogFilePortionDetailsTypeDef,
+    DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
     DownloadDBLogFilePortionMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
+    ExportTaskResponseMetadataTypeDef,
     ExportTaskTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     FailoverGlobalClusterMessageRequestTypeDef,
     FailoverStateTypeDef,
     GlobalClusterMemberTypeDef,
     MinimumEngineVersionPerAllowedValueTypeDef,
     ModifyActivityStreamRequestRequestTypeDef,
+    ModifyActivityStreamResponseTypeDef,
     ModifyCertificatesMessageRequestTypeDef,
     ModifyCurrentDBClusterCapacityMessageRequestTypeDef,
     ModifyCustomDBEngineVersionMessageRequestTypeDef,
     ModifyDBClusterEndpointMessageRequestTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBProxyEndpointRequestRequestTypeDef,
     ModifyDBSnapshotAttributeMessageRequestTypeDef,
     ModifyDBSnapshotMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
     OptionSettingTypeDef,
     OptionVersionTypeDef,
     OutpostTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PromoteReadReplicaDBClusterMessageRequestTypeDef,
     PromoteReadReplicaMessageRequestTypeDef,
     RangeTypeDef,
     RebootDBClusterMessageRequestTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RecurringChargeTypeDef,
     RegisterDBProxyTargetsRequestRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveRoleFromDBClusterMessageRequestTypeDef,
     RemoveRoleFromDBInstanceMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeDBSecurityGroupIngressMessageRequestTypeDef,
     SourceRegionTypeDef,
     StartActivityStreamRequestRequestTypeDef,
+    StartActivityStreamResponseTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     StartDBInstanceMessageRequestTypeDef,
     StartExportTaskMessageRequestTypeDef,
     StopActivityStreamRequestRequestTypeDef,
+    StopActivityStreamResponseTypeDef,
     StopDBClusterMessageRequestTypeDef,
     StopDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     StopDBInstanceMessageRequestTypeDef,
     SwitchoverBlueGreenDeploymentRequestRequestTypeDef,
     SwitchoverReadReplicaMessageRequestTypeDef,
     AccountAttributesMessageTypeDef,
-    DBClusterBacktrackResponseMetadataTypeDef,
-    DBClusterCapacityInfoTypeDef,
-    DBClusterEndpointResponseMetadataTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
-    DBParameterGroupNameMessageTypeDef,
-    DownloadDBLogFilePortionDetailsTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportTaskResponseMetadataTypeDef,
-    ModifyActivityStreamResponseTypeDef,
-    StartActivityStreamResponseTypeDef,
-    StopActivityStreamResponseTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
     CreateEventSubscriptionResultTypeDef,
     DeleteEventSubscriptionResultTypeDef,
     EventSubscriptionsMessageTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
@@ -760,85 +761,84 @@
     DBEngineVersionResponseMetadataTypeDef,
     DBEngineVersionTypeDef,
     DBInstanceAutomatedBackupTypeDef,
     DBProxyTargetTypeDef,
     DBProxyTypeDef,
     DBSecurityGroupTypeDef,
     DBSnapshotAttributesResultTypeDef,
+    DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef,
     DescribeBlueGreenDeploymentsRequestRequestTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
+    DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
     DescribeDBClusterBacktracksMessageRequestTypeDef,
+    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
     DescribeDBClusterEndpointsMessageRequestTypeDef,
+    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
     DescribeDBClusterParameterGroupsMessageRequestTypeDef,
+    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
     DescribeDBClusterParametersMessageRequestTypeDef,
+    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
     DescribeDBClusterSnapshotsMessageRequestTypeDef,
+    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
     DescribeDBClustersMessageRequestTypeDef,
+    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
     DescribeDBEngineVersionsMessageRequestTypeDef,
+    DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef,
     DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef,
+    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
     DescribeDBInstancesMessageRequestTypeDef,
+    DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
     DescribeDBLogFilesMessageRequestTypeDef,
+    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
     DescribeDBParameterGroupsMessageRequestTypeDef,
+    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
     DescribeDBParametersMessageRequestTypeDef,
+    DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef,
     DescribeDBProxiesRequestRequestTypeDef,
+    DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef,
     DescribeDBProxyEndpointsRequestRequestTypeDef,
+    DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
     DescribeDBProxyTargetGroupsRequestRequestTypeDef,
+    DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
     DescribeDBProxyTargetsRequestRequestTypeDef,
+    DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef,
     DescribeDBSecurityGroupsMessageRequestTypeDef,
+    DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef,
     DescribeDBSnapshotsMessageRequestTypeDef,
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
+    DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef,
     DescribeExportTasksMessageRequestTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
+    DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
     DescribeOptionGroupOptionsMessageRequestTypeDef,
+    DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef,
     DescribeOptionGroupsMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
+    DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef,
     DescribeReservedDBInstancesMessageRequestTypeDef,
+    DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef,
     DescribeReservedDBInstancesOfferingsMessageRequestTypeDef,
+    DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef,
     DescribeSourceRegionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
-    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
-    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
-    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef,
-    DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef,
-    DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
-    DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
-    DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef,
-    DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef,
-    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
-    DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
-    DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef,
-    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
-    DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef,
-    DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef,
-    DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef,
-    DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
     DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef,
     DescribeDBClusterSnapshotsMessageDBClusterSnapshotDeletedWaitTypeDef,
     DescribeDBClustersMessageDBClusterAvailableWaitTypeDef,
     DescribeDBClustersMessageDBClusterDeletedWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef,
     DescribeDBSnapshotsMessageDBSnapshotAvailableWaitTypeDef,
@@ -957,43 +957,43 @@
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/setup.py` & `types-aiobotocore-rds-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-rds.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-rds",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_rds"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RDS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.RDS 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/",
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/__init__.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/__init__.pyi` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/__main__.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RDS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RDS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS\nOther"
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/client.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -12,15 +12,15 @@
     session = get_session()
     async with session.create_client("rds") as client:
         client: RDSClient
     ```
 """
 import sys
 from datetime import datetime
-from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
+from typing import Any, Dict, Mapping, Optional, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     ActivityStreamModeType,
     AuditPolicyStateType,
@@ -238,14 +238,15 @@
     AuthorizationNotFoundFault: Type[BotocoreClientError]
     AuthorizationQuotaExceededFault: Type[BotocoreClientError]
     BackupPolicyNotFoundFault: Type[BotocoreClientError]
     BlueGreenDeploymentAlreadyExistsFault: Type[BotocoreClientError]
     BlueGreenDeploymentNotFoundFault: Type[BotocoreClientError]
     CertificateNotFoundFault: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    CreateCustomDBEngineVersionFault: Type[BotocoreClientError]
     CustomAvailabilityZoneNotFoundFault: Type[BotocoreClientError]
     CustomDBEngineVersionAlreadyExistsFault: Type[BotocoreClientError]
     CustomDBEngineVersionNotFoundFault: Type[BotocoreClientError]
     CustomDBEngineVersionQuotaExceededFault: Type[BotocoreClientError]
     DBClusterAlreadyExistsFault: Type[BotocoreClientError]
     DBClusterBacktrackNotFoundFault: Type[BotocoreClientError]
     DBClusterEndpointAlreadyExistsFault: Type[BotocoreClientError]
@@ -350,14 +351,15 @@
     SNSTopicArnNotFoundFault: Type[BotocoreClientError]
     SharedSnapshotQuotaExceededFault: Type[BotocoreClientError]
     SnapshotQuotaExceededFault: Type[BotocoreClientError]
     SourceClusterNotSupportedFault: Type[BotocoreClientError]
     SourceDatabaseNotSupportedFault: Type[BotocoreClientError]
     SourceNotFoundFault: Type[BotocoreClientError]
     StorageQuotaExceededFault: Type[BotocoreClientError]
+    StorageTypeNotAvailableFault: Type[BotocoreClientError]
     StorageTypeNotSupportedFault: Type[BotocoreClientError]
     SubnetAlreadyInUse: Type[BotocoreClientError]
     SubscriptionAlreadyExistFault: Type[BotocoreClientError]
     SubscriptionCategoryNotFoundFault: Type[BotocoreClientError]
     SubscriptionNotFoundFault: Type[BotocoreClientError]
 
 
@@ -783,15 +785,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#create_db_instance)
         """
 
     async def create_db_instance_read_replica(
         self,
         *,
         DBInstanceIdentifier: str,
-        SourceDBInstanceIdentifier: str,
+        SourceDBInstanceIdentifier: str = ...,
         DBInstanceClass: str = ...,
         AvailabilityZone: str = ...,
         Port: int = ...,
         MultiAZ: bool = ...,
         AutoMinorVersionUpgrade: bool = ...,
         Iops: int = ...,
         OptionGroupName: str = ...,
@@ -819,19 +821,20 @@
         ReplicaMode: ReplicaModeType = ...,
         MaxAllocatedStorage: int = ...,
         CustomIamInstanceProfile: str = ...,
         NetworkType: str = ...,
         StorageThroughput: int = ...,
         EnableCustomerOwnedIp: bool = ...,
         AllocatedStorage: int = ...,
+        SourceDBClusterIdentifier: str = ...,
         SourceRegion: str = ...
     ) -> CreateDBInstanceReadReplicaResultTypeDef:
         """
         Creates a new DB instance that acts as a read replica for an existing source DB
-        instance.
+        instance or Multi-AZ DB cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.create_db_instance_read_replica)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#create_db_instance_read_replica)
         """
 
     async def create_db_parameter_group(
         self,
@@ -1164,15 +1167,15 @@
         DBProxyName: str,
         TargetGroupName: str = ...,
         DBInstanceIdentifiers: Sequence[str] = ...,
         DBClusterIdentifiers: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
         Remove the association between one or more `DBProxyTarget` data structures and a
-        `DBProxyTargetGroup` .
+        `DBProxyTargetGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.deregister_db_proxy_targets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#deregister_db_proxy_targets)
         """
 
     async def describe_account_attributes(self) -> AccountAttributesMessageTypeDef:
         """
@@ -1312,15 +1315,15 @@
         DBClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         MaxRecords: int = ...,
         Marker: str = ...,
         IncludeShared: bool = ...
     ) -> DBClusterMessageTypeDef:
         """
-        Returns information about Amazon Aurora DB clusters and Multi-AZ DB clusters.
+        Describes existing Amazon Aurora DB clusters and Multi-AZ DB clusters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.describe_db_clusters)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#describe_db_clusters)
         """
 
     async def describe_db_engine_versions(
         self,
@@ -1365,15 +1368,15 @@
         *,
         DBInstanceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         MaxRecords: int = ...,
         Marker: str = ...
     ) -> DBInstanceMessageTypeDef:
         """
-        Returns information about provisioned RDS instances.
+        Describes provisioned RDS instances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.describe_db_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#describe_db_instances)
         """
 
     async def describe_db_log_files(
         self,
@@ -1827,22 +1830,22 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#failover_db_cluster)
         """
 
     async def failover_global_cluster(
         self, *, GlobalClusterIdentifier: str, TargetDbClusterIdentifier: str
     ) -> FailoverGlobalClusterResultTypeDef:
         """
-        Initiates the failover process for an Aurora global database (  GlobalCluster ).
+        Initiates the failover process for an Aurora global database (  GlobalCluster).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.failover_global_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#failover_global_cluster)
         """
 
     async def generate_db_auth_token(
-        self, DBHostname: str, Port: int, DBUsername: str, Region: str = ...
+        self, DBHostname: str, Port: int, DBUsername: str, Region: Optional[str] = ...
     ) -> str:
         """
         Generates an auth token used to connect to a db with IAM credentials.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.generate_db_auth_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#generate_db_auth_token)
         """
@@ -1961,18 +1964,20 @@
         EnablePerformanceInsights: bool = ...,
         PerformanceInsightsKMSKeyId: str = ...,
         PerformanceInsightsRetentionPeriod: int = ...,
         ServerlessV2ScalingConfiguration: ServerlessV2ScalingConfigurationTypeDef = ...,
         NetworkType: str = ...,
         ManageMasterUserPassword: bool = ...,
         RotateMasterUserPassword: bool = ...,
-        MasterUserSecretKmsKeyId: str = ...
+        MasterUserSecretKmsKeyId: str = ...,
+        EngineMode: str = ...,
+        AllowEngineModeChange: bool = ...
     ) -> ModifyDBClusterResultTypeDef:
         """
-        Modify the settings for an Amazon Aurora DB cluster or a Multi-AZ DB cluster.
+        Modifies the settings of an Amazon Aurora DB cluster or a Multi-AZ DB cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.modify_db_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#modify_db_cluster)
         """
 
     async def modify_db_cluster_endpoint(
         self,
@@ -2065,15 +2070,16 @@
         AwsBackupRecoveryPointArn: str = ...,
         AutomationMode: AutomationModeType = ...,
         ResumeFullAutomationModeMinutes: int = ...,
         NetworkType: str = ...,
         StorageThroughput: int = ...,
         ManageMasterUserPassword: bool = ...,
         RotateMasterUserPassword: bool = ...,
-        MasterUserSecretKmsKeyId: str = ...
+        MasterUserSecretKmsKeyId: str = ...,
+        Engine: str = ...
     ) -> ModifyDBInstanceResultTypeDef:
         """
         Modifies settings for a DB instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.modify_db_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#modify_db_instance)
         """
@@ -2126,15 +2132,15 @@
         *,
         TargetGroupName: str,
         DBProxyName: str,
         ConnectionPoolConfig: ConnectionPoolConfigurationTypeDef = ...,
         NewName: str = ...
     ) -> ModifyDBProxyTargetGroupResponseTypeDef:
         """
-        Modifies the properties of a `DBProxyTargetGroup` .
+        Modifies the properties of a `DBProxyTargetGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.modify_db_proxy_target_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#modify_db_proxy_target_group)
         """
 
     async def modify_db_snapshot(
         self, *, DBSnapshotIdentifier: str, EngineVersion: str = ..., OptionGroupName: str = ...
@@ -2286,15 +2292,15 @@
         DBProxyName: str,
         TargetGroupName: str = ...,
         DBInstanceIdentifiers: Sequence[str] = ...,
         DBClusterIdentifiers: Sequence[str] = ...
     ) -> RegisterDBProxyTargetsResponseTypeDef:
         """
         Associate one or more `DBProxyTarget` data structures with a
-        `DBProxyTargetGroup` .
+        `DBProxyTargetGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.register_db_proxy_targets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#register_db_proxy_targets)
         """
 
     async def remove_from_global_cluster(
         self, *, GlobalClusterIdentifier: str = ..., DbClusterIdentifier: str = ...
@@ -2411,15 +2417,16 @@
         DeletionProtection: bool = ...,
         CopyTagsToSnapshot: bool = ...,
         Domain: str = ...,
         DomainIAMRoleName: str = ...,
         ServerlessV2ScalingConfiguration: ServerlessV2ScalingConfigurationTypeDef = ...,
         NetworkType: str = ...,
         ManageMasterUserPassword: bool = ...,
-        MasterUserSecretKmsKeyId: str = ...
+        MasterUserSecretKmsKeyId: str = ...,
+        StorageType: str = ...
     ) -> RestoreDBClusterFromS3ResultTypeDef:
         """
         Creates an Amazon Aurora DB cluster from MySQL data stored in an Amazon S3
         bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.restore_db_cluster_from_s3)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#restore_db_cluster_from_s3)
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/client.pyi` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -12,15 +12,15 @@
     session = get_session()
     async with session.create_client("rds") as client:
         client: RDSClient
     ```
 """
 import sys
 from datetime import datetime
-from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
+from typing import Any, Dict, Mapping, Optional, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     ActivityStreamModeType,
     AuditPolicyStateType,
@@ -235,14 +235,15 @@
     AuthorizationNotFoundFault: Type[BotocoreClientError]
     AuthorizationQuotaExceededFault: Type[BotocoreClientError]
     BackupPolicyNotFoundFault: Type[BotocoreClientError]
     BlueGreenDeploymentAlreadyExistsFault: Type[BotocoreClientError]
     BlueGreenDeploymentNotFoundFault: Type[BotocoreClientError]
     CertificateNotFoundFault: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    CreateCustomDBEngineVersionFault: Type[BotocoreClientError]
     CustomAvailabilityZoneNotFoundFault: Type[BotocoreClientError]
     CustomDBEngineVersionAlreadyExistsFault: Type[BotocoreClientError]
     CustomDBEngineVersionNotFoundFault: Type[BotocoreClientError]
     CustomDBEngineVersionQuotaExceededFault: Type[BotocoreClientError]
     DBClusterAlreadyExistsFault: Type[BotocoreClientError]
     DBClusterBacktrackNotFoundFault: Type[BotocoreClientError]
     DBClusterEndpointAlreadyExistsFault: Type[BotocoreClientError]
@@ -347,14 +348,15 @@
     SNSTopicArnNotFoundFault: Type[BotocoreClientError]
     SharedSnapshotQuotaExceededFault: Type[BotocoreClientError]
     SnapshotQuotaExceededFault: Type[BotocoreClientError]
     SourceClusterNotSupportedFault: Type[BotocoreClientError]
     SourceDatabaseNotSupportedFault: Type[BotocoreClientError]
     SourceNotFoundFault: Type[BotocoreClientError]
     StorageQuotaExceededFault: Type[BotocoreClientError]
+    StorageTypeNotAvailableFault: Type[BotocoreClientError]
     StorageTypeNotSupportedFault: Type[BotocoreClientError]
     SubnetAlreadyInUse: Type[BotocoreClientError]
     SubscriptionAlreadyExistFault: Type[BotocoreClientError]
     SubscriptionCategoryNotFoundFault: Type[BotocoreClientError]
     SubscriptionNotFoundFault: Type[BotocoreClientError]
 
 class RDSClient(AioBaseClient):
@@ -756,15 +758,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.create_db_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#create_db_instance)
         """
     async def create_db_instance_read_replica(
         self,
         *,
         DBInstanceIdentifier: str,
-        SourceDBInstanceIdentifier: str,
+        SourceDBInstanceIdentifier: str = ...,
         DBInstanceClass: str = ...,
         AvailabilityZone: str = ...,
         Port: int = ...,
         MultiAZ: bool = ...,
         AutoMinorVersionUpgrade: bool = ...,
         Iops: int = ...,
         OptionGroupName: str = ...,
@@ -792,19 +794,20 @@
         ReplicaMode: ReplicaModeType = ...,
         MaxAllocatedStorage: int = ...,
         CustomIamInstanceProfile: str = ...,
         NetworkType: str = ...,
         StorageThroughput: int = ...,
         EnableCustomerOwnedIp: bool = ...,
         AllocatedStorage: int = ...,
+        SourceDBClusterIdentifier: str = ...,
         SourceRegion: str = ...
     ) -> CreateDBInstanceReadReplicaResultTypeDef:
         """
         Creates a new DB instance that acts as a read replica for an existing source DB
-        instance.
+        instance or Multi-AZ DB cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.create_db_instance_read_replica)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#create_db_instance_read_replica)
         """
     async def create_db_parameter_group(
         self,
         *,
@@ -1110,15 +1113,15 @@
         DBProxyName: str,
         TargetGroupName: str = ...,
         DBInstanceIdentifiers: Sequence[str] = ...,
         DBClusterIdentifiers: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
         Remove the association between one or more `DBProxyTarget` data structures and a
-        `DBProxyTargetGroup` .
+        `DBProxyTargetGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.deregister_db_proxy_targets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#deregister_db_proxy_targets)
         """
     async def describe_account_attributes(self) -> AccountAttributesMessageTypeDef:
         """
         Lists all of the attributes for a customer account.
@@ -1248,15 +1251,15 @@
         DBClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         MaxRecords: int = ...,
         Marker: str = ...,
         IncludeShared: bool = ...
     ) -> DBClusterMessageTypeDef:
         """
-        Returns information about Amazon Aurora DB clusters and Multi-AZ DB clusters.
+        Describes existing Amazon Aurora DB clusters and Multi-AZ DB clusters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.describe_db_clusters)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#describe_db_clusters)
         """
     async def describe_db_engine_versions(
         self,
         *,
@@ -1298,15 +1301,15 @@
         *,
         DBInstanceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         MaxRecords: int = ...,
         Marker: str = ...
     ) -> DBInstanceMessageTypeDef:
         """
-        Returns information about provisioned RDS instances.
+        Describes provisioned RDS instances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.describe_db_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#describe_db_instances)
         """
     async def describe_db_log_files(
         self,
         *,
@@ -1731,21 +1734,21 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.failover_db_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#failover_db_cluster)
         """
     async def failover_global_cluster(
         self, *, GlobalClusterIdentifier: str, TargetDbClusterIdentifier: str
     ) -> FailoverGlobalClusterResultTypeDef:
         """
-        Initiates the failover process for an Aurora global database (  GlobalCluster ).
+        Initiates the failover process for an Aurora global database (  GlobalCluster).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.failover_global_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#failover_global_cluster)
         """
     async def generate_db_auth_token(
-        self, DBHostname: str, Port: int, DBUsername: str, Region: str = ...
+        self, DBHostname: str, Port: int, DBUsername: str, Region: Optional[str] = ...
     ) -> str:
         """
         Generates an auth token used to connect to a db with IAM credentials.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.generate_db_auth_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#generate_db_auth_token)
         """
@@ -1857,18 +1860,20 @@
         EnablePerformanceInsights: bool = ...,
         PerformanceInsightsKMSKeyId: str = ...,
         PerformanceInsightsRetentionPeriod: int = ...,
         ServerlessV2ScalingConfiguration: ServerlessV2ScalingConfigurationTypeDef = ...,
         NetworkType: str = ...,
         ManageMasterUserPassword: bool = ...,
         RotateMasterUserPassword: bool = ...,
-        MasterUserSecretKmsKeyId: str = ...
+        MasterUserSecretKmsKeyId: str = ...,
+        EngineMode: str = ...,
+        AllowEngineModeChange: bool = ...
     ) -> ModifyDBClusterResultTypeDef:
         """
-        Modify the settings for an Amazon Aurora DB cluster or a Multi-AZ DB cluster.
+        Modifies the settings of an Amazon Aurora DB cluster or a Multi-AZ DB cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.modify_db_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#modify_db_cluster)
         """
     async def modify_db_cluster_endpoint(
         self,
         *,
@@ -1957,15 +1962,16 @@
         AwsBackupRecoveryPointArn: str = ...,
         AutomationMode: AutomationModeType = ...,
         ResumeFullAutomationModeMinutes: int = ...,
         NetworkType: str = ...,
         StorageThroughput: int = ...,
         ManageMasterUserPassword: bool = ...,
         RotateMasterUserPassword: bool = ...,
-        MasterUserSecretKmsKeyId: str = ...
+        MasterUserSecretKmsKeyId: str = ...,
+        Engine: str = ...
     ) -> ModifyDBInstanceResultTypeDef:
         """
         Modifies settings for a DB instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.modify_db_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#modify_db_instance)
         """
@@ -2014,15 +2020,15 @@
         *,
         TargetGroupName: str,
         DBProxyName: str,
         ConnectionPoolConfig: ConnectionPoolConfigurationTypeDef = ...,
         NewName: str = ...
     ) -> ModifyDBProxyTargetGroupResponseTypeDef:
         """
-        Modifies the properties of a `DBProxyTargetGroup` .
+        Modifies the properties of a `DBProxyTargetGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.modify_db_proxy_target_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#modify_db_proxy_target_group)
         """
     async def modify_db_snapshot(
         self, *, DBSnapshotIdentifier: str, EngineVersion: str = ..., OptionGroupName: str = ...
     ) -> ModifyDBSnapshotResultTypeDef:
@@ -2162,15 +2168,15 @@
         DBProxyName: str,
         TargetGroupName: str = ...,
         DBInstanceIdentifiers: Sequence[str] = ...,
         DBClusterIdentifiers: Sequence[str] = ...
     ) -> RegisterDBProxyTargetsResponseTypeDef:
         """
         Associate one or more `DBProxyTarget` data structures with a
-        `DBProxyTargetGroup` .
+        `DBProxyTargetGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.register_db_proxy_targets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#register_db_proxy_targets)
         """
     async def remove_from_global_cluster(
         self, *, GlobalClusterIdentifier: str = ..., DbClusterIdentifier: str = ...
     ) -> RemoveFromGlobalClusterResultTypeDef:
@@ -2279,15 +2285,16 @@
         DeletionProtection: bool = ...,
         CopyTagsToSnapshot: bool = ...,
         Domain: str = ...,
         DomainIAMRoleName: str = ...,
         ServerlessV2ScalingConfiguration: ServerlessV2ScalingConfigurationTypeDef = ...,
         NetworkType: str = ...,
         ManageMasterUserPassword: bool = ...,
-        MasterUserSecretKmsKeyId: str = ...
+        MasterUserSecretKmsKeyId: str = ...,
+        StorageType: str = ...
     ) -> RestoreDBClusterFromS3ResultTypeDef:
         """
         Creates an Amazon Aurora DB cluster from MySQL data stored in an Amazon S3
         bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Client.restore_db_cluster_from_s3)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/client/#restore_db_cluster_from_s3)
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/literals.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -261,14 +261,15 @@
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
@@ -347,14 +348,15 @@
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
@@ -365,14 +367,15 @@
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
@@ -408,14 +411,15 @@
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
@@ -434,16 +438,19 @@
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
@@ -527,15 +534,17 @@
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/literals.pyi` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -259,14 +259,15 @@
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
@@ -345,14 +346,15 @@
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
@@ -363,14 +365,15 @@
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
@@ -406,14 +409,15 @@
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
@@ -432,16 +436,19 @@
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
@@ -525,15 +532,17 @@
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/paginator.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -84,17 +84,16 @@
         describe_pending_maintenance_actions_paginator: DescribePendingMaintenanceActionsPaginator = client.get_paginator("describe_pending_maintenance_actions")
         describe_reserved_db_instances_paginator: DescribeReservedDBInstancesPaginator = client.get_paginator("describe_reserved_db_instances")
         describe_reserved_db_instances_offerings_paginator: DescribeReservedDBInstancesOfferingsPaginator = client.get_paginator("describe_reserved_db_instances_offerings")
         describe_source_regions_paginator: DescribeSourceRegionsPaginator = client.get_paginator("describe_source_regions")
         download_db_log_file_portion_paginator: DownloadDBLogFilePortionPaginator = client.get_paginator("download_db_log_file_portion")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ExportSourceTypeType, SourceTypeType
 from .type_defs import (
     CertificateMessageTypeDef,
@@ -132,20 +131,14 @@
     PaginatorConfigTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
     ReservedDBInstanceMessageTypeDef,
     ReservedDBInstancesOfferingMessageTypeDef,
     SourceRegionMessageTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeBlueGreenDeploymentsPaginator",
     "DescribeCertificatesPaginator",
     "DescribeDBClusterBacktracksPaginator",
     "DescribeDBClusterEndpointsPaginator",
     "DescribeDBClusterParameterGroupsPaginator",
     "DescribeDBClusterParametersPaginator",
@@ -198,15 +191,15 @@
     """
 
     def paginate(
         self,
         *,
         BlueGreenDeploymentIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBlueGreenDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeBlueGreenDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describebluegreendeploymentspaginator)
         """
 
 
@@ -217,15 +210,15 @@
     """
 
     def paginate(
         self,
         *,
         CertificateIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CertificateMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describecertificatespaginator)
         """
 
 
@@ -237,15 +230,15 @@
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str,
         BacktrackIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterBacktrackMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterBacktracks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterbacktrackspaginator)
         """
 
 
@@ -257,15 +250,15 @@
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str = ...,
         DBClusterEndpointIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterEndpointMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterendpointspaginator)
         """
 
 
@@ -276,15 +269,15 @@
     """
 
     def paginate(
         self,
         *,
         DBClusterParameterGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterParameterGroupsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterparametergroupspaginator)
         """
 
 
@@ -296,15 +289,15 @@
 
     def paginate(
         self,
         *,
         DBClusterParameterGroupName: str,
         Source: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterParameterGroupDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterparameterspaginator)
         """
 
 
@@ -319,15 +312,15 @@
         *,
         DBClusterIdentifier: str = ...,
         DBClusterSnapshotIdentifier: str = ...,
         SnapshotType: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         IncludeShared: bool = ...,
         IncludePublic: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterSnapshotMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclustersnapshotspaginator)
         """
 
 
@@ -339,15 +332,15 @@
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         IncludeShared: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterspaginator)
         """
 
 
@@ -364,15 +357,15 @@
         EngineVersion: str = ...,
         DBParameterGroupFamily: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         DefaultOnly: bool = ...,
         ListSupportedCharacterSets: bool = ...,
         ListSupportedTimezones: bool = ...,
         IncludeAll: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBEngineVersionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbengineversionspaginator)
         """
 
 
@@ -385,15 +378,15 @@
     def paginate(
         self,
         *,
         DbiResourceId: str = ...,
         DBInstanceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         DBInstanceAutomatedBackupsArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBInstanceAutomatedBackupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBInstanceAutomatedBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbinstanceautomatedbackupspaginator)
         """
 
 
@@ -404,15 +397,15 @@
     """
 
     def paginate(
         self,
         *,
         DBInstanceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBInstanceMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbinstancespaginator)
         """
 
 
@@ -426,15 +419,15 @@
         self,
         *,
         DBInstanceIdentifier: str,
         FilenameContains: str = ...,
         FileLastWritten: int = ...,
         FileSize: int = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBLogFilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBLogFiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedblogfilespaginator)
         """
 
 
@@ -445,15 +438,15 @@
     """
 
     def paginate(
         self,
         *,
         DBParameterGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBParameterGroupsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbparametergroupspaginator)
         """
 
 
@@ -465,15 +458,15 @@
 
     def paginate(
         self,
         *,
         DBParameterGroupName: str,
         Source: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBParameterGroupDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbparameterspaginator)
         """
 
 
@@ -484,15 +477,15 @@
     """
 
     def paginate(
         self,
         *,
         DBProxyName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxiespaginator)
         """
 
 
@@ -504,15 +497,15 @@
 
     def paginate(
         self,
         *,
         DBProxyName: str = ...,
         DBProxyEndpointName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxyEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxyendpointspaginator)
         """
 
 
@@ -524,15 +517,15 @@
 
     def paginate(
         self,
         *,
         DBProxyName: str,
         TargetGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxyTargetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyTargetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxytargetgroupspaginator)
         """
 
 
@@ -544,15 +537,15 @@
 
     def paginate(
         self,
         *,
         DBProxyName: str,
         TargetGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxyTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxytargetspaginator)
         """
 
 
@@ -563,15 +556,15 @@
     """
 
     def paginate(
         self,
         *,
         DBSecurityGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBSecurityGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSecurityGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbsecuritygroupspaginator)
         """
 
 
@@ -587,15 +580,15 @@
         DBInstanceIdentifier: str = ...,
         DBSnapshotIdentifier: str = ...,
         SnapshotType: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         IncludeShared: bool = ...,
         IncludePublic: bool = ...,
         DbiResourceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBSnapshotMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbsnapshotspaginator)
         """
 
 
@@ -606,15 +599,15 @@
     """
 
     def paginate(
         self,
         *,
         DBSubnetGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBSubnetGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbsubnetgroupspaginator)
         """
 
 
@@ -625,15 +618,15 @@
     """
 
     def paginate(
         self,
         *,
         DBParameterGroupFamily: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineDefaultClusterParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEngineDefaultClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeenginedefaultclusterparameterspaginator)
         """
 
 
@@ -644,15 +637,15 @@
     """
 
     def paginate(
         self,
         *,
         DBParameterGroupFamily: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineDefaultParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEngineDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeenginedefaultparameterspaginator)
         """
 
 
@@ -663,15 +656,15 @@
     """
 
     def paginate(
         self,
         *,
         SubscriptionName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventSubscriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeeventsubscriptionspaginator)
         """
 
 
@@ -687,15 +680,15 @@
         SourceIdentifier: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
         EventCategories: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeeventspaginator)
         """
 
 
@@ -708,15 +701,15 @@
     def paginate(
         self,
         *,
         ExportTaskIdentifier: str = ...,
         SourceArn: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         SourceType: ExportSourceTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportTasksMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeExportTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeexporttaskspaginator)
         """
 
 
@@ -727,15 +720,15 @@
     """
 
     def paginate(
         self,
         *,
         GlobalClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GlobalClustersMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeGlobalClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeglobalclusterspaginator)
         """
 
 
@@ -747,15 +740,15 @@
 
     def paginate(
         self,
         *,
         EngineName: str,
         MajorEngineVersion: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OptionGroupOptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOptionGroupOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeoptiongroupoptionspaginator)
         """
 
 
@@ -768,15 +761,15 @@
     def paginate(
         self,
         *,
         OptionGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         EngineName: str = ...,
         MajorEngineVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OptionGroupsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOptionGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeoptiongroupspaginator)
         """
 
 
@@ -792,15 +785,15 @@
         Engine: str,
         EngineVersion: str = ...,
         DBInstanceClass: str = ...,
         LicenseModel: str = ...,
         AvailabilityZoneGroup: str = ...,
         Vpc: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OrderableDBInstanceOptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOrderableDBInstanceOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeorderabledbinstanceoptionspaginator)
         """
 
 
@@ -811,15 +804,15 @@
     """
 
     def paginate(
         self,
         *,
         ResourceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[PendingMaintenanceActionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribePendingMaintenanceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describependingmaintenanceactionspaginator)
         """
 
 
@@ -837,15 +830,15 @@
         DBInstanceClass: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
         MultiAZ: bool = ...,
         LeaseId: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedDBInstanceMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeReservedDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describereserveddbinstancespaginator)
         """
 
 
@@ -861,15 +854,15 @@
         ReservedDBInstancesOfferingId: str = ...,
         DBInstanceClass: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
         MultiAZ: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedDBInstancesOfferingMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeReservedDBInstancesOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describereserveddbinstancesofferingspaginator)
         """
 
 
@@ -880,15 +873,15 @@
     """
 
     def paginate(
         self,
         *,
         RegionName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SourceRegionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeSourceRegions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describesourceregionspaginator)
         """
 
 
@@ -899,13 +892,13 @@
     """
 
     def paginate(
         self,
         *,
         DBInstanceIdentifier: str,
         LogFileName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DownloadDBLogFilePortionDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DownloadDBLogFilePortion.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#downloaddblogfileportionpaginator)
         """
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/paginator.pyi` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -84,17 +84,16 @@
         describe_pending_maintenance_actions_paginator: DescribePendingMaintenanceActionsPaginator = client.get_paginator("describe_pending_maintenance_actions")
         describe_reserved_db_instances_paginator: DescribeReservedDBInstancesPaginator = client.get_paginator("describe_reserved_db_instances")
         describe_reserved_db_instances_offerings_paginator: DescribeReservedDBInstancesOfferingsPaginator = client.get_paginator("describe_reserved_db_instances_offerings")
         describe_source_regions_paginator: DescribeSourceRegionsPaginator = client.get_paginator("describe_source_regions")
         download_db_log_file_portion_paginator: DownloadDBLogFilePortionPaginator = client.get_paginator("download_db_log_file_portion")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ExportSourceTypeType, SourceTypeType
 from .type_defs import (
     CertificateMessageTypeDef,
@@ -132,19 +131,14 @@
     PaginatorConfigTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
     ReservedDBInstanceMessageTypeDef,
     ReservedDBInstancesOfferingMessageTypeDef,
     SourceRegionMessageTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeBlueGreenDeploymentsPaginator",
     "DescribeCertificatesPaginator",
     "DescribeDBClusterBacktracksPaginator",
     "DescribeDBClusterEndpointsPaginator",
     "DescribeDBClusterParameterGroupsPaginator",
     "DescribeDBClusterParametersPaginator",
@@ -194,15 +188,15 @@
     """
 
     def paginate(
         self,
         *,
         BlueGreenDeploymentIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBlueGreenDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeBlueGreenDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describebluegreendeploymentspaginator)
         """
 
 class DescribeCertificatesPaginator(AioPaginator):
@@ -212,15 +206,15 @@
     """
 
     def paginate(
         self,
         *,
         CertificateIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CertificateMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describecertificatespaginator)
         """
 
 class DescribeDBClusterBacktracksPaginator(AioPaginator):
@@ -231,15 +225,15 @@
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str,
         BacktrackIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterBacktrackMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterBacktracks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterbacktrackspaginator)
         """
 
 class DescribeDBClusterEndpointsPaginator(AioPaginator):
@@ -250,15 +244,15 @@
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str = ...,
         DBClusterEndpointIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterEndpointMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterendpointspaginator)
         """
 
 class DescribeDBClusterParameterGroupsPaginator(AioPaginator):
@@ -268,15 +262,15 @@
     """
 
     def paginate(
         self,
         *,
         DBClusterParameterGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterParameterGroupsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterparametergroupspaginator)
         """
 
 class DescribeDBClusterParametersPaginator(AioPaginator):
@@ -287,15 +281,15 @@
 
     def paginate(
         self,
         *,
         DBClusterParameterGroupName: str,
         Source: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterParameterGroupDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterparameterspaginator)
         """
 
 class DescribeDBClusterSnapshotsPaginator(AioPaginator):
@@ -309,15 +303,15 @@
         *,
         DBClusterIdentifier: str = ...,
         DBClusterSnapshotIdentifier: str = ...,
         SnapshotType: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         IncludeShared: bool = ...,
         IncludePublic: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterSnapshotMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclustersnapshotspaginator)
         """
 
 class DescribeDBClustersPaginator(AioPaginator):
@@ -328,15 +322,15 @@
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         IncludeShared: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbclusterspaginator)
         """
 
 class DescribeDBEngineVersionsPaginator(AioPaginator):
@@ -352,15 +346,15 @@
         EngineVersion: str = ...,
         DBParameterGroupFamily: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         DefaultOnly: bool = ...,
         ListSupportedCharacterSets: bool = ...,
         ListSupportedTimezones: bool = ...,
         IncludeAll: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBEngineVersionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbengineversionspaginator)
         """
 
 class DescribeDBInstanceAutomatedBackupsPaginator(AioPaginator):
@@ -372,15 +366,15 @@
     def paginate(
         self,
         *,
         DbiResourceId: str = ...,
         DBInstanceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         DBInstanceAutomatedBackupsArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBInstanceAutomatedBackupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBInstanceAutomatedBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbinstanceautomatedbackupspaginator)
         """
 
 class DescribeDBInstancesPaginator(AioPaginator):
@@ -390,15 +384,15 @@
     """
 
     def paginate(
         self,
         *,
         DBInstanceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBInstanceMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbinstancespaginator)
         """
 
 class DescribeDBLogFilesPaginator(AioPaginator):
@@ -411,15 +405,15 @@
         self,
         *,
         DBInstanceIdentifier: str,
         FilenameContains: str = ...,
         FileLastWritten: int = ...,
         FileSize: int = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBLogFilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBLogFiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedblogfilespaginator)
         """
 
 class DescribeDBParameterGroupsPaginator(AioPaginator):
@@ -429,15 +423,15 @@
     """
 
     def paginate(
         self,
         *,
         DBParameterGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBParameterGroupsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbparametergroupspaginator)
         """
 
 class DescribeDBParametersPaginator(AioPaginator):
@@ -448,15 +442,15 @@
 
     def paginate(
         self,
         *,
         DBParameterGroupName: str,
         Source: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBParameterGroupDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbparameterspaginator)
         """
 
 class DescribeDBProxiesPaginator(AioPaginator):
@@ -466,15 +460,15 @@
     """
 
     def paginate(
         self,
         *,
         DBProxyName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxiespaginator)
         """
 
 class DescribeDBProxyEndpointsPaginator(AioPaginator):
@@ -485,15 +479,15 @@
 
     def paginate(
         self,
         *,
         DBProxyName: str = ...,
         DBProxyEndpointName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxyEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxyendpointspaginator)
         """
 
 class DescribeDBProxyTargetGroupsPaginator(AioPaginator):
@@ -504,15 +498,15 @@
 
     def paginate(
         self,
         *,
         DBProxyName: str,
         TargetGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxyTargetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyTargetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxytargetgroupspaginator)
         """
 
 class DescribeDBProxyTargetsPaginator(AioPaginator):
@@ -523,15 +517,15 @@
 
     def paginate(
         self,
         *,
         DBProxyName: str,
         TargetGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDBProxyTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBProxyTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbproxytargetspaginator)
         """
 
 class DescribeDBSecurityGroupsPaginator(AioPaginator):
@@ -541,15 +535,15 @@
     """
 
     def paginate(
         self,
         *,
         DBSecurityGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBSecurityGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSecurityGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbsecuritygroupspaginator)
         """
 
 class DescribeDBSnapshotsPaginator(AioPaginator):
@@ -564,15 +558,15 @@
         DBInstanceIdentifier: str = ...,
         DBSnapshotIdentifier: str = ...,
         SnapshotType: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         IncludeShared: bool = ...,
         IncludePublic: bool = ...,
         DbiResourceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBSnapshotMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbsnapshotspaginator)
         """
 
 class DescribeDBSubnetGroupsPaginator(AioPaginator):
@@ -582,15 +576,15 @@
     """
 
     def paginate(
         self,
         *,
         DBSubnetGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBSubnetGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeDBSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describedbsubnetgroupspaginator)
         """
 
 class DescribeEngineDefaultClusterParametersPaginator(AioPaginator):
@@ -600,15 +594,15 @@
     """
 
     def paginate(
         self,
         *,
         DBParameterGroupFamily: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineDefaultClusterParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEngineDefaultClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeenginedefaultclusterparameterspaginator)
         """
 
 class DescribeEngineDefaultParametersPaginator(AioPaginator):
@@ -618,15 +612,15 @@
     """
 
     def paginate(
         self,
         *,
         DBParameterGroupFamily: str,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineDefaultParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEngineDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeenginedefaultparameterspaginator)
         """
 
 class DescribeEventSubscriptionsPaginator(AioPaginator):
@@ -636,15 +630,15 @@
     """
 
     def paginate(
         self,
         *,
         SubscriptionName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventSubscriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeeventsubscriptionspaginator)
         """
 
 class DescribeEventsPaginator(AioPaginator):
@@ -659,15 +653,15 @@
         SourceIdentifier: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
         EventCategories: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeeventspaginator)
         """
 
 class DescribeExportTasksPaginator(AioPaginator):
@@ -679,15 +673,15 @@
     def paginate(
         self,
         *,
         ExportTaskIdentifier: str = ...,
         SourceArn: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         SourceType: ExportSourceTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportTasksMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeExportTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeexporttaskspaginator)
         """
 
 class DescribeGlobalClustersPaginator(AioPaginator):
@@ -697,15 +691,15 @@
     """
 
     def paginate(
         self,
         *,
         GlobalClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GlobalClustersMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeGlobalClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeglobalclusterspaginator)
         """
 
 class DescribeOptionGroupOptionsPaginator(AioPaginator):
@@ -716,15 +710,15 @@
 
     def paginate(
         self,
         *,
         EngineName: str,
         MajorEngineVersion: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OptionGroupOptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOptionGroupOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeoptiongroupoptionspaginator)
         """
 
 class DescribeOptionGroupsPaginator(AioPaginator):
@@ -736,15 +730,15 @@
     def paginate(
         self,
         *,
         OptionGroupName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         EngineName: str = ...,
         MajorEngineVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OptionGroupsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOptionGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeoptiongroupspaginator)
         """
 
 class DescribeOrderableDBInstanceOptionsPaginator(AioPaginator):
@@ -759,15 +753,15 @@
         Engine: str,
         EngineVersion: str = ...,
         DBInstanceClass: str = ...,
         LicenseModel: str = ...,
         AvailabilityZoneGroup: str = ...,
         Vpc: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OrderableDBInstanceOptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeOrderableDBInstanceOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describeorderabledbinstanceoptionspaginator)
         """
 
 class DescribePendingMaintenanceActionsPaginator(AioPaginator):
@@ -777,15 +771,15 @@
     """
 
     def paginate(
         self,
         *,
         ResourceIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[PendingMaintenanceActionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribePendingMaintenanceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describependingmaintenanceactionspaginator)
         """
 
 class DescribeReservedDBInstancesPaginator(AioPaginator):
@@ -802,15 +796,15 @@
         DBInstanceClass: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
         MultiAZ: bool = ...,
         LeaseId: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedDBInstanceMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeReservedDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describereserveddbinstancespaginator)
         """
 
 class DescribeReservedDBInstancesOfferingsPaginator(AioPaginator):
@@ -825,15 +819,15 @@
         ReservedDBInstancesOfferingId: str = ...,
         DBInstanceClass: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
         MultiAZ: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedDBInstancesOfferingMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeReservedDBInstancesOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describereserveddbinstancesofferingspaginator)
         """
 
 class DescribeSourceRegionsPaginator(AioPaginator):
@@ -843,15 +837,15 @@
     """
 
     def paginate(
         self,
         *,
         RegionName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SourceRegionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DescribeSourceRegions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#describesourceregionspaginator)
         """
 
 class DownloadDBLogFilePortionPaginator(AioPaginator):
@@ -861,13 +855,13 @@
     """
 
     def paginate(
         self,
         *,
         DBInstanceIdentifier: str,
         LogFileName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DownloadDBLogFilePortionDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS.Paginator.DownloadDBLogFilePortion.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/paginators/#downloaddblogfileportionpaginator)
         """
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/type_defs.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_rds.type_defs import AccountQuotaTypeDef
 
     data: AccountQuotaTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Sequence, Union
+from typing import Dict, List, Optional, Sequence, Union
 
 from .literals import (
     ActivityStreamModeType,
     ActivityStreamPolicyStatusType,
     ActivityStreamStatusType,
     ApplyMethodType,
     AuditPolicyStateType,
@@ -45,18 +45,16 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AccountQuotaTypeDef",
-    "ResponseMetadataTypeDef",
     "AddRoleToDBClusterMessageRequestTypeDef",
     "AddRoleToDBInstanceMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionMessageRequestTypeDef",
     "EventSubscriptionTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
     "AuthorizeDBSecurityGroupIngressMessageRequestTypeDef",
@@ -80,18 +78,22 @@
     "ServerlessV2ScalingConfigurationTypeDef",
     "ProcessorFeatureTypeDef",
     "DBProxyEndpointTypeDef",
     "UserAuthConfigTypeDef",
     "CreateGlobalClusterMessageRequestTypeDef",
     "CustomDBEngineVersionAMITypeDef",
     "DBClusterBacktrackTypeDef",
+    "DBClusterBacktrackResponseMetadataTypeDef",
+    "DBClusterCapacityInfoTypeDef",
     "DBClusterEndpointTypeDef",
+    "DBClusterEndpointResponseMetadataTypeDef",
     "DBClusterMemberTypeDef",
     "DBClusterOptionGroupStatusTypeDef",
     "ParameterTypeDef",
+    "DBClusterParameterGroupNameMessageTypeDef",
     "DBClusterRoleTypeDef",
     "DBClusterSnapshotAttributeTypeDef",
     "DomainMembershipTypeDef",
     "MasterUserSecretTypeDef",
     "ScalingConfigurationInfoTypeDef",
     "ServerlessV2ScalingConfigurationInfoTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
@@ -101,14 +103,15 @@
     "RestoreWindowTypeDef",
     "DBInstanceRoleTypeDef",
     "DBInstanceStatusInfoTypeDef",
     "DBParameterGroupStatusTypeDef",
     "DBSecurityGroupMembershipTypeDef",
     "EndpointTypeDef",
     "OptionGroupMembershipTypeDef",
+    "DBParameterGroupNameMessageTypeDef",
     "TargetHealthTypeDef",
     "UserAuthConfigInfoTypeDef",
     "EC2SecurityGroupTypeDef",
     "IPRangeTypeDef",
     "DBSnapshotAttributeTypeDef",
     "DeleteBlueGreenDeploymentRequestRequestTypeDef",
     "DeleteCustomDBEngineVersionMessageRequestTypeDef",
@@ -125,83 +128,80 @@
     "DeleteDBSnapshotMessageRequestTypeDef",
     "DeleteDBSubnetGroupMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteGlobalClusterMessageRequestTypeDef",
     "DeleteOptionGroupMessageRequestTypeDef",
     "DeregisterDBProxyTargetsRequestRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeDBLogFilesDetailsTypeDef",
     "DescribeDBSnapshotAttributesMessageRequestTypeDef",
     "DescribeValidDBInstanceModificationsMessageRequestTypeDef",
     "DoubleRangeTypeDef",
+    "DownloadDBLogFilePortionDetailsTypeDef",
+    "DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
     "DownloadDBLogFilePortionMessageRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventCategoriesMapTypeDef",
     "EventTypeDef",
+    "ExportTaskResponseMetadataTypeDef",
     "ExportTaskTypeDef",
     "FailoverDBClusterMessageRequestTypeDef",
     "FailoverGlobalClusterMessageRequestTypeDef",
     "FailoverStateTypeDef",
     "GlobalClusterMemberTypeDef",
     "MinimumEngineVersionPerAllowedValueTypeDef",
     "ModifyActivityStreamRequestRequestTypeDef",
+    "ModifyActivityStreamResponseTypeDef",
     "ModifyCertificatesMessageRequestTypeDef",
     "ModifyCurrentDBClusterCapacityMessageRequestTypeDef",
     "ModifyCustomDBEngineVersionMessageRequestTypeDef",
     "ModifyDBClusterEndpointMessageRequestTypeDef",
     "ModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBProxyEndpointRequestRequestTypeDef",
     "ModifyDBSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBSnapshotMessageRequestTypeDef",
     "ModifyDBSubnetGroupMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyGlobalClusterMessageRequestTypeDef",
     "OptionSettingTypeDef",
     "OptionVersionTypeDef",
     "OutpostTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
     "PromoteReadReplicaDBClusterMessageRequestTypeDef",
     "PromoteReadReplicaMessageRequestTypeDef",
     "RangeTypeDef",
     "RebootDBClusterMessageRequestTypeDef",
     "RebootDBInstanceMessageRequestTypeDef",
     "RecurringChargeTypeDef",
     "RegisterDBProxyTargetsRequestRequestTypeDef",
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     "RemoveRoleFromDBClusterMessageRequestTypeDef",
     "RemoveRoleFromDBInstanceMessageRequestTypeDef",
     "RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeDBSecurityGroupIngressMessageRequestTypeDef",
     "SourceRegionTypeDef",
     "StartActivityStreamRequestRequestTypeDef",
+    "StartActivityStreamResponseTypeDef",
     "StartDBClusterMessageRequestTypeDef",
     "StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef",
     "StartDBInstanceMessageRequestTypeDef",
     "StartExportTaskMessageRequestTypeDef",
     "StopActivityStreamRequestRequestTypeDef",
+    "StopActivityStreamResponseTypeDef",
     "StopDBClusterMessageRequestTypeDef",
     "StopDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef",
     "StopDBInstanceMessageRequestTypeDef",
     "SwitchoverBlueGreenDeploymentRequestRequestTypeDef",
     "SwitchoverReadReplicaMessageRequestTypeDef",
     "AccountAttributesMessageTypeDef",
-    "DBClusterBacktrackResponseMetadataTypeDef",
-    "DBClusterCapacityInfoTypeDef",
-    "DBClusterEndpointResponseMetadataTypeDef",
-    "DBClusterParameterGroupNameMessageTypeDef",
-    "DBParameterGroupNameMessageTypeDef",
-    "DownloadDBLogFilePortionDetailsTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportTaskResponseMetadataTypeDef",
-    "ModifyActivityStreamResponseTypeDef",
-    "StartActivityStreamResponseTypeDef",
-    "StopActivityStreamResponseTypeDef",
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     "CreateEventSubscriptionResultTypeDef",
     "DeleteEventSubscriptionResultTypeDef",
     "EventSubscriptionsMessageTypeDef",
     "ModifyEventSubscriptionResultTypeDef",
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
@@ -270,85 +270,84 @@
     "DBEngineVersionResponseMetadataTypeDef",
     "DBEngineVersionTypeDef",
     "DBInstanceAutomatedBackupTypeDef",
     "DBProxyTargetTypeDef",
     "DBProxyTypeDef",
     "DBSecurityGroupTypeDef",
     "DBSnapshotAttributesResultTypeDef",
+    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
     "DescribeBlueGreenDeploymentsRequestRequestTypeDef",
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
     "DescribeCertificatesMessageRequestTypeDef",
+    "DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
     "DescribeDBClusterBacktracksMessageRequestTypeDef",
+    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
     "DescribeDBClusterEndpointsMessageRequestTypeDef",
+    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
     "DescribeDBClusterParameterGroupsMessageRequestTypeDef",
+    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
     "DescribeDBClusterParametersMessageRequestTypeDef",
+    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
     "DescribeDBClusterSnapshotsMessageRequestTypeDef",
+    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
     "DescribeDBClustersMessageRequestTypeDef",
+    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
     "DescribeDBEngineVersionsMessageRequestTypeDef",
+    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
     "DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef",
+    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
     "DescribeDBInstancesMessageRequestTypeDef",
+    "DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
     "DescribeDBLogFilesMessageRequestTypeDef",
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
     "DescribeDBParameterGroupsMessageRequestTypeDef",
+    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
     "DescribeDBParametersMessageRequestTypeDef",
+    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
     "DescribeDBProxiesRequestRequestTypeDef",
+    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
     "DescribeDBProxyEndpointsRequestRequestTypeDef",
+    "DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
     "DescribeDBProxyTargetGroupsRequestRequestTypeDef",
+    "DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
     "DescribeDBProxyTargetsRequestRequestTypeDef",
+    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
     "DescribeDBSecurityGroupsMessageRequestTypeDef",
+    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
     "DescribeDBSnapshotsMessageRequestTypeDef",
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
+    "DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
     "DescribeEngineDefaultClusterParametersMessageRequestTypeDef",
+    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     "DescribeEngineDefaultParametersMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
     "DescribeExportTasksMessageRequestTypeDef",
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     "DescribeGlobalClustersMessageRequestTypeDef",
+    "DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
     "DescribeOptionGroupOptionsMessageRequestTypeDef",
+    "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
     "DescribeOptionGroupsMessageRequestTypeDef",
+    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     "DescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
+    "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
     "DescribeReservedDBInstancesMessageRequestTypeDef",
+    "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
     "DescribeReservedDBInstancesOfferingsMessageRequestTypeDef",
+    "DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef",
     "DescribeSourceRegionsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
-    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    "DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
-    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    "DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
-    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
-    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
-    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
-    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
-    "DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
-    "DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
-    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
-    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
-    "DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
-    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    "DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
-    "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
-    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
-    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
-    "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
-    "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
-    "DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef",
-    "DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
     "DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef",
     "DescribeDBClusterSnapshotsMessageDBClusterSnapshotDeletedWaitTypeDef",
     "DescribeDBClustersMessageDBClusterAvailableWaitTypeDef",
     "DescribeDBClustersMessageDBClusterDeletedWaitTypeDef",
     "DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef",
     "DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef",
     "DescribeDBSnapshotsMessageDBSnapshotAvailableWaitTypeDef",
@@ -465,25 +464,14 @@
         "AccountQuotaName": str,
         "Used": int,
         "Max": int,
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
 _RequiredAddRoleToDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredAddRoleToDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "RoleArn": str,
     },
 )
@@ -491,22 +479,20 @@
     "_OptionalAddRoleToDBClusterMessageRequestTypeDef",
     {
         "FeatureName": str,
     },
     total=False,
 )
 
-
 class AddRoleToDBClusterMessageRequestTypeDef(
     _RequiredAddRoleToDBClusterMessageRequestTypeDef,
     _OptionalAddRoleToDBClusterMessageRequestTypeDef,
 ):
     pass
 
-
 AddRoleToDBInstanceMessageRequestTypeDef = TypedDict(
     "AddRoleToDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "RoleArn": str,
         "FeatureName": str,
     },
@@ -568,22 +554,20 @@
         "EC2SecurityGroupName": str,
         "EC2SecurityGroupId": str,
         "EC2SecurityGroupOwnerId": str,
     },
     total=False,
 )
 
-
 class AuthorizeDBSecurityGroupIngressMessageRequestTypeDef(
     _RequiredAuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
     _OptionalAuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
 ):
     pass
 
-
 AvailabilityZoneTypeDef = TypedDict(
     "AvailabilityZoneTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
@@ -610,22 +594,20 @@
     {
         "Force": bool,
         "UseEarliestTimeOnPointInTimeUnavailable": bool,
     },
     total=False,
 )
 
-
 class BacktrackDBClusterMessageRequestTypeDef(
     _RequiredBacktrackDBClusterMessageRequestTypeDef,
     _OptionalBacktrackDBClusterMessageRequestTypeDef,
 ):
     pass
 
-
 BlueGreenDeploymentTaskTypeDef = TypedDict(
     "BlueGreenDeploymentTaskTypeDef",
     {
         "Name": str,
         "Status": str,
     },
     total=False,
@@ -688,27 +670,25 @@
         "Port": int,
         "DBUsername": str,
     },
 )
 _OptionalClientGenerateDbAuthTokenRequestTypeDef = TypedDict(
     "_OptionalClientGenerateDbAuthTokenRequestTypeDef",
     {
-        "Region": str,
+        "Region": Optional[str],
     },
     total=False,
 )
 
-
 class ClientGenerateDbAuthTokenRequestTypeDef(
     _RequiredClientGenerateDbAuthTokenRequestTypeDef,
     _OptionalClientGenerateDbAuthTokenRequestTypeDef,
 ):
     pass
 
-
 CloudwatchLogsExportConfigurationTypeDef = TypedDict(
     "CloudwatchLogsExportConfigurationTypeDef",
     {
         "EnableLogTypes": Sequence[str],
         "DisableLogTypes": Sequence[str],
     },
     total=False,
@@ -863,14 +843,39 @@
         "BacktrackedFrom": datetime,
         "BacktrackRequestCreationTime": datetime,
         "Status": str,
     },
     total=False,
 )
 
+DBClusterBacktrackResponseMetadataTypeDef = TypedDict(
+    "DBClusterBacktrackResponseMetadataTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "BacktrackIdentifier": str,
+        "BacktrackTo": datetime,
+        "BacktrackedFrom": datetime,
+        "BacktrackRequestCreationTime": datetime,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DBClusterCapacityInfoTypeDef = TypedDict(
+    "DBClusterCapacityInfoTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "PendingCapacity": int,
+        "CurrentCapacity": int,
+        "SecondsBeforeTimeout": int,
+        "TimeoutAction": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DBClusterEndpointTypeDef = TypedDict(
     "DBClusterEndpointTypeDef",
     {
         "DBClusterEndpointIdentifier": str,
         "DBClusterIdentifier": str,
         "DBClusterEndpointResourceIdentifier": str,
         "Endpoint": str,
@@ -880,14 +885,31 @@
         "StaticMembers": List[str],
         "ExcludedMembers": List[str],
         "DBClusterEndpointArn": str,
     },
     total=False,
 )
 
+DBClusterEndpointResponseMetadataTypeDef = TypedDict(
+    "DBClusterEndpointResponseMetadataTypeDef",
+    {
+        "DBClusterEndpointIdentifier": str,
+        "DBClusterIdentifier": str,
+        "DBClusterEndpointResourceIdentifier": str,
+        "Endpoint": str,
+        "Status": str,
+        "EndpointType": str,
+        "CustomEndpointType": str,
+        "StaticMembers": List[str],
+        "ExcludedMembers": List[str],
+        "DBClusterEndpointArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DBClusterMemberTypeDef = TypedDict(
     "DBClusterMemberTypeDef",
     {
         "DBInstanceIdentifier": str,
         "IsClusterWriter": bool,
         "DBClusterParameterGroupStatus": str,
         "PromotionTier": int,
@@ -918,14 +940,22 @@
         "MinimumEngineVersion": str,
         "ApplyMethod": ApplyMethodType,
         "SupportedEngineModes": List[str],
     },
     total=False,
 )
 
+DBClusterParameterGroupNameMessageTypeDef = TypedDict(
+    "DBClusterParameterGroupNameMessageTypeDef",
+    {
+        "DBClusterParameterGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DBClusterRoleTypeDef = TypedDict(
     "DBClusterRoleTypeDef",
     {
         "RoleArn": str,
         "Status": str,
         "FeatureName": str,
     },
@@ -1088,14 +1118,22 @@
     {
         "OptionGroupName": str,
         "Status": str,
     },
     total=False,
 )
 
+DBParameterGroupNameMessageTypeDef = TypedDict(
+    "DBParameterGroupNameMessageTypeDef",
+    {
+        "DBParameterGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TargetHealthTypeDef = TypedDict(
     "TargetHealthTypeDef",
     {
         "State": TargetStateType,
         "Reason": TargetHealthReasonType,
         "Description": str,
     },
@@ -1154,22 +1192,20 @@
     "_OptionalDeleteBlueGreenDeploymentRequestRequestTypeDef",
     {
         "DeleteTarget": bool,
     },
     total=False,
 )
 
-
 class DeleteBlueGreenDeploymentRequestRequestTypeDef(
     _RequiredDeleteBlueGreenDeploymentRequestRequestTypeDef,
     _OptionalDeleteBlueGreenDeploymentRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteCustomDBEngineVersionMessageRequestTypeDef = TypedDict(
     "DeleteCustomDBEngineVersionMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
     },
 )
@@ -1192,21 +1228,19 @@
     {
         "SkipFinalSnapshot": bool,
         "FinalDBSnapshotIdentifier": str,
     },
     total=False,
 )
 
-
 class DeleteDBClusterMessageRequestTypeDef(
     _RequiredDeleteDBClusterMessageRequestTypeDef, _OptionalDeleteDBClusterMessageRequestTypeDef
 ):
     pass
 
-
 DeleteDBClusterParameterGroupMessageRequestTypeDef = TypedDict(
     "DeleteDBClusterParameterGroupMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
     },
 )
 
@@ -1238,21 +1272,19 @@
         "SkipFinalSnapshot": bool,
         "FinalDBSnapshotIdentifier": str,
         "DeleteAutomatedBackups": bool,
     },
     total=False,
 )
 
-
 class DeleteDBInstanceMessageRequestTypeDef(
     _RequiredDeleteDBInstanceMessageRequestTypeDef, _OptionalDeleteDBInstanceMessageRequestTypeDef
 ):
     pass
 
-
 DeleteDBParameterGroupMessageRequestTypeDef = TypedDict(
     "DeleteDBParameterGroupMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
     },
 )
 
@@ -1324,40 +1356,28 @@
         "TargetGroupName": str,
         "DBInstanceIdentifiers": Sequence[str],
         "DBClusterIdentifiers": Sequence[str],
     },
     total=False,
 )
 
-
 class DeregisterDBProxyTargetsRequestRequestTypeDef(
     _RequiredDeregisterDBProxyTargetsRequestRequestTypeDef,
     _OptionalDeregisterDBProxyTargetsRequestRequestTypeDef,
 ):
     pass
 
-
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
         "Values": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 DescribeDBClusterSnapshotAttributesMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
     },
 )
 
@@ -1399,14 +1419,45 @@
     {
         "From": float,
         "To": float,
     },
     total=False,
 )
 
+DownloadDBLogFilePortionDetailsTypeDef = TypedDict(
+    "DownloadDBLogFilePortionDetailsTypeDef",
+    {
+        "LogFileData": str,
+        "Marker": str,
+        "AdditionalDataPending": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
+    "_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+    {
+        "DBInstanceIdentifier": str,
+        "LogFileName": str,
+    },
+)
+_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
+    "_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef(
+    _RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
+    _OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
+):
+    pass
+
 _RequiredDownloadDBLogFilePortionMessageRequestTypeDef = TypedDict(
     "_RequiredDownloadDBLogFilePortionMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "LogFileName": str,
     },
 )
@@ -1415,21 +1466,26 @@
     {
         "Marker": str,
         "NumberOfLines": int,
     },
     total=False,
 )
 
-
 class DownloadDBLogFilePortionMessageRequestTypeDef(
     _RequiredDownloadDBLogFilePortionMessageRequestTypeDef,
     _OptionalDownloadDBLogFilePortionMessageRequestTypeDef,
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 EventCategoriesMapTypeDef = TypedDict(
     "EventCategoriesMapTypeDef",
     {
         "SourceType": str,
         "EventCategories": List[str],
     },
@@ -1445,14 +1501,37 @@
         "EventCategories": List[str],
         "Date": datetime,
         "SourceArn": str,
     },
     total=False,
 )
 
+ExportTaskResponseMetadataTypeDef = TypedDict(
+    "ExportTaskResponseMetadataTypeDef",
+    {
+        "ExportTaskIdentifier": str,
+        "SourceArn": str,
+        "ExportOnly": List[str],
+        "SnapshotTime": datetime,
+        "TaskStartTime": datetime,
+        "TaskEndTime": datetime,
+        "S3Bucket": str,
+        "S3Prefix": str,
+        "IamRoleArn": str,
+        "KmsKeyId": str,
+        "Status": str,
+        "PercentProgress": int,
+        "TotalExtractedDataInGB": int,
+        "FailureCause": str,
+        "WarningMessage": str,
+        "SourceType": ExportSourceTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportTaskTypeDef = TypedDict(
     "ExportTaskTypeDef",
     {
         "ExportTaskIdentifier": str,
         "SourceArn": str,
         "ExportOnly": List[str],
         "SnapshotTime": datetime,
@@ -1482,21 +1561,19 @@
     "_OptionalFailoverDBClusterMessageRequestTypeDef",
     {
         "TargetDBInstanceIdentifier": str,
     },
     total=False,
 )
 
-
 class FailoverDBClusterMessageRequestTypeDef(
     _RequiredFailoverDBClusterMessageRequestTypeDef, _OptionalFailoverDBClusterMessageRequestTypeDef
 ):
     pass
 
-
 FailoverGlobalClusterMessageRequestTypeDef = TypedDict(
     "FailoverGlobalClusterMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "TargetDbClusterIdentifier": str,
     },
 )
@@ -1536,14 +1613,27 @@
     {
         "ResourceArn": str,
         "AuditPolicyState": AuditPolicyStateType,
     },
     total=False,
 )
 
+ModifyActivityStreamResponseTypeDef = TypedDict(
+    "ModifyActivityStreamResponseTypeDef",
+    {
+        "KmsKeyId": str,
+        "KinesisStreamName": str,
+        "Status": ActivityStreamStatusType,
+        "Mode": ActivityStreamModeType,
+        "EngineNativeAuditFieldsIncluded": bool,
+        "PolicyStatus": ActivityStreamPolicyStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ModifyCertificatesMessageRequestTypeDef = TypedDict(
     "ModifyCertificatesMessageRequestTypeDef",
     {
         "CertificateIdentifier": str,
         "RemoveCustomerOverride": bool,
     },
     total=False,
@@ -1561,22 +1651,20 @@
         "Capacity": int,
         "SecondsBeforeTimeout": int,
         "TimeoutAction": str,
     },
     total=False,
 )
 
-
 class ModifyCurrentDBClusterCapacityMessageRequestTypeDef(
     _RequiredModifyCurrentDBClusterCapacityMessageRequestTypeDef,
     _OptionalModifyCurrentDBClusterCapacityMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyCustomDBEngineVersionMessageRequestTypeDef = TypedDict(
     "_RequiredModifyCustomDBEngineVersionMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
     },
 )
@@ -1585,22 +1673,20 @@
     {
         "Description": str,
         "Status": CustomEngineVersionStatusType,
     },
     total=False,
 )
 
-
 class ModifyCustomDBEngineVersionMessageRequestTypeDef(
     _RequiredModifyCustomDBEngineVersionMessageRequestTypeDef,
     _OptionalModifyCustomDBEngineVersionMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyDBClusterEndpointMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterEndpointMessageRequestTypeDef",
     {
         "DBClusterEndpointIdentifier": str,
     },
 )
 _OptionalModifyDBClusterEndpointMessageRequestTypeDef = TypedDict(
@@ -1609,22 +1695,20 @@
         "EndpointType": str,
         "StaticMembers": Sequence[str],
         "ExcludedMembers": Sequence[str],
     },
     total=False,
 )
 
-
 class ModifyDBClusterEndpointMessageRequestTypeDef(
     _RequiredModifyDBClusterEndpointMessageRequestTypeDef,
     _OptionalModifyDBClusterEndpointMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "AttributeName": str,
     },
 )
@@ -1633,22 +1717,20 @@
     {
         "ValuesToAdd": Sequence[str],
         "ValuesToRemove": Sequence[str],
     },
     total=False,
 )
 
-
 class ModifyDBClusterSnapshotAttributeMessageRequestTypeDef(
     _RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     _OptionalModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyDBProxyEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredModifyDBProxyEndpointRequestRequestTypeDef",
     {
         "DBProxyEndpointName": str,
     },
 )
 _OptionalModifyDBProxyEndpointRequestRequestTypeDef = TypedDict(
@@ -1656,22 +1738,20 @@
     {
         "NewDBProxyEndpointName": str,
         "VpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
-
 class ModifyDBProxyEndpointRequestRequestTypeDef(
     _RequiredModifyDBProxyEndpointRequestRequestTypeDef,
     _OptionalModifyDBProxyEndpointRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyDBSnapshotAttributeMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBSnapshotAttributeMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
         "AttributeName": str,
     },
 )
@@ -1680,22 +1760,20 @@
     {
         "ValuesToAdd": Sequence[str],
         "ValuesToRemove": Sequence[str],
     },
     total=False,
 )
 
-
 class ModifyDBSnapshotAttributeMessageRequestTypeDef(
     _RequiredModifyDBSnapshotAttributeMessageRequestTypeDef,
     _OptionalModifyDBSnapshotAttributeMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBSnapshotMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
     },
 )
 _OptionalModifyDBSnapshotMessageRequestTypeDef = TypedDict(
@@ -1703,21 +1781,19 @@
     {
         "EngineVersion": str,
         "OptionGroupName": str,
     },
     total=False,
 )
 
-
 class ModifyDBSnapshotMessageRequestTypeDef(
     _RequiredModifyDBSnapshotMessageRequestTypeDef, _OptionalModifyDBSnapshotMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredModifyDBSubnetGroupMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBSubnetGroupMessageRequestTypeDef",
     {
         "DBSubnetGroupName": str,
         "SubnetIds": Sequence[str],
     },
 )
@@ -1725,22 +1801,20 @@
     "_OptionalModifyDBSubnetGroupMessageRequestTypeDef",
     {
         "DBSubnetGroupDescription": str,
     },
     total=False,
 )
 
-
 class ModifyDBSubnetGroupMessageRequestTypeDef(
     _RequiredModifyDBSubnetGroupMessageRequestTypeDef,
     _OptionalModifyDBSubnetGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredModifyEventSubscriptionMessageRequestTypeDef = TypedDict(
     "_RequiredModifyEventSubscriptionMessageRequestTypeDef",
     {
         "SubscriptionName": str,
     },
 )
 _OptionalModifyEventSubscriptionMessageRequestTypeDef = TypedDict(
@@ -1750,22 +1824,20 @@
         "SourceType": str,
         "EventCategories": Sequence[str],
         "Enabled": bool,
     },
     total=False,
 )
 
-
 class ModifyEventSubscriptionMessageRequestTypeDef(
     _RequiredModifyEventSubscriptionMessageRequestTypeDef,
     _OptionalModifyEventSubscriptionMessageRequestTypeDef,
 ):
     pass
 
-
 ModifyGlobalClusterMessageRequestTypeDef = TypedDict(
     "ModifyGlobalClusterMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "NewGlobalClusterIdentifier": str,
         "DeletionProtection": bool,
         "EngineVersion": str,
@@ -1803,14 +1875,24 @@
     "OutpostTypeDef",
     {
         "Arn": str,
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
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
         "Action": str,
         "AutoAppliedAfterDate": datetime,
         "ForcedApplyDate": datetime,
         "OptInStatus": str,
@@ -1838,22 +1920,20 @@
     {
         "BackupRetentionPeriod": int,
         "PreferredBackupWindow": str,
     },
     total=False,
 )
 
-
 class PromoteReadReplicaMessageRequestTypeDef(
     _RequiredPromoteReadReplicaMessageRequestTypeDef,
     _OptionalPromoteReadReplicaMessageRequestTypeDef,
 ):
     pass
 
-
 RangeTypeDef = TypedDict(
     "RangeTypeDef",
     {
         "From": int,
         "To": int,
         "Step": int,
     },
@@ -1877,21 +1957,19 @@
     "_OptionalRebootDBInstanceMessageRequestTypeDef",
     {
         "ForceFailover": bool,
     },
     total=False,
 )
 
-
 class RebootDBInstanceMessageRequestTypeDef(
     _RequiredRebootDBInstanceMessageRequestTypeDef, _OptionalRebootDBInstanceMessageRequestTypeDef
 ):
     pass
 
-
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "RecurringChargeAmount": float,
         "RecurringChargeFrequency": str,
     },
     total=False,
@@ -1909,22 +1987,20 @@
         "TargetGroupName": str,
         "DBInstanceIdentifiers": Sequence[str],
         "DBClusterIdentifiers": Sequence[str],
     },
     total=False,
 )
 
-
 class RegisterDBProxyTargetsRequestRequestTypeDef(
     _RequiredRegisterDBProxyTargetsRequestRequestTypeDef,
     _OptionalRegisterDBProxyTargetsRequestRequestTypeDef,
 ):
     pass
 
-
 RemoveFromGlobalClusterMessageRequestTypeDef = TypedDict(
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "DbClusterIdentifier": str,
     },
     total=False,
@@ -1941,22 +2017,20 @@
     "_OptionalRemoveRoleFromDBClusterMessageRequestTypeDef",
     {
         "FeatureName": str,
     },
     total=False,
 )
 
-
 class RemoveRoleFromDBClusterMessageRequestTypeDef(
     _RequiredRemoveRoleFromDBClusterMessageRequestTypeDef,
     _OptionalRemoveRoleFromDBClusterMessageRequestTypeDef,
 ):
     pass
 
-
 RemoveRoleFromDBInstanceMessageRequestTypeDef = TypedDict(
     "RemoveRoleFromDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "RoleArn": str,
         "FeatureName": str,
     },
@@ -1974,14 +2048,25 @@
     "RemoveTagsFromResourceMessageRequestTypeDef",
     {
         "ResourceName": str,
         "TagKeys": Sequence[str],
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
 _RequiredRevokeDBSecurityGroupIngressMessageRequestTypeDef = TypedDict(
     "_RequiredRevokeDBSecurityGroupIngressMessageRequestTypeDef",
     {
         "DBSecurityGroupName": str,
     },
 )
 _OptionalRevokeDBSecurityGroupIngressMessageRequestTypeDef = TypedDict(
@@ -1991,22 +2076,20 @@
         "EC2SecurityGroupName": str,
         "EC2SecurityGroupId": str,
         "EC2SecurityGroupOwnerId": str,
     },
     total=False,
 )
 
-
 class RevokeDBSecurityGroupIngressMessageRequestTypeDef(
     _RequiredRevokeDBSecurityGroupIngressMessageRequestTypeDef,
     _OptionalRevokeDBSecurityGroupIngressMessageRequestTypeDef,
 ):
     pass
 
-
 SourceRegionTypeDef = TypedDict(
     "SourceRegionTypeDef",
     {
         "RegionName": str,
         "Endpoint": str,
         "Status": str,
         "SupportsDBInstanceAutomatedBackupsReplication": bool,
@@ -2027,21 +2110,32 @@
     {
         "ApplyImmediately": bool,
         "EngineNativeAuditFieldsIncluded": bool,
     },
     total=False,
 )
 
-
 class StartActivityStreamRequestRequestTypeDef(
     _RequiredStartActivityStreamRequestRequestTypeDef,
     _OptionalStartActivityStreamRequestRequestTypeDef,
 ):
     pass
 
+StartActivityStreamResponseTypeDef = TypedDict(
+    "StartActivityStreamResponseTypeDef",
+    {
+        "KmsKeyId": str,
+        "KinesisStreamName": str,
+        "Status": ActivityStreamStatusType,
+        "Mode": ActivityStreamModeType,
+        "ApplyImmediately": bool,
+        "EngineNativeAuditFieldsIncluded": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 StartDBClusterMessageRequestTypeDef = TypedDict(
     "StartDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
@@ -2059,22 +2153,20 @@
         "KmsKeyId": str,
         "PreSignedUrl": str,
         "SourceRegion": str,
     },
     total=False,
 )
 
-
 class StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef(
     _RequiredStartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     _OptionalStartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
 ):
     pass
 
-
 StartDBInstanceMessageRequestTypeDef = TypedDict(
     "StartDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
     },
 )
 
@@ -2093,42 +2185,48 @@
     {
         "S3Prefix": str,
         "ExportOnly": Sequence[str],
     },
     total=False,
 )
 
-
 class StartExportTaskMessageRequestTypeDef(
     _RequiredStartExportTaskMessageRequestTypeDef, _OptionalStartExportTaskMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredStopActivityStreamRequestRequestTypeDef = TypedDict(
     "_RequiredStopActivityStreamRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalStopActivityStreamRequestRequestTypeDef = TypedDict(
     "_OptionalStopActivityStreamRequestRequestTypeDef",
     {
         "ApplyImmediately": bool,
     },
     total=False,
 )
 
-
 class StopActivityStreamRequestRequestTypeDef(
     _RequiredStopActivityStreamRequestRequestTypeDef,
     _OptionalStopActivityStreamRequestRequestTypeDef,
 ):
     pass
 
+StopActivityStreamResponseTypeDef = TypedDict(
+    "StopActivityStreamResponseTypeDef",
+    {
+        "KmsKeyId": str,
+        "KinesisStreamName": str,
+        "Status": ActivityStreamStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 StopDBClusterMessageRequestTypeDef = TypedDict(
     "StopDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
@@ -2150,238 +2248,100 @@
     "_OptionalStopDBInstanceMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
     },
     total=False,
 )
 
-
 class StopDBInstanceMessageRequestTypeDef(
     _RequiredStopDBInstanceMessageRequestTypeDef, _OptionalStopDBInstanceMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredSwitchoverBlueGreenDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredSwitchoverBlueGreenDeploymentRequestRequestTypeDef",
     {
         "BlueGreenDeploymentIdentifier": str,
     },
 )
 _OptionalSwitchoverBlueGreenDeploymentRequestRequestTypeDef = TypedDict(
     "_OptionalSwitchoverBlueGreenDeploymentRequestRequestTypeDef",
     {
         "SwitchoverTimeout": int,
     },
     total=False,
 )
 
-
 class SwitchoverBlueGreenDeploymentRequestRequestTypeDef(
     _RequiredSwitchoverBlueGreenDeploymentRequestRequestTypeDef,
     _OptionalSwitchoverBlueGreenDeploymentRequestRequestTypeDef,
 ):
     pass
 
-
 SwitchoverReadReplicaMessageRequestTypeDef = TypedDict(
     "SwitchoverReadReplicaMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
     },
 )
 
 AccountAttributesMessageTypeDef = TypedDict(
     "AccountAttributesMessageTypeDef",
     {
         "AccountQuotas": List[AccountQuotaTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterBacktrackResponseMetadataTypeDef = TypedDict(
-    "DBClusterBacktrackResponseMetadataTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "BacktrackIdentifier": str,
-        "BacktrackTo": datetime,
-        "BacktrackedFrom": datetime,
-        "BacktrackRequestCreationTime": datetime,
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterCapacityInfoTypeDef = TypedDict(
-    "DBClusterCapacityInfoTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "PendingCapacity": int,
-        "CurrentCapacity": int,
-        "SecondsBeforeTimeout": int,
-        "TimeoutAction": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterEndpointResponseMetadataTypeDef = TypedDict(
-    "DBClusterEndpointResponseMetadataTypeDef",
-    {
-        "DBClusterEndpointIdentifier": str,
-        "DBClusterIdentifier": str,
-        "DBClusterEndpointResourceIdentifier": str,
-        "Endpoint": str,
-        "Status": str,
-        "EndpointType": str,
-        "CustomEndpointType": str,
-        "StaticMembers": List[str],
-        "ExcludedMembers": List[str],
-        "DBClusterEndpointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterParameterGroupNameMessageTypeDef = TypedDict(
-    "DBClusterParameterGroupNameMessageTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBParameterGroupNameMessageTypeDef = TypedDict(
-    "DBParameterGroupNameMessageTypeDef",
-    {
-        "DBParameterGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DownloadDBLogFilePortionDetailsTypeDef = TypedDict(
-    "DownloadDBLogFilePortionDetailsTypeDef",
-    {
-        "LogFileData": str,
-        "Marker": str,
-        "AdditionalDataPending": bool,
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
-ExportTaskResponseMetadataTypeDef = TypedDict(
-    "ExportTaskResponseMetadataTypeDef",
-    {
-        "ExportTaskIdentifier": str,
-        "SourceArn": str,
-        "ExportOnly": List[str],
-        "SnapshotTime": datetime,
-        "TaskStartTime": datetime,
-        "TaskEndTime": datetime,
-        "S3Bucket": str,
-        "S3Prefix": str,
-        "IamRoleArn": str,
-        "KmsKeyId": str,
-        "Status": str,
-        "PercentProgress": int,
-        "TotalExtractedDataInGB": int,
-        "FailureCause": str,
-        "WarningMessage": str,
-        "SourceType": ExportSourceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ModifyActivityStreamResponseTypeDef = TypedDict(
-    "ModifyActivityStreamResponseTypeDef",
-    {
-        "KmsKeyId": str,
-        "KinesisStreamName": str,
-        "Status": ActivityStreamStatusType,
-        "Mode": ActivityStreamModeType,
-        "EngineNativeAuditFieldsIncluded": bool,
-        "PolicyStatus": ActivityStreamPolicyStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartActivityStreamResponseTypeDef = TypedDict(
-    "StartActivityStreamResponseTypeDef",
-    {
-        "KmsKeyId": str,
-        "KinesisStreamName": str,
-        "Status": ActivityStreamStatusType,
-        "Mode": ActivityStreamModeType,
-        "ApplyImmediately": bool,
-        "EngineNativeAuditFieldsIncluded": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopActivityStreamResponseTypeDef = TypedDict(
-    "StopActivityStreamResponseTypeDef",
-    {
-        "KmsKeyId": str,
-        "KinesisStreamName": str,
-        "Status": ActivityStreamStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddSourceIdentifierToSubscriptionResultTypeDef = TypedDict(
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEventSubscriptionResultTypeDef = TypedDict(
     "CreateEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventSubscriptionResultTypeDef = TypedDict(
     "DeleteEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventSubscriptionsMessageTypeDef = TypedDict(
     "EventSubscriptionsMessageTypeDef",
     {
         "Marker": str,
         "EventSubscriptionsList": List[EventSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyEventSubscriptionResultTypeDef = TypedDict(
     "ModifyEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveSourceIdentifierFromSubscriptionResultTypeDef = TypedDict(
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddTagsToResourceMessageRequestTypeDef = TypedDict(
     "AddTagsToResourceMessageRequestTypeDef",
     {
         "ResourceName": str,
@@ -2401,22 +2361,20 @@
     "_OptionalCopyDBClusterParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CopyDBClusterParameterGroupMessageRequestTypeDef(
     _RequiredCopyDBClusterParameterGroupMessageRequestTypeDef,
     _OptionalCopyDBClusterParameterGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCopyDBClusterSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCopyDBClusterSnapshotMessageRequestTypeDef",
     {
         "SourceDBClusterSnapshotIdentifier": str,
         "TargetDBClusterSnapshotIdentifier": str,
     },
 )
@@ -2428,22 +2386,20 @@
         "CopyTags": bool,
         "Tags": Sequence[TagTypeDef],
         "SourceRegion": str,
     },
     total=False,
 )
 
-
 class CopyDBClusterSnapshotMessageRequestTypeDef(
     _RequiredCopyDBClusterSnapshotMessageRequestTypeDef,
     _OptionalCopyDBClusterSnapshotMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCopyDBParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCopyDBParameterGroupMessageRequestTypeDef",
     {
         "SourceDBParameterGroupIdentifier": str,
         "TargetDBParameterGroupIdentifier": str,
         "TargetDBParameterGroupDescription": str,
     },
@@ -2452,22 +2408,20 @@
     "_OptionalCopyDBParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CopyDBParameterGroupMessageRequestTypeDef(
     _RequiredCopyDBParameterGroupMessageRequestTypeDef,
     _OptionalCopyDBParameterGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCopyDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCopyDBSnapshotMessageRequestTypeDef",
     {
         "SourceDBSnapshotIdentifier": str,
         "TargetDBSnapshotIdentifier": str,
     },
 )
@@ -2482,21 +2436,19 @@
         "TargetCustomAvailabilityZone": str,
         "CopyOptionGroup": bool,
         "SourceRegion": str,
     },
     total=False,
 )
 
-
 class CopyDBSnapshotMessageRequestTypeDef(
     _RequiredCopyDBSnapshotMessageRequestTypeDef, _OptionalCopyDBSnapshotMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredCopyOptionGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCopyOptionGroupMessageRequestTypeDef",
     {
         "SourceOptionGroupIdentifier": str,
         "TargetOptionGroupIdentifier": str,
         "TargetOptionGroupDescription": str,
     },
@@ -2505,21 +2457,19 @@
     "_OptionalCopyOptionGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CopyOptionGroupMessageRequestTypeDef(
     _RequiredCopyOptionGroupMessageRequestTypeDef, _OptionalCopyOptionGroupMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateBlueGreenDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBlueGreenDeploymentRequestRequestTypeDef",
     {
         "BlueGreenDeploymentName": str,
         "Source": str,
     },
 )
@@ -2530,22 +2480,20 @@
         "TargetDBParameterGroupName": str,
         "TargetDBClusterParameterGroupName": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateBlueGreenDeploymentRequestRequestTypeDef(
     _RequiredCreateBlueGreenDeploymentRequestRequestTypeDef,
     _OptionalCreateBlueGreenDeploymentRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateCustomDBEngineVersionMessageRequestTypeDef = TypedDict(
     "_RequiredCreateCustomDBEngineVersionMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
     },
 )
@@ -2559,22 +2507,20 @@
         "Description": str,
         "Manifest": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateCustomDBEngineVersionMessageRequestTypeDef(
     _RequiredCreateCustomDBEngineVersionMessageRequestTypeDef,
     _OptionalCreateCustomDBEngineVersionMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBClusterEndpointMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterEndpointMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterEndpointIdentifier": str,
         "EndpointType": str,
     },
@@ -2585,22 +2531,20 @@
         "StaticMembers": Sequence[str],
         "ExcludedMembers": Sequence[str],
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBClusterEndpointMessageRequestTypeDef(
     _RequiredCreateDBClusterEndpointMessageRequestTypeDef,
     _OptionalCreateDBClusterEndpointMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBClusterParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterParameterGroupMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
         "DBParameterGroupFamily": str,
         "Description": str,
     },
@@ -2609,22 +2553,20 @@
     "_OptionalCreateDBClusterParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBClusterParameterGroupMessageRequestTypeDef(
     _RequiredCreateDBClusterParameterGroupMessageRequestTypeDef,
     _OptionalCreateDBClusterParameterGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBClusterSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterSnapshotMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "DBClusterIdentifier": str,
     },
 )
@@ -2632,22 +2574,20 @@
     "_OptionalCreateDBClusterSnapshotMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBClusterSnapshotMessageRequestTypeDef(
     _RequiredCreateDBClusterSnapshotMessageRequestTypeDef,
     _OptionalCreateDBClusterSnapshotMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBParameterGroupMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
         "DBParameterGroupFamily": str,
         "Description": str,
     },
@@ -2656,22 +2596,20 @@
     "_OptionalCreateDBParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBParameterGroupMessageRequestTypeDef(
     _RequiredCreateDBParameterGroupMessageRequestTypeDef,
     _OptionalCreateDBParameterGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBProxyEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDBProxyEndpointRequestRequestTypeDef",
     {
         "DBProxyName": str,
         "DBProxyEndpointName": str,
         "VpcSubnetIds": Sequence[str],
     },
@@ -2682,22 +2620,20 @@
         "VpcSecurityGroupIds": Sequence[str],
         "TargetRole": DBProxyEndpointTargetRoleType,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBProxyEndpointRequestRequestTypeDef(
     _RequiredCreateDBProxyEndpointRequestRequestTypeDef,
     _OptionalCreateDBProxyEndpointRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBSecurityGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBSecurityGroupMessageRequestTypeDef",
     {
         "DBSecurityGroupName": str,
         "DBSecurityGroupDescription": str,
     },
 )
@@ -2705,22 +2641,20 @@
     "_OptionalCreateDBSecurityGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBSecurityGroupMessageRequestTypeDef(
     _RequiredCreateDBSecurityGroupMessageRequestTypeDef,
     _OptionalCreateDBSecurityGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBSnapshotMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
         "DBInstanceIdentifier": str,
     },
 )
@@ -2728,21 +2662,19 @@
     "_OptionalCreateDBSnapshotMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBSnapshotMessageRequestTypeDef(
     _RequiredCreateDBSnapshotMessageRequestTypeDef, _OptionalCreateDBSnapshotMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateDBSubnetGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBSubnetGroupMessageRequestTypeDef",
     {
         "DBSubnetGroupName": str,
         "DBSubnetGroupDescription": str,
         "SubnetIds": Sequence[str],
     },
@@ -2751,22 +2683,20 @@
     "_OptionalCreateDBSubnetGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBSubnetGroupMessageRequestTypeDef(
     _RequiredCreateDBSubnetGroupMessageRequestTypeDef,
     _OptionalCreateDBSubnetGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateEventSubscriptionMessageRequestTypeDef = TypedDict(
     "_RequiredCreateEventSubscriptionMessageRequestTypeDef",
     {
         "SubscriptionName": str,
         "SnsTopicArn": str,
     },
 )
@@ -2778,22 +2708,20 @@
         "SourceIds": Sequence[str],
         "Enabled": bool,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateEventSubscriptionMessageRequestTypeDef(
     _RequiredCreateEventSubscriptionMessageRequestTypeDef,
     _OptionalCreateEventSubscriptionMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateOptionGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateOptionGroupMessageRequestTypeDef",
     {
         "OptionGroupName": str,
         "EngineName": str,
         "MajorEngineVersion": str,
         "OptionGroupDescription": str,
@@ -2803,21 +2731,19 @@
     "_OptionalCreateOptionGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateOptionGroupMessageRequestTypeDef(
     _RequiredCreateOptionGroupMessageRequestTypeDef, _OptionalCreateOptionGroupMessageRequestTypeDef
 ):
     pass
 
-
 DBClusterSnapshotTypeDef = TypedDict(
     "DBClusterSnapshotTypeDef",
     {
         "AvailabilityZones": List[str],
         "DBClusterSnapshotIdentifier": str,
         "DBClusterIdentifier": str,
         "SnapshotCreateTime": datetime,
@@ -2836,14 +2762,15 @@
         "StorageEncrypted": bool,
         "KmsKeyId": str,
         "DBClusterSnapshotArn": str,
         "SourceDBClusterSnapshotArn": str,
         "IAMDatabaseAuthenticationEnabled": bool,
         "TagList": List[TagTypeDef],
         "DBSystemId": str,
+        "StorageType": str,
     },
     total=False,
 )
 
 _RequiredPurchaseReservedDBInstancesOfferingMessageRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedDBInstancesOfferingMessageRequestTypeDef",
     {
@@ -2856,27 +2783,25 @@
         "ReservedDBInstanceId": str,
         "DBInstanceCount": int,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class PurchaseReservedDBInstancesOfferingMessageRequestTypeDef(
     _RequiredPurchaseReservedDBInstancesOfferingMessageRequestTypeDef,
     _OptionalPurchaseReservedDBInstancesOfferingMessageRequestTypeDef,
 ):
     pass
 
-
 TagListMessageTypeDef = TypedDict(
     "TagListMessageTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrderableDBInstanceOptionTypeDef = TypedDict(
     "OrderableDBInstanceOptionTypeDef",
     {
         "Engine": str,
@@ -2937,37 +2862,38 @@
 )
 
 CertificateMessageTypeDef = TypedDict(
     "CertificateMessageTypeDef",
     {
         "Certificates": List[CertificateTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyCertificatesResultTypeDef = TypedDict(
     "ModifyCertificatesResultTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterPendingModifiedValuesTypeDef = TypedDict(
     "ClusterPendingModifiedValuesTypeDef",
     {
         "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
         "DBClusterIdentifier": str,
         "MasterUserPassword": str,
         "IAMDatabaseAuthenticationEnabled": bool,
         "EngineVersion": str,
         "BackupRetentionPeriod": int,
         "AllocatedStorage": int,
         "Iops": int,
+        "StorageType": str,
     },
     total=False,
 )
 
 DBProxyTargetGroupTypeDef = TypedDict(
     "DBProxyTargetGroupTypeDef",
     {
@@ -2995,69 +2921,67 @@
     {
         "ConnectionPoolConfig": ConnectionPoolConfigurationTypeDef,
         "NewName": str,
     },
     total=False,
 )
 
-
 class ModifyDBProxyTargetGroupRequestRequestTypeDef(
     _RequiredModifyDBProxyTargetGroupRequestRequestTypeDef,
     _OptionalModifyDBProxyTargetGroupRequestRequestTypeDef,
 ):
     pass
 
-
 CopyDBClusterParameterGroupResultTypeDef = TypedDict(
     "CopyDBClusterParameterGroupResultTypeDef",
     {
         "DBClusterParameterGroup": DBClusterParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBClusterParameterGroupResultTypeDef = TypedDict(
     "CreateDBClusterParameterGroupResultTypeDef",
     {
         "DBClusterParameterGroup": DBClusterParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterParameterGroupsMessageTypeDef = TypedDict(
     "DBClusterParameterGroupsMessageTypeDef",
     {
         "Marker": str,
         "DBClusterParameterGroups": List[DBClusterParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyDBParameterGroupResultTypeDef = TypedDict(
     "CopyDBParameterGroupResultTypeDef",
     {
         "DBParameterGroup": DBParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBParameterGroupResultTypeDef = TypedDict(
     "CreateDBParameterGroupResultTypeDef",
     {
         "DBParameterGroup": DBParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBParameterGroupsMessageTypeDef = TypedDict(
     "DBParameterGroupsMessageTypeDef",
     {
         "Marker": str,
         "DBParameterGroups": List[DBParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
@@ -3115,21 +3039,19 @@
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
         "SourceRegion": str,
     },
     total=False,
 )
 
-
 class CreateDBClusterMessageRequestTypeDef(
     _RequiredCreateDBClusterMessageRequestTypeDef, _OptionalCreateDBClusterMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredModifyDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 _OptionalModifyDBClusterMessageRequestTypeDef = TypedDict(
@@ -3169,25 +3091,25 @@
         "PerformanceInsightsKMSKeyId": str,
         "PerformanceInsightsRetentionPeriod": int,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
         "ManageMasterUserPassword": bool,
         "RotateMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
+        "EngineMode": str,
+        "AllowEngineModeChange": bool,
     },
     total=False,
 )
 
-
 class ModifyDBClusterMessageRequestTypeDef(
     _RequiredModifyDBClusterMessageRequestTypeDef, _OptionalModifyDBClusterMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredRestoreDBClusterFromS3MessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBClusterFromS3MessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "Engine": str,
         "MasterUsername": str,
         "SourceEngine": str,
@@ -3223,26 +3145,25 @@
         "CopyTagsToSnapshot": bool,
         "Domain": str,
         "DomainIAMRoleName": str,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
+        "StorageType": str,
     },
     total=False,
 )
 
-
 class RestoreDBClusterFromS3MessageRequestTypeDef(
     _RequiredRestoreDBClusterFromS3MessageRequestTypeDef,
     _OptionalRestoreDBClusterFromS3MessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "SnapshotIdentifier": str,
         "Engine": str,
     },
@@ -3275,22 +3196,20 @@
         "PubliclyAccessible": bool,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
     },
     total=False,
 )
 
-
 class RestoreDBClusterFromSnapshotMessageRequestTypeDef(
     _RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef,
     _OptionalRestoreDBClusterFromSnapshotMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredRestoreDBClusterToPointInTimeMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBClusterToPointInTimeMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "SourceDBClusterIdentifier": str,
     },
 )
@@ -3322,22 +3241,20 @@
         "Iops": int,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
     },
     total=False,
 )
 
-
 class RestoreDBClusterToPointInTimeMessageRequestTypeDef(
     _RequiredRestoreDBClusterToPointInTimeMessageRequestTypeDef,
     _OptionalRestoreDBClusterToPointInTimeMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDBInstanceMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "Engine": str,
     },
@@ -3397,31 +3314,29 @@
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
         "CACertificateIdentifier": str,
     },
     total=False,
 )
 
-
 class CreateDBInstanceMessageRequestTypeDef(
     _RequiredCreateDBInstanceMessageRequestTypeDef, _OptionalCreateDBInstanceMessageRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateDBInstanceReadReplicaMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBInstanceReadReplicaMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
-        "SourceDBInstanceIdentifier": str,
     },
 )
 _OptionalCreateDBInstanceReadReplicaMessageRequestTypeDef = TypedDict(
     "_OptionalCreateDBInstanceReadReplicaMessageRequestTypeDef",
     {
+        "SourceDBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "AvailabilityZone": str,
         "Port": int,
         "MultiAZ": bool,
         "AutoMinorVersionUpgrade": bool,
         "Iops": int,
         "OptionGroupName": str,
@@ -3449,27 +3364,26 @@
         "ReplicaMode": ReplicaModeType,
         "MaxAllocatedStorage": int,
         "CustomIamInstanceProfile": str,
         "NetworkType": str,
         "StorageThroughput": int,
         "EnableCustomerOwnedIp": bool,
         "AllocatedStorage": int,
+        "SourceDBClusterIdentifier": str,
         "SourceRegion": str,
     },
     total=False,
 )
 
-
 class CreateDBInstanceReadReplicaMessageRequestTypeDef(
     _RequiredCreateDBInstanceReadReplicaMessageRequestTypeDef,
     _OptionalCreateDBInstanceReadReplicaMessageRequestTypeDef,
 ):
     pass
 
-
 DBSnapshotTypeDef = TypedDict(
     "DBSnapshotTypeDef",
     {
         "DBSnapshotIdentifier": str,
         "DBInstanceIdentifier": str,
         "SnapshotCreateTime": datetime,
         "Engine": str,
@@ -3562,25 +3476,24 @@
         "AutomationMode": AutomationModeType,
         "ResumeFullAutomationModeMinutes": int,
         "NetworkType": str,
         "StorageThroughput": int,
         "ManageMasterUserPassword": bool,
         "RotateMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
+        "Engine": str,
     },
     total=False,
 )
 
-
 class ModifyDBInstanceMessageRequestTypeDef(
     _RequiredModifyDBInstanceMessageRequestTypeDef, _OptionalModifyDBInstanceMessageRequestTypeDef
 ):
     pass
 
-
 PendingModifiedValuesTypeDef = TypedDict(
     "PendingModifiedValuesTypeDef",
     {
         "DBInstanceClass": str,
         "AllocatedStorage": int,
         "MasterUserPassword": str,
         "Port": int,
@@ -3595,14 +3508,15 @@
         "DBSubnetGroupName": str,
         "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
         "ProcessorFeatures": List[ProcessorFeatureTypeDef],
         "IAMDatabaseAuthenticationEnabled": bool,
         "AutomationMode": AutomationModeType,
         "ResumeFullAutomationModeTime": datetime,
         "StorageThroughput": int,
+        "Engine": str,
     },
     total=False,
 )
 
 _RequiredRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef",
     {
@@ -3646,22 +3560,20 @@
         "StorageThroughput": int,
         "DBClusterSnapshotIdentifier": str,
         "AllocatedStorage": int,
     },
     total=False,
 )
 
-
 class RestoreDBInstanceFromDBSnapshotMessageRequestTypeDef(
     _RequiredRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef,
     _OptionalRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredRestoreDBInstanceFromS3MessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBInstanceFromS3MessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "Engine": str,
         "SourceEngine": str,
@@ -3714,22 +3626,20 @@
         "StorageThroughput": int,
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
     },
     total=False,
 )
 
-
 class RestoreDBInstanceFromS3MessageRequestTypeDef(
     _RequiredRestoreDBInstanceFromS3MessageRequestTypeDef,
     _OptionalRestoreDBInstanceFromS3MessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredRestoreDBInstanceToPointInTimeMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBInstanceToPointInTimeMessageRequestTypeDef",
     {
         "TargetDBInstanceIdentifier": str,
     },
 )
 _OptionalRestoreDBInstanceToPointInTimeMessageRequestTypeDef = TypedDict(
@@ -3773,52 +3683,50 @@
         "NetworkType": str,
         "StorageThroughput": int,
         "AllocatedStorage": int,
     },
     total=False,
 )
 
-
 class RestoreDBInstanceToPointInTimeMessageRequestTypeDef(
     _RequiredRestoreDBInstanceToPointInTimeMessageRequestTypeDef,
     _OptionalRestoreDBInstanceToPointInTimeMessageRequestTypeDef,
 ):
     pass
 
-
 CreateDBProxyEndpointResponseTypeDef = TypedDict(
     "CreateDBProxyEndpointResponseTypeDef",
     {
         "DBProxyEndpoint": DBProxyEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBProxyEndpointResponseTypeDef = TypedDict(
     "DeleteDBProxyEndpointResponseTypeDef",
     {
         "DBProxyEndpoint": DBProxyEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBProxyEndpointsResponseTypeDef = TypedDict(
     "DescribeDBProxyEndpointsResponseTypeDef",
     {
         "DBProxyEndpoints": List[DBProxyEndpointTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBProxyEndpointResponseTypeDef = TypedDict(
     "ModifyDBProxyEndpointResponseTypeDef",
     {
         "DBProxyEndpoint": DBProxyEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDBProxyRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDBProxyRequestRequestTypeDef",
     {
         "DBProxyName": str,
@@ -3836,21 +3744,19 @@
         "IdleClientTimeout": int,
         "DebugLogging": bool,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDBProxyRequestRequestTypeDef(
     _RequiredCreateDBProxyRequestRequestTypeDef, _OptionalCreateDBProxyRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredModifyDBProxyRequestRequestTypeDef = TypedDict(
     "_RequiredModifyDBProxyRequestRequestTypeDef",
     {
         "DBProxyName": str,
     },
 )
 _OptionalModifyDBProxyRequestRequestTypeDef = TypedDict(
@@ -3863,54 +3769,52 @@
         "DebugLogging": bool,
         "RoleArn": str,
         "SecurityGroups": Sequence[str],
     },
     total=False,
 )
 
-
 class ModifyDBProxyRequestRequestTypeDef(
     _RequiredModifyDBProxyRequestRequestTypeDef, _OptionalModifyDBProxyRequestRequestTypeDef
 ):
     pass
 
-
 DBClusterBacktrackMessageTypeDef = TypedDict(
     "DBClusterBacktrackMessageTypeDef",
     {
         "Marker": str,
         "DBClusterBacktracks": List[DBClusterBacktrackTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterEndpointMessageTypeDef = TypedDict(
     "DBClusterEndpointMessageTypeDef",
     {
         "Marker": str,
         "DBClusterEndpoints": List[DBClusterEndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterParameterGroupDetailsTypeDef = TypedDict(
     "DBClusterParameterGroupDetailsTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBParameterGroupDetailsTypeDef = TypedDict(
     "DBParameterGroupDetailsTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EngineDefaultsTypeDef = TypedDict(
     "EngineDefaultsTypeDef",
     {
         "DBParameterGroupFamily": str,
@@ -3947,22 +3851,20 @@
     {
         "ResetAllParameters": bool,
         "Parameters": Sequence[ParameterTypeDef],
     },
     total=False,
 )
 
-
 class ResetDBClusterParameterGroupMessageRequestTypeDef(
     _RequiredResetDBClusterParameterGroupMessageRequestTypeDef,
     _OptionalResetDBClusterParameterGroupMessageRequestTypeDef,
 ):
     pass
 
-
 _RequiredResetDBParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredResetDBParameterGroupMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
     },
 )
 _OptionalResetDBParameterGroupMessageRequestTypeDef = TypedDict(
@@ -3970,22 +3872,20 @@
     {
         "ResetAllParameters": bool,
         "Parameters": Sequence[ParameterTypeDef],
     },
     total=False,
 )
 
-
 class ResetDBParameterGroupMessageRequestTypeDef(
     _RequiredResetDBParameterGroupMessageRequestTypeDef,
     _OptionalResetDBParameterGroupMessageRequestTypeDef,
 ):
     pass
 
-
 DBClusterSnapshotAttributesResultTypeDef = TypedDict(
     "DBClusterSnapshotAttributesResultTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "DBClusterSnapshotAttributes": List[DBClusterSnapshotAttributeTypeDef],
     },
     total=False,
@@ -4021,15 +3921,15 @@
         "KMSKeyId": str,
         "CreateTime": datetime,
         "TagList": List[TagTypeDef],
         "SupportsBabelfish": bool,
         "CustomDBEngineVersionManifest": str,
         "SupportsCertificateRotationWithoutRestart": bool,
         "SupportedCACertificateIdentifiers": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBEngineVersionTypeDef = TypedDict(
     "DBEngineVersionTypeDef",
     {
         "Engine": str,
@@ -4160,36 +4060,78 @@
     {
         "DBSnapshotIdentifier": str,
         "DBSnapshotAttributes": List[DBSnapshotAttributeTypeDef],
     },
     total=False,
 )
 
+DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef = TypedDict(
+    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
+    {
+        "BlueGreenDeploymentIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeBlueGreenDeploymentsRequestRequestTypeDef = TypedDict(
     "DescribeBlueGreenDeploymentsRequestRequestTypeDef",
     {
         "BlueGreenDeploymentIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
+    {
+        "CertificateIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCertificatesMessageRequestTypeDef = TypedDict(
     "DescribeCertificatesMessageRequestTypeDef",
     {
         "CertificateIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+    },
+)
+_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
+    {
+        "BacktrackIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef(
+    _RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
+    _OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDBClusterBacktracksMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBClusterBacktracksMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 _OptionalDescribeDBClusterBacktracksMessageRequestTypeDef = TypedDict(
@@ -4199,45 +4141,86 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeDBClusterBacktracksMessageRequestTypeDef(
     _RequiredDescribeDBClusterBacktracksMessageRequestTypeDef,
     _OptionalDescribeDBClusterBacktracksMessageRequestTypeDef,
 ):
     pass
 
+DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef = TypedDict(
+    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "DBClusterEndpointIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeDBClusterEndpointsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterEndpointsMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterEndpointIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
+    {
+        "DBClusterParameterGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBClusterParameterGroupsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterParameterGroupsMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
+    {
+        "DBClusterParameterGroupName": str,
+    },
+)
+_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef(
+    _RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
+    _OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDBClusterParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBClusterParametersMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
     },
 )
 _OptionalDescribeDBClusterParametersMessageRequestTypeDef = TypedDict(
@@ -4247,21 +4230,33 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeDBClusterParametersMessageRequestTypeDef(
     _RequiredDescribeDBClusterParametersMessageRequestTypeDef,
     _OptionalDescribeDBClusterParametersMessageRequestTypeDef,
 ):
     pass
 
+DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "DBClusterSnapshotIdentifier": str,
+        "SnapshotType": str,
+        "Filters": Sequence[FilterTypeDef],
+        "IncludeShared": bool,
+        "IncludePublic": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeDBClusterSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterSnapshotsMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterSnapshotIdentifier": str,
         "SnapshotType": str,
@@ -4270,26 +4265,53 @@
         "Marker": str,
         "IncludeShared": bool,
         "IncludePublic": bool,
     },
     total=False,
 )
 
+DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef = TypedDict(
+    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "IncludeShared": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBClustersMessageRequestTypeDef = TypedDict(
     "DescribeDBClustersMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
         "IncludeShared": bool,
     },
     total=False,
 )
 
+DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef = TypedDict(
+    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
+    {
+        "Engine": str,
+        "EngineVersion": str,
+        "DBParameterGroupFamily": str,
+        "Filters": Sequence[FilterTypeDef],
+        "DefaultOnly": bool,
+        "ListSupportedCharacterSets": bool,
+        "ListSupportedTimezones": bool,
+        "IncludeAll": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBEngineVersionsMessageRequestTypeDef = TypedDict(
     "DescribeDBEngineVersionsMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "DBParameterGroupFamily": str,
         "Filters": Sequence[FilterTypeDef],
@@ -4299,38 +4321,84 @@
         "ListSupportedCharacterSets": bool,
         "ListSupportedTimezones": bool,
         "IncludeAll": bool,
     },
     total=False,
 )
 
+DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef = TypedDict(
+    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
+    {
+        "DbiResourceId": str,
+        "DBInstanceIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "DBInstanceAutomatedBackupsArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef = TypedDict(
     "DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef",
     {
         "DbiResourceId": str,
         "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
         "DBInstanceAutomatedBackupsArn": str,
     },
     total=False,
 )
 
+DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef = TypedDict(
+    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
+    {
+        "DBInstanceIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBInstancesMessageRequestTypeDef = TypedDict(
     "DescribeDBInstancesMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
+    {
+        "DBInstanceIdentifier": str,
+    },
+)
+_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
+    {
+        "FilenameContains": str,
+        "FileLastWritten": int,
+        "FileSize": int,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef(
+    _RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
+    _OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDBLogFilesMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBLogFilesMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
     },
 )
 _OptionalDescribeDBLogFilesMessageRequestTypeDef = TypedDict(
@@ -4342,33 +4410,63 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeDBLogFilesMessageRequestTypeDef(
     _RequiredDescribeDBLogFilesMessageRequestTypeDef,
     _OptionalDescribeDBLogFilesMessageRequestTypeDef,
 ):
     pass
 
+DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
+    {
+        "DBParameterGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeDBParameterGroupsMessageRequestTypeDef = TypedDict(
     "DescribeDBParameterGroupsMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
+    {
+        "DBParameterGroupName": str,
+    },
+)
+_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef(
+    _RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
+    _OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDBParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBParametersMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
     },
 )
 _OptionalDescribeDBParametersMessageRequestTypeDef = TypedDict(
@@ -4378,45 +4476,86 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeDBParametersMessageRequestTypeDef(
     _RequiredDescribeDBParametersMessageRequestTypeDef,
     _OptionalDescribeDBParametersMessageRequestTypeDef,
 ):
     pass
 
+DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef = TypedDict(
+    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
+    {
+        "DBProxyName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeDBProxiesRequestRequestTypeDef = TypedDict(
     "DescribeDBProxiesRequestRequestTypeDef",
     {
         "DBProxyName": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef = TypedDict(
+    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
+    {
+        "DBProxyName": str,
+        "DBProxyEndpointName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBProxyEndpointsRequestRequestTypeDef = TypedDict(
     "DescribeDBProxyEndpointsRequestRequestTypeDef",
     {
         "DBProxyName": str,
         "DBProxyEndpointName": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
+    {
+        "DBProxyName": str,
+    },
+)
+_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
+    {
+        "TargetGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef(
+    _RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
+    _OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef",
     {
         "DBProxyName": str,
     },
 )
 _OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef = TypedDict(
@@ -4426,21 +4565,41 @@
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
-
 class DescribeDBProxyTargetGroupsRequestRequestTypeDef(
     _RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef,
     _OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
+    {
+        "DBProxyName": str,
+    },
+)
+_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
+    {
+        "TargetGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef(
+    _RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
+    _OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
+):
+    pass
 
 _RequiredDescribeDBProxyTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDBProxyTargetsRequestRequestTypeDef",
     {
         "DBProxyName": str,
     },
 )
@@ -4451,33 +4610,56 @@
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
-
 class DescribeDBProxyTargetsRequestRequestTypeDef(
     _RequiredDescribeDBProxyTargetsRequestRequestTypeDef,
     _OptionalDescribeDBProxyTargetsRequestRequestTypeDef,
 ):
     pass
 
+DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
+    {
+        "DBSecurityGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeDBSecurityGroupsMessageRequestTypeDef = TypedDict(
     "DescribeDBSecurityGroupsMessageRequestTypeDef",
     {
         "DBSecurityGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
+    {
+        "DBInstanceIdentifier": str,
+        "DBSnapshotIdentifier": str,
+        "SnapshotType": str,
+        "Filters": Sequence[FilterTypeDef],
+        "IncludeShared": bool,
+        "IncludePublic": bool,
+        "DbiResourceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeDBSnapshotsMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
@@ -4486,25 +4668,56 @@
         "IncludeShared": bool,
         "IncludePublic": bool,
         "DbiResourceId": str,
     },
     total=False,
 )
 
+DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
+    {
+        "DBSubnetGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBSubnetGroupsMessageRequestTypeDef = TypedDict(
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
     {
         "DBSubnetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
+    {
+        "DBParameterGroupFamily": str,
+    },
+)
+_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef(
+    _RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
+    _OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef",
     {
         "DBParameterGroupFamily": str,
     },
 )
 _OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef = TypedDict(
@@ -4513,21 +4726,40 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeEngineDefaultClusterParametersMessageRequestTypeDef(
     _RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef,
     _OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+    {
+        "DBParameterGroupFamily": str,
+    },
+)
+_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+    {
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef(
+    _RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
+    _OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
+):
+    pass
 
 _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef",
     {
         "DBParameterGroupFamily": str,
     },
 )
@@ -4537,42 +4769,65 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeEngineDefaultParametersMessageRequestTypeDef(
     _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef,
     _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef,
 ):
     pass
 
-
 DescribeEventCategoriesMessageRequestTypeDef = TypedDict(
     "DescribeEventCategoriesMessageRequestTypeDef",
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
+        "SourceType": SourceTypeType,
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
         "SourceType": SourceTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -4581,38 +4836,82 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef = TypedDict(
+    "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
+    {
+        "ExportTaskIdentifier": str,
+        "SourceArn": str,
+        "Filters": Sequence[FilterTypeDef],
+        "SourceType": ExportSourceTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeExportTasksMessageRequestTypeDef = TypedDict(
     "DescribeExportTasksMessageRequestTypeDef",
     {
         "ExportTaskIdentifier": str,
         "SourceArn": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
         "SourceType": ExportSourceTypeType,
     },
     total=False,
 )
 
+DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
+    {
+        "GlobalClusterIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGlobalClustersMessageRequestTypeDef = TypedDict(
     "DescribeGlobalClustersMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
+    {
+        "EngineName": str,
+    },
+)
+_OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
+    {
+        "MajorEngineVersion": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef(
+    _RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
+    _OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeOptionGroupOptionsMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeOptionGroupOptionsMessageRequestTypeDef",
     {
         "EngineName": str,
     },
 )
 _OptionalDescribeOptionGroupOptionsMessageRequestTypeDef = TypedDict(
@@ -4622,35 +4921,71 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeOptionGroupOptionsMessageRequestTypeDef(
     _RequiredDescribeOptionGroupOptionsMessageRequestTypeDef,
     _OptionalDescribeOptionGroupOptionsMessageRequestTypeDef,
 ):
     pass
 
+DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef = TypedDict(
+    "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
+    {
+        "OptionGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "EngineName": str,
+        "MajorEngineVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeOptionGroupsMessageRequestTypeDef = TypedDict(
     "DescribeOptionGroupsMessageRequestTypeDef",
     {
         "OptionGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
         "EngineName": str,
         "MajorEngineVersion": str,
     },
     total=False,
 )
 
+_RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
+    {
+        "Engine": str,
+    },
+)
+_OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
+    {
+        "EngineVersion": str,
+        "DBInstanceClass": str,
+        "LicenseModel": str,
+        "AvailabilityZoneGroup": str,
+        "Vpc": bool,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef(
+    _RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
+    _OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
     {
         "Engine": str,
     },
 )
 _OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
@@ -4664,650 +4999,150 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-
 class DescribeOrderableDBInstanceOptionsMessageRequestTypeDef(
     _RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
     _OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
 ):
     pass
 
+DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef = (
+    TypedDict(
+        "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
+        {
+            "ResourceIdentifier": str,
+            "Filters": Sequence[FilterTypeDef],
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
 
 DescribePendingMaintenanceActionsMessageRequestTypeDef = TypedDict(
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
-DescribeReservedDBInstancesMessageRequestTypeDef = TypedDict(
-    "DescribeReservedDBInstancesMessageRequestTypeDef",
+DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef = TypedDict(
+    "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
     {
         "ReservedDBInstanceId": str,
         "ReservedDBInstancesOfferingId": str,
         "DBInstanceClass": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MultiAZ": bool,
         "LeaseId": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeReservedDBInstancesOfferingsMessageRequestTypeDef = TypedDict(
-    "DescribeReservedDBInstancesOfferingsMessageRequestTypeDef",
+DescribeReservedDBInstancesMessageRequestTypeDef = TypedDict(
+    "DescribeReservedDBInstancesMessageRequestTypeDef",
     {
+        "ReservedDBInstanceId": str,
         "ReservedDBInstancesOfferingId": str,
         "DBInstanceClass": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MultiAZ": bool,
+        "LeaseId": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-DescribeSourceRegionsMessageRequestTypeDef = TypedDict(
-    "DescribeSourceRegionsMessageRequestTypeDef",
-    {
-        "RegionName": str,
-        "MaxRecords": int,
-        "Marker": str,
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceMessageRequestTypeDef = TypedDict(
-    "_RequiredListTagsForResourceMessageRequestTypeDef",
-    {
-        "ResourceName": str,
-    },
-)
-_OptionalListTagsForResourceMessageRequestTypeDef = TypedDict(
-    "_OptionalListTagsForResourceMessageRequestTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceMessageRequestTypeDef(
-    _RequiredListTagsForResourceMessageRequestTypeDef,
-    _OptionalListTagsForResourceMessageRequestTypeDef,
-):
-    pass
-
-
-DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef = TypedDict(
-    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
-    {
-        "BlueGreenDeploymentIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    {
-        "CertificateIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
-    {
-        "DBClusterIdentifier": str,
-    },
-)
-_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
-    {
-        "BacktrackIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef(
-    _RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
-    _OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
-):
-    pass
-
-
-DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef = TypedDict(
-    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "DBClusterEndpointIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
-    },
-)
-_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    {
-        "Source": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef(
-    _RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    _OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-):
-    pass
-
-
-DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "DBClusterSnapshotIdentifier": str,
-        "SnapshotType": str,
-        "Filters": Sequence[FilterTypeDef],
-        "IncludeShared": bool,
-        "IncludePublic": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef = TypedDict(
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "IncludeShared": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef = TypedDict(
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    {
-        "Engine": str,
-        "EngineVersion": str,
-        "DBParameterGroupFamily": str,
-        "Filters": Sequence[FilterTypeDef],
-        "DefaultOnly": bool,
-        "ListSupportedCharacterSets": bool,
-        "ListSupportedTimezones": bool,
-        "IncludeAll": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef = TypedDict(
-    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
-    {
-        "DbiResourceId": str,
-        "DBInstanceIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "DBInstanceAutomatedBackupsArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef = TypedDict(
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    {
-        "DBInstanceIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
-    {
-        "DBInstanceIdentifier": str,
-    },
-)
-_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
-    {
-        "FilenameContains": str,
-        "FileLastWritten": int,
-        "FileSize": int,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef(
-    _RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
-    _OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
-):
-    pass
-
-
-DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
-    {
-        "DBParameterGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
-    {
-        "DBParameterGroupName": str,
-    },
-)
-_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
-    {
-        "Source": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef(
-    _RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    _OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-):
-    pass
-
-
-DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef = TypedDict(
-    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
-    {
-        "DBProxyName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef = TypedDict(
-    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
-    {
-        "DBProxyName": str,
-        "DBProxyEndpointName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
-    {
-        "DBProxyName": str,
-    },
-)
-_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
-    {
-        "TargetGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef(
-    _RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
-    _OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
-    {
-        "DBProxyName": str,
-    },
-)
-_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
-    {
-        "TargetGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef(
-    _RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
-    _OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
-):
-    pass
-
-
-DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
-    {
-        "DBSecurityGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
-    {
-        "DBInstanceIdentifier": str,
-        "DBSnapshotIdentifier": str,
-        "SnapshotType": str,
-        "Filters": Sequence[FilterTypeDef],
-        "IncludeShared": bool,
-        "IncludePublic": bool,
-        "DbiResourceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
-    {
-        "DBSubnetGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
-    {
-        "DBParameterGroupFamily": str,
-    },
-)
-_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef(
-    _RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-    _OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
-        "DBParameterGroupFamily": str,
-    },
-)
-_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef(
-    _RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    _OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-):
-    pass
-
-
-DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    {
-        "SubscriptionName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    {
-        "SourceIdentifier": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "EventCategories": Sequence[str],
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef = TypedDict(
-    "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
-    {
-        "ExportTaskIdentifier": str,
-        "SourceArn": str,
-        "Filters": Sequence[FilterTypeDef],
-        "SourceType": ExportSourceTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    {
-        "GlobalClusterIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
-    {
-        "EngineName": str,
-    },
-)
-_OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
-    {
-        "MajorEngineVersion": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef(
-    _RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
-    _OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
-):
-    pass
-
-
-DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef = TypedDict(
-    "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
-    {
-        "OptionGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "EngineName": str,
-        "MajorEngineVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
-    {
-        "Engine": str,
-    },
-)
-_OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
-    {
-        "EngineVersion": str,
-        "DBInstanceClass": str,
-        "LicenseModel": str,
-        "AvailabilityZoneGroup": str,
-        "Vpc": bool,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef(
-    _RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    _OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-):
-    pass
-
-
-DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef = (
-    TypedDict(
-        "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
-        {
-            "ResourceIdentifier": str,
-            "Filters": Sequence[FilterTypeDef],
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef = TypedDict(
-    "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
+DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
     {
-        "ReservedDBInstanceId": str,
         "ReservedDBInstancesOfferingId": str,
         "DBInstanceClass": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MultiAZ": bool,
-        "LeaseId": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
+DescribeReservedDBInstancesOfferingsMessageRequestTypeDef = TypedDict(
+    "DescribeReservedDBInstancesOfferingsMessageRequestTypeDef",
     {
         "ReservedDBInstancesOfferingId": str,
         "DBInstanceClass": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MultiAZ": bool,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
 DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef = TypedDict(
     "DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef",
     {
         "RegionName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
-    "_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+DescribeSourceRegionsMessageRequestTypeDef = TypedDict(
+    "DescribeSourceRegionsMessageRequestTypeDef",
     {
-        "DBInstanceIdentifier": str,
-        "LogFileName": str,
+        "RegionName": str,
+        "MaxRecords": int,
+        "Marker": str,
+        "Filters": Sequence[FilterTypeDef],
     },
+    total=False,
 )
-_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
-    "_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+
+_RequiredListTagsForResourceMessageRequestTypeDef = TypedDict(
+    "_RequiredListTagsForResourceMessageRequestTypeDef",
+    {
+        "ResourceName": str,
+    },
+)
+_OptionalListTagsForResourceMessageRequestTypeDef = TypedDict(
+    "_OptionalListTagsForResourceMessageRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-
-class DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef(
-    _RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
-    _OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
+class ListTagsForResourceMessageRequestTypeDef(
+    _RequiredListTagsForResourceMessageRequestTypeDef,
+    _OptionalListTagsForResourceMessageRequestTypeDef,
 ):
     pass
 
-
 DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef = TypedDict(
     "DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
@@ -5438,41 +5273,41 @@
 )
 
 DescribeDBLogFilesResponseTypeDef = TypedDict(
     "DescribeDBLogFilesResponseTypeDef",
     {
         "DescribeDBLogFiles": List[DescribeDBLogFilesDetailsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventCategoriesMessageTypeDef = TypedDict(
     "EventCategoriesMessageTypeDef",
     {
         "EventCategoriesMapList": List[EventCategoriesMapTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventsMessageTypeDef = TypedDict(
     "EventsMessageTypeDef",
     {
         "Marker": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportTasksMessageTypeDef = TypedDict(
     "ExportTasksMessageTypeDef",
     {
         "Marker": str,
         "ExportTasks": List[ExportTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalClusterTypeDef = TypedDict(
     "GlobalClusterTypeDef",
     {
         "GlobalClusterIdentifier": str,
@@ -5519,21 +5354,19 @@
         "DBSecurityGroupMemberships": Sequence[str],
         "VpcSecurityGroupMemberships": Sequence[str],
         "OptionSettings": Sequence[OptionSettingTypeDef],
     },
     total=False,
 )
 
-
 class OptionConfigurationTypeDef(
     _RequiredOptionConfigurationTypeDef, _OptionalOptionConfigurationTypeDef
 ):
     pass
 
-
 OptionTypeDef = TypedDict(
     "OptionTypeDef",
     {
         "OptionName": str,
         "OptionDescription": str,
         "Persistent": bool,
         "Permanent": bool,
@@ -5621,90 +5454,90 @@
 )
 
 SourceRegionMessageTypeDef = TypedDict(
     "SourceRegionMessageTypeDef",
     {
         "Marker": str,
         "SourceRegions": List[SourceRegionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyDBClusterSnapshotResultTypeDef = TypedDict(
     "CopyDBClusterSnapshotResultTypeDef",
     {
         "DBClusterSnapshot": DBClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBClusterSnapshotResultTypeDef = TypedDict(
     "CreateDBClusterSnapshotResultTypeDef",
     {
         "DBClusterSnapshot": DBClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterSnapshotMessageTypeDef = TypedDict(
     "DBClusterSnapshotMessageTypeDef",
     {
         "Marker": str,
         "DBClusterSnapshots": List[DBClusterSnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBClusterSnapshotResultTypeDef = TypedDict(
     "DeleteDBClusterSnapshotResultTypeDef",
     {
         "DBClusterSnapshot": DBClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrderableDBInstanceOptionsMessageTypeDef = TypedDict(
     "OrderableDBInstanceOptionsMessageTypeDef",
     {
         "OrderableDBInstanceOptions": List[OrderableDBInstanceOptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBlueGreenDeploymentResponseTypeDef = TypedDict(
     "CreateBlueGreenDeploymentResponseTypeDef",
     {
         "BlueGreenDeployment": BlueGreenDeploymentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBlueGreenDeploymentResponseTypeDef = TypedDict(
     "DeleteBlueGreenDeploymentResponseTypeDef",
     {
         "BlueGreenDeployment": BlueGreenDeploymentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBlueGreenDeploymentsResponseTypeDef = TypedDict(
     "DescribeBlueGreenDeploymentsResponseTypeDef",
     {
         "BlueGreenDeployments": List[BlueGreenDeploymentTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SwitchoverBlueGreenDeploymentResponseTypeDef = TypedDict(
     "SwitchoverBlueGreenDeploymentResponseTypeDef",
     {
         "BlueGreenDeployment": BlueGreenDeploymentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterTypeDef = TypedDict(
     "DBClusterTypeDef",
     {
         "AllocatedStorage": int,
@@ -5774,295 +5607,296 @@
         "PerformanceInsightsEnabled": bool,
         "PerformanceInsightsKMSKeyId": str,
         "PerformanceInsightsRetentionPeriod": int,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationInfoTypeDef,
         "NetworkType": str,
         "DBSystemId": str,
         "MasterUserSecret": MasterUserSecretTypeDef,
+        "IOOptimizedNextAllowedModificationTime": datetime,
     },
     total=False,
 )
 
 DescribeDBProxyTargetGroupsResponseTypeDef = TypedDict(
     "DescribeDBProxyTargetGroupsResponseTypeDef",
     {
         "TargetGroups": List[DBProxyTargetGroupTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBProxyTargetGroupResponseTypeDef = TypedDict(
     "ModifyDBProxyTargetGroupResponseTypeDef",
     {
         "DBProxyTargetGroup": DBProxyTargetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyDBSnapshotResultTypeDef = TypedDict(
     "CopyDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBSnapshotResultTypeDef = TypedDict(
     "CreateDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBSnapshotMessageTypeDef = TypedDict(
     "DBSnapshotMessageTypeDef",
     {
         "Marker": str,
         "DBSnapshots": List[DBSnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBSnapshotResultTypeDef = TypedDict(
     "DeleteDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBSnapshotResultTypeDef = TypedDict(
     "ModifyDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEngineDefaultClusterParametersResultTypeDef = TypedDict(
     "DescribeEngineDefaultClusterParametersResultTypeDef",
     {
         "EngineDefaults": EngineDefaultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEngineDefaultParametersResultTypeDef = TypedDict(
     "DescribeEngineDefaultParametersResultTypeDef",
     {
         "EngineDefaults": EngineDefaultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBClusterSnapshotAttributesResultTypeDef = TypedDict(
     "DescribeDBClusterSnapshotAttributesResultTypeDef",
     {
         "DBClusterSnapshotAttributesResult": DBClusterSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBClusterSnapshotAttributeResultTypeDef = TypedDict(
     "ModifyDBClusterSnapshotAttributeResultTypeDef",
     {
         "DBClusterSnapshotAttributesResult": DBClusterSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBEngineVersionMessageTypeDef = TypedDict(
     "DBEngineVersionMessageTypeDef",
     {
         "Marker": str,
         "DBEngineVersions": List[DBEngineVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBInstanceAutomatedBackupMessageTypeDef = TypedDict(
     "DBInstanceAutomatedBackupMessageTypeDef",
     {
         "Marker": str,
         "DBInstanceAutomatedBackups": List[DBInstanceAutomatedBackupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBInstanceAutomatedBackupResultTypeDef = TypedDict(
     "DeleteDBInstanceAutomatedBackupResultTypeDef",
     {
         "DBInstanceAutomatedBackup": DBInstanceAutomatedBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDBInstanceAutomatedBackupsReplicationResultTypeDef = TypedDict(
     "StartDBInstanceAutomatedBackupsReplicationResultTypeDef",
     {
         "DBInstanceAutomatedBackup": DBInstanceAutomatedBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopDBInstanceAutomatedBackupsReplicationResultTypeDef = TypedDict(
     "StopDBInstanceAutomatedBackupsReplicationResultTypeDef",
     {
         "DBInstanceAutomatedBackup": DBInstanceAutomatedBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBProxyTargetsResponseTypeDef = TypedDict(
     "DescribeDBProxyTargetsResponseTypeDef",
     {
         "Targets": List[DBProxyTargetTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterDBProxyTargetsResponseTypeDef = TypedDict(
     "RegisterDBProxyTargetsResponseTypeDef",
     {
         "DBProxyTargets": List[DBProxyTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBProxyResponseTypeDef = TypedDict(
     "CreateDBProxyResponseTypeDef",
     {
         "DBProxy": DBProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBProxyResponseTypeDef = TypedDict(
     "DeleteDBProxyResponseTypeDef",
     {
         "DBProxy": DBProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBProxiesResponseTypeDef = TypedDict(
     "DescribeDBProxiesResponseTypeDef",
     {
         "DBProxies": List[DBProxyTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBProxyResponseTypeDef = TypedDict(
     "ModifyDBProxyResponseTypeDef",
     {
         "DBProxy": DBProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthorizeDBSecurityGroupIngressResultTypeDef = TypedDict(
     "AuthorizeDBSecurityGroupIngressResultTypeDef",
     {
         "DBSecurityGroup": DBSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBSecurityGroupResultTypeDef = TypedDict(
     "CreateDBSecurityGroupResultTypeDef",
     {
         "DBSecurityGroup": DBSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBSecurityGroupMessageTypeDef = TypedDict(
     "DBSecurityGroupMessageTypeDef",
     {
         "Marker": str,
         "DBSecurityGroups": List[DBSecurityGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RevokeDBSecurityGroupIngressResultTypeDef = TypedDict(
     "RevokeDBSecurityGroupIngressResultTypeDef",
     {
         "DBSecurityGroup": DBSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBSnapshotAttributesResultTypeDef = TypedDict(
     "DescribeDBSnapshotAttributesResultTypeDef",
     {
         "DBSnapshotAttributesResult": DBSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBSnapshotAttributeResultTypeDef = TypedDict(
     "ModifyDBSnapshotAttributeResultTypeDef",
     {
         "DBSnapshotAttributesResult": DBSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGlobalClusterResultTypeDef = TypedDict(
     "CreateGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGlobalClusterResultTypeDef = TypedDict(
     "DeleteGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverGlobalClusterResultTypeDef = TypedDict(
     "FailoverGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalClustersMessageTypeDef = TypedDict(
     "GlobalClustersMessageTypeDef",
     {
         "Marker": str,
         "GlobalClusters": List[GlobalClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyGlobalClusterResultTypeDef = TypedDict(
     "ModifyGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveFromGlobalClusterResultTypeDef = TypedDict(
     "RemoveFromGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptionGroupOptionTypeDef = TypedDict(
     "OptionGroupOptionTypeDef",
     {
         "Name": str,
@@ -6098,21 +5932,19 @@
         "OptionsToInclude": Sequence[OptionConfigurationTypeDef],
         "OptionsToRemove": Sequence[str],
         "ApplyImmediately": bool,
     },
     total=False,
 )
 
-
 class ModifyOptionGroupMessageRequestTypeDef(
     _RequiredModifyOptionGroupMessageRequestTypeDef, _OptionalModifyOptionGroupMessageRequestTypeDef
 ):
     pass
 
-
 OptionGroupTypeDef = TypedDict(
     "OptionGroupTypeDef",
     {
         "OptionGroupName": str,
         "OptionGroupDescription": str,
         "EngineName": str,
         "MajorEngineVersion": str,
@@ -6141,24 +5973,24 @@
     total=False,
 )
 
 ApplyPendingMaintenanceActionResultTypeDef = TypedDict(
     "ApplyPendingMaintenanceActionResultTypeDef",
     {
         "ResourcePendingMaintenanceActions": ResourcePendingMaintenanceActionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PendingMaintenanceActionsMessageTypeDef = TypedDict(
     "PendingMaintenanceActionsMessageTypeDef",
     {
         "PendingMaintenanceActions": List[ResourcePendingMaintenanceActionsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidDBInstanceModificationsMessageTypeDef = TypedDict(
     "ValidDBInstanceModificationsMessageTypeDef",
     {
         "Storage": List[ValidStorageOptionsTypeDef],
@@ -6167,180 +5999,180 @@
     total=False,
 )
 
 PurchaseReservedDBInstancesOfferingResultTypeDef = TypedDict(
     "PurchaseReservedDBInstancesOfferingResultTypeDef",
     {
         "ReservedDBInstance": ReservedDBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedDBInstanceMessageTypeDef = TypedDict(
     "ReservedDBInstanceMessageTypeDef",
     {
         "Marker": str,
         "ReservedDBInstances": List[ReservedDBInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedDBInstancesOfferingMessageTypeDef = TypedDict(
     "ReservedDBInstancesOfferingMessageTypeDef",
     {
         "Marker": str,
         "ReservedDBInstancesOfferings": List[ReservedDBInstancesOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBClusterResultTypeDef = TypedDict(
     "CreateDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterMessageTypeDef = TypedDict(
     "DBClusterMessageTypeDef",
     {
         "Marker": str,
         "DBClusters": List[DBClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBClusterResultTypeDef = TypedDict(
     "DeleteDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverDBClusterResultTypeDef = TypedDict(
     "FailoverDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBClusterResultTypeDef = TypedDict(
     "ModifyDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PromoteReadReplicaDBClusterResultTypeDef = TypedDict(
     "PromoteReadReplicaDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootDBClusterResultTypeDef = TypedDict(
     "RebootDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBClusterFromS3ResultTypeDef = TypedDict(
     "RestoreDBClusterFromS3ResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBClusterFromSnapshotResultTypeDef = TypedDict(
     "RestoreDBClusterFromSnapshotResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBClusterToPointInTimeResultTypeDef = TypedDict(
     "RestoreDBClusterToPointInTimeResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDBClusterResultTypeDef = TypedDict(
     "StartDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopDBClusterResultTypeDef = TypedDict(
     "StopDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptionGroupOptionsMessageTypeDef = TypedDict(
     "OptionGroupOptionsMessageTypeDef",
     {
         "OptionGroupOptions": List[OptionGroupOptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyOptionGroupResultTypeDef = TypedDict(
     "CopyOptionGroupResultTypeDef",
     {
         "OptionGroup": OptionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOptionGroupResultTypeDef = TypedDict(
     "CreateOptionGroupResultTypeDef",
     {
         "OptionGroup": OptionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyOptionGroupResultTypeDef = TypedDict(
     "ModifyOptionGroupResultTypeDef",
     {
         "OptionGroup": OptionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptionGroupsTypeDef = TypedDict(
     "OptionGroupsTypeDef",
     {
         "OptionGroupsList": List[OptionGroupTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBSubnetGroupResultTypeDef = TypedDict(
     "CreateDBSubnetGroupResultTypeDef",
     {
         "DBSubnetGroup": DBSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBInstanceTypeDef = TypedDict(
     "DBInstanceTypeDef",
     {
         "DBInstanceIdentifier": str,
@@ -6421,140 +6253,141 @@
         "BackupTarget": str,
         "NetworkType": str,
         "ActivityStreamPolicyStatus": ActivityStreamPolicyStatusType,
         "StorageThroughput": int,
         "DBSystemId": str,
         "MasterUserSecret": MasterUserSecretTypeDef,
         "CertificateDetails": CertificateDetailsTypeDef,
+        "ReadReplicaSourceDBClusterIdentifier": str,
     },
     total=False,
 )
 
 DBSubnetGroupMessageTypeDef = TypedDict(
     "DBSubnetGroupMessageTypeDef",
     {
         "Marker": str,
         "DBSubnetGroups": List[DBSubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBSubnetGroupResultTypeDef = TypedDict(
     "ModifyDBSubnetGroupResultTypeDef",
     {
         "DBSubnetGroup": DBSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeValidDBInstanceModificationsResultTypeDef = TypedDict(
     "DescribeValidDBInstanceModificationsResultTypeDef",
     {
         "ValidDBInstanceModificationsMessage": ValidDBInstanceModificationsMessageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBInstanceReadReplicaResultTypeDef = TypedDict(
     "CreateDBInstanceReadReplicaResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBInstanceResultTypeDef = TypedDict(
     "CreateDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBInstanceMessageTypeDef = TypedDict(
     "DBInstanceMessageTypeDef",
     {
         "Marker": str,
         "DBInstances": List[DBInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBInstanceResultTypeDef = TypedDict(
     "DeleteDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBInstanceResultTypeDef = TypedDict(
     "ModifyDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PromoteReadReplicaResultTypeDef = TypedDict(
     "PromoteReadReplicaResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootDBInstanceResultTypeDef = TypedDict(
     "RebootDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBInstanceFromDBSnapshotResultTypeDef = TypedDict(
     "RestoreDBInstanceFromDBSnapshotResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBInstanceFromS3ResultTypeDef = TypedDict(
     "RestoreDBInstanceFromS3ResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBInstanceToPointInTimeResultTypeDef = TypedDict(
     "RestoreDBInstanceToPointInTimeResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDBInstanceResultTypeDef = TypedDict(
     "StartDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopDBInstanceResultTypeDef = TypedDict(
     "StopDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SwitchoverReadReplicaResultTypeDef = TypedDict(
     "SwitchoverReadReplicaResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/type_defs.pyi` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_rds.type_defs import AccountQuotaTypeDef
 
     data: AccountQuotaTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Sequence, Union
+from typing import Dict, List, Optional, Sequence, Union
 
 from .literals import (
     ActivityStreamModeType,
     ActivityStreamPolicyStatusType,
     ActivityStreamStatusType,
     ApplyMethodType,
     AuditPolicyStateType,
@@ -45,17 +45,17 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AccountQuotaTypeDef",
-    "ResponseMetadataTypeDef",
     "AddRoleToDBClusterMessageRequestTypeDef",
     "AddRoleToDBInstanceMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionMessageRequestTypeDef",
     "EventSubscriptionTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
     "AuthorizeDBSecurityGroupIngressMessageRequestTypeDef",
@@ -79,18 +79,22 @@
     "ServerlessV2ScalingConfigurationTypeDef",
     "ProcessorFeatureTypeDef",
     "DBProxyEndpointTypeDef",
     "UserAuthConfigTypeDef",
     "CreateGlobalClusterMessageRequestTypeDef",
     "CustomDBEngineVersionAMITypeDef",
     "DBClusterBacktrackTypeDef",
+    "DBClusterBacktrackResponseMetadataTypeDef",
+    "DBClusterCapacityInfoTypeDef",
     "DBClusterEndpointTypeDef",
+    "DBClusterEndpointResponseMetadataTypeDef",
     "DBClusterMemberTypeDef",
     "DBClusterOptionGroupStatusTypeDef",
     "ParameterTypeDef",
+    "DBClusterParameterGroupNameMessageTypeDef",
     "DBClusterRoleTypeDef",
     "DBClusterSnapshotAttributeTypeDef",
     "DomainMembershipTypeDef",
     "MasterUserSecretTypeDef",
     "ScalingConfigurationInfoTypeDef",
     "ServerlessV2ScalingConfigurationInfoTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
@@ -100,14 +104,15 @@
     "RestoreWindowTypeDef",
     "DBInstanceRoleTypeDef",
     "DBInstanceStatusInfoTypeDef",
     "DBParameterGroupStatusTypeDef",
     "DBSecurityGroupMembershipTypeDef",
     "EndpointTypeDef",
     "OptionGroupMembershipTypeDef",
+    "DBParameterGroupNameMessageTypeDef",
     "TargetHealthTypeDef",
     "UserAuthConfigInfoTypeDef",
     "EC2SecurityGroupTypeDef",
     "IPRangeTypeDef",
     "DBSnapshotAttributeTypeDef",
     "DeleteBlueGreenDeploymentRequestRequestTypeDef",
     "DeleteCustomDBEngineVersionMessageRequestTypeDef",
@@ -124,83 +129,80 @@
     "DeleteDBSnapshotMessageRequestTypeDef",
     "DeleteDBSubnetGroupMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteGlobalClusterMessageRequestTypeDef",
     "DeleteOptionGroupMessageRequestTypeDef",
     "DeregisterDBProxyTargetsRequestRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeDBLogFilesDetailsTypeDef",
     "DescribeDBSnapshotAttributesMessageRequestTypeDef",
     "DescribeValidDBInstanceModificationsMessageRequestTypeDef",
     "DoubleRangeTypeDef",
+    "DownloadDBLogFilePortionDetailsTypeDef",
+    "DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
     "DownloadDBLogFilePortionMessageRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventCategoriesMapTypeDef",
     "EventTypeDef",
+    "ExportTaskResponseMetadataTypeDef",
     "ExportTaskTypeDef",
     "FailoverDBClusterMessageRequestTypeDef",
     "FailoverGlobalClusterMessageRequestTypeDef",
     "FailoverStateTypeDef",
     "GlobalClusterMemberTypeDef",
     "MinimumEngineVersionPerAllowedValueTypeDef",
     "ModifyActivityStreamRequestRequestTypeDef",
+    "ModifyActivityStreamResponseTypeDef",
     "ModifyCertificatesMessageRequestTypeDef",
     "ModifyCurrentDBClusterCapacityMessageRequestTypeDef",
     "ModifyCustomDBEngineVersionMessageRequestTypeDef",
     "ModifyDBClusterEndpointMessageRequestTypeDef",
     "ModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBProxyEndpointRequestRequestTypeDef",
     "ModifyDBSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBSnapshotMessageRequestTypeDef",
     "ModifyDBSubnetGroupMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyGlobalClusterMessageRequestTypeDef",
     "OptionSettingTypeDef",
     "OptionVersionTypeDef",
     "OutpostTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
     "PromoteReadReplicaDBClusterMessageRequestTypeDef",
     "PromoteReadReplicaMessageRequestTypeDef",
     "RangeTypeDef",
     "RebootDBClusterMessageRequestTypeDef",
     "RebootDBInstanceMessageRequestTypeDef",
     "RecurringChargeTypeDef",
     "RegisterDBProxyTargetsRequestRequestTypeDef",
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     "RemoveRoleFromDBClusterMessageRequestTypeDef",
     "RemoveRoleFromDBInstanceMessageRequestTypeDef",
     "RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeDBSecurityGroupIngressMessageRequestTypeDef",
     "SourceRegionTypeDef",
     "StartActivityStreamRequestRequestTypeDef",
+    "StartActivityStreamResponseTypeDef",
     "StartDBClusterMessageRequestTypeDef",
     "StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef",
     "StartDBInstanceMessageRequestTypeDef",
     "StartExportTaskMessageRequestTypeDef",
     "StopActivityStreamRequestRequestTypeDef",
+    "StopActivityStreamResponseTypeDef",
     "StopDBClusterMessageRequestTypeDef",
     "StopDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef",
     "StopDBInstanceMessageRequestTypeDef",
     "SwitchoverBlueGreenDeploymentRequestRequestTypeDef",
     "SwitchoverReadReplicaMessageRequestTypeDef",
     "AccountAttributesMessageTypeDef",
-    "DBClusterBacktrackResponseMetadataTypeDef",
-    "DBClusterCapacityInfoTypeDef",
-    "DBClusterEndpointResponseMetadataTypeDef",
-    "DBClusterParameterGroupNameMessageTypeDef",
-    "DBParameterGroupNameMessageTypeDef",
-    "DownloadDBLogFilePortionDetailsTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportTaskResponseMetadataTypeDef",
-    "ModifyActivityStreamResponseTypeDef",
-    "StartActivityStreamResponseTypeDef",
-    "StopActivityStreamResponseTypeDef",
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     "CreateEventSubscriptionResultTypeDef",
     "DeleteEventSubscriptionResultTypeDef",
     "EventSubscriptionsMessageTypeDef",
     "ModifyEventSubscriptionResultTypeDef",
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
@@ -269,85 +271,84 @@
     "DBEngineVersionResponseMetadataTypeDef",
     "DBEngineVersionTypeDef",
     "DBInstanceAutomatedBackupTypeDef",
     "DBProxyTargetTypeDef",
     "DBProxyTypeDef",
     "DBSecurityGroupTypeDef",
     "DBSnapshotAttributesResultTypeDef",
+    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
     "DescribeBlueGreenDeploymentsRequestRequestTypeDef",
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
     "DescribeCertificatesMessageRequestTypeDef",
+    "DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
     "DescribeDBClusterBacktracksMessageRequestTypeDef",
+    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
     "DescribeDBClusterEndpointsMessageRequestTypeDef",
+    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
     "DescribeDBClusterParameterGroupsMessageRequestTypeDef",
+    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
     "DescribeDBClusterParametersMessageRequestTypeDef",
+    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
     "DescribeDBClusterSnapshotsMessageRequestTypeDef",
+    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
     "DescribeDBClustersMessageRequestTypeDef",
+    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
     "DescribeDBEngineVersionsMessageRequestTypeDef",
+    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
     "DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef",
+    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
     "DescribeDBInstancesMessageRequestTypeDef",
+    "DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
     "DescribeDBLogFilesMessageRequestTypeDef",
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
     "DescribeDBParameterGroupsMessageRequestTypeDef",
+    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
     "DescribeDBParametersMessageRequestTypeDef",
+    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
     "DescribeDBProxiesRequestRequestTypeDef",
+    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
     "DescribeDBProxyEndpointsRequestRequestTypeDef",
+    "DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
     "DescribeDBProxyTargetGroupsRequestRequestTypeDef",
+    "DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
     "DescribeDBProxyTargetsRequestRequestTypeDef",
+    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
     "DescribeDBSecurityGroupsMessageRequestTypeDef",
+    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
     "DescribeDBSnapshotsMessageRequestTypeDef",
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
+    "DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
     "DescribeEngineDefaultClusterParametersMessageRequestTypeDef",
+    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     "DescribeEngineDefaultParametersMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
     "DescribeExportTasksMessageRequestTypeDef",
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     "DescribeGlobalClustersMessageRequestTypeDef",
+    "DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
     "DescribeOptionGroupOptionsMessageRequestTypeDef",
+    "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
     "DescribeOptionGroupsMessageRequestTypeDef",
+    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     "DescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
+    "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
     "DescribeReservedDBInstancesMessageRequestTypeDef",
+    "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
     "DescribeReservedDBInstancesOfferingsMessageRequestTypeDef",
+    "DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef",
     "DescribeSourceRegionsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
-    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    "DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
-    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    "DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
-    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
-    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
-    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
-    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
-    "DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
-    "DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
-    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
-    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
-    "DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
-    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    "DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
-    "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
-    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
-    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
-    "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
-    "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
-    "DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef",
-    "DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
     "DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef",
     "DescribeDBClusterSnapshotsMessageDBClusterSnapshotDeletedWaitTypeDef",
     "DescribeDBClustersMessageDBClusterAvailableWaitTypeDef",
     "DescribeDBClustersMessageDBClusterDeletedWaitTypeDef",
     "DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef",
     "DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef",
     "DescribeDBSnapshotsMessageDBSnapshotAvailableWaitTypeDef",
@@ -464,25 +465,14 @@
         "AccountQuotaName": str,
         "Used": int,
         "Max": int,
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
 _RequiredAddRoleToDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredAddRoleToDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "RoleArn": str,
     },
 )
@@ -490,20 +480,22 @@
     "_OptionalAddRoleToDBClusterMessageRequestTypeDef",
     {
         "FeatureName": str,
     },
     total=False,
 )
 
+
 class AddRoleToDBClusterMessageRequestTypeDef(
     _RequiredAddRoleToDBClusterMessageRequestTypeDef,
     _OptionalAddRoleToDBClusterMessageRequestTypeDef,
 ):
     pass
 
+
 AddRoleToDBInstanceMessageRequestTypeDef = TypedDict(
     "AddRoleToDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "RoleArn": str,
         "FeatureName": str,
     },
@@ -565,20 +557,22 @@
         "EC2SecurityGroupName": str,
         "EC2SecurityGroupId": str,
         "EC2SecurityGroupOwnerId": str,
     },
     total=False,
 )
 
+
 class AuthorizeDBSecurityGroupIngressMessageRequestTypeDef(
     _RequiredAuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
     _OptionalAuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
 ):
     pass
 
+
 AvailabilityZoneTypeDef = TypedDict(
     "AvailabilityZoneTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
@@ -605,20 +599,22 @@
     {
         "Force": bool,
         "UseEarliestTimeOnPointInTimeUnavailable": bool,
     },
     total=False,
 )
 
+
 class BacktrackDBClusterMessageRequestTypeDef(
     _RequiredBacktrackDBClusterMessageRequestTypeDef,
     _OptionalBacktrackDBClusterMessageRequestTypeDef,
 ):
     pass
 
+
 BlueGreenDeploymentTaskTypeDef = TypedDict(
     "BlueGreenDeploymentTaskTypeDef",
     {
         "Name": str,
         "Status": str,
     },
     total=False,
@@ -681,25 +677,27 @@
         "Port": int,
         "DBUsername": str,
     },
 )
 _OptionalClientGenerateDbAuthTokenRequestTypeDef = TypedDict(
     "_OptionalClientGenerateDbAuthTokenRequestTypeDef",
     {
-        "Region": str,
+        "Region": Optional[str],
     },
     total=False,
 )
 
+
 class ClientGenerateDbAuthTokenRequestTypeDef(
     _RequiredClientGenerateDbAuthTokenRequestTypeDef,
     _OptionalClientGenerateDbAuthTokenRequestTypeDef,
 ):
     pass
 
+
 CloudwatchLogsExportConfigurationTypeDef = TypedDict(
     "CloudwatchLogsExportConfigurationTypeDef",
     {
         "EnableLogTypes": Sequence[str],
         "DisableLogTypes": Sequence[str],
     },
     total=False,
@@ -854,14 +852,39 @@
         "BacktrackedFrom": datetime,
         "BacktrackRequestCreationTime": datetime,
         "Status": str,
     },
     total=False,
 )
 
+DBClusterBacktrackResponseMetadataTypeDef = TypedDict(
+    "DBClusterBacktrackResponseMetadataTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "BacktrackIdentifier": str,
+        "BacktrackTo": datetime,
+        "BacktrackedFrom": datetime,
+        "BacktrackRequestCreationTime": datetime,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DBClusterCapacityInfoTypeDef = TypedDict(
+    "DBClusterCapacityInfoTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "PendingCapacity": int,
+        "CurrentCapacity": int,
+        "SecondsBeforeTimeout": int,
+        "TimeoutAction": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DBClusterEndpointTypeDef = TypedDict(
     "DBClusterEndpointTypeDef",
     {
         "DBClusterEndpointIdentifier": str,
         "DBClusterIdentifier": str,
         "DBClusterEndpointResourceIdentifier": str,
         "Endpoint": str,
@@ -871,14 +894,31 @@
         "StaticMembers": List[str],
         "ExcludedMembers": List[str],
         "DBClusterEndpointArn": str,
     },
     total=False,
 )
 
+DBClusterEndpointResponseMetadataTypeDef = TypedDict(
+    "DBClusterEndpointResponseMetadataTypeDef",
+    {
+        "DBClusterEndpointIdentifier": str,
+        "DBClusterIdentifier": str,
+        "DBClusterEndpointResourceIdentifier": str,
+        "Endpoint": str,
+        "Status": str,
+        "EndpointType": str,
+        "CustomEndpointType": str,
+        "StaticMembers": List[str],
+        "ExcludedMembers": List[str],
+        "DBClusterEndpointArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DBClusterMemberTypeDef = TypedDict(
     "DBClusterMemberTypeDef",
     {
         "DBInstanceIdentifier": str,
         "IsClusterWriter": bool,
         "DBClusterParameterGroupStatus": str,
         "PromotionTier": int,
@@ -909,14 +949,22 @@
         "MinimumEngineVersion": str,
         "ApplyMethod": ApplyMethodType,
         "SupportedEngineModes": List[str],
     },
     total=False,
 )
 
+DBClusterParameterGroupNameMessageTypeDef = TypedDict(
+    "DBClusterParameterGroupNameMessageTypeDef",
+    {
+        "DBClusterParameterGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DBClusterRoleTypeDef = TypedDict(
     "DBClusterRoleTypeDef",
     {
         "RoleArn": str,
         "Status": str,
         "FeatureName": str,
     },
@@ -1079,14 +1127,22 @@
     {
         "OptionGroupName": str,
         "Status": str,
     },
     total=False,
 )
 
+DBParameterGroupNameMessageTypeDef = TypedDict(
+    "DBParameterGroupNameMessageTypeDef",
+    {
+        "DBParameterGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TargetHealthTypeDef = TypedDict(
     "TargetHealthTypeDef",
     {
         "State": TargetStateType,
         "Reason": TargetHealthReasonType,
         "Description": str,
     },
@@ -1145,20 +1201,22 @@
     "_OptionalDeleteBlueGreenDeploymentRequestRequestTypeDef",
     {
         "DeleteTarget": bool,
     },
     total=False,
 )
 
+
 class DeleteBlueGreenDeploymentRequestRequestTypeDef(
     _RequiredDeleteBlueGreenDeploymentRequestRequestTypeDef,
     _OptionalDeleteBlueGreenDeploymentRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteCustomDBEngineVersionMessageRequestTypeDef = TypedDict(
     "DeleteCustomDBEngineVersionMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
     },
 )
@@ -1181,19 +1239,21 @@
     {
         "SkipFinalSnapshot": bool,
         "FinalDBSnapshotIdentifier": str,
     },
     total=False,
 )
 
+
 class DeleteDBClusterMessageRequestTypeDef(
     _RequiredDeleteDBClusterMessageRequestTypeDef, _OptionalDeleteDBClusterMessageRequestTypeDef
 ):
     pass
 
+
 DeleteDBClusterParameterGroupMessageRequestTypeDef = TypedDict(
     "DeleteDBClusterParameterGroupMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
     },
 )
 
@@ -1225,19 +1285,21 @@
         "SkipFinalSnapshot": bool,
         "FinalDBSnapshotIdentifier": str,
         "DeleteAutomatedBackups": bool,
     },
     total=False,
 )
 
+
 class DeleteDBInstanceMessageRequestTypeDef(
     _RequiredDeleteDBInstanceMessageRequestTypeDef, _OptionalDeleteDBInstanceMessageRequestTypeDef
 ):
     pass
 
+
 DeleteDBParameterGroupMessageRequestTypeDef = TypedDict(
     "DeleteDBParameterGroupMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
     },
 )
 
@@ -1309,38 +1371,30 @@
         "TargetGroupName": str,
         "DBInstanceIdentifiers": Sequence[str],
         "DBClusterIdentifiers": Sequence[str],
     },
     total=False,
 )
 
+
 class DeregisterDBProxyTargetsRequestRequestTypeDef(
     _RequiredDeregisterDBProxyTargetsRequestRequestTypeDef,
     _OptionalDeregisterDBProxyTargetsRequestRequestTypeDef,
 ):
     pass
 
+
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
         "Values": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 DescribeDBClusterSnapshotAttributesMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
     },
 )
 
@@ -1382,14 +1436,47 @@
     {
         "From": float,
         "To": float,
     },
     total=False,
 )
 
+DownloadDBLogFilePortionDetailsTypeDef = TypedDict(
+    "DownloadDBLogFilePortionDetailsTypeDef",
+    {
+        "LogFileData": str,
+        "Marker": str,
+        "AdditionalDataPending": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
+    "_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+    {
+        "DBInstanceIdentifier": str,
+        "LogFileName": str,
+    },
+)
+_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
+    "_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef(
+    _RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
+    _OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDownloadDBLogFilePortionMessageRequestTypeDef = TypedDict(
     "_RequiredDownloadDBLogFilePortionMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "LogFileName": str,
     },
 )
@@ -1398,20 +1485,29 @@
     {
         "Marker": str,
         "NumberOfLines": int,
     },
     total=False,
 )
 
+
 class DownloadDBLogFilePortionMessageRequestTypeDef(
     _RequiredDownloadDBLogFilePortionMessageRequestTypeDef,
     _OptionalDownloadDBLogFilePortionMessageRequestTypeDef,
 ):
     pass
 
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventCategoriesMapTypeDef = TypedDict(
     "EventCategoriesMapTypeDef",
     {
         "SourceType": str,
         "EventCategories": List[str],
     },
     total=False,
@@ -1426,14 +1522,37 @@
         "EventCategories": List[str],
         "Date": datetime,
         "SourceArn": str,
     },
     total=False,
 )
 
+ExportTaskResponseMetadataTypeDef = TypedDict(
+    "ExportTaskResponseMetadataTypeDef",
+    {
+        "ExportTaskIdentifier": str,
+        "SourceArn": str,
+        "ExportOnly": List[str],
+        "SnapshotTime": datetime,
+        "TaskStartTime": datetime,
+        "TaskEndTime": datetime,
+        "S3Bucket": str,
+        "S3Prefix": str,
+        "IamRoleArn": str,
+        "KmsKeyId": str,
+        "Status": str,
+        "PercentProgress": int,
+        "TotalExtractedDataInGB": int,
+        "FailureCause": str,
+        "WarningMessage": str,
+        "SourceType": ExportSourceTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportTaskTypeDef = TypedDict(
     "ExportTaskTypeDef",
     {
         "ExportTaskIdentifier": str,
         "SourceArn": str,
         "ExportOnly": List[str],
         "SnapshotTime": datetime,
@@ -1463,19 +1582,21 @@
     "_OptionalFailoverDBClusterMessageRequestTypeDef",
     {
         "TargetDBInstanceIdentifier": str,
     },
     total=False,
 )
 
+
 class FailoverDBClusterMessageRequestTypeDef(
     _RequiredFailoverDBClusterMessageRequestTypeDef, _OptionalFailoverDBClusterMessageRequestTypeDef
 ):
     pass
 
+
 FailoverGlobalClusterMessageRequestTypeDef = TypedDict(
     "FailoverGlobalClusterMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "TargetDbClusterIdentifier": str,
     },
 )
@@ -1515,14 +1636,27 @@
     {
         "ResourceArn": str,
         "AuditPolicyState": AuditPolicyStateType,
     },
     total=False,
 )
 
+ModifyActivityStreamResponseTypeDef = TypedDict(
+    "ModifyActivityStreamResponseTypeDef",
+    {
+        "KmsKeyId": str,
+        "KinesisStreamName": str,
+        "Status": ActivityStreamStatusType,
+        "Mode": ActivityStreamModeType,
+        "EngineNativeAuditFieldsIncluded": bool,
+        "PolicyStatus": ActivityStreamPolicyStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ModifyCertificatesMessageRequestTypeDef = TypedDict(
     "ModifyCertificatesMessageRequestTypeDef",
     {
         "CertificateIdentifier": str,
         "RemoveCustomerOverride": bool,
     },
     total=False,
@@ -1540,20 +1674,22 @@
         "Capacity": int,
         "SecondsBeforeTimeout": int,
         "TimeoutAction": str,
     },
     total=False,
 )
 
+
 class ModifyCurrentDBClusterCapacityMessageRequestTypeDef(
     _RequiredModifyCurrentDBClusterCapacityMessageRequestTypeDef,
     _OptionalModifyCurrentDBClusterCapacityMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyCustomDBEngineVersionMessageRequestTypeDef = TypedDict(
     "_RequiredModifyCustomDBEngineVersionMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
     },
 )
@@ -1562,20 +1698,22 @@
     {
         "Description": str,
         "Status": CustomEngineVersionStatusType,
     },
     total=False,
 )
 
+
 class ModifyCustomDBEngineVersionMessageRequestTypeDef(
     _RequiredModifyCustomDBEngineVersionMessageRequestTypeDef,
     _OptionalModifyCustomDBEngineVersionMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyDBClusterEndpointMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterEndpointMessageRequestTypeDef",
     {
         "DBClusterEndpointIdentifier": str,
     },
 )
 _OptionalModifyDBClusterEndpointMessageRequestTypeDef = TypedDict(
@@ -1584,20 +1722,22 @@
         "EndpointType": str,
         "StaticMembers": Sequence[str],
         "ExcludedMembers": Sequence[str],
     },
     total=False,
 )
 
+
 class ModifyDBClusterEndpointMessageRequestTypeDef(
     _RequiredModifyDBClusterEndpointMessageRequestTypeDef,
     _OptionalModifyDBClusterEndpointMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "AttributeName": str,
     },
 )
@@ -1606,20 +1746,22 @@
     {
         "ValuesToAdd": Sequence[str],
         "ValuesToRemove": Sequence[str],
     },
     total=False,
 )
 
+
 class ModifyDBClusterSnapshotAttributeMessageRequestTypeDef(
     _RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     _OptionalModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyDBProxyEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredModifyDBProxyEndpointRequestRequestTypeDef",
     {
         "DBProxyEndpointName": str,
     },
 )
 _OptionalModifyDBProxyEndpointRequestRequestTypeDef = TypedDict(
@@ -1627,20 +1769,22 @@
     {
         "NewDBProxyEndpointName": str,
         "VpcSecurityGroupIds": Sequence[str],
     },
     total=False,
 )
 
+
 class ModifyDBProxyEndpointRequestRequestTypeDef(
     _RequiredModifyDBProxyEndpointRequestRequestTypeDef,
     _OptionalModifyDBProxyEndpointRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyDBSnapshotAttributeMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBSnapshotAttributeMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
         "AttributeName": str,
     },
 )
@@ -1649,20 +1793,22 @@
     {
         "ValuesToAdd": Sequence[str],
         "ValuesToRemove": Sequence[str],
     },
     total=False,
 )
 
+
 class ModifyDBSnapshotAttributeMessageRequestTypeDef(
     _RequiredModifyDBSnapshotAttributeMessageRequestTypeDef,
     _OptionalModifyDBSnapshotAttributeMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBSnapshotMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
     },
 )
 _OptionalModifyDBSnapshotMessageRequestTypeDef = TypedDict(
@@ -1670,19 +1816,21 @@
     {
         "EngineVersion": str,
         "OptionGroupName": str,
     },
     total=False,
 )
 
+
 class ModifyDBSnapshotMessageRequestTypeDef(
     _RequiredModifyDBSnapshotMessageRequestTypeDef, _OptionalModifyDBSnapshotMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredModifyDBSubnetGroupMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBSubnetGroupMessageRequestTypeDef",
     {
         "DBSubnetGroupName": str,
         "SubnetIds": Sequence[str],
     },
 )
@@ -1690,20 +1838,22 @@
     "_OptionalModifyDBSubnetGroupMessageRequestTypeDef",
     {
         "DBSubnetGroupDescription": str,
     },
     total=False,
 )
 
+
 class ModifyDBSubnetGroupMessageRequestTypeDef(
     _RequiredModifyDBSubnetGroupMessageRequestTypeDef,
     _OptionalModifyDBSubnetGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredModifyEventSubscriptionMessageRequestTypeDef = TypedDict(
     "_RequiredModifyEventSubscriptionMessageRequestTypeDef",
     {
         "SubscriptionName": str,
     },
 )
 _OptionalModifyEventSubscriptionMessageRequestTypeDef = TypedDict(
@@ -1713,20 +1863,22 @@
         "SourceType": str,
         "EventCategories": Sequence[str],
         "Enabled": bool,
     },
     total=False,
 )
 
+
 class ModifyEventSubscriptionMessageRequestTypeDef(
     _RequiredModifyEventSubscriptionMessageRequestTypeDef,
     _OptionalModifyEventSubscriptionMessageRequestTypeDef,
 ):
     pass
 
+
 ModifyGlobalClusterMessageRequestTypeDef = TypedDict(
     "ModifyGlobalClusterMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "NewGlobalClusterIdentifier": str,
         "DeletionProtection": bool,
         "EngineVersion": str,
@@ -1764,14 +1916,24 @@
     "OutpostTypeDef",
     {
         "Arn": str,
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
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
         "Action": str,
         "AutoAppliedAfterDate": datetime,
         "ForcedApplyDate": datetime,
         "OptInStatus": str,
@@ -1799,20 +1961,22 @@
     {
         "BackupRetentionPeriod": int,
         "PreferredBackupWindow": str,
     },
     total=False,
 )
 
+
 class PromoteReadReplicaMessageRequestTypeDef(
     _RequiredPromoteReadReplicaMessageRequestTypeDef,
     _OptionalPromoteReadReplicaMessageRequestTypeDef,
 ):
     pass
 
+
 RangeTypeDef = TypedDict(
     "RangeTypeDef",
     {
         "From": int,
         "To": int,
         "Step": int,
     },
@@ -1836,19 +2000,21 @@
     "_OptionalRebootDBInstanceMessageRequestTypeDef",
     {
         "ForceFailover": bool,
     },
     total=False,
 )
 
+
 class RebootDBInstanceMessageRequestTypeDef(
     _RequiredRebootDBInstanceMessageRequestTypeDef, _OptionalRebootDBInstanceMessageRequestTypeDef
 ):
     pass
 
+
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "RecurringChargeAmount": float,
         "RecurringChargeFrequency": str,
     },
     total=False,
@@ -1866,20 +2032,22 @@
         "TargetGroupName": str,
         "DBInstanceIdentifiers": Sequence[str],
         "DBClusterIdentifiers": Sequence[str],
     },
     total=False,
 )
 
+
 class RegisterDBProxyTargetsRequestRequestTypeDef(
     _RequiredRegisterDBProxyTargetsRequestRequestTypeDef,
     _OptionalRegisterDBProxyTargetsRequestRequestTypeDef,
 ):
     pass
 
+
 RemoveFromGlobalClusterMessageRequestTypeDef = TypedDict(
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "DbClusterIdentifier": str,
     },
     total=False,
@@ -1896,20 +2064,22 @@
     "_OptionalRemoveRoleFromDBClusterMessageRequestTypeDef",
     {
         "FeatureName": str,
     },
     total=False,
 )
 
+
 class RemoveRoleFromDBClusterMessageRequestTypeDef(
     _RequiredRemoveRoleFromDBClusterMessageRequestTypeDef,
     _OptionalRemoveRoleFromDBClusterMessageRequestTypeDef,
 ):
     pass
 
+
 RemoveRoleFromDBInstanceMessageRequestTypeDef = TypedDict(
     "RemoveRoleFromDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "RoleArn": str,
         "FeatureName": str,
     },
@@ -1927,14 +2097,25 @@
     "RemoveTagsFromResourceMessageRequestTypeDef",
     {
         "ResourceName": str,
         "TagKeys": Sequence[str],
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
 _RequiredRevokeDBSecurityGroupIngressMessageRequestTypeDef = TypedDict(
     "_RequiredRevokeDBSecurityGroupIngressMessageRequestTypeDef",
     {
         "DBSecurityGroupName": str,
     },
 )
 _OptionalRevokeDBSecurityGroupIngressMessageRequestTypeDef = TypedDict(
@@ -1944,20 +2125,22 @@
         "EC2SecurityGroupName": str,
         "EC2SecurityGroupId": str,
         "EC2SecurityGroupOwnerId": str,
     },
     total=False,
 )
 
+
 class RevokeDBSecurityGroupIngressMessageRequestTypeDef(
     _RequiredRevokeDBSecurityGroupIngressMessageRequestTypeDef,
     _OptionalRevokeDBSecurityGroupIngressMessageRequestTypeDef,
 ):
     pass
 
+
 SourceRegionTypeDef = TypedDict(
     "SourceRegionTypeDef",
     {
         "RegionName": str,
         "Endpoint": str,
         "Status": str,
         "SupportsDBInstanceAutomatedBackupsReplication": bool,
@@ -1978,20 +2161,35 @@
     {
         "ApplyImmediately": bool,
         "EngineNativeAuditFieldsIncluded": bool,
     },
     total=False,
 )
 
+
 class StartActivityStreamRequestRequestTypeDef(
     _RequiredStartActivityStreamRequestRequestTypeDef,
     _OptionalStartActivityStreamRequestRequestTypeDef,
 ):
     pass
 
+
+StartActivityStreamResponseTypeDef = TypedDict(
+    "StartActivityStreamResponseTypeDef",
+    {
+        "KmsKeyId": str,
+        "KinesisStreamName": str,
+        "Status": ActivityStreamStatusType,
+        "Mode": ActivityStreamModeType,
+        "ApplyImmediately": bool,
+        "EngineNativeAuditFieldsIncluded": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartDBClusterMessageRequestTypeDef = TypedDict(
     "StartDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 
@@ -2008,20 +2206,22 @@
         "KmsKeyId": str,
         "PreSignedUrl": str,
         "SourceRegion": str,
     },
     total=False,
 )
 
+
 class StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef(
     _RequiredStartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     _OptionalStartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
 ):
     pass
 
+
 StartDBInstanceMessageRequestTypeDef = TypedDict(
     "StartDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
     },
 )
 
@@ -2040,39 +2240,53 @@
     {
         "S3Prefix": str,
         "ExportOnly": Sequence[str],
     },
     total=False,
 )
 
+
 class StartExportTaskMessageRequestTypeDef(
     _RequiredStartExportTaskMessageRequestTypeDef, _OptionalStartExportTaskMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredStopActivityStreamRequestRequestTypeDef = TypedDict(
     "_RequiredStopActivityStreamRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalStopActivityStreamRequestRequestTypeDef = TypedDict(
     "_OptionalStopActivityStreamRequestRequestTypeDef",
     {
         "ApplyImmediately": bool,
     },
     total=False,
 )
 
+
 class StopActivityStreamRequestRequestTypeDef(
     _RequiredStopActivityStreamRequestRequestTypeDef,
     _OptionalStopActivityStreamRequestRequestTypeDef,
 ):
     pass
 
+
+StopActivityStreamResponseTypeDef = TypedDict(
+    "StopActivityStreamResponseTypeDef",
+    {
+        "KmsKeyId": str,
+        "KinesisStreamName": str,
+        "Status": ActivityStreamStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDBClusterMessageRequestTypeDef = TypedDict(
     "StopDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 
@@ -2093,234 +2307,104 @@
     "_OptionalStopDBInstanceMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
     },
     total=False,
 )
 
+
 class StopDBInstanceMessageRequestTypeDef(
     _RequiredStopDBInstanceMessageRequestTypeDef, _OptionalStopDBInstanceMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredSwitchoverBlueGreenDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredSwitchoverBlueGreenDeploymentRequestRequestTypeDef",
     {
         "BlueGreenDeploymentIdentifier": str,
     },
 )
 _OptionalSwitchoverBlueGreenDeploymentRequestRequestTypeDef = TypedDict(
     "_OptionalSwitchoverBlueGreenDeploymentRequestRequestTypeDef",
     {
         "SwitchoverTimeout": int,
     },
     total=False,
 )
 
+
 class SwitchoverBlueGreenDeploymentRequestRequestTypeDef(
     _RequiredSwitchoverBlueGreenDeploymentRequestRequestTypeDef,
     _OptionalSwitchoverBlueGreenDeploymentRequestRequestTypeDef,
 ):
     pass
 
+
 SwitchoverReadReplicaMessageRequestTypeDef = TypedDict(
     "SwitchoverReadReplicaMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
     },
 )
 
 AccountAttributesMessageTypeDef = TypedDict(
     "AccountAttributesMessageTypeDef",
     {
         "AccountQuotas": List[AccountQuotaTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterBacktrackResponseMetadataTypeDef = TypedDict(
-    "DBClusterBacktrackResponseMetadataTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "BacktrackIdentifier": str,
-        "BacktrackTo": datetime,
-        "BacktrackedFrom": datetime,
-        "BacktrackRequestCreationTime": datetime,
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterCapacityInfoTypeDef = TypedDict(
-    "DBClusterCapacityInfoTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "PendingCapacity": int,
-        "CurrentCapacity": int,
-        "SecondsBeforeTimeout": int,
-        "TimeoutAction": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterEndpointResponseMetadataTypeDef = TypedDict(
-    "DBClusterEndpointResponseMetadataTypeDef",
-    {
-        "DBClusterEndpointIdentifier": str,
-        "DBClusterIdentifier": str,
-        "DBClusterEndpointResourceIdentifier": str,
-        "Endpoint": str,
-        "Status": str,
-        "EndpointType": str,
-        "CustomEndpointType": str,
-        "StaticMembers": List[str],
-        "ExcludedMembers": List[str],
-        "DBClusterEndpointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterParameterGroupNameMessageTypeDef = TypedDict(
-    "DBClusterParameterGroupNameMessageTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBParameterGroupNameMessageTypeDef = TypedDict(
-    "DBParameterGroupNameMessageTypeDef",
-    {
-        "DBParameterGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DownloadDBLogFilePortionDetailsTypeDef = TypedDict(
-    "DownloadDBLogFilePortionDetailsTypeDef",
-    {
-        "LogFileData": str,
-        "Marker": str,
-        "AdditionalDataPending": bool,
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
-ExportTaskResponseMetadataTypeDef = TypedDict(
-    "ExportTaskResponseMetadataTypeDef",
-    {
-        "ExportTaskIdentifier": str,
-        "SourceArn": str,
-        "ExportOnly": List[str],
-        "SnapshotTime": datetime,
-        "TaskStartTime": datetime,
-        "TaskEndTime": datetime,
-        "S3Bucket": str,
-        "S3Prefix": str,
-        "IamRoleArn": str,
-        "KmsKeyId": str,
-        "Status": str,
-        "PercentProgress": int,
-        "TotalExtractedDataInGB": int,
-        "FailureCause": str,
-        "WarningMessage": str,
-        "SourceType": ExportSourceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ModifyActivityStreamResponseTypeDef = TypedDict(
-    "ModifyActivityStreamResponseTypeDef",
-    {
-        "KmsKeyId": str,
-        "KinesisStreamName": str,
-        "Status": ActivityStreamStatusType,
-        "Mode": ActivityStreamModeType,
-        "EngineNativeAuditFieldsIncluded": bool,
-        "PolicyStatus": ActivityStreamPolicyStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartActivityStreamResponseTypeDef = TypedDict(
-    "StartActivityStreamResponseTypeDef",
-    {
-        "KmsKeyId": str,
-        "KinesisStreamName": str,
-        "Status": ActivityStreamStatusType,
-        "Mode": ActivityStreamModeType,
-        "ApplyImmediately": bool,
-        "EngineNativeAuditFieldsIncluded": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopActivityStreamResponseTypeDef = TypedDict(
-    "StopActivityStreamResponseTypeDef",
-    {
-        "KmsKeyId": str,
-        "KinesisStreamName": str,
-        "Status": ActivityStreamStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddSourceIdentifierToSubscriptionResultTypeDef = TypedDict(
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEventSubscriptionResultTypeDef = TypedDict(
     "CreateEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventSubscriptionResultTypeDef = TypedDict(
     "DeleteEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventSubscriptionsMessageTypeDef = TypedDict(
     "EventSubscriptionsMessageTypeDef",
     {
         "Marker": str,
         "EventSubscriptionsList": List[EventSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyEventSubscriptionResultTypeDef = TypedDict(
     "ModifyEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveSourceIdentifierFromSubscriptionResultTypeDef = TypedDict(
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddTagsToResourceMessageRequestTypeDef = TypedDict(
     "AddTagsToResourceMessageRequestTypeDef",
     {
         "ResourceName": str,
@@ -2340,20 +2424,22 @@
     "_OptionalCopyDBClusterParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CopyDBClusterParameterGroupMessageRequestTypeDef(
     _RequiredCopyDBClusterParameterGroupMessageRequestTypeDef,
     _OptionalCopyDBClusterParameterGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCopyDBClusterSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCopyDBClusterSnapshotMessageRequestTypeDef",
     {
         "SourceDBClusterSnapshotIdentifier": str,
         "TargetDBClusterSnapshotIdentifier": str,
     },
 )
@@ -2365,20 +2451,22 @@
         "CopyTags": bool,
         "Tags": Sequence[TagTypeDef],
         "SourceRegion": str,
     },
     total=False,
 )
 
+
 class CopyDBClusterSnapshotMessageRequestTypeDef(
     _RequiredCopyDBClusterSnapshotMessageRequestTypeDef,
     _OptionalCopyDBClusterSnapshotMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCopyDBParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCopyDBParameterGroupMessageRequestTypeDef",
     {
         "SourceDBParameterGroupIdentifier": str,
         "TargetDBParameterGroupIdentifier": str,
         "TargetDBParameterGroupDescription": str,
     },
@@ -2387,20 +2475,22 @@
     "_OptionalCopyDBParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CopyDBParameterGroupMessageRequestTypeDef(
     _RequiredCopyDBParameterGroupMessageRequestTypeDef,
     _OptionalCopyDBParameterGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCopyDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCopyDBSnapshotMessageRequestTypeDef",
     {
         "SourceDBSnapshotIdentifier": str,
         "TargetDBSnapshotIdentifier": str,
     },
 )
@@ -2415,19 +2505,21 @@
         "TargetCustomAvailabilityZone": str,
         "CopyOptionGroup": bool,
         "SourceRegion": str,
     },
     total=False,
 )
 
+
 class CopyDBSnapshotMessageRequestTypeDef(
     _RequiredCopyDBSnapshotMessageRequestTypeDef, _OptionalCopyDBSnapshotMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredCopyOptionGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCopyOptionGroupMessageRequestTypeDef",
     {
         "SourceOptionGroupIdentifier": str,
         "TargetOptionGroupIdentifier": str,
         "TargetOptionGroupDescription": str,
     },
@@ -2436,19 +2528,21 @@
     "_OptionalCopyOptionGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CopyOptionGroupMessageRequestTypeDef(
     _RequiredCopyOptionGroupMessageRequestTypeDef, _OptionalCopyOptionGroupMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateBlueGreenDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBlueGreenDeploymentRequestRequestTypeDef",
     {
         "BlueGreenDeploymentName": str,
         "Source": str,
     },
 )
@@ -2459,20 +2553,22 @@
         "TargetDBParameterGroupName": str,
         "TargetDBClusterParameterGroupName": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateBlueGreenDeploymentRequestRequestTypeDef(
     _RequiredCreateBlueGreenDeploymentRequestRequestTypeDef,
     _OptionalCreateBlueGreenDeploymentRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateCustomDBEngineVersionMessageRequestTypeDef = TypedDict(
     "_RequiredCreateCustomDBEngineVersionMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
     },
 )
@@ -2486,20 +2582,22 @@
         "Description": str,
         "Manifest": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateCustomDBEngineVersionMessageRequestTypeDef(
     _RequiredCreateCustomDBEngineVersionMessageRequestTypeDef,
     _OptionalCreateCustomDBEngineVersionMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBClusterEndpointMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterEndpointMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterEndpointIdentifier": str,
         "EndpointType": str,
     },
@@ -2510,20 +2608,22 @@
         "StaticMembers": Sequence[str],
         "ExcludedMembers": Sequence[str],
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBClusterEndpointMessageRequestTypeDef(
     _RequiredCreateDBClusterEndpointMessageRequestTypeDef,
     _OptionalCreateDBClusterEndpointMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBClusterParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterParameterGroupMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
         "DBParameterGroupFamily": str,
         "Description": str,
     },
@@ -2532,20 +2632,22 @@
     "_OptionalCreateDBClusterParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBClusterParameterGroupMessageRequestTypeDef(
     _RequiredCreateDBClusterParameterGroupMessageRequestTypeDef,
     _OptionalCreateDBClusterParameterGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBClusterSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterSnapshotMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "DBClusterIdentifier": str,
     },
 )
@@ -2553,20 +2655,22 @@
     "_OptionalCreateDBClusterSnapshotMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBClusterSnapshotMessageRequestTypeDef(
     _RequiredCreateDBClusterSnapshotMessageRequestTypeDef,
     _OptionalCreateDBClusterSnapshotMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBParameterGroupMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
         "DBParameterGroupFamily": str,
         "Description": str,
     },
@@ -2575,20 +2679,22 @@
     "_OptionalCreateDBParameterGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBParameterGroupMessageRequestTypeDef(
     _RequiredCreateDBParameterGroupMessageRequestTypeDef,
     _OptionalCreateDBParameterGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBProxyEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDBProxyEndpointRequestRequestTypeDef",
     {
         "DBProxyName": str,
         "DBProxyEndpointName": str,
         "VpcSubnetIds": Sequence[str],
     },
@@ -2599,20 +2705,22 @@
         "VpcSecurityGroupIds": Sequence[str],
         "TargetRole": DBProxyEndpointTargetRoleType,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBProxyEndpointRequestRequestTypeDef(
     _RequiredCreateDBProxyEndpointRequestRequestTypeDef,
     _OptionalCreateDBProxyEndpointRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBSecurityGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBSecurityGroupMessageRequestTypeDef",
     {
         "DBSecurityGroupName": str,
         "DBSecurityGroupDescription": str,
     },
 )
@@ -2620,20 +2728,22 @@
     "_OptionalCreateDBSecurityGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBSecurityGroupMessageRequestTypeDef(
     _RequiredCreateDBSecurityGroupMessageRequestTypeDef,
     _OptionalCreateDBSecurityGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBSnapshotMessageRequestTypeDef",
     {
         "DBSnapshotIdentifier": str,
         "DBInstanceIdentifier": str,
     },
 )
@@ -2641,19 +2751,21 @@
     "_OptionalCreateDBSnapshotMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBSnapshotMessageRequestTypeDef(
     _RequiredCreateDBSnapshotMessageRequestTypeDef, _OptionalCreateDBSnapshotMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateDBSubnetGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBSubnetGroupMessageRequestTypeDef",
     {
         "DBSubnetGroupName": str,
         "DBSubnetGroupDescription": str,
         "SubnetIds": Sequence[str],
     },
@@ -2662,20 +2774,22 @@
     "_OptionalCreateDBSubnetGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBSubnetGroupMessageRequestTypeDef(
     _RequiredCreateDBSubnetGroupMessageRequestTypeDef,
     _OptionalCreateDBSubnetGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateEventSubscriptionMessageRequestTypeDef = TypedDict(
     "_RequiredCreateEventSubscriptionMessageRequestTypeDef",
     {
         "SubscriptionName": str,
         "SnsTopicArn": str,
     },
 )
@@ -2687,20 +2801,22 @@
         "SourceIds": Sequence[str],
         "Enabled": bool,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateEventSubscriptionMessageRequestTypeDef(
     _RequiredCreateEventSubscriptionMessageRequestTypeDef,
     _OptionalCreateEventSubscriptionMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateOptionGroupMessageRequestTypeDef = TypedDict(
     "_RequiredCreateOptionGroupMessageRequestTypeDef",
     {
         "OptionGroupName": str,
         "EngineName": str,
         "MajorEngineVersion": str,
         "OptionGroupDescription": str,
@@ -2710,19 +2826,21 @@
     "_OptionalCreateOptionGroupMessageRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateOptionGroupMessageRequestTypeDef(
     _RequiredCreateOptionGroupMessageRequestTypeDef, _OptionalCreateOptionGroupMessageRequestTypeDef
 ):
     pass
 
+
 DBClusterSnapshotTypeDef = TypedDict(
     "DBClusterSnapshotTypeDef",
     {
         "AvailabilityZones": List[str],
         "DBClusterSnapshotIdentifier": str,
         "DBClusterIdentifier": str,
         "SnapshotCreateTime": datetime,
@@ -2741,14 +2859,15 @@
         "StorageEncrypted": bool,
         "KmsKeyId": str,
         "DBClusterSnapshotArn": str,
         "SourceDBClusterSnapshotArn": str,
         "IAMDatabaseAuthenticationEnabled": bool,
         "TagList": List[TagTypeDef],
         "DBSystemId": str,
+        "StorageType": str,
     },
     total=False,
 )
 
 _RequiredPurchaseReservedDBInstancesOfferingMessageRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedDBInstancesOfferingMessageRequestTypeDef",
     {
@@ -2761,25 +2880,27 @@
         "ReservedDBInstanceId": str,
         "DBInstanceCount": int,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class PurchaseReservedDBInstancesOfferingMessageRequestTypeDef(
     _RequiredPurchaseReservedDBInstancesOfferingMessageRequestTypeDef,
     _OptionalPurchaseReservedDBInstancesOfferingMessageRequestTypeDef,
 ):
     pass
 
+
 TagListMessageTypeDef = TypedDict(
     "TagListMessageTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrderableDBInstanceOptionTypeDef = TypedDict(
     "OrderableDBInstanceOptionTypeDef",
     {
         "Engine": str,
@@ -2840,37 +2961,38 @@
 )
 
 CertificateMessageTypeDef = TypedDict(
     "CertificateMessageTypeDef",
     {
         "Certificates": List[CertificateTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyCertificatesResultTypeDef = TypedDict(
     "ModifyCertificatesResultTypeDef",
     {
         "Certificate": CertificateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterPendingModifiedValuesTypeDef = TypedDict(
     "ClusterPendingModifiedValuesTypeDef",
     {
         "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
         "DBClusterIdentifier": str,
         "MasterUserPassword": str,
         "IAMDatabaseAuthenticationEnabled": bool,
         "EngineVersion": str,
         "BackupRetentionPeriod": int,
         "AllocatedStorage": int,
         "Iops": int,
+        "StorageType": str,
     },
     total=False,
 )
 
 DBProxyTargetGroupTypeDef = TypedDict(
     "DBProxyTargetGroupTypeDef",
     {
@@ -2898,67 +3020,69 @@
     {
         "ConnectionPoolConfig": ConnectionPoolConfigurationTypeDef,
         "NewName": str,
     },
     total=False,
 )
 
+
 class ModifyDBProxyTargetGroupRequestRequestTypeDef(
     _RequiredModifyDBProxyTargetGroupRequestRequestTypeDef,
     _OptionalModifyDBProxyTargetGroupRequestRequestTypeDef,
 ):
     pass
 
+
 CopyDBClusterParameterGroupResultTypeDef = TypedDict(
     "CopyDBClusterParameterGroupResultTypeDef",
     {
         "DBClusterParameterGroup": DBClusterParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBClusterParameterGroupResultTypeDef = TypedDict(
     "CreateDBClusterParameterGroupResultTypeDef",
     {
         "DBClusterParameterGroup": DBClusterParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterParameterGroupsMessageTypeDef = TypedDict(
     "DBClusterParameterGroupsMessageTypeDef",
     {
         "Marker": str,
         "DBClusterParameterGroups": List[DBClusterParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyDBParameterGroupResultTypeDef = TypedDict(
     "CopyDBParameterGroupResultTypeDef",
     {
         "DBParameterGroup": DBParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBParameterGroupResultTypeDef = TypedDict(
     "CreateDBParameterGroupResultTypeDef",
     {
         "DBParameterGroup": DBParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBParameterGroupsMessageTypeDef = TypedDict(
     "DBParameterGroupsMessageTypeDef",
     {
         "Marker": str,
         "DBParameterGroups": List[DBParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
@@ -3016,19 +3140,21 @@
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
         "SourceRegion": str,
     },
     total=False,
 )
 
+
 class CreateDBClusterMessageRequestTypeDef(
     _RequiredCreateDBClusterMessageRequestTypeDef, _OptionalCreateDBClusterMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredModifyDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 _OptionalModifyDBClusterMessageRequestTypeDef = TypedDict(
@@ -3068,23 +3194,27 @@
         "PerformanceInsightsKMSKeyId": str,
         "PerformanceInsightsRetentionPeriod": int,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
         "ManageMasterUserPassword": bool,
         "RotateMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
+        "EngineMode": str,
+        "AllowEngineModeChange": bool,
     },
     total=False,
 )
 
+
 class ModifyDBClusterMessageRequestTypeDef(
     _RequiredModifyDBClusterMessageRequestTypeDef, _OptionalModifyDBClusterMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredRestoreDBClusterFromS3MessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBClusterFromS3MessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "Engine": str,
         "MasterUsername": str,
         "SourceEngine": str,
@@ -3120,24 +3250,27 @@
         "CopyTagsToSnapshot": bool,
         "Domain": str,
         "DomainIAMRoleName": str,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
+        "StorageType": str,
     },
     total=False,
 )
 
+
 class RestoreDBClusterFromS3MessageRequestTypeDef(
     _RequiredRestoreDBClusterFromS3MessageRequestTypeDef,
     _OptionalRestoreDBClusterFromS3MessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "SnapshotIdentifier": str,
         "Engine": str,
     },
@@ -3170,20 +3303,22 @@
         "PubliclyAccessible": bool,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
     },
     total=False,
 )
 
+
 class RestoreDBClusterFromSnapshotMessageRequestTypeDef(
     _RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef,
     _OptionalRestoreDBClusterFromSnapshotMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredRestoreDBClusterToPointInTimeMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBClusterToPointInTimeMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "SourceDBClusterIdentifier": str,
     },
 )
@@ -3215,20 +3350,22 @@
         "Iops": int,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationTypeDef,
         "NetworkType": str,
     },
     total=False,
 )
 
+
 class RestoreDBClusterToPointInTimeMessageRequestTypeDef(
     _RequiredRestoreDBClusterToPointInTimeMessageRequestTypeDef,
     _OptionalRestoreDBClusterToPointInTimeMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDBInstanceMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "Engine": str,
     },
@@ -3288,29 +3425,31 @@
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
         "CACertificateIdentifier": str,
     },
     total=False,
 )
 
+
 class CreateDBInstanceMessageRequestTypeDef(
     _RequiredCreateDBInstanceMessageRequestTypeDef, _OptionalCreateDBInstanceMessageRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateDBInstanceReadReplicaMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBInstanceReadReplicaMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
-        "SourceDBInstanceIdentifier": str,
     },
 )
 _OptionalCreateDBInstanceReadReplicaMessageRequestTypeDef = TypedDict(
     "_OptionalCreateDBInstanceReadReplicaMessageRequestTypeDef",
     {
+        "SourceDBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "AvailabilityZone": str,
         "Port": int,
         "MultiAZ": bool,
         "AutoMinorVersionUpgrade": bool,
         "Iops": int,
         "OptionGroupName": str,
@@ -3338,25 +3477,28 @@
         "ReplicaMode": ReplicaModeType,
         "MaxAllocatedStorage": int,
         "CustomIamInstanceProfile": str,
         "NetworkType": str,
         "StorageThroughput": int,
         "EnableCustomerOwnedIp": bool,
         "AllocatedStorage": int,
+        "SourceDBClusterIdentifier": str,
         "SourceRegion": str,
     },
     total=False,
 )
 
+
 class CreateDBInstanceReadReplicaMessageRequestTypeDef(
     _RequiredCreateDBInstanceReadReplicaMessageRequestTypeDef,
     _OptionalCreateDBInstanceReadReplicaMessageRequestTypeDef,
 ):
     pass
 
+
 DBSnapshotTypeDef = TypedDict(
     "DBSnapshotTypeDef",
     {
         "DBSnapshotIdentifier": str,
         "DBInstanceIdentifier": str,
         "SnapshotCreateTime": datetime,
         "Engine": str,
@@ -3449,23 +3591,26 @@
         "AutomationMode": AutomationModeType,
         "ResumeFullAutomationModeMinutes": int,
         "NetworkType": str,
         "StorageThroughput": int,
         "ManageMasterUserPassword": bool,
         "RotateMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
+        "Engine": str,
     },
     total=False,
 )
 
+
 class ModifyDBInstanceMessageRequestTypeDef(
     _RequiredModifyDBInstanceMessageRequestTypeDef, _OptionalModifyDBInstanceMessageRequestTypeDef
 ):
     pass
 
+
 PendingModifiedValuesTypeDef = TypedDict(
     "PendingModifiedValuesTypeDef",
     {
         "DBInstanceClass": str,
         "AllocatedStorage": int,
         "MasterUserPassword": str,
         "Port": int,
@@ -3480,14 +3625,15 @@
         "DBSubnetGroupName": str,
         "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
         "ProcessorFeatures": List[ProcessorFeatureTypeDef],
         "IAMDatabaseAuthenticationEnabled": bool,
         "AutomationMode": AutomationModeType,
         "ResumeFullAutomationModeTime": datetime,
         "StorageThroughput": int,
+        "Engine": str,
     },
     total=False,
 )
 
 _RequiredRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef",
     {
@@ -3531,20 +3677,22 @@
         "StorageThroughput": int,
         "DBClusterSnapshotIdentifier": str,
         "AllocatedStorage": int,
     },
     total=False,
 )
 
+
 class RestoreDBInstanceFromDBSnapshotMessageRequestTypeDef(
     _RequiredRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef,
     _OptionalRestoreDBInstanceFromDBSnapshotMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredRestoreDBInstanceFromS3MessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBInstanceFromS3MessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "Engine": str,
         "SourceEngine": str,
@@ -3597,20 +3745,22 @@
         "StorageThroughput": int,
         "ManageMasterUserPassword": bool,
         "MasterUserSecretKmsKeyId": str,
     },
     total=False,
 )
 
+
 class RestoreDBInstanceFromS3MessageRequestTypeDef(
     _RequiredRestoreDBInstanceFromS3MessageRequestTypeDef,
     _OptionalRestoreDBInstanceFromS3MessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredRestoreDBInstanceToPointInTimeMessageRequestTypeDef = TypedDict(
     "_RequiredRestoreDBInstanceToPointInTimeMessageRequestTypeDef",
     {
         "TargetDBInstanceIdentifier": str,
     },
 )
 _OptionalRestoreDBInstanceToPointInTimeMessageRequestTypeDef = TypedDict(
@@ -3654,50 +3804,52 @@
         "NetworkType": str,
         "StorageThroughput": int,
         "AllocatedStorage": int,
     },
     total=False,
 )
 
+
 class RestoreDBInstanceToPointInTimeMessageRequestTypeDef(
     _RequiredRestoreDBInstanceToPointInTimeMessageRequestTypeDef,
     _OptionalRestoreDBInstanceToPointInTimeMessageRequestTypeDef,
 ):
     pass
 
+
 CreateDBProxyEndpointResponseTypeDef = TypedDict(
     "CreateDBProxyEndpointResponseTypeDef",
     {
         "DBProxyEndpoint": DBProxyEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBProxyEndpointResponseTypeDef = TypedDict(
     "DeleteDBProxyEndpointResponseTypeDef",
     {
         "DBProxyEndpoint": DBProxyEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBProxyEndpointsResponseTypeDef = TypedDict(
     "DescribeDBProxyEndpointsResponseTypeDef",
     {
         "DBProxyEndpoints": List[DBProxyEndpointTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBProxyEndpointResponseTypeDef = TypedDict(
     "ModifyDBProxyEndpointResponseTypeDef",
     {
         "DBProxyEndpoint": DBProxyEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDBProxyRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDBProxyRequestRequestTypeDef",
     {
         "DBProxyName": str,
@@ -3715,19 +3867,21 @@
         "IdleClientTimeout": int,
         "DebugLogging": bool,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDBProxyRequestRequestTypeDef(
     _RequiredCreateDBProxyRequestRequestTypeDef, _OptionalCreateDBProxyRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredModifyDBProxyRequestRequestTypeDef = TypedDict(
     "_RequiredModifyDBProxyRequestRequestTypeDef",
     {
         "DBProxyName": str,
     },
 )
 _OptionalModifyDBProxyRequestRequestTypeDef = TypedDict(
@@ -3740,52 +3894,54 @@
         "DebugLogging": bool,
         "RoleArn": str,
         "SecurityGroups": Sequence[str],
     },
     total=False,
 )
 
+
 class ModifyDBProxyRequestRequestTypeDef(
     _RequiredModifyDBProxyRequestRequestTypeDef, _OptionalModifyDBProxyRequestRequestTypeDef
 ):
     pass
 
+
 DBClusterBacktrackMessageTypeDef = TypedDict(
     "DBClusterBacktrackMessageTypeDef",
     {
         "Marker": str,
         "DBClusterBacktracks": List[DBClusterBacktrackTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterEndpointMessageTypeDef = TypedDict(
     "DBClusterEndpointMessageTypeDef",
     {
         "Marker": str,
         "DBClusterEndpoints": List[DBClusterEndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterParameterGroupDetailsTypeDef = TypedDict(
     "DBClusterParameterGroupDetailsTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBParameterGroupDetailsTypeDef = TypedDict(
     "DBParameterGroupDetailsTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EngineDefaultsTypeDef = TypedDict(
     "EngineDefaultsTypeDef",
     {
         "DBParameterGroupFamily": str,
@@ -3822,20 +3978,22 @@
     {
         "ResetAllParameters": bool,
         "Parameters": Sequence[ParameterTypeDef],
     },
     total=False,
 )
 
+
 class ResetDBClusterParameterGroupMessageRequestTypeDef(
     _RequiredResetDBClusterParameterGroupMessageRequestTypeDef,
     _OptionalResetDBClusterParameterGroupMessageRequestTypeDef,
 ):
     pass
 
+
 _RequiredResetDBParameterGroupMessageRequestTypeDef = TypedDict(
     "_RequiredResetDBParameterGroupMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
     },
 )
 _OptionalResetDBParameterGroupMessageRequestTypeDef = TypedDict(
@@ -3843,20 +4001,22 @@
     {
         "ResetAllParameters": bool,
         "Parameters": Sequence[ParameterTypeDef],
     },
     total=False,
 )
 
+
 class ResetDBParameterGroupMessageRequestTypeDef(
     _RequiredResetDBParameterGroupMessageRequestTypeDef,
     _OptionalResetDBParameterGroupMessageRequestTypeDef,
 ):
     pass
 
+
 DBClusterSnapshotAttributesResultTypeDef = TypedDict(
     "DBClusterSnapshotAttributesResultTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "DBClusterSnapshotAttributes": List[DBClusterSnapshotAttributeTypeDef],
     },
     total=False,
@@ -3892,15 +4052,15 @@
         "KMSKeyId": str,
         "CreateTime": datetime,
         "TagList": List[TagTypeDef],
         "SupportsBabelfish": bool,
         "CustomDBEngineVersionManifest": str,
         "SupportsCertificateRotationWithoutRestart": bool,
         "SupportedCACertificateIdentifiers": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBEngineVersionTypeDef = TypedDict(
     "DBEngineVersionTypeDef",
     {
         "Engine": str,
@@ -4031,36 +4191,80 @@
     {
         "DBSnapshotIdentifier": str,
         "DBSnapshotAttributes": List[DBSnapshotAttributeTypeDef],
     },
     total=False,
 )
 
+DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef = TypedDict(
+    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
+    {
+        "BlueGreenDeploymentIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeBlueGreenDeploymentsRequestRequestTypeDef = TypedDict(
     "DescribeBlueGreenDeploymentsRequestRequestTypeDef",
     {
         "BlueGreenDeploymentIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
+    {
+        "CertificateIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCertificatesMessageRequestTypeDef = TypedDict(
     "DescribeCertificatesMessageRequestTypeDef",
     {
         "CertificateIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+    },
+)
+_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
+    {
+        "BacktrackIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef(
+    _RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
+    _OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeDBClusterBacktracksMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBClusterBacktracksMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 _OptionalDescribeDBClusterBacktracksMessageRequestTypeDef = TypedDict(
@@ -4070,43 +4274,90 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+
 class DescribeDBClusterBacktracksMessageRequestTypeDef(
     _RequiredDescribeDBClusterBacktracksMessageRequestTypeDef,
     _OptionalDescribeDBClusterBacktracksMessageRequestTypeDef,
 ):
     pass
 
+
+DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef = TypedDict(
+    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "DBClusterEndpointIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBClusterEndpointsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterEndpointsMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterEndpointIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
+    {
+        "DBClusterParameterGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBClusterParameterGroupsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterParameterGroupsMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
+    {
+        "DBClusterParameterGroupName": str,
+    },
+)
+_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef(
+    _RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
+    _OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeDBClusterParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBClusterParametersMessageRequestTypeDef",
     {
         "DBClusterParameterGroupName": str,
     },
 )
 _OptionalDescribeDBClusterParametersMessageRequestTypeDef = TypedDict(
@@ -4116,20 +4367,36 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+
 class DescribeDBClusterParametersMessageRequestTypeDef(
     _RequiredDescribeDBClusterParametersMessageRequestTypeDef,
     _OptionalDescribeDBClusterParametersMessageRequestTypeDef,
 ):
     pass
 
+
+DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "DBClusterSnapshotIdentifier": str,
+        "SnapshotType": str,
+        "Filters": Sequence[FilterTypeDef],
+        "IncludeShared": bool,
+        "IncludePublic": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBClusterSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterSnapshotsMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
@@ -4137,865 +4404,651 @@
         "Marker": str,
         "IncludeShared": bool,
         "IncludePublic": bool,
     },
     total=False,
 )
 
+DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef = TypedDict(
+    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
+    {
+        "DBClusterIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "IncludeShared": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeDBClustersMessageRequestTypeDef = TypedDict(
     "DescribeDBClustersMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
         "IncludeShared": bool,
     },
     total=False,
 )
 
-DescribeDBEngineVersionsMessageRequestTypeDef = TypedDict(
-    "DescribeDBEngineVersionsMessageRequestTypeDef",
+DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef = TypedDict(
+    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "DBParameterGroupFamily": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
         "DefaultOnly": bool,
         "ListSupportedCharacterSets": bool,
         "ListSupportedTimezones": bool,
         "IncludeAll": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef = TypedDict(
-    "DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef",
+DescribeDBEngineVersionsMessageRequestTypeDef = TypedDict(
+    "DescribeDBEngineVersionsMessageRequestTypeDef",
     {
-        "DbiResourceId": str,
-        "DBInstanceIdentifier": str,
+        "Engine": str,
+        "EngineVersion": str,
+        "DBParameterGroupFamily": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
-        "DBInstanceAutomatedBackupsArn": str,
+        "DefaultOnly": bool,
+        "ListSupportedCharacterSets": bool,
+        "ListSupportedTimezones": bool,
+        "IncludeAll": bool,
     },
     total=False,
 )
 
-DescribeDBInstancesMessageRequestTypeDef = TypedDict(
-    "DescribeDBInstancesMessageRequestTypeDef",
+DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef = TypedDict(
+    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
     {
+        "DbiResourceId": str,
         "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "DBInstanceAutomatedBackupsArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeDBLogFilesMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeDBLogFilesMessageRequestTypeDef",
+DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef = TypedDict(
+    "DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef",
     {
+        "DbiResourceId": str,
         "DBInstanceIdentifier": str,
-    },
-)
-_OptionalDescribeDBLogFilesMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeDBLogFilesMessageRequestTypeDef",
-    {
-        "FilenameContains": str,
-        "FileLastWritten": int,
-        "FileSize": int,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
+        "DBInstanceAutomatedBackupsArn": str,
     },
     total=False,
 )
 
-class DescribeDBLogFilesMessageRequestTypeDef(
-    _RequiredDescribeDBLogFilesMessageRequestTypeDef,
-    _OptionalDescribeDBLogFilesMessageRequestTypeDef,
-):
-    pass
-
-DescribeDBParameterGroupsMessageRequestTypeDef = TypedDict(
-    "DescribeDBParameterGroupsMessageRequestTypeDef",
+DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef = TypedDict(
+    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
     {
-        "DBParameterGroupName": str,
+        "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeDBParametersMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeDBParametersMessageRequestTypeDef",
-    {
-        "DBParameterGroupName": str,
-    },
-)
-_OptionalDescribeDBParametersMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeDBParametersMessageRequestTypeDef",
+DescribeDBInstancesMessageRequestTypeDef = TypedDict(
+    "DescribeDBInstancesMessageRequestTypeDef",
     {
-        "Source": str,
+        "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-class DescribeDBParametersMessageRequestTypeDef(
-    _RequiredDescribeDBParametersMessageRequestTypeDef,
-    _OptionalDescribeDBParametersMessageRequestTypeDef,
-):
-    pass
-
-DescribeDBProxiesRequestRequestTypeDef = TypedDict(
-    "DescribeDBProxiesRequestRequestTypeDef",
+_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
     {
-        "DBProxyName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
-        "MaxRecords": int,
+        "DBInstanceIdentifier": str,
     },
-    total=False,
 )
-
-DescribeDBProxyEndpointsRequestRequestTypeDef = TypedDict(
-    "DescribeDBProxyEndpointsRequestRequestTypeDef",
+_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
     {
-        "DBProxyName": str,
-        "DBProxyEndpointName": str,
+        "FilenameContains": str,
+        "FileLastWritten": int,
+        "FileSize": int,
         "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
-        "MaxRecords": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef = TypedDict(
-    "_RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef",
-    {
-        "DBProxyName": str,
-    },
-)
-_OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef = TypedDict(
-    "_OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef",
-    {
-        "TargetGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
-        "MaxRecords": int,
-    },
-    total=False,
-)
 
-class DescribeDBProxyTargetGroupsRequestRequestTypeDef(
-    _RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef,
-    _OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef,
+class DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef(
+    _RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
+    _OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
 ):
     pass
 
-_RequiredDescribeDBProxyTargetsRequestRequestTypeDef = TypedDict(
-    "_RequiredDescribeDBProxyTargetsRequestRequestTypeDef",
+
+_RequiredDescribeDBLogFilesMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeDBLogFilesMessageRequestTypeDef",
     {
-        "DBProxyName": str,
+        "DBInstanceIdentifier": str,
     },
 )
-_OptionalDescribeDBProxyTargetsRequestRequestTypeDef = TypedDict(
-    "_OptionalDescribeDBProxyTargetsRequestRequestTypeDef",
+_OptionalDescribeDBLogFilesMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeDBLogFilesMessageRequestTypeDef",
     {
-        "TargetGroupName": str,
+        "FilenameContains": str,
+        "FileLastWritten": int,
+        "FileSize": int,
         "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
         "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-class DescribeDBProxyTargetsRequestRequestTypeDef(
-    _RequiredDescribeDBProxyTargetsRequestRequestTypeDef,
-    _OptionalDescribeDBProxyTargetsRequestRequestTypeDef,
+
+class DescribeDBLogFilesMessageRequestTypeDef(
+    _RequiredDescribeDBLogFilesMessageRequestTypeDef,
+    _OptionalDescribeDBLogFilesMessageRequestTypeDef,
 ):
     pass
 
-DescribeDBSecurityGroupsMessageRequestTypeDef = TypedDict(
-    "DescribeDBSecurityGroupsMessageRequestTypeDef",
-    {
-        "DBSecurityGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
-    },
-    total=False,
-)
 
-DescribeDBSnapshotsMessageRequestTypeDef = TypedDict(
-    "DescribeDBSnapshotsMessageRequestTypeDef",
+DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
     {
-        "DBInstanceIdentifier": str,
-        "DBSnapshotIdentifier": str,
-        "SnapshotType": str,
+        "DBParameterGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
-        "IncludeShared": bool,
-        "IncludePublic": bool,
-        "DbiResourceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeDBSubnetGroupsMessageRequestTypeDef = TypedDict(
-    "DescribeDBSubnetGroupsMessageRequestTypeDef",
+DescribeDBParameterGroupsMessageRequestTypeDef = TypedDict(
+    "DescribeDBParameterGroupsMessageRequestTypeDef",
     {
-        "DBSubnetGroupName": str,
+        "DBParameterGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-_RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef",
+_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
     {
-        "DBParameterGroupFamily": str,
+        "DBParameterGroupName": str,
     },
 )
-_OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef",
+_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
     {
+        "Source": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeEngineDefaultClusterParametersMessageRequestTypeDef(
-    _RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef,
-    _OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+
+class DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef(
+    _RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
+    _OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
 ):
     pass
 
-_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef",
+
+_RequiredDescribeDBParametersMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeDBParametersMessageRequestTypeDef",
     {
-        "DBParameterGroupFamily": str,
+        "DBParameterGroupName": str,
     },
 )
-_OptionalDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultParametersMessageRequestTypeDef",
+_OptionalDescribeDBParametersMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeDBParametersMessageRequestTypeDef",
     {
+        "Source": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
-class DescribeEngineDefaultParametersMessageRequestTypeDef(
-    _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef,
-    _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef,
+
+class DescribeDBParametersMessageRequestTypeDef(
+    _RequiredDescribeDBParametersMessageRequestTypeDef,
+    _OptionalDescribeDBParametersMessageRequestTypeDef,
 ):
     pass
 
-DescribeEventCategoriesMessageRequestTypeDef = TypedDict(
-    "DescribeEventCategoriesMessageRequestTypeDef",
-    {
-        "SourceType": str,
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
 
-DescribeEventSubscriptionsMessageRequestTypeDef = TypedDict(
-    "DescribeEventSubscriptionsMessageRequestTypeDef",
+DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef = TypedDict(
+    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
     {
-        "SubscriptionName": str,
+        "DBProxyName": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeEventsMessageRequestTypeDef = TypedDict(
-    "DescribeEventsMessageRequestTypeDef",
+DescribeDBProxiesRequestRequestTypeDef = TypedDict(
+    "DescribeDBProxiesRequestRequestTypeDef",
     {
-        "SourceIdentifier": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "EventCategories": Sequence[str],
+        "DBProxyName": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
         "Marker": str,
+        "MaxRecords": int,
     },
     total=False,
 )
 
-DescribeExportTasksMessageRequestTypeDef = TypedDict(
-    "DescribeExportTasksMessageRequestTypeDef",
+DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef = TypedDict(
+    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
     {
-        "ExportTaskIdentifier": str,
-        "SourceArn": str,
+        "DBProxyName": str,
+        "DBProxyEndpointName": str,
         "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
-        "MaxRecords": int,
-        "SourceType": ExportSourceTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeGlobalClustersMessageRequestTypeDef = TypedDict(
-    "DescribeGlobalClustersMessageRequestTypeDef",
+DescribeDBProxyEndpointsRequestRequestTypeDef = TypedDict(
+    "DescribeDBProxyEndpointsRequestRequestTypeDef",
     {
-        "GlobalClusterIdentifier": str,
+        "DBProxyName": str,
+        "DBProxyEndpointName": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
         "Marker": str,
+        "MaxRecords": int,
     },
     total=False,
 )
 
-_RequiredDescribeOptionGroupOptionsMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeOptionGroupOptionsMessageRequestTypeDef",
+_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
     {
-        "EngineName": str,
+        "DBProxyName": str,
     },
 )
-_OptionalDescribeOptionGroupOptionsMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeOptionGroupOptionsMessageRequestTypeDef",
+_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
     {
-        "MajorEngineVersion": str,
+        "TargetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeOptionGroupOptionsMessageRequestTypeDef(
-    _RequiredDescribeOptionGroupOptionsMessageRequestTypeDef,
-    _OptionalDescribeOptionGroupOptionsMessageRequestTypeDef,
+
+class DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef(
+    _RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
+    _OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
 ):
     pass
 
-DescribeOptionGroupsMessageRequestTypeDef = TypedDict(
-    "DescribeOptionGroupsMessageRequestTypeDef",
-    {
-        "OptionGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
-        "MaxRecords": int,
-        "EngineName": str,
-        "MajorEngineVersion": str,
-    },
-    total=False,
-)
 
-_RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
-    "_RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+_RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef",
     {
-        "Engine": str,
+        "DBProxyName": str,
     },
 )
-_OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
-    "_OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+_OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef",
     {
-        "EngineVersion": str,
-        "DBInstanceClass": str,
-        "LicenseModel": str,
-        "AvailabilityZoneGroup": str,
-        "Vpc": bool,
+        "TargetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
         "Marker": str,
+        "MaxRecords": int,
     },
     total=False,
 )
 
-class DescribeOrderableDBInstanceOptionsMessageRequestTypeDef(
-    _RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
-    _OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+
+class DescribeDBProxyTargetGroupsRequestRequestTypeDef(
+    _RequiredDescribeDBProxyTargetGroupsRequestRequestTypeDef,
+    _OptionalDescribeDBProxyTargetGroupsRequestRequestTypeDef,
 ):
     pass
 
-DescribePendingMaintenanceActionsMessageRequestTypeDef = TypedDict(
-    "DescribePendingMaintenanceActionsMessageRequestTypeDef",
-    {
-        "ResourceIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "Marker": str,
-        "MaxRecords": int,
-    },
-    total=False,
-)
-
-DescribeReservedDBInstancesMessageRequestTypeDef = TypedDict(
-    "DescribeReservedDBInstancesMessageRequestTypeDef",
-    {
-        "ReservedDBInstanceId": str,
-        "ReservedDBInstancesOfferingId": str,
-        "DBInstanceClass": str,
-        "Duration": str,
-        "ProductDescription": str,
-        "OfferingType": str,
-        "MultiAZ": bool,
-        "LeaseId": str,
-        "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
-    },
-    total=False,
-)
 
-DescribeReservedDBInstancesOfferingsMessageRequestTypeDef = TypedDict(
-    "DescribeReservedDBInstancesOfferingsMessageRequestTypeDef",
+_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
     {
-        "ReservedDBInstancesOfferingId": str,
-        "DBInstanceClass": str,
-        "Duration": str,
-        "ProductDescription": str,
-        "OfferingType": str,
-        "MultiAZ": bool,
-        "Filters": Sequence[FilterTypeDef],
-        "MaxRecords": int,
-        "Marker": str,
+        "DBProxyName": str,
     },
-    total=False,
 )
-
-DescribeSourceRegionsMessageRequestTypeDef = TypedDict(
-    "DescribeSourceRegionsMessageRequestTypeDef",
+_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
     {
-        "RegionName": str,
-        "MaxRecords": int,
-        "Marker": str,
+        "TargetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredListTagsForResourceMessageRequestTypeDef = TypedDict(
-    "_RequiredListTagsForResourceMessageRequestTypeDef",
-    {
-        "ResourceName": str,
-    },
-)
-_OptionalListTagsForResourceMessageRequestTypeDef = TypedDict(
-    "_OptionalListTagsForResourceMessageRequestTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
 
-class ListTagsForResourceMessageRequestTypeDef(
-    _RequiredListTagsForResourceMessageRequestTypeDef,
-    _OptionalListTagsForResourceMessageRequestTypeDef,
+class DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef(
+    _RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
+    _OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
 ):
     pass
 
-DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef = TypedDict(
-    "DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef",
-    {
-        "BlueGreenDeploymentIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef = TypedDict(
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    {
-        "CertificateIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
+_RequiredDescribeDBProxyTargetsRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeDBProxyTargetsRequestRequestTypeDef",
     {
-        "DBClusterIdentifier": str,
+        "DBProxyName": str,
     },
 )
-_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef",
+_OptionalDescribeDBProxyTargetsRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeDBProxyTargetsRequestRequestTypeDef",
     {
-        "BacktrackIdentifier": str,
+        "TargetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Marker": str,
+        "MaxRecords": int,
     },
     total=False,
 )
 
-class DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef(
-    _RequiredDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
-    _OptionalDescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
+
+class DescribeDBProxyTargetsRequestRequestTypeDef(
+    _RequiredDescribeDBProxyTargetsRequestRequestTypeDef,
+    _OptionalDescribeDBProxyTargetsRequestRequestTypeDef,
 ):
     pass
 
-DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef = TypedDict(
-    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
-    {
-        "DBClusterIdentifier": str,
-        "DBClusterEndpointIdentifier": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
+DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
     {
-        "DBClusterParameterGroupName": str,
+        "DBSecurityGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
-    },
-)
-_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
+DescribeDBSecurityGroupsMessageRequestTypeDef = TypedDict(
+    "DescribeDBSecurityGroupsMessageRequestTypeDef",
     {
-        "Source": str,
+        "DBSecurityGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-class DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef(
-    _RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    _OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-):
-    pass
-
-DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
+DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
     {
-        "DBClusterIdentifier": str,
-        "DBClusterSnapshotIdentifier": str,
+        "DBInstanceIdentifier": str,
+        "DBSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
         "IncludeShared": bool,
         "IncludePublic": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "DbiResourceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef = TypedDict(
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
+DescribeDBSnapshotsMessageRequestTypeDef = TypedDict(
+    "DescribeDBSnapshotsMessageRequestTypeDef",
     {
-        "DBClusterIdentifier": str,
+        "DBInstanceIdentifier": str,
+        "DBSnapshotIdentifier": str,
+        "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
+        "MaxRecords": int,
+        "Marker": str,
         "IncludeShared": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef = TypedDict(
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    {
-        "Engine": str,
-        "EngineVersion": str,
-        "DBParameterGroupFamily": str,
-        "Filters": Sequence[FilterTypeDef],
-        "DefaultOnly": bool,
-        "ListSupportedCharacterSets": bool,
-        "ListSupportedTimezones": bool,
-        "IncludeAll": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "IncludePublic": bool,
+        "DbiResourceId": str,
     },
     total=False,
 )
 
-DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef = TypedDict(
-    "DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef",
+DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     {
-        "DbiResourceId": str,
-        "DBInstanceIdentifier": str,
+        "DBSubnetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "DBInstanceAutomatedBackupsArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef = TypedDict(
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
+DescribeDBSubnetGroupsMessageRequestTypeDef = TypedDict(
+    "DescribeDBSubnetGroupsMessageRequestTypeDef",
     {
-        "DBInstanceIdentifier": str,
+        "DBSubnetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
+_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
     {
-        "DBInstanceIdentifier": str,
+        "DBParameterGroupFamily": str,
     },
 )
-_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef",
+_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
     {
-        "FilenameContains": str,
-        "FileLastWritten": int,
-        "FileSize": int,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef(
-    _RequiredDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
-    _OptionalDescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
+
+class DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef(
+    _RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
+    _OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
 ):
     pass
 
-DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
-    {
-        "DBParameterGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
+_RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef",
     {
-        "DBParameterGroupName": str,
+        "DBParameterGroupFamily": str,
     },
 )
-_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
+_OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef",
     {
-        "Source": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-class DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef(
-    _RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    _OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
+
+class DescribeEngineDefaultClusterParametersMessageRequestTypeDef(
+    _RequiredDescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    _OptionalDescribeEngineDefaultClusterParametersMessageRequestTypeDef,
 ):
     pass
 
-DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef = TypedDict(
-    "DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef",
-    {
-        "DBProxyName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef = TypedDict(
-    "DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef",
-    {
-        "DBProxyName": str,
-        "DBProxyEndpointName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
+_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     {
-        "DBProxyName": str,
+        "DBParameterGroupFamily": str,
     },
 )
-_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef",
+_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     {
-        "TargetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef(
-    _RequiredDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
-    _OptionalDescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
+
+class DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef(
+    _RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
+    _OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
 ):
     pass
 
-_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
+
+_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef",
     {
-        "DBProxyName": str,
+        "DBParameterGroupFamily": str,
     },
 )
-_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef",
+_OptionalDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultParametersMessageRequestTypeDef",
     {
-        "TargetGroupName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-class DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef(
-    _RequiredDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
-    _OptionalDescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
+
+class DescribeEngineDefaultParametersMessageRequestTypeDef(
+    _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef,
+    _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef,
 ):
     pass
 
-DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef",
-    {
-        "DBSecurityGroupName": str,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef",
-    {
-        "DBInstanceIdentifier": str,
-        "DBSnapshotIdentifier": str,
-        "SnapshotType": str,
-        "Filters": Sequence[FilterTypeDef],
-        "IncludeShared": bool,
-        "IncludePublic": bool,
-        "DbiResourceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
+DescribeEventCategoriesMessageRequestTypeDef = TypedDict(
+    "DescribeEventCategoriesMessageRequestTypeDef",
     {
-        "DBSubnetGroupName": str,
+        "SourceType": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
     },
     total=False,
 )
 
-_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
-    {
-        "DBParameterGroupFamily": str,
-    },
-)
-_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef",
+DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     {
+        "SubscriptionName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef(
-    _RequiredDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-    _OptionalDescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
-        "DBParameterGroupFamily": str,
-    },
-)
-_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+DescribeEventSubscriptionsMessageRequestTypeDef = TypedDict(
+    "DescribeEventSubscriptionsMessageRequestTypeDef",
     {
+        "SubscriptionName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
-class DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef(
-    _RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    _OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-):
-    pass
-
-DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef = TypedDict(
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     {
-        "SubscriptionName": str,
+        "SourceIdentifier": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "EventCategories": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+DescribeEventsMessageRequestTypeDef = TypedDict(
+    "DescribeEventsMessageRequestTypeDef",
     {
         "SourceIdentifier": str,
         "SourceType": SourceTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "Duration": int,
         "EventCategories": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
 DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef = TypedDict(
     "DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef",
     {
         "ExportTaskIdentifier": str,
         "SourceArn": str,
         "Filters": Sequence[FilterTypeDef],
         "SourceType": ExportSourceTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeExportTasksMessageRequestTypeDef = TypedDict(
+    "DescribeExportTasksMessageRequestTypeDef",
+    {
+        "ExportTaskIdentifier": str,
+        "SourceArn": str,
+        "Filters": Sequence[FilterTypeDef],
+        "Marker": str,
+        "MaxRecords": int,
+        "SourceType": ExportSourceTypeType,
     },
     total=False,
 )
 
 DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
     "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeGlobalClustersMessageRequestTypeDef = TypedDict(
+    "DescribeGlobalClustersMessageRequestTypeDef",
+    {
+        "GlobalClusterIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
 _RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef = TypedDict(
     "_RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
     {
@@ -5003,33 +5056,73 @@
     },
 )
 _OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef",
     {
         "MajorEngineVersion": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef(
     _RequiredDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
     _OptionalDescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
 ):
     pass
 
+
+_RequiredDescribeOptionGroupOptionsMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeOptionGroupOptionsMessageRequestTypeDef",
+    {
+        "EngineName": str,
+    },
+)
+_OptionalDescribeOptionGroupOptionsMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeOptionGroupOptionsMessageRequestTypeDef",
+    {
+        "MajorEngineVersion": str,
+        "Filters": Sequence[FilterTypeDef],
+        "MaxRecords": int,
+        "Marker": str,
+    },
+    total=False,
+)
+
+
+class DescribeOptionGroupOptionsMessageRequestTypeDef(
+    _RequiredDescribeOptionGroupOptionsMessageRequestTypeDef,
+    _OptionalDescribeOptionGroupOptionsMessageRequestTypeDef,
+):
+    pass
+
+
 DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef = TypedDict(
     "DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef",
     {
         "OptionGroupName": str,
         "Filters": Sequence[FilterTypeDef],
         "EngineName": str,
         "MajorEngineVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeOptionGroupsMessageRequestTypeDef = TypedDict(
+    "DescribeOptionGroupsMessageRequestTypeDef",
+    {
+        "OptionGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "Marker": str,
+        "MaxRecords": int,
+        "EngineName": str,
+        "MajorEngineVersion": str,
     },
     total=False,
 )
 
 _RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef = TypedDict(
     "_RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     {
@@ -5041,100 +5134,188 @@
     {
         "EngineVersion": str,
         "DBInstanceClass": str,
         "LicenseModel": str,
         "AvailabilityZoneGroup": str,
         "Vpc": bool,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef(
     _RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     _OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
 ):
     pass
 
+
+_RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
+    "_RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    {
+        "Engine": str,
+    },
+)
+_OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
+    "_OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    {
+        "EngineVersion": str,
+        "DBInstanceClass": str,
+        "LicenseModel": str,
+        "AvailabilityZoneGroup": str,
+        "Vpc": bool,
+        "Filters": Sequence[FilterTypeDef],
+        "MaxRecords": int,
+        "Marker": str,
+    },
+    total=False,
+)
+
+
+class DescribeOrderableDBInstanceOptionsMessageRequestTypeDef(
+    _RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    _OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+):
+    pass
+
+
 DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef = (
     TypedDict(
         "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
         {
             "ResourceIdentifier": str,
             "Filters": Sequence[FilterTypeDef],
-            "PaginationConfig": PaginatorConfigTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
         },
         total=False,
     )
 )
 
+DescribePendingMaintenanceActionsMessageRequestTypeDef = TypedDict(
+    "DescribePendingMaintenanceActionsMessageRequestTypeDef",
+    {
+        "ResourceIdentifier": str,
+        "Filters": Sequence[FilterTypeDef],
+        "Marker": str,
+        "MaxRecords": int,
+    },
+    total=False,
+)
+
 DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef = TypedDict(
     "DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef",
     {
         "ReservedDBInstanceId": str,
         "ReservedDBInstancesOfferingId": str,
         "DBInstanceClass": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MultiAZ": bool,
         "LeaseId": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeReservedDBInstancesMessageRequestTypeDef = TypedDict(
+    "DescribeReservedDBInstancesMessageRequestTypeDef",
+    {
+        "ReservedDBInstanceId": str,
+        "ReservedDBInstancesOfferingId": str,
+        "DBInstanceClass": str,
+        "Duration": str,
+        "ProductDescription": str,
+        "OfferingType": str,
+        "MultiAZ": bool,
+        "LeaseId": str,
+        "Filters": Sequence[FilterTypeDef],
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
 DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef = TypedDict(
     "DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef",
     {
         "ReservedDBInstancesOfferingId": str,
         "DBInstanceClass": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MultiAZ": bool,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeReservedDBInstancesOfferingsMessageRequestTypeDef = TypedDict(
+    "DescribeReservedDBInstancesOfferingsMessageRequestTypeDef",
+    {
+        "ReservedDBInstancesOfferingId": str,
+        "DBInstanceClass": str,
+        "Duration": str,
+        "ProductDescription": str,
+        "OfferingType": str,
+        "MultiAZ": bool,
+        "Filters": Sequence[FilterTypeDef],
+        "MaxRecords": int,
+        "Marker": str,
     },
     total=False,
 )
 
 DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef = TypedDict(
     "DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef",
     {
         "RegionName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
-    "_RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+DescribeSourceRegionsMessageRequestTypeDef = TypedDict(
+    "DescribeSourceRegionsMessageRequestTypeDef",
     {
-        "DBInstanceIdentifier": str,
-        "LogFileName": str,
+        "RegionName": str,
+        "MaxRecords": int,
+        "Marker": str,
+        "Filters": Sequence[FilterTypeDef],
     },
+    total=False,
 )
-_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef = TypedDict(
-    "_OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef",
+
+_RequiredListTagsForResourceMessageRequestTypeDef = TypedDict(
+    "_RequiredListTagsForResourceMessageRequestTypeDef",
+    {
+        "ResourceName": str,
+    },
+)
+_OptionalListTagsForResourceMessageRequestTypeDef = TypedDict(
+    "_OptionalListTagsForResourceMessageRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
-class DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef(
-    _RequiredDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
-    _OptionalDownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
+
+class ListTagsForResourceMessageRequestTypeDef(
+    _RequiredListTagsForResourceMessageRequestTypeDef,
+    _OptionalListTagsForResourceMessageRequestTypeDef,
 ):
     pass
 
+
 DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef = TypedDict(
     "DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
@@ -5265,41 +5446,41 @@
 )
 
 DescribeDBLogFilesResponseTypeDef = TypedDict(
     "DescribeDBLogFilesResponseTypeDef",
     {
         "DescribeDBLogFiles": List[DescribeDBLogFilesDetailsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventCategoriesMessageTypeDef = TypedDict(
     "EventCategoriesMessageTypeDef",
     {
         "EventCategoriesMapList": List[EventCategoriesMapTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventsMessageTypeDef = TypedDict(
     "EventsMessageTypeDef",
     {
         "Marker": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportTasksMessageTypeDef = TypedDict(
     "ExportTasksMessageTypeDef",
     {
         "Marker": str,
         "ExportTasks": List[ExportTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalClusterTypeDef = TypedDict(
     "GlobalClusterTypeDef",
     {
         "GlobalClusterIdentifier": str,
@@ -5346,19 +5527,21 @@
         "DBSecurityGroupMemberships": Sequence[str],
         "VpcSecurityGroupMemberships": Sequence[str],
         "OptionSettings": Sequence[OptionSettingTypeDef],
     },
     total=False,
 )
 
+
 class OptionConfigurationTypeDef(
     _RequiredOptionConfigurationTypeDef, _OptionalOptionConfigurationTypeDef
 ):
     pass
 
+
 OptionTypeDef = TypedDict(
     "OptionTypeDef",
     {
         "OptionName": str,
         "OptionDescription": str,
         "Persistent": bool,
         "Permanent": bool,
@@ -5446,90 +5629,90 @@
 )
 
 SourceRegionMessageTypeDef = TypedDict(
     "SourceRegionMessageTypeDef",
     {
         "Marker": str,
         "SourceRegions": List[SourceRegionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyDBClusterSnapshotResultTypeDef = TypedDict(
     "CopyDBClusterSnapshotResultTypeDef",
     {
         "DBClusterSnapshot": DBClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBClusterSnapshotResultTypeDef = TypedDict(
     "CreateDBClusterSnapshotResultTypeDef",
     {
         "DBClusterSnapshot": DBClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterSnapshotMessageTypeDef = TypedDict(
     "DBClusterSnapshotMessageTypeDef",
     {
         "Marker": str,
         "DBClusterSnapshots": List[DBClusterSnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBClusterSnapshotResultTypeDef = TypedDict(
     "DeleteDBClusterSnapshotResultTypeDef",
     {
         "DBClusterSnapshot": DBClusterSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OrderableDBInstanceOptionsMessageTypeDef = TypedDict(
     "OrderableDBInstanceOptionsMessageTypeDef",
     {
         "OrderableDBInstanceOptions": List[OrderableDBInstanceOptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBlueGreenDeploymentResponseTypeDef = TypedDict(
     "CreateBlueGreenDeploymentResponseTypeDef",
     {
         "BlueGreenDeployment": BlueGreenDeploymentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBlueGreenDeploymentResponseTypeDef = TypedDict(
     "DeleteBlueGreenDeploymentResponseTypeDef",
     {
         "BlueGreenDeployment": BlueGreenDeploymentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBlueGreenDeploymentsResponseTypeDef = TypedDict(
     "DescribeBlueGreenDeploymentsResponseTypeDef",
     {
         "BlueGreenDeployments": List[BlueGreenDeploymentTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SwitchoverBlueGreenDeploymentResponseTypeDef = TypedDict(
     "SwitchoverBlueGreenDeploymentResponseTypeDef",
     {
         "BlueGreenDeployment": BlueGreenDeploymentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterTypeDef = TypedDict(
     "DBClusterTypeDef",
     {
         "AllocatedStorage": int,
@@ -5599,295 +5782,296 @@
         "PerformanceInsightsEnabled": bool,
         "PerformanceInsightsKMSKeyId": str,
         "PerformanceInsightsRetentionPeriod": int,
         "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationInfoTypeDef,
         "NetworkType": str,
         "DBSystemId": str,
         "MasterUserSecret": MasterUserSecretTypeDef,
+        "IOOptimizedNextAllowedModificationTime": datetime,
     },
     total=False,
 )
 
 DescribeDBProxyTargetGroupsResponseTypeDef = TypedDict(
     "DescribeDBProxyTargetGroupsResponseTypeDef",
     {
         "TargetGroups": List[DBProxyTargetGroupTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBProxyTargetGroupResponseTypeDef = TypedDict(
     "ModifyDBProxyTargetGroupResponseTypeDef",
     {
         "DBProxyTargetGroup": DBProxyTargetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyDBSnapshotResultTypeDef = TypedDict(
     "CopyDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBSnapshotResultTypeDef = TypedDict(
     "CreateDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBSnapshotMessageTypeDef = TypedDict(
     "DBSnapshotMessageTypeDef",
     {
         "Marker": str,
         "DBSnapshots": List[DBSnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBSnapshotResultTypeDef = TypedDict(
     "DeleteDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBSnapshotResultTypeDef = TypedDict(
     "ModifyDBSnapshotResultTypeDef",
     {
         "DBSnapshot": DBSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEngineDefaultClusterParametersResultTypeDef = TypedDict(
     "DescribeEngineDefaultClusterParametersResultTypeDef",
     {
         "EngineDefaults": EngineDefaultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEngineDefaultParametersResultTypeDef = TypedDict(
     "DescribeEngineDefaultParametersResultTypeDef",
     {
         "EngineDefaults": EngineDefaultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBClusterSnapshotAttributesResultTypeDef = TypedDict(
     "DescribeDBClusterSnapshotAttributesResultTypeDef",
     {
         "DBClusterSnapshotAttributesResult": DBClusterSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBClusterSnapshotAttributeResultTypeDef = TypedDict(
     "ModifyDBClusterSnapshotAttributeResultTypeDef",
     {
         "DBClusterSnapshotAttributesResult": DBClusterSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBEngineVersionMessageTypeDef = TypedDict(
     "DBEngineVersionMessageTypeDef",
     {
         "Marker": str,
         "DBEngineVersions": List[DBEngineVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBInstanceAutomatedBackupMessageTypeDef = TypedDict(
     "DBInstanceAutomatedBackupMessageTypeDef",
     {
         "Marker": str,
         "DBInstanceAutomatedBackups": List[DBInstanceAutomatedBackupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBInstanceAutomatedBackupResultTypeDef = TypedDict(
     "DeleteDBInstanceAutomatedBackupResultTypeDef",
     {
         "DBInstanceAutomatedBackup": DBInstanceAutomatedBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDBInstanceAutomatedBackupsReplicationResultTypeDef = TypedDict(
     "StartDBInstanceAutomatedBackupsReplicationResultTypeDef",
     {
         "DBInstanceAutomatedBackup": DBInstanceAutomatedBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopDBInstanceAutomatedBackupsReplicationResultTypeDef = TypedDict(
     "StopDBInstanceAutomatedBackupsReplicationResultTypeDef",
     {
         "DBInstanceAutomatedBackup": DBInstanceAutomatedBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBProxyTargetsResponseTypeDef = TypedDict(
     "DescribeDBProxyTargetsResponseTypeDef",
     {
         "Targets": List[DBProxyTargetTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterDBProxyTargetsResponseTypeDef = TypedDict(
     "RegisterDBProxyTargetsResponseTypeDef",
     {
         "DBProxyTargets": List[DBProxyTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBProxyResponseTypeDef = TypedDict(
     "CreateDBProxyResponseTypeDef",
     {
         "DBProxy": DBProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBProxyResponseTypeDef = TypedDict(
     "DeleteDBProxyResponseTypeDef",
     {
         "DBProxy": DBProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBProxiesResponseTypeDef = TypedDict(
     "DescribeDBProxiesResponseTypeDef",
     {
         "DBProxies": List[DBProxyTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBProxyResponseTypeDef = TypedDict(
     "ModifyDBProxyResponseTypeDef",
     {
         "DBProxy": DBProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthorizeDBSecurityGroupIngressResultTypeDef = TypedDict(
     "AuthorizeDBSecurityGroupIngressResultTypeDef",
     {
         "DBSecurityGroup": DBSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBSecurityGroupResultTypeDef = TypedDict(
     "CreateDBSecurityGroupResultTypeDef",
     {
         "DBSecurityGroup": DBSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBSecurityGroupMessageTypeDef = TypedDict(
     "DBSecurityGroupMessageTypeDef",
     {
         "Marker": str,
         "DBSecurityGroups": List[DBSecurityGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RevokeDBSecurityGroupIngressResultTypeDef = TypedDict(
     "RevokeDBSecurityGroupIngressResultTypeDef",
     {
         "DBSecurityGroup": DBSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDBSnapshotAttributesResultTypeDef = TypedDict(
     "DescribeDBSnapshotAttributesResultTypeDef",
     {
         "DBSnapshotAttributesResult": DBSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBSnapshotAttributeResultTypeDef = TypedDict(
     "ModifyDBSnapshotAttributeResultTypeDef",
     {
         "DBSnapshotAttributesResult": DBSnapshotAttributesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGlobalClusterResultTypeDef = TypedDict(
     "CreateGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGlobalClusterResultTypeDef = TypedDict(
     "DeleteGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverGlobalClusterResultTypeDef = TypedDict(
     "FailoverGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalClustersMessageTypeDef = TypedDict(
     "GlobalClustersMessageTypeDef",
     {
         "Marker": str,
         "GlobalClusters": List[GlobalClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyGlobalClusterResultTypeDef = TypedDict(
     "ModifyGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveFromGlobalClusterResultTypeDef = TypedDict(
     "RemoveFromGlobalClusterResultTypeDef",
     {
         "GlobalCluster": GlobalClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptionGroupOptionTypeDef = TypedDict(
     "OptionGroupOptionTypeDef",
     {
         "Name": str,
@@ -5923,19 +6107,21 @@
         "OptionsToInclude": Sequence[OptionConfigurationTypeDef],
         "OptionsToRemove": Sequence[str],
         "ApplyImmediately": bool,
     },
     total=False,
 )
 
+
 class ModifyOptionGroupMessageRequestTypeDef(
     _RequiredModifyOptionGroupMessageRequestTypeDef, _OptionalModifyOptionGroupMessageRequestTypeDef
 ):
     pass
 
+
 OptionGroupTypeDef = TypedDict(
     "OptionGroupTypeDef",
     {
         "OptionGroupName": str,
         "OptionGroupDescription": str,
         "EngineName": str,
         "MajorEngineVersion": str,
@@ -5964,24 +6150,24 @@
     total=False,
 )
 
 ApplyPendingMaintenanceActionResultTypeDef = TypedDict(
     "ApplyPendingMaintenanceActionResultTypeDef",
     {
         "ResourcePendingMaintenanceActions": ResourcePendingMaintenanceActionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PendingMaintenanceActionsMessageTypeDef = TypedDict(
     "PendingMaintenanceActionsMessageTypeDef",
     {
         "PendingMaintenanceActions": List[ResourcePendingMaintenanceActionsTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidDBInstanceModificationsMessageTypeDef = TypedDict(
     "ValidDBInstanceModificationsMessageTypeDef",
     {
         "Storage": List[ValidStorageOptionsTypeDef],
@@ -5990,180 +6176,180 @@
     total=False,
 )
 
 PurchaseReservedDBInstancesOfferingResultTypeDef = TypedDict(
     "PurchaseReservedDBInstancesOfferingResultTypeDef",
     {
         "ReservedDBInstance": ReservedDBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedDBInstanceMessageTypeDef = TypedDict(
     "ReservedDBInstanceMessageTypeDef",
     {
         "Marker": str,
         "ReservedDBInstances": List[ReservedDBInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedDBInstancesOfferingMessageTypeDef = TypedDict(
     "ReservedDBInstancesOfferingMessageTypeDef",
     {
         "Marker": str,
         "ReservedDBInstancesOfferings": List[ReservedDBInstancesOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBClusterResultTypeDef = TypedDict(
     "CreateDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBClusterMessageTypeDef = TypedDict(
     "DBClusterMessageTypeDef",
     {
         "Marker": str,
         "DBClusters": List[DBClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBClusterResultTypeDef = TypedDict(
     "DeleteDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverDBClusterResultTypeDef = TypedDict(
     "FailoverDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBClusterResultTypeDef = TypedDict(
     "ModifyDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PromoteReadReplicaDBClusterResultTypeDef = TypedDict(
     "PromoteReadReplicaDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootDBClusterResultTypeDef = TypedDict(
     "RebootDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBClusterFromS3ResultTypeDef = TypedDict(
     "RestoreDBClusterFromS3ResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBClusterFromSnapshotResultTypeDef = TypedDict(
     "RestoreDBClusterFromSnapshotResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBClusterToPointInTimeResultTypeDef = TypedDict(
     "RestoreDBClusterToPointInTimeResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDBClusterResultTypeDef = TypedDict(
     "StartDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopDBClusterResultTypeDef = TypedDict(
     "StopDBClusterResultTypeDef",
     {
         "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptionGroupOptionsMessageTypeDef = TypedDict(
     "OptionGroupOptionsMessageTypeDef",
     {
         "OptionGroupOptions": List[OptionGroupOptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyOptionGroupResultTypeDef = TypedDict(
     "CopyOptionGroupResultTypeDef",
     {
         "OptionGroup": OptionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOptionGroupResultTypeDef = TypedDict(
     "CreateOptionGroupResultTypeDef",
     {
         "OptionGroup": OptionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyOptionGroupResultTypeDef = TypedDict(
     "ModifyOptionGroupResultTypeDef",
     {
         "OptionGroup": OptionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OptionGroupsTypeDef = TypedDict(
     "OptionGroupsTypeDef",
     {
         "OptionGroupsList": List[OptionGroupTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBSubnetGroupResultTypeDef = TypedDict(
     "CreateDBSubnetGroupResultTypeDef",
     {
         "DBSubnetGroup": DBSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBInstanceTypeDef = TypedDict(
     "DBInstanceTypeDef",
     {
         "DBInstanceIdentifier": str,
@@ -6244,140 +6430,141 @@
         "BackupTarget": str,
         "NetworkType": str,
         "ActivityStreamPolicyStatus": ActivityStreamPolicyStatusType,
         "StorageThroughput": int,
         "DBSystemId": str,
         "MasterUserSecret": MasterUserSecretTypeDef,
         "CertificateDetails": CertificateDetailsTypeDef,
+        "ReadReplicaSourceDBClusterIdentifier": str,
     },
     total=False,
 )
 
 DBSubnetGroupMessageTypeDef = TypedDict(
     "DBSubnetGroupMessageTypeDef",
     {
         "Marker": str,
         "DBSubnetGroups": List[DBSubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBSubnetGroupResultTypeDef = TypedDict(
     "ModifyDBSubnetGroupResultTypeDef",
     {
         "DBSubnetGroup": DBSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeValidDBInstanceModificationsResultTypeDef = TypedDict(
     "DescribeValidDBInstanceModificationsResultTypeDef",
     {
         "ValidDBInstanceModificationsMessage": ValidDBInstanceModificationsMessageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBInstanceReadReplicaResultTypeDef = TypedDict(
     "CreateDBInstanceReadReplicaResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDBInstanceResultTypeDef = TypedDict(
     "CreateDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DBInstanceMessageTypeDef = TypedDict(
     "DBInstanceMessageTypeDef",
     {
         "Marker": str,
         "DBInstances": List[DBInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDBInstanceResultTypeDef = TypedDict(
     "DeleteDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyDBInstanceResultTypeDef = TypedDict(
     "ModifyDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PromoteReadReplicaResultTypeDef = TypedDict(
     "PromoteReadReplicaResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootDBInstanceResultTypeDef = TypedDict(
     "RebootDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBInstanceFromDBSnapshotResultTypeDef = TypedDict(
     "RestoreDBInstanceFromDBSnapshotResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBInstanceFromS3ResultTypeDef = TypedDict(
     "RestoreDBInstanceFromS3ResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreDBInstanceToPointInTimeResultTypeDef = TypedDict(
     "RestoreDBInstanceToPointInTimeResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDBInstanceResultTypeDef = TypedDict(
     "StartDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopDBInstanceResultTypeDef = TypedDict(
     "StopDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SwitchoverReadReplicaResultTypeDef = TypedDict(
     "SwitchoverReadReplicaResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/waiter.py` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds/waiter.pyi` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/PKG-INFO` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rds
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RDS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RDS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rds"></a>
 
 # types-aiobotocore-rds
 
 [![PyPI - types-aiobotocore-rds](https://img.shields.io/pypi/v/types-aiobotocore-rds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rds.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rds)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rds?color=blue)](https://pypistats.org/packages/types-aiobotocore-rds)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RDS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
+[aiobotocore.RDS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rds.html#RDS)
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
 [types-aiobotocore-rds docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/).
 
 See how it helps to find and fix potential bugs:
 
@@ -571,15 +571,14 @@
 
 `types_aiobotocore_rds.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rds.type_defs import (
     AccountQuotaTypeDef,
-    ResponseMetadataTypeDef,
     AddRoleToDBClusterMessageRequestTypeDef,
     AddRoleToDBInstanceMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AuthorizeDBSecurityGroupIngressMessageRequestTypeDef,
@@ -603,18 +602,22 @@
     ServerlessV2ScalingConfigurationTypeDef,
     ProcessorFeatureTypeDef,
     DBProxyEndpointTypeDef,
     UserAuthConfigTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     CustomDBEngineVersionAMITypeDef,
     DBClusterBacktrackTypeDef,
+    DBClusterBacktrackResponseMetadataTypeDef,
+    DBClusterCapacityInfoTypeDef,
     DBClusterEndpointTypeDef,
+    DBClusterEndpointResponseMetadataTypeDef,
     DBClusterMemberTypeDef,
     DBClusterOptionGroupStatusTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     DomainMembershipTypeDef,
     MasterUserSecretTypeDef,
     ScalingConfigurationInfoTypeDef,
     ServerlessV2ScalingConfigurationInfoTypeDef,
     VpcSecurityGroupMembershipTypeDef,
@@ -624,14 +627,15 @@
     RestoreWindowTypeDef,
     DBInstanceRoleTypeDef,
     DBInstanceStatusInfoTypeDef,
     DBParameterGroupStatusTypeDef,
     DBSecurityGroupMembershipTypeDef,
     EndpointTypeDef,
     OptionGroupMembershipTypeDef,
+    DBParameterGroupNameMessageTypeDef,
     TargetHealthTypeDef,
     UserAuthConfigInfoTypeDef,
     EC2SecurityGroupTypeDef,
     IPRangeTypeDef,
     DBSnapshotAttributeTypeDef,
     DeleteBlueGreenDeploymentRequestRequestTypeDef,
     DeleteCustomDBEngineVersionMessageRequestTypeDef,
@@ -648,83 +652,80 @@
     DeleteDBSnapshotMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     DeleteOptionGroupMessageRequestTypeDef,
     DeregisterDBProxyTargetsRequestRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeDBLogFilesDetailsTypeDef,
     DescribeDBSnapshotAttributesMessageRequestTypeDef,
     DescribeValidDBInstanceModificationsMessageRequestTypeDef,
     DoubleRangeTypeDef,
+    DownloadDBLogFilePortionDetailsTypeDef,
+    DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
     DownloadDBLogFilePortionMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
+    ExportTaskResponseMetadataTypeDef,
     ExportTaskTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     FailoverGlobalClusterMessageRequestTypeDef,
     FailoverStateTypeDef,
     GlobalClusterMemberTypeDef,
     MinimumEngineVersionPerAllowedValueTypeDef,
     ModifyActivityStreamRequestRequestTypeDef,
+    ModifyActivityStreamResponseTypeDef,
     ModifyCertificatesMessageRequestTypeDef,
     ModifyCurrentDBClusterCapacityMessageRequestTypeDef,
     ModifyCustomDBEngineVersionMessageRequestTypeDef,
     ModifyDBClusterEndpointMessageRequestTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBProxyEndpointRequestRequestTypeDef,
     ModifyDBSnapshotAttributeMessageRequestTypeDef,
     ModifyDBSnapshotMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
     OptionSettingTypeDef,
     OptionVersionTypeDef,
     OutpostTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PromoteReadReplicaDBClusterMessageRequestTypeDef,
     PromoteReadReplicaMessageRequestTypeDef,
     RangeTypeDef,
     RebootDBClusterMessageRequestTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RecurringChargeTypeDef,
     RegisterDBProxyTargetsRequestRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveRoleFromDBClusterMessageRequestTypeDef,
     RemoveRoleFromDBInstanceMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeDBSecurityGroupIngressMessageRequestTypeDef,
     SourceRegionTypeDef,
     StartActivityStreamRequestRequestTypeDef,
+    StartActivityStreamResponseTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StartDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     StartDBInstanceMessageRequestTypeDef,
     StartExportTaskMessageRequestTypeDef,
     StopActivityStreamRequestRequestTypeDef,
+    StopActivityStreamResponseTypeDef,
     StopDBClusterMessageRequestTypeDef,
     StopDBInstanceAutomatedBackupsReplicationMessageRequestTypeDef,
     StopDBInstanceMessageRequestTypeDef,
     SwitchoverBlueGreenDeploymentRequestRequestTypeDef,
     SwitchoverReadReplicaMessageRequestTypeDef,
     AccountAttributesMessageTypeDef,
-    DBClusterBacktrackResponseMetadataTypeDef,
-    DBClusterCapacityInfoTypeDef,
-    DBClusterEndpointResponseMetadataTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
-    DBParameterGroupNameMessageTypeDef,
-    DownloadDBLogFilePortionDetailsTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportTaskResponseMetadataTypeDef,
-    ModifyActivityStreamResponseTypeDef,
-    StartActivityStreamResponseTypeDef,
-    StopActivityStreamResponseTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
     CreateEventSubscriptionResultTypeDef,
     DeleteEventSubscriptionResultTypeDef,
     EventSubscriptionsMessageTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
@@ -793,85 +794,84 @@
     DBEngineVersionResponseMetadataTypeDef,
     DBEngineVersionTypeDef,
     DBInstanceAutomatedBackupTypeDef,
     DBProxyTargetTypeDef,
     DBProxyTypeDef,
     DBSecurityGroupTypeDef,
     DBSnapshotAttributesResultTypeDef,
+    DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef,
     DescribeBlueGreenDeploymentsRequestRequestTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
+    DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
     DescribeDBClusterBacktracksMessageRequestTypeDef,
+    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
     DescribeDBClusterEndpointsMessageRequestTypeDef,
+    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
     DescribeDBClusterParameterGroupsMessageRequestTypeDef,
+    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
     DescribeDBClusterParametersMessageRequestTypeDef,
+    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
     DescribeDBClusterSnapshotsMessageRequestTypeDef,
+    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
     DescribeDBClustersMessageRequestTypeDef,
+    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
     DescribeDBEngineVersionsMessageRequestTypeDef,
+    DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef,
     DescribeDBInstanceAutomatedBackupsMessageRequestTypeDef,
+    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
     DescribeDBInstancesMessageRequestTypeDef,
+    DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
     DescribeDBLogFilesMessageRequestTypeDef,
+    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
     DescribeDBParameterGroupsMessageRequestTypeDef,
+    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
     DescribeDBParametersMessageRequestTypeDef,
+    DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef,
     DescribeDBProxiesRequestRequestTypeDef,
+    DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef,
     DescribeDBProxyEndpointsRequestRequestTypeDef,
+    DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
     DescribeDBProxyTargetGroupsRequestRequestTypeDef,
+    DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
     DescribeDBProxyTargetsRequestRequestTypeDef,
+    DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef,
     DescribeDBSecurityGroupsMessageRequestTypeDef,
+    DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef,
     DescribeDBSnapshotsMessageRequestTypeDef,
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
+    DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef,
     DescribeExportTasksMessageRequestTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
+    DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
     DescribeOptionGroupOptionsMessageRequestTypeDef,
+    DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef,
     DescribeOptionGroupsMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
+    DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef,
     DescribeReservedDBInstancesMessageRequestTypeDef,
+    DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef,
     DescribeReservedDBInstancesOfferingsMessageRequestTypeDef,
+    DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef,
     DescribeSourceRegionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeBlueGreenDeploymentsRequestDescribeBlueGreenDeploymentsPaginateTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeDBClusterBacktracksMessageDescribeDBClusterBacktracksPaginateTypeDef,
-    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstanceAutomatedBackupsMessageDescribeDBInstanceAutomatedBackupsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBLogFilesMessageDescribeDBLogFilesPaginateTypeDef,
-    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
-    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    DescribeDBProxiesRequestDescribeDBProxiesPaginateTypeDef,
-    DescribeDBProxyEndpointsRequestDescribeDBProxyEndpointsPaginateTypeDef,
-    DescribeDBProxyTargetGroupsRequestDescribeDBProxyTargetGroupsPaginateTypeDef,
-    DescribeDBProxyTargetsRequestDescribeDBProxyTargetsPaginateTypeDef,
-    DescribeDBSecurityGroupsMessageDescribeDBSecurityGroupsPaginateTypeDef,
-    DescribeDBSnapshotsMessageDescribeDBSnapshotsPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultClusterParametersMessageDescribeEngineDefaultClusterParametersPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeExportTasksMessageDescribeExportTasksPaginateTypeDef,
-    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
-    DescribeOptionGroupOptionsMessageDescribeOptionGroupOptionsPaginateTypeDef,
-    DescribeOptionGroupsMessageDescribeOptionGroupsPaginateTypeDef,
-    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
-    DescribeReservedDBInstancesMessageDescribeReservedDBInstancesPaginateTypeDef,
-    DescribeReservedDBInstancesOfferingsMessageDescribeReservedDBInstancesOfferingsPaginateTypeDef,
-    DescribeSourceRegionsMessageDescribeSourceRegionsPaginateTypeDef,
-    DownloadDBLogFilePortionMessageDownloadDBLogFilePortionPaginateTypeDef,
     DescribeDBClusterSnapshotsMessageDBClusterSnapshotAvailableWaitTypeDef,
     DescribeDBClusterSnapshotsMessageDBClusterSnapshotDeletedWaitTypeDef,
     DescribeDBClustersMessageDBClusterAvailableWaitTypeDef,
     DescribeDBClustersMessageDBClusterDeletedWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef,
     DescribeDBSnapshotsMessageDBSnapshotAvailableWaitTypeDef,
@@ -990,43 +990,43 @@
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

### Comparing `types-aiobotocore-rds-2.5.0.post1/types_aiobotocore_rds.egg-info/SOURCES.txt` & `types-aiobotocore-rds-2.5.1/types_aiobotocore_rds.egg-info/SOURCES.txt`

 * *Files identical despite different names*

