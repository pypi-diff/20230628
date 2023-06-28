# Comparing `tmp/types-aiobotocore-neptune-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-neptune-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-neptune-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-neptune-2.5.1.tar", last modified: Wed Jun 28 01:43:54 2023, max compression
```

## Comparing `types-aiobotocore-neptune-2.5.0.post1.tar` & `types-aiobotocore-neptune-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.387462 types-aiobotocore-neptune-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    26136 2023-03-11 12:27:03.379462 types-aiobotocore-neptune-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    24565 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.387462 types-aiobotocore-neptune-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.379462 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/
--rw-r--r--   0 runner    (1001) docker     (123)     5033 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5032 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    70641 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    70545 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11053 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11051 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    22326 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    22307 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    83879 2023-03-11 12:19:06.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    83802 2023-03-11 12:19:05.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:01.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2901 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2899 2023-03-11 12:19:02.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.379462 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    26136 2023-03-11 12:27:03.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      886 2023-03-11 12:27:03.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:27:03.000000 types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.282183 types-aiobotocore-neptune-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    26169 2023-06-28 01:43:54.282183 types-aiobotocore-neptune-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    24604 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:54.282183 types-aiobotocore-neptune-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.278183 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/
+-rw-r--r--   0 runner    (1001) docker     (123)     5033 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5032 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70635 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70539 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11262 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11260 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    22262 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22244 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    84596 2023-06-28 01:35:49.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    84519 2023-06-28 01:35:48.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:46.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2901 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2899 2023-06-28 01:35:47.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.282183 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    26169 2023-06-28 01:43:54.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      886 2023-06-28 01:43:54.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:54.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:54.000000 types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/LICENSE` & `types-aiobotocore-neptune-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/PKG-INFO` & `types-aiobotocore-neptune-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-neptune
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Neptune 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Neptune 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-neptune"></a>
 
 # types-aiobotocore-neptune
 
 [![PyPI - types-aiobotocore-neptune](https://img.shields.io/pypi/v/types-aiobotocore-neptune.svg?color=blue)](https://pypi.org/project/types-aiobotocore-neptune)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-neptune.svg?color=blue)](https://pypi.org/project/types-aiobotocore-neptune)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-neptune?color=blue)](https://pypistats.org/packages/types-aiobotocore-neptune)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Neptune 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
+[aiobotocore.Neptune 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
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
 [types-aiobotocore-neptune docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/).
 
 See how it helps to find and fix potential bugs:
 
@@ -424,88 +424,89 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_neptune.type_defs import (
     AddRoleToDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     CharacterSetTypeDef,
     CloudwatchLogsExportConfigurationTypeDef,
+    PendingCloudwatchLogsExportsTypeDef,
     DBClusterParameterGroupTypeDef,
     DBClusterSnapshotTypeDef,
     DBParameterGroupTypeDef,
+    CreateDBClusterEndpointOutputTypeDef,
     ServerlessV2ScalingConfigurationTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     DBClusterEndpointTypeDef,
     DBClusterMemberTypeDef,
     DBClusterOptionGroupStatusTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     ServerlessV2ScalingConfigurationInfoTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     TimezoneTypeDef,
     UpgradeTargetTypeDef,
     DBInstanceStatusInfoTypeDef,
     DBParameterGroupStatusTypeDef,
     DBSecurityGroupMembershipTypeDef,
     DomainMembershipTypeDef,
     EndpointTypeDef,
     OptionGroupMembershipTypeDef,
+    DBParameterGroupNameMessageTypeDef,
     DeleteDBClusterEndpointMessageRequestTypeDef,
+    DeleteDBClusterEndpointOutputTypeDef,
     DeleteDBClusterMessageRequestTypeDef,
     DeleteDBClusterParameterGroupMessageRequestTypeDef,
     DeleteDBClusterSnapshotMessageRequestTypeDef,
     DeleteDBInstanceMessageRequestTypeDef,
     DeleteDBParameterGroupMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
     DescribeValidDBInstanceModificationsMessageRequestTypeDef,
     DoubleRangeTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     FailoverGlobalClusterMessageRequestTypeDef,
     GlobalClusterMemberTypeDef,
     ModifyDBClusterEndpointMessageRequestTypeDef,
+    ModifyDBClusterEndpointOutputTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
-    PendingCloudwatchLogsExportsTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PromoteReadReplicaDBClusterMessageRequestTypeDef,
     RangeTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveRoleFromDBClusterMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StopDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
-    CreateDBClusterEndpointOutputTypeDef,
     CreateEventSubscriptionResultTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
-    DBParameterGroupNameMessageTypeDef,
-    DeleteDBClusterEndpointOutputTypeDef,
     DeleteEventSubscriptionResultTypeDef,
-    EmptyResponseMetadataTypeDef,
     EventSubscriptionsMessageTypeDef,
-    ModifyDBClusterEndpointOutputTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopyDBClusterParameterGroupMessageRequestTypeDef,
     CopyDBClusterSnapshotMessageRequestTypeDef,
     CopyDBParameterGroupMessageRequestTypeDef,
     CreateDBClusterEndpointMessageRequestTypeDef,
@@ -515,14 +516,16 @@
     CreateDBParameterGroupMessageRequestTypeDef,
     CreateDBSubnetGroupMessageRequestTypeDef,
     CreateEventSubscriptionMessageRequestTypeDef,
     TagListMessageTypeDef,
     OrderableDBInstanceOptionTypeDef,
     SubnetTypeDef,
     ModifyDBInstanceMessageRequestTypeDef,
+    ClusterPendingModifiedValuesTypeDef,
+    PendingModifiedValuesTypeDef,
     CopyDBClusterParameterGroupResultTypeDef,
     CreateDBClusterParameterGroupResultTypeDef,
     DBClusterParameterGroupsMessageTypeDef,
     CopyDBClusterSnapshotResultTypeDef,
     CreateDBClusterSnapshotResultTypeDef,
     DBClusterSnapshotMessageTypeDef,
     DeleteDBClusterSnapshotResultTypeDef,
@@ -538,88 +541,86 @@
     DBParameterGroupDetailsTypeDef,
     EngineDefaultsTypeDef,
     ModifyDBClusterParameterGroupMessageRequestTypeDef,
     ModifyDBParameterGroupMessageRequestTypeDef,
     ResetDBClusterParameterGroupMessageRequestTypeDef,
     ResetDBParameterGroupMessageRequestTypeDef,
     DBClusterSnapshotAttributesResultTypeDef,
-    DBClusterTypeDef,
     DBEngineVersionTypeDef,
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
+    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
     DescribeDBInstancesMessageRequestTypeDef,
+    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
     DescribeDBParameterGroupsMessageRequestTypeDef,
+    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
     DescribeDBParametersMessageRequestTypeDef,
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
-    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
-    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef,
     EventCategoriesMessageTypeDef,
     EventsMessageTypeDef,
     GlobalClusterTypeDef,
-    PendingModifiedValuesTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
     ValidStorageOptionsTypeDef,
     OrderableDBInstanceOptionsMessageTypeDef,
     DBSubnetGroupTypeDef,
+    DBClusterTypeDef,
     DescribeEngineDefaultClusterParametersResultTypeDef,
     DescribeEngineDefaultParametersResultTypeDef,
     DescribeDBClusterSnapshotAttributesResultTypeDef,
     ModifyDBClusterSnapshotAttributeResultTypeDef,
-    CreateDBClusterResultTypeDef,
-    DBClusterMessageTypeDef,
-    DeleteDBClusterResultTypeDef,
-    FailoverDBClusterResultTypeDef,
-    ModifyDBClusterResultTypeDef,
-    PromoteReadReplicaDBClusterResultTypeDef,
-    RestoreDBClusterFromSnapshotResultTypeDef,
-    RestoreDBClusterToPointInTimeResultTypeDef,
-    StartDBClusterResultTypeDef,
-    StopDBClusterResultTypeDef,
     DBEngineVersionMessageTypeDef,
     CreateGlobalClusterResultTypeDef,
     DeleteGlobalClusterResultTypeDef,
     FailoverGlobalClusterResultTypeDef,
     GlobalClustersMessageTypeDef,
     ModifyGlobalClusterResultTypeDef,
     RemoveFromGlobalClusterResultTypeDef,
     ApplyPendingMaintenanceActionResultTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
     ValidDBInstanceModificationsMessageTypeDef,
     CreateDBSubnetGroupResultTypeDef,
     DBInstanceTypeDef,
     DBSubnetGroupMessageTypeDef,
     ModifyDBSubnetGroupResultTypeDef,
+    CreateDBClusterResultTypeDef,
+    DBClusterMessageTypeDef,
+    DeleteDBClusterResultTypeDef,
+    FailoverDBClusterResultTypeDef,
+    ModifyDBClusterResultTypeDef,
+    PromoteReadReplicaDBClusterResultTypeDef,
+    RestoreDBClusterFromSnapshotResultTypeDef,
+    RestoreDBClusterToPointInTimeResultTypeDef,
+    StartDBClusterResultTypeDef,
+    StopDBClusterResultTypeDef,
     DescribeValidDBInstanceModificationsResultTypeDef,
     CreateDBInstanceResultTypeDef,
     DBInstanceMessageTypeDef,
     DeleteDBInstanceResultTypeDef,
     ModifyDBInstanceResultTypeDef,
     RebootDBInstanceResultTypeDef,
 )
@@ -632,43 +633,43 @@
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/README.md` & `types-aiobotocore-neptune-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-neptune"></a>
 
 # types-aiobotocore-neptune
 
 [![PyPI - types-aiobotocore-neptune](https://img.shields.io/pypi/v/types-aiobotocore-neptune.svg?color=blue)](https://pypi.org/project/types-aiobotocore-neptune)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-neptune.svg?color=blue)](https://pypi.org/project/types-aiobotocore-neptune)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-neptune?color=blue)](https://pypistats.org/packages/types-aiobotocore-neptune)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Neptune 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
+[aiobotocore.Neptune 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
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
 [types-aiobotocore-neptune docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,88 +391,89 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_neptune.type_defs import (
     AddRoleToDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     CharacterSetTypeDef,
     CloudwatchLogsExportConfigurationTypeDef,
+    PendingCloudwatchLogsExportsTypeDef,
     DBClusterParameterGroupTypeDef,
     DBClusterSnapshotTypeDef,
     DBParameterGroupTypeDef,
+    CreateDBClusterEndpointOutputTypeDef,
     ServerlessV2ScalingConfigurationTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     DBClusterEndpointTypeDef,
     DBClusterMemberTypeDef,
     DBClusterOptionGroupStatusTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     ServerlessV2ScalingConfigurationInfoTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     TimezoneTypeDef,
     UpgradeTargetTypeDef,
     DBInstanceStatusInfoTypeDef,
     DBParameterGroupStatusTypeDef,
     DBSecurityGroupMembershipTypeDef,
     DomainMembershipTypeDef,
     EndpointTypeDef,
     OptionGroupMembershipTypeDef,
+    DBParameterGroupNameMessageTypeDef,
     DeleteDBClusterEndpointMessageRequestTypeDef,
+    DeleteDBClusterEndpointOutputTypeDef,
     DeleteDBClusterMessageRequestTypeDef,
     DeleteDBClusterParameterGroupMessageRequestTypeDef,
     DeleteDBClusterSnapshotMessageRequestTypeDef,
     DeleteDBInstanceMessageRequestTypeDef,
     DeleteDBParameterGroupMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
     DescribeValidDBInstanceModificationsMessageRequestTypeDef,
     DoubleRangeTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     FailoverGlobalClusterMessageRequestTypeDef,
     GlobalClusterMemberTypeDef,
     ModifyDBClusterEndpointMessageRequestTypeDef,
+    ModifyDBClusterEndpointOutputTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
-    PendingCloudwatchLogsExportsTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PromoteReadReplicaDBClusterMessageRequestTypeDef,
     RangeTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveRoleFromDBClusterMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StopDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
-    CreateDBClusterEndpointOutputTypeDef,
     CreateEventSubscriptionResultTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
-    DBParameterGroupNameMessageTypeDef,
-    DeleteDBClusterEndpointOutputTypeDef,
     DeleteEventSubscriptionResultTypeDef,
-    EmptyResponseMetadataTypeDef,
     EventSubscriptionsMessageTypeDef,
-    ModifyDBClusterEndpointOutputTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopyDBClusterParameterGroupMessageRequestTypeDef,
     CopyDBClusterSnapshotMessageRequestTypeDef,
     CopyDBParameterGroupMessageRequestTypeDef,
     CreateDBClusterEndpointMessageRequestTypeDef,
@@ -482,14 +483,16 @@
     CreateDBParameterGroupMessageRequestTypeDef,
     CreateDBSubnetGroupMessageRequestTypeDef,
     CreateEventSubscriptionMessageRequestTypeDef,
     TagListMessageTypeDef,
     OrderableDBInstanceOptionTypeDef,
     SubnetTypeDef,
     ModifyDBInstanceMessageRequestTypeDef,
+    ClusterPendingModifiedValuesTypeDef,
+    PendingModifiedValuesTypeDef,
     CopyDBClusterParameterGroupResultTypeDef,
     CreateDBClusterParameterGroupResultTypeDef,
     DBClusterParameterGroupsMessageTypeDef,
     CopyDBClusterSnapshotResultTypeDef,
     CreateDBClusterSnapshotResultTypeDef,
     DBClusterSnapshotMessageTypeDef,
     DeleteDBClusterSnapshotResultTypeDef,
@@ -505,88 +508,86 @@
     DBParameterGroupDetailsTypeDef,
     EngineDefaultsTypeDef,
     ModifyDBClusterParameterGroupMessageRequestTypeDef,
     ModifyDBParameterGroupMessageRequestTypeDef,
     ResetDBClusterParameterGroupMessageRequestTypeDef,
     ResetDBParameterGroupMessageRequestTypeDef,
     DBClusterSnapshotAttributesResultTypeDef,
-    DBClusterTypeDef,
     DBEngineVersionTypeDef,
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
+    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
     DescribeDBInstancesMessageRequestTypeDef,
+    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
     DescribeDBParameterGroupsMessageRequestTypeDef,
+    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
     DescribeDBParametersMessageRequestTypeDef,
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
-    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
-    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef,
     EventCategoriesMessageTypeDef,
     EventsMessageTypeDef,
     GlobalClusterTypeDef,
-    PendingModifiedValuesTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
     ValidStorageOptionsTypeDef,
     OrderableDBInstanceOptionsMessageTypeDef,
     DBSubnetGroupTypeDef,
+    DBClusterTypeDef,
     DescribeEngineDefaultClusterParametersResultTypeDef,
     DescribeEngineDefaultParametersResultTypeDef,
     DescribeDBClusterSnapshotAttributesResultTypeDef,
     ModifyDBClusterSnapshotAttributeResultTypeDef,
-    CreateDBClusterResultTypeDef,
-    DBClusterMessageTypeDef,
-    DeleteDBClusterResultTypeDef,
-    FailoverDBClusterResultTypeDef,
-    ModifyDBClusterResultTypeDef,
-    PromoteReadReplicaDBClusterResultTypeDef,
-    RestoreDBClusterFromSnapshotResultTypeDef,
-    RestoreDBClusterToPointInTimeResultTypeDef,
-    StartDBClusterResultTypeDef,
-    StopDBClusterResultTypeDef,
     DBEngineVersionMessageTypeDef,
     CreateGlobalClusterResultTypeDef,
     DeleteGlobalClusterResultTypeDef,
     FailoverGlobalClusterResultTypeDef,
     GlobalClustersMessageTypeDef,
     ModifyGlobalClusterResultTypeDef,
     RemoveFromGlobalClusterResultTypeDef,
     ApplyPendingMaintenanceActionResultTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
     ValidDBInstanceModificationsMessageTypeDef,
     CreateDBSubnetGroupResultTypeDef,
     DBInstanceTypeDef,
     DBSubnetGroupMessageTypeDef,
     ModifyDBSubnetGroupResultTypeDef,
+    CreateDBClusterResultTypeDef,
+    DBClusterMessageTypeDef,
+    DeleteDBClusterResultTypeDef,
+    FailoverDBClusterResultTypeDef,
+    ModifyDBClusterResultTypeDef,
+    PromoteReadReplicaDBClusterResultTypeDef,
+    RestoreDBClusterFromSnapshotResultTypeDef,
+    RestoreDBClusterToPointInTimeResultTypeDef,
+    StartDBClusterResultTypeDef,
+    StopDBClusterResultTypeDef,
     DescribeValidDBInstanceModificationsResultTypeDef,
     CreateDBInstanceResultTypeDef,
     DBInstanceMessageTypeDef,
     DeleteDBInstanceResultTypeDef,
     ModifyDBInstanceResultTypeDef,
     RebootDBInstanceResultTypeDef,
 )
@@ -599,43 +600,43 @@
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/setup.py` & `types-aiobotocore-neptune-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-neptune.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-neptune",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_neptune"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Neptune 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Neptune 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/"
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/__init__.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/__init__.pyi` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/__main__.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Neptune 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Neptune 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune\nOther"
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/client.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -409,14 +409,15 @@
 
     async def create_db_instance(
         self,
         *,
         DBInstanceIdentifier: str,
         DBInstanceClass: str,
         Engine: str,
+        DBClusterIdentifier: str,
         DBName: str = ...,
         AllocatedStorage: int = ...,
         MasterUsername: str = ...,
         MasterUserPassword: str = ...,
         DBSecurityGroups: Sequence[str] = ...,
         VpcSecurityGroupIds: Sequence[str] = ...,
         AvailabilityZone: str = ...,
@@ -431,15 +432,14 @@
         AutoMinorVersionUpgrade: bool = ...,
         LicenseModel: str = ...,
         Iops: int = ...,
         OptionGroupName: str = ...,
         CharacterSetName: str = ...,
         PubliclyAccessible: bool = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        DBClusterIdentifier: str = ...,
         StorageType: str = ...,
         TdeCredentialArn: str = ...,
         TdeCredentialPassword: str = ...,
         StorageEncrypted: bool = ...,
         KmsKeyId: str = ...,
         Domain: str = ...,
         CopyTagsToSnapshot: bool = ...,
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/client.pyi` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -391,14 +391,15 @@
         """
     async def create_db_instance(
         self,
         *,
         DBInstanceIdentifier: str,
         DBInstanceClass: str,
         Engine: str,
+        DBClusterIdentifier: str,
         DBName: str = ...,
         AllocatedStorage: int = ...,
         MasterUsername: str = ...,
         MasterUserPassword: str = ...,
         DBSecurityGroups: Sequence[str] = ...,
         VpcSecurityGroupIds: Sequence[str] = ...,
         AvailabilityZone: str = ...,
@@ -413,15 +414,14 @@
         AutoMinorVersionUpgrade: bool = ...,
         LicenseModel: str = ...,
         Iops: int = ...,
         OptionGroupName: str = ...,
         CharacterSetName: str = ...,
         PubliclyAccessible: bool = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        DBClusterIdentifier: str = ...,
         StorageType: str = ...,
         TdeCredentialArn: str = ...,
         TdeCredentialPassword: str = ...,
         StorageEncrypted: bool = ...,
         KmsKeyId: str = ...,
         Domain: str = ...,
         CopyTagsToSnapshot: bool = ...,
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/literals.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -135,14 +135,15 @@
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
@@ -221,14 +222,15 @@
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
@@ -239,14 +241,15 @@
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
@@ -282,14 +285,15 @@
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
@@ -308,16 +312,19 @@
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
@@ -401,15 +408,17 @@
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/literals.pyi` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -133,14 +133,15 @@
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
@@ -219,14 +220,15 @@
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
@@ -237,14 +239,15 @@
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
@@ -280,14 +283,15 @@
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
@@ -306,16 +310,19 @@
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
@@ -399,15 +406,17 @@
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/paginator.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,17 +46,16 @@
         describe_event_subscriptions_paginator: DescribeEventSubscriptionsPaginator = client.get_paginator("describe_event_subscriptions")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_global_clusters_paginator: DescribeGlobalClustersPaginator = client.get_paginator("describe_global_clusters")
         describe_orderable_db_instance_options_paginator: DescribeOrderableDBInstanceOptionsPaginator = client.get_paginator("describe_orderable_db_instance_options")
         describe_pending_maintenance_actions_paginator: DescribePendingMaintenanceActionsPaginator = client.get_paginator("describe_pending_maintenance_actions")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SourceTypeType
 from .type_defs import (
     DBClusterEndpointMessageTypeDef,
@@ -75,20 +74,14 @@
     FilterTypeDef,
     GlobalClustersMessageTypeDef,
     OrderableDBInstanceOptionsMessageTypeDef,
     PaginatorConfigTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeDBClusterEndpointsPaginator",
     "DescribeDBClusterParameterGroupsPaginator",
     "DescribeDBClusterParametersPaginator",
     "DescribeDBClusterSnapshotsPaginator",
     "DescribeDBClustersPaginator",
     "DescribeDBEngineVersionsPaginator",
@@ -123,15 +116,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterendpointspaginator)
         """
 
 
@@ -142,15 +135,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterparametergroupspaginator)
         """
 
 
@@ -162,15 +155,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterparameterspaginator)
         """
 
 
@@ -185,15 +178,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclustersnapshotspaginator)
         """
 
 
@@ -204,15 +197,15 @@
     """
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterspaginator)
         """
 
 
@@ -228,15 +221,15 @@
         Engine: str = ...,
         EngineVersion: str = ...,
         DBParameterGroupFamily: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         DefaultOnly: bool = ...,
         ListSupportedCharacterSets: bool = ...,
         ListSupportedTimezones: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBEngineVersionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbengineversionspaginator)
         """
 
 
@@ -247,15 +240,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbinstancespaginator)
         """
 
 
@@ -266,15 +259,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbparametergroupspaginator)
         """
 
 
@@ -286,15 +279,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbparameterspaginator)
         """
 
 
@@ -305,15 +298,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbsubnetgroupspaginator)
         """
 
 
@@ -324,15 +317,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeEngineDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeenginedefaultparameterspaginator)
         """
 
 
@@ -343,15 +336,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeeventsubscriptionspaginator)
         """
 
 
@@ -367,30 +360,33 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeeventspaginator)
         """
 
 
 class DescribeGlobalClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeGlobalClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeglobalclusterspaginator)
     """
 
     def paginate(
-        self, *, GlobalClusterIdentifier: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        GlobalClusterIdentifier: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GlobalClustersMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeGlobalClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeglobalclusterspaginator)
         """
 
 
@@ -405,15 +401,15 @@
         *,
         Engine: str,
         EngineVersion: str = ...,
         DBInstanceClass: str = ...,
         LicenseModel: str = ...,
         Vpc: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OrderableDBInstanceOptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeOrderableDBInstanceOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeorderabledbinstanceoptionspaginator)
         """
 
 
@@ -424,13 +420,13 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribePendingMaintenanceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describependingmaintenanceactionspaginator)
         """
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/paginator.pyi` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -46,17 +46,16 @@
         describe_event_subscriptions_paginator: DescribeEventSubscriptionsPaginator = client.get_paginator("describe_event_subscriptions")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_global_clusters_paginator: DescribeGlobalClustersPaginator = client.get_paginator("describe_global_clusters")
         describe_orderable_db_instance_options_paginator: DescribeOrderableDBInstanceOptionsPaginator = client.get_paginator("describe_orderable_db_instance_options")
         describe_pending_maintenance_actions_paginator: DescribePendingMaintenanceActionsPaginator = client.get_paginator("describe_pending_maintenance_actions")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SourceTypeType
 from .type_defs import (
     DBClusterEndpointMessageTypeDef,
@@ -75,19 +74,14 @@
     FilterTypeDef,
     GlobalClustersMessageTypeDef,
     OrderableDBInstanceOptionsMessageTypeDef,
     PaginatorConfigTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeDBClusterEndpointsPaginator",
     "DescribeDBClusterParameterGroupsPaginator",
     "DescribeDBClusterParametersPaginator",
     "DescribeDBClusterSnapshotsPaginator",
     "DescribeDBClustersPaginator",
     "DescribeDBEngineVersionsPaginator",
@@ -119,15 +113,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterendpointspaginator)
         """
 
 class DescribeDBClusterParameterGroupsPaginator(AioPaginator):
@@ -137,15 +131,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterparametergroupspaginator)
         """
 
 class DescribeDBClusterParametersPaginator(AioPaginator):
@@ -156,15 +150,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterparameterspaginator)
         """
 
 class DescribeDBClusterSnapshotsPaginator(AioPaginator):
@@ -178,15 +172,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclustersnapshotspaginator)
         """
 
 class DescribeDBClustersPaginator(AioPaginator):
@@ -196,15 +190,15 @@
     """
 
     def paginate(
         self,
         *,
         DBClusterIdentifier: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBClusterMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbclusterspaginator)
         """
 
 class DescribeDBEngineVersionsPaginator(AioPaginator):
@@ -219,15 +213,15 @@
         Engine: str = ...,
         EngineVersion: str = ...,
         DBParameterGroupFamily: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         DefaultOnly: bool = ...,
         ListSupportedCharacterSets: bool = ...,
         ListSupportedTimezones: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DBEngineVersionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbengineversionspaginator)
         """
 
 class DescribeDBInstancesPaginator(AioPaginator):
@@ -237,15 +231,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbinstancespaginator)
         """
 
 class DescribeDBParameterGroupsPaginator(AioPaginator):
@@ -255,15 +249,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbparametergroupspaginator)
         """
 
 class DescribeDBParametersPaginator(AioPaginator):
@@ -274,15 +268,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbparameterspaginator)
         """
 
 class DescribeDBSubnetGroupsPaginator(AioPaginator):
@@ -292,15 +286,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeDBSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describedbsubnetgroupspaginator)
         """
 
 class DescribeEngineDefaultParametersPaginator(AioPaginator):
@@ -310,15 +304,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeEngineDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeenginedefaultparameterspaginator)
         """
 
 class DescribeEventSubscriptionsPaginator(AioPaginator):
@@ -328,15 +322,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeeventsubscriptionspaginator)
         """
 
 class DescribeEventsPaginator(AioPaginator):
@@ -351,29 +345,32 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeeventspaginator)
         """
 
 class DescribeGlobalClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeGlobalClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeglobalclusterspaginator)
     """
 
     def paginate(
-        self, *, GlobalClusterIdentifier: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        GlobalClusterIdentifier: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GlobalClustersMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeGlobalClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeglobalclusterspaginator)
         """
 
 class DescribeOrderableDBInstanceOptionsPaginator(AioPaginator):
@@ -387,15 +384,15 @@
         *,
         Engine: str,
         EngineVersion: str = ...,
         DBInstanceClass: str = ...,
         LicenseModel: str = ...,
         Vpc: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[OrderableDBInstanceOptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribeOrderableDBInstanceOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describeorderabledbinstanceoptionspaginator)
         """
 
 class DescribePendingMaintenanceActionsPaginator(AioPaginator):
@@ -405,13 +402,13 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune.Paginator.DescribePendingMaintenanceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/paginators/#describependingmaintenanceactionspaginator)
         """
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/type_defs.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -23,88 +23,89 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddRoleToDBClusterMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionMessageRequestTypeDef",
     "EventSubscriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
     "AvailabilityZoneTypeDef",
     "CharacterSetTypeDef",
     "CloudwatchLogsExportConfigurationTypeDef",
+    "PendingCloudwatchLogsExportsTypeDef",
     "DBClusterParameterGroupTypeDef",
     "DBClusterSnapshotTypeDef",
     "DBParameterGroupTypeDef",
+    "CreateDBClusterEndpointOutputTypeDef",
     "ServerlessV2ScalingConfigurationTypeDef",
     "CreateGlobalClusterMessageRequestTypeDef",
     "DBClusterEndpointTypeDef",
     "DBClusterMemberTypeDef",
     "DBClusterOptionGroupStatusTypeDef",
     "ParameterTypeDef",
+    "DBClusterParameterGroupNameMessageTypeDef",
     "DBClusterRoleTypeDef",
     "DBClusterSnapshotAttributeTypeDef",
     "ServerlessV2ScalingConfigurationInfoTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "TimezoneTypeDef",
     "UpgradeTargetTypeDef",
     "DBInstanceStatusInfoTypeDef",
     "DBParameterGroupStatusTypeDef",
     "DBSecurityGroupMembershipTypeDef",
     "DomainMembershipTypeDef",
     "EndpointTypeDef",
     "OptionGroupMembershipTypeDef",
+    "DBParameterGroupNameMessageTypeDef",
     "DeleteDBClusterEndpointMessageRequestTypeDef",
+    "DeleteDBClusterEndpointOutputTypeDef",
     "DeleteDBClusterMessageRequestTypeDef",
     "DeleteDBClusterParameterGroupMessageRequestTypeDef",
     "DeleteDBClusterSnapshotMessageRequestTypeDef",
     "DeleteDBInstanceMessageRequestTypeDef",
     "DeleteDBParameterGroupMessageRequestTypeDef",
     "DeleteDBSubnetGroupMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteGlobalClusterMessageRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     "DescribeGlobalClustersMessageRequestTypeDef",
     "DescribeValidDBInstanceModificationsMessageRequestTypeDef",
     "DoubleRangeTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventCategoriesMapTypeDef",
     "EventTypeDef",
     "FailoverDBClusterMessageRequestTypeDef",
     "FailoverGlobalClusterMessageRequestTypeDef",
     "GlobalClusterMemberTypeDef",
     "ModifyDBClusterEndpointMessageRequestTypeDef",
+    "ModifyDBClusterEndpointOutputTypeDef",
     "ModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBSubnetGroupMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyGlobalClusterMessageRequestTypeDef",
-    "PendingCloudwatchLogsExportsTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
     "PromoteReadReplicaDBClusterMessageRequestTypeDef",
     "RangeTypeDef",
     "RebootDBInstanceMessageRequestTypeDef",
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     "RemoveRoleFromDBClusterMessageRequestTypeDef",
     "RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDBClusterMessageRequestTypeDef",
     "StopDBClusterMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionResultTypeDef",
-    "CreateDBClusterEndpointOutputTypeDef",
     "CreateEventSubscriptionResultTypeDef",
-    "DBClusterParameterGroupNameMessageTypeDef",
-    "DBParameterGroupNameMessageTypeDef",
-    "DeleteDBClusterEndpointOutputTypeDef",
     "DeleteEventSubscriptionResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EventSubscriptionsMessageTypeDef",
-    "ModifyDBClusterEndpointOutputTypeDef",
     "ModifyEventSubscriptionResultTypeDef",
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CopyDBClusterParameterGroupMessageRequestTypeDef",
     "CopyDBClusterSnapshotMessageRequestTypeDef",
     "CopyDBParameterGroupMessageRequestTypeDef",
     "CreateDBClusterEndpointMessageRequestTypeDef",
@@ -114,14 +115,16 @@
     "CreateDBParameterGroupMessageRequestTypeDef",
     "CreateDBSubnetGroupMessageRequestTypeDef",
     "CreateEventSubscriptionMessageRequestTypeDef",
     "TagListMessageTypeDef",
     "OrderableDBInstanceOptionTypeDef",
     "SubnetTypeDef",
     "ModifyDBInstanceMessageRequestTypeDef",
+    "ClusterPendingModifiedValuesTypeDef",
+    "PendingModifiedValuesTypeDef",
     "CopyDBClusterParameterGroupResultTypeDef",
     "CreateDBClusterParameterGroupResultTypeDef",
     "DBClusterParameterGroupsMessageTypeDef",
     "CopyDBClusterSnapshotResultTypeDef",
     "CreateDBClusterSnapshotResultTypeDef",
     "DBClusterSnapshotMessageTypeDef",
     "DeleteDBClusterSnapshotResultTypeDef",
@@ -137,88 +140,86 @@
     "DBParameterGroupDetailsTypeDef",
     "EngineDefaultsTypeDef",
     "ModifyDBClusterParameterGroupMessageRequestTypeDef",
     "ModifyDBParameterGroupMessageRequestTypeDef",
     "ResetDBClusterParameterGroupMessageRequestTypeDef",
     "ResetDBParameterGroupMessageRequestTypeDef",
     "DBClusterSnapshotAttributesResultTypeDef",
-    "DBClusterTypeDef",
     "DBEngineVersionTypeDef",
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
+    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
     "DescribeDBInstancesMessageRequestTypeDef",
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
     "DescribeDBParameterGroupsMessageRequestTypeDef",
+    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
     "DescribeDBParametersMessageRequestTypeDef",
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
     "DescribeEngineDefaultClusterParametersMessageRequestTypeDef",
+    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     "DescribeEngineDefaultParametersMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     "DescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
-    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
-    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
-    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
-    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef",
     "DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef",
     "EventCategoriesMessageTypeDef",
     "EventsMessageTypeDef",
     "GlobalClusterTypeDef",
-    "PendingModifiedValuesTypeDef",
     "ResourcePendingMaintenanceActionsTypeDef",
     "ValidStorageOptionsTypeDef",
     "OrderableDBInstanceOptionsMessageTypeDef",
     "DBSubnetGroupTypeDef",
+    "DBClusterTypeDef",
     "DescribeEngineDefaultClusterParametersResultTypeDef",
     "DescribeEngineDefaultParametersResultTypeDef",
     "DescribeDBClusterSnapshotAttributesResultTypeDef",
     "ModifyDBClusterSnapshotAttributeResultTypeDef",
-    "CreateDBClusterResultTypeDef",
-    "DBClusterMessageTypeDef",
-    "DeleteDBClusterResultTypeDef",
-    "FailoverDBClusterResultTypeDef",
-    "ModifyDBClusterResultTypeDef",
-    "PromoteReadReplicaDBClusterResultTypeDef",
-    "RestoreDBClusterFromSnapshotResultTypeDef",
-    "RestoreDBClusterToPointInTimeResultTypeDef",
-    "StartDBClusterResultTypeDef",
-    "StopDBClusterResultTypeDef",
     "DBEngineVersionMessageTypeDef",
     "CreateGlobalClusterResultTypeDef",
     "DeleteGlobalClusterResultTypeDef",
     "FailoverGlobalClusterResultTypeDef",
     "GlobalClustersMessageTypeDef",
     "ModifyGlobalClusterResultTypeDef",
     "RemoveFromGlobalClusterResultTypeDef",
     "ApplyPendingMaintenanceActionResultTypeDef",
     "PendingMaintenanceActionsMessageTypeDef",
     "ValidDBInstanceModificationsMessageTypeDef",
     "CreateDBSubnetGroupResultTypeDef",
     "DBInstanceTypeDef",
     "DBSubnetGroupMessageTypeDef",
     "ModifyDBSubnetGroupResultTypeDef",
+    "CreateDBClusterResultTypeDef",
+    "DBClusterMessageTypeDef",
+    "DeleteDBClusterResultTypeDef",
+    "FailoverDBClusterResultTypeDef",
+    "ModifyDBClusterResultTypeDef",
+    "PromoteReadReplicaDBClusterResultTypeDef",
+    "RestoreDBClusterFromSnapshotResultTypeDef",
+    "RestoreDBClusterToPointInTimeResultTypeDef",
+    "StartDBClusterResultTypeDef",
+    "StopDBClusterResultTypeDef",
     "DescribeValidDBInstanceModificationsResultTypeDef",
     "CreateDBInstanceResultTypeDef",
     "DBInstanceMessageTypeDef",
     "DeleteDBInstanceResultTypeDef",
     "ModifyDBInstanceResultTypeDef",
     "RebootDBInstanceResultTypeDef",
 )
@@ -267,25 +268,14 @@
         "EventCategoriesList": List[str],
         "Enabled": bool,
         "EventSubscriptionArn": str,
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
@@ -322,14 +312,23 @@
     {
         "EnableLogTypes": Sequence[str],
         "DisableLogTypes": Sequence[str],
     },
     total=False,
 )
 
+PendingCloudwatchLogsExportsTypeDef = TypedDict(
+    "PendingCloudwatchLogsExportsTypeDef",
+    {
+        "LogTypesToEnable": List[str],
+        "LogTypesToDisable": List[str],
+    },
+    total=False,
+)
+
 DBClusterParameterGroupTypeDef = TypedDict(
     "DBClusterParameterGroupTypeDef",
     {
         "DBClusterParameterGroupName": str,
         "DBParameterGroupFamily": str,
         "Description": str,
         "DBClusterParameterGroupArn": str,
@@ -371,14 +370,31 @@
         "DBParameterGroupFamily": str,
         "Description": str,
         "DBParameterGroupArn": str,
     },
     total=False,
 )
 
+CreateDBClusterEndpointOutputTypeDef = TypedDict(
+    "CreateDBClusterEndpointOutputTypeDef",
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
 ServerlessV2ScalingConfigurationTypeDef = TypedDict(
     "ServerlessV2ScalingConfigurationTypeDef",
     {
         "MinCapacity": float,
         "MaxCapacity": float,
     },
     total=False,
@@ -460,14 +476,22 @@
         "IsModifiable": bool,
         "MinimumEngineVersion": str,
         "ApplyMethod": ApplyMethodType,
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
@@ -577,21 +601,46 @@
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
 DeleteDBClusterEndpointMessageRequestTypeDef = TypedDict(
     "DeleteDBClusterEndpointMessageRequestTypeDef",
     {
         "DBClusterEndpointIdentifier": str,
     },
 )
 
+DeleteDBClusterEndpointOutputTypeDef = TypedDict(
+    "DeleteDBClusterEndpointOutputTypeDef",
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
 _RequiredDeleteDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredDeleteDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 _OptionalDeleteDBClusterMessageRequestTypeDef = TypedDict(
@@ -678,24 +727,14 @@
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
 
@@ -704,14 +743,23 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
+    {
+        "GlobalClusterIdentifier": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGlobalClustersMessageRequestTypeDef = TypedDict(
     "DescribeGlobalClustersMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "MaxRecords": int,
         "Marker": str,
     },
@@ -730,14 +778,21 @@
     {
         "From": float,
         "To": float,
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
 EventCategoriesMapTypeDef = TypedDict(
     "EventCategoriesMapTypeDef",
     {
         "SourceType": str,
         "EventCategories": List[str],
     },
     total=False,
@@ -803,14 +858,31 @@
 class ModifyDBClusterEndpointMessageRequestTypeDef(
     _RequiredModifyDBClusterEndpointMessageRequestTypeDef,
     _OptionalModifyDBClusterEndpointMessageRequestTypeDef,
 ):
     pass
 
 
+ModifyDBClusterEndpointOutputTypeDef = TypedDict(
+    "ModifyDBClusterEndpointOutputTypeDef",
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
 _RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "AttributeName": str,
     },
 )
@@ -900,19 +972,20 @@
 class ModifyGlobalClusterMessageRequestTypeDef(
     _RequiredModifyGlobalClusterMessageRequestTypeDef,
     _OptionalModifyGlobalClusterMessageRequestTypeDef,
 ):
     pass
 
 
-PendingCloudwatchLogsExportsTypeDef = TypedDict(
-    "PendingCloudwatchLogsExportsTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "LogTypesToEnable": List[str],
-        "LogTypesToDisable": List[str],
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
     total=False,
 )
 
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
@@ -1007,14 +1080,25 @@
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
 StartDBClusterMessageRequestTypeDef = TypedDict(
     "StartDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 
@@ -1025,130 +1109,56 @@
     },
 )
 
 AddSourceIdentifierToSubscriptionResultTypeDef = TypedDict(
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDBClusterEndpointOutputTypeDef = TypedDict(
-    "CreateDBClusterEndpointOutputTypeDef",
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEventSubscriptionResultTypeDef = TypedDict(
     "CreateEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
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
-DeleteDBClusterEndpointOutputTypeDef = TypedDict(
-    "DeleteDBClusterEndpointOutputTypeDef",
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventSubscriptionResultTypeDef = TypedDict(
     "DeleteEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
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
-    },
-)
-
-ModifyDBClusterEndpointOutputTypeDef = TypedDict(
-    "ModifyDBClusterEndpointOutputTypeDef",
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
@@ -1306,14 +1316,15 @@
 
 _RequiredCreateDBInstanceMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "Engine": str,
+        "DBClusterIdentifier": str,
     },
 )
 _OptionalCreateDBInstanceMessageRequestTypeDef = TypedDict(
     "_OptionalCreateDBInstanceMessageRequestTypeDef",
     {
         "DBName": str,
         "AllocatedStorage": int,
@@ -1333,15 +1344,14 @@
         "AutoMinorVersionUpgrade": bool,
         "LicenseModel": str,
         "Iops": int,
         "OptionGroupName": str,
         "CharacterSetName": str,
         "PubliclyAccessible": bool,
         "Tags": Sequence[TagTypeDef],
-        "DBClusterIdentifier": str,
         "StorageType": str,
         "TdeCredentialArn": str,
         "TdeCredentialPassword": str,
         "StorageEncrypted": bool,
         "KmsKeyId": str,
         "Domain": str,
         "CopyTagsToSnapshot": bool,
@@ -1441,15 +1451,15 @@
     pass
 
 
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
@@ -1539,94 +1549,129 @@
 
 class ModifyDBInstanceMessageRequestTypeDef(
     _RequiredModifyDBInstanceMessageRequestTypeDef, _OptionalModifyDBInstanceMessageRequestTypeDef
 ):
     pass
 
 
+ClusterPendingModifiedValuesTypeDef = TypedDict(
+    "ClusterPendingModifiedValuesTypeDef",
+    {
+        "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
+        "DBClusterIdentifier": str,
+        "IAMDatabaseAuthenticationEnabled": bool,
+        "EngineVersion": str,
+        "BackupRetentionPeriod": int,
+        "AllocatedStorage": int,
+        "Iops": int,
+    },
+    total=False,
+)
+
+PendingModifiedValuesTypeDef = TypedDict(
+    "PendingModifiedValuesTypeDef",
+    {
+        "DBInstanceClass": str,
+        "AllocatedStorage": int,
+        "MasterUserPassword": str,
+        "Port": int,
+        "BackupRetentionPeriod": int,
+        "MultiAZ": bool,
+        "EngineVersion": str,
+        "LicenseModel": str,
+        "Iops": int,
+        "DBInstanceIdentifier": str,
+        "StorageType": str,
+        "CACertificateIdentifier": str,
+        "DBSubnetGroupName": str,
+        "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
+    },
+    total=False,
+)
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
@@ -1786,33 +1831,33 @@
 
 
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
@@ -1889,62 +1934,14 @@
     {
         "DBClusterSnapshotIdentifier": str,
         "DBClusterSnapshotAttributes": List[DBClusterSnapshotAttributeTypeDef],
     },
     total=False,
 )
 
-DBClusterTypeDef = TypedDict(
-    "DBClusterTypeDef",
-    {
-        "AllocatedStorage": int,
-        "AvailabilityZones": List[str],
-        "BackupRetentionPeriod": int,
-        "CharacterSetName": str,
-        "DatabaseName": str,
-        "DBClusterIdentifier": str,
-        "DBClusterParameterGroup": str,
-        "DBSubnetGroup": str,
-        "Status": str,
-        "PercentProgress": str,
-        "EarliestRestorableTime": datetime,
-        "Endpoint": str,
-        "ReaderEndpoint": str,
-        "MultiAZ": bool,
-        "Engine": str,
-        "EngineVersion": str,
-        "LatestRestorableTime": datetime,
-        "Port": int,
-        "MasterUsername": str,
-        "DBClusterOptionGroupMemberships": List[DBClusterOptionGroupStatusTypeDef],
-        "PreferredBackupWindow": str,
-        "PreferredMaintenanceWindow": str,
-        "ReplicationSourceIdentifier": str,
-        "ReadReplicaIdentifiers": List[str],
-        "DBClusterMembers": List[DBClusterMemberTypeDef],
-        "VpcSecurityGroups": List[VpcSecurityGroupMembershipTypeDef],
-        "HostedZoneId": str,
-        "StorageEncrypted": bool,
-        "KmsKeyId": str,
-        "DbClusterResourceId": str,
-        "DBClusterArn": str,
-        "AssociatedRoles": List[DBClusterRoleTypeDef],
-        "IAMDatabaseAuthenticationEnabled": bool,
-        "CloneGroupId": str,
-        "ClusterCreateTime": datetime,
-        "CopyTagsToSnapshot": bool,
-        "EnabledCloudwatchLogsExports": List[str],
-        "DeletionProtection": bool,
-        "CrossAccountClone": bool,
-        "AutomaticRestartTime": datetime,
-        "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationInfoTypeDef,
-    },
-    total=False,
-)
-
 DBEngineVersionTypeDef = TypedDict(
     "DBEngineVersionTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "DBParameterGroupFamily": str,
         "DBEngineDescription": str,
@@ -1957,37 +1954,82 @@
         "SupportsLogExportsToCloudwatchLogs": bool,
         "SupportsReadReplica": bool,
         "SupportsGlobalDatabases": bool,
     },
     total=False,
 )
 
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
@@ -2005,14 +2047,28 @@
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
+
 DescribeDBClusterSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterSnapshotsMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
@@ -2020,25 +2076,50 @@
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
@@ -2047,36 +2128,80 @@
         "DefaultOnly": bool,
         "ListSupportedCharacterSets": bool,
         "ListSupportedTimezones": bool,
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
 
+DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
+    {
+        "DBParameterGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
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
+
+class DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef(
+    _RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
+    _OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeDBParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeDBParametersMessageRequestTypeDef",
     {
         "DBParameterGroupName": str,
     },
 )
 _OptionalDescribeDBParametersMessageRequestTypeDef = TypedDict(
@@ -2094,14 +2219,24 @@
 class DescribeDBParametersMessageRequestTypeDef(
     _RequiredDescribeDBParametersMessageRequestTypeDef,
     _OptionalDescribeDBParametersMessageRequestTypeDef,
 ):
     pass
 
 
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
@@ -2129,14 +2264,37 @@
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
+
+class DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef(
+    _RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
+    _OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef",
     {
         "DBParameterGroupFamily": str,
     },
 )
 _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
@@ -2162,25 +2320,50 @@
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
@@ -2189,14 +2372,41 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
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
+        "Vpc": bool,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef(
+    _RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
+    _OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
     {
         "Engine": str,
     },
 )
 _OptionalDescribeOrderableDBInstanceOptionsMessageRequestTypeDef = TypedDict(
@@ -2217,14 +2427,26 @@
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
+
 DescribePendingMaintenanceActionsMessageRequestTypeDef = TypedDict(
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
@@ -2250,248 +2472,14 @@
 class ListTagsForResourceMessageRequestTypeDef(
     _RequiredListTagsForResourceMessageRequestTypeDef,
     _OptionalListTagsForResourceMessageRequestTypeDef,
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
-DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    {
-        "GlobalClusterIdentifier": str,
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
 DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef = TypedDict(
     "DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef",
     {
         "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
@@ -2512,24 +2500,24 @@
     total=False,
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
 
 GlobalClusterTypeDef = TypedDict(
     "GlobalClusterTypeDef",
     {
         "GlobalClusterIdentifier": str,
@@ -2541,35 +2529,14 @@
         "StorageEncrypted": bool,
         "DeletionProtection": bool,
         "GlobalClusterMembers": List[GlobalClusterMemberTypeDef],
     },
     total=False,
 )
 
-PendingModifiedValuesTypeDef = TypedDict(
-    "PendingModifiedValuesTypeDef",
-    {
-        "DBInstanceClass": str,
-        "AllocatedStorage": int,
-        "MasterUserPassword": str,
-        "Port": int,
-        "BackupRetentionPeriod": int,
-        "MultiAZ": bool,
-        "EngineVersion": str,
-        "LicenseModel": str,
-        "Iops": int,
-        "DBInstanceIdentifier": str,
-        "StorageType": str,
-        "CACertificateIdentifier": str,
-        "DBSubnetGroupName": str,
-        "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
-    },
-    total=False,
-)
-
 ResourcePendingMaintenanceActionsTypeDef = TypedDict(
     "ResourcePendingMaintenanceActionsTypeDef",
     {
         "ResourceIdentifier": str,
         "PendingMaintenanceActionDetails": List[PendingMaintenanceActionTypeDef],
     },
     total=False,
@@ -2587,15 +2554,15 @@
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
 
 DBSubnetGroupTypeDef = TypedDict(
     "DBSubnetGroupTypeDef",
     {
         "DBSubnetGroupName": str,
@@ -2604,199 +2571,168 @@
         "SubnetGroupStatus": str,
         "Subnets": List[SubnetTypeDef],
         "DBSubnetGroupArn": str,
     },
     total=False,
 )
 
+DBClusterTypeDef = TypedDict(
+    "DBClusterTypeDef",
+    {
+        "AllocatedStorage": int,
+        "AvailabilityZones": List[str],
+        "BackupRetentionPeriod": int,
+        "CharacterSetName": str,
+        "DatabaseName": str,
+        "DBClusterIdentifier": str,
+        "DBClusterParameterGroup": str,
+        "DBSubnetGroup": str,
+        "Status": str,
+        "PercentProgress": str,
+        "EarliestRestorableTime": datetime,
+        "Endpoint": str,
+        "ReaderEndpoint": str,
+        "MultiAZ": bool,
+        "Engine": str,
+        "EngineVersion": str,
+        "LatestRestorableTime": datetime,
+        "Port": int,
+        "MasterUsername": str,
+        "DBClusterOptionGroupMemberships": List[DBClusterOptionGroupStatusTypeDef],
+        "PreferredBackupWindow": str,
+        "PreferredMaintenanceWindow": str,
+        "ReplicationSourceIdentifier": str,
+        "ReadReplicaIdentifiers": List[str],
+        "DBClusterMembers": List[DBClusterMemberTypeDef],
+        "VpcSecurityGroups": List[VpcSecurityGroupMembershipTypeDef],
+        "HostedZoneId": str,
+        "StorageEncrypted": bool,
+        "KmsKeyId": str,
+        "DbClusterResourceId": str,
+        "DBClusterArn": str,
+        "AssociatedRoles": List[DBClusterRoleTypeDef],
+        "IAMDatabaseAuthenticationEnabled": bool,
+        "CloneGroupId": str,
+        "ClusterCreateTime": datetime,
+        "CopyTagsToSnapshot": bool,
+        "EnabledCloudwatchLogsExports": List[str],
+        "PendingModifiedValues": ClusterPendingModifiedValuesTypeDef,
+        "DeletionProtection": bool,
+        "CrossAccountClone": bool,
+        "AutomaticRestartTime": datetime,
+        "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationInfoTypeDef,
+        "GlobalClusterIdentifier": str,
+    },
+    total=False,
+)
+
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
-    },
-)
-
-CreateDBClusterResultTypeDef = TypedDict(
-    "CreateDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterMessageTypeDef = TypedDict(
-    "DBClusterMessageTypeDef",
-    {
-        "Marker": str,
-        "DBClusters": List[DBClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDBClusterResultTypeDef = TypedDict(
-    "DeleteDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-FailoverDBClusterResultTypeDef = TypedDict(
-    "FailoverDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ModifyDBClusterResultTypeDef = TypedDict(
-    "ModifyDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PromoteReadReplicaDBClusterResultTypeDef = TypedDict(
-    "PromoteReadReplicaDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreDBClusterFromSnapshotResultTypeDef = TypedDict(
-    "RestoreDBClusterFromSnapshotResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreDBClusterToPointInTimeResultTypeDef = TypedDict(
-    "RestoreDBClusterToPointInTimeResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDBClusterResultTypeDef = TypedDict(
-    "StartDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDBClusterResultTypeDef = TypedDict(
-    "StopDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
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
@@ -2804,15 +2740,15 @@
     total=False,
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
@@ -2873,67 +2809,148 @@
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
+    },
+)
+
+CreateDBClusterResultTypeDef = TypedDict(
+    "CreateDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DBClusterMessageTypeDef = TypedDict(
+    "DBClusterMessageTypeDef",
+    {
+        "Marker": str,
+        "DBClusters": List[DBClusterTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteDBClusterResultTypeDef = TypedDict(
+    "DeleteDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FailoverDBClusterResultTypeDef = TypedDict(
+    "FailoverDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ModifyDBClusterResultTypeDef = TypedDict(
+    "ModifyDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PromoteReadReplicaDBClusterResultTypeDef = TypedDict(
+    "PromoteReadReplicaDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RestoreDBClusterFromSnapshotResultTypeDef = TypedDict(
+    "RestoreDBClusterFromSnapshotResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RestoreDBClusterToPointInTimeResultTypeDef = TypedDict(
+    "RestoreDBClusterToPointInTimeResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartDBClusterResultTypeDef = TypedDict(
+    "StartDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopDBClusterResultTypeDef = TypedDict(
+    "StopDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
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
 
 RebootDBInstanceResultTypeDef = TypedDict(
     "RebootDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/type_defs.pyi` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/type_defs.pyi`

 * *Files 11% similar despite different names*

```diff
@@ -22,88 +22,89 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddRoleToDBClusterMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionMessageRequestTypeDef",
     "EventSubscriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
     "AvailabilityZoneTypeDef",
     "CharacterSetTypeDef",
     "CloudwatchLogsExportConfigurationTypeDef",
+    "PendingCloudwatchLogsExportsTypeDef",
     "DBClusterParameterGroupTypeDef",
     "DBClusterSnapshotTypeDef",
     "DBParameterGroupTypeDef",
+    "CreateDBClusterEndpointOutputTypeDef",
     "ServerlessV2ScalingConfigurationTypeDef",
     "CreateGlobalClusterMessageRequestTypeDef",
     "DBClusterEndpointTypeDef",
     "DBClusterMemberTypeDef",
     "DBClusterOptionGroupStatusTypeDef",
     "ParameterTypeDef",
+    "DBClusterParameterGroupNameMessageTypeDef",
     "DBClusterRoleTypeDef",
     "DBClusterSnapshotAttributeTypeDef",
     "ServerlessV2ScalingConfigurationInfoTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "TimezoneTypeDef",
     "UpgradeTargetTypeDef",
     "DBInstanceStatusInfoTypeDef",
     "DBParameterGroupStatusTypeDef",
     "DBSecurityGroupMembershipTypeDef",
     "DomainMembershipTypeDef",
     "EndpointTypeDef",
     "OptionGroupMembershipTypeDef",
+    "DBParameterGroupNameMessageTypeDef",
     "DeleteDBClusterEndpointMessageRequestTypeDef",
+    "DeleteDBClusterEndpointOutputTypeDef",
     "DeleteDBClusterMessageRequestTypeDef",
     "DeleteDBClusterParameterGroupMessageRequestTypeDef",
     "DeleteDBClusterSnapshotMessageRequestTypeDef",
     "DeleteDBInstanceMessageRequestTypeDef",
     "DeleteDBParameterGroupMessageRequestTypeDef",
     "DeleteDBSubnetGroupMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteGlobalClusterMessageRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     "DescribeGlobalClustersMessageRequestTypeDef",
     "DescribeValidDBInstanceModificationsMessageRequestTypeDef",
     "DoubleRangeTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventCategoriesMapTypeDef",
     "EventTypeDef",
     "FailoverDBClusterMessageRequestTypeDef",
     "FailoverGlobalClusterMessageRequestTypeDef",
     "GlobalClusterMemberTypeDef",
     "ModifyDBClusterEndpointMessageRequestTypeDef",
+    "ModifyDBClusterEndpointOutputTypeDef",
     "ModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBSubnetGroupMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyGlobalClusterMessageRequestTypeDef",
-    "PendingCloudwatchLogsExportsTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
     "PromoteReadReplicaDBClusterMessageRequestTypeDef",
     "RangeTypeDef",
     "RebootDBInstanceMessageRequestTypeDef",
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     "RemoveRoleFromDBClusterMessageRequestTypeDef",
     "RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDBClusterMessageRequestTypeDef",
     "StopDBClusterMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionResultTypeDef",
-    "CreateDBClusterEndpointOutputTypeDef",
     "CreateEventSubscriptionResultTypeDef",
-    "DBClusterParameterGroupNameMessageTypeDef",
-    "DBParameterGroupNameMessageTypeDef",
-    "DeleteDBClusterEndpointOutputTypeDef",
     "DeleteEventSubscriptionResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EventSubscriptionsMessageTypeDef",
-    "ModifyDBClusterEndpointOutputTypeDef",
     "ModifyEventSubscriptionResultTypeDef",
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CopyDBClusterParameterGroupMessageRequestTypeDef",
     "CopyDBClusterSnapshotMessageRequestTypeDef",
     "CopyDBParameterGroupMessageRequestTypeDef",
     "CreateDBClusterEndpointMessageRequestTypeDef",
@@ -113,14 +114,16 @@
     "CreateDBParameterGroupMessageRequestTypeDef",
     "CreateDBSubnetGroupMessageRequestTypeDef",
     "CreateEventSubscriptionMessageRequestTypeDef",
     "TagListMessageTypeDef",
     "OrderableDBInstanceOptionTypeDef",
     "SubnetTypeDef",
     "ModifyDBInstanceMessageRequestTypeDef",
+    "ClusterPendingModifiedValuesTypeDef",
+    "PendingModifiedValuesTypeDef",
     "CopyDBClusterParameterGroupResultTypeDef",
     "CreateDBClusterParameterGroupResultTypeDef",
     "DBClusterParameterGroupsMessageTypeDef",
     "CopyDBClusterSnapshotResultTypeDef",
     "CreateDBClusterSnapshotResultTypeDef",
     "DBClusterSnapshotMessageTypeDef",
     "DeleteDBClusterSnapshotResultTypeDef",
@@ -136,88 +139,86 @@
     "DBParameterGroupDetailsTypeDef",
     "EngineDefaultsTypeDef",
     "ModifyDBClusterParameterGroupMessageRequestTypeDef",
     "ModifyDBParameterGroupMessageRequestTypeDef",
     "ResetDBClusterParameterGroupMessageRequestTypeDef",
     "ResetDBParameterGroupMessageRequestTypeDef",
     "DBClusterSnapshotAttributesResultTypeDef",
-    "DBClusterTypeDef",
     "DBEngineVersionTypeDef",
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
+    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
     "DescribeDBInstancesMessageRequestTypeDef",
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
     "DescribeDBParameterGroupsMessageRequestTypeDef",
+    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
     "DescribeDBParametersMessageRequestTypeDef",
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
     "DescribeEngineDefaultClusterParametersMessageRequestTypeDef",
+    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     "DescribeEngineDefaultParametersMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     "DescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
-    "DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef",
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
-    "DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef",
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
-    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
-    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef",
     "DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef",
     "EventCategoriesMessageTypeDef",
     "EventsMessageTypeDef",
     "GlobalClusterTypeDef",
-    "PendingModifiedValuesTypeDef",
     "ResourcePendingMaintenanceActionsTypeDef",
     "ValidStorageOptionsTypeDef",
     "OrderableDBInstanceOptionsMessageTypeDef",
     "DBSubnetGroupTypeDef",
+    "DBClusterTypeDef",
     "DescribeEngineDefaultClusterParametersResultTypeDef",
     "DescribeEngineDefaultParametersResultTypeDef",
     "DescribeDBClusterSnapshotAttributesResultTypeDef",
     "ModifyDBClusterSnapshotAttributeResultTypeDef",
-    "CreateDBClusterResultTypeDef",
-    "DBClusterMessageTypeDef",
-    "DeleteDBClusterResultTypeDef",
-    "FailoverDBClusterResultTypeDef",
-    "ModifyDBClusterResultTypeDef",
-    "PromoteReadReplicaDBClusterResultTypeDef",
-    "RestoreDBClusterFromSnapshotResultTypeDef",
-    "RestoreDBClusterToPointInTimeResultTypeDef",
-    "StartDBClusterResultTypeDef",
-    "StopDBClusterResultTypeDef",
     "DBEngineVersionMessageTypeDef",
     "CreateGlobalClusterResultTypeDef",
     "DeleteGlobalClusterResultTypeDef",
     "FailoverGlobalClusterResultTypeDef",
     "GlobalClustersMessageTypeDef",
     "ModifyGlobalClusterResultTypeDef",
     "RemoveFromGlobalClusterResultTypeDef",
     "ApplyPendingMaintenanceActionResultTypeDef",
     "PendingMaintenanceActionsMessageTypeDef",
     "ValidDBInstanceModificationsMessageTypeDef",
     "CreateDBSubnetGroupResultTypeDef",
     "DBInstanceTypeDef",
     "DBSubnetGroupMessageTypeDef",
     "ModifyDBSubnetGroupResultTypeDef",
+    "CreateDBClusterResultTypeDef",
+    "DBClusterMessageTypeDef",
+    "DeleteDBClusterResultTypeDef",
+    "FailoverDBClusterResultTypeDef",
+    "ModifyDBClusterResultTypeDef",
+    "PromoteReadReplicaDBClusterResultTypeDef",
+    "RestoreDBClusterFromSnapshotResultTypeDef",
+    "RestoreDBClusterToPointInTimeResultTypeDef",
+    "StartDBClusterResultTypeDef",
+    "StopDBClusterResultTypeDef",
     "DescribeValidDBInstanceModificationsResultTypeDef",
     "CreateDBInstanceResultTypeDef",
     "DBInstanceMessageTypeDef",
     "DeleteDBInstanceResultTypeDef",
     "ModifyDBInstanceResultTypeDef",
     "RebootDBInstanceResultTypeDef",
 )
@@ -264,25 +265,14 @@
         "EventCategoriesList": List[str],
         "Enabled": bool,
         "EventSubscriptionArn": str,
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
@@ -319,14 +309,23 @@
     {
         "EnableLogTypes": Sequence[str],
         "DisableLogTypes": Sequence[str],
     },
     total=False,
 )
 
+PendingCloudwatchLogsExportsTypeDef = TypedDict(
+    "PendingCloudwatchLogsExportsTypeDef",
+    {
+        "LogTypesToEnable": List[str],
+        "LogTypesToDisable": List[str],
+    },
+    total=False,
+)
+
 DBClusterParameterGroupTypeDef = TypedDict(
     "DBClusterParameterGroupTypeDef",
     {
         "DBClusterParameterGroupName": str,
         "DBParameterGroupFamily": str,
         "Description": str,
         "DBClusterParameterGroupArn": str,
@@ -368,14 +367,31 @@
         "DBParameterGroupFamily": str,
         "Description": str,
         "DBParameterGroupArn": str,
     },
     total=False,
 )
 
+CreateDBClusterEndpointOutputTypeDef = TypedDict(
+    "CreateDBClusterEndpointOutputTypeDef",
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
 ServerlessV2ScalingConfigurationTypeDef = TypedDict(
     "ServerlessV2ScalingConfigurationTypeDef",
     {
         "MinCapacity": float,
         "MaxCapacity": float,
     },
     total=False,
@@ -455,14 +471,22 @@
         "IsModifiable": bool,
         "MinimumEngineVersion": str,
         "ApplyMethod": ApplyMethodType,
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
@@ -572,21 +596,46 @@
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
 DeleteDBClusterEndpointMessageRequestTypeDef = TypedDict(
     "DeleteDBClusterEndpointMessageRequestTypeDef",
     {
         "DBClusterEndpointIdentifier": str,
     },
 )
 
+DeleteDBClusterEndpointOutputTypeDef = TypedDict(
+    "DeleteDBClusterEndpointOutputTypeDef",
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
 _RequiredDeleteDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredDeleteDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 _OptionalDeleteDBClusterMessageRequestTypeDef = TypedDict(
@@ -669,24 +718,14 @@
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
 
@@ -695,14 +734,23 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
+    {
+        "GlobalClusterIdentifier": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGlobalClustersMessageRequestTypeDef = TypedDict(
     "DescribeGlobalClustersMessageRequestTypeDef",
     {
         "GlobalClusterIdentifier": str,
         "MaxRecords": int,
         "Marker": str,
     },
@@ -721,14 +769,21 @@
     {
         "From": float,
         "To": float,
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
 EventCategoriesMapTypeDef = TypedDict(
     "EventCategoriesMapTypeDef",
     {
         "SourceType": str,
         "EventCategories": List[str],
     },
     total=False,
@@ -792,14 +847,31 @@
 
 class ModifyDBClusterEndpointMessageRequestTypeDef(
     _RequiredModifyDBClusterEndpointMessageRequestTypeDef,
     _OptionalModifyDBClusterEndpointMessageRequestTypeDef,
 ):
     pass
 
+ModifyDBClusterEndpointOutputTypeDef = TypedDict(
+    "ModifyDBClusterEndpointOutputTypeDef",
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
 _RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     {
         "DBClusterSnapshotIdentifier": str,
         "AttributeName": str,
     },
 )
@@ -881,19 +953,20 @@
 
 class ModifyGlobalClusterMessageRequestTypeDef(
     _RequiredModifyGlobalClusterMessageRequestTypeDef,
     _OptionalModifyGlobalClusterMessageRequestTypeDef,
 ):
     pass
 
-PendingCloudwatchLogsExportsTypeDef = TypedDict(
-    "PendingCloudwatchLogsExportsTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "LogTypesToEnable": List[str],
-        "LogTypesToDisable": List[str],
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
     total=False,
 )
 
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
@@ -984,14 +1057,25 @@
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
 StartDBClusterMessageRequestTypeDef = TypedDict(
     "StartDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
     },
 )
 
@@ -1002,130 +1086,56 @@
     },
 )
 
 AddSourceIdentifierToSubscriptionResultTypeDef = TypedDict(
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDBClusterEndpointOutputTypeDef = TypedDict(
-    "CreateDBClusterEndpointOutputTypeDef",
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEventSubscriptionResultTypeDef = TypedDict(
     "CreateEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
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
-DeleteDBClusterEndpointOutputTypeDef = TypedDict(
-    "DeleteDBClusterEndpointOutputTypeDef",
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventSubscriptionResultTypeDef = TypedDict(
     "DeleteEventSubscriptionResultTypeDef",
     {
         "EventSubscription": EventSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
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
-    },
-)
-
-ModifyDBClusterEndpointOutputTypeDef = TypedDict(
-    "ModifyDBClusterEndpointOutputTypeDef",
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
@@ -1271,14 +1281,15 @@
 
 _RequiredCreateDBInstanceMessageRequestTypeDef = TypedDict(
     "_RequiredCreateDBInstanceMessageRequestTypeDef",
     {
         "DBInstanceIdentifier": str,
         "DBInstanceClass": str,
         "Engine": str,
+        "DBClusterIdentifier": str,
     },
 )
 _OptionalCreateDBInstanceMessageRequestTypeDef = TypedDict(
     "_OptionalCreateDBInstanceMessageRequestTypeDef",
     {
         "DBName": str,
         "AllocatedStorage": int,
@@ -1298,15 +1309,14 @@
         "AutoMinorVersionUpgrade": bool,
         "LicenseModel": str,
         "Iops": int,
         "OptionGroupName": str,
         "CharacterSetName": str,
         "PubliclyAccessible": bool,
         "Tags": Sequence[TagTypeDef],
-        "DBClusterIdentifier": str,
         "StorageType": str,
         "TdeCredentialArn": str,
         "TdeCredentialPassword": str,
         "StorageEncrypted": bool,
         "KmsKeyId": str,
         "Domain": str,
         "CopyTagsToSnapshot": bool,
@@ -1398,15 +1408,15 @@
 ):
     pass
 
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
@@ -1494,94 +1504,129 @@
 )
 
 class ModifyDBInstanceMessageRequestTypeDef(
     _RequiredModifyDBInstanceMessageRequestTypeDef, _OptionalModifyDBInstanceMessageRequestTypeDef
 ):
     pass
 
+ClusterPendingModifiedValuesTypeDef = TypedDict(
+    "ClusterPendingModifiedValuesTypeDef",
+    {
+        "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
+        "DBClusterIdentifier": str,
+        "IAMDatabaseAuthenticationEnabled": bool,
+        "EngineVersion": str,
+        "BackupRetentionPeriod": int,
+        "AllocatedStorage": int,
+        "Iops": int,
+    },
+    total=False,
+)
+
+PendingModifiedValuesTypeDef = TypedDict(
+    "PendingModifiedValuesTypeDef",
+    {
+        "DBInstanceClass": str,
+        "AllocatedStorage": int,
+        "MasterUserPassword": str,
+        "Port": int,
+        "BackupRetentionPeriod": int,
+        "MultiAZ": bool,
+        "EngineVersion": str,
+        "LicenseModel": str,
+        "Iops": int,
+        "DBInstanceIdentifier": str,
+        "StorageType": str,
+        "CACertificateIdentifier": str,
+        "DBSubnetGroupName": str,
+        "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
+    },
+    total=False,
+)
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
@@ -1733,33 +1778,33 @@
     pass
 
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
@@ -1832,62 +1877,14 @@
     {
         "DBClusterSnapshotIdentifier": str,
         "DBClusterSnapshotAttributes": List[DBClusterSnapshotAttributeTypeDef],
     },
     total=False,
 )
 
-DBClusterTypeDef = TypedDict(
-    "DBClusterTypeDef",
-    {
-        "AllocatedStorage": int,
-        "AvailabilityZones": List[str],
-        "BackupRetentionPeriod": int,
-        "CharacterSetName": str,
-        "DatabaseName": str,
-        "DBClusterIdentifier": str,
-        "DBClusterParameterGroup": str,
-        "DBSubnetGroup": str,
-        "Status": str,
-        "PercentProgress": str,
-        "EarliestRestorableTime": datetime,
-        "Endpoint": str,
-        "ReaderEndpoint": str,
-        "MultiAZ": bool,
-        "Engine": str,
-        "EngineVersion": str,
-        "LatestRestorableTime": datetime,
-        "Port": int,
-        "MasterUsername": str,
-        "DBClusterOptionGroupMemberships": List[DBClusterOptionGroupStatusTypeDef],
-        "PreferredBackupWindow": str,
-        "PreferredMaintenanceWindow": str,
-        "ReplicationSourceIdentifier": str,
-        "ReadReplicaIdentifiers": List[str],
-        "DBClusterMembers": List[DBClusterMemberTypeDef],
-        "VpcSecurityGroups": List[VpcSecurityGroupMembershipTypeDef],
-        "HostedZoneId": str,
-        "StorageEncrypted": bool,
-        "KmsKeyId": str,
-        "DbClusterResourceId": str,
-        "DBClusterArn": str,
-        "AssociatedRoles": List[DBClusterRoleTypeDef],
-        "IAMDatabaseAuthenticationEnabled": bool,
-        "CloneGroupId": str,
-        "ClusterCreateTime": datetime,
-        "CopyTagsToSnapshot": bool,
-        "EnabledCloudwatchLogsExports": List[str],
-        "DeletionProtection": bool,
-        "CrossAccountClone": bool,
-        "AutomaticRestartTime": datetime,
-        "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationInfoTypeDef,
-    },
-    total=False,
-)
-
 DBEngineVersionTypeDef = TypedDict(
     "DBEngineVersionTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "DBParameterGroupFamily": str,
         "DBEngineDescription": str,
@@ -1900,37 +1897,80 @@
         "SupportsLogExportsToCloudwatchLogs": bool,
         "SupportsReadReplica": bool,
         "SupportsGlobalDatabases": bool,
     },
     total=False,
 )
 
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
@@ -1946,14 +1986,28 @@
 
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
+
 DescribeDBClusterSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeDBClusterSnapshotsMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
         "DBClusterSnapshotIdentifier": str,
         "SnapshotType": str,
         "Filters": Sequence[FilterTypeDef],
@@ -1961,25 +2015,50 @@
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
@@ -1988,36 +2067,78 @@
         "DefaultOnly": bool,
         "ListSupportedCharacterSets": bool,
         "ListSupportedTimezones": bool,
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
 
+DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef",
+    {
+        "DBParameterGroupName": str,
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
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
@@ -2033,14 +2154,24 @@
 
 class DescribeDBParametersMessageRequestTypeDef(
     _RequiredDescribeDBParametersMessageRequestTypeDef,
     _OptionalDescribeDBParametersMessageRequestTypeDef,
 ):
     pass
 
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
@@ -2066,14 +2197,35 @@
 
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
+
 _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeEngineDefaultParametersMessageRequestTypeDef",
     {
         "DBParameterGroupFamily": str,
     },
 )
 _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
@@ -2097,25 +2249,50 @@
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
@@ -2124,14 +2301,39 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
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
@@ -2150,14 +2352,26 @@
 
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
+
 DescribePendingMaintenanceActionsMessageRequestTypeDef = TypedDict(
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "Marker": str,
         "MaxRecords": int,
@@ -2181,240 +2395,14 @@
 
 class ListTagsForResourceMessageRequestTypeDef(
     _RequiredListTagsForResourceMessageRequestTypeDef,
     _OptionalListTagsForResourceMessageRequestTypeDef,
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
-class DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef(
-    _RequiredDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    _OptionalDescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-):
-    pass
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
-class DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef(
-    _RequiredDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    _OptionalDescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-):
-    pass
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
-class DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef(
-    _RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    _OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-):
-    pass
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
-DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef = TypedDict(
-    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
-    {
-        "GlobalClusterIdentifier": str,
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
-        "Vpc": bool,
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef(
-    _RequiredDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    _OptionalDescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-):
-    pass
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
 DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef = TypedDict(
     "DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef",
     {
         "DBInstanceIdentifier": str,
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
@@ -2435,24 +2423,24 @@
     total=False,
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
 
 GlobalClusterTypeDef = TypedDict(
     "GlobalClusterTypeDef",
     {
         "GlobalClusterIdentifier": str,
@@ -2464,35 +2452,14 @@
         "StorageEncrypted": bool,
         "DeletionProtection": bool,
         "GlobalClusterMembers": List[GlobalClusterMemberTypeDef],
     },
     total=False,
 )
 
-PendingModifiedValuesTypeDef = TypedDict(
-    "PendingModifiedValuesTypeDef",
-    {
-        "DBInstanceClass": str,
-        "AllocatedStorage": int,
-        "MasterUserPassword": str,
-        "Port": int,
-        "BackupRetentionPeriod": int,
-        "MultiAZ": bool,
-        "EngineVersion": str,
-        "LicenseModel": str,
-        "Iops": int,
-        "DBInstanceIdentifier": str,
-        "StorageType": str,
-        "CACertificateIdentifier": str,
-        "DBSubnetGroupName": str,
-        "PendingCloudwatchLogsExports": PendingCloudwatchLogsExportsTypeDef,
-    },
-    total=False,
-)
-
 ResourcePendingMaintenanceActionsTypeDef = TypedDict(
     "ResourcePendingMaintenanceActionsTypeDef",
     {
         "ResourceIdentifier": str,
         "PendingMaintenanceActionDetails": List[PendingMaintenanceActionTypeDef],
     },
     total=False,
@@ -2510,15 +2477,15 @@
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
 
 DBSubnetGroupTypeDef = TypedDict(
     "DBSubnetGroupTypeDef",
     {
         "DBSubnetGroupName": str,
@@ -2527,199 +2494,168 @@
         "SubnetGroupStatus": str,
         "Subnets": List[SubnetTypeDef],
         "DBSubnetGroupArn": str,
     },
     total=False,
 )
 
+DBClusterTypeDef = TypedDict(
+    "DBClusterTypeDef",
+    {
+        "AllocatedStorage": int,
+        "AvailabilityZones": List[str],
+        "BackupRetentionPeriod": int,
+        "CharacterSetName": str,
+        "DatabaseName": str,
+        "DBClusterIdentifier": str,
+        "DBClusterParameterGroup": str,
+        "DBSubnetGroup": str,
+        "Status": str,
+        "PercentProgress": str,
+        "EarliestRestorableTime": datetime,
+        "Endpoint": str,
+        "ReaderEndpoint": str,
+        "MultiAZ": bool,
+        "Engine": str,
+        "EngineVersion": str,
+        "LatestRestorableTime": datetime,
+        "Port": int,
+        "MasterUsername": str,
+        "DBClusterOptionGroupMemberships": List[DBClusterOptionGroupStatusTypeDef],
+        "PreferredBackupWindow": str,
+        "PreferredMaintenanceWindow": str,
+        "ReplicationSourceIdentifier": str,
+        "ReadReplicaIdentifiers": List[str],
+        "DBClusterMembers": List[DBClusterMemberTypeDef],
+        "VpcSecurityGroups": List[VpcSecurityGroupMembershipTypeDef],
+        "HostedZoneId": str,
+        "StorageEncrypted": bool,
+        "KmsKeyId": str,
+        "DbClusterResourceId": str,
+        "DBClusterArn": str,
+        "AssociatedRoles": List[DBClusterRoleTypeDef],
+        "IAMDatabaseAuthenticationEnabled": bool,
+        "CloneGroupId": str,
+        "ClusterCreateTime": datetime,
+        "CopyTagsToSnapshot": bool,
+        "EnabledCloudwatchLogsExports": List[str],
+        "PendingModifiedValues": ClusterPendingModifiedValuesTypeDef,
+        "DeletionProtection": bool,
+        "CrossAccountClone": bool,
+        "AutomaticRestartTime": datetime,
+        "ServerlessV2ScalingConfiguration": ServerlessV2ScalingConfigurationInfoTypeDef,
+        "GlobalClusterIdentifier": str,
+    },
+    total=False,
+)
+
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
-    },
-)
-
-CreateDBClusterResultTypeDef = TypedDict(
-    "CreateDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DBClusterMessageTypeDef = TypedDict(
-    "DBClusterMessageTypeDef",
-    {
-        "Marker": str,
-        "DBClusters": List[DBClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDBClusterResultTypeDef = TypedDict(
-    "DeleteDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-FailoverDBClusterResultTypeDef = TypedDict(
-    "FailoverDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ModifyDBClusterResultTypeDef = TypedDict(
-    "ModifyDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PromoteReadReplicaDBClusterResultTypeDef = TypedDict(
-    "PromoteReadReplicaDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreDBClusterFromSnapshotResultTypeDef = TypedDict(
-    "RestoreDBClusterFromSnapshotResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreDBClusterToPointInTimeResultTypeDef = TypedDict(
-    "RestoreDBClusterToPointInTimeResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDBClusterResultTypeDef = TypedDict(
-    "StartDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDBClusterResultTypeDef = TypedDict(
-    "StopDBClusterResultTypeDef",
-    {
-        "DBCluster": DBClusterTypeDef,
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
@@ -2727,15 +2663,15 @@
     total=False,
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
@@ -2796,67 +2732,148 @@
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
+    },
+)
+
+CreateDBClusterResultTypeDef = TypedDict(
+    "CreateDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DBClusterMessageTypeDef = TypedDict(
+    "DBClusterMessageTypeDef",
+    {
+        "Marker": str,
+        "DBClusters": List[DBClusterTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteDBClusterResultTypeDef = TypedDict(
+    "DeleteDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FailoverDBClusterResultTypeDef = TypedDict(
+    "FailoverDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ModifyDBClusterResultTypeDef = TypedDict(
+    "ModifyDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PromoteReadReplicaDBClusterResultTypeDef = TypedDict(
+    "PromoteReadReplicaDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RestoreDBClusterFromSnapshotResultTypeDef = TypedDict(
+    "RestoreDBClusterFromSnapshotResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RestoreDBClusterToPointInTimeResultTypeDef = TypedDict(
+    "RestoreDBClusterToPointInTimeResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartDBClusterResultTypeDef = TypedDict(
+    "StartDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopDBClusterResultTypeDef = TypedDict(
+    "StopDBClusterResultTypeDef",
+    {
+        "DBCluster": DBClusterTypeDef,
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
 
 RebootDBInstanceResultTypeDef = TypedDict(
     "RebootDBInstanceResultTypeDef",
     {
         "DBInstance": DBInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/waiter.py` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune/waiter.pyi` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/PKG-INFO` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-neptune
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Neptune 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Neptune 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-neptune"></a>
 
 # types-aiobotocore-neptune
 
 [![PyPI - types-aiobotocore-neptune](https://img.shields.io/pypi/v/types-aiobotocore-neptune.svg?color=blue)](https://pypi.org/project/types-aiobotocore-neptune)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-neptune.svg?color=blue)](https://pypi.org/project/types-aiobotocore-neptune)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-neptune?color=blue)](https://pypistats.org/packages/types-aiobotocore-neptune)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Neptune 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
+[aiobotocore.Neptune 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html#Neptune)
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
 [types-aiobotocore-neptune docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_neptune/).
 
 See how it helps to find and fix potential bugs:
 
@@ -424,88 +424,89 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_neptune.type_defs import (
     AddRoleToDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     CharacterSetTypeDef,
     CloudwatchLogsExportConfigurationTypeDef,
+    PendingCloudwatchLogsExportsTypeDef,
     DBClusterParameterGroupTypeDef,
     DBClusterSnapshotTypeDef,
     DBParameterGroupTypeDef,
+    CreateDBClusterEndpointOutputTypeDef,
     ServerlessV2ScalingConfigurationTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     DBClusterEndpointTypeDef,
     DBClusterMemberTypeDef,
     DBClusterOptionGroupStatusTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     ServerlessV2ScalingConfigurationInfoTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     TimezoneTypeDef,
     UpgradeTargetTypeDef,
     DBInstanceStatusInfoTypeDef,
     DBParameterGroupStatusTypeDef,
     DBSecurityGroupMembershipTypeDef,
     DomainMembershipTypeDef,
     EndpointTypeDef,
     OptionGroupMembershipTypeDef,
+    DBParameterGroupNameMessageTypeDef,
     DeleteDBClusterEndpointMessageRequestTypeDef,
+    DeleteDBClusterEndpointOutputTypeDef,
     DeleteDBClusterMessageRequestTypeDef,
     DeleteDBClusterParameterGroupMessageRequestTypeDef,
     DeleteDBClusterSnapshotMessageRequestTypeDef,
     DeleteDBInstanceMessageRequestTypeDef,
     DeleteDBParameterGroupMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
     DescribeValidDBInstanceModificationsMessageRequestTypeDef,
     DoubleRangeTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     FailoverGlobalClusterMessageRequestTypeDef,
     GlobalClusterMemberTypeDef,
     ModifyDBClusterEndpointMessageRequestTypeDef,
+    ModifyDBClusterEndpointOutputTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
-    PendingCloudwatchLogsExportsTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PromoteReadReplicaDBClusterMessageRequestTypeDef,
     RangeTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveRoleFromDBClusterMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StopDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
-    CreateDBClusterEndpointOutputTypeDef,
     CreateEventSubscriptionResultTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
-    DBParameterGroupNameMessageTypeDef,
-    DeleteDBClusterEndpointOutputTypeDef,
     DeleteEventSubscriptionResultTypeDef,
-    EmptyResponseMetadataTypeDef,
     EventSubscriptionsMessageTypeDef,
-    ModifyDBClusterEndpointOutputTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopyDBClusterParameterGroupMessageRequestTypeDef,
     CopyDBClusterSnapshotMessageRequestTypeDef,
     CopyDBParameterGroupMessageRequestTypeDef,
     CreateDBClusterEndpointMessageRequestTypeDef,
@@ -515,14 +516,16 @@
     CreateDBParameterGroupMessageRequestTypeDef,
     CreateDBSubnetGroupMessageRequestTypeDef,
     CreateEventSubscriptionMessageRequestTypeDef,
     TagListMessageTypeDef,
     OrderableDBInstanceOptionTypeDef,
     SubnetTypeDef,
     ModifyDBInstanceMessageRequestTypeDef,
+    ClusterPendingModifiedValuesTypeDef,
+    PendingModifiedValuesTypeDef,
     CopyDBClusterParameterGroupResultTypeDef,
     CreateDBClusterParameterGroupResultTypeDef,
     DBClusterParameterGroupsMessageTypeDef,
     CopyDBClusterSnapshotResultTypeDef,
     CreateDBClusterSnapshotResultTypeDef,
     DBClusterSnapshotMessageTypeDef,
     DeleteDBClusterSnapshotResultTypeDef,
@@ -538,88 +541,86 @@
     DBParameterGroupDetailsTypeDef,
     EngineDefaultsTypeDef,
     ModifyDBClusterParameterGroupMessageRequestTypeDef,
     ModifyDBParameterGroupMessageRequestTypeDef,
     ResetDBClusterParameterGroupMessageRequestTypeDef,
     ResetDBParameterGroupMessageRequestTypeDef,
     DBClusterSnapshotAttributesResultTypeDef,
-    DBClusterTypeDef,
     DBEngineVersionTypeDef,
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
+    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
     DescribeDBInstancesMessageRequestTypeDef,
+    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
     DescribeDBParameterGroupsMessageRequestTypeDef,
+    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
     DescribeDBParametersMessageRequestTypeDef,
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeDBClusterEndpointsMessageDescribeDBClusterEndpointsPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBParameterGroupsMessageDescribeDBParameterGroupsPaginateTypeDef,
-    DescribeDBParametersMessageDescribeDBParametersPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
-    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
-    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribeDBInstancesMessageDBInstanceAvailableWaitTypeDef,
     DescribeDBInstancesMessageDBInstanceDeletedWaitTypeDef,
     EventCategoriesMessageTypeDef,
     EventsMessageTypeDef,
     GlobalClusterTypeDef,
-    PendingModifiedValuesTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
     ValidStorageOptionsTypeDef,
     OrderableDBInstanceOptionsMessageTypeDef,
     DBSubnetGroupTypeDef,
+    DBClusterTypeDef,
     DescribeEngineDefaultClusterParametersResultTypeDef,
     DescribeEngineDefaultParametersResultTypeDef,
     DescribeDBClusterSnapshotAttributesResultTypeDef,
     ModifyDBClusterSnapshotAttributeResultTypeDef,
-    CreateDBClusterResultTypeDef,
-    DBClusterMessageTypeDef,
-    DeleteDBClusterResultTypeDef,
-    FailoverDBClusterResultTypeDef,
-    ModifyDBClusterResultTypeDef,
-    PromoteReadReplicaDBClusterResultTypeDef,
-    RestoreDBClusterFromSnapshotResultTypeDef,
-    RestoreDBClusterToPointInTimeResultTypeDef,
-    StartDBClusterResultTypeDef,
-    StopDBClusterResultTypeDef,
     DBEngineVersionMessageTypeDef,
     CreateGlobalClusterResultTypeDef,
     DeleteGlobalClusterResultTypeDef,
     FailoverGlobalClusterResultTypeDef,
     GlobalClustersMessageTypeDef,
     ModifyGlobalClusterResultTypeDef,
     RemoveFromGlobalClusterResultTypeDef,
     ApplyPendingMaintenanceActionResultTypeDef,
     PendingMaintenanceActionsMessageTypeDef,
     ValidDBInstanceModificationsMessageTypeDef,
     CreateDBSubnetGroupResultTypeDef,
     DBInstanceTypeDef,
     DBSubnetGroupMessageTypeDef,
     ModifyDBSubnetGroupResultTypeDef,
+    CreateDBClusterResultTypeDef,
+    DBClusterMessageTypeDef,
+    DeleteDBClusterResultTypeDef,
+    FailoverDBClusterResultTypeDef,
+    ModifyDBClusterResultTypeDef,
+    PromoteReadReplicaDBClusterResultTypeDef,
+    RestoreDBClusterFromSnapshotResultTypeDef,
+    RestoreDBClusterToPointInTimeResultTypeDef,
+    StartDBClusterResultTypeDef,
+    StopDBClusterResultTypeDef,
     DescribeValidDBInstanceModificationsResultTypeDef,
     CreateDBInstanceResultTypeDef,
     DBInstanceMessageTypeDef,
     DeleteDBInstanceResultTypeDef,
     ModifyDBInstanceResultTypeDef,
     RebootDBInstanceResultTypeDef,
 )
@@ -632,43 +633,43 @@
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

### Comparing `types-aiobotocore-neptune-2.5.0.post1/types_aiobotocore_neptune.egg-info/SOURCES.txt` & `types-aiobotocore-neptune-2.5.1/types_aiobotocore_neptune.egg-info/SOURCES.txt`

 * *Files identical despite different names*

